Linux in Malaysia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Malaysia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Malaysia/Desktop/README.md) and [notebooks](/Location/Malaysia/Notebook/README.md).

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

Total: 425

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | H470 HD3                    | Desktop     | [4857a7b7bf](https://linux-hardware.org/?probe=4857a7b7bf) | Jun 30, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [c5a5b25674](https://linux-hardware.org/?probe=c5a5b25674) | Jun 28, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [c292904665](https://linux-hardware.org/?probe=c292904665) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2a4d1c8a0b](https://linux-hardware.org/?probe=2a4d1c8a0b) | Jun 19, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [35c05116d1](https://linux-hardware.org/?probe=35c05116d1) | Jun 16, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [4692c93a71](https://linux-hardware.org/?probe=4692c93a71) | Jun 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| ASUSTek       | K42Jc                       | Notebook    | [29538e9e80](https://linux-hardware.org/?probe=29538e9e80) | May 21, 2022 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [e0aab70a85](https://linux-hardware.org/?probe=e0aab70a85) | May 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [d525e0eb0c](https://linux-hardware.org/?probe=d525e0eb0c) | May 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [0a9f8b0a4a](https://linux-hardware.org/?probe=0a9f8b0a4a) | May 09, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [f34555b3d6](https://linux-hardware.org/?probe=f34555b3d6) | Apr 30, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [43adb86887](https://linux-hardware.org/?probe=43adb86887) | Apr 25, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ba9b8d5ac1](https://linux-hardware.org/?probe=ba9b8d5ac1) | Apr 25, 2022 |
| ECS           | Iris8                       | Desktop     | [1cff4313c1](https://linux-hardware.org/?probe=1cff4313c1) | Apr 23, 2022 |
| HP            | 2B2C                        | Desktop     | [195e5473e9](https://linux-hardware.org/?probe=195e5473e9) | Apr 20, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [c4456aaa4f](https://linux-hardware.org/?probe=c4456aaa4f) | Apr 19, 2022 |
| HP            | 2B2C                        | Desktop     | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| ILLEGEAR      | ROGUE                       | Notebook    | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ddd1338d3](https://linux-hardware.org/?probe=9ddd1338d3) | Apr 08, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [7ec10d98e3](https://linux-hardware.org/?probe=7ec10d98e3) | Apr 03, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [6cd967267b](https://linux-hardware.org/?probe=6cd967267b) | Mar 31, 2022 |
| Lenovo        | 30D9 NOK                    | Desktop     | [c378cd6fd3](https://linux-hardware.org/?probe=c378cd6fd3) | Mar 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [d9e3d65314](https://linux-hardware.org/?probe=d9e3d65314) | Mar 24, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| Dell          | Inspiron 15 5501            | Notebook    | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [a1c0612337](https://linux-hardware.org/?probe=a1c0612337) | Mar 17, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [d52d9feb9e](https://linux-hardware.org/?probe=d52d9feb9e) | Mar 09, 2022 |
| Dell          | Precision 7730              | Notebook    | [9e9710e890](https://linux-hardware.org/?probe=9e9710e890) | Mar 08, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [8d3f72c54f](https://linux-hardware.org/?probe=8d3f72c54f) | Mar 03, 2022 |
| Biostar       | G41D3+                      | Desktop     | [62ba30cf71](https://linux-hardware.org/?probe=62ba30cf71) | Mar 02, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [bbedea92ea](https://linux-hardware.org/?probe=bbedea92ea) | Mar 01, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [297c168632](https://linux-hardware.org/?probe=297c168632) | Mar 01, 2022 |
| Shuttle       | FH170                       | Desktop     | [768e13fd34](https://linux-hardware.org/?probe=768e13fd34) | Feb 25, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [1dec2ddfad](https://linux-hardware.org/?probe=1dec2ddfad) | Feb 19, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [747515703c](https://linux-hardware.org/?probe=747515703c) | Jan 25, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [5d1c8ba7f2](https://linux-hardware.org/?probe=5d1c8ba7f2) | Jan 18, 2022 |
| Dell          | Precision 5550              | Notebook    | [6b866b7c2f](https://linux-hardware.org/?probe=6b866b7c2f) | Jan 18, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [7e0ee3374e](https://linux-hardware.org/?probe=7e0ee3374e) | Jan 16, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6b15f755b0](https://linux-hardware.org/?probe=6b15f755b0) | Jan 12, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [ff2f0db3fe](https://linux-hardware.org/?probe=ff2f0db3fe) | Jan 09, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Lenovo        | ThinkStation S10 6483CTO    | Desktop     | [0d867912a7](https://linux-hardware.org/?probe=0d867912a7) | Jan 01, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| Dell          | Latitude 7490               | Notebook    | [4ac5151ac0](https://linux-hardware.org/?probe=4ac5151ac0) | Dec 29, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| MSI           | GL62M 7RDX                  | Notebook    | [3f8cb0706d](https://linux-hardware.org/?probe=3f8cb0706d) | Dec 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9fe5f60531](https://linux-hardware.org/?probe=9fe5f60531) | Dec 26, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c8ca1c8cc8](https://linux-hardware.org/?probe=c8ca1c8cc8) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | Notebook    | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Acer          | E3-112M-C6BV                | Notebook    | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [c748f77108](https://linux-hardware.org/?probe=c748f77108) | Dec 12, 2021 |
| HP            | 2B44                        | Desktop     | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| Dell          | Latitude E6520              | Notebook    | [faf1be45ae](https://linux-hardware.org/?probe=faf1be45ae) | Dec 03, 2021 |
| Dell          | Latitude E6520              | Notebook    | [16b69bfefc](https://linux-hardware.org/?probe=16b69bfefc) | Dec 01, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [eb4fb496ae](https://linux-hardware.org/?probe=eb4fb496ae) | Dec 01, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5c4ae3bd8c](https://linux-hardware.org/?probe=5c4ae3bd8c) | Nov 30, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c731d25471](https://linux-hardware.org/?probe=c731d25471) | Nov 30, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [6e5e669c60](https://linux-hardware.org/?probe=6e5e669c60) | Nov 25, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | Notebook    | [644d197332](https://linux-hardware.org/?probe=644d197332) | Nov 17, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | Notebook    | [bece194d5a](https://linux-hardware.org/?probe=bece194d5a) | Nov 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [b5393ad660](https://linux-hardware.org/?probe=b5393ad660) | Nov 12, 2021 |
| ASUSTek       | T200TA                      | Notebook    | [1f55c83774](https://linux-hardware.org/?probe=1f55c83774) | Nov 04, 2021 |
| ASUSTek       | M2N32-SLI DELUXE            | Desktop     | [87fff05f0f](https://linux-hardware.org/?probe=87fff05f0f) | Nov 03, 2021 |
| Lenovo        | U310                        | Notebook    | [986ba47618](https://linux-hardware.org/?probe=986ba47618) | Oct 24, 2021 |
| Lenovo        | U310                        | Notebook    | [c74a07756c](https://linux-hardware.org/?probe=c74a07756c) | Oct 24, 2021 |
| Intel         | B75                         | Desktop     | [fef715f491](https://linux-hardware.org/?probe=fef715f491) | Oct 23, 2021 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [ccd587fde5](https://linux-hardware.org/?probe=ccd587fde5) | Oct 21, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | Notebook                    | Notebook    | [2761140513](https://linux-hardware.org/?probe=2761140513) | Oct 14, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [8fee3106f7](https://linux-hardware.org/?probe=8fee3106f7) | Oct 12, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [f79000e059](https://linux-hardware.org/?probe=f79000e059) | Oct 12, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Biostar       | G41D3C                      | Desktop     | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [09b2cd1736](https://linux-hardware.org/?probe=09b2cd1736) | Oct 06, 2021 |
| Biostar       | G41D3C                      | Desktop     | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [07b1aa0f24](https://linux-hardware.org/?probe=07b1aa0f24) | Sep 27, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [2cdb257de7](https://linux-hardware.org/?probe=2cdb257de7) | Sep 27, 2021 |
| HP            | Notebook                    | Notebook    | [32d9b71796](https://linux-hardware.org/?probe=32d9b71796) | Sep 25, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [17c3d61831](https://linux-hardware.org/?probe=17c3d61831) | Sep 21, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [1292424ff8](https://linux-hardware.org/?probe=1292424ff8) | Sep 17, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [7441498212](https://linux-hardware.org/?probe=7441498212) | Sep 14, 2021 |
| Lenovo        | Flex 6-11IGM 81A7           | Convertible | [17e78af479](https://linux-hardware.org/?probe=17e78af479) | Sep 14, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [c2533e9d48](https://linux-hardware.org/?probe=c2533e9d48) | Sep 11, 2021 |
| MSI           | H81M-P33                    | Desktop     | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [930ad79fe0](https://linux-hardware.org/?probe=930ad79fe0) | Sep 08, 2021 |
| Biostar       | G41D3C                      | Desktop     | [8137e09a97](https://linux-hardware.org/?probe=8137e09a97) | Sep 08, 2021 |
| Biostar       | G41D3C                      | Desktop     | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9c46f65e1d](https://linux-hardware.org/?probe=9c46f65e1d) | Sep 06, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| HP            | ENVY 4                      | Notebook    | [b61e9946e0](https://linux-hardware.org/?probe=b61e9946e0) | Sep 04, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5377e486bc](https://linux-hardware.org/?probe=5377e486bc) | Sep 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [acc6c11a97](https://linux-hardware.org/?probe=acc6c11a97) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [7b28a98a35](https://linux-hardware.org/?probe=7b28a98a35) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [7fada0ab8c](https://linux-hardware.org/?probe=7fada0ab8c) | Sep 01, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a61ee6d83a](https://linux-hardware.org/?probe=a61ee6d83a) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a1ec21ae3f](https://linux-hardware.org/?probe=a1ec21ae3f) | Aug 29, 2021 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [cac6720bff](https://linux-hardware.org/?probe=cac6720bff) | Aug 29, 2021 |
| Lenovo        | G400s VILG1                 | Notebook    | [20d6b25fd3](https://linux-hardware.org/?probe=20d6b25fd3) | Aug 29, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [777faedb05](https://linux-hardware.org/?probe=777faedb05) | Aug 27, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [9e8fa8f32d](https://linux-hardware.org/?probe=9e8fa8f32d) | Aug 23, 2021 |
| HP            | Notebook                    | Notebook    | [4028a5fb73](https://linux-hardware.org/?probe=4028a5fb73) | Aug 21, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [de1fa2ccc0](https://linux-hardware.org/?probe=de1fa2ccc0) | Aug 20, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [e359985b75](https://linux-hardware.org/?probe=e359985b75) | Aug 14, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [bb82d97c94](https://linux-hardware.org/?probe=bb82d97c94) | Aug 10, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [38abf3b8e9](https://linux-hardware.org/?probe=38abf3b8e9) | Aug 10, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [89188fe3ca](https://linux-hardware.org/?probe=89188fe3ca) | Aug 08, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3e56e95f2f](https://linux-hardware.org/?probe=3e56e95f2f) | Aug 05, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | Notebook    | [b10f021bef](https://linux-hardware.org/?probe=b10f021bef) | Aug 01, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [36562061d6](https://linux-hardware.org/?probe=36562061d6) | Jul 30, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | Notebook    | [4cf28c3600](https://linux-hardware.org/?probe=4cf28c3600) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| HP            | Notebook                    | Notebook    | [458741e8e2](https://linux-hardware.org/?probe=458741e8e2) | Jul 23, 2021 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [e71a7fc65b](https://linux-hardware.org/?probe=e71a7fc65b) | Jul 23, 2021 |
| HP            | Pavilion 14                 | Notebook    | [0556a517ff](https://linux-hardware.org/?probe=0556a517ff) | Jul 23, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [fe43d29e0e](https://linux-hardware.org/?probe=fe43d29e0e) | Jul 22, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [3e66028cf8](https://linux-hardware.org/?probe=3e66028cf8) | Jul 22, 2021 |
| ASUSTek       | K43SA                       | Notebook    | [3c81cd98ac](https://linux-hardware.org/?probe=3c81cd98ac) | Jul 21, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| ASUSTek       | K43SA                       | Notebook    | [3da0ea28fa](https://linux-hardware.org/?probe=3da0ea28fa) | Jul 20, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [5a349c4952](https://linux-hardware.org/?probe=5a349c4952) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [275304e806](https://linux-hardware.org/?probe=275304e806) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [99df792e3b](https://linux-hardware.org/?probe=99df792e3b) | Jul 18, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9ffbb5bc79](https://linux-hardware.org/?probe=9ffbb5bc79) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [0e8b29c721](https://linux-hardware.org/?probe=0e8b29c721) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [da8679ccca](https://linux-hardware.org/?probe=da8679ccca) | Jul 14, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [2495cf9be5](https://linux-hardware.org/?probe=2495cf9be5) | Jul 12, 2021 |
| HP            | Compaq 6530b (VA036PA#UU... | Notebook    | [ac0b6b96cc](https://linux-hardware.org/?probe=ac0b6b96cc) | Jul 11, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b551baea7d](https://linux-hardware.org/?probe=b551baea7d) | Jul 11, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [477a92a37e](https://linux-hardware.org/?probe=477a92a37e) | Jul 11, 2021 |
| HP            | Notebook                    | Notebook    | [2f040042a3](https://linux-hardware.org/?probe=2f040042a3) | Jul 10, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [82c73cf6be](https://linux-hardware.org/?probe=82c73cf6be) | Jul 09, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [4e555accb1](https://linux-hardware.org/?probe=4e555accb1) | Jul 08, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [416014c8b8](https://linux-hardware.org/?probe=416014c8b8) | Jul 07, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [a630867e0a](https://linux-hardware.org/?probe=a630867e0a) | Jul 06, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [e8965c736d](https://linux-hardware.org/?probe=e8965c736d) | Jul 05, 2021 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | Notebook    | [e1a02c3dcb](https://linux-hardware.org/?probe=e1a02c3dcb) | Jul 04, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [939fe39f71](https://linux-hardware.org/?probe=939fe39f71) | Jul 01, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [44c1472c85](https://linux-hardware.org/?probe=44c1472c85) | Jun 30, 2021 |
| AZW           | GT-R                        | Notebook    | [feaf90902f](https://linux-hardware.org/?probe=feaf90902f) | Jun 28, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [de1dbcbd7f](https://linux-hardware.org/?probe=de1dbcbd7f) | Jun 27, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [ddb8152ea4](https://linux-hardware.org/?probe=ddb8152ea4) | Jun 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [1104a3ca5a](https://linux-hardware.org/?probe=1104a3ca5a) | Jun 26, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [a5a80d3f13](https://linux-hardware.org/?probe=a5a80d3f13) | Jun 24, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [d9270ab2c1](https://linux-hardware.org/?probe=d9270ab2c1) | Jun 23, 2021 |
| Lenovo        | ThinkPad X201 3626RZ4       | Notebook    | [737819a617](https://linux-hardware.org/?probe=737819a617) | Jun 22, 2021 |
| HP            | Notebook                    | Notebook    | [0f663cf796](https://linux-hardware.org/?probe=0f663cf796) | Jun 20, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [9a397ba3b9](https://linux-hardware.org/?probe=9a397ba3b9) | Jun 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [0183eeb644](https://linux-hardware.org/?probe=0183eeb644) | Jun 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [b0ded1652a](https://linux-hardware.org/?probe=b0ded1652a) | Jun 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e4a2d2d3c9](https://linux-hardware.org/?probe=e4a2d2d3c9) | Jun 06, 2021 |
| MSI           | H81M-P33                    | Desktop     | [69a8b43e74](https://linux-hardware.org/?probe=69a8b43e74) | Jun 02, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a67e6bcfce](https://linux-hardware.org/?probe=a67e6bcfce) | Jun 02, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [49a2755ccd](https://linux-hardware.org/?probe=49a2755ccd) | May 31, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [00658a23ab](https://linux-hardware.org/?probe=00658a23ab) | May 27, 2021 |
| Lenovo        | ThinkPad X120e 0611CTO      | Notebook    | [72608b2ea0](https://linux-hardware.org/?probe=72608b2ea0) | May 27, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [5f39051050](https://linux-hardware.org/?probe=5f39051050) | May 26, 2021 |
| Dell          | Inspiron 3443               | Notebook    | [1a314f201b](https://linux-hardware.org/?probe=1a314f201b) | May 26, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [4c5c7570f6](https://linux-hardware.org/?probe=4c5c7570f6) | May 25, 2021 |
| HP            | Notebook                    | Notebook    | [a075cb3a8d](https://linux-hardware.org/?probe=a075cb3a8d) | May 24, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [2b0de1ba10](https://linux-hardware.org/?probe=2b0de1ba10) | May 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [021e17aa96](https://linux-hardware.org/?probe=021e17aa96) | May 19, 2021 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [0cd0f0c51f](https://linux-hardware.org/?probe=0cd0f0c51f) | May 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [71f7778600](https://linux-hardware.org/?probe=71f7778600) | May 13, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [d6ab5352b8](https://linux-hardware.org/?probe=d6ab5352b8) | May 10, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [67e6985b08](https://linux-hardware.org/?probe=67e6985b08) | May 02, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [8624f1c148](https://linux-hardware.org/?probe=8624f1c148) | Apr 30, 2021 |
| HP            | 0AA8h                       | Desktop     | [5f350b471f](https://linux-hardware.org/?probe=5f350b471f) | Apr 29, 2021 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [6bb8ea7872](https://linux-hardware.org/?probe=6bb8ea7872) | Apr 23, 2021 |
| System76      | Galago Pro                  | Notebook    | [e712e1fadc](https://linux-hardware.org/?probe=e712e1fadc) | Apr 21, 2021 |
| Gigabyte      | Z97X-Gaming G1              | Desktop     | [07efcf431f](https://linux-hardware.org/?probe=07efcf431f) | Apr 14, 2021 |
| Gigabyte      | Z97X-Gaming G1              | Desktop     | [9f265d798d](https://linux-hardware.org/?probe=9f265d798d) | Apr 14, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [87041c97fb](https://linux-hardware.org/?probe=87041c97fb) | Apr 14, 2021 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [6d3642385e](https://linux-hardware.org/?probe=6d3642385e) | Apr 11, 2021 |
| HP            | 2B1C MVB,A                  | All in one  | [ea47f5adbe](https://linux-hardware.org/?probe=ea47f5adbe) | Apr 05, 2021 |
| Dell          | XPS L412Z                   | Notebook    | [e383c24416](https://linux-hardware.org/?probe=e383c24416) | Apr 01, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [006be2bbab](https://linux-hardware.org/?probe=006be2bbab) | Mar 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [1a6bdfe860](https://linux-hardware.org/?probe=1a6bdfe860) | Mar 22, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [7a17fa61d9](https://linux-hardware.org/?probe=7a17fa61d9) | Mar 17, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [d476794634](https://linux-hardware.org/?probe=d476794634) | Mar 16, 2021 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [fc405347a5](https://linux-hardware.org/?probe=fc405347a5) | Mar 12, 2021 |
| Sony          | VPCEA42EG                   | Notebook    | [e49095cfef](https://linux-hardware.org/?probe=e49095cfef) | Mar 09, 2021 |
| ASUSTek       | S550CM                      | Notebook    | [5ac3e9de20](https://linux-hardware.org/?probe=5ac3e9de20) | Mar 08, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [597b4f88b9](https://linux-hardware.org/?probe=597b4f88b9) | Mar 08, 2021 |
| HP            | Presario CQ43               | Notebook    | [4f9c0e744c](https://linux-hardware.org/?probe=4f9c0e744c) | Feb 28, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [082f8fd3e5](https://linux-hardware.org/?probe=082f8fd3e5) | Feb 27, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [1555ed8743](https://linux-hardware.org/?probe=1555ed8743) | Feb 27, 2021 |
| ASUSTek       | H110M-D                     | Desktop     | [19e3cff2be](https://linux-hardware.org/?probe=19e3cff2be) | Feb 27, 2021 |
| HP            | Pavilion dv6                | Notebook    | [4f82ee745a](https://linux-hardware.org/?probe=4f82ee745a) | Feb 25, 2021 |
| HP            | Presario CQ43               | Notebook    | [e6e7199511](https://linux-hardware.org/?probe=e6e7199511) | Feb 22, 2021 |
| ASUSTek       | X456UF                      | Notebook    | [f69a109f5c](https://linux-hardware.org/?probe=f69a109f5c) | Feb 14, 2021 |
| HP            | G42                         | Notebook    | [7e1ebb9cf3](https://linux-hardware.org/?probe=7e1ebb9cf3) | Feb 13, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [6c0820678b](https://linux-hardware.org/?probe=6c0820678b) | Feb 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [92518dacfe](https://linux-hardware.org/?probe=92518dacfe) | Feb 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4f8464acc9](https://linux-hardware.org/?probe=4f8464acc9) | Feb 10, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [b50872caf4](https://linux-hardware.org/?probe=b50872caf4) | Feb 07, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [7daa68908c](https://linux-hardware.org/?probe=7daa68908c) | Feb 06, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [acb369859f](https://linux-hardware.org/?probe=acb369859f) | Feb 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [aa40d0ff2b](https://linux-hardware.org/?probe=aa40d0ff2b) | Feb 04, 2021 |
| Acer          | Veriton X6630G V:1.0        | Desktop     | [d6126d9f25](https://linux-hardware.org/?probe=d6126d9f25) | Jan 27, 2021 |
| Acer          | Veriton X6630G V:1.0        | Desktop     | [9e5a28d45d](https://linux-hardware.org/?probe=9e5a28d45d) | Jan 27, 2021 |
| Dell          | 0WR7PY A01                  | Desktop     | [9b13ab689f](https://linux-hardware.org/?probe=9b13ab689f) | Jan 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [31faebfa48](https://linux-hardware.org/?probe=31faebfa48) | Jan 23, 2021 |
| Dell          | Latitude 3440               | Notebook    | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [353fb07166](https://linux-hardware.org/?probe=353fb07166) | Jan 20, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [dd87c824a0](https://linux-hardware.org/?probe=dd87c824a0) | Jan 18, 2021 |
| HP            | G42                         | Notebook    | [b4a8c3727b](https://linux-hardware.org/?probe=b4a8c3727b) | Jan 13, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9e291d5782](https://linux-hardware.org/?probe=9e291d5782) | Jan 12, 2021 |
| HP            | Notebook                    | Notebook    | [6bb93d5d1d](https://linux-hardware.org/?probe=6bb93d5d1d) | Jan 03, 2021 |
| HP            | Presario CQ43               | Notebook    | [d410f07eef](https://linux-hardware.org/?probe=d410f07eef) | Jan 03, 2021 |
| HP            | Presario CQ43               | Notebook    | [15ba146bfe](https://linux-hardware.org/?probe=15ba146bfe) | Jan 03, 2021 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [f3c691cbf8](https://linux-hardware.org/?probe=f3c691cbf8) | Jan 01, 2021 |
| MSI           | H81M-P33                    | Desktop     | [e8d73a49e5](https://linux-hardware.org/?probe=e8d73a49e5) | Dec 30, 2020 |
| HP            | Pavilion g4                 | Notebook    | [c495b342b0](https://linux-hardware.org/?probe=c495b342b0) | Dec 30, 2020 |
| ASUSTek       | TP500LN                     | Notebook    | [36ae52e7d3](https://linux-hardware.org/?probe=36ae52e7d3) | Dec 27, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [fa76a31b79](https://linux-hardware.org/?probe=fa76a31b79) | Dec 24, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [7e473c8d12](https://linux-hardware.org/?probe=7e473c8d12) | Dec 24, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [645dfe5a80](https://linux-hardware.org/?probe=645dfe5a80) | Dec 23, 2020 |
| Dell          | 0PU052                      | Desktop     | [520a4ef3d0](https://linux-hardware.org/?probe=520a4ef3d0) | Dec 23, 2020 |
| Biostar       | A320MH                      | Desktop     | [a6b1134a37](https://linux-hardware.org/?probe=a6b1134a37) | Dec 18, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [41d76fb580](https://linux-hardware.org/?probe=41d76fb580) | Dec 17, 2020 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [a0b90b128d](https://linux-hardware.org/?probe=a0b90b128d) | Dec 16, 2020 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [9af064ae47](https://linux-hardware.org/?probe=9af064ae47) | Dec 16, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [414fc579a1](https://linux-hardware.org/?probe=414fc579a1) | Dec 02, 2020 |
| HP            | 2B1C MVB,A                  | All in one  | [4d1d3b1722](https://linux-hardware.org/?probe=4d1d3b1722) | Dec 02, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [cf6242caca](https://linux-hardware.org/?probe=cf6242caca) | Dec 02, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [afbf8ce7bc](https://linux-hardware.org/?probe=afbf8ce7bc) | Dec 01, 2020 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [967bb7f4d6](https://linux-hardware.org/?probe=967bb7f4d6) | Nov 30, 2020 |
| HP            | 2B1C MVB,A                  | All in one  | [400561434f](https://linux-hardware.org/?probe=400561434f) | Nov 27, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [151262b7a2](https://linux-hardware.org/?probe=151262b7a2) | Nov 26, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eecae3dcbf](https://linux-hardware.org/?probe=eecae3dcbf) | Nov 26, 2020 |
| Dell          | G3 3590                     | Notebook    | [d76accb676](https://linux-hardware.org/?probe=d76accb676) | Nov 18, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [c323f09a39](https://linux-hardware.org/?probe=c323f09a39) | Nov 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [db8eeca79f](https://linux-hardware.org/?probe=db8eeca79f) | Nov 15, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [f617d36143](https://linux-hardware.org/?probe=f617d36143) | Nov 12, 2020 |
| Gigabyte      | Z490 VISION D               | Desktop     | [af58d1579d](https://linux-hardware.org/?probe=af58d1579d) | Nov 09, 2020 |
| Acer          | TM4750                      | Notebook    | [8380f08a89](https://linux-hardware.org/?probe=8380f08a89) | Nov 07, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [4c1052e401](https://linux-hardware.org/?probe=4c1052e401) | Nov 06, 2020 |
| Dell          | G3 3590                     | Notebook    | [b2a86aaf94](https://linux-hardware.org/?probe=b2a86aaf94) | Nov 04, 2020 |
| Dell          | Latitude E6530              | Notebook    | [50772450d3](https://linux-hardware.org/?probe=50772450d3) | Nov 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [1a5aef928b](https://linux-hardware.org/?probe=1a5aef928b) | Nov 01, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [5021546be8](https://linux-hardware.org/?probe=5021546be8) | Oct 30, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [adc51544ee](https://linux-hardware.org/?probe=adc51544ee) | Oct 29, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | Notebook    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Acer          | TM4750                      | Notebook    | [2f46c4d024](https://linux-hardware.org/?probe=2f46c4d024) | Oct 27, 2020 |
| Acer          | TM4750                      | Notebook    | [29124f29f8](https://linux-hardware.org/?probe=29124f29f8) | Oct 23, 2020 |
| Dell          | G3 3590                     | Notebook    | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b6aa803efb](https://linux-hardware.org/?probe=b6aa803efb) | Oct 21, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [02a2657831](https://linux-hardware.org/?probe=02a2657831) | Oct 20, 2020 |
| Dell          | 09WH54 A00                  | Desktop     | [5c8d0c0991](https://linux-hardware.org/?probe=5c8d0c0991) | Oct 15, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a37736727](https://linux-hardware.org/?probe=1a37736727) | Oct 13, 2020 |
| Dell          | 06D7TR A02                  | Desktop     | [1fff522fa1](https://linux-hardware.org/?probe=1fff522fa1) | Oct 13, 2020 |
| Dell          | 09WH54 A00                  | Desktop     | [e8e5a3c2ac](https://linux-hardware.org/?probe=e8e5a3c2ac) | Oct 12, 2020 |
| Sony          | VGN-Z27GN_X                 | Notebook    | [a9230212d3](https://linux-hardware.org/?probe=a9230212d3) | Oct 03, 2020 |
| Unknown       | Unknown                     | Notebook    | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [80297bebea](https://linux-hardware.org/?probe=80297bebea) | Sep 17, 2020 |
| HP            | Pavilion dv6                | Notebook    | [f48a018bbb](https://linux-hardware.org/?probe=f48a018bbb) | Sep 16, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [5eaf26f820](https://linux-hardware.org/?probe=5eaf26f820) | Sep 15, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [4e3ee75e9b](https://linux-hardware.org/?probe=4e3ee75e9b) | Sep 15, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [f7f932b330](https://linux-hardware.org/?probe=f7f932b330) | Sep 14, 2020 |
| Acer          | Aspire ES1-420              | Notebook    | [730ae12528](https://linux-hardware.org/?probe=730ae12528) | Sep 10, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [828c695fab](https://linux-hardware.org/?probe=828c695fab) | Sep 06, 2020 |
| HP            | Pavilion dv6                | Notebook    | [47c4b0fdaa](https://linux-hardware.org/?probe=47c4b0fdaa) | Sep 03, 2020 |
| Dell          | Inspiron 5482               | Convertible | [4085a729ac](https://linux-hardware.org/?probe=4085a729ac) | Sep 03, 2020 |
| Dell          | 0RW203                      | Desktop     | [594ab9e6d3](https://linux-hardware.org/?probe=594ab9e6d3) | Sep 02, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [0930a62ca5](https://linux-hardware.org/?probe=0930a62ca5) | Aug 21, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| ASUSTek       | VivoBook S15 X530UN         | Notebook    | [64e65fe674](https://linux-hardware.org/?probe=64e65fe674) | Aug 11, 2020 |
| ASUSTek       | H110M-D                     | Desktop     | [bc44361c47](https://linux-hardware.org/?probe=bc44361c47) | Aug 02, 2020 |
| ASUSTek       | H110M-D                     | Desktop     | [e8cc620228](https://linux-hardware.org/?probe=e8cc620228) | Aug 02, 2020 |
| Unknown       | Unknown                     | Phone       | [38378b572a](https://linux-hardware.org/?probe=38378b572a) | Aug 01, 2020 |
| HP            | Presario CQ43               | Notebook    | [df780756ee](https://linux-hardware.org/?probe=df780756ee) | Jul 31, 2020 |
| HP            | Presario CQ43               | Notebook    | [102ab797a7](https://linux-hardware.org/?probe=102ab797a7) | Jul 31, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3f99c1674c](https://linux-hardware.org/?probe=3f99c1674c) | Jul 30, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [dbbc5219fd](https://linux-hardware.org/?probe=dbbc5219fd) | Jul 27, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [c85ae35bff](https://linux-hardware.org/?probe=c85ae35bff) | Jul 25, 2020 |
| Dell          | Latitude 7285               | Tablet      | [ed3aa05fd5](https://linux-hardware.org/?probe=ed3aa05fd5) | Jul 25, 2020 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [81e5774167](https://linux-hardware.org/?probe=81e5774167) | Jul 24, 2020 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [1856c4ccbf](https://linux-hardware.org/?probe=1856c4ccbf) | Jul 23, 2020 |
| Dell          | Latitude 7480               | Notebook    | [7fa880215f](https://linux-hardware.org/?probe=7fa880215f) | Jul 21, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [2bfaffc9c5](https://linux-hardware.org/?probe=2bfaffc9c5) | Jul 21, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [7b83e5785f](https://linux-hardware.org/?probe=7b83e5785f) | Jul 19, 2020 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [d45acf2543](https://linux-hardware.org/?probe=d45acf2543) | Jul 18, 2020 |
| Unknown       | Unknown                     | Phone       | [c0d8474803](https://linux-hardware.org/?probe=c0d8474803) | Jul 18, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ab9fa86313](https://linux-hardware.org/?probe=ab9fa86313) | Jul 16, 2020 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [4b144fb616](https://linux-hardware.org/?probe=4b144fb616) | Jul 14, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [7d9a43933e](https://linux-hardware.org/?probe=7d9a43933e) | Jul 14, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [48cdbb3d36](https://linux-hardware.org/?probe=48cdbb3d36) | Jul 11, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [f5ff1447a7](https://linux-hardware.org/?probe=f5ff1447a7) | Jul 08, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [a97a2e14e2](https://linux-hardware.org/?probe=a97a2e14e2) | Jul 06, 2020 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [0aa18d5241](https://linux-hardware.org/?probe=0aa18d5241) | Jul 05, 2020 |
| Dell          | Latitude E6440              | Notebook    | [521818b099](https://linux-hardware.org/?probe=521818b099) | Jul 02, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5d32eb1d75](https://linux-hardware.org/?probe=5d32eb1d75) | Jun 30, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [33534eca13](https://linux-hardware.org/?probe=33534eca13) | Jun 28, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6ae79e439f](https://linux-hardware.org/?probe=6ae79e439f) | Jun 28, 2020 |
| Acer          | Aspire 4738                 | Notebook    | [519a7577c0](https://linux-hardware.org/?probe=519a7577c0) | Jun 28, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [0cd3f983c9](https://linux-hardware.org/?probe=0cd3f983c9) | Jun 26, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [bad4de6363](https://linux-hardware.org/?probe=bad4de6363) | Jun 26, 2020 |
| Dell          | Latitude E6440              | Notebook    | [1ffde1aa78](https://linux-hardware.org/?probe=1ffde1aa78) | Jun 24, 2020 |
| HP            | Pavilion dv6                | Notebook    | [4833031b9b](https://linux-hardware.org/?probe=4833031b9b) | Jun 23, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [99ff555015](https://linux-hardware.org/?probe=99ff555015) | Jun 21, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [05556ef252](https://linux-hardware.org/?probe=05556ef252) | Jun 19, 2020 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0a15b3f355](https://linux-hardware.org/?probe=0a15b3f355) | Jun 18, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [eac1260628](https://linux-hardware.org/?probe=eac1260628) | Jun 17, 2020 |
| Unknown       | Unknown                     | Phone       | [6566b884d6](https://linux-hardware.org/?probe=6566b884d6) | Jun 15, 2020 |
| ASUSTek       | G551JM                      | Notebook    | [3ab69ab51e](https://linux-hardware.org/?probe=3ab69ab51e) | Jun 10, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [ba4a677fab](https://linux-hardware.org/?probe=ba4a677fab) | Jun 10, 2020 |
| HP            | 14                          | Notebook    | [5a36b38b50](https://linux-hardware.org/?probe=5a36b38b50) | Jun 07, 2020 |
| Fujitsu       | LIFEBOOK S761               | Notebook    | [7d4e0682de](https://linux-hardware.org/?probe=7d4e0682de) | Jun 07, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [6c1d889b0d](https://linux-hardware.org/?probe=6c1d889b0d) | Jun 06, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [709dcae624](https://linux-hardware.org/?probe=709dcae624) | Jun 06, 2020 |
| MSI           | A320M-A PRO MAX             | Desktop     | [11c6b72a1b](https://linux-hardware.org/?probe=11c6b72a1b) | Jun 03, 2020 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ecf8e72f94](https://linux-hardware.org/?probe=ecf8e72f94) | May 31, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [b335d617f7](https://linux-hardware.org/?probe=b335d617f7) | May 26, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [865933043f](https://linux-hardware.org/?probe=865933043f) | May 26, 2020 |
| Acer          | EQ45M                       | Desktop     | [a682473a39](https://linux-hardware.org/?probe=a682473a39) | May 23, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [d2113ac640](https://linux-hardware.org/?probe=d2113ac640) | May 21, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [1882c535de](https://linux-hardware.org/?probe=1882c535de) | May 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [445fc4fef9](https://linux-hardware.org/?probe=445fc4fef9) | May 19, 2020 |
| Dell          | 0PU052                      | Desktop     | [40ab4a84b5](https://linux-hardware.org/?probe=40ab4a84b5) | May 18, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [8156a3eef6](https://linux-hardware.org/?probe=8156a3eef6) | May 11, 2020 |
| SNS Networ... | JOI Book 150                | Notebook    | [3d61c3722c](https://linux-hardware.org/?probe=3d61c3722c) | May 11, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [f92d9768ce](https://linux-hardware.org/?probe=f92d9768ce) | May 07, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [b119ccc5f2](https://linux-hardware.org/?probe=b119ccc5f2) | May 07, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4893a0cfcd](https://linux-hardware.org/?probe=4893a0cfcd) | May 06, 2020 |
| Dell          | 0RY007                      | Desktop     | [4d44e2723d](https://linux-hardware.org/?probe=4d44e2723d) | May 04, 2020 |
| HP            | 14                          | Notebook    | [c0318bc179](https://linux-hardware.org/?probe=c0318bc179) | Apr 30, 2020 |
| Acer          | EQ45M                       | Desktop     | [03e154e2dc](https://linux-hardware.org/?probe=03e154e2dc) | Apr 21, 2020 |
| Dell          | 0C3YXR A01                  | Desktop     | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| BUSH          | Windows tablet              | Notebook    | [a25abad9de](https://linux-hardware.org/?probe=a25abad9de) | Apr 18, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [9c68002e3d](https://linux-hardware.org/?probe=9c68002e3d) | Apr 13, 2020 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [0444963962](https://linux-hardware.org/?probe=0444963962) | Apr 12, 2020 |
| MSI           | B150M Night Elf             | Desktop     | [01013b611d](https://linux-hardware.org/?probe=01013b611d) | Apr 11, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [1211d7770c](https://linux-hardware.org/?probe=1211d7770c) | Mar 15, 2020 |
| Acer          | TM4750                      | Notebook    | [bedf724360](https://linux-hardware.org/?probe=bedf724360) | Mar 11, 2020 |
| Acer          | TM4750                      | Notebook    | [db9b7453f2](https://linux-hardware.org/?probe=db9b7453f2) | Mar 11, 2020 |
| Acer          | TM4750                      | Notebook    | [69bbe5f0ee](https://linux-hardware.org/?probe=69bbe5f0ee) | Mar 11, 2020 |
| Dell          | Inspiron 1464               | Notebook    | [d6a38ddcea](https://linux-hardware.org/?probe=d6a38ddcea) | Mar 08, 2020 |
| Dell          | 0JWGHC A01                  | All in one  | [46ad418d75](https://linux-hardware.org/?probe=46ad418d75) | Feb 24, 2020 |
| Dell          | 0JWGHC A01                  | All in one  | [c1b65d99ff](https://linux-hardware.org/?probe=c1b65d99ff) | Feb 23, 2020 |
| Teclast       | F5                          | Convertible | [23690a5a6e](https://linux-hardware.org/?probe=23690a5a6e) | Feb 16, 2020 |
| Acer          | Aspire 4736Z                | Notebook    | [a6e2ff9c02](https://linux-hardware.org/?probe=a6e2ff9c02) | Feb 15, 2020 |
| ASUSTek       | P6T SE                      | Desktop     | [05737b4c23](https://linux-hardware.org/?probe=05737b4c23) | Feb 11, 2020 |
| HP            | 3647h                       | Desktop     | [06df72e240](https://linux-hardware.org/?probe=06df72e240) | Feb 08, 2020 |
| HP            | ProBook 645 G1              | Notebook    | [18fb680615](https://linux-hardware.org/?probe=18fb680615) | Feb 04, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [5ab23205d8](https://linux-hardware.org/?probe=5ab23205d8) | Jan 21, 2020 |
| ASUSTek       | P8Z77-M                     | Desktop     | [9247337003](https://linux-hardware.org/?probe=9247337003) | Jan 20, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [1b04478121](https://linux-hardware.org/?probe=1b04478121) | Jan 14, 2020 |
| Chuwi         | LapBook Pro                 | Notebook    | [f9d248ac7c](https://linux-hardware.org/?probe=f9d248ac7c) | Jan 03, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3b64de1ec8](https://linux-hardware.org/?probe=3b64de1ec8) | Dec 31, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [31643f4ace](https://linux-hardware.org/?probe=31643f4ace) | Dec 31, 2019 |
| Lenovo        | G500s 20245                 | Notebook    | [82346138d0](https://linux-hardware.org/?probe=82346138d0) | Dec 30, 2019 |
| HP            | ProBook 4545s               | Notebook    | [66e278f8a6](https://linux-hardware.org/?probe=66e278f8a6) | Dec 29, 2019 |
| HP            | ProBook 4545s               | Notebook    | [7c1a6a786f](https://linux-hardware.org/?probe=7c1a6a786f) | Dec 29, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [02d013ad00](https://linux-hardware.org/?probe=02d013ad00) | Dec 20, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [f4689330d7](https://linux-hardware.org/?probe=f4689330d7) | Dec 14, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [d651477524](https://linux-hardware.org/?probe=d651477524) | Dec 14, 2019 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c0c7973b78](https://linux-hardware.org/?probe=c0c7973b78) | Nov 20, 2019 |
| Supermicro    | K1SPE-IN001                 | Server      | [5f6d0233a8](https://linux-hardware.org/?probe=5f6d0233a8) | Nov 18, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [9e78c03471](https://linux-hardware.org/?probe=9e78c03471) | Nov 17, 2019 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [875f14ed53](https://linux-hardware.org/?probe=875f14ed53) | Nov 13, 2019 |
| Dell          | Vostro V130                 | Notebook    | [ca716fdbad](https://linux-hardware.org/?probe=ca716fdbad) | Nov 09, 2019 |
| Dell          | Vostro V130                 | Notebook    | [0ba8558483](https://linux-hardware.org/?probe=0ba8558483) | Nov 08, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [7ce70fa206](https://linux-hardware.org/?probe=7ce70fa206) | Oct 25, 2019 |
| Acer          | Swift SF314-55G             | Notebook    | [8526e89541](https://linux-hardware.org/?probe=8526e89541) | Oct 16, 2019 |
| ASUSTek       | X456URK                     | Notebook    | [03b7432783](https://linux-hardware.org/?probe=03b7432783) | Oct 10, 2019 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [b37e090603](https://linux-hardware.org/?probe=b37e090603) | Oct 06, 2019 |
| HP            | 0AA8h                       | Desktop     | [a60543a450](https://linux-hardware.org/?probe=a60543a450) | Sep 07, 2019 |
| HP            | ZBook 15                    | Notebook    | [f9aaccbfe0](https://linux-hardware.org/?probe=f9aaccbfe0) | Sep 06, 2019 |
| Dell          | Latitude E7440              | Notebook    | [04bd492077](https://linux-hardware.org/?probe=04bd492077) | Sep 06, 2019 |
| MSI           | GP70 2PE                    | Notebook    | [ae117eb491](https://linux-hardware.org/?probe=ae117eb491) | Sep 03, 2019 |
| Dell          | 0RY007                      | Desktop     | [576ec7dcd0](https://linux-hardware.org/?probe=576ec7dcd0) | Aug 22, 2019 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [d9d789a4f2](https://linux-hardware.org/?probe=d9d789a4f2) | Aug 21, 2019 |
| MSI           | GP70 2PE                    | Notebook    | [3442bbe40c](https://linux-hardware.org/?probe=3442bbe40c) | Aug 05, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [f8d49fa793](https://linux-hardware.org/?probe=f8d49fa793) | Aug 03, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [46b9ff1fff](https://linux-hardware.org/?probe=46b9ff1fff) | Aug 03, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [a91c21a426](https://linux-hardware.org/?probe=a91c21a426) | Aug 02, 2019 |
| HP            | ProLiant DL60 Gen9          | Server      | [140daf886e](https://linux-hardware.org/?probe=140daf886e) | Jul 24, 2019 |
| ASUSTek       | H81M-C                      | Desktop     | [38a96dff85](https://linux-hardware.org/?probe=38a96dff85) | Jul 02, 2019 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [62b0b05a66](https://linux-hardware.org/?probe=62b0b05a66) | Jul 01, 2019 |
| ASUSTek       | X450CP                      | Notebook    | [2931234c98](https://linux-hardware.org/?probe=2931234c98) | May 02, 2019 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [c7b00947af](https://linux-hardware.org/?probe=c7b00947af) | Apr 30, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [35e3cab7fd](https://linux-hardware.org/?probe=35e3cab7fd) | Apr 24, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3783735e9b](https://linux-hardware.org/?probe=3783735e9b) | Apr 23, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [672cf7aa7f](https://linux-hardware.org/?probe=672cf7aa7f) | Apr 20, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [5202aae85e](https://linux-hardware.org/?probe=5202aae85e) | Feb 26, 2019 |
| ASUSTek       | X101H                       | Notebook    | [bfa018d76d](https://linux-hardware.org/?probe=bfa018d76d) | Jan 21, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [323f6e2eeb](https://linux-hardware.org/?probe=323f6e2eeb) | Dec 17, 2018 |
| ASRock        | X79 Extreme9                | Desktop     | [c96c05c47b](https://linux-hardware.org/?probe=c96c05c47b) | Nov 30, 2018 |
| Dell          | XPS L521X                   | Notebook    | [3f3c8f2571](https://linux-hardware.org/?probe=3f3c8f2571) | Nov 25, 2018 |
| Dell          | Latitude E6520              | Notebook    | [166d529d12](https://linux-hardware.org/?probe=166d529d12) | Nov 12, 2018 |
| HP            | 2820h                       | Desktop     | [1f42af0283](https://linux-hardware.org/?probe=1f42af0283) | Dec 17, 2017 |
| Dell          | XPS L412Z                   | Notebook    | [8381b26177](https://linux-hardware.org/?probe=8381b26177) | Jan 27, 2017 |
| Dell          | XPS L412Z                   | Notebook    | [799ee32fce](https://linux-hardware.org/?probe=799ee32fce) | Jan 21, 2017 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 59        | 19.03%  |
| Ubuntu 18.04                 | 23        | 7.42%   |
| Pop!_OS 20.10                | 10        | 3.23%   |
| OpenMandriva 4.2             | 10        | 3.23%   |
| Pop!_OS 21.04                | 9         | 2.9%    |
| Pop!_OS 20.04                | 8         | 2.58%   |
| KDE neon 20.04               | 8         | 2.58%   |
| Fedora 33                    | 8         | 2.58%   |
| Ubuntu 19.04                 | 7         | 2.26%   |
| OpenMandriva 4.50            | 7         | 2.26%   |
| OpenMandriva 4.3             | 6         | 1.94%   |
| Linux Mint 19.3              | 6         | 1.94%   |
| Fedora 34                    | 6         | 1.94%   |
| ArcoLinux Rolling            | 6         | 1.94%   |
| Zorin 16                     | 5         | 1.61%   |
| Ubuntu 16.04                 | 5         | 1.61%   |
| Arch                         | 5         | 1.61%   |
| Zorin 15                     | 4         | 1.29%   |
| Ubuntu 21.04                 | 4         | 1.29%   |
| Ubuntu 20.10                 | 4         | 1.29%   |
| Ubuntu 19.10                 | 4         | 1.29%   |
| Manjaro                      | 4         | 1.29%   |
| Linux Mint 20.2              | 4         | 1.29%   |
| Elementary 5.1.7             | 4         | 1.29%   |
| Xubuntu 18.04                | 3         | 0.97%   |
| Ubuntu 21.10                 | 3         | 0.97%   |
| Linux Mint 20.1              | 3         | 0.97%   |
| Android                      | 3         | 0.97%   |
| Ubuntu 22.04                 | 2         | 0.65%   |
| Pop!_OS 22.04                | 2         | 0.65%   |
| Pop!_OS 21.10                | 2         | 0.65%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.65%   |
| Manjaro 21.2.6               | 2         | 0.65%   |
| Manjaro 21.0.7               | 2         | 0.65%   |
| Manjaro 21.0.5               | 2         | 0.65%   |
| Lubuntu 19.10                | 2         | 0.65%   |
| Lubuntu 18.04                | 2         | 0.65%   |
| Linux Mint 20.3              | 2         | 0.65%   |
| Linux Mint 18.3              | 2         | 0.65%   |
| Kali 2020.4                  | 2         | 0.65%   |
| Fedora 35                    | 2         | 0.65%   |
| Fedora 32                    | 2         | 0.65%   |
| EndeavourOS Rolling          | 2         | 0.65%   |
| Elementary 6.1               | 2         | 0.65%   |
| Elementary 5.1.4             | 2         | 0.65%   |
| Debian 11                    | 2         | 0.65%   |
| CentOS 8                     | 2         | 0.65%   |
| Arch Rolling                 | 2         | 0.65%   |
| Zorin 12                     | 1         | 0.32%   |
| Xubuntu 19.10                | 1         | 0.32%   |
| Xero Rolling                 | 1         | 0.32%   |
| Ubuntu MATE 20.04            | 1         | 0.32%   |
| Ubuntu Budgie 21.10          | 1         | 0.32%   |
| Ubuntu Budgie 20.04          | 1         | 0.32%   |
| ROSA R8                      | 1         | 0.32%   |
| ROSA R10                     | 1         | 0.32%   |
| Rocky Linux 8.4              | 1         | 0.32%   |
| Raspbian 10                  | 1         | 0.32%   |
| Peppermint 10                | 1         | 0.32%   |
| MX 21                        | 1         | 0.32%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 108       | 36.61%  |
| Pop!_OS       | 27        | 9.15%   |
| OpenMandriva  | 22        | 7.46%   |
| Linux Mint    | 17        | 5.76%   |
| Fedora        | 17        | 5.76%   |
| Manjaro       | 13        | 4.41%   |
| Zorin         | 10        | 3.39%   |
| KDE neon      | 9         | 3.05%   |
| Elementary    | 9         | 3.05%   |
| Endless       | 7         | 2.37%   |
| Arch          | 7         | 2.37%   |
| Lubuntu       | 6         | 2.03%   |
| ArcoLinux     | 6         | 2.03%   |
| Kali          | 5         | 1.69%   |
| Xubuntu       | 4         | 1.36%   |
| EndeavourOS   | 3         | 1.02%   |
| Android       | 3         | 1.02%   |
| Ubuntu Budgie | 2         | 0.68%   |
| ROSA          | 2         | 0.68%   |
| openSUSE      | 2         | 0.68%   |
| Kubuntu       | 2         | 0.68%   |
| Debian        | 2         | 0.68%   |
| CentOS        | 2         | 0.68%   |
| Xero          | 1         | 0.34%   |
| Ubuntu MATE   | 1         | 0.34%   |
| Rocky Linux   | 1         | 0.34%   |
| Raspbian      | 1         | 0.34%   |
| Peppermint    | 1         | 0.34%   |
| MX            | 1         | 0.34%   |
| LMDE          | 1         | 0.34%   |
| Linux Lite    | 1         | 0.34%   |
| Gentoo        | 1         | 0.34%   |
| BuildRoot     | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002      | 9         | 2.71%   |
| 5.4.0-58-generic              | 8         | 2.41%   |
| 5.4.0-42-generic              | 8         | 2.41%   |
| 5.11.0-7620-generic           | 6         | 1.81%   |
| 5.12.4-desktop-1omv4050       | 5         | 1.51%   |
| 5.11.0-27-generic             | 5         | 1.51%   |
| 5.4.0-7634-generic            | 4         | 1.2%    |
| 5.4.0-40-generic              | 4         | 1.2%    |
| 5.16.7-desktop-1omv4003       | 4         | 1.2%    |
| 5.0.0-37-generic              | 4         | 1.2%    |
| 5.8.0-7642-generic            | 3         | 0.9%    |
| 5.8.0-7630-generic            | 3         | 0.9%    |
| 5.4.0-54-generic              | 3         | 0.9%    |
| 5.4.0-52-generic              | 3         | 0.9%    |
| 5.4.0-48-generic              | 3         | 0.9%    |
| 5.4.0-37-generic              | 3         | 0.9%    |
| 5.3.0-53-generic              | 3         | 0.9%    |
| 5.3.0-46-generic              | 3         | 0.9%    |
| 5.13.0-7614-generic           | 3         | 0.9%    |
| 5.13.0-22-generic             | 3         | 0.9%    |
| 5.11.0-7614-generic           | 3         | 0.9%    |
| 5.11.0-46-generic             | 3         | 0.9%    |
| 5.11.0-43-generic             | 3         | 0.9%    |
| 5.11.0-34-generic             | 3         | 0.9%    |
| 5.0.0-32-generic              | 3         | 0.9%    |
| 5.0.0-25-generic              | 3         | 0.9%    |
| 5.0.0-23-generic              | 3         | 0.9%    |
| 4.15.0-76-generic             | 3         | 0.9%    |
| 4.15.0-45-generic             | 3         | 0.9%    |
| 5.9.0-kali1-amd64             | 2         | 0.6%    |
| 5.8.0-53-generic              | 2         | 0.6%    |
| 5.8.0-45-generic              | 2         | 0.6%    |
| 5.8.0-44-generic              | 2         | 0.6%    |
| 5.8.0-41-generic              | 2         | 0.6%    |
| 5.4.0-89-generic              | 2         | 0.6%    |
| 5.4.0-77-generic              | 2         | 0.6%    |
| 5.4.0-74-generic              | 2         | 0.6%    |
| 5.4.0-64-generic              | 2         | 0.6%    |
| 5.4.0-45-generic              | 2         | 0.6%    |
| 5.4.0-39-generic              | 2         | 0.6%    |
| 5.4.0-33-generic              | 2         | 0.6%    |
| 5.4.0-29-generic              | 2         | 0.6%    |
| 5.3.0-51-generic              | 2         | 0.6%    |
| 5.3.0-40-generic              | 2         | 0.6%    |
| 5.3.0-29-generic              | 2         | 0.6%    |
| 5.3.0-24-generic              | 2         | 0.6%    |
| 5.3.0-23-generic              | 2         | 0.6%    |
| 5.3.0-18-generic              | 2         | 0.6%    |
| 5.17.5-76051705-generic       | 2         | 0.6%    |
| 5.16.3-desktop-2omv4050       | 2         | 0.6%    |
| 5.15.0-39-generic             | 2         | 0.6%    |
| 5.13.0-30-generic             | 2         | 0.6%    |
| 5.12.7-desktop-clang-1omv4003 | 2         | 0.6%    |
| 5.12.15-300.fc34.x86_64       | 2         | 0.6%    |
| 5.11.0-41-generic             | 2         | 0.6%    |
| 5.11.0-40-generic             | 2         | 0.6%    |
| 5.10.79-1-lts                 | 2         | 0.6%    |
| 5.10.42-1-MANJARO             | 2         | 0.6%    |
| 5.10.13-200.fc33.x86_64       | 2         | 0.6%    |
| 5.10.0-13-amd64               | 2         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 68        | 21.86%  |
| 5.11.0  | 28        | 9%      |
| 5.8.0   | 26        | 8.36%   |
| 4.15.0  | 20        | 6.43%   |
| 5.3.0   | 19        | 6.11%   |
| 5.0.0   | 18        | 5.79%   |
| 5.13.0  | 15        | 4.82%   |
| 5.10.14 | 9         | 2.89%   |
| 4.18.0  | 6         | 1.93%   |
| 5.12.4  | 5         | 1.61%   |
| 5.16.7  | 4         | 1.29%   |
| 5.10.0  | 4         | 1.29%   |
| 5.9.0   | 3         | 0.96%   |
| 5.17.1  | 3         | 0.96%   |
| 5.16.15 | 3         | 0.96%   |
| 5.15.0  | 3         | 0.96%   |
| 5.9.1   | 2         | 0.64%   |
| 5.17.5  | 2         | 0.64%   |
| 5.16.3  | 2         | 0.64%   |
| 5.14.18 | 2         | 0.64%   |
| 5.14.0  | 2         | 0.64%   |
| 5.13.13 | 2         | 0.64%   |
| 5.12.9  | 2         | 0.64%   |
| 5.12.7  | 2         | 0.64%   |
| 5.12.15 | 2         | 0.64%   |
| 5.11.18 | 2         | 0.64%   |
| 5.10.79 | 2         | 0.64%   |
| 5.10.42 | 2         | 0.64%   |
| 5.10.13 | 2         | 0.64%   |
| 5.9.8   | 1         | 0.32%   |
| 5.9.15  | 1         | 0.32%   |
| 5.9.14  | 1         | 0.32%   |
| 5.8.8   | 1         | 0.32%   |
| 5.8.6   | 1         | 0.32%   |
| 5.8.4   | 1         | 0.32%   |
| 5.8.17  | 1         | 0.32%   |
| 5.8.16  | 1         | 0.32%   |
| 5.8.11  | 1         | 0.32%   |
| 5.8.10  | 1         | 0.32%   |
| 5.7.7   | 1         | 0.32%   |
| 5.7.0   | 1         | 0.32%   |
| 5.6.8   | 1         | 0.32%   |
| 5.6.16  | 1         | 0.32%   |
| 5.18.7  | 1         | 0.32%   |
| 5.18.0  | 1         | 0.32%   |
| 5.17.3  | 1         | 0.32%   |
| 5.16.19 | 1         | 0.32%   |
| 5.16.0  | 1         | 0.32%   |
| 5.15.8  | 1         | 0.32%   |
| 5.15.38 | 1         | 0.32%   |
| 5.15.35 | 1         | 0.32%   |
| 5.15.15 | 1         | 0.32%   |
| 5.15.13 | 1         | 0.32%   |
| 5.15.12 | 1         | 0.32%   |
| 5.15.11 | 1         | 0.32%   |
| 5.14.3  | 1         | 0.32%   |
| 5.14.12 | 1         | 0.32%   |
| 5.14.11 | 1         | 0.32%   |
| 5.14.10 | 1         | 0.32%   |
| 5.13.12 | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 68        | 22.08%  |
| 5.8     | 33        | 10.71%  |
| 5.11    | 33        | 10.71%  |
| 5.10    | 23        | 7.47%   |
| 4.15    | 20        | 6.49%   |
| 5.3     | 19        | 6.17%   |
| 5.13    | 18        | 5.84%   |
| 5.0     | 18        | 5.84%   |
| 5.12    | 13        | 4.22%   |
| 5.16    | 11        | 3.57%   |
| 5.15    | 10        | 3.25%   |
| 5.9     | 8         | 2.6%    |
| 5.14    | 8         | 2.6%    |
| 5.17    | 6         | 1.95%   |
| 4.18    | 6         | 1.95%   |
| 5.7     | 2         | 0.65%   |
| 5.6     | 2         | 0.65%   |
| 5.18    | 2         | 0.65%   |
| 3.18    | 2         | 0.65%   |
| 4.9     | 1         | 0.32%   |
| 4.4     | 1         | 0.32%   |
| 4.19    | 1         | 0.32%   |
| 4.10    | 1         | 0.32%   |
| 4.1     | 1         | 0.32%   |
| 3.10    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 272       | 96.45%  |
| i686   | 5         | 1.77%   |
| armv8l | 3         | 1.06%   |
| armv7l | 2         | 0.71%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 135       | 46.08%  |
| KDE5          | 45        | 15.36%  |
| Unknown       | 38        | 12.97%  |
| XFCE          | 20        | 6.83%   |
| X-Cinnamon    | 13        | 4.44%   |
| KDE           | 12        | 4.1%    |
| Pantheon      | 9         | 3.07%   |
| MATE          | 8         | 2.73%   |
| LXQt          | 4         | 1.37%   |
| Unity         | 2         | 0.68%   |
| Budgie        | 2         | 0.68%   |
| Peppermint    | 1         | 0.34%   |
| Openbox       | 1         | 0.34%   |
| LXDE          | 1         | 0.34%   |
| GNOME Classic | 1         | 0.34%   |
| Cinnamon      | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 238       | 81.79%  |
| Wayland | 27        | 9.28%   |
| Unknown | 20        | 6.87%   |
| Tty     | 6         | 2.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 185       | 64.24%  |
| SDDM    | 45        | 15.63%  |
| GDM     | 28        | 9.72%   |
| LightDM | 14        | 4.86%   |
| GDM3    | 11        | 3.82%   |
| TDM     | 5         | 1.74%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 209       | 73.08%  |
| Unknown | 31        | 10.84%  |
| en_GB   | 22        | 7.69%   |
| en_SG   | 11        | 3.85%   |
| en_AU   | 3         | 1.05%   |
| zh_CN   | 2         | 0.7%    |
| en_MY   | 2         | 0.7%    |
| C       | 2         | 0.7%    |
| ms_MY   | 1         | 0.35%   |
| ja_JP   | 1         | 0.35%   |
| id_ID   | 1         | 0.35%   |
| en_HK   | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 163       | 57.19%  |
| EFI  | 122       | 42.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 232       | 80.28%  |
| Overlay | 18        | 6.23%   |
| Btrfs   | 16        | 5.54%   |
| Unknown | 12        | 4.15%   |
| Xfs     | 6         | 2.08%   |
| Zfs     | 2         | 0.69%   |
| Ext2    | 2         | 0.69%   |
| Ext3    | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 191       | 67.02%  |
| GPT     | 55        | 19.3%   |
| MBR     | 39        | 13.68%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 236       | 81.94%  |
| Yes       | 52        | 18.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 196       | 68.29%  |
| Yes       | 91        | 31.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 55        | 19.5%   |
| Dell                    | 51        | 18.09%  |
| Hewlett-Packard         | 39        | 13.83%  |
| Lenovo                  | 25        | 8.87%   |
| Gigabyte Technology     | 18        | 6.38%   |
| Acer                    | 18        | 6.38%   |
| MSI                     | 16        | 5.67%   |
| Intel                   | 12        | 4.26%   |
| Apple                   | 7         | 2.48%   |
| Biostar                 | 5         | 1.77%   |
| Unknown                 | 5         | 1.77%   |
| ASRock                  | 4         | 1.42%   |
| Sony                    | 3         | 1.06%   |
| Fujitsu                 | 3         | 1.06%   |
| Raspberry Pi Foundation | 2         | 0.71%   |
| ILLEGEAR                | 2         | 0.71%   |
| HUAWEI                  | 2         | 0.71%   |
| ECS                     | 2         | 0.71%   |
| Toshiba                 | 1         | 0.35%   |
| Timi                    | 1         | 0.35%   |
| Teclast                 | 1         | 0.35%   |
| System76                | 1         | 0.35%   |
| Supermicro              | 1         | 0.35%   |
| SNS Network (M)         | 1         | 0.35%   |
| Shuttle                 | 1         | 0.35%   |
| HONOR                   | 1         | 0.35%   |
| Chuwi                   | 1         | 0.35%   |
| BUSH                    | 1         | 0.35%   |
| AZW                     | 1         | 0.35%   |
| AMI                     | 1         | 0.35%   |
| Acidanthera             | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS All Series                       | 6         | 2.13%   |
| Intel DH61WW AAG23116-204             | 5         | 1.77%   |
| Unknown                               | 5         | 1.77%   |
| HP Notebook                           | 4         | 1.42%   |
| MSI MS-7817                           | 3         | 1.06%   |
| Intel DH61WW AAG23116-300             | 3         | 1.06%   |
| Gigabyte B85M-D3H                     | 3         | 1.06%   |
| MSI MS-7C81                           | 2         | 0.71%   |
| MSI MS-7C52                           | 2         | 0.71%   |
| HP Pavilion dv6                       | 2         | 0.71%   |
| HP Laptop 15-bs0xx                    | 2         | 0.71%   |
| HP EliteBook 8470p                    | 2         | 0.71%   |
| Dell XPS 8940                         | 2         | 0.71%   |
| Dell XPS 15 7590                      | 2         | 0.71%   |
| Dell OptiPlex 990                     | 2         | 0.71%   |
| Dell OptiPlex 755                     | 2         | 0.71%   |
| Dell Latitude E6520                   | 2         | 0.71%   |
| Dell Latitude E6440                   | 2         | 0.71%   |
| Biostar G41D3C                        | 2         | 0.71%   |
| ASUS P8Z77-V LX                       | 2         | 0.71%   |
| ASUS K45VD                            | 2         | 0.71%   |
| ASUS K43SD                            | 2         | 0.71%   |
| Apple MacBookPro8,1                   | 2         | 0.71%   |
| Toshiba dynabook Satellite B552/H     | 1         | 0.35%   |
| Timi RedmiBook 14 II                  | 1         | 0.35%   |
| Teclast F5                            | 1         | 0.35%   |
| System76 Galago Pro                   | 1         | 0.35%   |
| Supermicro PIO-5038K-I-IN001          | 1         | 0.35%   |
| Sony VPCSB26FG                        | 1         | 0.35%   |
| Sony VPCEA42EG                        | 1         | 0.35%   |
| Sony VGN-Z27GN_X                      | 1         | 0.35%   |
| SNS Network (M) JOI Book 150          | 1         | 0.35%   |
| Shuttle DH170                         | 1         | 0.35%   |
| RPi Raspberry Pi 4 Model B Rev 1.2    | 1         | 0.35%   |
| RPi Raspberry Pi 4 Model B Rev 1.1    | 1         | 0.35%   |
| MSI Prestige 15 A10SC                 | 1         | 0.35%   |
| MSI MS-7D42                           | 1         | 0.35%   |
| MSI MS-7C02                           | 1         | 0.35%   |
| MSI MS-7B89                           | 1         | 0.35%   |
| MSI MS-7979                           | 1         | 0.35%   |
| MSI Modern 14 B5M                     | 1         | 0.35%   |
| MSI GT70 2OC/2OD                      | 1         | 0.35%   |
| MSI GP70 2PE                          | 1         | 0.35%   |
| MSI GL62M 7RDX                        | 1         | 0.35%   |
| Lenovo Yoga 720-13IKB 80X6            | 1         | 0.35%   |
| Lenovo Yoga 500-15IBD 80N6            | 1         | 0.35%   |
| Lenovo XiaoXinAir 14+ ACN 2021 82L7   | 1         | 0.35%   |
| Lenovo U310                           | 1         | 0.35%   |
| Lenovo ThinkStation S10 6483CTO       | 1         | 0.35%   |
| Lenovo ThinkStation P620 30E0S0E000   | 1         | 0.35%   |
| Lenovo ThinkStation P500 30A6S1B50X   | 1         | 0.35%   |
| Lenovo ThinkPad X220 42912WA          | 1         | 0.35%   |
| Lenovo ThinkPad X201 3626RZ4          | 1         | 0.35%   |
| Lenovo ThinkPad X201 3323LWA          | 1         | 0.35%   |
| Lenovo ThinkPad X131e 33682YU         | 1         | 0.35%   |
| Lenovo ThinkPad X120e 0611CTO         | 1         | 0.35%   |
| Lenovo ThinkPad T480 20L6S1RN00       | 1         | 0.35%   |
| Lenovo ThinkPad T460 20FMA0J6MY       | 1         | 0.35%   |
| Lenovo ThinkPad L15 Gen 2a 20X7CTO1WW | 1         | 0.35%   |
| Lenovo ThinkPad E590 20NBS03S00       | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Dell Inspiron                | 14        | 4.96%   |
| Dell Latitude                | 13        | 4.61%   |
| Acer Aspire                  | 12        | 4.26%   |
| Lenovo ThinkPad              | 9         | 3.19%   |
| Intel DH61WW                 | 8         | 2.84%   |
| HP Pavilion                  | 8         | 2.84%   |
| Dell OptiPlex                | 8         | 2.84%   |
| HP Compaq                    | 7         | 2.48%   |
| Dell XPS                     | 7         | 2.48%   |
| Dell Precision               | 6         | 2.13%   |
| ASUS All                     | 6         | 2.13%   |
| HP EliteBook                 | 5         | 1.77%   |
| Unknown                      | 5         | 1.77%   |
| HP Notebook                  | 4         | 1.42%   |
| ASUS TUF                     | 4         | 1.42%   |
| ASUS ROG                     | 4         | 1.42%   |
| MSI MS-7817                  | 3         | 1.06%   |
| Lenovo ThinkStation          | 3         | 1.06%   |
| HP Laptop                    | 3         | 1.06%   |
| Gigabyte B85M-D3H            | 3         | 1.06%   |
| Fujitsu LIFEBOOK             | 3         | 1.06%   |
| ASUS VivoBook                | 3         | 1.06%   |
| ASUS P8B75-M                 | 3         | 1.06%   |
| Apple MacBookPro8            | 3         | 1.06%   |
| RPi Raspberry                | 2         | 0.71%   |
| MSI MS-7C81                  | 2         | 0.71%   |
| MSI MS-7C52                  | 2         | 0.71%   |
| Lenovo Yoga                  | 2         | 0.71%   |
| Lenovo ThinkCentre           | 2         | 0.71%   |
| Lenovo IdeaPad               | 2         | 0.71%   |
| HP ProBook                   | 2         | 0.71%   |
| Gigabyte B450M               | 2         | 0.71%   |
| Biostar G41D3C               | 2         | 0.71%   |
| ASUS PRIME                   | 2         | 0.71%   |
| ASUS P8Z77-V                 | 2         | 0.71%   |
| ASUS K45VD                   | 2         | 0.71%   |
| ASUS K43SD                   | 2         | 0.71%   |
| Acer Veriton                 | 2         | 0.71%   |
| Toshiba dynabook             | 1         | 0.35%   |
| Timi RedmiBook               | 1         | 0.35%   |
| Teclast F5                   | 1         | 0.35%   |
| System76 Galago              | 1         | 0.35%   |
| Supermicro PIO-5038K-I-IN001 | 1         | 0.35%   |
| Sony VPCSB26FG               | 1         | 0.35%   |
| Sony VPCEA42EG               | 1         | 0.35%   |
| Sony VGN-Z27GN               | 1         | 0.35%   |
| SNS Network (M) JOI          | 1         | 0.35%   |
| Shuttle DH170                | 1         | 0.35%   |
| MSI Prestige                 | 1         | 0.35%   |
| MSI MS-7D42                  | 1         | 0.35%   |
| MSI MS-7C02                  | 1         | 0.35%   |
| MSI MS-7B89                  | 1         | 0.35%   |
| MSI MS-7979                  | 1         | 0.35%   |
| MSI Modern                   | 1         | 0.35%   |
| MSI GT70                     | 1         | 0.35%   |
| MSI GP70                     | 1         | 0.35%   |
| MSI GL62M                    | 1         | 0.35%   |
| Lenovo XiaoXinAir            | 1         | 0.35%   |
| Lenovo U310                  | 1         | 0.35%   |
| Lenovo Legion                | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 34        | 12.06%  |
| 2013    | 31        | 10.99%  |
| 2012    | 25        | 8.87%   |
| 2018    | 24        | 8.51%   |
| 2019    | 23        | 8.16%   |
| 2020    | 21        | 7.45%   |
| 2010    | 18        | 6.38%   |
| 2015    | 17        | 6.03%   |
| 2021    | 16        | 5.67%   |
| 2017    | 14        | 4.96%   |
| 2014    | 13        | 4.61%   |
| 2009    | 12        | 4.26%   |
| 2008    | 11        | 3.9%    |
| 2007    | 8         | 2.84%   |
| 2016    | 7         | 2.48%   |
| Unknown | 5         | 1.77%   |
| 2022    | 2         | 0.71%   |
| 2006    | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 148       | 52.48%  |
| Desktop        | 111       | 39.36%  |
| Convertible    | 8         | 2.84%   |
| All in one     | 5         | 1.77%   |
| Phone          | 3         | 1.06%   |
| System on chip | 2         | 0.71%   |
| Tablet         | 2         | 0.71%   |
| Server         | 2         | 0.71%   |
| Mini pc        | 1         | 0.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 265       | 93.97%  |
| Enabled  | 17        | 6.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 281       | 99.65%  |
| Yes  | 1         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 69        | 24.21%  |
| 8.01-16.0   | 59        | 20.7%   |
| 3.01-4.0    | 58        | 20.35%  |
| 16.01-24.0  | 45        | 15.79%  |
| 32.01-64.0  | 21        | 7.37%   |
| 1.01-2.0    | 15        | 5.26%   |
| 2.01-3.0    | 6         | 2.11%   |
| 64.01-256.0 | 6         | 2.11%   |
| 24.01-32.0  | 4         | 1.4%    |
| 0.51-1.0    | 2         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 109       | 34.94%  |
| 2.01-3.0   | 88        | 28.21%  |
| 3.01-4.0   | 45        | 14.42%  |
| 4.01-8.0   | 30        | 9.62%   |
| 0.51-1.0   | 27        | 8.65%   |
| 8.01-16.0  | 8         | 2.56%   |
| 0.01-0.5   | 3         | 0.96%   |
| 24.01-32.0 | 1         | 0.32%   |
| Unknown    | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 164       | 56.75%  |
| 2      | 86        | 29.76%  |
| 3      | 17        | 5.88%   |
| 5      | 8         | 2.77%   |
| 4      | 8         | 2.77%   |
| 7      | 3         | 1.04%   |
| 6      | 2         | 0.69%   |
| 8      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 172       | 60.78%  |
| Yes       | 111       | 39.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 236       | 83.69%  |
| No        | 46        | 16.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 230       | 80.99%  |
| No        | 54        | 19.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 61.27%  |
| No        | 110       | 38.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Malaysia | 282       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 100       | 32.89%  |
| Petaling Jaya          | 35        | 11.51%  |
| Shah Alam              | 13        | 4.28%   |
| Puchong Batu Dua Belas | 12        | 3.95%   |
| Johor Bahru            | 11        | 3.62%   |
| Sungai Buloh           | 9         | 2.96%   |
| Subang Jaya            | 8         | 2.63%   |
| Seremban               | 7         | 2.3%    |
| Kota Kinabalu          | 7         | 2.3%    |
| Kajang                 | 6         | 1.97%   |
| George Town            | 6         | 1.97%   |
| Malacca                | 5         | 1.64%   |
| Kota Bharu             | 5         | 1.64%   |
| Tawau                  | 4         | 1.32%   |
| Kulim                  | 4         | 1.32%   |
| Kulai                  | 4         | 1.32%   |
| Ipoh                   | 4         | 1.32%   |
| Cyberjaya              | 4         | 1.32%   |
| Butterworth            | 4         | 1.32%   |
| Ampang                 | 4         | 1.32%   |
| Sungai Petani          | 3         | 0.99%   |
| Putrajaya              | 3         | 0.99%   |
| Marabu                 | 3         | 0.99%   |
| Kuching                | 3         | 0.99%   |
| Skudai                 | 2         | 0.66%   |
| Seri Kembangan         | 2         | 0.66%   |
| Rawang                 | 2         | 0.66%   |
| Long Seridan           | 2         | 0.66%   |
| Klang                  | 2         | 0.66%   |
| Cheras                 | 2         | 0.66%   |
| Bukit Mertajam         | 2         | 0.66%   |
| Ayer Itam              | 2         | 0.66%   |
| Taiping                | 1         | 0.33%   |
| Sibu                   | 1         | 0.33%   |
| Sepang                 | 1         | 0.33%   |
| Penampang              | 1         | 0.33%   |
| Pasir Gudang           | 1         | 0.33%   |
| Padang Serai           | 1         | 0.33%   |
| Muar town              | 1         | 0.33%   |
| Labuan                 | 1         | 0.33%   |
| Kuantan                | 1         | 0.33%   |
| Kuala Terengganu       | 1         | 0.33%   |
| Kuala Nerang           | 1         | 0.33%   |
| Kuala Kangsar          | 1         | 0.33%   |
| Kota Tinggi            | 1         | 0.33%   |
| Kamunting              | 1         | 0.33%   |
| Jitra                  | 1         | 0.33%   |
| Hutan Melintang        | 1         | 0.33%   |
| Gambang                | 1         | 0.33%   |
| Cukai                  | 1         | 0.33%   |
| Bukit Asahan           | 1         | 0.33%   |
| Bayan Lepas            | 1         | 0.33%   |
| Batu Caves             | 1         | 0.33%   |
| Bandar Tenggara        | 1         | 0.33%   |
| Alor Star              | 1         | 0.33%   |
| Ajil                   | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 81        | 108    | 19.01%  |
| WDC                       | 72        | 128    | 16.9%   |
| Kingston                  | 37        | 51     | 8.69%   |
| Toshiba                   | 34        | 41     | 7.98%   |
| Samsung Electronics       | 34        | 51     | 7.98%   |
| Unknown                   | 20        | 28     | 4.69%   |
| SanDisk                   | 16        | 23     | 3.76%   |
| HGST                      | 13        | 16     | 3.05%   |
| Intel                     | 10        | 14     | 2.35%   |
| A-DATA Technology         | 10        | 13     | 2.35%   |
| Crucial                   | 8         | 15     | 1.88%   |
| Apacer                    | 8         | 12     | 1.88%   |
| SK hynix                  | 6         | 6      | 1.41%   |
| Phison                    | 6         | 8      | 1.41%   |
| Hitachi                   | 6         | 10     | 1.41%   |
| Micron Technology         | 5         | 9      | 1.17%   |
| China                     | 5         | 5      | 1.17%   |
| Transcend                 | 4         | 4      | 0.94%   |
| Silicon Motion            | 4         | 5      | 0.94%   |
| Patriot                   | 4         | 4      | 0.94%   |
| KIOXIA                    | 4         | 4      | 0.94%   |
| SPCC                      | 3         | 4      | 0.7%    |
| Hewlett-Packard           | 3         | 3      | 0.7%    |
| XPG                       | 2         | 3      | 0.47%   |
| Verbatim                  | 2         | 2      | 0.47%   |
| TO Exter                  | 2         | 4      | 0.47%   |
| PNY                       | 2         | 2      | 0.47%   |
| Plextor                   | 2         | 2      | 0.47%   |
| Colorful                  | 2         | 2      | 0.47%   |
| winstar                   | 1         | 1      | 0.23%   |
| Teclast                   | 1         | 1      | 0.23%   |
| SATAFIRM                  | 1         | 1      | 0.23%   |
| Netac                     | 1         | 1      | 0.23%   |
| Morebeck-S100             | 1         | 1      | 0.23%   |
| Micron/Crucial Technology | 1         | 1      | 0.23%   |
| Maxtor                    | 1         | 1      | 0.23%   |
| MAX                       | 1         | 1      | 0.23%   |
| LS                        | 1         | 1      | 0.23%   |
| KIOXIA-EXCERIA            | 1         | 3      | 0.23%   |
| Kingmax                   | 1         | 1      | 0.23%   |
| Kingchuxing               | 1         | 1      | 0.23%   |
| JMicron Technology        | 1         | 1      | 0.23%   |
| Hikvision                 | 1         | 2      | 0.23%   |
| Gigabyte Technology       | 1         | 1      | 0.23%   |
| GAMER                     | 1         | 1      | 0.23%   |
| Fujitsu                   | 1         | 1      | 0.23%   |
| External                  | 1         | 1      | 0.23%   |
| ASMT                      | 1         | 2      | 0.23%   |
| Apple                     | 1         | 2      | 0.23%   |
| AGI                       | 1         | 2      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 11        | 2.32%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 5         | 1.05%   |
| Seagate ST380815AS 80GB            | 5         | 1.05%   |
| WDC WD20EZRX-00D8PB0 2TB           | 4         | 0.84%   |
| Unknown MMC Card  32GB             | 4         | 0.84%   |
| Toshiba MQ04ABF100 1TB             | 4         | 0.84%   |
| Toshiba MQ01ABD100 1TB             | 4         | 0.84%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 0.84%   |
| Seagate ST3160815AS 160GB          | 4         | 0.84%   |
| Seagate ST1000DM010-2EP102 1TB     | 4         | 0.84%   |
| SanDisk SSD PLUS 240GB             | 4         | 0.84%   |
| Samsung SSD 860 EVO 250GB          | 4         | 0.84%   |
| Samsung HD103SJ 1TB                | 4         | 0.84%   |
| HGST HTS545050A7E680 500GB         | 4         | 0.84%   |
| Apacer AS340 120GB SSD             | 4         | 0.84%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 3         | 0.63%   |
| Unknown MMC Card  64GB             | 3         | 0.63%   |
| Unknown MMC Card                   | 3         | 0.63%   |
| Seagate ST9320325AS 320GB          | 3         | 0.63%   |
| Seagate ST320LT020-9YG142 320GB    | 3         | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB     | 3         | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB     | 3         | 0.63%   |
| SanDisk NVMe SSD Drive 512GB       | 3         | 0.63%   |
| Kingston NVMe SSD Drive 500GB      | 3         | 0.63%   |
| Intel NVMe SSD Drive 512GB         | 3         | 0.63%   |
| HGST HTS721010A9E630 1TB           | 3         | 0.63%   |
| Crucial CT500MX500SSD1 500GB       | 3         | 0.63%   |
| Crucial CT250MX500SSD1 250GB       | 3         | 0.63%   |
| XPG NVMe SSD Drive 512GB           | 2         | 0.42%   |
| WDC WD800JD-22MSA1 80GB            | 2         | 0.42%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 2         | 0.42%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 2         | 0.42%   |
| WDC WD5000AAKX-001CA0 500GB        | 2         | 0.42%   |
| WDC WD40EZRZ-00WN9B0 4TB           | 2         | 0.42%   |
| WDC WD360ADFD-00NLR1 37GB          | 2         | 0.42%   |
| WDC WD3200AAKS-00SBA0 320GB        | 2         | 0.42%   |
| WDC WD2500AAKX-753CA1 250GB        | 2         | 0.42%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2         | 0.42%   |
| WDC WD10EZEX-00MFCA0 1TB           | 2         | 0.42%   |
| WDC WD10EZEX-00BN5A0 1TB           | 2         | 0.42%   |
| WDC PC SN730 NVMe 1024GB           | 2         | 0.42%   |
| Verbatim Vi550 S3 SSD 128GB        | 2         | 0.42%   |
| Unknown MMC Card  128GB            | 2         | 0.42%   |
| Toshiba NVMe SSD Drive 512GB       | 2         | 0.42%   |
| Toshiba MQ01ABD050 500GB           | 2         | 0.42%   |
| Toshiba MK5065GSXF 500GB           | 2         | 0.42%   |
| Toshiba DT01ACA050 500GB           | 2         | 0.42%   |
| TO Exter nal USB 3.0 256GB         | 2         | 0.42%   |
| SK hynix NVMe SSD Drive 512GB      | 2         | 0.42%   |
| Seagate ST9750420AS 752GB          | 2         | 0.42%   |
| Seagate ST9500325AS 500GB          | 2         | 0.42%   |
| Seagate ST500LM000-1EJ162 500GB    | 2         | 0.42%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 0.42%   |
| Seagate ST500DM002-1BC142 500GB    | 2         | 0.42%   |
| Seagate ST3500414CS 500GB          | 2         | 0.42%   |
| Seagate ST3408111AS 40GB           | 2         | 0.42%   |
| Seagate ST3320620A 320GB           | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 105    | 38.42%  |
| WDC                 | 63        | 119    | 31.03%  |
| Toshiba             | 29        | 35     | 14.29%  |
| HGST                | 13        | 16     | 6.4%    |
| Samsung Electronics | 9         | 15     | 4.43%   |
| Hitachi             | 6         | 10     | 2.96%   |
| Hewlett-Packard     | 2         | 2      | 0.99%   |
| Maxtor              | 1         | 1      | 0.49%   |
| Fujitsu             | 1         | 1      | 0.49%   |
| ASMT                | 1         | 2      | 0.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 30        | 39     | 22.9%   |
| Samsung Electronics | 15        | 23     | 11.45%  |
| SanDisk             | 12        | 15     | 9.16%   |
| Crucial             | 8         | 15     | 6.11%   |
| Apacer              | 8         | 12     | 6.11%   |
| A-DATA Technology   | 7         | 7      | 5.34%   |
| China               | 5         | 5      | 3.82%   |
| Transcend           | 4         | 4      | 3.05%   |
| Patriot             | 4         | 4      | 3.05%   |
| Micron Technology   | 4         | 8      | 3.05%   |
| Intel               | 4         | 7      | 3.05%   |
| WDC                 | 3         | 3      | 2.29%   |
| SPCC                | 3         | 4      | 2.29%   |
| Verbatim            | 2         | 2      | 1.53%   |
| Toshiba             | 2         | 2      | 1.53%   |
| TO Exter            | 2         | 4      | 1.53%   |
| Seagate             | 2         | 2      | 1.53%   |
| Plextor             | 2         | 2      | 1.53%   |
| Colorful            | 2         | 2      | 1.53%   |
| Teclast             | 1         | 1      | 0.76%   |
| SK hynix            | 1         | 1      | 0.76%   |
| SATAFIRM            | 1         | 1      | 0.76%   |
| PNY                 | 1         | 1      | 0.76%   |
| Netac               | 1         | 1      | 0.76%   |
| LS                  | 1         | 1      | 0.76%   |
| KIOXIA-EXCERIA      | 1         | 3      | 0.76%   |
| Kingmax             | 1         | 1      | 0.76%   |
| JMicron Technology  | 1         | 1      | 0.76%   |
| Hikvision           | 1         | 2      | 0.76%   |
| Hewlett-Packard     | 1         | 1      | 0.76%   |
| Apple               | 1         | 2      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 176       | 306    | 47.31%  |
| SSD     | 115       | 176    | 30.91%  |
| NVMe    | 55        | 87     | 14.78%  |
| MMC     | 18        | 25     | 4.84%   |
| Unknown | 8         | 10     | 2.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 236       | 473    | 72.84%  |
| NVMe | 55        | 86     | 16.98%  |
| MMC  | 18        | 25     | 5.56%   |
| SAS  | 15        | 20     | 4.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 185       | 297    | 62.08%  |
| 0.51-1.0   | 85        | 131    | 28.52%  |
| 1.01-2.0   | 22        | 39     | 7.38%   |
| 3.01-4.0   | 3         | 11     | 1.01%   |
| 4.01-10.0  | 2         | 3      | 0.67%   |
| 2.01-3.0   | 1         | 1      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 28.67%  |
| 251-500        | 73        | 24.33%  |
| 501-1000       | 37        | 12.33%  |
| 1-20           | 23        | 7.67%   |
| 51-100         | 21        | 7%      |
| 1001-2000      | 18        | 6%      |
| 21-50          | 17        | 5.67%   |
| More than 3000 | 10        | 3.33%   |
| Unknown        | 10        | 3.33%   |
| 2001-3000      | 5         | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 139       | 45.28%  |
| 21-50          | 44        | 14.33%  |
| 101-250        | 38        | 12.38%  |
| 51-100         | 29        | 9.45%   |
| 251-500        | 23        | 7.49%   |
| Unknown        | 10        | 3.26%   |
| 501-1000       | 9         | 2.93%   |
| 1001-2000      | 8         | 2.61%   |
| More than 3000 | 6         | 1.95%   |
| 2001-3000      | 1         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                   | 2         | 2      | 6.67%   |
| Seagate ST3500414CS 500GB                   | 2         | 3      | 6.67%   |
| WDC WD800AAJS-00PSA0 80GB                   | 1         | 1      | 3.33%   |
| WDC WD5000BPVT-00HXZT1 500GB                | 1         | 1      | 3.33%   |
| WDC WD5000AAKX-753CA1 500GB                 | 1         | 1      | 3.33%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1      | 3.33%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1      | 3.33%   |
| WDC WD10JPVT-75A1YT0 1TB                    | 1         | 1      | 3.33%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 1      | 3.33%   |
| WDC WD10EZEX-08WN4A0 1TB                    | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 3.33%   |
| Toshiba MK5065GSX 500GB                     | 1         | 1      | 3.33%   |
| Toshiba MK1059GSMP 1TB                      | 1         | 1      | 3.33%   |
| SPCC Solid State Disk 256GB                 | 1         | 1      | 3.33%   |
| Seagate ST9750420AS 752GB                   | 1         | 1      | 3.33%   |
| Seagate ST9250315AS 250GB                   | 1         | 1      | 3.33%   |
| Seagate ST380211AS 80GB                     | 1         | 1      | 3.33%   |
| Seagate ST3320620A 320GB                    | 1         | 1      | 3.33%   |
| Samsung Electronics SSD PM830 2.5 7mm 512GB | 1         | 1      | 3.33%   |
| Samsung Electronics HM160HI 160GB           | 1         | 1      | 3.33%   |
| Micron Technology 1100 SATA 512GB SSD       | 1         | 1      | 3.33%   |
| Kingston SV300S37A120G 120GB SSD            | 1         | 1      | 3.33%   |
| Hitachi HTS723232A7A364 320GB               | 1         | 1      | 3.33%   |
| Hitachi HTS547575A9E384 752GB               | 1         | 3      | 3.33%   |
| Hitachi HDS721050CLA362 500GB               | 1         | 1      | 3.33%   |
| HGST HTS541075A9E680 752GB                  | 1         | 1      | 3.33%   |
| HGST HTS541010A9E680 1TB                    | 1         | 1      | 3.33%   |
| Hewlett-Packard SSD S700 120GB              | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 27.59%  |
| Seagate             | 7         | 9      | 24.14%  |
| Toshiba             | 3         | 3      | 10.34%  |
| Hitachi             | 3         | 5      | 10.34%  |
| Samsung Electronics | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| SPCC                | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| Kingston            | 1         | 1      | 3.45%   |
| Hewlett-Packard     | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 33.33%  |
| Seagate             | 7         | 9      | 29.17%  |
| Toshiba             | 3         | 3      | 12.5%   |
| Hitachi             | 3         | 5      | 12.5%   |
| HGST                | 2         | 2      | 8.33%   |
| Samsung Electronics | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 28     | 82.14%  |
| SSD  | 5         | 5      | 17.86%  |

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
| Detected | 200       | 450    | 66.01%  |
| Works    | 76        | 121    | 25.08%  |
| Malfunc  | 27        | 33     | 8.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 214       | 65.85%  |
| AMD                          | 33        | 10.15%  |
| Samsung Electronics          | 11        | 3.38%   |
| SanDisk                      | 10        | 3.08%   |
| Phison Electronics           | 8         | 2.46%   |
| Nvidia                       | 7         | 2.15%   |
| Kingston Technology Company  | 7         | 2.15%   |
| SK hynix                     | 5         | 1.54%   |
| Silicon Motion               | 5         | 1.54%   |
| Marvell Technology Group     | 4         | 1.23%   |
| KIOXIA                       | 4         | 1.23%   |
| ASMedia Technology           | 4         | 1.23%   |
| Toshiba America Info Systems | 3         | 0.92%   |
| JMicron Technology           | 3         | 0.92%   |
| ADATA Technology             | 3         | 0.92%   |
| Silicon Image                | 1         | 0.31%   |
| Micron/Crucial Technology    | 1         | 0.31%   |
| Micron Technology            | 1         | 0.31%   |
| Lite-On IT Corp. / Plextor   | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 28        | 7.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 19        | 4.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 18        | 4.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 3.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 13        | 3.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 3.12%   |
| Intel SATA Controller [RAID mode]                                              | 9         | 2.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 8         | 2.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 1.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 1.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.3%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 5         | 1.3%    |
| KIOXIA Non-Volatile memory controller                                          | 4         | 1.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.04%   |
| Intel 82Q35 Express PT IDER Controller                                         | 4         | 1.04%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 4         | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 4         | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 4         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 1.04%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.04%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 3         | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.78%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 0.78%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.78%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3         | 0.78%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.78%   |
| Intel SSD 660P Series                                                          | 3         | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 0.78%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3         | 0.78%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3         | 0.78%   |
| AMD FCH SATA Controller D                                                      | 3         | 0.78%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3         | 0.78%   |
| SK hynix Gold P31 SSD                                                          | 2         | 0.52%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.52%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.52%   |
| Nvidia MCP61 SATA Controller                                                   | 2         | 0.52%   |
| Nvidia MCP61 IDE                                                               | 2         | 0.52%   |
| Kingston Company KC2000 NVMe SSD                                               | 2         | 0.52%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2         | 0.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 0.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.52%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.52%   |
| Intel Comet Lake PCH-H RAID                                                    | 2         | 0.52%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 2         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 199       | 61.61%  |
| NVMe | 55        | 17.03%  |
| IDE  | 40        | 12.38%  |
| RAID | 29        | 8.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 230       | 81.56%  |
| AMD    | 47        | 16.67%  |
| ARM    | 5         | 1.77%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Pentium CPU G620 @ 2.60GHz                 | 6         | 2.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz                | 6         | 2.12%   |
| Intel Core i5-2450M CPU @ 2.50GHz                | 4         | 1.41%   |
| Intel Core i3-4130 CPU @ 3.40GHz                 | 4         | 1.41%   |
| Intel Pentium CPU G630 @ 2.70GHz                 | 3         | 1.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz                | 3         | 1.06%   |
| Intel Core i7-3770 CPU @ 3.40GHz                 | 3         | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz                | 3         | 1.06%   |
| Intel Core i5-4590 CPU @ 3.30GHz                 | 3         | 1.06%   |
| Intel Core i5-4570 CPU @ 3.20GHz                 | 3         | 1.06%   |
| Intel Core i5-4210U CPU @ 1.70GHz                | 3         | 1.06%   |
| Intel Core i5-4200U CPU @ 1.60GHz                | 3         | 1.06%   |
| Intel Core i5-3570 CPU @ 3.40GHz                 | 3         | 1.06%   |
| Intel Core i5-2410M CPU @ 2.30GHz                | 3         | 1.06%   |
| Intel Core i5-2400 CPU @ 3.10GHz                 | 3         | 1.06%   |
| Intel Celeron N4100 CPU @ 1.10GHz                | 3         | 1.06%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx    | 3         | 1.06%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics      | 3         | 1.06%   |
| Intel Xeon CPU X5450 @ 3.00GHz                   | 2         | 0.71%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz      | 2         | 0.71%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz      | 2         | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz                | 2         | 0.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz                | 2         | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz               | 2         | 0.71%   |
| Intel Core i7-5500U CPU @ 2.40GHz                | 2         | 0.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz                | 2         | 0.71%   |
| Intel Core i7-4790 CPU @ 3.60GHz                 | 2         | 0.71%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz               | 2         | 0.71%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz               | 2         | 0.71%   |
| Intel Core i5-8400 CPU @ 2.80GHz                 | 2         | 0.71%   |
| Intel Core i5-7300U CPU @ 2.60GHz                | 2         | 0.71%   |
| Intel Core i5-6400 CPU @ 2.70GHz                 | 2         | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz                 | 2         | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz                | 2         | 0.71%   |
| Intel Core i5-2540M CPU @ 2.60GHz                | 2         | 0.71%   |
| Intel Core i5-2435M CPU @ 2.40GHz                | 2         | 0.71%   |
| Intel Core i5-10400 CPU @ 2.90GHz                | 2         | 0.71%   |
| Intel Core i3-9100 CPU @ 3.60GHz                 | 2         | 0.71%   |
| Intel Core i3-8145U CPU @ 2.10GHz                | 2         | 0.71%   |
| Intel Core i3-3220 CPU @ 3.30GHz                 | 2         | 0.71%   |
| Intel Core i3-3110M CPU @ 2.40GHz                | 2         | 0.71%   |
| Intel Core i3-2367M CPU @ 1.40GHz                | 2         | 0.71%   |
| Intel Core i3-2350M CPU @ 2.30GHz                | 2         | 0.71%   |
| Intel Core i3 CPU M 380 @ 2.53GHz                | 2         | 0.71%   |
| Intel Core i3 CPU M 330 @ 2.13GHz                | 2         | 0.71%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz            | 2         | 0.71%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz             | 2         | 0.71%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz             | 2         | 0.71%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz             | 2         | 0.71%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz             | 2         | 0.71%   |
| Intel 12th Gen Core i7-12700                     | 2         | 0.71%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz           | 2         | 0.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz          | 2         | 0.71%   |
| ARM Qualcomm Technologies, Inc MSM8937 Processor | 2         | 0.71%   |
| ARM BCM2835 Processor                            | 2         | 0.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics           | 2         | 0.71%   |
| AMD Ryzen 7 1700X Eight-Core Processor           | 2         | 0.71%   |
| AMD Ryzen 5 4600H with Radeon Graphics           | 2         | 0.71%   |
| AMD Ryzen 5 3600 6-Core Processor                | 2         | 0.71%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+       | 2         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 75        | 26.5%   |
| Intel Core i7           | 49        | 17.31%  |
| Intel Core i3           | 31        | 10.95%  |
| Intel Core 2 Duo        | 17        | 6.01%   |
| AMD Ryzen 5             | 17        | 6.01%   |
| Intel Pentium           | 14        | 4.95%   |
| Other                   | 11        | 3.89%   |
| Intel Xeon              | 10        | 3.53%   |
| Intel Celeron           | 7         | 2.47%   |
| Intel Atom              | 6         | 2.12%   |
| AMD Ryzen 7             | 6         | 2.12%   |
| Intel Pentium Dual-Core | 5         | 1.77%   |
| Intel Core 2 Quad       | 4         | 1.41%   |
| AMD A6                  | 4         | 1.41%   |
| AMD Ryzen 3             | 3         | 1.06%   |
| AMD A10                 | 3         | 1.06%   |
| Intel Core i9           | 2         | 0.71%   |
| ARM BCM                 | 2         | 0.71%   |
| AMD Ryzen 9             | 2         | 0.71%   |
| AMD Ryzen 7 PRO         | 2         | 0.71%   |
| AMD Athlon 64 X2        | 2         | 0.71%   |
| AMD A4                  | 2         | 0.71%   |
| Intel Pentium Dual      | 1         | 0.35%   |
| Intel Genuine           | 1         | 0.35%   |
| ARM AArch64             | 1         | 0.35%   |
| AMD Ryzen Threadripper  | 1         | 0.35%   |
| AMD Phenom II X6        | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD Athlon X2           | 1         | 0.35%   |
| AMD Athlon              | 1         | 0.35%   |
| AMD A12                 | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 128       | 45.39%  |
| 4      | 101       | 35.82%  |
| 6      | 29        | 10.28%  |
| 8      | 13        | 4.61%   |
| 1      | 5         | 1.77%   |
| 12     | 3         | 1.06%   |
| 64     | 1         | 0.35%   |
| 10     | 1         | 0.35%   |
| 3      | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 279       | 98.94%  |
| 2      | 3         | 1.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 177       | 62.54%  |
| 1      | 105       | 37.1%   |
| 4      | 1         | 0.35%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 278       | 98.23%  |
| Unknown        | 5         | 1.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 18.69%  |
| 0x206a7    | 28        | 9.69%   |
| 0x306c3    | 27        | 9.34%   |
| 0x306a9    | 23        | 7.96%   |
| 0x1067a    | 15        | 5.19%   |
| 0x906ea    | 9         | 3.11%   |
| 0x806e9    | 9         | 3.11%   |
| 0x40651    | 7         | 2.42%   |
| 0x406e3    | 6         | 2.08%   |
| 0x20655    | 6         | 2.08%   |
| 0x506e3    | 5         | 1.73%   |
| 0x08108109 | 5         | 1.73%   |
| 0x706a1    | 4         | 1.38%   |
| 0x6fd      | 4         | 1.38%   |
| 0x6fb      | 4         | 1.38%   |
| 0x306d4    | 4         | 1.38%   |
| 0x20652    | 4         | 1.38%   |
| 0x08600104 | 4         | 1.38%   |
| 0x06001119 | 4         | 1.38%   |
| 0xa0652    | 3         | 1.04%   |
| 0x806eb    | 3         | 1.04%   |
| 0x806ea    | 3         | 1.04%   |
| 0x10676    | 3         | 1.04%   |
| 0xa0671    | 2         | 0.69%   |
| 0xa0655    | 2         | 0.69%   |
| 0x906eb    | 2         | 0.69%   |
| 0x906e9    | 2         | 0.69%   |
| 0x90672    | 2         | 0.69%   |
| 0x806ec    | 2         | 0.69%   |
| 0x706e5    | 2         | 0.69%   |
| 0x406c3    | 2         | 0.69%   |
| 0x30678    | 2         | 0.69%   |
| 0x106ca    | 2         | 0.69%   |
| 0x0a50000b | 2         | 0.69%   |
| 0x08701021 | 2         | 0.69%   |
| 0x08108102 | 2         | 0.69%   |
| 0x0700010f | 2         | 0.69%   |
| 0xa0660    | 1         | 0.35%   |
| 0xa0653    | 1         | 0.35%   |
| 0x806d1    | 1         | 0.35%   |
| 0x806c1    | 1         | 0.35%   |
| 0x50671    | 1         | 0.35%   |
| 0x406f1    | 1         | 0.35%   |
| 0x406c4    | 1         | 0.35%   |
| 0x306f2    | 1         | 0.35%   |
| 0x206d7    | 1         | 0.35%   |
| 0x106e5    | 1         | 0.35%   |
| 0x106a5    | 1         | 0.35%   |
| 0x0a50000c | 1         | 0.35%   |
| 0x0a20120a | 1         | 0.35%   |
| 0x0a201009 | 1         | 0.35%   |
| 0x08701013 | 1         | 0.35%   |
| 0x08608103 | 1         | 0.35%   |
| 0x08600106 | 1         | 0.35%   |
| 0x08301039 | 1         | 0.35%   |
| 0x08101016 | 1         | 0.35%   |
| 0x08001136 | 1         | 0.35%   |
| 0x08001126 | 1         | 0.35%   |
| 0x06006118 | 1         | 0.35%   |
| 0x06003106 | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 37        | 13.12%  |
| Haswell          | 37        | 13.12%  |
| KabyLake         | 34        | 12.06%  |
| IvyBridge        | 30        | 10.64%  |
| Penryn           | 21        | 7.45%   |
| Skylake          | 12        | 4.26%   |
| Westmere         | 11        | 3.9%    |
| Zen+             | 10        | 3.55%   |
| Unknown          | 10        | 3.55%   |
| Zen 2            | 9         | 3.19%   |
| Core             | 9         | 3.19%   |
| CometLake        | 8         | 2.84%   |
| Zen 3            | 7         | 2.48%   |
| Silvermont       | 6         | 2.13%   |
| Broadwell        | 5         | 1.77%   |
| Zen              | 4         | 1.42%   |
| Piledriver       | 4         | 1.42%   |
| Goldmont plus    | 4         | 1.42%   |
| TigerLake        | 3         | 1.06%   |
| IceLake          | 3         | 1.06%   |
| Nehalem          | 2         | 0.71%   |
| K8 Hammer        | 2         | 0.71%   |
| K10              | 2         | 0.71%   |
| Jaguar           | 2         | 0.71%   |
| Excavator        | 2         | 0.71%   |
| Bonnell          | 2         | 0.71%   |
| Alderlake Hybrid | 2         | 0.71%   |
| Steamroller      | 1         | 0.35%   |
| K8 & K10 hybrid  | 1         | 0.35%   |
| K10 Llano        | 1         | 0.35%   |
| Bobcat           | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 170       | 48.3%   |
| Nvidia                     | 103       | 29.26%  |
| AMD                        | 77        | 21.88%  |
| Matrox Electronics Systems | 1         | 0.28%   |
| ASPEED Technology          | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 6.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 4.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 9         | 2.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 2.23%   |
| Intel HD Graphics 620                                                                    | 8         | 2.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 2.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 2.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 2.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 1.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 1.68%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 5         | 1.4%    |
| Nvidia GF108 [GeForce GT 430]                                                            | 5         | 1.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.4%    |
| AMD Renoir                                                                               | 5         | 1.4%    |
| AMD Cezanne                                                                              | 5         | 1.4%    |
| Intel HD Graphics 5500                                                                   | 4         | 1.12%   |
| Intel HD Graphics 530                                                                    | 4         | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.12%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 1.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.12%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.84%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 3         | 0.84%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.84%   |
| Intel HD Graphics 630                                                                    | 3         | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.84%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 0.84%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.56%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2         | 0.56%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2         | 0.56%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.56%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.56%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.56%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.56%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 2         | 0.56%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.56%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 0.56%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.56%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.56%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2         | 0.56%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 2         | 0.56%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.56%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 0.56%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.56%   |
| AMD Richland [Radeon HD 8450G]                                                           | 2         | 0.56%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 101       | 35.69%  |
| 1 x Nvidia     | 51        | 18.02%  |
| 1 x AMD        | 51        | 18.02%  |
| Intel + Nvidia | 46        | 16.25%  |
| Intel + AMD    | 16        | 5.65%   |
| AMD + Nvidia   | 6         | 2.12%   |
| Other          | 5         | 1.77%   |
| 2 x AMD        | 5         | 1.77%   |
| 1 x Matrox     | 1         | 0.35%   |
| 1 x ASPEED     | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 216       | 76.06%  |
| Proprietary | 56        | 19.72%  |
| Unknown     | 12        | 4.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 135       | 47.2%   |
| 1.01-2.0   | 58        | 20.28%  |
| 0.51-1.0   | 27        | 9.44%   |
| 3.01-4.0   | 25        | 8.74%   |
| 0.01-0.5   | 24        | 8.39%   |
| 7.01-8.0   | 10        | 3.5%    |
| 5.01-6.0   | 4         | 1.4%    |
| 8.01-16.0  | 2         | 0.7%    |
| 2.01-3.0   | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 39        | 13.18%  |
| Samsung Electronics     | 33        | 11.15%  |
| Dell                    | 33        | 11.15%  |
| Chimei Innolux          | 25        | 8.45%   |
| BOE                     | 22        | 7.43%   |
| LG Display              | 19        | 6.42%   |
| Hewlett-Packard         | 17        | 5.74%   |
| Acer                    | 14        | 4.73%   |
| Sharp                   | 11        | 3.72%   |
| Goldstar                | 10        | 3.38%   |
| AOC                     | 10        | 3.38%   |
| BenQ                    | 9         | 3.04%   |
| ViewSonic               | 7         | 2.36%   |
| Philips                 | 7         | 2.36%   |
| Apple                   | 6         | 2.03%   |
| Lenovo                  | 5         | 1.69%   |
| Chi Mei Optoelectronics | 4         | 1.35%   |
| Toshiba                 | 3         | 1.01%   |
| ASUSTek Computer        | 3         | 1.01%   |
| LG Electronics          | 2         | 0.68%   |
| InnoLux Display         | 2         | 0.68%   |
| Unknown                 | 1         | 0.34%   |
| Sony                    | 1         | 0.34%   |
| PANDA                   | 1         | 0.34%   |
| Panasonic               | 1         | 0.34%   |
| LG Philips              | 1         | 0.34%   |
| InfoVision              | 1         | 0.34%   |
| HUYINIUDA               | 1         | 0.34%   |
| EXP                     | 1         | 0.34%   |
| Envision Peripherals    | 1         | 0.34%   |
| Dinner                  | 1         | 0.34%   |
| Denver                  | 1         | 0.34%   |
| CVT                     | 1         | 0.34%   |
| Armaggeddon             | 1         | 0.34%   |
| Ancor Communications    | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 5         | 1.63%   |
| Dell E2720HS DELA15E 1920x1080 598x336mm 27.0-inch                        | 3         | 0.98%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                         | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch             | 3         | 0.98%   |
| Sharp LCD SHP10C9 1920x540                                                | 2         | 0.65%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch         | 2         | 0.65%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch          | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch      | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 2         | 0.65%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 2         | 0.65%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                        | 2         | 0.65%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 2         | 0.65%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch          | 2         | 0.65%   |
| Hewlett-Packard LCD Monitor P221                                          | 2         | 0.65%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 2         | 0.65%   |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                        | 2         | 0.65%   |
| Dell LCD Monitor E2720HS 1920x1080                                        | 2         | 0.65%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                         | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch           | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x174mm 14.0-inch           | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch           | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.65%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch             | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch             | 2         | 0.65%   |
| ASUSTek Computer XG32VQR AUS32B2 2560x1440 697x393mm 31.5-inch            | 2         | 0.65%   |
| AOC LCD Monitor 936W 1366x768                                             | 2         | 0.65%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                             | 2         | 0.65%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                         | 2         | 0.65%   |
| Acer K202HQLA ACR0498 1366x768 434x236mm 19.4-inch                        | 2         | 0.65%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch             | 1         | 0.33%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch                 | 1         | 0.33%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch                 | 1         | 0.33%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch             | 1         | 0.33%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch                | 1         | 0.33%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch              | 1         | 0.33%   |
| ViewSonic V3D231 Series VSC4C29 1920x1080 510x290mm 23.1-inch             | 1         | 0.33%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1600x900               | 1         | 0.33%   |
| Toshiba TV TSB0113 1920x1080 1220x680mm 55.0-inch                         | 1         | 0.33%   |
| Toshiba TV TSB010B 1920x1080 926x523mm 41.9-inch                          | 1         | 0.33%   |
| Toshiba Crystal View LCD0001 1920x1080 408x255mm 18.9-inch                | 1         | 0.33%   |
| Sony TV SNY0902 1360x768                                                  | 1         | 0.33%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                   | 1         | 0.33%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                   | 1         | 0.33%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                   | 1         | 0.33%   |
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch                   | 1         | 0.33%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 1         | 0.33%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 1         | 0.33%   |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch                   | 1         | 0.33%   |
| Sharp LC-22LE420M SHP2242 1920x1080 477x268mm 21.5-inch                   | 1         | 0.33%   |
| Sharp HDMI SHP10A1 1360x768 700x390mm 31.5-inch                           | 1         | 0.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM0484 1920x1080 520x320mm 24.0-inch      | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 117       | 40.77%  |
| 1366x768 (WXGA)    | 87        | 30.31%  |
| 2560x1440 (QHD)    | 13        | 4.53%   |
| 3840x2160 (4K)     | 10        | 3.48%   |
| 1600x900 (HD+)     | 10        | 3.48%   |
| 1280x800 (WXGA)    | 8         | 2.79%   |
| 1440x900 (WXGA+)   | 6         | 2.09%   |
| 2560x1080          | 5         | 1.74%   |
| Unknown            | 4         | 1.39%   |
| 1920x1200 (WUXGA)  | 3         | 1.05%   |
| 1280x1024 (SXGA)   | 3         | 1.05%   |
| 5760x1080          | 2         | 0.7%    |
| 2160x1440          | 2         | 0.7%    |
| 1920x540           | 2         | 0.7%    |
| 1680x1050 (WSXGA+) | 2         | 0.7%    |
| 1600x1200          | 2         | 0.7%    |
| 5440x1080          | 1         | 0.35%   |
| 5120x1440          | 1         | 0.35%   |
| 3840x1080          | 1         | 0.35%   |
| 3440x1440          | 1         | 0.35%   |
| 2880x1920          | 1         | 0.35%   |
| 2240x1400          | 1         | 0.35%   |
| 1360x768           | 1         | 0.35%   |
| 1360x765           | 1         | 0.35%   |
| 1280x960           | 1         | 0.35%   |
| 1024x768 (XGA)     | 1         | 0.35%   |
| 1024x600           | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 58        | 19.59%  |
| 14      | 37        | 12.5%   |
| 13      | 32        | 10.81%  |
| 23      | 25        | 8.45%   |
| 24      | 20        | 6.76%   |
| 21      | 19        | 6.42%   |
| Unknown | 16        | 5.41%   |
| 27      | 15        | 5.07%   |
| 18      | 14        | 4.73%   |
| 19      | 12        | 4.05%   |
| 31      | 8         | 2.7%    |
| 17      | 8         | 2.7%    |
| 20      | 5         | 1.69%   |
| 11      | 5         | 1.69%   |
| 12      | 4         | 1.35%   |
| 34      | 3         | 1.01%   |
| 72      | 2         | 0.68%   |
| 28      | 2         | 0.68%   |
| 25      | 2         | 0.68%   |
| 22      | 2         | 0.68%   |
| 84      | 1         | 0.34%   |
| 55      | 1         | 0.34%   |
| 52      | 1         | 0.34%   |
| 39      | 1         | 0.34%   |
| 32      | 1         | 0.34%   |
| 16      | 1         | 0.34%   |
| 10      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 118       | 40.14%  |
| 501-600     | 57        | 19.39%  |
| 401-500     | 51        | 17.35%  |
| 201-300     | 21        | 7.14%   |
| Unknown     | 16        | 5.44%   |
| 601-700     | 12        | 4.08%   |
| 351-400     | 9         | 3.06%   |
| 701-800     | 4         | 1.36%   |
| 1501-2000   | 3         | 1.02%   |
| 1001-1500   | 2         | 0.68%   |
| 801-900     | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 213       | 79.48%  |
| 16/10   | 21        | 7.84%   |
| Unknown | 14        | 5.22%   |
| 5/4     | 5         | 1.87%   |
| 3/2     | 5         | 1.87%   |
| 21/9    | 5         | 1.87%   |
| 4/3     | 3         | 1.12%   |
| 32/9    | 2         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 61        | 20.82%  |
| 101-110        | 59        | 20.14%  |
| 201-250        | 56        | 19.11%  |
| 151-200        | 23        | 7.85%   |
| Unknown        | 16        | 5.46%   |
| 301-350        | 15        | 5.12%   |
| 141-150        | 15        | 5.12%   |
| 351-500        | 12        | 4.1%    |
| 71-80          | 8         | 2.73%   |
| 251-300        | 7         | 2.39%   |
| More than 1000 | 5         | 1.71%   |
| 51-60          | 5         | 1.71%   |
| 121-130        | 5         | 1.71%   |
| 61-70          | 4         | 1.37%   |
| 41-50          | 1         | 0.34%   |
| 501-1000       | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 99        | 34.38%  |
| 101-120       | 94        | 32.64%  |
| 121-160       | 64        | 22.22%  |
| Unknown       | 16        | 5.56%   |
| 161-240       | 7         | 2.43%   |
| 1-50          | 6         | 2.08%   |
| More than 240 | 2         | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 233       | 82.04%  |
| 2     | 37        | 13.03%  |
| 0     | 12        | 4.23%   |
| 3     | 2         | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 143       | 31.36%  |
| Intel                             | 122       | 26.75%  |
| Qualcomm Atheros                  | 67        | 14.69%  |
| Broadcom                          | 29        | 6.36%   |
| TP-Link                           | 19        | 4.17%   |
| Ralink Technology                 | 15        | 3.29%   |
| D-Link                            | 10        | 2.19%   |
| Xiaomi                            | 6         | 1.32%   |
| Ralink                            | 5         | 1.1%    |
| Qualcomm Atheros Communications   | 5         | 1.1%    |
| Nvidia                            | 5         | 1.1%    |
| MediaTek                          | 5         | 1.1%    |
| Broadcom Limited                  | 5         | 1.1%    |
| Huawei Technologies               | 3         | 0.66%   |
| Samsung Electronics               | 2         | 0.44%   |
| OPPO Electronics                  | 2         | 0.44%   |
| ASIX Electronics                  | 2         | 0.44%   |
| Sundance Technology Inc / IC Plus | 1         | 0.22%   |
| Marvell Technology Group          | 1         | 0.22%   |
| JMicron Technology                | 1         | 0.22%   |
| Hewlett-Packard                   | 1         | 0.22%   |
| DisplayLink                       | 1         | 0.22%   |
| D-Link System                     | 1         | 0.22%   |
| Attansic Technology               | 1         | 0.22%   |
| ASUSTek Computer                  | 1         | 0.22%   |
| Aquantia                          | 1         | 0.22%   |
| Apple                             | 1         | 0.22%   |
| AboCom Systems                    | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 94        | 18.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 19        | 3.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 12        | 2.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 10        | 1.92%   |
| Ralink MT7601U Wireless Adapter                                                      | 9         | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 9         | 1.73%   |
| TP-Link Archer T4U ver.3                                                             | 8         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 8         | 1.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 8         | 1.54%   |
| Intel Wi-Fi 6 AX200                                                                  | 8         | 1.54%   |
| Intel Wireless 8265 / 8275                                                           | 7         | 1.34%   |
| Intel 82579V Gigabit Network Connection                                              | 7         | 1.34%   |
| TP-Link 802.11n NIC                                                                  | 6         | 1.15%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 6         | 1.15%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 6         | 1.15%   |
| Realtek 802.11ac NIC                                                                 | 6         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 6         | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 5         | 0.96%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 5         | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 5         | 0.96%   |
| Intel Ethernet Connection I217-LM                                                    | 5         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 5         | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                             | 5         | 0.96%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 5         | 0.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                       | 4         | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 4         | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 4         | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4         | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 4         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 4         | 0.77%   |
| Intel Wireless 3165                                                                  | 4         | 0.77%   |
| Intel Ethernet Connection (11) I219-V                                                | 4         | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4         | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                    | 4         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 3         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                            | 3         | 0.58%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3         | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 3         | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                           | 3         | 0.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 3         | 0.58%   |
| Intel Wireless-AC 9260                                                               | 3         | 0.58%   |
| Intel Wireless 7260                                                                  | 3         | 0.58%   |
| Intel Wireless 3160                                                                  | 3         | 0.58%   |
| Intel Wi-Fi 6 AX201                                                                  | 3         | 0.58%   |
| Intel I211 Gigabit Network Connection                                                | 3         | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                                | 3         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                                                 | 3         | 0.58%   |
| Intel Centrino Wireless-N 2230                                                       | 3         | 0.58%   |
| Intel Centrino Ultimate-N 6300                                                       | 3         | 0.58%   |
| Intel 82577LM Gigabit Network Connection                                             | 3         | 0.58%   |
| Intel 82566DM-2 Gigabit Network Connection                                           | 3         | 0.58%   |
| Huawei COL-L29                                                                       | 3         | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                      | 3         | 0.58%   |
| Broadcom BCM4331 802.11a/b/g/n                                                       | 3         | 0.58%   |
| Broadcom BCM43228 802.11a/b/g/n                                                      | 3         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                 | 2         | 0.38%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2         | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 2         | 0.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2         | 0.38%   |
| Realtek RTL8723DE Wireless Network Adapter                                           | 2         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 80        | 31.37%  |
| Qualcomm Atheros                | 53        | 20.78%  |
| Realtek Semiconductor           | 38        | 14.9%   |
| TP-Link                         | 19        | 7.45%   |
| Broadcom                        | 18        | 7.06%   |
| Ralink Technology               | 15        | 5.88%   |
| D-Link                          | 10        | 3.92%   |
| Ralink                          | 5         | 1.96%   |
| Qualcomm Atheros Communications | 5         | 1.96%   |
| MediaTek                        | 5         | 1.96%   |
| Broadcom Limited                | 4         | 1.57%   |
| D-Link System                   | 1         | 0.39%   |
| ASUSTek Computer                | 1         | 0.39%   |
| AboCom Systems                  | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 10        | 3.86%   |
| Ralink MT7601U Wireless Adapter                                                      | 9         | 3.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 9         | 3.47%   |
| TP-Link Archer T4U ver.3                                                             | 8         | 3.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 8         | 3.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 8         | 3.09%   |
| Intel Wi-Fi 6 AX200                                                                  | 8         | 3.09%   |
| Intel Wireless 8265 / 8275                                                           | 7         | 2.7%    |
| TP-Link 802.11n NIC                                                                  | 6         | 2.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 6         | 2.32%   |
| Realtek 802.11ac NIC                                                                 | 6         | 2.32%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 6         | 2.32%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 5         | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 5         | 1.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 5         | 1.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                             | 5         | 1.93%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 5         | 1.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 4         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 4         | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4         | 1.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 4         | 1.54%   |
| Intel Wireless 3165                                                                  | 4         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4         | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 3         | 1.16%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3         | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 3         | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 3         | 1.16%   |
| Intel Wireless-AC 9260                                                               | 3         | 1.16%   |
| Intel Wireless 7260                                                                  | 3         | 1.16%   |
| Intel Wireless 3160                                                                  | 3         | 1.16%   |
| Intel Wi-Fi 6 AX201                                                                  | 3         | 1.16%   |
| Intel Centrino Wireless-N 2230                                                       | 3         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                                       | 3         | 1.16%   |
| Broadcom BCM4331 802.11a/b/g/n                                                       | 3         | 1.16%   |
| Broadcom BCM43228 802.11a/b/g/n                                                      | 3         | 1.16%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2         | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 2         | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2         | 0.77%   |
| Realtek RTL8723DE Wireless Network Adapter                                           | 2         | 0.77%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2         | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2         | 0.77%   |
| Ralink RT5370 Wireless Adapter                                                       | 2         | 0.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                            | 2         | 0.77%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 2         | 0.77%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 2         | 0.77%   |
| Intel Wireless 7265                                                                  | 2         | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 2         | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                | 2         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 2         | 0.77%   |
| Intel Centrino Advanced-N 6235                                                       | 2         | 0.77%   |
| Intel Centrino Advanced-N 6200                                                       | 2         | 0.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 2         | 0.77%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                            | 2         | 0.77%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 2         | 0.77%   |
| Broadcom BCM43224 802.11a/b/g/n                                                      | 2         | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 2         | 0.77%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                    | 2         | 0.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 1         | 0.39%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                              | 1         | 0.39%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 127       | 49.8%   |
| Intel                             | 68        | 26.67%  |
| Qualcomm Atheros                  | 18        | 7.06%   |
| Broadcom                          | 14        | 5.49%   |
| Xiaomi                            | 6         | 2.35%   |
| Nvidia                            | 5         | 1.96%   |
| Huawei Technologies               | 3         | 1.18%   |
| Samsung Electronics               | 2         | 0.78%   |
| OPPO Electronics                  | 2         | 0.78%   |
| ASIX Electronics                  | 2         | 0.78%   |
| Sundance Technology Inc / IC Plus | 1         | 0.39%   |
| Marvell Technology Group          | 1         | 0.39%   |
| JMicron Technology                | 1         | 0.39%   |
| DisplayLink                       | 1         | 0.39%   |
| Broadcom Limited                  | 1         | 0.39%   |
| Attansic Technology               | 1         | 0.39%   |
| Aquantia                          | 1         | 0.39%   |
| Apple                             | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 94        | 36.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 19        | 7.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 4.6%    |
| Intel 82579V Gigabit Network Connection                                        | 7         | 2.68%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 2.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 1.92%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 1.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4         | 1.53%   |
| Intel Ethernet Connection (11) I219-V                                          | 4         | 1.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 1.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 1.15%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.15%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.15%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.15%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3         | 1.15%   |
| Huawei COL-L29                                                                 | 3         | 1.15%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.15%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 0.77%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.77%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.77%   |
| OPPO Find X2 Lite                                                              | 2         | 0.77%   |
| Intel I350 Gigabit Network Connection                                          | 2         | 0.77%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.77%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.77%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.77%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.77%   |
| Intel 82562V-2 10/100 Network Connection                                       | 2         | 0.77%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 2         | 0.77%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 2         | 0.77%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 1         | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.38%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.38%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.38%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.38%   |
| Nvidia MCP73 Ethernet                                                          | 1         | 0.38%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.38%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.38%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.38%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.38%   |
| Intel I350 Gigabit Fiber Network Connection                                    | 1         | 0.38%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.38%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.38%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.38%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.38%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.38%   |
| Intel Ethernet Connection (2) I218-LM                                          | 1         | 0.38%   |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 1         | 0.38%   |
| Intel 82583V Gigabit Network Connection                                        | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 235       | 50.43%  |
| WiFi     | 230       | 49.36%  |
| Modem    | 1         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 187       | 66.55%  |
| Ethernet | 94        | 33.45%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 153       | 54.06%  |
| 1     | 104       | 36.75%  |
| 0     | 20        | 7.07%   |
| 3     | 5         | 1.77%   |
| 9     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 222       | 77.08%  |
| Yes  | 66        | 22.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 33.9%   |
| Cambridge Silicon Radio         | 19        | 10.73%  |
| Qualcomm Atheros Communications | 15        | 8.47%   |
| Broadcom                        | 14        | 7.91%   |
| Realtek Semiconductor           | 12        | 6.78%   |
| IMC Networks                    | 10        | 5.65%   |
| Foxconn / Hon Hai               | 10        | 5.65%   |
| Apple                           | 10        | 5.65%   |
| Lite-On Technology              | 8         | 4.52%   |
| Realtek                         | 3         | 1.69%   |
| Hewlett-Packard                 | 3         | 1.69%   |
| Dell                            | 3         | 1.69%   |
| Ralink                          | 2         | 1.13%   |
| MediaTek                        | 2         | 1.13%   |
| TP-Link                         | 1         | 0.56%   |
| Ralink Technology               | 1         | 0.56%   |
| D-Link                          | 1         | 0.56%   |
| ASUSTek Computer                | 1         | 0.56%   |
| Askey Computer                  | 1         | 0.56%   |
| Alps Electric                   | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 19        | 10.73%  |
| Intel Bluetooth wireless interface                                                  | 18        | 10.17%  |
| Intel Bluetooth Device                                                              | 12        | 6.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 5.65%   |
| Intel AX200 Bluetooth                                                               | 8         | 4.52%   |
| Realtek Bluetooth Radio                                                             | 6         | 3.39%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.82%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.26%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2.26%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.26%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 2.26%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.26%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.69%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.69%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.69%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.69%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.13%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.13%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 1.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.13%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.13%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.13%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.13%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.13%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.13%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.13%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.13%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 1.13%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.13%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 1.13%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.13%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 1.13%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.13%   |
| Broadcom BCM20702A0                                                                 | 2         | 1.13%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.13%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.56%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.56%   |
| Ralink CSR BS8510                                                                   | 1         | 0.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.56%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.56%   |
| MediaTek Wireless_Device                                                            | 1         | 0.56%   |
| MediaTek BT                                                                         | 1         | 0.56%   |
| Lite-On Wireless_Device                                                             | 1         | 0.56%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.56%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.56%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.56%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.56%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 1         | 0.56%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.56%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.56%   |
| D-Link DBT-122 Bluetooth adapter                                                    | 1         | 0.56%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.56%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.56%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 0.56%   |
| Askey Bluetooth Device                                                              | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 218       | 56.33%  |
| Nvidia                      | 73        | 18.86%  |
| AMD                         | 66        | 17.05%  |
| C-Media Electronics         | 8         | 2.07%   |
| Logitech                    | 6         | 1.55%   |
| JMTek                       | 3         | 0.78%   |
| Samsung Electronics         | 2         | 0.52%   |
| Unknown                     | 1         | 0.26%   |
| Texas Instruments           | 1         | 0.26%   |
| Realtek Semiconductor       | 1         | 0.26%   |
| Plantronics                 | 1         | 0.26%   |
| MVSILICON.INC.              | 1         | 0.26%   |
| GN Netcom                   | 1         | 0.26%   |
| Generalplus Technology      | 1         | 0.26%   |
| FiiO Electronics Technology | 1         | 0.26%   |
| Creative Labs               | 1         | 0.26%   |
| Cooler Master               | 1         | 0.26%   |
| ASUSTek Computer            | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 35        | 7.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 29        | 6.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 21        | 4.71%   |
| AMD Family 17h/19h HD Audio Controller                                            | 21        | 4.71%   |
| Intel Sunrise Point-LP HD Audio                                                   | 19        | 4.26%   |
| Nvidia GF108 High Definition Audio Controller                                     | 14        | 3.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14        | 3.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 14        | 3.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 12        | 2.69%   |
| Intel Cannon Lake PCH cAVS                                                        | 11        | 2.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 10        | 2.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9         | 2.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 9         | 2.02%   |
| Intel 8 Series HD Audio Controller                                                | 8         | 1.79%   |
| AMD FCH Azalia Controller                                                         | 8         | 1.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 8         | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                             | 7         | 1.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 6         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6         | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5         | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5         | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5         | 1.12%   |
| Intel Comet Lake PCH cAVS                                                         | 5         | 1.12%   |
| AMD Starship/Matisse HD Audio Controller                                          | 5         | 1.12%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5         | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 0.9%    |
| Nvidia High Definition Audio Controller                                           | 4         | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4         | 0.9%    |
| Nvidia GK107 HDMI Audio Controller                                                | 4         | 0.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 4         | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 4         | 0.9%    |
| Intel Broadwell-U Audio Controller                                                | 4         | 0.9%    |
| AMD Trinity HDMI Audio Controller                                                 | 4         | 0.9%    |
| AMD Kabini HDMI/DP Audio                                                          | 4         | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                                     | 3         | 0.67%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3         | 0.67%   |
| Nvidia GK104 HDMI Audio Controller                                                | 3         | 0.67%   |
| Logitech H600 [Wireless Headset]                                                  | 3         | 0.67%   |
| JMTek USB PnP Audio Device                                                        | 3         | 0.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 3         | 0.67%   |
| Intel Alder Lake-S HD Audio Controller                                            | 3         | 0.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3         | 0.67%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 3         | 0.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3         | 0.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 3         | 0.67%   |
| Nvidia MCP61 High Definition Audio                                                | 2         | 0.45%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2         | 0.45%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.45%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2         | 0.45%   |
| Nvidia Audio device                                                               | 2         | 0.45%   |
| Logitech USB Headset H540                                                         | 2         | 0.45%   |
| Intel USB PnP Sound Device                                                        | 2         | 0.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 0.45%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2         | 0.45%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 0.45%   |
| Intel Audio device                                                                | 2         | 0.45%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2         | 0.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 0.45%   |
| Intel 200 Series PCH HD Audio                                                     | 2         | 0.45%   |
| C-Media Electronics Thronmax MDrill One                                           | 2         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 41        | 27.89%  |
| Samsung Electronics | 26        | 17.69%  |
| SK hynix            | 25        | 17.01%  |
| Unknown             | 9         | 6.12%   |
| Micron Technology   | 9         | 6.12%   |
| Nanya Technology    | 6         | 4.08%   |
| Corsair             | 5         | 3.4%    |
| Ramaxel Technology  | 4         | 2.72%   |
| A-DATA Technology   | 4         | 2.72%   |
| Kingmax             | 3         | 2.04%   |
| Crucial             | 3         | 2.04%   |
| Silicon Power       | 2         | 1.36%   |
| Unknown (ABCD)      | 1         | 0.68%   |
| Team                | 1         | 0.68%   |
| SemsoTai            | 1         | 0.68%   |
| PNY                 | 1         | 0.68%   |
| Kinlstuo            | 1         | 0.68%   |
| Kimtigo             | 1         | 0.68%   |
| Hewlett-Packard     | 1         | 0.68%   |
| G.Skill             | 1         | 0.68%   |
| Elpida              | 1         | 0.68%   |
| Apacer              | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 2.52%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s               | 4         | 2.52%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 3         | 1.89%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s                | 3         | 1.89%   |
| Unknown RAM Module 4GB DIMM SDRAM                                   | 2         | 1.26%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.26%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.26%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 2         | 1.26%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.26%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.26%   |
| Kingston RAM 99U5428-082.A00LF 8192MB SODIMM DDR3 1600MT/s          | 2         | 1.26%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 2         | 1.26%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.63%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                           | 1         | 0.63%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 1         | 0.63%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                 | 1         | 0.63%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.63%   |
| Team RAM Elite-800 2048MB DIMM SDRAM 2048MT/s                       | 1         | 0.63%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                        | 1         | 0.63%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s                | 1         | 0.63%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 0.63%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                        | 1         | 0.63%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                       | 1         | 0.63%   |
| SK hynix RAM HYMP112F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s         | 1         | 0.63%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s                | 1         | 0.63%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 0.63%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 0.63%   |
| SK hynix RAM HMT351S6CFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.63%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.63%   |
| SK hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1333MT/s              | 1         | 0.63%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s             | 1         | 0.63%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 0.63%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.63%   |
| SK hynix RAM HMA84GR7CJR4N-XN 32GB DIMM DDR4 3200MT/s               | 1         | 0.63%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 1         | 0.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 0.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 0.63%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s                | 1         | 0.63%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s    | 1         | 0.63%   |
| Silicon Power RAM SP004GBSFU213N02 4GB SODIMM DDR4 2133MT/s         | 1         | 0.63%   |
| Silicon Power RAM DBLT2GN568S 2048MB DIMM DDR3 1333MT/s             | 1         | 0.63%   |
| SemsoTai RAM Module 8GB DIMM DDR4 2667MT/s                          | 1         | 0.63%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                         | 1         | 0.63%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 0.63%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |
| Samsung RAM M471B2873EH1-CF8 1GB SODIMM 1067MT/s                    | 1         | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 0.63%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.63%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 0.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 0.63%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 1         | 0.63%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 0.63%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s         | 1         | 0.63%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s                 | 1         | 0.63%   |
| Samsung RAM M04GD08P1600C10 4096MB SODIMM DDR3 800MT/s              | 1         | 0.63%   |
| Samsung RAM 8G3200CL22 8192MB SODIMM DDR4 3200MT/s                  | 1         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 59        | 47.97%  |
| DDR4    | 47        | 38.21%  |
| SDRAM   | 6         | 4.88%   |
| DDR2    | 4         | 3.25%   |
| LPDDR4  | 2         | 1.63%   |
| LPDDR3  | 2         | 1.63%   |
| Unknown | 2         | 1.63%   |
| DDR     | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 56.56%  |
| DIMM         | 48        | 39.34%  |
| Row Of Chips | 4         | 3.28%   |
| FB-DIMM      | 1         | 0.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 52        | 38.52%  |
| 8192  | 39        | 28.89%  |
| 2048  | 23        | 17.04%  |
| 16384 | 11        | 8.15%   |
| 32768 | 6         | 4.44%   |
| 1024  | 4         | 2.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 35        | 25.93%  |
| 2667    | 19        | 14.07%  |
| 3200    | 14        | 10.37%  |
| 1334    | 12        | 8.89%   |
| 1333    | 10        | 7.41%   |
| 2400    | 9         | 6.67%   |
| 2133    | 6         | 4.44%   |
| 800     | 5         | 3.7%    |
| Unknown | 5         | 3.7%    |
| 1067    | 4         | 2.96%   |
| 667     | 3         | 2.22%   |
| 1867    | 2         | 1.48%   |
| 1066    | 2         | 1.48%   |
| 4267    | 1         | 0.74%   |
| 3600    | 1         | 0.74%   |
| 3533    | 1         | 0.74%   |
| 3266    | 1         | 0.74%   |
| 3000    | 1         | 0.74%   |
| 2933    | 1         | 0.74%   |
| 2048    | 1         | 0.74%   |
| 1866    | 1         | 0.74%   |
| 1800    | 1         | 0.74%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 3         | 27.27%  |
| Samsung Electronics | 2         | 18.18%  |
| Canon               | 2         | 18.18%  |
| Brother Industries  | 2         | 18.18%  |
| Prolific Technology | 1         | 9.09%   |
| Hewlett-Packard     | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-3400 Series       | 2         | 18.18%  |
| Seiko Epson L3150 Series      | 1         | 9.09%   |
| Seiko Epson L312 Series       | 1         | 9.09%   |
| Seiko Epson L210 Series       | 1         | 9.09%   |
| Prolific PL2305 Parallel Port | 1         | 9.09%   |
| HP Ink Tank 110 series        | 1         | 9.09%   |
| Canon LBP6030/6030B/6018L     | 1         | 9.09%   |
| Canon E410 series             | 1         | 9.09%   |
| Brother DCP-J105              | 1         | 9.09%   |
| Brother DCP-1610W             | 1         | 9.09%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 17.42%  |
| Microdia                               | 16        | 10.32%  |
| Realtek Semiconductor                  | 15        | 9.68%   |
| IMC Networks                           | 15        | 9.68%   |
| Suyin                                  | 11        | 7.1%    |
| Sunplus Innovation Technology          | 11        | 7.1%    |
| Acer                                   | 11        | 7.1%    |
| Apple                                  | 9         | 5.81%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.87%   |
| Logitech                               | 5         | 3.23%   |
| Generalplus Technology                 | 5         | 3.23%   |
| Alcor Micro                            | 4         | 2.58%   |
| Quanta                                 | 3         | 1.94%   |
| Syntek                                 | 2         | 1.29%   |
| Lite-On Technology                     | 2         | 1.29%   |
| HD WEBCAM                              | 2         | 1.29%   |
| Z-Star Microelectronics                | 1         | 0.65%   |
| WCM_USB                                | 1         | 0.65%   |
| Samsung Electronics                    | 1         | 0.65%   |
| Ricoh                                  | 1         | 0.65%   |
| Primax Electronics                     | 1         | 0.65%   |
| OmniVision Technologies                | 1         | 0.65%   |
| Luxvisions Innotech Limited            | 1         | 0.65%   |
| Lenovo                                 | 1         | 0.65%   |
| Jieli Technology                       | 1         | 0.65%   |
| icSpring                               | 1         | 0.65%   |
| ARC International                      | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 6         | 3.87%   |
| Sunplus Integrated_Webcam_HD                            | 4         | 2.58%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 2.58%   |
| Chicony USB2.0 VGA UVC WebCam                           | 4         | 2.58%   |
| Chicony HD WebCam                                       | 4         | 2.58%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.94%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 3         | 1.94%   |
| Generalplus GENERAL WEBCAM                              | 3         | 1.94%   |
| Chicony USB2.0 HD UVC WebCam                            | 3         | 1.94%   |
| Chicony HP HD Webcam                                    | 3         | 1.94%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.94%   |
| Apple FaceTime HD Camera                                | 3         | 1.94%   |
| Acer Lenovo Integrated Webcam                           | 3         | 1.94%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 2         | 1.29%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 1.29%   |
| Suyin 1.3M HD WebCam                                    | 2         | 1.29%   |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 1.29%   |
| Realtek USB Camera                                      | 2         | 1.29%   |
| Realtek HD WebCam                                       | 2         | 1.29%   |
| Microdia USB 2.0 Camera                                 | 2         | 1.29%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.29%   |
| IMC Networks Integrated Camera                          | 2         | 1.29%   |
| IMC Networks HD Camera                                  | 2         | 1.29%   |
| HD WEBCAM Web Camera                                    | 2         | 1.29%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.29%   |
| Chicony Integrated Camera                               | 2         | 1.29%   |
| Apple iPhone 5/5C/5S/6/SE                               | 2         | 1.29%   |
| Apple Built-in iSight                                   | 2         | 1.29%   |
| Alcor Micro Asus Integrated Webcam                      | 2         | 1.29%   |
| Acer EasyCamera                                         | 2         | 1.29%   |
| Acer BisonCam,NB Pro                                    | 2         | 1.29%   |
| Z-Star Sirius USB2.0 Camera                             | 1         | 0.65%   |
| WCM_USB WEB CAM                                         | 1         | 0.65%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.65%   |
| Syntek Laptop_Integrated_Webcam_1.3M                    | 1         | 0.65%   |
| Suyin WebCam                                            | 1         | 0.65%   |
| Suyin Integrated Webcam                                 | 1         | 0.65%   |
| Suyin HP Webcam-101                                     | 1         | 0.65%   |
| Suyin HP Webcam 101                                     | 1         | 0.65%   |
| Suyin HP Truevision HD                                  | 1         | 0.65%   |
| Sunplus Laptop Integrated Webcam HD                     | 1         | 0.65%   |
| Sunplus Laptop Integrated Webcam FHD                    | 1         | 0.65%   |
| Sunplus Integrated_Webcam_FHD                           | 1         | 0.65%   |
| Sunplus Full HD webcam                                  | 1         | 0.65%   |
| Sunplus Dell HD Webcam                                  | 1         | 0.65%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 1         | 0.65%   |
| Ricoh Sony Vaio Integrated Webcam                       | 1         | 0.65%   |
| Realtek USB2.0 HD UVC WebCam                            | 1         | 0.65%   |
| Realtek USB2.0 camera                                   | 1         | 0.65%   |
| Realtek USB HD Webcam                                   | 1         | 0.65%   |
| Realtek Lenovo EasyCamera                               | 1         | 0.65%   |
| Realtek Integrated Webcam_HD                            | 1         | 0.65%   |
| Realtek HP Truevision HD                                | 1         | 0.65%   |
| Realtek HP High Definition 1MP Webcam                   | 1         | 0.65%   |
| Realtek Acer 640 x 480 laptop camera                    | 1         | 0.65%   |
| Quanta HP Wide Vision HD Camera                         | 1         | 0.65%   |
| Quanta HP TrueVision HD Camera                          | 1         | 0.65%   |
| Quanta HD User Facing                                   | 1         | 0.65%   |
| Primax HP HD Webcam [Fixed]                             | 1         | 0.65%   |
| OmniVision OV2640 Webcam                                | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 29.17%  |
| Shenzhen Goodix Technology | 5         | 20.83%  |
| Synaptics                  | 3         | 12.5%   |
| AuthenTec                  | 3         | 12.5%   |
| Upek                       | 2         | 8.33%   |
| Elan Microelectronics      | 2         | 8.33%   |
| LighTuning Technology      | 1         | 4.17%   |
| Focal-systems.Corp         | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                          | 3         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 2         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader                  | 1         | 4.17%   |
| Validity Sensors VFS491                                     | 1         | 4.17%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 1         | 4.17%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 1         | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 1         | 4.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 4.17%   |
| Validity Sensors Fingerprint scanner                        | 1         | 4.17%   |
| Synaptics  WBDI                                             | 1         | 4.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 4.17%   |
| Shenzhen Goodix  Fingerprint Device                         | 1         | 4.17%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 4.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 1         | 4.17%   |
| Focal-systems.Corp FT9201Fingerprint.                       | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                       | 1         | 4.17%   |
| Elan ELAN:ARM-M4                                            | 1         | 4.17%   |
| AuthenTec Fingerprint Sensor                                | 1         | 4.17%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 1         | 4.17%   |
| AuthenTec AES1660 Fingerprint Sensor                        | 1         | 4.17%   |
| Unknown                                                     | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 66.67%  |
| O2 Micro    | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 33.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 215       | 75.17%  |
| 1     | 59        | 20.63%  |
| 2     | 9         | 3.15%   |
| 3     | 2         | 0.7%    |
| 4     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 29.27%  |
| Net/wireless             | 17        | 20.73%  |
| Graphics card            | 13        | 15.85%  |
| Multimedia controller    | 6         | 7.32%   |
| Communication controller | 5         | 6.1%    |
| Chipcard                 | 4         | 4.88%   |
| Unassigned class         | 3         | 3.66%   |
| Bluetooth                | 3         | 3.66%   |
| Storage                  | 2         | 2.44%   |
| Storage/ide              | 1         | 1.22%   |
| Sound                    | 1         | 1.22%   |
| Network                  | 1         | 1.22%   |
| Net/ethernet             | 1         | 1.22%   |
| Card reader              | 1         | 1.22%   |

