0.2.0
---
* **core**
  - gattc: DeviceCharacteristic Read() implementation
  - gap: add Disconnect() to Driver
  - gap: change signature for Addresser interface Set() function to accept string and then parse it as needed
* **linux**
  - update to latest version of go-bluetooth package for Linux
* **macos**
  - handle case when adapter enable sends notification before event delegate is set
  - Document async Disconnect behaviour
* **examples**
  - discover should only wait on startup on baremetal, since macOS does not like that

0.1.0
---
* **linux**
  - support for both central and peripheral operation
* **macos**
  - support for both central and peripheral operation
* **windows**
  - experimental support for both central scanning only
* **nordic semiconductor**
  - support for both central and peripheral operation on nRF82840 and nRF52832
  - support for peripheral only on nRF51822