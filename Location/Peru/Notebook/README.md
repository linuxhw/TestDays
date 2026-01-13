Linux in Peru - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Peru.

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

Total: 558

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo     | IdeaPad Slim 3 15IRH10 8... | [48dad43a94](https://linux-hardware.org/?probe=48dad43a94) | Jan 03, 2026 |
| HP         | Pavilion Laptop 15-cw1xx... | [41269d55ef](https://linux-hardware.org/?probe=41269d55ef) | Jan 02, 2026 |
| Dell       | Inspiron 5421               | [962e4faf7f](https://linux-hardware.org/?probe=962e4faf7f) | Dec 07, 2025 |
| Acer       | Aspire A515-56              | [f9694f2d35](https://linux-hardware.org/?probe=f9694f2d35) | Dec 07, 2025 |
| Toshiba    | Satellite A500              | [843d18c706](https://linux-hardware.org/?probe=843d18c706) | Nov 28, 2025 |
| HP         | Laptop 14-cm1xxx            | [5bf51e2181](https://linux-hardware.org/?probe=5bf51e2181) | Nov 26, 2025 |
| HP         | Laptop 15-dw3xxx            | [86c0d58b32](https://linux-hardware.org/?probe=86c0d58b32) | Nov 24, 2025 |
| HP         | 1000                        | [5c1c57a137](https://linux-hardware.org/?probe=5c1c57a137) | Nov 20, 2025 |
| Lenovo     | S145-15AST Laptop(IdeaPa... | [19839f9206](https://linux-hardware.org/?probe=19839f9206) | Nov 19, 2025 |
| Lenovo     | S145-15AST Laptop(IdeaPa... | [6c02b712d8](https://linux-hardware.org/?probe=6c02b712d8) | Nov 19, 2025 |
| ASUSTek    | VivoBook_ASUSLaptop X160... | [eeea55aece](https://linux-hardware.org/?probe=eeea55aece) | Nov 13, 2025 |
| Lenovo     | IdeaPad Z410 20292          | [cf5085d95b](https://linux-hardware.org/?probe=cf5085d95b) | Nov 12, 2025 |
| Lenovo     | G40-80 80E4                 | [459dcbd757](https://linux-hardware.org/?probe=459dcbd757) | Nov 08, 2025 |
| Toshiba    | Satellite C45-A             | [ae89bbeb4b](https://linux-hardware.org/?probe=ae89bbeb4b) | Nov 06, 2025 |
| Dell       | XPS 9315                    | [322a0843d2](https://linux-hardware.org/?probe=322a0843d2) | Oct 26, 2025 |
| Dell       | XPS 9315                    | [d4201f0c58](https://linux-hardware.org/?probe=d4201f0c58) | Oct 22, 2025 |
| Dell       | Inspiron 3501               | [0be2178dbe](https://linux-hardware.org/?probe=0be2178dbe) | Oct 20, 2025 |
| Lenovo     | G40-80 80E4                 | [df042238d5](https://linux-hardware.org/?probe=df042238d5) | Oct 15, 2025 |
| Lenovo     | G40-80 80E4                 | [3c426d7278](https://linux-hardware.org/?probe=3c426d7278) | Oct 15, 2025 |
| Toshiba    | Satellite L755              | [f8562bb58a](https://linux-hardware.org/?probe=f8562bb58a) | Oct 14, 2025 |
| Toshiba    | Satellite L755              | [e131d69d93](https://linux-hardware.org/?probe=e131d69d93) | Oct 03, 2025 |
| Lenovo     | IdeaPad 330-15IKB 81DE      | [6a7d693e77](https://linux-hardware.org/?probe=6a7d693e77) | Oct 03, 2025 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [6869b0a724](https://linux-hardware.org/?probe=6869b0a724) | Sep 29, 2025 |
| Lenovo     | S145-15AST Laptop(IdeaPa... | [b525efbf9e](https://linux-hardware.org/?probe=b525efbf9e) | Sep 29, 2025 |
| Lenovo     | S145-15AST Laptop(IdeaPa... | [fd6329dded](https://linux-hardware.org/?probe=fd6329dded) | Sep 29, 2025 |
| Dell       | Inspiron 14-3467            | [542ac3e9c0](https://linux-hardware.org/?probe=542ac3e9c0) | Sep 28, 2025 |
| HP         | ZBook 15                    | [787e1db37e](https://linux-hardware.org/?probe=787e1db37e) | Sep 27, 2025 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [ad86d534d5](https://linux-hardware.org/?probe=ad86d534d5) | Sep 27, 2025 |
| Lenovo     | IdeaPad 330-14IKB 81G2      | [58645d5c20](https://linux-hardware.org/?probe=58645d5c20) | Sep 27, 2025 |
| Toshiba    | Satellite L755              | [83c25e7153](https://linux-hardware.org/?probe=83c25e7153) | Sep 25, 2025 |
| Dell       | Latitude E5440              | [bd12814a9e](https://linux-hardware.org/?probe=bd12814a9e) | Sep 16, 2025 |
| Dell       | Inspiron 3505               | [be7825a330](https://linux-hardware.org/?probe=be7825a330) | Sep 08, 2025 |
| HP         | ZBook 17 G3                 | [c7d807af40](https://linux-hardware.org/?probe=c7d807af40) | Aug 22, 2025 |
| Lenovo     | ThinkPad T16 Gen 2 21K8C... | [e74d6820eb](https://linux-hardware.org/?probe=e74d6820eb) | Aug 15, 2025 |
| ASUSTek    | VivoBook_ASUSLaptop X160... | [4fbbcc723d](https://linux-hardware.org/?probe=4fbbcc723d) | Aug 10, 2025 |
| ASUSTek    | ROG Zephyrus G14 GA403UI... | [5a129d14f2](https://linux-hardware.org/?probe=5a129d14f2) | Jul 26, 2025 |
| ASUSTek    | VivoBook_ASUSLaptop X150... | [78ebd465f4](https://linux-hardware.org/?probe=78ebd465f4) | Jul 22, 2025 |
| HP         | 240 G7 Notebook PC          | [490557e657](https://linux-hardware.org/?probe=490557e657) | Jul 21, 2025 |
| HP         | Laptop 15-dw1xxx            | [34ab13e8ff](https://linux-hardware.org/?probe=34ab13e8ff) | Jul 10, 2025 |
| ASUSTek    | ASUS Vivobook Pro 15 N65... | [6c4c70c87d](https://linux-hardware.org/?probe=6c4c70c87d) | Jul 04, 2025 |
| Sony       | SVF14213CLB                 | [daea350931](https://linux-hardware.org/?probe=daea350931) | Jun 23, 2025 |
| Dell       | XPS 13 9360                 | [b165b7cd23](https://linux-hardware.org/?probe=b165b7cd23) | Jun 21, 2025 |
| ASUSTek    | X542UQ                      | [57c664ab63](https://linux-hardware.org/?probe=57c664ab63) | Jun 16, 2025 |
| ASUSTek    | ASUS Zenbook 14 UM3406HA... | [71cb727642](https://linux-hardware.org/?probe=71cb727642) | Jun 11, 2025 |
| Sony       | VGN-CR260F                  | [ee56468a4c](https://linux-hardware.org/?probe=ee56468a4c) | Jun 07, 2025 |
| Lenovo     | IdeaPad 3 15ALC6 82KU       | [0748848a6d](https://linux-hardware.org/?probe=0748848a6d) | Jun 07, 2025 |
| Lenovo     | IdeaPad 3 15IIL05 81WE      | [c4f8f784f9](https://linux-hardware.org/?probe=c4f8f784f9) | Jun 03, 2025 |
| HP         | Laptop 15-da0xxx            | [3b26e7d15c](https://linux-hardware.org/?probe=3b26e7d15c) | May 30, 2025 |
| Acer       | Aspire A315-59              | [d6cd2d06be](https://linux-hardware.org/?probe=d6cd2d06be) | May 20, 2025 |
| Lenovo     | V15 G3 IAP 82TT             | [9d72e95f24](https://linux-hardware.org/?probe=9d72e95f24) | May 18, 2025 |
| HP         | 245 G7                      | [f73fc77354](https://linux-hardware.org/?probe=f73fc77354) | May 12, 2025 |
| HP         | Laptop 15-da0xxx            | [ab8f21fe7f](https://linux-hardware.org/?probe=ab8f21fe7f) | May 03, 2025 |
| HP         | Laptop 15-da0xxx            | [fdc94029ee](https://linux-hardware.org/?probe=fdc94029ee) | May 03, 2025 |
| ASUSTek    | VivoBook_ASUSLaptop X160... | [4f31528209](https://linux-hardware.org/?probe=4f31528209) | Apr 29, 2025 |
| Lenovo     | V15 G3 ABA 82TV             | [cfa1c55512](https://linux-hardware.org/?probe=cfa1c55512) | Apr 26, 2025 |
| Acer       | Nitro AN515-55              | [3201bc1451](https://linux-hardware.org/?probe=3201bc1451) | Apr 20, 2025 |
| Lenovo     | V310-15ISK 80SY             | [1b35b696dd](https://linux-hardware.org/?probe=1b35b696dd) | Apr 18, 2025 |
| Valve      | Jupiter                     | [6db523cd42](https://linux-hardware.org/?probe=6db523cd42) | Apr 17, 2025 |
| Acer       | Aspire 4736                 | [49da7e22ed](https://linux-hardware.org/?probe=49da7e22ed) | Apr 14, 2025 |
| HP         | Compaq 15                   | [84ddb2a884](https://linux-hardware.org/?probe=84ddb2a884) | Apr 11, 2025 |
| HP         | Compaq 15                   | [612fc4b67c](https://linux-hardware.org/?probe=612fc4b67c) | Apr 09, 2025 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [811356ab75](https://linux-hardware.org/?probe=811356ab75) | Apr 06, 2025 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [d97b227a42](https://linux-hardware.org/?probe=d97b227a42) | Apr 06, 2025 |
| Acer       | Aspire E5-774               | [cabfdab622](https://linux-hardware.org/?probe=cabfdab622) | Apr 01, 2025 |
| Sony       | VPCZ120GL                   | [ad6c8045fe](https://linux-hardware.org/?probe=ad6c8045fe) | Apr 01, 2025 |
| Dell       | Inspiron 5567               | [231e589bb6](https://linux-hardware.org/?probe=231e589bb6) | Mar 11, 2025 |
| HP         | ProBook 4430s               | [225abef2f5](https://linux-hardware.org/?probe=225abef2f5) | Mar 04, 2025 |
| ASUSTek    | ROG Zephyrus G14 GA403UV... | [354f7cc550](https://linux-hardware.org/?probe=354f7cc550) | Mar 02, 2025 |
| ASUSTek    | ROG Zephyrus G14 GA403UV... | [bf3fe68b77](https://linux-hardware.org/?probe=bf3fe68b77) | Mar 02, 2025 |
| HP         | ProBook 4430s               | [6931376a63](https://linux-hardware.org/?probe=6931376a63) | Feb 28, 2025 |
| ASUSTek    | VivoBook_ASUSLaptop X160... | [1be3763a41](https://linux-hardware.org/?probe=1be3763a41) | Feb 20, 2025 |
| HP         | Pavilion Gaming Laptop 1... | [a4e847a7fd](https://linux-hardware.org/?probe=a4e847a7fd) | Feb 20, 2025 |
| Dell       | Inspiron MP061              | [b995685a87](https://linux-hardware.org/?probe=b995685a87) | Feb 03, 2025 |
| Dell       | Inspiron MP061              | [ff7bdb9ff5](https://linux-hardware.org/?probe=ff7bdb9ff5) | Feb 03, 2025 |
| ASUSTek    | N501VW                      | [ba51603b74](https://linux-hardware.org/?probe=ba51603b74) | Jan 30, 2025 |
| Lenovo     | LOQ 15IRH8 82XV             | [fd88e70119](https://linux-hardware.org/?probe=fd88e70119) | Jan 22, 2025 |
| Lenovo     | IdeaPad 3 15IIL05 81WE      | [69b5272424](https://linux-hardware.org/?probe=69b5272424) | Jan 20, 2025 |
| Dell       | Inspiron 3501               | [7c36829ffc](https://linux-hardware.org/?probe=7c36829ffc) | Jan 15, 2025 |
| Lenovo     | IdeaPad 3 15IIL05 81WE      | [de70f3fc74](https://linux-hardware.org/?probe=de70f3fc74) | Jan 14, 2025 |
| HP         | ProBook 6560b               | [e639c92dfe](https://linux-hardware.org/?probe=e639c92dfe) | Jan 14, 2025 |
| ASUSTek    | S400CA                      | [a076c3dca9](https://linux-hardware.org/?probe=a076c3dca9) | Dec 20, 2024 |
| Lenovo     | G50-80 80E5                 | [e3ff832ae6](https://linux-hardware.org/?probe=e3ff832ae6) | Dec 11, 2024 |
| HP         | Pavilion g4                 | [be7deb3d00](https://linux-hardware.org/?probe=be7deb3d00) | Dec 10, 2024 |
| MSI        | GL72M 7REX                  | [fbeb721328](https://linux-hardware.org/?probe=fbeb721328) | Dec 05, 2024 |
| HP         | Pavilion g4                 | [42bd25b20f](https://linux-hardware.org/?probe=42bd25b20f) | Dec 02, 2024 |
| ASUSTek    | S400CA                      | [6b626eb981](https://linux-hardware.org/?probe=6b626eb981) | Dec 01, 2024 |
| HP         | Pavilion Gaming Laptop 1... | [7af06c00e5](https://linux-hardware.org/?probe=7af06c00e5) | Dec 01, 2024 |
| HP         | Laptop 15-fd0xxx            | [5bc6ff3fa8](https://linux-hardware.org/?probe=5bc6ff3fa8) | Nov 19, 2024 |
| Lenovo     | ThinkPad E16 Gen 1 21JU0... | [9fdbbb1b89](https://linux-hardware.org/?probe=9fdbbb1b89) | Nov 17, 2024 |
| Lenovo     | ThinkPad E16 Gen 1 21JU0... | [49190049b9](https://linux-hardware.org/?probe=49190049b9) | Nov 17, 2024 |
| Acer       | Aspire E5-774               | [b81d46ef22](https://linux-hardware.org/?probe=b81d46ef22) | Nov 05, 2024 |
| Acer       | Aspire E5-774               | [24b5385ac1](https://linux-hardware.org/?probe=24b5385ac1) | Oct 30, 2024 |
| Dell       | Latitude E7440              | [59f882ef98](https://linux-hardware.org/?probe=59f882ef98) | Oct 25, 2024 |
| Dell       | Latitude E7440              | [48182c2497](https://linux-hardware.org/?probe=48182c2497) | Oct 25, 2024 |
| Lenovo     | Legion Y540-15IRH-PG0 81... | [1c61630c00](https://linux-hardware.org/?probe=1c61630c00) | Oct 20, 2024 |
| Toshiba    | QOSMIO X75-A                | [90eddc4513](https://linux-hardware.org/?probe=90eddc4513) | Oct 20, 2024 |
| Toshiba    | QOSMIO X75-A                | [7bbaac259d](https://linux-hardware.org/?probe=7bbaac259d) | Oct 20, 2024 |
| Dell       | Latitude 5540               | [ba75f2134f](https://linux-hardware.org/?probe=ba75f2134f) | Oct 19, 2024 |
| Acer       | Aspire A315-59G             | [3c57995295](https://linux-hardware.org/?probe=3c57995295) | Oct 05, 2024 |
| Lenovo     | G585 20137                  | [379f6e6fef](https://linux-hardware.org/?probe=379f6e6fef) | Oct 05, 2024 |
| HP         | Pavilion g4                 | [c705d7afa6](https://linux-hardware.org/?probe=c705d7afa6) | Oct 05, 2024 |
| Acer       | Aspire ES1-531              | [16c5519c67](https://linux-hardware.org/?probe=16c5519c67) | Sep 30, 2024 |
| Acer       | Aspire A315-55G             | [3f77776e4c](https://linux-hardware.org/?probe=3f77776e4c) | Sep 24, 2024 |
| Gateway    | NV55C                       | [151ce02b0c](https://linux-hardware.org/?probe=151ce02b0c) | Sep 16, 2024 |
| Gateway    | NV55C                       | [f7170c1236](https://linux-hardware.org/?probe=f7170c1236) | Sep 16, 2024 |
| Google     | Storo                       | [fff45fd343](https://linux-hardware.org/?probe=fff45fd343) | Sep 13, 2024 |
| HUAWEI     | NBM-WXX9                    | [c1712b4ef5](https://linux-hardware.org/?probe=c1712b4ef5) | Sep 12, 2024 |
| Google     | Storo                       | [f39c3f92b1](https://linux-hardware.org/?probe=f39c3f92b1) | Sep 11, 2024 |
| HP         | Pavilion Gaming Laptop 1... | [1ac4846a16](https://linux-hardware.org/?probe=1ac4846a16) | Sep 03, 2024 |
| HP         | Pavilion g4                 | [cee1aebcc0](https://linux-hardware.org/?probe=cee1aebcc0) | Aug 28, 2024 |
| Valve      | Galileo                     | [71ce12da6b](https://linux-hardware.org/?probe=71ce12da6b) | Aug 27, 2024 |
| Toshiba    | Satellite C45-A             | [1a81d7fa5c](https://linux-hardware.org/?probe=1a81d7fa5c) | Aug 26, 2024 |
| ASUSTek    | VivoBook_ASUSLaptop X150... | [b8adeadb11](https://linux-hardware.org/?probe=b8adeadb11) | Aug 25, 2024 |
| HP         | ProBook 640 G1              | [d1f86fd641](https://linux-hardware.org/?probe=d1f86fd641) | Aug 08, 2024 |
| Lenovo     | 3000 N500 4233A14           | [ae44dcd68e](https://linux-hardware.org/?probe=ae44dcd68e) | Aug 01, 2024 |
| ASUSTek    | VivoBook_ASUSLaptop X160... | [7cc5cb201a](https://linux-hardware.org/?probe=7cc5cb201a) | Jul 29, 2024 |
| Lenovo     | IdeaPad 100S-11IBY 80R2     | [365d877167](https://linux-hardware.org/?probe=365d877167) | Jul 25, 2024 |
| HP         | Pavilion Gaming Laptop 1... | [9186d6890f](https://linux-hardware.org/?probe=9186d6890f) | Jul 23, 2024 |
| Dell       | G3 3779                     | [20366c590d](https://linux-hardware.org/?probe=20366c590d) | Jul 22, 2024 |
| Dell       | G3 3779                     | [7c990f5b0f](https://linux-hardware.org/?probe=7c990f5b0f) | Jul 22, 2024 |
| Lenovo     | IdeaPad 330-15IKB 81DE      | [96a15691d5](https://linux-hardware.org/?probe=96a15691d5) | Jul 20, 2024 |
| Lenovo     | ThinkPad W540 20BH002NLM    | [98a58c738f](https://linux-hardware.org/?probe=98a58c738f) | Jul 14, 2024 |
| Dell       | Precision 3541              | [fd3dbaf3d6](https://linux-hardware.org/?probe=fd3dbaf3d6) | Jul 09, 2024 |
| Lenovo     | G400 20235                  | [2740ab422f](https://linux-hardware.org/?probe=2740ab422f) | Jul 05, 2024 |
| HP         | Laptop 15-bw0xx             | [3a1445300b](https://linux-hardware.org/?probe=3a1445300b) | Jun 28, 2024 |
| Lenovo     | ThinkPad T470s W10DG 20J... | [35390b11ef](https://linux-hardware.org/?probe=35390b11ef) | Jun 25, 2024 |
| HP         | Laptop 14-ck0xxx            | [b63a668d43](https://linux-hardware.org/?probe=b63a668d43) | Jun 19, 2024 |
| Dell       | Inspiron 3458               | [484309983e](https://linux-hardware.org/?probe=484309983e) | Jun 18, 2024 |
| Lenovo     | ThinkPad P1 20MES0E900      | [4343f5b4ad](https://linux-hardware.org/?probe=4343f5b4ad) | Jun 12, 2024 |
| Lenovo     | ThinkPad P1 20MES0E900      | [c711f7f5e2](https://linux-hardware.org/?probe=c711f7f5e2) | Jun 12, 2024 |
| Lenovo     | IdeaPad 3 14IIL05 81WD      | [68667d6b61](https://linux-hardware.org/?probe=68667d6b61) | Jun 09, 2024 |
| HP         | Laptop 15-bs0xx             | [750c40c84c](https://linux-hardware.org/?probe=750c40c84c) | May 22, 2024 |
| Dell       | Inspiron 5521               | [7b5e2f5c2e](https://linux-hardware.org/?probe=7b5e2f5c2e) | May 20, 2024 |
| ASUSTek    | VivoBook_ASUSLaptop X160... | [972388da07](https://linux-hardware.org/?probe=972388da07) | May 13, 2024 |
| Toshiba    | Satellite E55-A             | [b77667e33a](https://linux-hardware.org/?probe=b77667e33a) | May 08, 2024 |
| HP         | Laptop 15-bs0xx             | [f0bc418296](https://linux-hardware.org/?probe=f0bc418296) | May 08, 2024 |
| Lenovo     | Unknown                     | [dae6c8e749](https://linux-hardware.org/?probe=dae6c8e749) | May 06, 2024 |
| Apple      | MacBookPro9,2               | [120440b735](https://linux-hardware.org/?probe=120440b735) | May 01, 2024 |
| Toshiba    | Satellite E55-A             | [66fc7bf95a](https://linux-hardware.org/?probe=66fc7bf95a) | Apr 30, 2024 |
| Lenovo     | ThinkPad T440 20B7000CLM    | [49c44d3355](https://linux-hardware.org/?probe=49c44d3355) | Apr 21, 2024 |
| Lenovo     | ThinkPad T440 20B7000CLM    | [b6124fdf94](https://linux-hardware.org/?probe=b6124fdf94) | Apr 21, 2024 |
| Lenovo     | Y50-70 20378                | [50de89d752](https://linux-hardware.org/?probe=50de89d752) | Apr 18, 2024 |
| Lenovo     | Legion Pro 5 16IRX8 82WK    | [323bf9fa10](https://linux-hardware.org/?probe=323bf9fa10) | Apr 04, 2024 |
| Lenovo     | Legion Pro 5 16IRX8 82WK    | [c41823fc76](https://linux-hardware.org/?probe=c41823fc76) | Apr 04, 2024 |
| Chuwi      | GemiBook Pro                | [bfb77127c6](https://linux-hardware.org/?probe=bfb77127c6) | Mar 31, 2024 |
| Toshiba    | Satellite L45-B             | [7a6b9a0b7b](https://linux-hardware.org/?probe=7a6b9a0b7b) | Mar 28, 2024 |
| HUAWEI     | NBLB-WAX9N                  | [de162db434](https://linux-hardware.org/?probe=de162db434) | Mar 27, 2024 |
| HUAWEI     | NBLB-WAX9N                  | [e5c5d49216](https://linux-hardware.org/?probe=e5c5d49216) | Mar 22, 2024 |
| ASUSTek    | VivoBook_ASUSLaptop M160... | [c6499bbbb9](https://linux-hardware.org/?probe=c6499bbbb9) | Mar 21, 2024 |
| ASUSTek    | VivoBook_ASUSLaptop M160... | [d6d2c95a7a](https://linux-hardware.org/?probe=d6d2c95a7a) | Mar 17, 2024 |
| Lenovo     | IdeaPad 3 14ADA05 81W0      | [cd9270ccb4](https://linux-hardware.org/?probe=cd9270ccb4) | Mar 14, 2024 |
| Lenovo     | IdeaPad 5 14ALC05 82LM      | [9d3648dfb3](https://linux-hardware.org/?probe=9d3648dfb3) | Mar 04, 2024 |
| HP         | ZBook 15                    | [bcb41f3b4c](https://linux-hardware.org/?probe=bcb41f3b4c) | Feb 14, 2024 |
| Apple      | MacBookPro16,1              | [da438018c3](https://linux-hardware.org/?probe=da438018c3) | Feb 10, 2024 |
| ASUSTek    | VivoBook_ASUSLaptop X160... | [6f80a7214c](https://linux-hardware.org/?probe=6f80a7214c) | Feb 01, 2024 |
| ASUSTek    | G75VX                       | [5c270f1082](https://linux-hardware.org/?probe=5c270f1082) | Jan 30, 2024 |
| Samsung    | 905S3G/906S3G/915S3G/930... | [8c1fb214b8](https://linux-hardware.org/?probe=8c1fb214b8) | Jan 25, 2024 |
| Samsung    | 905S3G/906S3G/915S3G/930... | [f3512d75e9](https://linux-hardware.org/?probe=f3512d75e9) | Jan 24, 2024 |
| Dell       | Latitude 7430               | [153f1a144c](https://linux-hardware.org/?probe=153f1a144c) | Jan 19, 2024 |
| Dell       | Latitude 7430               | [a05210eeb4](https://linux-hardware.org/?probe=a05210eeb4) | Jan 19, 2024 |
| System76   | Adder WS                    | [94120ee028](https://linux-hardware.org/?probe=94120ee028) | Jan 11, 2024 |
| ASUSTek    | UX510UXK                    | [17be26f2de](https://linux-hardware.org/?probe=17be26f2de) | Jan 04, 2024 |
| Toshiba    | Satellite P55-B             | [9a1e5dc1f6](https://linux-hardware.org/?probe=9a1e5dc1f6) | Dec 31, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X160... | [460fe0575c](https://linux-hardware.org/?probe=460fe0575c) | Dec 30, 2023 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [1594f8077b](https://linux-hardware.org/?probe=1594f8077b) | Dec 27, 2023 |
| Sony       | SVS13A25PLB                 | [9b32de2519](https://linux-hardware.org/?probe=9b32de2519) | Dec 27, 2023 |
| HP         | Pavilion Gaming Laptop 1... | [bcae8d434f](https://linux-hardware.org/?probe=bcae8d434f) | Dec 19, 2023 |
| Dell       | Latitude E5470              | [9aa1f53217](https://linux-hardware.org/?probe=9aa1f53217) | Dec 18, 2023 |
| Toshiba    | Satellite A300              | [5e373b58ac](https://linux-hardware.org/?probe=5e373b58ac) | Dec 15, 2023 |
| ASRock     | B560M Pro4/ac               | [0dd2927c25](https://linux-hardware.org/?probe=0dd2927c25) | Dec 14, 2023 |
| Apple      | MacBookPro5,4               | [fb45c81af9](https://linux-hardware.org/?probe=fb45c81af9) | Nov 26, 2023 |
| Gigabyte   | B550M K                     | [989886ee56](https://linux-hardware.org/?probe=989886ee56) | Nov 19, 2023 |
| Lenovo     | ThinkPad T16 Gen 1 21BWS... | [f4de613bd5](https://linux-hardware.org/?probe=f4de613bd5) | Nov 15, 2023 |
| Dell       | Latitude 5490               | [ac938f1435](https://linux-hardware.org/?probe=ac938f1435) | Nov 08, 2023 |
| Dell       | Latitude E5470              | [bbbdcac07b](https://linux-hardware.org/?probe=bbbdcac07b) | Nov 07, 2023 |
| Dell       | Latitude E5470              | [19fc06d0b2](https://linux-hardware.org/?probe=19fc06d0b2) | Nov 07, 2023 |
| Lenovo     | IdeaPad 110-15ISK 80UD      | [de293a4621](https://linux-hardware.org/?probe=de293a4621) | Nov 03, 2023 |
| HP         | Laptop 15-fc0xxx            | [d0be3aec4e](https://linux-hardware.org/?probe=d0be3aec4e) | Nov 01, 2023 |
| Lenovo     | ThinkPad T16 Gen 1 21BWS... | [8f20a345e3](https://linux-hardware.org/?probe=8f20a345e3) | Oct 24, 2023 |
| HP         | 14                          | [e207fce0d4](https://linux-hardware.org/?probe=e207fce0d4) | Oct 12, 2023 |
| Lenovo     | IdeaPad 110-15IBR 80T7      | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| HP         | EliteBook 2760p             | [e9d026d0df](https://linux-hardware.org/?probe=e9d026d0df) | Sep 29, 2023 |
| Toshiba    | Satellite L45-B             | [e998b320d8](https://linux-hardware.org/?probe=e998b320d8) | Sep 24, 2023 |
| Lenovo     | IdeaPad 3 14IIL05 81WD      | [952169c1ce](https://linux-hardware.org/?probe=952169c1ce) | Sep 24, 2023 |
| HP         | Pavilion dv4                | [b1ee39c175](https://linux-hardware.org/?probe=b1ee39c175) | Sep 24, 2023 |
| ASUSTek    | X550LD                      | [9d8e946b59](https://linux-hardware.org/?probe=9d8e946b59) | Sep 21, 2023 |
| ASUSTek    | X550LD                      | [18a02021f6](https://linux-hardware.org/?probe=18a02021f6) | Sep 21, 2023 |
| Lenovo     | IdeaPad 3 14IIL05 81WD      | [e9c24b2427](https://linux-hardware.org/?probe=e9c24b2427) | Sep 18, 2023 |
| ASUSTek    | G752VY                      | [7d3353b537](https://linux-hardware.org/?probe=7d3353b537) | Sep 15, 2023 |
| HP         | OMEN by Laptop 17-ck0xxx    | [09c2d451ab](https://linux-hardware.org/?probe=09c2d451ab) | Sep 11, 2023 |
| HP         | OMEN by Laptop 15-dc0xxx    | [38a80416eb](https://linux-hardware.org/?probe=38a80416eb) | Sep 10, 2023 |
| Google     | Treeya                      | [a4db63abbe](https://linux-hardware.org/?probe=a4db63abbe) | Sep 10, 2023 |
| HP         | Pavilion dv4                | [0b01aaddd6](https://linux-hardware.org/?probe=0b01aaddd6) | Sep 06, 2023 |
| Google     | Treeya                      | [fcc8d7d8a1](https://linux-hardware.org/?probe=fcc8d7d8a1) | Sep 05, 2023 |
| HP         | Notebook                    | [3a7a5608af](https://linux-hardware.org/?probe=3a7a5608af) | Sep 04, 2023 |
| Dell       | Latitude 5490               | [392d7335ed](https://linux-hardware.org/?probe=392d7335ed) | Sep 03, 2023 |
| HP         | OMEN Laptop 15-en0xxx       | [47ef8122dc](https://linux-hardware.org/?probe=47ef8122dc) | Sep 03, 2023 |
| HP         | Laptop 15-da0xxx            | [4c9a89e532](https://linux-hardware.org/?probe=4c9a89e532) | Aug 27, 2023 |
| HP         | ProBook 640 G1              | [c3b97aa105](https://linux-hardware.org/?probe=c3b97aa105) | Aug 27, 2023 |
| ASUSTek    | GL552VX                     | [fbe195ec09](https://linux-hardware.org/?probe=fbe195ec09) | Aug 17, 2023 |
| ASUSTek    | GL552VX                     | [37a66a073b](https://linux-hardware.org/?probe=37a66a073b) | Aug 17, 2023 |
| HP         | ZBook 15                    | [97923a8762](https://linux-hardware.org/?probe=97923a8762) | Aug 15, 2023 |
| Chuwi      | GemiBook Pro                | [b5685bdafc](https://linux-hardware.org/?probe=b5685bdafc) | Aug 10, 2023 |
| HP         | Laptop 15-dw0xxx            | [08e20bb994](https://linux-hardware.org/?probe=08e20bb994) | Jul 31, 2023 |
| Lenovo     | IdeaPad S145-14AST 81ST     | [c51105da6a](https://linux-hardware.org/?probe=c51105da6a) | Jul 28, 2023 |
| Lenovo     | IdeaPad 330-15IKB 81DE      | [8cde0390c4](https://linux-hardware.org/?probe=8cde0390c4) | Jul 26, 2023 |
| HP         | ProBook 440 G2              | [85168259e3](https://linux-hardware.org/?probe=85168259e3) | Jul 25, 2023 |
| HP         | Compaq Presario C700        | [71ca83faee](https://linux-hardware.org/?probe=71ca83faee) | Jul 23, 2023 |
| Lenovo     | IdeaPad 3 15ITL6 82H8       | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| Lenovo     | IdeaPad 3 15ITL6 82H8       | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Acer       | Predator PH16-71            | [1917d24a87](https://linux-hardware.org/?probe=1917d24a87) | Jul 15, 2023 |
| HP         | Compaq Presario C700        | [32659f379c](https://linux-hardware.org/?probe=32659f379c) | Jul 09, 2023 |
| HP         | 240 G7 Notebook PC          | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop M160... | [265dc6c0e9](https://linux-hardware.org/?probe=265dc6c0e9) | Jul 06, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| HP         | 250 G5 Notebook PC          | [99c60820c5](https://linux-hardware.org/?probe=99c60820c5) | Jul 05, 2023 |
| Lenovo     | IdeaPad 3 14ADA05 81W0      | [2b4069db98](https://linux-hardware.org/?probe=2b4069db98) | Jun 25, 2023 |
| ASUSTek    | ROG Strix G513RC_G513RC     | [1d6a241c9e](https://linux-hardware.org/?probe=1d6a241c9e) | Jun 23, 2023 |
| Chuwi      | GemiBook Pro                | [34cfc4a037](https://linux-hardware.org/?probe=34cfc4a037) | Jun 13, 2023 |
| ASUSTek    | ROG Zephyrus G14 GA401QC... | [57f37d5836](https://linux-hardware.org/?probe=57f37d5836) | Jun 10, 2023 |
| Lenovo     | IdeaPad L340-15API 81LW     | [1794287cf0](https://linux-hardware.org/?probe=1794287cf0) | Jun 09, 2023 |
| HP         | 14                          | [1540a787fb](https://linux-hardware.org/?probe=1540a787fb) | Jun 09, 2023 |
| HP         | 14                          | [1404218cab](https://linux-hardware.org/?probe=1404218cab) | Jun 09, 2023 |
| Apple      | MacBookPro9,2               | [c22081b097](https://linux-hardware.org/?probe=c22081b097) | Jun 09, 2023 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [97d002b53a](https://linux-hardware.org/?probe=97d002b53a) | Jun 08, 2023 |
| Lenovo     | Legion S7 15ACH6 82K8       | [8f160a999a](https://linux-hardware.org/?probe=8f160a999a) | Jun 08, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [bb571d888d](https://linux-hardware.org/?probe=bb571d888d) | Jun 08, 2023 |
| Apple      | MacBookPro9,2               | [8d70c1dd42](https://linux-hardware.org/?probe=8d70c1dd42) | Jun 07, 2023 |
| Toshiba    | Satellite L45-B             | [a1bcda2245](https://linux-hardware.org/?probe=a1bcda2245) | Jun 05, 2023 |
| ASUSTek    | TUF Gaming FX505DT_FX505... | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [a5ebbfe1ef](https://linux-hardware.org/?probe=a5ebbfe1ef) | May 31, 2023 |
| HP         | 14                          | [977d26c9b5](https://linux-hardware.org/?probe=977d26c9b5) | May 29, 2023 |
| Lenovo     | G400 20235                  | [193fbef9a1](https://linux-hardware.org/?probe=193fbef9a1) | May 28, 2023 |
| HP         | Laptop 15-dy5xxx            | [3ab3a101e8](https://linux-hardware.org/?probe=3ab3a101e8) | May 21, 2023 |
| Sony       | VPCEL36FJ                   | [c372bac204](https://linux-hardware.org/?probe=c372bac204) | May 21, 2023 |
| HP         | Victus by Gaming Laptop ... | [8f2ccf9c6d](https://linux-hardware.org/?probe=8f2ccf9c6d) | May 21, 2023 |
| Lenovo     | ThinkPad L460 20FVS3JK00    | [c812ee44af](https://linux-hardware.org/?probe=c812ee44af) | May 18, 2023 |
| Dell       | Latitude E7450              | [cb96fcfaff](https://linux-hardware.org/?probe=cb96fcfaff) | May 12, 2023 |
| Chuwi      | GemiBook Pro                | [b63292a4f9](https://linux-hardware.org/?probe=b63292a4f9) | May 11, 2023 |
| Apple      | MacBookPro11,5              | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| MSI        | PS42 Modern 8RA             | [8371e35044](https://linux-hardware.org/?probe=8371e35044) | May 08, 2023 |
| Dell       | G5 5505                     | [94e01ce854](https://linux-hardware.org/?probe=94e01ce854) | May 07, 2023 |
| Dell       | G5 5505                     | [b484646926](https://linux-hardware.org/?probe=b484646926) | May 07, 2023 |
| HP         | Pavilion 11                 | [696ac990d2](https://linux-hardware.org/?probe=696ac990d2) | May 07, 2023 |
| HP         | Pavilion g4                 | [5e3bd3ea22](https://linux-hardware.org/?probe=5e3bd3ea22) | May 06, 2023 |
| ASUSTek    | ROG Strix G513RC_G513RC     | [d1dc588f69](https://linux-hardware.org/?probe=d1dc588f69) | May 05, 2023 |
| ASUSTek    | ROG Strix G513RC_G513RC     | [9d3ea79ded](https://linux-hardware.org/?probe=9d3ea79ded) | May 04, 2023 |
| HP         | Laptop 15-ef2xxx            | [f922f80a69](https://linux-hardware.org/?probe=f922f80a69) | Apr 28, 2023 |
| Chuwi      | GemiBook Pro                | [b4d8bd0f23](https://linux-hardware.org/?probe=b4d8bd0f23) | Apr 24, 2023 |
| Toshiba    | Satellite C45-A             | [3fd496c5f8](https://linux-hardware.org/?probe=3fd496c5f8) | Apr 16, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [426140ece2](https://linux-hardware.org/?probe=426140ece2) | Apr 12, 2023 |
| eMachines  | D725                        | [f3cdf26e60](https://linux-hardware.org/?probe=f3cdf26e60) | Apr 04, 2023 |
| HP         | 250 G7 Notebook PC          | [3995abb8b8](https://linux-hardware.org/?probe=3995abb8b8) | Apr 04, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| Lenovo     | IdeaPad Gaming 3 15ARH7 ... | [a6c0f30f2f](https://linux-hardware.org/?probe=a6c0f30f2f) | Apr 03, 2023 |
| ASUSTek    | T100TA                      | [5be9a0230e](https://linux-hardware.org/?probe=5be9a0230e) | Apr 01, 2023 |
| ASUSTek    | T100TA                      | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Acer       | Aspire ES1-531              | [aedba72f70](https://linux-hardware.org/?probe=aedba72f70) | Mar 31, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [0d7e6b4a80](https://linux-hardware.org/?probe=0d7e6b4a80) | Mar 12, 2023 |
| Lenovo     | ThinkPad T450 20BUA05K00    | [a496755d7a](https://linux-hardware.org/?probe=a496755d7a) | Mar 10, 2023 |
| HP         | Laptop 15-gw0xxx            | [e05606240c](https://linux-hardware.org/?probe=e05606240c) | Feb 28, 2023 |
| HP         | EliteBook 8540p             | [9f543932d2](https://linux-hardware.org/?probe=9f543932d2) | Feb 26, 2023 |
| HP         | Notebook                    | [b929a8ff3c](https://linux-hardware.org/?probe=b929a8ff3c) | Feb 24, 2023 |
| MSI        | Modern 15 A5M               | [f6c80ff7a9](https://linux-hardware.org/?probe=f6c80ff7a9) | Feb 20, 2023 |
| HP         | 14                          | [0244e880e1](https://linux-hardware.org/?probe=0244e880e1) | Feb 19, 2023 |
| HP         | Laptop 15-gw0xxx            | [4bcd17d5a6](https://linux-hardware.org/?probe=4bcd17d5a6) | Feb 17, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Dell       | Inspiron 13 5310            | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| Lenovo     | ThinkPad L15 Gen 1 20U3S... | [ad0b876d84](https://linux-hardware.org/?probe=ad0b876d84) | Feb 10, 2023 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [8d0a0a0422](https://linux-hardware.org/?probe=8d0a0a0422) | Feb 06, 2023 |
| HP         | Pavilion Laptop 15-cc1xx    | [d693442f27](https://linux-hardware.org/?probe=d693442f27) | Feb 03, 2023 |
| Lenovo     | IdeaPad 320-15IKB 80XL      | [5dbc5260b2](https://linux-hardware.org/?probe=5dbc5260b2) | Jan 29, 2023 |
| Lenovo     | IdeaPad 320-15IKB 80XL      | [7c0c804a3e](https://linux-hardware.org/?probe=7c0c804a3e) | Jan 29, 2023 |
| HP         | ProBook 640 G2              | [7b08eeb50c](https://linux-hardware.org/?probe=7b08eeb50c) | Jan 29, 2023 |
| HP         | Compaq Presario C700        | [d2ec58874c](https://linux-hardware.org/?probe=d2ec58874c) | Jan 21, 2023 |
| Lenovo     | IdeaPad 3 15IML05 81WR      | [07b3eb6453](https://linux-hardware.org/?probe=07b3eb6453) | Jan 20, 2023 |
| Toshiba    | Satellite C45-A             | [16f5bae11f](https://linux-hardware.org/?probe=16f5bae11f) | Jan 20, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| HP         | ProBook 655 G1              | [1e3f42b7d1](https://linux-hardware.org/?probe=1e3f42b7d1) | Jan 10, 2023 |
| Toshiba    | Satellite P300              | [d35d765c2f](https://linux-hardware.org/?probe=d35d765c2f) | Jan 09, 2023 |
| Acer       | Aspire VN7-571G             | [88e5718807](https://linux-hardware.org/?probe=88e5718807) | Jan 03, 2023 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [a30f96dea4](https://linux-hardware.org/?probe=a30f96dea4) | Dec 31, 2022 |
| HP         | Laptop 15-dy5xxx            | [d7daff3ed1](https://linux-hardware.org/?probe=d7daff3ed1) | Dec 27, 2022 |
| HP         | Compaq Mini CQ10-100        | [8b34b357bb](https://linux-hardware.org/?probe=8b34b357bb) | Dec 27, 2022 |
| HP         | 255 G8 Notebook PC          | [08800ce691](https://linux-hardware.org/?probe=08800ce691) | Dec 19, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [36a0b6f8d9](https://linux-hardware.org/?probe=36a0b6f8d9) | Dec 16, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [61dd034d23](https://linux-hardware.org/?probe=61dd034d23) | Dec 16, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [17cbc91488](https://linux-hardware.org/?probe=17cbc91488) | Dec 10, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [4b9eb9fcab](https://linux-hardware.org/?probe=4b9eb9fcab) | Dec 10, 2022 |
| Lenovo     | IdeaPad U400 099342G        | [9ecbde32ab](https://linux-hardware.org/?probe=9ecbde32ab) | Dec 06, 2022 |
| HUAWEI     | CREM-WXX9                   | [2436f4cf5e](https://linux-hardware.org/?probe=2436f4cf5e) | Nov 30, 2022 |
| HP         | 255 G7 Notebook PC          | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| HP         | 250 G7 Notebook PC          | [10b5bb5eab](https://linux-hardware.org/?probe=10b5bb5eab) | Nov 17, 2022 |
| HP         | 250 G7 Notebook PC          | [c765249482](https://linux-hardware.org/?probe=c765249482) | Nov 17, 2022 |
| Lenovo     | Legion 7 16ITHg6 82K6       | [eebc3537d1](https://linux-hardware.org/?probe=eebc3537d1) | Nov 09, 2022 |
| HP         | Pavilion Laptop 15-cw1xx... | [b4d22497e8](https://linux-hardware.org/?probe=b4d22497e8) | Nov 08, 2022 |
| HP         | Pavilion Laptop 15-cc1xx    | [b97ba1d3f0](https://linux-hardware.org/?probe=b97ba1d3f0) | Nov 07, 2022 |
| Lenovo     | Legion 7 16ITHg6 82K6       | [88a69a9a20](https://linux-hardware.org/?probe=88a69a9a20) | Nov 05, 2022 |
| Dell       | Latitude E5470              | [4de6b7bdb8](https://linux-hardware.org/?probe=4de6b7bdb8) | Nov 04, 2022 |
| Dell       | Latitude 5420               | [717e0e6d40](https://linux-hardware.org/?probe=717e0e6d40) | Nov 03, 2022 |
| Lenovo     | ThinkPad E15 Gen 2 20TES... | [209e99f964](https://linux-hardware.org/?probe=209e99f964) | Nov 02, 2022 |
| Lenovo     | ThinkPad E15 Gen 2 20TES... | [f12fc289fa](https://linux-hardware.org/?probe=f12fc289fa) | Nov 02, 2022 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [dca18dced0](https://linux-hardware.org/?probe=dca18dced0) | Oct 30, 2022 |
| Acer       | Aspire 5745                 | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| HP         | Pavilion Laptop 15-cc1xx    | [a977f9c3e9](https://linux-hardware.org/?probe=a977f9c3e9) | Oct 26, 2022 |
| ASUSTek    | X205TA                      | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| ADVANCE    | PS5077                      | [998e544711](https://linux-hardware.org/?probe=998e544711) | Oct 22, 2022 |
| ADVANCE    | PS5077                      | [97bfff0fc6](https://linux-hardware.org/?probe=97bfff0fc6) | Oct 22, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [07acd27a70](https://linux-hardware.org/?probe=07acd27a70) | Oct 21, 2022 |
| Dell       | Latitude E5470              | [11ad7cd084](https://linux-hardware.org/?probe=11ad7cd084) | Oct 20, 2022 |
| ASUSTek    | VivoBook 15_ASUS Laptop ... | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop M350... | [f15acdf9d4](https://linux-hardware.org/?probe=f15acdf9d4) | Oct 09, 2022 |
| HUAWEI     | BOHB-WAX9                   | [6fec6456bc](https://linux-hardware.org/?probe=6fec6456bc) | Oct 07, 2022 |
| HUAWEI     | BOHB-WAX9                   | [fb954f84b4](https://linux-hardware.org/?probe=fb954f84b4) | Oct 07, 2022 |
| HUAWEI     | BOHB-WAX9                   | [d56cf9868c](https://linux-hardware.org/?probe=d56cf9868c) | Oct 07, 2022 |
| Lenovo     | IdeaPad 320-15ISK 80XH      | [44afa82c4a](https://linux-hardware.org/?probe=44afa82c4a) | Sep 19, 2022 |
| ASUSTek    | S550CA                      | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| HP         | Laptop 15-ef1xxx            | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Lenovo     | V330-15IKB 81AX             | [0a91582802](https://linux-hardware.org/?probe=0a91582802) | Sep 14, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [2267f01dee](https://linux-hardware.org/?probe=2267f01dee) | Aug 27, 2022 |
| Lenovo     | G570 4334                   | [7bea18122c](https://linux-hardware.org/?probe=7bea18122c) | Aug 27, 2022 |
| HP         | 255 G7 Notebook PC          | [c001653a5a](https://linux-hardware.org/?probe=c001653a5a) | Aug 20, 2022 |
| Dell       | Vostro 3405                 | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Dell       | Latitude E6430              | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell       | Latitude E6430              | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| Lenovo     | ThinkPad T60 1953D9U        | [1c31cb6b44](https://linux-hardware.org/?probe=1c31cb6b44) | Jul 21, 2022 |
| Acer       | Aspire A515-51G             | [4414dd4c1b](https://linux-hardware.org/?probe=4414dd4c1b) | Jul 19, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [b511d2883b](https://linux-hardware.org/?probe=b511d2883b) | Jul 16, 2022 |
| Lenovo     | ThinkPad X140e 20BLA00C0... | [8c160ae192](https://linux-hardware.org/?probe=8c160ae192) | Jul 12, 2022 |
| Acer       | Aspire ES1-512              | [aa2ad87835](https://linux-hardware.org/?probe=aa2ad87835) | Jul 08, 2022 |
| Acer       | Aspire V3-471               | [75664ddf0f](https://linux-hardware.org/?probe=75664ddf0f) | Jul 07, 2022 |
| ASUSTek    | S550CA                      | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| MSI        | GL65 Leopard 10SEK          | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| Lenovo     | ThinkPad X140e 20BLA00C0... | [01fbfc98f8](https://linux-hardware.org/?probe=01fbfc98f8) | Jun 27, 2022 |
| Lenovo     | V15-IIL 82C5                | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| HP         | Laptop 15-ef1xxx            | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell       | Inspiron 15-3567            | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Dell       | Inspiron 15 7000 Gaming     | [fac01563a9](https://linux-hardware.org/?probe=fac01563a9) | Jun 24, 2022 |
| HP         | Laptop 15-ef1xxx            | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell       | Inspiron 5570               | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| ASUSTek    | S550CA                      | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Dell       | Inspiron 15-3567            | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| Lenovo     | V15-IIL 82C5                | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
| HUAWEI     | NBLB-WAX9N                  | [e24239a843](https://linux-hardware.org/?probe=e24239a843) | Jun 09, 2022 |
| ASUSTek    | S550CA                      | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| Dell       | Latitude E7450              | [29219339b2](https://linux-hardware.org/?probe=29219339b2) | Jun 05, 2022 |
| ASUSTek    | ROG Strix G513QY_G513QY     | [49c400d1f7](https://linux-hardware.org/?probe=49c400d1f7) | May 31, 2022 |
| HP         | Pavilion Laptop 15-cw1xx... | [be0f84abb3](https://linux-hardware.org/?probe=be0f84abb3) | May 30, 2022 |
| ASUSTek    | X555UQ                      | [c266f3d070](https://linux-hardware.org/?probe=c266f3d070) | May 30, 2022 |
| Lenovo     | ThinkPad P52 20MAS3X200     | [da2a67f904](https://linux-hardware.org/?probe=da2a67f904) | May 28, 2022 |
| Acer       | TravelMate 5320             | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| Lenovo     | ThinkPad P52 20MAS3X200     | [7f0fc0c72e](https://linux-hardware.org/?probe=7f0fc0c72e) | May 19, 2022 |
| ASUSTek    | ROG Strix G513QY_G513QY     | [2ee4916960](https://linux-hardware.org/?probe=2ee4916960) | May 18, 2022 |
| Dell       | Vostro 3405                 | [fcec5f1cdd](https://linux-hardware.org/?probe=fcec5f1cdd) | May 17, 2022 |
| ASUSTek    | ROG Strix G513QY_G513QY     | [21f3f7368f](https://linux-hardware.org/?probe=21f3f7368f) | May 17, 2022 |
| Dell       | Vostro 3405                 | [3c8e334d43](https://linux-hardware.org/?probe=3c8e334d43) | May 12, 2022 |
| Lenovo     | Legion 5 17ITH6H 82JM       | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| Lenovo     | ThinkPad T530 24296G9       | [934e13a24c](https://linux-hardware.org/?probe=934e13a24c) | May 08, 2022 |
| HP         | ZBook 15                    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| Compal     | QAQXX                       | [d3211e6bc6](https://linux-hardware.org/?probe=d3211e6bc6) | May 05, 2022 |
| HP         | Laptop 15-ef1xxx            | [d2eb5ae290](https://linux-hardware.org/?probe=d2eb5ae290) | May 05, 2022 |
| Lenovo     | V310-15ISK 80SY             | [1a791b0fd5](https://linux-hardware.org/?probe=1a791b0fd5) | May 04, 2022 |
| Lenovo     | V310-15ISK 80SY             | [3846d07c7f](https://linux-hardware.org/?probe=3846d07c7f) | May 04, 2022 |
| HP         | ENVY dv6                    | [23ad3290c2](https://linux-hardware.org/?probe=23ad3290c2) | May 03, 2022 |
| Lenovo     | ThinkPad L15 Gen 1 20U3S... | [74eec8c684](https://linux-hardware.org/?probe=74eec8c684) | May 01, 2022 |
| Lenovo     | V330-15IKB 81AX             | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Lenovo     | IdeaPad S145-15IWL 81MV     | [05db30a69b](https://linux-hardware.org/?probe=05db30a69b) | Apr 30, 2022 |
| Acer       | Aspire E5-571               | [ebdc8b1380](https://linux-hardware.org/?probe=ebdc8b1380) | Apr 30, 2022 |
| Acer       | Aspire A315-23              | [865091bbc1](https://linux-hardware.org/?probe=865091bbc1) | Apr 30, 2022 |
| Acer       | Aspire A315-23              | [5ee29c3982](https://linux-hardware.org/?probe=5ee29c3982) | Apr 30, 2022 |
| ASUSTek    | X556UR                      | [3f920954f7](https://linux-hardware.org/?probe=3f920954f7) | Apr 30, 2022 |
| HP         | Pavilion Sleekbook 15       | [0003f9342e](https://linux-hardware.org/?probe=0003f9342e) | Apr 30, 2022 |
| HP         | Laptop 14-dq1xxx            | [7c9e2f4d8f](https://linux-hardware.org/?probe=7c9e2f4d8f) | Apr 30, 2022 |
| HP         | Notebook                    | [94f0ce7610](https://linux-hardware.org/?probe=94f0ce7610) | Apr 26, 2022 |
| Dell       | Vostro 3405                 | [2d5bae0eeb](https://linux-hardware.org/?probe=2d5bae0eeb) | Apr 24, 2022 |
| HP         | Pavilion Laptop 15-cw1xx... | [a33d067e62](https://linux-hardware.org/?probe=a33d067e62) | Apr 18, 2022 |
| HP         | Compaq Mini CQ10-100        | [89c92e2cf7](https://linux-hardware.org/?probe=89c92e2cf7) | Apr 15, 2022 |
| Dell       | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| HP         | ZBook Firefly 15 G7 Mobi... | [0e9e99acae](https://linux-hardware.org/?probe=0e9e99acae) | Apr 13, 2022 |
| Lenovo     | ThinkPad X140e 20BLA00C0... | [9cad677222](https://linux-hardware.org/?probe=9cad677222) | Mar 24, 2022 |
| HP         | Stream Laptop 14-ax0XX      | [9b99145008](https://linux-hardware.org/?probe=9b99145008) | Mar 21, 2022 |
| HP         | Laptop 14-ck0xxx            | [92c7141f37](https://linux-hardware.org/?probe=92c7141f37) | Mar 12, 2022 |
| HP         | 340 G2                      | [c4f663b37b](https://linux-hardware.org/?probe=c4f663b37b) | Mar 04, 2022 |
| HP         | Pavilion Laptop 15-cd0xx    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Acer       | Aspire 4750                 | [b8f02b07fb](https://linux-hardware.org/?probe=b8f02b07fb) | Feb 18, 2022 |
| Acer       | Aspire 4750                 | [3269f565c4](https://linux-hardware.org/?probe=3269f565c4) | Feb 18, 2022 |
| HP         | 240 G7 Notebook PC          | [03f63a3789](https://linux-hardware.org/?probe=03f63a3789) | Feb 09, 2022 |
| efirstview | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Toshiba    | Satellite C645              | [d552c9b132](https://linux-hardware.org/?probe=d552c9b132) | Feb 04, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [b7cb93aff2](https://linux-hardware.org/?probe=b7cb93aff2) | Jan 25, 2022 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| Lenovo     | IdeaPad S340-15API 81NC     | [1f065ea4dd](https://linux-hardware.org/?probe=1f065ea4dd) | Jan 12, 2022 |
| Sony       | VGN-FW56M                   | [9fb3fa0f32](https://linux-hardware.org/?probe=9fb3fa0f32) | Jan 09, 2022 |
| Lenovo     | IdeaPad S540-14API 81NH     | [eb23bd590c](https://linux-hardware.org/?probe=eb23bd590c) | Jan 07, 2022 |
| Toshiba    | Satellite E205              | [92431da366](https://linux-hardware.org/?probe=92431da366) | Dec 24, 2021 |
| Lenovo     | G400 20235                  | [c2bb5d0010](https://linux-hardware.org/?probe=c2bb5d0010) | Dec 18, 2021 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [020b7460a1](https://linux-hardware.org/?probe=020b7460a1) | Dec 11, 2021 |
| HP         | Pavilion Gaming Laptop 1... | [fefa594281](https://linux-hardware.org/?probe=fefa594281) | Dec 10, 2021 |
| HP         | 250 G5 Notebook PC          | [3cd230924a](https://linux-hardware.org/?probe=3cd230924a) | Dec 04, 2021 |
| Lenovo     | ThinkPad X1 Carbon Gen 8... | [54f954491a](https://linux-hardware.org/?probe=54f954491a) | Nov 21, 2021 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [e085c7e42a](https://linux-hardware.org/?probe=e085c7e42a) | Nov 09, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [90fbcc38c3](https://linux-hardware.org/?probe=90fbcc38c3) | Nov 08, 2021 |
| Dell       | XPS 13 9360                 | [61db5bc9b5](https://linux-hardware.org/?probe=61db5bc9b5) | Nov 04, 2021 |
| Lenovo     | ThinkPad E15 Gen 2 20TES... | [df2d173d7c](https://linux-hardware.org/?probe=df2d173d7c) | Nov 01, 2021 |
| Lenovo     | V14-ARE 82DQ                | [8948989999](https://linux-hardware.org/?probe=8948989999) | Oct 31, 2021 |
| HP         | Laptop 15-db0xxx            | [f4d2f1104e](https://linux-hardware.org/?probe=f4d2f1104e) | Oct 28, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [849c03d63c](https://linux-hardware.org/?probe=849c03d63c) | Oct 21, 2021 |
| Lenovo     | IdeaPad 3 14ADA05 81W0      | [87d959803d](https://linux-hardware.org/?probe=87d959803d) | Oct 15, 2021 |
| Dell       | XPS 13 9360                 | [8bb0307157](https://linux-hardware.org/?probe=8bb0307157) | Sep 25, 2021 |
| HP         | Notebook                    | [36fd24364d](https://linux-hardware.org/?probe=36fd24364d) | Sep 24, 2021 |
| Advance    | AN-5431                     | [d48465a943](https://linux-hardware.org/?probe=d48465a943) | Sep 14, 2021 |
| HP         | Notebook                    | [2a564798fd](https://linux-hardware.org/?probe=2a564798fd) | Sep 11, 2021 |
| Lenovo     | ThinkPad T440 20B7A08500    | [b7e859020c](https://linux-hardware.org/?probe=b7e859020c) | Aug 26, 2021 |
| HP         | 450                         | [9f5d03c478](https://linux-hardware.org/?probe=9f5d03c478) | Aug 19, 2021 |
| Chuwi      | GemiBook Pro                | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| Lenovo     | IdeaPad 3 14ADA05 81W0      | [392df1ef2b](https://linux-hardware.org/?probe=392df1ef2b) | Aug 13, 2021 |
| ASUSTek    | X542UQ                      | [63d2276d55](https://linux-hardware.org/?probe=63d2276d55) | Aug 03, 2021 |
| Advance    | AN-5431                     | [06409d8637](https://linux-hardware.org/?probe=06409d8637) | Aug 01, 2021 |
| Lenovo     | ThinkPad T580 20LAS0XD00    | [36f1b3eb94](https://linux-hardware.org/?probe=36f1b3eb94) | Jul 31, 2021 |
| Dell       | Latitude E5540              | [44b8f3a781](https://linux-hardware.org/?probe=44b8f3a781) | Jul 23, 2021 |
| HP         | Pavilion dv6                | [3e69858907](https://linux-hardware.org/?probe=3e69858907) | Jul 09, 2021 |
| Lenovo     | ThinkPad L460 20FVA0G400    | [378021c178](https://linux-hardware.org/?probe=378021c178) | Jul 06, 2021 |
| ASUSTek    | ROG Strix G532LW_G532LWI    | [b36be47753](https://linux-hardware.org/?probe=b36be47753) | Jun 27, 2021 |
| HP         | Pavilion Notebook           | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Lenovo     | IdeaPad S540-14API 81NH     | [003f0d1c2a](https://linux-hardware.org/?probe=003f0d1c2a) | Jun 21, 2021 |
| ASUSTek    | ROG Strix G532LW_G532LWI    | [1344b72b26](https://linux-hardware.org/?probe=1344b72b26) | Jun 20, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [6670e1c145](https://linux-hardware.org/?probe=6670e1c145) | Jun 01, 2021 |
| ASUSTek    | VivoBook_ASUSLaptop X509... | [af8045a7b3](https://linux-hardware.org/?probe=af8045a7b3) | May 31, 2021 |
| ASUSTek    | X550LD                      | [89bed4ca0a](https://linux-hardware.org/?probe=89bed4ca0a) | May 28, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [ee9233be38](https://linux-hardware.org/?probe=ee9233be38) | May 26, 2021 |
| HP         | ProBook 450 G1              | [6d64546949](https://linux-hardware.org/?probe=6d64546949) | May 23, 2021 |
| HP         | ProBook 450 G1              | [1b52ac3979](https://linux-hardware.org/?probe=1b52ac3979) | May 23, 2021 |
| HP         | 240 G7                      | [9fff9c48ab](https://linux-hardware.org/?probe=9fff9c48ab) | May 16, 2021 |
| ASUSTek    | X550LC                      | [23a000c11b](https://linux-hardware.org/?probe=23a000c11b) | May 05, 2021 |
| ASUSTek    | X550LC                      | [d50b1f77d7](https://linux-hardware.org/?probe=d50b1f77d7) | May 05, 2021 |
| Toshiba    | Satellite L35               | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| HP         | 14                          | [9d65301476](https://linux-hardware.org/?probe=9d65301476) | Apr 09, 2021 |
| Lenovo     | IdeaPad S145-15IWL 81MV     | [14e58f968d](https://linux-hardware.org/?probe=14e58f968d) | Apr 07, 2021 |
| Toshiba    | Satellite C655D             | [1959880e8f](https://linux-hardware.org/?probe=1959880e8f) | Mar 28, 2021 |
| Dell       | Latitude E5470              | [6ade45ee37](https://linux-hardware.org/?probe=6ade45ee37) | Mar 21, 2021 |
| Lenovo     | V310-14ISK 80SX             | [529bb59872](https://linux-hardware.org/?probe=529bb59872) | Mar 12, 2021 |
| Toshiba    | Satellite A665              | [23143ad7ae](https://linux-hardware.org/?probe=23143ad7ae) | Mar 07, 2021 |
| Lenovo     | IdeaPad S145-14IWL 81MU     | [b2e0735680](https://linux-hardware.org/?probe=b2e0735680) | Feb 28, 2021 |
| MSI        | Prestige 14 A10SC           | [26f40cdcba](https://linux-hardware.org/?probe=26f40cdcba) | Feb 25, 2021 |
| HP         | ProBook 5330m               | [4a66a57a41](https://linux-hardware.org/?probe=4a66a57a41) | Feb 23, 2021 |
| Razer      | Blade                       | [58fcda1ac4](https://linux-hardware.org/?probe=58fcda1ac4) | Feb 18, 2021 |
| ASUSTek    | N56JN                       | [02008fdd48](https://linux-hardware.org/?probe=02008fdd48) | Jan 31, 2021 |
| Acer       | Aspire V5-471               | [3c0bc82dde](https://linux-hardware.org/?probe=3c0bc82dde) | Jan 16, 2021 |
| Lenovo     | V330-15IKB 81AX             | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| HP         | Pavilion dv7                | [7591424ea2](https://linux-hardware.org/?probe=7591424ea2) | Jan 06, 2021 |
| HP         | Pavilion dv7                | [d660b968a4](https://linux-hardware.org/?probe=d660b968a4) | Jan 06, 2021 |
| Dell       | Inspiron 14-3467            | [fe678ae6f5](https://linux-hardware.org/?probe=fe678ae6f5) | Jan 04, 2021 |
| Dell       | G5 5505                     | [156236cc47](https://linux-hardware.org/?probe=156236cc47) | Dec 30, 2020 |
| Dell       | Latitude E5470              | [f6a3bc1097](https://linux-hardware.org/?probe=f6a3bc1097) | Dec 28, 2020 |
| HP         | Pavilion Notebook           | [033a1ff3cd](https://linux-hardware.org/?probe=033a1ff3cd) | Dec 07, 2020 |
| ASUSTek    | N56JN                       | [776cb81132](https://linux-hardware.org/?probe=776cb81132) | Nov 25, 2020 |
| ASUSTek    | N56JN                       | [e14774acd5](https://linux-hardware.org/?probe=e14774acd5) | Nov 25, 2020 |
| HP         | 14                          | [918fb071c2](https://linux-hardware.org/?probe=918fb071c2) | Nov 22, 2020 |
| Dell       | Latitude 3440               | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP         | ProBook 440 G5              | [07ac3c5495](https://linux-hardware.org/?probe=07ac3c5495) | Oct 07, 2020 |
| HP         | ProBook 440 G5              | [123eb500e2](https://linux-hardware.org/?probe=123eb500e2) | Oct 06, 2020 |
| Lenovo     | IdeaPad S540-14API 81NH     | [735aea26c5](https://linux-hardware.org/?probe=735aea26c5) | Sep 28, 2020 |
| HP         | 240 G7                      | [2507cc1bc7](https://linux-hardware.org/?probe=2507cc1bc7) | Sep 28, 2020 |
| Lenovo     | ThinkPad T470 20HES0JQ00    | [4235f1fc42](https://linux-hardware.org/?probe=4235f1fc42) | Sep 20, 2020 |
| Acer       | Nitro AN515-54              | [60efe004ff](https://linux-hardware.org/?probe=60efe004ff) | Sep 19, 2020 |
| Lenovo     | Legion Y540-15IRH 81SX      | [123ba2dd21](https://linux-hardware.org/?probe=123ba2dd21) | Sep 15, 2020 |
| Lenovo     | Legion Y540-15IRH-PG0 81... | [e193207a8f](https://linux-hardware.org/?probe=e193207a8f) | Sep 14, 2020 |
| Lenovo     | IdeaPad S540-14API 81NH     | [d043bf1b42](https://linux-hardware.org/?probe=d043bf1b42) | Sep 06, 2020 |
| Lenovo     | ThinkPad T430 2349LRS       | [d886cd5c31](https://linux-hardware.org/?probe=d886cd5c31) | Sep 05, 2020 |
| Lenovo     | ThinkPad T430 2349LRS       | [38284d9848](https://linux-hardware.org/?probe=38284d9848) | Sep 05, 2020 |
| Lenovo     | V310-15ISK 80SY             | [fc06b19016](https://linux-hardware.org/?probe=fc06b19016) | Sep 05, 2020 |
| Lenovo     | IdeaPad S540-14API 81NH     | [395b3e9836](https://linux-hardware.org/?probe=395b3e9836) | Sep 05, 2020 |
| Lenovo     | ThinkPad T430s 23539KU      | [2f700d4f41](https://linux-hardware.org/?probe=2f700d4f41) | Sep 03, 2020 |
| Lenovo     | G475 20080                  | [c97ad59308](https://linux-hardware.org/?probe=c97ad59308) | Aug 26, 2020 |
| Acer       | Aspire A515-52G             | [86a890eb18](https://linux-hardware.org/?probe=86a890eb18) | Aug 23, 2020 |
| Acer       | Aspire A515-52G             | [5034bf6bc3](https://linux-hardware.org/?probe=5034bf6bc3) | Aug 23, 2020 |
| Toshiba    | Satellite C845              | [7e218cb089](https://linux-hardware.org/?probe=7e218cb089) | Aug 22, 2020 |
| ASUSTek    | VivoBook_ASUS Laptop X50... | [26fe839699](https://linux-hardware.org/?probe=26fe839699) | Aug 14, 2020 |
| ASUSTek    | VivoBook_ASUS Laptop X50... | [55d2d92173](https://linux-hardware.org/?probe=55d2d92173) | Aug 14, 2020 |
| Lenovo     | ThinkPad P50 20EQA09900     | [4360f8c6a6](https://linux-hardware.org/?probe=4360f8c6a6) | Aug 12, 2020 |
| Lenovo     | ThinkPad P50 20EQA09900     | [76f4cf6487](https://linux-hardware.org/?probe=76f4cf6487) | Aug 12, 2020 |
| Toshiba    | Satellite L45-B             | [ce51a04f5d](https://linux-hardware.org/?probe=ce51a04f5d) | Aug 01, 2020 |
| Lenovo     | ThinkPad T60 1953D9U        | [45c01e0aca](https://linux-hardware.org/?probe=45c01e0aca) | Jul 30, 2020 |
| HP         | 245 G3                      | [044b206096](https://linux-hardware.org/?probe=044b206096) | Jul 26, 2020 |
| Lenovo     | G480 20149                  | [7fdfad1fc4](https://linux-hardware.org/?probe=7fdfad1fc4) | Jul 11, 2020 |
| ASUSTek    | VivoBook 15_ASUS Laptop ... | [f0ed82358a](https://linux-hardware.org/?probe=f0ed82358a) | Jul 05, 2020 |
| Lenovo     | G480 20149                  | [c9d75e29d3](https://linux-hardware.org/?probe=c9d75e29d3) | Jun 30, 2020 |
| HP         | ProBook 645 G4              | [2fb2b6ad63](https://linux-hardware.org/?probe=2fb2b6ad63) | Jun 22, 2020 |
| HP         | Pavilion Laptop 15-cw1xx... | [844f7b115e](https://linux-hardware.org/?probe=844f7b115e) | Jun 21, 2020 |
| HP         | ProBook 645 G4              | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| ASUSTek    | X540LA                      | [333139a886](https://linux-hardware.org/?probe=333139a886) | Jun 17, 2020 |
| HP         | ProBook 645 G4              | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| Toshiba    | Satellite L855              | [adbdc1e191](https://linux-hardware.org/?probe=adbdc1e191) | Jun 13, 2020 |
| ASUSTek    | VivoBook 15_ASUS Laptop ... | [97237c08ac](https://linux-hardware.org/?probe=97237c08ac) | Jun 11, 2020 |
| Apple      | MacBookPro9,2               | [371c5ccd5a](https://linux-hardware.org/?probe=371c5ccd5a) | May 31, 2020 |
| HP         | ENVY 15                     | [9075368552](https://linux-hardware.org/?probe=9075368552) | May 29, 2020 |
| Lenovo     | G50-70 20351                | [fb33cd7cef](https://linux-hardware.org/?probe=fb33cd7cef) | May 26, 2020 |
| HP         | EliteBook 840 G6            | [07829f089a](https://linux-hardware.org/?probe=07829f089a) | May 24, 2020 |
| HP         | ENVY 15                     | [afcc7af453](https://linux-hardware.org/?probe=afcc7af453) | May 23, 2020 |
| Unknown    | Unknown                     | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Unknown    | Unknown                     | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Dell       | Precision M4600             | [7060267281](https://linux-hardware.org/?probe=7060267281) | May 08, 2020 |
| HP         | Pavilion Sleekbook 14 PC    | [c513103ac9](https://linux-hardware.org/?probe=c513103ac9) | May 05, 2020 |
| HP         | 450                         | [22b90eb634](https://linux-hardware.org/?probe=22b90eb634) | May 02, 2020 |
| HP         | 450                         | [0da93b6fce](https://linux-hardware.org/?probe=0da93b6fce) | May 02, 2020 |
| Dell       | System XPS L502X            | [939683d725](https://linux-hardware.org/?probe=939683d725) | Apr 27, 2020 |
| Dell       | System XPS L502X            | [c893f3f105](https://linux-hardware.org/?probe=c893f3f105) | Apr 24, 2020 |
| HP         | Pavilion Laptop 15-cs0xx... | [97261529e7](https://linux-hardware.org/?probe=97261529e7) | Apr 21, 2020 |
| HP         | Pavilion Laptop 15-cs0xx... | [babdfebf40](https://linux-hardware.org/?probe=babdfebf40) | Apr 17, 2020 |
| Lenovo     | Yoga 2 11 20332             | [bbd3b573e1](https://linux-hardware.org/?probe=bbd3b573e1) | Apr 05, 2020 |
| Lenovo     | Yoga 2 11 20332             | [51c0fd8c5c](https://linux-hardware.org/?probe=51c0fd8c5c) | Apr 05, 2020 |
| Toshiba    | NB505                       | [934ebfe06b](https://linux-hardware.org/?probe=934ebfe06b) | Apr 05, 2020 |
| Samsung    | 300E5EV/300E4EV/270E5EV/... | [b112c2d6c6](https://linux-hardware.org/?probe=b112c2d6c6) | Mar 30, 2020 |
| Samsung    | 300E5EV/300E4EV/270E5EV/... | [7dee8ed61e](https://linux-hardware.org/?probe=7dee8ed61e) | Mar 26, 2020 |
| Samsung    | 300E5EV/300E4EV/270E5EV/... | [e274c73209](https://linux-hardware.org/?probe=e274c73209) | Mar 23, 2020 |
| Sony       | SVF15A17CLB                 | [6f9e42f276](https://linux-hardware.org/?probe=6f9e42f276) | Mar 22, 2020 |
| Lenovo     | V310-15ISK 80SY             | [88cf0450ac](https://linux-hardware.org/?probe=88cf0450ac) | Mar 15, 2020 |
| Dell       | Inspiron 5567               | [e598212cee](https://linux-hardware.org/?probe=e598212cee) | Feb 28, 2020 |
| HP         | Pavilion Gaming Laptop 1... | [2eebfcd5e9](https://linux-hardware.org/?probe=2eebfcd5e9) | Feb 27, 2020 |
| HP         | Pavilion Gaming Laptop 1... | [1335c3693b](https://linux-hardware.org/?probe=1335c3693b) | Feb 27, 2020 |
| Lenovo     | IdeaPad 330-15ARR 81D2      | [9344a74aa9](https://linux-hardware.org/?probe=9344a74aa9) | Feb 26, 2020 |
| Lenovo     | IdeaPad 330-15ARR 81D2      | [b253180703](https://linux-hardware.org/?probe=b253180703) | Feb 20, 2020 |
| Lenovo     | IdeaPad 330-15ARR 81D2      | [ad43873fae](https://linux-hardware.org/?probe=ad43873fae) | Feb 19, 2020 |
| Toshiba    | QOSMIO X775                 | [6abcb623e3](https://linux-hardware.org/?probe=6abcb623e3) | Feb 02, 2020 |
| Toshiba    | QOSMIO X775                 | [a2cf60ec44](https://linux-hardware.org/?probe=a2cf60ec44) | Feb 02, 2020 |
| Acer       | Aspire ES1-572              | [8bc74bd7fb](https://linux-hardware.org/?probe=8bc74bd7fb) | Dec 06, 2019 |
| Unknown    | Unknown                     | [cd4af41624](https://linux-hardware.org/?probe=cd4af41624) | Nov 30, 2019 |
| HP         | Pavilion g4                 | [cb1f2e06e7](https://linux-hardware.org/?probe=cb1f2e06e7) | Nov 28, 2019 |
| Dell       | Latitude 5580               | [7abf5fbce7](https://linux-hardware.org/?probe=7abf5fbce7) | Nov 21, 2019 |
| Dell       | Latitude 5580               | [521a1d30b6](https://linux-hardware.org/?probe=521a1d30b6) | Nov 21, 2019 |
| Lenovo     | Y70-70 Touch 80DU           | [dfa431bef9](https://linux-hardware.org/?probe=dfa431bef9) | Nov 13, 2019 |
| Toshiba    | Satellite C55-B             | [ef97116a29](https://linux-hardware.org/?probe=ef97116a29) | Nov 12, 2019 |
| Lenovo     | V330-15IKB 81AX             | [d0612d575f](https://linux-hardware.org/?probe=d0612d575f) | Nov 04, 2019 |
| Dell       | Inspiron 3443               | [daa04d519c](https://linux-hardware.org/?probe=daa04d519c) | Oct 15, 2019 |
| Sony       | VPCEC2JFX                   | [ad30a52539](https://linux-hardware.org/?probe=ad30a52539) | Oct 03, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [e486c2c05f](https://linux-hardware.org/?probe=e486c2c05f) | Sep 12, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [b09160e7cf](https://linux-hardware.org/?probe=b09160e7cf) | Sep 10, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [333fbc5a3b](https://linux-hardware.org/?probe=333fbc5a3b) | Aug 16, 2019 |
| Sony       | VPCEC2JFX                   | [f28ba85f16](https://linux-hardware.org/?probe=f28ba85f16) | Aug 04, 2019 |
| Acer       | Aspire ES1-572              | [432212e4c9](https://linux-hardware.org/?probe=432212e4c9) | Jul 31, 2019 |
| Acer       | Aspire ES1-572              | [8783b0d26c](https://linux-hardware.org/?probe=8783b0d26c) | Jul 31, 2019 |
| HP         | ProBook 440 G4              | [b0ae12ca81](https://linux-hardware.org/?probe=b0ae12ca81) | Jun 27, 2019 |
| Toshiba    | Satellite P755              | [8eaca3c3df](https://linux-hardware.org/?probe=8eaca3c3df) | Jun 13, 2019 |
| HP         | ProBook 645 G4              | [f2f88aaa9d](https://linux-hardware.org/?probe=f2f88aaa9d) | May 24, 2019 |
| HP         | ProBook 645 G4              | [049bd45822](https://linux-hardware.org/?probe=049bd45822) | May 24, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [cdf8203e8f](https://linux-hardware.org/?probe=cdf8203e8f) | Apr 24, 2019 |
| Lenovo     | B50-80 80EW                 | [275d0c887d](https://linux-hardware.org/?probe=275d0c887d) | Dec 28, 2018 |
| Lenovo     | B50-80 80EW                 | [603e6d3da4](https://linux-hardware.org/?probe=603e6d3da4) | Dec 28, 2018 |
| HP         | 1000                        | [9bf9fc957a](https://linux-hardware.org/?probe=9bf9fc957a) | Sep 04, 2018 |
| HP         | 1000                        | [684f6b1db8](https://linux-hardware.org/?probe=684f6b1db8) | Jan 30, 2018 |
| Sony       | VGN-FW170J                  | [2ac505bc7b](https://linux-hardware.org/?probe=2ac505bc7b) | Jan 04, 2018 |
| HP         | 1000                        | [0e00b75fea](https://linux-hardware.org/?probe=0e00b75fea) | Dec 19, 2017 |
| Sony       | VGN-FW170J                  | [d2b4cdb291](https://linux-hardware.org/?probe=d2b4cdb291) | Nov 21, 2017 |
| Acer       | Aspire S3                   | [db53fb01bd](https://linux-hardware.org/?probe=db53fb01bd) | May 26, 2017 |
| Acer       | Aspire S3                   | [a3cfad5de1](https://linux-hardware.org/?probe=a3cfad5de1) | May 26, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Peru/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 32        | 7.69%   |
| Ubuntu 22.04                 | 18        | 4.33%   |
| Arch Rolling                 | 18        | 4.33%   |
| OpenMandriva 4.3             | 11        | 2.64%   |
| Ubuntu 24.04                 | 9         | 2.16%   |
| Ubuntu 18.04                 | 9         | 2.16%   |
| Linux Mint 21.1              | 9         | 2.16%   |
| Fedora 40                    | 9         | 2.16%   |
| Fedora 38                    | 8         | 1.92%   |
| Pop!_OS 22.04                | 7         | 1.68%   |
| OpenMandriva 23.03           | 7         | 1.68%   |
| Zorin 15                     | 6         | 1.44%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 1.44%   |
| Manjaro                      | 6         | 1.44%   |
| Linux Mint 20.3              | 6         | 1.44%   |
| EndeavourOS Rolling          | 6         | 1.44%   |
| Ubuntu 19.10                 | 5         | 1.2%    |
| OpenMandriva 25.90           | 5         | 1.2%    |
| OpenMandriva 24.12           | 5         | 1.2%    |
| Fedora 39                    | 5         | 1.2%    |
| Fedora 37                    | 5         | 1.2%    |
| Debian 12                    | 5         | 1.2%    |
| ArcoLinux Rolling            | 5         | 1.2%    |
| Arch                         | 5         | 1.2%    |
| Zorin 17                     | 4         | 0.96%   |
| Xubuntu 20.04                | 4         | 0.96%   |
| Ubuntu 21.04                 | 4         | 0.96%   |
| Pop!_OS 21.10                | 4         | 0.96%   |
| OpenMandriva 23.08           | 4         | 0.96%   |
| OpenMandriva 23.01           | 4         | 0.96%   |
| Linux Mint 22.1              | 4         | 0.96%   |
| Debian 11                    | 4         | 0.96%   |
| Zorin 18                     | 3         | 0.72%   |
| Zorin 16                     | 3         | 0.72%   |
| Ubuntu 19.04                 | 3         | 0.72%   |
| Pop!_OS 20.10                | 3         | 0.72%   |
| OpenMandriva 6.0             | 3         | 0.72%   |
| OpenMandriva 5.0             | 3         | 0.72%   |
| OpenMandriva 4.2             | 3         | 0.72%   |
| Manjaro 20.1                 | 3         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 82        | 20.5%   |
| OpenMandriva  | 49        | 12.25%  |
| Fedora        | 42        | 10.5%   |
| Linux Mint    | 30        | 7.5%    |
| Arch          | 24        | 6%      |
| Pop!_OS       | 18        | 4.5%    |
| Debian        | 17        | 4.25%   |
| Zorin         | 16        | 4%      |
| Manjaro       | 15        | 3.75%   |
| ROSA          | 13        | 3.25%   |
| openSUSE      | 7         | 1.75%   |
| Kubuntu       | 7         | 1.75%   |
| Lubuntu       | 6         | 1.5%    |
| EndeavourOS   | 6         | 1.5%    |
| KDE neon      | 5         | 1.25%   |
| Elementary    | 5         | 1.25%   |
| ArcoLinux     | 5         | 1.25%   |
| Xubuntu       | 4         | 1%      |
| Ubuntu MATE   | 4         | 1%      |
| SteamOS       | 4         | 1%      |
| Parrot        | 4         | 1%      |
| Kali          | 4         | 1%      |
| Mageia        | 3         | 0.75%   |
| LMDE          | 3         | 0.75%   |
| Endless       | 3         | 0.75%   |
| Ubuntu Budgie | 2         | 0.5%    |
| MX            | 2         | 0.5%    |
| Garuda Linux  | 2         | 0.5%    |
| CentOS        | 2         | 0.5%    |
| Bazzite       | 2         | 0.5%    |
| Void Linux    | 1         | 0.25%   |
| Ubuntu Unity  | 1         | 0.25%   |
| Ubuntu Studio | 1         | 0.25%   |
| Secureblue    | 1         | 0.25%   |
| Peppermint    | 1         | 0.25%   |
| Oracle Linux  | 1         | 0.25%   |
| NixOS         | 1         | 0.25%   |
| Linux Lite    | 1         | 0.25%   |
| Laxer OS      | 1         | 0.25%   |
| Clear Linux   | 1         | 0.25%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 11        | 2.44%   |
| 6.14.2-desktop-3omv2590  | 8         | 1.78%   |
| 6.2.6-desktop-1omv2390   | 6         | 1.33%   |
| 5.13.0-40-generic        | 5         | 1.11%   |
| 6.6.2-desktop-1omv2390   | 4         | 0.89%   |
| 6.12.1-desktop-1omv2490  | 4         | 0.89%   |
| 5.4.0-42-generic         | 4         | 0.89%   |
| 6.6.52-desktop-1.mga9    | 3         | 0.67%   |
| 6.3.5-desktop-3omv2390   | 3         | 0.67%   |
| 6.3.5-200.fc38.x86_64    | 3         | 0.67%   |
| 5.4.0-26-generic         | 3         | 0.67%   |
| 5.3.0-40-generic         | 3         | 0.67%   |
| 5.15.0-76-generic        | 3         | 0.67%   |
| 5.15.0-71-generic        | 3         | 0.67%   |
| 5.13.0-51-generic        | 3         | 0.67%   |
| 5.11.0-25-generic        | 3         | 0.67%   |
| 5.10.0-13-amd64          | 3         | 0.67%   |
| 6.8.0-57-generic         | 2         | 0.44%   |
| 6.8.0-41-generic         | 2         | 0.44%   |
| 6.8.0-31-generic         | 2         | 0.44%   |
| 6.5.0-18-generic         | 2         | 0.44%   |
| 6.5.0-15-generic         | 2         | 0.44%   |
| 6.4.8-desktop-2omv2390   | 2         | 0.44%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.44%   |
| 6.3.6-arch1-1            | 2         | 0.44%   |
| 6.2.0-36-generic         | 2         | 0.44%   |
| 6.2.0-24-generic         | 2         | 0.44%   |
| 6.14.0-35-generic        | 2         | 0.44%   |
| 6.14.0-27-generic        | 2         | 0.44%   |
| 6.12.48+deb13-amd64      | 2         | 0.44%   |
| 6.12.10-76061203-generic | 2         | 0.44%   |
| 6.11.7-300.fc41.x86_64   | 2         | 0.44%   |
| 6.11.3-200.fc40.x86_64   | 2         | 0.44%   |
| 6.11.0-26-generic        | 2         | 0.44%   |
| 6.1.4-desktop-1omv2301   | 2         | 0.44%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.44%   |
| 6.1.0-30-amd64           | 2         | 0.44%   |
| 5.8.0-44-generic         | 2         | 0.44%   |
| 5.4.0-7642-generic       | 2         | 0.44%   |
| 5.4.0-66-generic         | 2         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 39        | 8.9%    |
| 5.15.0  | 27        | 6.16%   |
| 6.8.0   | 18        | 4.11%   |
| 6.5.0   | 14        | 3.2%    |
| 5.13.0  | 14        | 3.2%    |
| 5.11.0  | 14        | 3.2%    |
| 5.3.0   | 12        | 2.74%   |
| 6.2.0   | 11        | 2.51%   |
| 5.16.7  | 11        | 2.51%   |
| 6.14.2  | 8         | 1.83%   |
| 6.2.6   | 7         | 1.6%    |
| 5.8.0   | 7         | 1.6%    |
| 5.10.0  | 7         | 1.6%    |
| 5.0.0   | 7         | 1.6%    |
| 4.15.0  | 7         | 1.6%    |
| 6.3.5   | 6         | 1.37%   |
| 6.14.0  | 6         | 1.37%   |
| 4.18.0  | 6         | 1.37%   |
| 6.1.0   | 5         | 1.14%   |
| 5.19.0  | 5         | 1.14%   |
| 6.6.2   | 4         | 0.91%   |
| 6.3.6   | 4         | 0.91%   |
| 6.12.1  | 4         | 0.91%   |
| 6.6.6   | 3         | 0.68%   |
| 6.6.52  | 3         | 0.68%   |
| 6.4.11  | 3         | 0.68%   |
| 6.11.0  | 3         | 0.68%   |
| 6.0.0   | 3         | 0.68%   |
| 5.17.5  | 3         | 0.68%   |
| 4.9.60  | 3         | 0.68%   |
| 6.9.7   | 2         | 0.46%   |
| 6.9.3   | 2         | 0.46%   |
| 6.8.7   | 2         | 0.46%   |
| 6.5.6   | 2         | 0.46%   |
| 6.4.8   | 2         | 0.46%   |
| 6.16.8  | 2         | 0.46%   |
| 6.13.7  | 2         | 0.46%   |
| 6.12.48 | 2         | 0.46%   |
| 6.12.10 | 2         | 0.46%   |
| 6.11.7  | 2         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 42        | 9.77%   |
| 5.15    | 40        | 9.3%    |
| 6.2     | 24        | 5.58%   |
| 6.8     | 21        | 4.88%   |
| 6.5     | 21        | 4.88%   |
| 6.1     | 20        | 4.65%   |
| 6.14    | 18        | 4.19%   |
| 6.6     | 16        | 3.72%   |
| 5.13    | 15        | 3.49%   |
| 5.11    | 15        | 3.49%   |
| 5.10    | 15        | 3.49%   |
| 5.16    | 14        | 3.26%   |
| 6.4     | 12        | 2.79%   |
| 6.3     | 12        | 2.79%   |
| 6.12    | 12        | 2.79%   |
| 6.0     | 12        | 2.79%   |
| 5.3     | 12        | 2.79%   |
| 6.11    | 11        | 2.56%   |
| 5.8     | 10        | 2.33%   |
| 6.10    | 8         | 1.86%   |
| 5.19    | 7         | 1.63%   |
| 5.17    | 7         | 1.63%   |
| 5.0     | 7         | 1.63%   |
| 4.15    | 7         | 1.63%   |
| 6.9     | 6         | 1.4%    |
| 4.18    | 6         | 1.4%    |
| 6.16    | 4         | 0.93%   |
| 6.15    | 4         | 0.93%   |
| 5.18    | 4         | 0.93%   |
| 5.14    | 4         | 0.93%   |
| 5.12    | 4         | 0.93%   |
| 4.9     | 4         | 0.93%   |
| 6.13    | 3         | 0.7%    |
| 6.17    | 2         | 0.47%   |
| 5.9     | 2         | 0.47%   |
| 5.7     | 2         | 0.47%   |
| 5.6     | 2         | 0.47%   |
| 4.19    | 2         | 0.47%   |
| 6.7     | 1         | 0.23%   |
| 5.1     | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 378       | 97.67%  |
| i686   | 9         | 2.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 171       | 42.33%  |
| KDE5            | 75        | 18.56%  |
| XFCE            | 33        | 8.17%   |
| X-Cinnamon      | 27        | 6.68%   |
| KDE6            | 22        | 5.45%   |
| Unknown         | 18        | 4.46%   |
| MATE            | 12        | 2.97%   |
| LXQt            | 8         | 1.98%   |
| KDE             | 7         | 1.73%   |
| Pantheon        | 5         | 1.24%   |
| i3              | 5         | 1.24%   |
| KDE4            | 4         | 0.99%   |
| Budgie          | 4         | 0.99%   |
| sway            | 2         | 0.5%    |
| LXDE            | 2         | 0.5%    |
| Hyprland        | 2         | 0.5%    |
| fluxbox         | 2         | 0.5%    |
| Unity           | 1         | 0.25%   |
| spectrwm        | 1         | 0.25%   |
| GNOME Flashback | 1         | 0.25%   |
| Deepin          | 1         | 0.25%   |
| COSMIC          | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 255       | 63.75%  |
| Wayland | 126       | 31.5%   |
| Unknown | 15        | 3.75%   |
| Tty     | 4         | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 165       | 41.46%  |
| SDDM    | 80        | 20.1%   |
| GDM     | 54        | 13.57%  |
| LightDM | 49        | 12.31%  |
| GDM3    | 40        | 10.05%  |
| KDM     | 4         | 1.01%   |
| TDM     | 2         | 0.5%    |
| XDM     | 1         | 0.25%   |
| LY-DM   | 1         | 0.25%   |
| Ly      | 1         | 0.25%   |
| LXDM    | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_PE   | 188       | 46.88%  |
| en_US   | 111       | 27.68%  |
| es_ES   | 45        | 11.22%  |
| Unknown | 16        | 3.99%   |
| es_MX   | 14        | 3.49%   |
| C       | 7         | 1.75%   |
| en_GB   | 3         | 0.75%   |
| it_IT   | 2         | 0.5%    |
| fr_FR   | 2         | 0.5%    |
| es_AR   | 2         | 0.5%    |
| en_CA   | 2         | 0.5%    |
| ca_ES   | 2         | 0.5%    |
| POSIX   | 1         | 0.25%   |
| es_VE   | 1         | 0.25%   |
| es_CO   | 1         | 0.25%   |
| en_NZ   | 1         | 0.25%   |
| en_DK   | 1         | 0.25%   |
| de_DE   | 1         | 0.25%   |
| Default | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 223       | 56.6%   |
| BIOS | 171       | 43.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 268       | 67.17%  |
| Btrfs   | 61        | 15.29%  |
| Overlay | 36        | 9.02%   |
| Tmpfs   | 18        | 4.51%   |
| Xfs     | 8         | 2.01%   |
| Unknown | 7         | 1.75%   |
| Ext3    | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 184       | 46.7%   |
| Unknown | 174       | 44.16%  |
| MBR     | 36        | 9.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 346       | 87.59%  |
| Yes       | 49        | 12.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 241       | 61.17%  |
| Yes       | 153       | 38.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 97        | 25.13%  |
| Hewlett-Packard     | 97        | 25.13%  |
| ASUSTek Computer    | 55        | 14.25%  |
| Dell                | 42        | 10.88%  |
| Toshiba             | 23        | 5.96%   |
| Acer                | 23        | 5.96%   |
| Sony                | 9         | 2.33%   |
| HUAWEI              | 6         | 1.55%   |
| Chuwi               | 6         | 1.55%   |
| Apple               | 6         | 1.55%   |
| MSI                 | 5         | 1.3%    |
| Valve               | 2         | 0.52%   |
| Samsung Electronics | 2         | 0.52%   |
| Google              | 2         | 0.52%   |
| ADVANCE             | 2         | 0.52%   |
| System76            | 1         | 0.26%   |
| Razer               | 1         | 0.26%   |
| Gigabyte Technology | 1         | 0.26%   |
| Gateway             | 1         | 0.26%   |
| eMachines           | 1         | 0.26%   |
| efirstview          | 1         | 0.26%   |
| Compal              | 1         | 0.26%   |
| ASRock              | 1         | 0.26%   |
| Unknown             | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chuwi GemiBook Pro                       | 6         | 1.55%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA | 6         | 1.55%   |
| HP Pavilion Laptop 15-cw1xxx             | 5         | 1.3%    |
| HP Pavilion g4                           | 5         | 1.3%    |
| Lenovo V330-15IKB 81AX                   | 4         | 1.04%   |
| Lenovo V310-15ISK 80SY                   | 4         | 1.04%   |
| HP 14                                    | 4         | 1.04%   |
| Toshiba Satellite L45-B                  | 3         | 0.78%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 3         | 0.78%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 3         | 0.78%   |
| HUAWEI NBLB-WAX9N                        | 3         | 0.78%   |
| HP Pavilion Gaming Laptop 15-dk1xxx      | 3         | 0.78%   |
| HP Laptop 15-da0xxx                      | 3         | 0.78%   |
| Dell XPS 13 9360                         | 3         | 0.78%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA   | 3         | 0.78%   |
| Apple MacBookPro9,2                      | 3         | 0.78%   |
| Toshiba Satellite C45-A                  | 2         | 0.52%   |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 2         | 0.52%   |
| Lenovo IdeaPad S540-14API 81NH           | 2         | 0.52%   |
| Lenovo IdeaPad S145-15IWL 81MV           | 2         | 0.52%   |
| Lenovo IdeaPad 330S-14IKB 81F4           | 2         | 0.52%   |
| Lenovo IdeaPad 3 15IIL05 81WE            | 2         | 0.52%   |
| Lenovo G400 20235                        | 2         | 0.52%   |
| HP ProBook 645 G4                        | 2         | 0.52%   |
| HP Pavilion dv4                          | 2         | 0.52%   |
| HP Notebook                              | 2         | 0.52%   |
| HP Laptop 15-ef1xxx                      | 2         | 0.52%   |
| HP Laptop 14-ck0xxx                      | 2         | 0.52%   |
| HP Compaq Presario C700                  | 2         | 0.52%   |
| HP 450                                   | 2         | 0.52%   |
| HP 250 G7 Notebook PC                    | 2         | 0.52%   |
| HP 250 G5 Notebook PC                    | 2         | 0.52%   |
| HP 240 G7 Notebook PC                    | 2         | 0.52%   |
| HP 1000                                  | 2         | 0.52%   |
| Dell Latitude E7450                      | 2         | 0.52%   |
| Dell Latitude E5470                      | 2         | 0.52%   |
| Dell Latitude 5490                       | 2         | 0.52%   |
| Dell Inspiron 5567                       | 2         | 0.52%   |
| Dell Inspiron 14-3467                    | 2         | 0.52%   |
| Dell G5 5505                             | 2         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 35        | 9.07%   |
| HP Pavilion       | 26        | 6.74%   |
| Lenovo ThinkPad   | 24        | 6.22%   |
| ASUS VivoBook     | 23        | 5.96%   |
| Toshiba Satellite | 20        | 5.18%   |
| HP Laptop         | 20        | 5.18%   |
| Acer Aspire       | 19        | 4.92%   |
| Dell Latitude     | 16        | 4.15%   |
| Dell Inspiron     | 15        | 3.89%   |
| HP ProBook        | 12        | 3.11%   |
| Lenovo Legion     | 7         | 1.81%   |
| ASUS ROG          | 7         | 1.81%   |
| ASUS ASUS         | 7         | 1.81%   |
| Chuwi GemiBook    | 6         | 1.55%   |
| Lenovo V330-15IKB | 4         | 1.04%   |
| Lenovo V310-15ISK | 4         | 1.04%   |
| HP Compaq         | 4         | 1.04%   |
| HP 250            | 4         | 1.04%   |
| HP 14             | 4         | 1.04%   |
| Dell XPS          | 4         | 1.04%   |
| HUAWEI NBLB-WAX9N | 3         | 0.78%   |
| HP ZBook          | 3         | 0.78%   |
| HP OMEN           | 3         | 0.78%   |
| HP EliteBook      | 3         | 0.78%   |
| HP 240            | 3         | 0.78%   |
| Apple MacBookPro9 | 3         | 0.78%   |
| Toshiba QOSMIO    | 2         | 0.52%   |
| Lenovo V15        | 2         | 0.52%   |
| Lenovo G400       | 2         | 0.52%   |
| HP Notebook       | 2         | 0.52%   |
| HP ENVY           | 2         | 0.52%   |
| HP 450            | 2         | 0.52%   |
| HP 255            | 2         | 0.52%   |
| HP 245            | 2         | 0.52%   |
| HP 1000           | 2         | 0.52%   |
| Dell Precision    | 2         | 0.52%   |
| Dell G5           | 2         | 0.52%   |
| ASUS X550LD       | 2         | 0.52%   |
| Acer Nitro        | 2         | 0.52%   |
| Unknown           | 2         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 41        | 10.62%  |
| 2019 | 36        | 9.33%   |
| 2018 | 35        | 9.07%   |
| 2012 | 35        | 9.07%   |
| 2021 | 31        | 8.03%   |
| 2013 | 30        | 7.77%   |
| 2016 | 28        | 7.25%   |
| 2014 | 26        | 6.74%   |
| 2017 | 23        | 5.96%   |
| 2011 | 22        | 5.7%    |
| 2022 | 20        | 5.18%   |
| 2023 | 11        | 2.85%   |
| 2015 | 11        | 2.85%   |
| 2010 | 9         | 2.33%   |
| 2009 | 8         | 2.07%   |
| 2008 | 7         | 1.81%   |
| 2024 | 6         | 1.55%   |
| 2007 | 5         | 1.3%    |
| 2006 | 1         | 0.26%   |
| 2005 | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 386       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 352       | 90.72%  |
| Enabled  | 36        | 9.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 383       | 99.22%  |
| Yes  | 3         | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 120       | 30.15%  |
| 4.01-8.0    | 113       | 28.39%  |
| 3.01-4.0    | 61        | 15.33%  |
| 16.01-24.0  | 60        | 15.08%  |
| 32.01-64.0  | 11        | 2.76%   |
| 24.01-32.0  | 11        | 2.76%   |
| 1.01-2.0    | 10        | 2.51%   |
| 2.01-3.0    | 7         | 1.76%   |
| 64.01-256.0 | 3         | 0.75%   |
| 0.51-1.0    | 2         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 122       | 28.44%  |
| 1.01-2.0   | 118       | 27.51%  |
| 4.01-8.0   | 72        | 16.78%  |
| 3.01-4.0   | 67        | 15.62%  |
| 8.01-16.0  | 24        | 5.59%   |
| 0.51-1.0   | 22        | 5.13%   |
| 16.01-24.0 | 2         | 0.47%   |
| 24.01-32.0 | 1         | 0.23%   |
| 0.01-0.5   | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 281       | 72.05%  |
| 2      | 100       | 25.64%  |
| 3      | 7         | 1.79%   |
| 0      | 2         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 271       | 70.03%  |
| Yes       | 116       | 29.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 313       | 80.67%  |
| No        | 75        | 19.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 377       | 97.67%  |
| No        | 9         | 2.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 325       | 83.76%  |
| No        | 63        | 16.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Peru    | 386       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lima                  | 257       | 64.09%  |
| Arequipa              | 32        | 7.98%   |
| Trujillo              | 21        | 5.24%   |
| Huancayo              | 10        | 2.49%   |
| Piura                 | 9         | 2.24%   |
| Cusco                 | 9         | 2.24%   |
| Chiclayo              | 8         | 2%      |
| Ica                   | 6         | 1.5%    |
| San Isidro            | 3         | 0.75%   |
| La Victoria           | 3         | 0.75%   |
| Iquitos               | 3         | 0.75%   |
| Huaraz                | 3         | 0.75%   |
| Chimbote              | 3         | 0.75%   |
| Tarapoto              | 2         | 0.5%    |
| Tacna                 | 2         | 0.5%    |
| Santiago de Surco     | 2         | 0.5%    |
| Miraflores District   | 2         | 0.5%    |
| Lima region           | 2         | 0.5%    |
| Ilo                   | 2         | 0.5%    |
| Callao                | 2         | 0.5%    |
| Talara                | 1         | 0.25%   |
| San Vicente de Canete | 1         | 0.25%   |
| San Borja             | 1         | 0.25%   |
| San Agustin           | 1         | 0.25%   |
| Punta Colorada        | 1         | 0.25%   |
| Puno                  | 1         | 0.25%   |
| Pisco                 | 1         | 0.25%   |
| Pisac                 | 1         | 0.25%   |
| Palianñuñas         | 1         | 0.25%   |
| Oxapampa              | 1         | 0.25%   |
| Moquegua              | 1         | 0.25%   |
| Mala                  | 1         | 0.25%   |
| Lurin                 | 1         | 0.25%   |
| Juliaca               | 1         | 0.25%   |
| Distrito de Lima      | 1         | 0.25%   |
| Cerro de Pasco        | 1         | 0.25%   |
| Cajamarca             | 1         | 0.25%   |
| Barranco              | 1         | 0.25%   |
| Ayacucho              | 1         | 0.25%   |
| Abancay               | 1         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 64        | 77     | 13.22%  |
| Toshiba                        | 55        | 70     | 11.36%  |
| Seagate                        | 55        | 69     | 11.36%  |
| Kingston                       | 52        | 69     | 10.74%  |
| Samsung Electronics            | 45        | 55     | 9.3%    |
| SanDisk                        | 36        | 39     | 7.44%   |
| Crucial                        | 17        | 24     | 3.51%   |
| Unknown                        | 15        | 16     | 3.1%    |
| Micron Technology              | 14        | 15     | 2.89%   |
| Intel                          | 13        | 15     | 2.69%   |
| HGST                           | 10        | 11     | 2.07%   |
| Hewlett-Packard                | 10        | 10     | 2.07%   |
| SK hynix                       | 9         | 12     | 1.86%   |
| KIOXIA                         | 9         | 10     | 1.86%   |
| Kingston Technology Company    | 9         | 11     | 1.86%   |
| Netac                          | 7         | 7      | 1.45%   |
| Hitachi                        | 7         | 9      | 1.45%   |
| China                          | 5         | 6      | 1.03%   |
| Gigabyte Technology            | 4         | 4      | 0.83%   |
| TO Exter                       | 3         | 7      | 0.62%   |
| Phison Electronics             | 3         | 3      | 0.62%   |
| LITEON                         | 3         | 3      | 0.62%   |
| Apple                          | 3         | 3      | 0.62%   |
| Unknown                        | 3         | 3      | 0.62%   |
| UMIS                           | 2         | 2      | 0.41%   |
| Silicon Motion                 | 2         | 2      | 0.41%   |
| Patriot                        | 2         | 3      | 0.41%   |
| Lenovo                         | 2         | 3      | 0.41%   |
| A-DATA Technology              | 2         | 2      | 0.41%   |
| YMTC                           | 1         | 1      | 0.21%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.21%   |
| WALRAM                         | 1         | 1      | 0.21%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.21%   |
| Team                           | 1         | 2      | 0.21%   |
| SSSTC                          | 1         | 1      | 0.21%   |
| Solid State Storage Technology | 1         | 1      | 0.21%   |
| Reletech-P400                  | 1         | 2      | 0.21%   |
| Realtek Semiconductor          | 1         | 1      | 0.21%   |
| Phison                         | 1         | 1      | 0.21%   |
| O2 Micro                       | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 22        | 4.44%   |
| Seagate ST1000LM035-1RK172 1TB                    | 21        | 4.23%   |
| Toshiba MQ04ABF100 1TB                            | 14        | 2.82%   |
| Toshiba MQ01ABD100 1TB                            | 9         | 1.81%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 7         | 1.41%   |
| Toshiba MQ01ABF050 500GB                          | 7         | 1.41%   |
| Kingston SA400S37480G 480GB SSD                   | 7         | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 6         | 1.21%   |
| Netac SSD 256GB                                   | 6         | 1.21%   |
| Kingston SA400S37960G 960GB SSD                   | 6         | 1.21%   |
| Intel SSDPEKNU512GZ 512GB                         | 6         | 1.21%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 5         | 1.01%   |
| Unknown MMC Card  32GB                            | 5         | 1.01%   |
| Seagate ST9500325AS 500GB                         | 5         | 1.01%   |
| Seagate ST1000LM049-2GH172 1TB                    | 5         | 1.01%   |
| Kingston Company SNV2S1000G 1TB                   | 5         | 1.01%   |
| Kingston SA400S37120G 120GB SSD                   | 5         | 1.01%   |
| Crucial CT500MX500SSD4 500GB                      | 5         | 1.01%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 4         | 0.81%   |
| Unknown SD32G  32GB                               | 4         | 0.81%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB             | 4         | 0.81%   |
| SanDisk NVMe SSD Drive 1TB                        | 4         | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 0.81%   |
| HGST HTS721010A9E630 1TB                          | 4         | 0.81%   |
| HP SSD S700 500GB                                 | 4         | 0.81%   |
| Crucial CT1000BX500SSD1 1TB                       | 4         | 0.81%   |
| WDC WD10SPZX-24Z10 1TB                            | 3         | 0.6%    |
| Toshiba MQ01ABD075 752GB                          | 3         | 0.6%    |
| TO Exter nal USB 3.0 250GB                        | 3         | 0.6%    |
| Seagate ST500LT012-1DG142 500GB                   | 3         | 0.6%    |
| Seagate ST500LM021-1KJ152 500GB                   | 3         | 0.6%    |
| Seagate ST1000LM048-2E7172 1TB                    | 3         | 0.6%    |
| Samsung MZVLQ256HAJD-000H1 256GB                  | 3         | 0.6%    |
| Samsung MZVLQ1T0HALB-00000 1TB                    | 3         | 0.6%    |
| KIOXIA KBG40ZNS512G NVMe 512GB                    | 3         | 0.6%    |
| Intel SSDPEKNU512GZH 512GB                        | 3         | 0.6%    |
| HGST HTS541010B7E610 1TB                          | 3         | 0.6%    |
| Unknown                                           | 3         | 0.6%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 2         | 0.4%    |
| WDC WD5000LPVX-22V0TT0 500GB                      | 2         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 67     | 32.93%  |
| Toshiba             | 50        | 62     | 29.94%  |
| WDC                 | 37        | 42     | 22.16%  |
| HGST                | 10        | 11     | 5.99%   |
| Hitachi             | 7         | 9      | 4.19%   |
| TO Exter            | 3         | 7      | 1.8%    |
| Samsung Electronics | 1         | 1      | 0.6%    |
| JMicron Technology  | 1         | 1      | 0.6%    |
| Fujitsu             | 1         | 1      | 0.6%    |
| Apple               | 1         | 1      | 0.6%    |
| ACASIS              | 1         | 1      | 0.6%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 45        | 60     | 29.8%   |
| WDC                 | 23        | 27     | 15.23%  |
| Crucial             | 16        | 22     | 10.6%   |
| Samsung Electronics | 10        | 10     | 6.62%   |
| Hewlett-Packard     | 10        | 10     | 6.62%   |
| SanDisk             | 8         | 10     | 5.3%    |
| Netac               | 6         | 6      | 3.97%   |
| China               | 5         | 6      | 3.31%   |
| LITEON              | 3         | 3      | 1.99%   |
| Toshiba             | 2         | 3      | 1.32%   |
| Lenovo              | 2         | 3      | 1.32%   |
| Intel               | 2         | 2      | 1.32%   |
| Gigabyte Technology | 2         | 2      | 1.32%   |
| A-DATA Technology   | 2         | 2      | 1.32%   |
| WALRAM              | 1         | 1      | 0.66%   |
| Team                | 1         | 2      | 0.66%   |
| SSSTC               | 1         | 1      | 0.66%   |
| SK hynix            | 1         | 4      | 0.66%   |
| Seagate             | 1         | 1      | 0.66%   |
| Reletech-P400       | 1         | 2      | 0.66%   |
| Patriot             | 1         | 1      | 0.66%   |
| MSI                 | 1         | 1      | 0.66%   |
| KingSpec            | 1         | 1      | 0.66%   |
| GLOWAY              | 1         | 1      | 0.66%   |
| Fanxiang            | 1         | 1      | 0.66%   |
| Dogfish             | 1         | 1      | 0.66%   |
| Corsair             | 1         | 1      | 0.66%   |
| Apple               | 1         | 1      | 0.66%   |
| Unknown             | 1         | 1      | 0.66%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 165       | 203    | 35.64%  |
| NVMe    | 143       | 182    | 30.89%  |
| SSD     | 138       | 186    | 29.81%  |
| MMC     | 15        | 17     | 3.24%   |
| Unknown | 2         | 2      | 0.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 260       | 378    | 60.89%  |
| NVMe | 143       | 182    | 33.49%  |
| MMC  | 15        | 17     | 3.51%   |
| SAS  | 9         | 13     | 2.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 162       | 229    | 55.86%  |
| 0.51-1.0   | 122       | 151    | 42.07%  |
| 1.01-2.0   | 6         | 9      | 2.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 97        | 24.07%  |
| 251-500        | 93        | 23.08%  |
| 501-1000       | 86        | 21.34%  |
| 51-100         | 29        | 7.2%    |
| 1001-2000      | 28        | 6.95%   |
| 21-50          | 25        | 6.2%    |
| 1-20           | 25        | 6.2%    |
| Unknown        | 8         | 1.99%   |
| More than 3000 | 7         | 1.74%   |
| 2001-3000      | 5         | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 160       | 38.19%  |
| 21-50          | 83        | 19.81%  |
| 101-250        | 56        | 13.37%  |
| 51-100         | 46        | 10.98%  |
| 251-500        | 33        | 7.88%   |
| 501-1000       | 24        | 5.73%   |
| Unknown        | 8         | 1.91%   |
| 1001-2000      | 4         | 0.95%   |
| 2001-3000      | 3         | 0.72%   |
| More than 3000 | 1         | 0.24%   |
| 0              | 1         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 3         | 3      | 8.11%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 3      | 5.41%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 2      | 5.41%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 2      | 5.41%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 2      | 5.41%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 1      | 2.7%    |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 1      | 2.7%    |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1      | 2.7%    |
| Toshiba MQ04ABF100 1TB               | 1         | 1      | 2.7%    |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 2.7%    |
| Toshiba MK5065GSXN 500GB             | 1         | 1      | 2.7%    |
| Toshiba MK5056GSY 500GB              | 1         | 1      | 2.7%    |
| Toshiba MK4058GSX 400GB              | 1         | 1      | 2.7%    |
| Toshiba MK2035GSS 200GB              | 1         | 1      | 2.7%    |
| Toshiba HDWL110 1TB                  | 1         | 1      | 2.7%    |
| Toshiba HDWJ110 1TB                  | 1         | 1      | 2.7%    |
| SSSTC CVB-8D128-HP 128GB             | 1         | 1      | 2.7%    |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 1      | 2.7%    |
| Seagate ST9250315AS 250GB            | 1         | 1      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB      | 1         | 2      | 2.7%    |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 2.7%    |
| Seagate ST1000LM014-1EJ164 1TB       | 1         | 1      | 2.7%    |
| SanDisk SSD U110 16GB                | 1         | 1      | 2.7%    |
| Hitachi HTS725050A7E630 500GB        | 1         | 1      | 2.7%    |
| Hitachi HTS545050B9A300 500GB        | 1         | 1      | 2.7%    |
| Hitachi HTS545050A7E380 500GB        | 1         | 3      | 2.7%    |
| Hitachi HTS545032B9A302 320GB        | 1         | 1      | 2.7%    |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 2.7%    |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 2.7%    |
| Hewlett-Packard SSD S700 500GB       | 1         | 1      | 2.7%    |
| Hewlett-Packard SSD S700 1TB         | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 7         | 8      | 19.44%  |
| Toshiba         | 7         | 8      | 19.44%  |
| Seagate         | 7         | 8      | 19.44%  |
| Kingston        | 4         | 4      | 11.11%  |
| Hitachi         | 4         | 6      | 11.11%  |
| HGST            | 2         | 2      | 5.56%   |
| Hewlett-Packard | 2         | 2      | 5.56%   |
| SSSTC           | 1         | 1      | 2.78%   |
| SK hynix        | 1         | 1      | 2.78%   |
| SanDisk         | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 7         | 8      | 30.43%  |
| Seagate | 7         | 8      | 30.43%  |
| Hitachi | 4         | 6      | 17.39%  |
| WDC     | 3         | 3      | 13.04%  |
| HGST    | 2         | 2      | 8.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 27     | 63.89%  |
| SSD  | 12        | 13     | 33.33%  |
| NVMe | 1         | 1      | 2.78%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK3252GSX 320GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 221       | 327    | 53%     |
| Works    | 160       | 220    | 38.37%  |
| Malfunc  | 35        | 41     | 8.39%   |
| Failed   | 1         | 2      | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 270       | 58.44%  |
| AMD                              | 49        | 10.61%  |
| SanDisk                          | 35        | 7.58%   |
| Samsung Electronics              | 35        | 7.58%   |
| Kingston Technology Company      | 16        | 3.46%   |
| Micron Technology                | 14        | 3.03%   |
| KIOXIA                           | 9         | 1.95%   |
| SK hynix                         | 8         | 1.73%   |
| Phison Electronics               | 5         | 1.08%   |
| Toshiba America Info Systems     | 3         | 0.65%   |
| Yangtze Memory Technologies      | 2         | 0.43%   |
| Union Memory (Shenzhen)          | 2         | 0.43%   |
| Silicon Motion                   | 2         | 0.43%   |
| Realtek Semiconductor            | 2         | 0.43%   |
| Micron/Crucial Technology        | 2         | 0.43%   |
| Solid State Storage Technology   | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| O2 Micro                         | 1         | 0.22%   |
| Nvidia                           | 1         | 0.22%   |
| INNOGRIT                         | 1         | 0.22%   |
| Hosin Global Electronics         | 1         | 0.22%   |
| Biwin Storage Technology         | 1         | 0.22%   |
| Apple                            | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 44        | 9.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 41        | 8.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 36        | 7.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 28        | 5.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 19        | 3.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 15        | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 3.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 12        | 2.48%   |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 2.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 10        | 2.07%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 9         | 1.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 1.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 1.45%   |
| Intel RST Volume Management Device Controller                                  | 7         | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.45%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 6         | 1.24%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 1.24%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 1.24%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 1.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 1.24%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 5         | 1.04%   |
| SK hynix BC511 NVMe SSD                                                        | 4         | 0.83%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 4         | 0.83%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 4         | 0.83%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 4         | 0.83%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 0.83%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 4         | 0.83%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 4         | 0.83%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 4         | 0.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 0.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.83%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.62%   |
| SanDisk IX SN530 NVMe SSD / microSD Express Card (DRAM-less)                   | 3         | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.62%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3         | 0.62%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 3         | 0.62%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 3         | 0.62%   |
| Kingston Company NV2 NVMe SSD [E21T] (DRAM-less)                               | 3         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 256       | 54.58%  |
| NVMe | 143       | 30.49%  |
| RAID | 58        | 12.37%  |
| IDE  | 12        | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 300       | 77.52%  |
| AMD    | 87        | 22.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 2.58%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 2.33%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 2.07%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 2.07%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 2.07%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 1.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 1.55%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 6         | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.55%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.29%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.29%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.29%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 1.29%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 1.29%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 1.29%   |
| Intel 13th Gen Core i9-13900H                 | 5         | 1.29%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.29%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.29%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 1.29%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 1.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.03%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 4         | 1.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.03%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 4         | 1.03%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 1.03%   |
| Intel 12th Gen Core i5-1235U                  | 4         | 1.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.78%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.78%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.78%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.78%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.78%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 3         | 0.78%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 3         | 0.78%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 90        | 23.26%  |
| Intel Core i7           | 88        | 22.74%  |
| Intel Core i3           | 45        | 11.63%  |
| Other                   | 41        | 10.59%  |
| AMD Ryzen 5             | 29        | 7.49%   |
| AMD Ryzen 7             | 22        | 5.68%   |
| Intel Celeron           | 15        | 3.88%   |
| Intel Core 2 Duo        | 7         | 1.81%   |
| Intel Atom              | 6         | 1.55%   |
| AMD Ryzen 9             | 4         | 1.03%   |
| AMD Ryzen 3             | 4         | 1.03%   |
| Intel Xeon              | 3         | 0.78%   |
| AMD Ryzen 7 PRO         | 3         | 0.78%   |
| AMD E1                  | 3         | 0.78%   |
| AMD E                   | 3         | 0.78%   |
| AMD Athlon              | 3         | 0.78%   |
| AMD A8                  | 3         | 0.78%   |
| AMD A4                  | 3         | 0.78%   |
| Intel Pentium Dual-Core | 2         | 0.52%   |
| Intel Pentium           | 2         | 0.52%   |
| AMD A10                 | 2         | 0.52%   |
| Intel Pentium Dual      | 1         | 0.26%   |
| Intel Genuine           | 1         | 0.26%   |
| Intel Core i9           | 1         | 0.26%   |
| Intel Core 2            | 1         | 0.26%   |
| Intel Core              | 1         | 0.26%   |
| Intel Celeron M         | 1         | 0.26%   |
| AMD Quad-Core           | 1         | 0.26%   |
| AMD C-50                | 1         | 0.26%   |
| AMD A12                 | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 175       | 45.22%  |
| 4       | 128       | 33.07%  |
| 8       | 30        | 7.75%   |
| 6       | 24        | 6.2%    |
| 10      | 9         | 2.33%   |
| 1       | 7         | 1.81%   |
| 14      | 6         | 1.55%   |
| 12      | 3         | 0.78%   |
| 24      | 2         | 0.52%   |
| 16      | 2         | 0.52%   |
| Unknown | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 386       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 328       | 84.75%  |
| 1       | 58        | 14.99%  |
| Unknown | 1         | 0.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 380       | 97.94%  |
| 64-bit         | 3         | 0.77%   |
| 32-bit         | 3         | 0.77%   |
| Unknown        | 2         | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 191       | 47.75%  |
| 0x206a7    | 16        | 4%      |
| 0x306a9    | 12        | 3%      |
| 0x406e3    | 11        | 2.75%   |
| 0x40651    | 11        | 2.75%   |
| 0x806ec    | 10        | 2.5%    |
| 0x806ea    | 10        | 2.5%    |
| 0x806e9    | 9         | 2.25%   |
| 0x306d4    | 9         | 2.25%   |
| 0x08108109 | 8         | 2%      |
| 0x306c3    | 7         | 1.75%   |
| 0x08108102 | 6         | 1.5%    |
| 0x906ea    | 5         | 1.25%   |
| 0x806c1    | 5         | 1.25%   |
| 0x706e5    | 5         | 1.25%   |
| 0x0a50000c | 5         | 1.25%   |
| 0x30678    | 4         | 1%      |
| 0x20655    | 4         | 1%      |
| 0x20652    | 4         | 1%      |
| 0xa0652    | 3         | 0.75%   |
| 0x806eb    | 3         | 0.75%   |
| 0x1067a    | 3         | 0.75%   |
| 0x10661    | 3         | 0.75%   |
| 0x08608103 | 3         | 0.75%   |
| 0x08600106 | 3         | 0.75%   |
| 0xb06a2    | 2         | 0.5%    |
| 0x906e9    | 2         | 0.5%    |
| 0x906a3    | 2         | 0.5%    |
| 0x806d1    | 2         | 0.5%    |
| 0x0a50000d | 2         | 0.5%    |
| 0x0a404101 | 2         | 0.5%    |
| 0x08a00008 | 2         | 0.5%    |
| 0x08600104 | 2         | 0.5%    |
| 0x08600102 | 2         | 0.5%    |
| 0x06006704 | 2         | 0.5%    |
| 0x0600611a | 2         | 0.5%    |
| 0x05000119 | 2         | 0.5%    |
| 0x05000029 | 2         | 0.5%    |
| 0x906a4    | 1         | 0.25%   |
| 0x706a1    | 1         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 81        | 20.88%  |
| Haswell           | 33        | 8.51%   |
| Unknown           | 30        | 7.73%   |
| IvyBridge         | 25        | 6.44%   |
| SandyBridge       | 24        | 6.19%   |
| Zen+              | 21        | 5.41%   |
| Skylake           | 21        | 5.41%   |
| Alderlake Hybrid  | 15        | 3.87%   |
| IceLake           | 14        | 3.61%   |
| Broadwell         | 14        | 3.61%   |
| Westmere          | 12        | 3.09%   |
| Zen 3             | 11        | 2.84%   |
| Zen 2             | 10        | 2.58%   |
| TigerLake         | 9         | 2.32%   |
| Silvermont        | 9         | 2.32%   |
| Penryn            | 8         | 2.06%   |
| Excavator         | 7         | 1.8%    |
| Zen               | 6         | 1.55%   |
| Goldmont plus     | 6         | 1.55%   |
| Core              | 6         | 1.55%   |
| CometLake         | 6         | 1.55%   |
| Jaguar            | 4         | 1.03%   |
| Bobcat            | 4         | 1.03%   |
| Piledriver        | 3         | 0.77%   |
| Puma              | 2         | 0.52%   |
| P6                | 2         | 0.52%   |
| Nehalem           | 2         | 0.52%   |
| Bonnell           | 2         | 0.52%   |
| Meteorlake Hybrid | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 279       | 55.58%  |
| AMD                              | 121       | 24.1%   |
| Nvidia                           | 101       | 20.12%  |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                              | 25        | 4.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 23        | 4.46%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 22        | 4.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 21        | 4.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 21        | 4.07%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                               | 17        | 3.29%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                 | 14        | 2.71%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                              | 14        | 2.71%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 14        | 2.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 13        | 2.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 11        | 2.13%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                           | 10        | 1.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 9         | 1.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 9         | 1.74%   |
| Intel Core Processor Integrated Graphics Controller                                   | 9         | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 1.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 8         | 1.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 8         | 1.55%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 8         | 1.55%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 8         | 1.55%   |
| AMD Lucienne                                                                          | 7         | 1.36%   |
| Nvidia GM108M [GeForce MX110]                                                         | 6         | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 6         | 1.16%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 6         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 6         | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 6         | 1.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 6         | 1.16%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 5         | 0.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 5         | 0.97%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 5         | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 5         | 0.97%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 4         | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 0.78%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                 | 4         | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 0.78%   |
| AMD Rembrandt [Radeon 680M]                                                           | 4         | 0.78%   |
| AMD Barcelo                                                                           | 4         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 3         | 0.58%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 3         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 174       | 44.85%  |
| Intel + Nvidia | 73        | 18.81%  |
| 1 x AMD        | 71        | 18.3%   |
| Intel + AMD    | 28        | 7.22%   |
| 1 x Nvidia     | 15        | 3.87%   |
| AMD + Nvidia   | 14        | 3.61%   |
| 2 x AMD        | 8         | 2.06%   |
| 2 x Intel      | 4         | 1.03%   |
| 1 x SiS        | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 341       | 87.21%  |
| Proprietary | 38        | 9.72%   |
| Unknown     | 12        | 3.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 246       | 62.6%   |
| 1.01-2.0   | 55        | 13.99%  |
| 0.01-0.5   | 50        | 12.72%  |
| 3.01-4.0   | 15        | 3.82%   |
| 0.51-1.0   | 12        | 3.05%   |
| 7.01-8.0   | 6         | 1.53%   |
| 5.01-6.0   | 6         | 1.53%   |
| 8.01-16.0  | 2         | 0.51%   |
| 2.01-3.0   | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 93        | 20.85%  |
| BOE                     | 81        | 18.16%  |
| AU Optronics            | 69        | 15.47%  |
| Samsung Electronics     | 56        | 12.56%  |
| LG Display              | 47        | 10.54%  |
| Goldstar                | 16        | 3.59%   |
| PANDA                   | 9         | 2.02%   |
| Hewlett-Packard         | 6         | 1.35%   |
| Apple                   | 6         | 1.35%   |
| AOC                     | 5         | 1.12%   |
| Sharp                   | 4         | 0.9%    |
| Sony                    | 3         | 0.67%   |
| LG Philips              | 3         | 0.67%   |
| Lenovo                  | 3         | 0.67%   |
| JRY                     | 3         | 0.67%   |
| Dell                    | 3         | 0.67%   |
| Acer                    | 3         | 0.67%   |
| TMX                     | 2         | 0.45%   |
| InnoLux Display         | 2         | 0.45%   |
| HannStar                | 2         | 0.45%   |
| CSO                     | 2         | 0.45%   |
| Chi Mei Optoelectronics | 2         | 0.45%   |
| AGO                     | 2         | 0.45%   |
| Unknown                 | 2         | 0.45%   |
| ZSC                     | 1         | 0.22%   |
| Yuraku                  | 1         | 0.22%   |
| ViewSonic               | 1         | 0.22%   |
| Valve                   | 1         | 0.22%   |
| Unknown (XXX)           | 1         | 0.22%   |
| Sceptre Tech            | 1         | 0.22%   |
| RGT                     | 1         | 0.22%   |
| Panasonic               | 1         | 0.22%   |
| MSI                     | 1         | 0.22%   |
| MSD                     | 1         | 0.22%   |
| Mi                      | 1         | 0.22%   |
| LGD                     | 1         | 0.22%   |
| InfoVision              | 1         | 0.22%   |
| HUAWEI                  | 1         | 0.22%   |
| HKC                     | 1         | 0.22%   |
| Hitachi                 | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 13        | 2.88%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 9         | 2%      |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 6         | 1.33%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch       | 6         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 6         | 1.33%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                   | 6         | 1.33%   |
| AU Optronics LCD Monitor AUO459D 1920x1200 344x215mm 16.0-inch         | 6         | 1.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 5         | 1.11%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch       | 4         | 0.89%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                   | 4         | 0.89%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 4         | 0.89%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3         | 0.67%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch            | 3         | 0.67%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch        | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch        | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch        | 3         | 0.67%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                  | 3         | 0.67%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                  | 3         | 0.67%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                   | 3         | 0.67%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                   | 3         | 0.67%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                   | 3         | 0.67%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                   | 3         | 0.67%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                          | 2         | 0.44%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 2         | 0.44%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 2         | 0.44%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch   | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch   | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch   | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch   | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch   | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch   | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch   | 2         | 0.44%   |
| Samsung Electronics ATNA40CU05-0 SDC419C 2880x1800 302x189mm 14.0-inch | 2         | 0.44%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                | 2         | 0.44%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch            | 2         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 190       | 44.39%  |
| 1920x1080 (FHD)    | 140       | 32.71%  |
| 1920x1200 (WUXGA)  | 21        | 4.91%   |
| 3840x2160 (4K)     | 12        | 2.8%    |
| 1600x900 (HD+)     | 12        | 2.8%    |
| 1280x800 (WXGA)    | 11        | 2.57%   |
| 2160x1440          | 6         | 1.4%    |
| 1440x900 (WXGA+)   | 6         | 1.4%    |
| 1360x768           | 4         | 0.93%   |
| 2880x1800          | 3         | 0.7%    |
| 2560x1600          | 3         | 0.7%    |
| 2560x1440 (QHD)    | 3         | 0.7%    |
| 3840x1080          | 2         | 0.47%   |
| 3200x1800 (QHD+)   | 2         | 0.47%   |
| 1024x600           | 2         | 0.47%   |
| Unknown            | 2         | 0.47%   |
| 800x1280           | 1         | 0.23%   |
| 640x480            | 1         | 0.23%   |
| 3200x2000          | 1         | 0.23%   |
| 3072x1920          | 1         | 0.23%   |
| 2880x1620          | 1         | 0.23%   |
| 2520x1680          | 1         | 0.23%   |
| 1680x1050 (WSXGA+) | 1         | 0.23%   |
| 1280x720 (HD)      | 1         | 0.23%   |
| 1024x768 (XGA)     | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 199       | 44.92%  |
| 13      | 68        | 15.35%  |
| 14      | 60        | 13.54%  |
| 23      | 18        | 4.06%   |
| 16      | 17        | 3.84%   |
| 17      | 14        | 3.16%   |
| 21      | 9         | 2.03%   |
| 27      | 8         | 1.81%   |
| 18      | 8         | 1.81%   |
| 24      | 7         | 1.58%   |
| 11      | 7         | 1.58%   |
| 31      | 5         | 1.13%   |
| 12      | 4         | 0.9%    |
| Unknown | 3         | 0.68%   |
| 72      | 2         | 0.45%   |
| 48      | 2         | 0.45%   |
| 20      | 2         | 0.45%   |
| 10      | 2         | 0.45%   |
| 84      | 1         | 0.23%   |
| 60      | 1         | 0.23%   |
| 54      | 1         | 0.23%   |
| 46      | 1         | 0.23%   |
| 39      | 1         | 0.23%   |
| 22      | 1         | 0.23%   |
| 19      | 1         | 0.23%   |
| 7       | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 320       | 72.89%  |
| 501-600     | 32        | 7.29%   |
| 201-300     | 30        | 6.83%   |
| 401-500     | 21        | 4.78%   |
| 351-400     | 17        | 3.87%   |
| 601-700     | 6         | 1.37%   |
| 1001-1500   | 5         | 1.14%   |
| 1501-2000   | 3         | 0.68%   |
| Unknown     | 3         | 0.68%   |
| 801-900     | 1         | 0.23%   |
| 1-100       | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 333       | 84.52%  |
| 16/10   | 45        | 11.42%  |
| 3/2     | 7         | 1.78%   |
| 4/3     | 4         | 1.02%   |
| Unknown | 3         | 0.76%   |
| 32/9    | 1         | 0.25%   |
| 0.62    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 199       | 45.02%  |
| 81-90          | 110       | 24.89%  |
| 201-250        | 32        | 7.24%   |
| 111-120        | 17        | 3.85%   |
| 71-80          | 16        | 3.62%   |
| 121-130        | 12        | 2.71%   |
| 301-350        | 8         | 1.81%   |
| 51-60          | 7         | 1.58%   |
| 151-200        | 7         | 1.58%   |
| More than 1000 | 6         | 1.36%   |
| 141-150        | 6         | 1.36%   |
| 351-500        | 5         | 1.13%   |
| 131-140        | 3         | 0.68%   |
| 501-1000       | 3         | 0.68%   |
| 91-100         | 3         | 0.68%   |
| Unknown        | 3         | 0.68%   |
| 61-70          | 2         | 0.45%   |
| 41-50          | 2         | 0.45%   |
| 1-40           | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 197       | 44.98%  |
| 121-160       | 139       | 31.74%  |
| 51-100        | 62        | 14.16%  |
| 161-240       | 23        | 5.25%   |
| More than 240 | 7         | 1.6%    |
| 1-50          | 7         | 1.6%    |
| Unknown       | 3         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 311       | 79.13%  |
| 2     | 71        | 18.07%  |
| 0     | 8         | 2.04%   |
| 3     | 3         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 245       | 40.97%  |
| Intel                            | 142       | 23.75%  |
| Qualcomm Atheros                 | 95        | 15.89%  |
| Broadcom                         | 29        | 4.85%   |
| MediaTek                         | 25        | 4.18%   |
| TP-Link                          | 13        | 2.17%   |
| Xiaomi                           | 9         | 1.51%   |
| Ralink                           | 8         | 1.34%   |
| Ralink Technology                | 4         | 0.67%   |
| Marvell Technology Group         | 4         | 0.67%   |
| ASIX Electronics                 | 4         | 0.67%   |
| ICS Advent                       | 3         | 0.5%    |
| Samsung Electronics              | 2         | 0.33%   |
| Qualcomm                         | 2         | 0.33%   |
| Motorola PCS                     | 2         | 0.33%   |
| Broadcom Limited                 | 2         | 0.33%   |
| T & A Mobile Phones              | 1         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| OPPO Electronics                 | 1         | 0.17%   |
| Nvidia                           | 1         | 0.17%   |
| Microsoft                        | 1         | 0.17%   |
| Lenovo                           | 1         | 0.17%   |
| Google                           | 1         | 0.17%   |
| DisplayLink                      | 1         | 0.17%   |
| Apple                            | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 147       | 20.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 49        | 6.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 32        | 4.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 2.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 2.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 13        | 1.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 12        | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 1.65%   |
| Intel Wireless 8260                                                     | 11        | 1.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 1.37%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 10        | 1.37%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 10        | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 9         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 1.23%   |
| Intel Wireless 7260                                                     | 9         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 1.23%   |
| Intel Wireless 8265 / 8275                                              | 8         | 1.1%    |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 1.1%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 7         | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.82%   |
| Intel Wireless 7265                                                     | 6         | 0.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 6         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 0.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.69%   |
| Intel Ethernet Connection I218-LM                                       | 5         | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 0.69%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 0.55%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.55%   |
| Intel Wireless 3160                                                     | 4         | 0.55%   |
| Intel WiFi Link 5100                                                    | 4         | 0.55%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 134       | 33.75%  |
| Realtek Semiconductor | 102       | 25.69%  |
| Qualcomm Atheros      | 84        | 21.16%  |
| Broadcom              | 26        | 6.55%   |
| MediaTek              | 25        | 6.3%    |
| TP-Link               | 11        | 2.77%   |
| Ralink                | 8         | 2.02%   |
| Ralink Technology     | 4         | 1.01%   |
| Qualcomm              | 2         | 0.5%    |
| Broadcom Limited      | 1         | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 32        | 8.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 6.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 4.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 3.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 12        | 3.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 3.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 3.02%   |
| Intel Wireless 8260                                                     | 11        | 2.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 2.52%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 10        | 2.52%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 10        | 2.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 2.27%   |
| Intel Wireless 7260                                                     | 9         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 2.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 2.27%   |
| Intel Wireless 8265 / 8275                                              | 8         | 2.02%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 2.02%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 7         | 1.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 1.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.51%   |
| Intel Wireless 7265                                                     | 6         | 1.51%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 6         | 1.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 1.26%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.26%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 1.01%   |
| Realtek 802.11ac NIC                                                    | 4         | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.01%   |
| Intel Wireless 3160                                                     | 4         | 1.01%   |
| Intel WiFi Link 5100                                                    | 4         | 1.01%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.01%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.76%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.76%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 214       | 65.24%  |
| Intel                            | 49        | 14.94%  |
| Qualcomm Atheros                 | 22        | 6.71%   |
| Xiaomi                           | 9         | 2.74%   |
| Broadcom                         | 7         | 2.13%   |
| Marvell Technology Group         | 4         | 1.22%   |
| ASIX Electronics                 | 4         | 1.22%   |
| ICS Advent                       | 3         | 0.91%   |
| TP-Link                          | 2         | 0.61%   |
| Samsung Electronics              | 2         | 0.61%   |
| Motorola PCS                     | 2         | 0.61%   |
| T & A Mobile Phones              | 1         | 0.3%    |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |
| OPPO Electronics                 | 1         | 0.3%    |
| Nvidia                           | 1         | 0.3%    |
| Microsoft                        | 1         | 0.3%    |
| Lenovo                           | 1         | 0.3%    |
| Google                           | 1         | 0.3%    |
| DisplayLink                      | 1         | 0.3%    |
| Broadcom Limited                 | 1         | 0.3%    |
| Apple                            | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 147       | 44.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 49        | 14.76%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 3.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9         | 2.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 2.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 1.51%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 1.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.9%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.9%    |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.9%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 3         | 0.9%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.6%    |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.6%    |
| Motorola PCS motorola one 5G ace                                       | 2         | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.6%    |
| Intel Ethernet Connection I219-V                                       | 2         | 0.6%    |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.6%    |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.6%    |
| TP-Link USB 10/100 LAN                                                 | 1         | 0.3%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.3%    |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                           | 1         | 0.3%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.3%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.3%    |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 377       | 54.64%  |
| Ethernet | 313       | 45.36%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 305       | 74.03%  |
| Ethernet | 107       | 25.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 282       | 73.06%  |
| 1     | 100       | 25.91%  |
| 0     | 4         | 1.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 296       | 74.56%  |
| Yes  | 101       | 25.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 110       | 33.64%  |
| Realtek Semiconductor           | 72        | 22.02%  |
| Qualcomm Atheros Communications | 44        | 13.46%  |
| IMC Networks                    | 32        | 9.79%   |
| Lite-On Technology              | 15        | 4.59%   |
| Foxconn / Hon Hai               | 12        | 3.67%   |
| Toshiba                         | 8         | 2.45%   |
| Broadcom                        | 8         | 2.45%   |
| Ralink                          | 6         | 1.83%   |
| Apple                           | 5         | 1.53%   |
| Hewlett-Packard                 | 3         | 0.92%   |
| Cambridge Silicon Radio         | 3         | 0.92%   |
| Realtek                         | 2         | 0.61%   |
| Foxconn International           | 2         | 0.61%   |
| Dell                            | 2         | 0.61%   |
| Alps Electric                   | 2         | 0.61%   |
| USI                             | 1         | 0.31%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 11.93%  |
| Realtek Bluetooth Radio                             | 38        | 11.62%  |
| Realtek  Bluetooth 4.2 Adapter                      | 29        | 8.87%   |
| Qualcomm Atheros  Bluetooth Device                  | 29        | 8.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 29        | 8.87%   |
| IMC Networks Wireless_Device                        | 18        | 5.5%    |
| Intel AX201 Bluetooth                               | 14        | 4.28%   |
| Intel AX200 Bluetooth                               | 8         | 2.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 2.14%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.14%   |
| Ralink RT3290 Bluetooth                             | 6         | 1.83%   |
| Intel Bluetooth Device                              | 6         | 1.83%   |
| Toshiba Bluetooth Device                            | 5         | 1.53%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 1.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 1.22%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 1.22%   |
| IMC Networks Bluetooth Device                       | 4         | 1.22%   |
| Lite-On Bluetooth Radio                             | 3         | 0.92%   |
| Lite-On Bluetooth Device                            | 3         | 0.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 0.92%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 0.92%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.92%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.61%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.61%   |
| Realtek Bluetooth Radio                             | 2         | 0.61%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.61%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.61%   |
| Intel AX210 Bluetooth                               | 2         | 0.61%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.61%   |
| Foxconn / Hon Hai BCM43142A0                        | 2         | 0.61%   |
| Broadcom HP Portable Valentine                      | 2         | 0.61%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.61%   |
| Apple Bluetooth Host Controller                     | 2         | 0.61%   |
| USI Bluetooth Device                                | 1         | 0.31%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 292       | 62.93%  |
| AMD                              | 95        | 20.47%  |
| Nvidia                           | 56        | 12.07%  |
| Generalplus Technology           | 3         | 0.65%   |
| C-Media Electronics              | 3         | 0.65%   |
| Sony                             | 2         | 0.43%   |
| Logitech                         | 2         | 0.43%   |
| Kingston Technology              | 2         | 0.43%   |
| GN Netcom                        | 2         | 0.43%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Razer USA                        | 1         | 0.22%   |
| Pixart Imaging                   | 1         | 0.22%   |
| Panasonic (Matsushita)           | 1         | 0.22%   |
| JMTek                            | 1         | 0.22%   |
| Hewlett-Packard                  | 1         | 0.22%   |
| Apple                            | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 63        | 10.75%  |
| Intel Sunrise Point-LP HD Audio                                            | 57        | 9.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 32        | 5.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 26        | 4.44%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 25        | 4.27%   |
| Intel 8 Series HD Audio Controller                                         | 21        | 3.58%   |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 3.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17        | 2.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 14        | 2.39%   |
| Intel Broadwell-U Audio Controller                                         | 14        | 2.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 2.39%   |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 2.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 2.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 11        | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 1.71%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 10        | 1.71%   |
| AMD FCH Azalia Controller                                                  | 10        | 1.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 9         | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 1.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 1.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 1.54%   |
| AMD Radeon High Definition Audio Controller                                | 9         | 1.54%   |
| AMD Kabini HDMI/DP Audio                                                   | 8         | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 1.19%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 1.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 1.02%   |
| Nvidia AD107 High Definition Audio Controller                              | 5         | 0.85%   |
| AMD High Definition Audio Controller                                       | 5         | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.68%   |
| Nvidia GA107 High Definition Audio Controller                              | 4         | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 0.68%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 91        | 30.64%  |
| SK hynix            | 64        | 21.55%  |
| Micron Technology   | 40        | 13.47%  |
| Kingston            | 33        | 11.11%  |
| Ramaxel Technology  | 16        | 5.39%   |
| Unknown             | 13        | 4.38%   |
| Team                | 7         | 2.36%   |
| Crucial             | 6         | 2.02%   |
| Unknown (ABCD)      | 5         | 1.68%   |
| Hewlett-Packard     | 4         | 1.35%   |
| Elpida              | 3         | 1.01%   |
| Unknown             | 3         | 1.01%   |
| Patriot             | 2         | 0.67%   |
| Kllisre             | 2         | 0.67%   |
| CSX                 | 2         | 0.67%   |
| Nanya Technology    | 1         | 0.34%   |
| Goldkey             | 1         | 0.34%   |
| Corsair             | 1         | 0.34%   |
| Apacer              | 1         | 0.34%   |
| A-DATA Technology   | 1         | 0.34%   |
| 80540000802C        | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 2.74%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 2.13%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 6         | 1.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.83%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.83%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.52%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 1.52%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 5         | 1.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 1.52%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 1.22%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 4         | 1.22%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.22%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.22%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.22%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 1.22%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 4         | 1.22%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.91%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.91%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.91%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.91%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.91%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.91%   |
| Samsung RAM M471A1K43BB0-CPB 8GiB SODIMM DDR4 2133MT/s           | 3         | 0.91%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 3         | 0.91%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 3         | 0.91%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.91%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.91%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s          | 3         | 0.91%   |
| Unknown                                                          | 3         | 0.91%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.61%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s          | 2         | 0.61%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 2         | 0.61%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.61%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 110       | 48.25%  |
| DDR3    | 76        | 33.33%  |
| LPDDR4  | 13        | 5.7%    |
| DDR5    | 8         | 3.51%   |
| DDR2    | 7         | 3.07%   |
| LPDDR5  | 6         | 2.63%   |
| LPDDR3  | 4         | 1.75%   |
| SDRAM   | 3         | 1.32%   |
| Unknown | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 213       | 93.01%  |
| Row Of Chips | 13        | 5.68%   |
| Unknown      | 2         | 0.87%   |
| Chip         | 1         | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 116       | 42.96%  |
| 4096  | 89        | 32.96%  |
| 16384 | 27        | 10%     |
| 2048  | 22        | 8.15%   |
| 32768 | 11        | 4.07%   |
| 1024  | 4         | 1.48%   |
| 512   | 1         | 0.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 61        | 23.74%  |
| 1600    | 61        | 23.74%  |
| 2667    | 52        | 20.23%  |
| 2400    | 16        | 6.23%   |
| 3266    | 9         | 3.5%    |
| 1333    | 8         | 3.11%   |
| 2133    | 7         | 2.72%   |
| 5600    | 5         | 1.95%   |
| Unknown | 5         | 1.95%   |
| 8400    | 4         | 1.56%   |
| 1334    | 4         | 1.56%   |
| 7500    | 3         | 1.17%   |
| 4800    | 3         | 1.17%   |
| 1867    | 3         | 1.17%   |
| 5500    | 2         | 0.78%   |
| 1067    | 2         | 0.78%   |
| 975     | 2         | 0.78%   |
| 667     | 2         | 0.78%   |
| 6400    | 1         | 0.39%   |
| 4267    | 1         | 0.39%   |
| 4199    | 1         | 0.39%   |
| 2933    | 1         | 0.39%   |
| 2048    | 1         | 0.39%   |
| 1066    | 1         | 0.39%   |
| 800     | 1         | 0.39%   |
| 533     | 1         | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon                         | 2         | 28.57%  |
| Seiko Epson                   | 1         | 14.29%  |
| Samsung Info. Systems America | 1         | 14.29%  |
| Prolific Technology           | 1         | 14.29%  |
| Hewlett-Packard               | 1         | 14.29%  |
| Brother Industries            | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                    | 1         | 14.29%  |
| Samsung Info. Systems America SAMSUNG SRP-270 | 1         | 14.29%  |
| Prolific PL2305 Parallel Port                 | 1         | 14.29%  |
| HP LaserJet Professional P 1102w              | 1         | 14.29%  |
| Canon G2010 series                            | 1         | 14.29%  |
| Canon E400 series                             | 1         | 14.29%  |
| Brother DCP-T300                              | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 82        | 22.4%   |
| IMC Networks                           | 36        | 9.84%   |
| Microdia                               | 31        | 8.47%   |
| Realtek Semiconductor                  | 30        | 8.2%    |
| Bison Electronics                      | 26        | 7.1%    |
| Quanta                                 | 23        | 6.28%   |
| Syntek                                 | 20        | 5.46%   |
| Sunplus Innovation Technology          | 19        | 5.19%   |
| Lite-On Technology                     | 19        | 5.19%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 4.64%   |
| Suyin                                  | 14        | 3.83%   |
| ShineTech                              | 10        | 2.73%   |
| Luxvisions Innotech Limited            | 6         | 1.64%   |
| Sonix Technology                       | 5         | 1.37%   |
| Apple                                  | 5         | 1.37%   |
| Ricoh                                  | 4         | 1.09%   |
| Importek                               | 4         | 1.09%   |
| Alcor Micro                            | 3         | 0.82%   |
| Samsung Electronics                    | 2         | 0.55%   |
| Logitech                               | 2         | 0.55%   |
| Acer                                   | 2         | 0.55%   |
| Silicon Motion                         | 1         | 0.27%   |
| Shine-optics                           | 1         | 0.27%   |
| Jieli Technology                       | 1         | 0.27%   |
| BillionPixels                          | 1         | 0.27%   |
| ASUSTek Computer                       | 1         | 0.27%   |
| ANYKA                                  | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 15        | 4.08%   |
| Chicony Integrated Camera                                                  | 14        | 3.8%    |
| Bison Integrated Camera                                                    | 10        | 2.72%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 2.45%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 2.17%   |
| Chicony EasyCamera                                                         | 8         | 2.17%   |
| Realtek Integrated_Webcam_HD                                               | 7         | 1.9%    |
| Lite-On Integrated Camera                                                  | 7         | 1.9%    |
| ShineTech USB2.0 HD UVC WebCam                                             | 6         | 1.63%   |
| Microdia Webcam Vitade AF                                                  | 6         | 1.63%   |
| Microdia Integrated_Webcam_HD                                              | 6         | 1.63%   |
| IMC Networks Integrated Camera                                             | 6         | 1.63%   |
| Chicony HP Truevision HD                                                   | 6         | 1.63%   |
| Sunplus Integrated_Webcam_HD                                               | 5         | 1.36%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 5         | 1.36%   |
| Chicony Lenovo EasyCamera                                                  | 5         | 1.36%   |
| Chicony HP Webcam                                                          | 5         | 1.36%   |
| Chicony HP TrueVision HD Camera                                            | 5         | 1.36%   |
| Quanta HD Camera                                                           | 4         | 1.09%   |
| IMC Networks HP TrueVision HD Camera                                       | 4         | 1.09%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 1.09%   |
| Chicony TOSHIBA Web Camera - HD                                            | 4         | 1.09%   |
| Chicony HD WebCam                                                          | 4         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 4         | 1.09%   |
| Shinetech USB2.0 FHD UVC WebCam                                            | 3         | 0.82%   |
| Realtek Integrated Webcam                                                  | 3         | 0.82%   |
| Quanta HP Webcam                                                           | 3         | 0.82%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 3         | 0.82%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 3         | 0.82%   |
| Lite-On HP HD Camera                                                       | 3         | 0.82%   |
| Chicony HP Wide Vision HD Camera                                           | 3         | 0.82%   |
| Chicony HP HD Webcam                                                       | 3         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 0.82%   |
| Bison Lenovo EasyCamera                                                    | 3         | 0.82%   |
| Bison EasyCamera                                                           | 3         | 0.82%   |
| Apple FaceTime HD Camera                                                   | 3         | 0.82%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 2         | 0.54%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 2         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 30        | 50%     |
| Synaptics                  | 14        | 23.33%  |
| Shenzhen Goodix Technology | 6         | 10%     |
| Elan Microelectronics      | 6         | 10%     |
| AuthenTec                  | 2         | 3.33%   |
| Upek                       | 1         | 1.67%   |
| STMicroelectronics         | 1         | 1.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 9         | 15%     |
| Validity Sensors VFS5011 Fingerprint Reader               | 8         | 13.33%  |
| Synaptics  WBDI                                           | 4         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                       | 4         | 6.67%   |
| Elan ELAN:Fingerprint                                     | 4         | 6.67%   |
| Validity Sensors VFS471 Fingerprint Reader                | 3         | 5%      |
| Validity Sensors Synaptics WBDI                           | 3         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 3         | 5%      |
| Validity Sensors Fingerprint scanner                      | 2         | 3.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                 | 2         | 3.33%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 3.33%   |
| Elan ELAN:ARM-M4                                          | 2         | 3.33%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 2         | 3.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 1.67%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 1.67%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 1.67%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 1.67%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 1.67%   |
| Upek TCS5B Fingerprint sensor                             | 1         | 1.67%   |
| Synaptics WBDI                                            | 1         | 1.67%   |
| Synaptics UWP WBDI Device                                 | 1         | 1.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 1.67%   |
| Synaptics Fingerprint reader [HP G6]                      | 1         | 1.67%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 1.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 50%     |
| Alcor Micro | 5         | 27.78%  |
| Upek        | 3         | 16.67%  |
| O2 Micro    | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 27.78%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 16.67%  |
| Broadcom 5880                                                                | 3         | 16.67%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 2         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 245       | 62.18%  |
| 1     | 123       | 31.22%  |
| 2     | 23        | 5.84%   |
| 3     | 3         | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 60        | 34.68%  |
| Graphics card            | 38        | 21.97%  |
| Net/wireless             | 29        | 16.76%  |
| Chipcard                 | 15        | 8.67%   |
| Bluetooth                | 8         | 4.62%   |
| Multimedia controller    | 7         | 4.05%   |
| Camera                   | 5         | 2.89%   |
| Sound                    | 3         | 1.73%   |
| Communication controller | 3         | 1.73%   |
| Storage                  | 2         | 1.16%   |
| Card reader              | 2         | 1.16%   |
| Net/ethernet             | 1         | 0.58%   |

