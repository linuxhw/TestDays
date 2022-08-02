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

Total: 130

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek    | VivoBook_ASUSLaptop M350... | Notebook    | [b2b969b0e3](https://linux-hardware.org/?probe=b2b969b0e3) | Aug 01, 2022 |
| HP         | Pavilion Laptop 14-bf0xx    | Notebook    | [54c42c649d](https://linux-hardware.org/?probe=54c42c649d) | Jul 24, 2022 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Feren OS 20.04   | 45        | 54.88%  |
| Feren OS 18.04   | 35        | 42.68%  |
| Feren OS 2018.10 | 2         | 2.44%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Feren OS | 80        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.11.0-37-generic          | 7         | 7.53%   |
| 5.3.0-46-generic           | 5         | 5.38%   |
| 5.8.0-55-generic           | 4         | 4.3%    |
| 5.8.0-53-generic           | 4         | 4.3%    |
| 5.4.0-42-generic           | 4         | 4.3%    |
| 5.0.0-37-generic           | 4         | 4.3%    |
| 5.8.0-48-generic           | 3         | 3.23%   |
| 5.4.0-52-generic           | 3         | 3.23%   |
| 5.3.0-51-generic           | 3         | 3.23%   |
| 5.8.0-50-generic           | 2         | 2.15%   |
| 5.8.0-36-generic           | 2         | 2.15%   |
| 5.4.0-54-generic           | 2         | 2.15%   |
| 5.4.0-48-generic           | 2         | 2.15%   |
| 5.4.0-47-generic           | 2         | 2.15%   |
| 5.4.0-45-generic           | 2         | 2.15%   |
| 5.3.0-59-generic           | 2         | 2.15%   |
| 5.3.0-53-generic           | 2         | 2.15%   |
| 5.11.0-40-generic          | 2         | 2.15%   |
| 5.11.0-27-generic          | 2         | 2.15%   |
| 4.15.0-48-generic          | 2         | 2.15%   |
| 5.8.0-44-generic           | 1         | 1.08%   |
| 5.8.0-40-generic           | 1         | 1.08%   |
| 5.8.0-29-generic           | 1         | 1.08%   |
| 5.4.66-xanmod1             | 1         | 1.08%   |
| 5.4.0-77-generic           | 1         | 1.08%   |
| 5.4.0-74-generic           | 1         | 1.08%   |
| 5.4.0-72-generic           | 1         | 1.08%   |
| 5.4.0-58-generic           | 1         | 1.08%   |
| 5.4.0-51-generic           | 1         | 1.08%   |
| 5.4.0-37-generic           | 1         | 1.08%   |
| 5.4.0-31-generic           | 1         | 1.08%   |
| 5.3.0-42-generic           | 1         | 1.08%   |
| 5.3.0-40-generic           | 1         | 1.08%   |
| 5.3.0-28-generic           | 1         | 1.08%   |
| 5.17.5-76051705-generic    | 1         | 1.08%   |
| 5.15.6-051506-generic      | 1         | 1.08%   |
| 5.15.0-41-generic          | 1         | 1.08%   |
| 5.15.0-33-generic          | 1         | 1.08%   |
| 5.15.0-15.1-liquorix-amd64 | 1         | 1.08%   |
| 5.13.0-52-generic          | 1         | 1.08%   |
| 5.13.0-40-generic          | 1         | 1.08%   |
| 5.13.0-37-generic          | 1         | 1.08%   |
| 5.13.0-30-generic          | 1         | 1.08%   |
| 5.13.0-22-generic          | 1         | 1.08%   |
| 5.13.0-21-generic          | 1         | 1.08%   |
| 5.11.0-25-generic          | 1         | 1.08%   |
| 5.11.0-16-generic          | 1         | 1.08%   |
| 5.0.0-29-generic           | 1         | 1.08%   |
| 5.0.0-25-generic           | 1         | 1.08%   |
| 4.15.0-58-generic          | 1         | 1.08%   |
| 4.15.0-55-generic          | 1         | 1.08%   |
| 4.15.0-47-generic          | 1         | 1.08%   |
| 4.15.0-43-generic          | 1         | 1.08%   |
| 4.15.0-42-generic          | 1         | 1.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 22.62%  |
| 5.8.0   | 17        | 20.24%  |
| 5.3.0   | 14        | 16.67%  |
| 5.11.0  | 12        | 14.29%  |
| 4.15.0  | 6         | 7.14%   |
| 5.13.0  | 5         | 5.95%   |
| 5.0.0   | 5         | 5.95%   |
| 5.15.0  | 3         | 3.57%   |
| 5.4.66  | 1         | 1.19%   |
| 5.17.5  | 1         | 1.19%   |
| 5.15.6  | 1         | 1.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 22.89%  |
| 5.8     | 17        | 20.48%  |
| 5.3     | 14        | 16.87%  |
| 5.11    | 12        | 14.46%  |
| 4.15    | 6         | 7.23%   |
| 5.13    | 5         | 6.02%   |
| 5.0     | 5         | 6.02%   |
| 5.15    | 4         | 4.82%   |
| 5.17    | 1         | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 80        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE        | 47        | 55.95%  |
| KDE5       | 23        | 27.38%  |
| Unknown    | 9         | 10.71%  |
| X-Cinnamon | 3         | 3.57%   |
| GNOME      | 2         | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 80        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 67        | 83.75%  |
| LightDM | 9         | 11.25%  |
| TDM     | 4         | 5%      |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 21        | 25.61%  |
| en_GB   | 16        | 19.51%  |
| Unknown | 7         | 8.54%   |
| de_CH   | 6         | 7.32%   |
| en_AU   | 5         | 6.1%    |
| de_DE   | 5         | 6.1%    |
| en_IN   | 3         | 3.66%   |
| pt_BR   | 2         | 2.44%   |
| nl_BE   | 2         | 2.44%   |
| es_VE   | 2         | 2.44%   |
| en_CA   | 2         | 2.44%   |
| pt_PT   | 1         | 1.22%   |
| it_IT   | 1         | 1.22%   |
| fi_FI   | 1         | 1.22%   |
| es_UY   | 1         | 1.22%   |
| es_PE   | 1         | 1.22%   |
| es_MX   | 1         | 1.22%   |
| es_HN   | 1         | 1.22%   |
| es_ES   | 1         | 1.22%   |
| es_CL   | 1         | 1.22%   |
| en_IE   | 1         | 1.22%   |
| de_AT   | 1         | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 46        | 57.5%   |
| BIOS | 34        | 42.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 67        | 81.71%  |
| Btrfs   | 7         | 8.54%   |
| Unknown | 6         | 7.32%   |
| Overlay | 2         | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 71        | 87.65%  |
| GPT     | 9         | 11.11%  |
| MBR     | 1         | 1.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 88.75%  |
| Yes       | 9         | 11.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 18        | 22.5%   |
| MSI                 | 9         | 11.25%  |
| Lenovo              | 8         | 10%     |
| Hewlett-Packard     | 8         | 10%     |
| Dell                | 7         | 8.75%   |
| Gigabyte Technology | 4         | 5%      |
| Apple               | 4         | 5%      |
| ASRock              | 3         | 3.75%   |
| Acer                | 3         | 3.75%   |
| Sony                | 2         | 2.5%    |
| Pegatron            | 2         | 2.5%    |
| ZOTAC               | 1         | 1.25%   |
| Wortmann AG         | 1         | 1.25%   |
| Toshiba             | 1         | 1.25%   |
| PCWare              | 1         | 1.25%   |
| Panasonic           | 1         | 1.25%   |
| Microsoft           | 1         | 1.25%   |
| Medion              | 1         | 1.25%   |
| HUAWEI              | 1         | 1.25%   |
| Fujitsu             | 1         | 1.25%   |
| Foxconn             | 1         | 1.25%   |
| Exo                 | 1         | 1.25%   |
| Unknown             | 1         | 1.25%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS ROG Zephyrus M16 GU603HE_GU603HE    | 2         | 2.5%    |
| ASUS PRIME Z370-A                        | 2         | 2.5%    |
| ASUS All Series                          | 2         | 2.5%    |
| ZOTAC ZBOX-CI527/CI547                   | 1         | 1.25%   |
| Wortmann AG TERRA_PC                     | 1         | 1.25%   |
| Toshiba Satellite T135D                  | 1         | 1.25%   |
| Sony VPCEE4J1E                           | 1         | 1.25%   |
| Sony SVF15318SNB                         | 1         | 1.25%   |
| Pegatron p7-1030                         | 1         | 1.25%   |
| Pegatron AY691AA-ABA p6367c              | 1         | 1.25%   |
| PCWare IPMH81G1                          | 1         | 1.25%   |
| Panasonic CF-J10YYBHR                    | 1         | 1.25%   |
| MSI Traveller 1591                       | 1         | 1.25%   |
| MSI MS-7C37                              | 1         | 1.25%   |
| MSI MS-7B89                              | 1         | 1.25%   |
| MSI MS-7788                              | 1         | 1.25%   |
| MSI GS66 Stealth 10SE                    | 1         | 1.25%   |
| MSI GP72 7RDX                            | 1         | 1.25%   |
| MSI GE66 Raider 11UG                     | 1         | 1.25%   |
| MSI C Series                             | 1         | 1.25%   |
| MSI 700-216                              | 1         | 1.25%   |
| Microsoft Surface Pro 3                  | 1         | 1.25%   |
| Medion H61H2-LM3                         | 1         | 1.25%   |
| Lenovo Yoga 730-15IKB 81CU               | 1         | 1.25%   |
| Lenovo XiaoXin Air 12 80UN               | 1         | 1.25%   |
| Lenovo ThinkPad X240 20AMS72901          | 1         | 1.25%   |
| Lenovo ThinkPad X230 2325AT6             | 1         | 1.25%   |
| Lenovo ThinkCentre M72z 3548B2S          | 1         | 1.25%   |
| Lenovo Legion Y7000P 81LD                | 1         | 1.25%   |
| Lenovo G550 2958                         | 1         | 1.25%   |
| Lenovo G50-45 80E3                       | 1         | 1.25%   |
| HUAWEI BOHK-WAX9X                        | 1         | 1.25%   |
| HP ProLiant DL380p Gen8                  | 1         | 1.25%   |
| HP ProBook 6560b                         | 1         | 1.25%   |
| HP Pavilion x360 Convertible 14-cd1xxx   | 1         | 1.25%   |
| HP Pavilion Laptop 14-bf0xx              | 1         | 1.25%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 1         | 1.25%   |
| HP Pavilion Desktop PC 570-p0xx          | 1         | 1.25%   |
| HP EliteDesk 800 G3 DM 35W               | 1         | 1.25%   |
| HP EliteBook Folio 1040 G1               | 1         | 1.25%   |
| Gigabyte Z170X-UD3                       | 1         | 1.25%   |
| Gigabyte GA-78LMT-USB3 R2                | 1         | 1.25%   |
| Gigabyte F2A68HM-DS2                     | 1         | 1.25%   |
| Gigabyte EX58-UD5                        | 1         | 1.25%   |
| Fujitsu LIFEBOOK E554                    | 1         | 1.25%   |
| Foxconn Pro3500 Series                   | 1         | 1.25%   |
| Exo CloudbookE15                         | 1         | 1.25%   |
| Dell OptiPlex GX620                      | 1         | 1.25%   |
| Dell OptiPlex 780                        | 1         | 1.25%   |
| Dell OptiPlex 360                        | 1         | 1.25%   |
| Dell Latitude E5570                      | 1         | 1.25%   |
| Dell Latitude E5430 vPro                 | 1         | 1.25%   |
| Dell Inspiron 3421                       | 1         | 1.25%   |
| Dell Inspiron 23 Model 5348              | 1         | 1.25%   |
| ASUS X550CA                              | 1         | 1.25%   |
| ASUS X541NA                              | 1         | 1.25%   |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC | 1         | 1.25%   |
| ASUS VivoBook_ASUS Laptop E210MA_E210MA  | 1         | 1.25%   |
| ASUS TUF Gaming X570-PLUS                | 1         | 1.25%   |
| ASUS STRIKER II FORMULA                  | 1         | 1.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUS PRIME             | 6         | 7.5%    |
| HP Pavilion            | 4         | 5%      |
| Dell OptiPlex          | 3         | 3.75%   |
| Lenovo ThinkPad        | 2         | 2.5%    |
| Dell Latitude          | 2         | 2.5%    |
| Dell Inspiron          | 2         | 2.5%    |
| ASUS VivoBook          | 2         | 2.5%    |
| ASUS ROG               | 2         | 2.5%    |
| ASUS All               | 2         | 2.5%    |
| ZOTAC ZBOX-CI527       | 1         | 1.25%   |
| Wortmann AG TERRA      | 1         | 1.25%   |
| Toshiba Satellite      | 1         | 1.25%   |
| Sony VPCEE4J1E         | 1         | 1.25%   |
| Sony SVF15318SNB       | 1         | 1.25%   |
| Pegatron p7-1030       | 1         | 1.25%   |
| Pegatron AY691AA-ABA   | 1         | 1.25%   |
| PCWare IPMH81G1        | 1         | 1.25%   |
| Panasonic CF-J10YYBHR  | 1         | 1.25%   |
| MSI Traveller          | 1         | 1.25%   |
| MSI MS-7C37            | 1         | 1.25%   |
| MSI MS-7B89            | 1         | 1.25%   |
| MSI MS-7788            | 1         | 1.25%   |
| MSI GS66               | 1         | 1.25%   |
| MSI GP72               | 1         | 1.25%   |
| MSI GE66               | 1         | 1.25%   |
| MSI C                  | 1         | 1.25%   |
| MSI 700-216            | 1         | 1.25%   |
| Microsoft Surface      | 1         | 1.25%   |
| Medion H61H2-LM3       | 1         | 1.25%   |
| Lenovo Yoga            | 1         | 1.25%   |
| Lenovo XiaoXin         | 1         | 1.25%   |
| Lenovo ThinkCentre     | 1         | 1.25%   |
| Lenovo Legion          | 1         | 1.25%   |
| Lenovo G550            | 1         | 1.25%   |
| Lenovo G50-45          | 1         | 1.25%   |
| HUAWEI BOHK-WAX9X      | 1         | 1.25%   |
| HP ProLiant            | 1         | 1.25%   |
| HP ProBook             | 1         | 1.25%   |
| HP EliteDesk           | 1         | 1.25%   |
| HP EliteBook           | 1         | 1.25%   |
| Gigabyte Z170X-UD3     | 1         | 1.25%   |
| Gigabyte GA-78LMT-USB3 | 1         | 1.25%   |
| Gigabyte F2A68HM-DS2   | 1         | 1.25%   |
| Gigabyte EX58-UD5      | 1         | 1.25%   |
| Fujitsu LIFEBOOK       | 1         | 1.25%   |
| Foxconn Pro3500        | 1         | 1.25%   |
| Exo CloudbookE15       | 1         | 1.25%   |
| ASUS X550CA            | 1         | 1.25%   |
| ASUS X541NA            | 1         | 1.25%   |
| ASUS TUF               | 1         | 1.25%   |
| ASUS STRIKER           | 1         | 1.25%   |
| ASUS S400CA            | 1         | 1.25%   |
| ASUS P552LJ            | 1         | 1.25%   |
| ASRock Z68             | 1         | 1.25%   |
| ASRock H61M-VS         | 1         | 1.25%   |
| ASRock B75             | 1         | 1.25%   |
| Apple MacBookPro8      | 1         | 1.25%   |
| Apple iMac14           | 1         | 1.25%   |
| Apple iMac11           | 1         | 1.25%   |
| Apple iMac10           | 1         | 1.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2017 | 12        | 15%     |
| 2011 | 10        | 12.5%   |
| 2012 | 9         | 11.25%  |
| 2019 | 7         | 8.75%   |
| 2013 | 7         | 8.75%   |
| 2018 | 6         | 7.5%    |
| 2016 | 5         | 6.25%   |
| 2014 | 5         | 6.25%   |
| 2009 | 5         | 6.25%   |
| 2021 | 4         | 5%      |
| 2020 | 4         | 5%      |
| 2008 | 3         | 3.75%   |
| 2015 | 1         | 1.25%   |
| 2010 | 1         | 1.25%   |
| 2006 | 1         | 1.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 36        | 45%     |
| Desktop     | 34        | 42.5%   |
| All in one  | 4         | 5%      |
| Convertible | 2         | 2.5%    |
| Mini pc     | 2         | 2.5%    |
| Tablet      | 1         | 1.25%   |
| Server      | 1         | 1.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 76        | 93.83%  |
| Enabled  | 5         | 6.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 80        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 19        | 22.89%  |
| 8.01-16.0   | 19        | 22.89%  |
| 16.01-24.0  | 16        | 19.28%  |
| 3.01-4.0    | 14        | 16.87%  |
| 32.01-64.0  | 8         | 9.64%   |
| 64.01-256.0 | 3         | 3.61%   |
| 24.01-32.0  | 2         | 2.41%   |
| 1.01-2.0    | 2         | 2.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 37        | 42.53%  |
| 2.01-3.0  | 26        | 29.89%  |
| 3.01-4.0  | 12        | 13.79%  |
| 4.01-8.0  | 9         | 10.34%  |
| 0.51-1.0  | 2         | 2.3%    |
| 8.01-16.0 | 1         | 1.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 57.83%  |
| 2      | 20        | 24.1%   |
| 3      | 10        | 12.05%  |
| 4      | 3         | 3.61%   |
| 5      | 1         | 1.2%    |
| 0      | 1         | 1.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 61.25%  |
| Yes       | 31        | 38.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 91.25%  |
| No        | 7         | 8.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 70%     |
| No        | 24        | 30%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 52.44%  |
| No        | 39        | 47.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 17        | 21.25%  |
| Switzerland | 9         | 11.25%  |
| Germany     | 7         | 8.75%   |
| Australia   | 7         | 8.75%   |
| UK          | 6         | 7.5%    |
| India       | 3         | 3.75%   |
| Venezuela   | 2         | 2.5%    |
| Turkey      | 2         | 2.5%    |
| Poland      | 2         | 2.5%    |
| Canada      | 2         | 2.5%    |
| Brazil      | 2         | 2.5%    |
| Belgium     | 2         | 2.5%    |
| Argentina   | 2         | 2.5%    |
| Uruguay     | 1         | 1.25%   |
| UAE         | 1         | 1.25%   |
| Spain       | 1         | 1.25%   |
| Portugal    | 1         | 1.25%   |
| Peru        | 1         | 1.25%   |
| Norway      | 1         | 1.25%   |
| Mexico      | 1         | 1.25%   |
| Jordan      | 1         | 1.25%   |
| Japan       | 1         | 1.25%   |
| Italy       | 1         | 1.25%   |
| Ireland     | 1         | 1.25%   |
| Honduras    | 1         | 1.25%   |
| Greece      | 1         | 1.25%   |
| Finland     | 1         | 1.25%   |
| Chile       | 1         | 1.25%   |
| Bulgaria    | 1         | 1.25%   |
| Belize      | 1         | 1.25%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Oberwil-Lieli  | 8         | 9.41%   |
| Melbourne      | 3         | 3.53%   |
| Winterthur     | 2         | 2.35%   |
| Richmond       | 2         | 2.35%   |
| Istanbul       | 2         | 2.35%   |
| Escondido      | 2         | 2.35%   |
| Ypsilanti      | 1         | 1.18%   |
| Wrexham        | 1         | 1.18%   |
| Varna          | 1         | 1.18%   |
| Tegucigalpa    | 1         | 1.18%   |
| Surat          | 1         | 1.18%   |
| Stuttgart      | 1         | 1.18%   |
| Stavanger      | 1         | 1.18%   |
| Sligo          | 1         | 1.18%   |
| Seattle        | 1         | 1.18%   |
| Schleusingen   | 1         | 1.18%   |
| Sao Jose       | 1         | 1.18%   |
| Santiago       | 1         | 1.18%   |
| Sankt Augustin | 1         | 1.18%   |
| Saitama        | 1         | 1.18%   |
| Recklinghausen | 1         | 1.18%   |
| Portland       | 1         | 1.18%   |
| Plymouth       | 1         | 1.18%   |
| Phoenix        | 1         | 1.18%   |
| Oudenaarde     | 1         | 1.18%   |
| New York       | 1         | 1.18%   |
| Naples         | 1         | 1.18%   |
| Montevideo     | 1         | 1.18%   |
| Moncton        | 1         | 1.18%   |
| Mieres         | 1         | 1.18%   |
| Maracay        | 1         | 1.18%   |
| Macaé         | 1         | 1.18%   |
| Los Angeles    | 1         | 1.18%   |
| Lineville      | 1         | 1.18%   |
| Lima           | 1         | 1.18%   |
| Leicester      | 1         | 1.18%   |
| Lafayette      | 1         | 1.18%   |
| La Barca       | 1         | 1.18%   |
| Krakow         | 1         | 1.18%   |
| Kloten         | 1         | 1.18%   |
| Karlsruhe      | 1         | 1.18%   |
| Hyderabad      | 1         | 1.18%   |
| Hummeltal      | 1         | 1.18%   |
| Hobart         | 1         | 1.18%   |
| Hickory        | 1         | 1.18%   |
| Hämeenlinna   | 1         | 1.18%   |
| Glasgow        | 1         | 1.18%   |
| Gdynia         | 1         | 1.18%   |
| Gdansk         | 1         | 1.18%   |
| Funchal        | 1         | 1.18%   |
| Fort St. John  | 1         | 1.18%   |
| Ernakulam      | 1         | 1.18%   |
| Edinburg       | 1         | 1.18%   |
| Delmenhorst    | 1         | 1.18%   |
| Corpus Christi | 1         | 1.18%   |
| Cincinnati     | 1         | 1.18%   |
| Caracas        | 1         | 1.18%   |
| Buenos Aires   | 1         | 1.18%   |
| Brisbane       | 1         | 1.18%   |
| Bridgwater     | 1         | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 19        | 28     | 16.38%  |
| Seagate                   | 16        | 23     | 13.79%  |
| Samsung Electronics       | 12        | 16     | 10.34%  |
| SanDisk                   | 8         | 9      | 6.9%    |
| Intel                     | 8         | 9      | 6.9%    |
| Unknown                   | 7         | 7      | 6.03%   |
| Hitachi                   | 7         | 8      | 6.03%   |
| Toshiba                   | 6         | 8      | 5.17%   |
| Kingston                  | 6         | 12     | 5.17%   |
| HGST                      | 4         | 4      | 3.45%   |
| SK hynix                  | 3         | 4      | 2.59%   |
| Phison                    | 3         | 3      | 2.59%   |
| A-DATA Technology         | 3         | 3      | 2.59%   |
| Realtek Semiconductor     | 2         | 2      | 1.72%   |
| PNY                       | 2         | 2      | 1.72%   |
| OCZ                       | 2         | 2      | 1.72%   |
| Crucial                   | 2         | 5      | 1.72%   |
| Verbatim                  | 1         | 1      | 0.86%   |
| Micron/Crucial Technology | 1         | 1      | 0.86%   |
| LITEONIT                  | 1         | 1      | 0.86%   |
| LITEON                    | 1         | 1      | 0.86%   |
| IBM                       | 1         | 1      | 0.86%   |
| China                     | 1         | 1      | 0.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 64GB            | 2         | 1.61%   |
| Unknown MMC Card  32GB                | 2         | 1.61%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 1.61%   |
| Seagate ST4000LM016-1N2170 4TB        | 2         | 1.61%   |
| Samsung HD103SJ 1TB                   | 2         | 1.61%   |
| Realtek NVMe SSD Drive 512GB          | 2         | 1.61%   |
| Phison NVMe SSD Drive 1TB             | 2         | 1.61%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 1.61%   |
| Intel NVMe SSD Drive 512GB            | 2         | 1.61%   |
| Hitachi HDS721010CLA332 1TB           | 2         | 1.61%   |
| HGST HTS721010A9E630 1TB              | 2         | 1.61%   |
| WDC WDS500G1R0B-68A4Z0 500GB SSD      | 1         | 0.81%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 0.81%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 0.81%   |
| WDC WD80EFBX-68AZZN0 8TB              | 1         | 0.81%   |
| WDC WD6400AAKS-00A7B2 640GB           | 1         | 0.81%   |
| WDC WD5000LPCX-60VHAT1 500GB          | 1         | 0.81%   |
| WDC WD5000BPKT-60PK4T0 500GB          | 1         | 0.81%   |
| WDC WD5000AAVS-00G9B1 500GB           | 1         | 0.81%   |
| WDC WD5000AAKS-65A7B2 500GB           | 1         | 0.81%   |
| WDC WD5000AAKS-00A7B2 500GB           | 1         | 0.81%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 0.81%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1         | 0.81%   |
| WDC WD2500BPVT-00JJ5T0 250GB          | 1         | 0.81%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1         | 0.81%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1         | 0.81%   |
| WDC WD10PURX-78E5EY0 1TB              | 1         | 0.81%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 0.81%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 0.81%   |
| WDC WD10EZEX-22MFCA0 1TB              | 1         | 0.81%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 0.81%   |
| WDC WD10EZEX-00WN4A0 1TB              | 1         | 0.81%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1         | 0.81%   |
| WDC WD10EURX-83UY4Y0 1TB              | 1         | 0.81%   |
| Verbatim Vi550 S3 SSD 128GB           | 1         | 0.81%   |
| Unknown SB128  128GB                  | 1         | 0.81%   |
| Unknown SA04G  4GB                    | 1         | 0.81%   |
| Unknown MMC Card  128GB               | 1         | 0.81%   |
| Toshiba THNSNJ256GCST 256GB SSD       | 1         | 0.81%   |
| Toshiba THNSNC128GNSJ 128GB SSD       | 1         | 0.81%   |
| Toshiba NVMe SSD Drive 256GB          | 1         | 0.81%   |
| Toshiba MQ01ABD100 1TB                | 1         | 0.81%   |
| Toshiba MK3275GSX 320GB               | 1         | 0.81%   |
| Toshiba DT01ACA100 1TB                | 1         | 0.81%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD | 1         | 0.81%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 0.81%   |
| SK hynix HFM001TD3JX013N 1TB          | 1         | 0.81%   |
| Seagate ST500LM000-1EJ162 500GB       | 1         | 0.81%   |
| Seagate ST500DM005 HD502HJ 500GB      | 1         | 0.81%   |
| Seagate ST3500630NS 500GB             | 1         | 0.81%   |
| Seagate ST3500418AS 500GB             | 1         | 0.81%   |
| Seagate ST3320418AS 320GB             | 1         | 0.81%   |
| Seagate ST31000528AS 1TB              | 1         | 0.81%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 0.81%   |
| Seagate ST2000DM001-9YN164 2TB        | 1         | 0.81%   |
| Seagate ST2000DM001-1CH164 2TB        | 1         | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 0.81%   |
| Seagate ST1000DM010-2EP102 1TB        | 1         | 0.81%   |
| Seagate ST1000DM003-9YN162 1TB        | 1         | 0.81%   |
| Seagate Game Drive PS4 4TB            | 1         | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


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

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 6         | 6      | 14.29%  |
| Kingston            | 6         | 12     | 14.29%  |
| Samsung Electronics | 5         | 7      | 11.9%   |
| Intel               | 5         | 5      | 11.9%   |
| WDC                 | 3         | 3      | 7.14%   |
| A-DATA Technology   | 3         | 3      | 7.14%   |
| Toshiba             | 2         | 3      | 4.76%   |
| SK hynix            | 2         | 3      | 4.76%   |
| PNY                 | 2         | 2      | 4.76%   |
| OCZ                 | 2         | 2      | 4.76%   |
| Crucial             | 2         | 5      | 4.76%   |
| Verbatim            | 1         | 1      | 2.38%   |
| LITEONIT            | 1         | 1      | 2.38%   |
| LITEON              | 1         | 1      | 2.38%   |
| China               | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 44        | 67     | 41.51%  |
| SSD     | 38        | 55     | 35.85%  |
| NVMe    | 17        | 21     | 16.04%  |
| MMC     | 5         | 6      | 4.72%   |
| Unknown | 2         | 2      | 1.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 68        | 119    | 70.83%  |
| NVMe | 17        | 21     | 17.71%  |
| SAS  | 6         | 5      | 6.25%   |
| MMC  | 5         | 6      | 5.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 73     | 60.71%  |
| 0.51-1.0   | 24        | 35     | 28.57%  |
| 1.01-2.0   | 4         | 5      | 4.76%   |
| 3.01-4.0   | 2         | 6      | 2.38%   |
| 2.01-3.0   | 2         | 2      | 2.38%   |
| 4.01-10.0  | 1         | 1      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 25.58%  |
| 251-500        | 21        | 24.42%  |
| 1001-2000      | 14        | 16.28%  |
| 501-1000       | 13        | 15.12%  |
| More than 3000 | 4         | 4.65%   |
| 2001-3000      | 4         | 4.65%   |
| 51-100         | 4         | 4.65%   |
| 21-50          | 2         | 2.33%   |
| 1-20           | 1         | 1.16%   |
| Unknown        | 1         | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 27        | 31.4%   |
| 1-20      | 15        | 17.44%  |
| 251-500   | 13        | 15.12%  |
| 101-250   | 12        | 13.95%  |
| 51-100    | 11        | 12.79%  |
| 501-1000  | 6         | 6.98%   |
| 1001-2000 | 1         | 1.16%   |
| Unknown   | 1         | 1.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5000AAVS-00G9B1 500GB     | 1         | 1      | 25%     |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 25%     |
| Seagate ST3500418AS 500GB       | 1         | 1      | 25%     |
| Intel SSDSC2BW240A4 240GB       | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Intel   | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 71        | 131    | 85.54%  |
| Works    | 9         | 16     | 10.84%  |
| Malfunc  | 3         | 4      | 3.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 59        | 60.2%   |
| AMD                          | 13        | 13.27%  |
| Samsung Electronics          | 9         | 9.18%   |
| Phison Electronics           | 3         | 3.06%   |
| Nvidia                       | 3         | 3.06%   |
| SanDisk                      | 2         | 2.04%   |
| Realtek Semiconductor        | 2         | 2.04%   |
| ASMedia Technology           | 2         | 2.04%   |
| Toshiba America Info Systems | 1         | 1.02%   |
| SK hynix                     | 1         | 1.02%   |
| Micron/Crucial Technology    | 1         | 1.02%   |
| JMicron Technology           | 1         | 1.02%   |
| Hewlett-Packard              | 1         | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8         | 6.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 4.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 4.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 4.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 4.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 3.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 3.42%   |
| Phison E12 NVMe Controller                                                              | 3         | 2.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 2.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.71%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.71%   |
| Intel Non-Volatile memory controller                                                    | 2         | 1.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.71%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.71%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 1.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.71%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.71%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.71%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 1.71%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.85%   |
| SK hynix Gold P31 SSD                                                                   | 1         | 0.85%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1         | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.85%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.85%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1         | 0.85%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 0.85%   |
| Nvidia nForce SATA Controller                                                           | 1         | 0.85%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 0.85%   |
| Nvidia MCP55 SATA Controller                                                            | 1         | 0.85%   |
| Nvidia MCP55 IDE                                                                        | 1         | 0.85%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.85%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1         | 0.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.85%   |
| Intel SSD 600P Series                                                                   | 1         | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.85%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 0.85%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1         | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 0.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.85%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1         | 0.85%   |
| HP Smart Array Gen8 Controllers                                                         | 1         | 0.85%   |
| AMD RS690 PCI to PCI Bridge (PCI Express Port 2)                                        | 1         | 0.85%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 0.85%   |
| AMD FCH IDE Controller                                                                  | 1         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 60        | 60%     |
| NVMe | 20        | 20%     |
| IDE  | 13        | 13%     |
| RAID | 7         | 7%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 65        | 81.25%  |
| AMD    | 15        | 18.75%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 3         | 3.75%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2         | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 2.5%    |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 2.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 2.5%    |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2         | 2.5%    |
| Intel Celeron CPU 1007U @ 1.50GHz           | 2         | 2.5%    |
| Intel Xeon CPU E5-2667 0 @ 2.90GHz          | 1         | 1.25%   |
| Intel Pentium D CPU 3.00GHz                 | 1         | 1.25%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 1.25%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.25%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1         | 1.25%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 1.25%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 1         | 1.25%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 1.25%   |
| Intel Core i7-7700T CPU @ 2.90GHz           | 1         | 1.25%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 1.25%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.25%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 1.25%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.25%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 1.25%   |
| Intel Core i7-4650U CPU @ 1.70GHz           | 1         | 1.25%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1         | 1.25%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1         | 1.25%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.25%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.25%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1         | 1.25%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1         | 1.25%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1         | 1.25%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.25%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.25%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.25%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 1.25%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.25%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.25%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1         | 1.25%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1         | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.25%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.25%   |
| Intel Core i5-2435M CPU @ 2.40GHz           | 1         | 1.25%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1         | 1.25%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.25%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1         | 1.25%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1         | 1.25%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.25%   |
| Intel Core i3-2375M CPU @ 1.50GHz           | 1         | 1.25%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 1         | 1.25%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1         | 1.25%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1         | 1.25%   |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz        | 1         | 1.25%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 1         | 1.25%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.25%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1         | 1.25%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz | 1         | 1.25%   |
| Intel Celeron CPU G1840 @ 2.80GHz           | 1         | 1.25%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 1.25%   |
| AMD Turion Neo X2 Dual Core Processor L625  | 1         | 1.25%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 1         | 1.25%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 22.5%   |
| Intel Core i7           | 17        | 21.25%  |
| Intel Core i3           | 7         | 8.75%   |
| Intel Pentium           | 5         | 6.25%   |
| Intel Celeron           | 5         | 6.25%   |
| Other                   | 3         | 3.75%   |
| Intel Core 2 Quad       | 3         | 3.75%   |
| AMD Ryzen 5             | 3         | 3.75%   |
| Intel Core 2 Duo        | 2         | 2.5%    |
| AMD Ryzen 9             | 2         | 2.5%    |
| AMD Ryzen 7             | 2         | 2.5%    |
| AMD A8                  | 2         | 2.5%    |
| Intel Xeon              | 1         | 1.25%   |
| Intel Pentium D         | 1         | 1.25%   |
| Intel Core m3           | 1         | 1.25%   |
| Intel Celeron Dual-Core | 1         | 1.25%   |
| Intel Atom              | 1         | 1.25%   |
| AMD Turion Neo X2       | 1         | 1.25%   |
| AMD FX                  | 1         | 1.25%   |
| AMD Athlon X2           | 1         | 1.25%   |
| AMD Athlon II           | 1         | 1.25%   |
| AMD A6                  | 1         | 1.25%   |
| AMD A10                 | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 40        | 50%     |
| 4      | 26        | 32.5%   |
| 8      | 8         | 10%     |
| 6      | 4         | 5%      |
| 12     | 2         | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 79        | 98.75%  |
| 2      | 1         | 1.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 67.5%   |
| 1      | 26        | 32.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 74        | 92.5%   |
| Unknown        | 6         | 7.5%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 8         | 10%     |
| 0x206a7    | 8         | 10%     |
| 0x40651    | 5         | 6.25%   |
| 0x306c3    | 5         | 6.25%   |
| 0x1067a    | 5         | 6.25%   |
| 0x906ea    | 4         | 5%      |
| 0x906e9    | 4         | 5%      |
| 0x806d1    | 3         | 3.75%   |
| Unknown    | 3         | 3.75%   |
| 0x806ea    | 2         | 2.5%    |
| 0x806e9    | 2         | 2.5%    |
| 0x706a8    | 2         | 2.5%    |
| 0x406e3    | 2         | 2.5%    |
| 0x0800820d | 2         | 2.5%    |
| 0xf62      | 1         | 1.25%   |
| 0xa0655    | 1         | 1.25%   |
| 0xa0652    | 1         | 1.25%   |
| 0x806eb    | 1         | 1.25%   |
| 0x6fb      | 1         | 1.25%   |
| 0x506e3    | 1         | 1.25%   |
| 0x506c9    | 1         | 1.25%   |
| 0x406c4    | 1         | 1.25%   |
| 0x306d4    | 1         | 1.25%   |
| 0x206d7    | 1         | 1.25%   |
| 0x20655    | 1         | 1.25%   |
| 0x106e5    | 1         | 1.25%   |
| 0x106a5    | 1         | 1.25%   |
| 0x0a50000c | 1         | 1.25%   |
| 0x08701021 | 1         | 1.25%   |
| 0x08108109 | 1         | 1.25%   |
| 0x0810100b | 1         | 1.25%   |
| 0x08001138 | 1         | 1.25%   |
| 0x07030105 | 1         | 1.25%   |
| 0x0600611a | 1         | 1.25%   |
| 0x06003104 | 1         | 1.25%   |
| 0x06001119 | 1         | 1.25%   |
| 0x06000852 | 1         | 1.25%   |
| 0x02000032 | 1         | 1.25%   |
| 0x010000c8 | 1         | 1.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 13        | 16.25%  |
| SandyBridge     | 10        | 12.5%   |
| Haswell         | 10        | 12.5%   |
| IvyBridge       | 9         | 11.25%  |
| Penryn          | 5         | 6.25%   |
| Zen+            | 3         | 3.75%   |
| Skylake         | 3         | 3.75%   |
| Icelake         | 3         | 3.75%   |
| Zen             | 2         | 2.5%    |
| Piledriver      | 2         | 2.5%    |
| Nehalem         | 2         | 2.5%    |
| Goldmont plus   | 2         | 2.5%    |
| CometLake       | 2         | 2.5%    |
| Zen 3           | 1         | 1.25%   |
| Zen 2           | 1         | 1.25%   |
| Westmere        | 1         | 1.25%   |
| Steamroller     | 1         | 1.25%   |
| Silvermont      | 1         | 1.25%   |
| Puma            | 1         | 1.25%   |
| NetBurst        | 1         | 1.25%   |
| K8 Hammer       | 1         | 1.25%   |
| K8 & K10 hybrid | 1         | 1.25%   |
| K10             | 1         | 1.25%   |
| Goldmont        | 1         | 1.25%   |
| Excavator       | 1         | 1.25%   |
| Core            | 1         | 1.25%   |
| Broadwell       | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 50        | 53.19%  |
| Nvidia                     | 28        | 29.79%  |
| AMD                        | 15        | 15.96%  |
| Matrox Electronics Systems | 1         | 1.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 5.32%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 5.32%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 4.26%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 3.19%   |
| Intel HD Graphics 630                                                                    | 3         | 3.19%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 2.13%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 2.13%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.13%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.13%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 2.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 2.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 2.13%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 1.06%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.06%   |
| Nvidia MCP7A [GeForce 9400]                                                              | 1         | 1.06%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.06%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.06%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 1.06%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.06%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.06%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 1.06%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 1.06%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1         | 1.06%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 1.06%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1         | 1.06%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.06%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.06%   |
| Nvidia G92 [GeForce 8800 GT]                                                             | 1         | 1.06%   |
| Nvidia C77 [GeForce 9100M G]                                                             | 1         | 1.06%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.06%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1         | 1.06%   |
| Intel HD Graphics 620                                                                    | 1         | 1.06%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.06%   |
| Intel HD Graphics 515                                                                    | 1         | 1.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.06%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.06%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.06%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.06%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 1         | 1.06%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.06%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 1         | 1.06%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.06%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 1         | 1.06%   |
| AMD Richland [Radeon HD 8670D]                                                           | 1         | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.06%   |
| AMD Navi 14 [Radeon Pro W5500]                                                           | 1         | 1.06%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.06%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 46.25%  |
| 1 x Nvidia     | 16        | 20%     |
| 1 x AMD        | 13        | 16.25%  |
| Intel + Nvidia | 11        | 13.75%  |
| 1 x Matrox     | 1         | 1.25%   |
| Intel + AMD    | 1         | 1.25%   |
| AMD + Nvidia   | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 63        | 76.83%  |
| Proprietary | 17        | 20.73%  |
| Unknown     | 2         | 2.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 51.22%  |
| 1.01-2.0   | 11        | 13.41%  |
| 0.51-1.0   | 9         | 10.98%  |
| 0.01-0.5   | 7         | 8.54%   |
| 3.01-4.0   | 6         | 7.32%   |
| 7.01-8.0   | 5         | 6.1%    |
| 5.01-6.0   | 2         | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 10        | 12.35%  |
| Samsung Electronics     | 9         | 11.11%  |
| BOE                     | 8         | 9.88%   |
| AU Optronics            | 8         | 9.88%   |
| Acer                    | 7         | 8.64%   |
| Dell                    | 4         | 4.94%   |
| Apple                   | 4         | 4.94%   |
| Lenovo                  | 3         | 3.7%    |
| Hewlett-Packard         | 3         | 3.7%    |
| Chimei Innolux          | 3         | 3.7%    |
| Sharp                   | 2         | 2.47%   |
| Philips                 | 2         | 2.47%   |
| Chi Mei Optoelectronics | 2         | 2.47%   |
| AOC                     | 2         | 2.47%   |
| Vestel                  | 1         | 1.23%   |
| Unknown                 | 1         | 1.23%   |
| Toshiba                 | 1         | 1.23%   |
| Sony                    | 1         | 1.23%   |
| Sceptre Tech            | 1         | 1.23%   |
| Panasonic               | 1         | 1.23%   |
| Onkyo                   | 1         | 1.23%   |
| Medion                  | 1         | 1.23%   |
| LG Electronics          | 1         | 1.23%   |
| Lenovo Group Limited    | 1         | 1.23%   |
| Insignia                | 1         | 1.23%   |
| Goldstar                | 1         | 1.23%   |
| BenQ                    | 1         | 1.23%   |
| Ancor Communications    | 1         | 1.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch           | 2         | 2.33%   |
| Vestel LCD Monitor 32W_LCD_TV 1920x1080                                  | 1         | 1.16%   |
| Unknown LCD Monitor SAMSUNG                                              | 1         | 1.16%   |
| Toshiba LCD Monitor LCD0905 1366x768 295x166mm 13.3-inch                 | 1         | 1.16%   |
| Sony AVAMP SNYF400 1920x1080 700x390mm 31.5-inch                         | 1         | 1.16%   |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch                  | 1         | 1.16%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 1.16%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                   | 1         | 1.16%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch        | 1         | 1.16%   |
| Samsung Electronics LCD Monitor U28E590 7680x2160                        | 1         | 1.16%   |
| Samsung Electronics LCD Monitor U28E590                                  | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch    | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch     | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch   | 1         | 1.16%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1         | 1.16%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.16%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch        | 1         | 1.16%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 1         | 1.16%   |
| Philips PHL 328E9Q PHLC180 1920x1080 698x393mm 31.5-inch                 | 1         | 1.16%   |
| Philips 220EW PHL0861 1680x1050 434x270mm 20.1-inch                      | 1         | 1.16%   |
| Panasonic TV MEIC301 1920x1080 698x392mm 31.5-inch                       | 1         | 1.16%   |
| Onkyo TX-NR535 ONK0E51 2560x1440 597x336mm 27.0-inch                     | 1         | 1.16%   |
| Medion MD 20094 MED3610 1920x1200 550x344mm 25.5-inch                    | 1         | 1.16%   |
| LG Electronics LCD Monitor MP59HT 1920x1080                              | 1         | 1.16%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD044F 1920x1080 344x194mm 15.5-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 1.16%   |
| Lenovo LEN L171 LEN240B 1280x1024 340x270mm 17.1-inch                    | 1         | 1.16%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                     | 1         | 1.16%   |
| Lenovo H61 LEN520B 1600x900 410x230mm 18.5-inch                          | 1         | 1.16%   |
| Lenovo Group Limited LCD Monitor L24q-10 2560x1440                       | 1         | 1.16%   |
| Insignia NS-24EM51A14 BBYBB24 1920x1080 531x299mm 24.0-inch              | 1         | 1.16%   |
| Hewlett-Packard ZR22w HWP2867 1920x1080 475x267mm 21.5-inch              | 1         | 1.16%   |
| Hewlett-Packard LCD Monitor ZR22w 3840x1080                              | 1         | 1.16%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x287mm 23.0-inch             | 1         | 1.16%   |
| Hewlett-Packard 2509 HWP283A 1920x1080 553x311mm 25.0-inch               | 1         | 1.16%   |
| Goldstar E2242 GSM58BE 1920x1080 480x270mm 21.7-inch                     | 1         | 1.16%   |
| Dell UP3017 DEL40FA 2560x1600 641x401mm 29.8-inch                        | 1         | 1.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 1         | 1.16%   |
| Dell SP1908FP DEL4030 1280x1024 376x301mm 19.0-inch                      | 1         | 1.16%   |
| Dell Inspiron 5348 DEL93E8 1920x1080 510x287mm 23.0-inch                 | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1557 1366x768 344x193mm 15.5-inch | 1         | 1.16%   |
| Chi Mei Optoelectronics LCD Monitor CMC 19AW 1440x900                    | 1         | 1.16%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 1         | 1.16%   |
| BOE LCD Monitor BOE0854 1920x1080 344x194mm 15.5-inch                    | 1         | 1.16%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                    | 1         | 1.16%   |
| BOE LCD Monitor BOE072B 1920x1080 309x173mm 13.9-inch                    | 1         | 1.16%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 1         | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 40%     |
| 1366x768 (WXGA)    | 21        | 26.25%  |
| 2560x1440 (QHD)    | 6         | 7.5%    |
| 3840x2160 (4K)     | 3         | 3.75%   |
| 2560x1600          | 3         | 3.75%   |
| 1280x1024 (SXGA)   | 3         | 3.75%   |
| 1680x1050 (WSXGA+) | 2         | 2.5%    |
| Unknown            | 2         | 2.5%    |
| 7680x2160          | 1         | 1.25%   |
| 3840x1080          | 1         | 1.25%   |
| 2160x1440          | 1         | 1.25%   |
| 1920x1200 (WUXGA)  | 1         | 1.25%   |
| 1600x900 (HD+)     | 1         | 1.25%   |
| 1440x900 (WXGA+)   | 1         | 1.25%   |
| 1280x800 (WXGA)    | 1         | 1.25%   |
| 1024x768 (XGA)     | 1         | 1.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 30%     |
| Unknown | 8         | 10%     |
| 27      | 6         | 7.5%    |
| 21      | 5         | 6.25%   |
| 24      | 4         | 5%      |
| 14      | 4         | 5%      |
| 13      | 4         | 5%      |
| 31      | 3         | 3.75%   |
| 23      | 3         | 3.75%   |
| 17      | 3         | 3.75%   |
| 32      | 2         | 2.5%    |
| 25      | 2         | 2.5%    |
| 22      | 2         | 2.5%    |
| 16      | 2         | 2.5%    |
| 12      | 2         | 2.5%    |
| 54      | 1         | 1.25%   |
| 49      | 1         | 1.25%   |
| 29      | 1         | 1.25%   |
| 19      | 1         | 1.25%   |
| 18      | 1         | 1.25%   |
| 11      | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 41.25%  |
| 501-600     | 15        | 18.75%  |
| 401-500     | 8         | 10%     |
| Unknown     | 8         | 10%     |
| 201-300     | 5         | 6.25%   |
| 601-700     | 4         | 5%      |
| 351-400     | 3         | 3.75%   |
| 701-800     | 2         | 2.5%    |
| 1001-1500   | 2         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 58        | 74.36%  |
| 16/10   | 8         | 10.26%  |
| Unknown | 8         | 10.26%  |
| 5/4     | 3         | 3.85%   |
| 4/3     | 1         | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 30%     |
| 201-250        | 12        | 15%     |
| Unknown        | 8         | 10%     |
| 81-90          | 7         | 8.75%   |
| 351-500        | 6         | 7.5%    |
| 301-350        | 6         | 7.5%    |
| 251-300        | 3         | 3.75%   |
| 141-150        | 3         | 3.75%   |
| More than 1000 | 2         | 2.5%    |
| 61-70          | 2         | 2.5%    |
| 151-200        | 2         | 2.5%    |
| 111-120        | 2         | 2.5%    |
| 71-80          | 1         | 1.25%   |
| 51-60          | 1         | 1.25%   |
| 121-130        | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 24        | 30.77%  |
| 101-120       | 23        | 29.49%  |
| 121-160       | 17        | 21.79%  |
| Unknown       | 8         | 10.26%  |
| 161-240       | 3         | 3.85%   |
| 1-50          | 2         | 2.56%   |
| More than 240 | 1         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 71        | 85.54%  |
| 2     | 9         | 10.84%  |
| 0     | 2         | 2.41%   |
| 3     | 1         | 1.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 47        | 39.5%   |
| Intel                           | 26        | 21.85%  |
| Qualcomm Atheros                | 10        | 8.4%    |
| Broadcom                        | 10        | 8.4%    |
| TP-Link                         | 3         | 2.52%   |
| Ralink Technology               | 3         | 2.52%   |
| Ralink                          | 3         | 2.52%   |
| MediaTek                        | 3         | 2.52%   |
| Sierra Wireless                 | 2         | 1.68%   |
| Nvidia                          | 2         | 1.68%   |
| Linksys                         | 2         | 1.68%   |
| Qualcomm Atheros Communications | 1         | 0.84%   |
| Qualcomm                        | 1         | 0.84%   |
| NetGear                         | 1         | 0.84%   |
| Motorola PCS                    | 1         | 0.84%   |
| Microsoft                       | 1         | 0.84%   |
| Marvell Technology Group        | 1         | 0.84%   |
| Edimax Technology               | 1         | 0.84%   |
| D-Link                          | 1         | 0.84%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 35        | 24.48%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 2.8%    |
| Intel Ethernet Connection (2) I219-V                                                          | 4         | 2.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3         | 2.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 3         | 2.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 2.1%    |
| Intel Wireless 7260                                                                           | 3         | 2.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 2.1%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2         | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.4%    |
| Realtek Realtek Ethernet controller                                                           | 2         | 1.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 2         | 1.4%    |
| Intel Ethernet Connection I219-LM                                                             | 2         | 1.4%    |
| Intel Ethernet Connection I218-LM                                                             | 2         | 1.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 1.4%    |
| Intel 82579V Gigabit Network Connection                                                       | 2         | 1.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2         | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 1.4%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 0.7%    |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 0.7%    |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 0.7%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1         | 0.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 0.7%    |
| Realtek RTL8187 Wireless Adapter                                                              | 1         | 0.7%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.7%    |
| Realtek Killer E3000 2.5GbE Controller                                                        | 1         | 0.7%    |
| Ralink RT5572 Wireless Adapter                                                                | 1         | 0.7%    |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1         | 0.7%    |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.7%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1         | 0.7%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 0.7%    |
| Qualcomm BENGAL-QRD _SN:C5464635                                                              | 1         | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 0.7%    |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 0.7%    |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 0.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1         | 0.7%    |
| Nvidia MCP79 Ethernet                                                                         | 1         | 0.7%    |
| Nvidia MCP55 Ethernet                                                                         | 1         | 0.7%    |
| NetGear A6210                                                                                 | 1         | 0.7%    |
| Motorola PCS moto g(9) play                                                                   | 1         | 0.7%    |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                                             | 1         | 0.7%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                             | 1         | 0.7%    |
| Linksys WUSB6300 V2                                                                           | 1         | 0.7%    |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                        | 1         | 0.7%    |
| Intel Wireless 8265 / 8275                                                                    | 1         | 0.7%    |
| Intel Wireless 8260                                                                           | 1         | 0.7%    |
| Intel Wireless 3165                                                                           | 1         | 0.7%    |
| Intel Wireless 3160                                                                           | 1         | 0.7%    |
| Intel WiMAX Connection 2400m                                                                  | 1         | 0.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 0.7%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 28.79%  |
| Realtek Semiconductor           | 14        | 21.21%  |
| Qualcomm Atheros                | 8         | 12.12%  |
| Broadcom                        | 4         | 6.06%   |
| TP-Link                         | 3         | 4.55%   |
| Ralink Technology               | 3         | 4.55%   |
| Ralink                          | 3         | 4.55%   |
| MediaTek                        | 3         | 4.55%   |
| Sierra Wireless                 | 2         | 3.03%   |
| Linksys                         | 2         | 3.03%   |
| Qualcomm Atheros Communications | 1         | 1.52%   |
| NetGear                         | 1         | 1.52%   |
| Marvell Technology Group        | 1         | 1.52%   |
| Edimax Technology               | 1         | 1.52%   |
| D-Link                          | 1         | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 6.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3         | 4.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 4.55%   |
| Intel Wireless 7260                                                                           | 3         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 4.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 3.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 3.03%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 3.03%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 1.52%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 1.52%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.52%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 1.52%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1         | 1.52%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1         | 1.52%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1         | 1.52%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.52%   |
| Ralink RT5572 Wireless Adapter                                                                | 1         | 1.52%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1         | 1.52%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.52%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1         | 1.52%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.52%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 1.52%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1         | 1.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.52%   |
| NetGear A6210                                                                                 | 1         | 1.52%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                             | 1         | 1.52%   |
| Linksys WUSB6300 V2                                                                           | 1         | 1.52%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                        | 1         | 1.52%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.52%   |
| Intel Wireless 8260                                                                           | 1         | 1.52%   |
| Intel Wireless 3165                                                                           | 1         | 1.52%   |
| Intel Wireless 3160                                                                           | 1         | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 1.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 1.52%   |
| Intel Centrino Wireless-N 2230                                                                | 1         | 1.52%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                                          | 1         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.52%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                                      | 1         | 1.52%   |
| D-Link DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.B2) [Ralink RT5572]                  | 1         | 1.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1         | 1.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 1         | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 41        | 53.95%  |
| Intel                 | 18        | 23.68%  |
| Broadcom              | 8         | 10.53%  |
| Qualcomm Atheros      | 4         | 5.26%   |
| Nvidia                | 2         | 2.63%   |
| Qualcomm              | 1         | 1.32%   |
| Motorola PCS          | 1         | 1.32%   |
| Microsoft             | 1         | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 45.45%  |
| Intel Ethernet Connection (2) I219-V                              | 4         | 5.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.9%    |
| Realtek Realtek Ethernet controller                               | 2         | 2.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 2.6%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.6%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.6%    |
| Intel 82579V Gigabit Network Connection                           | 2         | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.6%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.3%    |
| Qualcomm BENGAL-QRD _SN:C5464635                                  | 1         | 1.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.3%    |
| Nvidia MCP79 Ethernet                                             | 1         | 1.3%    |
| Nvidia MCP55 Ethernet                                             | 1         | 1.3%    |
| Motorola PCS moto g(9) play                                       | 1         | 1.3%    |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 1         | 1.3%    |
| Intel WiMAX Connection 2400m                                      | 1         | 1.3%    |
| Intel Ethernet controller                                         | 1         | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.3%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.3%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.3%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 1.3%    |
| Broadcom NetXtreme II BCM57711 10-Gigabit PCIe                    | 1         | 1.3%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.3%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.3%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.3%    |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 1.3%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.3%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.3%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 73        | 56.59%  |
| WiFi     | 56        | 43.41%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 54.88%  |
| Ethernet | 37        | 45.12%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 40        | 50%     |
| 1     | 37        | 46.25%  |
| 4     | 1         | 1.25%   |
| 3     | 1         | 1.25%   |
| 0     | 1         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 69        | 85.19%  |
| Yes  | 12        | 14.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 31.82%  |
| Realtek Semiconductor           | 6         | 13.64%  |
| Cambridge Silicon Radio         | 6         | 13.64%  |
| Apple                           | 4         | 9.09%   |
| IMC Networks                    | 3         | 6.82%   |
| Broadcom                        | 3         | 6.82%   |
| Realtek                         | 2         | 4.55%   |
| Ralink                          | 1         | 2.27%   |
| Qualcomm Atheros Communications | 1         | 2.27%   |
| Marvell Semiconductor           | 1         | 2.27%   |
| Lite-On Technology              | 1         | 2.27%   |
| Hewlett-Packard                 | 1         | 2.27%   |
| Foxconn / Hon Hai               | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 18.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 13.64%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.82%   |
| IMC Networks Wireless_Device                        | 3         | 6.82%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 4.55%   |
| Realtek Bluetooth Radio                             | 2         | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 4.55%   |
| Realtek Bluetooth Radio                             | 1         | 2.27%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.27%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.27%   |
| Lite-On Bluetooth Device                            | 1         | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.27%   |
| Intel AX210 Bluetooth                               | 1         | 2.27%   |
| Intel AX201 Bluetooth                               | 1         | 2.27%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.27%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 2.27%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 2.27%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.27%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.27%   |
| Apple Bluetooth Host Controller                     | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 61        | 55.45%  |
| Nvidia              | 23        | 20.91%  |
| AMD                 | 17        | 15.45%  |
| Logitech            | 2         | 1.82%   |
| C-Media Electronics | 2         | 1.82%   |
| Texas Instruments   | 1         | 0.91%   |
| Razer USA           | 1         | 0.91%   |
| Microsoft           | 1         | 0.91%   |
| Hewlett-Packard     | 1         | 0.91%   |
| Creative Labs       | 1         | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 8.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.38%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 4.62%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 3.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 3.85%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 3.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 3.08%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 3.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 2.31%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.31%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 2.31%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.31%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.31%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 2.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 2.31%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.54%   |
| Nvidia Audio device                                                        | 2         | 1.54%   |
| Logitech Headset H390                                                      | 2         | 1.54%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 1.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.54%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.77%   |
| Razer USA Nommo Chroma                                                     | 1         | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.77%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.77%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1         | 0.77%   |
| Nvidia MCP55 High Definition Audio                                         | 1         | 0.77%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.77%   |
| Microsoft Surface Pro 3 Docking Station Audio Device                       | 1         | 0.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.77%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 0.77%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.77%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.77%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 0.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.77%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1         | 0.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.77%   |
| Hewlett-Packard Speaker Bar                                                | 1         | 0.77%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1         | 0.77%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1         | 0.77%   |
| C-Media Electronics BIRD UM1                                               | 1         | 0.77%   |
| C-Media Electronics Audio Adapter                                          | 1         | 0.77%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1         | 0.77%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 0.77%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 0.77%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 0.77%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1         | 0.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 0.77%   |
| AMD Navi 10 HDMI Audio                                                     | 1         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 17.39%  |
| Micron Technology   | 4         | 17.39%  |
| Crucial             | 4         | 17.39%  |
| Unknown             | 2         | 8.7%    |
| SK hynix            | 2         | 8.7%    |
| Kingston            | 2         | 8.7%    |
| A-DATA Technology   | 2         | 8.7%    |
| Nanya Technology    | 1         | 4.35%   |
| Hewlett-Packard     | 1         | 4.35%   |
| Corsair             | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 2         | 7.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 7.69%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 3.85%   |
| Unknown RAM Module 4096MB DIMM DDR3 1400MT/s               | 1         | 3.85%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s            | 1         | 3.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s           | 1         | 3.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 3.85%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s   | 1         | 3.85%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s        | 1         | 3.85%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1         | 3.85%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s         | 1         | 3.85%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4096MB SODIMM DDR3 1600MT/s  | 1         | 3.85%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 3.85%   |
| Kingston RAM MSI24D4S7D8MH-16 16384MB SODIMM DDR4 2400MT/s | 1         | 3.85%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s        | 1         | 3.85%   |
| HP RAM 7EH65AA# 16384MB DIMM DDR4 2666MT/s                 | 1         | 3.85%   |
| Crucial RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 3.85%   |
| Crucial RAM CT8G4DFD8213.C16FBR2 8GB DIMM DDR4 2133MT/s    | 1         | 3.85%   |
| Crucial RAM CT51264BF160BJ.C8F 4096MB SODIMM DDR3 1600MT/s | 1         | 3.85%   |
| Crucial RAM CT16G4SFD824A.C16FP 16GB SODIMM DDR4 2400MT/s  | 1         | 3.85%   |
| Corsair RAM CMK16GX4M2A2666C16 8192MB DIMM DDR4 3200MT/s   | 1         | 3.85%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3000MT/s                | 1         | 3.85%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s       | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 52.63%  |
| DDR3   | 7         | 36.84%  |
| LPDDR3 | 1         | 5.26%   |
| DDR2   | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 12        | 63.16%  |
| DIMM   | 7         | 36.84%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 7         | 35%     |
| 4096  | 7         | 35%     |
| 16384 | 4         | 20%     |
| 2048  | 2         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 6         | 28.57%  |
| 3200  | 4         | 19.05%  |
| 2400  | 3         | 14.29%  |
| 3000  | 1         | 4.76%   |
| 2667  | 1         | 4.76%   |
| 2666  | 1         | 4.76%   |
| 2133  | 1         | 4.76%   |
| 2048  | 1         | 4.76%   |
| 2000  | 1         | 4.76%   |
| 1867  | 1         | 4.76%   |
| 1400  | 1         | 4.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 28.57%  |
| Canon              | 2         | 28.57%  |
| Brother Industries | 2         | 28.57%  |
| Star Micronics     | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 18%     |
| IMC Networks                           | 6         | 12%     |
| Acer                                   | 5         | 10%     |
| Realtek Semiconductor                  | 4         | 8%      |
| Apple                                  | 4         | 8%      |
| Sunplus Innovation Technology          | 3         | 6%      |
| Logitech                               | 3         | 6%      |
| Microsoft                              | 2         | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4%      |
| Z-Star Microelectronics                | 1         | 2%      |
| Samsung Electronics                    | 1         | 2%      |
| Pixart Imaging                         | 1         | 2%      |
| Novatek Microelectronics               | 1         | 2%      |
| Microdia                               | 1         | 2%      |
| Lite-On Technology                     | 1         | 2%      |
| Huawei Technologies                    | 1         | 2%      |
| Generalplus Technology                 | 1         | 2%      |
| GEMBIRD                                | 1         | 2%      |
| Cubeternet                             | 1         | 2%      |
| ARC International                      | 1         | 2%      |
| Alcor Micro                            | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 6%      |
| Acer Lenovo EasyCamera                                                     | 3         | 6%      |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 4%      |
| Chicony Integrated Camera                                                  | 2         | 4%      |
| Apple Built-in iSight                                                      | 2         | 4%      |
| Z-Star Integrated Camera                                                   | 1         | 2%      |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2%      |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 2%      |
| Sunplus ASUS USB2.0 Webcam                                                 | 1         | 2%      |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 2%      |
| Realtek USB Camera                                                         | 1         | 2%      |
| Realtek Integrated_Webcam_HD                                               | 1         | 2%      |
| Realtek HP Wide Vision HD Camera                                           | 1         | 2%      |
| Realtek HD WebCam                                                          | 1         | 2%      |
| Pixart Imaging GE 1.3 MP MiniCam Pro                                       | 1         | 2%      |
| Novatek J1455                                                              | 1         | 2%      |
| Microsoft LifeCam VX-5000                                                  | 1         | 2%      |
| Microsoft LifeCam VX-500 [1357]                                            | 1         | 2%      |
| Microdia Integrated Webcam                                                 | 1         | 2%      |
| Logitech Webcam C270                                                       | 1         | 2%      |
| Logitech Webcam C250                                                       | 1         | 2%      |
| Logitech QuickCam Communicate MP/S5500                                     | 1         | 2%      |
| Lite-On Integrated Camera                                                  | 1         | 2%      |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 2%      |
| Huawei HiCamera                                                            | 1         | 2%      |
| Generalplus 808 Camera                                                     | 1         | 2%      |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]                          | 1         | 2%      |
| Cubeternet GL-UPC822 UVC WebCam                                            | 1         | 2%      |
| Chicony WebCam                                                             | 1         | 2%      |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 2%      |
| Chicony USB 2.0 Camera                                                     | 1         | 2%      |
| Chicony Sony Visual Communication Camera                                   | 1         | 2%      |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 2%      |
| Chicony HP Wide Vision HD Camera                                           | 1         | 2%      |
| Chicony FJ Camera                                                          | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 1         | 2%      |
| ARC International Camera                                                   | 1         | 2%      |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 2%      |
| Apple FaceTime HD Camera                                                   | 1         | 2%      |
| Alcor Micro USB 2.0 PC cam                                                 | 1         | 2%      |
| Acer Integrated Camera                                                     | 1         | 2%      |
| Acer HD Camera                                                             | 1         | 2%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 66.67%  |
| Synaptics                  | 1         | 16.67%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| OmniKey           | 1         | 25%     |
| Mako Technologies | 1         | 25%     |
| Broadcom          | 1         | 25%     |
| BIT4ID            | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 61        | 73.49%  |
| 1     | 18        | 21.69%  |
| 2     | 3         | 3.61%   |
| 3     | 1         | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 8         | 32%     |
| Fingerprint reader    | 6         | 24%     |
| Net/wireless          | 4         | 16%     |
| Chipcard              | 3         | 12%     |
| Sound                 | 1         | 4%      |
| Net/ethernet          | 1         | 4%      |
| Multimedia controller | 1         | 4%      |
| Bluetooth             | 1         | 4%      |

