CentOS 7 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for CentOS 7.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/CentOS_7/Desktop/README.md) and [notebooks](/Dist/CentOS_7/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=centos-7

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | Z77 Extreme4                | Desktop     | [bf66e1d281](https://linux-hardware.org/?probe=bf66e1d281) | Oct 29, 2021 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [6fe6c2d416](https://linux-hardware.org/?probe=6fe6c2d416) | Oct 27, 2021 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [22fd625209](https://linux-hardware.org/?probe=22fd625209) | Oct 26, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [b4a30d2562](https://linux-hardware.org/?probe=b4a30d2562) | Oct 22, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [862513b9f6](https://linux-hardware.org/?probe=862513b9f6) | Oct 21, 2021 |
| ASUSTek       | P5BV-M/RS100-E5             | Desktop     | [13134022df](https://linux-hardware.org/?probe=13134022df) | Oct 19, 2021 |
| Huanan        | X79                         | Desktop     | [3532bbed3d](https://linux-hardware.org/?probe=3532bbed3d) | Oct 08, 2021 |
| Huanan        | X79                         | Desktop     | [6638a35363](https://linux-hardware.org/?probe=6638a35363) | Oct 08, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [a68000e142](https://linux-hardware.org/?probe=a68000e142) | Sep 26, 2021 |
| Dell          | Latitude E6530              | Notebook    | [41d65e59eb](https://linux-hardware.org/?probe=41d65e59eb) | Sep 26, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [3eb1f3e342](https://linux-hardware.org/?probe=3eb1f3e342) | Sep 24, 2021 |
| Dell          | 0F0XJ6 A11                  | Server      | [26944912d7](https://linux-hardware.org/?probe=26944912d7) | Sep 17, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [d7ee29aac3](https://linux-hardware.org/?probe=d7ee29aac3) | Sep 15, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e4278d3243](https://linux-hardware.org/?probe=e4278d3243) | Sep 15, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [fd6f5273e3](https://linux-hardware.org/?probe=fd6f5273e3) | Sep 02, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [0beccde57d](https://linux-hardware.org/?probe=0beccde57d) | Sep 01, 2021 |
| Supermicro    | X10DRL-CT                   | Server      | [cc00646768](https://linux-hardware.org/?probe=cc00646768) | Aug 28, 2021 |
| Supermicro    | X10DRL-CT                   | Server      | [15df3c0fff](https://linux-hardware.org/?probe=15df3c0fff) | Aug 28, 2021 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [01d87985dd](https://linux-hardware.org/?probe=01d87985dd) | Aug 28, 2021 |
| HP            | 8751                        | Desktop     | [cdaf5a0ed8](https://linux-hardware.org/?probe=cdaf5a0ed8) | Aug 24, 2021 |
| Lenovo        | 7X06CTO1WW                  | Server      | [928ee22e71](https://linux-hardware.org/?probe=928ee22e71) | Aug 24, 2021 |
| Dell          | 0F0XJ6 A11                  | Server      | [2c424ced84](https://linux-hardware.org/?probe=2c424ced84) | Aug 23, 2021 |
| Dell          | 0F0XJ6 A11                  | Server      | [5e08b5eafd](https://linux-hardware.org/?probe=5e08b5eafd) | Aug 22, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [f9c840ba9c](https://linux-hardware.org/?probe=f9c840ba9c) | Aug 21, 2021 |
| Supermicro    | X11SSH-F                    | Desktop     | [35fff898d1](https://linux-hardware.org/?probe=35fff898d1) | Aug 20, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [d2f1dd867d](https://linux-hardware.org/?probe=d2f1dd867d) | Aug 20, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [6e6d5c8f2c](https://linux-hardware.org/?probe=6e6d5c8f2c) | Aug 20, 2021 |
| HP            | Presario C700               | Notebook    | [fa731abf46](https://linux-hardware.org/?probe=fa731abf46) | Aug 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cabe0be4fc](https://linux-hardware.org/?probe=cabe0be4fc) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cf348cec5f](https://linux-hardware.org/?probe=cf348cec5f) | Aug 16, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [8ddb489f03](https://linux-hardware.org/?probe=8ddb489f03) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [d19976dabe](https://linux-hardware.org/?probe=d19976dabe) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [d56fdac07b](https://linux-hardware.org/?probe=d56fdac07b) | Aug 05, 2021 |
| HP            | ProLiant DL360 G5           | Server      | [58c9a1d28b](https://linux-hardware.org/?probe=58c9a1d28b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [3eb59a276c](https://linux-hardware.org/?probe=3eb59a276c) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [3d0db6b81f](https://linux-hardware.org/?probe=3d0db6b81f) | Aug 05, 2021 |
| Sun Micros... | S39                         | Server      | [e54a36a0c4](https://linux-hardware.org/?probe=e54a36a0c4) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [1fc2375e54](https://linux-hardware.org/?probe=1fc2375e54) | Aug 05, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [7952948421](https://linux-hardware.org/?probe=7952948421) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a653e9beb2](https://linux-hardware.org/?probe=a653e9beb2) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [9a5d8276bf](https://linux-hardware.org/?probe=9a5d8276bf) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [2165980dd3](https://linux-hardware.org/?probe=2165980dd3) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [4a2adade2a](https://linux-hardware.org/?probe=4a2adade2a) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [78c5e3532b](https://linux-hardware.org/?probe=78c5e3532b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [10bdaec1ef](https://linux-hardware.org/?probe=10bdaec1ef) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [70fc6a65ef](https://linux-hardware.org/?probe=70fc6a65ef) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [80244f2809](https://linux-hardware.org/?probe=80244f2809) | Aug 05, 2021 |
| Sun Micros... | SUN FIRE X2270 375-3602-... | Server      | [54eaa5139f](https://linux-hardware.org/?probe=54eaa5139f) | Aug 05, 2021 |
| HP            | 8591                        | Desktop     | [6794bdb00e](https://linux-hardware.org/?probe=6794bdb00e) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [f209feb9c8](https://linux-hardware.org/?probe=f209feb9c8) | Aug 05, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [40b8d28af0](https://linux-hardware.org/?probe=40b8d28af0) | Aug 04, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [597de4e10b](https://linux-hardware.org/?probe=597de4e10b) | Aug 01, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [1232705d62](https://linux-hardware.org/?probe=1232705d62) | Jul 22, 2021 |
| HP            | 2B34                        | Desktop     | [0de82dabad](https://linux-hardware.org/?probe=0de82dabad) | Jul 10, 2021 |
| HP            | 0A9Ch                       | Desktop     | [e3159a6511](https://linux-hardware.org/?probe=e3159a6511) | Jul 07, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [c0af3fd295](https://linux-hardware.org/?probe=c0af3fd295) | Jul 05, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [a3f3f1e1c0](https://linux-hardware.org/?probe=a3f3f1e1c0) | Jul 02, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [70929dad4d](https://linux-hardware.org/?probe=70929dad4d) | Jun 24, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [32d294ba2a](https://linux-hardware.org/?probe=32d294ba2a) | Jun 23, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [6beb9f6867](https://linux-hardware.org/?probe=6beb9f6867) | Jun 19, 2021 |
| HP            | 1494                        | Desktop     | [d34b022996](https://linux-hardware.org/?probe=d34b022996) | Jun 11, 2021 |
| Intel         | E98683-353                  | Desktop     | [2f0ae62282](https://linux-hardware.org/?probe=2f0ae62282) | May 29, 2021 |
| HP            | 1589                        | Desktop     | [a4b0ebbee2](https://linux-hardware.org/?probe=a4b0ebbee2) | May 23, 2021 |
| ASRock        | J3710M                      | Desktop     | [6f289497fc](https://linux-hardware.org/?probe=6f289497fc) | May 23, 2021 |
| HP            | 8710                        | Mini pc     | [b2a212246b](https://linux-hardware.org/?probe=b2a212246b) | May 14, 2021 |
| HP            | 8594                        | Desktop     | [991250b6a8](https://linux-hardware.org/?probe=991250b6a8) | May 14, 2021 |
| HP            | 829A                        | Mini pc     | [c326081d7d](https://linux-hardware.org/?probe=c326081d7d) | May 14, 2021 |
| HP            | 1825                        | Desktop     | [13110a2081](https://linux-hardware.org/?probe=13110a2081) | May 14, 2021 |
| ASUSTek       | U35JC                       | Notebook    | [29ea6520a1](https://linux-hardware.org/?probe=29ea6520a1) | May 08, 2021 |
| Lenovo        | ThinkPad X200 7459ZEJ       | Notebook    | [a4f7ad5736](https://linux-hardware.org/?probe=a4f7ad5736) | May 07, 2021 |
| HP            | 8710                        | Mini pc     | [a9e3962fe5](https://linux-hardware.org/?probe=a9e3962fe5) | May 07, 2021 |
| HP            | 8710                        | Mini pc     | [a862c9d728](https://linux-hardware.org/?probe=a862c9d728) | May 07, 2021 |
| Lenovo        | 01DC328                     | Server      | [3510dd7b10](https://linux-hardware.org/?probe=3510dd7b10) | May 05, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [33c13bfcf0](https://linux-hardware.org/?probe=33c13bfcf0) | May 01, 2021 |
| HP            | 8591                        | Desktop     | [149576417f](https://linux-hardware.org/?probe=149576417f) | Apr 27, 2021 |
| HP            | 8591                        | Desktop     | [03b17d692d](https://linux-hardware.org/?probe=03b17d692d) | Apr 26, 2021 |
| Lenovo        | 01GR174                     | Server      | [63ec4551f5](https://linux-hardware.org/?probe=63ec4551f5) | Apr 26, 2021 |
| Lenovo        | 01GR174                     | Server      | [c68b7991a5](https://linux-hardware.org/?probe=c68b7991a5) | Apr 26, 2021 |
| HP            | 213D A01                    | Desktop     | [72e7e27309](https://linux-hardware.org/?probe=72e7e27309) | Apr 26, 2021 |
| Hyve          | HS-9216Lite2 5411C405005... | Server      | [20edfbf60b](https://linux-hardware.org/?probe=20edfbf60b) | Apr 06, 2021 |
| Gigabyte      | EP43-DS3                    | Desktop     | [3eaab1a9d9](https://linux-hardware.org/?probe=3eaab1a9d9) | Apr 05, 2021 |
| HP            | 8591                        | Desktop     | [d3dd8e0a2b](https://linux-hardware.org/?probe=d3dd8e0a2b) | Apr 02, 2021 |
| Dell          | 0MWYPT A02                  | Desktop     | [e2e2e6f179](https://linux-hardware.org/?probe=e2e2e6f179) | Mar 31, 2021 |
| Cisco Syst... | UCSB-B200-M4 73-15862-03    | Desktop     | [4c55de0b30](https://linux-hardware.org/?probe=4c55de0b30) | Mar 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [b672c68361](https://linux-hardware.org/?probe=b672c68361) | Mar 30, 2021 |
| HP            | 8591                        | Desktop     | [3c4d055665](https://linux-hardware.org/?probe=3c4d055665) | Mar 30, 2021 |
| HP            | 8591                        | Desktop     | [b436577a94](https://linux-hardware.org/?probe=b436577a94) | Mar 30, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c724df2a1a](https://linux-hardware.org/?probe=c724df2a1a) | Mar 23, 2021 |
| MiTAC         | PD10BI PD10BI-702           | Desktop     | [63335e1b88](https://linux-hardware.org/?probe=63335e1b88) | Mar 18, 2021 |
| MiTAC         | PD10BI PD10BI-702           | Desktop     | [5d23375dcd](https://linux-hardware.org/?probe=5d23375dcd) | Mar 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [234c991949](https://linux-hardware.org/?probe=234c991949) | Mar 17, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [72df2af331](https://linux-hardware.org/?probe=72df2af331) | Mar 16, 2021 |
| HP            | 871C                        | All in one  | [2f7fd6200f](https://linux-hardware.org/?probe=2f7fd6200f) | Mar 10, 2021 |
| HP            | 871C                        | All in one  | [7cbfb86cef](https://linux-hardware.org/?probe=7cbfb86cef) | Mar 10, 2021 |
| Dell          | Latitude E7250              | Notebook    | [551399bf55](https://linux-hardware.org/?probe=551399bf55) | Mar 08, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [6663605d82](https://linux-hardware.org/?probe=6663605d82) | Feb 27, 2021 |
| Huawei        | BC82AMDDA V200R002C00       | Server      | [63bdabb5a4](https://linux-hardware.org/?probe=63bdabb5a4) | Feb 26, 2021 |
| AMI           | PCHK-Z83 Poslab_ECO         | Desktop     | [5dd25822e3](https://linux-hardware.org/?probe=5dd25822e3) | Feb 23, 2021 |
| HP            | 81C6 MVB 0C                 | Server      | [9d6e46eca9](https://linux-hardware.org/?probe=9d6e46eca9) | Feb 23, 2021 |
| Gigabyte      | D525TUD                     | Desktop     | [59b1050f5f](https://linux-hardware.org/?probe=59b1050f5f) | Feb 19, 2021 |
| HP            | ProBook 6560b               | Notebook    | [57004cab16](https://linux-hardware.org/?probe=57004cab16) | Feb 17, 2021 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [aab84fafeb](https://linux-hardware.org/?probe=aab84fafeb) | Feb 10, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [9fc9b672d0](https://linux-hardware.org/?probe=9fc9b672d0) | Feb 07, 2021 |
| HP            | 3397                        | Desktop     | [aba05551cb](https://linux-hardware.org/?probe=aba05551cb) | Feb 05, 2021 |
| Intel         | S5000PAL0 FRU Ver           | Server      | [390f15b7f9](https://linux-hardware.org/?probe=390f15b7f9) | Feb 03, 2021 |
| HP            | 8755                        | Mini pc     | [334abf8c53](https://linux-hardware.org/?probe=334abf8c53) | Feb 02, 2021 |
| Lenovo        | ThinkPad T520 4243Y1N       | Notebook    | [66b47b2f1e](https://linux-hardware.org/?probe=66b47b2f1e) | Jan 20, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| Dell          | 0HHV7N A00                  | Desktop     | [7b55587c5a](https://linux-hardware.org/?probe=7b55587c5a) | Jan 10, 2021 |
| Intel         | S1200RP_SE G62252-405       | Server      | [1eaaae85a8](https://linux-hardware.org/?probe=1eaaae85a8) | Jan 04, 2021 |
| Gigabyte      | D525TUD                     | Desktop     | [e9f1445d02](https://linux-hardware.org/?probe=e9f1445d02) | Jan 03, 2021 |
| Intel         | DQ67OW AAG12528-309         | Desktop     | [5f42b365ae](https://linux-hardware.org/?probe=5f42b365ae) | Dec 26, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [aad57f82cd](https://linux-hardware.org/?probe=aad57f82cd) | Dec 24, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [46613a5ce9](https://linux-hardware.org/?probe=46613a5ce9) | Dec 20, 2020 |
| Acer          | Aspire E1-572               | Notebook    | [a06266ed7f](https://linux-hardware.org/?probe=a06266ed7f) | Dec 17, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b7c033babd](https://linux-hardware.org/?probe=b7c033babd) | Dec 10, 2020 |
| Gigabyte      | D525TUD                     | Desktop     | [0c13d73ba0](https://linux-hardware.org/?probe=0c13d73ba0) | Nov 27, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [bc3bd4ea10](https://linux-hardware.org/?probe=bc3bd4ea10) | Nov 24, 2020 |
| Toshiba       | Satellite A135              | Notebook    | [310ddb721f](https://linux-hardware.org/?probe=310ddb721f) | Nov 20, 2020 |
| Lenovo        | ThinkPad X200 7459H92       | Notebook    | [242193b8bc](https://linux-hardware.org/?probe=242193b8bc) | Nov 17, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [ed3c250112](https://linux-hardware.org/?probe=ed3c250112) | Nov 03, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [d3ed1625b0](https://linux-hardware.org/?probe=d3ed1625b0) | Nov 03, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [4cc9a41607](https://linux-hardware.org/?probe=4cc9a41607) | Oct 30, 2020 |
| Dell          | Latitude E6440              | Notebook    | [46a2699a96](https://linux-hardware.org/?probe=46a2699a96) | Oct 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [97a2b45d12](https://linux-hardware.org/?probe=97a2b45d12) | Oct 21, 2020 |
| Dell          | Latitude E6410              | Notebook    | [926bbbdaf2](https://linux-hardware.org/?probe=926bbbdaf2) | Oct 18, 2020 |
| Dell          | Latitude E6410              | Notebook    | [194e7f24f3](https://linux-hardware.org/?probe=194e7f24f3) | Oct 12, 2020 |
| Dell          | 01NP3N A00                  | Desktop     | [1f5b92d91b](https://linux-hardware.org/?probe=1f5b92d91b) | Oct 12, 2020 |
| ASUSTek       | F2A55-M LE                  | Desktop     | [1fc864e04c](https://linux-hardware.org/?probe=1fc864e04c) | Oct 10, 2020 |
| Lenovo        | G500s 20245                 | Notebook    | [8a975cb577](https://linux-hardware.org/?probe=8a975cb577) | Oct 07, 2020 |
| Dell          | Latitude E6410              | Notebook    | [a36dab9e9b](https://linux-hardware.org/?probe=a36dab9e9b) | Oct 06, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| HP            | 0AECh D                     | Desktop     | [d80079cb33](https://linux-hardware.org/?probe=d80079cb33) | Sep 18, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [b363aea94a](https://linux-hardware.org/?probe=b363aea94a) | Sep 17, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [1896a5c345](https://linux-hardware.org/?probe=1896a5c345) | Sep 17, 2020 |
| HP            | ProLiant DL165 G7           | Server      | [91ad975174](https://linux-hardware.org/?probe=91ad975174) | Sep 14, 2020 |
| AEWIN         | SCB-1711A                   | Desktop     | [2d8dbb0d3a](https://linux-hardware.org/?probe=2d8dbb0d3a) | Sep 09, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [233a83b315](https://linux-hardware.org/?probe=233a83b315) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [fcb2182f02](https://linux-hardware.org/?probe=fcb2182f02) | Sep 08, 2020 |
| Unknown       | 34AS1                       | Notebook    | [cc188d0f25](https://linux-hardware.org/?probe=cc188d0f25) | Sep 08, 2020 |
| Unknown       | 34AS1                       | Notebook    | [0ab59553ea](https://linux-hardware.org/?probe=0ab59553ea) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [751df6a75b](https://linux-hardware.org/?probe=751df6a75b) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [14680221b6](https://linux-hardware.org/?probe=14680221b6) | Sep 07, 2020 |
| HP            | EliteBook 6930p             | Notebook    | [8fdba744ec](https://linux-hardware.org/?probe=8fdba744ec) | Sep 03, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [d7700d73c4](https://linux-hardware.org/?probe=d7700d73c4) | Sep 03, 2020 |
| Zenith        | Orion                       | Desktop     | [9de5e32b25](https://linux-hardware.org/?probe=9de5e32b25) | Sep 02, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [599830e150](https://linux-hardware.org/?probe=599830e150) | Aug 29, 2020 |
| ASUSTek       | P7P55D                      | Desktop     | [4a55c3588b](https://linux-hardware.org/?probe=4a55c3588b) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | Desktop     | [09fb692364](https://linux-hardware.org/?probe=09fb692364) | Aug 26, 2020 |
| Supermicro    | X8DT3                       | Server      | [c3337aa815](https://linux-hardware.org/?probe=c3337aa815) | Aug 24, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [c51c0d5538](https://linux-hardware.org/?probe=c51c0d5538) | Aug 15, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [f0d9b71d6d](https://linux-hardware.org/?probe=f0d9b71d6d) | Aug 15, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| Dell          | 08HPGT A02                  | Desktop     | [fa6826d636](https://linux-hardware.org/?probe=fa6826d636) | Aug 02, 2020 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [001888ed9c](https://linux-hardware.org/?probe=001888ed9c) | Aug 02, 2020 |
| Dell          | 0W23H8 A00                  | Server      | [e752263e49](https://linux-hardware.org/?probe=e752263e49) | Jul 27, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [be78e318ef](https://linux-hardware.org/?probe=be78e318ef) | Jul 23, 2020 |
| HP            | 0AECh D                     | Desktop     | [c6310b9606](https://linux-hardware.org/?probe=c6310b9606) | Jul 14, 2020 |
| HP            | 1589                        | Desktop     | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ce6e9cb36](https://linux-hardware.org/?probe=8ce6e9cb36) | Jul 10, 2020 |
| HP            | Falco                       | Notebook    | [26ace050f7](https://linux-hardware.org/?probe=26ace050f7) | Jul 07, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [2a05830be5](https://linux-hardware.org/?probe=2a05830be5) | Jul 05, 2020 |
| Intel         | H81C                        | Desktop     | [54732275c2](https://linux-hardware.org/?probe=54732275c2) | Jul 04, 2020 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [d014e3ba24](https://linux-hardware.org/?probe=d014e3ba24) | Jul 03, 2020 |
| Dell          | 0PYVT1 A03                  | Server      | [b7f3606e31](https://linux-hardware.org/?probe=b7f3606e31) | Jun 30, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [670706063d](https://linux-hardware.org/?probe=670706063d) | Jun 25, 2020 |
| Gigabyte      | P85-D3                      | Desktop     | [3be565ccfd](https://linux-hardware.org/?probe=3be565ccfd) | Jun 23, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [bdaf8406b2](https://linux-hardware.org/?probe=bdaf8406b2) | Jun 22, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [f2bfe6bfb3](https://linux-hardware.org/?probe=f2bfe6bfb3) | Jun 22, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [51b8e4300b](https://linux-hardware.org/?probe=51b8e4300b) | Jun 20, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [e1184552d0](https://linux-hardware.org/?probe=e1184552d0) | Jun 20, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [d78a90c712](https://linux-hardware.org/?probe=d78a90c712) | Jun 18, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [b5360affff](https://linux-hardware.org/?probe=b5360affff) | Jun 18, 2020 |
| Supermicro    | X10DRG-H                    | Desktop     | [3bd676846b](https://linux-hardware.org/?probe=3bd676846b) | Jun 12, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| IBM           | 00W2263                     | Server      | [fc0558920d](https://linux-hardware.org/?probe=fc0558920d) | Jun 01, 2020 |
| Dell          | 0VRWRC A00                  | Desktop     | [dd7e20baec](https://linux-hardware.org/?probe=dd7e20baec) | May 29, 2020 |
| Dell          | 0VRWRC A00                  | Desktop     | [c27987482d](https://linux-hardware.org/?probe=c27987482d) | May 29, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [8f5cbe37da](https://linux-hardware.org/?probe=8f5cbe37da) | May 26, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [396660cc0e](https://linux-hardware.org/?probe=396660cc0e) | May 26, 2020 |
| ASRock        | AM1B-ITX                    | Desktop     | [d0b6f8f474](https://linux-hardware.org/?probe=d0b6f8f474) | May 25, 2020 |
| IBM           | I/O Port                    | Server      | [7c109612b9](https://linux-hardware.org/?probe=7c109612b9) | May 20, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [65921c1a5e](https://linux-hardware.org/?probe=65921c1a5e) | May 14, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [6a3f0afa07](https://linux-hardware.org/?probe=6a3f0afa07) | May 07, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [1f49c0d636](https://linux-hardware.org/?probe=1f49c0d636) | May 06, 2020 |
| Dell          | Latitude E6220              | Notebook    | [a4db1d31a5](https://linux-hardware.org/?probe=a4db1d31a5) | May 05, 2020 |
| Dell          | Latitude E6220              | Notebook    | [c0152a3b02](https://linux-hardware.org/?probe=c0152a3b02) | May 05, 2020 |
| HP            | 1495                        | Desktop     | [a38478daa1](https://linux-hardware.org/?probe=a38478daa1) | May 05, 2020 |
| HP            | 1495                        | Desktop     | [c3d3f31b83](https://linux-hardware.org/?probe=c3d3f31b83) | May 05, 2020 |
| HP            | 1495                        | Desktop     | [6fed1750c3](https://linux-hardware.org/?probe=6fed1750c3) | May 05, 2020 |
| Toshiba       | Satellite Radius 12 P20W... | Notebook    | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [0606d60ddb](https://linux-hardware.org/?probe=0606d60ddb) | Apr 29, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [c4f288077d](https://linux-hardware.org/?probe=c4f288077d) | Apr 29, 2020 |
| Dell          | Precision 7510              | Notebook    | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Supermicro    | H12SSW-NT                   | Server      | [7027370293](https://linux-hardware.org/?probe=7027370293) | Apr 27, 2020 |
| Supermicro    | X10SDE-DF                   | Desktop     | [54cbea6bb1](https://linux-hardware.org/?probe=54cbea6bb1) | Apr 26, 2020 |
| Supermicro    | X10SDE-DF                   | Desktop     | [3c55fe3c77](https://linux-hardware.org/?probe=3c55fe3c77) | Apr 26, 2020 |
| Sony          | VGN-N19VP_B                 | Notebook    | [a2e6c99940](https://linux-hardware.org/?probe=a2e6c99940) | Apr 20, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [942f7d3c3c](https://linux-hardware.org/?probe=942f7d3c3c) | Apr 01, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [fc9be427f5](https://linux-hardware.org/?probe=fc9be427f5) | Apr 01, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| ASRock        | X399 Professional Gaming    | Desktop     | [efe1215f69](https://linux-hardware.org/?probe=efe1215f69) | Mar 19, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c20d28a563](https://linux-hardware.org/?probe=c20d28a563) | Mar 15, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [3086c3b9f5](https://linux-hardware.org/?probe=3086c3b9f5) | Mar 15, 2020 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | Notebook    | [2918602e15](https://linux-hardware.org/?probe=2918602e15) | Mar 12, 2020 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | Notebook    | [8376f889c2](https://linux-hardware.org/?probe=8376f889c2) | Mar 12, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [1345dd63eb](https://linux-hardware.org/?probe=1345dd63eb) | Mar 11, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [6fc52e234a](https://linux-hardware.org/?probe=6fc52e234a) | Mar 09, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [add6bd96c8](https://linux-hardware.org/?probe=add6bd96c8) | Mar 09, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [906db6cad1](https://linux-hardware.org/?probe=906db6cad1) | Mar 09, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d2ab3b608a](https://linux-hardware.org/?probe=d2ab3b608a) | Mar 07, 2020 |
| Dell          | 0X8DXD A01                  | Desktop     | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [ed0506aa18](https://linux-hardware.org/?probe=ed0506aa18) | Feb 25, 2020 |
| Dell          | 0FRVY0 A06                  | Server      | [40545e3bb0](https://linux-hardware.org/?probe=40545e3bb0) | Feb 21, 2020 |
| Dell          | 0CNCJW A05                  | Server      | [c436f9e67a](https://linux-hardware.org/?probe=c436f9e67a) | Feb 21, 2020 |
| Dell          | 0CNCJW A05                  | Server      | [0b376dd32a](https://linux-hardware.org/?probe=0b376dd32a) | Feb 21, 2020 |
| HP            | ZBook 17                    | Notebook    | [5937f48c97](https://linux-hardware.org/?probe=5937f48c97) | Feb 13, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [d45674e336](https://linux-hardware.org/?probe=d45674e336) | Feb 06, 2020 |
| Sony          | VPCSB19GG                   | Notebook    | [cc8806b4ec](https://linux-hardware.org/?probe=cc8806b4ec) | Feb 04, 2020 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [a0fa3c7ca0](https://linux-hardware.org/?probe=a0fa3c7ca0) | Jan 28, 2020 |
| HP            | 18E4                        | Desktop     | [f6f6dfd341](https://linux-hardware.org/?probe=f6f6dfd341) | Jan 25, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [917bf2b4cf](https://linux-hardware.org/?probe=917bf2b4cf) | Jan 24, 2020 |
| Dell          | 0C27VV A01                  | Desktop     | [01545ea8b0](https://linux-hardware.org/?probe=01545ea8b0) | Jan 24, 2020 |
| Dell          | 081N4V A01                  | Server      | [9a09d720c8](https://linux-hardware.org/?probe=9a09d720c8) | Jan 24, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9d92e8ed9d](https://linux-hardware.org/?probe=9d92e8ed9d) | Jan 24, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [21e230fb02](https://linux-hardware.org/?probe=21e230fb02) | Jan 24, 2020 |
| HP            | EliteBook x360 1040 G6      | Notebook    | [7d1585f3cd](https://linux-hardware.org/?probe=7d1585f3cd) | Dec 28, 2019 |
| AIC           | LIBRA                       | Server      | [43ee2001e1](https://linux-hardware.org/?probe=43ee2001e1) | Dec 17, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e795735d5b](https://linux-hardware.org/?probe=e795735d5b) | Dec 14, 2019 |
| Dell          | 0VRJCG A05                  | Server      | [0fc3f83656](https://linux-hardware.org/?probe=0fc3f83656) | Dec 14, 2019 |
| HP            | 0A98h                       | Desktop     | [e68759aa8e](https://linux-hardware.org/?probe=e68759aa8e) | Dec 12, 2019 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [02eca27578](https://linux-hardware.org/?probe=02eca27578) | Dec 05, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| Dell          | XPS L702X                   | Notebook    | [ba096189bc](https://linux-hardware.org/?probe=ba096189bc) | Dec 03, 2019 |
| MSI           | GL63 8SD                    | Notebook    | [3cef0087aa](https://linux-hardware.org/?probe=3cef0087aa) | Dec 01, 2019 |
| Dell          | 09KPNV A01                  | Desktop     | [0c44bfb480](https://linux-hardware.org/?probe=0c44bfb480) | Nov 22, 2019 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [0c5c6bd0d1](https://linux-hardware.org/?probe=0c5c6bd0d1) | Oct 31, 2019 |
| Dell          | Vostro 5568                 | Notebook    | [a0b3e4d70f](https://linux-hardware.org/?probe=a0b3e4d70f) | Oct 16, 2019 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [aa1be9cbec](https://linux-hardware.org/?probe=aa1be9cbec) | Oct 15, 2019 |
| ECS           | H55H-M                      | Desktop     | [970477516c](https://linux-hardware.org/?probe=970477516c) | Oct 12, 2019 |
| ECS           | H55H-M                      | Desktop     | [dab03eeec5](https://linux-hardware.org/?probe=dab03eeec5) | Oct 12, 2019 |
| ASUSTek       | P8H67-M                     | Desktop     | [a3522aac75](https://linux-hardware.org/?probe=a3522aac75) | Oct 09, 2019 |
| ASUSTek       | P8H67-M                     | Desktop     | [1c6a686559](https://linux-hardware.org/?probe=1c6a686559) | Oct 08, 2019 |
| ASUSTek       | P8H67-M                     | Desktop     | [8c40634de7](https://linux-hardware.org/?probe=8c40634de7) | Oct 08, 2019 |
| Supermicro    | X8DTN+-F                    | Server      | [cf99aad395](https://linux-hardware.org/?probe=cf99aad395) | Sep 16, 2019 |
| Supermicro    | X8DTN+-F                    | Server      | [de7268071a](https://linux-hardware.org/?probe=de7268071a) | Sep 16, 2019 |
| Supermicro    | X8DTN+-F                    | Server      | [550719b1d2](https://linux-hardware.org/?probe=550719b1d2) | Sep 16, 2019 |
| HP            | Pavilion 15                 | Notebook    | [7e407e7cd4](https://linux-hardware.org/?probe=7e407e7cd4) | Sep 15, 2019 |
| HP            | Pavilion 15                 | Notebook    | [b2625d7672](https://linux-hardware.org/?probe=b2625d7672) | Sep 15, 2019 |
| HP            | Pavilion 15                 | Notebook    | [447f75484c](https://linux-hardware.org/?probe=447f75484c) | Sep 11, 2019 |
| HP            | Pavilion 15                 | Notebook    | [9352d1efae](https://linux-hardware.org/?probe=9352d1efae) | Sep 11, 2019 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [05d00cc5d7](https://linux-hardware.org/?probe=05d00cc5d7) | Sep 09, 2019 |
| Supermicro    | X8DTL                       | Server      | [f94537400b](https://linux-hardware.org/?probe=f94537400b) | Sep 08, 2019 |
| Gigabyte      | 970A-D3P                    | Desktop     | [6e3666d8c9](https://linux-hardware.org/?probe=6e3666d8c9) | Sep 04, 2019 |
| MSI           | GP62MVR 7RFX                | Notebook    | [5a21834bbd](https://linux-hardware.org/?probe=5a21834bbd) | Sep 01, 2019 |
| Notebook      | WA50SRQ                     | Notebook    | [fd99d2b5e2](https://linux-hardware.org/?probe=fd99d2b5e2) | Aug 09, 2019 |
| AMI           | Cherry Trail CR             | Desktop     | [fe652a02c9](https://linux-hardware.org/?probe=fe652a02c9) | Jul 25, 2019 |
| Dell          | 09KPNV A00                  | Desktop     | [a72c60b73b](https://linux-hardware.org/?probe=a72c60b73b) | Jul 24, 2019 |
| Supermicro    | X8DTL                       | Server      | [e6f0f25fea](https://linux-hardware.org/?probe=e6f0f25fea) | Jul 22, 2019 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [b2fac79afd](https://linux-hardware.org/?probe=b2fac79afd) | Jun 27, 2019 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [44eb4c1fed](https://linux-hardware.org/?probe=44eb4c1fed) | Jun 25, 2019 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [4bb11d6dc0](https://linux-hardware.org/?probe=4bb11d6dc0) | Jun 07, 2019 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [3fb7cc0574](https://linux-hardware.org/?probe=3fb7cc0574) | Jun 07, 2019 |
| AAEON         | MF-001 V1.0                 | Desktop     | [19f89f5d4e](https://linux-hardware.org/?probe=19f89f5d4e) | Jun 05, 2019 |
| HP            | 8054                        | Desktop     | [8409fbc1c6](https://linux-hardware.org/?probe=8409fbc1c6) | May 28, 2019 |
| Intel         | SHARKBAY                    | Desktop     | [8418bef88a](https://linux-hardware.org/?probe=8418bef88a) | May 15, 2019 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [24dd606150](https://linux-hardware.org/?probe=24dd606150) | May 13, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [17bf7a3cbc](https://linux-hardware.org/?probe=17bf7a3cbc) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [57fc9bdf47](https://linux-hardware.org/?probe=57fc9bdf47) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [351f393121](https://linux-hardware.org/?probe=351f393121) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [b3519b05fc](https://linux-hardware.org/?probe=b3519b05fc) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [c6069f57f1](https://linux-hardware.org/?probe=c6069f57f1) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [6c1c564ab7](https://linux-hardware.org/?probe=6c1c564ab7) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [5a96f790b1](https://linux-hardware.org/?probe=5a96f790b1) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [a57a14dcc6](https://linux-hardware.org/?probe=a57a14dcc6) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [f55ae15514](https://linux-hardware.org/?probe=f55ae15514) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [e41c677045](https://linux-hardware.org/?probe=e41c677045) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [add4ffbbb0](https://linux-hardware.org/?probe=add4ffbbb0) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [143a54d4b9](https://linux-hardware.org/?probe=143a54d4b9) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [7b74a423d0](https://linux-hardware.org/?probe=7b74a423d0) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [e31de989f7](https://linux-hardware.org/?probe=e31de989f7) | May 01, 2019 |
| Supermicro    | X10DRW-i                    | Server      | [7d87dd2d1c](https://linux-hardware.org/?probe=7d87dd2d1c) | May 01, 2019 |
| Supermicro    | X10DRT-P                    | Server      | [6c96e4a591](https://linux-hardware.org/?probe=6c96e4a591) | May 01, 2019 |
| Supermicro    | X10DRT-P                    | Server      | [cc949d61be](https://linux-hardware.org/?probe=cc949d61be) | May 01, 2019 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [16ecb5a13f](https://linux-hardware.org/?probe=16ecb5a13f) | Apr 19, 2019 |
| Dell          | Precision M4600             | Notebook    | [9b9a3a238d](https://linux-hardware.org/?probe=9b9a3a238d) | Apr 14, 2019 |
| Dell          | Vostro 5470                 | Notebook    | [e106741644](https://linux-hardware.org/?probe=e106741644) | Apr 10, 2019 |
| Intel         | SHARKBAY                    | Desktop     | [58607accae](https://linux-hardware.org/?probe=58607accae) | Apr 08, 2019 |
| Intel         | SHARKBAY                    | Desktop     | [d8c89a633e](https://linux-hardware.org/?probe=d8c89a633e) | Apr 08, 2019 |
| Intel         | SHARKBAY                    | Desktop     | [5e5b4e25a0](https://linux-hardware.org/?probe=5e5b4e25a0) | Apr 08, 2019 |
| Dell          | 09T7VV A02                  | Server      | [3a05f2f446](https://linux-hardware.org/?probe=3a05f2f446) | Apr 05, 2019 |
| Intel         | NUC6i5SYB H81131-504        | Mini pc     | [97355011d7](https://linux-hardware.org/?probe=97355011d7) | Apr 05, 2019 |
| Supermicro    | X8DTN+-F                    | Server      | [1d3c1dc3bf](https://linux-hardware.org/?probe=1d3c1dc3bf) | Mar 29, 2019 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [f8301ffe57](https://linux-hardware.org/?probe=f8301ffe57) | Mar 26, 2019 |
| ASRock        | Z87 Extreme6                | Desktop     | [96aaa39135](https://linux-hardware.org/?probe=96aaa39135) | Mar 18, 2019 |
| HP            | 81C5 MVB                    | Desktop     | [46ea2e591e](https://linux-hardware.org/?probe=46ea2e591e) | Mar 18, 2019 |
| MSI           | X299 RAIDER                 | Desktop     | [f06f57dde9](https://linux-hardware.org/?probe=f06f57dde9) | Mar 07, 2019 |
| Lenovo        | 4030                        | Desktop     | [10455104fd](https://linux-hardware.org/?probe=10455104fd) | Mar 01, 2019 |
| IBM           | 00W2444 08                  | Server      | [b55f7ae6f3](https://linux-hardware.org/?probe=b55f7ae6f3) | Feb 20, 2019 |
| IBM           | 00W2444 08                  | Server      | [1acfafdc9e](https://linux-hardware.org/?probe=1acfafdc9e) | Feb 20, 2019 |
| ASUSTek       | X540SC                      | Notebook    | [f513215ec6](https://linux-hardware.org/?probe=f513215ec6) | Jan 09, 2019 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9c8b01fc94](https://linux-hardware.org/?probe=9c8b01fc94) | Dec 22, 2018 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3b0d00f6c9](https://linux-hardware.org/?probe=3b0d00f6c9) | Dec 22, 2018 |
| Lenovo        | ThinkPad T440p 20AWS27B0... | Notebook    | [000dae069a](https://linux-hardware.org/?probe=000dae069a) | Oct 31, 2018 |
| Dell          | 0CD6TV A01                  | Desktop     | [7f702ee88f](https://linux-hardware.org/?probe=7f702ee88f) | Oct 29, 2018 |
| Dell          | 0CD6TV A01                  | Desktop     | [46e3d4f4d9](https://linux-hardware.org/?probe=46e3d4f4d9) | Oct 29, 2018 |
| Lenovo        | ThinkPad T530 2394AG6       | Notebook    | [6b8015f1e2](https://linux-hardware.org/?probe=6b8015f1e2) | Oct 26, 2018 |
| Lenovo        | ThinkPad T530 2394AG6       | Notebook    | [c834cadf29](https://linux-hardware.org/?probe=c834cadf29) | Oct 26, 2018 |
| Supermicro    | X10SRi-FB                   | Server      | [eee6327556](https://linux-hardware.org/?probe=eee6327556) | Jul 11, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [73b1be59e6](https://linux-hardware.org/?probe=73b1be59e6) | May 03, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [7b5a78d2db](https://linux-hardware.org/?probe=7b5a78d2db) | May 03, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [6d7db21504](https://linux-hardware.org/?probe=6d7db21504) | May 03, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [7e6e74a11d](https://linux-hardware.org/?probe=7e6e74a11d) | May 03, 2018 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [a5918b30a1](https://linux-hardware.org/?probe=a5918b30a1) | May 01, 2018 |
| Dell          | 0CX0R0 A01                  | Server      | [3f4700f256](https://linux-hardware.org/?probe=3f4700f256) | Jan 29, 2018 |
| HP            | EliteBook 2740p             | Notebook    | [1b72dbb418](https://linux-hardware.org/?probe=1b72dbb418) | Sep 17, 2017 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                               | Computers | Percent |
|---------------------------------------|-----------|---------|
| 3.10.0-862.14.4.el7.x86_64            | 17        | 6.75%   |
| 3.10.0-1160.25.1.el7.x86_64           | 14        | 5.56%   |
| 3.10.0-1160.31.1.el7.x86_64           | 12        | 4.76%   |
| 3.10.0-1062.12.1.el7.x86_64           | 12        | 4.76%   |
| 3.10.0-1160.15.2.el7.x86_64           | 10        | 3.97%   |
| 3.10.0-1127.19.1.el7.x86_64           | 10        | 3.97%   |
| 3.10.0-957.10.1.el7.x86_64            | 9         | 3.57%   |
| 3.10.0-957.1.3.el7.x86_64             | 8         | 3.17%   |
| 3.10.0-1127.el7.x86_64                | 8         | 3.17%   |
| 3.10.0-1062.18.1.el7.x86_64           | 7         | 2.78%   |
| 3.10.0-957.5.1.el7.x86_64             | 6         | 2.38%   |
| 3.10.0-957.27.2.el7.x86_64            | 6         | 2.38%   |
| 3.10.0-1160.11.1.el7.x86_64           | 6         | 2.38%   |
| 3.10.0-1127.10.1.el7.x86_64           | 6         | 2.38%   |
| 3.10.0-1160.6.1.el7.x86_64            | 5         | 1.98%   |
| 3.10.0-1160.36.2.el7.x86_64           | 5         | 1.98%   |
| 3.10.0-1127.13.1.el7.x86_64           | 5         | 1.98%   |
| 3.10.0-1062.9.1.el7.x86_64            | 5         | 1.98%   |
| 3.10.0-957.el7.x86_64                 | 4         | 1.59%   |
| 3.10.0-1160.21.1.el7.x86_64           | 4         | 1.59%   |
| 3.10.0-1062.el7.x86_64                | 4         | 1.59%   |
| 5.4.118-1.el7.elrepo.x86_64           | 3         | 1.19%   |
| 3.10.0-957.12.2.el7.x86_64            | 3         | 1.19%   |
| 3.10.0-1160.45.1.el7.x86_64           | 3         | 1.19%   |
| 3.10.0-1127.8.2.el7.x86_64            | 3         | 1.19%   |
| 3.10.0-1062.4.1.el7.x86_64            | 3         | 1.19%   |
| 3.10.0-1062.1.2.el7.x86_64            | 3         | 1.19%   |
| 3.10.0-1062.1.1.el7.x86_64            | 3         | 1.19%   |
| 3.10.0-957.21.3.el7.x86_64            | 2         | 0.79%   |
| 3.10.0-957.12.1.el7.x86_64            | 2         | 0.79%   |
| 3.10.0-693.21.1.el7.x86_64            | 2         | 0.79%   |
| 3.10.0-693.2.2.el7.x86_64             | 2         | 0.79%   |
| 3.10.0-327.28.3.el7.x86_64            | 2         | 0.79%   |
| 3.10.0-1160.el7.x86_64                | 2         | 0.79%   |
| 3.10.0-1160.42.2.el7.x86_64           | 2         | 0.79%   |
| 3.10.0-1160.24.1.el7.x86_64           | 2         | 0.79%   |
| 3.10.0-1160.2.2.el7.x86_64            | 2         | 0.79%   |
| 3.10.0-1127.18.2.el7.x86_64           | 2         | 0.79%   |
| 3.10.0-1127.18.2.el7.centos.plus.i686 | 2         | 0.79%   |
| 3.10.0-1062.4.3.el7.x86_64            | 2         | 0.79%   |
| 5.8.13-1.el7.elrepo.x86_64            | 1         | 0.4%    |
| 5.8.0-1.el7.elrepo.x86_64             | 1         | 0.4%    |
| 5.7.7-1.el7.elrepo.x86_64             | 1         | 0.4%    |
| 5.7.10-1.el7.elrepo.x86_64            | 1         | 0.4%    |
| 5.6.8-1.el7.elrepo.x86_64             | 1         | 0.4%    |
| 5.6.10-1.el7.elrepo.x86_64            | 1         | 0.4%    |
| 5.5.0-1.el7.elrepo.x86_64             | 1         | 0.4%    |
| 5.4.96-200.el7.x86_64                 | 1         | 0.4%    |
| 5.4.6-1.el7.elrepo.x86_64             | 1         | 0.4%    |
| 5.4.142-1.el7.elrepo.x86_64           | 1         | 0.4%    |
| 5.4.125-200.el7.x86_64                | 1         | 0.4%    |
| 5.4.121-200.el7.x86_64                | 1         | 0.4%    |
| 5.4.119-1.el7.elrepo.x86_64           | 1         | 0.4%    |
| 5.4.113-1.el7.elrepo.x86_64           | 1         | 0.4%    |
| 5.3.11-1.el7.elrepo.x86_64            | 1         | 0.4%    |
| 5.2.13-1.el7.elrepo.x86_64            | 1         | 0.4%    |
| 5.2.1-1.el7.elrepo.x86_64             | 1         | 0.4%    |
| 5.11.0-1.el7.elrepo.x86_64            | 1         | 0.4%    |
| 5.1.19                                | 1         | 0.4%    |
| 4.9.188-35.el7.x86_64                 | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 3.10.0  | 206       | 86.92%  |
| 5.4.118 | 3         | 1.27%   |
| 5.8.13  | 1         | 0.42%   |
| 5.8.0   | 1         | 0.42%   |
| 5.7.7   | 1         | 0.42%   |
| 5.7.10  | 1         | 0.42%   |
| 5.6.8   | 1         | 0.42%   |
| 5.6.10  | 1         | 0.42%   |
| 5.5.0   | 1         | 0.42%   |
| 5.4.96  | 1         | 0.42%   |
| 5.4.6   | 1         | 0.42%   |
| 5.4.142 | 1         | 0.42%   |
| 5.4.125 | 1         | 0.42%   |
| 5.4.121 | 1         | 0.42%   |
| 5.4.119 | 1         | 0.42%   |
| 5.4.113 | 1         | 0.42%   |
| 5.3.11  | 1         | 0.42%   |
| 5.2.13  | 1         | 0.42%   |
| 5.2.1   | 1         | 0.42%   |
| 5.11.0  | 1         | 0.42%   |
| 5.1.19  | 1         | 0.42%   |
| 4.9.188 | 1         | 0.42%   |
| 4.9.182 | 1         | 0.42%   |
| 4.9.180 | 1         | 0.42%   |
| 4.9.179 | 1         | 0.42%   |
| 4.20.8  | 1         | 0.42%   |
| 4.20.4  | 1         | 0.42%   |
| 4.19.8  | 1         | 0.42%   |
| 4.18.6  | 1         | 0.42%   |
| 4.18.0  | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 3.10    | 206       | 87.66%  |
| 5.4     | 9         | 3.83%   |
| 4.9     | 4         | 1.7%    |
| 5.8     | 2         | 0.85%   |
| 5.7     | 2         | 0.85%   |
| 5.6     | 2         | 0.85%   |
| 4.20    | 2         | 0.85%   |
| 4.18    | 2         | 0.85%   |
| 5.5     | 1         | 0.43%   |
| 5.3     | 1         | 0.43%   |
| 5.2     | 1         | 0.43%   |
| 5.11    | 1         | 0.43%   |
| 5.1     | 1         | 0.43%   |
| 4.19    | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 231       | 98.3%   |
| i686    | 3         | 1.28%   |
| aarch64 | 1         | 0.43%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 107       | 45.34%  |
| GNOME         | 70        | 29.66%  |
| KDE4          | 29        | 12.29%  |
| GNOME Classic | 12        | 5.08%   |
| MATE          | 9         | 3.81%   |
| Cinnamon      | 5         | 2.12%   |
| XFCE          | 2         | 0.85%   |
| Xpra          | 1         | 0.42%   |
| KDE           | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 166       | 70.64%  |
| Unknown | 68        | 28.94%  |
| Web     | 1         | 0.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 128       | 54.24%  |
| GDM     | 101       | 42.8%   |
| LightDM | 7         | 2.97%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 81        | 34.18%  |
| Unknown     | 79        | 33.33%  |
| C           | 18        | 7.59%   |
| ru_RU       | 14        | 5.91%   |
| fr_FR       | 6         | 2.53%   |
| en_GB       | 6         | 2.53%   |
| de_AT       | 6         | 2.53%   |
| zh_CN       | 4         | 1.69%   |
| pt_BR       | 4         | 1.69%   |
| en_AU       | 3         | 1.27%   |
| pl_PL       | 2         | 0.84%   |
| es_ES       | 2         | 0.84%   |
| en_US.utf-8 | 2         | 0.84%   |
| en_CA       | 2         | 0.84%   |
| de_DE       | 2         | 0.84%   |
| pt_PT       | 1         | 0.42%   |
| ko_KR       | 1         | 0.42%   |
| ja_JP       | 1         | 0.42%   |
| es_AR       | 1         | 0.42%   |
| en_SG       | 1         | 0.42%   |
| cs_CZ       | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 143       | 60.59%  |
| EFI  | 93        | 39.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 170       | 72.03%  |
| Ext4    | 62        | 26.27%  |
| Overlay | 1         | 0.42%   |
| Ext3    | 1         | 0.42%   |
| Ext2    | 1         | 0.42%   |
| Unknown | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 119       | 50.42%  |
| MBR     | 79        | 33.47%  |
| Unknown | 38        | 16.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 207       | 88.09%  |
| Yes       | 28        | 11.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 213       | 90.25%  |
| Yes       | 23        | 9.75%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 52        | 22.13%  |
| Hewlett-Packard     | 38        | 16.17%  |
| Supermicro          | 30        | 12.77%  |
| ASUSTek Computer    | 23        | 9.79%   |
| Lenovo              | 18        | 7.66%   |
| Gigabyte Technology | 15        | 6.38%   |
| Intel               | 11        | 4.68%   |
| ASRock              | 6         | 2.55%   |
| MSI                 | 5         | 2.13%   |
| IBM                 | 3         | 1.28%   |
| ASRockRack          | 3         | 1.28%   |
| AMI                 | 3         | 1.28%   |
| Unknown             | 3         | 1.28%   |
| Toshiba             | 2         | 0.85%   |
| Sun Microsystems    | 2         | 0.85%   |
| Sony                | 2         | 0.85%   |
| Fujitsu             | 2         | 0.85%   |
| ECS                 | 2         | 0.85%   |
| Zenith              | 1         | 0.43%   |
| Samsung Electronics | 1         | 0.43%   |
| Notebook            | 1         | 0.43%   |
| MiTAC               | 1         | 0.43%   |
| Hyve                | 1         | 0.43%   |
| Huawei              | 1         | 0.43%   |
| Huanan              | 1         | 0.43%   |
| Foxconn             | 1         | 0.43%   |
| eMachines           | 1         | 0.43%   |
| Cisco Systems       | 1         | 0.43%   |
| Apple               | 1         | 0.43%   |
| AIC                 | 1         | 0.43%   |
| AEWIN               | 1         | 0.43%   |
| Acer                | 1         | 0.43%   |
| AAEON               | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Supermicro Super Server                               | 17        | 7.23%   |
| Dell OptiPlex 7040                                    | 8         | 3.4%    |
| Dell OptiPlex 9020                                    | 6         | 2.55%   |
| ASUS All Series                                       | 5         | 2.13%   |
| Supermicro X8DTN+-F                                   | 4         | 1.7%    |
| Dell Precision WorkStation T3500                      | 3         | 1.28%   |
| ASRockRack E3C242D4U2-2T                              | 3         | 1.28%   |
| Unknown                                               | 3         | 1.28%   |
| Supermicro SYS-1028TP-DC1R                            | 2         | 0.85%   |
| Lenovo System x3650 M5: -[8871AC1]-                   | 2         | 0.85%   |
| HP Z420 Workstation                                   | 2         | 0.85%   |
| HP EliteDesk 800 G6 Desktop Mini PC                   | 2         | 0.85%   |
| Fujitsu D3401-H1                                      | 2         | 0.85%   |
| Dell PowerEdge R630                                   | 2         | 0.85%   |
| Dell Inspiron N4050                                   | 2         | 0.85%   |
| Zenith Orion                                          | 1         | 0.43%   |
| Toshiba Satellite Radius 12 P20W-C-106                | 1         | 0.43%   |
| Toshiba Satellite A135                                | 1         | 0.43%   |
| Supermicro X8DTL                                      | 1         | 0.43%   |
| Supermicro X8DT3                                      | 1         | 0.43%   |
| Supermicro SYS-6018R-WTR                              | 1         | 0.43%   |
| Supermicro SYS-5038MD-H24TRF-OS012                    | 1         | 0.43%   |
| Supermicro SYS-5019S-MR                               | 1         | 0.43%   |
| Supermicro SYS-1028GR-TR                              | 1         | 0.43%   |
| Supermicro AS -1014S-WTRT                             | 1         | 0.43%   |
| Sun Microsystems SUN FIRE X2270                       | 1         | 0.43%   |
| Sun Microsystems Sun Fire X2200 M2                    | 1         | 0.43%   |
| Sony VPCSB19GG                                        | 1         | 0.43%   |
| Sony VGN-N19VP_B                                      | 1         | 0.43%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.43%   |
| Notebook WA50SRQ                                      | 1         | 0.43%   |
| MSI MS-7B89                                           | 1         | 0.43%   |
| MSI MS-7A94                                           | 1         | 0.43%   |
| MSI MS-7978                                           | 1         | 0.43%   |
| MSI GP62MVR 7RFX                                      | 1         | 0.43%   |
| MSI GL63 8SD                                          | 1         | 0.43%   |
| MiTAC PD10BI                                          | 1         | 0.43%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.43%   |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]-               | 1         | 0.43%   |
| Lenovo ThinkPad X61s 7667DB2                          | 1         | 0.43%   |
| Lenovo ThinkPad X200 7459ZEJ                          | 1         | 0.43%   |
| Lenovo ThinkPad X200 7459H92                          | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGSA3T00              | 1         | 0.43%   |
| Lenovo ThinkPad T530 2394AG6                          | 1         | 0.43%   |
| Lenovo ThinkPad T520 4243Y1N                          | 1         | 0.43%   |
| Lenovo ThinkPad T440p 20AWS27B0X                      | 1         | 0.43%   |
| Lenovo ThinkPad P53 20QNS00Y00                        | 1         | 0.43%   |
| Lenovo ThinkCentre M920x 10S10013GE                   | 1         | 0.43%   |
| Lenovo ThinkCentre M920q 10RS002YGE                   | 1         | 0.43%   |
| Lenovo IdeaPad 310-15ISK 80UH                         | 1         | 0.43%   |
| Lenovo G500s 20245                                    | 1         | 0.43%   |
| Lenovo 70UB001NEA ThinkServer TS150                   | 1         | 0.43%   |
| Lenovo 70A4000FUX ThinkServer TS140                   | 1         | 0.43%   |
| Intel SHARKBAY                                        | 1         | 0.43%   |
| Intel SandyBridge Platform                            | 1         | 0.43%   |
| Intel S5000PAL                                        | 1         | 0.43%   |
| Intel S1200RP_SE                                      | 1         | 0.43%   |
| Intel NUC8i7BEH                                       | 1         | 0.43%   |
| Intel NUC6i7KYB H90766-405                            | 1         | 0.43%   |
| Intel NUC6i5SYB H81131-504                            | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Dell OptiPlex                      | 19        | 8.09%   |
| Supermicro Super                   | 17        | 7.23%   |
| Dell Precision                     | 10        | 4.26%   |
| Dell PowerEdge                     | 10        | 4.26%   |
| Lenovo ThinkPad                    | 8         | 3.4%    |
| HP EliteDesk                       | 7         | 2.98%   |
| HP EliteBook                       | 5         | 2.13%   |
| Dell Latitude                      | 5         | 2.13%   |
| Dell Inspiron                      | 5         | 2.13%   |
| ASUS All                           | 5         | 2.13%   |
| Supermicro X8DTN+-F                | 4         | 1.7%    |
| HP Compaq                          | 3         | 1.28%   |
| ASUS PRIME                         | 3         | 1.28%   |
| ASRockRack E3C242D4U2-2T           | 3         | 1.28%   |
| Unknown                            | 3         | 1.28%   |
| Toshiba Satellite                  | 2         | 0.85%   |
| Supermicro SYS-1028TP-DC1R         | 2         | 0.85%   |
| Sun Microsystems Sun               | 2         | 0.85%   |
| Lenovo ThinkCentre                 | 2         | 0.85%   |
| Lenovo System                      | 2         | 0.85%   |
| IBM System                         | 2         | 0.85%   |
| HP Z420                            | 2         | 0.85%   |
| HP Z2                              | 2         | 0.85%   |
| HP ProLiant                        | 2         | 0.85%   |
| HP Pavilion                        | 2         | 0.85%   |
| Fujitsu D3401-H1                   | 2         | 0.85%   |
| Dell Vostro                        | 2         | 0.85%   |
| ASUS M5A78L-M                      | 2         | 0.85%   |
| Zenith Orion                       | 1         | 0.43%   |
| Supermicro X8DTL                   | 1         | 0.43%   |
| Supermicro X8DT3                   | 1         | 0.43%   |
| Supermicro SYS-6018R-WTR           | 1         | 0.43%   |
| Supermicro SYS-5038MD-H24TRF-OS012 | 1         | 0.43%   |
| Supermicro SYS-5019S-MR            | 1         | 0.43%   |
| Supermicro SYS-1028GR-TR           | 1         | 0.43%   |
| Supermicro AS                      | 1         | 0.43%   |
| Sony VPCSB19GG                     | 1         | 0.43%   |
| Sony VGN-N19VP                     | 1         | 0.43%   |
| Samsung 300E5EV                    | 1         | 0.43%   |
| Notebook WA50SRQ                   | 1         | 0.43%   |
| MSI MS-7B89                        | 1         | 0.43%   |
| MSI MS-7A94                        | 1         | 0.43%   |
| MSI MS-7978                        | 1         | 0.43%   |
| MSI GP62MVR                        | 1         | 0.43%   |
| MSI GL63                           | 1         | 0.43%   |
| MiTAC PD10BI                       | 1         | 0.43%   |
| Lenovo Y520-15IKBN                 | 1         | 0.43%   |
| Lenovo ThinkSystem                 | 1         | 0.43%   |
| Lenovo IdeaPad                     | 1         | 0.43%   |
| Lenovo G500s                       | 1         | 0.43%   |
| Lenovo 70UB001NEA                  | 1         | 0.43%   |
| Lenovo 70A4000FUX                  | 1         | 0.43%   |
| Intel SHARKBAY                     | 1         | 0.43%   |
| Intel SandyBridge                  | 1         | 0.43%   |
| Intel S5000PAL                     | 1         | 0.43%   |
| Intel S1200RP                      | 1         | 0.43%   |
| Intel NUC8i7BEH                    | 1         | 0.43%   |
| Intel NUC6i7KYB                    | 1         | 0.43%   |
| Intel NUC6i5SYB                    | 1         | 0.43%   |
| Intel NUC6i3SYB                    | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 33        | 14.04%  |
| 2018    | 33        | 14.04%  |
| 2017    | 20        | 8.51%   |
| 2011    | 19        | 8.09%   |
| 2014    | 17        | 7.23%   |
| 2013    | 17        | 7.23%   |
| 2015    | 16        | 6.81%   |
| 2016    | 15        | 6.38%   |
| 2020    | 14        | 5.96%   |
| 2012    | 14        | 5.96%   |
| 2021    | 13        | 5.53%   |
| 2010    | 12        | 5.11%   |
| 2009    | 4         | 1.7%    |
| 2008    | 4         | 1.7%    |
| 2007    | 1         | 0.43%   |
| 2006    | 1         | 0.43%   |
| 2001    | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 117       | 49.79%  |
| Server      | 54        | 22.98%  |
| Notebook    | 50        | 21.28%  |
| Mini pc     | 12        | 5.11%   |
| Convertible | 1         | 0.43%   |
| All in one  | 1         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 234       | 99.57%  |
| Enabled  | 1         | 0.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 233       | 99.15%  |
| Yes  | 2         | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 61        | 25.96%  |
| 32.01-64.0      | 42        | 17.87%  |
| 16.01-24.0      | 33        | 14.04%  |
| More than 256.0 | 26        | 11.06%  |
| 64.01-256.0     | 24        | 10.21%  |
| 3.01-4.0        | 17        | 7.23%   |
| 8.01-16.0       | 15        | 6.38%   |
| 1.01-2.0        | 10        | 4.26%   |
| 24.01-32.0      | 5         | 2.13%   |
| 2.01-3.0        | 1         | 0.43%   |
| 0.51-1.0        | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 47        | 19.18%  |
| 4.01-8.0        | 38        | 15.51%  |
| 0.51-1.0        | 38        | 15.51%  |
| 2.01-3.0        | 37        | 15.1%   |
| 3.01-4.0        | 25        | 10.2%   |
| 8.01-16.0       | 17        | 6.94%   |
| 64.01-256.0     | 15        | 6.12%   |
| 32.01-64.0      | 10        | 4.08%   |
| 0.01-0.5        | 10        | 4.08%   |
| 16.01-24.0      | 4         | 1.63%   |
| 24.01-32.0      | 3         | 1.22%   |
| More than 256.0 | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 105       | 44.12%  |
| 2       | 46        | 19.33%  |
| 3       | 27        | 11.34%  |
| Unknown | 19        | 7.98%   |
| 4       | 12        | 5.04%   |
| 5       | 9         | 3.78%   |
| 6       | 5         | 2.1%    |
| 0       | 3         | 1.26%   |
| 209     | 1         | 0.42%   |
| 68      | 1         | 0.42%   |
| 18      | 1         | 0.42%   |
| 17      | 1         | 0.42%   |
| 15      | 1         | 0.42%   |
| 13      | 1         | 0.42%   |
| 12      | 1         | 0.42%   |
| 11      | 1         | 0.42%   |
| 10      | 1         | 0.42%   |
| 9       | 1         | 0.42%   |
| 8       | 1         | 0.42%   |
| 7       | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 150       | 63.83%  |
| Yes       | 85        | 36.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 231       | 98.3%   |
| No        | 4         | 1.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 158       | 67.23%  |
| Yes       | 77        | 32.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 180       | 76.6%   |
| Yes       | 55        | 23.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 72        | 30.25%  |
| Russia       | 35        | 14.71%  |
| Germany      | 12        | 5.04%   |
| France       | 11        | 4.62%   |
| Brazil       | 11        | 4.62%   |
| UK           | 9         | 3.78%   |
| China        | 9         | 3.78%   |
| Switzerland  | 7         | 2.94%   |
| Canada       | 7         | 2.94%   |
| Australia    | 7         | 2.94%   |
| Belgium      | 5         | 2.1%    |
| Norway       | 4         | 1.68%   |
| Czechia      | 4         | 1.68%   |
| Ukraine      | 3         | 1.26%   |
| Spain        | 3         | 1.26%   |
| South Korea  | 3         | 1.26%   |
| Poland       | 3         | 1.26%   |
| Japan        | 3         | 1.26%   |
| India        | 3         | 1.26%   |
| Finland      | 3         | 1.26%   |
| Sweden       | 2         | 0.84%   |
| Pakistan     | 2         | 0.84%   |
| Israel       | 2         | 0.84%   |
| Taiwan       | 1         | 0.42%   |
| South Africa | 1         | 0.42%   |
| Singapore    | 1         | 0.42%   |
| Romania      | 1         | 0.42%   |
| Portugal     | 1         | 0.42%   |
| Netherlands  | 1         | 0.42%   |
| Mexico       | 1         | 0.42%   |
| Kazakhstan   | 1         | 0.42%   |
| Ireland      | 1         | 0.42%   |
| Iran         | 1         | 0.42%   |
| Hong Kong    | 1         | 0.42%   |
| Greece       | 1         | 0.42%   |
| Ecuador      | 1         | 0.42%   |
| Croatia      | 1         | 0.42%   |
| Chile        | 1         | 0.42%   |
| Bulgaria     | 1         | 0.42%   |
| Argentina    | 1         | 0.42%   |
| Algeria      | 1         | 0.42%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Moscow             | 20        | 8.26%   |
| Rochester          | 18        | 7.44%   |
| Madison            | 17        | 7.02%   |
| Frankfurt am Main  | 6         | 2.48%   |
| Bern               | 5         | 2.07%   |
| St Petersburg      | 4         | 1.65%   |
| London             | 4         | 1.65%   |
| Tampa              | 3         | 1.24%   |
| Sydney             | 3         | 1.24%   |
| Rio de Janeiro     | 3         | 1.24%   |
| Paris              | 3         | 1.24%   |
| Helsinki           | 3         | 1.24%   |
| Brno               | 3         | 1.24%   |
| Victoria           | 2         | 0.83%   |
| S??o Paulo         | 2         | 0.83%   |
| Noisy-le-Grand     | 2         | 0.83%   |
| Melbourne          | 2         | 0.83%   |
| Leuven             | 2         | 0.83%   |
| Kyiv               | 2         | 0.83%   |
| Krasnodar          | 2         | 0.83%   |
| Kongsberg          | 2         | 0.83%   |
| Issaquah           | 2         | 0.83%   |
| Hornsby            | 2         | 0.83%   |
| Guangzhou          | 2         | 0.83%   |
| Brandon            | 2         | 0.83%   |
| Beijing            | 2         | 0.83%   |
| Bad Sassendorf     | 2         | 0.83%   |
| Ashburn            | 2         | 0.83%   |
| Zagreb             | 1         | 0.41%   |
| Yel'tsovka         | 1         | 0.41%   |
| Wuxi               | 1         | 0.41%   |
| Wheeling           | 1         | 0.41%   |
| West Henrietta     | 1         | 0.41%   |
| West Chester       | 1         | 0.41%   |
| Waxhaw             | 1         | 0.41%   |
| Vancouver          | 1         | 0.41%   |
| Universitário     | 1         | 0.41%   |
| Tyumen             | 1         | 0.41%   |
| Tucson             | 1         | 0.41%   |
| Trivandrum         | 1         | 0.41%   |
| Toyama             | 1         | 0.41%   |
| Tours              | 1         | 0.41%   |
| Toronto            | 1         | 0.41%   |
| Tokyo              | 1         | 0.41%   |
| Tel Aviv           | 1         | 0.41%   |
| Tehran             | 1         | 0.41%   |
| Sundbyberg         | 1         | 0.41%   |
| Stockholm          | 1         | 0.41%   |
| Sterling           | 1         | 0.41%   |
| St Andrews         | 1         | 0.41%   |
| Springfield        | 1         | 0.41%   |
| Singapore          | 1         | 0.41%   |
| Shanghai           | 1         | 0.41%   |
| Shakhovskaya       | 1         | 0.41%   |
| Seattle            | 1         | 0.41%   |
| Saratoga Springs   | 1         | 0.41%   |
| Sao Joao de Meriti | 1         | 0.41%   |
| Santiago           | 1         | 0.41%   |
| Santa Luzia        | 1         | 0.41%   |
| San Jose           | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 60        | 192    | 19.48%  |
| WDC                          | 53        | 315    | 17.21%  |
| Samsung Electronics          | 44        | 109    | 14.29%  |
| Toshiba                      | 31        | 47     | 10.06%  |
| Kingston                     | 20        | 22     | 6.49%   |
| Intel                        | 18        | 38     | 5.84%   |
| Hitachi                      | 16        | 22     | 5.19%   |
| SanDisk                      | 8         | 11     | 2.6%    |
| HGST                         | 7         | 39     | 2.27%   |
| Unknown                      | 6         | 11     | 1.95%   |
| Micron Technology            | 5         | 7      | 1.62%   |
| Hewlett-Packard              | 4         | 12     | 1.3%    |
| SPCC                         | 3         | 4      | 0.97%   |
| SK Hynix                     | 3         | 3      | 0.97%   |
| Toshiba America Info Systems | 2         | 2      | 0.65%   |
| SUN                          | 2         | 6      | 0.65%   |
| StoreJet                     | 2         | 2      | 0.65%   |
| OCZ                          | 2         | 3      | 0.65%   |
| NVMe                         | 2         | 2      | 0.65%   |
| LITEONIT                     | 2         | 2      | 0.65%   |
| Crucial                      | 2         | 2      | 0.65%   |
| A-DATA Technology            | 2         | 3      | 0.65%   |
| Transcend                    | 1         | 1      | 0.32%   |
| Smartbuy                     | 1         | 1      | 0.32%   |
| OWC                          | 1         | 1      | 0.32%   |
| Micron/Crucial Technology    | 1         | 1      | 0.32%   |
| MAXTOR                       | 1         | 1      | 0.32%   |
| Lenovo                       | 1         | 2      | 0.32%   |
| KingSpec                     | 1         | 1      | 0.32%   |
| KingDian                     | 1         | 4      | 0.32%   |
| GOODRAM                      | 1         | 1      | 0.32%   |
| GLOWAY                       | 1         | 1      | 0.32%   |
| Fujitsu                      | 1         | 1      | 0.32%   |
| Corsair                      | 1         | 1      | 0.32%   |
| ASMT                         | 1         | 4      | 0.32%   |
| 2.5"                         | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Toshiba DT01ACA050 500GB               | 7         | 1.97%   |
| Seagate ST500DM002-1SB10A 500GB        | 6         | 1.69%   |
| Samsung SSD 860 EVO 250GB              | 5         | 1.41%   |
| WDC WD1003FZEX-00MK2A0 1TB             | 4         | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB         | 4         | 1.13%   |
| Kingston SA400S37240G 240GB SSD        | 4         | 1.13%   |
| Intel SSDSC2BA200G4 200GB              | 4         | 1.13%   |
| Seagate ST2000DM006-2DM164 2TB         | 3         | 0.85%   |
| Kingston SV300S37A120G 120GB SSD       | 3         | 0.85%   |
| WDC WDS250G2B0A-00SM50 250GB SSD       | 2         | 0.56%   |
| WDC WD3200AAKS-75L9A0 320GB            | 2         | 0.56%   |
| WDC WD20EFRX-68EUZN0 2TB               | 2         | 0.56%   |
| WDC WD10EZEX-00BN5A0 1TB               | 2         | 0.56%   |
| Toshiba TR200 240GB SSD                | 2         | 0.56%   |
| Toshiba NVMe SSD Drive 256GB           | 2         | 0.56%   |
| Toshiba DT01ACA200 2TB                 | 2         | 0.56%   |
| SUN COMSTAR 112GB                      | 2         | 0.56%   |
| StoreJet Transcend 240GB               | 2         | 0.56%   |
| SPCC Solid State Disk 64GB             | 2         | 0.56%   |
| Seagate ST600MM0026 600GB              | 2         | 0.56%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 0.56%   |
| Seagate ST2000DM001-1ER164 2TB         | 2         | 0.56%   |
| Seagate ST2000DM001-1CH164 2TB         | 2         | 0.56%   |
| Seagate ST1000NX0423 00AJ142 1TB       | 2         | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB         | 2         | 0.56%   |
| Seagate BUP Slim 2TB                   | 2         | 0.56%   |
| Sandisk WDC CL SN720 SDA 512GB         | 2         | 0.56%   |
| Samsung SSD SM871 2.5 7mm 512GB        | 2         | 0.56%   |
| Samsung SSD 970 512GB                  | 2         | 0.56%   |
| Samsung PM963 2.5" NVMe PCIe SSD 512GB | 2         | 0.56%   |
| Samsung MZVLB1T0 1TB                   | 2         | 0.56%   |
| WDC WUH721816AL5204 16TB               | 1         | 0.28%   |
| WDC WSH722020ALE6L0 20TB               | 1         | 0.28%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.28%   |
| WDC WDS500G2B0A 500GB SSD              | 1         | 0.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.28%   |
| WDC WDS120G1G0A-00SS50 120GB SSD       | 1         | 0.28%   |
| WDC WD80EFAX-68KNBN0 8TB               | 1         | 0.28%   |
| WDC WD7500BPVX-22JC3T0 752GB           | 1         | 0.28%   |
| WDC WD7500BPKX-00HPJT0 752GB           | 1         | 0.28%   |
| WDC WD60EFRX-68L0BN1 6TB               | 1         | 0.28%   |
| WDC WD5003ABYX-01WERA0 500GB           | 1         | 0.28%   |
| WDC WD5000BEVT-80A0RT0 500GB           | 1         | 0.28%   |
| WDC WD5000AZLX-75K2TA0 500GB           | 1         | 0.28%   |
| WDC WD5000AZLX-60K2TA1 500GB           | 1         | 0.28%   |
| WDC WD5000AVCS-632DY1 500GB            | 1         | 0.28%   |
| WDC WD5000AAKX-603CA0 500GB            | 1         | 0.28%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 1         | 0.28%   |
| WDC WD40EZRZ-75GXCB0 4TB               | 1         | 0.28%   |
| WDC WD40EZRX-00SPEB0 4TB               | 1         | 0.28%   |
| WDC WD40EZAZ-00SF3B0 4TB               | 1         | 0.28%   |
| WDC WD3202ABYS-02B7A0 320GB            | 1         | 0.28%   |
| WDC WD3200BPVT-75JJ5T0 320GB           | 1         | 0.28%   |
| WDC WD3200AAKX-753CA0 320GB            | 1         | 0.28%   |
| WDC WD3200AAKX-001CA0 320GB            | 1         | 0.28%   |
| WDC WD30EZRZ-22Z5HB0 3TB               | 1         | 0.28%   |
| WDC WD30EZRZ-00GXCB0 3TB               | 1         | 0.28%   |
| WDC WD30EZRX-00MMMB0 3TB               | 1         | 0.28%   |
| WDC WD30EZRX-00DC0B0 3TB               | 1         | 0.28%   |
| WDC WD2502ABYS-18B7A0 250GB            | 1         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 60        | 192    | 34.68%  |
| WDC                 | 49        | 101    | 28.32%  |
| Toshiba             | 25        | 36     | 14.45%  |
| Hitachi             | 16        | 22     | 9.25%   |
| Samsung Electronics | 7         | 63     | 4.05%   |
| HGST                | 7         | 39     | 4.05%   |
| SUN                 | 2         | 6      | 1.16%   |
| Hewlett-Packard     | 2         | 8      | 1.16%   |
| Unknown             | 1         | 6      | 0.58%   |
| MAXTOR              | 1         | 1      | 0.58%   |
| Lenovo              | 1         | 2      | 0.58%   |
| Fujitsu             | 1         | 1      | 0.58%   |
| ASMT                | 1         | 4      | 0.58%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 28     | 22.86%  |
| Kingston            | 19        | 21     | 18.1%   |
| Intel               | 17        | 37     | 16.19%  |
| WDC                 | 5         | 8      | 4.76%   |
| SanDisk             | 5         | 5      | 4.76%   |
| Micron Technology   | 5         | 7      | 4.76%   |
| Toshiba             | 4         | 8      | 3.81%   |
| SPCC                | 3         | 4      | 2.86%   |
| SK Hynix            | 3         | 3      | 2.86%   |
| StoreJet            | 2         | 2      | 1.9%    |
| OCZ                 | 2         | 3      | 1.9%    |
| LITEONIT            | 2         | 2      | 1.9%    |
| Hewlett-Packard     | 2         | 4      | 1.9%    |
| Crucial             | 2         | 2      | 1.9%    |
| A-DATA Technology   | 2         | 3      | 1.9%    |
| Transcend           | 1         | 1      | 0.95%   |
| Smartbuy            | 1         | 1      | 0.95%   |
| OWC                 | 1         | 1      | 0.95%   |
| KingDian            | 1         | 4      | 0.95%   |
| GOODRAM             | 1         | 1      | 0.95%   |
| GLOWAY              | 1         | 1      | 0.95%   |
| Corsair             | 1         | 1      | 0.95%   |
| 2.5"                | 1         | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 142       | 481    | 52.59%  |
| SSD     | 95        | 148    | 35.19%  |
| NVMe    | 26        | 35     | 9.63%   |
| MMC     | 5         | 5      | 1.85%   |
| Unknown | 2         | 206    | 0.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 185       | 555    | 80.79%  |
| NVMe | 26        | 35     | 11.35%  |
| SAS  | 13        | 280    | 5.68%   |
| MMC  | 5         | 5      | 2.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 134       | 277    | 51.74%  |
| 0.51-1.0   | 67        | 135    | 25.87%  |
| 1.01-2.0   | 24        | 62     | 9.27%   |
| 3.01-4.0   | 13        | 58     | 5.02%   |
| 2.01-3.0   | 8         | 19     | 3.09%   |
| 4.01-10.0  | 8         | 41     | 3.09%   |
| 10.01-20.0 | 5         | 37     | 1.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 48        | 20.17%  |
| 101-250        | 47        | 19.75%  |
| More than 3000 | 43        | 18.07%  |
| 501-1000       | 29        | 12.18%  |
| 1001-2000      | 22        | 9.24%   |
| 51-100         | 14        | 5.88%   |
| 21-50          | 11        | 4.62%   |
| Unknown        | 11        | 4.62%   |
| 1-20           | 8         | 3.36%   |
| 2001-3000      | 5         | 2.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 91        | 38.56%  |
| 101-250        | 28        | 11.86%  |
| 51-100         | 27        | 11.44%  |
| 251-500        | 24        | 10.17%  |
| 21-50          | 18        | 7.63%   |
| 501-1000       | 16        | 6.78%   |
| More than 3000 | 11        | 4.66%   |
| Unknown        | 11        | 4.66%   |
| 1001-2000      | 5         | 2.12%   |
| 2001-3000      | 4         | 1.69%   |
| 0              | 1         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000AVCS-632DY1 500GB                         | 1         | 1      | 2.04%   |
| WDC WD3200AAKS-75L9A0 320GB                         | 1         | 1      | 2.04%   |
| WDC WD2500HHTZ-04N21V0 250GB                        | 1         | 1      | 2.04%   |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 1      | 2.04%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 2      | 2.04%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 1      | 2.04%   |
| WDC WD10EZEX-60WN4A1 1TB                            | 1         | 1      | 2.04%   |
| WDC WD10EADS-00L5B1 1TB                             | 1         | 1      | 2.04%   |
| WDC WD1001FALS-00J7B1 1TB                           | 1         | 1      | 2.04%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 2.04%   |
| Toshiba MK8032GSX 80GB                              | 1         | 1      | 2.04%   |
| Smartbuy SSD 120GB                                  | 1         | 1      | 2.04%   |
| SK Hynix SC210 mSATA 256GB SSD                      | 1         | 1      | 2.04%   |
| Seagate ST380211AS 80GB                             | 1         | 1      | 2.04%   |
| Seagate ST380013AS 80GB                             | 1         | 1      | 2.04%   |
| Seagate ST3250620NS 250GB                           | 1         | 2      | 2.04%   |
| Seagate ST3160813AS 160GB                           | 1         | 1      | 2.04%   |
| Seagate ST31000524NS 1TB                            | 1         | 1      | 2.04%   |
| Seagate ST31000340AS 1TB                            | 1         | 1      | 2.04%   |
| Seagate ST2000DM001-9YN164 2TB                      | 1         | 1      | 2.04%   |
| Seagate ST1000NX0313 1TB                            | 1         | 1      | 2.04%   |
| SanDisk SDSSDX240GG25 240GB                         | 1         | 1      | 2.04%   |
| Samsung Electronics SSD SM871 2.5 7mm 512GB         | 1         | 1      | 2.04%   |
| Samsung Electronics HD154UI 1TB                     | 1         | 1      | 2.04%   |
| Samsung Electronics HD103UI 1TB                     | 1         | 1      | 2.04%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 2.04%   |
| Micron Technology 1100 SATA 256GB SSD               | 1         | 1      | 2.04%   |
| MAXTOR 6Y080L0 82GB                                 | 1         | 1      | 2.04%   |
| LITEONIT LSS-16L6G-HP 16GB SSD                      | 1         | 1      | 2.04%   |
| LITEONIT LCT-256M3S 256GB SSD                       | 1         | 1      | 2.04%   |
| Kingston SV100S264G 64GB SSD                        | 1         | 1      | 2.04%   |
| Kingston SNS4151S316G 16GB SSD                      | 1         | 1      | 2.04%   |
| Kingston SHFS37A120G 120GB SSD                      | 1         | 1      | 2.04%   |
| Intel SSDSC2KW240H6 240GB                           | 1         | 1      | 2.04%   |
| Intel SSDSC2KW180H6 180GB                           | 1         | 1      | 2.04%   |
| Intel SSDSC2BX400G4R 400GB                          | 1         | 2      | 2.04%   |
| Intel SSDSC2BB300G4R 304GB                          | 1         | 2      | 2.04%   |
| Intel SSDSA2M120G2GC 120GB                          | 1         | 1      | 2.04%   |
| Intel SSDSA2M080G2LE 80GB                           | 1         | 11     | 2.04%   |
| Hitachi HTS727575A9E364 752GB                       | 1         | 1      | 2.04%   |
| Hitachi HTS542512K9A300 120GB                       | 1         | 1      | 2.04%   |
| Hitachi HTS541680J9SA00 80GB                        | 1         | 1      | 2.04%   |
| Hitachi HDS728080PLA380 82GB                        | 1         | 1      | 2.04%   |
| Hitachi HDS7225SBSUN250G 0632NLKRTJ 250GB           | 1         | 1      | 2.04%   |
| Hitachi HDS721050CLA660 500GB                       | 1         | 1      | 2.04%   |
| HGST HDN726060ALE610 6TB                            | 1         | 1      | 2.04%   |
| Hewlett-Packard VB0160EAVEQ 160GB                   | 1         | 1      | 2.04%   |
| Crucial CT480M500SSD1 480GB                         | 1         | 1      | 2.04%   |
| A-DATA Technology SP900NS38 256GB SSD               | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 18.37%  |
| Seagate             | 8         | 9      | 16.33%  |
| Intel               | 6         | 18     | 12.24%  |
| Hitachi             | 6         | 6      | 12.24%  |
| Samsung Electronics | 3         | 3      | 6.12%   |
| Kingston            | 3         | 3      | 6.12%   |
| Toshiba             | 2         | 2      | 4.08%   |
| Micron Technology   | 2         | 2      | 4.08%   |
| LITEONIT            | 2         | 2      | 4.08%   |
| Smartbuy            | 1         | 1      | 2.04%   |
| SK Hynix            | 1         | 1      | 2.04%   |
| SanDisk             | 1         | 1      | 2.04%   |
| MAXTOR              | 1         | 1      | 2.04%   |
| HGST                | 1         | 1      | 2.04%   |
| Hewlett-Packard     | 1         | 1      | 2.04%   |
| Crucial             | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 30%     |
| Seagate             | 8         | 9      | 26.67%  |
| Hitachi             | 6         | 6      | 20%     |
| Toshiba             | 2         | 2      | 6.67%   |
| Samsung Electronics | 2         | 2      | 6.67%   |
| MAXTOR              | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 32     | 56.82%  |
| SSD  | 19        | 31     | 43.18%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 144       | 433    | 60%     |
| Detected | 55        | 379    | 22.92%  |
| Malfunc  | 41        | 63     | 17.08%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 192       | 62.14%  |
| LSI Logic / Symbios Logic        | 28        | 9.06%   |
| AMD                              | 21        | 6.8%    |
| Samsung Electronics              | 15        | 4.85%   |
| Broadcom / LSI                   | 14        | 4.53%   |
| ASMedia Technology               | 8         | 2.59%   |
| Toshiba America Info Systems     | 4         | 1.29%   |
| Sandisk                          | 4         | 1.29%   |
| Marvell Technology Group         | 4         | 1.29%   |
| JMicron Technology               | 4         | 1.29%   |
| Nvidia                           | 3         | 0.97%   |
| Adaptec                          | 3         | 0.97%   |
| VIA Technologies                 | 1         | 0.32%   |
| SK Hynix                         | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| Silicon Image                    | 1         | 0.32%   |
| Micron/Crucial Technology        | 1         | 0.32%   |
| KIOXIA                           | 1         | 0.32%   |
| Kingston Technology Company      | 1         | 0.32%   |
| Huawei Technologies              | 1         | 0.32%   |
| Hewlett-Packard                  | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 23        | 5.96%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 21        | 5.44%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                                 | 19        | 4.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19        | 4.92%   |
| Intel SATA Controller [RAID mode]                                                       | 13        | 3.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12        | 3.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 11        | 2.85%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 11        | 2.85%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 11        | 2.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 2.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 2.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 8         | 2.07%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8         | 2.07%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6         | 1.55%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 6         | 1.55%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 5         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.3%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 4         | 1.04%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 4         | 1.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.04%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 3         | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3         | 0.78%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 3         | 0.78%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 3         | 0.78%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 3         | 0.78%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3         | 0.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 0.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.78%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 3         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 0.78%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 0.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.52%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.52%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                        | 2         | 0.52%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2208 [Thunderbolt]                               | 2         | 0.52%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 0.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 0.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 0.52%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                                | 2         | 0.52%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                                | 2         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.52%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 0.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.52%   |
| Intel 631xESB/632xESB SATA RAID Controller                                              | 2         | 0.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 0.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 0.52%   |
| AMD FCH IDE Controller                                                                  | 2         | 0.52%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.26%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.26%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 166       | 52.04%  |
| RAID | 72        | 22.57%  |
| IDE  | 39        | 12.23%  |
| NVMe | 27        | 8.46%   |
| SAS  | 10        | 3.13%   |
| SCSI | 5         | 1.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 213       | 90.64%  |
| AMD     | 21        | 8.94%   |
| Unknown | 1         | 0.43%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2630 v4 @ 2.20GHz  | 17        | 7.23%   |
| Intel Core i7-6700 CPU @ 3.40GHz     | 11        | 4.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz     | 7         | 2.98%   |
| Intel Xeon CPU X5650 @ 2.67GHz       | 6         | 2.55%   |
| Intel Xeon E-2136 CPU @ 3.30GHz      | 3         | 1.28%   |
| Intel Xeon CPU E5620 @ 2.40GHz       | 3         | 1.28%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 3         | 1.28%   |
| Intel Core i3-6100U CPU @ 2.30GHz    | 3         | 1.28%   |
| Intel Xeon W-1290 CPU @ 3.20GHz      | 2         | 0.85%   |
| Intel Xeon CPU W3530 @ 2.80GHz       | 2         | 0.85%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz  | 2         | 0.85%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz  | 2         | 0.85%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz   | 2         | 0.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz     | 2         | 0.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2         | 0.85%   |
| Intel Core i5-9500 CPU @ 3.00GHz     | 2         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 2         | 0.85%   |
| Intel Core i5-10500 CPU @ 3.10GHz    | 2         | 0.85%   |
| Intel Core i5 CPU M 560 @ 2.67GHz    | 2         | 0.85%   |
| Intel Core i3-3120M CPU @ 2.50GHz    | 2         | 0.85%   |
| Intel Core i3-2330M CPU @ 2.20GHz    | 2         | 0.85%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 2         | 0.85%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz | 2         | 0.85%   |
| Intel Celeron CPU J1900 @ 1.99GHz    | 2         | 0.85%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz    | 2         | 0.85%   |
| Intel Atom CPU D525 @ 1.80GHz        | 2         | 0.85%   |
| AMD Ryzen 5 1600 Six-Core Processor  | 2         | 0.85%   |
| AMD FX-6300 Six-Core Processor       | 2         | 0.85%   |
| Intel Xeon W-2155 CPU @ 3.30GHz      | 1         | 0.43%   |
| Intel Xeon W-2125 CPU @ 4.00GHz      | 1         | 0.43%   |
| Intel Xeon Silver 4116 CPU @ 2.10GHz | 1         | 0.43%   |
| Intel Xeon Gold 6248 CPU @ 2.50GHz   | 1         | 0.43%   |
| Intel Xeon Gold 6139 CPU @ 2.30GHz   | 1         | 0.43%   |
| Intel Xeon Gold 6134 CPU @ 3.20GHz   | 1         | 0.43%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz   | 1         | 0.43%   |
| Intel Xeon CPU X5680 @ 3.33GHz       | 1         | 0.43%   |
| Intel Xeon CPU X5450 @ 3.00GHz       | 1         | 0.43%   |
| Intel Xeon CPU L5420 @ 2.50GHz       | 1         | 0.43%   |
| Intel Xeon CPU E5506 @ 2.13GHz       | 1         | 0.43%   |
| Intel Xeon CPU E5504 @ 2.00GHz       | 1         | 0.43%   |
| Intel Xeon CPU E5440 @ 2.83GHz       | 1         | 0.43%   |
| Intel Xeon CPU E5430 @ 2.66GHz       | 1         | 0.43%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz | 1         | 0.43%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz  | 1         | 0.43%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz  | 1         | 0.43%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz  | 1         | 0.43%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz   | 1         | 0.43%   |
| Intel Xeon CPU E5-2687W v3 @ 3.10GHz | 1         | 0.43%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz  | 1         | 0.43%   |
| Intel Xeon CPU E5-2650 v4 @ 2.20GHz  | 1         | 0.43%   |
| Intel Xeon CPU E5-2643 v3 @ 3.40GHz  | 1         | 0.43%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz   | 1         | 0.43%   |
| Intel Xeon CPU E5-2407 v2 @ 2.40GHz  | 1         | 0.43%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz   | 1         | 0.43%   |
| Intel Xeon CPU E5-1607 0 @ 3.00GHz   | 1         | 0.43%   |
| Intel Xeon CPU E31270 @ 3.40GHz      | 1         | 0.43%   |
| Intel Xeon CPU E31220 @ 3.10GHz      | 1         | 0.43%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz  | 1         | 0.43%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz  | 1         | 0.43%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz  | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Xeon              | 69        | 29.36%  |
| Intel Core i7           | 51        | 21.7%   |
| Intel Core i5           | 34        | 14.47%  |
| Intel Core i3           | 18        | 7.66%   |
| Intel Core 2 Duo        | 9         | 3.83%   |
| Intel Pentium           | 7         | 2.98%   |
| Intel Atom              | 6         | 2.55%   |
| AMD FX                  | 5         | 2.13%   |
| Intel Xeon Gold         | 4         | 1.7%    |
| Intel Core i9           | 4         | 1.7%    |
| Intel Celeron           | 4         | 1.7%    |
| AMD Ryzen 5             | 4         | 1.7%    |
| Other                   | 2         | 0.85%   |
| Intel Genuine           | 2         | 0.85%   |
| Intel Core 2 Quad       | 2         | 0.85%   |
| AMD EPYC                | 2         | 0.85%   |
| Intel Xeon Silver       | 1         | 0.43%   |
| Intel Pentium Dual-Core | 1         | 0.43%   |
| Intel Pentium 4         | 1         | 0.43%   |
| AMD Ryzen Threadripper  | 1         | 0.43%   |
| AMD Ryzen 7             | 1         | 0.43%   |
| AMD Phenom II X6        | 1         | 0.43%   |
| AMD Opteron             | 1         | 0.43%   |
| AMD GX                  | 1         | 0.43%   |
| AMD E2                  | 1         | 0.43%   |
| AMD Athlon              | 1         | 0.43%   |
| AMD A8                  | 1         | 0.43%   |
| AMD A10                 | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 81        | 34.47%  |
| 2      | 59        | 25.11%  |
| 6      | 24        | 10.21%  |
| 20     | 21        | 8.94%   |
| 8      | 14        | 5.96%   |
| 12     | 10        | 4.26%   |
| 16     | 6         | 2.55%   |
| 10     | 4         | 1.7%    |
| 3      | 3         | 1.28%   |
| 1      | 3         | 1.28%   |
| 32     | 2         | 0.85%   |
| 24     | 2         | 0.85%   |
| 96     | 1         | 0.43%   |
| 48     | 1         | 0.43%   |
| 40     | 1         | 0.43%   |
| 36     | 1         | 0.43%   |
| 28     | 1         | 0.43%   |
| 14     | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 185       | 78.72%  |
| 2      | 49        | 20.85%  |
| 0      | 1         | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 164       | 69.79%  |
| 1      | 71        | 30.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 219       | 93.19%  |
| Unknown        | 13        | 5.53%   |
| 32-bit         | 3         | 1.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 12.13%  |
| 0x306c3    | 22        | 9.21%   |
| 0x506e3    | 18        | 7.53%   |
| 0x406f1    | 18        | 7.53%   |
| 0x206a7    | 18        | 7.53%   |
| 0x906ea    | 10        | 4.18%   |
| 0x306a9    | 10        | 4.18%   |
| 0x306f2    | 8         | 3.35%   |
| 0x1067a    | 8         | 3.35%   |
| 0x206c2    | 7         | 2.93%   |
| 0x40651    | 6         | 2.51%   |
| 0x50654    | 5         | 2.09%   |
| 0x206d7    | 5         | 2.09%   |
| 0xa0655    | 4         | 1.67%   |
| 0x906e9    | 4         | 1.67%   |
| 0x806ea    | 4         | 1.67%   |
| 0x106a5    | 4         | 1.67%   |
| 0x06000852 | 4         | 1.67%   |
| 0xa0653    | 3         | 1.26%   |
| 0x906ed    | 3         | 1.26%   |
| 0x806e9    | 3         | 1.26%   |
| 0x406e3    | 3         | 1.26%   |
| 0x406c4    | 3         | 1.26%   |
| 0x20655    | 3         | 1.26%   |
| 0x106e5    | 3         | 1.26%   |
| 0x106ca    | 3         | 1.26%   |
| 0x10676    | 3         | 1.26%   |
| 0x6fb      | 2         | 0.84%   |
| 0x406c3    | 2         | 0.84%   |
| 0x306e4    | 2         | 0.84%   |
| 0x30678    | 2         | 0.84%   |
| 0x08701013 | 2         | 0.84%   |
| 0x08301034 | 2         | 0.84%   |
| 0x03000027 | 2         | 0.84%   |
| 0xf24      | 1         | 0.42%   |
| 0xa0660    | 1         | 0.42%   |
| 0x806ec    | 1         | 0.42%   |
| 0x6ec      | 1         | 0.42%   |
| 0x6e8      | 1         | 0.42%   |
| 0x306d4    | 1         | 0.42%   |
| 0x0800820d | 1         | 0.42%   |
| 0x0800820b | 1         | 0.42%   |
| 0x08001137 | 1         | 0.42%   |
| 0x0700010f | 1         | 0.42%   |
| 0x06001119 | 1         | 0.42%   |
| 0x0600084f | 1         | 0.42%   |
| 0x010000dc | 1         | 0.42%   |
| 0x010000d9 | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Haswell     | 37        | 15.74%  |
| Skylake     | 33        | 14.04%  |
| SandyBridge | 25        | 10.64%  |
| KabyLake    | 25        | 10.64%  |
| Broadwell   | 24        | 10.21%  |
| Penryn      | 14        | 5.96%   |
| Westmere    | 13        | 5.53%   |
| IvyBridge   | 12        | 5.11%   |
| CometLake   | 8         | 3.4%    |
| Silvermont  | 7         | 2.98%   |
| Nehalem     | 7         | 2.98%   |
| Piledriver  | 6         | 2.55%   |
| Zen 2       | 5         | 2.13%   |
| Bonnell     | 3         | 1.28%   |
| Zen+        | 2         | 0.85%   |
| P6          | 2         | 0.85%   |
| K10 Llano   | 2         | 0.85%   |
| K10         | 2         | 0.85%   |
| Jaguar      | 2         | 0.85%   |
| Core        | 2         | 0.85%   |
| Zen         | 1         | 0.43%   |
| NetBurst    | 1         | 0.43%   |
| K8 Hammer   | 1         | 0.43%   |
| Unknown     | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 101       | 39.45%  |
| Nvidia                                       | 49        | 19.14%  |
| AMD                                          | 46        | 17.97%  |
| ASPEED Technology                            | 31        | 12.11%  |
| Matrox Electronics Systems                   | 25        | 9.77%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.39%   |
| Silicon Motion                               | 1         | 0.39%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.39%   |
| Huawei Technologies                          | 1         | 0.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 31        | 11.88%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 4.6%    |
| Matrox Electronics Systems G200eR2                                                       | 10        | 3.83%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 9         | 3.45%   |
| Intel HD Graphics 530                                                                    | 9         | 3.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 9         | 3.45%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 8         | 3.07%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 7         | 2.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 1.92%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 4         | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.53%   |
| Nvidia GP107GL [Quadro P400]                                                             | 3         | 1.15%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.15%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.15%   |
| Nvidia GP106GL [Quadro P2000]                                                            | 2         | 0.77%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 2         | 0.77%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 0.77%   |
| Intel UHD P630 Graphics                                                                  | 2         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.77%   |
| Intel HD Graphics 630                                                                    | 2         | 0.77%   |
| Intel HD Graphics 620                                                                    | 2         | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.77%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.77%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 0.77%   |
| AMD ES1000                                                                               | 2         | 0.77%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)                           | 1         | 0.38%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 0.38%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                | 1         | 0.38%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.38%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                                         | 1         | 0.38%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1         | 0.38%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.38%   |
| Nvidia TU102 [TITAN RTX]                                                                 | 1         | 0.38%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 1         | 0.38%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.38%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.38%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.38%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1         | 0.38%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.38%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.38%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.38%   |
| Nvidia GP106GL [Quadro P2200]                                                            | 1         | 0.38%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.38%   |
| Nvidia GP104GL [Quadro P4000]                                                            | 1         | 0.38%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.38%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 80        | 34.04%  |
| 1 x AMD                 | 38        | 16.17%  |
| 1 x Nvidia              | 37        | 15.74%  |
| 1 x ASPEED              | 30        | 12.77%  |
| 1 x Matrox              | 25        | 10.64%  |
| Intel + Nvidia          | 10        | 4.26%   |
| Intel + AMD             | 7         | 2.98%   |
| Other                   | 1         | 0.43%   |
| 2 x Nvidia              | 1         | 0.43%   |
| 2 x AMD                 | 1         | 0.43%   |
| 1 x XGI                 | 1         | 0.43%   |
| 1 x SiS                 | 1         | 0.43%   |
| 1 x Silicon Motion      | 1         | 0.43%   |
| Nvidia + ASPEED         | 1         | 0.43%   |
| 1 x Huawei Technologies | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 186       | 79.15%  |
| Unknown     | 25        | 10.64%  |
| Proprietary | 24        | 10.21%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 144       | 61.28%  |
| 1.01-2.0   | 28        | 11.91%  |
| 0.51-1.0   | 25        | 10.64%  |
| 0.01-0.5   | 12        | 5.11%   |
| 7.01-8.0   | 9         | 3.83%   |
| 3.01-4.0   | 9         | 3.83%   |
| 4.01-5.0   | 3         | 1.28%   |
| 5.01-6.0   | 2         | 0.85%   |
| 2.01-3.0   | 2         | 0.85%   |
| 16.01-24.0 | 1         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 47        | 26.4%   |
| Samsung Electronics     | 19        | 10.67%  |
| Hewlett-Packard         | 14        | 7.87%   |
| LG Display              | 11        | 6.18%   |
| Goldstar                | 10        | 5.62%   |
| Chimei Innolux          | 9         | 5.06%   |
| AU Optronics            | 9         | 5.06%   |
| Acer                    | 9         | 5.06%   |
| Lenovo                  | 7         | 3.93%   |
| Philips                 | 4         | 2.25%   |
| BOE                     | 4         | 2.25%   |
| AOC                     | 4         | 2.25%   |
| BenQ                    | 3         | 1.69%   |
| Ancor Communications    | 3         | 1.69%   |
| NEC Computers           | 2         | 1.12%   |
| InnoLux Display         | 2         | 1.12%   |
| ___                     | 1         | 0.56%   |
| Westinghouse            | 1         | 0.56%   |
| ViewSonic               | 1         | 0.56%   |
| Unknown                 | 1         | 0.56%   |
| Sony                    | 1         | 0.56%   |
| Sharp                   | 1         | 0.56%   |
| Pixio                   | 1         | 0.56%   |
| PEP                     | 1         | 0.56%   |
| Packard Bell            | 1         | 0.56%   |
| NME                     | 1         | 0.56%   |
| MIT                     | 1         | 0.56%   |
| LG Philips              | 1         | 0.56%   |
| Insignia                | 1         | 0.56%   |
| HPN                     | 1         | 0.56%   |
| GVV                     | 1         | 0.56%   |
| Founder                 | 1         | 0.56%   |
| Eizo                    | 1         | 0.56%   |
| CHR                     | 1         | 0.56%   |
| Chi Mei Optoelectronics | 1         | 0.56%   |
| Apple                   | 1         | 0.56%   |
| AMW                     | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                                     | 6         | 3.13%   |
| Dell P2414H DELA09A 1920x1080 527x297mm 23.8-inch                                     | 6         | 3.13%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                                     | 6         | 3.13%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 410x260mm 19.1-inch                   | 2         | 1.04%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch                           | 2         | 1.04%   |
| InnoLux Display LCD Monitor INL0014 1366x768 309x174mm 14.0-inch                      | 2         | 1.04%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch                         | 2         | 1.04%   |
| Hewlett-Packard Z32x HWP3275 3840x2160 697x392mm 31.5-inch                            | 2         | 1.04%   |
| Dell P2417H DELA0DA 1920x1080 527x296mm 23.8-inch                                     | 2         | 1.04%   |
| BenQ GW2765 BNQ78D6 1920x1080 600x340mm 27.2-inch                                     | 2         | 1.04%   |
| ___ Monitor ranges (GTF): 48-62Hz V, 14-68kHz H, max dotclock 150MHz ___9000 1440x900 | 1         | 0.52%   |
| Westinghouse LD-2240 WDT19DA 1920x1080 480x270mm 21.7-inch                            | 1         | 0.52%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 495x291mm 22.6-inch                             | 1         | 0.52%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                                    | 1         | 0.52%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                                    | 1         | 0.52%   |
| Sharp LCD Monitor SHP144D 3840x2160 276x156mm 12.5-inch                               | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM05C7 1920x1080 521x293mm 23.5-inch                  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM04DD 1920x1080 477x268mm 21.5-inch                  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch                  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch                  | 1         | 0.52%   |
| Samsung Electronics SMBX2350 SAM071E 1920x1080 509x286mm 23.0-inch                    | 1         | 0.52%   |
| Samsung Electronics SA300/SA350 SAM078E 1680x1050 480x270mm 21.7-inch                 | 1         | 0.52%   |
| Samsung Electronics S27E391 SAM0C16 1920x1080 600x340mm 27.2-inch                     | 1         | 0.52%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch                     | 1         | 0.52%   |
| Samsung Electronics S22C300 SAM0A20 1920x1080 477x268mm 21.5-inch                     | 1         | 0.52%   |
| Samsung Electronics S22C300 SAM0A1E 1920x1080 477x268mm 21.5-inch                     | 1         | 0.52%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 443x249mm 20.0-inch                      | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch                  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch                  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch                  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch                  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch                  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor C27F591 1440x900                                      | 1         | 0.52%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch                     | 1         | 0.52%   |
| Pixio HDMI ICB270A 1280x800 368x207mm 16.6-inch                                       | 1         | 0.52%   |
| Philips PHL 284E5 PHLC0DE 1920x1080 621x341mm 27.9-inch                               | 1         | 0.52%   |
| Philips LCD Monitor PHLC081 1920x1080 480x270mm 21.7-inch                             | 1         | 0.52%   |
| Philips 196V4 PHLC0AF 1366x768 410x230mm 18.5-inch                                    | 1         | 0.52%   |
| Philips 190S PHL083F 1280x1024 376x301mm 19.0-inch                                    | 1         | 0.52%   |
| PEP KIRA PEP0001 1600x1200 376x301mm 19.0-inch                                        | 1         | 0.52%   |
| Packard Bell Viseo223DX PKB0385 1920x1080 477x268mm 21.5-inch                         | 1         | 0.52%   |
| NME 202M NME1021 1680x1050 380x290mm 18.8-inch                                        | 1         | 0.52%   |
| NEC Computers LCD2190UXi NEC66B2 1600x1200 432x324mm 21.3-inch                        | 1         | 0.52%   |
| NEC Computers EA261WM NEC6750 1920x1200 560x350mm 26.0-inch                           | 1         | 0.52%   |
| MIT LCD Monitor MIT2011 3840x2160 1150x650mm 52.0-inch                                | 1         | 0.52%   |
| MIT HDMI Analyzer MIT2011 3840x2160 800x450mm 36.1-inch                               | 1         | 0.52%   |
| LG Philips LCD Monitor LPLC700 1280x800 331x207mm 15.4-inch                           | 1         | 0.52%   |
| LG Display LCD Monitor LGD6616 1366x768 277x156mm 12.5-inch                           | 1         | 0.52%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch                           | 1         | 0.52%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch                           | 1         | 0.52%   |
| LG Display LCD Monitor LGD0450 1366x768 277x156mm 12.5-inch                           | 1         | 0.52%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch                           | 1         | 0.52%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch                          | 1         | 0.52%   |
| LG Display LCD Monitor LGD02FC 1920x1080 380x210mm 17.1-inch                          | 1         | 0.52%   |
| LG Display LCD Monitor LGD02D9 1920x1080 350x190mm 15.7-inch                          | 1         | 0.52%   |
| LG Display LCD Monitor LGD02C5 1920x1080 380x210mm 17.1-inch                          | 1         | 0.52%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                                  | 1         | 0.52%   |
| Lenovo LEN E2224A LEN60DA 1920x1080 477x268mm 21.5-inch                               | 1         | 0.52%   |
| Lenovo LEN E2054A LEN60DF 1440x900 419x262mm 19.5-inch                                | 1         | 0.52%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                               | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 74        | 41.81%  |
| 1366x768 (WXGA)    | 24        | 13.56%  |
| 1280x1024 (SXGA)   | 15        | 8.47%   |
| 1440x900 (WXGA+)   | 10        | 5.65%   |
| 3840x2160 (4K)     | 7         | 3.95%   |
| 2560x1440 (QHD)    | 7         | 3.95%   |
| 1280x800 (WXGA)    | 7         | 3.95%   |
| 1680x1050 (WSXGA+) | 6         | 3.39%   |
| 1920x1200 (WUXGA)  | 5         | 2.82%   |
| 1600x900 (HD+)     | 5         | 2.82%   |
| Unknown            | 5         | 2.82%   |
| 1600x1200          | 3         | 1.69%   |
| 3840x1200          | 2         | 1.13%   |
| 3840x1080          | 2         | 1.13%   |
| 1360x768           | 2         | 1.13%   |
| 4480x1440          | 1         | 0.56%   |
| 3440x1440          | 1         | 0.56%   |
| 1280x720 (HD)      | 1         | 0.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 24      | 27        | 14.84%  |
| 15      | 24        | 13.19%  |
| 23      | 20        | 10.99%  |
| 21      | 18        | 9.89%   |
| 19      | 16        | 8.79%   |
| 27      | 12        | 6.59%   |
| Unknown | 12        | 6.59%   |
| 17      | 9         | 4.95%   |
| 13      | 8         | 4.4%    |
| 14      | 7         | 3.85%   |
| 12      | 6         | 3.3%    |
| 22      | 4         | 2.2%    |
| 20      | 4         | 2.2%    |
| 18      | 3         | 1.65%   |
| 31      | 2         | 1.1%    |
| 72      | 1         | 0.55%   |
| 55      | 1         | 0.55%   |
| 52      | 1         | 0.55%   |
| 42      | 1         | 0.55%   |
| 36      | 1         | 0.55%   |
| 34      | 1         | 0.55%   |
| 32      | 1         | 0.55%   |
| 26      | 1         | 0.55%   |
| 25      | 1         | 0.55%   |
| 16      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 55        | 31.25%  |
| 301-350     | 41        | 23.3%   |
| 401-500     | 36        | 20.45%  |
| 351-400     | 14        | 7.95%   |
| Unknown     | 12        | 6.82%   |
| 201-300     | 8         | 4.55%   |
| 701-800     | 3         | 1.7%    |
| 601-700     | 3         | 1.7%    |
| 1001-1500   | 2         | 1.14%   |
| 1501-2000   | 1         | 0.57%   |
| 901-1000    | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 108       | 65.85%  |
| 16/10   | 25        | 15.24%  |
| 5/4     | 15        | 9.15%   |
| Unknown | 10        | 6.1%    |
| 4/3     | 3         | 1.83%   |
| 3/2     | 2         | 1.22%   |
| 21/9    | 1         | 0.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 53        | 29.78%  |
| 151-200        | 27        | 15.17%  |
| 101-110        | 24        | 13.48%  |
| 81-90          | 14        | 7.87%   |
| 301-350        | 12        | 6.74%   |
| Unknown        | 12        | 6.74%   |
| 251-300        | 8         | 4.49%   |
| 141-150        | 8         | 4.49%   |
| 61-70          | 6         | 3.37%   |
| 351-500        | 4         | 2.25%   |
| More than 1000 | 3         | 1.69%   |
| 121-130        | 3         | 1.69%   |
| 501-1000       | 2         | 1.12%   |
| 71-80          | 1         | 0.56%   |
| 111-120        | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 85        | 49.42%  |
| 101-120       | 44        | 25.58%  |
| 121-160       | 25        | 14.53%  |
| Unknown       | 12        | 6.98%   |
| 1-50          | 3         | 1.74%   |
| More than 240 | 2         | 1.16%   |
| 161-240       | 1         | 0.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 130       | 54.62%  |
| 0     | 72        | 30.25%  |
| 2     | 33        | 13.87%  |
| 3     | 3         | 1.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 153       | 48.73%  |
| Realtek Semiconductor             | 68        | 21.66%  |
| Broadcom                          | 26        | 8.28%   |
| Qualcomm Atheros                  | 17        | 5.41%   |
| IBM                               | 6         | 1.91%   |
| TP-Link                           | 5         | 1.59%   |
| Ralink Technology                 | 4         | 1.27%   |
| Broadcom Limited                  | 4         | 1.27%   |
| D-Link System                     | 3         | 0.96%   |
| Xilinx                            | 2         | 0.64%   |
| Nvidia                            | 2         | 0.64%   |
| Mellanox Technologies             | 2         | 0.64%   |
| Marvell Technology Group          | 2         | 0.64%   |
| D-Link                            | 2         | 0.64%   |
| VIA Technologies                  | 1         | 0.32%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.32%   |
| Samsung Electronics               | 1         | 0.32%   |
| Ralink                            | 1         | 0.32%   |
| Qualcomm Atheros Communications   | 1         | 0.32%   |
| MediaTek                          | 1         | 0.32%   |
| Linux 2.6.31.6 with s3c-udc       | 1         | 0.32%   |
| Linksys                           | 1         | 0.32%   |
| Huawei Technologies               | 1         | 0.32%   |
| Ericsson Business Mobile Networks | 1         | 0.32%   |
| Emulex                            | 1         | 0.32%   |
| Edimax Technology                 | 1         | 0.32%   |
| Dresden Elektronik                | 1         | 0.32%   |
| Cisco Systems                     | 1         | 0.32%   |
| ASIX Electronics                  | 1         | 0.32%   |
| Aquantia                          | 1         | 0.32%   |
| Apple                             | 1         | 0.32%   |
| 3Com                              | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 50        | 12.59%  |
| Intel I350 Gigabit Network Connection                                   | 25        | 6.3%    |
| Intel Ethernet Connection (2) I219-LM                                   | 16        | 4.03%   |
| Intel 82599 10 Gigabit Dual Port Network Connection                     | 15        | 3.78%   |
| Intel Ethernet Connection I217-LM                                       | 14        | 3.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 13        | 3.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 2.52%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                           | 10        | 2.52%   |
| Intel I210 Gigabit Network Connection                                   | 8         | 2.02%   |
| Intel Ethernet Connection (7) I219-LM                                   | 7         | 1.76%   |
| Intel 82576 Gigabit Network Connection                                  | 7         | 1.76%   |
| Intel Ethernet Connection (11) I219-LM                                  | 6         | 1.51%   |
| IBM RNDIS/Ethernet Gadget                                               | 6         | 1.51%   |
| Intel 82574L Gigabit Network Connection                                 | 5         | 1.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.01%   |
| Intel I211 Gigabit Network Connection                                   | 4         | 1.01%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                           | 4         | 1.01%   |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 1.01%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                        | 4         | 1.01%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                        | 4         | 1.01%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 0.76%   |
| Intel Wireless 8260                                                     | 3         | 0.76%   |
| Intel Wireless 7260                                                     | 3         | 0.76%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 0.76%   |
| Intel Ethernet Controller 10G X550T                                     | 3         | 0.76%   |
| Intel Ethernet Connection I219-V                                        | 3         | 0.76%   |
| Intel Ethernet Connection (2) I218-V                                    | 3         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.76%   |
| Intel 82580 Gigabit Network Connection                                  | 3         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 0.76%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 0.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.5%    |
| Intel Wireless 7265                                                     | 2         | 0.5%    |
| Intel Wireless 3165                                                     | 2         | 0.5%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.5%    |
| Intel Ethernet Connection X722 for 1GbE                                 | 2         | 0.5%    |
| Intel Ethernet Connection X722                                          | 2         | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                    | 2         | 0.5%    |
| Intel Ethernet Connection (3) I219-LM                                   | 2         | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.5%    |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.5%    |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 0.5%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.5%    |
| Intel 82579V Gigabit Network Connection                                 | 2         | 0.5%    |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                 | 2         | 0.5%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                        | 2         | 0.5%    |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                             | 2         | 0.5%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2         | 0.5%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 0.5%    |
| Xilinx Network controller                                               | 1         | 0.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 48.78%  |
| Realtek Semiconductor           | 11        | 13.41%  |
| Qualcomm Atheros                | 11        | 13.41%  |
| Broadcom                        | 5         | 6.1%    |
| Ralink Technology               | 4         | 4.88%   |
| TP-Link                         | 3         | 3.66%   |
| D-Link                          | 2         | 2.44%   |
| Ralink                          | 1         | 1.22%   |
| Qualcomm Atheros Communications | 1         | 1.22%   |
| MediaTek                        | 1         | 1.22%   |
| Linksys                         | 1         | 1.22%   |
| Edimax Technology               | 1         | 1.22%   |
| D-Link System                   | 1         | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 4.82%   |
| Intel Wireless 8260                                                           | 3         | 3.61%   |
| Intel Wireless 7260                                                           | 3         | 3.61%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 3.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 3.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 3         | 3.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2         | 2.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2         | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 2         | 2.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2         | 2.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 2.41%   |
| Intel Wireless 7265                                                           | 2         | 2.41%   |
| Intel Wireless 3165                                                           | 2         | 2.41%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 2.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 2.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 2.41%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 2.41%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                 | 2         | 2.41%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 2.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 2         | 2.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 2         | 2.41%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 1.2%    |
| Realtek RTL8723DE Wireless Network Adapter                                    | 1         | 1.2%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 1.2%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 1.2%    |
| Ralink RT5572 Wireless Adapter                                                | 1         | 1.2%    |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.2%    |
| Ralink MT7601U Wireless Adapter                                               | 1         | 1.2%    |
| Ralink Conceptronic C300RU v2 802.11bgn Wireless Adapter [Ralink RT2770]      | 1         | 1.2%    |
| Ralink RT2500 Wireless 802.11bg                                               | 1         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 1.2%    |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.2%    |
| MediaTek WiFi                                                                 | 1         | 1.2%    |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 1.2%    |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.2%    |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 1.2%    |
| Intel Centrino Wireless-N 135                                                 | 1         | 1.2%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 1.2%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 1.2%    |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 1         | 1.2%    |
| Edimax AC600 USB                                                              | 1         | 1.2%    |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]             | 1         | 1.2%    |
| D-Link DWA-160 Xtreme N Dual Band USB Adapter(rev.C1)                         | 1         | 1.2%    |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]          | 1         | 1.2%    |
| D-Link 802.11 n WLAN                                                          | 1         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 140       | 53.23%  |
| Realtek Semiconductor            | 65        | 24.71%  |
| Broadcom                         | 21        | 7.98%   |
| Qualcomm Atheros                 | 7         | 2.66%   |
| IBM                              | 6         | 2.28%   |
| Broadcom Limited                 | 4         | 1.52%   |
| TP-Link                          | 2         | 0.76%   |
| Nvidia                           | 2         | 0.76%   |
| Marvell Technology Group         | 2         | 0.76%   |
| D-Link System                    | 2         | 0.76%   |
| Xilinx                           | 1         | 0.38%   |
| VIA Technologies                 | 1         | 0.38%   |
| Silicon Integrated Systems [SiS] | 1         | 0.38%   |
| Samsung Electronics              | 1         | 0.38%   |
| Mellanox Technologies            | 1         | 0.38%   |
| Huawei Technologies              | 1         | 0.38%   |
| Emulex                           | 1         | 0.38%   |
| Cisco Systems                    | 1         | 0.38%   |
| ASIX Electronics                 | 1         | 0.38%   |
| Aquantia                         | 1         | 0.38%   |
| Apple                            | 1         | 0.38%   |
| 3Com                             | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 50        | 16.23%  |
| Intel I350 Gigabit Network Connection                                          | 25        | 8.12%   |
| Intel Ethernet Connection (2) I219-LM                                          | 16        | 5.19%   |
| Intel 82599 10 Gigabit Dual Port Network Connection                            | 15        | 4.87%   |
| Intel Ethernet Connection I217-LM                                              | 14        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 13        | 4.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 3.25%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 10        | 3.25%   |
| Intel I210 Gigabit Network Connection                                          | 8         | 2.6%    |
| Intel Ethernet Connection (7) I219-LM                                          | 7         | 2.27%   |
| Intel 82576 Gigabit Network Connection                                         | 7         | 2.27%   |
| Intel Ethernet Connection (11) I219-LM                                         | 6         | 1.95%   |
| IBM RNDIS/Ethernet Gadget                                                      | 6         | 1.95%   |
| Intel 82574L Gigabit Network Connection                                        | 5         | 1.62%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 1.3%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 4         | 1.3%    |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 4         | 1.3%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 4         | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.97%   |
| Intel Ethernet Controller 10G X550T                                            | 3         | 0.97%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.97%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.97%   |
| Intel 82580 Gigabit Network Connection                                         | 3         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.97%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.65%   |
| Intel Ethernet Connection X722 for 1GbE                                        | 2         | 0.65%   |
| Intel Ethernet Connection X722                                                 | 2         | 0.65%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.65%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.65%   |
| Intel Ethernet Connection (3) I219-LM                                          | 2         | 0.65%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 0.65%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 2         | 0.65%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 2         | 0.65%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                                    | 2         | 0.65%   |
| Xilinx Ethernet controller                                                     | 1         | 0.32%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 1         | 0.32%   |
| TP-LINK USB 10/100 LAN                                                         | 1         | 0.32%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 0.32%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.32%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.32%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.32%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                        | 1         | 0.32%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.32%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.32%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                               | 1         | 0.32%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.32%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                  | 1         | 0.32%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                   | 1         | 0.32%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.32%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.32%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 231       | 73.57%  |
| WiFi     | 77        | 24.52%  |
| Modem    | 4         | 1.27%   |
| Unknown  | 2         | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 198       | 78.88%  |
| WiFi     | 52        | 20.72%  |
| Unknown  | 1         | 0.4%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 91        | 38.72%  |
| 1     | 89        | 37.87%  |
| 4     | 22        | 9.36%   |
| 6     | 14        | 5.96%   |
| 3     | 9         | 3.83%   |
| 8     | 3         | 1.28%   |
| 5     | 2         | 0.85%   |
| 0     | 2         | 0.85%   |
| 20    | 1         | 0.43%   |
| 12    | 1         | 0.43%   |
| 10    | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 223       | 94.09%  |
| Yes  | 14        | 5.91%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 41.07%  |
| Qualcomm Atheros Communications | 7         | 12.5%   |
| Broadcom                        | 7         | 12.5%   |
| Cambridge Silicon Radio         | 5         | 8.93%   |
| Realtek Semiconductor           | 4         | 7.14%   |
| Dell                            | 3         | 5.36%   |
| ASUSTek Computer                | 3         | 5.36%   |
| Lite-On Technology              | 1         | 1.79%   |
| IMC Networks                    | 1         | 1.79%   |
| Foxconn / Hon Hai               | 1         | 1.79%   |
| Apple                           | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 8         | 14.29%  |
| Intel Bluetooth wireless interface                                                  | 5         | 8.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 8.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 7.14%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 5.36%   |
| Intel AX200 Bluetooth                                                               | 3         | 5.36%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 3.57%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 3.57%   |
| Intel AX201 Bluetooth                                                               | 2         | 3.57%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 3.57%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 3.57%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 2         | 3.57%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.79%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.79%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.79%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.79%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.79%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 1.79%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1.79%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.79%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 1.79%   |
| Broadcom ANYCOM Blue USB-200/250                                                    | 1         | 1.79%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 1.79%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 136       | 59.13%  |
| AMD                              | 45        | 19.57%  |
| Nvidia                           | 37        | 16.09%  |
| Logitech                         | 2         | 0.87%   |
| GN Netcom                        | 2         | 0.87%   |
| Creative Labs                    | 2         | 0.87%   |
| Texas Instruments                | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] | 1         | 0.43%   |
| Lenovo                           | 1         | 0.43%   |
| Ensoniq                          | 1         | 0.43%   |
| C-Media Electronics              | 1         | 0.43%   |
| ASUSTek Computer                 | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 7.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 6.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 16        | 6.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 16        | 6.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 3.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 3.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 3.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.32%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 2.32%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.93%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.54%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1.54%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4         | 1.54%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 4         | 1.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 1.54%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.54%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 1.16%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.16%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.16%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 1.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.16%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 1.16%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 1.16%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 2         | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.77%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.77%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.77%   |
| Logitech Headset H390                                                                             | 2         | 0.77%   |
| Intel Lewisburg MROM 0                                                                            | 2         | 0.77%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.77%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2         | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.77%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]                             | 2         | 0.77%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.77%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.39%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.39%   |
| Nvidia stereo controller                                                                          | 1         | 0.39%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.39%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 0.39%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.39%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.39%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.39%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.39%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 0.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.39%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.39%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 22.48%  |
| Micron Technology   | 42        | 19.27%  |
| SK Hynix            | 41        | 18.81%  |
| Kingston            | 37        | 16.97%  |
| Unknown             | 21        | 9.63%   |
| Crucial             | 15        | 6.88%   |
| Transcend           | 3         | 1.38%   |
| A-DATA Technology   | 3         | 1.38%   |
| Patriot             | 2         | 0.92%   |
| Corsair             | 2         | 0.92%   |
| Ramaxel Technology  | 1         | 0.46%   |
| ELPIDA              | 1         | 0.46%   |
| Apacer              | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s       | 10        | 4.15%   |
| Samsung RAM M378B5173QH0-YK0 4096MB DIMM DDR3 1600MT/s     | 6         | 2.49%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s       | 5         | 2.07%   |
| Samsung RAM Module 8192MB DIMM DDR3 800MT/s                | 4         | 1.66%   |
| Micron RAM 4ATF51264AZ-2G3B1 4GB DIMM DDR4 2800MT/s        | 4         | 1.66%   |
| Micron RAM 36ASF4G72PZ-2G6D1 32GB DIMM DDR4 2667MT/s       | 4         | 1.66%   |
| Crucial RAM CT16G4DFD824A.C16FDD 16GB DIMM DDR4 2400MT/s   | 4         | 1.66%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s              | 2         | 0.83%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 0.83%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 2         | 0.83%   |
| SK Hynix RAM HMA451R7MFR8N-TF 4096MB DIMM DDR4 2133MT/s    | 2         | 0.83%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 0.83%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                 | 2         | 0.83%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s         | 2         | 0.83%   |
| Micron RAM 36ASF4G72PZ-2G3A1 32GB DIMM DDR4 2400MT/s       | 2         | 0.83%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16384MB DIMM DDR4 2667MT/s    | 2         | 0.83%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s     | 2         | 0.83%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8192MB DIMM DDR4 2400MT/s | 2         | 0.83%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s               | 1         | 0.41%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s               | 1         | 0.41%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                    | 1         | 0.41%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                    | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                | 1         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3                      | 1         | 0.41%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s               | 1         | 0.41%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s                | 1         | 0.41%   |
| Unknown RAM Module 4096MB DIMM 800MT/s                     | 1         | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                    | 1         | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 1         | 0.41%   |
| Unknown RAM Module 4096MB DIMM                             | 1         | 0.41%   |
| Unknown RAM Module 2048MB SODIMM DDR3 800MT/s              | 1         | 0.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s              | 1         | 0.41%   |
| Unknown RAM Module 2048MB FB-DIMM DDR2 667MT/s             | 1         | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s               | 1         | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s                | 1         | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2                        | 1         | 0.41%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 1         | 0.41%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 1         | 0.41%   |
| Unknown RAM Module 2048MB DIMM 1067MT/s                    | 1         | 0.41%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s              | 1         | 0.41%   |
| Unknown RAM Module 16384MB DIMM 1067MT/s                   | 1         | 0.41%   |
| Unknown RAM Module 1024MB SODIMM DRAM                      | 1         | 0.41%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                | 1         | 0.41%   |
| Transcend RAM TS1GLH64V1H 8192MB DIMM DDR4 2133MT/s        | 1         | 0.41%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s      | 1         | 0.41%   |
| Transcend RAM AQD-SD3L2GN16-S Q 2048MB DIMM DDR3 1600MT/s  | 1         | 0.41%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2667MT/s               | 1         | 0.41%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s               | 1         | 0.41%   |
| SK Hynix RAM Module 32GB SODIMM DDR4 3200MT/s              | 1         | 0.41%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 800MT/s               | 1         | 0.41%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 667MT/s               | 1         | 0.41%   |
| SK Hynix RAM Module 16GB DIMM DDR4 3200MT/s                | 1         | 0.41%   |
| SK Hynix RAM HMT451U7BFR8A-PB 4096MB DIMM DDR3 1600MT/s    | 1         | 0.41%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s       | 1         | 0.41%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 0.41%   |
| SK Hynix RAM HMT41GU7MFR8C-PB 8192MB DIMM DDR3 1600MT/s    | 1         | 0.41%   |
| SK Hynix RAM HMT41GU7AFR8A-PB 8GB DIMM DDR3 1600MT/s       | 1         | 0.41%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8192MB DIMM DDR3 2000MT/s    | 1         | 0.41%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s  | 1         | 0.41%   |
| SK Hynix RAM HMT41GR7AFR8A-PB 8192MB DIMM DDR3 1066MT/s    | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 93        | 46.73%  |
| DDR3    | 83        | 41.71%  |
| Unknown | 10        | 5.03%   |
| DDR2    | 8         | 4.02%   |
| LPDDR3  | 2         | 1.01%   |
| SDRAM   | 1         | 0.5%    |
| DRAM    | 1         | 0.5%    |
| DDR     | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 140       | 70.35%  |
| SODIMM       | 55        | 27.64%  |
| FB-DIMM      | 2         | 1.01%   |
| Row Of Chips | 1         | 0.5%    |
| RIMM         | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 61        | 28.77%  |
| 4096  | 57        | 26.89%  |
| 16384 | 32        | 15.09%  |
| 32768 | 29        | 13.68%  |
| 2048  | 27        | 12.74%  |
| 1024  | 4         | 1.89%   |
| 65536 | 2         | 0.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 43        | 20.28%  |
| 2400    | 37        | 17.45%  |
| 1333    | 29        | 13.68%  |
| 2667    | 28        | 13.21%  |
| 2133    | 14        | 6.6%    |
| 3200    | 11        | 5.19%   |
| 800     | 10        | 4.72%   |
| 667     | 7         | 3.3%    |
| 2800    | 4         | 1.89%   |
| Unknown | 4         | 1.89%   |
| 2666    | 3         | 1.42%   |
| 2933    | 2         | 0.94%   |
| 2134    | 2         | 0.94%   |
| 2000    | 2         | 0.94%   |
| 1800    | 2         | 0.94%   |
| 1334    | 2         | 0.94%   |
| 1067    | 2         | 0.94%   |
| 1066    | 2         | 0.94%   |
| 4199    | 1         | 0.47%   |
| 3500    | 1         | 0.47%   |
| 3266    | 1         | 0.47%   |
| 2465    | 1         | 0.47%   |
| 1867    | 1         | 0.47%   |
| 1866    | 1         | 0.47%   |
| 533     | 1         | 0.47%   |
| 400     | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Canon               | 1         | 20%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Samsung M288x Series  | 1         | 20%     |
| HP LaserJet 400 M401n | 1         | 20%     |
| HP LaserJet 3030      | 1         | 20%     |
| Canon MF210 Series    | 1         | 20%     |
| Brother MFC-9130CW    | 1         | 20%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 6         | 12.5%   |
| Sunplus Innovation Technology          | 5         | 10.42%  |
| Realtek Semiconductor                  | 4         | 8.33%   |
| Suyin                                  | 3         | 6.25%   |
| Quanta                                 | 3         | 6.25%   |
| Microdia                               | 3         | 6.25%   |
| Logitech                               | 3         | 6.25%   |
| Generalplus Technology                 | 3         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.25%   |
| Acer                                   | 3         | 6.25%   |
| Ricoh                                  | 2         | 4.17%   |
| Microsoft                              | 2         | 4.17%   |
| IMC Networks                           | 2         | 4.17%   |
| Apple                                  | 2         | 4.17%   |
| Syntek                                 | 1         | 2.08%   |
| Silicon Motion                         | 1         | 2.08%   |
| Samsung Electronics                    | 1         | 2.08%   |
| Lite-On Technology                     | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                               | 3         | 6.25%   |
| Generalplus 808 Camera                                                     | 3         | 6.25%   |
| Suyin Integrated Webcam                                                    | 2         | 4.17%   |
| IMC Networks Integrated Camera                                             | 2         | 4.17%   |
| Syntek EasyCamera                                                          | 1         | 2.08%   |
| Suyin Asus Integrated Webcam [CN031B]                                      | 1         | 2.08%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 2.08%   |
| Sunplus Integrated Webcam                                                  | 1         | 2.08%   |
| Silicon Motion WebCam SC-10HDD12636N                                       | 1         | 2.08%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 2.08%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 2.08%   |
| Ricoh HD Webcam                                                            | 1         | 2.08%   |
| Realtek Web Camera                                                         | 1         | 2.08%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 2.08%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 2.08%   |
| Realtek Integrated Webcam HD                                               | 1         | 2.08%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                       | 1         | 2.08%   |
| Quanta HP Webcam                                                           | 1         | 2.08%   |
| Quanta HP Full-HD Camera                                                   | 1         | 2.08%   |
| Microsoft LifeCam NX-6000                                                  | 1         | 2.08%   |
| Microsoft LifeCam HD-5000                                                  | 1         | 2.08%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 2.08%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.08%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 2.08%   |
| Logitech Webcam C310                                                       | 1         | 2.08%   |
| Logitech Webcam C170                                                       | 1         | 2.08%   |
| Logitech HD Pro Webcam C920                                                | 1         | 2.08%   |
| Lite-On HP HD Camera                                                       | 1         | 2.08%   |
| Chicony USB2.0 Camera                                                      | 1         | 2.08%   |
| Chicony TOSHIBA Web Camera - HD                                            | 1         | 2.08%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 2.08%   |
| Chicony HP Webcam [2 MP Macro]                                             | 1         | 2.08%   |
| Chicony HP Truevision HD                                                   | 1         | 2.08%   |
| Chicony HD WebCam                                                          | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP 5M Camera                        | 1         | 2.08%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 2.08%   |
| Apple Built-in iSight                                                      | 1         | 2.08%   |
| Acer SunplusIT INC. Integrated Camera                                      | 1         | 2.08%   |
| Acer HD Webcam                                                             | 1         | 2.08%   |
| Acer EasyCamera                                                            | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 6         | 40%     |
| AuthenTec          | 4         | 26.67%  |
| Synaptics          | 3         | 20%     |
| Upek               | 1         | 6.67%   |
| STMicroelectronics | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 3         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 6.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 6.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 6.67%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 6         | 60%     |
| SCM Microsystems | 2         | 20%     |
| Lenovo           | 1         | 10%     |
| Hewlett-Packard  | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 40%     |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 10%     |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 10%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 10%     |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 130       | 54.85%  |
| 1     | 57        | 24.05%  |
| 2     | 35        | 14.77%  |
| 3     | 11        | 4.64%   |
| 4     | 3         | 1.27%   |
| 5     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 47        | 29.56%  |
| Unassigned class         | 36        | 22.64%  |
| Graphics card            | 30        | 18.87%  |
| Fingerprint reader       | 15        | 9.43%   |
| Net/wireless             | 10        | 6.29%   |
| Net/ethernet             | 8         | 5.03%   |
| Chipcard                 | 5         | 3.14%   |
| Storage                  | 3         | 1.89%   |
| Network                  | 2         | 1.26%   |
| Storage/raid             | 1         | 0.63%   |
| Multimedia controller    | 1         | 0.63%   |
| Camera                   | 1         | 0.63%   |

