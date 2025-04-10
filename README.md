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
