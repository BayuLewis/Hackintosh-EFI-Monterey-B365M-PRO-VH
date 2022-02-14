# Hackintosh-EFI-Monterey-B365M-PRO-VH
OpenCore v0.7.8  
macOS 12.2.1  

![img](https://krisbane.github.io/assets/images/macOS.png)


### Specs
| Component | Model |
| --- | --- |
| Motherboard | MSI B365M PRO VH |
| CPU | Intel Core i5 9400F 6C/6T |
| GPU | HIS AMD RX 570 4GB |
| Audio Codec | Realtek® ALC887 |
| SSD | KIOXIA EXCERIA NVMe SSD 500GB |
| Ethernet | Realtek RTL8111H (Onboard) |

### Working
- Most Apple Apps
- Sleep
- USB Port
- Ethernet
- Etc...

### Not Working
- iMessage
- AirDrop (You need a bluetooth card for this)

### Notes
- Make sure to use GenSMBIOS to refill the UUID, System Serial Number,...
- For iMessage you can check [this](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html)
- For the GPU part, I would recommend you choose another Model because HIS is kinda sus and it's not functioning well on Windows (Linux is fine AFAIK)
- This config is for macOS 10.15 and above
- Make sure to do USB Mapping and replace the USBMap.kext before continue.

### Special Thanks
- [Apple](https://www.apple.com/) for [macOS](https://www.apple.com/vn/macos/monterey/)
- Dortania's OpenCore [Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- And Other Resouces belongs to OpenCore
