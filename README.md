Gigabyte GA-Z77N-WiFi Hackintosh DSDT Patch by Mrengles

This DSDT patch with the right Clover EFI Bootloader configuration and SSDT should produce a fully compatible Hackintosh running OS X Mavericks or Yosemite.

Included Patches:

1. Fixes All Errors & Warnings
2. Toleda HDMI Audio with Layout-ID 3
3. MCHC
4. LPC
5. RTC
6. SBUS with BUS0 and BUS1 (Built-in Serial Port Support)

Apply the patch to your extracted DSDT with MaciASL.

Don't apply this patch to the same extracted DSDT more then once!

This patch has only been tested with the following hardware:

- Gigabyte GA-Z77N-WiFi
- Intel Core i7-3570K
- EVGA GeForce GTX 660 Ti

Required Kext extensions for this Motherboard/DSDT combination.

FakeSMC.kext
FakePCIID.kext
FakePCIID_XHCIMux.kext

Thanks Toleda, JPalm, and Rehabman for their original works!
