# Hackintosh-BigSur-Monterey-Ventura
This is about the EFI Configuration file for Big Sur, Monterey and Ventura. (All Tested)

Note: Version 1 is made using Prebuilt SSDT, making it support z490 mobo with comet lake processors.</br>
      Version 2 is made using manual SSDT, making it specific to Maximus XII Hero with i7-10700K processor.</br>
      Version 3-5 uses -wenogpu bootarg
      Version 5+ uses SSDT to disable to PCIe Port labelled in the diagram below.
      Donot use the SSDT if you are unsure.
      
Hardwares:
Asus Maximus XII Hero (z490)</br>
Processor i7-10700K</br>
Corsair Vengeance RGB PRO 32 GB 3200 MHz</br>
Nvidia RTX 3080 - Disabled (unsupported), iGPU- Intel UHD 630</br>

BIOS Settings to Change:</br>
Secure boot: Other OS</br>
That's all...

Working:</br>
Everything except

Not Working:</br>
Airdrop: Due to apple not supporting this wireless module.

Note: Try to understand the EFI File, even though we might have shared the same hardware, you might not get everything working.   </br>
      When you are using iGPU to accelerate, connect your display to motherboard port, as your gpu will be disabled.</br>


I want to thank https://dortania.github.io/OpenCore-Install-Guide/ and some people on discord server for the guide

The ports enabled in this EFI are: (1,3,4,7,9,11,12,13,14,17,19,20,23,25) due to 15 port limit. The blocked PCIe Port is labelled here.
![Back Port](https://user-images.githubusercontent.com/32937797/226535012-9cdef757-5f45-41fe-9fc3-7cf88e550bdd.png)

![Front Port](https://user-images.githubusercontent.com/32937797/226535019-3294d185-35af-4f28-8336-ef104020680f.png)
