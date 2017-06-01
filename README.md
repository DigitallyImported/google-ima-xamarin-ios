This repository is used to create the Google Interactive Media Ads binding for iOS. [See website here](https://developers.google.com/interactive-media-ads/docs/sdks/ios/quickstart)

Current Version - 3.5.2

To use Google IMA SDK in your project, follow these directions:

1. Open google_ima_ios_binding/google_ima_ios_binding.sln in Xamarin
2. Rebuild that solution.
3. Copy the resulting bin/\<BuildType\>/GoogleIMASDK.dll to your own Xamarin project.
4. Download the 3.5.2 version of the GoogleInteractiveMediaAds.framework and place it at the root level of your Xamarin project.
5. Include linking options in your project's options -> iOS Build -> Additional mtouch arguments for each build option. The linking should look like "--framework:${ProjectDir}/GoogleInteractiveMediaAds.framework"
