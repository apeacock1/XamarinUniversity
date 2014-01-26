Xamarin University Setup Requirements
========================

You can do all the class labs using either your own installs, or you can use the pre-configured Virtual Machines provided below.  If you want to use your own install, then please read the following information carefully to make sure you have it setup properly.

To begin, our documentation portal has detailed installation instructions for:

* [Xamarin.iOS](http://docs.xamarin.com/guides/ios/getting_started/installation/)
* [Xamarin.Android](http://docs.xamarin.com/guides/android/getting_started/installation/)

### Version Requirements

Xamarin University course material has been developed with the latest versions of Xamarin Studio (currently 4.2) and Visual Studio 2013. Earlier versions may still work for you, but some instructions may be slightly different (things like menu items, toolbar buttons and other features may be different in older versions of each IDE).

## Mac Running OS X

If you're doing the iOS or Cross-platform portion of the course, you must have an Apple Computer running Mac OS X. This is both a legal and technical requirement. Apple requires that iOS Developers do their development on a Mac, and Xamarin uses the Xcode build chain to create native iOS packages.

## Android SDK Version (API Level)

Most Xamarin University courses involving Android development will target Android SDK 4.3 (API level 18). SDK versions can be downloaded and installed from the Android SDK Manager (accessible from the Tools menu in Xamarin Studio). Please check the lab document prerequisites section for your specific courses to see if additional levels will need to be downloaded.

## Xamarin Software

#### Running on a Mac ####
On your Mac, you'll need to have the latest Xamarin.iOS installed on this machine, as well as Xamarin.Android, if you wish to do Android development on your Mac (you can also choose to develop Android on Windows).

In order to use the Xamarin iOS Design support during the training, you will need to enable the **alpha channel** in Xamarin Studio. This is only a requirement for the iOS or Cross-platform tracks.  For more information, see the [guide on changing your update channel](http://docs.xamarin.com/recipes/cross-platform/ide/change_updates_channel/)

**If you are doing production work in Xamarin Studio** and cannot change to the alpha channel, then we recommend using the supplied OS X Virtual Machine (details below) while you work through the labs and take the online classes.

#### Running on Windows ####
If you're doing your development and training on Windows, you'll need to have Xamarin.Android and Xamarin.iOS installed there. Note, that if you're doing iOS development on a Mac with Visual Studio, you'll still need a Mac Running OS X to build.

You can find the Xamarin software on the [download page](http://xamarin.com/download).

### Xamarin Business Tier

Additionally, Xamarin University has a number of corporate-focused classes that require at least the Business tier of Xamarin products. For the Fundamentals Course, Indie level is sufficient for everything except for development in Visual Studio and the WCF portion of the Intro to Web Services Class. If you're not subscribed to the Business tier, you can start a trial by following the instructions [here](http://docs.xamarin.com/guides/cross-platform/getting_started/beginning_a_xamarin_trial/)

## Virtual Machines

For performance and productivity reasons, we recommend doing the Xamarin University classes on your own machine/install, however, if you'd like to use a VM, for instance, if you want to stay on the Stable channel in your primary development environment, we've created two Virtual Machine images that have Xamarin all installed and ready to go. You can download them from the following links:

### Windows 8 VMWare Image

This image requires the free VMWare Player that can be downloaded from from [here](https://my.vmware.com/web/vmware/free#desktop_end_user_computing/vmware_player/6_0).  There are two files you will need:
 1. [Xamarin.Android.vmx](https://s3.amazonaws.com/xamarin-download/XamarinUniversity/Xamarin.Android VM/Xamarin.Android.vmx)
 2. [Xamarin.Android.vmdk Disk Image](https://s3.amazonaws.com/xamarin-download/XamarinUniversity/Xamarin.Android+VM+Unzipped/Xamarin.Android.vmdk)
 
The disk image is quite large (22G) and must be placed in the same directory as the .vmx file.  If you have a slow Internet connection but more disk space available, you can download a 7zipped version of the disk image from [here](https://s3.amazonaws.com/xamarin-download/XamarinUniversity/Xamarin.Android+VM/Xamarin.Android.vmdk.7z).  Then unzip the file to get the full disk image.  To run the VM, make sure you have VMWare or the free VMWare player installed and then double-click on the .vmx file you downloaded.

### Mac OSX 10.9 (Mavericks)

This image requires the free Virtual Box software to run - you can download Virtual Box from [here](http://virtualbox.org).  The disk image itself is in VMWare format so you can move it to a VMWare product or convert it to Parallels fairly easily if you already own one of those tools.  Keep in mind that Apple requires any virtualized OSX system be run on Apple hardware and most VM software tools will require this. 

There are two files you will need:

1. [Xamarin_iOS.vbox](https://s3.amazonaws.com/xamarin-download/XamarinUniversity/Xamarin.iOS.VM/Xamarin_iOS.vbox)
2. [Xamarin_ios.vmdk](https://s3.amazonaws.com/xamarin-download/XamarinUniversity/Xamarin.iOS.VM+Unzipped/Android.ios.vmdk)

The disk image is quite large (22G) and must be placed in the same directory as the .vbx file.  If you have a slow Internet connection but more disk space available, you can download a 7zipped version of the disk image from [here](https://s3.amazonaws.com/xamarin-download/XamarinUniversity/Xamarin.iOS.VM/Android.ios.vmdk.7z).  Then unzip the file to get the full disk image.  To run the VM, make sure you have VirtualBox installed and then double-click on the .vbox file you downloaded.
