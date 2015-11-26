Gigabyte GA-Z77N-WiFi Hackintosh DSDT Patch by Mrengles

This DSDT patch with the right Clover (or Ozmosis) Bootloader configuration and SSDT should produce a fully compatible Hackintosh running OS X Mavericks, Yosemite or El Capitan.

Included Patches:

1. Fix Errors & Warnings
2. Add HDMI Audio (Layout-ID 3 by Toleda)
3. Add MCHC
4. Add IMEI
5. Fix LPC
6. Fix HPET
7. Fix IRQ
8. Fix Mutex
9. Fix PNOT/PPNT/PNTF
10. Fix USB (2.0 & 3.0)
11. Simulate Windows 2012
12. Add SMBUS (BUS1 & BUS2)
13. Add DTGP

Apply the patch to your extracted DSDT with MaciASL.

Don't apply this patch to the same extracted DSDT more then once!

This patch has only been tested with the following hardware:

- Gigabyte GA-Z77N-WiFi
- Intel Core i7-3570K
- EVGA GeForce GTX 660 Ti

Required Kext extensions for this Motherboard/DSDT combination.

- FakeSMC.kext
- FakePCIID.kext
- FakePCIID_XHCIMux.kext
- RealtekRTL8111.kext

Thanks Toleda, JPalm, and Rehabman for their original works!
