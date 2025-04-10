# ubuntu-Bluetooth-version-check

# ✅ Step 1: Check Bluetooth Adapter Info
```bash
bluetoothctl show
```
# ✅ Step 2: Check Supported Bluetooth Version
```bash
sudo apt update
sudo apt install bluez
```
# Now, run this command:  btmgmt
```bash
sudo btmgmt info
```
# Version
```bash
hci0:	Primary controller
	addr 00:1A:7D:DA:71:13 version 10 manufacturer 10
```
## version 10 (HCI version)।
```bash
| **HCI Version** | **Bluetooth Version** |
|-----------------|-----------------------|
| 1               | 1.0b                  |
| 2               | 1.1                   |
| 3               | 1.2                   |
| 4               | 2.0 + EDR             |
| 5               | 2.1 + EDR             |
| 6               | 3.0 + HS              |
| 7               | 4.0                   |
| 8               | 4.1                   |
| 9               | 4.2                   |
| 10              | 5.0                   |
| 11              | 5.1                   |
| 12              | 5.2                   |
| 13              | 5.3                   |

```
