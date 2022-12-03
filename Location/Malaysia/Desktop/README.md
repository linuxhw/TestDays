Linux in Malaysia - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Malaysia.

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

Total: 195

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | 2B2C                        | [91862a2497](https://linux-hardware.org/?probe=91862a2497) | Nov 19, 2022 |
| HP       | 2B2C                        | [2eb8311f18](https://linux-hardware.org/?probe=2eb8311f18) | Nov 16, 2022 |
| MSI      | MPG X570 GAMING EDGE WIF... | [1fef4a8aa5](https://linux-hardware.org/?probe=1fef4a8aa5) | Nov 13, 2022 |
| MSI      | B450M-A PRO MAX             | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| Gigabyte | X570 UD                     | [29641e8b7c](https://linux-hardware.org/?probe=29641e8b7c) | Nov 09, 2022 |
| ASUSTek  | P7H55-M LE                  | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| ASUSTek  | P7H55-M LE                  | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Seco     | C40 C                       | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| Gigabyte | AX370M-Gaming 3-CF          | [abe170cf19](https://linux-hardware.org/?probe=abe170cf19) | Oct 27, 2022 |
| HP       | 2B2C                        | [df8a8ec9bc](https://linux-hardware.org/?probe=df8a8ec9bc) | Sep 29, 2022 |
| HP       | 18E7                        | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| ASUSTek  | ProArt Z690-CREATOR WIFI    | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| Intel    | DH61WW AAG23116-204         | [3310a4c592](https://linux-hardware.org/?probe=3310a4c592) | Sep 02, 2022 |
| Vorke    | V1 Plus                     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI      | B450M MORTAR MAX            | [25e7e97937](https://linux-hardware.org/?probe=25e7e97937) | Aug 29, 2022 |
| MSI      | B450M MORTAR MAX            | [9b0e2c480f](https://linux-hardware.org/?probe=9b0e2c480f) | Aug 28, 2022 |
| Dell     | 0PU052                      | [2bffd37724](https://linux-hardware.org/?probe=2bffd37724) | Aug 24, 2022 |
| ASUSTek  | P5G41T-M LX3                | [0aefa0613d](https://linux-hardware.org/?probe=0aefa0613d) | Aug 15, 2022 |
| ASUSTek  | P5G41T-M LX3                | [d000ce4d8c](https://linux-hardware.org/?probe=d000ce4d8c) | Aug 15, 2022 |
| Intel    | DH61WW AAG23116-204         | [30715e2f04](https://linux-hardware.org/?probe=30715e2f04) | Aug 01, 2022 |
| Lenovo   | ThinkCentre M58 7359DHJ     | [46c2c1db62](https://linux-hardware.org/?probe=46c2c1db62) | Jul 26, 2022 |
| ONDA     | H110-MINI V3.00 Ver:3.00    | [62b2a7897b](https://linux-hardware.org/?probe=62b2a7897b) | Jul 24, 2022 |
| Gigabyte | Z390 GAMING X-CF            | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| Gigabyte | X570 AORUS MASTER           | [aa2a721361](https://linux-hardware.org/?probe=aa2a721361) | Jul 15, 2022 |
| Gigabyte | B450M S2H                   | [0287348f80](https://linux-hardware.org/?probe=0287348f80) | Jul 12, 2022 |
| Intel    | MAHOBAY                     | [39c0379cee](https://linux-hardware.org/?probe=39c0379cee) | Jul 04, 2022 |
| Gigabyte | H470 HD3                    | [4857a7b7bf](https://linux-hardware.org/?probe=4857a7b7bf) | Jun 30, 2022 |
| ASUSTek  | ROG Maximus Z690 HERO       | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI      | MAG B660M MORTAR WIFI DD... | [c5a5b25674](https://linux-hardware.org/?probe=c5a5b25674) | Jun 28, 2022 |
| Intel    | MAHOBAY                     | [c292904665](https://linux-hardware.org/?probe=c292904665) | Jun 24, 2022 |
| ASUSTek  | CROSSHAIR VI HERO           | [2a4d1c8a0b](https://linux-hardware.org/?probe=2a4d1c8a0b) | Jun 19, 2022 |
| Lenovo   | 102F SDK0E50510 WIN 2625... | [35c05116d1](https://linux-hardware.org/?probe=35c05116d1) | Jun 16, 2022 |
| ASUSTek  | TUF Gaming B660M-PLUS WI... | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| ASUSTek  | TUF Gaming B660M-PLUS WI... | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| ASUSTek  | TUF Gaming B660M-PLUS WI... | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek  | TUF Gaming B660M-PLUS WI... | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| Gigabyte | X570 AORUS ELITE WIFI       | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| ASUSTek  | P5G41T-M LX3                | [43adb86887](https://linux-hardware.org/?probe=43adb86887) | Apr 25, 2022 |
| ASUSTek  | P5G41T-M LX3                | [ba9b8d5ac1](https://linux-hardware.org/?probe=ba9b8d5ac1) | Apr 25, 2022 |
| ECS      | Iris8                       | [1cff4313c1](https://linux-hardware.org/?probe=1cff4313c1) | Apr 23, 2022 |
| HP       | 2B2C                        | [195e5473e9](https://linux-hardware.org/?probe=195e5473e9) | Apr 20, 2022 |
| HP       | 2B2C                        | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| ASUSTek  | B85M-G                      | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| ASUSTek  | B85M-G                      | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte | H470 HD3                    | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| Intel    | DH61WW AAG23116-204         | [7ec10d98e3](https://linux-hardware.org/?probe=7ec10d98e3) | Apr 03, 2022 |
| Lenovo   | 30D9 NOK                    | [c378cd6fd3](https://linux-hardware.org/?probe=c378cd6fd3) | Mar 27, 2022 |
| Intel    | DH61WW AAG23116-204         | [a1c0612337](https://linux-hardware.org/?probe=a1c0612337) | Mar 17, 2022 |
| ASUSTek  | P8B75-M LX                  | [d52d9feb9e](https://linux-hardware.org/?probe=d52d9feb9e) | Mar 09, 2022 |
| ASUSTek  | P8B75-M LX                  | [8d3f72c54f](https://linux-hardware.org/?probe=8d3f72c54f) | Mar 03, 2022 |
| Biostar  | G41D3+                      | [62ba30cf71](https://linux-hardware.org/?probe=62ba30cf71) | Mar 02, 2022 |
| Dell     | 0D441T A03                  | [bbedea92ea](https://linux-hardware.org/?probe=bbedea92ea) | Mar 01, 2022 |
| Dell     | 0D441T A03                  | [297c168632](https://linux-hardware.org/?probe=297c168632) | Mar 01, 2022 |
| Shuttle  | FH170                       | [768e13fd34](https://linux-hardware.org/?probe=768e13fd34) | Feb 25, 2022 |
| ASUSTek  | H110M-D                     | [1dec2ddfad](https://linux-hardware.org/?probe=1dec2ddfad) | Feb 19, 2022 |
| MSI      | B450 TOMAHAWK               | [6b15f755b0](https://linux-hardware.org/?probe=6b15f755b0) | Jan 12, 2022 |
| Gigabyte | H470 HD3                    | [ff2f0db3fe](https://linux-hardware.org/?probe=ff2f0db3fe) | Jan 09, 2022 |
| Lenovo   | ThinkStation S10 6483CTO    | [0d867912a7](https://linux-hardware.org/?probe=0d867912a7) | Jan 01, 2022 |
| ECS      | H61H2-M12                   | [c8ca1c8cc8](https://linux-hardware.org/?probe=c8ca1c8cc8) | Dec 24, 2021 |
| MSI      | MAG B460 TOMAHAWK           | [c748f77108](https://linux-hardware.org/?probe=c748f77108) | Dec 12, 2021 |
| HP       | 2B44                        | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| ASUSTek  | TUF Gaming B550-PLUS        | [5c4ae3bd8c](https://linux-hardware.org/?probe=5c4ae3bd8c) | Nov 30, 2021 |
| ECS      | H61H2-M12                   | [c731d25471](https://linux-hardware.org/?probe=c731d25471) | Nov 30, 2021 |
| Dell     | 048DY8 A01                  | [6e5e669c60](https://linux-hardware.org/?probe=6e5e669c60) | Nov 25, 2021 |
| ECS      | H61H2-M12                   | [b5393ad660](https://linux-hardware.org/?probe=b5393ad660) | Nov 12, 2021 |
| ASUSTek  | M2N32-SLI DELUXE            | [87fff05f0f](https://linux-hardware.org/?probe=87fff05f0f) | Nov 03, 2021 |
| Intel    | B75                         | [fef715f491](https://linux-hardware.org/?probe=fef715f491) | Oct 23, 2021 |
| Gigabyte | H370M D3H-CF                | [8fee3106f7](https://linux-hardware.org/?probe=8fee3106f7) | Oct 12, 2021 |
| Gigabyte | H370M D3H-CF                | [f79000e059](https://linux-hardware.org/?probe=f79000e059) | Oct 12, 2021 |
| Biostar  | G41D3C                      | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Biostar  | G41D3C                      | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| Gigabyte | B85M-D3H                    | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| Lenovo   | MAHOBAY NOK                 | [c2533e9d48](https://linux-hardware.org/?probe=c2533e9d48) | Sep 11, 2021 |
| MSI      | H81M-P33                    | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| Biostar  | G41D3C                      | [8137e09a97](https://linux-hardware.org/?probe=8137e09a97) | Sep 08, 2021 |
| Biostar  | G41D3C                      | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| Gigabyte | B85M-D3H                    | [5377e486bc](https://linux-hardware.org/?probe=5377e486bc) | Sep 03, 2021 |
| MSI      | MAG B460 TOMAHAWK           | [a61ee6d83a](https://linux-hardware.org/?probe=a61ee6d83a) | Sep 01, 2021 |
| Biostar  | G41D3C                      | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar  | G41D3C                      | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| MSI      | MAG B460 TOMAHAWK           | [a1ec21ae3f](https://linux-hardware.org/?probe=a1ec21ae3f) | Aug 29, 2021 |
| ASRock   | H81M-VG4 R2.0               | [cac6720bff](https://linux-hardware.org/?probe=cac6720bff) | Aug 29, 2021 |
| Gigabyte | B450M S2H V2                | [777faedb05](https://linux-hardware.org/?probe=777faedb05) | Aug 27, 2021 |
| Gigabyte | B85M-D3H                    | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte | B85M-D3H                    | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Gigabyte | B450M S2H V2                | [9e8fa8f32d](https://linux-hardware.org/?probe=9e8fa8f32d) | Aug 23, 2021 |
| Lenovo   | 1046 SDK0T08861 WIN 3305... | [de1fa2ccc0](https://linux-hardware.org/?probe=de1fa2ccc0) | Aug 20, 2021 |
| Intel    | DH61WW AAG23116-204         | [89188fe3ca](https://linux-hardware.org/?probe=89188fe3ca) | Aug 08, 2021 |
| Gigabyte | B85M-D3H                    | [3e56e95f2f](https://linux-hardware.org/?probe=3e56e95f2f) | Aug 05, 2021 |
| ASUSTek  | P8Z77-V LX                  | [36562061d6](https://linux-hardware.org/?probe=36562061d6) | Jul 30, 2021 |
| ASUSTek  | P8B75-M LE                  | [e71a7fc65b](https://linux-hardware.org/?probe=e71a7fc65b) | Jul 23, 2021 |
| Dell     | 0427JK A00                  | [3e66028cf8](https://linux-hardware.org/?probe=3e66028cf8) | Jul 22, 2021 |
| ASUSTek  | P8B75-M                     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek  | P8B75-M                     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| ASUSTek  | PRIME H310M-D R2.0          | [5a349c4952](https://linux-hardware.org/?probe=5a349c4952) | Jul 19, 2021 |
| Intel    | DH61WW AAG23116-204         | [275304e806](https://linux-hardware.org/?probe=275304e806) | Jul 19, 2021 |
| Intel    | DH61WW AAG23116-204         | [99df792e3b](https://linux-hardware.org/?probe=99df792e3b) | Jul 18, 2021 |
| Gigabyte | M61PME-S2P                  | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| Intel    | DH61WW AAG23116-204         | [2495cf9be5](https://linux-hardware.org/?probe=2495cf9be5) | Jul 12, 2021 |
| Gigabyte | B85M-D3H                    | [b551baea7d](https://linux-hardware.org/?probe=b551baea7d) | Jul 11, 2021 |
| Dell     | 0427JK A00                  | [82c73cf6be](https://linux-hardware.org/?probe=82c73cf6be) | Jul 09, 2021 |
| MSI      | B450M MORTAR                | [e8965c736d](https://linux-hardware.org/?probe=e8965c736d) | Jul 05, 2021 |
| Intel    | DH61WW AAG23116-204         | [a5a80d3f13](https://linux-hardware.org/?probe=a5a80d3f13) | Jun 24, 2021 |
| Dell     | 0427JK A00                  | [d9270ab2c1](https://linux-hardware.org/?probe=d9270ab2c1) | Jun 23, 2021 |
| MSI      | B450M MORTAR                | [0183eeb644](https://linux-hardware.org/?probe=0183eeb644) | Jun 12, 2021 |
| MSI      | H81M-P33                    | [69a8b43e74](https://linux-hardware.org/?probe=69a8b43e74) | Jun 02, 2021 |
| MSI      | H81M-P33                    | [a67e6bcfce](https://linux-hardware.org/?probe=a67e6bcfce) | Jun 02, 2021 |
| Gigabyte | AB350M-Gaming 3-CF          | [00658a23ab](https://linux-hardware.org/?probe=00658a23ab) | May 27, 2021 |
| ASUSTek  | H97M-E                      | [5f39051050](https://linux-hardware.org/?probe=5f39051050) | May 26, 2021 |
| Gigabyte | B450M S2H                   | [4c5c7570f6](https://linux-hardware.org/?probe=4c5c7570f6) | May 25, 2021 |
| ASUSTek  | P8Z68-V PRO                 | [2b0de1ba10](https://linux-hardware.org/?probe=2b0de1ba10) | May 21, 2021 |
| ASUSTek  | GRYPHON Z87                 | [0cd0f0c51f](https://linux-hardware.org/?probe=0cd0f0c51f) | May 13, 2021 |
| HP       | 0AA8h                       | [5f350b471f](https://linux-hardware.org/?probe=5f350b471f) | Apr 29, 2021 |
| Gigabyte | Z97X-Gaming G1              | [07efcf431f](https://linux-hardware.org/?probe=07efcf431f) | Apr 14, 2021 |
| Gigabyte | Z97X-Gaming G1              | [9f265d798d](https://linux-hardware.org/?probe=9f265d798d) | Apr 14, 2021 |
| AMI      | Cherry Trail Tablet         | [87041c97fb](https://linux-hardware.org/?probe=87041c97fb) | Apr 14, 2021 |
| ASUSTek  | P5QPL-VM EPU                | [6d3642385e](https://linux-hardware.org/?probe=6d3642385e) | Apr 11, 2021 |
| ASUSTek  | P5QPL-VM EPU                | [fc405347a5](https://linux-hardware.org/?probe=fc405347a5) | Mar 12, 2021 |
| ASUSTek  | H110M-D                     | [19e3cff2be](https://linux-hardware.org/?probe=19e3cff2be) | Feb 27, 2021 |
| Gigabyte | A320M-S2H V2-CF             | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| Acer     | MCP73VE NVIDIA MCP73        | [b50872caf4](https://linux-hardware.org/?probe=b50872caf4) | Feb 07, 2021 |
| MSI      | A320M-A PRO MAX             | [7daa68908c](https://linux-hardware.org/?probe=7daa68908c) | Feb 06, 2021 |
| Acer     | MCP73VE NVIDIA MCP73        | [acb369859f](https://linux-hardware.org/?probe=acb369859f) | Feb 06, 2021 |
| Acer     | Veriton X6630G V:1.0        | [d6126d9f25](https://linux-hardware.org/?probe=d6126d9f25) | Jan 27, 2021 |
| Acer     | Veriton X6630G V:1.0        | [9e5a28d45d](https://linux-hardware.org/?probe=9e5a28d45d) | Jan 27, 2021 |
| Dell     | 0WR7PY A01                  | [9b13ab689f](https://linux-hardware.org/?probe=9b13ab689f) | Jan 24, 2021 |
| Dell     | 0WMJ54 A01                  | [dd87c824a0](https://linux-hardware.org/?probe=dd87c824a0) | Jan 18, 2021 |
| ASUSTek  | P8Z77-V LX                  | [9e291d5782](https://linux-hardware.org/?probe=9e291d5782) | Jan 12, 2021 |
| Intel    | DH77KC AAG39641-400         | [f3c691cbf8](https://linux-hardware.org/?probe=f3c691cbf8) | Jan 01, 2021 |
| MSI      | H81M-P33                    | [e8d73a49e5](https://linux-hardware.org/?probe=e8d73a49e5) | Dec 30, 2020 |
| Intel    | DH61WW AAG23116-300         | [7e473c8d12](https://linux-hardware.org/?probe=7e473c8d12) | Dec 24, 2020 |
| Intel    | DH61WW AAG23116-300         | [645dfe5a80](https://linux-hardware.org/?probe=645dfe5a80) | Dec 23, 2020 |
| Dell     | 0PU052                      | [520a4ef3d0](https://linux-hardware.org/?probe=520a4ef3d0) | Dec 23, 2020 |
| Biostar  | A320MH                      | [a6b1134a37](https://linux-hardware.org/?probe=a6b1134a37) | Dec 18, 2020 |
| Gigabyte | F2A88XM-HD3P                | [a0b90b128d](https://linux-hardware.org/?probe=a0b90b128d) | Dec 16, 2020 |
| Gigabyte | H77M-D3H                    | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte | H77M-D3H                    | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| Intel    | DH61WW AAG23116-300         | [414fc579a1](https://linux-hardware.org/?probe=414fc579a1) | Dec 02, 2020 |
| Intel    | DH61WW AAG23116-300         | [cf6242caca](https://linux-hardware.org/?probe=cf6242caca) | Dec 02, 2020 |
| Intel    | DH61WW AAG23116-300         | [afbf8ce7bc](https://linux-hardware.org/?probe=afbf8ce7bc) | Dec 01, 2020 |
| ASRock   | G41C-GS                     | [c323f09a39](https://linux-hardware.org/?probe=c323f09a39) | Nov 17, 2020 |
| Gigabyte | Z490 VISION D               | [af58d1579d](https://linux-hardware.org/?probe=af58d1579d) | Nov 09, 2020 |
| ASUSTek  | B85M-G                      | [5021546be8](https://linux-hardware.org/?probe=5021546be8) | Oct 30, 2020 |
| ASUSTek  | PRIME B350-PLUS             | [b6aa803efb](https://linux-hardware.org/?probe=b6aa803efb) | Oct 21, 2020 |
| ASUSTek  | PRIME B350-PLUS             | [02a2657831](https://linux-hardware.org/?probe=02a2657831) | Oct 20, 2020 |
| Dell     | 09WH54 A00                  | [5c8d0c0991](https://linux-hardware.org/?probe=5c8d0c0991) | Oct 15, 2020 |
| Dell     | 06D7TR A02                  | [1fff522fa1](https://linux-hardware.org/?probe=1fff522fa1) | Oct 13, 2020 |
| Dell     | 09WH54 A00                  | [e8e5a3c2ac](https://linux-hardware.org/?probe=e8e5a3c2ac) | Oct 12, 2020 |
| Dell     | 0RW203                      | [594ab9e6d3](https://linux-hardware.org/?probe=594ab9e6d3) | Sep 02, 2020 |
| Gigabyte | B450M S2H                   | [0930a62ca5](https://linux-hardware.org/?probe=0930a62ca5) | Aug 21, 2020 |
| ASUSTek  | Z170 PRO GAMING             | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| ASUSTek  | H110M-D                     | [bc44361c47](https://linux-hardware.org/?probe=bc44361c47) | Aug 02, 2020 |
| ASUSTek  | H110M-D                     | [e8cc620228](https://linux-hardware.org/?probe=e8cc620228) | Aug 02, 2020 |
| Gigabyte | B85M-D3H                    | [3f99c1674c](https://linux-hardware.org/?probe=3f99c1674c) | Jul 30, 2020 |
| Dell     | 0D6H9T A00                  | [dbbc5219fd](https://linux-hardware.org/?probe=dbbc5219fd) | Jul 27, 2020 |
| Gigabyte | B85M-D3H                    | [2bfaffc9c5](https://linux-hardware.org/?probe=2bfaffc9c5) | Jul 21, 2020 |
| Gigabyte | H61M-S2P-R3                 | [7b83e5785f](https://linux-hardware.org/?probe=7b83e5785f) | Jul 19, 2020 |
| Gigabyte | B85M-D3H                    | [ab9fa86313](https://linux-hardware.org/?probe=ab9fa86313) | Jul 16, 2020 |
| Gigabyte | GA-890GPA-UD3H              | [7d9a43933e](https://linux-hardware.org/?probe=7d9a43933e) | Jul 14, 2020 |
| Biostar  | H81MHV3                     | [48cdbb3d36](https://linux-hardware.org/?probe=48cdbb3d36) | Jul 11, 2020 |
| Biostar  | H81MHV3                     | [a97a2e14e2](https://linux-hardware.org/?probe=a97a2e14e2) | Jul 06, 2020 |
| Gigabyte | B85M-D3H                    | [5d32eb1d75](https://linux-hardware.org/?probe=5d32eb1d75) | Jun 30, 2020 |
| Acer     | Aspire XC600 v1.0           | [99ff555015](https://linux-hardware.org/?probe=99ff555015) | Jun 21, 2020 |
| Gigabyte | GA-890GPA-UD3H              | [05556ef252](https://linux-hardware.org/?probe=05556ef252) | Jun 19, 2020 |
| Acer     | Aspire XC600 v1.0           | [eac1260628](https://linux-hardware.org/?probe=eac1260628) | Jun 17, 2020 |
| ASRock   | Z77 Extreme4                | [ba4a677fab](https://linux-hardware.org/?probe=ba4a677fab) | Jun 10, 2020 |
| MSI      | A320M-A PRO MAX             | [11c6b72a1b](https://linux-hardware.org/?probe=11c6b72a1b) | Jun 03, 2020 |
| MSI      | A320M-A PRO MAX             | [ecf8e72f94](https://linux-hardware.org/?probe=ecf8e72f94) | May 31, 2020 |
| ASRock   | Z77 Extreme4                | [865933043f](https://linux-hardware.org/?probe=865933043f) | May 26, 2020 |
| Acer     | EQ45M                       | [a682473a39](https://linux-hardware.org/?probe=a682473a39) | May 23, 2020 |
| Gigabyte | B85M-D3H                    | [d2113ac640](https://linux-hardware.org/?probe=d2113ac640) | May 21, 2020 |
| Dell     | 0PU052                      | [40ab4a84b5](https://linux-hardware.org/?probe=40ab4a84b5) | May 18, 2020 |
| Gigabyte | B85M-D3H                    | [8156a3eef6](https://linux-hardware.org/?probe=8156a3eef6) | May 11, 2020 |
| Dell     | 0RY007                      | [4d44e2723d](https://linux-hardware.org/?probe=4d44e2723d) | May 04, 2020 |
| Acer     | EQ45M                       | [03e154e2dc](https://linux-hardware.org/?probe=03e154e2dc) | Apr 21, 2020 |
| Dell     | 0C3YXR A01                  | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| ASUSTek  | TUF B360-PLUS GAMING        | [0444963962](https://linux-hardware.org/?probe=0444963962) | Apr 12, 2020 |
| MSI      | B150M Night Elf             | [01013b611d](https://linux-hardware.org/?probe=01013b611d) | Apr 11, 2020 |
| Gigabyte | H61M-S2P-R3                 | [1211d7770c](https://linux-hardware.org/?probe=1211d7770c) | Mar 15, 2020 |
| ASUSTek  | P6T SE                      | [05737b4c23](https://linux-hardware.org/?probe=05737b4c23) | Feb 11, 2020 |
| HP       | 3647h                       | [06df72e240](https://linux-hardware.org/?probe=06df72e240) | Feb 08, 2020 |
| ASUSTek  | P8Z77-M                     | [9247337003](https://linux-hardware.org/?probe=9247337003) | Jan 20, 2020 |
| ASUSTek  | P6T SE                      | [02d013ad00](https://linux-hardware.org/?probe=02d013ad00) | Dec 20, 2019 |
| ASUSTek  | P6T SE                      | [9e78c03471](https://linux-hardware.org/?probe=9e78c03471) | Nov 17, 2019 |
| ASUSTek  | F1A55-M LX PLUS             | [875f14ed53](https://linux-hardware.org/?probe=875f14ed53) | Nov 13, 2019 |
| ASUSTek  | P6T SE                      | [7ce70fa206](https://linux-hardware.org/?probe=7ce70fa206) | Oct 25, 2019 |
| ASUSTek  | P5QPL-AM                    | [b37e090603](https://linux-hardware.org/?probe=b37e090603) | Oct 06, 2019 |
| HP       | 0AA8h                       | [a60543a450](https://linux-hardware.org/?probe=a60543a450) | Sep 07, 2019 |
| Dell     | 0RY007                      | [576ec7dcd0](https://linux-hardware.org/?probe=576ec7dcd0) | Aug 22, 2019 |
| ASUSTek  | Maximus VII RANGER          | [d9d789a4f2](https://linux-hardware.org/?probe=d9d789a4f2) | Aug 21, 2019 |
| ASUSTek  | P6T SE                      | [a91c21a426](https://linux-hardware.org/?probe=a91c21a426) | Aug 02, 2019 |
| ASUSTek  | H81M-C                      | [38a96dff85](https://linux-hardware.org/?probe=38a96dff85) | Jul 02, 2019 |
| ASUSTek  | ROG STRIX Z370-F GAMING     | [62b0b05a66](https://linux-hardware.org/?probe=62b0b05a66) | Jul 01, 2019 |
| ASRock   | X79 Extreme9                | [c96c05c47b](https://linux-hardware.org/?probe=c96c05c47b) | Nov 30, 2018 |
| HP       | 2820h                       | [1f42af0283](https://linux-hardware.org/?probe=1f42af0283) | Dec 17, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 28       | 19.72%  |
| Ubuntu 18.04                 | 9        | 6.34%   |
| Zorin 16                     | 6        | 4.23%   |
| OpenMandriva 4.3             | 6        | 4.23%   |
| OpenMandriva 4.2             | 6        | 4.23%   |
| Pop!_OS 20.04                | 5        | 3.52%   |
| OpenMandriva 4.50            | 5        | 3.52%   |
| Ubuntu 19.04                 | 4        | 2.82%   |
| Debian 11                    | 4        | 2.82%   |
| Xubuntu 18.04                | 3        | 2.11%   |
| Linux Mint 19.3              | 3        | 2.11%   |
| Fedora 33                    | 3        | 2.11%   |
| ArcoLinux Rolling            | 3        | 2.11%   |
| Zorin 15                     | 2        | 1.41%   |
| Ubuntu 22.04                 | 2        | 1.41%   |
| Ubuntu 19.10                 | 2        | 1.41%   |
| Pop!_OS 21.04                | 2        | 1.41%   |
| Pop!_OS 20.10                | 2        | 1.41%   |
| Manjaro 21.2.6               | 2        | 1.41%   |
| Linux Mint 20.3              | 2        | 1.41%   |
| KDE neon 20.04               | 2        | 1.41%   |
| Fedora 34                    | 2        | 1.41%   |
| Arch                         | 2        | 1.41%   |
| Ubuntu MATE 20.04            | 1        | 0.7%    |
| Ubuntu 21.10                 | 1        | 0.7%    |
| Ubuntu 21.04                 | 1        | 0.7%    |
| Ubuntu 20.10                 | 1        | 0.7%    |
| ROSA R10                     | 1        | 0.7%    |
| Pop!_OS 22.04                | 1        | 0.7%    |
| Pop!_OS 21.10                | 1        | 0.7%    |
| openSUSE Tumbleweed-XXXXXXXX | 1        | 0.7%    |
| Manjaro 21.1.1               | 1        | 0.7%    |
| Manjaro 21.0.5               | 1        | 0.7%    |
| Manjaro                      | 1        | 0.7%    |
| Lubuntu 20.10                | 1        | 0.7%    |
| Lubuntu 20.04                | 1        | 0.7%    |
| Linux Mint 21                | 1        | 0.7%    |
| Linux Mint 20.2              | 1        | 0.7%    |
| Linux Mint 20.1              | 1        | 0.7%    |
| Linux Mint 20                | 1        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 46       | 34.07%  |
| OpenMandriva | 16       | 11.85%  |
| Pop!_OS      | 9        | 6.67%   |
| Linux Mint   | 9        | 6.67%   |
| Zorin        | 8        | 5.93%   |
| Fedora       | 7        | 5.19%   |
| Manjaro      | 5        | 3.7%    |
| Debian       | 5        | 3.7%    |
| Xubuntu      | 3        | 2.22%   |
| KDE neon     | 3        | 2.22%   |
| Endless      | 3        | 2.22%   |
| Elementary   | 3        | 2.22%   |
| ArcoLinux    | 3        | 2.22%   |
| Lubuntu      | 2        | 1.48%   |
| Kubuntu      | 2        | 1.48%   |
| Kali         | 2        | 1.48%   |
| Arch         | 2        | 1.48%   |
| Ubuntu MATE  | 1        | 0.74%   |
| ROSA         | 1        | 0.74%   |
| openSUSE     | 1        | 0.74%   |
| Linux Lite   | 1        | 0.74%   |
| Gentoo       | 1        | 0.74%   |
| EndeavourOS  | 1        | 0.74%   |
| CentOS       | 1        | 0.74%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002      | 6        | 3.92%   |
| 5.4.0-58-generic              | 5        | 3.27%   |
| 5.4.0-42-generic              | 4        | 2.61%   |
| 5.16.7-desktop-1omv4003       | 4        | 2.61%   |
| 5.4.0-40-generic              | 3        | 1.96%   |
| 5.3.0-53-generic              | 3        | 1.96%   |
| 5.3.0-46-generic              | 3        | 1.96%   |
| 5.16.3-desktop-2omv4050       | 3        | 1.96%   |
| 5.15.0-52-generic             | 3        | 1.96%   |
| 5.11.0-27-generic             | 3        | 1.96%   |
| 5.8.0-53-generic              | 2        | 1.31%   |
| 5.8.0-44-generic              | 2        | 1.31%   |
| 5.8.0-41-generic              | 2        | 1.31%   |
| 5.4.0-77-generic              | 2        | 1.31%   |
| 5.4.0-7634-generic            | 2        | 1.31%   |
| 5.4.0-48-generic              | 2        | 1.31%   |
| 5.4.0-37-generic              | 2        | 1.31%   |
| 5.4.0-29-generic              | 2        | 1.31%   |
| 5.15.35-3-pve                 | 2        | 1.31%   |
| 5.15.0-39-generic             | 2        | 1.31%   |
| 5.12.7-desktop-clang-1omv4003 | 2        | 1.31%   |
| 5.12.4-desktop-1omv4050       | 2        | 1.31%   |
| 5.12.15-300.fc34.x86_64       | 2        | 1.31%   |
| 5.11.0-41-generic             | 2        | 1.31%   |
| 5.11.0-35-generic             | 2        | 1.31%   |
| 5.11.0-34-generic             | 2        | 1.31%   |
| 5.0.0-27-generic              | 2        | 1.31%   |
| 6.0.3-76060003-generic        | 1        | 0.65%   |
| 5.9.8-arch1-1                 | 1        | 0.65%   |
| 5.9.14-200.fc33.x86_64        | 1        | 0.65%   |
| 5.9.1-1-MANJARO               | 1        | 0.65%   |
| 5.8.0-7630-generic            | 1        | 0.65%   |
| 5.8.0-59-generic              | 1        | 0.65%   |
| 5.8.0-49-generic              | 1        | 0.65%   |
| 5.8.0-48-generic              | 1        | 0.65%   |
| 5.8.0-40-generic              | 1        | 0.65%   |
| 5.8.0-31-generic              | 1        | 0.65%   |
| 5.4.0-88-generic              | 1        | 0.65%   |
| 5.4.0-84-generic              | 1        | 0.65%   |
| 5.4.0-7625-generic            | 1        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 22.7%   |
| 5.11.0  | 12       | 8.51%   |
| 5.8.0   | 11       | 7.8%    |
| 5.15.0  | 9        | 6.38%   |
| 5.3.0   | 8        | 5.67%   |
| 5.0.0   | 7        | 4.96%   |
| 5.10.14 | 6        | 4.26%   |
| 4.15.0  | 6        | 4.26%   |
| 5.16.7  | 4        | 2.84%   |
| 5.13.0  | 4        | 2.84%   |
| 5.16.3  | 3        | 2.13%   |
| 5.18.0  | 2        | 1.42%   |
| 5.17.1  | 2        | 1.42%   |
| 5.15.35 | 2        | 1.42%   |
| 5.12.7  | 2        | 1.42%   |
| 5.12.4  | 2        | 1.42%   |
| 5.12.15 | 2        | 1.42%   |
| 5.10.0  | 2        | 1.42%   |
| 4.18.0  | 2        | 1.42%   |
| 6.0.3   | 1        | 0.71%   |
| 5.9.8   | 1        | 0.71%   |
| 5.9.14  | 1        | 0.71%   |
| 5.9.1   | 1        | 0.71%   |
| 5.19.9  | 1        | 0.71%   |
| 5.18.7  | 1        | 0.71%   |
| 5.18.18 | 1        | 0.71%   |
| 5.17.6  | 1        | 0.71%   |
| 5.17.3  | 1        | 0.71%   |
| 5.16.19 | 1        | 0.71%   |
| 5.16.0  | 1        | 0.71%   |
| 5.15.8  | 1        | 0.71%   |
| 5.15.64 | 1        | 0.71%   |
| 5.15.15 | 1        | 0.71%   |
| 5.15.13 | 1        | 0.71%   |
| 5.15.12 | 1        | 0.71%   |
| 5.14.18 | 1        | 0.71%   |
| 5.14.11 | 1        | 0.71%   |
| 5.14.0  | 1        | 0.71%   |
| 5.13.12 | 1        | 0.71%   |
| 5.11.15 | 1        | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 22.86%  |
| 5.15    | 16       | 11.43%  |
| 5.11    | 13       | 9.29%   |
| 5.8     | 11       | 7.86%   |
| 5.16    | 9        | 6.43%   |
| 5.10    | 9        | 6.43%   |
| 5.3     | 8        | 5.71%   |
| 5.0     | 7        | 5%      |
| 5.12    | 6        | 4.29%   |
| 4.15    | 6        | 4.29%   |
| 5.13    | 5        | 3.57%   |
| 5.18    | 4        | 2.86%   |
| 5.9     | 3        | 2.14%   |
| 5.17    | 3        | 2.14%   |
| 5.14    | 3        | 2.14%   |
| 4.18    | 2        | 1.43%   |
| 6.0     | 1        | 0.71%   |
| 5.19    | 1        | 0.71%   |
| 4.9     | 1        | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 128      | 98.46%  |
| i686   | 2        | 1.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 61       | 45.52%  |
| KDE5       | 24       | 17.91%  |
| Unknown    | 13       | 9.7%    |
| XFCE       | 11       | 8.21%   |
| X-Cinnamon | 7        | 5.22%   |
| MATE       | 6        | 4.48%   |
| Pantheon   | 3        | 2.24%   |
| Openbox    | 3        | 2.24%   |
| KDE        | 3        | 2.24%   |
| LXQt       | 2        | 1.49%   |
| Cinnamon   | 1        | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 112      | 85.5%   |
| Wayland | 8        | 6.11%   |
| Unknown | 7        | 5.34%   |
| Tty     | 4        | 3.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 79       | 59.4%   |
| SDDM    | 26       | 19.55%  |
| LightDM | 11       | 8.27%   |
| GDM     | 8        | 6.02%   |
| GDM3    | 6        | 4.51%   |
| TDM     | 3        | 2.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 98       | 74.24%  |
| en_GB   | 11       | 8.33%   |
| Unknown | 10       | 7.58%   |
| en_SG   | 7        | 5.3%    |
| en_AU   | 3        | 2.27%   |
| zh_CN   | 1        | 0.76%   |
| en_MY   | 1        | 0.76%   |
| en_HK   | 1        | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 86       | 65.15%  |
| EFI  | 46       | 34.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 101      | 75.94%  |
| Overlay | 12       | 9.02%   |
| Btrfs   | 8        | 6.02%   |
| Unknown | 4        | 3.01%   |
| Zfs     | 3        | 2.26%   |
| Xfs     | 3        | 2.26%   |
| Ext3    | 1        | 0.75%   |
| Ext2    | 1        | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 80       | 61.54%  |
| GPT     | 28       | 21.54%  |
| MBR     | 22       | 16.92%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 77.44%  |
| Yes       | 30       | 22.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 65.15%  |
| Yes       | 46       | 34.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 31       | 23.85%  |
| Gigabyte Technology | 22       | 16.92%  |
| Dell                | 16       | 12.31%  |
| MSI                 | 14       | 10.77%  |
| Intel               | 14       | 10.77%  |
| Hewlett-Packard     | 7        | 5.38%   |
| Lenovo              | 6        | 4.62%   |
| Biostar             | 5        | 3.85%   |
| ASRock              | 4        | 3.08%   |
| Acer                | 4        | 3.08%   |
| ECS                 | 2        | 1.54%   |
| Vorke               | 1        | 0.77%   |
| Shuttle             | 1        | 0.77%   |
| Seco                | 1        | 0.77%   |
| ONDA                | 1        | 0.77%   |
| AMI                 | 1        | 0.77%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Intel DH61WW AAG23116-204           | 7        | 5.38%   |
| ASUS All Series                     | 6        | 4.62%   |
| MSI MS-7C52                         | 3        | 2.31%   |
| MSI MS-7817                         | 3        | 2.31%   |
| Intel DH61WW AAG23116-300           | 3        | 2.31%   |
| Gigabyte B85M-D3H                   | 3        | 2.31%   |
| Dell OptiPlex 755                   | 3        | 2.31%   |
| MSI MS-7C81                         | 2        | 1.54%   |
| MSI MS-7B89                         | 2        | 1.54%   |
| Intel MAHOBAY                       | 2        | 1.54%   |
| Gigabyte B450M S2H                  | 2        | 1.54%   |
| Dell XPS 8940                       | 2        | 1.54%   |
| Dell OptiPlex 990                   | 2        | 1.54%   |
| Biostar G41D3C                      | 2        | 1.54%   |
| ASUS P8Z77-V LX                     | 2        | 1.54%   |
| Vorke V1 Plus                       | 1        | 0.77%   |
| Shuttle DH170                       | 1        | 0.77%   |
| Seco C40                            | 1        | 0.77%   |
| ONDA H110-MINI V3.00                | 1        | 0.77%   |
| MSI MS-7D42                         | 1        | 0.77%   |
| MSI MS-7C37                         | 1        | 0.77%   |
| MSI MS-7C02                         | 1        | 0.77%   |
| MSI MS-7979                         | 1        | 0.77%   |
| Lenovo ThinkStation S10 6483CTO     | 1        | 0.77%   |
| Lenovo ThinkStation P620 30E0S0E000 | 1        | 0.77%   |
| Lenovo ThinkStation P500 30A6S1B50X | 1        | 0.77%   |
| Lenovo ThinkCentre M72e 32673M3     | 1        | 0.77%   |
| Lenovo ThinkCentre M700 10GQCTO1WW  | 1        | 0.77%   |
| Lenovo ThinkCentre M58 7359DHJ      | 1        | 0.77%   |
| Intel DH77KC AAG39641-400           | 1        | 0.77%   |
| Intel B75                           | 1        | 0.77%   |
| HP ProDesk 600 G1 TWR               | 1        | 0.77%   |
| HP Compaq dc7800p Small Form Factor | 1        | 0.77%   |
| HP Compaq dc7800 Small Form Factor  | 1        | 0.77%   |
| HP Compaq dc5800 Small Form Factor  | 1        | 0.77%   |
| HP Compaq 8000 Elite CMT PC         | 1        | 0.77%   |
| HP 500-536d                         | 1        | 0.77%   |
| HP 23-q145d                         | 1        | 0.77%   |
| Gigabyte Z97X-Gaming G1             | 1        | 0.77%   |
| Gigabyte Z490 VISION D              | 1        | 0.77%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Intel DH61WW         | 10       | 7.69%   |
| Dell OptiPlex        | 8        | 6.15%   |
| ASUS All             | 6        | 4.62%   |
| HP Compaq            | 4        | 3.08%   |
| Dell Precision       | 4        | 3.08%   |
| MSI MS-7C52          | 3        | 2.31%   |
| MSI MS-7817          | 3        | 2.31%   |
| Lenovo ThinkStation  | 3        | 2.31%   |
| Lenovo ThinkCentre   | 3        | 2.31%   |
| Gigabyte X570        | 3        | 2.31%   |
| Gigabyte B85M-D3H    | 3        | 2.31%   |
| Gigabyte B450M       | 3        | 2.31%   |
| ASUS TUF             | 3        | 2.31%   |
| ASUS P8B75-M         | 3        | 2.31%   |
| MSI MS-7C81          | 2        | 1.54%   |
| MSI MS-7B89          | 2        | 1.54%   |
| Intel MAHOBAY        | 2        | 1.54%   |
| Dell XPS             | 2        | 1.54%   |
| Dell Inspiron        | 2        | 1.54%   |
| Biostar G41D3C       | 2        | 1.54%   |
| ASUS ROG             | 2        | 1.54%   |
| ASUS PRIME           | 2        | 1.54%   |
| ASUS P8Z77-V         | 2        | 1.54%   |
| Acer Veriton         | 2        | 1.54%   |
| Acer Aspire          | 2        | 1.54%   |
| Vorke V1             | 1        | 0.77%   |
| Shuttle DH170        | 1        | 0.77%   |
| Seco C40             | 1        | 0.77%   |
| ONDA H110-MINI       | 1        | 0.77%   |
| MSI MS-7D42          | 1        | 0.77%   |
| MSI MS-7C37          | 1        | 0.77%   |
| MSI MS-7C02          | 1        | 0.77%   |
| MSI MS-7979          | 1        | 0.77%   |
| Intel DH77KC         | 1        | 0.77%   |
| Intel B75            | 1        | 0.77%   |
| HP ProDesk           | 1        | 0.77%   |
| HP 500-536d          | 1        | 0.77%   |
| HP 23-q145d          | 1        | 0.77%   |
| Gigabyte Z97X-Gaming | 1        | 0.77%   |
| Gigabyte Z490        | 1        | 0.77%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 16       | 12.31%  |
| 2018 | 14       | 10.77%  |
| 2013 | 13       | 10%     |
| 2011 | 12       | 9.23%   |
| 2019 | 10       | 7.69%   |
| 2015 | 9        | 6.92%   |
| 2020 | 8        | 6.15%   |
| 2021 | 7        | 5.38%   |
| 2017 | 7        | 5.38%   |
| 2010 | 7        | 5.38%   |
| 2008 | 7        | 5.38%   |
| 2007 | 7        | 5.38%   |
| 2009 | 6        | 4.62%   |
| 2014 | 5        | 3.85%   |
| 2022 | 1        | 0.77%   |
| 2006 | 1        | 0.77%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 130      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 126      | 96.92%  |
| Enabled  | 4        | 3.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 130      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 33       | 25%     |
| 8.01-16.0   | 24       | 18.18%  |
| 4.01-8.0    | 23       | 17.42%  |
| 3.01-4.0    | 18       | 13.64%  |
| 32.01-64.0  | 16       | 12.12%  |
| 1.01-2.0    | 8        | 6.06%   |
| 64.01-256.0 | 5        | 3.79%   |
| 24.01-32.0  | 3        | 2.27%   |
| 2.01-3.0    | 2        | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 47       | 32.41%  |
| 2.01-3.0   | 42       | 28.97%  |
| 3.01-4.0   | 20       | 13.79%  |
| 4.01-8.0   | 13       | 8.97%   |
| 0.51-1.0   | 12       | 8.28%   |
| 8.01-16.0  | 7        | 4.83%   |
| 0.01-0.5   | 2        | 1.38%   |
| 32.01-64.0 | 1        | 0.69%   |
| 24.01-32.0 | 1        | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 51       | 37.5%   |
| 2      | 41       | 30.15%  |
| 3      | 19       | 13.97%  |
| 4      | 10       | 7.35%   |
| 5      | 8        | 5.88%   |
| 7      | 3        | 2.21%   |
| 6      | 3        | 2.21%   |
| 8      | 1        | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 60.31%  |
| Yes       | 52       | 39.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 118      | 90.77%  |
| No        | 12       | 9.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 83       | 62.88%  |
| No        | 49       | 37.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 66.41%  |
| Yes       | 44       | 33.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Malaysia | 130      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Kuala Lumpur           | 47       | 33.33%  |
| Petaling Jaya          | 16       | 11.35%  |
| George Town            | 8        | 5.67%   |
| Shah Alam              | 5        | 3.55%   |
| Subang Jaya            | 4        | 2.84%   |
| Sungai Buloh           | 3        | 2.13%   |
| Seremban               | 3        | 2.13%   |
| Puchong Batu Dua Belas | 3        | 2.13%   |
| Malacca                | 3        | 2.13%   |
| Kulim                  | 3        | 2.13%   |
| Kota Bharu             | 3        | 2.13%   |
| Kajang                 | 3        | 2.13%   |
| Butterworth            | 3        | 2.13%   |
| Tawau                  | 2        | 1.42%   |
| Kuching                | 2        | 1.42%   |
| Kota Kinabalu          | 2        | 1.42%   |
| Bukit Mertajam         | 2        | 1.42%   |
| Bayan Lepas            | 2        | 1.42%   |
| Ampang                 | 2        | 1.42%   |
| Alor Star              | 2        | 1.42%   |
| Taiping                | 1        | 0.71%   |
| Sungai Petani          | 1        | 0.71%   |
| Semenyih               | 1        | 0.71%   |
| Rawang                 | 1        | 0.71%   |
| Putrajaya              | 1        | 0.71%   |
| Penampang              | 1        | 0.71%   |
| Padang Serai           | 1        | 0.71%   |
| Muar town              | 1        | 0.71%   |
| Marabu                 | 1        | 0.71%   |
| Long Seridan           | 1        | 0.71%   |
| Labuan                 | 1        | 0.71%   |
| Kulai                  | 1        | 0.71%   |
| Kuantan                | 1        | 0.71%   |
| Klang                  | 1        | 0.71%   |
| Johor Bahru            | 1        | 0.71%   |
| Ipoh                   | 1        | 0.71%   |
| Cukai                  | 1        | 0.71%   |
| Cheras                 | 1        | 0.71%   |
| Bukit Asahan           | 1        | 0.71%   |
| Batu Caves             | 1        | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 55       | 105    | 22.09%  |
| Seagate                   | 51       | 75     | 20.48%  |
| Kingston                  | 27       | 40     | 10.84%  |
| Samsung Electronics       | 22       | 34     | 8.84%   |
| Toshiba                   | 12       | 14     | 4.82%   |
| Crucial                   | 7        | 13     | 2.81%   |
| Intel                     | 6        | 10     | 2.41%   |
| Apacer                    | 5        | 9      | 2.01%   |
| A-DATA Technology         | 5        | 8      | 2.01%   |
| Unknown                   | 4        | 5      | 1.61%   |
| SanDisk                   | 4        | 7      | 1.61%   |
| PNY                       | 4        | 4      | 1.61%   |
| Phison                    | 3        | 4      | 1.2%    |
| China                     | 3        | 3      | 1.2%    |
| XPG                       | 2        | 3      | 0.8%    |
| TO Exter                  | 2        | 4      | 0.8%    |
| Silicon Motion            | 2        | 3      | 0.8%    |
| Plextor                   | 2        | 2      | 0.8%    |
| Micron Technology         | 2        | 6      | 0.8%    |
| Hitachi                   | 2        | 2      | 0.8%    |
| HGST                      | 2        | 2      | 0.8%    |
| Hewlett-Packard           | 2        | 2      | 0.8%    |
| Gigabyte Technology       | 2        | 2      | 0.8%    |
| External                  | 2        | 2      | 0.8%    |
| Verbatim                  | 1        | 1      | 0.4%    |
| Transcend                 | 1        | 1      | 0.4%    |
| SK hynix                  | 1        | 1      | 0.4%    |
| SATAFIRM                  | 1        | 1      | 0.4%    |
| Phison Electronics        | 1        | 1      | 0.4%    |
| OCZ                       | 1        | 1      | 0.4%    |
| Micron/Crucial Technology | 1        | 1      | 0.4%    |
| Maxtor                    | 1        | 2      | 0.4%    |
| MAX                       | 1        | 2      | 0.4%    |
| LITEON                    | 1        | 1      | 0.4%    |
| KIOXIA-EXCERIA            | 1        | 3      | 0.4%    |
| Kingchuxing               | 1        | 1      | 0.4%    |
| JMicron Technology        | 1        | 1      | 0.4%    |
| Hikvision                 | 1        | 2      | 0.4%    |
| GAMER                     | 1        | 1      | 0.4%    |
| FORESEE                   | 1        | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD    | 10       | 3.38%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 5        | 1.69%   |
| Seagate ST380815AS 80GB            | 5        | 1.69%   |
| Seagate ST1000DM010-2EP102 1TB     | 5        | 1.69%   |
| WDC WD20EZRX-00D8PB0 2TB           | 4        | 1.35%   |
| Seagate ST500DM002-1BC142 500GB    | 4        | 1.35%   |
| Seagate ST3160815AS 160GB          | 4        | 1.35%   |
| Samsung HD103SJ 1TB                | 4        | 1.35%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 3        | 1.01%   |
| Seagate ST2000DM006-2DM164 2TB     | 3        | 1.01%   |
| Seagate ST1000DM003-1ER162 1TB     | 3        | 1.01%   |
| Seagate ST1000DM003-1CH162 1TB     | 3        | 1.01%   |
| Kingston SA400S37480G 480GB SSD    | 3        | 1.01%   |
| Kingston NVMe SSD Drive 500GB      | 3        | 1.01%   |
| Crucial CT500MX500SSD1 500GB       | 3        | 1.01%   |
| XPG NVMe SSD Drive 512GB           | 2        | 0.68%   |
| WDC WD800JD-22MSA1 80GB            | 2        | 0.68%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 2        | 0.68%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 2        | 0.68%   |
| WDC WD5000AAKX-001CA0 500GB        | 2        | 0.68%   |
| WDC WD40EZRZ-00WN9B0 4TB           | 2        | 0.68%   |
| WDC WD360ADFD-00NLR1 37GB          | 2        | 0.68%   |
| WDC WD3200AAKS-00SBA0 320GB        | 2        | 0.68%   |
| WDC WD3200AAKS-00L9A0 320GB        | 2        | 0.68%   |
| WDC WD2500AAKX-753CA1 250GB        | 2        | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 0.68%   |
| WDC WD10EZEX-00MFCA0 1TB           | 2        | 0.68%   |
| WDC WD10EZEX-00BN5A0 1TB           | 2        | 0.68%   |
| Toshiba DT01ACA050 500GB           | 2        | 0.68%   |
| TO Exter nal USB 3.0 512GB         | 2        | 0.68%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 0.68%   |
| Seagate ST3500414CS 500GB          | 2        | 0.68%   |
| Seagate ST3408111AS 40GB           | 2        | 0.68%   |
| Seagate ST3320620A 320GB           | 2        | 0.68%   |
| Seagate ST3250318AS 250GB          | 2        | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 0.68%   |
| Seagate ST2000DM001-1ER164 2TB     | 2        | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.68%   |
| SanDisk SDSSDH3 250G               | 2        | 0.68%   |
| Samsung SSD 960 EVO 250GB          | 2        | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 53       | 103    | 40.46%  |
| Seagate             | 50       | 74     | 38.17%  |
| Toshiba             | 12       | 14     | 9.16%   |
| Samsung Electronics | 8        | 12     | 6.11%   |
| Hitachi             | 2        | 2      | 1.53%   |
| HGST                | 2        | 2      | 1.53%   |
| Maxtor              | 1        | 2      | 0.76%   |
| JMicron Technology  | 1        | 1      | 0.76%   |
| Hewlett-Packard     | 1        | 1      | 0.76%   |
| ASMT                | 1        | 2      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 23       | 32     | 29.87%  |
| Samsung Electronics | 8        | 10     | 10.39%  |
| Crucial             | 7        | 13     | 9.09%   |
| Apacer              | 5        | 9      | 6.49%   |
| Intel               | 4        | 7      | 5.19%   |
| SanDisk             | 3        | 6      | 3.9%    |
| PNY                 | 3        | 3      | 3.9%    |
| China               | 3        | 3      | 3.9%    |
| A-DATA Technology   | 3        | 3      | 3.9%    |
| TO Exter            | 2        | 4      | 2.6%    |
| Plextor             | 2        | 2      | 2.6%    |
| WDC                 | 1        | 1      | 1.3%    |
| Verbatim            | 1        | 1      | 1.3%    |
| Transcend           | 1        | 1      | 1.3%    |
| SK hynix            | 1        | 1      | 1.3%    |
| Seagate             | 1        | 1      | 1.3%    |
| SATAFIRM            | 1        | 1      | 1.3%    |
| OCZ                 | 1        | 1      | 1.3%    |
| Micron Technology   | 1        | 5      | 1.3%    |
| LITEON              | 1        | 1      | 1.3%    |
| KIOXIA-EXCERIA      | 1        | 3      | 1.3%    |
| Hikvision           | 1        | 2      | 1.3%    |
| Hewlett-Packard     | 1        | 1      | 1.3%    |
| FORESEE             | 1        | 1      | 1.3%    |
| Colorful            | 1        | 1      | 1.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 103      | 213    | 50.99%  |
| SSD     | 64       | 113    | 31.68%  |
| NVMe    | 26       | 50     | 12.87%  |
| Unknown | 7        | 9      | 3.47%   |
| MMC     | 2        | 2      | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 121      | 320    | 76.1%   |
| NVMe | 25       | 48     | 15.72%  |
| SAS  | 11       | 17     | 6.92%   |
| MMC  | 2        | 2      | 1.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 101      | 188    | 57.71%  |
| 0.51-1.0   | 47       | 84     | 26.86%  |
| 1.01-2.0   | 21       | 39     | 12%     |
| 3.01-4.0   | 3        | 11     | 1.71%   |
| 4.01-10.0  | 2        | 3      | 1.14%   |
| 2.01-3.0   | 1        | 1      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 41       | 29.71%  |
| 501-1000       | 19       | 13.77%  |
| 251-500        | 18       | 13.04%  |
| 1001-2000      | 15       | 10.87%  |
| 51-100         | 11       | 7.97%   |
| More than 3000 | 9        | 6.52%   |
| 21-50          | 8        | 5.8%    |
| 1-20           | 8        | 5.8%    |
| 2001-3000      | 5        | 3.62%   |
| Unknown        | 4        | 2.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 61       | 42.66%  |
| 21-50          | 17       | 11.89%  |
| 101-250        | 16       | 11.19%  |
| 51-100         | 16       | 11.19%  |
| 251-500        | 10       | 6.99%   |
| More than 3000 | 6        | 4.2%    |
| 1001-2000      | 6        | 4.2%    |
| 501-1000       | 5        | 3.5%    |
| Unknown        | 4        | 2.8%    |
| 2001-3000      | 2        | 1.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST3500414CS 500GB          | 2        | 3      | 15.38%  |
| WDC WD800AAJS-00PSA0 80GB          | 1        | 1      | 7.69%   |
| WDC WD5000AAKX-753CA1 500GB        | 1        | 1      | 7.69%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 1      | 7.69%   |
| WDC WD10EZEX-60WN4A0 1TB           | 1        | 1      | 7.69%   |
| Seagate ST380211AS 80GB            | 1        | 1      | 7.69%   |
| Seagate ST3320620A 320GB           | 1        | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 7.69%   |
| Samsung Electronics HM160HI 160GB  | 1        | 1      | 7.69%   |
| Kingston SV300S37A120G 120GB SSD   | 1        | 1      | 7.69%   |
| Hitachi HDS721050CLA362 500GB      | 1        | 1      | 7.69%   |
| Hewlett-Packard SSD S700 120GB     | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 33.33%  |
| Seagate             | 4        | 6      | 33.33%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |
| Hewlett-Packard     | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 40%     |
| Seagate             | 4        | 6      | 40%     |
| Samsung Electronics | 1        | 1      | 10%     |
| Hitachi             | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 12     | 83.33%  |
| SSD  | 2        | 2      | 16.67%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 88       | 284    | 61.11%  |
| Works    | 44       | 89     | 30.56%  |
| Malfunc  | 12       | 14     | 8.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 99       | 57.89%  |
| AMD                         | 26       | 15.2%   |
| Samsung Electronics         | 8        | 4.68%   |
| Phison Electronics          | 8        | 4.68%   |
| Nvidia                      | 4        | 2.34%   |
| Marvell Technology Group    | 4        | 2.34%   |
| Kingston Technology Company | 4        | 2.34%   |
| JMicron Technology          | 4        | 2.34%   |
| ASMedia Technology          | 4        | 2.34%   |
| Silicon Motion              | 2        | 1.17%   |
| SanDisk                     | 2        | 1.17%   |
| ADATA Technology            | 2        | 1.17%   |
| Silicon Image               | 1        | 0.58%   |
| Micron/Crucial Technology   | 1        | 0.58%   |
| Micron Technology           | 1        | 0.58%   |
| Lite-On IT Corp. / Plextor  | 1        | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 21       | 9.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14       | 6.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 14       | 6.09%   |
| Intel SATA Controller [RAID mode]                                              | 9        | 3.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9        | 3.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 3.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7        | 3.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7        | 3.04%   |
| AMD 400 Series Chipset SATA Controller                                         | 7        | 3.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 2.17%   |
| Intel 82Q35 Express PT IDER Controller                                         | 5        | 2.17%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 5        | 2.17%   |
| Phison PS5013 E13 NVMe Controller                                              | 4        | 1.74%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4        | 1.74%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 4        | 1.74%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 4        | 1.74%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 4        | 1.74%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4        | 1.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 1.3%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 1.3%    |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 3        | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 1.3%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3        | 1.3%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 3        | 1.3%    |
| AMD FCH SATA Controller D                                                      | 3        | 1.3%    |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 0.87%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.87%   |
| Phison E12 NVMe Controller                                                     | 2        | 0.87%   |
| Nvidia MCP61 SATA Controller                                                   | 2        | 0.87%   |
| Nvidia MCP61 IDE                                                               | 2        | 0.87%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 0.87%   |
| Intel Comet Lake PCH-H RAID                                                    | 2        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2        | 0.87%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 0.87%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 94       | 55.29%  |
| IDE  | 35       | 20.59%  |
| NVMe | 25       | 14.71%  |
| RAID | 16       | 9.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 101      | 77.69%  |
| AMD    | 29       | 22.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium CPU G620 @ 2.60GHz            | 8        | 6.15%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 4        | 3.08%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 3.08%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 3        | 2.31%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.31%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 2.31%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 2.31%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 2.31%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.31%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 2.31%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 2        | 1.54%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 1.54%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.54%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 1.54%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.54%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 1.54%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.54%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.54%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.54%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.54%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 2        | 1.54%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.54%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.54%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 2        | 1.54%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.54%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 2        | 1.54%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz          | 1        | 0.77%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.77%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 0.77%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 0.77%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1        | 0.77%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.77%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.77%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.77%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.77%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 0.77%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.77%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 27       | 20.77%  |
| Intel Pentium           | 14       | 10.77%  |
| Intel Core i3           | 14       | 10.77%  |
| AMD Ryzen 5             | 12       | 9.23%   |
| Intel Core i7           | 11       | 8.46%   |
| Intel Core 2 Duo        | 11       | 8.46%   |
| Intel Xeon              | 7        | 5.38%   |
| Other                   | 6        | 4.62%   |
| Intel Core 2 Quad       | 5        | 3.85%   |
| AMD Ryzen 7             | 4        | 3.08%   |
| AMD Ryzen 3             | 3        | 2.31%   |
| Intel Pentium Dual-Core | 2        | 1.54%   |
| AMD Athlon 64 X2        | 2        | 1.54%   |
| AMD A10                 | 2        | 1.54%   |
| Intel Pentium Dual      | 1        | 0.77%   |
| Intel Core i9           | 1        | 0.77%   |
| Intel Celeron           | 1        | 0.77%   |
| Intel Atom              | 1        | 0.77%   |
| AMD Ryzen Threadripper  | 1        | 0.77%   |
| AMD Ryzen Embedded      | 1        | 0.77%   |
| AMD Ryzen 9             | 1        | 0.77%   |
| AMD Phenom II X6        | 1        | 0.77%   |
| AMD Athlon X2           | 1        | 0.77%   |
| AMD A6                  | 1        | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 54       | 41.54%  |
| 2      | 45       | 34.62%  |
| 6      | 18       | 13.85%  |
| 8      | 6        | 4.62%   |
| 12     | 3        | 2.31%   |
| 16     | 2        | 1.54%   |
| 10     | 1        | 0.77%   |
| 3      | 1        | 0.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 130      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 75       | 57.69%  |
| 2      | 55       | 42.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 130      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 20       | 15.04%  |
| Unknown    | 20       | 15.04%  |
| 0x206a7    | 14       | 10.53%  |
| 0x306a9    | 12       | 9.02%   |
| 0x1067a    | 12       | 9.02%   |
| 0x506e3    | 5        | 3.76%   |
| 0x08701021 | 5        | 3.76%   |
| 0x08108109 | 5        | 3.76%   |
| 0x6fb      | 4        | 3.01%   |
| 0x90672    | 3        | 2.26%   |
| 0x6fd      | 3        | 2.26%   |
| 0xa0671    | 2        | 1.5%    |
| 0xa0655    | 2        | 1.5%    |
| 0x906ea    | 2        | 1.5%    |
| 0x906e9    | 2        | 1.5%    |
| 0x10676    | 2        | 1.5%    |
| 0x0a20120a | 2        | 1.5%    |
| 0xa0653    | 1        | 0.75%   |
| 0x906eb    | 1        | 0.75%   |
| 0x506c9    | 1        | 0.75%   |
| 0x406c3    | 1        | 0.75%   |
| 0x306f2    | 1        | 0.75%   |
| 0x206d7    | 1        | 0.75%   |
| 0x20652    | 1        | 0.75%   |
| 0x106a5    | 1        | 0.75%   |
| 0x0a201009 | 1        | 0.75%   |
| 0x08701013 | 1        | 0.75%   |
| 0x08301039 | 1        | 0.75%   |
| 0x0810100b | 1        | 0.75%   |
| 0x08001136 | 1        | 0.75%   |
| 0x08001126 | 1        | 0.75%   |
| 0x06003106 | 1        | 0.75%   |
| 0x03000027 | 1        | 0.75%   |
| 0x010000dc | 1        | 0.75%   |
| 0x00000000 | 1        | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 21       | 16.15%  |
| SandyBridge      | 17       | 13.08%  |
| IvyBridge        | 15       | 11.54%  |
| Penryn           | 14       | 10.77%  |
| Zen 2            | 7        | 5.38%   |
| KabyLake         | 7        | 5.38%   |
| Core             | 7        | 5.38%   |
| Zen+             | 6        | 4.62%   |
| Zen              | 5        | 3.85%   |
| Skylake          | 5        | 3.85%   |
| Zen 3            | 4        | 3.08%   |
| CometLake        | 4        | 3.08%   |
| Alderlake Hybrid | 3        | 2.31%   |
| Unknown          | 3        | 2.31%   |
| Westmere         | 2        | 1.54%   |
| K8 Hammer        | 2        | 1.54%   |
| K10              | 2        | 1.54%   |
| Steamroller      | 1        | 0.77%   |
| Silvermont       | 1        | 0.77%   |
| Nehalem          | 1        | 0.77%   |
| K10 Llano        | 1        | 0.77%   |
| Goldmont         | 1        | 0.77%   |
| Excavator        | 1        | 0.77%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 56       | 40%     |
| Intel  | 46       | 32.86%  |
| AMD    | 38       | 27.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 6.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 4.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 4.9%    |
| Nvidia GF108 [GeForce GT 630]                                               | 6        | 4.2%    |
| Nvidia GF108 [GeForce GT 430]                                               | 5        | 3.5%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 3.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 3.5%    |
| Intel HD Graphics 530                                                       | 4        | 2.8%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 2.8%    |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 2.1%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 3        | 2.1%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 2.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.4%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.4%    |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.4%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.4%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.4%    |
| Nvidia GK107 [GeForce GT 640]                                               | 2        | 1.4%    |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.4%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.4%    |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 1.4%    |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1.4%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.4%    |
| AMD Bonaire XT [Radeon HD 7790/8770 / R7 360 / R9 260/360 OEM]              | 2        | 1.4%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.7%    |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.7%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.7%    |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.7%    |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.7%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.7%    |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 0.7%    |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.7%    |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 0.7%    |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.7%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.7%    |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                         | 1        | 0.7%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.7%    |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 54       | 41.54%  |
| 1 x Intel            | 37       | 28.46%  |
| 1 x AMD              | 35       | 26.92%  |
| 2 x AMD + 3 x Nvidia | 1        | 0.77%   |
| 2 x AMD              | 1        | 0.77%   |
| Intel + Nvidia       | 1        | 0.77%   |
| Intel + AMD          | 1        | 0.77%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 99       | 75.57%  |
| Proprietary | 28       | 21.37%  |
| Unknown     | 4        | 3.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 36.92%  |
| 1.01-2.0   | 29       | 22.31%  |
| 0.51-1.0   | 20       | 15.38%  |
| 7.01-8.0   | 12       | 9.23%   |
| 3.01-4.0   | 8        | 6.15%   |
| 0.01-0.5   | 7        | 5.38%   |
| 5.01-6.0   | 3        | 2.31%   |
| 8.01-16.0  | 2        | 1.54%   |
| 2.01-3.0   | 1        | 0.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 27       | 20.15%  |
| Samsung Electronics  | 15       | 11.19%  |
| Hewlett-Packard      | 15       | 11.19%  |
| Acer                 | 14       | 10.45%  |
| Goldstar             | 12       | 8.96%   |
| AOC                  | 11       | 8.21%   |
| BenQ                 | 9        | 6.72%   |
| ViewSonic            | 6        | 4.48%   |
| Philips              | 6        | 4.48%   |
| ASUSTek Computer     | 3        | 2.24%   |
| Toshiba              | 2        | 1.49%   |
| Sharp                | 2        | 1.49%   |
| LG Electronics       | 2        | 1.49%   |
| Lenovo               | 2        | 1.49%   |
| Unknown              | 1        | 0.75%   |
| Panasonic            | 1        | 0.75%   |
| HUYINIUDA            | 1        | 0.75%   |
| Envision Peripherals | 1        | 0.75%   |
| Dinner               | 1        | 0.75%   |
| Denver               | 1        | 0.75%   |
| CVT                  | 1        | 0.75%   |
| Unknown              | 1        | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 5        | 3.47%   |
| Dell E2720HS DELA15E 1920x1080 598x336mm 27.0-inch                   | 4        | 2.78%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                    | 3        | 2.08%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                    | 3        | 2.08%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 2        | 1.39%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 2        | 1.39%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                   | 2        | 1.39%   |
| Hewlett-Packard LCD Monitor P221                                     | 2        | 1.39%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2        | 1.39%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 2        | 1.39%   |
| Dell LCD Monitor E2720HS 1920x1080                                   | 2        | 1.39%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                    | 2        | 1.39%   |
| ASUSTek Computer XG32VQR AUS32B2 2560x1440 697x393mm 31.5-inch       | 2        | 1.39%   |
| AOC LCD Monitor 936W 1366x768                                        | 2        | 1.39%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                        | 2        | 1.39%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                       | 2        | 1.39%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch            | 1        | 0.69%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch            | 1        | 0.69%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch        | 1        | 0.69%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch           | 1        | 0.69%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch         | 1        | 0.69%   |
| ViewSonic LCD Monitor VSCBB31 1920x1080 530x300mm 24.0-inch          | 1        | 0.69%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                | 1        | 0.69%   |
| Toshiba TV TSB0113 1920x1080 1220x680mm 55.0-inch                    | 1        | 0.69%   |
| Toshiba Crystal View LCD0001 1920x1080 408x255mm 18.9-inch           | 1        | 0.69%   |
| Sharp LCD SHP10C9 1920x540                                           | 1        | 0.69%   |
| Sharp LC-22LE420M SHP2242 1920x1080 477x268mm 21.5-inch              | 1        | 0.69%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1        | 0.69%   |
| Samsung Electronics SME1920 SAM06B7 1360x768 410x230mm 18.5-inch     | 1        | 0.69%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch    | 1        | 0.69%   |
| Samsung Electronics S24C350 SAM0A3C 1920x1080 521x293mm 23.5-inch    | 1        | 0.69%   |
| Samsung Electronics S23C350 SAM0A35 1920x1080 510x287mm 23.0-inch    | 1        | 0.69%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1        | 0.69%   |
| Samsung Electronics S22A33x SAM7122 1920x1080 479x260mm 21.5-inch    | 1        | 0.69%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch     | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0E9B 1366x768 609x347mm 27.6-inch | 1        | 0.69%   |
| Samsung Electronics LCD Monitor S24B350 1920x1080                    | 1        | 0.69%   |
| Samsung Electronics C27FG70 SAM0DC9 1920x1080 598x337mm 27.0-inch    | 1        | 0.69%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 598x336mm 27.0-inch              | 1        | 0.69%   |
| Philips LCD Monitor 40PFA4509 1920x1080                              | 1        | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 58       | 43.28%  |
| 1366x768 (WXGA)    | 16       | 11.94%  |
| 3840x2160 (4K)     | 12       | 8.96%   |
| 2560x1440 (QHD)    | 7        | 5.22%   |
| 1600x900 (HD+)     | 7        | 5.22%   |
| 1440x900 (WXGA+)   | 5        | 3.73%   |
| 2560x1080          | 4        | 2.99%   |
| Unknown            | 4        | 2.99%   |
| 1360x768           | 3        | 2.24%   |
| 1280x1024 (SXGA)   | 3        | 2.24%   |
| 5760x1080          | 2        | 1.49%   |
| 1680x1050 (WSXGA+) | 2        | 1.49%   |
| 1600x1200          | 2        | 1.49%   |
| 5440x1080          | 1        | 0.75%   |
| 5120x1440          | 1        | 0.75%   |
| 3840x1080          | 1        | 0.75%   |
| 3440x1440          | 1        | 0.75%   |
| 1920x540           | 1        | 0.75%   |
| 1920x1200 (WUXGA)  | 1        | 0.75%   |
| 1280x960           | 1        | 0.75%   |
| 1280x720 (HD)      | 1        | 0.75%   |
| 1024x768 (XGA)     | 1        | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 17       | 12.69%  |
| 21      | 16       | 11.94%  |
| 18      | 16       | 11.94%  |
| 23      | 15       | 11.19%  |
| Unknown | 15       | 11.19%  |
| 27      | 14       | 10.45%  |
| 19      | 11       | 8.21%   |
| 31      | 8        | 5.97%   |
| 20      | 6        | 4.48%   |
| 34      | 3        | 2.24%   |
| 32      | 3        | 2.24%   |
| 17      | 3        | 2.24%   |
| 22      | 2        | 1.49%   |
| 55      | 1        | 0.75%   |
| 39      | 1        | 0.75%   |
| 28      | 1        | 0.75%   |
| 25      | 1        | 0.75%   |
| 15      | 1        | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 49       | 37.12%  |
| 501-600     | 43       | 32.58%  |
| Unknown     | 15       | 11.36%  |
| 601-700     | 11       | 8.33%   |
| 701-800     | 6        | 4.55%   |
| 301-350     | 4        | 3.03%   |
| 351-400     | 2        | 1.52%   |
| 801-900     | 1        | 0.76%   |
| 1001-1500   | 1        | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 92       | 71.88%  |
| Unknown | 14       | 10.94%  |
| 16/10   | 9        | 7.03%   |
| 5/4     | 5        | 3.91%   |
| 21/9    | 4        | 3.13%   |
| 4/3     | 3        | 2.34%   |
| 32/9    | 1        | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 43       | 32.82%  |
| 151-200        | 22       | 16.79%  |
| 141-150        | 17       | 12.98%  |
| Unknown        | 15       | 11.45%  |
| 351-500        | 14       | 10.69%  |
| 301-350        | 14       | 10.69%  |
| 251-300        | 3        | 2.29%   |
| More than 1000 | 1        | 0.76%   |
| 101-110        | 1        | 0.76%   |
| 501-1000       | 1        | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 85       | 65.89%  |
| 101-120 | 20       | 15.5%   |
| Unknown | 15       | 11.63%  |
| 121-160 | 5        | 3.88%   |
| 1-50    | 3        | 2.33%   |
| 161-240 | 1        | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 112      | 86.15%  |
| 2     | 11       | 8.46%   |
| 0     | 5        | 3.85%   |
| 3     | 2        | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 68       | 31.63%  |
| Intel                             | 57       | 26.51%  |
| Qualcomm Atheros                  | 16       | 7.44%   |
| TP-Link                           | 14       | 6.51%   |
| Ralink Technology                 | 14       | 6.51%   |
| D-Link                            | 10       | 4.65%   |
| Broadcom                          | 9        | 4.19%   |
| Qualcomm Atheros Communications   | 6        | 2.79%   |
| Xiaomi                            | 5        | 2.33%   |
| Nvidia                            | 3        | 1.4%    |
| Samsung Electronics               | 2        | 0.93%   |
| Aquantia                          | 2        | 0.93%   |
| Tehuti Networks                   | 1        | 0.47%   |
| Sundance Technology Inc / IC Plus | 1        | 0.47%   |
| Ralink                            | 1        | 0.47%   |
| OPPO Electronics                  | 1        | 0.47%   |
| InterBiometrics                   | 1        | 0.47%   |
| D-Link System                     | 1        | 0.47%   |
| Broadcom Limited                  | 1        | 0.47%   |
| Apple                             | 1        | 0.47%   |
| AboCom Systems                    | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 51       | 21.07%  |
| TP-Link Archer T4U ver.3                                                             | 8        | 3.31%   |
| Intel 82579V Gigabit Network Connection                                              | 8        | 3.31%   |
| Ralink MT7601U Wireless Adapter                                                      | 7        | 2.89%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 6        | 2.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 6        | 2.48%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6        | 2.48%   |
| Realtek 802.11ac NIC                                                                 | 5        | 2.07%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 4        | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 4        | 1.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 4        | 1.65%   |
| Intel I211 Gigabit Network Connection                                                | 4        | 1.65%   |
| Intel Ethernet Connection (11) I219-V                                                | 4        | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 4        | 1.65%   |
| Intel 82566DM-2 Gigabit Network Connection                                           | 4        | 1.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                       | 3        | 1.24%   |
| TP-Link 802.11n NIC                                                                  | 3        | 1.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 1.24%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 1.24%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 3        | 1.24%   |
| Intel Ethernet Controller I225-V                                                     | 3        | 1.24%   |
| Intel Ethernet Connection I217-LM                                                    | 3        | 1.24%   |
| Intel Ethernet Connection (7) I219-V                                                 | 3        | 1.24%   |
| Intel Ethernet Connection (2) I219-V                                                 | 3        | 1.24%   |
| Intel 82567LM-3 Gigabit Network Connection                                           | 3        | 1.24%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 3        | 1.24%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                 | 2        | 0.83%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2        | 0.83%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 0.83%   |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2        | 0.83%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 2        | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                           | 2        | 0.83%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                       | 2        | 0.83%   |
| Intel Wireless 3165                                                                  | 2        | 0.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 2        | 0.83%   |
| Intel I350 Gigabit Fiber Network Connection                                          | 2        | 0.83%   |
| Intel Ethernet Connection I217-V                                                     | 2        | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                                | 2        | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 19       | 20.21%  |
| TP-Link                         | 14       | 14.89%  |
| Ralink Technology               | 14       | 14.89%  |
| Intel                           | 14       | 14.89%  |
| Qualcomm Atheros                | 9        | 9.57%   |
| D-Link                          | 9        | 9.57%   |
| Qualcomm Atheros Communications | 6        | 6.38%   |
| Broadcom                        | 5        | 5.32%   |
| Ralink                          | 1        | 1.06%   |
| D-Link System                   | 1        | 1.06%   |
| Broadcom Limited                | 1        | 1.06%   |
| AboCom Systems                  | 1        | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| TP-Link Archer T4U ver.3                                                             | 8        | 8.33%   |
| Ralink MT7601U Wireless Adapter                                                      | 7        | 7.29%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 6        | 6.25%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6        | 6.25%   |
| Realtek 802.11ac NIC                                                                 | 5        | 5.21%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 4        | 4.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 4        | 4.17%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 4.17%   |
| TP-Link 802.11n NIC                                                                  | 3        | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 3.13%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 3.13%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 3        | 3.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 3        | 3.13%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2        | 2.08%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 2.08%   |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2        | 2.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 2        | 2.08%   |
| Intel Wireless 3165                                                                  | 2        | 2.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 2        | 2.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 2        | 2.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 1        | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 1        | 1.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.04%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.04%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 1.04%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                            | 1        | 1.04%   |
| Ralink RT5572 Wireless Adapter                                                       | 1        | 1.04%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                          | 1        | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 1        | 1.04%   |
| Intel Wireless-AC 9260                                                               | 1        | 1.04%   |
| Intel Wi-Fi 6 AX200                                                                  | 1        | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1        | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 1        | 1.04%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]                    | 1        | 1.04%   |
| D-Link DWA-182 Wireless AC Dualband Adapter(rev.C) [Realtek RTL8812AU]               | 1        | 1.04%   |
| D-Link 802.11n WLAN Adapter                                                          | 1        | 1.04%   |
| D-Link 802.11ac NIC                                                                  | 1        | 1.04%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                           | 1        | 1.04%   |
| Broadcom BCM43228 802.11a/b/g/n                                                      | 1        | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 61       | 44.2%   |
| Intel                             | 49       | 35.51%  |
| Qualcomm Atheros                  | 7        | 5.07%   |
| Xiaomi                            | 5        | 3.62%   |
| Broadcom                          | 4        | 2.9%    |
| Nvidia                            | 3        | 2.17%   |
| Samsung Electronics               | 2        | 1.45%   |
| Aquantia                          | 2        | 1.45%   |
| Tehuti Networks                   | 1        | 0.72%   |
| Sundance Technology Inc / IC Plus | 1        | 0.72%   |
| OPPO Electronics                  | 1        | 0.72%   |
| D-Link                            | 1        | 0.72%   |
| Apple                             | 1        | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 51       | 35.17%  |
| Intel 82579V Gigabit Network Connection                                    | 8        | 5.52%   |
| Realtek RTL8125 2.5GbE Controller                                          | 6        | 4.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 4        | 2.76%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 2.76%   |
| Intel Ethernet Connection (11) I219-V                                      | 4        | 2.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 4        | 2.76%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 2.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 2.07%   |
| Intel Ethernet Controller I225-V                                           | 3        | 2.07%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 2.07%   |
| Intel Ethernet Connection (7) I219-V                                       | 3        | 2.07%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 2.07%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 3        | 2.07%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2        | 1.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 2        | 1.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2        | 1.38%   |
| Intel I350 Gigabit Fiber Network Connection                                | 2        | 1.38%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.38%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 1.38%   |
| Intel 82583V Gigabit Network Connection                                    | 2        | 1.38%   |
| Intel 82562V-2 10/100 Network Connection                                   | 2        | 1.38%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 1.38%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 1.38%   |
| Tehuti Networks TN9310 10GbE SFP+ Ethernet Adapter                         | 1        | 0.69%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.69%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1        | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 1        | 0.69%   |
| OPPO SDM665-IDP _SN:18689828                                               | 1        | 0.69%   |
| Nvidia MCP73 Ethernet                                                      | 1        | 0.69%   |
| Nvidia MCP61 Ethernet                                                      | 1        | 0.69%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.69%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.69%   |
| Intel Ethernet Connection (2) I218-LM                                      | 1        | 0.69%   |
| Intel 82578DM Gigabit Network Connection                                   | 1        | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 118      | 58.42%  |
| WiFi     | 83       | 41.09%  |
| Modem    | 1        | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 68       | 51.91%  |
| WiFi     | 63       | 48.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 76       | 58.02%  |
| 2     | 36       | 27.48%  |
| 0     | 11       | 8.4%    |
| 3     | 6        | 4.58%   |
| 9     | 1        | 0.76%   |
| 8     | 1        | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 105      | 78.95%  |
| Yes  | 28       | 21.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 20       | 44.44%  |
| Intel                   | 14       | 31.11%  |
| Realtek Semiconductor   | 3        | 6.67%   |
| Broadcom                | 2        | 4.44%   |
| Apple                   | 2        | 4.44%   |
| TP-Link                 | 1        | 2.22%   |
| IMC Networks            | 1        | 2.22%   |
| Foxconn / Hon Hai       | 1        | 2.22%   |
| D-Link                  | 1        | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20       | 44.44%  |
| Intel AX201 Bluetooth                               | 6        | 13.33%  |
| Realtek Bluetooth Radio                             | 3        | 6.67%   |
| Intel Bluetooth wireless interface                  | 3        | 6.67%   |
| Intel AX210 Bluetooth                               | 2        | 4.44%   |
| Apple Bluetooth USB Host Controller                 | 2        | 4.44%   |
| TP-Link UB500 Adapter                               | 1        | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.22%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 2.22%   |
| Intel AX200 Bluetooth                               | 1        | 2.22%   |
| IMC Networks Bluetooth Radio                        | 1        | 2.22%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1        | 2.22%   |
| D-Link DBT-122 Bluetooth adapter                    | 1        | 2.22%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 2.22%   |
| Broadcom BCM20702A0                                 | 1        | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 94       | 43.12%  |
| Nvidia                      | 56       | 25.69%  |
| AMD                         | 44       | 20.18%  |
| Logitech                    | 6        | 2.75%   |
| C-Media Electronics         | 5        | 2.29%   |
| JMTek                       | 3        | 1.38%   |
| Unknown                     | 1        | 0.46%   |
| Texas Instruments           | 1        | 0.46%   |
| RODE Microphones            | 1        | 0.46%   |
| Razer USA                   | 1        | 0.46%   |
| GN Netcom                   | 1        | 0.46%   |
| Generalplus Technology      | 1        | 0.46%   |
| FiiO Electronics Technology | 1        | 0.46%   |
| Creative Labs               | 1        | 0.46%   |
| Cooler Master               | 1        | 0.46%   |
| ASUSTek Computer            | 1        | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 15       | 6.15%   |
| Nvidia GF108 High Definition Audio Controller                                     | 13       | 5.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 13       | 5.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 12       | 4.92%   |
| AMD Starship/Matisse HD Audio Controller                                          | 10       | 4.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9        | 3.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 9        | 3.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 8        | 3.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7        | 2.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7        | 2.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 2.87%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7        | 2.87%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 1.64%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4        | 1.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4        | 1.64%   |
| Intel Alder Lake-S HD Audio Controller                                            | 4        | 1.64%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 4        | 1.64%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 1.64%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 1.23%   |
| Nvidia High Definition Audio Controller                                           | 3        | 1.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 1.23%   |
| Nvidia GK107 HDMI Audio Controller                                                | 3        | 1.23%   |
| Logitech H600 [Wireless Headset]                                                  | 3        | 1.23%   |
| JMTek USB PnP Audio Device                                                        | 3        | 1.23%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 1.23%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 1.23%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 3        | 1.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 1.23%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 0.82%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 0.82%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.82%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 0.82%   |
| Logitech USB Headset H540                                                         | 2        | 0.82%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 0.82%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 0.82%   |
| Intel Audio device                                                                | 2        | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 0.82%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 0.82%   |
| C-Media Electronics Thronmax MDrill One                                           | 2        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 25       | 39.06%  |
| Corsair             | 8        | 12.5%   |
| Unknown             | 7        | 10.94%  |
| SK hynix            | 6        | 9.38%   |
| Kingmax             | 3        | 4.69%   |
| Team                | 2        | 3.13%   |
| Micron Technology   | 2        | 3.13%   |
| Kimtigo             | 2        | 3.13%   |
| A-DATA Technology   | 2        | 3.13%   |
| Unknown (ABCD)      | 1        | 1.56%   |
| Silicon Power       | 1        | 1.56%   |
| SemsoTai            | 1        | 1.56%   |
| Samsung Electronics | 1        | 1.56%   |
| PNY                 | 1        | 1.56%   |
| Kinlstuo            | 1        | 1.56%   |
| G.Skill             | 1        | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s        | 5        | 6.76%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 3        | 4.05%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 2        | 2.7%    |
| Kingmax RAM FLFE85F-C8KL9 2GB DIMM DDR3 1333MT/s             | 2        | 2.7%    |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s               | 2        | 2.7%    |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                  | 2        | 2.7%    |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                    | 1        | 1.35%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 1.35%   |
| Unknown RAM Module 2GB DIMM 667MT/s                          | 1        | 1.35%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 1.35%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s           | 1        | 1.35%   |
| Team RAM Elite-800 2048MB DIMM SDRAM 2048MT/s                | 1        | 1.35%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                | 1        | 1.35%   |
| SK hynix RAM HYMP112F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s  | 1        | 1.35%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s         | 1        | 1.35%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 1.35%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s      | 1        | 1.35%   |
| SK hynix RAM HMA84GR7CJR4N-XN 32GB DIMM DDR4 3200MT/s        | 1        | 1.35%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s         | 1        | 1.35%   |
| Silicon Power RAM DBLT2GN568S 2048MB DIMM DDR3 1333MT/s      | 1        | 1.35%   |
| SemsoTai RAM Module 8GB DIMM DDR4 2667MT/s                   | 1        | 1.35%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 1.35%   |
| PNY RAM 8GBF1X08LFHH35-12-K 8GB DIMM DDR4 2667MT/s           | 1        | 1.35%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 1        | 1.35%   |
| Micron RAM 18JSF25672AZ 2048MB DIMM DDR3 1066MT/s            | 1        | 1.35%   |
| Kinlstuo RAM Module 8192MB DIMM DDR3 1600MT/s                | 1        | 1.35%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                    | 1        | 1.35%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                 | 1        | 1.35%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s      | 1        | 1.35%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 1        | 1.35%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s          | 1        | 1.35%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s          | 1        | 1.35%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s        | 1        | 1.35%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s        | 1        | 1.35%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s        | 1        | 1.35%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s           | 1        | 1.35%   |
| Kingston RAM 99U5474-041.A00LF 4GB DIMM DDR3 1333MT/s        | 1        | 1.35%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s        | 1        | 1.35%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM 1600MT/s             | 1        | 1.35%   |
| Kingston RAM 99U5471-036.A00LF 8GB DIMM DDR3 1600MT/s        | 1        | 1.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 26       | 42.62%  |
| DDR4    | 22       | 36.07%  |
| SDRAM   | 6        | 9.84%   |
| DDR2    | 4        | 6.56%   |
| Unknown | 2        | 3.28%   |
| LPDDR4  | 1        | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 56       | 93.33%  |
| SODIMM  | 3        | 5%      |
| FB-DIMM | 1        | 1.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 26       | 40.63%  |
| 2048  | 15       | 23.44%  |
| 4096  | 10       | 15.63%  |
| 32768 | 6        | 9.38%   |
| 16384 | 6        | 9.38%   |
| 1024  | 1        | 1.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 24.62%  |
| 3200    | 8        | 12.31%  |
| 1333    | 6        | 9.23%   |
| 2667    | 5        | 7.69%   |
| 3600    | 4        | 6.15%   |
| 2400    | 4        | 6.15%   |
| Unknown | 4        | 6.15%   |
| 800     | 3        | 4.62%   |
| 667     | 3        | 4.62%   |
| 3400    | 2        | 3.08%   |
| 1066    | 2        | 3.08%   |
| 3000    | 1        | 1.54%   |
| 2933    | 1        | 1.54%   |
| 2133    | 1        | 1.54%   |
| 2048    | 1        | 1.54%   |
| 1867    | 1        | 1.54%   |
| 1866    | 1        | 1.54%   |
| 1800    | 1        | 1.54%   |
| 1067    | 1        | 1.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 25%     |
| Brother Industries  | 2        | 25%     |
| Seiko Epson         | 1        | 12.5%   |
| Prolific Technology | 1        | 12.5%   |
| Hewlett-Packard     | 1        | 12.5%   |
| Canon               | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung SCX-3400 Series       | 2        | 25%     |
| Seiko Epson L312 Series       | 1        | 12.5%   |
| Prolific PL2305 Parallel Port | 1        | 12.5%   |
| HP Ink Tank 110 series        | 1        | 12.5%   |
| Canon E410 series             | 1        | 12.5%   |
| Brother DCP-J105              | 1        | 12.5%   |
| Brother DCP-1610W             | 1        | 12.5%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 35.29%  |
| Generalplus Technology        | 3        | 17.65%  |
| Apple                         | 2        | 11.76%  |
| YGTek                         | 1        | 5.88%   |
| WCM_USB                       | 1        | 5.88%   |
| Sunplus Innovation Technology | 1        | 5.88%   |
| Realtek Semiconductor         | 1        | 5.88%   |
| Jieli Technology              | 1        | 5.88%   |
| ARC International             | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 2        | 11.76%  |
| Generalplus 808 Camera                | 2        | 11.76%  |
| Apple iPhone 5/5C/5S/6/SE             | 2        | 11.76%  |
| YGTek Webcam                          | 1        | 5.88%   |
| WCM_USB WEB CAM                       | 1        | 5.88%   |
| Sunplus Full HD webcam                | 1        | 5.88%   |
| Realtek HP High Definition 1MP Webcam | 1        | 5.88%   |
| Logitech Webcam C310                  | 1        | 5.88%   |
| Logitech Webcam C170                  | 1        | 5.88%   |
| Logitech HD Webcam C510               | 1        | 5.88%   |
| Logitech HD Pro Webcam C920           | 1        | 5.88%   |
| Jieli USB PHY 2.0                     | 1        | 5.88%   |
| Generalplus GENERAL WEBCAM            | 1        | 5.88%   |
| ARC International Camera              | 1        | 5.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 110      | 82.71%  |
| 1     | 20       | 15.04%  |
| 6     | 1        | 0.75%   |
| 3     | 1        | 0.75%   |
| 2     | 1        | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 11       | 44%     |
| Graphics card            | 6        | 24%     |
| Communication controller | 3        | 12%     |
| Sound                    | 2        | 8%      |
| Unassigned class         | 1        | 4%      |
| Storage/ide              | 1        | 4%      |
| Network                  | 1        | 4%      |

