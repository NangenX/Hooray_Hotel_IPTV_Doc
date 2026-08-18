# License Setting

> Introduction

![License](_images/license/license_1.png ':size=80%')

<!-- 📷 截图待补充：License 管理页面 -->

In `License`, administrators manage the license of the IPTV system. The license controls the number of set-top boxes that can connect to the system and the validity period. When the license is invalid or expired, new terminals cannot register to the system.

## License Status

![License Status](_images/license/license_2.png ':size=80%')

<!-- 📷 截图待补充：License 状态信息 -->

The license page displays the current license information:

<font color="red">**Status**</font>: The current status of the license (valid / invalid / expired / not activated).

<font color="red">**Customer Name**</font>: The customer name bound to the license.

<font color="red">**Max Connect**</font>: The maximum number of set-top boxes allowed to connect to the system.

<font color="red">**Expire Date**</font>: The expiry date of the license.

<font color="red">**Failure Reason**</font>: If the license is invalid, the reason for the failure is shown here.

## Fingerprint

![Fingerprint](_images/license/license_3.png ':size=80%')

<!-- 📷 截图待补充：设备指纹 -->

Press the `Fingerprint` button to generate the fingerprint of the current server. The fingerprint is a unique identifier of the server hardware; it must be provided to the license issuer so that a license bound to this server can be generated.

Press the `Download` button to download the fingerprint file and send it to the license issuer.

## Upload License

![Upload License](_images/license/license_4.png ':size=80%')

<!-- 📷 截图待补充：上传 License 文件 -->

After obtaining the license file from the license issuer:

1. Click the `Upload` button on the license page.
2. In the pop-up dialog, select the license file.
3. Press `Submit`. The system verifies the license file (signature, customer binding, expiry date and time rollback defense). If the verification passes, the license takes effect immediately; otherwise the failure reason is displayed on the page.
