LMDE 4 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for LMDE 4.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=lmde-4

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 843C                        | [e7df8fecdd](https://linux-hardware.org/?probe=e7df8fecdd) | Oct 30, 2021 |
| ASUSTek       | P7F-M                       | [f0983027ee](https://linux-hardware.org/?probe=f0983027ee) | Oct 26, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | [48187accde](https://linux-hardware.org/?probe=48187accde) | Oct 21, 2021 |
| ASUSTek       | Z97-K                       | [f1fcb9d1db](https://linux-hardware.org/?probe=f1fcb9d1db) | Oct 17, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | [a1820d8f0c](https://linux-hardware.org/?probe=a1820d8f0c) | Oct 17, 2021 |
| Gigabyte      | H61M-D2-B3                  | [138df954cb](https://linux-hardware.org/?probe=138df954cb) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | [dabe5d459a](https://linux-hardware.org/?probe=dabe5d459a) | Oct 15, 2021 |
| ASUSTek       | Z97-K                       | [940a27249a](https://linux-hardware.org/?probe=940a27249a) | Oct 12, 2021 |
| ASUSTek       | Z97-K                       | [012056e32d](https://linux-hardware.org/?probe=012056e32d) | Sep 28, 2021 |
| Biostar       | G41D3C                      | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [9c0ade7c9c](https://linux-hardware.org/?probe=9c0ade7c9c) | Sep 20, 2021 |
| ASUSTek       | P5VD2-VM                    | [9eec34a3f2](https://linux-hardware.org/?probe=9eec34a3f2) | Sep 13, 2021 |
| Foxconn       | 945 7MC Series              | [623cb095f2](https://linux-hardware.org/?probe=623cb095f2) | Sep 12, 2021 |
| Pegatron      | 2AB5                        | [3c335b37fa](https://linux-hardware.org/?probe=3c335b37fa) | Sep 10, 2021 |
| ASUSTek       | UN62                        | [0702f80222](https://linux-hardware.org/?probe=0702f80222) | Sep 09, 2021 |
| ASUSTek       | P5VD2-VM                    | [9bab4b76ff](https://linux-hardware.org/?probe=9bab4b76ff) | Sep 07, 2021 |
| ASUSTek       | P5VD2-VM                    | [305d566f57](https://linux-hardware.org/?probe=305d566f57) | Sep 07, 2021 |
| Gigabyte      | H61M-S1                     | [d1773b3e3d](https://linux-hardware.org/?probe=d1773b3e3d) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | [5d2cc7f4ca](https://linux-hardware.org/?probe=5d2cc7f4ca) | Sep 06, 2021 |
| Intel         | DG31PR AAD97573-302         | [7122e4bd16](https://linux-hardware.org/?probe=7122e4bd16) | Sep 04, 2021 |
| Gigabyte      | M52LT-D3P                   | [09cbb5b50e](https://linux-hardware.org/?probe=09cbb5b50e) | Sep 03, 2021 |
| Gigabyte      | M52LT-D3P                   | [949b2062ea](https://linux-hardware.org/?probe=949b2062ea) | Sep 03, 2021 |
| ASRock        | G41M-S3                     | [c34caa75e2](https://linux-hardware.org/?probe=c34caa75e2) | Aug 23, 2021 |
| ASRock        | G41M-S3                     | [48360885d9](https://linux-hardware.org/?probe=48360885d9) | Aug 22, 2021 |
| MSI           | MS-7142                     | [2700c74bd9](https://linux-hardware.org/?probe=2700c74bd9) | Aug 21, 2021 |
| MSI           | MS-7142                     | [18ae0c1bb3](https://linux-hardware.org/?probe=18ae0c1bb3) | Aug 21, 2021 |
| HP            | 0AA8h                       | [d9a8fd3722](https://linux-hardware.org/?probe=d9a8fd3722) | Aug 15, 2021 |
| ASUSTek       | A7N8X-LA                    | [0e9fd81caf](https://linux-hardware.org/?probe=0e9fd81caf) | Aug 11, 2021 |
| ASUSTek       | A7N8X-LA                    | [f14c99bbce](https://linux-hardware.org/?probe=f14c99bbce) | Aug 11, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [b937ce5e88](https://linux-hardware.org/?probe=b937ce5e88) | Aug 10, 2021 |
| ASUSTek       | P7F-M                       | [cff87306ab](https://linux-hardware.org/?probe=cff87306ab) | Aug 07, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [a1768aa578](https://linux-hardware.org/?probe=a1768aa578) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [52aa712b0c](https://linux-hardware.org/?probe=52aa712b0c) | Aug 05, 2021 |
| ASUSTek       | PRIME Z370-A                | [05c1703574](https://linux-hardware.org/?probe=05c1703574) | Aug 03, 2021 |
| ASUSTek       | PRIME Z370-A                | [faf304d157](https://linux-hardware.org/?probe=faf304d157) | Aug 02, 2021 |
| OEM           | 45CMX/45GMX/45CMX-K         | [65d8eb687e](https://linux-hardware.org/?probe=65d8eb687e) | Jul 30, 2021 |
| ASUSTek       | P7F-M                       | [33a6186148](https://linux-hardware.org/?probe=33a6186148) | Jul 30, 2021 |
| Intel         | BTC-T37                     | [bb5051b598](https://linux-hardware.org/?probe=bb5051b598) | Jul 27, 2021 |
| ASRock        | FM2A85X Extreme4-M          | [aa0030f094](https://linux-hardware.org/?probe=aa0030f094) | Jul 26, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [763cb39ac0](https://linux-hardware.org/?probe=763cb39ac0) | Jul 25, 2021 |
| Gigabyte      | X570 AORUS PRO              | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [eef16a5b8f](https://linux-hardware.org/?probe=eef16a5b8f) | Jul 17, 2021 |
| Dell          | 08HPGT A01                  | [64d562d6ef](https://linux-hardware.org/?probe=64d562d6ef) | Jul 16, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [ab57bbf3d8](https://linux-hardware.org/?probe=ab57bbf3d8) | Jul 15, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| ASUSTek       | P7F-M                       | [3007b813c6](https://linux-hardware.org/?probe=3007b813c6) | Jul 13, 2021 |
| ASUSTek       | P7F-M                       | [5cfa1dcb4f](https://linux-hardware.org/?probe=5cfa1dcb4f) | Jul 12, 2021 |
| MSI           | H81M-E34                    | [14c2f8a49d](https://linux-hardware.org/?probe=14c2f8a49d) | Jul 05, 2021 |
| MSI           | A320M-A PRO                 | [9d356e787a](https://linux-hardware.org/?probe=9d356e787a) | Jul 01, 2021 |
| HP            | 0A98h                       | [40990f73a5](https://linux-hardware.org/?probe=40990f73a5) | Jun 22, 2021 |
| HP            | 0AA8h                       | [43103b39a5](https://linux-hardware.org/?probe=43103b39a5) | Jun 17, 2021 |
| Intel         | H61                         | [6b0bdb5986](https://linux-hardware.org/?probe=6b0bdb5986) | Jun 14, 2021 |
| HP            | 0AA8h                       | [9154911bc9](https://linux-hardware.org/?probe=9154911bc9) | Jun 13, 2021 |
| ASUSTek       | Maximus VI HERO             | [699d10613e](https://linux-hardware.org/?probe=699d10613e) | Jun 11, 2021 |
| ASUSTek       | Z97-K                       | [f0b9aa22e5](https://linux-hardware.org/?probe=f0b9aa22e5) | Jun 10, 2021 |
| Unknown       | Unknown                     | [3e408e9ead](https://linux-hardware.org/?probe=3e408e9ead) | May 31, 2021 |
| Unknown       | Unknown                     | [39b2780acf](https://linux-hardware.org/?probe=39b2780acf) | May 31, 2021 |
| Dell          | 0HY9JP A01                  | [3f6ddbd81d](https://linux-hardware.org/?probe=3f6ddbd81d) | May 30, 2021 |
| ASUSTek       | H61M-A/BR                   | [7d2b37e6e1](https://linux-hardware.org/?probe=7d2b37e6e1) | May 29, 2021 |
| ASRock        | G41M-S3                     | [adc801308b](https://linux-hardware.org/?probe=adc801308b) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | [d03d2796a0](https://linux-hardware.org/?probe=d03d2796a0) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | [200072e2a7](https://linux-hardware.org/?probe=200072e2a7) | May 29, 2021 |
| ASRock        | G41M-S3                     | [47f6c3e962](https://linux-hardware.org/?probe=47f6c3e962) | May 28, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | [cd3697bd15](https://linux-hardware.org/?probe=cd3697bd15) | May 25, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | [7c520b0d6e](https://linux-hardware.org/?probe=7c520b0d6e) | May 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [55d981b2ed](https://linux-hardware.org/?probe=55d981b2ed) | May 23, 2021 |
| Intel         | H61                         | [1954634de4](https://linux-hardware.org/?probe=1954634de4) | May 22, 2021 |
| ASUSTek       | P7F-M                       | [2ad3cb7346](https://linux-hardware.org/?probe=2ad3cb7346) | May 22, 2021 |
| Intel         | H61                         | [dad657a0bc](https://linux-hardware.org/?probe=dad657a0bc) | May 19, 2021 |
| Foxconn       | 945 7MC Series              | [f4634ec470](https://linux-hardware.org/?probe=f4634ec470) | May 17, 2021 |
| Dell          | 0FM586 A00                  | [8a955d2c5a](https://linux-hardware.org/?probe=8a955d2c5a) | May 16, 2021 |
| Intel         | H61                         | [76574dce75](https://linux-hardware.org/?probe=76574dce75) | May 16, 2021 |
| ASUSTek       | B150M-A                     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| Dell          | 0XR1GT A00                  | [a502e8842e](https://linux-hardware.org/?probe=a502e8842e) | May 12, 2021 |
| ASUSTek       | V-P7H55E                    | [3c0a297ede](https://linux-hardware.org/?probe=3c0a297ede) | May 08, 2021 |
| ASUSTek       | Crosshair V Formula         | [0fd87c485e](https://linux-hardware.org/?probe=0fd87c485e) | May 07, 2021 |
| ASUSTek       | P5KC                        | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASUSTek       | P5KC                        | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| ASUSTek       | P5KC                        | [50505c9ede](https://linux-hardware.org/?probe=50505c9ede) | Apr 30, 2021 |
| ASUSTek       | P5KC                        | [b51106e072](https://linux-hardware.org/?probe=b51106e072) | Apr 30, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [46b0bab7d8](https://linux-hardware.org/?probe=46b0bab7d8) | Apr 27, 2021 |
| Unknown       | Phitronics N68C-M           | [3076a5bae3](https://linux-hardware.org/?probe=3076a5bae3) | Apr 24, 2021 |
| Unknown       | Phitronics N68C-M           | [d3a56832d9](https://linux-hardware.org/?probe=d3a56832d9) | Apr 23, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [761a9ce0e9](https://linux-hardware.org/?probe=761a9ce0e9) | Apr 21, 2021 |
| ASUSTek       | P5Q DELUXE                  | [8ab143ec6b](https://linux-hardware.org/?probe=8ab143ec6b) | Apr 20, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [2813977a91](https://linux-hardware.org/?probe=2813977a91) | Apr 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [d6c3daff43](https://linux-hardware.org/?probe=d6c3daff43) | Apr 19, 2021 |
| ASUSTek       | V-P7H55E                    | [fb3b69b074](https://linux-hardware.org/?probe=fb3b69b074) | Apr 18, 2021 |
| Gigabyte      | M68MT-S2P                   | [47deff8a39](https://linux-hardware.org/?probe=47deff8a39) | Apr 17, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [16d03cb92f](https://linux-hardware.org/?probe=16d03cb92f) | Apr 12, 2021 |
| Dell          | 0KP561                      | [3579bff9c4](https://linux-hardware.org/?probe=3579bff9c4) | Apr 08, 2021 |
| DFI           | LP BI P45-T2S Elite         | [01f0babd70](https://linux-hardware.org/?probe=01f0babd70) | Apr 08, 2021 |
| ASUSTek       | PRIME Z390-P                | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| ASUSTek       | P5KC                        | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| Pegatron      | 2ADC                        | [e4bfddb8d9](https://linux-hardware.org/?probe=e4bfddb8d9) | Apr 04, 2021 |
| MSI           | MS-7267                     | [d16e8a4364](https://linux-hardware.org/?probe=d16e8a4364) | Apr 03, 2021 |
| Intel         | H61                         | [724cdd1804](https://linux-hardware.org/?probe=724cdd1804) | Mar 27, 2021 |
| Intel         | H61                         | [d7c3f87e52](https://linux-hardware.org/?probe=d7c3f87e52) | Mar 26, 2021 |
| Gigabyte      | Z77-D3H                     | [6ab1c423db](https://linux-hardware.org/?probe=6ab1c423db) | Mar 25, 2021 |
| MSI           | Z77A-GD65                   | [a9c3672597](https://linux-hardware.org/?probe=a9c3672597) | Mar 25, 2021 |
| Gigabyte      | Z77-D3H                     | [3b4565a813](https://linux-hardware.org/?probe=3b4565a813) | Mar 20, 2021 |
| ASUSTek       | M5A97 PRO                   | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| MSI           | MS-6785                     | [303c1ac636](https://linux-hardware.org/?probe=303c1ac636) | Mar 17, 2021 |
| ASUSTek       | P7F-M                       | [faee1ed378](https://linux-hardware.org/?probe=faee1ed378) | Mar 13, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | [f8503ecc3b](https://linux-hardware.org/?probe=f8503ecc3b) | Mar 10, 2021 |
| ECS           | A740GM-M                    | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| ASUSTek       | P7F-M                       | [a8d2e4fa56](https://linux-hardware.org/?probe=a8d2e4fa56) | Mar 07, 2021 |
| Unknown       | Unknown                     | [79e6e8bbfc](https://linux-hardware.org/?probe=79e6e8bbfc) | Mar 06, 2021 |
| ASRock        | G31M-GS                     | [ea6fbcd94e](https://linux-hardware.org/?probe=ea6fbcd94e) | Mar 02, 2021 |
| Acer          | EG43LMK                     | [249967a21a](https://linux-hardware.org/?probe=249967a21a) | Feb 28, 2021 |
| ASRock        | A320M-HDV R4.0              | [527b138b70](https://linux-hardware.org/?probe=527b138b70) | Feb 22, 2021 |
| Acer          | EG43LMK                     | [1c1fdf43c0](https://linux-hardware.org/?probe=1c1fdf43c0) | Feb 17, 2021 |
| MSI           | MS-7267                     | [6bf114a22f](https://linux-hardware.org/?probe=6bf114a22f) | Feb 15, 2021 |
| MSI           | MS-7267                     | [78e4d03c89](https://linux-hardware.org/?probe=78e4d03c89) | Feb 15, 2021 |
| Intel         | DP55WB AAE64798-206         | [4b2befb0d2](https://linux-hardware.org/?probe=4b2befb0d2) | Feb 14, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c8e67a7d41](https://linux-hardware.org/?probe=c8e67a7d41) | Feb 07, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [6e605fd64d](https://linux-hardware.org/?probe=6e605fd64d) | Feb 06, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [ec667e7b35](https://linux-hardware.org/?probe=ec667e7b35) | Feb 05, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [b71d20e5de](https://linux-hardware.org/?probe=b71d20e5de) | Feb 05, 2021 |
| ASUSTek       | Z97-K                       | [3adb6d9dc1](https://linux-hardware.org/?probe=3adb6d9dc1) | Feb 05, 2021 |
| ASRock        | X570 Taichi                 | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| ASRock        | H61M-HVS                    | [05c23c4247](https://linux-hardware.org/?probe=05c23c4247) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | [8c45cfc073](https://linux-hardware.org/?probe=8c45cfc073) | Feb 02, 2021 |
| ASUSTek       | P5E3 Deluxe                 | [47324765ec](https://linux-hardware.org/?probe=47324765ec) | Feb 02, 2021 |
| Unknown       | Unknown                     | [94d77e9dd0](https://linux-hardware.org/?probe=94d77e9dd0) | Feb 02, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [9761a3446c](https://linux-hardware.org/?probe=9761a3446c) | Jan 30, 2021 |
| Dell          | 03NVJ6 A02                  | [9c930ede42](https://linux-hardware.org/?probe=9c930ede42) | Jan 28, 2021 |
| MSI           | B450M-A PRO MAX             | [e5bc80f882](https://linux-hardware.org/?probe=e5bc80f882) | Jan 26, 2021 |
| Dell          | 0TT708 A01                  | [d04b2d493f](https://linux-hardware.org/?probe=d04b2d493f) | Jan 20, 2021 |
| Dell          | 0TT708 A01                  | [08ac15e868](https://linux-hardware.org/?probe=08ac15e868) | Jan 15, 2021 |
| Dell          | 0TT708 A01                  | [d60611163e](https://linux-hardware.org/?probe=d60611163e) | Jan 15, 2021 |
| Dell          | 0TT708 A01                  | [d0da7a44f7](https://linux-hardware.org/?probe=d0da7a44f7) | Jan 14, 2021 |
| Alienware     | 06G6JW A00                  | [992089d02a](https://linux-hardware.org/?probe=992089d02a) | Jan 12, 2021 |
| Intel         | DP55WB AAE64798-206         | [51ec8a1510](https://linux-hardware.org/?probe=51ec8a1510) | Jan 06, 2021 |
| ASUSTek       | P5K                         | [22a568db8e](https://linux-hardware.org/?probe=22a568db8e) | Jan 02, 2021 |
| ASUSTek       | P5K                         | [4233bd7b15](https://linux-hardware.org/?probe=4233bd7b15) | Jan 02, 2021 |
| MSI           | MS-6570                     | [f6bdec1638](https://linux-hardware.org/?probe=f6bdec1638) | Dec 28, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8396553751](https://linux-hardware.org/?probe=8396553751) | Dec 26, 2020 |
| MSI           | Z87 MPOWER MAX              | [5db0b2dedf](https://linux-hardware.org/?probe=5db0b2dedf) | Dec 23, 2020 |
| MSI           | MS-7541                     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| ASUSTek       | Maximus VI HERO             | [862b159eb2](https://linux-hardware.org/?probe=862b159eb2) | Dec 19, 2020 |
| Toshiba       | STI 910123                  | [f9f7a69232](https://linux-hardware.org/?probe=f9f7a69232) | Dec 18, 2020 |
| Toshiba       | STI 910123                  | [ae79e069f3](https://linux-hardware.org/?probe=ae79e069f3) | Dec 18, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | [fdc26c9f6d](https://linux-hardware.org/?probe=fdc26c9f6d) | Dec 18, 2020 |
| ASUSTek       | P8B75-V                     | [edb814f54a](https://linux-hardware.org/?probe=edb814f54a) | Dec 15, 2020 |
| ASUSTek       | Z97-K                       | [5b78a6b7ee](https://linux-hardware.org/?probe=5b78a6b7ee) | Dec 13, 2020 |
| ASUSTek       | Z97-K                       | [e1afb118e5](https://linux-hardware.org/?probe=e1afb118e5) | Dec 12, 2020 |
| Acer          | Aspire XC600 v1.0           | [5a3c92338e](https://linux-hardware.org/?probe=5a3c92338e) | Dec 08, 2020 |
| EVGA          | 131-HE-E095                 | [8fca80343b](https://linux-hardware.org/?probe=8fca80343b) | Dec 08, 2020 |
| HP            | 1496                        | [61eeea25ed](https://linux-hardware.org/?probe=61eeea25ed) | Dec 04, 2020 |
| Dell          | 0XPDFK A01                  | [02ffa180c8](https://linux-hardware.org/?probe=02ffa180c8) | Nov 30, 2020 |
| ASRock        | X370 Taichi                 | [a229c68d0e](https://linux-hardware.org/?probe=a229c68d0e) | Nov 27, 2020 |
| Gigabyte      | 945GM-S2                    | [1bbf0f874b](https://linux-hardware.org/?probe=1bbf0f874b) | Nov 26, 2020 |
| MSI           | B85M-G43                    | [dee4fcacb7](https://linux-hardware.org/?probe=dee4fcacb7) | Nov 26, 2020 |
| Gigabyte      | H81M-S2PV                   | [1c5cc4c12e](https://linux-hardware.org/?probe=1c5cc4c12e) | Nov 25, 2020 |
| Dell          | 0F6X5P A00                  | [458d498ed4](https://linux-hardware.org/?probe=458d498ed4) | Nov 24, 2020 |
| ASUSTek       | M4A785TD-V EVO              | [c03bf04e1e](https://linux-hardware.org/?probe=c03bf04e1e) | Nov 15, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [2fe3e165eb](https://linux-hardware.org/?probe=2fe3e165eb) | Oct 31, 2020 |
| Dell          | 0DR845                      | [958876c9d6](https://linux-hardware.org/?probe=958876c9d6) | Oct 27, 2020 |
| HP            | 843B                        | [cf9214c9e8](https://linux-hardware.org/?probe=cf9214c9e8) | Oct 25, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [c637e2732a](https://linux-hardware.org/?probe=c637e2732a) | Oct 22, 2020 |
| Unknown       | Unknown                     | [d5b1adf1cc](https://linux-hardware.org/?probe=d5b1adf1cc) | Oct 21, 2020 |
| MSI           | Z97 GAMING 3                | [d70dc5679f](https://linux-hardware.org/?probe=d70dc5679f) | Oct 15, 2020 |
| ASUSTek       | P7F-M                       | [a931f70b33](https://linux-hardware.org/?probe=a931f70b33) | Oct 14, 2020 |
| HP            | 304Ah                       | [720e05d59c](https://linux-hardware.org/?probe=720e05d59c) | Oct 04, 2020 |
| HP            | 304Ah                       | [e8bf5f6700](https://linux-hardware.org/?probe=e8bf5f6700) | Oct 04, 2020 |
| HP            | 304Ah                       | [298b55e06b](https://linux-hardware.org/?probe=298b55e06b) | Sep 28, 2020 |
| HP            | 304Ah                       | [5a86fa2901](https://linux-hardware.org/?probe=5a86fa2901) | Sep 28, 2020 |
| HP            | 304Ah                       | [e72550a43e](https://linux-hardware.org/?probe=e72550a43e) | Sep 28, 2020 |
| HP            | 304Ah                       | [11dc9e4238](https://linux-hardware.org/?probe=11dc9e4238) | Sep 28, 2020 |
| ASUSTek       | P8H61-MX USB3               | [2def8c0128](https://linux-hardware.org/?probe=2def8c0128) | Sep 19, 2020 |
| ASUSTek       | P5E3 Deluxe                 | [694576f25f](https://linux-hardware.org/?probe=694576f25f) | Sep 14, 2020 |
| ASUSTek       | B150 PRO GAMING/AURA        | [e5260021d2](https://linux-hardware.org/?probe=e5260021d2) | Sep 06, 2020 |
| Dell          | 0DR845                      | [f9dfefaf63](https://linux-hardware.org/?probe=f9dfefaf63) | Aug 31, 2020 |
| Gigabyte      | EP45C-DS3R                  | [3baa06afa2](https://linux-hardware.org/?probe=3baa06afa2) | Aug 24, 2020 |
| ECS           | KAM1-I                      | [cef51c9cd7](https://linux-hardware.org/?probe=cef51c9cd7) | Aug 15, 2020 |
| MSI           | D2414 S26361-D2414-A10      | [a0ea23eae8](https://linux-hardware.org/?probe=a0ea23eae8) | Aug 10, 2020 |
| Unknown       | P4M800Pro-8237              | [e632211d18](https://linux-hardware.org/?probe=e632211d18) | Aug 04, 2020 |
| Gigabyte      | Z77-D3H                     | [05331a0b70](https://linux-hardware.org/?probe=05331a0b70) | Aug 04, 2020 |
| Intel         | DG33FB AAD81072-309         | [217bfd48bd](https://linux-hardware.org/?probe=217bfd48bd) | Aug 04, 2020 |
| Dell          | 0DR845                      | [a70d949ebc](https://linux-hardware.org/?probe=a70d949ebc) | Jul 30, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | [4af42f19bb](https://linux-hardware.org/?probe=4af42f19bb) | Jul 14, 2020 |
| HP            | 3396                        | [53167bce1a](https://linux-hardware.org/?probe=53167bce1a) | Jul 09, 2020 |
| ASUSTek       | G11DF                       | [73ddfc32aa](https://linux-hardware.org/?probe=73ddfc32aa) | Jun 23, 2020 |
| ASUSTek       | G11DF                       | [497ebd9b60](https://linux-hardware.org/?probe=497ebd9b60) | Jun 23, 2020 |
| Biostar       | NF61S-M2A                   | [c071fa24d8](https://linux-hardware.org/?probe=c071fa24d8) | Jun 21, 2020 |
| Dell          | 0DR845                      | [9d1640a3a7](https://linux-hardware.org/?probe=9d1640a3a7) | Jun 20, 2020 |
| PCWare        | IPMH81G1                    | [416c3e2997](https://linux-hardware.org/?probe=416c3e2997) | Jun 07, 2020 |
| Dell          | 0200DY A03                  | [aebb17da40](https://linux-hardware.org/?probe=aebb17da40) | Jun 01, 2020 |
| Dell          | 0DR845                      | [4b8a511c08](https://linux-hardware.org/?probe=4b8a511c08) | May 29, 2020 |
| Dell          | 042P49 A00                  | [aca1fb8ea1](https://linux-hardware.org/?probe=aca1fb8ea1) | May 21, 2020 |
| Dell          | 042P49 A00                  | [ec868da9dd](https://linux-hardware.org/?probe=ec868da9dd) | May 20, 2020 |
| Dell          | 042P49 A00                  | [6ba5e37491](https://linux-hardware.org/?probe=6ba5e37491) | May 20, 2020 |
| Dell          | 042P49 A00                  | [8e547a1414](https://linux-hardware.org/?probe=8e547a1414) | May 20, 2020 |
| Unknown       | Unknown                     | [cf5fe3dbce](https://linux-hardware.org/?probe=cf5fe3dbce) | May 17, 2020 |
| ASRock        | B75M R2.0                   | [efd3354b61](https://linux-hardware.org/?probe=efd3354b61) | May 10, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | [1a79fa9925](https://linux-hardware.org/?probe=1a79fa9925) | May 03, 2020 |
| ASRock        | J4205-ITX                   | [4fc5d5a325](https://linux-hardware.org/?probe=4fc5d5a325) | Apr 22, 2020 |
| ECS           | Nettle2                     | [ababaf523c](https://linux-hardware.org/?probe=ababaf523c) | Apr 19, 2020 |
| Unknown       | Unknown                     | [12c198a6f5](https://linux-hardware.org/?probe=12c198a6f5) | Apr 18, 2020 |
| Unknown       | Unknown                     | [cc77c3c7c4](https://linux-hardware.org/?probe=cc77c3c7c4) | Apr 16, 2020 |
| Unknown       | Unknown                     | [5ca6d3f366](https://linux-hardware.org/?probe=5ca6d3f366) | Apr 14, 2020 |
| Unknown       | Unknown                     | [0d1b40e847](https://linux-hardware.org/?probe=0d1b40e847) | Apr 14, 2020 |
| ASRock        | N68-GS3 UCC                 | [3cc8e9e496](https://linux-hardware.org/?probe=3cc8e9e496) | Apr 12, 2020 |
| ASRock        | N68-GS3 UCC                 | [8822c3378d](https://linux-hardware.org/?probe=8822c3378d) | Apr 12, 2020 |
| HP            | 8526 MVB, A                 | [30e90998e1](https://linux-hardware.org/?probe=30e90998e1) | Apr 08, 2020 |
| Gigabyte      | B450M DS3H-CF               | [b660991573](https://linux-hardware.org/?probe=b660991573) | Mar 29, 2020 |
| MSI           | G31M2                       | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
| Acer          | Aspire TC-605               | [495fffaa63](https://linux-hardware.org/?probe=495fffaa63) | Mar 26, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | [fb006f397c](https://linux-hardware.org/?probe=fb006f397c) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | [5c7e0a86df](https://linux-hardware.org/?probe=5c7e0a86df) | Mar 24, 2020 |
| Dell          | 018D1Y A01                  | [c6a5cf98ee](https://linux-hardware.org/?probe=c6a5cf98ee) | Mar 24, 2020 |
| Gigabyte      | Z370 AORUS Gaming 7         | [0c52aebe31](https://linux-hardware.org/?probe=0c52aebe31) | Mar 23, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 4.19.0-16-amd64     | 24       | 16.78%  |
| 4.19.0-17-amd64     | 19       | 13.29%  |
| 4.19.0-14-amd64     | 18       | 12.59%  |
| 4.19.0-13-amd64     | 17       | 11.89%  |
| 4.19.0-8-amd64      | 14       | 9.79%   |
| 4.19.0-12-amd64     | 9        | 6.29%   |
| 4.19.0-10-amd64     | 8        | 5.59%   |
| 4.19.0-9-amd64      | 7        | 4.9%    |
| 4.19.0-18-amd64     | 4        | 2.8%    |
| 4.19.0-11-amd64     | 4        | 2.8%    |
| 4.19.0-17-686       | 3        | 2.1%    |
| 4.19.0-16-686       | 3        | 2.1%    |
| 4.19.0-14-686       | 3        | 2.1%    |
| 4.19.0-8-686        | 2        | 1.4%    |
| 4.19.0-13-686       | 2        | 1.4%    |
| 5.8.0-3-amd64       | 1        | 0.7%    |
| 5.6.0-0.bpo.2-amd64 | 1        | 0.7%    |
| 5.4.0-0.bpo.4-amd64 | 1        | 0.7%    |
| 5.10.0-7-amd64      | 1        | 0.7%    |
| 4.19.0-9-686        | 1        | 0.7%    |
| 4.19.0-12-686       | 1        | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 124      | 96.88%  |
| 5.8.0   | 1        | 0.78%   |
| 5.6.0   | 1        | 0.78%   |
| 5.4.0   | 1        | 0.78%   |
| 5.10.0  | 1        | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 124      | 96.88%  |
| 5.8     | 1        | 0.78%   |
| 5.6     | 1        | 0.78%   |
| 5.4     | 1        | 0.78%   |
| 5.10    | 1        | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 113      | 88.28%  |
| i686   | 15       | 11.72%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 114      | 88.37%  |
| Cinnamon   | 6        | 4.65%   |
| Unknown    | 3        | 2.33%   |
| MATE       | 2        | 1.55%   |
| XFCE       | 1        | 0.78%   |
| LXQt       | 1        | 0.78%   |
| LXDE       | 1        | 0.78%   |
| GNOME      | 1        | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 128      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 116      | 90.63%  |
| TDM     | 8        | 6.25%   |
| LightDM | 3        | 2.34%   |
| GDM     | 1        | 0.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Desktops | Percent |
|--------|----------|---------|
| en_US  | 32       | 25%     |
| pt_BR  | 14       | 10.94%  |
| de_DE  | 14       | 10.94%  |
| fr_FR  | 12       | 9.38%   |
| pl_PL  | 6        | 4.69%   |
| ru_RU  | 5        | 3.91%   |
| en_GB  | 5        | 3.91%   |
| sv_SE  | 3        | 2.34%   |
| nl_BE  | 3        | 2.34%   |
| es_AR  | 3        | 2.34%   |
| en_AU  | 3        | 2.34%   |
| pt_PT  | 2        | 1.56%   |
| it_IT  | 2        | 1.56%   |
| hu_HU  | 2        | 1.56%   |
| en_CA  | 2        | 1.56%   |
| unm_US | 1        | 0.78%   |
| uk_UA  | 1        | 0.78%   |
| tr_TR  | 1        | 0.78%   |
| sk_SK  | 1        | 0.78%   |
| nb_NO  | 1        | 0.78%   |
| fr_CA  | 1        | 0.78%   |
| fi_FI  | 1        | 0.78%   |
| et_EE  | 1        | 0.78%   |
| es_UY  | 1        | 0.78%   |
| es_MX  | 1        | 0.78%   |
| es_ES  | 1        | 0.78%   |
| es_CO  | 1        | 0.78%   |
| es_CL  | 1        | 0.78%   |
| en_ZA  | 1        | 0.78%   |
| el_GR  | 1        | 0.78%   |
| de_AT  | 1        | 0.78%   |
| cs_CZ  | 1        | 0.78%   |
| ca_ES  | 1        | 0.78%   |
| bg_BG  | 1        | 0.78%   |
| ar_EG  | 1        | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 89       | 69.53%  |
| EFI  | 39       | 30.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 122      | 94.57%  |
| Btrfs   | 4        | 3.1%    |
| Unknown | 2        | 1.55%   |
| Ext3    | 1        | 0.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 115      | 88.46%  |
| GPT     | 10       | 7.69%   |
| MBR     | 5        | 3.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 95.38%  |
| Yes       | 6        | 4.62%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 95.31%  |
| Yes       | 6        | 4.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 30       | 23.44%  |
| Gigabyte Technology | 18       | 14.06%  |
| MSI                 | 16       | 12.5%   |
| Dell                | 13       | 10.16%  |
| ASRock              | 10       | 7.81%   |
| Hewlett-Packard     | 8        | 6.25%   |
| Unknown             | 7        | 5.47%   |
| Intel               | 5        | 3.91%   |
| ECS                 | 3        | 2.34%   |
| Acer                | 3        | 2.34%   |
| Pegatron            | 2        | 1.56%   |
| EVGA                | 2        | 1.56%   |
| Biostar             | 2        | 1.56%   |
| Semp Toshiba        | 1        | 0.78%   |
| Positivo            | 1        | 0.78%   |
| PCWare              | 1        | 0.78%   |
| OEM                 | 1        | 0.78%   |
| Lenovo              | 1        | 0.78%   |
| Fujitsu Siemens     | 1        | 0.78%   |
| Foxconn             | 1        | 0.78%   |
| DFI                 | 1        | 0.78%   |
| Alienware           | 1        | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 7        | 5.47%   |
| Dell OptiPlex 780                  | 2        | 1.56%   |
| ASUS All Series                    | 2        | 1.56%   |
| Semp Toshiba STI                   | 1        | 0.78%   |
| Positivo POS-EIH61CE               | 1        | 0.78%   |
| Pegatron Elite 7300 Series MT      | 1        | 0.78%   |
| Pegatron 520-1188la                | 1        | 0.78%   |
| PCWare IPMH81G1                    | 1        | 0.78%   |
| OEM 45CMX/45GMX/45CMX-K            | 1        | 0.78%   |
| MSI PX714AA-ABH t3040.nl           | 1        | 0.78%   |
| MSI MS-7C52                        | 1        | 0.78%   |
| MSI MS-7C51                        | 1        | 0.78%   |
| MSI MS-7A40                        | 1        | 0.78%   |
| MSI MS-7918                        | 1        | 0.78%   |
| MSI MS-7823                        | 1        | 0.78%   |
| MSI MS-7817                        | 1        | 0.78%   |
| MSI MS-7815                        | 1        | 0.78%   |
| MSI MS-7751                        | 1        | 0.78%   |
| MSI MS-7383                        | 1        | 0.78%   |
| MSI MS-7267                        | 1        | 0.78%   |
| MSI MS-7142                        | 1        | 0.78%   |
| MSI MS-6785                        | 1        | 0.78%   |
| MSI MS-6570                        | 1        | 0.78%   |
| MSI ESPRIMO P2440                  | 1        | 0.78%   |
| MSI *MF                            | 1        | 0.78%   |
| Lenovo ThinkCentre M93p 10AB0010US | 1        | 0.78%   |
| Intel H61                          | 1        | 0.78%   |
| Intel DP55WB AAE64798-206          | 1        | 0.78%   |
| Intel DG33FB AAD81072-309          | 1        | 0.78%   |
| Intel DG31PR AAD97573-302          | 1        | 0.78%   |
| Intel BTC-T37                      | 1        | 0.78%   |
| HP xw8600 Workstation              | 1        | 0.78%   |
| HP Pavilion Desktop 590-p0xxx      | 1        | 0.78%   |
| HP Desktop 190-0xxx                | 1        | 0.78%   |
| HP Compaq Elite 8300 CMT           | 1        | 0.78%   |
| HP Compaq dc7800 Small Form Factor | 1        | 0.78%   |
| HP Compaq 8200 Elite USDT PC       | 1        | 0.78%   |
| HP Compaq 8100 Elite SFF PC        | 1        | 0.78%   |
| HP 290 G2 MT Business PC           | 1        | 0.78%   |
| Gigabyte Z97-D3H                   | 1        | 0.78%   |
| Gigabyte Z77-D3H                   | 1        | 0.78%   |
| Gigabyte Z390 M GAMING             | 1        | 0.78%   |
| Gigabyte Z390 DESIGNARE            | 1        | 0.78%   |
| Gigabyte Z370 AORUS Gaming 7       | 1        | 0.78%   |
| Gigabyte X570 AORUS ULTRA          | 1        | 0.78%   |
| Gigabyte X570 AORUS PRO            | 1        | 0.78%   |
| Gigabyte M68MT-S2P                 | 1        | 0.78%   |
| Gigabyte M52LT-D3P                 | 1        | 0.78%   |
| Gigabyte H81M-S2PV                 | 1        | 0.78%   |
| Gigabyte H61M-S1                   | 1        | 0.78%   |
| Gigabyte H61M-DS2 DVI              | 1        | 0.78%   |
| Gigabyte GA-880GM-UD2H             | 1        | 0.78%   |
| Gigabyte GA-78LMT-USB3 6.0         | 1        | 0.78%   |
| Gigabyte EP45C-DS3R                | 1        | 0.78%   |
| Gigabyte COMFOR OFFICE I33         | 1        | 0.78%   |
| Gigabyte B450M DS3H                | 1        | 0.78%   |
| Gigabyte 945GM-S2                  | 1        | 0.78%   |
| Fujitsu Siemens D2264-A1           | 1        | 0.78%   |
| Foxconn 945 7MC Series             | 1        | 0.78%   |
| EVGA 132-BL-E758 Tylersburg        | 1        | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Dell OptiPlex            | 8        | 6.25%   |
| Unknown                  | 7        | 5.47%   |
| HP Compaq                | 4        | 3.13%   |
| ASUS PRIME               | 4        | 3.13%   |
| Dell Inspiron            | 3        | 2.34%   |
| Gigabyte Z390            | 2        | 1.56%   |
| Gigabyte X570            | 2        | 1.56%   |
| Dell Precision           | 2        | 1.56%   |
| ASUS ROG                 | 2        | 1.56%   |
| ASUS P5KPL-AM            | 2        | 1.56%   |
| ASUS All                 | 2        | 1.56%   |
| Acer Aspire              | 2        | 1.56%   |
| Semp Toshiba STI         | 1        | 0.78%   |
| Positivo POS-EIH61CE     | 1        | 0.78%   |
| Pegatron Elite           | 1        | 0.78%   |
| Pegatron 520-1188la      | 1        | 0.78%   |
| PCWare IPMH81G1          | 1        | 0.78%   |
| OEM 45CMX                | 1        | 0.78%   |
| MSI PX714AA-ABH          | 1        | 0.78%   |
| MSI MS-7C52              | 1        | 0.78%   |
| MSI MS-7C51              | 1        | 0.78%   |
| MSI MS-7A40              | 1        | 0.78%   |
| MSI MS-7918              | 1        | 0.78%   |
| MSI MS-7823              | 1        | 0.78%   |
| MSI MS-7817              | 1        | 0.78%   |
| MSI MS-7815              | 1        | 0.78%   |
| MSI MS-7751              | 1        | 0.78%   |
| MSI MS-7383              | 1        | 0.78%   |
| MSI MS-7267              | 1        | 0.78%   |
| MSI MS-7142              | 1        | 0.78%   |
| MSI MS-6785              | 1        | 0.78%   |
| MSI MS-6570              | 1        | 0.78%   |
| MSI ESPRIMO              | 1        | 0.78%   |
| MSI *MF                  | 1        | 0.78%   |
| Lenovo ThinkCentre       | 1        | 0.78%   |
| Intel H61                | 1        | 0.78%   |
| Intel DP55WB             | 1        | 0.78%   |
| Intel DG33FB             | 1        | 0.78%   |
| Intel DG31PR             | 1        | 0.78%   |
| Intel BTC-T37            | 1        | 0.78%   |
| HP xw8600                | 1        | 0.78%   |
| HP Pavilion              | 1        | 0.78%   |
| HP Desktop               | 1        | 0.78%   |
| HP 290                   | 1        | 0.78%   |
| Gigabyte Z97-D3H         | 1        | 0.78%   |
| Gigabyte Z77-D3H         | 1        | 0.78%   |
| Gigabyte Z370            | 1        | 0.78%   |
| Gigabyte M68MT-S2P       | 1        | 0.78%   |
| Gigabyte M52LT-D3P       | 1        | 0.78%   |
| Gigabyte H81M-S2PV       | 1        | 0.78%   |
| Gigabyte H61M-S1         | 1        | 0.78%   |
| Gigabyte H61M-DS2        | 1        | 0.78%   |
| Gigabyte GA-880GM-UD2H   | 1        | 0.78%   |
| Gigabyte GA-78LMT-USB3   | 1        | 0.78%   |
| Gigabyte EP45C-DS3R      | 1        | 0.78%   |
| Gigabyte COMFOR          | 1        | 0.78%   |
| Gigabyte B450M           | 1        | 0.78%   |
| Gigabyte 945GM-S2        | 1        | 0.78%   |
| Fujitsu Siemens D2264-A1 | 1        | 0.78%   |
| Foxconn 945              | 1        | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 15       | 11.72%  |
| 2010 | 14       | 10.94%  |
| 2019 | 11       | 8.59%   |
| 2007 | 11       | 8.59%   |
| 2020 | 9        | 7.03%   |
| 2018 | 9        | 7.03%   |
| 2008 | 9        | 7.03%   |
| 2014 | 8        | 6.25%   |
| 2011 | 8        | 6.25%   |
| 2013 | 7        | 5.47%   |
| 2021 | 5        | 3.91%   |
| 2016 | 5        | 3.91%   |
| 2015 | 5        | 3.91%   |
| 2009 | 5        | 3.91%   |
| 2005 | 3        | 2.34%   |
| 2003 | 2        | 1.56%   |
| 2017 | 1        | 0.78%   |
| 2004 | 1        | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 128      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 126      | 98.44%  |
| Enabled  | 2        | 1.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 128      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 34       | 25.95%  |
| 3.01-4.0    | 29       | 22.14%  |
| 16.01-24.0  | 24       | 18.32%  |
| 4.01-8.0    | 17       | 12.98%  |
| 32.01-64.0  | 10       | 7.63%   |
| 2.01-3.0    | 8        | 6.11%   |
| 1.01-2.0    | 6        | 4.58%   |
| 0.51-1.0    | 2        | 1.53%   |
| 64.01-256.0 | 1        | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 63       | 45.65%  |
| 2.01-3.0 | 30       | 21.74%  |
| 3.01-4.0 | 19       | 13.77%  |
| 0.51-1.0 | 16       | 11.59%  |
| 4.01-8.0 | 10       | 7.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 61       | 45.86%  |
| 2      | 43       | 32.33%  |
| 3      | 14       | 10.53%  |
| 4      | 7        | 5.26%   |
| 7      | 4        | 3.01%   |
| 5      | 2        | 1.5%    |
| 8      | 1        | 0.75%   |
| 6      | 1        | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 79       | 60.31%  |
| No        | 52       | 39.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 128      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 61.83%  |
| Yes       | 50       | 38.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 79.84%  |
| Yes       | 26       | 20.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 17       | 13.28%  |
| USA          | 15       | 11.72%  |
| Brazil       | 14       | 10.94%  |
| France       | 11       | 8.59%   |
| Poland       | 5        | 3.91%   |
| Canada       | 5        | 3.91%   |
| Ukraine      | 4        | 3.13%   |
| UK           | 4        | 3.13%   |
| Netherlands  | 4        | 3.13%   |
| Russia       | 3        | 2.34%   |
| Bulgaria     | 3        | 2.34%   |
| Belgium      | 3        | 2.34%   |
| Argentina    | 3        | 2.34%   |
| Sweden       | 2        | 1.56%   |
| Spain        | 2        | 1.56%   |
| Portugal     | 2        | 1.56%   |
| Italy        | 2        | 1.56%   |
| Hungary      | 2        | 1.56%   |
| Greece       | 2        | 1.56%   |
| Finland      | 2        | 1.56%   |
| Austria      | 2        | 1.56%   |
| Australia    | 2        | 1.56%   |
| Uruguay      | 1        | 0.78%   |
| Turkey       | 1        | 0.78%   |
| South Africa | 1        | 0.78%   |
| Slovakia     | 1        | 0.78%   |
| Serbia       | 1        | 0.78%   |
| Romania      | 1        | 0.78%   |
| Puerto Rico  | 1        | 0.78%   |
| Philippines  | 1        | 0.78%   |
| Norway       | 1        | 0.78%   |
| Mexico       | 1        | 0.78%   |
| Luxembourg   | 1        | 0.78%   |
| India        | 1        | 0.78%   |
| Estonia      | 1        | 0.78%   |
| Egypt        | 1        | 0.78%   |
| Czechia      | 1        | 0.78%   |
| Croatia      | 1        | 0.78%   |
| Colombia     | 1        | 0.78%   |
| Chile        | 1        | 0.78%   |
| Belarus      | 1        | 0.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Paris                         | 4        | 2.96%   |
| Toronto                       | 2        | 1.48%   |
| Sofia                         | 2        | 1.48%   |
| Rio de Janeiro                | 2        | 1.48%   |
| Perth                         | 2        | 1.48%   |
| Helsinki                      | 2        | 1.48%   |
| Hamburg                       | 2        | 1.48%   |
| Florian??polis                | 2        | 1.48%   |
| Braunschweig                  | 2        | 1.48%   |
| Belo Horizonte                | 2        | 1.48%   |
| Yalta                         | 1        | 0.74%   |
| Wroclaw                       | 1        | 0.74%   |
| Wernberg-Koblitz              | 1        | 0.74%   |
| Warsaw                        | 1        | 0.74%   |
| Vienna                        | 1        | 0.74%   |
| Ulm                           | 1        | 0.74%   |
| Ukhta                         | 1        | 0.74%   |
| Trpinja                       | 1        | 0.74%   |
| Tires                         | 1        | 0.74%   |
| Timișoara                    | 1        | 0.74%   |
| Thornton                      | 1        | 0.74%   |
| The Hague                     | 1        | 0.74%   |
| Thaur                         | 1        | 0.74%   |
| Taby                          | 1        | 0.74%   |
| São Luís                    | 1        | 0.74%   |
| Stroud                        | 1        | 0.74%   |
| Souda                         | 1        | 0.74%   |
| Shimla                        | 1        | 0.74%   |
| Sherbrooke                    | 1        | 0.74%   |
| Seibersbach                   | 1        | 0.74%   |
| Santiago                      | 1        | 0.74%   |
| Santa Rosa                    | 1        | 0.74%   |
| San Juan                      | 1        | 0.74%   |
| San Giorgio della Richinvelda | 1        | 0.74%   |
| San Antonio                   | 1        | 0.74%   |
| Salem                         | 1        | 0.74%   |
| Saint-Brice-Courcelles        | 1        | 0.74%   |
| Rotterdam                     | 1        | 0.74%   |
| Ribeirão Preto               | 1        | 0.74%   |
| Rhyl                          | 1        | 0.74%   |
| Rapla                         | 1        | 0.74%   |
| Radom                         | 1        | 0.74%   |
| Puerto Vallarta               | 1        | 0.74%   |
| Presidente Prudente           | 1        | 0.74%   |
| Poznan                        | 1        | 0.74%   |
| Plovdiv                       | 1        | 0.74%   |
| Pasto                         | 1        | 0.74%   |
| Partizánske                  | 1        | 0.74%   |
| Park City                     | 1        | 0.74%   |
| Paracin                       | 1        | 0.74%   |
| Osasco                        | 1        | 0.74%   |
| Offenburg                     | 1        | 0.74%   |
| Novokuybyshevsk               | 1        | 0.74%   |
| Niagara Falls                 | 1        | 0.74%   |
| Munich                        | 1        | 0.74%   |
| Montreal                      | 1        | 0.74%   |
| Montevideo                    | 1        | 0.74%   |
| Mogilev                       | 1        | 0.74%   |
| Minya                         | 1        | 0.74%   |
| Milan                         | 1        | 0.74%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 50       | 84     | 23.7%   |
| Seagate             | 36       | 61     | 17.06%  |
| Samsung Electronics | 35       | 53     | 16.59%  |
| Kingston            | 11       | 13     | 5.21%   |
| Hitachi             | 11       | 14     | 5.21%   |
| Toshiba             | 10       | 15     | 4.74%   |
| SanDisk             | 8        | 11     | 3.79%   |
| Crucial             | 7        | 9      | 3.32%   |
| Phison              | 6        | 7      | 2.84%   |
| A-DATA Technology   | 6        | 6      | 2.84%   |
| Intel               | 4        | 4      | 1.9%    |
| MAXTOR              | 3        | 5      | 1.42%   |
| Intenso             | 3        | 4      | 1.42%   |
| China               | 3        | 3      | 1.42%   |
| TCSUNBOW            | 2        | 2      | 0.95%   |
| OCZ                 | 2        | 3      | 0.95%   |
| Micron Technology   | 2        | 2      | 0.95%   |
| Unknown             | 1        | 2      | 0.47%   |
| Team                | 1        | 2      | 0.47%   |
| Silicon Motion      | 1        | 1      | 0.47%   |
| SABRENT             | 1        | 1      | 0.47%   |
| Patriot             | 1        | 1      | 0.47%   |
| Mushkin             | 1        | 1      | 0.47%   |
| Kingmax             | 1        | 1      | 0.47%   |
| KESU                | 1        | 2      | 0.47%   |
| HPE                 | 1        | 5      | 0.47%   |
| Fujitsu             | 1        | 1      | 0.47%   |
| ExcelStor           | 1        | 1      | 0.47%   |
| Dogfish             | 1        | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB              | 4        | 1.6%    |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 1.6%    |
| Samsung SSD 860 EVO 500GB           | 3        | 1.2%    |
| Samsung HD322HJ 320GB               | 3        | 1.2%    |
| Samsung HD103SJ 1TB                 | 3        | 1.2%    |
| Kingston SA400S37120G 120GB SSD     | 3        | 1.2%    |
| WDC WD5000AAKX-00U6AA0 500GB        | 2        | 0.8%    |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.8%    |
| WDC WD3200AAKS-00L9A0 320GB         | 2        | 0.8%    |
| WDC WD2500AAKX-753CA1 250GB         | 2        | 0.8%    |
| WDC WD1600AABS-00PRA0 160GB         | 2        | 0.8%    |
| WDC WD10EZEX-60WN4A0 1TB            | 2        | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB            | 2        | 0.8%    |
| Seagate ST2000LX001-1RG174 2TB      | 2        | 0.8%    |
| Seagate ST2000DM001-9YN164 2TB      | 2        | 0.8%    |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 0.8%    |
| Seagate Expansion 1TB               | 2        | 0.8%    |
| Samsung SSD 850 EVO 500GB           | 2        | 0.8%    |
| Samsung SSD 850 EVO 250GB           | 2        | 0.8%    |
| Samsung SP0802N 80GB                | 2        | 0.8%    |
| Samsung NVMe SSD Drive 2TB          | 2        | 0.8%    |
| Samsung NVMe SSD Drive 256GB        | 2        | 0.8%    |
| Samsung HD161HJ 160GB               | 2        | 0.8%    |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2        | 0.8%    |
| Kingston SV300S37A120G 120GB SSD    | 2        | 0.8%    |
| Kingston SA400S37240G 240GB SSD     | 2        | 0.8%    |
| Crucial CT500MX500SSD1 500GB        | 2        | 0.8%    |
| Crucial CT240BX500SSD1 240GB        | 2        | 0.8%    |
| A-DATA SU650 240GB SSD              | 2        | 0.8%    |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1        | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1        | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1        | 0.4%    |
| WDC WDS120G1G0A-00SS50 120GB SSD    | 1        | 0.4%    |
| WDC WDBNCE2500PNC 250GB SSD         | 1        | 0.4%    |
| WDC WD6400AAKS-07A7B0 640GB         | 1        | 0.4%    |
| WDC WD6002FRYZ-01WD5B1 6TB          | 1        | 0.4%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.4%    |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1        | 0.4%    |
| WDC WD5000BEVT-60ZAT1 500GB         | 1        | 0.4%    |
| WDC WD5000AAVS-32ZTB0 500GB         | 1        | 0.4%    |
| WDC WD5000AAKX-75U6AA0 500GB        | 1        | 0.4%    |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 0.4%    |
| WDC WD5000AAKX-083CA1 500GB         | 1        | 0.4%    |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 0.4%    |
| WDC WD5000AAKX-001CA0 500GB         | 1        | 0.4%    |
| WDC WD5000AAKS-75A7B0 500GB         | 1        | 0.4%    |
| WDC WD5000AAKS-22A7B0 500GB         | 1        | 0.4%    |
| WDC WD5000AAKS-07A7B2 500GB         | 1        | 0.4%    |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 0.4%    |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 0.4%    |
| WDC WD400EB-00CPF0 40GB             | 1        | 0.4%    |
| WDC WD360ADFD-00NLR5 37GB           | 1        | 0.4%    |
| WDC WD3200AVJS-63N9A0 320GB         | 1        | 0.4%    |
| WDC WD3200AAJS-22L7A0 320GB         | 1        | 0.4%    |
| WDC WD3200AAJS-00VWA0 320GB         | 1        | 0.4%    |
| WDC WD3200AAJS-00L7A0 320GB         | 1        | 0.4%    |
| WDC WD32 00BEKT-60V5T1 320GB        | 1        | 0.4%    |
| WDC WD30EZRX-00D8PB0 3TB            | 1        | 0.4%    |
| WDC WD3000HLFS-01G6U1 304GB         | 1        | 0.4%    |
| WDC WD3000GLFS-01F8U0 304GB         | 1        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 46       | 79     | 35.38%  |
| Seagate             | 36       | 61     | 27.69%  |
| Samsung Electronics | 21       | 29     | 16.15%  |
| Hitachi             | 11       | 14     | 8.46%   |
| Toshiba             | 8        | 9      | 6.15%   |
| MAXTOR              | 3        | 5      | 2.31%   |
| Unknown             | 1        | 1      | 0.77%   |
| SABRENT             | 1        | 1      | 0.77%   |
| KESU                | 1        | 2      | 0.77%   |
| HPE                 | 1        | 5      | 0.77%   |
| Fujitsu             | 1        | 1      | 0.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 16     | 17.14%  |
| Kingston            | 10       | 12     | 14.29%  |
| SanDisk             | 8        | 11     | 11.43%  |
| Crucial             | 7        | 9      | 10%     |
| A-DATA Technology   | 6        | 6      | 8.57%   |
| WDC                 | 5        | 5      | 7.14%   |
| Intenso             | 3        | 4      | 4.29%   |
| Intel               | 3        | 3      | 4.29%   |
| China               | 3        | 3      | 4.29%   |
| Toshiba             | 2        | 6      | 2.86%   |
| TCSUNBOW            | 2        | 2      | 2.86%   |
| OCZ                 | 2        | 3      | 2.86%   |
| Micron Technology   | 2        | 2      | 2.86%   |
| Unknown             | 1        | 1      | 1.43%   |
| Team                | 1        | 2      | 1.43%   |
| Patriot             | 1        | 1      | 1.43%   |
| Kingmax             | 1        | 1      | 1.43%   |
| Dogfish             | 1        | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 100      | 207    | 58.14%  |
| SSD     | 57       | 88     | 33.14%  |
| NVMe    | 14       | 19     | 8.14%   |
| Unknown | 1        | 1      | 0.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 122      | 280    | 84.72%  |
| NVMe | 14       | 19     | 9.72%   |
| SAS  | 8        | 16     | 5.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 104      | 199    | 60.82%  |
| 0.51-1.0   | 43       | 61     | 25.15%  |
| 1.01-2.0   | 17       | 24     | 9.94%   |
| 3.01-4.0   | 3        | 7      | 1.75%   |
| 2.01-3.0   | 2        | 2      | 1.17%   |
| 4.01-10.0  | 2        | 2      | 1.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 41       | 30.83%  |
| 251-500        | 28       | 21.05%  |
| 1001-2000      | 17       | 12.78%  |
| More than 3000 | 13       | 9.77%   |
| 501-1000       | 11       | 8.27%   |
| 2001-3000      | 8        | 6.02%   |
| 51-100         | 8        | 6.02%   |
| 21-50          | 7        | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 41       | 29.93%  |
| 21-50          | 32       | 23.36%  |
| 51-100         | 18       | 13.14%  |
| 251-500        | 11       | 8.03%   |
| 1001-2000      | 10       | 7.3%    |
| 101-250        | 9        | 6.57%   |
| 501-1000       | 8        | 5.84%   |
| More than 3000 | 4        | 2.92%   |
| 2001-3000      | 4        | 2.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HM500JI 500GB | 1        | 1      | 50%     |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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
| Detected | 116      | 280    | 86.57%  |
| Works    | 16       | 33     | 11.94%  |
| Malfunc  | 2        | 2      | 1.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 89       | 53.29%  |
| AMD                              | 25       | 14.97%  |
| Nvidia                           | 9        | 5.39%   |
| ASMedia Technology               | 9        | 5.39%   |
| JMicron Technology               | 8        | 4.79%   |
| Samsung Electronics              | 6        | 3.59%   |
| Phison Electronics               | 6        | 3.59%   |
| VIA Technologies                 | 4        | 2.4%    |
| Marvell Technology Group         | 4        | 2.4%    |
| Silicon Motion                   | 2        | 1.2%    |
| Silicon Integrated Systems [SiS] | 2        | 1.2%    |
| Silicon Image                    | 1        | 0.6%    |
| Kingston Technology Company      | 1        | 0.6%    |
| Broadcom / LSI                   | 1        | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 7.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 5.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11       | 4.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11       | 4.85%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 3.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.52%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 2.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.2%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 2.2%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 2.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.2%    |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.2%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 4        | 1.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 1.76%   |
| Nvidia MCP61 IDE                                                                        | 4        | 1.76%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.76%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.76%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.76%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 1.76%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3        | 1.32%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.32%   |
| JMicron JMB368 IDE controller                                                           | 3        | 1.32%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.32%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.32%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.32%   |
| Nvidia nForce2 IDE                                                                      | 2        | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 0.88%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.88%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.88%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.88%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 0.88%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.88%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 0.88%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.88%   |
| VIA Serial ATA Controller                                                               | 1        | 0.44%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.44%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.44%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1        | 0.44%   |
| Silicon Integrated Systems [SiS] 182 SATA/RAID Controller                               | 1        | 0.44%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.44%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.44%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.44%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.44%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.44%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.44%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.44%   |
| Marvell Group 88SX7042 PCI-e 4-port SATA-II                                             | 1        | 0.44%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.44%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.44%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.44%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.44%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.44%   |
| Intel Non-Volatile memory controller                                                    | 1        | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 85       | 52.15%  |
| IDE  | 54       | 33.13%  |
| NVMe | 14       | 8.59%   |
| RAID | 7        | 4.29%   |
| SAS  | 2        | 1.23%   |
| SCSI | 1        | 0.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 92       | 71.88%  |
| AMD    | 36       | 28.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-8100 CPU @ 3.60GHz            | 4        | 3.13%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.34%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2.34%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 2.34%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 3        | 2.34%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 3        | 2.34%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 1.56%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 1.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 1.56%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 1.56%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.56%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.56%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.56%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.56%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz       | 2        | 1.56%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.56%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.56%   |
| AMD Sempron Processor 3000+                 | 2        | 1.56%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.56%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.56%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.56%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1        | 0.78%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 0.78%   |
| Intel Xeon CPU E5472 @ 3.00GHz              | 1        | 0.78%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.78%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.78%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.78%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.78%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.78%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.78%   |
| Intel Pentium D CPU 3.20GHz                 | 1        | 0.78%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.78%   |
| Intel Pentium CPU J4205 @ 1.50GHz           | 1        | 0.78%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.78%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.78%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.78%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.78%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.78%   |
| Intel Core i9-10900T CPU @ 1.90GHz          | 1        | 0.78%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1        | 0.78%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1        | 0.78%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.78%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 0.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.78%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 0.78%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 0.78%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 0.78%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 0.78%   |
| Intel Core i5-3450S CPU @ 2.80GHz           | 1        | 0.78%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 0.78%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 0.78%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 0.78%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1        | 0.78%   |
| Intel Core i3-2130 CPU @ 3.40GHz            | 1        | 0.78%   |
| Intel Core i3-2120T CPU @ 2.60GHz           | 1        | 0.78%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 1        | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 15       | 11.72%  |
| Intel Core i5           | 15       | 11.72%  |
| Intel Core 2 Duo        | 13       | 10.16%  |
| Intel Core i3           | 11       | 8.59%   |
| Intel Core 2 Quad       | 9        | 7.03%   |
| Intel Pentium           | 7        | 5.47%   |
| Intel Xeon              | 6        | 4.69%   |
| Intel Celeron           | 5        | 3.91%   |
| AMD Ryzen 7             | 5        | 3.91%   |
| AMD Ryzen 5             | 5        | 3.91%   |
| AMD Sempron             | 4        | 3.13%   |
| AMD FX                  | 4        | 3.13%   |
| AMD Athlon 64 X2        | 4        | 3.13%   |
| Intel Pentium Dual-Core | 3        | 2.34%   |
| AMD Phenom II X4        | 3        | 2.34%   |
| Intel Pentium D         | 2        | 1.56%   |
| Intel Pentium 4         | 2        | 1.56%   |
| Intel Core i9           | 2        | 1.56%   |
| Intel Core 2            | 2        | 1.56%   |
| AMD Ryzen 3             | 2        | 1.56%   |
| AMD Phenom II X6        | 2        | 1.56%   |
| AMD Athlon XP           | 2        | 1.56%   |
| AMD Ryzen 9             | 1        | 0.78%   |
| AMD Ryzen 5 PRO         | 1        | 0.78%   |
| AMD Athlon II X2        | 1        | 0.78%   |
| AMD Athlon              | 1        | 0.78%   |
| AMD A10                 | 1        | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 54       | 42.19%  |
| 2      | 46       | 35.94%  |
| 8      | 8        | 6.25%   |
| 6      | 8        | 6.25%   |
| 1      | 8        | 6.25%   |
| 16     | 1        | 0.78%   |
| 12     | 1        | 0.78%   |
| 10     | 1        | 0.78%   |
| 3      | 1        | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 126      | 98.44%  |
| 2      | 2        | 1.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 80       | 62.5%   |
| 2      | 48       | 37.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 124      | 96.88%  |
| 32-bit         | 4        | 3.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 11.63%  |
| 0x1067a    | 14       | 10.85%  |
| 0x206a7    | 12       | 9.3%    |
| 0x306c3    | 11       | 8.53%   |
| 0x306a9    | 9        | 6.98%   |
| 0x10677    | 5        | 3.88%   |
| 0x906eb    | 4        | 3.1%    |
| 0x6fd      | 4        | 3.1%    |
| 0x08108109 | 4        | 3.1%    |
| 0x6fb      | 3        | 2.33%   |
| 0x106e5    | 3        | 2.33%   |
| 0xf65      | 2        | 1.55%   |
| 0x906ed    | 2        | 1.55%   |
| 0x906ea    | 2        | 1.55%   |
| 0x6f2      | 2        | 1.55%   |
| 0x506e3    | 2        | 1.55%   |
| 0x106a5    | 2        | 1.55%   |
| 0x08701021 | 2        | 1.55%   |
| 0x0800820d | 2        | 1.55%   |
| 0x06000852 | 2        | 1.55%   |
| 0x0600063e | 2        | 1.55%   |
| 0x010000dc | 2        | 1.55%   |
| 0x010000c8 | 2        | 1.55%   |
| 0xf64      | 1        | 0.78%   |
| 0xf29      | 1        | 0.78%   |
| 0xa0655    | 1        | 0.78%   |
| 0x706a8    | 1        | 0.78%   |
| 0x506c9    | 1        | 0.78%   |
| 0x40651    | 1        | 0.78%   |
| 0x306f2    | 1        | 0.78%   |
| 0x206d7    | 1        | 0.78%   |
| 0x20655    | 1        | 0.78%   |
| 0x10676    | 1        | 0.78%   |
| 0x0a201009 | 1        | 0.78%   |
| 0x08701013 | 1        | 0.78%   |
| 0x08101102 | 1        | 0.78%   |
| 0x08101016 | 1        | 0.78%   |
| 0x0800820c | 1        | 0.78%   |
| 0x08001129 | 1        | 0.78%   |
| 0x08001126 | 1        | 0.78%   |
| 0x0700010f | 1        | 0.78%   |
| 0x06001119 | 1        | 0.78%   |
| 0x010000db | 1        | 0.78%   |
| 0x010000c7 | 1        | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 20       | 15.63%  |
| SandyBridge   | 16       | 12.5%   |
| Haswell       | 13       | 10.16%  |
| KabyLake      | 9        | 7.03%   |
| IvyBridge     | 9        | 7.03%   |
| Core          | 9        | 7.03%   |
| Zen+          | 7        | 5.47%   |
| K8 Hammer     | 7        | 5.47%   |
| K10           | 6        | 4.69%   |
| NetBurst      | 5        | 3.91%   |
| Nehalem       | 5        | 3.91%   |
| Zen           | 4        | 3.13%   |
| Zen 2         | 3        | 2.34%   |
| Piledriver    | 3        | 2.34%   |
| Skylake       | 2        | 1.56%   |
| K6            | 2        | 1.56%   |
| Bulldozer     | 2        | 1.56%   |
| Zen 3         | 1        | 0.78%   |
| Westmere      | 1        | 0.78%   |
| Jaguar        | 1        | 0.78%   |
| Goldmont plus | 1        | 0.78%   |
| Goldmont      | 1        | 0.78%   |
| CometLake     | 1        | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 56       | 40.58%  |
| Intel             | 48       | 34.78%  |
| AMD               | 29       | 21.01%  |
| VIA Technologies  | 4        | 2.9%    |
| ASPEED Technology | 1        | 0.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                              | Desktops | Percent |
|------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 13       | 9.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                   | 7        | 4.86%   |
| Nvidia GM206 [GeForce GTX 960]                                                     | 6        | 4.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller        | 6        | 4.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                              | 6        | 4.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                            | 6        | 4.17%   |
| Nvidia GT218 [GeForce 210]                                                         | 4        | 2.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                 | 4        | 2.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                          | 4        | 2.78%   |
| AMD Picasso                                                                        | 4        | 2.78%   |
| Nvidia GK208B [GeForce GT 710]                                                     | 3        | 2.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                   | 3        | 2.08%   |
| Nvidia TU106 [GeForce RTX 2070]                                                    | 2        | 1.39%   |
| Nvidia GP107 [GeForce GTX 1050]                                                    | 2        | 1.39%   |
| Nvidia GP104 [GeForce GTX 1070]                                                    | 2        | 1.39%   |
| Nvidia GK104 [GeForce GTX 760]                                                     | 2        | 1.39%   |
| Nvidia GF104 [GeForce GTX 460]                                                     | 2        | 1.39%   |
| Nvidia G86 [GeForce 8400 GS]                                                       | 2        | 1.39%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                            | 2        | 1.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                           | 2        | 1.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                   | 2        | 1.39%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                         | 1        | 0.69%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                          | 1        | 0.69%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                  | 1        | 0.69%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro]      | 1        | 0.69%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                             | 1        | 0.69%   |
| Nvidia NV43 [GeForce 6600]                                                         | 1        | 0.69%   |
| Nvidia NV36 [GeForce FX 5700VE]                                                    | 1        | 0.69%   |
| Nvidia NV34 [GeForce FX 5200]                                                      | 1        | 0.69%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                              | 1        | 0.69%   |
| Nvidia GT218 [GeForce 310]                                                         | 1        | 0.69%   |
| Nvidia GT200 [GeForce GTX 260]                                                     | 1        | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                | 1        | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                | 1        | 0.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                  | 1        | 0.69%   |
| Nvidia GK208B [GeForce GT 730]                                                     | 1        | 0.69%   |
| Nvidia GK107 [GeForce GTX 650]                                                     | 1        | 0.69%   |
| Nvidia GK104 [GeForce GTX 660 OEM]                                                 | 1        | 0.69%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                  | 1        | 0.69%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                              | 1        | 0.69%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                  | 1        | 0.69%   |
| Nvidia GF108 [GeForce GT 730]                                                      | 1        | 0.69%   |
| Nvidia GF108 [GeForce GT 630]                                                      | 1        | 0.69%   |
| Nvidia GF108 [GeForce GT 420]                                                      | 1        | 0.69%   |
| Nvidia G96GL [Quadro FX 380]                                                       | 1        | 0.69%   |
| Nvidia G96C [GeForce 9500 GT]                                                      | 1        | 0.69%   |
| Nvidia G96C [GeForce 9400 GT]                                                      | 1        | 0.69%   |
| Nvidia G94 [GeForce 9600 GT]                                                       | 1        | 0.69%   |
| Nvidia G92 [GeForce GTS 250]                                                       | 1        | 0.69%   |
| Nvidia G73 [GeForce 7600 GS]                                                       | 1        | 0.69%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                               | 1        | 0.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                         | 1        | 0.69%   |
| Intel HD Graphics 510                                                              | 1        | 0.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 1        | 0.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                | 1        | 0.69%   |
| Intel Core Processor Integrated Graphics Controller                                | 1        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 1        | 0.69%   |
| Intel 82Q35 Express Integrated Graphics Controller                                 | 1        | 0.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                             | 1        | 0.69%   |
| Intel 82945G/GZ Integrated Graphics Controller                                     | 1        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 52       | 40.31%  |
| 1 x Intel      | 39       | 30.23%  |
| 1 x AMD        | 26       | 20.16%  |
| 1 x VIA        | 4        | 3.1%    |
| 2 x AMD        | 3        | 2.33%   |
| Intel + Nvidia | 3        | 2.33%   |
| 2 x Nvidia     | 1        | 0.78%   |
| 1 x ASPEED     | 1        | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 85       | 65.89%  |
| Proprietary | 25       | 19.38%  |
| Unknown     | 19       | 14.73%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 60       | 46.15%  |
| 0.51-1.0   | 20       | 15.38%  |
| 0.01-0.5   | 15       | 11.54%  |
| 1.01-2.0   | 13       | 10%     |
| 3.01-4.0   | 11       | 8.46%   |
| 7.01-8.0   | 9        | 6.92%   |
| 5.01-6.0   | 1        | 0.77%   |
| 2.01-3.0   | 1        | 0.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 24       | 17.27%  |
| Dell                    | 15       | 10.79%  |
| Goldstar                | 14       | 10.07%  |
| Acer                    | 12       | 8.63%   |
| Ancor Communications    | 8        | 5.76%   |
| AOC                     | 7        | 5.04%   |
| Unknown                 | 6        | 4.32%   |
| Philips                 | 6        | 4.32%   |
| Hewlett-Packard         | 5        | 3.6%    |
| BenQ                    | 5        | 3.6%    |
| Sony                    | 3        | 2.16%   |
| Iiyama                  | 3        | 2.16%   |
| NEC Computers           | 2        | 1.44%   |
| LG Electronics          | 2        | 1.44%   |
| Lenovo                  | 2        | 1.44%   |
| Fujitsu Siemens         | 2        | 1.44%   |
| ___                     | 1        | 0.72%   |
| Vestel                  | 1        | 0.72%   |
| Toshiba                 | 1        | 0.72%   |
| Targa Visionary         | 1        | 0.72%   |
| Sceptre Tech            | 1        | 0.72%   |
| OEM                     | 1        | 0.72%   |
| NCS                     | 1        | 0.72%   |
| Microstep               | 1        | 0.72%   |
| Medion                  | 1        | 0.72%   |
| IBM                     | 1        | 0.72%   |
| Hitachi                 | 1        | 0.72%   |
| eMachines               | 1        | 0.72%   |
| ELSA International      | 1        | 0.72%   |
| Elo Touch               | 1        | 0.72%   |
| Eizo                    | 1        | 0.72%   |
| DENON                   | 1        | 0.72%   |
| Compal                  | 1        | 0.72%   |
| Chi Mei Optoelectronics | 1        | 0.72%   |
| Belinea                 | 1        | 0.72%   |
| AUS                     | 1        | 0.72%   |
| ASUSTek Computer        | 1        | 0.72%   |
| AOpen                   | 1        | 0.72%   |
| AGO                     | 1        | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch     | 2        | 1.39%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                       | 2        | 1.39%   |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch                   | 1        | 0.69%   |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                               | 1        | 0.69%   |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                      | 1        | 0.69%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.69%   |
| Unknown LCD Monitor SAMSUNG                                             | 1        | 0.69%   |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                       | 1        | 0.69%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                                | 1        | 0.69%   |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch                  | 1        | 0.69%   |
| Toshiba LCD Monitor TV 1920x1080                                        | 1        | 0.69%   |
| Targa Visionary LCD19-4 TARA194 1280x1024 376x301mm 19.0-inch           | 1        | 0.69%   |
| Sony TV SNY4C03 1920x1080 1063x598mm 48.0-inch                          | 1        | 0.69%   |
| Sony TV SNY1B02 1360x768 1600x900mm 72.3-inch                           | 1        | 0.69%   |
| Sony LCD Monitor TV 3840x1080                                           | 1        | 0.69%   |
| Sceptre Tech E275W-1920 SPT0ABF 1920x1080 443x249mm 20.0-inch           | 1        | 0.69%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch       | 1        | 0.69%   |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch       | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch     | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 459x296mm 21.5-inch    | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM034F 1440x900 428x255mm 19.6-inch     | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM0303 1680x1050 494x320mm 23.2-inch    | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch    | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM006E 1280x1024 338x270mm 17.0-inch    | 1        | 0.69%   |
| Samsung Electronics SMS22A200/460 SAM0831 1920x1080 477x268mm 21.5-inch | 1        | 0.69%   |
| Samsung Electronics SMB2230 SAM063E 1920x1080 477x268mm 21.5-inch       | 1        | 0.69%   |
| Samsung Electronics SA300/350/360 SAM07D6 1920x1080 531x299mm 24.0-inch | 1        | 0.69%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 530x300mm 24.0-inch       | 1        | 0.69%   |
| Samsung Electronics S24F350 SAM0D21 1680x1050 520x290mm 23.4-inch       | 1        | 0.69%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.69%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1        | 0.69%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch       | 1        | 0.69%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1        | 0.69%   |
| Samsung Electronics S22B300 SAM08AC 1680x1050 480x270mm 21.7-inch       | 1        | 0.69%   |
| Samsung Electronics S16B110 SAM097E 1366x768 360x210mm 16.4-inch        | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0F39 1920x1080 1210x680mm 54.6-inch  | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM08FE 1920x1080                       | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SA300/SA350 1920x1080                   | 1        | 0.69%   |
| Samsung Electronics LCD Monitor S22B350 1920x1080                       | 1        | 0.69%   |
| Philips PHL 288E2 PHLC231 3840x2160 620x340mm 27.8-inch                 | 1        | 0.69%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 530x300mm 24.0-inch                 | 1        | 0.69%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                 | 1        | 0.69%   |
| Philips LCD Monitor PHL 498P9 1920x1080                                 | 1        | 0.69%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                     | 1        | 0.69%   |
| Philips 170B PHL081D 1280x1024 338x270mm 17.0-inch                      | 1        | 0.69%   |
| OEM LCD Monitor 46W_LCD_TV 1920x1080                                    | 1        | 0.69%   |
| NEC Computers LCD73V NEC66C2 1280x1024 338x270mm 17.0-inch              | 1        | 0.69%   |
| NEC Computers LCD1810X NEC6594 1280x1024 359x287mm 18.1-inch            | 1        | 0.69%   |
| NCS LCD Monitor NCS2275 1920x1080 300x230mm 14.9-inch                   | 1        | 0.69%   |
| Microstep LCD Monitor MSI PS341WU 7680x2160                             | 1        | 0.69%   |
| Medion MD 20144 MED3636 1920x1080 510x287mm 23.0-inch                   | 1        | 0.69%   |
| LG Electronics LCD Monitor LG TV 1360x768                               | 1        | 0.69%   |
| LG Electronics LCD Monitor 27EA53 1920x1080                             | 1        | 0.69%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                    | 1        | 0.69%   |
| Lenovo D22-20 LEN66AD 1920x1080 477x268mm 21.5-inch                     | 1        | 0.69%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                   | 1        | 0.69%   |
| Iiyama PLE2403WS IVM5604 1920x1200 519x324mm 24.1-inch                  | 1        | 0.69%   |
| Iiyama PL2294H IVM563B 1920x1080 476x268mm 21.5-inch                    | 1        | 0.69%   |
| Iiyama PL2278H IVM5624 1920x1080 477x268mm 21.5-inch                    | 1        | 0.69%   |
| IBM E74 IBM18BC 1280x1024 306x230mm 15.1-inch                           | 1        | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 60       | 44.78%  |
| 1280x1024 (SXGA)   | 24       | 17.91%  |
| 1440x900 (WXGA+)   | 9        | 6.72%   |
| 1680x1050 (WSXGA+) | 8        | 5.97%   |
| 1920x1200 (WUXGA)  | 5        | 3.73%   |
| 3840x2160 (4K)     | 4        | 2.99%   |
| 1360x768           | 4        | 2.99%   |
| 1024x768 (XGA)     | 4        | 2.99%   |
| 1600x900 (HD+)     | 3        | 2.24%   |
| 1366x768 (WXGA)    | 3        | 2.24%   |
| Unknown            | 3        | 2.24%   |
| 3440x1440          | 2        | 1.49%   |
| 7680x2160          | 1        | 0.75%   |
| 4240x1440          | 1        | 0.75%   |
| 3840x1080          | 1        | 0.75%   |
| 2560x1440 (QHD)    | 1        | 0.75%   |
| 1600x1200          | 1        | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 15.44%  |
| 21      | 15       | 11.03%  |
| 24      | 14       | 10.29%  |
| 19      | 14       | 10.29%  |
| 17      | 13       | 9.56%   |
| 23      | 12       | 8.82%   |
| 27      | 10       | 7.35%   |
| 18      | 9        | 6.62%   |
| 22      | 6        | 4.41%   |
| 15      | 6        | 4.41%   |
| 31      | 3        | 2.21%   |
| 20      | 3        | 2.21%   |
| 72      | 1        | 0.74%   |
| 54      | 1        | 0.74%   |
| 52      | 1        | 0.74%   |
| 48      | 1        | 0.74%   |
| 33      | 1        | 0.74%   |
| 32      | 1        | 0.74%   |
| 26      | 1        | 0.74%   |
| 16      | 1        | 0.74%   |
| 14      | 1        | 0.74%   |
| 12      | 1        | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 39       | 29.32%  |
| 501-600     | 32       | 24.06%  |
| Unknown     | 21       | 15.79%  |
| 301-350     | 18       | 13.53%  |
| 351-400     | 11       | 8.27%   |
| 601-700     | 4        | 3.01%   |
| 1001-1500   | 3        | 2.26%   |
| 701-800     | 2        | 1.5%    |
| 201-300     | 2        | 1.5%    |
| 1501-2000   | 1        | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 60       | 45.45%  |
| 5/4     | 21       | 15.91%  |
| 16/10   | 21       | 15.91%  |
| Unknown | 20       | 15.15%  |
| 4/3     | 8        | 6.06%   |
| 3/2     | 1        | 0.76%   |
| 21/9    | 1        | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 36       | 26.67%  |
| 151-200        | 26       | 19.26%  |
| Unknown        | 21       | 15.56%  |
| 141-150        | 17       | 12.59%  |
| 301-350        | 11       | 8.15%   |
| 101-110        | 7        | 5.19%   |
| 251-300        | 6        | 4.44%   |
| 351-500        | 5        | 3.7%    |
| More than 1000 | 3        | 2.22%   |
| 71-80          | 1        | 0.74%   |
| 111-120        | 1        | 0.74%   |
| 501-1000       | 1        | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 82       | 64.06%  |
| Unknown | 21       | 16.41%  |
| 101-120 | 17       | 13.28%  |
| 1-50    | 4        | 3.13%   |
| 121-160 | 3        | 2.34%   |
| 161-240 | 1        | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 105      | 80.77%  |
| 2     | 19       | 14.62%  |
| 0     | 5        | 3.85%   |
| 3     | 1        | 0.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 76       | 42.7%   |
| Intel                            | 36       | 20.22%  |
| Qualcomm Atheros                 | 18       | 10.11%  |
| Ralink Technology                | 8        | 4.49%   |
| Nvidia                           | 8        | 4.49%   |
| Broadcom                         | 6        | 3.37%   |
| VIA Technologies                 | 3        | 1.69%   |
| TP-Link                          | 3        | 1.69%   |
| Marvell Technology Group         | 3        | 1.69%   |
| Broadcom Limited                 | 2        | 1.12%   |
| AVM                              | 2        | 1.12%   |
| Sitecom Europe                   | 1        | 0.56%   |
| Silicon Integrated Systems [SiS] | 1        | 0.56%   |
| Realtek                          | 1        | 0.56%   |
| Ralink                           | 1        | 0.56%   |
| Microsoft                        | 1        | 0.56%   |
| Mellanox Technologies            | 1        | 0.56%   |
| LSI                              | 1        | 0.56%   |
| JMicron Technology               | 1        | 0.56%   |
| Huawei Technologies              | 1        | 0.56%   |
| Edimax Technology                | 1        | 0.56%   |
| Belkin Components                | 1        | 0.56%   |
| ASUSTek Computer                 | 1        | 0.56%   |
| ADMtek                           | 1        | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 59       | 29.65%  |
| Nvidia MCP61 Ethernet                                                                         | 6        | 3.02%   |
| Intel I211 Gigabit Network Connection                                                         | 6        | 3.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 5        | 2.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 5        | 2.51%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4        | 2.01%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 3        | 1.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 1.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 1.51%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                                    | 3        | 1.51%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                                 | 3        | 1.51%   |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 1.51%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 2        | 1.01%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 1.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2        | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 1.01%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2        | 1.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 2        | 1.01%   |
| Nvidia nForce2 Ethernet Controller                                                            | 2        | 1.01%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 2        | 1.01%   |
| Intel Ethernet Connection I217-V                                                              | 2        | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                                          | 2        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2        | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 1.01%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 1.01%   |
| Intel 82574L Gigabit Network Connection                                                       | 2        | 1.01%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 2        | 1.01%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2        | 1.01%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.5%    |
| TP-Link 802.11n NIC                                                                           | 1        | 0.5%    |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 0.5%    |
| Sitecom Europe RTL8188S WLAN Adapter                                                          | 1        | 0.5%    |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                                     | 1        | 0.5%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.5%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                                             | 1        | 0.5%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 0.5%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.5%    |
| Realtek 802.11n NIC                                                                           | 1        | 0.5%    |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 0.5%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 0.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 0.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 0.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1        | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 0.5%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                | 1        | 0.5%    |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 0.5%    |
| Mellanox MT23108 InfiniHost                                                                   | 1        | 0.5%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                                       | 1        | 0.5%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                             | 1        | 0.5%    |
| LSI 56k WinModem                                                                              | 1        | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                                        | 1        | 0.5%    |
| Intel Wireless 8265 / 8275                                                                    | 1        | 0.5%    |
| Intel Wireless 7265                                                                           | 1        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 25%     |
| Intel                 | 10       | 17.86%  |
| Ralink Technology     | 8        | 14.29%  |
| Qualcomm Atheros      | 8        | 14.29%  |
| TP-Link               | 3        | 5.36%   |
| Broadcom              | 3        | 5.36%   |
| AVM                   | 2        | 3.57%   |
| Sitecom Europe        | 1        | 1.79%   |
| Realtek               | 1        | 1.79%   |
| Ralink                | 1        | 1.79%   |
| Microsoft             | 1        | 1.79%   |
| Edimax Technology     | 1        | 1.79%   |
| Broadcom Limited      | 1        | 1.79%   |
| Belkin Components     | 1        | 1.79%   |
| ASUSTek Computer      | 1        | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                               | 4        | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 5.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 5.36%   |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 5.36%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 2        | 3.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 3.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 3.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 3.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 1.79%   |
| TP-Link 802.11n NIC                                                                           | 1        | 1.79%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 1.79%   |
| Sitecom Europe RTL8188S WLAN Adapter                                                          | 1        | 1.79%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.79%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 1.79%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 1.79%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.79%   |
| Realtek 802.11n NIC                                                                           | 1        | 1.79%   |
| Ralink RT5370 Wireless Adapter                                                                | 1        | 1.79%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 1.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.79%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1        | 1.79%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 1.79%   |
| Intel Wireless 8265 / 8275                                                                    | 1        | 1.79%   |
| Intel Wireless 7265                                                                           | 1        | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1        | 1.79%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 1.79%   |
| Intel Centrino Wireless-N 105                                                                 | 1        | 1.79%   |
| Edimax AC600 USB                                                                              | 1        | 1.79%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 1.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1        | 1.79%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1        | 1.79%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller                           | 1        | 1.79%   |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU]                   | 1        | 1.79%   |
| AVM Fritz!WLAN N [Atheros AR9001U]                                                            | 1        | 1.79%   |
| AVM FRITZ!WLAN AC 860                                                                         | 1        | 1.79%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                           | 1        | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 72       | 52.94%  |
| Intel                            | 32       | 23.53%  |
| Qualcomm Atheros                 | 10       | 7.35%   |
| Nvidia                           | 8        | 5.88%   |
| VIA Technologies                 | 3        | 2.21%   |
| Marvell Technology Group         | 3        | 2.21%   |
| Broadcom                         | 3        | 2.21%   |
| Silicon Integrated Systems [SiS] | 1        | 0.74%   |
| JMicron Technology               | 1        | 0.74%   |
| Huawei Technologies              | 1        | 0.74%   |
| Broadcom Limited                 | 1        | 0.74%   |
| ADMtek                           | 1        | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59       | 41.84%  |
| Nvidia MCP61 Ethernet                                             | 6        | 4.26%   |
| Intel I211 Gigabit Network Connection                             | 6        | 4.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 3.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.84%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3        | 2.13%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 2.13%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 2.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.42%   |
| Nvidia nForce2 Ethernet Controller                                | 2        | 1.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.42%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.42%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.42%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.42%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.42%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.42%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.42%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.71%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.71%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.71%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.71%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1        | 0.71%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.71%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.71%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.71%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.71%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.71%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.71%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.71%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.71%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.71%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 0.71%   |
| Intel 82544EI Gigabit Ethernet Controller (Copper)                | 1        | 0.71%   |
| Huawei BLA-L29                                                    | 1        | 0.71%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.71%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 0.71%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.71%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 0.71%   |
| ADMtek ADM8515 Pegasus II Ethernet                                | 1        | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 128      | 71.11%  |
| WiFi     | 50       | 27.78%  |
| Modem    | 1        | 0.56%   |
| Unknown  | 1        | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 125      | 76.22%  |
| WiFi     | 39       | 23.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 85       | 66.41%  |
| 2     | 39       | 30.47%  |
| 3     | 3        | 2.34%   |
| 4     | 1        | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 111      | 83.46%  |
| Yes  | 22       | 16.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 33.33%  |
| Cambridge Silicon Radio         | 8        | 29.63%  |
| Realtek Semiconductor           | 3        | 11.11%  |
| Qualcomm Atheros Communications | 2        | 7.41%   |
| Broadcom                        | 2        | 7.41%   |
| ASUSTek Computer                | 2        | 7.41%   |
| Apple                           | 1        | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 29.63%  |
| Intel AX200 Bluetooth                               | 3        | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 7.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 7.41%   |
| Intel Bluetooth Device                              | 2        | 7.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 7.41%   |
| Realtek Bluetooth Radio                             | 1        | 3.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 3.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 3.7%    |
| Intel Bluetooth wireless interface                  | 1        | 3.7%    |
| Intel AX201 Bluetooth                               | 1        | 3.7%    |
| Broadcom HP Bluethunder                             | 1        | 3.7%    |
| Broadcom BCM2045 Bluetooth                          | 1        | 3.7%    |
| Apple Bluetooth USB Host Controller                 | 1        | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 80       | 40.82%  |
| Nvidia                           | 49       | 25%     |
| AMD                              | 34       | 17.35%  |
| C-Media Electronics              | 9        | 4.59%   |
| VIA Technologies                 | 6        | 3.06%   |
| Creative Labs                    | 4        | 2.04%   |
| Silicon Integrated Systems [SiS] | 2        | 1.02%   |
| Logitech                         | 2        | 1.02%   |
| GN Netcom                        | 2        | 1.02%   |
| Xilinx                           | 1        | 0.51%   |
| M-Audio                          | 1        | 0.51%   |
| JMTek                            | 1        | 0.51%   |
| GYROCOM C&C                      | 1        | 0.51%   |
| Generalplus Technology           | 1        | 0.51%   |
| Focusrite-Novation               | 1        | 0.51%   |
| Evolution Electronics            | 1        | 0.51%   |
| Creative Technology              | 1        | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 17       | 7.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 11       | 5.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 8        | 3.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 8        | 3.65%   |
| Nvidia MCP61 High Definition Audio                                          | 6        | 2.74%   |
| Nvidia High Definition Audio Controller                                     | 6        | 2.74%   |
| Nvidia GP107GL High Definition Audio Controller                             | 6        | 2.74%   |
| Nvidia GM206 High Definition Audio Controller                               | 6        | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 6        | 2.74%   |
| Intel Cannon Lake PCH cAVS                                                  | 6        | 2.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 6        | 2.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 6        | 2.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 6        | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 6        | 2.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 6        | 2.74%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                               | 5        | 2.28%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                         | 5        | 2.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 4        | 1.83%   |
| AMD Starship/Matisse HD Audio Controller                                    | 4        | 1.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 4        | 1.83%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                   | 3        | 1.37%   |
| Nvidia TU106 High Definition Audio Controller                               | 3        | 1.37%   |
| Nvidia GK104 HDMI Audio Controller                                          | 3        | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                               | 3        | 1.37%   |
| Intel 9 Series Chipset Family HD Audio Controller                           | 3        | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 3        | 1.37%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 3        | 1.37%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller             | 2        | 0.91%   |
| Nvidia nForce2 AC97 Audio Controler (MCP)                                   | 2        | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                               | 2        | 0.91%   |
| Nvidia GP104 High Definition Audio Controller                               | 2        | 0.91%   |
| Nvidia GF116 High Definition Audio Controller                               | 2        | 0.91%   |
| Nvidia GF104 High Definition Audio Controller                               | 2        | 0.91%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 2        | 0.91%   |
| Intel 200 Series PCH HD Audio                                               | 2        | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 2        | 0.91%   |
| AMD FCH Azalia Controller                                                   | 2        | 0.91%   |
| Xilinx RME Hammerfall DSP                                                   | 1        | 0.46%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller              | 1        | 0.46%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.46%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller          | 1        | 0.46%   |
| Nvidia MCP51 High Definition Audio                                          | 1        | 0.46%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 1        | 0.46%   |
| Nvidia GK107 HDMI Audio Controller                                          | 1        | 0.46%   |
| Nvidia GF114 HDMI Audio Controller                                          | 1        | 0.46%   |
| M-Audio M-Audio Fast Track                                                  | 1        | 0.46%   |
| Logitech QuickCam Fusion                                                    | 1        | 0.46%   |
| Logitech G430 Surround Sound Gaming Headset                                 | 1        | 0.46%   |
| JMTek USB PnP Audio Device                                                  | 1        | 0.46%   |
| Intel Haswell-ULT HD Audio Controller                                       | 1        | 0.46%   |
| Intel Comet Lake PCH cAVS                                                   | 1        | 0.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                | 1        | 0.46%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster           | 1        | 0.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                      | 1        | 0.46%   |
| Intel C610/X99 series chipset HD Audio Controller                           | 1        | 0.46%   |
| Intel C600/X79 series chipset High Definition Audio Controller              | 1        | 0.46%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller           | 1        | 0.46%   |
| Intel 8 Series HD Audio Controller                                          | 1        | 0.46%   |
| GYROCOM C&C Fiio E10                                                        | 1        | 0.46%   |
| GN Netcom Jabra UC Voice 750 MS                                             | 1        | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 8        | 42.11%  |
| Crucial             | 3        | 15.79%  |
| Samsung Electronics | 2        | 10.53%  |
| Kingston            | 2        | 10.53%  |
| SK Hynix            | 1        | 5.26%   |
| Micron Technology   | 1        | 5.26%   |
| G.Skill             | 1        | 5.26%   |
| Exceleram           | 1        | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 667MT/s                    | 1        | 4.76%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 1        | 4.76%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 4.76%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 4.76%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 4.76%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 1        | 4.76%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s              | 1        | 4.76%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                   | 1        | 4.76%   |
| Unknown RAM Module 1024MB DIMM                           | 1        | 4.76%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 4.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 4.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 4.76%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s      | 1        | 4.76%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 4.76%   |
| Kingston RAM KP223C-ELD 2048MB DIMM DDR3 1333MT/s        | 1        | 4.76%   |
| Kingston RAM KHX3600C17D4/16GX 16GB DIMM DDR4 3800MT/s   | 1        | 4.76%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s   | 1        | 4.76%   |
| Exceleram RAM E30144A 4096MB DIMM DDR3 800MT/s           | 1        | 4.76%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s  | 1        | 4.76%   |
| Crucial RAM BLT8G4D26BFT4K.C8FD 8GB DIMM DDR4 2666MT/s   | 1        | 4.76%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 1        | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 7        | 36.84%  |
| DDR4    | 5        | 26.32%  |
| DDR2    | 4        | 21.05%  |
| Unknown | 2        | 10.53%  |
| DDR     | 1        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 17       | 89.47%  |
| SODIMM | 2        | 10.53%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 6        | 30%     |
| 8192  | 5        | 25%     |
| 4096  | 4        | 20%     |
| 16384 | 2        | 10%     |
| 1024  | 2        | 10%     |
| 512   | 1        | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 26.32%  |
| 800     | 3        | 15.79%  |
| 1333    | 2        | 10.53%  |
| 667     | 2        | 10.53%  |
| 3800    | 1        | 5.26%   |
| 3500    | 1        | 5.26%   |
| 3200    | 1        | 5.26%   |
| 2666    | 1        | 5.26%   |
| 2400    | 1        | 5.26%   |
| 400     | 1        | 5.26%   |
| Unknown | 1        | 5.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 5        | 45.45%  |
| Samsung Electronics | 2        | 18.18%  |
| Brother Industries  | 2        | 18.18%  |
| Ricoh               | 1        | 9.09%   |
| Canon               | 1        | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Samsung SCX-3400 Series  | 1        | 9.09%   |
| Samsung ML-1670 Series   | 1        | 9.09%   |
| Ricoh SP C260SFNw        | 1        | 9.09%   |
| HP LaserJet P1006        | 1        | 9.09%   |
| HP LaserJet 3050         | 1        | 9.09%   |
| HP DeskJet F4200 series  | 1        | 9.09%   |
| HP Deskjet 2540 series   | 1        | 9.09%   |
| HP Deskjet 1050 J410     | 1        | 9.09%   |
| Canon iP4200             | 1        | 9.09%   |
| Brother MFC-L2685DW      | 1        | 9.09%   |
| Brother HL-L2300D series | 1        | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 1        | 50%     |
| Hewlett-Packard | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 50%     |
| HP ScanJet 3800c                              | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 5        | 31.25%  |
| Microsoft                     | 3        | 18.75%  |
| Xiongmai                      | 1        | 6.25%   |
| Sunplus Innovation Technology | 1        | 6.25%   |
| Service & Quality Technology  | 1        | 6.25%   |
| Nintendo                      | 1        | 6.25%   |
| Microdia                      | 1        | 6.25%   |
| KYE Systems (Mouse Systems)   | 1        | 6.25%   |
| Generalplus Technology        | 1        | 6.25%   |
| Chicony Electronics           | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                          | 2        | 12.5%   |
| Logitech Webcam C270                               | 2        | 12.5%   |
| Xiongmai web camera                                | 1        | 6.25%   |
| Sunplus Full HD webcam                             | 1        | 6.25%   |
| Service & Quality USB PC Camera                    | 1        | 6.25%   |
| Nintendo USB Camera                                | 1        | 6.25%   |
| Microsoft Microsoft?� LifeCam VX-5500              | 1        | 6.25%   |
| Microdia Webcam Vitade AF                          | 1        | 6.25%   |
| Logitech Webcam Pro 9000                           | 1        | 6.25%   |
| Logitech Webcam C310                               | 1        | 6.25%   |
| Logitech HD Pro Webcam C920                        | 1        | 6.25%   |
| KYE Systems (Mouse Systems) Genius iSlim 2000AF V2 | 1        | 6.25%   |
| Generalplus 808 Camera                             | 1        | 6.25%   |
| Chicony HP High Definition 1MP Webcam              | 1        | 6.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| VASCO Data Security International | 1        | 33.33%  |
| OmniKey                           | 1        | 33.33%  |
| Jing-Mold Enterprise              | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| VASCO Data Security International DIGIPASS 870                    | 1        | 33.33%  |
| OmniKey CardMan 1021                                              | 1        | 33.33%  |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 91       | 70.54%  |
| 1     | 32       | 24.81%  |
| 2     | 3        | 2.33%   |
| 4     | 2        | 1.55%   |
| 3     | 1        | 0.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 22       | 50%     |
| Net/wireless             | 11       | 25%     |
| Communication controller | 3        | 6.82%   |
| Net/ethernet             | 2        | 4.55%   |
| Unassigned class         | 1        | 2.27%   |
| Storage/ide              | 1        | 2.27%   |
| Network                  | 1        | 2.27%   |
| Modem                    | 1        | 2.27%   |
| Fingerprint reader       | 1        | 2.27%   |
| Chipcard                 | 1        | 2.27%   |

