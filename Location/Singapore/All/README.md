Linux in Singapore - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Singapore.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Singapore/Desktop/README.md) and [notebooks](/Location/Singapore/Notebook/README.md).

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

Total: 488

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-F42386C8 PVT            | All in one  | [c172555349](https://linux-hardware.org/?probe=c172555349) | Jan 25, 2023 |
| Lenovo        | NOK                         | Desktop     | [507b602676](https://linux-hardware.org/?probe=507b602676) | Jan 25, 2023 |
| Acer          | Aspire V5-132               | Notebook    | [7f74397112](https://linux-hardware.org/?probe=7f74397112) | Jan 24, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [7fef453cdb](https://linux-hardware.org/?probe=7fef453cdb) | Jan 23, 2023 |
| Acer          | Aspire ES1-432              | Notebook    | [4a81caf8b2](https://linux-hardware.org/?probe=4a81caf8b2) | Jan 18, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [d696233b84](https://linux-hardware.org/?probe=d696233b84) | Jan 18, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a73de9a5b9](https://linux-hardware.org/?probe=a73de9a5b9) | Jan 14, 2023 |
| Dell          | Latitude 7390               | Notebook    | [cc5d8632f5](https://linux-hardware.org/?probe=cc5d8632f5) | Jan 13, 2023 |
| Dell          | Latitude 7390               | Notebook    | [a8ee39edc5](https://linux-hardware.org/?probe=a8ee39edc5) | Jan 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [ae506ac561](https://linux-hardware.org/?probe=ae506ac561) | Jan 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [3e870855db](https://linux-hardware.org/?probe=3e870855db) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [14273d90fd](https://linux-hardware.org/?probe=14273d90fd) | Jan 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2e6f75ca07](https://linux-hardware.org/?probe=2e6f75ca07) | Jan 06, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [3af1bc02b8](https://linux-hardware.org/?probe=3af1bc02b8) | Jan 05, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [0a1360a7dc](https://linux-hardware.org/?probe=0a1360a7dc) | Jan 05, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c96c7d74fe](https://linux-hardware.org/?probe=c96c7d74fe) | Jan 02, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| Dell          | Inspiron 1420               | Notebook    | [fe6a8714da](https://linux-hardware.org/?probe=fe6a8714da) | Dec 31, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [c6325d4647](https://linux-hardware.org/?probe=c6325d4647) | Dec 29, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [6dac0c0943](https://linux-hardware.org/?probe=6dac0c0943) | Dec 29, 2022 |
| Gigabyte      | B365M D2V                   | Desktop     | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [8633f00865](https://linux-hardware.org/?probe=8633f00865) | Dec 26, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [802e7982de](https://linux-hardware.org/?probe=802e7982de) | Dec 26, 2022 |
| HP            | 8061                        | Desktop     | [4427032526](https://linux-hardware.org/?probe=4427032526) | Dec 24, 2022 |
| ASRock        | B75 Pro3-M                  | Desktop     | [e24692f75f](https://linux-hardware.org/?probe=e24692f75f) | Dec 24, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [61f064d35f](https://linux-hardware.org/?probe=61f064d35f) | Dec 22, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [d387b553bd](https://linux-hardware.org/?probe=d387b553bd) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [ee344993aa](https://linux-hardware.org/?probe=ee344993aa) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [cc9fb3fd05](https://linux-hardware.org/?probe=cc9fb3fd05) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [51f520d152](https://linux-hardware.org/?probe=51f520d152) | Dec 21, 2022 |
| Foxconn       | 17A0                        | Desktop     | [58a3486afd](https://linux-hardware.org/?probe=58a3486afd) | Dec 20, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [d5171f9491](https://linux-hardware.org/?probe=d5171f9491) | Dec 19, 2022 |
| Foxconn       | 17A0                        | Desktop     | [be57227f43](https://linux-hardware.org/?probe=be57227f43) | Dec 17, 2022 |
| Foxconn       | 17A0                        | Desktop     | [b2185eeab5](https://linux-hardware.org/?probe=b2185eeab5) | Dec 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [615d3e1599](https://linux-hardware.org/?probe=615d3e1599) | Dec 14, 2022 |
| Foxconn       | 17A0                        | Desktop     | [4518247b07](https://linux-hardware.org/?probe=4518247b07) | Dec 14, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [52546b1dd0](https://linux-hardware.org/?probe=52546b1dd0) | Dec 10, 2022 |
| Foxconn       | 17A0                        | Desktop     | [2f3b2f9fbb](https://linux-hardware.org/?probe=2f3b2f9fbb) | Dec 07, 2022 |
| HP            | 8061                        | Desktop     | [6e4cb7cde8](https://linux-hardware.org/?probe=6e4cb7cde8) | Dec 07, 2022 |
| HP            | 8061                        | Desktop     | [9d30b0126f](https://linux-hardware.org/?probe=9d30b0126f) | Dec 05, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [5b17c3205f](https://linux-hardware.org/?probe=5b17c3205f) | Dec 03, 2022 |
| HP            | ZBook 15                    | Notebook    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | Notebook    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | Notebook    | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [61f6e057e6](https://linux-hardware.org/?probe=61f6e057e6) | Nov 17, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| Dell          | Precision 3571              | Notebook    | [039ece6391](https://linux-hardware.org/?probe=039ece6391) | Nov 10, 2022 |
| Google        | Atlas                       | Notebook    | [77922a522d](https://linux-hardware.org/?probe=77922a522d) | Nov 09, 2022 |
| Google        | Atlas                       | Notebook    | [829fcb8f6a](https://linux-hardware.org/?probe=829fcb8f6a) | Nov 09, 2022 |
| Dell          | Precision 3571              | Notebook    | [d305848533](https://linux-hardware.org/?probe=d305848533) | Nov 08, 2022 |
| Dell          | Precision 3571              | Notebook    | [681a655e1c](https://linux-hardware.org/?probe=681a655e1c) | Nov 08, 2022 |
| Dell          | Precision 3571              | Notebook    | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| Dell          | Precision 3571              | Notebook    | [9da55445b0](https://linux-hardware.org/?probe=9da55445b0) | Nov 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [14e8385f99](https://linux-hardware.org/?probe=14e8385f99) | Oct 31, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [0a0922ed82](https://linux-hardware.org/?probe=0a0922ed82) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [52701ec9f4](https://linux-hardware.org/?probe=52701ec9f4) | Oct 24, 2022 |
| Acer          | RS880M05                    | Desktop     | [7adee2fd97](https://linux-hardware.org/?probe=7adee2fd97) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1dc7719a4d](https://linux-hardware.org/?probe=1dc7719a4d) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [18893915f3](https://linux-hardware.org/?probe=18893915f3) | Oct 17, 2022 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [d84677af13](https://linux-hardware.org/?probe=d84677af13) | Oct 17, 2022 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [9ec02e49a3](https://linux-hardware.org/?probe=9ec02e49a3) | Oct 13, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d67006c592](https://linux-hardware.org/?probe=d67006c592) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [5ace2d0c1f](https://linux-hardware.org/?probe=5ace2d0c1f) | Oct 06, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [3338607f1a](https://linux-hardware.org/?probe=3338607f1a) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | Notebook    | [855ad327a4](https://linux-hardware.org/?probe=855ad327a4) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | Notebook    | [829ec8aac1](https://linux-hardware.org/?probe=829ec8aac1) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [93680a7429](https://linux-hardware.org/?probe=93680a7429) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [ae5fd894b6](https://linux-hardware.org/?probe=ae5fd894b6) | Sep 25, 2022 |
| Dell          | Latitude 7275               | Tablet      | [49ee35636b](https://linux-hardware.org/?probe=49ee35636b) | Sep 24, 2022 |
| Lenovo        | Legion R9000K2021H 82N6     | Notebook    | [d739547049](https://linux-hardware.org/?probe=d739547049) | Sep 23, 2022 |
| Lenovo        | 10051                       | All in one  | [195ec7cb8c](https://linux-hardware.org/?probe=195ec7cb8c) | Sep 23, 2022 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [568bffc355](https://linux-hardware.org/?probe=568bffc355) | Sep 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [73fd6c23e1](https://linux-hardware.org/?probe=73fd6c23e1) | Sep 21, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [0f698c857c](https://linux-hardware.org/?probe=0f698c857c) | Sep 16, 2022 |
| Dell          | Precision 3561              | Notebook    | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [356956ad10](https://linux-hardware.org/?probe=356956ad10) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b50a1bc29b](https://linux-hardware.org/?probe=b50a1bc29b) | Sep 09, 2022 |
| Dell          | Latitude 3320               | Notebook    | [1ab9888966](https://linux-hardware.org/?probe=1ab9888966) | Sep 09, 2022 |
| ASUSTek       | X99-E WS                    | Desktop     | [c76dceef8e](https://linux-hardware.org/?probe=c76dceef8e) | Sep 08, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | Desktop     | [a61798e4d3](https://linux-hardware.org/?probe=a61798e4d3) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | Desktop     | [0ba66b6e07](https://linux-hardware.org/?probe=0ba66b6e07) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | Desktop     | [169df470a6](https://linux-hardware.org/?probe=169df470a6) | Sep 05, 2022 |
| MSI           | Pulse GL66 11UGK            | Notebook    | [db7f9099f2](https://linux-hardware.org/?probe=db7f9099f2) | Sep 05, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [814c094769](https://linux-hardware.org/?probe=814c094769) | Sep 01, 2022 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [3f61df6540](https://linux-hardware.org/?probe=3f61df6540) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [c94e06f68f](https://linux-hardware.org/?probe=c94e06f68f) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [7be66c9d4c](https://linux-hardware.org/?probe=7be66c9d4c) | Aug 25, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [5e20db2905](https://linux-hardware.org/?probe=5e20db2905) | Aug 24, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [f0c2f3a689](https://linux-hardware.org/?probe=f0c2f3a689) | Aug 24, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [a332f284ab](https://linux-hardware.org/?probe=a332f284ab) | Aug 22, 2022 |
| Acer          | Aspire V5-471PG             | Notebook    | [c91dcf26c8](https://linux-hardware.org/?probe=c91dcf26c8) | Aug 14, 2022 |
| Dell          | Latitude 3320               | Notebook    | [b8e1190875](https://linux-hardware.org/?probe=b8e1190875) | Aug 14, 2022 |
| Dell          | Latitude 3320               | Notebook    | [f489cd4f21](https://linux-hardware.org/?probe=f489cd4f21) | Aug 14, 2022 |
| Timi          | TM1701                      | Notebook    | [dc4d12ca83](https://linux-hardware.org/?probe=dc4d12ca83) | Aug 14, 2022 |
| Acer          | Aspire V5-471PG             | Notebook    | [5c2d9bf35f](https://linux-hardware.org/?probe=5c2d9bf35f) | Aug 13, 2022 |
| Dell          | G15 5520                    | Notebook    | [07feaad5d2](https://linux-hardware.org/?probe=07feaad5d2) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [5931b46fe1](https://linux-hardware.org/?probe=5931b46fe1) | Aug 10, 2022 |
| HP            | 843B                        | Desktop     | [6033dabb9d](https://linux-hardware.org/?probe=6033dabb9d) | Aug 09, 2022 |
| Dell          | Latitude 3320               | Notebook    | [b99f237d17](https://linux-hardware.org/?probe=b99f237d17) | Aug 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [681326262a](https://linux-hardware.org/?probe=681326262a) | Aug 08, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [6a9c811ea3](https://linux-hardware.org/?probe=6a9c811ea3) | Aug 07, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9893d12c54](https://linux-hardware.org/?probe=9893d12c54) | Aug 06, 2022 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| HP            | ZBook 15v G5                | Notebook    | [b08d670a98](https://linux-hardware.org/?probe=b08d670a98) | Jul 28, 2022 |
| Acer          | Spin SP513-52N              | Convertible | [975a56edb1](https://linux-hardware.org/?probe=975a56edb1) | Jul 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [f6670624ed](https://linux-hardware.org/?probe=f6670624ed) | Jul 16, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [366f3c9611](https://linux-hardware.org/?probe=366f3c9611) | Jul 14, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [27f2c99f99](https://linux-hardware.org/?probe=27f2c99f99) | Jul 14, 2022 |
| Sony          | SVF1531V8CW                 | Notebook    | [bebf2fb162](https://linux-hardware.org/?probe=bebf2fb162) | Jul 13, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [b33dcf5312](https://linux-hardware.org/?probe=b33dcf5312) | Jul 12, 2022 |
| Dell          | Latitude 3120               | Notebook    | [361c9c4fa3](https://linux-hardware.org/?probe=361c9c4fa3) | Jul 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [e91c32dba7](https://linux-hardware.org/?probe=e91c32dba7) | Jun 25, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [a49c763e59](https://linux-hardware.org/?probe=a49c763e59) | Jun 23, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [c434fdda77](https://linux-hardware.org/?probe=c434fdda77) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [6941a8232a](https://linux-hardware.org/?probe=6941a8232a) | Jun 17, 2022 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [b30a078392](https://linux-hardware.org/?probe=b30a078392) | Jun 15, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [0415226162](https://linux-hardware.org/?probe=0415226162) | Jun 11, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [df2d1b5c12](https://linux-hardware.org/?probe=df2d1b5c12) | Jun 11, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [53877eebd1](https://linux-hardware.org/?probe=53877eebd1) | Jun 10, 2022 |
| Sony          | VPCCA15FG                   | Notebook    | [d155f5ee52](https://linux-hardware.org/?probe=d155f5ee52) | Jun 08, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [70eccb19d4](https://linux-hardware.org/?probe=70eccb19d4) | Jun 01, 2022 |
| Unknown       | ZynqMP SMK-K26 Rev1/B/A     | Soc         | [1acb6dc064](https://linux-hardware.org/?probe=1acb6dc064) | May 31, 2022 |
| Lenovo        | 14w 81MQS02H00              | Notebook    | [e31087bfa9](https://linux-hardware.org/?probe=e31087bfa9) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [f1f75187e1](https://linux-hardware.org/?probe=f1f75187e1) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [8fd4bc6a6d](https://linux-hardware.org/?probe=8fd4bc6a6d) | May 15, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [0906d694b9](https://linux-hardware.org/?probe=0906d694b9) | May 15, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [bd4201a786](https://linux-hardware.org/?probe=bd4201a786) | May 09, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [8deb85f8e2](https://linux-hardware.org/?probe=8deb85f8e2) | May 03, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [78752966d0](https://linux-hardware.org/?probe=78752966d0) | May 02, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [200ed04d31](https://linux-hardware.org/?probe=200ed04d31) | May 02, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3a7cd290f6](https://linux-hardware.org/?probe=3a7cd290f6) | Apr 30, 2022 |
| Dell          | 06CV2N A00                  | Desktop     | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Dell          | Latitude 3120               | Notebook    | [c6b9dfe36e](https://linux-hardware.org/?probe=c6b9dfe36e) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [69b4016133](https://linux-hardware.org/?probe=69b4016133) | Apr 15, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7fe8e51699](https://linux-hardware.org/?probe=7fe8e51699) | Apr 13, 2022 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [b8c46a667d](https://linux-hardware.org/?probe=b8c46a667d) | Apr 12, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [8e602bc358](https://linux-hardware.org/?probe=8e602bc358) | Apr 07, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [7309102f77](https://linux-hardware.org/?probe=7309102f77) | Apr 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ceee79344c](https://linux-hardware.org/?probe=ceee79344c) | Mar 31, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [615009b8ee](https://linux-hardware.org/?probe=615009b8ee) | Mar 23, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [f4d3207c6d](https://linux-hardware.org/?probe=f4d3207c6d) | Mar 22, 2022 |
| AMI           | Intel                       | Notebook    | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [17b7d9dd0c](https://linux-hardware.org/?probe=17b7d9dd0c) | Mar 10, 2022 |
| HP            | 8054                        | Desktop     | [dfbd7e95d0](https://linux-hardware.org/?probe=dfbd7e95d0) | Mar 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d7f14afdd4](https://linux-hardware.org/?probe=d7f14afdd4) | Feb 26, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [f92ae76fed](https://linux-hardware.org/?probe=f92ae76fed) | Feb 24, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [a8c8bdd208](https://linux-hardware.org/?probe=a8c8bdd208) | Feb 23, 2022 |
| Dell          | 09M8Y8 A02                  | Desktop     | [862667e874](https://linux-hardware.org/?probe=862667e874) | Feb 22, 2022 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [9eb75ab42f](https://linux-hardware.org/?probe=9eb75ab42f) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [fbb2caeacf](https://linux-hardware.org/?probe=fbb2caeacf) | Feb 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [c5acc050e4](https://linux-hardware.org/?probe=c5acc050e4) | Feb 19, 2022 |
| Dell          | Precision 7560              | Notebook    | [811983afdd](https://linux-hardware.org/?probe=811983afdd) | Feb 17, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| ASUSTek       | N501JW                      | Notebook    | [55550ca825](https://linux-hardware.org/?probe=55550ca825) | Feb 13, 2022 |
| COPELION I... | ZX Series                   | Notebook    | [764c80257b](https://linux-hardware.org/?probe=764c80257b) | Feb 12, 2022 |
| COPELION I... | ZX Series                   | Notebook    | [958dcebefa](https://linux-hardware.org/?probe=958dcebefa) | Feb 12, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b426feb1d9](https://linux-hardware.org/?probe=b426feb1d9) | Feb 11, 2022 |
| Acer          | Predator G9-792             | Notebook    | [a01c295f77](https://linux-hardware.org/?probe=a01c295f77) | Feb 09, 2022 |
| Acer          | Predator G9-792             | Notebook    | [c030ff8b96](https://linux-hardware.org/?probe=c030ff8b96) | Feb 09, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a7ba3830f7](https://linux-hardware.org/?probe=a7ba3830f7) | Feb 07, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [3dbd4103ce](https://linux-hardware.org/?probe=3dbd4103ce) | Feb 06, 2022 |
| Dell          | 06CV2N A00                  | Desktop     | [b3be05cbce](https://linux-hardware.org/?probe=b3be05cbce) | Feb 06, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [190a99dd63](https://linux-hardware.org/?probe=190a99dd63) | Jan 31, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [5cb4dcfe48](https://linux-hardware.org/?probe=5cb4dcfe48) | Jan 29, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [39cac76612](https://linux-hardware.org/?probe=39cac76612) | Jan 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [a172ae51cf](https://linux-hardware.org/?probe=a172ae51cf) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [efbe19b07b](https://linux-hardware.org/?probe=efbe19b07b) | Jan 20, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [6c19d2fbd6](https://linux-hardware.org/?probe=6c19d2fbd6) | Jan 11, 2022 |
| ASUSTek       | N501JW                      | Notebook    | [af9aaff7ee](https://linux-hardware.org/?probe=af9aaff7ee) | Jan 05, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9309138e99](https://linux-hardware.org/?probe=9309138e99) | Dec 31, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [9f745065df](https://linux-hardware.org/?probe=9f745065df) | Dec 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [aae3ae242f](https://linux-hardware.org/?probe=aae3ae242f) | Dec 21, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [ef12425b00](https://linux-hardware.org/?probe=ef12425b00) | Dec 19, 2021 |
| ASRock        | B560M Pro4                  | Desktop     | [bd3ec294cb](https://linux-hardware.org/?probe=bd3ec294cb) | Dec 18, 2021 |
| Dell          | 0VD5HY A04                  | Desktop     | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [b92a9a109f](https://linux-hardware.org/?probe=b92a9a109f) | Dec 18, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [96c2c68676](https://linux-hardware.org/?probe=96c2c68676) | Dec 16, 2021 |
| Dell          | 0C96W1 A02                  | Desktop     | [31f32bf184](https://linux-hardware.org/?probe=31f32bf184) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [91b2a03d70](https://linux-hardware.org/?probe=91b2a03d70) | Dec 13, 2021 |
| Dell          | Inspiron 5580               | Notebook    | [29d56d5a5e](https://linux-hardware.org/?probe=29d56d5a5e) | Dec 06, 2021 |
| INET          | Z12B                        | Mini pc     | [a18fff612e](https://linux-hardware.org/?probe=a18fff612e) | Dec 05, 2021 |
| ASUSTek       | K501UX                      | Notebook    | [3f9b547c57](https://linux-hardware.org/?probe=3f9b547c57) | Dec 04, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8876123555](https://linux-hardware.org/?probe=8876123555) | Nov 26, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [19812541db](https://linux-hardware.org/?probe=19812541db) | Nov 23, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [0eac4a44ef](https://linux-hardware.org/?probe=0eac4a44ef) | Nov 23, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [cf60dd841c](https://linux-hardware.org/?probe=cf60dd841c) | Nov 10, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [97e66fa893](https://linux-hardware.org/?probe=97e66fa893) | Nov 09, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [97e2f36d1f](https://linux-hardware.org/?probe=97e2f36d1f) | Nov 07, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [5d9f112e39](https://linux-hardware.org/?probe=5d9f112e39) | Nov 07, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [4b9f5aed33](https://linux-hardware.org/?probe=4b9f5aed33) | Nov 01, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [9ad082f18e](https://linux-hardware.org/?probe=9ad082f18e) | Nov 01, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7ad1f07edb](https://linux-hardware.org/?probe=7ad1f07edb) | Oct 21, 2021 |
| congatec      | conga-MA5 B.2               | Mini pc     | [a393bc32f9](https://linux-hardware.org/?probe=a393bc32f9) | Oct 18, 2021 |
| congatec      | conga-MA5 B.2               | Mini pc     | [10851c579f](https://linux-hardware.org/?probe=10851c579f) | Oct 16, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5ac27f4e29](https://linux-hardware.org/?probe=5ac27f4e29) | Oct 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6e2173f8b4](https://linux-hardware.org/?probe=6e2173f8b4) | Sep 30, 2021 |
| ASUSTek       | UX32LA                      | Notebook    | [9763fb0928](https://linux-hardware.org/?probe=9763fb0928) | Sep 25, 2021 |
| ASUSTek       | UX32LA                      | Notebook    | [e97b7fce6b](https://linux-hardware.org/?probe=e97b7fce6b) | Sep 25, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [e1c9dadb12](https://linux-hardware.org/?probe=e1c9dadb12) | Sep 12, 2021 |
| Acer          | Aspire 6935                 | Notebook    | [fc440eee50](https://linux-hardware.org/?probe=fc440eee50) | Sep 12, 2021 |
| Acer          | Aspire 6935                 | Notebook    | [24cfb86539](https://linux-hardware.org/?probe=24cfb86539) | Sep 12, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [02983fa577](https://linux-hardware.org/?probe=02983fa577) | Sep 08, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [6daf2c7553](https://linux-hardware.org/?probe=6daf2c7553) | Sep 04, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [bea89f1164](https://linux-hardware.org/?probe=bea89f1164) | Sep 04, 2021 |
| ASRock        | Z77 Extreme3                | Desktop     | [0e95fc1e3d](https://linux-hardware.org/?probe=0e95fc1e3d) | Sep 03, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [b7ff195931](https://linux-hardware.org/?probe=b7ff195931) | Sep 02, 2021 |
| Dell          | Precision 7560              | Notebook    | [75c607555e](https://linux-hardware.org/?probe=75c607555e) | Aug 27, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [adf156f9db](https://linux-hardware.org/?probe=adf156f9db) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| Lenovo        | NOK                         | Desktop     | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [606b3cf160](https://linux-hardware.org/?probe=606b3cf160) | Aug 23, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f4ec2b8446](https://linux-hardware.org/?probe=f4ec2b8446) | Aug 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [a613776a9c](https://linux-hardware.org/?probe=a613776a9c) | Aug 18, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [d0952296d7](https://linux-hardware.org/?probe=d0952296d7) | Aug 17, 2021 |
| Dell          | Inspiron 7370               | Notebook    | [b702f17a07](https://linux-hardware.org/?probe=b702f17a07) | Aug 17, 2021 |
| Acer          | Swift SF314-57G             | Notebook    | [a5f10ae10b](https://linux-hardware.org/?probe=a5f10ae10b) | Aug 17, 2021 |
| Biostar       | TB250-BTC+                  | Desktop     | [f45d61ab64](https://linux-hardware.org/?probe=f45d61ab64) | Jul 31, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [85f066488a](https://linux-hardware.org/?probe=85f066488a) | Jul 29, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [fd1285b7f2](https://linux-hardware.org/?probe=fd1285b7f2) | Jul 29, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | Notebook    | [978dbea880](https://linux-hardware.org/?probe=978dbea880) | Jul 27, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | Notebook    | [e3c0726e19](https://linux-hardware.org/?probe=e3c0726e19) | Jul 27, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [e74f010570](https://linux-hardware.org/?probe=e74f010570) | Jul 26, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [f938836ae3](https://linux-hardware.org/?probe=f938836ae3) | Jul 24, 2021 |
| Toshiba       | PORTEGE R930                | Notebook    | [6141314610](https://linux-hardware.org/?probe=6141314610) | Jul 22, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [502fe1bf66](https://linux-hardware.org/?probe=502fe1bf66) | Jul 19, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| ASUSTek       | K45VM                       | Notebook    | [6d08e71c4e](https://linux-hardware.org/?probe=6d08e71c4e) | Jul 07, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f4778083d9](https://linux-hardware.org/?probe=f4778083d9) | Jul 02, 2021 |
| Acer          | Swift SF314-41G             | Notebook    | [fe5e126da1](https://linux-hardware.org/?probe=fe5e126da1) | Jul 01, 2021 |
| Acer          | Aspire one                  | Notebook    | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| LattePanda    | Alpha                       | Desktop     | [1d9daab9aa](https://linux-hardware.org/?probe=1d9daab9aa) | Jun 20, 2021 |
| LattePanda    | Alpha                       | Desktop     | [e9ef19ed6e](https://linux-hardware.org/?probe=e9ef19ed6e) | Jun 20, 2021 |
| Sony          | VPCSB36FG                   | Notebook    | [c834499816](https://linux-hardware.org/?probe=c834499816) | Jun 10, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [650e1b9bf5](https://linux-hardware.org/?probe=650e1b9bf5) | Jun 05, 2021 |
| Dell          | Latitude 7490               | Notebook    | [879fc7a838](https://linux-hardware.org/?probe=879fc7a838) | May 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8bf489a0cb](https://linux-hardware.org/?probe=8bf489a0cb) | May 26, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e16504b6f4](https://linux-hardware.org/?probe=e16504b6f4) | May 25, 2021 |
| HP            | 198E                        | Desktop     | [a44ce74aaa](https://linux-hardware.org/?probe=a44ce74aaa) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [920ef637b1](https://linux-hardware.org/?probe=920ef637b1) | May 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [c9c9d02ede](https://linux-hardware.org/?probe=c9c9d02ede) | May 20, 2021 |
| Sony          | VPCSB36FG                   | Notebook    | [828a8ac75d](https://linux-hardware.org/?probe=828a8ac75d) | May 18, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [ffa207ed1e](https://linux-hardware.org/?probe=ffa207ed1e) | May 14, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d2d2eb910a](https://linux-hardware.org/?probe=d2d2eb910a) | May 12, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [589d53b7ce](https://linux-hardware.org/?probe=589d53b7ce) | May 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c17ba8c1a6](https://linux-hardware.org/?probe=c17ba8c1a6) | May 04, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [e20da66200](https://linux-hardware.org/?probe=e20da66200) | Apr 17, 2021 |
| ASRock        | HM55-MXM                    | Desktop     | [e56d216ab7](https://linux-hardware.org/?probe=e56d216ab7) | Apr 14, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| Lenovo        | ThinkCentre M90p 5864BM3    | Desktop     | [666e4f970e](https://linux-hardware.org/?probe=666e4f970e) | Apr 10, 2021 |
| Dell          | 0D6H9T A00                  | Desktop     | [94d321f020](https://linux-hardware.org/?probe=94d321f020) | Apr 02, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [e26f3c0f44](https://linux-hardware.org/?probe=e26f3c0f44) | Mar 29, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [e4c813c694](https://linux-hardware.org/?probe=e4c813c694) | Mar 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ce138f71dd](https://linux-hardware.org/?probe=ce138f71dd) | Mar 15, 2021 |
| Toshiba       | PORTEGE R930                | Notebook    | [6e5981a1c8](https://linux-hardware.org/?probe=6e5981a1c8) | Mar 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [81b4d6916d](https://linux-hardware.org/?probe=81b4d6916d) | Mar 11, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [46ff93e8b8](https://linux-hardware.org/?probe=46ff93e8b8) | Mar 09, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [98a5817785](https://linux-hardware.org/?probe=98a5817785) | Mar 09, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [820e208bca](https://linux-hardware.org/?probe=820e208bca) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [d8b4e607e1](https://linux-hardware.org/?probe=d8b4e607e1) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [eca0e7f55f](https://linux-hardware.org/?probe=eca0e7f55f) | Mar 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9eff035231](https://linux-hardware.org/?probe=9eff035231) | Mar 01, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e6cb859b40](https://linux-hardware.org/?probe=e6cb859b40) | Feb 21, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [eb33727eff](https://linux-hardware.org/?probe=eb33727eff) | Feb 18, 2021 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [b2795c1a02](https://linux-hardware.org/?probe=b2795c1a02) | Feb 13, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [e67e7f24e8](https://linux-hardware.org/?probe=e67e7f24e8) | Feb 11, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [cbb8e959b4](https://linux-hardware.org/?probe=cbb8e959b4) | Feb 05, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [a8f5211aee](https://linux-hardware.org/?probe=a8f5211aee) | Feb 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [f4505630e3](https://linux-hardware.org/?probe=f4505630e3) | Feb 03, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [563ceb4238](https://linux-hardware.org/?probe=563ceb4238) | Jan 28, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [0e5eeb215d](https://linux-hardware.org/?probe=0e5eeb215d) | Jan 28, 2021 |
| ASUSTek       | UX360UAK                    | Convertible | [93b1606116](https://linux-hardware.org/?probe=93b1606116) | Jan 27, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | Notebook    | [15d05a517c](https://linux-hardware.org/?probe=15d05a517c) | Jan 23, 2021 |
| Notebook      | P65_P67SE                   | Notebook    | [1b4cd968fd](https://linux-hardware.org/?probe=1b4cd968fd) | Jan 22, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [08990229db](https://linux-hardware.org/?probe=08990229db) | Jan 17, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [dc6edb4a25](https://linux-hardware.org/?probe=dc6edb4a25) | Jan 14, 2021 |
| Dell          | G3 3500                     | Notebook    | [27386ee67b](https://linux-hardware.org/?probe=27386ee67b) | Jan 12, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [e08b05c812](https://linux-hardware.org/?probe=e08b05c812) | Jan 09, 2021 |
| Lenovo        | ThinkPad E14 20RA0058VA     | Notebook    | [3c08ce49f5](https://linux-hardware.org/?probe=3c08ce49f5) | Jan 08, 2021 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [10b66f86e5](https://linux-hardware.org/?probe=10b66f86e5) | Jan 04, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [e5b808ee57](https://linux-hardware.org/?probe=e5b808ee57) | Jan 02, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [4b19f38fcd](https://linux-hardware.org/?probe=4b19f38fcd) | Jan 02, 2021 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [3f041f4b71](https://linux-hardware.org/?probe=3f041f4b71) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [c30d1c7374](https://linux-hardware.org/?probe=c30d1c7374) | Dec 31, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [ccd41dd67e](https://linux-hardware.org/?probe=ccd41dd67e) | Dec 28, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [2fd914ada2](https://linux-hardware.org/?probe=2fd914ada2) | Dec 25, 2020 |
| Microsoft     | Surface Pro                 | Tablet      | [38d64b5845](https://linux-hardware.org/?probe=38d64b5845) | Dec 22, 2020 |
| Acer          | Aspire one                  | Notebook    | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| ASUSTek       | P9D-X Series                | Server      | [519b6669d2](https://linux-hardware.org/?probe=519b6669d2) | Dec 11, 2020 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [1d878eeb02](https://linux-hardware.org/?probe=1d878eeb02) | Dec 10, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [e28bcb99e5](https://linux-hardware.org/?probe=e28bcb99e5) | Dec 07, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca915222e5](https://linux-hardware.org/?probe=ca915222e5) | Dec 07, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [1d822ef5a3](https://linux-hardware.org/?probe=1d822ef5a3) | Dec 07, 2020 |
| ASUSTek       | K45VM                       | Notebook    | [9dedb35f93](https://linux-hardware.org/?probe=9dedb35f93) | Dec 04, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [b9461ebddd](https://linux-hardware.org/?probe=b9461ebddd) | Nov 29, 2020 |
| Aftershock    | N15_N17RF1                  | Notebook    | [09b42b449a](https://linux-hardware.org/?probe=09b42b449a) | Nov 27, 2020 |
| Dell          | Precision 7530              | Notebook    | [6ea3afdb4a](https://linux-hardware.org/?probe=6ea3afdb4a) | Nov 26, 2020 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [1250c7dfbe](https://linux-hardware.org/?probe=1250c7dfbe) | Nov 25, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [cc79643d27](https://linux-hardware.org/?probe=cc79643d27) | Nov 22, 2020 |
| Dell          | Latitude 7400               | Notebook    | [3154149e40](https://linux-hardware.org/?probe=3154149e40) | Nov 21, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [93678477d7](https://linux-hardware.org/?probe=93678477d7) | Nov 20, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [c0ab31022d](https://linux-hardware.org/?probe=c0ab31022d) | Nov 20, 2020 |
| Dell          | 0D441T A03                  | Desktop     | [b57394e325](https://linux-hardware.org/?probe=b57394e325) | Nov 20, 2020 |
| ASUSTek       | E3M-ET V5 SERIES            | Desktop     | [f1faffa793](https://linux-hardware.org/?probe=f1faffa793) | Nov 20, 2020 |
| ASUSTek       | E3M-ET V5 SERIES            | Desktop     | [e727ca80a6](https://linux-hardware.org/?probe=e727ca80a6) | Nov 20, 2020 |
| HP            | 81C6 MVB 0C                 | Server      | [298cea57e1](https://linux-hardware.org/?probe=298cea57e1) | Nov 19, 2020 |
| Dell          | Inspiron 5379               | Notebook    | [63815d0103](https://linux-hardware.org/?probe=63815d0103) | Nov 15, 2020 |
| ASUSTek       | M4A78-EM-1394               | Desktop     | [3736bdc191](https://linux-hardware.org/?probe=3736bdc191) | Nov 12, 2020 |
| ASRock        | H110M-HDS R3.0              | Desktop     | [7dea4e7c04](https://linux-hardware.org/?probe=7dea4e7c04) | Nov 10, 2020 |
| Fujitsu       | LIFEBOOK SH561              | Notebook    | [759718c54b](https://linux-hardware.org/?probe=759718c54b) | Nov 10, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [f3f5326846](https://linux-hardware.org/?probe=f3f5326846) | Nov 08, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [e08c38affc](https://linux-hardware.org/?probe=e08c38affc) | Nov 04, 2020 |
| HP            | 81C6 MVB 0C                 | Server      | [eaa10c5051](https://linux-hardware.org/?probe=eaa10c5051) | Oct 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [14cf318590](https://linux-hardware.org/?probe=14cf318590) | Oct 29, 2020 |
| Acer          | Swift SF314-54              | Notebook    | [35aa366265](https://linux-hardware.org/?probe=35aa366265) | Oct 18, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [8396c1d9e6](https://linux-hardware.org/?probe=8396c1d9e6) | Oct 13, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [b47f8da412](https://linux-hardware.org/?probe=b47f8da412) | Oct 09, 2020 |
| ASRock        | 990FX Killer                | Desktop     | [4faf15fe7f](https://linux-hardware.org/?probe=4faf15fe7f) | Oct 08, 2020 |
| HP            | Compaq 6510b                | Notebook    | [cf190a85ea](https://linux-hardware.org/?probe=cf190a85ea) | Oct 08, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2dada3cfbe](https://linux-hardware.org/?probe=2dada3cfbe) | Sep 30, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c0f7498f1b](https://linux-hardware.org/?probe=c0f7498f1b) | Sep 30, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [f542320df7](https://linux-hardware.org/?probe=f542320df7) | Sep 28, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [05ef194f79](https://linux-hardware.org/?probe=05ef194f79) | Sep 28, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [78566669f0](https://linux-hardware.org/?probe=78566669f0) | Sep 27, 2020 |
| ASUSTek       | T300LA                      | Notebook    | [9ca4cba592](https://linux-hardware.org/?probe=9ca4cba592) | Sep 27, 2020 |
| Dell          | Inspiron 3476               | Notebook    | [021351472c](https://linux-hardware.org/?probe=021351472c) | Sep 26, 2020 |
| ASUSTek       | M3A78-EM                    | Desktop     | [65ed8bba9c](https://linux-hardware.org/?probe=65ed8bba9c) | Sep 23, 2020 |
| HP            | Compaq 6510b                | Notebook    | [9b9a4b4614](https://linux-hardware.org/?probe=9b9a4b4614) | Sep 22, 2020 |
| HP            | Compaq 6510b                | Notebook    | [3487aab3a6](https://linux-hardware.org/?probe=3487aab3a6) | Sep 20, 2020 |
| HP            | Compaq 6510b                | Notebook    | [b7382d2141](https://linux-hardware.org/?probe=b7382d2141) | Sep 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [4a4a01267c](https://linux-hardware.org/?probe=4a4a01267c) | Sep 18, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [dc9532c57b](https://linux-hardware.org/?probe=dc9532c57b) | Sep 12, 2020 |
| Samsung       | 305U1A                      | Notebook    | [9949d76953](https://linux-hardware.org/?probe=9949d76953) | Sep 09, 2020 |
| Samsung       | 305U1A                      | Notebook    | [9dbf37ad63](https://linux-hardware.org/?probe=9dbf37ad63) | Sep 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [cab06cdbd7](https://linux-hardware.org/?probe=cab06cdbd7) | Sep 07, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [c9d6ce6954](https://linux-hardware.org/?probe=c9d6ce6954) | Sep 05, 2020 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [db8a9ea1ef](https://linux-hardware.org/?probe=db8a9ea1ef) | Sep 04, 2020 |
| Aftershock    | N8xxEP6                     | Notebook    | [d8e9d4edfd](https://linux-hardware.org/?probe=d8e9d4edfd) | Sep 04, 2020 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [56d2f5c077](https://linux-hardware.org/?probe=56d2f5c077) | Sep 03, 2020 |
| Dell          | Precision 7530              | Notebook    | [91306b715e](https://linux-hardware.org/?probe=91306b715e) | Sep 03, 2020 |
| Aftershock    | N15_N17RF1                  | Notebook    | [e3e85f51cc](https://linux-hardware.org/?probe=e3e85f51cc) | Sep 03, 2020 |
| Dell          | Latitude 5400               | Notebook    | [498b1be7bd](https://linux-hardware.org/?probe=498b1be7bd) | Sep 02, 2020 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [3a8e991dee](https://linux-hardware.org/?probe=3a8e991dee) | Sep 01, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [64ba8fde9d](https://linux-hardware.org/?probe=64ba8fde9d) | Aug 31, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [b37b0d860d](https://linux-hardware.org/?probe=b37b0d860d) | Aug 31, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d6a3031f11](https://linux-hardware.org/?probe=d6a3031f11) | Aug 30, 2020 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [3623866056](https://linux-hardware.org/?probe=3623866056) | Aug 28, 2020 |
| HP            | Compaq 6510b                | Notebook    | [7db74443d5](https://linux-hardware.org/?probe=7db74443d5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | Notebook    | [20f281e6e5](https://linux-hardware.org/?probe=20f281e6e5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | Notebook    | [2791e33d53](https://linux-hardware.org/?probe=2791e33d53) | Aug 24, 2020 |
| ASUSTek       | V200IB                      | All in one  | [16748c4ba8](https://linux-hardware.org/?probe=16748c4ba8) | Aug 23, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | Notebook    | [8bc9e504d7](https://linux-hardware.org/?probe=8bc9e504d7) | Aug 13, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [9f944b581d](https://linux-hardware.org/?probe=9f944b581d) | Aug 09, 2020 |
| Sony          | VGN-CR32G_W                 | Notebook    | [faf8f6a6fa](https://linux-hardware.org/?probe=faf8f6a6fa) | Aug 08, 2020 |
| Sony          | VGN-CR32G_W                 | Notebook    | [421ed7dcba](https://linux-hardware.org/?probe=421ed7dcba) | Aug 08, 2020 |
| MECHREVO      | Code 01 Series PF5NU1G      | Notebook    | [4dffd28998](https://linux-hardware.org/?probe=4dffd28998) | Aug 07, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | Notebook    | [4319315cd0](https://linux-hardware.org/?probe=4319315cd0) | Jul 25, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [efb532b71e](https://linux-hardware.org/?probe=efb532b71e) | Jul 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [b6111e69ca](https://linux-hardware.org/?probe=b6111e69ca) | Jul 19, 2020 |
| ASRock        | HM55-MXM                    | Desktop     | [7f12e5a53c](https://linux-hardware.org/?probe=7f12e5a53c) | Jul 19, 2020 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [b554a2c8ec](https://linux-hardware.org/?probe=b554a2c8ec) | Jul 14, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [6d5b75622f](https://linux-hardware.org/?probe=6d5b75622f) | Jul 10, 2020 |
| HP            | Pavilion dv6000 (GF659EA... | Notebook    | [84a4ec9209](https://linux-hardware.org/?probe=84a4ec9209) | Jul 09, 2020 |
| HP            | EliteBook 725 G4            | Notebook    | [941e94f528](https://linux-hardware.org/?probe=941e94f528) | Jul 09, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU27    | Notebook    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [16b4aed55f](https://linux-hardware.org/?probe=16b4aed55f) | Jul 07, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [e794850de2](https://linux-hardware.org/?probe=e794850de2) | Jul 05, 2020 |
| HP            | EliteBook 725 G4            | Notebook    | [b3e1336d2f](https://linux-hardware.org/?probe=b3e1336d2f) | Jul 04, 2020 |
| Acer          | Swift SF514-54GT            | Notebook    | [a5b63702a2](https://linux-hardware.org/?probe=a5b63702a2) | Jul 03, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3769ee6e50](https://linux-hardware.org/?probe=3769ee6e50) | Jul 01, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [121efa47d4](https://linux-hardware.org/?probe=121efa47d4) | Jul 01, 2020 |
| Lenovo        | ThinkPad T420s 417429U      | Notebook    | [8d9ec3fd6e](https://linux-hardware.org/?probe=8d9ec3fd6e) | Jun 27, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [7b35a1c840](https://linux-hardware.org/?probe=7b35a1c840) | Jun 26, 2020 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [dd0834c2dd](https://linux-hardware.org/?probe=dd0834c2dd) | Jun 23, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [a4ebb57c65](https://linux-hardware.org/?probe=a4ebb57c65) | Jun 19, 2020 |
| Lenovo        | IdeaPad U460 20056          | Notebook    | [31c7edc616](https://linux-hardware.org/?probe=31c7edc616) | Jun 17, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [5d31ba79a1](https://linux-hardware.org/?probe=5d31ba79a1) | Jun 17, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2c22387cdf](https://linux-hardware.org/?probe=2c22387cdf) | Jun 17, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | Notebook    | [4add01698f](https://linux-hardware.org/?probe=4add01698f) | Jun 14, 2020 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [9e8603cab8](https://linux-hardware.org/?probe=9e8603cab8) | Jun 05, 2020 |
| Dell          | Latitude E7440              | Notebook    | [1664235765](https://linux-hardware.org/?probe=1664235765) | Jun 03, 2020 |
| Dell          | Latitude E7440              | Notebook    | [d71cf3dba2](https://linux-hardware.org/?probe=d71cf3dba2) | Jun 03, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| ASRock        | H110M-HDS R3.0              | Desktop     | [8610132ae8](https://linux-hardware.org/?probe=8610132ae8) | Jun 03, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [a8c4b1a8cf](https://linux-hardware.org/?probe=a8c4b1a8cf) | Jun 01, 2020 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [74e66b2a4a](https://linux-hardware.org/?probe=74e66b2a4a) | May 30, 2020 |
| Lenovo        | ThinkPad L460 20FUCTO1WW    | Notebook    | [da2a23020c](https://linux-hardware.org/?probe=da2a23020c) | May 21, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [c91cd5679c](https://linux-hardware.org/?probe=c91cd5679c) | May 19, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [10e8823c6b](https://linux-hardware.org/?probe=10e8823c6b) | May 17, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ea544afa99](https://linux-hardware.org/?probe=ea544afa99) | May 12, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [058ecc2781](https://linux-hardware.org/?probe=058ecc2781) | May 12, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [cfd6e82a6f](https://linux-hardware.org/?probe=cfd6e82a6f) | May 11, 2020 |
| ASUSTek       | PRIME H310M-A               | Desktop     | [aaed21ffd0](https://linux-hardware.org/?probe=aaed21ffd0) | May 08, 2020 |
| Acer          | Predator PH315-52           | Notebook    | [7adb1a873c](https://linux-hardware.org/?probe=7adb1a873c) | May 04, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | Notebook    | [09817eac19](https://linux-hardware.org/?probe=09817eac19) | May 01, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | Notebook    | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| Dell          | 06D7TR A00                  | Desktop     | [60b49366ed](https://linux-hardware.org/?probe=60b49366ed) | Apr 30, 2020 |
| ASUSTek       | T300LA                      | Notebook    | [c173e838c3](https://linux-hardware.org/?probe=c173e838c3) | Apr 26, 2020 |
| ASUSTek       | T300LA                      | Notebook    | [6311e7f4b5](https://linux-hardware.org/?probe=6311e7f4b5) | Apr 26, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [42636a47b1](https://linux-hardware.org/?probe=42636a47b1) | Apr 26, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [a9cd8ef28f](https://linux-hardware.org/?probe=a9cd8ef28f) | Apr 22, 2020 |
| Acer          | Prespa1                     | Notebook    | [791259386e](https://linux-hardware.org/?probe=791259386e) | Apr 16, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [d5124038f4](https://linux-hardware.org/?probe=d5124038f4) | Apr 15, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [7e6120b5c7](https://linux-hardware.org/?probe=7e6120b5c7) | Apr 10, 2020 |
| Lenovo        | B50-30 20382                | Notebook    | [57b8f867a1](https://linux-hardware.org/?probe=57b8f867a1) | Apr 09, 2020 |
| Acer          | Aspire E5-473G              | Notebook    | [17f3a0e473](https://linux-hardware.org/?probe=17f3a0e473) | Apr 08, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [429fde3ebd](https://linux-hardware.org/?probe=429fde3ebd) | Apr 02, 2020 |
| Dell          | Latitude E6410              | Notebook    | [920a80dc90](https://linux-hardware.org/?probe=920a80dc90) | Mar 31, 2020 |
| Apple         | MacBookPro11,4              | Notebook    | [3c9bd63848](https://linux-hardware.org/?probe=3c9bd63848) | Mar 30, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [2a99d0f76b](https://linux-hardware.org/?probe=2a99d0f76b) | Mar 28, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [26486f2fff](https://linux-hardware.org/?probe=26486f2fff) | Mar 24, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [93d970f678](https://linux-hardware.org/?probe=93d970f678) | Mar 24, 2020 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [daa4d098dc](https://linux-hardware.org/?probe=daa4d098dc) | Mar 13, 2020 |
| Dell          | 0X8DXD A01                  | Desktop     | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [001695659e](https://linux-hardware.org/?probe=001695659e) | Mar 04, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [199fc82812](https://linux-hardware.org/?probe=199fc82812) | Mar 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th E... | Notebook    | [b913bc5cc5](https://linux-hardware.org/?probe=b913bc5cc5) | Feb 18, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [819116ee69](https://linux-hardware.org/?probe=819116ee69) | Feb 16, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [93c40180a2](https://linux-hardware.org/?probe=93c40180a2) | Feb 11, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [f6c3a576c2](https://linux-hardware.org/?probe=f6c3a576c2) | Feb 11, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [627909b9e5](https://linux-hardware.org/?probe=627909b9e5) | Feb 04, 2020 |
| Dell          | Inspiron 7591               | Notebook    | [b33d5cddc5](https://linux-hardware.org/?probe=b33d5cddc5) | Jan 25, 2020 |
| Microsoft     | Surface Laptop 3            | Tablet      | [7910582d7c](https://linux-hardware.org/?probe=7910582d7c) | Jan 06, 2020 |
| Microsoft     | Surface Laptop 3            | Tablet      | [eb592eeb36](https://linux-hardware.org/?probe=eb592eeb36) | Jan 05, 2020 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [a38c129cd9](https://linux-hardware.org/?probe=a38c129cd9) | Jan 04, 2020 |
| Acer          | Aspire X3950                | Desktop     | [fd467d33f5](https://linux-hardware.org/?probe=fd467d33f5) | Jan 03, 2020 |
| ASUSTek       | U24E                        | Notebook    | [563b794d8a](https://linux-hardware.org/?probe=563b794d8a) | Dec 23, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [011ab343ef](https://linux-hardware.org/?probe=011ab343ef) | Dec 22, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [bb9da61133](https://linux-hardware.org/?probe=bb9da61133) | Dec 21, 2019 |
| Acer          | ConceptD CN715-71           | Notebook    | [54109739eb](https://linux-hardware.org/?probe=54109739eb) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | Notebook    | [5d75e45350](https://linux-hardware.org/?probe=5d75e45350) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | Notebook    | [fb27c8cabb](https://linux-hardware.org/?probe=fb27c8cabb) | Dec 20, 2019 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [adec400398](https://linux-hardware.org/?probe=adec400398) | Dec 19, 2019 |
| ASRock        | Z370 Pro4                   | Desktop     | [f681da046d](https://linux-hardware.org/?probe=f681da046d) | Dec 09, 2019 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [f35675231e](https://linux-hardware.org/?probe=f35675231e) | Dec 02, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [86221df903](https://linux-hardware.org/?probe=86221df903) | Nov 30, 2019 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [6bee5d9a22](https://linux-hardware.org/?probe=6bee5d9a22) | Nov 16, 2019 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [1b0467dde0](https://linux-hardware.org/?probe=1b0467dde0) | Nov 16, 2019 |
| Dell          | 0F3KHR A00                  | Desktop     | [636fbfdcb6](https://linux-hardware.org/?probe=636fbfdcb6) | Sep 22, 2019 |
| HP            | ZBook Studio G5             | Notebook    | [87503b1263](https://linux-hardware.org/?probe=87503b1263) | Aug 22, 2019 |
| ASUSTek       | X406UAR                     | Notebook    | [5e3ebad239](https://linux-hardware.org/?probe=5e3ebad239) | Jul 05, 2019 |
| Apple         | MacBookPro9,2               | Notebook    | [1d4494ee1f](https://linux-hardware.org/?probe=1d4494ee1f) | Jul 03, 2019 |
| Lenovo        | S20-30 20421                | Notebook    | [5c27867f6e](https://linux-hardware.org/?probe=5c27867f6e) | Jun 26, 2019 |
| Dell          | Inspiron 13-5378            | Notebook    | [f938ce631a](https://linux-hardware.org/?probe=f938ce631a) | Jun 17, 2019 |
| Dell          | Inspiron 13-5378            | Notebook    | [5e33156c57](https://linux-hardware.org/?probe=5e33156c57) | Jun 17, 2019 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [c6888a9735](https://linux-hardware.org/?probe=c6888a9735) | May 31, 2019 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0ab22425ea](https://linux-hardware.org/?probe=0ab22425ea) | May 28, 2019 |
| Apple         | MacBookPro11,5              | Notebook    | [ab95788992](https://linux-hardware.org/?probe=ab95788992) | May 18, 2019 |
| ASUSTek       | S500CA                      | Notebook    | [c0218275f7](https://linux-hardware.org/?probe=c0218275f7) | Apr 28, 2019 |
| Microsoft     | Surface Pro 4               | Tablet      | [6a82c09344](https://linux-hardware.org/?probe=6a82c09344) | Apr 16, 2019 |
| Microsoft     | Surface Pro 4               | Tablet      | [037f7f95c0](https://linux-hardware.org/?probe=037f7f95c0) | Apr 15, 2019 |
| ASUSTek       | ET2020I                     | Desktop     | [a695a9c422](https://linux-hardware.org/?probe=a695a9c422) | Apr 07, 2019 |
| Acer          | AO751h                      | Notebook    | [0ee57513c5](https://linux-hardware.org/?probe=0ee57513c5) | Apr 07, 2019 |
| MSI           | X299 RAIDER                 | Desktop     | [3f982f3e86](https://linux-hardware.org/?probe=3f982f3e86) | Dec 04, 2018 |
| MSI           | X299 RAIDER                 | Desktop     | [1207b80721](https://linux-hardware.org/?probe=1207b80721) | Dec 04, 2018 |
| MSI           | Boston                      | Desktop     | [104569cafb](https://linux-hardware.org/?probe=104569cafb) | Oct 24, 2018 |
| MSI           | GE63VR 7RE                  | Notebook    | [635226b290](https://linux-hardware.org/?probe=635226b290) | May 31, 2018 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [ecd2f8138f](https://linux-hardware.org/?probe=ecd2f8138f) | Dec 27, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 76        | 21.65%  |
| Ubuntu 18.04                 | 37        | 10.54%  |
| Ubuntu 22.04                 | 18        | 5.13%   |
| Fedora 33                    | 12        | 3.42%   |
| Arch Rolling                 | 10        | 2.85%   |
| Linux Mint 21                | 9         | 2.56%   |
| Pop!_OS 20.04                | 8         | 2.28%   |
| Arch                         | 8         | 2.28%   |
| Debian 11                    | 7         | 1.99%   |
| Pop!_OS 22.04                | 6         | 1.71%   |
| KDE neon 20.04               | 6         | 1.71%   |
| Ubuntu 21.10                 | 5         | 1.42%   |
| Ubuntu 21.04                 | 5         | 1.42%   |
| Linux Mint 20                | 5         | 1.42%   |
| Xubuntu 20.04                | 4         | 1.14%   |
| Pop!_OS 21.04                | 4         | 1.14%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 1.14%   |
| OpenMandriva 4.3             | 4         | 1.14%   |
| OpenMandriva 23.01           | 4         | 1.14%   |
| Manjaro                      | 4         | 1.14%   |
| Linux Mint 20.3              | 4         | 1.14%   |
| Kubuntu 22.04                | 4         | 1.14%   |
| Fedora 36                    | 4         | 1.14%   |
| Debian Testing               | 4         | 1.14%   |
| ArcoLinux Rolling            | 4         | 1.14%   |
| Zorin 16                     | 3         | 0.85%   |
| Fedora 37                    | 3         | 0.85%   |
| Fedora 34                    | 3         | 0.85%   |
| Fedora 32                    | 3         | 0.85%   |
| EndeavourOS Rolling          | 3         | 0.85%   |
| Elementary 6.1               | 3         | 0.85%   |
| Debian                       | 3         | 0.85%   |
| Zorin 15                     | 2         | 0.57%   |
| Ubuntu Unity 16.04           | 2         | 0.57%   |
| Ubuntu 22.10                 | 2         | 0.57%   |
| Ubuntu 19.10                 | 2         | 0.57%   |
| Ubuntu 19.04                 | 2         | 0.57%   |
| Ubuntu 18.10                 | 2         | 0.57%   |
| Rocky Linux 8.5              | 2         | 0.57%   |
| Raspbian 10                  | 2         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 148       | 43.27%  |
| Fedora        | 26        | 7.6%    |
| Pop!_OS       | 22        | 6.43%   |
| Linux Mint    | 18        | 5.26%   |
| Debian        | 17        | 4.97%   |
| Arch          | 17        | 4.97%   |
| OpenMandriva  | 14        | 4.09%   |
| Manjaro       | 9         | 2.63%   |
| Kubuntu       | 7         | 2.05%   |
| KDE neon      | 7         | 2.05%   |
| Zorin         | 5         | 1.46%   |
| Xubuntu       | 5         | 1.46%   |
| openSUSE      | 4         | 1.17%   |
| ArcoLinux     | 4         | 1.17%   |
| Ubuntu Unity  | 3         | 0.88%   |
| Rocky Linux   | 3         | 0.88%   |
| Lubuntu       | 3         | 0.88%   |
| EndeavourOS   | 3         | 0.88%   |
| Elementary    | 3         | 0.88%   |
| ROSA          | 2         | 0.58%   |
| RHEL          | 2         | 0.58%   |
| Raspbian      | 2         | 0.58%   |
| Kali          | 2         | 0.58%   |
| Gentoo        | 2         | 0.58%   |
| Garuda Linux  | 2         | 0.58%   |
| Endless       | 2         | 0.58%   |
| Clear Linux   | 2         | 0.58%   |
| Ubuntu MATE   | 1         | 0.29%   |
| Ubuntu Budgie | 1         | 0.29%   |
| Q4OS          | 1         | 0.29%   |
| Nobara        | 1         | 0.29%   |
| LMDE          | 1         | 0.29%   |
| Devuan        | 1         | 0.29%   |
| Deepin        | 1         | 0.29%   |
| CentOS        | 1         | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.15.0-56-generic       | 11        | 2.88%   |
| 5.15.0-46-generic       | 9         | 2.36%   |
| 5.9.8-200.fc33.x86_64   | 6         | 1.57%   |
| 5.4.0-48-generic        | 6         | 1.57%   |
| 5.4.0-42-generic        | 6         | 1.57%   |
| 5.4.0-40-generic        | 6         | 1.57%   |
| 5.4.0-37-generic        | 6         | 1.57%   |
| 5.4.0-29-generic        | 6         | 1.57%   |
| 5.4.0-52-generic        | 5         | 1.31%   |
| 5.11.0-43-generic       | 5         | 1.31%   |
| 6.1.1-desktop-1omv2290  | 4         | 1.05%   |
| 5.4.0-65-generic        | 4         | 1.05%   |
| 5.3.0-62-generic        | 4         | 1.05%   |
| 5.16.7-desktop-1omv4003 | 4         | 1.05%   |
| 5.15.0-43-generic       | 4         | 1.05%   |
| 5.15.0-41-generic       | 4         | 1.05%   |
| 5.4.0-7634-generic      | 3         | 0.79%   |
| 5.4.0-47-generic        | 3         | 0.79%   |
| 5.4.0-26-generic        | 3         | 0.79%   |
| 5.3.0-51-generic        | 3         | 0.79%   |
| 5.15.0-52-generic       | 3         | 0.79%   |
| 5.15.0-48-generic       | 3         | 0.79%   |
| 5.15.0-47-generic       | 3         | 0.79%   |
| 5.13.0-40-generic       | 3         | 0.79%   |
| 5.13.0-28-generic       | 3         | 0.79%   |
| 5.11.0-38-generic       | 3         | 0.79%   |
| 5.11.0-37-generic       | 3         | 0.79%   |
| 5.11.0-25-generic       | 3         | 0.79%   |
| 5.10.0-11-amd64         | 3         | 0.79%   |
| 5.0.0-23-generic        | 3         | 0.79%   |
| 6.0.6-76060006-generic  | 2         | 0.52%   |
| 6.0.15-300.fc37.x86_64  | 2         | 0.52%   |
| 5.8.0-7630-generic      | 2         | 0.52%   |
| 5.8.0-53-generic        | 2         | 0.52%   |
| 5.8.0-48-generic        | 2         | 0.52%   |
| 5.8.0-43-generic        | 2         | 0.52%   |
| 5.4.51-v7l+             | 2         | 0.52%   |
| 5.4.5-050405-generic    | 2         | 0.52%   |
| 5.4.0-96-generic        | 2         | 0.52%   |
| 5.4.0-81-generic        | 2         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 71        | 19.51%  |
| 5.15.0  | 44        | 12.09%  |
| 5.11.0  | 21        | 5.77%   |
| 5.13.0  | 17        | 4.67%   |
| 5.8.0   | 16        | 4.4%    |
| 4.18.0  | 13        | 3.57%   |
| 5.3.0   | 12        | 3.3%    |
| 5.0.0   | 11        | 3.02%   |
| 4.15.0  | 11        | 3.02%   |
| 5.10.0  | 9         | 2.47%   |
| 5.9.8   | 6         | 1.65%   |
| 5.18.0  | 6         | 1.65%   |
| 6.1.1   | 5         | 1.37%   |
| 5.19.0  | 4         | 1.1%    |
| 5.16.7  | 4         | 1.1%    |
| 6.0.0   | 3         | 0.82%   |
| 5.17.5  | 3         | 0.82%   |
| 5.13.13 | 3         | 0.82%   |
| 6.0.7   | 2         | 0.55%   |
| 6.0.6   | 2         | 0.55%   |
| 6.0.2   | 2         | 0.55%   |
| 6.0.15  | 2         | 0.55%   |
| 5.4.51  | 2         | 0.55%   |
| 5.4.5   | 2         | 0.55%   |
| 5.19.13 | 2         | 0.55%   |
| 5.15.5  | 2         | 0.55%   |
| 5.15.10 | 2         | 0.55%   |
| 5.13.12 | 2         | 0.55%   |
| 5.12.7  | 2         | 0.55%   |
| 5.10.14 | 2         | 0.55%   |
| 4.19.0  | 2         | 0.55%   |
| 3.10.0  | 2         | 0.55%   |
| 6.1.6   | 1         | 0.27%   |
| 6.1.3   | 1         | 0.27%   |
| 6.1.0   | 1         | 0.27%   |
| 5.9.9   | 1         | 0.27%   |
| 5.9.16  | 1         | 0.27%   |
| 5.9.15  | 1         | 0.27%   |
| 5.9.11  | 1         | 0.27%   |
| 5.9.10  | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 80        | 22.28%  |
| 5.15    | 55        | 15.32%  |
| 5.13    | 25        | 6.96%   |
| 5.8     | 24        | 6.69%   |
| 5.11    | 23        | 6.41%   |
| 5.10    | 18        | 5.01%   |
| 4.18    | 13        | 3.62%   |
| 5.3     | 12        | 3.34%   |
| 5.0     | 12        | 3.34%   |
| 6.0     | 11        | 3.06%   |
| 5.18    | 11        | 3.06%   |
| 4.15    | 11        | 3.06%   |
| 5.9     | 10        | 2.79%   |
| 5.16    | 10        | 2.79%   |
| 5.19    | 8         | 2.23%   |
| 6.1     | 7         | 1.95%   |
| 5.12    | 6         | 1.67%   |
| 5.17    | 5         | 1.39%   |
| 5.6     | 4         | 1.11%   |
| 5.14    | 3         | 0.84%   |
| 4.19    | 3         | 0.84%   |
| 5.5     | 2         | 0.56%   |
| 4.16    | 2         | 0.56%   |
| 3.10    | 2         | 0.56%   |
| 5.7     | 1         | 0.28%   |
| 4.4     | 1         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 324       | 97.89%  |
| aarch64 | 3         | 0.91%   |
| i686    | 2         | 0.6%    |
| armv7l  | 2         | 0.6%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 187       | 54.36%  |
| KDE5            | 47        | 13.66%  |
| Unknown         | 45        | 13.08%  |
| X-Cinnamon      | 20        | 5.81%   |
| XFCE            | 11        | 3.2%    |
| KDE             | 6         | 1.74%   |
| Cinnamon        | 6         | 1.74%   |
| LXQt            | 5         | 1.45%   |
| Unity           | 3         | 0.87%   |
| Pantheon        | 3         | 0.87%   |
| i3              | 3         | 0.87%   |
| MATE            | 2         | 0.58%   |
| GNOME Classic   | 2         | 0.58%   |
| Budgie          | 2         | 0.58%   |
| KDE4            | 1         | 0.29%   |
| GNOME Flashback | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 262       | 77.06%  |
| Wayland | 42        | 12.35%  |
| Unknown | 23        | 6.76%   |
| Tty     | 13        | 3.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 171       | 50%     |
| GDM     | 65        | 19.01%  |
| SDDM    | 42        | 12.28%  |
| GDM3    | 39        | 11.4%   |
| LightDM | 19        | 5.56%   |
| TDM     | 5         | 1.46%   |
| KDM     | 1         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_SG   | 137       | 40.77%  |
| en_US   | 125       | 37.2%   |
| Unknown | 26        | 7.74%   |
| C       | 12        | 3.57%   |
| zh_CN   | 8         | 2.38%   |
| en_IN   | 7         | 2.08%   |
| en_GB   | 5         | 1.49%   |
| en_AU   | 5         | 1.49%   |
| de_DE   | 5         | 1.49%   |
| en_PH   | 3         | 0.89%   |
| ru_UA   | 1         | 0.3%    |
| fr_FR   | 1         | 0.3%    |
| en_IE   | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 219       | 65.77%  |
| BIOS | 114       | 34.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 273       | 81.49%  |
| Btrfs   | 26        | 7.76%   |
| Overlay | 16        | 4.78%   |
| Unknown | 10        | 2.99%   |
| Xfs     | 8         | 2.39%   |
| Zfs     | 2         | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 171       | 51.2%   |
| GPT     | 145       | 43.41%  |
| MBR     | 18        | 5.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 291       | 85.84%  |
| Yes       | 48        | 14.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 221       | 66.37%  |
| Yes       | 112       | 33.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 61        | 18.43%  |
| ASUSTek Computer        | 58        | 17.52%  |
| Dell                    | 56        | 16.92%  |
| Acer                    | 28        | 8.46%   |
| Hewlett-Packard         | 23        | 6.95%   |
| MSI                     | 17        | 5.14%   |
| Gigabyte Technology     | 17        | 5.14%   |
| ASRock                  | 12        | 3.63%   |
| Apple                   | 12        | 3.63%   |
| Foxconn                 | 5         | 1.51%   |
| Sony                    | 4         | 1.21%   |
| Raspberry Pi Foundation | 4         | 1.21%   |
| Intel                   | 4         | 1.21%   |
| Microsoft               | 3         | 0.91%   |
| congatec                | 3         | 0.91%   |
| Toshiba                 | 2         | 0.6%    |
| Timi                    | 2         | 0.6%    |
| Samsung Electronics     | 2         | 0.6%    |
| Fujitsu                 | 2         | 0.6%    |
| AMI                     | 2         | 0.6%    |
| Aftershock              | 2         | 0.6%    |
| Unknown                 | 2         | 0.6%    |
| Razer                   | 1         | 0.3%    |
| Notebook                | 1         | 0.3%    |
| MECHREVO                | 1         | 0.3%    |
| LattePanda              | 1         | 0.3%    |
| INET                    | 1         | 0.3%    |
| HUAWEI                  | 1         | 0.3%    |
| Google                  | 1         | 0.3%    |
| ECS                     | 1         | 0.3%    |
| COPELION INTERNATIONAL  | 1         | 0.3%    |
| Biostar                 | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 5         | 1.51%   |
| MSI MS-7C84                                           | 3         | 0.91%   |
| Gigabyte X570 AORUS PRO WIFI                          | 3         | 0.91%   |
| Foxconn Pro 3330 MT                                   | 3         | 0.91%   |
| congatec conga-MA5 B.2                                | 3         | 0.91%   |
| RPi Raspberry Pi 4 Model B Rev 1.4                    | 2         | 0.6%    |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 2         | 0.6%    |
| Lenovo ThinkPad X220 42911H8                          | 2         | 0.6%    |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                      | 2         | 0.6%    |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 0.6%    |
| Intel NUC11PAHi7                                      | 2         | 0.6%    |
| HP Compaq 6510b                                       | 2         | 0.6%    |
| Gigabyte B550I AORUS PRO AX                           | 2         | 0.6%    |
| Foxconn Kangaroo Mobile Desktop                       | 2         | 0.6%    |
| Dell OptiPlex 990                                     | 2         | 0.6%    |
| Dell OptiPlex 9020                                    | 2         | 0.6%    |
| Dell Latitude 3320                                    | 2         | 0.6%    |
| Dell Latitude 3120                                    | 2         | 0.6%    |
| Dell Inspiron 15 5510                                 | 2         | 0.6%    |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC              | 2         | 0.6%    |
| ASUS T300LA                                           | 2         | 0.6%    |
| ASUS ROG STRIX B550-I GAMING                          | 2         | 0.6%    |
| ASUS K45VM                                            | 2         | 0.6%    |
| Apple MacBookPro8,1                                   | 2         | 0.6%    |
| Apple iMac19,1                                        | 2         | 0.6%    |
| Acer ConceptD CN715-71                                | 2         | 0.6%    |
| Unknown                                               | 2         | 0.6%    |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.3%    |
| Toshiba PORTEGE R930                                  | 1         | 0.3%    |
| Timi TM1701                                           | 1         | 0.3%    |
| Timi Redmi Book Pro 14 2022                           | 1         | 0.3%    |
| Sony VPCSB36FG                                        | 1         | 0.3%    |
| Sony VPCCA15FG                                        | 1         | 0.3%    |
| Sony VGN-CR32G_W                                      | 1         | 0.3%    |
| Sony SVF1531V8CW                                      | 1         | 0.3%    |
| Samsung RF510/RF410/RF710                             | 1         | 0.3%    |
| Samsung 305U1A                                        | 1         | 0.3%    |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.3%    |
| Notebook P65_P67SE                                    | 1         | 0.3%    |
| MSI Pulse GL66 11UGK                                  | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 32        | 9.67%   |
| Dell Inspiron       | 15        | 4.53%   |
| Dell Latitude       | 13        | 3.93%   |
| Acer Aspire         | 13        | 3.93%   |
| ASUS VivoBook       | 10        | 3.02%   |
| Dell OptiPlex       | 9         | 2.72%   |
| Lenovo IdeaPad      | 8         | 2.42%   |
| Dell XPS            | 8         | 2.42%   |
| HP Pavilion         | 7         | 2.11%   |
| Dell Precision      | 7         | 2.11%   |
| Acer Swift          | 7         | 2.11%   |
| Lenovo Legion       | 6         | 1.81%   |
| ASUS ROG            | 5         | 1.51%   |
| ASUS All            | 5         | 1.51%   |
| RPi Raspberry       | 4         | 1.21%   |
| Lenovo Yoga         | 4         | 1.21%   |
| ASUS ZenBook        | 4         | 1.21%   |
| MSI MS-7C84         | 3         | 0.91%   |
| Microsoft Surface   | 3         | 0.91%   |
| Lenovo ThinkCentre  | 3         | 0.91%   |
| HP ZBook            | 3         | 0.91%   |
| HP ENVY             | 3         | 0.91%   |
| HP EliteBook        | 3         | 0.91%   |
| Gigabyte X570       | 3         | 0.91%   |
| Foxconn Pro         | 3         | 0.91%   |
| congatec conga-MA5  | 3         | 0.91%   |
| ASUS TUF            | 3         | 0.91%   |
| Toshiba PORTEGE     | 2         | 0.6%    |
| Lenovo ThinkStation | 2         | 0.6%    |
| Intel NUC11PAHi7    | 2         | 0.6%    |
| HP ProDesk          | 2         | 0.6%    |
| HP Compaq           | 2         | 0.6%    |
| Gigabyte B550I      | 2         | 0.6%    |
| Gigabyte B365M      | 2         | 0.6%    |
| Fujitsu LIFEBOOK    | 2         | 0.6%    |
| Foxconn Kangaroo    | 2         | 0.6%    |
| ASUS T300LA         | 2         | 0.6%    |
| ASUS K45VM          | 2         | 0.6%    |
| ASUS ASUS           | 2         | 0.6%    |
| Apple MacBookPro8   | 2         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 44        | 13.29%  |
| 2020    | 43        | 12.99%  |
| 2018    | 38        | 11.48%  |
| 2021    | 34        | 10.27%  |
| 2013    | 23        | 6.95%   |
| 2011    | 21        | 6.34%   |
| 2012    | 19        | 5.74%   |
| 2016    | 17        | 5.14%   |
| 2017    | 16        | 4.83%   |
| 2015    | 16        | 4.83%   |
| 2014    | 16        | 4.83%   |
| 2010    | 12        | 3.63%   |
| 2022    | 11        | 3.32%   |
| 2008    | 7         | 2.11%   |
| 2007    | 7         | 2.11%   |
| Unknown | 4         | 1.21%   |
| 2009    | 3         | 0.91%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 195       | 58.91%  |
| Desktop        | 99        | 29.91%  |
| Convertible    | 9         | 2.72%   |
| Mini pc        | 9         | 2.72%   |
| All in one     | 7         | 2.11%   |
| System on chip | 5         | 1.51%   |
| Tablet         | 5         | 1.51%   |
| Server         | 2         | 0.6%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 291       | 87.39%  |
| Enabled  | 42        | 12.61%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 330       | 99.7%   |
| Yes  | 1         | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 87        | 25.89%  |
| 4.01-8.0        | 75        | 22.32%  |
| 8.01-16.0       | 58        | 17.26%  |
| 3.01-4.0        | 45        | 13.39%  |
| 32.01-64.0      | 43        | 12.8%   |
| 64.01-256.0     | 10        | 2.98%   |
| 1.01-2.0        | 8         | 2.38%   |
| 24.01-32.0      | 7         | 2.08%   |
| 2.01-3.0        | 2         | 0.6%    |
| More than 256.0 | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 101       | 27.82%  |
| 2.01-3.0   | 87        | 23.97%  |
| 4.01-8.0   | 65        | 17.91%  |
| 3.01-4.0   | 62        | 17.08%  |
| 8.01-16.0  | 23        | 6.34%   |
| 0.51-1.0   | 17        | 4.68%   |
| 0.01-0.5   | 5         | 1.38%   |
| 16.01-24.0 | 3         | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 207       | 61.24%  |
| 2      | 83        | 24.56%  |
| 3      | 28        | 8.28%   |
| 4      | 14        | 4.14%   |
| 5      | 3         | 0.89%   |
| 0      | 3         | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 251       | 75.6%   |
| Yes       | 81        | 24.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 74.77%  |
| No        | 84        | 25.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 273       | 81.98%  |
| No        | 60        | 18.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 226       | 67.87%  |
| No        | 107       | 32.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Singapore | 331       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Singapore            | 313       | 94.56%  |
| Jurong West          | 7         | 2.11%   |
| Kampong Pasir Ris    | 5         | 1.51%   |
| Queenstown Estate    | 2         | 0.6%    |
| Yio Chu Kang         | 1         | 0.3%    |
| Sembawang Estate     | 1         | 0.3%    |
| Kampong Ulu Jurong   | 1         | 0.3%    |
| Bukit Batok New Town | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 92        | 130    | 19.21%  |
| WDC                         | 57        | 90     | 11.9%   |
| Seagate                     | 55        | 65     | 11.48%  |
| Toshiba                     | 39        | 50     | 8.14%   |
| SanDisk                     | 31        | 37     | 6.47%   |
| Unknown                     | 21        | 24     | 4.38%   |
| SK hynix                    | 21        | 23     | 4.38%   |
| Intel                       | 13        | 15     | 2.71%   |
| Hitachi                     | 13        | 14     | 2.71%   |
| Kingston                    | 12        | 15     | 2.51%   |
| HGST                        | 12        | 19     | 2.51%   |
| Micron Technology           | 11        | 13     | 2.3%    |
| Crucial                     | 10        | 11     | 2.09%   |
| Phison                      | 6         | 8      | 1.25%   |
| JMicron Technology          | 6         | 8      | 1.25%   |
| KIOXIA                      | 5         | 5      | 1.04%   |
| Hewlett-Packard             | 5         | 6      | 1.04%   |
| Apple                       | 5         | 6      | 1.04%   |
| Lexar                       | 4         | 4      | 0.84%   |
| A-DATA Technology           | 4         | 4      | 0.84%   |
| Unknown                     | 4         | 4      | 0.84%   |
| Transcend                   | 3         | 4      | 0.63%   |
| Lenovo                      | 3         | 3      | 0.63%   |
| China                       | 3         | 3      | 0.63%   |
| Silicon Motion              | 2         | 3      | 0.42%   |
| Phison Electronics          | 2         | 2      | 0.42%   |
| Patriot                     | 2         | 2      | 0.42%   |
| OCZ                         | 2         | 2      | 0.42%   |
| Micron/Crucial Technology   | 2         | 2      | 0.42%   |
| LITEON                      | 2         | 3      | 0.42%   |
| KLEVV                       | 2         | 2      | 0.42%   |
| External                    | 2         | 2      | 0.42%   |
| Yangtze Memory Technologies | 1         | 1      | 0.21%   |
| Vaseky                      | 1         | 1      | 0.21%   |
| USB30                       | 1         | 1      | 0.21%   |
| UMIS                        | 1         | 1      | 0.21%   |
| TO Exter                    | 1         | 1      | 0.21%   |
| Teclast                     | 1         | 1      | 0.21%   |
| Team                        | 1         | 1      | 0.21%   |
| SPCC                        | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB                 | 7         | 1.37%   |
| Seagate ST1000LM035-1RK172 1TB         | 7         | 1.37%   |
| Samsung SSD 860 EVO 500GB              | 6         | 1.17%   |
| Samsung NVMe SSD Drive 1024GB          | 6         | 1.17%   |
| Unknown MMC Card  32GB                 | 5         | 0.98%   |
| Toshiba DT01ACA200 2TB                 | 5         | 0.98%   |
| Samsung SSD 850 EVO 250GB              | 5         | 0.98%   |
| JMicron Generic 500GB                  | 5         | 0.98%   |
| Unknown MMC Card  64GB                 | 4         | 0.78%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 0.78%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB         | 4         | 0.78%   |
| Samsung SSD 970 EVO Plus 500GB         | 4         | 0.78%   |
| Crucial CT500MX500SSD1 500GB           | 4         | 0.78%   |
| Unknown                                | 4         | 0.78%   |
| WDC WD10EZEX-00BN5A0 1TB               | 3         | 0.59%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB   | 3         | 0.59%   |
| Seagate Expansion 240GB                | 3         | 0.59%   |
| SanDisk NVMe SSD Drive 512GB           | 3         | 0.59%   |
| Samsung SSD 850 EVO 500GB              | 3         | 0.59%   |
| Samsung SSD 840 EVO 250GB              | 3         | 0.59%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 0.59%   |
| Samsung NVMe SSD Drive 500GB           | 3         | 0.59%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.59%   |
| HGST HTS545050A7E380 500GB             | 3         | 0.59%   |
| WDC WDS500G2X0C-00L350 500GB           | 2         | 0.39%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 2         | 0.39%   |
| WDC WDS100T2X0C-00L350 1TB             | 2         | 0.39%   |
| WDC WD7500BPVT-80HXZT3 752GB           | 2         | 0.39%   |
| WDC WD6400AAKS-22A7B2 640GB            | 2         | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.39%   |
| WDC WD10SPZX-21Z10T0 1TB               | 2         | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2         | 0.39%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 2         | 0.39%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB     | 2         | 0.39%   |
| WDC PC SN720 SED SDAQNTW-1T00 1TB      | 2         | 0.39%   |
| Toshiba NVMe SSD Drive 256GB           | 2         | 0.39%   |
| Toshiba MK5055GSX 500GB                | 2         | 0.39%   |
| SK hynix SC311 SATA 128GB SSD          | 2         | 0.39%   |
| SK hynix NVMe SSD Drive 256GB          | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 63     | 34.42%  |
| WDC                 | 38        | 52     | 24.68%  |
| Toshiba             | 29        | 38     | 18.83%  |
| Hitachi             | 13        | 14     | 8.44%   |
| HGST                | 12        | 19     | 7.79%   |
| Samsung Electronics | 3         | 5      | 1.95%   |
| Apple               | 2         | 2      | 1.3%    |
| SAGE                | 1         | 1      | 0.65%   |
| Maxtor              | 1         | 1      | 0.65%   |
| KESU                | 1         | 1      | 0.65%   |
| Fujitsu             | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 51        | 72     | 34.69%  |
| SanDisk             | 20        | 24     | 13.61%  |
| Kingston            | 9         | 12     | 6.12%   |
| Crucial             | 7         | 8      | 4.76%   |
| JMicron Technology  | 5         | 7      | 3.4%    |
| WDC                 | 4         | 5      | 2.72%   |
| SK hynix            | 4         | 4      | 2.72%   |
| Micron Technology   | 4         | 6      | 2.72%   |
| Hewlett-Packard     | 4         | 5      | 2.72%   |
| Transcend           | 3         | 4      | 2.04%   |
| China               | 3         | 3      | 2.04%   |
| Apple               | 3         | 3      | 2.04%   |
| A-DATA Technology   | 3         | 3      | 2.04%   |
| Patriot             | 2         | 2      | 1.36%   |
| OCZ                 | 2         | 2      | 1.36%   |
| LITEON              | 2         | 3      | 1.36%   |
| Lexar               | 2         | 2      | 1.36%   |
| Vaseky              | 1         | 1      | 0.68%   |
| USB30               | 1         | 1      | 0.68%   |
| Unknown             | 1         | 1      | 0.68%   |
| Toshiba             | 1         | 1      | 0.68%   |
| TO Exter            | 1         | 1      | 0.68%   |
| Teclast             | 1         | 1      | 0.68%   |
| SPCC                | 1         | 1      | 0.68%   |
| Plextor             | 1         | 1      | 0.68%   |
| Pioneer             | 1         | 1      | 0.68%   |
| Netac               | 1         | 1      | 0.68%   |
| MidasForce          | 1         | 1      | 0.68%   |
| KLEVV               | 1         | 1      | 0.68%   |
| Kingmax             | 1         | 1      | 0.68%   |
| Intel               | 1         | 1      | 0.68%   |
| GAMER               | 1         | 1      | 0.68%   |
| GALAX               | 1         | 1      | 0.68%   |
| CT1000MX            | 1         | 2      | 0.68%   |
| Apacer              | 1         | 1      | 0.68%   |
| Unknown             | 1         | 1      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 146       | 202    | 33.72%  |
| HDD     | 136       | 197    | 31.41%  |
| SSD     | 127       | 185    | 29.33%  |
| MMC     | 20        | 23     | 4.62%   |
| Unknown | 4         | 4      | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 205       | 357    | 51.51%  |
| NVMe | 146       | 196    | 36.68%  |
| SAS  | 27        | 35     | 6.78%   |
| MMC  | 20        | 23     | 5.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 148       | 217    | 54.41%  |
| 0.51-1.0   | 83        | 116    | 30.51%  |
| 1.01-2.0   | 22        | 27     | 8.09%   |
| 4.01-10.0  | 9         | 11     | 3.31%   |
| 3.01-4.0   | 7         | 8      | 2.57%   |
| 2.01-3.0   | 3         | 3      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 91        | 26%     |
| 251-500        | 66        | 18.86%  |
| 501-1000       | 61        | 17.43%  |
| 1001-2000      | 30        | 8.57%   |
| 1-20           | 25        | 7.14%   |
| More than 3000 | 21        | 6%      |
| 51-100         | 18        | 5.14%   |
| 21-50          | 15        | 4.29%   |
| Unknown        | 12        | 3.43%   |
| 2001-3000      | 11        | 3.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 132       | 37.61%  |
| 21-50          | 60        | 17.09%  |
| 101-250        | 51        | 14.53%  |
| 251-500        | 33        | 9.4%    |
| 51-100         | 30        | 8.55%   |
| 501-1000       | 16        | 4.56%   |
| Unknown        | 12        | 3.42%   |
| 1001-2000      | 10        | 2.85%   |
| More than 3000 | 4         | 1.14%   |
| 2001-3000      | 3         | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB        | 2         | 3      | 10%     |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 5%      |
| WDC WD5000BPVT-16HXZT1 500GB       | 1         | 1      | 5%      |
| WDC WD5000AAKS-22V1A0 500GB        | 1         | 1      | 5%      |
| WDC WD50 EZRX-00MVLB1 5TB          | 1         | 1      | 5%      |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 2      | 5%      |
| WDC WD10EZEX-60M2NA0 1TB           | 1         | 1      | 5%      |
| WDC WD1002FAEX-00Z3A0 1TB          | 1         | 1      | 5%      |
| WDC WD1002FAEX-00Y9A0 1TB          | 1         | 1      | 5%      |
| Toshiba DT01ACA100 1TB             | 1         | 1      | 5%      |
| Teclast 480GB A800 SSD             | 1         | 1      | 5%      |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 5%      |
| Seagate ST1000LM024 HN-M 1TB       | 1         | 1      | 5%      |
| Hitachi HTS545032B9A300 320GB      | 1         | 1      | 5%      |
| Hitachi HTS541010A9E680 1TB        | 1         | 1      | 5%      |
| Hitachi HDS721010CLA632 1TB        | 1         | 1      | 5%      |
| HGST HTS545050A7E380 500GB         | 1         | 1      | 5%      |
| Crucial CT120M500SSD1 120GB        | 1         | 1      | 5%      |
| China SSD 128GB                    | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 10        | 12     | 50%     |
| Hitachi | 3         | 3      | 15%     |
| Seagate | 2         | 2      | 10%     |
| Toshiba | 1         | 1      | 5%      |
| Teclast | 1         | 1      | 5%      |
| HGST    | 1         | 1      | 5%      |
| Crucial | 1         | 1      | 5%      |
| China   | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 10        | 12     | 58.82%  |
| Hitachi | 3         | 3      | 17.65%  |
| Seagate | 2         | 2      | 11.76%  |
| Toshiba | 1         | 1      | 5.88%   |
| HGST    | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 19     | 85%     |
| SSD  | 3         | 3      | 15%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| JMicron Technology Tech 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| JMicron Technology | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 201       | 342    | 55.52%  |
| Works    | 140       | 246    | 38.67%  |
| Malfunc  | 20        | 22     | 5.52%   |
| Failed   | 1         | 1      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 212       | 49.53%  |
| AMD                          | 52        | 12.15%  |
| Samsung Electronics          | 49        | 11.45%  |
| SanDisk                      | 28        | 6.54%   |
| SK hynix                     | 17        | 3.97%   |
| Toshiba America Info Systems | 8         | 1.87%   |
| Phison Electronics           | 8         | 1.87%   |
| KIOXIA                       | 8         | 1.87%   |
| Micron Technology            | 7         | 1.64%   |
| ASMedia Technology           | 6         | 1.4%    |
| Silicon Motion               | 5         | 1.17%   |
| Micron/Crucial Technology    | 5         | 1.17%   |
| Kingston Technology Company  | 4         | 0.93%   |
| Shenzhen Longsys Electronics | 3         | 0.7%    |
| Nvidia                       | 3         | 0.7%    |
| Lenovo                       | 3         | 0.7%    |
| Marvell Technology Group     | 2         | 0.47%   |
| ADATA Technology             | 2         | 0.47%   |
| Yangtze Memory Technologies  | 1         | 0.23%   |
| VIA Technologies             | 1         | 0.23%   |
| Union Memory (Shenzhen)      | 1         | 0.23%   |
| Seagate Technology           | 1         | 0.23%   |
| JMicron Technology           | 1         | 0.23%   |
| Broadcom / LSI               | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 38        | 8.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 29        | 6.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 3.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 3.02%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 2.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 2.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 2.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 1.73%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 7         | 1.51%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 1.51%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 7         | 1.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.51%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 1.51%   |
| Micron Non-Volatile memory controller                                          | 7         | 1.51%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 7         | 1.51%   |
| Intel SATA Controller [RAID mode]                                              | 7         | 1.51%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 1.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 1.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.51%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 1.51%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.3%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 6         | 1.3%    |
| SK hynix Non-Volatile memory controller                                        | 5         | 1.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.08%   |
| SanDisk Non-Volatile memory controller                                         | 5         | 1.08%   |
| Intel SSD 660P Series                                                          | 5         | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.08%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 4         | 0.86%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 4         | 0.86%   |
| Phison E12 NVMe Controller                                                     | 4         | 0.86%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 4         | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 0.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 218       | 51.42%  |
| NVMe | 147       | 34.67%  |
| RAID | 34        | 8.02%   |
| IDE  | 24        | 5.66%   |
| SAS  | 1         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 257       | 77.64%  |
| AMD    | 69        | 20.85%  |
| ARM    | 5         | 1.51%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 3.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 2.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 2.11%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 2.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.51%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 1.51%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 5         | 1.51%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.21%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.21%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 4         | 1.21%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 4         | 1.21%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.21%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.91%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.91%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 0.91%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 0.91%   |
| ARM Processor                                 | 3         | 0.91%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.91%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.91%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 0.6%    |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.6%    |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.6%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.6%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.6%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.6%    |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.6%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.6%    |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.6%    |
| Intel Core i5-4690 CPU @ 3.50GHz              | 2         | 0.6%    |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 0.6%    |
| Intel Core i5-3570 CPU @ 3.40GHz              | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 81        | 24.47%  |
| Intel Core i5           | 75        | 22.66%  |
| Other                   | 34        | 10.27%  |
| AMD Ryzen 5             | 23        | 6.95%   |
| AMD Ryzen 7             | 19        | 5.74%   |
| Intel Xeon              | 11        | 3.32%   |
| Intel Celeron           | 11        | 3.32%   |
| Intel Core i3           | 10        | 3.02%   |
| Intel Core 2 Duo        | 10        | 3.02%   |
| Intel Atom              | 6         | 1.81%   |
| Intel Pentium Silver    | 4         | 1.21%   |
| Intel Core i9           | 4         | 1.21%   |
| AMD Ryzen 9             | 4         | 1.21%   |
| Intel Core m3           | 3         | 0.91%   |
| AMD Ryzen 7 PRO         | 3         | 0.91%   |
| Intel Pentium Dual      | 2         | 0.6%    |
| Intel Pentium           | 2         | 0.6%    |
| ARM BCM                 | 2         | 0.6%    |
| AMD Ryzen Threadripper  | 2         | 0.6%    |
| AMD Ryzen 5 PRO         | 2         | 0.6%    |
| AMD Ryzen 3             | 2         | 0.6%    |
| AMD PRO A10             | 2         | 0.6%    |
| AMD FX                  | 2         | 0.6%    |
| AMD Athlon              | 2         | 0.6%    |
| AMD A10                 | 2         | 0.6%    |
| Intel Xeon Silver       | 1         | 0.3%    |
| Intel Pentium Gold      | 1         | 0.3%    |
| Intel Pentium Dual-Core | 1         | 0.3%    |
| Intel Pentium 4         | 1         | 0.3%    |
| Intel Core m7           | 1         | 0.3%    |
| Intel Core 2 Quad       | 1         | 0.3%    |
| Intel Core 2            | 1         | 0.3%    |
| AMD Turion 64 X2 Mobile | 1         | 0.3%    |
| AMD Phenom II X6        | 1         | 0.3%    |
| AMD Phenom II X4        | 1         | 0.3%    |
| AMD E1                  | 1         | 0.3%    |
| AMD E                   | 1         | 0.3%    |
| AMD A6                  | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 138       | 41.69%  |
| 2      | 96        | 29%     |
| 6      | 42        | 12.69%  |
| 8      | 35        | 10.57%  |
| 12     | 5         | 1.51%   |
| 16     | 4         | 1.21%   |
| 10     | 4         | 1.21%   |
| 14     | 3         | 0.91%   |
| 1      | 3         | 0.91%   |
| 3      | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 330       | 99.7%   |
| 2      | 1         | 0.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 242       | 72.67%  |
| 1      | 91        | 27.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 324       | 97.89%  |
| Unknown        | 5         | 1.51%   |
| 32-bit         | 2         | 0.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 17.16%  |
| 0x306a9    | 20        | 5.92%   |
| 0x906ea    | 18        | 5.33%   |
| 0x206a7    | 17        | 5.03%   |
| 0x806ea    | 15        | 4.44%   |
| 0x306c3    | 14        | 4.14%   |
| 0x806ec    | 12        | 3.55%   |
| 0x806c1    | 11        | 3.25%   |
| 0x506e3    | 10        | 2.96%   |
| 0x0a50000c | 9         | 2.66%   |
| 0x20655    | 8         | 2.37%   |
| 0x806eb    | 7         | 2.07%   |
| 0x40651    | 7         | 2.07%   |
| 0x406e3    | 6         | 1.78%   |
| 0x806e9    | 5         | 1.48%   |
| 0x6fd      | 5         | 1.48%   |
| 0x306d4    | 5         | 1.48%   |
| 0x1067a    | 5         | 1.48%   |
| 0x08108109 | 5         | 1.48%   |
| 0x906e9    | 4         | 1.18%   |
| 0x806d1    | 4         | 1.18%   |
| 0x08701021 | 4         | 1.18%   |
| 0x08600106 | 4         | 1.18%   |
| 0xa0652    | 3         | 0.89%   |
| 0x906ed    | 3         | 0.89%   |
| 0x90672    | 3         | 0.89%   |
| 0x806c2    | 3         | 0.89%   |
| 0x506ca    | 3         | 0.89%   |
| 0x50654    | 3         | 0.89%   |
| 0x406c3    | 3         | 0.89%   |
| 0x0a201016 | 3         | 0.89%   |
| 0x08701013 | 3         | 0.89%   |
| 0x08108102 | 3         | 0.89%   |
| 0x06003106 | 3         | 0.89%   |
| 0xa0660    | 2         | 0.59%   |
| 0x906c0    | 2         | 0.59%   |
| 0x906a3    | 2         | 0.59%   |
| 0x706a8    | 2         | 0.59%   |
| 0x706a1    | 2         | 0.59%   |
| 0x6fb      | 2         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 75        | 22.66%  |
| Haswell          | 26        | 7.85%   |
| IvyBridge        | 24        | 7.25%   |
| SandyBridge      | 21        | 6.34%   |
| Skylake          | 20        | 6.04%   |
| Zen 3            | 18        | 5.44%   |
| Zen 2            | 17        | 5.14%   |
| TigerLake        | 17        | 5.14%   |
| Unknown          | 16        | 4.83%   |
| Zen+             | 12        | 3.63%   |
| Westmere         | 8         | 2.42%   |
| Core             | 8         | 2.42%   |
| Silvermont       | 7         | 2.11%   |
| Penryn           | 7         | 2.11%   |
| Icelake          | 7         | 2.11%   |
| CometLake        | 7         | 2.11%   |
| Broadwell        | 7         | 2.11%   |
| Zen              | 4         | 1.21%   |
| Goldmont plus    | 4         | 1.21%   |
| Goldmont         | 4         | 1.21%   |
| Alderlake Hybrid | 4         | 1.21%   |
| Steamroller      | 3         | 0.91%   |
| K10              | 3         | 0.91%   |
| Tremont          | 2         | 0.6%    |
| Piledriver       | 2         | 0.6%    |
| Excavator        | 2         | 0.6%    |
| Bonnell          | 2         | 0.6%    |
| NetBurst         | 1         | 0.3%    |
| K8 Hammer        | 1         | 0.3%    |
| Jaguar           | 1         | 0.3%    |
| Bobcat           | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 213       | 50.96%  |
| Nvidia            | 128       | 30.62%  |
| AMD               | 75        | 17.94%  |
| ASPEED Technology | 2         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 19        | 4.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 4.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 3.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 2.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 2.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.33%   |
| Intel HD Graphics 530                                                                    | 8         | 1.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.86%   |
| AMD Renoir                                                                               | 8         | 1.86%   |
| Intel HD Graphics 620                                                                    | 7         | 1.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 1.63%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 1.4%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 1.17%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 5         | 1.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.17%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 4         | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.93%   |
| Intel HD Graphics 5500                                                                   | 4         | 0.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.93%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.7%    |
| Nvidia GP108BM [GeForce MX250]                                                           | 3         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 0.7%    |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.7%    |
| Nvidia GK107 [GeForce GT 640]                                                            | 3         | 0.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.7%    |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.7%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.7%    |
| Intel HD Graphics 630                                                                    | 3         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 135       | 40.3%   |
| Intel + Nvidia  | 62        | 18.51%  |
| 1 x Nvidia      | 54        | 16.12%  |
| 1 x AMD         | 53        | 15.82%  |
| Intel + AMD     | 10        | 2.99%   |
| AMD + Nvidia    | 8         | 2.39%   |
| Other           | 5         | 1.49%   |
| 2 x Nvidia      | 3         | 0.9%    |
| 2 x AMD         | 3         | 0.9%    |
| Nvidia + ASPEED | 2         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 246       | 73%     |
| Proprietary | 77        | 22.85%  |
| Unknown     | 14        | 4.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 197       | 57.27%  |
| 1.01-2.0   | 48        | 13.95%  |
| 3.01-4.0   | 27        | 7.85%   |
| 0.01-0.5   | 23        | 6.69%   |
| 7.01-8.0   | 15        | 4.36%   |
| 0.51-1.0   | 15        | 4.36%   |
| 8.01-16.0  | 11        | 3.2%    |
| 5.01-6.0   | 7         | 2.03%   |
| 2.01-3.0   | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 66        | 18.7%   |
| Dell                 | 53        | 15.01%  |
| Samsung Electronics  | 38        | 10.76%  |
| LG Display           | 30        | 8.5%    |
| BOE                  | 29        | 8.22%   |
| Chimei Innolux       | 19        | 5.38%   |
| Goldstar             | 13        | 3.68%   |
| Acer                 | 12        | 3.4%    |
| Apple                | 11        | 3.12%   |
| Sharp                | 9         | 2.55%   |
| Philips              | 7         | 1.98%   |
| Hewlett-Packard      | 7         | 1.98%   |
| Lenovo               | 5         | 1.42%   |
| InfoVision           | 4         | 1.13%   |
| CSO                  | 4         | 1.13%   |
| AOC                  | 4         | 1.13%   |
| PRISM+               | 3         | 0.85%   |
| PANDA                | 3         | 0.85%   |
| Denver               | 3         | 0.85%   |
| ASUSTek Computer     | 3         | 0.85%   |
| ViewSonic            | 2         | 0.57%   |
| Sony                 | 2         | 0.57%   |
| LG Philips           | 2         | 0.57%   |
| Lenovo Group Limited | 2         | 0.57%   |
| CVT                  | 2         | 0.57%   |
| Ancor Communications | 2         | 0.57%   |
| Wacom                | 1         | 0.28%   |
| Unknown              | 1         | 0.28%   |
| Toshiba              | 1         | 0.28%   |
| Tianma XM            | 1         | 0.28%   |
| SGT                  | 1         | 0.28%   |
| SAC                  | 1         | 0.28%   |
| RTK                  | 1         | 0.28%   |
| Pixio                | 1         | 0.28%   |
| MSI                  | 1         | 0.28%   |
| Mi                   | 1         | 0.28%   |
| HPN                  | 1         | 0.28%   |
| EXP                  | 1         | 0.28%   |
| CPT                  | 1         | 0.28%   |
| CHR                  | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4         | 1.11%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 4         | 1.11%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.84%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.84%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                     | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 0.84%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.56%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.56%   |
| PRISM+ K3A8F HDMI INN3200 1920x1080 698x393mm 31.5-inch               | 2         | 0.56%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 2         | 0.56%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 2         | 0.56%   |
| Hewlett-Packard 23es HWP331E 1920x1080 509x286mm 23.0-inch            | 2         | 0.56%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2         | 0.56%   |
| Goldstar IPS224 GSM58D5 1920x1080 477x268mm 21.5-inch                 | 2         | 0.56%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.56%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                | 2         | 0.56%   |
| Denver GB-2461CF LHC0236 1920x1080 530x280mm 23.6-inch                | 2         | 0.56%   |
| Dell SE2417HG DELD08D 1920x1080 521x293mm 23.5-inch                   | 2         | 0.56%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                   | 2         | 0.56%   |
| Dell LCD Monitor P2217H 1920x1080                                     | 2         | 0.56%   |
| Dell E2219HN DEL2008 1920x1080 476x268mm 21.5-inch                    | 2         | 0.56%   |
| Dell E2213H DELA08F 1920x1080 477x268mm 21.5-inch                     | 2         | 0.56%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                      | 2         | 0.56%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                      | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch      | 2         | 0.56%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.56%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                 | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO3892 1920x1080 344x194mm 15.5-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO2B99 1920x1080 293x165mm 13.2-inch        | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch         | 2         | 0.56%   |
| Apple iMac APPAE25 3840x2160 597x336mm 27.0-inch                      | 2         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 174       | 51.79%  |
| 1366x768 (WXGA)    | 39        | 11.61%  |
| 3840x2160 (4K)     | 28        | 8.33%   |
| 2560x1440 (QHD)    | 25        | 7.44%   |
| 1600x900 (HD+)     | 14        | 4.17%   |
| 1280x800 (WXGA)    | 9         | 2.68%   |
| 1920x1200 (WUXGA)  | 8         | 2.38%   |
| 2560x1600          | 7         | 2.08%   |
| 1360x768           | 4         | 1.19%   |
| 3440x1440          | 3         | 0.89%   |
| 2880x1800          | 3         | 0.89%   |
| 1440x900 (WXGA+)   | 3         | 0.89%   |
| 3200x1800 (QHD+)   | 2         | 0.6%    |
| 3000x2000          | 2         | 0.6%    |
| 2736x1824          | 2         | 0.6%    |
| 2560x1080          | 2         | 0.6%    |
| 2240x1400          | 2         | 0.6%    |
| 1280x1024 (SXGA)   | 2         | 0.6%    |
| 3840x2400          | 1         | 0.3%    |
| 3840x1600          | 1         | 0.3%    |
| 3286x1080          | 1         | 0.3%    |
| 2496x1664          | 1         | 0.3%    |
| 1680x1050 (WSXGA+) | 1         | 0.3%    |
| 1024x600           | 1         | 0.3%    |
| Unknown            | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 68        | 19.37%  |
| 13      | 57        | 16.24%  |
| 14      | 43        | 12.25%  |
| 27      | 31        | 8.83%   |
| 23      | 26        | 7.41%   |
| 24      | 19        | 5.41%   |
| Unknown | 17        | 4.84%   |
| 21      | 15        | 4.27%   |
| 12      | 12        | 3.42%   |
| 20      | 10        | 2.85%   |
| 11      | 7         | 1.99%   |
| 31      | 6         | 1.71%   |
| 19      | 6         | 1.71%   |
| 18      | 6         | 1.71%   |
| 16      | 4         | 1.14%   |
| 40      | 3         | 0.85%   |
| 34      | 3         | 0.85%   |
| 32      | 3         | 0.85%   |
| 28      | 2         | 0.57%   |
| 25      | 2         | 0.57%   |
| 84      | 1         | 0.28%   |
| 55      | 1         | 0.28%   |
| 54      | 1         | 0.28%   |
| 52      | 1         | 0.28%   |
| 39      | 1         | 0.28%   |
| 37      | 1         | 0.28%   |
| 35      | 1         | 0.28%   |
| 22      | 1         | 0.28%   |
| 17      | 1         | 0.28%   |
| 10      | 1         | 0.28%   |
| 8       | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 136       | 38.75%  |
| 501-600     | 78        | 22.22%  |
| 201-300     | 53        | 15.1%   |
| 401-500     | 35        | 9.97%   |
| Unknown     | 17        | 4.84%   |
| 601-700     | 8         | 2.28%   |
| 351-400     | 7         | 1.99%   |
| 801-900     | 6         | 1.71%   |
| 701-800     | 6         | 1.71%   |
| 1001-1500   | 3         | 0.85%   |
| 1501-2000   | 1         | 0.28%   |
| 101-200     | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 254       | 79.62%  |
| 16/10   | 34        | 10.66%  |
| Unknown | 15        | 4.7%    |
| 3/2     | 6         | 1.88%   |
| 21/9    | 6         | 1.88%   |
| 5/4     | 2         | 0.63%   |
| 6/5     | 1         | 0.31%   |
| 0.62    | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 71        | 20.29%  |
| 101-110        | 68        | 19.43%  |
| 201-250        | 50        | 14.29%  |
| 301-350        | 31        | 8.86%   |
| 71-80          | 29        | 8.29%   |
| 151-200        | 21        | 6%      |
| Unknown        | 17        | 4.86%   |
| 351-500        | 14        | 4%      |
| 61-70          | 11        | 3.14%   |
| 251-300        | 9         | 2.57%   |
| 51-60          | 7         | 2%      |
| 141-150        | 5         | 1.43%   |
| 501-1000       | 5         | 1.43%   |
| More than 1000 | 4         | 1.14%   |
| 111-120        | 4         | 1.14%   |
| 41-50          | 1         | 0.29%   |
| 1-40           | 1         | 0.29%   |
| 121-130        | 1         | 0.29%   |
| 91-100         | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 110       | 32.07%  |
| 51-100        | 89        | 25.95%  |
| 101-120       | 59        | 17.2%   |
| 161-240       | 50        | 14.58%  |
| Unknown       | 17        | 4.96%   |
| More than 240 | 14        | 4.08%   |
| 1-50          | 4         | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 275       | 80.65%  |
| 2     | 47        | 13.78%  |
| 0     | 18        | 5.28%   |
| 3     | 1         | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 187       | 39.53%  |
| Realtek Semiconductor    | 143       | 30.23%  |
| Qualcomm Atheros         | 55        | 11.63%  |
| Broadcom                 | 26        | 5.5%    |
| MediaTek                 | 8         | 1.69%   |
| ASIX Electronics         | 8         | 1.69%   |
| TP-Link                  | 7         | 1.48%   |
| Marvell Technology Group | 5         | 1.06%   |
| Samsung Electronics      | 3         | 0.63%   |
| Ralink Technology        | 3         | 0.63%   |
| Broadcom Limited         | 3         | 0.63%   |
| ASUSTek Computer         | 3         | 0.63%   |
| Sierra Wireless          | 2         | 0.42%   |
| Qualcomm                 | 2         | 0.42%   |
| Lenovo                   | 2         | 0.42%   |
| Hewlett-Packard          | 2         | 0.42%   |
| STMicroelectronics       | 1         | 0.21%   |
| Ralink                   | 1         | 0.21%   |
| Nvidia                   | 1         | 0.21%   |
| MosChip Semiconductor    | 1         | 0.21%   |
| Microsoft                | 1         | 0.21%   |
| Linksys                  | 1         | 0.21%   |
| Google                   | 1         | 0.21%   |
| Fargo                    | 1         | 0.21%   |
| Exar                     | 1         | 0.21%   |
| Edimax Technology        | 1         | 0.21%   |
| Dell                     | 1         | 0.21%   |
| D-Link                   | 1         | 0.21%   |
| Aquantia                 | 1         | 0.21%   |
| Apple                    | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 15.69%  |
| Intel Wi-Fi 6 AX200                                               | 30        | 5.35%   |
| Intel Wi-Fi 6 AX201                                               | 16        | 2.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 13        | 2.32%   |
| Intel Wireless 7265                                               | 13        | 2.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 2.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 1.96%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.96%   |
| Intel I211 Gigabit Network Connection                             | 11        | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 1.6%    |
| Intel Wireless 7260                                               | 8         | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.43%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 1.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 1.25%   |
| Intel Ethernet Controller I225-V                                  | 7         | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 0.89%   |
| Intel Wireless 3165                                               | 5         | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.89%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 0.89%   |
| Intel Wireless-AC 9260                                            | 4         | 0.71%   |
| Intel Wireless 8260                                               | 4         | 0.71%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 0.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.53%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.53%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 154       | 54.04%  |
| Qualcomm Atheros         | 46        | 16.14%  |
| Realtek Semiconductor    | 31        | 10.88%  |
| Broadcom                 | 19        | 6.67%   |
| MediaTek                 | 8         | 2.81%   |
| TP-Link                  | 7         | 2.46%   |
| Ralink Technology        | 3         | 1.05%   |
| ASUSTek Computer         | 3         | 1.05%   |
| Sierra Wireless          | 2         | 0.7%    |
| Qualcomm                 | 2         | 0.7%    |
| Marvell Technology Group | 2         | 0.7%    |
| Broadcom Limited         | 2         | 0.7%    |
| Ralink                   | 1         | 0.35%   |
| Linksys                  | 1         | 0.35%   |
| Hewlett-Packard          | 1         | 0.35%   |
| Edimax Technology        | 1         | 0.35%   |
| Dell                     | 1         | 0.35%   |
| D-Link                   | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 30        | 10.49%  |
| Intel Wi-Fi 6 AX201                                                     | 16        | 5.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 4.55%   |
| Intel Wireless 7265                                                     | 13        | 4.55%   |
| Intel Wireless 8265 / 8275                                              | 11        | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 3.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 3.15%   |
| Intel Wireless 7260                                                     | 8         | 2.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 2.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 2.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.75%   |
| Intel Wireless 3165                                                     | 5         | 1.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.75%   |
| Intel Wireless-AC 9260                                                  | 4         | 1.4%    |
| Intel Wireless 8260                                                     | 4         | 1.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.05%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.05%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]         | 3         | 1.05%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.7%    |
| Sierra Wireless EM7455                                                  | 2         | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.7%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 0.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.7%    |
| Realtek 802.11ac NIC                                                    | 2         | 0.7%    |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.7%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 2         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 122       | 46.39%  |
| Intel                    | 90        | 34.22%  |
| Qualcomm Atheros         | 14        | 5.32%   |
| Broadcom                 | 13        | 4.94%   |
| ASIX Electronics         | 8         | 3.04%   |
| Samsung Electronics      | 3         | 1.14%   |
| Marvell Technology Group | 3         | 1.14%   |
| Lenovo                   | 2         | 0.76%   |
| Nvidia                   | 1         | 0.38%   |
| MosChip Semiconductor    | 1         | 0.38%   |
| Microsoft                | 1         | 0.38%   |
| Hewlett-Packard          | 1         | 0.38%   |
| Google                   | 1         | 0.38%   |
| Broadcom Limited         | 1         | 0.38%   |
| Aquantia                 | 1         | 0.38%   |
| Apple                    | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 32.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 4.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 4.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 4.04%   |
| Intel I211 Gigabit Network Connection                             | 11        | 4.04%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 2.57%   |
| Intel Ethernet Controller I225-V                                  | 7         | 2.57%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.84%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.84%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 1.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.1%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.1%    |
| Intel Ethernet Connection I217-V                                  | 3         | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.1%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.74%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.74%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.74%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.74%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.74%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.74%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.74%   |
| Intel Ethernet Connection (14) I219-LM                            | 2         | 0.74%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.74%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.74%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.74%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.74%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.74%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 273       | 52%     |
| Ethernet | 249       | 47.43%  |
| Modem    | 2         | 0.38%   |
| Unknown  | 1         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 220       | 63.22%  |
| Ethernet | 127       | 36.49%  |
| Unknown  | 1         | 0.29%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 165       | 49.7%   |
| 1     | 154       | 46.39%  |
| 0     | 7         | 2.11%   |
| 3     | 5         | 1.51%   |
| 4     | 1         | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 307       | 92.75%  |
| Yes  | 24        | 7.25%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 128       | 55.41%  |
| Qualcomm Atheros Communications | 15        | 6.49%   |
| IMC Networks                    | 14        | 6.06%   |
| Foxconn / Hon Hai               | 11        | 4.76%   |
| Cambridge Silicon Radio         | 11        | 4.76%   |
| Realtek Semiconductor           | 9         | 3.9%    |
| Lite-On Technology              | 9         | 3.9%    |
| Broadcom                        | 9         | 3.9%    |
| Apple                           | 9         | 3.9%    |
| TP-Link                         | 4         | 1.73%   |
| Marvell Semiconductor           | 2         | 0.87%   |
| USI                             | 1         | 0.43%   |
| Toshiba                         | 1         | 0.43%   |
| SIN                             | 1         | 0.43%   |
| Realtek                         | 1         | 0.43%   |
| Ralink Technology               | 1         | 0.43%   |
| MediaTek                        | 1         | 0.43%   |
| Foxconn International           | 1         | 0.43%   |
| Chicony Electronics             | 1         | 0.43%   |
| Askey Computer                  | 1         | 0.43%   |
| Alps Electric                   | 1         | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 16.81%  |
| Intel Bluetooth Device                              | 35        | 15.09%  |
| Intel AX200 Bluetooth                               | 25        | 10.78%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 21        | 9.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 4.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 3.02%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 2.16%   |
| Lite-On Bluetooth Device                            | 5         | 2.16%   |
| IMC Networks Bluetooth Radio                        | 5         | 2.16%   |
| TP-Link TPuLink UB500 Adapter                       | 4         | 1.72%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.72%   |
| Realtek Bluetooth Radio                             | 4         | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.72%   |
| IMC Networks Wireless_Device                        | 4         | 1.72%   |
| IMC Networks Bluetooth Device                       | 4         | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.72%   |
| Apple Bluetooth Host Controller                     | 4         | 1.72%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.29%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 1.29%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.29%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.86%   |
| Lite-On Bluetooth Radio                             | 2         | 0.86%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.86%   |
| Intel AX210 Bluetooth                               | 2         | 0.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.86%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.86%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.86%   |
| USI Bluetooth Device                                | 1         | 0.43%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.43%   |
| SIN Bluetooth Keyboard                              | 1         | 0.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.43%   |
| Realtek Bluetooth Radio                             | 1         | 0.43%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.43%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.43%   |
| MediaTek Wireless_Device                            | 1         | 0.43%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.43%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 247       | 56.14%  |
| Nvidia                               | 82        | 18.64%  |
| AMD                                  | 78        | 17.73%  |
| Plantronics                          | 2         | 0.45%   |
| Logitech                             | 2         | 0.45%   |
| Lenovo                               | 2         | 0.45%   |
| Kingston Technology                  | 2         | 0.45%   |
| Creative Labs                        | 2         | 0.45%   |
| C-Media Electronics                  | 2         | 0.45%   |
| Apple                                | 2         | 0.45%   |
| XMOS                                 | 1         | 0.23%   |
| Unknown                              | 1         | 0.23%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.23%   |
| SteelSeries ApS                      | 1         | 0.23%   |
| Sony                                 | 1         | 0.23%   |
| Sennheiser Communications            | 1         | 0.23%   |
| SAVITECH                             | 1         | 0.23%   |
| Samson Technologies                  | 1         | 0.23%   |
| Realtek Semiconductor                | 1         | 0.23%   |
| Razer USA                            | 1         | 0.23%   |
| NXP Semiconductors                   | 1         | 0.23%   |
| Micro Star International             | 1         | 0.23%   |
| JMTek                                | 1         | 0.23%   |
| JBL                                  | 1         | 0.23%   |
| GN Netcom                            | 1         | 0.23%   |
| FiiO Electronics Technology          | 1         | 0.23%   |
| Cooler Master                        | 1         | 0.23%   |
| Conexant Systems                     | 1         | 0.23%   |
| ASUSTek Computer                     | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 37        | 7.18%   |
| Intel Sunrise Point-LP HD Audio                                            | 34        | 6.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24        | 4.66%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 3.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 3.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 17        | 3.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 3.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 17        | 3.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 15        | 2.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 2.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 2.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 2.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 1.94%   |
| Nvidia GA104 High Definition Audio Controller                              | 9         | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.55%   |
| Intel 200 Series PCH HD Audio                                              | 8         | 1.55%   |
| Nvidia GF108 High Definition Audio Controller                              | 7         | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.36%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.36%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6         | 1.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 1.17%   |
| Nvidia TU104 HD Audio Controller                                           | 5         | 0.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 0.97%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 0.97%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 0.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.78%   |
| Nvidia GP102 HDMI Audio Controller                                         | 4         | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.78%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.78%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4         | 0.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 0.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.78%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 47        | 21.17%  |
| SK hynix                       | 46        | 20.72%  |
| Micron Technology              | 26        | 11.71%  |
| Kingston                       | 24        | 10.81%  |
| Crucial                        | 19        | 8.56%   |
| Unknown                        | 10        | 4.5%    |
| Corsair                        | 9         | 4.05%   |
| G.Skill                        | 6         | 2.7%    |
| Transcend                      | 5         | 2.25%   |
| A-DATA Technology              | 4         | 1.8%    |
| Undefi                         | 3         | 1.35%   |
| Ramaxel Technology             | 3         | 1.35%   |
| Elpida                         | 3         | 1.35%   |
| Patriot                        | 2         | 0.9%    |
| Nanya Technology               | 2         | 0.9%    |
| KLEVV                          | 2         | 0.9%    |
| Kingmax                        | 2         | 0.9%    |
| V-GeN                          | 1         | 0.45%   |
| Unknown (ABCD)                 | 1         | 0.45%   |
| Unknown (0x02BA)               | 1         | 0.45%   |
| Team                           | 1         | 0.45%   |
| Qimonda                        | 1         | 0.45%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.45%   |
| Lexar                          | 1         | 0.45%   |
| Essencore Limited              | 1         | 0.45%   |
| ASint Technology               | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 1.27%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.27%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s        | 3         | 1.27%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.85%   |
| Undefi RAM Module 2GB SODIMM DDR3 1866MT/s                       | 2         | 0.85%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 2         | 0.85%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.85%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.85%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.85%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.85%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.85%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.85%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.85%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.85%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s   | 2         | 0.85%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8192MB SODIMM DDR4 2400MT/s          | 2         | 0.85%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.85%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.85%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                   | 2         | 0.85%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 2         | 0.85%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s           | 2         | 0.85%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3200MT/s              | 2         | 0.85%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 2         | 0.85%   |
| V-GeN RAM D3R4GS16B8R 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.42%   |
| Unknown RAM Module 8GB SODIMM DDR3 800MT/s                       | 1         | 0.42%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.42%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 104       | 55.61%  |
| DDR3    | 54        | 28.88%  |
| LPDDR3  | 11        | 5.88%   |
| LPDDR4  | 9         | 4.81%   |
| SDRAM   | 3         | 1.6%    |
| DDR2    | 3         | 1.6%    |
| LPDDR5  | 1         | 0.53%   |
| DDR5    | 1         | 0.53%   |
| Unknown | 1         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 107       | 57.84%  |
| DIMM         | 54        | 29.19%  |
| Row Of Chips | 21        | 11.35%  |
| Chip         | 2         | 1.08%   |
| Unknown      | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 76        | 36.02%  |
| 4096  | 59        | 27.96%  |
| 16384 | 45        | 21.33%  |
| 2048  | 17        | 8.06%   |
| 32768 | 11        | 5.21%   |
| 1024  | 3         | 1.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 42        | 20.1%   |
| 1600    | 37        | 17.7%   |
| 2667    | 32        | 15.31%  |
| 2400    | 20        | 9.57%   |
| 2133    | 11        | 5.26%   |
| 1333    | 10        | 4.78%   |
| 4267    | 7         | 3.35%   |
| 1867    | 6         | 2.87%   |
| 3600    | 5         | 2.39%   |
| 1866    | 5         | 2.39%   |
| 1334    | 5         | 2.39%   |
| 3266    | 3         | 1.44%   |
| 2666    | 3         | 1.44%   |
| 4800    | 2         | 0.96%   |
| 3400    | 2         | 0.96%   |
| 2048    | 2         | 0.96%   |
| 1800    | 2         | 0.96%   |
| 1067    | 2         | 0.96%   |
| 800     | 2         | 0.96%   |
| 8400    | 1         | 0.48%   |
| 6400    | 1         | 0.48%   |
| 4333    | 1         | 0.48%   |
| 4199    | 1         | 0.48%   |
| 4000    | 1         | 0.48%   |
| 3666    | 1         | 0.48%   |
| 2200    | 1         | 0.48%   |
| 2134    | 1         | 0.48%   |
| 1200    | 1         | 0.48%   |
| 667     | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Samsung M2020 Series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 49        | 24.14%  |
| IMC Networks                           | 30        | 14.78%  |
| Microdia                               | 22        | 10.84%  |
| Realtek Semiconductor                  | 18        | 8.87%   |
| Sunplus Innovation Technology          | 13        | 6.4%    |
| Apple                                  | 12        | 5.91%   |
| Acer                                   | 10        | 4.93%   |
| Logitech                               | 9         | 4.43%   |
| Suyin                                  | 6         | 2.96%   |
| Samsung Electronics                    | 5         | 2.46%   |
| Lite-On Technology                     | 5         | 2.46%   |
| Syntek                                 | 4         | 1.97%   |
| Silicon Motion                         | 2         | 0.99%   |
| Ricoh                                  | 2         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 0.99%   |
| Alcor Micro                            | 2         | 0.99%   |
| Z-Star Microelectronics                | 1         | 0.49%   |
| SunplusIT                              | 1         | 0.49%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.49%   |
| Sonix Technology                       | 1         | 0.49%   |
| Quanta                                 | 1         | 0.49%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.49%   |
| OmniVision Technologies                | 1         | 0.49%   |
| Microsoft                              | 1         | 0.49%   |
| Magic Control Technology               | 1         | 0.49%   |
| Luxvisions Innotech Limited            | 1         | 0.49%   |
| Lenovo                                 | 1         | 0.49%   |
| Intel                                  | 1         | 0.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 14        | 6.86%   |
| Chicony Integrated Camera                | 10        | 4.9%    |
| Chicony HD WebCam                        | 10        | 4.9%    |
| IMC Networks Integrated Camera           | 9         | 4.41%   |
| IMC Networks USB2.0 HD UVC WebCam        | 8         | 3.92%   |
| Sunplus Integrated_Webcam_HD             | 6         | 2.94%   |
| Realtek Integrated_Webcam_HD             | 6         | 2.94%   |
| Samsung Galaxy A5 (MTP)                  | 5         | 2.45%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 5         | 2.45%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 4         | 1.96%   |
| Chicony HP HD Camera                     | 4         | 1.96%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 1.96%   |
| Acer Integrated Camera                   | 4         | 1.96%   |
| Syntek Integrated Camera                 | 3         | 1.47%   |
| Logitech HD Webcam C615                  | 3         | 1.47%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 3         | 1.47%   |
| Chicony HP Wide Vision HD Camera         | 3         | 1.47%   |
| Apple iPhone 5/5C/5S/6/SE                | 3         | 1.47%   |
| Apple FaceTime HD Camera                 | 3         | 1.47%   |
| Realtek Integrated Webcam_HD             | 2         | 0.98%   |
| Realtek Asus 2.0 USB Webcam              | 2         | 0.98%   |
| Microdia USB 2.0 Camera                  | 2         | 0.98%   |
| Microdia Sonix USB 2.0 Camera            | 2         | 0.98%   |
| Logitech C922 Pro Stream Webcam          | 2         | 0.98%   |
| Lite-On Integrated Camera                | 2         | 0.98%   |
| Lite-On HP Wide Vision HD Camera         | 2         | 0.98%   |
| IMC Networks Lenovo EasyCamera           | 2         | 0.98%   |
| Chicony VGA Webcam                       | 2         | 0.98%   |
| Chicony USB2.0 HD UVC WebCam             | 2         | 0.98%   |
| Chicony USB2.0 Camera                    | 2         | 0.98%   |
| Chicony Integrated Camera [ThinkPad]     | 2         | 0.98%   |
| Chicony HD User Facing                   | 2         | 0.98%   |
| Apple Built-in iSight                    | 2         | 0.98%   |
| Acer BisonCam, NB Pro                    | 2         | 0.98%   |
| Z-Star Lenovo IdeaCentre Web Camera      | 1         | 0.49%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.49%   |
| Suyin UVC HD Webcam                      | 1         | 0.49%   |
| Suyin Laptop_Integrated_Webcam_HD        | 1         | 0.49%   |
| Suyin HD WebCam                          | 1         | 0.49%   |
| Suyin HD Video WebCam                    | 1         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 15        | 25.42%  |
| Validity Sensors                   | 10        | 16.95%  |
| Elan Microelectronics              | 8         | 13.56%  |
| Shenzhen Goodix Technology         | 7         | 11.86%  |
| Upek                               | 6         | 10.17%  |
| LighTuning Technology              | 6         | 10.17%  |
| AuthenTec                          | 6         | 10.17%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 13.56%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 10.17%  |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 10.17%  |
| Elan ELAN:Fingerprint                                                      | 6         | 10.17%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5.08%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 5.08%   |
| Unknown                                                                    | 3         | 5.08%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.39%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.39%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 3.39%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.39%   |
| AuthenTec AES2810                                                          | 2         | 3.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 3.39%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.69%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.69%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.69%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.69%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor     | Computers | Percent |
|------------|-----------|---------|
| Broadcom   | 7         | 87.5%   |
| Clay Logic | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 4         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 2         | 25%     |
| Clay Logic Nitrokey Start                      | 1         | 12.5%   |
| Broadcom 5880                                  | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 223       | 64.83%  |
| 1     | 92        | 26.74%  |
| 2     | 24        | 6.98%   |
| 3     | 3         | 0.87%   |
| 5     | 1         | 0.29%   |
| 4     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 56        | 36.6%   |
| Graphics card            | 39        | 25.49%  |
| Net/wireless             | 19        | 12.42%  |
| Multimedia controller    | 7         | 4.58%   |
| Chipcard                 | 7         | 4.58%   |
| Communication controller | 5         | 3.27%   |
| Camera                   | 5         | 3.27%   |
| Net/ethernet             | 4         | 2.61%   |
| Unassigned class         | 3         | 1.96%   |
| Network                  | 2         | 1.31%   |
| Bluetooth                | 2         | 1.31%   |
| Wireless                 | 1         | 0.65%   |
| Storage/raid             | 1         | 0.65%   |
| Sound                    | 1         | 0.65%   |
| Firewire controller      | 1         | 0.65%   |

