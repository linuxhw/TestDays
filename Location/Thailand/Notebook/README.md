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

Total: 295

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 28        | 12.73%  |
| Pop!_OS 22.04                | 11        | 5%      |
| OpenMandriva 4.2             | 9         | 4.09%   |
| Ubuntu 22.04                 | 8         | 3.64%   |
| Ubuntu 18.04                 | 8         | 3.64%   |
| KDE neon 20.04               | 8         | 3.64%   |
| Debian 11                    | 8         | 3.64%   |
| Linux Mint 21                | 6         | 2.73%   |
| Fedora 37                    | 6         | 2.73%   |
| Debian 10                    | 5         | 2.27%   |
| Arch Rolling                 | 5         | 2.27%   |
| Arch                         | 5         | 2.27%   |
| Ubuntu 19.10                 | 4         | 1.82%   |
| Ubuntu 19.04                 | 4         | 1.82%   |
| OpenMandriva 23.01           | 4         | 1.82%   |
| Linux Mint 20.2              | 4         | 1.82%   |
| Zorin 15                     | 3         | 1.36%   |
| Ubuntu 18.10                 | 3         | 1.36%   |
| Ubuntu 16.04                 | 3         | 1.36%   |
| Pop!_OS 21.04                | 3         | 1.36%   |
| OpenMandriva 4.3             | 3         | 1.36%   |
| Linux Mint 19.2              | 3         | 1.36%   |
| Kubuntu 20.04                | 3         | 1.36%   |
| Debian Testing               | 3         | 1.36%   |
| Zorin 16                     | 2         | 0.91%   |
| Xubuntu 20.04                | 2         | 0.91%   |
| Ubuntu MATE 20.10            | 2         | 0.91%   |
| Ubuntu MATE 20.04            | 2         | 0.91%   |
| Pop!_OS 20.04                | 2         | 0.91%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.91%   |
| MX 19                        | 2         | 0.91%   |
| Linux Mint 20.3              | 2         | 0.91%   |
| Linux Mint 19.3              | 2         | 0.91%   |
| Kubuntu 22.04                | 2         | 0.91%   |
| KDE neon 22.04               | 2         | 0.91%   |
| Fedora 36                    | 2         | 0.91%   |
| Fedora 33                    | 2         | 0.91%   |
| Endless 3.7.7                | 2         | 0.91%   |
| ArcoLinux Rolling            | 2         | 0.91%   |
| Xubuntu 18.04                | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 58        | 27.36%  |
| Linux Mint   | 20        | 9.43%   |
| Pop!_OS      | 17        | 8.02%   |
| OpenMandriva | 17        | 8.02%   |
| Debian       | 16        | 7.55%   |
| Fedora       | 13        | 6.13%   |
| KDE neon     | 10        | 4.72%   |
| Arch         | 10        | 4.72%   |
| Endless      | 6         | 2.83%   |
| Zorin        | 5         | 2.36%   |
| Ubuntu MATE  | 5         | 2.36%   |
| Kubuntu      | 5         | 2.36%   |
| Xubuntu      | 3         | 1.42%   |
| openSUSE     | 3         | 1.42%   |
| MX           | 3         | 1.42%   |
| Clear Linux  | 3         | 1.42%   |
| Manjaro      | 2         | 0.94%   |
| Lubuntu      | 2         | 0.94%   |
| Kali         | 2         | 0.94%   |
| Elementary   | 2         | 0.94%   |
| ArcoLinux    | 2         | 0.94%   |
| UbuntuDDE    | 1         | 0.47%   |
| Ubuntu Unity | 1         | 0.47%   |
| ROSA         | 1         | 0.47%   |
| Linux Lite   | 1         | 0.47%   |
| Lilidog      | 1         | 0.47%   |
| Garuda Linux | 1         | 0.47%   |
| EndeavourOS  | 1         | 0.47%   |
| BlackPanther | 1         | 0.47%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002   | 9         | 3.75%   |
| 5.15.0-46-generic          | 6         | 2.5%    |
| 6.1.1-desktop-1omv2290     | 4         | 1.67%   |
| 6.0.6-76060006-generic     | 3         | 1.25%   |
| 6.0.12-76060006-generic    | 3         | 1.25%   |
| 5.8.0-50-generic           | 3         | 1.25%   |
| 5.4.0-42-generic           | 3         | 1.25%   |
| 5.3.0-28-generic           | 3         | 1.25%   |
| 5.16.7-desktop-1omv4003    | 3         | 1.25%   |
| 5.15.0-58-generic          | 3         | 1.25%   |
| 5.11.0-40-generic          | 3         | 1.25%   |
| 5.0.0-32-generic           | 3         | 1.25%   |
| 5.0.0-27-generic           | 3         | 1.25%   |
| 4.18.0-15-generic          | 3         | 1.25%   |
| 6.1.11-200.fc37.x86_64     | 2         | 0.83%   |
| 5.8.14-arch1-1             | 2         | 0.83%   |
| 5.8.0-59-generic           | 2         | 0.83%   |
| 5.8.0-29-generic           | 2         | 0.83%   |
| 5.4.0-81-generic           | 2         | 0.83%   |
| 5.4.0-73-generic           | 2         | 0.83%   |
| 5.4.0-58-generic           | 2         | 0.83%   |
| 5.4.0-40-generic           | 2         | 0.83%   |
| 5.4.0-39-generic           | 2         | 0.83%   |
| 5.4.0-31-generic           | 2         | 0.83%   |
| 5.3.0-20-generic           | 2         | 0.83%   |
| 5.19.0-32-generic          | 2         | 0.83%   |
| 5.15.0-52-generic          | 2         | 0.83%   |
| 5.13.0-39-generic          | 2         | 0.83%   |
| 5.12.0-19.3-liquorix-amd64 | 2         | 0.83%   |
| 5.11.0-43-generic          | 2         | 0.83%   |
| 5.11.0-34-generic          | 2         | 0.83%   |
| 5.10.0-21-amd64            | 2         | 0.83%   |
| 5.0.0-25-generic           | 2         | 0.83%   |
| 4.19.0-6-amd64             | 2         | 0.83%   |
| 4.19.0-16-amd64            | 2         | 0.83%   |
| 4.15.0-70-generic          | 2         | 0.83%   |
| 4.15.0-51-generic          | 2         | 0.83%   |
| 4.15.0-48-generic          | 2         | 0.83%   |
| 6.1.8-x64v1-xanmod1-1      | 1         | 0.42%   |
| 6.1.12-arch1-1             | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 32        | 13.68%  |
| 5.15.0  | 22        | 9.4%    |
| 5.8.0   | 13        | 5.56%   |
| 4.15.0  | 13        | 5.56%   |
| 5.13.0  | 11        | 4.7%    |
| 5.11.0  | 11        | 4.7%    |
| 5.3.0   | 10        | 4.27%   |
| 5.10.14 | 9         | 3.85%   |
| 5.0.0   | 9         | 3.85%   |
| 4.19.0  | 7         | 2.99%   |
| 4.18.0  | 7         | 2.99%   |
| 5.10.0  | 6         | 2.56%   |
| 6.1.1   | 5         | 2.14%   |
| 5.19.0  | 5         | 2.14%   |
| 6.0.6   | 3         | 1.28%   |
| 6.0.12  | 3         | 1.28%   |
| 5.16.7  | 3         | 1.28%   |
| 6.1.12  | 2         | 0.85%   |
| 6.1.11  | 2         | 0.85%   |
| 5.8.14  | 2         | 0.85%   |
| 5.18.0  | 2         | 0.85%   |
| 5.17.5  | 2         | 0.85%   |
| 5.17.0  | 2         | 0.85%   |
| 5.16.0  | 2         | 0.85%   |
| 5.12.0  | 2         | 0.85%   |
| 6.1.8   | 1         | 0.43%   |
| 6.1.10  | 1         | 0.43%   |
| 6.0.8   | 1         | 0.43%   |
| 6.0.7   | 1         | 0.43%   |
| 6.0.2   | 1         | 0.43%   |
| 6.0.0   | 1         | 0.43%   |
| 5.9.14  | 1         | 0.43%   |
| 5.9.12  | 1         | 0.43%   |
| 5.9.11  | 1         | 0.43%   |
| 5.9.10  | 1         | 0.43%   |
| 5.8.4   | 1         | 0.43%   |
| 5.7.7   | 1         | 0.43%   |
| 5.6.15  | 1         | 0.43%   |
| 5.6.14  | 1         | 0.43%   |
| 5.6.0   | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 14.85%  |
| 5.15    | 26        | 11.35%  |
| 5.10    | 18        | 7.86%   |
| 5.8     | 16        | 6.99%   |
| 5.13    | 13        | 5.68%   |
| 4.15    | 13        | 5.68%   |
| 6.1     | 11        | 4.8%    |
| 5.3     | 11        | 4.8%    |
| 5.11    | 11        | 4.8%    |
| 6.0     | 10        | 4.37%   |
| 5.19    | 10        | 4.37%   |
| 5.16    | 10        | 4.37%   |
| 5.0     | 9         | 3.93%   |
| 4.18    | 8         | 3.49%   |
| 4.19    | 7         | 3.06%   |
| 5.18    | 5         | 2.18%   |
| 5.17    | 4         | 1.75%   |
| 5.12    | 4         | 1.75%   |
| 5.9     | 3         | 1.31%   |
| 5.6     | 3         | 1.31%   |
| 5.5     | 2         | 0.87%   |
| 5.7     | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 205       | 98.56%  |
| i686   | 3         | 1.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 96        | 45.07%  |
| KDE5             | 35        | 16.43%  |
| Unknown          | 27        | 12.68%  |
| X-Cinnamon       | 18        | 8.45%   |
| XFCE             | 13        | 6.1%    |
| KDE              | 7         | 3.29%   |
| MATE             | 5         | 2.35%   |
| Pantheon         | 2         | 0.94%   |
| Budgie           | 2         | 0.94%   |
| Unity            | 1         | 0.47%   |
| LXQt             | 1         | 0.47%   |
| LXDE             | 1         | 0.47%   |
| lightdm-xsession | 1         | 0.47%   |
| i3               | 1         | 0.47%   |
| Deepin           | 1         | 0.47%   |
| Cinnamon         | 1         | 0.47%   |
| awesome          | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 164       | 76.64%  |
| Wayland | 33        | 15.42%  |
| Unknown | 15        | 7.01%   |
| Tty     | 2         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 105       | 49.07%  |
| SDDM    | 32        | 14.95%  |
| GDM     | 30        | 14.02%  |
| LightDM | 20        | 9.35%   |
| GDM3    | 19        | 8.88%   |
| TDM     | 6         | 2.8%    |
| XDM     | 1         | 0.47%   |
| Ly      | 1         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 145       | 68.72%  |
| Unknown | 27        | 12.8%   |
| en_GB   | 9         | 4.27%   |
| th_TH   | 7         | 3.32%   |
| de_DE   | 7         | 3.32%   |
| en_SG   | 5         | 2.37%   |
| fr_FR   | 4         | 1.9%    |
| ru_RU   | 3         | 1.42%   |
| C       | 3         | 1.42%   |
| es_MX   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 128       | 61.24%  |
| BIOS | 81        | 38.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 171       | 81.04%  |
| Overlay | 18        | 8.53%   |
| Btrfs   | 16        | 7.58%   |
| Unknown | 5         | 2.37%   |
| Zfs     | 1         | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 110       | 52.13%  |
| GPT     | 88        | 41.71%  |
| MBR     | 13        | 6.16%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 182       | 87.08%  |
| Yes       | 27        | 12.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 145       | 67.76%  |
| Yes       | 69        | 32.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 47        | 22.6%   |
| ASUSTek Computer               | 37        | 17.79%  |
| Acer                           | 35        | 16.83%  |
| Hewlett-Packard                | 23        | 11.06%  |
| Dell                           | 23        | 11.06%  |
| MSI                            | 11        | 5.29%   |
| HUAWEI                         | 5         | 2.4%    |
| Apple                          | 5         | 2.4%    |
| Samsung Electronics            | 4         | 1.92%   |
| Toshiba                        | 3         | 1.44%   |
| Fujitsu                        | 2         | 0.96%   |
| Unknown                        | 2         | 0.96%   |
| Timi                           | 1         | 0.48%   |
| Sony                           | 1         | 0.48%   |
| SmbiosType1_SystemManufacturer | 1         | 0.48%   |
| Razer                          | 1         | 0.48%   |
| Notebook                       | 1         | 0.48%   |
| Infinix                        | 1         | 0.48%   |
| Hampoo                         | 1         | 0.48%   |
| Gigabyte Technology            | 1         | 0.48%   |
| Framework                      | 1         | 0.48%   |
| Foxconn                        | 1         | 0.48%   |
| Clevo                          | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                         | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 3         | 1.44%   |
| Samsung NC208/NC108                                          | 2         | 0.96%   |
| Lenovo ThinkPad 11e 5th Gen 20LQS00000                       | 2         | 0.96%   |
| Lenovo G460 20041                                            | 2         | 0.96%   |
| Dell Latitude E6430                                          | 2         | 0.96%   |
| Dell Latitude 3120                                           | 2         | 0.96%   |
| ASUS X556UQK                                                 | 2         | 0.96%   |
| ASUS X450LN                                                  | 2         | 0.96%   |
| ASUS VivoBook_ASUSLaptop M3500QA_D3500QA                     | 2         | 0.96%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA                      | 2         | 0.96%   |
| ASUS TUF Gaming FX505DT_FX505DT                              | 2         | 0.96%   |
| Apple MacBookAir3,2                                          | 2         | 0.96%   |
| Acer Aspire F5-573G                                          | 2         | 0.96%   |
| Acer Aspire E5-471G                                          | 2         | 0.96%   |
| Acer Aspire A315-21                                          | 2         | 0.96%   |
| Toshiba Satellite L840                                       | 1         | 0.48%   |
| Toshiba Satellite L645                                       | 1         | 0.48%   |
| Toshiba QOSMIO X70-B                                         | 1         | 0.48%   |
| Timi TM1701                                                  | 1         | 0.48%   |
| Sony SVF14N25CXB                                             | 1         | 0.48%   |
| SmbiosType1_SystemManufacturer SmbiosType1_SystemProductName | 1         | 0.48%   |
| Samsung RV418/RV518/RV718                                    | 1         | 0.48%   |
| Samsung R780/R778                                            | 1         | 0.48%   |
| Razer Blade 15 (2022) - RZ09-0421                            | 1         | 0.48%   |
| Notebook NV4XMB,ME,MZ                                        | 1         | 0.48%   |
| MSI X460/X460DX                                              | 1         | 0.48%   |
| MSI Raider GE77HX 12UHS                                      | 1         | 0.48%   |
| MSI Prestige 15 A10SC                                        | 1         | 0.48%   |
| MSI PE70 6QE                                                 | 1         | 0.48%   |
| MSI MS-14Y1                                                  | 1         | 0.48%   |
| MSI GP63 Leopard 8RE                                         | 1         | 0.48%   |
| MSI GF65 Thin 10UE                                           | 1         | 0.48%   |
| MSI GF63 Thin 9SCSR                                          | 1         | 0.48%   |
| MSI GE76 Raider 10UH                                         | 1         | 0.48%   |
| MSI GE75 Raider 10SGS                                        | 1         | 0.48%   |
| MSI Bravo 15 B5ED                                            | 1         | 0.48%   |
| Lenovo Z50-70 20354                                          | 1         | 0.48%   |
| Lenovo Yoga Slim 7 14ARE05 82A2                              | 1         | 0.48%   |
| Lenovo Y50-70 20378                                          | 1         | 0.48%   |
| Lenovo ThinkPad X230 23331R5                                 | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 24        | 11.54%  |
| Acer Aspire                                | 24        | 11.54%  |
| Lenovo IdeaPad                             | 11        | 5.29%   |
| ASUS VivoBook                              | 10        | 4.81%   |
| Dell Latitude                              | 8         | 3.85%   |
| HP Pavilion                                | 7         | 3.37%   |
| HP Laptop                                  | 6         | 2.88%   |
| Dell Inspiron                              | 6         | 2.88%   |
| ASUS TUF                                   | 5         | 2.4%    |
| ASUS ZenBook                               | 4         | 1.92%   |
| HP EliteBook                               | 3         | 1.44%   |
| Dell Vostro                                | 3         | 1.44%   |
| Dell Precision                             | 3         | 1.44%   |
| Acer TravelMate                            | 3         | 1.44%   |
| Acer Swift                                 | 3         | 1.44%   |
| Unknown                                    | 3         | 1.44%   |
| Toshiba Satellite                          | 2         | 0.96%   |
| Samsung NC208                              | 2         | 0.96%   |
| Lenovo ThinkBook                           | 2         | 0.96%   |
| Lenovo G460                                | 2         | 0.96%   |
| HP Stream                                  | 2         | 0.96%   |
| HP Compaq                                  | 2         | 0.96%   |
| Fujitsu LIFEBOOK                           | 2         | 0.96%   |
| ASUS X556UQK                               | 2         | 0.96%   |
| ASUS X450LN                                | 2         | 0.96%   |
| Apple MacBookPro11                         | 2         | 0.96%   |
| Apple MacBookAir3                          | 2         | 0.96%   |
| Acer Nitro                                 | 2         | 0.96%   |
| Toshiba QOSMIO                             | 1         | 0.48%   |
| Timi TM1701                                | 1         | 0.48%   |
| Sony SVF14N25CXB                           | 1         | 0.48%   |
| SmbiosType1_SystemManufacturer SmbiosType1 | 1         | 0.48%   |
| Samsung RV418                              | 1         | 0.48%   |
| Samsung R780                               | 1         | 0.48%   |
| Razer Blade                                | 1         | 0.48%   |
| Notebook NV4XMB                            | 1         | 0.48%   |
| MSI X460                                   | 1         | 0.48%   |
| MSI Raider                                 | 1         | 0.48%   |
| MSI Prestige                               | 1         | 0.48%   |
| MSI PE70                                   | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 25        | 12.02%  |
| 2018 | 23        | 11.06%  |
| 2021 | 21        | 10.1%   |
| 2019 | 20        | 9.62%   |
| 2014 | 18        | 8.65%   |
| 2015 | 16        | 7.69%   |
| 2016 | 15        | 7.21%   |
| 2012 | 15        | 7.21%   |
| 2011 | 12        | 5.77%   |
| 2017 | 10        | 4.81%   |
| 2022 | 9         | 4.33%   |
| 2010 | 9         | 4.33%   |
| 2013 | 6         | 2.88%   |
| 2009 | 3         | 1.44%   |
| 2008 | 3         | 1.44%   |
| 2007 | 2         | 0.96%   |
| 2006 | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 208       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 181       | 86.6%   |
| Enabled  | 28        | 13.4%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 208       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 58        | 27.75%  |
| 3.01-4.0    | 44        | 21.05%  |
| 16.01-24.0  | 37        | 17.7%   |
| 8.01-16.0   | 37        | 17.7%   |
| 32.01-64.0  | 17        | 8.13%   |
| 1.01-2.0    | 8         | 3.83%   |
| 24.01-32.0  | 4         | 1.91%   |
| 64.01-256.0 | 2         | 0.96%   |
| 2.01-3.0    | 1         | 0.48%   |
| 0.51-1.0    | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 80        | 35.87%  |
| 2.01-3.0   | 58        | 26.01%  |
| 4.01-8.0   | 34        | 15.25%  |
| 3.01-4.0   | 30        | 13.45%  |
| 8.01-16.0  | 12        | 5.38%   |
| 0.51-1.0   | 7         | 3.14%   |
| 16.01-24.0 | 1         | 0.45%   |
| 0.01-0.5   | 1         | 0.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 145       | 67.44%  |
| 2      | 55        | 25.58%  |
| 3      | 10        | 4.65%   |
| 0      | 3         | 1.4%    |
| 5      | 1         | 0.47%   |
| 4      | 1         | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 156       | 75%     |
| Yes       | 52        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 75.24%  |
| No        | 52        | 24.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 98.09%  |
| No        | 4         | 1.91%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 171       | 80.66%  |
| No        | 41        | 19.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Thailand | 208       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Bangkok             | 92        | 41.07%  |
| Chiang Mai          | 15        | 6.7%    |
| Nonthaburi          | 9         | 4.02%   |
| Phuket              | 8         | 3.57%   |
| Bang Lamung         | 8         | 3.57%   |
| Khon Kaen           | 7         | 3.13%   |
| Surat Thani         | 4         | 1.79%   |
| Surin               | 3         | 1.34%   |
| Rayong              | 3         | 1.34%   |
| Nakhon Pathom       | 3         | 1.34%   |
| Songkhla            | 2         | 0.89%   |
| Phayao              | 2         | 0.89%   |
| Pattaya             | 2         | 0.89%   |
| Pak Kret            | 2         | 0.89%   |
| Nakhon Ratchasima   | 2         | 0.89%   |
| Maha Sarakham       | 2         | 0.89%   |
| Khlong Luang        | 2         | 0.89%   |
| Hua Hin             | 2         | 0.89%   |
| Chiang Rai          | 2         | 0.89%   |
| Chanthaburi         | 2         | 0.89%   |
| Bang Bua Thong      | 2         | 0.89%   |
| Bang Bon            | 2         | 0.89%   |
| Ban Yang Sam Ton    | 2         | 0.89%   |
| Ban Phan Don        | 2         | 0.89%   |
| Yala                | 1         | 0.45%   |
| Udon Thani          | 1         | 0.45%   |
| Suan Luang          | 1         | 0.45%   |
| Si Sa Ket           | 1         | 0.45%   |
| Si Racha            | 1         | 0.45%   |
| Sattahip            | 1         | 0.45%   |
| Samut Prakan        | 1         | 0.45%   |
| Salaya              | 1         | 0.45%   |
| Rasi Salai          | 1         | 0.45%   |
| Prathai             | 1         | 0.45%   |
| Prachuap Khiri Khan | 1         | 0.45%   |
| Phitsanulok         | 1         | 0.45%   |
| Phetchaburi         | 1         | 0.45%   |
| Phen                | 1         | 0.45%   |
| Phan                | 1         | 0.45%   |
| Pattani             | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 52        | 61     | 19.48%  |
| Samsung Electronics | 36        | 47     | 13.48%  |
| Seagate             | 34        | 44     | 12.73%  |
| Toshiba             | 23        | 29     | 8.61%   |
| SanDisk             | 17        | 23     | 6.37%   |
| Unknown             | 16        | 20     | 5.99%   |
| Kingston            | 13        | 15     | 4.87%   |
| Intel               | 12        | 13     | 4.49%   |
| SK hynix            | 8         | 14     | 3%      |
| HGST                | 6         | 7      | 2.25%   |
| Micron Technology   | 5         | 6      | 1.87%   |
| Hitachi             | 5         | 5      | 1.87%   |
| Transcend           | 4         | 5      | 1.5%    |
| Apple               | 4         | 4      | 1.5%    |
| SPCC                | 3         | 3      | 1.12%   |
| Silicon Motion      | 3         | 4      | 1.12%   |
| Crucial             | 3         | 3      | 1.12%   |
| Phison Electronics  | 2         | 3      | 0.75%   |
| KIOXIA              | 2         | 4      | 0.75%   |
| Kingmax             | 2         | 4      | 0.75%   |
| China               | 2         | 2      | 0.75%   |
| XPG                 | 1         | 1      | 0.37%   |
| USB3.0              | 1         | 2      | 0.37%   |
| Teelkoou            | 1         | 1      | 0.37%   |
| Team                | 1         | 1      | 0.37%   |
| ShiJi               | 1         | 1      | 0.37%   |
| PNY                 | 1         | 2      | 0.37%   |
| Plextor             | 1         | 1      | 0.37%   |
| Pioneer             | 1         | 1      | 0.37%   |
| LITEON              | 1         | 2      | 0.37%   |
| Lite-On             | 1         | 2      | 0.37%   |
| HS-SSD-C100         | 1         | 1      | 0.37%   |
| GAMER               | 1         | 1      | 0.37%   |
| Fujitsu             | 1         | 2      | 0.37%   |
| Apacer              | 1         | 1      | 0.37%   |
| A-DATA Technology   | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                              | 6         | 2.2%    |
| Seagate ST1000LM035-1RK172 1TB                      | 6         | 2.2%    |
| Unknown MMC Card  32GB                              | 5         | 1.83%   |
| Toshiba MQ04ABF100 1TB                              | 5         | 1.83%   |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 1.83%   |
| Unknown MMC Card  64GB                              | 4         | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 1.47%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                | 4         | 1.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 1.1%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 3         | 1.1%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 3         | 1.1%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 3         | 1.1%    |
| WDC WD10SPZX-21Z10T0 1TB                            | 3         | 1.1%    |
| WDC WD10JPVX-22JC3T0 1TB                            | 3         | 1.1%    |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB                  | 3         | 1.1%    |
| SK hynix HFM512GD3JX013N 512GB                      | 3         | 1.1%    |
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 1.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 3         | 1.1%    |
| Kingston NVMe SSD Drive 512GB                       | 3         | 1.1%    |
| HGST HTS721010A9E630 1TB                            | 3         | 1.1%    |
| WDC WD5000BPVT-22HXZT3 500GB                        | 2         | 0.73%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 2         | 0.73%   |
| Unknown SD/MMC/MS PRO 64GB                          | 2         | 0.73%   |
| Unknown DA4064  64GB                                | 2         | 0.73%   |
| Toshiba MQ01ABF032 320GB                            | 2         | 0.73%   |
| Toshiba KBG30ZMT128G 128GB                          | 2         | 0.73%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 2         | 0.73%   |
| Seagate ST9500325AS 500GB                           | 2         | 0.73%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 0.73%   |
| SanDisk NVMe SSD Drive 512GB                        | 2         | 0.73%   |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 0.73%   |
| Samsung SSD 970 EVO Plus 500GB                      | 2         | 0.73%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2         | 0.73%   |
| Samsung NVMe SSD Drive 512GB                        | 2         | 0.73%   |
| Phison E12 NVMe Controller 256GB                    | 2         | 0.73%   |
| KIOXIA KBG40ZNS128G NVMe 128GB                      | 2         | 0.73%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 0.73%   |
| Intel SSDPEKNW512G8 512GB                           | 2         | 0.73%   |
| Intel NVMe SSD Drive 512GB                          | 2         | 0.73%   |
| Intel NVMe SSD Drive 1024GB                         | 2         | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 44     | 35.42%  |
| WDC                 | 26        | 28     | 27.08%  |
| Toshiba             | 18        | 22     | 18.75%  |
| HGST                | 6         | 7      | 6.25%   |
| Hitachi             | 5         | 5      | 5.21%   |
| Unknown             | 2         | 2      | 2.08%   |
| Samsung Electronics | 2         | 3      | 2.08%   |
| USB3.0              | 1         | 2      | 1.04%   |
| Pioneer             | 1         | 1      | 1.04%   |
| Fujitsu             | 1         | 2      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 24     | 25%     |
| Samsung Electronics | 13        | 19     | 18.06%  |
| SanDisk             | 7         | 12     | 9.72%   |
| Kingston            | 6         | 7      | 8.33%   |
| Apple               | 4         | 4      | 5.56%   |
| SPCC                | 3         | 3      | 4.17%   |
| Crucial             | 3         | 3      | 4.17%   |
| Transcend           | 2         | 3      | 2.78%   |
| SK hynix            | 2         | 2      | 2.78%   |
| Micron Technology   | 2         | 3      | 2.78%   |
| Kingmax             | 2         | 4      | 2.78%   |
| Intel               | 2         | 2      | 2.78%   |
| China               | 2         | 2      | 2.78%   |
| Teelkoou            | 1         | 1      | 1.39%   |
| Team                | 1         | 1      | 1.39%   |
| PNY                 | 1         | 2      | 1.39%   |
| Plextor             | 1         | 1      | 1.39%   |
| LITEON              | 1         | 2      | 1.39%   |
| Apacer              | 1         | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 91        | 116    | 35.97%  |
| NVMe    | 79        | 103    | 31.23%  |
| SSD     | 66        | 96     | 26.09%  |
| MMC     | 14        | 18     | 5.53%   |
| Unknown | 3         | 3      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 135       | 205    | 57.69%  |
| NVMe | 79        | 103    | 33.76%  |
| MMC  | 14        | 18     | 5.98%   |
| SAS  | 6         | 10     | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 86        | 125    | 55.84%  |
| 0.51-1.0   | 62        | 78     | 40.26%  |
| 1.01-2.0   | 6         | 9      | 3.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 53        | 24.31%  |
| 101-250        | 45        | 20.64%  |
| 501-1000       | 40        | 18.35%  |
| 1-20           | 19        | 8.72%   |
| 51-100         | 18        | 8.26%   |
| 1001-2000      | 16        | 7.34%   |
| 21-50          | 15        | 6.88%   |
| More than 3000 | 4         | 1.83%   |
| 2001-3000      | 4         | 1.83%   |
| Unknown        | 4         | 1.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 90        | 40%     |
| 21-50     | 41        | 18.22%  |
| 101-250   | 30        | 13.33%  |
| 251-500   | 23        | 10.22%  |
| 51-100    | 20        | 8.89%   |
| 501-1000  | 11        | 4.89%   |
| 1001-2000 | 6         | 2.67%   |
| Unknown   | 4         | 1.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB            | 2         | 2      | 13.33%  |
| Seagate ST1000LM049-2GH172 1TB    | 2         | 2      | 13.33%  |
| Seagate ST1000LM035-1RK172 1TB    | 2         | 2      | 13.33%  |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 2      | 6.67%   |
| USB3.0 Super Speed 500GB          | 1         | 2      | 6.67%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 6.67%   |
| Seagate ST500LM000-SSHD-8GB       | 1         | 1      | 6.67%   |
| SanDisk SDSSDX240GG25 240GB       | 1         | 1      | 6.67%   |
| Samsung Electronics HM160HI 160GB | 1         | 2      | 6.67%   |
| Intel SSDSC2KF256H6 SATA 256GB    | 1         | 1      | 6.67%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 6.67%   |
| HGST HTS721010A9E630 1TB          | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 40%     |
| Toshiba             | 2         | 2      | 13.33%  |
| HGST                | 2         | 2      | 13.33%  |
| WDC                 | 1         | 2      | 6.67%   |
| USB3.0              | 1         | 2      | 6.67%   |
| SanDisk             | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 2      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 46.15%  |
| Toshiba             | 2         | 2      | 15.38%  |
| HGST                | 2         | 2      | 15.38%  |
| WDC                 | 1         | 2      | 7.69%   |
| USB3.0              | 1         | 2      | 7.69%   |
| Samsung Electronics | 1         | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 16     | 86.67%  |
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
| Detected | 126       | 213    | 57.8%   |
| Works    | 76        | 104    | 34.86%  |
| Malfunc  | 15        | 18     | 6.88%   |
| Failed   | 1         | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 130       | 53.72%  |
| AMD                          | 28        | 11.57%  |
| Samsung Electronics          | 27        | 11.16%  |
| SanDisk                      | 19        | 7.85%   |
| Kingston Technology Company  | 7         | 2.89%   |
| SK hynix                     | 6         | 2.48%   |
| Toshiba America Info Systems | 5         | 2.07%   |
| Silicon Motion               | 4         | 1.65%   |
| Nvidia                       | 4         | 1.65%   |
| Micron Technology            | 3         | 1.24%   |
| Phison Electronics           | 2         | 0.83%   |
| KIOXIA                       | 2         | 0.83%   |
| ADATA Technology             | 2         | 0.83%   |
| VIA Technologies             | 1         | 0.41%   |
| Transcend                    | 1         | 0.41%   |
| Lite-On Technology           | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 10.59%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 17        | 6.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 6.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 14        | 5.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 4.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 3.53%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 7         | 2.75%   |
| Intel SSD 660P Series                                                            | 7         | 2.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 2.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 6         | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.35%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 5         | 1.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 1.96%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.57%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 1.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.57%   |
| Micron NVMe Storage Controller                                                   | 3         | 1.18%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 1.18%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 1.18%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.78%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.78%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.78%   |
| SanDisk NVMe Controller                                                          | 2         | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.78%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.78%   |
| Samsung Apple PCIe SSD                                                           | 2         | 0.78%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.78%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 0.78%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.78%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.78%   |
| Intel SSD 600P Series                                                            | 2         | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 143       | 58.61%  |
| NVMe | 82        | 33.61%  |
| RAID | 12        | 4.92%   |
| IDE  | 7         | 2.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 164       | 78.85%  |
| AMD    | 44        | 21.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 3.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 2.88%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 2.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 2.88%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 2.4%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.92%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 1.92%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 1.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.92%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.44%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.44%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 1.44%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.44%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.44%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.44%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 3         | 1.44%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.96%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.96%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.96%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.96%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.96%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.96%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.96%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.96%   |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 2         | 0.96%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.96%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 0.96%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.96%   |
| Intel Core 2 Duo CPU L9600 @ 2.13GHz          | 2         | 0.96%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 2         | 0.96%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 0.96%   |
| Intel Atom x5-Z8500 CPU @ 1.44GHz             | 2         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 54        | 25.96%  |
| Intel Core i5           | 43        | 20.67%  |
| AMD Ryzen 5             | 16        | 7.69%   |
| Intel Core i3           | 14        | 6.73%   |
| Other                   | 13        | 6.25%   |
| Intel Celeron           | 10        | 4.81%   |
| Intel Pentium           | 9         | 4.33%   |
| Intel Core 2 Duo        | 9         | 4.33%   |
| AMD Ryzen 7             | 9         | 4.33%   |
| Intel Atom              | 6         | 2.88%   |
| AMD Ryzen 9             | 3         | 1.44%   |
| AMD Ryzen 3             | 3         | 1.44%   |
| AMD A4                  | 3         | 1.44%   |
| Intel Pentium Silver    | 2         | 0.96%   |
| AMD Ryzen 7 PRO         | 2         | 0.96%   |
| AMD Athlon              | 2         | 0.96%   |
| Intel Xeon              | 1         | 0.48%   |
| Intel Pentium Dual      | 1         | 0.48%   |
| Intel Core m3           | 1         | 0.48%   |
| Intel Core i9           | 1         | 0.48%   |
| AMD Turion 64 X2 Mobile | 1         | 0.48%   |
| AMD Ryzen 5 PRO         | 1         | 0.48%   |
| AMD E2                  | 1         | 0.48%   |
| AMD E1                  | 1         | 0.48%   |
| AMD A8                  | 1         | 0.48%   |
| AMD A10                 | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 87        | 41.63%  |
| 4      | 84        | 40.19%  |
| 6      | 19        | 9.09%   |
| 8      | 14        | 6.7%    |
| 14     | 2         | 0.96%   |
| 1      | 2         | 0.96%   |
| 16     | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 208       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 165       | 78.57%  |
| 1      | 45        | 21.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 203       | 97.6%   |
| Unknown        | 4         | 1.92%   |
| 32-bit         | 1         | 0.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 24.54%  |
| 0x306a9    | 13        | 6.02%   |
| 0x206a7    | 10        | 4.63%   |
| 0x806e9    | 9         | 4.17%   |
| 0x806ec    | 8         | 3.7%    |
| 0x806c1    | 8         | 3.7%    |
| 0x40651    | 8         | 3.7%    |
| 0x806ea    | 7         | 3.24%   |
| 0x08108102 | 6         | 2.78%   |
| 0x906ea    | 5         | 2.31%   |
| 0x306c3    | 5         | 2.31%   |
| 0x1067a    | 5         | 2.31%   |
| 0x706a1    | 4         | 1.85%   |
| 0x506e3    | 4         | 1.85%   |
| 0x406e3    | 4         | 1.85%   |
| 0x406c4    | 4         | 1.85%   |
| 0x406c3    | 4         | 1.85%   |
| 0x20655    | 4         | 1.85%   |
| 0x20652    | 4         | 1.85%   |
| 0x0a50000c | 4         | 1.85%   |
| 0xa0652    | 3         | 1.39%   |
| 0x906c0    | 3         | 1.39%   |
| 0x706a8    | 3         | 1.39%   |
| 0x08600104 | 3         | 1.39%   |
| 0x0810100b | 3         | 1.39%   |
| 0x906e9    | 2         | 0.93%   |
| 0x6fd      | 2         | 0.93%   |
| 0x30678    | 2         | 0.93%   |
| 0x106ca    | 2         | 0.93%   |
| 0x08608103 | 2         | 0.93%   |
| 0x08600106 | 2         | 0.93%   |
| 0x08108109 | 2         | 0.93%   |
| 0x08101007 | 2         | 0.93%   |
| 0x06006704 | 2         | 0.93%   |
| 0xa0660    | 1         | 0.46%   |
| 0x90672    | 1         | 0.46%   |
| 0x706e5    | 1         | 0.46%   |
| 0x506c9    | 1         | 0.46%   |
| 0x40661    | 1         | 0.46%   |
| 0x306d4    | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 40        | 19.23%  |
| Haswell          | 19        | 9.13%   |
| Skylake          | 14        | 6.73%   |
| IvyBridge        | 14        | 6.73%   |
| Zen+             | 12        | 5.77%   |
| Silvermont       | 11        | 5.29%   |
| TigerLake        | 10        | 4.81%   |
| SandyBridge      | 10        | 4.81%   |
| Westmere         | 8         | 3.85%   |
| Penryn           | 8         | 3.85%   |
| Zen 3            | 7         | 3.37%   |
| Zen 2            | 7         | 3.37%   |
| Goldmont plus    | 7         | 3.37%   |
| CometLake        | 7         | 3.37%   |
| Unknown          | 7         | 3.37%   |
| Zen              | 5         | 2.4%    |
| Tremont          | 3         | 1.44%   |
| IceLake          | 3         | 1.44%   |
| Excavator        | 3         | 1.44%   |
| Bonnell          | 3         | 1.44%   |
| Puma             | 2         | 0.96%   |
| Core             | 2         | 0.96%   |
| K8 Hammer        | 1         | 0.48%   |
| Jaguar           | 1         | 0.48%   |
| Goldmont         | 1         | 0.48%   |
| Broadwell        | 1         | 0.48%   |
| Bobcat           | 1         | 0.48%   |
| Alderlake Hybrid | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 146       | 48.99%  |
| Nvidia           | 92        | 30.87%  |
| AMD              | 58        | 19.46%  |
| VIA Technologies | 1         | 0.34%   |
| ATI Technologies | 1         | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 4.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 3.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 3.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 3.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 3.24%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.91%   |
| Intel HD Graphics 620                                                                    | 9         | 2.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 2.91%   |
| Intel HD Graphics 530                                                                    | 8         | 2.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 2.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 2.27%   |
| AMD Renoir                                                                               | 7         | 2.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 2.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.94%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 1.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.62%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.62%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.29%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.29%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 1.29%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 4         | 1.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.29%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.97%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.97%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.97%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.97%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.97%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.97%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.97%   |
| AMD Lucienne                                                                             | 3         | 0.97%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 3         | 0.97%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.65%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel + Nvidia     | 68        | 32.69%  |
| 1 x Intel          | 66        | 31.73%  |
| 1 x AMD            | 32        | 15.38%  |
| 1 x Nvidia         | 12        | 5.77%   |
| Intel + AMD        | 10        | 4.81%   |
| AMD + Nvidia       | 10        | 4.81%   |
| 2 x AMD            | 7         | 3.37%   |
| Intel + 2 x Nvidia | 2         | 0.96%   |
| 1 x VIA            | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 164       | 77.36%  |
| Proprietary | 45        | 21.23%  |
| Unknown     | 3         | 1.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 114       | 53.52%  |
| 1.01-2.0   | 32        | 15.02%  |
| 3.01-4.0   | 26        | 12.21%  |
| 0.01-0.5   | 25        | 11.74%  |
| 0.51-1.0   | 11        | 5.16%   |
| 5.01-6.0   | 3         | 1.41%   |
| 7.01-8.0   | 1         | 0.47%   |
| 8.01-16.0  | 1         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 52        | 21.67%  |
| Chimei Innolux          | 39        | 16.25%  |
| LG Display              | 31        | 12.92%  |
| BOE                     | 31        | 12.92%  |
| Samsung Electronics     | 25        | 10.42%  |
| PANDA                   | 9         | 3.75%   |
| Dell                    | 9         | 3.75%   |
| Goldstar                | 7         | 2.92%   |
| Sharp                   | 5         | 2.08%   |
| Apple                   | 5         | 2.08%   |
| Lenovo                  | 3         | 1.25%   |
| Chi Mei Optoelectronics | 3         | 1.25%   |
| Hewlett-Packard         | 2         | 0.83%   |
| Acer                    | 2         | 0.83%   |
| ViewSonic               | 1         | 0.42%   |
| TCL                     | 1         | 0.42%   |
| SKY                     | 1         | 0.42%   |
| Quanta Display          | 1         | 0.42%   |
| Panasonic               | 1         | 0.42%   |
| NEC Computers           | 1         | 0.42%   |
| Mi                      | 1         | 0.42%   |
| LPL                     | 1         | 0.42%   |
| Lenovo Group Limited    | 1         | 0.42%   |
| InfoVision              | 1         | 0.42%   |
| HJC                     | 1         | 0.42%   |
| Hitachi                 | 1         | 0.42%   |
| CSO                     | 1         | 0.42%   |
| CPT                     | 1         | 0.42%   |
| BenQ                    | 1         | 0.42%   |
| ASUSTek Computer        | 1         | 0.42%   |
| AOC                     | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 4         | 1.66%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 1.24%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 1.24%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 3         | 1.24%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 0.83%   |
| LG Display LCD Monitor LGD0454 1366x768 310x174mm 14.0-inch           | 2         | 0.83%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 2         | 0.83%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 2         | 0.83%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 2         | 0.83%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.83%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                  | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO363C 1366x768 309x173mm 13.9-inch         | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO353D 1920x1080 309x173mm 13.9-inch        | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 0.83%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 2         | 0.83%   |
| ViewSonic VSC PJD VSCD934 1920x1080                                   | 1         | 0.41%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 1         | 0.41%   |
| SKY TV-monitor SKY1202 1920x1080 885x498mm 40.0-inch                  | 1         | 0.41%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 0.41%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP14A1 3840x2160 344x194mm 15.5-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM0366 1280x1024 338x270mm 17.0-inch  | 1         | 0.41%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 1         | 0.41%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.41%   |
| Samsung Electronics S20D300 SAM0B3A 1600x900 432x240mm 19.5-inch      | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 100       | 44.05%  |
| 1366x768 (WXGA)   | 79        | 34.8%   |
| 3840x2160 (4K)    | 10        | 4.41%   |
| 2560x1440 (QHD)   | 8         | 3.52%   |
| 1600x900 (HD+)    | 7         | 3.08%   |
| 1440x900 (WXGA+)  | 5         | 2.2%    |
| 1280x800 (WXGA)   | 3         | 1.32%   |
| 1280x1024 (SXGA)  | 3         | 1.32%   |
| 2560x1600         | 2         | 0.88%   |
| 1920x1200 (WUXGA) | 2         | 0.88%   |
| 3840x2400         | 1         | 0.44%   |
| 2880x1800         | 1         | 0.44%   |
| 2256x1504         | 1         | 0.44%   |
| 2160x1440         | 1         | 0.44%   |
| 1920x515          | 1         | 0.44%   |
| 1360x768          | 1         | 0.44%   |
| 1024x768 (XGA)    | 1         | 0.44%   |
| 1024x600          | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 82        | 34.31%  |
| 14      | 43        | 17.99%  |
| 13      | 40        | 16.74%  |
| 17      | 14        | 5.86%   |
| 11      | 12        | 5.02%   |
| 24      | 6         | 2.51%   |
| 27      | 5         | 2.09%   |
| 23      | 5         | 2.09%   |
| 21      | 5         | 2.09%   |
| 12      | 4         | 1.67%   |
| Unknown | 4         | 1.67%   |
| 31      | 3         | 1.26%   |
| 19      | 3         | 1.26%   |
| 18      | 3         | 1.26%   |
| 16      | 3         | 1.26%   |
| 84      | 2         | 0.84%   |
| 54      | 1         | 0.42%   |
| 46      | 1         | 0.42%   |
| 40      | 1         | 0.42%   |
| 20      | 1         | 0.42%   |
| 8       | 1         | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 150       | 63.29%  |
| 201-300     | 33        | 13.92%  |
| 501-600     | 16        | 6.75%   |
| 351-400     | 14        | 5.91%   |
| 401-500     | 11        | 4.64%   |
| Unknown     | 4         | 1.69%   |
| 601-700     | 3         | 1.27%   |
| 1501-2000   | 2         | 0.84%   |
| 1001-1500   | 2         | 0.84%   |
| 801-900     | 1         | 0.42%   |
| 101-200     | 1         | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 181       | 87.86%  |
| 16/10   | 15        | 7.28%   |
| 5/4     | 3         | 1.46%   |
| 3/2     | 3         | 1.46%   |
| Unknown | 2         | 0.97%   |
| 4/3     | 1         | 0.49%   |
| 3.73    | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 82        | 34.31%  |
| 81-90          | 70        | 29.29%  |
| 201-250        | 14        | 5.86%   |
| 71-80          | 13        | 5.44%   |
| 51-60          | 12        | 5.02%   |
| 121-130        | 11        | 4.6%    |
| 301-350        | 5         | 2.09%   |
| 151-200        | 5         | 2.09%   |
| 141-150        | 5         | 2.09%   |
| 61-70          | 4         | 1.67%   |
| Unknown        | 4         | 1.67%   |
| More than 1000 | 3         | 1.26%   |
| 351-500        | 3         | 1.26%   |
| 111-120        | 2         | 0.84%   |
| 501-1000       | 2         | 0.84%   |
| 1-40           | 1         | 0.42%   |
| 251-300        | 1         | 0.42%   |
| 131-140        | 1         | 0.42%   |
| 91-100         | 1         | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 103       | 43.28%  |
| 101-120       | 73        | 30.67%  |
| 51-100        | 31        | 13.03%  |
| 161-240       | 21        | 8.82%   |
| More than 240 | 4         | 1.68%   |
| Unknown       | 4         | 1.68%   |
| 1-50          | 2         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 170       | 79.81%  |
| 2     | 37        | 17.37%  |
| 3     | 3         | 1.41%   |
| 0     | 3         | 1.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 119       | 34.9%   |
| Intel                             | 102       | 29.91%  |
| Qualcomm Atheros                  | 55        | 16.13%  |
| Broadcom                          | 27        | 7.92%   |
| ASIX Electronics                  | 8         | 2.35%   |
| MediaTek                          | 7         | 2.05%   |
| Broadcom Limited                  | 3         | 0.88%   |
| Ralink Technology                 | 2         | 0.59%   |
| Ralink                            | 2         | 0.59%   |
| Ericsson Business Mobile Networks | 2         | 0.59%   |
| Xiaomi                            | 1         | 0.29%   |
| vivo                              | 1         | 0.29%   |
| VIA Technologies                  | 1         | 0.29%   |
| TP-Link                           | 1         | 0.29%   |
| Samsung Electronics               | 1         | 0.29%   |
| Qualcomm                          | 1         | 0.29%   |
| Nvidia                            | 1         | 0.29%   |
| Marvell Technology Group          | 1         | 0.29%   |
| Lenovo                            | 1         | 0.29%   |
| JMicron Technology                | 1         | 0.29%   |
| Huawei Technologies               | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |
| D-Link                            | 1         | 0.29%   |
| ASUSTek Computer                  | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 90        | 23.38%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 3.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 3.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 2.86%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.34%   |
| Intel Wireless 7265                                               | 7         | 1.82%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.56%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.56%   |
| Intel Wireless 3160                                               | 6         | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.3%    |
| Intel Wireless-AC 9260                                            | 5         | 1.3%    |
| Intel Wireless 8260                                               | 5         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.04%   |
| Intel Wireless 3165                                               | 4         | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 3         | 0.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.52%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 2         | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 100       | 46.3%   |
| Qualcomm Atheros      | 47        | 21.76%  |
| Realtek Semiconductor | 29        | 13.43%  |
| Broadcom              | 21        | 9.72%   |
| MediaTek              | 7         | 3.24%   |
| Broadcom Limited      | 3         | 1.39%   |
| Ralink Technology     | 2         | 0.93%   |
| Ralink                | 2         | 0.93%   |
| TP-Link               | 1         | 0.46%   |
| Qualcomm              | 1         | 0.46%   |
| D-Link System         | 1         | 0.46%   |
| D-Link                | 1         | 0.46%   |
| ASUSTek Computer      | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 15        | 6.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 5.56%   |
| Intel Wi-Fi 6 AX200                                            | 11        | 5.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 4.17%   |
| Intel Wireless 7265                                            | 7         | 3.24%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 3.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 3.24%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 3.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 2.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.78%   |
| Intel Wireless 8265 / 8275                                     | 6         | 2.78%   |
| Intel Wireless 3160                                            | 6         | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 2.31%   |
| Intel Wireless-AC 9260                                         | 5         | 2.31%   |
| Intel Wireless 8260                                            | 5         | 2.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.31%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 2.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2.31%   |
| Intel Wireless 3165                                            | 4         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 1.39%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 1.39%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.93%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 0.93%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 0.93%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 0.93%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 105       | 64.42%  |
| Intel                    | 20        | 12.27%  |
| Qualcomm Atheros         | 12        | 7.36%   |
| Broadcom                 | 10        | 6.13%   |
| ASIX Electronics         | 8         | 4.91%   |
| Xiaomi                   | 1         | 0.61%   |
| VIA Technologies         | 1         | 0.61%   |
| Samsung Electronics      | 1         | 0.61%   |
| Nvidia                   | 1         | 0.61%   |
| Marvell Technology Group | 1         | 0.61%   |
| Lenovo                   | 1         | 0.61%   |
| JMicron Technology       | 1         | 0.61%   |
| Huawei Technologies      | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 90        | 54.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11        | 6.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 3.61%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 6         | 3.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.2%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.2%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.2%    |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                              | 2         | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.6%    |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.6%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.6%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.6%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.6%    |
| Lenovo ThinkPad TBT 3 Dock                                                     | 1         | 0.6%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.6%    |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                            | 1         | 0.6%    |
| Intel Ethernet Controller I225-V                                               | 1         | 0.6%    |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.6%    |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.6%    |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.6%    |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.6%    |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.6%    |
| Huawei E353/E3131                                                              | 1         | 0.6%    |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                                    | 1         | 0.6%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 205       | 56.01%  |
| Ethernet | 158       | 43.17%  |
| Modem    | 2         | 0.55%   |
| Unknown  | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 184       | 82.88%  |
| Ethernet | 38        | 17.12%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 145       | 69.38%  |
| 1     | 64        | 30.62%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 165       | 77.83%  |
| Yes  | 47        | 22.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 44.51%  |
| IMC Networks                    | 19        | 10.98%  |
| Lite-On Technology              | 18        | 10.4%   |
| Realtek Semiconductor           | 11        | 6.36%   |
| Qualcomm Atheros Communications | 9         | 5.2%    |
| Broadcom                        | 8         | 4.62%   |
| Foxconn / Hon Hai               | 7         | 4.05%   |
| Apple                           | 5         | 2.89%   |
| Dell                            | 4         | 2.31%   |
| Foxconn International           | 3         | 1.73%   |
| Toshiba                         | 2         | 1.16%   |
| Realtek                         | 2         | 1.16%   |
| Hewlett-Packard                 | 2         | 1.16%   |
| USI                             | 1         | 0.58%   |
| Ralink                          | 1         | 0.58%   |
| MediaTek                        | 1         | 0.58%   |
| Cambridge Silicon Radio         | 1         | 0.58%   |
| ASUSTek Computer                | 1         | 0.58%   |
| Askey Computer                  | 1         | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 29        | 16.76%  |
| Intel AX201 Bluetooth                             | 16        | 9.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 13        | 7.51%   |
| Intel AX200 Bluetooth                             | 8         | 4.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 7         | 4.05%   |
| IMC Networks Bluetooth Radio                      | 7         | 4.05%   |
| IMC Networks Bluetooth Device                     | 7         | 4.05%   |
| Realtek Bluetooth Radio                           | 5         | 2.89%   |
| Foxconn / Hon Hai Bluetooth Device                | 5         | 2.89%   |
| Realtek  Bluetooth 4.2 Adapter                    | 4         | 2.31%   |
| Lite-On Bluetooth Device                          | 4         | 2.31%   |
| Qualcomm Atheros  Bluetooth Device                | 3         | 1.73%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 3         | 1.73%   |
| Intel Bluetooth Device                            | 3         | 1.73%   |
| Intel AX210 Bluetooth                             | 3         | 1.73%   |
| IMC Networks Wireless_Device                      | 3         | 1.73%   |
| Foxconn International BCM43142A0 Bluetooth module | 3         | 1.73%   |
| Apple Bluetooth Host Controller                   | 3         | 1.73%   |
| Realtek Bluetooth Radio                           | 2         | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 1.16%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 2         | 1.16%   |
| Lite-On Wireless_Device                           | 2         | 1.16%   |
| Lite-On Bluetooth Radio                           | 2         | 1.16%   |
| Intel Wireless-AC 3168 Bluetooth                  | 2         | 1.16%   |
| IMC Networks Bluetooth USB Host Controller        | 2         | 1.16%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 2         | 1.16%   |
| Dell BCM20702A0 Bluetooth Module                  | 2         | 1.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 1.16%   |
| Apple Bluetooth USB Host Controller               | 2         | 1.16%   |
| USI Bluetooth Device                              | 1         | 0.58%   |
| Toshiba Bluetooth USB Host Controller             | 1         | 0.58%   |
| Toshiba Askey Bluetooth Module                    | 1         | 0.58%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 1         | 0.58%   |
| Realtek RTL8723B Bluetooth                        | 1         | 0.58%   |
| Ralink RT3290 Bluetooth                           | 1         | 0.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 0.58%   |
| Qualcomm Atheros AR3012 Bluetooth                 | 1         | 0.58%   |
| MediaTek Wireless_Device                          | 1         | 0.58%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device      | 1         | 0.58%   |
| Lite-On Atheros Bluetooth                         | 1         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 156       | 59.09%  |
| AMD                                          | 50        | 18.94%  |
| Nvidia                                       | 44        | 16.67%  |
| JMTek                                        | 3         | 1.14%   |
| Samson Technologies                          | 2         | 0.76%   |
| Razer USA                                    | 2         | 0.76%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.38%   |
| VIA Technologies                             | 1         | 0.38%   |
| Samsung Electronics                          | 1         | 0.38%   |
| Lenovo                                       | 1         | 0.38%   |
| Huawei Technologies                          | 1         | 0.38%   |
| Dell                                         | 1         | 0.38%   |
| Cayin                                        | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 36        | 11.11%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 7.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 5.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 4.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15        | 4.63%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 3.7%    |
| Intel 8 Series HD Audio Controller                                                                | 12        | 3.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 3.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 3.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 2.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.85%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.85%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.23%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.93%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.93%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.93%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.93%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.93%   |
| Samson Technologies GoMic compact condenser mic                                                   | 2         | 0.62%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.62%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.62%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 29.85%  |
| SK hynix            | 26        | 19.4%   |
| Micron Technology   | 21        | 15.67%  |
| Kingston            | 18        | 13.43%  |
| Unknown             | 7         | 5.22%   |
| Crucial             | 5         | 3.73%   |
| Transcend           | 4         | 2.99%   |
| Elpida              | 3         | 2.24%   |
| A-DATA Technology   | 2         | 1.49%   |
| Unknown (ABCD)      | 1         | 0.75%   |
| Unknown (08B5)      | 1         | 0.75%   |
| Team                | 1         | 0.75%   |
| Ramaxel Technology  | 1         | 0.75%   |
| Nanya Technology    | 1         | 0.75%   |
| Lexar               | 1         | 0.75%   |
| G.Skill             | 1         | 0.75%   |
| ASint Technology    | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.16%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.16%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.16%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 1.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.44%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 1.44%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 2         | 1.44%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.44%   |
| Micron RAM Module 4096MB SODIMM DDR4 2400MT/s                    | 2         | 1.44%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 1.44%   |
| Crucial RAM CT16G4SFD824A.C16FBR 16GB SODIMM DDR4 2400MT/s       | 2         | 1.44%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1334MT/s                   | 1         | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.72%   |
| Unknown (08B5) RAM IM308GU16N16 8192MB SODIMM DDR3 1333MT/s      | 1         | 0.72%   |
| Transcend RAM JM3200HSG-8G 8GB SODIMM DDR4 3200MT/s              | 1         | 0.72%   |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s              | 1         | 0.72%   |
| Transcend RAM JM2666HSB-8G 8GB SODIMM DDR4 2667MT/s              | 1         | 0.72%   |
| Transcend RAM JM1600KSN-4G 4GB SODIMM DDR3 1600MT/s              | 1         | 0.72%   |
| Team RAM TEAMGROUP-SD4-2133 8GB SODIMM DDR4 2133MT/s             | 1         | 0.72%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.72%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3733MT/s             | 1         | 0.72%   |
| SK hynix RAM Module 4096MB Row Of Chips LPDDR4 3733MT/s          | 1         | 0.72%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.72%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.72%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.72%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.72%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 53        | 48.18%  |
| DDR3   | 37        | 33.64%  |
| LPDDR4 | 12        | 10.91%  |
| LPDDR3 | 3         | 2.73%   |
| DDR5   | 3         | 2.73%   |
| SDRAM  | 1         | 0.91%   |
| LPDDR5 | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 94        | 85.45%  |
| Row Of Chips | 16        | 14.55%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 46        | 40.71%  |
| 4096  | 39        | 34.51%  |
| 16384 | 16        | 14.16%  |
| 2048  | 11        | 9.73%   |
| 32768 | 1         | 0.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 30        | 25.21%  |
| 3200  | 21        | 17.65%  |
| 2667  | 19        | 15.97%  |
| 2400  | 11        | 9.24%   |
| 2133  | 6         | 5.04%   |
| 4267  | 5         | 4.2%    |
| 1334  | 5         | 4.2%    |
| 1333  | 5         | 4.2%    |
| 3266  | 4         | 3.36%   |
| 4800  | 3         | 2.52%   |
| 1067  | 3         | 2.52%   |
| 4266  | 2         | 1.68%   |
| 3733  | 2         | 1.68%   |
| 8400  | 1         | 0.84%   |
| 6400  | 1         | 0.84%   |
| 4199  | 1         | 0.84%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 50%     |
| Samsung Electronics | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Seiko Epson ME-100 Series | 1         | 50%     |
| Samsung SCX-4300 Series   | 1         | 50%     |

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
| Chicony Electronics                    | 51        | 26.98%  |
| IMC Networks                           | 29        | 15.34%  |
| Acer                                   | 21        | 11.11%  |
| Realtek Semiconductor                  | 18        | 9.52%   |
| Quanta                                 | 14        | 7.41%   |
| Microdia                               | 13        | 6.88%   |
| Sunplus Innovation Technology          | 5         | 2.65%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.65%   |
| Bison Electronics                      | 5         | 2.65%   |
| Suyin                                  | 3         | 1.59%   |
| Silicon Motion                         | 3         | 1.59%   |
| Logitech                               | 3         | 1.59%   |
| Lite-On Technology                     | 3         | 1.59%   |
| Apple                                  | 3         | 1.59%   |
| Samsung Electronics                    | 2         | 1.06%   |
| Z-Star Microelectronics                | 1         | 0.53%   |
| USB Camera                             | 1         | 0.53%   |
| Syntek                                 | 1         | 0.53%   |
| Sonix Technology                       | 1         | 0.53%   |
| Razer USA                              | 1         | 0.53%   |
| Microsoft                              | 1         | 0.53%   |
| Luxvisions Innotech Limited            | 1         | 0.53%   |
| Lenovo                                 | 1         | 0.53%   |
| Generalplus Technology                 | 1         | 0.53%   |
| Aveo Technology                        | 1         | 0.53%   |
| Alcor Micro                            | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 12        | 6.35%   |
| Chicony HD WebCam                                       | 11        | 5.82%   |
| Chicony Integrated Camera                               | 9         | 4.76%   |
| Microdia Integrated_Webcam_HD                           | 6         | 3.17%   |
| Acer Lenovo EasyCamera                                  | 6         | 3.17%   |
| Chicony HP TrueVision HD Camera                         | 5         | 2.65%   |
| Realtek Integrated_Webcam_HD                            | 4         | 2.12%   |
| Realtek HD WebCam                                       | 4         | 2.12%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 4         | 2.12%   |
| IMC Networks Integrated Camera                          | 4         | 2.12%   |
| Chicony Lenovo EasyCamera                               | 4         | 2.12%   |
| Acer SunplusIT Integrated Camera                        | 4         | 2.12%   |
| Silicon Motion WebCam SCB-0385N                         | 3         | 1.59%   |
| Chicony HD User Facing                                  | 3         | 1.59%   |
| Acer Lenovo Integrated Webcam                           | 3         | 1.59%   |
| Acer Integrated Camera                                  | 3         | 1.59%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.06%   |
| Samsung Galaxy A5 (MTP)                                 | 2         | 1.06%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.06%   |
| Realtek Integrated Webcam                               | 2         | 1.06%   |
| Quanta VGA WebCam                                       | 2         | 1.06%   |
| Quanta USB2.0 HD UVC WebCam                             | 2         | 1.06%   |
| Quanta ov9734_techfront_camera                          | 2         | 1.06%   |
| Quanta HD Webcam                                        | 2         | 1.06%   |
| Quanta HD User Facing                                   | 2         | 1.06%   |
| Microdia USB 2.0 Camera                                 | 2         | 1.06%   |
| Microdia Integrated Webcam                              | 2         | 1.06%   |
| IMC Networks VGA UVC WebCam                             | 2         | 1.06%   |
| IMC Networks HD Camera                                  | 2         | 1.06%   |
| Chicony VGA Webcam                                      | 2         | 1.06%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.06%   |
| Chicony TOSHIBA Web Camera - HD                         | 2         | 1.06%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.06%   |
| Bison ThinkPad Integrated Camera                        | 2         | 1.06%   |
| Bison Integrated Camera                                 | 2         | 1.06%   |
| Apple FaceTime Camera                                   | 2         | 1.06%   |
| Acer HD Webcam                                          | 2         | 1.06%   |
| Z-Star WebCam SCB-1900N                                 | 1         | 0.53%   |
| USB Camera USB Camera                                   | 1         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 10        | 27.78%  |
| Synaptics                  | 9         | 25%     |
| Elan Microelectronics      | 5         | 13.89%  |
| Validity Sensors           | 4         | 11.11%  |
| LighTuning Technology      | 4         | 11.11%  |
| Upek                       | 2         | 5.56%   |
| AuthenTec                  | 2         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                       | 6         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device                      | 4         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 3         | 8.33%   |
| Elan ELAN:Fingerprint                                    | 3         | 8.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 2         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 2         | 5.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 2         | 5.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 2         | 5.56%   |
| Elan ELAN:ARM-M4                                         | 2         | 5.56%   |
| Validity Sensors VFS101 Fingerprint Reader               | 1         | 2.78%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 2.78%   |
| Synaptics WBDI Fingerprint Reader USB 086                | 1         | 2.78%   |
| Synaptics WBDI                                           | 1         | 2.78%   |
| Synaptics UWP WBDI Device                                | 1         | 2.78%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 2.78%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 2.78%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.78%   |
| AuthenTec AES2810                                        | 1         | 2.78%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 2.78%   |

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
| 0     | 138       | 64.19%  |
| 1     | 62        | 28.84%  |
| 2     | 13        | 6.05%   |
| 3     | 2         | 0.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 34        | 36.96%  |
| Graphics card            | 21        | 22.83%  |
| Multimedia controller    | 10        | 10.87%  |
| Net/wireless             | 9         | 9.78%   |
| Chipcard                 | 8         | 8.7%    |
| Bluetooth                | 3         | 3.26%   |
| Camera                   | 2         | 2.17%   |
| Wireless                 | 1         | 1.09%   |
| Storage/ide              | 1         | 1.09%   |
| Flash memory             | 1         | 1.09%   |
| Communication controller | 1         | 1.09%   |
| Card reader              | 1         | 1.09%   |

