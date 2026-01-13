Linux in Indonesia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Indonesia/Desktop/README.md) and [notebooks](/Location/Indonesia/Notebook/README.md).

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

Total: 3165

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Sony          | SVF14212SGW                 | Notebook    | [5bbc92047d](https://linux-hardware.org/?probe=5bbc92047d) | Jan 03, 2026 |
| ASUSTek       | ASUS Zenbook 14 UM3406HA... | Notebook    | [890648fece](https://linux-hardware.org/?probe=890648fece) | Jan 03, 2026 |
| Lenovo        | G40-45 80E1                 | Notebook    | [b7776e4ae0](https://linux-hardware.org/?probe=b7776e4ae0) | Jan 03, 2026 |
| Sony          | SVP11213SGBI                | Notebook    | [811f8094ee](https://linux-hardware.org/?probe=811f8094ee) | Jan 03, 2026 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d8c9a2c73d](https://linux-hardware.org/?probe=d8c9a2c73d) | Jan 02, 2026 |
| Acer          | Aspire V5-471               | Notebook    | [423ccefb85](https://linux-hardware.org/?probe=423ccefb85) | Dec 31, 2025 |
| Acer          | Swift SF314-54G             | Notebook    | [4cd9361813](https://linux-hardware.org/?probe=4cd9361813) | Dec 31, 2025 |
| Lenovo        | ThinkPad X250 20CLS06800    | Notebook    | [ac469bf595](https://linux-hardware.org/?probe=ac469bf595) | Dec 30, 2025 |
| Intel         | H110                        | Desktop     | [329a7cfb8a](https://linux-hardware.org/?probe=329a7cfb8a) | Dec 30, 2025 |
| Apple         | MacBookAir4,1               | Notebook    | [c3797947db](https://linux-hardware.org/?probe=c3797947db) | Dec 29, 2025 |
| ASRock        | H310CM-HDV                  | Desktop     | [25f0a879bb](https://linux-hardware.org/?probe=25f0a879bb) | Dec 29, 2025 |
| Gigabyte      | B550M DS3H                  | Desktop     | [58bb579875](https://linux-hardware.org/?probe=58bb579875) | Dec 28, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [ae78491b3d](https://linux-hardware.org/?probe=ae78491b3d) | Dec 28, 2025 |
| Fujitsu       | T580                        | Notebook    | [b90bb28423](https://linux-hardware.org/?probe=b90bb28423) | Dec 28, 2025 |
| HP            | 3397                        | Desktop     | [d21a114362](https://linux-hardware.org/?probe=d21a114362) | Dec 28, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [08812fdfe2](https://linux-hardware.org/?probe=08812fdfe2) | Dec 28, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [44130e6ef0](https://linux-hardware.org/?probe=44130e6ef0) | Dec 28, 2025 |
| Panasonic     | CF-SX1GDHYS                 | Notebook    | [ed137e4105](https://linux-hardware.org/?probe=ed137e4105) | Dec 27, 2025 |
| Lenovo        | ThinkPad T420 4180PKC       | Notebook    | [96452fed0f](https://linux-hardware.org/?probe=96452fed0f) | Dec 26, 2025 |
| Intel         | H81                         | Desktop     | [514c6a7933](https://linux-hardware.org/?probe=514c6a7933) | Dec 25, 2025 |
| Intel         | H61                         | Desktop     | [a996c59bd4](https://linux-hardware.org/?probe=a996c59bd4) | Dec 25, 2025 |
| Gigabyte      | H81M-DS2                    | Desktop     | [48f1ce3c05](https://linux-hardware.org/?probe=48f1ce3c05) | Dec 24, 2025 |
| ASUSTek       | Vivobook Go E1404GAB_E14... | Notebook    | [4c326c5a9e](https://linux-hardware.org/?probe=4c326c5a9e) | Dec 24, 2025 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [7a3d640ca0](https://linux-hardware.org/?probe=7a3d640ca0) | Dec 24, 2025 |
| HP            | 1495                        | Desktop     | [672633acf3](https://linux-hardware.org/?probe=672633acf3) | Dec 24, 2025 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [7315a4dacb](https://linux-hardware.org/?probe=7315a4dacb) | Dec 22, 2025 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [d06a921c35](https://linux-hardware.org/?probe=d06a921c35) | Dec 21, 2025 |
| Supermicro    | X11SAE                      | Server      | [3749189306](https://linux-hardware.org/?probe=3749189306) | Dec 20, 2025 |
| Lenovo        | ThinkPad T61 765801U        | Notebook    | [d3860bc423](https://linux-hardware.org/?probe=d3860bc423) | Dec 20, 2025 |
| ASRock        | B460M Steel Legend          | Desktop     | [176f88f86e](https://linux-hardware.org/?probe=176f88f86e) | Dec 20, 2025 |
| ASUSTek       | H61M-C                      | Desktop     | [44829ff4b8](https://linux-hardware.org/?probe=44829ff4b8) | Dec 19, 2025 |
| ADVAN         | 1701                        | Notebook    | [4b91cc5a98](https://linux-hardware.org/?probe=4b91cc5a98) | Dec 18, 2025 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [7c20e10861](https://linux-hardware.org/?probe=7c20e10861) | Dec 18, 2025 |
| Acer          | Aspire ES1-431              | Notebook    | [99faafef7a](https://linux-hardware.org/?probe=99faafef7a) | Dec 18, 2025 |
| Acer          | Veriton Z4640G              | All in one  | [b93898c75e](https://linux-hardware.org/?probe=b93898c75e) | Dec 18, 2025 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [cafc2c974d](https://linux-hardware.org/?probe=cafc2c974d) | Dec 16, 2025 |
| Samsung       | 275E4E/275E5E               | Notebook    | [fa22f21ec7](https://linux-hardware.org/?probe=fa22f21ec7) | Dec 16, 2025 |
| Samsung       | 275E4E/275E5E               | Notebook    | [dcaa23df9f](https://linux-hardware.org/?probe=dcaa23df9f) | Dec 16, 2025 |
| Acer          | Aspire AL14-51M             | Notebook    | [6d7013d9fc](https://linux-hardware.org/?probe=6d7013d9fc) | Dec 16, 2025 |
| Acer          | Aspire E1-572               | Notebook    | [baad0ebb61](https://linux-hardware.org/?probe=baad0ebb61) | Dec 15, 2025 |
| Lenovo        | B40-80 80F6                 | Notebook    | [318f112a2f](https://linux-hardware.org/?probe=318f112a2f) | Dec 15, 2025 |
| AISURIX       | H81 Motherboard V2.0        | Desktop     | [3bcae0d33b](https://linux-hardware.org/?probe=3bcae0d33b) | Dec 14, 2025 |
| Gigabyte      | 965P-DS3                    | Desktop     | [3ed3880244](https://linux-hardware.org/?probe=3ed3880244) | Dec 13, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [67ddd7d385](https://linux-hardware.org/?probe=67ddd7d385) | Dec 13, 2025 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [6c10af5541](https://linux-hardware.org/?probe=6c10af5541) | Dec 12, 2025 |
| Acer          | Aspire E5-475G              | Notebook    | [5aab283242](https://linux-hardware.org/?probe=5aab283242) | Dec 12, 2025 |
| Lenovo        | ThinkPad T430 2347AY1       | Notebook    | [82657de520](https://linux-hardware.org/?probe=82657de520) | Dec 11, 2025 |
| Gigabyte      | G41M-Combo                  | Desktop     | [b6daa2fff5](https://linux-hardware.org/?probe=b6daa2fff5) | Dec 11, 2025 |
| Acer          | Aspire E5-475G              | Notebook    | [b21fdca8c7](https://linux-hardware.org/?probe=b21fdca8c7) | Dec 10, 2025 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [492de5e1b0](https://linux-hardware.org/?probe=492de5e1b0) | Dec 10, 2025 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [a02578bd61](https://linux-hardware.org/?probe=a02578bd61) | Dec 10, 2025 |
| ASUSTek       | H81M-C                      | Desktop     | [dcdc41b589](https://linux-hardware.org/?probe=dcdc41b589) | Dec 09, 2025 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [807118d9c2](https://linux-hardware.org/?probe=807118d9c2) | Dec 09, 2025 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [cd6f420426](https://linux-hardware.org/?probe=cd6f420426) | Dec 09, 2025 |
| HP            | 8597                        | Desktop     | [d52f1722fd](https://linux-hardware.org/?probe=d52f1722fd) | Dec 08, 2025 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [b495f7293c](https://linux-hardware.org/?probe=b495f7293c) | Dec 08, 2025 |
| HP            | 8597                        | Desktop     | [30ed22e915](https://linux-hardware.org/?probe=30ed22e915) | Dec 08, 2025 |
| Gigabyte      | GA-H110M-H-CF               | Desktop     | [4c446050d7](https://linux-hardware.org/?probe=4c446050d7) | Dec 08, 2025 |
| MSI           | Claw A1M                    | Tablet      | [51385f41da](https://linux-hardware.org/?probe=51385f41da) | Dec 07, 2025 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [6ac88f7c1c](https://linux-hardware.org/?probe=6ac88f7c1c) | Dec 07, 2025 |
| ASUSTek       | ROG Strix G513RM            | Notebook    | [b658600e4f](https://linux-hardware.org/?probe=b658600e4f) | Dec 06, 2025 |
| MSI           | B250M PRO-VDH               | Desktop     | [1ae1dc130c](https://linux-hardware.org/?probe=1ae1dc130c) | Dec 06, 2025 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [0c1c1825e3](https://linux-hardware.org/?probe=0c1c1825e3) | Dec 06, 2025 |
| ASRock        | B550M Pro4                  | Desktop     | [233048ee4b](https://linux-hardware.org/?probe=233048ee4b) | Dec 05, 2025 |
| ASRock        | B550M Pro4                  | Desktop     | [b206dfea93](https://linux-hardware.org/?probe=b206dfea93) | Dec 05, 2025 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [ed4340cd1a](https://linux-hardware.org/?probe=ed4340cd1a) | Dec 05, 2025 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [6e26cc8f0b](https://linux-hardware.org/?probe=6e26cc8f0b) | Dec 05, 2025 |
| Acer          | Swift SF314-510G            | Notebook    | [72d4a322d2](https://linux-hardware.org/?probe=72d4a322d2) | Dec 05, 2025 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [c38dcd8f2e](https://linux-hardware.org/?probe=c38dcd8f2e) | Dec 04, 2025 |
| AXIOO         | MyPC One Pro L-24           | All in one  | [d8f8c8f731](https://linux-hardware.org/?probe=d8f8c8f731) | Dec 04, 2025 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [5bfa835fe4](https://linux-hardware.org/?probe=5bfa835fe4) | Dec 03, 2025 |
| Acer          | Aspire A314-22              | Notebook    | [618ae0cb96](https://linux-hardware.org/?probe=618ae0cb96) | Dec 02, 2025 |
| ASUSTek       | Vivobook Go E1404GAB_E14... | Notebook    | [6a92791cba](https://linux-hardware.org/?probe=6a92791cba) | Dec 01, 2025 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [527ff37ff4](https://linux-hardware.org/?probe=527ff37ff4) | Nov 30, 2025 |
| ASUSTek       | X550IU                      | Notebook    | [25abd93fd5](https://linux-hardware.org/?probe=25abd93fd5) | Nov 30, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [cbf085a8c3](https://linux-hardware.org/?probe=cbf085a8c3) | Nov 29, 2025 |
| Toshiba       | dynabook G83/M              | Notebook    | [fffd9bf116](https://linux-hardware.org/?probe=fffd9bf116) | Nov 29, 2025 |
| Fujitsu       | FARQ1401AZ                  | Tablet      | [b45d25a19e](https://linux-hardware.org/?probe=b45d25a19e) | Nov 28, 2025 |
| Acer          | Aspire AL14-51M             | Notebook    | [9046fa633a](https://linux-hardware.org/?probe=9046fa633a) | Nov 26, 2025 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [44db012055](https://linux-hardware.org/?probe=44db012055) | Nov 25, 2025 |
| Lenovo        | V480 20143                  | Notebook    | [8a0c37dafd](https://linux-hardware.org/?probe=8a0c37dafd) | Nov 25, 2025 |
| Intel         | H55                         | Desktop     | [64547cb270](https://linux-hardware.org/?probe=64547cb270) | Nov 24, 2025 |
| Intel         | H55                         | Desktop     | [03919b1a0c](https://linux-hardware.org/?probe=03919b1a0c) | Nov 22, 2025 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [b3cefcb6a7](https://linux-hardware.org/?probe=b3cefcb6a7) | Nov 20, 2025 |
| HP            | ZBook 17 G4                 | Notebook    | [e61593dc31](https://linux-hardware.org/?probe=e61593dc31) | Nov 18, 2025 |
| Toshiba       | Satellite L745              | Notebook    | [b232141360](https://linux-hardware.org/?probe=b232141360) | Nov 17, 2025 |
| Toshiba       | Satellite L745              | Notebook    | [011f3387b2](https://linux-hardware.org/?probe=011f3387b2) | Nov 17, 2025 |
| Lenovo        | ThinkCentre Edge 71z 756... | Desktop     | [f53fa15a0e](https://linux-hardware.org/?probe=f53fa15a0e) | Nov 17, 2025 |
| Lenovo        | G410 20237                  | Notebook    | [0ddda52f91](https://linux-hardware.org/?probe=0ddda52f91) | Nov 17, 2025 |
| AXIOO         | MyBook Hype 5 AMD X5-2      | Notebook    | [1448aae1d0](https://linux-hardware.org/?probe=1448aae1d0) | Nov 17, 2025 |
| Lenovo        | G400 20235                  | Notebook    | [86e661ab78](https://linux-hardware.org/?probe=86e661ab78) | Nov 16, 2025 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [5ae1007d4c](https://linux-hardware.org/?probe=5ae1007d4c) | Nov 16, 2025 |
| ASUSTek       | GL553VD                     | Notebook    | [4366c9b128](https://linux-hardware.org/?probe=4366c9b128) | Nov 16, 2025 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [ff75f1410a](https://linux-hardware.org/?probe=ff75f1410a) | Nov 13, 2025 |
| ASUSTek       | Z97-A                       | Desktop     | [f6694986c9](https://linux-hardware.org/?probe=f6694986c9) | Nov 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [46aaf99b53](https://linux-hardware.org/?probe=46aaf99b53) | Nov 13, 2025 |
| venomRX       | H110 Ver:2.3                | Desktop     | [2348395742](https://linux-hardware.org/?probe=2348395742) | Nov 10, 2025 |
| Chuwi         | CW129-6 N150 V2             | Notebook    | [c426ba6944](https://linux-hardware.org/?probe=c426ba6944) | Nov 09, 2025 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [abadf600da](https://linux-hardware.org/?probe=abadf600da) | Nov 09, 2025 |
| ASUSTek       | X456URK                     | Notebook    | [91b2017dcd](https://linux-hardware.org/?probe=91b2017dcd) | Nov 07, 2025 |
| Apple         | MacBookAir4,1               | Notebook    | [5d609070cc](https://linux-hardware.org/?probe=5d609070cc) | Nov 06, 2025 |
| Apple         | MacBookAir4,1               | Notebook    | [ff75c1bc57](https://linux-hardware.org/?probe=ff75c1bc57) | Nov 06, 2025 |
| ASUSTek       | X441UV                      | Notebook    | [b29a5b208c](https://linux-hardware.org/?probe=b29a5b208c) | Nov 05, 2025 |
| Acer          | Nitro AN515-43              | Notebook    | [8f3615fe5b](https://linux-hardware.org/?probe=8f3615fe5b) | Nov 04, 2025 |
| Acer          | Nitro AN515-43              | Notebook    | [b3defe8e86](https://linux-hardware.org/?probe=b3defe8e86) | Nov 04, 2025 |
| Gigabyte      | H610M K DDR4                | Desktop     | [bff6aa9159](https://linux-hardware.org/?probe=bff6aa9159) | Nov 04, 2025 |
| Toshiba       | Satellite E105              | Notebook    | [034c60fabc](https://linux-hardware.org/?probe=034c60fabc) | Nov 03, 2025 |
| Unknown       | Unknown                     | Notebook    | [3b8403f9b4](https://linux-hardware.org/?probe=3b8403f9b4) | Nov 03, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0b0f0dad70](https://linux-hardware.org/?probe=0b0f0dad70) | Nov 02, 2025 |
| HP            | 1000                        | Notebook    | [91a4fe900f](https://linux-hardware.org/?probe=91a4fe900f) | Nov 01, 2025 |
| eMachines     | D725                        | Notebook    | [ba8479b330](https://linux-hardware.org/?probe=ba8479b330) | Oct 30, 2025 |
| Lenovo        | ThinkPad T480s 20L8S7GR0... | Notebook    | [a17031c704](https://linux-hardware.org/?probe=a17031c704) | Oct 30, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [35d7e93da4](https://linux-hardware.org/?probe=35d7e93da4) | Oct 30, 2025 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [9182e04f2c](https://linux-hardware.org/?probe=9182e04f2c) | Oct 30, 2025 |
| Biostar       | H61MLV2                     | Desktop     | [0734a3ade7](https://linux-hardware.org/?probe=0734a3ade7) | Oct 30, 2025 |
| ASRock        | AB350 Pro4                  | Desktop     | [682ad03729](https://linux-hardware.org/?probe=682ad03729) | Oct 30, 2025 |
| Acer          | Aspire 4739                 | Notebook    | [2e5855bdc6](https://linux-hardware.org/?probe=2e5855bdc6) | Oct 29, 2025 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [c5faaa4ca3](https://linux-hardware.org/?probe=c5faaa4ca3) | Oct 29, 2025 |
| wolfNfox c... | H55MXV-LE                   | Desktop     | [135c10fb45](https://linux-hardware.org/?probe=135c10fb45) | Oct 29, 2025 |
| Acer          | Swift SF314-510G            | Notebook    | [c30b00e2a0](https://linux-hardware.org/?probe=c30b00e2a0) | Oct 29, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [c10798b834](https://linux-hardware.org/?probe=c10798b834) | Oct 29, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [acc11e1382](https://linux-hardware.org/?probe=acc11e1382) | Oct 29, 2025 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [72691340c6](https://linux-hardware.org/?probe=72691340c6) | Oct 27, 2025 |
| ASUSTek       | X202E                       | Notebook    | [9b8fc2455a](https://linux-hardware.org/?probe=9b8fc2455a) | Oct 27, 2025 |
| Chuwi         | CW129-6 N150 V2             | Notebook    | [82b2ab89b0](https://linux-hardware.org/?probe=82b2ab89b0) | Oct 26, 2025 |
| Acer          | Aspire 4750                 | Notebook    | [f271528881](https://linux-hardware.org/?probe=f271528881) | Oct 24, 2025 |
| HP            | EliteBook 820 G3            | Notebook    | [ec41a82e08](https://linux-hardware.org/?probe=ec41a82e08) | Oct 23, 2025 |
| Toshiba       | dynabook VC72/M             | Convertible | [2e4685b1a3](https://linux-hardware.org/?probe=2e4685b1a3) | Oct 22, 2025 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6e3aefbe66](https://linux-hardware.org/?probe=6e3aefbe66) | Oct 22, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [f88e766ff4](https://linux-hardware.org/?probe=f88e766ff4) | Oct 21, 2025 |
| MSI           | H310M PRO-VD                | Desktop     | [5cef1d2379](https://linux-hardware.org/?probe=5cef1d2379) | Oct 21, 2025 |
| Intel         | H55                         | Desktop     | [595a9670e0](https://linux-hardware.org/?probe=595a9670e0) | Oct 20, 2025 |
| Acer          | Aspire E5-471               | Notebook    | [e080b5f1c5](https://linux-hardware.org/?probe=e080b5f1c5) | Oct 20, 2025 |
| HP            | Laptop 14 dq5115TU          | Notebook    | [cad11b3a38](https://linux-hardware.org/?probe=cad11b3a38) | Oct 20, 2025 |
| Acer          | Aspire E5-471               | Notebook    | [088c6bf421](https://linux-hardware.org/?probe=088c6bf421) | Oct 20, 2025 |
| ADVAN         | 1701                        | Notebook    | [816fa2260a](https://linux-hardware.org/?probe=816fa2260a) | Oct 20, 2025 |
| Dell          | Vostro 14-5459              | Notebook    | [8e208ddc35](https://linux-hardware.org/?probe=8e208ddc35) | Oct 18, 2025 |
| Lenovo        | IdeaPad Gaming 3-15ACH6 ... | Notebook    | [835e9bc751](https://linux-hardware.org/?probe=835e9bc751) | Oct 17, 2025 |
| HP            | 430                         | Notebook    | [bb6853a2e0](https://linux-hardware.org/?probe=bb6853a2e0) | Oct 17, 2025 |
| Lenovo        | ThinkPad T480 20L6SEYY00    | Notebook    | [dedd2b5651](https://linux-hardware.org/?probe=dedd2b5651) | Oct 17, 2025 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3fef4bd4f3](https://linux-hardware.org/?probe=3fef4bd4f3) | Oct 17, 2025 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [222d3d64fe](https://linux-hardware.org/?probe=222d3d64fe) | Oct 17, 2025 |
| Infinix       | BL51A5                      | Notebook    | [db66d02e7e](https://linux-hardware.org/?probe=db66d02e7e) | Oct 16, 2025 |
| ASUSTek       | X441SA                      | Notebook    | [0683121be4](https://linux-hardware.org/?probe=0683121be4) | Oct 15, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [fa42168a60](https://linux-hardware.org/?probe=fa42168a60) | Oct 15, 2025 |
| ASUSTek       | X441SA                      | Notebook    | [6f218e68a4](https://linux-hardware.org/?probe=6f218e68a4) | Oct 15, 2025 |
| Lenovo        | IdeaPad Slim 5 14AHP10 8... | Notebook    | [befa0f1de1](https://linux-hardware.org/?probe=befa0f1de1) | Oct 14, 2025 |
| Lenovo        | IdeaPad Slim 5 14AHP10 8... | Notebook    | [8763921c2b](https://linux-hardware.org/?probe=8763921c2b) | Oct 14, 2025 |
| LG Electro... | 15UD560-GX51K               | Notebook    | [705f9d66d7](https://linux-hardware.org/?probe=705f9d66d7) | Oct 13, 2025 |
| ASUSTek       | X200MA                      | Notebook    | [a33f07a4b8](https://linux-hardware.org/?probe=a33f07a4b8) | Oct 13, 2025 |
| ASUSTek       | X441BA                      | Notebook    | [a4d77e49ca](https://linux-hardware.org/?probe=a4d77e49ca) | Oct 13, 2025 |
| Lenovo        | V130-14IGM 81HM             | Notebook    | [122738a4fb](https://linux-hardware.org/?probe=122738a4fb) | Oct 13, 2025 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [6983035656](https://linux-hardware.org/?probe=6983035656) | Oct 12, 2025 |
| AXIOO         | Mybook Hype 5 AMD           | Notebook    | [7638cca9f5](https://linux-hardware.org/?probe=7638cca9f5) | Oct 12, 2025 |
| AXIOO         | Mybook Hype 5 AMD           | Notebook    | [bcabd89eee](https://linux-hardware.org/?probe=bcabd89eee) | Oct 12, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9f37fa48ac](https://linux-hardware.org/?probe=9f37fa48ac) | Oct 12, 2025 |
| Acer          | Aspire 4736Z                | Notebook    | [42f14c969f](https://linux-hardware.org/?probe=42f14c969f) | Oct 10, 2025 |
| Acer          | Aspire C22-1650             | All in one  | [bb2e992b12](https://linux-hardware.org/?probe=bb2e992b12) | Oct 10, 2025 |
| Dell          | Vostro 3400                 | Notebook    | [1e35f44928](https://linux-hardware.org/?probe=1e35f44928) | Oct 09, 2025 |
| Acer          | Veriton X2610               | Desktop     | [09c0b8ea84](https://linux-hardware.org/?probe=09c0b8ea84) | Oct 09, 2025 |
| HP            | Laptop 14-bs1xx             | Notebook    | [5d021986fd](https://linux-hardware.org/?probe=5d021986fd) | Oct 08, 2025 |
| ASUSTek       | X455LAB                     | Notebook    | [72b2e8230b](https://linux-hardware.org/?probe=72b2e8230b) | Oct 08, 2025 |
| HP            | Pavilion g4                 | Notebook    | [37aa765d83](https://linux-hardware.org/?probe=37aa765d83) | Oct 07, 2025 |
| Acer          | Nitro AN515-58              | Notebook    | [4b130ee2a3](https://linux-hardware.org/?probe=4b130ee2a3) | Oct 07, 2025 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [14fdc78a7b](https://linux-hardware.org/?probe=14fdc78a7b) | Oct 07, 2025 |
| ASUSTek       | X455LAB                     | Notebook    | [1443c76001](https://linux-hardware.org/?probe=1443c76001) | Oct 07, 2025 |
| HP            | 430                         | Notebook    | [7d4dbdd77d](https://linux-hardware.org/?probe=7d4dbdd77d) | Oct 05, 2025 |
| ASUSTek       | X455LD                      | Notebook    | [157c77ae3e](https://linux-hardware.org/?probe=157c77ae3e) | Oct 05, 2025 |
| Dell          | 045M96 A03                  | Server      | [20500c8675](https://linux-hardware.org/?probe=20500c8675) | Oct 05, 2025 |
| Lenovo        | V130-14IGM 81HM             | Notebook    | [bbbe41fd8d](https://linux-hardware.org/?probe=bbbe41fd8d) | Oct 04, 2025 |
| AXIOO         | Mybook Saga 10              | Notebook    | [24db04219f](https://linux-hardware.org/?probe=24db04219f) | Oct 04, 2025 |
| MSI           | Thin 15 B12UCX              | Notebook    | [1813ba8f32](https://linux-hardware.org/?probe=1813ba8f32) | Oct 03, 2025 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | Notebook    | [10d8ff1b44](https://linux-hardware.org/?probe=10d8ff1b44) | Oct 02, 2025 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | Notebook    | [1cafa83591](https://linux-hardware.org/?probe=1cafa83591) | Oct 02, 2025 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [5aa5cce5cd](https://linux-hardware.org/?probe=5aa5cce5cd) | Oct 02, 2025 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [1d16dda120](https://linux-hardware.org/?probe=1d16dda120) | Oct 01, 2025 |
| Dell          | G15 5515                    | Notebook    | [51886f045c](https://linux-hardware.org/?probe=51886f045c) | Oct 01, 2025 |
| Dell          | 0K06NC A00                  | All in one  | [968f9ed6d1](https://linux-hardware.org/?probe=968f9ed6d1) | Sep 30, 2025 |
| ASUSTek       | PRIME H510M-K R2.0          | Desktop     | [cb9b82619e](https://linux-hardware.org/?probe=cb9b82619e) | Sep 30, 2025 |
| ASRock        | X300M-STX                   | Desktop     | [9e206fc7cd](https://linux-hardware.org/?probe=9e206fc7cd) | Sep 30, 2025 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [c7f158e943](https://linux-hardware.org/?probe=c7f158e943) | Sep 28, 2025 |
| Dell          | 0JP3NX A01                  | Desktop     | [e9b36eaceb](https://linux-hardware.org/?probe=e9b36eaceb) | Sep 28, 2025 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [63ae8b394e](https://linux-hardware.org/?probe=63ae8b394e) | Sep 28, 2025 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [a417716168](https://linux-hardware.org/?probe=a417716168) | Sep 26, 2025 |
| MSI           | GL62M 7RDX                  | Notebook    | [714a237838](https://linux-hardware.org/?probe=714a237838) | Sep 26, 2025 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [34d252367d](https://linux-hardware.org/?probe=34d252367d) | Sep 26, 2025 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [3a0cff210e](https://linux-hardware.org/?probe=3a0cff210e) | Sep 26, 2025 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [213bfbf41e](https://linux-hardware.org/?probe=213bfbf41e) | Sep 26, 2025 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [c666c6e75e](https://linux-hardware.org/?probe=c666c6e75e) | Sep 26, 2025 |
| ASUSTek       | X441UV                      | Notebook    | [be09cfdb07](https://linux-hardware.org/?probe=be09cfdb07) | Sep 25, 2025 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [a00b5767de](https://linux-hardware.org/?probe=a00b5767de) | Sep 25, 2025 |
| Gigabyte      | G31M-S2L                    | Desktop     | [62cd36d091](https://linux-hardware.org/?probe=62cd36d091) | Sep 24, 2025 |
| Gigabyte      | G31M-S2L                    | Desktop     | [8c8c16ac10](https://linux-hardware.org/?probe=8c8c16ac10) | Sep 24, 2025 |
| AXIOO         | MyBook Z10 Metal            | Notebook    | [9965f4c890](https://linux-hardware.org/?probe=9965f4c890) | Sep 24, 2025 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [b8920b2f12](https://linux-hardware.org/?probe=b8920b2f12) | Sep 22, 2025 |
| ONERugged     | P10J                        | Tablet      | [6c7d053405](https://linux-hardware.org/?probe=6c7d053405) | Sep 22, 2025 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [69efd2f0c9](https://linux-hardware.org/?probe=69efd2f0c9) | Sep 21, 2025 |
| Dell          | Latitude E5450              | Notebook    | [ab4352584d](https://linux-hardware.org/?probe=ab4352584d) | Sep 21, 2025 |
| Lenovo        | ThinkPad T480 20L6SANC00    | Notebook    | [44fcc0df08](https://linux-hardware.org/?probe=44fcc0df08) | Sep 20, 2025 |
| Acer          | Aspire A314-22              | Notebook    | [897c4e7883](https://linux-hardware.org/?probe=897c4e7883) | Sep 20, 2025 |
| HP            | ZBook 15u G3                | Notebook    | [d057cfb420](https://linux-hardware.org/?probe=d057cfb420) | Sep 19, 2025 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [3028daad06](https://linux-hardware.org/?probe=3028daad06) | Sep 18, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [72d601839b](https://linux-hardware.org/?probe=72d601839b) | Sep 17, 2025 |
| Dell          | Latitude E6420              | Notebook    | [a8f5f255ee](https://linux-hardware.org/?probe=a8f5f255ee) | Sep 16, 2025 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [86e7353b2f](https://linux-hardware.org/?probe=86e7353b2f) | Sep 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [620a2c48d4](https://linux-hardware.org/?probe=620a2c48d4) | Sep 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [8ccfbf33fc](https://linux-hardware.org/?probe=8ccfbf33fc) | Sep 15, 2025 |
| HUAWEI        | FLMH-XX                     | Notebook    | [b30618441a](https://linux-hardware.org/?probe=b30618441a) | Sep 14, 2025 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [75ea035104](https://linux-hardware.org/?probe=75ea035104) | Sep 14, 2025 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [66f28131b4](https://linux-hardware.org/?probe=66f28131b4) | Sep 14, 2025 |
| Huanan        | X79 V2.5 249PC              | Desktop     | [8cd7c91d90](https://linux-hardware.org/?probe=8cd7c91d90) | Sep 14, 2025 |
| Sony          | SVF14212SGW                 | Notebook    | [2eb7602989](https://linux-hardware.org/?probe=2eb7602989) | Sep 12, 2025 |
| ASUSTek       | K84L                        | Notebook    | [3bac93e134](https://linux-hardware.org/?probe=3bac93e134) | Sep 11, 2025 |
| HP            | Laptop 14-em0xxx            | Notebook    | [7776d88938](https://linux-hardware.org/?probe=7776d88938) | Sep 10, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a1d9f854da](https://linux-hardware.org/?probe=a1d9f854da) | Sep 09, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7d7de94b2b](https://linux-hardware.org/?probe=7d7de94b2b) | Sep 09, 2025 |
| Acer          | Swift SFX14-41G             | Notebook    | [75869e2995](https://linux-hardware.org/?probe=75869e2995) | Sep 09, 2025 |
| Acer          | Swift SFX14-41G             | Notebook    | [be453416cd](https://linux-hardware.org/?probe=be453416cd) | Sep 09, 2025 |
| Huanan        | X79 V2.5 249PC              | Desktop     | [ecfd63e31b](https://linux-hardware.org/?probe=ecfd63e31b) | Sep 08, 2025 |
| ADVAN         | 1701                        | Notebook    | [15b92e24bb](https://linux-hardware.org/?probe=15b92e24bb) | Sep 07, 2025 |
| Acer          | Nitro AN515-58              | Notebook    | [b27cbe72b6](https://linux-hardware.org/?probe=b27cbe72b6) | Sep 07, 2025 |
| OEM           | X79G                        | Desktop     | [5958169308](https://linux-hardware.org/?probe=5958169308) | Sep 04, 2025 |
| ASUSTek       | X456URK                     | Notebook    | [63cca1412e](https://linux-hardware.org/?probe=63cca1412e) | Sep 04, 2025 |
| Lenovo        | G40-45 80E1                 | Notebook    | [90b8eaaed1](https://linux-hardware.org/?probe=90b8eaaed1) | Sep 02, 2025 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [8e741cb158](https://linux-hardware.org/?probe=8e741cb158) | Sep 01, 2025 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [a8850ffd5c](https://linux-hardware.org/?probe=a8850ffd5c) | Aug 31, 2025 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [ad7e485eb4](https://linux-hardware.org/?probe=ad7e485eb4) | Aug 29, 2025 |
| TECNO Mobi... | MEGABOOK T14DA              | Notebook    | [9b8f06e699](https://linux-hardware.org/?probe=9b8f06e699) | Aug 26, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [74c9a329e3](https://linux-hardware.org/?probe=74c9a329e3) | Aug 26, 2025 |
| MSI           | Modern 14 C7M               | Notebook    | [798ffdf8f2](https://linux-hardware.org/?probe=798ffdf8f2) | Aug 25, 2025 |
| Lenovo        | ThinkPad L570 20J9S34000    | Notebook    | [633076c1ea](https://linux-hardware.org/?probe=633076c1ea) | Aug 25, 2025 |
| Gigabyte      | EG45M-UD2H                  | Desktop     | [fe37eae13a](https://linux-hardware.org/?probe=fe37eae13a) | Aug 25, 2025 |
| Acer          | Aspire E5-552G              | Notebook    | [89d664e6ce](https://linux-hardware.org/?probe=89d664e6ce) | Aug 24, 2025 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [97b5af9278](https://linux-hardware.org/?probe=97b5af9278) | Aug 23, 2025 |
| GPD           | G1622-01                    | Notebook    | [8430a9bd3b](https://linux-hardware.org/?probe=8430a9bd3b) | Aug 23, 2025 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [f6e20d76e2](https://linux-hardware.org/?probe=f6e20d76e2) | Aug 23, 2025 |
| Lenovo        | G40-45 80E1                 | Notebook    | [e5dd58fca6](https://linux-hardware.org/?probe=e5dd58fca6) | Aug 23, 2025 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [a80e84712a](https://linux-hardware.org/?probe=a80e84712a) | Aug 23, 2025 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [62649034ac](https://linux-hardware.org/?probe=62649034ac) | Aug 22, 2025 |
| HP            | ProBook 440 G2              | Notebook    | [6e73779cc7](https://linux-hardware.org/?probe=6e73779cc7) | Aug 22, 2025 |
| HP            | ProBook 440 G2              | Notebook    | [220639ed23](https://linux-hardware.org/?probe=220639ed23) | Aug 22, 2025 |
| Acer          | Aspire A315-41              | Notebook    | [27691e29c2](https://linux-hardware.org/?probe=27691e29c2) | Aug 22, 2025 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [77ae7d891a](https://linux-hardware.org/?probe=77ae7d891a) | Aug 21, 2025 |
| Lenovo        | ThinkPad T480 20L6SDR207    | Notebook    | [7fc8ddc002](https://linux-hardware.org/?probe=7fc8ddc002) | Aug 20, 2025 |
| ECS           | H81H3-M4                    | Desktop     | [68017db36d](https://linux-hardware.org/?probe=68017db36d) | Aug 20, 2025 |
| ASUSTek       | ASUS EXPERTBOOK P1403CVA    | Notebook    | [e8de4e7c0d](https://linux-hardware.org/?probe=e8de4e7c0d) | Aug 18, 2025 |
| ASUSTek       | ASUS EXPERTBOOK P1403CVA    | Notebook    | [641eab3c98](https://linux-hardware.org/?probe=641eab3c98) | Aug 18, 2025 |
| Biostar       | H110MH PRO D4               | Desktop     | [17ec26f1c3](https://linux-hardware.org/?probe=17ec26f1c3) | Aug 18, 2025 |
| ASRock        | X600-ITX                    | Desktop     | [ded4cdf036](https://linux-hardware.org/?probe=ded4cdf036) | Aug 16, 2025 |
| MSI           | Modern 14 C11M              | Notebook    | [93de48aa18](https://linux-hardware.org/?probe=93de48aa18) | Aug 15, 2025 |
| Biostar       | G41D3+                      | Desktop     | [0fa7f0d0df](https://linux-hardware.org/?probe=0fa7f0d0df) | Aug 15, 2025 |
| ASRock        | H97M-ITX/ac                 | Desktop     | [d040318175](https://linux-hardware.org/?probe=d040318175) | Aug 15, 2025 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [3b1cb3b1fa](https://linux-hardware.org/?probe=3b1cb3b1fa) | Aug 15, 2025 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [8eab8248f4](https://linux-hardware.org/?probe=8eab8248f4) | Aug 14, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [5f0c65e41e](https://linux-hardware.org/?probe=5f0c65e41e) | Aug 12, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5e29a83715](https://linux-hardware.org/?probe=5e29a83715) | Aug 12, 2025 |
| HP            | 1589                        | Desktop     | [a8b28baa8a](https://linux-hardware.org/?probe=a8b28baa8a) | Aug 12, 2025 |
| Lenovo        | MIIX 510-12ISK 80U1         | Tablet      | [8484e6ba86](https://linux-hardware.org/?probe=8484e6ba86) | Aug 11, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [d89998f4ea](https://linux-hardware.org/?probe=d89998f4ea) | Aug 10, 2025 |
| Acer          | Aspire S3                   | Notebook    | [fe375f9016](https://linux-hardware.org/?probe=fe375f9016) | Aug 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [611e4e4fa5](https://linux-hardware.org/?probe=611e4e4fa5) | Aug 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [02f89efa37](https://linux-hardware.org/?probe=02f89efa37) | Aug 09, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [4bca717507](https://linux-hardware.org/?probe=4bca717507) | Aug 09, 2025 |
| Biostar       | NM70I-1037U                 | Desktop     | [371ec96c61](https://linux-hardware.org/?probe=371ec96c61) | Aug 07, 2025 |
| ASRock        | X570 PG Velocita            | Desktop     | [7877442c7b](https://linux-hardware.org/?probe=7877442c7b) | Aug 07, 2025 |
| Lenovo        | MIIX 510-12ISK 80U1         | Tablet      | [0a7e7c0317](https://linux-hardware.org/?probe=0a7e7c0317) | Aug 06, 2025 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [75d13cd9a4](https://linux-hardware.org/?probe=75d13cd9a4) | Aug 05, 2025 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [455b10eae6](https://linux-hardware.org/?probe=455b10eae6) | Aug 05, 2025 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [3b53da8f10](https://linux-hardware.org/?probe=3b53da8f10) | Aug 04, 2025 |
| ASUSTek       | X541NA                      | Notebook    | [2cce9c36ac](https://linux-hardware.org/?probe=2cce9c36ac) | Aug 04, 2025 |
| AZW           | GK55                        | Desktop     | [f01ba6fff6](https://linux-hardware.org/?probe=f01ba6fff6) | Aug 02, 2025 |
| HP            | EliteBook 840 G2            | Notebook    | [19ae00c613](https://linux-hardware.org/?probe=19ae00c613) | Aug 01, 2025 |
| ASUSTek       | ASUS Vivobook 14 X1407CA... | Notebook    | [0b2c8b1bfc](https://linux-hardware.org/?probe=0b2c8b1bfc) | Jul 31, 2025 |
| ASUSTek       | ASUS Vivobook 14 X1407CA... | Notebook    | [3630935316](https://linux-hardware.org/?probe=3630935316) | Jul 31, 2025 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [dc0ec33ceb](https://linux-hardware.org/?probe=dc0ec33ceb) | Jul 31, 2025 |
| ECS           | H81H3-M4                    | Desktop     | [a4ea413b68](https://linux-hardware.org/?probe=a4ea413b68) | Jul 31, 2025 |
| Acer          | Aspire A314-23M             | Notebook    | [34167df6dc](https://linux-hardware.org/?probe=34167df6dc) | Jul 29, 2025 |
| Acer          | Aspire A314-23M             | Notebook    | [30e41e9447](https://linux-hardware.org/?probe=30e41e9447) | Jul 29, 2025 |
| Wearnes       | MP6101-A1                   | Mini pc     | [1b6a3993a9](https://linux-hardware.org/?probe=1b6a3993a9) | Jul 29, 2025 |
| Lenovo        | IdeaPad Pro 5 14IRH8 83A... | Notebook    | [55e0584ba4](https://linux-hardware.org/?probe=55e0584ba4) | Jul 28, 2025 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [0dce015adf](https://linux-hardware.org/?probe=0dce015adf) | Jul 28, 2025 |
| ASUSTek       | ASUS Vivobook 14 X1407CA... | Notebook    | [a9890f2a78](https://linux-hardware.org/?probe=a9890f2a78) | Jul 24, 2025 |
| Dell          | Vostro 3400                 | Notebook    | [a4784a4cb0](https://linux-hardware.org/?probe=a4784a4cb0) | Jul 24, 2025 |
| Dell          | Vostro 3400                 | Notebook    | [3f95c1fa8a](https://linux-hardware.org/?probe=3f95c1fa8a) | Jul 24, 2025 |
| ASUSTek       | ASUS TUF Gaming F16 FX60... | Notebook    | [95ddbb14b1](https://linux-hardware.org/?probe=95ddbb14b1) | Jul 23, 2025 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [bced3c2fbc](https://linux-hardware.org/?probe=bced3c2fbc) | Jul 23, 2025 |
| Acer          | Swift SF314-54G             | Notebook    | [d394f4341a](https://linux-hardware.org/?probe=d394f4341a) | Jul 23, 2025 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [4fcd0b5188](https://linux-hardware.org/?probe=4fcd0b5188) | Jul 23, 2025 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [d9c49a08ae](https://linux-hardware.org/?probe=d9c49a08ae) | Jul 23, 2025 |
| HP            | Notebook                    | Notebook    | [ee92a5f469](https://linux-hardware.org/?probe=ee92a5f469) | Jul 21, 2025 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e249757bbe](https://linux-hardware.org/?probe=e249757bbe) | Jul 20, 2025 |
| Intel         | H81                         | Desktop     | [e273068f88](https://linux-hardware.org/?probe=e273068f88) | Jul 20, 2025 |
| Lenovo        | IdeaPad Pro 5 14IRH8 83A... | Notebook    | [125d6cc614](https://linux-hardware.org/?probe=125d6cc614) | Jul 18, 2025 |
| ASUSTek       | ASUS TUF Gaming F16 FX60... | Notebook    | [ac22e2b602](https://linux-hardware.org/?probe=ac22e2b602) | Jul 18, 2025 |
| HP            | EliteBook 840 G2            | Notebook    | [cf9ad678d8](https://linux-hardware.org/?probe=cf9ad678d8) | Jul 18, 2025 |
| Acer          | Aspire 4736Z                | Notebook    | [dabc715b77](https://linux-hardware.org/?probe=dabc715b77) | Jul 18, 2025 |
| ASUSTek       | X455LB                      | Notebook    | [ebafec1a79](https://linux-hardware.org/?probe=ebafec1a79) | Jul 15, 2025 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [713b7ea2a8](https://linux-hardware.org/?probe=713b7ea2a8) | Jul 15, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [11a8650c99](https://linux-hardware.org/?probe=11a8650c99) | Jul 15, 2025 |
| Lenovo        | ThinkPad T440p 20AWS14N0... | Notebook    | [17b9f8de92](https://linux-hardware.org/?probe=17b9f8de92) | Jul 14, 2025 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [6588b5b6d4](https://linux-hardware.org/?probe=6588b5b6d4) | Jul 14, 2025 |
| AXIOO         | PICO CJW                    | Notebook    | [b0cb4272e6](https://linux-hardware.org/?probe=b0cb4272e6) | Jul 12, 2025 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cfd7827fbd](https://linux-hardware.org/?probe=cfd7827fbd) | Jul 10, 2025 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [d0703df082](https://linux-hardware.org/?probe=d0703df082) | Jul 10, 2025 |
| ASUSTek       | X450EA                      | Notebook    | [1ec63ddd6b](https://linux-hardware.org/?probe=1ec63ddd6b) | Jul 10, 2025 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [2d6a734012](https://linux-hardware.org/?probe=2d6a734012) | Jul 09, 2025 |
| ASUSTek       | ROG Flow Z13 GZ301VV_GZ3... | Tablet      | [98546ad1db](https://linux-hardware.org/?probe=98546ad1db) | Jul 08, 2025 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [7676ba3ef4](https://linux-hardware.org/?probe=7676ba3ef4) | Jul 06, 2025 |
| Lenovo        | VersaPro Type VB 20F5000... | Notebook    | [0a05f8b17f](https://linux-hardware.org/?probe=0a05f8b17f) | Jul 06, 2025 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [c85c55a67f](https://linux-hardware.org/?probe=c85c55a67f) | Jul 05, 2025 |
| Lenovo        | ThinkCentre M80 7493CTO     | Desktop     | [95d8736416](https://linux-hardware.org/?probe=95d8736416) | Jul 05, 2025 |
| Lenovo        | ThinkCentre M80 7493CTO     | Desktop     | [a3122f28fe](https://linux-hardware.org/?probe=a3122f28fe) | Jul 05, 2025 |
| Unknown       | G41 Series                  | Desktop     | [d1ececac79](https://linux-hardware.org/?probe=d1ececac79) | Jul 04, 2025 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [cf996d03fd](https://linux-hardware.org/?probe=cf996d03fd) | Jul 04, 2025 |
| ASUSTek       | VivoBook_ASUS Laptop X40... | Notebook    | [c64b8388a9](https://linux-hardware.org/?probe=c64b8388a9) | Jul 03, 2025 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [259d334a44](https://linux-hardware.org/?probe=259d334a44) | Jul 03, 2025 |
| ASUSTek       | X456URK                     | Notebook    | [74abf5c992](https://linux-hardware.org/?probe=74abf5c992) | Jul 03, 2025 |
| ADVAN         | 1701                        | Notebook    | [2bd256412d](https://linux-hardware.org/?probe=2bd256412d) | Jul 03, 2025 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [1191422502](https://linux-hardware.org/?probe=1191422502) | Jul 03, 2025 |
| Dell          | Inspiron 3476               | Notebook    | [17f82bb049](https://linux-hardware.org/?probe=17f82bb049) | Jul 03, 2025 |
| Samsung       | 275E4E/275E5E               | Notebook    | [fea54302aa](https://linux-hardware.org/?probe=fea54302aa) | Jul 02, 2025 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [1e23e51afa](https://linux-hardware.org/?probe=1e23e51afa) | Jul 01, 2025 |
| ASUSTek       | N56VZ                       | Notebook    | [b5e6c9e8bf](https://linux-hardware.org/?probe=b5e6c9e8bf) | Jul 01, 2025 |
| ASUSTek       | ASUS Vivobook 14 X1407CA... | Notebook    | [348b8ad0dd](https://linux-hardware.org/?probe=348b8ad0dd) | Jul 01, 2025 |
| ASUSTek       | ASUS Vivobook 14 X1407CA... | Notebook    | [2558c00155](https://linux-hardware.org/?probe=2558c00155) | Jul 01, 2025 |
| Acer          | Okinawa                     | Notebook    | [7c6e80c9ac](https://linux-hardware.org/?probe=7c6e80c9ac) | Jun 29, 2025 |
| Dell          | Latitude 3350               | Notebook    | [b90cb489b8](https://linux-hardware.org/?probe=b90cb489b8) | Jun 28, 2025 |
| Acer          | Okinawa                     | Notebook    | [f2e686b05e](https://linux-hardware.org/?probe=f2e686b05e) | Jun 28, 2025 |
| ZOTAC         | ZBOX-ID18                   | Mini pc     | [a7dd1b1a63](https://linux-hardware.org/?probe=a7dd1b1a63) | Jun 27, 2025 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [243d96316d](https://linux-hardware.org/?probe=243d96316d) | Jun 27, 2025 |
| Acer          | Aspire 4352                 | Notebook    | [1cfa5c181c](https://linux-hardware.org/?probe=1cfa5c181c) | Jun 26, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [a4617fce7c](https://linux-hardware.org/?probe=a4617fce7c) | Jun 26, 2025 |
| ADVAN         | 1405                        | Notebook    | [63e8c5aecd](https://linux-hardware.org/?probe=63e8c5aecd) | Jun 26, 2025 |
| ADVAN         | 1701                        | Notebook    | [1ad4e3ac03](https://linux-hardware.org/?probe=1ad4e3ac03) | Jun 25, 2025 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [479129589e](https://linux-hardware.org/?probe=479129589e) | Jun 24, 2025 |
| Lenovo        | ThinkPad X1 Tablet Gen 2... | Tablet      | [5ae9e57e92](https://linux-hardware.org/?probe=5ae9e57e92) | Jun 24, 2025 |
| Acer          | Aspire 4750                 | Notebook    | [6457946093](https://linux-hardware.org/?probe=6457946093) | Jun 24, 2025 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [bf5ca69298](https://linux-hardware.org/?probe=bf5ca69298) | Jun 23, 2025 |
| TongFang      | GM7TG0P                     | Notebook    | [2b851f2530](https://linux-hardware.org/?probe=2b851f2530) | Jun 23, 2025 |
| Lenovo        | MIIX 510-12ISK 80U1         | Tablet      | [25dc32b794](https://linux-hardware.org/?probe=25dc32b794) | Jun 23, 2025 |
| Dell          | 0M9KCM A02                  | Desktop     | [78f99f574d](https://linux-hardware.org/?probe=78f99f574d) | Jun 22, 2025 |
| Unknown       | Unknown                     | Desktop     | [cc3ce164fd](https://linux-hardware.org/?probe=cc3ce164fd) | Jun 22, 2025 |
| Unknown       | FP7R2AIO                    | All in one  | [a54b00f5cd](https://linux-hardware.org/?probe=a54b00f5cd) | Jun 22, 2025 |
| Lenovo        | ThinkPad X390 20Q1S43P2E    | Notebook    | [a3583cd3c3](https://linux-hardware.org/?probe=a3583cd3c3) | Jun 20, 2025 |
| Unknown       | Unknown                     | Desktop     | [7fe3380ec2](https://linux-hardware.org/?probe=7fe3380ec2) | Jun 19, 2025 |
| Lenovo        | 7X04CTO1WW                  | Server      | [c7f81b38c8](https://linux-hardware.org/?probe=c7f81b38c8) | Jun 19, 2025 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [c39de1b08f](https://linux-hardware.org/?probe=c39de1b08f) | Jun 19, 2025 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [1a83c73bac](https://linux-hardware.org/?probe=1a83c73bac) | Jun 19, 2025 |
| ASUSTek       | X200MA                      | Notebook    | [6008c9e02a](https://linux-hardware.org/?probe=6008c9e02a) | Jun 19, 2025 |
| ASUSTek       | X441UV                      | Notebook    | [bf009333e1](https://linux-hardware.org/?probe=bf009333e1) | Jun 19, 2025 |
| Minix         | H61M-USB3 V1.2              | Desktop     | [088e1ba23e](https://linux-hardware.org/?probe=088e1ba23e) | Jun 18, 2025 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [7bb3e85cb0](https://linux-hardware.org/?probe=7bb3e85cb0) | Jun 18, 2025 |
| ASUSTek       | X200MA                      | Notebook    | [4a7e2290d4](https://linux-hardware.org/?probe=4a7e2290d4) | Jun 17, 2025 |
| ASUSTek       | X441NA                      | Notebook    | [7f70e5dd3b](https://linux-hardware.org/?probe=7f70e5dd3b) | Jun 17, 2025 |
| ASUSTek       | X441NA                      | Notebook    | [b6e3c525bc](https://linux-hardware.org/?probe=b6e3c525bc) | Jun 17, 2025 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [24cf734da2](https://linux-hardware.org/?probe=24cf734da2) | Jun 17, 2025 |
| ASRock        | A320M-HDV                   | Desktop     | [bae2e7d24c](https://linux-hardware.org/?probe=bae2e7d24c) | Jun 17, 2025 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [6ac5a9b0a1](https://linux-hardware.org/?probe=6ac5a9b0a1) | Jun 16, 2025 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [d576f70089](https://linux-hardware.org/?probe=d576f70089) | Jun 16, 2025 |
| Valve         | Jupiter                     | Notebook    | [47dd52c87c](https://linux-hardware.org/?probe=47dd52c87c) | Jun 16, 2025 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [f4ded16ac9](https://linux-hardware.org/?probe=f4ded16ac9) | Jun 16, 2025 |
| ASRock        | A55M-DGS                    | Desktop     | [aa8d71e629](https://linux-hardware.org/?probe=aa8d71e629) | Jun 15, 2025 |
| ASRock        | A55M-DGS                    | Desktop     | [a05e676e6b](https://linux-hardware.org/?probe=a05e676e6b) | Jun 15, 2025 |
| HP            | 14                          | Notebook    | [57f7a3fd40](https://linux-hardware.org/?probe=57f7a3fd40) | Jun 15, 2025 |
| Acer          | Aspire E1-432               | Notebook    | [5549edc6d3](https://linux-hardware.org/?probe=5549edc6d3) | Jun 15, 2025 |
| ASRock        | X600M-STX                   | Desktop     | [6c8adb7e17](https://linux-hardware.org/?probe=6c8adb7e17) | Jun 14, 2025 |
| HP            | 2B12                        | Desktop     | [9db1d09a0c](https://linux-hardware.org/?probe=9db1d09a0c) | Jun 14, 2025 |
| Intel         | H81                         | Desktop     | [52fc48d200](https://linux-hardware.org/?probe=52fc48d200) | Jun 14, 2025 |
| Intel         | H81                         | Desktop     | [3ceefa5484](https://linux-hardware.org/?probe=3ceefa5484) | Jun 14, 2025 |
| Unknown       | Unknown                     | Phone       | [95c976bdbf](https://linux-hardware.org/?probe=95c976bdbf) | Jun 14, 2025 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [c8eb984098](https://linux-hardware.org/?probe=c8eb984098) | Jun 13, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [51a4b51015](https://linux-hardware.org/?probe=51a4b51015) | Jun 13, 2025 |
| Acer          | Aspire V5-431               | Notebook    | [1c9e332dbc](https://linux-hardware.org/?probe=1c9e332dbc) | Jun 13, 2025 |
| HP            | 2B12                        | Desktop     | [9104ec5154](https://linux-hardware.org/?probe=9104ec5154) | Jun 13, 2025 |
| Lenovo        | ThinkPad X260 20F5S3WQ00    | Notebook    | [a2a15b5c22](https://linux-hardware.org/?probe=a2a15b5c22) | Jun 12, 2025 |
| Acer          | Aspire E5-476G              | Notebook    | [462a95ea2b](https://linux-hardware.org/?probe=462a95ea2b) | Jun 12, 2025 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [636d7f49c9](https://linux-hardware.org/?probe=636d7f49c9) | Jun 12, 2025 |
| MSI           | H61M-P20                    | Desktop     | [7f9cdd1a0a](https://linux-hardware.org/?probe=7f9cdd1a0a) | Jun 12, 2025 |
| Acer          | Nitro ANV15-41              | Notebook    | [3f6117ade7](https://linux-hardware.org/?probe=3f6117ade7) | Jun 11, 2025 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0f94470fba](https://linux-hardware.org/?probe=0f94470fba) | Jun 11, 2025 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5d2dd59bb6](https://linux-hardware.org/?probe=5d2dd59bb6) | Jun 11, 2025 |
| Toshiba       | Satellite Pro C640          | Notebook    | [20f759c3cf](https://linux-hardware.org/?probe=20f759c3cf) | Jun 10, 2025 |
| Valve         | Jupiter                     | Notebook    | [629e8a9020](https://linux-hardware.org/?probe=629e8a9020) | Jun 09, 2025 |
| ASUSTek       | X441BA                      | Notebook    | [0a13a8fc83](https://linux-hardware.org/?probe=0a13a8fc83) | Jun 09, 2025 |
| MSI           | A520M PRO                   | Desktop     | [f0ae8405e4](https://linux-hardware.org/?probe=f0ae8405e4) | Jun 09, 2025 |
| MSI           | A520M PRO                   | Desktop     | [0c51e08e21](https://linux-hardware.org/?probe=0c51e08e21) | Jun 08, 2025 |
| Toshiba       | Satellite E105              | Notebook    | [a3925e3211](https://linux-hardware.org/?probe=a3925e3211) | Jun 08, 2025 |
| ASUSTek       | P8Z68-M PRO                 | Desktop     | [e69221ece9](https://linux-hardware.org/?probe=e69221ece9) | Jun 07, 2025 |
| Dell          | Inspiron N4030              | Notebook    | [ba5d9c40c0](https://linux-hardware.org/?probe=ba5d9c40c0) | Jun 06, 2025 |
| Dell          | Latitude 7300               | Notebook    | [70a3f25c10](https://linux-hardware.org/?probe=70a3f25c10) | Jun 06, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [420bcdc2da](https://linux-hardware.org/?probe=420bcdc2da) | Jun 05, 2025 |
| MSI           | A520M-A PRO                 | Desktop     | [466c464e29](https://linux-hardware.org/?probe=466c464e29) | Jun 05, 2025 |
| MSI           | A520M-A PRO                 | Desktop     | [78c1647ec6](https://linux-hardware.org/?probe=78c1647ec6) | Jun 05, 2025 |
| HP            | Compaq 421                  | Notebook    | [f4e65b6c45](https://linux-hardware.org/?probe=f4e65b6c45) | Jun 04, 2025 |
| Gigabyte      | H81M-DS2                    | Desktop     | [62a89f4408](https://linux-hardware.org/?probe=62a89f4408) | Jun 04, 2025 |
| Lenovo        | ThinkPad X270 INVA20H       | Notebook    | [8c40503755](https://linux-hardware.org/?probe=8c40503755) | Jun 04, 2025 |
| AIO           | DynaBook e5                 | Notebook    | [855ba5397d](https://linux-hardware.org/?probe=855ba5397d) | Jun 03, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [80bc590cfb](https://linux-hardware.org/?probe=80bc590cfb) | Jun 03, 2025 |
| Panasonic     | CFSZ6-2                     | Notebook    | [daa871d4e6](https://linux-hardware.org/?probe=daa871d4e6) | Jun 02, 2025 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [8b03641397](https://linux-hardware.org/?probe=8b03641397) | Jun 02, 2025 |
| Acer          | Aspire AL14-31P             | Notebook    | [907e9bfef3](https://linux-hardware.org/?probe=907e9bfef3) | Jun 02, 2025 |
| Infinix       | INBook X1                   | Notebook    | [855c20e909](https://linux-hardware.org/?probe=855c20e909) | Jun 02, 2025 |
| Infinix       | INBook X1                   | Notebook    | [4cfb0bd2cb](https://linux-hardware.org/?probe=4cfb0bd2cb) | Jun 02, 2025 |
| Lenovo        | ThinkPad X220 4291KS8       | Notebook    | [4e10cc0299](https://linux-hardware.org/?probe=4e10cc0299) | Jun 01, 2025 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [8435b7cbe0](https://linux-hardware.org/?probe=8435b7cbe0) | May 31, 2025 |
| Acer          | Aspire AL14-31P             | Notebook    | [c2f1838836](https://linux-hardware.org/?probe=c2f1838836) | May 31, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [a0e7d31a48](https://linux-hardware.org/?probe=a0e7d31a48) | May 31, 2025 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [ea969eb068](https://linux-hardware.org/?probe=ea969eb068) | May 30, 2025 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [ecb76b31b0](https://linux-hardware.org/?probe=ecb76b31b0) | May 30, 2025 |
| MSI           | Cyborg 15 A12VE             | Notebook    | [2170ee2b4c](https://linux-hardware.org/?probe=2170ee2b4c) | May 30, 2025 |
| HP            | Notebook                    | Notebook    | [a849a12e12](https://linux-hardware.org/?probe=a849a12e12) | May 30, 2025 |
| Timi          | RedmiBook 15                | Notebook    | [9459a5965e](https://linux-hardware.org/?probe=9459a5965e) | May 29, 2025 |
| Lenovo        | IdeaPad 310 80tu            | Notebook    | [68f9e2c0c6](https://linux-hardware.org/?probe=68f9e2c0c6) | May 28, 2025 |
| Toshiba       | NB305                       | Notebook    | [a13b17c106](https://linux-hardware.org/?probe=a13b17c106) | May 26, 2025 |
| Gigabyte      | X870I AORUS PRO ICE         | Desktop     | [96452e46ed](https://linux-hardware.org/?probe=96452e46ed) | May 25, 2025 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [aa2f9c861b](https://linux-hardware.org/?probe=aa2f9c861b) | May 24, 2025 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [9cc98bf67c](https://linux-hardware.org/?probe=9cc98bf67c) | May 24, 2025 |
| ASUSTek       | X441BA                      | Notebook    | [53f7fabf55](https://linux-hardware.org/?probe=53f7fabf55) | May 24, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [dd163f2e80](https://linux-hardware.org/?probe=dd163f2e80) | May 24, 2025 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [76cfc052c1](https://linux-hardware.org/?probe=76cfc052c1) | May 23, 2025 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [e9aa37fcbb](https://linux-hardware.org/?probe=e9aa37fcbb) | May 22, 2025 |
| Lenovo        | ThinkPad L440 20ASA02AJP    | Notebook    | [461cf575a8](https://linux-hardware.org/?probe=461cf575a8) | May 21, 2025 |
| AXIOO         | Mybook Hype 7 AMD           | Notebook    | [8c3bad3cf7](https://linux-hardware.org/?probe=8c3bad3cf7) | May 20, 2025 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [34c1816abc](https://linux-hardware.org/?probe=34c1816abc) | May 20, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [58fe5cd572](https://linux-hardware.org/?probe=58fe5cd572) | May 18, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [c291f7da79](https://linux-hardware.org/?probe=c291f7da79) | May 18, 2025 |
| ASRock        | B650M Pro RS                | Desktop     | [432d2c28eb](https://linux-hardware.org/?probe=432d2c28eb) | May 17, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [b25ad47d19](https://linux-hardware.org/?probe=b25ad47d19) | May 17, 2025 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [fec2df22cf](https://linux-hardware.org/?probe=fec2df22cf) | May 17, 2025 |
| Supermicro    | X11DPi-NT                   | Server      | [6eb10fd13d](https://linux-hardware.org/?probe=6eb10fd13d) | May 17, 2025 |
| Supermicro    | X11DPi-NT                   | Server      | [cd803f4581](https://linux-hardware.org/?probe=cd803f4581) | May 17, 2025 |
| MSI           | Modern 14 C11M              | Notebook    | [7a522477e0](https://linux-hardware.org/?probe=7a522477e0) | May 17, 2025 |
| ASUSTek       | VivoBook E14 E402WA         | Notebook    | [5a85174220](https://linux-hardware.org/?probe=5a85174220) | May 16, 2025 |
| Valve         | Jupiter                     | Notebook    | [c5b4390a30](https://linux-hardware.org/?probe=c5b4390a30) | May 16, 2025 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [87ec54a2d6](https://linux-hardware.org/?probe=87ec54a2d6) | May 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [766ffa0d8c](https://linux-hardware.org/?probe=766ffa0d8c) | May 15, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c35990d0ed](https://linux-hardware.org/?probe=c35990d0ed) | May 15, 2025 |
| HP            | ProBook 430 G5              | Notebook    | [9c40451ead](https://linux-hardware.org/?probe=9c40451ead) | May 14, 2025 |
| ASUSTek       | ASUS Zenbook 14 UM3406KA... | Notebook    | [c3744984ac](https://linux-hardware.org/?probe=c3744984ac) | May 14, 2025 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [ed2ba76ed3](https://linux-hardware.org/?probe=ed2ba76ed3) | May 13, 2025 |
| Lenovo        | ThinkPad X200 7454HT1       | Notebook    | [ed68d0db2b](https://linux-hardware.org/?probe=ed68d0db2b) | May 12, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [18c45d9af2](https://linux-hardware.org/?probe=18c45d9af2) | May 12, 2025 |
| HP            | ENVY 15                     | Notebook    | [e197feb61c](https://linux-hardware.org/?probe=e197feb61c) | May 11, 2025 |
| HP            | ENVY 15                     | Notebook    | [e34782c06a](https://linux-hardware.org/?probe=e34782c06a) | May 11, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [5a57d7a2a2](https://linux-hardware.org/?probe=5a57d7a2a2) | May 11, 2025 |
| Acer          | Aspire ES1-111M             | Notebook    | [d12ec9a3ac](https://linux-hardware.org/?probe=d12ec9a3ac) | May 10, 2025 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [4f8a3a8aa2](https://linux-hardware.org/?probe=4f8a3a8aa2) | May 10, 2025 |
| MSI           | H81M-E35                    | Desktop     | [decb9c4ffb](https://linux-hardware.org/?probe=decb9c4ffb) | May 10, 2025 |
| Lenovo        | ThinkPad X230 23252G8       | Notebook    | [acaf05119c](https://linux-hardware.org/?probe=acaf05119c) | May 09, 2025 |
| Lenovo        | ThinkPad X250 20CLS3SR00    | Notebook    | [27eb3a81fb](https://linux-hardware.org/?probe=27eb3a81fb) | May 09, 2025 |
| Lenovo        | ThinkPad L440 20ASA02AJP    | Notebook    | [1f29f0c825](https://linux-hardware.org/?probe=1f29f0c825) | May 08, 2025 |
| ASRock        | X300-ITX                    | Desktop     | [c65077f42d](https://linux-hardware.org/?probe=c65077f42d) | May 07, 2025 |
| ASUSTek       | N43SL                       | Notebook    | [4ecae1e703](https://linux-hardware.org/?probe=4ecae1e703) | May 07, 2025 |
| ECS           | A58F2P-M4                   | Desktop     | [f4d07adc5f](https://linux-hardware.org/?probe=f4d07adc5f) | May 07, 2025 |
| Lenovo        | ThinkPad Edge E130 3358A... | Notebook    | [2987fa1bca](https://linux-hardware.org/?probe=2987fa1bca) | May 07, 2025 |
| Lenovo        | ThinkPad Edge E130 3358A... | Notebook    | [664601b72c](https://linux-hardware.org/?probe=664601b72c) | May 07, 2025 |
| HP            | 2AF9                        | Desktop     | [01139226eb](https://linux-hardware.org/?probe=01139226eb) | May 07, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [805570f3b3](https://linux-hardware.org/?probe=805570f3b3) | May 06, 2025 |
| HP            | Laptop 14s-dq5xxx           | Notebook    | [5695e90635](https://linux-hardware.org/?probe=5695e90635) | May 05, 2025 |
| Dell          | 05XGC8 A01                  | Desktop     | [cf61f96f20](https://linux-hardware.org/?probe=cf61f96f20) | May 05, 2025 |
| ASUSTek       | X200MA                      | Notebook    | [9497c344d0](https://linux-hardware.org/?probe=9497c344d0) | May 05, 2025 |
| HP            | ProBook 4431s               | Notebook    | [232ae41018](https://linux-hardware.org/?probe=232ae41018) | May 04, 2025 |
| Dell          | Latitude E7240              | Notebook    | [5675883f51](https://linux-hardware.org/?probe=5675883f51) | May 04, 2025 |
| ASUSTek       | X456URK                     | Notebook    | [0eec2e45dc](https://linux-hardware.org/?probe=0eec2e45dc) | May 03, 2025 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [98bc76e5dd](https://linux-hardware.org/?probe=98bc76e5dd) | May 02, 2025 |
| Notebook      | V35x_6xSNC_SND_SNE          | Notebook    | [14877c99d4](https://linux-hardware.org/?probe=14877c99d4) | May 02, 2025 |
| Lenovo        | MIIX 510-12ISK 80U1         | Tablet      | [6cb68bf8d4](https://linux-hardware.org/?probe=6cb68bf8d4) | Apr 29, 2025 |
| Lenovo        | MIIX 510-12ISK 80U1         | Tablet      | [9204687cd6](https://linux-hardware.org/?probe=9204687cd6) | Apr 29, 2025 |
| Acer          | Aspire A311-31              | Notebook    | [cedfe14ccd](https://linux-hardware.org/?probe=cedfe14ccd) | Apr 28, 2025 |
| Acer          | Aspire 4352                 | Notebook    | [7f556d9723](https://linux-hardware.org/?probe=7f556d9723) | Apr 26, 2025 |
| Dell          | 05XGC8 A01                  | Desktop     | [728bd664c9](https://linux-hardware.org/?probe=728bd664c9) | Apr 26, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ef2fe40b12](https://linux-hardware.org/?probe=ef2fe40b12) | Apr 26, 2025 |
| ASUSTek       | H61M-E                      | Desktop     | [008f988fee](https://linux-hardware.org/?probe=008f988fee) | Apr 26, 2025 |
| Valve         | Jupiter                     | Notebook    | [9eb0bb5c51](https://linux-hardware.org/?probe=9eb0bb5c51) | Apr 25, 2025 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | Notebook    | [1dc4e43187](https://linux-hardware.org/?probe=1dc4e43187) | Apr 24, 2025 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [4ce999e211](https://linux-hardware.org/?probe=4ce999e211) | Apr 24, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [ce8ad0a2f6](https://linux-hardware.org/?probe=ce8ad0a2f6) | Apr 22, 2025 |
| Timi          | RedmiBook 15                | Notebook    | [aeaab1a00c](https://linux-hardware.org/?probe=aeaab1a00c) | Apr 22, 2025 |
| HP            | ProBook 4421s               | Notebook    | [02e93a1c9a](https://linux-hardware.org/?probe=02e93a1c9a) | Apr 21, 2025 |
| AZW           | SER V1.0                    | Mini pc     | [f37f32f339](https://linux-hardware.org/?probe=f37f32f339) | Apr 21, 2025 |
| HP            | ProBook 4421s               | Notebook    | [844511443f](https://linux-hardware.org/?probe=844511443f) | Apr 21, 2025 |
| ASRock        | B650M PG Lightning WiFi     | Desktop     | [10e2bb695d](https://linux-hardware.org/?probe=10e2bb695d) | Apr 20, 2025 |
| Intel         | H81                         | Desktop     | [bff4b4a5f0](https://linux-hardware.org/?probe=bff4b4a5f0) | Apr 19, 2025 |
| Valve         | Galileo                     | Notebook    | [5ef4ab2e74](https://linux-hardware.org/?probe=5ef4ab2e74) | Apr 19, 2025 |
| MSI           | PRO H410M-B                 | Desktop     | [6381e79779](https://linux-hardware.org/?probe=6381e79779) | Apr 19, 2025 |
| Lenovo        | ThinkPad T430 2349KYA       | Notebook    | [f5a9e045d0](https://linux-hardware.org/?probe=f5a9e045d0) | Apr 18, 2025 |
| Acer          | Switch SW512-52             | Tablet      | [cf612d9b2b](https://linux-hardware.org/?probe=cf612d9b2b) | Apr 18, 2025 |
| Acer          | Switch SW512-52             | Tablet      | [8984812481](https://linux-hardware.org/?probe=8984812481) | Apr 18, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [261cca5e2a](https://linux-hardware.org/?probe=261cca5e2a) | Apr 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e045bb43a0](https://linux-hardware.org/?probe=e045bb43a0) | Apr 17, 2025 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b11cb00993](https://linux-hardware.org/?probe=b11cb00993) | Apr 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [3750829c9f](https://linux-hardware.org/?probe=3750829c9f) | Apr 16, 2025 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [e990ae749c](https://linux-hardware.org/?probe=e990ae749c) | Apr 13, 2025 |
| Valve         | Jupiter                     | Notebook    | [b1ad9f7e94](https://linux-hardware.org/?probe=b1ad9f7e94) | Apr 12, 2025 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [9f8d68726c](https://linux-hardware.org/?probe=9f8d68726c) | Apr 10, 2025 |
| Lenovo        | ThinkPad T495 20NKS3BG00    | Notebook    | [41202c42b6](https://linux-hardware.org/?probe=41202c42b6) | Apr 09, 2025 |
| Acer          | Aspire A314-23M             | Notebook    | [82ea64b7db](https://linux-hardware.org/?probe=82ea64b7db) | Apr 08, 2025 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [cc4be36fd5](https://linux-hardware.org/?probe=cc4be36fd5) | Apr 08, 2025 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [ad5c3a2113](https://linux-hardware.org/?probe=ad5c3a2113) | Apr 08, 2025 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [534d396c5a](https://linux-hardware.org/?probe=534d396c5a) | Apr 07, 2025 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [a0641663a5](https://linux-hardware.org/?probe=a0641663a5) | Apr 07, 2025 |
| HUAWEI        | FLMH-XX                     | Notebook    | [197993e262](https://linux-hardware.org/?probe=197993e262) | Apr 07, 2025 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [1e8baeba0d](https://linux-hardware.org/?probe=1e8baeba0d) | Apr 04, 2025 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [9a8e1d8467](https://linux-hardware.org/?probe=9a8e1d8467) | Apr 03, 2025 |
| Acer          | Aspire A314-23M             | Notebook    | [d095497d41](https://linux-hardware.org/?probe=d095497d41) | Apr 01, 2025 |
| HP            | 2B12                        | Desktop     | [18bd7cffd2](https://linux-hardware.org/?probe=18bd7cffd2) | Apr 01, 2025 |
| HP            | 2B12                        | Desktop     | [d414420da7](https://linux-hardware.org/?probe=d414420da7) | Apr 01, 2025 |
| Apple         | Mac-F2268CC8                | All in one  | [3d625ffc73](https://linux-hardware.org/?probe=3d625ffc73) | Mar 31, 2025 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [22b8849be5](https://linux-hardware.org/?probe=22b8849be5) | Mar 30, 2025 |
| Apple         | Mac-F2268CC8                | All in one  | [6a32b0cd47](https://linux-hardware.org/?probe=6a32b0cd47) | Mar 30, 2025 |
| HP            | Pavilion 14                 | Notebook    | [a9d21edec0](https://linux-hardware.org/?probe=a9d21edec0) | Mar 29, 2025 |
| Acer          | Aspire A514-54G             | Notebook    | [06b79da9f2](https://linux-hardware.org/?probe=06b79da9f2) | Mar 28, 2025 |
| ASRock        | B850 Pro-A                  | Desktop     | [e00a642b77](https://linux-hardware.org/?probe=e00a642b77) | Mar 27, 2025 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [c9407cf6b9](https://linux-hardware.org/?probe=c9407cf6b9) | Mar 27, 2025 |
| Dell          | Latitude 5400               | Notebook    | [c295b72bb1](https://linux-hardware.org/?probe=c295b72bb1) | Mar 25, 2025 |
| Acer          | Swift SF514-56T             | Notebook    | [376d808ffb](https://linux-hardware.org/?probe=376d808ffb) | Mar 25, 2025 |
| ASUSTek       | X456URK                     | Notebook    | [920a36ab33](https://linux-hardware.org/?probe=920a36ab33) | Mar 24, 2025 |
| ASUSTek       | X456URK                     | Notebook    | [b0b0ae7d96](https://linux-hardware.org/?probe=b0b0ae7d96) | Mar 24, 2025 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ed811aaa91](https://linux-hardware.org/?probe=ed811aaa91) | Mar 23, 2025 |
| Infinix       | INBook X1                   | Notebook    | [de6846871e](https://linux-hardware.org/?probe=de6846871e) | Mar 20, 2025 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [8e2160523e](https://linux-hardware.org/?probe=8e2160523e) | Mar 19, 2025 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [95b3e4a4d2](https://linux-hardware.org/?probe=95b3e4a4d2) | Mar 19, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6cb52e57aa](https://linux-hardware.org/?probe=6cb52e57aa) | Mar 19, 2025 |
| HP            | EliteBook 840 G6            | Notebook    | [879e7669a3](https://linux-hardware.org/?probe=879e7669a3) | Mar 18, 2025 |
| Dell          | Latitude 3420               | Notebook    | [58e3679dda](https://linux-hardware.org/?probe=58e3679dda) | Mar 18, 2025 |
| Acer          | Swift SF314-52G             | Notebook    | [99eab0e279](https://linux-hardware.org/?probe=99eab0e279) | Mar 18, 2025 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [8429859090](https://linux-hardware.org/?probe=8429859090) | Mar 16, 2025 |
| Unknown       | Unknown                     | Phone       | [6bb833ad8b](https://linux-hardware.org/?probe=6bb833ad8b) | Mar 16, 2025 |
| Infinix       | INBook X1                   | Notebook    | [58b1fcaeeb](https://linux-hardware.org/?probe=58b1fcaeeb) | Mar 16, 2025 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [565514c44f](https://linux-hardware.org/?probe=565514c44f) | Mar 16, 2025 |
| Unknown       | Unknown                     | Tablet      | [262cc8fa80](https://linux-hardware.org/?probe=262cc8fa80) | Mar 15, 2025 |
| Biostar       | NM70I-1037U                 | Desktop     | [977c3a6e1c](https://linux-hardware.org/?probe=977c3a6e1c) | Mar 15, 2025 |
| MSI           | B350M GAMING PRO            | Desktop     | [c535df19f9](https://linux-hardware.org/?probe=c535df19f9) | Mar 14, 2025 |
| HP            | EliteBook 8470p             | Notebook    | [91f0194615](https://linux-hardware.org/?probe=91f0194615) | Mar 14, 2025 |
| MSI           | B350M GAMING PRO            | Desktop     | [9c52154899](https://linux-hardware.org/?probe=9c52154899) | Mar 13, 2025 |
| Lenovo        | ThinkPad P50 20EQS3B302     | Notebook    | [8911174681](https://linux-hardware.org/?probe=8911174681) | Mar 13, 2025 |
| Lenovo        | ThinkPad P50 20EQS3B302     | Notebook    | [bbd0c73f77](https://linux-hardware.org/?probe=bbd0c73f77) | Mar 13, 2025 |
| HP            | ProBook 440 G6              | Notebook    | [b60ae271ce](https://linux-hardware.org/?probe=b60ae271ce) | Mar 13, 2025 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [172cb38c43](https://linux-hardware.org/?probe=172cb38c43) | Mar 12, 2025 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [143658c6f9](https://linux-hardware.org/?probe=143658c6f9) | Mar 11, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [84bd4a8d2a](https://linux-hardware.org/?probe=84bd4a8d2a) | Mar 10, 2025 |
| Acer          | Aspire 4752                 | Notebook    | [51068a585b](https://linux-hardware.org/?probe=51068a585b) | Mar 10, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [ad919d59a0](https://linux-hardware.org/?probe=ad919d59a0) | Mar 10, 2025 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [d210722d1f](https://linux-hardware.org/?probe=d210722d1f) | Mar 09, 2025 |
| ASUSTek       | X441BA                      | Notebook    | [c4cb0d019f](https://linux-hardware.org/?probe=c4cb0d019f) | Mar 09, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [a52d2a4820](https://linux-hardware.org/?probe=a52d2a4820) | Mar 08, 2025 |
| ASRock        | H97M-ITX/ac                 | Desktop     | [db2721c3d7](https://linux-hardware.org/?probe=db2721c3d7) | Mar 08, 2025 |
| Microsoft     | Surface Pro 3               | Tablet      | [213e7255fe](https://linux-hardware.org/?probe=213e7255fe) | Mar 07, 2025 |
| Acer          | Aspire 4752                 | Notebook    | [0663065782](https://linux-hardware.org/?probe=0663065782) | Mar 07, 2025 |
| ASRock        | B550M Pro4                  | Desktop     | [e81dd45b5b](https://linux-hardware.org/?probe=e81dd45b5b) | Mar 07, 2025 |
| Dell          | 0K06NC A00                  | All in one  | [ed05114a0f](https://linux-hardware.org/?probe=ed05114a0f) | Mar 06, 2025 |
| Lenovo        | G40-70 20369                | Notebook    | [0054a03579](https://linux-hardware.org/?probe=0054a03579) | Mar 05, 2025 |
| Beelink       | Gemini X                    | Notebook    | [29918e8e6d](https://linux-hardware.org/?probe=29918e8e6d) | Mar 05, 2025 |
| Dell          | 0Y2MRG A00                  | Desktop     | [3ac332cfad](https://linux-hardware.org/?probe=3ac332cfad) | Mar 04, 2025 |
| MicroByte     | ezbook                      | Notebook    | [89116248d8](https://linux-hardware.org/?probe=89116248d8) | Mar 04, 2025 |
| Lenovo        | IdeaPad 3 14IAU7 82RJ       | Notebook    | [517a0b0bf8](https://linux-hardware.org/?probe=517a0b0bf8) | Mar 03, 2025 |
| Gigabyte      | EG45M-UD2H                  | Desktop     | [d5a11f8862](https://linux-hardware.org/?probe=d5a11f8862) | Mar 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [6390659ba5](https://linux-hardware.org/?probe=6390659ba5) | Mar 02, 2025 |
| Lenovo        | ThinkPad A285 20MXS05R00    | Notebook    | [7f3bfb696b](https://linux-hardware.org/?probe=7f3bfb696b) | Mar 02, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ce55426d2b](https://linux-hardware.org/?probe=ce55426d2b) | Mar 01, 2025 |
| ASRock        | H410M-HVS R2.0              | Desktop     | [24a8d830bb](https://linux-hardware.org/?probe=24a8d830bb) | Mar 01, 2025 |
| ASRock        | H410M-HVS R2.0              | Desktop     | [48a3900cf6](https://linux-hardware.org/?probe=48a3900cf6) | Mar 01, 2025 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [ff834a6c4e](https://linux-hardware.org/?probe=ff834a6c4e) | Feb 28, 2025 |
| Google        | Vorticon                    | Notebook    | [92174303aa](https://linux-hardware.org/?probe=92174303aa) | Feb 28, 2025 |
| Google        | Vorticon                    | Notebook    | [ae7a4cd94f](https://linux-hardware.org/?probe=ae7a4cd94f) | Feb 28, 2025 |
| Lenovo        | ThinkPad E480 20KNA013CD    | Notebook    | [c33d4162e2](https://linux-hardware.org/?probe=c33d4162e2) | Feb 28, 2025 |
| Acer          | Aspire V5-471G              | Notebook    | [21097ec090](https://linux-hardware.org/?probe=21097ec090) | Feb 27, 2025 |
| System76      | Oryx Pro                    | Notebook    | [bfe3a1e66b](https://linux-hardware.org/?probe=bfe3a1e66b) | Feb 27, 2025 |
| ECS           | A320AM4-M3D/3.x/5.x         | Desktop     | [0bfd20edd7](https://linux-hardware.org/?probe=0bfd20edd7) | Feb 27, 2025 |
| Lenovo        | ThinkPad X220 42915L1       | Notebook    | [fb282a1f45](https://linux-hardware.org/?probe=fb282a1f45) | Feb 27, 2025 |
| Lenovo        | ThinkPad Yoga 370 20JJS2... | Convertible | [8ec49c9627](https://linux-hardware.org/?probe=8ec49c9627) | Feb 26, 2025 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d34875b43e](https://linux-hardware.org/?probe=d34875b43e) | Feb 26, 2025 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [60690258de](https://linux-hardware.org/?probe=60690258de) | Feb 26, 2025 |
| Lenovo        | ThinkPad X13s Gen 1 21BX... | Notebook    | [b08087034f](https://linux-hardware.org/?probe=b08087034f) | Feb 25, 2025 |
| Lenovo        | ThinkPad X13s Gen 1 21BX... | Notebook    | [c173ec8466](https://linux-hardware.org/?probe=c173ec8466) | Feb 25, 2025 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0a17a6d4eb](https://linux-hardware.org/?probe=0a17a6d4eb) | Feb 25, 2025 |
| Lenovo        | B450 1S168003694001K        | Notebook    | [3a899614a8](https://linux-hardware.org/?probe=3a899614a8) | Feb 25, 2025 |
| Lenovo        | IdeaPad Pro 5 14IRH8 83A... | Notebook    | [669fb284db](https://linux-hardware.org/?probe=669fb284db) | Feb 25, 2025 |
| MSI           | Cyborg 15 A12VE             | Notebook    | [abd55d12f9](https://linux-hardware.org/?probe=abd55d12f9) | Feb 24, 2025 |
| Microsoft     | Surface Pro 3               | Tablet      | [10ab0fc3d0](https://linux-hardware.org/?probe=10ab0fc3d0) | Feb 23, 2025 |
| Pegatron      | H24Z                        | Notebook    | [7ca6696e41](https://linux-hardware.org/?probe=7ca6696e41) | Feb 23, 2025 |
| MSI           | B450M-A PRO MAX             | Desktop     | [cc0ca34cd1](https://linux-hardware.org/?probe=cc0ca34cd1) | Feb 23, 2025 |
| ASUSTek       | ASUS P1412CEA_P1412CEA      | Notebook    | [f2c7a0de85](https://linux-hardware.org/?probe=f2c7a0de85) | Feb 22, 2025 |
| HP            | 1000                        | Notebook    | [3e9ea94616](https://linux-hardware.org/?probe=3e9ea94616) | Feb 22, 2025 |
| Acer          | Nitro AN515-58              | Notebook    | [948fe3275e](https://linux-hardware.org/?probe=948fe3275e) | Feb 22, 2025 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | Notebook    | [729a6cdc7f](https://linux-hardware.org/?probe=729a6cdc7f) | Feb 21, 2025 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | Notebook    | [2841edca44](https://linux-hardware.org/?probe=2841edca44) | Feb 21, 2025 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [59e3b32227](https://linux-hardware.org/?probe=59e3b32227) | Feb 20, 2025 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [3e87ea3249](https://linux-hardware.org/?probe=3e87ea3249) | Feb 20, 2025 |
| ADVAN         | 1701                        | Notebook    | [87ab532970](https://linux-hardware.org/?probe=87ab532970) | Feb 20, 2025 |
| ADVAN         | 1701                        | Notebook    | [3041f37c41](https://linux-hardware.org/?probe=3041f37c41) | Feb 20, 2025 |
| PC Partner... | A236 0A                     | Desktop     | [fd354b0204](https://linux-hardware.org/?probe=fd354b0204) | Feb 17, 2025 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ff4b955efc](https://linux-hardware.org/?probe=ff4b955efc) | Feb 16, 2025 |
| Infinix       | INBook X1 Pro               | Notebook    | [31d8d76e64](https://linux-hardware.org/?probe=31d8d76e64) | Feb 16, 2025 |
| Lenovo        | G40-45 80E1                 | Notebook    | [8ed3d96327](https://linux-hardware.org/?probe=8ed3d96327) | Feb 16, 2025 |
| PC Partner... | A236 0A                     | Desktop     | [f55a5da9f6](https://linux-hardware.org/?probe=f55a5da9f6) | Feb 15, 2025 |
| Intel         | B75                         | Desktop     | [18389eb77f](https://linux-hardware.org/?probe=18389eb77f) | Feb 15, 2025 |
| HP            | 212B                        | Desktop     | [6ba5de0521](https://linux-hardware.org/?probe=6ba5de0521) | Feb 15, 2025 |
| HP            | 212B                        | Desktop     | [5145984b7f](https://linux-hardware.org/?probe=5145984b7f) | Feb 15, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | Desktop     | [3ece699435](https://linux-hardware.org/?probe=3ece699435) | Feb 13, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | Desktop     | [282e5df271](https://linux-hardware.org/?probe=282e5df271) | Feb 13, 2025 |
| Dell          | 033FF6 A00                  | Desktop     | [c9ac06d36b](https://linux-hardware.org/?probe=c9ac06d36b) | Feb 13, 2025 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [738d0ac31e](https://linux-hardware.org/?probe=738d0ac31e) | Feb 13, 2025 |
| ADVAN         | 1701                        | Notebook    | [d878759b13](https://linux-hardware.org/?probe=d878759b13) | Feb 12, 2025 |
| Dell          | 033FF6 A00                  | Desktop     | [5be9faa359](https://linux-hardware.org/?probe=5be9faa359) | Feb 12, 2025 |
| HP            | 8704                        | Desktop     | [186e33f12e](https://linux-hardware.org/?probe=186e33f12e) | Feb 12, 2025 |
| PT Zyrexin... | Sky 232                     | Notebook    | [18461e2dfb](https://linux-hardware.org/?probe=18461e2dfb) | Feb 12, 2025 |
| Biostar       | B75MU3B                     | Desktop     | [8c0f562af1](https://linux-hardware.org/?probe=8c0f562af1) | Feb 11, 2025 |
| Lenovo        | ThinkPad R400 2784A48       | Notebook    | [eb04b141cb](https://linux-hardware.org/?probe=eb04b141cb) | Feb 11, 2025 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [ed96efb08a](https://linux-hardware.org/?probe=ed96efb08a) | Feb 10, 2025 |
| Dell          | 0WR7PY A00                  | Desktop     | [e3ae928c48](https://linux-hardware.org/?probe=e3ae928c48) | Feb 10, 2025 |
| Acer          | Swift SF314-511             | Notebook    | [4686c715f2](https://linux-hardware.org/?probe=4686c715f2) | Feb 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [c3eb22c6a6](https://linux-hardware.org/?probe=c3eb22c6a6) | Feb 08, 2025 |
| Acer          | Aspire A715-76G             | Notebook    | [24d7c1cdb0](https://linux-hardware.org/?probe=24d7c1cdb0) | Feb 08, 2025 |
| Acer          | Aspire A715-76G             | Notebook    | [a291e4250f](https://linux-hardware.org/?probe=a291e4250f) | Feb 08, 2025 |
| AXIOO         | MyPC One Pro K7-24          | All in one  | [8bd2eba618](https://linux-hardware.org/?probe=8bd2eba618) | Feb 08, 2025 |
| Lenovo        | ThinkPad L390 Yoga 20NUS... | Convertible | [f447de3a62](https://linux-hardware.org/?probe=f447de3a62) | Feb 07, 2025 |
| Pegatron      | H24Z                        | Notebook    | [3c81349f95](https://linux-hardware.org/?probe=3c81349f95) | Feb 06, 2025 |
| Unknown       | DS16                        | Notebook    | [3046e211c3](https://linux-hardware.org/?probe=3046e211c3) | Feb 04, 2025 |
| Dell          | Latitude 3410               | Notebook    | [274ab64912](https://linux-hardware.org/?probe=274ab64912) | Feb 04, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9e412f387b](https://linux-hardware.org/?probe=9e412f387b) | Feb 04, 2025 |
| Unknown       | DS16                        | Notebook    | [21f86f377f](https://linux-hardware.org/?probe=21f86f377f) | Feb 03, 2025 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [0654c79cbf](https://linux-hardware.org/?probe=0654c79cbf) | Feb 02, 2025 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [eaa235e5c0](https://linux-hardware.org/?probe=eaa235e5c0) | Feb 02, 2025 |
| Lenovo        | G40-45 80E1                 | Notebook    | [2e99c7e2bb](https://linux-hardware.org/?probe=2e99c7e2bb) | Feb 02, 2025 |
| Lenovo        | G40-45 80E1                 | Notebook    | [6d4bfb2e1a](https://linux-hardware.org/?probe=6d4bfb2e1a) | Feb 02, 2025 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [6cb7638c01](https://linux-hardware.org/?probe=6cb7638c01) | Feb 02, 2025 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2dcab89630](https://linux-hardware.org/?probe=2dcab89630) | Feb 01, 2025 |
| Toshiba       | Satellite E105              | Notebook    | [efaf43188f](https://linux-hardware.org/?probe=efaf43188f) | Jan 31, 2025 |
| Lenovo        | ThinkPad T480 20L6A080UK    | Notebook    | [e86d9e0be8](https://linux-hardware.org/?probe=e86d9e0be8) | Jan 31, 2025 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [e308b111ef](https://linux-hardware.org/?probe=e308b111ef) | Jan 31, 2025 |
| Lenovo        | V130-14IKB 81HQ             | Notebook    | [359e12ca0a](https://linux-hardware.org/?probe=359e12ca0a) | Jan 30, 2025 |
| MSI           | Thin 15 B12UCX              | Notebook    | [ae6e11a71c](https://linux-hardware.org/?probe=ae6e11a71c) | Jan 29, 2025 |
| Acer          | Aspire V5-132               | Notebook    | [e6dd3d6ec0](https://linux-hardware.org/?probe=e6dd3d6ec0) | Jan 27, 2025 |
| Dell          | 0D6H9T A02                  | Desktop     | [44dfc0cb6d](https://linux-hardware.org/?probe=44dfc0cb6d) | Jan 27, 2025 |
| HP            | ProBook 4421s               | Notebook    | [3ad7223dbf](https://linux-hardware.org/?probe=3ad7223dbf) | Jan 26, 2025 |
| HP            | 245 14 inch G10 Notebook... | Notebook    | [4d383eda43](https://linux-hardware.org/?probe=4d383eda43) | Jan 25, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7a81f8b4b0](https://linux-hardware.org/?probe=7a81f8b4b0) | Jan 25, 2025 |
| Lenovo        | IdeaPadFlex 5 14IRU8 82Y... | Convertible | [cc6beb1155](https://linux-hardware.org/?probe=cc6beb1155) | Jan 24, 2025 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [beb78f3767](https://linux-hardware.org/?probe=beb78f3767) | Jan 24, 2025 |
| ASRock        | B560M Pro4                  | Desktop     | [63f219119d](https://linux-hardware.org/?probe=63f219119d) | Jan 24, 2025 |
| Lenovo        | IdeaPadFlex 5 14IRU8 82Y... | Convertible | [0b4cc4a794](https://linux-hardware.org/?probe=0b4cc4a794) | Jan 24, 2025 |
| Timi          | RedmiBook 15                | Notebook    | [674e16712b](https://linux-hardware.org/?probe=674e16712b) | Jan 24, 2025 |
| Acer          | Nitro AN515-58              | Notebook    | [f46ba5ae1e](https://linux-hardware.org/?probe=f46ba5ae1e) | Jan 24, 2025 |
| ASRock        | X370M-HDV                   | Desktop     | [59b8497c91](https://linux-hardware.org/?probe=59b8497c91) | Jan 23, 2025 |
| HP            | 245 14 inch G10 Notebook... | Notebook    | [8b31dfa21b](https://linux-hardware.org/?probe=8b31dfa21b) | Jan 23, 2025 |
| HP            | 245 14 inch G10 Notebook... | Notebook    | [fff3a32597](https://linux-hardware.org/?probe=fff3a32597) | Jan 23, 2025 |
| HP            | 245 14 inch G10 Notebook... | Notebook    | [20268c40b9](https://linux-hardware.org/?probe=20268c40b9) | Jan 23, 2025 |
| Dell          | Latitude 7410               | Notebook    | [4163f4f046](https://linux-hardware.org/?probe=4163f4f046) | Jan 23, 2025 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [382e28b5a0](https://linux-hardware.org/?probe=382e28b5a0) | Jan 22, 2025 |
| Biostar       | NM70I-1037U                 | Desktop     | [3e7d70c21f](https://linux-hardware.org/?probe=3e7d70c21f) | Jan 22, 2025 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [e9f1dd03a7](https://linux-hardware.org/?probe=e9f1dd03a7) | Jan 22, 2025 |
| Gigabyte      | 965P-DS3                    | Desktop     | [7489046d93](https://linux-hardware.org/?probe=7489046d93) | Jan 20, 2025 |
| ASUSTek       | GL553VD                     | Notebook    | [f290b0e7e4](https://linux-hardware.org/?probe=f290b0e7e4) | Jan 20, 2025 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [3b4c108fee](https://linux-hardware.org/?probe=3b4c108fee) | Jan 20, 2025 |
| AXIOO         | MyBook Hype 7 AMD X7-2      | Notebook    | [2217855507](https://linux-hardware.org/?probe=2217855507) | Jan 19, 2025 |
| MSI           | B550M PRO-VDH               | Desktop     | [88ef98a9a7](https://linux-hardware.org/?probe=88ef98a9a7) | Jan 19, 2025 |
| MSI           | B450M-A PRO MAX             | Desktop     | [67ad350eda](https://linux-hardware.org/?probe=67ad350eda) | Jan 19, 2025 |
| HP            | Pavilion 11 x2              | Notebook    | [5bb68b1ea0](https://linux-hardware.org/?probe=5bb68b1ea0) | Jan 18, 2025 |
| HP            | Pavilion 11 x2              | Notebook    | [6c10cf02c4](https://linux-hardware.org/?probe=6c10cf02c4) | Jan 18, 2025 |
| ASRock        | H97M-ITX/ac                 | Desktop     | [7862031e44](https://linux-hardware.org/?probe=7862031e44) | Jan 17, 2025 |
| HP            | Notebook                    | Notebook    | [8785444a30](https://linux-hardware.org/?probe=8785444a30) | Jan 16, 2025 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [5bbd7f63da](https://linux-hardware.org/?probe=5bbd7f63da) | Jan 15, 2025 |
| Lenovo        | ThinkPad T480 20L6A080UK    | Notebook    | [a6fb25acac](https://linux-hardware.org/?probe=a6fb25acac) | Jan 15, 2025 |
| Lenovo        | ThinkPad T480 20L6A080UK    | Notebook    | [cb8dc4e308](https://linux-hardware.org/?probe=cb8dc4e308) | Jan 15, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [7d24cd1858](https://linux-hardware.org/?probe=7d24cd1858) | Jan 14, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [742a75a9eb](https://linux-hardware.org/?probe=742a75a9eb) | Jan 13, 2025 |
| Panasonic     | CFSZ6-2                     | Notebook    | [fca851e13d](https://linux-hardware.org/?probe=fca851e13d) | Jan 11, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [218fb03699](https://linux-hardware.org/?probe=218fb03699) | Jan 11, 2025 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [b5e4d0f289](https://linux-hardware.org/?probe=b5e4d0f289) | Jan 09, 2025 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [ec96260bec](https://linux-hardware.org/?probe=ec96260bec) | Jan 08, 2025 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [7b707d6903](https://linux-hardware.org/?probe=7b707d6903) | Jan 07, 2025 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [9c46a2928e](https://linux-hardware.org/?probe=9c46a2928e) | Jan 06, 2025 |
| Lenovo        | G40-45 80E1                 | Notebook    | [ac16ada090](https://linux-hardware.org/?probe=ac16ada090) | Jan 06, 2025 |
| HP            | 2B12                        | Desktop     | [f9594ff416](https://linux-hardware.org/?probe=f9594ff416) | Jan 05, 2025 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [3b654f1020](https://linux-hardware.org/?probe=3b654f1020) | Jan 05, 2025 |
| Unknown       | FP7R2AIO                    | All in one  | [7c37fce41a](https://linux-hardware.org/?probe=7c37fce41a) | Jan 04, 2025 |
| Unknown       | FP7R2AIO                    | All in one  | [d64e3db9ce](https://linux-hardware.org/?probe=d64e3db9ce) | Jan 04, 2025 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [d36b787d21](https://linux-hardware.org/?probe=d36b787d21) | Jan 04, 2025 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [a73526a4ad](https://linux-hardware.org/?probe=a73526a4ad) | Jan 04, 2025 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9bb39e061b](https://linux-hardware.org/?probe=9bb39e061b) | Jan 04, 2025 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [895f91d18f](https://linux-hardware.org/?probe=895f91d18f) | Jan 03, 2025 |
| Acer          | Aspire E5-552G              | Notebook    | [97430826f3](https://linux-hardware.org/?probe=97430826f3) | Jan 03, 2025 |
| Dell          | 033FF6 A00                  | Desktop     | [621ced80c1](https://linux-hardware.org/?probe=621ced80c1) | Jan 03, 2025 |
| Acer          | Aspire E5-552G              | Notebook    | [9b3e1c7a27](https://linux-hardware.org/?probe=9b3e1c7a27) | Jan 02, 2025 |
| Acer          | Aspire E5-552G              | Notebook    | [2cd3af691f](https://linux-hardware.org/?probe=2cd3af691f) | Jan 02, 2025 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [54b1993e1c](https://linux-hardware.org/?probe=54b1993e1c) | Jan 02, 2025 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [60d8cda1ee](https://linux-hardware.org/?probe=60d8cda1ee) | Jan 02, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [3bb27ee500](https://linux-hardware.org/?probe=3bb27ee500) | Jan 02, 2025 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [9829e4ea09](https://linux-hardware.org/?probe=9829e4ea09) | Jan 01, 2025 |
| Dell          | 033FF6 A00                  | Desktop     | [d8f0132e52](https://linux-hardware.org/?probe=d8f0132e52) | Jan 01, 2025 |
| Lenovo        | No DPK                      | Desktop     | [0a59c75def](https://linux-hardware.org/?probe=0a59c75def) | Dec 28, 2024 |
| MSI           | Z97-G43 GAMING              | Desktop     | [28be42de72](https://linux-hardware.org/?probe=28be42de72) | Dec 28, 2024 |
| Dell          | 07HXY6 A01                  | Desktop     | [05efb343fe](https://linux-hardware.org/?probe=05efb343fe) | Dec 28, 2024 |
| MSI           | Katana A15 AI B8VE          | Notebook    | [2dc1c3f9ae](https://linux-hardware.org/?probe=2dc1c3f9ae) | Dec 27, 2024 |
| MSI           | Katana A15 AI B8VE          | Notebook    | [ae92e3f945](https://linux-hardware.org/?probe=ae92e3f945) | Dec 27, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [283f8d39eb](https://linux-hardware.org/?probe=283f8d39eb) | Dec 27, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [eb07190046](https://linux-hardware.org/?probe=eb07190046) | Dec 27, 2024 |
| Fujitsu       | FARQ17004                   | Tablet      | [a8c473704c](https://linux-hardware.org/?probe=a8c473704c) | Dec 27, 2024 |
| ASUSTek       | X455LD                      | Notebook    | [0695dcd803](https://linux-hardware.org/?probe=0695dcd803) | Dec 26, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9930026b7c](https://linux-hardware.org/?probe=9930026b7c) | Dec 25, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [69227251ee](https://linux-hardware.org/?probe=69227251ee) | Dec 25, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [15ca1a3986](https://linux-hardware.org/?probe=15ca1a3986) | Dec 25, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [bc75be3895](https://linux-hardware.org/?probe=bc75be3895) | Dec 25, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [fab3c1d036](https://linux-hardware.org/?probe=fab3c1d036) | Dec 25, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [b5f8afb7e9](https://linux-hardware.org/?probe=b5f8afb7e9) | Dec 24, 2024 |
| Lenovo        | ThinkCentre A70 7099S3A     | Desktop     | [1ed214159d](https://linux-hardware.org/?probe=1ed214159d) | Dec 24, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e3ecdfe665](https://linux-hardware.org/?probe=e3ecdfe665) | Dec 23, 2024 |
| Unknown       | Unknown                     | Soc         | [4839a778ab](https://linux-hardware.org/?probe=4839a778ab) | Dec 22, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [d884bdac45](https://linux-hardware.org/?probe=d884bdac45) | Dec 19, 2024 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | Notebook    | [013dec6bfc](https://linux-hardware.org/?probe=013dec6bfc) | Dec 19, 2024 |
| Lenovo        | ThinkPad X260 20F5S0D501    | Notebook    | [d1c3cc5bc7](https://linux-hardware.org/?probe=d1c3cc5bc7) | Dec 18, 2024 |
| HP            | Notebook                    | Notebook    | [17804122c5](https://linux-hardware.org/?probe=17804122c5) | Dec 18, 2024 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [eee288c125](https://linux-hardware.org/?probe=eee288c125) | Dec 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [eaa6397d5e](https://linux-hardware.org/?probe=eaa6397d5e) | Dec 16, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [b200a9d4f6](https://linux-hardware.org/?probe=b200a9d4f6) | Dec 16, 2024 |
| Dell          | Latitude E7450              | Notebook    | [18a5e779b9](https://linux-hardware.org/?probe=18a5e779b9) | Dec 16, 2024 |
| Biostar       | IH61MF-Q5                   | Desktop     | [4ff0b038b3](https://linux-hardware.org/?probe=4ff0b038b3) | Dec 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [98e4e31c99](https://linux-hardware.org/?probe=98e4e31c99) | Dec 15, 2024 |
| ASUSTek       | X202E                       | Notebook    | [ff5d34316c](https://linux-hardware.org/?probe=ff5d34316c) | Dec 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [8c4e0cc970](https://linux-hardware.org/?probe=8c4e0cc970) | Dec 15, 2024 |
| Lenovo        | G41-35 80M7                 | Notebook    | [771258a66a](https://linux-hardware.org/?probe=771258a66a) | Dec 14, 2024 |
| Sony          | VPCYB15AG                   | Notebook    | [2b66b4ead4](https://linux-hardware.org/?probe=2b66b4ead4) | Dec 14, 2024 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [de007da665](https://linux-hardware.org/?probe=de007da665) | Dec 13, 2024 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [4333cd141f](https://linux-hardware.org/?probe=4333cd141f) | Dec 13, 2024 |
| ASUSTek       | X450CP                      | Notebook    | [920b185ab5](https://linux-hardware.org/?probe=920b185ab5) | Dec 13, 2024 |
| Dell          | G3 3590                     | Notebook    | [9559e19b33](https://linux-hardware.org/?probe=9559e19b33) | Dec 12, 2024 |
| ADVAN         | 1405                        | Notebook    | [0c35574db2](https://linux-hardware.org/?probe=0c35574db2) | Dec 10, 2024 |
| Acer          | Swift SF314-56G             | Notebook    | [64815f9248](https://linux-hardware.org/?probe=64815f9248) | Dec 09, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [cbd8da337a](https://linux-hardware.org/?probe=cbd8da337a) | Dec 09, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [1b7baa72c2](https://linux-hardware.org/?probe=1b7baa72c2) | Dec 06, 2024 |
| Lenovo        | ThinkPad L480 20LTA02MJP    | Notebook    | [5816a82f83](https://linux-hardware.org/?probe=5816a82f83) | Dec 05, 2024 |
| AXIOO         | EduBook Air                 | Notebook    | [54b6286adc](https://linux-hardware.org/?probe=54b6286adc) | Dec 05, 2024 |
| AXIOO         | EduBook Air                 | Notebook    | [f71d5640ed](https://linux-hardware.org/?probe=f71d5640ed) | Dec 05, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [f28ca4079c](https://linux-hardware.org/?probe=f28ca4079c) | Dec 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [456d3c7b2d](https://linux-hardware.org/?probe=456d3c7b2d) | Nov 30, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [a176cb1cfa](https://linux-hardware.org/?probe=a176cb1cfa) | Nov 30, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [0709f67f61](https://linux-hardware.org/?probe=0709f67f61) | Nov 29, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [3943e4d18a](https://linux-hardware.org/?probe=3943e4d18a) | Nov 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [d10b86c991](https://linux-hardware.org/?probe=d10b86c991) | Nov 29, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3757df02d2](https://linux-hardware.org/?probe=3757df02d2) | Nov 28, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [e7ffb651be](https://linux-hardware.org/?probe=e7ffb651be) | Nov 26, 2024 |
| HP            | EliteBook 8560w             | Notebook    | [5c651293f0](https://linux-hardware.org/?probe=5c651293f0) | Nov 25, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [616dd41a0d](https://linux-hardware.org/?probe=616dd41a0d) | Nov 25, 2024 |
| Lenovo        | ThinkPad X270 20HMS2JD03    | Notebook    | [9cc08cb72c](https://linux-hardware.org/?probe=9cc08cb72c) | Nov 25, 2024 |
| AXIOO         | Hype 5 G12                  | Notebook    | [c05b80051b](https://linux-hardware.org/?probe=c05b80051b) | Nov 25, 2024 |
| Dell          | Latitude D620               | Notebook    | [b6bcc2c7f0](https://linux-hardware.org/?probe=b6bcc2c7f0) | Nov 25, 2024 |
| ASUSTek       | GL553VD                     | Notebook    | [2dc26b3608](https://linux-hardware.org/?probe=2dc26b3608) | Nov 22, 2024 |
| ASUSTek       | GL553VD                     | Notebook    | [05198e67f4](https://linux-hardware.org/?probe=05198e67f4) | Nov 22, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [f3bc755a64](https://linux-hardware.org/?probe=f3bc755a64) | Nov 21, 2024 |
| Acer          | Aspire A514-54G             | Notebook    | [90415bf718](https://linux-hardware.org/?probe=90415bf718) | Nov 21, 2024 |
| Acer          | Aspire E1-531G              | Notebook    | [0dc612c4a9](https://linux-hardware.org/?probe=0dc612c4a9) | Nov 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [48d4b2b2d6](https://linux-hardware.org/?probe=48d4b2b2d6) | Nov 18, 2024 |
| Lenovo        | ThinkPad 20NMS0C900         | Notebook    | [4966e097ee](https://linux-hardware.org/?probe=4966e097ee) | Nov 17, 2024 |
| Lenovo        | ThinkPad 20NMS0C900         | Notebook    | [f32f6badec](https://linux-hardware.org/?probe=f32f6badec) | Nov 17, 2024 |
| Acer          | Aspire A514-54G             | Notebook    | [a965ec6798](https://linux-hardware.org/?probe=a965ec6798) | Nov 16, 2024 |
| ASRock        | X600-ITX                    | Desktop     | [00b43dd980](https://linux-hardware.org/?probe=00b43dd980) | Nov 15, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [e42cce2813](https://linux-hardware.org/?probe=e42cce2813) | Nov 15, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [e872037135](https://linux-hardware.org/?probe=e872037135) | Nov 14, 2024 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [f6ebfc4fcb](https://linux-hardware.org/?probe=f6ebfc4fcb) | Nov 13, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [3a28af2ad6](https://linux-hardware.org/?probe=3a28af2ad6) | Nov 13, 2024 |
| MSI           | ZH77A-G43                   | Desktop     | [6e7a02926e](https://linux-hardware.org/?probe=6e7a02926e) | Nov 12, 2024 |
| Acer          | Swift SF314-71              | Notebook    | [582c75cc01](https://linux-hardware.org/?probe=582c75cc01) | Nov 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [467624f847](https://linux-hardware.org/?probe=467624f847) | Nov 08, 2024 |
| AXIOO         | Mybook-14E                  | Notebook    | [32f6d232e2](https://linux-hardware.org/?probe=32f6d232e2) | Nov 07, 2024 |
| Unknown       | G41 A01                     | Desktop     | [b2d92f4da8](https://linux-hardware.org/?probe=b2d92f4da8) | Nov 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [2be2989e95](https://linux-hardware.org/?probe=2be2989e95) | Nov 05, 2024 |
| ASUSTek       | TP300LD                     | Notebook    | [3a6d49031d](https://linux-hardware.org/?probe=3a6d49031d) | Nov 04, 2024 |
| ASUSTek       | TP300LD                     | Notebook    | [551c5bff17](https://linux-hardware.org/?probe=551c5bff17) | Nov 03, 2024 |
| Acer          | Aspire A314-42P             | Notebook    | [3b985cceae](https://linux-hardware.org/?probe=3b985cceae) | Nov 03, 2024 |
| Acer          | Nitro ANV15-51              | Notebook    | [c135e3383d](https://linux-hardware.org/?probe=c135e3383d) | Nov 03, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [0c49f1f721](https://linux-hardware.org/?probe=0c49f1f721) | Nov 03, 2024 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [1e174054d4](https://linux-hardware.org/?probe=1e174054d4) | Nov 01, 2024 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [e49936d823](https://linux-hardware.org/?probe=e49936d823) | Nov 01, 2024 |
| Intel         | H61                         | Desktop     | [0e1936ef18](https://linux-hardware.org/?probe=0e1936ef18) | Oct 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e9762f3377](https://linux-hardware.org/?probe=e9762f3377) | Oct 31, 2024 |
| ASUSTek       | K46CB                       | Notebook    | [e081c9ab8c](https://linux-hardware.org/?probe=e081c9ab8c) | Oct 30, 2024 |
| ASUSTek       | X441UV                      | Notebook    | [ef419e7dda](https://linux-hardware.org/?probe=ef419e7dda) | Oct 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [d46929135e](https://linux-hardware.org/?probe=d46929135e) | Oct 25, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [5dc0afb6b3](https://linux-hardware.org/?probe=5dc0afb6b3) | Oct 24, 2024 |
| HP            | G60                         | Notebook    | [34dc5984dc](https://linux-hardware.org/?probe=34dc5984dc) | Oct 23, 2024 |
| ASUSTek       | X441UV                      | Notebook    | [d5527bcd69](https://linux-hardware.org/?probe=d5527bcd69) | Oct 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2b9158e95b](https://linux-hardware.org/?probe=2b9158e95b) | Oct 22, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [1e81679f39](https://linux-hardware.org/?probe=1e81679f39) | Oct 22, 2024 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [cfd54e896b](https://linux-hardware.org/?probe=cfd54e896b) | Oct 22, 2024 |
| Lenovo        | ThinkPad X230 2325YF3       | Notebook    | [b10ade1b28](https://linux-hardware.org/?probe=b10ade1b28) | Oct 19, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7d19f92203](https://linux-hardware.org/?probe=7d19f92203) | Oct 18, 2024 |
| Microsoft     | Surface Book 2              | Tablet      | [58861dc8f9](https://linux-hardware.org/?probe=58861dc8f9) | Oct 17, 2024 |
| ASUSTek       | ASUS Zenbook S 13 UX5304... | Notebook    | [a15c3e921c](https://linux-hardware.org/?probe=a15c3e921c) | Oct 17, 2024 |
| itel Mobil... | Epic 1                      | Notebook    | [d8b92ea891](https://linux-hardware.org/?probe=d8b92ea891) | Oct 17, 2024 |
| itel Mobil... | Epic 1                      | Notebook    | [b99b7f9e7a](https://linux-hardware.org/?probe=b99b7f9e7a) | Oct 16, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [fe47439b78](https://linux-hardware.org/?probe=fe47439b78) | Oct 15, 2024 |
| Acer          | Aspire A314-32              | Notebook    | [f0e0f318dd](https://linux-hardware.org/?probe=f0e0f318dd) | Oct 14, 2024 |
| HP            | 89B3 A                      | Desktop     | [95660e69d1](https://linux-hardware.org/?probe=95660e69d1) | Oct 12, 2024 |
| Lenovo        | ThinkPad L512 4444PL4       | Notebook    | [2df5620570](https://linux-hardware.org/?probe=2df5620570) | Oct 12, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [bcada5cbe6](https://linux-hardware.org/?probe=bcada5cbe6) | Oct 10, 2024 |
| HP            | 2B12                        | Desktop     | [dc89c52ca5](https://linux-hardware.org/?probe=dc89c52ca5) | Oct 10, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [7bf1c31e28](https://linux-hardware.org/?probe=7bf1c31e28) | Oct 10, 2024 |
| HP            | 2B12                        | Desktop     | [af8c8f5046](https://linux-hardware.org/?probe=af8c8f5046) | Oct 09, 2024 |
| ASRock        | H170 Performance            | Desktop     | [333e0c72e5](https://linux-hardware.org/?probe=333e0c72e5) | Oct 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [b02ac16d4e](https://linux-hardware.org/?probe=b02ac16d4e) | Oct 08, 2024 |
| HP            | Laptop 14-em0xxx            | Notebook    | [f0fb885887](https://linux-hardware.org/?probe=f0fb885887) | Oct 07, 2024 |
| ASUSTek       | X555DG                      | Notebook    | [c602f86121](https://linux-hardware.org/?probe=c602f86121) | Oct 06, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [b1fff870c3](https://linux-hardware.org/?probe=b1fff870c3) | Oct 05, 2024 |
| Dell          | Inspiron 5379               | Notebook    | [d4ec7c3588](https://linux-hardware.org/?probe=d4ec7c3588) | Oct 05, 2024 |
| Intel         | H81                         | Desktop     | [9792775b83](https://linux-hardware.org/?probe=9792775b83) | Oct 05, 2024 |
| Acer          | Aspire AG14-31P             | Notebook    | [ba0935bde6](https://linux-hardware.org/?probe=ba0935bde6) | Oct 05, 2024 |
| Acer          | Aspire AG14-31P             | Notebook    | [f3c50b490a](https://linux-hardware.org/?probe=f3c50b490a) | Oct 05, 2024 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [cd6776c30a](https://linux-hardware.org/?probe=cd6776c30a) | Oct 04, 2024 |
| Unknown       | Unknown                     | Notebook    | [cb3c212bc9](https://linux-hardware.org/?probe=cb3c212bc9) | Oct 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [8f6ef31fc0](https://linux-hardware.org/?probe=8f6ef31fc0) | Oct 01, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [605995ef0d](https://linux-hardware.org/?probe=605995ef0d) | Oct 01, 2024 |
| Dell          | Latitude 3420               | Notebook    | [d7672fb8f4](https://linux-hardware.org/?probe=d7672fb8f4) | Sep 29, 2024 |
| Acer          | Predator PHN16-71           | Notebook    | [8815e16a5e](https://linux-hardware.org/?probe=8815e16a5e) | Sep 29, 2024 |
| Acer          | Okinawa                     | Notebook    | [dd1134eda8](https://linux-hardware.org/?probe=dd1134eda8) | Sep 28, 2024 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [2b9c6f05fe](https://linux-hardware.org/?probe=2b9c6f05fe) | Sep 28, 2024 |
| Lenovo        | ThinkPad W550s 20E2000QU... | Notebook    | [5adcba6b0e](https://linux-hardware.org/?probe=5adcba6b0e) | Sep 27, 2024 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [7b4b348c98](https://linux-hardware.org/?probe=7b4b348c98) | Sep 27, 2024 |
| Google        | Fleex                       | Notebook    | [05a6990467](https://linux-hardware.org/?probe=05a6990467) | Sep 27, 2024 |
| Lenovo        | ThinkPad W550s 20E2000QU... | Notebook    | [fe8af671af](https://linux-hardware.org/?probe=fe8af671af) | Sep 26, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [24a8743042](https://linux-hardware.org/?probe=24a8743042) | Sep 24, 2024 |
| Intel         | B75                         | Desktop     | [17dd91b6f2](https://linux-hardware.org/?probe=17dd91b6f2) | Sep 24, 2024 |
| Dell          | Inspiron 5491 2n1           | Convertible | [8dda5a0bc7](https://linux-hardware.org/?probe=8dda5a0bc7) | Sep 23, 2024 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [fd06da7fc1](https://linux-hardware.org/?probe=fd06da7fc1) | Sep 22, 2024 |
| Lenovo        | ThinkPad X100e 2876CTO      | Notebook    | [7282bf9e1e](https://linux-hardware.org/?probe=7282bf9e1e) | Sep 22, 2024 |
| Dell          | Latitude 3420               | Notebook    | [91dbcf2851](https://linux-hardware.org/?probe=91dbcf2851) | Sep 21, 2024 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [7259f3460a](https://linux-hardware.org/?probe=7259f3460a) | Sep 21, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [126bd31450](https://linux-hardware.org/?probe=126bd31450) | Sep 20, 2024 |
| Lenovo        | G400 20235                  | Notebook    | [96ebcfea10](https://linux-hardware.org/?probe=96ebcfea10) | Sep 18, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [ffe3da2a61](https://linux-hardware.org/?probe=ffe3da2a61) | Sep 17, 2024 |
| AXIOO         | MyBook Hype 5               | Notebook    | [d6b2a6bbbe](https://linux-hardware.org/?probe=d6b2a6bbbe) | Sep 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [b105d16e70](https://linux-hardware.org/?probe=b105d16e70) | Sep 13, 2024 |
| Dell          | Latitude E7250              | Notebook    | [f5079722a9](https://linux-hardware.org/?probe=f5079722a9) | Sep 11, 2024 |
| Lenovo        | ThinkPad T480s 20L8S6360... | Notebook    | [488ff39e81](https://linux-hardware.org/?probe=488ff39e81) | Sep 10, 2024 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [5645aa8848](https://linux-hardware.org/?probe=5645aa8848) | Sep 05, 2024 |
| Dell          | XPS 9320                    | Notebook    | [27298b827b](https://linux-hardware.org/?probe=27298b827b) | Sep 03, 2024 |
| AYANEO        | GEEK                        | Tablet      | [33569d4ee1](https://linux-hardware.org/?probe=33569d4ee1) | Sep 03, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ab21866554](https://linux-hardware.org/?probe=ab21866554) | Sep 03, 2024 |
| ASUSTek       | E5402WHA                    | All in one  | [f9654565db](https://linux-hardware.org/?probe=f9654565db) | Sep 02, 2024 |
| Gigabyte      | G31M-S2C                    | Desktop     | [29671c0af6](https://linux-hardware.org/?probe=29671c0af6) | Sep 02, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [45cfeca88a](https://linux-hardware.org/?probe=45cfeca88a) | Aug 31, 2024 |
| AXIOO         | PICO CJW                    | Notebook    | [3c7b0a8d95](https://linux-hardware.org/?probe=3c7b0a8d95) | Aug 31, 2024 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [b0e323ae58](https://linux-hardware.org/?probe=b0e323ae58) | Aug 31, 2024 |
| AXIOO         | PICO CJW                    | Notebook    | [6ba416a56c](https://linux-hardware.org/?probe=6ba416a56c) | Aug 31, 2024 |
| Gigabyte      | P55-UD3P                    | Desktop     | [80da5ed3a8](https://linux-hardware.org/?probe=80da5ed3a8) | Aug 29, 2024 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [8886ae523e](https://linux-hardware.org/?probe=8886ae523e) | Aug 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [5502afcee2](https://linux-hardware.org/?probe=5502afcee2) | Aug 29, 2024 |
| ASUSTek       | K30AM-J                     | Desktop     | [912c2ae503](https://linux-hardware.org/?probe=912c2ae503) | Aug 29, 2024 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [7dfa339f21](https://linux-hardware.org/?probe=7dfa339f21) | Aug 29, 2024 |
| ASUSTek       | X455LF                      | Notebook    | [2ebd2ae224](https://linux-hardware.org/?probe=2ebd2ae224) | Aug 28, 2024 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [9d5c4db3d1](https://linux-hardware.org/?probe=9d5c4db3d1) | Aug 27, 2024 |
| Acer          | Aspire 4743                 | Notebook    | [2407fc17fc](https://linux-hardware.org/?probe=2407fc17fc) | Aug 27, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ae159e1811](https://linux-hardware.org/?probe=ae159e1811) | Aug 27, 2024 |
| PT. Zyrexi... | Zyrex Notebook Cruiser 2... | Convertible | [4c1b9f22d2](https://linux-hardware.org/?probe=4c1b9f22d2) | Aug 24, 2024 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [98393b8796](https://linux-hardware.org/?probe=98393b8796) | Aug 23, 2024 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [8457bf32ea](https://linux-hardware.org/?probe=8457bf32ea) | Aug 23, 2024 |
| Dell          | Latitude 3410               | Notebook    | [0b09307b53](https://linux-hardware.org/?probe=0b09307b53) | Aug 22, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [59afcb4476](https://linux-hardware.org/?probe=59afcb4476) | Aug 21, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [6ce7717ab8](https://linux-hardware.org/?probe=6ce7717ab8) | Aug 20, 2024 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [dd86f2e3f4](https://linux-hardware.org/?probe=dd86f2e3f4) | Aug 20, 2024 |
| Toshiba       | TECRA Z40-A                 | Notebook    | [24e6b94f55](https://linux-hardware.org/?probe=24e6b94f55) | Aug 20, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [571b1e7cf5](https://linux-hardware.org/?probe=571b1e7cf5) | Aug 20, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ca11b9e447](https://linux-hardware.org/?probe=ca11b9e447) | Aug 20, 2024 |
| Lenovo        | ThinkPad T61 7658CTO        | Notebook    | [c395b3e28c](https://linux-hardware.org/?probe=c395b3e28c) | Aug 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0b49e3d246](https://linux-hardware.org/?probe=0b49e3d246) | Aug 16, 2024 |
| ASRock        | X300M-STX                   | Desktop     | [39611ab403](https://linux-hardware.org/?probe=39611ab403) | Aug 16, 2024 |
| Lenovo        | ThinkPad X240 20AMA3AECD    | Notebook    | [ca3f5f8a59](https://linux-hardware.org/?probe=ca3f5f8a59) | Aug 15, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [54b3658243](https://linux-hardware.org/?probe=54b3658243) | Aug 15, 2024 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [0e2d15df7c](https://linux-hardware.org/?probe=0e2d15df7c) | Aug 15, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [2a780be401](https://linux-hardware.org/?probe=2a780be401) | Aug 14, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [aee1dc9bfe](https://linux-hardware.org/?probe=aee1dc9bfe) | Aug 13, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [e322a156a0](https://linux-hardware.org/?probe=e322a156a0) | Aug 13, 2024 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [fe32237e3a](https://linux-hardware.org/?probe=fe32237e3a) | Aug 12, 2024 |
| Gigabyte      | B75M-HD3                    | Desktop     | [39efa072bc](https://linux-hardware.org/?probe=39efa072bc) | Aug 12, 2024 |
| ASUSTek       | H61M-E                      | Desktop     | [c18e02345c](https://linux-hardware.org/?probe=c18e02345c) | Aug 12, 2024 |
| HP            | 198E                        | Desktop     | [21d03f44b1](https://linux-hardware.org/?probe=21d03f44b1) | Aug 11, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [f11d04ee8e](https://linux-hardware.org/?probe=f11d04ee8e) | Aug 09, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [e6c64713c1](https://linux-hardware.org/?probe=e6c64713c1) | Aug 08, 2024 |
| HP            | Compaq 435                  | Notebook    | [4911c70481](https://linux-hardware.org/?probe=4911c70481) | Aug 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [6afe9c392f](https://linux-hardware.org/?probe=6afe9c392f) | Aug 04, 2024 |
| Intel         | H110 Series                 | Desktop     | [ba2023d022](https://linux-hardware.org/?probe=ba2023d022) | Aug 03, 2024 |
| Lenovo        | G400 20235                  | Notebook    | [ffa298e6de](https://linux-hardware.org/?probe=ffa298e6de) | Aug 03, 2024 |
| Intel         | DH61WW AAG23116-303         | Desktop     | [f46309dc1c](https://linux-hardware.org/?probe=f46309dc1c) | Aug 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [1bae3fe2d4](https://linux-hardware.org/?probe=1bae3fe2d4) | Aug 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [058fa0e4aa](https://linux-hardware.org/?probe=058fa0e4aa) | Aug 01, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0d84b625a7](https://linux-hardware.org/?probe=0d84b625a7) | Jul 30, 2024 |
| ASUSTek       | H61M-E                      | Desktop     | [368a1a7088](https://linux-hardware.org/?probe=368a1a7088) | Jul 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [1329ba82ac](https://linux-hardware.org/?probe=1329ba82ac) | Jul 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [637e807f6a](https://linux-hardware.org/?probe=637e807f6a) | Jul 28, 2024 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [2e993c4215](https://linux-hardware.org/?probe=2e993c4215) | Jul 27, 2024 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [a9d457cbfe](https://linux-hardware.org/?probe=a9d457cbfe) | Jul 27, 2024 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [0dbc5b0c8a](https://linux-hardware.org/?probe=0dbc5b0c8a) | Jul 26, 2024 |
| HP            | ProBook 440 G4              | Notebook    | [a2ffdc1d34](https://linux-hardware.org/?probe=a2ffdc1d34) | Jul 26, 2024 |
| Dell          | Inspiron 14-3462            | Notebook    | [13234332e1](https://linux-hardware.org/?probe=13234332e1) | Jul 25, 2024 |
| Lenovo        | G460 20041                  | Notebook    | [67670a0f4a](https://linux-hardware.org/?probe=67670a0f4a) | Jul 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [79e199cee3](https://linux-hardware.org/?probe=79e199cee3) | Jul 24, 2024 |
| MSI           | B550M PRO-VDH               | Desktop     | [e20f83dc61](https://linux-hardware.org/?probe=e20f83dc61) | Jul 23, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e09128a4ab](https://linux-hardware.org/?probe=e09128a4ab) | Jul 22, 2024 |
| HP            | 14                          | Notebook    | [f418deebad](https://linux-hardware.org/?probe=f418deebad) | Jul 22, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L1400CDA... | Notebook    | [0ff73e973a](https://linux-hardware.org/?probe=0ff73e973a) | Jul 22, 2024 |
| Lenovo        | ThinkPad X230 2306A27       | Notebook    | [07e6f1b674](https://linux-hardware.org/?probe=07e6f1b674) | Jul 22, 2024 |
| Toshiba       | Satellite L510              | Notebook    | [97e25526be](https://linux-hardware.org/?probe=97e25526be) | Jul 21, 2024 |
| Lenovo        | G460 20041                  | Notebook    | [2baabb5540](https://linux-hardware.org/?probe=2baabb5540) | Jul 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [de93837a91](https://linux-hardware.org/?probe=de93837a91) | Jul 20, 2024 |
| Intel         | H61                         | Desktop     | [79cbc35474](https://linux-hardware.org/?probe=79cbc35474) | Jul 20, 2024 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [12bf57a78e](https://linux-hardware.org/?probe=12bf57a78e) | Jul 19, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [04a35f754e](https://linux-hardware.org/?probe=04a35f754e) | Jul 17, 2024 |
| ADVAN         | 1405                        | Notebook    | [fd0d652727](https://linux-hardware.org/?probe=fd0d652727) | Jul 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP34... | Convertible | [b32ef428be](https://linux-hardware.org/?probe=b32ef428be) | Jul 16, 2024 |
| Toshiba       | Satellite L645              | Notebook    | [7c46019cc3](https://linux-hardware.org/?probe=7c46019cc3) | Jul 16, 2024 |
| ASUSTek       | X455LJ                      | Notebook    | [560bb80195](https://linux-hardware.org/?probe=560bb80195) | Jul 15, 2024 |
| ASUSTek       | X455LJ                      | Notebook    | [6364ad10c5](https://linux-hardware.org/?probe=6364ad10c5) | Jul 15, 2024 |
| Acer          | Aspire E5-475G              | Notebook    | [18965ce4ea](https://linux-hardware.org/?probe=18965ce4ea) | Jul 15, 2024 |
| Lenovo        | ThinkPad T480 20L6S1F20F    | Notebook    | [b9445ad087](https://linux-hardware.org/?probe=b9445ad087) | Jul 15, 2024 |
| Lenovo        | ThinkPad T430 23476W7       | Notebook    | [9033123c38](https://linux-hardware.org/?probe=9033123c38) | Jul 15, 2024 |
| HP            | Laptop 14-bs1xx             | Notebook    | [cf4f3c0bb8](https://linux-hardware.org/?probe=cf4f3c0bb8) | Jul 15, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5482a0b3dc](https://linux-hardware.org/?probe=5482a0b3dc) | Jul 15, 2024 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [a7d115c7d5](https://linux-hardware.org/?probe=a7d115c7d5) | Jul 15, 2024 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [8e7672b34e](https://linux-hardware.org/?probe=8e7672b34e) | Jul 14, 2024 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [39b464c39e](https://linux-hardware.org/?probe=39b464c39e) | Jul 14, 2024 |
| HP            | Notebook                    | Notebook    | [76d1a8c671](https://linux-hardware.org/?probe=76d1a8c671) | Jul 14, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [d9aeff835a](https://linux-hardware.org/?probe=d9aeff835a) | Jul 13, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [a87baa98b1](https://linux-hardware.org/?probe=a87baa98b1) | Jul 11, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0837d07786](https://linux-hardware.org/?probe=0837d07786) | Jul 11, 2024 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c5a2c8ebb0](https://linux-hardware.org/?probe=c5a2c8ebb0) | Jul 09, 2024 |
| ASRock        | B650M PG Lightning          | Desktop     | [94eff09933](https://linux-hardware.org/?probe=94eff09933) | Jul 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [4da248e266](https://linux-hardware.org/?probe=4da248e266) | Jul 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [5c863e0d7c](https://linux-hardware.org/?probe=5c863e0d7c) | Jul 08, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [79a2ee9967](https://linux-hardware.org/?probe=79a2ee9967) | Jul 07, 2024 |
| HP            | Pavilion g4                 | Notebook    | [7dc29fa0b4](https://linux-hardware.org/?probe=7dc29fa0b4) | Jul 07, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [c5062c2b4e](https://linux-hardware.org/?probe=c5062c2b4e) | Jul 07, 2024 |
| ECS           | H61H2-M12                   | Desktop     | [7bcab0a14c](https://linux-hardware.org/?probe=7bcab0a14c) | Jul 07, 2024 |
| Acer          | Swift SF314-71              | Notebook    | [7910b13b30](https://linux-hardware.org/?probe=7910b13b30) | Jul 06, 2024 |
| ASUSTek       | X201EV                      | Notebook    | [f02eb29877](https://linux-hardware.org/?probe=f02eb29877) | Jul 06, 2024 |
| Panasonic     | CFSZ6-2                     | Notebook    | [09991bde50](https://linux-hardware.org/?probe=09991bde50) | Jul 06, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [5988ce94ee](https://linux-hardware.org/?probe=5988ce94ee) | Jul 06, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [9d7278dbe4](https://linux-hardware.org/?probe=9d7278dbe4) | Jul 06, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [54e71c6699](https://linux-hardware.org/?probe=54e71c6699) | Jul 06, 2024 |
| Gigabyte      | 970A-D3P                    | Desktop     | [1aba817d5d](https://linux-hardware.org/?probe=1aba817d5d) | Jul 05, 2024 |
| Lenovo        | ThinkPad T430 23476W7       | Notebook    | [5b5cf02ccc](https://linux-hardware.org/?probe=5b5cf02ccc) | Jul 05, 2024 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [6e79e0bd1e](https://linux-hardware.org/?probe=6e79e0bd1e) | Jul 04, 2024 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [83aba2641e](https://linux-hardware.org/?probe=83aba2641e) | Jul 04, 2024 |
| HP            | 8169                        | Desktop     | [c45572c08d](https://linux-hardware.org/?probe=c45572c08d) | Jul 04, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [a12c62a640](https://linux-hardware.org/?probe=a12c62a640) | Jul 04, 2024 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [2e09a7f7bd](https://linux-hardware.org/?probe=2e09a7f7bd) | Jul 04, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [9f0a26445e](https://linux-hardware.org/?probe=9f0a26445e) | Jul 04, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [16545a1d8f](https://linux-hardware.org/?probe=16545a1d8f) | Jul 02, 2024 |
| ADVAN         | 1701                        | Notebook    | [74128c428a](https://linux-hardware.org/?probe=74128c428a) | Jul 01, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [68fff6c23b](https://linux-hardware.org/?probe=68fff6c23b) | Jul 01, 2024 |
| Dell          | 0Y2MRG A00                  | Desktop     | [cab50448b9](https://linux-hardware.org/?probe=cab50448b9) | Jun 30, 2024 |
| Lenovo        | ThinkPad T520 423953J       | Notebook    | [01e5062809](https://linux-hardware.org/?probe=01e5062809) | Jun 29, 2024 |
| ASRock        | X370M Pro4                  | Desktop     | [65e29ff944](https://linux-hardware.org/?probe=65e29ff944) | Jun 29, 2024 |
| HP            | 87F3 0100                   | All in one  | [5738460f11](https://linux-hardware.org/?probe=5738460f11) | Jun 28, 2024 |
| ADVAN         | 1701                        | Notebook    | [983e29b86d](https://linux-hardware.org/?probe=983e29b86d) | Jun 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [6dd3ef98e9](https://linux-hardware.org/?probe=6dd3ef98e9) | Jun 26, 2024 |
| AVITA         | NE14A2                      | Notebook    | [36e93c620c](https://linux-hardware.org/?probe=36e93c620c) | Jun 25, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [4d278d12d7](https://linux-hardware.org/?probe=4d278d12d7) | Jun 25, 2024 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [186d1f827c](https://linux-hardware.org/?probe=186d1f827c) | Jun 24, 2024 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [ab244cc45f](https://linux-hardware.org/?probe=ab244cc45f) | Jun 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [49ade9d97b](https://linux-hardware.org/?probe=49ade9d97b) | Jun 24, 2024 |
| Acer          | Aspire MC605 v1.0           | Desktop     | [412057df6b](https://linux-hardware.org/?probe=412057df6b) | Jun 23, 2024 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [347663d539](https://linux-hardware.org/?probe=347663d539) | Jun 23, 2024 |
| Lenovo        | ThinkPad T430 23476W7       | Notebook    | [52e6290d5d](https://linux-hardware.org/?probe=52e6290d5d) | Jun 20, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [2cdf2b71a1](https://linux-hardware.org/?probe=2cdf2b71a1) | Jun 20, 2024 |
| Lenovo        | ThinkPad L570 20J9S34000    | Notebook    | [a600d8246f](https://linux-hardware.org/?probe=a600d8246f) | Jun 18, 2024 |
| FriendlyEl... | NanoPC-T6                   | Soc         | [9726e3b312](https://linux-hardware.org/?probe=9726e3b312) | Jun 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [f2f1d90b24](https://linux-hardware.org/?probe=f2f1d90b24) | Jun 16, 2024 |
| ASUSTek       | ASUS Zenbook S 13 UX5304... | Notebook    | [66051331fd](https://linux-hardware.org/?probe=66051331fd) | Jun 11, 2024 |
| TriGem Com... | H61H2-TM7                   | Desktop     | [7deb9d1c5a](https://linux-hardware.org/?probe=7deb9d1c5a) | Jun 11, 2024 |
| Toshiba       | dynabook R734/M             | Notebook    | [c8a799a398](https://linux-hardware.org/?probe=c8a799a398) | Jun 10, 2024 |
| HP            | Notebook                    | Notebook    | [4bbae416f7](https://linux-hardware.org/?probe=4bbae416f7) | Jun 09, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [d66cae1613](https://linux-hardware.org/?probe=d66cae1613) | Jun 08, 2024 |
| HP            | Laptop 14s-cf3xxx           | Notebook    | [fd48784b0f](https://linux-hardware.org/?probe=fd48784b0f) | Jun 08, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6cf80a06d1](https://linux-hardware.org/?probe=6cf80a06d1) | Jun 07, 2024 |
| AIO           | DynaBook e5                 | Notebook    | [0e4ad04db5](https://linux-hardware.org/?probe=0e4ad04db5) | Jun 06, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [9d0db9afbe](https://linux-hardware.org/?probe=9d0db9afbe) | Jun 06, 2024 |
| Unknown       | G41 Series                  | Desktop     | [f9b4dbc607](https://linux-hardware.org/?probe=f9b4dbc607) | Jun 05, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [be344b10dc](https://linux-hardware.org/?probe=be344b10dc) | Jun 05, 2024 |
| Toshiba       | dynabook R734/M             | Notebook    | [f539a0d213](https://linux-hardware.org/?probe=f539a0d213) | Jun 04, 2024 |
| Acer          | Veriton L4620G v1.0         | Desktop     | [24db2893da](https://linux-hardware.org/?probe=24db2893da) | Jun 04, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [00dc39a0b7](https://linux-hardware.org/?probe=00dc39a0b7) | Jun 03, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [0941f7e44b](https://linux-hardware.org/?probe=0941f7e44b) | Jun 03, 2024 |
| Toshiba       | dynabook R731/C             | Notebook    | [e8f41ce95d](https://linux-hardware.org/?probe=e8f41ce95d) | Jun 02, 2024 |
| Toshiba       | dynabook R731/C             | Notebook    | [421ef5ca84](https://linux-hardware.org/?probe=421ef5ca84) | Jun 02, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [e29deb87ee](https://linux-hardware.org/?probe=e29deb87ee) | May 28, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [060ce09ffd](https://linux-hardware.org/?probe=060ce09ffd) | May 27, 2024 |
| Toshiba       | Satellite L740              | Notebook    | [af075df4bd](https://linux-hardware.org/?probe=af075df4bd) | May 25, 2024 |
| ASUSTek       | X200CA                      | Notebook    | [b4af45240b](https://linux-hardware.org/?probe=b4af45240b) | May 25, 2024 |
| Panasonic     | CFSZ5-2                     | Notebook    | [dd94dab0da](https://linux-hardware.org/?probe=dd94dab0da) | May 24, 2024 |
| Toshiba       | Satellite L740              | Notebook    | [471713a2b2](https://linux-hardware.org/?probe=471713a2b2) | May 24, 2024 |
| Chuwi         | FreeBook                    | Notebook    | [6cd2de3abd](https://linux-hardware.org/?probe=6cd2de3abd) | May 23, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [ba3f755558](https://linux-hardware.org/?probe=ba3f755558) | May 23, 2024 |
| Acer          | Swift SF313-51              | Notebook    | [80ad889357](https://linux-hardware.org/?probe=80ad889357) | May 20, 2024 |
| Acer          | Swift SF313-51              | Notebook    | [79d8372cf3](https://linux-hardware.org/?probe=79d8372cf3) | May 20, 2024 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [0c62b9f67c](https://linux-hardware.org/?probe=0c62b9f67c) | May 20, 2024 |
| Acer          | Aspire E5-471G              | Notebook    | [6ad4e168d9](https://linux-hardware.org/?probe=6ad4e168d9) | May 20, 2024 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [c761a6d766](https://linux-hardware.org/?probe=c761a6d766) | May 19, 2024 |
| AIO           | DynaBook e5                 | Notebook    | [061663a80d](https://linux-hardware.org/?probe=061663a80d) | May 15, 2024 |
| Dell          | 0JH35T A00                  | Mini pc     | [b82c8fc7c5](https://linux-hardware.org/?probe=b82c8fc7c5) | May 15, 2024 |
| Lenovo        | ThinkPad X200               | Notebook    | [2cd87a7d08](https://linux-hardware.org/?probe=2cd87a7d08) | May 14, 2024 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [bda1d0daa6](https://linux-hardware.org/?probe=bda1d0daa6) | May 13, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Indonesia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 173       | 7.19%   |
| Ubuntu 22.04                 | 111       | 4.61%   |
| Ubuntu 18.04                 | 106       | 4.41%   |
| Arch Rolling                 | 92        | 3.82%   |
| Ubuntu 24.04                 | 77        | 3.2%    |
| OpenMandriva 4.3             | 63        | 2.62%   |
| Pop!_OS 22.04                | 61        | 2.54%   |
| Debian 12                    | 59        | 2.45%   |
| Zorin 17                     | 37        | 1.54%   |
| OpenMandriva 25.90           | 37        | 1.54%   |
| Fedora 42                    | 37        | 1.54%   |
| OpenMandriva 4.2             | 32        | 1.33%   |
| ArcoLinux Rolling            | 32        | 1.33%   |
| OpenMandriva 24.12           | 30        | 1.25%   |
| KDE neon 20.04               | 26        | 1.08%   |
| Fedora 41                    | 25        | 1.04%   |
| Fedora 40                    | 25        | 1.04%   |
| Manjaro                      | 24        | 1%      |
| Fedora 38                    | 24        | 1%      |
| Zorin 15                     | 23        | 0.96%   |
| OpenMandriva 23.08           | 23        | 0.96%   |
| Linux Mint 22.1              | 23        | 0.96%   |
| OpenMandriva 5.0             | 22        | 0.91%   |
| Arch                         | 22        | 0.91%   |
| Fedora 36                    | 21        | 0.87%   |
| Zorin 16                     | 20        | 0.83%   |
| EndeavourOS Rolling          | 20        | 0.83%   |
| Elementary 6.1               | 19        | 0.79%   |
| Pop!_OS 20.04                | 18        | 0.75%   |
| openSUSE Tumbleweed-XXXXXXXX | 18        | 0.75%   |
| OpenMandriva 23.03           | 17        | 0.71%   |
| Linux Mint 20.3              | 17        | 0.71%   |
| Fedora 35                    | 17        | 0.71%   |
| Debian 11                    | 17        | 0.71%   |
| Ubuntu 21.10                 | 16        | 0.67%   |
| Linux Mint 21.1              | 16        | 0.67%   |
| Ubuntu 19.10                 | 15        | 0.62%   |
| Fedora 37                    | 15        | 0.62%   |
| OpenMandriva 23.01           | 14        | 0.58%   |
| Linux Mint 19.3              | 14        | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 548       | 24.05%  |
| OpenMandriva  | 298       | 13.08%  |
| Fedora        | 190       | 8.34%   |
| Linux Mint    | 146       | 6.41%   |
| Arch          | 114       | 5%      |
| Debian        | 106       | 4.65%   |
| Pop!_OS       | 96        | 4.21%   |
| Zorin         | 92        | 4.04%   |
| Manjaro       | 64        | 2.81%   |
| Elementary    | 58        | 2.54%   |
| KDE neon      | 48        | 2.11%   |
| Kali          | 47        | 2.06%   |
| Kubuntu       | 45        | 1.97%   |
| Endless       | 35        | 1.54%   |
| ArcoLinux     | 33        | 1.45%   |
| Xubuntu       | 31        | 1.36%   |
| Lubuntu       | 25        | 1.1%    |
| openSUSE      | 23        | 1.01%   |
| EndeavourOS   | 20        | 0.88%   |
| ROSA          | 19        | 0.83%   |
| MX            | 18        | 0.79%   |
| Ubuntu MATE   | 16        | 0.7%    |
| SteamOS       | 15        | 0.66%   |
| CachyOS       | 13        | 0.57%   |
| Nobara        | 11        | 0.48%   |
| LMDE          | 11        | 0.48%   |
| Ubuntu Unity  | 10        | 0.44%   |
| Gentoo        | 9         | 0.39%   |
| Bazzite       | 9         | 0.39%   |
| Parrot        | 8         | 0.35%   |
| Clear Linux   | 8         | 0.35%   |
| Deepin        | 7         | 0.31%   |
| Android       | 7         | 0.31%   |
| Garuda Linux  | 6         | 0.26%   |
| NixOS         | 5         | 0.22%   |
| CentOS        | 5         | 0.22%   |
| Artix         | 5         | 0.22%   |
| Xero          | 4         | 0.18%   |
| Ubuntu Budgie | 4         | 0.18%   |
| TUXEDO OS     | 4         | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 62        | 2.42%   |
| 6.14.2-desktop-3omv2590  | 61        | 2.38%   |
| 5.10.14-desktop-1omv4002 | 29        | 1.13%   |
| 6.12.1-desktop-1omv2490  | 28        | 1.09%   |
| 5.4.0-42-generic         | 28        | 1.09%   |
| 6.6.2-desktop-1omv2390   | 26        | 1.01%   |
| 5.15.0-56-generic        | 22        | 0.86%   |
| 6.4.11-desktop-1omv2390  | 19        | 0.74%   |
| 5.4.0-26-generic         | 18        | 0.7%    |
| 6.2.6-desktop-1omv2390   | 16        | 0.62%   |
| 5.4.0-52-generic         | 16        | 0.62%   |
| 6.9.3-76060903-generic   | 15        | 0.59%   |
| 6.8.0-51-generic         | 15        | 0.59%   |
| 5.4.0-58-generic         | 15        | 0.59%   |
| 6.1.1-desktop-1omv2290   | 12        | 0.47%   |
| 4.18.0-15-generic        | 12        | 0.47%   |
| 6.8.0-60-generic         | 11        | 0.43%   |
| 6.8.0-52-generic         | 11        | 0.43%   |
| 5.15.0-41-generic        | 11        | 0.43%   |
| 5.0.0-25-generic         | 11        | 0.43%   |
| 6.14.0-33-generic        | 10        | 0.39%   |
| 5.15.0-48-generic        | 10        | 0.39%   |
| 5.15.0-46-generic        | 10        | 0.39%   |
| 5.15.0-43-generic        | 10        | 0.39%   |
| 6.8.0-49-generic         | 9         | 0.35%   |
| 6.8.0-45-generic         | 9         | 0.35%   |
| 5.4.0-80-generic         | 9         | 0.35%   |
| 5.15.0-47-generic        | 9         | 0.35%   |
| 5.11.0-37-generic        | 9         | 0.35%   |
| 6.8.0-41-generic         | 8         | 0.31%   |
| 6.5.0-35-generic         | 8         | 0.31%   |
| 6.14.0-27-generic        | 8         | 0.31%   |
| 6.10.0-desktop-1omv2490  | 8         | 0.31%   |
| 5.4.0-54-generic         | 8         | 0.31%   |
| 5.3.0-46-generic         | 8         | 0.31%   |
| 5.3.0-40-generic         | 8         | 0.31%   |
| 5.19.0-46-generic        | 8         | 0.31%   |
| 5.15.0-91-generic        | 8         | 0.31%   |
| 5.15.0-58-generic        | 8         | 0.31%   |
| 5.11.0-27-generic        | 8         | 0.31%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 215       | 8.66%   |
| 5.15.0  | 169       | 6.81%   |
| 6.8.0   | 134       | 5.4%    |
| 5.11.0  | 74        | 2.98%   |
| 6.1.0   | 70        | 2.82%   |
| 6.14.2  | 64        | 2.58%   |
| 5.16.7  | 64        | 2.58%   |
| 6.5.0   | 62        | 2.5%    |
| 6.14.0  | 61        | 2.46%   |
| 5.8.0   | 61        | 2.46%   |
| 4.15.0  | 57        | 2.3%    |
| 5.13.0  | 53        | 2.14%   |
| 5.3.0   | 51        | 2.05%   |
| 6.2.0   | 45        | 1.81%   |
| 5.0.0   | 43        | 1.73%   |
| 6.11.0  | 37        | 1.49%   |
| 5.19.0  | 36        | 1.45%   |
| 5.10.0  | 33        | 1.33%   |
| 4.18.0  | 32        | 1.29%   |
| 5.10.14 | 30        | 1.21%   |
| 6.12.1  | 28        | 1.13%   |
| 6.6.2   | 26        | 1.05%   |
| 6.4.11  | 22        | 0.89%   |
| 6.2.6   | 20        | 0.81%   |
| 6.1.1   | 18        | 0.73%   |
| 6.9.3   | 16        | 0.64%   |
| 6.5.5   | 15        | 0.6%    |
| 4.19.0  | 15        | 0.6%    |
| 6.9.7   | 11        | 0.44%   |
| 6.12.9  | 11        | 0.44%   |
| 5.14.0  | 11        | 0.44%   |
| 6.17.0  | 9         | 0.36%   |
| 6.10.0  | 9         | 0.36%   |
| 6.16.7  | 8         | 0.32%   |
| 6.12.10 | 8         | 0.32%   |
| 5.17.5  | 8         | 0.32%   |
| 4.4.0   | 8         | 0.32%   |
| 6.6.9   | 7         | 0.28%   |
| 6.5.6   | 7         | 0.28%   |
| 6.4.8   | 7         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 225       | 9.21%   |
| 5.15    | 196       | 8.03%   |
| 6.8     | 155       | 6.35%   |
| 6.14    | 146       | 5.98%   |
| 6.1     | 121       | 4.95%   |
| 6.12    | 110       | 4.5%    |
| 6.5     | 100       | 4.1%    |
| 5.10    | 100       | 4.1%    |
| 5.16    | 87        | 3.56%   |
| 5.11    | 84        | 3.44%   |
| 6.2     | 83        | 3.4%    |
| 6.6     | 79        | 3.24%   |
| 5.8     | 76        | 3.11%   |
| 5.13    | 61        | 2.5%    |
| 6.11    | 58        | 2.38%   |
| 4.15    | 57        | 2.33%   |
| 6.4     | 55        | 2.25%   |
| 5.3     | 55        | 2.25%   |
| 5.19    | 52        | 2.13%   |
| 5.0     | 45        | 1.84%   |
| 6.9     | 42        | 1.72%   |
| 6.17    | 39        | 1.6%    |
| 6.10    | 36        | 1.47%   |
| 4.18    | 35        | 1.43%   |
| 6.0     | 32        | 1.31%   |
| 6.16    | 31        | 1.27%   |
| 5.14    | 27        | 1.11%   |
| 6.15    | 26        | 1.06%   |
| 6.3     | 25        | 1.02%   |
| 5.17    | 22        | 0.9%    |
| 6.13    | 20        | 0.82%   |
| 5.18    | 19        | 0.78%   |
| 4.19    | 19        | 0.78%   |
| 6.7     | 16        | 0.66%   |
| 5.9     | 16        | 0.66%   |
| 4.9     | 14        | 0.57%   |
| 5.12    | 12        | 0.49%   |
| 5.7     | 10        | 0.41%   |
| 5.6     | 10        | 0.41%   |
| 4.4     | 10        | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2140      | 97.81%  |
| i686    | 31        | 1.42%   |
| aarch64 | 11        | 0.5%    |
| armv8l  | 3         | 0.14%   |
| armv7l  | 3         | 0.14%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 929       | 40.51%  |
| KDE5              | 361       | 15.74%  |
| KDE6              | 190       | 8.29%   |
| Unknown           | 188       | 8.2%    |
| XFCE              | 170       | 7.41%   |
| X-Cinnamon        | 138       | 6.02%   |
| Pantheon          | 56        | 2.44%   |
| LXQt              | 52        | 2.27%   |
| MATE              | 40        | 1.74%   |
| KDE               | 27        | 1.18%   |
| Hyprland          | 17        | 0.74%   |
| Cinnamon          | 17        | 0.74%   |
| i3                | 13        | 0.57%   |
| Budgie            | 11        | 0.48%   |
| Unity             | 10        | 0.44%   |
| Deepin            | 8         | 0.35%   |
| KDE4              | 6         | 0.26%   |
| dwm               | 6         | 0.26%   |
| ICEWM             | 5         | 0.22%   |
| GNOME Flashback   | 5         | 0.22%   |
| bspwm             | 5         | 0.22%   |
| LXDE              | 4         | 0.17%   |
| GNOME Classic     | 4         | 0.17%   |
| Cutefish          | 4         | 0.17%   |
| sway              | 3         | 0.13%   |
| openbox           | 3         | 0.13%   |
| lightdm-xsession  | 3         | 0.13%   |
| Yaru:ubuntu:GNOME | 2         | 0.09%   |
| xmonad            | 2         | 0.09%   |
| qtile             | 2         | 0.09%   |
| niri              | 2         | 0.09%   |
| DDE               | 2         | 0.09%   |
| COSMIC            | 2         | 0.09%   |
| Phosh:GNOME       | 1         | 0.04%   |
| Peux Gnome        | 1         | 0.04%   |
| Lubuntu           | 1         | 0.04%   |
| Endless:GNOME     | 1         | 0.04%   |
| awesomeminimal    | 1         | 0.04%   |
| awesome           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1412      | 62.37%  |
| Wayland | 696       | 30.74%  |
| Unknown | 122       | 5.39%   |
| Tty     | 34        | 1.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 915       | 40.2%   |
| SDDM           | 490       | 21.53%  |
| GDM3           | 308       | 13.53%  |
| LightDM        | 258       | 11.34%  |
| GDM            | 249       | 10.94%  |
| TDM            | 37        | 1.63%   |
| KDM            | 5         | 0.22%   |
| LY-DM          | 4         | 0.18%   |
| SLiM           | 3         | 0.13%   |
| Ly             | 3         | 0.13%   |
| SLIMSKI        | 1         | 0.04%   |
| LXDM           | 1         | 0.04%   |
| GREETD         | 1         | 0.04%   |
| COSMIC-GREETER | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1815      | 81.83%  |
| id_ID   | 150       | 6.76%   |
| Unknown | 134       | 6.04%   |
| C       | 54        | 2.43%   |
| en_GB   | 29        | 1.31%   |
| en_SG   | 8         | 0.36%   |
| en_AU   | 6         | 0.27%   |
| en_AG   | 5         | 0.23%   |
| de_DE   | 3         | 0.14%   |
| ru_RU   | 2         | 0.09%   |
| fr_FR   | 2         | 0.09%   |
| en_IN   | 2         | 0.09%   |
| en_CA   | 2         | 0.09%   |
| jv_ID   | 1         | 0.05%   |
| it_IT   | 1         | 0.05%   |
| en_HK   | 1         | 0.05%   |
| de_CH   | 1         | 0.05%   |
| Default | 1         | 0.05%   |
| C.UTF8  | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1200      | 53.67%  |
| BIOS | 1036      | 46.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1539      | 68.61%  |
| Btrfs   | 296       | 13.2%   |
| Overlay | 195       | 8.69%   |
| Tmpfs   | 112       | 4.99%   |
| Unknown | 48        | 2.14%   |
| Xfs     | 30        | 1.34%   |
| Zfs     | 8         | 0.36%   |
| F2fs    | 8         | 0.36%   |
| Ext2    | 5         | 0.22%   |
| Ext3    | 2         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1095      | 48.86%  |
| Unknown | 893       | 39.85%  |
| MBR     | 253       | 11.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1922      | 86.15%  |
| Yes       | 309       | 13.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1318      | 58.89%  |
| Yes       | 920       | 41.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 471       | 21.53%  |
| ASUSTek Computer        | 431       | 19.7%   |
| Hewlett-Packard         | 270       | 12.34%  |
| Acer                    | 212       | 9.69%   |
| Dell                    | 153       | 6.99%   |
| MSI                     | 91        | 4.16%   |
| ASRock                  | 77        | 3.52%   |
| Gigabyte Technology     | 76        | 3.47%   |
| Toshiba                 | 48        | 2.19%   |
| Intel                   | 38        | 1.74%   |
| Unknown                 | 29        | 1.33%   |
| Apple                   | 28        | 1.28%   |
| AXIOO                   | 27        | 1.23%   |
| Biostar                 | 24        | 1.1%    |
| ECS                     | 22        | 1.01%   |
| Fujitsu                 | 15        | 0.69%   |
| ADVAN                   | 14        | 0.64%   |
| Sony                    | 13        | 0.59%   |
| Samsung Electronics     | 10        | 0.46%   |
| Infinix                 | 10        | 0.46%   |
| Valve                   | 9         | 0.41%   |
| HUAWEI                  | 7         | 0.32%   |
| AZW                     | 7         | 0.32%   |
| Panasonic               | 6         | 0.27%   |
| Timi                    | 5         | 0.23%   |
| Clevo                   | 5         | 0.23%   |
| Supermicro              | 4         | 0.18%   |
| Microsoft               | 4         | 0.18%   |
| Google                  | 4         | 0.18%   |
| realme                  | 3         | 0.14%   |
| Pegatron                | 3         | 0.14%   |
| OEM                     | 3         | 0.14%   |
| Foxconn                 | 3         | 0.14%   |
| Chuwi                   | 3         | 0.14%   |
| ZOTAC                   | 2         | 0.09%   |
| Wearnes                 | 2         | 0.09%   |
| Raspberry Pi Foundation | 2         | 0.09%   |
| Notebook                | 2         | 0.09%   |
| MicroByte               | 2         | 0.09%   |
| LORD ELECTRONICS        | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 36        | 1.65%   |
| HP Notebook                              | 17        | 0.78%   |
| Lenovo G40-45 80E1                       | 16        | 0.73%   |
| Lenovo IdeaPad 330-14AST 81D5            | 12        | 0.55%   |
| Intel H61                                | 11        | 0.5%    |
| Lenovo G400 20235                        | 9         | 0.41%   |
| HP Pavilion Aero Laptop 13-be0xxx        | 9         | 0.41%   |
| ASUS X441BA                              | 9         | 0.41%   |
| ADVAN 1701                               | 9         | 0.41%   |
| Acer Aspire 4752                         | 9         | 0.41%   |
| Valve Jupiter                            | 8         | 0.37%   |
| HP Pavilion g4                           | 8         | 0.37%   |
| HP 14                                    | 8         | 0.37%   |
| ASUS X456URK                             | 8         | 0.37%   |
| ASUS GL553VD                             | 8         | 0.37%   |
| ASUS All Series                          | 8         | 0.37%   |
| Acer Swift SF314-71                      | 8         | 0.37%   |
| Acer Aspire 4750                         | 8         | 0.37%   |
| Lenovo IdeaPad S340-14API 81NB           | 7         | 0.32%   |
| HP Laptop 14-bw0xx                       | 7         | 0.32%   |
| ASUS X200MA                              | 7         | 0.32%   |
| Lenovo IdeaPad 3 14IIL05 81WD            | 6         | 0.27%   |
| HP Laptop 14-bs0xx                       | 6         | 0.27%   |
| HP 1000                                  | 6         | 0.27%   |
| Dell OptiPlex 7010                       | 6         | 0.27%   |
| ASUS X455LF                              | 6         | 0.27%   |
| ASUS X441UV                              | 6         | 0.27%   |
| ASRock A320M-HDV R4.0                    | 6         | 0.27%   |
| Apple MacBookPro12,1                     | 6         | 0.27%   |
| Acer Swift SFX14-41G                     | 6         | 0.27%   |
| Acer Aspire E5-475G                      | 6         | 0.27%   |
| Lenovo IdeaPad 320-14AST 80XU            | 5         | 0.23%   |
| HP Pavilion 14                           | 5         | 0.23%   |
| ASUS X455YA                              | 5         | 0.23%   |
| ASUS X455LD                              | 5         | 0.23%   |
| ASUS X441NA                              | 5         | 0.23%   |
| ASUS VivoBook_ASUSLaptop X1404ZA_A1404ZA | 5         | 0.23%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA  | 5         | 0.23%   |
| ASUS Vivobook Go E1404FA_E1404FA         | 5         | 0.23%   |
| ADVAN 1405                               | 5         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 173       | 7.91%   |
| Lenovo IdeaPad     | 132       | 6.03%   |
| Acer Aspire        | 124       | 5.67%   |
| ASUS Vivobook      | 95        | 4.34%   |
| HP Laptop          | 54        | 2.47%   |
| Dell Latitude      | 54        | 2.47%   |
| HP Pavilion        | 49        | 2.24%   |
| Dell Inspiron      | 36        | 1.65%   |
| Unknown            | 36        | 1.65%   |
| Acer Swift         | 34        | 1.55%   |
| ASUS ASUS          | 32        | 1.46%   |
| HP EliteBook       | 30        | 1.37%   |
| Toshiba Satellite  | 28        | 1.28%   |
| Dell OptiPlex      | 24        | 1.1%    |
| ASUS ROG           | 20        | 0.91%   |
| Lenovo Yoga        | 19        | 0.87%   |
| ASUS TUF           | 18        | 0.82%   |
| HP Notebook        | 17        | 0.78%   |
| Dell Vostro        | 17        | 0.78%   |
| Acer Nitro         | 17        | 0.78%   |
| Lenovo G40-45      | 16        | 0.73%   |
| HP ProBook         | 16        | 0.73%   |
| Lenovo ThinkCentre | 15        | 0.69%   |
| Lenovo ThinkBook   | 12        | 0.55%   |
| AXIOO Mybook       | 12        | 0.55%   |
| Lenovo Legion      | 11        | 0.5%    |
| Intel H61          | 11        | 0.5%    |
| HP ENVY            | 11        | 0.5%    |
| ASUS PRIME         | 11        | 0.5%    |
| MSI Modern         | 10        | 0.46%   |
| Lenovo IdeaPadFlex | 10        | 0.46%   |
| HP Compaq          | 10        | 0.46%   |
| Lenovo G400        | 9         | 0.41%   |
| Infinix INBook     | 9         | 0.41%   |
| ASUS X441BA        | 9         | 0.41%   |
| ASRock A320M-HDV   | 9         | 0.41%   |
| ADVAN 1701         | 9         | 0.41%   |
| Valve Jupiter      | 8         | 0.37%   |
| Toshiba PORTEGE    | 8         | 0.37%   |
| HP 14              | 8         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 190       | 8.68%   |
| 2018    | 187       | 8.55%   |
| 2020    | 178       | 8.14%   |
| 2021    | 173       | 7.91%   |
| 2013    | 162       | 7.4%    |
| 2012    | 156       | 7.13%   |
| 2017    | 152       | 6.95%   |
| 2011    | 148       | 6.76%   |
| 2014    | 145       | 6.63%   |
| 2015    | 111       | 5.07%   |
| 2010    | 102       | 4.66%   |
| 2016    | 101       | 4.62%   |
| 2022    | 90        | 4.11%   |
| 2023    | 89        | 4.07%   |
| 2009    | 62        | 2.83%   |
| 2008    | 51        | 2.33%   |
| 2024    | 40        | 1.83%   |
| 2007    | 20        | 0.91%   |
| Unknown | 15        | 0.69%   |
| 2025    | 9         | 0.41%   |
| 2006    | 7         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1521      | 69.52%  |
| Desktop        | 501       | 22.9%   |
| Convertible    | 60        | 2.74%   |
| All in one     | 32        | 1.46%   |
| Server         | 25        | 1.14%   |
| Tablet         | 21        | 0.96%   |
| Mini pc        | 12        | 0.55%   |
| System on chip | 8         | 0.37%   |
| Phone          | 7         | 0.32%   |
| Other          | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2044      | 92.74%  |
| Enabled  | 160       | 7.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2182      | 99.73%  |
| Yes  | 6         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 650       | 29.32%  |
| 3.01-4.0        | 482       | 21.74%  |
| 8.01-16.0       | 432       | 19.49%  |
| 16.01-24.0      | 337       | 15.2%   |
| 1.01-2.0        | 125       | 5.64%   |
| 32.01-64.0      | 103       | 4.65%   |
| 24.01-32.0      | 38        | 1.71%   |
| 64.01-256.0     | 22        | 0.99%   |
| 2.01-3.0        | 18        | 0.81%   |
| 0.51-1.0        | 9         | 0.41%   |
| More than 256.0 | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 741       | 30.62%  |
| 2.01-3.0   | 669       | 27.64%  |
| 4.01-8.0   | 407       | 16.82%  |
| 3.01-4.0   | 370       | 15.29%  |
| 0.51-1.0   | 127       | 5.25%   |
| 8.01-16.0  | 74        | 3.06%   |
| 0.01-0.5   | 15        | 0.62%   |
| 16.01-24.0 | 11        | 0.45%   |
| 24.01-32.0 | 3         | 0.12%   |
| 32.01-64.0 | 2         | 0.08%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1461      | 65.17%  |
| 2       | 590       | 26.32%  |
| 3       | 116       | 5.17%   |
| 4       | 39        | 1.74%   |
| 5       | 13        | 0.58%   |
| 0       | 13        | 0.58%   |
| 7       | 3         | 0.13%   |
| 6       | 3         | 0.13%   |
| 15      | 1         | 0.04%   |
| 12      | 1         | 0.04%   |
| 8       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1623      | 73.47%  |
| Yes       | 586       | 26.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1765      | 80.56%  |
| No        | 426       | 19.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1887      | 85.85%  |
| No        | 311       | 14.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1491      | 67.5%   |
| No        | 718       | 32.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Indonesia | 2188      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Jakarta         | 572       | 23.92%  |
| Bandung         | 185       | 7.74%   |
| Surabaya        | 184       | 7.7%    |
| Yogyakarta      | 94        | 3.93%   |
| Bekasi          | 83        | 3.47%   |
| Semarang        | 80        | 3.35%   |
| Bogor           | 66        | 2.76%   |
| Malang          | 64        | 2.68%   |
| Tangerang       | 60        | 2.51%   |
| Denpasar        | 54        | 2.26%   |
| South Tangerang | 51        | 2.13%   |
| Medan           | 50        | 2.09%   |
| Depok           | 42        | 1.76%   |
| Palembang       | 29        | 1.21%   |
| Makassar        | 29        | 1.21%   |
| Bengkulu        | 24        | 1%      |
| Banjarmasin     | 22        | 0.92%   |
| Kediri          | 19        | 0.79%   |
| Surakarta       | 17        | 0.71%   |
| Sleman          | 17        | 0.71%   |
| Samarinda       | 16        | 0.67%   |
| Balikpapan      | 16        | 0.67%   |
| Pecenongan      | 14        | 0.59%   |
| Tasikmalaya     | 13        | 0.54%   |
| Pontianak       | 13        | 0.54%   |
| Pekanbaru       | 13        | 0.54%   |
| Pasuruan        | 13        | 0.54%   |
| Magelang        | 13        | 0.54%   |
| Cirebon         | 13        | 0.54%   |
| Batam           | 13        | 0.54%   |
| Gresik          | 12        | 0.5%    |
| Sidoarjo        | 11        | 0.46%   |
| Blitar          | 11        | 0.46%   |
| Banda Aceh      | 11        | 0.46%   |
| Padang          | 10        | 0.42%   |
| Jember          | 10        | 0.42%   |
| Brebes          | 9         | 0.38%   |
| Bandar Lampung  | 9         | 0.38%   |
| Mataram         | 8         | 0.33%   |
| Kudus           | 8         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 497       | 669    | 16.39%  |
| WDC                         | 363       | 475    | 11.97%  |
| Samsung Electronics         | 273       | 357    | 9%      |
| Toshiba                     | 219       | 248    | 7.22%   |
| SanDisk                     | 132       | 154    | 4.35%   |
| HGST                        | 96        | 113    | 3.17%   |
| Unknown                     | 95        | 124    | 3.13%   |
| Hitachi                     | 86        | 106    | 2.84%   |
| V-GeN                       | 85        | 95     | 2.8%    |
| Intel                       | 82        | 105    | 2.7%    |
| Micron Technology           | 77        | 97     | 2.54%   |
| A-DATA Technology           | 77        | 92     | 2.54%   |
| SK hynix                    | 73        | 87     | 2.41%   |
| Kingston                    | 67        | 82     | 2.21%   |
| China                       | 49        | 56     | 1.62%   |
| MidasForce                  | 48        | 57     | 1.58%   |
| Unknown                     | 47        | 51     | 1.55%   |
| Silicon Motion              | 44        | 54     | 1.45%   |
| ADATA Technology            | 36        | 54     | 1.19%   |
| Team                        | 31        | 36     | 1.02%   |
| RX7                         | 22        | 29     | 0.73%   |
| VISIPRO                     | 21        | 26     | 0.69%   |
| Apacer                      | 21        | 24     | 0.69%   |
| KIOXIA                      | 20        | 27     | 0.66%   |
| Phison Electronics          | 19        | 21     | 0.63%   |
| JMicron Technology          | 19        | 20     | 0.63%   |
| EYOTA                       | 19        | 23     | 0.63%   |
| Patriot                     | 17        | 32     | 0.56%   |
| MAXIO Technology (Hangzhou) | 17        | 19     | 0.56%   |
| Crucial                     | 14        | 16     | 0.46%   |
| Realtek Semiconductor       | 13        | 13     | 0.43%   |
| Kingston Technology Company | 13        | 14     | 0.43%   |
| Fujitsu                     | 13        | 14     | 0.43%   |
| Apple                       | 13        | 15     | 0.43%   |
| RESCUE                      | 11        | 17     | 0.36%   |
| PNY                         | 10        | 12     | 0.33%   |
| Transcend                   | 9         | 13     | 0.3%    |
| Hewlett-Packard             | 9         | 11     | 0.3%    |
| SCY                         | 8         | 12     | 0.26%   |
| Pioneer                     | 8         | 9      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                                    | 64        | 2%      |
| Seagate ST1000LM035-1RK172 1TB                                     | 56        | 1.75%   |
| Unknown                                                            | 47        | 1.47%   |
| Toshiba MQ01ABF050 500GB                                           | 43        | 1.35%   |
| Toshiba MQ04ABF100 1TB                                             | 40        | 1.25%   |
| Seagate ST500DM002-1BD142 500GB                                    | 34        | 1.06%   |
| Seagate ST3500312CS 500GB                                          | 27        | 0.84%   |
| HGST HTS545050A7E680 500GB                                         | 25        | 0.78%   |
| Toshiba MQ01ABD100 1TB                                             | 24        | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB              | 24        | 0.75%   |
| A-DATA SU650 120GB SSD                                             | 24        | 0.75%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 20        | 0.63%   |
| Seagate ST9320325AS 320GB                                          | 19        | 0.59%   |
| Unknown MMC Card  32GB                                             | 17        | 0.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                  | 17        | 0.53%   |
| Seagate ST500LT012-9WS142 500GB                                    | 16        | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                                     | 16        | 0.5%    |
| MidasForce SSD 128GB                                               | 16        | 0.5%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB                   | 16        | 0.5%    |
| Hitachi HTS543232A7A384 320GB                                      | 16        | 0.5%    |
| HGST HTS721010A9E630 1TB                                           | 16        | 0.5%    |
| A-DATA SU650 240GB SSD                                             | 15        | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                   | 14        | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                                 | 13        | 0.41%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                              | 13        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                                       | 13        | 0.41%   |
| Hitachi HTS545050A7E380 500GB                                      | 13        | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB                                       | 12        | 0.38%   |
| Unknown MMC Card  64GB                                             | 12        | 0.38%   |
| Unknown MMC Card  128GB                                            | 12        | 0.38%   |
| Seagate ST1000DM003-1ER162 1TB                                     | 12        | 0.38%   |
| Samsung SSD 860 EVO 250GB                                          | 12        | 0.38%   |
| Samsung SSD 850 EVO 250GB                                          | 12        | 0.38%   |
| Micron 2450_MTFDKBA512TFK 512GB                                    | 12        | 0.38%   |
| Kingston SA400S37240G 240GB SSD                                    | 12        | 0.38%   |
| JMicron Generic 320GB                                              | 12        | 0.38%   |
| Seagate ST9500325AS 500GB                                          | 11        | 0.34%   |
| Seagate ST1000LM049-2GH172 1TB                                     | 11        | 0.34%   |
| Kingston SA400S37120G 120GB SSD                                    | 11        | 0.34%   |
| Intel SSDPEKNW512G8 512GB                                          | 11        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 489       | 654    | 39.63%  |
| WDC                 | 289       | 378    | 23.42%  |
| Toshiba             | 189       | 213    | 15.32%  |
| HGST                | 96        | 113    | 7.78%   |
| Hitachi             | 86        | 106    | 6.97%   |
| Samsung Electronics | 13        | 13     | 1.05%   |
| JMicron Technology  | 12        | 12     | 0.97%   |
| Fujitsu             | 11        | 11     | 0.89%   |
| Unknown             | 10        | 11     | 0.81%   |
| Hewlett-Packard     | 7         | 9      | 0.57%   |
| External            | 6         | 6      | 0.49%   |
| Maxtor              | 4         | 4      | 0.32%   |
| Apple               | 4         | 4      | 0.32%   |
| USB3.0              | 3         | 3      | 0.24%   |
| TO Exter            | 2         | 2      | 0.16%   |
| SAGE                | 2         | 2      | 0.16%   |
| Unknown             | 2         | 2      | 0.16%   |
| T-FORCE             | 1         | 1      | 0.08%   |
| SYMTEC              | 1         | 1      | 0.08%   |
| StoreJet            | 1         | 1      | 0.08%   |
| Shenzhen            | 1         | 1      | 0.08%   |
| SATAFIRM            | 1         | 1      | 0.08%   |
| Lenovo              | 1         | 3      | 0.08%   |
| HGST HTS            | 1         | 3      | 0.08%   |
| ExcelStor           | 1         | 1      | 0.08%   |
| CLOVER              | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 114       | 152    | 13.78%  |
| V-GeN               | 60        | 69     | 7.26%   |
| A-DATA Technology   | 60        | 72     | 7.26%   |
| MidasForce          | 47        | 56     | 5.68%   |
| WDC                 | 46        | 57     | 5.56%   |
| SanDisk             | 46        | 60     | 5.56%   |
| Kingston            | 46        | 53     | 5.56%   |
| China               | 45        | 52     | 5.44%   |
| Unknown             | 25        | 27     | 3.02%   |
| Team                | 21        | 26     | 2.54%   |
| Apacer              | 21        | 24     | 2.54%   |
| Patriot             | 17        | 32     | 2.06%   |
| RX7                 | 16        | 20     | 1.93%   |
| VISIPRO             | 15        | 20     | 1.81%   |
| Intel               | 13        | 17     | 1.57%   |
| EYOTA               | 13        | 16     | 1.57%   |
| Toshiba             | 11        | 12     | 1.33%   |
| Crucial             | 11        | 13     | 1.33%   |
| RESCUE              | 8         | 14     | 0.97%   |
| Pioneer             | 8         | 9      | 0.97%   |
| Micron Technology   | 8         | 14     | 0.97%   |
| Apple               | 8         | 9      | 0.97%   |
| Transcend           | 7         | 10     | 0.85%   |
| Seagate             | 7         | 10     | 0.85%   |
| Ramos Technology    | 7         | 25     | 0.85%   |
| Colorful            | 7         | 7      | 0.85%   |
| SK hynix            | 6         | 9      | 0.73%   |
| PNY                 | 6         | 6      | 0.73%   |
| LITEON              | 6         | 10     | 0.73%   |
| FORESEE             | 6         | 6      | 0.73%   |
| XSTAR               | 5         | 5      | 0.6%    |
| Wellcomm            | 5         | 5      | 0.6%    |
| LITEONIT            | 5         | 6      | 0.6%    |
| Varro               | 4         | 4      | 0.48%   |
| T-FORCE             | 4         | 4      | 0.48%   |
| Lexar               | 4         | 4      | 0.48%   |
| DST                 | 4         | 5      | 0.48%   |
| Unknown             | 3         | 4      | 0.36%   |
| SPCC                | 3         | 3      | 0.36%   |
| OCZ                 | 3         | 3      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1096      | 1556   | 39.9%   |
| SSD     | 747       | 1034   | 27.19%  |
| NVMe    | 732       | 981    | 26.65%  |
| Unknown | 94        | 110    | 3.42%   |
| MMC     | 78        | 106    | 2.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1571      | 2586   | 63.24%  |
| NVMe | 732       | 977    | 29.47%  |
| SAS  | 103       | 118    | 4.15%   |
| MMC  | 78        | 106    | 3.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1201      | 1788   | 66.87%  |
| 0.51-1.0   | 474       | 633    | 26.39%  |
| 1.01-2.0   | 85        | 125    | 4.73%   |
| 3.01-4.0   | 16        | 22     | 0.89%   |
| 4.01-10.0  | 10        | 12     | 0.56%   |
| 2.01-3.0   | 9         | 9      | 0.5%    |
| 10.01-20.0 | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 656       | 28.28%  |
| 251-500        | 557       | 24.01%  |
| 501-1000       | 278       | 11.98%  |
| 51-100         | 224       | 9.66%   |
| 1-20           | 168       | 7.24%   |
| 1001-2000      | 154       | 6.64%   |
| 21-50          | 126       | 5.43%   |
| Unknown        | 70        | 3.02%   |
| More than 3000 | 50        | 2.16%   |
| 2001-3000      | 37        | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 872       | 36.44%  |
| 21-50          | 447       | 18.68%  |
| 101-250        | 323       | 13.5%   |
| 51-100         | 288       | 12.04%  |
| 251-500        | 199       | 8.32%   |
| 501-1000       | 113       | 4.72%   |
| Unknown        | 70        | 2.93%   |
| 1001-2000      | 43        | 1.8%    |
| 2001-3000      | 18        | 0.75%   |
| More than 3000 | 17        | 0.71%   |
| 0              | 3         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                 | Computers | Drives | Percent |
|-------------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                       | 15        | 16     | 4.53%   |
| Seagate ST500DM002-1BD142 500GB                       | 12        | 14     | 3.63%   |
| HGST HTS545050A7E680 500GB                            | 10        | 11     | 3.02%   |
| Seagate ST500LT012-9WS142 500GB                       | 8         | 8      | 2.42%   |
| Seagate ST9320325AS 320GB                             | 6         | 7      | 1.81%   |
| Toshiba MQ01ABF050 500GB                              | 5         | 5      | 1.51%   |
| Seagate ST9500325AS 500GB                             | 5         | 5      | 1.51%   |
| Seagate ST1000LM035-1RK172 1TB                        | 5         | 5      | 1.51%   |
| Hitachi HTS543232A7A384 320GB                         | 5         | 5      | 1.51%   |
| HGST HTS545050A7E380 500GB                            | 5         | 6      | 1.51%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                  | 4         | 6      | 1.21%   |
| Unknown                                               | 4         | 4      | 1.21%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 3         | 3      | 0.91%   |
| WDC WD5000LPVX-22V0TT0 500GB                          | 3         | 4      | 0.91%   |
| Toshiba MQ01ABD050 500GB                              | 3         | 3      | 0.91%   |
| Toshiba MQ01ABD032 320GB                              | 3         | 3      | 0.91%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 3         | 4      | 0.91%   |
| Seagate ST9250410AS 250GB                             | 3         | 5      | 0.91%   |
| Seagate ST320LT012-9WS14C 320GB                       | 3         | 3      | 0.91%   |
| Seagate ST250DM000-1BD141 250GB                       | 3         | 3      | 0.91%   |
| Seagate ST1000LX015-1U7172 1TB                        | 3         | 4      | 0.91%   |
| Seagate ST1000DM003-1ER162 1TB                        | 3         | 3      | 0.91%   |
| Hitachi HTS545050B9A300 500GB                         | 3         | 4      | 0.91%   |
| Hitachi HTS545050A7E380 500GB                         | 3         | 3      | 0.91%   |
| Hitachi HTS545032B9A300 320GB                         | 3         | 3      | 0.91%   |
| HGST HTS725050A7E630 500GB                            | 3         | 3      | 0.91%   |
| WDC WD800JD-08LSA0 80GB                               | 2         | 2      | 0.6%    |
| WDC WD5000LPVX-80V0TT0 500GB                          | 2         | 2      | 0.6%    |
| WDC WD5000AAKX-75U6AA0 500GB                          | 2         | 2      | 0.6%    |
| WDC WD5000AAKX-08U6AA0 500GB                          | 2         | 2      | 0.6%    |
| WDC WD3200BEKT-60V5T1 320GB                           | 2         | 2      | 0.6%    |
| WDC WD3200AAKS-61L9A0 320GB                           | 2         | 3      | 0.6%    |
| WDC WD2000FYYZ-01UL1B1 2TB                            | 2         | 3      | 0.6%    |
| WDC WD10JPVX-60JC3T1 1TB                              | 2         | 2      | 0.6%    |
| WDC WD10JPCX-24UE4T0 1TB                              | 2         | 4      | 0.6%    |
| WDC WD10EZEX-08M2NA0 1TB                              | 2         | 2      | 0.6%    |
| Toshiba MQ01ABD100 1TB                                | 2         | 2      | 0.6%    |
| Toshiba MK5059GSXP 500GB                              | 2         | 2      | 0.6%    |
| Toshiba MK3265GSX 320GB                               | 2         | 3      | 0.6%    |
| Seagate ST9500420AS 500GB                             | 2         | 2      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 100       | 127    | 31.15%  |
| WDC                 | 65        | 77     | 20.25%  |
| Toshiba             | 32        | 35     | 9.97%   |
| Hitachi             | 28        | 29     | 8.72%   |
| HGST                | 24        | 27     | 7.48%   |
| Samsung Electronics | 7         | 8      | 2.18%   |
| SK hynix            | 6         | 8      | 1.87%   |
| A-DATA Technology   | 6         | 8      | 1.87%   |
| SanDisk             | 4         | 4      | 1.25%   |
| Micron Technology   | 4         | 4      | 1.25%   |
| Kingston            | 4         | 5      | 1.25%   |
| China               | 4         | 7      | 1.25%   |
| Unknown             | 4         | 4      | 1.25%   |
| Silicon Motion      | 3         | 4      | 0.93%   |
| Intel               | 3         | 3      | 0.93%   |
| VISIPRO             | 2         | 4      | 0.62%   |
| V-GeN               | 2         | 3      | 0.62%   |
| KLEVV               | 2         | 2      | 0.62%   |
| Fujitsu             | 2         | 2      | 0.62%   |
| Crucial             | 2         | 2      | 0.62%   |
| Apacer              | 2         | 3      | 0.62%   |
| Xinsujie            | 1         | 1      | 0.31%   |
| WellcommMaster      | 1         | 1      | 0.31%   |
| Wellcomm            | 1         | 1      | 0.31%   |
| ValueTech           | 1         | 1      | 0.31%   |
| Unknown             | 1         | 1      | 0.31%   |
| T-FORCE             | 1         | 1      | 0.31%   |
| SM200               | 1         | 1      | 0.31%   |
| RX7                 | 1         | 1      | 0.31%   |
| Maxtor              | 1         | 1      | 0.31%   |
| EYOTA               | 1         | 1      | 0.31%   |
| Colorful            | 1         | 1      | 0.31%   |
| CLOVER              | 1         | 1      | 0.31%   |
| BODI                | 1         | 1      | 0.31%   |
| Apple               | 1         | 1      | 0.31%   |
| ADATA Technology    | 1         | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 99        | 123    | 38.98%  |
| WDC                 | 61        | 73     | 24.02%  |
| Toshiba             | 32        | 35     | 12.6%   |
| Hitachi             | 28        | 29     | 11.02%  |
| HGST                | 24        | 27     | 9.45%   |
| Samsung Electronics | 3         | 3      | 1.18%   |
| Fujitsu             | 2         | 2      | 0.79%   |
| Unknown             | 1         | 1      | 0.39%   |
| Maxtor              | 1         | 1      | 0.39%   |
| CLOVER              | 1         | 1      | 0.39%   |
| Apple               | 1         | 1      | 0.39%   |
| Unknown             | 1         | 1      | 0.39%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 236       | 297    | 78.15%  |
| SSD  | 52        | 66     | 17.22%  |
| NVMe | 14        | 18     | 4.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2         | 2      | 16.67%  |
| Seagate ST3250318AS 250GB                        | 2         | 2      | 16.67%  |
| WDC WD5000BPVT-60HXZT1 500GB                     | 1         | 1      | 8.33%   |
| Toshiba MK6475GSX 640GB                          | 1         | 1      | 8.33%   |
| Toshiba MK2575GSX 250GB                          | 1         | 1      | 8.33%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD 500GB | 1         | 1      | 8.33%   |
| Hitachi HTS545050B9A300 500GB                    | 1         | 1      | 8.33%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 8.33%   |
| Hitachi HTS543232A7A384 320GB                    | 1         | 1      | 8.33%   |
| A-DATA Technology SX8200PNP 256GB                | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 4         | 4      | 33.33%  |
| Hitachi           | 3         | 3      | 25%     |
| Toshiba           | 2         | 2      | 16.67%  |
| WDC               | 1         | 1      | 8.33%   |
| Sandisk           | 1         | 1      | 8.33%   |
| A-DATA Technology | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1124      | 1848   | 46.62%  |
| Works    | 982       | 1546   | 40.73%  |
| Malfunc  | 294       | 381    | 12.19%  |
| Failed   | 11        | 12     | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1463      | 55.06%  |
| AMD                                     | 397       | 14.94%  |
| Samsung Electronics                     | 159       | 5.98%   |
| SanDisk                                 | 116       | 4.37%   |
| Micron Technology                       | 70        | 2.63%   |
| SK hynix                                | 66        | 2.48%   |
| Silicon Motion                          | 58        | 2.18%   |
| ADATA Technology                        | 56        | 2.11%   |
| Phison Electronics                      | 35        | 1.32%   |
| Kingston Technology Company             | 33        | 1.24%   |
| MAXIO Technology (Hangzhou)             | 23        | 0.87%   |
| KIOXIA                                  | 21        | 0.79%   |
| Realtek Semiconductor                   | 20        | 0.75%   |
| ASMedia Technology                      | 18        | 0.68%   |
| Toshiba America Info Systems            | 17        | 0.64%   |
| JMicron Technology                      | 10        | 0.38%   |
| Shenzhen Shichuangyi Electronics        | 9         | 0.34%   |
| Shenzhen Longsys Electronics            | 9         | 0.34%   |
| Union Memory (Shenzhen)                 | 8         | 0.3%    |
| Broadcom / LSI                          | 8         | 0.3%    |
| Solidigm                                | 6         | 0.23%   |
| Nvidia                                  | 6         | 0.23%   |
| Silicon Integrated Systems [SiS]        | 5         | 0.19%   |
| Marvell Technology Group                | 5         | 0.19%   |
| VIA Technologies                        | 4         | 0.15%   |
| Micron/Crucial Technology               | 4         | 0.15%   |
| INNOGRIT                                | 4         | 0.15%   |
| Hewlett-Packard                         | 4         | 0.15%   |
| Seagate Technology                      | 3         | 0.11%   |
| O2 Micro                                | 3         | 0.11%   |
| LSI Logic / Symbios Logic               | 3         | 0.11%   |
| Shenzhen Unionmemory Information System | 2         | 0.08%   |
| Hosin Global Electronics                | 2         | 0.08%   |
| Biwin Storage Technology                | 2         | 0.08%   |
| Adaptec                                 | 2         | 0.08%   |
| TenaFe                                  | 1         | 0.04%   |
| Solid State Storage Technology          | 1         | 0.04%   |
| Lenovo                                  | 1         | 0.04%   |
| Foxconn International                   | 1         | 0.04%   |
| Apple                                   | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 299       | 10.05%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 155       | 5.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 127       | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 78        | 2.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 73        | 2.45%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 68        | 2.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 66        | 2.22%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 65        | 2.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 62        | 2.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 55        | 1.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 51        | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 50        | 1.68%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 46        | 1.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 43        | 1.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 42        | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 40        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 39        | 1.31%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 37        | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 34        | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 34        | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 33        | 1.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 32        | 1.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 31        | 1.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 30        | 1.01%   |
| Intel SSD 660P Series                                                                   | 28        | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 27        | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 27        | 0.91%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 25        | 0.84%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 25        | 0.84%   |
| AMD 500 Series Chipset SATA Controller                                                  | 25        | 0.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 24        | 0.81%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 23        | 0.77%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 23        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 22        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 22        | 0.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 21        | 0.71%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 20        | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 20        | 0.67%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 19        | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 19        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1566      | 57.91%  |
| NVMe | 732       | 27.07%  |
| IDE  | 221       | 8.17%   |
| RAID | 179       | 6.62%   |
| SAS  | 5         | 0.18%   |
| SCSI | 1         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1624      | 74.22%  |
| AMD      | 547       | 25%     |
| ARM      | 13        | 0.59%   |
| QUALCOMM | 4         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 32        | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 30        | 1.37%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 27        | 1.23%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 24        | 1.09%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 24        | 1.09%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 22        | 1%      |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 21        | 0.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 21        | 0.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.91%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 20        | 0.91%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 19        | 0.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 0.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 18        | 0.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 18        | 0.82%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 17        | 0.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 16        | 0.73%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 15        | 0.68%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 15        | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.64%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 14        | 0.64%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 14        | 0.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 0.64%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 14        | 0.64%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 14        | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 13        | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 13        | 0.59%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 13        | 0.59%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 13        | 0.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 12        | 0.55%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 0.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 12        | 0.55%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 12        | 0.55%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 11        | 0.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 11        | 0.5%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 11        | 0.5%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 11        | 0.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 0.5%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 11        | 0.5%    |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 11        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 476       | 21.72%  |
| Intel Core i3           | 288       | 13.14%  |
| Intel Core i7           | 264       | 12.04%  |
| Other                   | 241       | 10.99%  |
| Intel Celeron           | 155       | 7.07%   |
| AMD Ryzen 5             | 146       | 6.66%   |
| Intel Core 2 Duo        | 76        | 3.47%   |
| AMD Ryzen 7             | 71        | 3.24%   |
| AMD Ryzen 3             | 61        | 2.78%   |
| Intel Pentium           | 43        | 1.96%   |
| AMD A8                  | 38        | 1.73%   |
| Intel Xeon              | 36        | 1.64%   |
| Intel Atom              | 27        | 1.23%   |
| AMD A4                  | 21        | 0.96%   |
| Intel Pentium Dual-Core | 20        | 0.91%   |
| AMD A6                  | 19        | 0.87%   |
| AMD Ryzen 9             | 16        | 0.73%   |
| AMD Ryzen 5 PRO         | 15        | 0.68%   |
| AMD FX                  | 15        | 0.68%   |
| AMD Athlon              | 15        | 0.68%   |
| Intel Core 2 Quad       | 14        | 0.64%   |
| AMD E1                  | 13        | 0.59%   |
| AMD E                   | 11        | 0.5%    |
| AMD A10                 | 11        | 0.5%    |
| Intel Core 2            | 8         | 0.36%   |
| AMD E2                  | 8         | 0.36%   |
| Intel Pentium Dual      | 7         | 0.32%   |
| Intel Genuine           | 7         | 0.32%   |
| Intel Core              | 7         | 0.32%   |
| AMD Athlon II X2        | 6         | 0.27%   |
| Intel Xeon Bronze       | 4         | 0.18%   |
| Intel Pentium Gold      | 4         | 0.18%   |
| AMD Ryzen 7 PRO         | 4         | 0.18%   |
| AMD Phenom II X6        | 4         | 0.18%   |
| AMD Athlon X4           | 4         | 0.18%   |
| QUALCOMM AArch64        | 3         | 0.14%   |
| Intel Xeon Silver       | 3         | 0.14%   |
| Intel Pentium Silver    | 3         | 0.14%   |
| AMD Phenom II X4        | 3         | 0.14%   |
| AMD C-60                | 3         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1101      | 50.21%  |
| 4       | 666       | 30.37%  |
| 6       | 196       | 8.94%   |
| 8       | 117       | 5.34%   |
| 10      | 34        | 1.55%   |
| 12      | 24        | 1.09%   |
| 1       | 20        | 0.91%   |
| 14      | 18        | 0.82%   |
| 16      | 7         | 0.32%   |
| 3       | 5         | 0.23%   |
| Unknown | 3         | 0.14%   |
| 44      | 1         | 0.05%   |
| 28      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2169      | 99.13%  |
| 2       | 14        | 0.64%   |
| Unknown | 3         | 0.14%   |
| 3       | 2         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1495      | 68.23%  |
| 1       | 693       | 31.63%  |
| Unknown | 3         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2157      | 98.58%  |
| Unknown        | 22        | 1.01%   |
| 64-bit         | 5         | 0.23%   |
| 32-bit         | 4         | 0.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1108      | 48.81%  |
| 0x206a7    | 99        | 4.36%   |
| 0x306a9    | 90        | 3.96%   |
| 0x1067a    | 51        | 2.25%   |
| 0x40651    | 44        | 1.94%   |
| 0x306c3    | 44        | 1.94%   |
| 0x806ec    | 35        | 1.54%   |
| 0x806ea    | 35        | 1.54%   |
| 0x306d4    | 34        | 1.5%    |
| 0x906ea    | 32        | 1.41%   |
| 0x06006705 | 31        | 1.37%   |
| 0x08108109 | 30        | 1.32%   |
| 0x806e9    | 29        | 1.28%   |
| 0x806c1    | 27        | 1.19%   |
| 0x406e3    | 27        | 1.19%   |
| 0x20655    | 25        | 1.1%    |
| 0x0a50000c | 21        | 0.93%   |
| 0x906e9    | 20        | 0.88%   |
| 0x08108102 | 19        | 0.84%   |
| 0x6fd      | 18        | 0.79%   |
| 0x806eb    | 16        | 0.7%    |
| 0x07030105 | 16        | 0.7%    |
| 0x20652    | 15        | 0.66%   |
| 0x706e5    | 14        | 0.62%   |
| 0x706a8    | 14        | 0.62%   |
| 0x30678    | 14        | 0.62%   |
| 0x08608103 | 14        | 0.62%   |
| 0x406c4    | 12        | 0.53%   |
| 0x06001119 | 12        | 0.53%   |
| 0x506e3    | 11        | 0.48%   |
| 0x0810100b | 11        | 0.48%   |
| 0x406c3    | 10        | 0.44%   |
| 0x10676    | 10        | 0.44%   |
| 0x08600104 | 10        | 0.44%   |
| 0x706a1    | 8         | 0.35%   |
| 0x0700010f | 8         | 0.35%   |
| 0x906a3    | 7         | 0.31%   |
| 0x6fb      | 7         | 0.31%   |
| 0x08101007 | 7         | 0.31%   |
| 0x06006704 | 7         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| KabyLake           | 332       | 15.16%  |
| SandyBridge        | 173       | 7.9%    |
| IvyBridge          | 172       | 7.85%   |
| Unknown            | 161       | 7.35%   |
| Haswell            | 145       | 6.62%   |
| Skylake            | 96        | 4.38%   |
| Penryn             | 91        | 4.16%   |
| Zen+               | 77        | 3.52%   |
| Westmere           | 74        | 3.38%   |
| TigerLake          | 74        | 3.38%   |
| Zen 3              | 71        | 3.24%   |
| Broadwell          | 68        | 3.11%   |
| Excavator          | 67        | 3.06%   |
| Silvermont         | 66        | 3.01%   |
| Alderlake Hybrid   | 59        | 2.69%   |
| Zen 2              | 53        | 2.42%   |
| Goldmont plus      | 48        | 2.19%   |
| Icelake            | 45        | 2.05%   |
| Zen                | 40        | 1.83%   |
| Core               | 40        | 1.83%   |
| Puma               | 39        | 1.78%   |
| CometLake          | 36        | 1.64%   |
| Piledriver         | 30        | 1.37%   |
| Bobcat             | 20        | 0.91%   |
| Goldmont           | 17        | 0.78%   |
| K10                | 14        | 0.64%   |
| Bonnell            | 13        | 0.59%   |
| Nehalem            | 12        | 0.55%   |
| Jaguar             | 11        | 0.5%    |
| Tremont            | 10        | 0.46%   |
| K10 Llano          | 10        | 0.46%   |
| Steamroller        | 8         | 0.37%   |
| Gracemont          | 5         | 0.23%   |
| K8 Hammer          | 4         | 0.18%   |
| P6                 | 2         | 0.09%   |
| NetBurst           | 2         | 0.09%   |
| Meteorlake Hybrid  | 2         | 0.09%   |
| Bulldozer          | 2         | 0.09%   |
| ArrowLake-H Hybrid | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1415      | 53.2%   |
| AMD                              | 661       | 24.85%  |
| Nvidia                           | 555       | 20.86%  |
| Matrox Electronics Systems       | 16        | 0.6%    |
| ASPEED Technology                | 6         | 0.23%   |
| Silicon Integrated Systems [SiS] | 5         | 0.19%   |
| Silicon Motion                   | 1         | 0.04%   |
| 3Com                             | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 144       | 5.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 106       | 3.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 73        | 2.66%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 71        | 2.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 70        | 2.55%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 60        | 2.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 58        | 2.12%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 55        | 2.01%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 53        | 1.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 50        | 1.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 50        | 1.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 46        | 1.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 46        | 1.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 44        | 1.6%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 38        | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 1.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 34        | 1.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 33        | 1.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 33        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 33        | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 33        | 1.2%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 31        | 1.13%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 30        | 1.09%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 30        | 1.09%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 28        | 1.02%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 28        | 1.02%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 28        | 1.02%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 27        | 0.98%   |
| AMD Lucienne                                                                             | 27        | 0.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 26        | 0.95%   |
| AMD Rembrandt [Radeon 680M]                                                              | 25        | 0.91%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 24        | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 20        | 0.73%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 19        | 0.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 19        | 0.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 19        | 0.69%   |
| Nvidia GT218 [GeForce 210]                                                               | 17        | 0.62%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 17        | 0.62%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 17        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 984       | 44.73%  |
| 1 x AMD                | 472       | 21.45%  |
| Intel + Nvidia         | 324       | 14.73%  |
| 1 x Nvidia             | 159       | 7.23%   |
| Intel + AMD            | 75        | 3.41%   |
| AMD + Nvidia           | 64        | 2.91%   |
| 2 x AMD                | 51        | 2.32%   |
| Other                  | 20        | 0.91%   |
| 2 x Intel              | 18        | 0.82%   |
| 1 x Matrox             | 16        | 0.73%   |
| 1 x SiS                | 5         | 0.23%   |
| 1 x ASPEED             | 4         | 0.18%   |
| 2 x Nvidia             | 3         | 0.14%   |
| Nvidia + ASPEED        | 2         | 0.09%   |
| 1 x Silicon Motion     | 1         | 0.05%   |
| 1 x Intel + 4 x Nvidia | 1         | 0.05%   |
| Intel + 3Com           | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1863      | 83.92%  |
| Proprietary | 239       | 10.77%  |
| Unknown     | 118       | 5.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1461      | 65.17%  |
| 1.01-2.0   | 276       | 12.31%  |
| 0.01-0.5   | 239       | 10.66%  |
| 0.51-1.0   | 114       | 5.08%   |
| 3.01-4.0   | 87        | 3.88%   |
| 7.01-8.0   | 26        | 1.16%   |
| 5.01-6.0   | 21        | 0.94%   |
| 8.01-16.0  | 12        | 0.54%   |
| 2.01-3.0   | 6         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 351       | 15.61%  |
| Chimei Innolux          | 337       | 14.98%  |
| BOE                     | 292       | 12.98%  |
| Samsung Electronics     | 203       | 9.03%   |
| LG Display              | 201       | 8.94%   |
| Goldstar                | 170       | 7.56%   |
| Lenovo                  | 86        | 3.82%   |
| Dell                    | 67        | 2.98%   |
| Hewlett-Packard         | 44        | 1.96%   |
| InfoVision              | 34        | 1.51%   |
| AOC                     | 34        | 1.51%   |
| Sharp                   | 30        | 1.33%   |
| Acer                    | 30        | 1.33%   |
| PANDA                   | 27        | 1.2%    |
| Apple                   | 27        | 1.2%    |
| ViewSonic               | 23        | 1.02%   |
| Philips                 | 19        | 0.84%   |
| Mi                      | 17        | 0.76%   |
| BenQ                    | 14        | 0.62%   |
| InnoLux Display         | 12        | 0.53%   |
| Chi Mei Optoelectronics | 12        | 0.53%   |
| HKC                     | 10        | 0.44%   |
| Valve                   | 9         | 0.4%    |
| Toshiba                 | 9         | 0.4%    |
| MSI                     | 9         | 0.4%    |
| LG Electronics          | 9         | 0.4%    |
| Ancor Communications    | 9         | 0.4%    |
| Panasonic               | 7         | 0.31%   |
| CPT                     | 7         | 0.31%   |
| TMX                     | 6         | 0.27%   |
| LG Philips              | 6         | 0.27%   |
| HannStar                | 6         | 0.27%   |
| Unknown                 | 5         | 0.22%   |
| RTK                     | 5         | 0.22%   |
| KDC                     | 5         | 0.22%   |
| HJC                     | 5         | 0.22%   |
| Unknown (XXX)           | 4         | 0.18%   |
| Sony                    | 4         | 0.18%   |
| Quanta Display          | 4         | 0.18%   |
| KDB                     | 4         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 32        | 1.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 30        | 1.32%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 27        | 1.19%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 24        | 1.05%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 24        | 1.05%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 23        | 1.01%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 22        | 0.97%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 22        | 0.97%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 19        | 0.83%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 17        | 0.75%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 17        | 0.75%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 17        | 0.75%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 15        | 0.66%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 14        | 0.62%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 13        | 0.57%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 13        | 0.57%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 13        | 0.57%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 13        | 0.57%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 13        | 0.57%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 13        | 0.57%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 12        | 0.53%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 12        | 0.53%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 11        | 0.48%   |
| BOE LCD Monitor BOE07F7 1920x1080 309x174mm 14.0-inch                 | 11        | 0.48%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 10        | 0.44%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 10        | 0.44%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 10        | 0.44%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 9         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch       | 9         | 0.4%    |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                  | 9         | 0.4%    |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 9         | 0.4%    |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                    | 9         | 0.4%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 8         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 8         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 8         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch       | 8         | 0.35%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                  | 8         | 0.35%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 7         | 0.31%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 7         | 0.31%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 7         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 863       | 39.77%  |
| 1920x1080 (FHD)    | 804       | 37.05%  |
| 1920x1200 (WUXGA)  | 83        | 3.82%   |
| 3840x2160 (4K)     | 72        | 3.32%   |
| 1600x900 (HD+)     | 47        | 2.17%   |
| 1440x900 (WXGA+)   | 46        | 2.12%   |
| 2560x1440 (QHD)    | 44        | 2.03%   |
| 1280x800 (WXGA)    | 39        | 1.8%    |
| 1360x768           | 26        | 1.2%    |
| 2880x1800          | 24        | 1.11%   |
| 2560x1600          | 19        | 0.88%   |
| 1280x1024 (SXGA)   | 14        | 0.65%   |
| 800x1280           | 10        | 0.46%   |
| 2560x1080          | 10        | 0.46%   |
| 3440x1440          | 8         | 0.37%   |
| 2160x1440          | 6         | 0.28%   |
| 1680x1050 (WSXGA+) | 5         | 0.23%   |
| 1024x600           | 5         | 0.23%   |
| Unknown            | 5         | 0.23%   |
| 2880x1920          | 4         | 0.18%   |
| 1024x768 (XGA)     | 4         | 0.18%   |
| 3000x2120          | 3         | 0.14%   |
| 1920x1280          | 3         | 0.14%   |
| 1280x960           | 3         | 0.14%   |
| 1280x720 (HD)      | 3         | 0.14%   |
| 3840x2400          | 2         | 0.09%   |
| 3840x1080          | 2         | 0.09%   |
| 3072x1920          | 2         | 0.09%   |
| 2288x1287          | 2         | 0.09%   |
| 1920x550           | 2         | 0.09%   |
| 640x480            | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 4093x4093          | 1         | 0.05%   |
| 3456x2160          | 1         | 0.05%   |
| 3200x1800 (QHD+)   | 1         | 0.05%   |
| 2966x900           | 1         | 0.05%   |
| 2736x1824          | 1         | 0.05%   |
| 2256x1504          | 1         | 0.05%   |
| 2240x1400          | 1         | 0.05%   |
| 1152x864           | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 521       | 23.24%  |
| 14      | 497       | 22.17%  |
| 15      | 360       | 16.06%  |
| 18      | 128       | 5.71%   |
| 23      | 104       | 4.64%   |
| 21      | 85        | 3.79%   |
| 12      | 80        | 3.57%   |
| 24      | 74        | 3.3%    |
| 11      | 59        | 2.63%   |
| 27      | 53        | 2.36%   |
| 19      | 51        | 2.27%   |
| 31      | 44        | 1.96%   |
| Unknown | 36        | 1.61%   |
| 17      | 22        | 0.98%   |
| 16      | 19        | 0.85%   |
| 40      | 14        | 0.62%   |
| 34      | 11        | 0.49%   |
| 7       | 10        | 0.45%   |
| 20      | 9         | 0.4%    |
| 63      | 7         | 0.31%   |
| 84      | 5         | 0.22%   |
| 22      | 5         | 0.22%   |
| 10      | 5         | 0.22%   |
| 48      | 4         | 0.18%   |
| 67      | 3         | 0.13%   |
| 52      | 3         | 0.13%   |
| 49      | 3         | 0.13%   |
| 42      | 3         | 0.13%   |
| 37      | 3         | 0.13%   |
| 32      | 3         | 0.13%   |
| 142     | 2         | 0.09%   |
| 72      | 2         | 0.09%   |
| 60      | 2         | 0.09%   |
| 54      | 2         | 0.09%   |
| 26      | 2         | 0.09%   |
| 65      | 1         | 0.04%   |
| 57      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 43      | 1         | 0.04%   |
| 39      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1248      | 56.24%  |
| 201-300        | 269       | 12.12%  |
| 401-500        | 265       | 11.94%  |
| 501-600        | 223       | 10.05%  |
| 601-700        | 53        | 2.39%   |
| 351-400        | 41        | 1.85%   |
| Unknown        | 36        | 1.62%   |
| 1001-1500      | 23        | 1.04%   |
| 801-900        | 19        | 0.86%   |
| 701-800        | 19        | 0.86%   |
| 1-100          | 9         | 0.41%   |
| 1501-2000      | 7         | 0.32%   |
| 901-1000       | 4         | 0.18%   |
| More than 2000 | 2         | 0.09%   |
| 101-200        | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1768      | 85.41%  |
| 16/10   | 195       | 9.42%   |
| Unknown | 30        | 1.45%   |
| 3/2     | 16        | 0.77%   |
| 5/4     | 14        | 0.68%   |
| 21/9    | 14        | 0.68%   |
| 4/3     | 12        | 0.58%   |
| 0.67    | 8         | 0.39%   |
| 32/9    | 5         | 0.24%   |
| 0.45    | 3         | 0.14%   |
| 1.00    | 2         | 0.1%    |
| 0.62    | 2         | 0.1%    |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 908       | 40.66%  |
| 101-110        | 354       | 15.85%  |
| 201-250        | 214       | 9.58%   |
| 141-150        | 133       | 5.96%   |
| 71-80          | 100       | 4.48%   |
| 151-200        | 89        | 3.99%   |
| 61-70          | 75        | 3.36%   |
| 51-60          | 59        | 2.64%   |
| 351-500        | 58        | 2.6%    |
| 301-350        | 55        | 2.46%   |
| Unknown        | 36        | 1.61%   |
| More than 1000 | 32        | 1.43%   |
| 501-1000       | 27        | 1.21%   |
| 251-300        | 26        | 1.16%   |
| 111-120        | 18        | 0.81%   |
| 91-100         | 15        | 0.67%   |
| 121-130        | 11        | 0.49%   |
| 1-40           | 10        | 0.45%   |
| 131-140        | 7         | 0.31%   |
| 41-50          | 6         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 795       | 35.97%  |
| 121-160       | 635       | 28.73%  |
| 51-100        | 508       | 22.99%  |
| 161-240       | 161       | 7.29%   |
| 1-50          | 38        | 1.72%   |
| More than 240 | 37        | 1.67%   |
| Unknown       | 36        | 1.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1911      | 85.85%  |
| 2     | 214       | 9.61%   |
| 0     | 94        | 4.22%   |
| 3     | 6         | 0.27%   |
| 4     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1324      | 38.8%   |
| Intel                             | 846       | 24.79%  |
| Qualcomm Atheros                  | 493       | 14.45%  |
| Broadcom                          | 180       | 5.28%   |
| MediaTek                          | 104       | 3.05%   |
| TP-Link                           | 71        | 2.08%   |
| Ralink Technology                 | 66        | 1.93%   |
| Xiaomi                            | 48        | 1.41%   |
| Samsung Electronics               | 33        | 0.97%   |
| Broadcom Limited                  | 24        | 0.7%    |
| Ralink                            | 21        | 0.62%   |
| Qualcomm Atheros Communications   | 21        | 0.62%   |
| OPPO Electronics                  | 19        | 0.56%   |
| Marvell Technology Group          | 16        | 0.47%   |
| Qualcomm                          | 14        | 0.41%   |
| ASIX Electronics                  | 12        | 0.35%   |
| JMicron Technology                | 9         | 0.26%   |
| Sierra Wireless                   | 8         | 0.23%   |
| Huawei Technologies               | 8         | 0.23%   |
| IBM                               | 7         | 0.21%   |
| D-Link                            | 7         | 0.21%   |
| vivo                              | 5         | 0.15%   |
| Shenzhen Goodix Technology        | 5         | 0.15%   |
| Nvidia                            | 5         | 0.15%   |
| ICS Advent                        | 5         | 0.15%   |
| D-Link System                     | 5         | 0.15%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.12%   |
| Ericsson Business Mobile Networks | 4         | 0.12%   |
| ZTopInc                           | 3         | 0.09%   |
| QinHeng Electronics               | 3         | 0.09%   |
| Attansic Technology               | 3         | 0.09%   |
| ASUSTek Computer                  | 3         | 0.09%   |
| AboCom Systems                    | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.06%   |
| Naxiang                           | 2         | 0.06%   |
| Mercucys                          | 2         | 0.06%   |
| Lenovo                            | 2         | 0.06%   |
| HMD Global                        | 2         | 0.06%   |
| Hewlett-Packard                   | 2         | 0.06%   |
| Foxconn / Hon Hai                 | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 849       | 21.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 223       | 5.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 122       | 3.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 98        | 2.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 82        | 2.06%   |
| Intel Wireless 8265 / 8275                                             | 78        | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 68        | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 61        | 1.53%   |
| Intel Wireless 7265                                                    | 58        | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 57        | 1.43%   |
| Intel Wi-Fi 6 AX201                                                    | 50        | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 48        | 1.2%    |
| Ralink MT7601U Wireless Adapter                                        | 47        | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 46        | 1.15%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 43        | 1.08%   |
| Intel Wi-Fi 6 AX200                                                    | 42        | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 41        | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 36        | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 36        | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 35        | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 35        | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 34        | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 33        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 33        | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                          | 33        | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 32        | 0.8%    |
| Intel Wireless 8260                                                    | 32        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 30        | 0.75%   |
| Intel Wireless 7260                                                    | 29        | 0.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 28        | 0.7%    |
| Realtek RTL8125 2.5GbE Controller                                      | 27        | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                                  | 26        | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 26        | 0.65%   |
| Intel Wireless 3165                                                    | 25        | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 24        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 23        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 23        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 23        | 0.58%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 23        | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                        | 21        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 692       | 34.74%  |
| Realtek Semiconductor           | 429       | 21.54%  |
| Qualcomm Atheros                | 426       | 21.39%  |
| Broadcom                        | 123       | 6.17%   |
| MediaTek                        | 89        | 4.47%   |
| Ralink Technology               | 66        | 3.31%   |
| TP-Link                         | 63        | 3.16%   |
| Ralink                          | 21        | 1.05%   |
| Qualcomm Atheros Communications | 21        | 1.05%   |
| Broadcom Limited                | 19        | 0.95%   |
| Sierra Wireless                 | 8         | 0.4%    |
| D-Link                          | 7         | 0.35%   |
| Qualcomm                        | 6         | 0.3%    |
| ZTopInc                         | 3         | 0.15%   |
| D-Link System                   | 3         | 0.15%   |
| AboCom Systems                  | 3         | 0.15%   |
| Mercucys                        | 2         | 0.1%    |
| Marvell Technology Group        | 2         | 0.1%    |
| Edimax Technology               | 2         | 0.1%    |
| ASUSTek Computer                | 2         | 0.1%    |
| Microsoft                       | 1         | 0.05%   |
| Linksys                         | 1         | 0.05%   |
| Fibocom                         | 1         | 0.05%   |
| Dell                            | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 122       | 6.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 98        | 4.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 82        | 4.08%   |
| Intel Wireless 8265 / 8275                                           | 78        | 3.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 61        | 3.04%   |
| Intel Wireless 7265                                                  | 58        | 2.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 57        | 2.84%   |
| Intel Wi-Fi 6 AX201                                                  | 50        | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 48        | 2.39%   |
| Ralink MT7601U Wireless Adapter                                      | 47        | 2.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 46        | 2.29%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 43        | 2.14%   |
| Intel Wi-Fi 6 AX200                                                  | 42        | 2.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 41        | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 36        | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 36        | 1.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 34        | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 33        | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 33        | 1.64%   |
| Broadcom BCM43142 802.11b/g/n                                        | 33        | 1.64%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 32        | 1.59%   |
| Intel Wireless 8260                                                  | 32        | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 30        | 1.49%   |
| Intel Wireless 7260                                                  | 29        | 1.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 27        | 1.34%   |
| Intel Wireless 3165                                                  | 25        | 1.25%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 24        | 1.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 24        | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 23        | 1.15%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 23        | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                      | 21        | 1.05%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 21        | 1.05%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310] | 20        | 1%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 19        | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 18        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 18        | 0.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 17        | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 17        | 0.85%   |
| Realtek 802.11ac NIC                                                 | 14        | 0.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 14        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1144      | 59.34%  |
| Intel                                  | 356       | 18.46%  |
| Qualcomm Atheros                       | 124       | 6.43%   |
| Broadcom                               | 72        | 3.73%   |
| Xiaomi                                 | 48        | 2.49%   |
| Samsung Electronics                    | 33        | 1.71%   |
| OPPO Electronics                       | 19        | 0.99%   |
| MediaTek                               | 16        | 0.83%   |
| Marvell Technology Group               | 14        | 0.73%   |
| ASIX Electronics                       | 12        | 0.62%   |
| JMicron Technology                     | 9         | 0.47%   |
| TP-Link                                | 8         | 0.41%   |
| Qualcomm                               | 8         | 0.41%   |
| IBM                                    | 7         | 0.36%   |
| Broadcom Limited                       | 7         | 0.36%   |
| vivo                                   | 5         | 0.26%   |
| Nvidia                                 | 5         | 0.26%   |
| ICS Advent                             | 5         | 0.26%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.21%   |
| Huawei Technologies                    | 3         | 0.16%   |
| Attansic Technology                    | 3         | 0.16%   |
| QinHeng Electronics                    | 2         | 0.1%    |
| Naxiang                                | 2         | 0.1%    |
| Lenovo                                 | 2         | 0.1%    |
| HMD Global                             | 2         | 0.1%    |
| Hewlett-Packard                        | 2         | 0.1%    |
| Foxconn / Hon Hai                      | 2         | 0.1%    |
| D-Link System                          | 2         | 0.1%    |
| 3Com                                   | 2         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 1         | 0.05%   |
| VIA Technologies                       | 1         | 0.05%   |
| T & A Mobile Phones                    | 1         | 0.05%   |
| Spreadtrum Communications              | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| skyGate Technology.                    | 1         | 0.05%   |
| Microchip Technology                   | 1         | 0.05%   |
| HTC (High Tech Computer)               | 1         | 0.05%   |
| DisplayLink                            | 1         | 0.05%   |
| ASUSTek Computer                       | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 849       | 43.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 223       | 11.39%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 68        | 3.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 35        | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                      | 27        | 1.38%   |
| Intel Ethernet Connection (4) I219-LM                                  | 26        | 1.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 26        | 1.33%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 23        | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 23        | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                                  | 20        | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 19        | 0.97%   |
| Intel Ethernet Connection I219-LM                                      | 19        | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 17        | 0.87%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 0.87%   |
| OPPO Ace 3V                                                            | 16        | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 14        | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 14        | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 11        | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 11        | 0.56%   |
| Intel Ethernet Connection I217-LM                                      | 11        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                                   | 11        | 0.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 11        | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 10        | 0.51%   |
| MediaTek Infinix HOT 50i                                               | 10        | 0.51%   |
| Intel I211 Gigabit Network Connection                                  | 10        | 0.51%   |
| Intel 82579V Gigabit Network Connection                                | 10        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                          | 10        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 9         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 9         | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                                  | 9         | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                                  | 9         | 0.46%   |
| Realtek Killer E2600 GbE Controller                                    | 8         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 8         | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 8         | 0.41%   |
| Intel 82577LM Gigabit Network Connection                               | 8         | 0.41%   |
| Intel 82574L Gigabit Network Connection                                | 8         | 0.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 8         | 0.41%   |
| Qualcomm Nokia X30 5G                                                  | 7         | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 7         | 0.36%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 7         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1887      | 51.46%  |
| Ethernet | 1761      | 48.02%  |
| Modem    | 17        | 0.46%   |
| Unknown  | 2         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1588      | 73.25%  |
| Ethernet | 579       | 26.71%  |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1243      | 56.68%  |
| 1     | 860       | 39.22%  |
| 0     | 42        | 1.92%   |
| 3     | 31        | 1.41%   |
| 4     | 12        | 0.55%   |
| 5     | 2         | 0.09%   |
| 27    | 1         | 0.05%   |
| 8     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1995      | 89.95%  |
| Yes  | 223       | 10.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 586       | 38.94%  |
| Realtek Semiconductor           | 237       | 15.75%  |
| IMC Networks                    | 168       | 11.16%  |
| Qualcomm Atheros Communications | 105       | 6.98%   |
| Lite-On Technology              | 93        | 6.18%   |
| Broadcom                        | 68        | 4.52%   |
| Cambridge Silicon Radio         | 66        | 4.39%   |
| Foxconn / Hon Hai               | 52        | 3.46%   |
| Apple                           | 27        | 1.79%   |
| Toshiba                         | 19        | 1.26%   |
| MediaTek                        | 14        | 0.93%   |
| Dell                            | 12        | 0.8%    |
| Ralink                          | 8         | 0.53%   |
| Hewlett-Packard                 | 8         | 0.53%   |
| Foxconn International           | 8         | 0.53%   |
| TP-Link                         | 5         | 0.33%   |
| Realtek                         | 5         | 0.33%   |
| Actions                         | 4         | 0.27%   |
| USI                             | 3         | 0.2%    |
| Marvell Semiconductor           | 3         | 0.2%    |
| ASUSTek Computer                | 3         | 0.2%    |
| Unknown                         | 3         | 0.2%    |
| Micro Star International        | 2         | 0.13%   |
| Alps Electric                   | 2         | 0.13%   |
| SINO WEALTH                     | 1         | 0.07%   |
| Integrated System Solution      | 1         | 0.07%   |
| Chicony Electronics             | 1         | 0.07%   |
| Askey Computer                  | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 214       | 14.21%  |
| Realtek Bluetooth Radio                             | 136       | 9.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 135       | 8.96%   |
| Intel AX201 Bluetooth                               | 105       | 6.97%   |
| IMC Networks Bluetooth Device                       | 80        | 5.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 66        | 4.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 51        | 3.39%   |
| Qualcomm Atheros  Bluetooth Device                  | 50        | 3.32%   |
| Intel AX200 Bluetooth                               | 42        | 2.79%   |
| IMC Networks Wireless_Device                        | 37        | 2.46%   |
| Lite-On Bluetooth Device                            | 32        | 2.12%   |
| IMC Networks Bluetooth Radio                        | 32        | 2.12%   |
| Intel Bluetooth Device                              | 29        | 1.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 22        | 1.46%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 22        | 1.46%   |
| Intel AX210 Bluetooth                               | 21        | 1.39%   |
| Lite-On Wireless_Device                             | 19        | 1.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 19        | 1.26%   |
| Realtek RTL8723B Bluetooth                          | 18        | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 1.13%   |
| Realtek RTL8821A Bluetooth                          | 16        | 1.06%   |
| MediaTek Wireless_Device                            | 14        | 0.93%   |
| Intel Wireless-AC 3168 Bluetooth                    | 14        | 0.93%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.86%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 11        | 0.73%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 11        | 0.73%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 10        | 0.66%   |
| Apple Bluetooth Host Controller                     | 10        | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.6%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 0.6%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 9         | 0.6%    |
| Ralink RT3290 Bluetooth                             | 8         | 0.53%   |
| Lite-On Atheros Bluetooth                           | 8         | 0.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 0.53%   |
| Foxconn International BCM43142A0 Bluetooth module   | 8         | 0.53%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 0.53%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 8         | 0.53%   |
| HP Broadcom 2070 Bluetooth Combo                    | 7         | 0.46%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 6         | 0.4%    |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1572      | 60.07%  |
| AMD                                  | 614       | 23.46%  |
| Nvidia                               | 298       | 11.39%  |
| C-Media Electronics                  | 20        | 0.76%   |
| Generalplus Technology               | 15        | 0.57%   |
| JMTek                                | 10        | 0.38%   |
| Texas Instruments                    | 7         | 0.27%   |
| Logitech                             | 7         | 0.27%   |
| Silicon Integrated Systems [SiS]     | 5         | 0.19%   |
| Comtrue                              | 5         | 0.19%   |
| Samson Technologies                  | 4         | 0.15%   |
| Jieli Technology                     | 4         | 0.15%   |
| Creative Labs                        | 4         | 0.15%   |
| Barco Display Systems                | 4         | 0.15%   |
| ASUSTek Computer                     | 4         | 0.15%   |
| Samsung Electronics                  | 3         | 0.11%   |
| Nordic Semiconductor ASA             | 3         | 0.11%   |
| KTMicro                              | 3         | 0.11%   |
| Yamaha                               | 2         | 0.08%   |
| Weltrend Semiconductor               | 2         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.08%   |
| STMicroelectronics                   | 2         | 0.08%   |
| SteelSeries ApS                      | 2         | 0.08%   |
| Soundprese                           | 2         | 0.08%   |
| Sony                                 | 2         | 0.08%   |
| Razer USA                            | 2         | 0.08%   |
| Kingston Technology                  | 2         | 0.08%   |
| Cooler Master                        | 2         | 0.08%   |
| Walmart                              | 1         | 0.04%   |
| TTGK Technology                      | 1         | 0.04%   |
| Solid State Logic                    | 1         | 0.04%   |
| SAVITECH                             | 1         | 0.04%   |
| Realtek Semiconductor                | 1         | 0.04%   |
| Micro Star International             | 1         | 0.04%   |
| JBL                                  | 1         | 0.04%   |
| Huawei Technologies                  | 1         | 0.04%   |
| Hewlett-Packard                      | 1         | 0.04%   |
| GYROCOM C&C                          | 1         | 0.04%   |
| Giga-Byte Technology                 | 1         | 0.04%   |
| FDUCE PRO AUDIO MADE                 | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 292       | 8.88%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 199       | 6.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 170       | 5.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 161       | 4.9%    |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 110       | 3.35%   |
| AMD FCH Azalia Controller                                                                         | 101       | 3.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 91        | 2.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 79        | 2.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 74        | 2.25%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 70        | 2.13%   |
| Intel 8 Series HD Audio Controller                                                                | 70        | 2.13%   |
| AMD Radeon High Definition Audio Controller                                                       | 70        | 2.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 69        | 2.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 65        | 1.98%   |
| AMD Kabini HDMI/DP Audio                                                                          | 65        | 1.98%   |
| Intel Broadwell-U Audio Controller                                                                | 63        | 1.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 63        | 1.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 62        | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 55        | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 54        | 1.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 51        | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 50        | 1.52%   |
| AMD High Definition Audio Controller                                                              | 50        | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 48        | 1.46%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 41        | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 40        | 1.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 37        | 1.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 36        | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 35        | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 31        | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 31        | 0.94%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 30        | 0.91%   |
| Nvidia High Definition Audio Controller                                                           | 27        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 25        | 0.76%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 24        | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 22        | 0.67%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 22        | 0.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 21        | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 21        | 0.64%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 21        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 441       | 26.91%  |
| SK hynix                                | 307       | 18.73%  |
| Micron Technology                       | 189       | 11.53%  |
| Kingston                                | 139       | 8.48%   |
| Unknown                                 | 136       | 8.3%    |
| Team                                    | 72        | 4.39%   |
| Corsair                                 | 60        | 3.66%   |
| V-GeN                                   | 51        | 3.11%   |
| Ramaxel Technology                      | 34        | 2.07%   |
| Unknown                                 | 29        | 1.77%   |
| Elpida                                  | 26        | 1.59%   |
| A-DATA Technology                       | 19        | 1.16%   |
| Unknown (ABCD)                          | 16        | 0.98%   |
| Nanya Technology                        | 15        | 0.92%   |
| Crucial                                 | 14        | 0.85%   |
| G.Skill                                 | 13        | 0.79%   |
| Transcend                               | 7         | 0.43%   |
| Hikvision                               | 6         | 0.37%   |
| Apacer                                  | 6         | 0.37%   |
| Visipro                                 | 5         | 0.31%   |
| Patriot                                 | 4         | 0.24%   |
| ASint Technology                        | 4         | 0.24%   |
| Unknown (0x0080)                        | 3         | 0.18%   |
| Shenzhen SCY                            | 3         | 0.18%   |
| SHARETRONIC                             | 3         | 0.18%   |
| PNY                                     | 3         | 0.18%   |
| Lexar                                   | 3         | 0.18%   |
| KLEVV                                   | 3         | 0.18%   |
| Unknown (0x0DD5)                        | 2         | 0.12%   |
| Kingmax                                 | 2         | 0.12%   |
| Hewlett-Packard                         | 2         | 0.12%   |
| A Force                                 | 2         | 0.12%   |
| Unknown (940A)                          | 1         | 0.06%   |
| Unknown (8AA1)                          | 1         | 0.06%   |
| Unknown (8A02)                          | 1         | 0.06%   |
| Toshiba                                 | 1         | 0.06%   |
| Teikon                                  | 1         | 0.06%   |
| Super Talent                            | 1         | 0.06%   |
| Strontium                               | 1         | 0.06%   |
| Silicon Power Computer & Communications | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 29        | 1.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 28        | 1.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 20        | 1.14%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 19        | 1.09%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 19        | 1.09%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 0.97%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 16        | 0.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.92%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 15        | 0.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.86%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 15        | 0.86%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 14        | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.8%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.69%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 12        | 0.69%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 11        | 0.63%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 10        | 0.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 0.57%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 10        | 0.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 10        | 0.57%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 9         | 0.51%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 9         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 9         | 0.51%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 3200MT/s            | 9         | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.46%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 8         | 0.46%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.46%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 8         | 0.46%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 8         | 0.46%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 8         | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 7         | 0.4%    |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 7         | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.4%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 7         | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.4%    |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s            | 7         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 605       | 45.94%  |
| DDR3    | 458       | 34.78%  |
| LPDDR4  | 59        | 4.48%   |
| LPDDR5  | 41        | 3.11%   |
| DDR2    | 39        | 2.96%   |
| SDRAM   | 36        | 2.73%   |
| DDR5    | 34        | 2.58%   |
| Unknown | 21        | 1.59%   |
| LPDDR3  | 20        | 1.52%   |
| DRAM    | 2         | 0.15%   |
| DDR     | 2         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 941       | 72%     |
| DIMM         | 254       | 19.43%  |
| Row Of Chips | 100       | 7.65%   |
| Chip         | 7         | 0.54%   |
| Unknown      | 5         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 540       | 36.1%   |
| 4096  | 498       | 33.29%  |
| 2048  | 199       | 13.3%   |
| 16384 | 154       | 10.29%  |
| 32768 | 74        | 4.95%   |
| 1024  | 24        | 1.6%    |
| 12288 | 3         | 0.2%    |
| 512   | 2         | 0.13%   |
| 65536 | 1         | 0.07%   |
| 6144  | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 313       | 21.03%  |
| 3200    | 260       | 17.47%  |
| 2667    | 205       | 13.78%  |
| 2400    | 125       | 8.4%    |
| 1333    | 98        | 6.59%   |
| 2133    | 63        | 4.23%   |
| 1334    | 33        | 2.22%   |
| 6400    | 31        | 2.08%   |
| 3266    | 28        | 1.88%   |
| 1067    | 26        | 1.75%   |
| 800     | 26        | 1.75%   |
| Unknown | 25        | 1.68%   |
| 8400    | 21        | 1.41%   |
| 3600    | 18        | 1.21%   |
| 667     | 18        | 1.21%   |
| 1867    | 17        | 1.14%   |
| 5600    | 15        | 1.01%   |
| 4800    | 15        | 1.01%   |
| 4266    | 15        | 1.01%   |
| 4267    | 14        | 0.94%   |
| 3800    | 11        | 0.74%   |
| 1800    | 10        | 0.67%   |
| 4199    | 9         | 0.6%    |
| 3733    | 9         | 0.6%    |
| 1866    | 9         | 0.6%    |
| 2666    | 7         | 0.47%   |
| 7500    | 5         | 0.34%   |
| 3000    | 5         | 0.34%   |
| 1066    | 5         | 0.34%   |
| 3400    | 4         | 0.27%   |
| 533     | 4         | 0.27%   |
| 5500    | 3         | 0.2%    |
| 4000    | 3         | 0.2%    |
| 3333    | 3         | 0.2%    |
| 2048    | 3         | 0.2%    |
| 333     | 3         | 0.2%    |
| 6000    | 2         | 0.13%   |
| 5400    | 2         | 0.13%   |
| 3866    | 2         | 0.13%   |
| 3151    | 2         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 26        | 59.09%  |
| Hewlett-Packard    | 8         | 18.18%  |
| Canon              | 4         | 9.09%   |
| Brother Industries | 3         | 6.82%   |
| STMicroelectronics | 2         | 4.55%   |
| Fuji Xerox         | 1         | 2.27%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seiko Epson L120 Series                 | 7         | 15.91%  |
| Seiko Epson EPSON L220 Series           | 6         | 13.64%  |
| Seiko Epson L312 Series                 | 3         | 6.82%   |
| Seiko Epson L3210 Series                | 2         | 4.55%   |
| Seiko Epson L3110 Series                | 2         | 4.55%   |
| Seiko Epson EPSON L300 Series           | 2         | 4.55%   |
| Canon iP2700 series                     | 2         | 4.55%   |
| Brother DCP-T300                        | 2         | 4.55%   |
| STMicroelectronics USB Printing Support | 1         | 2.27%   |
| STMicroelectronics ICOD_Thermal_Printer | 1         | 2.27%   |
| Seiko Epson L405 Series                 | 1         | 2.27%   |
| Seiko Epson L355 Series                 | 1         | 2.27%   |
| Seiko Epson L1300 Series                | 1         | 2.27%   |
| Seiko Epson L1110 Series                | 1         | 2.27%   |
| HP LaserJet P1102                       | 1         | 2.27%   |
| HP LaserJet P1006                       | 1         | 2.27%   |
| HP Ink Tank 310 series                  | 1         | 2.27%   |
| HP Ink Tank 110 series                  | 1         | 2.27%   |
| HP HP LaserJet M101-M106                | 1         | 2.27%   |
| HP DeskJet 5820 series                  | 1         | 2.27%   |
| HP Deskjet 4640 series                  | 1         | 2.27%   |
| HP DeskJet 2130 series                  | 1         | 2.27%   |
| Fuji Xerox DocuPrint M205 b             | 1         | 2.27%   |
| Canon PIXMA MP250                       | 1         | 2.27%   |
| Canon LiDE 300                          | 1         | 2.27%   |
| Brother DCP-T310                        | 1         | 2.27%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 4         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 25%     |
| Canon CanoScan LIDE 25             | 1         | 25%     |
| Canon CanoScan LiDE 110            | 1         | 25%     |
| Canon CanoScan 4400F               | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 400       | 25.82%  |
| IMC Networks                           | 220       | 14.2%   |
| Realtek Semiconductor                  | 126       | 8.13%   |
| Bison Electronics                      | 119       | 7.68%   |
| Sunplus Innovation Technology          | 84        | 5.42%   |
| Microdia                               | 72        | 4.65%   |
| Quanta                                 | 71        | 4.58%   |
| Syntek                                 | 63        | 4.07%   |
| Cheng Uei Precision Industry (Foxlink) | 53        | 3.42%   |
| Luxvisions Innotech Limited            | 35        | 2.26%   |
| Suyin                                  | 32        | 2.07%   |
| Sonix Technology                       | 30        | 1.94%   |
| Alcor Micro                            | 30        | 1.94%   |
| Lite-On Technology                     | 28        | 1.81%   |
| Apple                                  | 22        | 1.42%   |
| Logitech                               | 18        | 1.16%   |
| Acer                                   | 16        | 1.03%   |
| ShineTech                              | 11        | 0.71%   |
| Silicon Motion                         | 9         | 0.58%   |
| Ricoh                                  | 8         | 0.52%   |
| Lenovo                                 | 8         | 0.52%   |
| Jieli Technology                       | 8         | 0.52%   |
| Importek                               | 7         | 0.45%   |
| Primax Electronics                     | 5         | 0.32%   |
| ANYKA                                  | 5         | 0.32%   |
| Z-Star Microelectronics                | 4         | 0.26%   |
| SunplusIT                              | 4         | 0.26%   |
| Samsung Electronics                    | 4         | 0.26%   |
| Generalplus Technology                 | 4         | 0.26%   |
| Sunplus Technology                     | 3         | 0.19%   |
| SN0002                                 | 3         | 0.19%   |
| Shine-optics                           | 3         | 0.19%   |
| MacroSilicon                           | 3         | 0.19%   |
| GEMBIRD                                | 3         | 0.19%   |
| Unknown                                | 3         | 0.19%   |
| webcam                                 | 2         | 0.13%   |
| OPPO Electronics                       | 2         | 0.13%   |
| Microsoft                              | 2         | 0.13%   |
| Huawei Technologies                    | 2         | 0.13%   |
| Cubeternet                             | 2         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                      | 78        | 5%      |
| IMC Networks USB2.0 HD UVC WebCam                              | 63        | 4.04%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 50        | 3.21%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 48        | 3.08%   |
| Chicony HD WebCam                                              | 43        | 2.76%   |
| Syntek Integrated Camera                                       | 41        | 2.63%   |
| IMC Networks Integrated Camera                                 | 41        | 2.63%   |
| Bison Integrated Camera                                        | 39        | 2.5%    |
| Chicony HP TrueVision HD Camera                                | 26        | 1.67%   |
| Microdia Integrated_Webcam_HD                                  | 22        | 1.41%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 21        | 1.35%   |
| Realtek Integrated_Webcam_HD                                   | 21        | 1.35%   |
| Sonix USB2.0 HD UVC WebCam                                     | 20        | 1.28%   |
| Chicony USB2.0 HD UVC WebCam                                   | 19        | 1.22%   |
| IMC Networks Lenovo EasyCamera                                 | 16        | 1.03%   |
| Bison Lenovo EasyCamera                                        | 16        | 1.03%   |
| IMC Networks EasyCamera                                        | 15        | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 0.96%   |
| Chicony HD User Facing                                         | 14        | 0.9%    |
| Quanta HD User Facing                                          | 13        | 0.83%   |
| Chicony HP TrueVision HD                                       | 13        | 0.83%   |
| Realtek USB2.0 HD UVC WebCam                                   | 12        | 0.77%   |
| Realtek USB2.0 camera                                          | 12        | 0.77%   |
| Realtek USB Camera                                             | 12        | 0.77%   |
| Lite-On Integrated Camera                                      | 12        | 0.77%   |
| Sunplus Integrated_Webcam_HD                                   | 11        | 0.71%   |
| Sunplus Asus Webcam                                            | 11        | 0.71%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 11        | 0.71%   |
| Chicony TOSHIBA Web Camera - HD                                | 11        | 0.71%   |
| Chicony Lenovo EasyCamera                                      | 11        | 0.71%   |
| Chicony EasyCamera                                             | 11        | 0.71%   |
| Bison HD Webcam                                                | 11        | 0.71%   |
| Bison EasyCamera                                               | 11        | 0.71%   |
| Syntek Lenovo EasyCamera                                       | 10        | 0.64%   |
| Syntek EasyCamera                                              | 10        | 0.64%   |
| Microdia Webcam Vitade AF                                      | 10        | 0.64%   |
| Chicony Integrated Camera (1280x720@30)                        | 10        | 0.64%   |
| Quanta HD WebCam                                               | 9         | 0.58%   |
| Microdia Integrated Webcam                                     | 9         | 0.58%   |
| Suyin 1.3M HD WebCam                                           | 8         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 72        | 27.91%  |
| Synaptics                  | 69        | 26.74%  |
| Elan Microelectronics      | 37        | 14.34%  |
| Shenzhen Goodix Technology | 28        | 10.85%  |
| LighTuning Technology      | 17        | 6.59%   |
| AuthenTec                  | 13        | 5.04%   |
| Upek                       | 7         | 2.71%   |
| Focal-systems.Corp         | 7         | 2.71%   |
| STMicroelectronics         | 5         | 1.94%   |
| HOLTEK                     | 2         | 0.78%   |
| DigitalPersona             | 1         | 0.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 20        | 7.75%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 7.36%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 7.36%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 6.2%    |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 6.2%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 16        | 6.2%    |
| Elan ELAN:ARM-M4                                                           | 16        | 6.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 5.81%   |
| Shenzhen Goodix  FingerPrint Device                                        | 12        | 4.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 3.1%    |
| Synaptics WBDI                                                             | 8         | 3.1%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.71%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 2.71%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 7         | 2.71%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 2.33%   |
| AuthenTec AES1600                                                          | 6         | 2.33%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.94%   |
| Synaptics  WBDI                                                            | 5         | 1.94%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.55%   |
| Validity Sensors VFS491                                                    | 4         | 1.55%   |
| Synaptics UWP WBDI                                                         | 4         | 1.55%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.16%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.16%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.16%   |
| Synaptics Prometheus Fingerprint Reader                                    | 3         | 1.16%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.78%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.78%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 0.78%   |
| HOLTEK FocalTech Fingerprint Device                                        | 2         | 0.78%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.78%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.39%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.39%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.39%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.39%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.39%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.39%   |
| AuthenTec AES2810                                                          | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 28        | 47.46%  |
| Alcor Micro | 15        | 25.42%  |
| O2 Micro    | 9         | 15.25%  |
| Upek        | 5         | 8.47%   |
| Lenovo      | 2         | 3.39%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 25.42%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 25.42%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 13.56%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 10.17%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 8.47%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 3         | 5.08%   |
| Broadcom 5880                                                                | 3         | 5.08%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.39%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.69%   |
| Broadcom 58200                                                               | 1         | 1.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1593      | 71.5%   |
| 1     | 514       | 23.07%  |
| 2     | 100       | 4.49%   |
| 3     | 11        | 0.49%   |
| 4     | 7         | 0.31%   |
| 6     | 2         | 0.09%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 251       | 33.38%  |
| Graphics card            | 173       | 23.01%  |
| Net/wireless             | 102       | 13.56%  |
| Chipcard                 | 52        | 6.91%   |
| Multimedia controller    | 51        | 6.78%   |
| Communication controller | 29        | 3.86%   |
| Bluetooth                | 26        | 3.46%   |
| Net/ethernet             | 16        | 2.13%   |
| Camera                   | 16        | 2.13%   |
| Unassigned class         | 14        | 1.86%   |
| Storage                  | 5         | 0.66%   |
| Sound                    | 4         | 0.53%   |
| Flash memory             | 3         | 0.4%    |
| Card reader              | 3         | 0.4%    |
| Storage/ide              | 2         | 0.27%   |
| Wireless                 | 1         | 0.13%   |
| Video                    | 1         | 0.13%   |
| Network                  | 1         | 0.13%   |
| Modem                    | 1         | 0.13%   |
| Firewire controller      | 1         | 0.13%   |

