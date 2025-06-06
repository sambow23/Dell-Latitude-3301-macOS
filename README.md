# Dell Latitude 3301

| Hardware  | |
| ------------- | ------------- |
| CPU  | Intel® Core™ i7-8565U |
| RAM  | 8GB LPDDR3 (Soldered) |
| GPU  | Intel UHD Graphics 620  |
| Network  | Intel® Wi-Fi AC 9462 |
| Storage  | Western Digital® PC SN520 256GB |
| OS  | macOS Ventura 13.7.6 |
| Screen  | 13" 1920x1080 |
| Bootloader | OpenCore 1.0.4 | 

## Hardware compatibility
> [!CAUTION]
> This EFI currently uses a DSDT to get trackpad functionality. Hopefully this will be changed in the future.

#### What works
- CPU power management
- GPU acceleration and video codecs
- SSD (NVME)
- Wi-Fi (AirportItlwm.kext)
- All USB ports (not mapped)
- USB-C Video
- Trackpad
- FN Keys
- Webcam
- Screen Brightness
- Internal Audio (Speakers, Headphones, Microphone)
- Battery percentage
- Sleep

#### Untested
- iCloud Services
- Bluetooth (no kext installed)

#### Not working
- You tell me
