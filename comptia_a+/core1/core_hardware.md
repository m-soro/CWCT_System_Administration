# CompTIA A+ (220-1001) Cert Prep 3: Core Hardware
> Learn about essential hardware components, devices, and processes as you prepare to take and pass the CompTIA A+ Core 1 (220-1001) exam.

1. [Firmware]()
2. [Motherboards]()
3. [Power Supplies]()

---

### 1. Firmware - Objective 3.5 
> Given a scenario, install and configure motherboards, CPUs and 

What is BIOS/UEFI?
* firmware that is burned to the chip, used to speak to the motherboard before the OS boots up
* BIOS programs are codes
* Basic input/output services (BIOS) 
* M BIOS and B BIOS - Backup BIOS 

What can it do?
it talks to drive, to test the assumed hardware

#### Quick Review
* BIOS programming enables interaction with motherboard before OS loads
* BIOS is stored in nonvaltile media, thus called firmware
* POST Power On Self-Test routines are built into firmware
* The System Setup System Setup (CMOS) utility is also part of the firmware

### Firmware - POST
* As soon as power-good wire receives enough voltage, the cpu starts running and the first thing it does is talk to bios and run POST, it broadcast itselfs to the motherboard and says if you can hear me check yourself out - the all do a self check test. After the POST is succcessful, it beeps. 
* It checks CPU, RAM, Video, etc.

* **Beep Codes** - error message thru error codes
* **POST cards** - has two digit hexa decimal and it tells you the error

#### Quick Review 
* POST runs at boot, requesting devices to self check
* POST errors manifests as specific beep codes or display (text) codes
* POST cards enebale testing of "dead" computers

### Firmware - System Set up
* **Unified Extensible Firmware Interface(UEFI)** - an upgraded BIOS, it supplanted BIOS - but its still BIOS. 

System Set up - use to change the changeable part of BIOS hold `delete` or `F2 key`

#### Quick Review 
* UEFI replaces traditional 16-bit BIOS in modern systems
* The System Setup enables custom information about changeable devices
* System Setup enables changes to CPU frequencies, RAM timings, BIOS passwords, boot options, and more
