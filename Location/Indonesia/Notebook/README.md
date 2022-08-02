Linux in Indonesia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

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

Total: 862

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X230 23245NJ       | [3c85e43b86](https://linux-hardware.org/?probe=3c85e43b86) | Aug 01, 2022 |
| HP            | 240 G8 Notebook PC          | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [3a496f366f](https://linux-hardware.org/?probe=3a496f366f) | Aug 01, 2022 |
| Acer          | Z476                        | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Dell          | Latitude E7250              | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Sony          | VPCEA36FG                   | [6c742b6234](https://linux-hardware.org/?probe=6c742b6234) | Jul 30, 2022 |
| ASUSTek       | K43E                        | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| ASUSTek       | X455LF                      | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Acer          | Aspire 4732Z                | [3d23b4bbdc](https://linux-hardware.org/?probe=3d23b4bbdc) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [2773e9510b](https://linux-hardware.org/?probe=2773e9510b) | Jul 27, 2022 |
| Dell          | G3 3579                     | [96fab186c3](https://linux-hardware.org/?probe=96fab186c3) | Jul 24, 2022 |
| ASUSTek       | N56VZ                       | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [a6e3ee128e](https://linux-hardware.org/?probe=a6e3ee128e) | Jul 20, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [944ba71eef](https://linux-hardware.org/?probe=944ba71eef) | Jul 19, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [df94c841af](https://linux-hardware.org/?probe=df94c841af) | Jul 17, 2022 |
| Lenovo        | V310-14ISK 80SX             | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Acer          | Aspire E5-475G              | [1f7429b29d](https://linux-hardware.org/?probe=1f7429b29d) | Jul 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [54c99c7f2f](https://linux-hardware.org/?probe=54c99c7f2f) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [cf41c08ea5](https://linux-hardware.org/?probe=cf41c08ea5) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d651eb1f7d](https://linux-hardware.org/?probe=d651eb1f7d) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b04b2741a0](https://linux-hardware.org/?probe=b04b2741a0) | Jul 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b00361cdbd](https://linux-hardware.org/?probe=b00361cdbd) | Jul 13, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [cde5f69fef](https://linux-hardware.org/?probe=cde5f69fef) | Jul 13, 2022 |
| HP            | Pavilion g4                 | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Dell          | Latitude E6440              | [495237a0b0](https://linux-hardware.org/?probe=495237a0b0) | Jul 09, 2022 |
| Toshiba       | Satellite C640              | [cd8f69d739](https://linux-hardware.org/?probe=cd8f69d739) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Laptop 14s-cf2xxx           | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Lenovo        | ThinkPad L412 0585E86       | [ad82717c98](https://linux-hardware.org/?probe=ad82717c98) | Jul 01, 2022 |
| Acer          | Aspire 4732Z                | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | [97d88d7e00](https://linux-hardware.org/?probe=97d88d7e00) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | [3cec3cffbb](https://linux-hardware.org/?probe=3cec3cffbb) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | [bac4b49e55](https://linux-hardware.org/?probe=bac4b49e55) | Jun 30, 2022 |
| Acer          | Aspire A314-35              | [dfdd48254c](https://linux-hardware.org/?probe=dfdd48254c) | Jun 29, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| HP            | Pavilion g4                 | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Fujitsu       | FMVS02003                   | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Precision M4500             | [e41b9f3386](https://linux-hardware.org/?probe=e41b9f3386) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Aspire A315-41              | [00a254b4ff](https://linux-hardware.org/?probe=00a254b4ff) | Jun 21, 2022 |
| Acer          | Aspire A315-41              | [4ca3721cbb](https://linux-hardware.org/?probe=4ca3721cbb) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | [4d5fb8a789](https://linux-hardware.org/?probe=4d5fb8a789) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | [9f7b97f22f](https://linux-hardware.org/?probe=9f7b97f22f) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| AXIOO         | Mybook 14E                  | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Dell          | Inspiron 3442               | [b71d801e61](https://linux-hardware.org/?probe=b71d801e61) | Jun 18, 2022 |
| ASUSTek       | K46CB                       | [a6cc4351be](https://linux-hardware.org/?probe=a6cc4351be) | Jun 17, 2022 |
| ASUSTek       | K46CB                       | [fe4f649d9b](https://linux-hardware.org/?probe=fe4f649d9b) | Jun 17, 2022 |
| HP            | Laptop 14s-fq0xxx           | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| Acer          | AO756                       | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Acer          | Aspire A514-54G             | [a74cd897c5](https://linux-hardware.org/?probe=a74cd897c5) | Jun 09, 2022 |
| MSI           | Prestige 14 A11SC           | [ea39fa65a1](https://linux-hardware.org/?probe=ea39fa65a1) | Jun 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [bdb3bbe37f](https://linux-hardware.org/?probe=bdb3bbe37f) | Jun 07, 2022 |
| Lenovo        | Z41-70 80K5                 | [3419d2fd18](https://linux-hardware.org/?probe=3419d2fd18) | Jun 06, 2022 |
| HP            | Pavilion 15                 | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| Acer          | Aspire A514-54G             | [1019de0d68](https://linux-hardware.org/?probe=1019de0d68) | Jun 01, 2022 |
| ASUSTek       | N550JV                      | [2652284f1a](https://linux-hardware.org/?probe=2652284f1a) | May 31, 2022 |
| Acer          | Aspire 4720Z                | [a1dd5003f5](https://linux-hardware.org/?probe=a1dd5003f5) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | GL502VMK                    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| Lenovo        | G400 20235                  | [351b94ec15](https://linux-hardware.org/?probe=351b94ec15) | May 25, 2022 |
| HP            | 1000                        | [e83bc1e8fe](https://linux-hardware.org/?probe=e83bc1e8fe) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| ASUSTek       | K43U                        | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| MSI           | Modern 14 B11MO             | [c3b01c8c1b](https://linux-hardware.org/?probe=c3b01c8c1b) | May 20, 2022 |
| ASUSTek       | K43U                        | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [843a31b222](https://linux-hardware.org/?probe=843a31b222) | May 17, 2022 |
| Apple         | MacBookPro9,2               | [cfba770336](https://linux-hardware.org/?probe=cfba770336) | May 17, 2022 |
| Apple         | MacBookPro9,2               | [c19acfde6f](https://linux-hardware.org/?probe=c19acfde6f) | May 17, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [e633129a51](https://linux-hardware.org/?probe=e633129a51) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| MSI           | Modern 14 B5M               | [b207ce7566](https://linux-hardware.org/?probe=b207ce7566) | May 12, 2022 |
| Acer          | Aspire E5-476G              | [98b0999339](https://linux-hardware.org/?probe=98b0999339) | May 12, 2022 |
| Acer          | Aspire E5-476G              | [c4e0e740bb](https://linux-hardware.org/?probe=c4e0e740bb) | May 12, 2022 |
| Acer          | V1.24                       | [186531d4d8](https://linux-hardware.org/?probe=186531d4d8) | May 11, 2022 |
| Sony          | SVS13137PGB                 | [6dd2b49c52](https://linux-hardware.org/?probe=6dd2b49c52) | May 10, 2022 |
| Acer          | Nitro AN515-52              | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Acer          | Swift SF314-41              | [108b57a5a7](https://linux-hardware.org/?probe=108b57a5a7) | May 10, 2022 |
| Acer          | Aspire A514-54G             | [ec1fa8e360](https://linux-hardware.org/?probe=ec1fa8e360) | May 08, 2022 |
| Acer          | Aspire A514-54G             | [b4b52aad69](https://linux-hardware.org/?probe=b4b52aad69) | May 07, 2022 |
| Acer          | Aspire V5-431               | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [4dcc86a60e](https://linux-hardware.org/?probe=4dcc86a60e) | May 03, 2022 |
| MSI           | Modern 14 B5M               | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| ASUSTek       | X200MA                      | [f93f8fcb35](https://linux-hardware.org/?probe=f93f8fcb35) | Apr 28, 2022 |
| Dell          | Latitude E6510              | [10d60e00c2](https://linux-hardware.org/?probe=10d60e00c2) | Apr 27, 2022 |
| ASUSTek       | X455LD                      | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Gigabyte      | M912                        | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | X450LCP                     | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Gigabyte      | AERO 15XV8                  | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [345734b3fd](https://linux-hardware.org/?probe=345734b3fd) | Apr 07, 2022 |
| Acer          | Aspire 4720Z                | [eb44050489](https://linux-hardware.org/?probe=eb44050489) | Apr 07, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| ASUSTek       | X455YA                      | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Acer          | Aspire 4720Z                | [c3651e4d3d](https://linux-hardware.org/?probe=c3651e4d3d) | Apr 01, 2022 |
| Dell          | Latitude E6230              | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| HP            | Pavilion 14                 | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Infinix       | INBook X1                   | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| MSI           | GF63 Thin 9SCXR             | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Dell          | Latitude E7240              | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| Sony          | VPCSB35FG                   | [79d0465072](https://linux-hardware.org/?probe=79d0465072) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | [1b7f98b34d](https://linux-hardware.org/?probe=1b7f98b34d) | Mar 23, 2022 |
| ASUSTek       | X456UQK                     | [863693cc0a](https://linux-hardware.org/?probe=863693cc0a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [f0047d02ea](https://linux-hardware.org/?probe=f0047d02ea) | Mar 22, 2022 |
| Dell          | Inspiron 13-5368            | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| Clevo         | W240HU/W250HUQ              | [222cbe9b4e](https://linux-hardware.org/?probe=222cbe9b4e) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| ASUSTek       | X441NA                      | [b7cf53ebcc](https://linux-hardware.org/?probe=b7cf53ebcc) | Mar 15, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | Notebook                    | [6ae78b432d](https://linux-hardware.org/?probe=6ae78b432d) | Mar 12, 2022 |
| Dell          | Latitude E7240              | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| ASUSTek       | GL553VD                     | [5e43e1dd7b](https://linux-hardware.org/?probe=5e43e1dd7b) | Mar 11, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [ed4db5233e](https://linux-hardware.org/?probe=ed4db5233e) | Mar 10, 2022 |
| ASUSTek       | X450EA                      | [a7394d72a0](https://linux-hardware.org/?probe=a7394d72a0) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| HP            | Pavilion g4                 | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| Sony          | VPCSB35FG                   | [b8a266ddc0](https://linux-hardware.org/?probe=b8a266ddc0) | Mar 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| Toshiba       | PORTEGE R835                | [67e8021c81](https://linux-hardware.org/?probe=67e8021c81) | Mar 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e7d5945f3d](https://linux-hardware.org/?probe=e7d5945f3d) | Mar 05, 2022 |
| Lenovo        | G40-45 80E1                 | [28f40df81d](https://linux-hardware.org/?probe=28f40df81d) | Mar 04, 2022 |
| ASUSTek       | UL20A                       | [c4efddb6b4](https://linux-hardware.org/?probe=c4efddb6b4) | Mar 02, 2022 |
| Fujitsu       | Unknown                     | [bc81b988ce](https://linux-hardware.org/?probe=bc81b988ce) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [621999b245](https://linux-hardware.org/?probe=621999b245) | Feb 24, 2022 |
| Dell          | Vostro 5470                 | [5ba37db2b4](https://linux-hardware.org/?probe=5ba37db2b4) | Feb 23, 2022 |
| Dell          | Latitude E7240              | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Acer          | Aspire 4720Z                | [eba3609129](https://linux-hardware.org/?probe=eba3609129) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| Acer          | One Z1402                   | [8746e0e3e7](https://linux-hardware.org/?probe=8746e0e3e7) | Feb 18, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1582806778](https://linux-hardware.org/?probe=1582806778) | Feb 17, 2022 |
| ASUSTek       | X540LA                      | [b2efca795b](https://linux-hardware.org/?probe=b2efca795b) | Feb 17, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [e3dfc424ca](https://linux-hardware.org/?probe=e3dfc424ca) | Feb 16, 2022 |
| Fujitsu       | FMVNA1SE                    | [e2cd0bdcb5](https://linux-hardware.org/?probe=e2cd0bdcb5) | Feb 14, 2022 |
| Toshiba       | Satellite C840              | [cb53c43003](https://linux-hardware.org/?probe=cb53c43003) | Feb 13, 2022 |
| Lenovo        | IdeaPad S205 Brazos         | [402bdafb5f](https://linux-hardware.org/?probe=402bdafb5f) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [5d4b14e3e0](https://linux-hardware.org/?probe=5d4b14e3e0) | Feb 12, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [eea0ec2b64](https://linux-hardware.org/?probe=eea0ec2b64) | Feb 12, 2022 |
| Toshiba       | Satellite C800D             | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [54e246f496](https://linux-hardware.org/?probe=54e246f496) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [aa037a1c8c](https://linux-hardware.org/?probe=aa037a1c8c) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [0de3e1022e](https://linux-hardware.org/?probe=0de3e1022e) | Feb 09, 2022 |
| Acer          | Nitro AN515-54              | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [5e0e5de165](https://linux-hardware.org/?probe=5e0e5de165) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [aaceb070e8](https://linux-hardware.org/?probe=aaceb070e8) | Feb 07, 2022 |
| ASUSTek       | X455LD                      | [324512f303](https://linux-hardware.org/?probe=324512f303) | Feb 06, 2022 |
| Lenovo        | ThinkPad W520 427637U       | [f9eb52038d](https://linux-hardware.org/?probe=f9eb52038d) | Feb 01, 2022 |
| Dell          | Inspiron 5480               | [85796c8359](https://linux-hardware.org/?probe=85796c8359) | Jan 28, 2022 |
| Dell          | Inspiron 5480               | [59b6841322](https://linux-hardware.org/?probe=59b6841322) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [774625ff90](https://linux-hardware.org/?probe=774625ff90) | Jan 24, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [e7c5bda932](https://linux-hardware.org/?probe=e7c5bda932) | Jan 24, 2022 |
| ASUSTek       | X450CP                      | [3f431523c1](https://linux-hardware.org/?probe=3f431523c1) | Jan 22, 2022 |
| Acer          | Swift SF314-43              | [567c5725d5](https://linux-hardware.org/?probe=567c5725d5) | Jan 22, 2022 |
| Sony          | SVE14A15FGB                 | [c35af68d7b](https://linux-hardware.org/?probe=c35af68d7b) | Jan 21, 2022 |
| Acer          | Aspire E5-471               | [a7c6bed4e1](https://linux-hardware.org/?probe=a7c6bed4e1) | Jan 21, 2022 |
| Sony          | SVD13213SGW                 | [ee9e63ab7c](https://linux-hardware.org/?probe=ee9e63ab7c) | Jan 21, 2022 |
| Acer          | Nitro AN515-52              | [e4791d09ec](https://linux-hardware.org/?probe=e4791d09ec) | Jan 20, 2022 |
| Lenovo        | IdeaPad 305-14IBD 80R1      | [f963f78bc6](https://linux-hardware.org/?probe=f963f78bc6) | Jan 20, 2022 |
| MSI           | Modern 14 B5M               | [ae605d8a23](https://linux-hardware.org/?probe=ae605d8a23) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [c021e3bb40](https://linux-hardware.org/?probe=c021e3bb40) | Jan 18, 2022 |
| Acer          | Aspire E5-471               | [bf81e9a289](https://linux-hardware.org/?probe=bf81e9a289) | Jan 17, 2022 |
| Toshiba       | PORTEGE Z30-A               | [6df479c161](https://linux-hardware.org/?probe=6df479c161) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Lenovo        | G400s 20244                 | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Dell          | Vostro 5581                 | [45f89f3b39](https://linux-hardware.org/?probe=45f89f3b39) | Jan 13, 2022 |
| MSI           | Modern 14 B5M               | [4822adcbc3](https://linux-hardware.org/?probe=4822adcbc3) | Jan 09, 2022 |
| MSI           | GL65 9SC                    | [24c204f7cf](https://linux-hardware.org/?probe=24c204f7cf) | Jan 09, 2022 |
| Dell          | Latitude E7250              | [e586dba516](https://linux-hardware.org/?probe=e586dba516) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Dell          | Inspiron 5570               | [2268237364](https://linux-hardware.org/?probe=2268237364) | Jan 08, 2022 |
| MSI           | Modern 14 B5M               | [ea82b6b417](https://linux-hardware.org/?probe=ea82b6b417) | Jan 08, 2022 |
| ASUSTek       | N43SL                       | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | U310                        | [47b64f9b71](https://linux-hardware.org/?probe=47b64f9b71) | Jan 04, 2022 |
| ASUSTek       | TP300LD                     | [2048e4ff56](https://linux-hardware.org/?probe=2048e4ff56) | Jan 04, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [954bd9f15e](https://linux-hardware.org/?probe=954bd9f15e) | Jan 03, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [5a0df8b1d8](https://linux-hardware.org/?probe=5a0df8b1d8) | Jan 03, 2022 |
| Acer          | Aspire 4720Z                | [1928762a58](https://linux-hardware.org/?probe=1928762a58) | Jan 02, 2022 |
| Acer          | Aspire E5-471               | [ad8cdd464b](https://linux-hardware.org/?probe=ad8cdd464b) | Jan 01, 2022 |
| ASUSTek       | TP300LD                     | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [a9e50f6f42](https://linux-hardware.org/?probe=a9e50f6f42) | Dec 28, 2021 |
| Lenovo        | G40-45 80E1                 | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| HP            | Pavilion 14                 | [b212043e80](https://linux-hardware.org/?probe=b212043e80) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Fujitsu       | FMVNA7BEC                   | [5a7719cad2](https://linux-hardware.org/?probe=5a7719cad2) | Dec 23, 2021 |
| Acer          | Aspire E1-471G              | [93b181f3fd](https://linux-hardware.org/?probe=93b181f3fd) | Dec 21, 2021 |
| Dell          | Latitude E5400              | [ea58337ba8](https://linux-hardware.org/?probe=ea58337ba8) | Dec 20, 2021 |
| Toshiba       | Dakar10FW8                  | [937d3de436](https://linux-hardware.org/?probe=937d3de436) | Dec 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [f279fb7b6f](https://linux-hardware.org/?probe=f279fb7b6f) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [635ec3d5d2](https://linux-hardware.org/?probe=635ec3d5d2) | Dec 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ee7ae7b860](https://linux-hardware.org/?probe=ee7ae7b860) | Dec 06, 2021 |
| ASUSTek       | X200MA                      | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | 700T                        | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| ASUSTek       | X455LD                      | [8fcb88c027](https://linux-hardware.org/?probe=8fcb88c027) | Nov 30, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [8cffa892b2](https://linux-hardware.org/?probe=8cffa892b2) | Nov 26, 2021 |
| Acer          | Aspire 4732Z                | [7376dc0d58](https://linux-hardware.org/?probe=7376dc0d58) | Nov 25, 2021 |
| Acer          | Aspire 4732Z                | [d020b5f5c5](https://linux-hardware.org/?probe=d020b5f5c5) | Nov 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a87f01aa8a](https://linux-hardware.org/?probe=a87f01aa8a) | Nov 25, 2021 |
| Acer          | Swift SF514-53T             | [09cc50e9eb](https://linux-hardware.org/?probe=09cc50e9eb) | Nov 23, 2021 |
| ASUSTek       | X455LD                      | [34d8f7fdbb](https://linux-hardware.org/?probe=34d8f7fdbb) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| ASUSTek       | K45VD                       | [4a655e0c04](https://linux-hardware.org/?probe=4a655e0c04) | Nov 22, 2021 |
| Acer          | Swift SF514-53T             | [dbca729f8c](https://linux-hardware.org/?probe=dbca729f8c) | Nov 20, 2021 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | [34fb650910](https://linux-hardware.org/?probe=34fb650910) | Nov 16, 2021 |
| Dell          | Vostro 3400                 | [f6ba3e3359](https://linux-hardware.org/?probe=f6ba3e3359) | Nov 15, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Notebook      | P870DM                      | [7681edf3ee](https://linux-hardware.org/?probe=7681edf3ee) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | [fa2cb4cfff](https://linux-hardware.org/?probe=fa2cb4cfff) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | [53cf9a7e19](https://linux-hardware.org/?probe=53cf9a7e19) | Nov 12, 2021 |
| Acer          | Swift SF514-52T             | [020a93edbc](https://linux-hardware.org/?probe=020a93edbc) | Nov 10, 2021 |
| MSI           | GL62M 7RDX                  | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| ASUSTek       | X550ZE                      | [b27a794243](https://linux-hardware.org/?probe=b27a794243) | Nov 09, 2021 |
| HP            | Notebook                    | [9334c94844](https://linux-hardware.org/?probe=9334c94844) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [fe34c12d67](https://linux-hardware.org/?probe=fe34c12d67) | Nov 03, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a0bd3fa08](https://linux-hardware.org/?probe=3a0bd3fa08) | Nov 01, 2021 |
| Acer          | Swift SF314-43              | [4881a9a93c](https://linux-hardware.org/?probe=4881a9a93c) | Oct 31, 2021 |
| Lenovo        | G40-45 80E1                 | [0cdc6e9d84](https://linux-hardware.org/?probe=0cdc6e9d84) | Oct 28, 2021 |
| Dell          | Latitude E6440              | [00e8b6e3fd](https://linux-hardware.org/?probe=00e8b6e3fd) | Oct 24, 2021 |
| MSI           | Bravo 15 B5DD               | [afa573d049](https://linux-hardware.org/?probe=afa573d049) | Oct 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [78738c3586](https://linux-hardware.org/?probe=78738c3586) | Oct 22, 2021 |
| Dell          | G7 7588                     | [af1479f2fe](https://linux-hardware.org/?probe=af1479f2fe) | Oct 20, 2021 |
| Dell          | G7 7588                     | [0464fb8af6](https://linux-hardware.org/?probe=0464fb8af6) | Oct 20, 2021 |
| Dell          | Inspiron 1440               | [9e9967a3fa](https://linux-hardware.org/?probe=9e9967a3fa) | Oct 17, 2021 |
| Acer          | Aspire 4738Z                | [8962990035](https://linux-hardware.org/?probe=8962990035) | Oct 16, 2021 |
| ASUSTek       | U36SD                       | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| ASUSTek       | 1215B                       | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| ASUSTek       | K43SV                       | [6c0858f414](https://linux-hardware.org/?probe=6c0858f414) | Oct 08, 2021 |
| ASUSTek       | K43SV                       | [cff7419d9e](https://linux-hardware.org/?probe=cff7419d9e) | Oct 08, 2021 |
| HP            | Pavilion 14                 | [0c0ee7fe52](https://linux-hardware.org/?probe=0c0ee7fe52) | Oct 05, 2021 |
| Acer          | Aspire 4750                 | [b00fc610cd](https://linux-hardware.org/?probe=b00fc610cd) | Oct 05, 2021 |
| HP            | Laptop 14-bw0xx             | [5856720999](https://linux-hardware.org/?probe=5856720999) | Oct 04, 2021 |
| ASUSTek       | X441BA                      | [ae6206875f](https://linux-hardware.org/?probe=ae6206875f) | Oct 03, 2021 |
| ASUSTek       | X441BA                      | [692a1a1a57](https://linux-hardware.org/?probe=692a1a1a57) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | Laptop 14s-cf3xxx           | [1c4d130d6a](https://linux-hardware.org/?probe=1c4d130d6a) | Oct 01, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [2b03e34e82](https://linux-hardware.org/?probe=2b03e34e82) | Sep 30, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| HP            | EliteBook 2560p             | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Acer          | Swift SFX14-41G             | [cb763824f9](https://linux-hardware.org/?probe=cb763824f9) | Sep 25, 2021 |
| Acer          | Aspire 4752                 | [c68b87dd56](https://linux-hardware.org/?probe=c68b87dd56) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| Lenovo        | ThinkBook 14s-IML 20RS      | [f93df3c890](https://linux-hardware.org/?probe=f93df3c890) | Sep 19, 2021 |
| Acer          | Aspire 4752                 | [c5758f5a05](https://linux-hardware.org/?probe=c5758f5a05) | Sep 18, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [8ff619f5f3](https://linux-hardware.org/?probe=8ff619f5f3) | Sep 17, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [57dc237470](https://linux-hardware.org/?probe=57dc237470) | Sep 17, 2021 |
| Acer          | Swift SF314-43              | [e5804af7f6](https://linux-hardware.org/?probe=e5804af7f6) | Sep 14, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [e84546c757](https://linux-hardware.org/?probe=e84546c757) | Sep 14, 2021 |
| Acer          | Aspire 4752                 | [2cc8dabf64](https://linux-hardware.org/?probe=2cc8dabf64) | Sep 11, 2021 |
| HP            | Compaq Presario CQ40        | [62284df376](https://linux-hardware.org/?probe=62284df376) | Sep 10, 2021 |
| HP            | Laptop 14s-cf3xxx           | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| Dell          | XPS 15 7590                 | [82904dfc03](https://linux-hardware.org/?probe=82904dfc03) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Acer          | Aspire 4750                 | [f88ba2a8ea](https://linux-hardware.org/?probe=f88ba2a8ea) | Sep 04, 2021 |
| HP            | 14                          | [9f574ea069](https://linux-hardware.org/?probe=9f574ea069) | Sep 04, 2021 |
| Acer          | Aspire V3-371               | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [0bfcbeeab5](https://linux-hardware.org/?probe=0bfcbeeab5) | Sep 02, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [808ff28683](https://linux-hardware.org/?probe=808ff28683) | Aug 31, 2021 |
| ASUSTek       | GL553VD                     | [d6a7f7807d](https://linux-hardware.org/?probe=d6a7f7807d) | Aug 26, 2021 |
| Acer          | Aspire A315-42              | [6e6129ddbe](https://linux-hardware.org/?probe=6e6129ddbe) | Aug 26, 2021 |
| HP            | ProBook 4430s               | [e764612d91](https://linux-hardware.org/?probe=e764612d91) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [49aac2eefe](https://linux-hardware.org/?probe=49aac2eefe) | Aug 24, 2021 |
| Acer          | Aspire V3-371               | [d34df8e36e](https://linux-hardware.org/?probe=d34df8e36e) | Aug 23, 2021 |
| Acer          | Aspire 4750                 | [6f5d61dc20](https://linux-hardware.org/?probe=6f5d61dc20) | Aug 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [b57e843f46](https://linux-hardware.org/?probe=b57e843f46) | Aug 22, 2021 |
| Acer          | Swift SF314-41              | [34d2f87751](https://linux-hardware.org/?probe=34d2f87751) | Aug 18, 2021 |
| Fujitsu       | FMVNA6HG                    | [3af7eec32c](https://linux-hardware.org/?probe=3af7eec32c) | Aug 16, 2021 |
| Toshiba       | Satellite R630              | [b2b7f07b7a](https://linux-hardware.org/?probe=b2b7f07b7a) | Aug 12, 2021 |
| HP            | ENVY Notebook               | [f2dea0236d](https://linux-hardware.org/?probe=f2dea0236d) | Aug 11, 2021 |
| HP            | ENVY Notebook               | [ce3be0798b](https://linux-hardware.org/?probe=ce3be0798b) | Aug 11, 2021 |
| Toshiba       | Satellite M100              | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | [3d8ebc06f6](https://linux-hardware.org/?probe=3d8ebc06f6) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | [bb3eb06270](https://linux-hardware.org/?probe=bb3eb06270) | Aug 09, 2021 |
| Acer          | Nitro AN515-56              | [867c7e2bb4](https://linux-hardware.org/?probe=867c7e2bb4) | Aug 09, 2021 |
| Lenovo        | G40-45 80E1                 | [a9947e6264](https://linux-hardware.org/?probe=a9947e6264) | Aug 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6d691b88f0](https://linux-hardware.org/?probe=6d691b88f0) | Aug 08, 2021 |
| Acer          | Aspire 4752                 | [16f9fcdeed](https://linux-hardware.org/?probe=16f9fcdeed) | Aug 08, 2021 |
| Acer          | Swift SF314-41              | [4f141cc864](https://linux-hardware.org/?probe=4f141cc864) | Aug 07, 2021 |
| Acer          | Swift SF314-41              | [31e6bda7a8](https://linux-hardware.org/?probe=31e6bda7a8) | Aug 07, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Lenovo        | G40-45 80E1                 | [346da0d23a](https://linux-hardware.org/?probe=346da0d23a) | Aug 06, 2021 |
| ASUSTek       | X455YA                      | [7ceff8b834](https://linux-hardware.org/?probe=7ceff8b834) | Aug 05, 2021 |
| HP            | Laptop 15s-fq2xxx           | [506b637bd3](https://linux-hardware.org/?probe=506b637bd3) | Aug 05, 2021 |
| Lenovo        | G40-45 80E1                 | [26d0a4788c](https://linux-hardware.org/?probe=26d0a4788c) | Aug 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1a72340ff4](https://linux-hardware.org/?probe=1a72340ff4) | Aug 01, 2021 |
| Lenovo        | G400s 20244                 | [43fe80380d](https://linux-hardware.org/?probe=43fe80380d) | Aug 01, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Lenovo        | G40-45 80E1                 | [597f4ff063](https://linux-hardware.org/?probe=597f4ff063) | Jul 29, 2021 |
| Dell          | Inspiron 3458               | [43d4236000](https://linux-hardware.org/?probe=43d4236000) | Jul 27, 2021 |
| Dell          | Vostro 14-3468              | [c222cecae0](https://linux-hardware.org/?probe=c222cecae0) | Jul 27, 2021 |
| Acer          | Swift SF314-43              | [690b0d3adc](https://linux-hardware.org/?probe=690b0d3adc) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | [3c2e8b0074](https://linux-hardware.org/?probe=3c2e8b0074) | Jul 26, 2021 |
| Acer          | Aspire A315-42              | [d59705a499](https://linux-hardware.org/?probe=d59705a499) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad X220 4291G75       | [fc0c3340bd](https://linux-hardware.org/?probe=fc0c3340bd) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [c466690f21](https://linux-hardware.org/?probe=c466690f21) | Jul 25, 2021 |
| Toshiba       | PORTEGE M800                | [6de34f58af](https://linux-hardware.org/?probe=6de34f58af) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [bfbf5b3302](https://linux-hardware.org/?probe=bfbf5b3302) | Jul 25, 2021 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [a8970607e0](https://linux-hardware.org/?probe=a8970607e0) | Jul 23, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [8d72c96d15](https://linux-hardware.org/?probe=8d72c96d15) | Jul 23, 2021 |
| Acer          | Aspire V5-431               | [0616ef50a5](https://linux-hardware.org/?probe=0616ef50a5) | Jul 22, 2021 |
| Apple         | MacBookPro6,2               | [22a976ce11](https://linux-hardware.org/?probe=22a976ce11) | Jul 21, 2021 |
| Lenovo        | G40-45 80E1                 | [c6b76cb1f9](https://linux-hardware.org/?probe=c6b76cb1f9) | Jul 21, 2021 |
| Acer          | Nitro AN515-45              | [714ce6dfc9](https://linux-hardware.org/?probe=714ce6dfc9) | Jul 19, 2021 |
| Acer          | Nitro AN515-45              | [e1d1356c93](https://linux-hardware.org/?probe=e1d1356c93) | Jul 19, 2021 |
| Acer          | Aspire V5-431               | [e0519d6c32](https://linux-hardware.org/?probe=e0519d6c32) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [d3561fadd3](https://linux-hardware.org/?probe=d3561fadd3) | Jul 18, 2021 |
| HP            | Laptop 14s-dk0xxx           | [6cc56f596f](https://linux-hardware.org/?probe=6cc56f596f) | Jul 17, 2021 |
| Lenovo        | ThinkPad X250 20CLA200ID    | [28c05ab175](https://linux-hardware.org/?probe=28c05ab175) | Jul 17, 2021 |
| Unknown       | Unknown                     | [1d1680d9c3](https://linux-hardware.org/?probe=1d1680d9c3) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4e75379022](https://linux-hardware.org/?probe=4e75379022) | Jul 16, 2021 |
| Dell          | Latitude E5520              | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [393ed0c954](https://linux-hardware.org/?probe=393ed0c954) | Jul 12, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [cd0155712e](https://linux-hardware.org/?probe=cd0155712e) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9727587570](https://linux-hardware.org/?probe=9727587570) | Jul 10, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [3e43acf8af](https://linux-hardware.org/?probe=3e43acf8af) | Jul 08, 2021 |
| Lenovo        | ThinkPad T430 2349SU6       | [9cd74fc6d1](https://linux-hardware.org/?probe=9cd74fc6d1) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [196e6c6ec4](https://linux-hardware.org/?probe=196e6c6ec4) | Jul 08, 2021 |
| ASUSTek       | X450EA                      | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| ASUSTek       | K84L                        | [01c9e0cbe1](https://linux-hardware.org/?probe=01c9e0cbe1) | Jul 03, 2021 |
| Acer          | Aspire A515-45              | [42249c6e47](https://linux-hardware.org/?probe=42249c6e47) | Jul 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c980ba6ae7](https://linux-hardware.org/?probe=c980ba6ae7) | Jul 02, 2021 |
| Acer          | Aspire A315-41              | [67c143c435](https://linux-hardware.org/?probe=67c143c435) | Jul 01, 2021 |
| Dell          | Latitude E5410              | [b047bdb721](https://linux-hardware.org/?probe=b047bdb721) | Jun 25, 2021 |
| Acer          | Aspire 4752                 | [16a063ab28](https://linux-hardware.org/?probe=16a063ab28) | Jun 24, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e135f49903](https://linux-hardware.org/?probe=e135f49903) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [114ba38c36](https://linux-hardware.org/?probe=114ba38c36) | Jun 20, 2021 |
| Acer          | Aspire E5-475G              | [0d6df01751](https://linux-hardware.org/?probe=0d6df01751) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [0cb7e73af9](https://linux-hardware.org/?probe=0cb7e73af9) | Jun 19, 2021 |
| Acer          | Aspire E5-475G              | [c1c0f815dc](https://linux-hardware.org/?probe=c1c0f815dc) | Jun 15, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7572d1aea9](https://linux-hardware.org/?probe=7572d1aea9) | Jun 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [9551aa9271](https://linux-hardware.org/?probe=9551aa9271) | Jun 06, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [6d45501f90](https://linux-hardware.org/?probe=6d45501f90) | Jun 05, 2021 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [8af935f813](https://linux-hardware.org/?probe=8af935f813) | Jun 02, 2021 |
| Acer          | Aspire E5-476G              | [ecbaba7315](https://linux-hardware.org/?probe=ecbaba7315) | May 31, 2021 |
| HP            | EliteBook Folio 9470m       | [3e6a2f7b59](https://linux-hardware.org/?probe=3e6a2f7b59) | May 27, 2021 |
| ASUSTek       | K45DR                       | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Dell          | Latitude E6410              | [7e35c63842](https://linux-hardware.org/?probe=7e35c63842) | May 26, 2021 |
| Acer          | Aspire 4752                 | [7ca3035a20](https://linux-hardware.org/?probe=7ca3035a20) | May 26, 2021 |
| ASUSTek       | K45DR                       | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| ASUSTek       | X550JX                      | [c837a795d7](https://linux-hardware.org/?probe=c837a795d7) | May 19, 2021 |
| Acer          | Okinawa                     | [9579ede8a9](https://linux-hardware.org/?probe=9579ede8a9) | May 19, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [1ad049bf43](https://linux-hardware.org/?probe=1ad049bf43) | May 17, 2021 |
| Acer          | Aspire 4752                 | [b26958098c](https://linux-hardware.org/?probe=b26958098c) | May 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [9a69a064a2](https://linux-hardware.org/?probe=9a69a064a2) | May 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0d732d9421](https://linux-hardware.org/?probe=0d732d9421) | May 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0beb84ac05](https://linux-hardware.org/?probe=0beb84ac05) | Apr 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2fddce1bd1](https://linux-hardware.org/?probe=2fddce1bd1) | Apr 29, 2021 |
| ASUSTek       | X453SA                      | [e72a666c50](https://linux-hardware.org/?probe=e72a666c50) | Apr 28, 2021 |
| Acer          | Aspire 4750                 | [dcfd3e0bb5](https://linux-hardware.org/?probe=dcfd3e0bb5) | Apr 24, 2021 |
| Acer          | Aspire 4750                 | [5b1db085fc](https://linux-hardware.org/?probe=5b1db085fc) | Apr 24, 2021 |
| Dell          | Latitude 5400               | [a2fb8a380a](https://linux-hardware.org/?probe=a2fb8a380a) | Apr 23, 2021 |
| Dell          | Latitude 5400               | [e4a0edd922](https://linux-hardware.org/?probe=e4a0edd922) | Apr 23, 2021 |
| Acer          | Aspire A514-53              | [2a5c4baa8f](https://linux-hardware.org/?probe=2a5c4baa8f) | Apr 18, 2021 |
| Acer          | Swift SF314-41              | [fde9376452](https://linux-hardware.org/?probe=fde9376452) | Apr 16, 2021 |
| Acer          | Swift SF314-41              | [9f50b41201](https://linux-hardware.org/?probe=9f50b41201) | Apr 16, 2021 |
| ASUSTek       | X441UV                      | [8ee5e69c11](https://linux-hardware.org/?probe=8ee5e69c11) | Apr 16, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| Acer          | Aspire 4752                 | [dbc22d503d](https://linux-hardware.org/?probe=dbc22d503d) | Apr 12, 2021 |
| Acer          | Aspire 4752                 | [c6ef5b093d](https://linux-hardware.org/?probe=c6ef5b093d) | Apr 12, 2021 |
| HP            | EliteBook 840 G1            | [b14a1a07ac](https://linux-hardware.org/?probe=b14a1a07ac) | Apr 11, 2021 |
| Dell          | Inspiron 5570               | [059aa32bb7](https://linux-hardware.org/?probe=059aa32bb7) | Apr 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [4a05cec425](https://linux-hardware.org/?probe=4a05cec425) | Apr 10, 2021 |
| Acer          | Aspire 4741                 | [cf750140a8](https://linux-hardware.org/?probe=cf750140a8) | Apr 10, 2021 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | [156c9db184](https://linux-hardware.org/?probe=156c9db184) | Apr 10, 2021 |
| Lenovo        | IdeaPad Z410 20292          | [803bcbb44c](https://linux-hardware.org/?probe=803bcbb44c) | Apr 05, 2021 |
| HP            | EliteBook Folio 9470m       | [22fc47b193](https://linux-hardware.org/?probe=22fc47b193) | Apr 05, 2021 |
| HP            | Laptop 15-bw0xx             | [44efde8890](https://linux-hardware.org/?probe=44efde8890) | Apr 05, 2021 |
| HP            | 1000                        | [be995ccb43](https://linux-hardware.org/?probe=be995ccb43) | Apr 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [941b588cf9](https://linux-hardware.org/?probe=941b588cf9) | Apr 03, 2021 |
| Acer          | Aspire 4739                 | [19ba24510c](https://linux-hardware.org/?probe=19ba24510c) | Apr 02, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [c41ba66f79](https://linux-hardware.org/?probe=c41ba66f79) | Apr 01, 2021 |
| Lenovo        | V310-14ISK 80SX             | [463bdc0444](https://linux-hardware.org/?probe=463bdc0444) | Apr 01, 2021 |
| ASUSTek       | X550VX                      | [4d95cd31eb](https://linux-hardware.org/?probe=4d95cd31eb) | Mar 27, 2021 |
| Dell          | Latitude 5400               | [5cab0ca67e](https://linux-hardware.org/?probe=5cab0ca67e) | Mar 26, 2021 |
| ASUSTek       | K45VD                       | [74592068ee](https://linux-hardware.org/?probe=74592068ee) | Mar 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3d99b46431](https://linux-hardware.org/?probe=3d99b46431) | Mar 25, 2021 |
| Lenovo        | V310-14ISK 80SX             | [1ce5b4161e](https://linux-hardware.org/?probe=1ce5b4161e) | Mar 24, 2021 |
| ASUSTek       | X45U                        | [05632e634d](https://linux-hardware.org/?probe=05632e634d) | Mar 23, 2021 |
| Dell          | Vostro 3481                 | [63b8942776](https://linux-hardware.org/?probe=63b8942776) | Mar 12, 2021 |
| ASUSTek       | X441SA                      | [abec8a4c19](https://linux-hardware.org/?probe=abec8a4c19) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [461b5d7b4b](https://linux-hardware.org/?probe=461b5d7b4b) | Mar 06, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [cb688e237f](https://linux-hardware.org/?probe=cb688e237f) | Mar 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [50a76385ba](https://linux-hardware.org/?probe=50a76385ba) | Mar 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [68d0129e2d](https://linux-hardware.org/?probe=68d0129e2d) | Mar 05, 2021 |
| Fujitsu       | LIFEBOOK AH544              | [80ce017529](https://linux-hardware.org/?probe=80ce017529) | Mar 04, 2021 |
| ASUSTek       | X442URR                     | [d8e04d832e](https://linux-hardware.org/?probe=d8e04d832e) | Mar 03, 2021 |
| ASUSTek       | UX303UB                     | [c4867a5743](https://linux-hardware.org/?probe=c4867a5743) | Mar 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [a5f08bd719](https://linux-hardware.org/?probe=a5f08bd719) | Mar 01, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [d3f1f06d5d](https://linux-hardware.org/?probe=d3f1f06d5d) | Feb 22, 2021 |
| HP            | Notebook                    | [e718153751](https://linux-hardware.org/?probe=e718153751) | Feb 22, 2021 |
| ASUSTek       | K42F                        | [2380c82b48](https://linux-hardware.org/?probe=2380c82b48) | Feb 20, 2021 |
| HP            | Notebook                    | [326de2e4f5](https://linux-hardware.org/?probe=326de2e4f5) | Feb 19, 2021 |
| ASUSTek       | U36SD                       | [981c7e8da7](https://linux-hardware.org/?probe=981c7e8da7) | Feb 19, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [f9abaeb3f9](https://linux-hardware.org/?probe=f9abaeb3f9) | Feb 18, 2021 |
| HP            | Laptop 14-bw0xx             | [1a3e26503a](https://linux-hardware.org/?probe=1a3e26503a) | Feb 17, 2021 |
| Acer          | Aspire E5-471G              | [3b58cbf4e6](https://linux-hardware.org/?probe=3b58cbf4e6) | Feb 17, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [5a09ac2a06](https://linux-hardware.org/?probe=5a09ac2a06) | Feb 16, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [9805e3bcb5](https://linux-hardware.org/?probe=9805e3bcb5) | Feb 16, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a0537ad7d5](https://linux-hardware.org/?probe=a0537ad7d5) | Feb 16, 2021 |
| Toshiba       | Satellite C855              | [60adcbc05d](https://linux-hardware.org/?probe=60adcbc05d) | Feb 16, 2021 |
| Timi          | TM1703                      | [4d64e40cca](https://linux-hardware.org/?probe=4d64e40cca) | Feb 14, 2021 |
| HP            | Pavilion Laptop 14-bf0xx    | [309266e981](https://linux-hardware.org/?probe=309266e981) | Feb 13, 2021 |
| ASUSTek       | X456UQK                     | [f0380f099d](https://linux-hardware.org/?probe=f0380f099d) | Feb 12, 2021 |
| ASUSTek       | K43E                        | [1604193c0f](https://linux-hardware.org/?probe=1604193c0f) | Feb 11, 2021 |
| Lenovo        | G50-80 80E5                 | [704dbacb0d](https://linux-hardware.org/?probe=704dbacb0d) | Feb 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [ec95272afa](https://linux-hardware.org/?probe=ec95272afa) | Feb 10, 2021 |
| Lenovo        | ThinkPad X131e 33741E0      | [4c52c9aa29](https://linux-hardware.org/?probe=4c52c9aa29) | Feb 06, 2021 |
| Acer          | NXHATSN00190808A906600      | [2ed3d18f0a](https://linux-hardware.org/?probe=2ed3d18f0a) | Feb 05, 2021 |
| ASUSTek       | N56VM                       | [d56280ec33](https://linux-hardware.org/?probe=d56280ec33) | Feb 05, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [f48cf2f332](https://linux-hardware.org/?probe=f48cf2f332) | Feb 05, 2021 |
| Compal        | PBL10                       | [5cf67578d7](https://linux-hardware.org/?probe=5cf67578d7) | Feb 04, 2021 |
| Compal        | PBL10                       | [a20e9d9588](https://linux-hardware.org/?probe=a20e9d9588) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | [f79d79fd99](https://linux-hardware.org/?probe=f79d79fd99) | Feb 04, 2021 |
| HP            | ZBook Studio G3             | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| HP            | EliteBook Folio 9470m       | [15b84d2abc](https://linux-hardware.org/?probe=15b84d2abc) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | [9b722252fa](https://linux-hardware.org/?probe=9b722252fa) | Feb 04, 2021 |
| HP            | Laptop 14-cm0xxx            | [2365556c9d](https://linux-hardware.org/?probe=2365556c9d) | Jan 31, 2021 |
| ASUSTek       | U36SD                       | [5267c17fbb](https://linux-hardware.org/?probe=5267c17fbb) | Jan 30, 2021 |
| HP            | ZBook 15 G2                 | [cebba8a2a8](https://linux-hardware.org/?probe=cebba8a2a8) | Jan 30, 2021 |
| Lenovo        | ThinkPad X280 20KES7YB00    | [b498c0fcba](https://linux-hardware.org/?probe=b498c0fcba) | Jan 29, 2021 |
| ASUSTek       | U36SD                       | [15288996d1](https://linux-hardware.org/?probe=15288996d1) | Jan 28, 2021 |
| Acer          | Aspire 4752                 | [2e5b64f391](https://linux-hardware.org/?probe=2e5b64f391) | Jan 27, 2021 |
| Acer          | Aspire 4752                 | [f068345e45](https://linux-hardware.org/?probe=f068345e45) | Jan 27, 2021 |
| Acer          | AOD255E                     | [b346230927](https://linux-hardware.org/?probe=b346230927) | Jan 27, 2021 |
| ASUSTek       | N56VM                       | [e6d527734c](https://linux-hardware.org/?probe=e6d527734c) | Jan 27, 2021 |
| Acer          | One Z1402                   | [1b8a4dfe38](https://linux-hardware.org/?probe=1b8a4dfe38) | Jan 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4cacca5cdf](https://linux-hardware.org/?probe=4cacca5cdf) | Jan 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d18f1e2124](https://linux-hardware.org/?probe=d18f1e2124) | Jan 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [16b5d3f4ca](https://linux-hardware.org/?probe=16b5d3f4ca) | Jan 23, 2021 |
| Acer          | Swift SF514-52T             | [be049e723f](https://linux-hardware.org/?probe=be049e723f) | Jan 21, 2021 |
| ASUSTek       | N56VM                       | [81c592d723](https://linux-hardware.org/?probe=81c592d723) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [dc16c8d7a4](https://linux-hardware.org/?probe=dc16c8d7a4) | Jan 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f9b1a75983](https://linux-hardware.org/?probe=f9b1a75983) | Jan 19, 2021 |
| Lenovo        | ThinkPad T480 20L5A02JID    | [0599ce4883](https://linux-hardware.org/?probe=0599ce4883) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f34a9b325b](https://linux-hardware.org/?probe=f34a9b325b) | Jan 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [be559d7b11](https://linux-hardware.org/?probe=be559d7b11) | Jan 17, 2021 |
| Lenovo        | IdeaPad Z370                | [728438c7eb](https://linux-hardware.org/?probe=728438c7eb) | Jan 16, 2021 |
| Lenovo        | IdeaPad Z370                | [6e3c415308](https://linux-hardware.org/?probe=6e3c415308) | Jan 16, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [82728c7a68](https://linux-hardware.org/?probe=82728c7a68) | Jan 15, 2021 |
| Dell          | Vostro 5470                 | [8e785a29dd](https://linux-hardware.org/?probe=8e785a29dd) | Jan 15, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [bb99db17ed](https://linux-hardware.org/?probe=bb99db17ed) | Jan 15, 2021 |
| HP            | G42                         | [63dd848e66](https://linux-hardware.org/?probe=63dd848e66) | Jan 14, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [0cfe91c011](https://linux-hardware.org/?probe=0cfe91c011) | Jan 13, 2021 |
| HP            | ZBook 15 G2                 | [da387b9871](https://linux-hardware.org/?probe=da387b9871) | Jan 09, 2021 |
| ASUSTek       | G750JM                      | [794d86e07e](https://linux-hardware.org/?probe=794d86e07e) | Jan 07, 2021 |
| ASUSTek       | G750JM                      | [a32f193a0d](https://linux-hardware.org/?probe=a32f193a0d) | Jan 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [692f320444](https://linux-hardware.org/?probe=692f320444) | Jan 07, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [8a573087bd](https://linux-hardware.org/?probe=8a573087bd) | Jan 07, 2021 |
| MSI           | Modern 15 A10RBS            | [d4ded10aed](https://linux-hardware.org/?probe=d4ded10aed) | Jan 06, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [ea36c16e10](https://linux-hardware.org/?probe=ea36c16e10) | Jan 05, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [89d2d898df](https://linux-hardware.org/?probe=89d2d898df) | Jan 05, 2021 |
| ASUSTek       | K43SD                       | [79f04bb2b4](https://linux-hardware.org/?probe=79f04bb2b4) | Jan 04, 2021 |
| HP            | ZBook 15 G2                 | [6ebc8c1b1c](https://linux-hardware.org/?probe=6ebc8c1b1c) | Jan 03, 2021 |
| ASUSTek       | X455LAB                     | [1c55bbde2e](https://linux-hardware.org/?probe=1c55bbde2e) | Jan 01, 2021 |
| HP            | 1000                        | [981fa79f13](https://linux-hardware.org/?probe=981fa79f13) | Jan 01, 2021 |
| ASUSTek       | X455LAB                     | [8cbb6c5afe](https://linux-hardware.org/?probe=8cbb6c5afe) | Dec 31, 2020 |
| Sole          | Unknown                     | [04bc36aa05](https://linux-hardware.org/?probe=04bc36aa05) | Dec 30, 2020 |
| HP            | ZBook 15 G2                 | [87757ee4f2](https://linux-hardware.org/?probe=87757ee4f2) | Dec 30, 2020 |
| Dell          | Vostro A840                 | [76e7e81662](https://linux-hardware.org/?probe=76e7e81662) | Dec 28, 2020 |
| Lenovo        | ThinkPad T530 24294V4       | [50625b08c9](https://linux-hardware.org/?probe=50625b08c9) | Dec 26, 2020 |
| HP            | EliteBook Folio 9470m       | [5bd5d77342](https://linux-hardware.org/?probe=5bd5d77342) | Dec 24, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | [a53bf69f31](https://linux-hardware.org/?probe=a53bf69f31) | Dec 24, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | [7f1872861c](https://linux-hardware.org/?probe=7f1872861c) | Dec 24, 2020 |
| Acer          | Aspire 4738Z                | [26c4af7060](https://linux-hardware.org/?probe=26c4af7060) | Dec 22, 2020 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [be0654391c](https://linux-hardware.org/?probe=be0654391c) | Dec 21, 2020 |
| Phoenix/Si... | M720SR                      | [019e901528](https://linux-hardware.org/?probe=019e901528) | Dec 19, 2020 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [23766674a9](https://linux-hardware.org/?probe=23766674a9) | Dec 18, 2020 |
| ASUSTek       | K55DR                       | [86bca93d29](https://linux-hardware.org/?probe=86bca93d29) | Dec 16, 2020 |
| ASUSTek       | K55DR                       | [300d21973e](https://linux-hardware.org/?probe=300d21973e) | Dec 16, 2020 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [667577cb5f](https://linux-hardware.org/?probe=667577cb5f) | Dec 15, 2020 |
| ASUSTek       | 1015BX                      | [5cb5d5f2a8](https://linux-hardware.org/?probe=5cb5d5f2a8) | Dec 15, 2020 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [406d93673b](https://linux-hardware.org/?probe=406d93673b) | Dec 13, 2020 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [785196a6d7](https://linux-hardware.org/?probe=785196a6d7) | Dec 13, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | [8a32a0ec2e](https://linux-hardware.org/?probe=8a32a0ec2e) | Dec 08, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | [318416a95a](https://linux-hardware.org/?probe=318416a95a) | Dec 08, 2020 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [d4c5036cd3](https://linux-hardware.org/?probe=d4c5036cd3) | Dec 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [5f56870146](https://linux-hardware.org/?probe=5f56870146) | Dec 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2a305a9be7](https://linux-hardware.org/?probe=2a305a9be7) | Dec 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [cf81aea5fe](https://linux-hardware.org/?probe=cf81aea5fe) | Dec 02, 2020 |
| ASUSTek       | X456URK                     | [be6b2ec83a](https://linux-hardware.org/?probe=be6b2ec83a) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y410P 20216         | [b664b71a15](https://linux-hardware.org/?probe=b664b71a15) | Nov 28, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4be164a8cb](https://linux-hardware.org/?probe=4be164a8cb) | Nov 26, 2020 |
| Acer          | NXHATSN00190808A906600      | [402e6fe81a](https://linux-hardware.org/?probe=402e6fe81a) | Nov 26, 2020 |
| Toshiba       | Satellite L40               | [ffafc05e1f](https://linux-hardware.org/?probe=ffafc05e1f) | Nov 25, 2020 |
| HP            | 14                          | [1a02430025](https://linux-hardware.org/?probe=1a02430025) | Nov 23, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4accc1011e](https://linux-hardware.org/?probe=4accc1011e) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [b17dd2d085](https://linux-hardware.org/?probe=b17dd2d085) | Nov 21, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [25abf7a587](https://linux-hardware.org/?probe=25abf7a587) | Nov 19, 2020 |
| HP            | 14                          | [548056d4e9](https://linux-hardware.org/?probe=548056d4e9) | Nov 18, 2020 |
| HP            | 14                          | [a08766aff4](https://linux-hardware.org/?probe=a08766aff4) | Nov 18, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3d65def3ce](https://linux-hardware.org/?probe=3d65def3ce) | Nov 16, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [82dbd47dff](https://linux-hardware.org/?probe=82dbd47dff) | Nov 15, 2020 |
| Dell          | XPS 13 7390                 | [8844beb362](https://linux-hardware.org/?probe=8844beb362) | Nov 14, 2020 |
| Lenovo        | ThinkPad T410s 2904CGU      | [271f9ac078](https://linux-hardware.org/?probe=271f9ac078) | Nov 14, 2020 |
| Acer          | Aspire V5-132               | [166921ade6](https://linux-hardware.org/?probe=166921ade6) | Nov 13, 2020 |
| Acer          | Aspire E5-421               | [625727a34f](https://linux-hardware.org/?probe=625727a34f) | Nov 12, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [0b2411ab89](https://linux-hardware.org/?probe=0b2411ab89) | Nov 12, 2020 |
| Lenovo        | G400 20235                  | [e8b5212a0b](https://linux-hardware.org/?probe=e8b5212a0b) | Nov 11, 2020 |
| Acer          | Aspire E5-475G              | [1d195bfc21](https://linux-hardware.org/?probe=1d195bfc21) | Nov 10, 2020 |
| Lenovo        | ThinkPad T430 2342A19       | [579f942204](https://linux-hardware.org/?probe=579f942204) | Nov 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [923558f59a](https://linux-hardware.org/?probe=923558f59a) | Nov 08, 2020 |
| ASUSTek       | X453SA                      | [1bb7c5cfe5](https://linux-hardware.org/?probe=1bb7c5cfe5) | Nov 03, 2020 |
| ASUSTek       | X442UQR                     | [98225dbf74](https://linux-hardware.org/?probe=98225dbf74) | Nov 03, 2020 |
| Unknown       | Unknown                     | [4c80913adb](https://linux-hardware.org/?probe=4c80913adb) | Nov 02, 2020 |
| Lenovo        | G40-30 80FY                 | [7bc709a3cd](https://linux-hardware.org/?probe=7bc709a3cd) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [64b38989db](https://linux-hardware.org/?probe=64b38989db) | Oct 30, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [516ff504f0](https://linux-hardware.org/?probe=516ff504f0) | Oct 29, 2020 |
| Lenovo        | IdeaPad 310-14IKB 80TU      | [45b0065d49](https://linux-hardware.org/?probe=45b0065d49) | Oct 28, 2020 |
| HP            | Notebook                    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| Clevo         | M7x0S                       | [8559d7b074](https://linux-hardware.org/?probe=8559d7b074) | Oct 24, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3b60701957](https://linux-hardware.org/?probe=3b60701957) | Oct 23, 2020 |
| Lenovo        | V330-14IKB 81B0             | [0a1f42ff5e](https://linux-hardware.org/?probe=0a1f42ff5e) | Oct 18, 2020 |
| Lenovo        | V330-14IKB 81B0             | [327a983226](https://linux-hardware.org/?probe=327a983226) | Oct 18, 2020 |
| Acer          | Nitro AN515-52              | [ca3d5b9444](https://linux-hardware.org/?probe=ca3d5b9444) | Oct 13, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [646054c190](https://linux-hardware.org/?probe=646054c190) | Oct 08, 2020 |
| ASUSTek       | X442URR                     | [5e9f9ee314](https://linux-hardware.org/?probe=5e9f9ee314) | Oct 06, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [57e753215c](https://linux-hardware.org/?probe=57e753215c) | Oct 04, 2020 |
| Lenovo        | IdeaPad Z480                | [36a5cbc73c](https://linux-hardware.org/?probe=36a5cbc73c) | Oct 03, 2020 |
| Lenovo        | IdeaPad Z480                | [f7282459cf](https://linux-hardware.org/?probe=f7282459cf) | Oct 03, 2020 |
| Acer          | NXHATSN00190808A906600      | [ece82b096b](https://linux-hardware.org/?probe=ece82b096b) | Oct 01, 2020 |
| HP            | Pavilion x2 Detachable      | [d4078124eb](https://linux-hardware.org/?probe=d4078124eb) | Sep 30, 2020 |
| ASUSTek       | X450EA                      | [2646942e92](https://linux-hardware.org/?probe=2646942e92) | Sep 30, 2020 |
| HP            | 430                         | [9eef183864](https://linux-hardware.org/?probe=9eef183864) | Sep 27, 2020 |
| Toshiba       | Satellite L730              | [28ff46aa6b](https://linux-hardware.org/?probe=28ff46aa6b) | Sep 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [24b078a7f0](https://linux-hardware.org/?probe=24b078a7f0) | Sep 24, 2020 |
| HP            | Laptop 15-bw0xx             | [9067f67190](https://linux-hardware.org/?probe=9067f67190) | Sep 24, 2020 |
| ASUSTek       | X455YA                      | [0959901fca](https://linux-hardware.org/?probe=0959901fca) | Sep 23, 2020 |
| HP            | ENVY Laptop 13-aq1xxx       | [ed83ee1e30](https://linux-hardware.org/?probe=ed83ee1e30) | Sep 22, 2020 |
| Acer          | Aspire ES1-111M             | [4a9dbc9937](https://linux-hardware.org/?probe=4a9dbc9937) | Sep 19, 2020 |
| Acer          | Aspire ES1-111M             | [0e2694227b](https://linux-hardware.org/?probe=0e2694227b) | Sep 19, 2020 |
| Apple         | MacBookPro12,1              | [d766064036](https://linux-hardware.org/?probe=d766064036) | Sep 17, 2020 |
| HP            | 430                         | [bfb152e615](https://linux-hardware.org/?probe=bfb152e615) | Sep 10, 2020 |
| ASUSTek       | GL503VD                     | [820f4da953](https://linux-hardware.org/?probe=820f4da953) | Sep 09, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [d545f007f9](https://linux-hardware.org/?probe=d545f007f9) | Sep 05, 2020 |
| Acer          | Nitro AN515-43              | [7e0202ac18](https://linux-hardware.org/?probe=7e0202ac18) | Sep 04, 2020 |
| Acer          | Nitro AN515-43              | [152a400df9](https://linux-hardware.org/?probe=152a400df9) | Sep 04, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [712ec86d11](https://linux-hardware.org/?probe=712ec86d11) | Sep 04, 2020 |
| HP            | Pavilion Gaming Notebook    | [5bcdd6aa5a](https://linux-hardware.org/?probe=5bcdd6aa5a) | Sep 03, 2020 |
| HP            | Laptop 15-bw0xx             | [02c0bf156d](https://linux-hardware.org/?probe=02c0bf156d) | Sep 03, 2020 |
| Lenovo        | G405 20239                  | [518d27feca](https://linux-hardware.org/?probe=518d27feca) | Sep 03, 2020 |
| ASUSTek       | X441BA                      | [e244d30598](https://linux-hardware.org/?probe=e244d30598) | Sep 03, 2020 |
| Lenovo        | ThinkPad X230 2325WLB       | [e558c503f8](https://linux-hardware.org/?probe=e558c503f8) | Sep 03, 2020 |
| Lenovo        | ThinkPad X230 2324AS7       | [676f1b8dce](https://linux-hardware.org/?probe=676f1b8dce) | Sep 03, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [24bdd07050](https://linux-hardware.org/?probe=24bdd07050) | Sep 02, 2020 |
| HP            | Pavilion dm1                | [1723b44134](https://linux-hardware.org/?probe=1723b44134) | Sep 02, 2020 |
| HP            | Pavilion Gaming Notebook    | [0c63fa76a6](https://linux-hardware.org/?probe=0c63fa76a6) | Sep 01, 2020 |
| HP            | EliteBook 2570p             | [a70aa343a9](https://linux-hardware.org/?probe=a70aa343a9) | Aug 31, 2020 |
| HP            | Pavilion g4                 | [cf281b97df](https://linux-hardware.org/?probe=cf281b97df) | Aug 31, 2020 |
| HP            | Pavilion g4                 | [4ae31fc59f](https://linux-hardware.org/?probe=4ae31fc59f) | Aug 30, 2020 |
| HP            | Pavilion Laptop 14-bf0xx    | [687538cadf](https://linux-hardware.org/?probe=687538cadf) | Aug 24, 2020 |
| Lenovo        | G400 20235                  | [f209fc4fd1](https://linux-hardware.org/?probe=f209fc4fd1) | Aug 22, 2020 |
| ASUSTek       | X550IK                      | [70aa141880](https://linux-hardware.org/?probe=70aa141880) | Aug 21, 2020 |
| Dell          | Inspiron 3180               | [cd7328883c](https://linux-hardware.org/?probe=cd7328883c) | Aug 18, 2020 |
| Fujitsu       | LIFEBOOK E734               | [977a611718](https://linux-hardware.org/?probe=977a611718) | Aug 16, 2020 |
| Dell          | Latitude E6400              | [177b63fda5](https://linux-hardware.org/?probe=177b63fda5) | Aug 15, 2020 |
| HP            | ProBook 440 G7              | [5291acaadc](https://linux-hardware.org/?probe=5291acaadc) | Aug 14, 2020 |
| HP            | ProBook 440 G4              | [191f1be39f](https://linux-hardware.org/?probe=191f1be39f) | Aug 14, 2020 |
| Dell          | Latitude E6230              | [da6d9fdf1d](https://linux-hardware.org/?probe=da6d9fdf1d) | Aug 14, 2020 |
| HP            | Notebook                    | [8e7a53706c](https://linux-hardware.org/?probe=8e7a53706c) | Aug 13, 2020 |
| HP            | ProBook 440 G4              | [c34e36f36e](https://linux-hardware.org/?probe=c34e36f36e) | Aug 10, 2020 |
| HP            | ProBook 440 G4              | [5b6c3861bb](https://linux-hardware.org/?probe=5b6c3861bb) | Aug 10, 2020 |
| Fujitsu       | LIFEBOOK E734               | [74050bb5dd](https://linux-hardware.org/?probe=74050bb5dd) | Aug 10, 2020 |
| HP            | Pavilion g4                 | [0ea8276f60](https://linux-hardware.org/?probe=0ea8276f60) | Aug 07, 2020 |
| HP            | Pavilion g4                 | [227e2e8de7](https://linux-hardware.org/?probe=227e2e8de7) | Aug 07, 2020 |
| HP            | ProBook 440 G2              | [b19e6b64a7](https://linux-hardware.org/?probe=b19e6b64a7) | Aug 07, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [8a63857dec](https://linux-hardware.org/?probe=8a63857dec) | Aug 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [99bb1cd9d9](https://linux-hardware.org/?probe=99bb1cd9d9) | Aug 06, 2020 |
| Dell          | Latitude E6400              | [a1d10698bc](https://linux-hardware.org/?probe=a1d10698bc) | Aug 05, 2020 |
| Toshiba       | Satellite L745              | [4770498bee](https://linux-hardware.org/?probe=4770498bee) | Aug 02, 2020 |
| Toshiba       | Satellite L745              | [8f86800c3c](https://linux-hardware.org/?probe=8f86800c3c) | Aug 02, 2020 |
| ASUSTek       | N46VM                       | [d5866f9f0f](https://linux-hardware.org/?probe=d5866f9f0f) | Jul 30, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [81ca2030be](https://linux-hardware.org/?probe=81ca2030be) | Jul 29, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3db826b463](https://linux-hardware.org/?probe=3db826b463) | Jul 29, 2020 |
| ASUSTek       | K43E                        | [47067cf62f](https://linux-hardware.org/?probe=47067cf62f) | Jul 29, 2020 |
| ASUSTek       | K43E                        | [5cc61ff85e](https://linux-hardware.org/?probe=5cc61ff85e) | Jul 29, 2020 |
| ASUSTek       | N46VM                       | [b9abcbb0ca](https://linux-hardware.org/?probe=b9abcbb0ca) | Jul 27, 2020 |
| ASUSTek       | N46VM                       | [864b3c0808](https://linux-hardware.org/?probe=864b3c0808) | Jul 27, 2020 |
| ASUSTek       | N43SN                       | [8652a9c307](https://linux-hardware.org/?probe=8652a9c307) | Jul 24, 2020 |
| ASUSTek       | N43SN                       | [6417be2a1c](https://linux-hardware.org/?probe=6417be2a1c) | Jul 24, 2020 |
| Dell          | Latitude E6420              | [2c5b59d1df](https://linux-hardware.org/?probe=2c5b59d1df) | Jul 22, 2020 |
| ASUSTek       | X451CAP                     | [b4a3b63689](https://linux-hardware.org/?probe=b4a3b63689) | Jul 21, 2020 |
| ASUSTek       | X451CAP                     | [948bec3418](https://linux-hardware.org/?probe=948bec3418) | Jul 21, 2020 |
| HP            | Laptop 14-bs0xx             | [be0c3117b4](https://linux-hardware.org/?probe=be0c3117b4) | Jul 20, 2020 |
| ASUSTek       | X451CAP                     | [9043a7e401](https://linux-hardware.org/?probe=9043a7e401) | Jul 20, 2020 |
| Lenovo        | ThinkPad W550s 20E2000CM... | [2db5fa6bb3](https://linux-hardware.org/?probe=2db5fa6bb3) | Jul 19, 2020 |
| HP            | Pavilion g4                 | [cfa0470ff1](https://linux-hardware.org/?probe=cfa0470ff1) | Jul 18, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [50272ea6ea](https://linux-hardware.org/?probe=50272ea6ea) | Jul 16, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2b9f97d49e](https://linux-hardware.org/?probe=2b9f97d49e) | Jul 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [acf40c367c](https://linux-hardware.org/?probe=acf40c367c) | Jul 14, 2020 |
| HP            | 14                          | [c49bc9fa04](https://linux-hardware.org/?probe=c49bc9fa04) | Jul 13, 2020 |
| HP            | 14                          | [16f518d4d1](https://linux-hardware.org/?probe=16f518d4d1) | Jul 12, 2020 |
| ASUSTek       | X550ZE                      | [95e148ab0b](https://linux-hardware.org/?probe=95e148ab0b) | Jul 11, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | [ce870d391e](https://linux-hardware.org/?probe=ce870d391e) | Jul 09, 2020 |
| Acer          | Aspire E1-451G              | [4765a08df1](https://linux-hardware.org/?probe=4765a08df1) | Jul 04, 2020 |
| Toshiba       | Satellite C40-A             | [672cca96fd](https://linux-hardware.org/?probe=672cca96fd) | Jul 04, 2020 |
| Lenovo        | IdeaPad S210 20256          | [31723f3abc](https://linux-hardware.org/?probe=31723f3abc) | Jul 04, 2020 |
| ASUSTek       | X555BP                      | [e34500bb1c](https://linux-hardware.org/?probe=e34500bb1c) | Jul 03, 2020 |
| Acer          | Aspire F5-571T              | [61e70ca838](https://linux-hardware.org/?probe=61e70ca838) | Jun 29, 2020 |
| Acer          | Aspire F5-571T              | [bfc16ddd86](https://linux-hardware.org/?probe=bfc16ddd86) | Jun 28, 2020 |
| Lenovo        | ThinkPad X131e 33684SU      | [1ed3f7e63d](https://linux-hardware.org/?probe=1ed3f7e63d) | Jun 28, 2020 |
| ASUSTek       | UX331UN                     | [3bf2e1fb3c](https://linux-hardware.org/?probe=3bf2e1fb3c) | Jun 27, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [20fe5eb234](https://linux-hardware.org/?probe=20fe5eb234) | Jun 27, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [34c449d22e](https://linux-hardware.org/?probe=34c449d22e) | Jun 26, 2020 |
| HP            | 14                          | [4de0326f3b](https://linux-hardware.org/?probe=4de0326f3b) | Jun 24, 2020 |
| Acer          | Swift SF314-54G             | [e69e144ab8](https://linux-hardware.org/?probe=e69e144ab8) | Jun 21, 2020 |
| Lenovo        | G400 20235                  | [b3d56039ce](https://linux-hardware.org/?probe=b3d56039ce) | Jun 20, 2020 |
| Dell          | Latitude E6420              | [f186fc19d1](https://linux-hardware.org/?probe=f186fc19d1) | Jun 20, 2020 |
| Dell          | Latitude E6420              | [f4a05ff8fe](https://linux-hardware.org/?probe=f4a05ff8fe) | Jun 19, 2020 |
| Lenovo        | ThinkPad Twist 33473BA      | [6af138a9a7](https://linux-hardware.org/?probe=6af138a9a7) | Jun 18, 2020 |
| Dell          | System Inspiron N4110       | [4d8d8ad86f](https://linux-hardware.org/?probe=4d8d8ad86f) | Jun 18, 2020 |
| HP            | Laptop 14-bp0xx             | [6efe053f69](https://linux-hardware.org/?probe=6efe053f69) | Jun 18, 2020 |
| HP            | Laptop 14-bp0xx             | [e1611d4a8f](https://linux-hardware.org/?probe=e1611d4a8f) | Jun 18, 2020 |
| Dell          | Latitude E6420              | [d7a5e67910](https://linux-hardware.org/?probe=d7a5e67910) | Jun 16, 2020 |
| Acer          | Aspire 4752                 | [c1bf847a06](https://linux-hardware.org/?probe=c1bf847a06) | Jun 15, 2020 |
| Dell          | Latitude E6420              | [b4e34247b1](https://linux-hardware.org/?probe=b4e34247b1) | Jun 14, 2020 |
| Dell          | Latitude E6420              | [9f81490571](https://linux-hardware.org/?probe=9f81490571) | Jun 12, 2020 |
| ASUSTek       | K46CM                       | [f50bd98e01](https://linux-hardware.org/?probe=f50bd98e01) | Jun 06, 2020 |
| Toshiba       | NB510                       | [034e807bf8](https://linux-hardware.org/?probe=034e807bf8) | Jun 05, 2020 |
| HP            | Pavilion g4                 | [a6a626b9ca](https://linux-hardware.org/?probe=a6a626b9ca) | Jun 04, 2020 |
| Acer          | Aspire 5050                 | [0c4de1a1a1](https://linux-hardware.org/?probe=0c4de1a1a1) | Jun 01, 2020 |
| Acer          | Aspire 5050                 | [ec8759bd69](https://linux-hardware.org/?probe=ec8759bd69) | Jun 01, 2020 |
| Acer          | Aspire A315-41              | [e91778b012](https://linux-hardware.org/?probe=e91778b012) | May 31, 2020 |
| ASUSTek       | K46CM                       | [b2b5f9db8d](https://linux-hardware.org/?probe=b2b5f9db8d) | May 31, 2020 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [dcc2d3e59f](https://linux-hardware.org/?probe=dcc2d3e59f) | May 31, 2020 |
| Lenovo        | G40-45 80E1                 | [4002bc5fb1](https://linux-hardware.org/?probe=4002bc5fb1) | May 30, 2020 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [b45d1eb089](https://linux-hardware.org/?probe=b45d1eb089) | May 28, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [00f65112c3](https://linux-hardware.org/?probe=00f65112c3) | May 28, 2020 |
| ASUSTek       | X200CA                      | [838a34d93c](https://linux-hardware.org/?probe=838a34d93c) | May 22, 2020 |
| MSI           | MS-1481                     | [e32bed7fb1](https://linux-hardware.org/?probe=e32bed7fb1) | May 15, 2020 |
| Lenovo        | IdeaPad S340-15IWLTouch ... | [412ba3814d](https://linux-hardware.org/?probe=412ba3814d) | May 15, 2020 |
| Lenovo        | IdeaPad S340-15IWLTouch ... | [ba05f4ff6a](https://linux-hardware.org/?probe=ba05f4ff6a) | May 15, 2020 |
| HP            | Pavilion 14                 | [f366f5c4e4](https://linux-hardware.org/?probe=f366f5c4e4) | May 11, 2020 |
| Lenovo        | G400s 20244                 | [c53de49fbc](https://linux-hardware.org/?probe=c53de49fbc) | May 10, 2020 |
| Lenovo        | ThinkPad T430 2349FC3       | [00f6deaf61](https://linux-hardware.org/?probe=00f6deaf61) | May 09, 2020 |
| Lenovo        | ThinkPad Twist 33473BA      | [3dee72a67f](https://linux-hardware.org/?probe=3dee72a67f) | May 08, 2020 |
| Apple         | MacBookPro12,1              | [b0c6f48549](https://linux-hardware.org/?probe=b0c6f48549) | May 08, 2020 |
| ASUSTek       | N46VM                       | [dac0d32083](https://linux-hardware.org/?probe=dac0d32083) | May 08, 2020 |
| ASUSTek       | X442URR                     | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| Dell          | Vostro 14-3468              | [d1670dbbdd](https://linux-hardware.org/?probe=d1670dbbdd) | May 04, 2020 |
| Dell          | Vostro 14-3468              | [dbb1d688e9](https://linux-hardware.org/?probe=dbb1d688e9) | Apr 28, 2020 |
| Dell          | Vostro 14-3468              | [66350e55ef](https://linux-hardware.org/?probe=66350e55ef) | Apr 28, 2020 |
| Toshiba       | Satellite L510              | [a27037c0e1](https://linux-hardware.org/?probe=a27037c0e1) | Apr 26, 2020 |
| Lenovo        | ThinkPad T410 2522CTO       | [0342587f2b](https://linux-hardware.org/?probe=0342587f2b) | Apr 26, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [09b7ff4a7f](https://linux-hardware.org/?probe=09b7ff4a7f) | Apr 25, 2020 |
| HP            | EliteBook 840 G1            | [8d9870131a](https://linux-hardware.org/?probe=8d9870131a) | Apr 24, 2020 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [2aa0175c4b](https://linux-hardware.org/?probe=2aa0175c4b) | Apr 22, 2020 |
| ASUSTek       | X450CC                      | [8395776e77](https://linux-hardware.org/?probe=8395776e77) | Apr 21, 2020 |
| Acer          | Swift SF314-56G             | [f2608b9796](https://linux-hardware.org/?probe=f2608b9796) | Apr 18, 2020 |
| AXIOO         | NEON CNW                    | [64edfa7923](https://linux-hardware.org/?probe=64edfa7923) | Apr 18, 2020 |
| ASUSTek       | X442UR                      | [b96b676ec0](https://linux-hardware.org/?probe=b96b676ec0) | Apr 16, 2020 |
| Apple         | MacBook4,1                  | [17f5daf01e](https://linux-hardware.org/?probe=17f5daf01e) | Apr 16, 2020 |
| HP            | EliteBook 2560p             | [61ff7566f0](https://linux-hardware.org/?probe=61ff7566f0) | Apr 13, 2020 |
| HP            | EliteBook 2560p             | [e830e91c74](https://linux-hardware.org/?probe=e830e91c74) | Apr 13, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | [15057e288d](https://linux-hardware.org/?probe=15057e288d) | Apr 11, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | [90ca183e3d](https://linux-hardware.org/?probe=90ca183e3d) | Apr 10, 2020 |
| HP            | 540                         | [6fa99c27dd](https://linux-hardware.org/?probe=6fa99c27dd) | Apr 10, 2020 |
| AXIOO         | NEON CNW                    | [b31fc0c0dd](https://linux-hardware.org/?probe=b31fc0c0dd) | Apr 10, 2020 |
| Toshiba       | Satellite L510              | [659bf517f1](https://linux-hardware.org/?probe=659bf517f1) | Apr 08, 2020 |
| HP            | EliteBook 2560p             | [9e472a05c5](https://linux-hardware.org/?probe=9e472a05c5) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | [488c8306ff](https://linux-hardware.org/?probe=488c8306ff) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | [6928abb72d](https://linux-hardware.org/?probe=6928abb72d) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | [020c71d11e](https://linux-hardware.org/?probe=020c71d11e) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | [163b885549](https://linux-hardware.org/?probe=163b885549) | Apr 07, 2020 |
| Dell          | Inspiron 3458               | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| Toshiba       | Satellite Pro C640          | [322a06db55](https://linux-hardware.org/?probe=322a06db55) | Mar 29, 2020 |
| AXIOO         | Mybook Lite                 | [0ec3e1d33f](https://linux-hardware.org/?probe=0ec3e1d33f) | Mar 28, 2020 |
| AXIOO         | Mybook Lite                 | [539bf6ca99](https://linux-hardware.org/?probe=539bf6ca99) | Mar 28, 2020 |
| ASUSTek       | X450CA                      | [0c5e774258](https://linux-hardware.org/?probe=0c5e774258) | Mar 27, 2020 |
| Chuwi         | LapBook SE                  | [f7cfd1b163](https://linux-hardware.org/?probe=f7cfd1b163) | Mar 26, 2020 |
| Dell          | Latitude E5450              | [8a4a9dcec1](https://linux-hardware.org/?probe=8a4a9dcec1) | Mar 24, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [f08c6424b7](https://linux-hardware.org/?probe=f08c6424b7) | Mar 22, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [9fe1bc84d4](https://linux-hardware.org/?probe=9fe1bc84d4) | Mar 22, 2020 |
| Dell          | Inspiron 5490               | [79cbbe0dff](https://linux-hardware.org/?probe=79cbbe0dff) | Mar 20, 2020 |
| Acer          | Aspire 4738Z                | [e34aa3ebf4](https://linux-hardware.org/?probe=e34aa3ebf4) | Mar 14, 2020 |
| Acer          | Aspire 4738Z                | [c898bc3309](https://linux-hardware.org/?probe=c898bc3309) | Mar 13, 2020 |
| Acer          | Aspire 4738Z                | [4895887d9e](https://linux-hardware.org/?probe=4895887d9e) | Mar 13, 2020 |
| Lenovo        | ThinkPad E490s 20NG0002A... | [023e57edf3](https://linux-hardware.org/?probe=023e57edf3) | Mar 11, 2020 |
| Acer          | Swift SF314-56G             | [c62b3c237f](https://linux-hardware.org/?probe=c62b3c237f) | Mar 10, 2020 |
| Dell          | Inspiron 3493               | [23e7a2104b](https://linux-hardware.org/?probe=23e7a2104b) | Mar 09, 2020 |
| ASUSTek       | K43SV                       | [a036dac000](https://linux-hardware.org/?probe=a036dac000) | Mar 06, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [b94b74f6d4](https://linux-hardware.org/?probe=b94b74f6d4) | Mar 05, 2020 |
| Dell          | Latitude 7490               | [d03108116d](https://linux-hardware.org/?probe=d03108116d) | Mar 02, 2020 |
| MSI           | PS42 Modern 8RA             | [ab8a74e1ac](https://linux-hardware.org/?probe=ab8a74e1ac) | Mar 01, 2020 |
| Dell          | Inspiron 5490               | [1d589a5695](https://linux-hardware.org/?probe=1d589a5695) | Feb 24, 2020 |
| MSI           | CX420/CX420 MX              | [f1112049d2](https://linux-hardware.org/?probe=f1112049d2) | Feb 23, 2020 |
| Sony          | SVE11125CVW                 | [bee034816a](https://linux-hardware.org/?probe=bee034816a) | Feb 21, 2020 |
| HP            | EliteBook 2530p             | [55fb907088](https://linux-hardware.org/?probe=55fb907088) | Feb 17, 2020 |
| Dell          | Latitude 7490               | [39de737132](https://linux-hardware.org/?probe=39de737132) | Feb 16, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b41b751782](https://linux-hardware.org/?probe=b41b751782) | Feb 14, 2020 |
| AXIOO         | NEON MNW. SI94B-20+SI96A... | [ad58a21877](https://linux-hardware.org/?probe=ad58a21877) | Feb 11, 2020 |
| HP            | EliteBook 2530p             | [0ffc694ed0](https://linux-hardware.org/?probe=0ffc694ed0) | Feb 08, 2020 |
| Hampoo        | B3W6_NA123C Reserved        | [eaf4701374](https://linux-hardware.org/?probe=eaf4701374) | Feb 08, 2020 |
| HP            | 15                          | [e0d98d2e3d](https://linux-hardware.org/?probe=e0d98d2e3d) | Feb 05, 2020 |
| Lenovo        | ThinkPad T430s 2356GC9      | [08223129d8](https://linux-hardware.org/?probe=08223129d8) | Feb 05, 2020 |
| Hampoo        | B3W6_NA123C Reserved        | [1ca0264090](https://linux-hardware.org/?probe=1ca0264090) | Feb 04, 2020 |
| Hampoo        | B3W6_NA123C Reserved        | [f1d169e079](https://linux-hardware.org/?probe=f1d169e079) | Feb 04, 2020 |
| ASUSTek       | GL503VD                     | [3937c14284](https://linux-hardware.org/?probe=3937c14284) | Feb 02, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [7b9cdcc838](https://linux-hardware.org/?probe=7b9cdcc838) | Jan 29, 2020 |
| HP            | Compaq 6910p                | [b790eb4d3d](https://linux-hardware.org/?probe=b790eb4d3d) | Jan 28, 2020 |
| HP            | Presario C500 (RU924PA#U... | [f22ab20bae](https://linux-hardware.org/?probe=f22ab20bae) | Jan 28, 2020 |
| Dell          | Inspiron 5570               | [997718dc61](https://linux-hardware.org/?probe=997718dc61) | Jan 28, 2020 |
| HP            | Presario C500 (RU924PA#U... | [efe0249933](https://linux-hardware.org/?probe=efe0249933) | Jan 28, 2020 |
| Lenovo        | G40-45 80E1                 | [eeeb376a99](https://linux-hardware.org/?probe=eeeb376a99) | Jan 26, 2020 |
| ASUSTek       | S451LB                      | [0f309bac4f](https://linux-hardware.org/?probe=0f309bac4f) | Jan 24, 2020 |
| Acer          | Aspire 4738Z                | [f6d23a2b44](https://linux-hardware.org/?probe=f6d23a2b44) | Jan 24, 2020 |
| Lenovo        | G50-80 80E5                 | [8beff1830f](https://linux-hardware.org/?probe=8beff1830f) | Jan 24, 2020 |
| Dell          | Inspiron 3580               | [7a1e23b953](https://linux-hardware.org/?probe=7a1e23b953) | Jan 22, 2020 |
| Dell          | Inspiron 3580               | [0f76a113c1](https://linux-hardware.org/?probe=0f76a113c1) | Jan 22, 2020 |
| Acer          | TravelMate B115e            | [5dd85d88a5](https://linux-hardware.org/?probe=5dd85d88a5) | Jan 22, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7075d2c989](https://linux-hardware.org/?probe=7075d2c989) | Jan 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [f1b9fa59ec](https://linux-hardware.org/?probe=f1b9fa59ec) | Jan 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [f766995e7e](https://linux-hardware.org/?probe=f766995e7e) | Jan 16, 2020 |
| Toshiba       | Satellite L55-B             | [67b00cee9e](https://linux-hardware.org/?probe=67b00cee9e) | Jan 15, 2020 |
| Lenovo        | G40-80 80E4                 | [f4e0f183f5](https://linux-hardware.org/?probe=f4e0f183f5) | Jan 10, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | [5ec506d808](https://linux-hardware.org/?probe=5ec506d808) | Jan 09, 2020 |
| Lenovo        | G40-80 80E4                 | [d20a535458](https://linux-hardware.org/?probe=d20a535458) | Jan 09, 2020 |
| Acer          | Aspire E5-553G              | [b2aad899be](https://linux-hardware.org/?probe=b2aad899be) | Jan 02, 2020 |
| Acer          | Aspire E5-553G              | [e694f1b28a](https://linux-hardware.org/?probe=e694f1b28a) | Dec 27, 2019 |
| HP            | Laptop 14-bw0xx             | [47b10cd4f1](https://linux-hardware.org/?probe=47b10cd4f1) | Dec 25, 2019 |
| Acer          | Aspire 4750                 | [94a0b4fab9](https://linux-hardware.org/?probe=94a0b4fab9) | Dec 10, 2019 |
| Lenovo        | G40-45 80E1                 | [a89268fd79](https://linux-hardware.org/?probe=a89268fd79) | Dec 10, 2019 |
| Sony          | SVE14A35CVS                 | [405f4def54](https://linux-hardware.org/?probe=405f4def54) | Dec 01, 2019 |
| Acer          | AO725                       | [0143e45ad7](https://linux-hardware.org/?probe=0143e45ad7) | Nov 19, 2019 |
| Acer          | Aspire E5-475G              | [177939d114](https://linux-hardware.org/?probe=177939d114) | Nov 18, 2019 |
| Acer          | Aspire E5-475G              | [44dd5d0924](https://linux-hardware.org/?probe=44dd5d0924) | Nov 18, 2019 |
| HP            | Laptop 14s-cf1xxx           | [4d0bbf965b](https://linux-hardware.org/?probe=4d0bbf965b) | Nov 07, 2019 |
| HP            | Pavilion 14                 | [80979c9b2c](https://linux-hardware.org/?probe=80979c9b2c) | Oct 27, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [961235a0ff](https://linux-hardware.org/?probe=961235a0ff) | Oct 26, 2019 |
| ASUSTek       | GL553VD                     | [65246f893a](https://linux-hardware.org/?probe=65246f893a) | Oct 24, 2019 |
| Sony          | VPCZ227GG                   | [6e74a95929](https://linux-hardware.org/?probe=6e74a95929) | Oct 23, 2019 |
| ASUSTek       | GL553VD                     | [a97dc59515](https://linux-hardware.org/?probe=a97dc59515) | Oct 22, 2019 |
| ASUSTek       | X450LCP                     | [0f412b6c32](https://linux-hardware.org/?probe=0f412b6c32) | Oct 19, 2019 |
| ASUSTek       | X200MA                      | [ed6cbea554](https://linux-hardware.org/?probe=ed6cbea554) | Oct 14, 2019 |
| ASUSTek       | X450JN                      | [b16321a8a5](https://linux-hardware.org/?probe=b16321a8a5) | Oct 09, 2019 |
| ASUSTek       | X450JN                      | [9745c5a328](https://linux-hardware.org/?probe=9745c5a328) | Oct 09, 2019 |
| ASUSTek       | X200MA                      | [219d395e20](https://linux-hardware.org/?probe=219d395e20) | Oct 08, 2019 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [d5d77d3c0d](https://linux-hardware.org/?probe=d5d77d3c0d) | Oct 07, 2019 |
| Acer          | Aspire 4740                 | [b10fe6845e](https://linux-hardware.org/?probe=b10fe6845e) | Oct 06, 2019 |
| Lenovo        | G40-45 80E1                 | [88db11e321](https://linux-hardware.org/?probe=88db11e321) | Oct 06, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [156a080f13](https://linux-hardware.org/?probe=156a080f13) | Oct 05, 2019 |
| Acer          | Aspire 4750                 | [eb02531024](https://linux-hardware.org/?probe=eb02531024) | Sep 22, 2019 |
| HP            | G42                         | [5b701c891f](https://linux-hardware.org/?probe=5b701c891f) | Sep 18, 2019 |
| Acer          | Aspire 4750                 | [0315d96606](https://linux-hardware.org/?probe=0315d96606) | Sep 04, 2019 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [51c94c839c](https://linux-hardware.org/?probe=51c94c839c) | Aug 28, 2019 |
| ASUSTek       | GL552VXK                    | [facf474182](https://linux-hardware.org/?probe=facf474182) | Aug 28, 2019 |
| ASUSTek       | GL552VXK                    | [4f463b9a07](https://linux-hardware.org/?probe=4f463b9a07) | Aug 26, 2019 |
| Acer          | Aspire 4755                 | [90e4eaf7b2](https://linux-hardware.org/?probe=90e4eaf7b2) | Aug 24, 2019 |
| Acer          | Swift SF314-56G             | [5114f08197](https://linux-hardware.org/?probe=5114f08197) | Aug 24, 2019 |
| ASUSTek       | K43E                        | [8b6fca544b](https://linux-hardware.org/?probe=8b6fca544b) | Aug 24, 2019 |
| Clevo         | M7x0S                       | [6d5922e42c](https://linux-hardware.org/?probe=6d5922e42c) | Aug 23, 2019 |
| HP            | 14                          | [0ebab40d1e](https://linux-hardware.org/?probe=0ebab40d1e) | Aug 19, 2019 |
| Acer          | Swift SF314-56G             | [6410bd1b82](https://linux-hardware.org/?probe=6410bd1b82) | Aug 17, 2019 |
| Panasonic     | CF-Y8FWMCAS                 | [c3f2c78e79](https://linux-hardware.org/?probe=c3f2c78e79) | Aug 16, 2019 |
| Lenovo        | ThinkPad X120e 0611AM2      | [96c790e992](https://linux-hardware.org/?probe=96c790e992) | Aug 16, 2019 |
| Acer          | Aspire E1-410               | [b7d83d359d](https://linux-hardware.org/?probe=b7d83d359d) | Aug 16, 2019 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [e425b40f79](https://linux-hardware.org/?probe=e425b40f79) | Aug 09, 2019 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | [02c5d418e9](https://linux-hardware.org/?probe=02c5d418e9) | Aug 09, 2019 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [a4da95311b](https://linux-hardware.org/?probe=a4da95311b) | Aug 09, 2019 |
| HP            | Notebook                    | [2ec22fa87a](https://linux-hardware.org/?probe=2ec22fa87a) | Jul 25, 2019 |
| HP            | Notebook                    | [3225ed388d](https://linux-hardware.org/?probe=3225ed388d) | Jul 25, 2019 |
| Apple         | MacBook3,1                  | [b7ff730ca4](https://linux-hardware.org/?probe=b7ff730ca4) | Jul 20, 2019 |
| Apple         | MacBook3,1                  | [72555b95bc](https://linux-hardware.org/?probe=72555b95bc) | Jul 20, 2019 |
| Acer          | Aspire E1-451G              | [994ae0cfbf](https://linux-hardware.org/?probe=994ae0cfbf) | Jul 19, 2019 |
| Acer          | Aspire E5-571G              | [6f1f1687b8](https://linux-hardware.org/?probe=6f1f1687b8) | Jul 12, 2019 |
| Lenovo        | ThinkPad X240 20AMS00100    | [fa7155b0e4](https://linux-hardware.org/?probe=fa7155b0e4) | Jul 11, 2019 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [27bb2f0366](https://linux-hardware.org/?probe=27bb2f0366) | Jul 07, 2019 |
| Acer          | Okinawa                     | [ce7e2b4d22](https://linux-hardware.org/?probe=ce7e2b4d22) | Jul 04, 2019 |
| Sony          | VPCZ227GG                   | [9109d4a264](https://linux-hardware.org/?probe=9109d4a264) | Jul 03, 2019 |
| HP            | Laptop 14-cm0xxx            | [908e49b930](https://linux-hardware.org/?probe=908e49b930) | Jun 27, 2019 |
| HP            | Laptop 14-cm0xxx            | [d2d977663d](https://linux-hardware.org/?probe=d2d977663d) | Jun 27, 2019 |
| Acer          | Aspire 4755                 | [b8fb16b9f4](https://linux-hardware.org/?probe=b8fb16b9f4) | Jun 26, 2019 |
| HP            | Laptop 14-cm0xxx            | [eca46a8357](https://linux-hardware.org/?probe=eca46a8357) | Jun 25, 2019 |
| HP            | Laptop 14-cm0xxx            | [a5e8d15902](https://linux-hardware.org/?probe=a5e8d15902) | Jun 25, 2019 |
| ASUSTek       | Zephyrus M GM501GS          | [578f1342d9](https://linux-hardware.org/?probe=578f1342d9) | Jun 17, 2019 |
| Acer          | TravelMate P243             | [47fda1ca09](https://linux-hardware.org/?probe=47fda1ca09) | Jun 15, 2019 |
| Lenovo        | ThinkPad X240 20AMS00100    | [703e5773b1](https://linux-hardware.org/?probe=703e5773b1) | Jun 15, 2019 |
| ASUSTek       | GL503VD                     | [b8be17d96b](https://linux-hardware.org/?probe=b8be17d96b) | Jun 04, 2019 |
| Acer          | AO756                       | [8f2835ae3b](https://linux-hardware.org/?probe=8f2835ae3b) | May 31, 2019 |
| Lenovo        | ThinkPad X240 20AMS00100    | [b20a13a602](https://linux-hardware.org/?probe=b20a13a602) | May 30, 2019 |
| HP            | Presario V3000 (RL377PA#... | [400439715d](https://linux-hardware.org/?probe=400439715d) | May 30, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7420b6037e](https://linux-hardware.org/?probe=7420b6037e) | May 15, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [47e88cfbd1](https://linux-hardware.org/?probe=47e88cfbd1) | May 14, 2019 |
| Acer          | AO532h                      | [26399c140a](https://linux-hardware.org/?probe=26399c140a) | May 13, 2019 |
| Acer          | Aspire 4755                 | [f2b6448161](https://linux-hardware.org/?probe=f2b6448161) | May 13, 2019 |
| Acer          | Aspire 4755                 | [a800461b6d](https://linux-hardware.org/?probe=a800461b6d) | May 13, 2019 |
| ASUSTek       | K42JZ                       | [b2218d3c9f](https://linux-hardware.org/?probe=b2218d3c9f) | May 11, 2019 |
| Toshiba       | PORTEGE M780                | [9f5e64a19a](https://linux-hardware.org/?probe=9f5e64a19a) | May 10, 2019 |
| Toshiba       | PORTEGE M780                | [27436c537b](https://linux-hardware.org/?probe=27436c537b) | May 10, 2019 |
| ASUSTek       | 1215B                       | [31e97aedc6](https://linux-hardware.org/?probe=31e97aedc6) | May 09, 2019 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4adfd3a1c3](https://linux-hardware.org/?probe=4adfd3a1c3) | May 02, 2019 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [90dd7d30ec](https://linux-hardware.org/?probe=90dd7d30ec) | May 02, 2019 |
| HP            | Laptop 14-bs0xx             | [f74ea44f1a](https://linux-hardware.org/?probe=f74ea44f1a) | Apr 21, 2019 |
| HP            | Laptop 14-bs0xx             | [73779c26b3](https://linux-hardware.org/?probe=73779c26b3) | Apr 14, 2019 |
| ASUSTek       | X540NA                      | [21f04e1abe](https://linux-hardware.org/?probe=21f04e1abe) | Apr 11, 2019 |
| HP            | Laptop 14s-cf0xxx           | [46a39369f4](https://linux-hardware.org/?probe=46a39369f4) | Apr 09, 2019 |
| ASUSTek       | X456URK                     | [5fa130cbb4](https://linux-hardware.org/?probe=5fa130cbb4) | Apr 01, 2019 |
| Acer          | Aspire E1-451G              | [3631187d23](https://linux-hardware.org/?probe=3631187d23) | Mar 31, 2019 |
| ASUSTek       | X455LA                      | [c019eb486b](https://linux-hardware.org/?probe=c019eb486b) | Mar 24, 2019 |
| HP            | 1000                        | [b813049f31](https://linux-hardware.org/?probe=b813049f31) | Mar 03, 2019 |
| Lenovo        | G400 20235                  | [cd3d7d1c40](https://linux-hardware.org/?probe=cd3d7d1c40) | Feb 23, 2019 |
| Lenovo        | G400 20235                  | [2ca2f87846](https://linux-hardware.org/?probe=2ca2f87846) | Feb 23, 2019 |
| HP            | Laptop 14-bs0xx             | [82b35c05bb](https://linux-hardware.org/?probe=82b35c05bb) | Feb 15, 2019 |
| HP            | Laptop 14-bs0xx             | [520eb1f482](https://linux-hardware.org/?probe=520eb1f482) | Jan 27, 2019 |
| ASUSTek       | K43TA                       | [811cc55c64](https://linux-hardware.org/?probe=811cc55c64) | Jan 06, 2019 |
| ASUSTek       | X455LAB                     | [6952701375](https://linux-hardware.org/?probe=6952701375) | Jan 05, 2019 |
| ASUSTek       | X441UV                      | [82144bfe29](https://linux-hardware.org/?probe=82144bfe29) | Dec 30, 2018 |
| ASUSTek       | X441UV                      | [32b213b99f](https://linux-hardware.org/?probe=32b213b99f) | Dec 29, 2018 |
| ASUSTek       | X441UV                      | [93dd582dab](https://linux-hardware.org/?probe=93dd582dab) | Dec 29, 2018 |
| ASUSTek       | X550IU                      | [7e184779a7](https://linux-hardware.org/?probe=7e184779a7) | Dec 16, 2018 |
| Lenovo        | ThinkPad E420 11417NA       | [4b07a8c051](https://linux-hardware.org/?probe=4b07a8c051) | Oct 04, 2018 |
| Lenovo        | ThinkPad E420 11417NA       | [9d5fad95db](https://linux-hardware.org/?probe=9d5fad95db) | Aug 22, 2018 |
| ASUSTek       | S451LB                      | [ba8f3b9a74](https://linux-hardware.org/?probe=ba8f3b9a74) | May 17, 2018 |
| HP            | Notebook                    | [a6ecdfef67](https://linux-hardware.org/?probe=a6ecdfef67) | Aug 14, 2017 |
| Dell          | Vostro 1014                 | [6006f3386e](https://linux-hardware.org/?probe=6006f3386e) | Jul 22, 2017 |
| Lenovo        | ThinkPad Edge E445 20B1A... | [66cb77a61b](https://linux-hardware.org/?probe=66cb77a61b) | Apr 17, 2017 |
| ASUSTek       | N53SV                       | [bc8d639ebe](https://linux-hardware.org/?probe=bc8d639ebe) | Mar 29, 2017 |
| Apple         | MacBookPro12,1              | [322a47ba97](https://linux-hardware.org/?probe=322a47ba97) | Mar 10, 2017 |
| HP            | 14                          | [645b644da7](https://linux-hardware.org/?probe=645b644da7) | Oct 31, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 97        | 15.23%  |
| Ubuntu 18.04                 | 59        | 9.26%   |
| OpenMandriva 4.3             | 27        | 4.24%   |
| OpenMandriva 4.2             | 23        | 3.61%   |
| Arch                         | 16        | 2.51%   |
| Pop!_OS 20.04                | 14        | 2.2%    |
| Zorin 15                     | 13        | 2.04%   |
| Ubuntu 22.04                 | 12        | 1.88%   |
| Ubuntu 19.10                 | 12        | 1.88%   |
| KDE neon 20.04               | 12        | 1.88%   |
| Fedora 35                    | 12        | 1.88%   |
| Manjaro                      | 11        | 1.73%   |
| Fedora 36                    | 11        | 1.73%   |
| Ubuntu 21.10                 | 10        | 1.57%   |
| Linux Mint 20.3              | 9         | 1.41%   |
| Arch Rolling                 | 9         | 1.41%   |
| Xubuntu 20.04                | 8         | 1.26%   |
| Linux Mint 19.3              | 8         | 1.26%   |
| Kubuntu 20.04                | 8         | 1.26%   |
| Pop!_OS 21.04                | 7         | 1.1%    |
| Elementary 6.1               | 7         | 1.1%    |
| Debian 11                    | 7         | 1.1%    |
| ArcoLinux Rolling            | 7         | 1.1%    |
| Ubuntu 21.04                 | 6         | 0.94%   |
| Ubuntu 19.04                 | 6         | 0.94%   |
| Ubuntu 16.04                 | 6         | 0.94%   |
| Linux Mint 20.2              | 6         | 0.94%   |
| Fedora 34                    | 6         | 0.94%   |
| Fedora 32                    | 6         | 0.94%   |
| Debian 10                    | 6         | 0.94%   |
| Zorin 16                     | 5         | 0.78%   |
| Xubuntu 18.04                | 5         | 0.78%   |
| Linux Mint 20                | 5         | 0.78%   |
| Fedora 33                    | 5         | 0.78%   |
| EndeavourOS Rolling          | 5         | 0.78%   |
| Elementary 5.1.7             | 5         | 0.78%   |
| Pop!_OS 20.10                | 4         | 0.63%   |
| Linux Mint 20.1              | 4         | 0.63%   |
| Zorin 12                     | 3         | 0.47%   |
| Ubuntu MATE 20.04            | 3         | 0.47%   |
| ROSA R9                      | 3         | 0.47%   |
| Manjaro 18.1.5               | 3         | 0.47%   |
| Lubuntu 20.04                | 3         | 0.47%   |
| LMDE 4                       | 3         | 0.47%   |
| Kali 2022.2                  | 3         | 0.47%   |
| Kali 2020.4                  | 3         | 0.47%   |
| Endless 3.5.7                | 3         | 0.47%   |
| Elementary 6                 | 3         | 0.47%   |
| Xubuntu 22.04                | 2         | 0.31%   |
| Ubuntu Budgie 20.04          | 2         | 0.31%   |
| Ubuntu 20.10                 | 2         | 0.31%   |
| Solus 4.1                    | 2         | 0.31%   |
| ROSA R8.1                    | 2         | 0.31%   |
| ROSA R10                     | 2         | 0.31%   |
| Pop!_OS 21.10                | 2         | 0.31%   |
| Parrot 4.8                   | 2         | 0.31%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.31%   |
| Manjaro 21.1.0               | 2         | 0.31%   |
| Manjaro 20.2.1               | 2         | 0.31%   |
| Manjaro 20.2                 | 2         | 0.31%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 199       | 32.73%  |
| OpenMandriva  | 50        | 8.22%   |
| Fedora        | 39        | 6.41%   |
| Manjaro       | 32        | 5.26%   |
| Linux Mint    | 30        | 4.93%   |
| Pop!_OS       | 27        | 4.44%   |
| Arch          | 26        | 4.28%   |
| Zorin         | 21        | 3.45%   |
| Elementary    | 20        | 3.29%   |
| Xubuntu       | 18        | 2.96%   |
| Kubuntu       | 17        | 2.8%    |
| Endless       | 16        | 2.63%   |
| Debian        | 16        | 2.63%   |
| KDE neon      | 14        | 2.3%    |
| Kali          | 10        | 1.64%   |
| ROSA          | 8         | 1.32%   |
| ArcoLinux     | 8         | 1.32%   |
| Lubuntu       | 7         | 1.15%   |
| EndeavourOS   | 5         | 0.82%   |
| Ubuntu MATE   | 4         | 0.66%   |
| Parrot        | 4         | 0.66%   |
| Deepin        | 4         | 0.66%   |
| Artix         | 4         | 0.66%   |
| LMDE          | 3         | 0.49%   |
| Ubuntu Budgie | 2         | 0.33%   |
| Solus         | 2         | 0.33%   |
| openSUSE      | 2         | 0.33%   |
| Gentoo        | 2         | 0.33%   |
| Clear Linux   | 2         | 0.33%   |
| Chrome OS     | 2         | 0.33%   |
| CentOS        | 2         | 0.33%   |
| BlackPanther  | 2         | 0.33%   |
| Void Linux    | 1         | 0.16%   |
| UbuntuDDE     | 1         | 0.16%   |
| Trisquel      | 1         | 0.16%   |
| Pear OS       | 1         | 0.16%   |
| NST           | 1         | 0.16%   |
| MX            | 1         | 0.16%   |
| Mageia        | 1         | 0.16%   |
| Garuda Linux  | 1         | 0.16%   |
| Devuan        | 1         | 0.16%   |
| Archcraft     | 1         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 27        | 4%      |
| 5.10.14-desktop-1omv4002 | 23        | 3.41%   |
| 5.4.0-42-generic         | 16        | 2.37%   |
| 5.4.0-26-generic         | 11        | 1.63%   |
| 5.4.0-52-generic         | 9         | 1.33%   |
| 5.0.0-25-generic         | 8         | 1.19%   |
| 4.18.0-15-generic        | 8         | 1.19%   |
| 5.4.0-58-generic         | 7         | 1.04%   |
| 5.4.0-54-generic         | 7         | 1.04%   |
| 5.11.0-37-generic        | 7         | 1.04%   |
| 5.8.0-48-generic         | 6         | 0.89%   |
| 5.3.0-46-generic         | 6         | 0.89%   |
| 5.8.0-41-generic         | 5         | 0.74%   |
| 5.4.0-80-generic         | 5         | 0.74%   |
| 5.4.0-45-generic         | 5         | 0.74%   |
| 5.15.0-41-generic        | 5         | 0.74%   |
| 5.11.0-7620-generic      | 5         | 0.74%   |
| 5.11.0-40-generic        | 5         | 0.74%   |
| 5.0.0-23-generic         | 5         | 0.74%   |
| 5.4.0-7634-generic       | 4         | 0.59%   |
| 5.4.0-33-generic         | 4         | 0.59%   |
| 5.3.0-26-generic         | 4         | 0.59%   |
| 5.11.0-41-generic        | 4         | 0.59%   |
| 5.11.0-38-generic        | 4         | 0.59%   |
| 5.11.0-35-generic        | 4         | 0.59%   |
| 5.11.0-27-generic        | 4         | 0.59%   |
| 5.0.0-37-generic         | 4         | 0.59%   |
| 5.0.0-20-generic         | 4         | 0.59%   |
| 5.8.0-63-generic         | 3         | 0.44%   |
| 5.8.0-59-generic         | 3         | 0.44%   |
| 5.8.0-55-generic         | 3         | 0.44%   |
| 5.8.0-50-generic         | 3         | 0.44%   |
| 5.8.0-38-generic         | 3         | 0.44%   |
| 5.8.0-14-generic         | 3         | 0.44%   |
| 5.4.0-91-generic         | 3         | 0.44%   |
| 5.4.0-65-generic         | 3         | 0.44%   |
| 5.4.0-48-generic         | 3         | 0.44%   |
| 5.4.0-47-generic         | 3         | 0.44%   |
| 5.4.0-37-generic         | 3         | 0.44%   |
| 5.4.0-31-generic         | 3         | 0.44%   |
| 5.3.0-42-generic         | 3         | 0.44%   |
| 5.3.0-40-generic         | 3         | 0.44%   |
| 5.17.6-300.fc36.x86_64   | 3         | 0.44%   |
| 5.15.0-40-generic        | 3         | 0.44%   |
| 5.15.0-39-generic        | 3         | 0.44%   |
| 5.13.0-7620-generic      | 3         | 0.44%   |
| 5.13.0-30-generic        | 3         | 0.44%   |
| 5.13.0-28-generic        | 3         | 0.44%   |
| 5.13.0-27-generic        | 3         | 0.44%   |
| 5.11.0-7612-generic      | 3         | 0.44%   |
| 5.11.0-25-generic        | 3         | 0.44%   |
| 5.10.53-1-MANJARO        | 3         | 0.44%   |
| 5.0.0-32-generic         | 3         | 0.44%   |
| 4.15.0-76-generic        | 3         | 0.44%   |
| 5.9.11-3-MANJARO         | 2         | 0.3%    |
| 5.9.10-200.fc33.x86_64   | 2         | 0.3%    |
| 5.9.1-arch1-1            | 2         | 0.3%    |
| 5.8.5-arch1-1            | 2         | 0.3%    |
| 5.8.0-7642-generic       | 2         | 0.3%    |
| 5.8.0-7630-generic       | 2         | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 126       | 19.27%  |
| 5.11.0  | 50        | 7.65%   |
| 5.8.0   | 41        | 6.27%   |
| 5.3.0   | 33        | 5.05%   |
| 5.13.0  | 32        | 4.89%   |
| 5.0.0   | 30        | 4.59%   |
| 5.16.7  | 28        | 4.28%   |
| 4.15.0  | 28        | 4.28%   |
| 5.10.14 | 24        | 3.67%   |
| 5.15.0  | 20        | 3.06%   |
| 4.18.0  | 17        | 2.6%    |
| 5.10.0  | 12        | 1.83%   |
| 4.19.0  | 11        | 1.68%   |
| 5.16.0  | 6         | 0.92%   |
| 5.17.5  | 5         | 0.76%   |
| 5.15.12 | 4         | 0.61%   |
| 5.14.16 | 4         | 0.61%   |
| 5.9.11  | 3         | 0.46%   |
| 5.9.1   | 3         | 0.46%   |
| 5.17.6  | 3         | 0.46%   |
| 5.16.12 | 3         | 0.46%   |
| 5.14.0  | 3         | 0.46%   |
| 5.11.11 | 3         | 0.46%   |
| 5.10.53 | 3         | 0.46%   |
| 4.9.20  | 3         | 0.46%   |
| 4.4.0   | 3         | 0.46%   |
| 5.9.10  | 2         | 0.31%   |
| 5.8.5   | 2         | 0.31%   |
| 5.8.3   | 2         | 0.31%   |
| 5.8.12  | 2         | 0.31%   |
| 5.7.7   | 2         | 0.31%   |
| 5.5.7   | 2         | 0.31%   |
| 5.5.10  | 2         | 0.31%   |
| 5.18.7  | 2         | 0.31%   |
| 5.18.5  | 2         | 0.31%   |
| 5.18.14 | 2         | 0.31%   |
| 5.17.9  | 2         | 0.31%   |
| 5.17.7  | 2         | 0.31%   |
| 5.17.0  | 2         | 0.31%   |
| 5.16.19 | 2         | 0.31%   |
| 5.16.14 | 2         | 0.31%   |
| 5.15.32 | 2         | 0.31%   |
| 5.15.13 | 2         | 0.31%   |
| 5.15.11 | 2         | 0.31%   |
| 5.14.8  | 2         | 0.31%   |
| 5.14.11 | 2         | 0.31%   |
| 5.13.12 | 2         | 0.31%   |
| 5.12.13 | 2         | 0.31%   |
| 5.10.5  | 2         | 0.31%   |
| 5.10.49 | 2         | 0.31%   |
| 5.10.4  | 2         | 0.31%   |
| 5.10.16 | 2         | 0.31%   |
| 5.10.11 | 2         | 0.31%   |
| 4.9.60  | 2         | 0.31%   |
| 4.19.69 | 2         | 0.31%   |
| 4.18.16 | 2         | 0.31%   |
| 4.13.0  | 2         | 0.31%   |
| 4.10.0  | 2         | 0.31%   |
| 5.9.4   | 1         | 0.15%   |
| 5.9.2   | 1         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 134       | 20.78%  |
| 5.10    | 59        | 9.15%   |
| 5.11    | 53        | 8.22%   |
| 5.8     | 52        | 8.06%   |
| 5.16    | 46        | 7.13%   |
| 5.15    | 36        | 5.58%   |
| 5.13    | 36        | 5.58%   |
| 5.3     | 35        | 5.43%   |
| 5.0     | 32        | 4.96%   |
| 4.15    | 28        | 4.34%   |
| 4.18    | 20        | 3.1%    |
| 5.17    | 17        | 2.64%   |
| 5.14    | 16        | 2.48%   |
| 4.19    | 16        | 2.48%   |
| 5.9     | 12        | 1.86%   |
| 5.18    | 9         | 1.4%    |
| 5.6     | 7         | 1.09%   |
| 4.9     | 7         | 1.09%   |
| 5.12    | 6         | 0.93%   |
| 5.7     | 5         | 0.78%   |
| 5.5     | 5         | 0.78%   |
| 4.4     | 4         | 0.62%   |
| 5.2     | 2         | 0.31%   |
| 4.13    | 2         | 0.31%   |
| 4.10    | 2         | 0.31%   |
| 4.1     | 2         | 0.31%   |
| 5       | 1         | 0.16%   |
| 3.16    | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 569       | 96.77%  |
| i686   | 19        | 3.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 252       | 41.45%  |
| KDE5            | 100       | 16.45%  |
| Unknown         | 70        | 11.51%  |
| XFCE            | 53        | 8.72%   |
| X-Cinnamon      | 30        | 4.93%   |
| Pantheon        | 19        | 3.13%   |
| KDE             | 18        | 2.96%   |
| MATE            | 15        | 2.47%   |
| Cinnamon        | 8         | 1.32%   |
| LXQt            | 7         | 1.15%   |
| Deepin          | 5         | 0.82%   |
| Budgie          | 5         | 0.82%   |
| Unity           | 4         | 0.66%   |
| sway            | 3         | 0.49%   |
| KDE4            | 3         | 0.49%   |
| i3              | 3         | 0.49%   |
| qtile           | 2         | 0.33%   |
| ICEWM           | 2         | 0.33%   |
| bspwm           | 2         | 0.33%   |
| xmonad          | 1         | 0.16%   |
| openbox         | 1         | 0.16%   |
| Lubuntu         | 1         | 0.16%   |
| GNOME Flashback | 1         | 0.16%   |
| DWM             | 1         | 0.16%   |
| Cutefish        | 1         | 0.16%   |
| awesomeminimal  | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 490       | 81.8%   |
| Wayland | 61        | 10.18%  |
| Unknown | 46        | 7.68%   |
| Tty     | 2         | 0.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 298       | 48.85%  |
| SDDM    | 103       | 16.89%  |
| GDM     | 95        | 15.57%  |
| LightDM | 51        | 8.36%   |
| TDM     | 29        | 4.75%   |
| GDM3    | 27        | 4.43%   |
| KDM     | 3         | 0.49%   |
| SLiM    | 2         | 0.33%   |
| Ly      | 1         | 0.16%   |
| LXDM    | 1         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 467       | 78.09%  |
| Unknown | 73        | 12.21%  |
| id_ID   | 42        | 7.02%   |
| en_GB   | 7         | 1.17%   |
| C       | 4         | 0.67%   |
| jv_ID   | 1         | 0.17%   |
| en_SG   | 1         | 0.17%   |
| en_IN   | 1         | 0.17%   |
| en_AU   | 1         | 0.17%   |
| de_CH   | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 338       | 56.15%  |
| BIOS | 264       | 43.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 466       | 77.93%  |
| Btrfs   | 52        | 8.7%    |
| Overlay | 44        | 7.36%   |
| Unknown | 25        | 4.18%   |
| Xfs     | 3         | 0.5%    |
| Ext2    | 3         | 0.5%    |
| Zfs     | 2         | 0.33%   |
| Ext3    | 2         | 0.33%   |
| F2fs    | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 318       | 53.18%  |
| GPT     | 198       | 33.11%  |
| MBR     | 82        | 13.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 521       | 87.56%  |
| Yes       | 74        | 12.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 330       | 54.91%  |
| Yes       | 271       | 45.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 145       | 24.66%  |
| ASUSTek Computer    | 136       | 23.13%  |
| Hewlett-Packard     | 93        | 15.82%  |
| Acer                | 85        | 14.46%  |
| Dell                | 45        | 7.65%   |
| Toshiba             | 19        | 3.23%   |
| MSI                 | 14        | 2.38%   |
| Apple               | 11        | 1.87%   |
| Sony                | 8         | 1.36%   |
| Fujitsu             | 7         | 1.19%   |
| AXIOO               | 5         | 0.85%   |
| Clevo               | 3         | 0.51%   |
| Samsung Electronics | 2         | 0.34%   |
| HUAWEI              | 2         | 0.34%   |
| Gigabyte Technology | 2         | 0.34%   |
| Unknown             | 2         | 0.34%   |
| Timi                | 1         | 0.17%   |
| Sole                | 1         | 0.17%   |
| Phoenix/SiS         | 1         | 0.17%   |
| Panasonic           | 1         | 0.17%   |
| Notebook            | 1         | 0.17%   |
| Infinix             | 1         | 0.17%   |
| Hampoo              | 1         | 0.17%   |
| Compal              | 1         | 0.17%   |
| Chuwi               | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G40-45 80E1                       | 9         | 1.53%   |
| HP Notebook                              | 8         | 1.36%   |
| Lenovo IdeaPad 330-14AST 81D5            | 6         | 1.02%   |
| HP Pavilion Aero Laptop 13-be0xxx        | 6         | 1.02%   |
| Acer Aspire 4752                         | 6         | 1.02%   |
| Lenovo IdeaPad S340-14API 81NB           | 5         | 0.85%   |
| Lenovo G400 20235                        | 5         | 0.85%   |
| HP Pavilion g4                           | 5         | 0.85%   |
| HP 14                                    | 5         | 0.85%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA  | 5         | 0.85%   |
| Apple MacBookPro12,1                     | 5         | 0.85%   |
| HP Pavilion 14                           | 4         | 0.68%   |
| HP Laptop 14-bw0xx                       | 4         | 0.68%   |
| HP Laptop 14-bs0xx                       | 4         | 0.68%   |
| HP 1000                                  | 4         | 0.68%   |
| ASUS X455YA                              | 4         | 0.68%   |
| Acer Aspire E5-475G                      | 4         | 0.68%   |
| Acer Aspire 4750                         | 4         | 0.68%   |
| Unknown                                  | 4         | 0.68%   |
| Lenovo IdeaPad 320-14AST 80XU            | 3         | 0.51%   |
| Lenovo G400s 20244                       | 3         | 0.51%   |
| HP Laptop 14-cm0xxx                      | 3         | 0.51%   |
| ASUS X450EA                              | 3         | 0.51%   |
| ASUS X442URR                             | 3         | 0.51%   |
| ASUS X200MA                              | 3         | 0.51%   |
| ASUS VivoBook_ASUSLaptop X412DA_A412DA   | 3         | 0.51%   |
| ASUS K43E                                | 3         | 0.51%   |
| ASUS GL553VD                             | 3         | 0.51%   |
| Acer Swift SF314-56G                     | 3         | 0.51%   |
| Acer Swift SF314-41                      | 3         | 0.51%   |
| Acer Nitro AN515-52                      | 3         | 0.51%   |
| Acer Aspire A315-41                      | 3         | 0.51%   |
| Acer Aspire 4732Z                        | 3         | 0.51%   |
| Lenovo V330-14IKB 81B0                   | 2         | 0.34%   |
| Lenovo V310-14ISK 80SX                   | 2         | 0.34%   |
| Lenovo ThinkPad X240 20AMS0PB11          | 2         | 0.34%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BS002BAU | 2         | 0.34%   |
| Lenovo ThinkBook 14 G3 ACL 21A2          | 2         | 0.34%   |
| Lenovo IdeaPad Z460 20059                | 2         | 0.34%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 2         | 0.34%   |
| Lenovo IdeaPad 330-14IKB 81G2            | 2         | 0.34%   |
| Lenovo IdeaPad 320-14ISK 80XG            | 2         | 0.34%   |
| Lenovo IdeaPad 3 14IIL05 81WD            | 2         | 0.34%   |
| Lenovo IdeaPad 100-14IBD 80RK            | 2         | 0.34%   |
| Lenovo G50-80 80E5                       | 2         | 0.34%   |
| Lenovo G40-30 80FY                       | 2         | 0.34%   |
| HUAWEI BOHK-WAX9X                        | 2         | 0.34%   |
| HP Laptop 15-bw0xx                       | 2         | 0.34%   |
| HP Laptop 14s-dk0xxx                     | 2         | 0.34%   |
| HP Laptop 14s-cf3xxx                     | 2         | 0.34%   |
| HP G42                                   | 2         | 0.34%   |
| HP EliteBook 840 G1                      | 2         | 0.34%   |
| HP EliteBook 2570p                       | 2         | 0.34%   |
| HP EliteBook 2560p                       | 2         | 0.34%   |
| Dell Vostro 5470                         | 2         | 0.34%   |
| Dell Vostro 14-3468                      | 2         | 0.34%   |
| Dell Latitude E7250                      | 2         | 0.34%   |
| Dell Latitude E7240                      | 2         | 0.34%   |
| Dell Latitude E6440                      | 2         | 0.34%   |
| Dell Latitude E6230                      | 2         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 55        | 9.35%   |
| Acer Aspire        | 53        | 9.01%   |
| Lenovo ThinkPad    | 47        | 7.99%   |
| HP Laptop          | 23        | 3.91%   |
| ASUS VivoBook      | 23        | 3.91%   |
| HP Pavilion        | 22        | 3.74%   |
| Dell Latitude      | 19        | 3.23%   |
| Toshiba Satellite  | 13        | 2.21%   |
| Dell Inspiron      | 11        | 1.87%   |
| Acer Swift         | 11        | 1.87%   |
| HP EliteBook       | 10        | 1.7%    |
| Lenovo G40-45      | 9         | 1.53%   |
| Dell Vostro        | 9         | 1.53%   |
| HP Notebook        | 8         | 1.36%   |
| Acer Nitro         | 7         | 1.19%   |
| Lenovo ThinkBook   | 6         | 1.02%   |
| ASUS TUF           | 6         | 1.02%   |
| Lenovo G400        | 5         | 0.85%   |
| HP ProBook         | 5         | 0.85%   |
| HP 14              | 5         | 0.85%   |
| Apple MacBookPro12 | 5         | 0.85%   |
| Toshiba PORTEGE    | 4         | 0.68%   |
| MSI Modern         | 4         | 0.68%   |
| Lenovo Yoga        | 4         | 0.68%   |
| HP 1000            | 4         | 0.68%   |
| ASUS X455YA        | 4         | 0.68%   |
| Unknown            | 4         | 0.68%   |
| Lenovo Legion      | 3         | 0.51%   |
| Lenovo G400s       | 3         | 0.51%   |
| HP ENVY            | 3         | 0.51%   |
| AXIOO NEON         | 3         | 0.51%   |
| ASUS ZenBook       | 3         | 0.51%   |
| ASUS X450EA        | 3         | 0.51%   |
| ASUS X442URR       | 3         | 0.51%   |
| ASUS X200MA        | 3         | 0.51%   |
| ASUS ROG           | 3         | 0.51%   |
| ASUS K43E          | 3         | 0.51%   |
| ASUS GL553VD       | 3         | 0.51%   |
| MSI GL65           | 2         | 0.34%   |
| Lenovo V330-14IKB  | 2         | 0.34%   |
| Lenovo V310-14ISK  | 2         | 0.34%   |
| Lenovo G50-80      | 2         | 0.34%   |
| Lenovo G40-30      | 2         | 0.34%   |
| HUAWEI BOHK-WAX9X  | 2         | 0.34%   |
| HP ZBook           | 2         | 0.34%   |
| HP Presario        | 2         | 0.34%   |
| HP G42             | 2         | 0.34%   |
| HP Compaq          | 2         | 0.34%   |
| Fujitsu LIFEBOOK   | 2         | 0.34%   |
| Dell XPS           | 2         | 0.34%   |
| Clevo M7x0S        | 2         | 0.34%   |
| AXIOO Mybook       | 2         | 0.34%   |
| ASUS X550ZE        | 2         | 0.34%   |
| ASUS X456URK       | 2         | 0.34%   |
| ASUS X456UQK       | 2         | 0.34%   |
| ASUS X455LAB       | 2         | 0.34%   |
| ASUS X453SA        | 2         | 0.34%   |
| ASUS X450LCP       | 2         | 0.34%   |
| ASUS X450CP        | 2         | 0.34%   |
| ASUS X450CC        | 2         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 66        | 11.22%  |
| 2019 | 65        | 11.05%  |
| 2018 | 64        | 10.88%  |
| 2011 | 58        | 9.86%   |
| 2012 | 53        | 9.01%   |
| 2014 | 45        | 7.65%   |
| 2017 | 39        | 6.63%   |
| 2015 | 37        | 6.29%   |
| 2016 | 33        | 5.61%   |
| 2020 | 32        | 5.44%   |
| 2021 | 29        | 4.93%   |
| 2010 | 26        | 4.42%   |
| 2009 | 17        | 2.89%   |
| 2008 | 14        | 2.38%   |
| 2007 | 7         | 1.19%   |
| 2006 | 3         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 588       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 539       | 90.74%  |
| Enabled  | 55        | 9.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 588       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 191       | 32.26%  |
| 3.01-4.0    | 163       | 27.53%  |
| 8.01-16.0   | 93        | 15.71%  |
| 16.01-24.0  | 62        | 10.47%  |
| 1.01-2.0    | 59        | 9.97%   |
| 2.01-3.0    | 9         | 1.52%   |
| 32.01-64.0  | 6         | 1.01%   |
| 0.51-1.0    | 5         | 0.84%   |
| 24.01-32.0  | 3         | 0.51%   |
| 64.01-256.0 | 1         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 240       | 37.62%  |
| 2.01-3.0  | 185       | 29%     |
| 3.01-4.0  | 86        | 13.48%  |
| 4.01-8.0  | 73        | 11.44%  |
| 0.51-1.0  | 39        | 6.11%   |
| 8.01-16.0 | 11        | 1.72%   |
| 0.01-0.5  | 4         | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 427       | 71.52%  |
| 2      | 150       | 25.13%  |
| 3      | 14        | 2.35%   |
| 0      | 4         | 0.67%   |
| 4      | 2         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 350       | 59.12%  |
| Yes       | 242       | 40.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 499       | 84.72%  |
| No        | 90        | 15.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 579       | 98.3%   |
| No        | 10        | 1.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 450       | 76.4%   |
| No        | 139       | 23.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Indonesia | 588       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Jakarta             | 172       | 27.17%  |
| Surabaya            | 77        | 12.16%  |
| Bandung             | 46        | 7.27%   |
| Bogor               | 25        | 3.95%   |
| Semarang            | 23        | 3.63%   |
| Yogyakarta          | 21        | 3.32%   |
| Bekasi              | 15        | 2.37%   |
| Tangerang           | 13        | 2.05%   |
| Denpasar            | 13        | 2.05%   |
| Makassar            | 12        | 1.9%    |
| Malang              | 11        | 1.74%   |
| South Tangerang     | 10        | 1.58%   |
| Medan               | 9         | 1.42%   |
| Palembang           | 8         | 1.26%   |
| Blitar              | 6         | 0.95%   |
| Banda Aceh          | 6         | 0.95%   |
| Tasikmalaya         | 5         | 0.79%   |
| Surakarta           | 5         | 0.79%   |
| Samarinda           | 5         | 0.79%   |
| Pontianak           | 5         | 0.79%   |
| Depok               | 5         | 0.79%   |
| Brebes              | 5         | 0.79%   |
| Banjarmasin         | 5         | 0.79%   |
| Sleman              | 4         | 0.63%   |
| Mataram             | 4         | 0.63%   |
| Gresik              | 4         | 0.63%   |
| Cirebon             | 4         | 0.63%   |
| Pekan Baru          | 3         | 0.47%   |
| Magelang            | 3         | 0.47%   |
| Kediri              | 3         | 0.47%   |
| Batam               | 3         | 0.47%   |
| Balikpapan          | 3         | 0.47%   |
| Wonosari            | 2         | 0.32%   |
| Tegal               | 2         | 0.32%   |
| Purworejo           | 2         | 0.32%   |
| Purwokerto          | 2         | 0.32%   |
| Pegangsaan Dua      | 2         | 0.32%   |
| Jepara              | 2         | 0.32%   |
| Jember              | 2         | 0.32%   |
| Jatimulya           | 2         | 0.32%   |
| Demak               | 2         | 0.32%   |
| Ciapus              | 2         | 0.32%   |
| Cempaka Baru        | 2         | 0.32%   |
| Buaran              | 2         | 0.32%   |
| Bengkulu            | 2         | 0.32%   |
| Bantabantaeng       | 2         | 0.32%   |
| Wonogiri            | 1         | 0.16%   |
| Wates               | 1         | 0.16%   |
| Tenggarong          | 1         | 0.16%   |
| Tanjung Pinang      | 1         | 0.16%   |
| Tanjung Balai       | 1         | 0.16%   |
| Sukabumi            | 1         | 0.16%   |
| Sragen              | 1         | 0.16%   |
| South Jakarta       | 1         | 0.16%   |
| Sidoarjo            | 1         | 0.16%   |
| Sawunggaling        | 1         | 0.16%   |
| Sanur               | 1         | 0.16%   |
| Rintis              | 1         | 0.16%   |
| Purwakarta          | 1         | 0.16%   |
| Pugeran Maguwoharjo | 1         | 0.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 135       | 171    | 18.32%  |
| WDC                   | 100       | 117    | 13.57%  |
| Toshiba               | 78        | 84     | 10.58%  |
| Samsung Electronics   | 67        | 87     | 9.09%   |
| HGST                  | 47        | 51     | 6.38%   |
| Hitachi               | 33        | 39     | 4.48%   |
| Unknown               | 25        | 31     | 3.39%   |
| Kingston              | 24        | 31     | 3.26%   |
| Intel                 | 24        | 38     | 3.26%   |
| SanDisk               | 20        | 29     | 2.71%   |
| V-GeN                 | 16        | 16     | 2.17%   |
| SK hynix              | 15        | 17     | 2.04%   |
| A-DATA Technology     | 15        | 15     | 2.04%   |
| Micron Technology     | 13        | 14     | 1.76%   |
| Fujitsu               | 10        | 11     | 1.36%   |
| JMicron Technology    | 8         | 9      | 1.09%   |
| MidasForce            | 7         | 8      | 0.95%   |
| Apple                 | 7         | 8      | 0.95%   |
| Apacer                | 7         | 7      | 0.95%   |
| Crucial               | 6         | 7      | 0.81%   |
| China                 | 6         | 6      | 0.81%   |
| Unknown               | 6         | 6      | 0.81%   |
| Team                  | 5         | 8      | 0.68%   |
| Patriot               | 5         | 7      | 0.68%   |
| Silicon Motion        | 4         | 5      | 0.54%   |
| RX7                   | 3         | 3      | 0.41%   |
| Pioneer               | 3         | 3      | 0.41%   |
| LITEONIT              | 3         | 3      | 0.41%   |
| LITEON                | 3         | 4      | 0.41%   |
| Transcend             | 2         | 3      | 0.27%   |
| Realtek Semiconductor | 2         | 2      | 0.27%   |
| Phison                | 2         | 2      | 0.27%   |
| Lexar                 | 2         | 2      | 0.27%   |
| KIOXIA                | 2         | 2      | 0.27%   |
| HUAWEI                | 2         | 2      | 0.27%   |
| GALAX                 | 2         | 2      | 0.27%   |
| Corsair               | 2         | 2      | 0.27%   |
| XSTAR                 | 1         | 1      | 0.14%   |
| WellcommMaster        | 1         | 1      | 0.14%   |
| Vaseky                | 1         | 2      | 0.14%   |
| Varro                 | 1         | 1      | 0.14%   |
| Union Memory          | 1         | 1      | 0.14%   |
| UMIS                  | 1         | 2      | 0.14%   |
| TO Exter              | 1         | 1      | 0.14%   |
| SPCC                  | 1         | 1      | 0.14%   |
| SNX                   | 1         | 1      | 0.14%   |
| Smart                 | 1         | 1      | 0.14%   |
| SDVPSA18              | 1         | 1      | 0.14%   |
| Realtek               | 1         | 1      | 0.14%   |
| PNY                   | 1         | 1      | 0.14%   |
| OSCOO                 | 1         | 1      | 0.14%   |
| OSC                   | 1         | 1      | 0.14%   |
| NGFF                  | 1         | 1      | 0.14%   |
| Memory                | 1         | 1      | 0.14%   |
| Lenovo                | 1         | 1      | 0.14%   |
| KingDian              | 1         | 1      | 0.14%   |
| HGST HTS              | 1         | 3      | 0.14%   |
| Hewlett-Packard       | 1         | 1      | 0.14%   |
| FORESEE               | 1         | 1      | 0.14%   |
| EYOTA                 | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 31        | 4.1%    |
| Seagate ST500LT012-1DG142 500GB      | 27        | 3.57%   |
| Toshiba MQ01ABF050 500GB             | 15        | 1.98%   |
| Toshiba MQ01ABD100 1TB               | 15        | 1.98%   |
| Toshiba MQ04ABF100 1TB               | 14        | 1.85%   |
| HGST HTS545050A7E680 500GB           | 13        | 1.72%   |
| Seagate ST9500325AS 500GB            | 9         | 1.19%   |
| HGST HTS725050A7E630 500GB           | 9         | 1.19%   |
| SanDisk NVMe SSD Drive 512GB         | 8         | 1.06%   |
| Intel SSDPEKNW512G8 512GB            | 8         | 1.06%   |
| Hitachi HTS545050A7E380 500GB        | 8         | 1.06%   |
| A-DATA SU650 120GB SSD               | 8         | 1.06%   |
| Seagate ST9320325AS 320GB            | 7         | 0.93%   |
| HGST HTS721010A9E630 1TB             | 7         | 0.93%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 6         | 0.79%   |
| WDC WD10SPZX-21Z10T0 1TB             | 6         | 0.79%   |
| Seagate ST500LT012-9WS142 500GB      | 6         | 0.79%   |
| Seagate ST2000LM007-1R8174 2TB       | 6         | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 6         | 0.79%   |
| Samsung SSD 850 EVO 250GB            | 6         | 0.79%   |
| Hitachi HTS543232A7A384 320GB        | 6         | 0.79%   |
| HGST HTS541010A9E680 1TB             | 6         | 0.79%   |
| Unknown                              | 6         | 0.79%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 5         | 0.66%   |
| Unknown MMC Card  32GB               | 5         | 0.66%   |
| Seagate ST1000LX015-1U7172 1TB       | 5         | 0.66%   |
| Intel NVMe SSD Drive 512GB           | 5         | 0.66%   |
| HGST HTS545050A7E380 500GB           | 5         | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 4         | 0.53%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 4         | 0.53%   |
| WDC WD10SPZX-24Z10 1TB               | 4         | 0.53%   |
| WDC WD10JPCX-24UE4T0 1TB             | 4         | 0.53%   |
| Toshiba MQ01ABD032 320GB             | 4         | 0.53%   |
| Toshiba MK3265GSX 320GB              | 4         | 0.53%   |
| Seagate ST500LM021-1KJ152 500GB      | 4         | 0.53%   |
| Seagate ST1000LM049-2GH172 1TB       | 4         | 0.53%   |
| Samsung SSD 860 EVO 500GB            | 4         | 0.53%   |
| Samsung SSD 860 EVO 250GB            | 4         | 0.53%   |
| Samsung NVMe SSD Drive 512GB         | 4         | 0.53%   |
| Micron MTFDHBA512QFD-1AX1AABHA 512GB | 4         | 0.53%   |
| JMicron Generic 2TB                  | 4         | 0.53%   |
| Apacer AS340 240GB SSD               | 4         | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 3         | 0.4%    |
| WDC WD10SPZX-60Z10T0 1TB             | 3         | 0.4%    |
| WDC WD10JPVX-60JC3T0 1TB             | 3         | 0.4%    |
| WDC PC SN520 SDAPMUW-512G-1101 512GB | 3         | 0.4%    |
| Toshiba MQ01ABD075 752GB             | 3         | 0.4%    |
| Toshiba MQ01ABD050 500GB             | 3         | 0.4%    |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 0.4%    |
| Samsung NVMe SSD Drive 256GB         | 3         | 0.4%    |
| Samsung MZVLB512HBJQ-000L2 512GB     | 3         | 0.4%    |
| Micron NVMe SSD Drive 512GB          | 3         | 0.4%    |
| Kingston SA400S37240G 240GB SSD      | 3         | 0.4%    |
| JMicron Tech 250GB                   | 3         | 0.4%    |
| Hitachi HTS545025B9A300 250GB        | 3         | 0.4%    |
| Fujitsu MHZ2320BH G2 320GB           | 3         | 0.4%    |
| China SSD 120GB                      | 3         | 0.4%    |
| A-DATA SU650 240GB SSD               | 3         | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.26%   |
| WDC WD5000LPVT-22G33T0 500GB         | 2         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 134       | 167    | 35.54%  |
| WDC                 | 76        | 84     | 20.16%  |
| Toshiba             | 71        | 77     | 18.83%  |
| HGST                | 47        | 51     | 12.47%  |
| Hitachi             | 33        | 39     | 8.75%   |
| Fujitsu             | 8         | 8      | 2.12%   |
| Samsung Electronics | 3         | 3      | 0.8%    |
| Unknown             | 2         | 2      | 0.53%   |
| HGST HTS            | 1         | 3      | 0.27%   |
| Hewlett-Packard     | 1         | 1      | 0.27%   |
| Apple               | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 46     | 20.22%  |
| WDC                 | 14        | 21     | 7.65%   |
| Kingston            | 13        | 14     | 7.1%    |
| A-DATA Technology   | 11        | 11     | 6.01%   |
| SanDisk             | 10        | 17     | 5.46%   |
| V-GeN               | 7         | 7      | 3.83%   |
| MidasForce          | 7         | 8      | 3.83%   |
| Intel               | 7         | 11     | 3.83%   |
| Apacer              | 7         | 7      | 3.83%   |
| Crucial             | 6         | 7      | 3.28%   |
| China               | 6         | 6      | 3.28%   |
| Patriot             | 5         | 7      | 2.73%   |
| Apple               | 5         | 5      | 2.73%   |
| Unknown             | 5         | 5      | 2.73%   |
| Team                | 3         | 6      | 1.64%   |
| Seagate             | 3         | 3      | 1.64%   |
| Pioneer             | 3         | 3      | 1.64%   |
| Micron Technology   | 3         | 4      | 1.64%   |
| LITEONIT            | 3         | 3      | 1.64%   |
| LITEON              | 3         | 4      | 1.64%   |
| RX7                 | 2         | 2      | 1.09%   |
| Lexar               | 2         | 2      | 1.09%   |
| GALAX               | 2         | 2      | 1.09%   |
| XSTAR               | 1         | 1      | 0.55%   |
| WellcommMaster      | 1         | 1      | 0.55%   |
| Vaseky              | 1         | 2      | 0.55%   |
| Varro               | 1         | 1      | 0.55%   |
| Transcend           | 1         | 1      | 0.55%   |
| Toshiba             | 1         | 1      | 0.55%   |
| TO Exter            | 1         | 1      | 0.55%   |
| SPCC                | 1         | 1      | 0.55%   |
| Smart               | 1         | 1      | 0.55%   |
| SK hynix            | 1         | 1      | 0.55%   |
| PNY                 | 1         | 1      | 0.55%   |
| OSCOO               | 1         | 1      | 0.55%   |
| NGFF                | 1         | 1      | 0.55%   |
| Memory              | 1         | 1      | 0.55%   |
| KingDian            | 1         | 1      | 0.55%   |
| JMicron Technology  | 1         | 1      | 0.55%   |
| FORESEE             | 1         | 1      | 0.55%   |
| Corsair             | 1         | 1      | 0.55%   |
| Colorful            | 1         | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 366       | 436    | 51.26%  |
| SSD     | 175       | 221    | 24.51%  |
| NVMe    | 131       | 173    | 18.35%  |
| Unknown | 24        | 30     | 3.36%   |
| MMC     | 18        | 22     | 2.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 483       | 666    | 73.97%  |
| NVMe | 128       | 167    | 19.6%   |
| SAS  | 24        | 27     | 3.68%   |
| MMC  | 18        | 22     | 2.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 353       | 451    | 68.02%  |
| 0.51-1.0   | 156       | 189    | 30.06%  |
| 1.01-2.0   | 10        | 17     | 1.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 161       | 26.31%  |
| 251-500        | 158       | 25.82%  |
| 501-1000       | 73        | 11.93%  |
| 51-100         | 70        | 11.44%  |
| 1001-2000      | 45        | 7.35%   |
| 1-20           | 45        | 7.35%   |
| 21-50          | 44        | 7.19%   |
| More than 3000 | 6         | 0.98%   |
| Unknown        | 6         | 0.98%   |
| 2001-3000      | 4         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 242       | 37.52%  |
| 21-50          | 122       | 18.91%  |
| 51-100         | 83        | 12.87%  |
| 101-250        | 79        | 12.25%  |
| 251-500        | 62        | 9.61%   |
| 501-1000       | 39        | 6.05%   |
| 1001-2000      | 9         | 1.4%    |
| Unknown        | 6         | 0.93%   |
| 2001-3000      | 2         | 0.31%   |
| More than 3000 | 1         | 0.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                     | 4         | 4      | 5.71%   |
| Toshiba MQ01ABD032 320GB                       | 3         | 3      | 4.29%   |
| Seagate ST9500325AS 500GB                      | 3         | 3      | 4.29%   |
| Seagate ST500LT012-9WS142 500GB                | 3         | 3      | 4.29%   |
| Seagate ST1000LM035-1RK172 1TB                 | 3         | 3      | 4.29%   |
| Hitachi HTS545050A7E380 500GB                  | 3         | 3      | 4.29%   |
| Toshiba MK3265GSX 320GB                        | 2         | 2      | 2.86%   |
| Seagate ST500LT012-1DG142 500GB                | 2         | 2      | 2.86%   |
| Seagate ST1000LX015-1U7172 1TB                 | 2         | 3      | 2.86%   |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 2.86%   |
| WellcommMaster 128GB SSD                       | 1         | 1      | 1.43%   |
| WDC WD5000LPVX-80V0TT0 500GB                   | 1         | 1      | 1.43%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 1.43%   |
| WDC WD5000LPCX-22VHAT0 500GB                   | 1         | 1      | 1.43%   |
| WDC WD5000L 500GB                              | 1         | 1      | 1.43%   |
| WDC WD5000BPVT-60HXZT3 500GB                   | 1         | 1      | 1.43%   |
| WDC WD3200BEKT-60V5T1 320GB                    | 1         | 1      | 1.43%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 1      | 1.43%   |
| WDC WD10SPZX-24Z10 1TB                         | 1         | 1      | 1.43%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 1         | 1      | 1.43%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 1.43%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 1.43%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 1.43%   |
| Toshiba MK7575GSX 752GB                        | 1         | 2      | 1.43%   |
| Toshiba MK5075GSX 500GB                        | 1         | 1      | 1.43%   |
| Toshiba MK3276GSX 320GB                        | 1         | 1      | 1.43%   |
| Toshiba MK3275GSX 320GB                        | 1         | 1      | 1.43%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 1.43%   |
| Seagate ST9320423AS 320GB                      | 1         | 1      | 1.43%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 1.43%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1         | 1      | 1.43%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 6      | 1.43%   |
| Seagate ST1000LM049-2GH172 1TB                 | 1         | 1      | 1.43%   |
| Seagate OOS1000G128M 1TB                       | 1         | 1      | 1.43%   |
| SanDisk SSD PLUS 120 GB                        | 1         | 1      | 1.43%   |
| SanDisk SDSSDA120G 120GB                       | 1         | 1      | 1.43%   |
| Samsung Electronics SSD 870 EVO 500GB          | 1         | 1      | 1.43%   |
| Samsung Electronics MZVLB512HAJQ-00000 512GB   | 1         | 1      | 1.43%   |
| Samsung Electronics HM321HI 320GB              | 1         | 1      | 1.43%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 1.43%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 1.43%   |
| Intel SSDSC2KF480H6L 480GB                     | 1         | 1      | 1.43%   |
| Hitachi HTS725016A9A364 160GB                  | 1         | 1      | 1.43%   |
| Hitachi HTS547550A9E384 500GB                  | 1         | 1      | 1.43%   |
| Hitachi HTS545050B9SA00 500GB                  | 1         | 1      | 1.43%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 1.43%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 1.43%   |
| HGST HTS545050A7E660 500GB                     | 1         | 1      | 1.43%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 1.43%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 1.43%   |
| Crucial CT512M550SSD3 512GB                    | 1         | 1      | 1.43%   |
| China SSD 120GB                                | 1         | 1      | 1.43%   |
| A-DATA Technology SU650 240GB SSD              | 1         | 1      | 1.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 26     | 27.54%  |
| Toshiba             | 12        | 13     | 17.39%  |
| WDC                 | 9         | 9      | 13.04%  |
| HGST                | 9         | 9      | 13.04%  |
| Hitachi             | 8         | 8      | 11.59%  |
| Samsung Electronics | 3         | 3      | 4.35%   |
| SanDisk             | 2         | 2      | 2.9%    |
| Micron Technology   | 2         | 2      | 2.9%    |
| WellcommMaster      | 1         | 1      | 1.45%   |
| Intel               | 1         | 1      | 1.45%   |
| Crucial             | 1         | 1      | 1.45%   |
| China               | 1         | 1      | 1.45%   |
| A-DATA Technology   | 1         | 1      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 26     | 32.76%  |
| Toshiba             | 12        | 13     | 20.69%  |
| WDC                 | 9         | 9      | 15.52%  |
| HGST                | 9         | 9      | 15.52%  |
| Hitachi             | 8         | 8      | 13.79%  |
| Samsung Electronics | 1         | 1      | 1.72%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 58        | 66     | 84.06%  |
| SSD  | 10        | 10     | 14.49%  |
| NVMe | 1         | 1      | 1.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-60HXZT1 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 336       | 499    | 53.5%   |
| Works    | 222       | 305    | 35.35%  |
| Malfunc  | 69        | 77     | 10.99%  |
| Failed   | 1         | 1      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 415       | 62.41%  |
| AMD                              | 124       | 18.65%  |
| Samsung Electronics              | 34        | 5.11%   |
| SanDisk                          | 21        | 3.16%   |
| SK hynix                         | 14        | 2.11%   |
| Kingston Technology Company      | 11        | 1.65%   |
| Micron Technology                | 10        | 1.5%    |
| Silicon Motion                   | 6         | 0.9%    |
| Toshiba America Info Systems     | 5         | 0.75%   |
| Phison Electronics               | 5         | 0.75%   |
| Silicon Integrated Systems [SiS] | 4         | 0.6%    |
| ADATA Technology                 | 4         | 0.6%    |
| Union Memory (Shenzhen)          | 3         | 0.45%   |
| Realtek Semiconductor            | 3         | 0.45%   |
| KIOXIA                           | 3         | 0.45%   |
| Lenovo                           | 1         | 0.15%   |
| ASMedia Technology               | 1         | 0.15%   |
| Apple                            | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 114       | 16.01%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 64        | 8.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 51        | 7.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 42        | 5.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 35        | 4.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 31        | 4.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 22        | 3.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 20        | 2.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 14        | 1.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 14        | 1.97%   |
| Intel SSD 660P Series                                                                  | 13        | 1.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 12        | 1.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 12        | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 12        | 1.69%   |
| Samsung NVMe SSD Controller 980                                                        | 11        | 1.54%   |
| Micron Non-Volatile memory controller                                                  | 10        | 1.4%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 10        | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 10        | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 10        | 1.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 9         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 9         | 1.26%   |
| SanDisk PC SN520 NVMe SSD                                                              | 7         | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 7         | 0.98%   |
| SK hynix BC511                                                                         | 5         | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                                  | 5         | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 5         | 0.7%    |
| Samsung Electronics SATA controller                                                    | 5         | 0.7%    |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 5         | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 5         | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 5         | 0.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 5         | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                                  | 5         | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 4         | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 0.56%   |
| Phison E12 NVMe Controller                                                             | 4         | 0.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 4         | 0.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 4         | 0.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 4         | 0.56%   |
| AMD FCH IDE Controller                                                                 | 4         | 0.56%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 4         | 0.56%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 3         | 0.42%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 0.42%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                            | 3         | 0.42%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 3         | 0.42%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 3         | 0.42%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 3         | 0.42%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 3         | 0.42%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 0.42%   |
| Intel Non-Volatile memory controller                                                   | 3         | 0.42%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 3         | 0.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 0.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 3         | 0.42%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 0.42%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 3         | 0.42%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 3         | 0.42%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 0.42%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 0.42%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.28%   |
| SK hynix Gold P31 SSD                                                                  | 2         | 0.28%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                          | 2         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 491       | 71.06%  |
| NVMe | 128       | 18.52%  |
| IDE  | 37        | 5.35%   |
| RAID | 35        | 5.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 442       | 75.17%  |
| AMD    | 146       | 24.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 2.21%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 2.21%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 2.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 1.87%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 11        | 1.87%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 11        | 1.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 1.36%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 1.36%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 8         | 1.36%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.19%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 7         | 1.19%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 7         | 1.19%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 1.19%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 7         | 1.19%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 7         | 1.19%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.19%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 7         | 1.19%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 7         | 1.19%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.02%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 1.02%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 6         | 1.02%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 5         | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.85%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 5         | 0.85%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 5         | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.85%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 5         | 0.85%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.85%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.85%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 5         | 0.85%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 5         | 0.85%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 4         | 0.68%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 0.68%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 4         | 0.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.68%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.68%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 0.68%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.68%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 0.68%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.68%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 4         | 0.68%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 4         | 0.68%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 4         | 0.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 0.68%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 4         | 0.68%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 4         | 0.68%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.51%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 0.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.51%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 0.51%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 3         | 0.51%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 3         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 164       | 27.89%  |
| Intel Core i7           | 90        | 15.31%  |
| Intel Core i3           | 84        | 14.29%  |
| Intel Celeron           | 37        | 6.29%   |
| AMD Ryzen 5             | 33        | 5.61%   |
| Other                   | 24        | 4.08%   |
| Intel Core 2 Duo        | 19        | 3.23%   |
| AMD A8                  | 18        | 3.06%   |
| AMD Ryzen 3             | 16        | 2.72%   |
| Intel Pentium           | 14        | 2.38%   |
| AMD A4                  | 10        | 1.7%    |
| AMD Ryzen 7             | 9         | 1.53%   |
| Intel Atom              | 8         | 1.36%   |
| AMD E1                  | 8         | 1.36%   |
| AMD A6                  | 7         | 1.19%   |
| AMD E                   | 6         | 1.02%   |
| Intel Pentium Dual-Core | 5         | 0.85%   |
| Intel Pentium Dual      | 5         | 0.85%   |
| AMD E2                  | 5         | 0.85%   |
| AMD A10                 | 5         | 0.85%   |
| Intel Genuine           | 4         | 0.68%   |
| AMD Ryzen 9             | 3         | 0.51%   |
| AMD FX                  | 3         | 0.51%   |
| AMD C-60                | 3         | 0.51%   |
| AMD Athlon              | 3         | 0.51%   |
| Intel Core 2            | 2         | 0.34%   |
| AMD A12                 | 2         | 0.34%   |
| AMD Turion 64 Mobile    | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 391       | 66.5%   |
| 4      | 150       | 25.51%  |
| 6      | 32        | 5.44%   |
| 1      | 8         | 1.36%   |
| 8      | 7         | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 588       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 427       | 72.62%  |
| 1      | 161       | 27.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 574       | 97.62%  |
| Unknown        | 11        | 1.87%   |
| 32-bit         | 3         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 13.04%  |
| 0x206a7    | 53        | 8.75%   |
| 0x306a9    | 48        | 7.92%   |
| 0x40651    | 31        | 5.12%   |
| 0x306d4    | 26        | 4.29%   |
| 0x806ea    | 21        | 3.47%   |
| 0x806e9    | 20        | 3.3%    |
| 0x806ec    | 19        | 3.14%   |
| 0x20655    | 19        | 3.14%   |
| 0x906ea    | 17        | 2.81%   |
| 0x06006705 | 17        | 2.81%   |
| 0x08108109 | 14        | 2.31%   |
| 0x806eb    | 13        | 2.15%   |
| 0x406e3    | 13        | 2.15%   |
| 0x1067a    | 13        | 2.15%   |
| 0x07030105 | 13        | 2.15%   |
| 0x08108102 | 11        | 1.82%   |
| 0x6fd      | 10        | 1.65%   |
| 0x0a50000c | 10        | 1.65%   |
| 0x806c1    | 9         | 1.49%   |
| 0x306c3    | 9         | 1.49%   |
| 0x706e5    | 8         | 1.32%   |
| 0x30678    | 8         | 1.32%   |
| 0x20652    | 7         | 1.16%   |
| 0x06001119 | 7         | 1.16%   |
| 0x906e9    | 6         | 0.99%   |
| 0x406c4    | 6         | 0.99%   |
| 0x406c3    | 6         | 0.99%   |
| 0x05000119 | 6         | 0.99%   |
| 0x03000027 | 6         | 0.99%   |
| 0x506e3    | 5         | 0.83%   |
| 0x10676    | 5         | 0.83%   |
| 0x0810100b | 5         | 0.83%   |
| 0x0700010f | 5         | 0.83%   |
| 0x08608103 | 4         | 0.66%   |
| 0x08600104 | 4         | 0.66%   |
| 0x08101007 | 4         | 0.66%   |
| 0x0600611a | 4         | 0.66%   |
| 0x706a1    | 3         | 0.5%    |
| 0x06006704 | 3         | 0.5%    |
| 0x906ed    | 2         | 0.33%   |
| 0x6fa      | 2         | 0.33%   |
| 0x6f6      | 2         | 0.33%   |
| 0x6ec      | 2         | 0.33%   |
| 0x506c9    | 2         | 0.33%   |
| 0x30673    | 2         | 0.33%   |
| 0x106ca    | 2         | 0.33%   |
| 0x08608102 | 2         | 0.33%   |
| 0x08600103 | 2         | 0.33%   |
| 0x07030104 | 2         | 0.33%   |
| 0x0500010d | 2         | 0.33%   |
| 0x05000029 | 2         | 0.33%   |
| 0xa0660    | 1         | 0.17%   |
| 0xa0652    | 1         | 0.17%   |
| 0x906c0    | 1         | 0.17%   |
| 0x806c2    | 1         | 0.17%   |
| 0x706a8    | 1         | 0.17%   |
| 0x6fb      | 1         | 0.17%   |
| 0x106c2    | 1         | 0.17%   |
| 0x0a50000b | 1         | 0.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 108       | 18.37%  |
| SandyBridge   | 61        | 10.37%  |
| IvyBridge     | 53        | 9.01%   |
| Haswell       | 49        | 8.33%   |
| Westmere      | 30        | 5.1%    |
| Broadwell     | 29        | 4.93%   |
| Excavator     | 28        | 4.76%   |
| Zen+          | 27        | 4.59%   |
| Silvermont    | 23        | 3.91%   |
| Skylake       | 20        | 3.4%    |
| Penryn        | 19        | 3.23%   |
| Puma          | 18        | 3.06%   |
| Core          | 15        | 2.55%   |
| Zen 3         | 12        | 2.04%   |
| Bobcat        | 12        | 2.04%   |
| Zen           | 10        | 1.7%    |
| TigerLake     | 10        | 1.7%    |
| Zen 2         | 9         | 1.53%   |
| Piledriver    | 8         | 1.36%   |
| IceLake       | 8         | 1.36%   |
| Jaguar        | 7         | 1.19%   |
| K10 Llano     | 6         | 1.02%   |
| Unknown       | 6         | 1.02%   |
| Goldmont plus | 4         | 0.68%   |
| Bonnell       | 4         | 0.68%   |
| Goldmont      | 3         | 0.51%   |
| CometLake     | 3         | 0.51%   |
| Steamroller   | 2         | 0.34%   |
| P6            | 2         | 0.34%   |
| Tremont       | 1         | 0.17%   |
| K8 Hammer     | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 426       | 55.11%  |
| AMD                              | 189       | 24.45%  |
| Nvidia                           | 154       | 19.92%  |
| Silicon Integrated Systems [SiS] | 4         | 0.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 58        | 7.07%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 53        | 6.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 37        | 4.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 3.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 25        | 3.05%   |
| Intel HD Graphics 5500                                                                   | 24        | 2.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 23        | 2.8%    |
| Intel UHD Graphics 620                                                                   | 23        | 2.8%    |
| Intel HD Graphics 620                                                                    | 21        | 2.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 21        | 2.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 19        | 2.32%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 17        | 2.07%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 17        | 2.07%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 16        | 1.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 1.71%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 13        | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 12        | 1.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 1.46%   |
| AMD Cezanne                                                                              | 12        | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 1.22%   |
| AMD Renoir                                                                               | 9         | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 0.98%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 8         | 0.98%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.85%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 7         | 0.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 0.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 0.85%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 0.85%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 0.85%   |
| Nvidia GP108M [GeForce MX250]                                                            | 6         | 0.73%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 6         | 0.73%   |
| Intel HD Graphics 630                                                                    | 6         | 0.73%   |
| AMD Lucienne                                                                             | 6         | 0.73%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.61%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 0.61%   |
| Intel Iris Graphics 6100                                                                 | 5         | 0.61%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 5         | 0.61%   |
| AMD SuperSumo [Radeon HD 6480G]                                                          | 5         | 0.61%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 5         | 0.61%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 0.49%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.49%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 4         | 0.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 0.49%   |
| Intel HD Graphics 530                                                                    | 4         | 0.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.49%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 4         | 0.49%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 4         | 0.49%   |
| Nvidia TU117M                                                                            | 3         | 0.37%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.37%   |
| Nvidia GP107M [GeForce MX350]                                                            | 3         | 0.37%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.37%   |
| Nvidia GF119M [GeForce 610M]                                                             | 3         | 0.37%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 3         | 0.37%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 259       | 43.82%  |
| Intel + Nvidia | 132       | 22.34%  |
| 1 x AMD        | 105       | 17.77%  |
| Intel + AMD    | 38        | 6.43%   |
| 2 x AMD        | 31        | 5.25%   |
| AMD + Nvidia   | 15        | 2.54%   |
| 1 x Nvidia     | 7         | 1.18%   |
| 1 x SiS        | 4         | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 507       | 84.92%  |
| Proprietary | 78        | 13.07%  |
| Unknown     | 12        | 2.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 341       | 56.27%  |
| 1.01-2.0   | 114       | 18.81%  |
| 0.01-0.5   | 78        | 12.87%  |
| 0.51-1.0   | 35        | 5.78%   |
| 3.01-4.0   | 29        | 4.79%   |
| 5.01-6.0   | 7         | 1.16%   |
| 7.01-8.0   | 2         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 146       | 23.03%  |
| Chimei Innolux          | 115       | 18.14%  |
| BOE                     | 96        | 15.14%  |
| LG Display              | 87        | 13.72%  |
| Samsung Electronics     | 54        | 8.52%   |
| Goldstar                | 24        | 3.79%   |
| Lenovo                  | 12        | 1.89%   |
| Apple                   | 11        | 1.74%   |
| PANDA                   | 7         | 1.1%    |
| InnoLux Display         | 7         | 1.1%    |
| Chi Mei Optoelectronics | 7         | 1.1%    |
| Sharp                   | 6         | 0.95%   |
| Acer                    | 6         | 0.95%   |
| ViewSonic               | 5         | 0.79%   |
| LG Philips              | 5         | 0.79%   |
| InfoVision              | 5         | 0.79%   |
| Dell                    | 5         | 0.79%   |
| AOC                     | 4         | 0.63%   |
| Sony                    | 3         | 0.47%   |
| Quanta Display          | 3         | 0.47%   |
| Philips                 | 3         | 0.47%   |
| Hewlett-Packard         | 3         | 0.47%   |
| HannStar                | 3         | 0.47%   |
| CPT                     | 3         | 0.47%   |
| Toshiba                 | 2         | 0.32%   |
| Seiko/Epson             | 2         | 0.32%   |
| Panasonic               | 2         | 0.32%   |
| BenQ                    | 2         | 0.32%   |
| Mi                      | 1         | 0.16%   |
| KDC                     | 1         | 0.16%   |
| HKC                     | 1         | 0.16%   |
| HIC                     | 1         | 0.16%   |
| CSO                     | 1         | 0.16%   |
| Armaggeddon             | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 13        | 2.04%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 13        | 2.04%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 11        | 1.73%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 10        | 1.57%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch      | 9         | 1.42%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 9         | 1.42%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch        | 9         | 1.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 8         | 1.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 8         | 1.26%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 7         | 1.1%    |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                 | 7         | 1.1%    |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 6         | 0.94%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 6         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 6         | 0.94%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch      | 6         | 0.94%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 6         | 0.94%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 6         | 0.94%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch        | 6         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 5         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch     | 5         | 0.79%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch      | 5         | 0.79%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                 | 5         | 0.79%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 5         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch | 4         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch | 4         | 0.63%   |
| LG Display LCD Monitor LGD06B9 1920x1200 286x179mm 13.3-inch         | 4         | 0.63%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 4         | 0.63%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch          | 4         | 0.63%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 4         | 0.63%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 4         | 0.63%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 4         | 0.63%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch        | 4         | 0.63%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch        | 4         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 3         | 0.47%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3         | 0.47%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch         | 3         | 0.47%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch         | 3         | 0.47%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch          | 3         | 0.47%   |
| LG Display LCD Monitor LGD0454 1366x768 310x174mm 14.0-inch          | 3         | 0.47%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 3         | 0.47%   |
| LG Display LCD Monitor LGD01E6 1366x768 309x174mm 14.0-inch          | 3         | 0.47%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch     | 3         | 0.47%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch          | 3         | 0.47%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch             | 3         | 0.47%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 309x174mm 14.0-inch      | 3         | 0.47%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                 | 3         | 0.47%   |
| BOE LCD Monitor BOE05F0 1366x768 309x173mm 13.9-inch                 | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO393C 1366x768 309x173mm 13.9-inch        | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch       | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch        | 3         | 0.47%   |
| Apple Color LCD APPA029 2560x1600 286x179mm 13.3-inch                | 3         | 0.47%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                   | 3         | 0.47%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch            | 2         | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 2         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 341       | 56.27%  |
| 1920x1080 (FHD)   | 173       | 28.55%  |
| 1280x800 (WXGA)   | 21        | 3.47%   |
| 1600x900 (HD+)    | 17        | 2.81%   |
| 3840x2160 (4K)    | 10        | 1.65%   |
| 1440x900 (WXGA+)  | 8         | 1.32%   |
| 2560x1440 (QHD)   | 7         | 1.16%   |
| 1920x1200 (WUXGA) | 6         | 0.99%   |
| 2560x1600         | 5         | 0.83%   |
| 1360x768          | 4         | 0.66%   |
| 1024x600          | 4         | 0.66%   |
| 2880x1800         | 2         | 0.33%   |
| 2560x1080         | 2         | 0.33%   |
| 3840x2400         | 1         | 0.17%   |
| 3440x1440         | 1         | 0.17%   |
| 3200x1800 (QHD+)  | 1         | 0.17%   |
| 2966x900          | 1         | 0.17%   |
| 2736x1824         | 1         | 0.17%   |
| Unknown           | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 196       | 30.96%  |
| 14      | 179       | 28.28%  |
| 15      | 125       | 19.75%  |
| 12      | 29        | 4.58%   |
| 23      | 22        | 3.48%   |
| 11      | 19        | 3%      |
| 18      | 14        | 2.21%   |
| 21      | 9         | 1.42%   |
| 19      | 7         | 1.11%   |
| 17      | 6         | 0.95%   |
| 24      | 5         | 0.79%   |
| 10      | 4         | 0.63%   |
| 34      | 3         | 0.47%   |
| 27      | 3         | 0.47%   |
| Unknown | 3         | 0.47%   |
| 48      | 2         | 0.32%   |
| 40      | 2         | 0.32%   |
| 72      | 1         | 0.16%   |
| 54      | 1         | 0.16%   |
| 31      | 1         | 0.16%   |
| 20      | 1         | 0.16%   |
| 9       | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 450       | 71.66%  |
| 201-300     | 91        | 14.49%  |
| 401-500     | 30        | 4.78%   |
| 501-600     | 29        | 4.62%   |
| 351-400     | 14        | 2.23%   |
| 701-800     | 3         | 0.48%   |
| 1001-1500   | 3         | 0.48%   |
| Unknown     | 3         | 0.48%   |
| 801-900     | 2         | 0.32%   |
| 601-700     | 2         | 0.32%   |
| 1501-2000   | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 522       | 90.78%  |
| 16/10   | 45        | 7.83%   |
| 21/9    | 3         | 0.52%   |
| Unknown | 3         | 0.52%   |
| 4/3     | 1         | 0.17%   |
| 3/2     | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 342       | 54.03%  |
| 101-110        | 124       | 19.59%  |
| 201-250        | 36        | 5.69%   |
| 71-80          | 30        | 4.74%   |
| 61-70          | 28        | 4.42%   |
| 51-60          | 19        | 3%      |
| 141-150        | 14        | 2.21%   |
| 151-200        | 8         | 1.26%   |
| 41-50          | 5         | 0.79%   |
| 91-100         | 5         | 0.79%   |
| More than 1000 | 4         | 0.63%   |
| 351-500        | 4         | 0.63%   |
| 121-130        | 4         | 0.63%   |
| 301-350        | 3         | 0.47%   |
| Unknown        | 3         | 0.47%   |
| 131-140        | 2         | 0.32%   |
| 501-1000       | 2         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 310       | 49.6%   |
| 121-160       | 197       | 31.52%  |
| 51-100        | 72        | 11.52%  |
| 161-240       | 28        | 4.48%   |
| More than 240 | 10        | 1.6%    |
| 1-50          | 5         | 0.8%    |
| Unknown       | 3         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 517       | 86.17%  |
| 2     | 67        | 11.17%  |
| 0     | 14        | 2.33%   |
| 3     | 2         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 356       | 36.78%  |
| Qualcomm Atheros                  | 217       | 22.42%  |
| Intel                             | 211       | 21.8%   |
| Broadcom                          | 69        | 7.13%   |
| Broadcom Limited                  | 15        | 1.55%   |
| MediaTek                          | 14        | 1.45%   |
| Xiaomi                            | 9         | 0.93%   |
| Samsung Electronics               | 9         | 0.93%   |
| Ralink Technology                 | 9         | 0.93%   |
| TP-Link                           | 8         | 0.83%   |
| Marvell Technology Group          | 8         | 0.83%   |
| Ralink                            | 6         | 0.62%   |
| Qualcomm Atheros Communications   | 5         | 0.52%   |
| JMicron Technology                | 5         | 0.52%   |
| OPPO Electronics                  | 4         | 0.41%   |
| Huawei Technologies               | 4         | 0.41%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.31%   |
| Attansic Technology               | 3         | 0.31%   |
| Sierra Wireless                   | 2         | 0.21%   |
| Qualcomm                          | 2         | 0.21%   |
| Ericsson Business Mobile Networks | 2         | 0.21%   |
| ICS Advent                        | 1         | 0.1%    |
| HTC (High Tech Computer)          | 1         | 0.1%    |
| Hewlett-Packard                   | 1         | 0.1%    |
| Foxconn / Hon Hai                 | 1         | 0.1%    |
| ASUSTek Computer                  | 1         | 0.1%    |
| ASIX Electronics                  | 1         | 0.1%    |
| AboCom Systems                    | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 228       | 19.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 83        | 7.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 54        | 4.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 53        | 4.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 32        | 2.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 29        | 2.53%   |
| Intel Wireless 8265 / 8275                                              | 24        | 2.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 23        | 2.01%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 19        | 1.66%   |
| Intel Wireless 7265                                                     | 18        | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 1.48%   |
| Intel Wireless 7260                                                     | 16        | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 16        | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 14        | 1.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 14        | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 11        | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 10        | 0.87%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 0.87%   |
| Intel Ethernet Connection I218-LM                                       | 10        | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                                   | 9         | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.7%    |
| Ralink MT7601U Wireless Adapter                                         | 7         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                                | 7         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 6         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 6         | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 6         | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.52%   |
| Intel Wireless 3165                                                     | 6         | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                         | 5         | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 5         | 0.44%   |
| Intel Wireless 8260                                                     | 5         | 0.44%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.44%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.44%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 5         | 0.44%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 4         | 0.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.35%   |
| OPPO SDM720G-IDP _SN:B922E265                                           | 4         | 0.35%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 4         | 0.35%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.35%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.35%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.35%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 0.35%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 4         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 200       | 32.95%  |
| Intel                           | 195       | 32.13%  |
| Realtek Semiconductor           | 107       | 17.63%  |
| Broadcom                        | 56        | 9.23%   |
| Broadcom Limited                | 11        | 1.81%   |
| MediaTek                        | 10        | 1.65%   |
| Ralink Technology               | 9         | 1.48%   |
| Ralink                          | 6         | 0.99%   |
| TP-Link                         | 5         | 0.82%   |
| Qualcomm Atheros Communications | 5         | 0.82%   |
| Sierra Wireless                 | 2         | 0.33%   |
| AboCom Systems                  | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 54        | 8.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 53        | 8.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 32        | 5.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 29        | 4.75%   |
| Intel Wireless 8265 / 8275                                              | 24        | 3.93%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 19        | 3.11%   |
| Intel Wireless 7265                                                     | 18        | 2.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 2.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 2.78%   |
| Intel Wireless 7260                                                     | 16        | 2.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 16        | 2.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 2.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 14        | 2.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 1.8%    |
| Intel Wi-Fi 6 AX200                                                     | 10        | 1.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.31%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 1.15%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.98%   |
| Intel Wireless 3165                                                     | 6         | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                         | 5         | 0.82%   |
| Intel Wireless 8260                                                     | 5         | 0.82%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.82%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.82%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 5         | 0.82%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 4         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.65%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.65%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.65%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 0.65%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 4         | 0.65%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.65%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.49%   |
| Intel Wireless 3160                                                     | 3         | 0.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.49%   |
| Intel Centrino Wireless-N 135                                           | 3         | 0.49%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.49%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.49%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 0.49%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.49%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.33%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.33%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.33%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 321       | 60.8%   |
| Intel                            | 73        | 13.83%  |
| Qualcomm Atheros                 | 50        | 9.47%   |
| Broadcom                         | 21        | 3.98%   |
| Xiaomi                           | 9         | 1.7%    |
| Samsung Electronics              | 9         | 1.7%    |
| Marvell Technology Group         | 8         | 1.52%   |
| Broadcom Limited                 | 6         | 1.14%   |
| JMicron Technology               | 5         | 0.95%   |
| OPPO Electronics                 | 4         | 0.76%   |
| MediaTek                         | 4         | 0.76%   |
| TP-Link                          | 3         | 0.57%   |
| Silicon Integrated Systems [SiS] | 3         | 0.57%   |
| Attansic Technology              | 3         | 0.57%   |
| Qualcomm                         | 2         | 0.38%   |
| ICS Advent                       | 1         | 0.19%   |
| Huawei Technologies              | 1         | 0.19%   |
| HTC (High Tech Computer)         | 1         | 0.19%   |
| Hewlett-Packard                  | 1         | 0.19%   |
| Foxconn / Hon Hai                | 1         | 0.19%   |
| ASUSTek Computer                 | 1         | 0.19%   |
| ASIX Electronics                 | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 228       | 43.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 83        | 15.69%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 23        | 4.35%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 14        | 2.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 11        | 2.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 10        | 1.89%   |
| Intel Ethernet Connection I218-LM                                              | 10        | 1.89%   |
| Intel Ethernet Connection (3) I218-LM                                          | 9         | 1.7%    |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 6         | 1.13%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 6         | 1.13%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 6         | 1.13%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 5         | 0.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 0.76%   |
| OPPO SDM720G-IDP _SN:B922E265                                                  | 4         | 0.76%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 4         | 0.76%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 3         | 0.57%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 3         | 0.57%   |
| MediaTek moto e(6) plus                                                        | 3         | 0.57%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 3         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.57%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 3         | 0.57%   |
| TP-Link USB 10/100 LAN                                                         | 2         | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.38%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.38%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.38%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.38%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.38%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.38%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.38%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.38%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.38%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.19%   |
| Qualcomm BENGAL-QRD _SN:C5464635                                               | 1         | 0.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.19%   |
| Qualcomm Android                                                               | 1         | 0.19%   |
| MediaTek RMX3085                                                               | 1         | 0.19%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.19%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.19%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.19%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.19%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.19%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.19%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.19%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.19%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.19%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.19%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.19%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.19%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 579       | 53.51%  |
| Ethernet | 498       | 46.03%  |
| Modem    | 5         | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 508       | 87.44%  |
| Ethernet | 72        | 12.39%  |
| Modem    | 1         | 0.17%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 466       | 78.98%  |
| 1     | 116       | 19.66%  |
| 0     | 5         | 0.85%   |
| 3     | 3         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 575       | 97.29%  |
| Yes  | 16        | 2.71%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 144       | 31.93%  |
| Realtek Semiconductor           | 71        | 15.74%  |
| Qualcomm Atheros Communications | 52        | 11.53%  |
| IMC Networks                    | 46        | 10.2%   |
| Lite-On Technology              | 39        | 8.65%   |
| Broadcom                        | 32        | 7.1%    |
| Foxconn / Hon Hai               | 21        | 4.66%   |
| Apple                           | 10        | 2.22%   |
| Toshiba                         | 8         | 1.77%   |
| Dell                            | 5         | 1.11%   |
| Cambridge Silicon Radio         | 5         | 1.11%   |
| Ralink                          | 4         | 0.89%   |
| Hewlett-Packard                 | 3         | 0.67%   |
| Foxconn International           | 3         | 0.67%   |
| Realtek                         | 2         | 0.44%   |
| Micro Star International        | 2         | 0.44%   |
| ASUSTek Computer                | 2         | 0.44%   |
| MediaTek                        | 1         | 0.22%   |
| Chicony Electronics             | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 66        | 14.63%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 44        | 9.76%   |
| Realtek Bluetooth Radio                                                             | 31        | 6.87%   |
| IMC Networks Bluetooth Device                                                       | 28        | 6.21%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 24        | 5.32%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 20        | 4.43%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 13        | 2.88%   |
| Lite-On Bluetooth Device                                                            | 13        | 2.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 12        | 2.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 10        | 2.22%   |
| Intel AX201 Bluetooth                                                               | 10        | 2.22%   |
| Intel AX200 Bluetooth                                                               | 10        | 2.22%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 9         | 2%      |
| Realtek RTL8821A Bluetooth                                                          | 7         | 1.55%   |
| Realtek RTL8723B Bluetooth                                                          | 7         | 1.55%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 1.55%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 6         | 1.33%   |
| Lite-On Atheros Bluetooth                                                           | 6         | 1.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 1.33%   |
| Apple Bluetooth Host Controller                                                     | 6         | 1.33%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 5         | 1.11%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 1.11%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 5         | 1.11%   |
| Toshiba RT Bluetooth Radio                                                          | 4         | 0.89%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.89%   |
| Lite-On Wireless_Device                                                             | 4         | 0.89%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 0.89%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 4         | 0.89%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 0.89%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 0.67%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 3         | 0.67%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 3         | 0.67%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 0.67%   |
| Foxconn / Hon Hai Acer Module                                                       | 3         | 0.67%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 0.67%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 0.67%   |
| Broadcom BCM20702A0                                                                 | 3         | 0.67%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.67%   |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 0.44%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.44%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 2         | 0.44%   |
| Intel Bluetooth Device                                                              | 2         | 0.44%   |
| IMC Networks Bluetooth USB Host Controller                                          | 2         | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.44%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 2         | 0.44%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.44%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.44%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.44%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.22%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.22%   |
| MediaTek Wireless_Device                                                            | 1         | 0.22%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.22%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.22%   |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.22%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.22%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.22%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.22%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.22%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 1         | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 434       | 66.56%  |
| AMD                              | 149       | 22.85%  |
| Nvidia                           | 47        | 7.21%   |
| Silicon Integrated Systems [SiS] | 4         | 0.61%   |
| Samson Technologies              | 3         | 0.46%   |
| JMTek                            | 3         | 0.46%   |
| Generalplus Technology           | 3         | 0.46%   |
| Samsung Electronics              | 2         | 0.31%   |
| C-Media Electronics              | 2         | 0.31%   |
| USB-MIC                          | 1         | 0.15%   |
| SAVITECH                         | 1         | 0.15%   |
| Logitech                         | 1         | 0.15%   |
| Cooler Master                    | 1         | 0.15%   |
| ASUSTek Computer                 | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 67        | 7.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 64        | 7.39%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 62        | 7.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 47        | 5.43%   |
| AMD FCH Azalia Controller                                                                         | 46        | 5.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 37        | 4.27%   |
| Intel 8 Series HD Audio Controller                                                                | 37        | 4.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 34        | 3.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 32        | 3.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 30        | 3.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 29        | 3.35%   |
| Intel Broadwell-U Audio Controller                                                                | 29        | 3.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 28        | 3.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 23        | 2.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 22        | 2.54%   |
| AMD High Definition Audio Controller                                                              | 21        | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 19        | 2.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 15        | 1.73%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 13        | 1.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 1.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 1.27%   |
| AMD Wrestler HDMI Audio                                                                           | 11        | 1.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 0.92%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 0.81%   |
| Intel CM238 HD Audio Controller                                                                   | 7         | 0.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 0.81%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 6         | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.58%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 0.46%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.46%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.35%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.35%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.35%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.35%   |
| Samsung Electronics USBC Headset                                                                  | 2         | 0.23%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.23%   |
| JMTek USB PnP Audio Device                                                                        | 2         | 0.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.23%   |
| C-Media Electronics USB Audio Device                                                              | 2         | 0.23%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 0.23%   |
| USB-MIC USB-MIC                                                                                   | 1         | 0.12%   |
| SAVITECH USB DAC K1                                                                               | 1         | 0.12%   |
| Samson Technologies Q2U handheld microphone with XLR                                              | 1         | 0.12%   |
| Samson Technologies GoMic compact condenser mic                                                   | 1         | 0.12%   |
| Samson Technologies C01U Pro condenser microphone                                                 | 1         | 0.12%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.12%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.12%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.12%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 129       | 30.71%  |
| SK hynix            | 86        | 20.48%  |
| Micron Technology   | 47        | 11.19%  |
| Kingston            | 36        | 8.57%   |
| Unknown             | 30        | 7.14%   |
| Corsair             | 15        | 3.57%   |
| Team                | 14        | 3.33%   |
| V-GeN               | 11        | 2.62%   |
| Ramaxel Technology  | 11        | 2.62%   |
| Elpida              | 11        | 2.62%   |
| Nanya Technology    | 7         | 1.67%   |
| A-DATA Technology   | 4         | 0.95%   |
| Visipro             | 2         | 0.48%   |
| ASint Technology    | 2         | 0.48%   |
| Apacer              | 2         | 0.48%   |
| A Force             | 2         | 0.48%   |
| Unknown (ABCD)      | 1         | 0.24%   |
| Transcend           | 1         | 0.24%   |
| Strontium           | 1         | 0.24%   |
| Silicon Power       | 1         | 0.24%   |
| SHARETRONIC         | 1         | 0.24%   |
| Qumo                | 1         | 0.24%   |
| Patriot             | 1         | 0.24%   |
| GOODRAM             | 1         | 0.24%   |
| Goldkey             | 1         | 0.24%   |
| Crucial             | 1         | 0.24%   |
| Unknown             | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 12        | 2.63%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 11        | 2.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 8         | 1.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 7         | 1.54%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 7         | 1.54%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 7         | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 7         | 1.54%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 7         | 1.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 1.32%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 6         | 1.32%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s               | 6         | 1.32%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 5         | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 1.1%    |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 4         | 0.88%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s               | 4         | 0.88%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.88%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.88%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s              | 4         | 0.88%   |
| V-GeN RAM D4R8GS24A8R 8GB SODIMM DDR4 2400MT/s                      | 3         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 3         | 0.66%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.66%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s              | 3         | 0.66%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s           | 3         | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s           | 3         | 0.66%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.66%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s               | 3         | 0.66%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s                 | 3         | 0.66%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 0.66%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 3         | 0.66%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 3         | 0.66%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 3         | 0.66%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 3         | 0.66%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s                | 3         | 0.66%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 3         | 0.66%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 3         | 0.66%   |
| Kingston RAM ACR26D4S9S1ME-4 4GB SODIMM DDR4 2667MT/s               | 3         | 0.66%   |
| Corsair RAM CMSX8GX4M1A2666C18 8192MB SODIMM DDR4 2667MT/s          | 3         | 0.66%   |
| V-GeN RAM D3R4GS16B8R 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 2         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 2         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                          | 2         | 0.44%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 2         | 0.44%   |
| Team RAM TEAMGROUP-SD3-1600 4GB SODIMM DDR3 1600MT/s                | 2         | 0.44%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                        | 2         | 0.44%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                        | 2         | 0.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 2         | 0.44%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.44%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s           | 2         | 0.44%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s          | 2         | 0.44%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 2         | 0.44%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s               | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 152       | 46.91%  |
| DDR4    | 140       | 43.21%  |
| DDR2    | 12        | 3.7%    |
| LPDDR4  | 7         | 2.16%   |
| LPDDR3  | 6         | 1.85%   |
| SDRAM   | 5         | 1.54%   |
| DRAM    | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 306       | 94.15%  |
| Row Of Chips | 16        | 4.92%   |
| Chip         | 3         | 0.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 167       | 44.89%  |
| 8192  | 110       | 29.57%  |
| 2048  | 65        | 17.47%  |
| 16384 | 16        | 4.3%    |
| 1024  | 7         | 1.88%   |
| 32768 | 6         | 1.61%   |
| 512   | 1         | 0.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 114       | 30.08%  |
| 2667    | 72        | 19%     |
| 2400    | 36        | 9.5%    |
| 3200    | 34        | 8.97%   |
| 2133    | 22        | 5.8%    |
| 1334    | 22        | 5.8%    |
| 1333    | 18        | 4.75%   |
| 3266    | 12        | 3.17%   |
| 1067    | 7         | 1.85%   |
| Unknown | 7         | 1.85%   |
| 800     | 6         | 1.58%   |
| 667     | 6         | 1.58%   |
| 8400    | 4         | 1.06%   |
| 4266    | 4         | 1.06%   |
| 4199    | 3         | 0.79%   |
| 1867    | 3         | 0.79%   |
| 533     | 3         | 0.79%   |
| 4267    | 2         | 0.53%   |
| 2048    | 2         | 0.53%   |
| 1776    | 1         | 0.26%   |
| 333     | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 6         | 60%     |
| Canon              | 2         | 20%     |
| Brother Industries | 2         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L312 Series | 2         | 20%     |
| Seiko Epson L220 Series | 2         | 20%     |
| Canon iP2700 series     | 2         | 20%     |
| Brother DCP-T300        | 2         | 20%     |
| Seiko Epson L405 Series | 1         | 10%     |
| Seiko Epson L355 Series | 1         | 10%     |

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


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 4400F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 155       | 29.3%   |
| IMC Networks                           | 77        | 14.56%  |
| Realtek Semiconductor                  | 47        | 8.88%   |
| Acer                                   | 46        | 8.7%    |
| Sunplus Innovation Technology          | 36        | 6.81%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 4.91%   |
| Quanta                                 | 25        | 4.73%   |
| Syntek                                 | 24        | 4.54%   |
| Suyin                                  | 18        | 3.4%    |
| Alcor Micro                            | 18        | 3.4%    |
| Microdia                               | 15        | 2.84%   |
| Lite-On Technology                     | 9         | 1.7%    |
| Apple                                  | 6         | 1.13%   |
| Importek                               | 5         | 0.95%   |
| Ricoh                                  | 4         | 0.76%   |
| Silicon Motion                         | 3         | 0.57%   |
| Luxvisions Innotech Limited            | 2         | 0.38%   |
| Lenovo                                 | 2         | 0.38%   |
| Jieli Technology                       | 2         | 0.38%   |
| Sunplus Technology                     | 1         | 0.19%   |
| Primax Electronics                     | 1         | 0.19%   |
| Pixart Imaging                         | 1         | 0.19%   |
| Omnivision                             | 1         | 0.19%   |
| Logitech                               | 1         | 0.19%   |
| Genesys Logic                          | 1         | 0.19%   |
| DigiTech                               | 1         | 0.19%   |
| ALi                                    | 1         | 0.19%   |
| 2M UVC CAMERA                          | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                               | 26        | 4.9%    |
| IMC Networks USB2.0 HD UVC WebCam                               | 22        | 4.14%   |
| Chicony integrated camera                                       | 21        | 3.95%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 17        | 3.2%    |
| IMC Networks USB2.0 VGA UVC WebCam                              | 16        | 3.01%   |
| Chicony USB2.0 HD UVC WebCam                                    | 15        | 2.82%   |
| Syntek Integrated Camera                                        | 13        | 2.45%   |
| Acer Lenovo EasyCamera                                          | 11        | 2.07%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 10        | 1.88%   |
| IMC Networks Lenovo EasyCamera                                  | 10        | 1.88%   |
| Chicony Lenovo EasyCamera                                       | 9         | 1.69%   |
| Sunplus ASUS USB2.0 Webcam                                      | 8         | 1.51%   |
| Realtek Integrated_Webcam_HD                                    | 8         | 1.51%   |
| IMC Networks Integrated Camera                                  | 8         | 1.51%   |
| IMC Networks EasyCamera                                         | 8         | 1.51%   |
| Chicony HP TrueVision HD Camera                                 | 7         | 1.32%   |
| Chicony HP Truevision HD                                        | 7         | 1.32%   |
| Alcor Micro Asus Integrated Webcam                              | 7         | 1.32%   |
| Acer Integrated Camera                                          | 7         | 1.32%   |
| Syntek EasyCamera                                               | 6         | 1.13%   |
| Sunplus Integrated_Webcam_HD                                    | 6         | 1.13%   |
| Quanta HP TrueVision HD Camera                                  | 6         | 1.13%   |
| Quanta HD User Facing                                           | 6         | 1.13%   |
| Microdia Integrated_Webcam_HD                                   | 6         | 1.13%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 6         | 1.13%   |
| Suyin 1.3M HD WebCam                                            | 5         | 0.94%   |
| Realtek USB2.0 HD UVC WebCam                                    | 5         | 0.94%   |
| Realtek USB Camera                                              | 5         | 0.94%   |
| Microdia Integrated Webcam                                      | 5         | 0.94%   |
| Lite-On Integrated Camera                                       | 5         | 0.94%   |
| Chicony EasyCamera                                              | 5         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 5         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 5         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD         | 5         | 0.94%   |
| Acer HD Webcam                                                  | 5         | 0.94%   |
| Acer EasyCamera                                                 | 5         | 0.94%   |
| Acer BisonCam, NB Pro                                           | 5         | 0.94%   |
| Syntek Lenovo EasyCamera                                        | 4         | 0.75%   |
| Sunplus HP TrueVision HD Camera                                 | 4         | 0.75%   |
| Sunplus HD WebCam                                               | 4         | 0.75%   |
| Quanta HD WebCam                                                | 4         | 0.75%   |
| Chicony Acer CrystalEye Webcam                                  | 4         | 0.75%   |
| Alcor Micro USB 2.0 PC cam                                      | 4         | 0.75%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 3         | 0.56%   |
| Sunplus Integrated Webcam                                       | 3         | 0.56%   |
| Sunplus HP Truevision HD                                        | 3         | 0.56%   |
| Realtek HP Truevision HD                                        | 3         | 0.56%   |
| Realtek HD WebCam                                               | 3         | 0.56%   |
| Quanta VGA WebCam                                               | 3         | 0.56%   |
| IMC Networks USB2.0 UVC 2M WebCam                               | 3         | 0.56%   |
| IMC Networks USB Camera                                         | 3         | 0.56%   |
| Chicony USB2.0 0.3M UVC WebCam                                  | 3         | 0.56%   |
| Chicony TOSHIBA Web Camera - HD                                 | 3         | 0.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 3         | 0.56%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 3         | 0.56%   |
| Acer ThinkPad Integrated Camera                                 | 3         | 0.56%   |
| Acer Lenovo Integrated Webcam                                   | 3         | 0.56%   |
| Suyin Integrated_Webcam_HD                                      | 2         | 0.38%   |
| Suyin HD WebCam                                                 | 2         | 0.38%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 2         | 0.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 28        | 33.33%  |
| Elan Microelectronics      | 17        | 20.24%  |
| LighTuning Technology      | 11        | 13.1%   |
| Synaptics                  | 10        | 11.9%   |
| Shenzhen Goodix Technology | 8         | 9.52%   |
| AuthenTec                  | 5         | 5.95%   |
| Upek                       | 3         | 3.57%   |
| STMicroelectronics         | 2         | 2.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                  | 11        | 13.1%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 10        | 11.9%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 7         | 8.33%   |
| Elan ELAN:ARM-M4                                       | 6         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 5.95%   |
| Shenzhen Goodix  FingerPrint Device                    | 5         | 5.95%   |
| Validity Sensors Swipe Fingerprint Sensor              | 4         | 4.76%   |
| Unknown                                                | 4         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 3.57%   |
| Validity Sensors VFS Fingerprint sensor                | 3         | 3.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 3.57%   |
| Synaptics  WBDI                                        | 3         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 3         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 3.57%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 2.38%   |
| Validity Sensors VFS491                                | 2         | 2.38%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 2.38%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 2         | 2.38%   |
| AuthenTec AES1600                                      | 2         | 2.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 1.19%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 1.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 1.19%   |
| AuthenTec AES2810                                      | 1         | 1.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 12        | 52.17%  |
| Upek        | 4         | 17.39%  |
| Alcor Micro | 3         | 13.04%  |
| O2 Micro    | 2         | 8.7%    |
| Lenovo      | 2         | 8.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 30.43%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 17.39%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 13.04%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 8.7%    |
| Lenovo Integrated Smart Card Reader                                          | 2         | 8.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8.7%    |
| Broadcom 58200                                                               | 2         | 8.7%    |
| Broadcom 5880                                                                | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 408       | 67.89%  |
| 1     | 147       | 24.46%  |
| 2     | 41        | 6.82%   |
| 3     | 4         | 0.67%   |
| 6     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 84        | 36.36%  |
| Graphics card            | 50        | 21.65%  |
| Net/wireless             | 25        | 10.82%  |
| Chipcard                 | 22        | 9.52%   |
| Bluetooth                | 15        | 6.49%   |
| Multimedia controller    | 12        | 5.19%   |
| Communication controller | 5         | 2.16%   |
| Camera                   | 5         | 2.16%   |
| Net/ethernet             | 4         | 1.73%   |
| Storage                  | 3         | 1.3%    |
| Flash memory             | 2         | 0.87%   |
| Video                    | 1         | 0.43%   |
| Sound                    | 1         | 0.43%   |
| Network                  | 1         | 0.43%   |
| Card reader              | 1         | 0.43%   |

