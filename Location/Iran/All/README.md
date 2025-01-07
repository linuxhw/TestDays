Linux in Iran - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Linux in Iran.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Iran/Desktop/README.md) and [notebooks](/Location/Iran/Notebook/README.md).

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

Total: 1198

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5534263506](https://linux-hardware.org/?probe=5534263506) | Jan 04, 2025 |
| Lenovo        | Unknown                     | Notebook    | [a18bd92542](https://linux-hardware.org/?probe=a18bd92542) | Jan 02, 2025 |
| Acer          | Aspire E1-571G              | Notebook    | [a589ad91b5](https://linux-hardware.org/?probe=a589ad91b5) | Dec 30, 2024 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [7852114da0](https://linux-hardware.org/?probe=7852114da0) | Dec 24, 2024 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [52df805f98](https://linux-hardware.org/?probe=52df805f98) | Dec 24, 2024 |
| Acer          | Aspire ES1-132              | Notebook    | [0f3a83bb56](https://linux-hardware.org/?probe=0f3a83bb56) | Dec 19, 2024 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6748714931](https://linux-hardware.org/?probe=6748714931) | Dec 19, 2024 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [85385e1ab5](https://linux-hardware.org/?probe=85385e1ab5) | Dec 17, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [12be2072af](https://linux-hardware.org/?probe=12be2072af) | Dec 16, 2024 |
| Dell          | Vostro 1510                 | Notebook    | [e65fd8a402](https://linux-hardware.org/?probe=e65fd8a402) | Dec 16, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [cc9e7aed4d](https://linux-hardware.org/?probe=cc9e7aed4d) | Dec 12, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [861b5550d3](https://linux-hardware.org/?probe=861b5550d3) | Dec 10, 2024 |
| Lenovo        | LOQ 15IRX9 83DV             | Notebook    | [c6e0329105](https://linux-hardware.org/?probe=c6e0329105) | Dec 08, 2024 |
| Lenovo        | ThinkPad X131e 33671P9      | Notebook    | [ac080feaa5](https://linux-hardware.org/?probe=ac080feaa5) | Dec 07, 2024 |
| Lenovo        | ThinkPad X131e 33671P9      | Notebook    | [2ae8fcd4f0](https://linux-hardware.org/?probe=2ae8fcd4f0) | Dec 06, 2024 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [36683f8571](https://linux-hardware.org/?probe=36683f8571) | Dec 05, 2024 |
| ASUSTek       | X550CC                      | Notebook    | [c395078c21](https://linux-hardware.org/?probe=c395078c21) | Dec 05, 2024 |
| HP            | 8597                        | Desktop     | [c0b7ad7c1f](https://linux-hardware.org/?probe=c0b7ad7c1f) | Dec 01, 2024 |
| Apple         | MacBookPro15,4              | Notebook    | [0d07341af3](https://linux-hardware.org/?probe=0d07341af3) | Nov 29, 2024 |
| HP            | Elite x2 1013 G3            | Tablet      | [a1f8f4c528](https://linux-hardware.org/?probe=a1f8f4c528) | Nov 22, 2024 |
| HP            | Elite x2 1013 G3            | Tablet      | [6a0c61a016](https://linux-hardware.org/?probe=6a0c61a016) | Nov 22, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [73455e8d8a](https://linux-hardware.org/?probe=73455e8d8a) | Nov 20, 2024 |
| MSI           | MPG Z790 CARBON WIFI II     | Desktop     | [c10e454a0e](https://linux-hardware.org/?probe=c10e454a0e) | Nov 17, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [2674fe3d2e](https://linux-hardware.org/?probe=2674fe3d2e) | Nov 14, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [44fca8e77c](https://linux-hardware.org/?probe=44fca8e77c) | Nov 09, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e17bcc1d20](https://linux-hardware.org/?probe=e17bcc1d20) | Nov 09, 2024 |
| Lenovo        | ThinkCentre M81 M 5049-Y... | Desktop     | [e6e78d2a35](https://linux-hardware.org/?probe=e6e78d2a35) | Oct 30, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d1adfd3848](https://linux-hardware.org/?probe=d1adfd3848) | Oct 29, 2024 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [4d3c9d7850](https://linux-hardware.org/?probe=4d3c9d7850) | Oct 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [d0c1cb66bc](https://linux-hardware.org/?probe=d0c1cb66bc) | Oct 18, 2024 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | Notebook    | [c4a9610593](https://linux-hardware.org/?probe=c4a9610593) | Oct 18, 2024 |
| Apple         | MacBook8,1                  | Notebook    | [187941fe6d](https://linux-hardware.org/?probe=187941fe6d) | Oct 14, 2024 |
| Apple         | MacBook8,1                  | Notebook    | [be0a45d5f6](https://linux-hardware.org/?probe=be0a45d5f6) | Oct 14, 2024 |
| Dell          | XPS 13 7390                 | Notebook    | [4bc8b23ee8](https://linux-hardware.org/?probe=4bc8b23ee8) | Oct 13, 2024 |
| Sony          | SVE15118FGB                 | Notebook    | [b18e981595](https://linux-hardware.org/?probe=b18e981595) | Oct 07, 2024 |
| ECS           | A880GM-AD3                  | Desktop     | [7346981ac3](https://linux-hardware.org/?probe=7346981ac3) | Oct 06, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [8053e3651e](https://linux-hardware.org/?probe=8053e3651e) | Oct 05, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [dd0fe502ab](https://linux-hardware.org/?probe=dd0fe502ab) | Oct 04, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [372bdc8f2b](https://linux-hardware.org/?probe=372bdc8f2b) | Oct 04, 2024 |
| ASUSTek       | Z97-A                       | Desktop     | [1e8e373eb7](https://linux-hardware.org/?probe=1e8e373eb7) | Oct 04, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [b2977f96cd](https://linux-hardware.org/?probe=b2977f96cd) | Sep 27, 2024 |
| ASUSTek       | M5A88-M                     | Desktop     | [5725f8c2e1](https://linux-hardware.org/?probe=5725f8c2e1) | Sep 26, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [506cc233e6](https://linux-hardware.org/?probe=506cc233e6) | Sep 25, 2024 |
| Gigabyte      | H55M-USB3                   | Desktop     | [ddffc54d59](https://linux-hardware.org/?probe=ddffc54d59) | Sep 22, 2024 |
| Dell          | Latitude 7290               | Notebook    | [7310d2504b](https://linux-hardware.org/?probe=7310d2504b) | Sep 22, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [fdcd6421d6](https://linux-hardware.org/?probe=fdcd6421d6) | Sep 20, 2024 |
| Toshiba       | Satellite C640              | Notebook    | [e3a9b659d6](https://linux-hardware.org/?probe=e3a9b659d6) | Sep 19, 2024 |
| Lenovo        | ThinkPad T490 20N3S8T22A    | Notebook    | [32ec38ff8c](https://linux-hardware.org/?probe=32ec38ff8c) | Sep 19, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [6fd7c686fc](https://linux-hardware.org/?probe=6fd7c686fc) | Sep 14, 2024 |
| Gigabyte      | P110-D3-CF                  | Desktop     | [11179fcd4d](https://linux-hardware.org/?probe=11179fcd4d) | Sep 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [38fd7b1b76](https://linux-hardware.org/?probe=38fd7b1b76) | Sep 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [d63547e4e7](https://linux-hardware.org/?probe=d63547e4e7) | Sep 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [96fbec6444](https://linux-hardware.org/?probe=96fbec6444) | Sep 11, 2024 |
| HP            | ZBook 17 G5                 | Notebook    | [1a6e1fc880](https://linux-hardware.org/?probe=1a6e1fc880) | Sep 06, 2024 |
| DFI           | BI P45-T2R                  | Desktop     | [cef2a3926b](https://linux-hardware.org/?probe=cef2a3926b) | Sep 03, 2024 |
| HP            | 3397                        | Desktop     | [41f12d3708](https://linux-hardware.org/?probe=41f12d3708) | Aug 31, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [33cb105809](https://linux-hardware.org/?probe=33cb105809) | Aug 31, 2024 |
| MSI           | MS-AA52 11                  | Other       | [738afff05c](https://linux-hardware.org/?probe=738afff05c) | Aug 30, 2024 |
| MSI           | MS-AA52 11                  | Other       | [88c7f91229](https://linux-hardware.org/?probe=88c7f91229) | Aug 30, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [28dd42ce86](https://linux-hardware.org/?probe=28dd42ce86) | Aug 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [2942fe4c28](https://linux-hardware.org/?probe=2942fe4c28) | Aug 23, 2024 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [935b5d9511](https://linux-hardware.org/?probe=935b5d9511) | Aug 22, 2024 |
| Acer          | Aspire VN7-571G             | Notebook    | [1b0e2cc44c](https://linux-hardware.org/?probe=1b0e2cc44c) | Aug 20, 2024 |
| Sony          | VPCF132FX                   | Notebook    | [da6bb5274c](https://linux-hardware.org/?probe=da6bb5274c) | Aug 20, 2024 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [9d0afb59e0](https://linux-hardware.org/?probe=9d0afb59e0) | Aug 18, 2024 |
| Sony          | VPCF132FX                   | Notebook    | [83a4d54bd2](https://linux-hardware.org/?probe=83a4d54bd2) | Aug 17, 2024 |
| Dell          | Vostro 1510                 | Notebook    | [4c113026a9](https://linux-hardware.org/?probe=4c113026a9) | Aug 13, 2024 |
| Dell          | Vostro 1510                 | Notebook    | [a7630e0c14](https://linux-hardware.org/?probe=a7630e0c14) | Aug 12, 2024 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [da2b320cd5](https://linux-hardware.org/?probe=da2b320cd5) | Aug 12, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [83ebba4331](https://linux-hardware.org/?probe=83ebba4331) | Aug 10, 2024 |
| ASUSTek       | K45VM                       | Notebook    | [bb8ec693eb](https://linux-hardware.org/?probe=bb8ec693eb) | Aug 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [850bf21fa2](https://linux-hardware.org/?probe=850bf21fa2) | Aug 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7682cd79d5](https://linux-hardware.org/?probe=7682cd79d5) | Aug 06, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c5e066d0af](https://linux-hardware.org/?probe=c5e066d0af) | Aug 06, 2024 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6a328cd3ea](https://linux-hardware.org/?probe=6a328cd3ea) | Aug 02, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [04fbf7eb2d](https://linux-hardware.org/?probe=04fbf7eb2d) | Aug 01, 2024 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [eb708e134f](https://linux-hardware.org/?probe=eb708e134f) | Jul 30, 2024 |
| HP            | 1998                        | Desktop     | [60afbd15ac](https://linux-hardware.org/?probe=60afbd15ac) | Jul 29, 2024 |
| HP            | 1998                        | Desktop     | [aec61d3087](https://linux-hardware.org/?probe=aec61d3087) | Jul 29, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [057dd65190](https://linux-hardware.org/?probe=057dd65190) | Jul 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [79bbd8846b](https://linux-hardware.org/?probe=79bbd8846b) | Jul 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [6896bae4c8](https://linux-hardware.org/?probe=6896bae4c8) | Jul 27, 2024 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [66e39a4081](https://linux-hardware.org/?probe=66e39a4081) | Jul 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [ba66d077e7](https://linux-hardware.org/?probe=ba66d077e7) | Jul 26, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [0012829b12](https://linux-hardware.org/?probe=0012829b12) | Jul 24, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [38180e0cf9](https://linux-hardware.org/?probe=38180e0cf9) | Jul 24, 2024 |
| Dell          | Studio 1537                 | Notebook    | [a912e97b90](https://linux-hardware.org/?probe=a912e97b90) | Jul 23, 2024 |
| Dell          | System Inspiron N7110       | Notebook    | [9eca86601c](https://linux-hardware.org/?probe=9eca86601c) | Jul 23, 2024 |
| ASUSTek       | X550LD                      | Notebook    | [94884c2b02](https://linux-hardware.org/?probe=94884c2b02) | Jul 19, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [34fa837cb3](https://linux-hardware.org/?probe=34fa837cb3) | Jul 18, 2024 |
| ASUSTek       | K53SV                       | Notebook    | [76212aff71](https://linux-hardware.org/?probe=76212aff71) | Jul 12, 2024 |
| ASUSTek       | X550IK                      | Notebook    | [a6ae6a7c83](https://linux-hardware.org/?probe=a6ae6a7c83) | Jul 09, 2024 |
| Dell          | Latitude 7390               | Notebook    | [4d43328aad](https://linux-hardware.org/?probe=4d43328aad) | Jul 09, 2024 |
| Dell          | Latitude 7390               | Notebook    | [dc471a79e4](https://linux-hardware.org/?probe=dc471a79e4) | Jul 09, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [738373c2bd](https://linux-hardware.org/?probe=738373c2bd) | Jul 08, 2024 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [a0f176c415](https://linux-hardware.org/?probe=a0f176c415) | Jul 06, 2024 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [d710eb627a](https://linux-hardware.org/?probe=d710eb627a) | Jul 06, 2024 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e8b885d16c](https://linux-hardware.org/?probe=e8b885d16c) | Jul 01, 2024 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [2cc67e46f7](https://linux-hardware.org/?probe=2cc67e46f7) | Jun 27, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [0be9720c78](https://linux-hardware.org/?probe=0be9720c78) | Jun 27, 2024 |
| Acer          | Predator PT316-51s          | Notebook    | [4eaaff5dc9](https://linux-hardware.org/?probe=4eaaff5dc9) | Jun 26, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [eefb6986cb](https://linux-hardware.org/?probe=eefb6986cb) | Jun 26, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [7a3972d072](https://linux-hardware.org/?probe=7a3972d072) | Jun 26, 2024 |
| Gigabyte      | 970A-D3                     | Desktop     | [ca72b5cc43](https://linux-hardware.org/?probe=ca72b5cc43) | Jun 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fca3cbf957](https://linux-hardware.org/?probe=fca3cbf957) | Jun 24, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [4cb54dee0c](https://linux-hardware.org/?probe=4cb54dee0c) | Jun 23, 2024 |
| ASUSTek       | PRIME H770-PLUS             | Desktop     | [5a56b9dda5](https://linux-hardware.org/?probe=5a56b9dda5) | Jun 23, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5bb98f4fc3](https://linux-hardware.org/?probe=5bb98f4fc3) | Jun 21, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d20c1aabf4](https://linux-hardware.org/?probe=d20c1aabf4) | Jun 20, 2024 |
| HP            | ProBook 640 G2              | Notebook    | [f6ab7b098f](https://linux-hardware.org/?probe=f6ab7b098f) | Jun 19, 2024 |
| HP            | ProBook 640 G2              | Notebook    | [641728fe6f](https://linux-hardware.org/?probe=641728fe6f) | Jun 17, 2024 |
| Acer          | Swift SFG14-72              | Notebook    | [e83b83a5a9](https://linux-hardware.org/?probe=e83b83a5a9) | Jun 14, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6e9e46f097](https://linux-hardware.org/?probe=6e9e46f097) | Jun 14, 2024 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [1ba4b894ab](https://linux-hardware.org/?probe=1ba4b894ab) | Jun 13, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6865db43a7](https://linux-hardware.org/?probe=6865db43a7) | Jun 12, 2024 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [965524f775](https://linux-hardware.org/?probe=965524f775) | Jun 11, 2024 |
| HP            | EliteBook 8570w             | Notebook    | [01e1b70a0a](https://linux-hardware.org/?probe=01e1b70a0a) | Jun 11, 2024 |
| Acer          | Swift SFG14-72              | Notebook    | [f0f869b4eb](https://linux-hardware.org/?probe=f0f869b4eb) | Jun 07, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [9686819f62](https://linux-hardware.org/?probe=9686819f62) | Jun 07, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [aea8f7e4c8](https://linux-hardware.org/?probe=aea8f7e4c8) | Jun 04, 2024 |
| Gigabyte      | MD90-FS0-XX 01234567        | Server      | [8cbc315636](https://linux-hardware.org/?probe=8cbc315636) | May 28, 2024 |
| ASUSTek       | SABERTOOTH Z170 S           | Desktop     | [ad9041b532](https://linux-hardware.org/?probe=ad9041b532) | May 27, 2024 |
| ASUSTek       | SABERTOOTH Z170 S           | Desktop     | [df3d348d4b](https://linux-hardware.org/?probe=df3d348d4b) | May 27, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [2a65cacd9e](https://linux-hardware.org/?probe=2a65cacd9e) | May 20, 2024 |
| Dell          | Studio 1557                 | Notebook    | [170fc87723](https://linux-hardware.org/?probe=170fc87723) | May 20, 2024 |
| Dell          | Studio 1557                 | Notebook    | [db03b870cf](https://linux-hardware.org/?probe=db03b870cf) | May 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [deea96eb1c](https://linux-hardware.org/?probe=deea96eb1c) | May 19, 2024 |
| HP            | ENVY 15                     | Notebook    | [b7b96fb51a](https://linux-hardware.org/?probe=b7b96fb51a) | May 17, 2024 |
| Lenovo        | ThinkBook 16 G5+ IRH 21H... | Notebook    | [f38bb08185](https://linux-hardware.org/?probe=f38bb08185) | May 16, 2024 |
| HP            | ENVY 15                     | Notebook    | [31c08e7c6e](https://linux-hardware.org/?probe=31c08e7c6e) | May 15, 2024 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [65b8f85c07](https://linux-hardware.org/?probe=65b8f85c07) | May 09, 2024 |
| Dell          | Vostro 1015                 | Notebook    | [b5f6b13138](https://linux-hardware.org/?probe=b5f6b13138) | May 07, 2024 |
| Dell          | 0215PR A02                  | Desktop     | [ff480889b4](https://linux-hardware.org/?probe=ff480889b4) | May 07, 2024 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [3206e427b1](https://linux-hardware.org/?probe=3206e427b1) | May 07, 2024 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [3d1643b2c5](https://linux-hardware.org/?probe=3d1643b2c5) | May 06, 2024 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [4a361a3420](https://linux-hardware.org/?probe=4a361a3420) | May 06, 2024 |
| HP            | 83DD                        | Mini pc     | [c20e13567a](https://linux-hardware.org/?probe=c20e13567a) | May 04, 2024 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [dd201d321b](https://linux-hardware.org/?probe=dd201d321b) | May 03, 2024 |
| HP            | ProBook 650 G3              | Notebook    | [e2f71d285f](https://linux-hardware.org/?probe=e2f71d285f) | Apr 28, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [f7d0515f40](https://linux-hardware.org/?probe=f7d0515f40) | Apr 26, 2024 |
| HP            | ZBook 17 G3                 | Notebook    | [05ef86a1b6](https://linux-hardware.org/?probe=05ef86a1b6) | Apr 25, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [ec99c46757](https://linux-hardware.org/?probe=ec99c46757) | Apr 25, 2024 |
| Dell          | Latitude E6440              | Notebook    | [84566c2460](https://linux-hardware.org/?probe=84566c2460) | Apr 24, 2024 |
| Dell          | Latitude E6440              | Notebook    | [3b5213b70a](https://linux-hardware.org/?probe=3b5213b70a) | Apr 24, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [488c5e3d42](https://linux-hardware.org/?probe=488c5e3d42) | Apr 23, 2024 |
| Dell          | Precision 7720              | Notebook    | [53cebf5b16](https://linux-hardware.org/?probe=53cebf5b16) | Apr 20, 2024 |
| HP            | 339A                        | Desktop     | [8cb48fe045](https://linux-hardware.org/?probe=8cb48fe045) | Apr 19, 2024 |
| HP            | ProBook 640 G2              | Notebook    | [76e18e23c3](https://linux-hardware.org/?probe=76e18e23c3) | Apr 19, 2024 |
| ASUSTek       | H61M-C                      | Desktop     | [a0e36b103b](https://linux-hardware.org/?probe=a0e36b103b) | Apr 10, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [35d9b4afce](https://linux-hardware.org/?probe=35d9b4afce) | Apr 07, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [490787ceee](https://linux-hardware.org/?probe=490787ceee) | Apr 07, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [cf5333f4e5](https://linux-hardware.org/?probe=cf5333f4e5) | Apr 06, 2024 |
| MSI           | Unknown                     | Notebook    | [4eef9d4799](https://linux-hardware.org/?probe=4eef9d4799) | Apr 05, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [1d1175f274](https://linux-hardware.org/?probe=1d1175f274) | Apr 04, 2024 |
| HP            | Pro x2 612 G2               | Tablet      | [78020fe4fb](https://linux-hardware.org/?probe=78020fe4fb) | Apr 04, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [becc45e734](https://linux-hardware.org/?probe=becc45e734) | Apr 04, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [779b1b8228](https://linux-hardware.org/?probe=779b1b8228) | Apr 04, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [efd659b2da](https://linux-hardware.org/?probe=efd659b2da) | Apr 01, 2024 |
| Dell          | Latitude 5400               | Notebook    | [7c41e018c9](https://linux-hardware.org/?probe=7c41e018c9) | Mar 28, 2024 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [f51533e204](https://linux-hardware.org/?probe=f51533e204) | Mar 25, 2024 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [bb3d04acc5](https://linux-hardware.org/?probe=bb3d04acc5) | Mar 23, 2024 |
| MSI           | CR610M                      | Notebook    | [7b139fb61c](https://linux-hardware.org/?probe=7b139fb61c) | Mar 23, 2024 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [3cab34a6cb](https://linux-hardware.org/?probe=3cab34a6cb) | Mar 23, 2024 |
| Dell          | XPS 13 9343                 | Notebook    | [46380bc9fe](https://linux-hardware.org/?probe=46380bc9fe) | Mar 23, 2024 |
| ASUSTek       | X450LD                      | Notebook    | [a3b7b15fa7](https://linux-hardware.org/?probe=a3b7b15fa7) | Mar 22, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8b380f5ddd](https://linux-hardware.org/?probe=8b380f5ddd) | Mar 21, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [60437d07d3](https://linux-hardware.org/?probe=60437d07d3) | Mar 19, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [9ef0fec665](https://linux-hardware.org/?probe=9ef0fec665) | Mar 18, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [42a5d23a39](https://linux-hardware.org/?probe=42a5d23a39) | Mar 16, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [43b39cedea](https://linux-hardware.org/?probe=43b39cedea) | Mar 16, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ea5a34f828](https://linux-hardware.org/?probe=ea5a34f828) | Mar 15, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b9dc85b113](https://linux-hardware.org/?probe=b9dc85b113) | Mar 14, 2024 |
| HP            | 1998                        | Desktop     | [e51bd4abc7](https://linux-hardware.org/?probe=e51bd4abc7) | Mar 14, 2024 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [00c46d511e](https://linux-hardware.org/?probe=00c46d511e) | Mar 06, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [b4a202211e](https://linux-hardware.org/?probe=b4a202211e) | Mar 06, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [b4bc485d5e](https://linux-hardware.org/?probe=b4bc485d5e) | Mar 03, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [f176927a8f](https://linux-hardware.org/?probe=f176927a8f) | Mar 02, 2024 |
| Dell          | System XPS L502X            | Notebook    | [c289512484](https://linux-hardware.org/?probe=c289512484) | Feb 29, 2024 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [6df147d26d](https://linux-hardware.org/?probe=6df147d26d) | Feb 27, 2024 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [4510503539](https://linux-hardware.org/?probe=4510503539) | Feb 27, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [41dbc538ba](https://linux-hardware.org/?probe=41dbc538ba) | Feb 26, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f760d848e](https://linux-hardware.org/?probe=3f760d848e) | Feb 26, 2024 |
| ASUSTek       | N53SN                       | Notebook    | [121581f984](https://linux-hardware.org/?probe=121581f984) | Feb 23, 2024 |
| ASUSTek       | T303UA                      | Tablet      | [503d57f0a5](https://linux-hardware.org/?probe=503d57f0a5) | Feb 20, 2024 |
| Sony          | VGN-SR35G_B                 | Notebook    | [aaa8b6533c](https://linux-hardware.org/?probe=aaa8b6533c) | Feb 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [e477ab47a2](https://linux-hardware.org/?probe=e477ab47a2) | Feb 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [6afbbfd5d0](https://linux-hardware.org/?probe=6afbbfd5d0) | Feb 19, 2024 |
| I-life        | ZEDNOTE                     | Notebook    | [ceefa317d1](https://linux-hardware.org/?probe=ceefa317d1) | Feb 18, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [0c55d1c68f](https://linux-hardware.org/?probe=0c55d1c68f) | Feb 17, 2024 |
| ASUSTek       | X555YI                      | Notebook    | [9fcad9e566](https://linux-hardware.org/?probe=9fcad9e566) | Feb 16, 2024 |
| MSI           | CR610M                      | Notebook    | [cc4ca57086](https://linux-hardware.org/?probe=cc4ca57086) | Feb 13, 2024 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [98dd82d807](https://linux-hardware.org/?probe=98dd82d807) | Feb 12, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [26a59a1a00](https://linux-hardware.org/?probe=26a59a1a00) | Feb 11, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [3e88e5f74b](https://linux-hardware.org/?probe=3e88e5f74b) | Feb 10, 2024 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [255ad6e265](https://linux-hardware.org/?probe=255ad6e265) | Feb 09, 2024 |
| MSI           | MS-7388                     | Desktop     | [e9a8006742](https://linux-hardware.org/?probe=e9a8006742) | Feb 05, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [f2b4ad5d19](https://linux-hardware.org/?probe=f2b4ad5d19) | Jan 30, 2024 |
| Acer          | Aspire VN7-571G             | Notebook    | [b5f8437f3c](https://linux-hardware.org/?probe=b5f8437f3c) | Jan 28, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [b6507e7469](https://linux-hardware.org/?probe=b6507e7469) | Jan 25, 2024 |
| Rockchip      | RK3288 Asus Tinker          | Soc         | [b21fbd5b1c](https://linux-hardware.org/?probe=b21fbd5b1c) | Jan 22, 2024 |
| HP            | 82B4                        | Desktop     | [0eca4196b3](https://linux-hardware.org/?probe=0eca4196b3) | Jan 21, 2024 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [cd1e18703e](https://linux-hardware.org/?probe=cd1e18703e) | Jan 19, 2024 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [f07c9d75f0](https://linux-hardware.org/?probe=f07c9d75f0) | Jan 18, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [3437acb566](https://linux-hardware.org/?probe=3437acb566) | Jan 15, 2024 |
| HP            | ProLiant DL380 Gen9         | Server      | [8f3bf0ff17](https://linux-hardware.org/?probe=8f3bf0ff17) | Jan 15, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [c0f0afd78c](https://linux-hardware.org/?probe=c0f0afd78c) | Jan 14, 2024 |
| MSI           | Unknown                     | Notebook    | [e8e49c344d](https://linux-hardware.org/?probe=e8e49c344d) | Jan 14, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [5654e285db](https://linux-hardware.org/?probe=5654e285db) | Jan 10, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [234e6e24b3](https://linux-hardware.org/?probe=234e6e24b3) | Jan 10, 2024 |
| HP            | 17E2                        | Mini pc     | [a2be55ec15](https://linux-hardware.org/?probe=a2be55ec15) | Jan 09, 2024 |
| Lenovo        | ThinkPad X260 20F5A1AC00    | Notebook    | [b14e96fc5f](https://linux-hardware.org/?probe=b14e96fc5f) | Jan 03, 2024 |
| Dell          | Latitude E5470              | Notebook    | [fdc804210f](https://linux-hardware.org/?probe=fdc804210f) | Jan 01, 2024 |
| Dell          | Vostro 2420                 | Notebook    | [52ae549c99](https://linux-hardware.org/?probe=52ae549c99) | Dec 28, 2023 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [8f6b669800](https://linux-hardware.org/?probe=8f6b669800) | Dec 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [1f73670f10](https://linux-hardware.org/?probe=1f73670f10) | Dec 27, 2023 |
| ASUSTek       | H81-PLUS                    | Desktop     | [359af07cb2](https://linux-hardware.org/?probe=359af07cb2) | Dec 19, 2023 |
| ASUSTek       | H81-PLUS                    | Desktop     | [b4b91802b5](https://linux-hardware.org/?probe=b4b91802b5) | Dec 19, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [bad7f51319](https://linux-hardware.org/?probe=bad7f51319) | Dec 18, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [c3968eb521](https://linux-hardware.org/?probe=c3968eb521) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [b4bcda5523](https://linux-hardware.org/?probe=b4bcda5523) | Dec 15, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [fecb896f9f](https://linux-hardware.org/?probe=fecb896f9f) | Dec 14, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [899db988cc](https://linux-hardware.org/?probe=899db988cc) | Dec 12, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [eed0305500](https://linux-hardware.org/?probe=eed0305500) | Dec 10, 2023 |
| MSI           | CR610M                      | Notebook    | [f182f4595a](https://linux-hardware.org/?probe=f182f4595a) | Dec 10, 2023 |
| Unknown       | Apple MacBook Air (13-in... | Notebook    | [15b9622f09](https://linux-hardware.org/?probe=15b9622f09) | Dec 09, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ae0afe3e73](https://linux-hardware.org/?probe=ae0afe3e73) | Dec 09, 2023 |
| Unknown       | Apple MacBook Air (13-in... | Notebook    | [28887ed4c5](https://linux-hardware.org/?probe=28887ed4c5) | Dec 09, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d0e32e1ab3](https://linux-hardware.org/?probe=d0e32e1ab3) | Dec 08, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d1ad1e6658](https://linux-hardware.org/?probe=d1ad1e6658) | Dec 08, 2023 |
| HP            | 339A                        | Desktop     | [a114886e67](https://linux-hardware.org/?probe=a114886e67) | Dec 07, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [0e087e0b94](https://linux-hardware.org/?probe=0e087e0b94) | Dec 07, 2023 |
| HP            | 3646h                       | Desktop     | [df62144cda](https://linux-hardware.org/?probe=df62144cda) | Dec 05, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | Notebook    | [0c680c33ec](https://linux-hardware.org/?probe=0c680c33ec) | Dec 05, 2023 |
| Acer          | Aspire A715-76G             | Notebook    | [11e0ab5e1b](https://linux-hardware.org/?probe=11e0ab5e1b) | Dec 05, 2023 |
| Samsung       | QX311/QX411/QX412/QX511     | Notebook    | [a82cdb418c](https://linux-hardware.org/?probe=a82cdb418c) | Dec 01, 2023 |
| MSI           | CR610M                      | Notebook    | [35d23c9d26](https://linux-hardware.org/?probe=35d23c9d26) | Nov 30, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [9fa48c41da](https://linux-hardware.org/?probe=9fa48c41da) | Nov 27, 2023 |
| Samsung       | QX311/QX411/QX412/QX511     | Notebook    | [746bd8c3d5](https://linux-hardware.org/?probe=746bd8c3d5) | Nov 21, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [aa86ed33d3](https://linux-hardware.org/?probe=aa86ed33d3) | Nov 21, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [5f26bd4798](https://linux-hardware.org/?probe=5f26bd4798) | Nov 21, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [ed1bde2ed6](https://linux-hardware.org/?probe=ed1bde2ed6) | Nov 20, 2023 |
| MSI           | CR610M                      | Notebook    | [66ca456fa1](https://linux-hardware.org/?probe=66ca456fa1) | Nov 19, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [4243816d27](https://linux-hardware.org/?probe=4243816d27) | Nov 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [111e6f3234](https://linux-hardware.org/?probe=111e6f3234) | Nov 16, 2023 |
| HP            | Compaq 6910p                | Notebook    | [019a154d30](https://linux-hardware.org/?probe=019a154d30) | Nov 14, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [0b16b45e10](https://linux-hardware.org/?probe=0b16b45e10) | Nov 14, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [f307d97867](https://linux-hardware.org/?probe=f307d97867) | Nov 13, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [8599ff1b2c](https://linux-hardware.org/?probe=8599ff1b2c) | Nov 13, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [238ea043b4](https://linux-hardware.org/?probe=238ea043b4) | Nov 10, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [0f6145e565](https://linux-hardware.org/?probe=0f6145e565) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [c8cbd7f579](https://linux-hardware.org/?probe=c8cbd7f579) | Nov 09, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [80fb26e63a](https://linux-hardware.org/?probe=80fb26e63a) | Nov 03, 2023 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [555d634638](https://linux-hardware.org/?probe=555d634638) | Nov 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [af854a07c5](https://linux-hardware.org/?probe=af854a07c5) | Oct 31, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [fadc897ee2](https://linux-hardware.org/?probe=fadc897ee2) | Oct 31, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [0e14e6c7dc](https://linux-hardware.org/?probe=0e14e6c7dc) | Oct 30, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [23fdd2c31d](https://linux-hardware.org/?probe=23fdd2c31d) | Oct 30, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [f3f325941b](https://linux-hardware.org/?probe=f3f325941b) | Oct 25, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [1b88e8b489](https://linux-hardware.org/?probe=1b88e8b489) | Oct 25, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [1cc18d5c46](https://linux-hardware.org/?probe=1cc18d5c46) | Oct 25, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [b003720f21](https://linux-hardware.org/?probe=b003720f21) | Oct 23, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [6a5182fc9c](https://linux-hardware.org/?probe=6a5182fc9c) | Oct 20, 2023 |
| Dell          | Latitude E5470              | Notebook    | [be8c08b665](https://linux-hardware.org/?probe=be8c08b665) | Oct 18, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [fa78f5938c](https://linux-hardware.org/?probe=fa78f5938c) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [7045758f33](https://linux-hardware.org/?probe=7045758f33) | Oct 13, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [bef1086dfe](https://linux-hardware.org/?probe=bef1086dfe) | Oct 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [21d197e617](https://linux-hardware.org/?probe=21d197e617) | Oct 05, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [68e28eea76](https://linux-hardware.org/?probe=68e28eea76) | Oct 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f0b1db1bfd](https://linux-hardware.org/?probe=f0b1db1bfd) | Oct 03, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [394ad8616c](https://linux-hardware.org/?probe=394ad8616c) | Oct 02, 2023 |
| Dell          | Vostro 3360                 | Notebook    | [812367b788](https://linux-hardware.org/?probe=812367b788) | Sep 27, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [8c38084e7e](https://linux-hardware.org/?probe=8c38084e7e) | Sep 27, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [8da87a8c78](https://linux-hardware.org/?probe=8da87a8c78) | Sep 26, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [cba55a15ec](https://linux-hardware.org/?probe=cba55a15ec) | Sep 24, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e6bd73a6e1](https://linux-hardware.org/?probe=e6bd73a6e1) | Sep 24, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [169fe58269](https://linux-hardware.org/?probe=169fe58269) | Sep 22, 2023 |
| MSI           | CR610M                      | Notebook    | [5a9d9ba5ae](https://linux-hardware.org/?probe=5a9d9ba5ae) | Sep 22, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [5dae6d6eda](https://linux-hardware.org/?probe=5dae6d6eda) | Sep 21, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [ae062bd5ca](https://linux-hardware.org/?probe=ae062bd5ca) | Sep 21, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [ddf1d6a712](https://linux-hardware.org/?probe=ddf1d6a712) | Sep 20, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [4064a0898f](https://linux-hardware.org/?probe=4064a0898f) | Sep 20, 2023 |
| HP            | 3397                        | Desktop     | [f202c90e23](https://linux-hardware.org/?probe=f202c90e23) | Sep 20, 2023 |
| Dell          | Latitude E5470              | Notebook    | [0602c2deb2](https://linux-hardware.org/?probe=0602c2deb2) | Sep 16, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [ec5b4aeb84](https://linux-hardware.org/?probe=ec5b4aeb84) | Sep 15, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [db2962124c](https://linux-hardware.org/?probe=db2962124c) | Sep 14, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [cf48b0b959](https://linux-hardware.org/?probe=cf48b0b959) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a68551130a](https://linux-hardware.org/?probe=a68551130a) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3edc89267d](https://linux-hardware.org/?probe=3edc89267d) | Sep 13, 2023 |
| ECS           | A880GM-AD3                  | Desktop     | [828f89ff31](https://linux-hardware.org/?probe=828f89ff31) | Sep 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [be2af85bb7](https://linux-hardware.org/?probe=be2af85bb7) | Sep 12, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [f090137faf](https://linux-hardware.org/?probe=f090137faf) | Sep 11, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [d93600fc7c](https://linux-hardware.org/?probe=d93600fc7c) | Sep 11, 2023 |
| Gigabyte      | H110M-S2PT-CF               | Desktop     | [83ff674ae7](https://linux-hardware.org/?probe=83ff674ae7) | Sep 10, 2023 |
| HP            | 8266                        | Desktop     | [fed6cc89fe](https://linux-hardware.org/?probe=fed6cc89fe) | Sep 09, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [24a7c8a496](https://linux-hardware.org/?probe=24a7c8a496) | Sep 04, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [00a308aa4a](https://linux-hardware.org/?probe=00a308aa4a) | Sep 01, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [10db09006a](https://linux-hardware.org/?probe=10db09006a) | Aug 31, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [2d74d46701](https://linux-hardware.org/?probe=2d74d46701) | Aug 30, 2023 |
| HP            | 83DD                        | Mini pc     | [2955a0b6c5](https://linux-hardware.org/?probe=2955a0b6c5) | Aug 30, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | Notebook    | [243b20df85](https://linux-hardware.org/?probe=243b20df85) | Aug 28, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | Notebook    | [8cbbb0c64a](https://linux-hardware.org/?probe=8cbbb0c64a) | Aug 28, 2023 |
| MSI           | 970A-G46                    | Desktop     | [5b4c3411dc](https://linux-hardware.org/?probe=5b4c3411dc) | Aug 28, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [df71a92503](https://linux-hardware.org/?probe=df71a92503) | Aug 26, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [4f74cc24e0](https://linux-hardware.org/?probe=4f74cc24e0) | Aug 26, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [b9187b37b7](https://linux-hardware.org/?probe=b9187b37b7) | Aug 24, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [7041925c33](https://linux-hardware.org/?probe=7041925c33) | Aug 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [c61948c95e](https://linux-hardware.org/?probe=c61948c95e) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [6947635a16](https://linux-hardware.org/?probe=6947635a16) | Aug 18, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [dbee57dbed](https://linux-hardware.org/?probe=dbee57dbed) | Aug 17, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [c24cfbc475](https://linux-hardware.org/?probe=c24cfbc475) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6077ff7606](https://linux-hardware.org/?probe=6077ff7606) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [25f4c96f7b](https://linux-hardware.org/?probe=25f4c96f7b) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [3048a8eb60](https://linux-hardware.org/?probe=3048a8eb60) | Aug 12, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [2df5a4bd58](https://linux-hardware.org/?probe=2df5a4bd58) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1bf7b69b0f](https://linux-hardware.org/?probe=1bf7b69b0f) | Aug 11, 2023 |
| Dell          | Latitude E6400              | Notebook    | [f28a234c30](https://linux-hardware.org/?probe=f28a234c30) | Aug 10, 2023 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [cb8ad3e0fc](https://linux-hardware.org/?probe=cb8ad3e0fc) | Aug 10, 2023 |
| HP            | 8456                        | Desktop     | [fa8ea86591](https://linux-hardware.org/?probe=fa8ea86591) | Aug 08, 2023 |
| Sony          | VGN-FW373D                  | Notebook    | [535f0edf33](https://linux-hardware.org/?probe=535f0edf33) | Aug 04, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9f3cef93ed](https://linux-hardware.org/?probe=9f3cef93ed) | Aug 03, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [79c3c3612b](https://linux-hardware.org/?probe=79c3c3612b) | Aug 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d9db031e65](https://linux-hardware.org/?probe=d9db031e65) | Aug 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [7ed6a80c20](https://linux-hardware.org/?probe=7ed6a80c20) | Aug 01, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [96a30f2f21](https://linux-hardware.org/?probe=96a30f2f21) | Jul 27, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [fd2bcebb1d](https://linux-hardware.org/?probe=fd2bcebb1d) | Jul 22, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [daff830182](https://linux-hardware.org/?probe=daff830182) | Jul 21, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [173929b667](https://linux-hardware.org/?probe=173929b667) | Jul 19, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [b86a3c24df](https://linux-hardware.org/?probe=b86a3c24df) | Jul 16, 2023 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [8a2aeb02b0](https://linux-hardware.org/?probe=8a2aeb02b0) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [adab548264](https://linux-hardware.org/?probe=adab548264) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [ce2deb4b1d](https://linux-hardware.org/?probe=ce2deb4b1d) | Jul 13, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [fa3485dbc6](https://linux-hardware.org/?probe=fa3485dbc6) | Jul 13, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [26c6ceb0a6](https://linux-hardware.org/?probe=26c6ceb0a6) | Jul 13, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [779f922cbb](https://linux-hardware.org/?probe=779f922cbb) | Jul 12, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [13ece994a6](https://linux-hardware.org/?probe=13ece994a6) | Jul 09, 2023 |
| Unknown       | CoffeeLake                  | Desktop     | [b3f96a87d5](https://linux-hardware.org/?probe=b3f96a87d5) | Jul 09, 2023 |
| HP            | 18E7                        | Desktop     | [8157fe83c7](https://linux-hardware.org/?probe=8157fe83c7) | Jul 09, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a760e46715](https://linux-hardware.org/?probe=a760e46715) | Jul 08, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1a53ce97b8](https://linux-hardware.org/?probe=1a53ce97b8) | Jul 07, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [465b44efff](https://linux-hardware.org/?probe=465b44efff) | Jul 01, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [826e649d7a](https://linux-hardware.org/?probe=826e649d7a) | Jul 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [df0ca94515](https://linux-hardware.org/?probe=df0ca94515) | Jun 29, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [47451d9f30](https://linux-hardware.org/?probe=47451d9f30) | Jun 27, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [d675031e74](https://linux-hardware.org/?probe=d675031e74) | Jun 26, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [37e828b0b6](https://linux-hardware.org/?probe=37e828b0b6) | Jun 24, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [0908f99494](https://linux-hardware.org/?probe=0908f99494) | Jun 23, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [1999834725](https://linux-hardware.org/?probe=1999834725) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [e1678729ff](https://linux-hardware.org/?probe=e1678729ff) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [094d8e8ecf](https://linux-hardware.org/?probe=094d8e8ecf) | Jun 22, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a013e4866a](https://linux-hardware.org/?probe=a013e4866a) | Jun 22, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6c766e53cb](https://linux-hardware.org/?probe=6c766e53cb) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [91e2324734](https://linux-hardware.org/?probe=91e2324734) | Jun 20, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [cd78108f1f](https://linux-hardware.org/?probe=cd78108f1f) | Jun 19, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [eb29f214f3](https://linux-hardware.org/?probe=eb29f214f3) | Jun 17, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a7728ed657](https://linux-hardware.org/?probe=a7728ed657) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [03c8eed64b](https://linux-hardware.org/?probe=03c8eed64b) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [9b08f8189d](https://linux-hardware.org/?probe=9b08f8189d) | Jun 15, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [a5cbd2e848](https://linux-hardware.org/?probe=a5cbd2e848) | Jun 14, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [9f26d41d53](https://linux-hardware.org/?probe=9f26d41d53) | Jun 14, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [1c33fe3f61](https://linux-hardware.org/?probe=1c33fe3f61) | Jun 12, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [63c110632a](https://linux-hardware.org/?probe=63c110632a) | Jun 10, 2023 |
| Dell          | Latitude E5470              | Notebook    | [c9b909273b](https://linux-hardware.org/?probe=c9b909273b) | Jun 09, 2023 |
| Biostar       | A68N-2100K                  | Desktop     | [9ac86a512d](https://linux-hardware.org/?probe=9ac86a512d) | Jun 09, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [262ee566e1](https://linux-hardware.org/?probe=262ee566e1) | Jun 06, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [b6613930a2](https://linux-hardware.org/?probe=b6613930a2) | Jun 05, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [5102ecc266](https://linux-hardware.org/?probe=5102ecc266) | Jun 04, 2023 |
| Sony          | VPCEA45FG                   | Notebook    | [873ca04445](https://linux-hardware.org/?probe=873ca04445) | May 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [c2125f60d2](https://linux-hardware.org/?probe=c2125f60d2) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 80XB     | Convertible | [9e2f0c46ef](https://linux-hardware.org/?probe=9e2f0c46ef) | May 20, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [061e1e2aec](https://linux-hardware.org/?probe=061e1e2aec) | May 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0GK0... | Notebook    | [177f30243c](https://linux-hardware.org/?probe=177f30243c) | May 08, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [2cbff804d8](https://linux-hardware.org/?probe=2cbff804d8) | May 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [728b1e3209](https://linux-hardware.org/?probe=728b1e3209) | May 03, 2023 |
| Toshiba       | Satellite C640              | Notebook    | [20d436bfa7](https://linux-hardware.org/?probe=20d436bfa7) | May 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9a43268d9b](https://linux-hardware.org/?probe=9a43268d9b) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [5086f7f4a2](https://linux-hardware.org/?probe=5086f7f4a2) | May 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [dd0a47b6fc](https://linux-hardware.org/?probe=dd0a47b6fc) | May 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [7087295cd7](https://linux-hardware.org/?probe=7087295cd7) | May 01, 2023 |
| ASUSTek       | H110-PLUS                   | Desktop     | [f8317bce7b](https://linux-hardware.org/?probe=f8317bce7b) | Apr 26, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [e37aab534f](https://linux-hardware.org/?probe=e37aab534f) | Apr 24, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [a8644a5b03](https://linux-hardware.org/?probe=a8644a5b03) | Apr 23, 2023 |
| Sony          | VGN-SZ640N                  | Notebook    | [659b01c666](https://linux-hardware.org/?probe=659b01c666) | Apr 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c10e38e18e](https://linux-hardware.org/?probe=c10e38e18e) | Apr 20, 2023 |
| Toshiba       | Satellite A100              | Notebook    | [f95e411124](https://linux-hardware.org/?probe=f95e411124) | Apr 20, 2023 |
| HP            | ZBook 15                    | Notebook    | [c5397a7fbb](https://linux-hardware.org/?probe=c5397a7fbb) | Apr 14, 2023 |
| HP            | ZBook 15                    | Notebook    | [aaaa838a8f](https://linux-hardware.org/?probe=aaaa838a8f) | Apr 13, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [110fdee9b2](https://linux-hardware.org/?probe=110fdee9b2) | Apr 10, 2023 |
| Lenovo        | ThinkPad T420 4178A4G       | Notebook    | [206861226d](https://linux-hardware.org/?probe=206861226d) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [9e7e969310](https://linux-hardware.org/?probe=9e7e969310) | Apr 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a64c365f62](https://linux-hardware.org/?probe=a64c365f62) | Apr 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0a028a43f8](https://linux-hardware.org/?probe=0a028a43f8) | Apr 01, 2023 |
| ASUSTek       | X555BP                      | Notebook    | [c7f621e335](https://linux-hardware.org/?probe=c7f621e335) | Apr 01, 2023 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [4a7e7763c1](https://linux-hardware.org/?probe=4a7e7763c1) | Mar 28, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [54f096fd88](https://linux-hardware.org/?probe=54f096fd88) | Mar 27, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [ac6cf948d5](https://linux-hardware.org/?probe=ac6cf948d5) | Mar 27, 2023 |
| YANYU         | ITX-S192                    | Desktop     | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [fcd077e70a](https://linux-hardware.org/?probe=fcd077e70a) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [e4a88fa14e](https://linux-hardware.org/?probe=e4a88fa14e) | Mar 27, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [30e77255e4](https://linux-hardware.org/?probe=30e77255e4) | Mar 20, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [95ae633abb](https://linux-hardware.org/?probe=95ae633abb) | Mar 19, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [54025a10f5](https://linux-hardware.org/?probe=54025a10f5) | Mar 19, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [5f73fa5db7](https://linux-hardware.org/?probe=5f73fa5db7) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [51ec4d252f](https://linux-hardware.org/?probe=51ec4d252f) | Mar 17, 2023 |
| ASUSTek       | P5P43TD                     | Desktop     | [f2be993036](https://linux-hardware.org/?probe=f2be993036) | Mar 13, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5e4e9bde6f](https://linux-hardware.org/?probe=5e4e9bde6f) | Mar 03, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [7f72d6bba7](https://linux-hardware.org/?probe=7f72d6bba7) | Feb 26, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [d81c35b55b](https://linux-hardware.org/?probe=d81c35b55b) | Feb 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [6d36ab1fcf](https://linux-hardware.org/?probe=6d36ab1fcf) | Feb 24, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [0a1b4d8122](https://linux-hardware.org/?probe=0a1b4d8122) | Feb 23, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [72f074b930](https://linux-hardware.org/?probe=72f074b930) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [c6d06c27c7](https://linux-hardware.org/?probe=c6d06c27c7) | Feb 19, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [3932889971](https://linux-hardware.org/?probe=3932889971) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f6276d350a](https://linux-hardware.org/?probe=f6276d350a) | Feb 08, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [1b800ff8c2](https://linux-hardware.org/?probe=1b800ff8c2) | Feb 07, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [69f96bffa5](https://linux-hardware.org/?probe=69f96bffa5) | Feb 07, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [787543930a](https://linux-hardware.org/?probe=787543930a) | Feb 07, 2023 |
| Acer          | Aspire VN7-592G             | Notebook    | [a313fa3b83](https://linux-hardware.org/?probe=a313fa3b83) | Feb 02, 2023 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [e64a1e0a5a](https://linux-hardware.org/?probe=e64a1e0a5a) | Jan 31, 2023 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [4427845ac1](https://linux-hardware.org/?probe=4427845ac1) | Jan 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [2b2401b0f0](https://linux-hardware.org/?probe=2b2401b0f0) | Jan 28, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [17b4a2466c](https://linux-hardware.org/?probe=17b4a2466c) | Jan 20, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8474e8ce69](https://linux-hardware.org/?probe=8474e8ce69) | Jan 17, 2023 |
| HP            | 805A                        | Desktop     | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [b325ae9a48](https://linux-hardware.org/?probe=b325ae9a48) | Jan 11, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [268f34635a](https://linux-hardware.org/?probe=268f34635a) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d70aca4ad6](https://linux-hardware.org/?probe=d70aca4ad6) | Dec 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a6d43b6afd](https://linux-hardware.org/?probe=a6d43b6afd) | Dec 22, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [4d24d45918](https://linux-hardware.org/?probe=4d24d45918) | Dec 21, 2022 |
| Acer          | Predator PH315-55           | Notebook    | [01ba4c7b4a](https://linux-hardware.org/?probe=01ba4c7b4a) | Dec 16, 2022 |
| Acer          | Predator PH315-55           | Notebook    | [e2297c201d](https://linux-hardware.org/?probe=e2297c201d) | Dec 16, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d1342c521a](https://linux-hardware.org/?probe=d1342c521a) | Dec 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5c0099832f](https://linux-hardware.org/?probe=5c0099832f) | Dec 15, 2022 |
| HP            | Pavilion g6                 | Notebook    | [1120db45a3](https://linux-hardware.org/?probe=1120db45a3) | Dec 13, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [df78e85dfe](https://linux-hardware.org/?probe=df78e85dfe) | Dec 08, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [a1ec8cb1b2](https://linux-hardware.org/?probe=a1ec8cb1b2) | Nov 29, 2022 |
| HP            | 3397                        | Desktop     | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| HPE           | ProLiant DL380 Gen10        | Server      | [4cdcad1148](https://linux-hardware.org/?probe=4cdcad1148) | Nov 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2c8a884430](https://linux-hardware.org/?probe=2c8a884430) | Nov 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [451d2e210d](https://linux-hardware.org/?probe=451d2e210d) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [51809e1ff3](https://linux-hardware.org/?probe=51809e1ff3) | Nov 11, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [f8cd836199](https://linux-hardware.org/?probe=f8cd836199) | Nov 10, 2022 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [db0a79fbd9](https://linux-hardware.org/?probe=db0a79fbd9) | Nov 07, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [0d4536a010](https://linux-hardware.org/?probe=0d4536a010) | Nov 07, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [f22f67754e](https://linux-hardware.org/?probe=f22f67754e) | Oct 29, 2022 |
| MSI           | Modern 15 A10RBS            | Notebook    | [ddc3eded89](https://linux-hardware.org/?probe=ddc3eded89) | Oct 28, 2022 |
| HP            | G62                         | Notebook    | [a7b5ac8e19](https://linux-hardware.org/?probe=a7b5ac8e19) | Oct 20, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [6459e3fedb](https://linux-hardware.org/?probe=6459e3fedb) | Oct 16, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [5192a80499](https://linux-hardware.org/?probe=5192a80499) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | G62                         | Notebook    | [dbe9a778bb](https://linux-hardware.org/?probe=dbe9a778bb) | Oct 12, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| ASUSTek       | UX490UA                     | Notebook    | [e953c29d50](https://linux-hardware.org/?probe=e953c29d50) | Sep 19, 2022 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [d8be5e602a](https://linux-hardware.org/?probe=d8be5e602a) | Sep 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [a15d189c98](https://linux-hardware.org/?probe=a15d189c98) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0737d49df2](https://linux-hardware.org/?probe=0737d49df2) | Sep 15, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [968826d76c](https://linux-hardware.org/?probe=968826d76c) | Sep 13, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [8718c2bb09](https://linux-hardware.org/?probe=8718c2bb09) | Sep 12, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [33c08b8aef](https://linux-hardware.org/?probe=33c08b8aef) | Sep 09, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [c803fe67f3](https://linux-hardware.org/?probe=c803fe67f3) | Sep 08, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c98348c9a3](https://linux-hardware.org/?probe=c98348c9a3) | Sep 07, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [68b6da5fe1](https://linux-hardware.org/?probe=68b6da5fe1) | Sep 04, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [349fc1d85c](https://linux-hardware.org/?probe=349fc1d85c) | Sep 03, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [f0d85f4991](https://linux-hardware.org/?probe=f0d85f4991) | Sep 03, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ec5bb450ff](https://linux-hardware.org/?probe=ec5bb450ff) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | Notebook    | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [393cb25da2](https://linux-hardware.org/?probe=393cb25da2) | Aug 30, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c96e8a8254](https://linux-hardware.org/?probe=c96e8a8254) | Aug 30, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [a8b586b903](https://linux-hardware.org/?probe=a8b586b903) | Aug 27, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [93ac400083](https://linux-hardware.org/?probe=93ac400083) | Aug 23, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [8d187f0a28](https://linux-hardware.org/?probe=8d187f0a28) | Aug 22, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [c8f8e78df8](https://linux-hardware.org/?probe=c8f8e78df8) | Aug 17, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [fa12e95e32](https://linux-hardware.org/?probe=fa12e95e32) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a36a32eb0e](https://linux-hardware.org/?probe=a36a32eb0e) | Aug 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [759c9dee6b](https://linux-hardware.org/?probe=759c9dee6b) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [1636ef38d5](https://linux-hardware.org/?probe=1636ef38d5) | Aug 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [114ada270e](https://linux-hardware.org/?probe=114ada270e) | Aug 08, 2022 |
| ASUSTek       | H110M-C/PS                  | Desktop     | [b633163f9f](https://linux-hardware.org/?probe=b633163f9f) | Aug 06, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Timi          | RedmiBook 14                | Notebook    | [10c33f11cf](https://linux-hardware.org/?probe=10c33f11cf) | Aug 02, 2022 |
| Dell          | Latitude E7470              | Notebook    | [0851479f6b](https://linux-hardware.org/?probe=0851479f6b) | Aug 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [9996781aa7](https://linux-hardware.org/?probe=9996781aa7) | Jul 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [117f3d3969](https://linux-hardware.org/?probe=117f3d3969) | Jul 26, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb442470d4](https://linux-hardware.org/?probe=fb442470d4) | Jul 24, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [6f2adb5629](https://linux-hardware.org/?probe=6f2adb5629) | Jul 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [bc783f5d64](https://linux-hardware.org/?probe=bc783f5d64) | Jul 23, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [e632ef83da](https://linux-hardware.org/?probe=e632ef83da) | Jul 20, 2022 |
| HP            | G62                         | Notebook    | [bcb07d1cc9](https://linux-hardware.org/?probe=bcb07d1cc9) | Jul 16, 2022 |
| HP            | G62                         | Notebook    | [020a13b927](https://linux-hardware.org/?probe=020a13b927) | Jul 16, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [4e8aa38fb4](https://linux-hardware.org/?probe=4e8aa38fb4) | Jul 11, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [85845c3282](https://linux-hardware.org/?probe=85845c3282) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| ASUSTek       | N43JQ                       | Notebook    | [d73f714472](https://linux-hardware.org/?probe=d73f714472) | Jul 01, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| ASUSTek       | X542UN                      | Notebook    | [56e348118b](https://linux-hardware.org/?probe=56e348118b) | Jun 26, 2022 |
| HP            | 3397                        | Desktop     | [337e956c95](https://linux-hardware.org/?probe=337e956c95) | Jun 22, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [43cf14bdd7](https://linux-hardware.org/?probe=43cf14bdd7) | Jun 22, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| ASUSTek       | X542UN                      | Notebook    | [83a04b4dc4](https://linux-hardware.org/?probe=83a04b4dc4) | Jun 17, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [7b1a78a681](https://linux-hardware.org/?probe=7b1a78a681) | Jun 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2893254eb3](https://linux-hardware.org/?probe=2893254eb3) | Jun 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e64a2a0eeb](https://linux-hardware.org/?probe=e64a2a0eeb) | Jun 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b0e13d9a94](https://linux-hardware.org/?probe=b0e13d9a94) | Jun 05, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [05094a5491](https://linux-hardware.org/?probe=05094a5491) | Jun 05, 2022 |
| Lenovo        | ThinkPad E420 1141E9G       | Notebook    | [48b5588cbd](https://linux-hardware.org/?probe=48b5588cbd) | Jun 01, 2022 |
| ASUSTek       | Maximus II Formula          | Desktop     | [84df720c51](https://linux-hardware.org/?probe=84df720c51) | May 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [27dffb7089](https://linux-hardware.org/?probe=27dffb7089) | May 29, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8a4d6e798d](https://linux-hardware.org/?probe=8a4d6e798d) | May 26, 2022 |
| Toshiba       | Satellite Pro T130          | Notebook    | [2771a53784](https://linux-hardware.org/?probe=2771a53784) | May 23, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [232b74e86b](https://linux-hardware.org/?probe=232b74e86b) | May 17, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [1bce5b14e3](https://linux-hardware.org/?probe=1bce5b14e3) | May 17, 2022 |
| MSI           | 760GM-P33                   | Desktop     | [d37fca6b00](https://linux-hardware.org/?probe=d37fca6b00) | May 17, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [247fc8ed78](https://linux-hardware.org/?probe=247fc8ed78) | May 16, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [a0c15e2a2f](https://linux-hardware.org/?probe=a0c15e2a2f) | May 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8a9646dc78](https://linux-hardware.org/?probe=8a9646dc78) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [b6cb96e1d0](https://linux-hardware.org/?probe=b6cb96e1d0) | May 13, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [1d71c877c7](https://linux-hardware.org/?probe=1d71c877c7) | May 13, 2022 |
| Lenovo        | ThinkPad X230 23253QU       | Notebook    | [fde2b81a1c](https://linux-hardware.org/?probe=fde2b81a1c) | May 11, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [58b3a1b83d](https://linux-hardware.org/?probe=58b3a1b83d) | May 07, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [b53c2836e9](https://linux-hardware.org/?probe=b53c2836e9) | Apr 21, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [cb2bc8f53e](https://linux-hardware.org/?probe=cb2bc8f53e) | Apr 21, 2022 |
| Lenovo        | ThinkPad SL 2743X12         | Notebook    | [ad56efc5ff](https://linux-hardware.org/?probe=ad56efc5ff) | Apr 19, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [020929c7b4](https://linux-hardware.org/?probe=020929c7b4) | Apr 17, 2022 |
| HP            | 3048h                       | Desktop     | [2d19799047](https://linux-hardware.org/?probe=2d19799047) | Apr 14, 2022 |
| Gigabyte      | 945PL-S3                    | Desktop     | [a7da4b6ee0](https://linux-hardware.org/?probe=a7da4b6ee0) | Apr 14, 2022 |
| Gigabyte      | 945PL-S3                    | Desktop     | [a0ab75ee00](https://linux-hardware.org/?probe=a0ab75ee00) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [0809202e65](https://linux-hardware.org/?probe=0809202e65) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [a3f3072035](https://linux-hardware.org/?probe=a3f3072035) | Apr 12, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36c4b80dbb](https://linux-hardware.org/?probe=36c4b80dbb) | Apr 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000RAD     | Notebook    | [6f4db41ef5](https://linux-hardware.org/?probe=6f4db41ef5) | Apr 06, 2022 |
| Acer          | Aspire xxxx                 | Notebook    | [c389f4acb2](https://linux-hardware.org/?probe=c389f4acb2) | Apr 06, 2022 |
| Dell          | Latitude E7240              | Notebook    | [242cae44a5](https://linux-hardware.org/?probe=242cae44a5) | Apr 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [c0dd92f23c](https://linux-hardware.org/?probe=c0dd92f23c) | Apr 03, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [bfc20224d0](https://linux-hardware.org/?probe=bfc20224d0) | Mar 28, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [6e0eef7b54](https://linux-hardware.org/?probe=6e0eef7b54) | Mar 25, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5eb63254f8](https://linux-hardware.org/?probe=5eb63254f8) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5864c55419](https://linux-hardware.org/?probe=5864c55419) | Mar 19, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [08a511ac81](https://linux-hardware.org/?probe=08a511ac81) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [61b36dcd42](https://linux-hardware.org/?probe=61b36dcd42) | Mar 18, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [e3df8d9fc2](https://linux-hardware.org/?probe=e3df8d9fc2) | Mar 18, 2022 |
| Dell          | Latitude E7470              | Notebook    | [2eca1925d5](https://linux-hardware.org/?probe=2eca1925d5) | Mar 16, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b10d8b3a00](https://linux-hardware.org/?probe=b10d8b3a00) | Mar 16, 2022 |
| Dell          | Latitude E6530              | Notebook    | [2c3bfeff1d](https://linux-hardware.org/?probe=2c3bfeff1d) | Mar 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [472d23c4f4](https://linux-hardware.org/?probe=472d23c4f4) | Mar 13, 2022 |
| Gigabyte      | G1.Sniper 5                 | Desktop     | [1ee0fc40a2](https://linux-hardware.org/?probe=1ee0fc40a2) | Mar 12, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [0d2de64455](https://linux-hardware.org/?probe=0d2de64455) | Mar 06, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [76da8a616f](https://linux-hardware.org/?probe=76da8a616f) | Mar 05, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [91eafd1ed4](https://linux-hardware.org/?probe=91eafd1ed4) | Mar 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [dad6067f40](https://linux-hardware.org/?probe=dad6067f40) | Mar 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [29926fb03b](https://linux-hardware.org/?probe=29926fb03b) | Mar 03, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [071f146979](https://linux-hardware.org/?probe=071f146979) | Feb 24, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [fa0603a25d](https://linux-hardware.org/?probe=fa0603a25d) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [4d49233d4b](https://linux-hardware.org/?probe=4d49233d4b) | Feb 11, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [8294f013e8](https://linux-hardware.org/?probe=8294f013e8) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [93ca64d766](https://linux-hardware.org/?probe=93ca64d766) | Jan 28, 2022 |
| HP            | 8054                        | Desktop     | [332217129d](https://linux-hardware.org/?probe=332217129d) | Jan 26, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [c48fbc97e2](https://linux-hardware.org/?probe=c48fbc97e2) | Jan 22, 2022 |
| ECS           | H61H2-A                     | Desktop     | [90c26876b2](https://linux-hardware.org/?probe=90c26876b2) | Jan 21, 2022 |
| Alienware     | 17 R3                       | Notebook    | [032772ad42](https://linux-hardware.org/?probe=032772ad42) | Jan 20, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [e800e249d1](https://linux-hardware.org/?probe=e800e249d1) | Jan 19, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [104263a808](https://linux-hardware.org/?probe=104263a808) | Jan 19, 2022 |
| ECS           | H61H2-A                     | Desktop     | [518e31fcb0](https://linux-hardware.org/?probe=518e31fcb0) | Jan 13, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [6875440733](https://linux-hardware.org/?probe=6875440733) | Jan 10, 2022 |
| ASUSTek       | X450LC                      | Notebook    | [8228658808](https://linux-hardware.org/?probe=8228658808) | Jan 09, 2022 |
| ECS           | H61H2-A                     | Desktop     | [47fb5347c0](https://linux-hardware.org/?probe=47fb5347c0) | Jan 06, 2022 |
| ECS           | H61H2-A                     | Desktop     | [fa589d8ed4](https://linux-hardware.org/?probe=fa589d8ed4) | Jan 06, 2022 |
| HP            | 806A                        | Desktop     | [d7519db95a](https://linux-hardware.org/?probe=d7519db95a) | Jan 02, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [ba7acc9c68](https://linux-hardware.org/?probe=ba7acc9c68) | Jan 01, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [a175657549](https://linux-hardware.org/?probe=a175657549) | Dec 31, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [48423d0bef](https://linux-hardware.org/?probe=48423d0bef) | Dec 31, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [71a50bcb50](https://linux-hardware.org/?probe=71a50bcb50) | Dec 30, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d8d81e5c50](https://linux-hardware.org/?probe=d8d81e5c50) | Dec 30, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [71135c1724](https://linux-hardware.org/?probe=71135c1724) | Dec 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [9f22de7369](https://linux-hardware.org/?probe=9f22de7369) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [dcbbdb5fc5](https://linux-hardware.org/?probe=dcbbdb5fc5) | Dec 23, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [5408a1a82b](https://linux-hardware.org/?probe=5408a1a82b) | Dec 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [261f98a324](https://linux-hardware.org/?probe=261f98a324) | Dec 19, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [8e802c50ad](https://linux-hardware.org/?probe=8e802c50ad) | Dec 17, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [7b6f9acbf8](https://linux-hardware.org/?probe=7b6f9acbf8) | Dec 15, 2021 |
| HP            | 3397                        | Desktop     | [83d7b8fe86](https://linux-hardware.org/?probe=83d7b8fe86) | Dec 12, 2021 |
| HP            | 3397                        | Desktop     | [469adb677f](https://linux-hardware.org/?probe=469adb677f) | Dec 12, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [b4a346e899](https://linux-hardware.org/?probe=b4a346e899) | Dec 11, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [2c739999fa](https://linux-hardware.org/?probe=2c739999fa) | Dec 10, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [8473dd1cc0](https://linux-hardware.org/?probe=8473dd1cc0) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | Notebook    | [68820e21d2](https://linux-hardware.org/?probe=68820e21d2) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | Notebook    | [c7e180ab84](https://linux-hardware.org/?probe=c7e180ab84) | Dec 08, 2021 |
| Dell          | Latitude E7470              | Notebook    | [06666f541b](https://linux-hardware.org/?probe=06666f541b) | Dec 07, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [7eed1618fe](https://linux-hardware.org/?probe=7eed1618fe) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [01c7adcf94](https://linux-hardware.org/?probe=01c7adcf94) | Nov 28, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6eff02505f](https://linux-hardware.org/?probe=6eff02505f) | Nov 27, 2021 |
| HP            | EliteBook 745 G3            | Notebook    | [92968d4a23](https://linux-hardware.org/?probe=92968d4a23) | Nov 27, 2021 |
| ASUSTek       | Z170-PRO                    | Desktop     | [005b267983](https://linux-hardware.org/?probe=005b267983) | Nov 22, 2021 |
| ASUSTek       | GL702VMK                    | Notebook    | [ff58d2a76e](https://linux-hardware.org/?probe=ff58d2a76e) | Nov 21, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [81a7c19597](https://linux-hardware.org/?probe=81a7c19597) | Nov 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [f119e55cf9](https://linux-hardware.org/?probe=f119e55cf9) | Nov 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| Gigabyte      | P41T-D3P                    | Desktop     | [54a25af09a](https://linux-hardware.org/?probe=54a25af09a) | Nov 11, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [20aa404ab6](https://linux-hardware.org/?probe=20aa404ab6) | Nov 10, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [cfafa7735b](https://linux-hardware.org/?probe=cfafa7735b) | Nov 08, 2021 |
| Dell          | Latitude E7240              | Notebook    | [366228fab6](https://linux-hardware.org/?probe=366228fab6) | Nov 05, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [1e136c311c](https://linux-hardware.org/?probe=1e136c311c) | Nov 03, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [d098305f2a](https://linux-hardware.org/?probe=d098305f2a) | Oct 30, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [d99bdece1d](https://linux-hardware.org/?probe=d99bdece1d) | Oct 30, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8db63e7a74](https://linux-hardware.org/?probe=8db63e7a74) | Oct 28, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [75b53e8d45](https://linux-hardware.org/?probe=75b53e8d45) | Oct 27, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [19cdc9b391](https://linux-hardware.org/?probe=19cdc9b391) | Oct 26, 2021 |
| Sony          | VPCSA25GX                   | Notebook    | [be4db20b0e](https://linux-hardware.org/?probe=be4db20b0e) | Oct 25, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [6ab1ce41db](https://linux-hardware.org/?probe=6ab1ce41db) | Oct 25, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [6547cded19](https://linux-hardware.org/?probe=6547cded19) | Oct 22, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [30c1b322ad](https://linux-hardware.org/?probe=30c1b322ad) | Oct 22, 2021 |
| ASUSTek       | U56E                        | Notebook    | [a610876405](https://linux-hardware.org/?probe=a610876405) | Oct 20, 2021 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [4e6bceb431](https://linux-hardware.org/?probe=4e6bceb431) | Oct 18, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [783eeaaa01](https://linux-hardware.org/?probe=783eeaaa01) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [87c7c24dcc](https://linux-hardware.org/?probe=87c7c24dcc) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [0d9ad64b08](https://linux-hardware.org/?probe=0d9ad64b08) | Oct 15, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [cce3e9bd74](https://linux-hardware.org/?probe=cce3e9bd74) | Oct 12, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [398dedabb8](https://linux-hardware.org/?probe=398dedabb8) | Oct 07, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [24efeaacb7](https://linux-hardware.org/?probe=24efeaacb7) | Oct 07, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [23d2e1a73d](https://linux-hardware.org/?probe=23d2e1a73d) | Oct 06, 2021 |
| HP            | ProBook 440 G2              | Notebook    | [cc83275513](https://linux-hardware.org/?probe=cc83275513) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [325655d6c5](https://linux-hardware.org/?probe=325655d6c5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [6cfb3f0c44](https://linux-hardware.org/?probe=6cfb3f0c44) | Sep 28, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [b633c9e1d1](https://linux-hardware.org/?probe=b633c9e1d1) | Sep 28, 2021 |
| ASUSTek       | T103HAF                     | Tablet      | [b2d1b00b0a](https://linux-hardware.org/?probe=b2d1b00b0a) | Sep 28, 2021 |
| ASRock        | B85M                        | Desktop     | [566089bd43](https://linux-hardware.org/?probe=566089bd43) | Sep 27, 2021 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [eec5db351d](https://linux-hardware.org/?probe=eec5db351d) | Sep 27, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0e614dfffe](https://linux-hardware.org/?probe=0e614dfffe) | Sep 27, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [3c4378f506](https://linux-hardware.org/?probe=3c4378f506) | Sep 25, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [9b27471e86](https://linux-hardware.org/?probe=9b27471e86) | Sep 23, 2021 |
| HP            | EliteBook 745 G2            | Notebook    | [2b74c7b1ff](https://linux-hardware.org/?probe=2b74c7b1ff) | Sep 18, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [2b132c74b6](https://linux-hardware.org/?probe=2b132c74b6) | Sep 16, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [ca2bc77aa5](https://linux-hardware.org/?probe=ca2bc77aa5) | Sep 16, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [31ca803af1](https://linux-hardware.org/?probe=31ca803af1) | Sep 13, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [675a3f37b7](https://linux-hardware.org/?probe=675a3f37b7) | Sep 12, 2021 |
| LG Electro... | RD590-K.ADJCRE6             | Notebook    | [00da9ca38f](https://linux-hardware.org/?probe=00da9ca38f) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [ec0cd5d69b](https://linux-hardware.org/?probe=ec0cd5d69b) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [7797008e19](https://linux-hardware.org/?probe=7797008e19) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [07d1890920](https://linux-hardware.org/?probe=07d1890920) | Sep 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [a6221df8f8](https://linux-hardware.org/?probe=a6221df8f8) | Sep 10, 2021 |
| ASUSTek       | X540UV                      | Notebook    | [b0a231831a](https://linux-hardware.org/?probe=b0a231831a) | Sep 09, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [d47d63a84f](https://linux-hardware.org/?probe=d47d63a84f) | Sep 07, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [453f65a5e7](https://linux-hardware.org/?probe=453f65a5e7) | Sep 07, 2021 |
| Acer          | Aspire A715-71G             | Notebook    | [b915ae27b7](https://linux-hardware.org/?probe=b915ae27b7) | Sep 06, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [62fc103f71](https://linux-hardware.org/?probe=62fc103f71) | Sep 06, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [016672b182](https://linux-hardware.org/?probe=016672b182) | Sep 03, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [b011298d66](https://linux-hardware.org/?probe=b011298d66) | Sep 01, 2021 |
| MSI           | Prestige 14 A10RB           | Notebook    | [2aaa6d05d2](https://linux-hardware.org/?probe=2aaa6d05d2) | Sep 01, 2021 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [2044660bb8](https://linux-hardware.org/?probe=2044660bb8) | Aug 30, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [eec643e4e2](https://linux-hardware.org/?probe=eec643e4e2) | Aug 29, 2021 |
| YANYU         | M9F baytrail                | Desktop     | [0e5100e716](https://linux-hardware.org/?probe=0e5100e716) | Aug 29, 2021 |
| YANYU         | M9F baytrail                | Desktop     | [0bf997753c](https://linux-hardware.org/?probe=0bf997753c) | Aug 29, 2021 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [9f01a4629a](https://linux-hardware.org/?probe=9f01a4629a) | Aug 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [de74046226](https://linux-hardware.org/?probe=de74046226) | Aug 23, 2021 |
| ASUSTek       | X550EA                      | Notebook    | [19a7dfc92a](https://linux-hardware.org/?probe=19a7dfc92a) | Aug 22, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [bfe60273f6](https://linux-hardware.org/?probe=bfe60273f6) | Aug 09, 2021 |
| HP            | ZBook 15                    | Notebook    | [1a67896055](https://linux-hardware.org/?probe=1a67896055) | Aug 09, 2021 |
| Sony          | VPCEH36EG                   | Notebook    | [ec709da453](https://linux-hardware.org/?probe=ec709da453) | Aug 09, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [31891cbc13](https://linux-hardware.org/?probe=31891cbc13) | Aug 08, 2021 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [fe27de6bbc](https://linux-hardware.org/?probe=fe27de6bbc) | Aug 07, 2021 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [407501f166](https://linux-hardware.org/?probe=407501f166) | Aug 05, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [1e165352ad](https://linux-hardware.org/?probe=1e165352ad) | Aug 04, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [a5c472e082](https://linux-hardware.org/?probe=a5c472e082) | Aug 01, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [538eb1efa0](https://linux-hardware.org/?probe=538eb1efa0) | Aug 01, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [13e3cf7a5f](https://linux-hardware.org/?probe=13e3cf7a5f) | Jul 29, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [063facd29a](https://linux-hardware.org/?probe=063facd29a) | Jul 28, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [4b49f7026f](https://linux-hardware.org/?probe=4b49f7026f) | Jul 27, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [2bd8f0dd2e](https://linux-hardware.org/?probe=2bd8f0dd2e) | Jul 27, 2021 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [afb9cb6674](https://linux-hardware.org/?probe=afb9cb6674) | Jul 27, 2021 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [5d118fd4cc](https://linux-hardware.org/?probe=5d118fd4cc) | Jul 26, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [3f20462c62](https://linux-hardware.org/?probe=3f20462c62) | Jul 25, 2021 |
| HP            | ProBook 4540s               | Notebook    | [719b37c9ac](https://linux-hardware.org/?probe=719b37c9ac) | Jul 20, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [0ae43f5015](https://linux-hardware.org/?probe=0ae43f5015) | Jul 20, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [b26638f586](https://linux-hardware.org/?probe=b26638f586) | Jul 17, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [8a28a4f7f5](https://linux-hardware.org/?probe=8a28a4f7f5) | Jul 17, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [08f5207ee6](https://linux-hardware.org/?probe=08f5207ee6) | Jul 17, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [b3bb7e1295](https://linux-hardware.org/?probe=b3bb7e1295) | Jul 17, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [01b8cc373f](https://linux-hardware.org/?probe=01b8cc373f) | Jul 13, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [09ec64fc0d](https://linux-hardware.org/?probe=09ec64fc0d) | Jul 10, 2021 |
| HP            | Notebook                    | Notebook    | [3fc4cb2f55](https://linux-hardware.org/?probe=3fc4cb2f55) | Jul 09, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [90a20b185b](https://linux-hardware.org/?probe=90a20b185b) | Jul 03, 2021 |
| Gigabyte      | 8IPE1000-G/L                | Desktop     | [0301b9707b](https://linux-hardware.org/?probe=0301b9707b) | Jun 29, 2021 |
| Lenovo        | ThinkPad E560 20EV0005AD    | Notebook    | [fab11e73ee](https://linux-hardware.org/?probe=fab11e73ee) | Jun 29, 2021 |
| Acer          | Aspire 4736Z                | Notebook    | [6a5d92699d](https://linux-hardware.org/?probe=6a5d92699d) | Jun 23, 2021 |
| Dell          | Latitude D420               | Notebook    | [5f0d609bef](https://linux-hardware.org/?probe=5f0d609bef) | Jun 21, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [7026c20c97](https://linux-hardware.org/?probe=7026c20c97) | Jun 20, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [f34a1bbe5a](https://linux-hardware.org/?probe=f34a1bbe5a) | Jun 20, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [1343b5bb5d](https://linux-hardware.org/?probe=1343b5bb5d) | Jun 20, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [5963dd2256](https://linux-hardware.org/?probe=5963dd2256) | Jun 18, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [4af988fc2f](https://linux-hardware.org/?probe=4af988fc2f) | Jun 17, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [1fd8a9e8c8](https://linux-hardware.org/?probe=1fd8a9e8c8) | Jun 16, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| ASUSTek       | Z11PG-D24 Series            | Server      | [e4be3f2344](https://linux-hardware.org/?probe=e4be3f2344) | Jun 12, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [28e717743a](https://linux-hardware.org/?probe=28e717743a) | Jun 06, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [35b68a0b4a](https://linux-hardware.org/?probe=35b68a0b4a) | Jun 06, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [4b5debd7a6](https://linux-hardware.org/?probe=4b5debd7a6) | Jun 04, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [4333473e1e](https://linux-hardware.org/?probe=4333473e1e) | Jun 03, 2021 |
| HP            | ProBook 4520s               | Notebook    | [b0a9a196db](https://linux-hardware.org/?probe=b0a9a196db) | Jun 03, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [b3206cba40](https://linux-hardware.org/?probe=b3206cba40) | Jun 03, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [043730ad50](https://linux-hardware.org/?probe=043730ad50) | Jun 01, 2021 |
| ASRock        | N68-GS4 FX                  | Desktop     | [1023832c74](https://linux-hardware.org/?probe=1023832c74) | Jun 01, 2021 |
| ASRock        | N68-GS4 FX                  | Desktop     | [2ff6c9500b](https://linux-hardware.org/?probe=2ff6c9500b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [07aa0b9e2b](https://linux-hardware.org/?probe=07aa0b9e2b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [6b0fca64c4](https://linux-hardware.org/?probe=6b0fca64c4) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [4c650b1991](https://linux-hardware.org/?probe=4c650b1991) | Jun 01, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [74d1da4b68](https://linux-hardware.org/?probe=74d1da4b68) | May 28, 2021 |
| ASUSTek       | X550MJ                      | Notebook    | [208fc3f30f](https://linux-hardware.org/?probe=208fc3f30f) | May 25, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [28d19f1a59](https://linux-hardware.org/?probe=28d19f1a59) | May 25, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [512cc44d82](https://linux-hardware.org/?probe=512cc44d82) | May 21, 2021 |
| ASUSTek       | K53SM                       | Notebook    | [f0199bc53d](https://linux-hardware.org/?probe=f0199bc53d) | May 20, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [bca3c06314](https://linux-hardware.org/?probe=bca3c06314) | May 20, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [f232d2395d](https://linux-hardware.org/?probe=f232d2395d) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1779bd65f6](https://linux-hardware.org/?probe=1779bd65f6) | May 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8771b02dfe](https://linux-hardware.org/?probe=8771b02dfe) | May 17, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [1417eccc8b](https://linux-hardware.org/?probe=1417eccc8b) | May 15, 2021 |
| HP            | EliteBook 725 G2            | Notebook    | [5dddeca3e8](https://linux-hardware.org/?probe=5dddeca3e8) | May 09, 2021 |
| MSI           | PH67A-C43                   | Desktop     | [8e818ce79a](https://linux-hardware.org/?probe=8e818ce79a) | May 05, 2021 |
| Acer          | Aspire V3-574G              | Notebook    | [507422ce0b](https://linux-hardware.org/?probe=507422ce0b) | May 05, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [2d12301b1c](https://linux-hardware.org/?probe=2d12301b1c) | May 05, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [57540cdfa4](https://linux-hardware.org/?probe=57540cdfa4) | May 03, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8f0e9df209](https://linux-hardware.org/?probe=8f0e9df209) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [940758b420](https://linux-hardware.org/?probe=940758b420) | Apr 27, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [ced3a1165d](https://linux-hardware.org/?probe=ced3a1165d) | Apr 24, 2021 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [eeb73d1c4a](https://linux-hardware.org/?probe=eeb73d1c4a) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [93671f3ecc](https://linux-hardware.org/?probe=93671f3ecc) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [9fbf2707b0](https://linux-hardware.org/?probe=9fbf2707b0) | Apr 19, 2021 |
| ASUSTek       | X555LF                      | Notebook    | [eb9637ae4a](https://linux-hardware.org/?probe=eb9637ae4a) | Apr 19, 2021 |
| Lenovo        | ThinkPad E590 20NB0057AD    | Notebook    | [d06cfc6dee](https://linux-hardware.org/?probe=d06cfc6dee) | Apr 18, 2021 |
| Acer          | AOD260                      | Notebook    | [97f6b98307](https://linux-hardware.org/?probe=97f6b98307) | Apr 16, 2021 |
| Lenovo        | ThinkPad T470p 20J6S08M0... | Notebook    | [84619b1b45](https://linux-hardware.org/?probe=84619b1b45) | Apr 15, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [1dcb2a173e](https://linux-hardware.org/?probe=1dcb2a173e) | Apr 14, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [28d13bbb26](https://linux-hardware.org/?probe=28d13bbb26) | Apr 14, 2021 |
| Gigabyte      | M52S-S3P                    | Desktop     | [494ac8b449](https://linux-hardware.org/?probe=494ac8b449) | Apr 11, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [29e4ff83db](https://linux-hardware.org/?probe=29e4ff83db) | Apr 10, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [7713767fa6](https://linux-hardware.org/?probe=7713767fa6) | Apr 10, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [9c00d55213](https://linux-hardware.org/?probe=9c00d55213) | Apr 10, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9a9c3c8d26](https://linux-hardware.org/?probe=9a9c3c8d26) | Apr 09, 2021 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [6e1542aab7](https://linux-hardware.org/?probe=6e1542aab7) | Apr 09, 2021 |
| ASUSTek       | X542UQ                      | Notebook    | [5b0c97ade1](https://linux-hardware.org/?probe=5b0c97ade1) | Apr 09, 2021 |
| MSI           | CR610M                      | Notebook    | [e2e00880a3](https://linux-hardware.org/?probe=e2e00880a3) | Apr 08, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [60168d5b6d](https://linux-hardware.org/?probe=60168d5b6d) | Apr 07, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire 4741                 | Notebook    | [ddda7566c5](https://linux-hardware.org/?probe=ddda7566c5) | Apr 03, 2021 |
| Acer          | Aspire 4741                 | Notebook    | [5fb915669a](https://linux-hardware.org/?probe=5fb915669a) | Apr 03, 2021 |
| ASUSTek       | H61M-C                      | Desktop     | [c39fc169bf](https://linux-hardware.org/?probe=c39fc169bf) | Apr 02, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [c5e7e65164](https://linux-hardware.org/?probe=c5e7e65164) | Apr 01, 2021 |
| HP            | EliteBook 745 G4            | Notebook    | [a5888bbded](https://linux-hardware.org/?probe=a5888bbded) | Apr 01, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [9a4a054203](https://linux-hardware.org/?probe=9a4a054203) | Apr 01, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [9c2661508e](https://linux-hardware.org/?probe=9c2661508e) | Mar 30, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [bacb9e5030](https://linux-hardware.org/?probe=bacb9e5030) | Mar 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [344eec241a](https://linux-hardware.org/?probe=344eec241a) | Mar 21, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | Notebook    | [ca815648fc](https://linux-hardware.org/?probe=ca815648fc) | Mar 17, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [d5d788f2f3](https://linux-hardware.org/?probe=d5d788f2f3) | Mar 15, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [89b0451670](https://linux-hardware.org/?probe=89b0451670) | Mar 14, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [ed8b926f53](https://linux-hardware.org/?probe=ed8b926f53) | Mar 14, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | Notebook    | [75ba14ee94](https://linux-hardware.org/?probe=75ba14ee94) | Mar 14, 2021 |
| HP            | 3397                        | Desktop     | [13a7f8c4c2](https://linux-hardware.org/?probe=13a7f8c4c2) | Mar 08, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [be98339598](https://linux-hardware.org/?probe=be98339598) | Mar 07, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [eb31b2ffb6](https://linux-hardware.org/?probe=eb31b2ffb6) | Mar 07, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [fd19b6b1c8](https://linux-hardware.org/?probe=fd19b6b1c8) | Mar 07, 2021 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [502ef11b75](https://linux-hardware.org/?probe=502ef11b75) | Mar 07, 2021 |
| Gigabyte      | GA-M55SLI-S4                | Desktop     | [43d0cb9ac1](https://linux-hardware.org/?probe=43d0cb9ac1) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [b7e39a92a0](https://linux-hardware.org/?probe=b7e39a92a0) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [7ca6ad9361](https://linux-hardware.org/?probe=7ca6ad9361) | Mar 06, 2021 |
| ASUSTek       | P5E                         | Desktop     | [5681b93aaf](https://linux-hardware.org/?probe=5681b93aaf) | Mar 06, 2021 |
| ASUSTek       | P5E                         | Desktop     | [9f858aaf27](https://linux-hardware.org/?probe=9f858aaf27) | Mar 05, 2021 |
| ASUSTek       | K42JK                       | Notebook    | [bae11d222f](https://linux-hardware.org/?probe=bae11d222f) | Mar 04, 2021 |
| ASUSTek       | K42JK                       | Notebook    | [3ae670828a](https://linux-hardware.org/?probe=3ae670828a) | Mar 03, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [fd21e67a3c](https://linux-hardware.org/?probe=fd21e67a3c) | Feb 28, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [429c09a059](https://linux-hardware.org/?probe=429c09a059) | Feb 28, 2021 |
| HP            | Pavilion g6                 | Notebook    | [2ce61d58bf](https://linux-hardware.org/?probe=2ce61d58bf) | Feb 26, 2021 |
| HP            | ProBook 4540s               | Notebook    | [dda65f86ac](https://linux-hardware.org/?probe=dda65f86ac) | Feb 24, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e3ff93ab0a](https://linux-hardware.org/?probe=e3ff93ab0a) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [ab787a4172](https://linux-hardware.org/?probe=ab787a4172) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [7ba0b6a17d](https://linux-hardware.org/?probe=7ba0b6a17d) | Feb 21, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [b1b8587cdb](https://linux-hardware.org/?probe=b1b8587cdb) | Feb 19, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [d45ed4ad08](https://linux-hardware.org/?probe=d45ed4ad08) | Feb 19, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [b6a8851986](https://linux-hardware.org/?probe=b6a8851986) | Feb 19, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [520780b02d](https://linux-hardware.org/?probe=520780b02d) | Feb 18, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [62c9e819cd](https://linux-hardware.org/?probe=62c9e819cd) | Feb 17, 2021 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [8070e672a7](https://linux-hardware.org/?probe=8070e672a7) | Feb 15, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [ee986e1fdd](https://linux-hardware.org/?probe=ee986e1fdd) | Feb 11, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b661aa21f1](https://linux-hardware.org/?probe=b661aa21f1) | Feb 09, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [0c9067579c](https://linux-hardware.org/?probe=0c9067579c) | Feb 09, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [ab4bc22a87](https://linux-hardware.org/?probe=ab4bc22a87) | Feb 06, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [5e9aa1c3de](https://linux-hardware.org/?probe=5e9aa1c3de) | Feb 06, 2021 |
| ASUSTek       | X456URK                     | Notebook    | [6c3b5bdfb1](https://linux-hardware.org/?probe=6c3b5bdfb1) | Feb 05, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [9de86c8038](https://linux-hardware.org/?probe=9de86c8038) | Feb 05, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [d383b4a5e7](https://linux-hardware.org/?probe=d383b4a5e7) | Feb 05, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [2bd7b5699d](https://linux-hardware.org/?probe=2bd7b5699d) | Feb 05, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [f1f4fbad09](https://linux-hardware.org/?probe=f1f4fbad09) | Feb 03, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [0df26493a8](https://linux-hardware.org/?probe=0df26493a8) | Feb 03, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [82920966cf](https://linux-hardware.org/?probe=82920966cf) | Feb 01, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [d82031935e](https://linux-hardware.org/?probe=d82031935e) | Feb 01, 2021 |
| ASUSTek       | N56JR                       | Notebook    | [29ad612f88](https://linux-hardware.org/?probe=29ad612f88) | Jan 28, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [2960ce1b31](https://linux-hardware.org/?probe=2960ce1b31) | Jan 27, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [b97b822412](https://linux-hardware.org/?probe=b97b822412) | Jan 27, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [a0eb5fc713](https://linux-hardware.org/?probe=a0eb5fc713) | Jan 20, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [2fa2f12de6](https://linux-hardware.org/?probe=2fa2f12de6) | Jan 19, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [537d05799c](https://linux-hardware.org/?probe=537d05799c) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [66598d3f69](https://linux-hardware.org/?probe=66598d3f69) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [113406e67d](https://linux-hardware.org/?probe=113406e67d) | Jan 15, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [703dd398d1](https://linux-hardware.org/?probe=703dd398d1) | Jan 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [85c5454ed1](https://linux-hardware.org/?probe=85c5454ed1) | Jan 14, 2021 |
| ASUSTek       | X542UN                      | Notebook    | [44633c4ff2](https://linux-hardware.org/?probe=44633c4ff2) | Jan 13, 2021 |
| ASUSTek       | H61M-A/USB3                 | Desktop     | [d8aafdef30](https://linux-hardware.org/?probe=d8aafdef30) | Jan 10, 2021 |
| Sony          | SVF15N12SGB                 | Notebook    | [3ff592b868](https://linux-hardware.org/?probe=3ff592b868) | Jan 07, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 34483... | Notebook    | [4e6cc9fdc4](https://linux-hardware.org/?probe=4e6cc9fdc4) | Jan 03, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [96280026fb](https://linux-hardware.org/?probe=96280026fb) | Jan 03, 2021 |
| Dell          | Vostro 1015                 | Notebook    | [7243a2df4f](https://linux-hardware.org/?probe=7243a2df4f) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [4d96f1db71](https://linux-hardware.org/?probe=4d96f1db71) | Dec 31, 2020 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [be00a7c4e5](https://linux-hardware.org/?probe=be00a7c4e5) | Dec 28, 2020 |
| Acer          | Aspire 5755G                | Notebook    | [5577ccef28](https://linux-hardware.org/?probe=5577ccef28) | Dec 28, 2020 |
| HP            | ProBook 4540s               | Notebook    | [86bd405fac](https://linux-hardware.org/?probe=86bd405fac) | Dec 27, 2020 |
| HP            | ProBook 4540s               | Notebook    | [7a93e1b05a](https://linux-hardware.org/?probe=7a93e1b05a) | Dec 27, 2020 |
| Dell          | Vostro 1015                 | Notebook    | [9be1d69693](https://linux-hardware.org/?probe=9be1d69693) | Dec 26, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [9582155494](https://linux-hardware.org/?probe=9582155494) | Dec 25, 2020 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [f7f32358db](https://linux-hardware.org/?probe=f7f32358db) | Dec 24, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ec5fac5f1d](https://linux-hardware.org/?probe=ec5fac5f1d) | Dec 24, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [3071d9e517](https://linux-hardware.org/?probe=3071d9e517) | Dec 23, 2020 |
| MSI           | GE60 2PC                    | Notebook    | [46af0a2d84](https://linux-hardware.org/?probe=46af0a2d84) | Dec 22, 2020 |
| MSI           | GE60 2PC                    | Notebook    | [c659f6a910](https://linux-hardware.org/?probe=c659f6a910) | Dec 21, 2020 |
| HP            | 3397                        | Desktop     | [1b81310dbf](https://linux-hardware.org/?probe=1b81310dbf) | Dec 20, 2020 |
| HP            | 3397                        | Desktop     | [086227e446](https://linux-hardware.org/?probe=086227e446) | Dec 20, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T10... | Notebook    | [d5a85767cd](https://linux-hardware.org/?probe=d5a85767cd) | Dec 18, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [a6bf272580](https://linux-hardware.org/?probe=a6bf272580) | Dec 18, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [fe5ef27982](https://linux-hardware.org/?probe=fe5ef27982) | Dec 17, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [ccdd9fbe6b](https://linux-hardware.org/?probe=ccdd9fbe6b) | Dec 16, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [e7e6ad670b](https://linux-hardware.org/?probe=e7e6ad670b) | Dec 16, 2020 |
| Acer          | Aspire A715-74G             | Notebook    | [03f5d24d56](https://linux-hardware.org/?probe=03f5d24d56) | Dec 16, 2020 |
| Acer          | Aspire A715-74G             | Notebook    | [886054e929](https://linux-hardware.org/?probe=886054e929) | Dec 15, 2020 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [e39c3e59b5](https://linux-hardware.org/?probe=e39c3e59b5) | Dec 13, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [67aa2554c3](https://linux-hardware.org/?probe=67aa2554c3) | Dec 10, 2020 |
| MSI           | CX62 6QL                    | Notebook    | [90a60a1e78](https://linux-hardware.org/?probe=90a60a1e78) | Dec 06, 2020 |
| MSI           | CX62 6QL                    | Notebook    | [9b4aaf5856](https://linux-hardware.org/?probe=9b4aaf5856) | Dec 06, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [d93fb9ef4a](https://linux-hardware.org/?probe=d93fb9ef4a) | Dec 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [47835d66f6](https://linux-hardware.org/?probe=47835d66f6) | Dec 01, 2020 |
| Gigabyte      | P55A-UD3P                   | Desktop     | [9f5052c50b](https://linux-hardware.org/?probe=9f5052c50b) | Nov 30, 2020 |
| Gigabyte      | P55A-UD3P                   | Desktop     | [03db05b217](https://linux-hardware.org/?probe=03db05b217) | Nov 30, 2020 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [c9c25216a4](https://linux-hardware.org/?probe=c9c25216a4) | Nov 25, 2020 |
| Sony          | VPCEH11FX                   | Notebook    | [d3ff8db043](https://linux-hardware.org/?probe=d3ff8db043) | Nov 22, 2020 |
| HP            | 2AF3                        | Desktop     | [3c07a68022](https://linux-hardware.org/?probe=3c07a68022) | Nov 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8e0bc13a31](https://linux-hardware.org/?probe=8e0bc13a31) | Nov 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [c099ac62d5](https://linux-hardware.org/?probe=c099ac62d5) | Nov 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [7787345258](https://linux-hardware.org/?probe=7787345258) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Acer          | TravelMate 5742Z            | Notebook    | [be124397e2](https://linux-hardware.org/?probe=be124397e2) | Nov 13, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3bc3e0823a](https://linux-hardware.org/?probe=3bc3e0823a) | Nov 09, 2020 |
| HP            | ProBook 4540s               | Notebook    | [4864704e84](https://linux-hardware.org/?probe=4864704e84) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [adbb505553](https://linux-hardware.org/?probe=adbb505553) | Nov 08, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [543559dfac](https://linux-hardware.org/?probe=543559dfac) | Nov 07, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [c7b7b29a68](https://linux-hardware.org/?probe=c7b7b29a68) | Nov 07, 2020 |
| Lenovo        | E5                          | Notebook    | [3b7111b4a2](https://linux-hardware.org/?probe=3b7111b4a2) | Nov 07, 2020 |
| Lenovo        | E5                          | Notebook    | [cb3bf5a3df](https://linux-hardware.org/?probe=cb3bf5a3df) | Nov 07, 2020 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [6a88e646aa](https://linux-hardware.org/?probe=6a88e646aa) | Nov 07, 2020 |
| ASUSTek       | X550VXK                     | Notebook    | [5f95436c09](https://linux-hardware.org/?probe=5f95436c09) | Nov 06, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [42ef7e253c](https://linux-hardware.org/?probe=42ef7e253c) | Nov 01, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [cba527dd9f](https://linux-hardware.org/?probe=cba527dd9f) | Nov 01, 2020 |
| Acer          | Aspire 5741G                | Notebook    | [75bacf18a7](https://linux-hardware.org/?probe=75bacf18a7) | Oct 31, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [f6c5e1d108](https://linux-hardware.org/?probe=f6c5e1d108) | Oct 28, 2020 |
| Foxconn       | A8G-i                       | Desktop     | [b4675cde03](https://linux-hardware.org/?probe=b4675cde03) | Oct 27, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [c3cd0fcf33](https://linux-hardware.org/?probe=c3cd0fcf33) | Oct 24, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [11db584122](https://linux-hardware.org/?probe=11db584122) | Oct 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [7525ff1dde](https://linux-hardware.org/?probe=7525ff1dde) | Oct 23, 2020 |
| ASUSTek       | N552VW                      | Notebook    | [6893d4927d](https://linux-hardware.org/?probe=6893d4927d) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6A... | Notebook    | [9565cc6937](https://linux-hardware.org/?probe=9565cc6937) | Oct 20, 2020 |
| Lenovo        | B50-80 80EW                 | Notebook    | [c6bf9e5376](https://linux-hardware.org/?probe=c6bf9e5376) | Oct 17, 2020 |
| ASUSTek       | X505BA                      | Notebook    | [6f5c254a9f](https://linux-hardware.org/?probe=6f5c254a9f) | Oct 15, 2020 |
| Intel         | P61-S3                      | Desktop     | [efee9af681](https://linux-hardware.org/?probe=efee9af681) | Oct 13, 2020 |
| Intel         | P61-S3                      | Desktop     | [36f0f58223](https://linux-hardware.org/?probe=36f0f58223) | Oct 12, 2020 |
| Gigabyte      | 8S648FX-RZ                  | Desktop     | [c00289e6ed](https://linux-hardware.org/?probe=c00289e6ed) | Oct 11, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [2763c330eb](https://linux-hardware.org/?probe=2763c330eb) | Oct 09, 2020 |
| ASRock        | P5B-DE                      | Desktop     | [ef1c17dd39](https://linux-hardware.org/?probe=ef1c17dd39) | Oct 08, 2020 |
| ASUSTek       | UX430UA                     | Notebook    | [d6586b9bb8](https://linux-hardware.org/?probe=d6586b9bb8) | Oct 05, 2020 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [bbf7ae1125](https://linux-hardware.org/?probe=bbf7ae1125) | Oct 05, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [ceeced1246](https://linux-hardware.org/?probe=ceeced1246) | Oct 02, 2020 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [5996a3b895](https://linux-hardware.org/?probe=5996a3b895) | Sep 29, 2020 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [60156a645b](https://linux-hardware.org/?probe=60156a645b) | Sep 29, 2020 |
| Sony          | VPCEB1SFX                   | Notebook    | [01b67b1979](https://linux-hardware.org/?probe=01b67b1979) | Sep 27, 2020 |
| Sony          | VPCEB1SFX                   | Notebook    | [616d06a0b0](https://linux-hardware.org/?probe=616d06a0b0) | Sep 26, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [6f184c4bc8](https://linux-hardware.org/?probe=6f184c4bc8) | Sep 26, 2020 |
| ASUSTek       | K42Jc                       | Notebook    | [9808a6bb0c](https://linux-hardware.org/?probe=9808a6bb0c) | Sep 25, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [5ea9c0eca9](https://linux-hardware.org/?probe=5ea9c0eca9) | Sep 24, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [59f1e93325](https://linux-hardware.org/?probe=59f1e93325) | Sep 18, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [a91b502a98](https://linux-hardware.org/?probe=a91b502a98) | Sep 18, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [9456172087](https://linux-hardware.org/?probe=9456172087) | Sep 18, 2020 |
| Gigabyte      | B75M-D3V                    | Desktop     | [32e15ba2b5](https://linux-hardware.org/?probe=32e15ba2b5) | Sep 18, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [36d0455f5f](https://linux-hardware.org/?probe=36d0455f5f) | Sep 15, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7ad450ddd7](https://linux-hardware.org/?probe=7ad450ddd7) | Sep 14, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [5ed2d21f85](https://linux-hardware.org/?probe=5ed2d21f85) | Sep 05, 2020 |
| ASUSTek       | K52F                        | Notebook    | [1658b8903d](https://linux-hardware.org/?probe=1658b8903d) | Sep 04, 2020 |
| ASUSTek       | K52F                        | Notebook    | [b7a5d27a01](https://linux-hardware.org/?probe=b7a5d27a01) | Sep 04, 2020 |
| ASUSTek       | K42Jc                       | Notebook    | [79d7ee2e74](https://linux-hardware.org/?probe=79d7ee2e74) | Sep 04, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [61bc69e87c](https://linux-hardware.org/?probe=61bc69e87c) | Sep 04, 2020 |
| Dell          | Latitude E6530              | Notebook    | [c026f89bd8](https://linux-hardware.org/?probe=c026f89bd8) | Aug 31, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0ab2905b28](https://linux-hardware.org/?probe=0ab2905b28) | Aug 29, 2020 |
| MSI           | Prestige 14 A10RB           | Notebook    | [b7fff5e5cc](https://linux-hardware.org/?probe=b7fff5e5cc) | Aug 28, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [c172701a56](https://linux-hardware.org/?probe=c172701a56) | Aug 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [af595ebfde](https://linux-hardware.org/?probe=af595ebfde) | Aug 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [c03d58914c](https://linux-hardware.org/?probe=c03d58914c) | Aug 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [55c0c83149](https://linux-hardware.org/?probe=55c0c83149) | Aug 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [e97f7b8582](https://linux-hardware.org/?probe=e97f7b8582) | Aug 02, 2020 |
| MSI           | GF63 Thin 9RC               | Notebook    | [f7eff6d78e](https://linux-hardware.org/?probe=f7eff6d78e) | Jul 28, 2020 |
| MSI           | GF63 Thin 9RC               | Notebook    | [7b12eabb3e](https://linux-hardware.org/?probe=7b12eabb3e) | Jul 28, 2020 |
| HP            | 3397                        | Desktop     | [e4e6951a4f](https://linux-hardware.org/?probe=e4e6951a4f) | Jul 25, 2020 |
| ASUSTek       | M4A78T-E                    | Desktop     | [2c268bdb51](https://linux-hardware.org/?probe=2c268bdb51) | Jul 24, 2020 |
| Lenovo        | ThinkCentre M58 8910ASU     | Desktop     | [d29d396ad0](https://linux-hardware.org/?probe=d29d396ad0) | Jul 23, 2020 |
| Lenovo        | ThinkPad E490 20N8000JUE    | Notebook    | [66d2ca1186](https://linux-hardware.org/?probe=66d2ca1186) | Jul 22, 2020 |
| ASUSTek       | N53Jq                       | Notebook    | [4d04d4ee3a](https://linux-hardware.org/?probe=4d04d4ee3a) | Jul 19, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [d7789565b7](https://linux-hardware.org/?probe=d7789565b7) | Jul 18, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [43c91be0b3](https://linux-hardware.org/?probe=43c91be0b3) | Jul 16, 2020 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [eb9ea3a7af](https://linux-hardware.org/?probe=eb9ea3a7af) | Jul 12, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [e9a3474bde](https://linux-hardware.org/?probe=e9a3474bde) | Jul 09, 2020 |
| HP            | 212B                        | Desktop     | [4a3583e0db](https://linux-hardware.org/?probe=4a3583e0db) | Jul 06, 2020 |
| Acer          | TravelMate 5742Z            | Notebook    | [de25d26410](https://linux-hardware.org/?probe=de25d26410) | Jul 05, 2020 |
| ECS           | G31T-M                      | Desktop     | [614dcd20e7](https://linux-hardware.org/?probe=614dcd20e7) | Jul 05, 2020 |
| Acer          | Aspire V5-561G              | Notebook    | [81b19839f7](https://linux-hardware.org/?probe=81b19839f7) | Jul 02, 2020 |
| ASUSTek       | Z170-K                      | Desktop     | [a35de97ee5](https://linux-hardware.org/?probe=a35de97ee5) | Jun 27, 2020 |
| ASUSTek       | H110M-C                     | Desktop     | [5656016c57](https://linux-hardware.org/?probe=5656016c57) | Jun 27, 2020 |
| ASRock        | P5B-DE                      | Desktop     | [304331fe41](https://linux-hardware.org/?probe=304331fe41) | Jun 24, 2020 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [d0f33583b0](https://linux-hardware.org/?probe=d0f33583b0) | Jun 21, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [7554759bac](https://linux-hardware.org/?probe=7554759bac) | Jun 18, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [3f30010f53](https://linux-hardware.org/?probe=3f30010f53) | Jun 14, 2020 |
| ASUSTek       | X580VD                      | Notebook    | [1ad8491ca0](https://linux-hardware.org/?probe=1ad8491ca0) | Jun 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [376ebf1819](https://linux-hardware.org/?probe=376ebf1819) | Jun 14, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [56a1c895ee](https://linux-hardware.org/?probe=56a1c895ee) | Jun 07, 2020 |
| Acer          | Aspire V5-572G              | Notebook    | [4a67c5fabb](https://linux-hardware.org/?probe=4a67c5fabb) | Jun 03, 2020 |
| ASUSTek       | X510UQR                     | Notebook    | [8fd66dd600](https://linux-hardware.org/?probe=8fd66dd600) | Jun 01, 2020 |
| ASUSTek       | X510UQR                     | Notebook    | [fbd9ae49c7](https://linux-hardware.org/?probe=fbd9ae49c7) | Jun 01, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [d059aa2096](https://linux-hardware.org/?probe=d059aa2096) | May 29, 2020 |
| Sony          | VGN-SR165E                  | Notebook    | [ee7e382325](https://linux-hardware.org/?probe=ee7e382325) | May 27, 2020 |
| Microsoft     | Surface Book 2              | Tablet      | [0ff458cc64](https://linux-hardware.org/?probe=0ff458cc64) | May 23, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [639a8b36be](https://linux-hardware.org/?probe=639a8b36be) | May 23, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [870f5869a0](https://linux-hardware.org/?probe=870f5869a0) | May 22, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [842fbba95c](https://linux-hardware.org/?probe=842fbba95c) | May 22, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [c9967bfff4](https://linux-hardware.org/?probe=c9967bfff4) | May 22, 2020 |
| Fujitsu       | LIFEBOOK NH570              | Notebook    | [58dbbb5f10](https://linux-hardware.org/?probe=58dbbb5f10) | May 22, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [a82798aea1](https://linux-hardware.org/?probe=a82798aea1) | May 21, 2020 |
| HP            | 3397                        | Desktop     | [6d3acf04fa](https://linux-hardware.org/?probe=6d3acf04fa) | May 18, 2020 |
| Acer          | Aspire V5-572G              | Notebook    | [d919340bf8](https://linux-hardware.org/?probe=d919340bf8) | May 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [91908a3d7e](https://linux-hardware.org/?probe=91908a3d7e) | May 15, 2020 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [d064b573d0](https://linux-hardware.org/?probe=d064b573d0) | May 14, 2020 |
| ECS           | G41T-M13                    | Desktop     | [7f8c6dbb44](https://linux-hardware.org/?probe=7f8c6dbb44) | May 14, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3448fe759e](https://linux-hardware.org/?probe=3448fe759e) | May 13, 2020 |
| ECS           | G41T-M13                    | Desktop     | [b2c5f54483](https://linux-hardware.org/?probe=b2c5f54483) | May 10, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [d27ef604e7](https://linux-hardware.org/?probe=d27ef604e7) | May 10, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [cc84ca4df1](https://linux-hardware.org/?probe=cc84ca4df1) | May 08, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [150b4cbfba](https://linux-hardware.org/?probe=150b4cbfba) | May 08, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [efe32a1257](https://linux-hardware.org/?probe=efe32a1257) | May 07, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [3cac051446](https://linux-hardware.org/?probe=3cac051446) | May 07, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [543fb035d1](https://linux-hardware.org/?probe=543fb035d1) | May 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [7d8b34f96f](https://linux-hardware.org/?probe=7d8b34f96f) | May 03, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [a214d8fa2f](https://linux-hardware.org/?probe=a214d8fa2f) | May 02, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [a6f251843f](https://linux-hardware.org/?probe=a6f251843f) | May 01, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96005fbb6f](https://linux-hardware.org/?probe=96005fbb6f) | Apr 28, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [3405972303](https://linux-hardware.org/?probe=3405972303) | Apr 27, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [2950c5ee7f](https://linux-hardware.org/?probe=2950c5ee7f) | Apr 27, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [f82980ac2c](https://linux-hardware.org/?probe=f82980ac2c) | Apr 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [86e4dd0977](https://linux-hardware.org/?probe=86e4dd0977) | Apr 26, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [abfe333fb8](https://linux-hardware.org/?probe=abfe333fb8) | Apr 25, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [9e8575f75a](https://linux-hardware.org/?probe=9e8575f75a) | Apr 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5ec8b8b3b7](https://linux-hardware.org/?probe=5ec8b8b3b7) | Apr 25, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [c194d8e6be](https://linux-hardware.org/?probe=c194d8e6be) | Apr 24, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [680bbeabad](https://linux-hardware.org/?probe=680bbeabad) | Apr 24, 2020 |
| HP            | Pavilion g6                 | Notebook    | [66ba3bc59b](https://linux-hardware.org/?probe=66ba3bc59b) | Apr 23, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [82f761db09](https://linux-hardware.org/?probe=82f761db09) | Apr 23, 2020 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [409a40b72d](https://linux-hardware.org/?probe=409a40b72d) | Apr 20, 2020 |
| Lenovo        | ThinkPad E480 20KN007XAD    | Notebook    | [8310d15c91](https://linux-hardware.org/?probe=8310d15c91) | Apr 18, 2020 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [74699b5097](https://linux-hardware.org/?probe=74699b5097) | Apr 16, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Iran/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 109       | 12.99%  |
| Ubuntu 18.04       | 84        | 10.01%  |
| Ubuntu 22.04       | 76        | 9.06%   |
| Arch Rolling       | 29        | 3.46%   |
| Ubuntu 24.04       | 19        | 2.26%   |
| Arch               | 19        | 2.26%   |
| ArcoLinux Rolling  | 18        | 2.15%   |
| Ubuntu 19.04       | 16        | 1.91%   |
| Fedora 33          | 14        | 1.67%   |
| Fedora 38          | 13        | 1.55%   |
| Ubuntu 23.10       | 12        | 1.43%   |
| Debian 11          | 11        | 1.31%   |
| Ubuntu 21.10       | 10        | 1.19%   |
| Ubuntu 20.10       | 10        | 1.19%   |
| Manjaro            | 10        | 1.19%   |
| KDE neon 20.04     | 10        | 1.19%   |
| Xubuntu 18.04      | 9         | 1.07%   |
| OpenMandriva 4.2   | 9         | 1.07%   |
| Fedora 40          | 9         | 1.07%   |
| Fedora 34          | 9         | 1.07%   |
| Debian 12          | 9         | 1.07%   |
| Ubuntu 19.10       | 8         | 0.95%   |
| OpenMandriva 24.07 | 8         | 0.95%   |
| OpenMandriva 23.08 | 8         | 0.95%   |
| Xubuntu 22.04      | 6         | 0.72%   |
| Xubuntu 20.04      | 6         | 0.72%   |
| Ubuntu 23.04       | 6         | 0.72%   |
| Ubuntu 21.04       | 6         | 0.72%   |
| OpenMandriva 4.3   | 6         | 0.72%   |
| Linux Mint 20.3    | 6         | 0.72%   |
| Fedora 37          | 6         | 0.72%   |
| Zorin 17           | 5         | 0.6%    |
| Ubuntu 22.10       | 5         | 0.6%    |
| OpenMandriva 5.0   | 5         | 0.6%    |
| Fedora 35          | 5         | 0.6%    |
| Debian             | 5         | 0.6%    |
| Zorin 16           | 4         | 0.48%   |
| Zorin 15           | 4         | 0.48%   |
| Ubuntu 18.10       | 4         | 0.48%   |
| Pop!_OS 22.04      | 4         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 363       | 44.7%   |
| Fedora        | 67        | 8.25%   |
| Arch          | 46        | 5.67%   |
| OpenMandriva  | 41        | 5.05%   |
| Manjaro       | 35        | 4.31%   |
| Linux Mint    | 33        | 4.06%   |
| Debian        | 28        | 3.45%   |
| Xubuntu       | 21        | 2.59%   |
| Kali          | 18        | 2.22%   |
| ArcoLinux     | 18        | 2.22%   |
| KDE neon      | 17        | 2.09%   |
| Endless       | 17        | 2.09%   |
| Kubuntu       | 16        | 1.97%   |
| Zorin         | 14        | 1.72%   |
| Pop!_OS       | 12        | 1.48%   |
| ROSA          | 6         | 0.74%   |
| Lubuntu       | 6         | 0.74%   |
| Ubuntu Unity  | 5         | 0.62%   |
| Ubuntu Budgie | 4         | 0.49%   |
| Parch         | 4         | 0.49%   |
| openSUSE      | 4         | 0.49%   |
| Elementary    | 4         | 0.49%   |
| Gentoo        | 3         | 0.37%   |
| CentOS        | 3         | 0.37%   |
| Xero          | 2         | 0.25%   |
| Solus         | 2         | 0.25%   |
| NixOS         | 2         | 0.25%   |
| Clear Linux   | 2         | 0.25%   |
| Artix         | 2         | 0.25%   |
| Ubuntu MATE   | 1         | 0.12%   |
| Slackware     | 1         | 0.12%   |
| Sabayon       | 1         | 0.12%   |
| Rocky Linux   | 1         | 0.12%   |
| Raspbian      | 1         | 0.12%   |
| PureOS        | 1         | 0.12%   |
| PostmarketOS  | 1         | 0.12%   |
| Parrot        | 1         | 0.12%   |
| MX            | 1         | 0.12%   |
| LMDE          | 1         | 0.12%   |
| Linux Lite    | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 1.68%   |
| 5.4.0-26-generic         | 10        | 1.12%   |
| 5.10.14-desktop-1omv4002 | 9         | 1.01%   |
| 6.5.0-26-generic         | 8         | 0.9%    |
| 6.10.0-desktop-1omv2490  | 8         | 0.9%    |
| 5.3.0-46-generic         | 8         | 0.9%    |
| 5.15.0-47-generic        | 8         | 0.9%    |
| 6.5.0-9-generic          | 7         | 0.79%   |
| 5.4.0-58-generic         | 7         | 0.79%   |
| 5.4.0-52-generic         | 7         | 0.79%   |
| 5.3.0-40-generic         | 7         | 0.79%   |
| 5.15.0-56-generic        | 7         | 0.79%   |
| 5.11.0-27-generic        | 7         | 0.79%   |
| 5.4.0-48-generic         | 6         | 0.67%   |
| 5.16.7-desktop-1omv4003  | 6         | 0.67%   |
| 5.11.0-41-generic        | 6         | 0.67%   |
| 5.0.0-23-generic         | 6         | 0.67%   |
| 6.5.0-21-generic         | 5         | 0.56%   |
| 6.4.11-desktop-1omv2390  | 5         | 0.56%   |
| 6.2.0-39-generic         | 5         | 0.56%   |
| 6.2.0-20-generic         | 5         | 0.56%   |
| 5.8.0-63-generic         | 5         | 0.56%   |
| 5.8.0-48-generic         | 5         | 0.56%   |
| 5.15.0-58-generic        | 5         | 0.56%   |
| 5.0.0-37-generic         | 5         | 0.56%   |
| 5.0.0-25-generic         | 5         | 0.56%   |
| 5.0.0-13-generic         | 5         | 0.56%   |
| 4.18.0-15-generic        | 5         | 0.56%   |
| 4.15.0-29-generic        | 5         | 0.56%   |
| 6.8.0-49-generic         | 4         | 0.45%   |
| 6.6.2-desktop-1omv2390   | 4         | 0.45%   |
| 6.2.9-300.fc38.x86_64    | 4         | 0.45%   |
| 6.2.6-desktop-1omv2390   | 4         | 0.45%   |
| 6.2.0-35-generic         | 4         | 0.45%   |
| 5.8.0-50-generic         | 4         | 0.45%   |
| 5.3.0-51-generic         | 4         | 0.45%   |
| 5.19.0-35-generic        | 4         | 0.45%   |
| 5.13.0-30-generic        | 4         | 0.45%   |
| 4.18.0-25-generic        | 4         | 0.45%   |
| 4.18.0-18-generic        | 4         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 107       | 12.37%  |
| 5.15.0  | 63        | 7.28%   |
| 6.5.0   | 40        | 4.62%   |
| 4.15.0  | 39        | 4.51%   |
| 5.0.0   | 38        | 4.39%   |
| 5.11.0  | 36        | 4.16%   |
| 5.8.0   | 34        | 3.93%   |
| 5.3.0   | 33        | 3.82%   |
| 5.13.0  | 29        | 3.35%   |
| 6.8.0   | 27        | 3.12%   |
| 4.18.0  | 25        | 2.89%   |
| 6.2.0   | 23        | 2.66%   |
| 5.19.0  | 21        | 2.43%   |
| 5.10.0  | 16        | 1.85%   |
| 6.1.0   | 12        | 1.39%   |
| 6.4.11  | 9         | 1.04%   |
| 5.10.14 | 9         | 1.04%   |
| 6.10.0  | 8         | 0.92%   |
| 5.16.7  | 7         | 0.81%   |
| 4.13.0  | 6         | 0.69%   |
| 6.2.9   | 5         | 0.58%   |
| 6.8.9   | 4         | 0.46%   |
| 6.8.11  | 4         | 0.46%   |
| 6.6.2   | 4         | 0.46%   |
| 6.2.6   | 4         | 0.46%   |
| 5.8.18  | 4         | 0.46%   |
| 5.16.15 | 4         | 0.46%   |
| 5.11.11 | 4         | 0.46%   |
| 6.9.3   | 3         | 0.35%   |
| 6.7.4   | 3         | 0.35%   |
| 6.5.9   | 3         | 0.35%   |
| 6.4.8   | 3         | 0.35%   |
| 6.4.12  | 3         | 0.35%   |
| 5.9.16  | 3         | 0.35%   |
| 5.6.0   | 3         | 0.35%   |
| 5.18.0  | 3         | 0.35%   |
| 5.16.0  | 3         | 0.35%   |
| 5.14.16 | 3         | 0.35%   |
| 5.13.19 | 3         | 0.35%   |
| 6.9.4   | 2         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 113       | 13.23%  |
| 5.15    | 77        | 9.02%   |
| 6.5     | 47        | 5.5%    |
| 5.8     | 46        | 5.39%   |
| 5.11    | 45        | 5.27%   |
| 5.0     | 41        | 4.8%    |
| 4.15    | 39        | 4.57%   |
| 6.8     | 38        | 4.45%   |
| 5.13    | 38        | 4.45%   |
| 6.2     | 37        | 4.33%   |
| 5.10    | 35        | 4.1%    |
| 5.3     | 34        | 3.98%   |
| 6.4     | 25        | 2.93%   |
| 4.18    | 25        | 2.93%   |
| 5.19    | 23        | 2.69%   |
| 6.1     | 22        | 2.58%   |
| 6.6     | 20        | 2.34%   |
| 6.10    | 18        | 2.11%   |
| 5.16    | 18        | 2.11%   |
| 5.14    | 12        | 1.41%   |
| 6.9     | 9         | 1.05%   |
| 6.3     | 8         | 0.94%   |
| 6.11    | 8         | 0.94%   |
| 5.9     | 8         | 0.94%   |
| 5.18    | 8         | 0.94%   |
| 6.0     | 7         | 0.82%   |
| 5.6     | 7         | 0.82%   |
| 5.12    | 7         | 0.82%   |
| 6.7     | 6         | 0.7%    |
| 4.13    | 6         | 0.7%    |
| 5.7     | 5         | 0.59%   |
| 4.19    | 5         | 0.59%   |
| 5.17    | 3         | 0.35%   |
| 4.9     | 3         | 0.35%   |
| 6.12    | 2         | 0.23%   |
| 5.5     | 2         | 0.23%   |
| 4.14    | 2         | 0.23%   |
| 5.2     | 1         | 0.12%   |
| 4.5     | 1         | 0.12%   |
| 4.20    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 777       | 97.61%  |
| i686    | 15        | 1.88%   |
| aarch64 | 3         | 0.38%   |
| armv7l  | 1         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 448       | 54.37%  |
| Unknown       | 109       | 13.23%  |
| KDE5          | 88        | 10.68%  |
| XFCE          | 64        | 7.77%   |
| X-Cinnamon    | 28        | 3.4%    |
| KDE           | 21        | 2.55%   |
| i3            | 12        | 1.46%   |
| LXQt          | 8         | 0.97%   |
| KDE6          | 8         | 0.97%   |
| MATE          | 7         | 0.85%   |
| Budgie        | 6         | 0.73%   |
| Unity         | 5         | 0.61%   |
| Pantheon      | 4         | 0.49%   |
| GNOME Classic | 3         | 0.36%   |
| bspwm         | 3         | 0.36%   |
| sway          | 2         | 0.24%   |
| KDE4          | 2         | 0.24%   |
| Cinnamon      | 2         | 0.24%   |
| Trinity       | 1         | 0.12%   |
| LXDE          | 1         | 0.12%   |
| enlightenment | 1         | 0.12%   |
| Deepin        | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 534       | 65.12%  |
| Wayland | 201       | 24.51%  |
| Unknown | 75        | 9.15%   |
| Tty     | 10        | 1.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 385       | 46.55%  |
| GDM3    | 138       | 16.69%  |
| SDDM    | 111       | 13.42%  |
| GDM     | 103       | 12.45%  |
| LightDM | 68        | 8.22%   |
| TDM     | 14        | 1.69%   |
| Ly      | 3         | 0.36%   |
| XDM     | 2         | 0.24%   |
| KDM     | 2         | 0.24%   |
| LXDM    | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 647       | 80.17%  |
| Unknown | 93        | 11.52%  |
| en_GB   | 23        | 2.85%   |
| C       | 15        | 1.86%   |
| fa_IR   | 13        | 1.61%   |
| en_CA   | 7         | 0.87%   |
| en_AG   | 2         | 0.25%   |
| ru_RU   | 1         | 0.12%   |
| POSIX   | 1         | 0.12%   |
| ja_JP   | 1         | 0.12%   |
| en_150  | 1         | 0.12%   |
| en.US   | 1         | 0.12%   |
| de_DE   | 1         | 0.12%   |
| az_IR   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 433       | 53.39%  |
| EFI  | 378       | 46.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 606       | 74.91%  |
| Btrfs   | 68        | 8.41%   |
| Tmpfs   | 51        | 6.3%    |
| Overlay | 46        | 5.69%   |
| Unknown | 19        | 2.35%   |
| Xfs     | 9         | 1.11%   |
| Zfs     | 6         | 0.74%   |
| Ext3    | 2         | 0.25%   |
| F2fs    | 1         | 0.12%   |
| Ext2    | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 417       | 51.61%  |
| GPT     | 325       | 40.22%  |
| MBR     | 66        | 8.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 678       | 83.81%  |
| Yes       | 131       | 16.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 446       | 55.4%   |
| Yes       | 359       | 44.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 268       | 33.67%  |
| Lenovo                  | 158       | 19.85%  |
| Hewlett-Packard         | 115       | 14.45%  |
| Dell                    | 57        | 7.16%   |
| Gigabyte Technology     | 47        | 5.9%    |
| Acer                    | 45        | 5.65%   |
| MSI                     | 26        | 3.27%   |
| Sony                    | 16        | 2.01%   |
| Apple                   | 10        | 1.26%   |
| Toshiba                 | 8         | 1.01%   |
| ECS                     | 7         | 0.88%   |
| Unknown                 | 6         | 0.75%   |
| ASRock                  | 5         | 0.63%   |
| Fujitsu                 | 4         | 0.5%    |
| Microsoft               | 3         | 0.38%   |
| YANYU                   | 2         | 0.25%   |
| Raspberry Pi Foundation | 2         | 0.25%   |
| Biostar                 | 2         | 0.25%   |
| Timi                    | 1         | 0.13%   |
| Supermicro              | 1         | 0.13%   |
| Samsung Electronics     | 1         | 0.13%   |
| Rockchip                | 1         | 0.13%   |
| Razer                   | 1         | 0.13%   |
| Packard Bell            | 1         | 0.13%   |
| LG Electronics          | 1         | 0.13%   |
| Intel                   | 1         | 0.13%   |
| HPE                     | 1         | 0.13%   |
| HIGRADED                | 1         | 0.13%   |
| Foxconn                 | 1         | 0.13%   |
| DFI                     | 1         | 0.13%   |
| Alienware               | 1         | 0.13%   |
| Acidanthera             | 1         | 0.13%   |
| 3Logic Group            | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 16        | 2.01%   |
| HP Compaq Elite 8300 SFF                   | 9         | 1.13%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 8         | 1.01%   |
| Unknown                                    | 8         | 1.01%   |
| HP ProBook 4540s                           | 6         | 0.75%   |
| Acer Aspire V3-571G                        | 6         | 0.75%   |
| Lenovo IdeaPad Z510 20287                  | 5         | 0.63%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 5         | 0.63%   |
| Lenovo G50-70 20351                        | 5         | 0.63%   |
| Lenovo IdeaPad 520-15IKB 81BF              | 4         | 0.5%    |
| Lenovo B570e HuronRiver Platform           | 4         | 0.5%    |
| HP Pavilion g6                             | 4         | 0.5%    |
| HP EliteBook 8470p                         | 4         | 0.5%    |
| Dell Vostro 1510                           | 4         | 0.5%    |
| ASUS VivoBook 15_ASUS Laptop X540UBR       | 4         | 0.5%    |
| Lenovo Z50-70 20354                        | 3         | 0.38%   |
| Lenovo Legion 5 15ARH05H 82B1              | 3         | 0.38%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 3         | 0.38%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 3         | 0.38%   |
| Lenovo G510 20238                          | 3         | 0.38%   |
| Lenovo G50-80 80E5                         | 3         | 0.38%   |
| HP ZBook 17 G3                             | 3         | 0.38%   |
| HP ProBook 640 G2                          | 3         | 0.38%   |
| HP EliteBook 8570p                         | 3         | 0.38%   |
| HP EliteBook 840 G2                        | 3         | 0.38%   |
| Dell Vostro 1015                           | 3         | 0.38%   |
| ASUS X580VD                                | 3         | 0.38%   |
| ASUS VivoBook 15_ASUS Laptop X540MB_X540MB | 3         | 0.38%   |
| ASUS PRIME B250-PLUS                       | 3         | 0.38%   |
| ASUS P5P41T-LE                             | 3         | 0.38%   |
| ASUS K55VD                                 | 3         | 0.38%   |
| ASUS H61M-C                                | 3         | 0.38%   |
| ASUS ASUS TUF Gaming F15 FX506LH_FX506LH   | 3         | 0.38%   |
| Toshiba PORTEGE X30-D                      | 2         | 0.25%   |
| MSI Prestige 14 A10RB                      | 2         | 0.25%   |
| Microsoft Surface Book 2                   | 2         | 0.25%   |
| Lenovo V330-15IKB 81AX                     | 2         | 0.25%   |
| Lenovo V15 G4 AMN 82YU                     | 2         | 0.25%   |
| Lenovo ThinkPad X250 20CM002XUS            | 2         | 0.25%   |
| Lenovo ThinkPad E15 20RD0086UE             | 2         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 61        | 7.66%   |
| ASUS VivoBook      | 39        | 4.9%    |
| Acer Aspire        | 38        | 4.77%   |
| Lenovo ThinkPad    | 37        | 4.65%   |
| ASUS PRIME         | 33        | 4.15%   |
| HP EliteBook       | 28        | 3.52%   |
| HP ProBook         | 19        | 2.39%   |
| ASUS ASUS          | 19        | 2.39%   |
| Dell Latitude      | 18        | 2.26%   |
| ASUS All           | 16        | 2.01%   |
| HP Compaq          | 14        | 1.76%   |
| Dell Inspiron      | 14        | 1.76%   |
| Dell Vostro        | 13        | 1.63%   |
| HP Pavilion        | 11        | 1.38%   |
| ASUS TUF           | 10        | 1.26%   |
| ASUS ROG           | 10        | 1.26%   |
| Lenovo Legion      | 9         | 1.13%   |
| Unknown            | 8         | 1.01%   |
| HP ZBook           | 7         | 0.88%   |
| HP EliteDesk       | 6         | 0.75%   |
| ASUS ZenBook       | 6         | 0.75%   |
| Toshiba Satellite  | 5         | 0.63%   |
| Lenovo ThinkBook   | 5         | 0.63%   |
| Lenovo G50-70      | 5         | 0.63%   |
| HP ProDesk         | 5         | 0.63%   |
| Lenovo B570e       | 4         | 0.5%    |
| HP ProLiant        | 4         | 0.5%    |
| Fujitsu LIFEBOOK   | 4         | 0.5%    |
| Toshiba PORTEGE    | 3         | 0.38%   |
| MSI Modern         | 3         | 0.38%   |
| Microsoft Surface  | 3         | 0.38%   |
| Lenovo Z50-70      | 3         | 0.38%   |
| Lenovo V15         | 3         | 0.38%   |
| Lenovo ThinkCentre | 3         | 0.38%   |
| Lenovo G510        | 3         | 0.38%   |
| Lenovo G50-80      | 3         | 0.38%   |
| HP ENVY            | 3         | 0.38%   |
| Dell XPS           | 3         | 0.38%   |
| Dell Studio        | 3         | 0.38%   |
| Dell Precision     | 3         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 78        | 9.8%    |
| 2012    | 76        | 9.55%   |
| 2011    | 58        | 7.29%   |
| 2017    | 57        | 7.16%   |
| 2018    | 55        | 6.91%   |
| 2016    | 54        | 6.78%   |
| 2020    | 50        | 6.28%   |
| 2019    | 49        | 6.16%   |
| 2021    | 48        | 6.03%   |
| 2010    | 48        | 6.03%   |
| 2014    | 47        | 5.9%    |
| 2015    | 46        | 5.78%   |
| 2009    | 34        | 4.27%   |
| 2022    | 26        | 3.27%   |
| 2008    | 26        | 3.27%   |
| 2023    | 16        | 2.01%   |
| 2007    | 11        | 1.38%   |
| 2006    | 8         | 1.01%   |
| Unknown | 4         | 0.5%    |
| 2024    | 2         | 0.25%   |
| 2005    | 2         | 0.25%   |
| 2004    | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 550       | 69.1%   |
| Desktop        | 213       | 26.76%  |
| Tablet         | 9         | 1.13%   |
| Server         | 8         | 1.01%   |
| Convertible    | 6         | 0.75%   |
| System on chip | 3         | 0.38%   |
| Mini pc        | 3         | 0.38%   |
| All in one     | 3         | 0.38%   |
| Other          | 1         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 749       | 93.98%  |
| Enabled  | 48        | 6.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 796       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 235       | 29.34%  |
| 8.01-16.0       | 170       | 21.22%  |
| 16.01-24.0      | 160       | 19.98%  |
| 3.01-4.0        | 140       | 17.48%  |
| 32.01-64.0      | 43        | 5.37%   |
| 1.01-2.0        | 21        | 2.62%   |
| 2.01-3.0        | 13        | 1.62%   |
| 64.01-256.0     | 7         | 0.87%   |
| 24.01-32.0      | 5         | 0.62%   |
| 0.51-1.0        | 4         | 0.5%    |
| More than 256.0 | 3         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 276       | 32.06%  |
| 2.01-3.0   | 255       | 29.62%  |
| 3.01-4.0   | 133       | 15.45%  |
| 4.01-8.0   | 117       | 13.59%  |
| 0.51-1.0   | 38        | 4.41%   |
| 8.01-16.0  | 30        | 3.48%   |
| 0.01-0.5   | 9         | 1.05%   |
| 16.01-24.0 | 2         | 0.23%   |
| 24.01-32.0 | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 506       | 62.62%  |
| 2       | 238       | 29.46%  |
| 3       | 42        | 5.2%    |
| 4       | 13        | 1.61%   |
| 5       | 3         | 0.37%   |
| 0       | 3         | 0.37%   |
| 6       | 2         | 0.25%   |
| Unknown | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 464       | 57.64%  |
| Yes       | 341       | 42.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 697       | 87.45%  |
| No        | 100       | 12.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 670       | 83.54%  |
| No        | 132       | 16.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 511       | 63.72%  |
| No        | 291       | 36.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Iran    | 796       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Tehran                         | 488       | 58.03%  |
| TehrДЃn                      | 46        | 5.47%   |
| Mashhad                        | 33        | 3.92%   |
| Isfahan                        | 29        | 3.45%   |
| Shiraz                         | 21        | 2.5%    |
| Karaj                          | 18        | 2.14%   |
| Tabriz                         | 12        | 1.43%   |
| Qom                            | 10        | 1.19%   |
| Babol                          | 10        | 1.19%   |
| Tajrīsh                       | 9         | 1.07%   |
| Yazd                           | 7         | 0.83%   |
| Sanandij                       | 7         | 0.83%   |
| Khorramshahr                   | 7         | 0.83%   |
| Rasht                          | 6         | 0.71%   |
| Ahvaz                          | 6         | 0.71%   |
| Kerman                         | 5         | 0.59%   |
| Kermanshah                     | 4         | 0.48%   |
| TajrД«sh                     | 3         | 0.36%   |
| Gorgan                         | 3         | 0.36%   |
| Behshahr                       | 3         | 0.36%   |
| Arak                           | 3         | 0.36%   |
| Zanjan                         | 2         | 0.24%   |
| Shahre Jadide Andisheh         | 2         | 0.24%   |
| Shahr-e Qods                   | 2         | 0.24%   |
| Shahr-e Kord                   | 2         | 0.24%   |
| Sari                           | 2         | 0.24%   |
| Rey                            | 2         | 0.24%   |
| Rehnān                        | 2         | 0.24%   |
| Qazvin                         | 2         | 0.24%   |
| Mīāndoāb                    | 2         | 0.24%   |
| Markaz                         | 2         | 0.24%   |
| Khorramabad                    | 2         | 0.24%   |
| Hamadan                        | 2         | 0.24%   |
| Gachsaran                      | 2         | 0.24%   |
| Farsan                         | 2         | 0.24%   |
| DamДЃvand                    | 2         | 0.24%   |
| BorЕ«jerd                    | 2         | 0.24%   |
| Borazjan                       | 2         | 0.24%   |
| ДЂstДЃneh-ye AshrafД«yeh | 1         | 0.12%   |
| Varamin                        | 1         | 0.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC                          | 204       | 262    | 18.75%  |
| Seagate                      | 177       | 217    | 16.27%  |
| Samsung Electronics          | 141       | 164    | 12.96%  |
| Toshiba                      | 108       | 132    | 9.93%   |
| A-DATA Technology            | 44        | 53     | 4.04%   |
| SanDisk                      | 33        | 38     | 3.03%   |
| Micron Technology            | 31        | 41     | 2.85%   |
| Intel                        | 30        | 31     | 2.76%   |
| Maxtor                       | 24        | 32     | 2.21%   |
| HGST                         | 22        | 26     | 2.02%   |
| Unknown                      | 21        | 22     | 1.93%   |
| Lexar                        | 21        | 26     | 1.93%   |
| Hitachi                      | 21        | 24     | 1.93%   |
| SK hynix                     | 17        | 20     | 1.56%   |
| Kingston                     | 17        | 23     | 1.56%   |
| PNY                          | 10        | 12     | 0.92%   |
| SPCC                         | 8         | 10     | 0.74%   |
| LITEON                       | 8         | 9      | 0.74%   |
| Apple                        | 8         | 12     | 0.74%   |
| Kingmax                      | 7         | 8      | 0.64%   |
| Apacer                       | 7         | 7      | 0.64%   |
| Silicon Motion               | 6         | 6      | 0.55%   |
| MSI                          | 6         | 6      | 0.55%   |
| Gigabyte Technology          | 6         | 7      | 0.55%   |
| Crucial                      | 6         | 7      | 0.55%   |
| Unknown                      | 5         | 6      | 0.46%   |
| Union Memory (Shenzhen)      | 4         | 4      | 0.37%   |
| Shenzhen Longsys Electronics | 4         | 6      | 0.37%   |
| Plextor                      | 4         | 4      | 0.37%   |
| Team                         | 3         | 3      | 0.28%   |
| Realtek Semiconductor        | 3         | 4      | 0.28%   |
| Phison Electronics           | 3         | 3      | 0.28%   |
| MAXIO Technology (Hangzhou)  | 3         | 3      | 0.28%   |
| LITEONIT                     | 3         | 4      | 0.28%   |
| Hewlett-Packard              | 3         | 3      | 0.28%   |
| China                        | 3         | 3      | 0.28%   |
| Biostar                      | 3         | 4      | 0.28%   |
| XPG                          | 2         | 2      | 0.18%   |
| ValueTech                    | 2         | 3      | 0.18%   |
| USB                          | 2         | 2      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 43        | 3.79%   |
| Toshiba MQ01ABD100 1TB                              | 20        | 1.76%   |
| Toshiba MQ04ABF100 1TB                              | 19        | 1.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 18        | 1.59%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 15        | 1.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 13        | 1.15%   |
| WDC WD10SPZX-08Z10 1TB                              | 12        | 1.06%   |
| Seagate ST9500325AS 500GB                           | 12        | 1.06%   |
| Samsung SSD 860 EVO 500GB                           | 12        | 1.06%   |
| WDC WD10SPZX-24Z10 1TB                              | 10        | 0.88%   |
| A-DATA SU650 120GB SSD                              | 10        | 0.88%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 9         | 0.79%   |
| Toshiba MQ01ABF050 500GB                            | 9         | 0.79%   |
| Samsung SSD 860 EVO 250GB                           | 9         | 0.79%   |
| Samsung SSD 850 EVO 250GB                           | 9         | 0.79%   |
| Seagate ST500DM002-1BD142 500GB                     | 8         | 0.7%    |
| Seagate ST2000LM007-1R8174 2TB                      | 8         | 0.7%    |
| Lexar 128GB SSD                                     | 8         | 0.7%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 7         | 0.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 7         | 0.62%   |
| Micron 2210_MTFDHBA512QFD 512GB                     | 7         | 0.62%   |
| Seagate ST9500420AS 500GB                           | 6         | 0.53%   |
| Seagate ST500LT012-1DG142 500GB                     | 6         | 0.53%   |
| Maxtor STM3250310AS 250GB                           | 6         | 0.53%   |
| Lexar 256GB SSD                                     | 6         | 0.53%   |
| HGST HTS721010A9E630 1TB                            | 6         | 0.53%   |
| Unknown MMC Card  32GB                              | 5         | 0.44%   |
| Toshiba MQ01ABD075 752GB                            | 5         | 0.44%   |
| Toshiba MQ01ABD050V 500GB                           | 5         | 0.44%   |
| Toshiba MQ01ABD050 500GB                            | 5         | 0.44%   |
| Toshiba DT01ACA050 500GB                            | 5         | 0.44%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 5         | 0.44%   |
| Samsung SSD 870 EVO 500GB                           | 5         | 0.44%   |
| Maxtor STM3160215AS 160GB                           | 5         | 0.44%   |
| A-DATA SU630 240GB SSD                              | 5         | 0.44%   |
| Unknown                                             | 5         | 0.44%   |
| WDC WD20PURZ-85GU6Y0 2TB                            | 4         | 0.35%   |
| WDC WD10EZRX-00L4HB0 1TB                            | 4         | 0.35%   |
| SK hynix HFM001TD3JX013N 1024GB                     | 4         | 0.35%   |
| Seagate ST3500418AS 500GB                           | 4         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 177       | 217    | 32.9%   |
| WDC                 | 173       | 218    | 32.16%  |
| Toshiba             | 98        | 118    | 18.22%  |
| Maxtor              | 24        | 32     | 4.46%   |
| HGST                | 22        | 26     | 4.09%   |
| Hitachi             | 21        | 24     | 3.9%    |
| Samsung Electronics | 10        | 14     | 1.86%   |
| Hewlett-Packard     | 3         | 3      | 0.56%   |
| Apple               | 3         | 5      | 0.56%   |
| Unknown             | 2         | 2      | 0.37%   |
| TO Exter            | 1         | 1      | 0.19%   |
| Teleplan            | 1         | 4      | 0.19%   |
| HPE                 | 1         | 1      | 0.19%   |
| Fujitsu             | 1         | 1      | 0.19%   |
| Unknown             | 1         | 2      | 0.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 75        | 86     | 22.46%  |
| A-DATA Technology   | 43        | 52     | 12.87%  |
| WDC                 | 34        | 38     | 10.18%  |
| Lexar               | 19        | 22     | 5.69%   |
| SanDisk             | 18        | 22     | 5.39%   |
| Kingston            | 14        | 19     | 4.19%   |
| Micron Technology   | 12        | 12     | 3.59%   |
| PNY                 | 9         | 10     | 2.69%   |
| SPCC                | 8         | 10     | 2.4%    |
| SK hynix            | 8         | 10     | 2.4%    |
| LITEON              | 8         | 9      | 2.4%    |
| Gigabyte Technology | 6         | 7      | 1.8%    |
| Crucial             | 6         | 7      | 1.8%    |
| Apacer              | 6         | 6      | 1.8%    |
| Toshiba             | 5         | 9      | 1.5%    |
| Kingmax             | 5         | 6      | 1.5%    |
| Intel               | 5         | 5      | 1.5%    |
| Plextor             | 4         | 4      | 1.2%    |
| MSI                 | 4         | 4      | 1.2%    |
| Team                | 3         | 3      | 0.9%    |
| LITEONIT            | 3         | 4      | 0.9%    |
| China               | 3         | 3      | 0.9%    |
| Biostar             | 3         | 4      | 0.9%    |
| ValueTech           | 2         | 3      | 0.6%    |
| Transcend           | 2         | 2      | 0.6%    |
| Pioneer             | 2         | 2      | 0.6%    |
| OSCOO               | 2         | 3      | 0.6%    |
| OCZ                 | 2         | 2      | 0.6%    |
| KODAK               | 2         | 2      | 0.6%    |
| KingSpec            | 2         | 2      | 0.6%    |
| Dahua               | 2         | 2      | 0.6%    |
| Apple               | 2         | 2      | 0.6%    |
| X-ENERGY            | 1         | 1      | 0.3%    |
| Western             | 1         | 1      | 0.3%    |
| USB3.0              | 1         | 1      | 0.3%    |
| TwinMOS             | 1         | 1      | 0.3%    |
| SSSTC               | 1         | 1      | 0.3%    |
| Patriot             | 1         | 1      | 0.3%    |
| Netac               | 1         | 1      | 0.3%    |
| MAX                 | 1         | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 503       | 668    | 48.88%  |
| SSD     | 315       | 387    | 30.61%  |
| NVMe    | 181       | 225    | 17.59%  |
| MMC     | 16        | 17     | 1.55%   |
| Unknown | 14        | 16     | 1.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 663       | 1047   | 75%     |
| NVMe | 181       | 223    | 20.48%  |
| SAS  | 24        | 26     | 2.71%   |
| MMC  | 16        | 17     | 1.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 451       | 617    | 56.45%  |
| 0.51-1.0   | 293       | 369    | 36.67%  |
| 1.01-2.0   | 37        | 47     | 4.63%   |
| 3.01-4.0   | 9         | 9      | 1.13%   |
| 2.01-3.0   | 5         | 7      | 0.63%   |
| 10.01-20.0 | 2         | 4      | 0.25%   |
| 4.01-10.0  | 2         | 2      | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 232       | 27.85%  |
| 251-500        | 159       | 19.09%  |
| 501-1000       | 156       | 18.73%  |
| 51-100         | 76        | 9.12%   |
| 1001-2000      | 72        | 8.64%   |
| 1-20           | 48        | 5.76%   |
| 21-50          | 45        | 5.4%    |
| Unknown        | 18        | 2.16%   |
| More than 3000 | 16        | 1.92%   |
| 2001-3000      | 11        | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 306       | 35.96%  |
| 21-50          | 158       | 18.57%  |
| 51-100         | 116       | 13.63%  |
| 101-250        | 101       | 11.87%  |
| 501-1000       | 68        | 7.99%   |
| 251-500        | 63        | 7.4%    |
| Unknown        | 18        | 2.12%   |
| 1001-2000      | 10        | 1.18%   |
| More than 3000 | 7         | 0.82%   |
| 2001-3000      | 4         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB   | 5         | 6      | 6.33%   |
| Toshiba MQ01ABD100 1TB           | 3         | 3      | 3.8%    |
| Toshiba MQ01ABD075 752GB         | 3         | 3      | 3.8%    |
| Seagate ST9500420AS 500GB        | 3         | 3      | 3.8%    |
| Seagate ST9500325AS 500GB        | 3         | 8      | 3.8%    |
| Toshiba MQ01ABF050 500GB         | 2         | 7      | 2.53%   |
| Toshiba MQ01ABD050 500GB         | 2         | 2      | 2.53%   |
| SK hynix SC308 SATA 256GB SSD    | 2         | 2      | 2.53%   |
| Seagate ST500DM002-1BD142 500GB  | 2         | 3      | 2.53%   |
| Seagate ST3500413AS 500GB        | 2         | 2      | 2.53%   |
| HGST HTS541075A9E680 752GB       | 2         | 2      | 2.53%   |
| XPG SPECTRIX S40G 1TB            | 1         | 1      | 1.27%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1         | 1      | 1.27%   |
| WDC WD7500BPVT-80HXZT1 752GB     | 1         | 3      | 1.27%   |
| WDC WD5000LPVX-80V0TT0 500GB     | 1         | 1      | 1.27%   |
| WDC WD5000LPCX-24C6HT0 500GB     | 1         | 1      | 1.27%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1         | 1      | 1.27%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1         | 2      | 1.27%   |
| WDC WD5000AAKS-00V1A0 500GB      | 1         | 1      | 1.27%   |
| WDC WD3200BPVT-75ZEST0 320GB     | 1         | 1      | 1.27%   |
| WDC WD3200AVVS-62L2B0 320GB      | 1         | 1      | 1.27%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1      | 1.27%   |
| WDC WD10SPZX-08Z10 1TB           | 1         | 1      | 1.27%   |
| WDC WD10PURZ-85U8XY0 1TB         | 1         | 1      | 1.27%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 1      | 1.27%   |
| WDC WD10EZRX-00A3KB0 1TB         | 1         | 1      | 1.27%   |
| WDC WD10EZEX-00WN4A0 1TB         | 1         | 1      | 1.27%   |
| WDC WD10EARX-00N0YB0 1TB         | 1         | 1      | 1.27%   |
| WDC WD10EARS-00MVWB0 1TB         | 1         | 1      | 1.27%   |
| WDC WD1002FBYS-18A6B0 1TB        | 1         | 1      | 1.27%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 1.27%   |
| Toshiba MK3265GSXN 320GB         | 1         | 2      | 1.27%   |
| Toshiba MK3263GSX 320GB          | 1         | 1      | 1.27%   |
| Toshiba HDWD105 500GB            | 1         | 1      | 1.27%   |
| SSSTC CVB-8D128-HP 128GB SSD     | 1         | 1      | 1.27%   |
| Seagate ST9250315AS 250GB        | 1         | 2      | 1.27%   |
| Seagate ST500LT012-9WS142 500GB  | 1         | 1      | 1.27%   |
| Seagate ST500LT012-1DG142 500GB  | 1         | 1      | 1.27%   |
| Seagate ST3500418AS 500GB        | 1         | 1      | 1.27%   |
| Seagate ST3320613AS 320GB        | 1         | 1      | 1.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 31     | 29.49%  |
| WDC                 | 17        | 21     | 21.79%  |
| Toshiba             | 14        | 20     | 17.95%  |
| Hitachi             | 6         | 7      | 7.69%   |
| HGST                | 4         | 4      | 5.13%   |
| Samsung Electronics | 3         | 5      | 3.85%   |
| SK hynix            | 2         | 2      | 2.56%   |
| Micron Technology   | 2         | 2      | 2.56%   |
| Maxtor              | 2         | 3      | 2.56%   |
| XPG                 | 1         | 1      | 1.28%   |
| SSSTC               | 1         | 1      | 1.28%   |
| LITEON              | 1         | 1      | 1.28%   |
| Apple               | 1         | 1      | 1.28%   |
| Unknown             | 1         | 2      | 1.28%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 31     | 33.33%  |
| WDC                 | 16        | 20     | 23.19%  |
| Toshiba             | 14        | 20     | 20.29%  |
| Hitachi             | 6         | 7      | 8.7%    |
| HGST                | 4         | 4      | 5.8%    |
| Samsung Electronics | 2         | 3      | 2.9%    |
| Maxtor              | 2         | 3      | 2.9%    |
| Apple               | 1         | 1      | 1.45%   |
| Unknown             | 1         | 2      | 1.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 66        | 91     | 88%     |
| SSD  | 8         | 9      | 10.67%  |
| NVMe | 1         | 1      | 1.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 499       | 799    | 58.91%  |
| Works    | 273       | 412    | 32.23%  |
| Malfunc  | 74        | 101    | 8.74%   |
| Failed   | 1         | 1      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 655       | 70.51%  |
| AMD                                     | 67        | 7.21%   |
| Samsung Electronics                     | 60        | 6.46%   |
| SanDisk                                 | 21        | 2.26%   |
| Micron Technology                       | 19        | 2.05%   |
| Phison Electronics                      | 11        | 1.18%   |
| SK hynix                                | 9         | 0.97%   |
| Silicon Motion                          | 7         | 0.75%   |
| Shenzhen Longsys Electronics            | 7         | 0.75%   |
| Nvidia                                  | 7         | 0.75%   |
| Union Memory (Shenzhen)                 | 6         | 0.65%   |
| Realtek Semiconductor                   | 5         | 0.54%   |
| Marvell Technology Group                | 5         | 0.54%   |
| JMicron Technology                      | 5         | 0.54%   |
| ASMedia Technology                      | 5         | 0.54%   |
| ADATA Technology                        | 5         | 0.54%   |
| VIA Technologies                        | 4         | 0.43%   |
| Toshiba America Info Systems            | 4         | 0.43%   |
| MAXIO Technology (Hangzhou)             | 4         | 0.43%   |
| KIOXIA                                  | 4         | 0.43%   |
| Kingston Technology Company             | 4         | 0.43%   |
| Hewlett-Packard                         | 4         | 0.43%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.22%   |
| Micron/Crucial Technology               | 2         | 0.22%   |
| Apple                                   | 2         | 0.22%   |
| ULi Electronics                         | 1         | 0.11%   |
| Solidigm                                | 1         | 0.11%   |
| Shenzhen Unionmemory Information System | 1         | 0.11%   |
| Broadcom / LSI                          | 1         | 0.11%   |
| Adaptec                                 | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 71        | 6.74%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 53        | 5.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 49        | 4.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 49        | 4.65%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 41        | 3.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 33        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 33        | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 28        | 2.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 26        | 2.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 24        | 2.28%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 23        | 2.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 23        | 2.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 21        | 1.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 21        | 1.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 19        | 1.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 15        | 1.42%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14        | 1.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14        | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 13        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 13        | 1.23%   |
| Intel SSD 660P Series                                                                   | 11        | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 11        | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 10        | 0.95%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 10        | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 10        | 0.95%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 9         | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 9         | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9         | 0.85%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 9         | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 9         | 0.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9         | 0.85%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 8         | 0.76%   |
| Intel SATA Controller [RAID mode]                                                       | 8         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 8         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7         | 0.66%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7         | 0.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 588       | 61.51%  |
| NVMe | 180       | 18.83%  |
| IDE  | 96        | 10.04%  |
| RAID | 90        | 9.41%   |
| SAS  | 2         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 701       | 88.07%  |
| AMD     | 91        | 11.43%  |
| ARM     | 3         | 0.38%   |
| Unknown | 1         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 23        | 2.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 14        | 1.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 13        | 1.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 13        | 1.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 12        | 1.51%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 11        | 1.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 11        | 1.38%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 10        | 1.26%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 10        | 1.26%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 10        | 1.26%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 9         | 1.13%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 9         | 1.13%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 8         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 8         | 1.01%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 8         | 1.01%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 8         | 1.01%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 7         | 0.88%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 7         | 0.88%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 7         | 0.88%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 7         | 0.88%   |
| Intel 12th Gen Core i7-12700H               | 7         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 6         | 0.75%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 6         | 0.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 6         | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 0.75%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 5         | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 5         | 0.63%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 5         | 0.63%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 5         | 0.63%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 5         | 0.63%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 5         | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 0.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 5         | 0.63%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 5         | 0.63%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 5         | 0.63%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 5         | 0.63%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4         | 0.5%    |
| Intel Core i7-8650U CPU @ 1.90GHz           | 4         | 0.5%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 0.5%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 229       | 28.77%  |
| Intel Core i5           | 206       | 25.88%  |
| Other                   | 73        | 9.17%   |
| Intel Core i3           | 56        | 7.04%   |
| Intel Core 2 Duo        | 40        | 5.03%   |
| Intel Pentium           | 30        | 3.77%   |
| AMD Ryzen 7             | 23        | 2.89%   |
| Intel Celeron           | 16        | 2.01%   |
| AMD Ryzen 5             | 15        | 1.88%   |
| Intel Xeon              | 9         | 1.13%   |
| Intel Pentium Dual-Core | 9         | 1.13%   |
| AMD FX                  | 9         | 1.13%   |
| Intel Core 2 Quad       | 8         | 1.01%   |
| Intel Atom              | 8         | 1.01%   |
| AMD Ryzen 3             | 6         | 0.75%   |
| AMD E1                  | 5         | 0.63%   |
| Intel Pentium Dual      | 4         | 0.5%    |
| Intel Xeon Gold         | 3         | 0.38%   |
| Intel Pentium Silver    | 3         | 0.38%   |
| Intel Genuine           | 3         | 0.38%   |
| AMD PRO A10             | 3         | 0.38%   |
| AMD Athlon II X2        | 3         | 0.38%   |
| AMD A4                  | 3         | 0.38%   |
| AMD A10                 | 3         | 0.38%   |
| Intel Pentium 4         | 2         | 0.25%   |
| Intel Core M            | 2         | 0.25%   |
| Intel Core i9           | 2         | 0.25%   |
| AMD Ryzen 3 PRO         | 2         | 0.25%   |
| AMD Athlon 64 X2        | 2         | 0.25%   |
| AMD Athlon 64           | 2         | 0.25%   |
| AMD A6                  | 2         | 0.25%   |
| Intel Pentium D         | 1         | 0.13%   |
| Intel Core Duo          | 1         | 0.13%   |
| Intel Core              | 1         | 0.13%   |
| ARM BCM                 | 1         | 0.13%   |
| AMD Ryzen 9             | 1         | 0.13%   |
| AMD Ryzen 7 PRO         | 1         | 0.13%   |
| AMD PRO A8              | 1         | 0.13%   |
| AMD Phenom II X4        | 1         | 0.13%   |
| AMD Phenom              | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 363       | 45.55%  |
| 4      | 287       | 36.01%  |
| 6      | 48        | 6.02%   |
| 8      | 46        | 5.77%   |
| 14     | 12        | 1.51%   |
| 1      | 12        | 1.51%   |
| 10     | 9         | 1.13%   |
| 12     | 7         | 0.88%   |
| 3      | 4         | 0.5%    |
| 24     | 3         | 0.38%   |
| 28     | 2         | 0.25%   |
| 16     | 2         | 0.25%   |
| 52     | 1         | 0.13%   |
| 44     | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 786       | 98.74%  |
| 2      | 10        | 1.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 572       | 71.68%  |
| 1      | 225       | 28.2%   |
| 4      | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 777       | 97.37%  |
| Unknown        | 14        | 1.75%   |
| 32-bit         | 6         | 0.75%   |
| 64-bit         | 1         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 307       | 37.71%  |
| 0x306a9    | 50        | 6.14%   |
| 0x206a7    | 36        | 4.42%   |
| 0x306c3    | 35        | 4.3%    |
| 0x806ea    | 27        | 3.32%   |
| 0x1067a    | 27        | 3.32%   |
| 0x306d4    | 24        | 2.95%   |
| 0x20655    | 23        | 2.83%   |
| 0x806e9    | 18        | 2.21%   |
| 0x906e9    | 16        | 1.97%   |
| 0x506e3    | 16        | 1.97%   |
| 0x806ec    | 15        | 1.84%   |
| 0x906ea    | 14        | 1.72%   |
| 0x40651    | 13        | 1.6%    |
| 0x806c1    | 11        | 1.35%   |
| 0x906a3    | 9         | 1.11%   |
| 0x6fd      | 9         | 1.11%   |
| 0x406e3    | 9         | 1.11%   |
| 0x20652    | 7         | 0.86%   |
| 0xa0652    | 6         | 0.74%   |
| 0x706e5    | 6         | 0.74%   |
| 0x106e5    | 6         | 0.74%   |
| 0x6fb      | 5         | 0.61%   |
| 0x10676    | 5         | 0.61%   |
| 0x906ed    | 4         | 0.49%   |
| 0x706a1    | 4         | 0.49%   |
| 0x0a50000c | 4         | 0.49%   |
| 0x08608103 | 4         | 0.49%   |
| 0x0700010f | 4         | 0.49%   |
| 0x0600611a | 4         | 0.49%   |
| 0x90672    | 3         | 0.37%   |
| 0x806d1    | 3         | 0.37%   |
| 0x30678    | 3         | 0.37%   |
| 0x106ca    | 3         | 0.37%   |
| 0x0a50000d | 3         | 0.37%   |
| 0x08108109 | 3         | 0.37%   |
| 0x06003106 | 3         | 0.37%   |
| 0x010000c8 | 3         | 0.37%   |
| 0xa0653    | 2         | 0.25%   |
| 0x906eb    | 2         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 151       | 18.95%  |
| Haswell          | 93        | 11.67%  |
| IvyBridge        | 79        | 9.91%   |
| Skylake          | 55        | 6.9%    |
| SandyBridge      | 54        | 6.78%   |
| Penryn           | 45        | 5.65%   |
| Unknown          | 36        | 4.52%   |
| Westmere         | 34        | 4.27%   |
| Broadwell        | 31        | 3.89%   |
| Alderlake Hybrid | 24        | 3.01%   |
| TigerLake        | 22        | 2.76%   |
| CometLake        | 21        | 2.63%   |
| Core             | 18        | 2.26%   |
| Zen 3            | 12        | 1.51%   |
| IceLake          | 11        | 1.38%   |
| Nehalem          | 10        | 1.25%   |
| Excavator        | 10        | 1.25%   |
| Zen+             | 9         | 1.13%   |
| Zen 2            | 9         | 1.13%   |
| Goldmont plus    | 9         | 1.13%   |
| Silvermont       | 7         | 0.88%   |
| K10              | 7         | 0.88%   |
| Zen              | 6         | 0.75%   |
| Bonnell          | 6         | 0.75%   |
| Steamroller      | 5         | 0.63%   |
| NetBurst         | 5         | 0.63%   |
| Jaguar           | 5         | 0.63%   |
| Puma             | 4         | 0.5%    |
| K8 Hammer        | 4         | 0.5%    |
| P6               | 3         | 0.38%   |
| Goldmont         | 3         | 0.38%   |
| Bulldozer        | 3         | 0.38%   |
| Bobcat           | 3         | 0.38%   |
| Piledriver       | 1         | 0.13%   |
| K10 Llano        | 1         | 0.13%   |
| Gracemont        | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 545       | 48.23%  |
| Nvidia                           | 375       | 33.19%  |
| AMD                              | 199       | 17.61%  |
| ASPEED Technology                | 4         | 0.35%   |
| Matrox Electronics Systems       | 3         | 0.27%   |
| VIA Technologies                 | 1         | 0.09%   |
| Trident Microsystems             | 1         | 0.09%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |
| ATI Technologies                 | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 46        | 4%      |
| Intel UHD Graphics 620                                                                | 39        | 3.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 39        | 3.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 30        | 2.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 29        | 2.52%   |
| Intel HD Graphics 620                                                                 | 27        | 2.35%   |
| Intel HD Graphics 5500                                                                | 25        | 2.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 21        | 1.83%   |
| Intel HD Graphics 530                                                                 | 21        | 1.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 20        | 1.74%   |
| Intel Core Processor Integrated Graphics Controller                                   | 19        | 1.65%   |
| Intel HD Graphics 630                                                                 | 18        | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 17        | 1.48%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 16        | 1.39%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 16        | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 16        | 1.39%   |
| Nvidia GP108M [GeForce MX150]                                                         | 15        | 1.31%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 14        | 1.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 13        | 1.13%   |
| Nvidia GT218 [GeForce 210]                                                            | 12        | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 12        | 1.04%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 12        | 1.04%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                      | 12        | 1.04%   |
| Nvidia GM108M [GeForce MX110]                                                         | 11        | 0.96%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 11        | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 11        | 0.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 11        | 0.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 11        | 0.96%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 11        | 0.96%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 11        | 0.96%   |
| Nvidia GP107M [GeForce MX350]                                                         | 10        | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 10        | 0.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 9         | 0.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 9         | 0.78%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 8         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 8         | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 8         | 0.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 8         | 0.7%    |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 8         | 0.7%    |
| Nvidia GM108M [GeForce 840M]                                                          | 7         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Intel + Nvidia           | 247       | 30.99%  |
| 1 x Intel                | 223       | 27.98%  |
| 1 x Nvidia               | 111       | 13.93%  |
| 1 x AMD                  | 101       | 12.67%  |
| Intel + AMD              | 71        | 8.91%   |
| AMD + Nvidia             | 16        | 2.01%   |
| 2 x AMD                  | 13        | 1.63%   |
| Other                    | 4         | 0.5%    |
| 1 x Matrox               | 3         | 0.38%   |
| Nvidia + ASPEED          | 2         | 0.25%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.13%   |
| 2 x Intel                | 1         | 0.13%   |
| 1 x VIA                  | 1         | 0.13%   |
| 1 x Trident Microsystems | 1         | 0.13%   |
| 1 x SiS                  | 1         | 0.13%   |
| 1 x ASPEED               | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 604       | 74.94%  |
| Proprietary | 170       | 21.09%  |
| Unknown     | 32        | 3.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 427       | 52.59%  |
| 1.01-2.0   | 138       | 17%     |
| 0.51-1.0   | 79        | 9.73%   |
| 3.01-4.0   | 76        | 9.36%   |
| 0.01-0.5   | 60        | 7.39%   |
| 7.01-8.0   | 14        | 1.72%   |
| 5.01-6.0   | 13        | 1.6%    |
| 8.01-16.0  | 4         | 0.49%   |
| 2.01-3.0   | 1         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 128       | 16.12%  |
| AU Optronics            | 112       | 14.11%  |
| LG Display              | 99        | 12.47%  |
| BOE                     | 98        | 12.34%  |
| Chimei Innolux          | 90        | 11.34%  |
| Goldstar                | 78        | 9.82%   |
| PANDA                   | 15        | 1.89%   |
| Hewlett-Packard         | 14        | 1.76%   |
| Chi Mei Optoelectronics | 14        | 1.76%   |
| Ancor Communications    | 12        | 1.51%   |
| Apple                   | 11        | 1.39%   |
| AOC                     | 11        | 1.39%   |
| BenQ                    | 10        | 1.26%   |
| CHD                     | 8         | 1.01%   |
| Sony                    | 7         | 0.88%   |
| Lenovo                  | 7         | 0.88%   |
| Dell                    | 7         | 0.88%   |
| Sharp                   | 6         | 0.76%   |
| MSI                     | 5         | 0.63%   |
| LG Electronics          | 5         | 0.63%   |
| HannStar                | 5         | 0.63%   |
| ASUSTek Computer        | 5         | 0.63%   |
| RTK                     | 4         | 0.5%    |
| Unknown                 | 3         | 0.38%   |
| LG Philips              | 3         | 0.38%   |
| InfoVision              | 3         | 0.38%   |
| ViewSonic               | 2         | 0.25%   |
| Unknown (ADA)           | 2         | 0.25%   |
| Nvidia                  | 2         | 0.25%   |
| InnoLux Display         | 2         | 0.25%   |
| HUAWEI                  | 2         | 0.25%   |
| GOL                     | 2         | 0.25%   |
| CSO                     | 2         | 0.25%   |
| Acer                    | 2         | 0.25%   |
| XVision                 | 1         | 0.13%   |
| Xiaomi                  | 1         | 0.13%   |
| TMX                     | 1         | 0.13%   |
| Seiko/Epson             | 1         | 0.13%   |
| SEEYOO                  | 1         | 0.13%   |
| RGT                     | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 13        | 1.61%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 9         | 1.11%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 9         | 1.11%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.99%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 0.99%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 7         | 0.87%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 6         | 0.74%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 6         | 0.74%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 5         | 0.62%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch         | 5         | 0.62%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 5         | 0.62%   |
| Goldstar W2053 GSM4E9F 1600x900 443x249mm 20.0-inch                      | 5         | 0.62%   |
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch                  | 5         | 0.62%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 5         | 0.62%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                      | 5         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 5         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 5         | 0.62%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.62%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.62%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch        | 4         | 0.49%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch         | 4         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 4         | 0.49%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                   | 4         | 0.49%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 0.49%   |
| CHD GDM-245LN CHD0240 1920x1080 470x280mm 21.5-inch                      | 4         | 0.49%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 4         | 0.49%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 4         | 0.49%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 480x270mm 21.7-inch        | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch    | 3         | 0.37%   |
| PANDA LCD Monitor NCP003B 1920x1080 344x194mm 15.5-inch                  | 3         | 0.37%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 3         | 0.37%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 3         | 0.37%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 3         | 0.37%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 3         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 339       | 43.86%  |
| 1366x768 (WXGA)    | 222       | 28.72%  |
| 1600x900 (HD+)     | 41        | 5.3%    |
| 1440x900 (WXGA+)   | 28        | 3.62%   |
| 3840x2160 (4K)     | 27        | 3.49%   |
| 1280x800 (WXGA)    | 19        | 2.46%   |
| 1280x1024 (SXGA)   | 13        | 1.68%   |
| 1680x1050 (WSXGA+) | 12        | 1.55%   |
| 1360x768           | 11        | 1.42%   |
| 2560x1440 (QHD)    | 10        | 1.29%   |
| 1920x1200 (WUXGA)  | 7         | 0.91%   |
| 2560x1600          | 5         | 0.65%   |
| Unknown            | 5         | 0.65%   |
| 2560x1080          | 4         | 0.52%   |
| 1024x600           | 4         | 0.52%   |
| 2880x1800          | 3         | 0.39%   |
| 2880x1620          | 3         | 0.39%   |
| 3840x2400          | 2         | 0.26%   |
| 3240x2160          | 2         | 0.26%   |
| 3200x1800 (QHD+)   | 2         | 0.26%   |
| 2880x1920          | 2         | 0.26%   |
| 1280x960           | 2         | 0.26%   |
| 5760x2160          | 1         | 0.13%   |
| 3840x1080          | 1         | 0.13%   |
| 3200x2000          | 1         | 0.13%   |
| 3000x2000          | 1         | 0.13%   |
| 2944x1080          | 1         | 0.13%   |
| 2720x768           | 1         | 0.13%   |
| 2304x1440          | 1         | 0.13%   |
| 1920x1280          | 1         | 0.13%   |
| 1680x945           | 1         | 0.13%   |
| 1280x720 (HD)      | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 358       | 45.09%  |
| 13      | 61        | 7.68%   |
| 14      | 58        | 7.3%    |
| 21      | 52        | 6.55%   |
| 18      | 28        | 3.53%   |
| 23      | 26        | 3.27%   |
| 20      | 25        | 3.15%   |
| Unknown | 25        | 3.15%   |
| 19      | 22        | 2.77%   |
| 24      | 20        | 2.52%   |
| 17      | 19        | 2.39%   |
| 27      | 18        | 2.27%   |
| 12      | 15        | 1.89%   |
| 16      | 12        | 1.51%   |
| 22      | 9         | 1.13%   |
| 31      | 8         | 1.01%   |
| 11      | 8         | 1.01%   |
| 10      | 5         | 0.63%   |
| 46      | 4         | 0.5%    |
| 29      | 3         | 0.38%   |
| 84      | 2         | 0.25%   |
| 72      | 2         | 0.25%   |
| 65      | 2         | 0.25%   |
| 54      | 2         | 0.25%   |
| 32      | 2         | 0.25%   |
| 7       | 2         | 0.25%   |
| 75      | 1         | 0.13%   |
| 50      | 1         | 0.13%   |
| 40      | 1         | 0.13%   |
| 34      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |
| 25      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 465       | 59.01%  |
| 401-500     | 129       | 16.37%  |
| 501-600     | 64        | 8.12%   |
| 201-300     | 48        | 6.09%   |
| 351-400     | 25        | 3.17%   |
| Unknown     | 25        | 3.17%   |
| 601-700     | 12        | 1.52%   |
| 1001-1500   | 9         | 1.14%   |
| 1501-2000   | 5         | 0.63%   |
| 701-800     | 3         | 0.38%   |
| 101-200     | 2         | 0.25%   |
| 801-900     | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 625       | 84.57%  |
| 16/10   | 67        | 9.07%   |
| Unknown | 22        | 2.98%   |
| 5/4     | 8         | 1.08%   |
| 3/2     | 8         | 1.08%   |
| 4/3     | 6         | 0.81%   |
| 21/9    | 3         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 357       | 45.08%  |
| 81-90          | 100       | 12.63%  |
| 201-250        | 93        | 11.74%  |
| 151-200        | 56        | 7.07%   |
| 141-150        | 32        | 4.04%   |
| Unknown        | 25        | 3.16%   |
| 301-350        | 20        | 2.53%   |
| 71-80          | 17        | 2.15%   |
| 61-70          | 15        | 1.89%   |
| 121-130        | 14        | 1.77%   |
| 351-500        | 12        | 1.52%   |
| More than 1000 | 10        | 1.26%   |
| 51-60          | 8         | 1.01%   |
| 111-120        | 8         | 1.01%   |
| 251-300        | 6         | 0.76%   |
| 41-50          | 5         | 0.63%   |
| 501-1000       | 5         | 0.63%   |
| 131-140        | 4         | 0.51%   |
| 91-100         | 3         | 0.38%   |
| 1-40           | 2         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 258       | 33.03%  |
| 101-120       | 241       | 30.86%  |
| 51-100        | 197       | 25.22%  |
| 161-240       | 26        | 3.33%   |
| Unknown       | 25        | 3.2%    |
| More than 240 | 23        | 2.94%   |
| 1-50          | 11        | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 672       | 83.69%  |
| 2     | 86        | 10.71%  |
| 0     | 42        | 5.23%   |
| 3     | 3         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 460       | 35.83%  |
| Intel                                  | 337       | 26.25%  |
| Qualcomm Atheros                       | 155       | 12.07%  |
| Broadcom                               | 73        | 5.69%   |
| Ralink Technology                      | 29        | 2.26%   |
| MediaTek                               | 29        | 2.26%   |
| Samsung Electronics                    | 25        | 1.95%   |
| Ralink                                 | 22        | 1.71%   |
| Broadcom Limited                       | 21        | 1.64%   |
| Xiaomi                                 | 20        | 1.56%   |
| D-Link                                 | 18        | 1.4%    |
| Marvell Technology Group               | 15        | 1.17%   |
| TP-Link                                | 12        | 0.93%   |
| Huawei Technologies                    | 8         | 0.62%   |
| Hewlett-Packard                        | 7         | 0.55%   |
| VIA Technologies                       | 6         | 0.47%   |
| Nvidia                                 | 5         | 0.39%   |
| D-Link System                          | 5         | 0.39%   |
| Qualcomm Atheros Communications        | 3         | 0.23%   |
| JMicron Technology                     | 3         | 0.23%   |
| HTC (High Tech Computer)               | 3         | 0.23%   |
| ASUSTek Computer                       | 3         | 0.23%   |
| Apple                                  | 3         | 0.23%   |
| Qualcomm                               | 2         | 0.16%   |
| Microsoft                              | 2         | 0.16%   |
| ICS Advent                             | 2         | 0.16%   |
| ASIX Electronics                       | 2         | 0.16%   |
| ZyDAS                                  | 1         | 0.08%   |
| Tenda                                  | 1         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| Smart Link                             | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.08%   |
| Sierra Wireless                        | 1         | 0.08%   |
| Qualcomm Technologies                  | 1         | 0.08%   |
| LG Electronics                         | 1         | 0.08%   |
| Lenovo                                 | 1         | 0.08%   |
| BUFFALO                                | 1         | 0.08%   |
| Attansic Technology                    | 1         | 0.08%   |
| Aquantia                               | 1         | 0.08%   |
| Accton Technology                      | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 354       | 24.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 42        | 2.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 29        | 1.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 26        | 1.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 26        | 1.77%   |
| Intel Wireless 7265                                                    | 26        | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 24        | 1.63%   |
| Ralink MT7601U Wireless Adapter                                        | 22        | 1.49%   |
| Intel Wireless 8265 / 8275                                             | 22        | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 20        | 1.36%   |
| Intel Wireless 8260                                                    | 20        | 1.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 19        | 1.29%   |
| Intel Wireless 7260                                                    | 18        | 1.22%   |
| Intel Wi-Fi 6 AX201                                                    | 17        | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 16        | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 1.09%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 15        | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 15        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 15        | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                          | 14        | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 13        | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 12        | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 11        | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 11        | 0.75%   |
| Intel Ethernet Connection I217-LM                                      | 11        | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 11        | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 10        | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 10        | 0.68%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 9         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 9         | 0.61%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 8         | 0.54%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 8         | 0.54%   |
| Intel Wi-Fi 6 AX200                                                    | 8         | 0.54%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 8         | 0.54%   |
| Intel Centrino Ultimate-N 6300                                         | 8         | 0.54%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                         | 8         | 0.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 8         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 268       | 38.9%   |
| Qualcomm Atheros                | 119       | 17.27%  |
| Realtek Semiconductor           | 109       | 15.82%  |
| Broadcom                        | 49        | 7.11%   |
| Ralink Technology               | 29        | 4.21%   |
| MediaTek                        | 27        | 3.92%   |
| Ralink                          | 22        | 3.19%   |
| Broadcom Limited                | 18        | 2.61%   |
| D-Link                          | 17        | 2.47%   |
| TP-Link                         | 11        | 1.6%    |
| Hewlett-Packard                 | 4         | 0.58%   |
| Qualcomm Atheros Communications | 3         | 0.44%   |
| D-Link System                   | 3         | 0.44%   |
| Marvell Technology Group        | 2         | 0.29%   |
| ZyDAS                           | 1         | 0.15%   |
| Xiaomi                          | 1         | 0.15%   |
| Tenda                           | 1         | 0.15%   |
| Sierra Wireless                 | 1         | 0.15%   |
| Qualcomm Technologies           | 1         | 0.15%   |
| BUFFALO                         | 1         | 0.15%   |
| Accton Technology               | 1         | 0.15%   |
| AboCom Systems                  | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 26        | 3.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 26        | 3.75%   |
| Intel Wireless 7265                                            | 26        | 3.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 24        | 3.46%   |
| Ralink MT7601U Wireless Adapter                                | 22        | 3.17%   |
| Intel Wireless 8265 / 8275                                     | 22        | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 20        | 2.88%   |
| Intel Wireless 8260                                            | 20        | 2.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 19        | 2.74%   |
| Intel Wireless 7260                                            | 18        | 2.59%   |
| Intel Wi-Fi 6 AX201                                            | 17        | 2.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 16        | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 2.31%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 15        | 2.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 2.16%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 2.02%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 13        | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 1.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 11        | 1.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10        | 1.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 9         | 1.3%    |
| Intel Wi-Fi 6 AX200                                            | 8         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 1.15%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 8         | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 1.15%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 7         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 1.01%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 0.86%   |
| Ralink RT5370 Wireless Adapter                                 | 6         | 0.86%   |
| Intel Wireless 3160                                            | 6         | 0.86%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 0.86%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 6         | 0.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 5         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 417       | 55.31%  |
| Intel                                  | 142       | 18.83%  |
| Qualcomm Atheros                       | 56        | 7.43%   |
| Broadcom                               | 36        | 4.77%   |
| Xiaomi                                 | 19        | 2.52%   |
| Samsung Electronics                    | 15        | 1.99%   |
| Marvell Technology Group               | 13        | 1.72%   |
| Huawei Technologies                    | 8         | 1.06%   |
| VIA Technologies                       | 6         | 0.8%    |
| Nvidia                                 | 5         | 0.66%   |
| JMicron Technology                     | 3         | 0.4%    |
| HTC (High Tech Computer)               | 3         | 0.4%    |
| Hewlett-Packard                        | 3         | 0.4%    |
| Broadcom Limited                       | 3         | 0.4%    |
| Apple                                  | 3         | 0.4%    |
| Qualcomm                               | 2         | 0.27%   |
| Microsoft                              | 2         | 0.27%   |
| MediaTek                               | 2         | 0.27%   |
| ICS Advent                             | 2         | 0.27%   |
| D-Link System                          | 2         | 0.27%   |
| ASUSTek Computer                       | 2         | 0.27%   |
| ASIX Electronics                       | 2         | 0.27%   |
| TP-Link                                | 1         | 0.13%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.13%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.13%   |
| LG Electronics                         | 1         | 0.13%   |
| Lenovo                                 | 1         | 0.13%   |
| D-Link                                 | 1         | 0.13%   |
| Attansic Technology                    | 1         | 0.13%   |
| Aquantia                               | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 354       | 46.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 42        | 5.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 29        | 3.8%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 15        | 1.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 11        | 1.44%   |
| Intel Ethernet Connection I217-LM                                      | 11        | 1.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 10        | 1.31%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 8         | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 1.05%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 8         | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 0.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 7         | 0.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 7         | 0.92%   |
| Intel Ethernet Connection (2) I219-V                                   | 7         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.79%   |
| Huawei FOA-LX9                                                         | 6         | 0.79%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 5         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 5         | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 5         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                  | 5         | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 5         | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 4         | 0.52%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.52%   |
| Intel Ethernet Connection (2) I218-V                                   | 4         | 0.52%   |
| Intel Ethernet Connection (14) I219-V                                  | 4         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 3         | 0.39%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 3         | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 3         | 0.39%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 0.39%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.39%   |
| Intel Ethernet Controller I225-V                                       | 3         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 689       | 50.29%  |
| WiFi     | 667       | 48.69%  |
| Modem    | 11        | 0.8%    |
| Unknown  | 3         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 553       | 71.45%  |
| Ethernet | 220       | 28.42%  |
| Unknown  | 1         | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 496       | 62.31%  |
| 1     | 284       | 35.68%  |
| 0     | 7         | 0.88%   |
| 3     | 5         | 0.63%   |
| 4     | 3         | 0.38%   |
| 8     | 1         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 740       | 91.81%  |
| Yes  | 66        | 8.19%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 205       | 39.81%  |
| IMC Networks                    | 73        | 14.17%  |
| Realtek Semiconductor           | 46        | 8.93%   |
| Qualcomm Atheros Communications | 38        | 7.38%   |
| Foxconn / Hon Hai               | 25        | 4.85%   |
| Broadcom                        | 24        | 4.66%   |
| Cambridge Silicon Radio         | 21        | 4.08%   |
| Lite-On Technology              | 18        | 3.5%    |
| Ralink                          | 11        | 2.14%   |
| Dell                            | 11        | 2.14%   |
| ASUSTek Computer                | 10        | 1.94%   |
| Apple                           | 8         | 1.55%   |
| Foxconn International           | 7         | 1.36%   |
| Ralink Technology               | 3         | 0.58%   |
| Hewlett-Packard                 | 3         | 0.58%   |
| Realtek                         | 2         | 0.39%   |
| Marvell Semiconductor           | 2         | 0.39%   |
| Askey Computer                  | 2         | 0.39%   |
| Alps Electric                   | 2         | 0.39%   |
| SiW                             | 1         | 0.19%   |
| Micro Star International        | 1         | 0.19%   |
| MediaTek                        | 1         | 0.19%   |
| Integrated System Solution      | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 100       | 19.42%  |
| Intel AX201 Bluetooth                                                               | 45        | 8.74%   |
| IMC Networks Bluetooth Radio                                                        | 28        | 5.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 24        | 4.66%   |
| Realtek Bluetooth Radio                                                             | 23        | 4.47%   |
| IMC Networks Wireless_Device                                                        | 21        | 4.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 21        | 4.08%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 18        | 3.5%    |
| Ralink RT3290 Bluetooth                                                             | 11        | 2.14%   |
| IMC Networks Bluetooth Device                                                       | 11        | 2.14%   |
| Intel AX211 Bluetooth                                                               | 9         | 1.75%   |
| Realtek 802.11ac WLAN Adapter                                                       | 8         | 1.55%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 8         | 1.55%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 8         | 1.55%   |
| Intel AX200 Bluetooth                                                               | 8         | 1.55%   |
| Realtek RTL8723B Bluetooth                                                          | 7         | 1.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 1.36%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 7         | 1.36%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 7         | 1.36%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 7         | 1.36%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 6         | 1.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 6         | 1.17%   |
| Realtek RTL8821A Bluetooth                                                          | 5         | 0.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 0.97%   |
| Lite-On Bluetooth Device                                                            | 5         | 0.97%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.78%   |
| Dell Wireless 360 Bluetooth                                                         | 4         | 0.78%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 0.78%   |
| Broadcom BCM20702A0                                                                 | 4         | 0.78%   |
| Apple Bluetooth Host Controller                                                     | 4         | 0.78%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 3         | 0.58%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 3         | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.58%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.58%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 3         | 0.58%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 3         | 0.58%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 3         | 0.58%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 0.58%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 0.58%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 681       | 65.29%  |
| Nvidia                           | 182       | 17.45%  |
| AMD                              | 140       | 13.42%  |
| C-Media Electronics              | 10        | 0.96%   |
| ASUSTek Computer                 | 6         | 0.58%   |
| Generalplus Technology           | 5         | 0.48%   |
| Silicon Integrated Systems [SiS] | 2         | 0.19%   |
| Jieli Technology                 | 2         | 0.19%   |
| Focusrite-Novation               | 2         | 0.19%   |
| Creative Labs                    | 2         | 0.19%   |
| Yamaha                           | 1         | 0.1%    |
| VIA Technologies                 | 1         | 0.1%    |
| ULi Electronics                  | 1         | 0.1%    |
| TEAC                             | 1         | 0.1%    |
| Realtek Semiconductor            | 1         | 0.1%    |
| Native Instruments               | 1         | 0.1%    |
| Micro Star International         | 1         | 0.1%    |
| ESS Technology                   | 1         | 0.1%    |
| CMX Systems                      | 1         | 0.1%    |
| Audio-Technica                   | 1         | 0.1%    |
| Apple                            | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 89        | 7.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 71        | 5.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 58        | 4.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 54        | 4.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 43        | 3.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 41        | 3.38%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 39        | 3.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 33        | 2.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 31        | 2.55%   |
| Intel Haswell-ULT HD Audio Controller                                      | 29        | 2.39%   |
| Intel 8 Series HD Audio Controller                                         | 29        | 2.39%   |
| Intel Broadwell-U Audio Controller                                         | 28        | 2.31%   |
| Nvidia GF108 High Definition Audio Controller                              | 27        | 2.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 27        | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 26        | 2.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 22        | 1.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 20        | 1.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 20        | 1.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 19        | 1.57%   |
| Nvidia GA107 High Definition Audio Controller                              | 18        | 1.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 18        | 1.48%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 1.4%    |
| Nvidia High Definition Audio Controller                                    | 16        | 1.32%   |
| Intel CM238 HD Audio Controller                                            | 16        | 1.32%   |
| AMD Kabini HDMI/DP Audio                                                   | 15        | 1.24%   |
| AMD FCH Azalia Controller                                                  | 15        | 1.24%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 12        | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 0.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 11        | 0.91%   |
| Intel 200 Series PCH HD Audio                                              | 11        | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11        | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 10        | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 10        | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 10        | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9         | 0.74%   |
| Nvidia GF119 HDMI Audio Controller                                         | 9         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 9         | 0.74%   |
| Intel Alder Lake-S HD Audio Controller                                     | 9         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 139       | 28.31%  |
| SK hynix            | 93        | 18.94%  |
| Micron Technology   | 63        | 12.83%  |
| Crucial             | 39        | 7.94%   |
| Kingston            | 37        | 7.54%   |
| Unknown             | 34        | 6.92%   |
| Ramaxel Technology  | 17        | 3.46%   |
| Elpida              | 14        | 2.85%   |
| Corsair             | 9         | 1.83%   |
| A-DATA Technology   | 8         | 1.63%   |
| G.Skill             | 7         | 1.43%   |
| GeIL                | 6         | 1.22%   |
| Apacer              | 6         | 1.22%   |
| Kingmax             | 4         | 0.81%   |
| Nanya Technology    | 3         | 0.61%   |
| Unknown             | 3         | 0.61%   |
| Ramos Technology    | 2         | 0.41%   |
| Unknown (8A02)      | 1         | 0.2%    |
| TwinMOS             | 1         | 0.2%    |
| Transcend           | 1         | 0.2%    |
| Team                | 1         | 0.2%    |
| Silicon Power       | 1         | 0.2%    |
| Neo Forza           | 1         | 0.2%    |
| ASint Technology    | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 8         | 1.52%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 8         | 1.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 8         | 1.52%   |
| Crucial RAM CB16GS2666.C8ET 16GB SODIMM DDR4 2667MT/s        | 8         | 1.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 7         | 1.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 7         | 1.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 7         | 1.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 6         | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 6         | 1.14%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 6         | 1.14%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 6         | 1.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 6         | 1.14%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 6         | 1.14%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 5         | 0.95%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 5         | 0.95%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 5         | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 4         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 0.76%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 0.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 0.76%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 4         | 0.76%   |
| GeIL RAM CL17-17-17 D4-2400 8GB DIMM DDR4 2400MT/s           | 4         | 0.76%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 3         | 0.57%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 3         | 0.57%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 3         | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s     | 3         | 0.57%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 3         | 0.57%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 3         | 0.57%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s | 3         | 0.57%   |
| Ramaxel RAM RMT3170MK58F8F1600 2GB SODIMM DDR3 1600MT/s      | 3         | 0.57%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 3         | 0.57%   |
| Unknown                                                      | 3         | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 2         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 2         | 0.38%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 2         | 0.38%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 2         | 0.38%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 2         | 0.38%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 2         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 180       | 45.45%  |
| DDR3    | 149       | 37.63%  |
| DDR5    | 15        | 3.79%   |
| DDR2    | 13        | 3.28%   |
| Unknown | 10        | 2.53%   |
| SDRAM   | 8         | 2.02%   |
| LPDDR5  | 8         | 2.02%   |
| LPDDR3  | 7         | 1.77%   |
| LPDDR4  | 5         | 1.26%   |
| DDR     | 1         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 272       | 69.04%  |
| DIMM         | 93        | 23.6%   |
| Row Of Chips | 26        | 6.6%    |
| Chip         | 2         | 0.51%   |
| RIMM         | 1         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 172       | 38.05%  |
| 4096  | 141       | 31.19%  |
| 16384 | 65        | 14.38%  |
| 2048  | 55        | 12.17%  |
| 1024  | 11        | 2.43%   |
| 32768 | 7         | 1.55%   |
| 65536 | 1         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 103       | 23.46%  |
| 2667    | 74        | 16.86%  |
| 3200    | 58        | 13.21%  |
| 2400    | 34        | 7.74%   |
| 1334    | 26        | 5.92%   |
| 2133    | 24        | 5.47%   |
| 1333    | 24        | 5.47%   |
| 4800    | 12        | 2.73%   |
| Unknown | 9         | 2.05%   |
| 3266    | 8         | 1.82%   |
| 6400    | 7         | 1.59%   |
| 667     | 7         | 1.59%   |
| 1867    | 6         | 1.37%   |
| 800     | 6         | 1.37%   |
| 4199    | 5         | 1.14%   |
| 8400    | 3         | 0.68%   |
| 5600    | 3         | 0.68%   |
| 1067    | 3         | 0.68%   |
| 4266    | 2         | 0.46%   |
| 3466    | 2         | 0.46%   |
| 3400    | 2         | 0.46%   |
| 3000    | 2         | 0.46%   |
| 2666    | 2         | 0.46%   |
| 533     | 2         | 0.46%   |
| 8533    | 1         | 0.23%   |
| 4267    | 1         | 0.23%   |
| 3733    | 1         | 0.23%   |
| 3600    | 1         | 0.23%   |
| 3066    | 1         | 0.23%   |
| 2933    | 1         | 0.23%   |
| 2800    | 1         | 0.23%   |
| 2048    | 1         | 0.23%   |
| 1866    | 1         | 0.23%   |
| 1800    | 1         | 0.23%   |
| 1400    | 1         | 0.23%   |
| 1328    | 1         | 0.23%   |
| 1066    | 1         | 0.23%   |
| 975     | 1         | 0.23%   |
| 400     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 50%     |
| Canon               | 3         | 37.5%   |
| Samsung Electronics | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP LaserJet 1018                     | 2         | 25%     |
| Samsung ML-1640 Series Laser Printer | 1         | 12.5%   |
| HP LaserJet P1102                    | 1         | 12.5%   |
| HP DeskJet 2130 series               | 1         | 12.5%   |
| Canon PIXMA MG5600 Series            | 1         | 12.5%   |
| Canon LBP6300                        | 1         | 12.5%   |
| Canon iR2004/2204 UFRII LT           | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan LiDE 120            | 1         | 33.33%  |
| Canon CanoScan 4400F               | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 121       | 22.08%  |
| IMC Networks                           | 108       | 19.71%  |
| Realtek Semiconductor                  | 37        | 6.75%   |
| Microdia                               | 37        | 6.75%   |
| Bison Electronics                      | 31        | 5.66%   |
| Syntek                                 | 27        | 4.93%   |
| Sunplus Innovation Technology          | 22        | 4.01%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 3.65%   |
| Apple                                  | 19        | 3.47%   |
| Sonix Technology                       | 18        | 3.28%   |
| Acer                                   | 15        | 2.74%   |
| Quanta                                 | 14        | 2.55%   |
| Lite-On Technology                     | 14        | 2.55%   |
| Suyin                                  | 10        | 1.82%   |
| Samsung Electronics                    | 10        | 1.82%   |
| Ricoh                                  | 8         | 1.46%   |
| Luxvisions Innotech Limited            | 6         | 1.09%   |
| Alcor Micro                            | 4         | 0.73%   |
| Pixart Imaging                         | 3         | 0.55%   |
| Logitech                               | 3         | 0.55%   |
| Lenovo                                 | 3         | 0.55%   |
| ALi                                    | 3         | 0.55%   |
| Silicon Motion                         | 2         | 0.36%   |
| MacroSilicon                           | 2         | 0.36%   |
| Importek                               | 2         | 0.36%   |
| Sunplus Technology                     | 1         | 0.18%   |
| Primax Electronics                     | 1         | 0.18%   |
| OmniVision Technologies                | 1         | 0.18%   |
| LG Electronics                         | 1         | 0.18%   |
| KYE Systems (Mouse Systems)            | 1         | 0.18%   |
| Goertek Electronics                    | 1         | 0.18%   |
| Generalplus Technology                 | 1         | 0.18%   |
| BillionPixels                          | 1         | 0.18%   |
| 2M UVC CAMERA                          | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 34        | 6.2%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 27        | 4.93%   |
| Chicony Integrated Camera                           | 20        | 3.65%   |
| IMC Networks Integrated Camera                      | 18        | 3.28%   |
| Sonix USB2.0 HD UVC WebCam                          | 13        | 2.37%   |
| Chicony USB2.0 HD UVC WebCam                        | 12        | 2.19%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 12        | 2.19%   |
| IMC Networks Lenovo EasyCamera                      | 11        | 2.01%   |
| Samsung Galaxy series, misc. (MTP mode)             | 10        | 1.82%   |
| Syntek EasyCamera                                   | 9         | 1.64%   |
| Chicony EasyCamera                                  | 9         | 1.64%   |
| Syntek Lenovo EasyCamera                            | 8         | 1.46%   |
| Syntek Integrated Camera                            | 8         | 1.46%   |
| Lite-On Integrated Camera                           | 8         | 1.46%   |
| Chicony HP HD Camera                                | 8         | 1.46%   |
| Chicony HD WebCam                                   | 8         | 1.46%   |
| Acer Lenovo EasyCamera                              | 8         | 1.46%   |
| Realtek USB2.0 VGA UVC WebCam                       | 7         | 1.28%   |
| Realtek USB Camera                                  | 7         | 1.28%   |
| Microdia Laptop_Integrated_Webcam_HD                | 7         | 1.28%   |
| Sunplus HD WebCam                                   | 6         | 1.09%   |
| Chicony HP HD Webcam                                | 6         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 6         | 1.09%   |
| Bison Lenovo EasyCamera                             | 6         | 1.09%   |
| Bison Integrated Camera                             | 6         | 1.09%   |
| Sunplus Asus Webcam                                 | 5         | 0.91%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 0.91%   |
| Microdia Sonix Integrated Webcam                    | 5         | 0.91%   |
| Microdia Integrated_Webcam_HD                       | 5         | 0.91%   |
| Lite-On HP HD Camera                                | 5         | 0.91%   |
| Chicony Lenovo EasyCamera                           | 5         | 0.91%   |
| Chicony Integrated HP HD Webcam                     | 5         | 0.91%   |
| Chicony HP HD Webcam [Fixed]                        | 5         | 0.91%   |
| Bison SunplusIT Integrated Camera                   | 5         | 0.91%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 0.73%   |
| Sonix USB2.0 FHD UVC WebCam                         | 4         | 0.73%   |
| Realtek Integrated_Webcam_HD                        | 4         | 0.73%   |
| Microdia Integrated Webcam                          | 4         | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam                       | 4         | 0.73%   |
| Bison HD Webcam                                     | 4         | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 56        | 44.09%  |
| Shenzhen Goodix Technology         | 18        | 14.17%  |
| Synaptics                          | 13        | 10.24%  |
| Elan Microelectronics              | 13        | 10.24%  |
| Upek                               | 12        | 9.45%   |
| AuthenTec                          | 6         | 4.72%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.36%   |
| LighTuning Technology              | 3         | 2.36%   |
| STMicroelectronics                 | 2         | 1.57%   |
| Suprema                            | 1         | 0.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 18.9%   |
| Shenzhen Goodix  FingerPrint Device                                        | 14        | 11.02%  |
| Validity Sensors VFS491                                                    | 12        | 9.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 8.66%   |
| Elan ELAN:Fingerprint                                                      | 10        | 7.87%   |
| Synaptics  WBDI                                                            | 6         | 4.72%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 3.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 3.15%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.36%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 2.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.57%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 1.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.57%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.57%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 1.57%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 1.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.79%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.79%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.79%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.79%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.79%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.79%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.79%   |
| Synaptics UWP WBDI                                                         | 1         | 0.79%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader                           | 1         | 0.79%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.79%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.79%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.79%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.79%   |
| AuthenTec AES2810                                                          | 1         | 0.79%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.79%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 10        | 47.62%  |
| Alcor Micro           | 6         | 28.57%  |
| Upek                  | 2         | 9.52%   |
| O2 Micro              | 2         | 9.52%   |
| Gemalto (was Gemplus) | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 28.57%  |
| Broadcom 5880                                                                | 4         | 19.05%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 9.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.76%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.76%   |
| Broadcom 58200                                                               | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 512       | 62.98%  |
| 1     | 233       | 28.66%  |
| 2     | 51        | 6.27%   |
| 3     | 13        | 1.6%    |
| 4     | 2         | 0.25%   |
| 8     | 1         | 0.12%   |
| 5     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 127       | 33.69%  |
| Graphics card            | 114       | 30.24%  |
| Net/wireless             | 32        | 8.49%   |
| Communication controller | 22        | 5.84%   |
| Bluetooth                | 18        | 4.77%   |
| Chipcard                 | 17        | 4.51%   |
| Multimedia controller    | 11        | 2.92%   |
| Camera                   | 10        | 2.65%   |
| Unassigned class         | 9         | 2.39%   |
| Storage                  | 6         | 1.59%   |
| Sound                    | 3         | 0.8%    |
| Network                  | 2         | 0.53%   |
| Net/ethernet             | 2         | 0.53%   |
| Card reader              | 2         | 0.53%   |
| Wireless                 | 1         | 0.27%   |
| Storage/raid             | 1         | 0.27%   |

