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

Total: 136

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Feren OS 20.04   | 48        | 56.47%  |
| Feren OS 18.04   | 35        | 41.18%  |
| Feren OS 2018.10 | 2         | 2.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Feren OS | 83        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.11.0-37-generic       | 7         | 7.14%   |
| 5.3.0-46-generic        | 5         | 5.1%    |
| 5.8.0-55-generic        | 4         | 4.08%   |
| 5.8.0-53-generic        | 4         | 4.08%   |
| 5.4.0-42-generic        | 4         | 4.08%   |
| 5.0.0-37-generic        | 4         | 4.08%   |
| 5.8.0-48-generic        | 3         | 3.06%   |
| 5.4.0-52-generic        | 3         | 3.06%   |
| 5.3.0-51-generic        | 3         | 3.06%   |
| 5.15.0-48-generic       | 3         | 3.06%   |
| 5.8.0-50-generic        | 2         | 2.04%   |
| 5.8.0-36-generic        | 2         | 2.04%   |
| 5.4.0-54-generic        | 2         | 2.04%   |
| 5.4.0-48-generic        | 2         | 2.04%   |
| 5.4.0-47-generic        | 2         | 2.04%   |
| 5.4.0-45-generic        | 2         | 2.04%   |
| 5.3.0-59-generic        | 2         | 2.04%   |
| 5.3.0-53-generic        | 2         | 2.04%   |
| 5.11.0-40-generic       | 2         | 2.04%   |
| 5.11.0-27-generic       | 2         | 2.04%   |
| 4.15.0-48-generic       | 2         | 2.04%   |
| 5.8.0-44-generic        | 1         | 1.02%   |
| 5.8.0-40-generic        | 1         | 1.02%   |
| 5.8.0-29-generic        | 1         | 1.02%   |
| 5.4.66-xanmod1          | 1         | 1.02%   |
| 5.4.0-77-generic        | 1         | 1.02%   |
| 5.4.0-74-generic        | 1         | 1.02%   |
| 5.4.0-72-generic        | 1         | 1.02%   |
| 5.4.0-58-generic        | 1         | 1.02%   |
| 5.4.0-51-generic        | 1         | 1.02%   |
| 5.4.0-37-generic        | 1         | 1.02%   |
| 5.4.0-31-generic        | 1         | 1.02%   |
| 5.3.0-42-generic        | 1         | 1.02%   |
| 5.3.0-40-generic        | 1         | 1.02%   |
| 5.3.0-28-generic        | 1         | 1.02%   |
| 5.17.5-76051705-generic | 1         | 1.02%   |
| 5.15.6-051506-generic   | 1         | 1.02%   |
| 5.15.0-50-generic       | 1         | 1.02%   |
| 5.15.0-46-generic       | 1         | 1.02%   |
| 5.15.0-41-generic       | 1         | 1.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 21.59%  |
| 5.8.0   | 17        | 19.32%  |
| 5.3.0   | 14        | 15.91%  |
| 5.11.0  | 12        | 13.64%  |
| 5.15.0  | 7         | 7.95%   |
| 4.15.0  | 6         | 6.82%   |
| 5.13.0  | 5         | 5.68%   |
| 5.0.0   | 5         | 5.68%   |
| 5.4.66  | 1         | 1.14%   |
| 5.17.5  | 1         | 1.14%   |
| 5.15.6  | 1         | 1.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 21.84%  |
| 5.8     | 17        | 19.54%  |
| 5.3     | 14        | 16.09%  |
| 5.11    | 12        | 13.79%  |
| 5.15    | 8         | 9.2%    |
| 4.15    | 6         | 6.9%    |
| 5.13    | 5         | 5.75%   |
| 5.0     | 5         | 5.75%   |
| 5.17    | 1         | 1.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 83        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE        | 47        | 54.02%  |
| KDE5       | 26        | 29.89%  |
| Unknown    | 9         | 10.34%  |
| X-Cinnamon | 3         | 3.45%   |
| GNOME      | 2         | 2.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 83        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 68        | 81.93%  |
| LightDM | 11        | 13.25%  |
| TDM     | 4         | 4.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 23        | 27.06%  |
| en_GB   | 16        | 18.82%  |
| Unknown | 7         | 8.24%   |
| de_DE   | 6         | 7.06%   |
| de_CH   | 6         | 7.06%   |
| en_AU   | 5         | 5.88%   |
| en_IN   | 3         | 3.53%   |
| pt_BR   | 2         | 2.35%   |
| nl_BE   | 2         | 2.35%   |
| es_VE   | 2         | 2.35%   |
| en_CA   | 2         | 2.35%   |
| pt_PT   | 1         | 1.18%   |
| it_IT   | 1         | 1.18%   |
| fi_FI   | 1         | 1.18%   |
| es_UY   | 1         | 1.18%   |
| es_PE   | 1         | 1.18%   |
| es_MX   | 1         | 1.18%   |
| es_HN   | 1         | 1.18%   |
| es_ES   | 1         | 1.18%   |
| es_CL   | 1         | 1.18%   |
| en_IE   | 1         | 1.18%   |
| de_AT   | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 49        | 59.04%  |
| BIOS | 34        | 40.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 70        | 82.35%  |
| Btrfs   | 7         | 8.24%   |
| Unknown | 6         | 7.06%   |
| Overlay | 2         | 2.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 72        | 85.71%  |
| GPT     | 11        | 13.1%   |
| MBR     | 1         | 1.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 98.8%   |
| Yes       | 1         | 1.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 86.75%  |
| Yes       | 11        | 13.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 20        | 24.1%   |
| MSI                 | 10        | 12.05%  |
| Lenovo              | 8         | 9.64%   |
| Hewlett-Packard     | 8         | 9.64%   |
| Dell                | 7         | 8.43%   |
| Gigabyte Technology | 4         | 4.82%   |
| Apple               | 4         | 4.82%   |
| ASRock              | 3         | 3.61%   |
| Acer                | 3         | 3.61%   |
| Sony                | 2         | 2.41%   |
| Pegatron            | 2         | 2.41%   |
| ZOTAC               | 1         | 1.2%    |
| Wortmann AG         | 1         | 1.2%    |
| Toshiba             | 1         | 1.2%    |
| PCWare              | 1         | 1.2%    |
| Panasonic           | 1         | 1.2%    |
| Microsoft           | 1         | 1.2%    |
| Medion              | 1         | 1.2%    |
| HUAWEI              | 1         | 1.2%    |
| Fujitsu             | 1         | 1.2%    |
| Foxconn             | 1         | 1.2%    |
| Exo                 | 1         | 1.2%    |
| Unknown             | 1         | 1.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 3         | 3.61%   |
| ASUS ROG Zephyrus M16 GU603HE_GU603HE  | 2         | 2.41%   |
| ASUS PRIME Z370-A                      | 2         | 2.41%   |
| ZOTAC ZBOX-CI527/CI547                 | 1         | 1.2%    |
| Wortmann AG TERRA_PC                   | 1         | 1.2%    |
| Toshiba Satellite T135D                | 1         | 1.2%    |
| Sony VPCEE4J1E                         | 1         | 1.2%    |
| Sony SVF15318SNB                       | 1         | 1.2%    |
| Pegatron p7-1030                       | 1         | 1.2%    |
| Pegatron AY691AA-ABA p6367c            | 1         | 1.2%    |
| PCWare IPMH81G1                        | 1         | 1.2%    |
| Panasonic CF-J10YYBHR                  | 1         | 1.2%    |
| MSI Traveller 1591                     | 1         | 1.2%    |
| MSI MS-7C37                            | 1         | 1.2%    |
| MSI MS-7B89                            | 1         | 1.2%    |
| MSI MS-7A37                            | 1         | 1.2%    |
| MSI MS-7788                            | 1         | 1.2%    |
| MSI GS66 Stealth 10SE                  | 1         | 1.2%    |
| MSI GP72 7RDX                          | 1         | 1.2%    |
| MSI GE66 Raider 11UG                   | 1         | 1.2%    |
| MSI C Series                           | 1         | 1.2%    |
| MSI 700-216                            | 1         | 1.2%    |
| Microsoft Surface Pro 3                | 1         | 1.2%    |
| Medion H61H2-LM3                       | 1         | 1.2%    |
| Lenovo Yoga 730-15IKB 81CU             | 1         | 1.2%    |
| Lenovo XiaoXin Air 12 80UN             | 1         | 1.2%    |
| Lenovo ThinkPad X240 20AMS72901        | 1         | 1.2%    |
| Lenovo ThinkPad X230 2325AT6           | 1         | 1.2%    |
| Lenovo ThinkCentre M72z 3548B2S        | 1         | 1.2%    |
| Lenovo Legion Y7000P 81LD              | 1         | 1.2%    |
| Lenovo G550 2958                       | 1         | 1.2%    |
| Lenovo G50-45 80E3                     | 1         | 1.2%    |
| HUAWEI BOHK-WAX9X                      | 1         | 1.2%    |
| HP ProLiant DL380p Gen8                | 1         | 1.2%    |
| HP ProBook 6560b                       | 1         | 1.2%    |
| HP Pavilion x360 Convertible 14-cd1xxx | 1         | 1.2%    |
| HP Pavilion Laptop 14-bf0xx            | 1         | 1.2%    |
| HP Pavilion Gaming Laptop 15-cx0xxx    | 1         | 1.2%    |
| HP Pavilion Desktop PC 570-p0xx        | 1         | 1.2%    |
| HP EliteDesk 800 G3 DM 35W             | 1         | 1.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUS PRIME            | 6         | 7.23%   |
| HP Pavilion           | 4         | 4.82%   |
| Dell OptiPlex         | 3         | 3.61%   |
| ASUS All              | 3         | 3.61%   |
| Lenovo ThinkPad       | 2         | 2.41%   |
| Dell Latitude         | 2         | 2.41%   |
| Dell Inspiron         | 2         | 2.41%   |
| ASUS VivoBook         | 2         | 2.41%   |
| ASUS ROG              | 2         | 2.41%   |
| ZOTAC ZBOX-CI527      | 1         | 1.2%    |
| Wortmann AG TERRA     | 1         | 1.2%    |
| Toshiba Satellite     | 1         | 1.2%    |
| Sony VPCEE4J1E        | 1         | 1.2%    |
| Sony SVF15318SNB      | 1         | 1.2%    |
| Pegatron p7-1030      | 1         | 1.2%    |
| Pegatron AY691AA-ABA  | 1         | 1.2%    |
| PCWare IPMH81G1       | 1         | 1.2%    |
| Panasonic CF-J10YYBHR | 1         | 1.2%    |
| MSI Traveller         | 1         | 1.2%    |
| MSI MS-7C37           | 1         | 1.2%    |
| MSI MS-7B89           | 1         | 1.2%    |
| MSI MS-7A37           | 1         | 1.2%    |
| MSI MS-7788           | 1         | 1.2%    |
| MSI GS66              | 1         | 1.2%    |
| MSI GP72              | 1         | 1.2%    |
| MSI GE66              | 1         | 1.2%    |
| MSI C                 | 1         | 1.2%    |
| MSI 700-216           | 1         | 1.2%    |
| Microsoft Surface     | 1         | 1.2%    |
| Medion H61H2-LM3      | 1         | 1.2%    |
| Lenovo Yoga           | 1         | 1.2%    |
| Lenovo XiaoXin        | 1         | 1.2%    |
| Lenovo ThinkCentre    | 1         | 1.2%    |
| Lenovo Legion         | 1         | 1.2%    |
| Lenovo G550           | 1         | 1.2%    |
| Lenovo G50-45         | 1         | 1.2%    |
| HUAWEI BOHK-WAX9X     | 1         | 1.2%    |
| HP ProLiant           | 1         | 1.2%    |
| HP ProBook            | 1         | 1.2%    |
| HP EliteDesk          | 1         | 1.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2017 | 13        | 15.66%  |
| 2011 | 10        | 12.05%  |
| 2012 | 9         | 10.84%  |
| 2013 | 8         | 9.64%   |
| 2019 | 7         | 8.43%   |
| 2018 | 6         | 7.23%   |
| 2014 | 6         | 7.23%   |
| 2016 | 5         | 6.02%   |
| 2009 | 5         | 6.02%   |
| 2021 | 4         | 4.82%   |
| 2020 | 4         | 4.82%   |
| 2008 | 3         | 3.61%   |
| 2015 | 1         | 1.2%    |
| 2010 | 1         | 1.2%    |
| 2006 | 1         | 1.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 37        | 44.58%  |
| Desktop     | 36        | 43.37%  |
| All in one  | 4         | 4.82%   |
| Convertible | 2         | 2.41%   |
| Mini pc     | 2         | 2.41%   |
| Tablet      | 1         | 1.2%    |
| Server      | 1         | 1.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 79        | 94.05%  |
| Enabled  | 5         | 5.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 83        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 23.26%  |
| 8.01-16.0   | 19        | 22.09%  |
| 16.01-24.0  | 18        | 20.93%  |
| 3.01-4.0    | 14        | 16.28%  |
| 32.01-64.0  | 8         | 9.3%    |
| 64.01-256.0 | 3         | 3.49%   |
| 24.01-32.0  | 2         | 2.33%   |
| 1.01-2.0    | 2         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 38        | 41.3%   |
| 2.01-3.0  | 30        | 32.61%  |
| 3.01-4.0  | 12        | 13.04%  |
| 4.01-8.0  | 9         | 9.78%   |
| 0.51-1.0  | 2         | 2.17%   |
| 8.01-16.0 | 1         | 1.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 56.98%  |
| 2      | 20        | 23.26%  |
| 3      | 11        | 12.79%  |
| 4      | 3         | 3.49%   |
| 7      | 1         | 1.16%   |
| 5      | 1         | 1.16%   |
| 0      | 1         | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 61.45%  |
| Yes       | 32        | 38.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 91.57%  |
| No        | 7         | 8.43%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 69.88%  |
| No        | 25        | 30.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 52.94%  |
| No        | 40        | 47.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 17        | 20.48%  |
| Switzerland | 9         | 10.84%  |
| Germany     | 8         | 9.64%   |
| Australia   | 7         | 8.43%   |
| UK          | 6         | 7.23%   |
| India       | 3         | 3.61%   |
| Canada      | 3         | 3.61%   |
| Brazil      | 3         | 3.61%   |
| Venezuela   | 2         | 2.41%   |
| Turkey      | 2         | 2.41%   |
| Poland      | 2         | 2.41%   |
| Belgium     | 2         | 2.41%   |
| Argentina   | 2         | 2.41%   |
| Uruguay     | 1         | 1.2%    |
| UAE         | 1         | 1.2%    |
| Spain       | 1         | 1.2%    |
| Portugal    | 1         | 1.2%    |
| Peru        | 1         | 1.2%    |
| Norway      | 1         | 1.2%    |
| Mexico      | 1         | 1.2%    |
| Jordan      | 1         | 1.2%    |
| Japan       | 1         | 1.2%    |
| Italy       | 1         | 1.2%    |
| Ireland     | 1         | 1.2%    |
| Honduras    | 1         | 1.2%    |
| Greece      | 1         | 1.2%    |
| Finland     | 1         | 1.2%    |
| Chile       | 1         | 1.2%    |
| Bulgaria    | 1         | 1.2%    |
| Belize      | 1         | 1.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Oberwil-Lieli  | 8         | 8.99%   |
| Melbourne      | 3         | 3.37%   |
| Winterthur     | 2         | 2.25%   |
| Richmond       | 2         | 2.25%   |
| Istanbul       | 2         | 2.25%   |
| Escondido      | 2         | 2.25%   |
| Ypsilanti      | 1         | 1.12%   |
| Wrexham        | 1         | 1.12%   |
| Varna          | 1         | 1.12%   |
| Tegucigalpa    | 1         | 1.12%   |
| Surat          | 1         | 1.12%   |
| Stuttgart      | 1         | 1.12%   |
| Stavanger      | 1         | 1.12%   |
| Sligo          | 1         | 1.12%   |
| Seattle        | 1         | 1.12%   |
| Schleusingen   | 1         | 1.12%   |
| Sao Jose       | 1         | 1.12%   |
| Santiago       | 1         | 1.12%   |
| Sankt Augustin | 1         | 1.12%   |
| Saitama        | 1         | 1.12%   |
| Recklinghausen | 1         | 1.12%   |
| Portland       | 1         | 1.12%   |
| Plymouth       | 1         | 1.12%   |
| Phoenix        | 1         | 1.12%   |
| Oudenaarde     | 1         | 1.12%   |
| New York       | 1         | 1.12%   |
| Naples         | 1         | 1.12%   |
| Montevideo     | 1         | 1.12%   |
| Moncton        | 1         | 1.12%   |
| Mieres         | 1         | 1.12%   |
| Maracay        | 1         | 1.12%   |
| Macaé         | 1         | 1.12%   |
| Los Angeles    | 1         | 1.12%   |
| Lineville      | 1         | 1.12%   |
| Lima           | 1         | 1.12%   |
| Leicester      | 1         | 1.12%   |
| Lafayette      | 1         | 1.12%   |
| La Barca       | 1         | 1.12%   |
| Krakow         | 1         | 1.12%   |
| Kloten         | 1         | 1.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 20        | 31     | 15.87%  |
| Seagate                   | 18        | 25     | 14.29%  |
| Samsung Electronics       | 15        | 19     | 11.9%   |
| Unknown                   | 8         | 8      | 6.35%   |
| Toshiba                   | 8         | 11     | 6.35%   |
| SanDisk                   | 8         | 10     | 6.35%   |
| Intel                     | 8         | 9      | 6.35%   |
| Hitachi                   | 8         | 9      | 6.35%   |
| Kingston                  | 6         | 14     | 4.76%   |
| HGST                      | 4         | 4      | 3.17%   |
| SK hynix                  | 3         | 4      | 2.38%   |
| Phison                    | 3         | 3      | 2.38%   |
| A-DATA Technology         | 3         | 3      | 2.38%   |
| Realtek Semiconductor     | 2         | 2      | 1.59%   |
| PNY                       | 2         | 2      | 1.59%   |
| OCZ                       | 2         | 2      | 1.59%   |
| Crucial                   | 2         | 5      | 1.59%   |
| Verbatim                  | 1         | 1      | 0.79%   |
| Micron/Crucial Technology | 1         | 1      | 0.79%   |
| LITEONIT                  | 1         | 1      | 0.79%   |
| LITEON                    | 1         | 1      | 0.79%   |
| IBM                       | 1         | 1      | 0.79%   |
| China                     | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 1TB          | 3         | 2.21%   |
| Unknown MMC Card  32GB             | 2         | 1.47%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 1.47%   |
| Seagate ST4000LM016-1N2170 4TB     | 2         | 1.47%   |
| Seagate ST31000528AS 1TB           | 2         | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 1.47%   |
| Samsung HD103SJ 1TB                | 2         | 1.47%   |
| Realtek NVMe SSD Drive 512GB       | 2         | 1.47%   |
| Phison NVMe SSD Drive 1TB          | 2         | 1.47%   |
| Kingston SA400S37480G 480GB SSD    | 2         | 1.47%   |
| Intel NVMe SSD Drive 512GB         | 2         | 1.47%   |
| Hitachi HDS721010CLA332 1TB        | 2         | 1.47%   |
| HGST HTS721010A9E630 1TB           | 2         | 1.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 0.74%   |
| WDC WDS500G1R0B-68A4Z0 500GB SSD   | 1         | 0.74%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.74%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 1         | 0.74%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 1         | 0.74%   |
| WDC WD80EFBX-68AZZN0 8TB           | 1         | 0.74%   |
| WDC WD6400AAKS-00A7B2 640GB        | 1         | 0.74%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 0.74%   |
| WDC WD5000BPKT-60PK4T0 500GB       | 1         | 0.74%   |
| WDC WD5000AAVS-00G9B1 500GB        | 1         | 0.74%   |
| WDC WD5000AAKS-65A7B2 500GB        | 1         | 0.74%   |
| WDC WD5000AAKS-00A7B2 500GB        | 1         | 0.74%   |
| WDC WD30EZRX-00MMMB0 3TB           | 1         | 0.74%   |
| WDC WD30EZRX-00D8PB0 3TB           | 1         | 0.74%   |
| WDC WD2500BPVT-00JJ5T0 250GB       | 1         | 0.74%   |
| WDC WD2500AAKX-75U6AA0 250GB       | 1         | 0.74%   |
| WDC WD1600AAJS-00L7A0 160GB        | 1         | 0.74%   |
| WDC WD10PURX-78E5EY0 1TB           | 1         | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 0.74%   |
| WDC WD10EZEX-60WN4A0 1TB           | 1         | 0.74%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1         | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1         | 0.74%   |
| WDC WD10EZEX-00WN4A0 1TB           | 1         | 0.74%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1         | 0.74%   |
| WDC WD10EURX-83UY4Y0 1TB           | 1         | 0.74%   |
| Verbatim Vi550 S3 SSD 512GB        | 1         | 0.74%   |
| Unknown SB128  128GB               | 1         | 0.74%   |

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
| Samsung Electronics | 7         | 9      | 15.22%  |
| SanDisk             | 6         | 7      | 13.04%  |
| Kingston            | 6         | 14     | 13.04%  |
| Intel               | 5         | 5      | 10.87%  |
| WDC                 | 4         | 4      | 8.7%    |
| Toshiba             | 3         | 4      | 6.52%   |
| A-DATA Technology   | 3         | 3      | 6.52%   |
| SK hynix            | 2         | 3      | 4.35%   |
| PNY                 | 2         | 2      | 4.35%   |
| OCZ                 | 2         | 2      | 4.35%   |
| Crucial             | 2         | 5      | 4.35%   |
| Verbatim            | 1         | 1      | 2.17%   |
| LITEONIT            | 1         | 1      | 2.17%   |
| LITEON              | 1         | 1      | 2.17%   |
| China               | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 47        | 74     | 41.59%  |
| SSD     | 40        | 62     | 35.4%   |
| NVMe    | 19        | 23     | 16.81%  |
| MMC     | 5         | 6      | 4.42%   |
| Unknown | 2         | 2      | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 70        | 131    | 68.63%  |
| NVMe | 19        | 23     | 18.63%  |
| SAS  | 8         | 7      | 7.84%   |
| MMC  | 5         | 6      | 4.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 52        | 78     | 57.14%  |
| 0.51-1.0   | 28        | 42     | 30.77%  |
| 1.01-2.0   | 5         | 6      | 5.49%   |
| 3.01-4.0   | 3         | 7      | 3.3%    |
| 2.01-3.0   | 2         | 2      | 2.2%    |
| 4.01-10.0  | 1         | 1      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 22        | 24.44%  |
| 101-250        | 22        | 24.44%  |
| 1001-2000      | 16        | 17.78%  |
| 501-1000       | 13        | 14.44%  |
| More than 3000 | 4         | 4.44%   |
| 2001-3000      | 4         | 4.44%   |
| 51-100         | 4         | 4.44%   |
| 21-50          | 3         | 3.33%   |
| 1-20           | 1         | 1.11%   |
| Unknown        | 1         | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 28        | 31.11%  |
| 1-20      | 15        | 16.67%  |
| 251-500   | 14        | 15.56%  |
| 101-250   | 12        | 13.33%  |
| 51-100    | 12        | 13.33%  |
| 501-1000  | 7         | 7.78%   |
| 1001-2000 | 1         | 1.11%   |
| Unknown   | 1         | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000AAVS-00G9B1 500GB        | 1         | 1      | 16.67%  |
| Toshiba MK1234GSX 120GB            | 1         | 1      | 16.67%  |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 16.67%  |
| Seagate ST3500418AS 500GB          | 1         | 1      | 16.67%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 16.67%  |
| Intel SSDSC2BW240A4 240GB          | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 50%     |
| WDC     | 1         | 1      | 16.67%  |
| Toshiba | 1         | 1      | 16.67%  |
| Intel   | 1         | 1      | 16.67%  |

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
| HDD  | 4         | 5      | 80%     |
| SSD  | 1         | 1      | 20%     |

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
| Detected | 72        | 137    | 80.9%   |
| Works    | 11        | 23     | 12.36%  |
| Malfunc  | 5         | 6      | 5.62%   |
| Failed   | 1         | 1      | 1.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 61        | 59.22%  |
| AMD                          | 14        | 13.59%  |
| Samsung Electronics          | 10        | 9.71%   |
| SanDisk                      | 3         | 2.91%   |
| Phison Electronics           | 3         | 2.91%   |
| Nvidia                       | 3         | 2.91%   |
| Realtek Semiconductor        | 2         | 1.94%   |
| ASMedia Technology           | 2         | 1.94%   |
| Toshiba America Info Systems | 1         | 0.97%   |
| SK hynix                     | 1         | 0.97%   |
| Micron/Crucial Technology    | 1         | 0.97%   |
| JMicron Technology           | 1         | 0.97%   |
| Hewlett-Packard              | 1         | 0.97%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 7.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 4.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 4.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 4.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 4.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 3.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 3.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 2.44%   |
| Phison E12 NVMe Controller                                                              | 3         | 2.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 2.44%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3         | 2.44%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.63%   |
| Intel Non-Volatile memory controller                                                    | 2         | 1.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.63%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 1.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.63%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.63%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.81%   |
| SK hynix Gold P31 SSD                                                                   | 1         | 0.81%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1         | 0.81%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.81%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.81%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1         | 0.81%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 0.81%   |
| Nvidia nForce SATA Controller                                                           | 1         | 0.81%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.81%   |
| Nvidia MCP55 SATA Controller                                                            | 1         | 0.81%   |
| Nvidia MCP55 IDE                                                                        | 1         | 0.81%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 63        | 60%     |
| NVMe | 22        | 20.95%  |
| IDE  | 13        | 12.38%  |
| RAID | 7         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 67        | 80.72%  |
| AMD    | 16        | 19.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 3.61%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 2         | 2.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 2.41%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 2         | 2.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 2.41%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 2         | 2.41%   |
| Intel Celeron CPU 1007U @ 1.50GHz       | 2         | 2.41%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 2         | 2.41%   |
| Intel Xeon CPU E5-2667 0 @ 2.90GHz      | 1         | 1.2%    |
| Intel Pentium D CPU 3.00GHz             | 1         | 1.2%    |
| Intel Pentium CPU P6200 @ 2.13GHz       | 1         | 1.2%    |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 1.2%    |
| Intel Pentium CPU G630 @ 2.70GHz        | 1         | 1.2%    |
| Intel Pentium CPU G3250 @ 3.20GHz       | 1         | 1.2%    |
| Intel Pentium CPU 4415U @ 2.30GHz       | 1         | 1.2%    |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 1.2%    |
| Intel Core i7-7700T CPU @ 2.90GHz       | 1         | 1.2%    |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 1.2%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.2%    |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1         | 1.2%    |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.2%    |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1         | 1.2%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz      | 1         | 1.2%    |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.2%    |
| Intel Core i7-3770S CPU @ 3.10GHz       | 1         | 1.2%    |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1         | 1.2%    |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1         | 1.2%    |
| Intel Core i7-10875H CPU @ 2.30GHz      | 1         | 1.2%    |
| Intel Core i7-10700 CPU @ 2.90GHz       | 1         | 1.2%    |
| Intel Core i7 CPU 920 @ 2.67GHz         | 1         | 1.2%    |
| Intel Core i5-9400F CPU @ 2.90GHz       | 1         | 1.2%    |
| Intel Core i5-8300H CPU @ 2.30GHz       | 1         | 1.2%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.2%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.2%    |
| Intel Core i5-4690K CPU @ 3.50GHz       | 1         | 1.2%    |
| Intel Core i5-4260U CPU @ 1.40GHz       | 1         | 1.2%    |
| Intel Core i5-4210M CPU @ 2.60GHz       | 1         | 1.2%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.2%    |
| Intel Core i5-3570K CPU @ 3.40GHz       | 1         | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 22.89%  |
| Intel Core i7           | 18        | 21.69%  |
| Intel Core i3           | 7         | 8.43%   |
| Intel Pentium           | 5         | 6.02%   |
| Intel Celeron           | 5         | 6.02%   |
| AMD Ryzen 5             | 4         | 4.82%   |
| Other                   | 3         | 3.61%   |
| Intel Core 2 Quad       | 3         | 3.61%   |
| Intel Core 2 Duo        | 2         | 2.41%   |
| AMD Ryzen 9             | 2         | 2.41%   |
| AMD Ryzen 7             | 2         | 2.41%   |
| AMD A8                  | 2         | 2.41%   |
| Intel Xeon              | 1         | 1.2%    |
| Intel Pentium D         | 1         | 1.2%    |
| Intel Core m3           | 1         | 1.2%    |
| Intel Celeron Dual-Core | 1         | 1.2%    |
| Intel Atom              | 1         | 1.2%    |
| AMD Turion Neo X2       | 1         | 1.2%    |
| AMD FX                  | 1         | 1.2%    |
| AMD Athlon X2           | 1         | 1.2%    |
| AMD Athlon II           | 1         | 1.2%    |
| AMD A6                  | 1         | 1.2%    |
| AMD A10                 | 1         | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 40        | 48.19%  |
| 4      | 28        | 33.73%  |
| 8      | 8         | 9.64%   |
| 6      | 5         | 6.02%   |
| 12     | 2         | 2.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 82        | 98.8%   |
| 2      | 1         | 1.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 56        | 67.47%  |
| 1      | 27        | 32.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 77        | 92.77%  |
| Unknown        | 6         | 7.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 8         | 9.64%   |
| 0x206a7    | 8         | 9.64%   |
| 0x306c3    | 7         | 8.43%   |
| 0x40651    | 5         | 6.02%   |
| 0x1067a    | 5         | 6.02%   |
| 0x906ea    | 4         | 4.82%   |
| 0x906e9    | 4         | 4.82%   |
| 0x806d1    | 3         | 3.61%   |
| Unknown    | 3         | 3.61%   |
| 0x806ea    | 2         | 2.41%   |
| 0x806e9    | 2         | 2.41%   |
| 0x706a8    | 2         | 2.41%   |
| 0x406e3    | 2         | 2.41%   |
| 0x0800820d | 2         | 2.41%   |
| 0x08001138 | 2         | 2.41%   |
| 0xf62      | 1         | 1.2%    |
| 0xa0655    | 1         | 1.2%    |
| 0xa0652    | 1         | 1.2%    |
| 0x806eb    | 1         | 1.2%    |
| 0x6fb      | 1         | 1.2%    |
| 0x506e3    | 1         | 1.2%    |
| 0x506c9    | 1         | 1.2%    |
| 0x406c4    | 1         | 1.2%    |
| 0x306d4    | 1         | 1.2%    |
| 0x206d7    | 1         | 1.2%    |
| 0x20655    | 1         | 1.2%    |
| 0x106e5    | 1         | 1.2%    |
| 0x106a5    | 1         | 1.2%    |
| 0x0a50000c | 1         | 1.2%    |
| 0x08701021 | 1         | 1.2%    |
| 0x08108109 | 1         | 1.2%    |
| 0x0810100b | 1         | 1.2%    |
| 0x07030105 | 1         | 1.2%    |
| 0x0600611a | 1         | 1.2%    |
| 0x06003104 | 1         | 1.2%    |
| 0x06001119 | 1         | 1.2%    |
| 0x06000852 | 1         | 1.2%    |
| 0x02000032 | 1         | 1.2%    |
| 0x010000c8 | 1         | 1.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 13        | 15.66%  |
| Haswell         | 12        | 14.46%  |
| SandyBridge     | 10        | 12.05%  |
| IvyBridge       | 9         | 10.84%  |
| Penryn          | 5         | 6.02%   |
| Zen+            | 3         | 3.61%   |
| Zen             | 3         | 3.61%   |
| Skylake         | 3         | 3.61%   |
| Icelake         | 3         | 3.61%   |
| Piledriver      | 2         | 2.41%   |
| Nehalem         | 2         | 2.41%   |
| Goldmont plus   | 2         | 2.41%   |
| CometLake       | 2         | 2.41%   |
| Zen 3           | 1         | 1.2%    |
| Zen 2           | 1         | 1.2%    |
| Westmere        | 1         | 1.2%    |
| Steamroller     | 1         | 1.2%    |
| Silvermont      | 1         | 1.2%    |
| Puma            | 1         | 1.2%    |
| NetBurst        | 1         | 1.2%    |
| K8 Hammer       | 1         | 1.2%    |
| K8 & K10 hybrid | 1         | 1.2%    |
| K10             | 1         | 1.2%    |
| Goldmont        | 1         | 1.2%    |
| Excavator       | 1         | 1.2%    |
| Core            | 1         | 1.2%    |
| Broadwell       | 1         | 1.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 51        | 52.04%  |
| Nvidia                     | 30        | 30.61%  |
| AMD                        | 16        | 16.33%  |
| Matrox Electronics Systems | 1         | 1.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 5.1%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 5.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 5.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 4         | 4.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 3         | 3.06%   |
| Intel HD Graphics 630                                                       | 3         | 3.06%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2         | 2.04%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 2.04%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 2         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 2.04%   |
| Intel UHD Graphics 620                                                      | 2         | 2.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 2.04%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 2.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 2.04%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2         | 2.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 2.04%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 1.02%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 1.02%   |
| Nvidia MCP7A [GeForce 9400]                                                 | 1         | 1.02%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 1.02%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1         | 1.02%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 1.02%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 1.02%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 1.02%   |
| Nvidia GK208BM [GeForce 920M]                                               | 1         | 1.02%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 1.02%   |
| Nvidia GK107M [GeForce GT 750M]                                             | 1         | 1.02%   |
| Nvidia GK107 [NVS 510]                                                      | 1         | 1.02%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1         | 1.02%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1         | 1.02%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1         | 1.02%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 1         | 1.02%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 1         | 1.02%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1         | 1.02%   |
| Nvidia C77 [GeForce 9100M G]                                                | 1         | 1.02%   |
| Matrox Electronics Systems MGA G200EH                                       | 1         | 1.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 44.58%  |
| 1 x Nvidia     | 17        | 20.48%  |
| 1 x AMD        | 14        | 16.87%  |
| Intel + Nvidia | 12        | 14.46%  |
| 1 x Matrox     | 1         | 1.2%    |
| Intel + AMD    | 1         | 1.2%    |
| AMD + Nvidia   | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 64        | 75.29%  |
| Proprietary | 19        | 22.35%  |
| Unknown     | 2         | 2.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 49.41%  |
| 1.01-2.0   | 12        | 14.12%  |
| 0.51-1.0   | 9         | 10.59%  |
| 3.01-4.0   | 7         | 8.24%   |
| 0.01-0.5   | 7         | 8.24%   |
| 7.01-8.0   | 6         | 7.06%   |
| 5.01-6.0   | 2         | 2.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 10        | 11.9%   |
| Samsung Electronics     | 9         | 10.71%  |
| AU Optronics            | 9         | 10.71%  |
| BOE                     | 8         | 9.52%   |
| Acer                    | 7         | 8.33%   |
| Dell                    | 5         | 5.95%   |
| Apple                   | 4         | 4.76%   |
| Lenovo                  | 3         | 3.57%   |
| Hewlett-Packard         | 3         | 3.57%   |
| Chimei Innolux          | 3         | 3.57%   |
| Sharp                   | 2         | 2.38%   |
| Philips                 | 2         | 2.38%   |
| Chi Mei Optoelectronics | 2         | 2.38%   |
| AOC                     | 2         | 2.38%   |
| Vestel                  | 1         | 1.19%   |
| Unknown                 | 1         | 1.19%   |
| Toshiba                 | 1         | 1.19%   |
| Sony                    | 1         | 1.19%   |
| Sceptre Tech            | 1         | 1.19%   |
| Ruijiang                | 1         | 1.19%   |
| Panasonic               | 1         | 1.19%   |
| Onkyo                   | 1         | 1.19%   |
| Medion                  | 1         | 1.19%   |
| LG Electronics          | 1         | 1.19%   |
| Lenovo Group Limited    | 1         | 1.19%   |
| Insignia                | 1         | 1.19%   |
| Goldstar                | 1         | 1.19%   |
| BenQ                    | 1         | 1.19%   |
| Ancor Communications    | 1         | 1.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch         | 2         | 2.25%   |
| Vestel LCD Monitor 32W_LCD_TV 1920x1080                                | 1         | 1.12%   |
| Unknown LCD Monitor SAMSUNG                                            | 1         | 1.12%   |
| Toshiba LCD Monitor LCD0905 1366x768 295x166mm 13.3-inch               | 1         | 1.12%   |
| Sony AVAMP SNYF400 1920x1080 700x390mm 31.5-inch                       | 1         | 1.12%   |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch                | 1         | 1.12%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                | 1         | 1.12%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch         | 1         | 1.12%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch      | 1         | 1.12%   |
| Samsung Electronics LCD Monitor U28E590 7680x2160                      | 1         | 1.12%   |
| Samsung Electronics LCD Monitor U28E590                                | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch   | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch | 1         | 1.12%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1         | 1.12%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1         | 1.12%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch      | 1         | 1.12%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 1         | 1.12%   |
| Ruijiang RJT HDMI RJT1200 1920x1200 320x180mm 14.5-inch                | 1         | 1.12%   |
| Philips PHL 328E9Q PHLC180 1920x1080 698x393mm 31.5-inch               | 1         | 1.12%   |
| Philips 220EW PHL0861 1680x1050 434x270mm 20.1-inch                    | 1         | 1.12%   |
| Panasonic TV MEIC301 1920x1080 698x392mm 31.5-inch                     | 1         | 1.12%   |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                   | 1         | 1.12%   |
| Medion MD 20094 MED3610 1920x1200 550x344mm 25.5-inch                  | 1         | 1.12%   |
| LG Electronics LCD Monitor MP59HT 1920x1080                            | 1         | 1.12%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch            | 1         | 1.12%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch            | 1         | 1.12%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch            | 1         | 1.12%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch            | 1         | 1.12%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch            | 1         | 1.12%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 1         | 1.12%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch            | 1         | 1.12%   |
| Lenovo LEN L171 LEN240B 1280x1024 337x270mm 17.0-inch                  | 1         | 1.12%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                   | 1         | 1.12%   |
| Lenovo H61 LEN520B 1600x900 410x230mm 18.5-inch                        | 1         | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 35        | 42.17%  |
| 1366x768 (WXGA)    | 21        | 25.3%   |
| 2560x1440 (QHD)    | 6         | 7.23%   |
| 3840x2160 (4K)     | 3         | 3.61%   |
| 2560x1600          | 3         | 3.61%   |
| 1280x1024 (SXGA)   | 3         | 3.61%   |
| 1680x1050 (WSXGA+) | 2         | 2.41%   |
| Unknown            | 2         | 2.41%   |
| 7680x2160          | 1         | 1.2%    |
| 3840x1080          | 1         | 1.2%    |
| 2160x1440          | 1         | 1.2%    |
| 1920x1200 (WUXGA)  | 1         | 1.2%    |
| 1600x900 (HD+)     | 1         | 1.2%    |
| 1440x900 (WXGA+)   | 1         | 1.2%    |
| 1280x800 (WXGA)    | 1         | 1.2%    |
| 1024x768 (XGA)     | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 28.92%  |
| Unknown | 8         | 9.64%   |
| 27      | 7         | 8.43%   |
| 21      | 5         | 6.02%   |
| 24      | 4         | 4.82%   |
| 17      | 4         | 4.82%   |
| 14      | 4         | 4.82%   |
| 13      | 4         | 4.82%   |
| 31      | 3         | 3.61%   |
| 23      | 3         | 3.61%   |
| 32      | 2         | 2.41%   |
| 25      | 2         | 2.41%   |
| 22      | 2         | 2.41%   |
| 16      | 2         | 2.41%   |
| 12      | 2         | 2.41%   |
| 86      | 1         | 1.2%    |
| 54      | 1         | 1.2%    |
| 49      | 1         | 1.2%    |
| 29      | 1         | 1.2%    |
| 19      | 1         | 1.2%    |
| 18      | 1         | 1.2%    |
| 11      | 1         | 1.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 39.76%  |
| 501-600     | 16        | 19.28%  |
| 401-500     | 8         | 9.64%   |
| Unknown     | 8         | 9.64%   |
| 201-300     | 5         | 6.02%   |
| 601-700     | 4         | 4.82%   |
| 351-400     | 4         | 4.82%   |
| 701-800     | 2         | 2.41%   |
| 1001-1500   | 2         | 2.41%   |
| 1501-2000   | 1         | 1.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 61        | 75.31%  |
| 16/10   | 8         | 9.88%   |
| Unknown | 8         | 9.88%   |
| 5/4     | 3         | 3.7%    |
| 4/3     | 1         | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 28.92%  |
| 201-250        | 12        | 14.46%  |
| Unknown        | 8         | 9.64%   |
| 81-90          | 7         | 8.43%   |
| 301-350        | 7         | 8.43%   |
| 351-500        | 6         | 7.23%   |
| More than 1000 | 3         | 3.61%   |
| 251-300        | 3         | 3.61%   |
| 141-150        | 3         | 3.61%   |
| 61-70          | 2         | 2.41%   |
| 151-200        | 2         | 2.41%   |
| 121-130        | 2         | 2.41%   |
| 111-120        | 2         | 2.41%   |
| 71-80          | 1         | 1.2%    |
| 51-60          | 1         | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 25        | 30.86%  |
| 101-120       | 23        | 28.4%   |
| 121-160       | 18        | 22.22%  |
| Unknown       | 8         | 9.88%   |
| 1-50          | 3         | 3.7%    |
| 161-240       | 3         | 3.7%    |
| More than 240 | 1         | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 74        | 86.05%  |
| 2     | 9         | 10.47%  |
| 0     | 2         | 2.33%   |
| 3     | 1         | 1.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 49        | 39.52%  |
| Intel                           | 28        | 22.58%  |
| Qualcomm Atheros                | 11        | 8.87%   |
| Broadcom                        | 10        | 8.06%   |
| TP-Link                         | 3         | 2.42%   |
| Ralink Technology               | 3         | 2.42%   |
| Ralink                          | 3         | 2.42%   |
| MediaTek                        | 3         | 2.42%   |
| Sierra Wireless                 | 2         | 1.61%   |
| Nvidia                          | 2         | 1.61%   |
| Linksys                         | 2         | 1.61%   |
| Qualcomm Atheros Communications | 1         | 0.81%   |
| Qualcomm                        | 1         | 0.81%   |
| NetGear                         | 1         | 0.81%   |
| Motorola PCS                    | 1         | 0.81%   |
| Microsoft                       | 1         | 0.81%   |
| Marvell Technology Group        | 1         | 0.81%   |
| Edimax Technology               | 1         | 0.81%   |
| D-Link                          | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 25%     |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 3.38%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 2.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 2.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 2.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 2.03%   |
| Intel Wireless 7260                                               | 3         | 2.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.03%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.35%   |
| Realtek Realtek Ethernet controller                               | 2         | 1.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.35%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.35%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.35%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.35%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.68%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.68%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.68%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.68%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.68%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.68%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.68%   |
| Realtek 802.11ac WLAN Adapter                                     | 1         | 0.68%   |
| Ralink RT5572 Wireless Adapter                                    | 1         | 0.68%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.68%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                              | 1         | 0.68%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 0.68%   |
| Qualcomm Mobile Router                                            | 1         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.68%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter        | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 29.41%  |
| Realtek Semiconductor           | 14        | 20.59%  |
| Qualcomm Atheros                | 9         | 13.24%  |
| Broadcom                        | 4         | 5.88%   |
| TP-Link                         | 3         | 4.41%   |
| Ralink Technology               | 3         | 4.41%   |
| Ralink                          | 3         | 4.41%   |
| MediaTek                        | 3         | 4.41%   |
| Sierra Wireless                 | 2         | 2.94%   |
| Linksys                         | 2         | 2.94%   |
| Qualcomm Atheros Communications | 1         | 1.47%   |
| NetGear                         | 1         | 1.47%   |
| Marvell Technology Group        | 1         | 1.47%   |
| Edimax Technology               | 1         | 1.47%   |
| D-Link                          | 1         | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 7.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 4.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 4.41%   |
| Intel Wireless 7260                                                    | 3         | 4.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 4.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2         | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 2.94%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1         | 1.47%   |
| Sierra Wireless EM7345 4G LTE                                          | 1         | 1.47%   |
| Sierra Wireless EM7305 Modem                                           | 1         | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.47%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 1         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 1.47%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 1         | 1.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1         | 1.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1         | 1.47%   |
| Realtek RTL8187 Wireless Adapter                                       | 1         | 1.47%   |
| Realtek 802.11ac WLAN Adapter                                          | 1         | 1.47%   |
| Ralink RT5572 Wireless Adapter                                         | 1         | 1.47%   |
| Ralink RT2501/RT2573 Wireless Adapter                                  | 1         | 1.47%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 1.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1         | 1.47%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                   | 1         | 1.47%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 1         | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 1.47%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter             | 1         | 1.47%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1         | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1         | 1.47%   |
| NetGear A6210                                                          | 1         | 1.47%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                      | 1         | 1.47%   |
| Linksys WUSB6300 V2                                                    | 1         | 1.47%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1         | 1.47%   |
| Intel Wireless 8265 / 8275                                             | 1         | 1.47%   |
| Intel Wireless 8260                                                    | 1         | 1.47%   |
| Intel Wireless 3165                                                    | 1         | 1.47%   |
| Intel Wireless 3160                                                    | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 43        | 54.43%  |
| Intel                 | 19        | 24.05%  |
| Broadcom              | 8         | 10.13%  |
| Qualcomm Atheros      | 4         | 5.06%   |
| Nvidia                | 2         | 2.53%   |
| Qualcomm              | 1         | 1.27%   |
| Motorola PCS          | 1         | 1.27%   |
| Microsoft             | 1         | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 46.25%  |
| Intel Ethernet Connection (2) I219-V                              | 4         | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.75%   |
| Realtek Realtek Ethernet controller                               | 2         | 2.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.5%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.5%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.5%    |
| Intel 82579V Gigabit Network Connection                           | 2         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.5%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.25%   |
| Qualcomm Mobile Router                                            | 1         | 1.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.25%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.25%   |
| Nvidia MCP55 Ethernet                                             | 1         | 1.25%   |
| Motorola PCS moto g(6) plus                                       | 1         | 1.25%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 1         | 1.25%   |
| Intel WiMAX Connection 2400m                                      | 1         | 1.25%   |
| Intel Ethernet controller                                         | 1         | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.25%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.25%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.25%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.25%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 1.25%   |
| Broadcom NetXtreme II BCM57711 10-Gigabit PCIe                    | 1         | 1.25%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.25%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 1.25%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.25%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.25%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 76        | 56.72%  |
| WiFi     | 58        | 43.28%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 52.94%  |
| Ethernet | 40        | 47.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 42        | 50.6%   |
| 1     | 38        | 45.78%  |
| 4     | 1         | 1.2%    |
| 3     | 1         | 1.2%    |
| 0     | 1         | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 72        | 84.71%  |
| Yes  | 13        | 15.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 32.61%  |
| Realtek Semiconductor           | 6         | 13.04%  |
| Cambridge Silicon Radio         | 6         | 13.04%  |
| IMC Networks                    | 4         | 8.7%    |
| Apple                           | 4         | 8.7%    |
| Broadcom                        | 3         | 6.52%   |
| Realtek                         | 2         | 4.35%   |
| Ralink                          | 1         | 2.17%   |
| Qualcomm Atheros Communications | 1         | 2.17%   |
| Marvell Semiconductor           | 1         | 2.17%   |
| Lite-On Technology              | 1         | 2.17%   |
| Hewlett-Packard                 | 1         | 2.17%   |
| Foxconn / Hon Hai               | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 17.39%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 13.04%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.52%   |
| IMC Networks Wireless_Device                        | 3         | 6.52%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 4.35%   |
| Realtek Bluetooth Radio                             | 2         | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 4.35%   |
| Realtek Bluetooth Radio                             | 1         | 2.17%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.17%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.17%   |
| Lite-On Bluetooth Device                            | 1         | 2.17%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.17%   |
| Intel AX210 Bluetooth                               | 1         | 2.17%   |
| Intel AX201 Bluetooth                               | 1         | 2.17%   |
| Intel AX200 Bluetooth                               | 1         | 2.17%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 2.17%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.17%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 2.17%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 2.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.17%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.17%   |
| Apple Bluetooth Host Controller                     | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 63        | 54.31%  |
| Nvidia              | 24        | 20.69%  |
| AMD                 | 18        | 15.52%  |
| Texas Instruments   | 2         | 1.72%   |
| Microsoft           | 2         | 1.72%   |
| Logitech            | 2         | 1.72%   |
| C-Media Electronics | 2         | 1.72%   |
| Razer USA           | 1         | 0.86%   |
| Hewlett-Packard     | 1         | 0.86%   |
| Creative Labs       | 1         | 0.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 7.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.07%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.35%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 3.62%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 3.62%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.9%    |
| Intel 200 Series PCH HD Audio                                              | 4         | 2.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 2.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 2.17%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 2.17%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.17%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.17%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 2.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.45%   |
| Nvidia Audio device                                                        | 2         | 1.45%   |
| Logitech Headset H390                                                      | 2         | 1.45%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 1.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.45%   |
| Texas Instruments PCM2902C Audio CODEC                                     | 1         | 0.72%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.72%   |
| Razer USA Nommo Chroma                                                     | 1         | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.72%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1         | 0.72%   |
| Nvidia MCP55 High Definition Audio                                         | 1         | 0.72%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.72%   |
| Microsoft Surface Pro 3 Docking Station Audio Device                       | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 16%     |
| Micron Technology   | 4         | 16%     |
| Crucial             | 4         | 16%     |
| Kingston            | 3         | 12%     |
| Unknown             | 2         | 8%      |
| SK hynix            | 2         | 8%      |
| A-DATA Technology   | 2         | 8%      |
| Nanya Technology    | 1         | 4%      |
| Hewlett-Packard     | 1         | 4%      |
| G.Skill             | 1         | 4%      |
| Corsair             | 1         | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 2         | 6.9%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 6.9%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 3.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1400MT/s               | 1         | 3.45%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s            | 1         | 3.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 3.45%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s           | 1         | 3.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 3.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 3.45%   |
| Samsung RAM M378B5273CH0-CK0 4096MB DIMM DDR3 2000MT/s     | 1         | 3.45%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1         | 3.45%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR 2048MT/s          | 1         | 3.45%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4096MB SODIMM DDR3 1600MT/s  | 1         | 3.45%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 3.45%   |
| Kingston RAM MSI24D4S7D8MH-16 16384MB SODIMM DDR4 2400MT/s | 1         | 3.45%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s        | 1         | 3.45%   |
| Kingston RAM ASU16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s     | 1         | 3.45%   |
| HP RAM 7EH65AA# 16384MB DIMM DDR4 2666MT/s                 | 1         | 3.45%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1867MT/s       | 1         | 3.45%   |
| G.Skill RAM F3-12800CL9-4GBSR 4GB DIMM DDR3 1600MT/s       | 1         | 3.45%   |
| Crucial RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 3.45%   |
| Crucial RAM CT8G4DFD8213.C16FBR2 8GB DIMM DDR4 2133MT/s    | 1         | 3.45%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s    | 1         | 3.45%   |
| Crucial RAM CT16G4SFD824A.C16FP 16GB SODIMM DDR4 2400MT/s  | 1         | 3.45%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s      | 1         | 3.45%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3000MT/s                | 1         | 3.45%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s       | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 47.62%  |
| DDR3   | 9         | 42.86%  |
| LPDDR3 | 1         | 4.76%   |
| DDR2   | 1         | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 13        | 61.9%   |
| DIMM   | 8         | 38.1%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 9         | 40.91%  |
| 8192  | 7         | 31.82%  |
| 16384 | 4         | 18.18%  |
| 2048  | 2         | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 8         | 33.33%  |
| 3200  | 3         | 12.5%   |
| 2400  | 3         | 12.5%   |
| 1867  | 2         | 8.33%   |
| 3400  | 1         | 4.17%   |
| 3000  | 1         | 4.17%   |
| 2667  | 1         | 4.17%   |
| 2666  | 1         | 4.17%   |
| 2133  | 1         | 4.17%   |
| 2048  | 1         | 4.17%   |
| 2000  | 1         | 4.17%   |
| 1400  | 1         | 4.17%   |

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
| HP Laser 107w                     | 1         | 14.29%  |
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
| Chicony Electronics                    | 9         | 17.65%  |
| IMC Networks                           | 7         | 13.73%  |
| Acer                                   | 5         | 9.8%    |
| Realtek Semiconductor                  | 4         | 7.84%   |
| Apple                                  | 4         | 7.84%   |
| Sunplus Innovation Technology          | 3         | 5.88%   |
| Logitech                               | 3         | 5.88%   |
| Microsoft                              | 2         | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.92%   |
| Z-Star Microelectronics                | 1         | 1.96%   |
| Samsung Electronics                    | 1         | 1.96%   |
| Pixart Imaging                         | 1         | 1.96%   |
| Novatek Microelectronics               | 1         | 1.96%   |
| Microdia                               | 1         | 1.96%   |
| Lite-On Technology                     | 1         | 1.96%   |
| Huawei Technologies                    | 1         | 1.96%   |
| Generalplus Technology                 | 1         | 1.96%   |
| GEMBIRD                                | 1         | 1.96%   |
| Cubeternet                             | 1         | 1.96%   |
| ARC International                      | 1         | 1.96%   |
| Alcor Micro                            | 1         | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 3         | 5.88%   |
| Acer Lenovo EasyCamera                                          | 3         | 5.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 2         | 3.92%   |
| Chicony Integrated Camera                                       | 2         | 3.92%   |
| Apple Built-in iSight                                           | 2         | 3.92%   |
| Z-Star Integrated Camera                                        | 1         | 1.96%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 1.96%   |
| Sunplus HP HD Webcam [Fixed]                                    | 1         | 1.96%   |
| Sunplus Asus Webcam                                             | 1         | 1.96%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 1.96%   |
| Realtek USB Camera                                              | 1         | 1.96%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 1.96%   |
| Realtek HP Wide Vision HD Camera                                | 1         | 1.96%   |
| Realtek HD WebCam                                               | 1         | 1.96%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                            | 1         | 1.96%   |
| Novatek T2S Webcam                                              | 1         | 1.96%   |
| Microsoft LifeCam VX-5000                                       | 1         | 1.96%   |
| Microsoft LifeCam VX-500 [1357]                                 | 1         | 1.96%   |
| Microdia Integrated Webcam                                      | 1         | 1.96%   |
| Logitech Webcam C270                                            | 1         | 1.96%   |
| Logitech Webcam C250                                            | 1         | 1.96%   |
| Logitech QuickCam Communicate MP/S5500                          | 1         | 1.96%   |
| Lite-On Integrated Camera                                       | 1         | 1.96%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 1         | 1.96%   |
| IMC Networks ov9734_azurewave_camera                            | 1         | 1.96%   |
| Huawei HiCamera                                                 | 1         | 1.96%   |
| Generalplus 808 Camera                                          | 1         | 1.96%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]               | 1         | 1.96%   |
| Cubeternet GL-UPC822 UVC WebCam                                 | 1         | 1.96%   |
| Chicony WebCam                                                  | 1         | 1.96%   |
| Chicony USB2.0 HD UVC WebCam                                    | 1         | 1.96%   |
| Chicony USB 2.0 Camera                                          | 1         | 1.96%   |
| Chicony Sony Visual Communication Camera                        | 1         | 1.96%   |
| Chicony Integrated Camera (1280x720@30)                         | 1         | 1.96%   |
| Chicony HP Wide Vision HD Camera                                | 1         | 1.96%   |
| Chicony FJ Camera                                               | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 1         | 1.96%   |
| ARC International Camera                                        | 1         | 1.96%   |
| Apple FaceTime HD Camera (Built-in)                             | 1         | 1.96%   |

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
| 0     | 63        | 73.26%  |
| 1     | 20        | 23.26%  |
| 2     | 3         | 3.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 7         | 28%     |
| Fingerprint reader    | 6         | 24%     |
| Net/wireless          | 5         | 20%     |
| Chipcard              | 3         | 12%     |
| Sound                 | 1         | 4%      |
| Net/ethernet          | 1         | 4%      |
| Multimedia controller | 1         | 4%      |
| Bluetooth             | 1         | 4%      |

