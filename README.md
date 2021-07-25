# Hackintosh-bigsur
This is about the EFI Configuration file for Big Sur - 11.5.


Hardwares:
Asus Maximus XII Hero (z490)
Processor i7-10700K
Corsair Vengeance RGB PRO 32 GB 3200 MHz
Nvidia RTX 3080 - Disabled (unsupported), iGPU- Intel UHD 630

BIOS Settings to Change:
DVMT - 64mb
That's all...

Working:
Wifi
Bluetooth
Shutdown/Restart fixed
USB
USB 3.1
Technically everything...

Not Working:
Nothing that I am aware of! (other than nvidia)

Note: Try to understand the EFI File, even though we might have shared the same hardware, you might not get everything working.   
      When you are using iGPU to accelerate, connect your display to mother board port, as your gpu will be disabled.


I thank https://dortania.github.io/OpenCore-Install-Guide/ for the guide
