Linux in Venezuela - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Venezuela.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Venezuela/Desktop/README.md) and [notebooks](/Location/Venezuela/Notebook/README.md).

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

Total: 385

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [61b7eaac72](https://linux-hardware.org/?probe=61b7eaac72) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [de0a127527](https://linux-hardware.org/?probe=de0a127527) | Dec 16, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [515785c9c4](https://linux-hardware.org/?probe=515785c9c4) | Dec 16, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [68f683d29e](https://linux-hardware.org/?probe=68f683d29e) | Dec 06, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a656b96d5f](https://linux-hardware.org/?probe=a656b96d5f) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | Desktop     | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6275a6ee8f](https://linux-hardware.org/?probe=6275a6ee8f) | Dec 02, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e1a4335a71](https://linux-hardware.org/?probe=e1a4335a71) | Dec 01, 2022 |
| HP            | Mini 110-1100               | Notebook    | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| Lenovo        | 3000 N500 42336DS           | Notebook    | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| Intel         | powered classmate PC        | Tablet      | [44cc912fe3](https://linux-hardware.org/?probe=44cc912fe3) | Nov 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [906ad9a3c1](https://linux-hardware.org/?probe=906ad9a3c1) | Nov 25, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [b252a902f4](https://linux-hardware.org/?probe=b252a902f4) | Nov 24, 2022 |
| VIT           | M2400-01                    | Mini pc     | [4b590aa76a](https://linux-hardware.org/?probe=4b590aa76a) | Nov 22, 2022 |
| Intel         | powered classmate PC        | Notebook    | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [a195c7598f](https://linux-hardware.org/?probe=a195c7598f) | Nov 14, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2176ff6bc0](https://linux-hardware.org/?probe=2176ff6bc0) | Nov 14, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [3469b1e624](https://linux-hardware.org/?probe=3469b1e624) | Nov 07, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [d3ef4a43db](https://linux-hardware.org/?probe=d3ef4a43db) | Nov 06, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [36612b5e01](https://linux-hardware.org/?probe=36612b5e01) | Nov 02, 2022 |
| Intel         | H61                         | Desktop     | [326fa40958](https://linux-hardware.org/?probe=326fa40958) | Nov 01, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| Intel         | powered classmate PC        | Tablet      | [d047cd6e73](https://linux-hardware.org/?probe=d047cd6e73) | Oct 22, 2022 |
| Google        | Candy                       | Notebook    | [af2c0be6ca](https://linux-hardware.org/?probe=af2c0be6ca) | Oct 17, 2022 |
| Google        | Candy                       | Notebook    | [ec740507fd](https://linux-hardware.org/?probe=ec740507fd) | Oct 17, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| ECS           | A890GXM-A2                  | Desktop     | [d6f77b12c2](https://linux-hardware.org/?probe=d6f77b12c2) | Oct 09, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Unknown       | NB-7000                     | Notebook    | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| VIT           | P2402                       | Notebook    | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [13ad69a13e](https://linux-hardware.org/?probe=13ad69a13e) | Sep 23, 2022 |
| Toshiba       | ENCORE 2 WT8-B              | Notebook    | [b9cd7b49d3](https://linux-hardware.org/?probe=b9cd7b49d3) | Sep 23, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [21cfcdcbdd](https://linux-hardware.org/?probe=21cfcdcbdd) | Sep 23, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [858fd4f09e](https://linux-hardware.org/?probe=858fd4f09e) | Sep 20, 2022 |
| Gateway       | NV57H                       | Notebook    | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [7c89dc4342](https://linux-hardware.org/?probe=7c89dc4342) | Sep 19, 2022 |
| Clevo         | W54xEU                      | Notebook    | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [ac687f4dcd](https://linux-hardware.org/?probe=ac687f4dcd) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | Notebook    | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [51b15f6d34](https://linux-hardware.org/?probe=51b15f6d34) | Sep 06, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b3b173a476](https://linux-hardware.org/?probe=b3b173a476) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [688dcf88c9](https://linux-hardware.org/?probe=688dcf88c9) | Aug 30, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [4ccef99860](https://linux-hardware.org/?probe=4ccef99860) | Aug 30, 2022 |
| HP            | 0A60h                       | Desktop     | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [3c63953ca6](https://linux-hardware.org/?probe=3c63953ca6) | Aug 27, 2022 |
| HP            | 1497                        | Desktop     | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [4bd2fabdc7](https://linux-hardware.org/?probe=4bd2fabdc7) | Aug 26, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [659ccaca6e](https://linux-hardware.org/?probe=659ccaca6e) | Aug 22, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Intel         | S1200BTL E98681-352         | Server      | [1db51bcff9](https://linux-hardware.org/?probe=1db51bcff9) | Aug 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [63a6df97b9](https://linux-hardware.org/?probe=63a6df97b9) | Aug 09, 2022 |
| VIT           | P2402                       | Notebook    | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [fc4f66c2de](https://linux-hardware.org/?probe=fc4f66c2de) | Aug 02, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| Dell          | Latitude 5490               | Notebook    | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | Notebook    | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| VIT           | P2402                       | Notebook    | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| HP            | 339A                        | Desktop     | [c19f3d1361](https://linux-hardware.org/?probe=c19f3d1361) | Jul 29, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [a0ebe8cf5a](https://linux-hardware.org/?probe=a0ebe8cf5a) | Jul 20, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | Desktop     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| Intel         | powered classmate PC        | Tablet      | [1abacce964](https://linux-hardware.org/?probe=1abacce964) | Jul 06, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2919feb689](https://linux-hardware.org/?probe=2919feb689) | Jul 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [dee20b535f](https://linux-hardware.org/?probe=dee20b535f) | Jul 04, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2933dddc75](https://linux-hardware.org/?probe=2933dddc75) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| MSI           | H81M-E33                    | Desktop     | [737e14fea7](https://linux-hardware.org/?probe=737e14fea7) | Jul 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [d7282a0f61](https://linux-hardware.org/?probe=d7282a0f61) | Jun 29, 2022 |
| Pegatron      | IPPSB-DB                    | Desktop     | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [c3e90d4ebd](https://linux-hardware.org/?probe=c3e90d4ebd) | Jun 26, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| ASRock        | H370M-HDV                   | Desktop     | [4d6a88cd74](https://linux-hardware.org/?probe=4d6a88cd74) | Jun 16, 2022 |
| Google        | Cyan                        | Notebook    | [7b82520717](https://linux-hardware.org/?probe=7b82520717) | Jun 13, 2022 |
| langchao      | IPM41-D3                    | Desktop     | [bb1a55c140](https://linux-hardware.org/?probe=bb1a55c140) | Jun 13, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [5d8aa17afc](https://linux-hardware.org/?probe=5d8aa17afc) | Jun 10, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [a502ed154f](https://linux-hardware.org/?probe=a502ed154f) | Jun 10, 2022 |
| VIT           | M2420                       | Notebook    | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | Notebook    | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
| VIT           | M2420                       | Notebook    | [c2ea650175](https://linux-hardware.org/?probe=c2ea650175) | Jun 01, 2022 |
| Dell          | Precision 7710              | Notebook    | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Lenovo        | 11051CS ThinkServer TS13... | Desktop     | [48e6a5501d](https://linux-hardware.org/?probe=48e6a5501d) | May 26, 2022 |
| Acer          | TravelMate 5742Z            | Notebook    | [fd6407ece1](https://linux-hardware.org/?probe=fd6407ece1) | May 26, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [13918cd2b7](https://linux-hardware.org/?probe=13918cd2b7) | May 23, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [0e7bf88677](https://linux-hardware.org/?probe=0e7bf88677) | May 19, 2022 |
| IP3 Tech      | TB20                        | Desktop     | [1cf2be0840](https://linux-hardware.org/?probe=1cf2be0840) | May 16, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [8dc1b9cd87](https://linux-hardware.org/?probe=8dc1b9cd87) | May 14, 2022 |
| Intel         | H61                         | Desktop     | [28277b5d5a](https://linux-hardware.org/?probe=28277b5d5a) | May 10, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [00620504c7](https://linux-hardware.org/?probe=00620504c7) | Apr 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ff32f84c4e](https://linux-hardware.org/?probe=ff32f84c4e) | Apr 23, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [8869defd9c](https://linux-hardware.org/?probe=8869defd9c) | Apr 22, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [8510a8836c](https://linux-hardware.org/?probe=8510a8836c) | Apr 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [6c3ed980a1](https://linux-hardware.org/?probe=6c3ed980a1) | Apr 18, 2022 |
| Clevo         | W54xEU                      | Notebook    | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| HP            | Pavilion dv5                | Notebook    | [22aa828b2f](https://linux-hardware.org/?probe=22aa828b2f) | Apr 16, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Clevo         | W54xEU                      | Notebook    | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3f66b1cb5c](https://linux-hardware.org/?probe=3f66b1cb5c) | Apr 13, 2022 |
| Dell          | Latitude 5590               | Notebook    | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [659999d04a](https://linux-hardware.org/?probe=659999d04a) | Apr 11, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [227c3936b8](https://linux-hardware.org/?probe=227c3936b8) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [6cb82accd9](https://linux-hardware.org/?probe=6cb82accd9) | Apr 07, 2022 |
| ASRock        | G31M-S                      | Desktop     | [33737ec5ba](https://linux-hardware.org/?probe=33737ec5ba) | Apr 01, 2022 |
| Gateway       | NV57H                       | Notebook    | [ce2e78a407](https://linux-hardware.org/?probe=ce2e78a407) | Mar 31, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| Intel         | D945GCCR AAD78647-300       | Desktop     | [c3d1b55376](https://linux-hardware.org/?probe=c3d1b55376) | Mar 27, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [552956f271](https://linux-hardware.org/?probe=552956f271) | Mar 24, 2022 |
| VIT           | P2402                       | Notebook    | [5d9e3733ea](https://linux-hardware.org/?probe=5d9e3733ea) | Mar 21, 2022 |
| ASRock        | H370M-HDV                   | Desktop     | [9945efc3fa](https://linux-hardware.org/?probe=9945efc3fa) | Mar 20, 2022 |
| Inspur        | Computer All in one PC V... | Desktop     | [5c419895c5](https://linux-hardware.org/?probe=5c419895c5) | Mar 18, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [3dcc73772f](https://linux-hardware.org/?probe=3dcc73772f) | Mar 12, 2022 |
| MSI           | 3664h                       | Desktop     | [e5eaec6553](https://linux-hardware.org/?probe=e5eaec6553) | Mar 08, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [5fa0d18666](https://linux-hardware.org/?probe=5fa0d18666) | Mar 04, 2022 |
| VIT           | NP3020M3                    | Server      | [9fbb87a829](https://linux-hardware.org/?probe=9fbb87a829) | Mar 03, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [0e8fbc26f1](https://linux-hardware.org/?probe=0e8fbc26f1) | Mar 01, 2022 |
| Pegatron      | 2ACC                        | Desktop     | [c1127626c5](https://linux-hardware.org/?probe=c1127626c5) | Mar 01, 2022 |
| VIT           | P3400                       | Notebook    | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Intel         | powered classmate PC        | Tablet      | [a2b7a04dfa](https://linux-hardware.org/?probe=a2b7a04dfa) | Feb 18, 2022 |
| VIT           | P3400                       | Notebook    | [b90c32748d](https://linux-hardware.org/?probe=b90c32748d) | Feb 18, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [89cecb62bc](https://linux-hardware.org/?probe=89cecb62bc) | Feb 17, 2022 |
| Lenovo        | ThinkPad X201 3680AE2       | Notebook    | [cb777c91bc](https://linux-hardware.org/?probe=cb777c91bc) | Feb 13, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [16dbcf63f1](https://linux-hardware.org/?probe=16dbcf63f1) | Feb 12, 2022 |
| ECS           | KAM1-I                      | Desktop     | [be38f855ff](https://linux-hardware.org/?probe=be38f855ff) | Feb 10, 2022 |
| Gateway       | NV57H                       | Notebook    | [9d59228f90](https://linux-hardware.org/?probe=9d59228f90) | Feb 09, 2022 |
| ASRock        | A55M-HVS                    | Desktop     | [c4c68e7dd1](https://linux-hardware.org/?probe=c4c68e7dd1) | Feb 08, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [ac9ed3224d](https://linux-hardware.org/?probe=ac9ed3224d) | Feb 01, 2022 |
| ASUSTek       | P6X58-E PRO                 | Desktop     | [9ee8e1ecdf](https://linux-hardware.org/?probe=9ee8e1ecdf) | Jan 30, 2022 |
| Intel         | DG41TY AAE47335-203         | Desktop     | [01ec1ff569](https://linux-hardware.org/?probe=01ec1ff569) | Jan 26, 2022 |
| MSI           | MS-1454                     | Notebook    | [1cb9a056e7](https://linux-hardware.org/?probe=1cb9a056e7) | Jan 14, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8700fd1193](https://linux-hardware.org/?probe=8700fd1193) | Jan 11, 2022 |
| VIT           | M2421                       | Notebook    | [c6cc8a474d](https://linux-hardware.org/?probe=c6cc8a474d) | Jan 10, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b6cffe86a0](https://linux-hardware.org/?probe=b6cffe86a0) | Dec 23, 2021 |
| UNIQCELL      | Q15.6                       | Notebook    | [d21e7048e1](https://linux-hardware.org/?probe=d21e7048e1) | Dec 20, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| Intel         | powered classmate PC        | Notebook    | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | Notebook    | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [8d19cd079a](https://linux-hardware.org/?probe=8d19cd079a) | Dec 09, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [ecd0add9b3](https://linux-hardware.org/?probe=ecd0add9b3) | Dec 09, 2021 |
| HP            | 3398                        | Desktop     | [5ae73e1468](https://linux-hardware.org/?probe=5ae73e1468) | Dec 07, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Lenovo        | B40-70 20392                | Notebook    | [4f4458d61a](https://linux-hardware.org/?probe=4f4458d61a) | Nov 23, 2021 |
| Intel         | powered classmate PC        | Tablet      | [aea7e0243a](https://linux-hardware.org/?probe=aea7e0243a) | Nov 21, 2021 |
| Intel         | powered classmate PC        | Tablet      | [444812feb3](https://linux-hardware.org/?probe=444812feb3) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [2f83ccbc4f](https://linux-hardware.org/?probe=2f83ccbc4f) | Nov 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a492e3e1ff](https://linux-hardware.org/?probe=a492e3e1ff) | Nov 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b37e3324e3](https://linux-hardware.org/?probe=b37e3324e3) | Nov 05, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| VIT           | P3400                       | Notebook    | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [d1d57448c4](https://linux-hardware.org/?probe=d1d57448c4) | Oct 29, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [f5112dbf47](https://linux-hardware.org/?probe=f5112dbf47) | Oct 29, 2021 |
| Dell          | Latitude E7450              | Notebook    | [9cbd7f01e8](https://linux-hardware.org/?probe=9cbd7f01e8) | Oct 18, 2021 |
| Dell          | Latitude E6420              | Notebook    | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| Biostar       | P4M90-M7A Ver:1.0           | Desktop     | [d8875918ac](https://linux-hardware.org/?probe=d8875918ac) | Oct 16, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [e5391d41e0](https://linux-hardware.org/?probe=e5391d41e0) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [3f6e406107](https://linux-hardware.org/?probe=3f6e406107) | Oct 14, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [903dc4ef05](https://linux-hardware.org/?probe=903dc4ef05) | Oct 13, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [1ec421714e](https://linux-hardware.org/?probe=1ec421714e) | Oct 02, 2021 |
| HP            | 1495                        | Desktop     | [64cbb112e2](https://linux-hardware.org/?probe=64cbb112e2) | Oct 01, 2021 |
| Clevo         | W54xEU                      | Notebook    | [a6732ab721](https://linux-hardware.org/?probe=a6732ab721) | Sep 30, 2021 |
| VIT           | P3400                       | Notebook    | [22260810d1](https://linux-hardware.org/?probe=22260810d1) | Sep 27, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [4571e36b80](https://linux-hardware.org/?probe=4571e36b80) | Sep 26, 2021 |
| ASUSTek       | TUF Gaming FA506IH_FA506... | Notebook    | [5854fbcaed](https://linux-hardware.org/?probe=5854fbcaed) | Sep 17, 2021 |
| Foxconn       | M61PMV FAB                  | Desktop     | [290d3e0fd5](https://linux-hardware.org/?probe=290d3e0fd5) | Sep 14, 2021 |
| Pegatron      | T14AF                       | Notebook    | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [202fe67100](https://linux-hardware.org/?probe=202fe67100) | Aug 27, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [321f53f711](https://linux-hardware.org/?probe=321f53f711) | Aug 27, 2021 |
| Lenovo        | ThinkPad Edge 01962AS       | Notebook    | [8ccb24d0d8](https://linux-hardware.org/?probe=8ccb24d0d8) | Aug 24, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [ec9367ff70](https://linux-hardware.org/?probe=ec9367ff70) | Aug 16, 2021 |
| VIT           | P2400                       | Notebook    | [f844ffff09](https://linux-hardware.org/?probe=f844ffff09) | Aug 11, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Foxconn       | ELA01                       | Desktop     | [13bcd06d5f](https://linux-hardware.org/?probe=13bcd06d5f) | Jul 23, 2021 |
| Foxconn       | ELA01                       | Desktop     | [a73982649a](https://linux-hardware.org/?probe=a73982649a) | Jul 22, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c726cd767b](https://linux-hardware.org/?probe=c726cd767b) | Jul 19, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [ab44db5647](https://linux-hardware.org/?probe=ab44db5647) | Jul 18, 2021 |
| Lenovo        | ThinkCentre M71e 3157G6S    | Desktop     | [89217c2643](https://linux-hardware.org/?probe=89217c2643) | Jul 14, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [60c62c33f8](https://linux-hardware.org/?probe=60c62c33f8) | Jul 14, 2021 |
| Biostar       | G41D3                       | Desktop     | [673d4faa98](https://linux-hardware.org/?probe=673d4faa98) | Jul 12, 2021 |
| HP            | 3397                        | Desktop     | [f1a6d10d78](https://linux-hardware.org/?probe=f1a6d10d78) | Jul 08, 2021 |
| HP            | 3397                        | Desktop     | [e087e03e0b](https://linux-hardware.org/?probe=e087e03e0b) | Jul 08, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [a57f28921c](https://linux-hardware.org/?probe=a57f28921c) | Jul 05, 2021 |
| ECS           | Livermore                   | Desktop     | [b471a4666c](https://linux-hardware.org/?probe=b471a4666c) | Jun 30, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [c468ca84d3](https://linux-hardware.org/?probe=c468ca84d3) | Jun 30, 2021 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [a82bafec08](https://linux-hardware.org/?probe=a82bafec08) | Jun 29, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [fc58981ecd](https://linux-hardware.org/?probe=fc58981ecd) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [bce9c74edb](https://linux-hardware.org/?probe=bce9c74edb) | Jun 27, 2021 |
| ECS           | Livermore                   | Desktop     | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [cb1c07fa68](https://linux-hardware.org/?probe=cb1c07fa68) | Jun 17, 2021 |
| VIT           | P2400                       | Notebook    | [295d4d5a47](https://linux-hardware.org/?probe=295d4d5a47) | Jun 17, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [512537c402](https://linux-hardware.org/?probe=512537c402) | Jun 17, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [9773736b0f](https://linux-hardware.org/?probe=9773736b0f) | Jun 17, 2021 |
| ECS           | G31T-M7                     | Desktop     | [01ed8410e9](https://linux-hardware.org/?probe=01ed8410e9) | Jun 15, 2021 |
| Lenovo        | ThinkCentre M55E 9645BN2    | Desktop     | [ef91279611](https://linux-hardware.org/?probe=ef91279611) | Jun 15, 2021 |
| VIT           | P1400                       | Notebook    | [129d543695](https://linux-hardware.org/?probe=129d543695) | Jun 13, 2021 |
| Biostar       | G41D3C                      | Desktop     | [263491c02a](https://linux-hardware.org/?probe=263491c02a) | Jun 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [423b514d2b](https://linux-hardware.org/?probe=423b514d2b) | May 30, 2021 |
| VIT           | P2400                       | Notebook    | [f39537fca1](https://linux-hardware.org/?probe=f39537fca1) | May 28, 2021 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [0f12ef1983](https://linux-hardware.org/?probe=0f12ef1983) | May 25, 2021 |
| VIT           | P2400                       | Notebook    | [4fa6d109de](https://linux-hardware.org/?probe=4fa6d109de) | May 25, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [42960896cb](https://linux-hardware.org/?probe=42960896cb) | May 20, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [4856303cbe](https://linux-hardware.org/?probe=4856303cbe) | May 20, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [1a9761824e](https://linux-hardware.org/?probe=1a9761824e) | May 20, 2021 |
| Intel         | powered classmate PC        | Notebook    | [a3b0d4e33e](https://linux-hardware.org/?probe=a3b0d4e33e) | May 12, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [9e701873b1](https://linux-hardware.org/?probe=9e701873b1) | May 09, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [59a6774cd5](https://linux-hardware.org/?probe=59a6774cd5) | May 09, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [f16304ca03](https://linux-hardware.org/?probe=f16304ca03) | May 04, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [8eca6b6f79](https://linux-hardware.org/?probe=8eca6b6f79) | May 04, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [bef0f33897](https://linux-hardware.org/?probe=bef0f33897) | May 02, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [8d84f6dc9e](https://linux-hardware.org/?probe=8d84f6dc9e) | Apr 25, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [db04624ac3](https://linux-hardware.org/?probe=db04624ac3) | Apr 20, 2021 |
| Acer          | Aspire 4935                 | Notebook    | [cbe6a288f1](https://linux-hardware.org/?probe=cbe6a288f1) | Apr 06, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [330f034c61](https://linux-hardware.org/?probe=330f034c61) | Apr 04, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [4cf71fac35](https://linux-hardware.org/?probe=4cf71fac35) | Apr 04, 2021 |
| Toshiba       | Satellite E55t-A            | Notebook    | [e1a3602d7b](https://linux-hardware.org/?probe=e1a3602d7b) | Mar 28, 2021 |
| Dell          | Vostro 1500                 | Notebook    | [76ade477e8](https://linux-hardware.org/?probe=76ade477e8) | Mar 28, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [28996604f4](https://linux-hardware.org/?probe=28996604f4) | Mar 27, 2021 |
| ASUSTek       | X555DA                      | Notebook    | [e90c94fd9d](https://linux-hardware.org/?probe=e90c94fd9d) | Mar 27, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [7f2618efb7](https://linux-hardware.org/?probe=7f2618efb7) | Mar 12, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [918f841c61](https://linux-hardware.org/?probe=918f841c61) | Mar 12, 2021 |
| HP            | 1495                        | Desktop     | [248af9611e](https://linux-hardware.org/?probe=248af9611e) | Mar 11, 2021 |
| Dell          | 0GX297                      | Desktop     | [6ac3da669a](https://linux-hardware.org/?probe=6ac3da669a) | Mar 09, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [543e8d3501](https://linux-hardware.org/?probe=543e8d3501) | Mar 07, 2021 |
| langchao      | IPM41-D3                    | Desktop     | [892f3e6658](https://linux-hardware.org/?probe=892f3e6658) | Mar 07, 2021 |
| HP            | 2000                        | Notebook    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| Intel         | S5500BC E25124-407          | Server      | [fe3d758c20](https://linux-hardware.org/?probe=fe3d758c20) | Mar 06, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [e7550259a4](https://linux-hardware.org/?probe=e7550259a4) | Mar 06, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [294b1c19fb](https://linux-hardware.org/?probe=294b1c19fb) | Feb 20, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [9e6a12d9e1](https://linux-hardware.org/?probe=9e6a12d9e1) | Feb 15, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [4883c81a02](https://linux-hardware.org/?probe=4883c81a02) | Feb 07, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [63ab85aac6](https://linux-hardware.org/?probe=63ab85aac6) | Feb 05, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [570fb5f20b](https://linux-hardware.org/?probe=570fb5f20b) | Jan 27, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b481e5f8d2](https://linux-hardware.org/?probe=b481e5f8d2) | Jan 27, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e4d1cc65bc](https://linux-hardware.org/?probe=e4d1cc65bc) | Jan 27, 2021 |
| HP            | 1493                        | Desktop     | [febb5aee31](https://linux-hardware.org/?probe=febb5aee31) | Jan 15, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| Dell          | Inspiron 3180               | Notebook    | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| Pegatron      | IPM41-D3                    | Desktop     | [4e0489bdb0](https://linux-hardware.org/?probe=4e0489bdb0) | Dec 05, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [5751926628](https://linux-hardware.org/?probe=5751926628) | Nov 23, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [812b2188d4](https://linux-hardware.org/?probe=812b2188d4) | Nov 23, 2020 |
| Biostar       | A55MLC2                     | Desktop     | [e195f622e4](https://linux-hardware.org/?probe=e195f622e4) | Nov 22, 2020 |
| Biostar       | A55MLC2                     | Desktop     | [a0456b9ad3](https://linux-hardware.org/?probe=a0456b9ad3) | Nov 22, 2020 |
| HP            | 1495                        | Desktop     | [72bdee2784](https://linux-hardware.org/?probe=72bdee2784) | Nov 19, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | Notebook    | [1d1e7e6236](https://linux-hardware.org/?probe=1d1e7e6236) | Nov 07, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [31fa456854](https://linux-hardware.org/?probe=31fa456854) | Nov 07, 2020 |
| Exo           | AIO A210                    | Notebook    | [2082cc5386](https://linux-hardware.org/?probe=2082cc5386) | Nov 02, 2020 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [c172177266](https://linux-hardware.org/?probe=c172177266) | Oct 31, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [8de08ff7ac](https://linux-hardware.org/?probe=8de08ff7ac) | Oct 24, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [46849fa419](https://linux-hardware.org/?probe=46849fa419) | Oct 24, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [0fa1b76517](https://linux-hardware.org/?probe=0fa1b76517) | Oct 15, 2020 |
| Foxconn       | M61PMV FAB A1               | Desktop     | [cb7568786f](https://linux-hardware.org/?probe=cb7568786f) | Oct 05, 2020 |
| Lenovo        | G460 20041                  | Notebook    | [6944572eca](https://linux-hardware.org/?probe=6944572eca) | Oct 02, 2020 |
| Lenovo        | G460 20041                  | Notebook    | [1f4ffcafa7](https://linux-hardware.org/?probe=1f4ffcafa7) | Oct 02, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db328c3c01](https://linux-hardware.org/?probe=db328c3c01) | Sep 29, 2020 |
| ECS           | H61H2-CM                    | Desktop     | [8ae7ffac0b](https://linux-hardware.org/?probe=8ae7ffac0b) | Sep 28, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [0d9041893c](https://linux-hardware.org/?probe=0d9041893c) | Sep 15, 2020 |
| Unknown       | Unknown                     | Notebook    | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Intel         | powered classmate PC        | Tablet      | [4f4efbc5c6](https://linux-hardware.org/?probe=4f4efbc5c6) | Sep 06, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [5f5f0bd2cf](https://linux-hardware.org/?probe=5f5f0bd2cf) | Aug 29, 2020 |
| Biostar       | N68S3B                      | Desktop     | [1e4d89cafe](https://linux-hardware.org/?probe=1e4d89cafe) | Aug 27, 2020 |
| MSI           | FM2-A75MA-E35               | Desktop     | [7f40a96159](https://linux-hardware.org/?probe=7f40a96159) | Aug 20, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8445b18759](https://linux-hardware.org/?probe=8445b18759) | Aug 20, 2020 |
| HP            | Presario V2000 (EW997LA#... | Notebook    | [77a2a0c00f](https://linux-hardware.org/?probe=77a2a0c00f) | Aug 15, 2020 |
| Alienware     | 17 R4                       | Notebook    | [c1a871b29b](https://linux-hardware.org/?probe=c1a871b29b) | Aug 14, 2020 |
| ECS           | H61H2-CM                    | Desktop     | [43d0144f0a](https://linux-hardware.org/?probe=43d0144f0a) | Aug 06, 2020 |
| MSI           | K9N2 Diamond                | Desktop     | [07a001660f](https://linux-hardware.org/?probe=07a001660f) | Aug 04, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [56ad5a6a22](https://linux-hardware.org/?probe=56ad5a6a22) | Jul 29, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [f2fdb4f618](https://linux-hardware.org/?probe=f2fdb4f618) | Jul 27, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [a2e742ec36](https://linux-hardware.org/?probe=a2e742ec36) | Jul 27, 2020 |
| VIT           | M2421                       | Notebook    | [451969e0fc](https://linux-hardware.org/?probe=451969e0fc) | Jul 27, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [6786c103d7](https://linux-hardware.org/?probe=6786c103d7) | Jul 27, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [8081f20c91](https://linux-hardware.org/?probe=8081f20c91) | Jul 25, 2020 |
| Intel         | powered classmate PC        | Notebook    | [1ffa275c8b](https://linux-hardware.org/?probe=1ffa275c8b) | Jul 12, 2020 |
| Intel         | powered classmate PC        | Notebook    | [49442bdbca](https://linux-hardware.org/?probe=49442bdbca) | Jul 11, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [39510acc74](https://linux-hardware.org/?probe=39510acc74) | Jul 06, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [eff9ad2c7d](https://linux-hardware.org/?probe=eff9ad2c7d) | Jul 05, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [a1e610807e](https://linux-hardware.org/?probe=a1e610807e) | Jun 30, 2020 |
| HP            | Presario C700               | Notebook    | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [e8c521f7e8](https://linux-hardware.org/?probe=e8c521f7e8) | Jun 25, 2020 |
| Standard      | AHV                         | All in one  | [989175dbdc](https://linux-hardware.org/?probe=989175dbdc) | Jun 08, 2020 |
| Standard      | AHV                         | All in one  | [f0bd9ac2e1](https://linux-hardware.org/?probe=f0bd9ac2e1) | Jun 07, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [cd52689b0a](https://linux-hardware.org/?probe=cd52689b0a) | May 25, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [d48d360c14](https://linux-hardware.org/?probe=d48d360c14) | May 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [e8a608f296](https://linux-hardware.org/?probe=e8a608f296) | May 23, 2020 |
| Lenovo        | ThinkCentre A55 8705AV4     | Desktop     | [18c81b7e8b](https://linux-hardware.org/?probe=18c81b7e8b) | May 19, 2020 |
| Lenovo        | ThinkCentre A55 8705AV4     | Desktop     | [cce631f67b](https://linux-hardware.org/?probe=cce631f67b) | May 19, 2020 |
| VIT           | P3400                       | Notebook    | [48c981187d](https://linux-hardware.org/?probe=48c981187d) | May 18, 2020 |
| Intel         | DG41TX AAE78178-303         | Desktop     | [084641dbc1](https://linux-hardware.org/?probe=084641dbc1) | May 17, 2020 |
| VIT           | P3400                       | Notebook    | [f9be2de38c](https://linux-hardware.org/?probe=f9be2de38c) | May 14, 2020 |
| HP            | Pavilion dv4                | Notebook    | [2efd349a3f](https://linux-hardware.org/?probe=2efd349a3f) | May 13, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [b55d1daea5](https://linux-hardware.org/?probe=b55d1daea5) | May 11, 2020 |
| VIT           | P2402                       | Notebook    | [bacbeb66bd](https://linux-hardware.org/?probe=bacbeb66bd) | May 07, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [97e5a8c8da](https://linux-hardware.org/?probe=97e5a8c8da) | Apr 26, 2020 |
| VIT           | P3400                       | Notebook    | [cd75b7e2c3](https://linux-hardware.org/?probe=cd75b7e2c3) | Apr 24, 2020 |
| VIT           | P2400                       | Notebook    | [4acb382140](https://linux-hardware.org/?probe=4acb382140) | Apr 23, 2020 |
| VIT           | M2420                       | Notebook    | [a7535d12dc](https://linux-hardware.org/?probe=a7535d12dc) | Apr 13, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [b3436f0ec6](https://linux-hardware.org/?probe=b3436f0ec6) | Apr 11, 2020 |
| langchao      | IPM41-D3                    | Desktop     | [841ded939f](https://linux-hardware.org/?probe=841ded939f) | Mar 31, 2020 |
| Lenovo        | ThinkCentre A58 7515A33     | Desktop     | [75be0ab7ac](https://linux-hardware.org/?probe=75be0ab7ac) | Mar 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [ebbf8f7b4e](https://linux-hardware.org/?probe=ebbf8f7b4e) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [e39e92a6f9](https://linux-hardware.org/?probe=e39e92a6f9) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | Notebook    | [b9d2e7e174](https://linux-hardware.org/?probe=b9d2e7e174) | Mar 20, 2020 |
| VIT           | P2402                       | Notebook    | [9f90b82033](https://linux-hardware.org/?probe=9f90b82033) | Mar 10, 2020 |
| Pegatron      | 2A73h                       | Desktop     | [1d140aa76c](https://linux-hardware.org/?probe=1d140aa76c) | Mar 07, 2020 |
| Acer          | Aspire Z3730                | All in one  | [24d42a520e](https://linux-hardware.org/?probe=24d42a520e) | Mar 03, 2020 |
| VIT           | P2402                       | Notebook    | [ea6b959930](https://linux-hardware.org/?probe=ea6b959930) | Mar 03, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [2859756e56](https://linux-hardware.org/?probe=2859756e56) | Feb 29, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [79f0a68dd3](https://linux-hardware.org/?probe=79f0a68dd3) | Feb 26, 2020 |
| Lenovo        | ThinkCentre XXXX 8705A84    | Desktop     | [b824441963](https://linux-hardware.org/?probe=b824441963) | Feb 23, 2020 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [d1a4bff183](https://linux-hardware.org/?probe=d1a4bff183) | Feb 15, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [33fc6022df](https://linux-hardware.org/?probe=33fc6022df) | Feb 06, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [e79318e87d](https://linux-hardware.org/?probe=e79318e87d) | Feb 06, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [3e6bc93a39](https://linux-hardware.org/?probe=3e6bc93a39) | Jan 31, 2020 |
| Intel         | S5500BC E25124-407          | Server      | [b6ba4394f7](https://linux-hardware.org/?probe=b6ba4394f7) | Jan 29, 2020 |
| ASUSTek       | Leonite2                    | Desktop     | [d0d56d5609](https://linux-hardware.org/?probe=d0d56d5609) | Jan 23, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [17f334232d](https://linux-hardware.org/?probe=17f334232d) | Jan 01, 2020 |
| VIT           | Aptio CRB                   | Mini pc     | [d999c674f1](https://linux-hardware.org/?probe=d999c674f1) | Dec 23, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [41131b1d8e](https://linux-hardware.org/?probe=41131b1d8e) | Dec 23, 2019 |
| Intel         | powered classmate PC        | Notebook    | [b772cf9349](https://linux-hardware.org/?probe=b772cf9349) | Dec 11, 2019 |
| Intel         | powered classmate PC        | Notebook    | [b66f15db35](https://linux-hardware.org/?probe=b66f15db35) | Dec 11, 2019 |
| Lenovo        | ThinkCentre M55E 9632BU8    | Desktop     | [209a9171b1](https://linux-hardware.org/?probe=209a9171b1) | Dec 04, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [2d4b473d59](https://linux-hardware.org/?probe=2d4b473d59) | Dec 01, 2019 |
| Pegatron      | 2A73h                       | Desktop     | [2371d130d0](https://linux-hardware.org/?probe=2371d130d0) | Nov 30, 2019 |
| VIT           | Aptio CRB                   | Mini pc     | [aba5fa885d](https://linux-hardware.org/?probe=aba5fa885d) | Nov 25, 2019 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [7c2893dba4](https://linux-hardware.org/?probe=7c2893dba4) | Nov 15, 2019 |
| IBM           | 8188LS4                     | Desktop     | [3d775f418d](https://linux-hardware.org/?probe=3d775f418d) | Oct 08, 2019 |
| Foxconn       | 8657MF-series               | Desktop     | [8ce7f69a15](https://linux-hardware.org/?probe=8ce7f69a15) | Oct 05, 2019 |
| IBM           | 8188LS4                     | Desktop     | [3fc14db446](https://linux-hardware.org/?probe=3fc14db446) | Oct 05, 2019 |
| IBM           | 8188LS4                     | Desktop     | [af840eb366](https://linux-hardware.org/?probe=af840eb366) | Oct 04, 2019 |
| Lenovo        | IdeaPad S100c 20194         | Notebook    | [530c41513b](https://linux-hardware.org/?probe=530c41513b) | Sep 20, 2019 |
| Intel         | powered classmate PC        | Tablet      | [05f47d610a](https://linux-hardware.org/?probe=05f47d610a) | Aug 22, 2019 |
| Pegatron      | 2AAE                        | Desktop     | [f80cb4a7f2](https://linux-hardware.org/?probe=f80cb4a7f2) | Aug 17, 2019 |
| Dell          | 0RK936                      | Desktop     | [060c60558b](https://linux-hardware.org/?probe=060c60558b) | Aug 08, 2019 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [e107cafe33](https://linux-hardware.org/?probe=e107cafe33) | Jun 07, 2019 |
| ASRock        | H67M-GE                     | Desktop     | [65dd091a6f](https://linux-hardware.org/?probe=65dd091a6f) | May 13, 2019 |
| Lenovo        | G480 20150                  | Notebook    | [1b7e674c82](https://linux-hardware.org/?probe=1b7e674c82) | May 08, 2019 |
| Lenovo        | G480 20150                  | Notebook    | [99198fbcfa](https://linux-hardware.org/?probe=99198fbcfa) | May 08, 2019 |
| Pegatron      | 2AF0                        | Desktop     | [bebc187dbd](https://linux-hardware.org/?probe=bebc187dbd) | May 05, 2019 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1ddb0e459f](https://linux-hardware.org/?probe=1ddb0e459f) | Apr 26, 2019 |
| Pegatron      | IPPEL-DB                    | Desktop     | [c73b25ed21](https://linux-hardware.org/?probe=c73b25ed21) | Apr 24, 2019 |
| Pegatron      | IPPEL-DB                    | Desktop     | [d1941d4619](https://linux-hardware.org/?probe=d1941d4619) | Apr 24, 2019 |
| Lenovo        | H220 10028                  | Desktop     | [9b6593e8c6](https://linux-hardware.org/?probe=9b6593e8c6) | Apr 21, 2019 |
| ASRock        | N68C-S UCC                  | Desktop     | [ac39e69311](https://linux-hardware.org/?probe=ac39e69311) | Apr 21, 2019 |
| ASRock        | H67M-GE                     | Desktop     | [282ee52768](https://linux-hardware.org/?probe=282ee52768) | Apr 19, 2019 |
| HP            | Pavilion dv4                | Notebook    | [e59414c439](https://linux-hardware.org/?probe=e59414c439) | Apr 11, 2019 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [e054fab57c](https://linux-hardware.org/?probe=e054fab57c) | Nov 24, 2018 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [d3d5ff2e54](https://linux-hardware.org/?probe=d3d5ff2e54) | Nov 24, 2018 |
| Intel         | powered classmate PC        | Notebook    | [405f76133d](https://linux-hardware.org/?probe=405f76133d) | Oct 11, 2017 |
| Intel         | powered classmate PC        | Notebook    | [e79ec0466f](https://linux-hardware.org/?probe=e79ec0466f) | Oct 01, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [8d884b92fa](https://linux-hardware.org/?probe=8d884b92fa) | Sep 16, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [17af4fce47](https://linux-hardware.org/?probe=17af4fce47) | Sep 03, 2017 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [c501aaa553](https://linux-hardware.org/?probe=c501aaa553) | Sep 01, 2017 |
| Lenovo        | 3000 N200 0769ARS           | Notebook    | [1ada6660c3](https://linux-hardware.org/?probe=1ada6660c3) | Aug 15, 2017 |
| Lenovo        | 3000 N200 0769ARS           | Notebook    | [5548cd964f](https://linux-hardware.org/?probe=5548cd964f) | Jul 28, 2017 |
| ASRock        | 945GCM-S                    | Desktop     | [009791bef2](https://linux-hardware.org/?probe=009791bef2) | Jun 25, 2017 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [270499b92c](https://linux-hardware.org/?probe=270499b92c) | Dec 29, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Debian 11          | 29        | 10.39%  |
| Ubuntu 20.04       | 23        | 8.24%   |
| OpenMandriva 4.3   | 17        | 6.09%   |
| Ubuntu 18.04       | 16        | 5.73%   |
| Ubuntu 22.04       | 10        | 3.58%   |
| Debian 10          | 10        | 3.58%   |
| OpenMandriva 4.2   | 9         | 3.23%   |
| KDE neon 20.04     | 9         | 3.23%   |
| Zorin 16           | 7         | 2.51%   |
| Linux Mint 20.3    | 7         | 2.51%   |
| Xubuntu 18.04      | 6         | 2.15%   |
| Kubuntu 20.04      | 6         | 2.15%   |
| ROSA R9            | 5         | 1.79%   |
| ROSA R11           | 5         | 1.79%   |
| Linux Mint 20      | 5         | 1.79%   |
| Linux Mint 19.3    | 5         | 1.79%   |
| Ubuntu MATE 19.10  | 4         | 1.43%   |
| Ubuntu 19.10       | 4         | 1.43%   |
| Fedora 35          | 4         | 1.43%   |
| Zorin 15           | 3         | 1.08%   |
| Ubuntu 21.10       | 3         | 1.08%   |
| OpenMandriva 4.50  | 3         | 1.08%   |
| Manjaro            | 3         | 1.08%   |
| KDE neon 18.04     | 3         | 1.08%   |
| Fedora 36          | 3         | 1.08%   |
| Arch Rolling       | 3         | 1.08%   |
| Xubuntu 22.04      | 2         | 0.72%   |
| Xubuntu 20.04      | 2         | 0.72%   |
| Xubuntu 16.04      | 2         | 0.72%   |
| Ubuntu Unity 16.04 | 2         | 0.72%   |
| Ubuntu 20.10       | 2         | 0.72%   |
| Pop!_OS 22.04      | 2         | 0.72%   |
| Pop!_OS 21.04      | 2         | 0.72%   |
| MX 21              | 2         | 0.72%   |
| LMDE 5             | 2         | 0.72%   |
| Linux Mint 20.1    | 2         | 0.72%   |
| Fedora 34          | 2         | 0.72%   |
| Elementary 6.1     | 2         | 0.72%   |
| ArcoLinux Rolling  | 2         | 0.72%   |
| Arch               | 2         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 57        | 21.27%  |
| Debian       | 41        | 15.3%   |
| OpenMandriva | 29        | 10.82%  |
| Linux Mint   | 21        | 7.84%   |
| ROSA         | 14        | 5.22%   |
| Xubuntu      | 12        | 4.48%   |
| KDE neon     | 11        | 4.1%    |
| Zorin        | 10        | 3.73%   |
| Fedora       | 10        | 3.73%   |
| Manjaro      | 8         | 2.99%   |
| Kubuntu      | 7         | 2.61%   |
| Ubuntu MATE  | 5         | 1.87%   |
| Pop!_OS      | 5         | 1.87%   |
| Arch         | 5         | 1.87%   |
| Elementary   | 4         | 1.49%   |
| Ubuntu Unity | 3         | 1.12%   |
| MX           | 3         | 1.12%   |
| LMDE         | 3         | 1.12%   |
| Solus        | 2         | 0.75%   |
| Garuda Linux | 2         | 0.75%   |
| Feren OS     | 2         | 0.75%   |
| ArcoLinux    | 2         | 0.75%   |
| Sparky       | 1         | 0.37%   |
| Q4OS         | 1         | 0.37%   |
| PCLinuxOS    | 1         | 0.37%   |
| openSUSE     | 1         | 0.37%   |
| Nobara       | 1         | 0.37%   |
| Lubuntu      | 1         | 0.37%   |
| Linux Lite   | 1         | 0.37%   |
| Kali         | 1         | 0.37%   |
| Endless      | 1         | 0.37%   |
| Deepin       | 1         | 0.37%   |
| Alpine       | 1         | 0.37%   |
| AlmaLinux    | 1         | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 17        | 5.61%   |
| 5.10.14-desktop-1omv4002        | 9         | 2.97%   |
| 5.4.0-42-generic                | 8         | 2.64%   |
| 5.3.0-40-generic                | 6         | 1.98%   |
| 5.15.0-46-generic               | 6         | 1.98%   |
| 5.4.0-77-generic                | 4         | 1.32%   |
| 5.15.0-56-generic               | 4         | 1.32%   |
| 5.13.0-39-generic               | 4         | 1.32%   |
| 5.10.0-16-amd64                 | 4         | 1.32%   |
| 5.10.0-13-amd64                 | 4         | 1.32%   |
| 5.10.0-11-amd64                 | 4         | 1.32%   |
| 5.0.0-37-generic                | 4         | 1.32%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4         | 1.32%   |
| 4.19.0-17-amd64                 | 4         | 1.32%   |
| 5.4.0-73-generic                | 3         | 0.99%   |
| 5.4.0-52-generic                | 3         | 0.99%   |
| 5.3.0-29-generic                | 3         | 0.99%   |
| 5.15.0-52-generic               | 3         | 0.99%   |
| 5.11.0-37-generic               | 3         | 0.99%   |
| 4.15.0-48-generic               | 3         | 0.99%   |
| 5.8.0-63-generic                | 2         | 0.66%   |
| 5.8.0-55-generic                | 2         | 0.66%   |
| 5.8.0-44-generic                | 2         | 0.66%   |
| 5.4.0-89-generic                | 2         | 0.66%   |
| 5.4.0-74-generic                | 2         | 0.66%   |
| 5.4.0-66-generic                | 2         | 0.66%   |
| 5.4.0-54-generic                | 2         | 0.66%   |
| 5.4.0-48-generic                | 2         | 0.66%   |
| 5.4.0-31-generic                | 2         | 0.66%   |
| 5.4.0-26-generic                | 2         | 0.66%   |
| 5.4.0-107-generic               | 2         | 0.66%   |
| 5.3.0-42-generic                | 2         | 0.66%   |
| 5.19.0-2-amd64                  | 2         | 0.66%   |
| 5.15.0-53-generic               | 2         | 0.66%   |
| 5.15.0-48-generic               | 2         | 0.66%   |
| 5.15.0-43-generic               | 2         | 0.66%   |
| 5.14.10-300.fc35.x86_64         | 2         | 0.66%   |
| 5.13.0-52-generic               | 2         | 0.66%   |
| 5.13.0-51-generic               | 2         | 0.66%   |
| 5.13.0-28-generic               | 2         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 46        | 16.31%  |
| 5.10.0  | 28        | 9.93%   |
| 4.15.0  | 23        | 8.16%   |
| 5.15.0  | 22        | 7.8%    |
| 5.13.0  | 19        | 6.74%   |
| 5.16.7  | 17        | 6.03%   |
| 5.3.0   | 12        | 4.26%   |
| 4.19.0  | 12        | 4.26%   |
| 5.8.0   | 10        | 3.55%   |
| 5.11.0  | 9         | 3.19%   |
| 5.10.14 | 9         | 3.19%   |
| 5.0.0   | 7         | 2.48%   |
| 4.9.20  | 5         | 1.77%   |
| 5.19.0  | 3         | 1.06%   |
| 5.14.10 | 3         | 1.06%   |
| 5.15.6  | 2         | 0.71%   |
| 5.12.4  | 2         | 0.71%   |
| 4.9.0   | 2         | 0.71%   |
| 4.18.0  | 2         | 0.71%   |
| 6.0.8   | 1         | 0.35%   |
| 6.0.5   | 1         | 0.35%   |
| 6.0.2   | 1         | 0.35%   |
| 6.0.0   | 1         | 0.35%   |
| 5.9.16  | 1         | 0.35%   |
| 5.9.0   | 1         | 0.35%   |
| 5.8.6   | 1         | 0.35%   |
| 5.8.11  | 1         | 0.35%   |
| 5.8.10  | 1         | 0.35%   |
| 5.7.0   | 1         | 0.35%   |
| 5.6.6   | 1         | 0.35%   |
| 5.6.18  | 1         | 0.35%   |
| 5.6.0   | 1         | 0.35%   |
| 5.5.4   | 1         | 0.35%   |
| 5.4.83  | 1         | 0.35%   |
| 5.4.105 | 1         | 0.35%   |
| 5.19.9  | 1         | 0.35%   |
| 5.19.5  | 1         | 0.35%   |
| 5.18.7  | 1         | 0.35%   |
| 5.18.0  | 1         | 0.35%   |
| 5.17.2  | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 48        | 17.2%   |
| 5.10    | 43        | 15.41%  |
| 5.15    | 31        | 11.11%  |
| 4.15    | 23        | 8.24%   |
| 5.13    | 22        | 7.89%   |
| 5.16    | 19        | 6.81%   |
| 5.8     | 13        | 4.66%   |
| 5.3     | 12        | 4.3%    |
| 4.19    | 12        | 4.3%    |
| 5.11    | 9         | 3.23%   |
| 5.0     | 7         | 2.51%   |
| 4.9     | 7         | 2.51%   |
| 5.19    | 5         | 1.79%   |
| 6.0     | 4         | 1.43%   |
| 5.17    | 4         | 1.43%   |
| 5.6     | 3         | 1.08%   |
| 5.14    | 3         | 1.08%   |
| 5.12    | 3         | 1.08%   |
| 5.9     | 2         | 0.72%   |
| 5.18    | 2         | 0.72%   |
| 4.18    | 2         | 0.72%   |
| 5.7     | 1         | 0.36%   |
| 5.5     | 1         | 0.36%   |
| 4.4     | 1         | 0.36%   |
| 4.13    | 1         | 0.36%   |
| 4.1     | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 232       | 89.92%  |
| i686   | 26        | 10.08%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 85        | 31.02%  |
| KDE5            | 60        | 21.9%   |
| XFCE            | 36        | 13.14%  |
| Unknown         | 25        | 9.12%   |
| X-Cinnamon      | 13        | 4.74%   |
| MATE            | 12        | 4.38%   |
| KDE             | 12        | 4.38%   |
| KDE4            | 7         | 2.55%   |
| Cinnamon        | 5         | 1.82%   |
| LXDE            | 4         | 1.46%   |
| Unity           | 3         | 1.09%   |
| Pantheon        | 3         | 1.09%   |
| LXQt            | 2         | 0.73%   |
| GNOME Classic   | 2         | 0.73%   |
| Budgie          | 2         | 0.73%   |
| xmonad          | 1         | 0.36%   |
| GNOME Flashback | 1         | 0.36%   |
| Deepin          | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 223       | 85.77%  |
| Wayland | 30        | 11.54%  |
| Unknown | 5         | 1.92%   |
| Tty     | 2         | 0.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 108       | 40.45%  |
| SDDM    | 53        | 19.85%  |
| GDM     | 36        | 13.48%  |
| LightDM | 33        | 12.36%  |
| GDM3    | 18        | 6.74%   |
| TDM     | 10        | 3.75%   |
| KDM     | 7         | 2.62%   |
| SLiM    | 2         | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_VE   | 158       | 59.85%  |
| en_US   | 59        | 22.35%  |
| Unknown | 25        | 9.47%   |
| es_ES   | 16        | 6.06%   |
| es_US   | 2         | 0.76%   |
| C       | 2         | 0.76%   |
| en_CA   | 1         | 0.38%   |
| de_DE   | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 196       | 75.38%  |
| EFI  | 64        | 24.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 204       | 78.46%  |
| Overlay | 29        | 11.15%  |
| Btrfs   | 13        | 5%      |
| Unknown | 8         | 3.08%   |
| Xfs     | 4         | 1.54%   |
| Ext2    | 2         | 0.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 124       | 47.33%  |
| MBR     | 78        | 29.77%  |
| GPT     | 60        | 22.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 214       | 81.68%  |
| Yes       | 48        | 18.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 160       | 62.02%  |
| Yes       | 98        | 37.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 29        | 11.33%  |
| Dell                           | 26        | 10.16%  |
| Hewlett-Packard                | 24        | 9.38%   |
| ASRock                         | 24        | 9.38%   |
| Intel                          | 23        | 8.98%   |
| VIT                            | 22        | 8.59%   |
| ASUSTek Computer               | 17        | 6.64%   |
| ECS                            | 14        | 5.47%   |
| Pegatron                       | 11        | 4.3%    |
| Gigabyte Technology            | 8         | 3.13%   |
| Biostar                        | 8         | 3.13%   |
| Acer                           | 7         | 2.73%   |
| Unknown                        | 6         | 2.34%   |
| MSI                            | 5         | 1.95%   |
| langchao                       | 4         | 1.56%   |
| Foxconn                        | 4         | 1.56%   |
| Apple                          | 4         | 1.56%   |
| Toshiba                        | 2         | 0.78%   |
| Shanghai Zhaoxin Semiconductor | 2         | 0.78%   |
| Google                         | 2         | 0.78%   |
| UNIQCELL                       | 1         | 0.39%   |
| Standard                       | 1         | 0.39%   |
| Sony                           | 1         | 0.39%   |
| SIRAGON                        | 1         | 0.39%   |
| Samsung Electronics            | 1         | 0.39%   |
| IP3 Tech                       | 1         | 0.39%   |
| Inspur                         | 1         | 0.39%   |
| IBM                            | 1         | 0.39%   |
| GPU Company                    | 1         | 0.39%   |
| Gateway                        | 1         | 0.39%   |
| Exo                            | 1         | 0.39%   |
| Clevo                          | 1         | 0.39%   |
| AVITA                          | 1         | 0.39%   |
| Alienware                      | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel powered classmate PC           | 10        | 3.91%   |
| ECS H61H2-CM                         | 8         | 3.13%   |
| ASRock G41M-VS3                      | 6         | 2.34%   |
| Unknown                              | 6         | 2.34%   |
| VIT P2400                            | 5         | 1.95%   |
| VIT P2402                            | 4         | 1.56%   |
| langchao 12345                       | 4         | 1.56%   |
| VIT P3400                            | 3         | 1.17%   |
| VIT M2420                            | 3         | 1.17%   |
| ASRock N68C-S UCC                    | 3         | 1.17%   |
| ASRock N68-VS3 UCC                   | 3         | 1.17%   |
| VIT M2421                            | 2         | 0.78%   |
| VIT Aptio CRB                        | 2         | 0.78%   |
| Shanghai Zhaoxin ZXE CRB             | 2         | 0.78%   |
| Pegatron Compaq dx2400 Microtower    | 2         | 0.78%   |
| Lenovo IdeaPad S100c 20194           | 2         | 0.78%   |
| Lenovo 3000 N200 0769ARS             | 2         | 0.78%   |
| Intel H61                            | 2         | 0.78%   |
| HP Compaq Presario C700              | 2         | 0.78%   |
| Dell Inspiron 1545                   | 2         | 0.78%   |
| Apple iMac11,2                       | 2         | 0.78%   |
| VIT P1400                            | 1         | 0.39%   |
| VIT NP3020M3                         | 1         | 0.39%   |
| VIT M2400-01                         | 1         | 0.39%   |
| UNIQCELL Q15.6                       | 1         | 0.39%   |
| Toshiba Satellite E55t-A             | 1         | 0.39%   |
| Toshiba ENCORE 2 WT8-B               | 1         | 0.39%   |
| Standard AIO                         | 1         | 0.39%   |
| Sony VGN-FW510F                      | 1         | 0.39%   |
| SIRAGON AIO-5150                     | 1         | 0.39%   |
| Samsung 355V4C/356V4C/3445VC/3545VC  | 1         | 0.39%   |
| Pegatron T14AF                       | 1         | 0.39%   |
| Pegatron PEGATRON                    | 1         | 0.39%   |
| Pegatron IPPEL-DB                    | 1         | 0.39%   |
| Pegatron IPM41-D3                    | 1         | 0.39%   |
| Pegatron CQ1507LA                    | 1         | 0.39%   |
| Pegatron Compaq dx2400 Microtower PC | 1         | 0.39%   |
| Pegatron BM411AA-ABA CQ5600F         | 1         | 0.39%   |
| Pegatron 20-b010                     | 1         | 0.39%   |
| Pegatron 100-5010la                  | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Dell Inspiron        | 11        | 4.3%    |
| Intel powered        | 10        | 3.91%   |
| HP Compaq            | 9         | 3.52%   |
| ECS H61H2-CM         | 8         | 3.13%   |
| Lenovo ThinkCentre   | 7         | 2.73%   |
| Lenovo IdeaPad       | 7         | 2.73%   |
| HP Pavilion          | 7         | 2.73%   |
| ASRock G41M-VS3      | 6         | 2.34%   |
| Acer Aspire          | 6         | 2.34%   |
| Unknown              | 6         | 2.34%   |
| VIT P2400            | 5         | 1.95%   |
| Dell Vostro          | 5         | 1.95%   |
| VIT P2402            | 4         | 1.56%   |
| Lenovo ThinkPad      | 4         | 1.56%   |
| langchao 12345       | 4         | 1.56%   |
| Dell Latitude        | 4         | 1.56%   |
| VIT P3400            | 3         | 1.17%   |
| VIT M2420            | 3         | 1.17%   |
| Pegatron Compaq      | 3         | 1.17%   |
| Lenovo 3000          | 3         | 1.17%   |
| Dell OptiPlex        | 3         | 1.17%   |
| ASRock N68C-S        | 3         | 1.17%   |
| ASRock N68-VS3       | 3         | 1.17%   |
| VIT M2421            | 2         | 0.78%   |
| VIT Aptio            | 2         | 0.78%   |
| Shanghai Zhaoxin ZXE | 2         | 0.78%   |
| Intel H61            | 2         | 0.78%   |
| HP Presario          | 2         | 0.78%   |
| HP EliteBook         | 2         | 0.78%   |
| Dell Precision       | 2         | 0.78%   |
| ASUS VivoBook        | 2         | 0.78%   |
| ASUS P5G41T-M        | 2         | 0.78%   |
| ASUS ASUS            | 2         | 0.78%   |
| Apple iMac11         | 2         | 0.78%   |
| VIT P1400            | 1         | 0.39%   |
| VIT NP3020M3         | 1         | 0.39%   |
| VIT M2400-01         | 1         | 0.39%   |
| UNIQCELL Q15.6       | 1         | 0.39%   |
| Toshiba Satellite    | 1         | 0.39%   |
| Toshiba ENCORE       | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 45        | 17.58%  |
| 2010    | 41        | 16.02%  |
| 2012    | 28        | 10.94%  |
| 2007    | 20        | 7.81%   |
| 2008    | 19        | 7.42%   |
| 2013    | 18        | 7.03%   |
| 2014    | 15        | 5.86%   |
| 2020    | 8         | 3.13%   |
| 2017    | 8         | 3.13%   |
| 2006    | 8         | 3.13%   |
| 2021    | 7         | 2.73%   |
| 2018    | 7         | 2.73%   |
| 2015    | 7         | 2.73%   |
| 2009    | 7         | 2.73%   |
| 2022    | 6         | 2.34%   |
| 2019    | 6         | 2.34%   |
| 2016    | 4         | 1.56%   |
| 2005    | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 125       | 48.83%  |
| Notebook   | 115       | 44.92%  |
| All in one | 6         | 2.34%   |
| Tablet     | 4         | 1.56%   |
| Mini pc    | 3         | 1.17%   |
| Server     | 3         | 1.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 252       | 98.44%  |
| Enabled  | 4         | 1.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 254       | 99.22%  |
| Yes  | 2         | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 73        | 28.08%  |
| 4.01-8.0    | 55        | 21.15%  |
| 1.01-2.0    | 50        | 19.23%  |
| 8.01-16.0   | 37        | 14.23%  |
| 16.01-24.0  | 22        | 8.46%   |
| 2.01-3.0    | 11        | 4.23%   |
| 32.01-64.0  | 4         | 1.54%   |
| 24.01-32.0  | 4         | 1.54%   |
| 0.51-1.0    | 3         | 1.15%   |
| 64.01-256.0 | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 112       | 39.44%  |
| 2.01-3.0   | 71        | 25%     |
| 0.51-1.0   | 42        | 14.79%  |
| 4.01-8.0   | 30        | 10.56%  |
| 3.01-4.0   | 21        | 7.39%   |
| 0.01-0.5   | 4         | 1.41%   |
| 8.01-16.0  | 3         | 1.06%   |
| 16.01-24.0 | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 164       | 62.36%  |
| 2      | 79        | 30.04%  |
| 3      | 17        | 6.46%   |
| 4      | 2         | 0.76%   |
| 6      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 53.46%  |
| Yes       | 121       | 46.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 239       | 93%     |
| No        | 18        | 7%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 72.87%  |
| No        | 70        | 27.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 173       | 66.8%   |
| Yes       | 86        | 33.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Venezuela | 256       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 120       | 43.48%  |
| Maracaibo                  | 18        | 6.52%   |
| Maracay                    | 15        | 5.43%   |
| Barquisimeto               | 12        | 4.35%   |
| Valencia                   | 11        | 3.99%   |
| San Cristóbal             | 9         | 3.26%   |
| Mérida                    | 9         | 3.26%   |
| Barcelona                  | 7         | 2.54%   |
| San Carlos del Zulia       | 6         | 2.17%   |
| Maturín                   | 6         | 2.17%   |
| Barinas                    | 4         | 1.45%   |
| Parroquia El Recreo        | 3         | 1.09%   |
| Lecherias                  | 3         | 1.09%   |
| Ciudad Guayana             | 3         | 1.09%   |
| Ciudad Bolívar            | 3         | 1.09%   |
| Carrizal                   | 3         | 1.09%   |
| Acarigua                   | 3         | 1.09%   |
| San Juan Bautista          | 2         | 0.72%   |
| San Antonio de Los Altos   | 2         | 0.72%   |
| Porlamar                   | 2         | 0.72%   |
| Los Teques                 | 2         | 0.72%   |
| Los Palos Grandes          | 2         | 0.72%   |
| Las Vegas                  | 2         | 0.72%   |
| Guatire                    | 2         | 0.72%   |
| Guarenas                   | 2         | 0.72%   |
| Cua                        | 2         | 0.72%   |
| Anaco                      | 2         | 0.72%   |
| Valle de La Pascua         | 1         | 0.36%   |
| Tucupita                   | 1         | 0.36%   |
| Tucape                     | 1         | 0.36%   |
| Santa Rita                 | 1         | 0.36%   |
| San Francisco              | 1         | 0.36%   |
| San Felipe                 | 1         | 0.36%   |
| San Diego                  | 1         | 0.36%   |
| Puerto Ordaz and San Felix | 1         | 0.36%   |
| Puerto Cumarebo            | 1         | 0.36%   |
| Puerto Cruz                | 1         | 0.36%   |
| Naguanagua                 | 1         | 0.36%   |
| Mene Grande                | 1         | 0.36%   |
| Mariara                    | 1         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 85        | 117    | 25.99%  |
| Seagate             | 76        | 118    | 23.24%  |
| Hitachi             | 34        | 47     | 10.4%   |
| Toshiba             | 25        | 26     | 7.65%   |
| Samsung Electronics | 23        | 27     | 7.03%   |
| Unknown             | 10        | 14     | 3.06%   |
| Kingston            | 10        | 12     | 3.06%   |
| Crucial             | 6         | 8      | 1.83%   |
| SK hynix            | 5         | 6      | 1.53%   |
| SanDisk             | 5         | 7      | 1.53%   |
| PNY                 | 5         | 6      | 1.53%   |
| Intel               | 5         | 8      | 1.53%   |
| HGST                | 5         | 5      | 1.53%   |
| Maxtor              | 4         | 4      | 1.22%   |
| LITEONIT            | 4         | 7      | 1.22%   |
| SPCC                | 3         | 4      | 0.92%   |
| Fujitsu             | 3         | 3      | 0.92%   |
| Team                | 2         | 2      | 0.61%   |
| Patriot             | 2         | 2      | 0.61%   |
| Vaseky              | 1         | 1      | 0.31%   |
| Silicon Motion      | 1         | 1      | 0.31%   |
| PUSKILL             | 1         | 1      | 0.31%   |
| Phison              | 1         | 1      | 0.31%   |
| Micron Technology   | 1         | 3      | 0.31%   |
| Lexar               | 1         | 1      | 0.31%   |
| KingFast            | 1         | 2      | 0.31%   |
| Intenso             | 1         | 1      | 0.31%   |
| HUAWEI              | 1         | 1      | 0.31%   |
| ExcelStor           | 1         | 1      | 0.31%   |
| Dogfish             | 1         | 1      | 0.31%   |
| Dell                | 1         | 2      | 0.31%   |
| BIWIN               | 1         | 2      | 0.31%   |
| Apacer              | 1         | 1      | 0.31%   |
| addlink             | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST320LT012-1DG14C 320GB     | 13        | 3.61%   |
| Toshiba DT01ACA050 500GB            | 7         | 1.94%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 6         | 1.67%   |
| Seagate ST320LM000 HM321HI 320GB    | 5         | 1.39%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 4         | 1.11%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 1.11%   |
| Seagate ST500DM002-1BD142 500GB     | 4         | 1.11%   |
| Seagate ST3320418AS 320GB           | 4         | 1.11%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 1.11%   |
| Kingston SA400S37240G 240GB SSD     | 4         | 1.11%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 0.83%   |
| WDC WD5000AAKX-221CA1 500GB         | 3         | 0.83%   |
| WDC WD5000AAKX-001CA0 500GB         | 3         | 0.83%   |
| WDC WD5000AAKS-00A7B0 500GB         | 3         | 0.83%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 0.83%   |
| WDC WD3200AAJS-08L7A0 320GB         | 3         | 0.83%   |
| WDC WD3200AAJS-00L7A0 320GB         | 3         | 0.83%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 0.83%   |
| Seagate ST320LT012-9WS14C 320GB     | 3         | 0.83%   |
| Seagate ST250LM004 HN-M250MBB 250GB | 3         | 0.83%   |
| Samsung HD502HJ 500GB               | 3         | 0.83%   |
| Samsung HD161HJ 160GB               | 3         | 0.83%   |
| LITEONIT LMS-32L6M 32GB SSD         | 3         | 0.83%   |
| Hitachi HTS542580K9SA00 80GB        | 3         | 0.83%   |
| Hitachi HDS728080PLA380 82GB        | 3         | 0.83%   |
| WDC WD800BD-22MRA1 80GB             | 2         | 0.56%   |
| WDC WD800BB-22JHC0 80GB             | 2         | 0.56%   |
| WDC WD5000LPVT-08G33T1 500GB        | 2         | 0.56%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 2         | 0.56%   |
| WDC WD2500AAJS-60B4A0 250GB         | 2         | 0.56%   |
| WDC WD1200BEVS-60UST0 120GB         | 2         | 0.56%   |
| Unknown NVMe SSD Drive 512GB        | 2         | 0.56%   |
| Unknown MMC Card  16GB              | 2         | 0.56%   |
| Toshiba MQ04ABF100 1TB              | 2         | 0.56%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.56%   |
| Toshiba MQ01ABF032 320GB            | 2         | 0.56%   |
| Toshiba MQ01ABD050 500GB            | 2         | 0.56%   |
| Toshiba MK3275GSX 320GB             | 2         | 0.56%   |
| SPCC Solid State Disk 128GB         | 2         | 0.56%   |
| SK hynix SC300B SATA 512GB SSD      | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 83        | 113    | 33.6%   |
| Seagate             | 74        | 116    | 29.96%  |
| Hitachi             | 34        | 47     | 13.77%  |
| Toshiba             | 24        | 25     | 9.72%   |
| Samsung Electronics | 17        | 20     | 6.88%   |
| HGST                | 5         | 5      | 2.02%   |
| Maxtor              | 4         | 4      | 1.62%   |
| Fujitsu             | 3         | 3      | 1.21%   |
| Unknown             | 2         | 2      | 0.81%   |
| ExcelStor           | 1         | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 9         | 11     | 18.37%  |
| Crucial             | 6         | 8      | 12.24%  |
| PNY                 | 5         | 6      | 10.2%   |
| Samsung Electronics | 4         | 5      | 8.16%   |
| LITEONIT            | 4         | 7      | 8.16%   |
| SPCC                | 3         | 4      | 6.12%   |
| SK hynix            | 2         | 2      | 4.08%   |
| SanDisk             | 2         | 3      | 4.08%   |
| Patriot             | 2         | 2      | 4.08%   |
| Vaseky              | 1         | 1      | 2.04%   |
| Toshiba             | 1         | 1      | 2.04%   |
| Team                | 1         | 1      | 2.04%   |
| PUSKILL             | 1         | 1      | 2.04%   |
| Micron Technology   | 1         | 3      | 2.04%   |
| Lexar               | 1         | 1      | 2.04%   |
| KingFast            | 1         | 2      | 2.04%   |
| Intenso             | 1         | 1      | 2.04%   |
| Intel               | 1         | 1      | 2.04%   |
| Dogfish             | 1         | 1      | 2.04%   |
| Dell                | 1         | 2      | 2.04%   |
| BIWIN               | 1         | 2      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 203       | 336    | 72.5%   |
| SSD     | 47        | 65     | 16.79%  |
| NVMe    | 21        | 30     | 7.5%    |
| MMC     | 6         | 9      | 2.14%   |
| Unknown | 3         | 3      | 1.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 234       | 398    | 87.64%  |
| NVMe | 21        | 30     | 7.87%   |
| SAS  | 6         | 6      | 2.25%   |
| MMC  | 6         | 9      | 2.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 212       | 320    | 80%     |
| 0.51-1.0   | 38        | 57     | 14.34%  |
| 1.01-2.0   | 11        | 19     | 4.15%   |
| 3.01-4.0   | 2         | 2      | 0.75%   |
| 2.01-3.0   | 2         | 3      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 88        | 32.23%  |
| 101-250        | 62        | 22.71%  |
| 501-1000       | 39        | 14.29%  |
| 1-20           | 30        | 10.99%  |
| 51-100         | 22        | 8.06%   |
| 21-50          | 13        | 4.76%   |
| 1001-2000      | 10        | 3.66%   |
| 2001-3000      | 4         | 1.47%   |
| Unknown        | 3         | 1.1%    |
| More than 3000 | 2         | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 113       | 40.07%  |
| 21-50          | 53        | 18.79%  |
| 101-250        | 42        | 14.89%  |
| 51-100         | 28        | 9.93%   |
| 251-500        | 24        | 8.51%   |
| 501-1000       | 12        | 4.26%   |
| 2001-3000      | 3         | 1.06%   |
| Unknown        | 3         | 1.06%   |
| More than 3000 | 2         | 0.71%   |
| 1001-2000      | 2         | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB   | 5         | 6      | 6.25%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 3         | 4      | 3.75%   |
| WDC WD5000AAKX-221CA1 500GB       | 2         | 2      | 2.5%    |
| WDC WD5000AAKS-00A7B0 500GB       | 2         | 2      | 2.5%    |
| WDC WD1200BEVS-60UST0 120GB       | 2         | 2      | 2.5%    |
| Toshiba DT01ACA050 500GB          | 2         | 3      | 2.5%    |
| Seagate ST500DM002-1BD142 500GB   | 2         | 2      | 2.5%    |
| Samsung Electronics HM321HI 320GB | 2         | 2      | 2.5%    |
| Hitachi HDS728080PLA380 82GB      | 2         | 2      | 2.5%    |
| Hitachi HDS721616PLA380 160GB     | 2         | 2      | 2.5%    |
| WDC WD800BD-08MRA1 80GB           | 1         | 1      | 1.25%   |
| WDC WD800BB-22JHC0 80GB           | 1         | 1      | 1.25%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 1.25%   |
| WDC WD5000BPVT-24HXZT3 500GB      | 1         | 1      | 1.25%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1         | 1      | 1.25%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 1      | 1.25%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1         | 1      | 1.25%   |
| WDC WD50 00BPVT-24HXZT1 500GB     | 1         | 1      | 1.25%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1         | 1      | 1.25%   |
| WDC WD3200BEKT-22F3T0 320GB       | 1         | 1      | 1.25%   |
| WDC WD3200AAJS-08L7A0 320GB       | 1         | 2      | 1.25%   |
| WDC WD2003FYPS-27Y2B0 2TB         | 1         | 1      | 1.25%   |
| WDC WD10JPVX-22JC3T0 1TB          | 1         | 2      | 1.25%   |
| WDC WD10EZEX-22RKKA0 1TB          | 1         | 1      | 1.25%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1         | 1      | 1.25%   |
| Toshiba MQ01ACF050 500GB          | 1         | 1      | 1.25%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 1.25%   |
| Toshiba MK3275GSX 320GB           | 1         | 1      | 1.25%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 1.25%   |
| Seagate ST9320325AS 320GB         | 1         | 1      | 1.25%   |
| Seagate ST9160314AS 160GB         | 1         | 1      | 1.25%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 1.25%   |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 1.25%   |
| Seagate ST500DM005 HD502HJ 500GB  | 1         | 1      | 1.25%   |
| Seagate ST3500630AS 500GB         | 1         | 1      | 1.25%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 1.25%   |
| Seagate ST3500413AS 500GB         | 1         | 1      | 1.25%   |
| Seagate ST3500312CS 500GB         | 1         | 1      | 1.25%   |
| Seagate ST340014AS 40GB           | 1         | 1      | 1.25%   |
| Seagate ST3320418AS 320GB         | 1         | 2      | 1.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 26     | 31.08%  |
| WDC                 | 19        | 27     | 25.68%  |
| Hitachi             | 14        | 14     | 18.92%  |
| Samsung Electronics | 7         | 8      | 9.46%   |
| Toshiba             | 5         | 6      | 6.76%   |
| Maxtor              | 2         | 2      | 2.7%    |
| HGST                | 2         | 2      | 2.7%    |
| Intel               | 1         | 1      | 1.35%   |
| ExcelStor           | 1         | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 26     | 31.51%  |
| WDC                 | 19        | 27     | 26.03%  |
| Hitachi             | 14        | 14     | 19.18%  |
| Samsung Electronics | 7         | 8      | 9.59%   |
| Toshiba             | 5         | 6      | 6.85%   |
| Maxtor              | 2         | 2      | 2.74%   |
| HGST                | 2         | 2      | 2.74%   |
| ExcelStor           | 1         | 1      | 1.37%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 62        | 86     | 98.41%  |
| NVMe | 1         | 1      | 1.59%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB | 2         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 139       | 247    | 49.29%  |
| Works    | 78        | 107    | 27.66%  |
| Malfunc  | 63        | 87     | 22.34%  |
| Failed   | 2         | 2      | 0.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 202       | 72.92%  |
| AMD                         | 29        | 10.47%  |
| Nvidia                      | 14        | 5.05%   |
| Marvell Technology Group    | 5         | 1.81%   |
| JMicron Technology          | 5         | 1.81%   |
| SanDisk                     | 4         | 1.44%   |
| VIA Technologies            | 3         | 1.08%   |
| SK hynix                    | 3         | 1.08%   |
| Unknown                     | 3         | 1.08%   |
| Silicon Motion              | 2         | 0.72%   |
| Samsung Electronics         | 2         | 0.72%   |
| Phison Electronics          | 2         | 0.72%   |
| Kingston Technology Company | 1         | 0.36%   |
| ASMedia Technology          | 1         | 0.36%   |
| Adaptec                     | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 33        | 8.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 25        | 6.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 18        | 4.81%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 4.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 4.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14        | 3.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 14        | 3.74%   |
| Nvidia MCP61 SATA Controller                                                            | 13        | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 3.21%   |
| Nvidia MCP61 IDE                                                                        | 11        | 2.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 8         | 2.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 2.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7         | 1.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 1.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 1.87%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6         | 1.6%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6         | 1.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 1.34%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5         | 1.34%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5         | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 4         | 1.07%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.07%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.8%    |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.8%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3         | 0.8%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3         | 0.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 0.8%    |
| Unknown                                                                                 | 3         | 0.8%    |
| VIA Serial ATA Controller                                                               | 2         | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.53%   |
| SanDisk Non-Volatile memory controller                                                  | 2         | 0.53%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 151       | 52.07%  |
| IDE  | 103       | 35.52%  |
| NVMe | 21        | 7.24%   |
| RAID | 13        | 4.48%   |
| SAS  | 1         | 0.34%   |
| SCSI | 1         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 210       | 82.03%  |
| AMD          | 44        | 17.19%  |
| CentaurHauls | 2         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 6         | 2.34%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 6         | 2.34%   |
| Intel Celeron CPU N2805 @ 1.46GHz           | 6         | 2.34%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 4         | 1.56%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4         | 1.56%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 4         | 1.56%   |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 1.56%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 3         | 1.17%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3         | 1.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 1.17%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 1.17%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 3         | 1.17%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3         | 1.17%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3         | 1.17%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3         | 1.17%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 3         | 1.17%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz        | 3         | 1.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 1.17%   |
| AMD Sempron 145 Processor                   | 3         | 1.17%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 0.78%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 2         | 0.78%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 2         | 0.78%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz      | 2         | 0.78%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2         | 0.78%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 2         | 0.78%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 2         | 0.78%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 2         | 0.78%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 2         | 0.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 0.78%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.78%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 0.78%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2         | 0.78%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 0.78%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 0.78%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.78%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 0.78%   |
| Intel Core i3-4000M CPU @ 2.40GHz           | 2         | 0.78%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 0.78%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 0.78%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 36        | 14.06%  |
| Intel Core i3                  | 30        | 11.72%  |
| Intel Pentium Dual-Core        | 24        | 9.38%   |
| Intel Core 2 Duo               | 19        | 7.42%   |
| Intel Celeron                  | 18        | 7.03%   |
| Intel Pentium                  | 17        | 6.64%   |
| Intel Core i7                  | 17        | 6.64%   |
| Intel Atom                     | 10        | 3.91%   |
| Other                          | 9         | 3.52%   |
| Intel Pentium Dual             | 8         | 3.13%   |
| Intel Xeon                     | 7         | 2.73%   |
| AMD Sempron                    | 7         | 2.73%   |
| AMD Ryzen 5                    | 6         | 2.34%   |
| Intel Core 2 Quad              | 5         | 1.95%   |
| Intel Pentium 4                | 4         | 1.56%   |
| Intel Core 2                   | 4         | 1.56%   |
| AMD FX                         | 3         | 1.17%   |
| AMD Athlon II X2               | 3         | 1.17%   |
| Intel Genuine                  | 2         | 0.78%   |
| AMD Ryzen 7                    | 2         | 0.78%   |
| AMD Ryzen 3                    | 2         | 0.78%   |
| AMD Phenom II X4               | 2         | 0.78%   |
| AMD Phenom                     | 2         | 0.78%   |
| AMD E1                         | 2         | 0.78%   |
| AMD Athlon                     | 2         | 0.78%   |
| AMD A6                         | 2         | 0.78%   |
| AMD A10                        | 2         | 0.78%   |
| Intel Pentium Silver           | 1         | 0.39%   |
| Intel Pentium D                | 1         | 0.39%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.39%   |
| AMD Phenom II X2               | 1         | 0.39%   |
| AMD Mobile Sempron             | 1         | 0.39%   |
| AMD E                          | 1         | 0.39%   |
| AMD Athlon II X4               | 1         | 0.39%   |
| AMD Athlon II                  | 1         | 0.39%   |
| AMD Athlon 64 X2               | 1         | 0.39%   |
| AMD A8                         | 1         | 0.39%   |
| AMD A4                         | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 157       | 61.33%  |
| 4       | 65        | 25.39%  |
| 1       | 19        | 7.42%   |
| 6       | 4         | 1.56%   |
| 3       | 4         | 1.56%   |
| Unknown | 4         | 1.56%   |
| 8       | 3         | 1.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 256       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 151       | 58.98%  |
| 2       | 101       | 39.45%  |
| Unknown | 4         | 1.56%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 246       | 96.09%  |
| 64-bit         | 5         | 1.95%   |
| 32-bit         | 4         | 1.56%   |
| Unknown        | 1         | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 17.56%  |
| 0x1067a    | 37        | 14.12%  |
| 0x206a7    | 30        | 11.45%  |
| 0x306a9    | 23        | 8.78%   |
| 0x6fd      | 11        | 4.2%    |
| 0x306c3    | 7         | 2.67%   |
| 0x30673    | 6         | 2.29%   |
| 0x106ca    | 6         | 2.29%   |
| 0x806e9    | 5         | 1.91%   |
| 0x806c1    | 5         | 1.91%   |
| 0x010000c8 | 5         | 1.91%   |
| 0x6fb      | 4         | 1.53%   |
| 0x20655    | 4         | 1.53%   |
| 0xf65      | 3         | 1.15%   |
| 0x6f2      | 3         | 1.15%   |
| 0x40651    | 3         | 1.15%   |
| 0x30678    | 3         | 1.15%   |
| 0x106a5    | 3         | 1.15%   |
| 0x05000119 | 3         | 1.15%   |
| 0x010000c7 | 3         | 1.15%   |
| 0x906e9    | 2         | 0.76%   |
| 0x406e3    | 2         | 0.76%   |
| 0x406c4    | 2         | 0.76%   |
| 0x306d4    | 2         | 0.76%   |
| 0x10676    | 2         | 0.76%   |
| 0x08608103 | 2         | 0.76%   |
| 0x08108102 | 2         | 0.76%   |
| 0x0810100b | 2         | 0.76%   |
| 0x0600063e | 2         | 0.76%   |
| 0x010000b6 | 2         | 0.76%   |
| 0xf47      | 1         | 0.38%   |
| 0xf41      | 1         | 0.38%   |
| 0xa0671    | 1         | 0.38%   |
| 0x906eb    | 1         | 0.38%   |
| 0x806ea    | 1         | 0.38%   |
| 0x806d1    | 1         | 0.38%   |
| 0x706e5    | 1         | 0.38%   |
| 0x706a8    | 1         | 0.38%   |
| 0x6fa      | 1         | 0.38%   |
| 0x6f6      | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Penryn          | 40        | 15.63%  |
| SandyBridge     | 39        | 15.23%  |
| IvyBridge       | 28        | 10.94%  |
| Core            | 25        | 9.77%   |
| K10             | 15        | 5.86%   |
| Silvermont      | 12        | 4.69%   |
| Haswell         | 12        | 4.69%   |
| KabyLake        | 11        | 4.3%    |
| Westmere        | 9         | 3.52%   |
| Bonnell         | 9         | 3.52%   |
| TigerLake       | 5         | 1.95%   |
| NetBurst        | 5         | 1.95%   |
| Unknown         | 5         | 1.95%   |
| Zen+            | 4         | 1.56%   |
| K8 Hammer       | 4         | 1.56%   |
| Zen             | 3         | 1.17%   |
| Skylake         | 3         | 1.17%   |
| Nehalem         | 3         | 1.17%   |
| Bobcat          | 3         | 1.17%   |
| Zen 2           | 2         | 0.78%   |
| Piledriver      | 2         | 0.78%   |
| K10 Llano       | 2         | 0.78%   |
| IceLake         | 2         | 0.78%   |
| Goldmont plus   | 2         | 0.78%   |
| Excavator       | 2         | 0.78%   |
| Bulldozer       | 2         | 0.78%   |
| Broadwell       | 2         | 0.78%   |
| Steamroller     | 1         | 0.39%   |
| P6              | 1         | 0.39%   |
| K8 & K10 hybrid | 1         | 0.39%   |
| Jaguar          | 1         | 0.39%   |
| Goldmont        | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 176       | 64.47%  |
| AMD                        | 47        | 17.22%  |
| Nvidia                     | 43        | 15.75%  |
| VIA Technologies           | 3         | 1.1%    |
| Zhaoxin                    | 2         | 0.73%   |
| Matrox Electronics Systems | 1         | 0.37%   |
| ASPEED Technology          | 1         | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 34        | 11.93%  |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 17        | 5.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 5.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 3.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 2.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 2.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.46%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 2.46%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 7         | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.75%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 5         | 1.75%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 4         | 1.4%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.4%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 1.4%    |
| Intel HD Graphics 620                                                                    | 4         | 1.4%    |
| Intel 82946GZ/GL Integrated Graphics Controller                                          | 4         | 1.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.4%    |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 1.05%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.05%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 3         | 1.05%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 3         | 1.05%   |
| Intel HD Graphics 630                                                                    | 3         | 1.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.05%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 2         | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.7%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.7%    |
| Nvidia G96C [GeForce 9500 GT]                                                            | 2         | 0.7%    |
| Nvidia G86 [GeForce 8500 GT]                                                             | 2         | 0.7%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 0.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.7%    |
| Intel HD Graphics 5500                                                                   | 2         | 0.7%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2         | 0.7%    |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.7%    |
| Intel 82865G Integrated Graphics Controller                                              | 2         | 0.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 163       | 63.42%  |
| 1 x AMD         | 42        | 16.34%  |
| 1 x Nvidia      | 35        | 13.62%  |
| Intel + Nvidia  | 5         | 1.95%   |
| 1 x VIA         | 3         | 1.17%   |
| 1 x Zhaoxin     | 2         | 0.78%   |
| Intel + AMD     | 2         | 0.78%   |
| AMD + Nvidia    | 2         | 0.78%   |
| 2 x AMD         | 1         | 0.39%   |
| Nvidia + ASPEED | 1         | 0.39%   |
| 1 x Matrox      | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 222       | 86.38%  |
| Proprietary | 20        | 7.78%   |
| Unknown     | 15        | 5.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 169       | 64.26%  |
| 0.01-0.5   | 38        | 14.45%  |
| 0.51-1.0   | 28        | 10.65%  |
| 1.01-2.0   | 21        | 7.98%   |
| 3.01-4.0   | 7         | 2.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung Electronics                   | 51        | 20.08%  |
| BOE                                   | 18        | 7.09%   |
| LG Display                            | 16        | 6.3%    |
| Hewlett-Packard                       | 16        | 6.3%    |
| AU Optronics                          | 16        | 6.3%    |
| Goldstar                              | 15        | 5.91%   |
| Lenovo                                | 13        | 5.12%   |
| Chimei Innolux                        | 12        | 4.72%   |
| Dell                                  | 10        | 3.94%   |
| Toshiba                               | 9         | 3.54%   |
| InfoVision                            | 9         | 3.54%   |
| Chi Mei Optoelectronics               | 7         | 2.76%   |
| AOC                                   | 7         | 2.76%   |
| Acer                                  | 7         | 2.76%   |
| LG Philips                            | 5         | 1.97%   |
| Vita                                  | 4         | 1.57%   |
| HannStar                              | 4         | 1.57%   |
| Apple                                 | 4         | 1.57%   |
| BenQ                                  | 3         | 1.18%   |
| ViewSonic                             | 2         | 0.79%   |
| Sony                                  | 2         | 0.79%   |
| PANDA                                 | 2         | 0.79%   |
| MStar                                 | 2         | 0.79%   |
| ITL                                   | 2         | 0.79%   |
| Envision                              | 2         | 0.79%   |
| Vizio                                 | 1         | 0.39%   |
| Unknown (XXX)                         | 1         | 0.39%   |
| Toshiba Matsushita Display Technology | 1         | 0.39%   |
| TCL                                   | 1         | 0.39%   |
| Sharp                                 | 1         | 0.39%   |
| Plain Tree Systems                    | 1         | 0.39%   |
| PEGA                                  | 1         | 0.39%   |
| Parker                                | 1         | 0.39%   |
| LSC                                   | 1         | 0.39%   |
| LG Electronics                        | 1         | 0.39%   |
| LED                                   | 1         | 0.39%   |
| KTC                                   | 1         | 0.39%   |
| InnoLux Display                       | 1         | 0.39%   |
| IBM                                   | 1         | 0.39%   |
| CVT                                   | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 6         | 2.33%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 6         | 2.33%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                   | 4         | 1.55%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 4         | 1.55%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch | 4         | 1.55%   |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                | 4         | 1.55%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch      | 4         | 1.55%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 3         | 1.16%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 3         | 1.16%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                 | 3         | 1.16%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch        | 3         | 1.16%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch    | 2         | 0.78%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch | 2         | 0.78%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2         | 0.78%   |
| Samsung Electronics S19A10N SAM083E 1366x768 410x230mm 18.5-inch     | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 2         | 0.78%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.78%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                       | 2         | 0.78%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 2         | 0.78%   |
| ITL MT-3185 ITL3185 1366x768 409x230mm 18.5-inch                     | 2         | 0.78%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 2         | 0.78%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 2         | 0.78%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2         | 0.78%   |
| Goldstar FHD GSM5BC9 1920x1080 480x270mm 21.7-inch                   | 2         | 0.78%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                 | 2         | 0.78%   |
| Apple Color LCD APP9CDD 1920x1080 475x267mm 21.5-inch                | 2         | 0.78%   |
| Vizio E322AR VIZ0079 1360x768 700x400mm 31.7-inch                    | 1         | 0.39%   |
| ViewSonic VA2448 SERIES VSC3828 1920x1080 521x293mm 23.5-inch        | 1         | 0.39%   |
| ViewSonic VA2252 SERIES VSC7731 1920x1080 476x268mm 21.5-inch        | 1         | 0.39%   |
| Unknown (XXX) 1772ED XXX1772 1280x1024 320x250mm 16.0-inch           | 1         | 0.39%   |
| Unknown (XXX) 1772E XXX1772 1280x1024 320x250mm 16.0-inch            | 1         | 0.39%   |
| Toshiba Matsushita Display Technology LCD Monitor LCD-MONITOR        | 1         | 0.39%   |
| TCL T-7005L TCL1770 1280x1024 338x270mm 17.0-inch                    | 1         | 0.39%   |
| Sony TV SNYEB01 1360x768                                             | 1         | 0.39%   |
| Sony TV SNYEA01 1920x1080                                            | 1         | 0.39%   |
| Sony TV SNYDC01 1360x768                                             | 1         | 0.39%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch              | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch  | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 92        | 37.4%   |
| 1920x1080 (FHD)    | 52        | 21.14%  |
| 1280x1024 (SXGA)   | 28        | 11.38%  |
| 1600x900 (HD+)     | 14        | 5.69%   |
| 1440x900 (WXGA+)   | 14        | 5.69%   |
| 1280x800 (WXGA)    | 12        | 4.88%   |
| 1360x768           | 7         | 2.85%   |
| 1680x1050 (WSXGA+) | 6         | 2.44%   |
| 3840x2160 (4K)     | 4         | 1.63%   |
| 1920x1200 (WUXGA)  | 3         | 1.22%   |
| 1280x720 (HD)      | 3         | 1.22%   |
| 1024x768 (XGA)     | 3         | 1.22%   |
| 1024x600           | 3         | 1.22%   |
| 2560x1440 (QHD)    | 2         | 0.81%   |
| Unknown            | 2         | 0.81%   |
| 3840x1080          | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 53        | 21.03%  |
| 18      | 32        | 12.7%   |
| 17      | 25        | 9.92%   |
| 14      | 24        | 9.52%   |
| 21      | 23        | 9.13%   |
| 13      | 21        | 8.33%   |
| 19      | 14        | 5.56%   |
| 10      | 10        | 3.97%   |
| Unknown | 9         | 3.57%   |
| 20      | 8         | 3.17%   |
| 23      | 6         | 2.38%   |
| 11      | 4         | 1.59%   |
| 74      | 3         | 1.19%   |
| 27      | 3         | 1.19%   |
| 22      | 3         | 1.19%   |
| 16      | 3         | 1.19%   |
| 72      | 2         | 0.79%   |
| 52      | 2         | 0.79%   |
| 24      | 2         | 0.79%   |
| 54      | 1         | 0.4%    |
| 39      | 1         | 0.4%    |
| 32      | 1         | 0.4%    |
| 31      | 1         | 0.4%    |
| 12      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 115       | 46.56%  |
| 401-500     | 71        | 28.74%  |
| 201-300     | 17        | 6.88%   |
| 351-400     | 13        | 5.26%   |
| 501-600     | 11        | 4.45%   |
| Unknown     | 9         | 3.64%   |
| 1501-2000   | 5         | 2.02%   |
| 1001-1500   | 3         | 1.21%   |
| 801-900     | 1         | 0.4%    |
| 701-800     | 1         | 0.4%    |
| 601-700     | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 156       | 66.95%  |
| 16/10   | 38        | 16.31%  |
| 5/4     | 26        | 11.16%  |
| Unknown | 7         | 3%      |
| 4/3     | 4         | 1.72%   |
| 3/2     | 2         | 0.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 21.12%  |
| 141-150        | 45        | 17.93%  |
| 81-90          | 43        | 17.13%  |
| 151-200        | 37        | 14.74%  |
| 201-250        | 23        | 9.16%   |
| 41-50          | 10        | 3.98%   |
| Unknown        | 9         | 3.59%   |
| More than 1000 | 8         | 3.19%   |
| 121-130        | 7         | 2.79%   |
| 51-60          | 4         | 1.59%   |
| 301-350        | 3         | 1.2%    |
| 351-500        | 2         | 0.8%    |
| 251-300        | 2         | 0.8%    |
| 71-80          | 1         | 0.4%    |
| 61-70          | 1         | 0.4%    |
| 131-140        | 1         | 0.4%    |
| 501-1000       | 1         | 0.4%    |
| 91-100         | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 112       | 44.98%  |
| 101-120       | 80        | 32.13%  |
| 121-160       | 35        | 14.06%  |
| 1-50          | 10        | 4.02%   |
| Unknown       | 9         | 3.61%   |
| 161-240       | 2         | 0.8%    |
| More than 240 | 1         | 0.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 216       | 83.72%  |
| 2     | 25        | 9.69%   |
| 0     | 14        | 5.43%   |
| 3     | 3         | 1.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 159       | 38.69%  |
| Qualcomm Atheros                  | 74        | 18%     |
| Intel                             | 69        | 16.79%  |
| Broadcom                          | 26        | 6.33%   |
| Nvidia                            | 14        | 3.41%   |
| Ralink                            | 12        | 2.92%   |
| Ralink Technology                 | 7         | 1.7%    |
| Xiaomi                            | 6         | 1.46%   |
| Qualcomm Atheros Communications   | 6         | 1.46%   |
| Broadcom Limited                  | 6         | 1.46%   |
| Marvell Technology Group          | 5         | 1.22%   |
| JMicron Technology                | 4         | 0.97%   |
| VIA Technologies                  | 3         | 0.73%   |
| Samsung Electronics               | 3         | 0.73%   |
| Trendchip Technologies            | 2         | 0.49%   |
| Sundance Technology Inc / IC Plus | 2         | 0.49%   |
| Mercucys                          | 2         | 0.49%   |
| D-Link System                     | 2         | 0.49%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.24%   |
| National Semiconductor            | 1         | 0.24%   |
| Motorola PCS                      | 1         | 0.24%   |
| Motorola BCS                      | 1         | 0.24%   |
| MediaTek                          | 1         | 0.24%   |
| ICS Advent                        | 1         | 0.24%   |
| Huawei Technologies               | 1         | 0.24%   |
| Digium                            | 1         | 0.24%   |
| AMD                               | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 93        | 20.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 31        | 6.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 14        | 3.03%   |
| Nvidia MCP61 Ethernet                                                          | 13        | 2.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 2.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 9         | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 9         | 1.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 8         | 1.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 7         | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 7         | 1.52%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 7         | 1.52%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 6         | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 1.3%    |
| Intel Wireless 7265                                                            | 6         | 1.3%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 0.87%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 4         | 0.87%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 4         | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4         | 0.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 4         | 0.87%   |
| Qualcomm Atheros AR9271 802.11n                                                | 4         | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 4         | 0.87%   |
| Intel Wireless 7260                                                            | 4         | 0.87%   |
| Intel Centrino Wireless-N 105                                                  | 4         | 0.87%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 4         | 0.87%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 4         | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.65%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 3         | 0.65%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 0.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 3         | 0.65%   |
| Ralink MT7601U Wireless Adapter                                                | 3         | 0.65%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3         | 0.65%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3         | 0.65%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3         | 0.65%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 55        | 27.92%  |
| Realtek Semiconductor           | 53        | 26.9%   |
| Intel                           | 41        | 20.81%  |
| Broadcom                        | 15        | 7.61%   |
| Ralink                          | 12        | 6.09%   |
| Ralink Technology               | 7         | 3.55%   |
| Qualcomm Atheros Communications | 6         | 3.05%   |
| Mercucys                        | 2         | 1.02%   |
| D-Link System                   | 2         | 1.02%   |
| Broadcom Limited                | 2         | 1.02%   |
| Xiaomi                          | 1         | 0.51%   |
| MediaTek                        | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 14        | 7.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 9         | 4.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 9         | 4.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 7         | 3.55%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 7         | 3.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 6         | 3.05%   |
| Intel Wireless 7265                                                            | 6         | 3.05%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 5         | 2.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 2.03%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 4         | 2.03%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 4         | 2.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4         | 2.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 4         | 2.03%   |
| Qualcomm Atheros AR9271 802.11n                                                | 4         | 2.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 4         | 2.03%   |
| Intel Wireless 7260                                                            | 4         | 2.03%   |
| Intel Centrino Wireless-N 105                                                  | 4         | 2.03%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 4         | 2.03%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 1.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 3         | 1.52%   |
| Ralink MT7601U Wireless Adapter                                                | 3         | 1.52%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 3         | 1.52%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 3         | 1.52%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 3         | 1.52%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 3         | 1.52%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 1.52%   |
| Intel Wi-Fi 6 AX201                                                            | 3         | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 1.52%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                              | 3         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.02%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 2         | 1.02%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                         | 2         | 1.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2         | 1.02%   |
| Realtek 802.11n WLAN Adapter                                                   | 2         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 1.02%   |
| Mercucys MW300UM RTL8192EU wifi                                                | 2         | 1.02%   |
| Intel Wireless 8260                                                            | 2         | 1.02%   |
| Intel Wireless 3165                                                            | 2         | 1.02%   |
| Intel WiFi Link 5100                                                           | 2         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 134       | 52.14%  |
| Intel                             | 38        | 14.79%  |
| Qualcomm Atheros                  | 27        | 10.51%  |
| Nvidia                            | 14        | 5.45%   |
| Broadcom                          | 12        | 4.67%   |
| Xiaomi                            | 5         | 1.95%   |
| Marvell Technology Group          | 5         | 1.95%   |
| JMicron Technology                | 4         | 1.56%   |
| Broadcom Limited                  | 4         | 1.56%   |
| VIA Technologies                  | 3         | 1.17%   |
| Samsung Electronics               | 3         | 1.17%   |
| Trendchip Technologies            | 2         | 0.78%   |
| Sundance Technology Inc / IC Plus | 2         | 0.78%   |
| National Semiconductor            | 1         | 0.39%   |
| Motorola PCS                      | 1         | 0.39%   |
| Motorola BCS                      | 1         | 0.39%   |
| ICS Advent                        | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 93        | 35.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 31        | 11.88%  |
| Nvidia MCP61 Ethernet                                                      | 13        | 4.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 11        | 4.21%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 8         | 3.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 7         | 2.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 6         | 2.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 5         | 1.92%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                      | 4         | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3         | 1.15%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3         | 1.15%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3         | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3         | 1.15%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                     | 3         | 1.15%   |
| Intel PRO/100 VE Network Connection                                        | 3         | 1.15%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 3         | 1.15%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2         | 0.77%   |
| Trendchip Ethernet controller                                              | 2         | 0.77%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 2         | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2         | 0.77%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 2         | 0.77%   |
| Intel Ethernet Connection I217-V                                           | 2         | 0.77%   |
| Intel Ethernet Connection I217-LM                                          | 2         | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                                      | 2         | 0.77%   |
| Intel 82574L Gigabit Network Connection                                    | 2         | 0.77%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2         | 0.77%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                | 2         | 0.77%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                      | 1         | 0.38%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1         | 0.38%   |
| Realtek Realtek Ethernet controller                                        | 1         | 0.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.38%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1         | 0.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                      | 1         | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1         | 0.38%   |
| Nvidia MCP77 Ethernet                                                      | 1         | 0.38%   |
| National DP83815 (MacPhyter) Ethernet Controller                           | 1         | 0.38%   |
| Motorola PCS moto g(9) play                                                | 1         | 0.38%   |
| Motorola BCS SurfBoard SB5100 Cable Modem                                  | 1         | 0.38%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                    | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 238       | 55.35%  |
| WiFi     | 188       | 43.72%  |
| Modem    | 3         | 0.7%    |
| Unknown  | 1         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 50.37%  |
| Ethernet | 133       | 49.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 149       | 57.53%  |
| 1     | 102       | 39.38%  |
| 3     | 4         | 1.54%   |
| 0     | 3         | 1.16%   |
| 4     | 1         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 256       | 99.61%  |
| Yes  | 1         | 0.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 30.23%  |
| IMC Networks                    | 12        | 13.95%  |
| Realtek Semiconductor           | 11        | 12.79%  |
| Qualcomm Atheros Communications | 11        | 12.79%  |
| Cambridge Silicon Radio         | 9         | 10.47%  |
| Broadcom                        | 6         | 6.98%   |
| Apple                           | 4         | 4.65%   |
| ASUSTek Computer                | 3         | 3.49%   |
| Lite-On Technology              | 2         | 2.33%   |
| Hewlett-Packard                 | 2         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 16        | 18.6%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 9         | 10.47%  |
| Realtek RTL8723B Bluetooth                                  | 7         | 8.14%   |
| Qualcomm Atheros  Bluetooth Device                          | 5         | 5.81%   |
| IMC Networks Bluetooth                                      | 4         | 4.65%   |
| Realtek Bluetooth Radio                                     | 3         | 3.49%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 3.49%   |
| Intel AX201 Bluetooth                                       | 3         | 3.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 3         | 3.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 3.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 2.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 2.33%   |
| Intel AX200 Bluetooth                                       | 2         | 2.33%   |
| IMC Networks Bluetooth Radio                                | 2         | 2.33%   |
| IMC Networks Bluetooth Module                               | 2         | 2.33%   |
| Broadcom BCM2045 Bluetooth                                  | 2         | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 1.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.16%   |
| Lite-On Bluetooth Device                                    | 1         | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.16%   |
| IMC Networks Wireless_Device                                | 1         | 1.16%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.16%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.16%   |
| Broadcom BCM2070 Bluetooth Device                           | 1         | 1.16%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.16%   |
| Broadcom BCM2035B3 Bluetooth Adapter                        | 1         | 1.16%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.16%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 1.16%   |
| ASUS Bluetooth Adapter                                      | 1         | 1.16%   |
| Apple Bluetooth HCI                                         | 1         | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 203       | 63.84%  |
| AMD                       | 48        | 15.09%  |
| Nvidia                    | 38        | 11.95%  |
| C-Media Electronics       | 6         | 1.89%   |
| VIA Technologies          | 4         | 1.26%   |
| Logitech                  | 3         | 0.94%   |
| Creative Labs             | 3         | 0.94%   |
| Zhaoxin                   | 2         | 0.63%   |
| Sennheiser Communications | 2         | 0.63%   |
| Microsoft                 | 2         | 0.63%   |
| JMTek                     | 2         | 0.63%   |
| Unknown                   | 1         | 0.31%   |
| Realtek Semiconductor     | 1         | 0.31%   |
| Megawin Technology        | 1         | 0.31%   |
| Generalplus Technology    | 1         | 0.31%   |
| Cirrus Logic              | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 43        | 11.98%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 39        | 10.86%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 26        | 7.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 3.62%   |
| Nvidia MCP61 High Definition Audio                                                                | 12        | 3.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 3.34%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 3.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.23%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 2.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 2.23%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.23%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 7         | 1.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.39%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 5         | 1.39%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.11%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.84%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.84%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.84%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.84%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.84%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 2         | 0.56%   |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                                         | 2         | 0.56%   |
| Sennheiser Communications SC230                                                                   | 2         | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.56%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.56%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.56%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.56%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 54        | 25.35%  |
| Samsung Electronics | 28        | 13.15%  |
| SK hynix            | 26        | 12.21%  |
| Ramaxel Technology  | 21        | 9.86%   |
| Kingston            | 20        | 9.39%   |
| Micron Technology   | 12        | 5.63%   |
| Crucial             | 9         | 4.23%   |
| Corsair             | 8         | 3.76%   |
| Elpida              | 6         | 2.82%   |
| Qimonda             | 3         | 1.41%   |
| Nanya Technology    | 3         | 1.41%   |
| A-DATA Technology   | 3         | 1.41%   |
| Unknown             | 3         | 1.41%   |
| Unknown (ABCD)      | 2         | 0.94%   |
| Unknown (0x07D5)    | 2         | 0.94%   |
| Team                | 2         | 0.94%   |
| Shenzhen WODPOSIT   | 2         | 0.94%   |
| Avant               | 2         | 0.94%   |
| Unknown (0x0CBA)    | 1         | 0.47%   |
| Unknown (081A)      | 1         | 0.47%   |
| PNY                 | 1         | 0.47%   |
| OCZ                 | 1         | 0.47%   |
| Memox               | 1         | 0.47%   |
| Kreton              | 1         | 0.47%   |
| Apacer              | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM 400MT/s                        | 3         | 1.28%   |
| Unknown RAM Module 2048MB DIMM DDR2                        | 3         | 1.28%   |
| Unknown RAM Module 1024MB DIMM DDR2                        | 3         | 1.28%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s     | 3         | 1.28%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s    | 3         | 1.28%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 3         | 1.28%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s    | 3         | 1.28%   |
| Ramaxel RAM RMT3010EC58E8F1333 2048MB SODIMM DDR3 1600MT/s | 3         | 1.28%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s    | 3         | 1.28%   |
| Unknown                                                    | 3         | 1.28%   |
| Unknown RAM Module 4GB DIMM SDRAM                          | 2         | 0.85%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 2         | 0.85%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                       | 2         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                | 2         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 2         | 0.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 2         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                  | 2         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR2                           | 2         | 0.85%   |
| Unknown RAM Module 2GB DIMM 400MT/s                        | 2         | 0.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 2         | 0.85%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 2         | 0.85%   |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 2         | 0.85%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                | 2         | 0.85%   |
| Unknown (0x07D5) RAM Module 4GB SODIMM DDR3 1333MT/s       | 2         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 2         | 0.85%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s      | 2         | 0.85%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                | 2         | 0.85%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s      | 2         | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 0.85%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s        | 2         | 0.85%   |
| Ramaxel RAM RMR5030ME68F9F1600 4GB DIMM DDR3 1600MT/s      | 2         | 0.85%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s      | 2         | 0.85%   |
| Ramaxel RAM Module 4GB SODIMM DDR3 1333MT/s                | 2         | 0.85%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s         | 2         | 0.85%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s     | 2         | 0.85%   |
| Kingston RAM Module 4GB SODIMM DDR3 1333MT/s               | 2         | 0.85%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s      | 2         | 0.85%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 0.43%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                       | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 69        | 41.32%  |
| DDR2    | 34        | 20.36%  |
| DDR4    | 29        | 17.37%  |
| SDRAM   | 16        | 9.58%   |
| Unknown | 11        | 6.59%   |
| DDR     | 5         | 2.99%   |
| LPDDR4  | 3         | 1.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 83        | 51.55%  |
| SODIMM       | 76        | 47.2%   |
| Row Of Chips | 2         | 1.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 67        | 35.08%  |
| 4096  | 56        | 29.32%  |
| 8192  | 36        | 18.85%  |
| 1024  | 22        | 11.52%  |
| 16384 | 7         | 3.66%   |
| 512   | 2         | 1.05%   |
| 32768 | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 46        | 24.73%  |
| 1333    | 25        | 13.44%  |
| Unknown | 19        | 10.22%  |
| 2667    | 11        | 5.91%   |
| 667     | 11        | 5.91%   |
| 3200    | 8         | 4.3%    |
| 2400    | 8         | 4.3%    |
| 800     | 8         | 4.3%    |
| 1066    | 7         | 3.76%   |
| 533     | 7         | 3.76%   |
| 400     | 5         | 2.69%   |
| 2048    | 4         | 2.15%   |
| 1334    | 4         | 2.15%   |
| 1639    | 3         | 1.61%   |
| 1067    | 3         | 1.61%   |
| 133     | 3         | 1.61%   |
| 4199    | 2         | 1.08%   |
| 2666    | 2         | 1.08%   |
| 2133    | 2         | 1.08%   |
| 1867    | 2         | 1.08%   |
| 3733    | 1         | 0.54%   |
| 3600    | 1         | 0.54%   |
| 3266    | 1         | 0.54%   |
| 3000    | 1         | 0.54%   |
| 1024    | 1         | 0.54%   |
| 975     | 1         | 0.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 60%     |
| Seiko Epson         | 2         | 20%     |
| Samsung Electronics | 2         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 10%     |
| Seiko Epson L210 Series                      | 1         | 10%     |
| Samsung ML-216x Series Laser Printer         | 1         | 10%     |
| Samsung ML-1865                              | 1         | 10%     |
| HP LaserJet Professional P1102w              | 1         | 10%     |
| HP LaserJet P1006                            | 1         | 10%     |
| HP LaserJet P1005                            | 1         | 10%     |
| HP LaserJet 1018                             | 1         | 10%     |
| HP DeskJet 2300 series                       | 1         | 10%     |
| HP Color LaserJet CP1215                     | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP Scanjet 200          | 1         | 50%     |
| Canon CanoScan LiDE 110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 22.69%  |
| Microdia                               | 13        | 10.92%  |
| Acer                                   | 11        | 9.24%   |
| Realtek Semiconductor                  | 10        | 8.4%    |
| IMC Networks                           | 9         | 7.56%   |
| Suyin                                  | 7         | 5.88%   |
| Logitech                               | 5         | 4.2%    |
| Apple                                  | 5         | 4.2%    |
| Ricoh                                  | 3         | 2.52%   |
| Quanta                                 | 3         | 2.52%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.52%   |
| Syntek                                 | 2         | 1.68%   |
| Sunplus Innovation Technology          | 2         | 1.68%   |
| Samsung Electronics                    | 2         | 1.68%   |
| Microsoft                              | 2         | 1.68%   |
| Lite-On Technology                     | 2         | 1.68%   |
| KYE Systems (Mouse Systems)            | 2         | 1.68%   |
| ALi                                    | 2         | 1.68%   |
| USB Camera                             | 1         | 0.84%   |
| Tobii Technology AB                    | 1         | 0.84%   |
| Sonix Technology                       | 1         | 0.84%   |
| SiGma Micro                            | 1         | 0.84%   |
| Luxvisions Innotech Limited            | 1         | 0.84%   |
| LG Electronics                         | 1         | 0.84%   |
| Lenovo                                 | 1         | 0.84%   |
| Importek                               | 1         | 0.84%   |
| Aveo Technology                        | 1         | 0.84%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                        | 10        | 8.4%    |
| Realtek Integrated_Webcam_HD                                  | 5         | 4.2%    |
| Microdia USB 2.0 Camera                                       | 4         | 3.36%   |
| Chicony Lenovo EasyCamera                                     | 4         | 3.36%   |
| Acer USB Camera                                               | 4         | 3.36%   |
| Logitech Webcam C270                                          | 3         | 2.52%   |
| Chicony HD Webcam                                             | 3         | 2.52%   |
| Apple Built-in iSight                                         | 3         | 2.52%   |
| Suyin Webcam-101                                              | 2         | 1.68%   |
| Samsung Galaxy A5 (MTP)                                       | 2         | 1.68%   |
| Ricoh Laptop_Integrated_Webcam_FHD                            | 2         | 1.68%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 1.68%   |
| Microdia Integrated_Webcam_1.3M                               | 2         | 1.68%   |
| IMC Networks XHC Camera                                       | 2         | 1.68%   |
| IMC Networks Lenovo EasyCamera                                | 2         | 1.68%   |
| Chicony Integrated Camera                                     | 2         | 1.68%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 2         | 1.68%   |
| Acer Lenovo EasyCamera                                        | 2         | 1.68%   |
| Acer HD Webcam                                                | 2         | 1.68%   |
| USB Camera USB Camera                                         | 1         | 0.84%   |
| Tobii AB EyeChip                                              | 1         | 0.84%   |
| Syntek USB Camera Device                                      | 1         | 0.84%   |
| Syntek Integrated Webcam                                      | 1         | 0.84%   |
| Suyin Lenovo EasyCamera                                       | 1         | 0.84%   |
| Suyin Integrated_Webcam_HD                                    | 1         | 0.84%   |
| Suyin HP Webcam                                               | 1         | 0.84%   |
| Suyin HD Video WebCam                                         | 1         | 0.84%   |
| Suyin Acer CrystalEye Webcam                                  | 1         | 0.84%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 0.84%   |
| Sunplus HD WebCam                                             | 1         | 0.84%   |
| Sonix USB2.0 HD UVC WebCam                                    | 1         | 0.84%   |
| SiGma Micro WebCam SiGma Micro                                | 1         | 0.84%   |
| Ricoh Sony Vaio Integrated Webcam                             | 1         | 0.84%   |
| Realtek USB2.0 camera                                         | 1         | 0.84%   |
| Realtek USB Camera                                            | 1         | 0.84%   |
| Realtek Integrated Webcam                                     | 1         | 0.84%   |
| Realtek HP 1.0MP High Definition Webcam                       | 1         | 0.84%   |
| Realtek EasyCamera                                            | 1         | 0.84%   |
| Quanta VGA WebCam                                             | 1         | 0.84%   |
| Quanta HP Webcam                                              | 1         | 0.84%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 63.64%  |
| AuthenTec                  | 2         | 18.18%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| Futronic Technology        | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 3         | 27.27%  |
| Validity Sensors VFS495 Fingerprint Reader  | 2         | 18.18%  |
| AuthenTec AES2501 Fingerprint Sensor        | 2         | 18.18%  |
| Validity Sensors VFS471 Fingerprint Reader  | 1         | 9.09%   |
| Validity Sensors Fingerprint scanner        | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader          | 1         | 9.09%   |
| Futronic Fingerprint Scanner Model FS88     | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 80%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 2         | 40%     |
| Broadcom 5880                                  | 2         | 40%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 205       | 79.15%  |
| 1     | 46        | 17.76%  |
| 2     | 7         | 2.7%    |
| 4     | 1         | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 22        | 34.38%  |
| Fingerprint reader       | 11        | 17.19%  |
| Communication controller | 11        | 17.19%  |
| Sound                    | 5         | 7.81%   |
| Net/wireless             | 5         | 7.81%   |
| Chipcard                 | 5         | 7.81%   |
| Camera                   | 2         | 3.13%   |
| Storage                  | 1         | 1.56%   |
| Network                  | 1         | 1.56%   |
| Multimedia controller    | 1         | 1.56%   |

