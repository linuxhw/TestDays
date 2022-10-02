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

Total: 436

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [87580733cb](https://linux-hardware.org/?probe=87580733cb) | Sep 08, 2022 |
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
| Lenovo        | ThinkPad X250 20CLA1VECD    | Notebook    | [ab1472b3cd](https://linux-hardware.org/?probe=ab1472b3cd) | Jul 15, 2022 |
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
| Dell          | XPS 15 9520                 | Notebook    | [eee1a317b6](https://linux-hardware.org/?probe=eee1a317b6) | May 30, 2022 |
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

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 46        | 15.08%  |
| Ubuntu 18.04        | 23        | 7.54%   |
| Ubuntu 22.04        | 13        | 4.26%   |
| OpenMandriva 4.2    | 13        | 4.26%   |
| Arch                | 11        | 3.61%   |
| antiX 21            | 9         | 2.95%   |
| Ubuntu 19.10        | 8         | 2.62%   |
| Debian 11           | 8         | 2.62%   |
| KDE neon 20.04      | 7         | 2.3%    |
| Ubuntu 20.10        | 6         | 1.97%   |
| OpenMandriva 4.3    | 6         | 1.97%   |
| Gentoo 2.7          | 6         | 1.97%   |
| Fedora 35           | 6         | 1.97%   |
| Fedora 32           | 6         | 1.97%   |
| ArcoLinux Rolling   | 6         | 1.97%   |
| Arch Rolling        | 6         | 1.97%   |
| Pop!_OS 22.04       | 5         | 1.64%   |
| EndeavourOS Rolling | 5         | 1.64%   |
| Ubuntu 21.04        | 4         | 1.31%   |
| Ubuntu 19.04        | 4         | 1.31%   |
| Pop!_OS 20.10       | 4         | 1.31%   |
| Linux Mint 20       | 4         | 1.31%   |
| Fedora 33           | 4         | 1.31%   |
| Ubuntu 21.10        | 3         | 0.98%   |
| Ubuntu 16.04        | 3         | 0.98%   |
| OpenMandriva 4.50   | 3         | 0.98%   |
| Linux Mint 20.3     | 3         | 0.98%   |
| Gentoo 2.8          | 3         | 0.98%   |
| Fedora 36           | 3         | 0.98%   |
| Elementary 5.1.7    | 3         | 0.98%   |
| Chrome OS           | 3         | 0.98%   |
| Zorin 15            | 2         | 0.66%   |
| Slackware 15.0      | 2         | 0.66%   |
| PostmarketOS Edge   | 2         | 0.66%   |
| Pop!_OS 21.04       | 2         | 0.66%   |
| Pop!_OS 20.04       | 2         | 0.66%   |
| Parrot 4.9          | 2         | 0.66%   |
| Manjaro 21.1.0      | 2         | 0.66%   |
| Manjaro 20.1        | 2         | 0.66%   |
| Kubuntu 21.10       | 2         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 104       | 35.25%  |
| Fedora        | 24        | 8.14%   |
| OpenMandriva  | 23        | 7.8%    |
| Arch          | 17        | 5.76%   |
| Pop!_OS       | 14        | 4.75%   |
| Linux Mint    | 10        | 3.39%   |
| Debian        | 10        | 3.39%   |
| Manjaro       | 9         | 3.05%   |
| antiX         | 9         | 3.05%   |
| Gentoo        | 8         | 2.71%   |
| KDE neon      | 7         | 2.37%   |
| EndeavourOS   | 6         | 2.03%   |
| ArcoLinux     | 6         | 2.03%   |
| Clear Linux   | 5         | 1.69%   |
| Elementary    | 4         | 1.36%   |
| Zorin         | 3         | 1.02%   |
| Slackware     | 3         | 1.02%   |
| ROSA          | 3         | 1.02%   |
| Kubuntu       | 3         | 1.02%   |
| Chrome OS     | 3         | 1.02%   |
| CentOS        | 3         | 1.02%   |
| Ubuntu Unity  | 2         | 0.68%   |
| Ubuntu MATE   | 2         | 0.68%   |
| PostmarketOS  | 2         | 0.68%   |
| Parrot        | 2         | 0.68%   |
| Kali          | 2         | 0.68%   |
| Xubuntu       | 1         | 0.34%   |
| UbuntuDDE     | 1         | 0.34%   |
| Ubuntu Budgie | 1         | 0.34%   |
| SteamOS       | 1         | 0.34%   |
| Raspbian      | 1         | 0.34%   |
| PCLinuxOS     | 1         | 0.34%   |
| Oracle Linux  | 1         | 0.34%   |
| openSUSE      | 1         | 0.34%   |
| Lubuntu       | 1         | 0.34%   |
| BlackPanther  | 1         | 0.34%   |
| Artix         | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002  | 12        | 3.59%   |
| 5.4.0-42-generic          | 9         | 2.69%   |
| 4.9.0-279-antix.1-486-smp | 8         | 2.4%    |
| 5.16.7-desktop-1omv4003   | 6         | 1.8%    |
| 5.15.0-46-generic         | 5         | 1.5%    |
| 5.13.0-39-generic         | 4         | 1.2%    |
| 5.13.0-35-generic         | 4         | 1.2%    |
| 5.8.0-7630-generic        | 3         | 0.9%    |
| 5.8.0-55-generic          | 3         | 0.9%    |
| 5.8.0-43-generic          | 3         | 0.9%    |
| 5.4.0-48-generic          | 3         | 0.9%    |
| 5.4.0-33-generic          | 3         | 0.9%    |
| 5.4.0-28-generic          | 3         | 0.9%    |
| 5.4.0-26-generic          | 3         | 0.9%    |
| 5.3.0-46-generic          | 3         | 0.9%    |
| 5.15.0-47-generic         | 3         | 0.9%    |
| 5.11.0-37-generic         | 3         | 0.9%    |
| 4.19.49+                  | 3         | 0.9%    |
| 5.9.2-arch1-1             | 2         | 0.6%    |
| 5.5.0-1parrot1-amd64      | 2         | 0.6%    |
| 5.4.0-58-generic          | 2         | 0.6%    |
| 5.4.0-56-generic          | 2         | 0.6%    |
| 5.4.0-52-generic          | 2         | 0.6%    |
| 5.4.0-47-generic          | 2         | 0.6%    |
| 5.4.0-109-generic         | 2         | 0.6%    |
| 5.3.0-24-generic          | 2         | 0.6%    |
| 5.3.0-18-generic          | 2         | 0.6%    |
| 5.17.5-76051705-generic   | 2         | 0.6%    |
| 5.17.11-300.fc36.x86_64   | 2         | 0.6%    |
| 5.16.12-200.fc35.x86_64   | 2         | 0.6%    |
| 5.13.0-7614-generic       | 2         | 0.6%    |
| 5.13.0-21-generic         | 2         | 0.6%    |
| 5.11.0-43-generic         | 2         | 0.6%    |
| 5.11.0-41-generic         | 2         | 0.6%    |
| 5.11.0-25-generic         | 2         | 0.6%    |
| 5.10.76-gentoo-r1-x86_64  | 2         | 0.6%    |
| 5.0.0-37-generic          | 2         | 0.6%    |
| 5.0.0-32-generic          | 2         | 0.6%    |
| 5.0.0-31-generic          | 2         | 0.6%    |
| 5.0.0-25-generic          | 2         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 13.06%  |
| 5.8.0   | 22        | 7.01%   |
| 5.13.0  | 19        | 6.05%   |
| 5.15.0  | 15        | 4.78%   |
| 5.11.0  | 15        | 4.78%   |
| 4.15.0  | 14        | 4.46%   |
| 5.3.0   | 12        | 3.82%   |
| 5.10.14 | 12        | 3.82%   |
| 5.0.0   | 10        | 3.18%   |
| 4.9.0   | 9         | 2.87%   |
| 5.10.0  | 7         | 2.23%   |
| 5.16.7  | 6         | 1.91%   |
| 4.18.0  | 5         | 1.59%   |
| 6.0.0   | 3         | 0.96%   |
| 5.19.0  | 3         | 0.96%   |
| 5.17.5  | 3         | 0.96%   |
| 4.19.49 | 3         | 0.96%   |
| 5.9.2   | 2         | 0.64%   |
| 5.5.0   | 2         | 0.64%   |
| 5.18.5  | 2         | 0.64%   |
| 5.17.4  | 2         | 0.64%   |
| 5.17.11 | 2         | 0.64%   |
| 5.16.12 | 2         | 0.64%   |
| 5.16.11 | 2         | 0.64%   |
| 5.14.14 | 2         | 0.64%   |
| 5.11.12 | 2         | 0.64%   |
| 5.10.76 | 2         | 0.64%   |
| 5.9.8   | 1         | 0.32%   |
| 5.9.4   | 1         | 0.32%   |
| 5.9.3   | 1         | 0.32%   |
| 5.9.16  | 1         | 0.32%   |
| 5.9.14  | 1         | 0.32%   |
| 5.9.12  | 1         | 0.32%   |
| 5.9.10  | 1         | 0.32%   |
| 5.9.0   | 1         | 0.32%   |
| 5.8.7   | 1         | 0.32%   |
| 5.8.6   | 1         | 0.32%   |
| 5.8.3   | 1         | 0.32%   |
| 5.8.16  | 1         | 0.32%   |
| 5.8.15  | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 13.23%  |
| 5.10    | 31        | 10%     |
| 5.8     | 28        | 9.03%   |
| 5.15    | 24        | 7.74%   |
| 5.13    | 23        | 7.42%   |
| 5.11    | 22        | 7.1%    |
| 5.3     | 15        | 4.84%   |
| 4.15    | 14        | 4.52%   |
| 5.16    | 13        | 4.19%   |
| 4.9     | 13        | 4.19%   |
| 5.17    | 12        | 3.87%   |
| 5.9     | 10        | 3.23%   |
| 5.19    | 10        | 3.23%   |
| 5.0     | 10        | 3.23%   |
| 5.18    | 7         | 2.26%   |
| 5.7     | 6         | 1.94%   |
| 5.14    | 6         | 1.94%   |
| 4.18    | 6         | 1.94%   |
| 6.0     | 3         | 0.97%   |
| 5.6     | 3         | 0.97%   |
| 5.5     | 3         | 0.97%   |
| 5.12    | 3         | 0.97%   |
| 4.19    | 3         | 0.97%   |
| 4.4     | 2         | 0.65%   |
| 4.17    | 1         | 0.32%   |
| 3.10    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 267       | 92.39%  |
| i686    | 12        | 4.15%   |
| aarch64 | 8         | 2.77%   |
| i586    | 1         | 0.35%   |
| armv7l  | 1         | 0.35%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 135       | 45.15%  |
| KDE5       | 55        | 18.39%  |
| Unknown    | 55        | 18.39%  |
| XFCE       | 11        | 3.68%   |
| KDE        | 8         | 2.68%   |
| X-Cinnamon | 7         | 2.34%   |
| MATE       | 4         | 1.34%   |
| i3         | 4         | 1.34%   |
| Pantheon   | 3         | 1%      |
| Unity      | 2         | 0.67%   |
| Openbox    | 2         | 0.67%   |
| LXDE       | 2         | 0.67%   |
| dwm        | 2         | 0.67%   |
| Deepin     | 2         | 0.67%   |
| sway       | 1         | 0.33%   |
| LXQt       | 1         | 0.33%   |
| KDE4       | 1         | 0.33%   |
| fvwm       | 1         | 0.33%   |
| Cinnamon   | 1         | 0.33%   |
| Budgie     | 1         | 0.33%   |
| awesome    | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 232       | 78.11%  |
| Wayland | 42        | 14.14%  |
| Unknown | 18        | 6.06%   |
| Tty     | 5         | 1.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 146       | 49.16%  |
| SDDM    | 57        | 19.19%  |
| GDM     | 41        | 13.8%   |
| GDM3    | 24        | 8.08%   |
| LightDM | 18        | 6.06%   |
| TDM     | 7         | 2.36%   |
| XDM     | 1         | 0.34%   |
| Ly      | 1         | 0.34%   |
| LXDM    | 1         | 0.34%   |
| KDM     | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 108       | 36.12%  |
| en_HK   | 78        | 26.09%  |
| Unknown | 34        | 11.37%  |
| zh_CN   | 30        | 10.03%  |
| zh_TW   | 14        | 4.68%   |
| zh_HK   | 13        | 4.35%   |
| en_GB   | 8         | 2.68%   |
| C       | 8         | 2.68%   |
| en_AU   | 3         | 1%      |
| it_IT   | 1         | 0.33%   |
| en_ZA   | 1         | 0.33%   |
| de_DE   | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 177       | 60.2%   |
| BIOS | 117       | 39.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 216       | 73.47%  |
| Btrfs   | 32        | 10.88%  |
| Overlay | 20        | 6.8%    |
| Xfs     | 8         | 2.72%   |
| Unknown | 8         | 2.72%   |
| Zfs     | 5         | 1.7%    |
| Ext3    | 2         | 0.68%   |
| Ext2    | 2         | 0.68%   |
| F2fs    | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 138       | 46.94%  |
| GPT     | 125       | 42.52%  |
| MBR     | 31        | 10.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 253       | 86.35%  |
| Yes       | 40        | 13.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 192       | 65.31%  |
| Yes       | 102       | 34.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 59        | 20.42%  |
| ASUSTek Computer        | 44        | 15.22%  |
| Dell                    | 27        | 9.34%   |
| MSI                     | 22        | 7.61%   |
| Hewlett-Packard         | 22        | 7.61%   |
| Gigabyte Technology     | 21        | 7.27%   |
| Fujitsu                 | 12        | 4.15%   |
| ASRock                  | 12        | 4.15%   |
| Unknown                 | 12        | 4.15%   |
| Acer                    | 7         | 2.42%   |
| HUAWEI                  | 5         | 1.73%   |
| Apple                   | 5         | 1.73%   |
| Raspberry Pi Foundation | 4         | 1.38%   |
| Intel                   | 4         | 1.38%   |
| Supermicro              | 3         | 1.04%   |
| Toshiba                 | 2         | 0.69%   |
| Samsung Electronics     | 2         | 0.69%   |
| KOHJINSHA               | 2         | 0.69%   |
| IBM                     | 2         | 0.69%   |
| GPD                     | 2         | 0.69%   |
| AMI                     | 2         | 0.69%   |
| ZOTAC                   | 1         | 0.35%   |
| Timi                    | 1         | 0.35%   |
| Soyo                    | 1         | 0.35%   |
| Sony                    | 1         | 0.35%   |
| Seco                    | 1         | 0.35%   |
| Schenker                | 1         | 0.35%   |
| Panasonic               | 1         | 0.35%   |
| Nvidia                  | 1         | 0.35%   |
| Jumper                  | 1         | 0.35%   |
| Intel Client Systems    | 1         | 0.35%   |
| Huanan                  | 1         | 0.35%   |
| Hardkernel              | 1         | 0.35%   |
| Google                  | 1         | 0.35%   |
| Foxconn                 | 1         | 0.35%   |
| CompuLab                | 1         | 0.35%   |
| Compaq                  | 1         | 0.35%   |
| Chuwi                   | 1         | 0.35%   |
| Biostar                 | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 13        | 4.5%    |
| Lenovo Legion R7000 2020 82B6          | 3         | 1.04%   |
| ASUS H110I-PLUS                        | 3         | 1.04%   |
| ASUS All Series                        | 3         | 1.04%   |
| RPi Raspberry Pi                       | 2         | 0.69%   |
| MSI MS-7C94                            | 2         | 0.69%   |
| IBM 260921H                            | 2         | 0.69%   |
| HUAWEI KPRC-WX0                        | 2         | 0.69%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC       | 2         | 0.69%   |
| HP ProDesk 600 G1 SFF                  | 2         | 0.69%   |
| HP EliteBook 2540p                     | 2         | 0.69%   |
| Gigabyte X570 AORUS ELITE              | 2         | 0.69%   |
| Fujitsu UH-X                           | 2         | 0.69%   |
| Fujitsu LIFEBOOK AH544                 | 2         | 0.69%   |
| Dell XPS 13 9310                       | 2         | 0.69%   |
| Dell Inspiron 5580                     | 2         | 0.69%   |
| ASUS Z8NA-D6                           | 2         | 0.69%   |
| ASUS VM65                              | 2         | 0.69%   |
| ASUS VM62                              | 2         | 0.69%   |
| ASUS TUF Gaming FA506IU_FA506IU        | 2         | 0.69%   |
| ASRock H410M-ITX/ac                    | 2         | 0.69%   |
| ASRock H410M-HDV                       | 2         | 0.69%   |
| AMI Aptio CRB                          | 2         | 0.69%   |
| ZOTAC ZBOX-ID92/ZBOX-IQ01              | 1         | 0.35%   |
| Toshiba PORTEGE R830                   | 1         | 0.35%   |
| Toshiba dynabook R731/E                | 1         | 0.35%   |
| Timi TM1607                            | 1         | 0.35%   |
| Supermicro X9DRD-7LN4F(-JBOD)/X9DRD-EF | 1         | 0.35%   |
| Supermicro PIO-617R-TLN4F+-ST031       | 1         | 0.35%   |
| Supermicro C2SBC-Q                     | 1         | 0.35%   |
| Soyo SY-A68M FS V2.0                   | 1         | 0.35%   |
| Sony VPCCB17FG                         | 1         | 0.35%   |
| Seco C40                               | 1         | 0.35%   |
| Schenker XMG_APEX15_XAP15E20           | 1         | 0.35%   |
| Samsung SQ1S                           | 1         | 0.35%   |
| Samsung 930XBE                         | 1         | 0.35%   |
| RPi Raspberry Pi Zero 2 Rev 1.0        | 1         | 0.35%   |
| RPi Raspberry Pi 400 Rev 1.0           | 1         | 0.35%   |
| Panasonic CFSZ5-2L                     | 1         | 0.35%   |
| Nvidia Tegra                           | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 25        | 8.65%   |
| Unknown            | 13        | 4.5%    |
| Fujitsu LIFEBOOK   | 8         | 2.77%   |
| Dell Inspiron      | 8         | 2.77%   |
| Dell XPS           | 7         | 2.42%   |
| Lenovo Legion      | 6         | 2.08%   |
| ASUS PRIME         | 6         | 2.08%   |
| Lenovo IdeaPad     | 5         | 1.73%   |
| Dell Precision     | 5         | 1.73%   |
| ASUS TUF           | 5         | 1.73%   |
| RPi Raspberry      | 4         | 1.38%   |
| Lenovo Yoga        | 4         | 1.38%   |
| ASUS ROG           | 4         | 1.38%   |
| Acer Aspire        | 4         | 1.38%   |
| Lenovo ThinkCentre | 3         | 1.04%   |
| HP ProDesk         | 3         | 1.04%   |
| HP EliteBook       | 3         | 1.04%   |
| Gigabyte X570      | 3         | 1.04%   |
| Dell OptiPlex      | 3         | 1.04%   |
| Dell Latitude      | 3         | 1.04%   |
| ASUS H110I-PLUS    | 3         | 1.04%   |
| ASUS All           | 3         | 1.04%   |
| Acer Swift         | 3         | 1.04%   |
| MSI MS-7C94        | 2         | 0.69%   |
| Lenovo ThinkBook   | 2         | 0.69%   |
| Lenovo IdeaPadFlex | 2         | 0.69%   |
| Lenovo IdeaCentre  | 2         | 0.69%   |
| IBM 260921H        | 2         | 0.69%   |
| HUAWEI KPRC-WX0    | 2         | 0.69%   |
| HP ZHAN            | 2         | 0.69%   |
| Fujitsu UH-X       | 2         | 0.69%   |
| ASUS Z8NA-D6       | 2         | 0.69%   |
| ASUS VM65          | 2         | 0.69%   |
| ASUS VM62          | 2         | 0.69%   |
| ASRock H410M-ITX   | 2         | 0.69%   |
| ASRock H410M-HDV   | 2         | 0.69%   |
| AMI Aptio          | 2         | 0.69%   |
| ZOTAC ZBOX-ID92    | 1         | 0.35%   |
| Toshiba PORTEGE    | 1         | 0.35%   |
| Toshiba dynabook   | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 41        | 14.19%  |
| 2020    | 40        | 13.84%  |
| 2019    | 30        | 10.38%  |
| 2021    | 27        | 9.34%   |
| 2013    | 17        | 5.88%   |
| 2011    | 16        | 5.54%   |
| 2010    | 16        | 5.54%   |
| 2016    | 15        | 5.19%   |
| 2015    | 15        | 5.19%   |
| 2014    | 15        | 5.19%   |
| 2017    | 12        | 4.15%   |
| 2012    | 10        | 3.46%   |
| 2008    | 8         | 2.77%   |
| Unknown | 8         | 2.77%   |
| 2022    | 6         | 2.08%   |
| 2009    | 5         | 1.73%   |
| 2007    | 4         | 1.38%   |
| 1999    | 2         | 0.69%   |
| 2005    | 1         | 0.35%   |
| 2003    | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 149       | 51.56%  |
| Desktop        | 118       | 40.83%  |
| Mini pc        | 7         | 2.42%   |
| System on chip | 6         | 2.08%   |
| Convertible    | 5         | 1.73%   |
| All in one     | 2         | 0.69%   |
| Tablet         | 1         | 0.35%   |
| Server         | 1         | 0.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 265       | 91.7%   |
| Enabled  | 24        | 8.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 288       | 99.65%  |
| Yes  | 1         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 64        | 21.92%  |
| 8.01-16.0   | 64        | 21.92%  |
| 4.01-8.0    | 50        | 17.12%  |
| 32.01-64.0  | 39        | 13.36%  |
| 3.01-4.0    | 31        | 10.62%  |
| 64.01-256.0 | 18        | 6.16%   |
| 1.01-2.0    | 7         | 2.4%    |
| 24.01-32.0  | 6         | 2.05%   |
| 2.01-3.0    | 6         | 2.05%   |
| 0.51-1.0    | 4         | 1.37%   |
| 0.01-0.5    | 3         | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 90        | 29.03%  |
| 2.01-3.0   | 69        | 22.26%  |
| 4.01-8.0   | 53        | 17.1%   |
| 3.01-4.0   | 41        | 13.23%  |
| 8.01-16.0  | 19        | 6.13%   |
| 0.01-0.5   | 17        | 5.48%   |
| 0.51-1.0   | 15        | 4.84%   |
| 16.01-24.0 | 5         | 1.61%   |
| 24.01-32.0 | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 160       | 53.51%  |
| 2      | 87        | 29.1%   |
| 3      | 28        | 9.36%   |
| 5      | 7         | 2.34%   |
| 4      | 7         | 2.34%   |
| 0      | 5         | 1.67%   |
| 9      | 2         | 0.67%   |
| 6      | 2         | 0.67%   |
| 7      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 217       | 74.32%  |
| Yes       | 75        | 25.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 234       | 80.97%  |
| No        | 55        | 19.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 223       | 76.11%  |
| No        | 70        | 23.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 62.24%  |
| No        | 111       | 37.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Hong Kong | 289       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Central          | 159       | 52.48%  |
| Shatin           | 12        | 3.96%   |
| Kowloon          | 12        | 3.96%   |
| Tuen Mun         | 11        | 3.63%   |
| Tseung Kwan O    | 10        | 3.3%    |
| Wanchai          | 9         | 2.97%   |
| Hong Kong        | 8         | 2.64%   |
| Tung Chung       | 6         | 1.98%   |
| Ngau Wu Tok      | 6         | 1.98%   |
| Hung Hom         | 6         | 1.98%   |
| Yuen Long        | 5         | 1.65%   |
| Tai Po           | 5         | 1.65%   |
| To Kwa Wan       | 4         | 1.32%   |
| Sai Kung         | 4         | 1.32%   |
| Quarry Bay       | 3         | 0.99%   |
| Ma On Shan Tsuen | 3         | 0.99%   |
| Tai Wan To       | 2         | 0.66%   |
| Sheung Shui      | 2         | 0.66%   |
| Man Kok          | 2         | 0.66%   |
| Kwun Hang        | 2         | 0.66%   |
| Kwu Tung         | 2         | 0.66%   |
| Kowloon Bay      | 2         | 0.66%   |
| Fanling          | 2         | 0.66%   |
| Discovery Bay    | 2         | 0.66%   |
| Cheung Sha Lan   | 2         | 0.66%   |
| Yau Tsim Mong    | 1         | 0.33%   |
| Wong Tai Sin     | 1         | 0.33%   |
| Tsuen Wan        | 1         | 0.33%   |
| Tsimshatsui      | 1         | 0.33%   |
| Tin Shui Wai     | 1         | 0.33%   |
| Tai Wan          | 1         | 0.33%   |
| Tai Kok Tsui     | 1         | 0.33%   |
| So Kon Po        | 1         | 0.33%   |
| Shau Kei Wan     | 1         | 0.33%   |
| Sham Shui Po     | 1         | 0.33%   |
| Sha Tin Wai      | 1         | 0.33%   |
| North Point      | 1         | 0.33%   |
| North            | 1         | 0.33%   |
| Mong Kok         | 1         | 0.33%   |
| Ma Wan           | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 65        | 84     | 14.57%  |
| WDC                         | 57        | 84     | 12.78%  |
| Seagate                     | 52        | 71     | 11.66%  |
| Toshiba                     | 25        | 32     | 5.61%   |
| SanDisk                     | 22        | 23     | 4.93%   |
| Kingston                    | 19        | 21     | 4.26%   |
| Unknown                     | 17        | 21     | 3.81%   |
| Hitachi                     | 16        | 21     | 3.59%   |
| Intel                       | 14        | 20     | 3.14%   |
| A-DATA Technology           | 14        | 20     | 3.14%   |
| SK hynix                    | 12        | 16     | 2.69%   |
| HGST                        | 10        | 11     | 2.24%   |
| Crucial                     | 10        | 17     | 2.24%   |
| Fujitsu                     | 8         | 14     | 1.79%   |
| Silicon Motion              | 6         | 7      | 1.35%   |
| Phison                      | 6         | 9      | 1.35%   |
| Micron Technology           | 6         | 7      | 1.35%   |
| JMicron Technology          | 6         | 10     | 1.35%   |
| Apple                       | 5         | 8      | 1.12%   |
| Transcend                   | 4         | 4      | 0.9%    |
| LITEON                      | 4         | 4      | 0.9%    |
| Hikvision                   | 4         | 4      | 0.9%    |
| China                       | 4         | 5      | 0.9%    |
| Unknown                     | 4         | 4      | 0.9%    |
| Team                        | 3         | 3      | 0.67%   |
| Plextor                     | 3         | 4      | 0.67%   |
| KIOXIA                      | 3         | 3      | 0.67%   |
| DOGGO                       | 3         | 3      | 0.67%   |
| ZHITAI                      | 2         | 3      | 0.45%   |
| Lite-On                     | 2         | 4      | 0.45%   |
| Lexar                       | 2         | 2      | 0.45%   |
| KingSpec                    | 2         | 3      | 0.45%   |
| HS-SSD-C100                 | 2         | 3      | 0.45%   |
| Gigabyte Technology         | 2         | 5      | 0.45%   |
| BIWIN                       | 2         | 2      | 0.45%   |
| Apacer                      | 2         | 7      | 0.45%   |
| Yangtze Memory Technologies | 1         | 1      | 0.22%   |
| XPG                         | 1         | 1      | 0.22%   |
| Verbatim                    | 1         | 2      | 0.22%   |
| Unknown (CF)                | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB              | 6         | 1.25%   |
| Samsung NVMe SSD Drive 512GB         | 6         | 1.25%   |
| Toshiba DT01ACA100 1TB               | 5         | 1.04%   |
| JMicron Generic 120GB                | 5         | 1.04%   |
| Fujitsu F300 480GB                   | 5         | 1.04%   |
| A-DATA SP550 240GB SSD               | 5         | 1.04%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 0.84%   |
| Unknown MMC Card  32GB               | 4         | 0.84%   |
| Toshiba DT01ACA050 500GB             | 4         | 0.84%   |
| Samsung NVMe SSD Drive 1024GB        | 4         | 0.84%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.84%   |
| Crucial CT500MX500SSD1 500GB         | 4         | 0.84%   |
| Unknown                              | 4         | 0.84%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 3         | 0.63%   |
| Unknown MMC Card  64GB               | 3         | 0.63%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 0.63%   |
| Seagate ST3500413AS 500GB            | 3         | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 0.63%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 0.63%   |
| SanDisk NVMe SSD Drive 1TB           | 3         | 0.63%   |
| Samsung SSD 970 EVO Plus 2TB         | 3         | 0.63%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.63%   |
| Samsung NVMe SSD Drive 1TB           | 3         | 0.63%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.63%   |
| DOGGO DQ-60G SSD                     | 3         | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.42%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 2         | 0.42%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 2         | 0.42%   |
| WDC WD30EZRX-00D8PB0 3TB             | 2         | 0.42%   |
| WDC WD10SPZX-22Z10T1 1TB             | 2         | 0.42%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 2         | 0.42%   |
| Unknown SD32G  32GB                  | 2         | 0.42%   |
| Unknown MMC Card  128GB              | 2         | 0.42%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.42%   |
| Toshiba DT01ACA300 3TB               | 2         | 0.42%   |
| SK hynix SC311 SATA 128GB SSD        | 2         | 0.42%   |
| SK hynix BC501 NVMe 128GB            | 2         | 0.42%   |
| Silicon Motion NVMe SSD Drive 512GB  | 2         | 0.42%   |
| Silicon Motion NVMe SSD Drive 1024GB | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 71     | 36.62%  |
| WDC                 | 35        | 57     | 24.65%  |
| Toshiba             | 22        | 29     | 15.49%  |
| Hitachi             | 16        | 21     | 11.27%  |
| HGST                | 10        | 11     | 7.04%   |
| Fujitsu             | 2         | 2      | 1.41%   |
| Unknown             | 1         | 1      | 0.7%    |
| Samsung Electronics | 1         | 1      | 0.7%    |
| JMicron Technology  | 1         | 2      | 0.7%    |
| HGST HTS            | 1         | 1      | 0.7%    |
| Apple               | 1         | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 35     | 18.66%  |
| Kingston            | 13        | 14     | 9.7%    |
| A-DATA Technology   | 12        | 18     | 8.96%   |
| WDC                 | 9         | 9      | 6.72%   |
| Crucial             | 9         | 16     | 6.72%   |
| SanDisk             | 6         | 6      | 4.48%   |
| Intel               | 5         | 9      | 3.73%   |
| Fujitsu             | 5         | 11     | 3.73%   |
| Transcend           | 4         | 4      | 2.99%   |
| China               | 4         | 5      | 2.99%   |
| Team                | 3         | 3      | 2.24%   |
| SK hynix            | 3         | 7      | 2.24%   |
| LITEON              | 3         | 3      | 2.24%   |
| DOGGO               | 3         | 3      | 2.24%   |
| ZHITAI              | 2         | 2      | 1.49%   |
| Plextor             | 2         | 3      | 1.49%   |
| Micron Technology   | 2         | 3      | 1.49%   |
| Lexar               | 2         | 2      | 1.49%   |
| Hikvision           | 2         | 2      | 1.49%   |
| Apacer              | 2         | 7      | 1.49%   |
| Verbatim            | 1         | 2      | 0.75%   |
| Unknown (CF)        | 1         | 1      | 0.75%   |
| TO Exter            | 1         | 1      | 0.75%   |
| tigo                | 1         | 1      | 0.75%   |
| SPCC                | 1         | 1      | 0.75%   |
| RECADATA            | 1         | 1      | 0.75%   |
| Ramsta              | 1         | 1      | 0.75%   |
| PNY                 | 1         | 1      | 0.75%   |
| OCZ                 | 1         | 1      | 0.75%   |
| Netac               | 1         | 1      | 0.75%   |
| Dogfish             | 1         | 1      | 0.75%   |
| DGM                 | 1         | 1      | 0.75%   |
| Corsair             | 1         | 1      | 0.75%   |
| BIWIN               | 1         | 1      | 0.75%   |
| Apple               | 1         | 1      | 0.75%   |
| Aoluska             | 1         | 1      | 0.75%   |
| AGI                 | 1         | 1      | 0.75%   |
| Unknown             | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 127       | 176    | 32.07%  |
| HDD     | 123       | 197    | 31.06%  |
| SSD     | 117       | 181    | 29.55%  |
| MMC     | 18        | 22     | 4.55%   |
| Unknown | 11        | 14     | 2.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 190       | 368    | 53.37%  |
| NVMe | 124       | 167    | 34.83%  |
| SAS  | 24        | 33     | 6.74%   |
| MMC  | 18        | 22     | 5.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 138       | 222    | 57.02%  |
| 0.51-1.0   | 64        | 83     | 26.45%  |
| 1.01-2.0   | 20        | 25     | 8.26%   |
| 2.01-3.0   | 8         | 13     | 3.31%   |
| 3.01-4.0   | 7         | 28     | 2.89%   |
| 4.01-10.0  | 4         | 6      | 1.65%   |
| 10.01-20.0 | 1         | 1      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 77        | 25.33%  |
| 251-500        | 58        | 19.08%  |
| 501-1000       | 43        | 14.14%  |
| 1001-2000      | 29        | 9.54%   |
| 51-100         | 27        | 8.88%   |
| 1-20           | 23        | 7.57%   |
| More than 3000 | 14        | 4.61%   |
| 2001-3000      | 12        | 3.95%   |
| Unknown        | 12        | 3.95%   |
| 21-50          | 9         | 2.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 133       | 41.69%  |
| 101-250        | 37        | 11.6%   |
| 21-50          | 36        | 11.29%  |
| 251-500        | 34        | 10.66%  |
| 51-100         | 33        | 10.34%  |
| 501-1000       | 16        | 5.02%   |
| Unknown        | 12        | 3.76%   |
| 1001-2000      | 11        | 3.45%   |
| 2001-3000      | 5         | 1.57%   |
| More than 3000 | 2         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WD8088AADS-00M2B0 809GB               | 1         | 1      | 3.57%   |
| WDC WD30EZRX-00D8PB0 3TB                  | 1         | 1      | 3.57%   |
| WDC WD10EZEX-60WN4A1 1TB                  | 1         | 1      | 3.57%   |
| WDC WD10EZEX-00RKKA0 1TB                  | 1         | 1      | 3.57%   |
| WDC WD10EALS-00Z8A0 1TB                   | 1         | 2      | 3.57%   |
| Toshiba MK1252GSX 120GB                   | 1         | 1      | 3.57%   |
| Toshiba DT01ACA100 1TB                    | 1         | 1      | 3.57%   |
| Seagate ST9500325AS 500GB                 | 1         | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 3.57%   |
| Seagate ST3500418AS 500GB                 | 1         | 1      | 3.57%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 3.57%   |
| Seagate ST3160815AS 160GB                 | 1         | 1      | 3.57%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB       | 1         | 1      | 3.57%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD       | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 860 EVO 1TB       | 1         | 1      | 3.57%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD | 1         | 1      | 3.57%   |
| Kingston SA400S37480G 480GB SSD           | 1         | 1      | 3.57%   |
| Intel SSDPEKKW128G7 128GB                 | 1         | 1      | 3.57%   |
| Hitachi HTS725050A7E630 500GB             | 1         | 1      | 3.57%   |
| Hitachi HTS723216L9A360 160GB             | 1         | 1      | 3.57%   |
| Hitachi HTS542512K9SA00 120GB             | 1         | 1      | 3.57%   |
| Hitachi HTC426040G8CE00 40GB              | 1         | 1      | 3.57%   |
| Hitachi DK23AA-60 6GB                     | 1         | 1      | 3.57%   |
| HGST TOURO Mobile 1TB                     | 1         | 1      | 3.57%   |
| HGST HTS 541010A9E680 1TB                 | 1         | 1      | 3.57%   |
| DGM SSD 120GB S3-120A                     | 1         | 1      | 3.57%   |
| Crucial CT500MX500SSD1 500GB              | 1         | 2      | 3.57%   |
| Crucial CT240M500SSD1 240GB               | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 22.22%  |
| Hitachi             | 5         | 5      | 18.52%  |
| WDC                 | 4         | 6      | 14.81%  |
| Toshiba             | 2         | 2      | 7.41%   |
| Crucial             | 2         | 3      | 7.41%   |
| SanDisk             | 1         | 1      | 3.7%    |
| Samsung Electronics | 1         | 1      | 3.7%    |
| LITEON              | 1         | 1      | 3.7%    |
| Kingston            | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| HGST HTS            | 1         | 1      | 3.7%    |
| HGST                | 1         | 1      | 3.7%    |
| DGM                 | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 6         | 6      | 31.58%  |
| Hitachi  | 5         | 5      | 26.32%  |
| WDC      | 4         | 6      | 21.05%  |
| Toshiba  | 2         | 2      | 10.53%  |
| HGST HTS | 1         | 1      | 5.26%   |
| HGST     | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 21     | 69.23%  |
| SSD  | 7         | 8      | 26.92%  |
| NVMe | 1         | 1      | 3.85%   |

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
| Detected | 156       | 320    | 49.68%  |
| Works    | 132       | 240    | 42.04%  |
| Malfunc  | 26        | 30     | 8.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 198       | 51.03%  |
| Samsung Electronics           | 44        | 11.34%  |
| AMD                           | 39        | 10.05%  |
| SanDisk                       | 29        | 7.47%   |
| SK hynix                      | 9         | 2.32%   |
| Silicon Motion                | 9         | 2.32%   |
| Phison Electronics            | 9         | 2.32%   |
| ASMedia Technology            | 8         | 2.06%   |
| Kingston Technology Company   | 6         | 1.55%   |
| Toshiba America Info Systems  | 4         | 1.03%   |
| Micron Technology             | 4         | 1.03%   |
| Marvell Technology Group      | 4         | 1.03%   |
| KIOXIA                        | 3         | 0.77%   |
| ADATA Technology              | 3         | 0.77%   |
| Yangtze Memory Technologies   | 2         | 0.52%   |
| VIA Technologies              | 2         | 0.52%   |
| Nvidia                        | 2         | 0.52%   |
| Micron/Crucial Technology     | 2         | 0.52%   |
| Lite-On Technology            | 2         | 0.52%   |
| JMicron Technology            | 2         | 0.52%   |
| Apple                         | 2         | 0.52%   |
| LSI Logic / Symbios Logic     | 1         | 0.26%   |
| Lenovo                        | 1         | 0.26%   |
| Integrated Technology Express | 1         | 0.26%   |
| Huawei Technologies           | 1         | 0.26%   |
| Biwin Storage Technology      | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 28        | 6.54%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 26        | 6.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 18        | 4.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 3.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 12        | 2.8%    |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 2.57%   |
| AMD 400 Series Chipset SATA Controller                                         | 11        | 2.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 2.34%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 2.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 2.1%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 7         | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 1.64%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.64%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 7         | 1.64%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 6         | 1.4%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 6         | 1.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 6         | 1.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6         | 1.4%    |
| SanDisk Non-Volatile memory controller                                         | 5         | 1.17%   |
| Intel SSD 660P Series                                                          | 5         | 1.17%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.17%   |
| SK hynix Gold P31 SSD                                                          | 4         | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 0.93%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 0.93%   |
| Micron Non-Volatile memory controller                                          | 4         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.93%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4         | 0.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.7%    |
| Phison E12 NVMe Controller                                                     | 3         | 0.7%    |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.7%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 203       | 53.42%  |
| NVMe | 125       | 32.89%  |
| IDE  | 30        | 7.89%   |
| RAID | 20        | 5.26%   |
| SAS  | 2         | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 226       | 78.2%   |
| AMD          | 53        | 18.34%  |
| ARM          | 5         | 1.73%   |
| Unknown      | 3         | 1.04%   |
| HISILICON    | 1         | 0.35%   |
| GenuineTMx86 | 1         | 0.35%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 2.07%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.72%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 4         | 1.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.38%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.38%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 1.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.38%   |
| ARM Processor                                 | 4         | 1.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.03%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 3         | 1.03%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 3         | 1.03%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 3         | 1.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.03%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 3         | 1.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.03%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 1.03%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 3         | 1.03%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.03%   |
|                                               | 3         | 1.03%   |
| Intel Xeon CPU X5675 @ 3.07GHz                | 2         | 0.69%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 0.69%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 2         | 0.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.69%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.69%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.69%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.69%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2         | 0.69%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 2         | 0.69%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.69%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 60        | 20.69%  |
| Intel Core i5           | 56        | 19.31%  |
| Other                   | 34        | 11.72%  |
| Intel Core i3           | 21        | 7.24%   |
| Intel Celeron           | 21        | 7.24%   |
| AMD Ryzen 7             | 17        | 5.86%   |
| AMD Ryzen 5             | 17        | 5.86%   |
| Intel Xeon              | 12        | 4.14%   |
| AMD Ryzen 9             | 7         | 2.41%   |
| Intel Pentium           | 5         | 1.72%   |
| Intel Core 2 Duo        | 5         | 1.72%   |
| Intel Atom              | 4         | 1.38%   |
| Intel Core m3           | 3         | 1.03%   |
| AMD Phenom II X4        | 3         | 1.03%   |
| Intel Pentium Gold      | 2         | 0.69%   |
| Intel Pentium Dual-Core | 2         | 0.69%   |
| Intel Pentium Dual      | 2         | 0.69%   |
| Intel Core i9           | 2         | 0.69%   |
| AMD Ryzen 7 PRO         | 2         | 0.69%   |
| Intel Pentium Silver    | 1         | 0.34%   |
| Intel Pentium M         | 1         | 0.34%   |
| Intel Genuine           | 1         | 0.34%   |
| Intel Core 2 Quad       | 1         | 0.34%   |
| Intel Core 2 Extreme    | 1         | 0.34%   |
| Intel Core 2            | 1         | 0.34%   |
| ARM BCM                 | 1         | 0.34%   |
| AMD Ryzen Threadripper  | 1         | 0.34%   |
| AMD Ryzen Embedded      | 1         | 0.34%   |
| AMD Phenom II X6        | 1         | 0.34%   |
| AMD FX                  | 1         | 0.34%   |
| AMD Athlon II X3        | 1         | 0.34%   |
| AMD Athlon 64 X2        | 1         | 0.34%   |
| AMD A8                  | 1         | 0.34%   |
| AMD A10                 | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 110       | 37.93%  |
| 2       | 85        | 29.31%  |
| 8       | 35        | 12.07%  |
| 6       | 28        | 9.66%   |
| 12      | 10        | 3.45%   |
| 1       | 9         | 3.1%    |
| 14      | 3         | 1.03%   |
| 24      | 2         | 0.69%   |
| 16      | 2         | 0.69%   |
| 10      | 2         | 0.69%   |
| 3       | 2         | 0.69%   |
| Unknown | 2         | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 282       | 97.58%  |
| 2       | 5         | 1.73%   |
| Unknown | 2         | 0.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 201       | 69.07%  |
| 1       | 88        | 30.24%  |
| Unknown | 2         | 0.69%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 269       | 93.08%  |
| 32-bit         | 9         | 3.11%   |
| Unknown        | 9         | 3.11%   |
| 64-bit         | 2         | 0.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 21.36%  |
| 0x306c3    | 16        | 5.42%   |
| 0x206a7    | 16        | 5.42%   |
| 0x806e9    | 12        | 4.07%   |
| 0x906ea    | 10        | 3.39%   |
| 0x806ea    | 9         | 3.05%   |
| 0x806c1    | 9         | 3.05%   |
| 0x306a9    | 9         | 3.05%   |
| 0x506e3    | 8         | 2.71%   |
| 0x40651    | 7         | 2.37%   |
| 0x0a50000c | 6         | 2.03%   |
| 0x906ed    | 5         | 1.69%   |
| 0x906e9    | 5         | 1.69%   |
| 0x806eb    | 5         | 1.69%   |
| 0x506c9    | 5         | 1.69%   |
| 0x08600106 | 5         | 1.69%   |
| 0x806ec    | 4         | 1.36%   |
| 0x406e3    | 4         | 1.36%   |
| 0x20655    | 4         | 1.36%   |
| 0x106c2    | 4         | 1.36%   |
| 0x1067a    | 4         | 1.36%   |
| 0xa0653    | 3         | 1.02%   |
| 0xa0652    | 3         | 1.02%   |
| 0x906a3    | 3         | 1.02%   |
| 0x90672    | 3         | 1.02%   |
| 0x706e5    | 3         | 1.02%   |
| 0x6fd      | 3         | 1.02%   |
| 0x306e4    | 3         | 1.02%   |
| 0x20652    | 3         | 1.02%   |
| 0x0a201009 | 3         | 1.02%   |
| 0x08701013 | 3         | 1.02%   |
| 0x08600104 | 3         | 1.02%   |
| 0x08108102 | 3         | 1.02%   |
| 0x0800820d | 3         | 1.02%   |
| 0xa0671    | 2         | 0.68%   |
| 0x806d1    | 2         | 0.68%   |
| 0x706a8    | 2         | 0.68%   |
| 0x706a1    | 2         | 0.68%   |
| 0x66a      | 2         | 0.68%   |
| 0x306d4    | 2         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 56        | 19.31%  |
| Haswell          | 28        | 9.66%   |
| Zen 2            | 20        | 6.9%    |
| SandyBridge      | 20        | 6.9%    |
| Unknown          | 18        | 6.21%   |
| Skylake          | 16        | 5.52%   |
| IvyBridge        | 16        | 5.52%   |
| Zen 3            | 13        | 4.48%   |
| TigerLake        | 12        | 4.14%   |
| Westmere         | 10        | 3.45%   |
| CometLake        | 10        | 3.45%   |
| Zen+             | 9         | 3.1%    |
| Icelake          | 9         | 3.1%    |
| Penryn           | 6         | 2.07%   |
| Goldmont         | 6         | 2.07%   |
| Core             | 6         | 2.07%   |
| K10              | 5         | 1.72%   |
| Alderlake Hybrid | 5         | 1.72%   |
| Goldmont plus    | 4         | 1.38%   |
| Broadwell        | 4         | 1.38%   |
| Bonnell          | 4         | 1.38%   |
| Silvermont       | 3         | 1.03%   |
| Zen              | 2         | 0.69%   |
| Steamroller      | 2         | 0.69%   |
| P6               | 2         | 0.69%   |
| Tremont          | 1         | 0.34%   |
| Piledriver       | 1         | 0.34%   |
| Nehalem          | 1         | 0.34%   |
| K8 Hammer        | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 173       | 51.18%  |
| Nvidia                     | 102       | 30.18%  |
| AMD                        | 58        | 17.16%  |
| Neomagic                   | 2         | 0.59%   |
| S3 Graphics                | 1         | 0.3%    |
| Matrox Electronics Systems | 1         | 0.3%    |
| ASPEED Technology          | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 15        | 4.35%   |
| AMD Renoir                                                                    | 11        | 3.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 10        | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 9         | 2.61%   |
| Intel UHD Graphics 620                                                        | 9         | 2.61%   |
| AMD Cezanne                                                                   | 9         | 2.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 8         | 2.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 2.03%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 7         | 2.03%   |
| Intel HD Graphics 620                                                         | 6         | 1.74%   |
| Intel HD Graphics 530                                                         | 6         | 1.74%   |
| Intel HD Graphics 500                                                         | 6         | 1.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 6         | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 1.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 1.45%   |
| Nvidia GP108M [GeForce MX150]                                                 | 4         | 1.16%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 4         | 1.16%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 4         | 1.16%   |
| Nvidia GM107 [GeForce GTX 750]                                                | 4         | 1.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 1.16%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 4         | 1.16%   |
| Intel HD Graphics 615                                                         | 4         | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 4         | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 1.16%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 4         | 1.16%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 4         | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 4         | 1.16%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 3         | 0.87%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 3         | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 3         | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 3         | 0.87%   |
| Nvidia GK208B [GeForce GT 730]                                                | 3         | 0.87%   |
| Nvidia GK208B [GeForce GT 710]                                                | 3         | 0.87%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 3         | 0.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 0.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 0.87%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 0.87%   |
| Intel HD Graphics 5500                                                        | 3         | 0.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 130       | 44.83%  |
| 1 x Nvidia      | 57        | 19.66%  |
| 1 x AMD         | 42        | 14.48%  |
| Intel + Nvidia  | 33        | 11.38%  |
| AMD + Nvidia    | 10        | 3.45%   |
| Other           | 8         | 2.76%   |
| Intel + AMD     | 5         | 1.72%   |
| 1 x Neomagic    | 2         | 0.69%   |
| 1 x S3 Graphics | 1         | 0.34%   |
| Nvidia + Matrox | 1         | 0.34%   |
| 1 x ASPEED      | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 216       | 74.23%  |
| Proprietary | 55        | 18.9%   |
| Unknown     | 20        | 6.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 171       | 58.16%  |
| 1.01-2.0   | 29        | 9.86%   |
| 0.01-0.5   | 23        | 7.82%   |
| 0.51-1.0   | 22        | 7.48%   |
| 3.01-4.0   | 18        | 6.12%   |
| 7.01-8.0   | 17        | 5.78%   |
| 5.01-6.0   | 9         | 3.06%   |
| 2.01-3.0   | 2         | 0.68%   |
| 8.01-16.0  | 2         | 0.68%   |
| 16.01-24.0 | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 32        | 10.67%  |
| AU Optronics            | 27        | 9%      |
| Samsung Electronics     | 25        | 8.33%   |
| LG Display              | 21        | 7%      |
| Dell                    | 20        | 6.67%   |
| Chimei Innolux          | 20        | 6.67%   |
| Goldstar                | 18        | 6%      |
| AOC                     | 16        | 5.33%   |
| Philips                 | 13        | 4.33%   |
| Sharp                   | 8         | 2.67%   |
| Unknown                 | 7         | 2.33%   |
| Ancor Communications    | 7         | 2.33%   |
| Lenovo                  | 6         | 2%      |
| AMO                     | 6         | 2%      |
| Acer                    | 6         | 2%      |
| Hewlett-Packard         | 4         | 1.33%   |
| BenQ                    | 4         | 1.33%   |
| Apple                   | 4         | 1.33%   |
| ViewSonic               | 3         | 1%      |
| RTK                     | 2         | 0.67%   |
| Mi                      | 2         | 0.67%   |
| LG Philips              | 2         | 0.67%   |
| IPS                     | 2         | 0.67%   |
| InfoVision              | 2         | 0.67%   |
| CSO                     | 2         | 0.67%   |
| CPT                     | 2         | 0.67%   |
| Chi Mei Optoelectronics | 2         | 0.67%   |
| AUS                     | 2         | 0.67%   |
| ASUSTek Computer        | 2         | 0.67%   |
| Xiaomi                  | 1         | 0.33%   |
| Xiangye                 | 1         | 0.33%   |
| Unknown (DAE)           | 1         | 0.33%   |
| Unknown (AAA)           | 1         | 0.33%   |
| Toshiba                 | 1         | 0.33%   |
| TMX                     | 1         | 0.33%   |
| TCT                     | 1         | 0.33%   |
| Sony                    | 1         | 0.33%   |
| SKY                     | 1         | 0.33%   |
| SGT                     | 1         | 0.33%   |
| SAC                     | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AMO HS241P AMO2800 2560x1440 620x349mm 28.0-inch                      | 4         | 1.31%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 3         | 0.98%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 3         | 0.98%   |
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.98%   |
| AOC G2790G4 AOC2790 1920x1080 598x336mm 27.0-inch                     | 3         | 0.98%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 0.65%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 2         | 0.65%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 0.65%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 2         | 0.65%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 2         | 0.65%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.65%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.65%   |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                   | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 2         | 0.65%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 0.65%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                 | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO233D 1920x1080 309x174mm 14.0-inch        | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 2         | 0.65%   |
| AOC G2490W1G4 AOC2490 1920x1080 527x296mm 23.8-inch                   | 2         | 0.65%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 2         | 0.65%   |
| Xiaomi Mi TV XMD004A 3840x2160 1110x620mm 50.1-inch                   | 1         | 0.33%   |
| Xiangye XE2400 XYE2380 3840x2160 520x310mm 23.8-inch                  | 1         | 0.33%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch              | 1         | 0.33%   |
| ViewSonic VX2239 SERIES VSC5225 1920x1080 480x270mm 21.7-inch         | 1         | 0.33%   |
| ViewSonic VA1616wSERIES VSC0021 1366x768 348x197mm 15.7-inch          | 1         | 0.33%   |
| Unknown LCD Monitor ROW AAA                                           | 1         | 0.33%   |
| Unknown LCD Monitor hp f1523 1024x768                                 | 1         | 0.33%   |
| Unknown LCD Monitor GBT G32QC A 2560x1440                             | 1         | 0.33%   |
| Unknown LCD Monitor FST V22T-1R LED 1920x1080                         | 1         | 0.33%   |
| Unknown (DAE) L32S6550BN DAE0010 1366x768 698x392mm 31.5-inch         | 1         | 0.33%   |
| Unknown (AAA) U270 AAA2700 3840x2160 596x335mm 26.9-inch              | 1         | 0.33%   |
| Toshiba TV TSB2634 1920x1080 697x392mm 31.5-inch                      | 1         | 0.33%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.33%   |
| TCT DP1080P60 TCT0270 2560x1600 520x290mm 23.4-inch                   | 1         | 0.33%   |
| Sony BW8 MS_9001 2560x1600                                            | 1         | 0.33%   |
| SKY M16U1 SKY0156 3840x2160 345x194mm 15.6-inch                       | 1         | 0.33%   |
| Sharp LQ133M1JW48 SHP14F5 1920x1080 294x165mm 13.3-inch               | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 132       | 46.48%  |
| 3840x2160 (4K)     | 29        | 10.21%  |
| 1366x768 (WXGA)    | 26        | 9.15%   |
| 2560x1440 (QHD)    | 21        | 7.39%   |
| 1440x900 (WXGA+)   | 9         | 3.17%   |
| 1600x900 (HD+)     | 7         | 2.46%   |
| Unknown            | 7         | 2.46%   |
| 1280x800 (WXGA)    | 5         | 1.76%   |
| 3440x1440          | 4         | 1.41%   |
| 2560x1600          | 4         | 1.41%   |
| 1680x1050 (WSXGA+) | 4         | 1.41%   |
| 3840x1080          | 3         | 1.06%   |
| 2880x1800          | 3         | 1.06%   |
| 1360x768           | 3         | 1.06%   |
| 3840x2400          | 2         | 0.7%    |
| 2560x1080          | 2         | 0.7%    |
| 1920x1200 (WUXGA)  | 2         | 0.7%    |
| 1280x1024 (SXGA)   | 2         | 0.7%    |
| 1024x768 (XGA)     | 2         | 0.7%    |
| 5120x1440          | 1         | 0.35%   |
| 4480x1440          | 1         | 0.35%   |
| 3840x1600          | 1         | 0.35%   |
| 3520x1080          | 1         | 0.35%   |
| 3456x2160          | 1         | 0.35%   |
| 3200x2000          | 1         | 0.35%   |
| 3200x1800 (QHD+)   | 1         | 0.35%   |
| 3200x1080          | 1         | 0.35%   |
| 2880x1920          | 1         | 0.35%   |
| 2400x1600          | 1         | 0.35%   |
| 2304x1440          | 1         | 0.35%   |
| 2256x1504          | 1         | 0.35%   |
| 2240x1400          | 1         | 0.35%   |
| 2160x1440          | 1         | 0.35%   |
| 2160x1350          | 1         | 0.35%   |
| 1024x600           | 1         | 0.35%   |
| 1024x576           | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 55        | 18.64%  |
| 13      | 35        | 11.86%  |
| 14      | 26        | 8.81%   |
| 21      | 25        | 8.47%   |
| 23      | 23        | 7.8%    |
| Unknown | 22        | 7.46%   |
| 27      | 19        | 6.44%   |
| 24      | 17        | 5.76%   |
| 31      | 11        | 3.73%   |
| 12      | 10        | 3.39%   |
| 18      | 8         | 2.71%   |
| 28      | 6         | 2.03%   |
| 17      | 6         | 2.03%   |
| 34      | 5         | 1.69%   |
| 19      | 5         | 1.69%   |
| 22      | 3         | 1.02%   |
| 10      | 3         | 1.02%   |
| 25      | 2         | 0.68%   |
| 16      | 2         | 0.68%   |
| 84      | 1         | 0.34%   |
| 72      | 1         | 0.34%   |
| 65      | 1         | 0.34%   |
| 52      | 1         | 0.34%   |
| 48      | 1         | 0.34%   |
| 46      | 1         | 0.34%   |
| 40      | 1         | 0.34%   |
| 37      | 1         | 0.34%   |
| 26      | 1         | 0.34%   |
| 20      | 1         | 0.34%   |
| 11      | 1         | 0.34%   |
| 8       | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 98        | 33.68%  |
| 501-600     | 60        | 20.62%  |
| 401-500     | 40        | 13.75%  |
| 201-300     | 34        | 11.68%  |
| Unknown     | 22        | 7.56%   |
| 601-700     | 17        | 5.84%   |
| 351-400     | 6         | 2.06%   |
| 701-800     | 5         | 1.72%   |
| 1001-1500   | 4         | 1.37%   |
| 801-900     | 2         | 0.69%   |
| 1501-2000   | 2         | 0.69%   |
| 101-200     | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 202       | 74.54%  |
| 16/10   | 36        | 13.28%  |
| Unknown | 18        | 6.64%   |
| 21/9    | 6         | 2.21%   |
| 3/2     | 4         | 1.48%   |
| 6/5     | 2         | 0.74%   |
| 4/3     | 1         | 0.37%   |
| 32/9    | 1         | 0.37%   |
| 0.62    | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 57        | 19.45%  |
| 101-110        | 55        | 18.77%  |
| 81-90          | 45        | 15.36%  |
| 301-350        | 25        | 8.53%   |
| Unknown        | 22        | 7.51%   |
| 351-500        | 18        | 6.14%   |
| 71-80          | 17        | 5.8%    |
| 151-200        | 15        | 5.12%   |
| 61-70          | 9         | 3.07%   |
| 251-300        | 5         | 1.71%   |
| 141-150        | 5         | 1.71%   |
| 121-130        | 5         | 1.71%   |
| More than 1000 | 4         | 1.37%   |
| 41-50          | 3         | 1.02%   |
| 501-1000       | 3         | 1.02%   |
| 51-60          | 1         | 0.34%   |
| 1-40           | 1         | 0.34%   |
| 131-140        | 1         | 0.34%   |
| 111-120        | 1         | 0.34%   |
| 91-100         | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 78        | 27.18%  |
| 121-160       | 77        | 26.83%  |
| 101-120       | 57        | 19.86%  |
| 161-240       | 30        | 10.45%  |
| Unknown       | 22        | 7.67%   |
| More than 240 | 17        | 5.92%   |
| 1-50          | 6         | 2.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 233       | 80.34%  |
| 2     | 41        | 14.14%  |
| 0     | 15        | 5.17%   |
| 3     | 1         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 168       | 40.98%  |
| Realtek Semiconductor    | 137       | 33.41%  |
| Qualcomm Atheros         | 30        | 7.32%   |
| Broadcom                 | 19        | 4.63%   |
| MediaTek                 | 9         | 2.2%    |
| Ralink Technology        | 8         | 1.95%   |
| TP-Link                  | 7         | 1.71%   |
| Marvell Technology Group | 3         | 0.73%   |
| Broadcom Limited         | 3         | 0.73%   |
| ASIX Electronics         | 3         | 0.73%   |
| Xiaomi                   | 2         | 0.49%   |
| SEGGER                   | 2         | 0.49%   |
| Qualcomm                 | 2         | 0.49%   |
| Microsoft                | 2         | 0.49%   |
| Huawei Technologies      | 2         | 0.49%   |
| Texas Instruments        | 1         | 0.24%   |
| Ralink                   | 1         | 0.24%   |
| PEAK-System Technik      | 1         | 0.24%   |
| OPPO Electronics         | 1         | 0.24%   |
| Nvidia                   | 1         | 0.24%   |
| National Semiconductor   | 1         | 0.24%   |
| Lenovo                   | 1         | 0.24%   |
| ICS Advent               | 1         | 0.24%   |
| Fitbit                   | 1         | 0.24%   |
| DisplayLink              | 1         | 0.24%   |
| D-Link                   | 1         | 0.24%   |
| Belkin Components        | 1         | 0.24%   |
| Apple                    | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 92        | 18.4%   |
| Intel Wi-Fi 6 AX200                                                     | 27        | 5.4%    |
| Intel Wireless 8265 / 8275                                              | 13        | 2.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 2.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 2.2%    |
| Intel I211 Gigabit Network Connection                                   | 11        | 2.2%    |
| Intel Wi-Fi 6 AX201                                                     | 8         | 1.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 1.6%    |
| Realtek RTL8125 2.5GbE Controller                                       | 7         | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.4%    |
| Intel Wireless 7265                                                     | 7         | 1.4%    |
| Intel Wireless 7260                                                     | 7         | 1.4%    |
| Intel Ethernet Connection (2) I219-V                                    | 7         | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.4%    |
| Intel Ethernet Connection (4) I219-V                                    | 6         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.2%    |
| Intel 82579V Gigabit Network Connection                                 | 6         | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1%      |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 1%      |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1%      |
| Intel Wireless 8260                                                     | 5         | 1%      |
| Intel Ethernet Connection I217-LM                                       | 5         | 1%      |
| Intel Ethernet Controller I225-V                                        | 4         | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.6%    |
| Realtek 802.11ac NIC                                                    | 3         | 0.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.6%    |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.6%    |
| Intel Ethernet Connection (11) I219-V                                   | 3         | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.6%    |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.6%    |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 3         | 0.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 0.6%    |
| Intel 82577LM Gigabit Network Connection                                | 3         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 135       | 57.45%  |
| Realtek Semiconductor | 29        | 12.34%  |
| Qualcomm Atheros      | 24        | 10.21%  |
| Broadcom              | 15        | 6.38%   |
| MediaTek              | 9         | 3.83%   |
| Ralink Technology     | 8         | 3.4%    |
| TP-Link               | 7         | 2.98%   |
| Qualcomm              | 2         | 0.85%   |
| Microsoft             | 2         | 0.85%   |
| Texas Instruments     | 1         | 0.43%   |
| Ralink                | 1         | 0.43%   |
| Broadcom Limited      | 1         | 0.43%   |
| Belkin Components     | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 27        | 11.44%  |
| Intel Wireless 8265 / 8275                                              | 13        | 5.51%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 3.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 3.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.97%   |
| Intel Wireless 7265                                                     | 7         | 2.97%   |
| Intel Wireless 7260                                                     | 7         | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 2.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 2.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 2.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.12%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 2.12%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 2.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.12%   |
| Intel Wireless 8260                                                     | 5         | 2.12%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.27%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.27%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.27%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 3         | 1.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.27%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.85%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 2         | 0.85%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)               | 2         | 0.85%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.85%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.85%   |
| Microsoft XBOX ACC                                                      | 2         | 0.85%   |
| MediaTek 802.11 n WLAN                                                  | 2         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 126       | 50.4%   |
| Intel                    | 89        | 35.6%   |
| Qualcomm Atheros         | 9         | 3.6%    |
| Broadcom                 | 6         | 2.4%    |
| Marvell Technology Group | 3         | 1.2%    |
| ASIX Electronics         | 3         | 1.2%    |
| Xiaomi                   | 2         | 0.8%    |
| Huawei Technologies      | 2         | 0.8%    |
| Broadcom Limited         | 2         | 0.8%    |
| OPPO Electronics         | 1         | 0.4%    |
| Nvidia                   | 1         | 0.4%    |
| National Semiconductor   | 1         | 0.4%    |
| Lenovo                   | 1         | 0.4%    |
| ICS Advent               | 1         | 0.4%    |
| DisplayLink              | 1         | 0.4%    |
| D-Link                   | 1         | 0.4%    |
| Apple                    | 1         | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 92        | 35.66%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 4.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 4.26%   |
| Intel I211 Gigabit Network Connection                             | 11        | 4.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 2.71%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 2.71%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 2.33%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.94%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.55%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.16%   |
| Intel Ethernet Connection (11) I219-V                             | 3         | 1.16%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.16%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.78%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2         | 0.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.78%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.78%   |
| Realtek USB 10/100 LAN                                            | 1         | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.39%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.39%   |
| OPPO RMX2117                                                      | 1         | 0.39%   |
| Nvidia MCP65 Ethernet                                             | 1         | 0.39%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1         | 0.39%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.39%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 233       | 50.43%  |
| WiFi     | 223       | 48.27%  |
| Modem    | 3         | 0.65%   |
| Unknown  | 3         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 171       | 55.52%  |
| Ethernet | 137       | 44.48%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 148       | 50.68%  |
| 1     | 122       | 41.78%  |
| 0     | 14        | 4.79%   |
| 3     | 4         | 1.37%   |
| 4     | 2         | 0.68%   |
| 8     | 1         | 0.34%   |
| 7     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 286       | 98.28%  |
| Yes  | 5         | 1.72%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 60.75%  |
| Cambridge Silicon Radio         | 15        | 8.06%   |
| Broadcom                        | 8         | 4.3%    |
| Realtek Semiconductor           | 7         | 3.76%   |
| Foxconn / Hon Hai               | 7         | 3.76%   |
| Qualcomm Atheros Communications | 6         | 3.23%   |
| Lite-On Technology              | 5         | 2.69%   |
| IMC Networks                    | 4         | 2.15%   |
| Apple                           | 4         | 2.15%   |
| Realtek                         | 3         | 1.61%   |
| Hewlett-Packard                 | 3         | 1.61%   |
| Foxconn International           | 2         | 1.08%   |
| Dell                            | 2         | 1.08%   |
| ASUSTek Computer                | 2         | 1.08%   |
| Taiyo Yuden                     | 1         | 0.54%   |
| SINO WEALTH                     | 1         | 0.54%   |
| Micro Star International        | 1         | 0.54%   |
| Fujitsu                         | 1         | 0.54%   |
| Askey Computer                  | 1         | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 32        | 17.2%   |
| Intel AX200 Bluetooth                               | 27        | 14.52%  |
| Intel AX201 Bluetooth                               | 23        | 12.37%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 8.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 6.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 4.3%    |
| Realtek Bluetooth Radio                             | 7         | 3.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.15%   |
| Intel Bluetooth Device                              | 4         | 2.15%   |
| Realtek Bluetooth Radio                             | 3         | 1.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.61%   |
| IMC Networks Wireless_Device                        | 3         | 1.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.08%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.08%   |
| Intel AX210 Bluetooth                               | 2         | 1.08%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.08%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 1.08%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.08%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.08%   |
| ASUS Bluetooth Radio                                | 2         | 1.08%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.08%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.54%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1         | 0.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.54%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.54%   |
| Micro Star International Bluetooth Dongle           | 1         | 0.54%   |
| Lite-On Bluetooth Radio                             | 1         | 0.54%   |
| Lite-On Bluetooth Device                            | 1         | 0.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.54%   |
| IMC Networks Bluetooth Device                       | 1         | 0.54%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.54%   |
| Fujitsu Bluetooth Device                            | 1         | 0.54%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.54%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.54%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.54%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.54%   |
| Broadcom Bluetooth Controller                       | 1         | 0.54%   |
| Broadcom BCM2045A0                                  | 1         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 219       | 56.01%  |
| Nvidia                               | 77        | 19.69%  |
| AMD                                  | 62        | 15.86%  |
| C-Media Electronics                  | 9         | 2.3%    |
| Logitech                             | 3         | 0.77%   |
| Generalplus Technology               | 2         | 0.51%   |
| Focusrite-Novation                   | 2         | 0.51%   |
| FiiO Electronics Technology          | 2         | 0.51%   |
| ESS Technology                       | 2         | 0.51%   |
| Creative Labs                        | 2         | 0.51%   |
| XMOS                                 | 1         | 0.26%   |
| VIA Technologies                     | 1         | 0.26%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.26%   |
| Sony                                 | 1         | 0.26%   |
| Realtek Semiconductor                | 1         | 0.26%   |
| Lynx                                 | 1         | 0.26%   |
| iCreate Technologies                 | 1         | 0.26%   |
| HiFimeDIY Audio                      | 1         | 0.26%   |
| BY EDIFIER                           | 1         | 0.26%   |
| AudioQuest                           | 1         | 0.26%   |
| Apple                                | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 27        | 5.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 26        | 5.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18        | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 18        | 3.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 16        | 3.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15        | 3.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 3.3%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 2.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 2.64%   |
| AMD Starship/Matisse HD Audio Controller                                   | 12        | 2.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.76%   |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.54%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.54%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.54%   |
| Nvidia GM206 High Definition Audio Controller                              | 6         | 1.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.32%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 1.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 6         | 1.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.1%    |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 1.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.1%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.1%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5         | 1.1%    |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.88%   |
| Intel Comet Lake PCH-V cAVS                                                | 4         | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.88%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4         | 0.88%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 0.88%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 0.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 40        | 20.83%  |
| Samsung Electronics | 37        | 19.27%  |
| Kingston            | 29        | 15.1%   |
| Micron Technology   | 18        | 9.38%   |
| Unknown             | 16        | 8.33%   |
| Corsair             | 10        | 5.21%   |
| A-DATA Technology   | 8         | 4.17%   |
| Crucial             | 7         | 3.65%   |
| Unknown             | 7         | 3.65%   |
| Team                | 3         | 1.56%   |
| Unknown (ABCD)      | 2         | 1.04%   |
| Ramaxel Technology  | 2         | 1.04%   |
| Kingmax             | 2         | 1.04%   |
| Elpida              | 2         | 1.04%   |
| Transcend           | 1         | 0.52%   |
| tigo                | 1         | 0.52%   |
| Nanya Technology    | 1         | 0.52%   |
| Lenovo              | 1         | 0.52%   |
| Juhor               | 1         | 0.52%   |
| GLOWAY              | 1         | 0.52%   |
| G.Skill             | 1         | 0.52%   |
| Essencore Limited   | 1         | 0.52%   |
| Apacer              | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown                                                         | 7         | 3.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s          | 4         | 1.98%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s       | 4         | 1.98%   |
| Unknown RAM Module 2GB DIMM SDRAM                               | 2         | 0.99%   |
| Unknown RAM Module 256MB SODIMM DRAM                            | 2         | 0.99%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s | 2         | 0.99%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                    | 2         | 0.99%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s    | 2         | 0.99%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s           | 2         | 0.99%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 2         | 0.99%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s          | 2         | 0.99%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 2         | 0.99%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.99%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.99%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                  | 2         | 0.99%   |
| Kingston RAM KHX2666C16/16G 16384MB DIMM DDR4 3200MT/s          | 2         | 0.99%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s         | 2         | 0.99%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s           | 2         | 0.99%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                    | 1         | 0.5%    |
| Unknown RAM Module 512MB SODIMM DRAM                            | 1         | 0.5%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s             | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s                     | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 333MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR                               | 1         | 0.5%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s             | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                   | 1         | 0.5%    |
| Unknown RAM Module 1024MB DIMM 800MT/s                          | 1         | 0.5%    |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s               | 1         | 0.5%    |
| tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                      | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s              | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s              | 1         | 0.5%    |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s            | 1         | 0.5%    |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s            | 1         | 0.5%    |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 0.5%    |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                      | 1         | 0.5%    |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 86        | 51.81%  |
| DDR3    | 37        | 22.29%  |
| LPDDR3  | 11        | 6.63%   |
| DDR2    | 9         | 5.42%   |
| LPDDR4  | 8         | 4.82%   |
| SDRAM   | 5         | 3.01%   |
| DRAM    | 3         | 1.81%   |
| Unknown | 3         | 1.81%   |
| DDR5    | 2         | 1.2%    |
| LPDDR5  | 1         | 0.6%    |
| DDR     | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 46.06%  |
| DIMM         | 66        | 40%     |
| Row Of Chips | 22        | 13.33%  |
| Unknown      | 1         | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 65        | 36.11%  |
| 4096  | 40        | 22.22%  |
| 16384 | 30        | 16.67%  |
| 2048  | 19        | 10.56%  |
| 32768 | 14        | 7.78%   |
| 1024  | 6         | 3.33%   |
| 256   | 2         | 1.11%   |
| 64    | 2         | 1.11%   |
| 512   | 1         | 0.56%   |
| 232   | 1         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 32        | 18.29%  |
| 2667    | 29        | 16.57%  |
| 1600    | 29        | 16.57%  |
| 2400    | 13        | 7.43%   |
| 2133    | 12        | 6.86%   |
| 1333    | 8         | 4.57%   |
| Unknown | 6         | 3.43%   |
| 1867    | 5         | 2.86%   |
| 4267    | 4         | 2.29%   |
| 2666    | 4         | 2.29%   |
| 667     | 4         | 2.29%   |
| 3600    | 3         | 1.71%   |
| 3466    | 3         | 1.71%   |
| 4800    | 2         | 1.14%   |
| 3000    | 2         | 1.14%   |
| 800     | 2         | 1.14%   |
| 533     | 2         | 1.14%   |
| 6400    | 1         | 0.57%   |
| 4266    | 1         | 0.57%   |
| 4199    | 1         | 0.57%   |
| 3800    | 1         | 0.57%   |
| 3733    | 1         | 0.57%   |
| 3400    | 1         | 0.57%   |
| 3266    | 1         | 0.57%   |
| 3007    | 1         | 0.57%   |
| 2933    | 1         | 0.57%   |
| 1866    | 1         | 0.57%   |
| 1800    | 1         | 0.57%   |
| 1334    | 1         | 0.57%   |
| 975     | 1         | 0.57%   |
| 333     | 1         | 0.57%   |
| 200     | 1         | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


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

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 29        | 20%     |
| IMC Networks                           | 14        | 9.66%   |
| Acer                                   | 13        | 8.97%   |
| Microdia                               | 11        | 7.59%   |
| Logitech                               | 9         | 6.21%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 5.52%   |
| Realtek Semiconductor                  | 6         | 4.14%   |
| Luxvisions Innotech Limited            | 6         | 4.14%   |
| Apple                                  | 6         | 4.14%   |
| Syntek                                 | 5         | 3.45%   |
| Sunplus Innovation Technology          | 5         | 3.45%   |
| Silicon Motion                         | 3         | 2.07%   |
| Quanta                                 | 3         | 2.07%   |
| Alcor Micro                            | 3         | 2.07%   |
| Suyin                                  | 2         | 1.38%   |
| Lite-On Technology                     | 2         | 1.38%   |
| Importek                               | 2         | 1.38%   |
| eMPIA Technology                       | 2         | 1.38%   |
| Cubeternet                             | 2         | 1.38%   |
| WaveRider Communications               | 1         | 0.69%   |
| Sonix Technology                       | 1         | 0.69%   |
| SN0002                                 | 1         | 0.69%   |
| Ricoh                                  | 1         | 0.69%   |
| Primax Electronics                     | 1         | 0.69%   |
| Nokia Mobile Phones                    | 1         | 0.69%   |
| Nebraska Furniture Mart                | 1         | 0.69%   |
| Microsoft                              | 1         | 0.69%   |
| lihappe8                               | 1         | 0.69%   |
| icSpring                               | 1         | 0.69%   |
| Google                                 | 1         | 0.69%   |
| Genesys Logic                          | 1         | 0.69%   |
| Essential Products                     | 1         | 0.69%   |
| ARC International                      | 1         | 0.69%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 9         | 6.08%   |
| Microdia Integrated_Webcam_HD                                   | 7         | 4.73%   |
| IMC Networks Integrated Camera                                  | 6         | 4.05%   |
| Syntek Integrated Camera                                        | 5         | 3.38%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 3.38%   |
| Chicony FJ Camera                                               | 5         | 3.38%   |
| Acer Integrated Camera                                          | 5         | 3.38%   |
| Chicony HD Webcam                                               | 4         | 2.7%    |
| Logitech Webcam C270                                            | 3         | 2.03%   |
| Apple FaceTime HD Camera (Built-in)                             | 3         | 2.03%   |
| Alcor Micro SHUNCCM2MP                                          | 3         | 2.03%   |
| Realtek Integrated_Webcam_HD                                    | 2         | 1.35%   |
| Luxvisions Innotech Limited Integrated Camera                   | 2         | 1.35%   |
| Luxvisions Innotech Limited HP HD Camera                        | 2         | 1.35%   |
| Logitech B525 HD Webcam                                         | 2         | 1.35%   |
| Lite-On Integrated Camera                                       | 2         | 1.35%   |
| Importek FJ Camera                                              | 2         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.35%   |
| Apple iPhone5/5C/5S/6                                           | 2         | 1.35%   |
| Acer SunplusIT Integrated Camera                                | 2         | 1.35%   |
| Acer Lenovo EasyCamera                                          | 2         | 1.35%   |
| WaveRider USB 2.0 Camera                                        | 1         | 0.68%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 1         | 0.68%   |
| Suyin HP Truevision HD                                          | 1         | 0.68%   |
| Sunplus SPCA2085 PC Camera                                      | 1         | 0.68%   |
| Sunplus MTD Camera                                              | 1         | 0.68%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 0.68%   |
| Sunplus HP Universal Camera                                     | 1         | 0.68%   |
| Sunplus HD WebCam                                               | 1         | 0.68%   |
| Sonix USB2.0 HD UVC WebCam                                      | 1         | 0.68%   |
| SN0002 2K USB Camera                                            | 1         | 0.68%   |
| Silicon Motion Lenovo EasyCamera                                | 1         | 0.68%   |
| Silicon Motion 720p HD Camera                                   | 1         | 0.68%   |
| Silicon Motion 300k Pixel Camera                                | 1         | 0.68%   |
| Ricoh USB2.0 Camera                                             | 1         | 0.68%   |
| Realtek WebCamera                                               | 1         | 0.68%   |
| Realtek USB2.0 HD UVC WebCam                                    | 1         | 0.68%   |
| Realtek Integrated Webcam_HD                                    | 1         | 0.68%   |
| Realtek EasyCamera                                              | 1         | 0.68%   |
| Quanta USB Webcam                                               | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 16        | 44.44%  |
| Validity Sensors           | 7         | 19.44%  |
| Shenzhen Goodix Technology | 6         | 16.67%  |
| AuthenTec                  | 3         | 8.33%   |
| Upek                       | 2         | 5.56%   |
| Samsung Electronics        | 1         | 2.78%   |
| LighTuning Technology      | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader       | 6         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 13.89%  |
| Unknown                                                | 3         | 8.33%   |
| Validity Sensors Synaptics WBDI                        | 2         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 5.56%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 5.56%   |
| Shenzhen Goodix FingerPrint                            | 2         | 5.56%   |
| AuthenTec Fingerprint Sensor                           | 2         | 5.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.78%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 2.78%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 2.78%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 2.78%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.78%   |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1         | 2.78%   |
| Synaptics  WBDI                                        | 1         | 2.78%   |
| Samsung Fingerprint Device                             | 1         | 2.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.78%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 2.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 28.57%  |
| Upek                  | 2         | 14.29%  |
| Lenovo                | 2         | 14.29%  |
| Alcor Micro           | 2         | 14.29%  |
| Advanced Card Systems | 2         | 14.29%  |
| Yubico.com            | 1         | 7.14%   |
| O2 Micro              | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 14.29%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 14.29%  |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 2         | 14.29%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 7.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 7.14%   |
| Broadcom 5880                                                                | 1         | 7.14%   |
| Broadcom 58200                                                               | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 196       | 65.99%  |
| 1     | 79        | 26.6%   |
| 2     | 15        | 5.05%   |
| 4     | 4         | 1.35%   |
| 3     | 2         | 0.67%   |
| 5     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 34        | 25.56%  |
| Graphics card            | 30        | 22.56%  |
| Net/wireless             | 18        | 13.53%  |
| Chipcard                 | 13        | 9.77%   |
| Communication controller | 10        | 7.52%   |
| Multimedia controller    | 9         | 6.77%   |
| Bluetooth                | 4         | 3.01%   |
| Sound                    | 3         | 2.26%   |
| Unassigned class         | 2         | 1.5%    |
| Storage                  | 2         | 1.5%    |
| Net/ethernet             | 2         | 1.5%    |
| Camera                   | 2         | 1.5%    |
| Storage/raid             | 1         | 0.75%   |
| Storage/ata              | 1         | 0.75%   |
| Network                  | 1         | 0.75%   |
| Card reader              | 1         | 0.75%   |

