Linux in Thailand - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Thailand.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Thailand/Desktop/README.md) and [notebooks](/Location/Thailand/Notebook/README.md).

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

Total: 642

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | Notebook    | [628ee9ac88](https://linux-hardware.org/?probe=628ee9ac88) | Jun 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [19c6b51f80](https://linux-hardware.org/?probe=19c6b51f80) | Jun 08, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [483ac7223f](https://linux-hardware.org/?probe=483ac7223f) | Jun 08, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [1bdfa737bc](https://linux-hardware.org/?probe=1bdfa737bc) | Jun 08, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [cf560e91e7](https://linux-hardware.org/?probe=cf560e91e7) | Jun 07, 2023 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [d311022361](https://linux-hardware.org/?probe=d311022361) | Jun 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8fa7afa4a1](https://linux-hardware.org/?probe=8fa7afa4a1) | Jun 04, 2023 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [3e68e53c33](https://linux-hardware.org/?probe=3e68e53c33) | Jun 03, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [108cb2ce17](https://linux-hardware.org/?probe=108cb2ce17) | Jun 01, 2023 |
| Dell          | 07WP95 A01                  | Desktop     | [b9f3afed0c](https://linux-hardware.org/?probe=b9f3afed0c) | May 31, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [87c3dbc5df](https://linux-hardware.org/?probe=87c3dbc5df) | May 30, 2023 |
| Dell          | 07WP95 A01                  | Desktop     | [a58adc500e](https://linux-hardware.org/?probe=a58adc500e) | May 30, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [a199dc360d](https://linux-hardware.org/?probe=a199dc360d) | May 29, 2023 |
| Lenovo        | 313A NOK                    | Desktop     | [a1ffbc1e1e](https://linux-hardware.org/?probe=a1ffbc1e1e) | May 27, 2023 |
| Gigabyte      | P75-D3P                     | Desktop     | [c341cbff1b](https://linux-hardware.org/?probe=c341cbff1b) | May 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [01c17ab9dc](https://linux-hardware.org/?probe=01c17ab9dc) | May 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [93074475ac](https://linux-hardware.org/?probe=93074475ac) | May 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [08eb3979f4](https://linux-hardware.org/?probe=08eb3979f4) | May 19, 2023 |
| Acer          | Veriton M2610G              | Desktop     | [001e547ddf](https://linux-hardware.org/?probe=001e547ddf) | May 18, 2023 |
| ASUSTek       | ROG Strix G733CX_G743CX     | Notebook    | [744f091c75](https://linux-hardware.org/?probe=744f091c75) | May 18, 2023 |
| ASUSTek       | D320SF                      | Desktop     | [bbfd29fb88](https://linux-hardware.org/?probe=bbfd29fb88) | May 08, 2023 |
| ASUSTek       | D320SF                      | Desktop     | [fdb3953309](https://linux-hardware.org/?probe=fdb3953309) | May 08, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e35b234e43](https://linux-hardware.org/?probe=e35b234e43) | May 07, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [aaf53ecd65](https://linux-hardware.org/?probe=aaf53ecd65) | May 05, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [bbe145a1a2](https://linux-hardware.org/?probe=bbe145a1a2) | May 05, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2ebe14f5d0](https://linux-hardware.org/?probe=2ebe14f5d0) | May 04, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [71bf54960f](https://linux-hardware.org/?probe=71bf54960f) | May 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [206f95ee6f](https://linux-hardware.org/?probe=206f95ee6f) | May 02, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [a7cc631b80](https://linux-hardware.org/?probe=a7cc631b80) | Apr 27, 2023 |
| Lenovo        | ThinkPad T530 23594ZC       | Notebook    | [7aec73dfa1](https://linux-hardware.org/?probe=7aec73dfa1) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [52001c8ac6](https://linux-hardware.org/?probe=52001c8ac6) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [fc70e3e9e0](https://linux-hardware.org/?probe=fc70e3e9e0) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [bb212aa105](https://linux-hardware.org/?probe=bb212aa105) | Apr 19, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [2b839be032](https://linux-hardware.org/?probe=2b839be032) | Apr 19, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [6f8dbb2e8e](https://linux-hardware.org/?probe=6f8dbb2e8e) | Apr 14, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3166746b52](https://linux-hardware.org/?probe=3166746b52) | Apr 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [52e50e17de](https://linux-hardware.org/?probe=52e50e17de) | Apr 11, 2023 |
| Lenovo        | No DPK                      | Desktop     | [7028629b85](https://linux-hardware.org/?probe=7028629b85) | Apr 08, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [add0dfc4ca](https://linux-hardware.org/?probe=add0dfc4ca) | Apr 05, 2023 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [422a85d62b](https://linux-hardware.org/?probe=422a85d62b) | Apr 03, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1a3e968dff](https://linux-hardware.org/?probe=1a3e968dff) | Apr 03, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [2c68190118](https://linux-hardware.org/?probe=2c68190118) | Apr 03, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [fab3140b7b](https://linux-hardware.org/?probe=fab3140b7b) | Mar 29, 2023 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [8d94a6c8e7](https://linux-hardware.org/?probe=8d94a6c8e7) | Mar 28, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [81dc7d8f53](https://linux-hardware.org/?probe=81dc7d8f53) | Mar 27, 2023 |
| HP            | 802F                        | Desktop     | [89dadeeea6](https://linux-hardware.org/?probe=89dadeeea6) | Mar 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fda0ab85e6](https://linux-hardware.org/?probe=fda0ab85e6) | Mar 18, 2023 |
| ASUSTek       | Z97-K R2.0                  | Desktop     | [8c266d3142](https://linux-hardware.org/?probe=8c266d3142) | Mar 16, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [9f33a01f8d](https://linux-hardware.org/?probe=9f33a01f8d) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [061b0673b4](https://linux-hardware.org/?probe=061b0673b4) | Mar 12, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1875fd875d](https://linux-hardware.org/?probe=1875fd875d) | Mar 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2a40386fb8](https://linux-hardware.org/?probe=2a40386fb8) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [89194cffbe](https://linux-hardware.org/?probe=89194cffbe) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [d674283cb0](https://linux-hardware.org/?probe=d674283cb0) | Mar 11, 2023 |
| Acer          | Veriton X4620G v1.0         | Desktop     | [fc27bc474e](https://linux-hardware.org/?probe=fc27bc474e) | Mar 11, 2023 |
| Acer          | Aspire TC-390               | Desktop     | [2d092d008e](https://linux-hardware.org/?probe=2d092d008e) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [388f28c258](https://linux-hardware.org/?probe=388f28c258) | Mar 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [91fab60d63](https://linux-hardware.org/?probe=91fab60d63) | Mar 04, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [bd1f7da7bc](https://linux-hardware.org/?probe=bd1f7da7bc) | Mar 03, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [8ef1c9b71d](https://linux-hardware.org/?probe=8ef1c9b71d) | Mar 02, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [053c6d5368](https://linux-hardware.org/?probe=053c6d5368) | Mar 02, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [588ac214ef](https://linux-hardware.org/?probe=588ac214ef) | Mar 01, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [715d043ec7](https://linux-hardware.org/?probe=715d043ec7) | Mar 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [d475dd1788](https://linux-hardware.org/?probe=d475dd1788) | Feb 25, 2023 |
| HP            | 1998                        | Desktop     | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| ASUSTek       | A4110                       | All in one  | [69f378f0b5](https://linux-hardware.org/?probe=69f378f0b5) | Feb 24, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [990ffa68f4](https://linux-hardware.org/?probe=990ffa68f4) | Feb 23, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [73dde5b3db](https://linux-hardware.org/?probe=73dde5b3db) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [daf7b5a6cc](https://linux-hardware.org/?probe=daf7b5a6cc) | Feb 21, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [a813f73ea2](https://linux-hardware.org/?probe=a813f73ea2) | Feb 20, 2023 |
| MSI           | Bravo 15 B5ED               | Notebook    | [a0b7f1b5f8](https://linux-hardware.org/?probe=a0b7f1b5f8) | Feb 20, 2023 |
| Supermicro    | X10DRiB                     | Desktop     | [8e6438214d](https://linux-hardware.org/?probe=8e6438214d) | Feb 20, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [06c1b9f781](https://linux-hardware.org/?probe=06c1b9f781) | Feb 20, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | Notebook    | [abd464b0d3](https://linux-hardware.org/?probe=abd464b0d3) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | Notebook    | [d77cac7fb6](https://linux-hardware.org/?probe=d77cac7fb6) | Feb 10, 2023 |
| HP            | 83E4                        | All in one  | [cdefba9e55](https://linux-hardware.org/?probe=cdefba9e55) | Feb 09, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [647f120e0b](https://linux-hardware.org/?probe=647f120e0b) | Feb 08, 2023 |
| Lenovo        | ThinkPad P50 20EN0017US     | Notebook    | [43c5ab14ec](https://linux-hardware.org/?probe=43c5ab14ec) | Feb 03, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [8944f22b68](https://linux-hardware.org/?probe=8944f22b68) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [6094b799d7](https://linux-hardware.org/?probe=6094b799d7) | Jan 31, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [15cda8e776](https://linux-hardware.org/?probe=15cda8e776) | Jan 30, 2023 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [064806786c](https://linux-hardware.org/?probe=064806786c) | Jan 23, 2023 |
| Acer          | Aspire A515-55G             | Notebook    | [7a4e781669](https://linux-hardware.org/?probe=7a4e781669) | Jan 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [40560e6bcd](https://linux-hardware.org/?probe=40560e6bcd) | Jan 21, 2023 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [0fc911e254](https://linux-hardware.org/?probe=0fc911e254) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [84d86434e8](https://linux-hardware.org/?probe=84d86434e8) | Jan 16, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [22b5c66553](https://linux-hardware.org/?probe=22b5c66553) | Jan 12, 2023 |
| Dell          | 054KM3 A00                  | Desktop     | [4ea59c00f3](https://linux-hardware.org/?probe=4ea59c00f3) | Jan 11, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [e6ecb9037e](https://linux-hardware.org/?probe=e6ecb9037e) | Jan 10, 2023 |
| AZW           | GTR V01                     | Mini pc     | [4ab41ad921](https://linux-hardware.org/?probe=4ab41ad921) | Jan 08, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [a6d6bf8d28](https://linux-hardware.org/?probe=a6d6bf8d28) | Jan 08, 2023 |
| Lenovo        | IdeaPad 300S-11IBR 80KU     | Notebook    | [6335e974a1](https://linux-hardware.org/?probe=6335e974a1) | Jan 08, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [9c9e1b06f9](https://linux-hardware.org/?probe=9c9e1b06f9) | Jan 07, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [67103caf92](https://linux-hardware.org/?probe=67103caf92) | Jan 07, 2023 |
| ALLDOCUBE     | i1025P                      | Tablet      | [631c1eea14](https://linux-hardware.org/?probe=631c1eea14) | Jan 06, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [7acb37a2f5](https://linux-hardware.org/?probe=7acb37a2f5) | Jan 05, 2023 |
| Dell          | G3 3579                     | Notebook    | [becea24616](https://linux-hardware.org/?probe=becea24616) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| HP            | 802F                        | Desktop     | [22444b4b2c](https://linux-hardware.org/?probe=22444b4b2c) | Dec 31, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [2e23d15c25](https://linux-hardware.org/?probe=2e23d15c25) | Dec 24, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| AMI           | Cherry Trail CR             | Mini pc     | [26ed239f3c](https://linux-hardware.org/?probe=26ed239f3c) | Dec 23, 2022 |
| Gigabyte      | P75-D3P                     | Desktop     | [ff2420e759](https://linux-hardware.org/?probe=ff2420e759) | Dec 19, 2022 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [e46710b0cf](https://linux-hardware.org/?probe=e46710b0cf) | Dec 19, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [016e7d7ef2](https://linux-hardware.org/?probe=016e7d7ef2) | Dec 16, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [b0a81337c4](https://linux-hardware.org/?probe=b0a81337c4) | Dec 13, 2022 |
| Supermicro    | X9DRW                       | Server      | [ead67ca4f7](https://linux-hardware.org/?probe=ead67ca4f7) | Dec 13, 2022 |
| Acer          | TravelMate P214-41-G2       | Notebook    | [cb52e49fa2](https://linux-hardware.org/?probe=cb52e49fa2) | Dec 08, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [2ac449d25f](https://linux-hardware.org/?probe=2ac449d25f) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3807efd1f4](https://linux-hardware.org/?probe=3807efd1f4) | Dec 03, 2022 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [af31550cae](https://linux-hardware.org/?probe=af31550cae) | Nov 27, 2022 |
| MSI           | GP63 Leopard 8RE            | Notebook    | [f8bb75758e](https://linux-hardware.org/?probe=f8bb75758e) | Nov 24, 2022 |
| Gigabyte      | 970A-D3                     | Desktop     | [89287418e8](https://linux-hardware.org/?probe=89287418e8) | Nov 23, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [8b44a7deaa](https://linux-hardware.org/?probe=8b44a7deaa) | Nov 21, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [e60a1f8fc4](https://linux-hardware.org/?probe=e60a1f8fc4) | Nov 20, 2022 |
| HP            | 82F2 A01                    | Desktop     | [b6cb9447df](https://linux-hardware.org/?probe=b6cb9447df) | Nov 19, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [32e8c529f0](https://linux-hardware.org/?probe=32e8c529f0) | Nov 14, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [16b7880c43](https://linux-hardware.org/?probe=16b7880c43) | Nov 07, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [f4c2d5224b](https://linux-hardware.org/?probe=f4c2d5224b) | Oct 30, 2022 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| Dell          | Precision 5530              | Notebook    | [bb4d35f452](https://linux-hardware.org/?probe=bb4d35f452) | Oct 28, 2022 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [7977a48aca](https://linux-hardware.org/?probe=7977a48aca) | Oct 26, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [13873c81b2](https://linux-hardware.org/?probe=13873c81b2) | Oct 24, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [4a6e283158](https://linux-hardware.org/?probe=4a6e283158) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [7c284b1dfd](https://linux-hardware.org/?probe=7c284b1dfd) | Oct 20, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [7c689396eb](https://linux-hardware.org/?probe=7c689396eb) | Oct 19, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [357ad9257d](https://linux-hardware.org/?probe=357ad9257d) | Oct 19, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [478b58f9b6](https://linux-hardware.org/?probe=478b58f9b6) | Oct 15, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [64cbdc6e2a](https://linux-hardware.org/?probe=64cbdc6e2a) | Oct 13, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [ed74f1da66](https://linux-hardware.org/?probe=ed74f1da66) | Oct 10, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [29f63f8a32](https://linux-hardware.org/?probe=29f63f8a32) | Oct 10, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3665682cc6](https://linux-hardware.org/?probe=3665682cc6) | Oct 08, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [7d71e688f4](https://linux-hardware.org/?probe=7d71e688f4) | Oct 08, 2022 |
| HP            | Laptop                      | Notebook    | [3a26ec874f](https://linux-hardware.org/?probe=3a26ec874f) | Oct 04, 2022 |
| Timi          | TM1701                      | Notebook    | [59153cc5fe](https://linux-hardware.org/?probe=59153cc5fe) | Sep 27, 2022 |
| HP            | Laptop                      | Notebook    | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Laptop                      | Notebook    | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| Acer          | TravelMate P653-M           | Notebook    | [c0fcc47188](https://linux-hardware.org/?probe=c0fcc47188) | Sep 03, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [685e484cbd](https://linux-hardware.org/?probe=685e484cbd) | Aug 31, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [576dfabbf6](https://linux-hardware.org/?probe=576dfabbf6) | Aug 29, 2022 |
| OEM           | Intel H81                   | Desktop     | [8732ebea02](https://linux-hardware.org/?probe=8732ebea02) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [65f638768e](https://linux-hardware.org/?probe=65f638768e) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [1746f3874c](https://linux-hardware.org/?probe=1746f3874c) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [0008869bb6](https://linux-hardware.org/?probe=0008869bb6) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [c0e9a2e062](https://linux-hardware.org/?probe=c0e9a2e062) | Aug 27, 2022 |
| OEM           | Intel H81                   | Desktop     | [cbedace60c](https://linux-hardware.org/?probe=cbedace60c) | Aug 25, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [51a98d93a6](https://linux-hardware.org/?probe=51a98d93a6) | Aug 20, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [dc65bd0f38](https://linux-hardware.org/?probe=dc65bd0f38) | Aug 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [93b2d066d6](https://linux-hardware.org/?probe=93b2d066d6) | Aug 17, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [5cdd2332d5](https://linux-hardware.org/?probe=5cdd2332d5) | Aug 14, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
| HP            | 8062                        | Desktop     | [0f24b44d56](https://linux-hardware.org/?probe=0f24b44d56) | Aug 14, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [1b9f19b21e](https://linux-hardware.org/?probe=1b9f19b21e) | Aug 13, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5ebbabea13](https://linux-hardware.org/?probe=5ebbabea13) | Aug 10, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [eab28163ce](https://linux-hardware.org/?probe=eab28163ce) | Aug 09, 2022 |
| SHARKBAY      | Unknown                     | Desktop     | [a35fff735f](https://linux-hardware.org/?probe=a35fff735f) | Aug 09, 2022 |
| Acer          | TravelMate P643-M           | Notebook    | [33254cfb1e](https://linux-hardware.org/?probe=33254cfb1e) | Aug 03, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [d736692861](https://linux-hardware.org/?probe=d736692861) | Jul 31, 2022 |
| Dell          | Latitude 3320               | Notebook    | [183ae38016](https://linux-hardware.org/?probe=183ae38016) | Jul 31, 2022 |
| Dell          | Latitude 3320               | Notebook    | [a849c0d90a](https://linux-hardware.org/?probe=a849c0d90a) | Jul 30, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [f8808faaf0](https://linux-hardware.org/?probe=f8808faaf0) | Jul 24, 2022 |
| Acer          | TravelMate P643-M           | Notebook    | [0357bf32d7](https://linux-hardware.org/?probe=0357bf32d7) | Jul 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [eac5600627](https://linux-hardware.org/?probe=eac5600627) | Jul 12, 2022 |
| Lenovo        | SHARKBAY 31900059 WIN       | All in one  | [f27df86fda](https://linux-hardware.org/?probe=f27df86fda) | Jul 11, 2022 |
| ASUSTek       | ROG Maximus X APEX          | Desktop     | [e1fa4e4923](https://linux-hardware.org/?probe=e1fa4e4923) | Jul 06, 2022 |
| MSI           | Z97 XPOWER AC               | Desktop     | [b7324cb6ab](https://linux-hardware.org/?probe=b7324cb6ab) | Jul 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [4829f98af6](https://linux-hardware.org/?probe=4829f98af6) | Jul 04, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [cfa0dde1d0](https://linux-hardware.org/?probe=cfa0dde1d0) | Jul 02, 2022 |
| Infinix       | INBOOK X2                   | Notebook    | [eedac976d8](https://linux-hardware.org/?probe=eedac976d8) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [334719e6a2](https://linux-hardware.org/?probe=334719e6a2) | Jun 30, 2022 |
| Infinix       | INBOOK X2                   | Notebook    | [1c87102f96](https://linux-hardware.org/?probe=1c87102f96) | Jun 29, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| Lenovo        | ThinkPad X230 23331R5       | Notebook    | [c6589e02c4](https://linux-hardware.org/?probe=c6589e02c4) | Jun 25, 2022 |
| AFOX          | AF IH81-MA3 V1.0            | Desktop     | [4ce7ccc125](https://linux-hardware.org/?probe=4ce7ccc125) | Jun 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a1a0b3b43b](https://linux-hardware.org/?probe=a1a0b3b43b) | Jun 23, 2022 |
| MSI           | GE76 Raider 10UH            | Notebook    | [77ef5acb4c](https://linux-hardware.org/?probe=77ef5acb4c) | Jun 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [51ec938467](https://linux-hardware.org/?probe=51ec938467) | Jun 22, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [11151bb62c](https://linux-hardware.org/?probe=11151bb62c) | Jun 22, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [1cc4490d99](https://linux-hardware.org/?probe=1cc4490d99) | Jun 17, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [e3bb4dee4b](https://linux-hardware.org/?probe=e3bb4dee4b) | Jun 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [00090936e8](https://linux-hardware.org/?probe=00090936e8) | Jun 15, 2022 |
| Dell          | Latitude 3120               | Notebook    | [c5c6eed0d9](https://linux-hardware.org/?probe=c5c6eed0d9) | Jun 14, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [fd7d146eb1](https://linux-hardware.org/?probe=fd7d146eb1) | Jun 08, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [b12802bc7a](https://linux-hardware.org/?probe=b12802bc7a) | Jun 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [799a25df83](https://linux-hardware.org/?probe=799a25df83) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| Acer          | One Z1402                   | Notebook    | [4278b806cf](https://linux-hardware.org/?probe=4278b806cf) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| ASUSTek       | S400CA                      | Notebook    | [dadda333d2](https://linux-hardware.org/?probe=dadda333d2) | May 28, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [3dbf1858d0](https://linux-hardware.org/?probe=3dbf1858d0) | May 27, 2022 |
| Dell          | Latitude 3120               | Notebook    | [e97cf58459](https://linux-hardware.org/?probe=e97cf58459) | May 23, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [8949bc2cf8](https://linux-hardware.org/?probe=8949bc2cf8) | May 22, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| Acer          | One Z1402                   | Notebook    | [ae69c0fdbd](https://linux-hardware.org/?probe=ae69c0fdbd) | May 21, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [90bfbc9f6b](https://linux-hardware.org/?probe=90bfbc9f6b) | May 16, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [ec0ec5ea27](https://linux-hardware.org/?probe=ec0ec5ea27) | May 15, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [07e54c3c41](https://linux-hardware.org/?probe=07e54c3c41) | May 12, 2022 |
| Intel         | D54250WYK H13922-305        | Desktop     | [6d1745c79b](https://linux-hardware.org/?probe=6d1745c79b) | May 11, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [e765b34181](https://linux-hardware.org/?probe=e765b34181) | May 11, 2022 |
| Lenovo        | ThinkPad X230 23257Y1       | Notebook    | [0c4e13a23d](https://linux-hardware.org/?probe=0c4e13a23d) | May 11, 2022 |
| HP            | 18E7                        | Desktop     | [52a59840d8](https://linux-hardware.org/?probe=52a59840d8) | May 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YJS... | Notebook    | [fb11780c46](https://linux-hardware.org/?probe=fb11780c46) | May 07, 2022 |
| ASRock        | H370 Pro4                   | Desktop     | [ccf085e9dc](https://linux-hardware.org/?probe=ccf085e9dc) | May 02, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fec983464c](https://linux-hardware.org/?probe=fec983464c) | Apr 29, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [b485d8f932](https://linux-hardware.org/?probe=b485d8f932) | Apr 28, 2022 |
| ASUSTek       | K40IN                       | Notebook    | [ab6a95da52](https://linux-hardware.org/?probe=ab6a95da52) | Apr 28, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| HP            | Pro Tablet 608 G1           | Notebook    | [a8b97ee7cf](https://linux-hardware.org/?probe=a8b97ee7cf) | Apr 25, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [377315649e](https://linux-hardware.org/?probe=377315649e) | Apr 22, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [6d291b9c9c](https://linux-hardware.org/?probe=6d291b9c9c) | Apr 21, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [218e8b7d2a](https://linux-hardware.org/?probe=218e8b7d2a) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4286A78       | Notebook    | [d5c9254caa](https://linux-hardware.org/?probe=d5c9254caa) | Apr 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [95744e46d1](https://linux-hardware.org/?probe=95744e46d1) | Apr 18, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [be1e468728](https://linux-hardware.org/?probe=be1e468728) | Apr 17, 2022 |
| Acer          | Aspire E5-471G              | Notebook    | [a7179e1ba3](https://linux-hardware.org/?probe=a7179e1ba3) | Apr 16, 2022 |
| ASRock        | B460M-ITX/ac                | Desktop     | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| Framework     | Laptop                      | Notebook    | [bd5ea938e7](https://linux-hardware.org/?probe=bd5ea938e7) | Apr 07, 2022 |
| Dell          | Latitude 3120               | Notebook    | [c0df9a1ac0](https://linux-hardware.org/?probe=c0df9a1ac0) | Apr 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [30c09eec3b](https://linux-hardware.org/?probe=30c09eec3b) | Mar 28, 2022 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [a9a4291601](https://linux-hardware.org/?probe=a9a4291601) | Mar 26, 2022 |
| Dell          | Latitude 3120               | Notebook    | [69b7d6b1a3](https://linux-hardware.org/?probe=69b7d6b1a3) | Mar 26, 2022 |
| Dell          | Latitude 3120               | Notebook    | [78ae48c482](https://linux-hardware.org/?probe=78ae48c482) | Mar 26, 2022 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [db31622d02](https://linux-hardware.org/?probe=db31622d02) | Mar 21, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1602a60580](https://linux-hardware.org/?probe=1602a60580) | Mar 18, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [db613d4f60](https://linux-hardware.org/?probe=db613d4f60) | Mar 16, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [d534c1e639](https://linux-hardware.org/?probe=d534c1e639) | Mar 16, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [7a484a0d61](https://linux-hardware.org/?probe=7a484a0d61) | Mar 11, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [c2f6faf193](https://linux-hardware.org/?probe=c2f6faf193) | Mar 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [afa2ad19c8](https://linux-hardware.org/?probe=afa2ad19c8) | Mar 04, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| ASRock        | H410M-HDV R2.0              | Desktop     | [0c91f1563f](https://linux-hardware.org/?probe=0c91f1563f) | Feb 14, 2022 |
| Acer          | AOA150                      | Notebook    | [aeb35f9f12](https://linux-hardware.org/?probe=aeb35f9f12) | Feb 13, 2022 |
| Acer          | AOA150                      | Notebook    | [7d493dd5d5](https://linux-hardware.org/?probe=7d493dd5d5) | Feb 13, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [5d3d7c5340](https://linux-hardware.org/?probe=5d3d7c5340) | Feb 12, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9544722d31](https://linux-hardware.org/?probe=9544722d31) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1488d5e773](https://linux-hardware.org/?probe=1488d5e773) | Feb 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [dfc4821588](https://linux-hardware.org/?probe=dfc4821588) | Feb 08, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [ad24d41607](https://linux-hardware.org/?probe=ad24d41607) | Feb 08, 2022 |
| Unknown       | Intel X79                   | Desktop     | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| HP            | 1998                        | Desktop     | [263c4b1a93](https://linux-hardware.org/?probe=263c4b1a93) | Feb 03, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [5e8f4aba70](https://linux-hardware.org/?probe=5e8f4aba70) | Feb 03, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [c90234250e](https://linux-hardware.org/?probe=c90234250e) | Jan 31, 2022 |
| Lenovo        | ThinkPad P50 20EQS2AB00     | Notebook    | [bdc680b5f1](https://linux-hardware.org/?probe=bdc680b5f1) | Jan 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [31f48cd25e](https://linux-hardware.org/?probe=31f48cd25e) | Jan 19, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [2c877954ab](https://linux-hardware.org/?probe=2c877954ab) | Jan 15, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [4151d78b0a](https://linux-hardware.org/?probe=4151d78b0a) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [322291a7b1](https://linux-hardware.org/?probe=322291a7b1) | Jan 14, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [dfe91144b0](https://linux-hardware.org/?probe=dfe91144b0) | Jan 13, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [247f2934b0](https://linux-hardware.org/?probe=247f2934b0) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [608af1b572](https://linux-hardware.org/?probe=608af1b572) | Jan 04, 2022 |
| HP            | 82B4                        | Desktop     | [363fec4fa2](https://linux-hardware.org/?probe=363fec4fa2) | Jan 03, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [b26b378274](https://linux-hardware.org/?probe=b26b378274) | Jan 01, 2022 |
| ASRock        | M3A770DE                    | Desktop     | [92b50bf0b6](https://linux-hardware.org/?probe=92b50bf0b6) | Dec 27, 2021 |
| Lenovo        | ThinkPad X131e 33722VU      | Notebook    | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [47fa1e385d](https://linux-hardware.org/?probe=47fa1e385d) | Dec 26, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [2e71480673](https://linux-hardware.org/?probe=2e71480673) | Dec 24, 2021 |
| HP            | 82B4                        | Desktop     | [02f9952fa5](https://linux-hardware.org/?probe=02f9952fa5) | Dec 24, 2021 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [99e3241324](https://linux-hardware.org/?probe=99e3241324) | Dec 18, 2021 |
| MiTAC         | PD14RI                      | Desktop     | [e4dc1c326a](https://linux-hardware.org/?probe=e4dc1c326a) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| MSI           | Boston                      | Desktop     | [760fa25b63](https://linux-hardware.org/?probe=760fa25b63) | Dec 15, 2021 |
| MSI           | Boston                      | Desktop     | [bc4405aa85](https://linux-hardware.org/?probe=bc4405aa85) | Dec 15, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [15671c0dbe](https://linux-hardware.org/?probe=15671c0dbe) | Dec 14, 2021 |
| MiTAC         | PD14RI                      | Desktop     | [acf3343fe7](https://linux-hardware.org/?probe=acf3343fe7) | Dec 13, 2021 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [e22dd08488](https://linux-hardware.org/?probe=e22dd08488) | Dec 02, 2021 |
| Gigabyte      | M52L-S3                     | Desktop     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Lenovo        | ThinkPad L530 24792T1       | Notebook    | [3e12618615](https://linux-hardware.org/?probe=3e12618615) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | Desktop     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| Toshiba       | Satellite L840              | Notebook    | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0d0596e9ea](https://linux-hardware.org/?probe=0d0596e9ea) | Nov 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [6043e86d2a](https://linux-hardware.org/?probe=6043e86d2a) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | Desktop     | [63edfe6809](https://linux-hardware.org/?probe=63edfe6809) | Nov 24, 2021 |
| Gigabyte      | H110M-DS2V-CF               | Desktop     | [a4986016ca](https://linux-hardware.org/?probe=a4986016ca) | Nov 23, 2021 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [edaff183a5](https://linux-hardware.org/?probe=edaff183a5) | Nov 21, 2021 |
| MSI           | 3666h                       | Desktop     | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| MSI           | 3666h                       | Desktop     | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [4083699145](https://linux-hardware.org/?probe=4083699145) | Nov 14, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [e3825be547](https://linux-hardware.org/?probe=e3825be547) | Nov 14, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [b362dd3f20](https://linux-hardware.org/?probe=b362dd3f20) | Nov 13, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [d1b6520785](https://linux-hardware.org/?probe=d1b6520785) | Nov 13, 2021 |
| HP            | EliteBook 6930p (FL488AW... | Notebook    | [af8e63842a](https://linux-hardware.org/?probe=af8e63842a) | Oct 28, 2021 |
| Acer          | Aspire ES1-131              | Notebook    | [de7bee5c36](https://linux-hardware.org/?probe=de7bee5c36) | Oct 20, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [ff477e5a71](https://linux-hardware.org/?probe=ff477e5a71) | Oct 10, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [f467bc83ef](https://linux-hardware.org/?probe=f467bc83ef) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [3bf6f778dc](https://linux-hardware.org/?probe=3bf6f778dc) | Oct 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1193264475](https://linux-hardware.org/?probe=1193264475) | Oct 10, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [f873a240d5](https://linux-hardware.org/?probe=f873a240d5) | Oct 10, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [26e5760e58](https://linux-hardware.org/?probe=26e5760e58) | Oct 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [514642d183](https://linux-hardware.org/?probe=514642d183) | Sep 30, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [e4fb99f5b8](https://linux-hardware.org/?probe=e4fb99f5b8) | Sep 30, 2021 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [26b0b41886](https://linux-hardware.org/?probe=26b0b41886) | Sep 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [8141d6fa89](https://linux-hardware.org/?probe=8141d6fa89) | Sep 22, 2021 |
| Cube          | SurfTab twin 11.6           | Convertible | [74fe90715f](https://linux-hardware.org/?probe=74fe90715f) | Sep 22, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [71820e1f85](https://linux-hardware.org/?probe=71820e1f85) | Sep 18, 2021 |
| Dell          | 02P9X9 A03                  | Server      | [56b5e62268](https://linux-hardware.org/?probe=56b5e62268) | Sep 17, 2021 |
| Dell          | 02P9X9 A03                  | Server      | [cb07eeaf33](https://linux-hardware.org/?probe=cb07eeaf33) | Sep 17, 2021 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [8ab840927b](https://linux-hardware.org/?probe=8ab840927b) | Sep 17, 2021 |
| HP            | 1497                        | Desktop     | [311efc294a](https://linux-hardware.org/?probe=311efc294a) | Sep 16, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| ASRock        | 880GM-LE FX                 | Desktop     | [022e5df6bd](https://linux-hardware.org/?probe=022e5df6bd) | Sep 12, 2021 |
| ASRock        | 880GM-LE FX                 | Desktop     | [f7706441f2](https://linux-hardware.org/?probe=f7706441f2) | Sep 12, 2021 |
| Dell          | Latitude D630               | Notebook    | [3af0cdbc54](https://linux-hardware.org/?probe=3af0cdbc54) | Sep 09, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [04e6db02f9](https://linux-hardware.org/?probe=04e6db02f9) | Sep 02, 2021 |
| Acer          | Aspire V3-575G              | Notebook    | [28e06e0c2b](https://linux-hardware.org/?probe=28e06e0c2b) | Aug 28, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [8e060f6c6c](https://linux-hardware.org/?probe=8e060f6c6c) | Aug 23, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [57b648bd45](https://linux-hardware.org/?probe=57b648bd45) | Aug 23, 2021 |
| VIA Techno... | EITX-3002                   | Desktop     | [db8b46aea5](https://linux-hardware.org/?probe=db8b46aea5) | Aug 21, 2021 |
| Acer          | Aspire E5-471G              | Notebook    | [7f7c5133ad](https://linux-hardware.org/?probe=7f7c5133ad) | Aug 18, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [ae7b04d5d3](https://linux-hardware.org/?probe=ae7b04d5d3) | Aug 12, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [68af6cccad](https://linux-hardware.org/?probe=68af6cccad) | Aug 05, 2021 |
| Dell          | 0D24M8 A00                  | Desktop     | [c56bb51edc](https://linux-hardware.org/?probe=c56bb51edc) | Aug 03, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [1a50426a2c](https://linux-hardware.org/?probe=1a50426a2c) | Aug 02, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [94623b82cf](https://linux-hardware.org/?probe=94623b82cf) | Aug 02, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [73a47bf698](https://linux-hardware.org/?probe=73a47bf698) | Aug 02, 2021 |
| HP            | 0AECh D                     | Desktop     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [65ad8ece4a](https://linux-hardware.org/?probe=65ad8ece4a) | Jul 30, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [10b4953c7e](https://linux-hardware.org/?probe=10b4953c7e) | Jul 26, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [71aae9e020](https://linux-hardware.org/?probe=71aae9e020) | Jul 26, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [3db5dd7ea0](https://linux-hardware.org/?probe=3db5dd7ea0) | Jul 26, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | Notebook    | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b1d25f1e88](https://linux-hardware.org/?probe=b1d25f1e88) | Jul 22, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [568a71080e](https://linux-hardware.org/?probe=568a71080e) | Jul 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [9d13b7e8df](https://linux-hardware.org/?probe=9d13b7e8df) | Jul 21, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [6bf04f98f6](https://linux-hardware.org/?probe=6bf04f98f6) | Jul 21, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [c503220e78](https://linux-hardware.org/?probe=c503220e78) | Jul 19, 2021 |
| Acer          | Aspire E5-471G              | Notebook    | [bde4a22e40](https://linux-hardware.org/?probe=bde4a22e40) | Jul 19, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [5c7365be9d](https://linux-hardware.org/?probe=5c7365be9d) | Jul 16, 2021 |
| Acer          | One 10 SW110-1CT            | Tablet      | [51296db584](https://linux-hardware.org/?probe=51296db584) | Jul 14, 2021 |
| Acer          | One 10 SW110-1CT            | Tablet      | [9a40d5c9da](https://linux-hardware.org/?probe=9a40d5c9da) | Jul 14, 2021 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [e46886ce2d](https://linux-hardware.org/?probe=e46886ce2d) | Jul 12, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [c298371b89](https://linux-hardware.org/?probe=c298371b89) | Jul 12, 2021 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [f51a4f44b2](https://linux-hardware.org/?probe=f51a4f44b2) | Jul 12, 2021 |
| Dell          | Vostro 3578                 | Notebook    | [f5bfb0ada6](https://linux-hardware.org/?probe=f5bfb0ada6) | Jul 09, 2021 |
| Dell          | Vostro 3578                 | Notebook    | [e69ebc683f](https://linux-hardware.org/?probe=e69ebc683f) | Jul 09, 2021 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [2c6fd223a1](https://linux-hardware.org/?probe=2c6fd223a1) | Jul 07, 2021 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [1270256228](https://linux-hardware.org/?probe=1270256228) | Jul 07, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [40450f88e3](https://linux-hardware.org/?probe=40450f88e3) | Jul 07, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [7eb7b4a001](https://linux-hardware.org/?probe=7eb7b4a001) | Jul 07, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [e8c3804e26](https://linux-hardware.org/?probe=e8c3804e26) | Jun 25, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Fujitsu       | LIFEBOOK BH531              | Notebook    | [688d9f583e](https://linux-hardware.org/?probe=688d9f583e) | Jun 16, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [db886610f5](https://linux-hardware.org/?probe=db886610f5) | Jun 11, 2021 |
| HP            | Stream Notebook             | Notebook    | [806c24449c](https://linux-hardware.org/?probe=806c24449c) | Jun 09, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [45b8d7ca02](https://linux-hardware.org/?probe=45b8d7ca02) | Jun 08, 2021 |
| ASUSTek       | X450LN                      | Notebook    | [9157df68c1](https://linux-hardware.org/?probe=9157df68c1) | May 27, 2021 |
| Lenovo        | B50-80 80LT                 | Notebook    | [ef615e10ea](https://linux-hardware.org/?probe=ef615e10ea) | May 27, 2021 |
| Intel         | H61M S1                     | Desktop     | [f60c55c8c4](https://linux-hardware.org/?probe=f60c55c8c4) | May 27, 2021 |
| ASUSTek       | X450LN                      | Notebook    | [aa8e32e484](https://linux-hardware.org/?probe=aa8e32e484) | May 25, 2021 |
| Toshiba       | Satellite L645              | Notebook    | [a3c061e392](https://linux-hardware.org/?probe=a3c061e392) | May 17, 2021 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [0d99884dcd](https://linux-hardware.org/?probe=0d99884dcd) | May 17, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [e8e3c50f4b](https://linux-hardware.org/?probe=e8e3c50f4b) | May 16, 2021 |
| Dell          | Latitude 3410               | Notebook    | [b29d7ddfe8](https://linux-hardware.org/?probe=b29d7ddfe8) | May 09, 2021 |
| Dell          | Latitude E6430              | Notebook    | [1a7d88c72a](https://linux-hardware.org/?probe=1a7d88c72a) | May 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [7b00c56952](https://linux-hardware.org/?probe=7b00c56952) | May 02, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [aa9bfbf347](https://linux-hardware.org/?probe=aa9bfbf347) | Apr 29, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [298d859193](https://linux-hardware.org/?probe=298d859193) | Apr 27, 2021 |
| Dell          | Latitude 3410               | Notebook    | [b6748a9a7e](https://linux-hardware.org/?probe=b6748a9a7e) | Apr 25, 2021 |
| Acer          | Veriton X2665G              | Desktop     | [f23ed8abd1](https://linux-hardware.org/?probe=f23ed8abd1) | Apr 20, 2021 |
| Fujitsu       | LIFEBOOK BH531              | Notebook    | [2fa4c2d1ef](https://linux-hardware.org/?probe=2fa4c2d1ef) | Apr 18, 2021 |
| Huanan        | X79 249PC V2.2              | Desktop     | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| ASRock        | G31M-S                      | Desktop     | [ee71002286](https://linux-hardware.org/?probe=ee71002286) | Mar 26, 2021 |
| Huanan        | X79 V6.11                   | Desktop     | [85cbe2c1ed](https://linux-hardware.org/?probe=85cbe2c1ed) | Mar 16, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [bca1dbaafd](https://linux-hardware.org/?probe=bca1dbaafd) | Mar 10, 2021 |
| Dell          | G7 7590                     | Notebook    | [be5780df0a](https://linux-hardware.org/?probe=be5780df0a) | Mar 09, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [465d5f43f1](https://linux-hardware.org/?probe=465d5f43f1) | Mar 08, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [32e4837219](https://linux-hardware.org/?probe=32e4837219) | Mar 05, 2021 |
| Unknown       | Unknown                     | Tablet      | [315c09fd74](https://linux-hardware.org/?probe=315c09fd74) | Mar 04, 2021 |
| Gigabyte      | Z490 UD                     | Desktop     | [ec3e24bbcc](https://linux-hardware.org/?probe=ec3e24bbcc) | Mar 02, 2021 |
| Samsung       | R780/R778                   | Notebook    | [0c57a7241e](https://linux-hardware.org/?probe=0c57a7241e) | Feb 26, 2021 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [d8037b520e](https://linux-hardware.org/?probe=d8037b520e) | Feb 26, 2021 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [f1e66dfcc2](https://linux-hardware.org/?probe=f1e66dfcc2) | Feb 22, 2021 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [90a83f66fc](https://linux-hardware.org/?probe=90a83f66fc) | Feb 21, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [1faf0b360f](https://linux-hardware.org/?probe=1faf0b360f) | Feb 19, 2021 |
| ASUSTek       | K45VM                       | Notebook    | [26690f314d](https://linux-hardware.org/?probe=26690f314d) | Feb 15, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [1b2994e7f3](https://linux-hardware.org/?probe=1b2994e7f3) | Feb 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [40bcb4aaf2](https://linux-hardware.org/?probe=40bcb4aaf2) | Feb 15, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [0392f08b03](https://linux-hardware.org/?probe=0392f08b03) | Feb 15, 2021 |
| HP            | 1998                        | Desktop     | [c415742b9e](https://linux-hardware.org/?probe=c415742b9e) | Feb 13, 2021 |
| Acer          | Aspire E5-471G              | Notebook    | [401fa9d58e](https://linux-hardware.org/?probe=401fa9d58e) | Feb 13, 2021 |
| Dell          | 0F8096                      | Desktop     | [d6748871e7](https://linux-hardware.org/?probe=d6748871e7) | Feb 13, 2021 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [bd0fcefe9f](https://linux-hardware.org/?probe=bd0fcefe9f) | Feb 13, 2021 |
| HP            | 1000                        | Notebook    | [16b305a6f5](https://linux-hardware.org/?probe=16b305a6f5) | Feb 13, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [20b10721e2](https://linux-hardware.org/?probe=20b10721e2) | Feb 09, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [da10acb66c](https://linux-hardware.org/?probe=da10acb66c) | Feb 07, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [360e7155d7](https://linux-hardware.org/?probe=360e7155d7) | Feb 06, 2021 |
| Dell          | 0F8096                      | Desktop     | [d6ce430a08](https://linux-hardware.org/?probe=d6ce430a08) | Feb 04, 2021 |
| Gigabyte      | G41M-ES2H                   | Desktop     | [53c32c80a6](https://linux-hardware.org/?probe=53c32c80a6) | Feb 03, 2021 |
| Sony          | SVF14N25CXB                 | Notebook    | [1db1e6aec9](https://linux-hardware.org/?probe=1db1e6aec9) | Jan 28, 2021 |
| Acer          | Aspire M1935                | Desktop     | [64d53ff0ad](https://linux-hardware.org/?probe=64d53ff0ad) | Jan 28, 2021 |
| Fujitsu       | JIM76YK3                    | Desktop     | [4c5225559f](https://linux-hardware.org/?probe=4c5225559f) | Jan 23, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [6ba43f198a](https://linux-hardware.org/?probe=6ba43f198a) | Jan 22, 2021 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | Notebook    | [731a44edca](https://linux-hardware.org/?probe=731a44edca) | Jan 16, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [1a065f105a](https://linux-hardware.org/?probe=1a065f105a) | Jan 16, 2021 |
| Lenovo        | IdeaPad Y450                | Notebook    | [1285c5deb9](https://linux-hardware.org/?probe=1285c5deb9) | Jan 11, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [788c6c2caf](https://linux-hardware.org/?probe=788c6c2caf) | Jan 07, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [fcdcacd2bc](https://linux-hardware.org/?probe=fcdcacd2bc) | Jan 07, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [f224060be4](https://linux-hardware.org/?probe=f224060be4) | Jan 07, 2021 |
| Fujitsu       | JIM76YK3                    | Desktop     | [b33ad621e1](https://linux-hardware.org/?probe=b33ad621e1) | Jan 07, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [26d33eb0de](https://linux-hardware.org/?probe=26d33eb0de) | Jan 06, 2021 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [e28d350fac](https://linux-hardware.org/?probe=e28d350fac) | Dec 24, 2020 |
| ASUSTek       | X450CC                      | Notebook    | [750f666a09](https://linux-hardware.org/?probe=750f666a09) | Dec 23, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9bcae82db8](https://linux-hardware.org/?probe=9bcae82db8) | Dec 16, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [039b541097](https://linux-hardware.org/?probe=039b541097) | Dec 16, 2020 |
| Lenovo        | ThinkPad E15 20RES51Y00     | Notebook    | [66b1afc07c](https://linux-hardware.org/?probe=66b1afc07c) | Dec 15, 2020 |
| ASRock        | Z390 Pro4                   | Desktop     | [3befcf341c](https://linux-hardware.org/?probe=3befcf341c) | Dec 14, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [a5170be239](https://linux-hardware.org/?probe=a5170be239) | Dec 11, 2020 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [86f61c5fce](https://linux-hardware.org/?probe=86f61c5fce) | Dec 11, 2020 |
| Dell          | Inspiron 5468               | Notebook    | [abc26c7422](https://linux-hardware.org/?probe=abc26c7422) | Dec 09, 2020 |
| MSI           | PE70 6QE                    | Notebook    | [cb5f05e67d](https://linux-hardware.org/?probe=cb5f05e67d) | Dec 02, 2020 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [813b0a40eb](https://linux-hardware.org/?probe=813b0a40eb) | Dec 01, 2020 |
| Acer          | Aspire E5-475G              | Notebook    | [53a62697ed](https://linux-hardware.org/?probe=53a62697ed) | Dec 01, 2020 |
| Acer          | Aspire E5-475G              | Notebook    | [719a24bc0f](https://linux-hardware.org/?probe=719a24bc0f) | Nov 30, 2020 |
| MSI           | PE70 6QE                    | Notebook    | [90b21f8369](https://linux-hardware.org/?probe=90b21f8369) | Nov 23, 2020 |
| Acer          | Aspire VN7-793G             | Notebook    | [79f11201bc](https://linux-hardware.org/?probe=79f11201bc) | Nov 22, 2020 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [43c71a128c](https://linux-hardware.org/?probe=43c71a128c) | Nov 20, 2020 |
| Dell          | G5 5590                     | Notebook    | [007ad64378](https://linux-hardware.org/?probe=007ad64378) | Nov 20, 2020 |
| MSI           | GE75 Raider 10SGS           | Notebook    | [025deb9bbe](https://linux-hardware.org/?probe=025deb9bbe) | Nov 19, 2020 |
| Dell          | G5 5590                     | Notebook    | [e82ed4c1d0](https://linux-hardware.org/?probe=e82ed4c1d0) | Nov 19, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [f90473f671](https://linux-hardware.org/?probe=f90473f671) | Nov 16, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bf8d99074a](https://linux-hardware.org/?probe=bf8d99074a) | Nov 15, 2020 |
| Unknown       | Unknown                     | Desktop     | [65fba277e7](https://linux-hardware.org/?probe=65fba277e7) | Nov 11, 2020 |
| Unknown       | Unknown                     | Desktop     | [2a8118e258](https://linux-hardware.org/?probe=2a8118e258) | Nov 11, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [4c0fec3ac5](https://linux-hardware.org/?probe=4c0fec3ac5) | Nov 09, 2020 |
| Hampoo        | Unknown                     | Notebook    | [b713cd21d1](https://linux-hardware.org/?probe=b713cd21d1) | Oct 24, 2020 |
| Hampoo        | Unknown                     | Notebook    | [03640b9aac](https://linux-hardware.org/?probe=03640b9aac) | Oct 24, 2020 |
| MSI           | PE70 6QE                    | Notebook    | [8c3ccf4956](https://linux-hardware.org/?probe=8c3ccf4956) | Oct 19, 2020 |
| ASRock        | Z270 Killer SLI             | Desktop     | [42e012b0e1](https://linux-hardware.org/?probe=42e012b0e1) | Oct 19, 2020 |
| Dell          | Precision 7740              | Notebook    | [814a0ec705](https://linux-hardware.org/?probe=814a0ec705) | Oct 15, 2020 |
| MSI           | PE70 6QE                    | Notebook    | [1691661a18](https://linux-hardware.org/?probe=1691661a18) | Oct 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [e0d54e69ff](https://linux-hardware.org/?probe=e0d54e69ff) | Oct 11, 2020 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [2b12ebd1f3](https://linux-hardware.org/?probe=2b12ebd1f3) | Oct 09, 2020 |
| Gigabyte      | F2A85XM-HD3                 | Desktop     | [4a8bc27a98](https://linux-hardware.org/?probe=4a8bc27a98) | Oct 06, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [924b361628](https://linux-hardware.org/?probe=924b361628) | Oct 04, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [cce759037c](https://linux-hardware.org/?probe=cce759037c) | Oct 01, 2020 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [93a29298d7](https://linux-hardware.org/?probe=93a29298d7) | Sep 29, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c9ece9190b](https://linux-hardware.org/?probe=c9ece9190b) | Sep 27, 2020 |
| HP            | Pavilion dv7                | Notebook    | [058179daf5](https://linux-hardware.org/?probe=058179daf5) | Sep 24, 2020 |
| ASRock        | B460M Steel Legend          | Desktop     | [5398b2247d](https://linux-hardware.org/?probe=5398b2247d) | Sep 12, 2020 |
| ASRock        | B460M Steel Legend          | Desktop     | [44abe999aa](https://linux-hardware.org/?probe=44abe999aa) | Sep 12, 2020 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [25c77e6927](https://linux-hardware.org/?probe=25c77e6927) | Sep 11, 2020 |
| HP            | Pavilion dv6                | Notebook    | [acce68d947](https://linux-hardware.org/?probe=acce68d947) | Sep 09, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2b4fe70eaf](https://linux-hardware.org/?probe=2b4fe70eaf) | Sep 04, 2020 |
| Dell          | Inspiron 5447               | Notebook    | [9fc26445da](https://linux-hardware.org/?probe=9fc26445da) | Sep 03, 2020 |
| Dell          | Inspiron 5447               | Notebook    | [fd56e29478](https://linux-hardware.org/?probe=fd56e29478) | Sep 03, 2020 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [e55f750fc2](https://linux-hardware.org/?probe=e55f750fc2) | Sep 02, 2020 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [cc7e35217e](https://linux-hardware.org/?probe=cc7e35217e) | Sep 02, 2020 |
| ASRock        | B450M Steel Legend          | Desktop     | [2aa3eef6bd](https://linux-hardware.org/?probe=2aa3eef6bd) | Sep 02, 2020 |
| Acer          | Aspire VN7-792G             | Notebook    | [706847f6cd](https://linux-hardware.org/?probe=706847f6cd) | Aug 30, 2020 |
| Dell          | 0X8DXD A01                  | Desktop     | [0c6362ecb0](https://linux-hardware.org/?probe=0c6362ecb0) | Aug 24, 2020 |
| Lenovo        | No DPK                      | All in one  | [08057029e5](https://linux-hardware.org/?probe=08057029e5) | Aug 23, 2020 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [c90b90e1a8](https://linux-hardware.org/?probe=c90b90e1a8) | Aug 21, 2020 |
| ASRock        | Z77 Extreme6                | Desktop     | [a23bd9e79b](https://linux-hardware.org/?probe=a23bd9e79b) | Aug 19, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [211cb85a6f](https://linux-hardware.org/?probe=211cb85a6f) | Aug 08, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [dc8ed0c837](https://linux-hardware.org/?probe=dc8ed0c837) | Jul 30, 2020 |
| ASUSTek       | X411UN                      | Notebook    | [212932d80d](https://linux-hardware.org/?probe=212932d80d) | Jul 27, 2020 |
| ASRock        | B450 Pro4                   | Desktop     | [c318976f19](https://linux-hardware.org/?probe=c318976f19) | Jul 26, 2020 |
| Gigabyte      | P67A-UD3P-B3                | Desktop     | [d68a3e43ab](https://linux-hardware.org/?probe=d68a3e43ab) | Jul 25, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [8dd238e5a1](https://linux-hardware.org/?probe=8dd238e5a1) | Jul 24, 2020 |
| Acer          | Swift SF314-57G             | Notebook    | [c74653b694](https://linux-hardware.org/?probe=c74653b694) | Jul 15, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [f545576ae9](https://linux-hardware.org/?probe=f545576ae9) | Jul 14, 2020 |
| Acer          | Aspire VN7-792G             | Notebook    | [405d399549](https://linux-hardware.org/?probe=405d399549) | Jul 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [4175ac62a0](https://linux-hardware.org/?probe=4175ac62a0) | Jul 10, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [7c061a0688](https://linux-hardware.org/?probe=7c061a0688) | Jul 06, 2020 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [f395c86ea3](https://linux-hardware.org/?probe=f395c86ea3) | Jul 05, 2020 |
| Acer          | Aspire VN7-792G             | Notebook    | [1457f6e3b5](https://linux-hardware.org/?probe=1457f6e3b5) | Jul 04, 2020 |
| Fujitsu       | LIFEBOOK BH531              | Notebook    | [2484e68205](https://linux-hardware.org/?probe=2484e68205) | Jul 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [adc28756a8](https://linux-hardware.org/?probe=adc28756a8) | Jun 29, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [6e947dfc9d](https://linux-hardware.org/?probe=6e947dfc9d) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | Desktop     | [ef9bd4541a](https://linux-hardware.org/?probe=ef9bd4541a) | Jun 27, 2020 |
| ASUSTek       | H61M-D                      | Desktop     | [d9b6cb6c0b](https://linux-hardware.org/?probe=d9b6cb6c0b) | Jun 27, 2020 |
| ASUSTek       | K42JB                       | Notebook    | [5f87f39c75](https://linux-hardware.org/?probe=5f87f39c75) | Jun 27, 2020 |
| MSI           | MS-14Y1                     | Notebook    | [c585b33393](https://linux-hardware.org/?probe=c585b33393) | Jun 25, 2020 |
| ASUSTek       | S340MF                      | Desktop     | [e8b7344421](https://linux-hardware.org/?probe=e8b7344421) | Jun 24, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [262f40d535](https://linux-hardware.org/?probe=262f40d535) | Jun 20, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [8d0c93ef24](https://linux-hardware.org/?probe=8d0c93ef24) | Jun 17, 2020 |
| Gigabyte      | Z390 UD                     | Desktop     | [1bd38851f2](https://linux-hardware.org/?probe=1bd38851f2) | Jun 13, 2020 |
| Lenovo        | No DPK                      | All in one  | [72809cb04b](https://linux-hardware.org/?probe=72809cb04b) | Jun 05, 2020 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [79456b5994](https://linux-hardware.org/?probe=79456b5994) | Jun 05, 2020 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [f839493f2c](https://linux-hardware.org/?probe=f839493f2c) | Jun 05, 2020 |
| MSI           | MS-14Y1                     | Notebook    | [657c6d539f](https://linux-hardware.org/?probe=657c6d539f) | Jun 03, 2020 |
| Sony          | SVF14N25CXB                 | Notebook    | [2fdd1fc4d3](https://linux-hardware.org/?probe=2fdd1fc4d3) | Jun 02, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [859b71baa9](https://linux-hardware.org/?probe=859b71baa9) | Jun 01, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [2c3fadf526](https://linux-hardware.org/?probe=2c3fadf526) | Jun 01, 2020 |
| ASUSTek       | K53SV                       | Notebook    | [0bb72c8f71](https://linux-hardware.org/?probe=0bb72c8f71) | Jun 01, 2020 |
| Lenovo        | Yoga S740-15IRH 81NX        | Convertible | [6af9fd9245](https://linux-hardware.org/?probe=6af9fd9245) | May 31, 2020 |
| Lenovo        | No DPK                      | All in one  | [f2bbfbe37d](https://linux-hardware.org/?probe=f2bbfbe37d) | May 27, 2020 |
| ASUSTek       | M2N                         | Desktop     | [383651de63](https://linux-hardware.org/?probe=383651de63) | May 26, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [645ef14cb4](https://linux-hardware.org/?probe=645ef14cb4) | May 21, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [4827cdc9b5](https://linux-hardware.org/?probe=4827cdc9b5) | May 21, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [94ad6c90d4](https://linux-hardware.org/?probe=94ad6c90d4) | May 21, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | Notebook    | [338493712f](https://linux-hardware.org/?probe=338493712f) | May 19, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | Notebook    | [17f5a0932c](https://linux-hardware.org/?probe=17f5a0932c) | May 19, 2020 |
| Samsung       | RV418/RV518/RV718           | Notebook    | [ff8f525d6b](https://linux-hardware.org/?probe=ff8f525d6b) | May 18, 2020 |
| Lenovo        | G480 20156                  | Notebook    | [6cb3a28f6a](https://linux-hardware.org/?probe=6cb3a28f6a) | May 18, 2020 |
| Lenovo        | G480 20156                  | Notebook    | [7487bf67c4](https://linux-hardware.org/?probe=7487bf67c4) | May 18, 2020 |
| Unknown       | Unknown                     | Desktop     | [6f211d004a](https://linux-hardware.org/?probe=6f211d004a) | May 10, 2020 |
| Unknown       | Unknown                     | Desktop     | [b3ddb6ef68](https://linux-hardware.org/?probe=b3ddb6ef68) | May 09, 2020 |
| Unknown       | Unknown                     | Desktop     | [0a74b9927c](https://linux-hardware.org/?probe=0a74b9927c) | May 09, 2020 |
| Acer          | Nitro AN515-42              | Notebook    | [5c659d6268](https://linux-hardware.org/?probe=5c659d6268) | May 07, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | Notebook    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [f286a38265](https://linux-hardware.org/?probe=f286a38265) | Apr 30, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [1275e05c7b](https://linux-hardware.org/?probe=1275e05c7b) | Apr 20, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [bbd3e36751](https://linux-hardware.org/?probe=bbd3e36751) | Apr 16, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [8bca0c818d](https://linux-hardware.org/?probe=8bca0c818d) | Apr 16, 2020 |
| Pegatron      | 2A99                        | Desktop     | [f01c0c56e7](https://linux-hardware.org/?probe=f01c0c56e7) | Apr 08, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [8958ee3446](https://linux-hardware.org/?probe=8958ee3446) | Apr 07, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [4a07604dd5](https://linux-hardware.org/?probe=4a07604dd5) | Apr 06, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [c5b4596173](https://linux-hardware.org/?probe=c5b4596173) | Apr 06, 2020 |
| Lenovo        | ThinkPad T420 4180JH1       | Notebook    | [4d0e9109bb](https://linux-hardware.org/?probe=4d0e9109bb) | Mar 21, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [d577b178a1](https://linux-hardware.org/?probe=d577b178a1) | Mar 06, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [cc28243d3d](https://linux-hardware.org/?probe=cc28243d3d) | Mar 06, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [1d2bb93475](https://linux-hardware.org/?probe=1d2bb93475) | Mar 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [626f7fb341](https://linux-hardware.org/?probe=626f7fb341) | Feb 29, 2020 |
| Packard Be... | IMEDIA S3720                | Desktop     | [04ba71e930](https://linux-hardware.org/?probe=04ba71e930) | Feb 25, 2020 |
| Acer          | Predator PH315-51           | Notebook    | [b3edf8c190](https://linux-hardware.org/?probe=b3edf8c190) | Feb 23, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [8d16cc2992](https://linux-hardware.org/?probe=8d16cc2992) | Feb 23, 2020 |
| Samsung       | NC208/NC108                 | Notebook    | [ffbfac004c](https://linux-hardware.org/?probe=ffbfac004c) | Feb 23, 2020 |
| Dell          | Precision 5510              | Notebook    | [0e30ff12b4](https://linux-hardware.org/?probe=0e30ff12b4) | Feb 18, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [ac7b752d68](https://linux-hardware.org/?probe=ac7b752d68) | Feb 13, 2020 |
| Acer          | Aspire XC-330               | Desktop     | [168e69a32d](https://linux-hardware.org/?probe=168e69a32d) | Feb 11, 2020 |
| Acer          | Aspire XC-330               | Desktop     | [f1cbd72914](https://linux-hardware.org/?probe=f1cbd72914) | Feb 10, 2020 |
| Acer          | Aspire XC-330               | Desktop     | [0e517066e2](https://linux-hardware.org/?probe=0e517066e2) | Feb 08, 2020 |
| Acer          | Aspire XC-330               | Desktop     | [687cbfa242](https://linux-hardware.org/?probe=687cbfa242) | Feb 08, 2020 |
| HP            | Compaq 15                   | Notebook    | [e8597ab3e4](https://linux-hardware.org/?probe=e8597ab3e4) | Feb 06, 2020 |
| MSI           | X460/X460DX                 | Notebook    | [faf3829102](https://linux-hardware.org/?probe=faf3829102) | Feb 04, 2020 |
| HP            | 3048h                       | Desktop     | [ff1cde7e50](https://linux-hardware.org/?probe=ff1cde7e50) | Feb 04, 2020 |
| HP            | 3048h                       | Desktop     | [398e00244e](https://linux-hardware.org/?probe=398e00244e) | Feb 04, 2020 |
| HP            | 3048h                       | Desktop     | [69ac011884](https://linux-hardware.org/?probe=69ac011884) | Feb 04, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [a79eea9131](https://linux-hardware.org/?probe=a79eea9131) | Jan 30, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [d47fbd4f5c](https://linux-hardware.org/?probe=d47fbd4f5c) | Jan 30, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [00b99ed436](https://linux-hardware.org/?probe=00b99ed436) | Jan 20, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [1c91ad30fd](https://linux-hardware.org/?probe=1c91ad30fd) | Jan 19, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [eb0d14b4ad](https://linux-hardware.org/?probe=eb0d14b4ad) | Jan 18, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [8827da4dc1](https://linux-hardware.org/?probe=8827da4dc1) | Jan 15, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [c228f44226](https://linux-hardware.org/?probe=c228f44226) | Jan 14, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [dd045a2aef](https://linux-hardware.org/?probe=dd045a2aef) | Jan 13, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [3fb9d0e024](https://linux-hardware.org/?probe=3fb9d0e024) | Jan 11, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [4fae95f520](https://linux-hardware.org/?probe=4fae95f520) | Jan 10, 2020 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [f78dc97f63](https://linux-hardware.org/?probe=f78dc97f63) | Jan 07, 2020 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [0e11277c74](https://linux-hardware.org/?probe=0e11277c74) | Jan 06, 2020 |
| Acer          | Veriton Z4660G              | All in one  | [866f2f8c49](https://linux-hardware.org/?probe=866f2f8c49) | Dec 28, 2019 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [670b5a0247](https://linux-hardware.org/?probe=670b5a0247) | Dec 27, 2019 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [fc21e1c322](https://linux-hardware.org/?probe=fc21e1c322) | Dec 18, 2019 |
| Lenovo        | ThinkPad P50 20EQS5XE00     | Notebook    | [65dc93e325](https://linux-hardware.org/?probe=65dc93e325) | Dec 18, 2019 |
| HP            | 2B15A                       | Desktop     | [24dd32836d](https://linux-hardware.org/?probe=24dd32836d) | Dec 14, 2019 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [6d7723d13c](https://linux-hardware.org/?probe=6d7723d13c) | Dec 08, 2019 |
| MSI           | 760GM-P23                   | Desktop     | [bbd22621aa](https://linux-hardware.org/?probe=bbd22621aa) | Dec 05, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| Fujitsu       | LIFEBOOK BH531              | Notebook    | [c00057fc87](https://linux-hardware.org/?probe=c00057fc87) | Dec 01, 2019 |
| Clevo         | M540SR VT6363A              | Notebook    | [97181c941c](https://linux-hardware.org/?probe=97181c941c) | Nov 23, 2019 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [9f6b248a62](https://linux-hardware.org/?probe=9f6b248a62) | Nov 22, 2019 |
| Fujitsu       | LIFEBOOK BH531              | Notebook    | [0223eca896](https://linux-hardware.org/?probe=0223eca896) | Nov 22, 2019 |
| Lenovo        | G710 20252                  | Notebook    | [d11fbec88a](https://linux-hardware.org/?probe=d11fbec88a) | Nov 14, 2019 |
| Lenovo        | G710 20252                  | Notebook    | [21ae1ec676](https://linux-hardware.org/?probe=21ae1ec676) | Nov 10, 2019 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [6a6a0d614e](https://linux-hardware.org/?probe=6a6a0d614e) | Oct 29, 2019 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [3d932d77ba](https://linux-hardware.org/?probe=3d932d77ba) | Oct 29, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [b65742b189](https://linux-hardware.org/?probe=b65742b189) | Oct 26, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [6ccf378246](https://linux-hardware.org/?probe=6ccf378246) | Oct 26, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [29d4434f82](https://linux-hardware.org/?probe=29d4434f82) | Oct 26, 2019 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [73bfd283e5](https://linux-hardware.org/?probe=73bfd283e5) | Oct 25, 2019 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [7da594325d](https://linux-hardware.org/?probe=7da594325d) | Oct 07, 2019 |
| Acer          | Swift SF113-31              | Notebook    | [a37935b2e0](https://linux-hardware.org/?probe=a37935b2e0) | Sep 27, 2019 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | Notebook    | [ccf2eacdd1](https://linux-hardware.org/?probe=ccf2eacdd1) | Sep 14, 2019 |
| Acer          | Aspire E5-552G              | Notebook    | [5c4bd87bc9](https://linux-hardware.org/?probe=5c4bd87bc9) | Sep 04, 2019 |
| Dell          | Vostro 3458                 | Notebook    | [a62197181c](https://linux-hardware.org/?probe=a62197181c) | Sep 04, 2019 |
| Lenovo        | G460 20041                  | Notebook    | [7b5945bfc2](https://linux-hardware.org/?probe=7b5945bfc2) | Aug 31, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [2d5f51cdd8](https://linux-hardware.org/?probe=2d5f51cdd8) | Aug 23, 2019 |
| ASUSTek       | H81M-CS                     | Desktop     | [577f91eb8a](https://linux-hardware.org/?probe=577f91eb8a) | Aug 18, 2019 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fe49019be0](https://linux-hardware.org/?probe=fe49019be0) | Aug 16, 2019 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7551b403e2](https://linux-hardware.org/?probe=7551b403e2) | Aug 16, 2019 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ef69a20f15](https://linux-hardware.org/?probe=ef69a20f15) | Aug 07, 2019 |
| ASUSTek       | H81M-E                      | Desktop     | [18e73b61d9](https://linux-hardware.org/?probe=18e73b61d9) | Aug 02, 2019 |
| MSI           | H170 GAMING M3              | Desktop     | [8b7204fcba](https://linux-hardware.org/?probe=8b7204fcba) | Jul 23, 2019 |
| HP            | ENVY Laptop ah0xxx          | Notebook    | [defe18c4c3](https://linux-hardware.org/?probe=defe18c4c3) | Jul 09, 2019 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [7136ff50b4](https://linux-hardware.org/?probe=7136ff50b4) | Jul 04, 2019 |
| MSI           | 2A9C                        | Desktop     | [e4de30c7e4](https://linux-hardware.org/?probe=e4de30c7e4) | Jun 25, 2019 |
| Dell          | Latitude E6430              | Notebook    | [c8334c6a31](https://linux-hardware.org/?probe=c8334c6a31) | Jun 22, 2019 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [26db49d8f2](https://linux-hardware.org/?probe=26db49d8f2) | Jun 19, 2019 |
| Lenovo        | G460 20041                  | Notebook    | [62697bf35b](https://linux-hardware.org/?probe=62697bf35b) | Jun 16, 2019 |
| Biostar       | A10N-8800E                  | Desktop     | [e160dec9cf](https://linux-hardware.org/?probe=e160dec9cf) | Jun 08, 2019 |
| Lenovo        | MIIX 520-12IKB 81CG         | Tablet      | [1dd80d33e5](https://linux-hardware.org/?probe=1dd80d33e5) | May 24, 2019 |
| Lenovo        | MIIX 520-12IKB 81CG         | Tablet      | [1ad0a80b86](https://linux-hardware.org/?probe=1ad0a80b86) | May 24, 2019 |
| Acer          | Aspire A315-21              | Notebook    | [6d4aebc3ef](https://linux-hardware.org/?probe=6d4aebc3ef) | May 22, 2019 |
| ASUSTek       | P7P55 LX                    | Desktop     | [349a68f1f0](https://linux-hardware.org/?probe=349a68f1f0) | May 20, 2019 |
| ASUSTek       | P7P55 LX                    | Desktop     | [7c9e75ec67](https://linux-hardware.org/?probe=7c9e75ec67) | May 20, 2019 |
| MSI           | 2A9C                        | Desktop     | [d810098335](https://linux-hardware.org/?probe=d810098335) | May 09, 2019 |
| Acer          | Aspire A315-21              | Notebook    | [f878e784e2](https://linux-hardware.org/?probe=f878e784e2) | May 04, 2019 |
| ASUSTek       | X556UQK                     | Notebook    | [d906d6357c](https://linux-hardware.org/?probe=d906d6357c) | May 02, 2019 |
| ASUSTek       | X556UQK                     | Notebook    | [63a8e04d9e](https://linux-hardware.org/?probe=63a8e04d9e) | May 02, 2019 |
| ASUSTek       | X556UQK                     | Notebook    | [7d55bd0096](https://linux-hardware.org/?probe=7d55bd0096) | May 02, 2019 |
| ASUSTek       | X556UQK                     | Notebook    | [6648050a69](https://linux-hardware.org/?probe=6648050a69) | May 01, 2019 |
| Dell          | Inspiron 14-3467            | Notebook    | [9b390a3c82](https://linux-hardware.org/?probe=9b390a3c82) | Apr 11, 2019 |
| Dell          | Inspiron 14-3467            | Notebook    | [7f1e85018c](https://linux-hardware.org/?probe=7f1e85018c) | Apr 11, 2019 |
| ASRock        | Z77 Pro4                    | Desktop     | [f0f2be33be](https://linux-hardware.org/?probe=f0f2be33be) | Apr 04, 2019 |
| ASRock        | Z77 Pro4                    | Desktop     | [04a8af85b2](https://linux-hardware.org/?probe=04a8af85b2) | Apr 03, 2019 |
| Acer          | Aspire 4750                 | Notebook    | [94d50c8e16](https://linux-hardware.org/?probe=94d50c8e16) | Mar 26, 2019 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [c2c81fc796](https://linux-hardware.org/?probe=c2c81fc796) | Feb 15, 2019 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [d754fa1328](https://linux-hardware.org/?probe=d754fa1328) | Feb 15, 2019 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [31229ee6d4](https://linux-hardware.org/?probe=31229ee6d4) | Feb 04, 2019 |
| Lenovo        | MIIX 520-12IKB 81CG         | Tablet      | [1d220d1155](https://linux-hardware.org/?probe=1d220d1155) | Feb 04, 2019 |
| Apple         | MacBookAir3,2               | Notebook    | [ee6b3b0da4](https://linux-hardware.org/?probe=ee6b3b0da4) | Jan 29, 2019 |
| HP            | Compaq nx6325 (EQ422AV)     | Notebook    | [410fe4b520](https://linux-hardware.org/?probe=410fe4b520) | Dec 21, 2018 |
| HP            | Compaq nx6325 (EQ422AV)     | Notebook    | [1697d0f3f4](https://linux-hardware.org/?probe=1697d0f3f4) | Dec 21, 2018 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [64fa4eaf5e](https://linux-hardware.org/?probe=64fa4eaf5e) | Nov 30, 2018 |
| Acer          | Aspire 4741                 | Notebook    | [0875804f8d](https://linux-hardware.org/?probe=0875804f8d) | Nov 22, 2018 |
| Acer          | Aspire 4741                 | Notebook    | [d2f2af2cb2](https://linux-hardware.org/?probe=d2f2af2cb2) | Nov 13, 2018 |
| Lenovo        | G40-45 80E1                 | Notebook    | [ebf69568bf](https://linux-hardware.org/?probe=ebf69568bf) | Oct 29, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Thailand/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 62        | 13.45%  |
| Ubuntu 18.04                 | 34        | 7.38%   |
| Ubuntu 22.04                 | 21        | 4.56%   |
| OpenMandriva 4.2             | 16        | 3.47%   |
| Pop!_OS 22.04                | 14        | 3.04%   |
| KDE neon 20.04               | 12        | 2.6%    |
| Debian 11                    | 12        | 2.6%    |
| Arch Rolling                 | 12        | 2.6%    |
| OpenMandriva 4.3             | 11        | 2.39%   |
| Fedora 37                    | 11        | 2.39%   |
| OpenMandriva 23.01           | 9         | 1.95%   |
| Linux Mint 21                | 8         | 1.74%   |
| Fedora 38                    | 8         | 1.74%   |
| Zorin 15                     | 7         | 1.52%   |
| Manjaro                      | 7         | 1.52%   |
| Arch                         | 7         | 1.52%   |
| Zorin 16                     | 6         | 1.3%    |
| Ubuntu 19.10                 | 6         | 1.3%    |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 1.3%    |
| Linux Mint 20.2              | 6         | 1.3%    |
| KDE neon 22.04               | 6         | 1.3%    |
| Xubuntu 20.04                | 5         | 1.08%   |
| Ubuntu 19.04                 | 5         | 1.08%   |
| Linux Mint 20.3              | 5         | 1.08%   |
| Kubuntu 22.04                | 5         | 1.08%   |
| Fedora 36                    | 5         | 1.08%   |
| Debian Testing               | 5         | 1.08%   |
| Debian 10                    | 5         | 1.08%   |
| Ubuntu 16.04                 | 4         | 0.87%   |
| Pop!_OS 21.04                | 4         | 0.87%   |
| Linux Mint 19.3              | 4         | 0.87%   |
| Linux Mint 19.2              | 4         | 0.87%   |
| Fedora 35                    | 4         | 0.87%   |
| Fedora 33                    | 4         | 0.87%   |
| Xubuntu 18.04                | 3         | 0.65%   |
| Ubuntu 22.10                 | 3         | 0.65%   |
| Ubuntu 21.10                 | 3         | 0.65%   |
| Ubuntu 18.10                 | 3         | 0.65%   |
| Pop!_OS 20.04                | 3         | 0.65%   |
| Linux Mint 20                | 3         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 138       | 31.08%  |
| OpenMandriva  | 38        | 8.56%   |
| Fedora        | 37        | 8.33%   |
| Linux Mint    | 34        | 7.66%   |
| Pop!_OS       | 24        | 5.41%   |
| Debian        | 22        | 4.95%   |
| KDE neon      | 19        | 4.28%   |
| Arch          | 19        | 4.28%   |
| Endless       | 14        | 3.15%   |
| Zorin         | 13        | 2.93%   |
| Manjaro       | 10        | 2.25%   |
| Xubuntu       | 9         | 2.03%   |
| openSUSE      | 8         | 1.8%    |
| Kubuntu       | 8         | 1.8%    |
| Ubuntu MATE   | 6         | 1.35%   |
| Elementary    | 5         | 1.13%   |
| Clear Linux   | 5         | 1.13%   |
| Kali          | 4         | 0.9%    |
| SteamOS       | 3         | 0.68%   |
| MX            | 3         | 0.68%   |
| ArcoLinux     | 3         | 0.68%   |
| UbuntuDDE     | 2         | 0.45%   |
| Reborn OS     | 2         | 0.45%   |
| Lubuntu       | 2         | 0.45%   |
| EndeavourOS   | 2         | 0.45%   |
| CentOS        | 2         | 0.45%   |
| BlackPanther  | 2         | 0.45%   |
| Ubuntu Unity  | 1         | 0.23%   |
| Ubuntu Budgie | 1         | 0.23%   |
| Solus         | 1         | 0.23%   |
| ROSA          | 1         | 0.23%   |
| Nobara        | 1         | 0.23%   |
| Linux Lite    | 1         | 0.23%   |
| Lilidog       | 1         | 0.23%   |
| GNOME OS      | 1         | 0.23%   |
| Garuda Linux  | 1         | 0.23%   |
| Archcraft     | 1         | 0.23%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 16        | 3.19%   |
| 5.15.0-46-generic        | 10        | 1.99%   |
| 6.1.1-desktop-1omv2290   | 9         | 1.79%   |
| 5.16.7-desktop-1omv4003  | 9         | 1.79%   |
| 5.4.0-42-generic         | 7         | 1.39%   |
| 5.4.0-48-generic         | 6         | 1.2%    |
| 5.15.0-56-generic        | 6         | 1.2%    |
| 4.18.0-15-generic        | 6         | 1.2%    |
| 5.3.0-28-generic         | 5         | 1%      |
| 5.15.0-58-generic        | 5         | 1%      |
| 5.15.0-43-generic        | 5         | 1%      |
| 6.0.12-76060006-generic  | 4         | 0.8%    |
| 5.8.0-59-generic         | 4         | 0.8%    |
| 5.4.0-59-generic         | 4         | 0.8%    |
| 5.3.0-23-generic         | 4         | 0.8%    |
| 5.11.0-40-generic        | 4         | 0.8%    |
| 5.10.0-21-amd64          | 4         | 0.8%    |
| 5.0.0-32-generic         | 4         | 0.8%    |
| 6.0.6-76060006-generic   | 3         | 0.6%    |
| 5.8.0-63-generic         | 3         | 0.6%    |
| 5.8.0-50-generic         | 3         | 0.6%    |
| 5.8.0-14-generic         | 3         | 0.6%    |
| 5.4.0-66-generic         | 3         | 0.6%    |
| 5.4.0-45-generic         | 3         | 0.6%    |
| 5.4.0-39-generic         | 3         | 0.6%    |
| 5.4.0-37-generic         | 3         | 0.6%    |
| 5.4.0-31-generic         | 3         | 0.6%    |
| 5.3.0-53-generic         | 3         | 0.6%    |
| 5.19.0-76051900-generic  | 3         | 0.6%    |
| 5.19.0-43-generic        | 3         | 0.6%    |
| 5.19.0-38-generic        | 3         | 0.6%    |
| 5.17.5-76051705-generic  | 3         | 0.6%    |
| 5.15.0-60-generic        | 3         | 0.6%    |
| 5.15.0-52-generic        | 3         | 0.6%    |
| 5.13.0-39-generic        | 3         | 0.6%    |
| 5.11.0-43-generic        | 3         | 0.6%    |
| 5.11.0-37-generic        | 3         | 0.6%    |
| 5.0.0-27-generic         | 3         | 0.6%    |
| 6.2.6-desktop-1omv2390   | 2         | 0.4%    |
| 6.2.15-300.fc38.x86_64   | 2         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 73        | 14.93%  |
| 5.15.0  | 45        | 9.2%    |
| 5.13.0  | 27        | 5.52%   |
| 5.8.0   | 26        | 5.32%   |
| 4.15.0  | 24        | 4.91%   |
| 5.3.0   | 22        | 4.5%    |
| 5.11.0  | 18        | 3.68%   |
| 5.10.14 | 16        | 3.27%   |
| 5.0.0   | 16        | 3.27%   |
| 5.19.0  | 14        | 2.86%   |
| 4.18.0  | 14        | 2.86%   |
| 6.1.1   | 11        | 2.25%   |
| 5.10.0  | 10        | 2.04%   |
| 5.16.7  | 9         | 1.84%   |
| 4.19.0  | 7         | 1.43%   |
| 5.17.5  | 6         | 1.23%   |
| 6.0.12  | 5         | 1.02%   |
| 5.16.0  | 4         | 0.82%   |
| 6.1.12  | 3         | 0.61%   |
| 6.0.6   | 3         | 0.61%   |
| 6.2.9   | 2         | 0.41%   |
| 6.2.6   | 2         | 0.41%   |
| 6.2.2   | 2         | 0.41%   |
| 6.2.15  | 2         | 0.41%   |
| 6.2.14  | 2         | 0.41%   |
| 6.2.13  | 2         | 0.41%   |
| 6.1.11  | 2         | 0.41%   |
| 6.1.0   | 2         | 0.41%   |
| 6.0.7   | 2         | 0.41%   |
| 6.0.0   | 2         | 0.41%   |
| 5.8.14  | 2         | 0.41%   |
| 5.6.14  | 2         | 0.41%   |
| 5.5.7   | 2         | 0.41%   |
| 5.19.16 | 2         | 0.41%   |
| 5.19.13 | 2         | 0.41%   |
| 5.18.5  | 2         | 0.41%   |
| 5.18.0  | 2         | 0.41%   |
| 5.17.3  | 2         | 0.41%   |
| 5.17.0  | 2         | 0.41%   |
| 5.16.9  | 2         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 77        | 16.04%  |
| 5.15    | 55        | 11.46%  |
| 5.13    | 32        | 6.67%   |
| 5.8     | 30        | 6.25%   |
| 5.10    | 30        | 6.25%   |
| 5.3     | 24        | 5%      |
| 5.16    | 24        | 5%      |
| 4.15    | 24        | 5%      |
| 6.1     | 23        | 4.79%   |
| 5.19    | 21        | 4.38%   |
| 5.11    | 18        | 3.75%   |
| 5.0     | 17        | 3.54%   |
| 6.2     | 15        | 3.13%   |
| 4.18    | 15        | 3.13%   |
| 6.0     | 14        | 2.92%   |
| 5.17    | 13        | 2.71%   |
| 5.18    | 7         | 1.46%   |
| 4.19    | 7         | 1.46%   |
| 5.6     | 6         | 1.25%   |
| 5.9     | 5         | 1.04%   |
| 5.5     | 5         | 1.04%   |
| 5.12    | 5         | 1.04%   |
| 6.3     | 3         | 0.63%   |
| 5.14    | 3         | 0.63%   |
| 5.7     | 2         | 0.42%   |
| 4.20    | 2         | 0.42%   |
| 5.1     | 1         | 0.21%   |
| 4.4     | 1         | 0.21%   |
| 4.17    | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 426       | 99.07%  |
| i686   | 4         | 0.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 216       | 48.54%  |
| KDE5             | 73        | 16.4%   |
| Unknown          | 52        | 11.69%  |
| X-Cinnamon       | 31        | 6.97%   |
| XFCE             | 26        | 5.84%   |
| KDE              | 12        | 2.7%    |
| MATE             | 8         | 1.8%    |
| Pantheon         | 5         | 1.12%   |
| Budgie           | 5         | 1.12%   |
| Cinnamon         | 4         | 0.9%    |
| Deepin           | 3         | 0.67%   |
| LXQt             | 2         | 0.45%   |
| lightdm-xsession | 2         | 0.45%   |
| i3               | 2         | 0.45%   |
| Unity            | 1         | 0.22%   |
| openbox          | 1         | 0.22%   |
| LXDE             | 1         | 0.22%   |
| awesome          | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 328       | 74.55%  |
| Wayland | 73        | 16.59%  |
| Unknown | 32        | 7.27%   |
| Tty     | 7         | 1.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 241       | 54.28%  |
| SDDM    | 63        | 14.19%  |
| GDM     | 52        | 11.71%  |
| GDM3    | 43        | 9.68%   |
| LightDM | 34        | 7.66%   |
| TDM     | 9         | 2.03%   |
| XDM     | 1         | 0.23%   |
| Ly      | 1         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 303       | 69.18%  |
| Unknown | 47        | 10.73%  |
| en_GB   | 22        | 5.02%   |
| th_TH   | 20        | 4.57%   |
| de_DE   | 16        | 3.65%   |
| en_SG   | 7         | 1.6%    |
| C       | 7         | 1.6%    |
| fr_FR   | 5         | 1.14%   |
| ru_RU   | 3         | 0.68%   |
| it_IT   | 3         | 0.68%   |
| zh_CN   | 1         | 0.23%   |
| sv_SE   | 1         | 0.23%   |
| he_IL   | 1         | 0.23%   |
| es_MX   | 1         | 0.23%   |
| de_CH   | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 240       | 54.67%  |
| BIOS | 199       | 45.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 342       | 77.73%  |
| Btrfs   | 43        | 9.77%   |
| Overlay | 37        | 8.41%   |
| Unknown | 11        | 2.5%    |
| Xfs     | 4         | 0.91%   |
| Zfs     | 2         | 0.45%   |
| Tmpfs   | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 253       | 57.89%  |
| GPT     | 159       | 36.38%  |
| MBR     | 25        | 5.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 368       | 84.79%  |
| Yes       | 66        | 15.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 291       | 66.29%  |
| Yes       | 148       | 33.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUSTek Computer               | 75        | 17.44%  |
| Lenovo                         | 64        | 14.88%  |
| Acer                           | 48        | 11.16%  |
| Hewlett-Packard                | 41        | 9.53%   |
| Dell                           | 41        | 9.53%   |
| Gigabyte Technology            | 38        | 8.84%   |
| ASRock                         | 27        | 6.28%   |
| MSI                            | 26        | 6.05%   |
| Apple                          | 10        | 2.33%   |
| HUAWEI                         | 8         | 1.86%   |
| Unknown                        | 6         | 1.4%    |
| Intel                          | 5         | 1.16%   |
| Samsung Electronics            | 4         | 0.93%   |
| Toshiba                        | 3         | 0.7%    |
| Fujitsu                        | 3         | 0.7%    |
| Valve                          | 2         | 0.47%   |
| Supermicro                     | 2         | 0.47%   |
| Huanan                         | 2         | 0.47%   |
| VIA Technologies               | 1         | 0.23%   |
| Timi                           | 1         | 0.23%   |
| Sony                           | 1         | 0.23%   |
| SmbiosType1_SystemManufacturer | 1         | 0.23%   |
| SHARKBAY                       | 1         | 0.23%   |
| Razer                          | 1         | 0.23%   |
| Pegatron                       | 1         | 0.23%   |
| Packard Bell                   | 1         | 0.23%   |
| OEM                            | 1         | 0.23%   |
| Notebook                       | 1         | 0.23%   |
| MiTAC                          | 1         | 0.23%   |
| Microsoft                      | 1         | 0.23%   |
| MECHREVO                       | 1         | 0.23%   |
| Infinix                        | 1         | 0.23%   |
| Hampoo                         | 1         | 0.23%   |
| Framework                      | 1         | 0.23%   |
| Foxconn                        | 1         | 0.23%   |
| Cube                           | 1         | 0.23%   |
| Clevo                          | 1         | 0.23%   |
| Biostar                        | 1         | 0.23%   |
| BESSTAR Tech                   | 1         | 0.23%   |
| AZW                            | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 8         | 1.86%   |
| ASUS All Series                          | 7         | 1.63%   |
| Dell OptiPlex 7010                       | 4         | 0.93%   |
| Lenovo MIIX 520-12IKB 81CG               | 3         | 0.7%    |
| HUAWEI BOHB-WAX9                         | 3         | 0.7%    |
| ASUS P8H61-M LE                          | 3         | 0.7%    |
| ASRock B450 Steel Legend                 | 3         | 0.7%    |
| Valve Jupiter                            | 2         | 0.47%   |
| Samsung NC208/NC108                      | 2         | 0.47%   |
| Lenovo ThinkPad 11e 5th Gen 20LQS00000   | 2         | 0.47%   |
| Lenovo G460 20041                        | 2         | 0.47%   |
| HUAWEI KLVL-WXX9                         | 2         | 0.47%   |
| HP Z240 Tower Workstation                | 2         | 0.47%   |
| HP EliteDesk 800 G1 SFF PC               | 2         | 0.47%   |
| Gigabyte Z97X-UD3H-BK                    | 2         | 0.47%   |
| Gigabyte F2A88XM-HD3P                    | 2         | 0.47%   |
| Gigabyte F2A68HM-DS2                     | 2         | 0.47%   |
| Gigabyte B250-HD3                        | 2         | 0.47%   |
| Dell OptiPlex 3020                       | 2         | 0.47%   |
| Dell Latitude E6430                      | 2         | 0.47%   |
| Dell Latitude 3120                       | 2         | 0.47%   |
| Dell Inspiron 3847                       | 2         | 0.47%   |
| ASUS X556UQK                             | 2         | 0.47%   |
| ASUS X450LN                              | 2         | 0.47%   |
| ASUS VivoBook_ASUSLaptop M3500QA_D3500QA | 2         | 0.47%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA  | 2         | 0.47%   |
| ASUS TUF Gaming FX505DT_FX505DT          | 2         | 0.47%   |
| ASUS H110M-E/M.2                         | 2         | 0.47%   |
| ASRock B450M Steel Legend                | 2         | 0.47%   |
| Apple MacBookAir3,2                      | 2         | 0.47%   |
| Acer Aspire TC-885                       | 2         | 0.47%   |
| Acer Aspire F5-573G                      | 2         | 0.47%   |
| Acer Aspire E5-471G                      | 2         | 0.47%   |
| Acer Aspire A315-21                      | 2         | 0.47%   |
| VIA VX900                                | 1         | 0.23%   |
| Toshiba Satellite L840                   | 1         | 0.23%   |
| Toshiba Satellite L645                   | 1         | 0.23%   |
| Toshiba QOSMIO X70-B                     | 1         | 0.23%   |
| Timi TM1701                              | 1         | 0.23%   |
| Supermicro X9DRW                         | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 30        | 6.98%   |
| Lenovo ThinkPad   | 26        | 6.05%   |
| Lenovo IdeaPad    | 11        | 2.56%   |
| HP Pavilion       | 11        | 2.56%   |
| Dell OptiPlex     | 11        | 2.56%   |
| ASUS VivoBook     | 10        | 2.33%   |
| Dell Latitude     | 8         | 1.86%   |
| Dell Inspiron     | 8         | 1.86%   |
| Unknown           | 8         | 1.86%   |
| ASUS All          | 7         | 1.63%   |
| Lenovo Yoga       | 6         | 1.4%    |
| HP Laptop         | 6         | 1.4%    |
| ASUS PRIME        | 6         | 1.4%    |
| Dell Precision    | 5         | 1.16%   |
| ASUS TUF          | 5         | 1.16%   |
| ASUS ROG          | 5         | 1.16%   |
| ASRock B450       | 5         | 1.16%   |
| Acer Veriton      | 5         | 1.16%   |
| Lenovo MIIX       | 4         | 0.93%   |
| HP Compaq         | 4         | 0.93%   |
| Dell Vostro       | 4         | 0.93%   |
| ASUS ZenBook      | 4         | 0.93%   |
| ASRock B450M      | 4         | 0.93%   |
| HUAWEI BOHB-WAX9  | 3         | 0.7%    |
| HP ProDesk        | 3         | 0.7%    |
| HP EliteBook      | 3         | 0.7%    |
| ASUS P8H61-M      | 3         | 0.7%    |
| ASUS M5A78L-M     | 3         | 0.7%    |
| Acer TravelMate   | 3         | 0.7%    |
| Acer Swift        | 3         | 0.7%    |
| Acer Nitro        | 3         | 0.7%    |
| Valve Jupiter     | 2         | 0.47%   |
| Toshiba Satellite | 2         | 0.47%   |
| Samsung NC208     | 2         | 0.47%   |
| MSI Pro           | 2         | 0.47%   |
| Lenovo ThinkBook  | 2         | 0.47%   |
| Lenovo G460       | 2         | 0.47%   |
| HUAWEI KLVL-WXX9  | 2         | 0.47%   |
| Huanan X79        | 2         | 0.47%   |
| HP Z240           | 2         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 55        | 12.79%  |
| 2020 | 43        | 10%     |
| 2019 | 41        | 9.53%   |
| 2016 | 34        | 7.91%   |
| 2014 | 33        | 7.67%   |
| 2012 | 33        | 7.67%   |
| 2021 | 29        | 6.74%   |
| 2017 | 28        | 6.51%   |
| 2013 | 26        | 6.05%   |
| 2015 | 25        | 5.81%   |
| 2011 | 24        | 5.58%   |
| 2010 | 16        | 3.72%   |
| 2022 | 15        | 3.49%   |
| 2009 | 13        | 3.02%   |
| 2008 | 8         | 1.86%   |
| 2007 | 3         | 0.7%    |
| 2006 | 3         | 0.7%    |
| 2005 | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 221       | 51.4%   |
| Desktop     | 175       | 40.7%   |
| Convertible | 10        | 2.33%   |
| Tablet      | 8         | 1.86%   |
| Mini pc     | 7         | 1.63%   |
| All in one  | 7         | 1.63%   |
| Server      | 2         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 394       | 90.78%  |
| Enabled  | 40        | 9.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 430       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 108       | 24.6%   |
| 16.01-24.0      | 91        | 20.73%  |
| 3.01-4.0        | 84        | 19.13%  |
| 8.01-16.0       | 81        | 18.45%  |
| 32.01-64.0      | 38        | 8.66%   |
| 1.01-2.0        | 19        | 4.33%   |
| 24.01-32.0      | 7         | 1.59%   |
| 64.01-256.0     | 7         | 1.59%   |
| 0.51-1.0        | 2         | 0.46%   |
| More than 256.0 | 1         | 0.23%   |
| 2.01-3.0        | 1         | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 169       | 35.88%  |
| 2.01-3.0   | 140       | 29.72%  |
| 4.01-8.0   | 63        | 13.38%  |
| 3.01-4.0   | 55        | 11.68%  |
| 8.01-16.0  | 18        | 3.82%   |
| 0.51-1.0   | 18        | 3.82%   |
| 16.01-24.0 | 4         | 0.85%   |
| 0.01-0.5   | 3         | 0.64%   |
| 24.01-32.0 | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 254       | 56.57%  |
| 2      | 119       | 26.5%   |
| 3      | 45        | 10.02%  |
| 4      | 13        | 2.9%    |
| 5      | 7         | 1.56%   |
| 0      | 7         | 1.56%   |
| 6      | 2         | 0.45%   |
| 51     | 1         | 0.22%   |
| 32     | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 302       | 69.75%  |
| Yes       | 131       | 30.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 356       | 82.41%  |
| No        | 76        | 17.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 334       | 76.96%  |
| No        | 100       | 23.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 262       | 59.68%  |
| No        | 177       | 40.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Thailand | 430       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangkok           | 171       | 37.5%   |
| Chiang Mai        | 37        | 8.11%   |
| Phuket            | 15        | 3.29%   |
| Khon Kaen         | 15        | 3.29%   |
| Bang Lamung       | 15        | 3.29%   |
| Nonthaburi        | 13        | 2.85%   |
| Nakhon Pathom     | 9         | 1.97%   |
| Surin             | 6         | 1.32%   |
| Surat Thani       | 6         | 1.32%   |
| Songkhla          | 6         | 1.32%   |
| Pattaya           | 6         | 1.32%   |
| Nakhon Ratchasima | 6         | 1.32%   |
| Chon Buri         | 6         | 1.32%   |
| Hua Hin           | 5         | 1.1%    |
| Ban Phan Don      | 5         | 1.1%    |
| Pak Kret          | 4         | 0.88%   |
| Lampang           | 4         | 0.88%   |
| Khlong Luang      | 4         | 0.88%   |
| Suan Luang        | 3         | 0.66%   |
| Si Racha          | 3         | 0.66%   |
| Rayong            | 3         | 0.66%   |
| Phitsanulok       | 3         | 0.66%   |
| Phetchaburi       | 3         | 0.66%   |
| Lat Krabang       | 3         | 0.66%   |
| Bang Khae         | 3         | 0.66%   |
| Bang Bon          | 3         | 0.66%   |
| Ban Yang Sam Ton  | 3         | 0.66%   |
| Ban Du            | 3         | 0.66%   |
| Samut Prakan      | 2         | 0.44%   |
| Salaya            | 2         | 0.44%   |
| Phayao            | 2         | 0.44%   |
| Phan              | 2         | 0.44%   |
| Pattani           | 2         | 0.44%   |
| Pathum Thani      | 2         | 0.44%   |
| Min Buri          | 2         | 0.44%   |
| Maha Sarakham     | 2         | 0.44%   |
| Krabi             | 2         | 0.44%   |
| Kalasin           | 2         | 0.44%   |
| Chiang Rai        | 2         | 0.44%   |
| Chanthaburi       | 2         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 130       | 197    | 20.5%   |
| Seagate                     | 95        | 140    | 14.98%  |
| Samsung Electronics         | 81        | 113    | 12.78%  |
| Toshiba                     | 38        | 86     | 5.99%   |
| Sandisk                     | 36        | 48     | 5.68%   |
| Kingston                    | 33        | 35     | 5.21%   |
| Unknown                     | 29        | 41     | 4.57%   |
| Intel                       | 16        | 17     | 2.52%   |
| Hitachi                     | 13        | 14     | 2.05%   |
| Crucial                     | 12        | 12     | 1.89%   |
| SK hynix                    | 10        | 20     | 1.58%   |
| HGST                        | 10        | 19     | 1.58%   |
| HS-SSD-C100                 | 9         | 15     | 1.42%   |
| Micron Technology           | 8         | 9      | 1.26%   |
| Apacer                      | 8         | 9      | 1.26%   |
| Transcend                   | 6         | 7      | 0.95%   |
| Silicon Motion              | 6         | 8      | 0.95%   |
| China                       | 6         | 6      | 0.95%   |
| Apple                       | 6         | 6      | 0.95%   |
| Phison Electronics          | 5         | 7      | 0.79%   |
| Phison                      | 5         | 10     | 0.79%   |
| Hikvision                   | 5         | 5      | 0.79%   |
| SPCC                        | 4         | 4      | 0.63%   |
| GALAX                       | 4         | 4      | 0.63%   |
| USB3.0                      | 3         | 4      | 0.47%   |
| Plextor                     | 3         | 3      | 0.47%   |
| KingSpec                    | 3         | 5      | 0.47%   |
| JMicron Technology          | 3         | 3      | 0.47%   |
| TO Exter                    | 2         | 2      | 0.32%   |
| Pioneer                     | 2         | 2      | 0.32%   |
| KIOXIA                      | 2         | 4      | 0.32%   |
| Kingmax                     | 2         | 5      | 0.32%   |
| Hewlett-Packard             | 2         | 4      | 0.32%   |
| External                    | 2         | 2      | 0.32%   |
| Corsair                     | 2         | 2      | 0.32%   |
| Colorful                    | 2         | 3      | 0.32%   |
| Acer                        | 2         | 5      | 0.32%   |
| A-DATA Technology           | 2         | 2      | 0.32%   |
| YMTC                        | 1         | 1      | 0.16%   |
| Yangtze Memory Technologies | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 9         | 1.3%    |
| Unknown MMC Card  32GB               | 8         | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB       | 8         | 1.15%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 7         | 1.01%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 7         | 1.01%   |
| Unknown MMC Card  64GB               | 7         | 1.01%   |
| Toshiba MQ04ABF100 1TB               | 6         | 0.87%   |
| Toshiba MQ01ABD100 1TB               | 6         | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB       | 6         | 0.87%   |
| Seagate ST1000DM003-1ER162 1TB       | 6         | 0.87%   |
| Kingston SA400S37240G 240GB SSD      | 6         | 0.87%   |
| Crucial CT500MX500SSD1 500GB         | 6         | 0.87%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 5         | 0.72%   |
| WDC WD10EZEX-00WN4A0 1TB             | 5         | 0.72%   |
| Unknown SD/MMC/MS PRO 64GB           | 5         | 0.72%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 0.72%   |
| SanDisk NVMe SSD Drive 250GB         | 5         | 0.72%   |
| SanDisk NVMe SSD Drive 1TB           | 5         | 0.72%   |
| Kingston SUV400S37120G 120GB SSD     | 5         | 0.72%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 4         | 0.58%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 4         | 0.58%   |
| WDC WD20EZAZ-00GGJB0 2TB             | 4         | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 0.58%   |
| Toshiba DT01ACA100 1TB               | 4         | 0.58%   |
| Seagate ST2000VX008-2E3164 2TB       | 4         | 0.58%   |
| Seagate ST1000LM049-2GH172 1TB       | 4         | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 0.58%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB | 4         | 0.58%   |
| Samsung HD103SJ 1TB                  | 4         | 0.58%   |
| HS-SSD-C100 240G                     | 4         | 0.58%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 3         | 0.43%   |
| WDC WD10SPZX-21Z10T0 1TB             | 3         | 0.43%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 0.43%   |
| WDC WD10EZEX-60WN4A0 1TB             | 3         | 0.43%   |
| WDC WD10EZEX-00MFCA0 1TB             | 3         | 0.43%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB   | 3         | 0.43%   |
| USB3.0 Super Speed 1TB               | 3         | 0.43%   |
| Toshiba MQ01ABF032 320GB             | 3         | 0.43%   |
| SK hynix HFM512GD3JX013N 512GB       | 3         | 0.43%   |
| Seagate ST3500418AS 500GB            | 3         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 94        | 139    | 35.07%  |
| WDC                 | 88        | 131    | 32.84%  |
| Toshiba             | 32        | 78     | 11.94%  |
| Samsung Electronics | 14        | 20     | 5.22%   |
| Hitachi             | 13        | 14     | 4.85%   |
| HGST                | 10        | 19     | 3.73%   |
| Unknown             | 6         | 11     | 2.24%   |
| USB3.0              | 3         | 4      | 1.12%   |
| External            | 2         | 2      | 0.75%   |
| Apple               | 2         | 2      | 0.75%   |
| Pioneer             | 1         | 1      | 0.37%   |
| JMicron Technology  | 1         | 1      | 0.37%   |
| Hewlett-Packard     | 1         | 3      | 0.37%   |
| Fujitsu             | 1         | 2      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 36        | 48     | 19.46%  |
| Samsung Electronics | 28        | 40     | 15.14%  |
| Kingston            | 20        | 21     | 10.81%  |
| SanDisk             | 13        | 19     | 7.03%   |
| Crucial             | 12        | 12     | 6.49%   |
| Apacer              | 8         | 9      | 4.32%   |
| Intel               | 6         | 6      | 3.24%   |
| China               | 6         | 6      | 3.24%   |
| SPCC                | 4         | 4      | 2.16%   |
| Hikvision           | 4         | 4      | 2.16%   |
| GALAX               | 4         | 4      | 2.16%   |
| Apple               | 4         | 4      | 2.16%   |
| Transcend           | 3         | 4      | 1.62%   |
| SK hynix            | 3         | 4      | 1.62%   |
| Plextor             | 3         | 3      | 1.62%   |
| Micron Technology   | 3         | 4      | 1.62%   |
| KingSpec            | 3         | 5      | 1.62%   |
| TO Exter            | 2         | 2      | 1.08%   |
| Kingmax             | 2         | 5      | 1.08%   |
| Acer                | 2         | 5      | 1.08%   |
| WALRAM              | 1         | 1      | 0.54%   |
| Verbatim            | 1         | 1      | 0.54%   |
| Teelkoou            | 1         | 1      | 0.54%   |
| Team                | 1         | 1      | 0.54%   |
| PNY                 | 1         | 2      | 0.54%   |
| Pioneer             | 1         | 1      | 0.54%   |
| OCZ                 | 1         | 1      | 0.54%   |
| LITEON              | 1         | 2      | 0.54%   |
| Lexar               | 1         | 1      | 0.54%   |
| JMicron Technology  | 1         | 1      | 0.54%   |
| Initio              | 1         | 1      | 0.54%   |
| HS-SSD-E100         | 1         | 1      | 0.54%   |
| Hised               | 1         | 1      | 0.54%   |
| Hewlett-Packard     | 1         | 1      | 0.54%   |
| FORESEE             | 1         | 1      | 0.54%   |
| DGM                 | 1         | 1      | 0.54%   |
| Corsair             | 1         | 1      | 0.54%   |
| Colorful            | 1         | 2      | 0.54%   |
| A-DATA Technology   | 1         | 1      | 0.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 221       | 427    | 39.18%  |
| SSD     | 159       | 231    | 28.19%  |
| NVMe    | 145       | 199    | 25.71%  |
| MMC     | 23        | 30     | 4.08%   |
| Unknown | 16        | 22     | 2.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 316       | 646    | 62.08%  |
| NVMe | 145       | 199    | 28.49%  |
| SAS  | 25        | 34     | 4.91%   |
| MMC  | 23        | 30     | 4.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 214       | 328    | 52.32%  |
| 0.51-1.0   | 141       | 195    | 34.47%  |
| 1.01-2.0   | 36        | 44     | 8.8%    |
| 3.01-4.0   | 10        | 57     | 2.44%   |
| 2.01-3.0   | 3         | 8      | 0.73%   |
| 4.01-10.0  | 3         | 15     | 0.73%   |
| 10.01-20.0 | 2         | 11     | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 104       | 22.91%  |
| 251-500        | 95        | 20.93%  |
| 501-1000       | 70        | 15.42%  |
| 1-20           | 42        | 9.25%   |
| 1001-2000      | 37        | 8.15%   |
| 51-100         | 37        | 8.15%   |
| 21-50          | 27        | 5.95%   |
| More than 3000 | 16        | 3.52%   |
| 2001-3000      | 16        | 3.52%   |
| Unknown        | 10        | 2.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 187       | 39.87%  |
| 21-50          | 80        | 17.06%  |
| 101-250        | 57        | 12.15%  |
| 51-100         | 46        | 9.81%   |
| 251-500        | 37        | 7.89%   |
| 501-1000       | 27        | 5.76%   |
| 1001-2000      | 15        | 3.2%    |
| Unknown        | 10        | 2.13%   |
| More than 3000 | 7         | 1.49%   |
| 2001-3000      | 3         | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD2002FAEX-007BA0 2TB                | 2         | 2      | 5.26%   |
| Toshiba MQ01ABD100 1TB                   | 2         | 2      | 5.26%   |
| Seagate ST500DM002-1BD14 500GB           | 2         | 3      | 5.26%   |
| Seagate ST1000LM049-2GH172 1TB           | 2         | 2      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 5.26%   |
| Samsung Electronics SSD 830 Series 128GB | 2         | 2      | 5.26%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1         | 1      | 2.63%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 3      | 2.63%   |
| WDC WD10PURX-64E5EY0 1TB                 | 1         | 1      | 2.63%   |
| WDC WD10EZEX-00WN4A0 1TB                 | 1         | 1      | 2.63%   |
| WDC WD1002FAEX-00Y9A0 1TB                | 1         | 1      | 2.63%   |
| USB3.0 Super Speed 1TB                   | 1         | 2      | 2.63%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 2.63%   |
| Toshiba HDWL110 1TB                      | 1         | 1      | 2.63%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 2.63%   |
| Seagate ST9120822AS 120GB                | 1         | 1      | 2.63%   |
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 2.63%   |
| Seagate ST500LM000-SSHD-8GB              | 1         | 1      | 2.63%   |
| Seagate ST500DM002-1BD142 500GB          | 1         | 1      | 2.63%   |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 1      | 2.63%   |
| Seagate ST3500418AS 500GB                | 1         | 2      | 2.63%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB      | 1         | 1      | 2.63%   |
| Seagate ST1000LM014-1EJ164 1TB           | 1         | 1      | 2.63%   |
| SanDisk SDSSDX240GG25 240GB              | 1         | 1      | 2.63%   |
| Samsung Electronics HM160HI 160GB        | 1         | 2      | 2.63%   |
| Samsung Electronics HD322GJ 320GB        | 1         | 1      | 2.63%   |
| Samsung Electronics HD253GJ 250GB        | 1         | 1      | 2.63%   |
| Samsung Electronics HD103SJ 1TB          | 1         | 1      | 2.63%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD  | 1         | 1      | 2.63%   |
| Intel SSDSC2KF256H6 SATA 256GB           | 1         | 1      | 2.63%   |
| HGST HTS725050A7E630 500GB               | 1         | 1      | 2.63%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 40.54%  |
| WDC                 | 6         | 9      | 16.22%  |
| Samsung Electronics | 6         | 7      | 16.22%  |
| Toshiba             | 4         | 4      | 10.81%  |
| HGST                | 2         | 2      | 5.41%   |
| USB3.0              | 1         | 2      | 2.7%    |
| SanDisk             | 1         | 1      | 2.7%    |
| Kingston            | 1         | 1      | 2.7%    |
| Intel               | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 46.88%  |
| WDC                 | 6         | 9      | 18.75%  |
| Toshiba             | 4         | 4      | 12.5%   |
| Samsung Electronics | 4         | 5      | 12.5%   |
| HGST                | 2         | 2      | 6.25%   |
| USB3.0              | 1         | 2      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 39     | 85.71%  |
| SSD  | 5         | 5      | 14.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB  | 1         | 1      | 50%     |
| Samsung Electronics HD103SJ 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 289       | 558    | 62.02%  |
| Works    | 142       | 305    | 30.47%  |
| Malfunc  | 33        | 44     | 7.08%   |
| Failed   | 2         | 2      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 272       | 50.94%  |
| AMD                          | 82        | 15.36%  |
| Samsung Electronics          | 47        | 8.8%    |
| SanDisk                      | 39        | 7.3%    |
| Kingston Technology Company  | 14        | 2.62%   |
| Phison Electronics           | 11        | 2.06%   |
| Nvidia                       | 11        | 2.06%   |
| ASMedia Technology           | 11        | 2.06%   |
| SK hynix                     | 7         | 1.31%   |
| Silicon Motion               | 7         | 1.31%   |
| Toshiba America Info Systems | 6         | 1.12%   |
| Micron Technology            | 5         | 0.94%   |
| VIA Technologies             | 3         | 0.56%   |
| LSI Logic / Symbios Logic    | 3         | 0.56%   |
| Yangtze Memory Technologies  | 2         | 0.37%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.37%   |
| KIOXIA                       | 2         | 0.37%   |
| Broadcom / LSI               | 2         | 0.37%   |
| ADATA Technology             | 2         | 0.37%   |
| Transcend                    | 1         | 0.19%   |
| Realtek Semiconductor        | 1         | 0.19%   |
| O2 Micro                     | 1         | 0.19%   |
| Micron/Crucial Technology    | 1         | 0.19%   |
| Lite-On Technology           | 1         | 0.19%   |
| JMicron Technology           | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 60        | 9.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 26        | 4.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 24        | 3.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 22        | 3.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 3.14%   |
| AMD 400 Series Chipset SATA Controller                                           | 17        | 2.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 15        | 2.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 2.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 11        | 1.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 10        | 1.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 10        | 1.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 10        | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 9         | 1.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 9         | 1.49%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 9         | 1.49%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 8         | 1.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 8         | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 7         | 1.16%   |
| Intel SSD 660P Series                                                            | 7         | 1.16%   |
| Intel SATA Controller [RAID mode]                                                | 7         | 1.16%   |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 1.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 7         | 1.16%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 6         | 0.99%   |
| SanDisk Non-Volatile memory controller                                           | 6         | 0.99%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 0.99%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 5         | 0.83%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 0.83%   |
| Phison E12 NVMe Controller                                                       | 5         | 0.83%   |
| Micron NVMe Storage Controller                                                   | 5         | 0.83%   |
| Kingston Company Company Non-Volatile memory controller                          | 5         | 0.83%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 5         | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 311       | 57.7%   |
| NVMe | 149       | 27.64%  |
| IDE  | 48        | 8.91%   |
| RAID | 27        | 5.01%   |
| SAS  | 2         | 0.37%   |
| SCSI | 2         | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 323       | 75.12%  |
| AMD          | 106       | 24.65%  |
| CentaurHauls | 1         | 0.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 2.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 1.39%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 6         | 1.39%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.16%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 5         | 1.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.93%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 4         | 0.93%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.93%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 4         | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.93%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 4         | 0.93%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 0.93%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 0.93%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.93%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 4         | 0.93%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.69%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 3         | 0.69%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 0.69%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 0.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.69%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 0.69%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3         | 0.69%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 3         | 0.69%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.69%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.69%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 0.69%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 3         | 0.69%   |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G  | 3         | 0.69%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.46%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 2         | 0.46%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.46%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 2         | 0.46%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.46%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 89        | 20.65%  |
| Intel Core i7           | 86        | 19.95%  |
| Intel Core i3           | 46        | 10.67%  |
| AMD Ryzen 5             | 33        | 7.66%   |
| Other                   | 18        | 4.18%   |
| AMD Ryzen 7             | 18        | 4.18%   |
| Intel Celeron           | 16        | 3.71%   |
| Intel Xeon              | 13        | 3.02%   |
| Intel Pentium           | 13        | 3.02%   |
| Intel Core 2 Duo        | 12        | 2.78%   |
| Intel Atom              | 12        | 2.78%   |
| AMD Ryzen 3             | 8         | 1.86%   |
| AMD Ryzen 9             | 7         | 1.62%   |
| AMD FX                  | 5         | 1.16%   |
| AMD Athlon II X2        | 5         | 1.16%   |
| AMD A4                  | 5         | 1.16%   |
| AMD A10                 | 5         | 1.16%   |
| Intel Core i9           | 4         | 0.93%   |
| Intel Core 2 Quad       | 4         | 0.93%   |
| Intel Pentium Silver    | 3         | 0.7%    |
| Intel Pentium Dual-Core | 3         | 0.7%    |
| Intel Pentium Dual      | 2         | 0.46%   |
| Intel Core m3           | 2         | 0.46%   |
| AMD Ryzen 7 PRO         | 2         | 0.46%   |
| AMD Phenom II X6        | 2         | 0.46%   |
| AMD Phenom II X4        | 2         | 0.46%   |
| AMD Athlon 64 X2        | 2         | 0.46%   |
| AMD Athlon              | 2         | 0.46%   |
| AMD A6                  | 2         | 0.46%   |
| Intel Pentium D         | 1         | 0.23%   |
| Intel Pentium 4         | 1         | 0.23%   |
| CentaurHauls VIA Eden   | 1         | 0.23%   |
| AMD Turion 64 X2 Mobile | 1         | 0.23%   |
| AMD Ryzen 5 PRO         | 1         | 0.23%   |
| AMD Ryzen 3 PRO         | 1         | 0.23%   |
| AMD Phenom II X3        | 1         | 0.23%   |
| AMD E2                  | 1         | 0.23%   |
| AMD E1                  | 1         | 0.23%   |
| AMD A8                  | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 177       | 40.97%  |
| 2      | 154       | 35.65%  |
| 6      | 50        | 11.57%  |
| 8      | 33        | 7.64%   |
| 1      | 5         | 1.16%   |
| 16     | 3         | 0.69%   |
| 12     | 3         | 0.69%   |
| 14     | 2         | 0.46%   |
| 3      | 2         | 0.46%   |
| 40     | 1         | 0.23%   |
| 24     | 1         | 0.23%   |
| 10     | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 425       | 98.84%  |
| 2      | 5         | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 302       | 69.75%  |
| 1      | 131       | 30.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 423       | 98.37%  |
| Unknown        | 6         | 1.4%    |
| 32-bit         | 1         | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 114       | 25.39%  |
| 0x306c3    | 24        | 5.35%   |
| 0x306a9    | 21        | 4.68%   |
| 0x206a7    | 21        | 4.68%   |
| 0x506e3    | 15        | 3.34%   |
| 0x906ea    | 14        | 3.12%   |
| 0x806ea    | 12        | 2.67%   |
| 0x1067a    | 12        | 2.67%   |
| 0x906e9    | 10        | 2.23%   |
| 0x806ec    | 10        | 2.23%   |
| 0x806e9    | 10        | 2.23%   |
| 0x40651    | 9         | 2%      |
| 0x806c1    | 8         | 1.78%   |
| 0x20655    | 8         | 1.78%   |
| 0x406c4    | 7         | 1.56%   |
| 0x406e3    | 6         | 1.34%   |
| 0x406c3    | 6         | 1.34%   |
| 0x0a50000c | 6         | 1.34%   |
| 0x08108102 | 6         | 1.34%   |
| 0x0800820d | 6         | 1.34%   |
| 0x30678    | 5         | 1.11%   |
| 0x08600106 | 5         | 1.11%   |
| 0x0810100b | 5         | 1.11%   |
| 0x706a8    | 4         | 0.89%   |
| 0x706a1    | 4         | 0.89%   |
| 0x20652    | 4         | 0.89%   |
| 0x06001119 | 4         | 0.89%   |
| 0x010000c8 | 4         | 0.89%   |
| 0xa0655    | 3         | 0.67%   |
| 0xa0652    | 3         | 0.67%   |
| 0x906ec    | 3         | 0.67%   |
| 0x906c0    | 3         | 0.67%   |
| 0x6fd      | 3         | 0.67%   |
| 0x406f1    | 3         | 0.67%   |
| 0x106e5    | 3         | 0.67%   |
| 0x106ca    | 3         | 0.67%   |
| 0x08701021 | 3         | 0.67%   |
| 0x08600104 | 3         | 0.67%   |
| 0x08108109 | 3         | 0.67%   |
| 0x08001138 | 3         | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 78        | 18.1%   |
| Haswell          | 47        | 10.9%   |
| IvyBridge        | 31        | 7.19%   |
| Skylake          | 30        | 6.96%   |
| SandyBridge      | 23        | 5.34%   |
| Zen+             | 22        | 5.1%    |
| Silvermont       | 21        | 4.87%   |
| Zen 2            | 20        | 4.64%   |
| Penryn           | 18        | 4.18%   |
| Unknown          | 14        | 3.25%   |
| Westmere         | 13        | 3.02%   |
| CometLake        | 13        | 3.02%   |
| Zen 3            | 12        | 2.78%   |
| Zen              | 11        | 2.55%   |
| TigerLake        | 11        | 2.55%   |
| K10              | 9         | 2.09%   |
| Goldmont plus    | 9         | 2.09%   |
| Piledriver       | 8         | 1.86%   |
| Excavator        | 5         | 1.16%   |
| Core             | 4         | 0.93%   |
| Broadwell        | 4         | 0.93%   |
| Bonnell          | 4         | 0.93%   |
| Tremont          | 3         | 0.7%    |
| Nehalem          | 3         | 0.7%    |
| K8 Hammer        | 3         | 0.7%    |
| IceLake          | 3         | 0.7%    |
| Steamroller      | 2         | 0.46%   |
| Puma             | 2         | 0.46%   |
| NetBurst         | 2         | 0.46%   |
| Goldmont         | 2         | 0.46%   |
| K10 Llano        | 1         | 0.23%   |
| Jaguar           | 1         | 0.23%   |
| Bobcat           | 1         | 0.23%   |
| Alderlake Hybrid | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 241       | 44.46%  |
| Nvidia                     | 177       | 32.66%  |
| AMD                        | 119       | 21.96%  |
| VIA Technologies           | 2         | 0.37%   |
| Matrox Electronics Systems | 1         | 0.18%   |
| ATI Technologies           | 1         | 0.18%   |
| ASPEED Technology          | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 3.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 2.85%   |
| Intel UHD Graphics 620                                                                   | 15        | 2.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 2.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 2.67%   |
| Intel HD Graphics 530                                                                    | 14        | 2.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 2.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 12        | 2.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 1.96%   |
| Intel HD Graphics 620                                                                    | 11        | 1.96%   |
| AMD Renoir                                                                               | 11        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 1.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8         | 1.42%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 1.42%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.25%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 1.07%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 6         | 1.07%   |
| Intel HD Graphics 630                                                                    | 6         | 1.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.07%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6         | 1.07%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.07%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.89%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.89%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5         | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.89%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.89%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 0.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.71%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.71%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.71%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 4         | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 148       | 33.71%  |
| 1 x AMD              | 88        | 20.05%  |
| 1 x Nvidia           | 82        | 18.68%  |
| Intel + Nvidia       | 77        | 17.54%  |
| AMD + Nvidia         | 14        | 3.19%   |
| 2 x AMD              | 10        | 2.28%   |
| Intel + AMD          | 10        | 2.28%   |
| 1 x VIA              | 2         | 0.46%   |
| Intel + 2 x Nvidia   | 2         | 0.46%   |
| 3 x Nvidia           | 1         | 0.23%   |
| 2 x Nvidia           | 1         | 0.23%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.23%   |
| 1 x Matrox           | 1         | 0.23%   |
| 1 x ASPEED           | 1         | 0.23%   |
| AMD + 2 x Nvidia     | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 343       | 77.78%  |
| Proprietary | 87        | 19.73%  |
| Unknown     | 11        | 2.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 240       | 53.57%  |
| 1.01-2.0   | 60        | 13.39%  |
| 3.01-4.0   | 45        | 10.04%  |
| 0.01-0.5   | 43        | 9.6%    |
| 0.51-1.0   | 30        | 6.7%    |
| 7.01-8.0   | 16        | 3.57%   |
| 5.01-6.0   | 9         | 2.01%   |
| 8.01-16.0  | 2         | 0.45%   |
| 4.01-5.0   | 1         | 0.22%   |
| 2.01-3.0   | 1         | 0.22%   |
| 16.01-24.0 | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 66        | 14.1%   |
| AU Optronics            | 58        | 12.39%  |
| Chimei Innolux          | 41        | 8.76%   |
| BOE                     | 38        | 8.12%   |
| Acer                    | 35        | 7.48%   |
| Goldstar                | 34        | 7.26%   |
| LG Display              | 32        | 6.84%   |
| Dell                    | 26        | 5.56%   |
| Hewlett-Packard         | 16        | 3.42%   |
| AOC                     | 14        | 2.99%   |
| PANDA                   | 9         | 1.92%   |
| Lenovo                  | 9         | 1.92%   |
| Sharp                   | 8         | 1.71%   |
| Apple                   | 8         | 1.71%   |
| BenQ                    | 7         | 1.5%    |
| ViewSonic               | 6         | 1.28%   |
| LG Electronics          | 5         | 1.07%   |
| Philips                 | 3         | 0.64%   |
| InfoVision              | 3         | 0.64%   |
| Chi Mei Optoelectronics | 3         | 0.64%   |
| ASUSTek Computer        | 3         | 0.64%   |
| Valve                   | 2         | 0.43%   |
| Unknown (XXX)           | 2         | 0.43%   |
| SKY                     | 2         | 0.43%   |
| MStar                   | 2         | 0.43%   |
| MSI                     | 2         | 0.43%   |
| Microstep               | 2         | 0.43%   |
| Mi                      | 2         | 0.43%   |
| Fujitsu                 | 2         | 0.43%   |
| CSO                     | 2         | 0.43%   |
| Ancor Communications    | 2         | 0.43%   |
| Toshiba                 | 1         | 0.21%   |
| TCL                     | 1         | 0.21%   |
| Sony                    | 1         | 0.21%   |
| SGT                     | 1         | 0.21%   |
| Seiko/Epson             | 1         | 0.21%   |
| RTK                     | 1         | 0.21%   |
| Quanta Display          | 1         | 0.21%   |
| Panasonic               | 1         | 0.21%   |
| NEC Computers           | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 5         | 1.04%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 4         | 0.83%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 4         | 0.83%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 440x250mm 19.9-inch      | 3         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.62%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.62%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 3         | 0.62%   |
| AOC 2381 AOC2381 1920x1080 509x286mm 23.0-inch                        | 3         | 0.62%   |
| Acer k222HQL ACR0512 1920x1080 480x270mm 21.7-inch                    | 3         | 0.62%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                | 2         | 0.42%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.42%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch  | 2         | 0.42%   |
| Samsung Electronics SyncMaster SAM0366 1280x1024 338x270mm 17.0-inch  | 2         | 0.42%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch      | 2         | 0.42%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2         | 0.42%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 0.42%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2         | 0.42%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 2         | 0.42%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.42%   |
| Philips 236V4 PHLC0B3 1920x1080 510x287mm 23.0-inch                   | 2         | 0.42%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 2         | 0.42%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2         | 0.42%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 2         | 0.42%   |
| LG Display LCD Monitor LGD0454 1366x768 310x174mm 14.0-inch           | 2         | 0.42%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 2         | 0.42%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 2         | 0.42%   |
| Lenovo AIO PC LEN2000 1920x1080 510x290mm 23.1-inch                   | 2         | 0.42%   |
| Hewlett-Packard Z24n HWP320E 1920x1200 518x324mm 24.1-inch            | 2         | 0.42%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 2         | 0.42%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.42%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2         | 0.42%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.42%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                      | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 205       | 45.35%  |
| 1366x768 (WXGA)    | 99        | 21.9%   |
| 3840x2160 (4K)     | 27        | 5.97%   |
| 1600x900 (HD+)     | 23        | 5.09%   |
| 2560x1440 (QHD)    | 15        | 3.32%   |
| 1440x900 (WXGA+)   | 14        | 3.1%    |
| 1280x1024 (SXGA)   | 9         | 1.99%   |
| 1680x1050 (WSXGA+) | 8         | 1.77%   |
| 2560x1080          | 7         | 1.55%   |
| Unknown            | 6         | 1.33%   |
| 1360x768           | 5         | 1.11%   |
| 2560x1600          | 4         | 0.88%   |
| 1920x1200 (WUXGA)  | 4         | 0.88%   |
| 1280x800 (WXGA)    | 3         | 0.66%   |
| 800x1280           | 2         | 0.44%   |
| 3840x2400          | 2         | 0.44%   |
| 3840x1080          | 2         | 0.44%   |
| 3440x1440          | 2         | 0.44%   |
| 2160x1440          | 2         | 0.44%   |
| 1600x1200          | 2         | 0.44%   |
| 5120x1440          | 1         | 0.22%   |
| 3520x1080          | 1         | 0.22%   |
| 2880x1800          | 1         | 0.22%   |
| 2736x1824          | 1         | 0.22%   |
| 2732x768           | 1         | 0.22%   |
| 2256x1504          | 1         | 0.22%   |
| 1920x515           | 1         | 0.22%   |
| 1920x1280          | 1         | 0.22%   |
| 1280x720 (HD)      | 1         | 0.22%   |
| 1024x768 (XGA)     | 1         | 0.22%   |
| 1024x600           | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 94        | 20.09%  |
| 14      | 48        | 10.26%  |
| 13      | 43        | 9.19%   |
| 23      | 37        | 7.91%   |
| 24      | 30        | 6.41%   |
| 21      | 30        | 6.41%   |
| Unknown | 26        | 5.56%   |
| 27      | 24        | 5.13%   |
| 18      | 21        | 4.49%   |
| 19      | 17        | 3.63%   |
| 17      | 17        | 3.63%   |
| 20      | 16        | 3.42%   |
| 11      | 13        | 2.78%   |
| 34      | 7         | 1.5%    |
| 22      | 6         | 1.28%   |
| 31      | 5         | 1.07%   |
| 16      | 5         | 1.07%   |
| 12      | 5         | 1.07%   |
| 84      | 4         | 0.85%   |
| 72      | 2         | 0.43%   |
| 54      | 2         | 0.43%   |
| 52      | 2         | 0.43%   |
| 47      | 2         | 0.43%   |
| 26      | 2         | 0.43%   |
| 7       | 2         | 0.43%   |
| 60      | 1         | 0.21%   |
| 46      | 1         | 0.21%   |
| 40      | 1         | 0.21%   |
| 39      | 1         | 0.21%   |
| 32      | 1         | 0.21%   |
| 29      | 1         | 0.21%   |
| 10      | 1         | 0.21%   |
| 8       | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 170       | 37.12%  |
| 501-600     | 86        | 18.78%  |
| 401-500     | 86        | 18.78%  |
| 201-300     | 40        | 8.73%   |
| Unknown     | 26        | 5.68%   |
| 351-400     | 18        | 3.93%   |
| 701-800     | 8         | 1.75%   |
| 1001-1500   | 8         | 1.75%   |
| 601-700     | 6         | 1.31%   |
| 1501-2000   | 5         | 1.09%   |
| 801-900     | 2         | 0.44%   |
| 1-100       | 2         | 0.44%   |
| 101-200     | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 331       | 78.62%  |
| 16/10   | 41        | 9.74%   |
| Unknown | 22        | 5.23%   |
| 5/4     | 9         | 2.14%   |
| 21/9    | 7         | 1.66%   |
| 3/2     | 6         | 1.43%   |
| 4/3     | 2         | 0.48%   |
| 0.67    | 2         | 0.48%   |
| 3.73    | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 94        | 20.22%  |
| 201-250        | 84        | 18.06%  |
| 81-90          | 75        | 16.13%  |
| 151-200        | 42        | 9.03%   |
| 301-350        | 26        | 5.59%   |
| Unknown        | 26        | 5.59%   |
| 141-150        | 22        | 4.73%   |
| 71-80          | 16        | 3.44%   |
| 51-60          | 14        | 3.01%   |
| 351-500        | 14        | 3.01%   |
| 121-130        | 12        | 2.58%   |
| More than 1000 | 10        | 2.15%   |
| 251-300        | 10        | 2.15%   |
| 61-70          | 5         | 1.08%   |
| 501-1000       | 5         | 1.08%   |
| 1-40           | 3         | 0.65%   |
| 131-140        | 3         | 0.65%   |
| 111-120        | 3         | 0.65%   |
| 91-100         | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 145       | 32.37%  |
| 121-160       | 115       | 25.67%  |
| 101-120       | 110       | 24.55%  |
| 161-240       | 35        | 7.81%   |
| Unknown       | 26        | 5.8%    |
| 1-50          | 9         | 2.01%   |
| More than 240 | 8         | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 352       | 79.1%   |
| 2     | 69        | 15.51%  |
| 0     | 17        | 3.82%   |
| 3     | 7         | 1.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 261       | 39.43%  |
| Intel                             | 182       | 27.49%  |
| Qualcomm Atheros                  | 80        | 12.08%  |
| Broadcom                          | 40        | 6.04%   |
| Ralink Technology                 | 14        | 2.11%   |
| MediaTek                          | 11        | 1.66%   |
| ASIX Electronics                  | 9         | 1.36%   |
| TP-Link                           | 8         | 1.21%   |
| D-Link                            | 8         | 1.21%   |
| Nvidia                            | 7         | 1.06%   |
| Broadcom Limited                  | 5         | 0.76%   |
| Ralink                            | 4         | 0.6%    |
| D-Link System                     | 4         | 0.6%    |
| Xiaomi                            | 3         | 0.45%   |
| Samsung Electronics               | 3         | 0.45%   |
| ASUSTek Computer                  | 3         | 0.45%   |
| VIA Technologies                  | 2         | 0.3%    |
| Mercucys                          | 2         | 0.3%    |
| Marvell Technology Group          | 2         | 0.3%    |
| Huawei Technologies               | 2         | 0.3%    |
| Ericsson Business Mobile Networks | 2         | 0.3%    |
| Qualcomm Atheros Communications   | 1         | 0.15%   |
| Qualcomm                          | 1         | 0.15%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.15%   |
| Lenovo                            | 1         | 0.15%   |
| JMicron Technology                | 1         | 0.15%   |
| Edimax Technology                 | 1         | 0.15%   |
| BUFFALO                           | 1         | 0.15%   |
| Aquantia                          | 1         | 0.15%   |
| Android                           | 1         | 0.15%   |
| Adafruit                          | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 201       | 26.91%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 2.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 2.14%   |
| Intel Wi-Fi 6 AX200                                               | 16        | 2.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.2%    |
| Intel Wireless-AC 9260                                            | 9         | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 1.2%    |
| Intel Wireless 8265 / 8275                                        | 8         | 1.07%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.07%   |
| Intel Ethernet Connection (2) I219-V                              | 8         | 1.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 1.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 0.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 0.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 0.94%   |
| Intel Wireless 8260                                               | 7         | 0.94%   |
| Intel Wireless 7265                                               | 7         | 0.94%   |
| Intel Wireless 3160                                               | 7         | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.94%   |
| Ralink MT7601U Wireless Adapter                                   | 6         | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.8%    |
| Intel I211 Gigabit Network Connection                             | 6         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.67%   |
| Intel Wireless 3165                                               | 5         | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 0.67%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 4         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 137       | 38.48%  |
| Qualcomm Atheros                | 69        | 19.38%  |
| Realtek Semiconductor           | 63        | 17.7%   |
| Broadcom                        | 26        | 7.3%    |
| Ralink Technology               | 14        | 3.93%   |
| MediaTek                        | 11        | 3.09%   |
| D-Link                          | 8         | 2.25%   |
| TP-Link                         | 7         | 1.97%   |
| Broadcom Limited                | 5         | 1.4%    |
| Ralink                          | 4         | 1.12%   |
| ASUSTek Computer                | 3         | 0.84%   |
| Mercucys                        | 2         | 0.56%   |
| D-Link System                   | 2         | 0.56%   |
| Qualcomm Atheros Communications | 1         | 0.28%   |
| Qualcomm                        | 1         | 0.28%   |
| Marvell Technology Group        | 1         | 0.28%   |
| Edimax Technology               | 1         | 0.28%   |
| BUFFALO                         | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 22        | 6.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 16        | 4.47%   |
| Intel Wi-Fi 6 AX200                                            | 16        | 4.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 13        | 3.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 3.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 2.51%   |
| Intel Wireless-AC 9260                                         | 9         | 2.51%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 2.51%   |
| Intel Wireless 8265 / 8275                                     | 8         | 2.23%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 2.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 8         | 2.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7         | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 1.96%   |
| Intel Wireless 8260                                            | 7         | 1.96%   |
| Intel Wireless 7265                                            | 7         | 1.96%   |
| Intel Wireless 3160                                            | 7         | 1.96%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.68%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 1.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 1.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 1.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.4%    |
| Intel Wireless 3165                                            | 5         | 1.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.4%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 1.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 1.4%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 4         | 1.12%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 4         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 1.12%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 1.12%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.12%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]  | 4         | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 0.84%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 0.84%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 233       | 62.13%  |
| Intel                         | 75        | 20%     |
| Broadcom                      | 19        | 5.07%   |
| Qualcomm Atheros              | 16        | 4.27%   |
| ASIX Electronics              | 9         | 2.4%    |
| Nvidia                        | 7         | 1.87%   |
| Xiaomi                        | 3         | 0.8%    |
| VIA Technologies              | 2         | 0.53%   |
| Samsung Electronics           | 2         | 0.53%   |
| D-Link System                 | 2         | 0.53%   |
| TP-Link                       | 1         | 0.27%   |
| OnePlus Technology (Shenzhen) | 1         | 0.27%   |
| Marvell Technology Group      | 1         | 0.27%   |
| Lenovo                        | 1         | 0.27%   |
| JMicron Technology            | 1         | 0.27%   |
| Huawei Technologies           | 1         | 0.27%   |
| Aquantia                      | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 201       | 52.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 3.13%   |
| Intel Ethernet Connection (2) I219-V                              | 8         | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.83%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.83%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.83%   |
| Intel I211 Gigabit Network Connection                             | 6         | 1.57%   |
| Intel Ethernet Connection I217-V                                  | 5         | 1.31%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 1.31%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.78%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.78%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.52%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.52%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.52%   |
| Nvidia MCP73 Ethernet                                             | 2         | 0.52%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.52%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.52%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.52%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.52%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.52%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.52%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 2         | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.52%   |
| Xiaomi 100Mbps Network Card Adapter                               | 1         | 0.26%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1         | 0.26%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 355       | 51.08%  |
| WiFi     | 334       | 48.06%  |
| Modem    | 5         | 0.72%   |
| Unknown  | 1         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 283       | 63.45%  |
| Ethernet | 163       | 36.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 219       | 50.34%  |
| 1     | 201       | 46.21%  |
| 0     | 8         | 1.84%   |
| 3     | 4         | 0.92%   |
| 4     | 2         | 0.46%   |
| 5     | 1         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 338       | 75.78%  |
| Yes  | 108       | 24.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 110       | 41.04%  |
| Cambridge Silicon Radio         | 25        | 9.33%   |
| IMC Networks                    | 24        | 8.96%   |
| Lite-On Technology              | 20        | 7.46%   |
| Realtek Semiconductor           | 18        | 6.72%   |
| Qualcomm Atheros Communications | 14        | 5.22%   |
| Broadcom                        | 11        | 4.1%    |
| Apple                           | 11        | 4.1%    |
| Foxconn / Hon Hai               | 7         | 2.61%   |
| MediaTek                        | 5         | 1.87%   |
| Dell                            | 4         | 1.49%   |
| ASUSTek Computer                | 4         | 1.49%   |
| Toshiba                         | 3         | 1.12%   |
| Realtek                         | 3         | 1.12%   |
| Foxconn International           | 3         | 1.12%   |
| Hewlett-Packard                 | 2         | 0.75%   |
| USI                             | 1         | 0.37%   |
| Ralink                          | 1         | 0.37%   |
| Marvell Semiconductor           | 1         | 0.37%   |
| Askey Computer                  | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 38        | 14.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 25        | 9.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 22        | 8.21%   |
| Intel AX201 Bluetooth                               | 18        | 6.72%   |
| Intel AX200 Bluetooth                               | 13        | 4.85%   |
| IMC Networks Bluetooth Device                       | 10        | 3.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 3.36%   |
| IMC Networks Bluetooth Radio                        | 9         | 3.36%   |
| Realtek Bluetooth Radio                             | 8         | 2.99%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 2.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 2.61%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 2.24%   |
| MediaTek Wireless_Device                            | 5         | 1.87%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.87%   |
| Lite-On Bluetooth Device                            | 4         | 1.49%   |
| Intel Bluetooth Device                              | 4         | 1.49%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.49%   |
| Apple Bluetooth Host Controller                     | 4         | 1.49%   |
| Realtek Bluetooth Radio                             | 3         | 1.12%   |
| Intel AX210 Bluetooth                               | 3         | 1.12%   |
| IMC Networks Wireless_Device                        | 3         | 1.12%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.12%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.12%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.75%   |
| Lite-On Wireless_Device                             | 2         | 0.75%   |
| Lite-On Bluetooth Radio                             | 2         | 0.75%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.75%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.75%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.75%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.75%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.75%   |
| USI Bluetooth Device                                | 1         | 0.37%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.37%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.37%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 306       | 50.25%  |
| AMD                                          | 131       | 21.51%  |
| Nvidia                                       | 117       | 19.21%  |
| C-Media Electronics                          | 11        | 1.81%   |
| JMTek                                        | 8         | 1.31%   |
| Razer USA                                    | 5         | 0.82%   |
| VIA Technologies                             | 2         | 0.33%   |
| SAVITECH                                     | 2         | 0.33%   |
| Samson Technologies                          | 2         | 0.33%   |
| Generalplus Technology                       | 2         | 0.33%   |
| Elan Microelectronics                        | 2         | 0.33%   |
| Earth Computer Technologies                  | 2         | 0.33%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.16%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.16%   |
| Texas Instruments                            | 1         | 0.16%   |
| Samsung Electronics                          | 1         | 0.16%   |
| Nordic Semiconductor ASA                     | 1         | 0.16%   |
| Lenovo                                       | 1         | 0.16%   |
| Kingston Technology                          | 1         | 0.16%   |
| Huawei Technologies                          | 1         | 0.16%   |
| ESS Technology                               | 1         | 0.16%   |
| Dell                                         | 1         | 0.16%   |
| DCMT Technology                              | 1         | 0.16%   |
| Creative Technology                          | 1         | 0.16%   |
| Creative Labs                                | 1         | 0.16%   |
| Cayin                                        | 1         | 0.16%   |
| BlueTrm                                      | 1         | 0.16%   |
| Blue Microphones                             | 1         | 0.16%   |
| Barco Display Systems                        | 1         | 0.16%   |
| Audient                                      | 1         | 0.16%   |
| ASUSTek Computer                             | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 50        | 6.76%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 34        | 4.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 30        | 4.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 27        | 3.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 25        | 3.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 24        | 3.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 23        | 3.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 22        | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 2.7%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 15        | 2.03%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 2.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 1.89%   |
| Intel 200 Series PCH HD Audio                                                                     | 13        | 1.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 12        | 1.62%   |
| Nvidia High Definition Audio Controller                                                           | 11        | 1.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 1.49%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 11        | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 10        | 1.35%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 9         | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.22%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 1.08%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 1.08%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 7         | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 0.95%   |
| JMTek USB PnP Audio Device                                                                        | 7         | 0.95%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 6         | 0.81%   |
| AMD Navi 10 HDMI Audio                                                                            | 6         | 0.81%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 5         | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.68%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 5         | 0.68%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 55        | 23.01%  |
| Kingston            | 55        | 23.01%  |
| SK hynix            | 41        | 17.15%  |
| Micron Technology   | 26        | 10.88%  |
| Unknown             | 19        | 7.95%   |
| Corsair             | 10        | 4.18%   |
| Transcend           | 5         | 2.09%   |
| Crucial             | 5         | 2.09%   |
| Elpida              | 4         | 1.67%   |
| G.Skill             | 3         | 1.26%   |
| A-DATA Technology   | 3         | 1.26%   |
| Unknown (ABCD)      | 2         | 0.84%   |
| Team                | 2         | 0.84%   |
| Ramaxel Technology  | 2         | 0.84%   |
| Unknown (0x02BA)    | 1         | 0.42%   |
| Unknown (08B5)      | 1         | 0.42%   |
| Nanya Technology    | 1         | 0.42%   |
| Lexar               | 1         | 0.42%   |
| ASint Technology    | 1         | 0.42%   |
| Apacer              | 1         | 0.42%   |
| Unknown             | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 5         | 1.96%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 5         | 1.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 1.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 4         | 1.57%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3         | 1.18%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 1.18%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 3         | 1.18%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 3         | 1.18%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 1.18%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                    | 2         | 0.78%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 2         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                    | 2         | 0.78%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s           | 2         | 0.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 2         | 0.78%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 2         | 0.78%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 2         | 0.78%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 2         | 0.78%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                    | 2         | 0.78%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.78%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.78%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s                 | 2         | 0.78%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 2         | 0.78%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Micron RAM MT40A512M16LY-075:E 4GB SODIMM DDR4 3200MT/s        | 2         | 0.78%   |
| Micron RAM Module 4096MB SODIMM DDR4 2400MT/s                  | 2         | 0.78%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s          | 2         | 0.78%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s                 | 2         | 0.78%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 2         | 0.78%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s            | 2         | 0.78%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s           | 2         | 0.78%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 2         | 0.78%   |
| Kingston RAM 99U5471-001.A01LF 2GB DIMM DDR3 1333MT/s          | 2         | 0.78%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s        | 2         | 0.78%   |
| Crucial RAM CT16G4SFD824A.C16FBR 16GB SODIMM DDR4 2400MT/s     | 2         | 0.78%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                    | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 97        | 48.02%  |
| DDR3    | 68        | 33.66%  |
| LPDDR4  | 14        | 6.93%   |
| SDRAM   | 6         | 2.97%   |
| LPDDR3  | 4         | 1.98%   |
| DDR5    | 4         | 1.98%   |
| Unknown | 4         | 1.98%   |
| DDR2    | 2         | 0.99%   |
| DDR     | 2         | 0.99%   |
| LPDDR5  | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 114       | 57.58%  |
| DIMM         | 65        | 32.83%  |
| Row Of Chips | 17        | 8.59%   |
| RIMM         | 1         | 0.51%   |
| FB-DIMM      | 1         | 0.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 82        | 39.05%  |
| 4096  | 68        | 32.38%  |
| 16384 | 26        | 12.38%  |
| 2048  | 26        | 12.38%  |
| 32768 | 4         | 1.9%    |
| 1024  | 4         | 1.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 48        | 21.72%  |
| 3200    | 29        | 13.12%  |
| 2667    | 27        | 12.22%  |
| 1333    | 21        | 9.5%    |
| 2400    | 19        | 8.6%    |
| 2133    | 14        | 6.33%   |
| 3600    | 6         | 2.71%   |
| 4267    | 5         | 2.26%   |
| 3266    | 5         | 2.26%   |
| 1867    | 5         | 2.26%   |
| 1334    | 5         | 2.26%   |
| 1067    | 4         | 1.81%   |
| 4800    | 3         | 1.36%   |
| 3400    | 3         | 1.36%   |
| 1866    | 3         | 1.36%   |
| 4266    | 2         | 0.9%    |
| 3733    | 2         | 0.9%    |
| 3466    | 2         | 0.9%    |
| 3151    | 2         | 0.9%    |
| 3000    | 2         | 0.9%    |
| 2666    | 2         | 0.9%    |
| 667     | 2         | 0.9%    |
| 8400    | 1         | 0.45%   |
| 6400    | 1         | 0.45%   |
| 5600    | 1         | 0.45%   |
| 4199    | 1         | 0.45%   |
| 3534    | 1         | 0.45%   |
| 3333    | 1         | 0.45%   |
| 2800    | 1         | 0.45%   |
| 800     | 1         | 0.45%   |
| 533     | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 5         | 38.46%  |
| Seiko Epson         | 3         | 23.08%  |
| Canon               | 2         | 15.38%  |
| STMicroelectronics  | 1         | 7.69%   |
| Samsung Electronics | 1         | 7.69%   |
| Pantum              | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| STMicroelectronics USB Printer P | 1         | 7.69%   |
| Seiko Epson ME-100 Series        | 1         | 7.69%   |
| Seiko Epson LQ-310               | 1         | 7.69%   |
| Seiko Epson L220 Series          | 1         | 7.69%   |
| Samsung SCX-4300 Series          | 1         | 7.69%   |
| Pantum P2500W series             | 1         | 7.69%   |
| Canon PIXMA MP280                | 1         | 7.69%   |
| Canon E4200 series               | 1         | 7.69%   |
| Brother HL-1110 series           | 1         | 7.69%   |
| Brother DCP-T510W                | 1         | 7.69%   |
| Brother DCP-T300                 | 1         | 7.69%   |
| Brother DCP-L3551CDW             | 1         | 7.69%   |
| Brother DCP-1510                 | 1         | 7.69%   |

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


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 56        | 23.14%  |
| IMC Networks                           | 32        | 13.22%  |
| Bison Electronics                      | 22        | 9.09%   |
| Realtek Semiconductor                  | 20        | 8.26%   |
| Microdia                               | 18        | 7.44%   |
| Quanta                                 | 15        | 6.2%    |
| Logitech                               | 11        | 4.55%   |
| Acer                                   | 9         | 3.72%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.31%   |
| Sunplus Innovation Technology          | 7         | 2.89%   |
| Apple                                  | 6         | 2.48%   |
| Lite-On Technology                     | 5         | 2.07%   |
| Suyin                                  | 4         | 1.65%   |
| Generalplus Technology                 | 4         | 1.65%   |
| Aveo Technology                        | 4         | 1.65%   |
| Syntek                                 | 3         | 1.24%   |
| Silicon Motion                         | 3         | 1.24%   |
| Microsoft                              | 3         | 1.24%   |
| Samsung Electronics                    | 2         | 0.83%   |
| Z-Star Microelectronics                | 1         | 0.41%   |
| WCM_USB                                | 1         | 0.41%   |
| Sony Electronics                       | 1         | 0.41%   |
| Sonix Technology                       | 1         | 0.41%   |
| Razer USA                              | 1         | 0.41%   |
| Owon                                   | 1         | 0.41%   |
| Luxvisions Innotech Limited            | 1         | 0.41%   |
| Lenovo                                 | 1         | 0.41%   |
| icSpring                               | 1         | 0.41%   |
| Alcor Micro                            | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam       | 12        | 4.94%   |
| Chicony HD WebCam                       | 11        | 4.53%   |
| Chicony Integrated Camera               | 10        | 4.12%   |
| Bison Integrated Camera                 | 7         | 2.88%   |
| Microdia Integrated_Webcam_HD           | 6         | 2.47%   |
| Chicony HP Truevision HD camera         | 6         | 2.47%   |
| Realtek Integrated_Webcam_HD            | 5         | 2.06%   |
| Realtek HD WebCam                       | 4         | 1.65%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 4         | 1.65%   |
| IMC Networks Integrated Camera          | 4         | 1.65%   |
| Chicony Lenovo EasyCamera               | 4         | 1.65%   |
| Chicony HD User Facing                  | 4         | 1.65%   |
| Bison SunplusIT Integrated Camera       | 4         | 1.65%   |
| Silicon Motion WebCam SCB-0385N         | 3         | 1.23%   |
| Microdia CameraA                        | 3         | 1.23%   |
| Microdia Camera                         | 3         | 1.23%   |
| Lite-On HP Wide Vision HD Camera        | 3         | 1.23%   |
| Generalplus GENERAL WEBCAM              | 3         | 1.23%   |
| Chicony HP Wide Vision HD Camera        | 3         | 1.23%   |
| Bison ThinkPad Integrated Camera        | 3         | 1.23%   |
| Aveo USB2.0 Camera                      | 3         | 1.23%   |
| Apple Built-in iSight                   | 3         | 1.23%   |
| Acer Lenovo EasyCamera                  | 3         | 1.23%   |
| Syntek Integrated Camera                | 2         | 0.82%   |
| Sunplus Integrated_Webcam_HD            | 2         | 0.82%   |
| Samsung Galaxy series, misc. (MTP mode) | 2         | 0.82%   |
| Realtek USB2.0 HD UVC WebCam            | 2         | 0.82%   |
| Realtek Integrated Webcam               | 2         | 0.82%   |
| Quanta VGA WebCam                       | 2         | 0.82%   |
| Quanta USB2.0 HD UVC WebCam             | 2         | 0.82%   |
| Quanta ov9734_techfront_camera          | 2         | 0.82%   |
| Quanta HD Webcam                        | 2         | 0.82%   |
| Quanta HD User Facing                   | 2         | 0.82%   |
| Quanta HD Camera                        | 2         | 0.82%   |
| Microsoft MicrosoftÂ LifeCam Cinema    | 2         | 0.82%   |
| Microdia Integrated Webcam              | 2         | 0.82%   |
| Logitech Webcam C310                    | 2         | 0.82%   |
| Logitech Webcam C270                    | 2         | 0.82%   |
| Logitech HD Pro Webcam C920             | 2         | 0.82%   |
| IMC Networks VGA UVC WebCam             | 2         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 14        | 31.11%  |
| Shenzhen Goodix Technology | 12        | 26.67%  |
| Validity Sensors           | 5         | 11.11%  |
| LighTuning Technology      | 5         | 11.11%  |
| Elan Microelectronics      | 5         | 11.11%  |
| Upek                       | 2         | 4.44%   |
| AuthenTec                  | 2         | 4.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                       | 6         | 13.33%  |
| Shenzhen Goodix  Fingerprint Device                      | 5         | 11.11%  |
| Synaptics WBDI                                           | 4         | 8.89%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 3         | 6.67%   |
| Elan ELAN:Fingerprint                                    | 3         | 6.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 2         | 4.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 2         | 4.44%   |
| Synaptics  WBDI                                          | 2         | 4.44%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 2         | 4.44%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 2         | 4.44%   |
| Elan ELAN:ARM-M4                                         | 2         | 4.44%   |
| Validity Sensors VFS101 Fingerprint Reader               | 1         | 2.22%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 2.22%   |
| Validity Sensors Synaptics WBDI                          | 1         | 2.22%   |
| Synaptics WBDI Fingerprint Reader USB 086                | 1         | 2.22%   |
| Synaptics UWP WBDI Device                                | 1         | 2.22%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 2.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 2.22%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.22%   |
| Shenzhen Goodix FingerPrint                              | 1         | 2.22%   |
| LighTuning Fingerprint Sensor                            | 1         | 2.22%   |
| AuthenTec AES2810                                        | 1         | 2.22%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 2.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 3         | 37.5%   |
| O2 Micro              | 2         | 25%     |
| Broadcom              | 2         | 25%     |
| Gemalto (was Gemplus) | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 37.5%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 25%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom 58200                                                               | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 316       | 71.98%  |
| 1     | 100       | 22.78%  |
| 2     | 19        | 4.33%   |
| 3     | 2         | 0.46%   |
| 7     | 1         | 0.23%   |
| 5     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 29.25%  |
| Graphics card            | 33        | 22.45%  |
| Net/wireless             | 18        | 12.24%  |
| Multimedia controller    | 17        | 11.56%  |
| Chipcard                 | 8         | 5.44%   |
| Communication controller | 7         | 4.76%   |
| Sound                    | 6         | 4.08%   |
| Unassigned class         | 3         | 2.04%   |
| Camera                   | 3         | 2.04%   |
| Bluetooth                | 3         | 2.04%   |
| Wireless                 | 1         | 0.68%   |
| Storage/ide              | 1         | 0.68%   |
| Network                  | 1         | 0.68%   |
| Net/ethernet             | 1         | 0.68%   |
| Flash memory             | 1         | 0.68%   |
| Card reader              | 1         | 0.68%   |

