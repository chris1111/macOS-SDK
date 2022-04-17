# macOS-SDK

#### Install old macOS SDK on newer Xcode

----------------------------------------------------
### You need registered with Apple Developer

1. Go to https://developer.apple.com/downloads/index.action and download `Xcode xxx of your choice` 
2. Or use https://xcodereleases.com/ and download `Xcode xxx of your choice` 
3. Open the application by clicking `Show Package Content`
4. Navigate to `/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs`
5. Copy the `MacOSX.sdk` in a empty folder then rename of the Xcode Version `MacOSX12.1.sdk` as exemple
6. Navigate to /Applications/XCode.app and click `Show Package Content`
7. Navigate to `/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs`
8. Paste the copied `MacOSX12.1.sdk` folder
9. Restart Xcode

MacOSX12.1.sdk should now be available for selection and building.

![Screen Shot 2022-03-18 at 2 26 22 PM](https://user-images.githubusercontent.com/6248794/159061908-a67f1355-e76d-4023-b351-e131d9d924d2.png)

#### You can use https://github.com/phracker/MacOSX-SDKs/releases and download `macOS SDK of your choice`
