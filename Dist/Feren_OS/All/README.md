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

Total: 126

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Feren OS 20.04   | 42        | 53.16%  |
| Feren OS 18.04   | 35        | 44.3%   |
| Feren OS 2018.10 | 2         | 2.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Feren OS | 77        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.11.0-37-generic          | 7         | 7.78%   |
| 5.3.0-46-generic           | 5         | 5.56%   |
| 5.8.0-55-generic           | 4         | 4.44%   |
| 5.8.0-53-generic           | 4         | 4.44%   |
| 5.4.0-42-generic           | 4         | 4.44%   |
| 5.0.0-37-generic           | 4         | 4.44%   |
| 5.8.0-48-generic           | 3         | 3.33%   |
| 5.4.0-52-generic           | 3         | 3.33%   |
| 5.3.0-51-generic           | 3         | 3.33%   |
| 5.8.0-50-generic           | 2         | 2.22%   |
| 5.8.0-36-generic           | 2         | 2.22%   |
| 5.4.0-54-generic           | 2         | 2.22%   |
| 5.4.0-48-generic           | 2         | 2.22%   |
| 5.4.0-47-generic           | 2         | 2.22%   |
| 5.4.0-45-generic           | 2         | 2.22%   |
| 5.3.0-59-generic           | 2         | 2.22%   |
| 5.3.0-53-generic           | 2         | 2.22%   |
| 5.11.0-40-generic          | 2         | 2.22%   |
| 5.11.0-27-generic          | 2         | 2.22%   |
| 4.15.0-48-generic          | 2         | 2.22%   |
| 5.8.0-44-generic           | 1         | 1.11%   |
| 5.8.0-40-generic           | 1         | 1.11%   |
| 5.8.0-29-generic           | 1         | 1.11%   |
| 5.4.66-xanmod1             | 1         | 1.11%   |
| 5.4.0-77-generic           | 1         | 1.11%   |
| 5.4.0-74-generic           | 1         | 1.11%   |
| 5.4.0-72-generic           | 1         | 1.11%   |
| 5.4.0-58-generic           | 1         | 1.11%   |
| 5.4.0-51-generic           | 1         | 1.11%   |
| 5.4.0-37-generic           | 1         | 1.11%   |
| 5.4.0-31-generic           | 1         | 1.11%   |
| 5.3.0-42-generic           | 1         | 1.11%   |
| 5.3.0-40-generic           | 1         | 1.11%   |
| 5.3.0-28-generic           | 1         | 1.11%   |
| 5.15.6-051506-generic      | 1         | 1.11%   |
| 5.15.0-33-generic          | 1         | 1.11%   |
| 5.15.0-15.1-liquorix-amd64 | 1         | 1.11%   |
| 5.13.0-40-generic          | 1         | 1.11%   |
| 5.13.0-37-generic          | 1         | 1.11%   |
| 5.13.0-30-generic          | 1         | 1.11%   |
| 5.13.0-22-generic          | 1         | 1.11%   |
| 5.13.0-21-generic          | 1         | 1.11%   |
| 5.11.0-25-generic          | 1         | 1.11%   |
| 5.11.0-16-generic          | 1         | 1.11%   |
| 5.0.0-29-generic           | 1         | 1.11%   |
| 5.0.0-25-generic           | 1         | 1.11%   |
| 4.15.0-58-generic          | 1         | 1.11%   |
| 4.15.0-55-generic          | 1         | 1.11%   |
| 4.15.0-47-generic          | 1         | 1.11%   |
| 4.15.0-43-generic          | 1         | 1.11%   |
| 4.15.0-42-generic          | 1         | 1.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 23.46%  |
| 5.8.0   | 17        | 20.99%  |
| 5.3.0   | 14        | 17.28%  |
| 5.11.0  | 12        | 14.81%  |
| 4.15.0  | 6         | 7.41%   |
| 5.0.0   | 5         | 6.17%   |
| 5.13.0  | 4         | 4.94%   |
| 5.15.0  | 2         | 2.47%   |
| 5.4.66  | 1         | 1.23%   |
| 5.15.6  | 1         | 1.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 23.75%  |
| 5.8     | 17        | 21.25%  |
| 5.3     | 14        | 17.5%   |
| 5.11    | 12        | 15%     |
| 4.15    | 6         | 7.5%    |
| 5.0     | 5         | 6.25%   |
| 5.13    | 4         | 5%      |
| 5.15    | 3         | 3.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 77        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE        | 47        | 58.02%  |
| KDE5       | 20        | 24.69%  |
| Unknown    | 9         | 11.11%  |
| X-Cinnamon | 3         | 3.7%    |
| GNOME      | 2         | 2.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 77        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 66        | 85.71%  |
| LightDM | 7         | 9.09%   |
| TDM     | 4         | 5.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 20        | 25.32%  |
| en_GB   | 14        | 17.72%  |
| Unknown | 7         | 8.86%   |
| de_CH   | 6         | 7.59%   |
| en_AU   | 5         | 6.33%   |
| de_DE   | 5         | 6.33%   |
| en_IN   | 3         | 3.8%    |
| pt_BR   | 2         | 2.53%   |
| nl_BE   | 2         | 2.53%   |
| es_VE   | 2         | 2.53%   |
| en_CA   | 2         | 2.53%   |
| pt_PT   | 1         | 1.27%   |
| it_IT   | 1         | 1.27%   |
| fi_FI   | 1         | 1.27%   |
| es_UY   | 1         | 1.27%   |
| es_PE   | 1         | 1.27%   |
| es_MX   | 1         | 1.27%   |
| es_HN   | 1         | 1.27%   |
| es_ES   | 1         | 1.27%   |
| es_CL   | 1         | 1.27%   |
| en_IE   | 1         | 1.27%   |
| de_AT   | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 45        | 58.44%  |
| BIOS | 32        | 41.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 64        | 81.01%  |
| Btrfs   | 7         | 8.86%   |
| Unknown | 6         | 7.59%   |
| Overlay | 2         | 2.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 70        | 89.74%  |
| GPT     | 8         | 10.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 88.31%  |
| Yes       | 9         | 11.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 17        | 22.08%  |
| MSI                 | 9         | 11.69%  |
| Lenovo              | 8         | 10.39%  |
| Hewlett-Packard     | 7         | 9.09%   |
| Dell                | 7         | 9.09%   |
| Apple               | 4         | 5.19%   |
| Gigabyte Technology | 3         | 3.9%    |
| ASRock              | 3         | 3.9%    |
| Acer                | 3         | 3.9%    |
| Sony                | 2         | 2.6%    |
| Pegatron            | 2         | 2.6%    |
| ZOTAC               | 1         | 1.3%    |
| Wortmann AG         | 1         | 1.3%    |
| Toshiba             | 1         | 1.3%    |
| PCWare              | 1         | 1.3%    |
| Panasonic           | 1         | 1.3%    |
| Microsoft           | 1         | 1.3%    |
| Medion              | 1         | 1.3%    |
| HUAWEI              | 1         | 1.3%    |
| Fujitsu             | 1         | 1.3%    |
| Foxconn             | 1         | 1.3%    |
| Exo                 | 1         | 1.3%    |
| Unknown             | 1         | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ASUS ROG Zephyrus M16 GU603HE_GU603HE   | 2         | 2.6%    |
| ASUS PRIME Z370-A                       | 2         | 2.6%    |
| ASUS All Series                         | 2         | 2.6%    |
| ZOTAC ZBOX-CI527/CI547                  | 1         | 1.3%    |
| Wortmann AG TERRA_PC                    | 1         | 1.3%    |
| Toshiba Satellite T135D                 | 1         | 1.3%    |
| Sony VPCEE4J1E                          | 1         | 1.3%    |
| Sony SVF15318SNB                        | 1         | 1.3%    |
| Pegatron p7-1030                        | 1         | 1.3%    |
| Pegatron AY691AA-ABA p6367c             | 1         | 1.3%    |
| PCWare IPMH81G1                         | 1         | 1.3%    |
| Panasonic CF-J10YYBHR                   | 1         | 1.3%    |
| MSI Traveller 1591                      | 1         | 1.3%    |
| MSI MS-7C37                             | 1         | 1.3%    |
| MSI MS-7B89                             | 1         | 1.3%    |
| MSI MS-7788                             | 1         | 1.3%    |
| MSI GS66 Stealth 10SE                   | 1         | 1.3%    |
| MSI GP72 7RDX                           | 1         | 1.3%    |
| MSI GE66 Raider 11UG                    | 1         | 1.3%    |
| MSI C Series                            | 1         | 1.3%    |
| MSI 700-216                             | 1         | 1.3%    |
| Microsoft Surface Pro 3                 | 1         | 1.3%    |
| Medion H61H2-LM3                        | 1         | 1.3%    |
| Lenovo Yoga 730-15IKB 81CU              | 1         | 1.3%    |
| Lenovo XiaoXin Air 12 80UN              | 1         | 1.3%    |
| Lenovo ThinkPad X240 20AMS72901         | 1         | 1.3%    |
| Lenovo ThinkPad X230 2325AT6            | 1         | 1.3%    |
| Lenovo ThinkCentre M72z 3548B2S         | 1         | 1.3%    |
| Lenovo Legion Y7000P 81LD               | 1         | 1.3%    |
| Lenovo G550 2958                        | 1         | 1.3%    |
| Lenovo G50-45 80E3                      | 1         | 1.3%    |
| HUAWEI BOHK-WAX9X                       | 1         | 1.3%    |
| HP ProLiant DL380p Gen8                 | 1         | 1.3%    |
| HP ProBook 6560b                        | 1         | 1.3%    |
| HP Pavilion x360 Convertible 14-cd1xxx  | 1         | 1.3%    |
| HP Pavilion Gaming Laptop 15-cx0xxx     | 1         | 1.3%    |
| HP Pavilion Desktop PC 570-p0xx         | 1         | 1.3%    |
| HP EliteDesk 800 G3 DM 35W              | 1         | 1.3%    |
| HP EliteBook Folio 1040 G1              | 1         | 1.3%    |
| Gigabyte GA-78LMT-USB3 R2               | 1         | 1.3%    |
| Gigabyte F2A68HM-DS2                    | 1         | 1.3%    |
| Gigabyte EX58-UD5                       | 1         | 1.3%    |
| Fujitsu LIFEBOOK E554                   | 1         | 1.3%    |
| Foxconn Pro3500 Series                  | 1         | 1.3%    |
| Exo CloudbookE15                        | 1         | 1.3%    |
| Dell OptiPlex GX620                     | 1         | 1.3%    |
| Dell OptiPlex 780                       | 1         | 1.3%    |
| Dell OptiPlex 360                       | 1         | 1.3%    |
| Dell Latitude E5570                     | 1         | 1.3%    |
| Dell Latitude E5430 vPro                | 1         | 1.3%    |
| Dell Inspiron 3421                      | 1         | 1.3%    |
| Dell Inspiron 23 Model 5348             | 1         | 1.3%    |
| ASUS X550CA                             | 1         | 1.3%    |
| ASUS X541NA                             | 1         | 1.3%    |
| ASUS VivoBook_ASUS Laptop E210MA_E210MA | 1         | 1.3%    |
| ASUS TUF Gaming X570-PLUS               | 1         | 1.3%    |
| ASUS STRIKER II FORMULA                 | 1         | 1.3%    |
| ASUS S400CA                             | 1         | 1.3%    |
| ASUS PRIME Z270-A                       | 1         | 1.3%    |
| ASUS PRIME H410M-E                      | 1         | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUS PRIME             | 6         | 7.79%   |
| HP Pavilion            | 3         | 3.9%    |
| Dell OptiPlex          | 3         | 3.9%    |
| Lenovo ThinkPad        | 2         | 2.6%    |
| Dell Latitude          | 2         | 2.6%    |
| Dell Inspiron          | 2         | 2.6%    |
| ASUS ROG               | 2         | 2.6%    |
| ASUS All               | 2         | 2.6%    |
| ZOTAC ZBOX-CI527       | 1         | 1.3%    |
| Wortmann AG TERRA      | 1         | 1.3%    |
| Toshiba Satellite      | 1         | 1.3%    |
| Sony VPCEE4J1E         | 1         | 1.3%    |
| Sony SVF15318SNB       | 1         | 1.3%    |
| Pegatron p7-1030       | 1         | 1.3%    |
| Pegatron AY691AA-ABA   | 1         | 1.3%    |
| PCWare IPMH81G1        | 1         | 1.3%    |
| Panasonic CF-J10YYBHR  | 1         | 1.3%    |
| MSI Traveller          | 1         | 1.3%    |
| MSI MS-7C37            | 1         | 1.3%    |
| MSI MS-7B89            | 1         | 1.3%    |
| MSI MS-7788            | 1         | 1.3%    |
| MSI GS66               | 1         | 1.3%    |
| MSI GP72               | 1         | 1.3%    |
| MSI GE66               | 1         | 1.3%    |
| MSI C                  | 1         | 1.3%    |
| MSI 700-216            | 1         | 1.3%    |
| Microsoft Surface      | 1         | 1.3%    |
| Medion H61H2-LM3       | 1         | 1.3%    |
| Lenovo Yoga            | 1         | 1.3%    |
| Lenovo XiaoXin         | 1         | 1.3%    |
| Lenovo ThinkCentre     | 1         | 1.3%    |
| Lenovo Legion          | 1         | 1.3%    |
| Lenovo G550            | 1         | 1.3%    |
| Lenovo G50-45          | 1         | 1.3%    |
| HUAWEI BOHK-WAX9X      | 1         | 1.3%    |
| HP ProLiant            | 1         | 1.3%    |
| HP ProBook             | 1         | 1.3%    |
| HP EliteDesk           | 1         | 1.3%    |
| HP EliteBook           | 1         | 1.3%    |
| Gigabyte GA-78LMT-USB3 | 1         | 1.3%    |
| Gigabyte F2A68HM-DS2   | 1         | 1.3%    |
| Gigabyte EX58-UD5      | 1         | 1.3%    |
| Fujitsu LIFEBOOK       | 1         | 1.3%    |
| Foxconn Pro3500        | 1         | 1.3%    |
| Exo CloudbookE15       | 1         | 1.3%    |
| ASUS X550CA            | 1         | 1.3%    |
| ASUS X541NA            | 1         | 1.3%    |
| ASUS VivoBook          | 1         | 1.3%    |
| ASUS TUF               | 1         | 1.3%    |
| ASUS STRIKER           | 1         | 1.3%    |
| ASUS S400CA            | 1         | 1.3%    |
| ASUS P552LJ            | 1         | 1.3%    |
| ASRock Z68             | 1         | 1.3%    |
| ASRock H61M-VS         | 1         | 1.3%    |
| ASRock B75             | 1         | 1.3%    |
| Apple MacBookPro8      | 1         | 1.3%    |
| Apple iMac14           | 1         | 1.3%    |
| Apple iMac11           | 1         | 1.3%    |
| Apple iMac10           | 1         | 1.3%    |
| Acer Predator          | 1         | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2017 | 11        | 14.29%  |
| 2011 | 10        | 12.99%  |
| 2012 | 9         | 11.69%  |
| 2019 | 7         | 9.09%   |
| 2018 | 6         | 7.79%   |
| 2016 | 6         | 7.79%   |
| 2013 | 6         | 7.79%   |
| 2014 | 5         | 6.49%   |
| 2009 | 5         | 6.49%   |
| 2020 | 4         | 5.19%   |
| 2021 | 3         | 3.9%    |
| 2008 | 3         | 3.9%    |
| 2010 | 1         | 1.3%    |
| 2006 | 1         | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 34        | 44.16%  |
| Desktop     | 33        | 42.86%  |
| All in one  | 4         | 5.19%   |
| Convertible | 2         | 2.6%    |
| Mini pc     | 2         | 2.6%    |
| Tablet      | 1         | 1.3%    |
| Server      | 1         | 1.3%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 73        | 93.59%  |
| Enabled  | 5         | 6.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 77        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 19        | 23.75%  |
| 8.01-16.0   | 17        | 21.25%  |
| 16.01-24.0  | 15        | 18.75%  |
| 3.01-4.0    | 14        | 17.5%   |
| 32.01-64.0  | 8         | 10%     |
| 64.01-256.0 | 3         | 3.75%   |
| 24.01-32.0  | 2         | 2.5%    |
| 1.01-2.0    | 2         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 35        | 41.67%  |
| 2.01-3.0  | 26        | 30.95%  |
| 3.01-4.0  | 12        | 14.29%  |
| 4.01-8.0  | 8         | 9.52%   |
| 0.51-1.0  | 2         | 2.38%   |
| 8.01-16.0 | 1         | 1.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 56.25%  |
| 2      | 20        | 25%     |
| 3      | 10        | 12.5%   |
| 4      | 3         | 3.75%   |
| 5      | 1         | 1.25%   |
| 0      | 1         | 1.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 59.74%  |
| Yes       | 31        | 40.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 92.21%  |
| No        | 6         | 7.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 70.13%  |
| No        | 23        | 29.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 51.9%   |
| No        | 38        | 48.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 17        | 22.08%  |
| Switzerland | 9         | 11.69%  |
| Germany     | 7         | 9.09%   |
| Australia   | 7         | 9.09%   |
| UK          | 4         | 5.19%   |
| India       | 3         | 3.9%    |
| Venezuela   | 2         | 2.6%    |
| Turkey      | 2         | 2.6%    |
| Poland      | 2         | 2.6%    |
| Canada      | 2         | 2.6%    |
| Brazil      | 2         | 2.6%    |
| Belgium     | 2         | 2.6%    |
| Argentina   | 2         | 2.6%    |
| Uruguay     | 1         | 1.3%    |
| UAE         | 1         | 1.3%    |
| Spain       | 1         | 1.3%    |
| Portugal    | 1         | 1.3%    |
| Peru        | 1         | 1.3%    |
| Norway      | 1         | 1.3%    |
| Mexico      | 1         | 1.3%    |
| Jordan      | 1         | 1.3%    |
| Japan       | 1         | 1.3%    |
| Italy       | 1         | 1.3%    |
| Ireland     | 1         | 1.3%    |
| Honduras    | 1         | 1.3%    |
| Greece      | 1         | 1.3%    |
| Finland     | 1         | 1.3%    |
| Chile       | 1         | 1.3%    |
| Belize      | 1         | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Oberwil-Lieli  | 8         | 9.76%   |
| Melbourne      | 3         | 3.66%   |
| Winterthur     | 2         | 2.44%   |
| Richmond       | 2         | 2.44%   |
| Istanbul       | 2         | 2.44%   |
| Escondido      | 2         | 2.44%   |
| Ypsilanti      | 1         | 1.22%   |
| Tegucigalpa    | 1         | 1.22%   |
| Surat          | 1         | 1.22%   |
| Stuttgart      | 1         | 1.22%   |
| Stavanger      | 1         | 1.22%   |
| Sligo          | 1         | 1.22%   |
| Seattle        | 1         | 1.22%   |
| Schleusingen   | 1         | 1.22%   |
| Sao Jose       | 1         | 1.22%   |
| Santiago       | 1         | 1.22%   |
| Sankt Augustin | 1         | 1.22%   |
| Saitama        | 1         | 1.22%   |
| Recklinghausen | 1         | 1.22%   |
| Portland       | 1         | 1.22%   |
| Plymouth       | 1         | 1.22%   |
| Phoenix        | 1         | 1.22%   |
| Oudenaarde     | 1         | 1.22%   |
| New York       | 1         | 1.22%   |
| Naples         | 1         | 1.22%   |
| Montevideo     | 1         | 1.22%   |
| Moncton        | 1         | 1.22%   |
| Mieres         | 1         | 1.22%   |
| Maracay        | 1         | 1.22%   |
| Macaé         | 1         | 1.22%   |
| Los Angeles    | 1         | 1.22%   |
| Lineville      | 1         | 1.22%   |
| Lima           | 1         | 1.22%   |
| Lafayette      | 1         | 1.22%   |
| La Barca       | 1         | 1.22%   |
| Krakow         | 1         | 1.22%   |
| Kloten         | 1         | 1.22%   |
| Karlsruhe      | 1         | 1.22%   |
| Hyderabad      | 1         | 1.22%   |
| Hummeltal      | 1         | 1.22%   |
| Hobart         | 1         | 1.22%   |
| Hickory        | 1         | 1.22%   |
| Hämeenlinna   | 1         | 1.22%   |
| Glasgow        | 1         | 1.22%   |
| Gdynia         | 1         | 1.22%   |
| Gdansk         | 1         | 1.22%   |
| Funchal        | 1         | 1.22%   |
| Fort St. John  | 1         | 1.22%   |
| Ernakulam      | 1         | 1.22%   |
| Edinburg       | 1         | 1.22%   |
| Delmenhorst    | 1         | 1.22%   |
| Corpus Christi | 1         | 1.22%   |
| Cincinnati     | 1         | 1.22%   |
| Caracas        | 1         | 1.22%   |
| Buenos Aires   | 1         | 1.22%   |
| Brisbane       | 1         | 1.22%   |
| Bridgwater     | 1         | 1.22%   |
| Belmopan       | 1         | 1.22%   |
| Bellport       | 1         | 1.22%   |
| Bellflower     | 1         | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 19        | 28     | 16.81%  |
| Seagate                   | 16        | 23     | 14.16%  |
| Samsung Electronics       | 12        | 16     | 10.62%  |
| Intel                     | 8         | 9      | 7.08%   |
| Unknown                   | 7         | 7      | 6.19%   |
| Hitachi                   | 7         | 8      | 6.19%   |
| Toshiba                   | 6         | 8      | 5.31%   |
| SanDisk                   | 6         | 7      | 5.31%   |
| Kingston                  | 6         | 12     | 5.31%   |
| HGST                      | 4         | 4      | 3.54%   |
| Phison                    | 3         | 3      | 2.65%   |
| A-DATA Technology         | 3         | 3      | 2.65%   |
| SK hynix                  | 2         | 3      | 1.77%   |
| Realtek Semiconductor     | 2         | 2      | 1.77%   |
| PNY                       | 2         | 2      | 1.77%   |
| OCZ                       | 2         | 2      | 1.77%   |
| Crucial                   | 2         | 5      | 1.77%   |
| Verbatim                  | 1         | 1      | 0.88%   |
| Micron/Crucial Technology | 1         | 1      | 0.88%   |
| LITEONIT                  | 1         | 1      | 0.88%   |
| LITEON                    | 1         | 1      | 0.88%   |
| IBM                       | 1         | 1      | 0.88%   |
| China                     | 1         | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 128GB           | 2         | 1.65%   |
| Unknown MMC Card  32GB                | 2         | 1.65%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 1.65%   |
| Seagate ST4000LM016-1N2170 4TB        | 2         | 1.65%   |
| Samsung HD103SJ 1TB                   | 2         | 1.65%   |
| Realtek NVMe SSD Drive 512GB          | 2         | 1.65%   |
| Phison NVMe SSD Drive 1TB             | 2         | 1.65%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 1.65%   |
| Intel NVMe SSD Drive 512GB            | 2         | 1.65%   |
| Hitachi HDS721010CLA332 1TB           | 2         | 1.65%   |
| HGST HTS721010A9E630 1TB              | 2         | 1.65%   |
| WDC WDS500G1R0B-68A4Z0 500GB SSD      | 1         | 0.83%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 0.83%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 0.83%   |
| WDC WD80EFBX-68AZZN0 8TB              | 1         | 0.83%   |
| WDC WD6400AAKS-00A7B2 640GB           | 1         | 0.83%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 0.83%   |
| WDC WD5000BPKT-60PK4T0 500GB          | 1         | 0.83%   |
| WDC WD5000AAVS-00G9B1 500GB           | 1         | 0.83%   |
| WDC WD5000AAKS-65A7B2 500GB           | 1         | 0.83%   |
| WDC WD5000AAKS-00A7B2 500GB           | 1         | 0.83%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 0.83%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1         | 0.83%   |
| WDC WD2500BPVT-00JJ5T0 250GB          | 1         | 0.83%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1         | 0.83%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1         | 0.83%   |
| WDC WD10PURX-78E5EY0 1TB              | 1         | 0.83%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 0.83%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 0.83%   |
| WDC WD10EZEX-22MFCA0 1TB              | 1         | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 0.83%   |
| WDC WD10EZEX-00WN4A0 1TB              | 1         | 0.83%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1         | 0.83%   |
| WDC WD10EURX-83UY4Y0 1TB              | 1         | 0.83%   |
| Verbatim Vi550 S3 SSD 128GB           | 1         | 0.83%   |
| Unknown SB128  128GB                  | 1         | 0.83%   |
| Unknown SA04G  4GB                    | 1         | 0.83%   |
| Unknown MMC Card  128GB               | 1         | 0.83%   |
| Toshiba THNSNJ256GCST 256GB SSD       | 1         | 0.83%   |
| Toshiba THNSNC128GNSJ 128GB SSD       | 1         | 0.83%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.83%   |
| Toshiba MK3275GSX 320GB               | 1         | 0.83%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD   | 1         | 0.83%   |
| Toshiba DT01ACA100 1TB                | 1         | 0.83%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD | 1         | 0.83%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 0.83%   |
| Seagate ST500LM000-1EJ162 500GB       | 1         | 0.83%   |
| Seagate ST500DM005 HD502HJ 500GB      | 1         | 0.83%   |
| Seagate ST3500630NS 500GB             | 1         | 0.83%   |
| Seagate ST3500418AS 500GB             | 1         | 0.83%   |
| Seagate ST3320418AS 320GB             | 1         | 0.83%   |
| Seagate ST31000528AS 1TB              | 1         | 0.83%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 0.83%   |
| Seagate ST2000DM001-9YN164 2TB        | 1         | 0.83%   |
| Seagate ST2000DM001-1CH164 2TB        | 1         | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 0.83%   |
| Seagate ST1000DM010-2EP102 1TB        | 1         | 0.83%   |
| Seagate ST1000DM003-9YN162 1TB        | 1         | 0.83%   |
| Seagate Game Drive PS4 4TB            | 1         | 0.83%   |
| SanDisk SSD U100 24GB                 | 1         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 25     | 33.33%  |
| Seagate             | 16        | 22     | 31.37%  |
| Hitachi             | 7         | 8      | 13.73%  |
| HGST                | 4         | 4      | 7.84%   |
| Toshiba             | 3         | 4      | 5.88%   |
| Unknown             | 2         | 1      | 3.92%   |
| Samsung Electronics | 2         | 3      | 3.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 12     | 15%     |
| Samsung Electronics | 5         | 7      | 12.5%   |
| Intel               | 5         | 5      | 12.5%   |
| SanDisk             | 4         | 4      | 10%     |
| WDC                 | 3         | 3      | 7.5%    |
| A-DATA Technology   | 3         | 3      | 7.5%    |
| Toshiba             | 2         | 3      | 5%      |
| SK hynix            | 2         | 3      | 5%      |
| PNY                 | 2         | 2      | 5%      |
| OCZ                 | 2         | 2      | 5%      |
| Crucial             | 2         | 5      | 5%      |
| Verbatim            | 1         | 1      | 2.5%    |
| LITEONIT            | 1         | 1      | 2.5%    |
| LITEON              | 1         | 1      | 2.5%    |
| China               | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 44        | 67     | 42.72%  |
| SSD     | 36        | 53     | 34.95%  |
| NVMe    | 16        | 20     | 15.53%  |
| MMC     | 5         | 6      | 4.85%   |
| Unknown | 2         | 2      | 1.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 117    | 70.97%  |
| NVMe | 16        | 20     | 17.2%   |
| SAS  | 6         | 5      | 6.45%   |
| MMC  | 5         | 6      | 5.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 70     | 59.04%  |
| 0.51-1.0   | 25        | 36     | 30.12%  |
| 1.01-2.0   | 4         | 5      | 4.82%   |
| 3.01-4.0   | 2         | 6      | 2.41%   |
| 2.01-3.0   | 2         | 2      | 2.41%   |
| 4.01-10.0  | 1         | 1      | 1.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 21        | 25.3%   |
| 251-500        | 20        | 24.1%   |
| 1001-2000      | 14        | 16.87%  |
| 501-1000       | 12        | 14.46%  |
| More than 3000 | 4         | 4.82%   |
| 2001-3000      | 4         | 4.82%   |
| 51-100         | 4         | 4.82%   |
| 21-50          | 2         | 2.41%   |
| 1-20           | 1         | 1.2%    |
| Unknown        | 1         | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 26        | 31.33%  |
| 1-20      | 14        | 16.87%  |
| 251-500   | 13        | 15.66%  |
| 101-250   | 12        | 14.46%  |
| 51-100    | 11        | 13.25%  |
| 501-1000  | 5         | 6.02%   |
| 1001-2000 | 1         | 1.2%    |
| Unknown   | 1         | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5000AAVS-00G9B1 500GB     | 1         | 1      | 25%     |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 25%     |
| Seagate ST3500418AS 500GB       | 1         | 1      | 25%     |
| Intel SSDSC2BW240A4 240GB       | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Intel   | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 3      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 70        | 130    | 87.5%   |
| Works    | 7         | 14     | 8.75%   |
| Malfunc  | 3         | 4      | 3.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 57        | 60.64%  |
| AMD                          | 12        | 12.77%  |
| Samsung Electronics          | 9         | 9.57%   |
| Phison Electronics           | 3         | 3.19%   |
| Nvidia                       | 3         | 3.19%   |
| SanDisk                      | 2         | 2.13%   |
| Realtek Semiconductor        | 2         | 2.13%   |
| ASMedia Technology           | 2         | 2.13%   |
| Toshiba America Info Systems | 1         | 1.06%   |
| Micron/Crucial Technology    | 1         | 1.06%   |
| JMicron Technology           | 1         | 1.06%   |
| Hewlett-Packard              | 1         | 1.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 6.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 4.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 4.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 4.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 3.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 3.54%   |
| Phison E12 NVMe Controller                                                              | 3         | 2.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 2.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 2.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.77%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.77%   |
| Intel Non-Volatile memory controller                                                    | 2         | 1.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.77%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 1.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.77%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.77%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.77%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 1.77%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.88%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1         | 0.88%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.88%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.88%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1         | 0.88%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 0.88%   |
| Nvidia nForce SATA Controller                                                           | 1         | 0.88%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.88%   |
| Nvidia MCP55 SATA Controller                                                            | 1         | 0.88%   |
| Nvidia MCP55 IDE                                                                        | 1         | 0.88%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.88%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1         | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.88%   |
| Intel SSD 600P Series                                                                   | 1         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.88%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 0.88%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1         | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.88%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1         | 0.88%   |
| HP Smart Array Gen8 Controllers                                                         | 1         | 0.88%   |
| AMD RS690 PCI to PCI Bridge (PCI Express Port 2)                                        | 1         | 0.88%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 0.88%   |
| AMD FCH IDE Controller                                                                  | 1         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 57        | 59.38%  |
| NVMe | 19        | 19.79%  |
| IDE  | 13        | 13.54%  |
| RAID | 7         | 7.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 63        | 81.82%  |
| AMD    | 14        | 18.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 3.9%    |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 2.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.6%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 2.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 2.6%    |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 2.6%    |
| Intel Celeron CPU 1007U @ 1.50GHz             | 2         | 2.6%    |
| Intel Xeon CPU E5-2667 0 @ 2.90GHz            | 1         | 1.3%    |
| Intel Pentium D CPU 3.00GHz                   | 1         | 1.3%    |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.3%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 1.3%    |
| Intel Pentium CPU G630 @ 2.70GHz              | 1         | 1.3%    |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 1.3%    |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 1.3%    |
| Intel Core i7-7700T CPU @ 2.90GHz             | 1         | 1.3%    |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 1.3%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.3%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.3%    |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 1.3%    |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 1.3%    |
| Intel Core i7-3770S CPU @ 3.10GHz             | 1         | 1.3%    |
| Intel Core i7-2600K CPU @ 3.40GHz             | 1         | 1.3%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1         | 1.3%    |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.3%    |
| Intel Core i7-10700 CPU @ 2.90GHz             | 1         | 1.3%    |
| Intel Core i7 CPU 920 @ 2.67GHz               | 1         | 1.3%    |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1         | 1.3%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.3%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.3%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.3%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.3%    |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 1.3%    |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 1.3%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.3%    |
| Intel Core i5-3570K CPU @ 3.40GHz             | 1         | 1.3%    |
| Intel Core i5-3330 CPU @ 3.00GHz              | 1         | 1.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.3%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.3%    |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 1.3%    |
| Intel Core i5 CPU 760 @ 2.80GHz               | 1         | 1.3%    |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 1.3%    |
| Intel Core i3-4170 CPU @ 3.70GHz              | 1         | 1.3%    |
| Intel Core i3-3240 CPU @ 3.40GHz              | 1         | 1.3%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.3%    |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 1.3%    |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 1         | 1.3%    |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 1         | 1.3%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1         | 1.3%    |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz          | 1         | 1.3%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 1         | 1.3%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.3%    |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.3%    |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 1.3%    |
| Intel Celeron CPU G1840 @ 2.80GHz             | 1         | 1.3%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 1.3%    |
| AMD Turion Neo X2 Dual Core Processor L625    | 1         | 1.3%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.3%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1         | 1.3%    |
| AMD Ryzen 7 2700 Eight-Core Processor         | 1         | 1.3%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 23.38%  |
| Intel Core i7           | 16        | 20.78%  |
| Intel Core i3           | 7         | 9.09%   |
| Intel Celeron           | 5         | 6.49%   |
| Intel Pentium           | 4         | 5.19%   |
| Other                   | 3         | 3.9%    |
| Intel Core 2 Quad       | 3         | 3.9%    |
| AMD Ryzen 5             | 3         | 3.9%    |
| Intel Core 2 Duo        | 2         | 2.6%    |
| AMD Ryzen 7             | 2         | 2.6%    |
| AMD A8                  | 2         | 2.6%    |
| Intel Xeon              | 1         | 1.3%    |
| Intel Pentium D         | 1         | 1.3%    |
| Intel Core m3           | 1         | 1.3%    |
| Intel Celeron Dual-Core | 1         | 1.3%    |
| Intel Atom              | 1         | 1.3%    |
| AMD Turion Neo X2       | 1         | 1.3%    |
| AMD Ryzen 9             | 1         | 1.3%    |
| AMD FX                  | 1         | 1.3%    |
| AMD Athlon X2           | 1         | 1.3%    |
| AMD Athlon II           | 1         | 1.3%    |
| AMD A6                  | 1         | 1.3%    |
| AMD A10                 | 1         | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 39        | 50.65%  |
| 4      | 25        | 32.47%  |
| 8      | 7         | 9.09%   |
| 6      | 4         | 5.19%   |
| 12     | 2         | 2.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 76        | 98.7%   |
| 2      | 1         | 1.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 51        | 66.23%  |
| 1      | 26        | 33.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 71        | 92.21%  |
| Unknown        | 6         | 7.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 8         | 10.39%  |
| 0x206a7    | 8         | 10.39%  |
| 0x40651    | 5         | 6.49%   |
| 0x306c3    | 5         | 6.49%   |
| 0x1067a    | 5         | 6.49%   |
| 0x906ea    | 4         | 5.19%   |
| 0x906e9    | 4         | 5.19%   |
| 0x806d1    | 3         | 3.9%    |
| Unknown    | 3         | 3.9%    |
| 0x806ea    | 2         | 2.6%    |
| 0x706a8    | 2         | 2.6%    |
| 0x406e3    | 2         | 2.6%    |
| 0x0800820d | 2         | 2.6%    |
| 0xf62      | 1         | 1.3%    |
| 0xa0655    | 1         | 1.3%    |
| 0xa0652    | 1         | 1.3%    |
| 0x806eb    | 1         | 1.3%    |
| 0x806e9    | 1         | 1.3%    |
| 0x6fb      | 1         | 1.3%    |
| 0x506c9    | 1         | 1.3%    |
| 0x406c4    | 1         | 1.3%    |
| 0x306d4    | 1         | 1.3%    |
| 0x206d7    | 1         | 1.3%    |
| 0x20655    | 1         | 1.3%    |
| 0x106e5    | 1         | 1.3%    |
| 0x106a5    | 1         | 1.3%    |
| 0x08701021 | 1         | 1.3%    |
| 0x08108109 | 1         | 1.3%    |
| 0x0810100b | 1         | 1.3%    |
| 0x08001138 | 1         | 1.3%    |
| 0x07030105 | 1         | 1.3%    |
| 0x0600611a | 1         | 1.3%    |
| 0x06003104 | 1         | 1.3%    |
| 0x06001119 | 1         | 1.3%    |
| 0x06000852 | 1         | 1.3%    |
| 0x02000032 | 1         | 1.3%    |
| 0x010000c8 | 1         | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 12        | 15.58%  |
| SandyBridge     | 10        | 12.99%  |
| Haswell         | 10        | 12.99%  |
| IvyBridge       | 9         | 11.69%  |
| Penryn          | 5         | 6.49%   |
| Zen+            | 3         | 3.9%    |
| Icelake         | 3         | 3.9%    |
| Zen             | 2         | 2.6%    |
| Skylake         | 2         | 2.6%    |
| Piledriver      | 2         | 2.6%    |
| Nehalem         | 2         | 2.6%    |
| Goldmont plus   | 2         | 2.6%    |
| CometLake       | 2         | 2.6%    |
| Zen 2           | 1         | 1.3%    |
| Westmere        | 1         | 1.3%    |
| Steamroller     | 1         | 1.3%    |
| Silvermont      | 1         | 1.3%    |
| Puma            | 1         | 1.3%    |
| NetBurst        | 1         | 1.3%    |
| K8 Hammer       | 1         | 1.3%    |
| K8 & K10 hybrid | 1         | 1.3%    |
| K10             | 1         | 1.3%    |
| Goldmont        | 1         | 1.3%    |
| Excavator       | 1         | 1.3%    |
| Core            | 1         | 1.3%    |
| Broadwell       | 1         | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 49        | 54.44%  |
| Nvidia                     | 26        | 28.89%  |
| AMD                        | 14        | 15.56%  |
| Matrox Electronics Systems | 1         | 1.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 5.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 4.44%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 3.33%   |
| Intel HD Graphics 630                                                                    | 3         | 3.33%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 2.22%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.22%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.22%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 2.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 2.22%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 2.22%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 1.11%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.11%   |
| Nvidia MCP7A [GeForce 9400]                                                              | 1         | 1.11%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.11%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.11%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 1.11%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.11%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.11%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.11%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 1.11%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 1.11%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1         | 1.11%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 1.11%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1         | 1.11%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.11%   |
| Nvidia G92 [GeForce 8800 GT]                                                             | 1         | 1.11%   |
| Nvidia C77 [GeForce 9100M G]                                                             | 1         | 1.11%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 1.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.11%   |
| Intel HD Graphics 620                                                                    | 1         | 1.11%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.11%   |
| Intel HD Graphics 515                                                                    | 1         | 1.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.11%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.11%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.11%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 1         | 1.11%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.11%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 1         | 1.11%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.11%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 1         | 1.11%   |
| AMD Richland [Radeon HD 8670D]                                                           | 1         | 1.11%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.11%   |
| AMD Navi 14 [Radeon Pro W5500]                                                           | 1         | 1.11%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.11%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1         | 1.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.11%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 46.75%  |
| 1 x Nvidia     | 15        | 19.48%  |
| 1 x AMD        | 13        | 16.88%  |
| Intel + Nvidia | 11        | 14.29%  |
| 1 x Matrox     | 1         | 1.3%    |
| Intel + AMD    | 1         | 1.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 61        | 77.22%  |
| Proprietary | 16        | 20.25%  |
| Unknown     | 2         | 2.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 51.9%   |
| 1.01-2.0   | 10        | 12.66%  |
| 0.51-1.0   | 9         | 11.39%  |
| 3.01-4.0   | 6         | 7.59%   |
| 0.01-0.5   | 6         | 7.59%   |
| 7.01-8.0   | 5         | 6.33%   |
| 5.01-6.0   | 2         | 2.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 10        | 12.82%  |
| Samsung Electronics     | 8         | 10.26%  |
| AU Optronics            | 8         | 10.26%  |
| BOE                     | 7         | 8.97%   |
| Acer                    | 7         | 8.97%   |
| Dell                    | 4         | 5.13%   |
| Apple                   | 4         | 5.13%   |
| Lenovo                  | 3         | 3.85%   |
| Hewlett-Packard         | 3         | 3.85%   |
| Chimei Innolux          | 3         | 3.85%   |
| Sharp                   | 2         | 2.56%   |
| Philips                 | 2         | 2.56%   |
| Chi Mei Optoelectronics | 2         | 2.56%   |
| AOC                     | 2         | 2.56%   |
| Vestel                  | 1         | 1.28%   |
| Unknown                 | 1         | 1.28%   |
| Toshiba                 | 1         | 1.28%   |
| Sony                    | 1         | 1.28%   |
| Sceptre Tech            | 1         | 1.28%   |
| Panasonic               | 1         | 1.28%   |
| Onkyo                   | 1         | 1.28%   |
| Medion                  | 1         | 1.28%   |
| LG Electronics          | 1         | 1.28%   |
| Lenovo Group Limited    | 1         | 1.28%   |
| Insignia                | 1         | 1.28%   |
| Goldstar                | 1         | 1.28%   |
| Ancor Communications    | 1         | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch           | 2         | 2.41%   |
| Vestel LCD Monitor 32W_LCD_TV 1920x1080                                  | 1         | 1.2%    |
| Unknown LCD Monitor SAMSUNG                                              | 1         | 1.2%    |
| Toshiba LCD Monitor LCD0905 1366x768 295x166mm 13.3-inch                 | 1         | 1.2%    |
| Sony AVAMP SNYF400 1920x1080 700x390mm 31.5-inch                         | 1         | 1.2%    |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch                  | 1         | 1.2%    |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 1.2%    |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                   | 1         | 1.2%    |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch        | 1         | 1.2%    |
| Samsung Electronics LCD Monitor U28E590 7680x2160                        | 1         | 1.2%    |
| Samsung Electronics LCD Monitor U28E590                                  | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch    | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch     | 1         | 1.2%    |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch   | 1         | 1.2%    |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1         | 1.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.2%    |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch        | 1         | 1.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 1         | 1.2%    |
| Philips PHL 328E9Q PHLC180 1920x1080 698x393mm 31.5-inch                 | 1         | 1.2%    |
| Philips 220EW PHL0861 1680x1050 434x270mm 20.1-inch                      | 1         | 1.2%    |
| Panasonic TV MEIC301 1920x1080 698x392mm 31.5-inch                       | 1         | 1.2%    |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                     | 1         | 1.2%    |
| Medion MD 20094 MED3610 1920x1200 550x344mm 25.5-inch                    | 1         | 1.2%    |
| LG Electronics LCD Monitor MP59HT 1920x1080                              | 1         | 1.2%    |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch             | 1         | 1.2%    |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 1.2%    |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 1         | 1.2%    |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch             | 1         | 1.2%    |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 1         | 1.2%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 1.2%    |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch              | 1         | 1.2%    |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 1         | 1.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 1.2%    |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 1.2%    |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                    | 1         | 1.2%    |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                     | 1         | 1.2%    |
| Lenovo H61 LEN520B 1600x900 410x230mm 18.5-inch                          | 1         | 1.2%    |
| Lenovo Group Limited LCD Monitor L24q-10 2560x1440                       | 1         | 1.2%    |
| Insignia NS-24EM51A14 BBYBB24 1920x1080 531x299mm 24.0-inch              | 1         | 1.2%    |
| Hewlett-Packard ZR22w HWP2867 1920x1080 475x267mm 21.5-inch              | 1         | 1.2%    |
| Hewlett-Packard LCD Monitor ZR22w 3840x1080                              | 1         | 1.2%    |
| Hewlett-Packard LA2306 HWP2949 1920x1080 509x286mm 23.0-inch             | 1         | 1.2%    |
| Hewlett-Packard 2509 HWP283A 1920x1080 553x311mm 25.0-inch               | 1         | 1.2%    |
| Goldstar E2242 GSM58BE 1920x1080 480x270mm 21.7-inch                     | 1         | 1.2%    |
| Dell UP3017 DEL40FA 2560x1600 641x401mm 29.8-inch                        | 1         | 1.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 1         | 1.2%    |
| Dell SP1908FP DEL4030 1280x1024 376x301mm 19.0-inch                      | 1         | 1.2%    |
| Dell Inspiron 5348 DEL93E8 1920x1080 510x287mm 23.0-inch                 | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 1.2%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO1557 1366x768 344x193mm 15.5-inch | 1         | 1.2%    |
| Chi Mei Optoelectronics LCD Monitor CMC 19AW 1440x900                    | 1         | 1.2%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 1         | 1.2%    |
| BOE LCD Monitor BOE0854 1920x1080 344x194mm 15.5-inch                    | 1         | 1.2%    |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                    | 1         | 1.2%    |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 1         | 1.2%    |
| BOE LCD Monitor BOE06F4 3840x2160 345x194mm 15.6-inch                    | 1         | 1.2%    |
| BOE LCD Monitor BOE06A6 1366x768 309x174mm 14.0-inch                     | 1         | 1.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 38.96%  |
| 1366x768 (WXGA)    | 21        | 27.27%  |
| 2560x1440 (QHD)    | 5         | 6.49%   |
| 3840x2160 (4K)     | 3         | 3.9%    |
| 2560x1600          | 3         | 3.9%    |
| 1280x1024 (SXGA)   | 3         | 3.9%    |
| 1680x1050 (WSXGA+) | 2         | 2.6%    |
| Unknown            | 2         | 2.6%    |
| 7680x2160          | 1         | 1.3%    |
| 3840x1080          | 1         | 1.3%    |
| 2160x1440          | 1         | 1.3%    |
| 1920x1200 (WUXGA)  | 1         | 1.3%    |
| 1600x900 (HD+)     | 1         | 1.3%    |
| 1440x900 (WXGA+)   | 1         | 1.3%    |
| 1280x800 (WXGA)    | 1         | 1.3%    |
| 1024x768 (XGA)     | 1         | 1.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 29.87%  |
| Unknown | 8         | 10.39%  |
| 27      | 6         | 7.79%   |
| 21      | 5         | 6.49%   |
| 24      | 4         | 5.19%   |
| 14      | 4         | 5.19%   |
| 31      | 3         | 3.9%    |
| 23      | 3         | 3.9%    |
| 17      | 3         | 3.9%    |
| 13      | 3         | 3.9%    |
| 25      | 2         | 2.6%    |
| 22      | 2         | 2.6%    |
| 16      | 2         | 2.6%    |
| 12      | 2         | 2.6%    |
| 54      | 1         | 1.3%    |
| 49      | 1         | 1.3%    |
| 32      | 1         | 1.3%    |
| 29      | 1         | 1.3%    |
| 19      | 1         | 1.3%    |
| 18      | 1         | 1.3%    |
| 11      | 1         | 1.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 40.26%  |
| 501-600     | 15        | 19.48%  |
| 401-500     | 8         | 10.39%  |
| Unknown     | 8         | 10.39%  |
| 201-300     | 5         | 6.49%   |
| 601-700     | 4         | 5.19%   |
| 351-400     | 3         | 3.9%    |
| 1001-1500   | 2         | 2.6%    |
| 701-800     | 1         | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 55        | 73.33%  |
| 16/10   | 8         | 10.67%  |
| Unknown | 8         | 10.67%  |
| 5/4     | 3         | 4%      |
| 4/3     | 1         | 1.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 29.87%  |
| 201-250        | 12        | 15.58%  |
| Unknown        | 8         | 10.39%  |
| 81-90          | 6         | 7.79%   |
| 301-350        | 6         | 7.79%   |
| 351-500        | 5         | 6.49%   |
| 251-300        | 3         | 3.9%    |
| 141-150        | 3         | 3.9%    |
| More than 1000 | 2         | 2.6%    |
| 61-70          | 2         | 2.6%    |
| 151-200        | 2         | 2.6%    |
| 111-120        | 2         | 2.6%    |
| 71-80          | 1         | 1.3%    |
| 51-60          | 1         | 1.3%    |
| 121-130        | 1         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 23        | 30.67%  |
| 51-100        | 23        | 30.67%  |
| 121-160       | 15        | 20%     |
| Unknown       | 8         | 10.67%  |
| 161-240       | 3         | 4%      |
| 1-50          | 2         | 2.67%   |
| More than 240 | 1         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 68        | 85%     |
| 2     | 9         | 11.25%  |
| 0     | 2         | 2.5%    |
| 3     | 1         | 1.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 46        | 40.71%  |
| Intel                           | 24        | 21.24%  |
| Qualcomm Atheros                | 10        | 8.85%   |
| Broadcom                        | 10        | 8.85%   |
| Ralink Technology               | 3         | 2.65%   |
| Ralink                          | 3         | 2.65%   |
| TP-Link                         | 2         | 1.77%   |
| Sierra Wireless                 | 2         | 1.77%   |
| Nvidia                          | 2         | 1.77%   |
| MediaTek                        | 2         | 1.77%   |
| Linksys                         | 2         | 1.77%   |
| Qualcomm Atheros Communications | 1         | 0.88%   |
| Qualcomm                        | 1         | 0.88%   |
| NetGear                         | 1         | 0.88%   |
| Microsoft                       | 1         | 0.88%   |
| Marvell Technology Group        | 1         | 0.88%   |
| Edimax Technology               | 1         | 0.88%   |
| D-Link                          | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 34        | 24.82%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 2.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3         | 2.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 3         | 2.19%   |
| Intel Wireless 7260                                                                           | 3         | 2.19%   |
| Intel Ethernet Connection (2) I219-V                                                          | 3         | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 2.19%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2         | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.46%   |
| Realtek Realtek Ethernet controller                                                           | 2         | 1.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 2         | 1.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 2         | 1.46%   |
| Intel Ethernet Connection I219-LM                                                             | 2         | 1.46%   |
| Intel Ethernet Connection I218-LM                                                             | 2         | 1.46%   |
| Intel 82579V Gigabit Network Connection                                                       | 2         | 1.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2         | 1.46%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 1.46%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 0.73%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.73%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 0.73%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1         | 0.73%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 0.73%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1         | 0.73%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.73%   |
| Realtek Killer E3000 2.5GbE Controller                                                        | 1         | 0.73%   |
| Ralink RT5572 Wireless Adapter                                                                | 1         | 0.73%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1         | 0.73%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.73%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1         | 0.73%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 0.73%   |
| Qualcomm Redmi 9T                                                                             | 1         | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 0.73%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 0.73%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 0.73%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 0.73%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1         | 0.73%   |
| Nvidia MCP79 Ethernet                                                                         | 1         | 0.73%   |
| Nvidia MCP55 Ethernet                                                                         | 1         | 0.73%   |
| NetGear A6210                                                                                 | 1         | 0.73%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                                             | 1         | 0.73%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                             | 1         | 0.73%   |
| Linksys WUSB6300 V2                                                                           | 1         | 0.73%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                        | 1         | 0.73%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 0.73%   |
| Intel Wireless 8260                                                                           | 1         | 0.73%   |
| Intel Wireless 3165                                                                           | 1         | 0.73%   |
| Intel Wireless 3160                                                                           | 1         | 0.73%   |
| Intel WiMAX Connection 2400m                                                                  | 1         | 0.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 0.73%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 0.73%   |
| Intel Ethernet controller                                                                     | 1         | 0.73%   |
| Intel Ethernet Connection I217-LM                                                             | 1         | 0.73%   |
| Intel Ethernet Connection (7) I219-V                                                          | 1         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 28.57%  |
| Realtek Semiconductor           | 14        | 22.22%  |
| Qualcomm Atheros                | 8         | 12.7%   |
| Broadcom                        | 4         | 6.35%   |
| Ralink Technology               | 3         | 4.76%   |
| Ralink                          | 3         | 4.76%   |
| TP-Link                         | 2         | 3.17%   |
| Sierra Wireless                 | 2         | 3.17%   |
| MediaTek                        | 2         | 3.17%   |
| Linksys                         | 2         | 3.17%   |
| Qualcomm Atheros Communications | 1         | 1.59%   |
| NetGear                         | 1         | 1.59%   |
| Marvell Technology Group        | 1         | 1.59%   |
| Edimax Technology               | 1         | 1.59%   |
| D-Link                          | 1         | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 6.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3         | 4.76%   |
| Intel Wireless 7260                                                                           | 3         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 4.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2         | 3.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 3.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 2         | 3.17%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 3.17%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 1.59%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.59%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 1.59%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1         | 1.59%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 1.59%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1         | 1.59%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.59%   |
| Ralink RT5572 Wireless Adapter                                                                | 1         | 1.59%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1         | 1.59%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.59%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1         | 1.59%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.59%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 1.59%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 1.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.59%   |
| NetGear A6210                                                                                 | 1         | 1.59%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                             | 1         | 1.59%   |
| Linksys WUSB6300 V2                                                                           | 1         | 1.59%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                        | 1         | 1.59%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.59%   |
| Intel Wireless 8260                                                                           | 1         | 1.59%   |
| Intel Wireless 3165                                                                           | 1         | 1.59%   |
| Intel Wireless 3160                                                                           | 1         | 1.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 1.59%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 1.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 1.59%   |
| Intel Centrino Wireless-N 2230                                                                | 1         | 1.59%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                                          | 1         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.59%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                                      | 1         | 1.59%   |
| D-Link DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.B2) [Ralink RT5572]                  | 1         | 1.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1         | 1.59%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 1         | 1.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 40        | 54.79%  |
| Intel                 | 17        | 23.29%  |
| Broadcom              | 8         | 10.96%  |
| Qualcomm Atheros      | 4         | 5.48%   |
| Nvidia                | 2         | 2.74%   |
| Qualcomm              | 1         | 1.37%   |
| Microsoft             | 1         | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 45.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 4.05%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 4.05%   |
| Realtek Realtek Ethernet controller                               | 2         | 2.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.7%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.7%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.7%    |
| Intel 82579V Gigabit Network Connection                           | 2         | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.7%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.35%   |
| Qualcomm Redmi 9T                                                 | 1         | 1.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.35%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.35%   |
| Nvidia MCP55 Ethernet                                             | 1         | 1.35%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 1         | 1.35%   |
| Intel WiMAX Connection 2400m                                      | 1         | 1.35%   |
| Intel Ethernet controller                                         | 1         | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.35%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.35%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.35%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.35%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 1.35%   |
| Broadcom NetXtreme II BCM57711 10-Gigabit PCIe                    | 1         | 1.35%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.35%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.35%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 1.35%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.35%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 71        | 56.8%   |
| WiFi     | 54        | 43.2%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 55.13%  |
| Ethernet | 35        | 44.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 39        | 50.65%  |
| 1     | 35        | 45.45%  |
| 4     | 1         | 1.3%    |
| 3     | 1         | 1.3%    |
| 0     | 1         | 1.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 66        | 84.62%  |
| Yes  | 12        | 15.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 30.95%  |
| Realtek Semiconductor           | 6         | 14.29%  |
| Cambridge Silicon Radio         | 6         | 14.29%  |
| Apple                           | 4         | 9.52%   |
| Broadcom                        | 3         | 7.14%   |
| Realtek                         | 2         | 4.76%   |
| IMC Networks                    | 2         | 4.76%   |
| Ralink                          | 1         | 2.38%   |
| Qualcomm Atheros Communications | 1         | 2.38%   |
| Marvell Semiconductor           | 1         | 2.38%   |
| Lite-On Technology              | 1         | 2.38%   |
| Hewlett-Packard                 | 1         | 2.38%   |
| Foxconn / Hon Hai               | 1         | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 19.05%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 14.29%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 7.14%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 4.76%   |
| Realtek Bluetooth Radio                             | 2         | 4.76%   |
| IMC Networks Wireless_Device                        | 2         | 4.76%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 4.76%   |
| Realtek Bluetooth Radio                             | 1         | 2.38%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.38%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.38%   |
| Lite-On Bluetooth Device                            | 1         | 2.38%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.38%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.38%   |
| Intel Bluetooth Device                              | 1         | 2.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.38%   |
| Intel AX210 Bluetooth                               | 1         | 2.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.38%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 2.38%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 2.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.38%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.38%   |
| Apple Bluetooth Host Controller                     | 1         | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 59        | 55.66%  |
| Nvidia              | 22        | 20.75%  |
| AMD                 | 16        | 15.09%  |
| Logitech            | 2         | 1.89%   |
| C-Media Electronics | 2         | 1.89%   |
| Texas Instruments   | 1         | 0.94%   |
| Razer USA           | 1         | 0.94%   |
| Microsoft           | 1         | 0.94%   |
| Hewlett-Packard     | 1         | 0.94%   |
| Creative Labs       | 1         | 0.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 8.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.6%    |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 4%      |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 4%      |
| Intel 8 Series HD Audio Controller                                         | 5         | 4%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 3.2%    |
| Intel 200 Series PCH HD Audio                                              | 4         | 3.2%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 2.4%    |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.4%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 2.4%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.4%    |
| AMD FCH Azalia Controller                                                  | 3         | 2.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 2.4%    |
| Nvidia Audio device                                                        | 2         | 1.6%    |
| Logitech Headset H390                                                      | 2         | 1.6%    |
| Intel CM238 HD Audio Controller                                            | 2         | 1.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.6%    |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.6%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 1.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 1.6%    |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.8%    |
| Razer USA Nommo Chroma                                                     | 1         | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.8%    |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.8%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1         | 0.8%    |
| Nvidia MCP55 High Definition Audio                                         | 1         | 0.8%    |
| Nvidia High Definition Audio Controller                                    | 1         | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.8%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.8%    |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.8%    |
| Microsoft Surface Pro 3 Docking Station Audio Device                       | 1         | 0.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.8%    |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 0.8%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.8%    |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 0.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.8%    |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1         | 0.8%    |
| Hewlett-Packard Speaker Bar                                                | 1         | 0.8%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1         | 0.8%    |
| C-Media Electronics SKP PODCAST-300U                                       | 1         | 0.8%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1         | 0.8%    |
| C-Media Electronics Audio Adapter                                          | 1         | 0.8%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1         | 0.8%    |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 0.8%    |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 0.8%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 0.8%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1         | 0.8%    |
| AMD Navi 10 HDMI Audio                                                     | 1         | 0.8%    |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 0.8%    |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 4         | 19.05%  |
| Crucial             | 4         | 19.05%  |
| Samsung Electronics | 3         | 14.29%  |
| Unknown             | 2         | 9.52%   |
| SK hynix            | 2         | 9.52%   |
| Kingston            | 2         | 9.52%   |
| A-DATA Technology   | 2         | 9.52%   |
| Nanya Technology    | 1         | 4.76%   |
| Hewlett-Packard     | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 2         | 8.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 8.33%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 4.17%   |
| Unknown RAM Module 4096MB DIMM DDR3 1400MT/s               | 1         | 4.17%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s            | 1         | 4.17%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 1         | 4.17%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s           | 1         | 4.17%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 4.17%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s        | 1         | 4.17%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1         | 4.17%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR 2048MT/s          | 1         | 4.17%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4096MB SODIMM DDR3 1600MT/s  | 1         | 4.17%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s   | 1         | 4.17%   |
| Kingston RAM MSI24D4S7D8MH-16 16384MB SODIMM DDR4 2400MT/s | 1         | 4.17%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s        | 1         | 4.17%   |
| HP RAM 7EH65AA# 16384MB DIMM DDR4 2666MT/s                 | 1         | 4.17%   |
| Crucial RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 4.17%   |
| Crucial RAM CT8G4DFD8213.C16FBR2 8GB DIMM DDR4 2133MT/s    | 1         | 4.17%   |
| Crucial RAM CT51264BF160BJ.C8F 4096MB SODIMM DDR3 1600MT/s | 1         | 4.17%   |
| Crucial RAM CT16G4SFD824A.C16FP 16GB SODIMM DDR4 2400MT/s  | 1         | 4.17%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3000MT/s                | 1         | 4.17%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s       | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 8         | 47.06%  |
| DDR3   | 7         | 41.18%  |
| LPDDR3 | 1         | 5.88%   |
| DDR2   | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 11        | 64.71%  |
| DIMM   | 6         | 35.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 7         | 38.89%  |
| 8192  | 5         | 27.78%  |
| 16384 | 4         | 22.22%  |
| 2048  | 2         | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 6         | 31.58%  |
| 2400  | 3         | 15.79%  |
| 3200  | 2         | 10.53%  |
| 3000  | 1         | 5.26%   |
| 2667  | 1         | 5.26%   |
| 2666  | 1         | 5.26%   |
| 2133  | 1         | 5.26%   |
| 2048  | 1         | 5.26%   |
| 2000  | 1         | 5.26%   |
| 1867  | 1         | 5.26%   |
| 1400  | 1         | 5.26%   |

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
| Chicony Electronics                    | 9         | 18.75%  |
| IMC Networks                           | 5         | 10.42%  |
| Acer                                   | 5         | 10.42%  |
| Apple                                  | 4         | 8.33%   |
| Sunplus Innovation Technology          | 3         | 6.25%   |
| Realtek Semiconductor                  | 3         | 6.25%   |
| Logitech                               | 3         | 6.25%   |
| Microsoft                              | 2         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.17%   |
| Z-Star Microelectronics                | 1         | 2.08%   |
| Samsung Electronics                    | 1         | 2.08%   |
| Pixart Imaging                         | 1         | 2.08%   |
| Novatek Microelectronics               | 1         | 2.08%   |
| Microdia                               | 1         | 2.08%   |
| Lite-On Technology                     | 1         | 2.08%   |
| Huawei Technologies                    | 1         | 2.08%   |
| Generalplus Technology                 | 1         | 2.08%   |
| GEMBIRD                                | 1         | 2.08%   |
| Cubeternet                             | 1         | 2.08%   |
| ARC International                      | 1         | 2.08%   |
| Alcor Micro                            | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Acer Lenovo EasyCamera                                                     | 3         | 6.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 4.17%   |
| Chicony Integrated Camera                                                  | 2         | 4.17%   |
| Apple Built-in iSight                                                      | 2         | 4.17%   |
| Z-Star Integrated Camera                                                   | 1         | 2.08%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.08%   |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 2.08%   |
| Sunplus Asus Webcam                                                        | 1         | 2.08%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 1         | 2.08%   |
| Realtek USB Camera                                                         | 1         | 2.08%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.08%   |
| Realtek HD WebCam                                                          | 1         | 2.08%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                                       | 1         | 2.08%   |
| Novatek J1455                                                              | 1         | 2.08%   |
| Microsoft LifeCam VX-5000                                                  | 1         | 2.08%   |
| Microsoft LifeCam VX-500 [1357]                                            | 1         | 2.08%   |
| Microdia Integrated Webcam                                                 | 1         | 2.08%   |
| Logitech Webcam C270                                                       | 1         | 2.08%   |
| Logitech Webcam C250                                                       | 1         | 2.08%   |
| Logitech QuickCam Communicate MP/S5500                                     | 1         | 2.08%   |
| Lite-On Integrated Camera                                                  | 1         | 2.08%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 2.08%   |
| Huawei UVC Camera                                                          | 1         | 2.08%   |
| Generalplus 808 Camera                                                     | 1         | 2.08%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                          | 1         | 2.08%   |
| Cubeternet GL-UPC822 UVC WebCam                                            | 1         | 2.08%   |
| Chicony WebCam                                                             | 1         | 2.08%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 2.08%   |
| Chicony USB 2.0 Camera                                                     | 1         | 2.08%   |
| Chicony Sony Visual Communication Camera                                   | 1         | 2.08%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 2.08%   |
| Chicony HP Wide Vision HD Camera                                           | 1         | 2.08%   |
| Chicony FJ Camera                                                          | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 1         | 2.08%   |
| ARC International Camera                                                   | 1         | 2.08%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 2.08%   |
| Apple FaceTime HD Camera                                                   | 1         | 2.08%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 2.08%   |
| Acer Integrated Camera                                                     | 1         | 2.08%   |
| Acer HD Camera                                                             | 1         | 2.08%   |

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
| 0     | 58        | 72.5%   |
| 1     | 19        | 23.75%  |
| 2     | 3         | 3.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 7         | 29.17%  |
| Fingerprint reader    | 6         | 25%     |
| Net/wireless          | 4         | 16.67%  |
| Chipcard              | 3         | 12.5%   |
| Sound                 | 1         | 4.17%   |
| Net/ethernet          | 1         | 4.17%   |
| Multimedia controller | 1         | 4.17%   |
| Bluetooth             | 1         | 4.17%   |

