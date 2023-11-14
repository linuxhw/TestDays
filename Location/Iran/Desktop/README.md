Linux in Iran - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Linux in Iran.

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

Total: 243

| Vendor   | Model                   | Probe                                                      | Date         |
|----------|-------------------------|------------------------------------------------------------|--------------|
| Gigabyte | 970A-D3                 | [80fb26e63a](https://linux-hardware.org/?probe=80fb26e63a) | Nov 03, 2023 |
| MSI      | PRO Z690-A WIFI DDR4    | [23fdd2c31d](https://linux-hardware.org/?probe=23fdd2c31d) | Oct 30, 2023 |
| ASUSTek  | P8H67                   | [68e28eea76](https://linux-hardware.org/?probe=68e28eea76) | Oct 05, 2023 |
| ASUSTek  | TUF B450-PLUS GAMING    | [8da87a8c78](https://linux-hardware.org/?probe=8da87a8c78) | Sep 26, 2023 |
| HP       | 3397                    | [f202c90e23](https://linux-hardware.org/?probe=f202c90e23) | Sep 20, 2023 |
| ASUSTek  | P8H61/USB3              | [cf48b0b959](https://linux-hardware.org/?probe=cf48b0b959) | Sep 14, 2023 |
| ASUSTek  | TUF Gaming B550-PLUS    | [a68551130a](https://linux-hardware.org/?probe=a68551130a) | Sep 13, 2023 |
| ASUSTek  | TUF Gaming B550-PLUS    | [3edc89267d](https://linux-hardware.org/?probe=3edc89267d) | Sep 13, 2023 |
| ECS      | A880GM-AD3              | [828f89ff31](https://linux-hardware.org/?probe=828f89ff31) | Sep 12, 2023 |
| Gigabyte | P85-D3                  | [f090137faf](https://linux-hardware.org/?probe=f090137faf) | Sep 11, 2023 |
| ASUSTek  | P8H61/USB3              | [d93600fc7c](https://linux-hardware.org/?probe=d93600fc7c) | Sep 11, 2023 |
| Gigabyte | H110M-S2PT-CF           | [83ff674ae7](https://linux-hardware.org/?probe=83ff674ae7) | Sep 10, 2023 |
| HP       | 8266                    | [fed6cc89fe](https://linux-hardware.org/?probe=fed6cc89fe) | Sep 09, 2023 |
| ASUSTek  | TUF Z270 MARK 2         | [2d74d46701](https://linux-hardware.org/?probe=2d74d46701) | Aug 30, 2023 |
| MSI      | 970A-G46                | [5b4c3411dc](https://linux-hardware.org/?probe=5b4c3411dc) | Aug 28, 2023 |
| ASUSTek  | TUF Gaming Z490-PLUS    | [6947635a16](https://linux-hardware.org/?probe=6947635a16) | Aug 18, 2023 |
| HP       | 8456                    | [fa8ea86591](https://linux-hardware.org/?probe=fa8ea86591) | Aug 08, 2023 |
| ASUSTek  | TUF B360-PLUS GAMING    | [173929b667](https://linux-hardware.org/?probe=173929b667) | Jul 19, 2023 |
| ASUSTek  | PRIME H370-PLUS         | [8a2aeb02b0](https://linux-hardware.org/?probe=8a2aeb02b0) | Jul 13, 2023 |
| ASUSTek  | P8Z77-V                 | [13ece994a6](https://linux-hardware.org/?probe=13ece994a6) | Jul 09, 2023 |
| Unknown  | CoffeeLake              | [b3f96a87d5](https://linux-hardware.org/?probe=b3f96a87d5) | Jul 09, 2023 |
| HP       | 18E7                    | [8157fe83c7](https://linux-hardware.org/?probe=8157fe83c7) | Jul 09, 2023 |
| ASUSTek  | M5A97 PRO               | [a5cbd2e848](https://linux-hardware.org/?probe=a5cbd2e848) | Jun 14, 2023 |
| ASUSTek  | PRIME Z690-P WIFI       | [63c110632a](https://linux-hardware.org/?probe=63c110632a) | Jun 10, 2023 |
| Biostar  | A68N-2100K              | [9ac86a512d](https://linux-hardware.org/?probe=9ac86a512d) | Jun 09, 2023 |
| ASUSTek  | PRIME Z690-P WIFI       | [061e1e2aec](https://linux-hardware.org/?probe=061e1e2aec) | May 19, 2023 |
| Gigabyte | Z97X-Gaming 3           | [2cbff804d8](https://linux-hardware.org/?probe=2cbff804d8) | May 08, 2023 |
| Gigabyte | Z97X-Gaming 3           | [dd0a47b6fc](https://linux-hardware.org/?probe=dd0a47b6fc) | May 01, 2023 |
| Gigabyte | Z97X-Gaming 3           | [7087295cd7](https://linux-hardware.org/?probe=7087295cd7) | May 01, 2023 |
| ASUSTek  | H110-PLUS               | [f8317bce7b](https://linux-hardware.org/?probe=f8317bce7b) | Apr 26, 2023 |
| ASUSTek  | PRIME H370-PLUS         | [4a7e7763c1](https://linux-hardware.org/?probe=4a7e7763c1) | Mar 28, 2023 |
| YANYU    | ITX-S192                | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| Gigabyte | G31M-ES2C               | [fcd077e70a](https://linux-hardware.org/?probe=fcd077e70a) | Mar 27, 2023 |
| ASUSTek  | P5P43TD                 | [f2be993036](https://linux-hardware.org/?probe=f2be993036) | Mar 13, 2023 |
| Gigabyte | G41MT-S2                | [7f72d6bba7](https://linux-hardware.org/?probe=7f72d6bba7) | Feb 26, 2023 |
| Gigabyte | G41MT-S2                | [d81c35b55b](https://linux-hardware.org/?probe=d81c35b55b) | Feb 25, 2023 |
| ASUSTek  | PRIME H610M-A WIFI D4   | [1b800ff8c2](https://linux-hardware.org/?probe=1b800ff8c2) | Feb 07, 2023 |
| ASUSTek  | PRIME H610M-A WIFI D4   | [69f96bffa5](https://linux-hardware.org/?probe=69f96bffa5) | Feb 07, 2023 |
| Gigabyte | H270-Gaming 3           | [e64a1e0a5a](https://linux-hardware.org/?probe=e64a1e0a5a) | Jan 31, 2023 |
| Gigabyte | H270-Gaming 3           | [4427845ac1](https://linux-hardware.org/?probe=4427845ac1) | Jan 30, 2023 |
| HP       | 805A                    | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| ASUSTek  | H110M-K                 | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek  | H110M-K                 | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| ASUSTek  | PRIME B250-PLUS         | [4d24d45918](https://linux-hardware.org/?probe=4d24d45918) | Dec 21, 2022 |
| HP       | 3397                    | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| Gigabyte | EP41-UD3L               | [db0a79fbd9](https://linux-hardware.org/?probe=db0a79fbd9) | Nov 07, 2022 |
| ASUSTek  | H97-PLUS                | [f22f67754e](https://linux-hardware.org/?probe=f22f67754e) | Oct 29, 2022 |
| Gigabyte | G41MT-S2P               | [d8be5e602a](https://linux-hardware.org/?probe=d8be5e602a) | Sep 19, 2022 |
| ASUSTek  | H110M-K                 | [a15d189c98](https://linux-hardware.org/?probe=a15d189c98) | Sep 17, 2022 |
| ASUSTek  | M2N-E                   | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| ASUSTek  | PRIME A320M-C R2.0      | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| ASUSTek  | H61M-C                  | [93ac400083](https://linux-hardware.org/?probe=93ac400083) | Aug 23, 2022 |
| ASUSTek  | H61M-C                  | [8d187f0a28](https://linux-hardware.org/?probe=8d187f0a28) | Aug 22, 2022 |
| ASUSTek  | Z10PE-D16 WS            | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| Gigabyte | H81M-S2PH               | [c8f8e78df8](https://linux-hardware.org/?probe=c8f8e78df8) | Aug 17, 2022 |
| ASUSTek  | Z10PE-D16 WS            | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| ASUSTek  | H110M-C/PS              | [b633163f9f](https://linux-hardware.org/?probe=b633163f9f) | Aug 06, 2022 |
| ASUSTek  | H61-PLUS                | [117f3d3969](https://linux-hardware.org/?probe=117f3d3969) | Jul 26, 2022 |
| Gigabyte | H61M-D2P-B3             | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| ASUSTek  | PRIME B360M-C           | [6f2adb5629](https://linux-hardware.org/?probe=6f2adb5629) | Jul 24, 2022 |
| ASUSTek  | PRIME B360M-C           | [4e8aa38fb4](https://linux-hardware.org/?probe=4e8aa38fb4) | Jul 11, 2022 |
| ASUSTek  | PRIME Z390-P            | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| HP       | 3397                    | [337e956c95](https://linux-hardware.org/?probe=337e956c95) | Jun 22, 2022 |
| ASUSTek  | H61-PLUS                | [43cf14bdd7](https://linux-hardware.org/?probe=43cf14bdd7) | Jun 22, 2022 |
| Gigabyte | H510M H                 | [7b1a78a681](https://linux-hardware.org/?probe=7b1a78a681) | Jun 11, 2022 |
| ASUSTek  | Maximus II Formula      | [84df720c51](https://linux-hardware.org/?probe=84df720c51) | May 30, 2022 |
| MSI      | 760GM-P33               | [d37fca6b00](https://linux-hardware.org/?probe=d37fca6b00) | May 17, 2022 |
| ASUSTek  | PRIME Z390-P            | [a0c15e2a2f](https://linux-hardware.org/?probe=a0c15e2a2f) | May 16, 2022 |
| Dell     | 0WMJ54 A01              | [58b3a1b83d](https://linux-hardware.org/?probe=58b3a1b83d) | May 07, 2022 |
| Biostar  | A68N-2100K              | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar  | A68N-2100K              | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| HP       | 3048h                   | [2d19799047](https://linux-hardware.org/?probe=2d19799047) | Apr 14, 2022 |
| Gigabyte | 945PL-S3                | [a7da4b6ee0](https://linux-hardware.org/?probe=a7da4b6ee0) | Apr 14, 2022 |
| Gigabyte | 945PL-S3                | [a0ab75ee00](https://linux-hardware.org/?probe=a0ab75ee00) | Apr 14, 2022 |
| Gigabyte | G1.Sniper 5             | [1ee0fc40a2](https://linux-hardware.org/?probe=1ee0fc40a2) | Mar 12, 2022 |
| ASUSTek  | H61-PLUS                | [0d2de64455](https://linux-hardware.org/?probe=0d2de64455) | Mar 06, 2022 |
| ASUSTek  | PRIME H310-PLUS R2.0    | [76da8a616f](https://linux-hardware.org/?probe=76da8a616f) | Mar 05, 2022 |
| ASUSTek  | H81-PLUS                | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek  | H81-PLUS                | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| Gigabyte | P31-ES3G                | [8294f013e8](https://linux-hardware.org/?probe=8294f013e8) | Feb 02, 2022 |
| HP       | 8054                    | [332217129d](https://linux-hardware.org/?probe=332217129d) | Jan 26, 2022 |
| ECS      | H61H2-A                 | [90c26876b2](https://linux-hardware.org/?probe=90c26876b2) | Jan 21, 2022 |
| ECS      | H61H2-A                 | [518e31fcb0](https://linux-hardware.org/?probe=518e31fcb0) | Jan 13, 2022 |
| ECS      | H61H2-A                 | [47fb5347c0](https://linux-hardware.org/?probe=47fb5347c0) | Jan 06, 2022 |
| ECS      | H61H2-A                 | [fa589d8ed4](https://linux-hardware.org/?probe=fa589d8ed4) | Jan 06, 2022 |
| HP       | 806A                    | [d7519db95a](https://linux-hardware.org/?probe=d7519db95a) | Jan 02, 2022 |
| Gigabyte | H310M S2P               | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| HP       | 3397                    | [83d7b8fe86](https://linux-hardware.org/?probe=83d7b8fe86) | Dec 12, 2021 |
| HP       | 3397                    | [469adb677f](https://linux-hardware.org/?probe=469adb677f) | Dec 12, 2021 |
| ASUSTek  | Z170-PRO                | [005b267983](https://linux-hardware.org/?probe=005b267983) | Nov 22, 2021 |
| Gigabyte | P41T-D3P                | [54a25af09a](https://linux-hardware.org/?probe=54a25af09a) | Nov 11, 2021 |
| ASUSTek  | P5P41T-LE               | [20aa404ab6](https://linux-hardware.org/?probe=20aa404ab6) | Nov 10, 2021 |
| ASUSTek  | PRIME B460M-A           | [cfafa7735b](https://linux-hardware.org/?probe=cfafa7735b) | Nov 08, 2021 |
| ASUSTek  | Z97-K                   | [1e136c311c](https://linux-hardware.org/?probe=1e136c311c) | Nov 03, 2021 |
| ASUSTek  | TUF B450-PRO GAMING     | [75b53e8d45](https://linux-hardware.org/?probe=75b53e8d45) | Oct 27, 2021 |
| ASUSTek  | TUF B450-PRO GAMING     | [19cdc9b391](https://linux-hardware.org/?probe=19cdc9b391) | Oct 26, 2021 |
| ASUSTek  | H110M-R                 | [783eeaaa01](https://linux-hardware.org/?probe=783eeaaa01) | Oct 17, 2021 |
| ASUSTek  | P5G41T-M LE             | [398dedabb8](https://linux-hardware.org/?probe=398dedabb8) | Oct 07, 2021 |
| ASUSTek  | P5G41T-M LE             | [23d2e1a73d](https://linux-hardware.org/?probe=23d2e1a73d) | Oct 06, 2021 |
| ASUSTek  | P8H61-M LE R2.0         | [b633c9e1d1](https://linux-hardware.org/?probe=b633c9e1d1) | Sep 28, 2021 |
| ASRock   | B85M                    | [566089bd43](https://linux-hardware.org/?probe=566089bd43) | Sep 27, 2021 |
| ASUSTek  | TUF B360-PLUS GAMING    | [eec5db351d](https://linux-hardware.org/?probe=eec5db351d) | Sep 27, 2021 |
| ASUSTek  | PRIME Z390-P            | [9b27471e86](https://linux-hardware.org/?probe=9b27471e86) | Sep 23, 2021 |
| ECS      | GeForce6100PM-M2        | [016672b182](https://linux-hardware.org/?probe=016672b182) | Sep 03, 2021 |
| ASUSTek  | PRIME H310-PLUS R2.0    | [2044660bb8](https://linux-hardware.org/?probe=2044660bb8) | Aug 30, 2021 |
| YANYU    | M9F baytrail            | [0e5100e716](https://linux-hardware.org/?probe=0e5100e716) | Aug 29, 2021 |
| YANYU    | M9F baytrail            | [0bf997753c](https://linux-hardware.org/?probe=0bf997753c) | Aug 29, 2021 |
| MSI      | H81M-P33                | [de74046226](https://linux-hardware.org/?probe=de74046226) | Aug 23, 2021 |
| Gigabyte | P31-ES3G                | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte | P31-ES3G                | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| ASUSTek  | P5KPL-AM/PS             | [01b8cc373f](https://linux-hardware.org/?probe=01b8cc373f) | Jul 13, 2021 |
| Gigabyte | P31-ES3G                | [09ec64fc0d](https://linux-hardware.org/?probe=09ec64fc0d) | Jul 10, 2021 |
| ASUSTek  | ROG Maximus XII HERO    | [90a20b185b](https://linux-hardware.org/?probe=90a20b185b) | Jul 03, 2021 |
| Gigabyte | 8IPE1000-G/L            | [0301b9707b](https://linux-hardware.org/?probe=0301b9707b) | Jun 29, 2021 |
| ASUSTek  | ROG Maximus XII HERO    | [1343b5bb5d](https://linux-hardware.org/?probe=1343b5bb5d) | Jun 20, 2021 |
| ASUSTek  | PRIME B460-PLUS         | [5963dd2256](https://linux-hardware.org/?probe=5963dd2256) | Jun 18, 2021 |
| Gigabyte | P31-ES3G                | [4b5debd7a6](https://linux-hardware.org/?probe=4b5debd7a6) | Jun 04, 2021 |
| Gigabyte | P31-ES3G                | [4333473e1e](https://linux-hardware.org/?probe=4333473e1e) | Jun 03, 2021 |
| ASRock   | N68-GS4 FX              | [1023832c74](https://linux-hardware.org/?probe=1023832c74) | Jun 01, 2021 |
| ASRock   | N68-GS4 FX              | [2ff6c9500b](https://linux-hardware.org/?probe=2ff6c9500b) | Jun 01, 2021 |
| MSI      | PH67A-C43               | [8e818ce79a](https://linux-hardware.org/?probe=8e818ce79a) | May 05, 2021 |
| Gigabyte | G41MT-S2PT              | [eeb73d1c4a](https://linux-hardware.org/?probe=eeb73d1c4a) | Apr 20, 2021 |
| ASUSTek  | P8H61                   | [93671f3ecc](https://linux-hardware.org/?probe=93671f3ecc) | Apr 20, 2021 |
| ASUSTek  | P8H61                   | [9fbf2707b0](https://linux-hardware.org/?probe=9fbf2707b0) | Apr 19, 2021 |
| Gigabyte | M52S-S3P                | [494ac8b449](https://linux-hardware.org/?probe=494ac8b449) | Apr 11, 2021 |
| ASUSTek  | H61M-C                  | [c39fc169bf](https://linux-hardware.org/?probe=c39fc169bf) | Apr 02, 2021 |
| ASUSTek  | Z170-K                  | [9c2661508e](https://linux-hardware.org/?probe=9c2661508e) | Mar 30, 2021 |
| ASUSTek  | H81-PLUS                | [89b0451670](https://linux-hardware.org/?probe=89b0451670) | Mar 14, 2021 |
| ASUSTek  | H81-PLUS                | [ed8b926f53](https://linux-hardware.org/?probe=ed8b926f53) | Mar 14, 2021 |
| HP       | 3397                    | [13a7f8c4c2](https://linux-hardware.org/?probe=13a7f8c4c2) | Mar 08, 2021 |
| ASUSTek  | P8H61                   | [eb31b2ffb6](https://linux-hardware.org/?probe=eb31b2ffb6) | Mar 07, 2021 |
| ASUSTek  | P8H61                   | [fd19b6b1c8](https://linux-hardware.org/?probe=fd19b6b1c8) | Mar 07, 2021 |
| ASUSTek  | P5P41T-LE               | [502ef11b75](https://linux-hardware.org/?probe=502ef11b75) | Mar 07, 2021 |
| Gigabyte | GA-M55SLI-S4            | [43d0cb9ac1](https://linux-hardware.org/?probe=43d0cb9ac1) | Mar 07, 2021 |
| ASUSTek  | P5E                     | [5681b93aaf](https://linux-hardware.org/?probe=5681b93aaf) | Mar 06, 2021 |
| ASUSTek  | P5E                     | [9f858aaf27](https://linux-hardware.org/?probe=9f858aaf27) | Mar 05, 2021 |
| ASUSTek  | P8H77-V LE              | [b1b8587cdb](https://linux-hardware.org/?probe=b1b8587cdb) | Feb 19, 2021 |
| MSI      | B350M GAMING PRO        | [b6a8851986](https://linux-hardware.org/?probe=b6a8851986) | Feb 19, 2021 |
| Gigabyte | H81M-S2PV               | [9de86c8038](https://linux-hardware.org/?probe=9de86c8038) | Feb 05, 2021 |
| ASUSTek  | Z87-K                   | [f1f4fbad09](https://linux-hardware.org/?probe=f1f4fbad09) | Feb 03, 2021 |
| ASUSTek  | Z87-K                   | [0df26493a8](https://linux-hardware.org/?probe=0df26493a8) | Feb 03, 2021 |
| Unknown  | Unknown                 | [85c5454ed1](https://linux-hardware.org/?probe=85c5454ed1) | Jan 14, 2021 |
| ASUSTek  | H61M-A/USB3             | [d8aafdef30](https://linux-hardware.org/?probe=d8aafdef30) | Jan 10, 2021 |
| Biostar  | P4M900-M7 FE Ver:1.0    | [4d96f1db71](https://linux-hardware.org/?probe=4d96f1db71) | Dec 31, 2020 |
| ASUSTek  | P5P41T-LE               | [be00a7c4e5](https://linux-hardware.org/?probe=be00a7c4e5) | Dec 28, 2020 |
| Gigabyte | EP41-UD3L               | [9582155494](https://linux-hardware.org/?probe=9582155494) | Dec 25, 2020 |
| ASUSTek  | Z97-K                   | [3071d9e517](https://linux-hardware.org/?probe=3071d9e517) | Dec 23, 2020 |
| HP       | 3397                    | [1b81310dbf](https://linux-hardware.org/?probe=1b81310dbf) | Dec 20, 2020 |
| HP       | 3397                    | [086227e446](https://linux-hardware.org/?probe=086227e446) | Dec 20, 2020 |
| ASUSTek  | Z97-K                   | [ccdd9fbe6b](https://linux-hardware.org/?probe=ccdd9fbe6b) | Dec 16, 2020 |
| ASUSTek  | Z97-K                   | [e7e6ad670b](https://linux-hardware.org/?probe=e7e6ad670b) | Dec 16, 2020 |
| ASUSTek  | PRIME H310-PLUS         | [e39c3e59b5](https://linux-hardware.org/?probe=e39c3e59b5) | Dec 13, 2020 |
| Gigabyte | EP41-UD3L               | [d93fb9ef4a](https://linux-hardware.org/?probe=d93fb9ef4a) | Dec 04, 2020 |
| Gigabyte | P55A-UD3P               | [9f5052c50b](https://linux-hardware.org/?probe=9f5052c50b) | Nov 30, 2020 |
| Gigabyte | P55A-UD3P               | [03db05b217](https://linux-hardware.org/?probe=03db05b217) | Nov 30, 2020 |
| ASUSTek  | H110M-A/M.2             | [c9c25216a4](https://linux-hardware.org/?probe=c9c25216a4) | Nov 25, 2020 |
| HP       | 2AF3                    | [3c07a68022](https://linux-hardware.org/?probe=3c07a68022) | Nov 21, 2020 |
| Gigabyte | H81M-S2PV               | [6a88e646aa](https://linux-hardware.org/?probe=6a88e646aa) | Nov 07, 2020 |
| Foxconn  | A8G-i                   | [b4675cde03](https://linux-hardware.org/?probe=b4675cde03) | Oct 27, 2020 |
| Gigabyte | EP41-UD3L               | [c3cd0fcf33](https://linux-hardware.org/?probe=c3cd0fcf33) | Oct 24, 2020 |
| Intel    | P61-S3                  | [efee9af681](https://linux-hardware.org/?probe=efee9af681) | Oct 13, 2020 |
| Intel    | P61-S3                  | [36f0f58223](https://linux-hardware.org/?probe=36f0f58223) | Oct 12, 2020 |
| Gigabyte | 8S648FX-RZ              | [c00289e6ed](https://linux-hardware.org/?probe=c00289e6ed) | Oct 11, 2020 |
| ASRock   | P5B-DE                  | [ef1c17dd39](https://linux-hardware.org/?probe=ef1c17dd39) | Oct 08, 2020 |
| ASUSTek  | P8Z77-V LK              | [bbf7ae1125](https://linux-hardware.org/?probe=bbf7ae1125) | Oct 05, 2020 |
| Gigabyte | P55-USB3                | [ceeced1246](https://linux-hardware.org/?probe=ceeced1246) | Oct 02, 2020 |
| Gigabyte | AX370-Gaming K7         | [5996a3b895](https://linux-hardware.org/?probe=5996a3b895) | Sep 29, 2020 |
| Gigabyte | AX370-Gaming K7         | [60156a645b](https://linux-hardware.org/?probe=60156a645b) | Sep 29, 2020 |
| ASUSTek  | Maximus VII HERO        | [59f1e93325](https://linux-hardware.org/?probe=59f1e93325) | Sep 18, 2020 |
| ASUSTek  | Maximus VII HERO        | [a91b502a98](https://linux-hardware.org/?probe=a91b502a98) | Sep 18, 2020 |
| Gigabyte | B75M-D3V                | [32e15ba2b5](https://linux-hardware.org/?probe=32e15ba2b5) | Sep 18, 2020 |
| ASUSTek  | PRIME B360M-A           | [7ad450ddd7](https://linux-hardware.org/?probe=7ad450ddd7) | Sep 14, 2020 |
| HP       | 3397                    | [e4e6951a4f](https://linux-hardware.org/?probe=e4e6951a4f) | Jul 25, 2020 |
| ASUSTek  | M4A78T-E                | [2c268bdb51](https://linux-hardware.org/?probe=2c268bdb51) | Jul 24, 2020 |
| Lenovo   | ThinkCentre M58 8910ASU | [d29d396ad0](https://linux-hardware.org/?probe=d29d396ad0) | Jul 23, 2020 |
| Gigabyte | H170-D3H-CF             | [eb9ea3a7af](https://linux-hardware.org/?probe=eb9ea3a7af) | Jul 12, 2020 |
| HP       | 212B                    | [4a3583e0db](https://linux-hardware.org/?probe=4a3583e0db) | Jul 06, 2020 |
| ECS      | G31T-M                  | [614dcd20e7](https://linux-hardware.org/?probe=614dcd20e7) | Jul 05, 2020 |
| ASUSTek  | Z170-K                  | [a35de97ee5](https://linux-hardware.org/?probe=a35de97ee5) | Jun 27, 2020 |
| ASUSTek  | H110M-C                 | [5656016c57](https://linux-hardware.org/?probe=5656016c57) | Jun 27, 2020 |
| ASRock   | P5B-DE                  | [304331fe41](https://linux-hardware.org/?probe=304331fe41) | Jun 24, 2020 |
| ASUSTek  | H81M-C                  | [7554759bac](https://linux-hardware.org/?probe=7554759bac) | Jun 18, 2020 |
| Gigabyte | Z68P-DS3                | [a82798aea1](https://linux-hardware.org/?probe=a82798aea1) | May 21, 2020 |
| HP       | 3397                    | [6d3acf04fa](https://linux-hardware.org/?probe=6d3acf04fa) | May 18, 2020 |
| Gigabyte | H81M-S2PV               | [d064b573d0](https://linux-hardware.org/?probe=d064b573d0) | May 14, 2020 |
| ECS      | G41T-M13                | [7f8c6dbb44](https://linux-hardware.org/?probe=7f8c6dbb44) | May 14, 2020 |
| ECS      | G41T-M13                | [b2c5f54483](https://linux-hardware.org/?probe=b2c5f54483) | May 10, 2020 |
| ASUSTek  | H97-PRO                 | [a214d8fa2f](https://linux-hardware.org/?probe=a214d8fa2f) | May 02, 2020 |
| ASUSTek  | H97-PRO                 | [a6f251843f](https://linux-hardware.org/?probe=a6f251843f) | May 01, 2020 |
| ASUSTek  | Z10PE-D16 WS            | [409a40b72d](https://linux-hardware.org/?probe=409a40b72d) | Apr 20, 2020 |
| ASUSTek  | Z97-C                   | [53462bc3ec](https://linux-hardware.org/?probe=53462bc3ec) | Apr 07, 2020 |
| HP       | 3397                    | [f2d1e62e57](https://linux-hardware.org/?probe=f2d1e62e57) | Mar 29, 2020 |
| HP       | 3646h                   | [63c3bf2b90](https://linux-hardware.org/?probe=63c3bf2b90) | Mar 28, 2020 |
| Gigabyte | G31M-S2L                | [ec35befc4a](https://linux-hardware.org/?probe=ec35befc4a) | Mar 23, 2020 |
| Gigabyte | G31M-S2L                | [6f1f96e7fc](https://linux-hardware.org/?probe=6f1f96e7fc) | Mar 23, 2020 |
| Gigabyte | H61M-S2V-B3             | [b7d3805ba6](https://linux-hardware.org/?probe=b7d3805ba6) | Mar 23, 2020 |
| ASRock   | ConRoe865GV             | [e849d8b11f](https://linux-hardware.org/?probe=e849d8b11f) | Mar 15, 2020 |
| ASRock   | ConRoe865GV             | [2f52f8c106](https://linux-hardware.org/?probe=2f52f8c106) | Mar 12, 2020 |
| MSI      | B250M PRO-VH            | [1eb2d76730](https://linux-hardware.org/?probe=1eb2d76730) | Mar 10, 2020 |
| ECS      | 945GCT-M                | [069450c325](https://linux-hardware.org/?probe=069450c325) | Mar 08, 2020 |
| Gigabyte | M1689D                  | [9f48604ff2](https://linux-hardware.org/?probe=9f48604ff2) | Mar 07, 2020 |
| Gigabyte | M1689D                  | [43f9f0167a](https://linux-hardware.org/?probe=43f9f0167a) | Mar 07, 2020 |
| ASUSTek  | M4A78T-E                | [80b614b253](https://linux-hardware.org/?probe=80b614b253) | Mar 02, 2020 |
| Lenovo   | ThinkCentre M58 7360EHU | [7067a56ae2](https://linux-hardware.org/?probe=7067a56ae2) | Feb 27, 2020 |
| ASUSTek  | PRIME Z270-K            | [98cee968eb](https://linux-hardware.org/?probe=98cee968eb) | Feb 18, 2020 |
| Unknown  | Unknown                 | [0061763167](https://linux-hardware.org/?probe=0061763167) | Feb 11, 2020 |
| HP       | 8054                    | [b9f8081fe1](https://linux-hardware.org/?probe=b9f8081fe1) | Jan 06, 2020 |
| ASUSTek  | P8Z68-V LE              | [9d6c061d8b](https://linux-hardware.org/?probe=9d6c061d8b) | Jan 04, 2020 |
| Gigabyte | Z390 GAMING X-CF        | [61d0162de0](https://linux-hardware.org/?probe=61d0162de0) | Dec 21, 2019 |
| Gigabyte | Z390 GAMING X-CF        | [130e16c2b6](https://linux-hardware.org/?probe=130e16c2b6) | Dec 08, 2019 |
| ECS      | 945GCT-M                | [a68627d7eb](https://linux-hardware.org/?probe=a68627d7eb) | Nov 28, 2019 |
| HP       | 18E7                    | [f728a63212](https://linux-hardware.org/?probe=f728a63212) | Nov 26, 2019 |
| ECS      | 945GCT-M                | [380140eb8d](https://linux-hardware.org/?probe=380140eb8d) | Nov 06, 2019 |
| ECS      | 945GCT-M                | [89e9d28a32](https://linux-hardware.org/?probe=89e9d28a32) | Nov 01, 2019 |
| ASUSTek  | P7P55 LX                | [63dc09b54e](https://linux-hardware.org/?probe=63dc09b54e) | Oct 28, 2019 |
| ASUSTek  | P7P55 LX                | [cf9411c533](https://linux-hardware.org/?probe=cf9411c533) | Oct 28, 2019 |
| ASRock   | ConRoeXFire-eSATA2      | [22d2f0f13e](https://linux-hardware.org/?probe=22d2f0f13e) | Sep 12, 2019 |
| ASUSTek  | B85-PLUS                | [2665a9b231](https://linux-hardware.org/?probe=2665a9b231) | Sep 11, 2019 |
| ECS      | 945PT-A2                | [e73a14a3e7](https://linux-hardware.org/?probe=e73a14a3e7) | Sep 10, 2019 |
| ASUSTek  | M3N78-EH                | [0ded7435b9](https://linux-hardware.org/?probe=0ded7435b9) | Sep 04, 2019 |
| ASRock   | ConRoeXFire-eSATA2      | [eaf9b72412](https://linux-hardware.org/?probe=eaf9b72412) | Aug 31, 2019 |
| ASUSTek  | PRIME H310-PLUS         | [be649fc45f](https://linux-hardware.org/?probe=be649fc45f) | Aug 25, 2019 |
| Gigabyte | H110M-S2PV-CF           | [d0ac33919a](https://linux-hardware.org/?probe=d0ac33919a) | Aug 05, 2019 |
| ASUSTek  | All Series              | [383d32f068](https://linux-hardware.org/?probe=383d32f068) | Jun 27, 2019 |
| ASUSTek  | P5GC-MX/1333            | [b974503bc3](https://linux-hardware.org/?probe=b974503bc3) | Jun 07, 2019 |
| ASUSTek  | P9X79 LE                | [7cb5494874](https://linux-hardware.org/?probe=7cb5494874) | Jun 03, 2019 |
| ASUSTek  | P9X79 LE                | [77dc13fea3](https://linux-hardware.org/?probe=77dc13fea3) | Jun 03, 2019 |
| ASUSTek  | H81-PLUS                | [7ce9462b77](https://linux-hardware.org/?probe=7ce9462b77) | May 25, 2019 |
| ASUSTek  | H81-PLUS                | [4f2a9b31b5](https://linux-hardware.org/?probe=4f2a9b31b5) | May 19, 2019 |
| Gigabyte | P75-D3                  | [80e0cb37ad](https://linux-hardware.org/?probe=80e0cb37ad) | May 08, 2019 |
| Gigabyte | P75-D3                  | [af7b263534](https://linux-hardware.org/?probe=af7b263534) | May 08, 2019 |
| Gigabyte | P75-D3                  | [341ae19874](https://linux-hardware.org/?probe=341ae19874) | May 07, 2019 |
| ASUSTek  | P7H57D-V EVO            | [8083f1c192](https://linux-hardware.org/?probe=8083f1c192) | May 02, 2019 |
| HP       | 18E7                    | [314a0e2775](https://linux-hardware.org/?probe=314a0e2775) | Apr 24, 2019 |
| HP       | 18E7                    | [74ff68d1e2](https://linux-hardware.org/?probe=74ff68d1e2) | Feb 28, 2019 |
| ASUSTek  | B85-PRO GAMER           | [078ded72a8](https://linux-hardware.org/?probe=078ded72a8) | Dec 10, 2018 |
| ASUSTek  | B85-PRO GAMER           | [7ee24f399a](https://linux-hardware.org/?probe=7ee24f399a) | Dec 10, 2018 |
| Gigabyte | H61M-S2P                | [bdd9f59ab7](https://linux-hardware.org/?probe=bdd9f59ab7) | Dec 09, 2018 |
| Gigabyte | H61M-S2P                | [3e29d905ef](https://linux-hardware.org/?probe=3e29d905ef) | Dec 09, 2018 |
| ECS      | 945GZ/CT-M              | [86754f87d7](https://linux-hardware.org/?probe=86754f87d7) | Dec 07, 2018 |
| ECS      | 945GZ/CT-M              | [0c8259eea0](https://linux-hardware.org/?probe=0c8259eea0) | Dec 07, 2018 |
| ASUSTek  | PRIME B350-PLUS         | [504bfb59ec](https://linux-hardware.org/?probe=504bfb59ec) | Jan 08, 2018 |
| ASUSTek  | PRIME B350-PLUS         | [6976c096dc](https://linux-hardware.org/?probe=6976c096dc) | Jan 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 33       | 18.86%  |
| Ubuntu 18.04       | 26       | 14.86%  |
| Ubuntu 22.04       | 10       | 5.71%   |
| Ubuntu 19.04       | 6        | 3.43%   |
| Arch Rolling       | 5        | 2.86%   |
| Arch               | 5        | 2.86%   |
| Xubuntu 18.04      | 4        | 2.29%   |
| Linux Mint 21.1    | 4        | 2.29%   |
| Linux Mint 20.3    | 4        | 2.29%   |
| Debian 11          | 4        | 2.29%   |
| Xubuntu 20.04      | 3        | 1.71%   |
| Ubuntu 23.04       | 3        | 1.71%   |
| Ubuntu 20.10       | 3        | 1.71%   |
| OpenMandriva 4.2   | 3        | 1.71%   |
| KDE neon 20.04     | 3        | 1.71%   |
| Fedora 38          | 3        | 1.71%   |
| Zorin 15           | 2        | 1.14%   |
| Ubuntu 21.10       | 2        | 1.14%   |
| Ubuntu 19.10       | 2        | 1.14%   |
| OpenMandriva 4.3   | 2        | 1.14%   |
| OpenMandriva 23.08 | 2        | 1.14%   |
| Linux Mint 20.1    | 2        | 1.14%   |
| Linux Mint 20      | 2        | 1.14%   |
| Kubuntu 22.04      | 2        | 1.14%   |
| Elementary 6.1     | 2        | 1.14%   |
| ArcoLinux Rolling  | 2        | 1.14%   |
| Xubuntu 22.04      | 1        | 0.57%   |
| Xero Rolling       | 1        | 0.57%   |
| Ubuntu Unity 16.04 | 1        | 0.57%   |
| Ubuntu 22.10       | 1        | 0.57%   |
| Solus 4.3          | 1        | 0.57%   |
| ROSA R10           | 1        | 0.57%   |
| Pop!_OS 21.04      | 1        | 0.57%   |
| Pop!_OS 20.10      | 1        | 0.57%   |
| Pop!_OS 20.04      | 1        | 0.57%   |
| OpenMandriva 23.03 | 1        | 0.57%   |
| Manjaro 23.0.0     | 1        | 0.57%   |
| Manjaro 22.0.0     | 1        | 0.57%   |
| Manjaro 21.3.7     | 1        | 0.57%   |
| Manjaro 21.3.4     | 1        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 85       | 49.42%  |
| Linux Mint   | 12       | 6.98%   |
| Arch         | 10       | 5.81%   |
| Fedora       | 9        | 5.23%   |
| Xubuntu      | 8        | 4.65%   |
| OpenMandriva | 8        | 4.65%   |
| Manjaro      | 7        | 4.07%   |
| Debian       | 6        | 3.49%   |
| KDE neon     | 4        | 2.33%   |
| Pop!_OS      | 3        | 1.74%   |
| Zorin        | 2        | 1.16%   |
| Lubuntu      | 2        | 1.16%   |
| Kubuntu      | 2        | 1.16%   |
| Kali         | 2        | 1.16%   |
| Endless      | 2        | 1.16%   |
| Elementary   | 2        | 1.16%   |
| ArcoLinux    | 2        | 1.16%   |
| Xero         | 1        | 0.58%   |
| Ubuntu Unity | 1        | 0.58%   |
| Solus        | 1        | 0.58%   |
| ROSA         | 1        | 0.58%   |
| CentOS       | 1        | 0.58%   |
| Artix        | 1        | 0.58%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-48-generic         | 4        | 2.17%   |
| 6.2.0-20-generic         | 3        | 1.63%   |
| 5.4.0-58-generic         | 3        | 1.63%   |
| 5.4.0-42-generic         | 3        | 1.63%   |
| 5.3.0-40-generic         | 3        | 1.63%   |
| 5.15.0-47-generic        | 3        | 1.63%   |
| 5.11.0-27-generic        | 3        | 1.63%   |
| 5.10.14-desktop-1omv4002 | 3        | 1.63%   |
| 6.4.11-desktop-1omv2390  | 2        | 1.09%   |
| 6.2.9-300.fc38.x86_64    | 2        | 1.09%   |
| 5.8.0-50-generic         | 2        | 1.09%   |
| 5.8.0-44-generic         | 2        | 1.09%   |
| 5.4.0-52-generic         | 2        | 1.09%   |
| 5.4.0-37-generic         | 2        | 1.09%   |
| 5.4.0-26-generic         | 2        | 1.09%   |
| 5.19.0-46-generic        | 2        | 1.09%   |
| 5.19.0                   | 2        | 1.09%   |
| 5.16.7-desktop-1omv4003  | 2        | 1.09%   |
| 5.15.0-58-generic        | 2        | 1.09%   |
| 5.15.0-56-generic        | 2        | 1.09%   |
| 5.13.0-30-generic        | 2        | 1.09%   |
| 5.11.0-41-generic        | 2        | 1.09%   |
| 5.11.0-37-generic        | 2        | 1.09%   |
| 5.0.0-38-generic         | 2        | 1.09%   |
| 5.0.0-37-generic         | 2        | 1.09%   |
| 5.0.0-25-generic         | 2        | 1.09%   |
| 5.0.0-23-generic         | 2        | 1.09%   |
| 4.15.0-88-generic        | 2        | 1.09%   |
| 4.15.0-50-generic        | 2        | 1.09%   |
| 4.15.0-29-generic        | 2        | 1.09%   |
| 6.5.9-arch2-1            | 1        | 0.54%   |
| 6.4.3-arch1-1            | 1        | 0.54%   |
| 6.4.12-arch1-1           | 1        | 0.54%   |
| 6.4.11-x64v2-xanmod1-1   | 1        | 0.54%   |
| 6.4.11-060411-generic    | 1        | 0.54%   |
| 6.3.12-200.fc38.x86_64   | 1        | 0.54%   |
| 6.2.8-arch1-1            | 1        | 0.54%   |
| 6.2.6-desktop-1omv2390   | 1        | 0.54%   |
| 6.2.12-arch1-1           | 1        | 0.54%   |
| 6.2.0-31-generic         | 1        | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 17.88%  |
| 5.15.0  | 15       | 8.38%   |
| 4.15.0  | 14       | 7.82%   |
| 5.0.0   | 12       | 6.7%    |
| 5.11.0  | 11       | 6.15%   |
| 5.8.0   | 10       | 5.59%   |
| 5.13.0  | 10       | 5.59%   |
| 5.3.0   | 9        | 5.03%   |
| 5.19.0  | 5        | 2.79%   |
| 4.18.0  | 5        | 2.79%   |
| 6.4.11  | 4        | 2.23%   |
| 6.2.0   | 4        | 2.23%   |
| 5.10.14 | 3        | 1.68%   |
| 5.10.0  | 3        | 1.68%   |
| 6.2.9   | 2        | 1.12%   |
| 5.16.7  | 2        | 1.12%   |
| 6.5.9   | 1        | 0.56%   |
| 6.4.3   | 1        | 0.56%   |
| 6.4.12  | 1        | 0.56%   |
| 6.3.12  | 1        | 0.56%   |
| 6.2.8   | 1        | 0.56%   |
| 6.2.6   | 1        | 0.56%   |
| 6.2.12  | 1        | 0.56%   |
| 6.1.0   | 1        | 0.56%   |
| 6.0.0   | 1        | 0.56%   |
| 5.9.4   | 1        | 0.56%   |
| 5.9.12  | 1        | 0.56%   |
| 5.8.9   | 1        | 0.56%   |
| 5.8.8   | 1        | 0.56%   |
| 5.8.18  | 1        | 0.56%   |
| 5.8.12  | 1        | 0.56%   |
| 5.7.7   | 1        | 0.56%   |
| 5.7.6   | 1        | 0.56%   |
| 5.6.13  | 1        | 0.56%   |
| 5.18.0  | 1        | 0.56%   |
| 5.17.0  | 1        | 0.56%   |
| 5.16.4  | 1        | 0.56%   |
| 5.16.0  | 1        | 0.56%   |
| 5.15.60 | 1        | 0.56%   |
| 5.15.55 | 1        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 17.98%  |
| 5.15    | 21       | 11.8%   |
| 5.8     | 14       | 7.87%   |
| 4.15    | 14       | 7.87%   |
| 5.0     | 13       | 7.3%    |
| 5.13    | 11       | 6.18%   |
| 5.11    | 11       | 6.18%   |
| 6.2     | 9        | 5.06%   |
| 5.3     | 9        | 5.06%   |
| 5.10    | 8        | 4.49%   |
| 6.4     | 6        | 3.37%   |
| 5.19    | 5        | 2.81%   |
| 4.18    | 5        | 2.81%   |
| 5.16    | 4        | 2.25%   |
| 5.9     | 2        | 1.12%   |
| 5.7     | 2        | 1.12%   |
| 6.5     | 1        | 0.56%   |
| 6.3     | 1        | 0.56%   |
| 6.1     | 1        | 0.56%   |
| 6.0     | 1        | 0.56%   |
| 5.6     | 1        | 0.56%   |
| 5.18    | 1        | 0.56%   |
| 5.17    | 1        | 0.56%   |
| 5.14    | 1        | 0.56%   |
| 5.12    | 1        | 0.56%   |
| 4.9     | 1        | 0.56%   |
| 4.19    | 1        | 0.56%   |
| 4.14    | 1        | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 159      | 95.21%  |
| i686   | 8        | 4.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 93       | 53.45%  |
| KDE5       | 20       | 11.49%  |
| Unknown    | 20       | 11.49%  |
| XFCE       | 17       | 9.77%   |
| X-Cinnamon | 9        | 5.17%   |
| i3         | 4        | 2.3%    |
| LXQt       | 3        | 1.72%   |
| Pantheon   | 2        | 1.15%   |
| Unity      | 1        | 0.57%   |
| MATE       | 1        | 0.57%   |
| LXDE       | 1        | 0.57%   |
| KDE        | 1        | 0.57%   |
| Cinnamon   | 1        | 0.57%   |
| Budgie     | 1        | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 132      | 76.74%  |
| Wayland | 23       | 13.37%  |
| Unknown | 15       | 8.72%   |
| Tty     | 2        | 1.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 94       | 54.65%  |
| GDM3    | 20       | 11.63%  |
| SDDM    | 19       | 11.05%  |
| LightDM | 19       | 11.05%  |
| GDM     | 17       | 9.88%   |
| TDM     | 3        | 1.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 136      | 80%     |
| Unknown | 20       | 11.76%  |
| fa_IR   | 5        | 2.94%   |
| en_GB   | 5        | 2.94%   |
| en_CA   | 2        | 1.18%   |
| C       | 2        | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 100      | 59.88%  |
| EFI  | 67       | 40.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 143      | 84.62%  |
| Overlay | 10       | 5.92%   |
| Btrfs   | 6        | 3.55%   |
| Tmpfs   | 4        | 2.37%   |
| Unknown | 4        | 2.37%   |
| Xfs     | 1        | 0.59%   |
| Ext3    | 1        | 0.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 109      | 64.12%  |
| GPT     | 49       | 28.82%  |
| MBR     | 12       | 7.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 144      | 84.21%  |
| Yes       | 27       | 15.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 92       | 54.12%  |
| Yes       | 78       | 45.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 78       | 46.71%  |
| Gigabyte Technology | 38       | 22.75%  |
| Hewlett-Packard     | 20       | 11.98%  |
| MSI                 | 7        | 4.19%   |
| ECS                 | 7        | 4.19%   |
| ASRock              | 5        | 2.99%   |
| Unknown             | 3        | 1.8%    |
| YANYU               | 2        | 1.2%    |
| Lenovo              | 2        | 1.2%    |
| Biostar             | 2        | 1.2%    |
| Intel               | 1        | 0.6%    |
| Foxconn             | 1        | 0.6%    |
| Dell                | 1        | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 13       | 7.78%   |
| HP Compaq Elite 8300 SFF         | 8        | 4.79%   |
| ASUS P5P41T-LE                   | 3        | 1.8%    |
| Unknown                          | 3        | 1.8%    |
| HP ProDesk 600 G1 SFF            | 2        | 1.2%    |
| HP EliteDesk 800 G2 SFF          | 2        | 1.2%    |
| Gigabyte H81M-S2PV               | 2        | 1.2%    |
| Gigabyte EP41-UD3L               | 2        | 1.2%    |
| ASUS Z10PE-D16 WS                | 2        | 1.2%    |
| ASUS TUF B360-PLUS GAMING        | 2        | 1.2%    |
| ASUS PRIME Z390-P                | 2        | 1.2%    |
| ASUS PRIME H610M-A WIFI D4       | 2        | 1.2%    |
| ASUS PRIME H310-PLUS R2.0        | 2        | 1.2%    |
| ASUS PRIME H310-PLUS             | 2        | 1.2%    |
| ASUS P9X79 LE                    | 2        | 1.2%    |
| ASUS P8H61                       | 2        | 1.2%    |
| ASUS H61M-C                      | 2        | 1.2%    |
| YANYU M9F baytrail               | 1        | 0.6%    |
| YANYU ITX-S192                   | 1        | 0.6%    |
| MSI MS-7D25                      | 1        | 0.6%    |
| MSI MS-7A74                      | 1        | 0.6%    |
| MSI MS-7A39                      | 1        | 0.6%    |
| MSI MS-7817                      | 1        | 0.6%    |
| MSI MS-7693                      | 1        | 0.6%    |
| MSI MS-7673                      | 1        | 0.6%    |
| MSI MS-7623                      | 1        | 0.6%    |
| Lenovo ThinkCentre M58 8910ASU   | 1        | 0.6%    |
| Lenovo ThinkCentre M58 7360EHU   | 1        | 0.6%    |
| Intel P61-S3                     | 1        | 0.6%    |
| HP Z440 Workstation              | 1        | 0.6%    |
| HP Z2 SFF G4 Workstation         | 1        | 0.6%    |
| HP ProDesk 400 G2 MINI           | 1        | 0.6%    |
| HP EliteDesk 705 G3 Desktop Mini | 1        | 0.6%    |
| HP EliteDesk 705 G2 SFF          | 1        | 0.6%    |
| HP Compaq 8000 Elite SFF PC      | 1        | 0.6%    |
| HP Compaq 6000 Pro SFF PC        | 1        | 0.6%    |
| HP 700-270jp                     | 1        | 0.6%    |
| Gigabyte Z97X-Gaming 3           | 1        | 0.6%    |
| Gigabyte Z68P-DS3                | 1        | 0.6%    |
| Gigabyte Z390 GAMING X           | 1        | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 18       | 10.78%  |
| ASUS All             | 13       | 7.78%   |
| HP Compaq            | 10       | 5.99%   |
| ASUS TUF             | 6        | 3.59%   |
| HP EliteDesk         | 4        | 2.4%    |
| HP ProDesk           | 3        | 1.8%    |
| ASUS P8H61           | 3        | 1.8%    |
| ASUS P5P41T-LE       | 3        | 1.8%    |
| Unknown              | 3        | 1.8%    |
| Lenovo ThinkCentre   | 2        | 1.2%    |
| Gigabyte H81M-S2PV   | 2        | 1.2%    |
| Gigabyte EP41-UD3L   | 2        | 1.2%    |
| ASUS Z10PE-D16       | 2        | 1.2%    |
| ASUS P9X79           | 2        | 1.2%    |
| ASUS P8Z77-V         | 2        | 1.2%    |
| ASUS H61M-C          | 2        | 1.2%    |
| ASUS H110M-C         | 2        | 1.2%    |
| YANYU M9F            | 1        | 0.6%    |
| YANYU ITX-S192       | 1        | 0.6%    |
| MSI MS-7D25          | 1        | 0.6%    |
| MSI MS-7A74          | 1        | 0.6%    |
| MSI MS-7A39          | 1        | 0.6%    |
| MSI MS-7817          | 1        | 0.6%    |
| MSI MS-7693          | 1        | 0.6%    |
| MSI MS-7673          | 1        | 0.6%    |
| MSI MS-7623          | 1        | 0.6%    |
| Intel P61-S3         | 1        | 0.6%    |
| HP Z440              | 1        | 0.6%    |
| HP Z2                | 1        | 0.6%    |
| HP 700-270jp         | 1        | 0.6%    |
| Gigabyte Z97X-Gaming | 1        | 0.6%    |
| Gigabyte Z68P-DS3    | 1        | 0.6%    |
| Gigabyte Z390        | 1        | 0.6%    |
| Gigabyte P85-D3      | 1        | 0.6%    |
| Gigabyte P75-D3      | 1        | 0.6%    |
| Gigabyte P55A-UD3P   | 1        | 0.6%    |
| Gigabyte P55-USB3    | 1        | 0.6%    |
| Gigabyte P41T-D3P    | 1        | 0.6%    |
| Gigabyte P31-ES3G    | 1        | 0.6%    |
| Gigabyte M52S-S3P    | 1        | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 21       | 12.57%  |
| 2012 | 19       | 11.38%  |
| 2009 | 16       | 9.58%   |
| 2018 | 13       | 7.78%   |
| 2011 | 13       | 7.78%   |
| 2016 | 12       | 7.19%   |
| 2020 | 9        | 5.39%   |
| 2014 | 9        | 5.39%   |
| 2010 | 9        | 5.39%   |
| 2015 | 8        | 4.79%   |
| 2017 | 7        | 4.19%   |
| 2008 | 7        | 4.19%   |
| 2007 | 7        | 4.19%   |
| 2021 | 5        | 2.99%   |
| 2006 | 5        | 2.99%   |
| 2022 | 2        | 1.2%    |
| 2019 | 2        | 1.2%    |
| 2005 | 2        | 1.2%    |
| 2004 | 1        | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 167      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 162      | 97.01%  |
| Enabled  | 5        | 2.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 167      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 41       | 24.4%   |
| 4.01-8.0    | 35       | 20.83%  |
| 8.01-16.0   | 35       | 20.83%  |
| 3.01-4.0    | 33       | 19.64%  |
| 32.01-64.0  | 10       | 5.95%   |
| 1.01-2.0    | 7        | 4.17%   |
| 2.01-3.0    | 4        | 2.38%   |
| 64.01-256.0 | 2        | 1.19%   |
| 0.51-1.0    | 1        | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 76       | 41.99%  |
| 2.01-3.0   | 51       | 28.18%  |
| 3.01-4.0   | 18       | 9.94%   |
| 4.01-8.0   | 14       | 7.73%   |
| 0.51-1.0   | 9        | 4.97%   |
| 8.01-16.0  | 8        | 4.42%   |
| 0.01-0.5   | 4        | 2.21%   |
| 24.01-32.0 | 1        | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 79       | 46.2%   |
| 2      | 62       | 36.26%  |
| 3      | 19       | 11.11%  |
| 4      | 8        | 4.68%   |
| 5      | 2        | 1.17%   |
| 6      | 1        | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 53.22%  |
| Yes       | 80       | 46.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 166      | 99.4%   |
| No        | 1        | 0.6%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 55.81%  |
| Yes       | 76       | 44.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 86.98%  |
| Yes       | 22       | 13.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Iran    | 167      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Tehran                    | 99       | 55.62%  |
| TehrДЃn                 | 11       | 6.18%   |
| Shiraz                    | 7        | 3.93%   |
| Isfahan                   | 6        | 3.37%   |
| Karaj                     | 4        | 2.25%   |
| Tajrish                   | 3        | 1.69%   |
| Sanandij                  | 3        | 1.69%   |
| Rey                       | 2        | 1.12%   |
| Rehnān                   | 2        | 1.12%   |
| Qom                       | 2        | 1.12%   |
| Mashhad                   | 2        | 1.12%   |
| Kermanshah                | 2        | 1.12%   |
| Kerman                    | 2        | 1.12%   |
| Hamadan                   | 2        | 1.12%   |
| Arak                      | 2        | 1.12%   |
| Yazd                      | 1        | 0.56%   |
| Tīrān                   | 1        | 0.56%   |
| Siakhdekhan               | 1        | 0.56%   |
| Shahrak-e KÅ«lÅ«rÄ« | 1        | 0.56%   |
| Shaft                     | 1        | 0.56%   |
| Saveh                     | 1        | 0.56%   |
| Ramsar                    | 1        | 0.56%   |
| PДЃkdasht               | 1        | 0.56%   |
| Naz̧arābād             | 1        | 0.56%   |
| NajafÄbÄd           | 1        | 0.56%   |
| Khorramabad               | 1        | 0.56%   |
| KhondДЃb                | 1        | 0.56%   |
| Kāshān                  | 1        | 0.56%   |
| KahrД«z                 | 1        | 0.56%   |
| JongД«yeh               | 1        | 0.56%   |
| JavДЃnrЕ«d            | 1        | 0.56%   |
| Farsan                    | 1        | 0.56%   |
| FalÄvarjÄn          | 1        | 0.56%   |
| DorЕ«d                  | 1        | 0.56%   |
| Dezful                    | 1        | 0.56%   |
| DamДЃvand               | 1        | 0.56%   |
| BorЕ«jerd               | 1        | 0.56%   |
| Behshahr                  | 1        | 0.56%   |
| Behbahan                  | 1        | 0.56%   |
| Bahar                     | 1        | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 77       | 109    | 29.84%  |
| Seagate                     | 44       | 50     | 17.05%  |
| Samsung Electronics         | 23       | 34     | 8.91%   |
| Maxtor                      | 22       | 29     | 8.53%   |
| A-DATA Technology           | 19       | 21     | 7.36%   |
| Toshiba                     | 16       | 19     | 6.2%    |
| Lexar                       | 8        | 8      | 3.1%    |
| Kingston                    | 6        | 8      | 2.33%   |
| SPCC                        | 5        | 6      | 1.94%   |
| Hitachi                     | 5        | 6      | 1.94%   |
| Sandisk                     | 4        | 4      | 1.55%   |
| Unknown                     | 3        | 3      | 1.16%   |
| Intel                       | 3        | 3      | 1.16%   |
| Silicon Motion              | 2        | 2      | 0.78%   |
| Realtek Semiconductor       | 2        | 3      | 0.78%   |
| Kingmax                     | 2        | 2      | 0.78%   |
| Apacer                      | 2        | 2      | 0.78%   |
| Team                        | 1        | 1      | 0.39%   |
| Plextor                     | 1        | 1      | 0.39%   |
| Pioneer                     | 1        | 1      | 0.39%   |
| Phison Electronics          | 1        | 1      | 0.39%   |
| Patriot                     | 1        | 1      | 0.39%   |
| OSCOO                       | 1        | 2      | 0.39%   |
| OCZ                         | 1        | 1      | 0.39%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.39%   |
| Lite-On                     | 1        | 1      | 0.39%   |
| KingSpec                    | 1        | 1      | 0.39%   |
| HPE                         | 1        | 1      | 0.39%   |
| Gigabyte Technology         | 1        | 1      | 0.39%   |
| Crucial                     | 1        | 1      | 0.39%   |
| BR                          | 1        | 1      | 0.39%   |
| AMD                         | 1        | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB             | 15       | 5.24%   |
| Seagate ST500DM002-1BD142 500GB      | 8        | 2.8%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 6        | 2.1%    |
| Maxtor STM3250310AS 250GB            | 6        | 2.1%    |
| WDC WD10EZRX-00L4HB0 1TB             | 4        | 1.4%    |
| Samsung SSD 850 EVO 250GB            | 4        | 1.4%    |
| Maxtor 6Y080L0 82GB                  | 4        | 1.4%    |
| Lexar 256GB SSD                      | 4        | 1.4%    |
| A-DATA SU650 120GB SSD               | 4        | 1.4%    |
| WDC WD5000AZRX-00A8LB0 500GB         | 3        | 1.05%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 3        | 1.05%   |
| WDC WD10EARS-00MVWB0 1TB             | 3        | 1.05%   |
| Toshiba DT01ACA100 1TB               | 3        | 1.05%   |
| Toshiba DT01ACA050 500GB             | 3        | 1.05%   |
| SPCC Solid State Disk 128GB          | 3        | 1.05%   |
| Seagate ST3500413AS 500GB            | 3        | 1.05%   |
| Seagate ST1000DM003-9YN162 1TB       | 3        | 1.05%   |
| Maxtor STM3160215AS 160GB            | 3        | 1.05%   |
| A-DATA SU630 240GB SSD               | 3        | 1.05%   |
| WDC WD5000AZRX-00L4HB0 500GB         | 2        | 0.7%    |
| WDC WD5000AZLX-60K2TA0 500GB         | 2        | 0.7%    |
| WDC WD5000AAKX-75U6AA0 500GB         | 2        | 0.7%    |
| WDC WD40EZRZ-00GXCB0 4TB             | 2        | 0.7%    |
| WDC WD40EZAZ-00SF3B0 4TB             | 2        | 0.7%    |
| WDC WD20EZRX-00D8PB0 2TB             | 2        | 0.7%    |
| WDC WD20EARX-00PASB0 2TB             | 2        | 0.7%    |
| WDC WD10PURZ-85U8XY0 1TB             | 2        | 0.7%    |
| WDC WD10EZRX-00A3KB0 1TB             | 2        | 0.7%    |
| WDC WD10EZEX-00WN4A0 1TB             | 2        | 0.7%    |
| WDC WD10EURX-63C57Y0 1TB             | 2        | 0.7%    |
| WDC WD10EARX-00N0YB0 1TB             | 2        | 0.7%    |
| Toshiba MQ01ABF050 500GB             | 2        | 0.7%    |
| SPCC Solid State Disk 120GB          | 2        | 0.7%    |
| Seagate ST3500418AS 500GB            | 2        | 0.7%    |
| Seagate ST3320613AS 320GB            | 2        | 0.7%    |
| Seagate ST3250318AS 250GB            | 2        | 0.7%    |
| Seagate ST1000DM010-2EP102 1TB       | 2        | 0.7%    |
| Seagate ST1000DL002-9TT153 1TB       | 2        | 0.7%    |
| Seagate Backup+ Hub BK 8TB           | 2        | 0.7%    |
| Sandisk WDC WDS240G2G0C-00AJM0 240GB | 2        | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 71       | 98     | 42.51%  |
| Seagate             | 44       | 50     | 26.35%  |
| Maxtor              | 22       | 29     | 13.17%  |
| Toshiba             | 16       | 19     | 9.58%   |
| Samsung Electronics | 7        | 11     | 4.19%   |
| Hitachi             | 5        | 6      | 2.99%   |
| Unknown             | 1        | 1      | 0.6%    |
| HPE                 | 1        | 1      | 0.6%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| A-DATA Technology   | 19       | 21     | 23.17%  |
| Samsung Electronics | 15       | 19     | 18.29%  |
| WDC                 | 11       | 11     | 13.41%  |
| Lexar               | 7        | 7      | 8.54%   |
| Kingston            | 6        | 8      | 7.32%   |
| SPCC                | 5        | 6      | 6.1%    |
| SanDisk             | 2        | 2      | 2.44%   |
| Kingmax             | 2        | 2      | 2.44%   |
| Intel               | 2        | 2      | 2.44%   |
| Apacer              | 2        | 2      | 2.44%   |
| Team                | 1        | 1      | 1.22%   |
| Plextor             | 1        | 1      | 1.22%   |
| Pioneer             | 1        | 1      | 1.22%   |
| Patriot             | 1        | 1      | 1.22%   |
| OSCOO               | 1        | 2      | 1.22%   |
| OCZ                 | 1        | 1      | 1.22%   |
| KingSpec            | 1        | 1      | 1.22%   |
| Gigabyte Technology | 1        | 1      | 1.22%   |
| Crucial             | 1        | 1      | 1.22%   |
| BR                  | 1        | 1      | 1.22%   |
| AMD                 | 1        | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 141      | 215    | 61.57%  |
| SSD     | 75       | 92     | 32.75%  |
| NVMe    | 11       | 16     | 4.8%    |
| Unknown | 2        | 2      | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 163      | 304    | 91.06%  |
| NVMe | 11       | 16     | 6.15%   |
| SAS  | 5        | 5      | 2.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 127      | 188    | 57.73%  |
| 0.51-1.0   | 66       | 89     | 30%     |
| 1.01-2.0   | 11       | 11     | 5%      |
| 3.01-4.0   | 7        | 7      | 3.18%   |
| 2.01-3.0   | 4        | 5      | 1.82%   |
| 4.01-10.0  | 4        | 4      | 1.82%   |
| 10.01-20.0 | 1        | 3      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 42       | 24%     |
| 501-1000       | 35       | 20%     |
| 251-500        | 32       | 18.29%  |
| 1001-2000      | 18       | 10.29%  |
| 51-100         | 14       | 8%      |
| More than 3000 | 10       | 5.71%   |
| 21-50          | 7        | 4%      |
| 2001-3000      | 7        | 4%      |
| 1-20           | 7        | 4%      |
| Unknown        | 3        | 1.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 61       | 34.08%  |
| 21-50          | 24       | 13.41%  |
| 51-100         | 24       | 13.41%  |
| 101-250        | 23       | 12.85%  |
| 251-500        | 16       | 8.94%   |
| 501-1000       | 16       | 8.94%   |
| More than 3000 | 5        | 2.79%   |
| 1001-2000      | 5        | 2.79%   |
| Unknown        | 3        | 1.68%   |
| 2001-3000      | 2        | 1.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 2        | 3      | 8.7%    |
| WDC WD5000AVDS-63U7B1 500GB         | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 2      | 4.35%   |
| WDC WD3200AVVS-62L2B0 320GB         | 1        | 1      | 4.35%   |
| WDC WD10PURZ-85U8XY0 1TB            | 1        | 1      | 4.35%   |
| WDC WD10EZRX-00A3KB0 1TB            | 1        | 1      | 4.35%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 1      | 4.35%   |
| WDC WD10EARX-00N0YB0 1TB            | 1        | 1      | 4.35%   |
| WDC WD10EARS-00MVWB0 1TB            | 1        | 1      | 4.35%   |
| WDC WD1002FBYS-18A6B0 1TB           | 1        | 1      | 4.35%   |
| Toshiba MQ01ABF050 500GB            | 1        | 1      | 4.35%   |
| Toshiba HDWD105 500GB               | 1        | 1      | 4.35%   |
| Seagate ST9500420AS 500GB           | 1        | 1      | 4.35%   |
| Seagate ST3500413AS 500GB           | 1        | 1      | 4.35%   |
| Seagate ST3320613AS 320GB           | 1        | 1      | 4.35%   |
| Seagate ST1000DM003-9YN162 1TB      | 1        | 1      | 4.35%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 2      | 4.35%   |
| Samsung Electronics HD502HI 500GB   | 1        | 2      | 4.35%   |
| Maxtor 6Y080M0 80GB                 | 1        | 1      | 4.35%   |
| Maxtor 6Y080L0 82GB                 | 1        | 1      | 4.35%   |
| Hitachi HDS721010KLA330 1TB         | 1        | 1      | 4.35%   |
| Hitachi HCT721010SLA360 1TB         | 1        | 2      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 10     | 36.36%  |
| Seagate             | 6        | 7      | 27.27%  |
| Toshiba             | 2        | 2      | 9.09%   |
| Samsung Electronics | 2        | 4      | 9.09%   |
| Maxtor              | 2        | 2      | 9.09%   |
| Hitachi             | 2        | 3      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 10     | 38.1%   |
| Seagate             | 6        | 7      | 28.57%  |
| Toshiba             | 2        | 2      | 9.52%   |
| Maxtor              | 2        | 2      | 9.52%   |
| Hitachi             | 2        | 3      | 9.52%   |
| Samsung Electronics | 1        | 2      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 26     | 95.24%  |
| SSD  | 1        | 2      | 4.76%   |

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
| Detected | 115      | 226    | 63.19%  |
| Works    | 46       | 71     | 25.27%  |
| Malfunc  | 21       | 28     | 11.54%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 143      | 73.71%  |
| AMD                              | 16       | 8.25%   |
| Nvidia                           | 5        | 2.58%   |
| VIA Technologies                 | 4        | 2.06%   |
| Marvell Technology Group         | 4        | 2.06%   |
| ASMedia Technology               | 4        | 2.06%   |
| Samsung Electronics              | 3        | 1.55%   |
| JMicron Technology               | 3        | 1.55%   |
| Silicon Motion                   | 2        | 1.03%   |
| SanDisk                          | 2        | 1.03%   |
| Realtek Semiconductor            | 2        | 1.03%   |
| ULi Electronics                  | 1        | 0.52%   |
| Silicon Integrated Systems [SiS] | 1        | 0.52%   |
| Shenzhen Longsys Electronics     | 1        | 0.52%   |
| Phison Electronics               | 1        | 0.52%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.52%   |
| ADATA Technology                 | 1        | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 23       | 8.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 17       | 6.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 5.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 5.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12       | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12       | 4.63%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 3.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 3.09%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 3.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 2.7%    |
| Intel SATA Controller [RAID mode]                                                       | 6        | 2.32%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 2.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 2.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 1.93%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 1.54%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.54%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.54%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 3        | 1.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.16%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.16%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.16%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.16%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 2        | 0.77%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.77%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.77%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.77%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.77%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 2        | 0.77%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.77%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.77%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 106      | 54.64%  |
| IDE  | 67       | 34.54%  |
| NVMe | 12       | 6.19%   |
| RAID | 9        | 4.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 145      | 86.83%  |
| AMD    | 22       | 13.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 7        | 4.19%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 5        | 2.99%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 2.99%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4        | 2.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 2.4%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 2.4%    |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3        | 1.8%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 1.8%    |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 1.8%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.8%    |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3        | 1.8%    |
| Intel Core i3-4170 CPU @ 3.70GHz            | 3        | 1.8%    |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.8%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.8%    |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 1.2%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 1.2%    |
| Intel Pentium CPU G630 @ 2.70GHz            | 2        | 1.2%    |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 1.2%    |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 1.2%    |
| Intel Pentium CPU G3250 @ 3.20GHz           | 2        | 1.2%    |
| Intel Pentium CPU G2020 @ 2.90GHz           | 2        | 1.2%    |
| Intel Core i7-4820K CPU @ 3.70GHz           | 2        | 1.2%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.2%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.2%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.2%    |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.2%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.2%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 1.2%    |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.2%    |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.2%    |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.2%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.2%    |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 1.2%    |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 1.2%    |
| Intel 12th Gen Core i5-12400                | 2        | 1.2%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.2%    |
| AMD FX-6100 Six-Core Processor              | 2        | 1.2%    |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz         | 1        | 0.6%    |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz         | 1        | 0.6%    |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 38       | 22.75%  |
| Intel Core i7           | 25       | 14.97%  |
| Intel Core i3           | 20       | 11.98%  |
| Intel Pentium           | 14       | 8.38%   |
| Intel Core 2 Duo        | 14       | 8.38%   |
| Intel Pentium Dual-Core | 6        | 3.59%   |
| Intel Core 2 Quad       | 6        | 3.59%   |
| Intel Celeron           | 6        | 3.59%   |
| Other                   | 5        | 2.99%   |
| AMD FX                  | 4        | 2.4%    |
| Intel Xeon              | 3        | 1.8%    |
| Intel Pentium Dual      | 3        | 1.8%    |
| AMD Ryzen 7             | 3        | 1.8%    |
| AMD Ryzen 5             | 3        | 1.8%    |
| Intel Pentium 4         | 2        | 1.2%    |
| AMD PRO A10             | 2        | 1.2%    |
| AMD Athlon II X2        | 2        | 1.2%    |
| AMD Athlon 64 X2        | 2        | 1.2%    |
| AMD Athlon 64           | 2        | 1.2%    |
| Intel Pentium D         | 1        | 0.6%    |
| Intel Core i9           | 1        | 0.6%    |
| Intel Atom              | 1        | 0.6%    |
| AMD Phenom II X4        | 1        | 0.6%    |
| AMD E1                  | 1        | 0.6%    |
| AMD Athlon II X3        | 1        | 0.6%    |
| AMD Athlon              | 1        | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 66       | 39.52%  |
| 2      | 65       | 38.92%  |
| 6      | 14       | 8.38%   |
| 8      | 9        | 5.39%   |
| 1      | 7        | 4.19%   |
| 3      | 4        | 2.4%    |
| 24     | 1        | 0.6%    |
| 12     | 1        | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 166      | 99.4%   |
| 2      | 1        | 0.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 108      | 64.29%  |
| 2      | 60       | 35.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 164      | 97.62%  |
| 32-bit         | 2        | 1.19%   |
| Unknown        | 2        | 1.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 41       | 24.55%  |
| 0x306c3    | 18       | 10.78%  |
| 0x306a9    | 15       | 8.98%   |
| 0x1067a    | 15       | 8.98%   |
| 0x206a7    | 10       | 5.99%   |
| 0x506e3    | 8        | 4.79%   |
| 0x906e9    | 5        | 2.99%   |
| 0x906ed    | 4        | 2.4%    |
| 0x906ea    | 4        | 2.4%    |
| 0x6fd      | 4        | 2.4%    |
| 0x6fb      | 3        | 1.8%    |
| 0x010000c8 | 3        | 1.8%    |
| 0xa0653    | 2        | 1.2%    |
| 0x906eb    | 2        | 1.2%    |
| 0x90672    | 2        | 1.2%    |
| 0x306f2    | 2        | 1.2%    |
| 0x306e4    | 2        | 1.2%    |
| 0xf65      | 1        | 0.6%    |
| 0xf4a      | 1        | 0.6%    |
| 0xf49      | 1        | 0.6%    |
| 0xf41      | 1        | 0.6%    |
| 0xf33      | 1        | 0.6%    |
| 0xa0655    | 1        | 0.6%    |
| 0x906ec    | 1        | 0.6%    |
| 0x406f1    | 1        | 0.6%    |
| 0x30679    | 1        | 0.6%    |
| 0x30678    | 1        | 0.6%    |
| 0x30661    | 1        | 0.6%    |
| 0x20655    | 1        | 0.6%    |
| 0x20652    | 1        | 0.6%    |
| 0x106e5    | 1        | 0.6%    |
| 0x10676    | 1        | 0.6%    |
| 0x10661    | 1        | 0.6%    |
| 0x08701030 | 1        | 0.6%    |
| 0x0800820d | 1        | 0.6%    |
| 0x08001137 | 1        | 0.6%    |
| 0x08001129 | 1        | 0.6%    |
| 0x07030106 | 1        | 0.6%    |
| 0x0600611a | 1        | 0.6%    |
| 0x06003106 | 1        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 27       | 16.17%  |
| KabyLake         | 22       | 13.17%  |
| Penryn           | 21       | 12.57%  |
| IvyBridge        | 20       | 11.98%  |
| Skylake          | 12       | 7.19%   |
| SandyBridge      | 12       | 7.19%   |
| Core             | 9        | 5.39%   |
| NetBurst         | 5        | 2.99%   |
| K10              | 5        | 2.99%   |
| K8 Hammer        | 4        | 2.4%    |
| CometLake        | 4        | 2.4%    |
| Zen              | 3        | 1.8%    |
| Bulldozer        | 3        | 1.8%    |
| Alderlake Hybrid | 3        | 1.8%    |
| Zen+             | 2        | 1.2%    |
| Westmere         | 2        | 1.2%    |
| Silvermont       | 2        | 1.2%    |
| Nehalem          | 2        | 1.2%    |
| Unknown          | 2        | 1.2%    |
| Zen 2            | 1        | 0.6%    |
| Steamroller      | 1        | 0.6%    |
| Puma             | 1        | 0.6%    |
| Piledriver       | 1        | 0.6%    |
| Excavator        | 1        | 0.6%    |
| Broadwell        | 1        | 0.6%    |
| Bonnell          | 1        | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Nvidia               | 71       | 39.89%  |
| Intel                | 69       | 38.76%  |
| AMD                  | 35       | 19.66%  |
| VIA Technologies     | 1        | 0.56%   |
| Trident Microsystems | 1        | 0.56%   |
| ASPEED Technology    | 1        | 0.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14       | 7.87%   |
| Nvidia GT218 [GeForce 210]                                                  | 10       | 5.62%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 5.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 5.06%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 8        | 4.49%   |
| Intel HD Graphics 530                                                       | 6        | 3.37%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 3.37%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 2.81%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 2.25%   |
| Nvidia GF108 [GeForce GT 630]                                               | 4        | 2.25%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.69%   |
| Nvidia GF119 [GeForce GT 520]                                               | 3        | 1.69%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 3        | 1.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.69%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.12%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.12%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.12%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.12%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.12%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 1.12%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 1.12%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 1.12%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 2        | 1.12%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.12%   |
| Intel HD Graphics 630                                                       | 2        | 1.12%   |
| Intel HD Graphics 510                                                       | 2        | 1.12%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 1.12%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 1.12%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.12%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 2        | 1.12%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 0.56%   |
| Trident Microsystems XGI Volari XP5                                         | 1        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.56%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 63       | 37.5%   |
| 1 x Intel                | 60       | 35.71%  |
| 1 x AMD                  | 33       | 19.64%  |
| Intel + Nvidia           | 7        | 4.17%   |
| Intel + AMD              | 2        | 1.19%   |
| 1 x VIA                  | 1        | 0.6%    |
| 1 x Trident Microsystems | 1        | 0.6%    |
| Nvidia + ASPEED          | 1        | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 128      | 75.74%  |
| Proprietary | 33       | 19.53%  |
| Unknown     | 8        | 4.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 82       | 48.52%  |
| 1.01-2.0   | 30       | 17.75%  |
| 0.51-1.0   | 18       | 10.65%  |
| 0.01-0.5   | 16       | 9.47%   |
| 7.01-8.0   | 9        | 5.33%   |
| 3.01-4.0   | 8        | 4.73%   |
| 5.01-6.0   | 4        | 2.37%   |
| 8.01-16.0  | 2        | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 44       | 30.34%  |
| Samsung Electronics  | 42       | 28.97%  |
| Hewlett-Packard      | 9        | 6.21%   |
| Ancor Communications | 8        | 5.52%   |
| AOC                  | 6        | 4.14%   |
| LG Electronics       | 5        | 3.45%   |
| CHD                  | 5        | 3.45%   |
| Unknown              | 3        | 2.07%   |
| RTK                  | 3        | 2.07%   |
| Lenovo               | 3        | 2.07%   |
| Dell                 | 3        | 2.07%   |
| Sony                 | 2        | 1.38%   |
| MSI                  | 2        | 1.38%   |
| BenQ                 | 2        | 1.38%   |
| Acer                 | 2        | 1.38%   |
| XVision              | 1        | 0.69%   |
| Xiaomi               | 1        | 0.69%   |
| ViewSonic            | 1        | 0.69%   |
| Unknown (ADA)        | 1        | 0.69%   |
| SEEYOO               | 1        | 0.69%   |
| Hitachi              | 1        | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4        | 2.58%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch      | 4        | 2.58%   |
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch               | 4        | 2.58%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 3        | 1.94%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 3        | 1.94%   |
| Goldstar W2053 GSM4E9F 1600x900 443x249mm 20.0-inch                   | 3        | 1.94%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 2        | 1.29%   |
| Samsung Electronics LS27A70 SAM71A0 3840x2160 597x336mm 27.0-inch     | 2        | 1.29%   |
| Samsung Electronics C27FG70 SAM0DC9 1920x1080 598x337mm 27.0-inch     | 2        | 1.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 1.29%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 2        | 1.29%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 470x300mm 22.0-inch          | 2        | 1.29%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                   | 2        | 1.29%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch              | 2        | 1.29%   |
| Goldstar T730BH GSM43C2 1152x864 310x230mm 15.2-inch                  | 2        | 1.29%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 2        | 1.29%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 1.29%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2        | 1.29%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                   | 2        | 1.29%   |
| CHD 24VCF CHD0240 1920x1080 368x207mm 16.6-inch                       | 2        | 1.29%   |
| CHD 22MC625BF CHD0220 1920x1080 480x260mm 21.5-inch                   | 2        | 1.29%   |
| AOC 2240w AOC2240 1920x1080 477x268mm 21.5-inch                       | 2        | 1.29%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 2        | 1.29%   |
| XVision XL2020AI XVS0392 1600x900 600x340mm 27.2-inch                 | 1        | 0.65%   |
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                     | 1        | 0.65%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 1        | 0.65%   |
| Unknown LCD Monitor SYK VGA TO HDMI 1920x1080                         | 1        | 0.65%   |
| Unknown LCD Monitor SAMSUNG 2720x768                                  | 1        | 0.65%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.65%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.65%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1        | 0.65%   |
| Sony TV SNYA301 1920x1080                                             | 1        | 0.65%   |
| Sony TV SNY0902 1920x1080                                             | 1        | 0.65%   |
| SEEYOO 29XS440 SEE0032 1680x1050 640x384mm 29.4-inch                  | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0560 1440x900 408x255mm 18.9-inch   | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0378 1440x900 410x257mm 19.1-inch   | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0273 1440x900 410x257mm 19.1-inch   | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1        | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 60       | 41.67%  |
| 1600x900 (HD+)     | 18       | 12.5%   |
| 1366x768 (WXGA)    | 13       | 9.03%   |
| 1440x900 (WXGA+)   | 12       | 8.33%   |
| 1360x768           | 7        | 4.86%   |
| 1280x1024 (SXGA)   | 7        | 4.86%   |
| 3840x2160 (4K)     | 6        | 4.17%   |
| 1680x1050 (WSXGA+) | 6        | 4.17%   |
| 2560x1440 (QHD)    | 4        | 2.78%   |
| 2560x1080          | 3        | 2.08%   |
| 1280x960           | 2        | 1.39%   |
| Unknown            | 2        | 1.39%   |
| 2720x768           | 1        | 0.69%   |
| 1920x1200 (WUXGA)  | 1        | 0.69%   |
| 1280x800 (WXGA)    | 1        | 0.69%   |
| 1280x720 (HD)      | 1        | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 27       | 18.37%  |
| Unknown | 16       | 10.88%  |
| 20      | 14       | 9.52%   |
| 19      | 14       | 9.52%   |
| 18      | 14       | 9.52%   |
| 23      | 13       | 8.84%   |
| 27      | 9        | 6.12%   |
| 22      | 6        | 4.08%   |
| 24      | 5        | 3.4%    |
| 17      | 5        | 3.4%    |
| 46      | 3        | 2.04%   |
| 29      | 3        | 2.04%   |
| 16      | 3        | 2.04%   |
| 15      | 3        | 2.04%   |
| 72      | 2        | 1.36%   |
| 54      | 2        | 1.36%   |
| 84      | 1        | 0.68%   |
| 65      | 1        | 0.68%   |
| 50      | 1        | 0.68%   |
| 40      | 1        | 0.68%   |
| 32      | 1        | 0.68%   |
| 31      | 1        | 0.68%   |
| 26      | 1        | 0.68%   |
| 7       | 1        | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 72       | 49.66%  |
| 501-600     | 28       | 19.31%  |
| Unknown     | 16       | 11.03%  |
| 301-350     | 9        | 6.21%   |
| 1001-1500   | 7        | 4.83%   |
| 601-700     | 4        | 2.76%   |
| 351-400     | 3        | 2.07%   |
| 1501-2000   | 3        | 2.07%   |
| 801-900     | 1        | 0.69%   |
| 701-800     | 1        | 0.69%   |
| 101-200     | 1        | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 101      | 71.13%  |
| 16/10   | 16       | 11.27%  |
| Unknown | 14       | 9.86%   |
| 5/4     | 4        | 2.82%   |
| 4/3     | 4        | 2.82%   |
| 21/9    | 2        | 1.41%   |
| 3/2     | 1        | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 45       | 30.61%  |
| 151-200        | 33       | 22.45%  |
| 141-150        | 17       | 11.56%  |
| Unknown        | 16       | 10.88%  |
| 301-350        | 11       | 7.48%   |
| More than 1000 | 7        | 4.76%   |
| 501-1000       | 4        | 2.72%   |
| 351-500        | 3        | 2.04%   |
| 121-130        | 3        | 2.04%   |
| 251-300        | 2        | 1.36%   |
| 131-140        | 2        | 1.36%   |
| 101-110        | 2        | 1.36%   |
| 1-40           | 1        | 0.68%   |
| 111-120        | 1        | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 84       | 57.14%  |
| 101-120 | 35       | 23.81%  |
| Unknown | 16       | 10.88%  |
| 1-50    | 8        | 5.44%   |
| 161-240 | 3        | 2.04%   |
| 121-160 | 1        | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 138      | 82.14%  |
| 2     | 15       | 8.93%   |
| 0     | 15       | 8.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 103      | 40.08%  |
| Intel                                  | 45       | 17.51%  |
| Ralink Technology                      | 22       | 8.56%   |
| Qualcomm Atheros                       | 20       | 7.78%   |
| D-Link                                 | 12       | 4.67%   |
| Samsung Electronics                    | 10       | 3.89%   |
| VIA Technologies                       | 6        | 2.33%   |
| TP-Link                                | 6        | 2.33%   |
| Ralink                                 | 5        | 1.95%   |
| Nvidia                                 | 4        | 1.56%   |
| D-Link System                          | 4        | 1.56%   |
| Broadcom                               | 4        | 1.56%   |
| Xiaomi                                 | 2        | 0.78%   |
| Qualcomm Atheros Communications        | 2        | 0.78%   |
| Marvell Technology Group               | 2        | 0.78%   |
| ZyDAS                                  | 1        | 0.39%   |
| Tenda                                  | 1        | 0.39%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.39%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.39%   |
| Huawei Technologies                    | 1        | 0.39%   |
| Broadcom Limited                       | 1        | 0.39%   |
| ASUSTek Computer                       | 1        | 0.39%   |
| Aquantia                               | 1        | 0.39%   |
| Apple                                  | 1        | 0.39%   |
| AboCom Systems                         | 1        | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 87       | 31.64%  |
| Ralink MT7601U Wireless Adapter                                   | 15       | 5.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 2.91%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 7        | 2.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6        | 2.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 2.18%   |
| Ralink RT5370 Wireless Adapter                                    | 6        | 2.18%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 5        | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 1.82%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5        | 1.82%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 1.45%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.45%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3        | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.09%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                              | 3        | 1.09%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 3        | 1.09%   |
| Intel I211 Gigabit Network Connection                             | 3        | 1.09%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2        | 0.73%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 0.73%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.73%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.73%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.73%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.73%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.73%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.73%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.73%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.73%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.73%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 22       | 27.5%   |
| Realtek Semiconductor           | 17       | 21.25%  |
| D-Link                          | 12       | 15%     |
| TP-Link                         | 6        | 7.5%    |
| Ralink                          | 5        | 6.25%   |
| Qualcomm Atheros                | 5        | 6.25%   |
| Intel                           | 3        | 3.75%   |
| Qualcomm Atheros Communications | 2        | 2.5%    |
| D-Link System                   | 2        | 2.5%    |
| Broadcom                        | 2        | 2.5%    |
| ZyDAS                           | 1        | 1.25%   |
| Tenda                           | 1        | 1.25%   |
| Broadcom Limited                | 1        | 1.25%   |
| AboCom Systems                  | 1        | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                             | 15       | 18.52%  |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                              | 7        | 8.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 6        | 7.41%   |
| Ralink RT5370 Wireless Adapter                                              | 6        | 7.41%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 3        | 3.7%    |
| Ralink RT5360 Wireless 802.11n 1T/1R                                        | 3        | 3.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                            | 3        | 3.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 2        | 2.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 2        | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 2.47%   |
| Qualcomm Atheros AR9271 802.11n                                             | 2        | 2.47%   |
| Intel Alder Lake-S PCH CNVi WiFi                                            | 2        | 2.47%   |
| D-Link WLAN controller                                                      | 2        | 2.47%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]        | 2        | 2.47%   |
| ZyDAS ZD1211B 802.11g                                                       | 1        | 1.23%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                       | 1        | 1.23%   |
| TP-Link 802.11n NIC                                                         | 1        | 1.23%   |
| Tenda U12                                                                   | 1        | 1.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 1        | 1.23%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                             | 1        | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1        | 1.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1        | 1.23%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                   | 1        | 1.23%   |
| Realtek 802.11ac NIC                                                        | 1        | 1.23%   |
| Ralink RT2070 Wireless Adapter                                              | 1        | 1.23%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                        | 1        | 1.23%   |
| Ralink RT2561/RT61 802.11g PCI                                              | 1        | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1        | 1.23%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                  | 1        | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 1        | 1.23%   |
| D-Link DWA-182 Wireless AC Dualband Adapter(rev.C) [Realtek RTL8812AU]      | 1        | 1.23%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]               | 1        | 1.23%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS]     | 1        | 1.23%   |
| D-Link 11n Adapter                                                          | 1        | 1.23%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 1.23%   |
| Broadcom BCM43217 802.11b/g/n                                               | 1        | 1.23%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                           | 1        | 1.23%   |
| AboCom Systems AboCom Systems Inc [WN2001 Prolink Wireless-N Nano Adapter]  | 1        | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 97       | 50.79%  |
| Intel                                  | 44       | 23.04%  |
| Qualcomm Atheros                       | 16       | 8.38%   |
| Samsung Electronics                    | 10       | 5.24%   |
| VIA Technologies                       | 6        | 3.14%   |
| Nvidia                                 | 4        | 2.09%   |
| Xiaomi                                 | 2        | 1.05%   |
| Marvell Technology Group               | 2        | 1.05%   |
| D-Link System                          | 2        | 1.05%   |
| Broadcom                               | 2        | 1.05%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.52%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.52%   |
| Huawei Technologies                    | 1        | 0.52%   |
| ASUSTek Computer                       | 1        | 0.52%   |
| Aquantia                               | 1        | 0.52%   |
| Apple                                  | 1        | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 87       | 44.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 4.12%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6        | 3.09%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 5        | 2.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 2.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5        | 2.58%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.58%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 2.06%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 2.06%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.55%   |
| Intel I211 Gigabit Network Connection                             | 3        | 1.55%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.55%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2        | 1.03%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 1.03%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.03%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 1.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 1.03%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.03%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.03%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.03%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.03%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.03%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 1.03%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 1.03%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2        | 1.03%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.52%   |
| Sony Ericsson Mobile AB Xperia Z1                                 | 1        | 0.52%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.52%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.52%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.52%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.52%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.52%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.52%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 166      | 68.6%   |
| WiFi     | 76       | 31.4%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 105      | 65.22%  |
| WiFi     | 56       | 34.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 130      | 77.84%  |
| 2     | 30       | 17.96%  |
| 3     | 4        | 2.4%    |
| 8     | 1        | 0.6%    |
| 4     | 1        | 0.6%    |
| 0     | 1        | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 160      | 95.81%  |
| Yes  | 7        | 4.19%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Cambridge Silicon Radio    | 15       | 68.18%  |
| Intel                      | 3        | 13.64%  |
| ASUSTek Computer           | 2        | 9.09%   |
| ISSC                       | 1        | 4.55%   |
| Integrated System Solution | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15       | 68.18%  |
| Intel AX201 Bluetooth                               | 3        | 13.64%  |
| ASUS Bluetooth Radio                                | 2        | 9.09%   |
| ISSC Bluetooth Device                               | 1        | 4.55%   |
| Integrated System Solution Bluetooth Device         | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 139      | 54.51%  |
| Nvidia                           | 58       | 22.75%  |
| AMD                              | 41       | 16.08%  |
| C-Media Electronics              | 6        | 2.35%   |
| Generalplus Technology           | 2        | 0.78%   |
| Creative Labs                    | 2        | 0.78%   |
| VIA Technologies                 | 1        | 0.39%   |
| ULi Electronics                  | 1        | 0.39%   |
| Silicon Integrated Systems [SiS] | 1        | 0.39%   |
| Native Instruments               | 1        | 0.39%   |
| Jieli Technology                 | 1        | 0.39%   |
| Focusrite-Novation               | 1        | 0.39%   |
| ESS Technology                   | 1        | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 23       | 8.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 19       | 6.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 17       | 6.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 14       | 5.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 13       | 4.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12       | 4.32%   |
| Intel Cannon Lake PCH cAVS                                                        | 12       | 4.32%   |
| Nvidia High Definition Audio Controller                                           | 10       | 3.6%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 9        | 3.24%   |
| Nvidia GF108 High Definition Audio Controller                                     | 8        | 2.88%   |
| Intel 200 Series PCH HD Audio                                                     | 8        | 2.88%   |
| Nvidia GF119 HDMI Audio Controller                                                | 7        | 2.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 7        | 2.52%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 6        | 2.16%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5        | 1.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 1.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 1.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 5        | 1.8%    |
| Intel Alder Lake-S HD Audio Controller                                            | 4        | 1.44%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 1.44%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 4        | 1.44%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 1.08%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 1.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 1.08%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 3        | 1.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 1.08%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 0.72%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 0.72%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 0.72%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 0.72%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 0.72%   |
| Generalplus Technology USB Audio Device                                           | 2        | 0.72%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.72%   |
| AMD Kabini HDMI/DP Audio                                                          | 2        | 0.72%   |
| AMD FCH Azalia Controller                                                         | 2        | 0.72%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 13       | 17.57%  |
| Kingston            | 12       | 16.22%  |
| Crucial             | 7        | 9.46%   |
| GeIL                | 6        | 8.11%   |
| Corsair             | 6        | 8.11%   |
| SK hynix            | 5        | 6.76%   |
| Samsung Electronics | 4        | 5.41%   |
| Micron Technology   | 4        | 5.41%   |
| G.Skill             | 4        | 5.41%   |
| Apacer              | 4        | 5.41%   |
| Ramos Technology    | 2        | 2.7%    |
| Kingmax             | 2        | 2.7%    |
| Unknown (8A02)      | 1        | 1.35%   |
| TwinMOS             | 1        | 1.35%   |
| Nanya Technology    | 1        | 1.35%   |
| Elpida              | 1        | 1.35%   |
| Unknown             | 1        | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| GeIL RAM CL17-17-17 D4-2400 8GB DIMM DDR4 2400MT/s        | 4        | 4.71%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 2        | 2.35%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2        | 2.35%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s      | 2        | 2.35%   |
| Ramos RAM EWB4GB681PAE-16IC 4GB DIMM DDR3 1600MT/s        | 2        | 2.35%   |
| G.Skill RAM F4-3000C15-8GVRB 8GB DIMM DDR4 2933MT/s       | 2        | 2.35%   |
| Corsair RAM CMX8GX3M1A1600C11 8GB DIMM DDR3 1600MT/s      | 2        | 2.35%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s     | 2        | 2.35%   |
| Unknown RAM Module 4GB DIMM                               | 1        | 1.18%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1        | 1.18%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 1.18%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                   | 1        | 1.18%   |
| Unknown RAM Module 2GB DIMM 400MT/s                       | 1        | 1.18%   |
| Unknown RAM Module 2GB DIMM                               | 1        | 1.18%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s              | 1        | 1.18%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 1.18%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 1        | 1.18%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                   | 1        | 1.18%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s               | 1        | 1.18%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s | 1        | 1.18%   |
| Unknown (8A02) RAM DDR3 1333 8G 8GB DIMM DDR3 1333MT/s    | 1        | 1.18%   |
| TwinMOS RAM 9DSTBNZE-SATP 4GB DIMM DDR3 1333MT/s          | 1        | 1.18%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1        | 1.18%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 1.18%   |
| SK hynix RAM HMA84GR7MFR4N-TF 32GB DIMM DDR4 2133MT/s     | 1        | 1.18%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 1        | 1.18%   |
| Samsung RAM M393A2K43BB1-CTD 16GB DIMM DDR4 2667MT/s      | 1        | 1.18%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 1        | 1.18%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.18%   |
| Nanya RAM NT4GC64B8HG0NF-CG 4GB DIMM DDR3 1333MT/s        | 1        | 1.18%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s        | 1        | 1.18%   |
| Micron RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 1.18%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 1.18%   |
| Micron RAM 16ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s      | 1        | 1.18%   |
| Micron RAM 16ATF1G64AZ-2G1A2 8GB DIMM DDR4 2400MT/s       | 1        | 1.18%   |
| Kingston RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 1.18%   |
| Kingston RAM Module 4096MB DIMM DDR3 1400MT/s             | 1        | 1.18%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 1        | 1.18%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s       | 1        | 1.18%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 1        | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 28       | 44.44%  |
| DDR4    | 25       | 39.68%  |
| Unknown | 7        | 11.11%  |
| DDR5    | 1        | 1.59%   |
| DDR2    | 1        | 1.59%   |
| DDR     | 1        | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 62       | 98.41%  |
| SODIMM | 1        | 1.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 26       | 35.62%  |
| 4096  | 20       | 27.4%   |
| 2048  | 13       | 17.81%  |
| 16384 | 12       | 16.44%  |
| 32768 | 1        | 1.37%   |
| 1024  | 1        | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 15       | 21.74%  |
| 2400    | 11       | 15.94%  |
| 1333    | 11       | 15.94%  |
| 3200    | 5        | 7.25%   |
| 2667    | 4        | 5.8%    |
| 2133    | 4        | 5.8%    |
| 800     | 4        | 5.8%    |
| 2933    | 2        | 2.9%    |
| 4800    | 1        | 1.45%   |
| 3600    | 1        | 1.45%   |
| 3066    | 1        | 1.45%   |
| 2800    | 1        | 1.45%   |
| 2666    | 1        | 1.45%   |
| 1867    | 1        | 1.45%   |
| 1866    | 1        | 1.45%   |
| 1800    | 1        | 1.45%   |
| 1400    | 1        | 1.45%   |
| 1328    | 1        | 1.45%   |
| 533     | 1        | 1.45%   |
| 400     | 1        | 1.45%   |
| Unknown | 1        | 1.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 3        | 60%     |
| Samsung Electronics | 1        | 20%     |
| Hewlett-Packard     | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung ML-1640 Series Laser Printer | 1        | 20%     |
| HP LaserJet 1018                     | 1        | 20%     |
| Canon PIXMA MG5600 Series            | 1        | 20%     |
| Canon LBP6300                        | 1        | 20%     |
| Canon iR2004/2204 UFRII LT           | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Apple                       | 4        | 33.33%  |
| Samsung Electronics         | 2        | 16.67%  |
| Realtek Semiconductor       | 1        | 8.33%   |
| Pixart Imaging              | 1        | 8.33%   |
| Microdia                    | 1        | 8.33%   |
| MacroSilicon                | 1        | 8.33%   |
| KYE Systems (Mouse Systems) | 1        | 8.33%   |
| Generalplus Technology      | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 4        | 33.33%  |
| Samsung Galaxy series, misc. (MTP mode)       | 2        | 16.67%  |
| Realtek Full HD webcam                        | 1        | 8.33%   |
| Pixart Imaging Multimedia audio controller    | 1        | 8.33%   |
| Microdia Rapoo camera                         | 1        | 8.33%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 8.33%   |
| KYE Systems (Mouse Systems) FaceCam 311       | 1        | 8.33%   |
| Generalplus GENERAL WEBCAM                    | 1        | 8.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Suprema | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader | 1        | 100%    |

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
| 0     | 136      | 80%     |
| 1     | 28       | 16.47%  |
| 2     | 4        | 2.35%   |
| 3     | 2        | 1.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 15       | 38.46%  |
| Net/wireless             | 10       | 25.64%  |
| Communication controller | 7        | 17.95%  |
| Unassigned class         | 3        | 7.69%   |
| Multimedia controller    | 2        | 5.13%   |
| Sound                    | 1        | 2.56%   |
| Fingerprint reader       | 1        | 2.56%   |

