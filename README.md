# Skylake-ventura-hackintosh
In this repository, there is available the boot files (EFI folder) to boot macOS Ventura for my pc build
This files are based on the EFI folder available on olarila.com so many thanks to their team.

HARDWARE I USED:
CPU: Intel Core i3 - 6100
Motherboard: MSI B150M Mortar
RAM: 4 GB DDR4 2133 MHz (will update to 8gb in a future)
GPU: Nvidia GeForce GT 710 (MSI version)
WiFi: Intel AC 3168 (Dualband WiFi + Bluetooth)
Storage: Kingston 240GB SATA SSD

Screenshot:
![Captura de pantalla 2023-05-07 a las 23 36 50](https://user-images.githubusercontent.com/44674082/236703716-f6bc9e0a-3d20-4f62-b72e-fc640de24b7f.png)

![Uploading graphics.png…]()

![wifi](https://user-images.githubusercontent.com/44674082/236704195-e0c9674d-5297-4ec5-8bcf-b3c7f0b0c4b7.png)

![bluetooth](https://user-images.githubusercontent.com/44674082/236704203-9d370d9c-1a36-43d6-8952-61d40b15fc4b.png)


WHAT'S WORKING?
Full Graphics Accel with Opencore Legacy Patcher on nvidia gpu
Fully working Wifi + Bluetooth thanks to itlwn patch
M.2 Wifi and all sata ports
Audio with AppleALC (Realtek ALC892 codec)
HDMI Audio

WHAT IS NOT WORKING?
Intel HD 520 (iGPU): it could be easily fixed with some opencore patches but I prefer to use the nvidia GPU because it is easier to make it work, it is more powerfull and has it's own memory (1gb vram) meanwhile the igpu uses normal RAM
