# Hackintosh-bigsur
This is about the EFI Configuration file for Big Sur (Tested on- 11.4, 11.5, 11.5.1)

Note: Version 1 is made using Prebuilt SSDT, making it support z490 mobo with comet lake processors.</br>
      Version 2 is made using manual SSDT, making it specific to Maximus XII Hero with i7-10700K processor.</br>
      
      Donot use the SSDT if you are unsure.</br>
      
Hardwares:
Asus Maximus XII Hero (z490)</br>
Processor i7-10700K</br>
Corsair Vengeance RGB PRO 32 GB 3200 MHz</br>
Nvidia RTX 3080 - Disabled (unsupported), iGPU- Intel UHD 630</br>

BIOS Settings to Change:</br>
DVMT - 64mb</br>
That's all...

Working:</br>
Wifi</br>
Bluetooth</br>
Shutdown/Restart fixed</br>
USB</br>
USB 3.1</br>
Technically everything...</br>

Not Working:</br>
Airdrop: Due to apple not supporting much intel wifi modules.

Note: Try to understand the EFI File, even though we might have shared the same hardware, you might not get everything working.   </br>
      When you are using iGPU to accelerate, connect your display to motherboard port, as your gpu will be disabled.</br>


I thank https://dortania.github.io/OpenCore-Install-Guide/ for the guide
