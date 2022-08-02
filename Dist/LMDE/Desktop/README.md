LMDE - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for LMDE.

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

Total: 280

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | H61M-DGS                    | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Gigabyte      | B450 AORUS M                | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| Gigabyte      | B450 AORUS M                | [aca8d98967](https://linux-hardware.org/?probe=aca8d98967) | Jul 18, 2022 |
| HP            | 8433 11                     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| ASUSTek       | P5B                         | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
| Gigabyte      | B450 AORUS M                | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| ASUSTek       | P8H77-M PRO                 | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Dell          | 0XR1GT A00                  | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| Lenovo        | 3731 NOK                    | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| Dell          | 0XR1GT A00                  | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo        | MAHOBAY                     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| Acer          | Seawolf                     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| Intel         | DQ77MK AAG39642-400         | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| ASUSTek       | P5QL PRO                    | [9ea782b1d2](https://linux-hardware.org/?probe=9ea782b1d2) | May 08, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| HP            | 339A                        | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Gigabyte      | H110M-S2H-CF                | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Dell          | 0XR1GT A00                  | [2a3b9ad6cf](https://linux-hardware.org/?probe=2a3b9ad6cf) | Apr 24, 2022 |
| ASRock        | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Foxconn       | Cinema Series FAB           | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [eb751efc1f](https://linux-hardware.org/?probe=eb751efc1f) | Apr 09, 2022 |
| Acer          | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| ASUSTek       | P6T                         | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Acer          | EG43M                       | [28b4dd5236](https://linux-hardware.org/?probe=28b4dd5236) | Mar 31, 2022 |
| ASUSTek       | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [346857be22](https://linux-hardware.org/?probe=346857be22) | Mar 24, 2022 |
| ASUSTek       | P4P800                      | [0cb6a89491](https://linux-hardware.org/?probe=0cb6a89491) | Mar 19, 2022 |
| HP            | 0AA8h                       | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| HP            | 0AE8h C                     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Dell          | 0HR330                      | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell          | 0HR330                      | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| HP            | 0AA8h                       | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| Gigabyte      | Z77-D3H                     | [a0d52488b2](https://linux-hardware.org/?probe=a0d52488b2) | Feb 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [0731118682](https://linux-hardware.org/?probe=0731118682) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [5026ea812a](https://linux-hardware.org/?probe=5026ea812a) | Feb 15, 2022 |
| Dell          | 0Y2K8N A01                  | [e3922aecf0](https://linux-hardware.org/?probe=e3922aecf0) | Feb 04, 2022 |
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
| Intel         | D34010WYK H14771-303        | [0c19bbe87a](https://linux-hardware.org/?probe=0c19bbe87a) | Feb 18, 2020 |
| HP            | ProLiant MicroServer        | [363851a935](https://linux-hardware.org/?probe=363851a935) | Dec 19, 2019 |
| HP            | ProLiant MicroServer        | [708dff507f](https://linux-hardware.org/?probe=708dff507f) | Dec 19, 2019 |
| Dell          | OptiPlex GX620              | [21f221a304](https://linux-hardware.org/?probe=21f221a304) | May 17, 2019 |
| Dell          | OptiPlex GX620              | [3e9258a7c5](https://linux-hardware.org/?probe=3e9258a7c5) | Apr 15, 2019 |
| Dell          | OptiPlex GX620              | [87babb0fa3](https://linux-hardware.org/?probe=87babb0fa3) | Apr 15, 2019 |
| Gigabyte      | 945GCM-S2L                  | [d950de89e7](https://linux-hardware.org/?probe=d950de89e7) | Mar 26, 2019 |
| Gigabyte      | 970A-UD3P                   | [d425ca175b](https://linux-hardware.org/?probe=d425ca175b) | Oct 11, 2018 |
| Intel         | DG31PR AAD97573-205         | [693096a808](https://linux-hardware.org/?probe=693096a808) | Sep 06, 2018 |
| ASUSTek       | P8Z77-V                     | [bcdb9633d9](https://linux-hardware.org/?probe=bcdb9633d9) | Sep 05, 2018 |
| Foxconn       | 945 7MA Series              | [95d9e1dba9](https://linux-hardware.org/?probe=95d9e1dba9) | Nov 14, 2017 |
| ASUSTek       | H61M-K                      | [78a1c15c22](https://linux-hardware.org/?probe=78a1c15c22) | Sep 09, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| LMDE 4 | 148      | 79.57%  |
| LMDE 5 | 28       | 15.05%  |
| LMDE 3 | 8        | 4.3%    |
| LMDE 2 | 2        | 1.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| LMDE | 185      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 4.19.0-16-amd64      | 23       | 11.22%  |
| 4.19.0-18-amd64      | 19       | 9.27%   |
| 4.19.0-17-amd64      | 19       | 9.27%   |
| 4.19.0-14-amd64      | 18       | 8.78%   |
| 4.19.0-13-amd64      | 17       | 8.29%   |
| 4.19.0-8-amd64       | 15       | 7.32%   |
| 5.10.0-14-amd64      | 10       | 4.88%   |
| 5.10.0-13-amd64      | 10       | 4.88%   |
| 4.19.0-12-amd64      | 9        | 4.39%   |
| 4.19.0-10-amd64      | 8        | 3.9%    |
| 4.19.0-9-amd64       | 7        | 3.41%   |
| 5.10.0-12-amd64      | 5        | 2.44%   |
| 4.9.0-8-amd64        | 4        | 1.95%   |
| 4.19.0-11-amd64      | 4        | 1.95%   |
| 4.19.0-17-686        | 3        | 1.46%   |
| 4.19.0-16-686        | 3        | 1.46%   |
| 4.19.0-14-686        | 3        | 1.46%   |
| 5.10.0-15-amd64      | 2        | 0.98%   |
| 4.19.0-8-686         | 2        | 0.98%   |
| 4.19.0-20-amd64      | 2        | 0.98%   |
| 4.19.0-19-686        | 2        | 0.98%   |
| 4.19.0-18-686        | 2        | 0.98%   |
| 4.19.0-13-686        | 2        | 0.98%   |
| 3.16.0-4-amd64       | 2        | 0.98%   |
| 5.8.0-3-amd64        | 1        | 0.49%   |
| 5.6.0-0.bpo.2-amd64  | 1        | 0.49%   |
| 5.4.0-0.bpo.4-amd64  | 1        | 0.49%   |
| 5.10.0-7-amd64       | 1        | 0.49%   |
| 5.10.0-16-amd64      | 1        | 0.49%   |
| 5.10.0-13-686        | 1        | 0.49%   |
| 4.9.0-9-amd64        | 1        | 0.49%   |
| 4.9.0-17-amd64       | 1        | 0.49%   |
| 4.9.0-11-amd64       | 1        | 0.49%   |
| 4.19.0-9-686         | 1        | 0.49%   |
| 4.19.0-21-amd64      | 1        | 0.49%   |
| 4.19.0-19-amd64      | 1        | 0.49%   |
| 4.19.0-12-686        | 1        | 0.49%   |
| 4.17.0-0.bpo.3-amd64 | 1        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 144      | 77.42%  |
| 5.10.0  | 29       | 15.59%  |
| 4.9.0   | 7        | 3.76%   |
| 3.16.0  | 2        | 1.08%   |
| 5.8.0   | 1        | 0.54%   |
| 5.6.0   | 1        | 0.54%   |
| 5.4.0   | 1        | 0.54%   |
| 4.17.0  | 1        | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 144      | 77.42%  |
| 5.10    | 29       | 15.59%  |
| 4.9     | 7        | 3.76%   |
| 3.16    | 2        | 1.08%   |
| 5.8     | 1        | 0.54%   |
| 5.6     | 1        | 0.54%   |
| 5.4     | 1        | 0.54%   |
| 4.17    | 1        | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 165      | 89.19%  |
| i686   | 20       | 10.81%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 158      | 84.95%  |
| Cinnamon   | 14       | 7.53%   |
| MATE       | 5        | 2.69%   |
| Unknown    | 3        | 1.61%   |
| XFCE       | 2        | 1.08%   |
| GNOME      | 2        | 1.08%   |
| LXQt       | 1        | 0.54%   |
| LXDE       | 1        | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 185      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 152      | 82.16%  |
| TDM     | 15       | 8.11%   |
| LightDM | 15       | 8.11%   |
| MDM     | 2        | 1.08%   |
| GDM     | 1        | 0.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 50       | 27.03%  |
| de_DE   | 20       | 10.81%  |
| pt_BR   | 17       | 9.19%   |
| fr_FR   | 13       | 7.03%   |
| Unknown | 9        | 4.86%   |
| en_GB   | 8        | 4.32%   |
| ru_RU   | 7        | 3.78%   |
| pl_PL   | 7        | 3.78%   |
| en_CA   | 5        | 2.7%    |
| it_IT   | 4        | 2.16%   |
| es_ES   | 4        | 2.16%   |
| en_AU   | 4        | 2.16%   |
| sv_SE   | 3        | 1.62%   |
| nl_BE   | 3        | 1.62%   |
| es_AR   | 3        | 1.62%   |
| pt_PT   | 2        | 1.08%   |
| hu_HU   | 2        | 1.08%   |
| fr_CA   | 2        | 1.08%   |
| cs_CZ   | 2        | 1.08%   |
| ar_EG   | 2        | 1.08%   |
| unm_US  | 1        | 0.54%   |
| uk_UA   | 1        | 0.54%   |
| tr_TR   | 1        | 0.54%   |
| sk_SK   | 1        | 0.54%   |
| nb_NO   | 1        | 0.54%   |
| fi_FI   | 1        | 0.54%   |
| et_EE   | 1        | 0.54%   |
| es_UY   | 1        | 0.54%   |
| es_NI   | 1        | 0.54%   |
| es_MX   | 1        | 0.54%   |
| es_EC   | 1        | 0.54%   |
| es_CO   | 1        | 0.54%   |
| es_CL   | 1        | 0.54%   |
| en_ZA   | 1        | 0.54%   |
| el_GR   | 1        | 0.54%   |
| de_AT   | 1        | 0.54%   |
| ca_ES   | 1        | 0.54%   |
| bg_BG   | 1        | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 131      | 70.81%  |
| EFI  | 54       | 29.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 172      | 92.47%  |
| Btrfs   | 5        | 2.69%   |
| Unknown | 5        | 2.69%   |
| Tmpfs   | 2        | 1.08%   |
| Overlay | 1        | 0.54%   |
| Ext3    | 1        | 0.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 151      | 80.75%  |
| GPT     | 20       | 10.7%   |
| MBR     | 16       | 8.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 174      | 93.05%  |
| Yes       | 13       | 6.95%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 169      | 91.35%  |
| Yes       | 16       | 8.65%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 43       | 23.24%  |
| Gigabyte Technology | 26       | 14.05%  |
| MSI                 | 22       | 11.89%  |
| Dell                | 17       | 9.19%   |
| Hewlett-Packard     | 15       | 8.11%   |
| ASRock              | 14       | 7.57%   |
| Intel               | 8        | 4.32%   |
| Acer                | 7        | 3.78%   |
| Lenovo              | 5        | 2.7%    |
| Unknown             | 5        | 2.7%    |
| ECS                 | 4        | 2.16%   |
| Foxconn             | 3        | 1.62%   |
| Pegatron            | 2        | 1.08%   |
| OEM                 | 2        | 1.08%   |
| EVGA                | 2        | 1.08%   |
| Biostar             | 2        | 1.08%   |
| Semp Toshiba        | 1        | 0.54%   |
| Positivo            | 1        | 0.54%   |
| PCWare              | 1        | 0.54%   |
| NEC Computers       | 1        | 0.54%   |
| Fujitsu Siemens     | 1        | 0.54%   |
| eMachines           | 1        | 0.54%   |
| DFI                 | 1        | 0.54%   |
| Alienware           | 1        | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 6        | 3.24%   |
| HP Pavilion Desktop 590-p0xxx       | 2        | 1.08%   |
| Dell OptiPlex 780                   | 2        | 1.08%   |
| ASUS All Series                     | 2        | 1.08%   |
| Semp Toshiba STI                    | 1        | 0.54%   |
| Positivo POS-EIH61CE                | 1        | 0.54%   |
| Pegatron Elite 7300 Series MT       | 1        | 0.54%   |
| Pegatron 520-1188la                 | 1        | 0.54%   |
| PCWare IPMH81G1                     | 1        | 0.54%   |
| OEM 45CMX/45GMX/45CMX-K             | 1        | 0.54%   |
| NEC Computers IMEDIA S9509          | 1        | 0.54%   |
| MSI PX714AA-ABH t3040.nl            | 1        | 0.54%   |
| MSI MS-7C52                         | 1        | 0.54%   |
| MSI MS-7C51                         | 1        | 0.54%   |
| MSI MS-7B79                         | 1        | 0.54%   |
| MSI MS-7B17                         | 1        | 0.54%   |
| MSI MS-7A40                         | 1        | 0.54%   |
| MSI MS-7A38                         | 1        | 0.54%   |
| MSI MS-7977                         | 1        | 0.54%   |
| MSI MS-7974                         | 1        | 0.54%   |
| MSI MS-7918                         | 1        | 0.54%   |
| MSI MS-7850                         | 1        | 0.54%   |
| MSI MS-7823                         | 1        | 0.54%   |
| MSI MS-7817                         | 1        | 0.54%   |
| MSI MS-7815                         | 1        | 0.54%   |
| MSI MS-7751                         | 1        | 0.54%   |
| MSI MS-7383                         | 1        | 0.54%   |
| MSI MS-7267                         | 1        | 0.54%   |
| MSI MS-7142                         | 1        | 0.54%   |
| MSI MS-6785                         | 1        | 0.54%   |
| MSI MS-6570                         | 1        | 0.54%   |
| MSI ESPRIMO P2440                   | 1        | 0.54%   |
| MSI *MF                             | 1        | 0.54%   |
| Lenovo V55t-15ARE 11KJ0036TX        | 1        | 0.54%   |
| Lenovo ThinkStation P510 30B5005CUS | 1        | 0.54%   |
| Lenovo ThinkCentre M93p 10AB0010US  | 1        | 0.54%   |
| Lenovo ThinkCentre M92p 3238E9U     | 1        | 0.54%   |
| Lenovo ThinkCentre M720s 10SUS9KW00 | 1        | 0.54%   |
| Intel H61                           | 1        | 0.54%   |
| Intel Forte S4D3A-G31               | 1        | 0.54%   |
| Intel DQ77MK AAG39642-400           | 1        | 0.54%   |
| Intel DP55WB AAE64798-206           | 1        | 0.54%   |
| Intel DG33FB AAD81072-309           | 1        | 0.54%   |
| Intel DG31PR AAD97573-302           | 1        | 0.54%   |
| Intel D34010WYK H14771-303          | 1        | 0.54%   |
| Intel BTC-T37                       | 1        | 0.54%   |
| HP Z820 Workstation                 | 1        | 0.54%   |
| HP Z600 Workstation                 | 1        | 0.54%   |
| HP xw8600 Workstation               | 1        | 0.54%   |
| HP ProLiant MicroServer             | 1        | 0.54%   |
| HP Desktop 190-0xxx                 | 1        | 0.54%   |
| HP CQ2930EA                         | 1        | 0.54%   |
| HP Compaq Pro 6300 SFF              | 1        | 0.54%   |
| HP Compaq Elite 8300 CMT            | 1        | 0.54%   |
| HP Compaq dc7800p Small Form Factor | 1        | 0.54%   |
| HP Compaq dc7800 Small Form Factor  | 1        | 0.54%   |
| HP Compaq 8200 Elite USDT PC        | 1        | 0.54%   |
| HP Compaq 8100 Elite SFF PC         | 1        | 0.54%   |
| HP 290 G2 MT Business PC            | 1        | 0.54%   |
| Gigabyte Z97-D3H                    | 1        | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 10       | 5.41%   |
| ASUS PRIME           | 7        | 3.78%   |
| HP Compaq            | 6        | 3.24%   |
| Unknown              | 6        | 3.24%   |
| Acer Aspire          | 4        | 2.16%   |
| Lenovo ThinkCentre   | 3        | 1.62%   |
| Gigabyte X570        | 3        | 1.62%   |
| Dell Precision       | 3        | 1.62%   |
| Dell Inspiron        | 3        | 1.62%   |
| Acer Veriton         | 3        | 1.62%   |
| HP Pavilion          | 2        | 1.08%   |
| Gigabyte Z390        | 2        | 1.08%   |
| Foxconn 945          | 2        | 1.08%   |
| ASUS ROG             | 2        | 1.08%   |
| ASUS P5KPL-AM        | 2        | 1.08%   |
| ASUS All             | 2        | 1.08%   |
| Semp Toshiba STI     | 1        | 0.54%   |
| Positivo POS-EIH61CE | 1        | 0.54%   |
| Pegatron Elite       | 1        | 0.54%   |
| Pegatron 520-1188la  | 1        | 0.54%   |
| PCWare IPMH81G1      | 1        | 0.54%   |
| OEM 45CMX            | 1        | 0.54%   |
| NEC Computers IMEDIA | 1        | 0.54%   |
| MSI PX714AA-ABH      | 1        | 0.54%   |
| MSI MS-7C52          | 1        | 0.54%   |
| MSI MS-7C51          | 1        | 0.54%   |
| MSI MS-7B79          | 1        | 0.54%   |
| MSI MS-7B17          | 1        | 0.54%   |
| MSI MS-7A40          | 1        | 0.54%   |
| MSI MS-7A38          | 1        | 0.54%   |
| MSI MS-7977          | 1        | 0.54%   |
| MSI MS-7974          | 1        | 0.54%   |
| MSI MS-7918          | 1        | 0.54%   |
| MSI MS-7850          | 1        | 0.54%   |
| MSI MS-7823          | 1        | 0.54%   |
| MSI MS-7817          | 1        | 0.54%   |
| MSI MS-7815          | 1        | 0.54%   |
| MSI MS-7751          | 1        | 0.54%   |
| MSI MS-7383          | 1        | 0.54%   |
| MSI MS-7267          | 1        | 0.54%   |
| MSI MS-7142          | 1        | 0.54%   |
| MSI MS-6785          | 1        | 0.54%   |
| MSI MS-6570          | 1        | 0.54%   |
| MSI ESPRIMO          | 1        | 0.54%   |
| MSI *MF              | 1        | 0.54%   |
| Lenovo V55t-15ARE    | 1        | 0.54%   |
| Lenovo ThinkStation  | 1        | 0.54%   |
| Intel H61            | 1        | 0.54%   |
| Intel Forte          | 1        | 0.54%   |
| Intel DQ77MK         | 1        | 0.54%   |
| Intel DP55WB         | 1        | 0.54%   |
| Intel DG33FB         | 1        | 0.54%   |
| Intel DG31PR         | 1        | 0.54%   |
| Intel D34010WYK      | 1        | 0.54%   |
| Intel BTC-T37        | 1        | 0.54%   |
| HP Z820              | 1        | 0.54%   |
| HP Z600              | 1        | 0.54%   |
| HP xw8600            | 1        | 0.54%   |
| HP ProLiant          | 1        | 0.54%   |
| HP Desktop           | 1        | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 25       | 13.51%  |
| 2009 | 17       | 9.19%   |
| 2007 | 16       | 8.65%   |
| 2019 | 14       | 7.57%   |
| 2018 | 14       | 7.57%   |
| 2010 | 14       | 7.57%   |
| 2014 | 13       | 7.03%   |
| 2011 | 12       | 6.49%   |
| 2008 | 12       | 6.49%   |
| 2013 | 8        | 4.32%   |
| 2017 | 7        | 3.78%   |
| 2006 | 7        | 3.78%   |
| 2020 | 5        | 2.7%    |
| 2015 | 5        | 2.7%    |
| 2021 | 4        | 2.16%   |
| 2016 | 4        | 2.16%   |
| 2003 | 4        | 2.16%   |
| 2005 | 3        | 1.62%   |
| 2004 | 1        | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 185      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 184      | 98.4%   |
| Enabled  | 3        | 1.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 185      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 45       | 23.81%  |
| 3.01-4.0    | 40       | 21.16%  |
| 16.01-24.0  | 32       | 16.93%  |
| 4.01-8.0    | 27       | 14.29%  |
| 32.01-64.0  | 15       | 7.94%   |
| 2.01-3.0    | 11       | 5.82%   |
| 1.01-2.0    | 10       | 5.29%   |
| 0.51-1.0    | 4        | 2.12%   |
| 24.01-32.0  | 3        | 1.59%   |
| 64.01-256.0 | 2        | 1.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 86       | 43.88%  |
| 2.01-3.0   | 46       | 23.47%  |
| 3.01-4.0   | 27       | 13.78%  |
| 0.51-1.0   | 23       | 11.73%  |
| 4.01-8.0   | 13       | 6.63%   |
| 32.01-64.0 | 1        | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 45.79%  |
| 2      | 58       | 30.53%  |
| 3      | 21       | 11.05%  |
| 4      | 14       | 7.37%   |
| 7      | 4        | 2.11%   |
| 6      | 3        | 1.58%   |
| 5      | 2        | 1.05%   |
| 8      | 1        | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 107      | 56.91%  |
| No        | 81       | 43.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 185      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 116      | 61.05%  |
| Yes       | 74       | 38.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 151      | 81.18%  |
| Yes       | 35       | 18.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 23       | 12.43%  |
| Germany      | 22       | 11.89%  |
| Brazil       | 19       | 10.27%  |
| France       | 13       | 7.03%   |
| Russia       | 10       | 5.41%   |
| Canada       | 9        | 4.86%   |
| UK           | 6        | 3.24%   |
| Spain        | 6        | 3.24%   |
| Italy        | 6        | 3.24%   |
| Ukraine      | 5        | 2.7%    |
| Poland       | 5        | 2.7%    |
| Netherlands  | 5        | 2.7%    |
| Australia    | 5        | 2.7%    |
| Sweden       | 3        | 1.62%   |
| Bulgaria     | 3        | 1.62%   |
| Belgium      | 3        | 1.62%   |
| Argentina    | 3        | 1.62%   |
| Turkey       | 2        | 1.08%   |
| Puerto Rico  | 2        | 1.08%   |
| Portugal     | 2        | 1.08%   |
| Mexico       | 2        | 1.08%   |
| Hungary      | 2        | 1.08%   |
| Greece       | 2        | 1.08%   |
| Finland      | 2        | 1.08%   |
| Czechia      | 2        | 1.08%   |
| Austria      | 2        | 1.08%   |
| Venezuela    | 1        | 0.54%   |
| Uruguay      | 1        | 0.54%   |
| South Africa | 1        | 0.54%   |
| Slovakia     | 1        | 0.54%   |
| Serbia       | 1        | 0.54%   |
| Romania      | 1        | 0.54%   |
| Philippines  | 1        | 0.54%   |
| Pakistan     | 1        | 0.54%   |
| Norway       | 1        | 0.54%   |
| Nicaragua    | 1        | 0.54%   |
| Luxembourg   | 1        | 0.54%   |
| Latvia       | 1        | 0.54%   |
| India        | 1        | 0.54%   |
| Estonia      | 1        | 0.54%   |
| Egypt        | 1        | 0.54%   |
| Ecuador      | 1        | 0.54%   |
| Croatia      | 1        | 0.54%   |
| Colombia     | 1        | 0.54%   |
| Chile        | 1        | 0.54%   |
| Belarus      | 1        | 0.54%   |
| Bangladesh   | 1        | 0.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Hamburg                  | 4        | 2.03%   |
| Paris                    | 3        | 1.52%   |
| Melbourne                | 3        | 1.52%   |
| Warsaw                   | 2        | 1.02%   |
| Sofia                    | 2        | 1.02%   |
| Rio de Janeiro           | 2        | 1.02%   |
| Perth                    | 2        | 1.02%   |
| Moscow                   | 2        | 1.02%   |
| Montreal                 | 2        | 1.02%   |
| Marseille                | 2        | 1.02%   |
| Helsinki                 | 2        | 1.02%   |
| Florianópolis           | 2        | 1.02%   |
| Belo Horizonte           | 2        | 1.02%   |
| Bayamón                 | 2        | 1.02%   |
| Athens                   | 2        | 1.02%   |
| Amsterdam                | 2        | 1.02%   |
| Zaporozhe                | 1        | 0.51%   |
| Zaandam                  | 1        | 0.51%   |
| Wroclaw                  | 1        | 0.51%   |
| Wijchen                  | 1        | 0.51%   |
| Weiden                   | 1        | 0.51%   |
| Warmsen                  | 1        | 0.51%   |
| Voronezh                 | 1        | 0.51%   |
| Vitória da Conquista    | 1        | 0.51%   |
| Vincennes                | 1        | 0.51%   |
| Vienna                   | 1        | 0.51%   |
| Victoria                 | 1        | 0.51%   |
| Vicente Guerrero         | 1        | 0.51%   |
| Valencia                 | 1        | 0.51%   |
| Ukhta                    | 1        | 0.51%   |
| Trindade                 | 1        | 0.51%   |
| Trieste                  | 1        | 0.51%   |
| Tres Rios                | 1        | 0.51%   |
| Toronto                  | 1        | 0.51%   |
| Toledo                   | 1        | 0.51%   |
| Timișoara               | 1        | 0.51%   |
| Thornton                 | 1        | 0.51%   |
| Theodore                 | 1        | 0.51%   |
| The Hague                | 1        | 0.51%   |
| Tepic                    | 1        | 0.51%   |
| Telc                     | 1        | 0.51%   |
| Tacoma                   | 1        | 0.51%   |
| Stockholm                | 1        | 0.51%   |
| Stockbridge              | 1        | 0.51%   |
| Stendal                  | 1        | 0.51%   |
| Spruce Grove             | 1        | 0.51%   |
| Springdale               | 1        | 0.51%   |
| Sonneberg                | 1        | 0.51%   |
| Simferopol               | 1        | 0.51%   |
| Shimla                   | 1        | 0.51%   |
| Sherbrooke               | 1        | 0.51%   |
| Scotby                   | 1        | 0.51%   |
| Sao Luís                | 1        | 0.51%   |
| Sao Domingos de Rana     | 1        | 0.51%   |
| Santa Rosa               | 1        | 0.51%   |
| Sant Feliu de Llobregat  | 1        | 0.51%   |
| San Juan                 | 1        | 0.51%   |
| San Antonio de Los Altos | 1        | 0.51%   |
| San Antonio              | 1        | 0.51%   |
| Salem                    | 1        | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 72       | 127    | 23.92%  |
| Seagate             | 53       | 86     | 17.61%  |
| Samsung Electronics | 45       | 65     | 14.95%  |
| Kingston            | 18       | 21     | 5.98%   |
| Hitachi             | 15       | 19     | 4.98%   |
| Toshiba             | 14       | 19     | 4.65%   |
| Crucial             | 13       | 16     | 4.32%   |
| SanDisk             | 10       | 13     | 3.32%   |
| A-DATA Technology   | 8        | 8      | 2.66%   |
| Phison              | 6        | 7      | 1.99%   |
| Intel               | 6        | 6      | 1.99%   |
| OCZ                 | 3        | 5      | 1%      |
| Maxtor              | 3        | 5      | 1%      |
| Intenso             | 3        | 4      | 1%      |
| China               | 3        | 3      | 1%      |
| Transcend           | 2        | 3      | 0.66%   |
| TCSUNBOW            | 2        | 2      | 0.66%   |
| Micron Technology   | 2        | 2      | 0.66%   |
| CT500MX5            | 2        | 2      | 0.66%   |
| XrayDisk            | 1        | 2      | 0.33%   |
| Unknown             | 1        | 2      | 0.33%   |
| Team                | 1        | 2      | 0.33%   |
| Smartbuy            | 1        | 1      | 0.33%   |
| SK hynix            | 1        | 1      | 0.33%   |
| Silicon Motion      | 1        | 1      | 0.33%   |
| SABRENT             | 1        | 1      | 0.33%   |
| Plextor             | 1        | 2      | 0.33%   |
| Patriot             | 1        | 1      | 0.33%   |
| OCZ-VERTEX          | 1        | 1      | 0.33%   |
| Mushkin             | 1        | 1      | 0.33%   |
| KingSpec            | 1        | 1      | 0.33%   |
| Kingmax             | 1        | 1      | 0.33%   |
| KESU                | 1        | 2      | 0.33%   |
| HPE                 | 1        | 4      | 0.33%   |
| Hewlett-Packard     | 1        | 1      | 0.33%   |
| Gigabyte Technology | 1        | 1      | 0.33%   |
| Fujitsu             | 1        | 1      | 0.33%   |
| ExcelStor           | 1        | 1      | 0.33%   |
| Dogfish             | 1        | 1      | 0.33%   |
| 2.5''               | 1        | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB           | 5        | 1.42%   |
| Toshiba DT01ACA100 1TB              | 4        | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 1.13%   |
| Kingston SA400S37240G 240GB SSD     | 4        | 1.13%   |
| Kingston SA400S37120G 120GB SSD     | 4        | 1.13%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3        | 0.85%   |
| Seagate ST2000DM008-2FR102 2TB      | 3        | 0.85%   |
| Seagate ST2000DM001-1ER164 2TB      | 3        | 0.85%   |
| Samsung SSD 860 EVO 500GB           | 3        | 0.85%   |
| Samsung HD322HJ 320GB               | 3        | 0.85%   |
| Samsung HD161HJ 160GB               | 3        | 0.85%   |
| Samsung HD103SJ 1TB                 | 3        | 0.85%   |
| Kingston SA400S37480G 480GB SSD     | 3        | 0.85%   |
| Crucial CT480BX500SSD1 480GB        | 3        | 0.85%   |
| Crucial CT240BX500SSD1 240GB        | 3        | 0.85%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 0.57%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2        | 0.57%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.57%   |
| WDC WD3200AAKS-00L9A0 320GB         | 2        | 0.57%   |
| WDC WD2500AAKX-753CA1 250GB         | 2        | 0.57%   |
| WDC WD1600AABS-00PRA0 160GB         | 2        | 0.57%   |
| WDC WD10EZEX-60WN4A0 1TB            | 2        | 0.57%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 2        | 0.57%   |
| Toshiba HDWD110 1TB                 | 2        | 0.57%   |
| Seagate ST500LT012-1DG142 500GB     | 2        | 0.57%   |
| Seagate ST500DM002-1BD142 500GB     | 2        | 0.57%   |
| Seagate ST3160021A 160GB            | 2        | 0.57%   |
| Seagate ST31000528AS 1TB            | 2        | 0.57%   |
| Seagate ST2000LX001-1RG174 2TB      | 2        | 0.57%   |
| Seagate ST2000DM001-9YN164 2TB      | 2        | 0.57%   |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB      | 2        | 0.57%   |
| Seagate Expansion 1TB               | 2        | 0.57%   |
| SanDisk SDSSDA240G 240GB            | 2        | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB        | 2        | 0.57%   |
| Samsung SSD 850 EVO 500GB           | 2        | 0.57%   |
| Samsung SP0802N 80GB                | 2        | 0.57%   |
| Samsung NVMe SSD Drive 2TB          | 2        | 0.57%   |
| Samsung NVMe SSD Drive 256GB        | 2        | 0.57%   |
| Samsung HD080HJ/ 80GB               | 2        | 0.57%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2        | 0.57%   |
| Kingston SV300S37A120G 120GB SSD    | 2        | 0.57%   |
| Intel SSDSC2BW120A4 120GB           | 2        | 0.57%   |
| Hitachi HDP725050GLA360 500GB       | 2        | 0.57%   |
| CT500MX5 00SSD1 500GB               | 2        | 0.57%   |
| Crucial CT500MX500SSD1 500GB        | 2        | 0.57%   |
| A-DATA SU650 240GB SSD              | 2        | 0.57%   |
| A-DATA SU650 120GB SSD              | 2        | 0.57%   |
| XrayDisk 480GB                      | 1        | 0.28%   |
| XrayDisk 1TB                        | 1        | 0.28%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1        | 0.28%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1        | 0.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 0.28%   |
| WDC WDS120G1G0A-00SS50 120GB SSD    | 1        | 0.28%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.28%   |
| WDC WDBNCE2500PNC 250GB SSD         | 1        | 0.28%   |
| WDC WD7502AAEX-00Z3A0 752GB         | 1        | 0.28%   |
| WDC WD7502AAEX-00Y9A0 752GB         | 1        | 0.28%   |
| WDC WD6400AAKS-07A7B0 640GB         | 1        | 0.28%   |
| WDC WD60EZAZ-00ZGHB0 6TB            | 1        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 64       | 117    | 36.36%  |
| Seagate             | 53       | 86     | 30.11%  |
| Samsung Electronics | 24       | 32     | 13.64%  |
| Hitachi             | 15       | 19     | 8.52%   |
| Toshiba             | 11       | 12     | 6.25%   |
| Maxtor              | 3        | 5      | 1.7%    |
| Unknown             | 1        | 1      | 0.57%   |
| SABRENT             | 1        | 1      | 0.57%   |
| KESU                | 1        | 2      | 0.57%   |
| HPE                 | 1        | 4      | 0.57%   |
| Fujitsu             | 1        | 1      | 0.57%   |
| ExcelStor           | 1        | 1      | 0.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 17       | 20     | 15.6%   |
| Samsung Electronics | 16       | 20     | 14.68%  |
| Crucial             | 13       | 16     | 11.93%  |
| SanDisk             | 10       | 13     | 9.17%   |
| WDC                 | 8        | 8      | 7.34%   |
| A-DATA Technology   | 8        | 8      | 7.34%   |
| Intel               | 4        | 4      | 3.67%   |
| Toshiba             | 3        | 7      | 2.75%   |
| OCZ                 | 3        | 5      | 2.75%   |
| Intenso             | 3        | 4      | 2.75%   |
| China               | 3        | 3      | 2.75%   |
| Transcend           | 2        | 3      | 1.83%   |
| TCSUNBOW            | 2        | 2      | 1.83%   |
| Micron Technology   | 2        | 2      | 1.83%   |
| CT500MX5            | 2        | 2      | 1.83%   |
| Unknown             | 1        | 1      | 0.92%   |
| Team                | 1        | 2      | 0.92%   |
| Smartbuy            | 1        | 1      | 0.92%   |
| SK hynix            | 1        | 1      | 0.92%   |
| Plextor             | 1        | 2      | 0.92%   |
| Patriot             | 1        | 1      | 0.92%   |
| OCZ-VERTEX          | 1        | 1      | 0.92%   |
| KingSpec            | 1        | 1      | 0.92%   |
| Kingmax             | 1        | 1      | 0.92%   |
| Hewlett-Packard     | 1        | 1      | 0.92%   |
| Gigabyte Technology | 1        | 1      | 0.92%   |
| Dogfish             | 1        | 1      | 0.92%   |
| 2.5''               | 1        | 1      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 140      | 281    | 56%     |
| SSD     | 90       | 132    | 36%     |
| NVMe    | 19       | 27     | 7.6%    |
| Unknown | 1        | 2      | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 178      | 397    | 85.99%  |
| NVMe | 19       | 27     | 9.18%   |
| SAS  | 10       | 18     | 4.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 150      | 274    | 62.24%  |
| 0.51-1.0   | 57       | 84     | 23.65%  |
| 1.01-2.0   | 22       | 31     | 9.13%   |
| 2.01-3.0   | 5        | 13     | 2.07%   |
| 3.01-4.0   | 4        | 8      | 1.66%   |
| 4.01-10.0  | 3        | 3      | 1.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 57       | 29.69%  |
| 251-500        | 41       | 21.35%  |
| 1001-2000      | 26       | 13.54%  |
| More than 3000 | 18       | 9.38%   |
| 51-100         | 15       | 7.81%   |
| 501-1000       | 14       | 7.29%   |
| 2001-3000      | 10       | 5.21%   |
| 21-50          | 8        | 4.17%   |
| 1-20           | 3        | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 64       | 32%     |
| 21-50          | 47       | 23.5%   |
| 51-100         | 23       | 11.5%   |
| 101-250        | 16       | 8%      |
| 251-500        | 14       | 7%      |
| 1001-2000      | 13       | 6.5%    |
| 501-1000       | 13       | 6.5%    |
| More than 3000 | 5        | 2.5%    |
| 2001-3000      | 5        | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD2500BEVT-24A23T0 250GB      | 1        | 1      | 14.29%  |
| Seagate ST9320325AS 320GB         | 1        | 1      | 14.29%  |
| Seagate ST500LT012-1DG142 500GB   | 1        | 1      | 14.29%  |
| Seagate ST3250318AS 250GB         | 1        | 1      | 14.29%  |
| Samsung Electronics SP2004C 200GB | 1        | 1      | 14.29%  |
| Samsung Electronics HM500JI 500GB | 1        | 1      | 14.29%  |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 42.86%  |
| Samsung Electronics | 3        | 3      | 42.86%  |
| WDC                 | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 42.86%  |
| Samsung Electronics | 3        | 3      | 42.86%  |
| WDC                 | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 7      | 100%    |

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
| Detected | 153      | 355    | 77.66%  |
| Works    | 37       | 80     | 18.78%  |
| Malfunc  | 7        | 7      | 3.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 129      | 53.75%  |
| AMD                              | 40       | 16.67%  |
| Nvidia                           | 11       | 4.58%   |
| ASMedia Technology               | 11       | 4.58%   |
| JMicron Technology               | 10       | 4.17%   |
| Samsung Electronics              | 9        | 3.75%   |
| VIA Technologies                 | 6        | 2.5%    |
| Phison Electronics               | 6        | 2.5%    |
| Marvell Technology Group         | 6        | 2.5%    |
| Silicon Motion                   | 2        | 0.83%   |
| Silicon Integrated Systems [SiS] | 2        | 0.83%   |
| Silicon Image                    | 2        | 0.83%   |
| SanDisk                          | 2        | 0.83%   |
| Broadcom / LSI                   | 2        | 0.83%   |
| Kingston Technology Company      | 1        | 0.42%   |
| Integrated Technology Express    | 1        | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 6.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 19       | 5.72%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 18       | 5.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 4.82%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11       | 3.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 2.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 2.41%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 2.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 2.11%   |
| Nvidia MCP61 SATA Controller                                                            | 7        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 2.11%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 2.11%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.81%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.81%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.81%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.81%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 5        | 1.51%   |
| Nvidia MCP61 IDE                                                                        | 5        | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.51%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.2%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 1.2%    |
| AMD FCH SATA Controller D                                                               | 4        | 1.2%    |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 1.2%    |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3        | 0.9%    |
| Phison E12 NVMe Controller                                                              | 3        | 0.9%    |
| JMicron JMB368 IDE controller                                                           | 3        | 0.9%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 0.9%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 0.9%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 3        | 0.9%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 0.9%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 0.9%    |
| Nvidia nForce2 IDE                                                                      | 2        | 0.6%    |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 2        | 0.6%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.6%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 0.6%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2        | 0.6%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.6%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.6%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 0.6%    |
| AMD FCH IDE Controller                                                                  | 2        | 0.6%    |
| VIA VT6410 ATA133 RAID controller                                                       | 1        | 0.3%    |
| VIA Serial ATA Controller                                                               | 1        | 0.3%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.3%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.3%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1        | 0.3%    |
| Silicon Integrated Systems [SiS] 182 SATA/RAID Controller                               | 1        | 0.3%    |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.3%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.3%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.3%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.3%    |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 123      | 51.25%  |
| IDE  | 82       | 34.17%  |
| NVMe | 19       | 7.92%   |
| RAID | 12       | 5%      |
| SAS  | 3        | 1.25%   |
| SCSI | 1        | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 132      | 71.35%  |
| AMD    | 53       | 28.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 2.16%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 2.16%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 4        | 2.16%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 2.16%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 4        | 2.16%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 3        | 1.62%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.62%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.62%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 3        | 1.62%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 1.62%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 1.08%   |
| Intel Pentium D CPU 3.00GHz                 | 2        | 1.08%   |
| Intel Pentium D CPU 2.80GHz                 | 2        | 1.08%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 1.08%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 1.08%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 1.08%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 1.08%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.08%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 1.08%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 1.08%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.08%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.08%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.08%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.08%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz       | 2        | 1.08%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.08%   |
| AMD Sempron Processor 3000+                 | 2        | 1.08%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 1.08%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 1.08%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.08%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.08%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.08%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.08%   |
| AMD FX-4300 Quad-Core Processor             | 2        | 1.08%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 0.54%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 0.54%   |
| Intel Xeon CPU X5260 @ 3.33GHz              | 1        | 0.54%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1        | 0.54%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 0.54%   |
| Intel Xeon CPU E5472 @ 3.00GHz              | 1        | 0.54%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.54%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 1        | 0.54%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.54%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1        | 0.54%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.54%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.54%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.54%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.54%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.54%   |
| Intel Pentium D CPU 3.20GHz                 | 1        | 0.54%   |
| Intel Pentium CPU J4205 @ 1.50GHz           | 1        | 0.54%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.54%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.54%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.54%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.54%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.54%   |
| Intel Core i9-10900T CPU @ 1.90GHz          | 1        | 0.54%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 24       | 12.97%  |
| Intel Core i7           | 21       | 11.35%  |
| Intel Core 2 Duo        | 19       | 10.27%  |
| Intel Core i3           | 12       | 6.49%   |
| Intel Xeon              | 11       | 5.95%   |
| AMD Ryzen 5             | 10       | 5.41%   |
| Intel Pentium           | 9        | 4.86%   |
| Intel Core 2 Quad       | 9        | 4.86%   |
| Intel Celeron           | 7        | 3.78%   |
| AMD Ryzen 7             | 6        | 3.24%   |
| AMD FX                  | 6        | 3.24%   |
| Intel Pentium Dual-Core | 5        | 2.7%    |
| Intel Pentium D         | 5        | 2.7%    |
| AMD Sempron             | 4        | 2.16%   |
| AMD Athlon 64 X2        | 4        | 2.16%   |
| Intel Pentium 4         | 3        | 1.62%   |
| Intel Core 2            | 3        | 1.62%   |
| AMD Ryzen 3             | 3        | 1.62%   |
| AMD Phenom II X4        | 3        | 1.62%   |
| AMD Athlon XP           | 3        | 1.62%   |
| Intel Core i9           | 2        | 1.08%   |
| AMD Phenom II X6        | 2        | 1.08%   |
| AMD Athlon II X4        | 2        | 1.08%   |
| AMD Athlon              | 2        | 1.08%   |
| Other                   | 1        | 0.54%   |
| Intel Pentium Dual      | 1        | 0.54%   |
| AMD Turion II Neo       | 1        | 0.54%   |
| AMD Ryzen 9             | 1        | 0.54%   |
| AMD Ryzen 5 PRO         | 1        | 0.54%   |
| AMD Phenom II X2        | 1        | 0.54%   |
| AMD E1                  | 1        | 0.54%   |
| AMD Athlon II X2        | 1        | 0.54%   |
| AMD A4                  | 1        | 0.54%   |
| AMD A10                 | 1        | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 70       | 37.84%  |
| 2      | 70       | 37.84%  |
| 6      | 15       | 8.11%   |
| 8      | 12       | 6.49%   |
| 1      | 12       | 6.49%   |
| 16     | 2        | 1.08%   |
| 3      | 2        | 1.08%   |
| 12     | 1        | 0.54%   |
| 10     | 1        | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 181      | 97.84%  |
| 2      | 4        | 2.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 116      | 62.7%   |
| 2      | 69       | 37.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 179      | 96.76%  |
| 32-bit         | 6        | 3.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 19       | 10.22%  |
| Unknown    | 19       | 10.22%  |
| 0x306a9    | 15       | 8.06%   |
| 0x206a7    | 15       | 8.06%   |
| 0x306c3    | 12       | 6.45%   |
| 0x6fd      | 6        | 3.23%   |
| 0x08108109 | 6        | 3.23%   |
| 0x6fb      | 5        | 2.69%   |
| 0x10677    | 5        | 2.69%   |
| 0x010000c8 | 5        | 2.69%   |
| 0x906ed    | 4        | 2.15%   |
| 0x906eb    | 4        | 2.15%   |
| 0x506e3    | 4        | 2.15%   |
| 0xf65      | 3        | 1.61%   |
| 0xf64      | 3        | 1.61%   |
| 0x906ea    | 3        | 1.61%   |
| 0x106e5    | 3        | 1.61%   |
| 0x106a5    | 3        | 1.61%   |
| 0x06000852 | 3        | 1.61%   |
| 0xf29      | 2        | 1.08%   |
| 0x6f2      | 2        | 1.08%   |
| 0x40651    | 2        | 1.08%   |
| 0x206d7    | 2        | 1.08%   |
| 0x10676    | 2        | 1.08%   |
| 0x08701021 | 2        | 1.08%   |
| 0x08701013 | 2        | 1.08%   |
| 0x08101016 | 2        | 1.08%   |
| 0x0800820d | 2        | 1.08%   |
| 0x06001119 | 2        | 1.08%   |
| 0x0600063e | 2        | 1.08%   |
| 0x010000dc | 2        | 1.08%   |
| 0xa0655    | 1        | 0.54%   |
| 0xa0653    | 1        | 0.54%   |
| 0x90675    | 1        | 0.54%   |
| 0x706a8    | 1        | 0.54%   |
| 0x6f6      | 1        | 0.54%   |
| 0x506c9    | 1        | 0.54%   |
| 0x406f1    | 1        | 0.54%   |
| 0x306f2    | 1        | 0.54%   |
| 0x206c2    | 1        | 0.54%   |
| 0x20655    | 1        | 0.54%   |
| 0x10661    | 1        | 0.54%   |
| 0x0a50000c | 1        | 0.54%   |
| 0x0a50000b | 1        | 0.54%   |
| 0x0a201009 | 1        | 0.54%   |
| 0x08101102 | 1        | 0.54%   |
| 0x0810100b | 1        | 0.54%   |
| 0x0800820c | 1        | 0.54%   |
| 0x08001137 | 1        | 0.54%   |
| 0x08001129 | 1        | 0.54%   |
| 0x08001126 | 1        | 0.54%   |
| 0x0700010f | 1        | 0.54%   |
| 0x06000822 | 1        | 0.54%   |
| 0x05000119 | 1        | 0.54%   |
| 0x010000db | 1        | 0.54%   |
| 0x010000c7 | 1        | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 26       | 14.05%  |
| SandyBridge   | 20       | 10.81%  |
| IvyBridge     | 16       | 8.65%   |
| Core          | 16       | 8.65%   |
| Haswell       | 15       | 8.11%   |
| KabyLake      | 12       | 6.49%   |
| K10           | 10       | 5.41%   |
| Zen+          | 9        | 4.86%   |
| NetBurst      | 9        | 4.86%   |
| Zen           | 7        | 3.78%   |
| K8 Hammer     | 7        | 3.78%   |
| Piledriver    | 6        | 3.24%   |
| Nehalem       | 6        | 3.24%   |
| Zen 2         | 4        | 2.16%   |
| Skylake       | 4        | 2.16%   |
| Zen 3         | 3        | 1.62%   |
| K6            | 3        | 1.62%   |
| Westmere      | 2        | 1.08%   |
| CometLake     | 2        | 1.08%   |
| Bulldozer     | 2        | 1.08%   |
| Jaguar        | 1        | 0.54%   |
| Goldmont plus | 1        | 0.54%   |
| Goldmont      | 1        | 0.54%   |
| Broadwell     | 1        | 0.54%   |
| Bobcat        | 1        | 0.54%   |
| Unknown       | 1        | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 84       | 42.21%  |
| Intel                      | 62       | 31.16%  |
| AMD                        | 46       | 23.12%  |
| VIA Technologies           | 4        | 2.01%   |
| S3 Graphics                | 1        | 0.5%    |
| Matrox Electronics Systems | 1        | 0.5%    |
| ASPEED Technology          | 1        | 0.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 15       | 7.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 8        | 3.88%   |
| Nvidia GT218 [GeForce 210]                                                    | 7        | 3.4%    |
| Nvidia GM206 [GeForce GTX 960]                                                | 7        | 3.4%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 7        | 3.4%    |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 7        | 3.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 6        | 2.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 6        | 2.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 6        | 2.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4        | 1.94%   |
| Nvidia GK208B [GeForce GT 730]                                                | 4        | 1.94%   |
| Nvidia GK208B [GeForce GT 710]                                                | 4        | 1.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 4        | 1.94%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                             | 3        | 1.46%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 3        | 1.46%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 3        | 1.46%   |
| AMD RV710 [Radeon HD 4350/4550]                                               | 3        | 1.46%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 3        | 1.46%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 2        | 0.97%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 2        | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 2        | 0.97%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2        | 0.97%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 2        | 0.97%   |
| Nvidia GK104 [GeForce GTX 760]                                                | 2        | 0.97%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                             | 2        | 0.97%   |
| Nvidia GF104 [GeForce GTX 460]                                                | 2        | 0.97%   |
| Nvidia G86 [GeForce 8400 GS]                                                  | 2        | 0.97%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                       | 2        | 0.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2        | 0.97%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 2        | 0.97%   |
| Intel 82Q35 Express Integrated Graphics Controller                            | 2        | 0.97%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                    | 1        | 0.49%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                     | 1        | 0.49%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 1        | 0.49%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.49%   |
| S3 Graphics VT8375 [ProSavage8 KM266/KL266]                                   | 1        | 0.49%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1        | 0.49%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                         | 1        | 0.49%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                        | 1        | 0.49%   |
| Nvidia NV44 [GeForce 6200 TurboCache]                                         | 1        | 0.49%   |
| Nvidia NV43 [GeForce 6600]                                                    | 1        | 0.49%   |
| Nvidia NV36 [GeForce FX 5700VE]                                               | 1        | 0.49%   |
| Nvidia NV34 [GeForce FX 5200]                                                 | 1        | 0.49%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                         | 1        | 0.49%   |
| Nvidia GT218 [GeForce 310]                                                    | 1        | 0.49%   |
| Nvidia GT200 [GeForce GTX 260]                                                | 1        | 0.49%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1        | 0.49%   |
| Nvidia GP107GL [Quadro P400]                                                  | 1        | 0.49%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1        | 0.49%   |
| Nvidia GM204GL [Quadro M4000]                                                 | 1        | 0.49%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 1        | 0.49%   |
| Nvidia GM107GL [Quadro K620]                                                  | 1        | 0.49%   |
| Nvidia GK208B [GeForce GT 720]                                                | 1        | 0.49%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 1        | 0.49%   |
| Nvidia GK107 [GeForce GT 640]                                                 | 1        | 0.49%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                             | 1        | 0.49%   |
| Nvidia GK104 [GeForce GTX 660 OEM]                                            | 1        | 0.49%   |
| Nvidia GF119 [NVS 310]                                                        | 1        | 0.49%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                         | 1        | 0.49%   |
| Nvidia GF108 [GeForce GT 730]                                                 | 1        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 79       | 42.25%  |
| 1 x Intel       | 51       | 27.27%  |
| 1 x AMD         | 40       | 21.39%  |
| 2 x AMD         | 4        | 2.14%   |
| 1 x VIA         | 4        | 2.14%   |
| Intel + Nvidia  | 3        | 1.6%    |
| AMD + Nvidia    | 2        | 1.07%   |
| 2 x Nvidia      | 1        | 0.53%   |
| 1 x S3 Graphics | 1        | 0.53%   |
| 1 x Matrox      | 1        | 0.53%   |
| 1 x ASPEED      | 1        | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 127      | 67.91%  |
| Proprietary | 34       | 18.18%  |
| Unknown     | 26       | 13.9%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 77       | 41.18%  |
| 1.01-2.0   | 28       | 14.97%  |
| 0.51-1.0   | 28       | 14.97%  |
| 0.01-0.5   | 25       | 13.37%  |
| 3.01-4.0   | 16       | 8.56%   |
| 7.01-8.0   | 10       | 5.35%   |
| 2.01-3.0   | 2        | 1.07%   |
| 5.01-6.0   | 1        | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 36       | 18.18%  |
| Acer                    | 20       | 10.1%   |
| Goldstar                | 19       | 9.6%    |
| Dell                    | 18       | 9.09%   |
| Ancor Communications    | 12       | 6.06%   |
| AOC                     | 10       | 5.05%   |
| Philips                 | 9        | 4.55%   |
| Hewlett-Packard         | 9        | 4.55%   |
| BenQ                    | 8        | 4.04%   |
| Unknown                 | 7        | 3.54%   |
| Lenovo                  | 5        | 2.53%   |
| Sony                    | 4        | 2.02%   |
| Fujitsu Siemens         | 4        | 2.02%   |
| Iiyama                  | 3        | 1.52%   |
| ___                     | 2        | 1.01%   |
| Sceptre Tech            | 2        | 1.01%   |
| NEC Computers           | 2        | 1.01%   |
| Medion                  | 2        | 1.01%   |
| LG Electronics          | 2        | 1.01%   |
| eMachines               | 2        | 1.01%   |
| ASUSTek Computer        | 2        | 1.01%   |
| Vestel                  | 1        | 0.51%   |
| Toshiba                 | 1        | 0.51%   |
| Targa Visionary         | 1        | 0.51%   |
| OEM                     | 1        | 0.51%   |
| NCS                     | 1        | 0.51%   |
| Mitsubishi              | 1        | 0.51%   |
| Microstep               | 1        | 0.51%   |
| IBM                     | 1        | 0.51%   |
| Hitachi                 | 1        | 0.51%   |
| ELSA International      | 1        | 0.51%   |
| Elo Touch               | 1        | 0.51%   |
| ELO                     | 1        | 0.51%   |
| Eizo                    | 1        | 0.51%   |
| DENON                   | 1        | 0.51%   |
| Compal                  | 1        | 0.51%   |
| Chi Mei Optoelectronics | 1        | 0.51%   |
| Belinea                 | 1        | 0.51%   |
| AUS                     | 1        | 0.51%   |
| AOpen                   | 1        | 0.51%   |
| AGO                     | 1        | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch     | 2        | 0.98%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 2        | 0.98%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                     | 2        | 0.98%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                       | 2        | 0.98%   |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                           | 2        | 0.98%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch        | 2        | 0.98%   |
| ___ LCD TV ___0101 1360x768                                             | 1        | 0.49%   |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch                   | 1        | 0.49%   |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                               | 1        | 0.49%   |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                      | 1        | 0.49%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                      | 1        | 0.49%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.49%   |
| Unknown LCD Monitor SAMSUNG                                             | 1        | 0.49%   |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                       | 1        | 0.49%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                                | 1        | 0.49%   |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch                  | 1        | 0.49%   |
| Toshiba LCD Monitor TV 1920x1080                                        | 1        | 0.49%   |
| Targa Visionary LCD19-4 TARA194 1280x1024 380x300mm 19.1-inch           | 1        | 0.49%   |
| Sony TV SNY4C03 1920x1080 1063x598mm 48.0-inch                          | 1        | 0.49%   |
| Sony TV SNY1B02 1360x768 1600x900mm 72.3-inch                           | 1        | 0.49%   |
| Sony TV *00 SNYF503 1920x1080 1439x809mm 65.0-inch                      | 1        | 0.49%   |
| Sony LCD Monitor TV 3840x1080                                           | 1        | 0.49%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                  | 1        | 0.49%   |
| Sceptre Tech F24 SPT0961 1920x1080 480x260mm 21.5-inch                  | 1        | 0.49%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 600x340mm 27.2-inch       | 1        | 0.49%   |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch       | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch     | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 459x296mm 21.5-inch    | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch    | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM034F 1440x900 428x255mm 19.6-inch     | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0303 1680x1050 494x320mm 23.2-inch    | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch    | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch    | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 376x301mm 19.0-inch    | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM006E 1280x1024 338x270mm 17.0-inch    | 1        | 0.49%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 530x300mm 24.0-inch    | 1        | 0.49%   |
| Samsung Electronics SMS22A200/460 SAM0831 1920x1080 477x268mm 21.5-inch | 1        | 0.49%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 376x301mm 19.0-inch     | 1        | 0.49%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch      | 1        | 0.49%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch      | 1        | 0.49%   |
| Samsung Electronics SMB2230 SAM063E 1920x1080 477x268mm 21.5-inch       | 1        | 0.49%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch       | 1        | 0.49%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 1        | 0.49%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.49%   |
| Samsung Electronics S24D360 SAM0B24 1920x1080 521x293mm 23.5-inch       | 1        | 0.49%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1        | 0.49%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch       | 1        | 0.49%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch       | 1        | 0.49%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch        | 1        | 0.49%   |
| Samsung Electronics S16B110 SAM097E 1366x768 360x210mm 16.4-inch        | 1        | 0.49%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                      | 1        | 0.49%   |
| Samsung Electronics LCD Monitor SAM0F39 1920x1080 1210x680mm 54.6-inch  | 1        | 0.49%   |
| Samsung Electronics LCD Monitor SAM08FE 1920x1080                       | 1        | 0.49%   |
| Samsung Electronics LCD Monitor SA300/SA350 1920x1080                   | 1        | 0.49%   |
| Samsung Electronics LCD Monitor S22B350 1920x1080                       | 1        | 0.49%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch      | 1        | 0.49%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch       | 1        | 0.49%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch               | 1        | 0.49%   |
| Philips PHL 288E2 PHLC231 3840x2160 621x341mm 27.9-inch                 | 1        | 0.49%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                 | 1        | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 87       | 46.28%  |
| 1280x1024 (SXGA)   | 34       | 18.09%  |
| 1680x1050 (WSXGA+) | 12       | 6.38%   |
| 1440x900 (WXGA+)   | 9        | 4.79%   |
| 1366x768 (WXGA)    | 8        | 4.26%   |
| 1600x900 (HD+)     | 7        | 3.72%   |
| 1920x1200 (WUXGA)  | 5        | 2.66%   |
| 1360x768           | 5        | 2.66%   |
| 3840x2160 (4K)     | 4        | 2.13%   |
| 1024x768 (XGA)     | 4        | 2.13%   |
| 2560x1440 (QHD)    | 3        | 1.6%    |
| Unknown            | 3        | 1.6%    |
| 3440x1440          | 2        | 1.06%   |
| 7680x2160          | 1        | 0.53%   |
| 4240x1440          | 1        | 0.53%   |
| 3840x1080          | 1        | 0.53%   |
| 2560x1080          | 1        | 0.53%   |
| 1600x1200          | 1        | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 26       | 13.4%   |
| 21      | 25       | 12.89%  |
| 24      | 21       | 10.82%  |
| 23      | 19       | 9.79%   |
| 19      | 19       | 9.79%   |
| 17      | 16       | 8.25%   |
| 18      | 14       | 7.22%   |
| 27      | 13       | 6.7%    |
| 20      | 8        | 4.12%   |
| 15      | 8        | 4.12%   |
| 22      | 7        | 3.61%   |
| 31      | 3        | 1.55%   |
| 72      | 2        | 1.03%   |
| 32      | 2        | 1.03%   |
| 65      | 1        | 0.52%   |
| 54      | 1        | 0.52%   |
| 52      | 1        | 0.52%   |
| 48      | 1        | 0.52%   |
| 33      | 1        | 0.52%   |
| 28      | 1        | 0.52%   |
| 26      | 1        | 0.52%   |
| 16      | 1        | 0.52%   |
| 14      | 1        | 0.52%   |
| 13      | 1        | 0.52%   |
| 12      | 1        | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 58       | 30.69%  |
| 501-600     | 48       | 25.4%   |
| Unknown     | 26       | 13.76%  |
| 301-350     | 24       | 12.7%   |
| 351-400     | 17       | 8.99%   |
| 601-700     | 5        | 2.65%   |
| 1001-1500   | 4        | 2.12%   |
| 701-800     | 3        | 1.59%   |
| 201-300     | 2        | 1.06%   |
| 1501-2000   | 2        | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 94       | 50.81%  |
| 5/4     | 29       | 15.68%  |
| Unknown | 25       | 13.51%  |
| 16/10   | 24       | 12.97%  |
| 4/3     | 10       | 5.41%   |
| 21/9    | 2        | 1.08%   |
| 3/2     | 1        | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 58       | 30.21%  |
| 151-200        | 37       | 19.27%  |
| Unknown        | 26       | 13.54%  |
| 141-150        | 25       | 13.02%  |
| 301-350        | 14       | 7.29%   |
| 251-300        | 8        | 4.17%   |
| 101-110        | 7        | 3.65%   |
| 351-500        | 6        | 3.13%   |
| More than 1000 | 5        | 2.6%    |
| 111-120        | 3        | 1.56%   |
| 81-90          | 1        | 0.52%   |
| 71-80          | 1        | 0.52%   |
| 501-1000       | 1        | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 119      | 65.03%  |
| 101-120 | 28       | 15.3%   |
| Unknown | 26       | 14.21%  |
| 1-50    | 6        | 3.28%   |
| 121-160 | 3        | 1.64%   |
| 161-240 | 1        | 0.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 154      | 81.91%  |
| 2     | 24       | 12.77%  |
| 0     | 7        | 3.72%   |
| 3     | 3        | 1.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 110      | 42.15%  |
| Intel                            | 57       | 21.84%  |
| Qualcomm Atheros                 | 23       | 8.81%   |
| Ralink Technology                | 13       | 4.98%   |
| Broadcom                         | 11       | 4.21%   |
| Nvidia                           | 9        | 3.45%   |
| VIA Technologies                 | 4        | 1.53%   |
| TP-Link                          | 4        | 1.53%   |
| Marvell Technology Group         | 3        | 1.15%   |
| Broadcom Limited                 | 3        | 1.15%   |
| Sitecom Europe                   | 2        | 0.77%   |
| Samsung Electronics              | 2        | 0.77%   |
| Microsoft                        | 2        | 0.77%   |
| AVM                              | 2        | 0.77%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.38%   |
| Silicon Integrated Systems [SiS] | 1        | 0.38%   |
| Ralink                           | 1        | 0.38%   |
| Mercucys                         | 1        | 0.38%   |
| Mellanox Technologies            | 1        | 0.38%   |
| MediaTek                         | 1        | 0.38%   |
| LSI                              | 1        | 0.38%   |
| JMicron Technology               | 1        | 0.38%   |
| Huawei Technologies              | 1        | 0.38%   |
| Edimax Technology                | 1        | 0.38%   |
| DisplayLink                      | 1        | 0.38%   |
| D-Link System                    | 1        | 0.38%   |
| Belkin Components                | 1        | 0.38%   |
| ASUSTek Computer                 | 1        | 0.38%   |
| ADMtek                           | 1        | 0.38%   |
| 3Com                             | 1        | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 80       | 27.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 9        | 3.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 8        | 2.72%   |
| Nvidia MCP61 Ethernet                                                                         | 7        | 2.38%   |
| Intel I211 Gigabit Network Connection                                                         | 7        | 2.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 6        | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 5        | 1.7%    |
| Intel Wi-Fi 6 AX200                                                                           | 5        | 1.7%    |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 4        | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 1.36%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 4        | 1.36%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 1.36%   |
| Intel Ethernet Connection (7) I219-V                                                          | 4        | 1.36%   |
| Intel 82579V Gigabit Network Connection                                                       | 4        | 1.36%   |
| Intel 82574L Gigabit Network Connection                                                       | 4        | 1.36%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 3        | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 3        | 1.02%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                                    | 3        | 1.02%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                                 | 3        | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 3        | 1.02%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 3        | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2        | 0.68%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 2        | 0.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 0.68%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 0.68%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 0.68%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2        | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2        | 0.68%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 2        | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                | 2        | 0.68%   |
| Nvidia nForce2 Ethernet Controller                                                            | 2        | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 2        | 0.68%   |
| Intel Ethernet Connection I217-V                                                              | 2        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 0.68%   |
| Intel 82567V-2 Gigabit Network Connection                                                     | 2        | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 2        | 0.68%   |
| Intel 82566DC-2 Gigabit Network Connection                                                    | 2        | 0.68%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                                       | 2        | 0.68%   |
| ZTE WCDMA MSM ZTE MSM                                                                         | 1        | 0.34%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.34%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.34%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 0.34%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 0.34%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                                               | 1        | 0.34%   |
| Sitecom Europe RTL8188S WLAN Adapter                                                          | 1        | 0.34%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                                     | 1        | 0.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 0.34%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.34%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.34%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 0.34%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 0.34%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 0.34%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 0.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1        | 0.34%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 0.34%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 27       | 32.14%  |
| Ralink Technology     | 13       | 15.48%  |
| Intel                 | 13       | 15.48%  |
| Qualcomm Atheros      | 9        | 10.71%  |
| TP-Link               | 4        | 4.76%   |
| Broadcom              | 4        | 4.76%   |
| Sitecom Europe        | 2        | 2.38%   |
| Microsoft             | 2        | 2.38%   |
| AVM                   | 2        | 2.38%   |
| Ralink                | 1        | 1.19%   |
| Mercucys              | 1        | 1.19%   |
| MediaTek              | 1        | 1.19%   |
| Edimax Technology     | 1        | 1.19%   |
| D-Link System         | 1        | 1.19%   |
| Broadcom Limited      | 1        | 1.19%   |
| Belkin Components     | 1        | 1.19%   |
| ASUSTek Computer      | 1        | 1.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 6        | 7.06%   |
| Intel Wi-Fi 6 AX200                                                                           | 5        | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 4.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 4        | 4.71%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 4.71%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 3        | 3.53%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 2        | 2.35%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 2.35%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 2.35%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 2.35%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2        | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 2.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2        | 2.35%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 2        | 2.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 2.35%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.18%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 1.18%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 1        | 1.18%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 1.18%   |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                                               | 1        | 1.18%   |
| Sitecom Europe RTL8188S WLAN Adapter                                                          | 1        | 1.18%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.18%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.18%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.18%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 1.18%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 1.18%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 1.18%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 1.18%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 1.18%   |
| Realtek 802.11ac NIC                                                                          | 1        | 1.18%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1        | 1.18%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.18%   |
| Microsoft XBOX ACC                                                                            | 1        | 1.18%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 1.18%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 1.18%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 1.18%   |
| Intel Wireless 8265 / 8275                                                                    | 1        | 1.18%   |
| Intel Wireless 7265                                                                           | 1        | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1        | 1.18%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 1.18%   |
| Intel Centrino Wireless-N 105                                                                 | 1        | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.18%   |
| Edimax 802.11ac WLAN Adapter                                                                  | 1        | 1.18%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B2) [Ralink RT3072]                          | 1        | 1.18%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 1.18%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1        | 1.18%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1        | 1.18%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1        | 1.18%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller                           | 1        | 1.18%   |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU]                   | 1        | 1.18%   |
| AVM Fritz!WLAN N [Atheros AR9001U]                                                            | 1        | 1.18%   |
| AVM FRITZ!WLAN AC 860                                                                         | 1        | 1.18%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                           | 1        | 1.18%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 99       | 49.75%  |
| Intel                            | 52       | 26.13%  |
| Qualcomm Atheros                 | 14       | 7.04%   |
| Nvidia                           | 9        | 4.52%   |
| Broadcom                         | 7        | 3.52%   |
| VIA Technologies                 | 4        | 2.01%   |
| Marvell Technology Group         | 3        | 1.51%   |
| Samsung Electronics              | 2        | 1.01%   |
| Broadcom Limited                 | 2        | 1.01%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.5%    |
| Silicon Integrated Systems [SiS] | 1        | 0.5%    |
| JMicron Technology               | 1        | 0.5%    |
| Huawei Technologies              | 1        | 0.5%    |
| DisplayLink                      | 1        | 0.5%    |
| ADMtek                           | 1        | 0.5%    |
| 3Com                             | 1        | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80       | 38.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8        | 3.86%   |
| Nvidia MCP61 Ethernet                                             | 7        | 3.38%   |
| Intel I211 Gigabit Network Connection                             | 7        | 3.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 2.42%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 1.93%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.93%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.93%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 1.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 1.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 1.45%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 1.45%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.97%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.97%   |
| Nvidia nForce2 Ethernet Controller                                | 2        | 0.97%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.97%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 0.97%   |
| Intel 82567V-2 Gigabit Network Connection                         | 2        | 0.97%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.97%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 2        | 0.97%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.97%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1        | 0.48%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.48%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1        | 0.48%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.48%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.48%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 0.48%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.48%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.48%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.48%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.48%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.48%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.48%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.48%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.48%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.48%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.48%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 0.48%   |
| Intel 82544EI Gigabit Ethernet Controller (Copper)                | 1        | 0.48%   |
| Huawei LYA-L09                                                    | 1        | 0.48%   |
| DisplayLink Plugable UD-3900                                      | 1        | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.48%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.48%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 0.48%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 0.48%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 185      | 70.88%  |
| WiFi     | 74       | 28.35%  |
| Modem    | 1        | 0.38%   |
| Unknown  | 1        | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 152      | 79.17%  |
| WiFi     | 40       | 20.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 131      | 70.81%  |
| 2     | 49       | 26.49%  |
| 3     | 4        | 2.16%   |
| 4     | 1        | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 160      | 82.9%   |
| Yes  | 33       | 17.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 12       | 32.43%  |
| Cambridge Silicon Radio         | 11       | 29.73%  |
| Realtek Semiconductor           | 5        | 13.51%  |
| Qualcomm Atheros Communications | 2        | 5.41%   |
| Broadcom                        | 2        | 5.41%   |
| ASUSTek Computer                | 2        | 5.41%   |
| MediaTek                        | 1        | 2.7%    |
| Dell                            | 1        | 2.7%    |
| Apple                           | 1        | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 29.73%  |
| Intel AX200 Bluetooth                               | 5        | 13.51%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3        | 8.11%   |
| Realtek Bluetooth Radio                             | 2        | 5.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 5.41%   |
| Intel Bluetooth wireless interface                  | 2        | 5.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 5.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 2.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 2.7%    |
| MediaTek Wireless_Device                            | 1        | 2.7%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 2.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2.7%    |
| Intel AX201 Bluetooth                               | 1        | 2.7%    |
| Dell BT Mini-Receiver                               | 1        | 2.7%    |
| Broadcom HP Bluethunder                             | 1        | 2.7%    |
| Broadcom BCM2045 Bluetooth                          | 1        | 2.7%    |
| Apple Bluetooth USB Host Controller                 | 1        | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 117      | 40.07%  |
| Nvidia                           | 75       | 25.68%  |
| AMD                              | 55       | 18.84%  |
| C-Media Electronics              | 12       | 4.11%   |
| VIA Technologies                 | 8        | 2.74%   |
| Generalplus Technology           | 4        | 1.37%   |
| Creative Labs                    | 4        | 1.37%   |
| GN Netcom                        | 3        | 1.03%   |
| Silicon Integrated Systems [SiS] | 2        | 0.68%   |
| Logitech                         | 2        | 0.68%   |
| Yamaha                           | 1        | 0.34%   |
| Xilinx                           | 1        | 0.34%   |
| Tenx Technology                  | 1        | 0.34%   |
| Plantronics                      | 1        | 0.34%   |
| M-Audio                          | 1        | 0.34%   |
| JMTek                            | 1        | 0.34%   |
| GYROCOM C&C                      | 1        | 0.34%   |
| Focusrite-Novation               | 1        | 0.34%   |
| Evolution Electronics            | 1        | 0.34%   |
| Creative Technology              | 1        | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 21       | 6.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 18       | 5.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 13       | 3.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 11       | 3.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 11       | 3.37%   |
| AMD Family 17h/19h HD Audio Controller                                            | 11       | 3.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 10       | 3.07%   |
| Nvidia High Definition Audio Controller                                           | 9        | 2.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 9        | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                        | 9        | 2.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 8        | 2.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 8        | 2.45%   |
| Nvidia MCP61 High Definition Audio                                                | 7        | 2.15%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 2.15%   |
| Nvidia GM206 High Definition Audio Controller                                     | 7        | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6        | 1.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 1.84%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 5        | 1.53%   |
| AMD Starship/Matisse HD Audio Controller                                          | 5        | 1.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 1.53%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 4        | 1.23%   |
| Nvidia GF116 High Definition Audio Controller                                     | 4        | 1.23%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.23%   |
| Generalplus Technology USB Audio Device                                           | 4        | 1.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3        | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.92%   |
| Nvidia GK104 HDMI Audio Controller                                                | 3        | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 0.92%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 0.92%   |
| AMD FCH Azalia Controller                                                         | 3        | 0.92%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 0.92%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 2        | 0.61%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                   | 2        | 0.61%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 0.61%   |
| Nvidia nForce2 AC97 Audio Controler (MCP)                                         | 2        | 0.61%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 0.61%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 0.61%   |
| Nvidia GF114 HDMI Audio Controller                                                | 2        | 0.61%   |
| Nvidia GF104 High Definition Audio Controller                                     | 2        | 0.61%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2        | 0.61%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 0.61%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.61%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 0.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 0.61%   |
| Intel 8 Series HD Audio Controller                                                | 2        | 0.61%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 0.61%   |
| C-Media Electronics USB Audio Device                                              | 2        | 0.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 0.61%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 0.61%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 0.61%   |
| Yamaha AG06/AG03                                                                  | 1        | 0.31%   |
| Xilinx RME Hammerfall DSP                                                         | 1        | 0.31%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 1        | 0.31%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                | 1        | 0.31%   |
| Tenx Technology USB AUDIO                                                         | 1        | 0.31%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 15       | 33.33%  |
| Kingston            | 6        | 13.33%  |
| Crucial             | 6        | 13.33%  |
| Samsung Electronics | 4        | 8.89%   |
| SK hynix            | 3        | 6.67%   |
| Micron Technology   | 3        | 6.67%   |
| G.Skill             | 2        | 4.44%   |
| PLEXHD              | 1        | 2.22%   |
| Nanya Technology    | 1        | 2.22%   |
| Kingmax             | 1        | 2.22%   |
| Exceleram           | 1        | 2.22%   |
| Corsair             | 1        | 2.22%   |
| A-DATA Technology   | 1        | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2        | 4.26%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                   | 1        | 2.13%   |
| Unknown RAM Module 512MB DIMM 667MT/s                     | 1        | 2.13%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1        | 2.13%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 2.13%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 2.13%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 2.13%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 2.13%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 1        | 2.13%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s               | 1        | 2.13%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                | 1        | 2.13%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                | 1        | 2.13%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                    | 1        | 2.13%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 1        | 2.13%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                    | 1        | 2.13%   |
| Unknown RAM Module 1024MB DIMM                            | 1        | 2.13%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s        | 1        | 2.13%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s             | 1        | 2.13%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s     | 1        | 2.13%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s      | 1        | 2.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 2.13%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 2667MT/s   | 1        | 2.13%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s    | 1        | 2.13%   |
| PLEXHD RAM Module 8192MB DIMM DDR3 1333MT/s               | 1        | 2.13%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s         | 1        | 2.13%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s    | 1        | 2.13%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s       | 1        | 2.13%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s      | 1        | 2.13%   |
| Kingston RAM KP223C-ELD 2048MB DIMM DDR3 1600MT/s         | 1        | 2.13%   |
| Kingston RAM KHX3600C17D4/16GX 16GB DIMM DDR4 3800MT/s    | 1        | 2.13%   |
| Kingston RAM 99U4342-016.A00G 4096MB SODIMM DDR3 1600MT/s | 1        | 2.13%   |
| Kingston RAM 9965589-033.D00G 8192MB DIMM DDR4 2400MT/s   | 1        | 2.13%   |
| Kingston RAM 9905403-420.A00LF 4GB DIMM DDR3 2133MT/s     | 1        | 2.13%   |
| Kingston RAM 2G-UDIMM 2GB DIMM DDR2 800MT/s               | 1        | 2.13%   |
| Kingmax RAM FLFF65F-C8KM9 4096MB DIMM DDR3 1067MT/s       | 1        | 2.13%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s    | 1        | 2.13%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s     | 1        | 2.13%   |
| Exceleram RAM E30144A 4096MB DIMM DDR3 800MT/s            | 1        | 2.13%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s     | 1        | 2.13%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s     | 1        | 2.13%   |
| Crucial RAM CT51264BA160B 4GB DIMM DDR3 1600MT/s          | 1        | 2.13%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s   | 1        | 2.13%   |
| Crucial RAM BLT8G4D26BFT4K.C8FD 8GB DIMM DDR4 2666MT/s    | 1        | 2.13%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s     | 1        | 2.13%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s  | 1        | 2.13%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s               | 1        | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 16       | 37.21%  |
| DDR4    | 12       | 27.91%  |
| Unknown | 5        | 11.63%  |
| DDR2    | 4        | 9.3%    |
| SDRAM   | 3        | 6.98%   |
| DDR     | 3        | 6.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 38       | 90.48%  |
| SODIMM | 4        | 9.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 12       | 27.91%  |
| 4096  | 10       | 23.26%  |
| 2048  | 10       | 23.26%  |
| 16384 | 5        | 11.63%  |
| 1024  | 4        | 9.3%    |
| 32768 | 1        | 2.33%   |
| 512   | 1        | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 12       | 27.27%  |
| 800     | 5        | 11.36%  |
| 1333    | 4        | 9.09%   |
| 667     | 4        | 9.09%   |
| 3200    | 2        | 4.55%   |
| 2667    | 2        | 4.55%   |
| 2666    | 2        | 4.55%   |
| 2400    | 2        | 4.55%   |
| Unknown | 2        | 4.55%   |
| 4000    | 1        | 2.27%   |
| 3800    | 1        | 2.27%   |
| 3500    | 1        | 2.27%   |
| 3400    | 1        | 2.27%   |
| 2133    | 1        | 2.27%   |
| 1866    | 1        | 2.27%   |
| 1067    | 1        | 2.27%   |
| 533     | 1        | 2.27%   |
| 400     | 1        | 2.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 40%     |
| Brother Industries  | 3        | 20%     |
| Samsung Electronics | 2        | 13.33%  |
| Canon               | 2        | 13.33%  |
| Ricoh               | 1        | 6.67%   |
| Konica Minolta      | 1        | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Brother MFC-L2685DW              | 2        | 13.33%  |
| Samsung SCX-3400 Series          | 1        | 6.67%   |
| Samsung ML-1670 Series           | 1        | 6.67%   |
| Ricoh SP C260SFNw                | 1        | 6.67%   |
| Konica Minolta 185               | 1        | 6.67%   |
| HP OfficeJet Pro 8730            | 1        | 6.67%   |
| HP LaserJet P1006                | 1        | 6.67%   |
| HP LaserJet 3050                 | 1        | 6.67%   |
| HP DeskJet F4200 series          | 1        | 6.67%   |
| HP Deskjet 2540 series           | 1        | 6.67%   |
| HP Deskjet 1050 J410             | 1        | 6.67%   |
| Canon LaserShot LBP-1120 Printer | 1        | 6.67%   |
| Canon iP4200                     | 1        | 6.67%   |
| Brother HL-L2300D series         | 1        | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 1        | 33.33%  |
| Hewlett-Packard | 1        | 33.33%  |
| Canon           | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 33.33%  |
| HP ScanJet 3800c                              | 1        | 33.33%  |
| Canon CanoScan LiDE 110                       | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 12       | 40%     |
| Microsoft                     | 3        | 10%     |
| Z-Star Microelectronics       | 2        | 6.67%   |
| Xiongmai                      | 1        | 3.33%   |
| WCM_USB                       | 1        | 3.33%   |
| Sunplus Innovation Technology | 1        | 3.33%   |
| Service & Quality Technology  | 1        | 3.33%   |
| OmniVision Technologies       | 1        | 3.33%   |
| Nintendo                      | 1        | 3.33%   |
| Microdia                      | 1        | 3.33%   |
| MacroSilicon                  | 1        | 3.33%   |
| KYE Systems (Mouse Systems)   | 1        | 3.33%   |
| Generalplus Technology        | 1        | 3.33%   |
| Creative Technology           | 1        | 3.33%   |
| Chicony Electronics           | 1        | 3.33%   |
| ARC International             | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Logitech Webcam C270                               | 5        | 16.67%  |
| Z-Star Venus USB2.0 Camera                         | 2        | 6.67%   |
| Microsoft LifeCam HD-3000                          | 2        | 6.67%   |
| Logitech Webcam C310                               | 2        | 6.67%   |
| Xiongmai web camera                                | 1        | 3.33%   |
| WCM_USB WEB CAM                                    | 1        | 3.33%   |
| Sunplus Full HD webcam                             | 1        | 3.33%   |
| Service & Quality USB PC Camera                    | 1        | 3.33%   |
| OmniVision Integrated Webcam for Dell XPS 2010     | 1        | 3.33%   |
| Nintendo USB Camera                                | 1        | 3.33%   |
| Microsoft MicrosoftÂ LifeCam VX-5500              | 1        | 3.33%   |
| Microdia Amcrest AWC2198 USB Webcam                | 1        | 3.33%   |
| MacroSilicon USB3.0 HD VIDEO                       | 1        | 3.33%   |
| Logitech Webcam Pro 9000                           | 1        | 3.33%   |
| Logitech Webcam C930e                              | 1        | 3.33%   |
| Logitech Webcam C925e                              | 1        | 3.33%   |
| Logitech Webcam C210                               | 1        | 3.33%   |
| Logitech HD Pro Webcam C920                        | 1        | 3.33%   |
| KYE Systems (Mouse Systems) Genius iSlim 2000AF V2 | 1        | 3.33%   |
| Generalplus 808 Camera                             | 1        | 3.33%   |
| Creative Live! Cam Sync HD [VF0770]                | 1        | 3.33%   |
| Chicony HP High Definition 1MP Webcam              | 1        | 3.33%   |
| ARC International Camera                           | 1        | 3.33%   |

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
| 0     | 129      | 68.25%  |
| 1     | 52       | 27.51%  |
| 2     | 4        | 2.12%   |
| 4     | 2        | 1.06%   |
| 3     | 2        | 1.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 33       | 47.83%  |
| Net/wireless             | 19       | 27.54%  |
| Communication controller | 5        | 7.25%   |
| Unassigned class         | 2        | 2.9%    |
| Network                  | 2        | 2.9%    |
| Net/ethernet             | 2        | 2.9%    |
| Storage/ide              | 1        | 1.45%   |
| Multimedia controller    | 1        | 1.45%   |
| Modem                    | 1        | 1.45%   |
| Fingerprint reader       | 1        | 1.45%   |
| Chipcard                 | 1        | 1.45%   |
| Camera                   | 1        | 1.45%   |

