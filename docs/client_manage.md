# Client Management Setting

>Introduction

![Client Menu](_images/client/client_1.png)

In `Client Menu`, the administrator needs to configure the corresponding equipment information in `Room Category`, `Client Information` and `Client Status` and operate the check-in and check-out of visitors.

## Room Category

>Introduction

![Room Category](_images/client/client_2.png)

In `Room Category`, the administrator needs to set the logical classification name, in Hooray hotel IPTV logical classification named for distinguishing equipment belonging to different floors or different usage, for example, there are more than one piece of equipment placed on the 1st floor, then set the classification name for L1, and so on.

Press `Add` button to create the `Room Category`

![Room Category - Add](_images/client/client_3.png)

1. <font color="red">**Group Name**</font>: In `Group Name`, the administrator sets the logical category name.

## Client Information

>Introduction

![Client Information](_images/client/client_4.png)

In `Client information`, this page displays all the current online and offline devices, the administrator can manage the device name and `WIFI hotspot status` (abandoned) through this page, and in the device list, you can view the classification to which the device belongs, the corresponding room number and other device information and so on.

Press `Add` button to create the `Client Information`

![Client Information - Add](_images/client/client_5.png ':size=40%') ![Client Information - Edit](_images/client/client_6.png ':size=40%')

<font color="red">**MAC Address**</font> In `Mac Address`, if the device is not in Client Information, then it can be added manually by entering the MAC address, and if the device has been discovered by the hotel IPTV server, the MAC can only be viewed.

<font color="red">**IP**</font> In `IP`, displays information about the IP address of the last time the device was online.

<font color="red">**Room Name**</font> In `Room Name`, enter the name of the room to which the device belongs.

<font color="red">**Room Category**</font> In `Room Category`, select the room category to which the device belongs.

<font color="red">**WiFi**</font> In `WIFI`, the administrator can ON and OFF the device hotspot function, and can set the hotspot function WIFI name and password. Due to Google's protection for Android this feature can no longer be enabled.


## Client Status

>Introduction

![Client Status](_images/client/client_7.png)

In the Client Status page, the administrator can operate the check-in and check-out of the corresponding equipment, and the unchecked-in equipment can view the information of the previously checked-in customers and their consumption records. The checked-in devices can operate online orders, consumption records, edit guest information, view previous check-in records and check-out operations.

![Client Status Check-In Status](_images/client/client_8.png)

<font color="red">**Request**</font> Click the `request` button, will jump to the guest's current booking operation page, in the page, administrator can view the guest's booking of the room, the administrator through the operation button to confirm the order or delete the order. After the corresponding operation, the result will be returned to the guest and presented status of the hotel app.

<font color="red">**Consume**</font> Click `Consume` button will redirect you to the guest's current consumption record page, which displays the current guest's completed order from app.

<font color="red">**Edit**</font> Click `Edit` button, the administrator can reset the name of the check-in guest and the welcome message.

<font color="red">**Records**</font> Click `Record` button, administrator can view the device check-in record, including the name of the occupant, check-in time, check-out time and consumption record.

<font color="red">**Check-Out**</font> After clicking the `Check-Out` button, the device automatically enters the Check-Out state, in which all services are unavailable.

![Client Status Check-In Status](_images/client/client_9.png)

<font color="red">**Check-In**</font> Click the `Check-In` button, the administrator needs to fill in the name of the check-in customer and the welcome message displayed on the big screen.

## Device Management

> Introduction

![Device Management](_images/client/client_10.png ':size=80%')

<!-- 📷 截图待补充：Client Information 设备管理视图 -->

In `Client Information`, the device list is enhanced with device management capabilities. When a set-top box reports its status, the administrator can remotely operate the device without entering the guest room, which greatly reduces the IT maintenance cost.

### Device Telemetry

The device list shows the real-time telemetry reported by each set-top box, including **CPU usage** and **memory usage**, so that the administrator can quickly spot devices with performance problems (e.g. stuck or high memory usage).

### Device Detail

![Device Detail](_images/client/client_11.png ':size=80%')

<!-- 📷 截图待补充：Device Detail 弹窗 -->

Click the device `Detail` button to open the device detail dialog, where the information is grouped for easy viewing:

- **Device information**: MAC address, IP, room name, room category, device model, etc.
- **Supported functions**: the remote functions supported by the device (e.g. remote cleaning, log retrieval, status reporting).
- **Command history**: the latest instructions of the device (up to 10 records), with their status and results.
- **View Log**: open the device log in an independent dialog.

### Device Commands

The administrator can remotely send the following commands to a device:

| Command | Description |
|---|---|
| **reboot** | Remotely restart the set-top box. |
| **clear_guest_data** | Clear the guest data of third-party apps on the device (e.g. Netflix/YouTube login state and cache). The packages to be cleaned are controlled by the check-out cleaning whitelist configured on the `Client Information` page (see `Check-Out Cleaning Whitelist`). |
| **get_telemetry** | Ask the device to immediately report its current running status (CPU/memory usage). |
| **get_logs** | Ask the device to return its log text (up to 100KB). The returned content can be viewed in the command history. |

> **Note**: each operation is only available on devices that support the corresponding function.

### Manual Batch Cleaning

![Manual Batch Clean](_images/client/client_12.png ':size=80%')

<!-- 📷 截图待补充：手动批量清理入口 -->

On the device list, the administrator can select multiple devices and perform **manual batch cleaning** (`clear_guest_data`), which is usually used before a new guest checks in to protect the privacy of the previous guest.

### Check-Out Cleaning Whitelist

![Check-Out Cleaning Whitelist](_images/client/client_13.png ':size=80%')

<!-- 📷 截图待补充：退房清理白名单弹窗 -->

The check-out cleaning whitelist is configured on the `Client Information` page: press the `Whitelist` button to open the whitelist dialog, and enter the package names of the third-party apps to be cleaned (separated by commas, e.g. `com.netflix.ninja,com.google.android.youtube`). When a guest checks out (or a cleaning command is triggered), the terminal will clear the data of these packages locally. Leave it empty to disable automatic check-out cleaning.