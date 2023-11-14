EndeavourOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 980

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [985ed440bf](https://linux-hardware.org/?probe=985ed440bf) | Nov 06, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [1cf99ffe12](https://linux-hardware.org/?probe=1cf99ffe12) | Nov 05, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [cf8911c5e0](https://linux-hardware.org/?probe=cf8911c5e0) | Nov 05, 2023 |
| HP            | ProBook 430 G1              | [451abee058](https://linux-hardware.org/?probe=451abee058) | Nov 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [db71fb65bf](https://linux-hardware.org/?probe=db71fb65bf) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b592d36d74](https://linux-hardware.org/?probe=b592d36d74) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [da695062ba](https://linux-hardware.org/?probe=da695062ba) | Nov 03, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [de293a4621](https://linux-hardware.org/?probe=de293a4621) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b0c996ac38](https://linux-hardware.org/?probe=b0c996ac38) | Nov 02, 2023 |
| ASUSTek       | UX430UNR                    | [47abbeb9c1](https://linux-hardware.org/?probe=47abbeb9c1) | Nov 01, 2023 |
| MSI           | GV62 8RD                    | [d85cb220a0](https://linux-hardware.org/?probe=d85cb220a0) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [865e6764f2](https://linux-hardware.org/?probe=865e6764f2) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [bf87ba6b55](https://linux-hardware.org/?probe=bf87ba6b55) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | [0b21a4419d](https://linux-hardware.org/?probe=0b21a4419d) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | [757199e3cf](https://linux-hardware.org/?probe=757199e3cf) | Nov 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6c1c4ea069](https://linux-hardware.org/?probe=6c1c4ea069) | Oct 31, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUA... | [701a08bdb6](https://linux-hardware.org/?probe=701a08bdb6) | Oct 31, 2023 |
| HP            | Laptop 15-dw0xxx            | [55f41faf27](https://linux-hardware.org/?probe=55f41faf27) | Oct 31, 2023 |
| MSI           | Modern 15 A11M              | [43161bd5f4](https://linux-hardware.org/?probe=43161bd5f4) | Oct 30, 2023 |
| HP            | ProBook 650 G1              | [508c244637](https://linux-hardware.org/?probe=508c244637) | Oct 30, 2023 |
| HP            | 255 G6 Notebook PC          | [f19f70993f](https://linux-hardware.org/?probe=f19f70993f) | Oct 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [448c3ca446](https://linux-hardware.org/?probe=448c3ca446) | Oct 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [c1d00eb91f](https://linux-hardware.org/?probe=c1d00eb91f) | Oct 29, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [aaf303e411](https://linux-hardware.org/?probe=aaf303e411) | Oct 28, 2023 |
| Apple         | MacBookPro16,1              | [0e1711e674](https://linux-hardware.org/?probe=0e1711e674) | Oct 28, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [e0dc47cf61](https://linux-hardware.org/?probe=e0dc47cf61) | Oct 28, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [1f5d6e4141](https://linux-hardware.org/?probe=1f5d6e4141) | Oct 27, 2023 |
| HP            | ZBook 15 G3                 | [21bcc65553](https://linux-hardware.org/?probe=21bcc65553) | Oct 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [5aef96bd0e](https://linux-hardware.org/?probe=5aef96bd0e) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [9c37fcb5c9](https://linux-hardware.org/?probe=9c37fcb5c9) | Oct 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [e2e4b18ec2](https://linux-hardware.org/?probe=e2e4b18ec2) | Oct 23, 2023 |
| HP            | Snappy                      | [2d0c13b032](https://linux-hardware.org/?probe=2d0c13b032) | Oct 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f103762ce5](https://linux-hardware.org/?probe=f103762ce5) | Oct 21, 2023 |
| Acer          | Aspire A315-23              | [147d6ad175](https://linux-hardware.org/?probe=147d6ad175) | Oct 21, 2023 |
| HP            | Snappy                      | [b8dc14dc5d](https://linux-hardware.org/?probe=b8dc14dc5d) | Oct 21, 2023 |
| Dell          | XPS 15 9520                 | [7deca235e3](https://linux-hardware.org/?probe=7deca235e3) | Oct 20, 2023 |
| Acer          | Aspire E5-523G              | [12b93b3f48](https://linux-hardware.org/?probe=12b93b3f48) | Oct 20, 2023 |
| Acer          | Aspire E5-523G              | [240879310d](https://linux-hardware.org/?probe=240879310d) | Oct 19, 2023 |
| Sony          | SVE1713X1EB                 | [ec015a6c9e](https://linux-hardware.org/?probe=ec015a6c9e) | Oct 19, 2023 |
| Dell          | XPS 15 9530                 | [e350eec913](https://linux-hardware.org/?probe=e350eec913) | Oct 19, 2023 |
| HP            | EliteBook 845 14 inch G1... | [5ee2d06317](https://linux-hardware.org/?probe=5ee2d06317) | Oct 15, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [0d80ec0e27](https://linux-hardware.org/?probe=0d80ec0e27) | Oct 15, 2023 |
| Toshiba       | Satellite C855-1KF          | [1dbc7c0de3](https://linux-hardware.org/?probe=1dbc7c0de3) | Oct 15, 2023 |
| MSI           | GS63 Stealth 8RE            | [a83fe5a954](https://linux-hardware.org/?probe=a83fe5a954) | Oct 11, 2023 |
| MSI           | GS63 Stealth 8RE            | [5f9d5460fb](https://linux-hardware.org/?probe=5f9d5460fb) | Oct 11, 2023 |
| Dell          | XPS 15 9520                 | [04fbcfc11b](https://linux-hardware.org/?probe=04fbcfc11b) | Oct 10, 2023 |
| Dell          | Latitude 7420               | [4071bd53ce](https://linux-hardware.org/?probe=4071bd53ce) | Oct 10, 2023 |
| System76      | Gazelle                     | [1a40053c3e](https://linux-hardware.org/?probe=1a40053c3e) | Oct 07, 2023 |
| Acer          | Aspire 7730G                | [d48f861a2e](https://linux-hardware.org/?probe=d48f861a2e) | Oct 05, 2023 |
| HP            | ZBook 14u G4                | [1d14da7190](https://linux-hardware.org/?probe=1d14da7190) | Oct 05, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [cc02a5e08e](https://linux-hardware.org/?probe=cc02a5e08e) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8e0792976d](https://linux-hardware.org/?probe=8e0792976d) | Oct 03, 2023 |
| Sony          | SVE1713X1EB                 | [ca5985274a](https://linux-hardware.org/?probe=ca5985274a) | Oct 02, 2023 |
| Razer         | Blade 15 Base Model (Lat... | [4e1788f184](https://linux-hardware.org/?probe=4e1788f184) | Oct 02, 2023 |
| Gigabyte      | AERO 15-X9                  | [35830807d4](https://linux-hardware.org/?probe=35830807d4) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | [1c4b1aa68d](https://linux-hardware.org/?probe=1c4b1aa68d) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | [988f015a89](https://linux-hardware.org/?probe=988f015a89) | Sep 30, 2023 |
| Lenovo        | ThinkPad E495 20NES07V00    | [935dc10f6b](https://linux-hardware.org/?probe=935dc10f6b) | Sep 30, 2023 |
| Dell          | Latitude 5410               | [d13c5769a3](https://linux-hardware.org/?probe=d13c5769a3) | Sep 30, 2023 |
| MSI           | GL73 8RE                    | [670f7351b5](https://linux-hardware.org/?probe=670f7351b5) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | [1543bac588](https://linux-hardware.org/?probe=1543bac588) | Sep 27, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [b8b2b3ff7e](https://linux-hardware.org/?probe=b8b2b3ff7e) | Sep 26, 2023 |
| Acer          | Nitro AN515-45              | [94ce4b6306](https://linux-hardware.org/?probe=94ce4b6306) | Sep 25, 2023 |
| MSI           | GS63VR 6RF                  | [03a9aed3c9](https://linux-hardware.org/?probe=03a9aed3c9) | Sep 25, 2023 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [7ea3152d65](https://linux-hardware.org/?probe=7ea3152d65) | Sep 25, 2023 |
| Dell          | G5 5505                     | [e9c461d44d](https://linux-hardware.org/?probe=e9c461d44d) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [cada97becf](https://linux-hardware.org/?probe=cada97becf) | Sep 25, 2023 |
| Acer          | Aspire A515-51              | [f6369d0be5](https://linux-hardware.org/?probe=f6369d0be5) | Sep 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [2d1e14cb66](https://linux-hardware.org/?probe=2d1e14cb66) | Sep 23, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [45f00aaf92](https://linux-hardware.org/?probe=45f00aaf92) | Sep 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [9fdc142c76](https://linux-hardware.org/?probe=9fdc142c76) | Sep 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [d940deb0df](https://linux-hardware.org/?probe=d940deb0df) | Sep 19, 2023 |
| HP            | EliteBook 865 16 inch G9... | [5cab8957eb](https://linux-hardware.org/?probe=5cab8957eb) | Sep 18, 2023 |
| HP            | Dragonfly Pro               | [0c5d439504](https://linux-hardware.org/?probe=0c5d439504) | Sep 18, 2023 |
| Dell          | Latitude E5470              | [0602c2deb2](https://linux-hardware.org/?probe=0602c2deb2) | Sep 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [aea37f693f](https://linux-hardware.org/?probe=aea37f693f) | Sep 15, 2023 |
| Dell          | Precision 7710              | [c954042e8b](https://linux-hardware.org/?probe=c954042e8b) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [2260bcd7af](https://linux-hardware.org/?probe=2260bcd7af) | Sep 12, 2023 |
| Sony          | SVE1713X1EB                 | [2284d8a2dd](https://linux-hardware.org/?probe=2284d8a2dd) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | [dca28b0d09](https://linux-hardware.org/?probe=dca28b0d09) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | [6c6c4a19ec](https://linux-hardware.org/?probe=6c6c4a19ec) | Sep 12, 2023 |
| HP            | 245 14 inch G9 Notebook ... | [e72c31a6fc](https://linux-hardware.org/?probe=e72c31a6fc) | Sep 11, 2023 |
| Acer          | Swift SF314-512             | [4628c4e630](https://linux-hardware.org/?probe=4628c4e630) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d8ac2101a](https://linux-hardware.org/?probe=6d8ac2101a) | Sep 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [16b6bd1d3d](https://linux-hardware.org/?probe=16b6bd1d3d) | Sep 09, 2023 |
| HP            | 255 G8 Notebook PC          | [bdd270eddd](https://linux-hardware.org/?probe=bdd270eddd) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [5b0ce3438c](https://linux-hardware.org/?probe=5b0ce3438c) | Sep 08, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [6870581b7c](https://linux-hardware.org/?probe=6870581b7c) | Sep 08, 2023 |
| HP            | EliteBook 865 16 inch G9... | [872f12f24c](https://linux-hardware.org/?probe=872f12f24c) | Sep 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d5430e9279](https://linux-hardware.org/?probe=d5430e9279) | Sep 08, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [5b22cd283b](https://linux-hardware.org/?probe=5b22cd283b) | Sep 08, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [003d136012](https://linux-hardware.org/?probe=003d136012) | Sep 07, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [79ddc77f63](https://linux-hardware.org/?probe=79ddc77f63) | Sep 07, 2023 |
| Sony          | SVE1713X1EB                 | [f7c65dc902](https://linux-hardware.org/?probe=f7c65dc902) | Sep 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [cd1be324d4](https://linux-hardware.org/?probe=cd1be324d4) | Sep 05, 2023 |
| Sony          | SVE1513B1EW                 | [82fd19c99e](https://linux-hardware.org/?probe=82fd19c99e) | Sep 05, 2023 |
| MSI           | GS75 Stealth 8SG            | [fc603fc196](https://linux-hardware.org/?probe=fc603fc196) | Sep 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | [13b7789482](https://linux-hardware.org/?probe=13b7789482) | Sep 04, 2023 |
| HP            | EliteBook 845 14 inch G1... | [8a4af58adc](https://linux-hardware.org/?probe=8a4af58adc) | Sep 04, 2023 |
| ASUSTek       | N750JV                      | [f23cf01c1c](https://linux-hardware.org/?probe=f23cf01c1c) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [db2e607ae6](https://linux-hardware.org/?probe=db2e607ae6) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [b652970974](https://linux-hardware.org/?probe=b652970974) | Sep 01, 2023 |
| HP            | Pavilion Aero Laptop 13z... | [afa88a8a6a](https://linux-hardware.org/?probe=afa88a8a6a) | Sep 01, 2023 |
| MSI           | Modern 15 A5M               | [a6619c179c](https://linux-hardware.org/?probe=a6619c179c) | Aug 31, 2023 |
| Fujitsu       | LIFEBOOK U904               | [7cf4986142](https://linux-hardware.org/?probe=7cf4986142) | Aug 29, 2023 |
| Dell          | Inspiron 3542               | [320e8d218f](https://linux-hardware.org/?probe=320e8d218f) | Aug 28, 2023 |
| ASUSTek       | X550VXK                     | [897e4f89ec](https://linux-hardware.org/?probe=897e4f89ec) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [657c08f61f](https://linux-hardware.org/?probe=657c08f61f) | Aug 27, 2023 |
| Sony          | SVE1713X1EB                 | [ab8f75bb84](https://linux-hardware.org/?probe=ab8f75bb84) | Aug 27, 2023 |
| Google        | Madoo                       | [6644bab363](https://linux-hardware.org/?probe=6644bab363) | Aug 26, 2023 |
| HP            | EliteBook 645 14 inch G9... | [d02a7851a6](https://linux-hardware.org/?probe=d02a7851a6) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [3eea0be3b4](https://linux-hardware.org/?probe=3eea0be3b4) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [53ba2f91cd](https://linux-hardware.org/?probe=53ba2f91cd) | Aug 24, 2023 |
| Dell          | Latitude E5470              | [637ccef7bd](https://linux-hardware.org/?probe=637ccef7bd) | Aug 24, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [816f3ce721](https://linux-hardware.org/?probe=816f3ce721) | Aug 24, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [ef3454780b](https://linux-hardware.org/?probe=ef3454780b) | Aug 23, 2023 |
| HP            | 250 G4                      | [1eb6dc4c12](https://linux-hardware.org/?probe=1eb6dc4c12) | Aug 23, 2023 |
| Lenovo        | ThinkPad E495 20NES0KM00    | [783db5b84d](https://linux-hardware.org/?probe=783db5b84d) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | [26d59e1060](https://linux-hardware.org/?probe=26d59e1060) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | [d10b0c4ca0](https://linux-hardware.org/?probe=d10b0c4ca0) | Aug 23, 2023 |
| Sony          | SVE1713X1EB                 | [165cab2421](https://linux-hardware.org/?probe=165cab2421) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | [6112b46746](https://linux-hardware.org/?probe=6112b46746) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | [b883100fd3](https://linux-hardware.org/?probe=b883100fd3) | Aug 21, 2023 |
| MSI           | Katana 15 B13VGK            | [c21afd5e9f](https://linux-hardware.org/?probe=c21afd5e9f) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b6aa75cb80](https://linux-hardware.org/?probe=b6aa75cb80) | Aug 20, 2023 |
| Packard Be... | EasyNote TJ66               | [7e5e1655a6](https://linux-hardware.org/?probe=7e5e1655a6) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [d6df464cc7](https://linux-hardware.org/?probe=d6df464cc7) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [471f5f6132](https://linux-hardware.org/?probe=471f5f6132) | Aug 20, 2023 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [60385dd9f0](https://linux-hardware.org/?probe=60385dd9f0) | Aug 20, 2023 |
| HP            | EliteBook 865 16 inch G9... | [f99d3dca93](https://linux-hardware.org/?probe=f99d3dca93) | Aug 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | [5ed6b3612a](https://linux-hardware.org/?probe=5ed6b3612a) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [6e6a7171bf](https://linux-hardware.org/?probe=6e6a7171bf) | Aug 16, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [1632c89b98](https://linux-hardware.org/?probe=1632c89b98) | Aug 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [246c60a344](https://linux-hardware.org/?probe=246c60a344) | Aug 13, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [6cbef2a38d](https://linux-hardware.org/?probe=6cbef2a38d) | Aug 13, 2023 |
| Acer          | Aspire A317-53              | [17dacd99a6](https://linux-hardware.org/?probe=17dacd99a6) | Aug 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [083e25221d](https://linux-hardware.org/?probe=083e25221d) | Aug 10, 2023 |
| Acer          | Aspire A317-53              | [5a2d81b438](https://linux-hardware.org/?probe=5a2d81b438) | Aug 09, 2023 |
| Dell          | Latitude E5570              | [cbcea81a37](https://linux-hardware.org/?probe=cbcea81a37) | Aug 06, 2023 |
| Toshiba       | PORTEGE R700                | [f0df061bb2](https://linux-hardware.org/?probe=f0df061bb2) | Aug 04, 2023 |
| Dell          | Vostro 3500                 | [5f63621af2](https://linux-hardware.org/?probe=5f63621af2) | Aug 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [731ae84313](https://linux-hardware.org/?probe=731ae84313) | Aug 04, 2023 |
| Acer          | TravelMate P614-51-G2       | [33dd52a94f](https://linux-hardware.org/?probe=33dd52a94f) | Aug 03, 2023 |
| Dell          | Precision 3571              | [efa0df50dc](https://linux-hardware.org/?probe=efa0df50dc) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [fc2f2f7f45](https://linux-hardware.org/?probe=fc2f2f7f45) | Aug 02, 2023 |
| Sony          | VPCSB1V9R                   | [8d809c3877](https://linux-hardware.org/?probe=8d809c3877) | Aug 02, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [46ca3ef1f4](https://linux-hardware.org/?probe=46ca3ef1f4) | Aug 01, 2023 |
| Acer          | Aspire A317-53              | [3f1af34e1b](https://linux-hardware.org/?probe=3f1af34e1b) | Aug 01, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [37be164783](https://linux-hardware.org/?probe=37be164783) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [e24869945e](https://linux-hardware.org/?probe=e24869945e) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [a2148fe49f](https://linux-hardware.org/?probe=a2148fe49f) | Aug 01, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [5d12cf34ca](https://linux-hardware.org/?probe=5d12cf34ca) | Jul 31, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [ae14da63f3](https://linux-hardware.org/?probe=ae14da63f3) | Jul 30, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [f1db906c7c](https://linux-hardware.org/?probe=f1db906c7c) | Jul 30, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [963eb3c0a8](https://linux-hardware.org/?probe=963eb3c0a8) | Jul 29, 2023 |
| HP            | EliteBook 2540p             | [cb13e61bae](https://linux-hardware.org/?probe=cb13e61bae) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e08f65110d](https://linux-hardware.org/?probe=e08f65110d) | Jul 27, 2023 |
| Google        | Fleex                       | [977fa266d3](https://linux-hardware.org/?probe=977fa266d3) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | [045470ba6d](https://linux-hardware.org/?probe=045470ba6d) | Jul 26, 2023 |
| MSI           | GL73 8RE                    | [7de233f9bd](https://linux-hardware.org/?probe=7de233f9bd) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| ASUSTek       | K53SD                       | [2cd6047230](https://linux-hardware.org/?probe=2cd6047230) | Jul 25, 2023 |
| HP            | ProBook 440 G2              | [85168259e3](https://linux-hardware.org/?probe=85168259e3) | Jul 25, 2023 |
| HP            | 250 G3                      | [5580b343bd](https://linux-hardware.org/?probe=5580b343bd) | Jul 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8b89c63576](https://linux-hardware.org/?probe=8b89c63576) | Jul 24, 2023 |
| MSI           | GL73 8RE                    | [86035a17da](https://linux-hardware.org/?probe=86035a17da) | Jul 24, 2023 |
| Sony          | SVE1713X1EB                 | [f2dfaee237](https://linux-hardware.org/?probe=f2dfaee237) | Jul 23, 2023 |
| Apple         | MacBookPro16,1              | [7f3a5aa8cd](https://linux-hardware.org/?probe=7f3a5aa8cd) | Jul 22, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [2a3971e2fc](https://linux-hardware.org/?probe=2a3971e2fc) | Jul 21, 2023 |
| HP            | 245 G8 Notebook PC          | [788fc0bfc9](https://linux-hardware.org/?probe=788fc0bfc9) | Jul 21, 2023 |
| ASUSTek       | G551JK                      | [fed0cf1fce](https://linux-hardware.org/?probe=fed0cf1fce) | Jul 20, 2023 |
| Acer          | Aspire A515-47              | [9a705d5047](https://linux-hardware.org/?probe=9a705d5047) | Jul 20, 2023 |
| HP            | Pavilion dv6                | [cc73a658d1](https://linux-hardware.org/?probe=cc73a658d1) | Jul 19, 2023 |
| Sony          | SVE1713X1EB                 | [89340a2cf7](https://linux-hardware.org/?probe=89340a2cf7) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [7733ed8a40](https://linux-hardware.org/?probe=7733ed8a40) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [4bba49b11c](https://linux-hardware.org/?probe=4bba49b11c) | Jul 19, 2023 |
| Dell          | XPS 15 9570                 | [e6cf0622b0](https://linux-hardware.org/?probe=e6cf0622b0) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [69a47b22c4](https://linux-hardware.org/?probe=69a47b22c4) | Jul 18, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [ef2395800e](https://linux-hardware.org/?probe=ef2395800e) | Jul 16, 2023 |
| Teclast       | F7 Plus                     | [1c317224d2](https://linux-hardware.org/?probe=1c317224d2) | Jul 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [52870865a4](https://linux-hardware.org/?probe=52870865a4) | Jul 15, 2023 |
| Maibenben     | MaiBook M                   | [44a9f08c5e](https://linux-hardware.org/?probe=44a9f08c5e) | Jul 15, 2023 |
| Notebook      | NH5x_7xRCx,RDx              | [9e8ab59ea8](https://linux-hardware.org/?probe=9e8ab59ea8) | Jul 14, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | [2213337296](https://linux-hardware.org/?probe=2213337296) | Jul 14, 2023 |
| OriginPC      | EVO16-S                     | [f3b1c85a1a](https://linux-hardware.org/?probe=f3b1c85a1a) | Jul 11, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [fddf95e5c8](https://linux-hardware.org/?probe=fddf95e5c8) | Jul 11, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | ThinkPad A275 20KCS08C0K    | [9857dab3ab](https://linux-hardware.org/?probe=9857dab3ab) | Jul 08, 2023 |
| Sony          | SVE1713X1EB                 | [7fde9afaf1](https://linux-hardware.org/?probe=7fde9afaf1) | Jul 08, 2023 |
| Dell          | XPS 15 9530                 | [09ada263c3](https://linux-hardware.org/?probe=09ada263c3) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| ASUSTek       | X455LJ                      | [60c1acd1fc](https://linux-hardware.org/?probe=60c1acd1fc) | Jul 04, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16IAH7 8... | [ad57a8dd50](https://linux-hardware.org/?probe=ad57a8dd50) | Jul 04, 2023 |
| HP            | EliteBook 8770w             | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| HP            | Laptop 15-db0xxx            | [0064c1c269](https://linux-hardware.org/?probe=0064c1c269) | Jul 03, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f9e366002e](https://linux-hardware.org/?probe=f9e366002e) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [c1a241c0a5](https://linux-hardware.org/?probe=c1a241c0a5) | Jul 03, 2023 |
| Dell          | Latitude E5470              | [0a50455c18](https://linux-hardware.org/?probe=0a50455c18) | Jul 02, 2023 |
| Lenovo        | Legion Y9000X IAH7 82TF     | [efb7d0f42a](https://linux-hardware.org/?probe=efb7d0f42a) | Jul 02, 2023 |
| Dell          | XPS L521X                   | [b80baf340c](https://linux-hardware.org/?probe=b80baf340c) | Jul 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [cf9a80fbbc](https://linux-hardware.org/?probe=cf9a80fbbc) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f3cb4dc749](https://linux-hardware.org/?probe=f3cb4dc749) | Jun 29, 2023 |
| eMachines     | eME728                      | [37dc0ef617](https://linux-hardware.org/?probe=37dc0ef617) | Jun 29, 2023 |
| ASUSTek       | X455LJ                      | [c147d5716d](https://linux-hardware.org/?probe=c147d5716d) | Jun 27, 2023 |
| Google        | Sasuke                      | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| Dell          | Inspiron 3583               | [e0f5116d38](https://linux-hardware.org/?probe=e0f5116d38) | Jun 23, 2023 |
| Sony          | SVE1713X1EB                 | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| Apple         | MacBookPro16,2              | [2bcd63ec1e](https://linux-hardware.org/?probe=2bcd63ec1e) | Jun 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [bc3ba9b05e](https://linux-hardware.org/?probe=bc3ba9b05e) | Jun 15, 2023 |
| Dell          | Latitude E5570              | [43171e0f19](https://linux-hardware.org/?probe=43171e0f19) | Jun 14, 2023 |
| Sony          | SVE1513B1EW                 | [3528d095e0](https://linux-hardware.org/?probe=3528d095e0) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2db1bbb316](https://linux-hardware.org/?probe=2db1bbb316) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21a8144a2e](https://linux-hardware.org/?probe=21a8144a2e) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3c7683dfc4](https://linux-hardware.org/?probe=3c7683dfc4) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1d46e48d92](https://linux-hardware.org/?probe=1d46e48d92) | Jun 10, 2023 |
| Dell          | Latitude E6510              | [e7c1e59ac7](https://linux-hardware.org/?probe=e7c1e59ac7) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [2f0f8eb596](https://linux-hardware.org/?probe=2f0f8eb596) | Jun 09, 2023 |
| VIT           | P2402                       | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| Dell          | Vostro 1015                 | [3e38c53463](https://linux-hardware.org/?probe=3e38c53463) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | [0e24e0ad6c](https://linux-hardware.org/?probe=0e24e0ad6c) | Jun 07, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [33fb312b6d](https://linux-hardware.org/?probe=33fb312b6d) | Jun 05, 2023 |
| Sony          | SVE1713X1EB                 | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| TUXEDO        | InfinityBook Pro 15 v5      | [1b01df33d2](https://linux-hardware.org/?probe=1b01df33d2) | Jun 03, 2023 |
| HP            | Laptop 15-db0xxx            | [04830d213f](https://linux-hardware.org/?probe=04830d213f) | Jun 03, 2023 |
| Acer          | Aspire E5-575G              | [c4cd05b00f](https://linux-hardware.org/?probe=c4cd05b00f) | Jun 01, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3de415ea72](https://linux-hardware.org/?probe=3de415ea72) | Jun 01, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c198463bc3](https://linux-hardware.org/?probe=c198463bc3) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| ASUSTek       | GL553VD                     | [a1f825f4e5](https://linux-hardware.org/?probe=a1f825f4e5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | [0b04d3bf20](https://linux-hardware.org/?probe=0b04d3bf20) | May 28, 2023 |
| ASUSTek       | X455LF                      | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [574e88c4f3](https://linux-hardware.org/?probe=574e88c4f3) | May 28, 2023 |
| Acer          | Aspire E5-575G              | [af33101302](https://linux-hardware.org/?probe=af33101302) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4362f979b8](https://linux-hardware.org/?probe=4362f979b8) | May 26, 2023 |
| Acer          | Aspire E5-573G              | [4c22ef876f](https://linux-hardware.org/?probe=4c22ef876f) | May 26, 2023 |
| Apple         | MacBookPro16,2              | [46cb91a74d](https://linux-hardware.org/?probe=46cb91a74d) | May 25, 2023 |
| Dell          | Inspiron 3583               | [7f5d36cc34](https://linux-hardware.org/?probe=7f5d36cc34) | May 23, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | [a48977a871](https://linux-hardware.org/?probe=a48977a871) | May 22, 2023 |
| HP            | Laptop 14s-dk1xxx           | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| HUAWEI        | CREM-WXX9                   | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| ASUSTek       | N56VB                       | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| Acer          | Aspire A315-42G             | [1125a4111e](https://linux-hardware.org/?probe=1125a4111e) | May 19, 2023 |
| Dell          | Inspiron 3583               | [1edee9f902](https://linux-hardware.org/?probe=1edee9f902) | May 18, 2023 |
| Dell          | Inspiron 5577               | [e4bfe14f2d](https://linux-hardware.org/?probe=e4bfe14f2d) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [35d056f8bd](https://linux-hardware.org/?probe=35d056f8bd) | May 11, 2023 |
| ASUSTek       | N56VB                       | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b81c403545](https://linux-hardware.org/?probe=b81c403545) | May 09, 2023 |
| Lenovo        | G560 0679                   | [a916fc6080](https://linux-hardware.org/?probe=a916fc6080) | May 08, 2023 |
| Timi          | TM1701                      | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| Dell          | Inspiron 5402               | [bac25fa124](https://linux-hardware.org/?probe=bac25fa124) | May 04, 2023 |
| Lenovo        | ThinkPad W530 24473F2       | [937dddbff0](https://linux-hardware.org/?probe=937dddbff0) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [9984dd7707](https://linux-hardware.org/?probe=9984dd7707) | May 03, 2023 |
| Notebook      | NS5x_NS7xPU                 | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Apple         | MacBookAir7,2               | [1a343a4622](https://linux-hardware.org/?probe=1a343a4622) | Apr 30, 2023 |
| Dell          | Latitude 5580               | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Dell          | Inspiron 15 3520            | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Apple         | MacBookAir7,2               | [c1e0f0fa03](https://linux-hardware.org/?probe=c1e0f0fa03) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f1d5d361d5](https://linux-hardware.org/?probe=f1d5d361d5) | Apr 27, 2023 |
| MSI           | Modern 14 C7M               | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Acer          | Aspire A515-45              | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| Notebook      | NH5x_NH7xHP                 | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Sony          | SVE1713X1EB                 | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| Apple         | MacBookAir7,2               | [17ae2e245a](https://linux-hardware.org/?probe=17ae2e245a) | Apr 22, 2023 |
| Notebook      | W65_W67RB                   | [f34e442b8b](https://linux-hardware.org/?probe=f34e442b8b) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [00f7379c8f](https://linux-hardware.org/?probe=00f7379c8f) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| ASUSTek       | X55A                        | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| HUAWEI        | HLYL-WXX9                   | [8eaac4a62d](https://linux-hardware.org/?probe=8eaac4a62d) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | [47f2ba894b](https://linux-hardware.org/?probe=47f2ba894b) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d9f95c9169](https://linux-hardware.org/?probe=d9f95c9169) | Apr 11, 2023 |
| Sony          | SVE1713X1EB                 | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Acer          | Aspire E5-575               | [15d7d40bed](https://linux-hardware.org/?probe=15d7d40bed) | Apr 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | [aee22ee8b3](https://linux-hardware.org/?probe=aee22ee8b3) | Apr 08, 2023 |
| HP            | 250 G4                      | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| HP            | Unknown                     | [0af30fd642](https://linux-hardware.org/?probe=0af30fd642) | Apr 06, 2023 |
| Sony          | SVE1713X1EB                 | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| HP            | ZBook 17 G2                 | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [546e8e3742](https://linux-hardware.org/?probe=546e8e3742) | Apr 04, 2023 |
| Dell          | Inspiron 5402               | [5035f094da](https://linux-hardware.org/?probe=5035f094da) | Apr 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [9ba99b597e](https://linux-hardware.org/?probe=9ba99b597e) | Apr 03, 2023 |
| Apple         | MacBookAir6,2               | [d64af320d7](https://linux-hardware.org/?probe=d64af320d7) | Apr 02, 2023 |
| Apple         | MacBookAir6,2               | [3400bd9412](https://linux-hardware.org/?probe=3400bd9412) | Apr 02, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | [edb6e927bd](https://linux-hardware.org/?probe=edb6e927bd) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | [bfba694531](https://linux-hardware.org/?probe=bfba694531) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | [4169f13182](https://linux-hardware.org/?probe=4169f13182) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [3ac0a9cc94](https://linux-hardware.org/?probe=3ac0a9cc94) | Mar 31, 2023 |
| GPD           | G1621-02                    | [7d000ab41b](https://linux-hardware.org/?probe=7d000ab41b) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [008eb6ad60](https://linux-hardware.org/?probe=008eb6ad60) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4dd142ab8f](https://linux-hardware.org/?probe=4dd142ab8f) | Mar 31, 2023 |
| Sony          | SVE1713X1EB                 | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [d1295d9d1e](https://linux-hardware.org/?probe=d1295d9d1e) | Mar 30, 2023 |
| AWOW          | AL34                        | [19f60f27c8](https://linux-hardware.org/?probe=19f60f27c8) | Mar 29, 2023 |
| HP            | EliteBook 840 G5            | [65671e15cb](https://linux-hardware.org/?probe=65671e15cb) | Mar 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| Sony          | SVE1713X1EB                 | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [d80388d7ef](https://linux-hardware.org/?probe=d80388d7ef) | Mar 27, 2023 |
| ASUSTek       | N76VM                       | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| Samsung       | 550XDA                      | [058982f7d8](https://linux-hardware.org/?probe=058982f7d8) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [18cd806803](https://linux-hardware.org/?probe=18cd806803) | Mar 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E6C... | [3042a430c0](https://linux-hardware.org/?probe=3042a430c0) | Mar 24, 2023 |
| HP            | EliteBook 850 G1            | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| GPD           | G1619-04                    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | EliteBook 8460p             | [e0ec2e73be](https://linux-hardware.org/?probe=e0ec2e73be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Acer          | Swift SF315-52G             | [f6042580d0](https://linux-hardware.org/?probe=f6042580d0) | Mar 20, 2023 |
| Notebook      | N150ZU                      | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [a911c14f22](https://linux-hardware.org/?probe=a911c14f22) | Mar 19, 2023 |
| Samsung       | 550XDA                      | [5f14b733bb](https://linux-hardware.org/?probe=5f14b733bb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| ASUSTek       | UX301LAA                    | [882d4d095b](https://linux-hardware.org/?probe=882d4d095b) | Mar 18, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| Apple         | MacBookAir5,2               | [ae4d8ba68c](https://linux-hardware.org/?probe=ae4d8ba68c) | Mar 18, 2023 |
| Toshiba       | Satellite C55-C             | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | [066f0cd17b](https://linux-hardware.org/?probe=066f0cd17b) | Mar 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | [b588252431](https://linux-hardware.org/?probe=b588252431) | Mar 14, 2023 |
| Dell          | XPS 15 9520                 | [0f3b7bd317](https://linux-hardware.org/?probe=0f3b7bd317) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7f58d0d0a0](https://linux-hardware.org/?probe=7f58d0d0a0) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0c58b8ebad](https://linux-hardware.org/?probe=0c58b8ebad) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | [fc04961aef](https://linux-hardware.org/?probe=fc04961aef) | Mar 11, 2023 |
| Dell          | Precision 7720              | [6132f690aa](https://linux-hardware.org/?probe=6132f690aa) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [8a33917a89](https://linux-hardware.org/?probe=8a33917a89) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [f4d71dcbd0](https://linux-hardware.org/?probe=f4d71dcbd0) | Mar 09, 2023 |
| Dell          | Precision 7720              | [e4a1149bcb](https://linux-hardware.org/?probe=e4a1149bcb) | Mar 08, 2023 |
| Timi          | TM1701                      | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| HP            | EliteBook 8460p             | [3519073f46](https://linux-hardware.org/?probe=3519073f46) | Mar 07, 2023 |
| Dell          | Latitude 5289               | [dcac5b8ebc](https://linux-hardware.org/?probe=dcac5b8ebc) | Mar 06, 2023 |
| Google        | Rammus                      | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
| HP            | EliteBook 8460p             | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Lenovo        | Y50-70 20378                | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| Dell          | Inspiron N4010              | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| Medion        | Akoya E6412T                | [2915d1c409](https://linux-hardware.org/?probe=2915d1c409) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| ASUSTek       | X555LA                      | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [6234395029](https://linux-hardware.org/?probe=6234395029) | Feb 18, 2023 |
| Chuwi         | GemiBook Pro                | [7af4d238e8](https://linux-hardware.org/?probe=7af4d238e8) | Feb 18, 2023 |
| Google        | Helios                      | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| GPD           | G1621-02                    | [5d584fa1cf](https://linux-hardware.org/?probe=5d584fa1cf) | Feb 14, 2023 |
| HP            | Laptop 15s-fq4xxx           | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM    | [9e0e0bef82](https://linux-hardware.org/?probe=9e0e0bef82) | Feb 13, 2023 |
| Acer          | Aspire A515-54G             | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| HP            | Compaq 6820s                | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [0c6da36f9d](https://linux-hardware.org/?probe=0c6da36f9d) | Feb 11, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [059d515c3c](https://linux-hardware.org/?probe=059d515c3c) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2LN0... | [4fdb5d662c](https://linux-hardware.org/?probe=4fdb5d662c) | Feb 08, 2023 |
| HP            | ZBook 15 G4                 | [f2a6af1f7e](https://linux-hardware.org/?probe=f2a6af1f7e) | Feb 06, 2023 |
| HP            | Setzer                      | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | [e523dbd162](https://linux-hardware.org/?probe=e523dbd162) | Feb 02, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [bcaa2e6b1a](https://linux-hardware.org/?probe=bcaa2e6b1a) | Jan 30, 2023 |
| Dell          | Latitude 5400               | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | [3e957e185d](https://linux-hardware.org/?probe=3e957e185d) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | [849d901314](https://linux-hardware.org/?probe=849d901314) | Jan 28, 2023 |
| Toshiba       | Satellite L755              | [b15899ef80](https://linux-hardware.org/?probe=b15899ef80) | Jan 27, 2023 |
| Toshiba       | Satellite L755              | [357a0cd22d](https://linux-hardware.org/?probe=357a0cd22d) | Jan 27, 2023 |
| HUAWEI        | KLVC-WXX9                   | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Dell          | Latitude E5410              | [22df8731a9](https://linux-hardware.org/?probe=22df8731a9) | Jan 26, 2023 |
| Google        | Magpie                      | [34506f260e](https://linux-hardware.org/?probe=34506f260e) | Jan 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [56a9b7ad32](https://linux-hardware.org/?probe=56a9b7ad32) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| Dell          | XPS 13 9343                 | [f371c1c8b6](https://linux-hardware.org/?probe=f371c1c8b6) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| Acer          | Aspire E5-575G              | [1153793fd9](https://linux-hardware.org/?probe=1153793fd9) | Jan 22, 2023 |
| ASUSTek       | GL753VE                     | [10796ad8f6](https://linux-hardware.org/?probe=10796ad8f6) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [8b1ccef51d](https://linux-hardware.org/?probe=8b1ccef51d) | Jan 15, 2023 |
| Acer          | Aspire E5-575G              | [1681bdc38e](https://linux-hardware.org/?probe=1681bdc38e) | Jan 14, 2023 |
| Dell          | Precision M4800             | [c5deb205c7](https://linux-hardware.org/?probe=c5deb205c7) | Jan 14, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [cef6a9db45](https://linux-hardware.org/?probe=cef6a9db45) | Jan 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [8defa5d641](https://linux-hardware.org/?probe=8defa5d641) | Jan 05, 2023 |
| Dell          | XPS 9320                    | [8684c6d86b](https://linux-hardware.org/?probe=8684c6d86b) | Jan 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [be6730b67b](https://linux-hardware.org/?probe=be6730b67b) | Jan 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [bc57a904f7](https://linux-hardware.org/?probe=bc57a904f7) | Jan 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1be42c9032](https://linux-hardware.org/?probe=1be42c9032) | Jan 02, 2023 |
| Toshiba       | EQUIUM A100                 | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| MSI           | Modern 15 A5M               | [e0cb4d278d](https://linux-hardware.org/?probe=e0cb4d278d) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ce45aaceaf](https://linux-hardware.org/?probe=ce45aaceaf) | Dec 29, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| Acer          | Swift SFX14-41G             | [e422b934d0](https://linux-hardware.org/?probe=e422b934d0) | Dec 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b8099c7a94](https://linux-hardware.org/?probe=b8099c7a94) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | EliteBook 845 14 inch G9... | [475b76e98a](https://linux-hardware.org/?probe=475b76e98a) | Dec 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [244ad65a78](https://linux-hardware.org/?probe=244ad65a78) | Dec 24, 2022 |
| HP            | ProBook 450 G7              | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| Sony          | VGN-FW11E                   | [2d57afaa38](https://linux-hardware.org/?probe=2d57afaa38) | Dec 19, 2022 |
| HP            | 15                          | [cce5eb4078](https://linux-hardware.org/?probe=cce5eb4078) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [54e81a596c](https://linux-hardware.org/?probe=54e81a596c) | Dec 18, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0a486ca67b](https://linux-hardware.org/?probe=0a486ca67b) | Dec 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [8c87fc340b](https://linux-hardware.org/?probe=8c87fc340b) | Dec 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57ecebdc0f](https://linux-hardware.org/?probe=57ecebdc0f) | Dec 15, 2022 |
| PC Special... | Elimina Iv 17               | [66a5d6dd6a](https://linux-hardware.org/?probe=66a5d6dd6a) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [2a1d9a153b](https://linux-hardware.org/?probe=2a1d9a153b) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6ae6d710b7](https://linux-hardware.org/?probe=6ae6d710b7) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b56f450d6d](https://linux-hardware.org/?probe=b56f450d6d) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [ebf5cc9d6e](https://linux-hardware.org/?probe=ebf5cc9d6e) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| MSI           | GS75 Stealth 8SG            | [8741c9175e](https://linux-hardware.org/?probe=8741c9175e) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | [c3b6dada9d](https://linux-hardware.org/?probe=c3b6dada9d) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | [70be467762](https://linux-hardware.org/?probe=70be467762) | Dec 01, 2022 |
| Dell          | Inspiron 15-3567            | [eff3d877bc](https://linux-hardware.org/?probe=eff3d877bc) | Nov 30, 2022 |
| HP            | ENVY 17                     | [4a784f4642](https://linux-hardware.org/?probe=4a784f4642) | Nov 27, 2022 |
| Acer          | Aspire A517-52              | [3ce1a2c42a](https://linux-hardware.org/?probe=3ce1a2c42a) | Nov 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [4e7809f7f6](https://linux-hardware.org/?probe=4e7809f7f6) | Nov 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [123efdf4df](https://linux-hardware.org/?probe=123efdf4df) | Nov 26, 2022 |
| Dell          | Inspiron 15-3567            | [f05943013c](https://linux-hardware.org/?probe=f05943013c) | Nov 25, 2022 |
| Lenovo        | ThinkPad T440s 20ARA12UM... | [5e1b88160e](https://linux-hardware.org/?probe=5e1b88160e) | Nov 25, 2022 |
| Acer          | TravelMate 5730             | [0200afcfb3](https://linux-hardware.org/?probe=0200afcfb3) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | [077cd77583](https://linux-hardware.org/?probe=077cd77583) | Nov 24, 2022 |
| MSI           | Modern 14 B5M               | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [415fd12650](https://linux-hardware.org/?probe=415fd12650) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [aca01ed633](https://linux-hardware.org/?probe=aca01ed633) | Nov 21, 2022 |
| HP            | 15                          | [ab7c1e3bfd](https://linux-hardware.org/?probe=ab7c1e3bfd) | Nov 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| HP            | EliteBook 840 G2            | [6c896ef17e](https://linux-hardware.org/?probe=6c896ef17e) | Nov 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0b0d1f6427](https://linux-hardware.org/?probe=0b0d1f6427) | Nov 19, 2022 |
| Apple         | MacBookPro16,2              | [8c63644200](https://linux-hardware.org/?probe=8c63644200) | Nov 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [7aeba8b69a](https://linux-hardware.org/?probe=7aeba8b69a) | Nov 10, 2022 |
| Acer          | Aspire A315-22              | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AJ00    | [ec16a4b3c5](https://linux-hardware.org/?probe=ec16a4b3c5) | Nov 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fba0c1a99c](https://linux-hardware.org/?probe=fba0c1a99c) | Nov 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [0527a7a983](https://linux-hardware.org/?probe=0527a7a983) | Nov 07, 2022 |
| Lenovo        | ThinkPad T520 42406AG       | [1038487513](https://linux-hardware.org/?probe=1038487513) | Nov 06, 2022 |
| Timi          | RedmiBook Pro 15            | [226d8de9bb](https://linux-hardware.org/?probe=226d8de9bb) | Nov 04, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [08a8e0079a](https://linux-hardware.org/?probe=08a8e0079a) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0235661dbe](https://linux-hardware.org/?probe=0235661dbe) | Nov 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU    | [9e1b981f01](https://linux-hardware.org/?probe=9e1b981f01) | Nov 03, 2022 |
| MSI           | Prestige 15 A11SCX          | [973b498b3f](https://linux-hardware.org/?probe=973b498b3f) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| MSI           | Prestige 14Evo A12M         | [5e32f7b38b](https://linux-hardware.org/?probe=5e32f7b38b) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [ed6d5efa84](https://linux-hardware.org/?probe=ed6d5efa84) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [6263763f01](https://linux-hardware.org/?probe=6263763f01) | Oct 27, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [264d164669](https://linux-hardware.org/?probe=264d164669) | Oct 27, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [7e1a95e569](https://linux-hardware.org/?probe=7e1a95e569) | Oct 26, 2022 |
| Acer          | Extensa 2540                | [367660309f](https://linux-hardware.org/?probe=367660309f) | Oct 26, 2022 |
| HP            | 650                         | [d7b73bebc7](https://linux-hardware.org/?probe=d7b73bebc7) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | [95707c7cd5](https://linux-hardware.org/?probe=95707c7cd5) | Oct 25, 2022 |
| Timi          | RedmiBook Pro 14S           | [f81e674faf](https://linux-hardware.org/?probe=f81e674faf) | Oct 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [d6275970a0](https://linux-hardware.org/?probe=d6275970a0) | Oct 21, 2022 |
| HP            | Laptop 15-bs2xx             | [0fd75382e9](https://linux-hardware.org/?probe=0fd75382e9) | Oct 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [facb462239](https://linux-hardware.org/?probe=facb462239) | Oct 20, 2022 |
| MSI           | GE75 Raider 10SF            | [dd4102e2e7](https://linux-hardware.org/?probe=dd4102e2e7) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [5e31cc470c](https://linux-hardware.org/?probe=5e31cc470c) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00fece9d77](https://linux-hardware.org/?probe=00fece9d77) | Oct 18, 2022 |
| ASUSTek       | X441SA                      | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Google        | Liara                       | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| HP            | 340S G7 Notebook PC         | [1927ae6949](https://linux-hardware.org/?probe=1927ae6949) | Oct 12, 2022 |
| Lenovo        | V110-15AST 80TD             | [9d4b6fafb6](https://linux-hardware.org/?probe=9d4b6fafb6) | Oct 12, 2022 |
| ASUSTek       | S550CA                      | [261f171b10](https://linux-hardware.org/?probe=261f171b10) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Acer          | Swift SF314-51              | [cfc56878f0](https://linux-hardware.org/?probe=cfc56878f0) | Oct 07, 2022 |
| Toshiba       | Satellite L500              | [90c1d12ca3](https://linux-hardware.org/?probe=90c1d12ca3) | Oct 07, 2022 |
| Packard Be... | EasyNote TJ65               | [bb815f037b](https://linux-hardware.org/?probe=bb815f037b) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| HP            | 250 G4                      | [7c892fab7a](https://linux-hardware.org/?probe=7c892fab7a) | Oct 03, 2022 |
| HP            | 255 G8 Notebook PC          | [1a2e047ca1](https://linux-hardware.org/?probe=1a2e047ca1) | Oct 03, 2022 |
| MSI           | GF65 Thin 9SD               | [a761de487d](https://linux-hardware.org/?probe=a761de487d) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| MSI           | Modern 14 B5M               | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| ASUSTek       | GL753VE                     | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| HP            | EliteBook 745 G6            | [f9eecf6781](https://linux-hardware.org/?probe=f9eecf6781) | Sep 28, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | [658f9b891f](https://linux-hardware.org/?probe=658f9b891f) | Sep 27, 2022 |
| Apple         | MacBookPro8,1               | [c0d2617a28](https://linux-hardware.org/?probe=c0d2617a28) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [2b3c66f0ee](https://linux-hardware.org/?probe=2b3c66f0ee) | Sep 24, 2022 |
| HP            | 250 G4                      | [5d4c56fe14](https://linux-hardware.org/?probe=5d4c56fe14) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8e7a7a914c](https://linux-hardware.org/?probe=8e7a7a914c) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [031f4bb4f1](https://linux-hardware.org/?probe=031f4bb4f1) | Sep 23, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [d852d9e0dd](https://linux-hardware.org/?probe=d852d9e0dd) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [6f43da7fb4](https://linux-hardware.org/?probe=6f43da7fb4) | Sep 22, 2022 |
| ASUSTek       | GL553VD                     | [e6cb381fd2](https://linux-hardware.org/?probe=e6cb381fd2) | Sep 21, 2022 |
| ASUSTek       | G74Sx                       | [e8f0a018c9](https://linux-hardware.org/?probe=e8f0a018c9) | Sep 19, 2022 |
| Acer          | Aspire A515-41G             | [434b1869d7](https://linux-hardware.org/?probe=434b1869d7) | Sep 16, 2022 |
| MSI           | Summit E13FlipEvo A12MT     | [465e8d2c86](https://linux-hardware.org/?probe=465e8d2c86) | Sep 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [13cd2039a1](https://linux-hardware.org/?probe=13cd2039a1) | Sep 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S58700    | [9d9d51e924](https://linux-hardware.org/?probe=9d9d51e924) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| Gigabyte      | AORUS 15G XC                | [4b0e97e947](https://linux-hardware.org/?probe=4b0e97e947) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| MSI           | Alpha 15 B5EEK              | [cf9447ce8c](https://linux-hardware.org/?probe=cf9447ce8c) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Timi          | TM1703                      | [5c30ece6ff](https://linux-hardware.org/?probe=5c30ece6ff) | Sep 08, 2022 |
| HP            | ProBook 450 G0              | [07dfc865cf](https://linux-hardware.org/?probe=07dfc865cf) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| Timi          | TM1703                      | [fb7386017f](https://linux-hardware.org/?probe=fb7386017f) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [dd3b771e55](https://linux-hardware.org/?probe=dd3b771e55) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e8887916fa](https://linux-hardware.org/?probe=e8887916fa) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [a75fed8b3f](https://linux-hardware.org/?probe=a75fed8b3f) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | [cd613ebcd2](https://linux-hardware.org/?probe=cd613ebcd2) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [0e4f12b377](https://linux-hardware.org/?probe=0e4f12b377) | Sep 04, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | [2667cd1609](https://linux-hardware.org/?probe=2667cd1609) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [05221c6c18](https://linux-hardware.org/?probe=05221c6c18) | Sep 03, 2022 |
| ASUSTek       | X580VN                      | [fe8f1a7e6f](https://linux-hardware.org/?probe=fe8f1a7e6f) | Sep 03, 2022 |
| HP            | OMEN by Laptop 16z-c000     | [edc4a4ce85](https://linux-hardware.org/?probe=edc4a4ce85) | Sep 03, 2022 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | [3a8cfc8781](https://linux-hardware.org/?probe=3a8cfc8781) | Sep 01, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | [94b00f5da5](https://linux-hardware.org/?probe=94b00f5da5) | Aug 27, 2022 |
| Google        | Peppy                       | [be4ecba4dc](https://linux-hardware.org/?probe=be4ecba4dc) | Aug 26, 2022 |
| Google        | Auron_Yuna                  | [de2984c01a](https://linux-hardware.org/?probe=de2984c01a) | Aug 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| HUAWEI        | KLVL-WXX9                   | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| HP            | Elite x2 1012 G1            | [94fb37c745](https://linux-hardware.org/?probe=94fb37c745) | Aug 14, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [b391d570ba](https://linux-hardware.org/?probe=b391d570ba) | Aug 12, 2022 |
| Apple         | MacBookPro14,2              | [9e297d5dde](https://linux-hardware.org/?probe=9e297d5dde) | Aug 11, 2022 |
| ASUSTek       | GL502VT                     | [5e95e514a4](https://linux-hardware.org/?probe=5e95e514a4) | Aug 11, 2022 |
| HP            | Elite x2 1012 G1            | [a76e460266](https://linux-hardware.org/?probe=a76e460266) | Aug 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d76760ffa4](https://linux-hardware.org/?probe=d76760ffa4) | Aug 11, 2022 |
| Dell          | Inspiron 5402               | [5373247b06](https://linux-hardware.org/?probe=5373247b06) | Aug 05, 2022 |
| Apple         | MacBookPro14,2              | [d1079f3fba](https://linux-hardware.org/?probe=d1079f3fba) | Aug 04, 2022 |
| Positivo      | S14BW01                     | [28c70dfa85](https://linux-hardware.org/?probe=28c70dfa85) | Aug 04, 2022 |
| HP            | EliteBook 745 G6            | [0bcc9863e3](https://linux-hardware.org/?probe=0bcc9863e3) | Jul 31, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| Acer          | Nitro AN515-43              | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [1a394fdf59](https://linux-hardware.org/?probe=1a394fdf59) | Jul 18, 2022 |
| Lenovo        | ThinkPad E595 20NF001HGE    | [9d3a54dbcf](https://linux-hardware.org/?probe=9d3a54dbcf) | Jul 17, 2022 |
| ASUSTek       | GL753VE                     | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| HP            | Laptop 14-fq1xxx            | [9aa0a38b17](https://linux-hardware.org/?probe=9aa0a38b17) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | [b9b09609b8](https://linux-hardware.org/?probe=b9b09609b8) | Jul 01, 2022 |
| HUAWEI        | MACH-WX9                    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| HONOR         | BBR-WAX9                    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| Lenovo        | V330-14ARR 81B1             | [9816b1d616](https://linux-hardware.org/?probe=9816b1d616) | Jun 23, 2022 |
| Acer          | Aspire E5-575G              | [dc04d6eb1a](https://linux-hardware.org/?probe=dc04d6eb1a) | Jun 18, 2022 |
| ASUSTek       | N56VB                       | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| Dell          | Latitude XT                 | [6ca0e5ca92](https://linux-hardware.org/?probe=6ca0e5ca92) | Jun 14, 2022 |
| Dell          | Latitude E6440              | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| Acer          | Aspire A515-43              | [343315ec17](https://linux-hardware.org/?probe=343315ec17) | Jun 06, 2022 |
| ASUSTek       | GL753VE                     | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| Dell          | Latitude 5289               | [f9e3e0fa57](https://linux-hardware.org/?probe=f9e3e0fa57) | May 30, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| Sony          | VPCCA17FX                   | [4ced9d5222](https://linux-hardware.org/?probe=4ced9d5222) | May 26, 2022 |
| Dell          | Latitude E6510              | [52b94e68a9](https://linux-hardware.org/?probe=52b94e68a9) | May 23, 2022 |
| Timi          | A35S                        | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | [c4e15012d5](https://linux-hardware.org/?probe=c4e15012d5) | May 15, 2022 |
| Dell          | Inspiron 3580               | [33dbac4352](https://linux-hardware.org/?probe=33dbac4352) | May 15, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [5dea5cd6ff](https://linux-hardware.org/?probe=5dea5cd6ff) | May 14, 2022 |
| HP            | Notebook                    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| Unknown       | Unknown                     | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Nitro AN515-45              | [34272a60d1](https://linux-hardware.org/?probe=34272a60d1) | May 10, 2022 |
| HP            | ProBook 440 G4              | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| Chuwi         | GemiBook Pro                | [b5145fe094](https://linux-hardware.org/?probe=b5145fe094) | May 08, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [6a3cbcae26](https://linux-hardware.org/?probe=6a3cbcae26) | May 06, 2022 |
| Acer          | Swift SF314-41              | [3dbf93ec7f](https://linux-hardware.org/?probe=3dbf93ec7f) | May 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| ASUSTek       | X71Vn                       | [b31a7dce8b](https://linux-hardware.org/?probe=b31a7dce8b) | Apr 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| HUAWEI        | MACH-WX9                    | [0199a1bcec](https://linux-hardware.org/?probe=0199a1bcec) | Apr 24, 2022 |
| Dell          | Latitude 7280               | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| Google        | Celes                       | [a1a2262b88](https://linux-hardware.org/?probe=a1a2262b88) | Apr 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [5a58c1f799](https://linux-hardware.org/?probe=5a58c1f799) | Apr 18, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | [10a97e42a3](https://linux-hardware.org/?probe=10a97e42a3) | Apr 17, 2022 |
| Google        | Candy                       | [77b6731597](https://linux-hardware.org/?probe=77b6731597) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | [2b3ac63766](https://linux-hardware.org/?probe=2b3ac63766) | Apr 16, 2022 |
| HP            | Laptop 14-dq4xxx            | [a892a2412c](https://linux-hardware.org/?probe=a892a2412c) | Apr 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8350598ef6](https://linux-hardware.org/?probe=8350598ef6) | Apr 15, 2022 |
| Dell          | Latitude E6540              | [939dbc38d3](https://linux-hardware.org/?probe=939dbc38d3) | Apr 15, 2022 |
| HP            | Pavilion Notebook           | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| Acer          | Swift SF314-57G             | [b9b31b0528](https://linux-hardware.org/?probe=b9b31b0528) | Apr 14, 2022 |
| Dell          | XPS 15 7590                 | [d90283da2d](https://linux-hardware.org/?probe=d90283da2d) | Apr 13, 2022 |
| MSI           | Modern 15 A11M              | [c3202f68fc](https://linux-hardware.org/?probe=c3202f68fc) | Apr 13, 2022 |
| ILLEGEAR      | ROGUE                       | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Packard Be... | EasyNote ENTG71BM           | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| TrekStor      | Notebook Slim S130          | [febbb5b9a2](https://linux-hardware.org/?probe=febbb5b9a2) | Apr 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [3327822265](https://linux-hardware.org/?probe=3327822265) | Apr 06, 2022 |
| HP            | 250 G7 Notebook PC          | [9170392920](https://linux-hardware.org/?probe=9170392920) | Apr 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [376167460b](https://linux-hardware.org/?probe=376167460b) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [ee491ed7f4](https://linux-hardware.org/?probe=ee491ed7f4) | Mar 29, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [921004463e](https://linux-hardware.org/?probe=921004463e) | Mar 23, 2022 |
| HP            | Laptop 15-bw0xx             | [3500cd92bf](https://linux-hardware.org/?probe=3500cd92bf) | Mar 19, 2022 |
| Acer          | Extensa 2520                | [f070f33060](https://linux-hardware.org/?probe=f070f33060) | Mar 19, 2022 |
| Acer          | Extensa 2520                | [f2003c1f90](https://linux-hardware.org/?probe=f2003c1f90) | Mar 19, 2022 |
| ASUSTek       | G752VT                      | [632814d6a3](https://linux-hardware.org/?probe=632814d6a3) | Mar 18, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [7e64ef177c](https://linux-hardware.org/?probe=7e64ef177c) | Mar 18, 2022 |
| Lenovo        | V330-14IKB 81B0             | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [d742a1c2fa](https://linux-hardware.org/?probe=d742a1c2fa) | Mar 16, 2022 |
| Toshiba       | Satellite Pro C50-A-1E6     | [ad8e612da5](https://linux-hardware.org/?probe=ad8e612da5) | Mar 15, 2022 |
| Google        | Akemi                       | [6a52c103e9](https://linux-hardware.org/?probe=6a52c103e9) | Mar 14, 2022 |
| Dell          | Precision M6800             | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| ASUSTek       | G751JT                      | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| Unknown       | Unknown                     | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Acer          | Aspire E5-575               | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Dell          | Latitude E5430 non-vPro     | [2d2bd57c8b](https://linux-hardware.org/?probe=2d2bd57c8b) | Mar 06, 2022 |
| HP            | ZBook 17 G2                 | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [d3cc5d36be](https://linux-hardware.org/?probe=d3cc5d36be) | Feb 27, 2022 |
| Eluktronic... | Prometheus XVII             | [0797cebf2d](https://linux-hardware.org/?probe=0797cebf2d) | Feb 26, 2022 |
| Dell          | Latitude 3420               | [fb586744c3](https://linux-hardware.org/?probe=fb586744c3) | Feb 22, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [655c17b9ff](https://linux-hardware.org/?probe=655c17b9ff) | Feb 20, 2022 |
| Radxa         | ROCK Pi X v1.4              | [dd6d9dc630](https://linux-hardware.org/?probe=dd6d9dc630) | Feb 19, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [973e1c8d91](https://linux-hardware.org/?probe=973e1c8d91) | Feb 19, 2022 |
| Acer          | Aspire E1-572G              | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d98a594e28](https://linux-hardware.org/?probe=d98a594e28) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Eluktronic... | Prometheus XVII             | [36436d1aff](https://linux-hardware.org/?probe=36436d1aff) | Feb 17, 2022 |
| HUAWEI        | HLYL-WXX9                   | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| ASUSTek       | UX490UA                     | [5e40078555](https://linux-hardware.org/?probe=5e40078555) | Feb 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [f84892675f](https://linux-hardware.org/?probe=f84892675f) | Feb 12, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [dda932e1ae](https://linux-hardware.org/?probe=dda932e1ae) | Feb 11, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [c79fe1743d](https://linux-hardware.org/?probe=c79fe1743d) | Feb 10, 2022 |
| Dell          | G3 3500                     | [92ee625013](https://linux-hardware.org/?probe=92ee625013) | Feb 09, 2022 |
| HP            | Pavilion 10 TS              | [1228be8404](https://linux-hardware.org/?probe=1228be8404) | Feb 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [f2719a9d26](https://linux-hardware.org/?probe=f2719a9d26) | Feb 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Dell          | Latitude E4310              | [ef92697af7](https://linux-hardware.org/?probe=ef92697af7) | Feb 07, 2022 |
| Dell          | Latitude E6400              | [919eb44cc5](https://linux-hardware.org/?probe=919eb44cc5) | Feb 07, 2022 |
| Acer          | Aspire V5-471               | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| HP            | Pavilion dv7                | [28bb1241de](https://linux-hardware.org/?probe=28bb1241de) | Feb 06, 2022 |
| Notebook      | NH5x_7xDPx                  | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| HUAWEI        | MACH-WX9                    | [4998bf6630](https://linux-hardware.org/?probe=4998bf6630) | Feb 02, 2022 |
| HP            | Pavilion g6                 | [c2b7d7cdd1](https://linux-hardware.org/?probe=c2b7d7cdd1) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| HP            | 250 G7 Notebook PC          | [b8f0614b9c](https://linux-hardware.org/?probe=b8f0614b9c) | Feb 01, 2022 |
| HP            | Pavilion g6                 | [be25fc4f46](https://linux-hardware.org/?probe=be25fc4f46) | Feb 01, 2022 |
| Lenovo        | Yoga 700-14ISK 80QD         | [de0d67e8c4](https://linux-hardware.org/?probe=de0d67e8c4) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| Dell          | Inspiron 3542               | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [cc0c86531b](https://linux-hardware.org/?probe=cc0c86531b) | Jan 22, 2022 |
| ASUSTek       | K45VD                       | [206ce8c174](https://linux-hardware.org/?probe=206ce8c174) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | [6eafcfd89d](https://linux-hardware.org/?probe=6eafcfd89d) | Jan 18, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Acer          | Swift SF514-54T             | [dffa1b1708](https://linux-hardware.org/?probe=dffa1b1708) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | [cf529c7ad0](https://linux-hardware.org/?probe=cf529c7ad0) | Jan 14, 2022 |
| HUAWEI        | MACH-WX9                    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| HUAWEI        | MACH-WX9                    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [568c503df0](https://linux-hardware.org/?probe=568c503df0) | Jan 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb627691ce](https://linux-hardware.org/?probe=fb627691ce) | Jan 07, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c22ba841f6](https://linux-hardware.org/?probe=c22ba841f6) | Jan 06, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [be129c3a7a](https://linux-hardware.org/?probe=be129c3a7a) | Jan 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| MSI           | GP66 Leopard 10UH           | [e9689e292c](https://linux-hardware.org/?probe=e9689e292c) | Jan 05, 2022 |
| Dell          | Inspiron 5520               | [5ce6cac5cb](https://linux-hardware.org/?probe=5ce6cac5cb) | Jan 04, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [c10faa4e15](https://linux-hardware.org/?probe=c10faa4e15) | Jan 04, 2022 |
| ASUSTek       | N43SL                       | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| Timi          | A35S                        | [2dafd53d09](https://linux-hardware.org/?probe=2dafd53d09) | Jan 04, 2022 |
| HP            | EliteBook 2540p             | [12ce36d52f](https://linux-hardware.org/?probe=12ce36d52f) | Jan 03, 2022 |
| Acer          | Aspire A315-56              | [2edffdea76](https://linux-hardware.org/?probe=2edffdea76) | Jan 03, 2022 |
| Dell          | Inspiron 3542               | [a611e12778](https://linux-hardware.org/?probe=a611e12778) | Dec 31, 2021 |
| Dell          | Precision 5560              | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [e4d3f29412](https://linux-hardware.org/?probe=e4d3f29412) | Dec 30, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [b608797946](https://linux-hardware.org/?probe=b608797946) | Dec 28, 2021 |
| HP            | Laptop 14-fq0xxx            | [756df875af](https://linux-hardware.org/?probe=756df875af) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | [cd01eec1a8](https://linux-hardware.org/?probe=cd01eec1a8) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | [4d153ddb81](https://linux-hardware.org/?probe=4d153ddb81) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [deb1a17957](https://linux-hardware.org/?probe=deb1a17957) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [ca89ed6eab](https://linux-hardware.org/?probe=ca89ed6eab) | Dec 23, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [384617e5a7](https://linux-hardware.org/?probe=384617e5a7) | Dec 22, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [8c9fc05c39](https://linux-hardware.org/?probe=8c9fc05c39) | Dec 22, 2021 |
| Unknown       | Unknown                     | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [7a6594a954](https://linux-hardware.org/?probe=7a6594a954) | Dec 19, 2021 |
| MSI           | Modern 14 B5M               | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0LU0... | [ab6c683160](https://linux-hardware.org/?probe=ab6c683160) | Dec 16, 2021 |
| Dell          | Inspiron 5558               | [16daa16444](https://linux-hardware.org/?probe=16daa16444) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| HP            | 255 G7 Notebook PC          | [a34aa5357b](https://linux-hardware.org/?probe=a34aa5357b) | Dec 14, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Lenovo        | V14 G2 ITL 82NM             | [939be3ba51](https://linux-hardware.org/?probe=939be3ba51) | Dec 10, 2021 |
| MSI           | Prestige 15 A10SC           | [706fc926ca](https://linux-hardware.org/?probe=706fc926ca) | Dec 08, 2021 |
| Dell          | Latitude 7480               | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| Unknown       | Unknown                     | [2070780ca9](https://linux-hardware.org/?probe=2070780ca9) | Dec 07, 2021 |
| Framework     | Laptop                      | [c1a31372f4](https://linux-hardware.org/?probe=c1a31372f4) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [b49088935d](https://linux-hardware.org/?probe=b49088935d) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [7cdf0f8f44](https://linux-hardware.org/?probe=7cdf0f8f44) | Dec 04, 2021 |
| Apple         | MacBookAir6,2               | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | Bravo 15 B5DD               | [fc7c1ff3c8](https://linux-hardware.org/?probe=fc7c1ff3c8) | Nov 24, 2021 |
| Unknown       | Unknown                     | [b862ee20d9](https://linux-hardware.org/?probe=b862ee20d9) | Nov 24, 2021 |
| Unknown       | Unknown                     | [0555569b70](https://linux-hardware.org/?probe=0555569b70) | Nov 24, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [2b67e46016](https://linux-hardware.org/?probe=2b67e46016) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| MSI           | GS63VR 6RF                  | [2d9061c72e](https://linux-hardware.org/?probe=2d9061c72e) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [e6eb602b05](https://linux-hardware.org/?probe=e6eb602b05) | Nov 22, 2021 |
| HP            | 15 TS                       | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [a3d3e0eecd](https://linux-hardware.org/?probe=a3d3e0eecd) | Nov 20, 2021 |
| Dell          | XPS 13 9350                 | [ec54ffae7a](https://linux-hardware.org/?probe=ec54ffae7a) | Nov 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [778d32ce4b](https://linux-hardware.org/?probe=778d32ce4b) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [9fc3f12603](https://linux-hardware.org/?probe=9fc3f12603) | Nov 16, 2021 |
| HUAWEI        | HN-WX9X                     | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [c11672a55e](https://linux-hardware.org/?probe=c11672a55e) | Nov 11, 2021 |
| ASUSTek       | G751JT                      | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [e95d2fa980](https://linux-hardware.org/?probe=e95d2fa980) | Nov 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [85dff2829f](https://linux-hardware.org/?probe=85dff2829f) | Nov 03, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [222ce004da](https://linux-hardware.org/?probe=222ce004da) | Nov 01, 2021 |
| ASUSTek       | G751JT                      | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3fcea4d382](https://linux-hardware.org/?probe=3fcea4d382) | Oct 29, 2021 |
| Acer          | Aspire E5-573G              | [cce67d37aa](https://linux-hardware.org/?probe=cce67d37aa) | Oct 28, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [689f9368f1](https://linux-hardware.org/?probe=689f9368f1) | Oct 23, 2021 |
| Apple         | MacBookPro16,2              | [7b3cdda6e2](https://linux-hardware.org/?probe=7b3cdda6e2) | Oct 20, 2021 |
| HP            | ENVY 6                      | [94471889b0](https://linux-hardware.org/?probe=94471889b0) | Oct 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [ff566c77ce](https://linux-hardware.org/?probe=ff566c77ce) | Oct 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [2d3f367fa7](https://linux-hardware.org/?probe=2d3f367fa7) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | [6e745a1ec9](https://linux-hardware.org/?probe=6e745a1ec9) | Oct 17, 2021 |
| Dell          | Latitude E6410              | [68d7531397](https://linux-hardware.org/?probe=68d7531397) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | [8d0e93e90f](https://linux-hardware.org/?probe=8d0e93e90f) | Oct 16, 2021 |
| Lenovo        | Z50-70 20354                | [a852927b57](https://linux-hardware.org/?probe=a852927b57) | Oct 13, 2021 |
| Dell          | Precision M4400             | [bae8becab1](https://linux-hardware.org/?probe=bae8becab1) | Oct 11, 2021 |
| Google        | Kindred                     | [9420945432](https://linux-hardware.org/?probe=9420945432) | Oct 10, 2021 |
| Dell          | Latitude E4300              | [c486155f48](https://linux-hardware.org/?probe=c486155f48) | Oct 10, 2021 |
| Dell          | Latitude E4300              | [52e0d626fa](https://linux-hardware.org/?probe=52e0d626fa) | Oct 10, 2021 |
| Dell          | Latitude E6410              | [ebfe78c927](https://linux-hardware.org/?probe=ebfe78c927) | Oct 08, 2021 |
| Dell          | G3 3500                     | [b4e985bcba](https://linux-hardware.org/?probe=b4e985bcba) | Oct 08, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | Z50-70 20354                | [beda62c6f4](https://linux-hardware.org/?probe=beda62c6f4) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0923a8b728](https://linux-hardware.org/?probe=0923a8b728) | Oct 05, 2021 |
| Dell          | Precision M4400             | [ab43bad624](https://linux-hardware.org/?probe=ab43bad624) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9c8bc954a7](https://linux-hardware.org/?probe=9c8bc954a7) | Oct 02, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [dc91b564a8](https://linux-hardware.org/?probe=dc91b564a8) | Sep 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [86c4b5769f](https://linux-hardware.org/?probe=86c4b5769f) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [263233be76](https://linux-hardware.org/?probe=263233be76) | Sep 28, 2021 |
| HP            | Pavilion dv6                | [2a6a76f702](https://linux-hardware.org/?probe=2a6a76f702) | Sep 26, 2021 |
| Lenovo        | ThinkPad T480 20L6S3S500    | [067f3cf110](https://linux-hardware.org/?probe=067f3cf110) | Sep 26, 2021 |
| Lenovo        | ThinkPad T470 20HES2SF00    | [9cf10e22a6](https://linux-hardware.org/?probe=9cf10e22a6) | Sep 25, 2021 |
| Lenovo        | ThinkPad E460 20ET004LGE    | [b64e2c4a07](https://linux-hardware.org/?probe=b64e2c4a07) | Sep 25, 2021 |
| Dell          | Precision 3560              | [d9b527db16](https://linux-hardware.org/?probe=d9b527db16) | Sep 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1e1e40ce8b](https://linux-hardware.org/?probe=1e1e40ce8b) | Sep 22, 2021 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [711e2e3960](https://linux-hardware.org/?probe=711e2e3960) | Sep 22, 2021 |
| Dell          | XPS 15 7590                 | [3a7231ce53](https://linux-hardware.org/?probe=3a7231ce53) | Sep 17, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [8dfad66767](https://linux-hardware.org/?probe=8dfad66767) | Sep 16, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | [3e845646c9](https://linux-hardware.org/?probe=3e845646c9) | Sep 15, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | [0fe0fa66d6](https://linux-hardware.org/?probe=0fe0fa66d6) | Sep 14, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | [d5e170957e](https://linux-hardware.org/?probe=d5e170957e) | Sep 14, 2021 |
| Acer          | Nitro AN515-54              | [8f215120c2](https://linux-hardware.org/?probe=8f215120c2) | Sep 13, 2021 |
| AMI           | Intel                       | [49dd022241](https://linux-hardware.org/?probe=49dd022241) | Sep 10, 2021 |
| Razer         | Blade 15 Advanced Model ... | [0c83ae1e11](https://linux-hardware.org/?probe=0c83ae1e11) | Sep 10, 2021 |
| Lenovo        | Legion Y545 81Q6            | [167df4c15e](https://linux-hardware.org/?probe=167df4c15e) | Sep 09, 2021 |
| Dell          | Latitude E4310              | [34c3815468](https://linux-hardware.org/?probe=34c3815468) | Sep 02, 2021 |
| TrekStor      | Primebook P14               | [026e7277ee](https://linux-hardware.org/?probe=026e7277ee) | Sep 02, 2021 |
| HP            | Laptop 15s-fq2xxx           | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| Dell          | Precision M4400             | [289a2606bd](https://linux-hardware.org/?probe=289a2606bd) | Sep 02, 2021 |
| Apple         | MacBookAir7,2               | [581b1be43c](https://linux-hardware.org/?probe=581b1be43c) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d3ab28e58e](https://linux-hardware.org/?probe=d3ab28e58e) | Aug 30, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [24a34a526e](https://linux-hardware.org/?probe=24a34a526e) | Aug 28, 2021 |
| Lenovo        | IdeaPad 510S-14IKB 80UV     | [146390e85e](https://linux-hardware.org/?probe=146390e85e) | Aug 25, 2021 |
| ASUSTek       | G752VT                      | [23dea85a93](https://linux-hardware.org/?probe=23dea85a93) | Aug 24, 2021 |
| Dell          | Latitude E7440              | [0de5415ad7](https://linux-hardware.org/?probe=0de5415ad7) | Aug 22, 2021 |
| Dell          | Inspiron 5577               | [ae8d8171a7](https://linux-hardware.org/?probe=ae8d8171a7) | Aug 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [71645376f3](https://linux-hardware.org/?probe=71645376f3) | Aug 13, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [5d560f16cc](https://linux-hardware.org/?probe=5d560f16cc) | Aug 12, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [9be95b3419](https://linux-hardware.org/?probe=9be95b3419) | Aug 12, 2021 |
| HP            | EliteBook 745 G6            | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Dell          | Inspiron 5570               | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [52118232ff](https://linux-hardware.org/?probe=52118232ff) | Aug 10, 2021 |
| Notebook      | W65_67SZ                    | [ddd6f26db4](https://linux-hardware.org/?probe=ddd6f26db4) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [1ccf2e3d28](https://linux-hardware.org/?probe=1ccf2e3d28) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [b5b8bac74a](https://linux-hardware.org/?probe=b5b8bac74a) | Jul 26, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [12d6be24d7](https://linux-hardware.org/?probe=12d6be24d7) | Jul 25, 2021 |
| Apple         | MacBookAir7,2               | [a5959b657f](https://linux-hardware.org/?probe=a5959b657f) | Jul 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [f8f9bf0717](https://linux-hardware.org/?probe=f8f9bf0717) | Jul 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [7cdf389d4c](https://linux-hardware.org/?probe=7cdf389d4c) | Jul 22, 2021 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [4421b175f7](https://linux-hardware.org/?probe=4421b175f7) | Jul 16, 2021 |
| Acer          | Predator G9-792             | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| Acer          | Aspire A515-43              | [c79cfacd5e](https://linux-hardware.org/?probe=c79cfacd5e) | Jul 05, 2021 |
| Apple         | MacBookPro9,2               | [282a2e2926](https://linux-hardware.org/?probe=282a2e2926) | Jul 04, 2021 |
| Acer          | Nitro AN515-54              | [3be93cbc0c](https://linux-hardware.org/?probe=3be93cbc0c) | Jul 03, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | [181cfa9437](https://linux-hardware.org/?probe=181cfa9437) | Jul 01, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [a92028f13a](https://linux-hardware.org/?probe=a92028f13a) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | [56a361debf](https://linux-hardware.org/?probe=56a361debf) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | [431df4bc98](https://linux-hardware.org/?probe=431df4bc98) | Jul 01, 2021 |
| Dell          | G7 7588                     | [259694c4a1](https://linux-hardware.org/?probe=259694c4a1) | Jun 27, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [4b70691f2e](https://linux-hardware.org/?probe=4b70691f2e) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [397e22935b](https://linux-hardware.org/?probe=397e22935b) | Jun 25, 2021 |
| HP            | 255 G7 Notebook PC          | [2762be36c4](https://linux-hardware.org/?probe=2762be36c4) | Jun 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [48bda0fbd3](https://linux-hardware.org/?probe=48bda0fbd3) | Jun 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [117372a8ff](https://linux-hardware.org/?probe=117372a8ff) | Jun 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [6b6205bc5d](https://linux-hardware.org/?probe=6b6205bc5d) | May 31, 2021 |
| HP            | EliteBook Revolve 810       | [24758ed5b3](https://linux-hardware.org/?probe=24758ed5b3) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cad013a6a5](https://linux-hardware.org/?probe=cad013a6a5) | May 31, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | [4c600416f9](https://linux-hardware.org/?probe=4c600416f9) | May 28, 2021 |
| ASUSTek       | K45DR                       | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [99ab618bee](https://linux-hardware.org/?probe=99ab618bee) | May 25, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | [684dfb967f](https://linux-hardware.org/?probe=684dfb967f) | May 22, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | [c18360d17e](https://linux-hardware.org/?probe=c18360d17e) | May 22, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [c1b869c13a](https://linux-hardware.org/?probe=c1b869c13a) | May 22, 2021 |
| Acer          | Swift SF314-51              | [a666be1df5](https://linux-hardware.org/?probe=a666be1df5) | May 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [457597b9d1](https://linux-hardware.org/?probe=457597b9d1) | May 21, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [e18030e5f0](https://linux-hardware.org/?probe=e18030e5f0) | May 20, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [7e5dbc86b9](https://linux-hardware.org/?probe=7e5dbc86b9) | May 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [14b3851754](https://linux-hardware.org/?probe=14b3851754) | May 20, 2021 |
| Notebook      | NS50MU                      | [8e08645823](https://linux-hardware.org/?probe=8e08645823) | May 19, 2021 |
| Lenovo        | ThinkPad P51 20HHCT01WW     | [3f42eaf28b](https://linux-hardware.org/?probe=3f42eaf28b) | May 19, 2021 |
| MSI           | GE72 6QD                    | [7637f1ad9c](https://linux-hardware.org/?probe=7637f1ad9c) | May 19, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [634c63d316](https://linux-hardware.org/?probe=634c63d316) | May 15, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [17af51e9b1](https://linux-hardware.org/?probe=17af51e9b1) | May 14, 2021 |
| HP            | EliteBook 2170p             | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9048b606d2](https://linux-hardware.org/?probe=9048b606d2) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f02e90a00f](https://linux-hardware.org/?probe=f02e90a00f) | May 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [ec0cb83241](https://linux-hardware.org/?probe=ec0cb83241) | May 10, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | [b3a5056cbf](https://linux-hardware.org/?probe=b3a5056cbf) | May 07, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [365c656e4a](https://linux-hardware.org/?probe=365c656e4a) | May 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [fca3b0c89b](https://linux-hardware.org/?probe=fca3b0c89b) | May 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9e8b256742](https://linux-hardware.org/?probe=9e8b256742) | May 03, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [e7cd00034c](https://linux-hardware.org/?probe=e7cd00034c) | May 02, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [39f6decf99](https://linux-hardware.org/?probe=39f6decf99) | May 02, 2021 |
| HP            | 255 G4                      | [9070448ace](https://linux-hardware.org/?probe=9070448ace) | May 01, 2021 |
| Lenovo        | ThinkPad T61 7659W1W        | [c366a3e7a2](https://linux-hardware.org/?probe=c366a3e7a2) | May 01, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [3d3ef81b3b](https://linux-hardware.org/?probe=3d3ef81b3b) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| Acer          | Extensa 2510                | [1f257d3f4e](https://linux-hardware.org/?probe=1f257d3f4e) | Apr 25, 2021 |
| Lenovo        | E31-80 80MX                 | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [764390758a](https://linux-hardware.org/?probe=764390758a) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [eabc0fa5e5](https://linux-hardware.org/?probe=eabc0fa5e5) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [fae6227cfc](https://linux-hardware.org/?probe=fae6227cfc) | Apr 19, 2021 |
| Toshiba       | Satellite P750              | [d248a5f049](https://linux-hardware.org/?probe=d248a5f049) | Apr 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Dell          | Inspiron 5391               | [80bf268441](https://linux-hardware.org/?probe=80bf268441) | Apr 08, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [9e5b4c92f4](https://linux-hardware.org/?probe=9e5b4c92f4) | Apr 01, 2021 |
| Toshiba       | Satellite L50D-B            | [6fdb3a7d9e](https://linux-hardware.org/?probe=6fdb3a7d9e) | Mar 31, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [269185aba1](https://linux-hardware.org/?probe=269185aba1) | Mar 28, 2021 |
| Dell          | G7 7588                     | [95e0518b2c](https://linux-hardware.org/?probe=95e0518b2c) | Mar 25, 2021 |
| Dell          | Latitude 5300               | [efd4a051e5](https://linux-hardware.org/?probe=efd4a051e5) | Mar 23, 2021 |
| Lenovo        | ThinkPad L460 20FV002EBR    | [f19448d66f](https://linux-hardware.org/?probe=f19448d66f) | Mar 19, 2021 |
| Lenovo        | ThinkPad T520 4239CTO       | [e03adb0720](https://linux-hardware.org/?probe=e03adb0720) | Mar 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [13dfc4a9af](https://linux-hardware.org/?probe=13dfc4a9af) | Mar 17, 2021 |
| Dell          | G5 5505                     | [e8e38279d3](https://linux-hardware.org/?probe=e8e38279d3) | Mar 11, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [062dfb8010](https://linux-hardware.org/?probe=062dfb8010) | Mar 09, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [eec4ef3dce](https://linux-hardware.org/?probe=eec4ef3dce) | Mar 07, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [bd3a730b32](https://linux-hardware.org/?probe=bd3a730b32) | Mar 03, 2021 |
| HP            | Laptop 15-da0xxx            | [88635c9f76](https://linux-hardware.org/?probe=88635c9f76) | Feb 23, 2021 |
| Gigabyte      | AERO 15XV8                  | [c4ecc96eae](https://linux-hardware.org/?probe=c4ecc96eae) | Feb 19, 2021 |
| Apple         | MacBookPro7,1               | [93115f0746](https://linux-hardware.org/?probe=93115f0746) | Feb 14, 2021 |
| Apple         | MacBookPro7,1               | [1bd84f7c03](https://linux-hardware.org/?probe=1bd84f7c03) | Feb 13, 2021 |
| HP            | ZBook 15                    | [dc1d23b1c6](https://linux-hardware.org/?probe=dc1d23b1c6) | Feb 12, 2021 |
| ASUSTek       | GL503VM                     | [72f95227fd](https://linux-hardware.org/?probe=72f95227fd) | Feb 11, 2021 |
| ASUSTek       | GL503VM                     | [130e9bdb5c](https://linux-hardware.org/?probe=130e9bdb5c) | Feb 11, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [43bb3ec644](https://linux-hardware.org/?probe=43bb3ec644) | Feb 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [5856d93198](https://linux-hardware.org/?probe=5856d93198) | Feb 07, 2021 |
| HP            | ENVY Notebook               | [4f20314e69](https://linux-hardware.org/?probe=4f20314e69) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [311f54d837](https://linux-hardware.org/?probe=311f54d837) | Jan 28, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [a0c3014b22](https://linux-hardware.org/?probe=a0c3014b22) | Jan 17, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | [9fd64a3945](https://linux-hardware.org/?probe=9fd64a3945) | Jan 11, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [929b0edb33](https://linux-hardware.org/?probe=929b0edb33) | Jan 11, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [6499961dbf](https://linux-hardware.org/?probe=6499961dbf) | Jan 09, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [2df429a577](https://linux-hardware.org/?probe=2df429a577) | Jan 06, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [f2b808bdd1](https://linux-hardware.org/?probe=f2b808bdd1) | Dec 24, 2020 |
| MSI           | GL75 Leopard 10SDK          | [8b792fe096](https://linux-hardware.org/?probe=8b792fe096) | Dec 23, 2020 |
| HP            | Laptop 15-db1xxx            | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| HP            | EliteBook Revolve 810       | [b6b29c8237](https://linux-hardware.org/?probe=b6b29c8237) | Dec 17, 2020 |
| Apple         | MacBookAir4,2               | [a3ebd820e2](https://linux-hardware.org/?probe=a3ebd820e2) | Dec 17, 2020 |
| Alienware     | 14                          | [3211a0e18d](https://linux-hardware.org/?probe=3211a0e18d) | Dec 12, 2020 |
| HP            | 255 G7 Notebook PC          | [75384533dc](https://linux-hardware.org/?probe=75384533dc) | Dec 06, 2020 |
| Dell          | Precision M6600             | [c3eafadf96](https://linux-hardware.org/?probe=c3eafadf96) | Dec 05, 2020 |
| HP            | 255 G7 Notebook PC          | [7e7ad00d75](https://linux-hardware.org/?probe=7e7ad00d75) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | [7e75c8dc00](https://linux-hardware.org/?probe=7e75c8dc00) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | [2381ec1bad](https://linux-hardware.org/?probe=2381ec1bad) | Nov 30, 2020 |
| MSI           | GT80S 6QE                   | [a938950688](https://linux-hardware.org/?probe=a938950688) | Nov 28, 2020 |
| MSI           | GT80S 6QE                   | [a07d34dcff](https://linux-hardware.org/?probe=a07d34dcff) | Nov 28, 2020 |
| Dell          | Precision M6600             | [990be59736](https://linux-hardware.org/?probe=990be59736) | Nov 21, 2020 |
| ASUSTek       | X550CL                      | [5315051a75](https://linux-hardware.org/?probe=5315051a75) | Nov 21, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2a4a52111f](https://linux-hardware.org/?probe=2a4a52111f) | Nov 21, 2020 |
| Acer          | Aspire V3-575G              | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| Timi          | TM1607                      | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| HP            | Laptop 14-dk1xxx            | [5cdfdbceae](https://linux-hardware.org/?probe=5cdfdbceae) | Oct 26, 2020 |
| HP            | Laptop 14-dk1xxx            | [130d636b9e](https://linux-hardware.org/?probe=130d636b9e) | Oct 26, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [3e19ade739](https://linux-hardware.org/?probe=3e19ade739) | Oct 25, 2020 |
| HP            | Notebook                    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1e6190a4f2](https://linux-hardware.org/?probe=1e6190a4f2) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | [d3265c616b](https://linux-hardware.org/?probe=d3265c616b) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | [01f75c41ed](https://linux-hardware.org/?probe=01f75c41ed) | Oct 20, 2020 |
| Dell          | Inspiron 3493               | [502cfa6428](https://linux-hardware.org/?probe=502cfa6428) | Oct 15, 2020 |
| Dell          | Inspiron 3493               | [459870a593](https://linux-hardware.org/?probe=459870a593) | Oct 14, 2020 |
| ASUSTek       | GL702ZC                     | [c90edc1b80](https://linux-hardware.org/?probe=c90edc1b80) | Oct 12, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [2abc472e43](https://linux-hardware.org/?probe=2abc472e43) | Oct 08, 2020 |
| Acer          | Aspire E5-573               | [89237e04fc](https://linux-hardware.org/?probe=89237e04fc) | Oct 04, 2020 |
| Unknown       | Unknown                     | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [4ec2f0a6cc](https://linux-hardware.org/?probe=4ec2f0a6cc) | Sep 29, 2020 |
| Dell          | G3 3579                     | [6853280510](https://linux-hardware.org/?probe=6853280510) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| Acer          | TravelMate P633-M           | [a7fdf21400](https://linux-hardware.org/?probe=a7fdf21400) | Sep 11, 2020 |
| Dell          | Latitude E6440              | [ddd1e2f728](https://linux-hardware.org/?probe=ddd1e2f728) | Sep 03, 2020 |
| ASUSTek       | UX310UA                     | [90e38ace34](https://linux-hardware.org/?probe=90e38ace34) | Sep 03, 2020 |
| HP            | EliteBook 840 G5            | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [82736e9fa5](https://linux-hardware.org/?probe=82736e9fa5) | Aug 23, 2020 |
| Dell          | Latitude E6430              | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [935afc3dde](https://linux-hardware.org/?probe=935afc3dde) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [fd00cb49a3](https://linux-hardware.org/?probe=fd00cb49a3) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [4830a55da9](https://linux-hardware.org/?probe=4830a55da9) | Jul 27, 2020 |
| Dell          | Latitude 7400               | [69e41d5126](https://linux-hardware.org/?probe=69e41d5126) | Jul 20, 2020 |
| Dell          | Latitude 7400               | [42561b6e01](https://linux-hardware.org/?probe=42561b6e01) | Jul 20, 2020 |
| Dell          | Latitude 7400               | [606ef1afa8](https://linux-hardware.org/?probe=606ef1afa8) | Jul 17, 2020 |
| Lenovo        | ThinkPad E595 20NFS0TD00    | [7fbac3cf0a](https://linux-hardware.org/?probe=7fbac3cf0a) | Jul 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS2J000    | [ed0f57c08d](https://linux-hardware.org/?probe=ed0f57c08d) | Jul 14, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [fc1d360821](https://linux-hardware.org/?probe=fc1d360821) | Jun 29, 2020 |
| Dell          | Inspiron 5559               | [a2e2a6cf66](https://linux-hardware.org/?probe=a2e2a6cf66) | May 12, 2020 |
| Lenovo        | G505s 20255                 | [21f31cf2d0](https://linux-hardware.org/?probe=21f31cf2d0) | Apr 21, 2020 |
| HP            | EliteBook 8770w             | [44b687a5ef](https://linux-hardware.org/?probe=44b687a5ef) | Jan 31, 2020 |
| HP            | EliteBook 830 G6            | [c4078ad25e](https://linux-hardware.org/?probe=c4078ad25e) | Jan 25, 2020 |
| Acer          | Aspire ES1-520              | [12a0136c2d](https://linux-hardware.org/?probe=12a0136c2d) | Jan 20, 2020 |
| Shinelon C... | W65KJ1_KK1                  | [924a887f7d](https://linux-hardware.org/?probe=924a887f7d) | Dec 09, 2019 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [d5c741f8df](https://linux-hardware.org/?probe=d5c741f8df) | Dec 08, 2019 |
| Dell          | Inspiron 7520               | [3477d2f29e](https://linux-hardware.org/?probe=3477d2f29e) | Sep 10, 2019 |
| Dell          | Inspiron 7520               | [80bdb92976](https://linux-hardware.org/?probe=80bdb92976) | Sep 10, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/EndeavourOS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 612       | 87.8%   |
| EndeavourOS         | 85        | 12.2%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| EndeavourOS | 691       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 6.2.8-arch1-1   | 15        | 1.91%   |
| 6.5.9-arch2-1   | 12        | 1.53%   |
| 6.4.12-arch1-1  | 12        | 1.53%   |
| 6.3.9-arch1-1   | 9         | 1.15%   |
| 6.3.4-arch1-1   | 8         | 1.02%   |
| 6.2.10-arch1-1  | 8         | 1.02%   |
| 5.19.7-arch1-1  | 8         | 1.02%   |
| 5.15.12-arch1-1 | 8         | 1.02%   |
| 6.5.5-arch1-1   | 7         | 0.89%   |
| 6.5.3-arch1-1   | 7         | 0.89%   |
| 6.4.11-arch2-1  | 7         | 0.89%   |
| 6.3.1-arch1-1   | 7         | 0.89%   |
| 6.2.9-arch1-1   | 7         | 0.89%   |
| 6.1.12-arch1-1  | 7         | 0.89%   |
| 5.13.13-arch1-1 | 7         | 0.89%   |
| 6.2.2-arch1-1   | 6         | 0.76%   |
| 6.2.13-arch1-1  | 6         | 0.76%   |
| 6.1.1-arch1-1   | 6         | 0.76%   |
| 6.0.9-arch1-1   | 6         | 0.76%   |
| 5.15.10-arch1-1 | 6         | 0.76%   |
| 6.5.7-arch1-1   | 5         | 0.64%   |
| 6.4.7-arch1-1   | 5         | 0.64%   |
| 6.4.3-arch1-2   | 5         | 0.64%   |
| 6.4.1-arch2-1   | 5         | 0.64%   |
| 6.2.12-arch1-1  | 5         | 0.64%   |
| 6.0.2-arch1-1   | 5         | 0.64%   |
| 6.0.12-arch1-1  | 5         | 0.64%   |
| 5.9.14-arch1-1  | 5         | 0.64%   |
| 5.19.13-arch1-1 | 5         | 0.64%   |
| 5.19.11-arch1-1 | 5         | 0.64%   |
| 5.18.16-arch1-1 | 5         | 0.64%   |
| 5.15.4-arch1-1  | 5         | 0.64%   |
| 6.5.4-arch2-1   | 4         | 0.51%   |
| 6.4.10-arch1-1  | 4         | 0.51%   |
| 6.3.5-arch1-1   | 4         | 0.51%   |
| 6.2.7-arch1-1   | 4         | 0.51%   |
| 6.2.5-arch1-1   | 4         | 0.51%   |
| 6.1.8-arch1-1   | 4         | 0.51%   |
| 6.1.7-arch1-1   | 4         | 0.51%   |
| 6.1.4-arch1-1   | 4         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.8   | 16        | 2.04%   |
| 6.5.9   | 14        | 1.78%   |
| 6.4.12  | 14        | 1.78%   |
| 6.3.1   | 14        | 1.78%   |
| 6.4.11  | 12        | 1.53%   |
| 5.15.12 | 11        | 1.4%    |
| 6.3.9   | 10        | 1.27%   |
| 6.3.4   | 10        | 1.27%   |
| 6.1.1   | 10        | 1.27%   |
| 6.0.2   | 10        | 1.27%   |
| 5.19.7  | 10        | 1.27%   |
| 5.13.13 | 10        | 1.27%   |
| 6.5.5   | 9         | 1.15%   |
| 6.4.3   | 9         | 1.15%   |
| 6.4.1   | 9         | 1.15%   |
| 6.1.12  | 9         | 1.15%   |
| 6.0.9   | 9         | 1.15%   |
| 6.4.7   | 8         | 1.02%   |
| 6.2.9   | 8         | 1.02%   |
| 6.2.10  | 8         | 1.02%   |
| 5.15.4  | 8         | 1.02%   |
| 6.5.8   | 7         | 0.89%   |
| 6.5.3   | 7         | 0.89%   |
| 6.2.2   | 7         | 0.89%   |
| 6.2.13  | 7         | 0.89%   |
| 6.0.12  | 7         | 0.89%   |
| 5.19.13 | 7         | 0.89%   |
| 5.15.2  | 7         | 0.89%   |
| 5.12.13 | 7         | 0.89%   |
| 5.11.16 | 7         | 0.89%   |
| 6.5.7   | 6         | 0.76%   |
| 6.3.5   | 6         | 0.76%   |
| 6.2.12  | 6         | 0.76%   |
| 6.0.6   | 6         | 0.76%   |
| 5.19.6  | 6         | 0.76%   |
| 5.19.11 | 6         | 0.76%   |
| 5.17.5  | 6         | 0.76%   |
| 5.17.1  | 6         | 0.76%   |
| 5.15.10 | 6         | 0.76%   |
| 5.14.9  | 6         | 0.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 83        | 10.92%  |
| 5.15    | 72        | 9.47%   |
| 6.2     | 70        | 9.21%   |
| 6.4     | 69        | 9.08%   |
| 6.5     | 57        | 7.5%    |
| 6.3     | 52        | 6.84%   |
| 5.19    | 52        | 6.84%   |
| 6.0     | 46        | 6.05%   |
| 5.16    | 37        | 4.87%   |
| 5.14    | 30        | 3.95%   |
| 5.17    | 29        | 3.82%   |
| 5.18    | 24        | 3.16%   |
| 5.13    | 24        | 3.16%   |
| 5.12    | 24        | 3.16%   |
| 5.9     | 21        | 2.76%   |
| 5.11    | 21        | 2.76%   |
| 5.10    | 20        | 2.63%   |
| 5.8     | 9         | 1.18%   |
| 5.7     | 8         | 1.05%   |
| 5.4     | 6         | 0.79%   |
| 5.6     | 2         | 0.26%   |
| 4.19    | 2         | 0.26%   |
| 6.6     | 1         | 0.13%   |
| 5.17.1  | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 690       | 99.86%  |
| aarch64 | 1         | 0.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 257       | 35.99%  |
| GNOME           | 167       | 23.39%  |
| XFCE            | 137       | 19.19%  |
| i3              | 26        | 3.64%   |
| X-Cinnamon      | 22        | 3.08%   |
| Budgie          | 17        | 2.38%   |
| Unknown         | 16        | 2.24%   |
| KDE             | 14        | 1.96%   |
| sway            | 10        | 1.4%    |
| MATE            | 8         | 1.12%   |
| Hyprland        | 7         | 0.98%   |
| Cinnamon        | 7         | 0.98%   |
| LXQt            | 5         | 0.7%    |
| openbox         | 3         | 0.42%   |
| GNOME Flashback | 3         | 0.42%   |
| bspwm           | 3         | 0.42%   |
| awesome         | 3         | 0.42%   |
| qtile           | 2         | 0.28%   |
| LXDE            | 2         | 0.28%   |
| Deepin          | 2         | 0.28%   |
| xmonad          | 1         | 0.14%   |
| LeftWM          | 1         | 0.14%   |
| GNOME Classic   | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 487       | 68.88%  |
| Wayland | 184       | 26.03%  |
| Tty     | 24        | 3.39%   |
| Unknown | 12        | 1.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 230       | 32.35%  |
| SDDM    | 182       | 25.6%   |
| Unknown | 174       | 24.47%  |
| GDM     | 95        | 13.36%  |
| TDM     | 26        | 3.66%   |
| GREETD  | 2         | 0.28%   |
| LY-DM   | 1         | 0.14%   |
| LEMURS  | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 354       | 50.94%  |
| en_GB   | 53        | 7.63%   |
| it_IT   | 49        | 7.05%   |
| de_DE   | 31        | 4.46%   |
| en_CA   | 25        | 3.6%    |
| en_IN   | 19        | 2.73%   |
| ru_RU   | 17        | 2.45%   |
| fr_FR   | 16        | 2.3%    |
| es_ES   | 11        | 1.58%   |
| en_AU   | 9         | 1.29%   |
| Unknown | 9         | 1.29%   |
| pt_BR   | 8         | 1.15%   |
| pl_PL   | 7         | 1.01%   |
| nl_NL   | 7         | 1.01%   |
| es_MX   | 7         | 1.01%   |
| tr_TR   | 6         | 0.86%   |
| fi_FI   | 6         | 0.86%   |
| en_NZ   | 6         | 0.86%   |
| es_AR   | 5         | 0.72%   |
| en_PH   | 5         | 0.72%   |
| de_AT   | 4         | 0.58%   |
| zh_CN   | 3         | 0.43%   |
| sv_SE   | 3         | 0.43%   |
| pt_PT   | 3         | 0.43%   |
| en_DK   | 3         | 0.43%   |
| ru_UA   | 2         | 0.29%   |
| en_SG   | 2         | 0.29%   |
| en_IL   | 2         | 0.29%   |
| en_HK   | 2         | 0.29%   |
| en_AG   | 2         | 0.29%   |
| sr_RS   | 1         | 0.14%   |
| nl_BE   | 1         | 0.14%   |
| ko_KR   | 1         | 0.14%   |
| id_ID   | 1         | 0.14%   |
| hu_HU   | 1         | 0.14%   |
| hr_HR   | 1         | 0.14%   |
| es_US   | 1         | 0.14%   |
| es_PY   | 1         | 0.14%   |
| es_PE   | 1         | 0.14%   |
| es_CO   | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 463       | 66.14%  |
| BIOS | 237       | 33.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 480       | 68.77%  |
| Btrfs   | 180       | 25.79%  |
| Overlay | 18        | 2.58%   |
| Xfs     | 9         | 1.29%   |
| Tmpfs   | 6         | 0.86%   |
| F2fs    | 2         | 0.29%   |
| Zfs     | 1         | 0.14%   |
| Ext2    | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 473       | 67.67%  |
| Unknown | 172       | 24.61%  |
| MBR     | 54        | 7.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 610       | 87.52%  |
| Yes       | 87        | 12.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 506       | 71.98%  |
| Yes       | 197       | 28.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 191       | 27.64%  |
| Hewlett-Packard     | 112       | 16.21%  |
| ASUSTek Computer    | 108       | 15.63%  |
| Dell                | 77        | 11.14%  |
| Acer                | 46        | 6.66%   |
| MSI                 | 28        | 4.05%   |
| Apple               | 22        | 3.18%   |
| HUAWEI              | 14        | 2.03%   |
| Google              | 12        | 1.74%   |
| Timi                | 11        | 1.59%   |
| Toshiba             | 9         | 1.3%    |
| Notebook            | 7         | 1.01%   |
| Sony                | 5         | 0.72%   |
| Samsung Electronics | 4         | 0.58%   |
| Gigabyte Technology | 4         | 0.58%   |
| TUXEDO              | 3         | 0.43%   |
| Schenker            | 3         | 0.43%   |
| Packard Bell        | 3         | 0.43%   |
| Unknown             | 3         | 0.43%   |
| TrekStor            | 2         | 0.29%   |
| Razer               | 2         | 0.29%   |
| Positivo            | 2         | 0.29%   |
| GPD                 | 2         | 0.29%   |
| Chuwi               | 2         | 0.29%   |
| VIT                 | 1         | 0.14%   |
| Teclast             | 1         | 0.14%   |
| System76            | 1         | 0.14%   |
| Shinelon Computer   | 1         | 0.14%   |
| Radxa               | 1         | 0.14%   |
| Pine Microsystems   | 1         | 0.14%   |
| PC Specialist       | 1         | 0.14%   |
| OriginPC            | 1         | 0.14%   |
| Maibenben           | 1         | 0.14%   |
| ILLEGEAR            | 1         | 0.14%   |
| HONOR               | 1         | 0.14%   |
| Fujitsu             | 1         | 0.14%   |
| Framework           | 1         | 0.14%   |
| eMachines           | 1         | 0.14%   |
| Eluktronics         | 1         | 0.14%   |
| Dynabook            | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBookAir7,2                   | 7         | 1.01%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 4         | 0.58%   |
| Unknown                               | 4         | 0.58%   |
| MSI Modern 14 B5M                     | 3         | 0.43%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.43%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 3         | 0.43%   |
| Lenovo Legion 5 15ACH6H 82JU          | 3         | 0.43%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 3         | 0.43%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5      | 3         | 0.43%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 3         | 0.43%   |
| HUAWEI KLVL-WXX9                      | 3         | 0.43%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 3         | 0.43%   |
| HP Laptop 15-db0xxx                   | 3         | 0.43%   |
| Dell Inspiron 3542                    | 3         | 0.43%   |
| Apple MacBookPro16,2                  | 3         | 0.43%   |
| Acer Aspire E5-575G                   | 3         | 0.43%   |
| Timi TM1701                           | 2         | 0.29%   |
| Timi A35S                             | 2         | 0.29%   |
| Samsung 340XAA/350XAA/550XAA          | 2         | 0.29%   |
| Positivo S14BW01                      | 2         | 0.29%   |
| MSI Modern 15 A5M                     | 2         | 0.29%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS    | 2         | 0.29%   |
| Lenovo ThinkPad T14 Gen 3 21CFCTO1WW  | 2         | 0.29%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MB  | 2         | 0.29%   |
| Lenovo ThinkPad E14 Gen 4 21ECS00000  | 2         | 0.29%   |
| Lenovo ThinkBook 16p Gen 2 20YM       | 2         | 0.29%   |
| Lenovo Legion 5 Pro 16ARH7H 82RG      | 2         | 0.29%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ      | 2         | 0.29%   |
| Lenovo IdeaPad S340-14API 81NB        | 2         | 0.29%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 2         | 0.29%   |
| Lenovo IdeaPad Flex-14API 81SS        | 2         | 0.29%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 2         | 0.29%   |
| Lenovo IdeaPad 5 14ITL05 82FE         | 2         | 0.29%   |
| Lenovo IdeaPad 330-15IKB 81DE         | 2         | 0.29%   |
| Lenovo IdeaPad 320-15ISK 80XH         | 2         | 0.29%   |
| HUAWEI MACH-WX9                       | 2         | 0.29%   |
| HUAWEI HLYL-WXX9                      | 2         | 0.29%   |
| HP ZBook 15 G4                        | 2         | 0.29%   |
| HP Victus by Laptop 16-e0xxx          | 2         | 0.29%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 2         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 93        | 13.46%  |
| Lenovo IdeaPad        | 53        | 7.67%   |
| Acer Aspire           | 29        | 4.2%    |
| ASUS ROG              | 28        | 4.05%   |
| Dell Latitude         | 27        | 3.91%   |
| HP Pavilion           | 22        | 3.18%   |
| HP EliteBook          | 21        | 3.04%   |
| Dell Inspiron         | 21        | 3.04%   |
| HP Laptop             | 17        | 2.46%   |
| ASUS VivoBook         | 17        | 2.46%   |
| Lenovo Legion         | 16        | 2.32%   |
| Lenovo ThinkBook      | 11        | 1.59%   |
| Dell XPS              | 10        | 1.45%   |
| ASUS ASUS             | 10        | 1.45%   |
| MSI Modern            | 9         | 1.3%    |
| Dell Precision        | 9         | 1.3%    |
| ASUS Zenbook          | 9         | 1.3%    |
| Lenovo Yoga           | 8         | 1.16%   |
| ASUS TUF              | 8         | 1.16%   |
| Toshiba Satellite     | 7         | 1.01%   |
| HP 255                | 7         | 1.01%   |
| Apple MacBookAir7     | 7         | 1.01%   |
| Acer Swift            | 7         | 1.01%   |
| HP ZBook              | 6         | 0.87%   |
| HP ProBook            | 6         | 0.87%   |
| HP ENVY               | 6         | 0.87%   |
| Apple MacBookPro16    | 5         | 0.72%   |
| HP 250                | 4         | 0.58%   |
| Unknown               | 4         | 0.58%   |
| Schenker XMG          | 3         | 0.43%   |
| Packard Bell EasyNote | 3         | 0.43%   |
| Notebook NH5x         | 3         | 0.43%   |
| MSI Prestige          | 3         | 0.43%   |
| HUAWEI KLVL-WXX9      | 3         | 0.43%   |
| HP Victus             | 3         | 0.43%   |
| HP OMEN               | 3         | 0.43%   |
| Dell Vostro           | 3         | 0.43%   |
| Dell G3               | 3         | 0.43%   |
| Apple MacBookPro14    | 3         | 0.43%   |
| Acer TravelMate       | 3         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 108       | 15.63%  |
| 2020    | 97        | 14.04%  |
| 2022    | 70        | 10.13%  |
| 2019    | 69        | 9.99%   |
| 2018    | 56        | 8.1%    |
| 2017    | 50        | 7.24%   |
| 2016    | 39        | 5.64%   |
| 2015    | 38        | 5.5%    |
| 2013    | 36        | 5.21%   |
| 2012    | 30        | 4.34%   |
| 2014    | 28        | 4.05%   |
| 2011    | 18        | 2.6%    |
| 2023    | 17        | 2.46%   |
| 2010    | 14        | 2.03%   |
| 2008    | 10        | 1.45%   |
| 2009    | 7         | 1.01%   |
| 2007    | 3         | 0.43%   |
| Unknown | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 691       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 690       | 99.86%  |
| Enabled  | 1         | 0.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 676       | 97.83%  |
| Yes  | 15        | 2.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 189       | 27.12%  |
| 8.01-16.0   | 181       | 25.97%  |
| 16.01-24.0  | 141       | 20.23%  |
| 32.01-64.0  | 77        | 11.05%  |
| 3.01-4.0    | 70        | 10.04%  |
| 24.01-32.0  | 20        | 2.87%   |
| 64.01-256.0 | 13        | 1.87%   |
| 2.01-3.0    | 3         | 0.43%   |
| 1.01-2.0    | 3         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 192       | 25.63%  |
| 4.01-8.0   | 165       | 22.03%  |
| 1.01-2.0   | 165       | 22.03%  |
| 3.01-4.0   | 149       | 19.89%  |
| 8.01-16.0  | 46        | 6.14%   |
| 0.51-1.0   | 25        | 3.34%   |
| 16.01-24.0 | 4         | 0.53%   |
| 0.01-0.5   | 2         | 0.27%   |
| 24.01-32.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 483       | 68.8%   |
| 2      | 195       | 27.78%  |
| 3      | 19        | 2.71%   |
| 4      | 3         | 0.43%   |
| 0      | 2         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 562       | 81.21%  |
| Yes       | 130       | 18.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 509       | 73.24%  |
| No        | 186       | 26.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 686       | 99.13%  |
| No        | 6         | 0.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 636       | 91.64%  |
| No        | 58        | 8.36%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 145       | 20.77%  |
| Italy       | 73        | 10.46%  |
| Germany     | 54        | 7.74%   |
| Canada      | 26        | 3.72%   |
| India       | 25        | 3.58%   |
| Russia      | 22        | 3.15%   |
| UK          | 21        | 3.01%   |
| France      | 21        | 3.01%   |
| Turkey      | 20        | 2.87%   |
| Poland      | 20        | 2.87%   |
| Netherlands | 20        | 2.87%   |
| Brazil      | 18        | 2.58%   |
| Spain       | 16        | 2.29%   |
| Finland     | 16        | 2.29%   |
| Austria     | 10        | 1.43%   |
| Sweden      | 9         | 1.29%   |
| Australia   | 9         | 1.29%   |
| Mexico      | 8         | 1.15%   |
| Indonesia   | 8         | 1.15%   |
| Romania     | 7         | 1%      |
| New Zealand | 7         | 1%      |
| Argentina   | 7         | 1%      |
| Vietnam     | 6         | 0.86%   |
| Ukraine     | 6         | 0.86%   |
| Switzerland | 5         | 0.72%   |
| Philippines | 5         | 0.72%   |
| Greece      | 5         | 0.72%   |
| Belgium     | 5         | 0.72%   |
| Bangladesh  | 5         | 0.72%   |
| Portugal    | 4         | 0.57%   |
| Malaysia    | 4         | 0.57%   |
| Hungary     | 4         | 0.57%   |
| Hong Kong   | 4         | 0.57%   |
| Denmark     | 4         | 0.57%   |
| Colombia    | 4         | 0.57%   |
| Bahrain     | 4         | 0.57%   |
| Singapore   | 3         | 0.43%   |
| Serbia      | 3         | 0.43%   |
| Peru        | 3         | 0.43%   |
| Norway      | 3         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Helsinki          | 11        | 1.51%   |
| Milan             | 9         | 1.23%   |
| Istanbul          | 8         | 1.1%    |
| Toms River        | 7         | 0.96%   |
| St Petersburg     | 7         | 0.96%   |
| Rome              | 7         | 0.96%   |
| Montreal          | 7         | 0.96%   |
| Amsterdam         | 7         | 0.96%   |
| Frankfurt am Main | 6         | 0.82%   |
| Warsaw            | 5         | 0.68%   |
| Sydney            | 5         | 0.68%   |
| Portland          | 5         | 0.68%   |
| Moscow            | 5         | 0.68%   |
| Florence          | 5         | 0.68%   |
| Berlin            | 5         | 0.68%   |
| Barberton         | 5         | 0.68%   |
| Vienna            | 4         | 0.55%   |
| Victoria          | 4         | 0.55%   |
| Turin             | 4         | 0.55%   |
| Paris             | 4         | 0.55%   |
| Mesa              | 4         | 0.55%   |
| London            | 4         | 0.55%   |
| Hamburg           | 4         | 0.55%   |
| Auckland          | 4         | 0.55%   |
| Wroclaw           | 3         | 0.41%   |
| Singapore         | 3         | 0.41%   |
| Poznan            | 3         | 0.41%   |
| Naples            | 3         | 0.41%   |
| Milano            | 3         | 0.41%   |
| Mannheim          | 3         | 0.41%   |
| Manama            | 3         | 0.41%   |
| Madrid            | 3         | 0.41%   |
| Lima              | 3         | 0.41%   |
| Jacksonville      | 3         | 0.41%   |
| Hyderabad         | 3         | 0.41%   |
| Ho Chi Minh City  | 3         | 0.41%   |
| Greeley           | 3         | 0.41%   |
| Dhaka             | 3         | 0.41%   |
| Delhi             | 3         | 0.41%   |
| Dallas            | 3         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 197       | 254    | 21.79%  |
| SanDisk                        | 81        | 93     | 8.96%   |
| Seagate                        | 64        | 71     | 7.08%   |
| SK hynix                       | 58        | 68     | 6.42%   |
| WDC                            | 57        | 65     | 6.31%   |
| Kingston                       | 47        | 56     | 5.2%    |
| Micron Technology              | 39        | 42     | 4.31%   |
| Unknown                        | 33        | 42     | 3.65%   |
| Toshiba                        | 33        | 39     | 3.65%   |
| Intel                          | 26        | 29     | 2.88%   |
| Crucial                        | 24        | 31     | 2.65%   |
| KIOXIA                         | 22        | 23     | 2.43%   |
| HGST                           | 21        | 26     | 2.32%   |
| Apple                          | 19        | 24     | 2.1%    |
| A-DATA Technology              | 12        | 14     | 1.33%   |
| Kingston Technology Company    | 10        | 12     | 1.11%   |
| Phison Electronics             | 9         | 9      | 1%      |
| Micron/Crucial Technology      | 9         | 10     | 1%      |
| Hitachi                        | 9         | 9      | 1%      |
| Phison                         | 7         | 7      | 0.77%   |
| LITEONIT                       | 7         | 8      | 0.77%   |
| China                          | 6         | 6      | 0.66%   |
| Union Memory (Shenzhen)        | 5         | 5      | 0.55%   |
| Transcend                      | 4         | 4      | 0.44%   |
| Mushkin                        | 4         | 4      | 0.44%   |
| SSSTC                          | 3         | 3      | 0.33%   |
| Solid State Storage Technology | 3         | 5      | 0.33%   |
| Shenzhen Longsys Electronics   | 3         | 4      | 0.33%   |
| Realtek                        | 3         | 5      | 0.33%   |
| PNY                            | 3         | 4      | 0.33%   |
| Patriot                        | 3         | 3      | 0.33%   |
| OCZ                            | 3         | 3      | 0.33%   |
| MAXIO Technology (Hangzhou)    | 3         | 3      | 0.33%   |
| LITEON                         | 3         | 5      | 0.33%   |
| Lenovo                         | 3         | 3      | 0.33%   |
| Gigabyte Technology            | 3         | 4      | 0.33%   |
| Fujitsu                        | 3         | 3      | 0.33%   |
| Corsair                        | 3         | 3      | 0.33%   |
| ADATA Technology               | 3         | 3      | 0.33%   |
| Yangtze Memory Technologies    | 2         | 2      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 27        | 2.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 22        | 2.36%   |
| Seagate ST1000LM035-1RK172 1TB                     | 18        | 1.93%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB  | 12        | 1.29%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                 | 11        | 1.18%   |
| HGST HTS721010A9E630 1TB                           | 9         | 0.97%   |
| Kingston SA400S37240G 240GB SSD                    | 8         | 0.86%   |
| Unknown MMC Card  64GB                             | 7         | 0.75%   |
| Seagate ST500LT012-1DG142 500GB                    | 7         | 0.75%   |
| Unknown MMC Card  16GB                             | 6         | 0.64%   |
| Toshiba MQ01ABD100 1TB                             | 6         | 0.64%   |
| SK hynix HFM001TD3JX013N 1024GB                    | 6         | 0.64%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB    | 6         | 0.64%   |
| Samsung SSD 870 QVO 1TB                            | 6         | 0.64%   |
| Samsung NVMe SSD Drive 512GB                       | 6         | 0.64%   |
| Kingston OM8PCP3512F-AI1 512GB                     | 6         | 0.64%   |
| Apple SSD SM0128G 121GB                            | 6         | 0.64%   |
| Unknown MMC Card  32GB                             | 5         | 0.54%   |
| Unknown MMC Card  128GB                            | 5         | 0.54%   |
| Seagate ST1000LM049-2GH172 1TB                     | 5         | 0.54%   |
| Samsung SSD 970 EVO 500GB                          | 5         | 0.54%   |
| Samsung SSD 870 EVO 250GB                          | 5         | 0.54%   |
| Samsung SSD 860 EVO 500GB                          | 5         | 0.54%   |
| Samsung SSD 860 EVO 250GB                          | 5         | 0.54%   |
| Samsung SSD 860 EVO 1TB                            | 5         | 0.54%   |
| Samsung SSD 850 EVO 500GB                          | 5         | 0.54%   |
| Samsung MZALQ512HBLU-00BL2 512GB                   | 5         | 0.54%   |
| Micron 2400_MTFDKBA512QFM 512GB                    | 5         | 0.54%   |
| KIOXIA KBG40ZNV512G 512GB                          | 5         | 0.54%   |
| Kingston SA400S37480G 480GB SSD                    | 5         | 0.54%   |
| HGST HTS545050A7E680 500GB                         | 5         | 0.54%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB             | 4         | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 4         | 0.43%   |
| Sandisk WD Black SN850 1TB                         | 4         | 0.43%   |
| Samsung SSD 980 1TB                                | 4         | 0.43%   |
| Samsung MZVLQ512HBLU-00B00 512GB                   | 4         | 0.43%   |
| Samsung MZVLQ512HALU-000H1 512GB                   | 4         | 0.43%   |
| Samsung MZVLQ512HALU-00000 512GB                   | 4         | 0.43%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                      | 4         | 0.43%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB            | 4         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 63     | 39.58%  |
| WDC                 | 32        | 35     | 22.22%  |
| HGST                | 21        | 26     | 14.58%  |
| Toshiba             | 15        | 16     | 10.42%  |
| Hitachi             | 9         | 9      | 6.25%   |
| Fujitsu             | 3         | 3      | 2.08%   |
| Unknown             | 2         | 2      | 1.39%   |
| Maxone              | 2         | 2      | 1.39%   |
| USB3.0              | 1         | 1      | 0.69%   |
| Samsung Electronics | 1         | 1      | 0.69%   |
| Generic-            | 1         | 1      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 80        | 106    | 27.87%  |
| Kingston            | 28        | 33     | 9.76%   |
| Crucial             | 21        | 27     | 7.32%   |
| SanDisk             | 19        | 20     | 6.62%   |
| WDC                 | 15        | 19     | 5.23%   |
| SK hynix            | 11        | 14     | 3.83%   |
| Apple               | 11        | 11     | 3.83%   |
| A-DATA Technology   | 9         | 10     | 3.14%   |
| Micron Technology   | 7         | 8      | 2.44%   |
| LITEONIT            | 7         | 8      | 2.44%   |
| Toshiba             | 6         | 6      | 2.09%   |
| China               | 6         | 6      | 2.09%   |
| Transcend           | 4         | 4      | 1.39%   |
| Seagate             | 4         | 4      | 1.39%   |
| Intel               | 4         | 4      | 1.39%   |
| Patriot             | 3         | 3      | 1.05%   |
| OCZ                 | 3         | 3      | 1.05%   |
| Mushkin             | 3         | 3      | 1.05%   |
| Gigabyte Technology | 3         | 4      | 1.05%   |
| Corsair             | 3         | 3      | 1.05%   |
| WDC WDS             | 2         | 2      | 0.7%    |
| Teclast             | 2         | 4      | 0.7%    |
| SPCC                | 2         | 2      | 0.7%    |
| PNY                 | 2         | 3      | 0.7%    |
| Netac               | 2         | 3      | 0.7%    |
| LITEON              | 2         | 3      | 0.7%    |
| KingSpec            | 2         | 2      | 0.7%    |
| KingFast            | 2         | 2      | 0.7%    |
| Hewlett-Packard     | 2         | 2      | 0.7%    |
| GOODRAM             | 2         | 2      | 0.7%    |
| Emtec               | 2         | 2      | 0.7%    |
| Zheino              | 1         | 1      | 0.35%   |
| WALTON              | 1         | 2      | 0.35%   |
| V-GeN               | 1         | 1      | 0.35%   |
| Unknown             | 1         | 2      | 0.35%   |
| Team                | 1         | 2      | 0.35%   |
| TAMMUZ              | 1         | 4      | 0.35%   |
| StoreJet            | 1         | 1      | 0.35%   |
| SSSTC               | 1         | 1      | 0.35%   |
| OCZ-VERTEX          | 1         | 1      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 396       | 517    | 47.88%  |
| SSD     | 252       | 347    | 30.47%  |
| HDD     | 140       | 159    | 16.93%  |
| MMC     | 32        | 40     | 3.87%   |
| Unknown | 7         | 7      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 396       | 510    | 49.44%  |
| SATA | 337       | 472    | 42.07%  |
| SAS  | 36        | 48     | 4.49%   |
| MMC  | 32        | 40     | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 249       | 348    | 64.18%  |
| 0.51-1.0   | 122       | 134    | 31.44%  |
| 1.01-2.0   | 16        | 23     | 4.12%   |
| 4.01-10.0  | 1         | 1      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 174       | 24.23%  |
| 251-500        | 145       | 20.19%  |
| 501-1000       | 102       | 14.21%  |
| 1001-2000      | 94        | 13.09%  |
| 1-20           | 50        | 6.96%   |
| Unknown        | 48        | 6.69%   |
| 51-100         | 34        | 4.74%   |
| More than 3000 | 32        | 4.46%   |
| 2001-3000      | 21        | 2.92%   |
| 21-50          | 18        | 2.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 199       | 26.75%  |
| 21-50          | 134       | 18.01%  |
| 101-250        | 122       | 16.4%   |
| 51-100         | 96        | 12.9%   |
| 251-500        | 69        | 9.27%   |
| Unknown        | 48        | 6.45%   |
| 501-1000       | 39        | 5.24%   |
| 1001-2000      | 26        | 3.49%   |
| More than 3000 | 4         | 0.54%   |
| 0              | 4         | 0.54%   |
| 2001-3000      | 3         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                                      | 5         | 8      | 9.26%   |
| HGST HTS721010A9E630 1TB                                        | 3         | 3      | 5.56%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 2         | 2      | 3.7%    |
| Hitachi HTS545050A7E380 500GB                                   | 2         | 2      | 3.7%    |
| WDC WD5000LPVT-22G33T0 500GB                                    | 1         | 1      | 1.85%   |
| WDC WD5000BPVT-60HXZT3 500GB                                    | 1         | 1      | 1.85%   |
| WDC WD10SPZX-24Z10T0 1TB                                        | 1         | 1      | 1.85%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 1         | 1      | 1.85%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB                            | 1         | 1      | 1.85%   |
| Transcend TS240GMTS420S 240GB SSD                               | 1         | 1      | 1.85%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD                        | 1         | 1      | 1.85%   |
| Toshiba MQ01ABD100 1TB                                          | 1         | 1      | 1.85%   |
| Toshiba MQ01ABD050 500GB                                        | 1         | 2      | 1.85%   |
| Toshiba MK5055GSXF 500GB                                        | 1         | 1      | 1.85%   |
| Toshiba MK2533GSG 250GB                                         | 1         | 1      | 1.85%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD                         | 1         | 1      | 1.85%   |
| SSSTC CV8-8E128-HP 128GB                                        | 1         | 1      | 1.85%   |
| SK hynix SC308 SATA 128GB SSD                                   | 1         | 1      | 1.85%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB                           | 1         | 1      | 1.85%   |
| SK hynix HFS512G39TND-N210A 512GB SSD                           | 1         | 1      | 1.85%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 1         | 1      | 1.85%   |
| SK hynix HFS128G32TND-N210A 128GB SSD                           | 1         | 1      | 1.85%   |
| SK hynix BC711 HFM001TD3JX013N 1024GB                           | 1         | 1      | 1.85%   |
| Seagate ST9750420AS 752GB                                       | 1         | 1      | 1.85%   |
| Seagate ST9320325AS 320GB                                       | 1         | 1      | 1.85%   |
| Seagate ST500LX012-SSHD-8GB                                     | 1         | 1      | 1.85%   |
| Seagate ST500LT012-1DG142 500GB                                 | 1         | 1      | 1.85%   |
| Seagate ST2000LX001-1RG174 2TB                                  | 1         | 1      | 1.85%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 1.85%   |
| SanDisk SSD PLUS 240GB                                          | 1         | 1      | 1.85%   |
| SanDisk SD8SNAT128G1002 128GB SSD                               | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 980 1TB                                 | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 970 EVO 500GB                           | 1         | 1      | 1.85%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 121GB | 1         | 1      | 1.85%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD                | 1         | 1      | 1.85%   |
| LITEONIT LCT-512M3S 2.5 7mm 512GB SSD                           | 1         | 1      | 1.85%   |
| Kingston SNS4151S332GD 32GB SSD                                 | 1         | 1      | 1.85%   |
| Intel SSDSCKKF256H6 SATA 256GB                                  | 1         | 1      | 1.85%   |
| Intel SSDSCKJF180A5L 180GB                                      | 1         | 1      | 1.85%   |
| HGST HTS545050A7E380 500GB                                      | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 9         | 12     | 16.67%  |
| Seagate             | 8         | 8      | 14.81%  |
| Toshiba             | 6         | 7      | 11.11%  |
| SK hynix            | 6         | 6      | 11.11%  |
| WDC                 | 5         | 5      | 9.26%   |
| Samsung Electronics | 4         | 4      | 7.41%   |
| SanDisk             | 2         | 2      | 3.7%    |
| Intel               | 2         | 2      | 3.7%    |
| Hitachi             | 2         | 2      | 3.7%    |
| Apple               | 2         | 2      | 3.7%    |
| Transcend           | 1         | 1      | 1.85%   |
| SSSTC               | 1         | 1      | 1.85%   |
| LITEONIT            | 1         | 1      | 1.85%   |
| Kingston            | 1         | 1      | 1.85%   |
| Fujitsu             | 1         | 1      | 1.85%   |
| Corsair             | 1         | 1      | 1.85%   |
| China               | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 9         | 12     | 32.14%  |
| Seagate | 8         | 8      | 28.57%  |
| WDC     | 4         | 4      | 14.29%  |
| Toshiba | 4         | 5      | 14.29%  |
| Hitachi | 2         | 2      | 7.14%   |
| Fujitsu | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 32     | 51.85%  |
| SSD  | 21        | 21     | 38.89%  |
| NVMe | 5         | 5      | 9.26%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Notebooks | Drives | Percent |
|------------------------|-----------|--------|---------|
| LITEON CA3-8D512 512GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| LITEON | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 473       | 678    | 63.24%  |
| Detected | 221       | 332    | 29.55%  |
| Malfunc  | 53        | 58     | 7.09%   |
| Failed   | 1         | 2      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 368       | 41.21%  |
| Samsung Electronics            | 131       | 14.67%  |
| AMD                            | 100       | 11.2%   |
| SanDisk                        | 71        | 7.95%   |
| SK hynix                       | 46        | 5.15%   |
| Micron Technology              | 32        | 3.58%   |
| Kingston Technology Company    | 29        | 3.25%   |
| KIOXIA                         | 25        | 2.8%    |
| Phison Electronics             | 17        | 1.9%    |
| Micron/Crucial Technology      | 12        | 1.34%   |
| Toshiba America Info Systems   | 9         | 1.01%   |
| Apple                          | 8         | 0.9%    |
| Solid State Storage Technology | 7         | 0.78%   |
| Union Memory (Shenzhen)        | 6         | 0.67%   |
| ADATA Technology               | 6         | 0.67%   |
| Shenzhen Longsys Electronics   | 3         | 0.34%   |
| Seagate Technology             | 3         | 0.34%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.34%   |
| Lenovo                         | 3         | 0.34%   |
| Yangtze Memory Technologies    | 2         | 0.22%   |
| Silicon Motion                 | 2         | 0.22%   |
| Realtek Semiconductor          | 2         | 0.22%   |
| Lite-On Technology             | 2         | 0.22%   |
| JMicron Technology             | 2         | 0.22%   |
| Nvidia                         | 1         | 0.11%   |
| Marvell Technology Group       | 1         | 0.11%   |
| INNOGRIT                       | 1         | 0.11%   |
| Biwin Storage Technology       | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 98        | 10.54%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 57        | 6.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 53        | 5.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 39        | 4.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 31        | 3.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 28        | 3.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 27        | 2.9%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 26        | 2.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 26        | 2.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 25        | 2.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 22        | 2.37%   |
| Intel Tiger Lake-LP SATA Controller                                            | 18        | 1.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 17        | 1.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 17        | 1.83%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 16        | 1.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 16        | 1.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 1.72%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 15        | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 1.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 13        | 1.4%    |
| Intel Comet Lake SATA AHCI Controller                                          | 12        | 1.29%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 11        | 1.18%   |
| Intel SSD 660P Series                                                          | 11        | 1.18%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 10        | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 1.08%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 7         | 0.75%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 7         | 0.75%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 7         | 0.75%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 0.75%   |
| Phison E12 NVMe Controller                                                     | 6         | 0.65%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 6         | 0.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 6         | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 0.65%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 0.54%   |
| SK hynix BC511 NVMe SSD                                                        | 5         | 0.54%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 5         | 0.54%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 5         | 0.54%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 5         | 0.54%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 5         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 413       | 46.99%  |
| NVMe | 395       | 44.94%  |
| RAID | 63        | 7.17%   |
| IDE  | 8         | 0.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 471       | 68.16%  |
| AMD    | 219       | 31.69%  |
| ARM    | 1         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 2.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 2.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 14        | 2.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 14        | 2.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 12        | 1.74%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 11        | 1.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 11        | 1.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 1.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 1.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 10        | 1.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 1.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 1.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 1.3%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.16%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 1.16%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 1.16%   |
| Intel 12th Gen Core i7-12700H                 | 8         | 1.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.01%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 1.01%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 7         | 1.01%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 1.01%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 7         | 1.01%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 7         | 1.01%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 7         | 1.01%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 0.87%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 6         | 0.87%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 6         | 0.87%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 6         | 0.87%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.72%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.72%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 0.72%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 0.72%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 5         | 0.72%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 4         | 0.58%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.58%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 4         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 158       | 22.87%  |
| Intel Core i7           | 144       | 20.84%  |
| Other                   | 91        | 13.17%  |
| AMD Ryzen 7             | 74        | 10.71%  |
| AMD Ryzen 5             | 65        | 9.41%   |
| Intel Core i3           | 32        | 4.63%   |
| Intel Celeron           | 25        | 3.62%   |
| AMD Ryzen 9             | 19        | 2.75%   |
| AMD Ryzen 7 PRO         | 17        | 2.46%   |
| Intel Core 2 Duo        | 15        | 2.17%   |
| AMD Ryzen 3             | 10        | 1.45%   |
| AMD A4                  | 8         | 1.16%   |
| Intel Pentium           | 5         | 0.72%   |
| AMD Ryzen 5 PRO         | 4         | 0.58%   |
| AMD A8                  | 3         | 0.43%   |
| AMD A10                 | 3         | 0.43%   |
| Intel Xeon              | 2         | 0.29%   |
| Intel Core m3           | 2         | 0.29%   |
| Intel Atom              | 2         | 0.29%   |
| AMD E1                  | 2         | 0.29%   |
| AMD Athlon              | 2         | 0.29%   |
| Intel Pentium Dual-Core | 1         | 0.14%   |
| Intel Core m5           | 1         | 0.14%   |
| Intel Core 2 Extreme    | 1         | 0.14%   |
| Intel Core 2            | 1         | 0.14%   |
| AMD E2                  | 1         | 0.14%   |
| AMD E                   | 1         | 0.14%   |
| AMD Athlon II           | 1         | 0.14%   |
| AMD A6                  | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 236       | 34.15%  |
| 4      | 228       | 33%     |
| 8      | 116       | 16.79%  |
| 6      | 79        | 11.43%  |
| 14     | 16        | 2.32%   |
| 12     | 8         | 1.16%   |
| 10     | 6         | 0.87%   |
| 24     | 1         | 0.14%   |
| 1      | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 690       | 99.86%  |
| 2      | 1         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 597       | 86.27%  |
| 1      | 95        | 13.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 689       | 99.71%  |
| 64-bit         | 1         | 0.14%   |
| Unknown        | 1         | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 300       | 42.49%  |
| 0x0a50000c | 33        | 4.67%   |
| 0x806ec    | 18        | 2.55%   |
| 0x406e3    | 18        | 2.55%   |
| 0x08108109 | 18        | 2.55%   |
| 0x306a9    | 17        | 2.41%   |
| 0x806c1    | 16        | 2.27%   |
| 0x806ea    | 15        | 2.12%   |
| 0x40651    | 15        | 2.12%   |
| 0x08600106 | 15        | 2.12%   |
| 0x906ea    | 13        | 1.84%   |
| 0x806e9    | 13        | 1.84%   |
| 0x08608103 | 13        | 1.84%   |
| 0x08600104 | 13        | 1.84%   |
| 0x306c3    | 12        | 1.7%    |
| 0x0a404102 | 12        | 1.7%    |
| 0x08108102 | 11        | 1.56%   |
| 0x0a50000d | 10        | 1.42%   |
| 0x906e9    | 9         | 1.27%   |
| 0x906a3    | 9         | 1.27%   |
| 0x506e3    | 9         | 1.27%   |
| 0x306d4    | 9         | 1.27%   |
| 0x206a7    | 9         | 1.27%   |
| 0x1067a    | 8         | 1.13%   |
| 0xa0652    | 7         | 0.99%   |
| 0x706e5    | 7         | 0.99%   |
| 0x806d1    | 6         | 0.85%   |
| 0x406c4    | 6         | 0.85%   |
| 0x706a1    | 5         | 0.71%   |
| 0x20655    | 5         | 0.71%   |
| 0x0a404101 | 5         | 0.71%   |
| 0x06006705 | 5         | 0.71%   |
| 0x06006704 | 3         | 0.42%   |
| 0x906ed    | 2         | 0.28%   |
| 0x906c0    | 2         | 0.28%   |
| 0x806eb    | 2         | 0.28%   |
| 0x406c3    | 2         | 0.28%   |
| 0x10676    | 2         | 0.28%   |
| 0x0a704103 | 2         | 0.28%   |
| 0x0a50000b | 2         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 139       | 20.12%  |
| Unknown          | 62        | 8.97%   |
| Zen 3            | 57        | 8.25%   |
| Haswell          | 48        | 6.95%   |
| Zen 2            | 44        | 6.37%   |
| Skylake          | 44        | 6.37%   |
| TigerLake        | 40        | 5.79%   |
| Zen+             | 39        | 5.64%   |
| IvyBridge        | 31        | 4.49%   |
| Alderlake Hybrid | 24        | 3.47%   |
| Broadwell        | 23        | 3.33%   |
| Icelake          | 20        | 2.89%   |
| SandyBridge      | 19        | 2.75%   |
| CometLake        | 16        | 2.32%   |
| Penryn           | 15        | 2.17%   |
| Excavator        | 15        | 2.17%   |
| Silvermont       | 12        | 1.74%   |
| Westmere         | 11        | 1.59%   |
| Goldmont plus    | 8         | 1.16%   |
| Jaguar           | 6         | 0.87%   |
| Tremont          | 3         | 0.43%   |
| Piledriver       | 3         | 0.43%   |
| Goldmont         | 3         | 0.43%   |
| Core             | 3         | 0.43%   |
| Zen              | 2         | 0.29%   |
| Puma             | 2         | 0.29%   |
| K10              | 1         | 0.14%   |
| Bobcat           | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 442       | 48.46%  |
| AMD    | 242       | 26.54%  |
| Nvidia | 228       | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 43        | 4.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 40        | 4.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 39        | 4.15%   |
| Intel UHD Graphics 620                                                                   | 34        | 3.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 34        | 3.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 28        | 2.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 2.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 2.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 26        | 2.77%   |
| AMD Rembrandt [Radeon 680M]                                                              | 25        | 2.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 2.13%   |
| AMD Lucienne                                                                             | 20        | 2.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 19        | 2.02%   |
| Intel HD Graphics 620                                                                    | 19        | 2.02%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 19        | 2.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 2.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 18        | 1.91%   |
| Intel HD Graphics 5500                                                                   | 16        | 1.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 1.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 1.49%   |
| AMD Barcelo                                                                              | 13        | 1.38%   |
| Intel HD Graphics 630                                                                    | 12        | 1.28%   |
| Intel HD Graphics 530                                                                    | 12        | 1.28%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 1.28%   |
| Nvidia GP108M [GeForce MX150]                                                            | 11        | 1.17%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 10        | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.06%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 0.74%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 7         | 0.74%   |
| Intel HD Graphics 6000                                                                   | 7         | 0.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.74%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 6         | 0.64%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 6         | 0.64%   |
| Nvidia GM108M [GeForce 940M]                                                             | 6         | 0.64%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 259       | 37.43%  |
| Intel + Nvidia | 158       | 22.83%  |
| 1 x AMD        | 156       | 22.54%  |
| AMD + Nvidia   | 44        | 6.36%   |
| 1 x Nvidia     | 25        | 3.61%   |
| 2 x AMD        | 24        | 3.47%   |
| Intel + AMD    | 19        | 2.75%   |
| 2 x Intel      | 5         | 0.72%   |
| Other          | 2         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 530       | 76.37%  |
| Proprietary | 163       | 23.49%  |
| Unknown     | 1         | 0.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 463       | 66.05%  |
| 0.01-0.5   | 97        | 13.84%  |
| 1.01-2.0   | 60        | 8.56%   |
| 3.01-4.0   | 30        | 4.28%   |
| 0.51-1.0   | 21        | 3%      |
| 7.01-8.0   | 11        | 1.57%   |
| 5.01-6.0   | 11        | 1.57%   |
| 2.01-3.0   | 6         | 0.86%   |
| 8.01-16.0  | 2         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 157       | 18.98%  |
| Chimei Innolux          | 125       | 15.11%  |
| BOE                     | 123       | 14.87%  |
| LG Display              | 95        | 11.49%  |
| Samsung Electronics     | 66        | 7.98%   |
| PANDA                   | 26        | 3.14%   |
| Apple                   | 22        | 2.66%   |
| Sharp                   | 21        | 2.54%   |
| Dell                    | 21        | 2.54%   |
| Goldstar                | 19        | 2.3%    |
| Lenovo                  | 17        | 2.06%   |
| Acer                    | 12        | 1.45%   |
| CSO                     | 11        | 1.33%   |
| AOC                     | 11        | 1.33%   |
| Philips                 | 10        | 1.21%   |
| TMX                     | 9         | 1.09%   |
| InfoVision              | 9         | 1.09%   |
| BenQ                    | 7         | 0.85%   |
| Ancor Communications    | 7         | 0.85%   |
| Hewlett-Packard         | 6         | 0.73%   |
| Chi Mei Optoelectronics | 6         | 0.73%   |
| Iiyama                  | 5         | 0.6%    |
| ViewSonic               | 4         | 0.48%   |
| Sony                    | 3         | 0.36%   |
| Pixio                   | 3         | 0.36%   |
| LG Philips              | 3         | 0.36%   |
| JDI                     | 3         | 0.36%   |
| Gigabyte Technology     | 3         | 0.36%   |
| Toshiba                 | 2         | 0.24%   |
| InnoLux Display         | 2         | 0.24%   |
| HKC                     | 2         | 0.24%   |
| ASUSTek Computer        | 2         | 0.24%   |
| Vizio                   | 1         | 0.12%   |
| Unknown (XXX)           | 1         | 0.12%   |
| Unknown                 | 1         | 0.12%   |
| Sun                     | 1         | 0.12%   |
| RTK                     | 1         | 0.12%   |
| Panasonic               | 1         | 0.12%   |
| MSI                     | 1         | 0.12%   |
| HUAWEI                  | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 8         | 0.96%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.96%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 7         | 0.84%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.72%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 5         | 0.6%    |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 5         | 0.6%    |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 4         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 0.48%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.48%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 0.48%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.48%   |
| TMX TL140ADXP01 TMX1481 2560x1600 301x188mm 14.0-inch                 | 3         | 0.36%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.36%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 3         | 0.36%   |
| Pixio U29I WAM2900 2560x1080 690x260mm 29.0-inch                      | 3         | 0.36%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch          | 3         | 0.36%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch          | 3         | 0.36%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 3         | 0.36%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 3         | 0.36%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.36%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3         | 0.36%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch      | 3         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 3         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 3         | 0.36%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                 | 3         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 403       | 52.41%  |
| 1366x768 (WXGA)    | 146       | 18.99%  |
| 2560x1440 (QHD)    | 35        | 4.55%   |
| 2560x1600          | 33        | 4.29%   |
| 3840x2160 (4K)     | 26        | 3.38%   |
| 1440x900 (WXGA+)   | 19        | 2.47%   |
| 1920x1200 (WUXGA)  | 17        | 2.21%   |
| 2880x1800          | 15        | 1.95%   |
| 1280x800 (WXGA)    | 9         | 1.17%   |
| 2560x1080          | 7         | 0.91%   |
| 2160x1440          | 7         | 0.91%   |
| 1600x900 (HD+)     | 7         | 0.91%   |
| 3840x2400          | 5         | 0.65%   |
| 3200x2000          | 5         | 0.65%   |
| 1680x1050 (WSXGA+) | 5         | 0.65%   |
| 3440x1440          | 4         | 0.52%   |
| 3456x2160          | 3         | 0.39%   |
| 3200x1800 (QHD+)   | 3         | 0.39%   |
| 3072x1920          | 3         | 0.39%   |
| 3000x2000          | 3         | 0.39%   |
| 1280x1024 (SXGA)   | 3         | 0.39%   |
| 1920x1280          | 2         | 0.26%   |
| 1360x768           | 2         | 0.26%   |
| Unknown            | 2         | 0.26%   |
| 3840x1100          | 1         | 0.13%   |
| 3840x1080          | 1         | 0.13%   |
| 2520x1680          | 1         | 0.13%   |
| 2256x1504          | 1         | 0.13%   |
| 2240x1400          | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 312       | 37.5%   |
| 13      | 125       | 15.02%  |
| 14      | 118       | 14.18%  |
| 17      | 45        | 5.41%   |
| 27      | 36        | 4.33%   |
| 16      | 34        | 4.09%   |
| 24      | 29        | 3.49%   |
| 23      | 22        | 2.64%   |
| 12      | 17        | 2.04%   |
| 21      | 16        | 1.92%   |
| 11      | 12        | 1.44%   |
| 31      | 11        | 1.32%   |
| 18      | 7         | 0.84%   |
| 34      | 5         | 0.6%    |
| 54      | 3         | 0.36%   |
| 40      | 3         | 0.36%   |
| 29      | 3         | 0.36%   |
| 19      | 3         | 0.36%   |
| Unknown | 3         | 0.36%   |
| 58      | 2         | 0.24%   |
| 35      | 2         | 0.24%   |
| 28      | 2         | 0.24%   |
| 25      | 2         | 0.24%   |
| 22      | 2         | 0.24%   |
| 20      | 2         | 0.24%   |
| 10      | 2         | 0.24%   |
| 86      | 1         | 0.12%   |
| 84      | 1         | 0.12%   |
| 74      | 1         | 0.12%   |
| 72      | 1         | 0.12%   |
| 65      | 1         | 0.12%   |
| 57      | 1         | 0.12%   |
| 52      | 1         | 0.12%   |
| 49      | 1         | 0.12%   |
| 46      | 1         | 0.12%   |
| 42      | 1         | 0.12%   |
| 37      | 1         | 0.12%   |
| 32      | 1         | 0.12%   |
| 26      | 1         | 0.12%   |
| 8       | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 515       | 62.5%   |
| 201-300     | 92        | 11.17%  |
| 501-600     | 84        | 10.19%  |
| 351-400     | 58        | 7.04%   |
| 401-500     | 28        | 3.4%    |
| 601-700     | 18        | 2.18%   |
| 1001-1500   | 9         | 1.09%   |
| 801-900     | 6         | 0.73%   |
| 701-800     | 6         | 0.73%   |
| 1501-2000   | 3         | 0.36%   |
| Unknown     | 3         | 0.36%   |
| 101-200     | 1         | 0.12%   |
| 901-1000    | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 573       | 79.81%  |
| 16/10   | 109       | 15.18%  |
| 3/2     | 16        | 2.23%   |
| 21/9    | 8         | 1.11%   |
| 2.65    | 3         | 0.42%   |
| 6/5     | 2         | 0.28%   |
| Unknown | 2         | 0.28%   |
| 5/4     | 1         | 0.14%   |
| 4/3     | 1         | 0.14%   |
| 3.40    | 1         | 0.14%   |
| 0.62    | 1         | 0.14%   |
| 0.56    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 315       | 38.04%  |
| 81-90          | 198       | 23.91%  |
| 201-250        | 56        | 6.76%   |
| 71-80          | 43        | 5.19%   |
| 121-130        | 40        | 4.83%   |
| 301-350        | 37        | 4.47%   |
| 111-120        | 30        | 3.62%   |
| 351-500        | 20        | 2.42%   |
| 61-70          | 15        | 1.81%   |
| 51-60          | 13        | 1.57%   |
| 251-300        | 13        | 1.57%   |
| More than 1000 | 11        | 1.33%   |
| 151-200        | 9         | 1.09%   |
| 141-150        | 7         | 0.85%   |
| 131-140        | 6         | 0.72%   |
| 501-1000       | 6         | 0.72%   |
| 91-100         | 3         | 0.36%   |
| Unknown        | 3         | 0.36%   |
| 41-50          | 2         | 0.24%   |
| 1-40           | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 394       | 48.4%   |
| 101-120       | 161       | 19.78%  |
| 51-100        | 105       | 12.9%   |
| 161-240       | 97        | 11.92%  |
| More than 240 | 43        | 5.28%   |
| 1-50          | 11        | 1.35%   |
| Unknown       | 3         | 0.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 558       | 79.04%  |
| 2     | 138       | 19.55%  |
| 3     | 8         | 1.13%   |
| 0     | 2         | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 397       | 36.93%  |
| Realtek Semiconductor             | 390       | 36.28%  |
| Qualcomm Atheros                  | 104       | 9.67%   |
| MediaTek                          | 55        | 5.12%   |
| Broadcom                          | 34        | 3.16%   |
| Broadcom Limited                  | 12        | 1.12%   |
| ASIX Electronics                  | 12        | 1.12%   |
| TP-Link                           | 8         | 0.74%   |
| D-Link                            | 7         | 0.65%   |
| Sierra Wireless                   | 5         | 0.47%   |
| Qualcomm                          | 5         | 0.47%   |
| Lenovo                            | 5         | 0.47%   |
| Ralink                            | 4         | 0.37%   |
| Hewlett-Packard                   | 4         | 0.37%   |
| DisplayLink                       | 4         | 0.37%   |
| Apple                             | 4         | 0.37%   |
| Cypress Semiconductor             | 3         | 0.28%   |
| Samsung Electronics               | 2         | 0.19%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.19%   |
| ICS Advent                        | 2         | 0.19%   |
| Huawei Technologies               | 2         | 0.19%   |
| Ericsson Business Mobile Networks | 2         | 0.19%   |
| Quectel Wireless Solutions        | 1         | 0.09%   |
| Qualcomm Technologies             | 1         | 0.09%   |
| OPPO Electronics                  | 1         | 0.09%   |
| NetGear                           | 1         | 0.09%   |
| Microsoft                         | 1         | 0.09%   |
| Marvell Technology Group          | 1         | 0.09%   |
| Linksys                           | 1         | 0.09%   |
| Google                            | 1         | 0.09%   |
| Fibocom                           | 1         | 0.09%   |
| Dell                              | 1         | 0.09%   |
| D-Link System                     | 1         | 0.09%   |
| Belkin Components                 | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 266       | 20.86%  |
| Intel Wi-Fi 6 AX200                                                  | 57        | 4.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 34        | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 34        | 2.67%   |
| Intel Wireless 8265 / 8275                                           | 34        | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 31        | 2.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 28        | 2.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 28        | 2.2%    |
| Intel Wi-Fi 6 AX201                                                  | 28        | 2.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 26        | 2.04%   |
| Intel Wireless 7265                                                  | 24        | 1.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 24        | 1.88%   |
| Intel Wireless 7260                                                  | 22        | 1.73%   |
| Intel Wireless 8260                                                  | 19        | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 19        | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 18        | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 15        | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 15        | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 15        | 1.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 14        | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 13        | 1.02%   |
| Intel Wireless 3165                                                  | 12        | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 12        | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 11        | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 11        | 0.86%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 10        | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 10        | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 10        | 0.78%   |
| Intel Ethernet Connection I218-LM                                    | 10        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                        | 10        | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                    | 9         | 0.71%   |
| Intel Ethernet Connection I217-LM                                    | 9         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                | 9         | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 9         | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 9         | 0.71%   |
| Intel Ethernet Connection (4) I219-V                                 | 8         | 0.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 8         | 0.63%   |
| Broadcom BCM43142 802.11b/g/n                                        | 8         | 0.63%   |
| Realtek 802.11ac NIC                                                 | 7         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 7         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 389       | 53.8%   |
| Realtek Semiconductor             | 118       | 16.32%  |
| Qualcomm Atheros                  | 87        | 12.03%  |
| MediaTek                          | 54        | 7.47%   |
| Broadcom                          | 26        | 3.6%    |
| Broadcom Limited                  | 12        | 1.66%   |
| TP-Link                           | 7         | 0.97%   |
| D-Link                            | 7         | 0.97%   |
| Sierra Wireless                   | 5         | 0.69%   |
| Qualcomm                          | 5         | 0.69%   |
| Ralink                            | 4         | 0.55%   |
| Quectel Wireless Solutions        | 1         | 0.14%   |
| Qualcomm Technologies             | 1         | 0.14%   |
| Microsoft                         | 1         | 0.14%   |
| Linksys                           | 1         | 0.14%   |
| Fibocom                           | 1         | 0.14%   |
| Ericsson Business Mobile Networks | 1         | 0.14%   |
| Dell                              | 1         | 0.14%   |
| D-Link System                     | 1         | 0.14%   |
| Belkin Components                 | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 57        | 7.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 34        | 4.66%   |
| Intel Wireless 8265 / 8275                                           | 34        | 4.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 31        | 4.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 28        | 3.84%   |
| Intel Wi-Fi 6 AX201                                                  | 28        | 3.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 26        | 3.57%   |
| Intel Wireless 7265                                                  | 24        | 3.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 23        | 3.16%   |
| Intel Wireless 7260                                                  | 22        | 3.02%   |
| Intel Wireless 8260                                                  | 19        | 2.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 19        | 2.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 18        | 2.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 15        | 2.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 15        | 2.06%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 14        | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 13        | 1.78%   |
| Intel Wireless 3165                                                  | 12        | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 12        | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 11        | 1.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 11        | 1.51%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 10        | 1.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 10        | 1.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 10        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 9         | 1.23%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 9         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 8         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                        | 8         | 1.1%    |
| Realtek 802.11ac NIC                                                 | 7         | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 7         | 0.96%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 7         | 0.96%   |
| Intel Wireless-AC 9260                                               | 7         | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 7         | 0.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 6         | 0.82%   |
| Intel Wireless 3160                                                  | 6         | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 6         | 0.82%   |
| Intel Centrino Advanced-N 6200                                       | 6         | 0.82%   |
| D-Link 802.11ac NIC                                                  | 6         | 0.82%   |
| TP-Link 802.11ac NIC                                                 | 5         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 340       | 64.27%  |
| Intel                         | 111       | 20.98%  |
| Qualcomm Atheros              | 28        | 5.29%   |
| ASIX Electronics              | 12        | 2.27%   |
| Broadcom                      | 11        | 2.08%   |
| Lenovo                        | 4         | 0.76%   |
| DisplayLink                   | 4         | 0.76%   |
| Apple                         | 4         | 0.76%   |
| Cypress Semiconductor         | 3         | 0.57%   |
| Samsung Electronics           | 2         | 0.38%   |
| ICS Advent                    | 2         | 0.38%   |
| TP-Link                       | 1         | 0.19%   |
| OPPO Electronics              | 1         | 0.19%   |
| OnePlus Technology (Shenzhen) | 1         | 0.19%   |
| NetGear                       | 1         | 0.19%   |
| MediaTek                      | 1         | 0.19%   |
| Marvell Technology Group      | 1         | 0.19%   |
| Hewlett-Packard               | 1         | 0.19%   |
| Google                        | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 266       | 49.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 6.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 28        | 5.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 2.79%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 1.86%   |
| ASIX AX88179 Gigabit Ethernet                                     | 10        | 1.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.67%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 1.67%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 1.49%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 1.12%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.12%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.74%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.74%   |
| Apple iBridge                                                     | 4         | 0.74%   |
| Realtek PCIe GbE Family Controller                                | 3         | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.56%   |
| Intel Ethernet Connection (16) I219-V                             | 3         | 0.56%   |
| Cypress K38231_03                                                 | 3         | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.56%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.37%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 0.37%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.37%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.37%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.37%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.37%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.37%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 0.37%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.37%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.37%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 686       | 57.31%  |
| Ethernet | 503       | 42.02%  |
| Modem    | 7         | 0.58%   |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 618       | 84.2%   |
| Ethernet | 116       | 15.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 452       | 65.32%  |
| 1     | 230       | 33.24%  |
| 3     | 6         | 0.87%   |
| 0     | 4         | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 542       | 77.32%  |
| Yes  | 159       | 22.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 343       | 52.69%  |
| Realtek Semiconductor           | 80        | 12.29%  |
| Qualcomm Atheros Communications | 42        | 6.45%   |
| IMC Networks                    | 40        | 6.14%   |
| Foxconn / Hon Hai               | 34        | 5.22%   |
| Lite-On Technology              | 28        | 4.3%    |
| Broadcom                        | 21        | 3.23%   |
| Apple                           | 14        | 2.15%   |
| MediaTek                        | 8         | 1.23%   |
| Realtek                         | 7         | 1.08%   |
| Cambridge Silicon Radio         | 7         | 1.08%   |
| USI                             | 5         | 0.77%   |
| Toshiba                         | 5         | 0.77%   |
| Ralink                          | 4         | 0.61%   |
| Dell                            | 4         | 0.61%   |
| Hewlett-Packard                 | 3         | 0.46%   |
| Opticis                         | 2         | 0.31%   |
| TP-Link                         | 1         | 0.15%   |
| Foxconn International           | 1         | 0.15%   |
| ASUSTek Computer                | 1         | 0.15%   |
| Alps Electric                   | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 124       | 19.02%  |
| Intel AX201 Bluetooth                               | 65        | 9.97%   |
| Intel AX200 Bluetooth                               | 57        | 8.74%   |
| Realtek Bluetooth Radio                             | 52        | 7.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 42        | 6.44%   |
| Qualcomm Atheros  Bluetooth Device                  | 25        | 3.83%   |
| Intel Bluetooth Device                              | 25        | 3.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 22        | 3.37%   |
| IMC Networks Wireless_Device                        | 17        | 2.61%   |
| Realtek  Bluetooth 4.2 Adapter                      | 16        | 2.45%   |
| Intel AX210 Bluetooth                               | 15        | 2.3%    |
| IMC Networks Bluetooth Radio                        | 14        | 2.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 1.99%   |
| Apple Bluetooth USB Host Controller                 | 10        | 1.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 1.07%   |
| Realtek Bluetooth Radio                             | 7         | 1.07%   |
| MediaTek Wireless_Device                            | 7         | 1.07%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 1.07%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.92%   |
| USI Bluetooth Device                                | 5         | 0.77%   |
| Realtek RTL8821A Bluetooth                          | 5         | 0.77%   |
| Lite-On Bluetooth Device                            | 5         | 0.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.77%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 0.77%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.61%   |
| Lite-On Wireless_Device                             | 4         | 0.61%   |
| IMC Networks Bluetooth Device                       | 4         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.61%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.46%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.46%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.46%   |
| Toshiba BCM43142A0                                  | 2         | 0.31%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.31%   |
| Opticis Bluetooth Radio                             | 2         | 0.31%   |
| Lite-On Bluetooth Radio                             | 2         | 0.31%   |
| IMC Networks Bluetooth                              | 2         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 466       | 50.87%  |
| AMD                                             | 228       | 24.89%  |
| Nvidia                                          | 127       | 13.86%  |
| C-Media Electronics                             | 11        | 1.2%    |
| Texas Instruments                               | 8         | 0.87%   |
| Lenovo                                          | 6         | 0.66%   |
| KORG                                            | 6         | 0.66%   |
| Realtek Semiconductor                           | 5         | 0.55%   |
| Apple                                           | 5         | 0.55%   |
| AKAI                                            | 5         | 0.55%   |
| Logitech                                        | 4         | 0.44%   |
| Corsair                                         | 4         | 0.44%   |
| Sony                                            | 3         | 0.33%   |
| Kingston Technology                             | 3         | 0.33%   |
| Focusrite-Novation                              | 3         | 0.33%   |
| Creative Technology                             | 3         | 0.33%   |
| Samson Technologies                             | 2         | 0.22%   |
| JMTek                                           | 2         | 0.22%   |
| GYROCOM C&C                                     | 2         | 0.22%   |
| Generalplus Technology                          | 2         | 0.22%   |
| AKAI Professional M.I.                          | 2         | 0.22%   |
| YZ Technology                                   | 1         | 0.11%   |
| XMOS                                            | 1         | 0.11%   |
| Tenx Technology                                 | 1         | 0.11%   |
| Tdlasunnic                                      | 1         | 0.11%   |
| ROCCAT                                          | 1         | 0.11%   |
| NAD Electronics                                 | 1         | 0.11%   |
| Micro Star International                        | 1         | 0.11%   |
| M-Audio                                         | 1         | 0.11%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.11%   |
| LG Electronics                                  | 1         | 0.11%   |
| FiiO Electronics Technology                     | 1         | 0.11%   |
| Conexant Systems                                | 1         | 0.11%   |
| Beyerdynamic                                    | 1         | 0.11%   |
| Audient                                         | 1         | 0.11%   |
| ASUSTek Computer                                | 1         | 0.11%   |
| Asahi Kasei Microsystems                        | 1         | 0.11%   |
| Arturia                                         | 1         | 0.11%   |
| Applied Microsystems                            | 1         | 0.11%   |
| Anlya.cn                                        | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 183       | 15.38%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 104       | 8.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 88        | 7.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 40        | 3.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 37        | 3.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 33        | 2.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 28        | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 28        | 2.35%   |
| Intel 8 Series HD Audio Controller                                                                | 28        | 2.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 27        | 2.27%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 26        | 2.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23        | 1.93%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 1.93%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 1.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 20        | 1.68%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 18        | 1.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 16        | 1.34%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 1.26%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 1.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 1.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 14        | 1.18%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 1.01%   |
| AMD High Definition Audio Controller                                                              | 12        | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 11        | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 11        | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 0.92%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 0.92%   |
| AMD FCH Azalia Controller                                                                         | 11        | 0.92%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 10        | 0.84%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.76%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 9         | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 0.76%   |
| Nvidia Audio device                                                                               | 8         | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 0.67%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 8         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.59%   |
| AMD Navi 10 HDMI Audio                                                                            | 7         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 210       | 33.23%  |
| SK hynix            | 147       | 23.26%  |
| Micron Technology   | 99        | 15.66%  |
| Kingston            | 38        | 6.01%   |
| Crucial             | 33        | 5.22%   |
| Unknown             | 20        | 3.16%   |
| Ramaxel Technology  | 13        | 2.06%   |
| A-DATA Technology   | 9         | 1.42%   |
| Corsair             | 8         | 1.27%   |
| Elpida              | 7         | 1.11%   |
| G.Skill             | 6         | 0.95%   |
| Unknown (ABCD)      | 5         | 0.79%   |
| Team                | 4         | 0.63%   |
| Unknown             | 4         | 0.63%   |
| Patriot             | 3         | 0.47%   |
| Nanya Technology    | 3         | 0.47%   |
| Kllisre             | 3         | 0.47%   |
| Teikon              | 2         | 0.32%   |
| Shenzhen Mic        | 2         | 0.32%   |
| Hikvision           | 2         | 0.32%   |
| V-GeN               | 1         | 0.16%   |
| Transcend           | 1         | 0.16%   |
| Toshiba             | 1         | 0.16%   |
| Smart Brazil        | 1         | 0.16%   |
| Sesame              | 1         | 0.16%   |
| Qimonda             | 1         | 0.16%   |
| Neo Forza           | 1         | 0.16%   |
| Magnum Tech         | 1         | 0.16%   |
| Juhor               | 1         | 0.16%   |
| GOODRAM             | 1         | 0.16%   |
| ff                  | 1         | 0.16%   |
| CSX                 | 1         | 0.16%   |
| Apacer              | 1         | 0.16%   |
| 4ea5                | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 2.52%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.93%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 1.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 1.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 1.34%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.34%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.19%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 1.04%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 1.04%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 1.04%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 1.04%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 7         | 1.04%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 0.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.89%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 0.89%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.89%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.89%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.74%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.74%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.74%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.74%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.74%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.59%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.59%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.59%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.59%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.59%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 4         | 0.59%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.59%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s         | 4         | 0.59%   |
| Unknown                                                          | 4         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.45%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.45%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.45%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 310       | 58.38%  |
| DDR3    | 117       | 22.03%  |
| LPDDR4  | 31        | 5.84%   |
| DDR5    | 22        | 4.14%   |
| LPDDR3  | 19        | 3.58%   |
| LPDDR5  | 17        | 3.2%    |
| DDR2    | 10        | 1.88%   |
| SDRAM   | 4         | 0.75%   |
| Unknown | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 453       | 84.04%  |
| Row Of Chips | 73        | 13.54%  |
| Chip         | 7         | 1.3%    |
| Unknown      | 4         | 0.74%   |
| DIMM         | 2         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 282       | 48.45%  |
| 4096  | 141       | 24.23%  |
| 16384 | 99        | 17.01%  |
| 2048  | 32        | 5.5%    |
| 32768 | 24        | 4.12%   |
| 1024  | 4         | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 169       | 29.81%  |
| 2667    | 116       | 20.46%  |
| 1600    | 98        | 17.28%  |
| 2400    | 34        | 6%      |
| 2133    | 25        | 4.41%   |
| 4800    | 21        | 3.7%    |
| 3266    | 17        | 3%      |
| 6400    | 15        | 2.65%   |
| 1867    | 10        | 1.76%   |
| 1334    | 10        | 1.76%   |
| 4267    | 8         | 1.41%   |
| 667     | 5         | 0.88%   |
| 4266    | 4         | 0.71%   |
| 1333    | 4         | 0.71%   |
| 1067    | 4         | 0.71%   |
| Unknown | 4         | 0.71%   |
| 5600    | 3         | 0.53%   |
| 2933    | 3         | 0.53%   |
| 800     | 3         | 0.53%   |
| 3733    | 2         | 0.35%   |
| 2048    | 2         | 0.35%   |
| 1066    | 2         | 0.35%   |
| 8400    | 1         | 0.18%   |
| 7500    | 1         | 0.18%   |
| 7400    | 1         | 0.18%   |
| 4199    | 1         | 0.18%   |
| 3000    | 1         | 0.18%   |
| 1776    | 1         | 0.18%   |
| 1639    | 1         | 0.18%   |
| 1200    | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Xerox               | 1         | 25%     |
| Samsung Electronics | 1         | 25%     |
| Prolific Technology | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Xerox B210                    | 1         | 25%     |
| Samsung M2020 Series          | 1         | 25%     |
| Prolific PL2305 Parallel Port | 1         | 25%     |
| HP DeskJet 2130 series        | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 137       | 21.92%  |
| IMC Networks                           | 100       | 16%     |
| Bison Electronics                      | 56        | 8.96%   |
| Microdia                               | 42        | 6.72%   |
| Quanta                                 | 35        | 5.6%    |
| Realtek Semiconductor                  | 34        | 5.44%   |
| Sunplus Innovation Technology          | 31        | 4.96%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 4.96%   |
| Lite-On Technology                     | 23        | 3.68%   |
| Luxvisions Innotech Limited            | 20        | 3.2%    |
| Syntek                                 | 19        | 3.04%   |
| Apple                                  | 19        | 3.04%   |
| Logitech                               | 13        | 2.08%   |
| Sonix Technology                       | 12        | 1.92%   |
| Acer                                   | 11        | 1.76%   |
| Suyin                                  | 8         | 1.28%   |
| Silicon Motion                         | 4         | 0.64%   |
| Alcor Micro                            | 4         | 0.64%   |
| Primax Electronics                     | 3         | 0.48%   |
| Lenovo                                 | 3         | 0.48%   |
| Samsung Electronics                    | 2         | 0.32%   |
| Ricoh                                  | 2         | 0.32%   |
| MacroSilicon                           | 2         | 0.32%   |
| Intel                                  | 2         | 0.32%   |
| DLTDC0A9II090N                         | 2         | 0.32%   |
| Trust                                  | 1         | 0.16%   |
| Tripath Technology                     | 1         | 0.16%   |
| ShineTech                              | 1         | 0.16%   |
| OPPO Electronics                       | 1         | 0.16%   |
| LG Electronics                         | 1         | 0.16%   |
| GRANDSTREAM GUV3100                    | 1         | 0.16%   |
| Google                                 | 1         | 0.16%   |
| Generalplus Technology                 | 1         | 0.16%   |
| GEMBIRD                                | 1         | 0.16%   |
| ALi                                    | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 44        | 7.01%   |
| IMC Networks Integrated Camera                               | 40        | 6.37%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 35        | 5.57%   |
| Microdia Integrated_Webcam_HD                                | 20        | 3.18%   |
| Chicony HD WebCam                                            | 19        | 3.03%   |
| Bison Integrated Camera                                      | 15        | 2.39%   |
| Bison HD Webcam                                              | 13        | 2.07%   |
| Syntek Integrated Camera                                     | 12        | 1.91%   |
| Realtek Integrated_Webcam_HD                                 | 12        | 1.91%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                              | 11        | 1.75%   |
| Sonix USB2.0 HD UVC WebCam                                   | 9         | 1.43%   |
| Acer Integrated Camera                                       | 9         | 1.43%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 8         | 1.27%   |
| Sunplus Integrated_Webcam_HD                                 | 7         | 1.11%   |
| Sunplus HD WebCam                                            | 7         | 1.11%   |
| Quanta USB2.0 HD UVC WebCam                                  | 7         | 1.11%   |
| Quanta HP TrueVision HD Camera                               | 7         | 1.11%   |
| Lite-On Integrated Camera                                    | 7         | 1.11%   |
| Quanta HP HD Camera                                          | 6         | 0.96%   |
| Microdia Integrated Webcam                                   | 6         | 0.96%   |
| Chicony USB2.0 HD UVC WebCam                                 | 6         | 0.96%   |
| Bison BisonCam,NB Pro                                        | 6         | 0.96%   |
| Lite-On HP HD Camera                                         | 5         | 0.8%    |
| IMC Networks ov9734_azurewave_camera                         | 5         | 0.8%    |
| Chicony VGA WebCam                                           | 5         | 0.8%    |
| Chicony USB2.0 VGA UVC WebCam                                | 5         | 0.8%    |
| Chicony HP TrueVision HD Camera                              | 5         | 0.8%    |
| Chicony HD User Facing                                       | 5         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 5         | 0.8%    |
| Bison SunplusIT Integrated Camera                            | 5         | 0.8%    |
| Bison EasyCamera                                             | 5         | 0.8%    |
| Apple FaceTime HD Camera (Built-in)                          | 5         | 0.8%    |
| Syntek Lenovo EasyCamera                                     | 4         | 0.64%   |
| Sunplus Asus Webcam                                          | 4         | 0.64%   |
| Quanta VGA WebCam                                            | 4         | 0.64%   |
| Quanta HD User Facing                                        | 4         | 0.64%   |
| Microdia USB 2.0 Camera                                      | 4         | 0.64%   |
| Luxvisions Innotech Limited Integrated RGB Camera            | 4         | 0.64%   |
| Luxvisions Innotech Limited Integrated Camera                | 4         | 0.64%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 4         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 41        | 32.54%  |
| Validity Sensors                   | 34        | 26.98%  |
| Shenzhen Goodix Technology         | 21        | 16.67%  |
| Elan Microelectronics              | 16        | 12.7%   |
| LighTuning Technology              | 6         | 4.76%   |
| Upek                               | 3         | 2.38%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.38%   |
| AuthenTec                          | 2         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                                        | 14        | 11.11%  |
| Elan ELAN:Fingerprint                                                      | 9         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 6.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 5.56%   |
| Elan ELAN:ARM-M4                                                           | 7         | 5.56%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.97%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.38%   |
| Validity Sensors VFS491                                                    | 3         | 2.38%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.38%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.38%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 2.38%   |
| Synaptics UWP WBDI                                                         | 3         | 2.38%   |
| Synaptics  WBDI                                                            | 3         | 2.38%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 2.38%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 2.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.59%   |
| Synaptics WBDI                                                             | 2         | 1.59%   |
| Unknown                                                                    | 2         | 1.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.79%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.79%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.79%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.79%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.79%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.79%   |
| AuthenTec AES2810                                                          | 1         | 0.79%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 24        | 55.81%  |
| Alcor Micro | 12        | 27.91%  |
| Lenovo      | 3         | 6.98%   |
| Upek        | 2         | 4.65%   |
| O2 Micro    | 2         | 4.65%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 22.73%  |
| Broadcom 5880                                                                | 6         | 13.64%  |
| Broadcom 58200                                                               | 6         | 13.64%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.82%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6.82%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 419       | 59.1%   |
| 1     | 242       | 34.13%  |
| 2     | 46        | 6.49%   |
| 3     | 2         | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 126       | 38.3%   |
| Net/ethernet             | 41        | 12.46%  |
| Chipcard                 | 41        | 12.46%  |
| Multimedia controller    | 40        | 12.16%  |
| Graphics card            | 31        | 9.42%   |
| Net/wireless             | 21        | 6.38%   |
| Camera                   | 12        | 3.65%   |
| Bluetooth                | 10        | 3.04%   |
| Storage                  | 2         | 0.61%   |
| Communication controller | 2         | 0.61%   |
| Unassigned class         | 1         | 0.3%    |
| Modem                    | 1         | 0.3%    |
| Card reader              | 1         | 0.3%    |

