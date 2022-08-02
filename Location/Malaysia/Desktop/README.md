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

Total: 176

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 28       | 21.71%  |
| Ubuntu 18.04                 | 8        | 6.2%    |
| OpenMandriva 4.2             | 6        | 4.65%   |
| Pop!_OS 20.04                | 5        | 3.88%   |
| OpenMandriva 4.3             | 5        | 3.88%   |
| Ubuntu 19.04                 | 4        | 3.1%    |
| OpenMandriva 4.50            | 4        | 3.1%    |
| Zorin 16                     | 3        | 2.33%   |
| Xubuntu 18.04                | 3        | 2.33%   |
| Linux Mint 19.3              | 3        | 2.33%   |
| Fedora 33                    | 3        | 2.33%   |
| Debian 11                    | 3        | 2.33%   |
| ArcoLinux Rolling            | 3        | 2.33%   |
| Zorin 15                     | 2        | 1.55%   |
| Ubuntu 22.04                 | 2        | 1.55%   |
| Ubuntu 19.10                 | 2        | 1.55%   |
| Pop!_OS 21.04                | 2        | 1.55%   |
| Pop!_OS 20.10                | 2        | 1.55%   |
| Manjaro 21.2.6               | 2        | 1.55%   |
| Linux Mint 20.3              | 2        | 1.55%   |
| KDE neon 20.04               | 2        | 1.55%   |
| Fedora 34                    | 2        | 1.55%   |
| Arch                         | 2        | 1.55%   |
| Ubuntu MATE 20.04            | 1        | 0.78%   |
| Ubuntu 21.10                 | 1        | 0.78%   |
| Ubuntu 21.04                 | 1        | 0.78%   |
| Ubuntu 20.10                 | 1        | 0.78%   |
| ROSA R10                     | 1        | 0.78%   |
| Pop!_OS 21.10                | 1        | 0.78%   |
| openSUSE Tumbleweed-XXXXXXXX | 1        | 0.78%   |
| Manjaro 21.1.1               | 1        | 0.78%   |
| Manjaro 21.0.5               | 1        | 0.78%   |
| Manjaro                      | 1        | 0.78%   |
| Lubuntu 20.10                | 1        | 0.78%   |
| Lubuntu 20.04                | 1        | 0.78%   |
| Linux Mint 20.2              | 1        | 0.78%   |
| Linux Mint 20.1              | 1        | 0.78%   |
| Linux Mint 20                | 1        | 0.78%   |
| Linux Mint 18.3              | 1        | 0.78%   |
| Linux Lite 5.6               | 1        | 0.78%   |
| Kubuntu 22.04                | 1        | 0.78%   |
| Kali 2022.2                  | 1        | 0.78%   |
| Kali 2021.3                  | 1        | 0.78%   |
| Gentoo 2.8                   | 1        | 0.78%   |
| Endless 4.0.7                | 1        | 0.78%   |
| Endless 4.0.3                | 1        | 0.78%   |
| Endless 3.7.3                | 1        | 0.78%   |
| EndeavourOS                  | 1        | 0.78%   |
| Elementary 6.1               | 1        | 0.78%   |
| Elementary 5.1.7             | 1        | 0.78%   |
| Elementary 5.1.4             | 1        | 0.78%   |
| Elementary 5.1.3             | 1        | 0.78%   |
| Debian Unstable              | 1        | 0.78%   |
| CentOS 8                     | 1        | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 45       | 36.59%  |
| OpenMandriva | 14       | 11.38%  |
| Linux Mint   | 9        | 7.32%   |
| Pop!_OS      | 8        | 6.5%    |
| Zorin        | 5        | 4.07%   |
| Manjaro      | 5        | 4.07%   |
| Fedora       | 5        | 4.07%   |
| Debian       | 4        | 3.25%   |
| Xubuntu      | 3        | 2.44%   |
| Endless      | 3        | 2.44%   |
| Elementary   | 3        | 2.44%   |
| ArcoLinux    | 3        | 2.44%   |
| Lubuntu      | 2        | 1.63%   |
| KDE neon     | 2        | 1.63%   |
| Kali         | 2        | 1.63%   |
| Arch         | 2        | 1.63%   |
| Ubuntu MATE  | 1        | 0.81%   |
| ROSA         | 1        | 0.81%   |
| openSUSE     | 1        | 0.81%   |
| Linux Lite   | 1        | 0.81%   |
| Kubuntu      | 1        | 0.81%   |
| Gentoo       | 1        | 0.81%   |
| EndeavourOS  | 1        | 0.81%   |
| CentOS       | 1        | 0.81%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002      | 6        | 4.32%   |
| 5.4.0-58-generic              | 5        | 3.6%    |
| 5.4.0-42-generic              | 4        | 2.88%   |
| 5.4.0-40-generic              | 3        | 2.16%   |
| 5.3.0-53-generic              | 3        | 2.16%   |
| 5.3.0-46-generic              | 3        | 2.16%   |
| 5.16.7-desktop-1omv4003       | 3        | 2.16%   |
| 5.11.0-27-generic             | 3        | 2.16%   |
| 5.8.0-53-generic              | 2        | 1.44%   |
| 5.8.0-44-generic              | 2        | 1.44%   |
| 5.8.0-41-generic              | 2        | 1.44%   |
| 5.4.0-77-generic              | 2        | 1.44%   |
| 5.4.0-7634-generic            | 2        | 1.44%   |
| 5.4.0-48-generic              | 2        | 1.44%   |
| 5.4.0-37-generic              | 2        | 1.44%   |
| 5.4.0-29-generic              | 2        | 1.44%   |
| 5.16.3-desktop-2omv4050       | 2        | 1.44%   |
| 5.15.35-3-pve                 | 2        | 1.44%   |
| 5.15.0-39-generic             | 2        | 1.44%   |
| 5.12.7-desktop-clang-1omv4003 | 2        | 1.44%   |
| 5.12.4-desktop-1omv4050       | 2        | 1.44%   |
| 5.12.15-300.fc34.x86_64       | 2        | 1.44%   |
| 5.11.0-41-generic             | 2        | 1.44%   |
| 5.11.0-35-generic             | 2        | 1.44%   |
| 5.11.0-34-generic             | 2        | 1.44%   |
| 5.0.0-27-generic              | 2        | 1.44%   |
| 5.9.8-arch1-1                 | 1        | 0.72%   |
| 5.9.14-200.fc33.x86_64        | 1        | 0.72%   |
| 5.9.1-1-MANJARO               | 1        | 0.72%   |
| 5.8.0-7630-generic            | 1        | 0.72%   |
| 5.8.0-59-generic              | 1        | 0.72%   |
| 5.8.0-49-generic              | 1        | 0.72%   |
| 5.8.0-48-generic              | 1        | 0.72%   |
| 5.8.0-40-generic              | 1        | 0.72%   |
| 5.8.0-31-generic              | 1        | 0.72%   |
| 5.4.0-88-generic              | 1        | 0.72%   |
| 5.4.0-84-generic              | 1        | 0.72%   |
| 5.4.0-7625-generic            | 1        | 0.72%   |
| 5.4.0-74-generic              | 1        | 0.72%   |
| 5.4.0-65-generic              | 1        | 0.72%   |
| 5.4.0-63-generic              | 1        | 0.72%   |
| 5.4.0-56-generic              | 1        | 0.72%   |
| 5.4.0-52-generic              | 1        | 0.72%   |
| 5.4.0-47-generic              | 1        | 0.72%   |
| 5.4.0-45-generic              | 1        | 0.72%   |
| 5.4.0-39-generic              | 1        | 0.72%   |
| 5.4.0-31-generic              | 1        | 0.72%   |
| 5.4.0-109-generic             | 1        | 0.72%   |
| 5.4.0-100-generic             | 1        | 0.72%   |
| 5.3.0-40-generic              | 1        | 0.72%   |
| 5.3.0-29-generic              | 1        | 0.72%   |
| 5.3.0-24-generic              | 1        | 0.72%   |
| 5.3.0-23-generic              | 1        | 0.72%   |
| 5.3.0-19-generic              | 1        | 0.72%   |
| 5.3.0-18-generic              | 1        | 0.72%   |
| 5.3.0-12-generic              | 1        | 0.72%   |
| 5.18.7-arch1-1                | 1        | 0.72%   |
| 5.18.0-2-amd64                | 1        | 0.72%   |
| 5.18.0-1-MANJARO              | 1        | 0.72%   |
| 5.17.3-arch1-1                | 1        | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 25.2%   |
| 5.8.0   | 11       | 8.66%   |
| 5.11.0  | 11       | 8.66%   |
| 5.3.0   | 8        | 6.3%    |
| 5.0.0   | 7        | 5.51%   |
| 5.10.14 | 6        | 4.72%   |
| 4.15.0  | 6        | 4.72%   |
| 5.15.0  | 4        | 3.15%   |
| 5.13.0  | 4        | 3.15%   |
| 5.16.7  | 3        | 2.36%   |
| 5.18.0  | 2        | 1.57%   |
| 5.17.1  | 2        | 1.57%   |
| 5.16.3  | 2        | 1.57%   |
| 5.15.35 | 2        | 1.57%   |
| 5.12.7  | 2        | 1.57%   |
| 5.12.4  | 2        | 1.57%   |
| 5.12.15 | 2        | 1.57%   |
| 4.18.0  | 2        | 1.57%   |
| 5.9.8   | 1        | 0.79%   |
| 5.9.14  | 1        | 0.79%   |
| 5.9.1   | 1        | 0.79%   |
| 5.18.7  | 1        | 0.79%   |
| 5.17.3  | 1        | 0.79%   |
| 5.16.19 | 1        | 0.79%   |
| 5.16.0  | 1        | 0.79%   |
| 5.15.8  | 1        | 0.79%   |
| 5.15.15 | 1        | 0.79%   |
| 5.15.13 | 1        | 0.79%   |
| 5.15.12 | 1        | 0.79%   |
| 5.14.18 | 1        | 0.79%   |
| 5.14.11 | 1        | 0.79%   |
| 5.14.0  | 1        | 0.79%   |
| 5.13.12 | 1        | 0.79%   |
| 5.11.15 | 1        | 0.79%   |
| 5.10.61 | 1        | 0.79%   |
| 5.10.0  | 1        | 0.79%   |
| 4.9.60  | 1        | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 25.2%   |
| 5.11    | 12       | 9.45%   |
| 5.8     | 11       | 8.66%   |
| 5.15    | 10       | 7.87%   |
| 5.3     | 8        | 6.3%    |
| 5.10    | 8        | 6.3%    |
| 5.16    | 7        | 5.51%   |
| 5.0     | 7        | 5.51%   |
| 5.12    | 6        | 4.72%   |
| 4.15    | 6        | 4.72%   |
| 5.13    | 5        | 3.94%   |
| 5.9     | 3        | 2.36%   |
| 5.18    | 3        | 2.36%   |
| 5.17    | 3        | 2.36%   |
| 5.14    | 3        | 2.36%   |
| 4.18    | 2        | 1.57%   |
| 4.9     | 1        | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 116      | 98.31%  |
| i686   | 2        | 1.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 55       | 45.45%  |
| KDE5       | 21       | 17.36%  |
| Unknown    | 11       | 9.09%   |
| XFCE       | 10       | 8.26%   |
| X-Cinnamon | 7        | 5.79%   |
| MATE       | 6        | 4.96%   |
| Pantheon   | 3        | 2.48%   |
| KDE        | 3        | 2.48%   |
| Openbox    | 2        | 1.65%   |
| LXQt       | 2        | 1.65%   |
| Cinnamon   | 1        | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 102      | 85.71%  |
| Wayland | 7        | 5.88%   |
| Unknown | 7        | 5.88%   |
| Tty     | 3        | 2.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 72       | 60%     |
| SDDM    | 22       | 18.33%  |
| LightDM | 10       | 8.33%   |
| GDM     | 8        | 6.67%   |
| GDM3    | 5        | 4.17%   |
| TDM     | 3        | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 88       | 73.33%  |
| en_GB   | 10       | 8.33%   |
| Unknown | 10       | 8.33%   |
| en_SG   | 6        | 5%      |
| en_AU   | 3        | 2.5%    |
| zh_CN   | 1        | 0.83%   |
| en_MY   | 1        | 0.83%   |
| en_HK   | 1        | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 79       | 65.83%  |
| EFI  | 41       | 34.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 93       | 76.86%  |
| Overlay | 11       | 9.09%   |
| Btrfs   | 6        | 4.96%   |
| Unknown | 4        | 3.31%   |
| Xfs     | 3        | 2.48%   |
| Zfs     | 2        | 1.65%   |
| Ext3    | 1        | 0.83%   |
| Ext2    | 1        | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 73       | 61.86%  |
| GPT     | 24       | 20.34%  |
| MBR     | 21       | 17.8%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 76.86%  |
| Yes       | 28       | 23.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 65.83%  |
| Yes       | 41       | 34.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 29       | 24.58%  |
| Gigabyte Technology | 20       | 16.95%  |
| Dell                | 15       | 12.71%  |
| Intel               | 13       | 11.02%  |
| MSI                 | 11       | 9.32%   |
| Lenovo              | 6        | 5.08%   |
| Hewlett-Packard     | 6        | 5.08%   |
| Biostar             | 5        | 4.24%   |
| ASRock              | 4        | 3.39%   |
| Acer                | 4        | 3.39%   |
| ECS                 | 2        | 1.69%   |
| Shuttle             | 1        | 0.85%   |
| ONDA                | 1        | 0.85%   |
| AMI                 | 1        | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Intel DH61WW AAG23116-204           | 6        | 5.08%   |
| ASUS All Series                     | 6        | 5.08%   |
| MSI MS-7817                         | 3        | 2.54%   |
| Intel DH61WW AAG23116-300           | 3        | 2.54%   |
| Gigabyte B85M-D3H                   | 3        | 2.54%   |
| MSI MS-7C81                         | 2        | 1.69%   |
| MSI MS-7C52                         | 2        | 1.69%   |
| Intel MAHOBAY                       | 2        | 1.69%   |
| Gigabyte B450M S2H                  | 2        | 1.69%   |
| Dell XPS 8940                       | 2        | 1.69%   |
| Dell OptiPlex 990                   | 2        | 1.69%   |
| Dell OptiPlex 755                   | 2        | 1.69%   |
| Biostar G41D3C                      | 2        | 1.69%   |
| ASUS P8Z77-V LX                     | 2        | 1.69%   |
| Shuttle DH170                       | 1        | 0.85%   |
| ONDA H110-MINI V3.00                | 1        | 0.85%   |
| MSI MS-7D42                         | 1        | 0.85%   |
| MSI MS-7C02                         | 1        | 0.85%   |
| MSI MS-7B89                         | 1        | 0.85%   |
| MSI MS-7979                         | 1        | 0.85%   |
| Lenovo ThinkStation S10 6483CTO     | 1        | 0.85%   |
| Lenovo ThinkStation P620 30E0S0E000 | 1        | 0.85%   |
| Lenovo ThinkStation P500 30A6S1B50X | 1        | 0.85%   |
| Lenovo ThinkCentre M72e 32673M3     | 1        | 0.85%   |
| Lenovo ThinkCentre M700 10GQCTO1WW  | 1        | 0.85%   |
| Lenovo ThinkCentre M58 7359DHJ      | 1        | 0.85%   |
| Intel DH77KC AAG39641-400           | 1        | 0.85%   |
| Intel B75                           | 1        | 0.85%   |
| HP Compaq dc7800p Small Form Factor | 1        | 0.85%   |
| HP Compaq dc7800 Small Form Factor  | 1        | 0.85%   |
| HP Compaq dc5800 Small Form Factor  | 1        | 0.85%   |
| HP Compaq 8000 Elite CMT PC         | 1        | 0.85%   |
| HP 500-536d                         | 1        | 0.85%   |
| HP 23-q145d                         | 1        | 0.85%   |
| Gigabyte Z97X-Gaming G1             | 1        | 0.85%   |
| Gigabyte Z490 VISION D              | 1        | 0.85%   |
| Gigabyte Z390 GAMING X              | 1        | 0.85%   |
| Gigabyte X570 AORUS MASTER          | 1        | 0.85%   |
| Gigabyte X570 AORUS ELITE WIFI      | 1        | 0.85%   |
| Gigabyte M61PME-S2P                 | 1        | 0.85%   |
| Gigabyte H77M-D3H                   | 1        | 0.85%   |
| Gigabyte H61M-S2P-R3                | 1        | 0.85%   |
| Gigabyte H470 HD3                   | 1        | 0.85%   |
| Gigabyte H370M-D3H                  | 1        | 0.85%   |
| Gigabyte GA-890GPA-UD3H             | 1        | 0.85%   |
| Gigabyte F2A88XM-HD3P               | 1        | 0.85%   |
| Gigabyte B450M S2H V2               | 1        | 0.85%   |
| Gigabyte AB350M-Gaming 3            | 1        | 0.85%   |
| Gigabyte A320M-S2H V2               | 1        | 0.85%   |
| ECS KZ224AA-AB4 g3620l              | 1        | 0.85%   |
| ECS H61H2-M12                       | 1        | 0.85%   |
| Dell Precision WorkStation T5400    | 1        | 0.85%   |
| Dell Precision Tower 3620           | 1        | 0.85%   |
| Dell Precision T1700                | 1        | 0.85%   |
| Dell Precision T1650                | 1        | 0.85%   |
| Dell OptiPlex 980                   | 1        | 0.85%   |
| Dell OptiPlex 7010                  | 1        | 0.85%   |
| Dell OptiPlex 3020                  | 1        | 0.85%   |
| Dell Inspiron 530s                  | 1        | 0.85%   |
| Dell Inspiron 530                   | 1        | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Intel DH61WW            | 9        | 7.63%   |
| Dell OptiPlex           | 7        | 5.93%   |
| ASUS All                | 6        | 5.08%   |
| HP Compaq               | 4        | 3.39%   |
| Dell Precision          | 4        | 3.39%   |
| MSI MS-7817             | 3        | 2.54%   |
| Lenovo ThinkStation     | 3        | 2.54%   |
| Lenovo ThinkCentre      | 3        | 2.54%   |
| Gigabyte B85M-D3H       | 3        | 2.54%   |
| Gigabyte B450M          | 3        | 2.54%   |
| ASUS TUF                | 3        | 2.54%   |
| ASUS P8B75-M            | 3        | 2.54%   |
| MSI MS-7C81             | 2        | 1.69%   |
| MSI MS-7C52             | 2        | 1.69%   |
| Intel MAHOBAY           | 2        | 1.69%   |
| Gigabyte X570           | 2        | 1.69%   |
| Dell XPS                | 2        | 1.69%   |
| Dell Inspiron           | 2        | 1.69%   |
| Biostar G41D3C          | 2        | 1.69%   |
| ASUS ROG                | 2        | 1.69%   |
| ASUS PRIME              | 2        | 1.69%   |
| ASUS P8Z77-V            | 2        | 1.69%   |
| Acer Veriton            | 2        | 1.69%   |
| Acer Aspire             | 2        | 1.69%   |
| Shuttle DH170           | 1        | 0.85%   |
| ONDA H110-MINI          | 1        | 0.85%   |
| MSI MS-7D42             | 1        | 0.85%   |
| MSI MS-7C02             | 1        | 0.85%   |
| MSI MS-7B89             | 1        | 0.85%   |
| MSI MS-7979             | 1        | 0.85%   |
| Intel DH77KC            | 1        | 0.85%   |
| Intel B75               | 1        | 0.85%   |
| HP 500-536d             | 1        | 0.85%   |
| HP 23-q145d             | 1        | 0.85%   |
| Gigabyte Z97X-Gaming    | 1        | 0.85%   |
| Gigabyte Z490           | 1        | 0.85%   |
| Gigabyte Z390           | 1        | 0.85%   |
| Gigabyte M61PME-S2P     | 1        | 0.85%   |
| Gigabyte H77M-D3H       | 1        | 0.85%   |
| Gigabyte H61M-S2P-R3    | 1        | 0.85%   |
| Gigabyte H470           | 1        | 0.85%   |
| Gigabyte H370M-D3H      | 1        | 0.85%   |
| Gigabyte GA-890GPA-UD3H | 1        | 0.85%   |
| Gigabyte F2A88XM-HD3P   | 1        | 0.85%   |
| Gigabyte AB350M-Gaming  | 1        | 0.85%   |
| Gigabyte A320M-S2H      | 1        | 0.85%   |
| ECS KZ224AA-AB4         | 1        | 0.85%   |
| ECS H61H2-M12           | 1        | 0.85%   |
| Biostar H81MHV3         | 1        | 0.85%   |
| Biostar G41D3+          | 1        | 0.85%   |
| Biostar A320MH          | 1        | 0.85%   |
| ASUS Z170               | 1        | 0.85%   |
| ASUS P8Z77-M            | 1        | 0.85%   |
| ASUS P8Z68-V            | 1        | 0.85%   |
| ASUS P6T                | 1        | 0.85%   |
| ASUS P5QPL-VM           | 1        | 0.85%   |
| ASUS P5QPL-AM           | 1        | 0.85%   |
| ASUS P5G41T-M           | 1        | 0.85%   |
| ASUS M2N32-SLI          | 1        | 0.85%   |
| ASUS H110M-D            | 1        | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 16       | 13.56%  |
| 2018 | 13       | 11.02%  |
| 2013 | 12       | 10.17%  |
| 2011 | 11       | 9.32%   |
| 2015 | 9        | 7.63%   |
| 2020 | 8        | 6.78%   |
| 2008 | 7        | 5.93%   |
| 2017 | 6        | 5.08%   |
| 2010 | 6        | 5.08%   |
| 2009 | 6        | 5.08%   |
| 2007 | 6        | 5.08%   |
| 2021 | 5        | 4.24%   |
| 2019 | 5        | 4.24%   |
| 2014 | 5        | 4.24%   |
| 2022 | 2        | 1.69%   |
| 2006 | 1        | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 118      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 115      | 97.46%  |
| Enabled  | 3        | 2.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 118      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 28       | 23.33%  |
| 8.01-16.0   | 24       | 20%     |
| 4.01-8.0    | 20       | 16.67%  |
| 3.01-4.0    | 17       | 14.17%  |
| 32.01-64.0  | 15       | 12.5%   |
| 1.01-2.0    | 8        | 6.67%   |
| 24.01-32.0  | 3        | 2.5%    |
| 64.01-256.0 | 3        | 2.5%    |
| 2.01-3.0    | 2        | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 44       | 33.85%  |
| 2.01-3.0   | 36       | 27.69%  |
| 3.01-4.0   | 18       | 13.85%  |
| 0.51-1.0   | 12       | 9.23%   |
| 4.01-8.0   | 11       | 8.46%   |
| 8.01-16.0  | 6        | 4.62%   |
| 0.01-0.5   | 2        | 1.54%   |
| 24.01-32.0 | 1        | 0.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 51       | 41.46%  |
| 2      | 35       | 28.46%  |
| 3      | 15       | 12.2%   |
| 5      | 8        | 6.5%    |
| 4      | 8        | 6.5%    |
| 7      | 3        | 2.44%   |
| 6      | 2        | 1.63%   |
| 8      | 1        | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 61.34%  |
| Yes       | 46       | 38.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 106      | 89.83%  |
| No        | 12       | 10.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 76       | 63.33%  |
| No        | 44       | 36.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 68.91%  |
| Yes       | 37       | 31.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Malaysia | 118      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Kuala Lumpur           | 41       | 32.03%  |
| Petaling Jaya          | 15       | 11.72%  |
| George Town            | 6        | 4.69%   |
| Shah Alam              | 4        | 3.13%   |
| Sungai Buloh           | 3        | 2.34%   |
| Subang Jaya            | 3        | 2.34%   |
| Seremban               | 3        | 2.34%   |
| Puchong Batu Dua Belas | 3        | 2.34%   |
| Kulim                  | 3        | 2.34%   |
| Kajang                 | 3        | 2.34%   |
| Butterworth            | 3        | 2.34%   |
| Tawau                  | 2        | 1.56%   |
| Malacca                | 2        | 1.56%   |
| Kuching                | 2        | 1.56%   |
| Kota Kinabalu          | 2        | 1.56%   |
| Kota Bharu             | 2        | 1.56%   |
| Bukit Mertajam         | 2        | 1.56%   |
| Bayan Lepas            | 2        | 1.56%   |
| Ampang                 | 2        | 1.56%   |
| Alor Star              | 2        | 1.56%   |
| Taiping                | 1        | 0.78%   |
| Sungai Petani          | 1        | 0.78%   |
| Semenyih               | 1        | 0.78%   |
| Rawang                 | 1        | 0.78%   |
| Putrajaya              | 1        | 0.78%   |
| Penampang              | 1        | 0.78%   |
| Padang Serai           | 1        | 0.78%   |
| Muar town              | 1        | 0.78%   |
| Marabu                 | 1        | 0.78%   |
| Long Seridan           | 1        | 0.78%   |
| Labuan                 | 1        | 0.78%   |
| Kulai                  | 1        | 0.78%   |
| Kuantan                | 1        | 0.78%   |
| Klang                  | 1        | 0.78%   |
| Johor Bahru            | 1        | 0.78%   |
| Ipoh                   | 1        | 0.78%   |
| Cukai                  | 1        | 0.78%   |
| Cheras                 | 1        | 0.78%   |
| Bukit Asahan           | 1        | 0.78%   |
| Batu Caves             | 1        | 0.78%   |
| Bandar Tenggara        | 1        | 0.78%   |
| Ayer Itam              | 1        | 0.78%   |
| Ajil                   | 1        | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 49       | 99     | 22.37%  |
| Seagate                   | 48       | 68     | 21.92%  |
| Kingston                  | 23       | 36     | 10.5%   |
| Samsung Electronics       | 19       | 28     | 8.68%   |
| Toshiba                   | 12       | 14     | 5.48%   |
| Crucial                   | 7        | 13     | 3.2%    |
| Intel                     | 5        | 9      | 2.28%   |
| A-DATA Technology         | 5        | 8      | 2.28%   |
| SanDisk                   | 4        | 7      | 1.83%   |
| Apacer                    | 4        | 8      | 1.83%   |
| Phison                    | 3        | 4      | 1.37%   |
| China                     | 3        | 3      | 1.37%   |
| XPG                       | 2        | 3      | 0.91%   |
| Unknown                   | 2        | 3      | 0.91%   |
| TO Exter                  | 2        | 4      | 0.91%   |
| Silicon Motion            | 2        | 3      | 0.91%   |
| Plextor                   | 2        | 2      | 0.91%   |
| Micron Technology         | 2        | 6      | 0.91%   |
| Hitachi                   | 2        | 2      | 0.91%   |
| Hewlett-Packard           | 2        | 2      | 0.91%   |
| Gigabyte Technology       | 2        | 2      | 0.91%   |
| Verbatim                  | 1        | 1      | 0.46%   |
| Transcend                 | 1        | 1      | 0.46%   |
| SK hynix                  | 1        | 1      | 0.46%   |
| SATAFIRM                  | 1        | 1      | 0.46%   |
| PNY                       | 1        | 1      | 0.46%   |
| OCZ                       | 1        | 1      | 0.46%   |
| Micron/Crucial Technology | 1        | 1      | 0.46%   |
| Maxtor                    | 1        | 1      | 0.46%   |
| MAX                       | 1        | 1      | 0.46%   |
| LITEON                    | 1        | 1      | 0.46%   |
| KIOXIA-EXCERIA            | 1        | 3      | 0.46%   |
| Kingchuxing               | 1        | 1      | 0.46%   |
| JMicron Technology        | 1        | 1      | 0.46%   |
| Hikvision                 | 1        | 2      | 0.46%   |
| HGST                      | 1        | 1      | 0.46%   |
| GAMER                     | 1        | 1      | 0.46%   |
| External                  | 1        | 1      | 0.46%   |
| Colorful                  | 1        | 1      | 0.46%   |
| ASMT                      | 1        | 2      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD    | 9        | 3.44%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 5        | 1.91%   |
| Seagate ST380815AS 80GB            | 5        | 1.91%   |
| Seagate ST1000DM010-2EP102 1TB     | 5        | 1.91%   |
| WDC WD20EZRX-00D8PB0 2TB           | 4        | 1.53%   |
| Seagate ST3160815AS 160GB          | 4        | 1.53%   |
| Samsung HD103SJ 1TB                | 4        | 1.53%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 3        | 1.15%   |
| Seagate ST500DM002-1BC142 500GB    | 3        | 1.15%   |
| Seagate ST1000DM003-1ER162 1TB     | 3        | 1.15%   |
| Seagate ST1000DM003-1CH162 1TB     | 3        | 1.15%   |
| Kingston NVMe SSD Drive 500GB      | 3        | 1.15%   |
| Crucial CT500MX500SSD1 500GB       | 3        | 1.15%   |
| XPG NVMe SSD Drive 512GB           | 2        | 0.76%   |
| WDC WD800JD-22MSA1 80GB            | 2        | 0.76%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 2        | 0.76%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 2        | 0.76%   |
| WDC WD5000AAKX-001CA0 500GB        | 2        | 0.76%   |
| WDC WD40EZRZ-00WN9B0 4TB           | 2        | 0.76%   |
| WDC WD360ADFD-00NLR1 37GB          | 2        | 0.76%   |
| WDC WD3200AAKS-00SBA0 320GB        | 2        | 0.76%   |
| WDC WD2500AAKX-753CA1 250GB        | 2        | 0.76%   |
| WDC WD10EZEX-00MFCA0 1TB           | 2        | 0.76%   |
| WDC WD10EZEX-00BN5A0 1TB           | 2        | 0.76%   |
| Toshiba DT01ACA050 500GB           | 2        | 0.76%   |
| TO Exter nal USB 3.0 1TB           | 2        | 0.76%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 0.76%   |
| Seagate ST3500414CS 500GB          | 2        | 0.76%   |
| Seagate ST3408111AS 40GB           | 2        | 0.76%   |
| Seagate ST3320620A 320GB           | 2        | 0.76%   |
| Seagate ST3250318AS 250GB          | 2        | 0.76%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 0.76%   |
| Seagate ST2000DM006-2DM164 2TB     | 2        | 0.76%   |
| Seagate ST2000DM001-1ER164 2TB     | 2        | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.76%   |
| SanDisk SDSSDH3 250G               | 2        | 0.76%   |
| Samsung SSD 960 EVO 250GB          | 2        | 0.76%   |
| Samsung SSD 860 EVO 250GB          | 2        | 0.76%   |
| Samsung NVMe SSD Drive 250GB       | 2        | 0.76%   |
| Kingston SV300S37A60G 64GB SSD     | 2        | 0.76%   |
| Kingston SV300S37A120G 120GB SSD   | 2        | 0.76%   |
| Kingston SA400S37480G 480GB SSD    | 2        | 0.76%   |
| Crucial CT480BX500SSD1 480GB       | 2        | 0.76%   |
| Crucial CT1000MX500SSD1 1TB        | 2        | 0.76%   |
| China SSD 128GB                    | 2        | 0.76%   |
| A-DATA SX8200PNP 512GB             | 2        | 0.76%   |
| A-DATA SU650 120GB SSD             | 2        | 0.76%   |
| XPG NVMe SSD Drive 1TB             | 1        | 0.38%   |
| WDC WDS120G1G0B-00RC30 120GB SSD   | 1        | 0.38%   |
| WDC WD800BEVT-75ZCT2 80GB          | 1        | 0.38%   |
| WDC WD800AAJS-00PSA0 80GB          | 1        | 0.38%   |
| WDC WD6400AAKS-00A7B0 640GB        | 1        | 0.38%   |
| WDC WD5000AAKX-753CA1 500GB        | 1        | 0.38%   |
| WDC WD5000AADS-00S9B0 500GB        | 1        | 0.38%   |
| WDC WD50 00BEVT-60A0RT0 500GB      | 1        | 0.38%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1        | 0.38%   |
| WDC WD40EZRX-00SPEB0 4TB           | 1        | 0.38%   |
| WDC WD3200AAKS-75VYA0 320GB        | 1        | 0.38%   |
| WDC WD3200AAKS-00L9A0 320GB        | 1        | 0.38%   |
| WDC WD3200AAJS-00L7A0 320GB        | 1        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 47       | 97     | 38.84%  |
| Seagate             | 47       | 67     | 38.84%  |
| Toshiba             | 12       | 14     | 9.92%   |
| Samsung Electronics | 8        | 12     | 6.61%   |
| Hitachi             | 2        | 2      | 1.65%   |
| SATAFIRM            | 1        | 1      | 0.83%   |
| Maxtor              | 1        | 1      | 0.83%   |
| HGST                | 1        | 1      | 0.83%   |
| Hewlett-Packard     | 1        | 1      | 0.83%   |
| ASMT                | 1        | 2      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 20       | 29     | 29.85%  |
| Samsung Electronics | 7        | 9      | 10.45%  |
| Crucial             | 7        | 13     | 10.45%  |
| Apacer              | 4        | 8      | 5.97%   |
| SanDisk             | 3        | 6      | 4.48%   |
| Intel               | 3        | 6      | 4.48%   |
| China               | 3        | 3      | 4.48%   |
| A-DATA Technology   | 3        | 3      | 4.48%   |
| TO Exter            | 2        | 4      | 2.99%   |
| Plextor             | 2        | 2      | 2.99%   |
| WDC                 | 1        | 1      | 1.49%   |
| Verbatim            | 1        | 1      | 1.49%   |
| Transcend           | 1        | 1      | 1.49%   |
| SK hynix            | 1        | 1      | 1.49%   |
| Seagate             | 1        | 1      | 1.49%   |
| OCZ                 | 1        | 1      | 1.49%   |
| Micron Technology   | 1        | 5      | 1.49%   |
| LITEON              | 1        | 1      | 1.49%   |
| KIOXIA-EXCERIA      | 1        | 3      | 1.49%   |
| JMicron Technology  | 1        | 1      | 1.49%   |
| Hikvision           | 1        | 2      | 1.49%   |
| Hewlett-Packard     | 1        | 1      | 1.49%   |
| Colorful            | 1        | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 95       | 198    | 53.98%  |
| SSD     | 56       | 103    | 31.82%  |
| NVMe    | 20       | 40     | 11.36%  |
| Unknown | 4        | 5      | 2.27%   |
| MMC     | 1        | 1      | 0.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 110      | 293    | 78.57%  |
| NVMe | 20       | 39     | 14.29%  |
| SAS  | 9        | 14     | 6.43%   |
| MMC  | 1        | 1      | 0.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 95       | 172    | 58.64%  |
| 0.51-1.0   | 41       | 77     | 25.31%  |
| 1.01-2.0   | 20       | 37     | 12.35%  |
| 3.01-4.0   | 3        | 11     | 1.85%   |
| 4.01-10.0  | 2        | 3      | 1.23%   |
| 2.01-3.0   | 1        | 1      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 38       | 30.16%  |
| 251-500        | 16       | 12.7%   |
| 501-1000       | 16       | 12.7%   |
| 1001-2000      | 14       | 11.11%  |
| 51-100         | 11       | 8.73%   |
| More than 3000 | 9        | 7.14%   |
| 1-20           | 8        | 6.35%   |
| 21-50          | 7        | 5.56%   |
| 2001-3000      | 4        | 3.17%   |
| Unknown        | 3        | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 56       | 43.41%  |
| 21-50          | 15       | 11.63%  |
| 51-100         | 15       | 11.63%  |
| 101-250        | 14       | 10.85%  |
| 251-500        | 9        | 6.98%   |
| More than 3000 | 6        | 4.65%   |
| 1001-2000      | 6        | 4.65%   |
| 501-1000       | 4        | 3.1%    |
| Unknown        | 3        | 2.33%   |
| 2001-3000      | 1        | 0.78%   |

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
| Detected | 79       | 255    | 60.31%  |
| Works    | 40       | 78     | 30.53%  |
| Malfunc  | 12       | 14     | 9.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 93       | 61.59%  |
| AMD                         | 20       | 13.25%  |
| Phison Electronics          | 6        | 3.97%   |
| Samsung Electronics         | 5        | 3.31%   |
| Nvidia                      | 4        | 2.65%   |
| Marvell Technology Group    | 4        | 2.65%   |
| Kingston Technology Company | 3        | 1.99%   |
| JMicron Technology          | 3        | 1.99%   |
| ASMedia Technology          | 3        | 1.99%   |
| Silicon Motion              | 2        | 1.32%   |
| SanDisk                     | 2        | 1.32%   |
| ADATA Technology            | 2        | 1.32%   |
| Silicon Image               | 1        | 0.66%   |
| Micron/Crucial Technology   | 1        | 0.66%   |
| Micron Technology           | 1        | 0.66%   |
| Lite-On IT Corp. / Plextor  | 1        | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 16       | 7.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13       | 6.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 13       | 6.4%    |
| Intel SATA Controller [RAID mode]                                              | 9        | 4.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9        | 4.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 3.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7        | 3.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7        | 3.45%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 5        | 2.46%   |
| AMD 400 Series Chipset SATA Controller                                         | 5        | 2.46%   |
| Intel 82Q35 Express PT IDER Controller                                         | 4        | 1.97%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 4        | 1.97%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 4        | 1.97%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 4        | 1.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 1.48%   |
| Phison PS5013 E13 NVMe Controller                                              | 3        | 1.48%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 1.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 1.48%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 1.48%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3        | 1.48%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 1.48%   |
| AMD FCH SATA Controller D                                                      | 3        | 1.48%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 0.99%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.99%   |
| Nvidia MCP61 SATA Controller                                                   | 2        | 0.99%   |
| Nvidia MCP61 IDE                                                               | 2        | 0.99%   |
| Kingston Company Company Non-Volatile memory controller                        | 2        | 0.99%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 0.99%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 0.99%   |
| Intel Comet Lake PCH-H RAID                                                    | 2        | 0.99%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 2        | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2        | 0.99%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 0.99%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2        | 0.99%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.49%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.49%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.49%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 0.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.49%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.49%   |
| Nvidia MCP73 SATA RAID Controller                                              | 1        | 0.49%   |
| Nvidia MCP73 IDE Controller                                                    | 1        | 0.49%   |
| Nvidia MCP55 SATA Controller                                                   | 1        | 0.49%   |
| Nvidia MCP55 IDE                                                               | 1        | 0.49%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1        | 0.49%   |
| Micron Non-Volatile memory controller                                          | 1        | 0.49%   |
| Marvell Group 88SE9220 PCIe 2.0 x2 2-port SATA 6 Gb/s RAID Controller          | 1        | 0.49%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 0.49%   |
| Lite-On IT Corp. / Plextor M6e PCI Express SSD [Marvell 88SS9183]              | 1        | 0.49%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 0.49%   |
| JMicron JMB362 SATA Controller                                                 | 1        | 0.49%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1        | 0.49%   |
| Intel NVMe Optane Memory Series                                                | 1        | 0.49%   |
| Intel C610/X99 series chipset IDE-r Controller                                 | 1        | 0.49%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 0.49%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1        | 0.49%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 83       | 54.97%  |
| IDE  | 33       | 21.85%  |
| NVMe | 20       | 13.25%  |
| RAID | 15       | 9.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 95       | 80.51%  |
| AMD    | 23       | 19.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium CPU G620 @ 2.60GHz            | 7        | 5.93%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 4        | 3.39%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 3        | 2.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.54%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 2.54%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 2.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.54%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 2.54%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 2        | 1.69%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 1.69%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.69%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.69%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 1.69%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.69%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.69%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 1.69%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.69%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.69%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.69%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 2        | 1.69%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.69%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.69%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 2        | 1.69%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.69%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.69%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 2        | 1.69%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz          | 1        | 0.85%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.85%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 0.85%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 0.85%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1        | 0.85%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.85%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.85%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.85%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.85%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 0.85%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.85%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.85%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.85%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 0.85%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.85%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.85%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 0.85%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1        | 0.85%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 0.85%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 0.85%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 0.85%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 0.85%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 0.85%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 0.85%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 0.85%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1        | 0.85%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1        | 0.85%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 0.85%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 1        | 0.85%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 1        | 0.85%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 0.85%   |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz        | 1        | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 26       | 22.03%  |
| Intel Pentium           | 13       | 11.02%  |
| Intel Core i3           | 13       | 11.02%  |
| Intel Core i7           | 11       | 9.32%   |
| Intel Core 2 Duo        | 11       | 9.32%   |
| AMD Ryzen 5             | 8        | 6.78%   |
| Intel Xeon              | 7        | 5.93%   |
| Other                   | 5        | 4.24%   |
| Intel Core 2 Quad       | 4        | 3.39%   |
| AMD Ryzen 7             | 4        | 3.39%   |
| AMD Ryzen 3             | 3        | 2.54%   |
| Intel Pentium Dual-Core | 2        | 1.69%   |
| AMD Athlon 64 X2        | 2        | 1.69%   |
| AMD A10                 | 2        | 1.69%   |
| Intel Pentium Dual      | 1        | 0.85%   |
| Intel Core i9           | 1        | 0.85%   |
| Intel Atom              | 1        | 0.85%   |
| AMD Ryzen Threadripper  | 1        | 0.85%   |
| AMD Phenom II X6        | 1        | 0.85%   |
| AMD Athlon X2           | 1        | 0.85%   |
| AMD A6                  | 1        | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 49       | 41.53%  |
| 2      | 43       | 36.44%  |
| 6      | 15       | 12.71%  |
| 8      | 6        | 5.08%   |
| 12     | 3        | 2.54%   |
| 10     | 1        | 0.85%   |
| 3      | 1        | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 118      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 71       | 60.17%  |
| 2      | 47       | 39.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 118      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 19       | 15.7%   |
| Unknown    | 18       | 14.88%  |
| 0x206a7    | 13       | 10.74%  |
| 0x306a9    | 12       | 9.92%   |
| 0x1067a    | 12       | 9.92%   |
| 0x506e3    | 5        | 4.13%   |
| 0x08108109 | 5        | 4.13%   |
| 0x6fd      | 3        | 2.48%   |
| 0x6fb      | 3        | 2.48%   |
| 0x08701021 | 3        | 2.48%   |
| 0xa0671    | 2        | 1.65%   |
| 0xa0655    | 2        | 1.65%   |
| 0x906ea    | 2        | 1.65%   |
| 0x906e9    | 2        | 1.65%   |
| 0x90672    | 2        | 1.65%   |
| 0x10676    | 2        | 1.65%   |
| 0xa0653    | 1        | 0.83%   |
| 0x906eb    | 1        | 0.83%   |
| 0x406c3    | 1        | 0.83%   |
| 0x306f2    | 1        | 0.83%   |
| 0x206d7    | 1        | 0.83%   |
| 0x106a5    | 1        | 0.83%   |
| 0x0a20120a | 1        | 0.83%   |
| 0x0a201009 | 1        | 0.83%   |
| 0x08701013 | 1        | 0.83%   |
| 0x08301039 | 1        | 0.83%   |
| 0x08001136 | 1        | 0.83%   |
| 0x08001126 | 1        | 0.83%   |
| 0x06003106 | 1        | 0.83%   |
| 0x03000027 | 1        | 0.83%   |
| 0x010000dc | 1        | 0.83%   |
| 0x00000000 | 1        | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 20       | 16.95%  |
| SandyBridge      | 16       | 13.56%  |
| IvyBridge        | 15       | 12.71%  |
| Penryn           | 14       | 11.86%  |
| KabyLake         | 7        | 5.93%   |
| Zen+             | 6        | 5.08%   |
| Core             | 6        | 5.08%   |
| Zen 2            | 5        | 4.24%   |
| Skylake          | 5        | 4.24%   |
| CometLake        | 4        | 3.39%   |
| Zen              | 3        | 2.54%   |
| Unknown          | 3        | 2.54%   |
| Zen 3            | 2        | 1.69%   |
| K8 Hammer        | 2        | 1.69%   |
| K10              | 2        | 1.69%   |
| Alderlake Hybrid | 2        | 1.69%   |
| Westmere         | 1        | 0.85%   |
| Steamroller      | 1        | 0.85%   |
| Silvermont       | 1        | 0.85%   |
| Nehalem          | 1        | 0.85%   |
| K10 Llano        | 1        | 0.85%   |
| Excavator        | 1        | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 49       | 38.89%  |
| Intel  | 44       | 34.92%  |
| AMD    | 33       | 26.19%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8        | 6.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7        | 5.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6        | 4.72%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 5        | 3.94%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 5        | 3.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 3.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 3.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5        | 3.94%   |
| Intel HD Graphics 530                                                                    | 4        | 3.15%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4        | 3.15%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 2.36%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 1.57%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2        | 1.57%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2        | 1.57%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2        | 1.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 1.57%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.57%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 2        | 1.57%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2        | 1.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.57%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 1.57%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 1.57%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2        | 1.57%   |
| AMD Bonaire XT [Radeon HD 7790/8770 / R7 360 / R9 260/360 OEM]                           | 2        | 1.57%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.79%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1        | 0.79%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 0.79%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1        | 0.79%   |
| Nvidia TU106 [GeForce GTX 1650]                                                          | 1        | 0.79%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.79%   |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 0.79%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.79%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                                      | 1        | 0.79%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.79%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1        | 0.79%   |
| Nvidia GK107GL [Quadro K420]                                                             | 1        | 0.79%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.79%   |
| Nvidia GK104 [GeForce GTX 690]                                                           | 1        | 0.79%   |
| Nvidia GK104 [GeForce GTX 670]                                                           | 1        | 0.79%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1        | 0.79%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 0.79%   |
| Nvidia GF108 [GeForce GT 620]                                                            | 1        | 0.79%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 0.79%   |
| Nvidia C73 [GeForce 7100 / nForce 620i]                                                  | 1        | 0.79%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 0.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 0.79%   |
| Intel HD Graphics 630                                                                    | 1        | 0.79%   |
| Intel HD Graphics 610                                                                    | 1        | 0.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 0.79%   |
| Intel 82Q33 Express Integrated Graphics Controller                                       | 1        | 0.79%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 0.79%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1        | 0.79%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                                        | 1        | 0.79%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                                    | 1        | 0.79%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                                | 1        | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 48       | 40.68%  |
| 1 x Intel      | 36       | 30.51%  |
| 1 x AMD        | 31       | 26.27%  |
| 2 x AMD        | 1        | 0.85%   |
| Intel + Nvidia | 1        | 0.85%   |
| Intel + AMD    | 1        | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 92       | 77.31%  |
| Proprietary | 23       | 19.33%  |
| Unknown     | 4        | 3.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 43       | 36.44%  |
| 1.01-2.0   | 26       | 22.03%  |
| 0.51-1.0   | 17       | 14.41%  |
| 7.01-8.0   | 11       | 9.32%   |
| 3.01-4.0   | 8        | 6.78%   |
| 0.01-0.5   | 7        | 5.93%   |
| 5.01-6.0   | 3        | 2.54%   |
| 8.01-16.0  | 2        | 1.69%   |
| 2.01-3.0   | 1        | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 25       | 20.49%  |
| Samsung Electronics  | 14       | 11.48%  |
| Hewlett-Packard      | 14       | 11.48%  |
| Acer                 | 13       | 10.66%  |
| Goldstar             | 10       | 8.2%    |
| AOC                  | 10       | 8.2%    |
| BenQ                 | 8        | 6.56%   |
| ViewSonic            | 6        | 4.92%   |
| Philips              | 4        | 3.28%   |
| ASUSTek Computer     | 3        | 2.46%   |
| Toshiba              | 2        | 1.64%   |
| Sharp                | 2        | 1.64%   |
| LG Electronics       | 2        | 1.64%   |
| Lenovo               | 2        | 1.64%   |
| Panasonic            | 1        | 0.82%   |
| HUYINIUDA            | 1        | 0.82%   |
| Envision Peripherals | 1        | 0.82%   |
| Dinner               | 1        | 0.82%   |
| Denver               | 1        | 0.82%   |
| CVT                  | 1        | 0.82%   |
| Unknown              | 1        | 0.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 5        | 3.79%   |
| Dell E2720HS DELA15E 1920x1080 598x336mm 27.0-inch                   | 3        | 2.27%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 3        | 2.27%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                    | 3        | 2.27%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 2        | 1.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2        | 1.52%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                   | 2        | 1.52%   |
| Hewlett-Packard LCD Monitor P221                                     | 2        | 1.52%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 2        | 1.52%   |
| Dell LCD Monitor E2720HS 1920x1080                                   | 2        | 1.52%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                    | 2        | 1.52%   |
| ASUSTek Computer XG32VQR AUS32B2 2560x1440 697x393mm 31.5-inch       | 2        | 1.52%   |
| AOC LCD Monitor 936W 1366x768                                        | 2        | 1.52%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                        | 2        | 1.52%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                       | 2        | 1.52%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch        | 1        | 0.76%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch            | 1        | 0.76%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch            | 1        | 0.76%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch        | 1        | 0.76%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch           | 1        | 0.76%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch         | 1        | 0.76%   |
| Toshiba TV TSB0113 1920x1080 1220x680mm 55.0-inch                    | 1        | 0.76%   |
| Toshiba Crystal View LCD0001 1920x1080 408x255mm 18.9-inch           | 1        | 0.76%   |
| Sharp LCD SHP10C9 1920x540                                           | 1        | 0.76%   |
| Sharp LC-22LE420M SHP2242 1920x1080 477x268mm 21.5-inch              | 1        | 0.76%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 0.76%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch     | 1        | 0.76%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch    | 1        | 0.76%   |
| Samsung Electronics S24C350 SAM0A3C 1920x1080 520x290mm 23.4-inch    | 1        | 0.76%   |
| Samsung Electronics S23C350 SAM0A35 1920x1080 510x287mm 23.0-inch    | 1        | 0.76%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch    | 1        | 0.76%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch     | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM0E9B 1366x768 609x347mm 27.6-inch | 1        | 0.76%   |
| Samsung Electronics LCD Monitor S24B350 1920x1080                    | 1        | 0.76%   |
| Samsung Electronics C27FG70 SAM0DC9 1920x1080 598x337mm 27.0-inch    | 1        | 0.76%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 598x336mm 27.0-inch              | 1        | 0.76%   |
| Philips LCD Monitor 40PFA4509 1920x1080                              | 1        | 0.76%   |
| Panasonic TV MEIC32C 1280x720 698x392mm 31.5-inch                    | 1        | 0.76%   |
| LG Electronics LCD Monitor LG TV 1920x1080                           | 1        | 0.76%   |
| LG Electronics LCD Monitor 27GL850 5120x1440                         | 1        | 0.76%   |
| Lenovo L32p-30 LEN66C9 3840x2160 697x392mm 31.5-inch                 | 1        | 0.76%   |
| Lenovo E24-20 LEN62A5 1920x1080 527x296mm 23.8-inch                  | 1        | 0.76%   |
| HUYINIUDA HUYINIUDA HUY3200 1920x1080 376x301mm 19.0-inch            | 1        | 0.76%   |
| Hewlett-Packard ZR24w HWP286A 1920x1200 546x352mm 25.6-inch          | 1        | 0.76%   |
| Hewlett-Packard x2401 HWP303E 1920x1080 530x300mm 24.0-inch          | 1        | 0.76%   |
| Hewlett-Packard w1907 HWP26A3 1440x900 408x255mm 18.9-inch           | 1        | 0.76%   |
| Hewlett-Packard V24i HPN36AC 1920x1080 530x300mm 24.0-inch           | 1        | 0.76%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch         | 1        | 0.76%   |
| Hewlett-Packard LE1711 HWP2856 1280x1024 340x270mm 17.1-inch         | 1        | 0.76%   |
| Hewlett-Packard LCD Monitor Z23i                                     | 1        | 0.76%   |
| Hewlett-Packard LCD Monitor P221 1920x1080                           | 1        | 0.76%   |
| Hewlett-Packard LCD Monitor P201 5440x1080                           | 1        | 0.76%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 1        | 0.76%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch           | 1        | 0.76%   |
| Hewlett-Packard E231 HWP3063 1920x1080 510x287mm 23.0-inch           | 1        | 0.76%   |
| Hewlett-Packard ALL-in-One HWP4225 1920x1080 509x286mm 23.0-inch     | 1        | 0.76%   |
| Hewlett-Packard 24mq HPN366F 2560x1440 527x296mm 23.8-inch           | 1        | 0.76%   |
| Hewlett-Packard 20wd HWP3144 1600x900 432x239mm 19.4-inch            | 1        | 0.76%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 1        | 0.76%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch              | 1        | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 55       | 45.08%  |
| 1366x768 (WXGA)    | 15       | 12.3%   |
| 3840x2160 (4K)     | 8        | 6.56%   |
| 2560x1440 (QHD)    | 7        | 5.74%   |
| 1600x900 (HD+)     | 6        | 4.92%   |
| 1440x900 (WXGA+)   | 5        | 4.1%    |
| 2560x1080          | 4        | 3.28%   |
| Unknown            | 4        | 3.28%   |
| 1280x1024 (SXGA)   | 3        | 2.46%   |
| 5760x1080          | 2        | 1.64%   |
| 1680x1050 (WSXGA+) | 2        | 1.64%   |
| 1600x1200          | 2        | 1.64%   |
| 5440x1080          | 1        | 0.82%   |
| 5120x1440          | 1        | 0.82%   |
| 3840x1080          | 1        | 0.82%   |
| 3440x1440          | 1        | 0.82%   |
| 1920x540           | 1        | 0.82%   |
| 1920x1200 (WUXGA)  | 1        | 0.82%   |
| 1280x960           | 1        | 0.82%   |
| 1280x720 (HD)      | 1        | 0.82%   |
| 1024x768 (XGA)     | 1        | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 17       | 13.93%  |
| 23      | 15       | 12.3%   |
| 21      | 15       | 12.3%   |
| Unknown | 14       | 11.48%  |
| 18      | 13       | 10.66%  |
| 27      | 11       | 9.02%   |
| 19      | 11       | 9.02%   |
| 31      | 8        | 6.56%   |
| 20      | 5        | 4.1%    |
| 34      | 3        | 2.46%   |
| 17      | 3        | 2.46%   |
| 22      | 2        | 1.64%   |
| 55      | 1        | 0.82%   |
| 39      | 1        | 0.82%   |
| 28      | 1        | 0.82%   |
| 25      | 1        | 0.82%   |
| 15      | 1        | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 44       | 36.67%  |
| 501-600     | 40       | 33.33%  |
| Unknown     | 14       | 11.67%  |
| 601-700     | 11       | 9.17%   |
| 301-350     | 4        | 3.33%   |
| 701-800     | 3        | 2.5%    |
| 351-400     | 2        | 1.67%   |
| 801-900     | 1        | 0.83%   |
| 1001-1500   | 1        | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 81       | 69.83%  |
| Unknown | 13       | 11.21%  |
| 16/10   | 9        | 7.76%   |
| 5/4     | 5        | 4.31%   |
| 21/9    | 4        | 3.45%   |
| 4/3     | 3        | 2.59%   |
| 32/9    | 1        | 0.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 43       | 36.13%  |
| 151-200        | 20       | 16.81%  |
| 141-150        | 14       | 11.76%  |
| Unknown        | 14       | 11.76%  |
| 351-500        | 11       | 9.24%   |
| 301-350        | 11       | 9.24%   |
| 251-300        | 3        | 2.52%   |
| More than 1000 | 1        | 0.84%   |
| 101-110        | 1        | 0.84%   |
| 501-1000       | 1        | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 78       | 66.67%  |
| 101-120 | 19       | 16.24%  |
| Unknown | 14       | 11.97%  |
| 121-160 | 4        | 3.42%   |
| 1-50    | 2        | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 100      | 84.75%  |
| 2     | 11       | 9.32%   |
| 0     | 5        | 4.24%   |
| 3     | 2        | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 60       | 30.77%  |
| Intel                             | 50       | 25.64%  |
| Qualcomm Atheros                  | 16       | 8.21%   |
| TP-Link                           | 14       | 7.18%   |
| Ralink Technology                 | 13       | 6.67%   |
| D-Link                            | 9        | 4.62%   |
| Broadcom                          | 9        | 4.62%   |
| Xiaomi                            | 5        | 2.56%   |
| Qualcomm Atheros Communications   | 5        | 2.56%   |
| Nvidia                            | 3        | 1.54%   |
| Samsung Electronics               | 2        | 1.03%   |
| Sundance Technology Inc / IC Plus | 1        | 0.51%   |
| Ralink                            | 1        | 0.51%   |
| OPPO Electronics                  | 1        | 0.51%   |
| InterBiometrics                   | 1        | 0.51%   |
| D-Link System                     | 1        | 0.51%   |
| Broadcom Limited                  | 1        | 0.51%   |
| Aquantia                          | 1        | 0.51%   |
| Apple                             | 1        | 0.51%   |
| AboCom Systems                    | 1        | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 43       | 19.72%  |
| TP-Link 802.11ac NIC                                                                 | 8        | 3.67%   |
| Ralink MT7601U Wireless Adapter                                                      | 7        | 3.21%   |
| Intel 82579V Gigabit Network Connection                                              | 7        | 3.21%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 6        | 2.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 5        | 2.29%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 5        | 2.29%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 4        | 1.83%   |
| Realtek 802.11ac NIC                                                                 | 4        | 1.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 4        | 1.83%   |
| Intel I211 Gigabit Network Connection                                                | 4        | 1.83%   |
| Intel Ethernet Connection (11) I219-V                                                | 4        | 1.83%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 4        | 1.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                       | 3        | 1.38%   |
| TP-Link 802.11n NIC                                                                  | 3        | 1.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 1.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 3        | 1.38%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 1.38%   |
| Intel Ethernet Connection (7) I219-V                                                 | 3        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                                 | 3        | 1.38%   |
| Intel 82567LM-3 Gigabit Network Connection                                           | 3        | 1.38%   |
| Intel 82566DM-2 Gigabit Network Connection                                           | 3        | 1.38%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 3        | 1.38%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                 | 2        | 0.92%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2        | 0.92%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 0.92%   |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 0.92%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 2        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2        | 0.92%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 2        | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                           | 2        | 0.92%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                       | 2        | 0.92%   |
| Intel I350 Gigabit Fiber Network Connection                                          | 2        | 0.92%   |
| Intel Ethernet Controller I225-V                                                     | 2        | 0.92%   |
| Intel Ethernet Connection I217-V                                                     | 2        | 0.92%   |
| Intel Ethernet Connection I217-LM                                                    | 2        | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                                | 2        | 0.92%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 2        | 0.92%   |
| Intel 82583V Gigabit Network Connection                                              | 2        | 0.92%   |
| Intel 82562V-2 10/100 Network Connection                                             | 2        | 0.92%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                              | 2        | 0.92%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                      | 2        | 0.92%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 1        | 0.46%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY           | 1        | 0.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                          | 1        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                                        | 1        | 0.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 1        | 0.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.46%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 0.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 1        | 0.46%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                                     | 1        | 0.46%   |
| Ralink RT5572 Wireless Adapter                                                       | 1        | 0.46%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                          | 1        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                            | 1        | 0.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 1        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                             | 1        | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 1        | 0.46%   |
| OPPO SDM720G-IDP _SN:B922E265                                                        | 1        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 17       | 19.77%  |
| TP-Link                         | 14       | 16.28%  |
| Ralink Technology               | 13       | 15.12%  |
| Intel                           | 10       | 11.63%  |
| Qualcomm Atheros                | 9        | 10.47%  |
| D-Link                          | 9        | 10.47%  |
| Qualcomm Atheros Communications | 5        | 5.81%   |
| Broadcom                        | 5        | 5.81%   |
| Ralink                          | 1        | 1.16%   |
| D-Link System                   | 1        | 1.16%   |
| Broadcom Limited                | 1        | 1.16%   |
| AboCom Systems                  | 1        | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| TP-Link 802.11ac NIC                                                                 | 8        | 9.09%   |
| Ralink MT7601U Wireless Adapter                                                      | 7        | 7.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 5        | 5.68%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 5        | 5.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 4        | 4.55%   |
| Realtek 802.11ac NIC                                                                 | 4        | 4.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 4        | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 4.55%   |
| TP-Link 802.11n NIC                                                                  | 3        | 3.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 3.41%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 3.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 3        | 3.41%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2        | 2.27%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 2.27%   |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 2.27%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 2        | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 2        | 2.27%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 2        | 2.27%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 2        | 2.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 1        | 1.14%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 1        | 1.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.14%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.14%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 1.14%   |
| Ralink RT5572 Wireless Adapter                                                       | 1        | 1.14%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                          | 1        | 1.14%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 1        | 1.14%   |
| Intel Wireless-AC 9260                                                               | 1        | 1.14%   |
| Intel Wireless 3165                                                                  | 1        | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 1        | 1.14%   |
| Intel Wi-Fi 6 AX200                                                                  | 1        | 1.14%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]                    | 1        | 1.14%   |
| D-Link DWA-182 Wireless AC Dualband Adapter(rev.C) [Realtek RTL8812AU]               | 1        | 1.14%   |
| D-Link 802.11n WLAN Adapter                                                          | 1        | 1.14%   |
| D-Link 802.11ac NIC                                                                  | 1        | 1.14%   |
| D-Link 11ac adapter                                                                  | 1        | 1.14%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                           | 1        | 1.14%   |
| Broadcom BCM43228 802.11a/b/g/n                                                      | 1        | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 1        | 1.14%   |
| AboCom Systems 802.11n WLAN Adapter                                                  | 1        | 1.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 53       | 43.09%  |
| Intel                             | 45       | 36.59%  |
| Qualcomm Atheros                  | 7        | 5.69%   |
| Xiaomi                            | 5        | 4.07%   |
| Broadcom                          | 4        | 3.25%   |
| Nvidia                            | 3        | 2.44%   |
| Samsung Electronics               | 2        | 1.63%   |
| Sundance Technology Inc / IC Plus | 1        | 0.81%   |
| OPPO Electronics                  | 1        | 0.81%   |
| Aquantia                          | 1        | 0.81%   |
| Apple                             | 1        | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 43       | 33.33%  |
| Intel 82579V Gigabit Network Connection                                    | 7        | 5.43%   |
| Realtek RTL8125 2.5GbE Controller                                          | 6        | 4.65%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 3.1%    |
| Intel Ethernet Connection (11) I219-V                                      | 4        | 3.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 4        | 3.1%    |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3        | 2.33%   |
| Intel Ethernet Connection (7) I219-V                                       | 3        | 2.33%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 2.33%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 3        | 2.33%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 3        | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2        | 1.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 2        | 1.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2        | 1.55%   |
| Intel I350 Gigabit Fiber Network Connection                                | 2        | 1.55%   |
| Intel Ethernet Controller I225-V                                           | 2        | 1.55%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.55%   |
| Intel Ethernet Connection I217-LM                                          | 2        | 1.55%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 1.55%   |
| Intel 82583V Gigabit Network Connection                                    | 2        | 1.55%   |
| Intel 82562V-2 10/100 Network Connection                                   | 2        | 1.55%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 1.55%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 1.55%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1        | 0.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 1        | 0.78%   |
| OPPO SDM720G-IDP _SN:B922E265                                              | 1        | 0.78%   |
| Nvidia MCP73 Ethernet                                                      | 1        | 0.78%   |
| Nvidia MCP61 Ethernet                                                      | 1        | 0.78%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.78%   |
| Intel Ethernet Connection (2) I218-LM                                      | 1        | 0.78%   |
| Intel 82578DM Gigabit Network Connection                                   | 1        | 0.78%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 1        | 0.78%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                    | 1        | 0.78%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]          | 1        | 0.78%   |
| Apple iPad 4/Mini1                                                         | 1        | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 106      | 57.92%  |
| WiFi     | 76       | 41.53%  |
| Modem    | 1        | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 51.28%  |
| WiFi     | 57       | 48.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 70       | 58.82%  |
| 2     | 31       | 26.05%  |
| 0     | 11       | 9.24%   |
| 3     | 5        | 4.2%    |
| 9     | 1        | 0.84%   |
| 8     | 1        | 0.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 95       | 79.17%  |
| Yes  | 25       | 20.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 18       | 47.37%  |
| Intel                   | 10       | 26.32%  |
| Realtek Semiconductor   | 2        | 5.26%   |
| Broadcom                | 2        | 5.26%   |
| Apple                   | 2        | 5.26%   |
| TP-Link                 | 1        | 2.63%   |
| IMC Networks            | 1        | 2.63%   |
| Foxconn / Hon Hai       | 1        | 2.63%   |
| D-Link                  | 1        | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18       | 47.37%  |
| Intel AX201 Bluetooth                               | 6        | 15.79%  |
| Realtek Bluetooth Radio                             | 2        | 5.26%   |
| Apple Bluetooth USB Host Controller                 | 2        | 5.26%   |
| TP-Link TP-hink UB500 Adapter                       | 1        | 2.63%   |
| Intel Bluetooth wireless interface                  | 1        | 2.63%   |
| Intel Bluetooth Device                              | 1        | 2.63%   |
| Intel AX210 Bluetooth                               | 1        | 2.63%   |
| Intel AX200 Bluetooth                               | 1        | 2.63%   |
| IMC Networks Bluetooth Radio                        | 1        | 2.63%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1        | 2.63%   |
| D-Link DBT-122 Bluetooth adapter                    | 1        | 2.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 2.63%   |
| Broadcom BCM20702A0                                 | 1        | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 88       | 44.9%   |
| Nvidia                      | 49       | 25%     |
| AMD                         | 37       | 18.88%  |
| Logitech                    | 6        | 3.06%   |
| C-Media Electronics         | 5        | 2.55%   |
| JMTek                       | 3        | 1.53%   |
| Unknown                     | 1        | 0.51%   |
| Texas Instruments           | 1        | 0.51%   |
| RODE Microphones            | 1        | 0.51%   |
| GN Netcom                   | 1        | 0.51%   |
| FiiO Electronics Technology | 1        | 0.51%   |
| Creative Labs               | 1        | 0.51%   |
| Cooler Master               | 1        | 0.51%   |
| ASUSTek Computer            | 1        | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 14       | 6.51%   |
| Nvidia GF108 High Definition Audio Controller                                     | 12       | 5.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 12       | 5.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 12       | 5.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 3.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 8        | 3.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7        | 3.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7        | 3.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7        | 3.26%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 2.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 5        | 2.33%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5        | 2.33%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 1.86%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4        | 1.86%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 1.86%   |
| Nvidia High Definition Audio Controller                                           | 3        | 1.4%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 1.4%    |
| Nvidia GK107 HDMI Audio Controller                                                | 3        | 1.4%    |
| Logitech H600 [Wireless Headset]                                                  | 3        | 1.4%    |
| JMTek USB PnP Audio Device                                                        | 3        | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 1.4%    |
| Intel Alder Lake-S HD Audio Controller                                            | 3        | 1.4%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 1.4%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 3        | 1.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 0.93%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 0.93%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 0.93%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 0.93%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 0.93%   |
| Logitech USB Headset H540                                                         | 2        | 0.93%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 0.93%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 0.93%   |
| Intel Audio device                                                                | 2        | 0.93%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 0.93%   |
| C-Media Electronics Thronmax MDrill One                                           | 2        | 0.93%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 0.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 0.93%   |
| AMD FCH Azalia Controller                                                         | 2        | 0.93%   |
| AMD Bonaire HDMI Audio                                                            | 2        | 0.93%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 0.93%   |
| Unknown Realtek USB Audio Rear                                                    | 1        | 0.47%   |
| Unknown Realtek USB Audio Front                                                   | 1        | 0.47%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1        | 0.47%   |
| RODE Microphones RODE NT-USB Mini                                                 | 1        | 0.47%   |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 0.47%   |
| Nvidia MCP73 High Definition Audio                                                | 1        | 0.47%   |
| Nvidia MCP55 High Definition Audio                                                | 1        | 0.47%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.47%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1        | 0.47%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1        | 0.47%   |
| Logitech Z205                                                                     | 1        | 0.47%   |
| Intel USB PnP Sound Device                                                        | 1        | 0.47%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 1        | 0.47%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1        | 0.47%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 0.47%   |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 1        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 23       | 39.66%  |
| Unknown             | 7        | 12.07%  |
| Corsair             | 7        | 12.07%  |
| SK hynix            | 6        | 10.34%  |
| Kingmax             | 3        | 5.17%   |
| Micron Technology   | 2        | 3.45%   |
| Kimtigo             | 2        | 3.45%   |
| Team                | 1        | 1.72%   |
| Silicon Power       | 1        | 1.72%   |
| SemsoTai            | 1        | 1.72%   |
| Samsung Electronics | 1        | 1.72%   |
| PNY                 | 1        | 1.72%   |
| Kinlstuo            | 1        | 1.72%   |
| G.Skill             | 1        | 1.72%   |
| A-DATA Technology   | 1        | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s       | 4        | 5.97%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 3        | 4.48%   |
| Unknown RAM Module 4GB DIMM SDRAM                           | 2        | 2.99%   |
| Kingmax RAM FLFE85F-C8KL9 2GB DIMM DDR3 1333MT/s            | 2        | 2.99%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s              | 2        | 2.99%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                   | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM 667MT/s                         | 1        | 1.49%   |
| Team RAM Elite-800 2048MB DIMM SDRAM 2048MT/s               | 1        | 1.49%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s               | 1        | 1.49%   |
| SK hynix RAM HYMP112F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s | 1        | 1.49%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1        | 1.49%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s        | 1        | 1.49%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s     | 1        | 1.49%   |
| SK hynix RAM HMA84GR7CJR4N-XN 32GB DIMM DDR4 3200MT/s       | 1        | 1.49%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s        | 1        | 1.49%   |
| Silicon Power RAM DBLT2GN568S 2048MB DIMM DDR3 1333MT/s     | 1        | 1.49%   |
| SemsoTai RAM Module 8GB DIMM DDR4 2667MT/s                  | 1        | 1.49%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s              | 1        | 1.49%   |
| PNY RAM 8GBF1X08LFHH35-12-K 8GB DIMM DDR4 2667MT/s          | 1        | 1.49%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Micron RAM 18JSF25672AZ 2048MB DIMM DDR3 1066MT/s           | 1        | 1.49%   |
| Kinlstuo RAM Module 8192MB DIMM DDR3 1600MT/s               | 1        | 1.49%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                   | 1        | 1.49%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                | 1        | 1.49%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s        | 1        | 1.49%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s         | 1        | 1.49%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s         | 1        | 1.49%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s         | 1        | 1.49%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s       | 1        | 1.49%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 1        | 1.49%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s       | 1        | 1.49%   |
| Kingston RAM 99U5474-041.A00LF 4GB DIMM DDR3 1333MT/s       | 1        | 1.49%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1600MT/s       | 1        | 1.49%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s       | 1        | 1.49%   |
| Kingston RAM 99U5471-036.A00LF 8GB DIMM DDR3 1600MT/s       | 1        | 1.49%   |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s    | 1        | 1.49%   |
| Kingston RAM 99U5428-082.A00LF 8GB SODIMM DDR3 1600MT/s     | 1        | 1.49%   |
| Kingston RAM 99P5471-043.A00LF 8GB DIMM DDR3 1600MT/s       | 1        | 1.49%   |
| Kingston RAM 99P5471-004.A01LF 4GB DIMM DDR3 1333MT/s       | 1        | 1.49%   |
| Kingston RAM 99P5471-004.A01L12 4096MB DIMM DDR3 1333MT/s   | 1        | 1.49%   |
| Kingston RAM 9965525-005.A 2048MB DIMM DDR3 1066MT/s        | 1        | 1.49%   |
| Kingston RAM 9965432-033.A 2048MB DIMM DDR3 1066MT/s        | 1        | 1.49%   |
| Kingston RAM 9905702-120.A00G 8GB DIMM DDR4 2667MT/s        | 1        | 1.49%   |
| Kingston RAM 9905702-082.B00G 8GB DIMM DDR4 2667MT/s        | 1        | 1.49%   |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s        | 1        | 1.49%   |
| Kingston RAM 9905678-173.A00G 8192MB DIMM DDR4 2400MT/s     | 1        | 1.49%   |
| Kingston RAM 9905316-173.A00LF 2048MB DIMM DDR2 800MT/s     | 1        | 1.49%   |
| Kingmax RAM KLDE88F-B8KY6 2048MB DIMM DDR 800MT/s           | 1        | 1.49%   |
| Kingmax RAM FLFE85F-C8KM9 2048MB DIMM 1333MT/s              | 1        | 1.49%   |
| G.Skill RAM F4-2400C15-8GFT 8192MB DIMM DDR4 2400MT/s       | 1        | 1.49%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s         | 1        | 1.49%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s    | 1        | 1.49%   |
| Corsair RAM CMY8GX3M2A1866C9 4GB DIMM DDR3 1867MT/s         | 1        | 1.49%   |
| Corsair RAM CMK32GX4M1D3000C16 32GB DIMM DDR4 3000MT/s      | 1        | 1.49%   |
| Corsair RAM CMK16GX4M2Z3200C16 8192MB DIMM DDR4 3200MT/s    | 1        | 1.49%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s       | 1        | 1.49%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 1        | 1.49%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                 | 1        | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 25       | 44.64%  |
| DDR4    | 19       | 33.93%  |
| SDRAM   | 6        | 10.71%  |
| DDR2    | 4        | 7.14%   |
| Unknown | 2        | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 51       | 92.73%  |
| SODIMM  | 3        | 5.45%   |
| FB-DIMM | 1        | 1.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 24       | 42.11%  |
| 2048  | 15       | 26.32%  |
| 4096  | 10       | 17.54%  |
| 32768 | 4        | 7.02%   |
| 16384 | 3        | 5.26%   |
| 1024  | 1        | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 15       | 25.86%  |
| 3200    | 6        | 10.34%  |
| 1333    | 6        | 10.34%  |
| 2667    | 4        | 6.9%    |
| Unknown | 4        | 6.9%    |
| 3600    | 3        | 5.17%   |
| 2400    | 3        | 5.17%   |
| 800     | 3        | 5.17%   |
| 667     | 3        | 5.17%   |
| 1066    | 2        | 3.45%   |
| 3400    | 1        | 1.72%   |
| 3000    | 1        | 1.72%   |
| 2933    | 1        | 1.72%   |
| 2133    | 1        | 1.72%   |
| 2048    | 1        | 1.72%   |
| 1867    | 1        | 1.72%   |
| 1866    | 1        | 1.72%   |
| 1800    | 1        | 1.72%   |
| 1067    | 1        | 1.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 28.57%  |
| Brother Industries  | 2        | 28.57%  |
| Seiko Epson         | 1        | 14.29%  |
| Prolific Technology | 1        | 14.29%  |
| Hewlett-Packard     | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung SCX-3400 Series       | 2        | 28.57%  |
| Seiko Epson L312 Series       | 1        | 14.29%  |
| Prolific PL2305 Parallel Port | 1        | 14.29%  |
| HP Ink Tank 110 series        | 1        | 14.29%  |
| Brother DCP-J105              | 1        | 14.29%  |
| Brother DCP-1610W             | 1        | 14.29%  |

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
| Logitech                      | 4        | 26.67%  |
| Generalplus Technology        | 3        | 20%     |
| Apple                         | 2        | 13.33%  |
| YGTek                         | 1        | 6.67%   |
| WCM_USB                       | 1        | 6.67%   |
| Sunplus Innovation Technology | 1        | 6.67%   |
| Realtek Semiconductor         | 1        | 6.67%   |
| Jieli Technology              | 1        | 6.67%   |
| ARC International             | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Generalplus 808 Camera                | 2        | 13.33%  |
| Apple iPhone 5/5C/5S/6/SE             | 2        | 13.33%  |
| YGTek Webcam                          | 1        | 6.67%   |
| WCM_USB WEB CAM                       | 1        | 6.67%   |
| Sunplus Full HD webcam                | 1        | 6.67%   |
| Realtek HP High Definition 1MP Webcam | 1        | 6.67%   |
| Logitech Webcam C310                  | 1        | 6.67%   |
| Logitech Webcam C170                  | 1        | 6.67%   |
| Logitech HD Webcam C510               | 1        | 6.67%   |
| Logitech HD Pro Webcam C920           | 1        | 6.67%   |
| Jieli USB PHY 2.0                     | 1        | 6.67%   |
| Generalplus WEB CAM                   | 1        | 6.67%   |
| ARC International Camera              | 1        | 6.67%   |

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
| 0     | 99       | 82.5%   |
| 1     | 19       | 15.83%  |
| 3     | 1        | 0.83%   |
| 2     | 1        | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 10       | 43.48%  |
| Graphics card            | 6        | 26.09%  |
| Communication controller | 3        | 13.04%  |
| Unassigned class         | 1        | 4.35%   |
| Storage/ide              | 1        | 4.35%   |
| Sound                    | 1        | 4.35%   |
| Network                  | 1        | 4.35%   |

