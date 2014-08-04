kexts
=====

kexts for acer v5_573g (osx 10.9.4)


1. `AppleIntelFramebufferAzul.kext` `AppleIntelHD5000Graphics.kext` is the Intel
   Graphical Card Driver; from Mavericks osx 10.9.2
2. `ELAN_v3.8.5_Final_Upd.zip` : the elan touchpad driver.
3. `Kext Wizard.zip`: a driver installer for osx.
4. `RealtekRTL8111_1.2.0.zip`: the wired network driver for realtek 8111E
5. `RehabMan-Battery-2014-0207.zip`: a battery driver from Rehabman.

###Usage:###

* To use them, pls unzip `Kext Wizard.zip` first, and install `kexts` with Kext
Wizard or some other driver installer you like.
* Pls note; after driver installed, you nedd to fixed the permissions and rebuild
the `system kext cache`.
* You can edit the `info.plist` to meet you own needs on touchpad. --Elan Touchpad--

###Pic for Kext\ Wizard###




###Something Else###

To install OSX on no-apple-osx device, pls go to the offical bbs like
[pcbeta](http://bbs.pcbeta.com)
> Here is a [good news](http://bbs.pcbeta.com/viewthread-1468257-1-1.html) 

* Clover Uefi project maybe usful for acve v5-573g.
* A fixed dsdt is needed. you can search for it with google.
    - [MaciASL](https://github.com/RehabMan/OS-X-MaciASL-patchmatic) is Needed.
    - Rehabman has made a lots of pathches for dsdt, check it.
* A dsdt patch for cpu is good enough. 
    - [ssdtPRGen.sh](https://github.com/Piker-Alpha/ssdtPRGen.sh)
