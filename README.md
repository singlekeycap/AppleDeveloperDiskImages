# AppleDeveloperDiskImages
This is a repo for Apple Developer Disk Images for iOS (11.0-16.0)

Installation is quite easy.

## With Mac
- Install Xcode
- If these files are missing, drag .dmg and .signature for your iOS version into `/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/<iOS version>`
- Connect your phone and launch Xcode
- Debug any app.

## With Linux/Windows
- Install [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice)
- `cd` into directory where the .dmg and .signature files are saved
- Run command `ideviceimagemounter <DevDiskImage> <DevDiskImageSignature>`

### Enjoy!
