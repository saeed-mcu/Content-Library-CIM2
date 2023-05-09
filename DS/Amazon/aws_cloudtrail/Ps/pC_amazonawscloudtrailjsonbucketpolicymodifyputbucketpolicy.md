#### Parser Content
```Java
{
Name = amazon-awscloudtrail-json-bucket-policy-modify-putbucketpolicy
  Vendor = Amazon
  Product = AWS CloudTrail
  TimeFormat = """yyyy-MM-dd'T'HH:mm:ss.SSSSSSZ"""
  ParserVersion = "v1.0.0"
  Conditions = [ """AwsApiCall""", """"eventName":"PutBucketPolicy"""" ] 
  Fields = ${AwsParserTemplates.aws-cloudtrail-json.Fields}[
  """"+Sid\\?":\s*\{?\[?({policy_sids}[^\]\}]+)\]?\}?Effect"""",
  """"+bucketPolicy\\*"+:\s*\{[^\[]+({policy_content}"+Statement\\*"+[^\]]+\])""",
  """"+Effect\\?":\s*\\?"Allow\\?".+?Principal\\?":\s*\{?\[?({allowed_users}[^\]\}]+)\]?\}?"Action?""",
  """"+Effect\\?":\s*\\?"Allow\\?".+?Action\\?":\s*\[?({allowed_permissions}[^\.\]\}]+)\]?.*"Resource?""",
  """"+Effect\\?":\s*\\?"Allow\\?".+?Resource\\?":\s*\{?\[?({allowed_resources}[^\]\}]+)\]?\}?""",
  """"+Effect\\?":\s*\\?"Allow\\?".+?Condition\\?":\s*\[?({allowed_conditions}[^\.\]\}]+)\]?"""",
  """"+Effect\\?":\s*\\?"Deny\\?".+?Principal\\?":\s*\{?\[?({denied_users}[^\]\}]+)\]?\}?"Action?""",
  """"+Effect\\?":\s*\\?"Deny\\?".+?Action\\?":\s*\[?({denied_permissions}[^\.\]\}]+)\]?.*"Resource?""",
  """"+Effect\\?":\s*\\?"Deny\\?".+?Resource\\?":\s*\{?\[?({denied_resources}[^\]\}]+)\]?\}?""",
  """"+requestParameters.+?bucketName\\?":\s*\\?"({bucket_name}[^"]+?)\\?"""",
  """"+requestParameters.+?Host\\?":\s*\\?"({bucket_host}[^"]+?)\\?"""",
  """"+resources.+?(?:ARN|arn)\\?":\s*\\?"({bucket_arn}[^"]+?)\\?"""",
  ]
  DupFields = ["result->failure_code"]

aws-cloudtrail-json = {
    Vendor = Amazon
    Product = AWS CloudTrail
    TimeFormat = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
    Fields = [
      """"userIdentity":\{("[^,]+,)*"type"\\?:\s*\\?"({user_type}[^"]+?)\\?"""",
      """"userIdentity":\{("[^,]+,)*"arn"\\?:\s*\\?"({user_arn}[^"]+?)\\?"""",
      """"userIdentity":\{("[^,]+,)*"accountId\\?"+\s*:\s*\\?"+?({aws_account}[^"]+?)\\?"+\s*[,\]\}]""",
      """"userIdentity":\{("[^,]+,)*"principalId\\?"+\s*:\s*\\?"+?({principal_id}[^"]+?)\\?"+\s*[,\]\}]""",
      """"userIdentity":\{("[^,]+,)*"attributes":\{("[^,]+,)*"mfaAuthenticated"\\?:\s*\\?"({mfa}[^"]+?)\\?"""",
      """"assumedRoleUser":\{("[^,]+,)*"arn"\s*:\s*"({assumed_role_arn}[^"]+)\\?""""
      """"eventTime"+\s*:\s*"+?(|({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d)Z?)"+\s*[,\]\}]""",
      """"eventSource"+\s*:\s*"+?(|({service_name}[^"]+))"+\s*[,\]\}]""",
      """"eventName"+\s*:\s*"+?(|({operation}[^"]+))"+\s*[,\]\}]""",
      """"awsRegion"\s*:\s*"({region}[^"]+)"""",
      """"sourceIPAddress"+\s*:\s*"+?(?:({src_ip}((([0-9a-fA-F.]{1,4}):{1,2}){7}([0-9a-fA-F]){1,4})|(((25[0-5]|(2[0-4]|1\d|[0-9]|)\d)\.?\b){4}))(:({src_port}\d+))?|({src_host}[^"]+))"+\s*[,\]\}]""",
      """"userAgent"\s*:\s*"\[?(|({user_agent}[^"]+?))\]?"""",
      """"eventID\\?"+:\\?"+({event_code}[^"\\]+)\\?"""",
      """"eventType"+\s*:\s*"+?(|({event_category}[^"]+))"+\s*[,\]\}]""",
      """"errorCode"\s*:\s*"({result}[^"]+)"""",
      """"errorMessage"\s*:\s*"({failure_reason}[^"]+)"""",
      """"readOnly"\s*:\s*({readonly}[^",\}]+)("|,|\}\s*$)""",
      """"vpcEndpointId":"({vpc}[^"]+)""",
      """"+requestParameters":\{("[^,]+,)*"roleSessionName\\?":\s*\\?"({session_name}[^"]+?)\\?"""",
      """"+responseElements":\{"assumedRoleUser":\{("[^,]+,)*"assumedRoleId\\?":\s*\\?"({assumedRoleId}[^"]+?)\\?"""",
      """"credentials":\{"accessKeyId":"({accessKeyId}[^"]+?)\\?"""",
      #AWS CloudTrail user regexes
      """\Wsuser=[^=]*?(({email_address}[^@=\s\/:]+@[^=\.\s\/:]+\.[^\s=\/:]+?)|({user}[^\\\/@=]+?)(@[^=]+?)?)(\s+\w+=|\s*$)""",
      """"userName\\?":\s*\\?"(({email_address}[^"@]+@[^"\.]+\.[^"]+)|({user}[^"]+?)(@({domain}[^@"]+))?)\\?"""",
      """"userIdentity\\?":.+?"arn\\?":\s*\\?"arn:aws:sts::\d+:assumed-role\/([^\/"]+\/)(AssumeRoleSession|((?![\w\-\.]{30,})(({email_address}[^"@]+@[^"\.]+\.[^"]+)|({user}[^"]+?)(@({domain}[^@"]+))?)))\\?"""",
      """"sourceIdentity\\?":\s*\\?"(({email_address}[^"@]+@[^"\.]+\.[^"]+)|({user}[^"]+?)(@({domain}[^@"]+))?)\\?"""",
      """"userIdentity\\?":.+?"AssumedRole\\?".+?"principalId\\?":\s*\\?"[A-Z\d]{1,50}:({email_address}[^"]+?@[^@"]+)\\?"\s*[,\]\}]""",
      """"userIdentity\\?":.+?"AssumedRole\\?".+?"sessionIssuer\\?":\s*\{[^\}]+?"IAMUser\\?"[^\}]+?"userName\\?":\s*\\?"(({email_address}[^"@]+@[^"\.]+\.[^"]+)|({user}[^"]+?)(@({domain}[^@"]+))?)\\?"""",
      """"userIdentity\\?":.+?"IAMUser\\?".+?"userName\\?":\s*\\?"(({email_address}[^"@]+@[^"\.]+\.[^"]+)|({user}[^"]+?)(@({domain}[^@"]+))?)\\?"""",
      """"userIdentity\\?":\s*\{.*?"type\\?":\s*\\?"({user}Root)\\?""""
    
}
```