Linux in Hong Kong - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Hong Kong.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Hong_Kong/Desktop/README.md) and [notebooks](/Location/Hong_Kong/Notebook/README.md).

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

Total: 727

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [7cbebba117](https://linux-hardware.org/?probe=7cbebba117) | Feb 02, 2024 |
| ASRock        | X300-ITX                    | Desktop     | [3390b15018](https://linux-hardware.org/?probe=3390b15018) | Feb 02, 2024 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [910fba93b8](https://linux-hardware.org/?probe=910fba93b8) | Feb 01, 2024 |
| AMI           | Intel                       | Notebook    | [6d3ac84f15](https://linux-hardware.org/?probe=6d3ac84f15) | Feb 01, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [531a090457](https://linux-hardware.org/?probe=531a090457) | Feb 01, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [33490eaaf1](https://linux-hardware.org/?probe=33490eaaf1) | Jan 31, 2024 |
| HP            | 8B3C A                      | Desktop     | [12ec418267](https://linux-hardware.org/?probe=12ec418267) | Jan 31, 2024 |
| MECHREVO      | WUJIE14 PRO                 | Notebook    | [a3b9804ccf](https://linux-hardware.org/?probe=a3b9804ccf) | Jan 30, 2024 |
| AZW           | GTR V21                     | Mini pc     | [904e422f26](https://linux-hardware.org/?probe=904e422f26) | Jan 29, 2024 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [c0d98503dd](https://linux-hardware.org/?probe=c0d98503dd) | Jan 29, 2024 |
| Unknown       | Phicomm N1                  | Soc         | [96a0dce3c6](https://linux-hardware.org/?probe=96a0dce3c6) | Jan 28, 2024 |
| HP            | 84EE 1100                   | All in one  | [eed1f038fe](https://linux-hardware.org/?probe=eed1f038fe) | Jan 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [2bf1eac05d](https://linux-hardware.org/?probe=2bf1eac05d) | Jan 27, 2024 |
| Apple         | Mac-F22C86C8                | Mini pc     | [7434ec9fa6](https://linux-hardware.org/?probe=7434ec9fa6) | Jan 25, 2024 |
| Apple         | Mac-F22C86C8                | Mini pc     | [78d29adc26](https://linux-hardware.org/?probe=78d29adc26) | Jan 25, 2024 |
| ASRock        | B650M PG Riptide            | Desktop     | [1ebf8a3fea](https://linux-hardware.org/?probe=1ebf8a3fea) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [53b28fea12](https://linux-hardware.org/?probe=53b28fea12) | Jan 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [413fbae0c9](https://linux-hardware.org/?probe=413fbae0c9) | Jan 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [69d393fc55](https://linux-hardware.org/?probe=69d393fc55) | Jan 17, 2024 |
| Lenovo        | ZHAOYANG K4e-IIL 81Y2       | Notebook    | [a318e3a69e](https://linux-hardware.org/?probe=a318e3a69e) | Jan 17, 2024 |
| Notebook      | P15SM-A/SM1-A               | Notebook    | [bc817396a6](https://linux-hardware.org/?probe=bc817396a6) | Jan 16, 2024 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [f0466fefa4](https://linux-hardware.org/?probe=f0466fefa4) | Jan 15, 2024 |
| AZW           | GTR V21                     | Desktop     | [c87cc08a52](https://linux-hardware.org/?probe=c87cc08a52) | Jan 15, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [23ad168a68](https://linux-hardware.org/?probe=23ad168a68) | Jan 14, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [30679c3606](https://linux-hardware.org/?probe=30679c3606) | Jan 11, 2024 |
| Gigabyte      | G41M-Combo                  | Desktop     | [e34d332260](https://linux-hardware.org/?probe=e34d332260) | Jan 10, 2024 |
| Lenovo        | ThinkPad L380 Yoga 20M7C... | Convertible | [bedd5d29e3](https://linux-hardware.org/?probe=bedd5d29e3) | Jan 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [a16f0bdbca](https://linux-hardware.org/?probe=a16f0bdbca) | Jan 08, 2024 |
| Fujitsu       | UH-X                        | Notebook    | [fae98e772d](https://linux-hardware.org/?probe=fae98e772d) | Jan 04, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [8213f6a90c](https://linux-hardware.org/?probe=8213f6a90c) | Jan 04, 2024 |
| Dell          | 0VNM11 A00                  | Desktop     | [060cdd6c04](https://linux-hardware.org/?probe=060cdd6c04) | Jan 04, 2024 |
| KUU           | Andes II                    | Notebook    | [bda39c51cd](https://linux-hardware.org/?probe=bda39c51cd) | Jan 03, 2024 |
| Unknown       | Unknown                     | Notebook    | [6133ac662c](https://linux-hardware.org/?probe=6133ac662c) | Jan 03, 2024 |
| Unknown       | Unknown                     | Notebook    | [6519663043](https://linux-hardware.org/?probe=6519663043) | Jan 02, 2024 |
| Notebook      | P15SM-A/SM1-A               | Notebook    | [ed3bd04f1a](https://linux-hardware.org/?probe=ed3bd04f1a) | Jan 02, 2024 |
| Notebook      | N13xWU                      | Notebook    | [b88a27e565](https://linux-hardware.org/?probe=b88a27e565) | Jan 02, 2024 |
| Lenovo        | ThinkPad L380 Yoga 20M7C... | Convertible | [fa3f52294e](https://linux-hardware.org/?probe=fa3f52294e) | Jan 02, 2024 |
| Google        | Caroline                    | Notebook    | [8b3ec77c48](https://linux-hardware.org/?probe=8b3ec77c48) | Jan 02, 2024 |
| Google        | Caroline                    | Notebook    | [95fb0e423e](https://linux-hardware.org/?probe=95fb0e423e) | Jan 01, 2024 |
| Notebook      | N13xWU                      | Notebook    | [d877ecb7be](https://linux-hardware.org/?probe=d877ecb7be) | Jan 01, 2024 |
| Lenovo        | ThinkPad L380 Yoga 20M7C... | Convertible | [7e61024957](https://linux-hardware.org/?probe=7e61024957) | Jan 01, 2024 |
| Google        | Caroline                    | Notebook    | [94a1dd78ec](https://linux-hardware.org/?probe=94a1dd78ec) | Dec 31, 2023 |
| Google        | Caroline                    | Notebook    | [0d1ce09fbd](https://linux-hardware.org/?probe=0d1ce09fbd) | Dec 31, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0c20bdae04](https://linux-hardware.org/?probe=0c20bdae04) | Dec 31, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d6622a2c0a](https://linux-hardware.org/?probe=d6622a2c0a) | Dec 31, 2023 |
| Unknown       | Unknown                     | Notebook    | [e67f78cf16](https://linux-hardware.org/?probe=e67f78cf16) | Dec 30, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [0daa9bd3eb](https://linux-hardware.org/?probe=0daa9bd3eb) | Dec 29, 2023 |
| Alienware     | x17 R2                      | Notebook    | [b439c4c2a9](https://linux-hardware.org/?probe=b439c4c2a9) | Dec 29, 2023 |
| Chuwi         | MiniBook X                  | Notebook    | [6249e8f644](https://linux-hardware.org/?probe=6249e8f644) | Dec 27, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [dbb5cde105](https://linux-hardware.org/?probe=dbb5cde105) | Dec 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [edc0cbda53](https://linux-hardware.org/?probe=edc0cbda53) | Dec 25, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a0c82919c0](https://linux-hardware.org/?probe=a0c82919c0) | Dec 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [a013d585d9](https://linux-hardware.org/?probe=a013d585d9) | Dec 24, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [2b580a7725](https://linux-hardware.org/?probe=2b580a7725) | Dec 21, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [adb83b1dca](https://linux-hardware.org/?probe=adb83b1dca) | Dec 20, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [4d8fbbd6d0](https://linux-hardware.org/?probe=4d8fbbd6d0) | Dec 19, 2023 |
| Dell          | 0PJDGF A02                  | Desktop     | [cfdd125cd5](https://linux-hardware.org/?probe=cfdd125cd5) | Dec 19, 2023 |
| Dell          | 0PJDGF A02                  | Desktop     | [edcd06b95f](https://linux-hardware.org/?probe=edcd06b95f) | Dec 19, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [c6fa46e494](https://linux-hardware.org/?probe=c6fa46e494) | Dec 17, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [d1d3bc7a1c](https://linux-hardware.org/?probe=d1d3bc7a1c) | Dec 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [071d7464d1](https://linux-hardware.org/?probe=071d7464d1) | Dec 15, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [ebfb65701f](https://linux-hardware.org/?probe=ebfb65701f) | Dec 14, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [ab468a9a14](https://linux-hardware.org/?probe=ab468a9a14) | Dec 13, 2023 |
| Huanan        | X99-TF                      | Desktop     | [2bf94ff272](https://linux-hardware.org/?probe=2bf94ff272) | Dec 13, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [c4de324273](https://linux-hardware.org/?probe=c4de324273) | Dec 12, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [df2900565f](https://linux-hardware.org/?probe=df2900565f) | Dec 12, 2023 |
| ONE-NETBOO... | ONEXPLAYER F1               | Tablet      | [158658e952](https://linux-hardware.org/?probe=158658e952) | Dec 08, 2023 |
| ONE-NETBOO... | ONEXPLAYER F1               | Tablet      | [3539ea142d](https://linux-hardware.org/?probe=3539ea142d) | Dec 08, 2023 |
| ONE-NETBOO... | ONEXPLAYER Mini Pro         | Tablet      | [8fa27cc61f](https://linux-hardware.org/?probe=8fa27cc61f) | Dec 06, 2023 |
| ONE-NETBOO... | ONEXPLAYER Mini Pro         | Tablet      | [4ca7e9fcaf](https://linux-hardware.org/?probe=4ca7e9fcaf) | Dec 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6e7c9a6ebc](https://linux-hardware.org/?probe=6e7c9a6ebc) | Dec 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [71c469e9dd](https://linux-hardware.org/?probe=71c469e9dd) | Dec 05, 2023 |
| Lenovo        | ThinkPad X230 23066RC       | Notebook    | [ef45ef93ac](https://linux-hardware.org/?probe=ef45ef93ac) | Dec 05, 2023 |
| Unknown       | Unknown                     | Notebook    | [a74febcadd](https://linux-hardware.org/?probe=a74febcadd) | Dec 04, 2023 |
| Huanan        | X99-TF                      | Desktop     | [c617461c74](https://linux-hardware.org/?probe=c617461c74) | Dec 03, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [940148ec06](https://linux-hardware.org/?probe=940148ec06) | Dec 01, 2023 |
| Intel         | SKYBAY                      | Desktop     | [f802b552c5](https://linux-hardware.org/?probe=f802b552c5) | Nov 29, 2023 |
| Intel         | SKYBAY                      | Desktop     | [914eab8268](https://linux-hardware.org/?probe=914eab8268) | Nov 28, 2023 |
| Intel         | SKYBAY                      | Desktop     | [3e3de1a647](https://linux-hardware.org/?probe=3e3de1a647) | Nov 27, 2023 |
| Intel         | SKYBAY                      | Desktop     | [9d55b4f75f](https://linux-hardware.org/?probe=9d55b4f75f) | Nov 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [3ccba31903](https://linux-hardware.org/?probe=3ccba31903) | Nov 27, 2023 |
| Intel         | SKYBAY                      | Desktop     | [21f1b67acc](https://linux-hardware.org/?probe=21f1b67acc) | Nov 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [47bf46db9d](https://linux-hardware.org/?probe=47bf46db9d) | Nov 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [e62a5fc1bc](https://linux-hardware.org/?probe=e62a5fc1bc) | Nov 24, 2023 |
| Intel         | SKYBAY                      | Desktop     | [03d84cbd00](https://linux-hardware.org/?probe=03d84cbd00) | Nov 24, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [a749e7b6c5](https://linux-hardware.org/?probe=a749e7b6c5) | Nov 23, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [bdbde84396](https://linux-hardware.org/?probe=bdbde84396) | Nov 18, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [47870e4c12](https://linux-hardware.org/?probe=47870e4c12) | Nov 13, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [7461a3b207](https://linux-hardware.org/?probe=7461a3b207) | Nov 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [5c2d84d61d](https://linux-hardware.org/?probe=5c2d84d61d) | Nov 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [e84ce1e0d3](https://linux-hardware.org/?probe=e84ce1e0d3) | Nov 06, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [37aa104ebf](https://linux-hardware.org/?probe=37aa104ebf) | Nov 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [f90d872043](https://linux-hardware.org/?probe=f90d872043) | Nov 05, 2023 |
| Intel         | X79 V1.0                    | Desktop     | [9483a097a1](https://linux-hardware.org/?probe=9483a097a1) | Nov 03, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [b2c5bb3ed9](https://linux-hardware.org/?probe=b2c5bb3ed9) | Nov 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [650d69cdce](https://linux-hardware.org/?probe=650d69cdce) | Oct 31, 2023 |
| Lenovo        | G770 20089                  | Notebook    | [8428ba05f5](https://linux-hardware.org/?probe=8428ba05f5) | Oct 28, 2023 |
| Orange Pi     | 5 Plus                      | Soc         | [45f5ee6292](https://linux-hardware.org/?probe=45f5ee6292) | Oct 28, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [6e87d140be](https://linux-hardware.org/?probe=6e87d140be) | Oct 25, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [6a3e8e996e](https://linux-hardware.org/?probe=6a3e8e996e) | Oct 20, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [23f0d88b97](https://linux-hardware.org/?probe=23f0d88b97) | Oct 20, 2023 |
| MECHREVO      | WUJIE14 PRO                 | Notebook    | [40cfeec2b2](https://linux-hardware.org/?probe=40cfeec2b2) | Oct 15, 2023 |
| MECHREVO      | WUJIE14 PRO                 | Notebook    | [422e2e497a](https://linux-hardware.org/?probe=422e2e497a) | Oct 15, 2023 |
| Lenovo        | G770 20089                  | Notebook    | [b8d4374337](https://linux-hardware.org/?probe=b8d4374337) | Oct 14, 2023 |
| Lenovo        | G770 20089                  | Notebook    | [eefc449148](https://linux-hardware.org/?probe=eefc449148) | Oct 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [41ca042a36](https://linux-hardware.org/?probe=41ca042a36) | Oct 14, 2023 |
| ASUSTek       | ROG Strix G732LWS_G732LW... | Notebook    | [cc1f103b33](https://linux-hardware.org/?probe=cc1f103b33) | Oct 12, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [ae56dcb316](https://linux-hardware.org/?probe=ae56dcb316) | Oct 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [3f4a876b18](https://linux-hardware.org/?probe=3f4a876b18) | Oct 08, 2023 |
| Gigabyte      | B150M-HD3-CF                | Desktop     | [6f431b83bd](https://linux-hardware.org/?probe=6f431b83bd) | Oct 08, 2023 |
| Gigabyte      | B150M-HD3-CF                | Desktop     | [e524ccbf1b](https://linux-hardware.org/?probe=e524ccbf1b) | Oct 07, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a716f2a182](https://linux-hardware.org/?probe=a716f2a182) | Oct 06, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [ca79f8ce4c](https://linux-hardware.org/?probe=ca79f8ce4c) | Oct 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [54eaf1a92d](https://linux-hardware.org/?probe=54eaf1a92d) | Oct 04, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [f4f3555c2b](https://linux-hardware.org/?probe=f4f3555c2b) | Oct 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [b3a1f027db](https://linux-hardware.org/?probe=b3a1f027db) | Oct 03, 2023 |
| Toshiba       | PORTEGE R830                | Notebook    | [beaf871c4c](https://linux-hardware.org/?probe=beaf871c4c) | Oct 01, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [9b86a89bf4](https://linux-hardware.org/?probe=9b86a89bf4) | Sep 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [539887ee9a](https://linux-hardware.org/?probe=539887ee9a) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [08989d4bba](https://linux-hardware.org/?probe=08989d4bba) | Sep 21, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [6d0e6a863d](https://linux-hardware.org/?probe=6d0e6a863d) | Sep 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [07d34fd9b5](https://linux-hardware.org/?probe=07d34fd9b5) | Sep 18, 2023 |
| Gigabyte      | H55N-USB3                   | Desktop     | [afefe4b055](https://linux-hardware.org/?probe=afefe4b055) | Sep 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [5e399c56a0](https://linux-hardware.org/?probe=5e399c56a0) | Sep 16, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [fda84a9c7c](https://linux-hardware.org/?probe=fda84a9c7c) | Sep 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [526a6826ab](https://linux-hardware.org/?probe=526a6826ab) | Sep 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [062f19958d](https://linux-hardware.org/?probe=062f19958d) | Sep 01, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [2e74e88e2f](https://linux-hardware.org/?probe=2e74e88e2f) | Aug 31, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [f253067fa5](https://linux-hardware.org/?probe=f253067fa5) | Aug 30, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [baf0966633](https://linux-hardware.org/?probe=baf0966633) | Aug 29, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [ca90d2134f](https://linux-hardware.org/?probe=ca90d2134f) | Aug 26, 2023 |
| Lenovo        | ThinkPad P51 20HJS5WH0D     | Notebook    | [ae8a51b2f5](https://linux-hardware.org/?probe=ae8a51b2f5) | Aug 21, 2023 |
| Dell          | 0VNM11 A00                  | Desktop     | [e448e177d3](https://linux-hardware.org/?probe=e448e177d3) | Aug 21, 2023 |
| FriendlyEl... | NanoPi R2S                  | Soc         | [e8ae8c047f](https://linux-hardware.org/?probe=e8ae8c047f) | Aug 20, 2023 |
| FriendlyEl... | NanoPi R2S                  | Soc         | [992f8472ce](https://linux-hardware.org/?probe=992f8472ce) | Aug 20, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [4c589a0320](https://linux-hardware.org/?probe=4c589a0320) | Aug 18, 2023 |
| MeLE          | Rev GMLR1                   | Mini pc     | [eba93bad6a](https://linux-hardware.org/?probe=eba93bad6a) | Aug 17, 2023 |
| ASRock        | Q1900-ITX                   | Desktop     | [2c60ec2f95](https://linux-hardware.org/?probe=2c60ec2f95) | Aug 17, 2023 |
| Unknown       | Unknown                     | Tablet      | [a087e3a82c](https://linux-hardware.org/?probe=a087e3a82c) | Aug 16, 2023 |
| ASRock        | Q1900-ITX                   | Desktop     | [b4a64727f4](https://linux-hardware.org/?probe=b4a64727f4) | Aug 14, 2023 |
| Dell          | 0VNM11 A00                  | Desktop     | [71cd1ddbf5](https://linux-hardware.org/?probe=71cd1ddbf5) | Aug 13, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [cf233e5568](https://linux-hardware.org/?probe=cf233e5568) | Aug 13, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [88a9c5764d](https://linux-hardware.org/?probe=88a9c5764d) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [c90f282238](https://linux-hardware.org/?probe=c90f282238) | Aug 11, 2023 |
| Fujitsu       | UH-X                        | Notebook    | [e26b430aef](https://linux-hardware.org/?probe=e26b430aef) | Aug 09, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [a089f6ff62](https://linux-hardware.org/?probe=a089f6ff62) | Aug 05, 2023 |
| LG Electro... | 16Z90R-K.ADB9U1             | Notebook    | [d3a9e05559](https://linux-hardware.org/?probe=d3a9e05559) | Aug 02, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [dd11fc89fe](https://linux-hardware.org/?probe=dd11fc89fe) | Aug 02, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [eb332b024d](https://linux-hardware.org/?probe=eb332b024d) | Jul 30, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [e43da17360](https://linux-hardware.org/?probe=e43da17360) | Jul 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [e8368bcae8](https://linux-hardware.org/?probe=e8368bcae8) | Jul 28, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [0552cb3e44](https://linux-hardware.org/?probe=0552cb3e44) | Jul 26, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [8c8e7f5edd](https://linux-hardware.org/?probe=8c8e7f5edd) | Jul 26, 2023 |
| Lenovo        | Legion R9000X 2021 82HN     | Notebook    | [0079a4e7a0](https://linux-hardware.org/?probe=0079a4e7a0) | Jul 25, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [e14cb2c24e](https://linux-hardware.org/?probe=e14cb2c24e) | Jul 25, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [bddace9995](https://linux-hardware.org/?probe=bddace9995) | Jul 25, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [edfa5090fc](https://linux-hardware.org/?probe=edfa5090fc) | Jul 21, 2023 |
| Dell          | 0WXD1Y A01                  | Server      | [477343a949](https://linux-hardware.org/?probe=477343a949) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c5475d0982](https://linux-hardware.org/?probe=c5475d0982) | Jul 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [9430a42f8b](https://linux-hardware.org/?probe=9430a42f8b) | Jul 13, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [9bee6805c0](https://linux-hardware.org/?probe=9bee6805c0) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b89cab90c0](https://linux-hardware.org/?probe=b89cab90c0) | Jul 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [ee5ef8132f](https://linux-hardware.org/?probe=ee5ef8132f) | Jul 09, 2023 |
| Lenovo        | Legion R9000X ARHA7 82UG    | Notebook    | [5da53d3f61](https://linux-hardware.org/?probe=5da53d3f61) | Jul 09, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [c060069870](https://linux-hardware.org/?probe=c060069870) | Jul 07, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [5b085b711b](https://linux-hardware.org/?probe=5b085b711b) | Jul 06, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | Desktop     | [8a5ddbbafc](https://linux-hardware.org/?probe=8a5ddbbafc) | Jul 05, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a57586f69b](https://linux-hardware.org/?probe=a57586f69b) | Jul 01, 2023 |
| Google        | Nami                        | Notebook    | [6ffc403580](https://linux-hardware.org/?probe=6ffc403580) | Jun 29, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [3f9d0da410](https://linux-hardware.org/?probe=3f9d0da410) | Jun 28, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [928f167dee](https://linux-hardware.org/?probe=928f167dee) | Jun 22, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [016268562d](https://linux-hardware.org/?probe=016268562d) | Jun 21, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [25bc3b1533](https://linux-hardware.org/?probe=25bc3b1533) | Jun 21, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [6a63f44627](https://linux-hardware.org/?probe=6a63f44627) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [8a9a60ca4d](https://linux-hardware.org/?probe=8a9a60ca4d) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [eaca61c801](https://linux-hardware.org/?probe=eaca61c801) | Jun 19, 2023 |
| Lenovo        | ThinkPad E480 20KNA047CD    | Notebook    | [918de7de03](https://linux-hardware.org/?probe=918de7de03) | Jun 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [bd74568d10](https://linux-hardware.org/?probe=bd74568d10) | Jun 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c536181b6a](https://linux-hardware.org/?probe=c536181b6a) | Jun 14, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [a67c1e25b2](https://linux-hardware.org/?probe=a67c1e25b2) | Jun 11, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [604f40e700](https://linux-hardware.org/?probe=604f40e700) | Jun 09, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d001c4cf1c](https://linux-hardware.org/?probe=d001c4cf1c) | Jun 09, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [25c1d47331](https://linux-hardware.org/?probe=25c1d47331) | Jun 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [b7f109f62e](https://linux-hardware.org/?probe=b7f109f62e) | Jun 08, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [8d783c6b00](https://linux-hardware.org/?probe=8d783c6b00) | Jun 03, 2023 |
| HP            | 83E2                        | Desktop     | [eaf5f90360](https://linux-hardware.org/?probe=eaf5f90360) | Jun 01, 2023 |
| GPD           | G1619-04                    | Notebook    | [49b9e4edd3](https://linux-hardware.org/?probe=49b9e4edd3) | May 28, 2023 |
| GPD           | G1619-04                    | Notebook    | [caa6b5459d](https://linux-hardware.org/?probe=caa6b5459d) | May 28, 2023 |
| HP            | 1632                        | Desktop     | [ed47689eec](https://linux-hardware.org/?probe=ed47689eec) | May 22, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [b25115a01a](https://linux-hardware.org/?probe=b25115a01a) | May 19, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [2bfe226026](https://linux-hardware.org/?probe=2bfe226026) | May 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [c2ccca0208](https://linux-hardware.org/?probe=c2ccca0208) | May 16, 2023 |
| Dell          | 0WXD1Y A01                  | Server      | [9d5a4b579e](https://linux-hardware.org/?probe=9d5a4b579e) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | Notebook    | [cacfc4dacd](https://linux-hardware.org/?probe=cacfc4dacd) | May 16, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [df455b6f4b](https://linux-hardware.org/?probe=df455b6f4b) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b9cfd37540](https://linux-hardware.org/?probe=b9cfd37540) | May 05, 2023 |
| Fujitsu       | FMVNU6G1C                   | Notebook    | [969957b527](https://linux-hardware.org/?probe=969957b527) | Apr 29, 2023 |
| Samsung       | 950QED                      | Convertible | [0135cc3aa4](https://linux-hardware.org/?probe=0135cc3aa4) | Apr 27, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VV_GZ3... | Tablet      | [679dc6cbc8](https://linux-hardware.org/?probe=679dc6cbc8) | Apr 25, 2023 |
| Dell          | 0N0992 A01                  | Desktop     | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [65cce76dc9](https://linux-hardware.org/?probe=65cce76dc9) | Apr 20, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [59f6a81039](https://linux-hardware.org/?probe=59f6a81039) | Apr 17, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [9feb6e0d59](https://linux-hardware.org/?probe=9feb6e0d59) | Apr 16, 2023 |
| Lenovo        | ThinkPad X201 33233QM       | Notebook    | [f84da542f6](https://linux-hardware.org/?probe=f84da542f6) | Apr 15, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [0e074bebcf](https://linux-hardware.org/?probe=0e074bebcf) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [9d3c5ea28d](https://linux-hardware.org/?probe=9d3c5ea28d) | Apr 11, 2023 |
| MACHENIKE     | T58-V                       | Notebook    | [9a70cca135](https://linux-hardware.org/?probe=9a70cca135) | Apr 08, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [b4c155dc99](https://linux-hardware.org/?probe=b4c155dc99) | Apr 07, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [30e0bd8317](https://linux-hardware.org/?probe=30e0bd8317) | Apr 02, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [832b434c38](https://linux-hardware.org/?probe=832b434c38) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [7e283bfa25](https://linux-hardware.org/?probe=7e283bfa25) | Mar 28, 2023 |
| METAPHYUNI    | MetamechBook                | Notebook    | [7e4076cb61](https://linux-hardware.org/?probe=7e4076cb61) | Mar 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [79e1666c41](https://linux-hardware.org/?probe=79e1666c41) | Mar 23, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4757b31751](https://linux-hardware.org/?probe=4757b31751) | Mar 19, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [cdf57a039e](https://linux-hardware.org/?probe=cdf57a039e) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [27356d58d5](https://linux-hardware.org/?probe=27356d58d5) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | Desktop     | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| Intel         | W2600CR G21602-308          | Server      | [96cda648c2](https://linux-hardware.org/?probe=96cda648c2) | Mar 14, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d256faa9fc](https://linux-hardware.org/?probe=d256faa9fc) | Mar 06, 2023 |
| Dell          | 06WXJT A02                  | Server      | [a4f3535e84](https://linux-hardware.org/?probe=a4f3535e84) | Mar 03, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [97925534c2](https://linux-hardware.org/?probe=97925534c2) | Mar 02, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [fc803f9205](https://linux-hardware.org/?probe=fc803f9205) | Feb 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [601836815c](https://linux-hardware.org/?probe=601836815c) | Feb 22, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [c1936488f5](https://linux-hardware.org/?probe=c1936488f5) | Feb 20, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [81cfc27f9e](https://linux-hardware.org/?probe=81cfc27f9e) | Feb 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [ee4e2b3cde](https://linux-hardware.org/?probe=ee4e2b3cde) | Feb 19, 2023 |
| AOKZOE        | A1 AR07                     | Tablet      | [fe54acc90f](https://linux-hardware.org/?probe=fe54acc90f) | Feb 18, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [58bcb8bf04](https://linux-hardware.org/?probe=58bcb8bf04) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [bf63748499](https://linux-hardware.org/?probe=bf63748499) | Feb 18, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [162b72d7a8](https://linux-hardware.org/?probe=162b72d7a8) | Feb 17, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| Lenovo        | Y430P 20435                 | Notebook    | [da3030daae](https://linux-hardware.org/?probe=da3030daae) | Feb 16, 2023 |
| Lenovo        | ThinkPad X230 23066RC       | Notebook    | [6a223f0a71](https://linux-hardware.org/?probe=6a223f0a71) | Feb 15, 2023 |
| ASUSTek       | X705UA                      | Notebook    | [cc59e95283](https://linux-hardware.org/?probe=cc59e95283) | Feb 07, 2023 |
| ASUSTek       | X705UA                      | Notebook    | [25188e7cfa](https://linux-hardware.org/?probe=25188e7cfa) | Feb 07, 2023 |
| Timi          | TM1613                      | Notebook    | [503133b0db](https://linux-hardware.org/?probe=503133b0db) | Feb 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [42a3945648](https://linux-hardware.org/?probe=42a3945648) | Feb 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [5f77ae27c2](https://linux-hardware.org/?probe=5f77ae27c2) | Feb 04, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [6d6a8e4be4](https://linux-hardware.org/?probe=6d6a8e4be4) | Jan 24, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [81c1e35182](https://linux-hardware.org/?probe=81c1e35182) | Jan 24, 2023 |
| Acer          | Swift SF314-57G             | Notebook    | [ae9de10584](https://linux-hardware.org/?probe=ae9de10584) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [4b9d2e6e26](https://linux-hardware.org/?probe=4b9d2e6e26) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [f5bb76ae13](https://linux-hardware.org/?probe=f5bb76ae13) | Jan 21, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [a18f404d39](https://linux-hardware.org/?probe=a18f404d39) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7cb08d37fb](https://linux-hardware.org/?probe=7cb08d37fb) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | Desktop     | [4ce5e1fd02](https://linux-hardware.org/?probe=4ce5e1fd02) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | Desktop     | [09560460b9](https://linux-hardware.org/?probe=09560460b9) | Jan 14, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2e13f150e6](https://linux-hardware.org/?probe=2e13f150e6) | Jan 09, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6743fa1b](https://linux-hardware.org/?probe=ec6743fa1b) | Jan 06, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [dc81fac0f7](https://linux-hardware.org/?probe=dc81fac0f7) | Jan 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [ecf944f539](https://linux-hardware.org/?probe=ecf944f539) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [0031785936](https://linux-hardware.org/?probe=0031785936) | Dec 31, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [4bd2096c80](https://linux-hardware.org/?probe=4bd2096c80) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [7b3c89637b](https://linux-hardware.org/?probe=7b3c89637b) | Dec 30, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [2154a332b0](https://linux-hardware.org/?probe=2154a332b0) | Dec 29, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [8a5b919c91](https://linux-hardware.org/?probe=8a5b919c91) | Dec 24, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [641b77c3da](https://linux-hardware.org/?probe=641b77c3da) | Dec 20, 2022 |
| GPD           | P2 MAX                      | Notebook    | [de5983ec37](https://linux-hardware.org/?probe=de5983ec37) | Dec 17, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | Notebook    | [8d631bb590](https://linux-hardware.org/?probe=8d631bb590) | Dec 17, 2022 |
| Dell          | Inspiron 7590               | Notebook    | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| GPD           | P2 MAX                      | Notebook    | [63c199f475](https://linux-hardware.org/?probe=63c199f475) | Dec 08, 2022 |
| Lenovo        | ThinkSystem SR358FV2 Res... | Server      | [3702b80721](https://linux-hardware.org/?probe=3702b80721) | Dec 07, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [706e40ed5a](https://linux-hardware.org/?probe=706e40ed5a) | Dec 04, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | Desktop     | [5476b73cb7](https://linux-hardware.org/?probe=5476b73cb7) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | Desktop     | [6d07106192](https://linux-hardware.org/?probe=6d07106192) | Dec 02, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [aff020417f](https://linux-hardware.org/?probe=aff020417f) | Dec 01, 2022 |
| Dell          | Latitude 7390               | Notebook    | [7214cac96d](https://linux-hardware.org/?probe=7214cac96d) | Nov 30, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [7b0cf2fa20](https://linux-hardware.org/?probe=7b0cf2fa20) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20A... | Convertible | [341287988f](https://linux-hardware.org/?probe=341287988f) | Nov 17, 2022 |
| GPD           | G1619-04                    | Notebook    | [ce6d16840e](https://linux-hardware.org/?probe=ce6d16840e) | Nov 07, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [468f8df590](https://linux-hardware.org/?probe=468f8df590) | Nov 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [895a345eb9](https://linux-hardware.org/?probe=895a345eb9) | Nov 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9d9d3a4967](https://linux-hardware.org/?probe=9d9d3a4967) | Nov 02, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| ASRock        | H470M-STX                   | Desktop     | [02f3177542](https://linux-hardware.org/?probe=02f3177542) | Oct 26, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [ce7a9a3171](https://linux-hardware.org/?probe=ce7a9a3171) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [a9c49ccd5d](https://linux-hardware.org/?probe=a9c49ccd5d) | Oct 21, 2022 |
| Lenovo        | ThinkPad T470 20HD002TCD    | Notebook    | [0b0ca5a5f6](https://linux-hardware.org/?probe=0b0ca5a5f6) | Oct 20, 2022 |
| HP            | 8956 010                    | Mini pc     | [d959cdb332](https://linux-hardware.org/?probe=d959cdb332) | Oct 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8ebbbf93e4](https://linux-hardware.org/?probe=8ebbbf93e4) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [7d3c652547](https://linux-hardware.org/?probe=7d3c652547) | Oct 11, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6207d55486](https://linux-hardware.org/?probe=6207d55486) | Oct 05, 2022 |
| HP            | ZHAN 66 Pro A 14 inch G5... | Notebook    | [c5587dbec5](https://linux-hardware.org/?probe=c5587dbec5) | Oct 04, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [2163cddbe4](https://linux-hardware.org/?probe=2163cddbe4) | Oct 04, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| Fujitsu       | FMVNU6G1C                   | Notebook    | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| HP            | 18E7                        | Desktop     | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7c8030e423](https://linux-hardware.org/?probe=7c8030e423) | Sep 26, 2022 |
| Dell          | Latitude E5250              | Notebook    | [e4ffe3583d](https://linux-hardware.org/?probe=e4ffe3583d) | Sep 26, 2022 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [e939330716](https://linux-hardware.org/?probe=e939330716) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | Desktop     | [822d20fcdb](https://linux-hardware.org/?probe=822d20fcdb) | Sep 25, 2022 |
| Unknown       | Apple iPad Pro (9.7-inch... | Desktop     | [92f244ac1c](https://linux-hardware.org/?probe=92f244ac1c) | Sep 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [89a019875a](https://linux-hardware.org/?probe=89a019875a) | Sep 24, 2022 |
| ASRock        | Z490 PG Velocita            | Desktop     | [eac045585b](https://linux-hardware.org/?probe=eac045585b) | Sep 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [76be3ff1db](https://linux-hardware.org/?probe=76be3ff1db) | Sep 22, 2022 |
| Huanan        | X99-TF                      | Desktop     | [657d78e891](https://linux-hardware.org/?probe=657d78e891) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [3759658825](https://linux-hardware.org/?probe=3759658825) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f454a8f6a5](https://linux-hardware.org/?probe=f454a8f6a5) | Sep 19, 2022 |
| HUAWEI        | PGU-WBY0                    | Soc         | [3f3d475864](https://linux-hardware.org/?probe=3f3d475864) | Sep 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [5160feeaf2](https://linux-hardware.org/?probe=5160feeaf2) | Sep 13, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [876e87c7b6](https://linux-hardware.org/?probe=876e87c7b6) | Sep 13, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [1d95c5b6ef](https://linux-hardware.org/?probe=1d95c5b6ef) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4562797ebc](https://linux-hardware.org/?probe=4562797ebc) | Sep 08, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [32ab96441e](https://linux-hardware.org/?probe=32ab96441e) | Sep 08, 2022 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | Notebook    | [d0ddfb5815](https://linux-hardware.org/?probe=d0ddfb5815) | Sep 07, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [302c3f11ec](https://linux-hardware.org/?probe=302c3f11ec) | Aug 29, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [9a83e7ee58](https://linux-hardware.org/?probe=9a83e7ee58) | Aug 28, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [638f08fc43](https://linux-hardware.org/?probe=638f08fc43) | Aug 27, 2022 |
| Dell          | 0427JK A00                  | Desktop     | [8f6a2c8d0b](https://linux-hardware.org/?probe=8f6a2c8d0b) | Aug 22, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [90aed4d5d1](https://linux-hardware.org/?probe=90aed4d5d1) | Aug 20, 2022 |
| Dell          | 0200DY A03                  | Desktop     | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [58b22885a8](https://linux-hardware.org/?probe=58b22885a8) | Aug 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c32d69a956](https://linux-hardware.org/?probe=c32d69a956) | Aug 18, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [bd7c6f361d](https://linux-hardware.org/?probe=bd7c6f361d) | Aug 18, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [56ba58f5d0](https://linux-hardware.org/?probe=56ba58f5d0) | Aug 16, 2022 |
| Lenovo        | ThinkPad T490s 20NYS79X0... | Notebook    | [5fe4fba501](https://linux-hardware.org/?probe=5fe4fba501) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [bc4cf926f2](https://linux-hardware.org/?probe=bc4cf926f2) | Aug 06, 2022 |
| KOHJINSHA     | SC series                   | Notebook    | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | Notebook    | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | Notebook    | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Fujitsu       | LIFEBOOK V1020              | Notebook    | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d449f1aeb9](https://linux-hardware.org/?probe=d449f1aeb9) | Jul 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [353168b909](https://linux-hardware.org/?probe=353168b909) | Jul 18, 2022 |
| Huanan        | X99-TF                      | Desktop     | [55b43de5a6](https://linux-hardware.org/?probe=55b43de5a6) | Jul 17, 2022 |
| IBM           | 260921H                     | Notebook    | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | Notebook    | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | Notebook    | [f3e0ebd16e](https://linux-hardware.org/?probe=f3e0ebd16e) | Jul 15, 2022 |
| IBM           | 260921H                     | Notebook    | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | Notebook    | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e9adf47b7a](https://linux-hardware.org/?probe=e9adf47b7a) | Jul 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
| Soyo          | SY-A68M FS V2.0             | Desktop     | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [bd4792ebd8](https://linux-hardware.org/?probe=bd4792ebd8) | Jul 02, 2022 |
| Compaq        | Tablet PC TC1000            | Notebook    | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | Notebook    | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | Notebook    | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [044be44d33](https://linux-hardware.org/?probe=044be44d33) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [5bd3ad4d01](https://linux-hardware.org/?probe=5bd3ad4d01) | Jun 24, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Huanan        | X99-TF                      | Desktop     | [04dc5246af](https://linux-hardware.org/?probe=04dc5246af) | Jun 18, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | Desktop     | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [f4c7f13ff8](https://linux-hardware.org/?probe=f4c7f13ff8) | Jun 14, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | Notebook    | [e3df184136](https://linux-hardware.org/?probe=e3df184136) | Jun 12, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e373d39f20](https://linux-hardware.org/?probe=e373d39f20) | Jun 09, 2022 |
| Huanan        | X99-TF                      | Desktop     | [4e5364e832](https://linux-hardware.org/?probe=4e5364e832) | Jun 08, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [2f8215fb0a](https://linux-hardware.org/?probe=2f8215fb0a) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [4d4c32223e](https://linux-hardware.org/?probe=4d4c32223e) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [63fd75f1a8](https://linux-hardware.org/?probe=63fd75f1a8) | May 29, 2022 |
| Lenovo        | Legion Y7000P2020H 82AX     | Notebook    | [220325c031](https://linux-hardware.org/?probe=220325c031) | May 29, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [75d345243e](https://linux-hardware.org/?probe=75d345243e) | May 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [1f67896c5c](https://linux-hardware.org/?probe=1f67896c5c) | May 22, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [a227af798c](https://linux-hardware.org/?probe=a227af798c) | May 20, 2022 |
| Gigabyte      | HA65M-UD3H-B3               | Desktop     | [d368918a0b](https://linux-hardware.org/?probe=d368918a0b) | May 13, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [f0b122c199](https://linux-hardware.org/?probe=f0b122c199) | May 09, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [99e0958898](https://linux-hardware.org/?probe=99e0958898) | May 01, 2022 |
| Dell          | Precision 7520              | Notebook    | [2dc98a1a8d](https://linux-hardware.org/?probe=2dc98a1a8d) | Apr 30, 2022 |
| MSI           | H87I                        | Desktop     | [af4a26a5ea](https://linux-hardware.org/?probe=af4a26a5ea) | Apr 30, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [0633ac7757](https://linux-hardware.org/?probe=0633ac7757) | Apr 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [9191742453](https://linux-hardware.org/?probe=9191742453) | Apr 26, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [56902c7998](https://linux-hardware.org/?probe=56902c7998) | Apr 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [a3aa6e30b9](https://linux-hardware.org/?probe=a3aa6e30b9) | Apr 21, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [3dd8282149](https://linux-hardware.org/?probe=3dd8282149) | Apr 20, 2022 |
| GPD           | P2 MAX                      | Notebook    | [ca842dc5fb](https://linux-hardware.org/?probe=ca842dc5fb) | Apr 19, 2022 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [d359794b2f](https://linux-hardware.org/?probe=d359794b2f) | Apr 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [7ea786c89b](https://linux-hardware.org/?probe=7ea786c89b) | Apr 18, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0ac1f4daf9](https://linux-hardware.org/?probe=0ac1f4daf9) | Apr 12, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [abed3ae34d](https://linux-hardware.org/?probe=abed3ae34d) | Apr 12, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| ASUSTek       | VM62                        | Desktop     | [ae684cdf71](https://linux-hardware.org/?probe=ae684cdf71) | Apr 05, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [bdca066ba3](https://linux-hardware.org/?probe=bdca066ba3) | Apr 05, 2022 |
| ASRock        | H410M-ITX/ac                | Desktop     | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [314bd42e78](https://linux-hardware.org/?probe=314bd42e78) | Mar 28, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [a881a875bd](https://linux-hardware.org/?probe=a881a875bd) | Mar 27, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [2d48cb4419](https://linux-hardware.org/?probe=2d48cb4419) | Mar 26, 2022 |
| Dell          | 0Y3R3K A03                  | Desktop     | [b772cf9d86](https://linux-hardware.org/?probe=b772cf9d86) | Mar 26, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [e7fb180535](https://linux-hardware.org/?probe=e7fb180535) | Mar 16, 2022 |
| Dell          | Latitude 7285               | Notebook    | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [7320ed668a](https://linux-hardware.org/?probe=7320ed668a) | Mar 12, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [03b27c8ca4](https://linux-hardware.org/?probe=03b27c8ca4) | Mar 12, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [4998fff0f9](https://linux-hardware.org/?probe=4998fff0f9) | Mar 12, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [99d3e16ede](https://linux-hardware.org/?probe=99d3e16ede) | Mar 12, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [c68cec2207](https://linux-hardware.org/?probe=c68cec2207) | Mar 11, 2022 |
| Unknown       | Intel X79                   | Desktop     | [e947d6af7f](https://linux-hardware.org/?probe=e947d6af7f) | Mar 11, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [96b36779e0](https://linux-hardware.org/?probe=96b36779e0) | Mar 11, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| HP            | Notebook                    | Notebook    | [9c04c0776d](https://linux-hardware.org/?probe=9c04c0776d) | Mar 10, 2022 |
| HP            | Notebook                    | Notebook    | [c7d735dc99](https://linux-hardware.org/?probe=c7d735dc99) | Mar 10, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0b9a7acb84](https://linux-hardware.org/?probe=0b9a7acb84) | Feb 27, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [3c7daed552](https://linux-hardware.org/?probe=3c7daed552) | Feb 22, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [6c00869d7b](https://linux-hardware.org/?probe=6c00869d7b) | Feb 21, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [0f4fad19b2](https://linux-hardware.org/?probe=0f4fad19b2) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6e5689a733](https://linux-hardware.org/?probe=6e5689a733) | Jan 28, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 Rev ... | Soc         | [2a66f4b578](https://linux-hardware.org/?probe=2a66f4b578) | Jan 24, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [515465fd5a](https://linux-hardware.org/?probe=515465fd5a) | Jan 22, 2022 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [4c32bf6d7b](https://linux-hardware.org/?probe=4c32bf6d7b) | Jan 18, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c5fa4a0cec](https://linux-hardware.org/?probe=c5fa4a0cec) | Dec 24, 2021 |
| ASRock        | H410M-ITX/ac                | Desktop     | [99c341562a](https://linux-hardware.org/?probe=99c341562a) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| MSI           | 870-G45                     | Desktop     | [e6317a2b91](https://linux-hardware.org/?probe=e6317a2b91) | Dec 19, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| Fujitsu       | LIFEBOOK LH530              | Notebook    | [8db7409ab5](https://linux-hardware.org/?probe=8db7409ab5) | Dec 14, 2021 |
| Unknown       | Intel X79                   | Desktop     | [985655e4b3](https://linux-hardware.org/?probe=985655e4b3) | Dec 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [739be994cb](https://linux-hardware.org/?probe=739be994cb) | Dec 09, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [024a42eb21](https://linux-hardware.org/?probe=024a42eb21) | Dec 08, 2021 |
| Unknown       | Intel X79                   | Desktop     | [6f32192557](https://linux-hardware.org/?probe=6f32192557) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| MSI           | Boston                      | Desktop     | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| Supermicro    | C2SBC-Q                     | Desktop     | [1099e48366](https://linux-hardware.org/?probe=1099e48366) | Nov 28, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [58d43162d2](https://linux-hardware.org/?probe=58d43162d2) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ee13ae89af](https://linux-hardware.org/?probe=ee13ae89af) | Nov 26, 2021 |
| Apple         | MacBook10,1                 | Notebook    | [6cb99e6a5f](https://linux-hardware.org/?probe=6cb99e6a5f) | Nov 23, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [fc59694424](https://linux-hardware.org/?probe=fc59694424) | Nov 17, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [35b58ec233](https://linux-hardware.org/?probe=35b58ec233) | Nov 16, 2021 |
| Jumper        | EZbook                      | Notebook    | [5da2b95e2f](https://linux-hardware.org/?probe=5da2b95e2f) | Nov 12, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Seco          | C40 C                       | Desktop     | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [9bcd3d5479](https://linux-hardware.org/?probe=9bcd3d5479) | Oct 29, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [c7fc01bd49](https://linux-hardware.org/?probe=c7fc01bd49) | Oct 27, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [6f87ece998](https://linux-hardware.org/?probe=6f87ece998) | Oct 26, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [3d42bc888b](https://linux-hardware.org/?probe=3d42bc888b) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [54e54e71bd](https://linux-hardware.org/?probe=54e54e71bd) | Oct 24, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [aedfc53de6](https://linux-hardware.org/?probe=aedfc53de6) | Oct 20, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [20dc49f637](https://linux-hardware.org/?probe=20dc49f637) | Oct 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [aee062d6e5](https://linux-hardware.org/?probe=aee062d6e5) | Oct 04, 2021 |
| Lenovo        | Legion Y9000P2021H 82JD     | Notebook    | [4c3be0fe24](https://linux-hardware.org/?probe=4c3be0fe24) | Oct 02, 2021 |
| MSI           | H61M-P23                    | Desktop     | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| GPD           | G1618-03                    | Notebook    | [41916177c2](https://linux-hardware.org/?probe=41916177c2) | Sep 01, 2021 |
| GPD           | G1618-03                    | Notebook    | [c2abcaf10c](https://linux-hardware.org/?probe=c2abcaf10c) | Sep 01, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [1440e244f6](https://linux-hardware.org/?probe=1440e244f6) | Aug 26, 2021 |
| Dell          | Precision 7550              | Notebook    | [42721343a3](https://linux-hardware.org/?probe=42721343a3) | Aug 16, 2021 |
| Lenovo        | XiaoXin-14API QC 2019 81... | Notebook    | [814eb97442](https://linux-hardware.org/?probe=814eb97442) | Aug 14, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [d920558127](https://linux-hardware.org/?probe=d920558127) | Aug 14, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5cd377c0e0](https://linux-hardware.org/?probe=5cd377c0e0) | Aug 13, 2021 |
| Gigabyte      | B75M-D2P                    | Desktop     | [5e54c2a102](https://linux-hardware.org/?probe=5e54c2a102) | Aug 12, 2021 |
| Lenovo        | ThinkPad T61 6465CTO        | Notebook    | [d93258840e](https://linux-hardware.org/?probe=d93258840e) | Aug 04, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [eb060cd2c4](https://linux-hardware.org/?probe=eb060cd2c4) | Aug 04, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [828a52387f](https://linux-hardware.org/?probe=828a52387f) | Aug 02, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [12b2c3e130](https://linux-hardware.org/?probe=12b2c3e130) | Aug 01, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [3af43c8ebe](https://linux-hardware.org/?probe=3af43c8ebe) | Jul 29, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [fa0aa86cef](https://linux-hardware.org/?probe=fa0aa86cef) | Jul 28, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [8fc32673b3](https://linux-hardware.org/?probe=8fc32673b3) | Jul 25, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [58b70e282d](https://linux-hardware.org/?probe=58b70e282d) | Jul 14, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [66cf378cf1](https://linux-hardware.org/?probe=66cf378cf1) | Jul 10, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [71da4978c9](https://linux-hardware.org/?probe=71da4978c9) | Jun 29, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [ed911e7e8c](https://linux-hardware.org/?probe=ed911e7e8c) | Jun 26, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [8785d98b0b](https://linux-hardware.org/?probe=8785d98b0b) | Jun 19, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [54e520ac17](https://linux-hardware.org/?probe=54e520ac17) | Jun 17, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [c2bfccf320](https://linux-hardware.org/?probe=c2bfccf320) | Jun 16, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [d3f69874dd](https://linux-hardware.org/?probe=d3f69874dd) | Jun 16, 2021 |
| Lenovo        | IdeaCentre B305 10052       | All in one  | [8399296d51](https://linux-hardware.org/?probe=8399296d51) | Jun 13, 2021 |
| Dell          | Precision M4800             | Notebook    | [298694c222](https://linux-hardware.org/?probe=298694c222) | Jun 12, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [76219e9cca](https://linux-hardware.org/?probe=76219e9cca) | Jun 09, 2021 |
| Acer          | Aspire E5-573               | Notebook    | [4193a2da9d](https://linux-hardware.org/?probe=4193a2da9d) | Jun 08, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [bcb80080a5](https://linux-hardware.org/?probe=bcb80080a5) | Jun 06, 2021 |
| Dell          | Precision M4800             | Notebook    | [67fb08d285](https://linux-hardware.org/?probe=67fb08d285) | Jun 06, 2021 |
| Dell          | Precision M4800             | Notebook    | [c72664a2f4](https://linux-hardware.org/?probe=c72664a2f4) | Jun 06, 2021 |
| HP            | 18E7                        | Desktop     | [9844f6635c](https://linux-hardware.org/?probe=9844f6635c) | May 30, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [81ffc7ba9e](https://linux-hardware.org/?probe=81ffc7ba9e) | May 26, 2021 |
| ASUSTek       | VM62                        | Desktop     | [486aeb5b89](https://linux-hardware.org/?probe=486aeb5b89) | May 25, 2021 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [e19475cd4c](https://linux-hardware.org/?probe=e19475cd4c) | May 22, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [a201bdfc36](https://linux-hardware.org/?probe=a201bdfc36) | May 19, 2021 |
| Fujitsu       | UH-X                        | Notebook    | [be65091e59](https://linux-hardware.org/?probe=be65091e59) | May 19, 2021 |
| ASUSTek       | M4A78-VM                    | Desktop     | [3313d34c41](https://linux-hardware.org/?probe=3313d34c41) | May 15, 2021 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [1409e11b30](https://linux-hardware.org/?probe=1409e11b30) | May 12, 2021 |
| Nvidia        | Tegra                       | Soc         | [54592ec1a2](https://linux-hardware.org/?probe=54592ec1a2) | May 08, 2021 |
| Nvidia        | Tegra                       | Soc         | [ab1c7d5eab](https://linux-hardware.org/?probe=ab1c7d5eab) | May 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [8d372d62b7](https://linux-hardware.org/?probe=8d372d62b7) | May 07, 2021 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [1b777c6f08](https://linux-hardware.org/?probe=1b777c6f08) | May 02, 2021 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [4c7956a34c](https://linux-hardware.org/?probe=4c7956a34c) | May 02, 2021 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [f35a966b00](https://linux-hardware.org/?probe=f35a966b00) | Apr 14, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [a917367457](https://linux-hardware.org/?probe=a917367457) | Apr 09, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [f7937503ac](https://linux-hardware.org/?probe=f7937503ac) | Apr 08, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [99d71b6ea5](https://linux-hardware.org/?probe=99d71b6ea5) | Apr 06, 2021 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [8253b70553](https://linux-hardware.org/?probe=8253b70553) | Apr 06, 2021 |
| MSI           | Boston                      | Desktop     | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [60600f6f0c](https://linux-hardware.org/?probe=60600f6f0c) | Mar 26, 2021 |
| HP            | 1632                        | Desktop     | [adf9ebb679](https://linux-hardware.org/?probe=adf9ebb679) | Mar 25, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [6a4196e0aa](https://linux-hardware.org/?probe=6a4196e0aa) | Mar 23, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dc64c81c35](https://linux-hardware.org/?probe=dc64c81c35) | Mar 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [280785b873](https://linux-hardware.org/?probe=280785b873) | Mar 22, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [20d78f0b3a](https://linux-hardware.org/?probe=20d78f0b3a) | Mar 22, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [71ef988016](https://linux-hardware.org/?probe=71ef988016) | Mar 21, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [e44a5ce779](https://linux-hardware.org/?probe=e44a5ce779) | Mar 14, 2021 |
| ASUSTek       | UX302LA                     | Notebook    | [fe27a8e195](https://linux-hardware.org/?probe=fe27a8e195) | Mar 12, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [d23d84b5f6](https://linux-hardware.org/?probe=d23d84b5f6) | Mar 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [5051ba6156](https://linux-hardware.org/?probe=5051ba6156) | Mar 05, 2021 |
| MSI           | Boston                      | Desktop     | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [b94539c6dc](https://linux-hardware.org/?probe=b94539c6dc) | Mar 01, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [b2cb174b9a](https://linux-hardware.org/?probe=b2cb174b9a) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [2414020b54](https://linux-hardware.org/?probe=2414020b54) | Feb 26, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [ae61a5e1fa](https://linux-hardware.org/?probe=ae61a5e1fa) | Feb 26, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [87c36a9322](https://linux-hardware.org/?probe=87c36a9322) | Feb 23, 2021 |
| Lenovo        | ThinkPad E14 20RAA002CD     | Notebook    | [77ccb1ee60](https://linux-hardware.org/?probe=77ccb1ee60) | Feb 22, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [7d9f2bee38](https://linux-hardware.org/?probe=7d9f2bee38) | Feb 21, 2021 |
| ASUSTek       | VM45                        | Desktop     | [03eeb85521](https://linux-hardware.org/?probe=03eeb85521) | Feb 21, 2021 |
| ASUSTek       | VM65-K                      | Desktop     | [6b97cf71eb](https://linux-hardware.org/?probe=6b97cf71eb) | Feb 18, 2021 |
| ASUSTek       | VM65-K                      | Desktop     | [4f0bcd1276](https://linux-hardware.org/?probe=4f0bcd1276) | Feb 17, 2021 |
| ASUSTek       | VM40B                       | Desktop     | [6c0bf22f39](https://linux-hardware.org/?probe=6c0bf22f39) | Feb 17, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [d82924b12b](https://linux-hardware.org/?probe=d82924b12b) | Feb 16, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [ebc5645105](https://linux-hardware.org/?probe=ebc5645105) | Feb 11, 2021 |
| Lenovo        | IdeaCentre K330             | Desktop     | [78ce34058b](https://linux-hardware.org/?probe=78ce34058b) | Feb 11, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [f4c2a6bac8](https://linux-hardware.org/?probe=f4c2a6bac8) | Feb 07, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [d4f69c78fa](https://linux-hardware.org/?probe=d4f69c78fa) | Jan 31, 2021 |
| Fujitsu       | S6420                       | Notebook    | [b23c0f10e7](https://linux-hardware.org/?probe=b23c0f10e7) | Jan 28, 2021 |
| Fujitsu       | S6420                       | Notebook    | [0cf6376b40](https://linux-hardware.org/?probe=0cf6376b40) | Jan 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1d0000672d](https://linux-hardware.org/?probe=1d0000672d) | Jan 23, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [3d7ce778c6](https://linux-hardware.org/?probe=3d7ce778c6) | Jan 20, 2021 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [fe7d03f093](https://linux-hardware.org/?probe=fe7d03f093) | Jan 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [b8f5d6f1e4](https://linux-hardware.org/?probe=b8f5d6f1e4) | Jan 16, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [39bc70ca5d](https://linux-hardware.org/?probe=39bc70ca5d) | Jan 13, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [d2420f233b](https://linux-hardware.org/?probe=d2420f233b) | Jan 10, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| Dell          | 0TP412                      | Desktop     | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| Intel         | NUC6CAYB J23203-406         | Mini pc     | [038dce10fa](https://linux-hardware.org/?probe=038dce10fa) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [a8ac85cb5a](https://linux-hardware.org/?probe=a8ac85cb5a) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [8c7ba97457](https://linux-hardware.org/?probe=8c7ba97457) | Dec 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [01333c5b9e](https://linux-hardware.org/?probe=01333c5b9e) | Dec 29, 2020 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [728d7e48d4](https://linux-hardware.org/?probe=728d7e48d4) | Dec 27, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [1d4b16bb0d](https://linux-hardware.org/?probe=1d4b16bb0d) | Dec 22, 2020 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [cf7386e848](https://linux-hardware.org/?probe=cf7386e848) | Dec 18, 2020 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [88a7edec45](https://linux-hardware.org/?probe=88a7edec45) | Dec 18, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [1d6b7df7b4](https://linux-hardware.org/?probe=1d6b7df7b4) | Dec 08, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [8309aa39cf](https://linux-hardware.org/?probe=8309aa39cf) | Nov 30, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [ede3032fed](https://linux-hardware.org/?probe=ede3032fed) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [f3012a2898](https://linux-hardware.org/?probe=f3012a2898) | Nov 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [37d5acae7d](https://linux-hardware.org/?probe=37d5acae7d) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [3c4ff5bb58](https://linux-hardware.org/?probe=3c4ff5bb58) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [97c485886b](https://linux-hardware.org/?probe=97c485886b) | Nov 25, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [8f55b945a1](https://linux-hardware.org/?probe=8f55b945a1) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | Notebook    | [f55a6a6679](https://linux-hardware.org/?probe=f55a6a6679) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | Notebook    | [7aea886f7a](https://linux-hardware.org/?probe=7aea886f7a) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [de597aa847](https://linux-hardware.org/?probe=de597aa847) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f5aa8c9150](https://linux-hardware.org/?probe=f5aa8c9150) | Nov 20, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a3c484b8ee](https://linux-hardware.org/?probe=a3c484b8ee) | Nov 16, 2020 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [6254edfb10](https://linux-hardware.org/?probe=6254edfb10) | Nov 14, 2020 |
| Lenovo        | G770 20089                  | Notebook    | [6da9203114](https://linux-hardware.org/?probe=6da9203114) | Nov 13, 2020 |
| HP            | 2000                        | Notebook    | [f548e6d1cc](https://linux-hardware.org/?probe=f548e6d1cc) | Nov 11, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [e1700b887e](https://linux-hardware.org/?probe=e1700b887e) | Nov 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [69fb29494b](https://linux-hardware.org/?probe=69fb29494b) | Nov 07, 2020 |
| HP            | 2000                        | Notebook    | [df76d279ad](https://linux-hardware.org/?probe=df76d279ad) | Nov 05, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [f90977870e](https://linux-hardware.org/?probe=f90977870e) | Nov 04, 2020 |
| Timi          | TM1607                      | Notebook    | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| ZOTAC         | ZBOX-ID92/ZBOX-IQ01         | Mini pc     | [fbba9f6a3b](https://linux-hardware.org/?probe=fbba9f6a3b) | Nov 02, 2020 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [e970e25954](https://linux-hardware.org/?probe=e970e25954) | Nov 02, 2020 |
| Acer          | Swift SF314-57              | Notebook    | [8395e5a946](https://linux-hardware.org/?probe=8395e5a946) | Oct 30, 2020 |
| Acer          | Swift SF314-57              | Notebook    | [123f60c868](https://linux-hardware.org/?probe=123f60c868) | Oct 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [f9d1166197](https://linux-hardware.org/?probe=f9d1166197) | Oct 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77849f8db0](https://linux-hardware.org/?probe=77849f8db0) | Oct 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77d6dd66e2](https://linux-hardware.org/?probe=77d6dd66e2) | Oct 23, 2020 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [1af7b2b551](https://linux-hardware.org/?probe=1af7b2b551) | Oct 13, 2020 |
| HP            | 2140                        | Notebook    | [bde3dc449f](https://linux-hardware.org/?probe=bde3dc449f) | Oct 07, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [1fe32b8f6d](https://linux-hardware.org/?probe=1fe32b8f6d) | Oct 04, 2020 |
| HP            | 2000                        | Notebook    | [fbd8bf0e69](https://linux-hardware.org/?probe=fbd8bf0e69) | Oct 01, 2020 |
| Fujitsu       | LIFEBOOK S904               | Notebook    | [5035864c45](https://linux-hardware.org/?probe=5035864c45) | Sep 27, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [37e6b406f7](https://linux-hardware.org/?probe=37e6b406f7) | Sep 27, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [bd8f561b0b](https://linux-hardware.org/?probe=bd8f561b0b) | Sep 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e292456297](https://linux-hardware.org/?probe=e292456297) | Sep 17, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e7b41f62a4](https://linux-hardware.org/?probe=e7b41f62a4) | Sep 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [20bdbc68b7](https://linux-hardware.org/?probe=20bdbc68b7) | Sep 12, 2020 |
| ASUSTek       | H81M-E                      | Desktop     | [43b8c677bc](https://linux-hardware.org/?probe=43b8c677bc) | Sep 10, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [24cad8bed5](https://linux-hardware.org/?probe=24cad8bed5) | Aug 28, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [3d4c2a283d](https://linux-hardware.org/?probe=3d4c2a283d) | Aug 28, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [64a249acd1](https://linux-hardware.org/?probe=64a249acd1) | Aug 28, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [6a91a7b38c](https://linux-hardware.org/?probe=6a91a7b38c) | Aug 25, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [e27db6fb31](https://linux-hardware.org/?probe=e27db6fb31) | Aug 24, 2020 |
| Samsung       | 930XBE                      | Notebook    | [92925e0656](https://linux-hardware.org/?probe=92925e0656) | Aug 24, 2020 |
| HP            | 802E                        | Desktop     | [653b11eec3](https://linux-hardware.org/?probe=653b11eec3) | Aug 11, 2020 |
| HP            | 802E                        | Desktop     | [6f32afeb2b](https://linux-hardware.org/?probe=6f32afeb2b) | Aug 10, 2020 |
| HP            | 802E                        | Desktop     | [25d8ddc0bb](https://linux-hardware.org/?probe=25d8ddc0bb) | Aug 10, 2020 |
| Dell          | Inspiron 5580               | Notebook    | [fbaf2b8f7f](https://linux-hardware.org/?probe=fbaf2b8f7f) | Aug 05, 2020 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [e7488a8b16](https://linux-hardware.org/?probe=e7488a8b16) | Aug 04, 2020 |
| Toshiba       | PORTEGE R830                | Notebook    | [fa44f09e6e](https://linux-hardware.org/?probe=fa44f09e6e) | Aug 03, 2020 |
| Dell          | G7 7588                     | Notebook    | [e85e2949de](https://linux-hardware.org/?probe=e85e2949de) | Aug 01, 2020 |
| Lenovo        | ZHAOYANG K47                | Notebook    | [fa5be40392](https://linux-hardware.org/?probe=fa5be40392) | Jul 24, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [50dc692a9e](https://linux-hardware.org/?probe=50dc692a9e) | Jul 23, 2020 |
| Lenovo        | ZHAOYANG K47                | Notebook    | [879b0d586f](https://linux-hardware.org/?probe=879b0d586f) | Jul 22, 2020 |
| Gigabyte      | Z170X-Gaming 5 Modified ... | Desktop     | [a62f520dc3](https://linux-hardware.org/?probe=a62f520dc3) | Jul 18, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [723898cdec](https://linux-hardware.org/?probe=723898cdec) | Jun 20, 2020 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [f897dd388f](https://linux-hardware.org/?probe=f897dd388f) | Jun 17, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [c90b1cb242](https://linux-hardware.org/?probe=c90b1cb242) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [74dadf599d](https://linux-hardware.org/?probe=74dadf599d) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [db21903e1a](https://linux-hardware.org/?probe=db21903e1a) | Jun 14, 2020 |
| Lenovo        | ThinkPad T480s 20L7005FU... | Notebook    | [2bc99eeca5](https://linux-hardware.org/?probe=2bc99eeca5) | Jun 09, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| HP            | 1998                        | Desktop     | [255863fefb](https://linux-hardware.org/?probe=255863fefb) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | Desktop     | [b159b440f2](https://linux-hardware.org/?probe=b159b440f2) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | Desktop     | [4181637bf3](https://linux-hardware.org/?probe=4181637bf3) | Jun 01, 2020 |
| Fujitsu       | LIFEBOOK AH556              | Notebook    | [c16b3d9827](https://linux-hardware.org/?probe=c16b3d9827) | May 30, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [55680319a1](https://linux-hardware.org/?probe=55680319a1) | May 29, 2020 |
| Biostar       | H110MHC                     | Desktop     | [98d1029698](https://linux-hardware.org/?probe=98d1029698) | May 26, 2020 |
| ASUSTek       | B150M-C                     | Desktop     | [2229b866b3](https://linux-hardware.org/?probe=2229b866b3) | May 26, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Apple         | MacBookPro7,1               | Notebook    | [956da1ac80](https://linux-hardware.org/?probe=956da1ac80) | May 11, 2020 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| Toshiba       | PORTEGE R830                | Notebook    | [08f3e97afe](https://linux-hardware.org/?probe=08f3e97afe) | May 02, 2020 |
| Lenovo        | 3000 G410                   | Notebook    | [2a909aaad5](https://linux-hardware.org/?probe=2a909aaad5) | May 02, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [179a82277c](https://linux-hardware.org/?probe=179a82277c) | May 01, 2020 |
| MSI           | 2A9C                        | Desktop     | [23df26e5de](https://linux-hardware.org/?probe=23df26e5de) | Apr 25, 2020 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [664ac5b85b](https://linux-hardware.org/?probe=664ac5b85b) | Apr 24, 2020 |
| MSI           | Boston                      | Desktop     | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [f11d6eedc7](https://linux-hardware.org/?probe=f11d6eedc7) | Apr 14, 2020 |
| HP            | G72                         | Notebook    | [6272536a26](https://linux-hardware.org/?probe=6272536a26) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [f504649d96](https://linux-hardware.org/?probe=f504649d96) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [3916938374](https://linux-hardware.org/?probe=3916938374) | Apr 11, 2020 |
| Gigabyte      | Z87-HD3                     | Desktop     | [52a7dab5ac](https://linux-hardware.org/?probe=52a7dab5ac) | Apr 09, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [9c72670aa1](https://linux-hardware.org/?probe=9c72670aa1) | Apr 05, 2020 |
| Google        | Eve                         | Notebook    | [17c248ca99](https://linux-hardware.org/?probe=17c248ca99) | Apr 04, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [37fb7cae94](https://linux-hardware.org/?probe=37fb7cae94) | Mar 30, 2020 |
| MSI           | B360M FIRE                  | Desktop     | [8bb021d2a6](https://linux-hardware.org/?probe=8bb021d2a6) | Mar 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [18b565a861](https://linux-hardware.org/?probe=18b565a861) | Mar 26, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [abce376627](https://linux-hardware.org/?probe=abce376627) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e6860a26ae](https://linux-hardware.org/?probe=e6860a26ae) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [5f2e14b65b](https://linux-hardware.org/?probe=5f2e14b65b) | Mar 16, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [1bcf8a4701](https://linux-hardware.org/?probe=1bcf8a4701) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [bd55777a4f](https://linux-hardware.org/?probe=bd55777a4f) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [137262daa3](https://linux-hardware.org/?probe=137262daa3) | Mar 05, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [597092ba51](https://linux-hardware.org/?probe=597092ba51) | Feb 28, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [71fc35ceea](https://linux-hardware.org/?probe=71fc35ceea) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [047acafb1a](https://linux-hardware.org/?probe=047acafb1a) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e8315b1469](https://linux-hardware.org/?probe=e8315b1469) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [04e5b85d84](https://linux-hardware.org/?probe=04e5b85d84) | Feb 28, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [310ae04477](https://linux-hardware.org/?probe=310ae04477) | Feb 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [046814376c](https://linux-hardware.org/?probe=046814376c) | Feb 20, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a417965167](https://linux-hardware.org/?probe=a417965167) | Feb 19, 2020 |
| Intel         | DH77DF AAG40293-301         | Desktop     | [ac00169b1c](https://linux-hardware.org/?probe=ac00169b1c) | Feb 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [cef9a00862](https://linux-hardware.org/?probe=cef9a00862) | Feb 12, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [dcc65f9ee3](https://linux-hardware.org/?probe=dcc65f9ee3) | Feb 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [900a11f8b3](https://linux-hardware.org/?probe=900a11f8b3) | Feb 10, 2020 |
| MSI           | GS73VR 7RG                  | Notebook    | [fbdf43d1d6](https://linux-hardware.org/?probe=fbdf43d1d6) | Feb 04, 2020 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [20d5a3bd6a](https://linux-hardware.org/?probe=20d5a3bd6a) | Feb 01, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cf4dbec684](https://linux-hardware.org/?probe=cf4dbec684) | Feb 01, 2020 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Gigabyte      | P55A-UD3                    | Desktop     | [7168fd0137](https://linux-hardware.org/?probe=7168fd0137) | Jan 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [1007637420](https://linux-hardware.org/?probe=1007637420) | Dec 31, 2019 |
| Unknown       | Unknown                     | Notebook    | [bb58a92938](https://linux-hardware.org/?probe=bb58a92938) | Dec 31, 2019 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [b2d6dabaa7](https://linux-hardware.org/?probe=b2d6dabaa7) | Dec 23, 2019 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [e3b6ce369a](https://linux-hardware.org/?probe=e3b6ce369a) | Dec 23, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [0f39165d62](https://linux-hardware.org/?probe=0f39165d62) | Dec 06, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [816ad4feea](https://linux-hardware.org/?probe=816ad4feea) | Dec 06, 2019 |
| ASUSTek       | X556URK                     | Notebook    | [78f15ad5f0](https://linux-hardware.org/?probe=78f15ad5f0) | Nov 30, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [49e2cab57b](https://linux-hardware.org/?probe=49e2cab57b) | Nov 28, 2019 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [042c4b3c5a](https://linux-hardware.org/?probe=042c4b3c5a) | Nov 22, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [f63dcc4fc8](https://linux-hardware.org/?probe=f63dcc4fc8) | Nov 07, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [15f84fa3f2](https://linux-hardware.org/?probe=15f84fa3f2) | Oct 26, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3497939f58](https://linux-hardware.org/?probe=3497939f58) | Oct 18, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a04ed98be8](https://linux-hardware.org/?probe=a04ed98be8) | Oct 18, 2019 |
| CompuLab      | Airtop                      | Mini pc     | [ff3ce414e4](https://linux-hardware.org/?probe=ff3ce414e4) | Oct 16, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [b2ebcf2c70](https://linux-hardware.org/?probe=b2ebcf2c70) | Oct 10, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [43a5e168a1](https://linux-hardware.org/?probe=43a5e168a1) | Oct 10, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [3392a03f3c](https://linux-hardware.org/?probe=3392a03f3c) | Oct 03, 2019 |
| Unknown       | Unknown                     | Notebook    | [f8f1207d2d](https://linux-hardware.org/?probe=f8f1207d2d) | Sep 29, 2019 |
| Unknown       | Unknown                     | Notebook    | [d19b3f1330](https://linux-hardware.org/?probe=d19b3f1330) | Sep 28, 2019 |
| Unknown       | Unknown                     | Notebook    | [a6d4347345](https://linux-hardware.org/?probe=a6d4347345) | Sep 28, 2019 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [4302e84025](https://linux-hardware.org/?probe=4302e84025) | Sep 24, 2019 |
| Acer          | Aspire S3-371               | Notebook    | [5086f9ddaa](https://linux-hardware.org/?probe=5086f9ddaa) | Sep 07, 2019 |
| Acer          | Aspire S3-371               | Notebook    | [aa8140a178](https://linux-hardware.org/?probe=aa8140a178) | Sep 03, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [e8ccb234ed](https://linux-hardware.org/?probe=e8ccb234ed) | Aug 30, 2019 |
| ASRock        | B75M R2.0                   | Desktop     | [1479826c17](https://linux-hardware.org/?probe=1479826c17) | Aug 28, 2019 |
| Hardkernel    | ODROID-H2                   | Desktop     | [26d6c60ad5](https://linux-hardware.org/?probe=26d6c60ad5) | Jul 06, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [ea2ad2bc4d](https://linux-hardware.org/?probe=ea2ad2bc4d) | Jun 05, 2019 |
| ASUSTek       | TUF GAMING FX504GM_FX80G... | Notebook    | [7e9553ea70](https://linux-hardware.org/?probe=7e9553ea70) | Jun 03, 2019 |
| Lenovo        | ThinkPad T430 2342AG4       | Notebook    | [cf7413e712](https://linux-hardware.org/?probe=cf7413e712) | May 31, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [e8a5c28644](https://linux-hardware.org/?probe=e8a5c28644) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [b67f52c0c2](https://linux-hardware.org/?probe=b67f52c0c2) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [c408ceb62e](https://linux-hardware.org/?probe=c408ceb62e) | May 29, 2019 |
| Dell          | Latitude E4310              | Notebook    | [134afc5b6b](https://linux-hardware.org/?probe=134afc5b6b) | May 08, 2019 |
| Lenovo        | ThinkPad T520 4242BC5       | Notebook    | [977c44b97a](https://linux-hardware.org/?probe=977c44b97a) | Apr 29, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | Notebook    | [5801835e32](https://linux-hardware.org/?probe=5801835e32) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | Notebook    | [0f4999f205](https://linux-hardware.org/?probe=0f4999f205) | Apr 27, 2019 |
| Dell          | 0CRH6C A01                  | Desktop     | [23dcf2aff6](https://linux-hardware.org/?probe=23dcf2aff6) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [61bb547684](https://linux-hardware.org/?probe=61bb547684) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [8549b6dfd8](https://linux-hardware.org/?probe=8549b6dfd8) | Apr 08, 2019 |
| Unknown       | A11-COMPUTER                | Notebook    | [fae06bb10f](https://linux-hardware.org/?probe=fae06bb10f) | Mar 28, 2019 |
| Unknown       | A11-COMPUTER                | Notebook    | [427daf4d4e](https://linux-hardware.org/?probe=427daf4d4e) | Mar 28, 2019 |
| Lenovo        | ThinkPad W530 24384KU       | Notebook    | [2064d92892](https://linux-hardware.org/?probe=2064d92892) | Dec 12, 2018 |
| Dell          | XPS 13 9350                 | Notebook    | [6fb539c340](https://linux-hardware.org/?probe=6fb539c340) | Oct 29, 2018 |
| ASRock        | Z270 Killer SLI             | Desktop     | [a03ea38833](https://linux-hardware.org/?probe=a03ea38833) | Jul 06, 2018 |
| HP            | ProBook 4540s               | Notebook    | [ace9a95fb7](https://linux-hardware.org/?probe=ace9a95fb7) | May 09, 2018 |
| HP            | ProBook 4540s               | Notebook    | [8f50260d94](https://linux-hardware.org/?probe=8f50260d94) | May 09, 2018 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [17f0958960](https://linux-hardware.org/?probe=17f0958960) | Oct 06, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hong_Kong/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 54        | 10.63%  |
| Ubuntu 22.04        | 53        | 10.43%  |
| Arch Rolling        | 30        | 5.91%   |
| Ubuntu 18.04        | 23        | 4.53%   |
| Debian 11           | 16        | 3.15%   |
| Pop!_OS 22.04       | 13        | 2.56%   |
| OpenMandriva 4.2    | 13        | 2.56%   |
| ArcoLinux Rolling   | 11        | 2.17%   |
| Arch                | 11        | 2.17%   |
| Fedora 37           | 10        | 1.97%   |
| antiX 21            | 10        | 1.97%   |
| Ubuntu 16.04        | 9         | 1.77%   |
| Debian 12           | 9         | 1.77%   |
| Ubuntu 19.10        | 8         | 1.57%   |
| OpenMandriva 4.3    | 7         | 1.38%   |
| KDE neon 20.04      | 7         | 1.38%   |
| EndeavourOS Rolling | 7         | 1.38%   |
| Ubuntu 23.04        | 6         | 1.18%   |
| Ubuntu 20.10        | 6         | 1.18%   |
| Gentoo 2.7          | 6         | 1.18%   |
| Fedora 35           | 6         | 1.18%   |
| Fedora 32           | 6         | 1.18%   |
| OpenMandriva 23.03  | 5         | 0.98%   |
| Fedora 38           | 5         | 0.98%   |
| Fedora 36           | 5         | 0.98%   |
| Ubuntu 22.10        | 4         | 0.79%   |
| Ubuntu 21.10        | 4         | 0.79%   |
| Ubuntu 21.04        | 4         | 0.79%   |
| Ubuntu 19.04        | 4         | 0.79%   |
| Pop!_OS 20.10       | 4         | 0.79%   |
| OpenMandriva 23.01  | 4         | 0.79%   |
| Linux Mint 20       | 4         | 0.79%   |
| Fedora 33           | 4         | 0.79%   |
| Ubuntu 23.10        | 3         | 0.59%   |
| OpenMandriva 4.50   | 3         | 0.59%   |
| Linux Mint 20.3     | 3         | 0.59%   |
| Kylin V10           | 3         | 0.59%   |
| Gentoo 2.8          | 3         | 0.59%   |
| Fedora 39           | 3         | 0.59%   |
| Elementary 5.1.7    | 3         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 170       | 34.91%  |
| Fedora        | 42        | 8.62%   |
| Arch          | 41        | 8.42%   |
| OpenMandriva  | 35        | 7.19%   |
| Debian        | 27        | 5.54%   |
| Pop!_OS       | 22        | 4.52%   |
| Manjaro       | 14        | 2.87%   |
| Linux Mint    | 12        | 2.46%   |
| ArcoLinux     | 11        | 2.26%   |
| Gentoo        | 10        | 2.05%   |
| antiX         | 10        | 2.05%   |
| SteamOS       | 8         | 1.64%   |
| EndeavourOS   | 8         | 1.64%   |
| KDE neon      | 7         | 1.44%   |
| Clear Linux   | 6         | 1.23%   |
| Kubuntu       | 5         | 1.03%   |
| Elementary    | 5         | 1.03%   |
| Zorin         | 4         | 0.82%   |
| Ubuntu Unity  | 3         | 0.62%   |
| Ubuntu MATE   | 3         | 0.62%   |
| Slackware     | 3         | 0.62%   |
| ROSA          | 3         | 0.62%   |
| openSUSE      | 3         | 0.62%   |
| Kylin         | 3         | 0.62%   |
| Kali          | 3         | 0.62%   |
| Chrome OS     | 3         | 0.62%   |
| CentOS        | 3         | 0.62%   |
| Xubuntu       | 2         | 0.41%   |
| PostmarketOS  | 2         | 0.41%   |
| Parrot        | 2         | 0.41%   |
| Nobara        | 2         | 0.41%   |
| Deepin        | 2         | 0.41%   |
| Ultramarine   | 1         | 0.21%   |
| UbuntuDDE     | 1         | 0.21%   |
| Ubuntu Budgie | 1         | 0.21%   |
| Rocky Linux   | 1         | 0.21%   |
| Raspbian      | 1         | 0.21%   |
| PCLinuxOS     | 1         | 0.21%   |
| Oracle Linux  | 1         | 0.21%   |
| NixOS         | 1         | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002  | 12        | 2.14%   |
| 6.2.0-26-generic          | 9         | 1.61%   |
| 5.4.0-42-generic          | 9         | 1.61%   |
| 4.9.0-279-antix.1-486-smp | 9         | 1.61%   |
| 5.16.7-desktop-1omv4003   | 7         | 1.25%   |
| 5.15.0-46-generic         | 6         | 1.07%   |
| 4.15.0-142-generic        | 6         | 1.07%   |
| 6.2.6-desktop-1omv2390    | 5         | 0.89%   |
| 6.5.0-14-generic          | 4         | 0.71%   |
| 6.2.0-20-generic          | 4         | 0.71%   |
| 6.1.1-desktop-1omv2290    | 4         | 0.71%   |
| 5.15.0-58-generic         | 4         | 0.71%   |
| 5.15.0-52-generic         | 4         | 0.71%   |
| 5.13.0-39-generic         | 4         | 0.71%   |
| 5.13.0-35-generic         | 4         | 0.71%   |
| 6.3.6-arch1-1             | 3         | 0.54%   |
| 6.2.0-39-generic          | 3         | 0.54%   |
| 6.2.0-33-generic          | 3         | 0.54%   |
| 5.8.0-7630-generic        | 3         | 0.54%   |
| 5.8.0-55-generic          | 3         | 0.54%   |
| 5.8.0-43-generic          | 3         | 0.54%   |
| 5.4.0-48-generic          | 3         | 0.54%   |
| 5.4.0-33-generic          | 3         | 0.54%   |
| 5.4.0-28-generic          | 3         | 0.54%   |
| 5.4.0-26-generic          | 3         | 0.54%   |
| 5.3.0-46-generic          | 3         | 0.54%   |
| 5.19.0-32-generic         | 3         | 0.54%   |
| 5.15.0-47-generic         | 3         | 0.54%   |
| 5.11.0-37-generic         | 3         | 0.54%   |
| 4.19.49+                  | 3         | 0.54%   |
| 6.7.0-zen3-1.1-zen        | 2         | 0.36%   |
| 6.6.7-arch1-1             | 2         | 0.36%   |
| 6.6.2-desktop-1omv2390    | 2         | 0.36%   |
| 6.5.5-arch1-1             | 2         | 0.36%   |
| 6.5.0-15-generic          | 2         | 0.36%   |
| 6.4.11-desktop-1omv2390   | 2         | 0.36%   |
| 6.2.8-200.fc37.x86_64     | 2         | 0.36%   |
| 6.2.0-36-generic          | 2         | 0.36%   |
| 6.2.0-34-generic          | 2         | 0.36%   |
| 6.2.0-32-generic          | 2         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 7.69%   |
| 5.15.0  | 35        | 6.57%   |
| 6.2.0   | 28        | 5.25%   |
| 5.13.0  | 23        | 4.32%   |
| 5.8.0   | 22        | 4.13%   |
| 5.19.0  | 22        | 4.13%   |
| 4.15.0  | 20        | 3.75%   |
| 5.11.0  | 15        | 2.81%   |
| 5.3.0   | 12        | 2.25%   |
| 5.10.14 | 12        | 2.25%   |
| 6.1.0   | 11        | 2.06%   |
| 5.10.0  | 11        | 2.06%   |
| 5.0.0   | 10        | 1.88%   |
| 4.9.0   | 10        | 1.88%   |
| 6.5.0   | 7         | 1.31%   |
| 6.2.6   | 7         | 1.31%   |
| 6.1.1   | 7         | 1.31%   |
| 5.16.7  | 7         | 1.31%   |
| 6.0.0   | 5         | 0.94%   |
| 4.18.0  | 5         | 0.94%   |
| 5.17.5  | 4         | 0.75%   |
| 6.7.0   | 3         | 0.56%   |
| 6.6.7   | 3         | 0.56%   |
| 6.6.6   | 3         | 0.56%   |
| 6.5.6   | 3         | 0.56%   |
| 6.4.2   | 3         | 0.56%   |
| 6.4.11  | 3         | 0.56%   |
| 6.3.6   | 3         | 0.56%   |
| 6.2.8   | 3         | 0.56%   |
| 6.0.12  | 3         | 0.56%   |
| 5.14.0  | 3         | 0.56%   |
| 4.19.49 | 3         | 0.56%   |
| 6.6.4   | 2         | 0.38%   |
| 6.6.2   | 2         | 0.38%   |
| 6.6.11  | 2         | 0.38%   |
| 6.6.10  | 2         | 0.38%   |
| 6.5.5   | 2         | 0.38%   |
| 6.5.3   | 2         | 0.38%   |
| 6.5.12  | 2         | 0.38%   |
| 6.4.7   | 2         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 48        | 9.21%   |
| 6.2     | 42        | 8.06%   |
| 5.4     | 41        | 7.87%   |
| 6.1     | 35        | 6.72%   |
| 5.10    | 35        | 6.72%   |
| 5.19    | 32        | 6.14%   |
| 5.8     | 28        | 5.37%   |
| 5.13    | 27        | 5.18%   |
| 5.11    | 22        | 4.22%   |
| 4.15    | 20        | 3.84%   |
| 6.5     | 17        | 3.26%   |
| 6.6     | 15        | 2.88%   |
| 6.4     | 15        | 2.88%   |
| 5.3     | 15        | 2.88%   |
| 5.16    | 14        | 2.69%   |
| 4.9     | 14        | 2.69%   |
| 5.17    | 13        | 2.5%    |
| 6.0     | 11        | 2.11%   |
| 5.9     | 10        | 1.92%   |
| 5.0     | 10        | 1.92%   |
| 5.14    | 9         | 1.73%   |
| 6.3     | 7         | 1.34%   |
| 5.18    | 7         | 1.34%   |
| 5.7     | 6         | 1.15%   |
| 4.18    | 6         | 1.15%   |
| 6.7     | 4         | 0.77%   |
| 5.6     | 3         | 0.58%   |
| 5.5     | 3         | 0.58%   |
| 5.12    | 3         | 0.58%   |
| 4.19    | 3         | 0.58%   |
| 4.4     | 2         | 0.38%   |
| 6.8     | 1         | 0.19%   |
| 4.20    | 1         | 0.19%   |
| 4.17    | 1         | 0.19%   |
| 3.10    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 444       | 93.87%  |
| i686    | 14        | 2.96%   |
| aarch64 | 12        | 2.54%   |
| riscv64 | 1         | 0.21%   |
| i586    | 1         | 0.21%   |
| armv7l  | 1         | 0.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 228       | 46.44%  |
| KDE5          | 102       | 20.77%  |
| Unknown       | 76        | 15.48%  |
| XFCE          | 19        | 3.87%   |
| X-Cinnamon    | 10        | 2.04%   |
| KDE           | 10        | 2.04%   |
| i3            | 7         | 1.43%   |
| Deepin        | 6         | 1.22%   |
| MATE          | 5         | 1.02%   |
| Pantheon      | 4         | 0.81%   |
| sway          | 3         | 0.61%   |
| Unity         | 2         | 0.41%   |
| Openbox       | 2         | 0.41%   |
| LXQt          | 2         | 0.41%   |
| LXDE          | 2         | 0.41%   |
| icewm         | 2         | 0.41%   |
| Hyprland      | 2         | 0.41%   |
| dwm           | 2         | 0.41%   |
| KDE6          | 1         | 0.2%    |
| KDE4          | 1         | 0.2%    |
| GNOME Classic | 1         | 0.2%    |
| fvwm          | 1         | 0.2%    |
| Cinnamon      | 1         | 0.2%    |
| Budgie        | 1         | 0.2%    |
| awesome       | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 336       | 68.29%  |
| Wayland | 110       | 22.36%  |
| Tty     | 23        | 4.67%   |
| Unknown | 23        | 4.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 189       | 38.57%  |
| SDDM    | 93        | 18.98%  |
| GDM3    | 87        | 17.76%  |
| GDM     | 64        | 13.06%  |
| LightDM | 44        | 8.98%   |
| TDM     | 7         | 1.43%   |
| Ly      | 2         | 0.41%   |
| XDM     | 1         | 0.2%    |
| LXDM    | 1         | 0.2%    |
| KDM     | 1         | 0.2%    |
| GREETD  | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 195       | 39.47%  |
| en_HK   | 122       | 24.7%   |
| zh_CN   | 68        | 13.77%  |
| Unknown | 35        | 7.09%   |
| zh_TW   | 24        | 4.86%   |
| zh_HK   | 18        | 3.64%   |
| en_GB   | 13        | 2.63%   |
| C       | 11        | 2.23%   |
| en_AU   | 3         | 0.61%   |
| zh_SG   | 1         | 0.2%    |
| it_IT   | 1         | 0.2%    |
| en_ZA   | 1         | 0.2%    |
| de_DE   | 1         | 0.2%    |
| C.UTF8  | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 316       | 65.83%  |
| BIOS | 164       | 34.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 321       | 66.05%  |
| Btrfs   | 71        | 14.61%  |
| Overlay | 35        | 7.2%    |
| Tmpfs   | 26        | 5.35%   |
| Xfs     | 11        | 2.26%   |
| Unknown | 9         | 1.85%   |
| Zfs     | 7         | 1.44%   |
| Ext2    | 3         | 0.62%   |
| Ext3    | 2         | 0.41%   |
| F2fs    | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 276       | 57.38%  |
| Unknown | 165       | 34.3%   |
| MBR     | 40        | 8.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 410       | 84.54%  |
| Yes       | 75        | 15.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 310       | 64.05%  |
| Yes       | 174       | 35.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 98        | 20.72%  |
| ASUSTek Computer                     | 70        | 14.8%   |
| Dell                                 | 40        | 8.46%   |
| Hewlett-Packard                      | 35        | 7.4%    |
| MSI                                  | 33        | 6.98%   |
| Gigabyte Technology                  | 30        | 6.34%   |
| Unknown                              | 20        | 4.23%   |
| ASRock                               | 19        | 4.02%   |
| Fujitsu                              | 13        | 2.75%   |
| Acer                                 | 12        | 2.54%   |
| Intel                                | 11        | 2.33%   |
| Apple                                | 10        | 2.11%   |
| HUAWEI                               | 8         | 1.69%   |
| Samsung Electronics                  | 5         | 1.06%   |
| Chuwi                                | 5         | 1.06%   |
| AMI                                  | 5         | 1.06%   |
| Raspberry Pi Foundation              | 4         | 0.85%   |
| GPD                                  | 4         | 0.85%   |
| Supermicro                           | 3         | 0.63%   |
| ONE-NETBOOK                          | 3         | 0.63%   |
| Valve                                | 2         | 0.42%   |
| Toshiba                              | 2         | 0.42%   |
| Timi                                 | 2         | 0.42%   |
| Notebook                             | 2         | 0.42%   |
| KOHJINSHA                            | 2         | 0.42%   |
| IBM                                  | 2         | 0.42%   |
| Google                               | 2         | 0.42%   |
| AZW                                  | 2         | 0.42%   |
| AOKZOE                               | 2         | 0.42%   |
| ZOTAC                                | 1         | 0.21%   |
| Soyo                                 | 1         | 0.21%   |
| Sony                                 | 1         | 0.21%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.21%   |
| Seco                                 | 1         | 0.21%   |
| Schenker                             | 1         | 0.21%   |
| Panasonic                            | 1         | 0.21%   |
| Orange Pi                            | 1         | 0.21%   |
| Nvidia                               | 1         | 0.21%   |
| METAPHYUNI                           | 1         | 0.21%   |
| MeLE                                 | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 21        | 4.44%   |
| Intel SKYBAY                        | 4         | 0.85%   |
| ASUS All Series                     | 4         | 0.85%   |
| MSI MS-7C94                         | 3         | 0.63%   |
| Lenovo LOQ 15IRH8 82XV              | 3         | 0.63%   |
| Lenovo Legion R7000 2020 82B6       | 3         | 0.63%   |
| Chuwi HeroBook Pro                  | 3         | 0.63%   |
| ASUS H110I-PLUS                     | 3         | 0.63%   |
| AMI Aptio CRB                       | 3         | 0.63%   |
| Valve Jupiter                       | 2         | 0.42%   |
| RPi Raspberry Pi                    | 2         | 0.42%   |
| MSI MS-7D42                         | 2         | 0.42%   |
| MSI MS-7C02                         | 2         | 0.42%   |
| MSI MS-7B93                         | 2         | 0.42%   |
| MSI MS-7B89                         | 2         | 0.42%   |
| Lenovo XiaoXinPro 14ITL 2021 82GH   | 2         | 0.42%   |
| Lenovo ThinkBook 14 G4+ ARA 21D0    | 2         | 0.42%   |
| Lenovo G770 20089                   | 2         | 0.42%   |
| IBM 260921H                         | 2         | 0.42%   |
| HUAWEI KPRC-WX0                     | 2         | 0.42%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC    | 2         | 0.42%   |
| HP ProDesk 600 G1 SFF               | 2         | 0.42%   |
| HP Pavilion Gaming Laptop 15-ec2xxx | 2         | 0.42%   |
| HP OMEN by Gaming Laptop 16-wf0xxx  | 2         | 0.42%   |
| HP EliteBook 2540p                  | 2         | 0.42%   |
| GPD G1619-04                        | 2         | 0.42%   |
| Gigabyte X570 AORUS ELITE           | 2         | 0.42%   |
| Fujitsu UH-X                        | 2         | 0.42%   |
| Fujitsu LIFEBOOK AH544              | 2         | 0.42%   |
| Fujitsu FMVNU6G1C                   | 2         | 0.42%   |
| Dell XPS 13 9310                    | 2         | 0.42%   |
| Dell Inspiron 5580                  | 2         | 0.42%   |
| AZW GTR                             | 2         | 0.42%   |
| ASUS Z8NA-D6                        | 2         | 0.42%   |
| ASUS VM65                           | 2         | 0.42%   |
| ASUS VM62                           | 2         | 0.42%   |
| ASUS TUF Gaming FA506IU_FA506IU     | 2         | 0.42%   |
| ASRock H410M-ITX/ac                 | 2         | 0.42%   |
| ASRock H410M-HDV                    | 2         | 0.42%   |
| Apple MacBookAir6,2                 | 2         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 38        | 8.03%   |
| Unknown                | 21        | 4.44%   |
| Lenovo Legion          | 13        | 2.75%   |
| ASUS ROG               | 13        | 2.75%   |
| Dell XPS               | 10        | 2.11%   |
| Dell Inspiron          | 10        | 2.11%   |
| ASUS TUF               | 9         | 1.9%    |
| ASUS PRIME             | 9         | 1.9%    |
| Lenovo IdeaPad         | 8         | 1.69%   |
| Fujitsu LIFEBOOK       | 8         | 1.69%   |
| Dell Precision         | 7         | 1.48%   |
| Lenovo ThinkBook       | 6         | 1.27%   |
| Dell OptiPlex          | 6         | 1.27%   |
| Lenovo ThinkCentre     | 5         | 1.06%   |
| HP Pavilion            | 5         | 1.06%   |
| Dell Latitude          | 5         | 1.06%   |
| Acer Swift             | 5         | 1.06%   |
| RPi Raspberry          | 4         | 0.85%   |
| Lenovo Yoga            | 4         | 0.85%   |
| Intel SKYBAY           | 4         | 0.85%   |
| ASUS All               | 4         | 0.85%   |
| Acer Aspire            | 4         | 0.85%   |
| ONE-NETBOOK ONEXPLAYER | 3         | 0.63%   |
| MSI MS-7C94            | 3         | 0.63%   |
| Lenovo LOQ             | 3         | 0.63%   |
| HP ZHAN                | 3         | 0.63%   |
| HP ProDesk             | 3         | 0.63%   |
| HP OMEN                | 3         | 0.63%   |
| HP EliteBook           | 3         | 0.63%   |
| Gigabyte X570          | 3         | 0.63%   |
| Chuwi HeroBook         | 3         | 0.63%   |
| ASUS VivoBook          | 3         | 0.63%   |
| ASUS H110I-PLUS        | 3         | 0.63%   |
| AMI Aptio              | 3         | 0.63%   |
| Acer Nitro             | 3         | 0.63%   |
| Valve Jupiter          | 2         | 0.42%   |
| MSI MS-7D42            | 2         | 0.42%   |
| MSI MS-7C02            | 2         | 0.42%   |
| MSI MS-7B93            | 2         | 0.42%   |
| MSI MS-7B89            | 2         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 59        | 12.47%  |
| 2020    | 56        | 11.84%  |
| 2021    | 47        | 9.94%   |
| 2022    | 41        | 8.67%   |
| 2019    | 38        | 8.03%   |
| 2023    | 31        | 6.55%   |
| 2014    | 25        | 5.29%   |
| 2017    | 24        | 5.07%   |
| 2013    | 22        | 4.65%   |
| 2016    | 20        | 4.23%   |
| 2011    | 19        | 4.02%   |
| 2010    | 19        | 4.02%   |
| 2012    | 17        | 3.59%   |
| 2015    | 16        | 3.38%   |
| 2008    | 12        | 2.54%   |
| Unknown | 12        | 2.54%   |
| 2007    | 6         | 1.27%   |
| 2009    | 5         | 1.06%   |
| 1999    | 2         | 0.42%   |
| 2005    | 1         | 0.21%   |
| 2003    | 1         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 238       | 50.32%  |
| Desktop        | 183       | 38.69%  |
| Mini pc        | 15        | 3.17%   |
| Convertible    | 13        | 2.75%   |
| System on chip | 9         | 1.9%    |
| Tablet         | 7         | 1.48%   |
| Server         | 5         | 1.06%   |
| All in one     | 3         | 0.63%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 431       | 90.93%  |
| Enabled  | 43        | 9.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 471       | 99.58%  |
| Yes  | 2         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 106       | 22.13%  |
| 8.01-16.0   | 95        | 19.83%  |
| 32.01-64.0  | 78        | 16.28%  |
| 4.01-8.0    | 73        | 15.24%  |
| 3.01-4.0    | 52        | 10.86%  |
| 64.01-256.0 | 37        | 7.72%   |
| 24.01-32.0  | 14        | 2.92%   |
| 1.01-2.0    | 8         | 1.67%   |
| 0.51-1.0    | 7         | 1.46%   |
| 2.01-3.0    | 6         | 1.25%   |
| 0.01-0.5    | 3         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 129       | 24.9%   |
| 2.01-3.0   | 119       | 22.97%  |
| 4.01-8.0   | 99        | 19.11%  |
| 3.01-4.0   | 73        | 14.09%  |
| 8.01-16.0  | 39        | 7.53%   |
| 0.01-0.5   | 23        | 4.44%   |
| 0.51-1.0   | 17        | 3.28%   |
| 16.01-24.0 | 12        | 2.32%   |
| 32.01-64.0 | 4         | 0.77%   |
| 24.01-32.0 | 2         | 0.39%   |
| Unknown    | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 264       | 53.66%  |
| 2      | 144       | 29.27%  |
| 3      | 49        | 9.96%   |
| 5      | 12        | 2.44%   |
| 4      | 9         | 1.83%   |
| 0      | 7         | 1.42%   |
| 6      | 3         | 0.61%   |
| 9      | 2         | 0.41%   |
| 11     | 1         | 0.2%    |
| 7      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 385       | 80.88%  |
| Yes       | 91        | 19.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 378       | 79.41%  |
| No        | 98        | 20.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 375       | 78.29%  |
| No        | 104       | 21.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 321       | 66.74%  |
| No        | 160       | 33.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Hong Kong | 473       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Central           | 269       | 53.8%   |
| Kowloon           | 30        | 6%      |
| Hong Kong         | 20        | 4%      |
| Wanchai           | 19        | 3.8%    |
| Shatin            | 16        | 3.2%    |
| Tuen Mun          | 13        | 2.6%    |
| Tseung Kwan O     | 13        | 2.6%    |
| Tsuen Wan         | 8         | 1.6%    |
| Tai Po            | 7         | 1.4%    |
| Hung Hom          | 7         | 1.4%    |
| Yuen Long         | 6         | 1.2%    |
| Tung Chung        | 6         | 1.2%    |
| Sai Kung          | 6         | 1.2%    |
| Ngau Wu Tok       | 6         | 1.2%    |
| Tsimshatsui       | 5         | 1%      |
| To Kwa Wan        | 4         | 0.8%    |
| Quarry Bay        | 3         | 0.6%    |
| Mong Kok          | 3         | 0.6%    |
| Man Kok           | 3         | 0.6%    |
| Ma On Shan Tsuen  | 3         | 0.6%    |
| Kwai Chung        | 3         | 0.6%    |
| Kowloon Bay       | 3         | 0.6%    |
| Ho Man Tin        | 3         | 0.6%    |
| Fanling           | 3         | 0.6%    |
| Chai Wan          | 3         | 0.6%    |
| Yuen Long San Hui | 2         | 0.4%    |
| Wong Tai Sin      | 2         | 0.4%    |
| Tai Wan To        | 2         | 0.4%    |
| Sheung Shui       | 2         | 0.4%    |
| Sha Tin Wai       | 2         | 0.4%    |
| North Point       | 2         | 0.4%    |
| Ma On Shan        | 2         | 0.4%    |
| Kwun Hang         | 2         | 0.4%    |
| Kwu Tung          | 2         | 0.4%    |
| Discovery Bay     | 2         | 0.4%    |
| Cheung Sha Lan    | 2         | 0.4%    |
| Yau Tsim Mong     | 1         | 0.2%    |
| Tuen Mun San Hui  | 1         | 0.2%    |
| Tin Shui Wai      | 1         | 0.2%    |
| Tai Wan           | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 120       | 154    | 16.17%  |
| WDC                         | 83        | 121    | 11.19%  |
| Seagate                     | 69        | 95     | 9.3%    |
| Sandisk                     | 47        | 52     | 6.33%   |
| Toshiba                     | 36        | 49     | 4.85%   |
| Unknown                     | 32        | 37     | 4.31%   |
| Kingston                    | 32        | 38     | 4.31%   |
| Intel                       | 21        | 37     | 2.83%   |
| Crucial                     | 20        | 35     | 2.7%    |
| Hitachi                     | 19        | 28     | 2.56%   |
| SK hynix                    | 18        | 25     | 2.43%   |
| A-DATA Technology           | 17        | 23     | 2.29%   |
| HGST                        | 14        | 16     | 1.89%   |
| Micron Technology           | 13        | 14     | 1.75%   |
| KIOXIA                      | 12        | 13     | 1.62%   |
| Unknown                     | 11        | 11     | 1.48%   |
| Silicon Motion              | 9         | 12     | 1.21%   |
| Apple                       | 9         | 22     | 1.21%   |
| Fujitsu                     | 8         | 15     | 1.08%   |
| Phison                      | 7         | 10     | 0.94%   |
| MAXIO Technology (Hangzhou) | 7         | 8      | 0.94%   |
| Transcend                   | 6         | 7      | 0.81%   |
| LITEON                      | 6         | 6      | 0.81%   |
| JMicron Technology          | 6         | 10     | 0.81%   |
| ZHITAI                      | 5         | 7      | 0.67%   |
| Plextor                     | 5         | 6      | 0.67%   |
| Hikvision                   | 5         | 5      | 0.67%   |
| China                       | 5         | 7      | 0.67%   |
| Netac                       | 4         | 4      | 0.54%   |
| HS-SSD-C100                 | 4         | 5      | 0.54%   |
| Biwin Storage Technology    | 4         | 4      | 0.54%   |
| BIWIN                       | 4         | 4      | 0.54%   |
| Yangtze Memory Technologies | 3         | 3      | 0.4%    |
| Team                        | 3         | 3      | 0.4%    |
| SPCC                        | 3         | 3      | 0.4%    |
| Gigabyte Technology         | 3         | 6      | 0.4%    |
| DOGGO                       | 3         | 3      | 0.4%    |
| Yangtze Memory              | 2         | 2      | 0.27%   |
| TO Exter                    | 2         | 2      | 0.27%   |
| ShiJi                       | 2         | 9      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 11        | 1.38%   |
| Unknown                                            | 11        | 1.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 8         | 1.01%   |
| Unknown MMC Card  64GB                             | 6         | 0.75%   |
| Toshiba DT01ACA100 1TB                             | 6         | 0.75%   |
| Samsung SSD 860 EVO 1TB                            | 6         | 0.75%   |
| Samsung NVMe SSD Drive 512GB                       | 6         | 0.75%   |
| Seagate ST500DM002-1BD142 500GB                    | 5         | 0.63%   |
| SanDisk NVMe SSD Drive 1TB                         | 5         | 0.63%   |
| Kingston SA400S37480G 480GB SSD                    | 5         | 0.63%   |
| JMicron Generic 8GB                                | 5         | 0.63%   |
| Fujitsu F300 480GB                                 | 5         | 0.63%   |
| Crucial CT500MX500SSD1 500GB                       | 5         | 0.63%   |
| A-DATA SP550 240GB SSD                             | 5         | 0.63%   |
| WDC WDS100T2B0C-00PXH0 1TB                         | 4         | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB                           | 4         | 0.5%    |
| Unknown MMC Card  32GB                             | 4         | 0.5%    |
| Unknown MMC Card  128GB                            | 4         | 0.5%    |
| Toshiba DT01ACA050 500GB                           | 4         | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB                     | 4         | 0.5%    |
| SanDisk NVMe SSD Drive 2TB                         | 4         | 0.5%    |
| Samsung SSD 980 1TB                                | 4         | 0.5%    |
| Samsung NVMe SSD Drive 1024GB                      | 4         | 0.5%    |
| Samsung MZVL2512HCJQ-00BL7 512GB                   | 4         | 0.5%    |
| Kingston SA400S37960G 960GB SSD                    | 4         | 0.5%    |
| Kingston SA400S37120G 120GB SSD                    | 4         | 0.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 3         | 0.38%   |
| WDC WD30EZRX-00D8PB0 3TB                           | 3         | 0.38%   |
| Unknown SD32G  32GB                                | 3         | 0.38%   |
| Toshiba MQ04ABF100 1TB                             | 3         | 0.38%   |
| Toshiba DT01ACA300 3TB                             | 3         | 0.38%   |
| Toshiba DT01ACA200 2TB                             | 3         | 0.38%   |
| Seagate ST4000DM004-2CV104 4TB                     | 3         | 0.38%   |
| Seagate ST3500418AS 500GB                          | 3         | 0.38%   |
| Seagate ST3500413AS 500GB                          | 3         | 0.38%   |
| Seagate ST2000LM007-1R8174 2TB                     | 3         | 0.38%   |
| Seagate ST2000DM008-2FR102 2TB                     | 3         | 0.38%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 3         | 0.38%   |
| SanDisk NVMe SSD Drive 512GB                       | 3         | 0.38%   |
| Samsung SSD 970 EVO Plus 2TB                       | 3         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 68        | 94     | 33.17%  |
| WDC                 | 54        | 85     | 26.34%  |
| Toshiba             | 31        | 44     | 15.12%  |
| Hitachi             | 19        | 28     | 9.27%   |
| HGST                | 14        | 16     | 6.83%   |
| JMicron Technology  | 6         | 10     | 2.93%   |
| TO Exter            | 2         | 2      | 0.98%   |
| Fujitsu             | 2         | 2      | 0.98%   |
| External            | 2         | 2      | 0.98%   |
| Apple               | 2         | 2      | 0.98%   |
| Unknown (CF)        | 1         | 1      | 0.49%   |
| Unknown             | 1         | 1      | 0.49%   |
| Samsung Electronics | 1         | 1      | 0.49%   |
| Maxtor              | 1         | 1      | 0.49%   |
| HGST HTS            | 1         | 1      | 0.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 51     | 18.13%  |
| Kingston            | 22        | 27     | 11.4%   |
| Crucial             | 15        | 30     | 7.77%   |
| A-DATA Technology   | 13        | 19     | 6.74%   |
| WDC                 | 12        | 12     | 6.22%   |
| SanDisk             | 8         | 8      | 4.15%   |
| Intel               | 7         | 12     | 3.63%   |
| Transcend           | 6         | 7      | 3.11%   |
| LITEON              | 5         | 5      | 2.59%   |
| Fujitsu             | 5         | 12     | 2.59%   |
| China               | 5         | 7      | 2.59%   |
| Plextor             | 4         | 5      | 2.07%   |
| Netac               | 4         | 4      | 2.07%   |
| Apple               | 4         | 5      | 2.07%   |
| Team                | 3         | 3      | 1.55%   |
| SK hynix            | 3         | 7      | 1.55%   |
| DOGGO               | 3         | 3      | 1.55%   |
| ZHITAI              | 2         | 2      | 1.04%   |
| SPCC                | 2         | 2      | 1.04%   |
| ShiJi               | 2         | 9      | 1.04%   |
| Micron Technology   | 2         | 3      | 1.04%   |
| Lexar               | 2         | 2      | 1.04%   |
| HS-SSD-C100         | 2         | 2      | 1.04%   |
| Hikvision           | 2         | 2      | 1.04%   |
| BIWIN               | 2         | 2      | 1.04%   |
| Apacer              | 2         | 7      | 1.04%   |
| AGI                 | 2         | 2      | 1.04%   |
| Verbatim            | 1         | 2      | 0.52%   |
| USB3.0              | 1         | 1      | 0.52%   |
| tigo                | 1         | 1      | 0.52%   |
| RECADATA            | 1         | 1      | 0.52%   |
| Ramsta              | 1         | 1      | 0.52%   |
| PNY                 | 1         | 1      | 0.52%   |
| Patriot             | 1         | 1      | 0.52%   |
| OCZ                 | 1         | 1      | 0.52%   |
| NGFF                | 1         | 1      | 0.52%   |
| MAXSUN              | 1         | 1      | 0.52%   |
| KLEVV               | 1         | 1      | 0.52%   |
| KingFast            | 1         | 1      | 0.52%   |
| Dogfish             | 1         | 1      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 247       | 364    | 38.06%  |
| HDD     | 177       | 290    | 27.27%  |
| SSD     | 169       | 270    | 26.04%  |
| MMC     | 28        | 33     | 4.31%   |
| Unknown | 28        | 31     | 4.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 274       | 540    | 46.44%  |
| NVMe | 247       | 360    | 41.86%  |
| SAS  | 41        | 55     | 6.95%   |
| MMC  | 28        | 33     | 4.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 187       | 303    | 53.28%  |
| 0.51-1.0   | 95        | 132    | 27.07%  |
| 1.01-2.0   | 34        | 47     | 9.69%   |
| 3.01-4.0   | 13        | 37     | 3.7%    |
| 2.01-3.0   | 11        | 19     | 3.13%   |
| 4.01-10.0  | 9         | 18     | 2.56%   |
| 10.01-20.0 | 2         | 4      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 116       | 22.97%  |
| 251-500        | 87        | 17.23%  |
| 501-1000       | 71        | 14.06%  |
| 1001-2000      | 49        | 9.7%    |
| 1-20           | 45        | 8.91%   |
| 51-100         | 41        | 8.12%   |
| More than 3000 | 37        | 7.33%   |
| 21-50          | 24        | 4.75%   |
| 2001-3000      | 20        | 3.96%   |
| Unknown        | 15        | 2.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 210       | 40.08%  |
| 21-50          | 65        | 12.4%   |
| 101-250        | 58        | 11.07%  |
| 251-500        | 54        | 10.31%  |
| 51-100         | 50        | 9.54%   |
| 501-1000       | 33        | 6.3%    |
| 1001-2000      | 21        | 4.01%   |
| Unknown        | 15        | 2.86%   |
| 2001-3000      | 10        | 1.91%   |
| More than 3000 | 8         | 1.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 2         | 3      | 4.88%   |
| Seagate ST3500418AS 500GB                    | 2         | 2      | 4.88%   |
| LITEON CV8-8E128-HP 128GB SSD                | 2         | 2      | 4.88%   |
| ZHITAI TiPlus5000 512GB                      | 1         | 1      | 2.44%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 1      | 2.44%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1         | 1      | 2.44%   |
| WDC WD20SPZX-75UA7T0 2TB                     | 1         | 1      | 2.44%   |
| WDC WD10EZEX-60WN4A1 1TB                     | 1         | 1      | 2.44%   |
| WDC WD10EZEX-00RKKA0 1TB                     | 1         | 1      | 2.44%   |
| WDC WD10EALS-00Z8A0 1TB                      | 1         | 2      | 2.44%   |
| Toshiba MK1655GSX 160GB                      | 1         | 1      | 2.44%   |
| Toshiba MK1252GSX 120GB                      | 1         | 1      | 2.44%   |
| Toshiba DT01ACA100 1TB                       | 1         | 1      | 2.44%   |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 2.44%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 2.44%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 2.44%   |
| Seagate ST3250310AS 250GB                    | 1         | 1      | 2.44%   |
| Seagate ST3160815AS 160GB                    | 1         | 1      | 2.44%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB          | 1         | 1      | 2.44%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 860 EVO 1TB          | 1         | 1      | 2.44%   |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB | 1         | 1      | 2.44%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD    | 1         | 1      | 2.44%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 2.44%   |
| Kingston SA400S37480G 480GB SSD              | 1         | 1      | 2.44%   |
| Intel SSDPEKKW128G7 128GB                    | 1         | 1      | 2.44%   |
| Intel SSD 600P Series 256GB                  | 1         | 4      | 2.44%   |
| Hitachi HTS725050A7E630 500GB                | 1         | 1      | 2.44%   |
| Hitachi HTS723216L9A360 160GB                | 1         | 1      | 2.44%   |
| Hitachi HTS542512K9SA00 120GB                | 1         | 1      | 2.44%   |
| Hitachi HTC426040G8CE00 40GB                 | 1         | 1      | 2.44%   |
| HGST TOURO Mobile 1TB                        | 1         | 1      | 2.44%   |
| HGST HTS 541010A9E680 1TB                    | 1         | 1      | 2.44%   |
| DGM SSD 120GB S3-120A                        | 1         | 1      | 2.44%   |
| Crucial CT500MX500SSD1 500GB                 | 1         | 2      | 2.44%   |
| Crucial CT240M500SSD1 240GB                  | 1         | 1      | 2.44%   |
| BIWIN SSD 32GB                               | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 22.5%   |
| WDC                 | 5         | 7      | 12.5%   |
| Hitachi             | 4         | 4      | 10%     |
| Toshiba             | 3         | 3      | 7.5%    |
| Samsung Electronics | 3         | 3      | 7.5%    |
| LITEON              | 3         | 3      | 7.5%    |
| Kingston            | 2         | 2      | 5%      |
| Intel               | 2         | 5      | 5%      |
| Crucial             | 2         | 3      | 5%      |
| ZHITAI              | 1         | 1      | 2.5%    |
| SK hynix            | 1         | 1      | 2.5%    |
| SanDisk             | 1         | 1      | 2.5%    |
| HGST HTS            | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |
| DGM                 | 1         | 1      | 2.5%    |
| BIWIN               | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 9         | 10     | 40.91%  |
| WDC      | 4         | 6      | 18.18%  |
| Hitachi  | 4         | 4      | 18.18%  |
| Toshiba  | 3         | 3      | 13.64%  |
| HGST HTS | 1         | 1      | 4.55%   |
| HGST     | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 25     | 53.85%  |
| SSD  | 13        | 14     | 33.33%  |
| NVMe | 5         | 8      | 12.82%  |

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
| Works    | 246       | 482    | 47.04%  |
| Detected | 238       | 459    | 45.51%  |
| Malfunc  | 39        | 47     | 7.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 288       | 43.64%  |
| Samsung Electronics              | 92        | 13.94%  |
| AMD                              | 65        | 9.85%   |
| SanDisk                          | 55        | 8.33%   |
| SK hynix                         | 15        | 2.27%   |
| Silicon Motion                   | 13        | 1.97%   |
| ASMedia Technology               | 13        | 1.97%   |
| Phison Electronics               | 12        | 1.82%   |
| Micron Technology                | 11        | 1.67%   |
| KIOXIA                           | 11        | 1.67%   |
| Kingston Technology Company      | 11        | 1.67%   |
| MAXIO Technology (Hangzhou)      | 10        | 1.52%   |
| Yangtze Memory Technologies      | 8         | 1.21%   |
| Toshiba America Info Systems     | 7         | 1.06%   |
| Micron/Crucial Technology        | 7         | 1.06%   |
| Marvell Technology Group         | 7         | 1.06%   |
| Biwin Storage Technology         | 5         | 0.76%   |
| ADATA Technology                 | 5         | 0.76%   |
| Nvidia                           | 3         | 0.45%   |
| VIA Technologies                 | 2         | 0.3%    |
| Solidigm                         | 2         | 0.3%    |
| LSI Logic / Symbios Logic        | 2         | 0.3%    |
| Lite-On Technology               | 2         | 0.3%    |
| JMicron Technology               | 2         | 0.3%    |
| INNOGRIT                         | 2         | 0.3%    |
| Broadcom / LSI                   | 2         | 0.3%    |
| Apple                            | 2         | 0.3%    |
| Solid State Storage Technology   | 1         | 0.15%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.15%   |
| Realtek Semiconductor            | 1         | 0.15%   |
| Lenovo                           | 1         | 0.15%   |
| Integrated Technology Express    | 1         | 0.15%   |
| Huawei Technologies              | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 41        | 5.65%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 38        | 5.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 22        | 3.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 20        | 2.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 20        | 2.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 19        | 2.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 19        | 2.62%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 16        | 2.2%    |
| AMD 400 Series Chipset SATA Controller                                         | 15        | 2.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 1.65%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 12        | 1.65%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 11        | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 11        | 1.52%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 11        | 1.52%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 10        | 1.38%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 10        | 1.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 1.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 10        | 1.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10        | 1.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 9         | 1.24%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 8         | 1.1%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 8         | 1.1%    |
| Intel SSD 660P Series                                                          | 8         | 1.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8         | 1.1%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 7         | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 0.96%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 6         | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 0.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 0.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 0.69%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 5         | 0.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 5         | 0.69%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                       | 5         | 0.69%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 5         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 305       | 48.26%  |
| NVMe | 248       | 39.24%  |
| RAID | 40        | 6.33%   |
| IDE  | 35        | 5.54%   |
| SAS  | 4         | 0.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 353       | 74.63%  |
| AMD          | 104       | 21.99%  |
| ARM          | 8         | 1.69%   |
| Unknown      | 3         | 0.63%   |
| thead,c906   | 1         | 0.21%   |
| Phytium      | 1         | 0.21%   |
| iSH          | 1         | 0.21%   |
| HISILICON    | 1         | 0.21%   |
| GenuineTMx86 | 1         | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz       | 7         | 1.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 7         | 1.48%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 1.48%   |
| ARM Processor                           | 7         | 1.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 6         | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 6         | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 6         | 1.27%   |
| AMD Ryzen 7 6800U with Radeon Graphics  | 6         | 1.27%   |
| AMD Ryzen 7 6800H with Radeon Graphics  | 6         | 1.27%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 6         | 1.27%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 6         | 1.27%   |
| Intel Pentium CPU G4560 @ 3.50GHz       | 5         | 1.05%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 5         | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 5         | 1.05%   |
| Intel Celeron CPU N3450 @ 1.10GHz       | 5         | 1.05%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 5         | 1.05%   |
| AMD Ryzen 5 3600 6-Core Processor       | 5         | 1.05%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 4         | 0.84%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 4         | 0.84%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 4         | 0.84%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 4         | 0.84%   |
| Intel 12th Gen Core i7-12700H           | 4         | 0.84%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 3         | 0.63%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 3         | 0.63%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 3         | 0.63%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 3         | 0.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 3         | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 3         | 0.63%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 3         | 0.63%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 3         | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 3         | 0.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 0.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 3         | 0.63%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 3         | 0.63%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 3         | 0.63%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 3         | 0.63%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 3         | 0.63%   |
| Intel 13th Gen Core i9-13900HX          | 3         | 0.63%   |
| Intel 13th Gen Core i9-13900H           | 3         | 0.63%   |
| Intel 13th Gen Core i5-13420H           | 3         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 87        | 18.35%  |
| Intel Core i7           | 84        | 17.72%  |
| Intel Core i5           | 80        | 16.88%  |
| AMD Ryzen 7             | 42        | 8.86%   |
| Intel Celeron           | 31        | 6.54%   |
| Intel Core i3           | 30        | 6.33%   |
| AMD Ryzen 5             | 24        | 5.06%   |
| AMD Ryzen 9             | 18        | 3.8%    |
| Intel Xeon              | 14        | 2.95%   |
| Intel Pentium           | 10        | 2.11%   |
| Intel Core 2 Duo        | 6         | 1.27%   |
| Intel Atom              | 5         | 1.05%   |
| Intel Core m3           | 4         | 0.84%   |
| AMD Ryzen 7 PRO         | 3         | 0.63%   |
| AMD Phenom II X4        | 3         | 0.63%   |
| Intel Pentium Gold      | 2         | 0.42%   |
| Intel Pentium Dual-Core | 2         | 0.42%   |
| Intel Pentium Dual      | 2         | 0.42%   |
| Intel Genuine           | 2         | 0.42%   |
| Intel Core i9           | 2         | 0.42%   |
| Intel Core 2            | 2         | 0.42%   |
| AMD Phenom II X6        | 2         | 0.42%   |
| AMD FX                  | 2         | 0.42%   |
| Intel Xeon Silver       | 1         | 0.21%   |
| Intel Xeon Gold         | 1         | 0.21%   |
| Intel Pentium Silver    | 1         | 0.21%   |
| Intel Pentium M         | 1         | 0.21%   |
| Intel Core 2 Quad       | 1         | 0.21%   |
| Intel Core 2 Extreme    | 1         | 0.21%   |
| Intel Core              | 1         | 0.21%   |
| ARM BCM                 | 1         | 0.21%   |
| AMD Ryzen Threadripper  | 1         | 0.21%   |
| AMD Ryzen Embedded      | 1         | 0.21%   |
| AMD Quad-Core           | 1         | 0.21%   |
| AMD Opteron             | 1         | 0.21%   |
| AMD Athlon II X4        | 1         | 0.21%   |
| AMD Athlon II X3        | 1         | 0.21%   |
| AMD Athlon 64 X2        | 1         | 0.21%   |
| AMD A8                  | 1         | 0.21%   |
| AMD A10                 | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 159       | 33.54%  |
| 2       | 119       | 25.11%  |
| 8       | 71        | 14.98%  |
| 6       | 46        | 9.7%    |
| 12      | 21        | 4.43%   |
| 16      | 12        | 2.53%   |
| 14      | 11        | 2.32%   |
| 1       | 10        | 2.11%   |
| 10      | 8         | 1.69%   |
| Unknown | 6         | 1.27%   |
| 24      | 5         | 1.05%   |
| 3       | 3         | 0.63%   |
| 64      | 1         | 0.21%   |
| 32      | 1         | 0.21%   |
| 5       | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 460       | 97.25%  |
| 2       | 7         | 1.48%   |
| Unknown | 6         | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 345       | 72.63%  |
| 1       | 124       | 26.11%  |
| Unknown | 6         | 1.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 448       | 94.71%  |
| Unknown        | 11        | 2.33%   |
| 32-bit         | 10        | 2.11%   |
| 64-bit         | 4         | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 163       | 33.4%   |
| 0x306c3    | 17        | 3.48%   |
| 0x206a7    | 17        | 3.48%   |
| 0x906ea    | 14        | 2.87%   |
| 0x806e9    | 14        | 2.87%   |
| 0x306a9    | 13        | 2.66%   |
| 0x906e9    | 11        | 2.25%   |
| 0x806ea    | 11        | 2.25%   |
| 0x90672    | 10        | 2.05%   |
| 0x806c1    | 10        | 2.05%   |
| 0x0a50000c | 9         | 1.84%   |
| 0x506e3    | 8         | 1.64%   |
| 0x40651    | 8         | 1.64%   |
| 0x806eb    | 7         | 1.43%   |
| 0x0a404102 | 7         | 1.43%   |
| 0x806ec    | 6         | 1.23%   |
| 0x706e5    | 6         | 1.23%   |
| 0x506c9    | 6         | 1.23%   |
| 0x406e3    | 6         | 1.23%   |
| 0x08600106 | 6         | 1.23%   |
| 0xa0652    | 5         | 1.02%   |
| 0x906ed    | 5         | 1.02%   |
| 0x0a50000d | 5         | 1.02%   |
| 0x706a8    | 4         | 0.82%   |
| 0x306e4    | 4         | 0.82%   |
| 0x20655    | 4         | 0.82%   |
| 0x20652    | 4         | 0.82%   |
| 0x106c2    | 4         | 0.82%   |
| 0x1067a    | 4         | 0.82%   |
| 0x0a704103 | 4         | 0.82%   |
| 0x0a601203 | 4         | 0.82%   |
| 0x08701013 | 4         | 0.82%   |
| 0x0800820d | 4         | 0.82%   |
| 0xb0671    | 3         | 0.61%   |
| 0xa0653    | 3         | 0.61%   |
| 0x906a3    | 3         | 0.61%   |
| 0x6fd      | 3         | 0.61%   |
| 0x30678    | 3         | 0.61%   |
| 0x0a201009 | 3         | 0.61%   |
| 0x08701021 | 3         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 88        | 18.53%  |
| Unknown           | 58        | 12.21%  |
| Haswell           | 37        | 7.79%   |
| Alderlake Hybrid  | 32        | 6.74%   |
| Zen 3             | 27        | 5.68%   |
| Zen 2             | 26        | 5.47%   |
| IvyBridge         | 25        | 5.26%   |
| Skylake           | 23        | 4.84%   |
| SandyBridge       | 22        | 4.63%   |
| TigerLake         | 20        | 4.21%   |
| IceLake           | 13        | 2.74%   |
| CometLake         | 13        | 2.74%   |
| Westmere          | 12        | 2.53%   |
| Zen+              | 10        | 2.11%   |
| Goldmont plus     | 10        | 2.11%   |
| Penryn            | 7         | 1.47%   |
| K10               | 7         | 1.47%   |
| Goldmont          | 7         | 1.47%   |
| Core              | 7         | 1.47%   |
| Silvermont        | 6         | 1.26%   |
| Broadwell         | 4         | 0.84%   |
| Bonnell           | 4         | 0.84%   |
| P6                | 3         | 0.63%   |
| Zen               | 2         | 0.42%   |
| Steamroller       | 2         | 0.42%   |
| Piledriver        | 2         | 0.42%   |
| Gracemont         | 2         | 0.42%   |
| Tremont           | 1         | 0.21%   |
| Nehalem           | 1         | 0.21%   |
| Meteorlake Hybrid | 1         | 0.21%   |
| K8 Hammer         | 1         | 0.21%   |
| Jaguar            | 1         | 0.21%   |
| Excavator         | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 287       | 50.62%  |
| Nvidia                     | 166       | 29.28%  |
| AMD                        | 106       | 18.69%  |
| Matrox Electronics Systems | 3         | 0.53%   |
| Neomagic                   | 2         | 0.35%   |
| ASPEED Technology          | 2         | 0.35%   |
| S3 Graphics                | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 19        | 3.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 18        | 3.08%   |
| Intel UHD Graphics 620                                                        | 17        | 2.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 17        | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 13        | 2.23%   |
| AMD Rembrandt [Radeon 680M]                                                   | 13        | 2.23%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 12        | 2.05%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 11        | 1.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 10        | 1.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 10        | 1.71%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 10        | 1.71%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 10        | 1.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 9         | 1.54%   |
| Intel HD Graphics 620                                                         | 8         | 1.37%   |
| Intel HD Graphics 610                                                         | 8         | 1.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 8         | 1.37%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 7         | 1.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 1.2%    |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 7         | 1.2%    |
| Intel HD Graphics 530                                                         | 7         | 1.2%    |
| Intel HD Graphics 500                                                         | 7         | 1.2%    |
| Nvidia GP108M [GeForce MX150]                                                 | 6         | 1.03%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 1.03%   |
| Intel AlderLake-S GT1                                                         | 6         | 1.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 6         | 1.03%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 5         | 0.86%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 5         | 0.86%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                               | 5         | 0.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 5         | 0.86%   |
| Intel HD Graphics 630                                                         | 5         | 0.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 0.86%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 5         | 0.86%   |
| AMD Raphael                                                                   | 5         | 0.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 0.86%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 5         | 0.86%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 4         | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 4         | 0.68%   |
| Nvidia GM107 [GeForce GTX 750]                                                | 4         | 0.68%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 205       | 43.16%  |
| 1 x Nvidia      | 77        | 16.21%  |
| 1 x AMD         | 70        | 14.74%  |
| Intel + Nvidia  | 66        | 13.89%  |
| AMD + Nvidia    | 20        | 4.21%   |
| Other           | 13        | 2.74%   |
| Intel + AMD     | 8         | 1.68%   |
| 2 x AMD         | 6         | 1.26%   |
| Nvidia + Matrox | 2         | 0.42%   |
| 1 x Neomagic    | 2         | 0.42%   |
| 1 x ASPEED      | 2         | 0.42%   |
| 3 x AMD         | 1         | 0.21%   |
| 2 x Intel       | 1         | 0.21%   |
| 1 x S3 Graphics | 1         | 0.21%   |
| 1 x Matrox      | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 353       | 73.85%  |
| Proprietary | 96        | 20.08%  |
| Unknown     | 29        | 6.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 296       | 61.54%  |
| 1.01-2.0   | 37        | 7.69%   |
| 0.01-0.5   | 33        | 6.86%   |
| 7.01-8.0   | 32        | 6.65%   |
| 3.01-4.0   | 31        | 6.44%   |
| 0.51-1.0   | 26        | 5.41%   |
| 5.01-6.0   | 15        | 3.12%   |
| 8.01-16.0  | 6         | 1.25%   |
| 2.01-3.0   | 3         | 0.62%   |
| 4.01-5.0   | 1         | 0.21%   |
| 16.01-24.0 | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 61        | 12.13%  |
| AU Optronics         | 46        | 9.15%   |
| Samsung Electronics  | 42        | 8.35%   |
| Dell                 | 34        | 6.76%   |
| LG Display           | 30        | 5.96%   |
| Chimei Innolux       | 26        | 5.17%   |
| AOC                  | 26        | 5.17%   |
| Goldstar             | 22        | 4.37%   |
| Philips              | 16        | 3.18%   |
| Sharp                | 14        | 2.78%   |
| BenQ                 | 11        | 2.19%   |
| Acer                 | 11        | 2.19%   |
| Lenovo               | 10        | 1.99%   |
| Ancor Communications | 10        | 1.99%   |
| Unknown              | 7         | 1.39%   |
| JRY                  | 7         | 1.39%   |
| Apple                | 7         | 1.39%   |
| ViewSonic            | 6         | 1.19%   |
| IPS                  | 6         | 1.19%   |
| Hewlett-Packard      | 6         | 1.19%   |
| ASUSTek Computer     | 6         | 1.19%   |
| AMO                  | 6         | 1.19%   |
| RTK                  | 5         | 0.99%   |
| CSO                  | 5         | 0.99%   |
| Mi                   | 4         | 0.8%    |
| JDI                  | 4         | 0.8%    |
| SOY                  | 3         | 0.6%    |
| PANDA                | 3         | 0.6%    |
| InfoVision           | 3         | 0.6%    |
| Valve                | 2         | 0.4%    |
| TMX                  | 2         | 0.4%    |
| Sony                 | 2         | 0.4%    |
| SKY                  | 2         | 0.4%    |
| SAC                  | 2         | 0.4%    |
| LG Philips           | 2         | 0.4%    |
| LDR                  | 2         | 0.4%    |
| Intehill             | 2         | 0.4%    |
| HSO                  | 2         | 0.4%    |
| HKC                  | 2         | 0.4%    |
| Eizo                 | 2         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| JRY HDMI JRY1330 1920x1080 293x165mm 13.2-inch                        | 6         | 1.17%   |
| AOC Q2790 AOC2790 2560x1440 597x336mm 27.0-inch                       | 5         | 0.97%   |
| IPS HDMI IPS2700 1920x1080 597x336mm 27.0-inch                        | 4         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.78%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                 | 4         | 0.78%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 4         | 0.78%   |
| AMO HS241P AMO2800 3840x2160 620x350mm 28.0-inch                      | 4         | 0.78%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 3         | 0.58%   |
| RTK 7911D RTK2A3B 720x1280 720x1280mm 57.8-inch                       | 3         | 0.58%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 3         | 0.58%   |
| BOE LCD Monitor BOE0AE3 1920x1080 344x194mm 15.5-inch                 | 3         | 0.58%   |
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 3         | 0.58%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 3         | 0.58%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.39%   |
| SOY M5 MONITOR SOY0240 1920x1080 520x320mm 24.0-inch                  | 2         | 0.39%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 0.39%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.39%   |
| SAC HDMI SAC2400 1920x1080 530x300mm 24.0-inch                        | 2         | 0.39%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch               | 2         | 0.39%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 0.39%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 2         | 0.39%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.39%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 2         | 0.39%   |
| LDR CFORCE LDR1560 1920x1080 300x260mm 15.6-inch                      | 2         | 0.39%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 2         | 0.39%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 2         | 0.39%   |
| Intehill HS156PE HSJ0156 1920x1080 345x194mm 15.6-inch                | 2         | 0.39%   |
| HSO B2431M HSO2431 3840x2160 520x290mm 23.4-inch                      | 2         | 0.39%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.39%   |
| Goldstar MONITOR GSM59C6 1920x1080 509x286mm 23.0-inch                | 2         | 0.39%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.39%   |
| Dell U2417H DEL40E7 1920x1080 530x300mm 24.0-inch                     | 2         | 0.39%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                     | 2         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 214       | 45.34%  |
| 3840x2160 (4K)     | 57        | 12.08%  |
| 1366x768 (WXGA)    | 40        | 8.47%   |
| 2560x1440 (QHD)    | 34        | 7.2%    |
| 2560x1600          | 15        | 3.18%   |
| 1440x900 (WXGA+)   | 12        | 2.54%   |
| 1600x900 (HD+)     | 9         | 1.91%   |
| Unknown            | 7         | 1.48%   |
| 2880x1800          | 6         | 1.27%   |
| 1680x1050 (WSXGA+) | 6         | 1.27%   |
| 1280x800 (WXGA)    | 6         | 1.27%   |
| 3840x2400          | 5         | 1.06%   |
| 3000x2000          | 5         | 1.06%   |
| 1920x1200 (WUXGA)  | 5         | 1.06%   |
| 3440x1440          | 4         | 0.85%   |
| 2240x1400          | 4         | 0.85%   |
| 1280x1024 (SXGA)   | 4         | 0.85%   |
| 3840x1080          | 3         | 0.64%   |
| 1360x768           | 3         | 0.64%   |
| 800x1280           | 2         | 0.42%   |
| 3200x2000          | 2         | 0.42%   |
| 3200x1800 (QHD+)   | 2         | 0.42%   |
| 2880x1920          | 2         | 0.42%   |
| 2880x1620          | 2         | 0.42%   |
| 2560x1080          | 2         | 0.42%   |
| 2400x1600          | 2         | 0.42%   |
| 1024x768 (XGA)     | 2         | 0.42%   |
| 5120x1440          | 1         | 0.21%   |
| 4480x1440          | 1         | 0.21%   |
| 3840x1600          | 1         | 0.21%   |
| 3840x1100          | 1         | 0.21%   |
| 3520x1080          | 1         | 0.21%   |
| 3456x2160          | 1         | 0.21%   |
| 3200x1080          | 1         | 0.21%   |
| 2304x1440          | 1         | 0.21%   |
| 2256x1504          | 1         | 0.21%   |
| 2160x1440          | 1         | 0.21%   |
| 2160x1350          | 1         | 0.21%   |
| 1600x2560          | 1         | 0.21%   |
| 1400x1050          | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 80        | 16.13%  |
| 13      | 63        | 12.7%   |
| 14      | 45        | 9.07%   |
| 24      | 44        | 8.87%   |
| 23      | 39        | 7.86%   |
| 27      | 36        | 7.26%   |
| 21      | 33        | 6.65%   |
| Unknown | 26        | 5.24%   |
| 12      | 16        | 3.23%   |
| 16      | 15        | 3.02%   |
| 31      | 14        | 2.82%   |
| 18      | 13        | 2.62%   |
| 17      | 11        | 2.22%   |
| 40      | 8         | 1.61%   |
| 19      | 6         | 1.21%   |
| 34      | 5         | 1.01%   |
| 28      | 5         | 1.01%   |
| 84      | 4         | 0.81%   |
| 22      | 4         | 0.81%   |
| 57      | 3         | 0.6%    |
| 10      | 3         | 0.6%    |
| 32      | 2         | 0.4%    |
| 26      | 2         | 0.4%    |
| 25      | 2         | 0.4%    |
| 20      | 2         | 0.4%    |
| 8       | 2         | 0.4%    |
| 7       | 2         | 0.4%    |
| 72      | 1         | 0.2%    |
| 65      | 1         | 0.2%    |
| 58      | 1         | 0.2%    |
| 54      | 1         | 0.2%    |
| 52      | 1         | 0.2%    |
| 50      | 1         | 0.2%    |
| 48      | 1         | 0.2%    |
| 43      | 1         | 0.2%    |
| 38      | 1         | 0.2%    |
| 37      | 1         | 0.2%    |
| 11      | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 155       | 31.89%  |
| 501-600     | 115       | 23.66%  |
| 201-300     | 63        | 12.96%  |
| 401-500     | 54        | 11.11%  |
| Unknown     | 26        | 5.35%   |
| 601-700     | 21        | 4.32%   |
| 351-400     | 16        | 3.29%   |
| 801-900     | 10        | 2.06%   |
| 701-800     | 10        | 2.06%   |
| 1001-1500   | 6         | 1.23%   |
| 1501-2000   | 5         | 1.03%   |
| 101-200     | 2         | 0.41%   |
| 1-100       | 2         | 0.41%   |
| 901-1000    | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 332       | 73.13%  |
| 16/10   | 68        | 14.98%  |
| Unknown | 21        | 4.63%   |
| 3/2     | 11        | 2.42%   |
| 21/9    | 6         | 1.32%   |
| 0.56    | 4         | 0.88%   |
| 0.62    | 3         | 0.66%   |
| 6/5     | 2         | 0.44%   |
| 4/3     | 2         | 0.44%   |
| 0.67    | 2         | 0.44%   |
| 5/4     | 1         | 0.22%   |
| 32/9    | 1         | 0.22%   |
| 3.40    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 97        | 19.6%   |
| 101-110        | 82        | 16.57%  |
| 81-90          | 77        | 15.56%  |
| 301-350        | 43        | 8.69%   |
| 71-80          | 32        | 6.46%   |
| Unknown        | 26        | 5.25%   |
| 351-500        | 22        | 4.44%   |
| 151-200        | 21        | 4.24%   |
| 61-70          | 15        | 3.03%   |
| 251-300        | 14        | 2.83%   |
| More than 1000 | 13        | 2.63%   |
| 111-120        | 11        | 2.22%   |
| 501-1000       | 11        | 2.22%   |
| 121-130        | 10        | 2.02%   |
| 141-150        | 9         | 1.82%   |
| 1-40           | 4         | 0.81%   |
| 41-50          | 3         | 0.61%   |
| 51-60          | 2         | 0.4%    |
| 91-100         | 2         | 0.4%    |
| 131-140        | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 134       | 27.86%  |
| 121-160       | 123       | 25.57%  |
| 101-120       | 85        | 17.67%  |
| 161-240       | 69        | 14.35%  |
| More than 240 | 32        | 6.65%   |
| Unknown       | 26        | 5.41%   |
| 1-50          | 12        | 2.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 373       | 77.39%  |
| 2     | 77        | 15.98%  |
| 0     | 29        | 6.02%   |
| 3     | 3         | 0.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 278       | 40.52%  |
| Realtek Semiconductor                  | 236       | 34.4%   |
| Qualcomm Atheros                       | 44        | 6.41%   |
| Broadcom                               | 26        | 3.79%   |
| MediaTek                               | 24        | 3.5%    |
| ASIX Electronics                       | 12        | 1.75%   |
| TP-Link                                | 10        | 1.46%   |
| Ralink Technology                      | 9         | 1.31%   |
| Broadcom Limited                       | 6         | 0.87%   |
| Qualcomm                               | 3         | 0.44%   |
| Microsoft                              | 3         | 0.44%   |
| Marvell Technology Group               | 3         | 0.44%   |
| Xiaomi                                 | 2         | 0.29%   |
| SEGGER                                 | 2         | 0.29%   |
| Nvidia                                 | 2         | 0.29%   |
| Lenovo                                 | 2         | 0.29%   |
| Huawei Technologies                    | 2         | 0.29%   |
| DisplayLink                            | 2         | 0.29%   |
| Texas Instruments                      | 1         | 0.15%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.15%   |
| Samsung Electronics                    | 1         | 0.15%   |
| Ralink                                 | 1         | 0.15%   |
| Quectel Wireless Solutions             | 1         | 0.15%   |
| PEAK-System Technik                    | 1         | 0.15%   |
| OPPO Electronics                       | 1         | 0.15%   |
| NetGear                                | 1         | 0.15%   |
| National Semiconductor                 | 1         | 0.15%   |
| Kinesis                                | 1         | 0.15%   |
| ICS Advent                             | 1         | 0.15%   |
| Google                                 | 1         | 0.15%   |
| Fitbit                                 | 1         | 0.15%   |
| D-Link System                          | 1         | 0.15%   |
| D-Link                                 | 1         | 0.15%   |
| Belkin Components                      | 1         | 0.15%   |
| ASUSTek Computer                       | 1         | 0.15%   |
| Arduino SA                             | 1         | 0.15%   |
| Aquantia                               | 1         | 0.15%   |
| Apple                                  | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 155       | 18.93%  |
| Intel Wi-Fi 6 AX200                                                    | 37        | 4.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 23        | 2.81%   |
| Realtek RTL8125 2.5GbE Controller                                      | 18        | 2.2%    |
| Intel Wireless 8265 / 8275                                             | 18        | 2.2%    |
| Intel Ethernet Controller I225-V                                       | 15        | 1.83%   |
| Intel Wi-Fi 6 AX201                                                    | 14        | 1.71%   |
| Intel I211 Gigabit Network Connection                                  | 14        | 1.71%   |
| Intel Wireless 7265                                                    | 13        | 1.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 13        | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 11        | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 11        | 1.34%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 10        | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 1.22%   |
| ASIX AX88179 Gigabit Ethernet                                          | 10        | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 1.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 9         | 1.1%    |
| Intel Wireless 7260                                                    | 9         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 9         | 1.1%    |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 9         | 1.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                                   | 8         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 8         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 0.85%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 7         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 7         | 0.85%   |
| Intel Wireless 8260                                                    | 7         | 0.85%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 7         | 0.85%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 0.85%   |
| Ralink MT7601U Wireless Adapter                                        | 6         | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 6         | 0.73%   |
| Intel 82579V Gigabit Network Connection                                | 6         | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 0.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 5         | 0.61%   |
| Intel I350 Gigabit Network Connection                                  | 5         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 0.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 0.61%   |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 227       | 57.91%  |
| Realtek Semiconductor      | 51        | 13.01%  |
| Qualcomm Atheros           | 35        | 8.93%   |
| MediaTek                   | 24        | 6.12%   |
| Broadcom                   | 19        | 4.85%   |
| TP-Link                    | 10        | 2.55%   |
| Ralink Technology          | 9         | 2.3%    |
| Broadcom Limited           | 4         | 1.02%   |
| Qualcomm                   | 3         | 0.77%   |
| Microsoft                  | 3         | 0.77%   |
| Texas Instruments          | 1         | 0.26%   |
| Ralink                     | 1         | 0.26%   |
| Quectel Wireless Solutions | 1         | 0.26%   |
| NetGear                    | 1         | 0.26%   |
| D-Link System              | 1         | 0.26%   |
| Belkin Components          | 1         | 0.26%   |
| ASUSTek Computer           | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 37        | 9.41%   |
| Intel Wireless 8265 / 8275                                              | 18        | 4.58%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 3.56%   |
| Intel Wireless 7265                                                     | 13        | 3.31%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 13        | 3.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 11        | 2.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 2.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 10        | 2.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.29%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 9         | 2.29%   |
| Intel Wireless 7260                                                     | 9         | 2.29%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 2.29%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 9         | 2.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 2.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.78%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 7         | 1.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.78%   |
| Intel Wireless 8260                                                     | 7         | 1.78%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 7         | 1.78%   |
| Ralink MT7601U Wireless Adapter                                         | 6         | 1.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 1.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 5         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.02%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 4         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.76%   |
| Microsoft Xbox Wireless Adapter for Windows                             | 3         | 0.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 217       | 53.32%  |
| Intel                                  | 130       | 31.94%  |
| Qualcomm Atheros                       | 14        | 3.44%   |
| ASIX Electronics                       | 12        | 2.95%   |
| Broadcom                               | 10        | 2.46%   |
| Marvell Technology Group               | 3         | 0.74%   |
| Xiaomi                                 | 2         | 0.49%   |
| Nvidia                                 | 2         | 0.49%   |
| Lenovo                                 | 2         | 0.49%   |
| Huawei Technologies                    | 2         | 0.49%   |
| DisplayLink                            | 2         | 0.49%   |
| Broadcom Limited                       | 2         | 0.49%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.25%   |
| Samsung Electronics                    | 1         | 0.25%   |
| OPPO Electronics                       | 1         | 0.25%   |
| National Semiconductor                 | 1         | 0.25%   |
| ICS Advent                             | 1         | 0.25%   |
| Google                                 | 1         | 0.25%   |
| D-Link                                 | 1         | 0.25%   |
| Aquantia                               | 1         | 0.25%   |
| Apple                                  | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 155       | 37.08%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 23        | 5.5%    |
| Realtek RTL8125 2.5GbE Controller                                      | 18        | 4.31%   |
| Intel Ethernet Controller I225-V                                       | 15        | 3.59%   |
| Intel I211 Gigabit Network Connection                                  | 14        | 3.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 2.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 2.39%   |
| ASIX AX88179 Gigabit Ethernet                                          | 10        | 2.39%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 1.91%   |
| Intel Ethernet Connection (2) I219-V                                   | 8         | 1.91%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 1.67%   |
| Intel 82579V Gigabit Network Connection                                | 6         | 1.44%   |
| Intel I350 Gigabit Network Connection                                  | 5         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 1.2%    |
| Realtek Killer E2600 GbE Controller                                    | 4         | 0.96%   |
| Intel Ethernet Connection (11) I219-V                                  | 4         | 0.96%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.96%   |
| Intel 82574L Gigabit Network Connection                                | 4         | 0.96%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 3         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.72%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.72%   |
| Intel Ethernet Connection (17) I219-LM                                 | 3         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.48%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.48%   |
| Lenovo ThinkPad Lan                                                    | 2         | 0.48%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.48%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.48%   |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 0.48%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 0.48%   |
| Intel Ethernet Connection (12) I219-V                                  | 2         | 0.48%   |
| DisplayLink USB3.0 Dual Video Dock                                     | 2         | 0.48%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 376       | 49.54%  |
| WiFi     | 375       | 49.41%  |
| Modem    | 5         | 0.66%   |
| Unknown  | 3         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 281       | 55.98%  |
| Ethernet | 221       | 44.02%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 239       | 50%     |
| 1     | 200       | 41.84%  |
| 0     | 21        | 4.39%   |
| 3     | 11        | 2.3%    |
| 4     | 5         | 1.05%   |
| 8     | 1         | 0.21%   |
| 7     | 1         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 457       | 96.21%  |
| Yes  | 18        | 3.79%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 199       | 61.23%  |
| Realtek Semiconductor           | 20        | 6.15%   |
| Cambridge Silicon Radio         | 18        | 5.54%   |
| Foxconn / Hon Hai               | 15        | 4.62%   |
| Broadcom                        | 13        | 4%      |
| IMC Networks                    | 11        | 3.38%   |
| Qualcomm Atheros Communications | 10        | 3.08%   |
| Apple                           | 9         | 2.77%   |
| MediaTek                        | 5         | 1.54%   |
| Lite-On Technology              | 5         | 1.54%   |
| Realtek                         | 3         | 0.92%   |
| Hewlett-Packard                 | 3         | 0.92%   |
| Foxconn International           | 3         | 0.92%   |
| Taiyo Yuden                     | 2         | 0.62%   |
| Dell                            | 2         | 0.62%   |
| ASUSTek Computer                | 2         | 0.62%   |
| TP-Link                         | 1         | 0.31%   |
| SINO WEALTH                     | 1         | 0.31%   |
| Micro Star International        | 1         | 0.31%   |
| Fujitsu                         | 1         | 0.31%   |
| Askey Computer                  | 1         | 0.31%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 48        | 14.77%  |
| Intel AX201 Bluetooth                               | 43        | 13.23%  |
| Intel AX200 Bluetooth                               | 36        | 11.08%  |
| Intel Bluetooth Device                              | 23        | 7.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 21        | 6.46%   |
| Realtek Bluetooth Radio                             | 19        | 5.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18        | 5.54%   |
| Intel AX210 Bluetooth                               | 13        | 4%      |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 3.38%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 2.77%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 1.85%   |
| MediaTek Wireless_Device                            | 5         | 1.54%   |
| IMC Networks Wireless_Device                        | 5         | 1.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.23%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.23%   |
| Realtek Bluetooth Radio                             | 3         | 0.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.92%   |
| IMC Networks Bluetooth Radio                        | 3         | 0.92%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.92%   |
| Apple Bluetooth Host Controller                     | 3         | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.62%   |
| IMC Networks Bluetooth Device                       | 2         | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.62%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 2         | 0.62%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.62%   |
| ASUS Bluetooth Radio                                | 2         | 0.62%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.62%   |
| TP-Link UB500 Adapter                               | 1         | 0.31%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.31%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.31%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1         | 0.31%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.31%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.31%   |
| Micro Star International Bluetooth Dongle           | 1         | 0.31%   |
| Lite-On Bluetooth Radio                             | 1         | 0.31%   |
| Lite-On Bluetooth Device                            | 1         | 0.31%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 343       | 53.93%  |
| Nvidia                                       | 125       | 19.65%  |
| AMD                                          | 117       | 18.4%   |
| C-Media Electronics                          | 13        | 2.04%   |
| Logitech                                     | 3         | 0.47%   |
| FiiO Electronics Technology                  | 3         | 0.47%   |
| ASUSTek Computer                             | 3         | 0.47%   |
| Micro Star International                     | 2         | 0.31%   |
| Generalplus Technology                       | 2         | 0.31%   |
| Focusrite-Novation                           | 2         | 0.31%   |
| ESS Technology                               | 2         | 0.31%   |
| Creative Labs                                | 2         | 0.31%   |
| AudioQuest                                   | 2         | 0.31%   |
| Anlya.cn                                     | 2         | 0.31%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.16%   |
| XMOS                                         | 1         | 0.16%   |
| Winbond Electronics                          | 1         | 0.16%   |
| VIA Technologies                             | 1         | 0.16%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.16%   |
| Texas Instruments                            | 1         | 0.16%   |
| Sony                                         | 1         | 0.16%   |
| SAVITECH                                     | 1         | 0.16%   |
| Realtek Semiconductor                        | 1         | 0.16%   |
| Lynx                                         | 1         | 0.16%   |
| Lenovo                                       | 1         | 0.16%   |
| JMTek                                        | 1         | 0.16%   |
| iCreate Technologies                         | 1         | 0.16%   |
| DSEA A/S                                     | 1         | 0.16%   |
| Apple                                        | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 60        | 8.01%   |
| Intel Sunrise Point-LP HD Audio                                            | 41        | 5.47%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 24        | 3.2%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 24        | 3.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22        | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21        | 2.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 2.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 20        | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 20        | 2.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19        | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 2.4%    |
| Nvidia Audio device                                                        | 16        | 2.14%   |
| Intel Alder Lake-S HD Audio Controller                                     | 16        | 2.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 12        | 1.6%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11        | 1.47%   |
| Nvidia GP106 High Definition Audio Controller                              | 10        | 1.34%   |
| Nvidia GA104 High Definition Audio Controller                              | 10        | 1.34%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 10        | 1.34%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 1.34%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 1.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 1.34%   |
| Intel 200 Series PCH HD Audio                                              | 10        | 1.34%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.2%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 1.2%    |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 1.07%   |
| Nvidia GM206 High Definition Audio Controller                              | 8         | 1.07%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 1.07%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 8         | 1.07%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 8         | 1.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 7         | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 0.8%    |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 0.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 82        | 24.48%  |
| SK hynix                   | 60        | 17.91%  |
| Kingston                   | 42        | 12.54%  |
| Micron Technology          | 34        | 10.15%  |
| Unknown                    | 21        | 6.27%   |
| Crucial                    | 15        | 4.48%   |
| Corsair                    | 14        | 4.18%   |
| A-DATA Technology          | 14        | 4.18%   |
| Unknown                    | 10        | 2.99%   |
| Unknown (ABCD)             | 6         | 1.79%   |
| G.Skill                    | 5         | 1.49%   |
| Team                       | 4         | 1.19%   |
| Elpida                     | 4         | 1.19%   |
| Ramaxel Technology         | 3         | 0.9%    |
| Patriot                    | 2         | 0.6%    |
| Nanya Technology           | 2         | 0.6%    |
| Kingmax                    | 2         | 0.6%    |
| Unknown (0x0AFD)           | 1         | 0.3%    |
| Unknown (08C8)             | 1         | 0.3%    |
| Transcend                  | 1         | 0.3%    |
| tigo                       | 1         | 0.3%    |
| Shenzhen Jinge Information | 1         | 0.3%    |
| Lenovo                     | 1         | 0.3%    |
| KingSpec                   | 1         | 0.3%    |
| KINGBANK                   | 1         | 0.3%    |
| Kimtigo                    | 1         | 0.3%    |
| Juhor                      | 1         | 0.3%    |
| GLOWAY                     | 1         | 0.3%    |
| Essencore Limited          | 1         | 0.3%    |
| CUSO                       | 1         | 0.3%    |
| ChangXin Memory            | 1         | 0.3%    |
| Apacer                     | 1         | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 10        | 2.84%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 1.14%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 4         | 1.14%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 4         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 3         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 0.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.85%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 3         | 0.85%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s            | 3         | 0.85%   |
| Samsung RAM M425R1GB4BB0-CWMOD 8192MB SODIMM 5600MT/s               | 3         | 0.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 2         | 0.57%   |
| Unknown RAM Module 256MB SODIMM DRAM                                | 2         | 0.57%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                        | 2         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.57%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s                | 2         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 2         | 0.57%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.57%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 2         | 0.57%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 2         | 0.57%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s        | 2         | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.57%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 2         | 0.57%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s             | 2         | 0.57%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 2         | 0.57%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s         | 2         | 0.57%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                      | 2         | 0.57%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s                 | 2         | 0.57%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s             | 2         | 0.57%   |
| Kingston RAM 9905744-066.A00G 32GB SODIMM DDR4 3200MT/s             | 2         | 0.57%   |
| Crucial RAM CT16G4SFS832A.C8FB 16GB SODIMM DDR4 3200MT/s            | 2         | 0.57%   |
| Crucial RAM BLS16G4S26BFSD.16FBD 16GB SODIMM DDR4 2400MT/s          | 2         | 0.57%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s               | 2         | 0.57%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s               | 2         | 0.57%   |
| Corsair RAM CM4X16GC3600C18K2D 16GB DIMM DDR4 3600MT/s              | 2         | 0.57%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                            | 2         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 146       | 48.99%  |
| DDR3    | 50        | 16.78%  |
| DDR5    | 27        | 9.06%   |
| LPDDR4  | 22        | 7.38%   |
| LPDDR3  | 15        | 5.03%   |
| LPDDR5  | 13        | 4.36%   |
| DDR2    | 10        | 3.36%   |
| Unknown | 6         | 2.01%   |
| SDRAM   | 5         | 1.68%   |
| DRAM    | 3         | 1.01%   |
| DDR     | 1         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 143       | 47.83%  |
| DIMM         | 104       | 34.78%  |
| Row Of Chips | 49        | 16.39%  |
| Unknown      | 3         | 1%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 108       | 33.86%  |
| 16384 | 71        | 22.26%  |
| 4096  | 63        | 19.75%  |
| 32768 | 34        | 10.66%  |
| 2048  | 27        | 8.46%   |
| 1024  | 7         | 2.19%   |
| 3072  | 2         | 0.63%   |
| 256   | 2         | 0.63%   |
| 64    | 2         | 0.63%   |
| 49152 | 1         | 0.31%   |
| 512   | 1         | 0.31%   |
| 232   | 1         | 0.31%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 54        | 17.25%  |
| 2667    | 46        | 14.7%   |
| 1600    | 38        | 12.14%  |
| 2400    | 24        | 7.67%   |
| 2133    | 19        | 6.07%   |
| 4800    | 14        | 4.47%   |
| 6400    | 12        | 3.83%   |
| 5600    | 10        | 3.19%   |
| 4267    | 10        | 3.19%   |
| 1333    | 10        | 3.19%   |
| 3600    | 8         | 2.56%   |
| 2666    | 7         | 2.24%   |
| 1867    | 6         | 1.92%   |
| Unknown | 6         | 1.92%   |
| 3266    | 4         | 1.28%   |
| 3000    | 4         | 1.28%   |
| 667     | 4         | 1.28%   |
| 3733    | 3         | 0.96%   |
| 1334    | 3         | 0.96%   |
| 800     | 3         | 0.96%   |
| 6000    | 2         | 0.64%   |
| 3533    | 2         | 0.64%   |
| 533     | 2         | 0.64%   |
| 200     | 2         | 0.64%   |
| 8533    | 1         | 0.32%   |
| 8400    | 1         | 0.32%   |
| 7467    | 1         | 0.32%   |
| 7000    | 1         | 0.32%   |
| 5808    | 1         | 0.32%   |
| 4266    | 1         | 0.32%   |
| 4199    | 1         | 0.32%   |
| 3933    | 1         | 0.32%   |
| 3866    | 1         | 0.32%   |
| 3800    | 1         | 0.32%   |
| 3466    | 1         | 0.32%   |
| 3400    | 1         | 0.32%   |
| 3007    | 1         | 0.32%   |
| 2933    | 1         | 0.32%   |
| 1866    | 1         | 0.32%   |
| 1800    | 1         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Xiaomi             | 1         | 20%     |
| Hewlett-Packard    | 1         | 20%     |
| Fuji Xerox         | 1         | 20%     |
| Canon              | 1         | 20%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| Xiaomi MiMouse 2            | 1         | 20%     |
| HP LaserJet P2035           | 1         | 20%     |
| Fuji Xerox DocuPrint P158 b | 1         | 20%     |
| Canon MP160                 | 1         | 20%     |
| Brother HL-L2320D series    | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 51        | 21.16%  |
| IMC Networks                           | 20        | 8.3%    |
| Microdia                               | 17        | 7.05%   |
| Bison Electronics                      | 15        | 6.22%   |
| Realtek Semiconductor                  | 12        | 4.98%   |
| Luxvisions Innotech Limited            | 12        | 4.98%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 4.56%   |
| Logitech                               | 10        | 4.15%   |
| Sunplus Innovation Technology          | 9         | 3.73%   |
| Acer                                   | 9         | 3.73%   |
| Syntek                                 | 7         | 2.9%    |
| Quanta                                 | 7         | 2.9%    |
| Apple                                  | 7         | 2.9%    |
| Silicon Motion                         | 5         | 2.07%   |
| Suyin                                  | 4         | 1.66%   |
| Sonix Technology                       | 4         | 1.66%   |
| Microsoft                              | 3         | 1.24%   |
| eMPIA Technology                       | 3         | 1.24%   |
| Alcor Micro                            | 3         | 1.24%   |
| Tripath Technology                     | 2         | 0.83%   |
| SN0002                                 | 2         | 0.83%   |
| Shinetech                              | 2         | 0.83%   |
| Lite-On Technology                     | 2         | 0.83%   |
| Importek                               | 2         | 0.83%   |
| Cubeternet                             | 2         | 0.83%   |
| Z-Star Microelectronics                | 1         | 0.41%   |
| Xiaomi                                 | 1         | 0.41%   |
| WaveRider Communications               | 1         | 0.41%   |
| USB Camera                             | 1         | 0.41%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.41%   |
| Ricoh                                  | 1         | 0.41%   |
| Primax Electronics                     | 1         | 0.41%   |
| Nokia Mobile Phones                    | 1         | 0.41%   |
| Nebraska Furniture Mart                | 1         | 0.41%   |
| lihappe8                               | 1         | 0.41%   |
| Lenovo                                 | 1         | 0.41%   |
| kingcome                               | 1         | 0.41%   |
| HYGD-220831-A                          | 1         | 0.41%   |
| Hopewin Electronic Material            | 1         | 0.41%   |
| Google                                 | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 22        | 8.94%   |
| IMC Networks Integrated Camera                                             | 10        | 4.07%   |
| Microdia Integrated_Webcam_HD                                              | 9         | 3.66%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 6         | 2.44%   |
| Chicony HD WebCam                                                          | 6         | 2.44%   |
| Bison Integrated Camera                                                    | 6         | 2.44%   |
| Syntek Integrated Camera                                                   | 5         | 2.03%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 2.03%   |
| Chicony FJ Camera                                                          | 5         | 2.03%   |
| Logitech Webcam C270                                                       | 4         | 1.63%   |
| Apple FaceTime HD Camera (Built-in)                                        | 4         | 1.63%   |
| Acer Integrated Camera                                                     | 4         | 1.63%   |
| Sonix USB2.0 FHD UVC WebCam                                                | 3         | 1.22%   |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 3         | 1.22%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 3         | 1.22%   |
| Chicony Integrated IR Camera                                               | 3         | 1.22%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 3         | 1.22%   |
| Bison Lenovo EasyCamera                                                    | 3         | 1.22%   |
| Alcor Micro USB 2.0 Camera                                                 | 3         | 1.22%   |
| Tripath USB Camera                                                         | 2         | 0.81%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.81%   |
| SN0002 2K USB Camera                                                       | 2         | 0.81%   |
| Silicon Motion 720p HD Camera                                              | 2         | 0.81%   |
| Realtek USB Camera                                                         | 2         | 0.81%   |
| Quanta ACER HD User Facing                                                 | 2         | 0.81%   |
| Microsoft LifeCam Cinema                                                   | 2         | 0.81%   |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 0.81%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.81%   |
| Logitech B525 HD Webcam                                                    | 2         | 0.81%   |
| Lite-On Integrated Camera                                                  | 2         | 0.81%   |
| Importek FJ Camera                                                         | 2         | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 0.81%   |
| eMPIA M035 Compact Web Cam                                                 | 2         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 2         | 0.81%   |
| Bison BisonCam,NB Pro                                                      | 2         | 0.81%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                         | 2         | 0.81%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 0.81%   |
| Z-Star Sirius USB2.0 Camera                                                | 1         | 0.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 21        | 38.18%  |
| Validity Sensors                   | 9         | 16.36%  |
| Shenzhen Goodix Technology         | 9         | 16.36%  |
| LighTuning Technology              | 6         | 10.91%  |
| AuthenTec                          | 4         | 7.27%   |
| Upek                               | 3         | 5.45%   |
| Samsung Electronics                | 2         | 3.64%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.82%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader                | 8         | 14.55%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 5         | 9.09%   |
| Validity Sensors Synaptics WBDI                                 | 4         | 7.27%   |
| Shenzhen Goodix  Fingerprint Device                             | 4         | 7.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 3         | 5.45%   |
| Shenzhen Goodix FingerPrint                                     | 3         | 5.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 3         | 5.45%   |
| Synaptics WBDI                                                  | 2         | 3.64%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 3.64%   |
| LighTuning Fingerprint Sensor                                   | 2         | 3.64%   |
| AuthenTec Fingerprint Sensor                                    | 2         | 3.64%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 2         | 3.64%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 1.82%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 1.82%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 1.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.82%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.82%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.82%   |
| Synaptics UWP WBDI                                              | 1         | 1.82%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                    | 1         | 1.82%   |
| Synaptics  WBDI                                                 | 1         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.82%   |
| Samsung Fingerprint Sensor Device - 730B                        | 1         | 1.82%   |
| Samsung Fingerprint Device                                      | 1         | 1.82%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.82%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.82%   |
| Unknown                                                         | 1         | 1.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 27.78%  |
| Upek                  | 4         | 22.22%  |
| Advanced Card Systems | 3         | 16.67%  |
| Lenovo                | 2         | 11.11%  |
| Alcor Micro           | 2         | 11.11%  |
| Yubico.com            | 1         | 5.56%   |
| O2 Micro              | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 22.22%  |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 3         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 11.11%  |
| Broadcom 5880                                                                | 2         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 11.11%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.56%   |
| Broadcom 58200                                                               | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 326       | 67.22%  |
| 1     | 125       | 25.77%  |
| 2     | 22        | 4.54%   |
| 3     | 6         | 1.24%   |
| 4     | 4         | 0.82%   |
| 5     | 2         | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 24.88%  |
| Graphics card            | 49        | 23.9%   |
| Net/wireless             | 25        | 12.2%   |
| Multimedia controller    | 19        | 9.27%   |
| Communication controller | 16        | 7.8%    |
| Chipcard                 | 16        | 7.8%    |
| Camera                   | 7         | 3.41%   |
| Unassigned class         | 5         | 2.44%   |
| Sound                    | 4         | 1.95%   |
| Bluetooth                | 4         | 1.95%   |
| Storage                  | 2         | 0.98%   |
| Net/ethernet             | 2         | 0.98%   |
| Card reader              | 2         | 0.98%   |
| Storage/raid             | 1         | 0.49%   |
| Storage/ata              | 1         | 0.49%   |
| Network                  | 1         | 0.49%   |

