LMDE 4 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for LMDE 4.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 228

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | G41M-S3                     | [2cdcaebd43](https://linux-hardware.org/?probe=2cdcaebd43) | Sep 10, 2022 |
| ASUSTek       | P5B                         | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
| ASUSTek       | P5QL PRO                    | [9ea782b1d2](https://linux-hardware.org/?probe=9ea782b1d2) | May 08, 2022 |
| Dell          | 0XR1GT A00                  | [2a3b9ad6cf](https://linux-hardware.org/?probe=2a3b9ad6cf) | Apr 24, 2022 |
| Foxconn       | Cinema Series FAB           | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [eb751efc1f](https://linux-hardware.org/?probe=eb751efc1f) | Apr 09, 2022 |
| Acer          | EG43M                       | [28b4dd5236](https://linux-hardware.org/?probe=28b4dd5236) | Mar 31, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [346857be22](https://linux-hardware.org/?probe=346857be22) | Mar 24, 2022 |
| ASUSTek       | P4P800                      | [0cb6a89491](https://linux-hardware.org/?probe=0cb6a89491) | Mar 19, 2022 |
| HP            | 0AA8h                       | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| Dell          | 0HR330                      | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell          | 0HR330                      | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| HP            | 0AA8h                       | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| Gigabyte      | Z77-D3H                     | [a0d52488b2](https://linux-hardware.org/?probe=a0d52488b2) | Feb 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [0731118682](https://linux-hardware.org/?probe=0731118682) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [5026ea812a](https://linux-hardware.org/?probe=5026ea812a) | Feb 15, 2022 |
| EVGA          | 131-HE-E095                 | [6d45d47131](https://linux-hardware.org/?probe=6d45d47131) | Jan 31, 2022 |
| ASUSTek       | A68HM-K                     | [00cd805015](https://linux-hardware.org/?probe=00cd805015) | Jan 23, 2022 |
| MSI           | Z97 PC Mate                 | [be068c5a3a](https://linux-hardware.org/?probe=be068c5a3a) | Jan 21, 2022 |
| Dell          | 0XR1GT A00                  | [a988797ac9](https://linux-hardware.org/?probe=a988797ac9) | Jan 16, 2022 |
| eMachines     | EMCP73VT-PM                 | [1d55cceee4](https://linux-hardware.org/?probe=1d55cceee4) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | [43b421ad06](https://linux-hardware.org/?probe=43b421ad06) | Jan 08, 2022 |
| ASRock        | N68-S3 UCC                  | [bfcf287c09](https://linux-hardware.org/?probe=bfcf287c09) | Jan 08, 2022 |
| OEM           | Unknown                     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| Unknown       | K7VM2                       | [06f13210ad](https://linux-hardware.org/?probe=06f13210ad) | Dec 29, 2021 |
| Unknown       | K7VM2                       | [be785b672c](https://linux-hardware.org/?probe=be785b672c) | Dec 29, 2021 |
| HP            | 2AE3                        | [fb02077f16](https://linux-hardware.org/?probe=fb02077f16) | Dec 14, 2021 |
| HP            | 2AE3                        | [18efa559b9](https://linux-hardware.org/?probe=18efa559b9) | Dec 14, 2021 |
| ECS           | G41T-M7                     | [5a8641a9aa](https://linux-hardware.org/?probe=5a8641a9aa) | Dec 13, 2021 |
| Acer          | RS880M05                    | [2ce9c25975](https://linux-hardware.org/?probe=2ce9c25975) | Nov 25, 2021 |
| NEC Comput... | GA-8I945PM                  | [3d3711b8cc](https://linux-hardware.org/?probe=3d3711b8cc) | Nov 22, 2021 |
| ASUSTek       | A68HM-K                     | [b4b709eb1b](https://linux-hardware.org/?probe=b4b709eb1b) | Nov 18, 2021 |
| ASUSTek       | A68HM-K                     | [18236d5a16](https://linux-hardware.org/?probe=18236d5a16) | Nov 18, 2021 |
| Intel         | H61                         | [51f383b050](https://linux-hardware.org/?probe=51f383b050) | Nov 04, 2021 |
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
| ASUSTek       | P5VD2-VM                    | [305d566f57](https://linux-hardware.org/?probe=305d566f57) | Sep 07, 2021 |
| Gigabyte      | H61M-S1                     | [d1773b3e3d](https://linux-hardware.org/?probe=d1773b3e3d) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | [5d2cc7f4ca](https://linux-hardware.org/?probe=5d2cc7f4ca) | Sep 06, 2021 |
| Intel         | DG31PR AAD97573-302         | [7122e4bd16](https://linux-hardware.org/?probe=7122e4bd16) | Sep 04, 2021 |
| Gigabyte      | M52LT-D3P                   | [09cbb5b50e](https://linux-hardware.org/?probe=09cbb5b50e) | Sep 03, 2021 |
| Gigabyte      | M52LT-D3P                   | [949b2062ea](https://linux-hardware.org/?probe=949b2062ea) | Sep 03, 2021 |
| ASRock        | G41M-S3                     | [c34caa75e2](https://linux-hardware.org/?probe=c34caa75e2) | Aug 23, 2021 |
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
| Dell          | 08HPGT A01                  | [64d562d6ef](https://linux-hardware.org/?probe=64d562d6ef) | Jul 16, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| ASUSTek       | P7F-M                       | [3007b813c6](https://linux-hardware.org/?probe=3007b813c6) | Jul 13, 2021 |
| ASUSTek       | P7F-M                       | [5cfa1dcb4f](https://linux-hardware.org/?probe=5cfa1dcb4f) | Jul 12, 2021 |
| MSI           | H81M-E34                    | [14c2f8a49d](https://linux-hardware.org/?probe=14c2f8a49d) | Jul 05, 2021 |
| MSI           | A320M-A PRO                 | [9d356e787a](https://linux-hardware.org/?probe=9d356e787a) | Jul 01, 2021 |
| HP            | 0A98h                       | [40990f73a5](https://linux-hardware.org/?probe=40990f73a5) | Jun 22, 2021 |
| HP            | 0AA8h                       | [43103b39a5](https://linux-hardware.org/?probe=43103b39a5) | Jun 17, 2021 |
| HP            | 0AA8h                       | [9154911bc9](https://linux-hardware.org/?probe=9154911bc9) | Jun 13, 2021 |
| ASUSTek       | Maximus VI HERO             | [699d10613e](https://linux-hardware.org/?probe=699d10613e) | Jun 11, 2021 |
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
| Foxconn       | 945 7MC Series              | [f4634ec470](https://linux-hardware.org/?probe=f4634ec470) | May 17, 2021 |
| Dell          | 0FM586 A00                  | [8a955d2c5a](https://linux-hardware.org/?probe=8a955d2c5a) | May 16, 2021 |
| ASUSTek       | B150M-A                     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| Dell          | 0XR1GT A00                  | [a502e8842e](https://linux-hardware.org/?probe=a502e8842e) | May 12, 2021 |
| ASUSTek       | V-P7H55E                    | [3c0a297ede](https://linux-hardware.org/?probe=3c0a297ede) | May 08, 2021 |
| ASUSTek       | Crosshair V Formula         | [0fd87c485e](https://linux-hardware.org/?probe=0fd87c485e) | May 07, 2021 |
| ASUSTek       | P5KC                        | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASUSTek       | P5KC                        | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
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
| Intel         | H61                         | [d7c3f87e52](https://linux-hardware.org/?probe=d7c3f87e52) | Mar 26, 2021 |
| Gigabyte      | Z77-D3H                     | [6ab1c423db](https://linux-hardware.org/?probe=6ab1c423db) | Mar 25, 2021 |
| MSI           | Z77A-GD65                   | [a9c3672597](https://linux-hardware.org/?probe=a9c3672597) | Mar 25, 2021 |
| ASUSTek       | M5A97 PRO                   | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| MSI           | MS-6785                     | [303c1ac636](https://linux-hardware.org/?probe=303c1ac636) | Mar 17, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | [f8503ecc3b](https://linux-hardware.org/?probe=f8503ecc3b) | Mar 10, 2021 |
| ECS           | A740GM-M                    | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| ASUSTek       | P7F-M                       | [a8d2e4fa56](https://linux-hardware.org/?probe=a8d2e4fa56) | Mar 07, 2021 |
| MSI           | B450M PRO-VDH MAX           | [79e6e8bbfc](https://linux-hardware.org/?probe=79e6e8bbfc) | Mar 06, 2021 |
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
| Gigabyte      | G33M-S2                     | [d5b1adf1cc](https://linux-hardware.org/?probe=d5b1adf1cc) | Oct 21, 2020 |
| MSI           | Z97 GAMING 3                | [d70dc5679f](https://linux-hardware.org/?probe=d70dc5679f) | Oct 15, 2020 |
| ASUSTek       | P7F-M                       | [a931f70b33](https://linux-hardware.org/?probe=a931f70b33) | Oct 14, 2020 |
| HP            | 304Ah                       | [720e05d59c](https://linux-hardware.org/?probe=720e05d59c) | Oct 04, 2020 |
| HP            | 304Ah                       | [e8bf5f6700](https://linux-hardware.org/?probe=e8bf5f6700) | Oct 04, 2020 |
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
| PCWare        | IPMH81G1                    | [416c3e2997](https://linux-hardware.org/?probe=416c3e2997) | Jun 07, 2020 |
| Dell          | 0200DY A03                  | [aebb17da40](https://linux-hardware.org/?probe=aebb17da40) | Jun 01, 2020 |
| Dell          | 0DR845                      | [4b8a511c08](https://linux-hardware.org/?probe=4b8a511c08) | May 29, 2020 |
| Dell          | 042P49 A00                  | [aca1fb8ea1](https://linux-hardware.org/?probe=aca1fb8ea1) | May 21, 2020 |
| Dell          | 042P49 A00                  | [8e547a1414](https://linux-hardware.org/?probe=8e547a1414) | May 20, 2020 |
| ASRock        | EP2C602-4L/D16              | [cf5fe3dbce](https://linux-hardware.org/?probe=cf5fe3dbce) | May 17, 2020 |
| ASRock        | B75M R2.0                   | [efd3354b61](https://linux-hardware.org/?probe=efd3354b61) | May 10, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | [1a79fa9925](https://linux-hardware.org/?probe=1a79fa9925) | May 03, 2020 |
| ASRock        | J4205-ITX                   | [4fc5d5a325](https://linux-hardware.org/?probe=4fc5d5a325) | Apr 22, 2020 |
| ECS           | Nettle2                     | [ababaf523c](https://linux-hardware.org/?probe=ababaf523c) | Apr 19, 2020 |
| ASUSTek       | A88XM-A                     | [12c198a6f5](https://linux-hardware.org/?probe=12c198a6f5) | Apr 18, 2020 |
| ASUSTek       | A88XM-A                     | [0d1b40e847](https://linux-hardware.org/?probe=0d1b40e847) | Apr 14, 2020 |
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
| 4.19.0-16-amd64     | 23       | 13.77%  |
| 4.19.0-17-amd64     | 20       | 11.98%  |
| 4.19.0-18-amd64     | 19       | 11.38%  |
| 4.19.0-14-amd64     | 18       | 10.78%  |
| 4.19.0-13-amd64     | 17       | 10.18%  |
| 4.19.0-8-amd64      | 15       | 8.98%   |
| 4.19.0-12-amd64     | 9        | 5.39%   |
| 4.19.0-10-amd64     | 8        | 4.79%   |
| 4.19.0-9-amd64      | 7        | 4.19%   |
| 4.19.0-11-amd64     | 4        | 2.4%    |
| 4.19.0-17-686       | 3        | 1.8%    |
| 4.19.0-16-686       | 3        | 1.8%    |
| 4.19.0-14-686       | 3        | 1.8%    |
| 4.19.0-8-686        | 2        | 1.2%    |
| 4.19.0-20-amd64     | 2        | 1.2%    |
| 4.19.0-19-686       | 2        | 1.2%    |
| 4.19.0-18-686       | 2        | 1.2%    |
| 4.19.0-13-686       | 2        | 1.2%    |
| 5.8.0-3-amd64       | 1        | 0.6%    |
| 5.6.0-0.bpo.2-amd64 | 1        | 0.6%    |
| 5.4.0-0.bpo.4-amd64 | 1        | 0.6%    |
| 5.10.0-7-amd64      | 1        | 0.6%    |
| 4.19.0-9-686        | 1        | 0.6%    |
| 4.19.0-21-amd64     | 1        | 0.6%    |
| 4.19.0-19-amd64     | 1        | 0.6%    |
| 4.19.0-12-686       | 1        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 144      | 97.3%   |
| 5.8.0   | 1        | 0.68%   |
| 5.6.0   | 1        | 0.68%   |
| 5.4.0   | 1        | 0.68%   |
| 5.10.0  | 1        | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 144      | 97.3%   |
| 5.8     | 1        | 0.68%   |
| 5.6     | 1        | 0.68%   |
| 5.4     | 1        | 0.68%   |
| 5.10    | 1        | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 129      | 87.16%  |
| i686   | 19       | 12.84%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 133      | 89.26%  |
| Cinnamon   | 7        | 4.7%    |
| Unknown    | 3        | 2.01%   |
| MATE       | 2        | 1.34%   |
| XFCE       | 1        | 0.67%   |
| LXQt       | 1        | 0.67%   |
| LXDE       | 1        | 0.67%   |
| GNOME      | 1        | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 148      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 134      | 90.54%  |
| TDM     | 8        | 5.41%   |
| LightDM | 5        | 3.38%   |
| GDM     | 1        | 0.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Desktops | Percent |
|--------|----------|---------|
| en_US  | 38       | 25.68%  |
| de_DE  | 18       | 12.16%  |
| pt_BR  | 15       | 10.14%  |
| fr_FR  | 12       | 8.11%   |
| pl_PL  | 7        | 4.73%   |
| en_GB  | 7        | 4.73%   |
| ru_RU  | 5        | 3.38%   |
| en_CA  | 4        | 2.7%    |
| sv_SE  | 3        | 2.03%   |
| nl_BE  | 3        | 2.03%   |
| it_IT  | 3        | 2.03%   |
| es_AR  | 3        | 2.03%   |
| en_AU  | 3        | 2.03%   |
| pt_PT  | 2        | 1.35%   |
| hu_HU  | 2        | 1.35%   |
| es_ES  | 2        | 1.35%   |
| cs_CZ  | 2        | 1.35%   |
| unm_US | 1        | 0.68%   |
| uk_UA  | 1        | 0.68%   |
| tr_TR  | 1        | 0.68%   |
| sk_SK  | 1        | 0.68%   |
| nb_NO  | 1        | 0.68%   |
| fr_CA  | 1        | 0.68%   |
| fi_FI  | 1        | 0.68%   |
| et_EE  | 1        | 0.68%   |
| es_UY  | 1        | 0.68%   |
| es_MX  | 1        | 0.68%   |
| es_EC  | 1        | 0.68%   |
| es_CO  | 1        | 0.68%   |
| es_CL  | 1        | 0.68%   |
| en_ZA  | 1        | 0.68%   |
| el_GR  | 1        | 0.68%   |
| de_AT  | 1        | 0.68%   |
| ca_ES  | 1        | 0.68%   |
| bg_BG  | 1        | 0.68%   |
| ar_EG  | 1        | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 107      | 72.3%   |
| EFI  | 41       | 27.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 142      | 95.3%   |
| Btrfs   | 4        | 2.68%   |
| Unknown | 2        | 1.34%   |
| Ext3    | 1        | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 133      | 88.67%  |
| GPT     | 12       | 8%      |
| MBR     | 5        | 3.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 143      | 95.33%  |
| Yes       | 7        | 4.67%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 141      | 95.27%  |
| Yes       | 7        | 4.73%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 34       | 22.97%  |
| Gigabyte Technology | 21       | 14.19%  |
| MSI                 | 18       | 12.16%  |
| Dell                | 14       | 9.46%   |
| ASRock              | 12       | 8.11%   |
| Hewlett-Packard     | 10       | 6.76%   |
| Intel               | 5        | 3.38%   |
| Acer                | 5        | 3.38%   |
| Unknown             | 5        | 3.38%   |
| ECS                 | 4        | 2.7%    |
| Pegatron            | 2        | 1.35%   |
| OEM                 | 2        | 1.35%   |
| Lenovo              | 2        | 1.35%   |
| Foxconn             | 2        | 1.35%   |
| EVGA                | 2        | 1.35%   |
| Biostar             | 2        | 1.35%   |
| Semp Toshiba        | 1        | 0.68%   |
| Positivo            | 1        | 0.68%   |
| PCWare              | 1        | 0.68%   |
| NEC Computers       | 1        | 0.68%   |
| Fujitsu Siemens     | 1        | 0.68%   |
| eMachines           | 1        | 0.68%   |
| DFI                 | 1        | 0.68%   |
| Alienware           | 1        | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 6        | 4.05%   |
| Dell OptiPlex 780                   | 2        | 1.35%   |
| ASUS All Series                     | 2        | 1.35%   |
| Semp Toshiba STI                    | 1        | 0.68%   |
| Positivo POS-EIH61CE                | 1        | 0.68%   |
| Pegatron Elite 7300 Series MT       | 1        | 0.68%   |
| Pegatron 520-1188la                 | 1        | 0.68%   |
| PCWare IPMH81G1                     | 1        | 0.68%   |
| OEM 45CMX/45GMX/45CMX-K             | 1        | 0.68%   |
| NEC Computers IMEDIA S9509          | 1        | 0.68%   |
| MSI PX714AA-ABH t3040.nl            | 1        | 0.68%   |
| MSI MS-7C52                         | 1        | 0.68%   |
| MSI MS-7C51                         | 1        | 0.68%   |
| MSI MS-7A40                         | 1        | 0.68%   |
| MSI MS-7A38                         | 1        | 0.68%   |
| MSI MS-7918                         | 1        | 0.68%   |
| MSI MS-7850                         | 1        | 0.68%   |
| MSI MS-7823                         | 1        | 0.68%   |
| MSI MS-7817                         | 1        | 0.68%   |
| MSI MS-7815                         | 1        | 0.68%   |
| MSI MS-7751                         | 1        | 0.68%   |
| MSI MS-7383                         | 1        | 0.68%   |
| MSI MS-7267                         | 1        | 0.68%   |
| MSI MS-7142                         | 1        | 0.68%   |
| MSI MS-6785                         | 1        | 0.68%   |
| MSI MS-6570                         | 1        | 0.68%   |
| MSI ESPRIMO P2440                   | 1        | 0.68%   |
| MSI *MF                             | 1        | 0.68%   |
| Lenovo ThinkStation P510 30B5005CUS | 1        | 0.68%   |
| Lenovo ThinkCentre M93p 10AB0010US  | 1        | 0.68%   |
| Intel H61                           | 1        | 0.68%   |
| Intel DP55WB AAE64798-206           | 1        | 0.68%   |
| Intel DG33FB AAD81072-309           | 1        | 0.68%   |
| Intel DG31PR AAD97573-302           | 1        | 0.68%   |
| Intel BTC-T37                       | 1        | 0.68%   |
| HP xw8600 Workstation               | 1        | 0.68%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 0.68%   |
| HP Desktop 190-0xxx                 | 1        | 0.68%   |
| HP CQ2930EA                         | 1        | 0.68%   |
| HP Compaq Elite 8300 CMT            | 1        | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 9        | 6.08%   |
| Unknown              | 6        | 4.05%   |
| HP Compaq            | 5        | 3.38%   |
| ASUS PRIME           | 4        | 2.7%    |
| Gigabyte X570        | 3        | 2.03%   |
| Dell Inspiron        | 3        | 2.03%   |
| Acer Aspire          | 3        | 2.03%   |
| Gigabyte Z390        | 2        | 1.35%   |
| Dell Precision       | 2        | 1.35%   |
| ASUS ROG             | 2        | 1.35%   |
| ASUS P5KPL-AM        | 2        | 1.35%   |
| ASUS All             | 2        | 1.35%   |
| Acer Veriton         | 2        | 1.35%   |
| Semp Toshiba STI     | 1        | 0.68%   |
| Positivo POS-EIH61CE | 1        | 0.68%   |
| Pegatron Elite       | 1        | 0.68%   |
| Pegatron 520-1188la  | 1        | 0.68%   |
| PCWare IPMH81G1      | 1        | 0.68%   |
| OEM 45CMX            | 1        | 0.68%   |
| NEC Computers IMEDIA | 1        | 0.68%   |
| MSI PX714AA-ABH      | 1        | 0.68%   |
| MSI MS-7C52          | 1        | 0.68%   |
| MSI MS-7C51          | 1        | 0.68%   |
| MSI MS-7A40          | 1        | 0.68%   |
| MSI MS-7A38          | 1        | 0.68%   |
| MSI MS-7918          | 1        | 0.68%   |
| MSI MS-7850          | 1        | 0.68%   |
| MSI MS-7823          | 1        | 0.68%   |
| MSI MS-7817          | 1        | 0.68%   |
| MSI MS-7815          | 1        | 0.68%   |
| MSI MS-7751          | 1        | 0.68%   |
| MSI MS-7383          | 1        | 0.68%   |
| MSI MS-7267          | 1        | 0.68%   |
| MSI MS-7142          | 1        | 0.68%   |
| MSI MS-6785          | 1        | 0.68%   |
| MSI MS-6570          | 1        | 0.68%   |
| MSI ESPRIMO          | 1        | 0.68%   |
| MSI *MF              | 1        | 0.68%   |
| Lenovo ThinkStation  | 1        | 0.68%   |
| Lenovo ThinkCentre   | 1        | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 19       | 12.84%  |
| 2009 | 16       | 10.81%  |
| 2014 | 13       | 8.78%   |
| 2007 | 13       | 8.78%   |
| 2019 | 11       | 7.43%   |
| 2010 | 11       | 7.43%   |
| 2008 | 11       | 7.43%   |
| 2011 | 10       | 6.76%   |
| 2018 | 9        | 6.08%   |
| 2013 | 6        | 4.05%   |
| 2006 | 6        | 4.05%   |
| 2017 | 5        | 3.38%   |
| 2020 | 4        | 2.7%    |
| 2003 | 4        | 2.7%    |
| 2005 | 3        | 2.03%   |
| 2021 | 2        | 1.35%   |
| 2016 | 2        | 1.35%   |
| 2015 | 2        | 1.35%   |
| 2004 | 1        | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 148      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 147      | 98.66%  |
| Enabled  | 2        | 1.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 148      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 39       | 25.83%  |
| 3.01-4.0    | 35       | 23.18%  |
| 16.01-24.0  | 25       | 16.56%  |
| 4.01-8.0    | 19       | 12.58%  |
| 32.01-64.0  | 11       | 7.28%   |
| 2.01-3.0    | 11       | 7.28%   |
| 1.01-2.0    | 6        | 3.97%   |
| 0.51-1.0    | 4        | 2.65%   |
| 64.01-256.0 | 1        | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 75       | 47.47%  |
| 2.01-3.0 | 32       | 20.25%  |
| 3.01-4.0 | 21       | 13.29%  |
| 0.51-1.0 | 20       | 12.66%  |
| 4.01-8.0 | 10       | 6.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 73       | 47.4%   |
| 2      | 47       | 30.52%  |
| 3      | 16       | 10.39%  |
| 4      | 10       | 6.49%   |
| 7      | 4        | 2.6%    |
| 5      | 2        | 1.3%    |
| 8      | 1        | 0.65%   |
| 6      | 1        | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 90       | 59.21%  |
| No        | 62       | 40.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 148      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 95       | 62.09%  |
| Yes       | 58       | 37.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 81.21%  |
| Yes       | 28       | 18.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 21       | 14.19%  |
| USA          | 18       | 12.16%  |
| Brazil       | 15       | 10.14%  |
| France       | 11       | 7.43%   |
| Canada       | 7        | 4.73%   |
| UK           | 5        | 3.38%   |
| Poland       | 5        | 3.38%   |
| Netherlands  | 5        | 3.38%   |
| Spain        | 4        | 2.7%    |
| Russia       | 4        | 2.7%    |
| Ukraine      | 3        | 2.03%   |
| Italy        | 3        | 2.03%   |
| Bulgaria     | 3        | 2.03%   |
| Belgium      | 3        | 2.03%   |
| Argentina    | 3        | 2.03%   |
| Sweden       | 2        | 1.35%   |
| Puerto Rico  | 2        | 1.35%   |
| Portugal     | 2        | 1.35%   |
| Hungary      | 2        | 1.35%   |
| Greece       | 2        | 1.35%   |
| Finland      | 2        | 1.35%   |
| Czechia      | 2        | 1.35%   |
| Austria      | 2        | 1.35%   |
| Australia    | 2        | 1.35%   |
| Uruguay      | 1        | 0.68%   |
| Turkey       | 1        | 0.68%   |
| South Africa | 1        | 0.68%   |
| Slovakia     | 1        | 0.68%   |
| Serbia       | 1        | 0.68%   |
| Romania      | 1        | 0.68%   |
| Philippines  | 1        | 0.68%   |
| Pakistan     | 1        | 0.68%   |
| Norway       | 1        | 0.68%   |
| Mexico       | 1        | 0.68%   |
| Luxembourg   | 1        | 0.68%   |
| India        | 1        | 0.68%   |
| Estonia      | 1        | 0.68%   |
| Egypt        | 1        | 0.68%   |
| Ecuador      | 1        | 0.68%   |
| Croatia      | 1        | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Paris          | 3        | 1.88%   |
| Hamburg        | 3        | 1.88%   |
| Warsaw         | 2        | 1.25%   |
| Sofia          | 2        | 1.25%   |
| Rio de Janeiro | 2        | 1.25%   |
| Perth          | 2        | 1.25%   |
| Helsinki       | 2        | 1.25%   |
| Florianópolis | 2        | 1.25%   |
| Belo Horizonte | 2        | 1.25%   |
| Bayamón       | 2        | 1.25%   |
| Athens         | 2        | 1.25%   |
| Amsterdam      | 2        | 1.25%   |
| Zaporozhe      | 1        | 0.63%   |
| Zaandam        | 1        | 0.63%   |
| Wroclaw        | 1        | 0.63%   |
| Wijchen        | 1        | 0.63%   |
| Weiden         | 1        | 0.63%   |
| Warmsen        | 1        | 0.63%   |
| Voronezh       | 1        | 0.63%   |
| Vienna         | 1        | 0.63%   |
| Victoria       | 1        | 0.63%   |
| Valencia       | 1        | 0.63%   |
| Ukhta          | 1        | 0.63%   |
| Trindade       | 1        | 0.63%   |
| Toronto        | 1        | 0.63%   |
| Timișoara     | 1        | 0.63%   |
| Thornton       | 1        | 0.63%   |
| Theodore       | 1        | 0.63%   |
| The Hague      | 1        | 0.63%   |
| Tepic          | 1        | 0.63%   |
| Telc           | 1        | 0.63%   |
| Stockholm      | 1        | 0.63%   |
| Stendal        | 1        | 0.63%   |
| Springdale     | 1        | 0.63%   |
| Sonneberg      | 1        | 0.63%   |
| Simferopol     | 1        | 0.63%   |
| Shimla         | 1        | 0.63%   |
| Sherbrooke     | 1        | 0.63%   |
| Scotby         | 1        | 0.63%   |
| Sao Luís      | 1        | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 58       | 98     | 24.07%  |
| Seagate             | 40       | 69     | 16.6%   |
| Samsung Electronics | 38       | 57     | 15.77%  |
| Kingston            | 14       | 17     | 5.81%   |
| Toshiba             | 12       | 18     | 4.98%   |
| Hitachi             | 12       | 15     | 4.98%   |
| SanDisk             | 9        | 12     | 3.73%   |
| Crucial             | 9        | 12     | 3.73%   |
| Phison              | 6        | 7      | 2.49%   |
| A-DATA Technology   | 6        | 6      | 2.49%   |
| Intel               | 4        | 4      | 1.66%   |
| OCZ                 | 3        | 5      | 1.24%   |
| Maxtor              | 3        | 5      | 1.24%   |
| Intenso             | 3        | 4      | 1.24%   |
| China               | 3        | 3      | 1.24%   |
| TCSUNBOW            | 2        | 2      | 0.83%   |
| Micron Technology   | 2        | 2      | 0.83%   |
| CT500MX5            | 2        | 2      | 0.83%   |
| Unknown             | 1        | 2      | 0.41%   |
| Transcend           | 1        | 1      | 0.41%   |
| Team                | 1        | 2      | 0.41%   |
| Silicon Motion      | 1        | 1      | 0.41%   |
| SABRENT             | 1        | 1      | 0.41%   |
| Patriot             | 1        | 1      | 0.41%   |
| Mushkin             | 1        | 1      | 0.41%   |
| KingSpec            | 1        | 1      | 0.41%   |
| Kingmax             | 1        | 1      | 0.41%   |
| KESU                | 1        | 2      | 0.41%   |
| HPE                 | 1        | 4      | 0.41%   |
| Gigabyte Technology | 1        | 1      | 0.41%   |
| Fujitsu             | 1        | 1      | 0.41%   |
| ExcelStor           | 1        | 1      | 0.41%   |
| Dogfish             | 1        | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                 | 4        | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB         | 4        | 1.41%   |
| Samsung SSD 860 EVO 500GB              | 3        | 1.06%   |
| Samsung SSD 850 EVO 250GB              | 3        | 1.06%   |
| Samsung HD322HJ 320GB                  | 3        | 1.06%   |
| Samsung HD161HJ 160GB                  | 3        | 1.06%   |
| Samsung HD103SJ 1TB                    | 3        | 1.06%   |
| Kingston SA400S37480G 480GB SSD        | 3        | 1.06%   |
| Kingston SA400S37120G 120GB SSD        | 3        | 1.06%   |
| Crucial CT240BX500SSD1 240GB           | 3        | 1.06%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 2        | 0.71%   |
| WDC WD5000AAKX-00U6AA0 500GB           | 2        | 0.71%   |
| WDC WD40EFRX-68N32N0 4TB               | 2        | 0.71%   |
| WDC WD3200AAKS-00L9A0 320GB            | 2        | 0.71%   |
| WDC WD2500AAKX-753CA1 250GB            | 2        | 0.71%   |
| WDC WD1600AABS-00PRA0 160GB            | 2        | 0.71%   |
| WDC WD10EZEX-60WN4A0 1TB               | 2        | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2        | 0.71%   |
| Toshiba HDWD110 1TB                    | 2        | 0.71%   |
| Seagate ST500DM002-1BD142 500GB        | 2        | 0.71%   |
| Seagate ST2000LX001-1RG174 2TB         | 2        | 0.71%   |
| Seagate ST2000DM001-9YN164 2TB         | 2        | 0.71%   |
| Seagate ST2000DM001-1ER164 2TB         | 2        | 0.71%   |
| Seagate Expansion 4TB                  | 2        | 0.71%   |
| Samsung SSD 850 EVO 500GB              | 2        | 0.71%   |
| Samsung SP0802N 80GB                   | 2        | 0.71%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2        | 0.71%   |
| Samsung NVMe SSD Drive 2TB             | 2        | 0.71%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD    | 2        | 0.71%   |
| Kingston SV300S37A120G 120GB SSD       | 2        | 0.71%   |
| Kingston SA400S37240G 240GB SSD        | 2        | 0.71%   |
| CT500MX5 00SSD1 500GB                  | 2        | 0.71%   |
| Crucial CT500MX500SSD1 500GB           | 2        | 0.71%   |
| A-DATA SU650 240GB SSD                 | 2        | 0.71%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 1        | 0.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1        | 0.35%   |
| WDC WDS120G1G0A-00SS50 120GB SSD       | 1        | 0.35%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 1        | 0.35%   |
| WDC WDBNCE2500PNC 250GB SSD            | 1        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 51       | 89     | 35.92%  |
| Seagate             | 40       | 69     | 28.17%  |
| Samsung Electronics | 22       | 30     | 15.49%  |
| Hitachi             | 12       | 15     | 8.45%   |
| Toshiba             | 9        | 11     | 6.34%   |
| Maxtor              | 3        | 5      | 2.11%   |
| Unknown             | 1        | 1      | 0.7%    |
| KESU                | 1        | 2      | 0.7%    |
| HPE                 | 1        | 4      | 0.7%    |
| Fujitsu             | 1        | 1      | 0.7%    |
| ExcelStor           | 1        | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 17     | 14.94%  |
| Kingston            | 13       | 16     | 14.94%  |
| SanDisk             | 9        | 12     | 10.34%  |
| Crucial             | 9        | 12     | 10.34%  |
| WDC                 | 8        | 8      | 9.2%    |
| A-DATA Technology   | 6        | 6      | 6.9%    |
| Toshiba             | 3        | 7      | 3.45%   |
| OCZ                 | 3        | 5      | 3.45%   |
| Intenso             | 3        | 4      | 3.45%   |
| Intel               | 3        | 3      | 3.45%   |
| China               | 3        | 3      | 3.45%   |
| TCSUNBOW            | 2        | 2      | 2.3%    |
| Micron Technology   | 2        | 2      | 2.3%    |
| CT500MX5            | 2        | 2      | 2.3%    |
| Unknown             | 1        | 1      | 1.15%   |
| Transcend           | 1        | 1      | 1.15%   |
| Team                | 1        | 2      | 1.15%   |
| Patriot             | 1        | 1      | 1.15%   |
| KingSpec            | 1        | 1      | 1.15%   |
| Kingmax             | 1        | 1      | 1.15%   |
| Gigabyte Technology | 1        | 1      | 1.15%   |
| Dogfish             | 1        | 1      | 1.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 112      | 228    | 56.57%  |
| SSD  | 70       | 108    | 35.35%  |
| NVMe | 16       | 23     | 8.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 141      | 319    | 84.94%  |
| NVMe | 15       | 22     | 9.04%   |
| SAS  | 10       | 18     | 6.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 121      | 231    | 62.05%  |
| 0.51-1.0   | 46       | 65     | 23.59%  |
| 1.01-2.0   | 18       | 26     | 9.23%   |
| 3.01-4.0   | 6        | 10     | 3.08%   |
| 2.01-3.0   | 2        | 2      | 1.03%   |
| 4.01-10.0  | 2        | 2      | 1.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 51       | 33.12%  |
| 251-500        | 32       | 20.78%  |
| 1001-2000      | 20       | 12.99%  |
| More than 3000 | 14       | 9.09%   |
| 501-1000       | 12       | 7.79%   |
| 51-100         | 9        | 5.84%   |
| 21-50          | 8        | 5.19%   |
| 2001-3000      | 8        | 5.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 52       | 32.3%   |
| 21-50          | 37       | 22.98%  |
| 51-100         | 20       | 12.42%  |
| 251-500        | 13       | 8.07%   |
| 101-250        | 12       | 7.45%   |
| 1001-2000      | 10       | 6.21%   |
| 501-1000       | 9        | 5.59%   |
| More than 3000 | 4        | 2.48%   |
| 2001-3000      | 4        | 2.48%   |

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
| Detected | 134      | 316    | 86.45%  |
| Works    | 19       | 41     | 12.26%  |
| Malfunc  | 2        | 2      | 1.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 100      | 51.81%  |
| AMD                              | 31       | 16.06%  |
| Nvidia                           | 11       | 5.7%    |
| JMicron Technology               | 9        | 4.66%   |
| ASMedia Technology               | 9        | 4.66%   |
| Samsung Electronics              | 7        | 3.63%   |
| VIA Technologies                 | 6        | 3.11%   |
| Phison Electronics               | 6        | 3.11%   |
| Marvell Technology Group         | 5        | 2.59%   |
| Silicon Motion                   | 2        | 1.04%   |
| Silicon Integrated Systems [SiS] | 2        | 1.04%   |
| Silicon Image                    | 2        | 1.04%   |
| SanDisk                          | 1        | 0.52%   |
| Kingston Technology Company      | 1        | 0.52%   |
| Broadcom / LSI                   | 1        | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17       | 6.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14       | 5.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 4.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 4.89%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 3.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.01%   |
| Nvidia MCP61 SATA Controller                                                            | 7        | 2.63%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 6        | 2.26%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.26%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 5        | 1.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 1.88%   |
| Nvidia MCP61 IDE                                                                        | 5        | 1.88%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.88%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 1.88%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 1.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 1.88%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.5%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.5%    |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3        | 1.13%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.13%   |
| JMicron JMB368 IDE controller                                                           | 3        | 1.13%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 1.13%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 1.13%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.13%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.13%   |
| Nvidia nForce2 IDE                                                                      | 2        | 0.75%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 2        | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.75%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 0.75%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.75%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 96       | 50.26%  |
| IDE  | 68       | 35.6%   |
| NVMe | 15       | 7.85%   |
| RAID | 9        | 4.71%   |
| SAS  | 2        | 1.05%   |
| SCSI | 1        | 0.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 104      | 70.27%  |
| AMD    | 44       | 29.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-8100 CPU @ 3.60GHz            | 4        | 2.7%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 2.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.03%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2.03%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 3        | 2.03%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 2.03%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 3        | 2.03%   |
| Intel Pentium D CPU 2.80GHz                 | 2        | 1.35%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 1.35%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 1.35%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 1.35%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 1.35%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.35%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.35%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.35%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.35%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.35%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.35%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz       | 2        | 1.35%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.35%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.35%   |
| AMD Sempron Processor 3000+                 | 2        | 1.35%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.35%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.35%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.35%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1        | 0.68%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 0.68%   |
| Intel Xeon CPU E5472 @ 3.00GHz              | 1        | 0.68%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.68%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.68%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1        | 0.68%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.68%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.68%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.68%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.68%   |
| Intel Pentium D CPU 3.20GHz                 | 1        | 0.68%   |
| Intel Pentium CPU J4205 @ 1.50GHz           | 1        | 0.68%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.68%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.68%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core 2 Duo        | 18       | 12.16%  |
| Intel Core i5           | 16       | 10.81%  |
| Intel Core i7           | 15       | 10.14%  |
| Intel Core i3           | 11       | 7.43%   |
| Intel Core 2 Quad       | 9        | 6.08%   |
| Intel Xeon              | 7        | 4.73%   |
| Intel Pentium           | 7        | 4.73%   |
| Intel Celeron           | 7        | 4.73%   |
| AMD Ryzen 5             | 7        | 4.73%   |
| AMD Ryzen 7             | 5        | 3.38%   |
| AMD Sempron             | 4        | 2.7%    |
| AMD FX                  | 4        | 2.7%    |
| AMD Athlon 64 X2        | 4        | 2.7%    |
| Intel Pentium Dual-Core | 3        | 2.03%   |
| Intel Pentium D         | 3        | 2.03%   |
| Intel Pentium 4         | 3        | 2.03%   |
| Intel Core 2            | 3        | 2.03%   |
| AMD Phenom II X4        | 3        | 2.03%   |
| AMD Athlon XP           | 3        | 2.03%   |
| Intel Core i9           | 2        | 1.35%   |
| AMD Ryzen 3             | 2        | 1.35%   |
| AMD Phenom II X6        | 2        | 1.35%   |
| AMD Athlon II X4        | 2        | 1.35%   |
| AMD Ryzen 9             | 1        | 0.68%   |
| AMD Ryzen 5 PRO         | 1        | 0.68%   |
| AMD Phenom II X2        | 1        | 0.68%   |
| AMD E1                  | 1        | 0.68%   |
| AMD Athlon II X2        | 1        | 0.68%   |
| AMD Athlon              | 1        | 0.68%   |
| AMD A4                  | 1        | 0.68%   |
| AMD A10                 | 1        | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 57       | 38.51%  |
| 2      | 56       | 37.84%  |
| 1      | 12       | 8.11%   |
| 6      | 11       | 7.43%   |
| 8      | 8        | 5.41%   |
| 16     | 1        | 0.68%   |
| 12     | 1        | 0.68%   |
| 10     | 1        | 0.68%   |
| 3      | 1        | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 146      | 98.65%  |
| 2      | 2        | 1.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 96       | 64.86%  |
| 2      | 52       | 35.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 142      | 95.95%  |
| 32-bit         | 6        | 4.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 12.08%  |
| 0x1067a    | 16       | 10.74%  |
| 0x306c3    | 12       | 8.05%   |
| 0x206a7    | 12       | 8.05%   |
| 0x306a9    | 9        | 6.04%   |
| 0x6fb      | 5        | 3.36%   |
| 0x10677    | 5        | 3.36%   |
| 0x906eb    | 4        | 2.68%   |
| 0x6fd      | 4        | 2.68%   |
| 0x08108109 | 4        | 2.68%   |
| 0x010000c8 | 4        | 2.68%   |
| 0x106e5    | 3        | 2.01%   |
| 0xf65      | 2        | 1.34%   |
| 0xf64      | 2        | 1.34%   |
| 0xf29      | 2        | 1.34%   |
| 0x906ed    | 2        | 1.34%   |
| 0x906ea    | 2        | 1.34%   |
| 0x6f2      | 2        | 1.34%   |
| 0x506e3    | 2        | 1.34%   |
| 0x106a5    | 2        | 1.34%   |
| 0x10676    | 2        | 1.34%   |
| 0x08701021 | 2        | 1.34%   |
| 0x08701013 | 2        | 1.34%   |
| 0x0800820d | 2        | 1.34%   |
| 0x06001119 | 2        | 1.34%   |
| 0x06000852 | 2        | 1.34%   |
| 0x0600063e | 2        | 1.34%   |
| 0x010000dc | 2        | 1.34%   |
| 0xa0655    | 1        | 0.67%   |
| 0x706a8    | 1        | 0.67%   |
| 0x6f6      | 1        | 0.67%   |
| 0x506c9    | 1        | 0.67%   |
| 0x406f1    | 1        | 0.67%   |
| 0x40651    | 1        | 0.67%   |
| 0x306f2    | 1        | 0.67%   |
| 0x206d7    | 1        | 0.67%   |
| 0x20655    | 1        | 0.67%   |
| 0x10661    | 1        | 0.67%   |
| 0x0a50000c | 1        | 0.67%   |
| 0x0a201009 | 1        | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 23       | 15.54%  |
| SandyBridge   | 16       | 10.81%  |
| Haswell       | 14       | 9.46%   |
| Core          | 14       | 9.46%   |
| KabyLake      | 9        | 6.08%   |
| K10           | 9        | 6.08%   |
| IvyBridge     | 9        | 6.08%   |
| Zen+          | 7        | 4.73%   |
| NetBurst      | 7        | 4.73%   |
| K8 Hammer     | 7        | 4.73%   |
| Nehalem       | 5        | 3.38%   |
| Zen 2         | 4        | 2.7%    |
| Zen           | 4        | 2.7%    |
| Piledriver    | 4        | 2.7%    |
| K6            | 3        | 2.03%   |
| Zen 3         | 2        | 1.35%   |
| Skylake       | 2        | 1.35%   |
| Bulldozer     | 2        | 1.35%   |
| Westmere      | 1        | 0.68%   |
| Jaguar        | 1        | 0.68%   |
| Goldmont plus | 1        | 0.68%   |
| Goldmont      | 1        | 0.68%   |
| CometLake     | 1        | 0.68%   |
| Broadwell     | 1        | 0.68%   |
| Bobcat        | 1        | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 65       | 41.14%  |
| Intel                      | 51       | 32.28%  |
| AMD                        | 35       | 22.15%  |
| VIA Technologies           | 4        | 2.53%   |
| S3 Graphics                | 1        | 0.63%   |
| Matrox Electronics Systems | 1        | 0.63%   |
| ASPEED Technology          | 1        | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13       | 7.93%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 7        | 4.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 7        | 4.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 6        | 3.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 6        | 3.66%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 6        | 3.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 5        | 3.05%   |
| Nvidia GT218 [GeForce 210]                                                    | 4        | 2.44%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4        | 2.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4        | 2.44%   |
| Nvidia GK208B [GeForce GT 710]                                                | 3        | 1.83%   |
| AMD RV710 [Radeon HD 4350/4550]                                               | 3        | 1.83%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 3        | 1.83%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 2        | 1.22%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 2        | 1.22%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 2        | 1.22%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2        | 1.22%   |
| Nvidia GK104 [GeForce GTX 760]                                                | 2        | 1.22%   |
| Nvidia GF104 [GeForce GTX 460]                                                | 2        | 1.22%   |
| Nvidia G86 [GeForce 8400 GS]                                                  | 2        | 1.22%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                       | 2        | 1.22%   |
| Intel 82Q35 Express Integrated Graphics Controller                            | 2        | 1.22%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 2        | 1.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2        | 1.22%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                    | 1        | 0.61%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                     | 1        | 0.61%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 1        | 0.61%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.61%   |
| S3 Graphics VT8375 [ProSavage8 KM266/KL266]                                   | 1        | 0.61%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1        | 0.61%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 1        | 0.61%   |
| Nvidia NV44 [GeForce 6200 TurboCache]                                         | 1        | 0.61%   |
| Nvidia NV43 [GeForce 6600]                                                    | 1        | 0.61%   |
| Nvidia NV36 [GeForce FX 5700VE]                                               | 1        | 0.61%   |
| Nvidia NV34 [GeForce FX 5200]                                                 | 1        | 0.61%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                         | 1        | 0.61%   |
| Nvidia GT218 [GeForce 310]                                                    | 1        | 0.61%   |
| Nvidia GT200 [GeForce GTX 260]                                                | 1        | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1        | 0.61%   |
| Nvidia GM204GL [Quadro M4000]                                                 | 1        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 61       | 40.94%  |
| 1 x Intel       | 42       | 28.19%  |
| 1 x AMD         | 32       | 21.48%  |
| 1 x VIA         | 4        | 2.68%   |
| 2 x AMD         | 3        | 2.01%   |
| Intel + Nvidia  | 3        | 2.01%   |
| 2 x Nvidia      | 1        | 0.67%   |
| 1 x S3 Graphics | 1        | 0.67%   |
| 1 x Matrox      | 1        | 0.67%   |
| 1 x ASPEED      | 1        | 0.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 100      | 66.67%  |
| Proprietary | 27       | 18%     |
| Unknown     | 23       | 15.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 69       | 46%     |
| 0.51-1.0   | 22       | 14.67%  |
| 0.01-0.5   | 20       | 13.33%  |
| 1.01-2.0   | 14       | 9.33%   |
| 3.01-4.0   | 12       | 8%      |
| 7.01-8.0   | 10       | 6.67%   |
| 2.01-3.0   | 2        | 1.33%   |
| 5.01-6.0   | 1        | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 29       | 17.9%   |
| Dell                    | 16       | 9.88%   |
| Goldstar                | 15       | 9.26%   |
| Acer                    | 15       | 9.26%   |
| AOC                     | 9        | 5.56%   |
| Ancor Communications    | 9        | 5.56%   |
| Unknown                 | 6        | 3.7%    |
| Philips                 | 6        | 3.7%    |
| Hewlett-Packard         | 6        | 3.7%    |
| BenQ                    | 6        | 3.7%    |
| Lenovo                  | 4        | 2.47%   |
| Fujitsu Siemens         | 4        | 2.47%   |
| Sony                    | 3        | 1.85%   |
| Iiyama                  | 3        | 1.85%   |
| Sceptre Tech            | 2        | 1.23%   |
| NEC Computers           | 2        | 1.23%   |
| LG Electronics          | 2        | 1.23%   |
| eMachines               | 2        | 1.23%   |
| ___                     | 1        | 0.62%   |
| Vestel                  | 1        | 0.62%   |
| Toshiba                 | 1        | 0.62%   |
| Targa Visionary         | 1        | 0.62%   |
| OEM                     | 1        | 0.62%   |
| NCS                     | 1        | 0.62%   |
| Mitsubishi              | 1        | 0.62%   |
| Microstep               | 1        | 0.62%   |
| Medion                  | 1        | 0.62%   |
| IBM                     | 1        | 0.62%   |
| Hitachi                 | 1        | 0.62%   |
| ELSA International      | 1        | 0.62%   |
| Elo Touch               | 1        | 0.62%   |
| ELO                     | 1        | 0.62%   |
| Eizo                    | 1        | 0.62%   |
| DENON                   | 1        | 0.62%   |
| Compal                  | 1        | 0.62%   |
| Chi Mei Optoelectronics | 1        | 0.62%   |
| Belinea                 | 1        | 0.62%   |
| AUS                     | 1        | 0.62%   |
| ASUSTek Computer        | 1        | 0.62%   |
| AOpen                   | 1        | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch     | 2        | 1.2%    |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                       | 2        | 1.2%    |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                           | 2        | 1.2%    |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch                   | 1        | 0.6%    |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                               | 1        | 0.6%    |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                      | 1        | 0.6%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.6%    |
| Unknown LCD Monitor SAMSUNG                                             | 1        | 0.6%    |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                       | 1        | 0.6%    |
| Unknown LCD Monitor GBT G34WQC 3440x1440                                | 1        | 0.6%    |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch                  | 1        | 0.6%    |
| Toshiba LCD Monitor TV 1920x1080                                        | 1        | 0.6%    |
| Targa Visionary LCD19-4 TARA194 1280x1024 376x301mm 19.0-inch           | 1        | 0.6%    |
| Sony TV SNY4C03 1920x1080 1063x598mm 48.0-inch                          | 1        | 0.6%    |
| Sony TV SNY1B02 1360x768                                                | 1        | 0.6%    |
| Sony LCD Monitor TV 3840x1080                                           | 1        | 0.6%    |
| Sceptre Tech F24 SPT0961 1920x1080 480x260mm 21.5-inch                  | 1        | 0.6%    |
| Sceptre Tech E27 SPT0ABF 1920x1080 521x293mm 23.5-inch                  | 1        | 0.6%    |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch       | 1        | 0.6%    |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch       | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch     | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 459x296mm 21.5-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM034F 1440x900 428x255mm 19.6-inch     | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM0303 1680x1050 494x320mm 23.2-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 376x301mm 19.0-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM006E 1280x1024 338x270mm 17.0-inch    | 1        | 0.6%    |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch    | 1        | 0.6%    |
| Samsung Electronics SMS22A200/460 SAM0831 1920x1080 477x268mm 21.5-inch | 1        | 0.6%    |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch      | 1        | 0.6%    |
| Samsung Electronics SMB2230 SAM063E 1920x1080 477x268mm 21.5-inch       | 1        | 0.6%    |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch       | 1        | 0.6%    |
| Samsung Electronics S24F350 SAM0D21 1920x1080 520x290mm 23.4-inch       | 1        | 0.6%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 1        | 0.6%    |
| Samsung Electronics S24D360 SAM0B24 1920x1080 521x293mm 23.5-inch       | 1        | 0.6%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1        | 0.6%    |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch       | 1        | 0.6%    |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1        | 0.6%    |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch       | 1        | 0.6%    |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch        | 1        | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 68       | 44.16%  |
| 1280x1024 (SXGA)   | 30       | 19.48%  |
| 1680x1050 (WSXGA+) | 9        | 5.84%   |
| 1440x900 (WXGA+)   | 9        | 5.84%   |
| 1366x768 (WXGA)    | 7        | 4.55%   |
| 1920x1200 (WUXGA)  | 5        | 3.25%   |
| 3840x2160 (4K)     | 4        | 2.6%    |
| 1600x900 (HD+)     | 4        | 2.6%    |
| 1360x768           | 4        | 2.6%    |
| 1024x768 (XGA)     | 4        | 2.6%    |
| Unknown            | 3        | 1.95%   |
| 3440x1440          | 2        | 1.3%    |
| 7680x2160          | 1        | 0.65%   |
| 4240x1440          | 1        | 0.65%   |
| 3840x1080          | 1        | 0.65%   |
| 2560x1440 (QHD)    | 1        | 0.65%   |
| 1600x1200          | 1        | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 14.56%  |
| 21      | 20       | 12.66%  |
| 19      | 16       | 10.13%  |
| 17      | 16       | 10.13%  |
| 24      | 14       | 8.86%   |
| 23      | 14       | 8.86%   |
| 18      | 12       | 7.59%   |
| 27      | 11       | 6.96%   |
| 15      | 7        | 4.43%   |
| 22      | 6        | 3.8%    |
| 20      | 5        | 3.16%   |
| 31      | 3        | 1.9%    |
| 72      | 1        | 0.63%   |
| 54      | 1        | 0.63%   |
| 52      | 1        | 0.63%   |
| 48      | 1        | 0.63%   |
| 33      | 1        | 0.63%   |
| 32      | 1        | 0.63%   |
| 26      | 1        | 0.63%   |
| 16      | 1        | 0.63%   |
| 14      | 1        | 0.63%   |
| 13      | 1        | 0.63%   |
| 12      | 1        | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 48       | 30.97%  |
| 501-600     | 35       | 22.58%  |
| 301-350     | 23       | 14.84%  |
| Unknown     | 23       | 14.84%  |
| 351-400     | 14       | 9.03%   |
| 601-700     | 4        | 2.58%   |
| 1001-1500   | 3        | 1.94%   |
| 701-800     | 2        | 1.29%   |
| 201-300     | 2        | 1.29%   |
| 1501-2000   | 1        | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 72       | 47.37%  |
| 5/4     | 26       | 17.11%  |
| Unknown | 22       | 14.47%  |
| 16/10   | 21       | 13.82%  |
| 4/3     | 9        | 5.92%   |
| 3/2     | 1        | 0.66%   |
| 21/9    | 1        | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 26.75%  |
| 151-200        | 31       | 19.75%  |
| 141-150        | 23       | 14.65%  |
| Unknown        | 23       | 14.65%  |
| 301-350        | 12       | 7.64%   |
| 101-110        | 7        | 4.46%   |
| 251-300        | 6        | 3.82%   |
| 351-500        | 5        | 3.18%   |
| More than 1000 | 3        | 1.91%   |
| 111-120        | 2        | 1.27%   |
| 81-90          | 1        | 0.64%   |
| 71-80          | 1        | 0.64%   |
| 501-1000       | 1        | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 94       | 63.51%  |
| 101-120 | 23       | 15.54%  |
| Unknown | 23       | 15.54%  |
| 1-50    | 4        | 2.7%    |
| 121-160 | 3        | 2.03%   |
| 161-240 | 1        | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 123      | 81.46%  |
| 2     | 21       | 13.91%  |
| 0     | 6        | 3.97%   |
| 3     | 1        | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 90       | 42.86%  |
| Intel                            | 41       | 19.52%  |
| Qualcomm Atheros                 | 21       | 10%     |
| Ralink Technology                | 11       | 5.24%   |
| Nvidia                           | 9        | 4.29%   |
| Broadcom                         | 7        | 3.33%   |
| VIA Technologies                 | 4        | 1.9%    |
| TP-Link                          | 4        | 1.9%    |
| Marvell Technology Group         | 3        | 1.43%   |
| Broadcom Limited                 | 2        | 0.95%   |
| AVM                              | 2        | 0.95%   |
| Sitecom Europe                   | 1        | 0.48%   |
| Silicon Integrated Systems [SiS] | 1        | 0.48%   |
| Samsung Electronics              | 1        | 0.48%   |
| Ralink                           | 1        | 0.48%   |
| Microsoft                        | 1        | 0.48%   |
| Mellanox Technologies            | 1        | 0.48%   |
| MediaTek                         | 1        | 0.48%   |
| LSI                              | 1        | 0.48%   |
| JMicron Technology               | 1        | 0.48%   |
| Huawei Technologies              | 1        | 0.48%   |
| Edimax Technology                | 1        | 0.48%   |
| DisplayLink                      | 1        | 0.48%   |
| Belkin Components                | 1        | 0.48%   |
| ASUSTek Computer                 | 1        | 0.48%   |
| ADMtek                           | 1        | 0.48%   |
| 3Com                             | 1        | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64       | 27.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8        | 3.45%   |
| Nvidia MCP61 Ethernet                                             | 7        | 3.02%   |
| Intel I211 Gigabit Network Connection                             | 7        | 3.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 2.16%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 1.72%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 1.72%   |
| Intel Wi-Fi 6 AX200                                               | 4        | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 1.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 1.29%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 1.29%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 1.29%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 1.29%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.29%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2        | 0.86%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.86%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.86%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 2        | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.86%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 2        | 0.86%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.86%   |
| Nvidia nForce2 Ethernet Controller                                | 2        | 0.86%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.86%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.86%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.86%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.86%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.43%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.43%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.43%   |
| TP-Link 802.11n NIC                                               | 1        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 26.15%  |
| Ralink Technology     | 11       | 16.92%  |
| Intel                 | 11       | 16.92%  |
| Qualcomm Atheros      | 9        | 13.85%  |
| TP-Link               | 4        | 6.15%   |
| Broadcom              | 3        | 4.62%   |
| AVM                   | 2        | 3.08%   |
| Sitecom Europe        | 1        | 1.54%   |
| Ralink                | 1        | 1.54%   |
| Microsoft             | 1        | 1.54%   |
| MediaTek              | 1        | 1.54%   |
| Edimax Technology     | 1        | 1.54%   |
| Broadcom Limited      | 1        | 1.54%   |
| Belkin Components     | 1        | 1.54%   |
| ASUSTek Computer      | 1        | 1.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 6.15%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 6.15%   |
| Intel Wi-Fi 6 AX200                                                                           | 4        | 6.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 4.62%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 2        | 3.08%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 3.08%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 3.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 3.08%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2        | 3.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 3.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2        | 3.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 2        | 3.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 3.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 1.54%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 1.54%   |
| TP-Link 802.11n NIC                                                                           | 1        | 1.54%   |
| Sitecom Europe RTL8188S WLAN Adapter                                                          | 1        | 1.54%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 1.54%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 1.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.54%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 1.54%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.54%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1        | 1.54%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 1.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.54%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 1.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 1.54%   |
| Intel Wireless 8265 / 8275                                                                    | 1        | 1.54%   |
| Intel Wireless 7265                                                                           | 1        | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1        | 1.54%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 1.54%   |
| Intel Centrino Wireless-N 105                                                                 | 1        | 1.54%   |
| Edimax AC600 USB                                                                              | 1        | 1.54%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 1.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1        | 1.54%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1        | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 83       | 51.88%  |
| Intel                            | 37       | 23.13%  |
| Qualcomm Atheros                 | 12       | 7.5%    |
| Nvidia                           | 9        | 5.63%   |
| VIA Technologies                 | 4        | 2.5%    |
| Broadcom                         | 4        | 2.5%    |
| Marvell Technology Group         | 3        | 1.88%   |
| Silicon Integrated Systems [SiS] | 1        | 0.63%   |
| Samsung Electronics              | 1        | 0.63%   |
| JMicron Technology               | 1        | 0.63%   |
| Huawei Technologies              | 1        | 0.63%   |
| DisplayLink                      | 1        | 0.63%   |
| Broadcom Limited                 | 1        | 0.63%   |
| ADMtek                           | 1        | 0.63%   |
| 3Com                             | 1        | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64       | 38.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8        | 4.85%   |
| Nvidia MCP61 Ethernet                                             | 7        | 4.24%   |
| Intel I211 Gigabit Network Connection                             | 7        | 4.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.03%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 1.82%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 1.82%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 1.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 1.82%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.21%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 1.21%   |
| Nvidia nForce2 Ethernet Controller                                | 2        | 1.21%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.21%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.21%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.21%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.21%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.21%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.21%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.21%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 1.21%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.61%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1        | 0.61%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.61%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.61%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.61%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.61%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.61%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.61%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.61%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 148      | 71.15%  |
| WiFi     | 58       | 27.88%  |
| Modem    | 1        | 0.48%   |
| Unknown  | 1        | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 123      | 79.35%  |
| WiFi     | 32       | 20.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 102      | 68.92%  |
| 2     | 41       | 27.7%   |
| 3     | 4        | 2.7%    |
| 4     | 1        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 126      | 81.29%  |
| Yes  | 29       | 18.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 34.48%  |
| Cambridge Silicon Radio         | 8        | 27.59%  |
| Realtek Semiconductor           | 3        | 10.34%  |
| Qualcomm Atheros Communications | 2        | 6.9%    |
| Broadcom                        | 2        | 6.9%    |
| ASUSTek Computer                | 2        | 6.9%    |
| MediaTek                        | 1        | 3.45%   |
| Apple                           | 1        | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 27.59%  |
| Intel AX200 Bluetooth                               | 4        | 13.79%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 6.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 6.9%    |
| Intel Bluetooth wireless interface                  | 2        | 6.9%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 6.9%    |
| Realtek Bluetooth Radio                             | 1        | 3.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 3.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 3.45%   |
| MediaTek Wireless_Device                            | 1        | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 3.45%   |
| Intel AX201 Bluetooth                               | 1        | 3.45%   |
| Broadcom HP Bluethunder                             | 1        | 3.45%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 3.45%   |
| Apple Bluetooth USB Host Controller                 | 1        | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 90       | 39.3%   |
| Nvidia                           | 57       | 24.89%  |
| AMD                              | 42       | 18.34%  |
| C-Media Electronics              | 9        | 3.93%   |
| VIA Technologies                 | 8        | 3.49%   |
| Creative Labs                    | 4        | 1.75%   |
| GN Netcom                        | 3        | 1.31%   |
| Generalplus Technology           | 3        | 1.31%   |
| Silicon Integrated Systems [SiS] | 2        | 0.87%   |
| Logitech                         | 2        | 0.87%   |
| Yamaha                           | 1        | 0.44%   |
| Xilinx                           | 1        | 0.44%   |
| Tenx Technology                  | 1        | 0.44%   |
| M-Audio                          | 1        | 0.44%   |
| JMTek                            | 1        | 0.44%   |
| GYROCOM C&C                      | 1        | 0.44%   |
| Focusrite-Novation               | 1        | 0.44%   |
| Evolution Electronics            | 1        | 0.44%   |
| Creative Technology              | 1        | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 17       | 6.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 14       | 5.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 11       | 4.31%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 8        | 3.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 8        | 3.14%   |
| Nvidia MCP61 High Definition Audio                                          | 7        | 2.75%   |
| Nvidia GM206 High Definition Audio Controller                               | 7        | 2.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 7        | 2.75%   |
| Nvidia High Definition Audio Controller                                     | 6        | 2.35%   |
| Nvidia GP107GL High Definition Audio Controller                             | 6        | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 6        | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                  | 6        | 2.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 6        | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 6        | 2.35%   |
| AMD Family 17h/19h HD Audio Controller                                      | 6        | 2.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 6        | 2.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 5        | 1.96%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                               | 5        | 1.96%   |
| AMD Starship/Matisse HD Audio Controller                                    | 5        | 1.96%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                   | 4        | 1.57%   |
| Intel 9 Series Chipset Family HD Audio Controller                           | 4        | 1.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 4        | 1.57%   |
| Nvidia TU106 High Definition Audio Controller                               | 3        | 1.18%   |
| Nvidia GP106 High Definition Audio Controller                               | 3        | 1.18%   |
| Nvidia GK104 HDMI Audio Controller                                          | 3        | 1.18%   |
| Nvidia GF108 High Definition Audio Controller                               | 3        | 1.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 3        | 1.18%   |
| Generalplus Technology USB Audio Device                                     | 3        | 1.18%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                            | 3        | 1.18%   |
| AMD FCH Azalia Controller                                                   | 3        | 1.18%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 3        | 1.18%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 2        | 0.78%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller             | 2        | 0.78%   |
| Nvidia nForce2 AC97 Audio Controler (MCP)                                   | 2        | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                               | 2        | 0.78%   |
| Nvidia GF116 High Definition Audio Controller                               | 2        | 0.78%   |
| Nvidia GF104 High Definition Audio Controller                               | 2        | 0.78%   |
| Intel C610/X99 series chipset HD Audio Controller                           | 2        | 0.78%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 2        | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                              | 2        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 9        | 40.91%  |
| Kingston            | 3        | 13.64%  |
| Crucial             | 3        | 13.64%  |
| Samsung Electronics | 2        | 9.09%   |
| SK hynix            | 1        | 4.55%   |
| PLEXHD              | 1        | 4.55%   |
| Micron Technology   | 1        | 4.55%   |
| G.Skill             | 1        | 4.55%   |
| Exceleram           | 1        | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 667MT/s                   | 1        | 4.17%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 1        | 4.17%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 4.17%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                | 1        | 4.17%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 1        | 4.17%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s             | 1        | 4.17%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s             | 1        | 4.17%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                  | 1        | 4.17%   |
| Unknown RAM Module 1024MB DIMM                          | 1        | 4.17%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s      | 1        | 4.17%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s           | 1        | 4.17%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 4.17%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 4.17%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s     | 1        | 4.17%   |
| PLEXHD RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 4.17%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 1        | 4.17%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s          | 1        | 4.17%   |
| Kingston RAM KHX3600C17D4/16GX 16GB DIMM DDR4 3800MT/s  | 1        | 4.17%   |
| Kingston RAM 9965589-033.D00G 8192MB DIMM DDR4 2400MT/s | 1        | 4.17%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s  | 1        | 4.17%   |
| Exceleram RAM E30144A 4096MB DIMM DDR3 800MT/s          | 1        | 4.17%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 1        | 4.17%   |
| Crucial RAM BLT8G4D26BFT4K.C8FD 8GB DIMM DDR4 2666MT/s  | 1        | 4.17%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s   | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 8        | 36.36%  |
| DDR4    | 7        | 31.82%  |
| DDR2    | 4        | 18.18%  |
| Unknown | 2        | 9.09%   |
| DDR     | 1        | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 90.91%  |
| SODIMM | 2        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 34.78%  |
| 2048  | 6        | 26.09%  |
| 4096  | 4        | 17.39%  |
| 16384 | 2        | 8.7%    |
| 1024  | 2        | 8.7%    |
| 512   | 1        | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6        | 27.27%  |
| 800     | 3        | 13.64%  |
| 2400    | 2        | 9.09%   |
| 1333    | 2        | 9.09%   |
| 667     | 2        | 9.09%   |
| 4266    | 1        | 4.55%   |
| 3800    | 1        | 4.55%   |
| 3500    | 1        | 4.55%   |
| 3200    | 1        | 4.55%   |
| 2666    | 1        | 4.55%   |
| 400     | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

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
| Logitech                      | 7        | 35%     |
| Microsoft                     | 3        | 15%     |
| Xiongmai                      | 1        | 5%      |
| WCM_USB                       | 1        | 5%      |
| Sunplus Innovation Technology | 1        | 5%      |
| Service & Quality Technology  | 1        | 5%      |
| Nintendo                      | 1        | 5%      |
| Microdia                      | 1        | 5%      |
| MacroSilicon                  | 1        | 5%      |
| KYE Systems (Mouse Systems)   | 1        | 5%      |
| Generalplus Technology        | 1        | 5%      |
| Chicony Electronics           | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Logitech Webcam C270                               | 4        | 20%     |
| Microsoft LifeCam HD-3000                          | 2        | 10%     |
| Xiongmai web camera                                | 1        | 5%      |
| WCM_USB WEB CAM                                    | 1        | 5%      |
| Sunplus Full HD webcam                             | 1        | 5%      |
| Service & Quality USB PC Camera                    | 1        | 5%      |
| Nintendo USB Camera                                | 1        | 5%      |
| Microsoft MicrosoftÂ LifeCam VX-5500              | 1        | 5%      |
| Microdia Webcam Vitade AF                          | 1        | 5%      |
| MacroSilicon USB Video                             | 1        | 5%      |
| Logitech Webcam Pro 9000                           | 1        | 5%      |
| Logitech Webcam C310                               | 1        | 5%      |
| Logitech HD Pro Webcam C920                        | 1        | 5%      |
| KYE Systems (Mouse Systems) Genius iSlim 2000AF V2 | 1        | 5%      |
| Generalplus 808 Camera #9 (web-cam mode)           | 1        | 5%      |
| Chicony HP High Definition 1MP Webcam              | 1        | 5%      |

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
| 0     | 104      | 68.87%  |
| 1     | 40       | 26.49%  |
| 2     | 3        | 1.99%   |
| 4     | 2        | 1.32%   |
| 3     | 2        | 1.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 27       | 49.09%  |
| Net/wireless             | 14       | 25.45%  |
| Communication controller | 4        | 7.27%   |
| Unassigned class         | 2        | 3.64%   |
| Network                  | 2        | 3.64%   |
| Net/ethernet             | 2        | 3.64%   |
| Storage/ide              | 1        | 1.82%   |
| Modem                    | 1        | 1.82%   |
| Fingerprint reader       | 1        | 1.82%   |
| Chipcard                 | 1        | 1.82%   |

