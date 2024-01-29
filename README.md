# linux-boot-system-documentation
<br>

## Linux Boot Process Sequence
1. Click `Power Button` to start
2. CPU works
3. BIOS/UEFI
    - Perform POST (Power On Self Test)
    - Check for bootable device
4. MBR
    - Load the boot loader (446 byte) into the memory
5. GRUB
    - Load `boot/grab/grab.cfg`
    - GUI asking OS
    - Select Kernel
    - Load to RAM
6. Kernel
    - Load the driver from `temp.system`
    - Initialized the first process `init/systemD`
7. SystemD
    - Start all require process
    - To bring system to `run_level/targets`

## Info
  - CPU: Central Processing Unit
  - BIOS: Basic I/O (Input-Output) System
  - UEFI: Unified Extensible Firmware Interface
  - MBR: Master Boot Record
  - GRUB: GRand Unified Bootloader
  - GUI: Graphical User Interface
  - SystemD: System Daemons

<br>

### _Author: [Mahfuz Hasan Reza](https://github.com/mahfuzhasanreza/)_
 - _Connect with me on [LinkedIn](https://www.linkedin.com/in/mahfuzhasanreza/)_
 - _Follow me on [Instagram](https://www.instagram.com/mahfuzhasanreza/)_
 - _Connect with me on [Facebook](https://www.facebook.com/mahfuzhasanreza/)_
