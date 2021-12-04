LMDE 4 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for LMDE 4.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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
| Acer          | RS880M05                    | [2ce9c25975](https://linux-hardware.org/?probe=2ce9c25975) | Nov 25, 2021 |
| NEC Comput... | GA-8I945PM                  | [3d3711b8cc](https://linux-hardware.org/?probe=3d3711b8cc) | Nov 22, 2021 |
| ASUSTek       | A68HM-K                     | [b4b709eb1b](https://linux-hardware.org/?probe=b4b709eb1b) | Nov 18, 2021 |
| ASUSTek       | A68HM-K                     | [18236d5a16](https://linux-hardware.org/?probe=18236d5a16) | Nov 18, 2021 |
| Intel         | H61                         | [51f383b050](https://linux-hardware.org/?probe=51f383b050) | Nov 04, 2021 |
| Intel         | H61                         | [c3f5ace673](https://linux-hardware.org/?probe=c3f5ace673) | Nov 02, 2021 |
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
| 4.19.0-16-amd64     | 24       | 16.44%  |
| 4.19.0-17-amd64     | 19       | 13.01%  |
| 4.19.0-14-amd64     | 18       | 12.33%  |
| 4.19.0-13-amd64     | 17       | 11.64%  |
| 4.19.0-8-amd64      | 14       | 9.59%   |
| 4.19.0-12-amd64     | 9        | 6.16%   |
| 4.19.0-10-amd64     | 8        | 5.48%   |
| 4.19.0-9-amd64      | 7        | 4.79%   |
| 4.19.0-18-amd64     | 7        | 4.79%   |
| 4.19.0-11-amd64     | 4        | 2.74%   |
| 4.19.0-17-686       | 3        | 2.05%   |
| 4.19.0-16-686       | 3        | 2.05%   |
| 4.19.0-14-686       | 3        | 2.05%   |
| 4.19.0-8-686        | 2        | 1.37%   |
| 4.19.0-13-686       | 2        | 1.37%   |
| 5.8.0-3-amd64       | 1        | 0.68%   |
| 5.6.0-0.bpo.2-amd64 | 1        | 0.68%   |
| 5.4.0-0.bpo.4-amd64 | 1        | 0.68%   |
| 5.10.0-7-amd64      | 1        | 0.68%   |
| 4.19.0-9-686        | 1        | 0.68%   |
| 4.19.0-12-686       | 1        | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 126      | 96.92%  |
| 5.8.0   | 1        | 0.77%   |
| 5.6.0   | 1        | 0.77%   |
| 5.4.0   | 1        | 0.77%   |
| 5.10.0  | 1        | 0.77%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 126      | 96.92%  |
| 5.8     | 1        | 0.77%   |
| 5.6     | 1        | 0.77%   |
| 5.4     | 1        | 0.77%   |
| 5.10    | 1        | 0.77%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 115      | 88.46%  |
| i686   | 15       | 11.54%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 116      | 88.55%  |
| Cinnamon   | 6        | 4.58%   |
| Unknown    | 3        | 2.29%   |
| MATE       | 2        | 1.53%   |
| XFCE       | 1        | 0.76%   |
| LXQt       | 1        | 0.76%   |
| LXDE       | 1        | 0.76%   |
| GNOME      | 1        | 0.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 130      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 118      | 90.77%  |
| TDM     | 8        | 6.15%   |
| LightDM | 3        | 2.31%   |
| GDM     | 1        | 0.77%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Desktops | Percent |
|--------|----------|---------|
| en_US  | 33       | 25.38%  |
| pt_BR  | 14       | 10.77%  |
| de_DE  | 14       | 10.77%  |
| fr_FR  | 12       | 9.23%   |
| pl_PL  | 6        | 4.62%   |
| ru_RU  | 5        | 3.85%   |
| en_GB  | 5        | 3.85%   |
| sv_SE  | 3        | 2.31%   |
| nl_BE  | 3        | 2.31%   |
| es_AR  | 3        | 2.31%   |
| en_AU  | 3        | 2.31%   |
| pt_PT  | 2        | 1.54%   |
| it_IT  | 2        | 1.54%   |
| hu_HU  | 2        | 1.54%   |
| es_ES  | 2        | 1.54%   |
| en_CA  | 2        | 1.54%   |
| unm_US | 1        | 0.77%   |
| uk_UA  | 1        | 0.77%   |
| tr_TR  | 1        | 0.77%   |
| sk_SK  | 1        | 0.77%   |
| nb_NO  | 1        | 0.77%   |
| fr_CA  | 1        | 0.77%   |
| fi_FI  | 1        | 0.77%   |
| et_EE  | 1        | 0.77%   |
| es_UY  | 1        | 0.77%   |
| es_MX  | 1        | 0.77%   |
| es_CO  | 1        | 0.77%   |
| es_CL  | 1        | 0.77%   |
| en_ZA  | 1        | 0.77%   |
| el_GR  | 1        | 0.77%   |
| de_AT  | 1        | 0.77%   |
| cs_CZ  | 1        | 0.77%   |
| ca_ES  | 1        | 0.77%   |
| bg_BG  | 1        | 0.77%   |
| ar_EG  | 1        | 0.77%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 91       | 70%     |
| EFI  | 39       | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 124      | 94.66%  |
| Btrfs   | 4        | 3.05%   |
| Unknown | 2        | 1.53%   |
| Ext3    | 1        | 0.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 117      | 88.64%  |
| GPT     | 10       | 7.58%   |
| MBR     | 5        | 3.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 95.45%  |
| Yes       | 6        | 4.55%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 95.38%  |
| Yes       | 6        | 4.62%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 30       | 23.08%  |
| Gigabyte Technology | 18       | 13.85%  |
| MSI                 | 16       | 12.31%  |
| Dell                | 13       | 10%     |
| ASRock              | 10       | 7.69%   |
| Hewlett-Packard     | 8        | 6.15%   |
| Unknown             | 7        | 5.38%   |
| Intel               | 5        | 3.85%   |
| Acer                | 4        | 3.08%   |
| ECS                 | 3        | 2.31%   |
| Pegatron            | 2        | 1.54%   |
| EVGA                | 2        | 1.54%   |
| Biostar             | 2        | 1.54%   |
| Semp Toshiba        | 1        | 0.77%   |
| Positivo            | 1        | 0.77%   |
| PCWare              | 1        | 0.77%   |
| OEM                 | 1        | 0.77%   |
| NEC Computers       | 1        | 0.77%   |
| Lenovo              | 1        | 0.77%   |
| Fujitsu Siemens     | 1        | 0.77%   |
| Foxconn             | 1        | 0.77%   |
| DFI                 | 1        | 0.77%   |
| Alienware           | 1        | 0.77%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 7        | 5.38%   |
| Dell OptiPlex 780                  | 2        | 1.54%   |
| ASUS All Series                    | 2        | 1.54%   |
| Semp Toshiba STI                   | 1        | 0.77%   |
| Positivo POS-EIH61CE               | 1        | 0.77%   |
| Pegatron Elite 7300 Series MT      | 1        | 0.77%   |
| Pegatron 520-1188la                | 1        | 0.77%   |
| PCWare IPMH81G1                    | 1        | 0.77%   |
| OEM 45CMX/45GMX/45CMX-K            | 1        | 0.77%   |
| NEC Computers IMEDIA S9509         | 1        | 0.77%   |
| MSI PX714AA-ABH t3040.nl           | 1        | 0.77%   |
| MSI MS-7C52                        | 1        | 0.77%   |
| MSI MS-7C51                        | 1        | 0.77%   |
| MSI MS-7A40                        | 1        | 0.77%   |
| MSI MS-7918                        | 1        | 0.77%   |
| MSI MS-7823                        | 1        | 0.77%   |
| MSI MS-7817                        | 1        | 0.77%   |
| MSI MS-7815                        | 1        | 0.77%   |
| MSI MS-7751                        | 1        | 0.77%   |
| MSI MS-7383                        | 1        | 0.77%   |
| MSI MS-7267                        | 1        | 0.77%   |
| MSI MS-7142                        | 1        | 0.77%   |
| MSI MS-6785                        | 1        | 0.77%   |
| MSI MS-6570                        | 1        | 0.77%   |
| MSI ESPRIMO P2440                  | 1        | 0.77%   |
| MSI *MF                            | 1        | 0.77%   |
| Lenovo ThinkCentre M93p 10AB0010US | 1        | 0.77%   |
| Intel H61                          | 1        | 0.77%   |
| Intel DP55WB AAE64798-206          | 1        | 0.77%   |
| Intel DG33FB AAD81072-309          | 1        | 0.77%   |
| Intel DG31PR AAD97573-302          | 1        | 0.77%   |
| Intel BTC-T37                      | 1        | 0.77%   |
| HP xw8600 Workstation              | 1        | 0.77%   |
| HP Pavilion Desktop 590-p0xxx      | 1        | 0.77%   |
| HP Desktop 190-0xxx                | 1        | 0.77%   |
| HP Compaq Elite 8300 CMT           | 1        | 0.77%   |
| HP Compaq dc7800 Small Form Factor | 1        | 0.77%   |
| HP Compaq 8200 Elite USDT PC       | 1        | 0.77%   |
| HP Compaq 8100 Elite SFF PC        | 1        | 0.77%   |
| HP 290 G2 MT Business PC           | 1        | 0.77%   |
| Gigabyte Z97-D3H                   | 1        | 0.77%   |
| Gigabyte Z77-D3H                   | 1        | 0.77%   |
| Gigabyte Z390 M GAMING             | 1        | 0.77%   |
| Gigabyte Z390 DESIGNARE            | 1        | 0.77%   |
| Gigabyte Z370 AORUS Gaming 7       | 1        | 0.77%   |
| Gigabyte X570 AORUS ULTRA          | 1        | 0.77%   |
| Gigabyte X570 AORUS PRO            | 1        | 0.77%   |
| Gigabyte M68MT-S2P                 | 1        | 0.77%   |
| Gigabyte M52LT-D3P                 | 1        | 0.77%   |
| Gigabyte H81M-S2PV                 | 1        | 0.77%   |
| Gigabyte H61M-S1                   | 1        | 0.77%   |
| Gigabyte H61M-DS2 DVI              | 1        | 0.77%   |
| Gigabyte GA-880GM-UD2H             | 1        | 0.77%   |
| Gigabyte GA-78LMT-USB3 6.0         | 1        | 0.77%   |
| Gigabyte EP45C-DS3R                | 1        | 0.77%   |
| Gigabyte COMFOR OFFICE I33         | 1        | 0.77%   |
| Gigabyte B450M DS3H                | 1        | 0.77%   |
| Gigabyte 945GM-S2                  | 1        | 0.77%   |
| Fujitsu Siemens D2264-A1           | 1        | 0.77%   |
| Foxconn 945 7MC Series             | 1        | 0.77%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 8        | 6.15%   |
| Unknown                | 7        | 5.38%   |
| HP Compaq              | 4        | 3.08%   |
| ASUS PRIME             | 4        | 3.08%   |
| Dell Inspiron          | 3        | 2.31%   |
| Gigabyte Z390          | 2        | 1.54%   |
| Gigabyte X570          | 2        | 1.54%   |
| Dell Precision         | 2        | 1.54%   |
| ASUS ROG               | 2        | 1.54%   |
| ASUS P5KPL-AM          | 2        | 1.54%   |
| ASUS All               | 2        | 1.54%   |
| Acer Veriton           | 2        | 1.54%   |
| Acer Aspire            | 2        | 1.54%   |
| Semp Toshiba STI       | 1        | 0.77%   |
| Positivo POS-EIH61CE   | 1        | 0.77%   |
| Pegatron Elite         | 1        | 0.77%   |
| Pegatron 520-1188la    | 1        | 0.77%   |
| PCWare IPMH81G1        | 1        | 0.77%   |
| OEM 45CMX              | 1        | 0.77%   |
| NEC Computers IMEDIA   | 1        | 0.77%   |
| MSI PX714AA-ABH        | 1        | 0.77%   |
| MSI MS-7C52            | 1        | 0.77%   |
| MSI MS-7C51            | 1        | 0.77%   |
| MSI MS-7A40            | 1        | 0.77%   |
| MSI MS-7918            | 1        | 0.77%   |
| MSI MS-7823            | 1        | 0.77%   |
| MSI MS-7817            | 1        | 0.77%   |
| MSI MS-7815            | 1        | 0.77%   |
| MSI MS-7751            | 1        | 0.77%   |
| MSI MS-7383            | 1        | 0.77%   |
| MSI MS-7267            | 1        | 0.77%   |
| MSI MS-7142            | 1        | 0.77%   |
| MSI MS-6785            | 1        | 0.77%   |
| MSI MS-6570            | 1        | 0.77%   |
| MSI ESPRIMO            | 1        | 0.77%   |
| MSI *MF                | 1        | 0.77%   |
| Lenovo ThinkCentre     | 1        | 0.77%   |
| Intel H61              | 1        | 0.77%   |
| Intel DP55WB           | 1        | 0.77%   |
| Intel DG33FB           | 1        | 0.77%   |
| Intel DG31PR           | 1        | 0.77%   |
| Intel BTC-T37          | 1        | 0.77%   |
| HP xw8600              | 1        | 0.77%   |
| HP Pavilion            | 1        | 0.77%   |
| HP Desktop             | 1        | 0.77%   |
| HP 290                 | 1        | 0.77%   |
| Gigabyte Z97-D3H       | 1        | 0.77%   |
| Gigabyte Z77-D3H       | 1        | 0.77%   |
| Gigabyte Z370          | 1        | 0.77%   |
| Gigabyte M68MT-S2P     | 1        | 0.77%   |
| Gigabyte M52LT-D3P     | 1        | 0.77%   |
| Gigabyte H81M-S2PV     | 1        | 0.77%   |
| Gigabyte H61M-S1       | 1        | 0.77%   |
| Gigabyte H61M-DS2      | 1        | 0.77%   |
| Gigabyte GA-880GM-UD2H | 1        | 0.77%   |
| Gigabyte GA-78LMT-USB3 | 1        | 0.77%   |
| Gigabyte EP45C-DS3R    | 1        | 0.77%   |
| Gigabyte COMFOR        | 1        | 0.77%   |
| Gigabyte B450M         | 1        | 0.77%   |
| Gigabyte 945GM-S2      | 1        | 0.77%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 15       | 11.54%  |
| 2010 | 14       | 10.77%  |
| 2019 | 11       | 8.46%   |
| 2007 | 11       | 8.46%   |
| 2020 | 9        | 6.92%   |
| 2018 | 9        | 6.92%   |
| 2011 | 9        | 6.92%   |
| 2008 | 9        | 6.92%   |
| 2014 | 8        | 6.15%   |
| 2013 | 7        | 5.38%   |
| 2021 | 5        | 3.85%   |
| 2016 | 5        | 3.85%   |
| 2015 | 5        | 3.85%   |
| 2009 | 5        | 3.85%   |
| 2005 | 3        | 2.31%   |
| 2003 | 2        | 1.54%   |
| 2017 | 1        | 0.77%   |
| 2006 | 1        | 0.77%   |
| 2004 | 1        | 0.77%   |

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
| Disabled | 128      | 98.46%  |
| Enabled  | 2        | 1.54%   |

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
| 8.01-16.0   | 34       | 25.56%  |
| 3.01-4.0    | 29       | 21.8%   |
| 16.01-24.0  | 24       | 18.05%  |
| 4.01-8.0    | 18       | 13.53%  |
| 32.01-64.0  | 10       | 7.52%   |
| 2.01-3.0    | 8        | 6.02%   |
| 1.01-2.0    | 6        | 4.51%   |
| 0.51-1.0    | 3        | 2.26%   |
| 64.01-256.0 | 1        | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 63       | 45%     |
| 2.01-3.0 | 30       | 21.43%  |
| 3.01-4.0 | 19       | 13.57%  |
| 0.51-1.0 | 17       | 12.14%  |
| 4.01-8.0 | 11       | 7.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 45.93%  |
| 2      | 44       | 32.59%  |
| 3      | 14       | 10.37%  |
| 4      | 7        | 5.19%   |
| 7      | 4        | 2.96%   |
| 5      | 2        | 1.48%   |
| 8      | 1        | 0.74%   |
| 6      | 1        | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 77       | 57.89%  |
| No        | 56       | 42.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 130      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 62.41%  |
| Yes       | 50       | 37.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 105      | 80.15%  |
| Yes       | 26       | 19.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 17       | 13.08%  |
| USA          | 16       | 12.31%  |
| Brazil       | 14       | 10.77%  |
| France       | 11       | 8.46%   |
| Poland       | 5        | 3.85%   |
| Canada       | 5        | 3.85%   |
| Ukraine      | 4        | 3.08%   |
| UK           | 4        | 3.08%   |
| Netherlands  | 4        | 3.08%   |
| Spain        | 3        | 2.31%   |
| Russia       | 3        | 2.31%   |
| Bulgaria     | 3        | 2.31%   |
| Belgium      | 3        | 2.31%   |
| Argentina    | 3        | 2.31%   |
| Sweden       | 2        | 1.54%   |
| Portugal     | 2        | 1.54%   |
| Italy        | 2        | 1.54%   |
| Hungary      | 2        | 1.54%   |
| Greece       | 2        | 1.54%   |
| Finland      | 2        | 1.54%   |
| Austria      | 2        | 1.54%   |
| Australia    | 2        | 1.54%   |
| Uruguay      | 1        | 0.77%   |
| Turkey       | 1        | 0.77%   |
| South Africa | 1        | 0.77%   |
| Slovakia     | 1        | 0.77%   |
| Serbia       | 1        | 0.77%   |
| Romania      | 1        | 0.77%   |
| Puerto Rico  | 1        | 0.77%   |
| Philippines  | 1        | 0.77%   |
| Norway       | 1        | 0.77%   |
| Mexico       | 1        | 0.77%   |
| Luxembourg   | 1        | 0.77%   |
| India        | 1        | 0.77%   |
| Estonia      | 1        | 0.77%   |
| Egypt        | 1        | 0.77%   |
| Czechia      | 1        | 0.77%   |
| Croatia      | 1        | 0.77%   |
| Colombia     | 1        | 0.77%   |
| Chile        | 1        | 0.77%   |
| Belarus      | 1        | 0.77%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Paris                         | 4        | 2.92%   |
| Toronto                       | 2        | 1.46%   |
| Sofia                         | 2        | 1.46%   |
| Rio de Janeiro                | 2        | 1.46%   |
| Perth                         | 2        | 1.46%   |
| Helsinki                      | 2        | 1.46%   |
| Hamburg                       | 2        | 1.46%   |
| Belo Horizonte                | 2        | 1.46%   |
| Athens                        | 2        | 1.46%   |
| Yampil                        | 1        | 0.73%   |
| Yalta                         | 1        | 0.73%   |
| Wroclaw                       | 1        | 0.73%   |
| Wolfsburg                     | 1        | 0.73%   |
| Wernberg-Koblitz              | 1        | 0.73%   |
| Warsaw                        | 1        | 0.73%   |
| Wakefield                     | 1        | 0.73%   |
| Vinkovci                      | 1        | 0.73%   |
| Vienna                        | 1        | 0.73%   |
| Ulm                           | 1        | 0.73%   |
| Ukhta                         | 1        | 0.73%   |
| Tubarao                       | 1        | 0.73%   |
| Tires                         | 1        | 0.73%   |
| Tingvoll                      | 1        | 0.73%   |
| Timișoara                    | 1        | 0.73%   |
| Thornton                      | 1        | 0.73%   |
| The Hague                     | 1        | 0.73%   |
| Thaur                         | 1        | 0.73%   |
| Taby                          | 1        | 0.73%   |
| São Luís                    | 1        | 0.73%   |
| Shimla                        | 1        | 0.73%   |
| Sherbrooke                    | 1        | 0.73%   |
| Seibersbach                   | 1        | 0.73%   |
| Santa Rosa                    | 1        | 0.73%   |
| San Juan                      | 1        | 0.73%   |
| San Giorgio della Richinvelda | 1        | 0.73%   |
| San Antonio                   | 1        | 0.73%   |
| Salem                         | 1        | 0.73%   |
| Saint-Brice-Courcelles        | 1        | 0.73%   |
| Rotterdam                     | 1        | 0.73%   |
| Rosario                       | 1        | 0.73%   |
| Ribeir??o Preto               | 1        | 0.73%   |
| Rhyl                          | 1        | 0.73%   |
| Rapla                         | 1        | 0.73%   |
| Radom                         | 1        | 0.73%   |
| Quilmes                       | 1        | 0.73%   |
| Puerto Vallarta               | 1        | 0.73%   |
| Presidente Prudente           | 1        | 0.73%   |
| Poznan                        | 1        | 0.73%   |
| Plovdiv                       | 1        | 0.73%   |
| Pasto                         | 1        | 0.73%   |
| Park City                     | 1        | 0.73%   |
| Paracin                       | 1        | 0.73%   |
| Osasco                        | 1        | 0.73%   |
| Offenburg                     | 1        | 0.73%   |
| Novokuybyshevsk               | 1        | 0.73%   |
| Niagara Falls                 | 1        | 0.73%   |
| Munich                        | 1        | 0.73%   |
| Montreal                      | 1        | 0.73%   |
| Montevideo                    | 1        | 0.73%   |
| Mogilev                       | 1        | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 50       | 84     | 23.47%  |
| Seagate             | 38       | 64     | 17.84%  |
| Samsung Electronics | 35       | 53     | 16.43%  |
| Kingston            | 11       | 13     | 5.16%   |
| Hitachi             | 11       | 14     | 5.16%   |
| Toshiba             | 10       | 15     | 4.69%   |
| SanDisk             | 8        | 12     | 3.76%   |
| Crucial             | 7        | 9      | 3.29%   |
| Phison              | 6        | 7      | 2.82%   |
| A-DATA Technology   | 6        | 6      | 2.82%   |
| Intel               | 4        | 4      | 1.88%   |
| MAXTOR              | 3        | 5      | 1.41%   |
| Intenso             | 3        | 4      | 1.41%   |
| China               | 3        | 3      | 1.41%   |
| TCSUNBOW            | 2        | 2      | 0.94%   |
| OCZ                 | 2        | 3      | 0.94%   |
| Micron Technology   | 2        | 2      | 0.94%   |
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
| Toshiba DT01ACA100 1TB              | 4        | 1.58%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 1.58%   |
| Samsung SSD 860 EVO 500GB           | 3        | 1.19%   |
| Samsung HD322HJ 320GB               | 3        | 1.19%   |
| Samsung HD103SJ 1TB                 | 3        | 1.19%   |
| Kingston SA400S37120G 120GB SSD     | 3        | 1.19%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2        | 0.79%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.79%   |
| WDC WD3200AAKS-00L9A0 320GB         | 2        | 0.79%   |
| WDC WD2500AAKX-753CA1 250GB         | 2        | 0.79%   |
| WDC WD1600AABS-00PRA0 160GB         | 2        | 0.79%   |
| WDC WD10EZEX-60WN4A0 1TB            | 2        | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2        | 0.79%   |
| Seagate ST2000LX001-1RG174 2TB      | 2        | 0.79%   |
| Seagate ST2000DM001-9YN164 2TB      | 2        | 0.79%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 0.79%   |
| Seagate Expansion 1TB               | 2        | 0.79%   |
| Samsung SSD 850 EVO 500GB           | 2        | 0.79%   |
| Samsung SSD 850 EVO 250GB           | 2        | 0.79%   |
| Samsung SP0802N 80GB                | 2        | 0.79%   |
| Samsung NVMe SSD Drive 2TB          | 2        | 0.79%   |
| Samsung NVMe SSD Drive 256GB        | 2        | 0.79%   |
| Samsung HD161HJ 160GB               | 2        | 0.79%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2        | 0.79%   |
| Kingston SV300S37A120G 120GB SSD    | 2        | 0.79%   |
| Kingston SA400S37240G 240GB SSD     | 2        | 0.79%   |
| Crucial CT500MX500SSD1 500GB        | 2        | 0.79%   |
| Crucial CT240BX500SSD1 240GB        | 2        | 0.79%   |
| A-DATA SU650 240GB SSD              | 2        | 0.79%   |
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
| WDC                 | 46       | 79     | 35.11%  |
| Seagate             | 38       | 64     | 29.01%  |
| Samsung Electronics | 21       | 29     | 16.03%  |
| Hitachi             | 11       | 14     | 8.4%    |
| Toshiba             | 8        | 9      | 6.11%   |
| MAXTOR              | 3        | 5      | 2.29%   |
| Unknown             | 1        | 1      | 0.76%   |
| KESU                | 1        | 2      | 0.76%   |
| HPE                 | 1        | 5      | 0.76%   |
| Fujitsu             | 1        | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 16     | 17.14%  |
| Kingston            | 10       | 12     | 14.29%  |
| SanDisk             | 8        | 12     | 11.43%  |
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
| HDD     | 102      | 209    | 58.29%  |
| SSD     | 57       | 89     | 32.57%  |
| NVMe    | 15       | 20     | 8.57%   |
| Unknown | 1        | 1      | 0.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 124      | 284    | 84.93%  |
| NVMe | 14       | 19     | 9.59%   |
| SAS  | 8        | 16     | 5.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 105      | 200    | 60.69%  |
| 0.51-1.0   | 44       | 63     | 25.43%  |
| 1.01-2.0   | 17       | 24     | 9.83%   |
| 3.01-4.0   | 3        | 7      | 1.73%   |
| 2.01-3.0   | 2        | 2      | 1.16%   |
| 4.01-10.0  | 2        | 2      | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 42       | 31.11%  |
| 251-500        | 28       | 20.74%  |
| 1001-2000      | 18       | 13.33%  |
| More than 3000 | 13       | 9.63%   |
| 501-1000       | 11       | 8.15%   |
| 2001-3000      | 8        | 5.93%   |
| 51-100         | 8        | 5.93%   |
| 21-50          | 7        | 5.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 42       | 30.22%  |
| 21-50          | 32       | 23.02%  |
| 51-100         | 18       | 12.95%  |
| 251-500        | 11       | 7.91%   |
| 1001-2000      | 10       | 7.19%   |
| 101-250        | 9        | 6.47%   |
| 501-1000       | 9        | 6.47%   |
| More than 3000 | 4        | 2.88%   |
| 2001-3000      | 4        | 2.88%   |

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
| Detected | 118      | 284    | 86.76%  |
| Works    | 16       | 33     | 11.76%  |
| Malfunc  | 2        | 2      | 1.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 90       | 53.25%  |
| AMD                              | 26       | 15.38%  |
| Nvidia                           | 9        | 5.33%   |
| ASMedia Technology               | 9        | 5.33%   |
| JMicron Technology               | 8        | 4.73%   |
| Samsung Electronics              | 6        | 3.55%   |
| Phison Electronics               | 6        | 3.55%   |
| VIA Technologies                 | 4        | 2.37%   |
| Marvell Technology Group         | 4        | 2.37%   |
| Silicon Motion                   | 2        | 1.18%   |
| Silicon Integrated Systems [SiS] | 2        | 1.18%   |
| Silicon Image                    | 1        | 0.59%   |
| Kingston Technology Company      | 1        | 0.59%   |
| Broadcom / LSI                   | 1        | 0.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 6.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 5.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 12       | 5.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11       | 4.78%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 3.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.48%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 2.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.17%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 2.17%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 2.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.17%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.17%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 4        | 1.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 1.74%   |
| Nvidia MCP61 IDE                                                                        | 4        | 1.74%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.74%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.74%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.74%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 1.74%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3        | 1.3%    |
| Phison E12 NVMe Controller                                                              | 3        | 1.3%    |
| JMicron JMB368 IDE controller                                                           | 3        | 1.3%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.3%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.3%    |
| AMD FCH SATA Controller D                                                               | 3        | 1.3%    |
| Nvidia nForce2 IDE                                                                      | 2        | 0.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.87%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.87%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.87%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.87%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 0.87%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.87%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 0.87%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.87%   |
| VIA Serial ATA Controller                                                               | 1        | 0.43%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.43%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.43%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1        | 0.43%   |
| Silicon Integrated Systems [SiS] 182 SATA/RAID Controller                               | 1        | 0.43%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.43%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.43%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.43%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.43%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.43%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.43%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.43%   |
| Marvell Group 88SX7042 PCI-e 4-port SATA-II                                             | 1        | 0.43%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.43%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.43%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.43%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.43%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 86       | 51.81%  |
| IDE  | 55       | 33.13%  |
| NVMe | 14       | 8.43%   |
| RAID | 8        | 4.82%   |
| SAS  | 2        | 1.2%    |
| SCSI | 1        | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 93       | 71.54%  |
| AMD    | 37       | 28.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-8100 CPU @ 3.60GHz            | 4        | 3.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.31%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2.31%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 2.31%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 3        | 2.31%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 3        | 2.31%   |
| Intel Pentium D CPU 2.80GHz                 | 2        | 1.54%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 1.54%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 1.54%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 1.54%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 1.54%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.54%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.54%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.54%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.54%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz       | 2        | 1.54%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.54%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.54%   |
| AMD Sempron Processor 3000+                 | 2        | 1.54%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.54%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.54%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.54%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1        | 0.77%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 0.77%   |
| Intel Xeon CPU E5472 @ 3.00GHz              | 1        | 0.77%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.77%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.77%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.77%   |
| Intel Pentium D CPU 3.20GHz                 | 1        | 0.77%   |
| Intel Pentium CPU J4205 @ 1.50GHz           | 1        | 0.77%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.77%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.77%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.77%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.77%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.77%   |
| Intel Core i9-10900T CPU @ 1.90GHz          | 1        | 0.77%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.77%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1        | 0.77%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1        | 0.77%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.77%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.77%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 0.77%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.77%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 0.77%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 0.77%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 0.77%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 0.77%   |
| Intel Core i5-3450S CPU @ 2.80GHz           | 1        | 0.77%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 0.77%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 0.77%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 0.77%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1        | 0.77%   |
| Intel Core i3-2130 CPU @ 3.40GHz            | 1        | 0.77%   |
| Intel Core i3-2120T CPU @ 2.60GHz           | 1        | 0.77%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 1        | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 15       | 11.54%  |
| Intel Core i5           | 15       | 11.54%  |
| Intel Core 2 Duo        | 13       | 10%     |
| Intel Core i3           | 11       | 8.46%   |
| Intel Core 2 Quad       | 9        | 6.92%   |
| Intel Pentium           | 7        | 5.38%   |
| Intel Xeon              | 6        | 4.62%   |
| Intel Celeron           | 5        | 3.85%   |
| AMD Ryzen 7             | 5        | 3.85%   |
| AMD Ryzen 5             | 5        | 3.85%   |
| AMD Sempron             | 4        | 3.08%   |
| AMD FX                  | 4        | 3.08%   |
| AMD Athlon 64 X2        | 4        | 3.08%   |
| Intel Pentium Dual-Core | 3        | 2.31%   |
| Intel Pentium D         | 3        | 2.31%   |
| AMD Phenom II X4        | 3        | 2.31%   |
| Intel Pentium 4         | 2        | 1.54%   |
| Intel Core i9           | 2        | 1.54%   |
| Intel Core 2            | 2        | 1.54%   |
| AMD Ryzen 3             | 2        | 1.54%   |
| AMD Phenom II X6        | 2        | 1.54%   |
| AMD Athlon XP           | 2        | 1.54%   |
| AMD Ryzen 9             | 1        | 0.77%   |
| AMD Ryzen 5 PRO         | 1        | 0.77%   |
| AMD Athlon II X4        | 1        | 0.77%   |
| AMD Athlon II X2        | 1        | 0.77%   |
| AMD Athlon              | 1        | 0.77%   |
| AMD A10                 | 1        | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 55       | 42.31%  |
| 2      | 47       | 36.15%  |
| 8      | 8        | 6.15%   |
| 6      | 8        | 6.15%   |
| 1      | 8        | 6.15%   |
| 16     | 1        | 0.77%   |
| 12     | 1        | 0.77%   |
| 10     | 1        | 0.77%   |
| 3      | 1        | 0.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 128      | 98.46%  |
| 2      | 2        | 1.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 82       | 63.08%  |
| 2      | 48       | 36.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 126      | 96.92%  |
| 32-bit         | 4        | 3.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 11.45%  |
| 0x1067a    | 14       | 10.69%  |
| 0x206a7    | 12       | 9.16%   |
| 0x306c3    | 11       | 8.4%    |
| 0x306a9    | 9        | 6.87%   |
| 0x10677    | 5        | 3.82%   |
| 0x906eb    | 4        | 3.05%   |
| 0x6fd      | 4        | 3.05%   |
| 0x08108109 | 4        | 3.05%   |
| 0x6fb      | 3        | 2.29%   |
| 0x106e5    | 3        | 2.29%   |
| 0x010000c8 | 3        | 2.29%   |
| 0xf65      | 2        | 1.53%   |
| 0xf64      | 2        | 1.53%   |
| 0x906ed    | 2        | 1.53%   |
| 0x906ea    | 2        | 1.53%   |
| 0x6f2      | 2        | 1.53%   |
| 0x506e3    | 2        | 1.53%   |
| 0x106a5    | 2        | 1.53%   |
| 0x08701021 | 2        | 1.53%   |
| 0x0800820d | 2        | 1.53%   |
| 0x06000852 | 2        | 1.53%   |
| 0x0600063e | 2        | 1.53%   |
| 0x010000dc | 2        | 1.53%   |
| 0xf29      | 1        | 0.76%   |
| 0xa0655    | 1        | 0.76%   |
| 0x706a8    | 1        | 0.76%   |
| 0x506c9    | 1        | 0.76%   |
| 0x40651    | 1        | 0.76%   |
| 0x306f2    | 1        | 0.76%   |
| 0x206d7    | 1        | 0.76%   |
| 0x20655    | 1        | 0.76%   |
| 0x10676    | 1        | 0.76%   |
| 0x0a201009 | 1        | 0.76%   |
| 0x08701013 | 1        | 0.76%   |
| 0x08101102 | 1        | 0.76%   |
| 0x08101016 | 1        | 0.76%   |
| 0x0800820c | 1        | 0.76%   |
| 0x08001129 | 1        | 0.76%   |
| 0x08001126 | 1        | 0.76%   |
| 0x0700010f | 1        | 0.76%   |
| 0x06001119 | 1        | 0.76%   |
| 0x010000db | 1        | 0.76%   |
| 0x010000c7 | 1        | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 20       | 15.38%  |
| SandyBridge   | 16       | 12.31%  |
| Haswell       | 13       | 10%     |
| KabyLake      | 9        | 6.92%   |
| IvyBridge     | 9        | 6.92%   |
| Core          | 9        | 6.92%   |
| Zen+          | 7        | 5.38%   |
| K8 Hammer     | 7        | 5.38%   |
| K10           | 7        | 5.38%   |
| NetBurst      | 6        | 4.62%   |
| Nehalem       | 5        | 3.85%   |
| Zen           | 4        | 3.08%   |
| Zen 2         | 3        | 2.31%   |
| Piledriver    | 3        | 2.31%   |
| Skylake       | 2        | 1.54%   |
| K6            | 2        | 1.54%   |
| Bulldozer     | 2        | 1.54%   |
| Zen 3         | 1        | 0.77%   |
| Westmere      | 1        | 0.77%   |
| Jaguar        | 1        | 0.77%   |
| Goldmont plus | 1        | 0.77%   |
| Goldmont      | 1        | 0.77%   |
| CometLake     | 1        | 0.77%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 57       | 40.71%  |
| Intel             | 48       | 34.29%  |
| AMD               | 30       | 21.43%  |
| VIA Technologies  | 4        | 2.86%   |
| ASPEED Technology | 1        | 0.71%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                              | Desktops | Percent |
|------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 13       | 8.9%    |
| Nvidia GM206 [GeForce GTX 960]                                                     | 6        | 4.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller        | 6        | 4.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                   | 6        | 4.11%   |
| Intel 4 Series Chipset Integrated Graphics Controller                              | 6        | 4.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                            | 6        | 4.11%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                          | 5        | 3.42%   |
| Nvidia GT218 [GeForce 210]                                                         | 4        | 2.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                 | 4        | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]               | 4        | 2.74%   |
| Nvidia GK208B [GeForce GT 710]                                                     | 3        | 2.05%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                   | 3        | 2.05%   |
| Nvidia TU106 [GeForce RTX 2070]                                                    | 2        | 1.37%   |
| Nvidia GP107 [GeForce GTX 1050]                                                    | 2        | 1.37%   |
| Nvidia GP104 [GeForce GTX 1070]                                                    | 2        | 1.37%   |
| Nvidia GK104 [GeForce GTX 760]                                                     | 2        | 1.37%   |
| Nvidia GF104 [GeForce GTX 460]                                                     | 2        | 1.37%   |
| Nvidia G86 [GeForce 8400 GS]                                                       | 2        | 1.37%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                            | 2        | 1.37%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                   | 2        | 1.37%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                         | 1        | 0.68%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                          | 1        | 0.68%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                  | 1        | 0.68%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro]      | 1        | 0.68%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                             | 1        | 0.68%   |
| Nvidia NV43 [GeForce 6600]                                                         | 1        | 0.68%   |
| Nvidia NV36 [GeForce FX 5700VE]                                                    | 1        | 0.68%   |
| Nvidia NV34 [GeForce FX 5200]                                                      | 1        | 0.68%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                              | 1        | 0.68%   |
| Nvidia GT218 [GeForce 310]                                                         | 1        | 0.68%   |
| Nvidia GT200 [GeForce GTX 260]                                                     | 1        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                | 1        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                | 1        | 0.68%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                  | 1        | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                                     | 1        | 0.68%   |
| Nvidia GK107 [GeForce GTX 650]                                                     | 1        | 0.68%   |
| Nvidia GK104 [GeForce GTX 660 OEM]                                                 | 1        | 0.68%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                  | 1        | 0.68%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                              | 1        | 0.68%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                  | 1        | 0.68%   |
| Nvidia GF108 [GeForce GT 730]                                                      | 1        | 0.68%   |
| Nvidia GF108 [GeForce GT 630]                                                      | 1        | 0.68%   |
| Nvidia GF108 [GeForce GT 420]                                                      | 1        | 0.68%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                | 1        | 0.68%   |
| Nvidia G96GL [Quadro FX 380]                                                       | 1        | 0.68%   |
| Nvidia G96C [GeForce 9500 GT]                                                      | 1        | 0.68%   |
| Nvidia G96C [GeForce 9400 GT]                                                      | 1        | 0.68%   |
| Nvidia G94 [GeForce 9600 GT]                                                       | 1        | 0.68%   |
| Nvidia G92 [GeForce GTS 250]                                                       | 1        | 0.68%   |
| Nvidia G73 [GeForce 7600 GS]                                                       | 1        | 0.68%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                               | 1        | 0.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                         | 1        | 0.68%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                             | 1        | 0.68%   |
| Intel HD Graphics 510                                                              | 1        | 0.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 1        | 0.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                | 1        | 0.68%   |
| Intel Core Processor Integrated Graphics Controller                                | 1        | 0.68%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                           | 1        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 1        | 0.68%   |
| Intel 82Q35 Express Integrated Graphics Controller                                 | 1        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 53       | 40.46%  |
| 1 x Intel      | 39       | 29.77%  |
| 1 x AMD        | 27       | 20.61%  |
| 1 x VIA        | 4        | 3.05%   |
| 2 x AMD        | 3        | 2.29%   |
| Intel + Nvidia | 3        | 2.29%   |
| 2 x Nvidia     | 1        | 0.76%   |
| 1 x ASPEED     | 1        | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 87       | 66.41%  |
| Proprietary | 25       | 19.08%  |
| Unknown     | 19       | 14.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 60       | 45.45%  |
| 0.51-1.0   | 20       | 15.15%  |
| 0.01-0.5   | 17       | 12.88%  |
| 1.01-2.0   | 13       | 9.85%   |
| 3.01-4.0   | 11       | 8.33%   |
| 7.01-8.0   | 9        | 6.82%   |
| 5.01-6.0   | 1        | 0.76%   |
| 2.01-3.0   | 1        | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 24       | 16.9%   |
| Dell                    | 15       | 10.56%  |
| Goldstar                | 14       | 9.86%   |
| Acer                    | 12       | 8.45%   |
| Ancor Communications    | 8        | 5.63%   |
| AOC                     | 7        | 4.93%   |
| Unknown                 | 6        | 4.23%   |
| Philips                 | 6        | 4.23%   |
| Hewlett-Packard         | 5        | 3.52%   |
| BenQ                    | 5        | 3.52%   |
| Sony                    | 3        | 2.11%   |
| Lenovo                  | 3        | 2.11%   |
| Iiyama                  | 3        | 2.11%   |
| Sceptre Tech            | 2        | 1.41%   |
| NEC Computers           | 2        | 1.41%   |
| LG Electronics          | 2        | 1.41%   |
| Fujitsu Siemens         | 2        | 1.41%   |
| ___                     | 1        | 0.7%    |
| Vestel                  | 1        | 0.7%    |
| Toshiba                 | 1        | 0.7%    |
| Targa Visionary         | 1        | 0.7%    |
| OEM                     | 1        | 0.7%    |
| NCS                     | 1        | 0.7%    |
| Mitsubishi              | 1        | 0.7%    |
| Microstep               | 1        | 0.7%    |
| Medion                  | 1        | 0.7%    |
| IBM                     | 1        | 0.7%    |
| Hitachi                 | 1        | 0.7%    |
| eMachines               | 1        | 0.7%    |
| ELSA International      | 1        | 0.7%    |
| Elo Touch               | 1        | 0.7%    |
| Eizo                    | 1        | 0.7%    |
| DENON                   | 1        | 0.7%    |
| Compal                  | 1        | 0.7%    |
| Chi Mei Optoelectronics | 1        | 0.7%    |
| Belinea                 | 1        | 0.7%    |
| AUS                     | 1        | 0.7%    |
| ASUSTek Computer        | 1        | 0.7%    |
| AOpen                   | 1        | 0.7%    |
| AGO                     | 1        | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch     | 2        | 1.36%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                       | 2        | 1.36%   |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch                   | 1        | 0.68%   |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                               | 1        | 0.68%   |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                      | 1        | 0.68%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.68%   |
| Unknown LCD Monitor SAMSUNG                                             | 1        | 0.68%   |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                       | 1        | 0.68%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                                | 1        | 0.68%   |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch                  | 1        | 0.68%   |
| Toshiba LCD Monitor TV 1920x1080                                        | 1        | 0.68%   |
| Targa Visionary LCD19-4 TARA194 1280x1024 376x301mm 19.0-inch           | 1        | 0.68%   |
| Sony TV SNY4C03 1920x1080 1063x598mm 48.0-inch                          | 1        | 0.68%   |
| Sony TV SNY1B02 1360x768 1600x900mm 72.3-inch                           | 1        | 0.68%   |
| Sony LCD Monitor TV 3840x1080                                           | 1        | 0.68%   |
| Sceptre Tech F24 SPT0961 1920x1080 480x260mm 21.5-inch                  | 1        | 0.68%   |
| Sceptre Tech E275W-1920 SPT0ABF 1920x1080 443x249mm 20.0-inch           | 1        | 0.68%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch       | 1        | 0.68%   |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch       | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch     | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 459x296mm 21.5-inch    | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM034F 1440x900 428x255mm 19.6-inch     | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0303 1680x1050 494x320mm 23.2-inch    | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch    | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM006E 1280x1024 338x270mm 17.0-inch    | 1        | 0.68%   |
| Samsung Electronics SMS22A200/460 SAM0831 1920x1080 477x268mm 21.5-inch | 1        | 0.68%   |
| Samsung Electronics SMB2230 SAM063E 1920x1080 477x268mm 21.5-inch       | 1        | 0.68%   |
| Samsung Electronics SA300/350/360 SAM07D6 1920x1080 531x299mm 24.0-inch | 1        | 0.68%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 530x300mm 24.0-inch       | 1        | 0.68%   |
| Samsung Electronics S24F350 SAM0D21 1680x1050 520x290mm 23.4-inch       | 1        | 0.68%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.68%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1        | 0.68%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch       | 1        | 0.68%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1        | 0.68%   |
| Samsung Electronics S22B300 SAM08AC 1680x1050 480x270mm 21.7-inch       | 1        | 0.68%   |
| Samsung Electronics S16B110 SAM097E 1366x768 360x210mm 16.4-inch        | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0F39 1920x1080 1210x680mm 54.6-inch  | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM08FE 1920x1080                       | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SA300/SA350 1920x1080                   | 1        | 0.68%   |
| Samsung Electronics LCD Monitor S22B350 1920x1080                       | 1        | 0.68%   |
| Philips PHL 288E2 PHLC231 3840x2160 620x340mm 27.8-inch                 | 1        | 0.68%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 530x300mm 24.0-inch                 | 1        | 0.68%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                 | 1        | 0.68%   |
| Philips LCD Monitor PHL 498P9 1920x1080                                 | 1        | 0.68%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                     | 1        | 0.68%   |
| Philips 170B PHL081D 1280x1024 338x270mm 17.0-inch                      | 1        | 0.68%   |
| OEM LCD Monitor 46W_LCD_TV 1920x1080                                    | 1        | 0.68%   |
| NEC Computers LCD73V NEC66C2 1280x1024 338x270mm 17.0-inch              | 1        | 0.68%   |
| NEC Computers LCD1810X NEC6594 1280x1024 359x287mm 18.1-inch            | 1        | 0.68%   |
| NCS LCD Monitor NCS2275 1920x1080 300x230mm 14.9-inch                   | 1        | 0.68%   |
| Mitsubishi DiamondPlus73 MEL4460 1280x1024 310x232mm 15.2-inch          | 1        | 0.68%   |
| Microstep LCD Monitor MSI PS341WU 7680x2160                             | 1        | 0.68%   |
| Medion MD 20144 MED3636 1920x1080 510x287mm 23.0-inch                   | 1        | 0.68%   |
| LG Electronics LCD Monitor LG TV 1360x768                               | 1        | 0.68%   |
| LG Electronics LCD Monitor 27EA53 1920x1080                             | 1        | 0.68%   |
| Lenovo LCD Monitor LEN1421 1366x768 310x170mm 13.9-inch                 | 1        | 0.68%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                    | 1        | 0.68%   |
| Lenovo D22-20 LEN66AD 1920x1080 477x268mm 21.5-inch                     | 1        | 0.68%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                   | 1        | 0.68%   |
| Iiyama PLE2403WS IVM5604 1920x1200 519x324mm 24.1-inch                  | 1        | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 61       | 44.53%  |
| 1280x1024 (SXGA)   | 25       | 18.25%  |
| 1440x900 (WXGA+)   | 9        | 6.57%   |
| 1680x1050 (WSXGA+) | 8        | 5.84%   |
| 1920x1200 (WUXGA)  | 5        | 3.65%   |
| 3840x2160 (4K)     | 4        | 2.92%   |
| 1366x768 (WXGA)    | 4        | 2.92%   |
| 1360x768           | 4        | 2.92%   |
| 1024x768 (XGA)     | 4        | 2.92%   |
| 1600x900 (HD+)     | 3        | 2.19%   |
| Unknown            | 3        | 2.19%   |
| 3440x1440          | 2        | 1.46%   |
| 7680x2160          | 1        | 0.73%   |
| 4240x1440          | 1        | 0.73%   |
| 3840x1080          | 1        | 0.73%   |
| 2560x1440 (QHD)    | 1        | 0.73%   |
| 1600x1200          | 1        | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 15.11%  |
| 21      | 16       | 11.51%  |
| 24      | 14       | 10.07%  |
| 19      | 14       | 10.07%  |
| 17      | 13       | 9.35%   |
| 23      | 12       | 8.63%   |
| 27      | 10       | 7.19%   |
| 18      | 9        | 6.47%   |
| 15      | 7        | 5.04%   |
| 22      | 6        | 4.32%   |
| 31      | 3        | 2.16%   |
| 20      | 3        | 2.16%   |
| 72      | 1        | 0.72%   |
| 54      | 1        | 0.72%   |
| 52      | 1        | 0.72%   |
| 48      | 1        | 0.72%   |
| 33      | 1        | 0.72%   |
| 32      | 1        | 0.72%   |
| 26      | 1        | 0.72%   |
| 16      | 1        | 0.72%   |
| 14      | 1        | 0.72%   |
| 13      | 1        | 0.72%   |
| 12      | 1        | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 40       | 29.41%  |
| 501-600     | 32       | 23.53%  |
| Unknown     | 21       | 15.44%  |
| 301-350     | 20       | 14.71%  |
| 351-400     | 11       | 8.09%   |
| 601-700     | 4        | 2.94%   |
| 1001-1500   | 3        | 2.21%   |
| 701-800     | 2        | 1.47%   |
| 201-300     | 2        | 1.47%   |
| 1501-2000   | 1        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 61       | 45.52%  |
| 5/4     | 21       | 15.67%  |
| 16/10   | 21       | 15.67%  |
| Unknown | 20       | 14.93%  |
| 4/3     | 9        | 6.72%   |
| 3/2     | 1        | 0.75%   |
| 21/9    | 1        | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 36       | 26.09%  |
| 151-200        | 27       | 19.57%  |
| Unknown        | 21       | 15.22%  |
| 141-150        | 17       | 12.32%  |
| 301-350        | 11       | 7.97%   |
| 101-110        | 7        | 5.07%   |
| 251-300        | 6        | 4.35%   |
| 351-500        | 5        | 3.62%   |
| More than 1000 | 3        | 2.17%   |
| 111-120        | 2        | 1.45%   |
| 81-90          | 1        | 0.72%   |
| 71-80          | 1        | 0.72%   |
| 501-1000       | 1        | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 82       | 63.08%  |
| Unknown | 21       | 16.15%  |
| 101-120 | 19       | 14.62%  |
| 1-50    | 4        | 3.08%   |
| 121-160 | 3        | 2.31%   |
| 161-240 | 1        | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 106      | 80.3%   |
| 2     | 20       | 15.15%  |
| 0     | 5        | 3.79%   |
| 3     | 1        | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 78       | 43.09%  |
| Intel                            | 37       | 20.44%  |
| Qualcomm Atheros                 | 18       | 9.94%   |
| Ralink Technology                | 8        | 4.42%   |
| Nvidia                           | 8        | 4.42%   |
| Broadcom                         | 6        | 3.31%   |
| TP-Link                          | 4        | 2.21%   |
| VIA Technologies                 | 3        | 1.66%   |
| Marvell Technology Group         | 3        | 1.66%   |
| Broadcom Limited                 | 2        | 1.1%    |
| AVM                              | 2        | 1.1%    |
| Sitecom Europe                   | 1        | 0.55%   |
| Silicon Integrated Systems [SiS] | 1        | 0.55%   |
| Ralink                           | 1        | 0.55%   |
| Microsoft                        | 1        | 0.55%   |
| Mellanox Technologies            | 1        | 0.55%   |
| LSI                              | 1        | 0.55%   |
| JMicron Technology               | 1        | 0.55%   |
| Huawei Technologies              | 1        | 0.55%   |
| Edimax Technology                | 1        | 0.55%   |
| Belkin Components                | 1        | 0.55%   |
| ASUSTek Computer                 | 1        | 0.55%   |
| ADMtek                           | 1        | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60       | 29.7%   |
| Nvidia MCP61 Ethernet                                             | 6        | 2.97%   |
| Intel I211 Gigabit Network Connection                             | 6        | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 2.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 2.48%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.98%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3        | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.49%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 1.49%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 1.49%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 1.49%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2        | 0.99%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.99%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.99%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 0.99%   |
| Nvidia nForce2 Ethernet Controller                                | 2        | 0.99%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.99%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.99%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.99%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.99%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.99%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.99%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.99%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.99%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.5%    |
| TP-Link TL WN823N RTL8192EU                                       | 1        | 0.5%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.5%    |
| TP-Link 802.11n NIC                                               | 1        | 0.5%    |
| Sitecom Europe RTL8188S WLAN Adapter                              | 1        | 0.5%    |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.5%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.5%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.5%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 1        | 0.5%    |
| Realtek 802.11ac WLAN Adapter                                     | 1        | 0.5%    |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.5%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 0.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 0.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.5%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.5%    |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 0.5%    |
| Mellanox MT23108 InfiniHost                                       | 1        | 0.5%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1        | 0.5%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.5%    |
| LSI 56k WinModem                                                  | 1        | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.5%    |
| Intel Wireless 8265 / 8275                                        | 1        | 0.5%    |

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
| TP-Link               | 4        | 7.14%   |
| Broadcom              | 3        | 5.36%   |
| AVM                   | 2        | 3.57%   |
| Sitecom Europe        | 1        | 1.79%   |
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


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                             | 4        | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 3        | 5.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 3        | 5.36%   |
| Intel Wi-Fi 6 AX200                                                         | 3        | 5.36%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                             | 2        | 3.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 2        | 3.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 2        | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 2        | 3.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 2        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2        | 3.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 1        | 1.79%   |
| TP-Link TL WN823N RTL8192EU                                                 | 1        | 1.79%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1        | 1.79%   |
| TP-Link 802.11n NIC                                                         | 1        | 1.79%   |
| Sitecom Europe RTL8188S WLAN Adapter                                        | 1        | 1.79%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                             | 1        | 1.79%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                      | 1        | 1.79%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                   | 1        | 1.79%   |
| Realtek 802.11ac WLAN Adapter                                               | 1        | 1.79%   |
| Ralink RT5370 Wireless Adapter                                              | 1        | 1.79%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                           | 1        | 1.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                   | 1        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1        | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1        | 1.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1        | 1.79%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                            | 1        | 1.79%   |
| Microsoft Xbox 360 Wireless Adapter                                         | 1        | 1.79%   |
| Intel Wireless 8265 / 8275                                                  | 1        | 1.79%   |
| Intel Wireless 7265                                                         | 1        | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 1        | 1.79%   |
| Intel Centrino Wireless-N 2230                                              | 1        | 1.79%   |
| Intel Centrino Wireless-N 105                                               | 1        | 1.79%   |
| Edimax AC600 USB                                                            | 1        | 1.79%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                  | 1        | 1.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1        | 1.79%   |
| Broadcom BCM43225 802.11b/g/n                                               | 1        | 1.79%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller         | 1        | 1.79%   |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU] | 1        | 1.79%   |
| AVM Fritz!WLAN N [Atheros AR9001U]                                          | 1        | 1.79%   |
| AVM FRITZ!WLAN AC 860                                                       | 1        | 1.79%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]         | 1        | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 74       | 53.24%  |
| Intel                            | 33       | 23.74%  |
| Qualcomm Atheros                 | 10       | 7.19%   |
| Nvidia                           | 8        | 5.76%   |
| VIA Technologies                 | 3        | 2.16%   |
| Marvell Technology Group         | 3        | 2.16%   |
| Broadcom                         | 3        | 2.16%   |
| Silicon Integrated Systems [SiS] | 1        | 0.72%   |
| JMicron Technology               | 1        | 0.72%   |
| Huawei Technologies              | 1        | 0.72%   |
| Broadcom Limited                 | 1        | 0.72%   |
| ADMtek                           | 1        | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60       | 41.67%  |
| Nvidia MCP61 Ethernet                                             | 6        | 4.17%   |
| Intel I211 Gigabit Network Connection                             | 6        | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 3.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.78%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3        | 2.08%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 2.08%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 2.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 1.39%   |
| Nvidia nForce2 Ethernet Controller                                | 2        | 1.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.39%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.39%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.39%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.39%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.39%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.39%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.39%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.39%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.69%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1        | 0.69%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.69%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.69%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.69%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.69%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.69%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.69%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.69%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.69%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.69%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 0.69%   |
| Intel 82544EI Gigabit Ethernet Controller (Copper)                | 1        | 0.69%   |
| Huawei DRA-L01                                                    | 1        | 0.69%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.69%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 0.69%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.69%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 0.69%   |
| ADMtek AN8515 Ethernet                                            | 1        | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 130      | 71.43%  |
| WiFi     | 50       | 27.47%  |
| Modem    | 1        | 0.55%   |
| Unknown  | 1        | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 127      | 76.51%  |
| WiFi     | 39       | 23.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 87       | 66.92%  |
| 2     | 39       | 30%     |
| 3     | 3        | 2.31%   |
| 4     | 1        | 0.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 113      | 83.7%   |
| Yes  | 22       | 16.3%   |

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
| Intel Bluetooth wireless interface                  | 2        | 7.41%   |
| Intel Bluetooth Device                              | 2        | 7.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 7.41%   |
| Realtek Bluetooth Radio                             | 1        | 3.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 3.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 3.7%    |
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
| Intel                            | 81       | 40.91%  |
| Nvidia                           | 49       | 24.75%  |
| AMD                              | 35       | 17.68%  |
| C-Media Electronics              | 9        | 4.55%   |
| VIA Technologies                 | 6        | 3.03%   |
| Creative Labs                    | 4        | 2.02%   |
| Silicon Integrated Systems [SiS] | 2        | 1.01%   |
| Logitech                         | 2        | 1.01%   |
| GN Netcom                        | 2        | 1.01%   |
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
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 17       | 7.66%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 12       | 5.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 9        | 4.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 8        | 3.6%    |
| Nvidia MCP61 High Definition Audio                                          | 6        | 2.7%    |
| Nvidia High Definition Audio Controller                                     | 6        | 2.7%    |
| Nvidia GP107GL High Definition Audio Controller                             | 6        | 2.7%    |
| Nvidia GM206 High Definition Audio Controller                               | 6        | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 6        | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                  | 6        | 2.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 6        | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 6        | 2.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 6        | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 6        | 2.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 6        | 2.7%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                               | 5        | 2.25%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                         | 5        | 2.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 4        | 1.8%    |
| AMD Starship/Matisse HD Audio Controller                                    | 4        | 1.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 4        | 1.8%    |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                   | 3        | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                               | 3        | 1.35%   |
| Nvidia GK104 HDMI Audio Controller                                          | 3        | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                               | 3        | 1.35%   |
| Intel 9 Series Chipset Family HD Audio Controller                           | 3        | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 3        | 1.35%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 3        | 1.35%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller             | 2        | 0.9%    |
| Nvidia nForce2 AC97 Audio Controler (MCP)                                   | 2        | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                               | 2        | 0.9%    |
| Nvidia GP104 High Definition Audio Controller                               | 2        | 0.9%    |
| Nvidia GF116 High Definition Audio Controller                               | 2        | 0.9%    |
| Nvidia GF104 High Definition Audio Controller                               | 2        | 0.9%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 2        | 0.9%    |
| Intel 200 Series PCH HD Audio                                               | 2        | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 2        | 0.9%    |
| AMD FCH Azalia Controller                                                   | 2        | 0.9%    |
| Xilinx RME Hammerfall DSP                                                   | 1        | 0.45%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller              | 1        | 0.45%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.45%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller          | 1        | 0.45%   |
| Nvidia MCP51 High Definition Audio                                          | 1        | 0.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 1        | 0.45%   |
| Nvidia GK107 HDMI Audio Controller                                          | 1        | 0.45%   |
| Nvidia GF114 HDMI Audio Controller                                          | 1        | 0.45%   |
| M-Audio M-Audio Fast Track                                                  | 1        | 0.45%   |
| Logitech QuickCam Fusion                                                    | 1        | 0.45%   |
| Logitech G430 Surround Sound Gaming Headset                                 | 1        | 0.45%   |
| JMTek USB PnP Audio Device                                                  | 1        | 0.45%   |
| Intel Haswell-ULT HD Audio Controller                                       | 1        | 0.45%   |
| Intel Comet Lake PCH cAVS                                                   | 1        | 0.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                | 1        | 0.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster           | 1        | 0.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                      | 1        | 0.45%   |
| Intel C610/X99 series chipset HD Audio Controller                           | 1        | 0.45%   |
| Intel C600/X79 series chipset High Definition Audio Controller              | 1        | 0.45%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller           | 1        | 0.45%   |
| Intel 8 Series HD Audio Controller                                          | 1        | 0.45%   |
| GYROCOM C&C Fiio E10                                                        | 1        | 0.45%   |
| GN Netcom Jabra UC Voice 750 MS                                             | 1        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 8        | 40%     |
| Crucial             | 3        | 15%     |
| Samsung Electronics | 2        | 10%     |
| Kingston            | 2        | 10%     |
| SK Hynix            | 1        | 5%      |
| PLEXHD              | 1        | 5%      |
| Micron Technology   | 1        | 5%      |
| G.Skill             | 1        | 5%      |
| Exceleram           | 1        | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 667MT/s                    | 1        | 4.55%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 1        | 4.55%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 4.55%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                 | 1        | 4.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 4.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 1        | 4.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s              | 1        | 4.55%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                   | 1        | 4.55%   |
| Unknown RAM Module 1024MB DIMM                           | 1        | 4.55%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 4.55%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s | 1        | 4.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 4.55%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s   | 1        | 4.55%   |
| PLEXHD RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 4.55%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s   | 1        | 4.55%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s           | 1        | 4.55%   |
| Kingston RAM KHX3600C17D4/16GX 16GB DIMM DDR4 3800MT/s   | 1        | 4.55%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s   | 1        | 4.55%   |
| Exceleram RAM E30144A 4096MB DIMM DDR3 800MT/s           | 1        | 4.55%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s  | 1        | 4.55%   |
| Crucial RAM BLT8G4D26BFT4K.C8FD 8GB DIMM DDR4 2666MT/s   | 1        | 4.55%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 1        | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 8        | 40%     |
| DDR4    | 5        | 25%     |
| DDR2    | 4        | 20%     |
| Unknown | 2        | 10%     |
| DDR     | 1        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 18       | 90%     |
| SODIMM | 2        | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 28.57%  |
| 2048  | 6        | 28.57%  |
| 4096  | 4        | 19.05%  |
| 16384 | 2        | 9.52%   |
| 1024  | 2        | 9.52%   |
| 512   | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6        | 30%     |
| 800     | 3        | 15%     |
| 1333    | 2        | 10%     |
| 667     | 2        | 10%     |
| 3800    | 1        | 5%      |
| 3500    | 1        | 5%      |
| 3200    | 1        | 5%      |
| 2666    | 1        | 5%      |
| 2400    | 1        | 5%      |
| 400     | 1        | 5%      |
| Unknown | 1        | 5%      |

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
| Logitech                      | 6        | 35.29%  |
| Microsoft                     | 3        | 17.65%  |
| Xiongmai                      | 1        | 5.88%   |
| Sunplus Innovation Technology | 1        | 5.88%   |
| Service & Quality Technology  | 1        | 5.88%   |
| Nintendo                      | 1        | 5.88%   |
| Microdia                      | 1        | 5.88%   |
| KYE Systems (Mouse Systems)   | 1        | 5.88%   |
| Generalplus Technology        | 1        | 5.88%   |
| Chicony Electronics           | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Logitech Webcam C270                               | 3        | 17.65%  |
| Microsoft LifeCam HD-3000                          | 2        | 11.76%  |
| Xiongmai web camera                                | 1        | 5.88%   |
| Sunplus PAPALOOK_229AF                             | 1        | 5.88%   |
| Service & Quality USB PC Camera                    | 1        | 5.88%   |
| Nintendo USB Camera                                | 1        | 5.88%   |
| Microsoft Microsoft?� LifeCam VX-5500              | 1        | 5.88%   |
| Microdia Webcam Vitade AF                          | 1        | 5.88%   |
| Logitech Webcam Pro 9000                           | 1        | 5.88%   |
| Logitech Webcam C310                               | 1        | 5.88%   |
| Logitech HD Pro Webcam C920                        | 1        | 5.88%   |
| KYE Systems (Mouse Systems) Genius iSlim 2000AF V2 | 1        | 5.88%   |
| Generalplus 808 Camera                             | 1        | 5.88%   |
| Chicony HP High Definition 1MP Webcam              | 1        | 5.88%   |

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
| 0     | 93       | 70.99%  |
| 1     | 32       | 24.43%  |
| 2     | 3        | 2.29%   |
| 4     | 2        | 1.53%   |
| 3     | 1        | 0.76%   |

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

