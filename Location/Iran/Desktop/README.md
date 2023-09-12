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

Total: 230

| Vendor   | Model                   | Probe                                                      | Date         |
|----------|-------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 33       | 20%     |
| Ubuntu 18.04       | 26       | 15.76%  |
| Ubuntu 22.04       | 10       | 6.06%   |
| Ubuntu 19.04       | 6        | 3.64%   |
| Arch               | 5        | 3.03%   |
| Xubuntu 18.04      | 4        | 2.42%   |
| Linux Mint 21.1    | 4        | 2.42%   |
| Linux Mint 20.3    | 4        | 2.42%   |
| Arch Rolling       | 4        | 2.42%   |
| Ubuntu 23.04       | 3        | 1.82%   |
| Ubuntu 20.10       | 3        | 1.82%   |
| OpenMandriva 4.2   | 3        | 1.82%   |
| KDE neon 20.04     | 3        | 1.82%   |
| Debian 11          | 3        | 1.82%   |
| Zorin 15           | 2        | 1.21%   |
| Xubuntu 20.04      | 2        | 1.21%   |
| Ubuntu 21.10       | 2        | 1.21%   |
| Ubuntu 19.10       | 2        | 1.21%   |
| OpenMandriva 4.3   | 2        | 1.21%   |
| Linux Mint 20.1    | 2        | 1.21%   |
| Linux Mint 20      | 2        | 1.21%   |
| Kubuntu 22.04      | 2        | 1.21%   |
| Elementary 6.1     | 2        | 1.21%   |
| Xubuntu 22.04      | 1        | 0.61%   |
| Ubuntu Unity 16.04 | 1        | 0.61%   |
| Ubuntu 22.10       | 1        | 0.61%   |
| Solus 4.3          | 1        | 0.61%   |
| ROSA R10           | 1        | 0.61%   |
| Pop!_OS 21.04      | 1        | 0.61%   |
| Pop!_OS 20.10      | 1        | 0.61%   |
| Pop!_OS 20.04      | 1        | 0.61%   |
| OpenMandriva 23.03 | 1        | 0.61%   |
| Manjaro 23.0.0     | 1        | 0.61%   |
| Manjaro 22.0.0     | 1        | 0.61%   |
| Manjaro 21.3.7     | 1        | 0.61%   |
| Manjaro 21.3.4     | 1        | 0.61%   |
| Manjaro 21.2.6     | 1        | 0.61%   |
| Manjaro 18.0.4     | 1        | 0.61%   |
| Manjaro            | 1        | 0.61%   |
| Lubuntu 22.04      | 1        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 85       | 52.47%  |
| Linux Mint   | 12       | 7.41%   |
| Arch         | 9        | 5.56%   |
| Xubuntu      | 7        | 4.32%   |
| Manjaro      | 7        | 4.32%   |
| Fedora       | 7        | 4.32%   |
| OpenMandriva | 6        | 3.7%    |
| KDE neon     | 4        | 2.47%   |
| Debian       | 4        | 2.47%   |
| Pop!_OS      | 3        | 1.85%   |
| Zorin        | 2        | 1.23%   |
| Lubuntu      | 2        | 1.23%   |
| Kubuntu      | 2        | 1.23%   |
| Kali         | 2        | 1.23%   |
| Endless      | 2        | 1.23%   |
| Elementary   | 2        | 1.23%   |
| Ubuntu Unity | 1        | 0.62%   |
| Solus        | 1        | 0.62%   |
| ROSA         | 1        | 0.62%   |
| CentOS       | 1        | 0.62%   |
| Artix        | 1        | 0.62%   |
| ArcoLinux    | 1        | 0.62%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-48-generic         | 4        | 2.3%    |
| 6.2.0-20-generic         | 3        | 1.72%   |
| 5.4.0-58-generic         | 3        | 1.72%   |
| 5.4.0-42-generic         | 3        | 1.72%   |
| 5.3.0-40-generic         | 3        | 1.72%   |
| 5.15.0-47-generic        | 3        | 1.72%   |
| 5.11.0-27-generic        | 3        | 1.72%   |
| 5.10.14-desktop-1omv4002 | 3        | 1.72%   |
| 5.8.0-50-generic         | 2        | 1.15%   |
| 5.8.0-44-generic         | 2        | 1.15%   |
| 5.4.0-52-generic         | 2        | 1.15%   |
| 5.4.0-37-generic         | 2        | 1.15%   |
| 5.4.0-26-generic         | 2        | 1.15%   |
| 5.19.0-46-generic        | 2        | 1.15%   |
| 5.19.0                   | 2        | 1.15%   |
| 5.16.7-desktop-1omv4003  | 2        | 1.15%   |
| 5.15.0-58-generic        | 2        | 1.15%   |
| 5.15.0-56-generic        | 2        | 1.15%   |
| 5.13.0-30-generic        | 2        | 1.15%   |
| 5.11.0-41-generic        | 2        | 1.15%   |
| 5.11.0-37-generic        | 2        | 1.15%   |
| 5.0.0-38-generic         | 2        | 1.15%   |
| 5.0.0-37-generic         | 2        | 1.15%   |
| 5.0.0-25-generic         | 2        | 1.15%   |
| 5.0.0-23-generic         | 2        | 1.15%   |
| 4.15.0-88-generic        | 2        | 1.15%   |
| 4.15.0-50-generic        | 2        | 1.15%   |
| 4.15.0-29-generic        | 2        | 1.15%   |
| 6.4.3-arch1-1            | 1        | 0.57%   |
| 6.4.11-060411-generic    | 1        | 0.57%   |
| 6.3.12-200.fc38.x86_64   | 1        | 0.57%   |
| 6.2.8-arch1-1            | 1        | 0.57%   |
| 6.2.6-desktop-1omv2390   | 1        | 0.57%   |
| 6.2.12-arch1-1           | 1        | 0.57%   |
| 6.2.0-31-generic         | 1        | 0.57%   |
| 6.0.0                    | 1        | 0.57%   |
| 5.9.4-arch1-1            | 1        | 0.57%   |
| 5.9.12-arch1-1           | 1        | 0.57%   |
| 5.8.9-200.fc32.x86_64    | 1        | 0.57%   |
| 5.8.8-arch1-1            | 1        | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 18.93%  |
| 5.15.0  | 14       | 8.28%   |
| 4.15.0  | 14       | 8.28%   |
| 5.0.0   | 12       | 7.1%    |
| 5.11.0  | 11       | 6.51%   |
| 5.8.0   | 10       | 5.92%   |
| 5.13.0  | 10       | 5.92%   |
| 5.3.0   | 9        | 5.33%   |
| 5.19.0  | 5        | 2.96%   |
| 4.18.0  | 5        | 2.96%   |
| 6.2.0   | 4        | 2.37%   |
| 5.10.14 | 3        | 1.78%   |
| 5.16.7  | 2        | 1.18%   |
| 5.10.0  | 2        | 1.18%   |
| 6.4.3   | 1        | 0.59%   |
| 6.4.11  | 1        | 0.59%   |
| 6.3.12  | 1        | 0.59%   |
| 6.2.8   | 1        | 0.59%   |
| 6.2.6   | 1        | 0.59%   |
| 6.2.12  | 1        | 0.59%   |
| 6.0.0   | 1        | 0.59%   |
| 5.9.4   | 1        | 0.59%   |
| 5.9.12  | 1        | 0.59%   |
| 5.8.9   | 1        | 0.59%   |
| 5.8.8   | 1        | 0.59%   |
| 5.8.18  | 1        | 0.59%   |
| 5.8.12  | 1        | 0.59%   |
| 5.7.7   | 1        | 0.59%   |
| 5.7.6   | 1        | 0.59%   |
| 5.6.13  | 1        | 0.59%   |
| 5.18.0  | 1        | 0.59%   |
| 5.17.0  | 1        | 0.59%   |
| 5.16.4  | 1        | 0.59%   |
| 5.16.0  | 1        | 0.59%   |
| 5.15.60 | 1        | 0.59%   |
| 5.15.55 | 1        | 0.59%   |
| 5.15.48 | 1        | 0.59%   |
| 5.15.41 | 1        | 0.59%   |
| 5.15.38 | 1        | 0.59%   |
| 5.15.2  | 1        | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 19.05%  |
| 5.15    | 20       | 11.9%   |
| 5.8     | 14       | 8.33%   |
| 4.15    | 14       | 8.33%   |
| 5.0     | 13       | 7.74%   |
| 5.13    | 11       | 6.55%   |
| 5.11    | 11       | 6.55%   |
| 5.3     | 9        | 5.36%   |
| 6.2     | 7        | 4.17%   |
| 5.10    | 7        | 4.17%   |
| 5.19    | 5        | 2.98%   |
| 4.18    | 5        | 2.98%   |
| 5.16    | 4        | 2.38%   |
| 6.4     | 2        | 1.19%   |
| 5.9     | 2        | 1.19%   |
| 5.7     | 2        | 1.19%   |
| 6.3     | 1        | 0.6%    |
| 6.0     | 1        | 0.6%    |
| 5.6     | 1        | 0.6%    |
| 5.18    | 1        | 0.6%    |
| 5.17    | 1        | 0.6%    |
| 5.14    | 1        | 0.6%    |
| 5.12    | 1        | 0.6%    |
| 4.9     | 1        | 0.6%    |
| 4.19    | 1        | 0.6%    |
| 4.14    | 1        | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 149      | 94.9%   |
| i686   | 8        | 5.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 91       | 55.49%  |
| Unknown    | 20       | 12.2%   |
| KDE5       | 17       | 10.37%  |
| XFCE       | 15       | 9.15%   |
| X-Cinnamon | 9        | 5.49%   |
| i3         | 3        | 1.83%   |
| Pantheon   | 2        | 1.22%   |
| LXQt       | 2        | 1.22%   |
| Unity      | 1        | 0.61%   |
| LXDE       | 1        | 0.61%   |
| KDE        | 1        | 0.61%   |
| Cinnamon   | 1        | 0.61%   |
| Budgie     | 1        | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 126      | 77.78%  |
| Wayland | 19       | 11.73%  |
| Unknown | 15       | 9.26%   |
| Tty     | 2        | 1.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 92       | 56.79%  |
| GDM3    | 20       | 12.35%  |
| LightDM | 17       | 10.49%  |
| GDM     | 16       | 9.88%   |
| SDDM    | 14       | 8.64%   |
| TDM     | 3        | 1.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 126      | 78.75%  |
| Unknown | 20       | 12.5%   |
| fa_IR   | 5        | 3.13%   |
| en_GB   | 5        | 3.13%   |
| en_CA   | 2        | 1.25%   |
| C       | 2        | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 95       | 60.51%  |
| EFI  | 62       | 39.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 138      | 86.79%  |
| Overlay | 9        | 5.66%   |
| Tmpfs   | 4        | 2.52%   |
| Unknown | 4        | 2.52%   |
| Btrfs   | 3        | 1.89%   |
| Xfs     | 1        | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 107      | 66.88%  |
| GPT     | 41       | 25.63%  |
| MBR     | 12       | 7.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 136      | 84.47%  |
| Yes       | 25       | 15.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 55%     |
| Yes       | 72       | 45%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 75       | 47.77%  |
| Gigabyte Technology | 35       | 22.29%  |
| Hewlett-Packard     | 18       | 11.46%  |
| MSI                 | 6        | 3.82%   |
| ECS                 | 6        | 3.82%   |
| ASRock              | 5        | 3.18%   |
| Unknown             | 3        | 1.91%   |
| YANYU               | 2        | 1.27%   |
| Lenovo              | 2        | 1.27%   |
| Biostar             | 2        | 1.27%   |
| Intel               | 1        | 0.64%   |
| Foxconn             | 1        | 0.64%   |
| Dell                | 1        | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 13       | 8.28%   |
| HP Compaq Elite 8300 SFF       | 7        | 4.46%   |
| ASUS P5P41T-LE                 | 3        | 1.91%   |
| Unknown                        | 3        | 1.91%   |
| HP ProDesk 600 G1 SFF          | 2        | 1.27%   |
| HP EliteDesk 800 G2 SFF        | 2        | 1.27%   |
| Gigabyte H81M-S2PV             | 2        | 1.27%   |
| Gigabyte EP41-UD3L             | 2        | 1.27%   |
| ASUS Z10PE-D16 WS              | 2        | 1.27%   |
| ASUS TUF B360-PLUS GAMING      | 2        | 1.27%   |
| ASUS PRIME Z390-P              | 2        | 1.27%   |
| ASUS PRIME H610M-A WIFI D4     | 2        | 1.27%   |
| ASUS PRIME H310-PLUS R2.0      | 2        | 1.27%   |
| ASUS PRIME H310-PLUS           | 2        | 1.27%   |
| ASUS P9X79 LE                  | 2        | 1.27%   |
| ASUS P8H61                     | 2        | 1.27%   |
| ASUS H61M-C                    | 2        | 1.27%   |
| YANYU M9F baytrail             | 1        | 0.64%   |
| YANYU ITX-S192                 | 1        | 0.64%   |
| MSI MS-7A74                    | 1        | 0.64%   |
| MSI MS-7A39                    | 1        | 0.64%   |
| MSI MS-7817                    | 1        | 0.64%   |
| MSI MS-7693                    | 1        | 0.64%   |
| MSI MS-7673                    | 1        | 0.64%   |
| MSI MS-7623                    | 1        | 0.64%   |
| Lenovo ThinkCentre M58 8910ASU | 1        | 0.64%   |
| Lenovo ThinkCentre M58 7360EHU | 1        | 0.64%   |
| Intel P61-S3                   | 1        | 0.64%   |
| HP Z440 Workstation            | 1        | 0.64%   |
| HP Z2 SFF G4 Workstation       | 1        | 0.64%   |
| HP ProDesk 400 G2 MINI         | 1        | 0.64%   |
| HP EliteDesk 705 G2 SFF        | 1        | 0.64%   |
| HP Compaq 8000 Elite SFF PC    | 1        | 0.64%   |
| HP Compaq 6000 Pro SFF PC      | 1        | 0.64%   |
| HP 700-270jp                   | 1        | 0.64%   |
| Gigabyte Z97X-Gaming 3         | 1        | 0.64%   |
| Gigabyte Z68P-DS3              | 1        | 0.64%   |
| Gigabyte Z390 GAMING X         | 1        | 0.64%   |
| Gigabyte P75-D3                | 1        | 0.64%   |
| Gigabyte P55A-UD3P             | 1        | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 18       | 11.46%  |
| ASUS All             | 13       | 8.28%   |
| HP Compaq            | 9        | 5.73%   |
| ASUS TUF             | 5        | 3.18%   |
| HP ProDesk           | 3        | 1.91%   |
| HP EliteDesk         | 3        | 1.91%   |
| ASUS P5P41T-LE       | 3        | 1.91%   |
| Unknown              | 3        | 1.91%   |
| Lenovo ThinkCentre   | 2        | 1.27%   |
| Gigabyte H81M-S2PV   | 2        | 1.27%   |
| Gigabyte EP41-UD3L   | 2        | 1.27%   |
| ASUS Z10PE-D16       | 2        | 1.27%   |
| ASUS P9X79           | 2        | 1.27%   |
| ASUS P8Z77-V         | 2        | 1.27%   |
| ASUS P8H61           | 2        | 1.27%   |
| ASUS H61M-C          | 2        | 1.27%   |
| ASUS H110M-C         | 2        | 1.27%   |
| YANYU M9F            | 1        | 0.64%   |
| YANYU ITX-S192       | 1        | 0.64%   |
| MSI MS-7A74          | 1        | 0.64%   |
| MSI MS-7A39          | 1        | 0.64%   |
| MSI MS-7817          | 1        | 0.64%   |
| MSI MS-7693          | 1        | 0.64%   |
| MSI MS-7673          | 1        | 0.64%   |
| MSI MS-7623          | 1        | 0.64%   |
| Intel P61-S3         | 1        | 0.64%   |
| HP Z440              | 1        | 0.64%   |
| HP Z2                | 1        | 0.64%   |
| HP 700-270jp         | 1        | 0.64%   |
| Gigabyte Z97X-Gaming | 1        | 0.64%   |
| Gigabyte Z68P-DS3    | 1        | 0.64%   |
| Gigabyte Z390        | 1        | 0.64%   |
| Gigabyte P75-D3      | 1        | 0.64%   |
| Gigabyte P55A-UD3P   | 1        | 0.64%   |
| Gigabyte P55-USB3    | 1        | 0.64%   |
| Gigabyte P41T-D3P    | 1        | 0.64%   |
| Gigabyte P31-ES3G    | 1        | 0.64%   |
| Gigabyte M52S-S3P    | 1        | 0.64%   |
| Gigabyte M1689D      | 1        | 0.64%   |
| Gigabyte H81M-S2PH   | 1        | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 20       | 12.74%  |
| 2012 | 17       | 10.83%  |
| 2009 | 16       | 10.19%  |
| 2018 | 12       | 7.64%   |
| 2016 | 12       | 7.64%   |
| 2011 | 12       | 7.64%   |
| 2014 | 9        | 5.73%   |
| 2020 | 8        | 5.1%    |
| 2015 | 8        | 5.1%    |
| 2010 | 7        | 4.46%   |
| 2008 | 7        | 4.46%   |
| 2007 | 7        | 4.46%   |
| 2017 | 6        | 3.82%   |
| 2006 | 5        | 3.18%   |
| 2021 | 4        | 2.55%   |
| 2022 | 2        | 1.27%   |
| 2019 | 2        | 1.27%   |
| 2005 | 2        | 1.27%   |
| 2004 | 1        | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 157      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 152      | 96.82%  |
| Enabled  | 5        | 3.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 157      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 36       | 22.78%  |
| 4.01-8.0    | 35       | 22.15%  |
| 8.01-16.0   | 33       | 20.89%  |
| 3.01-4.0    | 31       | 19.62%  |
| 32.01-64.0  | 9        | 5.7%    |
| 1.01-2.0    | 7        | 4.43%   |
| 2.01-3.0    | 4        | 2.53%   |
| 64.01-256.0 | 2        | 1.27%   |
| 0.51-1.0    | 1        | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 74       | 43.27%  |
| 2.01-3.0   | 48       | 28.07%  |
| 3.01-4.0   | 17       | 9.94%   |
| 4.01-8.0   | 12       | 7.02%   |
| 0.51-1.0   | 9        | 5.26%   |
| 8.01-16.0  | 6        | 3.51%   |
| 0.01-0.5   | 4        | 2.34%   |
| 24.01-32.0 | 1        | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 77       | 47.83%  |
| 2      | 57       | 35.4%   |
| 3      | 17       | 10.56%  |
| 4      | 7        | 4.35%   |
| 5      | 2        | 1.24%   |
| 6      | 1        | 0.62%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 50.93%  |
| Yes       | 79       | 49.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 156      | 99.36%  |
| No        | 1        | 0.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 57.41%  |
| Yes       | 69       | 42.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 138      | 86.79%  |
| Yes       | 21       | 13.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Iran    | 157      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Tehran                    | 92       | 54.76%  |
| TehrДЃn                 | 11       | 6.55%   |
| Shiraz                    | 6        | 3.57%   |
| Isfahan                   | 6        | 3.57%   |
| Tajrish                   | 3        | 1.79%   |
| Sanandij                  | 3        | 1.79%   |
| Karaj                     | 3        | 1.79%   |
| Rey                       | 2        | 1.19%   |
| Rehnān                   | 2        | 1.19%   |
| Qom                       | 2        | 1.19%   |
| Mashhad                   | 2        | 1.19%   |
| Kerman                    | 2        | 1.19%   |
| Hamadan                   | 2        | 1.19%   |
| Arak                      | 2        | 1.19%   |
| Yazd                      | 1        | 0.6%    |
| Tīrān                   | 1        | 0.6%    |
| Siakhdekhan               | 1        | 0.6%    |
| Shahrak-e KÅ«lÅ«rÄ« | 1        | 0.6%    |
| Shaft                     | 1        | 0.6%    |
| Saveh                     | 1        | 0.6%    |
| Ramsar                    | 1        | 0.6%    |
| PДЃkdasht               | 1        | 0.6%    |
| Naz̧arābād             | 1        | 0.6%    |
| NajafÄbÄd           | 1        | 0.6%    |
| Khorramabad               | 1        | 0.6%    |
| KhondДЃb                | 1        | 0.6%    |
| Kermanshah                | 1        | 0.6%    |
| Kāshān                  | 1        | 0.6%    |
| KahrД«z                 | 1        | 0.6%    |
| JongД«yeh               | 1        | 0.6%    |
| JavДЃnrЕ«d            | 1        | 0.6%    |
| Farsan                    | 1        | 0.6%    |
| FalÄvarjÄn          | 1        | 0.6%    |
| DorЕ«d                  | 1        | 0.6%    |
| Dezful                    | 1        | 0.6%    |
| DamДЃvand               | 1        | 0.6%    |
| BorЕ«jerd               | 1        | 0.6%    |
| Behshahr                  | 1        | 0.6%    |
| Behbahan                  | 1        | 0.6%    |
| Bahar                     | 1        | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 74       | 105    | 30.96%  |
| Seagate               | 41       | 45     | 17.15%  |
| Samsung Electronics   | 22       | 33     | 9.21%   |
| Maxtor                | 21       | 28     | 8.79%   |
| A-DATA Technology     | 17       | 19     | 7.11%   |
| Toshiba               | 15       | 18     | 6.28%   |
| Lexar                 | 7        | 7      | 2.93%   |
| Kingston              | 6        | 8      | 2.51%   |
| SPCC                  | 5        | 6      | 2.09%   |
| SanDisk               | 4        | 4      | 1.67%   |
| Hitachi               | 4        | 5      | 1.67%   |
| Unknown               | 3        | 3      | 1.26%   |
| Intel                 | 3        | 3      | 1.26%   |
| Silicon Motion        | 2        | 2      | 0.84%   |
| Realtek Semiconductor | 2        | 3      | 0.84%   |
| Team                  | 1        | 1      | 0.42%   |
| Plextor               | 1        | 1      | 0.42%   |
| Pioneer               | 1        | 1      | 0.42%   |
| Phison Electronics    | 1        | 1      | 0.42%   |
| Patriot               | 1        | 1      | 0.42%   |
| OSCOO                 | 1        | 2      | 0.42%   |
| OCZ                   | 1        | 1      | 0.42%   |
| Kingmax               | 1        | 1      | 0.42%   |
| HPE                   | 1        | 1      | 0.42%   |
| Gigabyte Technology   | 1        | 1      | 0.42%   |
| BR                    | 1        | 1      | 0.42%   |
| Apacer                | 1        | 1      | 0.42%   |
| AMD                   | 1        | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB             | 15       | 5.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 6        | 2.26%   |
| Seagate ST500DM002-1BD142 500GB      | 6        | 2.26%   |
| Maxtor STM3250310AS 250GB            | 6        | 2.26%   |
| WDC WD10EZRX-00L4HB0 1TB             | 4        | 1.5%    |
| Lexar 256GB SSD                      | 4        | 1.5%    |
| WDC WD5000AZRX-00A8LB0 500GB         | 3        | 1.13%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 3        | 1.13%   |
| WDC WD10EARS-00MVWB0 1TB             | 3        | 1.13%   |
| Toshiba DT01ACA100 1TB               | 3        | 1.13%   |
| Toshiba DT01ACA050 500GB             | 3        | 1.13%   |
| SPCC Solid State Disk 128GB          | 3        | 1.13%   |
| Seagate ST3500413AS 500GB            | 3        | 1.13%   |
| Seagate ST1000DM003-9YN162 1TB       | 3        | 1.13%   |
| Samsung SSD 850 EVO 250GB            | 3        | 1.13%   |
| Maxtor STM3160215AS 160GB            | 3        | 1.13%   |
| Maxtor 6Y080L0 82GB                  | 3        | 1.13%   |
| A-DATA SU630 240GB SSD               | 3        | 1.13%   |
| WDC WD5000AZRX-00L4HB0 500GB         | 2        | 0.75%   |
| WDC WD5000AZLX-60K2TA0 500GB         | 2        | 0.75%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 2        | 0.75%   |
| WDC WD40EZRZ-00GXCB0 4TB             | 2        | 0.75%   |
| WDC WD40EZAZ-00SF3B0 4TB             | 2        | 0.75%   |
| WDC WD20EZRX-00D8PB0 2TB             | 2        | 0.75%   |
| WDC WD20EARX-00PASB0 2TB             | 2        | 0.75%   |
| WDC WD10PURZ-85U8XY0 1TB             | 2        | 0.75%   |
| WDC WD10EZEX-00WN4A0 1TB             | 2        | 0.75%   |
| WDC WD10EURX-63C57Y0 1TB             | 2        | 0.75%   |
| WDC WD10EARX-00N0YB0 1TB             | 2        | 0.75%   |
| Toshiba MQ01ABF050 500GB             | 2        | 0.75%   |
| SPCC Solid State Disk 120GB          | 2        | 0.75%   |
| Seagate ST3500418AS 500GB            | 2        | 0.75%   |
| Seagate ST3320613AS 320GB            | 2        | 0.75%   |
| Seagate ST3250318AS 250GB            | 2        | 0.75%   |
| Seagate ST1000DL002-9TT153 1TB       | 2        | 0.75%   |
| Seagate Backup+ Hub BK 8TB           | 2        | 0.75%   |
| Sandisk WDC WDS240G2G0C-00AJM0 240GB | 2        | 0.75%   |
| Samsung HD502HI 500GB                | 2        | 0.75%   |
| Samsung HD321HJ 320GB                | 2        | 0.75%   |
| Samsung HD160JJ 160GB                | 2        | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 69       | 95     | 43.4%   |
| Seagate             | 41       | 45     | 25.79%  |
| Maxtor              | 21       | 28     | 13.21%  |
| Toshiba             | 15       | 18     | 9.43%   |
| Samsung Electronics | 7        | 11     | 4.4%    |
| Hitachi             | 4        | 5      | 2.52%   |
| Unknown             | 1        | 1      | 0.63%   |
| HPE                 | 1        | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| A-DATA Technology   | 17       | 19     | 23.29%  |
| Samsung Electronics | 14       | 18     | 19.18%  |
| WDC                 | 10       | 10     | 13.7%   |
| Lexar               | 6        | 6      | 8.22%   |
| Kingston            | 6        | 8      | 8.22%   |
| SPCC                | 5        | 6      | 6.85%   |
| SanDisk             | 2        | 2      | 2.74%   |
| Intel               | 2        | 2      | 2.74%   |
| Team                | 1        | 1      | 1.37%   |
| Plextor             | 1        | 1      | 1.37%   |
| Pioneer             | 1        | 1      | 1.37%   |
| Patriot             | 1        | 1      | 1.37%   |
| OSCOO               | 1        | 2      | 1.37%   |
| OCZ                 | 1        | 1      | 1.37%   |
| Kingmax             | 1        | 1      | 1.37%   |
| Gigabyte Technology | 1        | 1      | 1.37%   |
| BR                  | 1        | 1      | 1.37%   |
| Apacer              | 1        | 1      | 1.37%   |
| AMD                 | 1        | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 134      | 204    | 63.21%  |
| SSD     | 67       | 83     | 31.6%   |
| NVMe    | 10       | 15     | 4.72%   |
| Unknown | 1        | 1      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 154      | 283    | 91.12%  |
| NVMe | 10       | 15     | 5.92%   |
| SAS  | 5        | 5      | 2.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 119      | 176    | 57.49%  |
| 0.51-1.0   | 61       | 81     | 29.47%  |
| 1.01-2.0   | 11       | 11     | 5.31%   |
| 3.01-4.0   | 7        | 7      | 3.38%   |
| 2.01-3.0   | 4        | 5      | 1.93%   |
| 4.01-10.0  | 4        | 4      | 1.93%   |
| 10.01-20.0 | 1        | 3      | 0.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 41       | 24.85%  |
| 501-1000       | 33       | 20%     |
| 251-500        | 30       | 18.18%  |
| 1001-2000      | 16       | 9.7%    |
| 51-100         | 13       | 7.88%   |
| More than 3000 | 9        | 5.45%   |
| 21-50          | 7        | 4.24%   |
| 2001-3000      | 7        | 4.24%   |
| 1-20           | 7        | 4.24%   |
| Unknown        | 2        | 1.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 58       | 34.32%  |
| 21-50          | 23       | 13.61%  |
| 101-250        | 23       | 13.61%  |
| 51-100         | 23       | 13.61%  |
| 251-500        | 14       | 8.28%   |
| 501-1000       | 14       | 8.28%   |
| More than 3000 | 5        | 2.96%   |
| 1001-2000      | 5        | 2.96%   |
| 2001-3000      | 2        | 1.18%   |
| Unknown        | 2        | 1.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 2      | 5.56%   |
| WDC WD3200AVVS-62L2B0 320GB         | 1        | 1      | 5.56%   |
| WDC WD10PURZ-85U8XY0 1TB            | 1        | 1      | 5.56%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 1      | 5.56%   |
| WDC WD10EARX-00N0YB0 1TB            | 1        | 1      | 5.56%   |
| WDC WD10EARS-00MVWB0 1TB            | 1        | 1      | 5.56%   |
| WDC WD1002FBYS-18A6B0 1TB           | 1        | 1      | 5.56%   |
| Toshiba MQ01ABF050 500GB            | 1        | 1      | 5.56%   |
| Toshiba HDWD105 500GB               | 1        | 1      | 5.56%   |
| Seagate ST9500420AS 500GB           | 1        | 1      | 5.56%   |
| Seagate ST3500413AS 500GB           | 1        | 1      | 5.56%   |
| Seagate ST3320613AS 320GB           | 1        | 1      | 5.56%   |
| Seagate ST1000DM003-9YN162 1TB      | 1        | 1      | 5.56%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 2      | 5.56%   |
| Samsung Electronics HD502HI 500GB   | 1        | 2      | 5.56%   |
| Maxtor 6Y080M0 80GB                 | 1        | 1      | 5.56%   |
| Hitachi HDS721010KLA330 1TB         | 1        | 1      | 5.56%   |
| Hitachi HCT721010SLA360 1TB         | 1        | 2      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 38.89%  |
| Seagate             | 4        | 4      | 22.22%  |
| Toshiba             | 2        | 2      | 11.11%  |
| Samsung Electronics | 2        | 4      | 11.11%  |
| Hitachi             | 2        | 3      | 11.11%  |
| Maxtor              | 1        | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 41.18%  |
| Seagate             | 4        | 4      | 23.53%  |
| Toshiba             | 2        | 2      | 11.76%  |
| Hitachi             | 2        | 3      | 11.76%  |
| Samsung Electronics | 1        | 2      | 5.88%   |
| Maxtor              | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 20     | 94.12%  |
| SSD  | 1        | 2      | 5.88%   |

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
| Detected | 112      | 218    | 66.27%  |
| Works    | 40       | 63     | 23.67%  |
| Malfunc  | 17       | 22     | 10.06%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 137      | 75.27%  |
| AMD                              | 12       | 6.59%   |
| Nvidia                           | 5        | 2.75%   |
| Marvell Technology Group         | 4        | 2.2%    |
| ASMedia Technology               | 4        | 2.2%    |
| VIA Technologies                 | 3        | 1.65%   |
| Samsung Electronics              | 3        | 1.65%   |
| JMicron Technology               | 3        | 1.65%   |
| Silicon Motion                   | 2        | 1.1%    |
| SanDisk                          | 2        | 1.1%    |
| Realtek Semiconductor            | 2        | 1.1%    |
| ULi Electronics                  | 1        | 0.55%   |
| Silicon Integrated Systems [SiS] | 1        | 0.55%   |
| Shenzhen Longsys Electronics     | 1        | 0.55%   |
| Phison Electronics               | 1        | 0.55%   |
| ADATA Technology                 | 1        | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 23       | 9.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 6.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13       | 5.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 5.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 4.12%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 3.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 3.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 2.88%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 2.88%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 2.47%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.06%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.65%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.23%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.23%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.23%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.23%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 1.23%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.23%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.23%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.82%   |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                                       | 2        | 0.82%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.82%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.82%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.82%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.82%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 2        | 0.82%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.82%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.82%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 98       | 54.14%  |
| IDE  | 63       | 34.81%  |
| NVMe | 11       | 6.08%   |
| RAID | 9        | 4.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 139      | 88.54%  |
| AMD    | 18       | 11.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 7        | 4.46%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 5        | 3.18%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4        | 2.55%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 2.55%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 2.55%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 2.55%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3        | 1.91%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 1.91%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 1.91%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.91%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3        | 1.91%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 3        | 1.91%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.91%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.91%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 1.27%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 1.27%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 2        | 1.27%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 1.27%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 1.27%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 2        | 1.27%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 2        | 1.27%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 2        | 1.27%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.27%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.27%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.27%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.27%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 1.27%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.27%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.27%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.27%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.27%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 1.27%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 1.27%   |
| Intel 12th Gen Core i5-12400                | 2        | 1.27%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.27%   |
| AMD FX-6100 Six-Core Processor              | 2        | 1.27%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz         | 1        | 0.64%   |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz         | 1        | 0.64%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.64%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 35       | 22.29%  |
| Intel Core i7           | 24       | 15.29%  |
| Intel Core i3           | 19       | 12.1%   |
| Intel Pentium           | 14       | 8.92%   |
| Intel Core 2 Duo        | 14       | 8.92%   |
| Intel Pentium Dual-Core | 6        | 3.82%   |
| Intel Core 2 Quad       | 6        | 3.82%   |
| Intel Celeron           | 6        | 3.82%   |
| Other                   | 4        | 2.55%   |
| Intel Xeon              | 3        | 1.91%   |
| Intel Pentium Dual      | 3        | 1.91%   |
| AMD Ryzen 7             | 3        | 1.91%   |
| AMD FX                  | 3        | 1.91%   |
| Intel Pentium 4         | 2        | 1.27%   |
| AMD Ryzen 5             | 2        | 1.27%   |
| AMD Athlon 64 X2        | 2        | 1.27%   |
| AMD Athlon 64           | 2        | 1.27%   |
| Intel Pentium D         | 1        | 0.64%   |
| Intel Core i9           | 1        | 0.64%   |
| Intel Atom              | 1        | 0.64%   |
| AMD PRO A10             | 1        | 0.64%   |
| AMD Phenom II X4        | 1        | 0.64%   |
| AMD E1                  | 1        | 0.64%   |
| AMD Athlon II X3        | 1        | 0.64%   |
| AMD Athlon II X2        | 1        | 0.64%   |
| AMD Athlon              | 1        | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 62       | 39.49%  |
| 4      | 61       | 38.85%  |
| 6      | 13       | 8.28%   |
| 8      | 9        | 5.73%   |
| 1      | 7        | 4.46%   |
| 3      | 3        | 1.91%   |
| 24     | 1        | 0.64%   |
| 12     | 1        | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 156      | 99.36%  |
| 2      | 1        | 0.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 104      | 65.82%  |
| 2      | 54       | 34.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 154      | 97.47%  |
| 32-bit         | 2        | 1.27%   |
| Unknown        | 2        | 1.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 22.93%  |
| 0x306c3    | 18       | 11.46%  |
| 0x306a9    | 15       | 9.55%   |
| 0x1067a    | 15       | 9.55%   |
| 0x206a7    | 9        | 5.73%   |
| 0x506e3    | 8        | 5.1%    |
| 0x906e9    | 5        | 3.18%   |
| 0x906ed    | 4        | 2.55%   |
| 0x906ea    | 4        | 2.55%   |
| 0x6fd      | 4        | 2.55%   |
| 0x6fb      | 3        | 1.91%   |
| 0xa0653    | 2        | 1.27%   |
| 0x906eb    | 2        | 1.27%   |
| 0x90672    | 2        | 1.27%   |
| 0x306f2    | 2        | 1.27%   |
| 0x306e4    | 2        | 1.27%   |
| 0x010000c8 | 2        | 1.27%   |
| 0xf65      | 1        | 0.64%   |
| 0xf4a      | 1        | 0.64%   |
| 0xf49      | 1        | 0.64%   |
| 0xf41      | 1        | 0.64%   |
| 0xf33      | 1        | 0.64%   |
| 0xa0655    | 1        | 0.64%   |
| 0x906ec    | 1        | 0.64%   |
| 0x406f1    | 1        | 0.64%   |
| 0x30679    | 1        | 0.64%   |
| 0x30678    | 1        | 0.64%   |
| 0x30661    | 1        | 0.64%   |
| 0x20655    | 1        | 0.64%   |
| 0x20652    | 1        | 0.64%   |
| 0x106e5    | 1        | 0.64%   |
| 0x10676    | 1        | 0.64%   |
| 0x10661    | 1        | 0.64%   |
| 0x0800820d | 1        | 0.64%   |
| 0x08001137 | 1        | 0.64%   |
| 0x08001129 | 1        | 0.64%   |
| 0x07030106 | 1        | 0.64%   |
| 0x06003106 | 1        | 0.64%   |
| 0x0600063e | 1        | 0.64%   |
| 0x010000db | 1        | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 26       | 16.56%  |
| KabyLake         | 22       | 14.01%  |
| Penryn           | 21       | 13.38%  |
| IvyBridge        | 19       | 12.1%   |
| Skylake          | 11       | 7.01%   |
| SandyBridge      | 10       | 6.37%   |
| Core             | 9        | 5.73%   |
| NetBurst         | 5        | 3.18%   |
| K8 Hammer        | 4        | 2.55%   |
| K10              | 4        | 2.55%   |
| CometLake        | 4        | 2.55%   |
| Zen              | 3        | 1.91%   |
| Bulldozer        | 3        | 1.91%   |
| Zen+             | 2        | 1.27%   |
| Westmere         | 2        | 1.27%   |
| Silvermont       | 2        | 1.27%   |
| Nehalem          | 2        | 1.27%   |
| Alderlake Hybrid | 2        | 1.27%   |
| Unknown          | 2        | 1.27%   |
| Steamroller      | 1        | 0.64%   |
| Puma             | 1        | 0.64%   |
| Broadwell        | 1        | 0.64%   |
| Bonnell          | 1        | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Nvidia               | 69       | 41.32%  |
| Intel                | 67       | 40.12%  |
| AMD                  | 28       | 16.77%  |
| VIA Technologies     | 1        | 0.6%    |
| Trident Microsystems | 1        | 0.6%    |
| ASPEED Technology    | 1        | 0.6%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 13       | 7.78%   |
| Nvidia GT218 [GeForce 210]                                                  | 10       | 5.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 5.39%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 4.79%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 4.19%   |
| Intel HD Graphics 530                                                       | 6        | 3.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 3.59%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 2.4%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.8%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.8%    |
| Nvidia GF119 [GeForce GT 520]                                               | 3        | 1.8%    |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 1.8%    |
| Nvidia G96C [GeForce 9500 GT]                                               | 3        | 1.8%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.8%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.8%    |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 1.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 1.8%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.2%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.2%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.2%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.2%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.2%    |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 1.2%    |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 1.2%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 1.2%    |
| Nvidia G86 [GeForce 8400 GS]                                                | 2        | 1.2%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.2%    |
| Intel HD Graphics 630                                                       | 2        | 1.2%    |
| Intel HD Graphics 510                                                       | 2        | 1.2%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 1.2%    |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 1.2%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.2%    |
| AMD RV730 PRO [Radeon HD 4650]                                              | 2        | 1.2%    |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 0.6%    |
| Trident Microsystems XGI Volari XP5                                         | 1        | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.6%    |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.6%    |
| Nvidia NV34 [GeForce FX 5500]                                               | 1        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 62       | 39.24%  |
| 1 x Intel                | 59       | 37.34%  |
| 1 x AMD                  | 26       | 16.46%  |
| Intel + Nvidia           | 6        | 3.8%    |
| Intel + AMD              | 2        | 1.27%   |
| 1 x VIA                  | 1        | 0.63%   |
| 1 x Trident Microsystems | 1        | 0.63%   |
| Nvidia + ASPEED          | 1        | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 118      | 74.21%  |
| Proprietary | 33       | 20.75%  |
| Unknown     | 8        | 5.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 80       | 50.31%  |
| 1.01-2.0   | 28       | 17.61%  |
| 0.51-1.0   | 16       | 10.06%  |
| 0.01-0.5   | 15       | 9.43%   |
| 3.01-4.0   | 8        | 5.03%   |
| 7.01-8.0   | 6        | 3.77%   |
| 5.01-6.0   | 4        | 2.52%   |
| 8.01-16.0  | 2        | 1.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 44       | 32.12%  |
| Samsung Electronics  | 38       | 27.74%  |
| Hewlett-Packard      | 9        | 6.57%   |
| Ancor Communications | 8        | 5.84%   |
| LG Electronics       | 5        | 3.65%   |
| CHD                  | 5        | 3.65%   |
| AOC                  | 5        | 3.65%   |
| Unknown              | 3        | 2.19%   |
| RTK                  | 3        | 2.19%   |
| Dell                 | 3        | 2.19%   |
| Sony                 | 2        | 1.46%   |
| MSI                  | 2        | 1.46%   |
| Lenovo               | 2        | 1.46%   |
| BenQ                 | 2        | 1.46%   |
| XVision              | 1        | 0.73%   |
| Xiaomi               | 1        | 0.73%   |
| ViewSonic            | 1        | 0.73%   |
| Unknown (ADA)        | 1        | 0.73%   |
| SEEYOO               | 1        | 0.73%   |
| Acer                 | 1        | 0.73%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4        | 2.74%   |
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch               | 4        | 2.74%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 3        | 2.05%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch      | 3        | 2.05%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 3        | 2.05%   |
| Goldstar W2053 GSM4E9F 1600x900 443x249mm 20.0-inch                   | 3        | 2.05%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 2        | 1.37%   |
| Samsung Electronics LS27A70 SAM71A0 3840x2160 597x336mm 27.0-inch     | 2        | 1.37%   |
| Samsung Electronics C27FG70 SAM0DC9 1920x1080 598x337mm 27.0-inch     | 2        | 1.37%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 2        | 1.37%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch          | 2        | 1.37%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                   | 2        | 1.37%   |
| Goldstar ULTRAWIDE GSM5A2A 2560x1080 677x290mm 29.0-inch              | 2        | 1.37%   |
| Goldstar T730BH GSM43C2 1152x864 310x230mm 15.2-inch                  | 2        | 1.37%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 2        | 1.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 1.37%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2        | 1.37%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                   | 2        | 1.37%   |
| CHD PMO S241-IFC CHD0240 1920x1080 530x300mm 24.0-inch                | 2        | 1.37%   |
| CHD 22MC625BF CHD0220 1920x1080 480x260mm 21.5-inch                   | 2        | 1.37%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 2        | 1.37%   |
| XVision XL2020AI XVS0392 1600x900 600x340mm 27.2-inch                 | 1        | 0.68%   |
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                     | 1        | 0.68%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 1        | 0.68%   |
| Unknown LCD Monitor SYK VGA TO HDMI 1920x1080                         | 1        | 0.68%   |
| Unknown LCD Monitor SAMSUNG 2720x768                                  | 1        | 0.68%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.68%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.68%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1        | 0.68%   |
| Sony TV SNYA301 1920x1080                                             | 1        | 0.68%   |
| Sony TV SNY0902 1920x1080                                             | 1        | 0.68%   |
| SEEYOO 29XS440 SEE0032 1680x1050 640x384mm 29.4-inch                  | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0560 1440x900 408x255mm 18.9-inch   | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 470x300mm 22.0-inch  | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0273 1440x900 410x257mm 19.1-inch   | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0159 1280x1024 338x270mm 17.0-inch  | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0152 1280x1024 312x234mm 15.4-inch  | 1        | 0.68%   |
| Samsung Electronics SME2020 SAM06A0 1600x900 443x249mm 20.0-inch      | 1        | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 56       | 41.48%  |
| 1600x900 (HD+)     | 17       | 12.59%  |
| 1366x768 (WXGA)    | 13       | 9.63%   |
| 1440x900 (WXGA+)   | 11       | 8.15%   |
| 1360x768           | 7        | 5.19%   |
| 1280x1024 (SXGA)   | 7        | 5.19%   |
| 1680x1050 (WSXGA+) | 6        | 4.44%   |
| 3840x2160 (4K)     | 5        | 3.7%    |
| 2560x1440 (QHD)    | 3        | 2.22%   |
| 2560x1080          | 3        | 2.22%   |
| 1280x960           | 2        | 1.48%   |
| Unknown            | 2        | 1.48%   |
| 2720x768           | 1        | 0.74%   |
| 1920x1200 (WUXGA)  | 1        | 0.74%   |
| 1280x800 (WXGA)    | 1        | 0.74%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 26       | 18.84%  |
| Unknown | 16       | 11.59%  |
| 18      | 14       | 10.14%  |
| 20      | 13       | 9.42%   |
| 19      | 13       | 9.42%   |
| 23      | 11       | 7.97%   |
| 27      | 9        | 6.52%   |
| 22      | 6        | 4.35%   |
| 17      | 5        | 3.62%   |
| 24      | 4        | 2.9%    |
| 46      | 3        | 2.17%   |
| 29      | 3        | 2.17%   |
| 16      | 3        | 2.17%   |
| 15      | 3        | 2.17%   |
| 72      | 2        | 1.45%   |
| 65      | 1        | 0.72%   |
| 54      | 1        | 0.72%   |
| 40      | 1        | 0.72%   |
| 32      | 1        | 0.72%   |
| 31      | 1        | 0.72%   |
| 26      | 1        | 0.72%   |
| 7       | 1        | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 69       | 50.74%  |
| 501-600     | 25       | 18.38%  |
| Unknown     | 16       | 11.76%  |
| 301-350     | 9        | 6.62%   |
| 1001-1500   | 5        | 3.68%   |
| 601-700     | 4        | 2.94%   |
| 351-400     | 3        | 2.21%   |
| 1501-2000   | 2        | 1.47%   |
| 801-900     | 1        | 0.74%   |
| 701-800     | 1        | 0.74%   |
| 101-200     | 1        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 93       | 69.92%  |
| 16/10   | 15       | 11.28%  |
| Unknown | 14       | 10.53%  |
| 5/4     | 4        | 3.01%   |
| 4/3     | 4        | 3.01%   |
| 21/9    | 2        | 1.5%    |
| 3/2     | 1        | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 30.43%  |
| 151-200        | 30       | 21.74%  |
| 141-150        | 17       | 12.32%  |
| Unknown        | 16       | 11.59%  |
| 301-350        | 11       | 7.97%   |
| More than 1000 | 4        | 2.9%    |
| 501-1000       | 4        | 2.9%    |
| 351-500        | 3        | 2.17%   |
| 121-130        | 3        | 2.17%   |
| 251-300        | 2        | 1.45%   |
| 131-140        | 2        | 1.45%   |
| 101-110        | 2        | 1.45%   |
| 1-40           | 1        | 0.72%   |
| 111-120        | 1        | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 79       | 57.25%  |
| 101-120 | 34       | 24.64%  |
| Unknown | 16       | 11.59%  |
| 1-50    | 6        | 4.35%   |
| 161-240 | 3        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 131      | 82.91%  |
| 2     | 14       | 8.86%   |
| 0     | 13       | 8.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 96       | 40.17%  |
| Intel                            | 43       | 17.99%  |
| Ralink Technology                | 20       | 8.37%   |
| Qualcomm Atheros                 | 20       | 8.37%   |
| Samsung Electronics              | 10       | 4.18%   |
| D-Link                           | 10       | 4.18%   |
| VIA Technologies                 | 6        | 2.51%   |
| TP-Link                          | 5        | 2.09%   |
| Ralink                           | 5        | 2.09%   |
| Nvidia                           | 4        | 1.67%   |
| D-Link System                    | 4        | 1.67%   |
| Broadcom                         | 3        | 1.26%   |
| Qualcomm Atheros Communications  | 2        | 0.84%   |
| Marvell Technology Group         | 2        | 0.84%   |
| ZyDAS                            | 1        | 0.42%   |
| Xiaomi                           | 1        | 0.42%   |
| Silicon Integrated Systems [SiS] | 1        | 0.42%   |
| Huawei Technologies              | 1        | 0.42%   |
| Broadcom Limited                 | 1        | 0.42%   |
| ASUSTek Computer                 | 1        | 0.42%   |
| Aquantia                         | 1        | 0.42%   |
| Apple                            | 1        | 0.42%   |
| AboCom Systems                   | 1        | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 81       | 31.89%  |
| Ralink MT7601U Wireless Adapter                                      | 13       | 5.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 7        | 2.76%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 7        | 2.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 6        | 2.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 6        | 2.36%   |
| Ralink RT5370 Wireless Adapter                                       | 6        | 2.36%   |
| VIA VT6105/VT6106S [Rhine-III]                                       | 5        | 1.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 5        | 1.97%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 5        | 1.97%   |
| Intel Ethernet Connection (2) I219-V                                 | 5        | 1.97%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 4        | 1.57%   |
| Intel Ethernet Connection (7) I219-V                                 | 4        | 1.57%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 4        | 1.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3        | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3        | 1.18%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                 | 3        | 1.18%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 3        | 1.18%   |
| Intel I211 Gigabit Network Connection                                | 3        | 1.18%   |
| Intel Ethernet Connection (2) I218-V                                 | 3        | 1.18%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2        | 0.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2        | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 2        | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller            | 2        | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 2        | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 0.79%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 2        | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 2        | 0.79%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller              | 2        | 0.79%   |
| Intel I210 Gigabit Network Connection                                | 2        | 0.79%   |
| Intel Ethernet Connection I217-V                                     | 2        | 0.79%   |
| Intel Ethernet Connection I217-LM                                    | 2        | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                                | 2        | 0.79%   |
| Intel Ethernet Connection (17) I219-V                                | 2        | 0.79%   |
| Intel Ethernet Connection (11) I219-V                                | 2        | 0.79%   |
| D-Link WLAN controller                                               | 2        | 0.79%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 2        | 0.79%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                      | 2        | 0.79%   |
| ZyDAS ZD1211B 802.11g                                                | 1        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 20       | 27.4%   |
| Realtek Semiconductor           | 17       | 23.29%  |
| D-Link                          | 10       | 13.7%   |
| TP-Link                         | 5        | 6.85%   |
| Ralink                          | 5        | 6.85%   |
| Qualcomm Atheros                | 5        | 6.85%   |
| Qualcomm Atheros Communications | 2        | 2.74%   |
| Intel                           | 2        | 2.74%   |
| D-Link System                   | 2        | 2.74%   |
| Broadcom                        | 2        | 2.74%   |
| ZyDAS                           | 1        | 1.37%   |
| Broadcom Limited                | 1        | 1.37%   |
| AboCom Systems                  | 1        | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                             | 13       | 17.81%  |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                              | 7        | 9.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 6        | 8.22%   |
| Ralink RT5370 Wireless Adapter                                              | 6        | 8.22%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 3        | 4.11%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                        | 3        | 4.11%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                            | 3        | 4.11%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 2        | 2.74%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 2        | 2.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 2.74%   |
| Qualcomm Atheros AR9271 802.11n                                             | 2        | 2.74%   |
| D-Link WLAN controller                                                      | 2        | 2.74%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]        | 2        | 2.74%   |
| ZyDAS ZD1211B 802.11g                                                       | 1        | 1.37%   |
| TP-Link 802.11n NIC                                                         | 1        | 1.37%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 1        | 1.37%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                             | 1        | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1        | 1.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1        | 1.37%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                   | 1        | 1.37%   |
| Realtek 802.11ac NIC                                                        | 1        | 1.37%   |
| Ralink RT2070 Wireless Adapter                                              | 1        | 1.37%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                        | 1        | 1.37%   |
| Ralink RT2561/RT61 802.11g PCI                                              | 1        | 1.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1        | 1.37%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                  | 1        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 1        | 1.37%   |
| Intel Alder Lake-S PCH CNVi WiFi                                            | 1        | 1.37%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS]     | 1        | 1.37%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 1.37%   |
| Broadcom BCM43217 802.11b/g/n                                               | 1        | 1.37%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                           | 1        | 1.37%   |
| AboCom Systems AboCom Systems Inc [WN2001 Prolink Wireless-N Nano Adapter]  | 1        | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 90       | 50.28%  |
| Intel                            | 42       | 23.46%  |
| Qualcomm Atheros                 | 16       | 8.94%   |
| Samsung Electronics              | 10       | 5.59%   |
| VIA Technologies                 | 6        | 3.35%   |
| Nvidia                           | 4        | 2.23%   |
| Marvell Technology Group         | 2        | 1.12%   |
| D-Link System                    | 2        | 1.12%   |
| Xiaomi                           | 1        | 0.56%   |
| Silicon Integrated Systems [SiS] | 1        | 0.56%   |
| Huawei Technologies              | 1        | 0.56%   |
| Broadcom                         | 1        | 0.56%   |
| ASUSTek Computer                 | 1        | 0.56%   |
| Aquantia                         | 1        | 0.56%   |
| Apple                            | 1        | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81       | 44.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 3.87%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6        | 3.31%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 5        | 2.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 2.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5        | 2.76%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.76%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 2.21%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 2.21%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.66%   |
| Intel I211 Gigabit Network Connection                             | 3        | 1.66%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 1.1%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 1.1%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.1%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 1.1%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 1.1%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.1%    |
| Intel I210 Gigabit Network Connection                             | 2        | 1.1%    |
| Intel Ethernet Connection I217-V                                  | 2        | 1.1%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.1%    |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.1%    |
| Intel Ethernet Connection (11) I219-V                             | 2        | 1.1%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 1.1%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 0.55%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.55%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.55%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.55%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.55%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.55%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.55%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.55%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.55%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 156      | 69.33%  |
| WiFi     | 69       | 30.67%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 99       | 65.56%  |
| WiFi     | 52       | 34.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 122      | 77.71%  |
| 2     | 28       | 17.83%  |
| 3     | 4        | 2.55%   |
| 8     | 1        | 0.64%   |
| 4     | 1        | 0.64%   |
| 0     | 1        | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 150      | 95.54%  |
| Yes  | 7        | 4.46%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Cambridge Silicon Radio    | 15       | 71.43%  |
| Intel                      | 2        | 9.52%   |
| ASUSTek Computer           | 2        | 9.52%   |
| ISSC                       | 1        | 4.76%   |
| Integrated System Solution | 1        | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15       | 71.43%  |
| Intel AX201 Bluetooth                               | 2        | 9.52%   |
| ASUS Bluetooth Radio                                | 2        | 9.52%   |
| ISSC Bluetooth Device                               | 1        | 4.76%   |
| Integrated System Solution Bluetooth Device         | 1        | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 133      | 55.65%  |
| Nvidia                           | 56       | 23.43%  |
| AMD                              | 34       | 14.23%  |
| C-Media Electronics              | 6        | 2.51%   |
| Generalplus Technology           | 2        | 0.84%   |
| Creative Labs                    | 2        | 0.84%   |
| VIA Technologies                 | 1        | 0.42%   |
| ULi Electronics                  | 1        | 0.42%   |
| Silicon Integrated Systems [SiS] | 1        | 0.42%   |
| Native Instruments               | 1        | 0.42%   |
| Focusrite-Novation               | 1        | 0.42%   |
| ESS Technology                   | 1        | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 23       | 8.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 18       | 7%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 15       | 5.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 13       | 5.06%   |
| Intel Cannon Lake PCH cAVS                                                        | 12       | 4.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 12       | 4.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11       | 4.28%   |
| Nvidia High Definition Audio Controller                                           | 10       | 3.89%   |
| Intel 200 Series PCH HD Audio                                                     | 8        | 3.11%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 8        | 3.11%   |
| Nvidia GF119 HDMI Audio Controller                                                | 7        | 2.72%   |
| Nvidia GF108 High Definition Audio Controller                                     | 7        | 2.72%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 6        | 2.33%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5        | 1.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 1.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 1.95%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 1.56%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 4        | 1.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 1.56%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 1.17%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 1.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 1.17%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 3        | 1.17%   |
| Intel Alder Lake-S HD Audio Controller                                            | 3        | 1.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 1.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 1.17%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 0.78%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 0.78%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 0.78%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 0.78%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 0.78%   |
| Generalplus Technology USB Audio Device                                           | 2        | 0.78%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.78%   |
| AMD FCH Azalia Controller                                                         | 2        | 0.78%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 0.78%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 1        | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 12       | 19.35%  |
| Kingston            | 8        | 12.9%   |
| GeIL                | 6        | 9.68%   |
| Crucial             | 6        | 9.68%   |
| Corsair             | 6        | 9.68%   |
| SK hynix            | 4        | 6.45%   |
| Samsung Electronics | 3        | 4.84%   |
| Micron Technology   | 3        | 4.84%   |
| G.Skill             | 3        | 4.84%   |
| Apacer              | 3        | 4.84%   |
| Ramos Technology    | 2        | 3.23%   |
| Kingmax             | 2        | 3.23%   |
| TwinMOS             | 1        | 1.61%   |
| Nanya Technology    | 1        | 1.61%   |
| Elpida              | 1        | 1.61%   |
| Unknown             | 1        | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| GeIL RAM CL17-17-17 D4-2400 8GB DIMM DDR4 2400MT/s        | 4        | 5.71%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2        | 2.86%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s      | 2        | 2.86%   |
| Ramos RAM EWB4GB681PAE-16IC 4GB DIMM DDR3 1600MT/s        | 2        | 2.86%   |
| Corsair RAM CMX8GX3M1A1600C11 8GB DIMM DDR3 1600MT/s      | 2        | 2.86%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s     | 2        | 2.86%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 1.43%   |
| Unknown RAM Module 4GB DIMM                               | 1        | 1.43%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1        | 1.43%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                   | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM 400MT/s                       | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM                               | 1        | 1.43%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s              | 1        | 1.43%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 1.43%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 1        | 1.43%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                   | 1        | 1.43%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s               | 1        | 1.43%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s | 1        | 1.43%   |
| TwinMOS RAM 9DSTBNZE-SATP 4GB DIMM DDR3 1333MT/s          | 1        | 1.43%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 1.43%   |
| SK hynix RAM HMA84GR7MFR4N-TF 32GB DIMM DDR4 2133MT/s     | 1        | 1.43%   |
| Samsung RAM M393A2K43BB1-CTD 16GB DIMM DDR4 2667MT/s      | 1        | 1.43%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 1        | 1.43%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.43%   |
| Nanya RAM NT4GC64B8HG0NF-CG 4GB DIMM DDR3 1333MT/s        | 1        | 1.43%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s        | 1        | 1.43%   |
| Micron RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 1.43%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 1.43%   |
| Micron RAM 16ATF1G64AZ-2G1A2 8GB DIMM DDR4 2400MT/s       | 1        | 1.43%   |
| Kingston RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 1.43%   |
| Kingston RAM Module 4096MB DIMM DDR3 1400MT/s             | 1        | 1.43%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 1        | 1.43%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s       | 1        | 1.43%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 1        | 1.43%   |
| Kingston RAM 99U5702-088.A00G 8GB DIMM DDR4 2400MT/s      | 1        | 1.43%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 1.43%   |
| Kingston RAM 99P5471-016.A00LF 8192MB DIMM DDR3 1600MT/s  | 1        | 1.43%   |
| Kingston RAM 9905702-120.A00G 8GB DIMM DDR4 2667MT/s      | 1        | 1.43%   |
| Kingston RAM 9905430-400.A00LF. 4096MB DIMM DDR3 1600MT/s | 1        | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 24       | 43.64%  |
| DDR4    | 21       | 38.18%  |
| Unknown | 7        | 12.73%  |
| DDR5    | 1        | 1.82%   |
| DDR2    | 1        | 1.82%   |
| DDR     | 1        | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 55       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 21       | 33.87%  |
| 4096  | 18       | 29.03%  |
| 2048  | 11       | 17.74%  |
| 16384 | 10       | 16.13%  |
| 32768 | 1        | 1.61%   |
| 1024  | 1        | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 21.67%  |
| 2400    | 10       | 16.67%  |
| 1333    | 8        | 13.33%  |
| 3200    | 4        | 6.67%   |
| 2667    | 4        | 6.67%   |
| 800     | 4        | 6.67%   |
| 2133    | 3        | 5%      |
| 4800    | 1        | 1.67%   |
| 3600    | 1        | 1.67%   |
| 3066    | 1        | 1.67%   |
| 2933    | 1        | 1.67%   |
| 2800    | 1        | 1.67%   |
| 2666    | 1        | 1.67%   |
| 1867    | 1        | 1.67%   |
| 1866    | 1        | 1.67%   |
| 1800    | 1        | 1.67%   |
| 1400    | 1        | 1.67%   |
| 1328    | 1        | 1.67%   |
| 533     | 1        | 1.67%   |
| 400     | 1        | 1.67%   |
| Unknown | 1        | 1.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 3        | 75%     |
| Hewlett-Packard | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| HP LaserJet 1018           | 1        | 25%     |
| Canon MG5600 series        | 1        | 25%     |
| Canon LBP6300              | 1        | 25%     |
| Canon iR2004/2204 UFRII LT | 1        | 25%     |

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
| Apple                       | 4        | 36.36%  |
| Samsung Electronics         | 2        | 18.18%  |
| Realtek Semiconductor       | 1        | 9.09%   |
| Pixart Imaging              | 1        | 9.09%   |
| MacroSilicon                | 1        | 9.09%   |
| KYE Systems (Mouse Systems) | 1        | 9.09%   |
| Generalplus Technology      | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 4        | 36.36%  |
| Samsung Galaxy series, misc. (MTP mode)       | 2        | 18.18%  |
| Realtek FULL HD 1080P Webcam                  | 1        | 9.09%   |
| Pixart Imaging Multimedia audio controller    | 1        | 9.09%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 9.09%   |
| KYE Systems (Mouse Systems) FaceCam 311       | 1        | 9.09%   |
| Generalplus CAMERA - UVC                      | 1        | 9.09%   |

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
| 0     | 128      | 80%     |
| 1     | 26       | 16.25%  |
| 2     | 4        | 2.5%    |
| 3     | 2        | 1.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 15       | 40.54%  |
| Net/wireless             | 8        | 21.62%  |
| Communication controller | 7        | 18.92%  |
| Unassigned class         | 3        | 8.11%   |
| Multimedia controller    | 2        | 5.41%   |
| Sound                    | 1        | 2.7%    |
| Fingerprint reader       | 1        | 2.7%    |

