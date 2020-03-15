# ryzentosh

This is my fully working EFI folder for my Ryzentosh. <br>
It contains OpenCore 0.5.5 (I didn't update to 0.5.6 yet) and rEFInd 12.0 for multi boot.<br>
I deleted my serial and UUID so you'll have to generate them using GenSMBIOS for iMacPro1,1 and edit config.plist (PlatformInfo > Generic). It's important to use a valid serial with no valid purchase date to enable iServices.<br>
<br>
My specs:<br>
- Ryzen 5 3600
- MSI B450M Mortar Max
- Radeon RX 580
- 2*8GB HyperX FuryX 3200Hz

Kexts:
- AppleALC
- FakeSMC
- Lilu (and Innie for the NVMe drives)
- NullEthernet
- RealtekRTL8111 (patched version so it works with newer bootloaders too)
- WhateverGreen
