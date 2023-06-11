Linux in Thailand - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Thailand.

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

Total: 316

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | [628ee9ac88](https://linux-hardware.org/?probe=628ee9ac88) | Jun 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [19c6b51f80](https://linux-hardware.org/?probe=19c6b51f80) | Jun 08, 2023 |
| Acer          | Nitro AN515-52              | [1bdfa737bc](https://linux-hardware.org/?probe=1bdfa737bc) | Jun 08, 2023 |
| MECHREVO      | Code01 Ver2.0               | [d311022361](https://linux-hardware.org/?probe=d311022361) | Jun 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | [8fa7afa4a1](https://linux-hardware.org/?probe=8fa7afa4a1) | Jun 04, 2023 |
| Lenovo        | IdeaPad Z410 20292          | [3e68e53c33](https://linux-hardware.org/?probe=3e68e53c33) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [01c17ab9dc](https://linux-hardware.org/?probe=01c17ab9dc) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | [08eb3979f4](https://linux-hardware.org/?probe=08eb3979f4) | May 19, 2023 |
| ASUSTek       | ROG Strix G733CX_G743CX     | [744f091c75](https://linux-hardware.org/?probe=744f091c75) | May 18, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [aaf53ecd65](https://linux-hardware.org/?probe=aaf53ecd65) | May 05, 2023 |
| Valve         | Jupiter                     | [206f95ee6f](https://linux-hardware.org/?probe=206f95ee6f) | May 02, 2023 |
| Dell          | XPS 15 9500                 | [a7cc631b80](https://linux-hardware.org/?probe=a7cc631b80) | Apr 27, 2023 |
| Lenovo        | ThinkPad T530 23594ZC       | [7aec73dfa1](https://linux-hardware.org/?probe=7aec73dfa1) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [52001c8ac6](https://linux-hardware.org/?probe=52001c8ac6) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [fc70e3e9e0](https://linux-hardware.org/?probe=fc70e3e9e0) | Apr 21, 2023 |
| Acer          | Aspire E5-575G              | [6f8dbb2e8e](https://linux-hardware.org/?probe=6f8dbb2e8e) | Apr 14, 2023 |
| HUAWEI        | KLVL-WXX9                   | [3166746b52](https://linux-hardware.org/?probe=3166746b52) | Apr 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | [52e50e17de](https://linux-hardware.org/?probe=52e50e17de) | Apr 11, 2023 |
| Lenovo        | IdeaPad Z410 20292          | [422a85d62b](https://linux-hardware.org/?probe=422a85d62b) | Apr 03, 2023 |
| HP            | Pavilion 15                 | [1a3e968dff](https://linux-hardware.org/?probe=1a3e968dff) | Apr 03, 2023 |
| Acer          | Aspire F5-573G              | [2c68190118](https://linux-hardware.org/?probe=2c68190118) | Apr 03, 2023 |
| Toshiba       | QOSMIO X70-B                | [8d94a6c8e7](https://linux-hardware.org/?probe=8d94a6c8e7) | Mar 28, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [061b0673b4](https://linux-hardware.org/?probe=061b0673b4) | Mar 12, 2023 |
| HUAWEI        | BOD-WXX9                    | [1875fd875d](https://linux-hardware.org/?probe=1875fd875d) | Mar 12, 2023 |
| Acer          | Aspire ES1-523              | [bd1f7da7bc](https://linux-hardware.org/?probe=bd1f7da7bc) | Mar 03, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [053c6d5368](https://linux-hardware.org/?probe=053c6d5368) | Mar 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [d475dd1788](https://linux-hardware.org/?probe=d475dd1788) | Feb 25, 2023 |
| Acer          | Aspire F5-573G              | [daf7b5a6cc](https://linux-hardware.org/?probe=daf7b5a6cc) | Feb 21, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a813f73ea2](https://linux-hardware.org/?probe=a813f73ea2) | Feb 20, 2023 |
| MSI           | Bravo 15 B5ED               | [a0b7f1b5f8](https://linux-hardware.org/?probe=a0b7f1b5f8) | Feb 20, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [06c1b9f781](https://linux-hardware.org/?probe=06c1b9f781) | Feb 20, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Acer          | Aspire E5-411G              | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | [abd464b0d3](https://linux-hardware.org/?probe=abd464b0d3) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | [d77cac7fb6](https://linux-hardware.org/?probe=d77cac7fb6) | Feb 10, 2023 |
| Acer          | Aspire ES1-523              | [647f120e0b](https://linux-hardware.org/?probe=647f120e0b) | Feb 08, 2023 |
| Lenovo        | ThinkPad P50 20EN0017US     | [43c5ab14ec](https://linux-hardware.org/?probe=43c5ab14ec) | Feb 03, 2023 |
| HP            | Laptop 15-db1xxx            | [8944f22b68](https://linux-hardware.org/?probe=8944f22b68) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [15cda8e776](https://linux-hardware.org/?probe=15cda8e776) | Jan 30, 2023 |
| Acer          | Aspire A515-55G             | [7a4e781669](https://linux-hardware.org/?probe=7a4e781669) | Jan 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [40560e6bcd](https://linux-hardware.org/?probe=40560e6bcd) | Jan 21, 2023 |
| Acer          | Aspire F5-573G              | [22b5c66553](https://linux-hardware.org/?probe=22b5c66553) | Jan 12, 2023 |
| Lenovo        | IdeaPad 300S-11IBR 80KU     | [6335e974a1](https://linux-hardware.org/?probe=6335e974a1) | Jan 08, 2023 |
| HUAWEI        | BOHB-WAX9                   | [9c9e1b06f9](https://linux-hardware.org/?probe=9c9e1b06f9) | Jan 07, 2023 |
| Acer          | Aspire V3-571G              | [67103caf92](https://linux-hardware.org/?probe=67103caf92) | Jan 07, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [7acb37a2f5](https://linux-hardware.org/?probe=7acb37a2f5) | Jan 05, 2023 |
| Dell          | G3 3579                     | [becea24616](https://linux-hardware.org/?probe=becea24616) | Jan 04, 2023 |
| Lenovo        | Z50-70 20354                | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| Lenovo        | IdeaPad Z410 20292          | [e46710b0cf](https://linux-hardware.org/?probe=e46710b0cf) | Dec 19, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [016e7d7ef2](https://linux-hardware.org/?probe=016e7d7ef2) | Dec 16, 2022 |
| Acer          | TravelMate P214-41-G2       | [cb52e49fa2](https://linux-hardware.org/?probe=cb52e49fa2) | Dec 08, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2ac449d25f](https://linux-hardware.org/?probe=2ac449d25f) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3807efd1f4](https://linux-hardware.org/?probe=3807efd1f4) | Dec 03, 2022 |
| Lenovo        | IdeaPad Z410 20292          | [af31550cae](https://linux-hardware.org/?probe=af31550cae) | Nov 27, 2022 |
| MSI           | GP63 Leopard 8RE            | [f8bb75758e](https://linux-hardware.org/?probe=f8bb75758e) | Nov 24, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [32e8c529f0](https://linux-hardware.org/?probe=32e8c529f0) | Nov 14, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [f4c2d5224b](https://linux-hardware.org/?probe=f4c2d5224b) | Oct 30, 2022 |
| Dell          | Precision 5530              | [bb4d35f452](https://linux-hardware.org/?probe=bb4d35f452) | Oct 28, 2022 |
| Gigabyte      | AERO 15 Classic-SA          | [7977a48aca](https://linux-hardware.org/?probe=7977a48aca) | Oct 26, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [13873c81b2](https://linux-hardware.org/?probe=13873c81b2) | Oct 24, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [4a6e283158](https://linux-hardware.org/?probe=4a6e283158) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7c284b1dfd](https://linux-hardware.org/?probe=7c284b1dfd) | Oct 20, 2022 |
| Acer          | Swift SFX14-41G             | [7c689396eb](https://linux-hardware.org/?probe=7c689396eb) | Oct 19, 2022 |
| Acer          | Swift SFX14-41G             | [357ad9257d](https://linux-hardware.org/?probe=357ad9257d) | Oct 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [478b58f9b6](https://linux-hardware.org/?probe=478b58f9b6) | Oct 15, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [64cbdc6e2a](https://linux-hardware.org/?probe=64cbdc6e2a) | Oct 13, 2022 |
| Acer          | Aspire E5-575G              | [ed74f1da66](https://linux-hardware.org/?probe=ed74f1da66) | Oct 10, 2022 |
| HP            | EliteBook 840 G6            | [29f63f8a32](https://linux-hardware.org/?probe=29f63f8a32) | Oct 10, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3665682cc6](https://linux-hardware.org/?probe=3665682cc6) | Oct 08, 2022 |
| HP            | Laptop                      | [3a26ec874f](https://linux-hardware.org/?probe=3a26ec874f) | Oct 04, 2022 |
| Timi          | TM1701                      | [59153cc5fe](https://linux-hardware.org/?probe=59153cc5fe) | Sep 27, 2022 |
| HP            | Laptop                      | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Laptop                      | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| Acer          | TravelMate P653-M           | [c0fcc47188](https://linux-hardware.org/?probe=c0fcc47188) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [65f638768e](https://linux-hardware.org/?probe=65f638768e) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1746f3874c](https://linux-hardware.org/?probe=1746f3874c) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | [0008869bb6](https://linux-hardware.org/?probe=0008869bb6) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | [c0e9a2e062](https://linux-hardware.org/?probe=c0e9a2e062) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | [51a98d93a6](https://linux-hardware.org/?probe=51a98d93a6) | Aug 20, 2022 |
| Acer          | Aspire V3-771               | [dc65bd0f38](https://linux-hardware.org/?probe=dc65bd0f38) | Aug 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [93b2d066d6](https://linux-hardware.org/?probe=93b2d066d6) | Aug 17, 2022 |
| Unknown       | Unknown                     | [5cdd2332d5](https://linux-hardware.org/?probe=5cdd2332d5) | Aug 14, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | [1b9f19b21e](https://linux-hardware.org/?probe=1b9f19b21e) | Aug 13, 2022 |
| Acer          | Aspire E5-575G              | [5ebbabea13](https://linux-hardware.org/?probe=5ebbabea13) | Aug 10, 2022 |
| Acer          | TravelMate P643-M           | [33254cfb1e](https://linux-hardware.org/?probe=33254cfb1e) | Aug 03, 2022 |
| HP            | Stream Notebook PC 13       | [d736692861](https://linux-hardware.org/?probe=d736692861) | Jul 31, 2022 |
| Dell          | Latitude 3320               | [183ae38016](https://linux-hardware.org/?probe=183ae38016) | Jul 31, 2022 |
| Dell          | Latitude 3320               | [a849c0d90a](https://linux-hardware.org/?probe=a849c0d90a) | Jul 30, 2022 |
| Dell          | Latitude E5430 non-vPro     | [f8808faaf0](https://linux-hardware.org/?probe=f8808faaf0) | Jul 24, 2022 |
| Acer          | TravelMate P643-M           | [0357bf32d7](https://linux-hardware.org/?probe=0357bf32d7) | Jul 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [eac5600627](https://linux-hardware.org/?probe=eac5600627) | Jul 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [4829f98af6](https://linux-hardware.org/?probe=4829f98af6) | Jul 04, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [cfa0dde1d0](https://linux-hardware.org/?probe=cfa0dde1d0) | Jul 02, 2022 |
| Infinix       | INBOOK X2                   | [eedac976d8](https://linux-hardware.org/?probe=eedac976d8) | Jul 02, 2022 |
| Infinix       | INBOOK X2                   | [1c87102f96](https://linux-hardware.org/?probe=1c87102f96) | Jun 29, 2022 |
| Lenovo        | ThinkPad X230 23331R5       | [c6589e02c4](https://linux-hardware.org/?probe=c6589e02c4) | Jun 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a1a0b3b43b](https://linux-hardware.org/?probe=a1a0b3b43b) | Jun 23, 2022 |
| MSI           | GE76 Raider 10UH            | [77ef5acb4c](https://linux-hardware.org/?probe=77ef5acb4c) | Jun 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [51ec938467](https://linux-hardware.org/?probe=51ec938467) | Jun 22, 2022 |
| Unknown       | Unknown                     | [00090936e8](https://linux-hardware.org/?probe=00090936e8) | Jun 15, 2022 |
| Dell          | Latitude 3120               | [c5c6eed0d9](https://linux-hardware.org/?probe=c5c6eed0d9) | Jun 14, 2022 |
| Acer          | Aspire F5-573G              | [fd7d146eb1](https://linux-hardware.org/?probe=fd7d146eb1) | Jun 08, 2022 |
| Apple         | MacBookPro11,1              | [b12802bc7a](https://linux-hardware.org/?probe=b12802bc7a) | Jun 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [799a25df83](https://linux-hardware.org/?probe=799a25df83) | May 31, 2022 |
| Acer          | One Z1402                   | [4278b806cf](https://linux-hardware.org/?probe=4278b806cf) | May 31, 2022 |
| ASUSTek       | S400CA                      | [dadda333d2](https://linux-hardware.org/?probe=dadda333d2) | May 28, 2022 |
| Dell          | Latitude 3120               | [e97cf58459](https://linux-hardware.org/?probe=e97cf58459) | May 23, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [8949bc2cf8](https://linux-hardware.org/?probe=8949bc2cf8) | May 22, 2022 |
| Acer          | One Z1402                   | [ae69c0fdbd](https://linux-hardware.org/?probe=ae69c0fdbd) | May 21, 2022 |
| Dell          | Inspiron 7559               | [90bfbc9f6b](https://linux-hardware.org/?probe=90bfbc9f6b) | May 16, 2022 |
| Lenovo        | ThinkPad X230 23257Y1       | [0c4e13a23d](https://linux-hardware.org/?probe=0c4e13a23d) | May 11, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YJS... | [fb11780c46](https://linux-hardware.org/?probe=fb11780c46) | May 07, 2022 |
| ASUSTek       | K40IN                       | [ab6a95da52](https://linux-hardware.org/?probe=ab6a95da52) | Apr 28, 2022 |
| HP            | Pro Tablet 608 G1           | [a8b97ee7cf](https://linux-hardware.org/?probe=a8b97ee7cf) | Apr 25, 2022 |
| Acer          | Aspire A515-45              | [377315649e](https://linux-hardware.org/?probe=377315649e) | Apr 22, 2022 |
| ASUSTek       | G550JK                      | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| ASUSTek       | G550JK                      | [6d291b9c9c](https://linux-hardware.org/?probe=6d291b9c9c) | Apr 21, 2022 |
| ASUSTek       | FX503VD                     | [218e8b7d2a](https://linux-hardware.org/?probe=218e8b7d2a) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4286A78       | [d5c9254caa](https://linux-hardware.org/?probe=d5c9254caa) | Apr 20, 2022 |
| Acer          | Aspire E5-471G              | [a7179e1ba3](https://linux-hardware.org/?probe=a7179e1ba3) | Apr 16, 2022 |
| Framework     | Laptop                      | [bd5ea938e7](https://linux-hardware.org/?probe=bd5ea938e7) | Apr 07, 2022 |
| Dell          | Latitude 3120               | [c0df9a1ac0](https://linux-hardware.org/?probe=c0df9a1ac0) | Apr 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [30c09eec3b](https://linux-hardware.org/?probe=30c09eec3b) | Mar 28, 2022 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [a9a4291601](https://linux-hardware.org/?probe=a9a4291601) | Mar 26, 2022 |
| Dell          | Latitude 3120               | [69b7d6b1a3](https://linux-hardware.org/?probe=69b7d6b1a3) | Mar 26, 2022 |
| Dell          | Latitude 3120               | [78ae48c482](https://linux-hardware.org/?probe=78ae48c482) | Mar 26, 2022 |
| Acer          | Aspire E5-571               | [c2f6faf193](https://linux-hardware.org/?probe=c2f6faf193) | Mar 06, 2022 |
| HUAWEI        | HLYL-WXX9                   | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| Acer          | AOA150                      | [aeb35f9f12](https://linux-hardware.org/?probe=aeb35f9f12) | Feb 13, 2022 |
| Acer          | AOA150                      | [7d493dd5d5](https://linux-hardware.org/?probe=7d493dd5d5) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5d3d7c5340](https://linux-hardware.org/?probe=5d3d7c5340) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1488d5e773](https://linux-hardware.org/?probe=1488d5e773) | Feb 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [dfc4821588](https://linux-hardware.org/?probe=dfc4821588) | Feb 08, 2022 |
| Dell          | Vostro 5471                 | [c90234250e](https://linux-hardware.org/?probe=c90234250e) | Jan 31, 2022 |
| Lenovo        | ThinkPad P50 20EQS2AB00     | [bdc680b5f1](https://linux-hardware.org/?probe=bdc680b5f1) | Jan 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [31f48cd25e](https://linux-hardware.org/?probe=31f48cd25e) | Jan 19, 2022 |
| ASUSTek       | G550JK                      | [b26b378274](https://linux-hardware.org/?probe=b26b378274) | Jan 01, 2022 |
| Lenovo        | ThinkPad X131e 33722VU      | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [2e71480673](https://linux-hardware.org/?probe=2e71480673) | Dec 24, 2021 |
| Lenovo        | ThinkPad L530 24792T1       | [3e12618615](https://linux-hardware.org/?probe=3e12618615) | Nov 29, 2021 |
| Toshiba       | Satellite L840              | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0d0596e9ea](https://linux-hardware.org/?probe=0d0596e9ea) | Nov 25, 2021 |
| Notebook      | NV4XMB,ME,MZ                | [edaff183a5](https://linux-hardware.org/?probe=edaff183a5) | Nov 21, 2021 |
| Dell          | Vostro 5471                 | [4083699145](https://linux-hardware.org/?probe=4083699145) | Nov 14, 2021 |
| MSI           | Prestige 15 A10SC           | [b362dd3f20](https://linux-hardware.org/?probe=b362dd3f20) | Nov 13, 2021 |
| Dell          | Inspiron N5010              | [d1b6520785](https://linux-hardware.org/?probe=d1b6520785) | Nov 13, 2021 |
| HP            | EliteBook 6930p (FL488AW... | [af8e63842a](https://linux-hardware.org/?probe=af8e63842a) | Oct 28, 2021 |
| Acer          | Aspire ES1-131              | [de7bee5c36](https://linux-hardware.org/?probe=de7bee5c36) | Oct 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1193264475](https://linux-hardware.org/?probe=1193264475) | Oct 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Apple         | MacBookPro5,5               | [514642d183](https://linux-hardware.org/?probe=514642d183) | Sep 30, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [e4fb99f5b8](https://linux-hardware.org/?probe=e4fb99f5b8) | Sep 30, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [8141d6fa89](https://linux-hardware.org/?probe=8141d6fa89) | Sep 22, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| Dell          | Latitude D630               | [3af0cdbc54](https://linux-hardware.org/?probe=3af0cdbc54) | Sep 09, 2021 |
| Acer          | Aspire V3-575G              | [28e06e0c2b](https://linux-hardware.org/?probe=28e06e0c2b) | Aug 28, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [8e060f6c6c](https://linux-hardware.org/?probe=8e060f6c6c) | Aug 23, 2021 |
| Acer          | Aspire E5-471G              | [7f7c5133ad](https://linux-hardware.org/?probe=7f7c5133ad) | Aug 18, 2021 |
| Fujitsu       | LIFEBOOK A357               | [68af6cccad](https://linux-hardware.org/?probe=68af6cccad) | Aug 05, 2021 |
| Acer          | Aspire E5-475G              | [65ad8ece4a](https://linux-hardware.org/?probe=65ad8ece4a) | Jul 30, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [10b4953c7e](https://linux-hardware.org/?probe=10b4953c7e) | Jul 26, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [9d13b7e8df](https://linux-hardware.org/?probe=9d13b7e8df) | Jul 21, 2021 |
| Acer          | Aspire E5-471G              | [bde4a22e40](https://linux-hardware.org/?probe=bde4a22e40) | Jul 19, 2021 |
| Acer          | Nitro AN515-55              | [5c7365be9d](https://linux-hardware.org/?probe=5c7365be9d) | Jul 16, 2021 |
| Dell          | Vostro 3578                 | [f5bfb0ada6](https://linux-hardware.org/?probe=f5bfb0ada6) | Jul 09, 2021 |
| Dell          | Vostro 3578                 | [e69ebc683f](https://linux-hardware.org/?probe=e69ebc683f) | Jul 09, 2021 |
| Acer          | Aspire ES1-111M             | [40450f88e3](https://linux-hardware.org/?probe=40450f88e3) | Jul 07, 2021 |
| Acer          | Aspire ES1-111M             | [7eb7b4a001](https://linux-hardware.org/?probe=7eb7b4a001) | Jul 07, 2021 |
| MSI           | GF65 Thin 10UE              | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Fujitsu       | LIFEBOOK BH531              | [688d9f583e](https://linux-hardware.org/?probe=688d9f583e) | Jun 16, 2021 |
| HP            | Stream Notebook             | [806c24449c](https://linux-hardware.org/?probe=806c24449c) | Jun 09, 2021 |
| ASUSTek       | X450LN                      | [9157df68c1](https://linux-hardware.org/?probe=9157df68c1) | May 27, 2021 |
| Lenovo        | B50-80 80LT                 | [ef615e10ea](https://linux-hardware.org/?probe=ef615e10ea) | May 27, 2021 |
| ASUSTek       | X450LN                      | [aa8e32e484](https://linux-hardware.org/?probe=aa8e32e484) | May 25, 2021 |
| Toshiba       | Satellite L645              | [a3c061e392](https://linux-hardware.org/?probe=a3c061e392) | May 17, 2021 |
| MSI           | GF63 Thin 9SCSR             | [0d99884dcd](https://linux-hardware.org/?probe=0d99884dcd) | May 17, 2021 |
| Dell          | Inspiron 7501               | [e8e3c50f4b](https://linux-hardware.org/?probe=e8e3c50f4b) | May 16, 2021 |
| Dell          | Latitude 3410               | [b29d7ddfe8](https://linux-hardware.org/?probe=b29d7ddfe8) | May 09, 2021 |
| Dell          | Latitude E6430              | [1a7d88c72a](https://linux-hardware.org/?probe=1a7d88c72a) | May 04, 2021 |
| Dell          | Latitude E6430              | [7b00c56952](https://linux-hardware.org/?probe=7b00c56952) | May 02, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| Acer          | Aspire ES1-111M             | [aa9bfbf347](https://linux-hardware.org/?probe=aa9bfbf347) | Apr 29, 2021 |
| Acer          | Aspire ES1-111M             | [298d859193](https://linux-hardware.org/?probe=298d859193) | Apr 27, 2021 |
| Dell          | Latitude 3410               | [b6748a9a7e](https://linux-hardware.org/?probe=b6748a9a7e) | Apr 25, 2021 |
| Fujitsu       | LIFEBOOK BH531              | [2fa4c2d1ef](https://linux-hardware.org/?probe=2fa4c2d1ef) | Apr 18, 2021 |
| Dell          | G7 7590                     | [be5780df0a](https://linux-hardware.org/?probe=be5780df0a) | Mar 09, 2021 |
| Samsung       | R780/R778                   | [0c57a7241e](https://linux-hardware.org/?probe=0c57a7241e) | Feb 26, 2021 |
| ASUSTek       | E200HA                      | [1faf0b360f](https://linux-hardware.org/?probe=1faf0b360f) | Feb 19, 2021 |
| ASUSTek       | K45VM                       | [26690f314d](https://linux-hardware.org/?probe=26690f314d) | Feb 15, 2021 |
| ASUSTek       | X555LD                      | [1b2994e7f3](https://linux-hardware.org/?probe=1b2994e7f3) | Feb 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [40bcb4aaf2](https://linux-hardware.org/?probe=40bcb4aaf2) | Feb 15, 2021 |
| Apple         | MacBookAir3,2               | [0392f08b03](https://linux-hardware.org/?probe=0392f08b03) | Feb 15, 2021 |
| Acer          | Aspire E5-471G              | [401fa9d58e](https://linux-hardware.org/?probe=401fa9d58e) | Feb 13, 2021 |
| HP            | 1000                        | [16b305a6f5](https://linux-hardware.org/?probe=16b305a6f5) | Feb 13, 2021 |
| HUAWEI        | KLVL-WXX9                   | [20b10721e2](https://linux-hardware.org/?probe=20b10721e2) | Feb 09, 2021 |
| Acer          | Aspire E5-475G              | [360e7155d7](https://linux-hardware.org/?probe=360e7155d7) | Feb 06, 2021 |
| Sony          | SVF14N25CXB                 | [1db1e6aec9](https://linux-hardware.org/?probe=1db1e6aec9) | Jan 28, 2021 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | [731a44edca](https://linux-hardware.org/?probe=731a44edca) | Jan 16, 2021 |
| Lenovo        | IdeaPad Y450                | [1285c5deb9](https://linux-hardware.org/?probe=1285c5deb9) | Jan 11, 2021 |
| Lenovo        | G460 20041                  | [f224060be4](https://linux-hardware.org/?probe=f224060be4) | Jan 07, 2021 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [e28d350fac](https://linux-hardware.org/?probe=e28d350fac) | Dec 24, 2020 |
| ASUSTek       | X450CC                      | [750f666a09](https://linux-hardware.org/?probe=750f666a09) | Dec 23, 2020 |
| Lenovo        | ThinkPad E15 20RES51Y00     | [66b1afc07c](https://linux-hardware.org/?probe=66b1afc07c) | Dec 15, 2020 |
| Dell          | Inspiron 5468               | [abc26c7422](https://linux-hardware.org/?probe=abc26c7422) | Dec 09, 2020 |
| MSI           | PE70 6QE                    | [cb5f05e67d](https://linux-hardware.org/?probe=cb5f05e67d) | Dec 02, 2020 |
| Acer          | Aspire E5-475G              | [53a62697ed](https://linux-hardware.org/?probe=53a62697ed) | Dec 01, 2020 |
| Acer          | Aspire E5-475G              | [719a24bc0f](https://linux-hardware.org/?probe=719a24bc0f) | Nov 30, 2020 |
| MSI           | PE70 6QE                    | [90b21f8369](https://linux-hardware.org/?probe=90b21f8369) | Nov 23, 2020 |
| Acer          | Aspire VN7-793G             | [79f11201bc](https://linux-hardware.org/?probe=79f11201bc) | Nov 22, 2020 |
| Dell          | G5 5590                     | [007ad64378](https://linux-hardware.org/?probe=007ad64378) | Nov 20, 2020 |
| MSI           | GE75 Raider 10SGS           | [025deb9bbe](https://linux-hardware.org/?probe=025deb9bbe) | Nov 19, 2020 |
| Dell          | G5 5590                     | [e82ed4c1d0](https://linux-hardware.org/?probe=e82ed4c1d0) | Nov 19, 2020 |
| HP            | Laptop 14-bs0xx             | [f90473f671](https://linux-hardware.org/?probe=f90473f671) | Nov 16, 2020 |
| HP            | Laptop 14-bs0xx             | [bf8d99074a](https://linux-hardware.org/?probe=bf8d99074a) | Nov 15, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [4c0fec3ac5](https://linux-hardware.org/?probe=4c0fec3ac5) | Nov 09, 2020 |
| Hampoo        | Unknown                     | [b713cd21d1](https://linux-hardware.org/?probe=b713cd21d1) | Oct 24, 2020 |
| Hampoo        | Unknown                     | [03640b9aac](https://linux-hardware.org/?probe=03640b9aac) | Oct 24, 2020 |
| MSI           | PE70 6QE                    | [8c3ccf4956](https://linux-hardware.org/?probe=8c3ccf4956) | Oct 19, 2020 |
| Dell          | Precision 7740              | [814a0ec705](https://linux-hardware.org/?probe=814a0ec705) | Oct 15, 2020 |
| MSI           | PE70 6QE                    | [1691661a18](https://linux-hardware.org/?probe=1691661a18) | Oct 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [e0d54e69ff](https://linux-hardware.org/?probe=e0d54e69ff) | Oct 11, 2020 |
| HP            | Pavilion dv7                | [058179daf5](https://linux-hardware.org/?probe=058179daf5) | Sep 24, 2020 |
| HP            | Pavilion dv6                | [acce68d947](https://linux-hardware.org/?probe=acce68d947) | Sep 09, 2020 |
| Dell          | Inspiron 5447               | [9fc26445da](https://linux-hardware.org/?probe=9fc26445da) | Sep 03, 2020 |
| Dell          | Inspiron 5447               | [fd56e29478](https://linux-hardware.org/?probe=fd56e29478) | Sep 03, 2020 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [e55f750fc2](https://linux-hardware.org/?probe=e55f750fc2) | Sep 02, 2020 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [cc7e35217e](https://linux-hardware.org/?probe=cc7e35217e) | Sep 02, 2020 |
| Acer          | Aspire VN7-792G             | [706847f6cd](https://linux-hardware.org/?probe=706847f6cd) | Aug 30, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [dc8ed0c837](https://linux-hardware.org/?probe=dc8ed0c837) | Jul 30, 2020 |
| ASUSTek       | X411UN                      | [212932d80d](https://linux-hardware.org/?probe=212932d80d) | Jul 27, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [8dd238e5a1](https://linux-hardware.org/?probe=8dd238e5a1) | Jul 24, 2020 |
| Acer          | Swift SF314-57G             | [c74653b694](https://linux-hardware.org/?probe=c74653b694) | Jul 15, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f545576ae9](https://linux-hardware.org/?probe=f545576ae9) | Jul 14, 2020 |
| Acer          | Aspire VN7-792G             | [405d399549](https://linux-hardware.org/?probe=405d399549) | Jul 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4175ac62a0](https://linux-hardware.org/?probe=4175ac62a0) | Jul 10, 2020 |
| Acer          | Aspire A315-42              | [7c061a0688](https://linux-hardware.org/?probe=7c061a0688) | Jul 06, 2020 |
| Acer          | Aspire VN7-792G             | [1457f6e3b5](https://linux-hardware.org/?probe=1457f6e3b5) | Jul 04, 2020 |
| Fujitsu       | LIFEBOOK BH531              | [2484e68205](https://linux-hardware.org/?probe=2484e68205) | Jul 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [adc28756a8](https://linux-hardware.org/?probe=adc28756a8) | Jun 29, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [6e947dfc9d](https://linux-hardware.org/?probe=6e947dfc9d) | Jun 27, 2020 |
| ASUSTek       | K42JB                       | [5f87f39c75](https://linux-hardware.org/?probe=5f87f39c75) | Jun 27, 2020 |
| MSI           | MS-14Y1                     | [c585b33393](https://linux-hardware.org/?probe=c585b33393) | Jun 25, 2020 |
| HP            | Pavilion Notebook           | [8d0c93ef24](https://linux-hardware.org/?probe=8d0c93ef24) | Jun 17, 2020 |
| MSI           | MS-14Y1                     | [657c6d539f](https://linux-hardware.org/?probe=657c6d539f) | Jun 03, 2020 |
| Sony          | SVF14N25CXB                 | [2fdd1fc4d3](https://linux-hardware.org/?probe=2fdd1fc4d3) | Jun 02, 2020 |
| ASUSTek       | K53SV                       | [0bb72c8f71](https://linux-hardware.org/?probe=0bb72c8f71) | Jun 01, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [645ef14cb4](https://linux-hardware.org/?probe=645ef14cb4) | May 21, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [4827cdc9b5](https://linux-hardware.org/?probe=4827cdc9b5) | May 21, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | [338493712f](https://linux-hardware.org/?probe=338493712f) | May 19, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | [17f5a0932c](https://linux-hardware.org/?probe=17f5a0932c) | May 19, 2020 |
| Samsung       | RV418/RV518/RV718           | [ff8f525d6b](https://linux-hardware.org/?probe=ff8f525d6b) | May 18, 2020 |
| Lenovo        | G480 20156                  | [6cb3a28f6a](https://linux-hardware.org/?probe=6cb3a28f6a) | May 18, 2020 |
| Lenovo        | G480 20156                  | [7487bf67c4](https://linux-hardware.org/?probe=7487bf67c4) | May 18, 2020 |
| Acer          | Nitro AN515-42              | [5c659d6268](https://linux-hardware.org/?probe=5c659d6268) | May 07, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [f286a38265](https://linux-hardware.org/?probe=f286a38265) | Apr 30, 2020 |
| Lenovo        | Y50-70 20378                | [bbd3e36751](https://linux-hardware.org/?probe=bbd3e36751) | Apr 16, 2020 |
| Lenovo        | Y50-70 20378                | [8bca0c818d](https://linux-hardware.org/?probe=8bca0c818d) | Apr 16, 2020 |
| Lenovo        | ThinkPad T420 4180JH1       | [4d0e9109bb](https://linux-hardware.org/?probe=4d0e9109bb) | Mar 21, 2020 |
| Samsung       | NC208/NC108                 | [d577b178a1](https://linux-hardware.org/?probe=d577b178a1) | Mar 06, 2020 |
| Samsung       | NC208/NC108                 | [cc28243d3d](https://linux-hardware.org/?probe=cc28243d3d) | Mar 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [626f7fb341](https://linux-hardware.org/?probe=626f7fb341) | Feb 29, 2020 |
| Acer          | Predator PH315-51           | [b3edf8c190](https://linux-hardware.org/?probe=b3edf8c190) | Feb 23, 2020 |
| Samsung       | NC208/NC108                 | [8d16cc2992](https://linux-hardware.org/?probe=8d16cc2992) | Feb 23, 2020 |
| Samsung       | NC208/NC108                 | [ffbfac004c](https://linux-hardware.org/?probe=ffbfac004c) | Feb 23, 2020 |
| Dell          | Precision 5510              | [0e30ff12b4](https://linux-hardware.org/?probe=0e30ff12b4) | Feb 18, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [ac7b752d68](https://linux-hardware.org/?probe=ac7b752d68) | Feb 13, 2020 |
| HP            | Compaq 15                   | [e8597ab3e4](https://linux-hardware.org/?probe=e8597ab3e4) | Feb 06, 2020 |
| MSI           | X460/X460DX                 | [faf3829102](https://linux-hardware.org/?probe=faf3829102) | Feb 04, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [670b5a0247](https://linux-hardware.org/?probe=670b5a0247) | Dec 27, 2019 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [fc21e1c322](https://linux-hardware.org/?probe=fc21e1c322) | Dec 18, 2019 |
| Lenovo        | ThinkPad P50 20EQS5XE00     | [65dc93e325](https://linux-hardware.org/?probe=65dc93e325) | Dec 18, 2019 |
| HP            | Laptop 14-ck0xxx            | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| Fujitsu       | LIFEBOOK BH531              | [c00057fc87](https://linux-hardware.org/?probe=c00057fc87) | Dec 01, 2019 |
| Clevo         | M540SR VT6363A              | [97181c941c](https://linux-hardware.org/?probe=97181c941c) | Nov 23, 2019 |
| Fujitsu       | LIFEBOOK BH531              | [0223eca896](https://linux-hardware.org/?probe=0223eca896) | Nov 22, 2019 |
| Lenovo        | G710 20252                  | [d11fbec88a](https://linux-hardware.org/?probe=d11fbec88a) | Nov 14, 2019 |
| Lenovo        | G710 20252                  | [21ae1ec676](https://linux-hardware.org/?probe=21ae1ec676) | Nov 10, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [b65742b189](https://linux-hardware.org/?probe=b65742b189) | Oct 26, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [6ccf378246](https://linux-hardware.org/?probe=6ccf378246) | Oct 26, 2019 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [29d4434f82](https://linux-hardware.org/?probe=29d4434f82) | Oct 26, 2019 |
| HP            | Laptop 14-cm0xxx            | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| Acer          | Swift SF113-31              | [a37935b2e0](https://linux-hardware.org/?probe=a37935b2e0) | Sep 27, 2019 |
| Lenovo        | ThinkPad T540p 20BFS0WB0... | [ccf2eacdd1](https://linux-hardware.org/?probe=ccf2eacdd1) | Sep 14, 2019 |
| Acer          | Aspire E5-552G              | [5c4bd87bc9](https://linux-hardware.org/?probe=5c4bd87bc9) | Sep 04, 2019 |
| Dell          | Vostro 3458                 | [a62197181c](https://linux-hardware.org/?probe=a62197181c) | Sep 04, 2019 |
| Lenovo        | G460 20041                  | [7b5945bfc2](https://linux-hardware.org/?probe=7b5945bfc2) | Aug 31, 2019 |
| HP            | Laptop 15-db0xxx            | [2d5f51cdd8](https://linux-hardware.org/?probe=2d5f51cdd8) | Aug 23, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [fe49019be0](https://linux-hardware.org/?probe=fe49019be0) | Aug 16, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [7551b403e2](https://linux-hardware.org/?probe=7551b403e2) | Aug 16, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [ef69a20f15](https://linux-hardware.org/?probe=ef69a20f15) | Aug 07, 2019 |
| HP            | ENVY Laptop ah0xxx          | [defe18c4c3](https://linux-hardware.org/?probe=defe18c4c3) | Jul 09, 2019 |
| Dell          | Latitude E6430              | [c8334c6a31](https://linux-hardware.org/?probe=c8334c6a31) | Jun 22, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [26db49d8f2](https://linux-hardware.org/?probe=26db49d8f2) | Jun 19, 2019 |
| Lenovo        | G460 20041                  | [62697bf35b](https://linux-hardware.org/?probe=62697bf35b) | Jun 16, 2019 |
| Acer          | Aspire A315-21              | [6d4aebc3ef](https://linux-hardware.org/?probe=6d4aebc3ef) | May 22, 2019 |
| Acer          | Aspire A315-21              | [f878e784e2](https://linux-hardware.org/?probe=f878e784e2) | May 04, 2019 |
| ASUSTek       | X556UQK                     | [d906d6357c](https://linux-hardware.org/?probe=d906d6357c) | May 02, 2019 |
| ASUSTek       | X556UQK                     | [63a8e04d9e](https://linux-hardware.org/?probe=63a8e04d9e) | May 02, 2019 |
| ASUSTek       | X556UQK                     | [7d55bd0096](https://linux-hardware.org/?probe=7d55bd0096) | May 02, 2019 |
| ASUSTek       | X556UQK                     | [6648050a69](https://linux-hardware.org/?probe=6648050a69) | May 01, 2019 |
| Dell          | Inspiron 14-3467            | [9b390a3c82](https://linux-hardware.org/?probe=9b390a3c82) | Apr 11, 2019 |
| Dell          | Inspiron 14-3467            | [7f1e85018c](https://linux-hardware.org/?probe=7f1e85018c) | Apr 11, 2019 |
| Acer          | Aspire 4750                 | [94d50c8e16](https://linux-hardware.org/?probe=94d50c8e16) | Mar 26, 2019 |
| Apple         | MacBookAir3,2               | [ee6b3b0da4](https://linux-hardware.org/?probe=ee6b3b0da4) | Jan 29, 2019 |
| HP            | Compaq nx6325 (EQ422AV)     | [410fe4b520](https://linux-hardware.org/?probe=410fe4b520) | Dec 21, 2018 |
| HP            | Compaq nx6325 (EQ422AV)     | [1697d0f3f4](https://linux-hardware.org/?probe=1697d0f3f4) | Dec 21, 2018 |
| Acer          | Aspire 4741                 | [0875804f8d](https://linux-hardware.org/?probe=0875804f8d) | Nov 22, 2018 |
| Acer          | Aspire 4741                 | [d2f2af2cb2](https://linux-hardware.org/?probe=d2f2af2cb2) | Nov 13, 2018 |
| Lenovo        | G40-45 80E1                 | [ebf69568bf](https://linux-hardware.org/?probe=ebf69568bf) | Oct 29, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 28        | 11.91%  |
| Pop!_OS 22.04                | 11        | 4.68%   |
| Ubuntu 22.04                 | 9         | 3.83%   |
| OpenMandriva 4.2             | 9         | 3.83%   |
| Debian 11                    | 9         | 3.83%   |
| Ubuntu 18.04                 | 8         | 3.4%    |
| KDE neon 20.04               | 8         | 3.4%    |
| Linux Mint 21                | 6         | 2.55%   |
| Fedora 37                    | 6         | 2.55%   |
| Arch Rolling                 | 6         | 2.55%   |
| KDE neon 22.04               | 5         | 2.13%   |
| Debian 10                    | 5         | 2.13%   |
| Arch                         | 5         | 2.13%   |
| Ubuntu 19.10                 | 4         | 1.7%    |
| Ubuntu 19.04                 | 4         | 1.7%    |
| OpenMandriva 23.01           | 4         | 1.7%    |
| Linux Mint 20.2              | 4         | 1.7%    |
| Zorin 15                     | 3         | 1.28%   |
| Ubuntu 18.10                 | 3         | 1.28%   |
| Ubuntu 16.04                 | 3         | 1.28%   |
| Pop!_OS 21.04                | 3         | 1.28%   |
| OpenMandriva 4.3             | 3         | 1.28%   |
| Linux Mint 19.2              | 3         | 1.28%   |
| Kubuntu 20.04                | 3         | 1.28%   |
| Fedora 38                    | 3         | 1.28%   |
| Debian Testing               | 3         | 1.28%   |
| Zorin 16                     | 2         | 0.85%   |
| Xubuntu 20.04                | 2         | 0.85%   |
| Ubuntu MATE 20.10            | 2         | 0.85%   |
| Ubuntu MATE 20.04            | 2         | 0.85%   |
| Pop!_OS 20.04                | 2         | 0.85%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.85%   |
| MX 19                        | 2         | 0.85%   |
| Linux Mint 20.3              | 2         | 0.85%   |
| Linux Mint 19.3              | 2         | 0.85%   |
| Kubuntu 22.04                | 2         | 0.85%   |
| Fedora 36                    | 2         | 0.85%   |
| Fedora 33                    | 2         | 0.85%   |
| Endless 3.7.7                | 2         | 0.85%   |
| Elementary 7                 | 2         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 59        | 26.11%  |
| Linux Mint   | 20        | 8.85%   |
| Pop!_OS      | 17        | 7.52%   |
| OpenMandriva | 17        | 7.52%   |
| Debian       | 17        | 7.52%   |
| Fedora       | 16        | 7.08%   |
| KDE neon     | 13        | 5.75%   |
| Arch         | 11        | 4.87%   |
| Endless      | 6         | 2.65%   |
| Zorin        | 5         | 2.21%   |
| Ubuntu MATE  | 5         | 2.21%   |
| Kubuntu      | 5         | 2.21%   |
| Xubuntu      | 3         | 1.33%   |
| openSUSE     | 3         | 1.33%   |
| MX           | 3         | 1.33%   |
| Manjaro      | 3         | 1.33%   |
| Elementary   | 3         | 1.33%   |
| Clear Linux  | 3         | 1.33%   |
| SteamOS      | 2         | 0.88%   |
| Lubuntu      | 2         | 0.88%   |
| Kali         | 2         | 0.88%   |
| ArcoLinux    | 2         | 0.88%   |
| UbuntuDDE    | 1         | 0.44%   |
| Ubuntu Unity | 1         | 0.44%   |
| ROSA         | 1         | 0.44%   |
| Linux Lite   | 1         | 0.44%   |
| Lilidog      | 1         | 0.44%   |
| Garuda Linux | 1         | 0.44%   |
| EndeavourOS  | 1         | 0.44%   |
| BlackPanther | 1         | 0.44%   |
| Archcraft    | 1         | 0.44%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002   | 9         | 3.46%   |
| 5.15.0-46-generic          | 6         | 2.31%   |
| 6.1.1-desktop-1omv2290     | 4         | 1.54%   |
| 5.15.0-58-generic          | 4         | 1.54%   |
| 6.0.6-76060006-generic     | 3         | 1.15%   |
| 6.0.12-76060006-generic    | 3         | 1.15%   |
| 5.8.0-50-generic           | 3         | 1.15%   |
| 5.4.0-42-generic           | 3         | 1.15%   |
| 5.3.0-28-generic           | 3         | 1.15%   |
| 5.19.0-43-generic          | 3         | 1.15%   |
| 5.16.7-desktop-1omv4003    | 3         | 1.15%   |
| 5.11.0-40-generic          | 3         | 1.15%   |
| 5.10.0-21-amd64            | 3         | 1.15%   |
| 5.0.0-32-generic           | 3         | 1.15%   |
| 5.0.0-27-generic           | 3         | 1.15%   |
| 4.18.0-15-generic          | 3         | 1.15%   |
| 6.1.11-200.fc37.x86_64     | 2         | 0.77%   |
| 5.8.14-arch1-1             | 2         | 0.77%   |
| 5.8.0-59-generic           | 2         | 0.77%   |
| 5.8.0-29-generic           | 2         | 0.77%   |
| 5.4.0-81-generic           | 2         | 0.77%   |
| 5.4.0-73-generic           | 2         | 0.77%   |
| 5.4.0-58-generic           | 2         | 0.77%   |
| 5.4.0-40-generic           | 2         | 0.77%   |
| 5.4.0-39-generic           | 2         | 0.77%   |
| 5.4.0-31-generic           | 2         | 0.77%   |
| 5.3.0-20-generic           | 2         | 0.77%   |
| 5.19.0-38-generic          | 2         | 0.77%   |
| 5.19.0-32-generic          | 2         | 0.77%   |
| 5.15.0-52-generic          | 2         | 0.77%   |
| 5.13.0-valve36-1-neptune   | 2         | 0.77%   |
| 5.13.0-39-generic          | 2         | 0.77%   |
| 5.12.0-19.3-liquorix-amd64 | 2         | 0.77%   |
| 5.11.0-43-generic          | 2         | 0.77%   |
| 5.11.0-34-generic          | 2         | 0.77%   |
| 5.0.0-25-generic           | 2         | 0.77%   |
| 4.19.0-6-amd64             | 2         | 0.77%   |
| 4.19.0-16-amd64            | 2         | 0.77%   |
| 4.15.0-70-generic          | 2         | 0.77%   |
| 4.15.0-51-generic          | 2         | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 32        | 12.75%  |
| 5.15.0  | 23        | 9.16%   |
| 5.8.0   | 13        | 5.18%   |
| 5.13.0  | 13        | 5.18%   |
| 4.15.0  | 13        | 5.18%   |
| 5.11.0  | 11        | 4.38%   |
| 5.3.0   | 10        | 3.98%   |
| 5.10.14 | 9         | 3.59%   |
| 5.0.0   | 9         | 3.59%   |
| 5.19.0  | 8         | 3.19%   |
| 5.10.0  | 7         | 2.79%   |
| 4.19.0  | 7         | 2.79%   |
| 4.18.0  | 7         | 2.79%   |
| 6.1.1   | 5         | 1.99%   |
| 6.0.6   | 3         | 1.2%    |
| 6.0.12  | 3         | 1.2%    |
| 5.16.7  | 3         | 1.2%    |
| 6.1.12  | 2         | 0.8%    |
| 6.1.11  | 2         | 0.8%    |
| 5.8.14  | 2         | 0.8%    |
| 5.18.0  | 2         | 0.8%    |
| 5.17.5  | 2         | 0.8%    |
| 5.17.0  | 2         | 0.8%    |
| 5.16.0  | 2         | 0.8%    |
| 5.12.0  | 2         | 0.8%    |
| 6.3.6   | 1         | 0.4%    |
| 6.3.4   | 1         | 0.4%    |
| 6.3.3   | 1         | 0.4%    |
| 6.2.9   | 1         | 0.4%    |
| 6.2.6   | 1         | 0.4%    |
| 6.2.2   | 1         | 0.4%    |
| 6.2.13  | 1         | 0.4%    |
| 6.2.12  | 1         | 0.4%    |
| 6.2.11  | 1         | 0.4%    |
| 6.2.10  | 1         | 0.4%    |
| 6.1.8   | 1         | 0.4%    |
| 6.1.10  | 1         | 0.4%    |
| 6.0.8   | 1         | 0.4%    |
| 6.0.7   | 1         | 0.4%    |
| 6.0.2   | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 13.88%  |
| 5.15    | 27        | 11.02%  |
| 5.10    | 19        | 7.76%   |
| 5.8     | 16        | 6.53%   |
| 5.13    | 15        | 6.12%   |
| 5.19    | 13        | 5.31%   |
| 4.15    | 13        | 5.31%   |
| 6.1     | 11        | 4.49%   |
| 5.3     | 11        | 4.49%   |
| 5.11    | 11        | 4.49%   |
| 6.0     | 10        | 4.08%   |
| 5.16    | 10        | 4.08%   |
| 5.0     | 9         | 3.67%   |
| 4.18    | 8         | 3.27%   |
| 6.2     | 7         | 2.86%   |
| 4.19    | 7         | 2.86%   |
| 5.18    | 5         | 2.04%   |
| 5.17    | 4         | 1.63%   |
| 5.12    | 4         | 1.63%   |
| 5.9     | 3         | 1.22%   |
| 5.6     | 3         | 1.22%   |
| 6.3     | 2         | 0.82%   |
| 5.5     | 2         | 0.82%   |
| 5.7     | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 218       | 98.64%  |
| i686   | 3         | 1.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 102       | 44.93%  |
| KDE5             | 40        | 17.62%  |
| Unknown          | 27        | 11.89%  |
| X-Cinnamon       | 18        | 7.93%   |
| XFCE             | 13        | 5.73%   |
| KDE              | 7         | 3.08%   |
| MATE             | 5         | 2.2%    |
| Pantheon         | 3         | 1.32%   |
| i3               | 2         | 0.88%   |
| Budgie           | 2         | 0.88%   |
| Unity            | 1         | 0.44%   |
| openbox          | 1         | 0.44%   |
| LXQt             | 1         | 0.44%   |
| LXDE             | 1         | 0.44%   |
| lightdm-xsession | 1         | 0.44%   |
| Deepin           | 1         | 0.44%   |
| Cinnamon         | 1         | 0.44%   |
| awesome          | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 172       | 75.77%  |
| Wayland | 37        | 16.3%   |
| Unknown | 15        | 6.61%   |
| Tty     | 3         | 1.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 115       | 50.44%  |
| SDDM    | 34        | 14.91%  |
| GDM     | 30        | 13.16%  |
| GDM3    | 21        | 9.21%   |
| LightDM | 20        | 8.77%   |
| TDM     | 6         | 2.63%   |
| XDM     | 1         | 0.44%   |
| Ly      | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 155       | 69.2%   |
| Unknown | 27        | 12.05%  |
| en_GB   | 9         | 4.02%   |
| de_DE   | 8         | 3.57%   |
| th_TH   | 7         | 3.13%   |
| fr_FR   | 5         | 2.23%   |
| en_SG   | 5         | 2.23%   |
| ru_RU   | 3         | 1.34%   |
| C       | 3         | 1.34%   |
| zh_CN   | 1         | 0.45%   |
| es_MX   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 135       | 60.81%  |
| BIOS | 87        | 39.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 179       | 79.56%  |
| Btrfs   | 22        | 9.78%   |
| Overlay | 18        | 8%      |
| Unknown | 5         | 2.22%   |
| Zfs     | 1         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 119       | 53.13%  |
| GPT     | 92        | 41.07%  |
| MBR     | 13        | 5.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 194       | 87%     |
| Yes       | 29        | 13%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 156       | 68.72%  |
| Yes       | 71        | 31.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 50        | 22.62%  |
| ASUSTek Computer               | 38        | 17.19%  |
| Acer                           | 36        | 16.29%  |
| Hewlett-Packard                | 24        | 10.86%  |
| Dell                           | 24        | 10.86%  |
| MSI                            | 11        | 4.98%   |
| HUAWEI                         | 8         | 3.62%   |
| Apple                          | 5         | 2.26%   |
| Samsung Electronics            | 4         | 1.81%   |
| Toshiba                        | 3         | 1.36%   |
| Valve                          | 2         | 0.9%    |
| Fujitsu                        | 2         | 0.9%    |
| Unknown                        | 2         | 0.9%    |
| Timi                           | 1         | 0.45%   |
| Sony                           | 1         | 0.45%   |
| SmbiosType1_SystemManufacturer | 1         | 0.45%   |
| Razer                          | 1         | 0.45%   |
| Notebook                       | 1         | 0.45%   |
| MECHREVO                       | 1         | 0.45%   |
| Infinix                        | 1         | 0.45%   |
| Hampoo                         | 1         | 0.45%   |
| Gigabyte Technology            | 1         | 0.45%   |
| Framework                      | 1         | 0.45%   |
| Foxconn                        | 1         | 0.45%   |
| Clevo                          | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                         | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| HUAWEI BOHB-WAX9                                             | 3         | 1.36%   |
| Unknown                                                      | 3         | 1.36%   |
| Valve Jupiter                                                | 2         | 0.9%    |
| Samsung NC208/NC108                                          | 2         | 0.9%    |
| Lenovo ThinkPad 11e 5th Gen 20LQS00000                       | 2         | 0.9%    |
| Lenovo G460 20041                                            | 2         | 0.9%    |
| HUAWEI KLVL-WXX9                                             | 2         | 0.9%    |
| Dell Latitude E6430                                          | 2         | 0.9%    |
| Dell Latitude 3120                                           | 2         | 0.9%    |
| ASUS X556UQK                                                 | 2         | 0.9%    |
| ASUS X450LN                                                  | 2         | 0.9%    |
| ASUS VivoBook_ASUSLaptop M3500QA_D3500QA                     | 2         | 0.9%    |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA                      | 2         | 0.9%    |
| ASUS TUF Gaming FX505DT_FX505DT                              | 2         | 0.9%    |
| Apple MacBookAir3,2                                          | 2         | 0.9%    |
| Acer Aspire F5-573G                                          | 2         | 0.9%    |
| Acer Aspire E5-471G                                          | 2         | 0.9%    |
| Acer Aspire A315-21                                          | 2         | 0.9%    |
| Toshiba Satellite L840                                       | 1         | 0.45%   |
| Toshiba Satellite L645                                       | 1         | 0.45%   |
| Toshiba QOSMIO X70-B                                         | 1         | 0.45%   |
| Timi TM1701                                                  | 1         | 0.45%   |
| Sony SVF14N25CXB                                             | 1         | 0.45%   |
| SmbiosType1_SystemManufacturer SmbiosType1_SystemProductName | 1         | 0.45%   |
| Samsung RV418/RV518/RV718                                    | 1         | 0.45%   |
| Samsung R780/R778                                            | 1         | 0.45%   |
| Razer Blade 15 (2022) - RZ09-0421                            | 1         | 0.45%   |
| Notebook NV4XMB,ME,MZ                                        | 1         | 0.45%   |
| MSI X460/X460DX                                              | 1         | 0.45%   |
| MSI Raider GE77HX 12UHS                                      | 1         | 0.45%   |
| MSI Prestige 15 A10SC                                        | 1         | 0.45%   |
| MSI PE70 6QE                                                 | 1         | 0.45%   |
| MSI MS-14Y1                                                  | 1         | 0.45%   |
| MSI GP63 Leopard 8RE                                         | 1         | 0.45%   |
| MSI GF65 Thin 10UE                                           | 1         | 0.45%   |
| MSI GF63 Thin 9SCSR                                          | 1         | 0.45%   |
| MSI GE76 Raider 10UH                                         | 1         | 0.45%   |
| MSI GE75 Raider 10SGS                                        | 1         | 0.45%   |
| MSI Bravo 15 B5ED                                            | 1         | 0.45%   |
| MECHREVO Code01 Ver2.0                                       | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 26        | 11.76%  |
| Acer Aspire                                | 24        | 10.86%  |
| Lenovo IdeaPad                             | 11        | 4.98%   |
| ASUS VivoBook                              | 10        | 4.52%   |
| HP Pavilion                                | 8         | 3.62%   |
| Dell Latitude                              | 8         | 3.62%   |
| HP Laptop                                  | 6         | 2.71%   |
| Dell Inspiron                              | 6         | 2.71%   |
| ASUS TUF                                   | 5         | 2.26%   |
| ASUS ZenBook                               | 4         | 1.81%   |
| HUAWEI BOHB-WAX9                           | 3         | 1.36%   |
| HP EliteBook                               | 3         | 1.36%   |
| Dell Vostro                                | 3         | 1.36%   |
| Dell Precision                             | 3         | 1.36%   |
| Acer TravelMate                            | 3         | 1.36%   |
| Acer Swift                                 | 3         | 1.36%   |
| Acer Nitro                                 | 3         | 1.36%   |
| Unknown                                    | 3         | 1.36%   |
| Valve Jupiter                              | 2         | 0.9%    |
| Toshiba Satellite                          | 2         | 0.9%    |
| Samsung NC208                              | 2         | 0.9%    |
| Lenovo ThinkBook                           | 2         | 0.9%    |
| Lenovo G460                                | 2         | 0.9%    |
| HUAWEI KLVL-WXX9                           | 2         | 0.9%    |
| HP Stream                                  | 2         | 0.9%    |
| HP Compaq                                  | 2         | 0.9%    |
| Fujitsu LIFEBOOK                           | 2         | 0.9%    |
| ASUS X556UQK                               | 2         | 0.9%    |
| ASUS X450LN                                | 2         | 0.9%    |
| ASUS ROG                                   | 2         | 0.9%    |
| Apple MacBookPro11                         | 2         | 0.9%    |
| Apple MacBookAir3                          | 2         | 0.9%    |
| Toshiba QOSMIO                             | 1         | 0.45%   |
| Timi TM1701                                | 1         | 0.45%   |
| Sony SVF14N25CXB                           | 1         | 0.45%   |
| SmbiosType1_SystemManufacturer SmbiosType1 | 1         | 0.45%   |
| Samsung RV418                              | 1         | 0.45%   |
| Samsung R780                               | 1         | 0.45%   |
| Razer Blade                                | 1         | 0.45%   |
| Notebook NV4XMB                            | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 27        | 12.22%  |
| 2018 | 24        | 10.86%  |
| 2021 | 23        | 10.41%  |
| 2019 | 20        | 9.05%   |
| 2014 | 18        | 8.14%   |
| 2015 | 16        | 7.24%   |
| 2012 | 16        | 7.24%   |
| 2016 | 15        | 6.79%   |
| 2022 | 13        | 5.88%   |
| 2017 | 12        | 5.43%   |
| 2011 | 12        | 5.43%   |
| 2010 | 9         | 4.07%   |
| 2013 | 7         | 3.17%   |
| 2009 | 3         | 1.36%   |
| 2008 | 3         | 1.36%   |
| 2007 | 2         | 0.9%    |
| 2006 | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 221       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 193       | 86.94%  |
| Enabled  | 29        | 13.06%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 221       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 62        | 27.93%  |
| 3.01-4.0    | 45        | 20.27%  |
| 16.01-24.0  | 40        | 18.02%  |
| 8.01-16.0   | 40        | 18.02%  |
| 32.01-64.0  | 17        | 7.66%   |
| 1.01-2.0    | 8         | 3.6%    |
| 24.01-32.0  | 5         | 2.25%   |
| 64.01-256.0 | 3         | 1.35%   |
| 2.01-3.0    | 1         | 0.45%   |
| 0.51-1.0    | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 82        | 34.31%  |
| 2.01-3.0   | 64        | 26.78%  |
| 4.01-8.0   | 40        | 16.74%  |
| 3.01-4.0   | 31        | 12.97%  |
| 8.01-16.0  | 12        | 5.02%   |
| 0.51-1.0   | 7         | 2.93%   |
| 0.01-0.5   | 2         | 0.84%   |
| 16.01-24.0 | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 155       | 67.69%  |
| 2      | 58        | 25.33%  |
| 3      | 11        | 4.8%    |
| 0      | 3         | 1.31%   |
| 5      | 1         | 0.44%   |
| 4      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 168       | 76.02%  |
| Yes       | 53        | 23.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 74.44%  |
| No        | 57        | 25.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 218       | 98.2%   |
| No        | 4         | 1.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 184       | 81.78%  |
| No        | 41        | 18.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Thailand | 221       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Bangkok             | 96        | 40.17%  |
| Chiang Mai          | 17        | 7.11%   |
| Nonthaburi          | 11        | 4.6%    |
| Phuket              | 9         | 3.77%   |
| Bang Lamung         | 8         | 3.35%   |
| Khon Kaen           | 7         | 2.93%   |
| Surat Thani         | 4         | 1.67%   |
| Surin               | 3         | 1.26%   |
| Rayong              | 3         | 1.26%   |
| Nakhon Pathom       | 3         | 1.26%   |
| Chon Buri           | 3         | 1.26%   |
| Songkhla            | 2         | 0.84%   |
| Phayao              | 2         | 0.84%   |
| Pattaya             | 2         | 0.84%   |
| Pattani             | 2         | 0.84%   |
| Pak Kret            | 2         | 0.84%   |
| Nakhon Ratchasima   | 2         | 0.84%   |
| Maha Sarakham       | 2         | 0.84%   |
| Khlong Luang        | 2         | 0.84%   |
| Hua Hin             | 2         | 0.84%   |
| Chiang Rai          | 2         | 0.84%   |
| Bang Bua Thong      | 2         | 0.84%   |
| Bang Bon            | 2         | 0.84%   |
| Ban Yang Sam Ton    | 2         | 0.84%   |
| Ban Phan Don        | 2         | 0.84%   |
| Yala                | 1         | 0.42%   |
| Udon Thani          | 1         | 0.42%   |
| Suan Luang          | 1         | 0.42%   |
| Si Sa Ket           | 1         | 0.42%   |
| Si Racha            | 1         | 0.42%   |
| Sattahip            | 1         | 0.42%   |
| Samut Prakan        | 1         | 0.42%   |
| Salaya              | 1         | 0.42%   |
| Ratchathewi         | 1         | 0.42%   |
| Rasi Salai          | 1         | 0.42%   |
| Prathai             | 1         | 0.42%   |
| Prachuap Khiri Khan | 1         | 0.42%   |
| Phitsanulok         | 1         | 0.42%   |
| Phetchaburi         | 1         | 0.42%   |
| Phen                | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 53        | 64     | 18.6%   |
| Samsung Electronics         | 40        | 51     | 14.04%  |
| Seagate                     | 34        | 45     | 11.93%  |
| Toshiba                     | 24        | 31     | 8.42%   |
| SanDisk                     | 19        | 25     | 6.67%   |
| Unknown                     | 17        | 21     | 5.96%   |
| Kingston                    | 13        | 15     | 4.56%   |
| Intel                       | 12        | 13     | 4.21%   |
| SK hynix                    | 8         | 17     | 2.81%   |
| HGST                        | 7         | 8      | 2.46%   |
| Micron Technology           | 6         | 7      | 2.11%   |
| Hitachi                     | 5         | 5      | 1.75%   |
| Transcend                   | 4         | 5      | 1.4%    |
| Crucial                     | 4         | 4      | 1.4%    |
| Apple                       | 4         | 4      | 1.4%    |
| SPCC                        | 3         | 3      | 1.05%   |
| Silicon Motion              | 3         | 4      | 1.05%   |
| Phison Electronics          | 3         | 5      | 1.05%   |
| KIOXIA                      | 2         | 4      | 0.7%    |
| Kingmax                     | 2         | 5      | 0.7%    |
| China                       | 2         | 2      | 0.7%    |
| Apacer                      | 2         | 2      | 0.7%    |
| YMTC                        | 1         | 1      | 0.35%   |
| Yangtze Memory Technologies | 1         | 1      | 0.35%   |
| XPG                         | 1         | 1      | 0.35%   |
| USB3.0                      | 1         | 2      | 0.35%   |
| Teelkoou                    | 1         | 1      | 0.35%   |
| Team                        | 1         | 1      | 0.35%   |
| ShiJi                       | 1         | 1      | 0.35%   |
| PNY                         | 1         | 2      | 0.35%   |
| Plextor                     | 1         | 1      | 0.35%   |
| Pioneer                     | 1         | 1      | 0.35%   |
| O2 Micro                    | 1         | 1      | 0.35%   |
| LITEON                      | 1         | 2      | 0.35%   |
| Lite-On                     | 1         | 2      | 0.35%   |
| Initio                      | 1         | 1      | 0.35%   |
| HS-SSD-C100                 | 1         | 1      | 0.35%   |
| GAMER                       | 1         | 1      | 0.35%   |
| Fujitsu                     | 1         | 2      | 0.35%   |
| A-DATA Technology           | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                              | 6         | 2.06%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 2.06%   |
| Seagate ST1000LM035-1RK172 1TB                      | 6         | 2.06%   |
| Unknown MMC Card  64GB                              | 5         | 1.72%   |
| Unknown MMC Card  32GB                              | 5         | 1.72%   |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 1.72%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 4         | 1.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 1.37%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 4         | 1.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 1.03%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 3         | 1.03%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 3         | 1.03%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 3         | 1.03%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 3         | 1.03%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB                  | 3         | 1.03%   |
| SK hynix HFM512GD3JX013N 512GB                      | 3         | 1.03%   |
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 1.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 1.03%   |
| Kingston NVMe SSD Drive 512GB                       | 3         | 1.03%   |
| HGST HTS725050A7E630 500GB                          | 3         | 1.03%   |
| HGST HTS721010A9E630 1TB                            | 3         | 1.03%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 2         | 0.69%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 2         | 0.69%   |
| Unknown SD/MMC/MS PRO 64GB                          | 2         | 0.69%   |
| Unknown DA4064  64GB                                | 2         | 0.69%   |
| Toshiba MQ01ABF032 320GB                            | 2         | 0.69%   |
| Toshiba KBG30ZMT128G 128GB                          | 2         | 0.69%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 2         | 0.69%   |
| Seagate ST9500325AS 500GB                           | 2         | 0.69%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 0.69%   |
| SanDisk NVMe SSD Drive 512GB                        | 2         | 0.69%   |
| SanDisk NVMe SSD Drive 250GB                        | 2         | 0.69%   |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 0.69%   |
| Samsung SSD 970 EVO Plus 500GB                      | 2         | 0.69%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2         | 0.69%   |
| Samsung NVMe SSD Drive 512GB                        | 2         | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 0.69%   |
| Phison E12 NVMe Controller 256GB                    | 2         | 0.69%   |
| KIOXIA KBG40ZNS128G NVMe 128GB                      | 2         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 45     | 34.69%  |
| WDC                 | 26        | 29     | 26.53%  |
| Toshiba             | 19        | 24     | 19.39%  |
| HGST                | 7         | 8      | 7.14%   |
| Hitachi             | 5         | 5      | 5.1%    |
| Unknown             | 2         | 2      | 2.04%   |
| Samsung Electronics | 2         | 3      | 2.04%   |
| USB3.0              | 1         | 2      | 1.02%   |
| Pioneer             | 1         | 1      | 1.02%   |
| Fujitsu             | 1         | 2      | 1.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 26     | 25%     |
| Samsung Electronics | 13        | 19     | 17.11%  |
| SanDisk             | 7         | 12     | 9.21%   |
| Kingston            | 6         | 7      | 7.89%   |
| Crucial             | 4         | 4      | 5.26%   |
| Apple               | 4         | 4      | 5.26%   |
| SPCC                | 3         | 3      | 3.95%   |
| Transcend           | 2         | 3      | 2.63%   |
| SK hynix            | 2         | 2      | 2.63%   |
| Micron Technology   | 2         | 3      | 2.63%   |
| Kingmax             | 2         | 5      | 2.63%   |
| Intel               | 2         | 2      | 2.63%   |
| China               | 2         | 2      | 2.63%   |
| Apacer              | 2         | 2      | 2.63%   |
| Teelkoou            | 1         | 1      | 1.32%   |
| Team                | 1         | 1      | 1.32%   |
| PNY                 | 1         | 2      | 1.32%   |
| Plextor             | 1         | 1      | 1.32%   |
| LITEON              | 1         | 2      | 1.32%   |
| Initio              | 1         | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 92        | 121    | 34.2%   |
| NVMe    | 89        | 118    | 33.09%  |
| SSD     | 70        | 102    | 26.02%  |
| MMC     | 15        | 19     | 5.58%   |
| Unknown | 3         | 3      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 138       | 215    | 55.42%  |
| NVMe | 89        | 118    | 35.74%  |
| MMC  | 15        | 19     | 6.02%   |
| SAS  | 7         | 11     | 2.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 89        | 131    | 56.33%  |
| 0.51-1.0   | 63        | 85     | 39.87%  |
| 1.01-2.0   | 6         | 7      | 3.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 55        | 23.4%   |
| 101-250        | 49        | 20.85%  |
| 501-1000       | 41        | 17.45%  |
| 51-100         | 23        | 9.79%   |
| 1-20           | 19        | 8.09%   |
| 1001-2000      | 18        | 7.66%   |
| 21-50          | 17        | 7.23%   |
| Unknown        | 5         | 2.13%   |
| More than 3000 | 4         | 1.7%    |
| 2001-3000      | 4         | 1.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 96        | 39.83%  |
| 21-50     | 45        | 18.67%  |
| 101-250   | 32        | 13.28%  |
| 251-500   | 25        | 10.37%  |
| 51-100    | 21        | 8.71%   |
| 501-1000  | 11        | 4.56%   |
| 1001-2000 | 6         | 2.49%   |
| Unknown   | 5         | 2.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB            | 2         | 2      | 12.5%   |
| Seagate ST1000LM049-2GH172 1TB    | 2         | 2      | 12.5%   |
| Seagate ST1000LM035-1RK172 1TB    | 2         | 2      | 12.5%   |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 3      | 6.25%   |
| USB3.0 Super Speed 1TB            | 1         | 2      | 6.25%   |
| Toshiba MQ04ABF100 1TB            | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 6.25%   |
| Seagate ST500LM000-SSHD-8GB       | 1         | 1      | 6.25%   |
| SanDisk SDSSDX240GG25 240GB       | 1         | 1      | 6.25%   |
| Samsung Electronics HM160HI 160GB | 1         | 2      | 6.25%   |
| Intel SSDSC2KF256H6 SATA 256GB    | 1         | 1      | 6.25%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB          | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 37.5%   |
| Toshiba             | 3         | 3      | 18.75%  |
| HGST                | 2         | 2      | 12.5%   |
| WDC                 | 1         | 3      | 6.25%   |
| USB3.0              | 1         | 2      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 2      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 42.86%  |
| Toshiba             | 3         | 3      | 21.43%  |
| HGST                | 2         | 2      | 14.29%  |
| WDC                 | 1         | 3      | 7.14%   |
| USB3.0              | 1         | 2      | 7.14%   |
| Samsung Electronics | 1         | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 18     | 86.67%  |
| SSD  | 2         | 2      | 13.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 138       | 230    | 59.48%  |
| Works    | 78        | 112    | 33.62%  |
| Malfunc  | 15        | 20     | 6.47%   |
| Failed   | 1         | 1      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 137       | 52.69%  |
| Samsung Electronics          | 31        | 11.92%  |
| AMD                          | 28        | 10.77%  |
| SanDisk                      | 21        | 8.08%   |
| Kingston Technology Company  | 7         | 2.69%   |
| SK hynix                     | 6         | 2.31%   |
| Toshiba America Info Systems | 5         | 1.92%   |
| Silicon Motion               | 4         | 1.54%   |
| Nvidia                       | 4         | 1.54%   |
| Micron Technology            | 4         | 1.54%   |
| Phison Electronics           | 3         | 1.15%   |
| Yangtze Memory Technologies  | 2         | 0.77%   |
| KIOXIA                       | 2         | 0.77%   |
| ADATA Technology             | 2         | 0.77%   |
| VIA Technologies             | 1         | 0.38%   |
| Transcend                    | 1         | 0.38%   |
| O2 Micro                     | 1         | 0.38%   |
| Lite-On Technology           | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 9.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 17        | 6.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 6.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 5.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 4.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 3.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 2.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 7         | 2.56%   |
| Intel SSD 660P Series                                                            | 7         | 2.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 2.2%    |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 2.2%    |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 2.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.2%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 5         | 1.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 1.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.83%   |
| Micron NVMe Storage Controller                                                   | 4         | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.47%   |
| SanDisk Non-Volatile memory controller                                           | 3         | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.1%    |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.1%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 1.1%    |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 1.1%    |
| Yangtze Memory Non-Volatile memory controller                                    | 2         | 0.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.73%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.73%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.73%   |
| SanDisk NVMe Controller                                                          | 2         | 0.73%   |
| Samsung Apple PCIe SSD                                                           | 2         | 0.73%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.73%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 0.73%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.73%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.73%   |
| Intel SSD 600P Series                                                            | 2         | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 148       | 56.7%   |
| NVMe | 92        | 35.25%  |
| RAID | 14        | 5.36%   |
| IDE  | 7         | 2.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 173       | 78.28%  |
| AMD    | 48        | 21.72%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 3.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 2.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 2.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 2.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 2.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.81%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.81%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.81%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 1.81%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 1.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.81%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.36%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 1.36%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.36%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 1.36%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 3         | 1.36%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.36%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.36%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.36%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 3         | 1.36%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.9%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.9%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.9%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.9%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.9%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.9%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.9%    |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 2         | 0.9%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.9%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 0.9%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.9%    |
| Intel Core 2 Duo CPU L9600 @ 2.13GHz          | 2         | 0.9%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 58        | 26.24%  |
| Intel Core i5           | 45        | 20.36%  |
| AMD Ryzen 5             | 17        | 7.69%   |
| Other                   | 16        | 7.24%   |
| Intel Core i3           | 16        | 7.24%   |
| Intel Celeron           | 10        | 4.52%   |
| AMD Ryzen 7             | 10        | 4.52%   |
| Intel Pentium           | 9         | 4.07%   |
| Intel Core 2 Duo        | 9         | 4.07%   |
| Intel Atom              | 6         | 2.71%   |
| AMD Ryzen 9             | 3         | 1.36%   |
| AMD Ryzen 3             | 3         | 1.36%   |
| AMD A4                  | 3         | 1.36%   |
| Intel Pentium Silver    | 2         | 0.9%    |
| AMD Ryzen 7 PRO         | 2         | 0.9%    |
| AMD Athlon              | 2         | 0.9%    |
| Intel Xeon              | 1         | 0.45%   |
| Intel Pentium Dual      | 1         | 0.45%   |
| Intel Core m3           | 1         | 0.45%   |
| Intel Core i9           | 1         | 0.45%   |
| AMD Turion 64 X2 Mobile | 1         | 0.45%   |
| AMD Ryzen 5 PRO         | 1         | 0.45%   |
| AMD E2                  | 1         | 0.45%   |
| AMD E1                  | 1         | 0.45%   |
| AMD A8                  | 1         | 0.45%   |
| AMD A10                 | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 91        | 40.99%  |
| 4      | 89        | 40.09%  |
| 6      | 21        | 9.46%   |
| 8      | 15        | 6.76%   |
| 16     | 2         | 0.9%    |
| 14     | 2         | 0.9%    |
| 1      | 2         | 0.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 221       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 177       | 79.37%  |
| 1      | 46        | 20.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 216       | 97.74%  |
| Unknown        | 4         | 1.81%   |
| 32-bit         | 1         | 0.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 27.07%  |
| 0x306a9    | 13        | 5.68%   |
| 0x206a7    | 10        | 4.37%   |
| 0x806ec    | 9         | 3.93%   |
| 0x806e9    | 9         | 3.93%   |
| 0x806c1    | 8         | 3.49%   |
| 0x40651    | 8         | 3.49%   |
| 0x806ea    | 7         | 3.06%   |
| 0x08108102 | 6         | 2.62%   |
| 0x906ea    | 5         | 2.18%   |
| 0x306c3    | 5         | 2.18%   |
| 0x1067a    | 5         | 2.18%   |
| 0x706a1    | 4         | 1.75%   |
| 0x506e3    | 4         | 1.75%   |
| 0x406e3    | 4         | 1.75%   |
| 0x406c4    | 4         | 1.75%   |
| 0x406c3    | 4         | 1.75%   |
| 0x20655    | 4         | 1.75%   |
| 0x20652    | 4         | 1.75%   |
| 0x0a50000c | 4         | 1.75%   |
| 0xa0652    | 3         | 1.31%   |
| 0x906e9    | 3         | 1.31%   |
| 0x906c0    | 3         | 1.31%   |
| 0x706a8    | 3         | 1.31%   |
| 0x08600106 | 3         | 1.31%   |
| 0x08600104 | 3         | 1.31%   |
| 0x0810100b | 3         | 1.31%   |
| 0x6fd      | 2         | 0.87%   |
| 0x30678    | 2         | 0.87%   |
| 0x106ca    | 2         | 0.87%   |
| 0x0a404102 | 2         | 0.87%   |
| 0x08608103 | 2         | 0.87%   |
| 0x08108109 | 2         | 0.87%   |
| 0x08101007 | 2         | 0.87%   |
| 0x06006704 | 2         | 0.87%   |
| 0xa0660    | 1         | 0.44%   |
| 0x90672    | 1         | 0.44%   |
| 0x706e5    | 1         | 0.44%   |
| 0x506c9    | 1         | 0.44%   |
| 0x40661    | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 45        | 20.36%  |
| Haswell          | 20        | 9.05%   |
| IvyBridge        | 15        | 6.79%   |
| Skylake          | 14        | 6.33%   |
| Zen+             | 12        | 5.43%   |
| Silvermont       | 11        | 4.98%   |
| Unknown          | 11        | 4.98%   |
| TigerLake        | 10        | 4.52%   |
| SandyBridge      | 10        | 4.52%   |
| Zen 2            | 8         | 3.62%   |
| Westmere         | 8         | 3.62%   |
| Penryn           | 8         | 3.62%   |
| CometLake        | 8         | 3.62%   |
| Zen 3            | 7         | 3.17%   |
| Goldmont plus    | 7         | 3.17%   |
| Zen              | 5         | 2.26%   |
| Tremont          | 3         | 1.36%   |
| IceLake          | 3         | 1.36%   |
| Excavator        | 3         | 1.36%   |
| Bonnell          | 3         | 1.36%   |
| Puma             | 2         | 0.9%    |
| Core             | 2         | 0.9%    |
| K8 Hammer        | 1         | 0.45%   |
| Jaguar           | 1         | 0.45%   |
| Goldmont         | 1         | 0.45%   |
| Broadwell        | 1         | 0.45%   |
| Bobcat           | 1         | 0.45%   |
| Alderlake Hybrid | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 154       | 48.73%  |
| Nvidia           | 98        | 31.01%  |
| AMD              | 62        | 19.62%  |
| VIA Technologies | 1         | 0.32%   |
| ATI Technologies | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 4.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 3.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 3.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 3.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 3.06%   |
| Intel HD Graphics 620                                                                    | 10        | 3.06%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 2.75%   |
| Intel HD Graphics 530                                                                    | 8         | 2.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.45%   |
| AMD Renoir                                                                               | 8         | 2.45%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 2.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 2.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 2.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 2.14%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 1.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.83%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.53%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.22%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.22%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 1.22%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 1.22%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 4         | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.22%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.92%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.92%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 0.92%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.92%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.92%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.92%   |
| Intel HD Graphics 630                                                                    | 3         | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.92%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 0.92%   |
| AMD Lucienne                                                                             | 3         | 0.92%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 3         | 0.92%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel + Nvidia     | 72        | 32.58%  |
| 1 x Intel          | 69        | 31.22%  |
| 1 x AMD            | 36        | 16.29%  |
| 1 x Nvidia         | 14        | 6.33%   |
| Intel + AMD        | 10        | 4.52%   |
| AMD + Nvidia       | 10        | 4.52%   |
| 2 x AMD            | 7         | 3.17%   |
| Intel + 2 x Nvidia | 2         | 0.9%    |
| 1 x VIA            | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 175       | 77.09%  |
| Proprietary | 49        | 21.59%  |
| Unknown     | 3         | 1.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 123       | 54.42%  |
| 1.01-2.0   | 32        | 14.16%  |
| 3.01-4.0   | 28        | 12.39%  |
| 0.01-0.5   | 26        | 11.5%   |
| 0.51-1.0   | 12        | 5.31%   |
| 5.01-6.0   | 3         | 1.33%   |
| 7.01-8.0   | 1         | 0.44%   |
| 8.01-16.0  | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 55        | 21.57%  |
| Chimei Innolux          | 40        | 15.69%  |
| BOE                     | 34        | 13.33%  |
| LG Display              | 31        | 12.16%  |
| Samsung Electronics     | 25        | 9.8%    |
| Dell                    | 10        | 3.92%   |
| PANDA                   | 9         | 3.53%   |
| Goldstar                | 7         | 2.75%   |
| Sharp                   | 6         | 2.35%   |
| Apple                   | 5         | 1.96%   |
| Lenovo                  | 3         | 1.18%   |
| Chi Mei Optoelectronics | 3         | 1.18%   |
| Valve                   | 2         | 0.78%   |
| Hewlett-Packard         | 2         | 0.78%   |
| CSO                     | 2         | 0.78%   |
| ASUSTek Computer        | 2         | 0.78%   |
| AOC                     | 2         | 0.78%   |
| Acer                    | 2         | 0.78%   |
| ViewSonic               | 1         | 0.39%   |
| TCL                     | 1         | 0.39%   |
| SKY                     | 1         | 0.39%   |
| Seiko/Epson             | 1         | 0.39%   |
| Quanta Display          | 1         | 0.39%   |
| Panasonic               | 1         | 0.39%   |
| NEC Computers           | 1         | 0.39%   |
| Mi                      | 1         | 0.39%   |
| LPL                     | 1         | 0.39%   |
| Lenovo Group Limited    | 1         | 0.39%   |
| InfoVision              | 1         | 0.39%   |
| HJC                     | 1         | 0.39%   |
| Hitachi                 | 1         | 0.39%   |
| CPT                     | 1         | 0.39%   |
| BenQ                    | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 5         | 1.95%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 4         | 1.56%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 1.17%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 1.17%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 1.17%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 0.78%   |
| LG Display LCD Monitor LGD0454 1366x768 310x174mm 14.0-inch           | 2         | 0.78%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 2         | 0.78%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 2         | 0.78%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 2         | 0.78%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.78%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 0.78%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                  | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO363C 1366x768 309x173mm 13.9-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO353D 1920x1080 309x173mm 13.9-inch        | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 0.78%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 2         | 0.78%   |
| ViewSonic VSC PJD VSCD934 1920x1080                                   | 1         | 0.39%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 1         | 0.39%   |
| SKY TV-monitor SKY1202 1920x1080 885x498mm 40.0-inch                  | 1         | 0.39%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.39%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP14A1 3840x2160 344x194mm 15.5-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 106       | 43.8%   |
| 1366x768 (WXGA)   | 80        | 33.06%  |
| 3840x2160 (4K)    | 11        | 4.55%   |
| 2560x1440 (QHD)   | 8         | 3.31%   |
| 1600x900 (HD+)    | 7         | 2.89%   |
| 1440x900 (WXGA+)  | 5         | 2.07%   |
| 2560x1600         | 3         | 1.24%   |
| 1280x800 (WXGA)   | 3         | 1.24%   |
| 1280x1024 (SXGA)  | 3         | 1.24%   |
| 800x1280          | 2         | 0.83%   |
| 3840x2400         | 2         | 0.83%   |
| 2160x1440         | 2         | 0.83%   |
| 1920x1200 (WUXGA) | 2         | 0.83%   |
| 3520x1080         | 1         | 0.41%   |
| 2880x1800         | 1         | 0.41%   |
| 2256x1504         | 1         | 0.41%   |
| 1920x515          | 1         | 0.41%   |
| 1360x768          | 1         | 0.41%   |
| 1024x768 (XGA)    | 1         | 0.41%   |
| 1024x600          | 1         | 0.41%   |
| Unknown           | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 88        | 34.78%  |
| 14      | 46        | 18.18%  |
| 13      | 39        | 15.42%  |
| 17      | 14        | 5.53%   |
| 11      | 12        | 4.74%   |
| 24      | 7         | 2.77%   |
| 27      | 6         | 2.37%   |
| 23      | 5         | 1.98%   |
| 21      | 5         | 1.98%   |
| Unknown | 5         | 1.98%   |
| 16      | 4         | 1.58%   |
| 12      | 4         | 1.58%   |
| 31      | 3         | 1.19%   |
| 19      | 3         | 1.19%   |
| 18      | 3         | 1.19%   |
| 84      | 2         | 0.79%   |
| 7       | 2         | 0.79%   |
| 54      | 1         | 0.4%    |
| 46      | 1         | 0.4%    |
| 40      | 1         | 0.4%    |
| 20      | 1         | 0.4%    |
| 8       | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 158       | 62.95%  |
| 201-300     | 34        | 13.55%  |
| 501-600     | 18        | 7.17%   |
| 351-400     | 14        | 5.58%   |
| 401-500     | 11        | 4.38%   |
| Unknown     | 5         | 1.99%   |
| 601-700     | 3         | 1.2%    |
| 1501-2000   | 2         | 0.8%    |
| 1001-1500   | 2         | 0.8%    |
| 1-100       | 2         | 0.8%    |
| 801-900     | 1         | 0.4%    |
| 101-200     | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 189       | 85.91%  |
| 16/10   | 17        | 7.73%   |
| 3/2     | 4         | 1.82%   |
| 5/4     | 3         | 1.36%   |
| Unknown | 3         | 1.36%   |
| 0.67    | 2         | 0.91%   |
| 4/3     | 1         | 0.45%   |
| 3.73    | 1         | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 88        | 34.78%  |
| 81-90          | 72        | 28.46%  |
| 201-250        | 15        | 5.93%   |
| 71-80          | 13        | 5.14%   |
| 51-60          | 12        | 4.74%   |
| 121-130        | 11        | 4.35%   |
| 301-350        | 6         | 2.37%   |
| 151-200        | 5         | 1.98%   |
| 141-150        | 5         | 1.98%   |
| Unknown        | 5         | 1.98%   |
| 61-70          | 4         | 1.58%   |
| More than 1000 | 3         | 1.19%   |
| 351-500        | 3         | 1.19%   |
| 1-40           | 3         | 1.19%   |
| 111-120        | 3         | 1.19%   |
| 501-1000       | 2         | 0.79%   |
| 251-300        | 1         | 0.4%    |
| 131-140        | 1         | 0.4%    |
| 91-100         | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 108       | 42.86%  |
| 101-120       | 73        | 28.97%  |
| 51-100        | 34        | 13.49%  |
| 161-240       | 25        | 9.92%   |
| More than 240 | 5         | 1.98%   |
| Unknown       | 5         | 1.98%   |
| 1-50          | 2         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 180       | 79.65%  |
| 2     | 40        | 17.7%   |
| 3     | 3         | 1.33%   |
| 0     | 3         | 1.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 127       | 35.18%  |
| Intel                             | 109       | 30.19%  |
| Qualcomm Atheros                  | 56        | 15.51%  |
| Broadcom                          | 28        | 7.76%   |
| ASIX Electronics                  | 9         | 2.49%   |
| MediaTek                          | 8         | 2.22%   |
| Broadcom Limited                  | 3         | 0.83%   |
| Xiaomi                            | 2         | 0.55%   |
| Ralink Technology                 | 2         | 0.55%   |
| Ralink                            | 2         | 0.55%   |
| Ericsson Business Mobile Networks | 2         | 0.55%   |
| VIA Technologies                  | 1         | 0.28%   |
| TP-Link                           | 1         | 0.28%   |
| Samsung Electronics               | 1         | 0.28%   |
| Qualcomm                          | 1         | 0.28%   |
| Nvidia                            | 1         | 0.28%   |
| Marvell Technology Group          | 1         | 0.28%   |
| Lenovo                            | 1         | 0.28%   |
| JMicron Technology                | 1         | 0.28%   |
| Huawei Technologies               | 1         | 0.28%   |
| D-Link System                     | 1         | 0.28%   |
| D-Link                            | 1         | 0.28%   |
| ASUSTek Computer                  | 1         | 0.28%   |
| Android                           | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 92        | 22.55%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 3.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 2.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 2.94%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 1.96%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.72%   |
| Intel Wireless 7265                                               | 7         | 1.72%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.72%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.47%   |
| Intel Wireless 3160                                               | 6         | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.23%   |
| Intel Wireless-AC 9260                                            | 5         | 1.23%   |
| Intel Wireless 8260                                               | 5         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.23%   |
| Intel Wireless 3165                                               | 4         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.74%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 3         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.74%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 107       | 46.72%  |
| Qualcomm Atheros      | 48        | 20.96%  |
| Realtek Semiconductor | 32        | 13.97%  |
| Broadcom              | 22        | 9.61%   |
| MediaTek              | 8         | 3.49%   |
| Broadcom Limited      | 3         | 1.31%   |
| Ralink Technology     | 2         | 0.87%   |
| Ralink                | 2         | 0.87%   |
| TP-Link               | 1         | 0.44%   |
| Qualcomm              | 1         | 0.44%   |
| D-Link System         | 1         | 0.44%   |
| D-Link                | 1         | 0.44%   |
| ASUSTek Computer      | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 16        | 6.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 5.24%   |
| Intel Wi-Fi 6 AX200                                            | 11        | 4.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 3.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 3.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8         | 3.49%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 3.49%   |
| Intel Wireless 8265 / 8275                                     | 7         | 3.06%   |
| Intel Wireless 7265                                            | 7         | 3.06%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 3.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 3.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 2.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.62%   |
| Intel Wireless 3160                                            | 6         | 2.62%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 2.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 2.18%   |
| Intel Wireless-AC 9260                                         | 5         | 2.18%   |
| Intel Wireless 8260                                            | 5         | 2.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 2.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2.18%   |
| Intel Wireless 3165                                            | 4         | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 1.31%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 1.31%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.31%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.87%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 0.87%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 0.87%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2         | 0.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 0.87%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 0.87%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 0.87%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 111       | 64.53%  |
| Intel                    | 22        | 12.79%  |
| Qualcomm Atheros         | 12        | 6.98%   |
| Broadcom                 | 10        | 5.81%   |
| ASIX Electronics         | 9         | 5.23%   |
| Xiaomi                   | 2         | 1.16%   |
| VIA Technologies         | 1         | 0.58%   |
| Nvidia                   | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| Lenovo                   | 1         | 0.58%   |
| JMicron Technology       | 1         | 0.58%   |
| Huawei Technologies      | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 92        | 52.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 6.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 4%      |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 4%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.86%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.14%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.14%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.14%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                              | 2         | 1.14%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.14%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.57%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.57%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.57%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.57%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.57%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 1         | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.57%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                            | 1         | 0.57%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.57%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.57%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.57%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.57%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.57%   |
| Huawei E353/E3131                                                              | 1         | 0.57%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                                    | 1         | 0.57%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 218       | 56.19%  |
| Ethernet | 166       | 42.78%  |
| Modem    | 3         | 0.77%   |
| Unknown  | 1         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 196       | 83.4%   |
| Ethernet | 39        | 16.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 152       | 68.47%  |
| 1     | 70        | 31.53%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 176       | 77.53%  |
| Yes  | 51        | 22.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 83        | 44.62%  |
| IMC Networks                    | 21        | 11.29%  |
| Lite-On Technology              | 18        | 9.68%   |
| Realtek Semiconductor           | 11        | 5.91%   |
| Qualcomm Atheros Communications | 10        | 5.38%   |
| Broadcom                        | 10        | 5.38%   |
| Foxconn / Hon Hai               | 7         | 3.76%   |
| Apple                           | 5         | 2.69%   |
| Dell                            | 4         | 2.15%   |
| Realtek                         | 3         | 1.61%   |
| Foxconn International           | 3         | 1.61%   |
| Toshiba                         | 2         | 1.08%   |
| MediaTek                        | 2         | 1.08%   |
| Hewlett-Packard                 | 2         | 1.08%   |
| USI                             | 1         | 0.54%   |
| Ralink                          | 1         | 0.54%   |
| Cambridge Silicon Radio         | 1         | 0.54%   |
| ASUSTek Computer                | 1         | 0.54%   |
| Askey Computer                  | 1         | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 30        | 16.13%  |
| Intel AX201 Bluetooth                             | 17        | 9.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 16        | 8.6%    |
| IMC Networks Bluetooth Radio                      | 9         | 4.84%   |
| Intel AX200 Bluetooth                             | 8         | 4.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 7         | 3.76%   |
| IMC Networks Bluetooth Device                     | 7         | 3.76%   |
| Realtek Bluetooth Radio                           | 5         | 2.69%   |
| Foxconn / Hon Hai Bluetooth Device                | 5         | 2.69%   |
| Realtek  Bluetooth 4.2 Adapter                    | 4         | 2.15%   |
| Qualcomm Atheros  Bluetooth Device                | 4         | 2.15%   |
| Lite-On Bluetooth Device                          | 4         | 2.15%   |
| Intel Bluetooth Device                            | 4         | 2.15%   |
| Realtek Bluetooth Radio                           | 3         | 1.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 3         | 1.61%   |
| Intel AX210 Bluetooth                             | 3         | 1.61%   |
| IMC Networks Wireless_Device                      | 3         | 1.61%   |
| Foxconn International BCM43142A0 Bluetooth module | 3         | 1.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 3         | 1.61%   |
| Apple Bluetooth Host Controller                   | 3         | 1.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 1.08%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 2         | 1.08%   |
| MediaTek Wireless_Device                          | 2         | 1.08%   |
| Lite-On Wireless_Device                           | 2         | 1.08%   |
| Lite-On Bluetooth Radio                           | 2         | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                  | 2         | 1.08%   |
| IMC Networks Bluetooth USB Host Controller        | 2         | 1.08%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 2         | 1.08%   |
| Dell BCM20702A0 Bluetooth Module                  | 2         | 1.08%   |
| Broadcom BCM43142A0 Bluetooth Device              | 2         | 1.08%   |
| Apple Bluetooth USB Host Controller               | 2         | 1.08%   |
| USI Bluetooth Device                              | 1         | 0.54%   |
| Toshiba Bluetooth USB Host Controller             | 1         | 0.54%   |
| Toshiba Askey Bluetooth Module                    | 1         | 0.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 1         | 0.54%   |
| Realtek RTL8723B Bluetooth                        | 1         | 0.54%   |
| Ralink RT3290 Bluetooth                           | 1         | 0.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 0.54%   |
| Qualcomm Atheros AR3012 Bluetooth                 | 1         | 0.54%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device      | 1         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 165       | 58.51%  |
| AMD                                          | 54        | 19.15%  |
| Nvidia                                       | 47        | 16.67%  |
| JMTek                                        | 3         | 1.06%   |
| Samson Technologies                          | 2         | 0.71%   |
| Razer USA                                    | 2         | 0.71%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.35%   |
| VIA Technologies                             | 1         | 0.35%   |
| Samsung Electronics                          | 1         | 0.35%   |
| Lenovo                                       | 1         | 0.35%   |
| Huawei Technologies                          | 1         | 0.35%   |
| Dell                                         | 1         | 0.35%   |
| DCMT Technology                              | 1         | 0.35%   |
| Cayin                                        | 1         | 0.35%   |
| BlueTrm                                      | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 38        | 11.01%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 7.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 5.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 4.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15        | 4.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 3.77%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 3.77%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 3.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 2.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 2.61%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 2.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.32%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 2.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.74%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.16%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 4         | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.16%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.87%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.87%   |
| Nvidia Audio device                                                                               | 3         | 0.87%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.87%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.87%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.87%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.87%   |
| Samson Technologies GoMic compact condenser mic                                                   | 2         | 0.58%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 29.5%   |
| SK hynix            | 27        | 19.42%  |
| Micron Technology   | 22        | 15.83%  |
| Kingston            | 18        | 12.95%  |
| Unknown             | 8         | 5.76%   |
| Crucial             | 5         | 3.6%    |
| Transcend           | 4         | 2.88%   |
| Elpida              | 3         | 2.16%   |
| A-DATA Technology   | 2         | 1.44%   |
| Unknown (ABCD)      | 1         | 0.72%   |
| Unknown (08B5)      | 1         | 0.72%   |
| Team                | 1         | 0.72%   |
| Ramaxel Technology  | 1         | 0.72%   |
| Nanya Technology    | 1         | 0.72%   |
| Lexar               | 1         | 0.72%   |
| G.Skill             | 1         | 0.72%   |
| Corsair             | 1         | 0.72%   |
| ASint Technology    | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.78%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.08%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 1.39%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 1.39%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 2         | 1.39%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.39%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.39%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.39%   |
| Micron RAM Module 4096MB SODIMM DDR4 2400MT/s                    | 2         | 1.39%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 1.39%   |
| Crucial RAM CT16G4SFD824A.C16FBR 16GB SODIMM DDR4 2400MT/s       | 2         | 1.39%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 0.69%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1334MT/s                   | 1         | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.69%   |
| Unknown (08B5) RAM IM308GU16N16 8192MB SODIMM DDR3 1333MT/s      | 1         | 0.69%   |
| Transcend RAM JM3200HSG-8G 8GB SODIMM DDR4 3200MT/s              | 1         | 0.69%   |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s              | 1         | 0.69%   |
| Transcend RAM JM2666HSB-8G 8GB SODIMM DDR4 2667MT/s              | 1         | 0.69%   |
| Transcend RAM JM1600KSN-4G 4GB SODIMM DDR3 1600MT/s              | 1         | 0.69%   |
| Team RAM TEAMGROUP-SD4-2133 8GB SODIMM DDR4 2133MT/s             | 1         | 0.69%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.69%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3733MT/s             | 1         | 0.69%   |
| SK hynix RAM Module 4096MB Row Of Chips LPDDR4 3733MT/s          | 1         | 0.69%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.69%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.69%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 55        | 48.25%  |
| DDR3   | 38        | 33.33%  |
| LPDDR4 | 12        | 10.53%  |
| LPDDR3 | 4         | 3.51%   |
| DDR5   | 3         | 2.63%   |
| SDRAM  | 1         | 0.88%   |
| LPDDR5 | 1         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 97        | 85.09%  |
| Row Of Chips | 17        | 14.91%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 49        | 41.88%  |
| 4096  | 40        | 34.19%  |
| 16384 | 16        | 13.68%  |
| 2048  | 11        | 9.4%    |
| 32768 | 1         | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 31        | 25.2%   |
| 3200  | 22        | 17.89%  |
| 2667  | 20        | 16.26%  |
| 2400  | 12        | 9.76%   |
| 2133  | 6         | 4.88%   |
| 4267  | 5         | 4.07%   |
| 1334  | 5         | 4.07%   |
| 3266  | 4         | 3.25%   |
| 1333  | 4         | 3.25%   |
| 4800  | 3         | 2.44%   |
| 1067  | 3         | 2.44%   |
| 4266  | 2         | 1.63%   |
| 3733  | 2         | 1.63%   |
| 8400  | 1         | 0.81%   |
| 6400  | 1         | 0.81%   |
| 4199  | 1         | 0.81%   |
| 1867  | 1         | 0.81%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 33.33%  |
| Samsung Electronics | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Seiko Epson ME-100 Series | 1         | 33.33%  |
| Samsung SCX-4300 Series   | 1         | 33.33%  |
| Canon PIXMA MP280         | 1         | 33.33%  |

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


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 53        | 26.63%  |
| IMC Networks                           | 31        | 15.58%  |
| Bison Electronics                      | 20        | 10.05%  |
| Realtek Semiconductor                  | 19        | 9.55%   |
| Quanta                                 | 15        | 7.54%   |
| Microdia                               | 13        | 6.53%   |
| Acer                                   | 8         | 4.02%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.02%   |
| Sunplus Innovation Technology          | 5         | 2.51%   |
| Suyin                                  | 3         | 1.51%   |
| Silicon Motion                         | 3         | 1.51%   |
| Logitech                               | 3         | 1.51%   |
| Lite-On Technology                     | 3         | 1.51%   |
| Apple                                  | 3         | 1.51%   |
| Samsung Electronics                    | 2         | 1.01%   |
| Generalplus Technology                 | 2         | 1.01%   |
| Z-Star Microelectronics                | 1         | 0.5%    |
| Syntek                                 | 1         | 0.5%    |
| Sonix Technology                       | 1         | 0.5%    |
| Razer USA                              | 1         | 0.5%    |
| Microsoft                              | 1         | 0.5%    |
| Luxvisions Innotech Limited            | 1         | 0.5%    |
| Lenovo                                 | 1         | 0.5%    |
| icSpring                               | 1         | 0.5%    |
| Aveo Technology                        | 1         | 0.5%    |
| Alcor Micro                            | 1         | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 12        | 6.03%   |
| Chicony HD WebCam                                       | 11        | 5.53%   |
| Chicony Integrated Camera                               | 9         | 4.52%   |
| Microdia Integrated_Webcam_HD                           | 6         | 3.02%   |
| Chicony HP Truevision HD camera                         | 6         | 3.02%   |
| Bison Integrated Camera                                 | 6         | 3.02%   |
| Realtek Integrated_Webcam_HD                            | 5         | 2.51%   |
| Realtek HD WebCam                                       | 4         | 2.01%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 4         | 2.01%   |
| IMC Networks Integrated Camera                          | 4         | 2.01%   |
| Chicony Lenovo EasyCamera                               | 4         | 2.01%   |
| Chicony HD User Facing                                  | 4         | 2.01%   |
| Bison SunplusIT Integrated Camera                       | 4         | 2.01%   |
| Silicon Motion WebCam SCB-0385N                         | 3         | 1.51%   |
| Bison ThinkPad Integrated Camera                        | 3         | 1.51%   |
| Acer Lenovo EasyCamera                                  | 3         | 1.51%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.01%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 2         | 1.01%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.01%   |
| Realtek Integrated Webcam                               | 2         | 1.01%   |
| Quanta VGA WebCam                                       | 2         | 1.01%   |
| Quanta USB2.0 HD UVC WebCam                             | 2         | 1.01%   |
| Quanta ov9734_techfront_camera                          | 2         | 1.01%   |
| Quanta HD Webcam                                        | 2         | 1.01%   |
| Quanta HD User Facing                                   | 2         | 1.01%   |
| Quanta HD Camera                                        | 2         | 1.01%   |
| Microdia Integrated Webcam                              | 2         | 1.01%   |
| Microdia CameraA                                        | 2         | 1.01%   |
| Logitech HD Pro Webcam C920                             | 2         | 1.01%   |
| IMC Networks VGA UVC WebCam                             | 2         | 1.01%   |
| IMC Networks ov9734_azurewave_camera                    | 2         | 1.01%   |
| Chicony VGA Webcam                                      | 2         | 1.01%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.01%   |
| Chicony TOSHIBA Web Camera - HD                         | 2         | 1.01%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.01%   |
| Bison Lenovo Integrated Webcam                          | 2         | 1.01%   |
| Bison Lenovo EasyCamera                                 | 2         | 1.01%   |
| Apple FaceTime Camera                                   | 2         | 1.01%   |
| Acer HD Webcam                                          | 2         | 1.01%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 12        | 30.77%  |
| Synaptics                  | 9         | 23.08%  |
| Validity Sensors           | 5         | 12.82%  |
| Elan Microelectronics      | 5         | 12.82%  |
| LighTuning Technology      | 4         | 10.26%  |
| Upek                       | 2         | 5.13%   |
| AuthenTec                  | 2         | 5.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                       | 6         | 15.38%  |
| Shenzhen Goodix  Fingerprint Device                      | 5         | 12.82%  |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 3         | 7.69%   |
| Elan ELAN:Fingerprint                                    | 3         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 2         | 5.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 2         | 5.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 2         | 5.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 2         | 5.13%   |
| Elan ELAN:ARM-M4                                         | 2         | 5.13%   |
| Validity Sensors VFS101 Fingerprint Reader               | 1         | 2.56%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 2.56%   |
| Validity Sensors Synaptics WBDI                          | 1         | 2.56%   |
| Synaptics WBDI Fingerprint Reader USB 086                | 1         | 2.56%   |
| Synaptics WBDI                                           | 1         | 2.56%   |
| Synaptics UWP WBDI Device                                | 1         | 2.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 2.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 2.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.56%   |
| Shenzhen Goodix FingerPrint                              | 1         | 2.56%   |
| AuthenTec AES2810                                        | 1         | 2.56%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 3         | 37.5%   |
| O2 Micro              | 2         | 25%     |
| Broadcom              | 2         | 25%     |
| Gemalto (was Gemplus) | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 146       | 63.76%  |
| 1     | 66        | 28.82%  |
| 2     | 15        | 6.55%   |
| 3     | 2         | 0.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 37        | 37%     |
| Graphics card            | 23        | 23%     |
| Multimedia controller    | 11        | 11%     |
| Net/wireless             | 10        | 10%     |
| Chipcard                 | 8         | 8%      |
| Camera                   | 3         | 3%      |
| Bluetooth                | 3         | 3%      |
| Wireless                 | 1         | 1%      |
| Storage/ide              | 1         | 1%      |
| Flash memory             | 1         | 1%      |
| Communication controller | 1         | 1%      |
| Card reader              | 1         | 1%      |

