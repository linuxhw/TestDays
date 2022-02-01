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
| 4.19.0-16-amd64     | 24       | 15.38%  |
| 4.19.0-17-amd64     | 19       | 12.18%  |
| 4.19.0-14-amd64     | 18       | 11.54%  |
| 4.19.0-13-amd64     | 17       | 10.9%   |
| 4.19.0-18-amd64     | 15       | 9.62%   |
| 4.19.0-8-amd64      | 14       | 8.97%   |
| 4.19.0-12-amd64     | 9        | 5.77%   |
| 4.19.0-10-amd64     | 8        | 5.13%   |
| 4.19.0-9-amd64      | 7        | 4.49%   |
| 4.19.0-11-amd64     | 4        | 2.56%   |
| 4.19.0-17-686       | 3        | 1.92%   |
| 4.19.0-16-686       | 3        | 1.92%   |
| 4.19.0-14-686       | 3        | 1.92%   |
| 4.19.0-8-686        | 2        | 1.28%   |
| 4.19.0-18-686       | 2        | 1.28%   |
| 4.19.0-13-686       | 2        | 1.28%   |
| 5.8.0-3-amd64       | 1        | 0.64%   |
| 5.6.0-0.bpo.2-amd64 | 1        | 0.64%   |
| 5.4.0-0.bpo.4-amd64 | 1        | 0.64%   |
| 5.10.0-7-amd64      | 1        | 0.64%   |
| 4.19.0-9-686        | 1        | 0.64%   |
| 4.19.0-12-686       | 1        | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 134      | 97.1%   |
| 5.8.0   | 1        | 0.72%   |
| 5.6.0   | 1        | 0.72%   |
| 5.4.0   | 1        | 0.72%   |
| 5.10.0  | 1        | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 134      | 97.1%   |
| 5.8     | 1        | 0.72%   |
| 5.6     | 1        | 0.72%   |
| 5.4     | 1        | 0.72%   |
| 5.10    | 1        | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 121      | 87.68%  |
| i686   | 17       | 12.32%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 124      | 89.21%  |
| Cinnamon   | 6        | 4.32%   |
| Unknown    | 3        | 2.16%   |
| MATE       | 2        | 1.44%   |
| XFCE       | 1        | 0.72%   |
| LXQt       | 1        | 0.72%   |
| LXDE       | 1        | 0.72%   |
| GNOME      | 1        | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 138      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 126      | 91.3%   |
| TDM     | 8        | 5.8%    |
| LightDM | 3        | 2.17%   |
| GDM     | 1        | 0.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Desktops | Percent |
|--------|----------|---------|
| en_US  | 35       | 25.36%  |
| pt_BR  | 15       | 10.87%  |
| de_DE  | 15       | 10.87%  |
| fr_FR  | 12       | 8.7%    |
| pl_PL  | 7        | 5.07%   |
| en_GB  | 6        | 4.35%   |
| ru_RU  | 5        | 3.62%   |
| sv_SE  | 3        | 2.17%   |
| nl_BE  | 3        | 2.17%   |
| it_IT  | 3        | 2.17%   |
| es_AR  | 3        | 2.17%   |
| en_CA  | 3        | 2.17%   |
| en_AU  | 3        | 2.17%   |
| pt_PT  | 2        | 1.45%   |
| hu_HU  | 2        | 1.45%   |
| es_ES  | 2        | 1.45%   |
| unm_US | 1        | 0.72%   |
| uk_UA  | 1        | 0.72%   |
| tr_TR  | 1        | 0.72%   |
| sk_SK  | 1        | 0.72%   |
| nb_NO  | 1        | 0.72%   |
| fr_CA  | 1        | 0.72%   |
| fi_FI  | 1        | 0.72%   |
| et_EE  | 1        | 0.72%   |
| es_UY  | 1        | 0.72%   |
| es_MX  | 1        | 0.72%   |
| es_CO  | 1        | 0.72%   |
| es_CL  | 1        | 0.72%   |
| en_ZA  | 1        | 0.72%   |
| el_GR  | 1        | 0.72%   |
| de_AT  | 1        | 0.72%   |
| cs_CZ  | 1        | 0.72%   |
| ca_ES  | 1        | 0.72%   |
| bg_BG  | 1        | 0.72%   |
| ar_EG  | 1        | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 98       | 71.01%  |
| EFI  | 40       | 28.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 132      | 94.96%  |
| Btrfs   | 4        | 2.88%   |
| Unknown | 2        | 1.44%   |
| Ext3    | 1        | 0.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 125      | 89.29%  |
| GPT     | 10       | 7.14%   |
| MBR     | 5        | 3.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 134      | 95.71%  |
| Yes       | 6        | 4.29%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 132      | 95.65%  |
| Yes       | 6        | 4.35%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 31       | 22.46%  |
| Gigabyte Technology | 18       | 13.04%  |
| MSI                 | 17       | 12.32%  |
| Dell                | 13       | 9.42%   |
| ASRock              | 11       | 7.97%   |
| Hewlett-Packard     | 9        | 6.52%   |
| Unknown             | 8        | 5.8%    |
| Intel               | 5        | 3.62%   |
| ECS                 | 4        | 2.9%    |
| Acer                | 4        | 2.9%    |
| Pegatron            | 2        | 1.45%   |
| OEM                 | 2        | 1.45%   |
| EVGA                | 2        | 1.45%   |
| Biostar             | 2        | 1.45%   |
| Semp Toshiba        | 1        | 0.72%   |
| Positivo            | 1        | 0.72%   |
| PCWare              | 1        | 0.72%   |
| NEC Computers       | 1        | 0.72%   |
| Lenovo              | 1        | 0.72%   |
| Fujitsu Siemens     | 1        | 0.72%   |
| Foxconn             | 1        | 0.72%   |
| eMachines           | 1        | 0.72%   |
| DFI                 | 1        | 0.72%   |
| Alienware           | 1        | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 9        | 6.52%   |
| Dell OptiPlex 780                  | 2        | 1.45%   |
| ASUS All Series                    | 2        | 1.45%   |
| Semp Toshiba STI                   | 1        | 0.72%   |
| Positivo POS-EIH61CE               | 1        | 0.72%   |
| Pegatron Elite 7300 Series MT      | 1        | 0.72%   |
| Pegatron 520-1188la                | 1        | 0.72%   |
| PCWare IPMH81G1                    | 1        | 0.72%   |
| OEM 45CMX/45GMX/45CMX-K            | 1        | 0.72%   |
| NEC Computers IMEDIA S9509         | 1        | 0.72%   |
| MSI PX714AA-ABH t3040.nl           | 1        | 0.72%   |
| MSI MS-7C52                        | 1        | 0.72%   |
| MSI MS-7C51                        | 1        | 0.72%   |
| MSI MS-7A40                        | 1        | 0.72%   |
| MSI MS-7918                        | 1        | 0.72%   |
| MSI MS-7850                        | 1        | 0.72%   |
| MSI MS-7823                        | 1        | 0.72%   |
| MSI MS-7817                        | 1        | 0.72%   |
| MSI MS-7815                        | 1        | 0.72%   |
| MSI MS-7751                        | 1        | 0.72%   |
| MSI MS-7383                        | 1        | 0.72%   |
| MSI MS-7267                        | 1        | 0.72%   |
| MSI MS-7142                        | 1        | 0.72%   |
| MSI MS-6785                        | 1        | 0.72%   |
| MSI MS-6570                        | 1        | 0.72%   |
| MSI ESPRIMO P2440                  | 1        | 0.72%   |
| MSI *MF                            | 1        | 0.72%   |
| Lenovo ThinkCentre M93p 10AB0010US | 1        | 0.72%   |
| Intel H61                          | 1        | 0.72%   |
| Intel DP55WB AAE64798-206          | 1        | 0.72%   |
| Intel DG33FB AAD81072-309          | 1        | 0.72%   |
| Intel DG31PR AAD97573-302          | 1        | 0.72%   |
| Intel BTC-T37                      | 1        | 0.72%   |
| HP xw8600 Workstation              | 1        | 0.72%   |
| HP Pavilion Desktop 590-p0xxx      | 1        | 0.72%   |
| HP Desktop 190-0xxx                | 1        | 0.72%   |
| HP CQ2930EA                        | 1        | 0.72%   |
| HP Compaq Elite 8300 CMT           | 1        | 0.72%   |
| HP Compaq dc7800 Small Form Factor | 1        | 0.72%   |
| HP Compaq 8200 Elite USDT PC       | 1        | 0.72%   |
| HP Compaq 8100 Elite SFF PC        | 1        | 0.72%   |
| HP 290 G2 MT Business PC           | 1        | 0.72%   |
| Gigabyte Z97-D3H                   | 1        | 0.72%   |
| Gigabyte Z77-D3H                   | 1        | 0.72%   |
| Gigabyte Z390 M GAMING             | 1        | 0.72%   |
| Gigabyte Z390 DESIGNARE            | 1        | 0.72%   |
| Gigabyte Z370 AORUS Gaming 7       | 1        | 0.72%   |
| Gigabyte X570 AORUS ULTRA          | 1        | 0.72%   |
| Gigabyte X570 AORUS PRO            | 1        | 0.72%   |
| Gigabyte M68MT-S2P                 | 1        | 0.72%   |
| Gigabyte M52LT-D3P                 | 1        | 0.72%   |
| Gigabyte H81M-S2PV                 | 1        | 0.72%   |
| Gigabyte H61M-S1                   | 1        | 0.72%   |
| Gigabyte H61M-DS2 DVI              | 1        | 0.72%   |
| Gigabyte GA-880GM-UD2H             | 1        | 0.72%   |
| Gigabyte GA-78LMT-USB3 6.0         | 1        | 0.72%   |
| Gigabyte EP45C-DS3R                | 1        | 0.72%   |
| Gigabyte COMFOR OFFICE I33         | 1        | 0.72%   |
| Gigabyte B450M DS3H                | 1        | 0.72%   |
| Gigabyte 945GM-S2                  | 1        | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 9        | 6.52%   |
| Dell OptiPlex          | 8        | 5.8%    |
| HP Compaq              | 4        | 2.9%    |
| ASUS PRIME             | 4        | 2.9%    |
| Dell Inspiron          | 3        | 2.17%   |
| Gigabyte Z390          | 2        | 1.45%   |
| Gigabyte X570          | 2        | 1.45%   |
| Dell Precision         | 2        | 1.45%   |
| ASUS ROG               | 2        | 1.45%   |
| ASUS P5KPL-AM          | 2        | 1.45%   |
| ASUS All               | 2        | 1.45%   |
| Acer Veriton           | 2        | 1.45%   |
| Acer Aspire            | 2        | 1.45%   |
| Semp Toshiba STI       | 1        | 0.72%   |
| Positivo POS-EIH61CE   | 1        | 0.72%   |
| Pegatron Elite         | 1        | 0.72%   |
| Pegatron 520-1188la    | 1        | 0.72%   |
| PCWare IPMH81G1        | 1        | 0.72%   |
| OEM 45CMX              | 1        | 0.72%   |
| NEC Computers IMEDIA   | 1        | 0.72%   |
| MSI PX714AA-ABH        | 1        | 0.72%   |
| MSI MS-7C52            | 1        | 0.72%   |
| MSI MS-7C51            | 1        | 0.72%   |
| MSI MS-7A40            | 1        | 0.72%   |
| MSI MS-7918            | 1        | 0.72%   |
| MSI MS-7850            | 1        | 0.72%   |
| MSI MS-7823            | 1        | 0.72%   |
| MSI MS-7817            | 1        | 0.72%   |
| MSI MS-7815            | 1        | 0.72%   |
| MSI MS-7751            | 1        | 0.72%   |
| MSI MS-7383            | 1        | 0.72%   |
| MSI MS-7267            | 1        | 0.72%   |
| MSI MS-7142            | 1        | 0.72%   |
| MSI MS-6785            | 1        | 0.72%   |
| MSI MS-6570            | 1        | 0.72%   |
| MSI ESPRIMO            | 1        | 0.72%   |
| MSI *MF                | 1        | 0.72%   |
| Lenovo ThinkCentre     | 1        | 0.72%   |
| Intel H61              | 1        | 0.72%   |
| Intel DP55WB           | 1        | 0.72%   |
| Intel DG33FB           | 1        | 0.72%   |
| Intel DG31PR           | 1        | 0.72%   |
| Intel BTC-T37          | 1        | 0.72%   |
| HP xw8600              | 1        | 0.72%   |
| HP Pavilion            | 1        | 0.72%   |
| HP Desktop             | 1        | 0.72%   |
| HP CQ2930EA            | 1        | 0.72%   |
| HP 290                 | 1        | 0.72%   |
| Gigabyte Z97-D3H       | 1        | 0.72%   |
| Gigabyte Z77-D3H       | 1        | 0.72%   |
| Gigabyte Z370          | 1        | 0.72%   |
| Gigabyte M68MT-S2P     | 1        | 0.72%   |
| Gigabyte M52LT-D3P     | 1        | 0.72%   |
| Gigabyte H81M-S2PV     | 1        | 0.72%   |
| Gigabyte H61M-S1       | 1        | 0.72%   |
| Gigabyte H61M-DS2      | 1        | 0.72%   |
| Gigabyte GA-880GM-UD2H | 1        | 0.72%   |
| Gigabyte GA-78LMT-USB3 | 1        | 0.72%   |
| Gigabyte EP45C-DS3R    | 1        | 0.72%   |
| Gigabyte COMFOR        | 1        | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 19       | 13.77%  |
| 2009 | 13       | 9.42%   |
| 2014 | 12       | 8.7%    |
| 2010 | 12       | 8.7%    |
| 2008 | 11       | 7.97%   |
| 2007 | 11       | 7.97%   |
| 2018 | 10       | 7.25%   |
| 2011 | 10       | 7.25%   |
| 2019 | 9        | 6.52%   |
| 2017 | 5        | 3.62%   |
| 2013 | 5        | 3.62%   |
| 2020 | 4        | 2.9%    |
| 2006 | 4        | 2.9%    |
| 2016 | 3        | 2.17%   |
| 2005 | 3        | 2.17%   |
| 2003 | 3        | 2.17%   |
| 2015 | 2        | 1.45%   |
| 2021 | 1        | 0.72%   |
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
| Disabled | 136      | 98.55%  |
| Enabled  | 2        | 1.45%   |

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
| 8.01-16.0   | 36       | 25.53%  |
| 3.01-4.0    | 32       | 22.7%   |
| 16.01-24.0  | 24       | 17.02%  |
| 4.01-8.0    | 19       | 13.48%  |
| 32.01-64.0  | 10       | 7.09%   |
| 2.01-3.0    | 9        | 6.38%   |
| 1.01-2.0    | 6        | 4.26%   |
| 0.51-1.0    | 4        | 2.84%   |
| 64.01-256.0 | 1        | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 69       | 46.62%  |
| 2.01-3.0 | 31       | 20.95%  |
| 3.01-4.0 | 19       | 12.84%  |
| 0.51-1.0 | 18       | 12.16%  |
| 4.01-8.0 | 11       | 7.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 67       | 46.85%  |
| 2      | 46       | 32.17%  |
| 3      | 14       | 9.79%   |
| 4      | 8        | 5.59%   |
| 7      | 4        | 2.8%    |
| 5      | 2        | 1.4%    |
| 8      | 1        | 0.7%    |
| 6      | 1        | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 81       | 57.45%  |
| No        | 60       | 42.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 138      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 62.41%  |
| Yes       | 53       | 37.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 113      | 81.29%  |
| Yes       | 26       | 18.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 18       | 13.04%  |
| USA          | 17       | 12.32%  |
| Brazil       | 15       | 10.87%  |
| France       | 11       | 7.97%   |
| Canada       | 6        | 4.35%   |
| UK           | 5        | 3.62%   |
| Poland       | 5        | 3.62%   |
| Ukraine      | 4        | 2.9%    |
| Spain        | 4        | 2.9%    |
| Netherlands  | 4        | 2.9%    |
| Russia       | 3        | 2.17%   |
| Italy        | 3        | 2.17%   |
| Bulgaria     | 3        | 2.17%   |
| Belgium      | 3        | 2.17%   |
| Argentina    | 3        | 2.17%   |
| Sweden       | 2        | 1.45%   |
| Portugal     | 2        | 1.45%   |
| Hungary      | 2        | 1.45%   |
| Greece       | 2        | 1.45%   |
| Finland      | 2        | 1.45%   |
| Austria      | 2        | 1.45%   |
| Australia    | 2        | 1.45%   |
| Uruguay      | 1        | 0.72%   |
| Turkey       | 1        | 0.72%   |
| South Africa | 1        | 0.72%   |
| Slovakia     | 1        | 0.72%   |
| Serbia       | 1        | 0.72%   |
| Romania      | 1        | 0.72%   |
| Puerto Rico  | 1        | 0.72%   |
| Philippines  | 1        | 0.72%   |
| Norway       | 1        | 0.72%   |
| Mexico       | 1        | 0.72%   |
| Luxembourg   | 1        | 0.72%   |
| India        | 1        | 0.72%   |
| Estonia      | 1        | 0.72%   |
| Egypt        | 1        | 0.72%   |
| Czechia      | 1        | 0.72%   |
| Croatia      | 1        | 0.72%   |
| Colombia     | 1        | 0.72%   |
| Chile        | 1        | 0.72%   |
| Belarus      | 1        | 0.72%   |
| Bangladesh   | 1        | 0.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Paris                         | 4        | 2.76%   |
| Toronto                       | 2        | 1.38%   |
| Sofia                         | 2        | 1.38%   |
| Rio de Janeiro                | 2        | 1.38%   |
| Perth                         | 2        | 1.38%   |
| Helsinki                      | 2        | 1.38%   |
| Hamburg                       | 2        | 1.38%   |
| Belo Horizonte                | 2        | 1.38%   |
| Athens                        | 2        | 1.38%   |
| Yampil                        | 1        | 0.69%   |
| Yalta                         | 1        | 0.69%   |
| Wroclaw                       | 1        | 0.69%   |
| Wolfsburg                     | 1        | 0.69%   |
| Wernberg-Koblitz              | 1        | 0.69%   |
| Warsaw                        | 1        | 0.69%   |
| Wankheim                      | 1        | 0.69%   |
| Wakefield                     | 1        | 0.69%   |
| Vinkovci                      | 1        | 0.69%   |
| Vienna                        | 1        | 0.69%   |
| Ulm                           | 1        | 0.69%   |
| Ukhta                         | 1        | 0.69%   |
| Tubarao                       | 1        | 0.69%   |
| Tires                         | 1        | 0.69%   |
| Tingvoll                      | 1        | 0.69%   |
| Timișoara                    | 1        | 0.69%   |
| Thornton                      | 1        | 0.69%   |
| The Hague                     | 1        | 0.69%   |
| Thaur                         | 1        | 0.69%   |
| Taby                          | 1        | 0.69%   |
| São Luís                    | 1        | 0.69%   |
| Surrey                        | 1        | 0.69%   |
| Shimla                        | 1        | 0.69%   |
| Sherbrooke                    | 1        | 0.69%   |
| Seibersbach                   | 1        | 0.69%   |
| Scotby                        | 1        | 0.69%   |
| Santa Rosa                    | 1        | 0.69%   |
| San Juan                      | 1        | 0.69%   |
| San Giorgio della Richinvelda | 1        | 0.69%   |
| San Antonio                   | 1        | 0.69%   |
| Salem                         | 1        | 0.69%   |
| Saint-Brice-Courcelles        | 1        | 0.69%   |
| Rotterdam                     | 1        | 0.69%   |
| Rosario                       | 1        | 0.69%   |
| Ribeir??o Preto               | 1        | 0.69%   |
| Rhyl                          | 1        | 0.69%   |
| Rapla                         | 1        | 0.69%   |
| Radom                         | 1        | 0.69%   |
| Quilmes                       | 1        | 0.69%   |
| Puerto Vallarta               | 1        | 0.69%   |
| Presidente Prudente           | 1        | 0.69%   |
| Poznan                        | 1        | 0.69%   |
| Plovdiv                       | 1        | 0.69%   |
| Pasto                         | 1        | 0.69%   |
| Park City                     | 1        | 0.69%   |
| Paracin                       | 1        | 0.69%   |
| Osasco                        | 1        | 0.69%   |
| Offenburg                     | 1        | 0.69%   |
| Novokuybyshevsk               | 1        | 0.69%   |
| Niagara Falls                 | 1        | 0.69%   |
| Munich                        | 1        | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 52       | 89     | 23.21%  |
| Seagate             | 39       | 66     | 17.41%  |
| Samsung Electronics | 36       | 55     | 16.07%  |
| Kingston            | 12       | 15     | 5.36%   |
| Hitachi             | 12       | 15     | 5.36%   |
| Toshiba             | 11       | 17     | 4.91%   |
| SanDisk             | 8        | 12     | 3.57%   |
| Crucial             | 8        | 10     | 3.57%   |
| Phison              | 6        | 7      | 2.68%   |
| A-DATA Technology   | 6        | 6      | 2.68%   |
| Intel               | 4        | 4      | 1.79%   |
| OCZ                 | 3        | 4      | 1.34%   |
| MAXTOR              | 3        | 5      | 1.34%   |
| Intenso             | 3        | 4      | 1.34%   |
| China               | 3        | 3      | 1.34%   |
| TCSUNBOW            | 2        | 2      | 0.89%   |
| Micron Technology   | 2        | 2      | 0.89%   |
| Unknown             | 1        | 2      | 0.45%   |
| Transcend           | 1        | 1      | 0.45%   |
| Team                | 1        | 2      | 0.45%   |
| Silicon Motion      | 1        | 1      | 0.45%   |
| SABRENT             | 1        | 1      | 0.45%   |
| Patriot             | 1        | 1      | 0.45%   |
| Mushkin             | 1        | 1      | 0.45%   |
| KingSpec            | 1        | 1      | 0.45%   |
| Kingmax             | 1        | 1      | 0.45%   |
| KESU                | 1        | 2      | 0.45%   |
| HPE                 | 1        | 5      | 0.45%   |
| Fujitsu             | 1        | 1      | 0.45%   |
| ExcelStor           | 1        | 1      | 0.45%   |
| Dogfish             | 1        | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB              | 4        | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 1.52%   |
| Samsung SSD 860 EVO 500GB           | 3        | 1.14%   |
| Samsung SSD 850 EVO 250GB           | 3        | 1.14%   |
| Samsung HD322HJ 320GB               | 3        | 1.14%   |
| Samsung HD103SJ 1TB                 | 3        | 1.14%   |
| Kingston SA400S37120G 120GB SSD     | 3        | 1.14%   |
| Crucial CT240BX500SSD1 240GB        | 3        | 1.14%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2        | 0.76%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.76%   |
| WDC WD3200AAKS-00L9A0 320GB         | 2        | 0.76%   |
| WDC WD2500AAKX-753CA1 250GB         | 2        | 0.76%   |
| WDC WD1600AABS-00PRA0 160GB         | 2        | 0.76%   |
| WDC WD10EZEX-60WN4A0 1TB            | 2        | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2        | 0.76%   |
| Seagate ST500DM002-1BD142 500GB     | 2        | 0.76%   |
| Seagate ST2000LX001-1RG174 2TB      | 2        | 0.76%   |
| Seagate ST2000DM001-9YN164 2TB      | 2        | 0.76%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 0.76%   |
| Seagate Expansion 1TB               | 2        | 0.76%   |
| Samsung SSD 850 EVO 500GB           | 2        | 0.76%   |
| Samsung SP0802N 80GB                | 2        | 0.76%   |
| Samsung NVMe SSD Drive 2TB          | 2        | 0.76%   |
| Samsung NVMe SSD Drive 256GB        | 2        | 0.76%   |
| Samsung HD161HJ 160GB               | 2        | 0.76%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2        | 0.76%   |
| Kingston SV300S37A120G 120GB SSD    | 2        | 0.76%   |
| Kingston SA400S37480G 480GB SSD     | 2        | 0.76%   |
| Kingston SA400S37240G 240GB SSD     | 2        | 0.76%   |
| Crucial CT500MX500SSD1 500GB        | 2        | 0.76%   |
| A-DATA SU650 240GB SSD              | 2        | 0.76%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1        | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1        | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1        | 0.38%   |
| WDC WDS120G1G0A-00SS50 120GB SSD    | 1        | 0.38%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.38%   |
| WDC WDBNCE2500PNC 250GB SSD         | 1        | 0.38%   |
| WDC WD6400AAKS-07A7B0 640GB         | 1        | 0.38%   |
| WDC WD6002FRYZ-01WD5B1 6TB          | 1        | 0.38%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.38%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1        | 0.38%   |
| WDC WD5000BEVT-60ZAT1 500GB         | 1        | 0.38%   |
| WDC WD5000AAVS-32ZTB0 500GB         | 1        | 0.38%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1        | 0.38%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 0.38%   |
| WDC WD5000AAKX-083CA1 500GB         | 1        | 0.38%   |
| WDC WD5000AAKX-003CA0 500GB         | 1        | 0.38%   |
| WDC WD5000AAKX-001CA0 500GB         | 1        | 0.38%   |
| WDC WD5000AAKS-75A7B0 500GB         | 1        | 0.38%   |
| WDC WD5000AAKS-22A7B0 500GB         | 1        | 0.38%   |
| WDC WD5000AAKS-07A7B2 500GB         | 1        | 0.38%   |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 0.38%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 0.38%   |
| WDC WD400EB-11CPF0 40GB             | 1        | 0.38%   |
| WDC WD400EB-00CPF0 40GB             | 1        | 0.38%   |
| WDC WD360ADFD-00NLR5 37GB           | 1        | 0.38%   |
| WDC WD3200AVJS-63N9A0 320GB         | 1        | 0.38%   |
| WDC WD3200AAJS-22L7A0 320GB         | 1        | 0.38%   |
| WDC WD3200AAJS-00VWA0 320GB         | 1        | 0.38%   |
| WDC WD3200AAJS-00L7A0 320GB         | 1        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 47       | 83     | 35.07%  |
| Seagate             | 39       | 66     | 29.1%   |
| Samsung Electronics | 21       | 29     | 15.67%  |
| Hitachi             | 12       | 15     | 8.96%   |
| Toshiba             | 8        | 9      | 5.97%   |
| MAXTOR              | 3        | 5      | 2.24%   |
| Unknown             | 1        | 1      | 0.75%   |
| KESU                | 1        | 2      | 0.75%   |
| HPE                 | 1        | 5      | 0.75%   |
| Fujitsu             | 1        | 1      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 17     | 16.46%  |
| Kingston            | 11       | 14     | 13.92%  |
| SanDisk             | 8        | 12     | 10.13%  |
| Crucial             | 8        | 10     | 10.13%  |
| WDC                 | 6        | 6      | 7.59%   |
| A-DATA Technology   | 6        | 6      | 7.59%   |
| Toshiba             | 3        | 8      | 3.8%    |
| OCZ                 | 3        | 4      | 3.8%    |
| Intenso             | 3        | 4      | 3.8%    |
| Intel               | 3        | 3      | 3.8%    |
| China               | 3        | 3      | 3.8%    |
| TCSUNBOW            | 2        | 2      | 2.53%   |
| Micron Technology   | 2        | 2      | 2.53%   |
| Unknown             | 1        | 1      | 1.27%   |
| Transcend           | 1        | 1      | 1.27%   |
| Team                | 1        | 2      | 1.27%   |
| SABRENT             | 1        | 1      | 1.27%   |
| Patriot             | 1        | 1      | 1.27%   |
| KingSpec            | 1        | 1      | 1.27%   |
| Kingmax             | 1        | 1      | 1.27%   |
| Dogfish             | 1        | 1      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 105      | 216    | 57.38%  |
| SSD     | 63       | 100    | 34.43%  |
| NVMe    | 14       | 20     | 7.65%   |
| Unknown | 1        | 1      | 0.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 132      | 300    | 85.71%  |
| NVMe | 14       | 20     | 9.09%   |
| SAS  | 8        | 17     | 5.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 112      | 217    | 61.88%  |
| 0.51-1.0   | 45       | 63     | 24.86%  |
| 1.01-2.0   | 17       | 24     | 9.39%   |
| 3.01-4.0   | 3        | 8      | 1.66%   |
| 2.01-3.0   | 2        | 2      | 1.1%    |
| 4.01-10.0  | 2        | 2      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 47       | 32.41%  |
| 251-500        | 30       | 20.69%  |
| 1001-2000      | 18       | 12.41%  |
| More than 3000 | 14       | 9.66%   |
| 501-1000       | 12       | 8.28%   |
| 21-50          | 8        | 5.52%   |
| 2001-3000      | 8        | 5.52%   |
| 51-100         | 8        | 5.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 49       | 32.67%  |
| 21-50          | 33       | 22%     |
| 51-100         | 18       | 12%     |
| 251-500        | 11       | 7.33%   |
| 101-250        | 11       | 7.33%   |
| 1001-2000      | 10       | 6.67%   |
| 501-1000       | 9        | 6%      |
| More than 3000 | 5        | 3.33%   |
| 2001-3000      | 4        | 2.67%   |

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
| Detected | 126      | 302    | 87.5%   |
| Works    | 16       | 33     | 11.11%  |
| Malfunc  | 2        | 2      | 1.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 93       | 52.54%  |
| AMD                              | 28       | 15.82%  |
| Nvidia                           | 11       | 6.21%   |
| ASMedia Technology               | 9        | 5.08%   |
| JMicron Technology               | 8        | 4.52%   |
| Samsung Electronics              | 6        | 3.39%   |
| Phison Electronics               | 6        | 3.39%   |
| VIA Technologies                 | 5        | 2.82%   |
| Marvell Technology Group         | 4        | 2.26%   |
| Silicon Motion                   | 2        | 1.13%   |
| Silicon Integrated Systems [SiS] | 2        | 1.13%   |
| Silicon Image                    | 1        | 0.56%   |
| Kingston Technology Company      | 1        | 0.56%   |
| Broadcom / LSI                   | 1        | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 6.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14       | 5.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 5.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 5.35%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.29%   |
| Nvidia MCP61 SATA Controller                                                            | 7        | 2.88%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 5        | 2.06%   |
| Nvidia MCP61 IDE                                                                        | 5        | 2.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.06%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 2.06%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 2.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 2.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.06%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 1.65%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.65%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.65%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.65%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.65%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3        | 1.23%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.23%   |
| JMicron JMB368 IDE controller                                                           | 3        | 1.23%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.23%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.23%   |
| Nvidia nForce2 IDE                                                                      | 2        | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.82%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 0.82%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.82%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.82%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 0.82%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.82%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 0.82%   |
| AMD FCH IDE Controller                                                                  | 2        | 0.82%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.82%   |
| VIA Serial ATA Controller                                                               | 1        | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.41%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.41%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1        | 0.41%   |
| Silicon Integrated Systems [SiS] 182 SATA/RAID Controller                               | 1        | 0.41%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.41%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.41%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.41%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.41%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.41%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.41%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.41%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 1        | 0.41%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.41%   |
| Marvell Group 88SX7042 PCI-e 4-port SATA-II                                             | 1        | 0.41%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.41%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 90       | 51.14%  |
| IDE  | 61       | 34.66%  |
| NVMe | 14       | 7.95%   |
| RAID | 8        | 4.55%   |
| SAS  | 2        | 1.14%   |
| SCSI | 1        | 0.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 97       | 70.29%  |
| AMD    | 41       | 29.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-8100 CPU @ 3.60GHz            | 4        | 2.9%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 2.9%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.17%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2.17%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 3        | 2.17%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 3        | 2.17%   |
| Intel Pentium D CPU 2.80GHz                 | 2        | 1.45%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 1.45%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 1.45%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 1.45%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 1.45%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.45%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.45%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.45%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.45%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz       | 2        | 1.45%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.45%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.45%   |
| AMD Sempron Processor 3000+                 | 2        | 1.45%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.45%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.45%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.45%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1        | 0.72%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 0.72%   |
| Intel Xeon CPU E5472 @ 3.00GHz              | 1        | 0.72%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.72%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.72%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.72%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.72%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.72%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.72%   |
| Intel Pentium D CPU 3.20GHz                 | 1        | 0.72%   |
| Intel Pentium CPU J4205 @ 1.50GHz           | 1        | 0.72%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.72%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.72%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.72%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.72%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.72%   |
| Intel Core i9-10900T CPU @ 1.90GHz          | 1        | 0.72%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1        | 0.72%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1        | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.72%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.72%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 0.72%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 0.72%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 0.72%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 0.72%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 0.72%   |
| Intel Core i5-3450S CPU @ 2.80GHz           | 1        | 0.72%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 0.72%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 0.72%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 0.72%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1        | 0.72%   |
| Intel Core i3-2130 CPU @ 3.40GHz            | 1        | 0.72%   |
| Intel Core i3-2120T CPU @ 2.60GHz           | 1        | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 16       | 11.59%  |
| Intel Core i7           | 15       | 10.87%  |
| Intel Core 2 Duo        | 15       | 10.87%  |
| Intel Core i3           | 11       | 7.97%   |
| Intel Core 2 Quad       | 9        | 6.52%   |
| Intel Pentium           | 7        | 5.07%   |
| Intel Xeon              | 6        | 4.35%   |
| Intel Celeron           | 6        | 4.35%   |
| AMD Ryzen 7             | 5        | 3.62%   |
| AMD Ryzen 5             | 5        | 3.62%   |
| AMD Sempron             | 4        | 2.9%    |
| AMD FX                  | 4        | 2.9%    |
| AMD Athlon 64 X2        | 4        | 2.9%    |
| Intel Pentium Dual-Core | 3        | 2.17%   |
| Intel Pentium D         | 3        | 2.17%   |
| AMD Phenom II X4        | 3        | 2.17%   |
| AMD Athlon XP           | 3        | 2.17%   |
| Intel Pentium 4         | 2        | 1.45%   |
| Intel Core i9           | 2        | 1.45%   |
| Intel Core 2            | 2        | 1.45%   |
| AMD Ryzen 3             | 2        | 1.45%   |
| AMD Phenom II X6        | 2        | 1.45%   |
| AMD Athlon II X4        | 2        | 1.45%   |
| AMD Ryzen 9             | 1        | 0.72%   |
| AMD Ryzen 5 PRO         | 1        | 0.72%   |
| AMD E1                  | 1        | 0.72%   |
| AMD Athlon II X2        | 1        | 0.72%   |
| AMD Athlon              | 1        | 0.72%   |
| AMD A4                  | 1        | 0.72%   |
| AMD A10                 | 1        | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 57       | 41.3%   |
| 2      | 50       | 36.23%  |
| 1      | 11       | 7.97%   |
| 8      | 8        | 5.8%    |
| 6      | 8        | 5.8%    |
| 16     | 1        | 0.72%   |
| 12     | 1        | 0.72%   |
| 10     | 1        | 0.72%   |
| 3      | 1        | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 136      | 98.55%  |
| 2      | 2        | 1.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 89       | 64.49%  |
| 2      | 49       | 35.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 133      | 96.38%  |
| 32-bit         | 5        | 3.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 11.51%  |
| 0x1067a    | 15       | 10.79%  |
| 0x306c3    | 12       | 8.63%   |
| 0x206a7    | 12       | 8.63%   |
| 0x306a9    | 9        | 6.47%   |
| 0x10677    | 5        | 3.6%    |
| 0x906eb    | 4        | 2.88%   |
| 0x6fd      | 4        | 2.88%   |
| 0x08108109 | 4        | 2.88%   |
| 0x010000c8 | 4        | 2.88%   |
| 0x6fb      | 3        | 2.16%   |
| 0x106e5    | 3        | 2.16%   |
| 0xf65      | 2        | 1.44%   |
| 0xf64      | 2        | 1.44%   |
| 0x906ed    | 2        | 1.44%   |
| 0x906ea    | 2        | 1.44%   |
| 0x6f2      | 2        | 1.44%   |
| 0x506e3    | 2        | 1.44%   |
| 0x106a5    | 2        | 1.44%   |
| 0x10676    | 2        | 1.44%   |
| 0x08701021 | 2        | 1.44%   |
| 0x0800820d | 2        | 1.44%   |
| 0x06001119 | 2        | 1.44%   |
| 0x06000852 | 2        | 1.44%   |
| 0x0600063e | 2        | 1.44%   |
| 0x010000dc | 2        | 1.44%   |
| 0xf29      | 1        | 0.72%   |
| 0xa0655    | 1        | 0.72%   |
| 0x706a8    | 1        | 0.72%   |
| 0x506c9    | 1        | 0.72%   |
| 0x40651    | 1        | 0.72%   |
| 0x306f2    | 1        | 0.72%   |
| 0x206d7    | 1        | 0.72%   |
| 0x20655    | 1        | 0.72%   |
| 0x10661    | 1        | 0.72%   |
| 0x0a201009 | 1        | 0.72%   |
| 0x08701013 | 1        | 0.72%   |
| 0x08101102 | 1        | 0.72%   |
| 0x08101016 | 1        | 0.72%   |
| 0x0800820c | 1        | 0.72%   |
| 0x08001129 | 1        | 0.72%   |
| 0x08001126 | 1        | 0.72%   |
| 0x0700010f | 1        | 0.72%   |
| 0x05000119 | 1        | 0.72%   |
| 0x010000db | 1        | 0.72%   |
| 0x010000c7 | 1        | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 22       | 15.94%  |
| SandyBridge   | 16       | 11.59%  |
| Haswell       | 14       | 10.14%  |
| Core          | 10       | 7.25%   |
| KabyLake      | 9        | 6.52%   |
| IvyBridge     | 9        | 6.52%   |
| K10           | 8        | 5.8%    |
| Zen+          | 7        | 5.07%   |
| K8 Hammer     | 7        | 5.07%   |
| NetBurst      | 6        | 4.35%   |
| Nehalem       | 5        | 3.62%   |
| Zen           | 4        | 2.9%    |
| Piledriver    | 4        | 2.9%    |
| Zen 2         | 3        | 2.17%   |
| K6            | 3        | 2.17%   |
| Skylake       | 2        | 1.45%   |
| Bulldozer     | 2        | 1.45%   |
| Zen 3         | 1        | 0.72%   |
| Westmere      | 1        | 0.72%   |
| Jaguar        | 1        | 0.72%   |
| Goldmont plus | 1        | 0.72%   |
| Goldmont      | 1        | 0.72%   |
| CometLake     | 1        | 0.72%   |
| Bobcat        | 1        | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 60       | 40.54%  |
| Intel             | 50       | 33.78%  |
| AMD               | 32       | 21.62%  |
| VIA Technologies  | 4        | 2.7%    |
| S3 Graphics       | 1        | 0.68%   |
| ASPEED Technology | 1        | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13       | 8.44%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 7        | 4.55%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 6        | 3.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 6        | 3.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 6        | 3.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 6        | 3.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 5        | 3.25%   |
| Nvidia GT218 [GeForce 210]                                                    | 4        | 2.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4        | 2.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4        | 2.6%    |
| Nvidia GK208B [GeForce GT 710]                                                | 3        | 1.95%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 3        | 1.95%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 2        | 1.3%    |
| Nvidia GP107 [GeForce GTX 1050]                                               | 2        | 1.3%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 2        | 1.3%    |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2        | 1.3%    |
| Nvidia GK104 [GeForce GTX 760]                                                | 2        | 1.3%    |
| Nvidia GF104 [GeForce GTX 460]                                                | 2        | 1.3%    |
| Nvidia G86 [GeForce 8400 GS]                                                  | 2        | 1.3%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                       | 2        | 1.3%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 2        | 1.3%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2        | 1.3%    |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                    | 1        | 0.65%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                     | 1        | 0.65%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 1        | 0.65%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.65%   |
| S3 Graphics VT8375 [ProSavage8 KM266/KL266]                                   | 1        | 0.65%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 1        | 0.65%   |
| Nvidia NV44 [GeForce 6200 TurboCache]                                         | 1        | 0.65%   |
| Nvidia NV43 [GeForce 6600]                                                    | 1        | 0.65%   |
| Nvidia NV36 [GeForce FX 5700VE]                                               | 1        | 0.65%   |
| Nvidia NV34 [GeForce FX 5200]                                                 | 1        | 0.65%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                         | 1        | 0.65%   |
| Nvidia GT218 [GeForce 310]                                                    | 1        | 0.65%   |
| Nvidia GT200 [GeForce GTX 260]                                                | 1        | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1        | 0.65%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 1        | 0.65%   |
| Nvidia GK208B [GeForce GT 730]                                                | 1        | 0.65%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 1        | 0.65%   |
| Nvidia GK104 [GeForce GTX 660 OEM]                                            | 1        | 0.65%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                             | 1        | 0.65%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                         | 1        | 0.65%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                             | 1        | 0.65%   |
| Nvidia GF108 [GeForce GT 730]                                                 | 1        | 0.65%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1        | 0.65%   |
| Nvidia GF108 [GeForce GT 420]                                                 | 1        | 0.65%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1        | 0.65%   |
| Nvidia G96GL [Quadro FX 380]                                                  | 1        | 0.65%   |
| Nvidia G96C [GeForce 9500 GT]                                                 | 1        | 0.65%   |
| Nvidia G96C [GeForce 9400 GT]                                                 | 1        | 0.65%   |
| Nvidia G94 [GeForce 9600 GT]                                                  | 1        | 0.65%   |
| Nvidia G92 [GeForce GTS 250]                                                  | 1        | 0.65%   |
| Nvidia G73 [GeForce 7600 GS]                                                  | 1        | 0.65%   |
| Nvidia C73 [GeForce 7100 / nForce 620i]                                       | 1        | 0.65%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                          | 1        | 0.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1        | 0.65%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 1        | 0.65%   |
| Intel HD Graphics 510                                                         | 1        | 0.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1        | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 56       | 40.29%  |
| 1 x Intel       | 41       | 29.5%   |
| 1 x AMD         | 29       | 20.86%  |
| 1 x VIA         | 4        | 2.88%   |
| 2 x AMD         | 3        | 2.16%   |
| Intel + Nvidia  | 3        | 2.16%   |
| 2 x Nvidia      | 1        | 0.72%   |
| 1 x S3 Graphics | 1        | 0.72%   |
| 1 x ASPEED      | 1        | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 93       | 66.43%  |
| Proprietary | 26       | 18.57%  |
| Unknown     | 21       | 15%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 64       | 45.71%  |
| 0.51-1.0   | 21       | 15%     |
| 0.01-0.5   | 19       | 13.57%  |
| 1.01-2.0   | 13       | 9.29%   |
| 3.01-4.0   | 11       | 7.86%   |
| 7.01-8.0   | 9        | 6.43%   |
| 2.01-3.0   | 2        | 1.43%   |
| 5.01-6.0   | 1        | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 28       | 18.42%  |
| Goldstar                | 15       | 9.87%   |
| Dell                    | 15       | 9.87%   |
| Acer                    | 14       | 9.21%   |
| Ancor Communications    | 9        | 5.92%   |
| AOC                     | 7        | 4.61%   |
| Unknown                 | 6        | 3.95%   |
| Philips                 | 6        | 3.95%   |
| Hewlett-Packard         | 5        | 3.29%   |
| BenQ                    | 5        | 3.29%   |
| Sony                    | 3        | 1.97%   |
| Lenovo                  | 3        | 1.97%   |
| Iiyama                  | 3        | 1.97%   |
| Fujitsu Siemens         | 3        | 1.97%   |
| Sceptre Tech            | 2        | 1.32%   |
| NEC Computers           | 2        | 1.32%   |
| LG Electronics          | 2        | 1.32%   |
| ___                     | 1        | 0.66%   |
| Vestel                  | 1        | 0.66%   |
| Toshiba                 | 1        | 0.66%   |
| Targa Visionary         | 1        | 0.66%   |
| OEM                     | 1        | 0.66%   |
| NCS                     | 1        | 0.66%   |
| Mitsubishi              | 1        | 0.66%   |
| Microstep               | 1        | 0.66%   |
| Medion                  | 1        | 0.66%   |
| IBM                     | 1        | 0.66%   |
| Hitachi                 | 1        | 0.66%   |
| eMachines               | 1        | 0.66%   |
| ELSA International      | 1        | 0.66%   |
| Elo Touch               | 1        | 0.66%   |
| ELO                     | 1        | 0.66%   |
| Eizo                    | 1        | 0.66%   |
| DENON                   | 1        | 0.66%   |
| Compal                  | 1        | 0.66%   |
| Chi Mei Optoelectronics | 1        | 0.66%   |
| Belinea                 | 1        | 0.66%   |
| AUS                     | 1        | 0.66%   |
| ASUSTek Computer        | 1        | 0.66%   |
| AOpen                   | 1        | 0.66%   |
| AGO                     | 1        | 0.66%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch     | 2        | 1.27%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                       | 2        | 1.27%   |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch                   | 1        | 0.64%   |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                               | 1        | 0.64%   |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                      | 1        | 0.64%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.64%   |
| Unknown LCD Monitor SAMSUNG                                             | 1        | 0.64%   |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                       | 1        | 0.64%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                                | 1        | 0.64%   |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch                  | 1        | 0.64%   |
| Toshiba LCD Monitor TV 1920x1080                                        | 1        | 0.64%   |
| Targa Visionary LCD19-4 TARA194 1280x1024 376x301mm 19.0-inch           | 1        | 0.64%   |
| Sony TV SNY4C03 1920x1080 1063x598mm 48.0-inch                          | 1        | 0.64%   |
| Sony TV SNY1B02 1360x768 1600x900mm 72.3-inch                           | 1        | 0.64%   |
| Sony LCD Monitor TV 3840x1080                                           | 1        | 0.64%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                  | 1        | 0.64%   |
| Sceptre Tech F24 SPT0961 1920x1080 480x260mm 21.5-inch                  | 1        | 0.64%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch       | 1        | 0.64%   |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch       | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch     | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 459x296mm 21.5-inch    | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM034F 1440x900 428x255mm 19.6-inch     | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0303 1680x1050 494x320mm 23.2-inch    | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch    | 1        | 0.64%   |
| Samsung Electronics SyncMaster SAM006E 1280x1024 338x270mm 17.0-inch    | 1        | 0.64%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch    | 1        | 0.64%   |
| Samsung Electronics SMS22A200/460 SAM0831 1920x1080 477x268mm 21.5-inch | 1        | 0.64%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch      | 1        | 0.64%   |
| Samsung Electronics SMB2230 SAM063E 1920x1080 477x268mm 21.5-inch       | 1        | 0.64%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch       | 1        | 0.64%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 1        | 0.64%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.64%   |
| Samsung Electronics S24D360 SAM0B24 1920x1080 521x293mm 23.5-inch       | 1        | 0.64%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1        | 0.64%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch       | 1        | 0.64%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1        | 0.64%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch       | 1        | 0.64%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch        | 1        | 0.64%   |
| Samsung Electronics S16B110 SAM097E 1366x768 360x210mm 16.4-inch        | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SAM0F39 1920x1080 1210x680mm 54.6-inch  | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SAM08FE 1920x1080                       | 1        | 0.64%   |
| Samsung Electronics LCD Monitor SA300/SA350 1920x1080                   | 1        | 0.64%   |
| Samsung Electronics LCD Monitor S22B350 1920x1080                       | 1        | 0.64%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch       | 1        | 0.64%   |
| Philips PHL 288E2 PHLC231 3840x2160 621x341mm 27.9-inch                 | 1        | 0.64%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 530x300mm 24.0-inch                 | 1        | 0.64%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 1        | 0.64%   |
| Philips LCD Monitor PHL 498P9 1920x1080                                 | 1        | 0.64%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                     | 1        | 0.64%   |
| Philips 170B PHL081D 1280x1024 338x270mm 17.0-inch                      | 1        | 0.64%   |
| OEM LCD Monitor 46W_LCD_TV 1920x1080                                    | 1        | 0.64%   |
| NEC Computers LCD73V NEC66C2 1280x1024 338x270mm 17.0-inch              | 1        | 0.64%   |
| NEC Computers LCD1810X NEC6594 1280x1024 359x287mm 18.1-inch            | 1        | 0.64%   |
| NCS LCD Monitor NCS2275 1920x1080 300x230mm 14.9-inch                   | 1        | 0.64%   |
| Mitsubishi DiamondPlus73 MEL4460 1280x1024 310x232mm 15.2-inch          | 1        | 0.64%   |
| Microstep LCD Monitor MSI PS341WU 7680x2160                             | 1        | 0.64%   |
| Medion MD 20144 MED3636 1920x1080 510x287mm 23.0-inch                   | 1        | 0.64%   |
| LG Electronics LCD Monitor LG TV 1360x768                               | 1        | 0.64%   |
| LG Electronics LCD Monitor 27EA53 1920x1080                             | 1        | 0.64%   |
| Lenovo LCD Monitor LEN1421 1366x768 310x170mm 13.9-inch                 | 1        | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 65       | 44.83%  |
| 1280x1024 (SXGA)   | 27       | 18.62%  |
| 1440x900 (WXGA+)   | 9        | 6.21%   |
| 1680x1050 (WSXGA+) | 8        | 5.52%   |
| 1366x768 (WXGA)    | 6        | 4.14%   |
| 1920x1200 (WUXGA)  | 5        | 3.45%   |
| 3840x2160 (4K)     | 4        | 2.76%   |
| 1360x768           | 4        | 2.76%   |
| 1024x768 (XGA)     | 4        | 2.76%   |
| 1600x900 (HD+)     | 3        | 2.07%   |
| Unknown            | 3        | 2.07%   |
| 3440x1440          | 2        | 1.38%   |
| 7680x2160          | 1        | 0.69%   |
| 4240x1440          | 1        | 0.69%   |
| 3840x1080          | 1        | 0.69%   |
| 2560x1440 (QHD)    | 1        | 0.69%   |
| 1600x1200          | 1        | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 14.77%  |
| 21      | 18       | 12.08%  |
| 19      | 15       | 10.07%  |
| 17      | 15       | 10.07%  |
| 24      | 14       | 9.4%    |
| 23      | 13       | 8.72%   |
| 27      | 11       | 7.38%   |
| 18      | 11       | 7.38%   |
| 15      | 7        | 4.7%    |
| 22      | 6        | 4.03%   |
| 31      | 3        | 2.01%   |
| 20      | 3        | 2.01%   |
| 72      | 1        | 0.67%   |
| 54      | 1        | 0.67%   |
| 52      | 1        | 0.67%   |
| 48      | 1        | 0.67%   |
| 33      | 1        | 0.67%   |
| 32      | 1        | 0.67%   |
| 26      | 1        | 0.67%   |
| 16      | 1        | 0.67%   |
| 14      | 1        | 0.67%   |
| 13      | 1        | 0.67%   |
| 12      | 1        | 0.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 44       | 30.14%  |
| 501-600     | 34       | 23.29%  |
| 301-350     | 22       | 15.07%  |
| Unknown     | 22       | 15.07%  |
| 351-400     | 12       | 8.22%   |
| 601-700     | 4        | 2.74%   |
| 1001-1500   | 3        | 2.05%   |
| 701-800     | 2        | 1.37%   |
| 201-300     | 2        | 1.37%   |
| 1501-2000   | 1        | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 67       | 46.85%  |
| 5/4     | 23       | 16.08%  |
| 16/10   | 21       | 14.69%  |
| Unknown | 21       | 14.69%  |
| 4/3     | 9        | 6.29%   |
| 3/2     | 1        | 0.7%    |
| 21/9    | 1        | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 39       | 26.35%  |
| 151-200        | 28       | 18.92%  |
| Unknown        | 22       | 14.86%  |
| 141-150        | 21       | 14.19%  |
| 301-350        | 12       | 8.11%   |
| 101-110        | 7        | 4.73%   |
| 251-300        | 6        | 4.05%   |
| 351-500        | 5        | 3.38%   |
| More than 1000 | 3        | 2.03%   |
| 111-120        | 2        | 1.35%   |
| 81-90          | 1        | 0.68%   |
| 71-80          | 1        | 0.68%   |
| 501-1000       | 1        | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 88       | 63.31%  |
| Unknown | 22       | 15.83%  |
| 101-120 | 21       | 15.11%  |
| 1-50    | 4        | 2.88%   |
| 121-160 | 3        | 2.16%   |
| 161-240 | 1        | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 114      | 81.43%  |
| 2     | 20       | 14.29%  |
| 0     | 5        | 3.57%   |
| 3     | 1        | 0.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 84       | 43.3%   |
| Intel                            | 37       | 19.07%  |
| Qualcomm Atheros                 | 20       | 10.31%  |
| Ralink Technology                | 9        | 4.64%   |
| Nvidia                           | 9        | 4.64%   |
| Broadcom                         | 6        | 3.09%   |
| VIA Technologies                 | 4        | 2.06%   |
| TP-Link                          | 4        | 2.06%   |
| Marvell Technology Group         | 3        | 1.55%   |
| Broadcom Limited                 | 2        | 1.03%   |
| AVM                              | 2        | 1.03%   |
| Sitecom Europe                   | 1        | 0.52%   |
| Silicon Integrated Systems [SiS] | 1        | 0.52%   |
| Samsung Electronics              | 1        | 0.52%   |
| Ralink                           | 1        | 0.52%   |
| Microsoft                        | 1        | 0.52%   |
| Mellanox Technologies            | 1        | 0.52%   |
| LSI                              | 1        | 0.52%   |
| JMicron Technology               | 1        | 0.52%   |
| Huawei Technologies              | 1        | 0.52%   |
| Edimax Technology                | 1        | 0.52%   |
| DisplayLink                      | 1        | 0.52%   |
| Belkin Components                | 1        | 0.52%   |
| ASUSTek Computer                 | 1        | 0.52%   |
| ADMtek                           | 1        | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 62       | 28.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 8        | 3.72%   |
| Nvidia MCP61 Ethernet                                                                         | 7        | 3.26%   |
| Intel I211 Gigabit Network Connection                                                         | 6        | 2.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 5        | 2.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 4        | 1.86%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4        | 1.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 1.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 1.4%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                                    | 3        | 1.4%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                                 | 3        | 1.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 3        | 1.4%    |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 1.4%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 2        | 0.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 0.93%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 0.93%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2        | 0.93%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 2        | 0.93%   |
| Nvidia nForce2 Ethernet Controller                                                            | 2        | 0.93%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 2        | 0.93%   |
| Intel Ethernet Connection I217-V                                                              | 2        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                                                          | 2        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 0.93%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 0.93%   |
| Intel 82574L Gigabit Network Connection                                                       | 2        | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 2        | 0.93%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2        | 0.93%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.47%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 0.47%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 0.47%   |
| Sitecom Europe RTL8188S WLAN Adapter                                                          | 1        | 0.47%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                                     | 1        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1        | 0.47%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.47%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 0.47%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 0.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1        | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1        | 0.47%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 0.47%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.47%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 0.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 0.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 0.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1        | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1        | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                | 1        | 0.47%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 0.47%   |
| Mellanox MT23108 InfiniHost                                                                   | 1        | 0.47%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                                       | 1        | 0.47%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                             | 1        | 0.47%   |
| LSI 56k WinModem                                                                              | 1        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 25.42%  |
| Intel                 | 10       | 16.95%  |
| Ralink Technology     | 9        | 15.25%  |
| Qualcomm Atheros      | 9        | 15.25%  |
| TP-Link               | 4        | 6.78%   |
| Broadcom              | 3        | 5.08%   |
| AVM                   | 2        | 3.39%   |
| Sitecom Europe        | 1        | 1.69%   |
| Ralink                | 1        | 1.69%   |
| Microsoft             | 1        | 1.69%   |
| Edimax Technology     | 1        | 1.69%   |
| Broadcom Limited      | 1        | 1.69%   |
| Belkin Components     | 1        | 1.69%   |
| ASUSTek Computer      | 1        | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                               | 4        | 6.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 5.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 5.08%   |
| Intel Wi-Fi 6 AX200                                                                           | 3        | 5.08%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 2        | 3.39%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 3.39%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 3.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 3.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 3.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2        | 3.39%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 2        | 3.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 3.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 1.69%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 1.69%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 1.69%   |
| Sitecom Europe RTL8188S WLAN Adapter                                                          | 1        | 1.69%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 1.69%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 1.69%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 1.69%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.69%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 1.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.69%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 1.69%   |
| Intel Wireless 8265 / 8275                                                                    | 1        | 1.69%   |
| Intel Wireless 7265                                                                           | 1        | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1        | 1.69%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 1.69%   |
| Intel Centrino Wireless-N 105                                                                 | 1        | 1.69%   |
| Edimax AC600 USB                                                                              | 1        | 1.69%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 1.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1        | 1.69%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1        | 1.69%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller                           | 1        | 1.69%   |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU]                   | 1        | 1.69%   |
| AVM Fritz!WLAN N [Atheros AR9001U]                                                            | 1        | 1.69%   |
| AVM FRITZ!WLAN AC 860                                                                         | 1        | 1.69%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                           | 1        | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 79       | 53.02%  |
| Intel                            | 33       | 22.15%  |
| Qualcomm Atheros                 | 11       | 7.38%   |
| Nvidia                           | 9        | 6.04%   |
| VIA Technologies                 | 4        | 2.68%   |
| Marvell Technology Group         | 3        | 2.01%   |
| Broadcom                         | 3        | 2.01%   |
| Silicon Integrated Systems [SiS] | 1        | 0.67%   |
| Samsung Electronics              | 1        | 0.67%   |
| JMicron Technology               | 1        | 0.67%   |
| Huawei Technologies              | 1        | 0.67%   |
| DisplayLink                      | 1        | 0.67%   |
| Broadcom Limited                 | 1        | 0.67%   |
| ADMtek                           | 1        | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62       | 40.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8        | 5.19%   |
| Nvidia MCP61 Ethernet                                             | 7        | 4.55%   |
| Intel I211 Gigabit Network Connection                             | 6        | 3.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 3.25%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.6%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 1.95%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 1.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 1.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.3%    |
| Nvidia nForce2 Ethernet Controller                                | 2        | 1.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 2        | 1.3%    |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.3%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.3%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.3%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.3%    |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.65%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1        | 0.65%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.65%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.65%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.65%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.65%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.65%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.65%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.65%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.65%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.65%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 0.65%   |
| Intel 82544EI Gigabit Ethernet Controller (Copper)                | 1        | 0.65%   |
| Huawei SNE-LX1                                                    | 1        | 0.65%   |
| DisplayLink Plugable UD-3900                                      | 1        | 0.65%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.65%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 0.65%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.65%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 0.65%   |
| ADMtek AN8515 Ethernet                                            | 1        | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 138      | 71.5%   |
| WiFi     | 53       | 27.46%  |
| Modem    | 1        | 0.52%   |
| Unknown  | 1        | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 135      | 76.27%  |
| WiFi     | 42       | 23.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 94       | 68.12%  |
| 2     | 40       | 28.99%  |
| 3     | 3        | 2.17%   |
| 4     | 1        | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 121      | 83.45%  |
| Yes  | 24       | 16.55%  |

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
| Intel Bluetooth Device                              | 5        | 18.52%  |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 7.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 7.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 7.41%   |
| Realtek Bluetooth Radio                             | 1        | 3.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 3.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 3.7%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 3.7%    |
| Intel Bluetooth wireless interface                  | 1        | 3.7%    |
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
| Intel                            | 84       | 40.19%  |
| Nvidia                           | 52       | 24.88%  |
| AMD                              | 37       | 17.7%   |
| C-Media Electronics              | 9        | 4.31%   |
| VIA Technologies                 | 7        | 3.35%   |
| Creative Labs                    | 4        | 1.91%   |
| Silicon Integrated Systems [SiS] | 2        | 0.96%   |
| Logitech                         | 2        | 0.96%   |
| GN Netcom                        | 2        | 0.96%   |
| Generalplus Technology           | 2        | 0.96%   |
| Yamaha                           | 1        | 0.48%   |
| Xilinx                           | 1        | 0.48%   |
| M-Audio                          | 1        | 0.48%   |
| JMTek                            | 1        | 0.48%   |
| GYROCOM C&C                      | 1        | 0.48%   |
| Focusrite-Novation               | 1        | 0.48%   |
| Evolution Electronics            | 1        | 0.48%   |
| Creative Technology              | 1        | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 17       | 7.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 14       | 6.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 10       | 4.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 8        | 3.43%   |
| Nvidia MCP61 High Definition Audio                                          | 7        | 3%      |
| Nvidia High Definition Audio Controller                                     | 6        | 2.58%   |
| Nvidia GP107GL High Definition Audio Controller                             | 6        | 2.58%   |
| Nvidia GM206 High Definition Audio Controller                               | 6        | 2.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 6        | 2.58%   |
| Intel Cannon Lake PCH cAVS                                                  | 6        | 2.58%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 6        | 2.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 6        | 2.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 6        | 2.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 6        | 2.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 6        | 2.58%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                               | 5        | 2.15%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                         | 5        | 2.15%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                   | 4        | 1.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 4        | 1.72%   |
| Intel 9 Series Chipset Family HD Audio Controller                           | 4        | 1.72%   |
| AMD Starship/Matisse HD Audio Controller                                    | 4        | 1.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 4        | 1.72%   |
| Nvidia TU106 High Definition Audio Controller                               | 3        | 1.29%   |
| Nvidia GP106 High Definition Audio Controller                               | 3        | 1.29%   |
| Nvidia GK104 HDMI Audio Controller                                          | 3        | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                               | 3        | 1.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 3        | 1.29%   |
| AMD FCH Azalia Controller                                                   | 3        | 1.29%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 3        | 1.29%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller             | 2        | 0.86%   |
| Nvidia nForce2 AC97 Audio Controler (MCP)                                   | 2        | 0.86%   |
| Nvidia GP104 High Definition Audio Controller                               | 2        | 0.86%   |
| Nvidia GF116 High Definition Audio Controller                               | 2        | 0.86%   |
| Nvidia GF104 High Definition Audio Controller                               | 2        | 0.86%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 2        | 0.86%   |
| Intel 200 Series PCH HD Audio                                               | 2        | 0.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 2        | 0.86%   |
| Generalplus Technology Usb Audio Device                                     | 2        | 0.86%   |
| Yamaha AG06/AG03                                                            | 1        | 0.43%   |
| Xilinx RME Hammerfall DSP                                                   | 1        | 0.43%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller              | 1        | 0.43%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.43%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller          | 1        | 0.43%   |
| Nvidia MCP73 High Definition Audio                                          | 1        | 0.43%   |
| Nvidia MCP51 High Definition Audio                                          | 1        | 0.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 1        | 0.43%   |
| Nvidia GK107 HDMI Audio Controller                                          | 1        | 0.43%   |
| Nvidia GF114 HDMI Audio Controller                                          | 1        | 0.43%   |
| M-Audio M-Audio Fast Track                                                  | 1        | 0.43%   |
| Logitech QuickCam Fusion                                                    | 1        | 0.43%   |
| Logitech G430 Surround Sound Gaming Headset                                 | 1        | 0.43%   |
| JMTek USB PnP Audio Device                                                  | 1        | 0.43%   |
| Intel Haswell-ULT HD Audio Controller                                       | 1        | 0.43%   |
| Intel Comet Lake PCH cAVS                                                   | 1        | 0.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                | 1        | 0.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster           | 1        | 0.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                      | 1        | 0.43%   |
| Intel C610/X99 series chipset HD Audio Controller                           | 1        | 0.43%   |
| Intel C600/X79 series chipset High Definition Audio Controller              | 1        | 0.43%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller           | 1        | 0.43%   |

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


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 667MT/s                      | 1        | 4.55%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s               | 1        | 4.55%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 1        | 4.55%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                   | 1        | 4.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1        | 4.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                | 1        | 4.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                | 1        | 4.55%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                     | 1        | 4.55%   |
| Unknown RAM Module 1024MB DIMM                             | 1        | 4.55%   |
| SK Hynix RAM Module 8192MB DIMM DDR4 2400MT/s              | 1        | 4.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 1        | 4.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1        | 4.55%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s        | 1        | 4.55%   |
| PLEXHD RAM Module 8192MB DIMM DDR3 1333MT/s                | 1        | 4.55%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s     | 1        | 4.55%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s             | 1        | 4.55%   |
| Kingston RAM KHX3600C17D4/16GX 16GB DIMM DDR4 3800MT/s     | 1        | 4.55%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s     | 1        | 4.55%   |
| Exceleram RAM E30144A 4096MB DIMM DDR3 800MT/s             | 1        | 4.55%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s | 1        | 4.55%   |
| Crucial RAM BLT8G4D26BFT4K.C8FD 8GB DIMM DDR4 2666MT/s     | 1        | 4.55%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s   | 1        | 4.55%   |

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
| Logitech                      | 6        | 33.33%  |
| Microsoft                     | 3        | 16.67%  |
| Xiongmai                      | 1        | 5.56%   |
| WCM_USB                       | 1        | 5.56%   |
| Sunplus Innovation Technology | 1        | 5.56%   |
| Service & Quality Technology  | 1        | 5.56%   |
| Nintendo                      | 1        | 5.56%   |
| Microdia                      | 1        | 5.56%   |
| KYE Systems (Mouse Systems)   | 1        | 5.56%   |
| Generalplus Technology        | 1        | 5.56%   |
| Chicony Electronics           | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Logitech Webcam C270                               | 3        | 16.67%  |
| Microsoft LifeCam HD-3000                          | 2        | 11.11%  |
| Xiongmai web camera                                | 1        | 5.56%   |
| WCM_USB WEB CAM                                    | 1        | 5.56%   |
| Sunplus Full HD webcam                             | 1        | 5.56%   |
| Service & Quality USB PC Camera                    | 1        | 5.56%   |
| Nintendo USB Camera                                | 1        | 5.56%   |
| Microsoft Microsoft?� LifeCam VX-5500              | 1        | 5.56%   |
| Microdia Webcam Vitade AF                          | 1        | 5.56%   |
| Logitech Webcam Pro 9000                           | 1        | 5.56%   |
| Logitech Webcam C310                               | 1        | 5.56%   |
| Logitech HD Pro Webcam C920                        | 1        | 5.56%   |
| KYE Systems (Mouse Systems) Genius iSlim 2000AF V2 | 1        | 5.56%   |
| Generalplus 808 Camera                             | 1        | 5.56%   |
| Chicony HP High Definition 1MP Webcam              | 1        | 5.56%   |

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
| 0     | 99       | 70.71%  |
| 1     | 35       | 25%     |
| 2     | 3        | 2.14%   |
| 4     | 2        | 1.43%   |
| 3     | 1        | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 24       | 51.06%  |
| Net/wireless             | 11       | 23.4%   |
| Communication controller | 4        | 8.51%   |
| Net/ethernet             | 2        | 4.26%   |
| Unassigned class         | 1        | 2.13%   |
| Storage/ide              | 1        | 2.13%   |
| Network                  | 1        | 2.13%   |
| Modem                    | 1        | 2.13%   |
| Fingerprint reader       | 1        | 2.13%   |
| Chipcard                 | 1        | 2.13%   |

