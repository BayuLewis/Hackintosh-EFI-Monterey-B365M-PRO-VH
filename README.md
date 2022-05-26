# Hackintosh-EFI-Monterey-B365M-PRO-VH
OpenCore v0.8.0  
macOS 12.4    

![img](https://BayuLewis.github.io/assets/images/macOS12dot4.jpg)
![iPhoneDevices](https://BayuLewis.github.io/assets/images/MacPro.jpg)
![LockScreen](https://BayuLewis.github.io/assets/images/LockScreenMac.jpg)
![YouTube](https://BayuLewis.github.io/assets/images/YouTubeMac.jpg)
![AppleMusic](https://BayuLewis.github.io/assets/images/AppleMusic.jpg)


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
- DRM
- Etc...

### Not Working
- AirDrop (You need a bluetooth card for this)

### Notes
- Make sure to use GenSMBIOS to refill some important credentials like MacSerial, UUID,...
- The screeshots you see above are iMacPro1,1 but you can change to MacPro7,1 if you wanted to. (You can see in the iPhone screenshot)
- Make sure to use GenSMBIOS to refill the UUID, System Serial Number,...
- For iMessage, you need to run via terminal once, then login with your account, after that it will automatically close, then you will need to open iMessage again and it will work flawlessly
- For the GPU part, I would recommend you choose another Model because HIS is kinda sus and it's not functioning well on Windows (Linux is fine AFAIK)
- This config is for macOS 10.15 and above
- Make sure to do USB Mapping and replace the USBMap.kext before continue.

### Special Thanks
- [Apple](https://www.apple.com/) for [macOS](https://www.apple.com/vn/macos/monterey/)
- Dortania's OpenCore [Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- And Other Resouces belongs to OpenCore
