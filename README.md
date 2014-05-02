Gigabyte GA-Z77N-WiFi Hackintosh DSDT Patch by Mrengles

This DSDT patch with the right Clover EFI Bootloader configuration and SSDT should produce a fully compatible Hackintosh running OS X Mavericks.

Checkout http://mrengles.com for more details!

Included Patches:

1. Fixes All Errors & Warnings
2. Toleda HDMI Audio with Layout-ID 3
3. USB 3.0 Multiplex with Extra Current (iPad Charging)
4. MCHC
5. LPC
6. RTC
7. SBUS with BUS0 and BUS1 (Built-in Serial Port Support)

Apply the patch to your extracted DSDT with MaciASL.

Don't apply this patch to the same extracted DSDT more then once!

This patch has only been tested with the following hardware:

- Gigabyte GA-Z77N-WiFi
- Intel Core i7-3570K
- EVGA GeForce GTX 660 Ti

Thanks Toleda, JPalm, and Rehabman for their original works!
