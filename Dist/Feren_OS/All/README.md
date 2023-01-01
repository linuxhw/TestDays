Feren OS - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Feren OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Feren_OS/Desktop/README.md) and [notebooks](/Dist/Feren_OS/Notebook/README.md).

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

Total: 140

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte   | MJPLNBB-00                  | Desktop     | [a9e701a27a](https://linux-hardware.org/?probe=a9e701a27a) | Dec 23, 2022 |
| Acer       | Aspire E5-773               | Notebook    | [d8d1898a3b](https://linux-hardware.org/?probe=d8d1898a3b) | Dec 17, 2022 |
| Apple      | MacBookAir6,2               | Notebook    | [0d098f7432](https://linux-hardware.org/?probe=0d098f7432) | Nov 29, 2022 |
| MSI        | B350M MORTAR                | Desktop     | [f85255857d](https://linux-hardware.org/?probe=f85255857d) | Nov 17, 2022 |
| HP         | Pavilion Laptop 14-bf0xx    | Notebook    | [79144ee806](https://linux-hardware.org/?probe=79144ee806) | Oct 25, 2022 |
| MSI        | B350M MORTAR                | Desktop     | [9312be9510](https://linux-hardware.org/?probe=9312be9510) | Oct 23, 2022 |
| ASUSTek    | PRIME B450M-A               | Desktop     | [f13203e3ce](https://linux-hardware.org/?probe=f13203e3ce) | Oct 14, 2022 |
| HP         | Pavilion Laptop 14-bf0xx    | Notebook    | [866d1ad750](https://linux-hardware.org/?probe=866d1ad750) | Oct 07, 2022 |
| MSI        | B350M MORTAR                | Desktop     | [4e56098080](https://linux-hardware.org/?probe=4e56098080) | Oct 04, 2022 |
| ASUSTek    | N750JV                      | Notebook    | [04cc8b4e36](https://linux-hardware.org/?probe=04cc8b4e36) | Sep 24, 2022 |
| ASUSTek    | Z97-A                       | Desktop     | [14fa58515f](https://linux-hardware.org/?probe=14fa58515f) | Aug 13, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop M350... | Notebook    | [b2b969b0e3](https://linux-hardware.org/?probe=b2b969b0e3) | Aug 01, 2022 |
| HP         | Pavilion Laptop 14-bf0xx    | Notebook    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| Gigabyte   | Z170X-UD3-CF                | Desktop     | [aecc3e1863](https://linux-hardware.org/?probe=aecc3e1863) | Jul 06, 2022 |
| ASUSTek    | PRIME Z270-A                | Desktop     | [0f85d8c023](https://linux-hardware.org/?probe=0f85d8c023) | Jun 19, 2022 |
| MSI        | GS66 Stealth 10SE           | Notebook    | [fbdc7a2279](https://linux-hardware.org/?probe=fbdc7a2279) | Jun 17, 2022 |
| ASUSTek    | PRIME Z270-A                | Desktop     | [dd22c99aac](https://linux-hardware.org/?probe=dd22c99aac) | Jun 14, 2022 |
| Gigabyte   | F2A68HM-DS2                 | Desktop     | [1fa6bb2d62](https://linux-hardware.org/?probe=1fa6bb2d62) | May 26, 2022 |
| Dell       | Latitude E5570              | Notebook    | [f132300275](https://linux-hardware.org/?probe=f132300275) | Feb 23, 2022 |
| ASRock     | Z68 Pro3                    | Desktop     | [4cdd6daf44](https://linux-hardware.org/?probe=4cdd6daf44) | Jan 19, 2022 |
| ASUSTek    | S400CA                      | Notebook    | [3d2d24d90e](https://linux-hardware.org/?probe=3d2d24d90e) | Jan 15, 2022 |
| ASUSTek    | ROG Zephyrus M16 GU603HE... | Notebook    | [a53f185048](https://linux-hardware.org/?probe=a53f185048) | Dec 22, 2021 |
| LattePanda | Alpha                       | Desktop     | [73f961d1b6](https://linux-hardware.org/?probe=73f961d1b6) | Dec 21, 2021 |
| ASUSTek    | ROG Zephyrus M16 GU603HE... | Notebook    | [21ea8cfa3b](https://linux-hardware.org/?probe=21ea8cfa3b) | Dec 16, 2021 |
| ASUSTek    | ROG Zephyrus M16 GU603HE... | Notebook    | [cd47b9ae21](https://linux-hardware.org/?probe=cd47b9ae21) | Dec 05, 2021 |
| ASUSTek    | P552LJ                      | Notebook    | [6dbe422798](https://linux-hardware.org/?probe=6dbe422798) | Nov 29, 2021 |
| MSI        | GP72 7RDX                   | Notebook    | [502ad3be8e](https://linux-hardware.org/?probe=502ad3be8e) | Nov 29, 2021 |
| HP         | 829A                        | Mini pc     | [a906b7c0d4](https://linux-hardware.org/?probe=a906b7c0d4) | Nov 20, 2021 |
| HP         | 829A                        | Mini pc     | [0eabb0317b](https://linux-hardware.org/?probe=0eabb0317b) | Nov 20, 2021 |
| MSI        | GE66 Raider 11UG            | Notebook    | [fe677aa4e9](https://linux-hardware.org/?probe=fe677aa4e9) | Nov 20, 2021 |
| ASUSTek    | ROG Zephyrus M16 GU603HE... | Notebook    | [6d92264040](https://linux-hardware.org/?probe=6d92264040) | Nov 14, 2021 |
| ASUSTek    | ROG Zephyrus M16 GU603HE... | Notebook    | [b3836e81d2](https://linux-hardware.org/?probe=b3836e81d2) | Nov 13, 2021 |
| ASUSTek    | PRIME B450M-A               | Desktop     | [1a8d172b1a](https://linux-hardware.org/?probe=1a8d172b1a) | Nov 02, 2021 |
| MSI        | H61M-P20                    | Desktop     | [4c9df75eee](https://linux-hardware.org/?probe=4c9df75eee) | Oct 15, 2021 |
| ASUSTek    | PRIME B350-PLUS             | Desktop     | [97dbb56e7f](https://linux-hardware.org/?probe=97dbb56e7f) | Oct 08, 2021 |
| MSI        | Traveller 1591              | Notebook    | [46430a6e00](https://linux-hardware.org/?probe=46430a6e00) | Oct 04, 2021 |
| Pegatron   | Eureka3                     | Desktop     | [1a6858321a](https://linux-hardware.org/?probe=1a6858321a) | Sep 06, 2021 |
| Pegatron   | Eureka3                     | Desktop     | [c68cf534fd](https://linux-hardware.org/?probe=c68cf534fd) | Sep 06, 2021 |
| HP         | Pavilion x360 Convertibl... | Convertible | [0a3ff1ead5](https://linux-hardware.org/?probe=0a3ff1ead5) | Aug 25, 2021 |
| HP         | Pavilion x360 Convertibl... | Convertible | [8091745305](https://linux-hardware.org/?probe=8091745305) | Aug 25, 2021 |
| ASUSTek    | PRIME B450M-A               | Desktop     | [446300d07d](https://linux-hardware.org/?probe=446300d07d) | Aug 04, 2021 |
| Dell       | Latitude E5430 vPro         | Notebook    | [8c45da134f](https://linux-hardware.org/?probe=8c45da134f) | Aug 01, 2021 |
| Microsoft  | Surface Pro 3               | Tablet      | [65f1f58d93](https://linux-hardware.org/?probe=65f1f58d93) | Jul 15, 2021 |
| ASUSTek    | PRIME H410M-E               | Desktop     | [3758d2a6b8](https://linux-hardware.org/?probe=3758d2a6b8) | Jul 09, 2021 |
| HP         | 82FE 11                     | Desktop     | [acabfe917b](https://linux-hardware.org/?probe=acabfe917b) | Jun 22, 2021 |
| ASRock     | H61M-VS                     | Desktop     | [cb1c07fa68](https://linux-hardware.org/?probe=cb1c07fa68) | Jun 17, 2021 |
| Lenovo     | ThinkPad X230 2325AT6       | Notebook    | [f0a5e0cbb6](https://linux-hardware.org/?probe=f0a5e0cbb6) | Jun 13, 2021 |
| ASUSTek    | VivoBook_ASUS Laptop E21... | Notebook    | [676f8cfa11](https://linux-hardware.org/?probe=676f8cfa11) | Jun 12, 2021 |
| Unknown    | Unknown                     | Notebook    | [16d75c0003](https://linux-hardware.org/?probe=16d75c0003) | Jun 11, 2021 |
| Lenovo     | ThinkPad X230 2325AT6       | Notebook    | [049671564e](https://linux-hardware.org/?probe=049671564e) | May 27, 2021 |
| Lenovo     | ThinkPad X230 2325AT6       | Notebook    | [cb5051e015](https://linux-hardware.org/?probe=cb5051e015) | May 27, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | Desktop     | [56b16c9c71](https://linux-hardware.org/?probe=56b16c9c71) | May 26, 2021 |
| Dell       | 0XHYJF A01                  | All in one  | [f61158882e](https://linux-hardware.org/?probe=f61158882e) | May 21, 2021 |
| ASUSTek    | TUF Gaming X570-PLUS        | Desktop     | [fdff074ae2](https://linux-hardware.org/?probe=fdff074ae2) | May 21, 2021 |
| Dell       | 0XHYJF A01                  | All in one  | [0d1f1e6906](https://linux-hardware.org/?probe=0d1f1e6906) | May 20, 2021 |
| MSI        | 2AE0                        | Desktop     | [cdddabf42c](https://linux-hardware.org/?probe=cdddabf42c) | May 19, 2021 |
| ASRock     | H61M-VS                     | Desktop     | [9e701873b1](https://linux-hardware.org/?probe=9e701873b1) | May 09, 2021 |
| ASRock     | H61M-VS                     | Desktop     | [59a6774cd5](https://linux-hardware.org/?probe=59a6774cd5) | May 09, 2021 |
| Lenovo     | XiaoXin Air 12 80UN         | Notebook    | [210f81171b](https://linux-hardware.org/?probe=210f81171b) | May 08, 2021 |
| HP         | Pavilion Gaming Laptop 1... | Notebook    | [6654328a0f](https://linux-hardware.org/?probe=6654328a0f) | May 05, 2021 |
| Lenovo     | Legion Y7000P 81LD          | Notebook    | [e3b22a36fb](https://linux-hardware.org/?probe=e3b22a36fb) | Apr 22, 2021 |
| Lenovo     | Legion Y7000P 81LD          | Notebook    | [f5715022b7](https://linux-hardware.org/?probe=f5715022b7) | Apr 22, 2021 |
| Wortmann   | TERRA_PC                    | Desktop     | [9224f13a87](https://linux-hardware.org/?probe=9224f13a87) | Apr 09, 2021 |
| Wortmann   | TERRA_PC                    | Desktop     | [c107b4f1a1](https://linux-hardware.org/?probe=c107b4f1a1) | Mar 31, 2021 |
| Dell       | 0FH884                      | Desktop     | [3f73f703ea](https://linux-hardware.org/?probe=3f73f703ea) | Feb 25, 2021 |
| Dell       | 0FH884                      | Desktop     | [9ef7d7ac26](https://linux-hardware.org/?probe=9ef7d7ac26) | Feb 24, 2021 |
| Gigabyte   | EX58-UD5                    | Desktop     | [9743cd82ce](https://linux-hardware.org/?probe=9743cd82ce) | Feb 01, 2021 |
| Pegatron   | 2AC2A                       | Desktop     | [c80b26e32c](https://linux-hardware.org/?probe=c80b26e32c) | Jan 21, 2021 |
| Sony       | VPCEE4J1E                   | Notebook    | [d919affcfd](https://linux-hardware.org/?probe=d919affcfd) | Jan 14, 2021 |
| Lenovo     | XiaoXin Air 12 80UN         | Notebook    | [7339b28f1b](https://linux-hardware.org/?probe=7339b28f1b) | Dec 26, 2020 |
| Lenovo     | XiaoXin Air 12 80UN         | Notebook    | [06c54d29ce](https://linux-hardware.org/?probe=06c54d29ce) | Dec 26, 2020 |
| ASUSTek    | H87-PLUS                    | Desktop     | [563b11dfc7](https://linux-hardware.org/?probe=563b11dfc7) | Nov 27, 2020 |
| ASUSTek    | H87-PLUS                    | Desktop     | [7b22071212](https://linux-hardware.org/?probe=7b22071212) | Nov 27, 2020 |
| MSI        | B360M Xtreme                | Desktop     | [68ebbb560b](https://linux-hardware.org/?probe=68ebbb560b) | Nov 20, 2020 |
| Acer       | NG-VX5-591G-52AT            | Notebook    | [304a828df3](https://linux-hardware.org/?probe=304a828df3) | Nov 20, 2020 |
| MSI        | MPG X570 GAMING PLUS        | Desktop     | [a1f9dad859](https://linux-hardware.org/?probe=a1f9dad859) | Nov 07, 2020 |
| MSI        | MPG X570 GAMING PLUS        | Desktop     | [f78c0034e0](https://linux-hardware.org/?probe=f78c0034e0) | Nov 07, 2020 |
| HP         | ProBook 6560b               | Notebook    | [1e12011c45](https://linux-hardware.org/?probe=1e12011c45) | Nov 05, 2020 |
| ASUSTek    | X541NA                      | Notebook    | [fa42a090b5](https://linux-hardware.org/?probe=fa42a090b5) | Nov 03, 2020 |
| Acer       | Aspire TC-105               | Desktop     | [954d6d151c](https://linux-hardware.org/?probe=954d6d151c) | Oct 17, 2020 |
| Acer       | Aspire TC-105               | Desktop     | [4897bba76b](https://linux-hardware.org/?probe=4897bba76b) | Oct 17, 2020 |
| Sony       | SVF15318SNB                 | Notebook    | [600b06bc21](https://linux-hardware.org/?probe=600b06bc21) | Oct 15, 2020 |
| Apple      | Mac-F2268CC8                | All in one  | [3d6de31d0c](https://linux-hardware.org/?probe=3d6de31d0c) | Oct 09, 2020 |
| Lenovo     | ThinkPad X230 2325AT6       | Notebook    | [fb75c1edd7](https://linux-hardware.org/?probe=fb75c1edd7) | Oct 05, 2020 |
| ASUSTek    | PRIME H410M-E               | Desktop     | [c64e54f364](https://linux-hardware.org/?probe=c64e54f364) | Sep 20, 2020 |
| ASUSTek    | PRIME H410M-E               | Desktop     | [df8fbe9e18](https://linux-hardware.org/?probe=df8fbe9e18) | Sep 20, 2020 |
| Acer       | Predator G5910              | Desktop     | [7c7e146182](https://linux-hardware.org/?probe=7c7e146182) | Sep 19, 2020 |
| Lenovo     | G550 2958                   | Notebook    | [6c33f8ea14](https://linux-hardware.org/?probe=6c33f8ea14) | Sep 13, 2020 |
| Acer       | Predator G5910              | Desktop     | [bc07c92db3](https://linux-hardware.org/?probe=bc07c92db3) | Sep 10, 2020 |
| Lenovo     | ThinkPad X230 2325AT6       | Notebook    | [59ed33b893](https://linux-hardware.org/?probe=59ed33b893) | Sep 06, 2020 |
| ZOTAC      | ZBOX-CI527/CI547            | Mini pc     | [efb03db319](https://linux-hardware.org/?probe=efb03db319) | Sep 02, 2020 |
| HUAWEI     | BOHK-WAX9X                  | Notebook    | [58c99091e7](https://linux-hardware.org/?probe=58c99091e7) | Aug 29, 2020 |
| Toshiba    | Satellite T135D             | Notebook    | [e59691cfe7](https://linux-hardware.org/?probe=e59691cfe7) | Aug 28, 2020 |
| Apple      | Mac-81E3E92DD6088272 iMa... | All in one  | [2f7b60e4cd](https://linux-hardware.org/?probe=2f7b60e4cd) | Aug 12, 2020 |
| Apple      | Mac-F2238BAE iMac11,3       | All in one  | [943de78484](https://linux-hardware.org/?probe=943de78484) | Aug 10, 2020 |
| Apple      | Mac-F2238BAE iMac11,3       | All in one  | [a22cc9f46c](https://linux-hardware.org/?probe=a22cc9f46c) | Aug 10, 2020 |
| ASUSTek    | H81-PLUS                    | Desktop     | [0e79ae7820](https://linux-hardware.org/?probe=0e79ae7820) | Jul 16, 2020 |
| ASUSTek    | X550CA                      | Notebook    | [7f2bf35eb8](https://linux-hardware.org/?probe=7f2bf35eb8) | Jun 30, 2020 |
| ASUSTek    | X550CA                      | Notebook    | [fe533b45dd](https://linux-hardware.org/?probe=fe533b45dd) | Jun 17, 2020 |
| ASUSTek    | X550CA                      | Notebook    | [e07d0dce49](https://linux-hardware.org/?probe=e07d0dce49) | Jun 17, 2020 |
| ASRock     | B75 Pro3-M                  | Desktop     | [83788eaf01](https://linux-hardware.org/?probe=83788eaf01) | Jun 10, 2020 |
| Lenovo     | ThinkPad X230 2325AT6       | Notebook    | [b7b58ba2d6](https://linux-hardware.org/?probe=b7b58ba2d6) | Jun 10, 2020 |
| HP         | EliteBook Folio 1040 G1     | Notebook    | [c7abaff76b](https://linux-hardware.org/?probe=c7abaff76b) | Jun 02, 2020 |
| HP         | ProLiant DL380p Gen8        | Server      | [f2602534be](https://linux-hardware.org/?probe=f2602534be) | May 25, 2020 |
| HP         | ProLiant DL380p Gen8        | Server      | [55a7b7ec76](https://linux-hardware.org/?probe=55a7b7ec76) | May 25, 2020 |
| HP         | ProLiant DL380p Gen8        | Server      | [05fab72756](https://linux-hardware.org/?probe=05fab72756) | May 25, 2020 |
| ASUSTek    | H81-PLUS                    | Desktop     | [d5ecf72e99](https://linux-hardware.org/?probe=d5ecf72e99) | May 24, 2020 |
| Lenovo     | ThinkPad X230 2325AT6       | Notebook    | [f3c754042c](https://linux-hardware.org/?probe=f3c754042c) | May 16, 2020 |
| Lenovo     | ThinkPad X230 2325AT6       | Notebook    | [cfa1314238](https://linux-hardware.org/?probe=cfa1314238) | May 04, 2020 |
| Apple      | MacBookPro8,1               | Notebook    | [b2b19968b0](https://linux-hardware.org/?probe=b2b19968b0) | May 03, 2020 |
| Lenovo     | ThinkPad X240 20AMS72901    | Notebook    | [ad1e10654b](https://linux-hardware.org/?probe=ad1e10654b) | Apr 30, 2020 |
| MSI        | B450M MORTAR TITANIUM       | Desktop     | [f347a42df8](https://linux-hardware.org/?probe=f347a42df8) | Apr 27, 2020 |
| MSI        | B450M MORTAR TITANIUM       | Desktop     | [4037a9fe71](https://linux-hardware.org/?probe=4037a9fe71) | Apr 24, 2020 |
| Gigabyte   | GA-78LMT-USB3 R2 sex        | Desktop     | [208cce85dd](https://linux-hardware.org/?probe=208cce85dd) | Apr 24, 2020 |
| Dell       | 0200DY A03                  | Desktop     | [2b2aa48899](https://linux-hardware.org/?probe=2b2aa48899) | Apr 13, 2020 |
| Dell       | 0T656F A01                  | Desktop     | [ea7fa24667](https://linux-hardware.org/?probe=ea7fa24667) | Apr 09, 2020 |
| Dell       | 0T656F A01                  | Desktop     | [24a2c39ee5](https://linux-hardware.org/?probe=24a2c39ee5) | Apr 09, 2020 |
| Dell       | 0T656F A01                  | Desktop     | [84566f9a9b](https://linux-hardware.org/?probe=84566f9a9b) | Apr 09, 2020 |
| Fujitsu    | LIFEBOOK E554               | Notebook    | [bb918daf7b](https://linux-hardware.org/?probe=bb918daf7b) | Mar 29, 2020 |
| Lenovo     | MAHOBAY                     | Desktop     | [651d7ac7be](https://linux-hardware.org/?probe=651d7ac7be) | Feb 28, 2020 |
| Lenovo     | MAHOBAY                     | Desktop     | [5b33f9565a](https://linux-hardware.org/?probe=5b33f9565a) | Feb 28, 2020 |
| Foxconn    | 2ABF                        | Desktop     | [e2858c8dd1](https://linux-hardware.org/?probe=e2858c8dd1) | Feb 16, 2020 |
| Acer       | Aspire 5733Z                | Notebook    | [ebca80c932](https://linux-hardware.org/?probe=ebca80c932) | Jan 04, 2020 |
| Acer       | Aspire 5733Z                | Notebook    | [05ef4a2f12](https://linux-hardware.org/?probe=05ef4a2f12) | Jan 02, 2020 |
| Acer       | Aspire 5733Z                | Notebook    | [b1af19a6ad](https://linux-hardware.org/?probe=b1af19a6ad) | Jan 02, 2020 |
| Medion     | H61H2-LM3 V1.0              | Desktop     | [32f60e252b](https://linux-hardware.org/?probe=32f60e252b) | Jan 02, 2020 |
| Dell       | Inspiron 3421               | Notebook    | [17f334232d](https://linux-hardware.org/?probe=17f334232d) | Jan 01, 2020 |
| Medion     | H61H2-LM3 V1.0              | Desktop     | [070631b0f3](https://linux-hardware.org/?probe=070631b0f3) | Dec 31, 2019 |
| PCWare     | IPMH81G1                    | Desktop     | [e962036292](https://linux-hardware.org/?probe=e962036292) | Dec 29, 2019 |
| PCWare     | IPMH81G1                    | Desktop     | [ffc38dcd04](https://linux-hardware.org/?probe=ffc38dcd04) | Dec 29, 2019 |
| Panasonic  | CF-J10YYBHR                 | Notebook    | [e00043a374](https://linux-hardware.org/?probe=e00043a374) | Sep 27, 2019 |
| Panasonic  | CF-J10YYBHR                 | Notebook    | [0005e1a411](https://linux-hardware.org/?probe=0005e1a411) | Aug 21, 2019 |
| Exo        | CloudbookE15                | Notebook    | [9a16d4a087](https://linux-hardware.org/?probe=9a16d4a087) | Aug 19, 2019 |
| Lenovo     | Yoga 730-15IKB 81CU         | Convertible | [27307bc4cf](https://linux-hardware.org/?probe=27307bc4cf) | Aug 02, 2019 |
| ASUSTek    | PRIME Z370-A                | Desktop     | [6c0faea524](https://linux-hardware.org/?probe=6c0faea524) | Aug 01, 2019 |
| Lenovo     | G50-45 80E3                 | Notebook    | [440ce358c0](https://linux-hardware.org/?probe=440ce358c0) | May 04, 2019 |
| Lenovo     | G50-45 80E3                 | Notebook    | [fa158b6a96](https://linux-hardware.org/?probe=fa158b6a96) | Apr 16, 2019 |
| ASUSTek    | STRIKER II FORMULA          | Desktop     | [17ab95ea83](https://linux-hardware.org/?probe=17ab95ea83) | Jan 22, 2019 |
| ASUSTek    | STRIKER II FORMULA          | Desktop     | [a9a4ca4d08](https://linux-hardware.org/?probe=a9a4ca4d08) | Jan 21, 2019 |
| ASUSTek    | PRIME Z370-A                | Desktop     | [6649ff8a00](https://linux-hardware.org/?probe=6649ff8a00) | Dec 14, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Feren OS 20.04   | 50        | 57.47%  |
| Feren OS 18.04   | 35        | 40.23%  |
| Feren OS 2018.10 | 2         | 2.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Feren OS | 85        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.11.0-37-generic       | 7         | 6.93%   |
| 5.3.0-46-generic        | 5         | 4.95%   |
| 5.8.0-55-generic        | 4         | 3.96%   |
| 5.8.0-53-generic        | 4         | 3.96%   |
| 5.4.0-42-generic        | 4         | 3.96%   |
| 5.0.0-37-generic        | 4         | 3.96%   |
| 5.8.0-48-generic        | 3         | 2.97%   |
| 5.4.0-52-generic        | 3         | 2.97%   |
| 5.3.0-51-generic        | 3         | 2.97%   |
| 5.15.0-48-generic       | 3         | 2.97%   |
| 5.8.0-50-generic        | 2         | 1.98%   |
| 5.8.0-36-generic        | 2         | 1.98%   |
| 5.4.0-54-generic        | 2         | 1.98%   |
| 5.4.0-48-generic        | 2         | 1.98%   |
| 5.4.0-47-generic        | 2         | 1.98%   |
| 5.4.0-45-generic        | 2         | 1.98%   |
| 5.3.0-59-generic        | 2         | 1.98%   |
| 5.3.0-53-generic        | 2         | 1.98%   |
| 5.15.0-53-generic       | 2         | 1.98%   |
| 5.11.0-40-generic       | 2         | 1.98%   |
| 5.11.0-27-generic       | 2         | 1.98%   |
| 4.15.0-48-generic       | 2         | 1.98%   |
| 5.8.0-44-generic        | 1         | 0.99%   |
| 5.8.0-40-generic        | 1         | 0.99%   |
| 5.8.0-29-generic        | 1         | 0.99%   |
| 5.4.66-xanmod1          | 1         | 0.99%   |
| 5.4.0-77-generic        | 1         | 0.99%   |
| 5.4.0-74-generic        | 1         | 0.99%   |
| 5.4.0-72-generic        | 1         | 0.99%   |
| 5.4.0-58-generic        | 1         | 0.99%   |
| 5.4.0-51-generic        | 1         | 0.99%   |
| 5.4.0-37-generic        | 1         | 0.99%   |
| 5.4.0-31-generic        | 1         | 0.99%   |
| 5.3.0-42-generic        | 1         | 0.99%   |
| 5.3.0-40-generic        | 1         | 0.99%   |
| 5.3.0-28-generic        | 1         | 0.99%   |
| 5.17.5-76051705-generic | 1         | 0.99%   |
| 5.15.6-051506-generic   | 1         | 0.99%   |
| 5.15.0-56-generic       | 1         | 0.99%   |
| 5.15.0-50-generic       | 1         | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 21.11%  |
| 5.8.0   | 17        | 18.89%  |
| 5.3.0   | 14        | 15.56%  |
| 5.11.0  | 12        | 13.33%  |
| 5.15.0  | 9         | 10%     |
| 4.15.0  | 6         | 6.67%   |
| 5.13.0  | 5         | 5.56%   |
| 5.0.0   | 5         | 5.56%   |
| 5.4.66  | 1         | 1.11%   |
| 5.17.5  | 1         | 1.11%   |
| 5.15.6  | 1         | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 21.35%  |
| 5.8     | 17        | 19.1%   |
| 5.3     | 14        | 15.73%  |
| 5.11    | 12        | 13.48%  |
| 5.15    | 10        | 11.24%  |
| 4.15    | 6         | 6.74%   |
| 5.13    | 5         | 5.62%   |
| 5.0     | 5         | 5.62%   |
| 5.17    | 1         | 1.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 85        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE        | 47        | 52.81%  |
| KDE5       | 28        | 31.46%  |
| Unknown    | 9         | 10.11%  |
| X-Cinnamon | 3         | 3.37%   |
| GNOME      | 2         | 2.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 85        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 69        | 81.18%  |
| LightDM | 12        | 14.12%  |
| TDM     | 4         | 4.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 23        | 26.44%  |
| en_GB   | 16        | 18.39%  |
| de_CH   | 7         | 8.05%   |
| Unknown | 7         | 8.05%   |
| de_DE   | 6         | 6.9%    |
| en_AU   | 5         | 5.75%   |
| en_IN   | 3         | 3.45%   |
| pt_BR   | 2         | 2.3%    |
| nl_BE   | 2         | 2.3%    |
| es_VE   | 2         | 2.3%    |
| en_CA   | 2         | 2.3%    |
| pt_PT   | 1         | 1.15%   |
| it_IT   | 1         | 1.15%   |
| fi_FI   | 1         | 1.15%   |
| es_UY   | 1         | 1.15%   |
| es_PE   | 1         | 1.15%   |
| es_MX   | 1         | 1.15%   |
| es_HN   | 1         | 1.15%   |
| es_ES   | 1         | 1.15%   |
| es_CL   | 1         | 1.15%   |
| en_IE   | 1         | 1.15%   |
| en_AG   | 1         | 1.15%   |
| de_AT   | 1         | 1.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 51        | 60%     |
| BIOS | 34        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 71        | 81.61%  |
| Btrfs   | 8         | 9.2%    |
| Unknown | 6         | 6.9%    |
| Overlay | 2         | 2.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 73        | 84.88%  |
| GPT     | 12        | 13.95%  |
| MBR     | 1         | 1.16%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 84        | 98.82%  |
| Yes       | 1         | 1.18%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 87.06%  |
| Yes       | 11        | 12.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 20        | 23.53%  |
| MSI                 | 10        | 11.76%  |
| Lenovo              | 8         | 9.41%   |
| Hewlett-Packard     | 8         | 9.41%   |
| Dell                | 7         | 8.24%   |
| Apple               | 5         | 5.88%   |
| Gigabyte Technology | 4         | 4.71%   |
| Acer                | 4         | 4.71%   |
| ASRock              | 3         | 3.53%   |
| Sony                | 2         | 2.35%   |
| Pegatron            | 2         | 2.35%   |
| ZOTAC               | 1         | 1.18%   |
| Wortmann AG         | 1         | 1.18%   |
| Toshiba             | 1         | 1.18%   |
| PCWare              | 1         | 1.18%   |
| Panasonic           | 1         | 1.18%   |
| Microsoft           | 1         | 1.18%   |
| Medion              | 1         | 1.18%   |
| HUAWEI              | 1         | 1.18%   |
| Fujitsu             | 1         | 1.18%   |
| Foxconn             | 1         | 1.18%   |
| Exo                 | 1         | 1.18%   |
| Unknown             | 1         | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 3         | 3.53%   |
| ASUS ROG Zephyrus M16 GU603HE_GU603HE  | 2         | 2.35%   |
| ASUS PRIME Z370-A                      | 2         | 2.35%   |
| ZOTAC ZBOX-CI527/CI547                 | 1         | 1.18%   |
| Wortmann AG TERRA_PC                   | 1         | 1.18%   |
| Toshiba Satellite T135D                | 1         | 1.18%   |
| Sony VPCEE4J1E                         | 1         | 1.18%   |
| Sony SVF15318SNB                       | 1         | 1.18%   |
| Pegatron p7-1030                       | 1         | 1.18%   |
| Pegatron AY691AA-ABA p6367c            | 1         | 1.18%   |
| PCWare IPMH81G1                        | 1         | 1.18%   |
| Panasonic CF-J10YYBHR                  | 1         | 1.18%   |
| MSI Traveller 1591                     | 1         | 1.18%   |
| MSI MS-7C37                            | 1         | 1.18%   |
| MSI MS-7B89                            | 1         | 1.18%   |
| MSI MS-7A37                            | 1         | 1.18%   |
| MSI MS-7788                            | 1         | 1.18%   |
| MSI GS66 Stealth 10SE                  | 1         | 1.18%   |
| MSI GP72 7RDX                          | 1         | 1.18%   |
| MSI GE66 Raider 11UG                   | 1         | 1.18%   |
| MSI C Series                           | 1         | 1.18%   |
| MSI 700-216                            | 1         | 1.18%   |
| Microsoft Surface Pro 3                | 1         | 1.18%   |
| Medion H61H2-LM3                       | 1         | 1.18%   |
| Lenovo Yoga 730-15IKB 81CU             | 1         | 1.18%   |
| Lenovo XiaoXin Air 12 80UN             | 1         | 1.18%   |
| Lenovo ThinkPad X240 20AMS72901        | 1         | 1.18%   |
| Lenovo ThinkPad X230 2325AT6           | 1         | 1.18%   |
| Lenovo ThinkCentre M72z 3548B2S        | 1         | 1.18%   |
| Lenovo Legion Y7000P 81LD              | 1         | 1.18%   |
| Lenovo G550 2958                       | 1         | 1.18%   |
| Lenovo G50-45 80E3                     | 1         | 1.18%   |
| HUAWEI BOHK-WAX9X                      | 1         | 1.18%   |
| HP ProLiant DL380p Gen8                | 1         | 1.18%   |
| HP ProBook 6560b                       | 1         | 1.18%   |
| HP Pavilion x360 Convertible 14-cd1xxx | 1         | 1.18%   |
| HP Pavilion Laptop 14-bf0xx            | 1         | 1.18%   |
| HP Pavilion Gaming Laptop 15-cx0xxx    | 1         | 1.18%   |
| HP Pavilion Desktop PC 570-p0xx        | 1         | 1.18%   |
| HP EliteDesk 800 G3 DM 35W             | 1         | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUS PRIME            | 6         | 7.06%   |
| HP Pavilion           | 4         | 4.71%   |
| Dell OptiPlex         | 3         | 3.53%   |
| ASUS All              | 3         | 3.53%   |
| Lenovo ThinkPad       | 2         | 2.35%   |
| Dell Latitude         | 2         | 2.35%   |
| Dell Inspiron         | 2         | 2.35%   |
| ASUS VivoBook         | 2         | 2.35%   |
| ASUS ROG              | 2         | 2.35%   |
| Acer Aspire           | 2         | 2.35%   |
| ZOTAC ZBOX-CI527      | 1         | 1.18%   |
| Wortmann AG TERRA     | 1         | 1.18%   |
| Toshiba Satellite     | 1         | 1.18%   |
| Sony VPCEE4J1E        | 1         | 1.18%   |
| Sony SVF15318SNB      | 1         | 1.18%   |
| Pegatron p7-1030      | 1         | 1.18%   |
| Pegatron AY691AA-ABA  | 1         | 1.18%   |
| PCWare IPMH81G1       | 1         | 1.18%   |
| Panasonic CF-J10YYBHR | 1         | 1.18%   |
| MSI Traveller         | 1         | 1.18%   |
| MSI MS-7C37           | 1         | 1.18%   |
| MSI MS-7B89           | 1         | 1.18%   |
| MSI MS-7A37           | 1         | 1.18%   |
| MSI MS-7788           | 1         | 1.18%   |
| MSI GS66              | 1         | 1.18%   |
| MSI GP72              | 1         | 1.18%   |
| MSI GE66              | 1         | 1.18%   |
| MSI C                 | 1         | 1.18%   |
| MSI 700-216           | 1         | 1.18%   |
| Microsoft Surface     | 1         | 1.18%   |
| Medion H61H2-LM3      | 1         | 1.18%   |
| Lenovo Yoga           | 1         | 1.18%   |
| Lenovo XiaoXin        | 1         | 1.18%   |
| Lenovo ThinkCentre    | 1         | 1.18%   |
| Lenovo Legion         | 1         | 1.18%   |
| Lenovo G550           | 1         | 1.18%   |
| Lenovo G50-45         | 1         | 1.18%   |
| HUAWEI BOHK-WAX9X     | 1         | 1.18%   |
| HP ProLiant           | 1         | 1.18%   |
| HP ProBook            | 1         | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2017 | 13        | 15.29%  |
| 2011 | 10        | 11.76%  |
| 2013 | 9         | 10.59%  |
| 2012 | 9         | 10.59%  |
| 2019 | 7         | 8.24%   |
| 2018 | 6         | 7.06%   |
| 2016 | 6         | 7.06%   |
| 2014 | 6         | 7.06%   |
| 2009 | 5         | 5.88%   |
| 2021 | 4         | 4.71%   |
| 2020 | 4         | 4.71%   |
| 2008 | 3         | 3.53%   |
| 2015 | 1         | 1.18%   |
| 2010 | 1         | 1.18%   |
| 2006 | 1         | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 39        | 45.88%  |
| Desktop     | 36        | 42.35%  |
| All in one  | 4         | 4.71%   |
| Convertible | 2         | 2.35%   |
| Mini pc     | 2         | 2.35%   |
| Tablet      | 1         | 1.18%   |
| Server      | 1         | 1.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 80        | 93.02%  |
| Enabled  | 6         | 6.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 85        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 22.73%  |
| 8.01-16.0   | 20        | 22.73%  |
| 16.01-24.0  | 18        | 20.45%  |
| 3.01-4.0    | 15        | 17.05%  |
| 32.01-64.0  | 8         | 9.09%   |
| 64.01-256.0 | 3         | 3.41%   |
| 24.01-32.0  | 2         | 2.27%   |
| 1.01-2.0    | 2         | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 40        | 42.55%  |
| 2.01-3.0  | 30        | 31.91%  |
| 3.01-4.0  | 12        | 12.77%  |
| 4.01-8.0  | 9         | 9.57%   |
| 0.51-1.0  | 2         | 2.13%   |
| 8.01-16.0 | 1         | 1.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 51        | 57.95%  |
| 2      | 20        | 22.73%  |
| 3      | 11        | 12.5%   |
| 4      | 3         | 3.41%   |
| 7      | 1         | 1.14%   |
| 5      | 1         | 1.14%   |
| 0      | 1         | 1.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 61.18%  |
| Yes       | 33        | 38.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 90.59%  |
| No        | 8         | 9.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 69.41%  |
| No        | 26        | 30.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 52.87%  |
| No        | 41        | 47.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 17        | 20%     |
| Switzerland | 10        | 11.76%  |
| Germany     | 8         | 9.41%   |
| Australia   | 7         | 8.24%   |
| UK          | 6         | 7.06%   |
| India       | 3         | 3.53%   |
| Canada      | 3         | 3.53%   |
| Brazil      | 3         | 3.53%   |
| Venezuela   | 2         | 2.35%   |
| Turkey      | 2         | 2.35%   |
| Poland      | 2         | 2.35%   |
| Belgium     | 2         | 2.35%   |
| Argentina   | 2         | 2.35%   |
| Uruguay     | 1         | 1.18%   |
| UAE         | 1         | 1.18%   |
| Spain       | 1         | 1.18%   |
| Portugal    | 1         | 1.18%   |
| Peru        | 1         | 1.18%   |
| Norway      | 1         | 1.18%   |
| Mexico      | 1         | 1.18%   |
| Jordan      | 1         | 1.18%   |
| Japan       | 1         | 1.18%   |
| Italy       | 1         | 1.18%   |
| Ireland     | 1         | 1.18%   |
| Honduras    | 1         | 1.18%   |
| Guam        | 1         | 1.18%   |
| Greece      | 1         | 1.18%   |
| Finland     | 1         | 1.18%   |
| Chile       | 1         | 1.18%   |
| Bulgaria    | 1         | 1.18%   |
| Belize      | 1         | 1.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Oberwil-Lieli  | 8         | 8.79%   |
| Melbourne      | 3         | 3.3%    |
| Winterthur     | 2         | 2.2%    |
| Richmond       | 2         | 2.2%    |
| Istanbul       | 2         | 2.2%    |
| Escondido      | 2         | 2.2%    |
| Zurich         | 1         | 1.1%    |
| Ypsilanti      | 1         | 1.1%    |
| Yigo Village   | 1         | 1.1%    |
| Wrexham        | 1         | 1.1%    |
| Varna          | 1         | 1.1%    |
| Tegucigalpa    | 1         | 1.1%    |
| Surat          | 1         | 1.1%    |
| Stuttgart      | 1         | 1.1%    |
| Stavanger      | 1         | 1.1%    |
| Sligo          | 1         | 1.1%    |
| Seattle        | 1         | 1.1%    |
| Schleusingen   | 1         | 1.1%    |
| Sao Jose       | 1         | 1.1%    |
| Santiago       | 1         | 1.1%    |
| Sankt Augustin | 1         | 1.1%    |
| Saitama        | 1         | 1.1%    |
| Recklinghausen | 1         | 1.1%    |
| Portland       | 1         | 1.1%    |
| Plymouth       | 1         | 1.1%    |
| Phoenix        | 1         | 1.1%    |
| Oudenaarde     | 1         | 1.1%    |
| New York       | 1         | 1.1%    |
| Naples         | 1         | 1.1%    |
| Montevideo     | 1         | 1.1%    |
| Moncton        | 1         | 1.1%    |
| Mieres         | 1         | 1.1%    |
| Maracay        | 1         | 1.1%    |
| Macaé         | 1         | 1.1%    |
| Los Angeles    | 1         | 1.1%    |
| Lineville      | 1         | 1.1%    |
| Lima           | 1         | 1.1%    |
| Leicester      | 1         | 1.1%    |
| Lafayette      | 1         | 1.1%    |
| La Barca       | 1         | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 20        | 31     | 15.63%  |
| Seagate                   | 18        | 25     | 14.06%  |
| Samsung Electronics       | 16        | 21     | 12.5%   |
| Unknown                   | 8         | 8      | 6.25%   |
| Toshiba                   | 8         | 11     | 6.25%   |
| SanDisk                   | 8         | 10     | 6.25%   |
| Intel                     | 8         | 9      | 6.25%   |
| Hitachi                   | 8         | 9      | 6.25%   |
| Kingston                  | 6         | 14     | 4.69%   |
| HGST                      | 4         | 4      | 3.13%   |
| SK hynix                  | 3         | 4      | 2.34%   |
| Phison                    | 3         | 3      | 2.34%   |
| A-DATA Technology         | 3         | 3      | 2.34%   |
| Realtek Semiconductor     | 2         | 2      | 1.56%   |
| PNY                       | 2         | 2      | 1.56%   |
| OCZ                       | 2         | 2      | 1.56%   |
| Crucial                   | 2         | 5      | 1.56%   |
| Verbatim                  | 1         | 1      | 0.78%   |
| Micron/Crucial Technology | 1         | 1      | 0.78%   |
| LITEONIT                  | 1         | 1      | 0.78%   |
| LITEON                    | 1         | 1      | 0.78%   |
| IBM                       | 1         | 1      | 0.78%   |
| China                     | 1         | 1      | 0.78%   |
| Apple                     | 1         | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 64GB         | 3         | 2.17%   |
| Unknown MMC Card  32GB             | 2         | 1.45%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 1.45%   |
| Seagate ST4000LM016-1N2170 4TB     | 2         | 1.45%   |
| Seagate ST31000528AS 1TB           | 2         | 1.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 1.45%   |
| Samsung HD103SJ 1TB                | 2         | 1.45%   |
| Realtek NVMe SSD Drive 512GB       | 2         | 1.45%   |
| Phison NVMe SSD Drive 1TB          | 2         | 1.45%   |
| Kingston SA400S37480G 480GB SSD    | 2         | 1.45%   |
| Intel NVMe SSD Drive 512GB         | 2         | 1.45%   |
| Hitachi HDS721010CLA332 1TB        | 2         | 1.45%   |
| HGST HTS721010A9E630 1TB           | 2         | 1.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 0.72%   |
| WDC WDS500G1R0B-68A4Z0 500GB SSD   | 1         | 0.72%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.72%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 1         | 0.72%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 1         | 0.72%   |
| WDC WD80EFBX-68AZZN0 8TB           | 1         | 0.72%   |
| WDC WD6400AAKS-00A7B2 640GB        | 1         | 0.72%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 0.72%   |
| WDC WD5000BPKT-60PK4T0 500GB       | 1         | 0.72%   |
| WDC WD5000AAVS-00G9B1 500GB        | 1         | 0.72%   |
| WDC WD5000AAKS-65A7B2 500GB        | 1         | 0.72%   |
| WDC WD5000AAKS-00A7B2 500GB        | 1         | 0.72%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1         | 0.72%   |
| WDC WD30EZRX-00D8PB0 3TB           | 1         | 0.72%   |
| WDC WD2500BPVT-00JJ5T0 250GB       | 1         | 0.72%   |
| WDC WD2500AAKX-75U6AA0 250GB       | 1         | 0.72%   |
| WDC WD1600AAJS-00L7A0 160GB        | 1         | 0.72%   |
| WDC WD10PURX-78E5EY0 1TB           | 1         | 0.72%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 0.72%   |
| WDC WD10EZEX-60WN4A0 1TB           | 1         | 0.72%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1         | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1         | 0.72%   |
| WDC WD10EZEX-00WN4A0 1TB           | 1         | 0.72%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1         | 0.72%   |
| WDC WD10EURX-83UY4Y0 1TB           | 1         | 0.72%   |
| Verbatim Vi550 S3 SSD 512GB        | 1         | 0.72%   |
| Unknown SB128  128GB               | 1         | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 24     | 32.14%  |
| WDC                 | 17        | 26     | 30.36%  |
| Hitachi             | 8         | 9      | 14.29%  |
| Toshiba             | 4         | 6      | 7.14%   |
| HGST                | 4         | 4      | 7.14%   |
| Unknown             | 3         | 2      | 5.36%   |
| Samsung Electronics | 2         | 3      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 10     | 16.67%  |
| SanDisk             | 6         | 7      | 12.5%   |
| Kingston            | 6         | 14     | 12.5%   |
| Intel               | 5         | 5      | 10.42%  |
| WDC                 | 4         | 4      | 8.33%   |
| Toshiba             | 3         | 4      | 6.25%   |
| A-DATA Technology   | 3         | 3      | 6.25%   |
| SK hynix            | 2         | 3      | 4.17%   |
| PNY                 | 2         | 2      | 4.17%   |
| OCZ                 | 2         | 2      | 4.17%   |
| Crucial             | 2         | 5      | 4.17%   |
| Verbatim            | 1         | 1      | 2.08%   |
| LITEONIT            | 1         | 1      | 2.08%   |
| LITEON              | 1         | 1      | 2.08%   |
| China               | 1         | 1      | 2.08%   |
| Apple               | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 47        | 74     | 40.87%  |
| SSD     | 42        | 64     | 36.52%  |
| NVMe    | 19        | 24     | 16.52%  |
| MMC     | 5         | 6      | 4.35%   |
| Unknown | 2         | 2      | 1.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 72        | 133    | 69.23%  |
| NVMe | 19        | 24     | 18.27%  |
| SAS  | 8         | 7      | 7.69%   |
| MMC  | 5         | 6      | 4.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 55        | 82     | 59.78%  |
| 0.51-1.0   | 26        | 40     | 28.26%  |
| 1.01-2.0   | 5         | 6      | 5.43%   |
| 3.01-4.0   | 3         | 7      | 3.26%   |
| 2.01-3.0   | 2         | 2      | 2.17%   |
| 4.01-10.0  | 1         | 1      | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 26.09%  |
| 251-500        | 22        | 23.91%  |
| 1001-2000      | 16        | 17.39%  |
| 501-1000       | 13        | 14.13%  |
| More than 3000 | 4         | 4.35%   |
| 2001-3000      | 4         | 4.35%   |
| 51-100         | 4         | 4.35%   |
| 21-50          | 3         | 3.26%   |
| 1-20           | 1         | 1.09%   |
| Unknown        | 1         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 29        | 31.52%  |
| 1-20      | 16        | 17.39%  |
| 251-500   | 14        | 15.22%  |
| 101-250   | 12        | 13.04%  |
| 51-100    | 12        | 13.04%  |
| 501-1000  | 7         | 7.61%   |
| 1001-2000 | 1         | 1.09%   |
| Unknown   | 1         | 1.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD5000AAVS-00G9B1 500GB              | 1         | 1      | 14.29%  |
| Toshiba MK1234GSX 120GB                  | 1         | 1      | 14.29%  |
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 14.29%  |
| Seagate ST3500418AS 500GB                | 1         | 1      | 14.29%  |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 840 Series 120GB | 1         | 1      | 14.29%  |
| Intel SSDSC2BW240A4 240GB                | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 42.86%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Intel               | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 60%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 5      | 66.67%  |
| SSD  | 2         | 2      | 33.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate ST31000528AS 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 73        | 139    | 80.22%  |
| Works    | 11        | 23     | 12.09%  |
| Malfunc  | 6         | 7      | 6.59%   |
| Failed   | 1         | 1      | 1.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 62        | 59.05%  |
| AMD                          | 14        | 13.33%  |
| Samsung Electronics          | 11        | 10.48%  |
| SanDisk                      | 3         | 2.86%   |
| Phison Electronics           | 3         | 2.86%   |
| Nvidia                       | 3         | 2.86%   |
| Realtek Semiconductor        | 2         | 1.9%    |
| ASMedia Technology           | 2         | 1.9%    |
| Toshiba America Info Systems | 1         | 0.95%   |
| SK hynix                     | 1         | 0.95%   |
| Micron/Crucial Technology    | 1         | 0.95%   |
| JMicron Technology           | 1         | 0.95%   |
| Hewlett-Packard              | 1         | 0.95%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 7.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 4.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 4%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 4%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 4%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 3.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 3.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 3.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 3.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 2.4%    |
| Phison E12 NVMe Controller                                                              | 3         | 2.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 2.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 2.4%    |
| AMD 300 Series Chipset SATA Controller                                                  | 3         | 2.4%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.6%    |
| Intel Non-Volatile memory controller                                                    | 2         | 1.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.6%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.6%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 1.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.6%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.6%    |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.6%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1         | 0.8%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1         | 0.8%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1         | 0.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.8%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.8%    |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.8%    |
| Samsung Electronics SATA controller                                                     | 1         | 0.8%    |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1         | 0.8%    |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 0.8%    |
| Nvidia nForce SATA Controller                                                           | 1         | 0.8%    |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.8%    |
| Nvidia MCP55 SATA Controller                                                            | 1         | 0.8%    |
| Nvidia MCP55 IDE                                                                        | 1         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 65        | 60.75%  |
| NVMe | 22        | 20.56%  |
| IDE  | 13        | 12.15%  |
| RAID | 7         | 6.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 69        | 81.18%  |
| AMD    | 16        | 18.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 3.53%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 2         | 2.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 2.35%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 2         | 2.35%   |
| Intel Core i5-4260U CPU @ 1.40GHz       | 2         | 2.35%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 2.35%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 2         | 2.35%   |
| Intel Celeron CPU 1007U @ 1.50GHz       | 2         | 2.35%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 2         | 2.35%   |
| Intel Xeon CPU E5-2667 0 @ 2.90GHz      | 1         | 1.18%   |
| Intel Pentium D CPU 3.00GHz             | 1         | 1.18%   |
| Intel Pentium CPU P6200 @ 2.13GHz       | 1         | 1.18%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 1.18%   |
| Intel Pentium CPU G630 @ 2.70GHz        | 1         | 1.18%   |
| Intel Pentium CPU G3250 @ 3.20GHz       | 1         | 1.18%   |
| Intel Pentium CPU 4415U @ 2.30GHz       | 1         | 1.18%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 1.18%   |
| Intel Core i7-7700T CPU @ 2.90GHz       | 1         | 1.18%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 1.18%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.18%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1         | 1.18%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.18%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1         | 1.18%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz      | 1         | 1.18%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.18%   |
| Intel Core i7-3770S CPU @ 3.10GHz       | 1         | 1.18%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1         | 1.18%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1         | 1.18%   |
| Intel Core i7-10875H CPU @ 2.30GHz      | 1         | 1.18%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 1         | 1.18%   |
| Intel Core i7 CPU 920 @ 2.67GHz         | 1         | 1.18%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 1         | 1.18%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 1.18%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 1.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.18%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.18%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.18%   |
| Intel Core i5-4690K CPU @ 3.50GHz       | 1         | 1.18%   |
| Intel Core i5-4210M CPU @ 2.60GHz       | 1         | 1.18%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 24.71%  |
| Intel Core i7           | 18        | 21.18%  |
| Intel Core i3           | 7         | 8.24%   |
| Intel Pentium           | 5         | 5.88%   |
| Intel Celeron           | 5         | 5.88%   |
| AMD Ryzen 5             | 4         | 4.71%   |
| Other                   | 3         | 3.53%   |
| Intel Core 2 Quad       | 3         | 3.53%   |
| Intel Core 2 Duo        | 2         | 2.35%   |
| AMD Ryzen 9             | 2         | 2.35%   |
| AMD Ryzen 7             | 2         | 2.35%   |
| AMD A8                  | 2         | 2.35%   |
| Intel Xeon              | 1         | 1.18%   |
| Intel Pentium D         | 1         | 1.18%   |
| Intel Core m3           | 1         | 1.18%   |
| Intel Celeron Dual-Core | 1         | 1.18%   |
| Intel Atom              | 1         | 1.18%   |
| AMD Turion Neo X2       | 1         | 1.18%   |
| AMD FX                  | 1         | 1.18%   |
| AMD Athlon X2           | 1         | 1.18%   |
| AMD Athlon II           | 1         | 1.18%   |
| AMD A6                  | 1         | 1.18%   |
| AMD A10                 | 1         | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 49.41%  |
| 4      | 28        | 32.94%  |
| 8      | 8         | 9.41%   |
| 6      | 5         | 5.88%   |
| 12     | 2         | 2.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 84        | 98.82%  |
| 2      | 1         | 1.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 58        | 68.24%  |
| 1      | 27        | 31.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 79        | 92.94%  |
| Unknown        | 6         | 7.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 8         | 9.41%   |
| 0x206a7    | 8         | 9.41%   |
| 0x306c3    | 7         | 8.24%   |
| 0x40651    | 6         | 7.06%   |
| 0x1067a    | 5         | 5.88%   |
| 0x906ea    | 4         | 4.71%   |
| 0x906e9    | 4         | 4.71%   |
| 0x806d1    | 3         | 3.53%   |
| 0x406e3    | 3         | 3.53%   |
| Unknown    | 3         | 3.53%   |
| 0x806ea    | 2         | 2.35%   |
| 0x806e9    | 2         | 2.35%   |
| 0x706a8    | 2         | 2.35%   |
| 0x0800820d | 2         | 2.35%   |
| 0x08001138 | 2         | 2.35%   |
| 0xf62      | 1         | 1.18%   |
| 0xa0655    | 1         | 1.18%   |
| 0xa0652    | 1         | 1.18%   |
| 0x806eb    | 1         | 1.18%   |
| 0x6fb      | 1         | 1.18%   |
| 0x506e3    | 1         | 1.18%   |
| 0x506c9    | 1         | 1.18%   |
| 0x406c4    | 1         | 1.18%   |
| 0x306d4    | 1         | 1.18%   |
| 0x206d7    | 1         | 1.18%   |
| 0x20655    | 1         | 1.18%   |
| 0x106e5    | 1         | 1.18%   |
| 0x106a5    | 1         | 1.18%   |
| 0x0a50000c | 1         | 1.18%   |
| 0x08701021 | 1         | 1.18%   |
| 0x08108109 | 1         | 1.18%   |
| 0x0810100b | 1         | 1.18%   |
| 0x07030105 | 1         | 1.18%   |
| 0x0600611a | 1         | 1.18%   |
| 0x06003104 | 1         | 1.18%   |
| 0x06001119 | 1         | 1.18%   |
| 0x06000852 | 1         | 1.18%   |
| 0x02000032 | 1         | 1.18%   |
| 0x010000c8 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 13        | 15.29%  |
| Haswell         | 13        | 15.29%  |
| SandyBridge     | 10        | 11.76%  |
| IvyBridge       | 9         | 10.59%  |
| Penryn          | 5         | 5.88%   |
| Skylake         | 4         | 4.71%   |
| Zen+            | 3         | 3.53%   |
| Zen             | 3         | 3.53%   |
| Icelake         | 3         | 3.53%   |
| Piledriver      | 2         | 2.35%   |
| Nehalem         | 2         | 2.35%   |
| Goldmont plus   | 2         | 2.35%   |
| CometLake       | 2         | 2.35%   |
| Zen 3           | 1         | 1.18%   |
| Zen 2           | 1         | 1.18%   |
| Westmere        | 1         | 1.18%   |
| Steamroller     | 1         | 1.18%   |
| Silvermont      | 1         | 1.18%   |
| Puma            | 1         | 1.18%   |
| NetBurst        | 1         | 1.18%   |
| K8 Hammer       | 1         | 1.18%   |
| K8 & K10 hybrid | 1         | 1.18%   |
| K10             | 1         | 1.18%   |
| Goldmont        | 1         | 1.18%   |
| Excavator       | 1         | 1.18%   |
| Core            | 1         | 1.18%   |
| Broadwell       | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 53        | 53%     |
| Nvidia                     | 30        | 30%     |
| AMD                        | 16        | 16%     |
| Matrox Electronics Systems | 1         | 1%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                            | 6         | 6%      |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 5%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 4         | 4%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 3         | 3%      |
| Intel HD Graphics 630                                                       | 3         | 3%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2         | 2%      |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 2%      |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 2         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 2%      |
| Intel UHD Graphics 620                                                      | 2         | 2%      |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 2%      |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 2%      |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 2%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 2%      |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2         | 2%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 2%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 1%      |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 1%      |
| Nvidia MCP7A [GeForce 9400]                                                 | 1         | 1%      |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 1%      |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1         | 1%      |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 1%      |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 1%      |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 1%      |
| Nvidia GK208BM [GeForce 920M]                                               | 1         | 1%      |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 1%      |
| Nvidia GK107M [GeForce GT 750M]                                             | 1         | 1%      |
| Nvidia GK107 [NVS 510]                                                      | 1         | 1%      |
| Nvidia GF108 [GeForce GT 730]                                               | 1         | 1%      |
| Nvidia GF108 [GeForce GT 630]                                               | 1         | 1%      |
| Nvidia GF108 [GeForce GT 430]                                               | 1         | 1%      |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 1         | 1%      |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 1         | 1%      |
| Nvidia G92 [GeForce 8800 GT]                                                | 1         | 1%      |
| Nvidia C77 [GeForce 9100M G]                                                | 1         | 1%      |
| Matrox Electronics Systems MGA G200EH                                       | 1         | 1%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 45.88%  |
| 1 x Nvidia     | 17        | 20%     |
| 1 x AMD        | 14        | 16.47%  |
| Intel + Nvidia | 12        | 14.12%  |
| 1 x Matrox     | 1         | 1.18%   |
| Intel + AMD    | 1         | 1.18%   |
| AMD + Nvidia   | 1         | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 66        | 75.86%  |
| Proprietary | 19        | 21.84%  |
| Unknown     | 2         | 2.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 50.57%  |
| 1.01-2.0   | 12        | 13.79%  |
| 0.51-1.0   | 9         | 10.34%  |
| 3.01-4.0   | 7         | 8.05%   |
| 0.01-0.5   | 7         | 8.05%   |
| 7.01-8.0   | 6         | 6.9%    |
| 5.01-6.0   | 2         | 2.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 10        | 11.63%  |
| Samsung Electronics     | 9         | 10.47%  |
| AU Optronics            | 9         | 10.47%  |
| BOE                     | 8         | 9.3%    |
| Acer                    | 7         | 8.14%   |
| Dell                    | 5         | 5.81%   |
| Apple                   | 5         | 5.81%   |
| Chimei Innolux          | 4         | 4.65%   |
| Lenovo                  | 3         | 3.49%   |
| Hewlett-Packard         | 3         | 3.49%   |
| Sharp                   | 2         | 2.33%   |
| Philips                 | 2         | 2.33%   |
| Chi Mei Optoelectronics | 2         | 2.33%   |
| AOC                     | 2         | 2.33%   |
| Vestel                  | 1         | 1.16%   |
| Unknown                 | 1         | 1.16%   |
| Toshiba                 | 1         | 1.16%   |
| Sony                    | 1         | 1.16%   |
| Sceptre Tech            | 1         | 1.16%   |
| Ruijiang                | 1         | 1.16%   |
| Panasonic               | 1         | 1.16%   |
| Onkyo                   | 1         | 1.16%   |
| Medion                  | 1         | 1.16%   |
| LG Electronics          | 1         | 1.16%   |
| Lenovo Group Limited    | 1         | 1.16%   |
| Insignia                | 1         | 1.16%   |
| Goldstar                | 1         | 1.16%   |
| BenQ                    | 1         | 1.16%   |
| Ancor Communications    | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch        | 2         | 2.2%    |
| Vestel LCD Monitor 32W_LCD_TV 1920x1080                               | 1         | 1.1%    |
| Unknown LCD Monitor SAMSUNG                                           | 1         | 1.1%    |
| Toshiba LCD Monitor LCD0905 1366x768 295x166mm 13.3-inch              | 1         | 1.1%    |
| Sony AVAMP SNYF400 1920x1080 700x390mm 31.5-inch                      | 1         | 1.1%    |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch               | 1         | 1.1%    |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 1         | 1.1%    |
| Sceptre Tech E27 SPT0ABF 1920x1080 521x293mm 23.5-inch                | 1         | 1.1%    |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 598x336mm 27.0-inch     | 1         | 1.1%    |
| Samsung Electronics LCD Monitor U28E590 7680x2160                     | 1         | 1.1%    |
| Samsung Electronics LCD Monitor U28E590                               | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch  | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 890x500mm 40.2-inch | 1         | 1.1%    |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 1         | 1.1%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 1.1%    |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch     | 1         | 1.1%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 1.1%    |
| Ruijiang RJT HDMI RJT1200 1920x1200 320x180mm 14.5-inch               | 1         | 1.1%    |
| Philips PHL 328E9Q PHLC180 1920x1080 698x393mm 31.5-inch              | 1         | 1.1%    |
| Philips 220EW PHL0861 1680x1050 434x270mm 20.1-inch                   | 1         | 1.1%    |
| Panasonic TV MEIC301 1920x1080 698x392mm 31.5-inch                    | 1         | 1.1%    |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                  | 1         | 1.1%    |
| Medion MD 20094 MED3610 1920x1200 550x344mm 25.5-inch                 | 1         | 1.1%    |
| LG Electronics LCD Monitor MP59HT 1920x1080                           | 1         | 1.1%    |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch          | 1         | 1.1%    |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch          | 1         | 1.1%    |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 1         | 1.1%    |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch           | 1         | 1.1%    |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                 | 1         | 1.1%    |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                  | 1         | 1.1%    |
| Lenovo H61 LEN520B 1600x900 410x230mm 18.5-inch                       | 1         | 1.1%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 35        | 41.18%  |
| 1366x768 (WXGA)    | 21        | 24.71%  |
| 2560x1440 (QHD)    | 6         | 7.06%   |
| 3840x2160 (4K)     | 3         | 3.53%   |
| 2560x1600          | 3         | 3.53%   |
| 1280x1024 (SXGA)   | 3         | 3.53%   |
| 1680x1050 (WSXGA+) | 2         | 2.35%   |
| 1600x900 (HD+)     | 2         | 2.35%   |
| 1440x900 (WXGA+)   | 2         | 2.35%   |
| Unknown            | 2         | 2.35%   |
| 7680x2160          | 1         | 1.18%   |
| 3840x1080          | 1         | 1.18%   |
| 2160x1440          | 1         | 1.18%   |
| 1920x1200 (WUXGA)  | 1         | 1.18%   |
| 1280x800 (WXGA)    | 1         | 1.18%   |
| 1024x768 (XGA)     | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 28.24%  |
| Unknown | 8         | 9.41%   |
| 27      | 7         | 8.24%   |
| 21      | 5         | 5.88%   |
| 17      | 5         | 5.88%   |
| 13      | 5         | 5.88%   |
| 24      | 4         | 4.71%   |
| 14      | 4         | 4.71%   |
| 31      | 3         | 3.53%   |
| 23      | 3         | 3.53%   |
| 32      | 2         | 2.35%   |
| 25      | 2         | 2.35%   |
| 22      | 2         | 2.35%   |
| 16      | 2         | 2.35%   |
| 12      | 2         | 2.35%   |
| 86      | 1         | 1.18%   |
| 54      | 1         | 1.18%   |
| 49      | 1         | 1.18%   |
| 29      | 1         | 1.18%   |
| 19      | 1         | 1.18%   |
| 18      | 1         | 1.18%   |
| 11      | 1         | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 38.82%  |
| 501-600     | 16        | 18.82%  |
| 401-500     | 8         | 9.41%   |
| Unknown     | 8         | 9.41%   |
| 201-300     | 6         | 7.06%   |
| 351-400     | 5         | 5.88%   |
| 601-700     | 4         | 4.71%   |
| 701-800     | 2         | 2.35%   |
| 1001-1500   | 2         | 2.35%   |
| 1501-2000   | 1         | 1.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 62        | 74.7%   |
| 16/10   | 9         | 10.84%  |
| Unknown | 8         | 9.64%   |
| 5/4     | 3         | 3.61%   |
| 4/3     | 1         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 28.24%  |
| 201-250        | 12        | 14.12%  |
| 81-90          | 8         | 9.41%   |
| Unknown        | 8         | 9.41%   |
| 301-350        | 7         | 8.24%   |
| 351-500        | 6         | 7.06%   |
| More than 1000 | 3         | 3.53%   |
| 251-300        | 3         | 3.53%   |
| 141-150        | 3         | 3.53%   |
| 121-130        | 3         | 3.53%   |
| 61-70          | 2         | 2.35%   |
| 151-200        | 2         | 2.35%   |
| 111-120        | 2         | 2.35%   |
| 71-80          | 1         | 1.18%   |
| 51-60          | 1         | 1.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 25        | 30.12%  |
| 101-120       | 24        | 28.92%  |
| 121-160       | 19        | 22.89%  |
| Unknown       | 8         | 9.64%   |
| 1-50          | 3         | 3.61%   |
| 161-240       | 3         | 3.61%   |
| More than 240 | 1         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 76        | 86.36%  |
| 2     | 9         | 10.23%  |
| 0     | 2         | 2.27%   |
| 3     | 1         | 1.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 50        | 39.68%  |
| Intel                           | 28        | 22.22%  |
| Qualcomm Atheros                | 11        | 8.73%   |
| Broadcom                        | 10        | 7.94%   |
| TP-Link                         | 3         | 2.38%   |
| Ralink Technology               | 3         | 2.38%   |
| Ralink                          | 3         | 2.38%   |
| MediaTek                        | 3         | 2.38%   |
| Sierra Wireless                 | 2         | 1.59%   |
| Nvidia                          | 2         | 1.59%   |
| Linksys                         | 2         | 1.59%   |
| Qualcomm Atheros Communications | 1         | 0.79%   |
| Qualcomm                        | 1         | 0.79%   |
| NetGear                         | 1         | 0.79%   |
| Motorola PCS                    | 1         | 0.79%   |
| Microsoft                       | 1         | 0.79%   |
| Marvell Technology Group        | 1         | 0.79%   |
| Edimax Technology               | 1         | 0.79%   |
| D-Link                          | 1         | 0.79%   |
| Broadcom Limited                | 1         | 0.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 38        | 25.33%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5         | 3.33%   |
| Intel Ethernet Connection (2) I219-V                                                          | 4         | 2.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3         | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 3         | 2%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 2%      |
| Intel Wireless 7260                                                                           | 3         | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 2%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.33%   |
| Realtek Realtek Ethernet controller                                                           | 2         | 1.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 2         | 1.33%   |
| Intel Ethernet Connection I219-LM                                                             | 2         | 1.33%   |
| Intel Ethernet Connection I218-LM                                                             | 2         | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 1.33%   |
| Intel 82579V Gigabit Network Connection                                                       | 2         | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2         | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 1.33%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 0.67%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 0.67%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 0.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1         | 0.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 0.67%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1         | 0.67%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.67%   |
| Realtek Killer E3000 2.5GbE Controller                                                        | 1         | 0.67%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 0.67%   |
| Ralink RT5572 Wireless Adapter                                                                | 1         | 0.67%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1         | 0.67%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.67%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1         | 0.67%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 0.67%   |
| Qualcomm MegaFon M150-4                                                                       | 1         | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 0.67%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 28.99%  |
| Realtek Semiconductor           | 14        | 20.29%  |
| Qualcomm Atheros                | 9         | 13.04%  |
| Broadcom                        | 4         | 5.8%    |
| TP-Link                         | 3         | 4.35%   |
| Ralink Technology               | 3         | 4.35%   |
| Ralink                          | 3         | 4.35%   |
| MediaTek                        | 3         | 4.35%   |
| Sierra Wireless                 | 2         | 2.9%    |
| Linksys                         | 2         | 2.9%    |
| Qualcomm Atheros Communications | 1         | 1.45%   |
| NetGear                         | 1         | 1.45%   |
| Marvell Technology Group        | 1         | 1.45%   |
| Edimax Technology               | 1         | 1.45%   |
| D-Link                          | 1         | 1.45%   |
| Broadcom Limited                | 1         | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5         | 7.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3         | 4.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 4.35%   |
| Intel Wireless 7260                                                                           | 3         | 4.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 4.35%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2         | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 2.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 2.9%    |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 2.9%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 1.45%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 1.45%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 1.45%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1         | 1.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 1.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 1.45%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1         | 1.45%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.45%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 1.45%   |
| Ralink RT5572 Wireless Adapter                                                                | 1         | 1.45%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1         | 1.45%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.45%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1         | 1.45%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.45%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 1.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.45%   |
| NetGear A6210                                                                                 | 1         | 1.45%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                             | 1         | 1.45%   |
| Linksys WUSB6300 V2                                                                           | 1         | 1.45%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                        | 1         | 1.45%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.45%   |
| Intel Wireless 8260                                                                           | 1         | 1.45%   |
| Intel Wireless 3165                                                                           | 1         | 1.45%   |
| Intel Wireless 3160                                                                           | 1         | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 44        | 55%     |
| Intel                 | 19        | 23.75%  |
| Broadcom              | 8         | 10%     |
| Qualcomm Atheros      | 4         | 5%      |
| Nvidia                | 2         | 2.5%    |
| Qualcomm              | 1         | 1.25%   |
| Motorola PCS          | 1         | 1.25%   |
| Microsoft             | 1         | 1.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 46.91%  |
| Intel Ethernet Connection (2) I219-V                              | 4         | 4.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.7%    |
| Realtek Realtek Ethernet controller                               | 2         | 2.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.47%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.47%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.47%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.47%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.23%   |
| Qualcomm MegaFon M150-4                                           | 1         | 1.23%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.23%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.23%   |
| Nvidia MCP55 Ethernet                                             | 1         | 1.23%   |
| Motorola PCS moto g(9) play                                       | 1         | 1.23%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 1         | 1.23%   |
| Intel WiMAX Connection 2400m                                      | 1         | 1.23%   |
| Intel Ethernet controller                                         | 1         | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.23%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.23%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.23%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.23%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 1.23%   |
| Broadcom NetXtreme II BCM57711 10-Gigabit PCIe                    | 1         | 1.23%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.23%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 1.23%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.23%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.23%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 77        | 56.62%  |
| WiFi     | 59        | 43.38%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 52.87%  |
| Ethernet | 41        | 47.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 42        | 49.41%  |
| 1     | 40        | 47.06%  |
| 4     | 1         | 1.18%   |
| 3     | 1         | 1.18%   |
| 0     | 1         | 1.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 74        | 85.06%  |
| Yes  | 13        | 14.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 31.91%  |
| Realtek Semiconductor           | 6         | 12.77%  |
| Cambridge Silicon Radio         | 6         | 12.77%  |
| Apple                           | 5         | 10.64%  |
| IMC Networks                    | 4         | 8.51%   |
| Broadcom                        | 3         | 6.38%   |
| Realtek                         | 2         | 4.26%   |
| Ralink                          | 1         | 2.13%   |
| Qualcomm Atheros Communications | 1         | 2.13%   |
| Marvell Semiconductor           | 1         | 2.13%   |
| Lite-On Technology              | 1         | 2.13%   |
| Hewlett-Packard                 | 1         | 2.13%   |
| Foxconn / Hon Hai               | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 17.02%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 12.77%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.38%   |
| Realtek Bluetooth Radio                             | 3         | 6.38%   |
| IMC Networks Wireless_Device                        | 3         | 6.38%   |
| Realtek Bluetooth Radio                             | 2         | 4.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.26%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 4.26%   |
| Apple Bluetooth USB Host Controller                 | 2         | 4.26%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.13%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.13%   |
| Lite-On Bluetooth Device                            | 1         | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.13%   |
| Intel AX210 Bluetooth                               | 1         | 2.13%   |
| Intel AX201 Bluetooth                               | 1         | 2.13%   |
| Intel AX200 Bluetooth                               | 1         | 2.13%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 2.13%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.13%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 2.13%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 2.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.13%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.13%   |
| Apple Bluetooth Host Controller                     | 1         | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 65        | 55.08%  |
| Nvidia              | 24        | 20.34%  |
| AMD                 | 18        | 15.25%  |
| Texas Instruments   | 2         | 1.69%   |
| Microsoft           | 2         | 1.69%   |
| Logitech            | 2         | 1.69%   |
| C-Media Electronics | 2         | 1.69%   |
| Razer USA           | 1         | 0.85%   |
| Hewlett-Packard     | 1         | 0.85%   |
| Creative Labs       | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 7.8%    |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 4.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 4.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 4.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.26%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 4.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 2.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.84%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 2.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 2.84%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 2.13%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 2.13%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 2.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.13%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 2.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.42%   |
| Nvidia Audio device                                                        | 2         | 1.42%   |
| Logitech Headset H390                                                      | 2         | 1.42%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.42%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.42%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 1.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.42%   |
| Texas Instruments PCM2902C Audio CODEC                                     | 1         | 0.71%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.71%   |
| Razer USA Nommo Chroma                                                     | 1         | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.71%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1         | 0.71%   |
| Nvidia MCP55 High Definition Audio                                         | 1         | 0.71%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.71%   |
| Microsoft Surface Pro 3 Docking Station Audio Device                       | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 15.38%  |
| Micron Technology   | 4         | 15.38%  |
| Crucial             | 4         | 15.38%  |
| SK hynix            | 3         | 11.54%  |
| Kingston            | 3         | 11.54%  |
| Unknown             | 2         | 7.69%   |
| A-DATA Technology   | 2         | 7.69%   |
| Nanya Technology    | 1         | 3.85%   |
| Hewlett-Packard     | 1         | 3.85%   |
| G.Skill             | 1         | 3.85%   |
| Corsair             | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 6.67%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 2         | 6.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 6.67%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 3.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1400MT/s               | 1         | 3.33%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s            | 1         | 3.33%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s           | 1         | 3.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 3.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 3.33%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s        | 1         | 3.33%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1         | 3.33%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s         | 1         | 3.33%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s     | 1         | 3.33%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 3.33%   |
| Kingston RAM MSI24D4S7D8MH-16 16384MB SODIMM DDR4 2400MT/s | 1         | 3.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s        | 1         | 3.33%   |
| Kingston RAM ASU16D3LS1KBG/4G 4096MB SODIMM DDR3 1600MT/s  | 1         | 3.33%   |
| HP RAM 7EH65AA# 16384MB DIMM DDR4 2666MT/s                 | 1         | 3.33%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1867MT/s       | 1         | 3.33%   |
| G.Skill RAM F3-12800CL9-4GBSR 4GB DIMM DDR3 1600MT/s       | 1         | 3.33%   |
| Crucial RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 3.33%   |
| Crucial RAM CT8G4DFD8213.C16FBR2 8GB DIMM DDR4 2133MT/s    | 1         | 3.33%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3             | 1         | 3.33%   |
| Crucial RAM CT16G4SFD824A.C16FP 16GB SODIMM DDR4 2400MT/s  | 1         | 3.33%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s      | 1         | 3.33%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3000MT/s                | 1         | 3.33%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s       | 1         | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 45.45%  |
| DDR3   | 10        | 45.45%  |
| LPDDR3 | 1         | 4.55%   |
| DDR2   | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 14        | 63.64%  |
| DIMM   | 8         | 36.36%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 10        | 43.48%  |
| 8192  | 7         | 30.43%  |
| 16384 | 4         | 17.39%  |
| 2048  | 2         | 8.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 9         | 36%     |
| 3200  | 3         | 12%     |
| 2400  | 3         | 12%     |
| 1867  | 2         | 8%      |
| 3400  | 1         | 4%      |
| 3000  | 1         | 4%      |
| 2667  | 1         | 4%      |
| 2666  | 1         | 4%      |
| 2133  | 1         | 4%      |
| 2048  | 1         | 4%      |
| 2000  | 1         | 4%      |
| 1400  | 1         | 4%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 28.57%  |
| Canon              | 2         | 28.57%  |
| Brother Industries | 2         | 28.57%  |
| Star Micronics     | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Star Micronics TUP592 (STR_T-001) | 1         | 14.29%  |
| HP Laser 107a                     | 1         | 14.29%  |
| HP ENVY 5000 series               | 1         | 14.29%  |
| Canon PIXMA MX490 Series          | 1         | 14.29%  |
| Canon G3000 series                | 1         | 14.29%  |
| Brother MFC-L8900CDW series       | 1         | 14.29%  |
| Brother HL-5370DW series          | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 19.23%  |
| IMC Networks                           | 7         | 13.46%  |
| Acer                                   | 5         | 9.62%   |
| Realtek Semiconductor                  | 4         | 7.69%   |
| Apple                                  | 4         | 7.69%   |
| Sunplus Innovation Technology          | 3         | 5.77%   |
| Logitech                               | 3         | 5.77%   |
| Microsoft                              | 2         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.85%   |
| Z-Star Microelectronics                | 1         | 1.92%   |
| Samsung Electronics                    | 1         | 1.92%   |
| Pixart Imaging                         | 1         | 1.92%   |
| Novatek Microelectronics               | 1         | 1.92%   |
| Microdia                               | 1         | 1.92%   |
| Lite-On Technology                     | 1         | 1.92%   |
| Huawei Technologies                    | 1         | 1.92%   |
| Generalplus Technology                 | 1         | 1.92%   |
| GEMBIRD                                | 1         | 1.92%   |
| Cubeternet                             | 1         | 1.92%   |
| ARC International                      | 1         | 1.92%   |
| Alcor Micro                            | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 5.77%   |
| Acer Lenovo EasyCamera                                                     | 3         | 5.77%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 3.85%   |
| Chicony Integrated Camera                                                  | 2         | 3.85%   |
| Apple Built-in iSight                                                      | 2         | 3.85%   |
| Z-Star Integrated Camera                                                   | 1         | 1.92%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.92%   |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 1.92%   |
| Sunplus Asus Webcam                                                        | 1         | 1.92%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.92%   |
| Realtek USB Camera                                                         | 1         | 1.92%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 1.92%   |
| Realtek HP Wide Vision HD Camera                                           | 1         | 1.92%   |
| Realtek HD WebCam                                                          | 1         | 1.92%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                                       | 1         | 1.92%   |
| Novatek J1455                                                              | 1         | 1.92%   |
| Microsoft LifeCam VX-5000                                                  | 1         | 1.92%   |
| Microsoft LifeCam VX-500 [1357]                                            | 1         | 1.92%   |
| Microdia Integrated Webcam                                                 | 1         | 1.92%   |
| Logitech Webcam C270                                                       | 1         | 1.92%   |
| Logitech Webcam C250                                                       | 1         | 1.92%   |
| Logitech QuickCam Communicate MP/S5500                                     | 1         | 1.92%   |
| Lite-On Integrated Camera                                                  | 1         | 1.92%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 1.92%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 1.92%   |
| Huawei UVC Camera                                                          | 1         | 1.92%   |
| Generalplus 808 Camera #9 (web-cam mode)                                   | 1         | 1.92%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                          | 1         | 1.92%   |
| Cubeternet GL-UPC822 UVC WebCam                                            | 1         | 1.92%   |
| Chicony WebCam                                                             | 1         | 1.92%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 1.92%   |
| Chicony USB 2.0 Camera                                                     | 1         | 1.92%   |
| Chicony Sony Visual Communication Camera                                   | 1         | 1.92%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.92%   |
| Chicony HP Wide Vision HD Camera                                           | 1         | 1.92%   |
| Chicony HD WebCam                                                          | 1         | 1.92%   |
| Chicony FJ Camera                                                          | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 1         | 1.92%   |
| ARC International Camera                                                   | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 66.67%  |
| Synaptics                  | 1         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 16.67%  |
| Validity Sensors VFS471 Fingerprint Reader | 1         | 16.67%  |
| Validity Sensors VFS Fingerprint sensor    | 1         | 16.67%  |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 16.67%  |
| Synaptics  WBDI                            | 1         | 16.67%  |
| Shenzhen Goodix  Fingerprint Device        | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| OmniKey           | 1         | 25%     |
| Mako Technologies | 1         | 25%     |
| Broadcom          | 1         | 25%     |
| BIT4ID            | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| OmniKey CardMan 4321          | 1         | 25%     |
| Mako Technologies SZZCS-ZCS80 | 1         | 25%     |
| Broadcom 5880                 | 1         | 25%     |
| BIT4ID miniLector EVO         | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 65        | 73.86%  |
| 1     | 20        | 22.73%  |
| 2     | 3         | 3.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 6         | 24%     |
| Fingerprint reader    | 6         | 24%     |
| Net/wireless          | 5         | 20%     |
| Chipcard              | 3         | 12%     |
| Multimedia controller | 2         | 8%      |
| Sound                 | 1         | 4%      |
| Net/ethernet          | 1         | 4%      |
| Bluetooth             | 1         | 4%      |

