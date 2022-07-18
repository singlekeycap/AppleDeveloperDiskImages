# Developer Disk Images for iOS
This is a repo for Apple Developer Disk Images for iOS (11.0-16.0)
This will make a menu appear in settings that looks like this:
![Developer menu](https://raw.githubusercontent.com/justanobody2107/AppleDeveloperDiskImages/main/Screenshots/DevMenu.jpg)

Installation is quite easy.

## With Mac
- Install Xcode
- If these files are missing, drag .dmg and .signature for your iOS version into `/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/<iOS version>`
- Connect your phone and launch Xcode
- Debug any app.

## With Linux
- Install [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice)
- Connect your phone, and hit trust this computer
- Verify that phone is paired by running `idevicepair pair`
- `cd` into directory where the .dmg and .signature files are saved
- Run command `ideviceimagemounter <DevDiskImage> <DevDiskImageSignature>`

### Enjoy!
