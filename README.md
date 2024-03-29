# Developer Disk Images for iOS
This is a repo for Apple Developer Disk Images for iOS (11.0-16.0)  
This will make a menu appear in settings that looks like this:
![Developer menu](https://raw.githubusercontent.com/justanobody2107/AppleDeveloperDiskImages/main/Screenshots/DevMenu.jpg)

Installation is quite easy.

## With Mac (the Apple way)
- If on iOS 16, enable developer mode on your phone
- Install Xcode
- Connect your phone and launch Xcode
- Build/Debug any app using your phone
- In the rare case that the developer images are missing, drag .dmg and .signature for your iOS version into `/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/<iOS version>` then repeat the last 2 steps

## With Mac (the FOSS way)
- If on iOS 16, enable developer mode on your phone
- Install [libimobiledevice](https://libimobiledevice.org/)
- Connect your phone, and run `idevicepair pair`
- `cd` into directory where the .dmg and .signature files are saved
- Run command `ideviceimagemounter <DevDiskImage> <DevDiskImageSignature>`

## With Linux
- If on iOS 16, enable developer mode on your phone
- Install [libimobiledevice](https://libimobiledevice.org/)
- Connect your phone, and hit trust this computer
- Verify that phone is paired by running `idevicepair pair`
- `cd` into directory where the .dmg and .signature files are saved
- Run command `ideviceimagemounter <DevDiskImage> <DevDiskImageSignature>`

## With Windows
- If on iOS 16, enable developer mode on your phone
- Install [libimobiledevice suite (exe)](https://github.com/L1ghtmann/libimobiledevice)
- Connect your phone, and hit trust this computer
- Verify that phone is paired by running `idevicepair pair`
- `cd` into directory where the .dmg and .signature files are saved
- Run command `ideviceimagemounter <DevDiskImage> <DevDiskImageSignature>`

### Enjoy!
