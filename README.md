# macOS-SDK

#### Install old macOS SDK on newer Xcode

----------------------------------------------------

1. Go to https://developer.apple.com/downloads/index.action and download `Xcode xxx of your choice` 
2. Open the application by clicking `Show Package Content`
3. Navigate to `/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs`
4. Copy the `MacOSX.sdk` in a empty folder then rename of the Xcode Version `MacOSX12.1.sdk` as exemple
5. 5. Navigate to /Applications/XCode.app and click `Show Package Content`
6. Navigate to `/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs`
7. Paste the copied `MacOSX12.1.sdk` folder
8. Restart Xcode

MacOSX12.1.sdk should now be available for selection and building.

![Screen Shot 2022-03-18 at 2 26 22 PM](https://user-images.githubusercontent.com/6248794/159061908-a67f1355-e76d-4023-b351-e131d9d924d2.png)
