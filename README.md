# Fedora

## Install fedora in a VirtualBox

### Quick glance if you have problems

1. After install fedora, when reboot if come back to the installation process: 
    + Virtual box keep the media that use to install as a boot device, so when reboot it load the media as a main boot
    - Fix: go to Settings => Choose tab Storage => remove/eject the optic drive or just find a way to switch Controller SATA as your main boot

### Some Usefull Tools
- Unikey: sudo dnf install ibus-bogo && ibus restart (After that simpley add the input in the Language and keyboard tab in Settings)