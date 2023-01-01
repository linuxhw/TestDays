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

Total: 200

| Vendor   | Model                   | Probe                                                      | Date         |
|----------|-------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 33       | 23.24%  |
| Ubuntu 18.04       | 26       | 18.31%  |
| Ubuntu 22.04       | 6        | 4.23%   |
| Ubuntu 19.04       | 6        | 4.23%   |
| Arch               | 5        | 3.52%   |
| Xubuntu 18.04      | 4        | 2.82%   |
| Linux Mint 20.3    | 4        | 2.82%   |
| Ubuntu 20.10       | 3        | 2.11%   |
| OpenMandriva 4.2   | 3        | 2.11%   |
| KDE neon 20.04     | 3        | 2.11%   |
| Zorin 15           | 2        | 1.41%   |
| Xubuntu 20.04      | 2        | 1.41%   |
| Ubuntu 21.10       | 2        | 1.41%   |
| Ubuntu 19.10       | 2        | 1.41%   |
| OpenMandriva 4.3   | 2        | 1.41%   |
| Linux Mint 20.1    | 2        | 1.41%   |
| Linux Mint 20      | 2        | 1.41%   |
| Elementary 6.1     | 2        | 1.41%   |
| Arch Rolling       | 2        | 1.41%   |
| Xubuntu 22.04      | 1        | 0.7%    |
| Ubuntu Unity 16.04 | 1        | 0.7%    |
| Solus 4.3          | 1        | 0.7%    |
| ROSA R10           | 1        | 0.7%    |
| Pop!_OS 21.04      | 1        | 0.7%    |
| Pop!_OS 20.10      | 1        | 0.7%    |
| Pop!_OS 20.04      | 1        | 0.7%    |
| Manjaro 21.3.7     | 1        | 0.7%    |
| Manjaro 21.3.4     | 1        | 0.7%    |
| Manjaro 21.2.6     | 1        | 0.7%    |
| Manjaro 18.0.4     | 1        | 0.7%    |
| Manjaro            | 1        | 0.7%    |
| Lubuntu 18.04      | 1        | 0.7%    |
| Kubuntu 22.04      | 1        | 0.7%    |
| Kali 2022.2        | 1        | 0.7%    |
| Kali 2022.1        | 1        | 0.7%    |
| Kali 2021.2        | 1        | 0.7%    |
| Fedora 34          | 1        | 0.7%    |
| Fedora 33          | 1        | 0.7%    |
| Fedora 32          | 1        | 0.7%    |
| Fedora 31          | 1        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 77       | 55.4%   |
| Linux Mint   | 8        | 5.76%   |
| Xubuntu      | 7        | 5.04%   |
| Arch         | 7        | 5.04%   |
| Fedora       | 6        | 4.32%   |
| OpenMandriva | 5        | 3.6%    |
| Manjaro      | 5        | 3.6%    |
| Pop!_OS      | 3        | 2.16%   |
| KDE neon     | 3        | 2.16%   |
| Zorin        | 2        | 1.44%   |
| Kali         | 2        | 1.44%   |
| Endless      | 2        | 1.44%   |
| Elementary   | 2        | 1.44%   |
| Debian       | 2        | 1.44%   |
| Ubuntu Unity | 1        | 0.72%   |
| Solus        | 1        | 0.72%   |
| ROSA         | 1        | 0.72%   |
| Lubuntu      | 1        | 0.72%   |
| Kubuntu      | 1        | 0.72%   |
| CentOS       | 1        | 0.72%   |
| Artix        | 1        | 0.72%   |
| ArcoLinux    | 1        | 0.72%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-48-generic         | 4        | 2.67%   |
| 5.4.0-58-generic         | 3        | 2%      |
| 5.4.0-42-generic         | 3        | 2%      |
| 5.3.0-40-generic         | 3        | 2%      |
| 5.15.0-47-generic        | 3        | 2%      |
| 5.11.0-27-generic        | 3        | 2%      |
| 5.10.14-desktop-1omv4002 | 3        | 2%      |
| 5.8.0-50-generic         | 2        | 1.33%   |
| 5.8.0-44-generic         | 2        | 1.33%   |
| 5.4.0-52-generic         | 2        | 1.33%   |
| 5.4.0-37-generic         | 2        | 1.33%   |
| 5.4.0-26-generic         | 2        | 1.33%   |
| 5.16.7-desktop-1omv4003  | 2        | 1.33%   |
| 5.13.0-30-generic        | 2        | 1.33%   |
| 5.11.0-41-generic        | 2        | 1.33%   |
| 5.11.0-37-generic        | 2        | 1.33%   |
| 5.0.0-38-generic         | 2        | 1.33%   |
| 5.0.0-37-generic         | 2        | 1.33%   |
| 5.0.0-25-generic         | 2        | 1.33%   |
| 5.0.0-23-generic         | 2        | 1.33%   |
| 4.15.0-88-generic        | 2        | 1.33%   |
| 4.15.0-50-generic        | 2        | 1.33%   |
| 4.15.0-29-generic        | 2        | 1.33%   |
| 5.9.4-arch1-1            | 1        | 0.67%   |
| 5.9.12-arch1-1           | 1        | 0.67%   |
| 5.8.9-200.fc32.x86_64    | 1        | 0.67%   |
| 5.8.8-arch1-1            | 1        | 0.67%   |
| 5.8.18-300.fc33.x86_64   | 1        | 0.67%   |
| 5.8.12-artix1-1          | 1        | 0.67%   |
| 5.8.0-7642-generic       | 1        | 0.67%   |
| 5.8.0-7630-generic       | 1        | 0.67%   |
| 5.8.0-53-generic         | 1        | 0.67%   |
| 5.8.0-43-generic         | 1        | 0.67%   |
| 5.8.0-33-generic         | 1        | 0.67%   |
| 5.8.0-25-generic         | 1        | 0.67%   |
| 5.7.7-100.fc31.x86_64    | 1        | 0.67%   |
| 5.7.6-arch1-1            | 1        | 0.67%   |
| 5.6.13-100.fc30.x86_64   | 1        | 0.67%   |
| 5.4.0-92-generic         | 1        | 0.67%   |
| 5.4.0-74-generic         | 1        | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 32       | 21.92%  |
| 4.15.0   | 14       | 9.59%   |
| 5.0.0    | 12       | 8.22%   |
| 5.11.0   | 11       | 7.53%   |
| 5.8.0    | 10       | 6.85%   |
| 5.13.0   | 10       | 6.85%   |
| 5.3.0    | 9        | 6.16%   |
| 5.15.0   | 9        | 6.16%   |
| 4.18.0   | 5        | 3.42%   |
| 5.10.14  | 3        | 2.05%   |
| 5.16.7   | 2        | 1.37%   |
| 5.10.0   | 2        | 1.37%   |
| 5.9.4    | 1        | 0.68%   |
| 5.9.12   | 1        | 0.68%   |
| 5.8.9    | 1        | 0.68%   |
| 5.8.8    | 1        | 0.68%   |
| 5.8.18   | 1        | 0.68%   |
| 5.8.12   | 1        | 0.68%   |
| 5.7.7    | 1        | 0.68%   |
| 5.7.6    | 1        | 0.68%   |
| 5.6.13   | 1        | 0.68%   |
| 5.17.0   | 1        | 0.68%   |
| 5.16.4   | 1        | 0.68%   |
| 5.16.0   | 1        | 0.68%   |
| 5.15.60  | 1        | 0.68%   |
| 5.15.55  | 1        | 0.68%   |
| 5.15.48  | 1        | 0.68%   |
| 5.15.41  | 1        | 0.68%   |
| 5.15.38  | 1        | 0.68%   |
| 5.15.2   | 1        | 0.68%   |
| 5.14.14  | 1        | 0.68%   |
| 5.13.12  | 1        | 0.68%   |
| 5.12.14  | 1        | 0.68%   |
| 5.10.27  | 1        | 0.68%   |
| 5.10.13  | 1        | 0.68%   |
| 5.0.9    | 1        | 0.68%   |
| 4.9.60   | 1        | 0.68%   |
| 4.19.0   | 1        | 0.68%   |
| 4.14.138 | 1        | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 22.07%  |
| 5.8     | 14       | 9.66%   |
| 5.15    | 14       | 9.66%   |
| 4.15    | 14       | 9.66%   |
| 5.0     | 13       | 8.97%   |
| 5.13    | 11       | 7.59%   |
| 5.11    | 11       | 7.59%   |
| 5.3     | 9        | 6.21%   |
| 5.10    | 7        | 4.83%   |
| 4.18    | 5        | 3.45%   |
| 5.16    | 4        | 2.76%   |
| 5.9     | 2        | 1.38%   |
| 5.7     | 2        | 1.38%   |
| 5.6     | 1        | 0.69%   |
| 5.17    | 1        | 0.69%   |
| 5.14    | 1        | 0.69%   |
| 5.12    | 1        | 0.69%   |
| 4.9     | 1        | 0.69%   |
| 4.19    | 1        | 0.69%   |
| 4.14    | 1        | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 128      | 94.12%  |
| i686   | 8        | 5.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 78       | 55.32%  |
| Unknown    | 20       | 14.18%  |
| XFCE       | 13       | 9.22%   |
| KDE5       | 13       | 9.22%   |
| X-Cinnamon | 6        | 4.26%   |
| i3         | 3        | 2.13%   |
| Pantheon   | 2        | 1.42%   |
| Unity      | 1        | 0.71%   |
| LXQt       | 1        | 0.71%   |
| LXDE       | 1        | 0.71%   |
| KDE        | 1        | 0.71%   |
| Cinnamon   | 1        | 0.71%   |
| Budgie     | 1        | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 111      | 79.29%  |
| Unknown | 15       | 10.71%  |
| Wayland | 12       | 8.57%   |
| Tty     | 2        | 1.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 86       | 61.87%  |
| GDM     | 15       | 10.79%  |
| LightDM | 14       | 10.07%  |
| GDM3    | 12       | 8.63%   |
| SDDM    | 9        | 6.47%   |
| TDM     | 3        | 2.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 105      | 76.09%  |
| Unknown | 20       | 14.49%  |
| fa_IR   | 5        | 3.62%   |
| en_GB   | 5        | 3.62%   |
| en_CA   | 2        | 1.45%   |
| C       | 1        | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 86       | 63.24%  |
| EFI  | 50       | 36.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 125      | 91.24%  |
| Overlay | 6        | 4.38%   |
| Unknown | 4        | 2.92%   |
| Xfs     | 1        | 0.73%   |
| Btrfs   | 1        | 0.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 101      | 73.72%  |
| GPT     | 24       | 17.52%  |
| MBR     | 12       | 8.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 119      | 86.23%  |
| Yes       | 19       | 13.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 53.62%  |
| Yes       | 64       | 46.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 64       | 47.06%  |
| Gigabyte Technology | 31       | 22.79%  |
| Hewlett-Packard     | 15       | 11.03%  |
| ECS                 | 6        | 4.41%   |
| MSI                 | 5        | 3.68%   |
| ASRock              | 5        | 3.68%   |
| Lenovo              | 2        | 1.47%   |
| Biostar             | 2        | 1.47%   |
| Unknown             | 2        | 1.47%   |
| YANYU               | 1        | 0.74%   |
| Intel               | 1        | 0.74%   |
| Foxconn             | 1        | 0.74%   |
| Dell                | 1        | 0.74%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 13       | 9.56%   |
| HP Compaq Elite 8300 SFF       | 7        | 5.15%   |
| ASUS P5P41T-LE                 | 3        | 2.21%   |
| HP EliteDesk 800 G2 SFF        | 2        | 1.47%   |
| Gigabyte H81M-S2PV             | 2        | 1.47%   |
| Gigabyte EP41-UD3L             | 2        | 1.47%   |
| ASUS Z10PE-D16 WS              | 2        | 1.47%   |
| ASUS PRIME Z390-P              | 2        | 1.47%   |
| ASUS PRIME H310-PLUS R2.0      | 2        | 1.47%   |
| ASUS PRIME H310-PLUS           | 2        | 1.47%   |
| ASUS P9X79 LE                  | 2        | 1.47%   |
| ASUS P8H61                     | 2        | 1.47%   |
| ASUS H61M-C                    | 2        | 1.47%   |
| Unknown                        | 2        | 1.47%   |
| YANYU M9F baytrail             | 1        | 0.74%   |
| MSI MS-7A74                    | 1        | 0.74%   |
| MSI MS-7A39                    | 1        | 0.74%   |
| MSI MS-7817                    | 1        | 0.74%   |
| MSI MS-7673                    | 1        | 0.74%   |
| MSI MS-7623                    | 1        | 0.74%   |
| Lenovo ThinkCentre M58 8910ASU | 1        | 0.74%   |
| Lenovo ThinkCentre M58 7360EHU | 1        | 0.74%   |
| Intel P61-S3                   | 1        | 0.74%   |
| HP Z440 Workstation            | 1        | 0.74%   |
| HP ProDesk 600 G1 SFF          | 1        | 0.74%   |
| HP ProDesk 400 G2 MINI         | 1        | 0.74%   |
| HP Compaq 8000 Elite SFF PC    | 1        | 0.74%   |
| HP Compaq 6000 Pro SFF PC      | 1        | 0.74%   |
| HP 700-270jp                   | 1        | 0.74%   |
| Gigabyte Z68P-DS3              | 1        | 0.74%   |
| Gigabyte Z390 GAMING X         | 1        | 0.74%   |
| Gigabyte P75-D3                | 1        | 0.74%   |
| Gigabyte P55A-UD3P             | 1        | 0.74%   |
| Gigabyte P55-USB3              | 1        | 0.74%   |
| Gigabyte P41T-D3P              | 1        | 0.74%   |
| Gigabyte P31-ES3G              | 1        | 0.74%   |
| Gigabyte M52S-S3P              | 1        | 0.74%   |
| Gigabyte M1689D                | 1        | 0.74%   |
| Gigabyte H81M-S2PH             | 1        | 0.74%   |
| Gigabyte H61M-S2V-B3           | 1        | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 14       | 10.29%  |
| ASUS All             | 13       | 9.56%   |
| HP Compaq            | 9        | 6.62%   |
| ASUS P5P41T-LE       | 3        | 2.21%   |
| Lenovo ThinkCentre   | 2        | 1.47%   |
| HP ProDesk           | 2        | 1.47%   |
| HP EliteDesk         | 2        | 1.47%   |
| Gigabyte H81M-S2PV   | 2        | 1.47%   |
| Gigabyte EP41-UD3L   | 2        | 1.47%   |
| ASUS Z10PE-D16       | 2        | 1.47%   |
| ASUS TUF             | 2        | 1.47%   |
| ASUS P9X79           | 2        | 1.47%   |
| ASUS P8H61           | 2        | 1.47%   |
| ASUS H61M-C          | 2        | 1.47%   |
| ASUS H110M-C         | 2        | 1.47%   |
| Unknown              | 2        | 1.47%   |
| YANYU M9F            | 1        | 0.74%   |
| MSI MS-7A74          | 1        | 0.74%   |
| MSI MS-7A39          | 1        | 0.74%   |
| MSI MS-7817          | 1        | 0.74%   |
| MSI MS-7673          | 1        | 0.74%   |
| MSI MS-7623          | 1        | 0.74%   |
| Intel P61-S3         | 1        | 0.74%   |
| HP Z440              | 1        | 0.74%   |
| HP 700-270jp         | 1        | 0.74%   |
| Gigabyte Z68P-DS3    | 1        | 0.74%   |
| Gigabyte Z390        | 1        | 0.74%   |
| Gigabyte P75-D3      | 1        | 0.74%   |
| Gigabyte P55A-UD3P   | 1        | 0.74%   |
| Gigabyte P55-USB3    | 1        | 0.74%   |
| Gigabyte P41T-D3P    | 1        | 0.74%   |
| Gigabyte P31-ES3G    | 1        | 0.74%   |
| Gigabyte M52S-S3P    | 1        | 0.74%   |
| Gigabyte M1689D      | 1        | 0.74%   |
| Gigabyte H81M-S2PH   | 1        | 0.74%   |
| Gigabyte H61M-S2V-B3 | 1        | 0.74%   |
| Gigabyte H61M-S2P    | 1        | 0.74%   |
| Gigabyte H61M-D2P-B3 | 1        | 0.74%   |
| Gigabyte H510M       | 1        | 0.74%   |
| Gigabyte H310M       | 1        | 0.74%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 19       | 13.97%  |
| 2012 | 15       | 11.03%  |
| 2009 | 15       | 11.03%  |
| 2011 | 11       | 8.09%   |
| 2018 | 10       | 7.35%   |
| 2017 | 8        | 5.88%   |
| 2016 | 8        | 5.88%   |
| 2014 | 8        | 5.88%   |
| 2020 | 7        | 5.15%   |
| 2007 | 7        | 5.15%   |
| 2015 | 6        | 4.41%   |
| 2010 | 6        | 4.41%   |
| 2008 | 6        | 4.41%   |
| 2006 | 5        | 3.68%   |
| 2005 | 2        | 1.47%   |
| 2021 | 1        | 0.74%   |
| 2019 | 1        | 0.74%   |
| 2004 | 1        | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 136      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 132      | 97.06%  |
| Enabled  | 4        | 2.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 136      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 30       | 21.9%   |
| 3.01-4.0    | 29       | 21.17%  |
| 8.01-16.0   | 29       | 21.17%  |
| 16.01-24.0  | 28       | 20.44%  |
| 32.01-64.0  | 7        | 5.11%   |
| 1.01-2.0    | 7        | 5.11%   |
| 2.01-3.0    | 4        | 2.92%   |
| 64.01-256.0 | 2        | 1.46%   |
| 0.51-1.0    | 1        | 0.73%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 68       | 46.58%  |
| 2.01-3.0  | 39       | 26.71%  |
| 3.01-4.0  | 13       | 8.9%    |
| 4.01-8.0  | 8        | 5.48%   |
| 0.51-1.0  | 8        | 5.48%   |
| 8.01-16.0 | 6        | 4.11%   |
| 0.01-0.5  | 4        | 2.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 69       | 49.64%  |
| 2      | 48       | 34.53%  |
| 3      | 16       | 11.51%  |
| 4      | 4        | 2.88%   |
| 5      | 2        | 1.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 73       | 52.14%  |
| No        | 67       | 47.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 135      | 99.26%  |
| No        | 1        | 0.74%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 59.29%  |
| Yes       | 57       | 40.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 89.05%  |
| Yes       | 15       | 10.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Iran    | 136      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Tehran                    | 78       | 54.17%  |
| TehrДЃn                 | 11       | 7.64%   |
| Isfahan                   | 5        | 3.47%   |
| Shiraz                    | 4        | 2.78%   |
| Karaj                     | 3        | 2.08%   |
| Tajrīsh                  | 2        | 1.39%   |
| Sanandij                  | 2        | 1.39%   |
| Rey                       | 2        | 1.39%   |
| Qom                       | 2        | 1.39%   |
| Mashhad                   | 2        | 1.39%   |
| Kerman                    | 2        | 1.39%   |
| Hamadan                   | 2        | 1.39%   |
| Arak                      | 2        | 1.39%   |
| Yazd                      | 1        | 0.69%   |
| Tīrān                   | 1        | 0.69%   |
| Siakhdekhan               | 1        | 0.69%   |
| Shahrak-e KÅ«lÅ«rÄ« | 1        | 0.69%   |
| Shaft                     | 1        | 0.69%   |
| Rehnān                   | 1        | 0.69%   |
| Ramsar                    | 1        | 0.69%   |
| PДЃkdasht               | 1        | 0.69%   |
| Naz̧arābād             | 1        | 0.69%   |
| NajafÄbÄd           | 1        | 0.69%   |
| Khorramabad               | 1        | 0.69%   |
| KhondДЃb                | 1        | 0.69%   |
| Kermanshah                | 1        | 0.69%   |
| Kāshān                  | 1        | 0.69%   |
| KahrД«z                 | 1        | 0.69%   |
| JongД«yeh               | 1        | 0.69%   |
| JavДЃnrЕ«d            | 1        | 0.69%   |
| FalÄvarjÄn          | 1        | 0.69%   |
| DorЕ«d                  | 1        | 0.69%   |
| DamДЃvand               | 1        | 0.69%   |
| BorЕ«jerd               | 1        | 0.69%   |
| Behshahr                  | 1        | 0.69%   |
| Bahar                     | 1        | 0.69%   |
| Babol                     | 1        | 0.69%   |
| Ardabil                   | 1        | 0.69%   |
| Alvand                    | 1        | 0.69%   |
| Ahvaz                     | 1        | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 59       | 80     | 29.35%  |
| Seagate               | 36       | 40     | 17.91%  |
| Maxtor                | 20       | 27     | 9.95%   |
| Samsung Electronics   | 17       | 27     | 8.46%   |
| Toshiba               | 15       | 17     | 7.46%   |
| A-DATA Technology     | 13       | 15     | 6.47%   |
| Lexar                 | 6        | 6      | 2.99%   |
| Kingston              | 6        | 8      | 2.99%   |
| SPCC                  | 5        | 6      | 2.49%   |
| Hitachi               | 4        | 4      | 1.99%   |
| Unknown               | 3        | 3      | 1.49%   |
| Silicon Motion        | 2        | 2      | 1%      |
| SanDisk               | 2        | 2      | 1%      |
| Team                  | 1        | 1      | 0.5%    |
| Realtek Semiconductor | 1        | 1      | 0.5%    |
| Plextor               | 1        | 1      | 0.5%    |
| Pioneer               | 1        | 1      | 0.5%    |
| Patriot               | 1        | 1      | 0.5%    |
| OSCOO                 | 1        | 2      | 0.5%    |
| OCZ                   | 1        | 1      | 0.5%    |
| Kingmax               | 1        | 1      | 0.5%    |
| Intel                 | 1        | 1      | 0.5%    |
| HPE                   | 1        | 1      | 0.5%    |
| Gigabyte Technology   | 1        | 1      | 0.5%    |
| Apacer                | 1        | 1      | 0.5%    |
| AMD                   | 1        | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB         | 11       | 4.98%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 6        | 2.71%   |
| Seagate ST500DM002-1BD142 500GB  | 6        | 2.71%   |
| Maxtor STM3250310AS 250GB        | 6        | 2.71%   |
| WDC WD10EZRX-00L4HB0 1TB         | 3        | 1.36%   |
| WDC WD10EARS-00MVWB0 1TB         | 3        | 1.36%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.36%   |
| Toshiba DT01ACA050 500GB         | 3        | 1.36%   |
| SPCC Solid State Disk 128GB      | 3        | 1.36%   |
| Seagate ST3500413AS 500GB        | 3        | 1.36%   |
| Maxtor 6Y080L0 81GB              | 3        | 1.36%   |
| Lexar 256GB SSD                  | 3        | 1.36%   |
| WDC WD5000AZRX-00L4HB0 500GB     | 2        | 0.9%    |
| WDC WD5000AZRX-00A8LB0 500GB     | 2        | 0.9%    |
| WDC WD5000AAKX-75U6AA0 500GB     | 2        | 0.9%    |
| WDC WD5000AAKX-08U6AA0 500GB     | 2        | 0.9%    |
| WDC WD10PURZ-85U8XY0 1TB         | 2        | 0.9%    |
| WDC WD10EZEX-00WN4A0 1TB         | 2        | 0.9%    |
| WDC WD10EARX-00N0YB0 1TB         | 2        | 0.9%    |
| Toshiba MQ01ABF050 500GB         | 2        | 0.9%    |
| SPCC Solid State Disk 120GB      | 2        | 0.9%    |
| Seagate ST3500418AS 500GB        | 2        | 0.9%    |
| Seagate ST3320613AS 320GB        | 2        | 0.9%    |
| Seagate ST1000DM003-9YN162 1TB   | 2        | 0.9%    |
| Seagate ST1000DL002-9TT153 1TB   | 2        | 0.9%    |
| Seagate Backup+ Hub BK 8TB       | 2        | 0.9%    |
| Samsung SSD 850 EVO 250GB        | 2        | 0.9%    |
| Samsung HD160JJ/ 160GB           | 2        | 0.9%    |
| Maxtor STM3802110A 80GB          | 2        | 0.9%    |
| Maxtor STM3160215AS 160GB        | 2        | 0.9%    |
| Lexar 128GB SSD                  | 2        | 0.9%    |
| Kingston SKC400S37256G 256GB SSD | 2        | 0.9%    |
| A-DATA XPG EX500 512GB SSD       | 2        | 0.9%    |
| A-DATA SU800 256GB SSD           | 2        | 0.9%    |
| A-DATA SU650 120GB SSD           | 2        | 0.9%    |
| A-DATA SU630 240GB SSD           | 2        | 0.9%    |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.45%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD | 1        | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.45%   |
| WDC WD7500AACS-65D6B0 752GB      | 1        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 54       | 71     | 39.71%  |
| Seagate             | 36       | 40     | 26.47%  |
| Maxtor              | 20       | 27     | 14.71%  |
| Toshiba             | 15       | 17     | 11.03%  |
| Samsung Electronics | 5        | 9      | 3.68%   |
| Hitachi             | 4        | 4      | 2.94%   |
| Unknown             | 1        | 1      | 0.74%   |
| HPE                 | 1        | 1      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| A-DATA Technology   | 13       | 15     | 20.63%  |
| Samsung Electronics | 12       | 16     | 19.05%  |
| WDC                 | 9        | 9      | 14.29%  |
| Kingston            | 6        | 8      | 9.52%   |
| SPCC                | 5        | 6      | 7.94%   |
| Lexar               | 5        | 5      | 7.94%   |
| SanDisk             | 2        | 2      | 3.17%   |
| Team                | 1        | 1      | 1.59%   |
| Plextor             | 1        | 1      | 1.59%   |
| Pioneer             | 1        | 1      | 1.59%   |
| Patriot             | 1        | 1      | 1.59%   |
| OSCOO               | 1        | 2      | 1.59%   |
| OCZ                 | 1        | 1      | 1.59%   |
| Kingmax             | 1        | 1      | 1.59%   |
| Intel               | 1        | 1      | 1.59%   |
| Gigabyte Technology | 1        | 1      | 1.59%   |
| Apacer              | 1        | 1      | 1.59%   |
| AMD                 | 1        | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 116      | 170    | 64.44%  |
| SSD     | 57       | 73     | 31.67%  |
| NVMe    | 6        | 7      | 3.33%   |
| Unknown | 1        | 1      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 134      | 239    | 92.41%  |
| NVMe | 6        | 7      | 4.14%   |
| SAS  | 5        | 5      | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 106      | 157    | 60.92%  |
| 0.51-1.0   | 54       | 69     | 31.03%  |
| 1.01-2.0   | 5        | 5      | 2.87%   |
| 2.01-3.0   | 4        | 5      | 2.3%    |
| 3.01-4.0   | 2        | 2      | 1.15%   |
| 4.01-10.0  | 2        | 2      | 1.15%   |
| 10.01-20.0 | 1        | 3      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 41       | 28.87%  |
| 501-1000       | 29       | 20.42%  |
| 251-500        | 24       | 16.9%   |
| 1001-2000      | 12       | 8.45%   |
| 51-100         | 12       | 8.45%   |
| 2001-3000      | 7        | 4.93%   |
| 21-50          | 6        | 4.23%   |
| More than 3000 | 5        | 3.52%   |
| 1-20           | 4        | 2.82%   |
| Unknown        | 2        | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 52       | 35.62%  |
| 21-50          | 22       | 15.07%  |
| 51-100         | 18       | 12.33%  |
| 101-250        | 17       | 11.64%  |
| 251-500        | 13       | 8.9%    |
| 501-1000       | 11       | 7.53%   |
| 1001-2000      | 5        | 3.42%   |
| More than 3000 | 4        | 2.74%   |
| 2001-3000      | 2        | 1.37%   |
| Unknown        | 2        | 1.37%   |

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
| Detected | 100      | 183    | 68.03%  |
| Works    | 31       | 48     | 21.09%  |
| Malfunc  | 16       | 20     | 10.88%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 119      | 77.78%  |
| AMD                              | 9        | 5.88%   |
| Nvidia                           | 5        | 3.27%   |
| VIA Technologies                 | 3        | 1.96%   |
| Marvell Technology Group         | 3        | 1.96%   |
| ASMedia Technology               | 3        | 1.96%   |
| Silicon Motion                   | 2        | 1.31%   |
| Samsung Electronics              | 2        | 1.31%   |
| JMicron Technology               | 2        | 1.31%   |
| ULi Electronics                  | 1        | 0.65%   |
| Silicon Integrated Systems [SiS] | 1        | 0.65%   |
| Shenzhen Longsys Electronics     | 1        | 0.65%   |
| Realtek Semiconductor            | 1        | 0.65%   |
| ADATA Technology                 | 1        | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 21       | 10.05%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 7.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 6.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12       | 5.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 4.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 4.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 3.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.87%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 2.87%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.39%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.91%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.91%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.44%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.44%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.44%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.44%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.96%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.96%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.96%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 0.96%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.96%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 2        | 0.96%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.96%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.96%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.48%   |
| VIA Serial ATA Controller                                                               | 1        | 0.48%   |
| ULi ULi 5289 SATA                                                                       | 1        | 0.48%   |
| ULi M5229 IDE                                                                           | 1        | 0.48%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.48%   |
| Silicon Motion Non-Volatile memory controller                                           | 1        | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 81       | 53.29%  |
| IDE  | 60       | 39.47%  |
| NVMe | 7        | 4.61%   |
| RAID | 4        | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 121      | 88.97%  |
| AMD    | 15       | 11.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 7        | 5.15%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 5        | 3.68%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4        | 2.94%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 2.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 2.94%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 2.21%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.21%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3        | 2.21%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 3        | 2.21%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 2.21%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 2.21%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 1.47%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 1.47%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 2        | 1.47%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 1.47%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 1.47%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 2        | 1.47%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 2        | 1.47%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 1.47%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.47%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 2        | 1.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.47%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.47%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.47%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.47%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.47%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.47%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 1.47%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.47%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz         | 1        | 0.74%   |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz         | 1        | 0.74%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.74%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.74%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 1        | 0.74%   |
| Intel Pentium CPU G4400T @ 2.90GHz          | 1        | 0.74%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 0.74%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.74%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.74%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.74%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 29       | 21.32%  |
| Intel Core i7           | 20       | 14.71%  |
| Intel Core i3           | 18       | 13.24%  |
| Intel Pentium           | 14       | 10.29%  |
| Intel Core 2 Duo        | 14       | 10.29%  |
| Intel Pentium Dual-Core | 6        | 4.41%   |
| Intel Celeron           | 5        | 3.68%   |
| Intel Core 2 Quad       | 4        | 2.94%   |
| Intel Xeon              | 3        | 2.21%   |
| Intel Pentium Dual      | 3        | 2.21%   |
| AMD Ryzen 7             | 3        | 2.21%   |
| Intel Pentium 4         | 2        | 1.47%   |
| AMD Ryzen 5             | 2        | 1.47%   |
| AMD Athlon 64 X2        | 2        | 1.47%   |
| AMD Athlon 64           | 2        | 1.47%   |
| Other                   | 1        | 0.74%   |
| Intel Core i9           | 1        | 0.74%   |
| Intel Atom              | 1        | 0.74%   |
| AMD Phenom II X4        | 1        | 0.74%   |
| AMD FX                  | 1        | 0.74%   |
| AMD E1                  | 1        | 0.74%   |
| AMD Athlon II X3        | 1        | 0.74%   |
| AMD Athlon II X2        | 1        | 0.74%   |
| AMD Athlon              | 1        | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 59       | 43.38%  |
| 4      | 51       | 37.5%   |
| 8      | 8        | 5.88%   |
| 6      | 8        | 5.88%   |
| 1      | 7        | 5.15%   |
| 3      | 2        | 1.47%   |
| 24     | 1        | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 135      | 99.26%  |
| 2      | 1        | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 92       | 67.15%  |
| 2      | 45       | 32.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 133      | 97.08%  |
| 32-bit         | 2        | 1.46%   |
| Unknown        | 2        | 1.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 16.91%  |
| 0x306c3    | 17       | 12.5%   |
| 0x306a9    | 15       | 11.03%  |
| 0x1067a    | 15       | 11.03%  |
| 0x206a7    | 9        | 6.62%   |
| 0x506e3    | 8        | 5.88%   |
| 0x906e9    | 5        | 3.68%   |
| 0x6fd      | 4        | 2.94%   |
| 0x906ed    | 3        | 2.21%   |
| 0x906ea    | 3        | 2.21%   |
| 0x6fb      | 3        | 2.21%   |
| 0xa0653    | 2        | 1.47%   |
| 0x906eb    | 2        | 1.47%   |
| 0x306f2    | 2        | 1.47%   |
| 0x306e4    | 2        | 1.47%   |
| 0x010000c8 | 2        | 1.47%   |
| 0xf4a      | 1        | 0.74%   |
| 0xf49      | 1        | 0.74%   |
| 0xf41      | 1        | 0.74%   |
| 0xf33      | 1        | 0.74%   |
| 0xa0655    | 1        | 0.74%   |
| 0x906ec    | 1        | 0.74%   |
| 0x406f1    | 1        | 0.74%   |
| 0x30678    | 1        | 0.74%   |
| 0x30661    | 1        | 0.74%   |
| 0x20655    | 1        | 0.74%   |
| 0x20652    | 1        | 0.74%   |
| 0x106e5    | 1        | 0.74%   |
| 0x10676    | 1        | 0.74%   |
| 0x10661    | 1        | 0.74%   |
| 0x0800820d | 1        | 0.74%   |
| 0x08001137 | 1        | 0.74%   |
| 0x08001129 | 1        | 0.74%   |
| 0x07030106 | 1        | 0.74%   |
| 0x0600063e | 1        | 0.74%   |
| 0x010000db | 1        | 0.74%   |
| 0x01000083 | 1        | 0.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 24       | 17.65%  |
| Penryn      | 20       | 14.71%  |
| IvyBridge   | 18       | 13.24%  |
| KabyLake    | 16       | 11.76%  |
| Skylake     | 10       | 7.35%   |
| SandyBridge | 10       | 7.35%   |
| Core        | 8        | 5.88%   |
| NetBurst    | 4        | 2.94%   |
| K8 Hammer   | 4        | 2.94%   |
| K10         | 4        | 2.94%   |
| Zen         | 3        | 2.21%   |
| CometLake   | 3        | 2.21%   |
| Zen+        | 2        | 1.47%   |
| Westmere    | 2        | 1.47%   |
| Nehalem     | 2        | 1.47%   |
| Silvermont  | 1        | 0.74%   |
| Puma        | 1        | 0.74%   |
| Bulldozer   | 1        | 0.74%   |
| Broadwell   | 1        | 0.74%   |
| Bonnell     | 1        | 0.74%   |
| Unknown     | 1        | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Nvidia               | 58       | 40%     |
| Intel                | 58       | 40%     |
| AMD                  | 26       | 17.93%  |
| VIA Technologies     | 1        | 0.69%   |
| Trident Microsystems | 1        | 0.69%   |
| ASPEED Technology    | 1        | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 7.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 5.52%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 4.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 4.83%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 4.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 4.14%   |
| Intel HD Graphics 530                                                       | 5        | 3.45%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 2.76%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 2.07%   |
| Nvidia GF119 [GeForce GT 520]                                               | 3        | 2.07%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 2.07%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 3        | 2.07%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2.07%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.07%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 2.07%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 2.07%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.38%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.38%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 1.38%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 1.38%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 1.38%   |
| Nvidia G86 [GeForce 8400 GS]                                                | 2        | 1.38%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.38%   |
| Intel HD Graphics 630                                                       | 2        | 1.38%   |
| Intel HD Graphics 510                                                       | 2        | 1.38%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.38%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 2        | 1.38%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 0.69%   |
| Trident Microsystems XGI Volari XP5                                         | 1        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.69%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.69%   |
| Nvidia NV34 [GeForce FX 5500]                                               | 1        | 0.69%   |
| Nvidia GT216 [GeForce 210]                                                  | 1        | 0.69%   |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 0.69%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 52       | 37.96%  |
| 1 x Intel                | 51       | 37.23%  |
| 1 x AMD                  | 24       | 17.52%  |
| Intel + Nvidia           | 5        | 3.65%   |
| Intel + AMD              | 2        | 1.46%   |
| 1 x VIA                  | 1        | 0.73%   |
| 1 x Trident Microsystems | 1        | 0.73%   |
| Nvidia + ASPEED          | 1        | 0.73%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 102      | 73.91%  |
| Proprietary | 29       | 21.01%  |
| Unknown     | 7        | 5.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 48.55%  |
| 1.01-2.0   | 27       | 19.57%  |
| 0.51-1.0   | 14       | 10.14%  |
| 0.01-0.5   | 14       | 10.14%  |
| 3.01-4.0   | 6        | 4.35%   |
| 7.01-8.0   | 5        | 3.62%   |
| 5.01-6.0   | 3        | 2.17%   |
| 8.01-16.0  | 2        | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 38       | 32.76%  |
| Samsung Electronics  | 30       | 25.86%  |
| Hewlett-Packard      | 8        | 6.9%    |
| Ancor Communications | 8        | 6.9%    |
| LG Electronics       | 5        | 4.31%   |
| AOC                  | 5        | 4.31%   |
| CHD                  | 4        | 3.45%   |
| Unknown              | 3        | 2.59%   |
| RTK                  | 3        | 2.59%   |
| Dell                 | 3        | 2.59%   |
| Sony                 | 2        | 1.72%   |
| Lenovo               | 2        | 1.72%   |
| BenQ                 | 2        | 1.72%   |
| XVision              | 1        | 0.86%   |
| MSI                  | 1        | 0.86%   |
| Acer                 | 1        | 0.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch               | 4        | 3.2%    |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 3        | 2.4%    |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch      | 3        | 2.4%    |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 3        | 2.4%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 1.6%    |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 2        | 1.6%    |
| Samsung Electronics C27FG70 SAM0DC9 1920x1080 598x337mm 27.0-inch     | 2        | 1.6%    |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 2        | 1.6%    |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch          | 2        | 1.6%    |
| Goldstar W2053 GSM4E9F 1600x900 443x249mm 20.0-inch                   | 2        | 1.6%    |
| Goldstar T730BH GSM43C2 1152x864 310x230mm 15.2-inch                  | 2        | 1.6%    |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 2        | 1.6%    |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2        | 1.6%    |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                   | 2        | 1.6%    |
| CHD DM-MONF2410 CHD0240 1920x1080 530x300mm 24.0-inch                 | 2        | 1.6%    |
| CHD DM-MONB2201 CHD0220 1920x1080 470x280mm 21.5-inch                 | 2        | 1.6%    |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 2        | 1.6%    |
| XVision XL2020AI XVS0392 1600x900 600x340mm 27.2-inch                 | 1        | 0.8%    |
| Unknown LCD Monitor SYK VGA TO HDMI 1920x1080                         | 1        | 0.8%    |
| Unknown LCD Monitor SAMSUNG 2720x768                                  | 1        | 0.8%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.8%    |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.8%    |
| Sony TV SNYA301 1920x1080                                             | 1        | 0.8%    |
| Sony TV SNY0902 1360x768                                              | 1        | 0.8%    |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 1        | 0.8%    |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.8%    |
| Samsung Electronics SyncMaster SAM0273 1440x900 410x257mm 19.1-inch   | 1        | 0.8%    |
| Samsung Electronics SyncMaster SAM022B 1280x1024 340x270mm 17.1-inch  | 1        | 0.8%    |
| Samsung Electronics SyncMaster SAM0159 1280x1024 338x270mm 17.0-inch  | 1        | 0.8%    |
| Samsung Electronics SyncMaster SAM0152 1280x1024 312x234mm 15.4-inch  | 1        | 0.8%    |
| Samsung Electronics SME2020 SAM06A0 1600x900 443x249mm 20.0-inch      | 1        | 0.8%    |
| Samsung Electronics SMBX1931N SAM0768 1366x768 410x230mm 18.5-inch    | 1        | 0.8%    |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch  | 1        | 0.8%    |
| Samsung Electronics S27F350 SAM0D23 1920x1080 598x336mm 27.0-inch     | 1        | 0.8%    |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 1        | 0.8%    |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch      | 1        | 0.8%    |
| Samsung Electronics S19B370 SAM08B8 1366x768 410x230mm 18.5-inch      | 1        | 0.8%    |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch      | 1        | 0.8%    |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                  | 1        | 0.8%    |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 0.8%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 50       | 43.48%  |
| 1600x900 (HD+)     | 15       | 13.04%  |
| 1366x768 (WXGA)    | 12       | 10.43%  |
| 1440x900 (WXGA+)   | 9        | 7.83%   |
| 1360x768           | 7        | 6.09%   |
| 1680x1050 (WSXGA+) | 6        | 5.22%   |
| 1280x1024 (SXGA)   | 6        | 5.22%   |
| 2560x1080          | 2        | 1.74%   |
| 1280x960           | 2        | 1.74%   |
| Unknown            | 2        | 1.74%   |
| 3840x2160 (4K)     | 1        | 0.87%   |
| 2720x768           | 1        | 0.87%   |
| 2560x1440 (QHD)    | 1        | 0.87%   |
| 1920x1200 (WUXGA)  | 1        | 0.87%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 22       | 18.64%  |
| Unknown | 16       | 13.56%  |
| 18      | 14       | 11.86%  |
| 20      | 11       | 9.32%   |
| 19      | 11       | 9.32%   |
| 23      | 9        | 7.63%   |
| 22      | 6        | 5.08%   |
| 27      | 5        | 4.24%   |
| 24      | 4        | 3.39%   |
| 46      | 3        | 2.54%   |
| 17      | 3        | 2.54%   |
| 16      | 3        | 2.54%   |
| 15      | 3        | 2.54%   |
| 72      | 2        | 1.69%   |
| 47      | 1        | 0.85%   |
| 40      | 1        | 0.85%   |
| 32      | 1        | 0.85%   |
| 31      | 1        | 0.85%   |
| 29      | 1        | 0.85%   |
| 26      | 1        | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 62       | 53.45%  |
| 501-600     | 19       | 16.38%  |
| Unknown     | 16       | 13.79%  |
| 301-350     | 8        | 6.9%    |
| 1001-1500   | 4        | 3.45%   |
| 601-700     | 2        | 1.72%   |
| 1501-2000   | 2        | 1.72%   |
| 801-900     | 1        | 0.86%   |
| 701-800     | 1        | 0.86%   |
| 351-400     | 1        | 0.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 78       | 69.03%  |
| 16/10   | 14       | 12.39%  |
| Unknown | 14       | 12.39%  |
| 4/3     | 4        | 3.54%   |
| 5/4     | 2        | 1.77%   |
| 21/9    | 1        | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 37       | 31.36%  |
| 151-200        | 25       | 21.19%  |
| 141-150        | 16       | 13.56%  |
| Unknown        | 16       | 13.56%  |
| 301-350        | 6        | 5.08%   |
| 501-1000       | 5        | 4.24%   |
| 121-130        | 3        | 2.54%   |
| More than 1000 | 2        | 1.69%   |
| 351-500        | 2        | 1.69%   |
| 251-300        | 2        | 1.69%   |
| 101-110        | 2        | 1.69%   |
| 131-140        | 1        | 0.85%   |
| 111-120        | 1        | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 69       | 58.47%  |
| 101-120 | 27       | 22.88%  |
| Unknown | 16       | 13.56%  |
| 1-50    | 6        | 5.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 111      | 81.02%  |
| 2     | 13       | 9.49%   |
| 0     | 13       | 9.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 88       | 42.93%  |
| Intel                            | 32       | 15.61%  |
| Ralink Technology                | 17       | 8.29%   |
| Qualcomm Atheros                 | 15       | 7.32%   |
| Samsung Electronics              | 9        | 4.39%   |
| D-Link                           | 8        | 3.9%    |
| VIA Technologies                 | 6        | 2.93%   |
| TP-Link                          | 5        | 2.44%   |
| Ralink                           | 4        | 1.95%   |
| Nvidia                           | 4        | 1.95%   |
| D-Link System                    | 4        | 1.95%   |
| Qualcomm Atheros Communications  | 2        | 0.98%   |
| Marvell Technology Group         | 2        | 0.98%   |
| ZyDAS                            | 1        | 0.49%   |
| Xiaomi                           | 1        | 0.49%   |
| Silicon Integrated Systems [SiS] | 1        | 0.49%   |
| Huawei Technologies              | 1        | 0.49%   |
| Broadcom Limited                 | 1        | 0.49%   |
| Broadcom                         | 1        | 0.49%   |
| ASUSTek Computer                 | 1        | 0.49%   |
| Aquantia                         | 1        | 0.49%   |
| AboCom Systems                   | 1        | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 77       | 35.16%  |
| Ralink MT7601U Wireless Adapter                                      | 11       | 5.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 7        | 3.2%    |
| Ralink RT5370 Wireless Adapter                                       | 6        | 2.74%   |
| VIA VT6105/VT6106S [Rhine-III]                                       | 5        | 2.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 5        | 2.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 5        | 2.28%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 5        | 2.28%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 4        | 1.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4        | 1.83%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 4        | 1.83%   |
| Intel Ethernet Connection (2) I219-V                                 | 4        | 1.83%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 4        | 1.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3        | 1.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3        | 1.37%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 3        | 1.37%   |
| Intel Ethernet Connection (7) I219-V                                 | 3        | 1.37%   |
| Intel Ethernet Connection (2) I218-V                                 | 3        | 1.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2        | 0.91%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 0.91%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                 | 2        | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 2        | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 0.91%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 2        | 0.91%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller              | 2        | 0.91%   |
| Intel I210 Gigabit Network Connection                                | 2        | 0.91%   |
| Intel Ethernet Connection I217-V                                     | 2        | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                                | 2        | 0.91%   |
| D-Link WLAN controller                                               | 2        | 0.91%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 2        | 0.91%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                      | 2        | 0.91%   |
| ZyDAS ZD1211B 802.11g                                                | 1        | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                 | 1        | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                         | 1        | 0.46%   |
| TP-Link 802.11n NIC                                                  | 1        | 0.46%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet            | 1        | 0.46%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1        | 0.46%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 0.46%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 17       | 27.87%  |
| Realtek Semiconductor           | 13       | 21.31%  |
| D-Link                          | 8        | 13.11%  |
| TP-Link                         | 5        | 8.2%    |
| Qualcomm Atheros                | 5        | 8.2%    |
| Ralink                          | 4        | 6.56%   |
| Qualcomm Atheros Communications | 2        | 3.28%   |
| D-Link System                   | 2        | 3.28%   |
| ZyDAS                           | 1        | 1.64%   |
| Intel                           | 1        | 1.64%   |
| Broadcom Limited                | 1        | 1.64%   |
| Broadcom                        | 1        | 1.64%   |
| AboCom Systems                  | 1        | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                             | 11       | 18.03%  |
| Ralink RT5370 Wireless Adapter                                              | 6        | 9.84%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                              | 5        | 8.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 4        | 6.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 3        | 4.92%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                            | 3        | 4.92%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 2        | 3.28%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 2        | 3.28%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                        | 2        | 3.28%   |
| Qualcomm Atheros AR9271 802.11n                                             | 2        | 3.28%   |
| D-Link WLAN controller                                                      | 2        | 3.28%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]        | 2        | 3.28%   |
| ZyDAS ZD1211B 802.11g                                                       | 1        | 1.64%   |
| TP-Link 802.11n NIC                                                         | 1        | 1.64%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 1        | 1.64%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                             | 1        | 1.64%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1        | 1.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1        | 1.64%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                   | 1        | 1.64%   |
| Realtek 802.11ac NIC                                                        | 1        | 1.64%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                        | 1        | 1.64%   |
| Ralink RT2561/RT61 802.11g PCI                                              | 1        | 1.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1        | 1.64%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                  | 1        | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 1        | 1.64%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS]     | 1        | 1.64%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 1.64%   |
| Broadcom BCM43217 802.11b/g/n                                               | 1        | 1.64%   |
| AboCom Systems AboCom Systems Inc [WN2001 Prolink Wireless-N Nano Adapter]  | 1        | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 85       | 54.49%  |
| Intel                            | 32       | 20.51%  |
| Qualcomm Atheros                 | 11       | 7.05%   |
| Samsung Electronics              | 9        | 5.77%   |
| VIA Technologies                 | 6        | 3.85%   |
| Nvidia                           | 4        | 2.56%   |
| Marvell Technology Group         | 2        | 1.28%   |
| D-Link System                    | 2        | 1.28%   |
| Xiaomi                           | 1        | 0.64%   |
| Silicon Integrated Systems [SiS] | 1        | 0.64%   |
| Huawei Technologies              | 1        | 0.64%   |
| ASUSTek Computer                 | 1        | 0.64%   |
| Aquantia                         | 1        | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 77       | 48.73%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.43%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 5        | 3.16%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 5        | 3.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.16%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 2.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 2.53%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.9%    |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.9%    |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 1.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 1.27%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.27%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.27%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.27%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 0.63%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.63%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.63%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.63%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.63%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.63%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.63%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.63%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.63%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.63%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.63%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.63%   |
| Huawei E353/E3131                                                 | 1        | 0.63%   |
| ASUS Android                                                      | 1        | 0.63%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 135      | 70.31%  |
| WiFi     | 57       | 29.69%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 85       | 66.41%  |
| WiFi     | 43       | 33.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 107      | 78.68%  |
| 2     | 24       | 17.65%  |
| 3     | 3        | 2.21%   |
| 4     | 1        | 0.74%   |
| 0     | 1        | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 129      | 94.85%  |
| Yes  | 7        | 5.15%   |

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
| Intel AX201 Bluetooth                               | 1        | 6.67%   |
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
| Intel                            | 115      | 56.1%   |
| Nvidia                           | 46       | 22.44%  |
| AMD                              | 30       | 14.63%  |
| C-Media Electronics              | 5        | 2.44%   |
| Generalplus Technology           | 2        | 0.98%   |
| Creative Labs                    | 2        | 0.98%   |
| VIA Technologies                 | 1        | 0.49%   |
| ULi Electronics                  | 1        | 0.49%   |
| Silicon Integrated Systems [SiS] | 1        | 0.49%   |
| Focusrite-Novation               | 1        | 0.49%   |
| ESS Technology                   | 1        | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 21       | 9.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 17       | 7.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 15       | 6.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 12       | 5.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 11       | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9        | 4.09%   |
| Nvidia High Definition Audio Controller                                           | 8        | 3.64%   |
| Intel Cannon Lake PCH cAVS                                                        | 8        | 3.64%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 8        | 3.64%   |
| Nvidia GF119 HDMI Audio Controller                                                | 7        | 3.18%   |
| Nvidia GF108 High Definition Audio Controller                                     | 7        | 3.18%   |
| Intel 200 Series PCH HD Audio                                                     | 6        | 2.73%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 5        | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 2.27%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 1.82%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 4        | 1.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 1.36%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 1.36%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 1.36%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 3        | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 1.36%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 1.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 0.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 0.91%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 0.91%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.91%   |
| Generalplus Technology USB Audio Device                                           | 2        | 0.91%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.91%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 0.91%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 1        | 0.45%   |
| ULi Electronics M5455 PCI AC-Link Controller Audio Device                         | 1        | 0.45%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                   | 1        | 0.45%   |
| Nvidia TU102 High Definition Audio Controller                                     | 1        | 0.45%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.45%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.45%   |
| Nvidia MCP55 High Definition Audio                                                | 1        | 0.45%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1        | 0.45%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 11       | 22%     |
| Kingston            | 8        | 16%     |
| GeIL                | 5        | 10%     |
| SK hynix            | 4        | 8%      |
| Samsung Electronics | 3        | 6%      |
| Micron Technology   | 3        | 6%      |
| G.Skill             | 3        | 6%      |
| Crucial             | 3        | 6%      |
| Corsair             | 3        | 6%      |
| Ramos Technology    | 2        | 4%      |
| Kingmax             | 2        | 4%      |
| Apacer              | 2        | 4%      |
| TwinMOS             | 1        | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| GeIL RAM CL17-17-17 D4-2400 8GB DIMM DDR4 2400MT/s        | 3        | 5.26%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8192MB DIMM DDR3 1600MT/s   | 2        | 3.51%   |
| Ramos RAM EWB4GB681PAE-16IC 4GB DIMM DDR3 1600MT/s        | 2        | 3.51%   |
| Corsair RAM CMX8GX3M1A1600C11 8GB DIMM DDR3 1600MT/s      | 2        | 3.51%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 1.75%   |
| Unknown RAM Module 4GB DIMM                               | 1        | 1.75%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1        | 1.75%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                   | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM 400MT/s                       | 1        | 1.75%   |
| Unknown RAM Module 2GB DIMM                               | 1        | 1.75%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s              | 1        | 1.75%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 1.75%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 1        | 1.75%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                   | 1        | 1.75%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s               | 1        | 1.75%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s | 1        | 1.75%   |
| TwinMOS RAM 9DSTBNZE-SATP 4GB DIMM DDR3 1333MT/s          | 1        | 1.75%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 1.75%   |
| SK hynix RAM HMA84GR7MFR4N-TF 32GB DIMM DDR4 2133MT/s     | 1        | 1.75%   |
| Samsung RAM M393A2K43BB1-CTD 16384MB DIMM DDR4 2667MT/s   | 1        | 1.75%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s       | 1        | 1.75%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.75%   |
| Micron RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 1.75%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 1.75%   |
| Micron RAM 16ATF1G64AZ-2G1A2 8GB DIMM DDR4 2400MT/s       | 1        | 1.75%   |
| Kingston RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 1.75%   |
| Kingston RAM Module 4096MB DIMM DDR3 1400MT/s             | 1        | 1.75%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 1        | 1.75%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s       | 1        | 1.75%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 1        | 1.75%   |
| Kingston RAM 99U5702-088.A00G 8GB DIMM DDR4 2400MT/s      | 1        | 1.75%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 1.75%   |
| Kingston RAM 99P5471-016.A00LF 8192MB DIMM DDR3 1600MT/s  | 1        | 1.75%   |
| Kingston RAM 9905702-120.A00G 8GB DIMM DDR4 2667MT/s      | 1        | 1.75%   |
| Kingston RAM 9905430-400.A00LF. 4096MB DIMM DDR3 1600MT/s | 1        | 1.75%   |
| Kingmax RAM FLGF65F-C8KLB 4GB DIMM DDR3 1333MT/s          | 1        | 1.75%   |
| Kingmax RAM FLFF65F-D8KM9 4GB DIMM DDR3 1333MT/s          | 1        | 1.75%   |
| GeIL RAM CL9-9-9 D3-1333 8GB DIMM DDR3 1333MT/s           | 1        | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 22       | 50%     |
| DDR4    | 14       | 31.82%  |
| Unknown | 6        | 13.64%  |
| DDR2    | 1        | 2.27%   |
| DDR     | 1        | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 44       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 34%     |
| 4096  | 16       | 32%     |
| 2048  | 9        | 18%     |
| 16384 | 6        | 12%     |
| 32768 | 1        | 2%      |
| 1024  | 1        | 2%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 12       | 25%     |
| 2400    | 8        | 16.67%  |
| 1333    | 7        | 14.58%  |
| 2133    | 4        | 8.33%   |
| 800     | 3        | 6.25%   |
| 2667    | 2        | 4.17%   |
| 3600    | 1        | 2.08%   |
| 3200    | 1        | 2.08%   |
| 3066    | 1        | 2.08%   |
| 2800    | 1        | 2.08%   |
| 2448    | 1        | 2.08%   |
| 1867    | 1        | 2.08%   |
| 1800    | 1        | 2.08%   |
| 1400    | 1        | 2.08%   |
| 1328    | 1        | 2.08%   |
| 533     | 1        | 2.08%   |
| 400     | 1        | 2.08%   |
| Unknown | 1        | 2.08%   |

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
| Apple                       | 4        | 40%     |
| Samsung Electronics         | 1        | 10%     |
| Realtek Semiconductor       | 1        | 10%     |
| Pixart Imaging              | 1        | 10%     |
| MacroSilicon                | 1        | 10%     |
| KYE Systems (Mouse Systems) | 1        | 10%     |
| Generalplus Technology      | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Apple iPhone5/5C/5S/6                         | 4        | 40%     |
| Samsung Galaxy A5 (MTP)                       | 1        | 10%     |
| Realtek Full HD webcam                        | 1        | 10%     |
| Pixart Imaging Multimedia audio controller    | 1        | 10%     |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 10%     |
| KYE Systems (Mouse Systems) FaceCam 311       | 1        | 10%     |
| Generalplus GENERAL WEBCAM                    | 1        | 10%     |

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
| 0     | 110      | 79.14%  |
| 1     | 23       | 16.55%  |
| 2     | 4        | 2.88%   |
| 3     | 2        | 1.44%   |

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

