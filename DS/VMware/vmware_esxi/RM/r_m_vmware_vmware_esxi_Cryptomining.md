Rules by Product and UseCase
============================
Vendor: VMware
--------------
### Product: [VMware ESXi](../ds_vmware_vmware_esxi.md)
### Use-Case: [Cryptomining](../../../../UseCases/uc_cryptomining.md)

| Rules | Models | MITRE TTPs | Activity Types | Parsers |
|:-----:|:------:|:----------:|:--------------:|:-------:|
|   2   |   0    |     2      |       11       |   11    |

| Event Type          | Rules    | Models |
| ---- | ---- | ------ |
| web-activity-denied | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>WEB-Shadow-Mining</b>: User has browsed to a known coinmining/shadowmining domain<br><br><b>T1496 - Resource Hijacking</b><br> ↳ <b>A-WEB-Shadow-Mining</b>: Host has browsed to a known coinmining/shadowmining domain<br> ↳ <b>WEB-Shadow-Mining</b>: User has browsed to a known coinmining/shadowmining domain |        |