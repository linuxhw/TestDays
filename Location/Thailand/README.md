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

Total: 613

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 60        | 13.57%  |
| Ubuntu 18.04                 | 34        | 7.69%   |
| Ubuntu 22.04                 | 20        | 4.52%   |
| OpenMandriva 4.2             | 16        | 3.62%   |
| Pop!_OS 22.04                | 14        | 3.17%   |
| KDE neon 20.04               | 12        | 2.71%   |
| Debian 11                    | 12        | 2.71%   |
| Arch Rolling                 | 12        | 2.71%   |
| OpenMandriva 4.3             | 11        | 2.49%   |
| Fedora 37                    | 11        | 2.49%   |
| OpenMandriva 23.01           | 9         | 2.04%   |
| Linux Mint 21                | 8         | 1.81%   |
| Zorin 15                     | 7         | 1.58%   |
| Arch                         | 7         | 1.58%   |
| Ubuntu 19.10                 | 6         | 1.36%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 1.36%   |
| Manjaro                      | 6         | 1.36%   |
| Linux Mint 20.2              | 6         | 1.36%   |
| Zorin 16                     | 5         | 1.13%   |
| Xubuntu 20.04                | 5         | 1.13%   |
| Ubuntu 19.04                 | 5         | 1.13%   |
| Linux Mint 20.3              | 5         | 1.13%   |
| Kubuntu 22.04                | 5         | 1.13%   |
| Fedora 36                    | 5         | 1.13%   |
| Debian Testing               | 5         | 1.13%   |
| Debian 10                    | 5         | 1.13%   |
| Ubuntu 16.04                 | 4         | 0.9%    |
| Pop!_OS 21.04                | 4         | 0.9%    |
| Linux Mint 19.3              | 4         | 0.9%    |
| Linux Mint 19.2              | 4         | 0.9%    |
| KDE neon 22.04               | 4         | 0.9%    |
| Fedora 35                    | 4         | 0.9%    |
| Fedora 33                    | 4         | 0.9%    |
| Xubuntu 18.04                | 3         | 0.68%   |
| Ubuntu 22.10                 | 3         | 0.68%   |
| Ubuntu 21.10                 | 3         | 0.68%   |
| Ubuntu 18.10                 | 3         | 0.68%   |
| Pop!_OS 20.04                | 3         | 0.68%   |
| Linux Mint 20                | 3         | 0.68%   |
| Kubuntu 20.04                | 3         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 135       | 31.76%  |
| OpenMandriva  | 38        | 8.94%   |
| Linux Mint    | 33        | 7.76%   |
| Fedora        | 32        | 7.53%   |
| Pop!_OS       | 24        | 5.65%   |
| Debian        | 22        | 5.18%   |
| Arch          | 19        | 4.47%   |
| KDE neon      | 17        | 4%      |
| Endless       | 14        | 3.29%   |
| Zorin         | 12        | 2.82%   |
| Xubuntu       | 9         | 2.12%   |
| Manjaro       | 9         | 2.12%   |
| Kubuntu       | 8         | 1.88%   |
| openSUSE      | 7         | 1.65%   |
| Ubuntu MATE   | 6         | 1.41%   |
| Elementary    | 5         | 1.18%   |
| Clear Linux   | 5         | 1.18%   |
| MX            | 3         | 0.71%   |
| Kali          | 3         | 0.71%   |
| ArcoLinux     | 3         | 0.71%   |
| UbuntuDDE     | 2         | 0.47%   |
| Reborn OS     | 2         | 0.47%   |
| Lubuntu       | 2         | 0.47%   |
| EndeavourOS   | 2         | 0.47%   |
| CentOS        | 2         | 0.47%   |
| BlackPanther  | 2         | 0.47%   |
| Ubuntu Unity  | 1         | 0.24%   |
| Ubuntu Budgie | 1         | 0.24%   |
| SteamOS       | 1         | 0.24%   |
| Solus         | 1         | 0.24%   |
| ROSA          | 1         | 0.24%   |
| Linux Lite    | 1         | 0.24%   |
| Lilidog       | 1         | 0.24%   |
| GNOME OS      | 1         | 0.24%   |
| Garuda Linux  | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 16        | 3.34%   |
| 5.15.0-46-generic        | 10        | 2.09%   |
| 6.1.1-desktop-1omv2290   | 9         | 1.88%   |
| 5.16.7-desktop-1omv4003  | 9         | 1.88%   |
| 5.4.0-42-generic         | 7         | 1.46%   |
| 5.4.0-48-generic         | 6         | 1.25%   |
| 4.18.0-15-generic        | 6         | 1.25%   |
| 5.3.0-28-generic         | 5         | 1.04%   |
| 5.15.0-58-generic        | 5         | 1.04%   |
| 5.15.0-56-generic        | 5         | 1.04%   |
| 5.15.0-43-generic        | 5         | 1.04%   |
| 6.0.12-76060006-generic  | 4         | 0.84%   |
| 5.8.0-59-generic         | 4         | 0.84%   |
| 5.4.0-59-generic         | 4         | 0.84%   |
| 5.3.0-23-generic         | 4         | 0.84%   |
| 5.11.0-40-generic        | 4         | 0.84%   |
| 5.10.0-21-amd64          | 4         | 0.84%   |
| 5.0.0-32-generic         | 4         | 0.84%   |
| 6.0.6-76060006-generic   | 3         | 0.63%   |
| 5.8.0-63-generic         | 3         | 0.63%   |
| 5.8.0-50-generic         | 3         | 0.63%   |
| 5.8.0-14-generic         | 3         | 0.63%   |
| 5.4.0-66-generic         | 3         | 0.63%   |
| 5.4.0-45-generic         | 3         | 0.63%   |
| 5.4.0-39-generic         | 3         | 0.63%   |
| 5.4.0-37-generic         | 3         | 0.63%   |
| 5.4.0-31-generic         | 3         | 0.63%   |
| 5.3.0-53-generic         | 3         | 0.63%   |
| 5.19.0-76051900-generic  | 3         | 0.63%   |
| 5.19.0-38-generic        | 3         | 0.63%   |
| 5.17.5-76051705-generic  | 3         | 0.63%   |
| 5.15.0-60-generic        | 3         | 0.63%   |
| 5.15.0-52-generic        | 3         | 0.63%   |
| 5.13.0-39-generic        | 3         | 0.63%   |
| 5.11.0-43-generic        | 3         | 0.63%   |
| 5.11.0-37-generic        | 3         | 0.63%   |
| 5.0.0-27-generic         | 3         | 0.63%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.42%   |
| 6.1.11-200.fc37.x86_64   | 2         | 0.42%   |
| 6.0.7-301.fc37.x86_64    | 2         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 72        | 15.42%  |
| 5.15.0  | 42        | 8.99%   |
| 5.8.0   | 26        | 5.57%   |
| 5.13.0  | 25        | 5.35%   |
| 4.15.0  | 24        | 5.14%   |
| 5.3.0   | 22        | 4.71%   |
| 5.11.0  | 18        | 3.85%   |
| 5.10.14 | 16        | 3.43%   |
| 5.0.0   | 16        | 3.43%   |
| 4.18.0  | 14        | 3%      |
| 6.1.1   | 11        | 2.36%   |
| 5.19.0  | 11        | 2.36%   |
| 5.10.0  | 10        | 2.14%   |
| 5.16.7  | 9         | 1.93%   |
| 4.19.0  | 7         | 1.5%    |
| 5.17.5  | 6         | 1.28%   |
| 6.0.12  | 5         | 1.07%   |
| 5.16.0  | 4         | 0.86%   |
| 6.1.12  | 3         | 0.64%   |
| 6.0.6   | 3         | 0.64%   |
| 6.2.6   | 2         | 0.43%   |
| 6.2.2   | 2         | 0.43%   |
| 6.1.11  | 2         | 0.43%   |
| 6.0.7   | 2         | 0.43%   |
| 6.0.0   | 2         | 0.43%   |
| 5.8.14  | 2         | 0.43%   |
| 5.6.14  | 2         | 0.43%   |
| 5.5.7   | 2         | 0.43%   |
| 5.19.16 | 2         | 0.43%   |
| 5.19.13 | 2         | 0.43%   |
| 5.18.5  | 2         | 0.43%   |
| 5.18.0  | 2         | 0.43%   |
| 5.17.3  | 2         | 0.43%   |
| 5.17.0  | 2         | 0.43%   |
| 5.16.9  | 2         | 0.43%   |
| 5.16.19 | 2         | 0.43%   |
| 5.16.13 | 2         | 0.43%   |
| 5.15.2  | 2         | 0.43%   |
| 5.15.14 | 2         | 0.43%   |
| 5.12.0  | 2         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 76        | 16.52%  |
| 5.15    | 52        | 11.3%   |
| 5.8     | 30        | 6.52%   |
| 5.13    | 30        | 6.52%   |
| 5.10    | 30        | 6.52%   |
| 5.3     | 24        | 5.22%   |
| 5.16    | 24        | 5.22%   |
| 4.15    | 24        | 5.22%   |
| 6.1     | 22        | 4.78%   |
| 5.19    | 18        | 3.91%   |
| 5.11    | 18        | 3.91%   |
| 5.0     | 17        | 3.7%    |
| 4.18    | 15        | 3.26%   |
| 6.0     | 14        | 3.04%   |
| 5.17    | 13        | 2.83%   |
| 6.2     | 8         | 1.74%   |
| 5.18    | 7         | 1.52%   |
| 4.19    | 7         | 1.52%   |
| 5.6     | 6         | 1.3%    |
| 5.9     | 5         | 1.09%   |
| 5.5     | 5         | 1.09%   |
| 5.12    | 5         | 1.09%   |
| 5.14    | 3         | 0.65%   |
| 5.7     | 2         | 0.43%   |
| 4.20    | 2         | 0.43%   |
| 5.1     | 1         | 0.22%   |
| 4.4     | 1         | 0.22%   |
| 4.17    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 409       | 99.03%  |
| i686   | 4         | 0.97%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 207       | 48.36%  |
| KDE5             | 69        | 16.12%  |
| Unknown          | 51        | 11.92%  |
| X-Cinnamon       | 31        | 7.24%   |
| XFCE             | 25        | 5.84%   |
| KDE              | 12        | 2.8%    |
| MATE             | 8         | 1.87%   |
| Pantheon         | 5         | 1.17%   |
| Budgie           | 5         | 1.17%   |
| Deepin           | 3         | 0.7%    |
| Cinnamon         | 3         | 0.7%    |
| LXQt             | 2         | 0.47%   |
| lightdm-xsession | 2         | 0.47%   |
| i3               | 2         | 0.47%   |
| Unity            | 1         | 0.23%   |
| LXDE             | 1         | 0.23%   |
| awesome          | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 318       | 75.18%  |
| Wayland | 67        | 15.84%  |
| Unknown | 32        | 7.57%   |
| Tty     | 6         | 1.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 228       | 53.52%  |
| SDDM    | 62        | 14.55%  |
| GDM     | 50        | 11.74%  |
| GDM3    | 42        | 9.86%   |
| LightDM | 33        | 7.75%   |
| TDM     | 9         | 2.11%   |
| XDM     | 1         | 0.23%   |
| Ly      | 1         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 290       | 68.88%  |
| Unknown | 47        | 11.16%  |
| en_GB   | 22        | 5.23%   |
| th_TH   | 20        | 4.75%   |
| de_DE   | 14        | 3.33%   |
| en_SG   | 7         | 1.66%   |
| C       | 7         | 1.66%   |
| fr_FR   | 4         | 0.95%   |
| ru_RU   | 3         | 0.71%   |
| it_IT   | 3         | 0.71%   |
| sv_SE   | 1         | 0.24%   |
| he_IL   | 1         | 0.24%   |
| es_MX   | 1         | 0.24%   |
| de_CH   | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 228       | 54.16%  |
| BIOS | 193       | 45.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 332       | 78.67%  |
| Overlay | 37        | 8.77%   |
| Btrfs   | 36        | 8.53%   |
| Unknown | 11        | 2.61%   |
| Xfs     | 3         | 0.71%   |
| Zfs     | 2         | 0.47%   |
| Tmpfs   | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 241       | 57.52%  |
| GPT     | 153       | 36.52%  |
| MBR     | 25        | 5.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 351       | 84.38%  |
| Yes       | 65        | 15.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 276       | 65.4%   |
| Yes       | 146       | 34.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUSTek Computer               | 73        | 17.68%  |
| Lenovo                         | 62        | 15.01%  |
| Acer                           | 46        | 11.14%  |
| Hewlett-Packard                | 41        | 9.93%   |
| Dell                           | 39        | 9.44%   |
| Gigabyte Technology            | 37        | 8.96%   |
| MSI                            | 26        | 6.3%    |
| ASRock                         | 24        | 5.81%   |
| Apple                          | 10        | 2.42%   |
| HUAWEI                         | 6         | 1.45%   |
| Unknown                        | 6         | 1.45%   |
| Intel                          | 5         | 1.21%   |
| Samsung Electronics            | 4         | 0.97%   |
| Toshiba                        | 3         | 0.73%   |
| Fujitsu                        | 3         | 0.73%   |
| Supermicro                     | 2         | 0.48%   |
| Huanan                         | 2         | 0.48%   |
| VIA Technologies               | 1         | 0.24%   |
| Timi                           | 1         | 0.24%   |
| Sony                           | 1         | 0.24%   |
| SmbiosType1_SystemManufacturer | 1         | 0.24%   |
| SHARKBAY                       | 1         | 0.24%   |
| Razer                          | 1         | 0.24%   |
| Pegatron                       | 1         | 0.24%   |
| Packard Bell                   | 1         | 0.24%   |
| OEM                            | 1         | 0.24%   |
| Notebook                       | 1         | 0.24%   |
| MiTAC                          | 1         | 0.24%   |
| Microsoft                      | 1         | 0.24%   |
| Infinix                        | 1         | 0.24%   |
| Hampoo                         | 1         | 0.24%   |
| Framework                      | 1         | 0.24%   |
| Foxconn                        | 1         | 0.24%   |
| Cube                           | 1         | 0.24%   |
| Clevo                          | 1         | 0.24%   |
| Biostar                        | 1         | 0.24%   |
| BESSTAR Tech                   | 1         | 0.24%   |
| AZW                            | 1         | 0.24%   |
| AMI                            | 1         | 0.24%   |
| ALLDOCUBE                      | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                         | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 8         | 1.94%   |
| ASUS All Series                                              | 7         | 1.69%   |
| Lenovo MIIX 520-12IKB 81CG                                   | 3         | 0.73%   |
| Dell OptiPlex 7010                                           | 3         | 0.73%   |
| ASUS P8H61-M LE                                              | 3         | 0.73%   |
| Samsung NC208/NC108                                          | 2         | 0.48%   |
| Lenovo ThinkPad 11e 5th Gen 20LQS00000                       | 2         | 0.48%   |
| Lenovo G460 20041                                            | 2         | 0.48%   |
| HUAWEI KLVL-WXX9                                             | 2         | 0.48%   |
| HP Z240 Tower Workstation                                    | 2         | 0.48%   |
| HP EliteDesk 800 G1 SFF PC                                   | 2         | 0.48%   |
| Gigabyte Z97X-UD3H-BK                                        | 2         | 0.48%   |
| Gigabyte F2A88XM-HD3P                                        | 2         | 0.48%   |
| Gigabyte F2A68HM-DS2                                         | 2         | 0.48%   |
| Gigabyte B250-HD3                                            | 2         | 0.48%   |
| Dell OptiPlex 3020                                           | 2         | 0.48%   |
| Dell Latitude E6430                                          | 2         | 0.48%   |
| Dell Latitude 3120                                           | 2         | 0.48%   |
| Dell Inspiron 3847                                           | 2         | 0.48%   |
| ASUS X556UQK                                                 | 2         | 0.48%   |
| ASUS X450LN                                                  | 2         | 0.48%   |
| ASUS VivoBook_ASUSLaptop M3500QA_D3500QA                     | 2         | 0.48%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA                      | 2         | 0.48%   |
| ASUS TUF Gaming FX505DT_FX505DT                              | 2         | 0.48%   |
| ASUS H110M-E/M.2                                             | 2         | 0.48%   |
| ASRock B450 Steel Legend                                     | 2         | 0.48%   |
| Apple MacBookAir3,2                                          | 2         | 0.48%   |
| Acer Aspire TC-885                                           | 2         | 0.48%   |
| Acer Aspire F5-573G                                          | 2         | 0.48%   |
| Acer Aspire E5-471G                                          | 2         | 0.48%   |
| Acer Aspire A315-21                                          | 2         | 0.48%   |
| VIA VX900                                                    | 1         | 0.24%   |
| Toshiba Satellite L840                                       | 1         | 0.24%   |
| Toshiba Satellite L645                                       | 1         | 0.24%   |
| Toshiba QOSMIO X70-B                                         | 1         | 0.24%   |
| Timi TM1701                                                  | 1         | 0.24%   |
| Supermicro X9DRW                                             | 1         | 0.24%   |
| Supermicro AT350 F3                                          | 1         | 0.24%   |
| Sony SVF14N25CXB                                             | 1         | 0.24%   |
| SmbiosType1_SystemManufacturer SmbiosType1_SystemProductName | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 30        | 7.26%   |
| Lenovo ThinkPad   | 26        | 6.3%    |
| Lenovo IdeaPad    | 11        | 2.66%   |
| HP Pavilion       | 11        | 2.66%   |
| ASUS VivoBook     | 10        | 2.42%   |
| Dell OptiPlex     | 9         | 2.18%   |
| Dell Latitude     | 8         | 1.94%   |
| Dell Inspiron     | 8         | 1.94%   |
| Unknown           | 8         | 1.94%   |
| ASUS All          | 7         | 1.69%   |
| Lenovo Yoga       | 6         | 1.45%   |
| HP Laptop         | 6         | 1.45%   |
| ASUS PRIME        | 6         | 1.45%   |
| Dell Precision    | 5         | 1.21%   |
| ASUS TUF          | 5         | 1.21%   |
| Lenovo MIIX       | 4         | 0.97%   |
| HP Compaq         | 4         | 0.97%   |
| Dell Vostro       | 4         | 0.97%   |
| ASUS ZenBook      | 4         | 0.97%   |
| ASUS ROG          | 4         | 0.97%   |
| ASRock B450       | 4         | 0.97%   |
| Acer Veriton      | 4         | 0.97%   |
| HP ProDesk        | 3         | 0.73%   |
| HP EliteBook      | 3         | 0.73%   |
| ASUS P8H61-M      | 3         | 0.73%   |
| ASUS M5A78L-M     | 3         | 0.73%   |
| ASRock B450M      | 3         | 0.73%   |
| Acer TravelMate   | 3         | 0.73%   |
| Acer Swift        | 3         | 0.73%   |
| Toshiba Satellite | 2         | 0.48%   |
| Samsung NC208     | 2         | 0.48%   |
| MSI Pro           | 2         | 0.48%   |
| Lenovo ThinkBook  | 2         | 0.48%   |
| Lenovo G460       | 2         | 0.48%   |
| HUAWEI KLVL-WXX9  | 2         | 0.48%   |
| Huanan X79        | 2         | 0.48%   |
| HP Z240           | 2         | 0.48%   |
| HP Stream         | 2         | 0.48%   |
| HP ENVY           | 2         | 0.48%   |
| HP EliteDesk      | 2         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 53        | 12.83%  |
| 2020 | 40        | 9.69%   |
| 2019 | 39        | 9.44%   |
| 2016 | 34        | 8.23%   |
| 2014 | 33        | 7.99%   |
| 2012 | 33        | 7.99%   |
| 2021 | 27        | 6.54%   |
| 2017 | 26        | 6.3%    |
| 2015 | 25        | 6.05%   |
| 2013 | 25        | 6.05%   |
| 2011 | 23        | 5.57%   |
| 2010 | 16        | 3.87%   |
| 2009 | 13        | 3.15%   |
| 2022 | 11        | 2.66%   |
| 2008 | 8         | 1.94%   |
| 2007 | 3         | 0.73%   |
| 2006 | 3         | 0.73%   |
| 2005 | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 213       | 51.57%  |
| Desktop     | 166       | 40.19%  |
| Convertible | 10        | 2.42%   |
| Tablet      | 8         | 1.94%   |
| Mini pc     | 7         | 1.69%   |
| All in one  | 7         | 1.69%   |
| Server      | 2         | 0.48%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 378       | 90.87%  |
| Enabled  | 38        | 9.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 413       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 100       | 23.87%  |
| 16.01-24.0      | 85        | 20.29%  |
| 3.01-4.0        | 83        | 19.81%  |
| 8.01-16.0       | 78        | 18.62%  |
| 32.01-64.0      | 38        | 9.07%   |
| 1.01-2.0        | 19        | 4.53%   |
| 24.01-32.0      | 6         | 1.43%   |
| 64.01-256.0     | 6         | 1.43%   |
| 0.51-1.0        | 2         | 0.48%   |
| More than 256.0 | 1         | 0.24%   |
| 2.01-3.0        | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 164       | 36.44%  |
| 2.01-3.0   | 132       | 29.33%  |
| 4.01-8.0   | 59        | 13.11%  |
| 3.01-4.0   | 53        | 11.78%  |
| 8.01-16.0  | 18        | 4%      |
| 0.51-1.0   | 17        | 3.78%   |
| 16.01-24.0 | 4         | 0.89%   |
| 0.01-0.5   | 2         | 0.44%   |
| 24.01-32.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 241       | 56.18%  |
| 2      | 114       | 26.57%  |
| 3      | 43        | 10.02%  |
| 4      | 13        | 3.03%   |
| 5      | 7         | 1.63%   |
| 0      | 7         | 1.63%   |
| 6      | 2         | 0.47%   |
| 51     | 1         | 0.23%   |
| 32     | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 285       | 68.67%  |
| Yes       | 130       | 31.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 343       | 82.65%  |
| No        | 72        | 17.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 322       | 77.4%   |
| No        | 94        | 22.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 250       | 59.38%  |
| No        | 171       | 40.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Thailand | 413       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangkok           | 164       | 37.53%  |
| Chiang Mai        | 35        | 8.01%   |
| Khon Kaen         | 15        | 3.43%   |
| Bang Lamung       | 15        | 3.43%   |
| Phuket            | 14        | 3.2%    |
| Nonthaburi        | 11        | 2.52%   |
| Nakhon Pathom     | 8         | 1.83%   |
| Songkhla          | 7         | 1.6%    |
| Surin             | 6         | 1.37%   |
| Pattaya           | 6         | 1.37%   |
| Nakhon Ratchasima | 6         | 1.37%   |
| Surat Thani       | 5         | 1.14%   |
| Hua Hin           | 5         | 1.14%   |
| Rayong            | 4         | 0.92%   |
| Pak Kret          | 4         | 0.92%   |
| Lat Krabang       | 4         | 0.92%   |
| Lampang           | 4         | 0.92%   |
| Khlong Luang      | 4         | 0.92%   |
| Chon Buri         | 4         | 0.92%   |
| Ban Phan Don      | 4         | 0.92%   |
| Suan Luang        | 3         | 0.69%   |
| Si Racha          | 3         | 0.69%   |
| Samut Prakan      | 3         | 0.69%   |
| Phitsanulok       | 3         | 0.69%   |
| Chanthaburi       | 3         | 0.69%   |
| Bang Khae         | 3         | 0.69%   |
| Bang Bon          | 3         | 0.69%   |
| Ban Yang Sam Ton  | 3         | 0.69%   |
| Ban Du            | 3         | 0.69%   |
| Salaya            | 2         | 0.46%   |
| Phetchaburi       | 2         | 0.46%   |
| Phayao            | 2         | 0.46%   |
| Phan              | 2         | 0.46%   |
| Pathum Thani      | 2         | 0.46%   |
| Min Buri          | 2         | 0.46%   |
| Maha Sarakham     | 2         | 0.46%   |
| Krabi             | 2         | 0.46%   |
| Chiang Rai        | 2         | 0.46%   |
| Bang Bua Thong    | 2         | 0.46%   |
| Ban Nong Sala     | 2         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 125       | 188    | 20.56%  |
| Seagate             | 94        | 139    | 15.46%  |
| Samsung Electronics | 76        | 108    | 12.5%   |
| Toshiba             | 38        | 86     | 6.25%   |
| Kingston            | 33        | 35     | 5.43%   |
| SanDisk             | 32        | 44     | 5.26%   |
| Unknown             | 29        | 41     | 4.77%   |
| Intel               | 16        | 17     | 2.63%   |
| Hitachi             | 13        | 14     | 2.14%   |
| Crucial             | 11        | 11     | 1.81%   |
| SK hynix            | 10        | 18     | 1.64%   |
| HGST                | 10        | 19     | 1.64%   |
| Micron Technology   | 8         | 9      | 1.32%   |
| HS-SSD-C100         | 8         | 14     | 1.32%   |
| Apacer              | 8         | 9      | 1.32%   |
| Transcend           | 6         | 7      | 0.99%   |
| Silicon Motion      | 6         | 8      | 0.99%   |
| Apple               | 6         | 6      | 0.99%   |
| Phison              | 5         | 10     | 0.82%   |
| Hikvision           | 5         | 5      | 0.82%   |
| China               | 5         | 5      | 0.82%   |
| SPCC                | 4         | 4      | 0.66%   |
| GALAX               | 4         | 4      | 0.66%   |
| USB3.0              | 3         | 4      | 0.49%   |
| Plextor             | 3         | 3      | 0.49%   |
| Phison Electronics  | 3         | 5      | 0.49%   |
| KingSpec            | 3         | 5      | 0.49%   |
| JMicron Technology  | 3         | 3      | 0.49%   |
| TO Exter            | 2         | 2      | 0.33%   |
| Pioneer             | 2         | 2      | 0.33%   |
| KIOXIA              | 2         | 4      | 0.33%   |
| Kingmax             | 2         | 5      | 0.33%   |
| Hewlett-Packard     | 2         | 4      | 0.33%   |
| External            | 2         | 2      | 0.33%   |
| Corsair             | 2         | 2      | 0.33%   |
| Colorful            | 2         | 3      | 0.33%   |
| A-DATA Technology   | 2         | 2      | 0.33%   |
| XPG                 | 1         | 1      | 0.16%   |
| WALRAM              | 1         | 1      | 0.16%   |
| Verbatim            | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB       | 9         | 1.35%   |
| Unknown MMC Card  32GB                | 8         | 1.2%    |
| Seagate ST1000DM010-2EP102 1TB        | 8         | 1.2%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 7         | 1.05%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 7         | 1.05%   |
| Unknown MMC Card  64GB                | 7         | 1.05%   |
| Toshiba MQ04ABF100 1TB                | 6         | 0.9%    |
| Toshiba MQ01ABD100 1TB                | 6         | 0.9%    |
| Seagate ST1000LM035-1RK172 970GB      | 6         | 0.9%    |
| Seagate ST1000DM003-1ER162 1TB        | 6         | 0.9%    |
| Kingston SA400S37240G 240GB SSD       | 6         | 0.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 5         | 0.75%   |
| WDC WD10EZEX-00WN4A0 1TB              | 5         | 0.75%   |
| Unknown SD/MMC/MS PRO 249GB           | 5         | 0.75%   |
| Seagate ST500LT012-1DG142 500GB       | 5         | 0.75%   |
| Kingston SUV400S37120G 120GB SSD      | 5         | 0.75%   |
| Crucial CT500MX500SSD1 500GB          | 5         | 0.75%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 4         | 0.6%    |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 4         | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB              | 4         | 0.6%    |
| Toshiba DT01ACA100 1TB                | 4         | 0.6%    |
| Seagate ST2000VX008-2E3164 2TB        | 4         | 0.6%    |
| Seagate ST1000LM049-2GH172 1TB        | 4         | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 0.6%    |
| Sandisk WD Blue SN550 NVMe SSD 1024GB | 4         | 0.6%    |
| SanDisk NVMe SSD Drive 250GB          | 4         | 0.6%    |
| SanDisk NVMe SSD Drive 1TB            | 4         | 0.6%    |
| Samsung HD103SJ 1TB                   | 4         | 0.6%    |
| HS-SSD-C100 240G                      | 4         | 0.6%    |
| WDC WD5000AAKX-00ERMA0 500GB          | 3         | 0.45%   |
| WDC WD20EZAZ-00GGJB0 2TB              | 3         | 0.45%   |
| WDC WD10SPZX-21Z10T0 1TB              | 3         | 0.45%   |
| WDC WD10JPVX-22JC3T0 1TB              | 3         | 0.45%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB    | 3         | 0.45%   |
| USB3.0 Super Speed 128GB              | 3         | 0.45%   |
| Toshiba MQ01ABF032 320GB              | 3         | 0.45%   |
| SK hynix HFM512GD3JX013N 512GB        | 3         | 0.45%   |
| Seagate ST3500418AS 500GB             | 3         | 0.45%   |
| SanDisk SDSSDA120G 120GB              | 3         | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB          | 3         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 93        | 138    | 35.63%  |
| WDC                 | 84        | 123    | 32.18%  |
| Toshiba             | 32        | 78     | 12.26%  |
| Samsung Electronics | 13        | 19     | 4.98%   |
| Hitachi             | 13        | 14     | 4.98%   |
| HGST                | 10        | 19     | 3.83%   |
| Unknown             | 6         | 11     | 2.3%    |
| USB3.0              | 3         | 4      | 1.15%   |
| JMicron Technology  | 2         | 2      | 0.77%   |
| Apple               | 2         | 2      | 0.77%   |
| Pioneer             | 1         | 1      | 0.38%   |
| Hewlett-Packard     | 1         | 3      | 0.38%   |
| Fujitsu             | 1         | 2      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 47     | 19.55%  |
| Samsung Electronics | 27        | 39     | 15.08%  |
| Kingston            | 20        | 21     | 11.17%  |
| SanDisk             | 12        | 18     | 6.7%    |
| Crucial             | 11        | 11     | 6.15%   |
| Apacer              | 8         | 9      | 4.47%   |
| Intel               | 6         | 6      | 3.35%   |
| China               | 5         | 5      | 2.79%   |
| SPCC                | 4         | 4      | 2.23%   |
| Hikvision           | 4         | 4      | 2.23%   |
| GALAX               | 4         | 4      | 2.23%   |
| Apple               | 4         | 4      | 2.23%   |
| Transcend           | 3         | 4      | 1.68%   |
| SK hynix            | 3         | 4      | 1.68%   |
| Plextor             | 3         | 3      | 1.68%   |
| Micron Technology   | 3         | 4      | 1.68%   |
| KingSpec            | 3         | 5      | 1.68%   |
| TO Exter            | 2         | 2      | 1.12%   |
| Kingmax             | 2         | 5      | 1.12%   |
| External            | 2         | 2      | 1.12%   |
| WALRAM              | 1         | 1      | 0.56%   |
| Verbatim            | 1         | 1      | 0.56%   |
| Teelkoou            | 1         | 1      | 0.56%   |
| Team                | 1         | 1      | 0.56%   |
| PNY                 | 1         | 2      | 0.56%   |
| Pioneer             | 1         | 1      | 0.56%   |
| OCZ                 | 1         | 1      | 0.56%   |
| LITEON              | 1         | 2      | 0.56%   |
| Lexar               | 1         | 1      | 0.56%   |
| HS-SSD-E100         | 1         | 1      | 0.56%   |
| Hised               | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 1      | 0.56%   |
| FORESEE             | 1         | 1      | 0.56%   |
| DGM                 | 1         | 1      | 0.56%   |
| Corsair             | 1         | 1      | 0.56%   |
| Colorful            | 1         | 2      | 0.56%   |
| Acer                | 1         | 3      | 0.56%   |
| A-DATA Technology   | 1         | 1      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 216       | 416    | 40%     |
| SSD     | 152       | 224    | 28.15%  |
| NVMe    | 134       | 185    | 24.81%  |
| MMC     | 23        | 30     | 4.26%   |
| Unknown | 15        | 21     | 2.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 307       | 629    | 63.04%  |
| NVMe | 134       | 185    | 27.52%  |
| SAS  | 23        | 32     | 4.72%   |
| MMC  | 23        | 30     | 4.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 209       | 325    | 53.45%  |
| 0.51-1.0   | 132       | 185    | 33.76%  |
| 1.01-2.0   | 32        | 39     | 8.18%   |
| 3.01-4.0   | 10        | 57     | 2.56%   |
| 2.01-3.0   | 3         | 8      | 0.77%   |
| 4.01-10.0  | 3         | 15     | 0.77%   |
| 10.01-20.0 | 2         | 11     | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 103       | 23.73%  |
| 251-500        | 90        | 20.74%  |
| 501-1000       | 68        | 15.67%  |
| 1-20           | 41        | 9.45%   |
| 1001-2000      | 34        | 7.83%   |
| 51-100         | 33        | 7.6%    |
| 21-50          | 25        | 5.76%   |
| 2001-3000      | 16        | 3.69%   |
| More than 3000 | 15        | 3.46%   |
| Unknown        | 9         | 2.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 181       | 40.22%  |
| 21-50          | 77        | 17.11%  |
| 101-250        | 54        | 12%     |
| 51-100         | 43        | 9.56%   |
| 251-500        | 35        | 7.78%   |
| 501-1000       | 26        | 5.78%   |
| 1001-2000      | 15        | 3.33%   |
| Unknown        | 9         | 2%      |
| More than 3000 | 7         | 1.56%   |
| 2001-3000      | 3         | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD2002FAEX-007BA0 2TB                | 2         | 2      | 5.41%   |
| Toshiba MQ01ABD100 1TB                   | 2         | 2      | 5.41%   |
| Seagate ST500DM002-1BD14 500GB           | 2         | 3      | 5.41%   |
| Seagate ST1000LM049-2GH172 1TB           | 2         | 2      | 5.41%   |
| Seagate ST1000LM035-1RK172 970GB         | 2         | 2      | 5.41%   |
| Samsung Electronics SSD 830 Series 128GB | 2         | 2      | 5.41%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1         | 1      | 2.7%    |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 2      | 2.7%    |
| WDC WD10PURX-64E5EY0 1TB                 | 1         | 1      | 2.7%    |
| WDC WD10EZEX-00WN4A0 1TB                 | 1         | 1      | 2.7%    |
| WDC WD1002FAEX-00Y9A0 1TB                | 1         | 1      | 2.7%    |
| USB3.0 Super Speed 128GB                 | 1         | 2      | 2.7%    |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 2.7%    |
| Toshiba HDWL110 1TB                      | 1         | 1      | 2.7%    |
| Seagate ST9500325AS 500GB                | 1         | 1      | 2.7%    |
| Seagate ST9120822AS 120GB                | 1         | 1      | 2.7%    |
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 2.7%    |
| Seagate ST500LM000-SSHD-8GB              | 1         | 1      | 2.7%    |
| Seagate ST500DM002-1BD142 500GB          | 1         | 1      | 2.7%    |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 1      | 2.7%    |
| Seagate ST3500418AS 500GB                | 1         | 2      | 2.7%    |
| Seagate ST1000LX015-1U7172-SSHD 1TB      | 1         | 1      | 2.7%    |
| Seagate ST1000LM014-1EJ164 1TB           | 1         | 1      | 2.7%    |
| SanDisk SDSSDX240GG25 240GB              | 1         | 1      | 2.7%    |
| Samsung Electronics HM160HI 160GB        | 1         | 2      | 2.7%    |
| Samsung Electronics HD253GJ 250GB        | 1         | 1      | 2.7%    |
| Samsung Electronics HD103SJ 1TB          | 1         | 1      | 2.7%    |
| Kingston RBU-SNS8350DES3128GP 128GB SSD  | 1         | 1      | 2.7%    |
| Intel SSDSC2KF256H6 SATA 256GB           | 1         | 1      | 2.7%    |
| HGST HTS725050A7E630 500GB               | 1         | 1      | 2.7%    |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 41.67%  |
| WDC                 | 6         | 8      | 16.67%  |
| Samsung Electronics | 5         | 6      | 13.89%  |
| Toshiba             | 4         | 4      | 11.11%  |
| HGST                | 2         | 2      | 5.56%   |
| USB3.0              | 1         | 2      | 2.78%   |
| SanDisk             | 1         | 1      | 2.78%   |
| Kingston            | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 48.39%  |
| WDC                 | 6         | 8      | 19.35%  |
| Toshiba             | 4         | 4      | 12.9%   |
| Samsung Electronics | 3         | 4      | 9.68%   |
| HGST                | 2         | 2      | 6.45%   |
| USB3.0              | 1         | 2      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 37     | 85.29%  |
| SSD  | 5         | 5      | 14.71%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 970GB | 1         | 1      | 50%     |
| Samsung Electronics HD103SJ 1TB  | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 275       | 538    | 61.66%  |
| Works    | 137       | 294    | 30.72%  |
| Malfunc  | 32        | 42     | 7.17%   |
| Failed   | 2         | 2      | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 262       | 51.68%  |
| AMD                          | 78        | 15.38%  |
| Samsung Electronics          | 44        | 8.68%   |
| SanDisk                      | 36        | 7.1%    |
| Kingston Technology Company  | 13        | 2.56%   |
| Nvidia                       | 11        | 2.17%   |
| ASMedia Technology           | 10        | 1.97%   |
| Phison Electronics           | 9         | 1.78%   |
| SK hynix                     | 7         | 1.38%   |
| Silicon Motion               | 7         | 1.38%   |
| Toshiba America Info Systems | 6         | 1.18%   |
| Micron Technology            | 5         | 0.99%   |
| VIA Technologies             | 3         | 0.59%   |
| LSI Logic / Symbios Logic    | 3         | 0.59%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.39%   |
| KIOXIA                       | 2         | 0.39%   |
| Broadcom / LSI               | 2         | 0.39%   |
| ADATA Technology             | 2         | 0.39%   |
| Transcend                    | 1         | 0.2%    |
| Realtek Semiconductor        | 1         | 0.2%    |
| Micron/Crucial Technology    | 1         | 0.2%    |
| Lite-On Technology           | 1         | 0.2%    |
| JMicron Technology           | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 57        | 9.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 26        | 4.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 24        | 4.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 22        | 3.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 3.31%   |
| AMD 400 Series Chipset SATA Controller                                           | 15        | 2.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 14        | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 2.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 11        | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 10        | 1.74%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 10        | 1.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 9         | 1.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 1.57%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 8         | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 8         | 1.39%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 1.22%   |
| Intel SSD 660P Series                                                            | 7         | 1.22%   |
| Intel SATA Controller [RAID mode]                                                | 7         | 1.22%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 1.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 7         | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 7         | 1.22%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 6         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 6         | 1.05%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 5         | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 0.87%   |
| Phison E12 NVMe Controller                                                       | 5         | 0.87%   |
| Micron NVMe Storage Controller                                                   | 5         | 0.87%   |
| Kingston Company Company Non-Volatile memory controller                          | 5         | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 0.87%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 5         | 0.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 298       | 58.09%  |
| NVMe | 138       | 26.9%   |
| IDE  | 48        | 9.36%   |
| RAID | 25        | 4.87%   |
| SAS  | 2         | 0.39%   |
| SCSI | 2         | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 313       | 75.79%  |
| AMD          | 99        | 23.97%  |
| CentaurHauls | 1         | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 2.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.93%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 1.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.2%    |
| Intel Core i3-2120 CPU @ 3.30GHz              | 5         | 1.2%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 5         | 1.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.96%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 4         | 0.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.96%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 4         | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 4         | 0.96%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 0.96%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 0.96%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.96%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.72%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 3         | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 0.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 0.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.72%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 0.72%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3         | 0.72%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.72%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.72%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 0.72%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 3         | 0.72%   |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G  | 3         | 0.72%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.48%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 2         | 0.48%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.48%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 2         | 0.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.48%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.48%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 86        | 20.77%  |
| Intel Core i5           | 84        | 20.29%  |
| Intel Core i3           | 42        | 10.14%  |
| AMD Ryzen 5             | 30        | 7.25%   |
| AMD Ryzen 7             | 17        | 4.11%   |
| Intel Celeron           | 16        | 3.86%   |
| Other                   | 15        | 3.62%   |
| Intel Xeon              | 13        | 3.14%   |
| Intel Pentium           | 13        | 3.14%   |
| Intel Core 2 Duo        | 12        | 2.9%    |
| Intel Atom              | 12        | 2.9%    |
| AMD Ryzen 9             | 7         | 1.69%   |
| AMD Ryzen 3             | 7         | 1.69%   |
| AMD FX                  | 5         | 1.21%   |
| AMD Athlon II X2        | 5         | 1.21%   |
| AMD A4                  | 5         | 1.21%   |
| AMD A10                 | 5         | 1.21%   |
| Intel Core i9           | 4         | 0.97%   |
| Intel Core 2 Quad       | 4         | 0.97%   |
| Intel Pentium Silver    | 3         | 0.72%   |
| Intel Pentium Dual-Core | 3         | 0.72%   |
| Intel Pentium Dual      | 2         | 0.48%   |
| Intel Core m3           | 2         | 0.48%   |
| AMD Ryzen 7 PRO         | 2         | 0.48%   |
| AMD Phenom II X6        | 2         | 0.48%   |
| AMD Phenom II X4        | 2         | 0.48%   |
| AMD Athlon 64 X2        | 2         | 0.48%   |
| AMD Athlon              | 2         | 0.48%   |
| AMD A6                  | 2         | 0.48%   |
| Intel Pentium D         | 1         | 0.24%   |
| Intel Pentium 4         | 1         | 0.24%   |
| CentaurHauls VIA Eden   | 1         | 0.24%   |
| AMD Turion 64 X2 Mobile | 1         | 0.24%   |
| AMD Ryzen 5 PRO         | 1         | 0.24%   |
| AMD Ryzen 3 PRO         | 1         | 0.24%   |
| AMD Phenom II X3        | 1         | 0.24%   |
| AMD E2                  | 1         | 0.24%   |
| AMD E1                  | 1         | 0.24%   |
| AMD A8                  | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 169       | 40.72%  |
| 2      | 151       | 36.39%  |
| 6      | 46        | 11.08%  |
| 8      | 32        | 7.71%   |
| 1      | 5         | 1.2%    |
| 12     | 3         | 0.72%   |
| 16     | 2         | 0.48%   |
| 14     | 2         | 0.48%   |
| 3      | 2         | 0.48%   |
| 40     | 1         | 0.24%   |
| 24     | 1         | 0.24%   |
| 10     | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 408       | 98.79%  |
| 2      | 5         | 1.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 290       | 69.71%  |
| 1      | 126       | 30.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 406       | 98.31%  |
| Unknown        | 6         | 1.45%   |
| 32-bit         | 1         | 0.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 107       | 24.83%  |
| 0x306c3    | 24        | 5.57%   |
| 0x306a9    | 21        | 4.87%   |
| 0x206a7    | 20        | 4.64%   |
| 0x506e3    | 14        | 3.25%   |
| 0x906ea    | 13        | 3.02%   |
| 0x806ea    | 12        | 2.78%   |
| 0x1067a    | 12        | 2.78%   |
| 0x806e9    | 10        | 2.32%   |
| 0x906e9    | 9         | 2.09%   |
| 0x806ec    | 9         | 2.09%   |
| 0x40651    | 9         | 2.09%   |
| 0x806c1    | 8         | 1.86%   |
| 0x20655    | 8         | 1.86%   |
| 0x406c4    | 7         | 1.62%   |
| 0x406e3    | 6         | 1.39%   |
| 0x406c3    | 6         | 1.39%   |
| 0x08108102 | 6         | 1.39%   |
| 0x30678    | 5         | 1.16%   |
| 0x0a50000c | 5         | 1.16%   |
| 0x0810100b | 5         | 1.16%   |
| 0x0800820d | 5         | 1.16%   |
| 0x706a8    | 4         | 0.93%   |
| 0x706a1    | 4         | 0.93%   |
| 0x20652    | 4         | 0.93%   |
| 0x08600106 | 4         | 0.93%   |
| 0x06001119 | 4         | 0.93%   |
| 0x010000c8 | 4         | 0.93%   |
| 0xa0655    | 3         | 0.7%    |
| 0xa0652    | 3         | 0.7%    |
| 0x906ec    | 3         | 0.7%    |
| 0x906c0    | 3         | 0.7%    |
| 0x6fd      | 3         | 0.7%    |
| 0x406f1    | 3         | 0.7%    |
| 0x106e5    | 3         | 0.7%    |
| 0x106ca    | 3         | 0.7%    |
| 0x08701021 | 3         | 0.7%    |
| 0x08600104 | 3         | 0.7%    |
| 0x08108109 | 3         | 0.7%    |
| 0x08001138 | 3         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 72        | 17.39%  |
| Haswell          | 47        | 11.35%  |
| IvyBridge        | 30        | 7.25%   |
| Skylake          | 29        | 7%      |
| SandyBridge      | 22        | 5.31%   |
| Silvermont       | 21        | 5.07%   |
| Zen+             | 20        | 4.83%   |
| Zen 2            | 19        | 4.59%   |
| Penryn           | 18        | 4.35%   |
| Westmere         | 13        | 3.14%   |
| CometLake        | 13        | 3.14%   |
| Zen 3            | 11        | 2.66%   |
| Zen              | 11        | 2.66%   |
| TigerLake        | 11        | 2.66%   |
| Unknown          | 10        | 2.42%   |
| K10              | 9         | 2.17%   |
| Goldmont plus    | 9         | 2.17%   |
| Piledriver       | 8         | 1.93%   |
| Excavator        | 5         | 1.21%   |
| Core             | 4         | 0.97%   |
| Broadwell        | 4         | 0.97%   |
| Bonnell          | 4         | 0.97%   |
| Tremont          | 3         | 0.72%   |
| Nehalem          | 3         | 0.72%   |
| K8 Hammer        | 3         | 0.72%   |
| IceLake          | 3         | 0.72%   |
| Steamroller      | 2         | 0.48%   |
| Puma             | 2         | 0.48%   |
| NetBurst         | 2         | 0.48%   |
| Goldmont         | 2         | 0.48%   |
| K10 Llano        | 1         | 0.24%   |
| Jaguar           | 1         | 0.24%   |
| Bobcat           | 1         | 0.24%   |
| Alderlake Hybrid | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 231       | 44.42%  |
| Nvidia                     | 173       | 33.27%  |
| AMD                        | 111       | 21.35%  |
| VIA Technologies           | 2         | 0.38%   |
| Matrox Electronics Systems | 1         | 0.19%   |
| ATI Technologies           | 1         | 0.19%   |
| ASPEED Technology          | 1         | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 3.34%   |
| Intel UHD Graphics 620                                                                   | 15        | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 2.6%    |
| Intel HD Graphics 530                                                                    | 13        | 2.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 2.04%   |
| Intel HD Graphics 620                                                                    | 11        | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.04%   |
| AMD Renoir                                                                               | 11        | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 1.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.48%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 1.48%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 1.11%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 6         | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.11%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.11%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.11%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6         | 1.11%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.11%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.93%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5         | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.93%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 0.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 0.93%   |
| Intel HD Graphics 630                                                                    | 5         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.74%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.74%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.74%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 4         | 0.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 0.74%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 142       | 33.73%  |
| 1 x Nvidia           | 80        | 19%     |
| 1 x AMD              | 80        | 19%     |
| Intel + Nvidia       | 75        | 17.81%  |
| AMD + Nvidia         | 14        | 3.33%   |
| 2 x AMD              | 10        | 2.38%   |
| Intel + AMD          | 10        | 2.38%   |
| 1 x VIA              | 2         | 0.48%   |
| Intel + 2 x Nvidia   | 2         | 0.48%   |
| 3 x Nvidia           | 1         | 0.24%   |
| 2 x Nvidia           | 1         | 0.24%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.24%   |
| 1 x Matrox           | 1         | 0.24%   |
| 1 x ASPEED           | 1         | 0.24%   |
| AMD + 2 x Nvidia     | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 329       | 77.59%  |
| Proprietary | 84        | 19.81%  |
| Unknown     | 11        | 2.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 229       | 53.38%  |
| 1.01-2.0   | 59        | 13.75%  |
| 3.01-4.0   | 43        | 10.02%  |
| 0.01-0.5   | 43        | 10.02%  |
| 0.51-1.0   | 29        | 6.76%   |
| 7.01-8.0   | 13        | 3.03%   |
| 5.01-6.0   | 8         | 1.86%   |
| 8.01-16.0  | 2         | 0.47%   |
| 4.01-5.0   | 1         | 0.23%   |
| 2.01-3.0   | 1         | 0.23%   |
| 16.01-24.0 | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 64        | 14.35%  |
| AU Optronics            | 56        | 12.56%  |
| Chimei Innolux          | 41        | 9.19%   |
| BOE                     | 36        | 8.07%   |
| Goldstar                | 34        | 7.62%   |
| Acer                    | 33        | 7.4%    |
| LG Display              | 32        | 7.17%   |
| Dell                    | 24        | 5.38%   |
| Hewlett-Packard         | 16        | 3.59%   |
| AOC                     | 12        | 2.69%   |
| PANDA                   | 9         | 2.02%   |
| Lenovo                  | 9         | 2.02%   |
| Sharp                   | 8         | 1.79%   |
| Apple                   | 8         | 1.79%   |
| BenQ                    | 7         | 1.57%   |
| ViewSonic               | 5         | 1.12%   |
| LG Electronics          | 5         | 1.12%   |
| InfoVision              | 3         | 0.67%   |
| Chi Mei Optoelectronics | 3         | 0.67%   |
| Unknown (XXX)           | 2         | 0.45%   |
| Philips                 | 2         | 0.45%   |
| MStar                   | 2         | 0.45%   |
| Mi                      | 2         | 0.45%   |
| ASUSTek Computer        | 2         | 0.45%   |
| Ancor Communications    | 2         | 0.45%   |
| Toshiba                 | 1         | 0.22%   |
| TCL                     | 1         | 0.22%   |
| Sony                    | 1         | 0.22%   |
| SKY                     | 1         | 0.22%   |
| SGT                     | 1         | 0.22%   |
| Seiko/Epson             | 1         | 0.22%   |
| RTK                     | 1         | 0.22%   |
| Quanta Display          | 1         | 0.22%   |
| Panasonic               | 1         | 0.22%   |
| NEC Computers           | 1         | 0.22%   |
| MSI                     | 1         | 0.22%   |
| MIG                     | 1         | 0.22%   |
| Microstep               | 1         | 0.22%   |
| LPL                     | 1         | 0.22%   |
| Lenovo Group Limited    | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 4         | 0.87%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 4         | 0.87%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 3         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.66%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 3         | 0.66%   |
| Acer K222HQL ACR0512 1920x1080 477x268mm 21.5-inch                    | 3         | 0.66%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                | 2         | 0.44%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch  | 2         | 0.44%   |
| Samsung Electronics SyncMaster SAM0366 1280x1024 338x270mm 17.0-inch  | 2         | 0.44%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch      | 2         | 0.44%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2         | 0.44%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2         | 0.44%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch  | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 2         | 0.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.44%   |
| MStar Demo MST0030 1366x768 708x398mm 32.0-inch                       | 2         | 0.44%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2         | 0.44%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 2         | 0.44%   |
| LG Display LCD Monitor LGD0454 1366x768 310x174mm 14.0-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 2         | 0.44%   |
| Lenovo AIO PC LEN2000 1920x1080 527x296mm 23.8-inch                   | 2         | 0.44%   |
| Hewlett-Packard Z24n HWP320E 1920x1080 518x324mm 24.1-inch            | 2         | 0.44%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 2         | 0.44%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.44%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2         | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 2         | 0.44%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.44%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 0.44%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                  | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 197       | 45.71%  |
| 1366x768 (WXGA)    | 97        | 22.51%  |
| 3840x2160 (4K)     | 26        | 6.03%   |
| 1600x900 (HD+)     | 21        | 4.87%   |
| 2560x1440 (QHD)    | 14        | 3.25%   |
| 1440x900 (WXGA+)   | 14        | 3.25%   |
| 1280x1024 (SXGA)   | 9         | 2.09%   |
| 1680x1050 (WSXGA+) | 8         | 1.86%   |
| 2560x1080          | 7         | 1.62%   |
| 1360x768           | 5         | 1.16%   |
| Unknown            | 5         | 1.16%   |
| 2560x1600          | 3         | 0.7%    |
| 1920x1200 (WUXGA)  | 3         | 0.7%    |
| 1280x800 (WXGA)    | 3         | 0.7%    |
| 3840x2400          | 2         | 0.46%   |
| 3840x1080          | 2         | 0.46%   |
| 2160x1440          | 2         | 0.46%   |
| 1600x1200          | 2         | 0.46%   |
| 3520x1080          | 1         | 0.23%   |
| 3440x1440          | 1         | 0.23%   |
| 2880x1800          | 1         | 0.23%   |
| 2736x1824          | 1         | 0.23%   |
| 2732x768           | 1         | 0.23%   |
| 2256x1504          | 1         | 0.23%   |
| 1920x515           | 1         | 0.23%   |
| 1920x1280          | 1         | 0.23%   |
| 1280x720 (HD)      | 1         | 0.23%   |
| 1024x768 (XGA)     | 1         | 0.23%   |
| 1024x600           | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 90        | 20.13%  |
| 14      | 48        | 10.74%  |
| 13      | 43        | 9.62%   |
| 23      | 34        | 7.61%   |
| 21      | 29        | 6.49%   |
| 24      | 27        | 6.04%   |
| Unknown | 25        | 5.59%   |
| 27      | 24        | 5.37%   |
| 18      | 19        | 4.25%   |
| 19      | 17        | 3.8%    |
| 17      | 17        | 3.8%    |
| 20      | 14        | 3.13%   |
| 11      | 13        | 2.91%   |
| 34      | 6         | 1.34%   |
| 22      | 6         | 1.34%   |
| 31      | 5         | 1.12%   |
| 12      | 5         | 1.12%   |
| 84      | 4         | 0.89%   |
| 16      | 4         | 0.89%   |
| 72      | 2         | 0.45%   |
| 54      | 2         | 0.45%   |
| 52      | 2         | 0.45%   |
| 47      | 2         | 0.45%   |
| 26      | 2         | 0.45%   |
| 60      | 1         | 0.22%   |
| 46      | 1         | 0.22%   |
| 40      | 1         | 0.22%   |
| 39      | 1         | 0.22%   |
| 29      | 1         | 0.22%   |
| 10      | 1         | 0.22%   |
| 8       | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 165       | 37.59%  |
| 501-600     | 82        | 18.68%  |
| 401-500     | 81        | 18.45%  |
| 201-300     | 40        | 9.11%   |
| Unknown     | 25        | 5.69%   |
| 351-400     | 18        | 4.1%    |
| 1001-1500   | 8         | 1.82%   |
| 701-800     | 6         | 1.37%   |
| 601-700     | 6         | 1.37%   |
| 1501-2000   | 5         | 1.14%   |
| 801-900     | 2         | 0.46%   |
| 101-200     | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 319       | 79.35%  |
| 16/10   | 38        | 9.45%   |
| Unknown | 21        | 5.22%   |
| 5/4     | 9         | 2.24%   |
| 3/2     | 6         | 1.49%   |
| 21/9    | 6         | 1.49%   |
| 4/3     | 2         | 0.5%    |
| 3.73    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 90        | 20.27%  |
| 201-250        | 79        | 17.79%  |
| 81-90          | 75        | 16.89%  |
| 151-200        | 40        | 9.01%   |
| 301-350        | 26        | 5.86%   |
| Unknown        | 25        | 5.63%   |
| 141-150        | 20        | 4.5%    |
| 71-80          | 16        | 3.6%    |
| 51-60          | 14        | 3.15%   |
| 351-500        | 12        | 2.7%    |
| 121-130        | 12        | 2.7%    |
| More than 1000 | 10        | 2.25%   |
| 251-300        | 8         | 1.8%    |
| 61-70          | 5         | 1.13%   |
| 501-1000       | 5         | 1.13%   |
| 131-140        | 3         | 0.68%   |
| 111-120        | 2         | 0.45%   |
| 1-40           | 1         | 0.23%   |
| 91-100         | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 139       | 32.25%  |
| 121-160       | 110       | 25.52%  |
| 101-120       | 108       | 25.06%  |
| 161-240       | 32        | 7.42%   |
| Unknown       | 25        | 5.8%    |
| 1-50          | 9         | 2.09%   |
| More than 240 | 8         | 1.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 339       | 79.39%  |
| 2     | 64        | 14.99%  |
| 0     | 17        | 3.98%   |
| 3     | 7         | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 246       | 38.86%  |
| Intel                             | 175       | 27.65%  |
| Qualcomm Atheros                  | 77        | 12.16%  |
| Broadcom                          | 40        | 6.32%   |
| Ralink Technology                 | 13        | 2.05%   |
| MediaTek                          | 10        | 1.58%   |
| ASIX Electronics                  | 9         | 1.42%   |
| D-Link                            | 8         | 1.26%   |
| TP-Link                           | 7         | 1.11%   |
| Nvidia                            | 7         | 1.11%   |
| Broadcom Limited                  | 5         | 0.79%   |
| Ralink                            | 4         | 0.63%   |
| D-Link System                     | 4         | 0.63%   |
| Xiaomi                            | 3         | 0.47%   |
| Samsung Electronics               | 3         | 0.47%   |
| VIA Technologies                  | 2         | 0.32%   |
| Mercucys                          | 2         | 0.32%   |
| Marvell Technology Group          | 2         | 0.32%   |
| Huawei Technologies               | 2         | 0.32%   |
| Ericsson Business Mobile Networks | 2         | 0.32%   |
| ASUSTek Computer                  | 2         | 0.32%   |
| Qualcomm Atheros Communications   | 1         | 0.16%   |
| Qualcomm                          | 1         | 0.16%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.16%   |
| Lenovo                            | 1         | 0.16%   |
| JMicron Technology                | 1         | 0.16%   |
| Edimax Technology                 | 1         | 0.16%   |
| BUFFALO                           | 1         | 0.16%   |
| Aquantia                          | 1         | 0.16%   |
| Android                           | 1         | 0.16%   |
| Adafruit                          | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 192       | 26.82%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 2.23%   |
| Intel Wi-Fi 6 AX200                                               | 15        | 2.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 1.54%   |
| Intel Wireless-AC 9260                                            | 9         | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 1.26%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.12%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 0.98%   |
| Intel Wireless 8260                                               | 7         | 0.98%   |
| Intel Wireless 7265                                               | 7         | 0.98%   |
| Intel Wireless 3160                                               | 7         | 0.98%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 0.98%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.98%   |
| Ralink MT7601U Wireless Adapter                                   | 6         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.84%   |
| Intel I211 Gigabit Network Connection                             | 6         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.7%    |
| Intel Wireless 3165                                               | 5         | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 5         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 4         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 132       | 38.82%  |
| Qualcomm Atheros                | 66        | 19.41%  |
| Realtek Semiconductor           | 58        | 17.06%  |
| Broadcom                        | 26        | 7.65%   |
| Ralink Technology               | 13        | 3.82%   |
| MediaTek                        | 10        | 2.94%   |
| D-Link                          | 8         | 2.35%   |
| TP-Link                         | 7         | 2.06%   |
| Broadcom Limited                | 5         | 1.47%   |
| Ralink                          | 4         | 1.18%   |
| Mercucys                        | 2         | 0.59%   |
| D-Link System                   | 2         | 0.59%   |
| ASUSTek Computer                | 2         | 0.59%   |
| Qualcomm Atheros Communications | 1         | 0.29%   |
| Qualcomm                        | 1         | 0.29%   |
| Marvell Technology Group        | 1         | 0.29%   |
| Edimax Technology               | 1         | 0.29%   |
| BUFFALO                         | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 19        | 5.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 16        | 4.69%   |
| Intel Wi-Fi 6 AX200                                            | 15        | 4.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 3.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 12        | 3.52%   |
| Intel Wireless-AC 9260                                         | 9         | 2.64%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 2.64%   |
| Intel Wireless 8265 / 8275                                     | 8         | 2.35%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 2.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 2.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7         | 2.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.05%   |
| Intel Wireless 8260                                            | 7         | 2.05%   |
| Intel Wireless 7265                                            | 7         | 2.05%   |
| Intel Wireless 3160                                            | 7         | 2.05%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.76%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 1.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 1.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.47%   |
| Intel Wireless 3165                                            | 5         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 1.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 1.17%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 4         | 1.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 1.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 1.17%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.17%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]  | 4         | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 0.88%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 222       | 61.5%   |
| Intel                         | 73        | 20.22%  |
| Broadcom                      | 19        | 5.26%   |
| Qualcomm Atheros              | 16        | 4.43%   |
| ASIX Electronics              | 9         | 2.49%   |
| Nvidia                        | 7         | 1.94%   |
| Xiaomi                        | 3         | 0.83%   |
| VIA Technologies              | 2         | 0.55%   |
| Samsung Electronics           | 2         | 0.55%   |
| D-Link System                 | 2         | 0.55%   |
| OnePlus Technology (Shenzhen) | 1         | 0.28%   |
| Marvell Technology Group      | 1         | 0.28%   |
| Lenovo                        | 1         | 0.28%   |
| JMicron Technology            | 1         | 0.28%   |
| Huawei Technologies           | 1         | 0.28%   |
| Aquantia                      | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 192       | 52.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 4.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.9%    |
| Intel Ethernet Connection (2) I219-V                              | 7         | 1.9%    |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.9%    |
| Intel I211 Gigabit Network Connection                             | 6         | 1.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.36%   |
| Intel Ethernet Connection I217-V                                  | 5         | 1.36%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 1.36%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.81%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.81%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.54%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.54%   |
| Nvidia MCP73 Ethernet                                             | 2         | 0.54%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.54%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.54%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.54%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.54%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.54%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 2         | 0.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.54%   |
| Xiaomi 100Mbps Network Card Adapter                               | 1         | 0.27%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1         | 0.27%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 342       | 51.04%  |
| WiFi     | 322       | 48.06%  |
| Modem    | 5         | 0.75%   |
| Unknown  | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 271       | 63.47%  |
| Ethernet | 156       | 36.53%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 213       | 51.08%  |
| 1     | 189       | 45.32%  |
| 0     | 8         | 1.92%   |
| 3     | 4         | 0.96%   |
| 4     | 2         | 0.48%   |
| 5     | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 325       | 75.93%  |
| Yes  | 103       | 24.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 105       | 41.34%  |
| Cambridge Silicon Radio         | 23        | 9.06%   |
| IMC Networks                    | 21        | 8.27%   |
| Lite-On Technology              | 20        | 7.87%   |
| Realtek Semiconductor           | 17        | 6.69%   |
| Qualcomm Atheros Communications | 12        | 4.72%   |
| Broadcom                        | 11        | 4.33%   |
| Apple                           | 11        | 4.33%   |
| Foxconn / Hon Hai               | 7         | 2.76%   |
| MediaTek                        | 4         | 1.57%   |
| Dell                            | 4         | 1.57%   |
| ASUSTek Computer                | 4         | 1.57%   |
| Toshiba                         | 3         | 1.18%   |
| Realtek                         | 3         | 1.18%   |
| Foxconn International           | 3         | 1.18%   |
| Hewlett-Packard                 | 2         | 0.79%   |
| USI                             | 1         | 0.39%   |
| Ralink                          | 1         | 0.39%   |
| Marvell Semiconductor           | 1         | 0.39%   |
| Askey Computer                  | 1         | 0.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 38        | 14.96%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23        | 9.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 7.48%   |
| Intel AX201 Bluetooth                               | 18        | 7.09%   |
| Intel AX200 Bluetooth                               | 12        | 4.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 3.54%   |
| IMC Networks Bluetooth Device                       | 9         | 3.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 2.76%   |
| Realtek Bluetooth Radio                             | 7         | 2.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 2.76%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 2.36%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.97%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.97%   |
| MediaTek Wireless_Device                            | 4         | 1.57%   |
| Lite-On Bluetooth Device                            | 4         | 1.57%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.57%   |
| Apple Bluetooth Host Controller                     | 4         | 1.57%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 1.18%   |
| Intel Bluetooth Device                              | 3         | 1.18%   |
| Intel AX210 Bluetooth                               | 3         | 1.18%   |
| IMC Networks Wireless_Device                        | 3         | 1.18%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.18%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.18%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.79%   |
| Lite-On Wireless_Device                             | 2         | 0.79%   |
| Lite-On Bluetooth Radio                             | 2         | 0.79%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.79%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.79%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.79%   |
| USI Bluetooth Device                                | 1         | 0.39%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.39%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.39%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.39%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.39%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 296       | 50.68%  |
| AMD                                          | 122       | 20.89%  |
| Nvidia                                       | 114       | 19.52%  |
| C-Media Electronics                          | 11        | 1.88%   |
| JMTek                                        | 8         | 1.37%   |
| Razer USA                                    | 5         | 0.86%   |
| VIA Technologies                             | 2         | 0.34%   |
| SAVITECH                                     | 2         | 0.34%   |
| Samson Technologies                          | 2         | 0.34%   |
| Elan Microelectronics                        | 2         | 0.34%   |
| Earth Computer Technologies                  | 2         | 0.34%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.17%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.17%   |
| Texas Instruments                            | 1         | 0.17%   |
| Samsung Electronics                          | 1         | 0.17%   |
| Nordic Semiconductor ASA                     | 1         | 0.17%   |
| Lenovo                                       | 1         | 0.17%   |
| Kingston Technology                          | 1         | 0.17%   |
| Huawei Technologies                          | 1         | 0.17%   |
| Generalplus Technology                       | 1         | 0.17%   |
| ESS Technology                               | 1         | 0.17%   |
| Dell                                         | 1         | 0.17%   |
| DCMT Technology                              | 1         | 0.17%   |
| Creative Technology                          | 1         | 0.17%   |
| Creative Labs                                | 1         | 0.17%   |
| Cayin                                        | 1         | 0.17%   |
| Blue Microphones                             | 1         | 0.17%   |
| Audient                                      | 1         | 0.17%   |
| ASUSTek Computer                             | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 47        | 6.64%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 34        | 4.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 29        | 4.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 27        | 3.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 24        | 3.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 23        | 3.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21        | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 20        | 2.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 2.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 15        | 2.12%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 2.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 1.98%   |
| Intel 200 Series PCH HD Audio                                                                     | 13        | 1.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.69%   |
| Nvidia High Definition Audio Controller                                                           | 11        | 1.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 1.55%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 1.55%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.55%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 1.41%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 10        | 1.41%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 9         | 1.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 9         | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 1.13%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 1.13%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 1.13%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 7         | 0.99%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 0.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 0.99%   |
| JMTek USB PnP Audio Device                                                                        | 7         | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 0.99%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 6         | 0.85%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 5         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.71%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 5         | 0.71%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.71%   |
| AMD Navi 10 HDMI Audio                                                                            | 5         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 55        | 24.23%  |
| Kingston            | 52        | 22.91%  |
| SK hynix            | 36        | 15.86%  |
| Micron Technology   | 25        | 11.01%  |
| Unknown             | 18        | 7.93%   |
| Corsair             | 10        | 4.41%   |
| Transcend           | 5         | 2.2%    |
| Crucial             | 5         | 2.2%    |
| Elpida              | 4         | 1.76%   |
| G.Skill             | 3         | 1.32%   |
| A-DATA Technology   | 3         | 1.32%   |
| Unknown (ABCD)      | 2         | 0.88%   |
| Team                | 2         | 0.88%   |
| Unknown (0x02BA)    | 1         | 0.44%   |
| Unknown (08B5)      | 1         | 0.44%   |
| Ramaxel Technology  | 1         | 0.44%   |
| Nanya Technology    | 1         | 0.44%   |
| Lexar               | 1         | 0.44%   |
| ASint Technology    | 1         | 0.44%   |
| Unknown             | 1         | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 5         | 2.09%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 5         | 2.09%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 1.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 4         | 1.67%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3         | 1.26%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 1.26%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 3         | 1.26%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 3         | 1.26%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 1.26%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                    | 2         | 0.84%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 2         | 0.84%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                    | 2         | 0.84%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 0.84%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 2         | 0.84%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s | 2         | 0.84%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                    | 2         | 0.84%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.84%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 0.84%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.84%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.84%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 2         | 0.84%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 2         | 0.84%   |
| Micron RAM Module 4096MB SODIMM DDR4 2400MT/s                  | 2         | 0.84%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 2         | 0.84%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s          | 2         | 0.84%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s                 | 2         | 0.84%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 2         | 0.84%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s            | 2         | 0.84%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2         | 0.84%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 2         | 0.84%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s        | 2         | 0.84%   |
| Crucial RAM CT16G4SFD824A.C16FBR 16GB SODIMM DDR4 2400MT/s     | 2         | 0.84%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM 1600MT/s                 | 2         | 0.84%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s            | 1         | 0.42%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s                   | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1334MT/s                 | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                        | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                       | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 92        | 46.94%  |
| DDR3    | 67        | 34.18%  |
| LPDDR4  | 14        | 7.14%   |
| SDRAM   | 6         | 3.06%   |
| LPDDR3  | 4         | 2.04%   |
| DDR5    | 4         | 2.04%   |
| Unknown | 4         | 2.04%   |
| DDR2    | 2         | 1.02%   |
| DDR     | 2         | 1.02%   |
| LPDDR5  | 1         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 111       | 57.81%  |
| DIMM         | 62        | 32.29%  |
| Row Of Chips | 17        | 8.85%   |
| RIMM         | 1         | 0.52%   |
| FB-DIMM      | 1         | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 79        | 39.5%   |
| 4096  | 65        | 32.5%   |
| 16384 | 26        | 13%     |
| 2048  | 24        | 12%     |
| 32768 | 4         | 2%      |
| 1024  | 2         | 1%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 47        | 22.27%  |
| 3200    | 28        | 13.27%  |
| 2667    | 25        | 11.85%  |
| 1333    | 21        | 9.95%   |
| 2400    | 18        | 8.53%   |
| 2133    | 11        | 5.21%   |
| 3600    | 6         | 2.84%   |
| 4267    | 5         | 2.37%   |
| 3266    | 5         | 2.37%   |
| 1867    | 5         | 2.37%   |
| 1334    | 5         | 2.37%   |
| 1067    | 4         | 1.9%    |
| 4800    | 3         | 1.42%   |
| 1866    | 3         | 1.42%   |
| 4266    | 2         | 0.95%   |
| 3733    | 2         | 0.95%   |
| 3466    | 2         | 0.95%   |
| 3400    | 2         | 0.95%   |
| 3151    | 2         | 0.95%   |
| 3000    | 2         | 0.95%   |
| 667     | 2         | 0.95%   |
| 8400    | 1         | 0.47%   |
| 6400    | 1         | 0.47%   |
| 5600    | 1         | 0.47%   |
| 4199    | 1         | 0.47%   |
| 3534    | 1         | 0.47%   |
| 3333    | 1         | 0.47%   |
| 2800    | 1         | 0.47%   |
| 2666    | 1         | 0.47%   |
| 800     | 1         | 0.47%   |
| 533     | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 36.36%  |
| Seiko Epson         | 3         | 27.27%  |
| STMicroelectronics  | 1         | 9.09%   |
| Samsung Electronics | 1         | 9.09%   |
| Pantum              | 1         | 9.09%   |
| Canon               | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| STMicroelectronics USB Printer P | 1         | 9.09%   |
| Seiko Epson ME-100 Series        | 1         | 9.09%   |
| Seiko Epson LQ-310               | 1         | 9.09%   |
| Seiko Epson L222 Series          | 1         | 9.09%   |
| Samsung SCX-4300 Series          | 1         | 9.09%   |
| Pantum P2500W series             | 1         | 9.09%   |
| Canon E4200 series               | 1         | 9.09%   |
| Brother HL-1110 series           | 1         | 9.09%   |
| Brother DCP-T510W                | 1         | 9.09%   |
| Brother DCP-T300                 | 1         | 9.09%   |
| Brother DCP-L3551CDW             | 1         | 9.09%   |

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


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 55        | 23.5%   |
| IMC Networks                           | 30        | 12.82%  |
| Realtek Semiconductor                  | 20        | 8.55%   |
| Acer                                   | 19        | 8.12%   |
| Microdia                               | 18        | 7.69%   |
| Quanta                                 | 14        | 5.98%   |
| Logitech                               | 11        | 4.7%    |
| Bison Electronics                      | 11        | 4.7%    |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.42%   |
| Sunplus Innovation Technology          | 7         | 2.99%   |
| Apple                                  | 6         | 2.56%   |
| Lite-On Technology                     | 5         | 2.14%   |
| Suyin                                  | 4         | 1.71%   |
| Aveo Technology                        | 4         | 1.71%   |
| Syntek                                 | 3         | 1.28%   |
| Silicon Motion                         | 3         | 1.28%   |
| Generalplus Technology                 | 3         | 1.28%   |
| Samsung Electronics                    | 2         | 0.85%   |
| Microsoft                              | 2         | 0.85%   |
| Z-Star Microelectronics                | 1         | 0.43%   |
| Sony Electronics                       | 1         | 0.43%   |
| Sonix Technology                       | 1         | 0.43%   |
| Razer USA                              | 1         | 0.43%   |
| Owon                                   | 1         | 0.43%   |
| Luxvisions Innotech Limited            | 1         | 0.43%   |
| Lenovo                                 | 1         | 0.43%   |
| icSpring                               | 1         | 0.43%   |
| Alcor Micro                            | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam       | 12        | 5.11%   |
| Chicony HD WebCam                       | 11        | 4.68%   |
| Chicony Integrated Camera               | 10        | 4.26%   |
| Microdia Integrated_Webcam_HD           | 6         | 2.55%   |
| Chicony HP Truevision HD camera         | 6         | 2.55%   |
| Realtek Integrated_Webcam_HD            | 5         | 2.13%   |
| Acer Lenovo EasyCamera                  | 5         | 2.13%   |
| Acer Integrated Camera                  | 5         | 2.13%   |
| Realtek HD WebCam                       | 4         | 1.7%    |
| IMC Networks USB2.0 VGA UVC WebCam      | 4         | 1.7%    |
| IMC Networks Integrated Camera          | 4         | 1.7%    |
| Chicony Lenovo EasyCamera               | 4         | 1.7%    |
| Bison SunplusIT Integrated Camera       | 4         | 1.7%    |
| Silicon Motion WebCam SCB-0385N         | 3         | 1.28%   |
| Microdia USB 2.0 Camera                 | 3         | 1.28%   |
| Microdia Camera                         | 3         | 1.28%   |
| Lite-On HP Wide Vision HD Camera        | 3         | 1.28%   |
| Generalplus GENERAL WEBCAM              | 3         | 1.28%   |
| Chicony HP Wide Vision HD Camera        | 3         | 1.28%   |
| Chicony HD User Facing                  | 3         | 1.28%   |
| Aveo USB2.0 Camera                      | 3         | 1.28%   |
| Apple Built-in iSight                   | 3         | 1.28%   |
| Acer ThinkPad Integrated Camera         | 3         | 1.28%   |
| Acer Lenovo Integrated Webcam           | 3         | 1.28%   |
| Syntek Integrated Camera                | 2         | 0.85%   |
| Sunplus Integrated_Webcam_HD            | 2         | 0.85%   |
| Samsung Galaxy series, misc. (MTP mode) | 2         | 0.85%   |
| Realtek USB2.0 HD UVC WebCam            | 2         | 0.85%   |
| Realtek Integrated Webcam               | 2         | 0.85%   |
| Quanta VGA WebCam                       | 2         | 0.85%   |
| Quanta USB2.0 HD UVC WebCam             | 2         | 0.85%   |
| Quanta ov9734_techfront_camera          | 2         | 0.85%   |
| Quanta HD Webcam                        | 2         | 0.85%   |
| Quanta HD User Facing                   | 2         | 0.85%   |
| Microdia Integrated Webcam              | 2         | 0.85%   |
| Logitech Webcam C310                    | 2         | 0.85%   |
| Logitech Webcam C270                    | 2         | 0.85%   |
| IMC Networks VGA UVC WebCam             | 2         | 0.85%   |
| IMC Networks USB2.0 UVC HD Webcam       | 2         | 0.85%   |
| IMC Networks ov9734_azurewave_camera    | 2         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 3         | 37.5%   |
| O2 Micro              | 2         | 25%     |
| Broadcom              | 2         | 25%     |
| Gemalto (was Gemplus) | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 301       | 71.33%  |
| 1     | 98        | 23.22%  |
| 2     | 19        | 4.5%    |
| 3     | 2         | 0.47%   |
| 7     | 1         | 0.24%   |
| 5     | 1         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 29.66%  |
| Graphics card            | 33        | 22.76%  |
| Net/wireless             | 17        | 11.72%  |
| Multimedia controller    | 17        | 11.72%  |
| Chipcard                 | 8         | 5.52%   |
| Communication controller | 7         | 4.83%   |
| Sound                    | 6         | 4.14%   |
| Unassigned class         | 3         | 2.07%   |
| Bluetooth                | 3         | 2.07%   |
| Camera                   | 2         | 1.38%   |
| Wireless                 | 1         | 0.69%   |
| Storage/ide              | 1         | 0.69%   |
| Network                  | 1         | 0.69%   |
| Net/ethernet             | 1         | 0.69%   |
| Flash memory             | 1         | 0.69%   |
| Card reader              | 1         | 0.69%   |

