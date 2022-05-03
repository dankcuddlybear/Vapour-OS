# Vapour-OS
What is Vapour OS?
Vapour OS is an Arch Linux based distro. It aims to be flexible, optimised for performance and security, used for a variety of purposes and with no extra junk. At its core, Vapour OS is a basic Arch Linux system with all the core packages, plus commonly used command line utilities and performance enhancements. I've also included features from other distros like Ubuntu, Steam OS and Android. Arch Linux follows a rolling release model, so you will always get the latest software updates, but Vapour OS additionally ships with it's own updater to install and configure new features.

Why did you create Vapour OS?
The initial aim was to create an install script to automate installation and configuration of Arch Linux. 

Who is Vapour OS for?
Once the core system is installed, you can install and configure any extra software you need with a simple tool. Here are the current software choices:
Desktop/GUI: KDE Plasma, XFCE, Kodi and Steam Big Picture
Gaming: Proton/Wine, game libs (64bit and 32bit), emulators
Multimedia: Video codecs
Server: Nginx (with extra security features)
Security: Extra security features. Choose from enhanced (slight performance impact) and ultra-secure (bigger performance impact, for governments and cyber criminals)

Why the name?
I don't really know. I originally planned to make it a gaming distro, like Steam OS, so I changed Steam OS to Vapour OS.

Is it complete?
Right now Vapour OS is still very much a work in progress, and I do not recommend that anyone uses it. Here's some things you should know before you try it:
 - The only language currently supported is British English
 - Only 2 desktop environments are supported: KDE Plasma (for high end machines) and XFCE (for servers or low end machines). If you prefer a different DE, you'll have to install it manually.
 - If AMD integrated graphics are detected, any dedicated AMD Graphics card will not be detected. This is because the hardware detector is not written very well. Any third GPU will also not be detected. If you have Intel, AMD and Nvidia graphics then the AMD GPU will be used for PRIME offloading.

What do I need to run Vapour OS?
Only recent hardware is officially supported. You can get it to run on older x86_64 PCs but you'll have to tweak the installer yourself.
CPU: x86_64 CPU (SSE4.2 support recommended)
RAM: 128MiB for CLI only. HIGHLY recommended: 1GiB
Motherboard: Any motherboard with UEFI support
Storage: Any SSD or SATA HDD with at least 10GiB free space
GPU: Intel Nehalem (gen 1) or above iGPU. Recommended: Ivy Bridge (gen 3) or above
     AMD Graphics Core Next or above GPU
     Nvidia Maxwell or above GPU
