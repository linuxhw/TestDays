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

Total: 205

| Vendor   | Model                   | Probe                                                      | Date         |
|----------|-------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 33       | 22.76%  |
| Ubuntu 18.04       | 26       | 17.93%  |
| Ubuntu 22.04       | 7        | 4.83%   |
| Ubuntu 19.04       | 6        | 4.14%   |
| Arch               | 5        | 3.45%   |
| Xubuntu 18.04      | 4        | 2.76%   |
| Linux Mint 20.3    | 4        | 2.76%   |
| Ubuntu 20.10       | 3        | 2.07%   |
| OpenMandriva 4.2   | 3        | 2.07%   |
| KDE neon 20.04     | 3        | 2.07%   |
| Zorin 15           | 2        | 1.38%   |
| Xubuntu 20.04      | 2        | 1.38%   |
| Ubuntu 21.10       | 2        | 1.38%   |
| Ubuntu 19.10       | 2        | 1.38%   |
| OpenMandriva 4.3   | 2        | 1.38%   |
| Linux Mint 20.1    | 2        | 1.38%   |
| Linux Mint 20      | 2        | 1.38%   |
| Kubuntu 22.04      | 2        | 1.38%   |
| Elementary 6.1     | 2        | 1.38%   |
| Arch Rolling       | 2        | 1.38%   |
| Xubuntu 22.04      | 1        | 0.69%   |
| Ubuntu Unity 16.04 | 1        | 0.69%   |
| Solus 4.3          | 1        | 0.69%   |
| ROSA R10           | 1        | 0.69%   |
| Pop!_OS 21.04      | 1        | 0.69%   |
| Pop!_OS 20.10      | 1        | 0.69%   |
| Pop!_OS 20.04      | 1        | 0.69%   |
| Manjaro 22.0.0     | 1        | 0.69%   |
| Manjaro 21.3.7     | 1        | 0.69%   |
| Manjaro 21.3.4     | 1        | 0.69%   |
| Manjaro 21.2.6     | 1        | 0.69%   |
| Manjaro 18.0.4     | 1        | 0.69%   |
| Manjaro            | 1        | 0.69%   |
| Lubuntu 18.04      | 1        | 0.69%   |
| Kali 2022.2        | 1        | 0.69%   |
| Kali 2022.1        | 1        | 0.69%   |
| Kali 2021.2        | 1        | 0.69%   |
| Fedora 34          | 1        | 0.69%   |
| Fedora 33          | 1        | 0.69%   |
| Fedora 32          | 1        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 78       | 54.93%  |
| Linux Mint   | 8        | 5.63%   |
| Xubuntu      | 7        | 4.93%   |
| Arch         | 7        | 4.93%   |
| Manjaro      | 6        | 4.23%   |
| Fedora       | 6        | 4.23%   |
| OpenMandriva | 5        | 3.52%   |
| Pop!_OS      | 3        | 2.11%   |
| KDE neon     | 3        | 2.11%   |
| Zorin        | 2        | 1.41%   |
| Kubuntu      | 2        | 1.41%   |
| Kali         | 2        | 1.41%   |
| Endless      | 2        | 1.41%   |
| Elementary   | 2        | 1.41%   |
| Debian       | 2        | 1.41%   |
| Ubuntu Unity | 1        | 0.7%    |
| Solus        | 1        | 0.7%    |
| ROSA         | 1        | 0.7%    |
| Lubuntu      | 1        | 0.7%    |
| CentOS       | 1        | 0.7%    |
| Artix        | 1        | 0.7%    |
| ArcoLinux    | 1        | 0.7%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-48-generic         | 4        | 2.61%   |
| 5.4.0-58-generic         | 3        | 1.96%   |
| 5.4.0-42-generic         | 3        | 1.96%   |
| 5.3.0-40-generic         | 3        | 1.96%   |
| 5.15.0-47-generic        | 3        | 1.96%   |
| 5.11.0-27-generic        | 3        | 1.96%   |
| 5.10.14-desktop-1omv4002 | 3        | 1.96%   |
| 5.8.0-50-generic         | 2        | 1.31%   |
| 5.8.0-44-generic         | 2        | 1.31%   |
| 5.4.0-52-generic         | 2        | 1.31%   |
| 5.4.0-37-generic         | 2        | 1.31%   |
| 5.4.0-26-generic         | 2        | 1.31%   |
| 5.16.7-desktop-1omv4003  | 2        | 1.31%   |
| 5.13.0-30-generic        | 2        | 1.31%   |
| 5.11.0-41-generic        | 2        | 1.31%   |
| 5.11.0-37-generic        | 2        | 1.31%   |
| 5.0.0-38-generic         | 2        | 1.31%   |
| 5.0.0-37-generic         | 2        | 1.31%   |
| 5.0.0-25-generic         | 2        | 1.31%   |
| 5.0.0-23-generic         | 2        | 1.31%   |
| 4.15.0-88-generic        | 2        | 1.31%   |
| 4.15.0-50-generic        | 2        | 1.31%   |
| 4.15.0-29-generic        | 2        | 1.31%   |
| 6.0.0                    | 1        | 0.65%   |
| 5.9.4-arch1-1            | 1        | 0.65%   |
| 5.9.12-arch1-1           | 1        | 0.65%   |
| 5.8.9-200.fc32.x86_64    | 1        | 0.65%   |
| 5.8.8-arch1-1            | 1        | 0.65%   |
| 5.8.18-300.fc33.x86_64   | 1        | 0.65%   |
| 5.8.12-artix1-1          | 1        | 0.65%   |
| 5.8.0-7642-generic       | 1        | 0.65%   |
| 5.8.0-7630-generic       | 1        | 0.65%   |
| 5.8.0-53-generic         | 1        | 0.65%   |
| 5.8.0-43-generic         | 1        | 0.65%   |
| 5.8.0-33-generic         | 1        | 0.65%   |
| 5.8.0-25-generic         | 1        | 0.65%   |
| 5.7.7-100.fc31.x86_64    | 1        | 0.65%   |
| 5.7.6-arch1-1            | 1        | 0.65%   |
| 5.6.13-100.fc30.x86_64   | 1        | 0.65%   |
| 5.4.0-92-generic         | 1        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 21.48%  |
| 4.15.0  | 14       | 9.4%    |
| 5.0.0   | 12       | 8.05%   |
| 5.11.0  | 11       | 7.38%   |
| 5.8.0   | 10       | 6.71%   |
| 5.15.0  | 10       | 6.71%   |
| 5.13.0  | 10       | 6.71%   |
| 5.3.0   | 9        | 6.04%   |
| 4.18.0  | 5        | 3.36%   |
| 5.10.14 | 3        | 2.01%   |
| 5.16.7  | 2        | 1.34%   |
| 5.10.0  | 2        | 1.34%   |
| 6.0.0   | 1        | 0.67%   |
| 5.9.4   | 1        | 0.67%   |
| 5.9.12  | 1        | 0.67%   |
| 5.8.9   | 1        | 0.67%   |
| 5.8.8   | 1        | 0.67%   |
| 5.8.18  | 1        | 0.67%   |
| 5.8.12  | 1        | 0.67%   |
| 5.7.7   | 1        | 0.67%   |
| 5.7.6   | 1        | 0.67%   |
| 5.6.13  | 1        | 0.67%   |
| 5.18.0  | 1        | 0.67%   |
| 5.17.0  | 1        | 0.67%   |
| 5.16.4  | 1        | 0.67%   |
| 5.16.0  | 1        | 0.67%   |
| 5.15.60 | 1        | 0.67%   |
| 5.15.55 | 1        | 0.67%   |
| 5.15.48 | 1        | 0.67%   |
| 5.15.41 | 1        | 0.67%   |
| 5.15.38 | 1        | 0.67%   |
| 5.15.2  | 1        | 0.67%   |
| 5.14.14 | 1        | 0.67%   |
| 5.13.12 | 1        | 0.67%   |
| 5.12.14 | 1        | 0.67%   |
| 5.10.27 | 1        | 0.67%   |
| 5.10.13 | 1        | 0.67%   |
| 5.0.9   | 1        | 0.67%   |
| 4.9.60  | 1        | 0.67%   |
| 4.19.0  | 1        | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 21.62%  |
| 5.15    | 15       | 10.14%  |
| 5.8     | 14       | 9.46%   |
| 4.15    | 14       | 9.46%   |
| 5.0     | 13       | 8.78%   |
| 5.13    | 11       | 7.43%   |
| 5.11    | 11       | 7.43%   |
| 5.3     | 9        | 6.08%   |
| 5.10    | 7        | 4.73%   |
| 4.18    | 5        | 3.38%   |
| 5.16    | 4        | 2.7%    |
| 5.9     | 2        | 1.35%   |
| 5.7     | 2        | 1.35%   |
| 6.0     | 1        | 0.68%   |
| 5.6     | 1        | 0.68%   |
| 5.18    | 1        | 0.68%   |
| 5.17    | 1        | 0.68%   |
| 5.14    | 1        | 0.68%   |
| 5.12    | 1        | 0.68%   |
| 4.9     | 1        | 0.68%   |
| 4.19    | 1        | 0.68%   |
| 4.14    | 1        | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 130      | 94.2%   |
| i686   | 8        | 5.8%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 80       | 55.56%  |
| Unknown    | 20       | 13.89%  |
| KDE5       | 14       | 9.72%   |
| XFCE       | 13       | 9.03%   |
| X-Cinnamon | 6        | 4.17%   |
| i3         | 3        | 2.08%   |
| Pantheon   | 2        | 1.39%   |
| Unity      | 1        | 0.69%   |
| LXQt       | 1        | 0.69%   |
| LXDE       | 1        | 0.69%   |
| KDE        | 1        | 0.69%   |
| Cinnamon   | 1        | 0.69%   |
| Budgie     | 1        | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 112      | 78.87%  |
| Unknown | 15       | 10.56%  |
| Wayland | 13       | 9.15%   |
| Tty     | 2        | 1.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 86       | 60.56%  |
| GDM     | 16       | 11.27%  |
| LightDM | 14       | 9.86%   |
| GDM3    | 12       | 8.45%   |
| SDDM    | 11       | 7.75%   |
| TDM     | 3        | 2.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 107      | 76.43%  |
| Unknown | 20       | 14.29%  |
| fa_IR   | 5        | 3.57%   |
| en_GB   | 5        | 3.57%   |
| en_CA   | 2        | 1.43%   |
| C       | 1        | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 87       | 63.04%  |
| EFI  | 51       | 36.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 127      | 91.37%  |
| Overlay | 6        | 4.32%   |
| Unknown | 4        | 2.88%   |
| Xfs     | 1        | 0.72%   |
| Btrfs   | 1        | 0.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 101      | 72.14%  |
| GPT     | 27       | 19.29%  |
| MBR     | 12       | 8.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 120      | 85.71%  |
| Yes       | 20       | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 52.86%  |
| Yes       | 66       | 47.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 64       | 46.38%  |
| Gigabyte Technology | 32       | 23.19%  |
| Hewlett-Packard     | 16       | 11.59%  |
| ECS                 | 6        | 4.35%   |
| MSI                 | 5        | 3.62%   |
| ASRock              | 5        | 3.62%   |
| Lenovo              | 2        | 1.45%   |
| Biostar             | 2        | 1.45%   |
| Unknown             | 2        | 1.45%   |
| YANYU               | 1        | 0.72%   |
| Intel               | 1        | 0.72%   |
| Foxconn             | 1        | 0.72%   |
| Dell                | 1        | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 13       | 9.42%   |
| HP Compaq Elite 8300 SFF       | 7        | 5.07%   |
| ASUS P5P41T-LE                 | 3        | 2.17%   |
| HP EliteDesk 800 G2 SFF        | 2        | 1.45%   |
| Gigabyte H81M-S2PV             | 2        | 1.45%   |
| Gigabyte EP41-UD3L             | 2        | 1.45%   |
| ASUS Z10PE-D16 WS              | 2        | 1.45%   |
| ASUS PRIME Z390-P              | 2        | 1.45%   |
| ASUS PRIME H310-PLUS R2.0      | 2        | 1.45%   |
| ASUS PRIME H310-PLUS           | 2        | 1.45%   |
| ASUS P9X79 LE                  | 2        | 1.45%   |
| ASUS P8H61                     | 2        | 1.45%   |
| ASUS H61M-C                    | 2        | 1.45%   |
| Unknown                        | 2        | 1.45%   |
| YANYU M9F baytrail             | 1        | 0.72%   |
| MSI MS-7A74                    | 1        | 0.72%   |
| MSI MS-7A39                    | 1        | 0.72%   |
| MSI MS-7817                    | 1        | 0.72%   |
| MSI MS-7673                    | 1        | 0.72%   |
| MSI MS-7623                    | 1        | 0.72%   |
| Lenovo ThinkCentre M58 8910ASU | 1        | 0.72%   |
| Lenovo ThinkCentre M58 7360EHU | 1        | 0.72%   |
| Intel P61-S3                   | 1        | 0.72%   |
| HP Z440 Workstation            | 1        | 0.72%   |
| HP ProDesk 600 G1 SFF          | 1        | 0.72%   |
| HP ProDesk 400 G2 MINI         | 1        | 0.72%   |
| HP EliteDesk 705 G2 SFF        | 1        | 0.72%   |
| HP Compaq 8000 Elite SFF PC    | 1        | 0.72%   |
| HP Compaq 6000 Pro SFF PC      | 1        | 0.72%   |
| HP 700-270jp                   | 1        | 0.72%   |
| Gigabyte Z68P-DS3              | 1        | 0.72%   |
| Gigabyte Z390 GAMING X         | 1        | 0.72%   |
| Gigabyte P75-D3                | 1        | 0.72%   |
| Gigabyte P55A-UD3P             | 1        | 0.72%   |
| Gigabyte P55-USB3              | 1        | 0.72%   |
| Gigabyte P41T-D3P              | 1        | 0.72%   |
| Gigabyte P31-ES3G              | 1        | 0.72%   |
| Gigabyte M52S-S3P              | 1        | 0.72%   |
| Gigabyte M1689D                | 1        | 0.72%   |
| Gigabyte H81M-S2PH             | 1        | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 14       | 10.14%  |
| ASUS All             | 13       | 9.42%   |
| HP Compaq            | 9        | 6.52%   |
| HP EliteDesk         | 3        | 2.17%   |
| ASUS P5P41T-LE       | 3        | 2.17%   |
| Lenovo ThinkCentre   | 2        | 1.45%   |
| HP ProDesk           | 2        | 1.45%   |
| Gigabyte H81M-S2PV   | 2        | 1.45%   |
| Gigabyte EP41-UD3L   | 2        | 1.45%   |
| ASUS Z10PE-D16       | 2        | 1.45%   |
| ASUS TUF             | 2        | 1.45%   |
| ASUS P9X79           | 2        | 1.45%   |
| ASUS P8H61           | 2        | 1.45%   |
| ASUS H61M-C          | 2        | 1.45%   |
| ASUS H110M-C         | 2        | 1.45%   |
| Unknown              | 2        | 1.45%   |
| YANYU M9F            | 1        | 0.72%   |
| MSI MS-7A74          | 1        | 0.72%   |
| MSI MS-7A39          | 1        | 0.72%   |
| MSI MS-7817          | 1        | 0.72%   |
| MSI MS-7673          | 1        | 0.72%   |
| MSI MS-7623          | 1        | 0.72%   |
| Intel P61-S3         | 1        | 0.72%   |
| HP Z440              | 1        | 0.72%   |
| HP 700-270jp         | 1        | 0.72%   |
| Gigabyte Z68P-DS3    | 1        | 0.72%   |
| Gigabyte Z390        | 1        | 0.72%   |
| Gigabyte P75-D3      | 1        | 0.72%   |
| Gigabyte P55A-UD3P   | 1        | 0.72%   |
| Gigabyte P55-USB3    | 1        | 0.72%   |
| Gigabyte P41T-D3P    | 1        | 0.72%   |
| Gigabyte P31-ES3G    | 1        | 0.72%   |
| Gigabyte M52S-S3P    | 1        | 0.72%   |
| Gigabyte M1689D      | 1        | 0.72%   |
| Gigabyte H81M-S2PH   | 1        | 0.72%   |
| Gigabyte H61M-S2V-B3 | 1        | 0.72%   |
| Gigabyte H61M-S2P    | 1        | 0.72%   |
| Gigabyte H61M-D2P-B3 | 1        | 0.72%   |
| Gigabyte H510M       | 1        | 0.72%   |
| Gigabyte H310M       | 1        | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 19       | 13.77%  |
| 2012 | 15       | 10.87%  |
| 2009 | 15       | 10.87%  |
| 2011 | 11       | 7.97%   |
| 2018 | 10       | 7.25%   |
| 2016 | 10       | 7.25%   |
| 2017 | 8        | 5.8%    |
| 2014 | 8        | 5.8%    |
| 2020 | 7        | 5.07%   |
| 2007 | 7        | 5.07%   |
| 2015 | 6        | 4.35%   |
| 2010 | 6        | 4.35%   |
| 2008 | 6        | 4.35%   |
| 2006 | 5        | 3.62%   |
| 2005 | 2        | 1.45%   |
| 2021 | 1        | 0.72%   |
| 2019 | 1        | 0.72%   |
| 2004 | 1        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 138      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 134      | 97.1%   |
| Enabled  | 4        | 2.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 138      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 31       | 22.3%   |
| 3.01-4.0    | 29       | 20.86%  |
| 16.01-24.0  | 29       | 20.86%  |
| 8.01-16.0   | 29       | 20.86%  |
| 32.01-64.0  | 7        | 5.04%   |
| 1.01-2.0    | 7        | 5.04%   |
| 2.01-3.0    | 4        | 2.88%   |
| 64.01-256.0 | 2        | 1.44%   |
| 0.51-1.0    | 1        | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 69       | 46.31%  |
| 2.01-3.0  | 41       | 27.52%  |
| 3.01-4.0  | 13       | 8.72%   |
| 4.01-8.0  | 8        | 5.37%   |
| 0.51-1.0  | 8        | 5.37%   |
| 8.01-16.0 | 6        | 4.03%   |
| 0.01-0.5  | 4        | 2.68%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 69       | 48.94%  |
| 2      | 50       | 35.46%  |
| 3      | 16       | 11.35%  |
| 4      | 4        | 2.84%   |
| 5      | 2        | 1.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 75       | 52.82%  |
| No        | 67       | 47.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 137      | 99.28%  |
| No        | 1        | 0.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 59.44%  |
| Yes       | 58       | 40.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 89.21%  |
| Yes       | 15       | 10.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Iran    | 138      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Tehran                    | 80       | 54.42%  |
| TehrДЃn                 | 11       | 7.48%   |
| Isfahan                   | 5        | 3.4%    |
| Shiraz                    | 4        | 2.72%   |
| Karaj                     | 3        | 2.04%   |
| Tajrīsh                  | 2        | 1.36%   |
| Sanandij                  | 2        | 1.36%   |
| Rey                       | 2        | 1.36%   |
| Qom                       | 2        | 1.36%   |
| Mashhad                   | 2        | 1.36%   |
| Kerman                    | 2        | 1.36%   |
| Hamadan                   | 2        | 1.36%   |
| Arak                      | 2        | 1.36%   |
| Yazd                      | 1        | 0.68%   |
| Tīrān                   | 1        | 0.68%   |
| Siakhdekhan               | 1        | 0.68%   |
| Shahrak-e KÅ«lÅ«rÄ« | 1        | 0.68%   |
| Shaft                     | 1        | 0.68%   |
| Saveh                     | 1        | 0.68%   |
| Rehnān                   | 1        | 0.68%   |
| Ramsar                    | 1        | 0.68%   |
| PДЃkdasht               | 1        | 0.68%   |
| Naz̧arābād             | 1        | 0.68%   |
| NajafÄbÄd           | 1        | 0.68%   |
| Khorramabad               | 1        | 0.68%   |
| KhondДЃb                | 1        | 0.68%   |
| Kermanshah                | 1        | 0.68%   |
| Kāshān                  | 1        | 0.68%   |
| KahrД«z                 | 1        | 0.68%   |
| JongД«yeh               | 1        | 0.68%   |
| JavДЃnrЕ«d            | 1        | 0.68%   |
| FalÄvarjÄn          | 1        | 0.68%   |
| DorЕ«d                  | 1        | 0.68%   |
| DamДЃvand               | 1        | 0.68%   |
| BorЕ«jerd               | 1        | 0.68%   |
| Behshahr                  | 1        | 0.68%   |
| Bahar                     | 1        | 0.68%   |
| Babol                     | 1        | 0.68%   |
| Ardabil                   | 1        | 0.68%   |
| Alvand                    | 1        | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 60       | 83     | 29.27%  |
| Seagate               | 36       | 40     | 17.56%  |
| Maxtor                | 20       | 27     | 9.76%   |
| Samsung Electronics   | 17       | 27     | 8.29%   |
| Toshiba               | 15       | 17     | 7.32%   |
| A-DATA Technology     | 14       | 16     | 6.83%   |
| Lexar                 | 6        | 6      | 2.93%   |
| Kingston              | 6        | 8      | 2.93%   |
| SPCC                  | 5        | 6      | 2.44%   |
| Hitachi               | 4        | 4      | 1.95%   |
| Unknown               | 3        | 3      | 1.46%   |
| Silicon Motion        | 2        | 2      | 0.98%   |
| SanDisk               | 2        | 2      | 0.98%   |
| Intel                 | 2        | 2      | 0.98%   |
| Team                  | 1        | 1      | 0.49%   |
| Realtek Semiconductor | 1        | 1      | 0.49%   |
| Plextor               | 1        | 1      | 0.49%   |
| Pioneer               | 1        | 1      | 0.49%   |
| Phison Electronics    | 1        | 1      | 0.49%   |
| Patriot               | 1        | 1      | 0.49%   |
| OSCOO                 | 1        | 2      | 0.49%   |
| OCZ                   | 1        | 1      | 0.49%   |
| Kingmax               | 1        | 1      | 0.49%   |
| HPE                   | 1        | 1      | 0.49%   |
| Gigabyte Technology   | 1        | 1      | 0.49%   |
| Apacer                | 1        | 1      | 0.49%   |
| AMD                   | 1        | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB         | 11       | 4.89%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 6        | 2.67%   |
| Seagate ST500DM002-1BD142 500GB  | 6        | 2.67%   |
| Maxtor STM3250310AS 250GB        | 6        | 2.67%   |
| WDC WD10EZRX-00L4HB0 1TB         | 3        | 1.33%   |
| WDC WD10EARS-00MVWB0 1TB         | 3        | 1.33%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.33%   |
| Toshiba DT01ACA050 500GB         | 3        | 1.33%   |
| SPCC Solid State Disk 128GB      | 3        | 1.33%   |
| Seagate ST3500413AS 500GB        | 3        | 1.33%   |
| Maxtor 6Y080L0 81GB              | 3        | 1.33%   |
| Lexar 256GB SSD                  | 3        | 1.33%   |
| WDC WD5000AZRX-00L4HB0 500GB     | 2        | 0.89%   |
| WDC WD5000AZRX-00A8LB0 500GB     | 2        | 0.89%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 2        | 0.89%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 2        | 0.89%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 2        | 0.89%   |
| WDC WD10PURZ-85U8XY0 1TB         | 2        | 0.89%   |
| WDC WD10EZEX-00WN4A0 1TB         | 2        | 0.89%   |
| WDC WD10EARX-00N0YB0 1TB         | 2        | 0.89%   |
| Toshiba MQ01ABF050 500GB         | 2        | 0.89%   |
| SPCC Solid State Disk 120GB      | 2        | 0.89%   |
| Seagate ST3500418AS 500GB        | 2        | 0.89%   |
| Seagate ST3320613AS 320GB        | 2        | 0.89%   |
| Seagate ST1000DM003-9YN162 1TB   | 2        | 0.89%   |
| Seagate ST1000DL002-9TT153 1TB   | 2        | 0.89%   |
| Seagate Backup+ Hub BK 8TB       | 2        | 0.89%   |
| Samsung SSD 850 EVO 250GB        | 2        | 0.89%   |
| Samsung HD160JJ 160GB            | 2        | 0.89%   |
| Maxtor STM3802110A 80GB          | 2        | 0.89%   |
| Maxtor STM3160215AS 160GB        | 2        | 0.89%   |
| Lexar 128GB SSD                  | 2        | 0.89%   |
| Kingston SKC400S37256G 256GB SSD | 2        | 0.89%   |
| A-DATA XPG EX500 512GB SSD       | 2        | 0.89%   |
| A-DATA SU800 256GB SSD           | 2        | 0.89%   |
| A-DATA SU650 240GB SSD           | 2        | 0.89%   |
| A-DATA SU650 120GB SSD           | 2        | 0.89%   |
| A-DATA SU630 240GB SSD           | 2        | 0.89%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.44%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD | 1        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 55       | 74     | 40.15%  |
| Seagate             | 36       | 40     | 26.28%  |
| Maxtor              | 20       | 27     | 14.6%   |
| Toshiba             | 15       | 17     | 10.95%  |
| Samsung Electronics | 5        | 9      | 3.65%   |
| Hitachi             | 4        | 4      | 2.92%   |
| Unknown             | 1        | 1      | 0.73%   |
| HPE                 | 1        | 1      | 0.73%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| A-DATA Technology   | 14       | 16     | 21.88%  |
| Samsung Electronics | 12       | 16     | 18.75%  |
| WDC                 | 9        | 9      | 14.06%  |
| Kingston            | 6        | 8      | 9.38%   |
| SPCC                | 5        | 6      | 7.81%   |
| Lexar               | 5        | 5      | 7.81%   |
| SanDisk             | 2        | 2      | 3.13%   |
| Team                | 1        | 1      | 1.56%   |
| Plextor             | 1        | 1      | 1.56%   |
| Pioneer             | 1        | 1      | 1.56%   |
| Patriot             | 1        | 1      | 1.56%   |
| OSCOO               | 1        | 2      | 1.56%   |
| OCZ                 | 1        | 1      | 1.56%   |
| Kingmax             | 1        | 1      | 1.56%   |
| Intel               | 1        | 1      | 1.56%   |
| Gigabyte Technology | 1        | 1      | 1.56%   |
| Apacer              | 1        | 1      | 1.56%   |
| AMD                 | 1        | 1      | 1.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 117      | 173    | 63.93%  |
| SSD     | 58       | 74     | 31.69%  |
| NVMe    | 7        | 9      | 3.83%   |
| Unknown | 1        | 1      | 0.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 135      | 243    | 91.84%  |
| NVMe | 7        | 9      | 4.76%   |
| SAS  | 5        | 5      | 3.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 107      | 161    | 61.14%  |
| 0.51-1.0   | 54       | 69     | 30.86%  |
| 1.01-2.0   | 5        | 5      | 2.86%   |
| 2.01-3.0   | 4        | 5      | 2.29%   |
| 3.01-4.0   | 2        | 2      | 1.14%   |
| 4.01-10.0  | 2        | 2      | 1.14%   |
| 10.01-20.0 | 1        | 3      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 41       | 28.47%  |
| 501-1000       | 29       | 20.14%  |
| 251-500        | 25       | 17.36%  |
| 51-100         | 13       | 9.03%   |
| 1001-2000      | 12       | 8.33%   |
| 2001-3000      | 7        | 4.86%   |
| 21-50          | 6        | 4.17%   |
| More than 3000 | 5        | 3.47%   |
| 1-20           | 4        | 2.78%   |
| Unknown        | 2        | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 52       | 34.9%   |
| 21-50          | 22       | 14.77%  |
| 51-100         | 20       | 13.42%  |
| 101-250        | 18       | 12.08%  |
| 251-500        | 13       | 8.72%   |
| 501-1000       | 11       | 7.38%   |
| 1001-2000      | 5        | 3.36%   |
| More than 3000 | 4        | 2.68%   |
| 2001-3000      | 2        | 1.34%   |
| Unknown        | 2        | 1.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 2      | 5.88%   |
| WDC WD10PURZ-85U8XY0 1TB            | 1        | 1      | 5.88%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 1      | 5.88%   |
| WDC WD10EARX-00N0YB0 1TB            | 1        | 1      | 5.88%   |
| WDC WD10EARS-00MVWB0 1TB            | 1        | 1      | 5.88%   |
| WDC WD1002FBYS-18A6B0 1TB           | 1        | 1      | 5.88%   |
| Toshiba MQ01ABF050 500GB            | 1        | 1      | 5.88%   |
| Toshiba HDWD105 500GB               | 1        | 1      | 5.88%   |
| Seagate ST9500420AS 500GB           | 1        | 1      | 5.88%   |
| Seagate ST3500413AS 500GB           | 1        | 1      | 5.88%   |
| Seagate ST3320613AS 320GB           | 1        | 1      | 5.88%   |
| Seagate ST1000DM003-9YN162 1TB      | 1        | 1      | 5.88%   |
| Samsung Electronics SSD 870 EVO 1TB | 1        | 2      | 5.88%   |
| Samsung Electronics HD502HI 500GB   | 1        | 2      | 5.88%   |
| Maxtor 6Y080M0 81GB                 | 1        | 1      | 5.88%   |
| Hitachi HDS721010KLA330 1TB         | 1        | 1      | 5.88%   |
| Hitachi HCT721010SLA360 1TB         | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 35.29%  |
| Seagate             | 4        | 4      | 23.53%  |
| Toshiba             | 2        | 2      | 11.76%  |
| Samsung Electronics | 2        | 4      | 11.76%  |
| Hitachi             | 2        | 2      | 11.76%  |
| Maxtor              | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 37.5%   |
| Seagate             | 4        | 4      | 25%     |
| Toshiba             | 2        | 2      | 12.5%   |
| Hitachi             | 2        | 2      | 12.5%   |
| Samsung Electronics | 1        | 2      | 6.25%   |
| Maxtor              | 1        | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 18     | 93.75%  |
| SSD  | 1        | 2      | 6.25%   |

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
| Detected | 102      | 189    | 68.46%  |
| Works    | 31       | 48     | 20.81%  |
| Malfunc  | 16       | 20     | 10.74%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 120      | 76.92%  |
| AMD                              | 10       | 6.41%   |
| Nvidia                           | 5        | 3.21%   |
| VIA Technologies                 | 3        | 1.92%   |
| Marvell Technology Group         | 3        | 1.92%   |
| ASMedia Technology               | 3        | 1.92%   |
| Silicon Motion                   | 2        | 1.28%   |
| Samsung Electronics              | 2        | 1.28%   |
| JMicron Technology               | 2        | 1.28%   |
| ULi Electronics                  | 1        | 0.64%   |
| Silicon Integrated Systems [SiS] | 1        | 0.64%   |
| Shenzhen Longsys Electronics     | 1        | 0.64%   |
| Realtek Semiconductor            | 1        | 0.64%   |
| Phison Electronics               | 1        | 0.64%   |
| ADATA Technology                 | 1        | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 21       | 9.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 7.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 6.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12       | 5.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 4.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 4.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 3.76%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 3.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 2.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.35%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.88%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.88%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.41%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.41%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 1.41%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 1.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.41%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.41%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.41%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.41%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.94%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.94%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.94%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.94%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.94%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 2        | 0.94%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.94%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.94%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.47%   |
| VIA Serial ATA Controller                                                               | 1        | 0.47%   |
| ULi ULi 5289 SATA                                                                       | 1        | 0.47%   |
| ULi M5229 IDE                                                                           | 1        | 0.47%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.47%   |
| Silicon Motion Non-Volatile memory controller                                           | 1        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 83       | 53.9%   |
| IDE  | 59       | 38.31%  |
| NVMe | 8        | 5.19%   |
| RAID | 4        | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 122      | 88.41%  |
| AMD    | 16       | 11.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 7        | 5.07%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 5        | 3.62%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4        | 2.9%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 2.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 2.9%    |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 2.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.17%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3        | 2.17%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 3        | 2.17%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 2.17%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 2.17%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 1.45%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 1.45%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 2        | 1.45%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 1.45%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 1.45%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 2        | 1.45%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 2        | 1.45%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 1.45%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.45%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 2        | 1.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.45%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.45%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.45%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.45%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.45%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.45%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.45%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 1.45%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.45%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz         | 1        | 0.72%   |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz         | 1        | 0.72%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.72%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.72%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 1        | 0.72%   |
| Intel Pentium CPU G4400T @ 2.90GHz          | 1        | 0.72%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 0.72%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.72%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.72%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 30       | 21.74%  |
| Intel Core i7           | 20       | 14.49%  |
| Intel Core i3           | 18       | 13.04%  |
| Intel Pentium           | 14       | 10.14%  |
| Intel Core 2 Duo        | 14       | 10.14%  |
| Intel Pentium Dual-Core | 6        | 4.35%   |
| Intel Celeron           | 5        | 3.62%   |
| Intel Core 2 Quad       | 4        | 2.9%    |
| Intel Xeon              | 3        | 2.17%   |
| Intel Pentium Dual      | 3        | 2.17%   |
| AMD Ryzen 7             | 3        | 2.17%   |
| Intel Pentium 4         | 2        | 1.45%   |
| AMD Ryzen 5             | 2        | 1.45%   |
| AMD Athlon 64 X2        | 2        | 1.45%   |
| AMD Athlon 64           | 2        | 1.45%   |
| Other                   | 1        | 0.72%   |
| Intel Core i9           | 1        | 0.72%   |
| Intel Atom              | 1        | 0.72%   |
| AMD PRO A10             | 1        | 0.72%   |
| AMD Phenom II X4        | 1        | 0.72%   |
| AMD FX                  | 1        | 0.72%   |
| AMD E1                  | 1        | 0.72%   |
| AMD Athlon II X3        | 1        | 0.72%   |
| AMD Athlon II X2        | 1        | 0.72%   |
| AMD Athlon              | 1        | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 60       | 43.48%  |
| 4      | 52       | 37.68%  |
| 8      | 8        | 5.8%    |
| 6      | 8        | 5.8%    |
| 1      | 7        | 5.07%   |
| 3      | 2        | 1.45%   |
| 24     | 1        | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 137      | 99.28%  |
| 2      | 1        | 0.72%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 93       | 66.91%  |
| 2      | 46       | 33.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 135      | 97.12%  |
| 32-bit         | 2        | 1.44%   |
| Unknown        | 2        | 1.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 17.39%  |
| 0x306c3    | 17       | 12.32%  |
| 0x306a9    | 15       | 10.87%  |
| 0x1067a    | 15       | 10.87%  |
| 0x206a7    | 9        | 6.52%   |
| 0x506e3    | 8        | 5.8%    |
| 0x906e9    | 5        | 3.62%   |
| 0x6fd      | 4        | 2.9%    |
| 0x906ed    | 3        | 2.17%   |
| 0x906ea    | 3        | 2.17%   |
| 0x6fb      | 3        | 2.17%   |
| 0xa0653    | 2        | 1.45%   |
| 0x906eb    | 2        | 1.45%   |
| 0x306f2    | 2        | 1.45%   |
| 0x306e4    | 2        | 1.45%   |
| 0x010000c8 | 2        | 1.45%   |
| 0xf4a      | 1        | 0.72%   |
| 0xf49      | 1        | 0.72%   |
| 0xf41      | 1        | 0.72%   |
| 0xf33      | 1        | 0.72%   |
| 0xa0655    | 1        | 0.72%   |
| 0x906ec    | 1        | 0.72%   |
| 0x406f1    | 1        | 0.72%   |
| 0x30678    | 1        | 0.72%   |
| 0x30661    | 1        | 0.72%   |
| 0x20655    | 1        | 0.72%   |
| 0x20652    | 1        | 0.72%   |
| 0x106e5    | 1        | 0.72%   |
| 0x10676    | 1        | 0.72%   |
| 0x10661    | 1        | 0.72%   |
| 0x0800820d | 1        | 0.72%   |
| 0x08001137 | 1        | 0.72%   |
| 0x08001129 | 1        | 0.72%   |
| 0x07030106 | 1        | 0.72%   |
| 0x06003106 | 1        | 0.72%   |
| 0x0600063e | 1        | 0.72%   |
| 0x010000db | 1        | 0.72%   |
| 0x01000083 | 1        | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 24       | 17.39%  |
| Penryn      | 20       | 14.49%  |
| IvyBridge   | 18       | 13.04%  |
| KabyLake    | 17       | 12.32%  |
| Skylake     | 10       | 7.25%   |
| SandyBridge | 10       | 7.25%   |
| Core        | 8        | 5.8%    |
| NetBurst    | 4        | 2.9%    |
| K8 Hammer   | 4        | 2.9%    |
| K10         | 4        | 2.9%    |
| Zen         | 3        | 2.17%   |
| CometLake   | 3        | 2.17%   |
| Zen+        | 2        | 1.45%   |
| Westmere    | 2        | 1.45%   |
| Nehalem     | 2        | 1.45%   |
| Steamroller | 1        | 0.72%   |
| Silvermont  | 1        | 0.72%   |
| Puma        | 1        | 0.72%   |
| Bulldozer   | 1        | 0.72%   |
| Broadwell   | 1        | 0.72%   |
| Bonnell     | 1        | 0.72%   |
| Unknown     | 1        | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Nvidia               | 59       | 40.14%  |
| Intel                | 58       | 39.46%  |
| AMD                  | 27       | 18.37%  |
| VIA Technologies     | 1        | 0.68%   |
| Trident Microsystems | 1        | 0.68%   |
| ASPEED Technology    | 1        | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 7.48%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 5.44%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 4.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 4.76%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 4.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 4.08%   |
| Intel HD Graphics 530                                                       | 5        | 3.4%    |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 2.72%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 2.04%   |
| Nvidia GF119 [GeForce GT 520]                                               | 3        | 2.04%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 2.04%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 3        | 2.04%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2.04%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.04%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 2.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 2.04%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.36%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.36%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.36%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 1.36%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 1.36%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 1.36%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 2        | 1.36%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.36%   |
| Intel HD Graphics 630                                                       | 2        | 1.36%   |
| Intel HD Graphics 510                                                       | 2        | 1.36%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.36%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 2        | 1.36%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 0.68%   |
| Trident Microsystems XGI Volari XP5                                         | 1        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.68%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.68%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1        | 0.68%   |
| Nvidia GT216 [GeForce 210]                                                  | 1        | 0.68%   |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 0.68%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.68%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 53       | 38.13%  |
| 1 x Intel                | 51       | 36.69%  |
| 1 x AMD                  | 25       | 17.99%  |
| Intel + Nvidia           | 5        | 3.6%    |
| Intel + AMD              | 2        | 1.44%   |
| 1 x VIA                  | 1        | 0.72%   |
| 1 x Trident Microsystems | 1        | 0.72%   |
| Nvidia + ASPEED          | 1        | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 103      | 73.57%  |
| Proprietary | 30       | 21.43%  |
| Unknown     | 7        | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 47.86%  |
| 1.01-2.0   | 27       | 19.29%  |
| 0.51-1.0   | 15       | 10.71%  |
| 0.01-0.5   | 14       | 10%     |
| 3.01-4.0   | 7        | 5%      |
| 7.01-8.0   | 5        | 3.57%   |
| 5.01-6.0   | 3        | 2.14%   |
| 8.01-16.0  | 2        | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 38       | 32.2%   |
| Samsung Electronics  | 31       | 26.27%  |
| Hewlett-Packard      | 8        | 6.78%   |
| Ancor Communications | 8        | 6.78%   |
| LG Electronics       | 5        | 4.24%   |
| AOC                  | 5        | 4.24%   |
| CHD                  | 4        | 3.39%   |
| Unknown              | 3        | 2.54%   |
| RTK                  | 3        | 2.54%   |
| Dell                 | 3        | 2.54%   |
| Sony                 | 2        | 1.69%   |
| Lenovo               | 2        | 1.69%   |
| BenQ                 | 2        | 1.69%   |
| XVision              | 1        | 0.85%   |
| SEEYOO               | 1        | 0.85%   |
| MSI                  | 1        | 0.85%   |
| Acer                 | 1        | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch               | 4        | 3.15%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 3        | 2.36%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 3        | 2.36%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch      | 3        | 2.36%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 3        | 2.36%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 2        | 1.57%   |
| Samsung Electronics C27FG70 SAM0DC9 1920x1080 598x337mm 27.0-inch     | 2        | 1.57%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 2        | 1.57%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch          | 2        | 1.57%   |
| Goldstar W2053 GSM4E9F 1600x900 443x249mm 20.0-inch                   | 2        | 1.57%   |
| Goldstar T730BH GSM43C2 1152x864 310x230mm 15.2-inch                  | 2        | 1.57%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 2        | 1.57%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2        | 1.57%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                   | 2        | 1.57%   |
| CHD DM-MONB2201 CHD0220 1920x1080 470x280mm 21.5-inch                 | 2        | 1.57%   |
| CHD 24VCF CHD0240 1920x1080 368x207mm 16.6-inch                       | 2        | 1.57%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 2        | 1.57%   |
| XVision XL2020AI XVS0392 1600x900 600x340mm 27.2-inch                 | 1        | 0.79%   |
| Unknown LCD Monitor SYK VGA TO HDMI 1920x1080                         | 1        | 0.79%   |
| Unknown LCD Monitor SAMSUNG 2720x768                                  | 1        | 0.79%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.79%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.79%   |
| Sony TV SNYA301 1920x1080                                             | 1        | 0.79%   |
| Sony TV SNY0902 1360x768                                              | 1        | 0.79%   |
| SEEYOO 29XS440 SEE0032 1680x1050 640x384mm 29.4-inch                  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM0273 1440x900 410x257mm 19.1-inch   | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM0159 1280x1024 338x270mm 17.0-inch  | 1        | 0.79%   |
| Samsung Electronics SyncMaster SAM0152 1280x1024 312x234mm 15.4-inch  | 1        | 0.79%   |
| Samsung Electronics SME2020 SAM06A0 1600x900 443x249mm 20.0-inch      | 1        | 0.79%   |
| Samsung Electronics SMBX1931N SAM0768 1366x768 410x230mm 18.5-inch    | 1        | 0.79%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch  | 1        | 0.79%   |
| Samsung Electronics S27F350 SAM0D23 1920x1080 598x336mm 27.0-inch     | 1        | 0.79%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 1        | 0.79%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch      | 1        | 0.79%   |
| Samsung Electronics S19B370 SAM08B8 1366x768 410x230mm 18.5-inch      | 1        | 0.79%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch      | 1        | 0.79%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                  | 1        | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 51       | 43.59%  |
| 1600x900 (HD+)     | 15       | 12.82%  |
| 1366x768 (WXGA)    | 13       | 11.11%  |
| 1440x900 (WXGA+)   | 9        | 7.69%   |
| 1360x768           | 7        | 5.98%   |
| 1680x1050 (WSXGA+) | 6        | 5.13%   |
| 1280x1024 (SXGA)   | 6        | 5.13%   |
| 2560x1080          | 2        | 1.71%   |
| 1280x960           | 2        | 1.71%   |
| Unknown            | 2        | 1.71%   |
| 3840x2160 (4K)     | 1        | 0.85%   |
| 2720x768           | 1        | 0.85%   |
| 2560x1440 (QHD)    | 1        | 0.85%   |
| 1920x1200 (WUXGA)  | 1        | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 23       | 19.17%  |
| Unknown | 16       | 13.33%  |
| 18      | 14       | 11.67%  |
| 20      | 11       | 9.17%   |
| 19      | 11       | 9.17%   |
| 23      | 9        | 7.5%    |
| 22      | 6        | 5%      |
| 27      | 5        | 4.17%   |
| 24      | 4        | 3.33%   |
| 46      | 3        | 2.5%    |
| 17      | 3        | 2.5%    |
| 16      | 3        | 2.5%    |
| 15      | 3        | 2.5%    |
| 72      | 2        | 1.67%   |
| 29      | 2        | 1.67%   |
| 47      | 1        | 0.83%   |
| 40      | 1        | 0.83%   |
| 32      | 1        | 0.83%   |
| 31      | 1        | 0.83%   |
| 26      | 1        | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 63       | 53.39%  |
| 501-600     | 19       | 16.1%   |
| Unknown     | 16       | 13.56%  |
| 301-350     | 8        | 6.78%   |
| 1001-1500   | 4        | 3.39%   |
| 601-700     | 3        | 2.54%   |
| 1501-2000   | 2        | 1.69%   |
| 801-900     | 1        | 0.85%   |
| 701-800     | 1        | 0.85%   |
| 351-400     | 1        | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 80       | 69.57%  |
| 16/10   | 14       | 12.17%  |
| Unknown | 14       | 12.17%  |
| 4/3     | 4        | 3.48%   |
| 5/4     | 2        | 1.74%   |
| 21/9    | 1        | 0.87%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 38       | 31.67%  |
| 151-200        | 25       | 20.83%  |
| 141-150        | 16       | 13.33%  |
| Unknown        | 16       | 13.33%  |
| 301-350        | 6        | 5%      |
| 501-1000       | 5        | 4.17%   |
| 351-500        | 3        | 2.5%    |
| 121-130        | 3        | 2.5%    |
| More than 1000 | 2        | 1.67%   |
| 251-300        | 2        | 1.67%   |
| 101-110        | 2        | 1.67%   |
| 131-140        | 1        | 0.83%   |
| 111-120        | 1        | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 70       | 58.33%  |
| 101-120 | 28       | 23.33%  |
| Unknown | 16       | 13.33%  |
| 1-50    | 6        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 113      | 81.29%  |
| 2     | 13       | 9.35%   |
| 0     | 13       | 9.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 88       | 42.11%  |
| Intel                            | 32       | 15.31%  |
| Ralink Technology                | 17       | 8.13%   |
| Qualcomm Atheros                 | 16       | 7.66%   |
| Samsung Electronics              | 10       | 4.78%   |
| D-Link                           | 8        | 3.83%   |
| VIA Technologies                 | 6        | 2.87%   |
| TP-Link                          | 5        | 2.39%   |
| Ralink                           | 5        | 2.39%   |
| Nvidia                           | 4        | 1.91%   |
| D-Link System                    | 4        | 1.91%   |
| Qualcomm Atheros Communications  | 2        | 0.96%   |
| Marvell Technology Group         | 2        | 0.96%   |
| Broadcom                         | 2        | 0.96%   |
| ZyDAS                            | 1        | 0.48%   |
| Xiaomi                           | 1        | 0.48%   |
| Silicon Integrated Systems [SiS] | 1        | 0.48%   |
| Huawei Technologies              | 1        | 0.48%   |
| Broadcom Limited                 | 1        | 0.48%   |
| ASUSTek Computer                 | 1        | 0.48%   |
| Aquantia                         | 1        | 0.48%   |
| AboCom Systems                   | 1        | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 77       | 34.53%  |
| Ralink MT7601U Wireless Adapter                                      | 11       | 4.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 7        | 3.14%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 6        | 2.69%   |
| Ralink RT5370 Wireless Adapter                                       | 6        | 2.69%   |
| VIA VT6105/VT6106S [Rhine-III]                                       | 5        | 2.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 5        | 2.24%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 5        | 2.24%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 4        | 1.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4        | 1.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 4        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                                 | 4        | 1.79%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 4        | 1.79%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3        | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3        | 1.35%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                 | 3        | 1.35%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 3        | 1.35%   |
| Intel Ethernet Connection (7) I219-V                                 | 3        | 1.35%   |
| Intel Ethernet Connection (2) I218-V                                 | 3        | 1.35%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2        | 0.9%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 0.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 2        | 0.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller            | 2        | 0.9%    |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 2        | 0.9%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller              | 2        | 0.9%    |
| Intel I210 Gigabit Network Connection                                | 2        | 0.9%    |
| Intel Ethernet Connection I217-V                                     | 2        | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                                | 2        | 0.9%    |
| D-Link WLAN controller                                               | 2        | 0.9%    |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 2        | 0.9%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                      | 2        | 0.9%    |
| ZyDAS ZD1211B 802.11g                                                | 1        | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                 | 1        | 0.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                         | 1        | 0.45%   |
| TP-Link 802.11n NIC                                                  | 1        | 0.45%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet            | 1        | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1        | 0.45%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 17       | 27.42%  |
| Realtek Semiconductor           | 13       | 20.97%  |
| D-Link                          | 8        | 12.9%   |
| TP-Link                         | 5        | 8.06%   |
| Ralink                          | 5        | 8.06%   |
| Qualcomm Atheros                | 5        | 8.06%   |
| Qualcomm Atheros Communications | 2        | 3.23%   |
| D-Link System                   | 2        | 3.23%   |
| ZyDAS                           | 1        | 1.61%   |
| Intel                           | 1        | 1.61%   |
| Broadcom Limited                | 1        | 1.61%   |
| Broadcom                        | 1        | 1.61%   |
| AboCom Systems                  | 1        | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                             | 11       | 17.74%  |
| Ralink RT5370 Wireless Adapter                                              | 6        | 9.68%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                              | 5        | 8.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 4        | 6.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 3        | 4.84%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                        | 3        | 4.84%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                            | 3        | 4.84%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 2        | 3.23%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 2        | 3.23%   |
| Qualcomm Atheros AR9271 802.11n                                             | 2        | 3.23%   |
| D-Link WLAN controller                                                      | 2        | 3.23%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]        | 2        | 3.23%   |
| ZyDAS ZD1211B 802.11g                                                       | 1        | 1.61%   |
| TP-Link 802.11n NIC                                                         | 1        | 1.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 1        | 1.61%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                             | 1        | 1.61%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1        | 1.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1        | 1.61%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                   | 1        | 1.61%   |
| Realtek 802.11ac NIC                                                        | 1        | 1.61%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                        | 1        | 1.61%   |
| Ralink RT2561/RT61 802.11g PCI                                              | 1        | 1.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1        | 1.61%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                  | 1        | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 1        | 1.61%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS]     | 1        | 1.61%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 1.61%   |
| Broadcom BCM43217 802.11b/g/n                                               | 1        | 1.61%   |
| AboCom Systems AboCom Systems Inc [WN2001 Prolink Wireless-N Nano Adapter]  | 1        | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 85       | 53.46%  |
| Intel                            | 32       | 20.13%  |
| Qualcomm Atheros                 | 12       | 7.55%   |
| Samsung Electronics              | 10       | 6.29%   |
| VIA Technologies                 | 6        | 3.77%   |
| Nvidia                           | 4        | 2.52%   |
| Marvell Technology Group         | 2        | 1.26%   |
| D-Link System                    | 2        | 1.26%   |
| Xiaomi                           | 1        | 0.63%   |
| Silicon Integrated Systems [SiS] | 1        | 0.63%   |
| Huawei Technologies              | 1        | 0.63%   |
| Broadcom                         | 1        | 0.63%   |
| ASUSTek Computer                 | 1        | 0.63%   |
| Aquantia                         | 1        | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 77       | 47.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6        | 3.73%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 5        | 3.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.11%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 2.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 2.48%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.48%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.86%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.86%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 1.24%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 1.24%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 1.24%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.24%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.24%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.24%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.24%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 1.24%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 0.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.62%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.62%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.62%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.62%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.62%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.62%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.62%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.62%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.62%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.62%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.62%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.62%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.62%   |
| Huawei E353/E3131                                                 | 1        | 0.62%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.62%   |
| ASUS Android                                                      | 1        | 0.62%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 137      | 70.26%  |
| WiFi     | 58       | 29.74%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 88       | 67.18%  |
| WiFi     | 43       | 32.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 108      | 78.26%  |
| 2     | 25       | 18.12%  |
| 3     | 3        | 2.17%   |
| 4     | 1        | 0.72%   |
| 0     | 1        | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 131      | 94.93%  |
| Yes  | 7        | 5.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Cambridge Silicon Radio    | 12       | 80%     |
| Intel                      | 1        | 6.67%   |
| Integrated System Solution | 1        | 6.67%   |
| Broadcom                   | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12       | 80%     |
| Intel Bluetooth Device                              | 1        | 6.67%   |
| Integrated System Solution Bluetooth Device         | 1        | 6.67%   |
| Broadcom BCM92045B3 ROM                             | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 116      | 55.77%  |
| Nvidia                           | 47       | 22.6%   |
| AMD                              | 31       | 14.9%   |
| C-Media Electronics              | 5        | 2.4%    |
| Generalplus Technology           | 2        | 0.96%   |
| Creative Labs                    | 2        | 0.96%   |
| VIA Technologies                 | 1        | 0.48%   |
| ULi Electronics                  | 1        | 0.48%   |
| Silicon Integrated Systems [SiS] | 1        | 0.48%   |
| Focusrite-Novation               | 1        | 0.48%   |
| ESS Technology                   | 1        | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 21       | 9.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 17       | 7.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 15       | 6.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 12       | 5.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 11       | 4.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9        | 4.02%   |
| Nvidia High Definition Audio Controller                                           | 8        | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                        | 8        | 3.57%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 8        | 3.57%   |
| Nvidia GF119 HDMI Audio Controller                                                | 7        | 3.13%   |
| Nvidia GF108 High Definition Audio Controller                                     | 7        | 3.13%   |
| Intel 200 Series PCH HD Audio                                                     | 7        | 3.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 5        | 2.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 2.23%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 1.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 1.79%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 4        | 1.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 1.79%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 1.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 1.34%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 3        | 1.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 1.34%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 1.34%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 0.89%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 0.89%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.89%   |
| Generalplus Technology USB Audio Device                                           | 2        | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.89%   |
| AMD FCH Azalia Controller                                                         | 2        | 0.89%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 0.89%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 1        | 0.45%   |
| ULi Electronics M5455 PCI AC-Link Controller Audio Device                         | 1        | 0.45%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                   | 1        | 0.45%   |
| Nvidia TU102 High Definition Audio Controller                                     | 1        | 0.45%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.45%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.45%   |
| Nvidia MCP55 High Definition Audio                                                | 1        | 0.45%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 11       | 21.15%  |
| Kingston            | 8        | 15.38%  |
| GeIL                | 5        | 9.62%   |
| SK hynix            | 4        | 7.69%   |
| Samsung Electronics | 3        | 5.77%   |
| Micron Technology   | 3        | 5.77%   |
| G.Skill             | 3        | 5.77%   |
| Crucial             | 3        | 5.77%   |
| Corsair             | 3        | 5.77%   |
| Ramos Technology    | 2        | 3.85%   |
| Kingmax             | 2        | 3.85%   |
| Apacer              | 2        | 3.85%   |
| TwinMOS             | 1        | 1.92%   |
| Nanya Technology    | 1        | 1.92%   |
| Elpida              | 1        | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| GeIL RAM CL17-17-17 D4-2400 8GB DIMM DDR4 2400MT/s        | 3        | 5%      |
| SK hynix RAM HMT41GU6BFR8C-PB 8192MB DIMM DDR3 1600MT/s   | 2        | 3.33%   |
| Ramos RAM EWB4GB681PAE-16IC 4GB DIMM DDR3 1600MT/s        | 2        | 3.33%   |
| Corsair RAM CMX8GX3M1A1600C11 8GB DIMM DDR3 1600MT/s      | 2        | 3.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 1.67%   |
| Unknown RAM Module 4GB DIMM                               | 1        | 1.67%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1        | 1.67%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 1.67%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                   | 1        | 1.67%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 1        | 1.67%   |
| Unknown RAM Module 2GB DIMM 400MT/s                       | 1        | 1.67%   |
| Unknown RAM Module 2GB DIMM                               | 1        | 1.67%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s              | 1        | 1.67%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 1.67%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 1        | 1.67%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                   | 1        | 1.67%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s               | 1        | 1.67%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s | 1        | 1.67%   |
| TwinMOS RAM 9DSTBNZE-SATP 4GB DIMM DDR3 1333MT/s          | 1        | 1.67%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 1.67%   |
| SK hynix RAM HMA84GR7MFR4N-TF 32GB DIMM DDR4 2133MT/s     | 1        | 1.67%   |
| Samsung RAM M393A2K43BB1-CTD 16384MB DIMM DDR4 2667MT/s   | 1        | 1.67%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 1        | 1.67%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.67%   |
| Nanya RAM NT4GC64B8HG0NF-CG 4GB DIMM DDR3 1333MT/s        | 1        | 1.67%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s        | 1        | 1.67%   |
| Micron RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 1.67%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 1.67%   |
| Micron RAM 16ATF1G64AZ-2G1A2 8GB DIMM DDR4 2400MT/s       | 1        | 1.67%   |
| Kingston RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 1.67%   |
| Kingston RAM Module 4096MB DIMM DDR3 1400MT/s             | 1        | 1.67%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 2133MT/s    | 1        | 1.67%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s       | 1        | 1.67%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 1        | 1.67%   |
| Kingston RAM 99U5702-088.A00G 8GB DIMM DDR4 2400MT/s      | 1        | 1.67%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 1.67%   |
| Kingston RAM 99P5471-016.A00LF 8192MB DIMM DDR3 1600MT/s  | 1        | 1.67%   |
| Kingston RAM 9905702-120.A00G 8GB DIMM DDR4 2667MT/s      | 1        | 1.67%   |
| Kingston RAM 9905430-400.A00LF. 4096MB DIMM DDR3 1600MT/s | 1        | 1.67%   |
| Kingmax RAM FLGF65F-C8KLB 4GB DIMM DDR3 1333MT/s          | 1        | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 23       | 51.11%  |
| DDR4    | 14       | 31.11%  |
| Unknown | 6        | 13.33%  |
| DDR2    | 1        | 2.22%   |
| DDR     | 1        | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 45       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 32.69%  |
| 4096  | 17       | 32.69%  |
| 2048  | 10       | 19.23%  |
| 16384 | 6        | 11.54%  |
| 32768 | 1        | 1.92%   |
| 1024  | 1        | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 12       | 24%     |
| 2400    | 8        | 16%     |
| 1333    | 8        | 16%     |
| 2133    | 4        | 8%      |
| 800     | 3        | 6%      |
| 2667    | 2        | 4%      |
| 3600    | 1        | 2%      |
| 3200    | 1        | 2%      |
| 3066    | 1        | 2%      |
| 2800    | 1        | 2%      |
| 2448    | 1        | 2%      |
| 1867    | 1        | 2%      |
| 1866    | 1        | 2%      |
| 1800    | 1        | 2%      |
| 1400    | 1        | 2%      |
| 1328    | 1        | 2%      |
| 533     | 1        | 2%      |
| 400     | 1        | 2%      |
| Unknown | 1        | 2%      |

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
| Apple iPhone 5/5C/5S/6/SE                     | 4        | 36.36%  |
| Samsung Galaxy A5 (MTP)                       | 2        | 18.18%  |
| Realtek Full HD webcam                        | 1        | 9.09%   |
| Pixart Imaging Multimedia audio controller    | 1        | 9.09%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 9.09%   |
| KYE Systems (Mouse Systems) FaceCam 311       | 1        | 9.09%   |
| Generalplus GENERAL WEBCAM                    | 1        | 9.09%   |

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
| 0     | 112      | 79.43%  |
| 1     | 23       | 16.31%  |
| 2     | 4        | 2.84%   |
| 3     | 2        | 1.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 13       | 38.24%  |
| Net/wireless             | 8        | 23.53%  |
| Communication controller | 6        | 17.65%  |
| Unassigned class         | 3        | 8.82%   |
| Multimedia controller    | 2        | 5.88%   |
| Sound                    | 1        | 2.94%   |
| Fingerprint reader       | 1        | 2.94%   |

