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

Total: 577

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 60        | 14.29%  |
| Ubuntu 18.04                 | 34        | 8.1%    |
| Ubuntu 22.04                 | 19        | 4.52%   |
| OpenMandriva 4.2             | 16        | 3.81%   |
| Pop!_OS 22.04                | 14        | 3.33%   |
| KDE neon 20.04               | 12        | 2.86%   |
| OpenMandriva 4.3             | 11        | 2.62%   |
| Arch Rolling                 | 11        | 2.62%   |
| Debian 11                    | 10        | 2.38%   |
| Fedora 37                    | 9         | 2.14%   |
| OpenMandriva 23.01           | 8         | 1.9%    |
| Linux Mint 21                | 8         | 1.9%    |
| Zorin 15                     | 7         | 1.67%   |
| Arch                         | 7         | 1.67%   |
| Ubuntu 19.10                 | 6         | 1.43%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 1.43%   |
| Manjaro                      | 6         | 1.43%   |
| Linux Mint 20.2              | 6         | 1.43%   |
| Zorin 16                     | 5         | 1.19%   |
| Xubuntu 20.04                | 5         | 1.19%   |
| Ubuntu 19.04                 | 5         | 1.19%   |
| Kubuntu 22.04                | 5         | 1.19%   |
| Fedora 36                    | 5         | 1.19%   |
| Debian Testing               | 5         | 1.19%   |
| Debian 10                    | 5         | 1.19%   |
| Ubuntu 16.04                 | 4         | 0.95%   |
| Pop!_OS 21.04                | 4         | 0.95%   |
| Linux Mint 20.3              | 4         | 0.95%   |
| Linux Mint 19.2              | 4         | 0.95%   |
| Fedora 35                    | 4         | 0.95%   |
| Fedora 33                    | 4         | 0.95%   |
| Xubuntu 18.04                | 3         | 0.71%   |
| Ubuntu 21.10                 | 3         | 0.71%   |
| Ubuntu 18.10                 | 3         | 0.71%   |
| Pop!_OS 20.04                | 3         | 0.71%   |
| Linux Mint 20                | 3         | 0.71%   |
| Linux Mint 19.3              | 3         | 0.71%   |
| Kubuntu 20.04                | 3         | 0.71%   |
| Fedora 29                    | 3         | 0.71%   |
| Endless 3.7.6                | 3         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 133       | 32.76%  |
| OpenMandriva  | 36        | 8.87%   |
| Linux Mint    | 31        | 7.64%   |
| Fedora        | 28        | 6.9%    |
| Pop!_OS       | 24        | 5.91%   |
| Debian        | 20        | 4.93%   |
| Arch          | 18        | 4.43%   |
| KDE neon      | 15        | 3.69%   |
| Endless       | 14        | 3.45%   |
| Zorin         | 12        | 2.96%   |
| Xubuntu       | 9         | 2.22%   |
| Manjaro       | 9         | 2.22%   |
| Kubuntu       | 8         | 1.97%   |
| openSUSE      | 7         | 1.72%   |
| Ubuntu MATE   | 6         | 1.48%   |
| Clear Linux   | 5         | 1.23%   |
| Elementary    | 4         | 0.99%   |
| MX            | 3         | 0.74%   |
| Kali          | 3         | 0.74%   |
| ArcoLinux     | 3         | 0.74%   |
| UbuntuDDE     | 2         | 0.49%   |
| Reborn OS     | 2         | 0.49%   |
| Lubuntu       | 2         | 0.49%   |
| EndeavourOS   | 2         | 0.49%   |
| CentOS        | 2         | 0.49%   |
| BlackPanther  | 2         | 0.49%   |
| Ubuntu Unity  | 1         | 0.25%   |
| Ubuntu Budgie | 1         | 0.25%   |
| Solus         | 1         | 0.25%   |
| ROSA          | 1         | 0.25%   |
| GNOME OS      | 1         | 0.25%   |
| Garuda Linux  | 1         | 0.25%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 16        | 3.56%   |
| 5.15.0-46-generic        | 10        | 2.22%   |
| 5.16.7-desktop-1omv4003  | 9         | 2%      |
| 6.1.1-desktop-1omv2290   | 8         | 1.78%   |
| 5.4.0-42-generic         | 7         | 1.56%   |
| 5.4.0-48-generic         | 6         | 1.33%   |
| 4.18.0-15-generic        | 6         | 1.33%   |
| 5.3.0-28-generic         | 5         | 1.11%   |
| 5.15.0-56-generic        | 5         | 1.11%   |
| 5.15.0-43-generic        | 5         | 1.11%   |
| 5.8.0-59-generic         | 4         | 0.89%   |
| 5.4.0-59-generic         | 4         | 0.89%   |
| 5.3.0-23-generic         | 4         | 0.89%   |
| 5.15.0-58-generic        | 4         | 0.89%   |
| 5.11.0-40-generic        | 4         | 0.89%   |
| 5.0.0-32-generic         | 4         | 0.89%   |
| 6.0.6-76060006-generic   | 3         | 0.67%   |
| 6.0.12-76060006-generic  | 3         | 0.67%   |
| 5.8.0-63-generic         | 3         | 0.67%   |
| 5.8.0-50-generic         | 3         | 0.67%   |
| 5.8.0-14-generic         | 3         | 0.67%   |
| 5.4.0-66-generic         | 3         | 0.67%   |
| 5.4.0-45-generic         | 3         | 0.67%   |
| 5.4.0-39-generic         | 3         | 0.67%   |
| 5.4.0-37-generic         | 3         | 0.67%   |
| 5.4.0-31-generic         | 3         | 0.67%   |
| 5.3.0-53-generic         | 3         | 0.67%   |
| 5.19.0-76051900-generic  | 3         | 0.67%   |
| 5.17.5-76051705-generic  | 3         | 0.67%   |
| 5.15.0-52-generic        | 3         | 0.67%   |
| 5.13.0-39-generic        | 3         | 0.67%   |
| 5.11.0-43-generic        | 3         | 0.67%   |
| 5.11.0-37-generic        | 3         | 0.67%   |
| 5.0.0-27-generic         | 3         | 0.67%   |
| 6.1.11-200.fc37.x86_64   | 2         | 0.44%   |
| 5.8.14-arch1-1           | 2         | 0.44%   |
| 5.8.0-29-generic         | 2         | 0.44%   |
| 5.6.14-desktop-2bP       | 2         | 0.44%   |
| 5.4.0-81-generic         | 2         | 0.44%   |
| 5.4.0-80-generic         | 2         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 70        | 15.87%  |
| 5.15.0  | 39        | 8.84%   |
| 5.8.0   | 26        | 5.9%    |
| 5.13.0  | 24        | 5.44%   |
| 4.15.0  | 24        | 5.44%   |
| 5.3.0   | 22        | 4.99%   |
| 5.11.0  | 18        | 4.08%   |
| 5.10.14 | 16        | 3.63%   |
| 5.0.0   | 16        | 3.63%   |
| 4.18.0  | 14        | 3.17%   |
| 6.1.1   | 10        | 2.27%   |
| 5.16.7  | 9         | 2.04%   |
| 5.19.0  | 7         | 1.59%   |
| 5.10.0  | 7         | 1.59%   |
| 4.19.0  | 7         | 1.59%   |
| 5.17.5  | 6         | 1.36%   |
| 6.0.12  | 4         | 0.91%   |
| 5.16.0  | 4         | 0.91%   |
| 6.1.12  | 3         | 0.68%   |
| 6.0.6   | 3         | 0.68%   |
| 6.1.11  | 2         | 0.45%   |
| 6.0.0   | 2         | 0.45%   |
| 5.8.14  | 2         | 0.45%   |
| 5.6.14  | 2         | 0.45%   |
| 5.5.7   | 2         | 0.45%   |
| 5.19.16 | 2         | 0.45%   |
| 5.19.13 | 2         | 0.45%   |
| 5.18.5  | 2         | 0.45%   |
| 5.18.0  | 2         | 0.45%   |
| 5.17.3  | 2         | 0.45%   |
| 5.17.0  | 2         | 0.45%   |
| 5.16.9  | 2         | 0.45%   |
| 5.16.19 | 2         | 0.45%   |
| 5.16.13 | 2         | 0.45%   |
| 5.15.2  | 2         | 0.45%   |
| 5.15.14 | 2         | 0.45%   |
| 5.12.0  | 2         | 0.45%   |
| 6.1.8   | 1         | 0.23%   |
| 6.1.5   | 1         | 0.23%   |
| 6.1.3   | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 74        | 17.05%  |
| 5.15    | 49        | 11.29%  |
| 5.8     | 30        | 6.91%   |
| 5.13    | 29        | 6.68%   |
| 5.10    | 27        | 6.22%   |
| 5.3     | 24        | 5.53%   |
| 5.16    | 24        | 5.53%   |
| 4.15    | 24        | 5.53%   |
| 6.1     | 19        | 4.38%   |
| 5.11    | 18        | 4.15%   |
| 5.0     | 17        | 3.92%   |
| 4.18    | 15        | 3.46%   |
| 5.19    | 14        | 3.23%   |
| 5.17    | 13        | 3%      |
| 6.0     | 12        | 2.76%   |
| 5.18    | 7         | 1.61%   |
| 4.19    | 7         | 1.61%   |
| 5.6     | 6         | 1.38%   |
| 5.9     | 5         | 1.15%   |
| 5.5     | 5         | 1.15%   |
| 5.12    | 5         | 1.15%   |
| 5.14    | 3         | 0.69%   |
| 5.7     | 2         | 0.46%   |
| 4.20    | 2         | 0.46%   |
| 5.1     | 1         | 0.23%   |
| 4.4     | 1         | 0.23%   |
| 4.17    | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 392       | 98.99%  |
| i686   | 4         | 1.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 200       | 49.02%  |
| KDE5       | 65        | 15.93%  |
| Unknown    | 51        | 12.5%   |
| X-Cinnamon | 29        | 7.11%   |
| XFCE       | 24        | 5.88%   |
| KDE        | 12        | 2.94%   |
| MATE       | 8         | 1.96%   |
| Budgie     | 5         | 1.23%   |
| Pantheon   | 4         | 0.98%   |
| Deepin     | 3         | 0.74%   |
| Cinnamon   | 2         | 0.49%   |
| Unity      | 1         | 0.25%   |
| LXQt       | 1         | 0.25%   |
| LXDE       | 1         | 0.25%   |
| i3         | 1         | 0.25%   |
| awesome    | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 308       | 76.05%  |
| Wayland | 61        | 15.06%  |
| Unknown | 32        | 7.9%    |
| Tty     | 4         | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 218       | 53.69%  |
| SDDM    | 59        | 14.53%  |
| GDM     | 49        | 12.07%  |
| GDM3    | 40        | 9.85%   |
| LightDM | 29        | 7.14%   |
| TDM     | 9         | 2.22%   |
| XDM     | 1         | 0.25%   |
| Ly      | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 276       | 68.49%  |
| Unknown | 47        | 11.66%  |
| en_GB   | 22        | 5.46%   |
| th_TH   | 18        | 4.47%   |
| de_DE   | 12        | 2.98%   |
| en_SG   | 7         | 1.74%   |
| C       | 7         | 1.74%   |
| fr_FR   | 4         | 0.99%   |
| ru_RU   | 3         | 0.74%   |
| it_IT   | 3         | 0.74%   |
| sv_SE   | 1         | 0.25%   |
| he_IL   | 1         | 0.25%   |
| es_MX   | 1         | 0.25%   |
| de_CH   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 216       | 53.87%  |
| BIOS | 185       | 46.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 321       | 79.65%  |
| Overlay | 37        | 9.18%   |
| Btrfs   | 29        | 7.2%    |
| Unknown | 11        | 2.73%   |
| Xfs     | 3         | 0.74%   |
| Zfs     | 2         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 233       | 58.1%   |
| GPT     | 143       | 35.66%  |
| MBR     | 25        | 6.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 338       | 84.92%  |
| Yes       | 60        | 15.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 262       | 64.69%  |
| Yes       | 143       | 35.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUSTek Computer               | 71        | 17.93%  |
| Lenovo                         | 57        | 14.39%  |
| Acer                           | 44        | 11.11%  |
| Hewlett-Packard                | 39        | 9.85%   |
| Dell                           | 38        | 9.6%    |
| Gigabyte Technology            | 37        | 9.34%   |
| MSI                            | 26        | 6.57%   |
| ASRock                         | 22        | 5.56%   |
| Apple                          | 10        | 2.53%   |
| Unknown                        | 6         | 1.52%   |
| Intel                          | 5         | 1.26%   |
| Samsung Electronics            | 4         | 1.01%   |
| HUAWEI                         | 4         | 1.01%   |
| Fujitsu                        | 3         | 0.76%   |
| Toshiba                        | 2         | 0.51%   |
| Supermicro                     | 2         | 0.51%   |
| Huanan                         | 2         | 0.51%   |
| VIA Technologies               | 1         | 0.25%   |
| Timi                           | 1         | 0.25%   |
| Sony                           | 1         | 0.25%   |
| SmbiosType1_SystemManufacturer | 1         | 0.25%   |
| SHARKBAY                       | 1         | 0.25%   |
| Razer                          | 1         | 0.25%   |
| Pegatron                       | 1         | 0.25%   |
| Packard Bell                   | 1         | 0.25%   |
| OEM                            | 1         | 0.25%   |
| Notebook                       | 1         | 0.25%   |
| MiTAC                          | 1         | 0.25%   |
| Microsoft                      | 1         | 0.25%   |
| Infinix                        | 1         | 0.25%   |
| Hampoo                         | 1         | 0.25%   |
| Framework                      | 1         | 0.25%   |
| Foxconn                        | 1         | 0.25%   |
| Cube                           | 1         | 0.25%   |
| Clevo                          | 1         | 0.25%   |
| Biostar                        | 1         | 0.25%   |
| BESSTAR Tech                   | 1         | 0.25%   |
| AZW                            | 1         | 0.25%   |
| AMI                            | 1         | 0.25%   |
| ALLDOCUBE                      | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                         | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 8         | 2.02%   |
| ASUS All Series                                              | 6         | 1.52%   |
| Lenovo MIIX 520-12IKB 81CG                                   | 3         | 0.76%   |
| Dell OptiPlex 7010                                           | 3         | 0.76%   |
| ASUS P8H61-M LE                                              | 3         | 0.76%   |
| Samsung NC208/NC108                                          | 2         | 0.51%   |
| Lenovo ThinkPad 11e 5th Gen 20LQS00000                       | 2         | 0.51%   |
| Lenovo G460 20041                                            | 2         | 0.51%   |
| HP EliteDesk 800 G1 SFF PC                                   | 2         | 0.51%   |
| Gigabyte Z97X-UD3H-BK                                        | 2         | 0.51%   |
| Gigabyte F2A88XM-HD3P                                        | 2         | 0.51%   |
| Gigabyte F2A68HM-DS2                                         | 2         | 0.51%   |
| Gigabyte B250-HD3                                            | 2         | 0.51%   |
| Dell OptiPlex 3020                                           | 2         | 0.51%   |
| Dell Latitude E6430                                          | 2         | 0.51%   |
| Dell Latitude 3120                                           | 2         | 0.51%   |
| Dell Inspiron 3847                                           | 2         | 0.51%   |
| ASUS X556UQK                                                 | 2         | 0.51%   |
| ASUS X450LN                                                  | 2         | 0.51%   |
| ASUS VivoBook_ASUSLaptop M3500QA_D3500QA                     | 2         | 0.51%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA                      | 2         | 0.51%   |
| ASUS TUF Gaming FX505DT_FX505DT                              | 2         | 0.51%   |
| ASUS H110M-E/M.2                                             | 2         | 0.51%   |
| ASRock B450 Steel Legend                                     | 2         | 0.51%   |
| Apple MacBookAir3,2                                          | 2         | 0.51%   |
| Acer Aspire TC-885                                           | 2         | 0.51%   |
| Acer Aspire F5-573G                                          | 2         | 0.51%   |
| Acer Aspire E5-471G                                          | 2         | 0.51%   |
| Acer Aspire A315-21                                          | 2         | 0.51%   |
| VIA VX900                                                    | 1         | 0.25%   |
| Toshiba Satellite L840                                       | 1         | 0.25%   |
| Toshiba Satellite L645                                       | 1         | 0.25%   |
| Timi TM1701                                                  | 1         | 0.25%   |
| Supermicro X9DRW                                             | 1         | 0.25%   |
| Supermicro AT350 F3                                          | 1         | 0.25%   |
| Sony SVF14N25CXB                                             | 1         | 0.25%   |
| SmbiosType1_SystemManufacturer SmbiosType1_SystemProductName | 1         | 0.25%   |
| Samsung RV418/RV518/RV718                                    | 1         | 0.25%   |
| Samsung R780/R778                                            | 1         | 0.25%   |
| Razer Blade 15 (2022) - RZ09-0421                            | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 29        | 7.32%   |
| Lenovo ThinkPad        | 24        | 6.06%   |
| Lenovo IdeaPad         | 11        | 2.78%   |
| HP Pavilion            | 10        | 2.53%   |
| ASUS VivoBook          | 10        | 2.53%   |
| Dell OptiPlex          | 9         | 2.27%   |
| Dell Latitude          | 8         | 2.02%   |
| Dell Inspiron          | 8         | 2.02%   |
| Unknown                | 8         | 2.02%   |
| HP Laptop              | 6         | 1.52%   |
| ASUS All               | 6         | 1.52%   |
| Lenovo Yoga            | 5         | 1.26%   |
| Dell Precision         | 5         | 1.26%   |
| ASUS TUF               | 5         | 1.26%   |
| ASUS PRIME             | 5         | 1.26%   |
| Lenovo MIIX            | 4         | 1.01%   |
| HP Compaq              | 4         | 1.01%   |
| Dell Vostro            | 4         | 1.01%   |
| ASUS ZenBook           | 4         | 1.01%   |
| ASUS ROG               | 4         | 1.01%   |
| ASRock B450            | 4         | 1.01%   |
| HP ProDesk             | 3         | 0.76%   |
| HP EliteBook           | 3         | 0.76%   |
| ASUS P8H61-M           | 3         | 0.76%   |
| ASUS M5A78L-M          | 3         | 0.76%   |
| Acer Veriton           | 3         | 0.76%   |
| Acer TravelMate        | 3         | 0.76%   |
| Acer Swift             | 3         | 0.76%   |
| Toshiba Satellite      | 2         | 0.51%   |
| Samsung NC208          | 2         | 0.51%   |
| MSI Pro                | 2         | 0.51%   |
| Lenovo ThinkBook       | 2         | 0.51%   |
| Lenovo G460            | 2         | 0.51%   |
| Huanan X79             | 2         | 0.51%   |
| HP Stream              | 2         | 0.51%   |
| HP ENVY                | 2         | 0.51%   |
| HP EliteDesk           | 2         | 0.51%   |
| Gigabyte Z97X-UD3H-BK  | 2         | 0.51%   |
| Gigabyte Z390          | 2         | 0.51%   |
| Gigabyte GA-78LMT-USB3 | 2         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 53        | 13.38%  |
| 2019 | 38        | 9.6%    |
| 2020 | 36        | 9.09%   |
| 2016 | 33        | 8.33%   |
| 2014 | 32        | 8.08%   |
| 2012 | 31        | 7.83%   |
| 2021 | 25        | 6.31%   |
| 2017 | 25        | 6.31%   |
| 2015 | 24        | 6.06%   |
| 2011 | 23        | 5.81%   |
| 2013 | 22        | 5.56%   |
| 2010 | 15        | 3.79%   |
| 2009 | 14        | 3.54%   |
| 2022 | 11        | 2.78%   |
| 2008 | 7         | 1.77%   |
| 2007 | 3         | 0.76%   |
| 2006 | 3         | 0.76%   |
| 2005 | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 205       | 51.77%  |
| Desktop     | 157       | 39.65%  |
| Convertible | 10        | 2.53%   |
| Tablet      | 8         | 2.02%   |
| Mini pc     | 7         | 1.77%   |
| All in one  | 7         | 1.77%   |
| Server      | 2         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 362       | 90.73%  |
| Enabled  | 37        | 9.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 396       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 97        | 24.13%  |
| 3.01-4.0        | 80        | 19.9%   |
| 16.01-24.0      | 80        | 19.9%   |
| 8.01-16.0       | 76        | 18.91%  |
| 32.01-64.0      | 35        | 8.71%   |
| 1.01-2.0        | 18        | 4.48%   |
| 24.01-32.0      | 6         | 1.49%   |
| 64.01-256.0     | 6         | 1.49%   |
| 0.51-1.0        | 2         | 0.5%    |
| More than 256.0 | 1         | 0.25%   |
| 2.01-3.0        | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 156       | 36.53%  |
| 2.01-3.0   | 125       | 29.27%  |
| 4.01-8.0   | 55        | 12.88%  |
| 3.01-4.0   | 51        | 11.94%  |
| 8.01-16.0  | 17        | 3.98%   |
| 0.51-1.0   | 16        | 3.75%   |
| 16.01-24.0 | 4         | 0.94%   |
| 0.01-0.5   | 2         | 0.47%   |
| 24.01-32.0 | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 231       | 56.34%  |
| 2      | 110       | 26.83%  |
| 3      | 40        | 9.76%   |
| 4      | 12        | 2.93%   |
| 0      | 7         | 1.71%   |
| 5      | 6         | 1.46%   |
| 6      | 2         | 0.49%   |
| 51     | 1         | 0.24%   |
| 32     | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 274       | 68.84%  |
| Yes       | 124       | 31.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 329       | 82.66%  |
| No        | 69        | 17.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 309       | 77.44%  |
| No        | 90        | 22.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 237       | 58.81%  |
| No        | 166       | 41.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Thailand | 396       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangkok           | 156       | 37.41%  |
| Chiang Mai        | 34        | 8.15%   |
| Bang Lamung       | 15        | 3.6%    |
| Phuket            | 14        | 3.36%   |
| Khon Kaen         | 13        | 3.12%   |
| Nonthaburi        | 11        | 2.64%   |
| Nakhon Pathom     | 7         | 1.68%   |
| Surin             | 6         | 1.44%   |
| Songkhla          | 6         | 1.44%   |
| Pattaya           | 6         | 1.44%   |
| Surat Thani       | 5         | 1.2%    |
| Nakhon Ratchasima | 5         | 1.2%    |
| Hua Hin           | 5         | 1.2%    |
| Rayong            | 4         | 0.96%   |
| Pak Kret          | 4         | 0.96%   |
| Lat Krabang       | 4         | 0.96%   |
| Lampang           | 4         | 0.96%   |
| Khlong Luang      | 4         | 0.96%   |
| Chon Buri         | 4         | 0.96%   |
| Ban Phan Don      | 4         | 0.96%   |
| Suan Luang        | 3         | 0.72%   |
| Si Racha          | 3         | 0.72%   |
| Phitsanulok       | 3         | 0.72%   |
| Bang Khae         | 3         | 0.72%   |
| Bang Bon          | 3         | 0.72%   |
| Ban Yang Sam Ton  | 3         | 0.72%   |
| Ban Du            | 3         | 0.72%   |
| Samut Prakan      | 2         | 0.48%   |
| Salaya            | 2         | 0.48%   |
| Phetchaburi       | 2         | 0.48%   |
| Phayao            | 2         | 0.48%   |
| Phan              | 2         | 0.48%   |
| Pathum Thani      | 2         | 0.48%   |
| Min Buri          | 2         | 0.48%   |
| Maha Sarakham     | 2         | 0.48%   |
| Krabi             | 2         | 0.48%   |
| Chiang Rai        | 2         | 0.48%   |
| Chanthaburi       | 2         | 0.48%   |
| Bang Bua Thong    | 2         | 0.48%   |
| Ban Nong Sala     | 2         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 118       | 176    | 20.34%  |
| Seagate             | 92        | 132    | 15.86%  |
| Samsung Electronics | 72        | 102    | 12.41%  |
| Toshiba             | 35        | 80     | 6.03%   |
| SanDisk             | 31        | 42     | 5.34%   |
| Kingston            | 31        | 33     | 5.34%   |
| Unknown             | 27        | 39     | 4.66%   |
| Intel               | 16        | 17     | 2.76%   |
| Hitachi             | 13        | 14     | 2.24%   |
| Crucial             | 11        | 11     | 1.9%    |
| SK hynix            | 10        | 17     | 1.72%   |
| HGST                | 9         | 18     | 1.55%   |
| Micron Technology   | 7         | 8      | 1.21%   |
| HS-SSD-C100         | 7         | 12     | 1.21%   |
| Apacer              | 7         | 7      | 1.21%   |
| Transcend           | 6         | 7      | 1.03%   |
| Silicon Motion      | 6         | 8      | 1.03%   |
| Apple               | 6         | 6      | 1.03%   |
| Phison              | 5         | 10     | 0.86%   |
| SPCC                | 4         | 4      | 0.69%   |
| Hikvision           | 4         | 4      | 0.69%   |
| GALAX               | 4         | 4      | 0.69%   |
| China               | 4         | 4      | 0.69%   |
| USB3.0              | 3         | 4      | 0.52%   |
| Plextor             | 3         | 3      | 0.52%   |
| Phison Electronics  | 3         | 4      | 0.52%   |
| KingSpec            | 3         | 5      | 0.52%   |
| JMicron Technology  | 3         | 3      | 0.52%   |
| TO Exter            | 2         | 2      | 0.34%   |
| Pioneer             | 2         | 2      | 0.34%   |
| KIOXIA              | 2         | 4      | 0.34%   |
| Kingmax             | 2         | 4      | 0.34%   |
| Hewlett-Packard     | 2         | 4      | 0.34%   |
| External            | 2         | 2      | 0.34%   |
| Corsair             | 2         | 2      | 0.34%   |
| Colorful            | 2         | 3      | 0.34%   |
| A-DATA Technology   | 2         | 2      | 0.34%   |
| XPG                 | 1         | 1      | 0.17%   |
| WALRAM              | 1         | 1      | 0.17%   |
| Verbatim            | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 8         | 1.26%   |
| Seagate ST500DM002-1BD142 500GB        | 8         | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB         | 8         | 1.26%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 7         | 1.1%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 6         | 0.95%   |
| Unknown MMC Card  64GB                 | 6         | 0.95%   |
| Toshiba MQ01ABD100 1TB                 | 6         | 0.95%   |
| Seagate ST1000LM035-1RK172 1TB         | 6         | 0.95%   |
| Seagate ST1000DM003-1ER162 1TB         | 6         | 0.95%   |
| Kingston SA400S37240G 240GB SSD        | 6         | 0.95%   |
| WDC WD10EZEX-00WN4A0 1TB               | 5         | 0.79%   |
| Unknown SD/MMC/MS PRO 16GB             | 5         | 0.79%   |
| Toshiba MQ04ABF100 1TB                 | 5         | 0.79%   |
| Seagate ST500LT012-1DG142 500GB        | 5         | 0.79%   |
| Kingston SUV400S37120G 120GB SSD       | 5         | 0.79%   |
| Crucial CT500MX500SSD1 500GB           | 5         | 0.79%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 4         | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB               | 4         | 0.63%   |
| Toshiba DT01ACA100 1TB                 | 4         | 0.63%   |
| Seagate ST2000VX008-2E3164 2TB         | 4         | 0.63%   |
| Seagate ST1000LM049-2GH172 1TB         | 4         | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 4         | 0.63%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB     | 4         | 0.63%   |
| SanDisk NVMe SSD Drive 250GB           | 4         | 0.63%   |
| SanDisk NVMe SSD Drive 1TB             | 4         | 0.63%   |
| Samsung HD103SJ 1TB                    | 4         | 0.63%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 3         | 0.47%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 3         | 0.47%   |
| WDC WD20EZAZ-00GGJB0 2TB               | 3         | 0.47%   |
| WDC WD10SPZX-21Z10T0 1TB               | 3         | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.47%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB     | 3         | 0.47%   |
| USB3.0 Super Speed 960GB               | 3         | 0.47%   |
| Toshiba MQ01ABF032 320GB               | 3         | 0.47%   |
| SK hynix HFM512GD3JX013N 512GB         | 3         | 0.47%   |
| Seagate ST3500418AS 500GB              | 3         | 0.47%   |
| SanDisk SDSSDA120G 120GB               | 3         | 0.47%   |
| Samsung SSD 970 EVO Plus 1TB           | 3         | 0.47%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 0.47%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB | 3         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 91        | 131    | 36.11%  |
| WDC                 | 82        | 118    | 32.54%  |
| Toshiba             | 29        | 73     | 11.51%  |
| Hitachi             | 13        | 14     | 5.16%   |
| Samsung Electronics | 12        | 18     | 4.76%   |
| HGST                | 9         | 18     | 3.57%   |
| Unknown             | 6         | 11     | 2.38%   |
| USB3.0              | 3         | 4      | 1.19%   |
| JMicron Technology  | 2         | 2      | 0.79%   |
| Apple               | 2         | 2      | 0.79%   |
| Pioneer             | 1         | 1      | 0.4%    |
| Hewlett-Packard     | 1         | 3      | 0.4%    |
| Fujitsu             | 1         | 2      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 30        | 41     | 17.96%  |
| Samsung Electronics | 26        | 37     | 15.57%  |
| Kingston            | 20        | 21     | 11.98%  |
| SanDisk             | 12        | 18     | 7.19%   |
| Crucial             | 11        | 11     | 6.59%   |
| Apacer              | 7         | 7      | 4.19%   |
| Intel               | 6         | 6      | 3.59%   |
| SPCC                | 4         | 4      | 2.4%    |
| GALAX               | 4         | 4      | 2.4%    |
| China               | 4         | 4      | 2.4%    |
| Apple               | 4         | 4      | 2.4%    |
| Transcend           | 3         | 4      | 1.8%    |
| SK hynix            | 3         | 4      | 1.8%    |
| Plextor             | 3         | 3      | 1.8%    |
| Micron Technology   | 3         | 4      | 1.8%    |
| KingSpec            | 3         | 5      | 1.8%    |
| Hikvision           | 3         | 3      | 1.8%    |
| TO Exter            | 2         | 2      | 1.2%    |
| Kingmax             | 2         | 4      | 1.2%    |
| WALRAM              | 1         | 1      | 0.6%    |
| Verbatim            | 1         | 1      | 0.6%    |
| Teelkoou            | 1         | 1      | 0.6%    |
| Team                | 1         | 1      | 0.6%    |
| PNY                 | 1         | 2      | 0.6%    |
| Pioneer             | 1         | 1      | 0.6%    |
| OCZ                 | 1         | 1      | 0.6%    |
| LITEON              | 1         | 2      | 0.6%    |
| Lexar               | 1         | 1      | 0.6%    |
| HS-SSD-E100         | 1         | 1      | 0.6%    |
| Hewlett-Packard     | 1         | 1      | 0.6%    |
| FORESEE             | 1         | 1      | 0.6%    |
| DGM                 | 1         | 1      | 0.6%    |
| Corsair             | 1         | 1      | 0.6%    |
| Colorful            | 1         | 2      | 0.6%    |
| Acer                | 1         | 3      | 0.6%    |
| A-DATA Technology   | 1         | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 209       | 397    | 40.58%  |
| SSD     | 143       | 208    | 27.77%  |
| NVMe    | 127       | 174    | 24.66%  |
| MMC     | 21        | 28     | 4.08%   |
| Unknown | 15        | 20     | 2.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 295       | 596    | 63.71%  |
| NVMe | 125       | 172    | 27%     |
| SAS  | 22        | 31     | 4.75%   |
| MMC  | 21        | 28     | 4.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 202       | 306    | 53.3%   |
| 0.51-1.0   | 130       | 174    | 34.3%   |
| 1.01-2.0   | 30        | 35     | 7.92%   |
| 3.01-4.0   | 9         | 56     | 2.37%   |
| 2.01-3.0   | 3         | 8      | 0.79%   |
| 4.01-10.0  | 3         | 15     | 0.79%   |
| 10.01-20.0 | 2         | 11     | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 96        | 23.24%  |
| 251-500        | 85        | 20.58%  |
| 501-1000       | 67        | 16.22%  |
| 1-20           | 40        | 9.69%   |
| 1001-2000      | 31        | 7.51%   |
| 51-100         | 30        | 7.26%   |
| 21-50          | 25        | 6.05%   |
| More than 3000 | 15        | 3.63%   |
| 2001-3000      | 15        | 3.63%   |
| Unknown        | 9         | 2.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 172       | 40.28%  |
| 21-50          | 71        | 16.63%  |
| 101-250        | 53        | 12.41%  |
| 51-100         | 42        | 9.84%   |
| 251-500        | 31        | 7.26%   |
| 501-1000       | 25        | 5.85%   |
| 1001-2000      | 15        | 3.51%   |
| Unknown        | 9         | 2.11%   |
| More than 3000 | 7         | 1.64%   |
| 2001-3000      | 2         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD2002FAEX-007BA0 2TB                | 2         | 2      | 5.88%   |
| Toshiba MQ01ABD100 1TB                   | 2         | 2      | 5.88%   |
| Seagate ST500DM002-1BD14 500GB           | 2         | 3      | 5.88%   |
| Seagate ST1000LM049-2GH172 1TB           | 2         | 2      | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 5.88%   |
| Samsung Electronics SSD 830 Series 128GB | 2         | 2      | 5.88%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1         | 1      | 2.94%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 2      | 2.94%   |
| WDC WD10PURX-64E5EY0 1TB                 | 1         | 1      | 2.94%   |
| WDC WD10EZEX-00WN4A0 1TB                 | 1         | 1      | 2.94%   |
| WDC WD1002FAEX-00Y9A0 1TB                | 1         | 1      | 2.94%   |
| USB3.0 Super Speed 960GB                 | 1         | 2      | 2.94%   |
| Toshiba HDWL110 1TB                      | 1         | 1      | 2.94%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 2.94%   |
| Seagate ST9120822AS 120GB                | 1         | 1      | 2.94%   |
| Seagate ST500LM000-SSHD-8GB              | 1         | 1      | 2.94%   |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 1      | 2.94%   |
| Seagate ST3500418AS 500GB                | 1         | 2      | 2.94%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB      | 1         | 1      | 2.94%   |
| Seagate ST1000LM014-1EJ164 1TB           | 1         | 1      | 2.94%   |
| SanDisk SDSSDX240GG25 240GB              | 1         | 1      | 2.94%   |
| Samsung Electronics HM160HI 160GB        | 1         | 2      | 2.94%   |
| Samsung Electronics HD253GJ 250GB        | 1         | 1      | 2.94%   |
| Samsung Electronics HD103SJ 1TB          | 1         | 1      | 2.94%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD  | 1         | 1      | 2.94%   |
| Intel SSDSC2KF256H6 SATA 256GB           | 1         | 1      | 2.94%   |
| HGST HTS725050A7E630 500GB               | 1         | 1      | 2.94%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 39.39%  |
| WDC                 | 6         | 8      | 18.18%  |
| Samsung Electronics | 5         | 6      | 15.15%  |
| Toshiba             | 3         | 3      | 9.09%   |
| HGST                | 2         | 2      | 6.06%   |
| USB3.0              | 1         | 2      | 3.03%   |
| SanDisk             | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 46.43%  |
| WDC                 | 6         | 8      | 21.43%  |
| Toshiba             | 3         | 3      | 10.71%  |
| Samsung Electronics | 3         | 4      | 10.71%  |
| HGST                | 2         | 2      | 7.14%   |
| USB3.0              | 1         | 2      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 34     | 84.38%  |
| SSD  | 5         | 5      | 15.63%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB  | 1         | 1      | 50%     |
| Samsung Electronics HD103SJ 1TB | 1         | 1      | 50%     |

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
| Detected | 263       | 508    | 61.88%  |
| Works    | 130       | 278    | 30.59%  |
| Malfunc  | 30        | 39     | 7.06%   |
| Failed   | 2         | 2      | 0.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 252       | 51.85%  |
| AMD                          | 76        | 15.64%  |
| Samsung Electronics          | 41        | 8.44%   |
| SanDisk                      | 34        | 7%      |
| Nvidia                       | 11        | 2.26%   |
| Kingston Technology Company  | 11        | 2.26%   |
| ASMedia Technology           | 10        | 2.06%   |
| Phison Electronics           | 9         | 1.85%   |
| SK hynix                     | 7         | 1.44%   |
| Silicon Motion               | 7         | 1.44%   |
| Toshiba America Info Systems | 6         | 1.23%   |
| Micron Technology            | 4         | 0.82%   |
| VIA Technologies             | 3         | 0.62%   |
| LSI Logic / Symbios Logic    | 3         | 0.62%   |
| KIOXIA                       | 2         | 0.41%   |
| Broadcom / LSI               | 2         | 0.41%   |
| ADATA Technology             | 2         | 0.41%   |
| Transcend                    | 1         | 0.21%   |
| Realtek Semiconductor        | 1         | 0.21%   |
| Micron/Crucial Technology    | 1         | 0.21%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.21%   |
| Lite-On Technology           | 1         | 0.21%   |
| JMicron Technology           | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 55        | 10%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 25        | 4.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 22        | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 22        | 4%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 17        | 3.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 14        | 2.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 13        | 2.36%   |
| AMD 400 Series Chipset SATA Controller                                           | 13        | 2.36%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 11        | 2%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 10        | 1.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 9         | 1.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 9         | 1.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 1.64%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 8         | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 8         | 1.45%   |
| Intel SSD 660P Series                                                            | 7         | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 1.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 7         | 1.27%   |
| SanDisk Non-Volatile memory controller                                           | 6         | 1.09%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.09%   |
| Intel SATA Controller [RAID mode]                                                | 6         | 1.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 6         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 6         | 1.09%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 5         | 0.91%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 5         | 0.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 0.91%   |
| Phison E12 NVMe Controller                                                       | 5         | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 0.91%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 0.91%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4         | 0.73%   |
| Nvidia MCP61 SATA Controller                                                     | 4         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 288       | 58.66%  |
| NVMe | 129       | 26.27%  |
| IDE  | 47        | 9.57%   |
| RAID | 23        | 4.68%   |
| SAS  | 2         | 0.41%   |
| SCSI | 2         | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 300       | 75.76%  |
| AMD          | 95        | 23.99%  |
| CentaurHauls | 1         | 0.25%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 2.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 2.01%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 1.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.26%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 5         | 1.26%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 5         | 1.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.01%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 4         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.01%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 4         | 1.01%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.01%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 1.01%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 1.01%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.75%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 3         | 0.75%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.75%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 3         | 0.75%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 0.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.75%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 0.75%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.75%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.75%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.75%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 0.75%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 3         | 0.75%   |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G  | 3         | 0.75%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.5%    |
| Intel Pentium CPU N3700 @ 1.60GHz             | 2         | 0.5%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.5%    |
| Intel Core i9-9900K CPU @ 3.60GHz             | 2         | 0.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.5%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.5%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.5%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 84        | 21.16%  |
| Intel Core i7           | 79        | 19.9%   |
| Intel Core i3           | 40        | 10.08%  |
| AMD Ryzen 5             | 26        | 6.55%   |
| AMD Ryzen 7             | 17        | 4.28%   |
| Intel Celeron           | 16        | 4.03%   |
| Other                   | 13        | 3.27%   |
| Intel Pentium           | 13        | 3.27%   |
| Intel Xeon              | 12        | 3.02%   |
| Intel Core 2 Duo        | 12        | 3.02%   |
| Intel Atom              | 12        | 3.02%   |
| AMD Ryzen 9             | 7         | 1.76%   |
| AMD Ryzen 3             | 7         | 1.76%   |
| AMD FX                  | 5         | 1.26%   |
| AMD Athlon II X2        | 5         | 1.26%   |
| AMD A4                  | 5         | 1.26%   |
| AMD A10                 | 5         | 1.26%   |
| Intel Core i9           | 4         | 1.01%   |
| Intel Core 2 Quad       | 4         | 1.01%   |
| Intel Pentium Silver    | 3         | 0.76%   |
| Intel Pentium Dual-Core | 3         | 0.76%   |
| Intel Pentium Dual      | 2         | 0.5%    |
| Intel Core m3           | 2         | 0.5%    |
| AMD Ryzen 7 PRO         | 2         | 0.5%    |
| AMD Phenom II X6        | 2         | 0.5%    |
| AMD Phenom II X4        | 2         | 0.5%    |
| AMD Athlon 64 X2        | 2         | 0.5%    |
| AMD Athlon              | 2         | 0.5%    |
| AMD A6                  | 2         | 0.5%    |
| Intel Pentium 4         | 1         | 0.25%   |
| CentaurHauls VIA Eden   | 1         | 0.25%   |
| AMD Turion 64 X2 Mobile | 1         | 0.25%   |
| AMD Ryzen 5 PRO         | 1         | 0.25%   |
| AMD Ryzen 3 PRO         | 1         | 0.25%   |
| AMD Phenom II X3        | 1         | 0.25%   |
| AMD E2                  | 1         | 0.25%   |
| AMD E1                  | 1         | 0.25%   |
| AMD A8                  | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 161       | 40.45%  |
| 2      | 146       | 36.68%  |
| 6      | 42        | 10.55%  |
| 8      | 32        | 8.04%   |
| 1      | 5         | 1.26%   |
| 12     | 3         | 0.75%   |
| 16     | 2         | 0.5%    |
| 14     | 2         | 0.5%    |
| 3      | 2         | 0.5%    |
| 40     | 1         | 0.25%   |
| 24     | 1         | 0.25%   |
| 10     | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 391       | 98.74%  |
| 2      | 5         | 1.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 275       | 68.92%  |
| 1      | 124       | 31.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 389       | 98.23%  |
| Unknown        | 6         | 1.52%   |
| 32-bit         | 1         | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 23.41%  |
| 0x306c3    | 22        | 5.37%   |
| 0x306a9    | 20        | 4.88%   |
| 0x206a7    | 20        | 4.88%   |
| 0x906ea    | 13        | 3.17%   |
| 0x506e3    | 13        | 3.17%   |
| 0x806ea    | 12        | 2.93%   |
| 0x1067a    | 12        | 2.93%   |
| 0x806e9    | 10        | 2.44%   |
| 0x906e9    | 9         | 2.2%    |
| 0x806ec    | 9         | 2.2%    |
| 0x40651    | 9         | 2.2%    |
| 0x20655    | 8         | 1.95%   |
| 0x806c1    | 7         | 1.71%   |
| 0x406c4    | 7         | 1.71%   |
| 0x406e3    | 6         | 1.46%   |
| 0x406c3    | 6         | 1.46%   |
| 0x08108102 | 6         | 1.46%   |
| 0x30678    | 5         | 1.22%   |
| 0x0a50000c | 5         | 1.22%   |
| 0x0810100b | 5         | 1.22%   |
| 0x706a8    | 4         | 0.98%   |
| 0x706a1    | 4         | 0.98%   |
| 0x20652    | 4         | 0.98%   |
| 0x0800820d | 4         | 0.98%   |
| 0x06001119 | 4         | 0.98%   |
| 0x010000c8 | 4         | 0.98%   |
| 0xa0655    | 3         | 0.73%   |
| 0xa0652    | 3         | 0.73%   |
| 0x906ec    | 3         | 0.73%   |
| 0x906c0    | 3         | 0.73%   |
| 0x6fd      | 3         | 0.73%   |
| 0x406f1    | 3         | 0.73%   |
| 0x106e5    | 3         | 0.73%   |
| 0x106ca    | 3         | 0.73%   |
| 0x08701021 | 3         | 0.73%   |
| 0x08600104 | 3         | 0.73%   |
| 0x08108109 | 3         | 0.73%   |
| 0x06006704 | 3         | 0.73%   |
| 0x506c9    | 2         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 71        | 17.88%  |
| Haswell          | 43        | 10.83%  |
| Skylake          | 28        | 7.05%   |
| IvyBridge        | 27        | 6.8%    |
| SandyBridge      | 22        | 5.54%   |
| Silvermont       | 21        | 5.29%   |
| Zen+             | 19        | 4.79%   |
| Penryn           | 18        | 4.53%   |
| Zen 2            | 17        | 4.28%   |
| Westmere         | 13        | 3.27%   |
| CometLake        | 12        | 3.02%   |
| Zen 3            | 11        | 2.77%   |
| Zen              | 10        | 2.52%   |
| TigerLake        | 10        | 2.52%   |
| K10              | 9         | 2.27%   |
| Goldmont plus    | 9         | 2.27%   |
| Unknown          | 9         | 2.27%   |
| Piledriver       | 8         | 2.02%   |
| Excavator        | 5         | 1.26%   |
| Core             | 4         | 1.01%   |
| Broadwell        | 4         | 1.01%   |
| Bonnell          | 4         | 1.01%   |
| Tremont          | 3         | 0.76%   |
| Nehalem          | 3         | 0.76%   |
| K8 Hammer        | 3         | 0.76%   |
| IceLake          | 3         | 0.76%   |
| Steamroller      | 2         | 0.5%    |
| Puma             | 2         | 0.5%    |
| Goldmont         | 2         | 0.5%    |
| NetBurst         | 1         | 0.25%   |
| K10 Llano        | 1         | 0.25%   |
| Jaguar           | 1         | 0.25%   |
| Bobcat           | 1         | 0.25%   |
| Alderlake Hybrid | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 222       | 44.4%   |
| Nvidia                     | 168       | 33.6%   |
| AMD                        | 105       | 21%     |
| VIA Technologies           | 2         | 0.4%    |
| Matrox Electronics Systems | 1         | 0.2%    |
| ATI Technologies           | 1         | 0.2%    |
| ASPEED Technology          | 1         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 3.28%   |
| Intel UHD Graphics 620                                                                   | 15        | 2.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 2.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 2.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 2.7%    |
| Intel HD Graphics 530                                                                    | 13        | 2.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 2.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 1.93%   |
| Intel HD Graphics 620                                                                    | 10        | 1.93%   |
| AMD Renoir                                                                               | 9         | 1.74%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 1.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 1.54%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 1.54%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 1.35%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 6         | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.16%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6         | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.16%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 0.97%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.97%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5         | 0.97%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.97%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 0.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 0.97%   |
| Intel HD Graphics 630                                                                    | 5         | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.77%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.77%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 4         | 0.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 0.77%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.58%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 136       | 33.66%  |
| 1 x Nvidia           | 77        | 19.06%  |
| 1 x AMD              | 75        | 18.56%  |
| Intel + Nvidia       | 73        | 18.07%  |
| AMD + Nvidia         | 14        | 3.47%   |
| 2 x AMD              | 10        | 2.48%   |
| Intel + AMD          | 9         | 2.23%   |
| 1 x VIA              | 2         | 0.5%    |
| Intel + 2 x Nvidia   | 2         | 0.5%    |
| 3 x Nvidia           | 1         | 0.25%   |
| 2 x Nvidia           | 1         | 0.25%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.25%   |
| 1 x Matrox           | 1         | 0.25%   |
| 1 x ASPEED           | 1         | 0.25%   |
| AMD + 2 x Nvidia     | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 313       | 77.28%  |
| Proprietary | 81        | 20%     |
| Unknown     | 11        | 2.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 219       | 53.41%  |
| 1.01-2.0   | 57        | 13.9%   |
| 3.01-4.0   | 41        | 10%     |
| 0.01-0.5   | 41        | 10%     |
| 0.51-1.0   | 27        | 6.59%   |
| 7.01-8.0   | 13        | 3.17%   |
| 5.01-6.0   | 7         | 1.71%   |
| 8.01-16.0  | 2         | 0.49%   |
| 4.01-5.0   | 1         | 0.24%   |
| 2.01-3.0   | 1         | 0.24%   |
| 16.01-24.0 | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 63        | 14.72%  |
| AU Optronics            | 56        | 13.08%  |
| Chimei Innolux          | 39        | 9.11%   |
| BOE                     | 34        | 7.94%   |
| LG Display              | 32        | 7.48%   |
| Goldstar                | 32        | 7.48%   |
| Acer                    | 32        | 7.48%   |
| Dell                    | 22        | 5.14%   |
| Hewlett-Packard         | 14        | 3.27%   |
| AOC                     | 11        | 2.57%   |
| PANDA                   | 9         | 2.1%    |
| Lenovo                  | 8         | 1.87%   |
| Apple                   | 8         | 1.87%   |
| Sharp                   | 7         | 1.64%   |
| BenQ                    | 7         | 1.64%   |
| ViewSonic               | 5         | 1.17%   |
| LG Electronics          | 4         | 0.93%   |
| InfoVision              | 3         | 0.7%    |
| Chi Mei Optoelectronics | 3         | 0.7%    |
| Unknown (XXX)           | 2         | 0.47%   |
| Philips                 | 2         | 0.47%   |
| MStar                   | 2         | 0.47%   |
| Mi                      | 2         | 0.47%   |
| ASUSTek Computer        | 2         | 0.47%   |
| Ancor Communications    | 2         | 0.47%   |
| Toshiba                 | 1         | 0.23%   |
| TCL                     | 1         | 0.23%   |
| Sony                    | 1         | 0.23%   |
| SKY                     | 1         | 0.23%   |
| SGT                     | 1         | 0.23%   |
| RTK                     | 1         | 0.23%   |
| Quanta Display          | 1         | 0.23%   |
| Panasonic               | 1         | 0.23%   |
| NEC Computers           | 1         | 0.23%   |
| MSI                     | 1         | 0.23%   |
| MIG                     | 1         | 0.23%   |
| Microstep               | 1         | 0.23%   |
| LPL                     | 1         | 0.23%   |
| Lenovo Group Limited    | 1         | 0.23%   |
| ITE                     | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 4         | 0.91%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 3         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.68%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.68%   |
| Acer K222HQL ACR0512 1920x1080 476x268mm 21.5-inch                    | 3         | 0.68%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                | 2         | 0.46%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch  | 2         | 0.46%   |
| Samsung Electronics SyncMaster SAM0366 1280x1024 338x270mm 17.0-inch  | 2         | 0.46%   |
| Samsung Electronics SME1920 SAM06B7 1360x768 410x230mm 18.5-inch      | 2         | 0.46%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2         | 0.46%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2         | 0.46%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 2         | 0.46%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.46%   |
| MStar Demo MST0030 1920x540 708x398mm 32.0-inch                       | 2         | 0.46%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2         | 0.46%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 2         | 0.46%   |
| LG Display LCD Monitor LGD0454 1366x768 310x174mm 14.0-inch           | 2         | 0.46%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 2         | 0.46%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 2         | 0.46%   |
| Lenovo AIO PC LEN2000 1920x1080 480x270mm 21.7-inch                   | 2         | 0.46%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 2         | 0.46%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.46%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2         | 0.46%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 2         | 0.46%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.46%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 0.46%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                  | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 190       | 46%     |
| 1366x768 (WXGA)    | 95        | 23%     |
| 3840x2160 (4K)     | 26        | 6.3%    |
| 1600x900 (HD+)     | 21        | 5.08%   |
| 1440x900 (WXGA+)   | 14        | 3.39%   |
| 2560x1440 (QHD)    | 13        | 3.15%   |
| 1280x1024 (SXGA)   | 9         | 2.18%   |
| 1680x1050 (WSXGA+) | 8         | 1.94%   |
| 2560x1080          | 6         | 1.45%   |
| Unknown            | 4         | 0.97%   |
| 2560x1600          | 3         | 0.73%   |
| 1920x1200 (WUXGA)  | 3         | 0.73%   |
| 1360x768           | 3         | 0.73%   |
| 1280x800 (WXGA)    | 3         | 0.73%   |
| 3840x1080          | 2         | 0.48%   |
| 3840x2400          | 1         | 0.24%   |
| 3440x1440          | 1         | 0.24%   |
| 2880x1800          | 1         | 0.24%   |
| 2736x1824          | 1         | 0.24%   |
| 2732x768           | 1         | 0.24%   |
| 2256x1504          | 1         | 0.24%   |
| 2160x1440          | 1         | 0.24%   |
| 1920x515           | 1         | 0.24%   |
| 1920x1280          | 1         | 0.24%   |
| 1600x1200          | 1         | 0.24%   |
| 1280x720 (HD)      | 1         | 0.24%   |
| 1024x768 (XGA)     | 1         | 0.24%   |
| 1024x600           | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 89        | 20.75%  |
| 14      | 44        | 10.26%  |
| 13      | 44        | 10.26%  |
| 23      | 33        | 7.69%   |
| 21      | 27        | 6.29%   |
| 24      | 24        | 5.59%   |
| 27      | 23        | 5.36%   |
| Unknown | 21        | 4.9%    |
| 18      | 18        | 4.2%    |
| 19      | 17        | 3.96%   |
| 17      | 16        | 3.73%   |
| 20      | 14        | 3.26%   |
| 11      | 13        | 3.03%   |
| 22      | 6         | 1.4%    |
| 34      | 5         | 1.17%   |
| 31      | 5         | 1.17%   |
| 12      | 5         | 1.17%   |
| 84      | 4         | 0.93%   |
| 16      | 4         | 0.93%   |
| 72      | 2         | 0.47%   |
| 54      | 2         | 0.47%   |
| 52      | 2         | 0.47%   |
| 47      | 2         | 0.47%   |
| 26      | 2         | 0.47%   |
| 60      | 1         | 0.23%   |
| 46      | 1         | 0.23%   |
| 40      | 1         | 0.23%   |
| 39      | 1         | 0.23%   |
| 29      | 1         | 0.23%   |
| 10      | 1         | 0.23%   |
| 8       | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 162       | 38.39%  |
| 501-600     | 78        | 18.48%  |
| 401-500     | 78        | 18.48%  |
| 201-300     | 39        | 9.24%   |
| Unknown     | 21        | 4.98%   |
| 351-400     | 17        | 4.03%   |
| 1001-1500   | 8         | 1.9%    |
| 601-700     | 6         | 1.42%   |
| 701-800     | 5         | 1.18%   |
| 1501-2000   | 5         | 1.18%   |
| 801-900     | 2         | 0.47%   |
| 101-200     | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 309       | 80.26%  |
| 16/10   | 36        | 9.35%   |
| Unknown | 18        | 4.68%   |
| 5/4     | 9         | 2.34%   |
| 3/2     | 5         | 1.3%    |
| 21/9    | 5         | 1.3%    |
| 4/3     | 2         | 0.52%   |
| 3.73    | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 89        | 20.89%  |
| 201-250        | 74        | 17.37%  |
| 81-90          | 72        | 16.9%   |
| 151-200        | 40        | 9.39%   |
| 301-350        | 25        | 5.87%   |
| Unknown        | 21        | 4.93%   |
| 141-150        | 19        | 4.46%   |
| 71-80          | 16        | 3.76%   |
| 51-60          | 14        | 3.29%   |
| 351-500        | 11        | 2.58%   |
| 121-130        | 11        | 2.58%   |
| More than 1000 | 10        | 2.35%   |
| 251-300        | 7         | 1.64%   |
| 61-70          | 5         | 1.17%   |
| 501-1000       | 5         | 1.17%   |
| 131-140        | 3         | 0.7%    |
| 111-120        | 2         | 0.47%   |
| 1-40           | 1         | 0.23%   |
| 91-100         | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 133       | 32.13%  |
| 121-160       | 108       | 26.09%  |
| 101-120       | 105       | 25.36%  |
| 161-240       | 31        | 7.49%   |
| Unknown       | 21        | 5.07%   |
| 1-50          | 9         | 2.17%   |
| More than 240 | 7         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 322       | 79.12%  |
| 2     | 62        | 15.23%  |
| 0     | 17        | 4.18%   |
| 3     | 6         | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 237       | 39.24%  |
| Intel                             | 166       | 27.48%  |
| Qualcomm Atheros                  | 74        | 12.25%  |
| Broadcom                          | 38        | 6.29%   |
| Ralink Technology                 | 12        | 1.99%   |
| MediaTek                          | 10        | 1.66%   |
| D-Link                            | 8         | 1.32%   |
| ASIX Electronics                  | 8         | 1.32%   |
| Nvidia                            | 7         | 1.16%   |
| TP-Link                           | 6         | 0.99%   |
| Ralink                            | 4         | 0.66%   |
| D-Link System                     | 4         | 0.66%   |
| Broadcom Limited                  | 4         | 0.66%   |
| Samsung Electronics               | 3         | 0.5%    |
| Xiaomi                            | 2         | 0.33%   |
| VIA Technologies                  | 2         | 0.33%   |
| Mercucys                          | 2         | 0.33%   |
| Marvell Technology Group          | 2         | 0.33%   |
| Huawei Technologies               | 2         | 0.33%   |
| Ericsson Business Mobile Networks | 2         | 0.33%   |
| ASUSTek Computer                  | 2         | 0.33%   |
| vivo                              | 1         | 0.17%   |
| Qualcomm Atheros Communications   | 1         | 0.17%   |
| Qualcomm                          | 1         | 0.17%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.17%   |
| Lenovo                            | 1         | 0.17%   |
| JMicron Technology                | 1         | 0.17%   |
| Edimax Technology                 | 1         | 0.17%   |
| BUFFALO                           | 1         | 0.17%   |
| Aquantia                          | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 185       | 27.09%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 2.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 2.34%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 1.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 1.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 1.46%   |
| Intel Wireless-AC 9260                                            | 9         | 1.32%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 1.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.02%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.02%   |
| Intel Wireless 8260                                               | 7         | 1.02%   |
| Intel Wireless 7265                                               | 7         | 1.02%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.02%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                   | 6         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.88%   |
| Intel Wireless 3160                                               | 6         | 0.88%   |
| Intel I211 Gigabit Network Connection                             | 6         | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.73%   |
| Intel Wireless 3165                                               | 5         | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.73%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.59%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 4         | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 125       | 38.58%  |
| Qualcomm Atheros                | 63        | 19.44%  |
| Realtek Semiconductor           | 56        | 17.28%  |
| Broadcom                        | 25        | 7.72%   |
| Ralink Technology               | 12        | 3.7%    |
| MediaTek                        | 10        | 3.09%   |
| D-Link                          | 8         | 2.47%   |
| TP-Link                         | 6         | 1.85%   |
| Ralink                          | 4         | 1.23%   |
| Broadcom Limited                | 4         | 1.23%   |
| Mercucys                        | 2         | 0.62%   |
| D-Link System                   | 2         | 0.62%   |
| ASUSTek Computer                | 2         | 0.62%   |
| Qualcomm Atheros Communications | 1         | 0.31%   |
| Qualcomm                        | 1         | 0.31%   |
| Marvell Technology Group        | 1         | 0.31%   |
| Edimax Technology               | 1         | 0.31%   |
| BUFFALO                         | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 5.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 16        | 4.92%   |
| Intel Wi-Fi 6 AX200                                            | 13        | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 3.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 12        | 3.69%   |
| Intel Wireless-AC 9260                                         | 9         | 2.77%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 2.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7         | 2.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.15%   |
| Intel Wireless 8265 / 8275                                     | 7         | 2.15%   |
| Intel Wireless 8260                                            | 7         | 2.15%   |
| Intel Wireless 7265                                            | 7         | 2.15%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 2.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.85%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.85%   |
| Intel Wireless 3160                                            | 6         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 1.85%   |
| Intel Wireless 3165                                            | 5         | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 1.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 1.23%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 4         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 1.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 1.23%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]  | 4         | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.92%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 0.92%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 0.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 0.92%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 0.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 0.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.62%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 213       | 61.56%  |
| Intel                         | 69        | 19.94%  |
| Broadcom                      | 18        | 5.2%    |
| Qualcomm Atheros              | 16        | 4.62%   |
| ASIX Electronics              | 8         | 2.31%   |
| Nvidia                        | 7         | 2.02%   |
| Samsung Electronics           | 3         | 0.87%   |
| Xiaomi                        | 2         | 0.58%   |
| VIA Technologies              | 2         | 0.58%   |
| D-Link System                 | 2         | 0.58%   |
| OnePlus Technology (Shenzhen) | 1         | 0.29%   |
| Marvell Technology Group      | 1         | 0.29%   |
| Lenovo                        | 1         | 0.29%   |
| JMicron Technology            | 1         | 0.29%   |
| Huawei Technologies           | 1         | 0.29%   |
| Aquantia                      | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 185       | 52.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 4.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.82%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 1.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.69%   |
| Intel I211 Gigabit Network Connection                             | 6         | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.41%   |
| Intel Ethernet Connection I217-V                                  | 5         | 1.41%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.13%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 1.13%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.85%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.85%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.56%   |
| Nvidia MCP73 Ethernet                                             | 2         | 0.56%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.56%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.56%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.56%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.56%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.56%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.56%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 2         | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.28%   |
| Xiaomi 100Mbps Network Card Adapter                               | 1         | 0.28%   |
| VIA VT6120/VT6121/VT6122 Gigabit Ethernet Adapter                 | 1         | 0.28%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 328       | 51.17%  |
| WiFi     | 309       | 48.21%  |
| Modem    | 3         | 0.47%   |
| Unknown  | 1         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 261       | 63.66%  |
| Ethernet | 149       | 36.34%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 204       | 51.26%  |
| 1     | 179       | 44.97%  |
| 0     | 8         | 2.01%   |
| 3     | 4         | 1.01%   |
| 4     | 2         | 0.5%    |
| 5     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 311       | 76.23%  |
| Yes  | 97        | 23.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 100       | 41.67%  |
| Cambridge Silicon Radio         | 21        | 8.75%   |
| IMC Networks                    | 20        | 8.33%   |
| Lite-On Technology              | 19        | 7.92%   |
| Realtek Semiconductor           | 17        | 7.08%   |
| Qualcomm Atheros Communications | 12        | 5%      |
| Apple                           | 10        | 4.17%   |
| Broadcom                        | 9         | 3.75%   |
| Foxconn / Hon Hai               | 7         | 2.92%   |
| MediaTek                        | 4         | 1.67%   |
| Dell                            | 4         | 1.67%   |
| ASUSTek Computer                | 4         | 1.67%   |
| Foxconn International           | 3         | 1.25%   |
| Toshiba                         | 2         | 0.83%   |
| Realtek                         | 2         | 0.83%   |
| Hewlett-Packard                 | 2         | 0.83%   |
| USI                             | 1         | 0.42%   |
| Ralink                          | 1         | 0.42%   |
| Marvell Semiconductor           | 1         | 0.42%   |
| Askey Computer                  | 1         | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 36        | 15%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 21        | 8.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 7.92%   |
| Intel AX201 Bluetooth                               | 16        | 6.67%   |
| Intel AX200 Bluetooth                               | 11        | 4.58%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 3.33%   |
| IMC Networks Bluetooth Device                       | 8         | 3.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 2.92%   |
| Realtek Bluetooth Radio                             | 7         | 2.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 2.92%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.92%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 2.08%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 2.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 1.67%   |
| MediaTek Wireless_Device                            | 4         | 1.67%   |
| Lite-On Bluetooth Device                            | 4         | 1.67%   |
| Apple Bluetooth Host Controller                     | 4         | 1.67%   |
| Intel Bluetooth Device                              | 3         | 1.25%   |
| Intel AX210 Bluetooth                               | 3         | 1.25%   |
| IMC Networks Wireless_Device                        | 3         | 1.25%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.25%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.25%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.83%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.83%   |
| Lite-On Wireless_Device                             | 2         | 0.83%   |
| Lite-On Bluetooth Radio                             | 2         | 0.83%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.83%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.83%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.83%   |
| USI Bluetooth Device                                | 1         | 0.42%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.42%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.42%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.42%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 283       | 50.72%  |
| AMD                                          | 116       | 20.79%  |
| Nvidia                                       | 111       | 19.89%  |
| C-Media Electronics                          | 11        | 1.97%   |
| JMTek                                        | 8         | 1.43%   |
| Razer USA                                    | 5         | 0.9%    |
| VIA Technologies                             | 2         | 0.36%   |
| SAVITECH                                     | 2         | 0.36%   |
| Samson Technologies                          | 2         | 0.36%   |
| Elan Microelectronics                        | 2         | 0.36%   |
| Earth Computer Technologies                  | 2         | 0.36%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.18%   |
| Texas Instruments                            | 1         | 0.18%   |
| Samsung Electronics                          | 1         | 0.18%   |
| Nordic Semiconductor ASA                     | 1         | 0.18%   |
| Lenovo                                       | 1         | 0.18%   |
| Kingston Technology                          | 1         | 0.18%   |
| Huawei Technologies                          | 1         | 0.18%   |
| Generalplus Technology                       | 1         | 0.18%   |
| ESS Technology                               | 1         | 0.18%   |
| Dell                                         | 1         | 0.18%   |
| Creative Technology                          | 1         | 0.18%   |
| Creative Labs                                | 1         | 0.18%   |
| Cayin                                        | 1         | 0.18%   |
| Blue Microphones                             | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 44        | 6.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 33        | 4.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 26        | 3.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 25        | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 3.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 21        | 3.11%   |
| Intel Cannon Lake PCH cAVS                                                                        | 20        | 2.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 20        | 2.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 2.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 2.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 2.07%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 2.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 2.07%   |
| Intel 200 Series PCH HD Audio                                                                     | 13        | 1.93%   |
| Nvidia High Definition Audio Controller                                                           | 11        | 1.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 1.63%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 1.63%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 1.48%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 10        | 1.48%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.33%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 7         | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.04%   |
| JMTek USB PnP Audio Device                                                                        | 7         | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.04%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 5         | 0.74%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.74%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.74%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 51        | 23.61%  |
| Kingston            | 49        | 22.69%  |
| SK hynix            | 36        | 16.67%  |
| Micron Technology   | 23        | 10.65%  |
| Unknown             | 17        | 7.87%   |
| Corsair             | 9         | 4.17%   |
| Transcend           | 5         | 2.31%   |
| Crucial             | 5         | 2.31%   |
| Elpida              | 4         | 1.85%   |
| G.Skill             | 3         | 1.39%   |
| A-DATA Technology   | 3         | 1.39%   |
| Unknown (ABCD)      | 2         | 0.93%   |
| Team                | 2         | 0.93%   |
| Unknown (0x02BA)    | 1         | 0.46%   |
| Unknown (08B5)      | 1         | 0.46%   |
| Ramaxel Technology  | 1         | 0.46%   |
| Nanya Technology    | 1         | 0.46%   |
| Lexar               | 1         | 0.46%   |
| ASint Technology    | 1         | 0.46%   |
| Unknown             | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 2.2%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 5         | 2.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.76%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 1.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.32%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 3         | 1.32%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 1.32%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.32%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 0.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.88%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.88%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.88%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 2         | 0.88%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.88%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.88%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.88%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s                   | 2         | 0.88%   |
| Micron RAM Module 4096MB SODIMM DDR4 2400MT/s                    | 2         | 0.88%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 0.88%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s         | 2         | 0.88%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s                   | 2         | 0.88%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 2         | 0.88%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s              | 2         | 0.88%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 2         | 0.88%   |
| Crucial RAM CT16G4SFD824A.C16FBR 16GB SODIMM DDR4 2400MT/s       | 2         | 0.88%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s              | 2         | 0.88%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1334MT/s                   | 1         | 0.44%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 1         | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.44%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.44%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.44%   |
| Unknown (0x02BA) RAM Module 2048MB FB-DIMM DDR2 800MT/s          | 1         | 0.44%   |
| Unknown (08B5) RAM IM308GU16N16 8192MB SODIMM DDR3 1333MT/s      | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 88        | 47.57%  |
| DDR3    | 62        | 33.51%  |
| LPDDR4  | 13        | 7.03%   |
| SDRAM   | 6         | 3.24%   |
| DDR5    | 4         | 2.16%   |
| Unknown | 4         | 2.16%   |
| LPDDR3  | 3         | 1.62%   |
| DDR2    | 2         | 1.08%   |
| DDR     | 2         | 1.08%   |
| LPDDR5  | 1         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 108       | 59.67%  |
| DIMM         | 57        | 31.49%  |
| Row Of Chips | 14        | 7.73%   |
| RIMM         | 1         | 0.55%   |
| FB-DIMM      | 1         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 71        | 37.57%  |
| 4096  | 63        | 33.33%  |
| 16384 | 25        | 13.23%  |
| 2048  | 24        | 12.7%   |
| 32768 | 4         | 2.12%   |
| 1024  | 2         | 1.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 43        | 21.61%  |
| 3200    | 26        | 13.07%  |
| 2667    | 25        | 12.56%  |
| 1333    | 21        | 10.55%  |
| 2400    | 17        | 8.54%   |
| 2133    | 10        | 5.03%   |
| 3600    | 6         | 3.02%   |
| 4267    | 5         | 2.51%   |
| 3266    | 5         | 2.51%   |
| 1334    | 5         | 2.51%   |
| 1067    | 4         | 2.01%   |
| 4800    | 3         | 1.51%   |
| 1867    | 3         | 1.51%   |
| 3733    | 2         | 1.01%   |
| 3466    | 2         | 1.01%   |
| 3400    | 2         | 1.01%   |
| 3151    | 2         | 1.01%   |
| 3000    | 2         | 1.01%   |
| 1866    | 2         | 1.01%   |
| 667     | 2         | 1.01%   |
| 8400    | 1         | 0.5%    |
| 6400    | 1         | 0.5%    |
| 5600    | 1         | 0.5%    |
| 4266    | 1         | 0.5%    |
| 4199    | 1         | 0.5%    |
| 3534    | 1         | 0.5%    |
| 3333    | 1         | 0.5%    |
| 2800    | 1         | 0.5%    |
| 2666    | 1         | 0.5%    |
| 800     | 1         | 0.5%    |
| 533     | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

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
| Seiko Epson L220 Series          | 1         | 9.09%   |
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
| Chicony Electronics                    | 53        | 23.45%  |
| IMC Networks                           | 30        | 13.27%  |
| Acer                                   | 29        | 12.83%  |
| Realtek Semiconductor                  | 19        | 8.41%   |
| Microdia                               | 18        | 7.96%   |
| Quanta                                 | 13        | 5.75%   |
| Logitech                               | 11        | 4.87%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.1%    |
| Sunplus Innovation Technology          | 6         | 2.65%   |
| Apple                                  | 6         | 2.65%   |
| Lite-On Technology                     | 5         | 2.21%   |
| Suyin                                  | 4         | 1.77%   |
| Aveo Technology                        | 4         | 1.77%   |
| Syntek                                 | 3         | 1.33%   |
| Silicon Motion                         | 3         | 1.33%   |
| Samsung Electronics                    | 2         | 0.88%   |
| Microsoft                              | 2         | 0.88%   |
| Generalplus Technology                 | 2         | 0.88%   |
| Z-Star Microelectronics                | 1         | 0.44%   |
| Sony Electronics                       | 1         | 0.44%   |
| Sonix Technology                       | 1         | 0.44%   |
| Razer USA                              | 1         | 0.44%   |
| Owon                                   | 1         | 0.44%   |
| Luxvisions Innotech Limited            | 1         | 0.44%   |
| Lenovo                                 | 1         | 0.44%   |
| icSpring                               | 1         | 0.44%   |
| Alcor Micro                            | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam    | 12        | 5.29%   |
| Chicony HD WebCam                    | 11        | 4.85%   |
| Chicony Integrated Camera            | 10        | 4.41%   |
| Acer Integrated Camera               | 7         | 3.08%   |
| Microdia Integrated_Webcam_HD        | 6         | 2.64%   |
| Acer Lenovo EasyCamera               | 6         | 2.64%   |
| Chicony HP TrueVision HD Camera      | 5         | 2.2%    |
| Realtek Integrated_Webcam_HD         | 4         | 1.76%   |
| Realtek HD WebCam                    | 4         | 1.76%   |
| IMC Networks USB2.0 VGA UVC WebCam   | 4         | 1.76%   |
| IMC Networks Integrated Camera       | 4         | 1.76%   |
| Chicony Lenovo EasyCamera            | 4         | 1.76%   |
| Acer SunplusIT Integrated Camera     | 4         | 1.76%   |
| Silicon Motion WebCam SCB-0385N      | 3         | 1.32%   |
| Microdia CameraA                     | 3         | 1.32%   |
| Microdia Camera                      | 3         | 1.32%   |
| Lite-On HP Wide Vision HD Camera     | 3         | 1.32%   |
| Chicony HP Wide Vision HD Camera     | 3         | 1.32%   |
| Chicony HD User Facing               | 3         | 1.32%   |
| Aveo USB2.0 Camera                   | 3         | 1.32%   |
| Apple Built-in iSight                | 3         | 1.32%   |
| Acer Lenovo Integrated Webcam        | 3         | 1.32%   |
| Syntek Integrated Camera             | 2         | 0.88%   |
| Sunplus Integrated_Webcam_HD         | 2         | 0.88%   |
| Samsung Galaxy A5 (MTP)              | 2         | 0.88%   |
| Realtek USB2.0 HD UVC WebCam         | 2         | 0.88%   |
| Realtek Integrated Webcam            | 2         | 0.88%   |
| Quanta VGA WebCam                    | 2         | 0.88%   |
| Quanta USB2.0 HD UVC WebCam          | 2         | 0.88%   |
| Quanta HD Webcam                     | 2         | 0.88%   |
| Quanta HD User Facing                | 2         | 0.88%   |
| Microdia Integrated Webcam           | 2         | 0.88%   |
| Logitech Webcam C310                 | 2         | 0.88%   |
| Logitech Webcam C270                 | 2         | 0.88%   |
| IMC Networks VGA UVC WebCam          | 2         | 0.88%   |
| IMC Networks USB2.0 UVC HD Webcam    | 2         | 0.88%   |
| IMC Networks ov9734_azurewave_camera | 2         | 0.88%   |
| Generalplus GENERAL WEBCAM           | 2         | 0.88%   |
| Chicony VGA Webcam                   | 2         | 0.88%   |
| Chicony USB2.0 VGA UVC WebCam        | 2         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 14        | 33.33%  |
| Shenzhen Goodix Technology | 10        | 23.81%  |
| LighTuning Technology      | 5         | 11.9%   |
| Elan Microelectronics      | 5         | 11.9%   |
| Validity Sensors           | 4         | 9.52%   |
| Upek                       | 2         | 4.76%   |
| AuthenTec                  | 2         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown                                                | 7         | 16.67%  |
| Shenzhen Goodix Fingerprint Reader                     | 6         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device                    | 4         | 9.52%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 3         | 7.14%   |
| Elan ELAN:Fingerprint                                  | 3         | 7.14%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 4.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 4.76%   |
| Synaptics  WBDI                                        | 2         | 4.76%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 2         | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 4.76%   |
| Elan ELAN:ARM-M4                                       | 2         | 4.76%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 2.38%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 2.38%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 2.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.38%   |
| LighTuning Fingerprint Sensor                          | 1         | 2.38%   |
| AuthenTec AES2810                                      | 1         | 2.38%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 2.38%   |

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
| 0     | 288       | 71.46%  |
| 1     | 93        | 23.08%  |
| 2     | 18        | 4.47%   |
| 3     | 2         | 0.5%    |
| 7     | 1         | 0.25%   |
| 5     | 1         | 0.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 40        | 28.99%  |
| Graphics card            | 32        | 23.19%  |
| Multimedia controller    | 16        | 11.59%  |
| Net/wireless             | 15        | 10.87%  |
| Chipcard                 | 8         | 5.8%    |
| Communication controller | 7         | 5.07%   |
| Sound                    | 6         | 4.35%   |
| Unassigned class         | 3         | 2.17%   |
| Bluetooth                | 3         | 2.17%   |
| Camera                   | 2         | 1.45%   |
| Wireless                 | 1         | 0.72%   |
| Storage/ide              | 1         | 0.72%   |
| Network                  | 1         | 0.72%   |
| Net/ethernet             | 1         | 0.72%   |
| Flash memory             | 1         | 0.72%   |
| Card reader              | 1         | 0.72%   |

