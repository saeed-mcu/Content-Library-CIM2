#### Parser Content
```Java
{
Name = amazon-awscloudtrail-json-app-notification-success-digests3object
  ParserVersion = v1.0.0
  Vendor = Amazon
  Product = AWS CloudTrail
  TimeFormat = "yyyy-MM-dd'T'HH:mm:ss"
  Conditions = [ """"previousDigestS3Object":""",""""digestPublicKeyFingerprint":"""",""""destinationServiceName":"AWS"""",""""s3Bucket":"""" ]
  Fields = [
    """"digestEndTime":"({time}\d\d\d\d-\d\d-\d\dT\d\d:\d\d:\d\d)""",
    """"destinationServiceName":"({app}[^"]+)"""",
    """"awsAccountId":"({account_id}\d+)"""",
 ]


}
```