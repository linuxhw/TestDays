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

Total: 246

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI      | MS-7388                     | [6d3a406400](https://linux-hardware.org/?probe=6d3a406400) | Jun 10, 2023 |
| MSI      | MS-7388                     | [fc12ac6b90](https://linux-hardware.org/?probe=fc12ac6b90) | Jun 02, 2023 |
| ASUSTek  | H81M-K                      | [f65eac842b](https://linux-hardware.org/?probe=f65eac842b) | May 23, 2023 |
| Gigabyte | H410M S2 V2                 | [9d2439e8d7](https://linux-hardware.org/?probe=9d2439e8d7) | May 18, 2023 |
| Gigabyte | B450 AORUS ELITE            | [7957c81218](https://linux-hardware.org/?probe=7957c81218) | May 17, 2023 |
| Gigabyte | B450 AORUS ELITE            | [1aedc7da48](https://linux-hardware.org/?probe=1aedc7da48) | May 17, 2023 |
| MSI      | MS-7388                     | [948e1d2358](https://linux-hardware.org/?probe=948e1d2358) | May 03, 2023 |
| MSI      | MS-7388                     | [ec819aca80](https://linux-hardware.org/?probe=ec819aca80) | May 01, 2023 |
| Gigabyte | Z77M-D3H                    | [6da1ddcef5](https://linux-hardware.org/?probe=6da1ddcef5) | May 01, 2023 |
| Gigabyte | Z77M-D3H                    | [a3d2b3dcd3](https://linux-hardware.org/?probe=a3d2b3dcd3) | Apr 30, 2023 |
| Gigabyte | Z77M-D3H                    | [915147a191](https://linux-hardware.org/?probe=915147a191) | Apr 25, 2023 |
| Gigabyte | Z77M-D3H                    | [92a968e58d](https://linux-hardware.org/?probe=92a968e58d) | Apr 25, 2023 |
| Dell     | 0F373D A00                  | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Acer     | Aspire XC-710 V:1.1         | [a09ea158cc](https://linux-hardware.org/?probe=a09ea158cc) | Apr 20, 2023 |
| ASRock   | B550 Pro4                   | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| MSI      | MS-7388                     | [4efa2b04da](https://linux-hardware.org/?probe=4efa2b04da) | Apr 14, 2023 |
| Gigabyte | B550 AORUS PRO V2           | [f4cbe67033](https://linux-hardware.org/?probe=f4cbe67033) | Apr 14, 2023 |
| Gigabyte | Z77M-D3H                    | [ffdcd55e2e](https://linux-hardware.org/?probe=ffdcd55e2e) | Apr 13, 2023 |
| MSI      | MS-7388                     | [d7f892b3e2](https://linux-hardware.org/?probe=d7f892b3e2) | Apr 12, 2023 |
| Gigabyte | Z77M-D3H                    | [d76bd92923](https://linux-hardware.org/?probe=d76bd92923) | Apr 07, 2023 |
| MSI      | B450M-A PRO MAX             | [54789b15f3](https://linux-hardware.org/?probe=54789b15f3) | Mar 29, 2023 |
| ASUSTek  | Pro WS WRX80E-SAGE SE WI... | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| Biostar  | G41D3+                      | [ebb9a17568](https://linux-hardware.org/?probe=ebb9a17568) | Mar 23, 2023 |
| Gigabyte | GA-890GPA-UD3H              | [b54b641b36](https://linux-hardware.org/?probe=b54b641b36) | Mar 14, 2023 |
| ASUSTek  | Pro WS WRX80E-SAGE SE WI... | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek  | Pro WS WRX80E-SAGE SE WI... | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte | X570 UD                     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| Dell     | 084J0R A00                  | [dcde5e81ed](https://linux-hardware.org/?probe=dcde5e81ed) | Mar 04, 2023 |
| Intel    | DH61WW AAG23116-204         | [c9b32e7136](https://linux-hardware.org/?probe=c9b32e7136) | Mar 03, 2023 |
| Unknown  | J3160-4L                    | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| MSI      | A320M GRENADE               | [1a5ffd0fc4](https://linux-hardware.org/?probe=1a5ffd0fc4) | Mar 01, 2023 |
| Gigabyte | H370 AORUS GAMING 3-CF      | [59d082bd5f](https://linux-hardware.org/?probe=59d082bd5f) | Feb 26, 2023 |
| Gigabyte | B550 AORUS PRO V2           | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRock   | B550 Pro4                   | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| ASUSTek  | B85M-G                      | [c803a7f9e8](https://linux-hardware.org/?probe=c803a7f9e8) | Feb 15, 2023 |
| ASUSTek  | B85M-G                      | [3a660768c0](https://linux-hardware.org/?probe=3a660768c0) | Feb 15, 2023 |
| Dell     | 0MGK50 A02                  | [43bd1ca5e1](https://linux-hardware.org/?probe=43bd1ca5e1) | Feb 15, 2023 |
| Gigabyte | B550 AORUS PRO V2           | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek  | Pro WS WRX80E-SAGE SE WI... | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASUSTek  | Pro WS WRX80E-SAGE SE WI... | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| Gigabyte | X570 UD                     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| MSI      | 970A-G46                    | [6012e644eb](https://linux-hardware.org/?probe=6012e644eb) | Feb 13, 2023 |
| HP       | 18E4                        | [55972b87dd](https://linux-hardware.org/?probe=55972b87dd) | Feb 11, 2023 |
| Gigabyte | B560M AORUS ELITE           | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| Gigabyte | B85M-D3H                    | [903e8715e4](https://linux-hardware.org/?probe=903e8715e4) | Feb 03, 2023 |
| Gigabyte | B85M-D3H                    | [6013489300](https://linux-hardware.org/?probe=6013489300) | Feb 03, 2023 |
| Gigabyte | GA-890GPA-UD3H              | [e660f922a4](https://linux-hardware.org/?probe=e660f922a4) | Jan 27, 2023 |
| ASUSTek  | H81M-K                      | [cb932accdb](https://linux-hardware.org/?probe=cb932accdb) | Jan 24, 2023 |
| HP       | 2B2C                        | [1a74d92aaf](https://linux-hardware.org/?probe=1a74d92aaf) | Jan 08, 2023 |
| ASRock   | A320M-DVS R4.0              | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| Gigabyte | B85M-D3H                    | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
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
| Ubuntu 20.04                 | 28       | 15.91%  |
| Debian 11                    | 10       | 5.68%   |
| Ubuntu 18.04                 | 9        | 5.11%   |
| Zorin 16                     | 8        | 4.55%   |
| OpenMandriva 4.3             | 7        | 3.98%   |
| OpenMandriva 23.03           | 7        | 3.98%   |
| OpenMandriva 4.2             | 6        | 3.41%   |
| Pop!_OS 20.04                | 5        | 2.84%   |
| OpenMandriva 4.50            | 5        | 2.84%   |
| Ubuntu 22.04                 | 4        | 2.27%   |
| Ubuntu 19.04                 | 4        | 2.27%   |
| Pop!_OS 22.04                | 4        | 2.27%   |
| OpenMandriva 23.01           | 4        | 2.27%   |
| ArcoLinux Rolling            | 4        | 2.27%   |
| Xubuntu 18.04                | 3        | 1.7%    |
| Linux Mint 19.3              | 3        | 1.7%    |
| Fedora 37                    | 3        | 1.7%    |
| Fedora 33                    | 3        | 1.7%    |
| Zorin 15                     | 2        | 1.14%   |
| Ubuntu 19.10                 | 2        | 1.14%   |
| Pop!_OS 21.04                | 2        | 1.14%   |
| Pop!_OS 20.10                | 2        | 1.14%   |
| Manjaro 21.2.6               | 2        | 1.14%   |
| Linux Mint 20.3              | 2        | 1.14%   |
| KDE neon 22.04               | 2        | 1.14%   |
| KDE neon 20.04               | 2        | 1.14%   |
| Fedora 34                    | 2        | 1.14%   |
| Arch                         | 2        | 1.14%   |
| Ubuntu MATE 20.04            | 1        | 0.57%   |
| Ubuntu 23.04                 | 1        | 0.57%   |
| Ubuntu 21.10                 | 1        | 0.57%   |
| Ubuntu 21.04                 | 1        | 0.57%   |
| Ubuntu 20.10                 | 1        | 0.57%   |
| SteamOS 3.4                  | 1        | 0.57%   |
| ROSA R10                     | 1        | 0.57%   |
| Pop!_OS 21.10                | 1        | 0.57%   |
| openSUSE Tumbleweed-XXXXXXXX | 1        | 0.57%   |
| Manjaro 21.1.1               | 1        | 0.57%   |
| Manjaro 21.0.5               | 1        | 0.57%   |
| Manjaro                      | 1        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 48       | 28.92%  |
| OpenMandriva | 26       | 15.66%  |
| Pop!_OS      | 12       | 7.23%   |
| Debian       | 11       | 6.63%   |
| Zorin        | 10       | 6.02%   |
| Linux Mint   | 10       | 6.02%   |
| Fedora       | 10       | 6.02%   |
| Manjaro      | 5        | 3.01%   |
| KDE neon     | 4        | 2.41%   |
| ArcoLinux    | 4        | 2.41%   |
| Xubuntu      | 3        | 1.81%   |
| Lubuntu      | 3        | 1.81%   |
| Endless      | 3        | 1.81%   |
| Elementary   | 3        | 1.81%   |
| Kubuntu      | 2        | 1.2%    |
| Kali         | 2        | 1.2%    |
| Arch         | 2        | 1.2%    |
| Ubuntu MATE  | 1        | 0.6%    |
| SteamOS      | 1        | 0.6%    |
| ROSA         | 1        | 0.6%    |
| openSUSE     | 1        | 0.6%    |
| Linux Lite   | 1        | 0.6%    |
| Gentoo       | 1        | 0.6%    |
| EndeavourOS  | 1        | 0.6%    |
| CentOS       | 1        | 0.6%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.2.6-desktop-1omv2390        | 8        | 4.15%   |
| 5.10.14-desktop-1omv4002      | 6        | 3.11%   |
| 5.4.0-58-generic              | 5        | 2.59%   |
| 5.16.7-desktop-1omv4003       | 5        | 2.59%   |
| 5.13.19-6-pve                 | 5        | 2.59%   |
| 5.4.0-42-generic              | 4        | 2.07%   |
| 5.4.0-40-generic              | 3        | 1.55%   |
| 5.3.0-53-generic              | 3        | 1.55%   |
| 5.3.0-46-generic              | 3        | 1.55%   |
| 5.16.3-desktop-2omv4050       | 3        | 1.55%   |
| 5.15.0-52-generic             | 3        | 1.55%   |
| 5.11.0-27-generic             | 3        | 1.55%   |
| 6.0.12-76060006-generic       | 2        | 1.04%   |
| 5.8.0-53-generic              | 2        | 1.04%   |
| 5.8.0-44-generic              | 2        | 1.04%   |
| 5.8.0-41-generic              | 2        | 1.04%   |
| 5.4.0-77-generic              | 2        | 1.04%   |
| 5.4.0-7634-generic            | 2        | 1.04%   |
| 5.4.0-48-generic              | 2        | 1.04%   |
| 5.4.0-37-generic              | 2        | 1.04%   |
| 5.4.0-29-generic              | 2        | 1.04%   |
| 5.19.0-32-generic             | 2        | 1.04%   |
| 5.15.35-3-pve                 | 2        | 1.04%   |
| 5.15.0-58-generic             | 2        | 1.04%   |
| 5.15.0-39-generic             | 2        | 1.04%   |
| 5.12.7-desktop-clang-1omv4003 | 2        | 1.04%   |
| 5.12.4-desktop-1omv4050       | 2        | 1.04%   |
| 5.12.15-300.fc34.x86_64       | 2        | 1.04%   |
| 5.11.0-41-generic             | 2        | 1.04%   |
| 5.11.0-35-generic             | 2        | 1.04%   |
| 5.11.0-34-generic             | 2        | 1.04%   |
| 5.0.0-27-generic              | 2        | 1.04%   |
| 6.3.4-201.fc38.x86_64         | 1        | 0.52%   |
| 6.3.2-arch1-1                 | 1        | 0.52%   |
| 6.2.6-76060206-generic        | 1        | 0.52%   |
| 6.2.13-300.fc38.x86_64        | 1        | 0.52%   |
| 6.2.10-300.fc38.x86_64        | 1        | 0.52%   |
| 6.2.1-cb1.0.fc37.x86_64       | 1        | 0.52%   |
| 6.1.4-desktop-1omv2301        | 1        | 0.52%   |
| 6.1.1-desktop-1omv2290        | 1        | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 17.68%  |
| 5.15.0  | 13       | 7.18%   |
| 5.11.0  | 12       | 6.63%   |
| 5.8.0   | 11       | 6.08%   |
| 6.2.6   | 9        | 4.97%   |
| 5.3.0   | 8        | 4.42%   |
| 5.0.0   | 7        | 3.87%   |
| 5.10.14 | 6        | 3.31%   |
| 4.15.0  | 6        | 3.31%   |
| 5.16.7  | 5        | 2.76%   |
| 5.13.19 | 5        | 2.76%   |
| 5.13.0  | 5        | 2.76%   |
| 5.19.0  | 4        | 2.21%   |
| 5.16.3  | 3        | 1.66%   |
| 6.0.12  | 2        | 1.1%    |
| 5.18.0  | 2        | 1.1%    |
| 5.17.1  | 2        | 1.1%    |
| 5.15.35 | 2        | 1.1%    |
| 5.12.7  | 2        | 1.1%    |
| 5.12.4  | 2        | 1.1%    |
| 5.12.15 | 2        | 1.1%    |
| 5.10.0  | 2        | 1.1%    |
| 4.18.0  | 2        | 1.1%    |
| 6.3.4   | 1        | 0.55%   |
| 6.3.2   | 1        | 0.55%   |
| 6.2.13  | 1        | 0.55%   |
| 6.2.10  | 1        | 0.55%   |
| 6.2.1   | 1        | 0.55%   |
| 6.1.4   | 1        | 0.55%   |
| 6.1.1   | 1        | 0.55%   |
| 6.1.0   | 1        | 0.55%   |
| 6.0.3   | 1        | 0.55%   |
| 6.0.19  | 1        | 0.55%   |
| 6.0.15  | 1        | 0.55%   |
| 5.9.8   | 1        | 0.55%   |
| 5.9.14  | 1        | 0.55%   |
| 5.9.1   | 1        | 0.55%   |
| 5.19.9  | 1        | 0.55%   |
| 5.19.12 | 1        | 0.55%   |
| 5.18.7  | 1        | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 17.88%  |
| 5.15    | 23       | 12.85%  |
| 5.11    | 13       | 7.26%   |
| 6.2     | 11       | 6.15%   |
| 5.8     | 11       | 6.15%   |
| 5.13    | 11       | 6.15%   |
| 5.16    | 10       | 5.59%   |
| 5.10    | 9        | 5.03%   |
| 5.3     | 8        | 4.47%   |
| 5.0     | 7        | 3.91%   |
| 5.19    | 6        | 3.35%   |
| 5.12    | 6        | 3.35%   |
| 4.15    | 6        | 3.35%   |
| 6.0     | 5        | 2.79%   |
| 5.18    | 4        | 2.23%   |
| 6.1     | 3        | 1.68%   |
| 5.9     | 3        | 1.68%   |
| 5.17    | 3        | 1.68%   |
| 5.14    | 3        | 1.68%   |
| 6.3     | 2        | 1.12%   |
| 4.18    | 2        | 1.12%   |
| 4.9     | 1        | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 158      | 98.75%  |
| i686   | 2        | 1.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 67       | 40.36%  |
| KDE5       | 39       | 23.49%  |
| Unknown    | 14       | 8.43%   |
| XFCE       | 12       | 7.23%   |
| Openbox    | 9        | 5.42%   |
| X-Cinnamon | 8        | 4.82%   |
| MATE       | 6        | 3.61%   |
| Pantheon   | 3        | 1.81%   |
| LXQt       | 3        | 1.81%   |
| KDE        | 3        | 1.81%   |
| LXDE       | 1        | 0.6%    |
| Cinnamon   | 1        | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 137      | 83.54%  |
| Wayland | 12       | 7.32%   |
| Tty     | 8        | 4.88%   |
| Unknown | 7        | 4.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 86       | 52.44%  |
| SDDM    | 39       | 23.78%  |
| LightDM | 17       | 10.37%  |
| GDM3    | 9        | 5.49%   |
| GDM     | 9        | 5.49%   |
| TDM     | 3        | 1.83%   |
| LXDM    | 1        | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 125      | 76.22%  |
| en_GB   | 13       | 7.93%   |
| Unknown | 10       | 6.1%    |
| en_SG   | 8        | 4.88%   |
| en_AU   | 3        | 1.83%   |
| zh_SG   | 1        | 0.61%   |
| zh_CN   | 1        | 0.61%   |
| en_MY   | 1        | 0.61%   |
| en_HK   | 1        | 0.61%   |
| de_DE   | 1        | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 106      | 65.03%  |
| EFI  | 57       | 34.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 119      | 73.01%  |
| Overlay | 16       | 9.82%   |
| Btrfs   | 11       | 6.75%   |
| Zfs     | 8        | 4.91%   |
| Unknown | 4        | 2.45%   |
| Xfs     | 3        | 1.84%   |
| Ext3    | 1        | 0.61%   |
| Ext2    | 1        | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 87       | 53.7%   |
| GPT     | 51       | 31.48%  |
| MBR     | 24       | 14.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 74.25%  |
| Yes       | 43       | 25.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 61.59%  |
| Yes       | 63       | 38.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 36       | 22.5%   |
| ASUSTek Computer    | 35       | 21.88%  |
| Dell                | 19       | 11.88%  |
| MSI                 | 18       | 11.25%  |
| Intel               | 14       | 8.75%   |
| Hewlett-Packard     | 8        | 5%      |
| Lenovo              | 6        | 3.75%   |
| ASRock              | 6        | 3.75%   |
| Biostar             | 5        | 3.13%   |
| Acer                | 5        | 3.13%   |
| ECS                 | 2        | 1.25%   |
| Vorke               | 1        | 0.63%   |
| Shuttle             | 1        | 0.63%   |
| Seco                | 1        | 0.63%   |
| ONDA                | 1        | 0.63%   |
| AMI                 | 1        | 0.63%   |
| Unknown             | 1        | 0.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 8        | 5%      |
| Intel DH61WW AAG23116-204           | 7        | 4.38%   |
| Gigabyte Z77M-D3H                   | 6        | 3.75%   |
| Gigabyte B85M-D3H                   | 5        | 3.13%   |
| MSI MS-7C52                         | 4        | 2.5%    |
| MSI MS-7817                         | 3        | 1.88%   |
| Intel DH61WW AAG23116-300           | 3        | 1.88%   |
| Dell OptiPlex 755                   | 3        | 1.88%   |
| MSI MS-7C81                         | 2        | 1.25%   |
| MSI MS-7B89                         | 2        | 1.25%   |
| Intel MAHOBAY                       | 2        | 1.25%   |
| Gigabyte X570 UD                    | 2        | 1.25%   |
| Gigabyte B450M S2H                  | 2        | 1.25%   |
| Dell XPS 8940                       | 2        | 1.25%   |
| Dell OptiPlex 990                   | 2        | 1.25%   |
| Biostar G41D3C                      | 2        | 1.25%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI     | 2        | 1.25%   |
| ASUS P8Z77-V LX                     | 2        | 1.25%   |
| Vorke V1 Plus                       | 1        | 0.63%   |
| Shuttle DH170                       | 1        | 0.63%   |
| Seco C40                            | 1        | 0.63%   |
| ONDA H110-MINI V3.00                | 1        | 0.63%   |
| MSI MS-7D42                         | 1        | 0.63%   |
| MSI MS-7C37                         | 1        | 0.63%   |
| MSI MS-7C02                         | 1        | 0.63%   |
| MSI MS-7A39                         | 1        | 0.63%   |
| MSI MS-7979                         | 1        | 0.63%   |
| MSI MS-7693                         | 1        | 0.63%   |
| MSI MS-7388                         | 1        | 0.63%   |
| Lenovo ThinkStation S10 6483CTO     | 1        | 0.63%   |
| Lenovo ThinkStation P620 30E0S0E000 | 1        | 0.63%   |
| Lenovo ThinkStation P500 30A6S1B50X | 1        | 0.63%   |
| Lenovo ThinkCentre M72e 32673M3     | 1        | 0.63%   |
| Lenovo ThinkCentre M700 10GQCTO1WW  | 1        | 0.63%   |
| Lenovo ThinkCentre M58 7359DHJ      | 1        | 0.63%   |
| Intel DH77KC AAG39641-400           | 1        | 0.63%   |
| Intel B75                           | 1        | 0.63%   |
| HP ProDesk 600 G1 TWR               | 1        | 0.63%   |
| HP EliteDesk 800 G1 TWR             | 1        | 0.63%   |
| HP Compaq dc7800p Small Form Factor | 1        | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Intel DH61WW        | 10       | 6.25%   |
| Dell OptiPlex       | 10       | 6.25%   |
| ASUS All            | 8        | 5%      |
| Gigabyte Z77M-D3H   | 6        | 3.75%   |
| Gigabyte B85M-D3H   | 5        | 3.13%   |
| MSI MS-7C52         | 4        | 2.5%    |
| HP Compaq           | 4        | 2.5%    |
| Gigabyte X570       | 4        | 2.5%    |
| Dell Precision      | 4        | 2.5%    |
| MSI MS-7817         | 3        | 1.88%   |
| Lenovo ThinkStation | 3        | 1.88%   |
| Lenovo ThinkCentre  | 3        | 1.88%   |
| Gigabyte B450M      | 3        | 1.88%   |
| Dell Inspiron       | 3        | 1.88%   |
| ASUS TUF            | 3        | 1.88%   |
| ASUS P8B75-M        | 3        | 1.88%   |
| Acer Aspire         | 3        | 1.88%   |
| MSI MS-7C81         | 2        | 1.25%   |
| MSI MS-7B89         | 2        | 1.25%   |
| Intel MAHOBAY       | 2        | 1.25%   |
| Dell XPS            | 2        | 1.25%   |
| Biostar G41D3C      | 2        | 1.25%   |
| ASUS ROG            | 2        | 1.25%   |
| ASUS Pro            | 2        | 1.25%   |
| ASUS PRIME          | 2        | 1.25%   |
| ASUS P8Z77-V        | 2        | 1.25%   |
| Acer Veriton        | 2        | 1.25%   |
| Vorke V1            | 1        | 0.63%   |
| Shuttle DH170       | 1        | 0.63%   |
| Seco C40            | 1        | 0.63%   |
| ONDA H110-MINI      | 1        | 0.63%   |
| MSI MS-7D42         | 1        | 0.63%   |
| MSI MS-7C37         | 1        | 0.63%   |
| MSI MS-7C02         | 1        | 0.63%   |
| MSI MS-7A39         | 1        | 0.63%   |
| MSI MS-7979         | 1        | 0.63%   |
| MSI MS-7693         | 1        | 0.63%   |
| MSI MS-7388         | 1        | 0.63%   |
| Intel DH77KC        | 1        | 0.63%   |
| Intel B75           | 1        | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 23       | 14.38%  |
| 2013 | 19       | 11.88%  |
| 2018 | 17       | 10.63%  |
| 2019 | 13       | 8.13%   |
| 2011 | 12       | 7.5%    |
| 2020 | 10       | 6.25%   |
| 2015 | 10       | 6.25%   |
| 2021 | 9        | 5.63%   |
| 2017 | 9        | 5.63%   |
| 2008 | 9        | 5.63%   |
| 2007 | 8        | 5%      |
| 2010 | 7        | 4.38%   |
| 2009 | 6        | 3.75%   |
| 2014 | 5        | 3.13%   |
| 2022 | 2        | 1.25%   |
| 2006 | 1        | 0.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 160      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 156      | 97.5%   |
| Enabled  | 4        | 2.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 160      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 46       | 28.22%  |
| 8.01-16.0   | 30       | 18.4%   |
| 4.01-8.0    | 28       | 17.18%  |
| 3.01-4.0    | 20       | 12.27%  |
| 32.01-64.0  | 17       | 10.43%  |
| 64.01-256.0 | 9        | 5.52%   |
| 1.01-2.0    | 8        | 4.91%   |
| 24.01-32.0  | 3        | 1.84%   |
| 2.01-3.0    | 2        | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 58       | 31.69%  |
| 2.01-3.0    | 54       | 29.51%  |
| 3.01-4.0    | 27       | 14.75%  |
| 4.01-8.0    | 14       | 7.65%   |
| 0.51-1.0    | 12       | 6.56%   |
| 8.01-16.0   | 7        | 3.83%   |
| 32.01-64.0  | 4        | 2.19%   |
| 24.01-32.0  | 3        | 1.64%   |
| 0.01-0.5    | 2        | 1.09%   |
| 64.01-256.0 | 1        | 0.55%   |
| 16.01-24.0  | 1        | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 54       | 32.34%  |
| 2      | 47       | 28.14%  |
| 3      | 27       | 16.17%  |
| 4      | 16       | 9.58%   |
| 5      | 9        | 5.39%   |
| 7      | 6        | 3.59%   |
| 6      | 4        | 2.4%    |
| 8      | 3        | 1.8%    |
| 9      | 1        | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 107      | 66.05%  |
| Yes       | 55       | 33.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 146      | 91.25%  |
| No        | 14       | 8.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 102      | 62.58%  |
| No        | 61       | 37.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 107      | 66.46%  |
| Yes       | 54       | 33.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Malaysia | 160      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Kuala Lumpur           | 65       | 37.36%  |
| Petaling Jaya          | 19       | 10.92%  |
| George Town            | 8        | 4.6%    |
| Shah Alam              | 5        | 2.87%   |
| Kuching                | 5        | 2.87%   |
| Subang Jaya            | 4        | 2.3%    |
| Malacca                | 4        | 2.3%    |
| Kota Kinabalu          | 4        | 2.3%    |
| Kajang                 | 4        | 2.3%    |
| Sungai Buloh           | 3        | 1.72%   |
| Seremban               | 3        | 1.72%   |
| Puchong Batu Dua Belas | 3        | 1.72%   |
| Kulim                  | 3        | 1.72%   |
| Kota Bharu             | 3        | 1.72%   |
| Ipoh                   | 3        | 1.72%   |
| Butterworth            | 3        | 1.72%   |
| Bayan Lepas            | 3        | 1.72%   |
| Tawau                  | 2        | 1.15%   |
| Johor Bahru            | 2        | 1.15%   |
| Bukit Mertajam         | 2        | 1.15%   |
| Ampang                 | 2        | 1.15%   |
| Alor Star              | 2        | 1.15%   |
| Taman Senai            | 1        | 0.57%   |
| Taiping                | 1        | 0.57%   |
| Sungai Petani          | 1        | 0.57%   |
| Semenyih               | 1        | 0.57%   |
| Rawang                 | 1        | 0.57%   |
| Putrajaya              | 1        | 0.57%   |
| Penampang              | 1        | 0.57%   |
| Padang Serai           | 1        | 0.57%   |
| Muar town              | 1        | 0.57%   |
| Marabu                 | 1        | 0.57%   |
| Long Seridan           | 1        | 0.57%   |
| Labuan                 | 1        | 0.57%   |
| Kulai                  | 1        | 0.57%   |
| Kuantan                | 1        | 0.57%   |
| Klang                  | 1        | 0.57%   |
| Cukai                  | 1        | 0.57%   |
| Cheras                 | 1        | 0.57%   |
| Bukit Asahan           | 1        | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 72       | 137    | 22.15%  |
| Seagate                   | 70       | 125    | 21.54%  |
| Kingston                  | 31       | 46     | 9.54%   |
| Samsung Electronics       | 23       | 37     | 7.08%   |
| Toshiba                   | 16       | 18     | 4.92%   |
| PNY                       | 10       | 30     | 3.08%   |
| A-DATA Technology         | 10       | 18     | 3.08%   |
| Crucial                   | 8        | 14     | 2.46%   |
| SanDisk                   | 6        | 9      | 1.85%   |
| Intel                     | 6        | 10     | 1.85%   |
| Apacer                    | 6        | 11     | 1.85%   |
| Unknown                   | 5        | 6      | 1.54%   |
| Corsair                   | 4        | 12     | 1.23%   |
| Phison                    | 3        | 4      | 0.92%   |
| HGST                      | 3        | 3      | 0.92%   |
| China                     | 3        | 3      | 0.92%   |
| XPG                       | 2        | 3      | 0.62%   |
| TO Exter                  | 2        | 4      | 0.62%   |
| Silicon Motion            | 2        | 3      | 0.62%   |
| Plextor                   | 2        | 2      | 0.62%   |
| Phison Electronics        | 2        | 2      | 0.62%   |
| OCZ                       | 2        | 4      | 0.62%   |
| Micron Technology         | 2        | 6      | 0.62%   |
| KIOXIA-EXCERIA            | 2        | 4      | 0.62%   |
| Hitachi                   | 2        | 2      | 0.62%   |
| Hewlett-Packard           | 2        | 2      | 0.62%   |
| Gigabyte Technology       | 2        | 2      | 0.62%   |
| External                  | 2        | 2      | 0.62%   |
| ADATA Technology          | 2        | 2      | 0.62%   |
| Verbatim                  | 1        | 1      | 0.31%   |
| Transcend                 | 1        | 1      | 0.31%   |
| SPCC                      | 1        | 1      | 0.31%   |
| sk600                     | 1        | 1      | 0.31%   |
| SK hynix                  | 1        | 1      | 0.31%   |
| SATAFIRM                  | 1        | 1      | 0.31%   |
| Realtek                   | 1        | 1      | 0.31%   |
| Pioneer                   | 1        | 1      | 0.31%   |
| Micron/Crucial Technology | 1        | 1      | 0.31%   |
| Maxtor                    | 1        | 2      | 0.31%   |
| MAX                       | 1        | 2      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD    | 11       | 2.82%   |
| Seagate ST3500414CS 500GB          | 8        | 2.05%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 7        | 1.79%   |
| WDC WD2500AAKX-753CA1 250GB        | 7        | 1.79%   |
| Seagate ST2000DM008-2UB102 2TB     | 6        | 1.54%   |
| Seagate ST1000DM010-2EP102 1TB     | 6        | 1.54%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 5        | 1.28%   |
| WDC WD20EZRX-00D8PB0 2TB           | 5        | 1.28%   |
| Seagate ST380815AS 80GB            | 5        | 1.28%   |
| Samsung HD103SJ 1TB                | 5        | 1.28%   |
| PNY 1TB SATA SSD                   | 5        | 1.28%   |
| Toshiba MQ01ABD100 1TB             | 4        | 1.03%   |
| Seagate ST500DM002-1BD142 500GB    | 4        | 1.03%   |
| Seagate ST500DM002-1BC142 500GB    | 4        | 1.03%   |
| Seagate ST3160815AS 160GB          | 4        | 1.03%   |
| Kingston SA400S37480G 480GB SSD    | 4        | 1.03%   |
| Corsair Force MP510 240GB          | 4        | 1.03%   |
| A-DATA SU650 120GB SSD             | 4        | 1.03%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 3        | 0.77%   |
| WDC WD3200AAKS-00SBA0 320GB        | 3        | 0.77%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 3        | 0.77%   |
| Seagate ST3320418AS 320GB          | 3        | 0.77%   |
| Seagate ST2000DM006-2DM164 2TB     | 3        | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3        | 0.77%   |
| Seagate ST1000DM003-1ER162 1TB     | 3        | 0.77%   |
| Seagate ST1000DM003-1CH162 1TB     | 3        | 0.77%   |
| PNY CS900 1TB SSD                  | 3        | 0.77%   |
| Kingston SV300S37A120G 120GB SSD   | 3        | 0.77%   |
| Kingston NVMe SSD Drive 500GB      | 3        | 0.77%   |
| Crucial CT500MX500SSD1 500GB       | 3        | 0.77%   |
| A-DATA SX8200PNP 256GB             | 3        | 0.77%   |
| XPG NVMe SSD Drive 512GB           | 2        | 0.51%   |
| WDC WD800JD-22MSA1 80GB            | 2        | 0.51%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 2        | 0.51%   |
| WDC WD5000AAKX-001CA0 500GB        | 2        | 0.51%   |
| WDC WD5000AADS-00S9B0 500GB        | 2        | 0.51%   |
| WDC WD40EZRZ-00WN9B0 4TB           | 2        | 0.51%   |
| WDC WD360ADFD-00NLR1 37GB          | 2        | 0.51%   |
| WDC WD3200AAKS-00L9A0 320GB        | 2        | 0.51%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 2        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 70       | 135    | 40%     |
| Seagate             | 69       | 124    | 39.43%  |
| Toshiba             | 16       | 18     | 9.14%   |
| Samsung Electronics | 9        | 13     | 5.14%   |
| HGST                | 3        | 3      | 1.71%   |
| Hitachi             | 2        | 2      | 1.14%   |
| External            | 2        | 2      | 1.14%   |
| Unknown             | 1        | 1      | 0.57%   |
| Maxtor              | 1        | 2      | 0.57%   |
| JMicron Technology  | 1        | 1      | 0.57%   |
| Hewlett-Packard     | 1        | 1      | 0.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 26       | 37     | 26.26%  |
| PNY                 | 9        | 29     | 9.09%   |
| Samsung Electronics | 8        | 12     | 8.08%   |
| Crucial             | 8        | 14     | 8.08%   |
| Apacer              | 6        | 11     | 6.06%   |
| SanDisk             | 5        | 8      | 5.05%   |
| A-DATA Technology   | 5        | 5      | 5.05%   |
| Intel               | 4        | 7      | 4.04%   |
| China               | 3        | 3      | 3.03%   |
| TO Exter            | 2        | 4      | 2.02%   |
| Plextor             | 2        | 2      | 2.02%   |
| OCZ                 | 2        | 4      | 2.02%   |
| KIOXIA-EXCERIA      | 2        | 4      | 2.02%   |
| WDC                 | 1        | 1      | 1.01%   |
| Verbatim            | 1        | 1      | 1.01%   |
| Transcend           | 1        | 1      | 1.01%   |
| SPCC                | 1        | 1      | 1.01%   |
| sk600               | 1        | 1      | 1.01%   |
| SK hynix            | 1        | 1      | 1.01%   |
| Seagate             | 1        | 1      | 1.01%   |
| SATAFIRM            | 1        | 1      | 1.01%   |
| Pioneer             | 1        | 1      | 1.01%   |
| Micron Technology   | 1        | 5      | 1.01%   |
| LITEON              | 1        | 1      | 1.01%   |
| KimMiDi             | 1        | 1      | 1.01%   |
| Hikvision           | 1        | 2      | 1.01%   |
| Hewlett-Packard     | 1        | 1      | 1.01%   |
| FORESEE             | 1        | 1      | 1.01%   |
| Colorful            | 1        | 1      | 1.01%   |
| ASMT                | 1        | 2      | 1.01%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 131      | 302    | 50.78%  |
| SSD     | 83       | 163    | 32.17%  |
| NVMe    | 35       | 72     | 13.57%  |
| Unknown | 7        | 9      | 2.71%   |
| MMC     | 2        | 2      | 0.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 151      | 454    | 74.75%  |
| NVMe | 35       | 71     | 17.33%  |
| SAS  | 14       | 21     | 6.93%   |
| MMC  | 2        | 2      | 0.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 124      | 247    | 54.63%  |
| 0.51-1.0   | 66       | 136    | 29.07%  |
| 1.01-2.0   | 28       | 64     | 12.33%  |
| 3.01-4.0   | 6        | 14     | 2.64%   |
| 4.01-10.0  | 2        | 3      | 0.88%   |
| 2.01-3.0   | 1        | 1      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 44       | 26.04%  |
| 251-500        | 26       | 15.38%  |
| 501-1000       | 24       | 14.2%   |
| 1001-2000      | 18       | 10.65%  |
| 51-100         | 13       | 7.69%   |
| 1-20           | 12       | 7.1%    |
| More than 3000 | 9        | 5.33%   |
| 21-50          | 9        | 5.33%   |
| Unknown        | 9        | 5.33%   |
| 2001-3000      | 5        | 2.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 73       | 41.71%  |
| 51-100         | 21       | 12%     |
| 21-50          | 19       | 10.86%  |
| 101-250        | 18       | 10.29%  |
| 251-500        | 12       | 6.86%   |
| 501-1000       | 9        | 5.14%   |
| Unknown        | 9        | 5.14%   |
| More than 3000 | 6        | 3.43%   |
| 1001-2000      | 6        | 3.43%   |
| 2001-3000      | 2        | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB       | 7        | 7      | 30.43%  |
| Seagate ST3500414CS 500GB          | 2        | 3      | 8.7%    |
| WDC WD800AAJS-00PSA0 80GB          | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-753CA1 500GB        | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 1      | 4.35%   |
| WDC WD5000AADS-00S9B0 500GB        | 1        | 1      | 4.35%   |
| WDC WD10EZEX-60WN4A0 1TB           | 1        | 1      | 4.35%   |
| Toshiba MQ01ABD100 1TB             | 1        | 1      | 4.35%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 4.35%   |
| Seagate ST380211AS 80GB            | 1        | 1      | 4.35%   |
| Seagate ST3320620A 320GB           | 1        | 1      | 4.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 4.35%   |
| Samsung Electronics HM160HI 160GB  | 1        | 1      | 4.35%   |
| Kingston SV300S37A120G 120GB SSD   | 1        | 1      | 4.35%   |
| Hitachi HDS721050CLA362 500GB      | 1        | 1      | 4.35%   |
| Hewlett-Packard SSD S700 120GB     | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 54.55%  |
| Seagate             | 5        | 7      | 22.73%  |
| Toshiba             | 1        | 1      | 4.55%   |
| Samsung Electronics | 1        | 1      | 4.55%   |
| Kingston            | 1        | 1      | 4.55%   |
| Hitachi             | 1        | 1      | 4.55%   |
| Hewlett-Packard     | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 60%     |
| Seagate             | 5        | 7      | 25%     |
| Toshiba             | 1        | 1      | 5%      |
| Samsung Electronics | 1        | 1      | 5%      |
| Hitachi             | 1        | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 22     | 90.91%  |
| SSD  | 2        | 2      | 9.09%   |

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
| Detected | 100      | 324    | 53.76%  |
| Works    | 64       | 200    | 34.41%  |
| Malfunc  | 22       | 24     | 11.83%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 118      | 54.88%  |
| AMD                         | 37       | 17.21%  |
| Phison Electronics          | 12       | 5.58%   |
| Samsung Electronics         | 8        | 3.72%   |
| ASMedia Technology          | 7        | 3.26%   |
| ADATA Technology            | 7        | 3.26%   |
| Kingston Technology Company | 6        | 2.79%   |
| Nvidia                      | 4        | 1.86%   |
| Marvell Technology Group    | 4        | 1.86%   |
| JMicron Technology          | 4        | 1.86%   |
| Silicon Motion              | 2        | 0.93%   |
| SanDisk                     | 2        | 0.93%   |
| Silicon Image               | 1        | 0.47%   |
| Micron/Crucial Technology   | 1        | 0.47%   |
| Micron Technology           | 1        | 0.47%   |
| Lite-On IT Corp. / Plextor  | 1        | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 26       | 9.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 19       | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 14       | 4.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10       | 3.51%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 10       | 3.51%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 10       | 3.51%   |
| Intel SATA Controller [RAID mode]                                              | 9        | 3.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9        | 3.16%   |
| AMD 400 Series Chipset SATA Controller                                         | 9        | 3.16%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7        | 2.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7        | 2.46%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 7        | 2.46%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6        | 2.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 1.75%   |
| Phison PS5013 E13 NVMe Controller                                              | 5        | 1.75%   |
| Phison E12 NVMe Controller                                                     | 5        | 1.75%   |
| Intel 82Q35 Express PT IDER Controller                                         | 5        | 1.75%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 5        | 1.75%   |
| AMD FCH SATA Controller D                                                      | 5        | 1.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 1.4%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4        | 1.4%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 4        | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 1.05%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 1.05%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3        | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3        | 1.05%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 3        | 1.05%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 3        | 1.05%   |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 1.05%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 0.7%    |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.7%    |
| Nvidia MCP61 SATA Controller                                                   | 2        | 0.7%    |
| Nvidia MCP61 IDE                                                               | 2        | 0.7%    |
| Kingston Company NVMe Controller                                               | 2        | 0.7%    |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 0.7%    |
| Intel Comet Lake PCH-H RAID                                                    | 2        | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 2        | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 2        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 117      | 55.45%  |
| IDE  | 43       | 20.38%  |
| NVMe | 35       | 16.59%  |
| RAID | 16       | 7.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 120      | 75%     |
| AMD    | 40       | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium CPU G620 @ 2.60GHz            | 8        | 4.97%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 8        | 4.97%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 5        | 3.11%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 2.48%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 2.48%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 2.48%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 2.48%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 3        | 1.86%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.86%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 1.86%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 1.86%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 1.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.86%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 1.86%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 1.86%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 2        | 1.24%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 1.24%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.24%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.24%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.24%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.24%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.24%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.24%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.24%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 2        | 1.24%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.24%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.24%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 2        | 1.24%   |
| AMD Ryzen 5 5600 6-Core Processor           | 2        | 1.24%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.24%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.24%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 2        | 1.24%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz          | 1        | 0.62%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.62%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 0.62%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 0.62%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1        | 0.62%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.62%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.62%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 33       | 20.5%   |
| Intel Core i3           | 23       | 14.29%  |
| Intel Pentium           | 15       | 9.32%   |
| AMD Ryzen 5             | 15       | 9.32%   |
| Intel Core i7           | 13       | 8.07%   |
| Intel Core 2 Duo        | 12       | 7.45%   |
| Intel Xeon              | 7        | 4.35%   |
| Other                   | 6        | 3.73%   |
| Intel Core 2 Quad       | 5        | 3.11%   |
| AMD Ryzen 7             | 5        | 3.11%   |
| AMD Ryzen 3             | 4        | 2.48%   |
| AMD Ryzen Threadripper  | 3        | 1.86%   |
| AMD Ryzen 9             | 3        | 1.86%   |
| Intel Pentium Dual-Core | 2        | 1.24%   |
| Intel Celeron           | 2        | 1.24%   |
| AMD Athlon 64 X2        | 2        | 1.24%   |
| AMD A10                 | 2        | 1.24%   |
| Intel Pentium Dual      | 1        | 0.62%   |
| Intel Core i9           | 1        | 0.62%   |
| Intel Atom              | 1        | 0.62%   |
| AMD Ryzen Embedded      | 1        | 0.62%   |
| AMD Phenom II X6        | 1        | 0.62%   |
| AMD Phenom II X4        | 1        | 0.62%   |
| AMD FX                  | 1        | 0.62%   |
| AMD Athlon X2           | 1        | 0.62%   |
| AMD A6                  | 1        | 0.62%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 64       | 39.75%  |
| 2      | 56       | 34.78%  |
| 6      | 23       | 14.29%  |
| 8      | 7        | 4.35%   |
| 16     | 6        | 3.73%   |
| 12     | 3        | 1.86%   |
| 10     | 1        | 0.62%   |
| 3      | 1        | 0.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 160      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 85       | 52.8%   |
| 2      | 76       | 47.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 160      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 39       | 23.35%  |
| 0x306c3    | 22       | 13.17%  |
| 0x206a7    | 14       | 8.38%   |
| 0x306a9    | 13       | 7.78%   |
| 0x1067a    | 12       | 7.19%   |
| 0x506e3    | 6        | 3.59%   |
| 0x08701021 | 5        | 2.99%   |
| 0x08108109 | 5        | 2.99%   |
| 0x6fb      | 4        | 2.4%    |
| 0x906ea    | 3        | 1.8%    |
| 0x90672    | 3        | 1.8%    |
| 0x6fd      | 3        | 1.8%    |
| 0x0a20120a | 3        | 1.8%    |
| 0xa0671    | 2        | 1.2%    |
| 0xa0655    | 2        | 1.2%    |
| 0xa0653    | 2        | 1.2%    |
| 0x906e9    | 2        | 1.2%    |
| 0x10676    | 2        | 1.2%    |
| 0x906eb    | 1        | 0.6%    |
| 0x506c9    | 1        | 0.6%    |
| 0x406c4    | 1        | 0.6%    |
| 0x406c3    | 1        | 0.6%    |
| 0x306f2    | 1        | 0.6%    |
| 0x206d7    | 1        | 0.6%    |
| 0x20652    | 1        | 0.6%    |
| 0x106a5    | 1        | 0.6%    |
| 0x0a50000b | 1        | 0.6%    |
| 0x0a201016 | 1        | 0.6%    |
| 0x0a201009 | 1        | 0.6%    |
| 0x0a008203 | 1        | 0.6%    |
| 0x08701013 | 1        | 0.6%    |
| 0x0830104d | 1        | 0.6%    |
| 0x08301039 | 1        | 0.6%    |
| 0x0810100b | 1        | 0.6%    |
| 0x0800820d | 1        | 0.6%    |
| 0x08001138 | 1        | 0.6%    |
| 0x08001136 | 1        | 0.6%    |
| 0x08001126 | 1        | 0.6%    |
| 0x06003106 | 1        | 0.6%    |
| 0x03000027 | 1        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 26       | 16.25%  |
| IvyBridge        | 22       | 13.75%  |
| SandyBridge      | 17       | 10.63%  |
| Penryn           | 15       | 9.38%   |
| Zen+             | 8        | 5%      |
| Zen 3            | 8        | 5%      |
| Zen 2            | 8        | 5%      |
| KabyLake         | 8        | 5%      |
| Skylake          | 7        | 4.38%   |
| Core             | 7        | 4.38%   |
| Zen              | 6        | 3.75%   |
| CometLake        | 6        | 3.75%   |
| Unknown          | 4        | 2.5%    |
| K10              | 3        | 1.88%   |
| Alderlake Hybrid | 3        | 1.88%   |
| Westmere         | 2        | 1.25%   |
| Silvermont       | 2        | 1.25%   |
| K8 Hammer        | 2        | 1.25%   |
| Steamroller      | 1        | 0.63%   |
| Piledriver       | 1        | 0.63%   |
| Nehalem          | 1        | 0.63%   |
| K10 Llano        | 1        | 0.63%   |
| Goldmont         | 1        | 0.63%   |
| Excavator        | 1        | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 68       | 39.31%  |
| Intel             | 61       | 35.26%  |
| AMD               | 42       | 24.28%  |
| ASPEED Technology | 2        | 1.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 14       | 7.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10       | 5.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9        | 5.11%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 6        | 3.41%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 3.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6        | 3.41%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 5        | 2.84%   |
| Intel HD Graphics 530                                                                    | 5        | 2.84%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5        | 2.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 2.84%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3        | 1.7%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3        | 1.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 1.7%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 3        | 1.7%    |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 3        | 1.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 1.7%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 3        | 1.7%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 1.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 1.14%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2        | 1.14%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2        | 1.14%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 1.14%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 2        | 1.14%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2        | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.14%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 1.14%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 1.14%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.14%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 1.14%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 1.14%   |
| AMD Bonaire XT [Radeon HD 7790/8770 / R7 360 / R9 260/360 OEM]                           | 2        | 1.14%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.57%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.57%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1        | 0.57%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.57%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1        | 0.57%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 0.57%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1        | 0.57%   |
| Nvidia TU106 [GeForce GTX 1650]                                                          | 1        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 63       | 39.38%  |
| 1 x Intel            | 51       | 31.88%  |
| 1 x AMD              | 39       | 24.38%  |
| Nvidia + ASPEED      | 2        | 1.25%   |
| Intel + Nvidia       | 2        | 1.25%   |
| 2 x AMD + 3 x Nvidia | 1        | 0.63%   |
| 2 x AMD              | 1        | 0.63%   |
| Intel + AMD          | 1        | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 124      | 75.15%  |
| Proprietary | 34       | 20.61%  |
| Unknown     | 7        | 4.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 70       | 42.94%  |
| 1.01-2.0   | 29       | 17.79%  |
| 0.51-1.0   | 23       | 14.11%  |
| 7.01-8.0   | 13       | 7.98%   |
| 3.01-4.0   | 10       | 6.13%   |
| 0.01-0.5   | 8        | 4.91%   |
| 5.01-6.0   | 4        | 2.45%   |
| 8.01-16.0  | 4        | 2.45%   |
| 2.01-3.0   | 2        | 1.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 32       | 19.63%  |
| Samsung Electronics  | 18       | 11.04%  |
| Acer                 | 18       | 11.04%  |
| Goldstar             | 17       | 10.43%  |
| BenQ                 | 16       | 9.82%   |
| Hewlett-Packard      | 15       | 9.2%    |
| AOC                  | 12       | 7.36%   |
| ViewSonic            | 6        | 3.68%   |
| Philips              | 6        | 3.68%   |
| ASUSTek Computer     | 3        | 1.84%   |
| Toshiba              | 2        | 1.23%   |
| Sharp                | 2        | 1.23%   |
| LG Electronics       | 2        | 1.23%   |
| Lenovo               | 2        | 1.23%   |
| Denver               | 2        | 1.23%   |
| Unknown              | 2        | 1.23%   |
| Unknown              | 1        | 0.61%   |
| Panasonic            | 1        | 0.61%   |
| HUYINIUDA            | 1        | 0.61%   |
| Envision Peripherals | 1        | 0.61%   |
| Eizo                 | 1        | 0.61%   |
| Dinner               | 1        | 0.61%   |
| CVT                  | 1        | 0.61%   |
| AOpen                | 1        | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 7        | 4.02%   |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                  | 6        | 3.45%   |
| Dell E2720HS DELA15E 1920x1080 600x340mm 27.2-inch                | 4        | 2.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 3        | 1.72%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch               | 3        | 1.72%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch           | 3        | 1.72%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                 | 3        | 1.72%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                 | 3        | 1.72%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch  | 2        | 1.15%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                | 2        | 1.15%   |
| Hewlett-Packard LCD Monitor P221                                  | 2        | 1.15%   |
| Dell LCD Monitor E2720HS 1920x1080                                | 2        | 1.15%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                 | 2        | 1.15%   |
| BenQ LCD Monitor GW2270 1920x1080                                 | 2        | 1.15%   |
| ASUSTek Computer XG32VQR AUS32B2 2560x1440 697x393mm 31.5-inch    | 2        | 1.15%   |
| AOC LCD Monitor 936W 1366x768                                     | 2        | 1.15%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                     | 2        | 1.15%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                    | 2        | 1.15%   |
| Acer V193HQL ACR027C 1366x768 410x230mm 18.5-inch                 | 2        | 1.15%   |
| Unknown                                                           | 2        | 1.15%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch     | 1        | 0.57%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch         | 1        | 0.57%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch         | 1        | 0.57%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch     | 1        | 0.57%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch        | 1        | 0.57%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch      | 1        | 0.57%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                             | 1        | 0.57%   |
| Toshiba TV TSB0113 1920x1080 1220x680mm 55.0-inch                 | 1        | 0.57%   |
| Toshiba Crystal View LCD0001 1920x1080 408x255mm 18.9-inch        | 1        | 0.57%   |
| Sharp LCD SHP10C9 1920x540                                        | 1        | 0.57%   |
| Sharp LC-22LE420M SHP2242 1920x1080 477x268mm 21.5-inch           | 1        | 0.57%   |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch | 1        | 0.57%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch  | 1        | 0.57%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch | 1        | 0.57%   |
| Samsung Electronics S24C350 SAM0A3C 1920x1080 521x293mm 23.5-inch | 1        | 0.57%   |
| Samsung Electronics S23C350 SAM0A35 1920x1080 510x287mm 23.0-inch | 1        | 0.57%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch | 1        | 0.57%   |
| Samsung Electronics S22A33x SAM7122 1920x1080 479x260mm 21.5-inch | 1        | 0.57%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch  | 1        | 0.57%   |
| Samsung Electronics S20C300 SAM0A19 1600x900 432x240mm 19.5-inch  | 1        | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 66       | 40.74%  |
| 1366x768 (WXGA)    | 18       | 11.11%  |
| 3840x2160 (4K)     | 16       | 9.88%   |
| 1600x900 (HD+)     | 14       | 8.64%   |
| 2560x1440 (QHD)    | 8        | 4.94%   |
| 2560x1080          | 5        | 3.09%   |
| 1440x900 (WXGA+)   | 5        | 3.09%   |
| Unknown            | 5        | 3.09%   |
| 1360x768           | 4        | 2.47%   |
| 1680x1050 (WSXGA+) | 3        | 1.85%   |
| 1280x1024 (SXGA)   | 3        | 1.85%   |
| 5760x1080          | 2        | 1.23%   |
| 1920x1200 (WUXGA)  | 2        | 1.23%   |
| 1600x1200          | 2        | 1.23%   |
| 5440x1080          | 1        | 0.62%   |
| 5120x1440          | 1        | 0.62%   |
| 3840x1080          | 1        | 0.62%   |
| 3440x1440          | 1        | 0.62%   |
| 3120x1600          | 1        | 0.62%   |
| 1920x540           | 1        | 0.62%   |
| 1280x960           | 1        | 0.62%   |
| 1280x720 (HD)      | 1        | 0.62%   |
| 1024x768 (XGA)     | 1        | 0.62%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 23       | 14.2%   |
| 21      | 20       | 12.35%  |
| 18      | 19       | 11.73%  |
| Unknown | 17       | 10.49%  |
| 23      | 16       | 9.88%   |
| 27      | 14       | 8.64%   |
| 20      | 12       | 7.41%   |
| 19      | 12       | 7.41%   |
| 31      | 9        | 5.56%   |
| 34      | 4        | 2.47%   |
| 32      | 3        | 1.85%   |
| 22      | 3        | 1.85%   |
| 17      | 3        | 1.85%   |
| 84      | 1        | 0.62%   |
| 55      | 1        | 0.62%   |
| 39      | 1        | 0.62%   |
| 35      | 1        | 0.62%   |
| 28      | 1        | 0.62%   |
| 25      | 1        | 0.62%   |
| 15      | 1        | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 64       | 40.25%  |
| 501-600     | 49       | 30.82%  |
| Unknown     | 17       | 10.69%  |
| 601-700     | 12       | 7.55%   |
| 701-800     | 7        | 4.4%    |
| 301-350     | 4        | 2.52%   |
| 801-900     | 2        | 1.26%   |
| 351-400     | 2        | 1.26%   |
| 1501-2000   | 1        | 0.63%   |
| 1001-1500   | 1        | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 113      | 72.44%  |
| Unknown | 16       | 10.26%  |
| 16/10   | 12       | 7.69%   |
| 21/9    | 6        | 3.85%   |
| 5/4     | 5        | 3.21%   |
| 4/3     | 3        | 1.92%   |
| 32/9    | 1        | 0.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 53       | 33.33%  |
| 151-200        | 29       | 18.24%  |
| 141-150        | 20       | 12.58%  |
| 351-500        | 17       | 10.69%  |
| Unknown        | 17       | 10.69%  |
| 301-350        | 14       | 8.81%   |
| 251-300        | 5        | 3.14%   |
| More than 1000 | 2        | 1.26%   |
| 101-110        | 1        | 0.63%   |
| 501-1000       | 1        | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 105      | 67.31%  |
| 101-120 | 25       | 16.03%  |
| Unknown | 17       | 10.9%   |
| 121-160 | 5        | 3.21%   |
| 1-50    | 3        | 1.92%   |
| 161-240 | 1        | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 136      | 83.95%  |
| 2     | 14       | 8.64%   |
| 0     | 10       | 6.17%   |
| 3     | 2        | 1.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 89       | 33.84%  |
| Intel                             | 69       | 26.24%  |
| Qualcomm Atheros                  | 24       | 9.13%   |
| TP-Link                           | 17       | 6.46%   |
| Ralink Technology                 | 14       | 5.32%   |
| D-Link                            | 10       | 3.8%    |
| Broadcom                          | 10       | 3.8%    |
| Qualcomm Atheros Communications   | 8        | 3.04%   |
| Xiaomi                            | 6        | 2.28%   |
| Nvidia                            | 3        | 1.14%   |
| Samsung Electronics               | 2        | 0.76%   |
| Aquantia                          | 2        | 0.76%   |
| Tehuti Networks                   | 1        | 0.38%   |
| Sundance Technology Inc / IC Plus | 1        | 0.38%   |
| Ralink                            | 1        | 0.38%   |
| OPPO Electronics                  | 1        | 0.38%   |
| InterBiometrics                   | 1        | 0.38%   |
| D-Link System                     | 1        | 0.38%   |
| Broadcom Limited                  | 1        | 0.38%   |
| Apple                             | 1        | 0.38%   |
| AboCom Systems                    | 1        | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 64       | 21.84%  |
| TP-Link Archer T4U ver.3                                                             | 9        | 3.07%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 8        | 2.73%   |
| Intel 82579V Gigabit Network Connection                                              | 8        | 2.73%   |
| Ralink MT7601U Wireless Adapter                                                      | 7        | 2.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 7        | 2.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 6        | 2.05%   |
| Realtek 802.11ac NIC                                                                 | 6        | 2.05%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 6        | 2.05%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6        | 2.05%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 5        | 1.71%   |
| Intel I211 Gigabit Network Connection                                                | 5        | 1.71%   |
| Intel Ethernet Connection (11) I219-V                                                | 5        | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                       | 4        | 1.37%   |
| TP-Link 802.11n NIC                                                                  | 4        | 1.37%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 4        | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4        | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 4        | 1.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 4        | 1.37%   |
| Intel Ethernet Connection I217-LM                                                    | 4        | 1.37%   |
| Intel Ethernet Connection (7) I219-V                                                 | 4        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 4        | 1.37%   |
| Intel 82567LM-3 Gigabit Network Connection                                           | 4        | 1.37%   |
| Intel 82566DM-2 Gigabit Network Connection                                           | 4        | 1.37%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3        | 1.02%   |
| Intel Ethernet Controller I225-V                                                     | 3        | 1.02%   |
| Intel Ethernet Connection (2) I219-V                                                 | 3        | 1.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 3        | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                 | 2        | 0.68%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2        | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 0.68%   |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 0.68%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 2        | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                           | 2        | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                       | 2        | 0.68%   |
| Intel Wireless 3165                                                                  | 2        | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 2        | 0.68%   |
| Intel Wi-Fi 6 AX200                                                                  | 2        | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 26       | 23.01%  |
| TP-Link                         | 17       | 15.04%  |
| Intel                           | 17       | 15.04%  |
| Ralink Technology               | 14       | 12.39%  |
| Qualcomm Atheros                | 11       | 9.73%   |
| D-Link                          | 10       | 8.85%   |
| Qualcomm Atheros Communications | 8        | 7.08%   |
| Broadcom                        | 6        | 5.31%   |
| Ralink                          | 1        | 0.88%   |
| D-Link System                   | 1        | 0.88%   |
| Broadcom Limited                | 1        | 0.88%   |
| AboCom Systems                  | 1        | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| TP-Link Archer T4U ver.3                                                             | 9        | 7.83%   |
| Ralink MT7601U Wireless Adapter                                                      | 7        | 6.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 6        | 5.22%   |
| Realtek 802.11ac NIC                                                                 | 6        | 5.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 6        | 5.22%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6        | 5.22%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 5        | 4.35%   |
| TP-Link 802.11n NIC                                                                  | 4        | 3.48%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 4        | 3.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4        | 3.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 4        | 3.48%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 3.48%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 2.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3        | 2.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 3        | 2.61%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2        | 1.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 1.74%   |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 1.74%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 2        | 1.74%   |
| Intel Wireless 3165                                                                  | 2        | 1.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 2        | 1.74%   |
| Intel Wi-Fi 6 AX200                                                                  | 2        | 1.74%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 2        | 1.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 1        | 0.87%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1        | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.87%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 0.87%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                            | 1        | 0.87%   |
| Ralink RT5572 Wireless Adapter                                                       | 1        | 0.87%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                          | 1        | 0.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1        | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 1        | 0.87%   |
| Intel Wireless-AC 9260                                                               | 1        | 0.87%   |
| Intel Wireless 8260                                                                  | 1        | 0.87%   |
| Intel Wireless 7260                                                                  | 1        | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1        | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 1        | 0.87%   |
| D-Link WLAN controller                                                               | 1        | 0.87%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]                    | 1        | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 76       | 45.24%  |
| Intel                             | 59       | 35.12%  |
| Qualcomm Atheros                  | 13       | 7.74%   |
| Xiaomi                            | 6        | 3.57%   |
| Broadcom                          | 4        | 2.38%   |
| Nvidia                            | 3        | 1.79%   |
| Aquantia                          | 2        | 1.19%   |
| Tehuti Networks                   | 1        | 0.6%    |
| Sundance Technology Inc / IC Plus | 1        | 0.6%    |
| Samsung Electronics               | 1        | 0.6%    |
| OPPO Electronics                  | 1        | 0.6%    |
| Apple                             | 1        | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 64       | 36.36%  |
| Realtek RTL8125 2.5GbE Controller                                          | 8        | 4.55%   |
| Intel 82579V Gigabit Network Connection                                    | 8        | 4.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 7        | 3.98%   |
| Intel I211 Gigabit Network Connection                                      | 5        | 2.84%   |
| Intel Ethernet Connection (11) I219-V                                      | 5        | 2.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 4        | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 4        | 2.27%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 2.27%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 4        | 2.27%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 2.27%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 2.27%   |
| Intel Ethernet Controller I225-V                                           | 3        | 1.7%    |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 1.7%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2        | 1.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 2        | 1.14%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2        | 1.14%   |
| Intel I350 Gigabit Fiber Network Connection                                | 2        | 1.14%   |
| Intel Ethernet Controller X550                                             | 2        | 1.14%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 1.14%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                       | 2        | 1.14%   |
| Intel 82583V Gigabit Network Connection                                    | 2        | 1.14%   |
| Intel 82562V-2 10/100 Network Connection                                   | 2        | 1.14%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 1.14%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 1.14%   |
| Tehuti Networks TN9310 10GbE SFP+ Ethernet Adapter                         | 1        | 0.57%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                                      | 1        | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1        | 0.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.57%   |
| OPPO SM8350-MTP _SN:1518BD09                                               | 1        | 0.57%   |
| Nvidia MCP73 Ethernet                                                      | 1        | 0.57%   |
| Nvidia MCP61 Ethernet                                                      | 1        | 0.57%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 146      | 58.4%   |
| WiFi     | 102      | 40.8%   |
| Modem    | 2        | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 91       | 55.83%  |
| WiFi     | 72       | 44.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 93       | 57.41%  |
| 2     | 42       | 25.93%  |
| 0     | 13       | 8.02%   |
| 3     | 10       | 6.17%   |
| 9     | 1        | 0.62%   |
| 8     | 1        | 0.62%   |
| 5     | 1        | 0.62%   |
| 4     | 1        | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 127      | 76.51%  |
| Yes  | 39       | 23.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 22       | 40%     |
| Intel                   | 18       | 32.73%  |
| Realtek Semiconductor   | 4        | 7.27%   |
| TP-Link                 | 2        | 3.64%   |
| IMC Networks            | 2        | 3.64%   |
| D-Link                  | 2        | 3.64%   |
| Broadcom                | 2        | 3.64%   |
| Apple                   | 2        | 3.64%   |
| Foxconn / Hon Hai       | 1        | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22       | 40%     |
| Intel AX201 Bluetooth                               | 6        | 10.91%  |
| Intel Bluetooth wireless interface                  | 5        | 9.09%   |
| Realtek Bluetooth Radio                             | 4        | 7.27%   |
| Intel AX200 Bluetooth                               | 3        | 5.45%   |
| TP-Link UB500 Adapter                               | 2        | 3.64%   |
| Intel AX210 Bluetooth                               | 2        | 3.64%   |
| D-Link DBT-122 Bluetooth adapter                    | 2        | 3.64%   |
| Apple Bluetooth Host Controller                     | 2        | 3.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 1.82%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.82%   |
| IMC Networks Bluetooth Device                       | 1        | 1.82%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1        | 1.82%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.82%   |
| Broadcom BCM20702A0                                 | 1        | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 112      | 41.95%  |
| Nvidia                      | 68       | 25.47%  |
| AMD                         | 56       | 20.97%  |
| Logitech                    | 7        | 2.62%   |
| C-Media Electronics         | 5        | 1.87%   |
| JMTek                       | 4        | 1.5%    |
| ASUSTek Computer            | 3        | 1.12%   |
| Texas Instruments           | 2        | 0.75%   |
| Setek Elektronik            | 1        | 0.37%   |
| RODE Microphones            | 1        | 0.37%   |
| Razer USA                   | 1        | 0.37%   |
| GYROCOM C&C                 | 1        | 0.37%   |
| GN Netcom                   | 1        | 0.37%   |
| Generalplus Technology      | 1        | 0.37%   |
| FiiO Electronics Technology | 1        | 0.37%   |
| DCMT Technology             | 1        | 0.37%   |
| Creative Labs               | 1        | 0.37%   |
| Cooler Master               | 1        | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 19       | 6.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 18       | 6.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 15       | 5.03%   |
| AMD Starship/Matisse HD Audio Controller                                          | 15       | 5.03%   |
| Nvidia GF108 High Definition Audio Controller                                     | 13       | 4.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11       | 3.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 9        | 3.02%   |
| AMD Family 17h/19h HD Audio Controller                                            | 9        | 3.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 9        | 3.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 8        | 2.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 8        | 2.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7        | 2.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 1.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 5        | 1.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 1.68%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 1.34%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4        | 1.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 1.34%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 1.34%   |
| Logitech H600 [Wireless Headset]                                                  | 4        | 1.34%   |
| JMTek USB PnP Audio Device                                                        | 4        | 1.34%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 1.34%   |
| Intel Alder Lake-S HD Audio Controller                                            | 4        | 1.34%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 1.34%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 1.01%   |
| Nvidia High Definition Audio Controller                                           | 3        | 1.01%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 1.01%   |
| Nvidia GA106 High Definition Audio Controller                                     | 3        | 1.01%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 1.01%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 1.01%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 1.01%   |
| ASUSTek Computer USB Audio                                                        | 3        | 1.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 1.01%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2        | 0.67%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 0.67%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 0.67%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 0.67%   |
| Nvidia GF116 High Definition Audio Controller                                     | 2        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 30       | 34.88%  |
| Corsair             | 18       | 20.93%  |
| Unknown             | 8        | 9.3%    |
| SK hynix            | 7        | 8.14%   |
| Micron Technology   | 3        | 3.49%   |
| Kingmax             | 3        | 3.49%   |
| Team                | 2        | 2.33%   |
| Samsung Electronics | 2        | 2.33%   |
| Kimtigo             | 2        | 2.33%   |
| G.Skill             | 2        | 2.33%   |
| A-DATA Technology   | 2        | 2.33%   |
| Unknown (ABCD)      | 1        | 1.16%   |
| Silicon Power       | 1        | 1.16%   |
| SemsoTai            | 1        | 1.16%   |
| PNY                 | 1        | 1.16%   |
| Patriot Memory      | 1        | 1.16%   |
| Kinlstuo            | 1        | 1.16%   |
| Apacer              | 1        | 1.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s            | 6        | 6.25%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 5        | 5.21%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s         | 4        | 4.17%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 3        | 3.13%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 2        | 2.08%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 2.08%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 2        | 2.08%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 2        | 2.08%   |
| Kingmax RAM FLFE85F-C8KL9 2GB DIMM DDR3 1333MT/s               | 2        | 2.08%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                 | 2        | 2.08%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 2        | 2.08%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                      | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM 667MT/s                            | 1        | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 1.04%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s             | 1        | 1.04%   |
| Team RAM Elite-800 2GB DIMM SDRAM 2048MT/s                     | 1        | 1.04%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                  | 1        | 1.04%   |
| SK hynix RAM HYMP112F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s    | 1        | 1.04%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 1        | 1.04%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s           | 1        | 1.04%   |
| SK hynix RAM HMA84GR7CJR4N-XN 32GB DIMM DDR4 3200MT/s          | 1        | 1.04%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s           | 1        | 1.04%   |
| Silicon Power RAM DBLT2GN568S 2048MB DIMM DDR3 1333MT/s        | 1        | 1.04%   |
| SemsoTai RAM Module 8GB DIMM DDR4 2667MT/s                     | 1        | 1.04%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1        | 1.04%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.04%   |
| PNY RAM 8GBF1X08LFHH35-12-K 8GB DIMM DDR4 2667MT/s             | 1        | 1.04%   |
| Patriot Memory RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s     | 1        | 1.04%   |
| Micron RAM M378B5273BH1-CK0 8GB DIMM DDR3 1600MT/s             | 1        | 1.04%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 1        | 1.04%   |
| Micron RAM 18JSF25672AZ 2048MB DIMM DDR3 1066MT/s              | 1        | 1.04%   |
| Kinlstuo RAM Module 8192MB DIMM DDR3 1600MT/s                  | 1        | 1.04%   |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s                      | 1        | 1.04%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                   | 1        | 1.04%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 1        | 1.04%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 1        | 1.04%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s            | 1        | 1.04%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s            | 1        | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 31       | 37.8%   |
| DDR3    | 31       | 37.8%   |
| SDRAM   | 12       | 14.63%  |
| DDR2    | 5        | 6.1%    |
| Unknown | 2        | 2.44%   |
| LPDDR4  | 1        | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 76       | 93.83%  |
| SODIMM  | 4        | 4.94%   |
| FB-DIMM | 1        | 1.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 38       | 44.71%  |
| 2048  | 16       | 18.82%  |
| 4096  | 12       | 14.12%  |
| 32768 | 11       | 12.94%  |
| 16384 | 7        | 8.24%   |
| 1024  | 1        | 1.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 27       | 31.4%   |
| 3200    | 12       | 13.95%  |
| 3600    | 6        | 6.98%   |
| 1333    | 6        | 6.98%   |
| 2667    | 5        | 5.81%   |
| 2400    | 4        | 4.65%   |
| 667     | 4        | 4.65%   |
| Unknown | 4        | 4.65%   |
| 800     | 3        | 3.49%   |
| 3933    | 2        | 2.33%   |
| 1800    | 2        | 2.33%   |
| 1066    | 2        | 2.33%   |
| 3534    | 1        | 1.16%   |
| 3466    | 1        | 1.16%   |
| 3000    | 1        | 1.16%   |
| 2933    | 1        | 1.16%   |
| 2133    | 1        | 1.16%   |
| 2048    | 1        | 1.16%   |
| 1867    | 1        | 1.16%   |
| 1866    | 1        | 1.16%   |
| 1067    | 1        | 1.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 33.33%  |
| Brother Industries  | 2        | 22.22%  |
| Seiko Epson         | 1        | 11.11%  |
| Prolific Technology | 1        | 11.11%  |
| Hewlett-Packard     | 1        | 11.11%  |
| Canon               | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung SCX-3400 Series       | 3        | 33.33%  |
| Seiko Epson L310 Series       | 1        | 11.11%  |
| Prolific PL2305 Parallel Port | 1        | 11.11%  |
| HP Ink Tank 110 series        | 1        | 11.11%  |
| Canon E410 series             | 1        | 11.11%  |
| Brother DCP-J105              | 1        | 11.11%  |
| Brother DCP-1610W             | 1        | 11.11%  |

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
| Logitech                      | 10       | 41.67%  |
| Generalplus Technology        | 3        | 12.5%   |
| HD WEBCAM                     | 2        | 8.33%   |
| Apple                         | 2        | 8.33%   |
| WCM_USB                       | 1        | 4.17%   |
| Sunplus Innovation Technology | 1        | 4.17%   |
| Realtek Semiconductor         | 1        | 4.17%   |
| Microdia                      | 1        | 4.17%   |
| Lenovo                        | 1        | 4.17%   |
| Jieli Technology              | 1        | 4.17%   |
| ARC International             | 1        | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 3        | 12.5%   |
| Logitech Webcam C170                     | 2        | 8.33%   |
| HD WEBCAM Web Camera                     | 2        | 8.33%   |
| Generalplus 808 Camera #9 (web-cam mode) | 2        | 8.33%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 2        | 8.33%   |
| WCM_USB WEB CAM                          | 1        | 4.17%   |
| Sunplus Full HD webcam                   | 1        | 4.17%   |
| Realtek HP High Definition 1MP Webcam    | 1        | 4.17%   |
| Microdia CameraA                         | 1        | 4.17%   |
| Logitech Webcam C310                     | 1        | 4.17%   |
| Logitech Webcam C250                     | 1        | 4.17%   |
| Logitech Webcam B500                     | 1        | 4.17%   |
| Logitech HD Webcam C510                  | 1        | 4.17%   |
| Logitech HD Pro Webcam C920              | 1        | 4.17%   |
| Lenovo FHD Webcam                        | 1        | 4.17%   |
| Jieli USB PHY 2.0                        | 1        | 4.17%   |
| Generalplus GENERAL WEBCAM               | 1        | 4.17%   |
| ARC International Camera                 | 1        | 4.17%   |

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
| 0     | 135      | 81.33%  |
| 1     | 28       | 16.87%  |
| 6     | 1        | 0.6%    |
| 3     | 1        | 0.6%    |
| 2     | 1        | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 39.39%  |
| Graphics card            | 12       | 36.36%  |
| Communication controller | 3        | 9.09%   |
| Sound                    | 2        | 6.06%   |
| Unassigned class         | 1        | 3.03%   |
| Storage/ide              | 1        | 3.03%   |
| Network                  | 1        | 3.03%   |

