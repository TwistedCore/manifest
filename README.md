TwistedProject Github

Build sources for Twisted Rom Shamu and Hammerhead devices

Setting up Build Environment

Official build environment as per Google and AOSP Android source page
XDA user guides Ubuntu 14.04 Trusty LTS , Ubuntu 14.10 Utopic
Arch Linux
Initializing the Source

(Assuming you have a valid build environment setup)

mkdir aosp (or whatever you want to name the source folder)

cd ~/aosp

repo init -u https://github.com/TwistedCore/manifest.git -b stuart

Sync the Source

repo sync -jx -f (x being however many cpu jobs, you can also use -c to sync only the current branch specified by repo init)

Getting Ready to Build

. build/envsetup.sh

Choose Supported Device to Build

mka otapackage

For Quick Dirty Rebuilds


cd ~/aosp

repo sync -jx -f (x being however many cpu jobs, may also use -c as above)

lunch and pick the right device (refer to above for choosing right device to build)

mka dirty

mka otapackage

Credits

Google for AOSP
Rascarlo and RastaPop
Altaf-Mahdi and Euphoria-OS
DariosF and Purity ROM
Paranoid Android (AOSPA)
AOSPAL
CyanogenMod
Dirty Unicorns
LiquidSmooth
AOKP
SlimROMS
Project D.I.S.C.O. Team
PartimusPrime for bootanimations
OmniROM
Lichti1901 and Terminus
Sykopompos
Team Horizon and XenonHD
Chet and OptiPop
VanirAOSP
PurifiedROM
The-Ancile-Project
AOD-Lollibeans
Android Open Development
Dhacker29
beanstown106
Ayysir
BitSyko Development
Others we may have missed
