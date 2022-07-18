# AppleDeveloperDiskImages
This is a repo for Apple Developer Disk Images for iOS (11.0-16.0)

Installation is quite easy.

## With Mac
Drag .dmg and .signature for your iOS version into your Xcode app folder (in case they're missing), then connect your phone and launch Xcode, then debug any app.

## With Linux/Windows
Use libimobiledevice, with command `ideviceimagemounter <DevDiskImage> <DevDiskImageSignature>`
