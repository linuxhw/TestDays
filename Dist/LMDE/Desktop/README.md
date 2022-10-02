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

Total: 305

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire XC-1660G V:1.1       | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell          | 082WXT A01                  | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Gateway       | DX4870                      | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| Digiboard     | NM70-TI                     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Dell          | 0XC837                      | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| MSI           | B360M MORTAR                | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek       | PRIME H610M-E D4            | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| ASRock        | G41M-S3                     | [2cdcaebd43](https://linux-hardware.org/?probe=2cdcaebd43) | Sep 10, 2022 |
| Dell          | 0FJ030                      | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI           | B450I GAMING PLUS AC        | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Pegatron      | 2A9Eh                       | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek       | P8H77-V                     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines     | EL1352G                     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| ASUSTek       | P5K-E                       | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Dell          | 042P49 A00                  | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | P5QPL-AM                    | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI           | Z170A GAMING PRO            | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| MSI           | B85I                        | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Gigabyte      | H97-Gaming 3                | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
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
| LMDE 4 | 148      | 71.84%  |
| LMDE 5 | 48       | 23.3%   |
| LMDE 3 | 8        | 3.88%   |
| LMDE 2 | 2        | 0.97%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| LMDE | 204      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 4.19.0-16-amd64      | 23       | 10.18%  |
| 4.19.0-17-amd64      | 20       | 8.85%   |
| 4.19.0-18-amd64      | 19       | 8.41%   |
| 4.19.0-14-amd64      | 18       | 7.96%   |
| 4.19.0-13-amd64      | 17       | 7.52%   |
| 4.19.0-8-amd64       | 15       | 6.64%   |
| 5.10.0-17-amd64      | 11       | 4.87%   |
| 5.10.0-14-amd64      | 10       | 4.42%   |
| 5.10.0-13-amd64      | 10       | 4.42%   |
| 5.10.0-12-amd64      | 9        | 3.98%   |
| 4.19.0-12-amd64      | 9        | 3.98%   |
| 4.19.0-10-amd64      | 8        | 3.54%   |
| 4.19.0-9-amd64       | 7        | 3.1%    |
| 5.10.0-18-amd64      | 4        | 1.77%   |
| 4.9.0-8-amd64        | 4        | 1.77%   |
| 4.19.0-11-amd64      | 4        | 1.77%   |
| 4.19.0-17-686        | 3        | 1.33%   |
| 4.19.0-16-686        | 3        | 1.33%   |
| 4.19.0-14-686        | 3        | 1.33%   |
| 5.10.0-16-amd64      | 2        | 0.88%   |
| 5.10.0-15-amd64      | 2        | 0.88%   |
| 4.19.0-8-686         | 2        | 0.88%   |
| 4.19.0-20-amd64      | 2        | 0.88%   |
| 4.19.0-19-686        | 2        | 0.88%   |
| 4.19.0-18-686        | 2        | 0.88%   |
| 4.19.0-13-686        | 2        | 0.88%   |
| 3.16.0-4-amd64       | 2        | 0.88%   |
| 5.8.0-3-amd64        | 1        | 0.44%   |
| 5.6.0-0.bpo.2-amd64  | 1        | 0.44%   |
| 5.4.0-0.bpo.4-amd64  | 1        | 0.44%   |
| 5.10.0-7-amd64       | 1        | 0.44%   |
| 5.10.0-13-686        | 1        | 0.44%   |
| 4.9.0-9-amd64        | 1        | 0.44%   |
| 4.9.0-17-amd64       | 1        | 0.44%   |
| 4.9.0-11-amd64       | 1        | 0.44%   |
| 4.19.0-9-686         | 1        | 0.44%   |
| 4.19.0-21-amd64      | 1        | 0.44%   |
| 4.19.0-19-amd64      | 1        | 0.44%   |
| 4.19.0-12-686        | 1        | 0.44%   |
| 4.17.0-0.bpo.3-amd64 | 1        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 144      | 69.9%   |
| 5.10.0  | 49       | 23.79%  |
| 4.9.0   | 7        | 3.4%    |
| 3.16.0  | 2        | 0.97%   |
| 5.8.0   | 1        | 0.49%   |
| 5.6.0   | 1        | 0.49%   |
| 5.4.0   | 1        | 0.49%   |
| 4.17.0  | 1        | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 144      | 69.9%   |
| 5.10    | 49       | 23.79%  |
| 4.9     | 7        | 3.4%    |
| 3.16    | 2        | 0.97%   |
| 5.8     | 1        | 0.49%   |
| 5.6     | 1        | 0.49%   |
| 5.4     | 1        | 0.49%   |
| 4.17    | 1        | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 184      | 90.2%   |
| i686   | 20       | 9.8%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 176      | 85.85%  |
| Cinnamon   | 15       | 7.32%   |
| MATE       | 5        | 2.44%   |
| Unknown    | 3        | 1.46%   |
| XFCE       | 2        | 0.98%   |
| GNOME      | 2        | 0.98%   |
| LXQt       | 1        | 0.49%   |
| LXDE       | 1        | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 204      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 166      | 81.37%  |
| LightDM | 20       | 9.8%    |
| TDM     | 15       | 7.35%   |
| MDM     | 2        | 0.98%   |
| GDM     | 1        | 0.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 57       | 27.94%  |
| de_DE   | 21       | 10.29%  |
| pt_BR   | 19       | 9.31%   |
| fr_FR   | 15       | 7.35%   |
| ru_RU   | 9        | 4.41%   |
| pl_PL   | 9        | 4.41%   |
| Unknown | 9        | 4.41%   |
| en_GB   | 8        | 3.92%   |
| it_IT   | 5        | 2.45%   |
| en_CA   | 5        | 2.45%   |
| sv_SE   | 4        | 1.96%   |
| es_ES   | 4        | 1.96%   |
| en_AU   | 4        | 1.96%   |
| nl_BE   | 3        | 1.47%   |
| es_AR   | 3        | 1.47%   |
| pt_PT   | 2        | 0.98%   |
| hu_HU   | 2        | 0.98%   |
| fr_CA   | 2        | 0.98%   |
| cs_CZ   | 2        | 0.98%   |
| ar_EG   | 2        | 0.98%   |
| unm_US  | 1        | 0.49%   |
| uk_UA   | 1        | 0.49%   |
| tr_TR   | 1        | 0.49%   |
| sk_SK   | 1        | 0.49%   |
| nb_NO   | 1        | 0.49%   |
| it_CH   | 1        | 0.49%   |
| fi_FI   | 1        | 0.49%   |
| et_EE   | 1        | 0.49%   |
| es_UY   | 1        | 0.49%   |
| es_NI   | 1        | 0.49%   |
| es_MX   | 1        | 0.49%   |
| es_EC   | 1        | 0.49%   |
| es_CO   | 1        | 0.49%   |
| es_CL   | 1        | 0.49%   |
| en_ZA   | 1        | 0.49%   |
| el_GR   | 1        | 0.49%   |
| de_AT   | 1        | 0.49%   |
| ca_ES   | 1        | 0.49%   |
| bg_BG   | 1        | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 141      | 69.12%  |
| EFI  | 63       | 30.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 190      | 92.68%  |
| Btrfs   | 6        | 2.93%   |
| Unknown | 5        | 2.44%   |
| Tmpfs   | 2        | 0.98%   |
| Overlay | 1        | 0.49%   |
| Ext3    | 1        | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 166      | 80.58%  |
| GPT     | 22       | 10.68%  |
| MBR     | 18       | 8.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 193      | 93.69%  |
| Yes       | 13       | 6.31%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 187      | 91.67%  |
| Yes       | 17       | 8.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 48       | 23.53%  |
| Gigabyte Technology | 28       | 13.73%  |
| MSI                 | 25       | 12.25%  |
| Dell                | 21       | 10.29%  |
| Hewlett-Packard     | 15       | 7.35%   |
| ASRock              | 14       | 6.86%   |
| Intel               | 8        | 3.92%   |
| Acer                | 8        | 3.92%   |
| Lenovo              | 5        | 2.45%   |
| Unknown             | 5        | 2.45%   |
| ECS                 | 4        | 1.96%   |
| Pegatron            | 3        | 1.47%   |
| Foxconn             | 3        | 1.47%   |
| OEM                 | 2        | 0.98%   |
| EVGA                | 2        | 0.98%   |
| eMachines           | 2        | 0.98%   |
| Biostar             | 2        | 0.98%   |
| Semp Toshiba        | 1        | 0.49%   |
| Positivo            | 1        | 0.49%   |
| PCWare              | 1        | 0.49%   |
| NEC Computers       | 1        | 0.49%   |
| Gateway             | 1        | 0.49%   |
| Fujitsu Siemens     | 1        | 0.49%   |
| Digiboard           | 1        | 0.49%   |
| DFI                 | 1        | 0.49%   |
| Alienware           | 1        | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 6        | 2.94%   |
| HP Pavilion Desktop 590-p0xxx   | 2        | 0.98%   |
| Gigabyte B450M DS3H             | 2        | 0.98%   |
| Dell OptiPlex 780               | 2        | 0.98%   |
| Dell OptiPlex 3010              | 2        | 0.98%   |
| ASUS All Series                 | 2        | 0.98%   |
| Semp Toshiba STI                | 1        | 0.49%   |
| Positivo POS-EIH61CE            | 1        | 0.49%   |
| Pegatron Pro 3015 Microtower PC | 1        | 0.49%   |
| Pegatron Elite 7300 Series MT   | 1        | 0.49%   |
| Pegatron 520-1188la             | 1        | 0.49%   |
| PCWare IPMH81G1                 | 1        | 0.49%   |
| OEM 45CMX/45GMX/45CMX-K         | 1        | 0.49%   |
| NEC Computers IMEDIA S9509      | 1        | 0.49%   |
| MSI PX714AA-ABH t3040.nl        | 1        | 0.49%   |
| MSI MS-7C52                     | 1        | 0.49%   |
| MSI MS-7C51                     | 1        | 0.49%   |
| MSI MS-7B79                     | 1        | 0.49%   |
| MSI MS-7B23                     | 1        | 0.49%   |
| MSI MS-7B17                     | 1        | 0.49%   |
| MSI MS-7A40                     | 1        | 0.49%   |
| MSI MS-7A38                     | 1        | 0.49%   |
| MSI MS-7984                     | 1        | 0.49%   |
| MSI MS-7977                     | 1        | 0.49%   |
| MSI MS-7974                     | 1        | 0.49%   |
| MSI MS-7918                     | 1        | 0.49%   |
| MSI MS-7851                     | 1        | 0.49%   |
| MSI MS-7850                     | 1        | 0.49%   |
| MSI MS-7823                     | 1        | 0.49%   |
| MSI MS-7817                     | 1        | 0.49%   |
| MSI MS-7815                     | 1        | 0.49%   |
| MSI MS-7751                     | 1        | 0.49%   |
| MSI MS-7383                     | 1        | 0.49%   |
| MSI MS-7267                     | 1        | 0.49%   |
| MSI MS-7142                     | 1        | 0.49%   |
| MSI MS-6785                     | 1        | 0.49%   |
| MSI MS-6570                     | 1        | 0.49%   |
| MSI ESPRIMO P2440               | 1        | 0.49%   |
| MSI *MF                         | 1        | 0.49%   |
| Lenovo V55t-15ARE 11KJ0036TX    | 1        | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 11       | 5.39%   |
| ASUS PRIME           | 8        | 3.92%   |
| HP Compaq            | 6        | 2.94%   |
| Unknown              | 6        | 2.94%   |
| Dell Precision       | 5        | 2.45%   |
| Acer Aspire          | 5        | 2.45%   |
| Lenovo ThinkCentre   | 3        | 1.47%   |
| Gigabyte X570        | 3        | 1.47%   |
| Dell Inspiron        | 3        | 1.47%   |
| ASUS ROG             | 3        | 1.47%   |
| Acer Veriton         | 3        | 1.47%   |
| HP Pavilion          | 2        | 0.98%   |
| Gigabyte Z390        | 2        | 0.98%   |
| Gigabyte B450M       | 2        | 0.98%   |
| Foxconn 945          | 2        | 0.98%   |
| ASUS P5KPL-AM        | 2        | 0.98%   |
| ASUS All             | 2        | 0.98%   |
| Semp Toshiba STI     | 1        | 0.49%   |
| Positivo POS-EIH61CE | 1        | 0.49%   |
| Pegatron Pro         | 1        | 0.49%   |
| Pegatron Elite       | 1        | 0.49%   |
| Pegatron 520-1188la  | 1        | 0.49%   |
| PCWare IPMH81G1      | 1        | 0.49%   |
| OEM 45CMX            | 1        | 0.49%   |
| NEC Computers IMEDIA | 1        | 0.49%   |
| MSI PX714AA-ABH      | 1        | 0.49%   |
| MSI MS-7C52          | 1        | 0.49%   |
| MSI MS-7C51          | 1        | 0.49%   |
| MSI MS-7B79          | 1        | 0.49%   |
| MSI MS-7B23          | 1        | 0.49%   |
| MSI MS-7B17          | 1        | 0.49%   |
| MSI MS-7A40          | 1        | 0.49%   |
| MSI MS-7A38          | 1        | 0.49%   |
| MSI MS-7984          | 1        | 0.49%   |
| MSI MS-7977          | 1        | 0.49%   |
| MSI MS-7974          | 1        | 0.49%   |
| MSI MS-7918          | 1        | 0.49%   |
| MSI MS-7851          | 1        | 0.49%   |
| MSI MS-7850          | 1        | 0.49%   |
| MSI MS-7823          | 1        | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 28       | 13.73%  |
| 2009 | 18       | 8.82%   |
| 2018 | 16       | 7.84%   |
| 2010 | 16       | 7.84%   |
| 2007 | 16       | 7.84%   |
| 2019 | 14       | 6.86%   |
| 2014 | 14       | 6.86%   |
| 2011 | 12       | 5.88%   |
| 2008 | 12       | 5.88%   |
| 2013 | 10       | 4.9%    |
| 2006 | 10       | 4.9%    |
| 2017 | 8        | 3.92%   |
| 2015 | 7        | 3.43%   |
| 2021 | 5        | 2.45%   |
| 2020 | 5        | 2.45%   |
| 2003 | 4        | 1.96%   |
| 2016 | 3        | 1.47%   |
| 2005 | 3        | 1.47%   |
| 2022 | 2        | 0.98%   |
| 2004 | 1        | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 204      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 203      | 98.54%  |
| Enabled  | 3        | 1.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 204      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 51       | 24.52%  |
| 3.01-4.0    | 44       | 21.15%  |
| 16.01-24.0  | 36       | 17.31%  |
| 4.01-8.0    | 29       | 13.94%  |
| 32.01-64.0  | 17       | 8.17%   |
| 2.01-3.0    | 11       | 5.29%   |
| 1.01-2.0    | 10       | 4.81%   |
| 0.51-1.0    | 4        | 1.92%   |
| 24.01-32.0  | 3        | 1.44%   |
| 64.01-256.0 | 3        | 1.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 96       | 44.65%  |
| 2.01-3.0   | 49       | 22.79%  |
| 3.01-4.0   | 28       | 13.02%  |
| 0.51-1.0   | 23       | 10.7%   |
| 4.01-8.0   | 17       | 7.91%   |
| 32.01-64.0 | 1        | 0.47%   |
| 8.01-16.0  | 1        | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 96       | 45.71%  |
| 2      | 60       | 28.57%  |
| 3      | 26       | 12.38%  |
| 4      | 16       | 7.62%   |
| 7      | 4        | 1.9%    |
| 5      | 4        | 1.9%    |
| 6      | 3        | 1.43%   |
| 8      | 1        | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 116      | 55.77%  |
| No        | 92       | 44.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 204      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 61.72%  |
| Yes       | 80       | 38.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 165      | 80.49%  |
| Yes       | 40       | 19.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 30       | 14.71%  |
| Germany      | 23       | 11.27%  |
| Brazil       | 21       | 10.29%  |
| France       | 15       | 7.35%   |
| Russia       | 12       | 5.88%   |
| Canada       | 9        | 4.41%   |
| Italy        | 8        | 3.92%   |
| Poland       | 7        | 3.43%   |
| UK           | 6        | 2.94%   |
| Spain        | 6        | 2.94%   |
| Ukraine      | 5        | 2.45%   |
| Netherlands  | 5        | 2.45%   |
| Australia    | 5        | 2.45%   |
| Sweden       | 4        | 1.96%   |
| Bulgaria     | 3        | 1.47%   |
| Belgium      | 3        | 1.47%   |
| Argentina    | 3        | 1.47%   |
| Turkey       | 2        | 0.98%   |
| Puerto Rico  | 2        | 0.98%   |
| Portugal     | 2        | 0.98%   |
| Mexico       | 2        | 0.98%   |
| Hungary      | 2        | 0.98%   |
| Greece       | 2        | 0.98%   |
| Finland      | 2        | 0.98%   |
| Czechia      | 2        | 0.98%   |
| Austria      | 2        | 0.98%   |
| Venezuela    | 1        | 0.49%   |
| Uruguay      | 1        | 0.49%   |
| South Africa | 1        | 0.49%   |
| Slovakia     | 1        | 0.49%   |
| Serbia       | 1        | 0.49%   |
| Romania      | 1        | 0.49%   |
| Philippines  | 1        | 0.49%   |
| Pakistan     | 1        | 0.49%   |
| Norway       | 1        | 0.49%   |
| Nicaragua    | 1        | 0.49%   |
| Luxembourg   | 1        | 0.49%   |
| Latvia       | 1        | 0.49%   |
| India        | 1        | 0.49%   |
| Estonia      | 1        | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Hamburg               | 4        | 1.83%   |
| Paris                 | 3        | 1.38%   |
| Melbourne             | 3        | 1.38%   |
| Warsaw                | 2        | 0.92%   |
| Sofia                 | 2        | 0.92%   |
| San Antonio           | 2        | 0.92%   |
| Rio de Janeiro        | 2        | 0.92%   |
| Perth                 | 2        | 0.92%   |
| Moscow                | 2        | 0.92%   |
| Montreal              | 2        | 0.92%   |
| Milan                 | 2        | 0.92%   |
| Marseille             | 2        | 0.92%   |
| Helsinki              | 2        | 0.92%   |
| Frankfurt am Main     | 2        | 0.92%   |
| Florianópolis        | 2        | 0.92%   |
| Belo Horizonte        | 2        | 0.92%   |
| Bayamón              | 2        | 0.92%   |
| Athens                | 2        | 0.92%   |
| Amsterdam             | 2        | 0.92%   |
| Zaporozhe             | 1        | 0.46%   |
| Zaandam               | 1        | 0.46%   |
| Wroclaw               | 1        | 0.46%   |
| Wijchen               | 1        | 0.46%   |
| Weiden                | 1        | 0.46%   |
| Warmsen               | 1        | 0.46%   |
| Voronezh              | 1        | 0.46%   |
| Volta Redonda         | 1        | 0.46%   |
| Vitória da Conquista | 1        | 0.46%   |
| Vincennes             | 1        | 0.46%   |
| Vienna                | 1        | 0.46%   |
| Victoria              | 1        | 0.46%   |
| Vicente Guerrero      | 1        | 0.46%   |
| Valencia              | 1        | 0.46%   |
| Ukhta                 | 1        | 0.46%   |
| Trindade              | 1        | 0.46%   |
| Trieste               | 1        | 0.46%   |
| Tres Rios             | 1        | 0.46%   |
| Toronto               | 1        | 0.46%   |
| Tolyatti              | 1        | 0.46%   |
| Toledo                | 1        | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 79       | 135    | 23.8%   |
| Seagate             | 57       | 91     | 17.17%  |
| Samsung Electronics | 51       | 78     | 15.36%  |
| Kingston            | 19       | 22     | 5.72%   |
| Toshiba             | 17       | 23     | 5.12%   |
| Hitachi             | 16       | 20     | 4.82%   |
| Crucial             | 14       | 18     | 4.22%   |
| SanDisk             | 13       | 16     | 3.92%   |
| A-DATA Technology   | 9        | 9      | 2.71%   |
| Phison              | 6        | 7      | 1.81%   |
| Intel               | 6        | 6      | 1.81%   |
| China               | 4        | 4      | 1.2%    |
| OCZ                 | 3        | 5      | 0.9%    |
| Maxtor              | 3        | 5      | 0.9%    |
| Intenso             | 3        | 4      | 0.9%    |
| Transcend           | 2        | 3      | 0.6%    |
| TCSUNBOW            | 2        | 2      | 0.6%    |
| Micron Technology   | 2        | 2      | 0.6%    |
| CT500MX5            | 2        | 2      | 0.6%    |
| XrayDisk            | 1        | 2      | 0.3%    |
| Unknown             | 1        | 2      | 0.3%    |
| Team                | 1        | 2      | 0.3%    |
| Smartbuy            | 1        | 1      | 0.3%    |
| SK hynix            | 1        | 1      | 0.3%    |
| Silicon Motion      | 1        | 1      | 0.3%    |
| SABRENT             | 1        | 1      | 0.3%    |
| Plextor             | 1        | 2      | 0.3%    |
| Patriot             | 1        | 1      | 0.3%    |
| OCZ-VERTEX          | 1        | 1      | 0.3%    |
| Netac               | 1        | 1      | 0.3%    |
| Mushkin             | 1        | 1      | 0.3%    |
| KingSpec            | 1        | 1      | 0.3%    |
| Kingmax             | 1        | 1      | 0.3%    |
| KESU                | 1        | 2      | 0.3%    |
| HPE                 | 1        | 4      | 0.3%    |
| Hewlett-Packard     | 1        | 1      | 0.3%    |
| GOODRAM             | 1        | 1      | 0.3%    |
| Gigabyte Technology | 1        | 1      | 0.3%    |
| Fujitsu             | 1        | 1      | 0.3%    |
| ExcelStor           | 1        | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB        | 7        | 1.79%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 1.02%   |
| Toshiba DT01ACA100 1TB           | 4        | 1.02%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 1.02%   |
| Samsung SSD 850 EVO 500GB        | 4        | 1.02%   |
| Kingston SA400S37240G 240GB SSD  | 4        | 1.02%   |
| Kingston SA400S37120G 120GB SSD  | 4        | 1.02%   |
| Toshiba HDWD110 1TB              | 3        | 0.77%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 0.77%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 0.77%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 0.77%   |
| Samsung SSD 860 EVO 500GB        | 3        | 0.77%   |
| Samsung NVMe SSD Drive 500GB     | 3        | 0.77%   |
| Samsung HD322HJ 320GB            | 3        | 0.77%   |
| Samsung HD161HJ 160GB            | 3        | 0.77%   |
| Samsung HD103SJ 1TB              | 3        | 0.77%   |
| Kingston SA400S37480G 480GB SSD  | 3        | 0.77%   |
| Crucial CT480BX500SSD1 480GB     | 3        | 0.77%   |
| Crucial CT240BX500SSD1 240GB     | 3        | 0.77%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2        | 0.51%   |
| WDC WD5000AAKX-00U6AA0 500GB     | 2        | 0.51%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 2        | 0.51%   |
| WDC WD40EFRX-68N32N0 4TB         | 2        | 0.51%   |
| WDC WD3200AAKS-00L9A0 320GB      | 2        | 0.51%   |
| WDC WD2500AAKX-753CA1 250GB      | 2        | 0.51%   |
| WDC WD1600AABS-00PRA0 160GB      | 2        | 0.51%   |
| WDC WD10EZEX-60WN4A0 1TB         | 2        | 0.51%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 2        | 0.51%   |
| Toshiba DT01ACA200 2TB           | 2        | 0.51%   |
| Seagate ST500LT012-1DG142 500GB  | 2        | 0.51%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 0.51%   |
| Seagate ST3500418AS 500GB        | 2        | 0.51%   |
| Seagate ST3160021A 160GB         | 2        | 0.51%   |
| Seagate ST31000528AS 1TB         | 2        | 0.51%   |
| Seagate ST2000LX001-1RG174 2TB   | 2        | 0.51%   |
| Seagate ST2000DM001-9YN164 2TB   | 2        | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 0.51%   |
| Seagate Expansion 1TB            | 2        | 0.51%   |
| SanDisk SDSSDA240G 240GB         | 2        | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 71       | 125    | 37.17%  |
| Seagate             | 57       | 91     | 29.84%  |
| Samsung Electronics | 25       | 33     | 13.09%  |
| Hitachi             | 16       | 20     | 8.38%   |
| Toshiba             | 13       | 15     | 6.81%   |
| Maxtor              | 3        | 5      | 1.57%   |
| Unknown             | 1        | 1      | 0.52%   |
| KESU                | 1        | 2      | 0.52%   |
| HPE                 | 1        | 4      | 0.52%   |
| Fujitsu             | 1        | 1      | 0.52%   |
| ExcelStor           | 1        | 1      | 0.52%   |
| ASMedia             | 1        | 1      | 0.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 20       | 27     | 16.53%  |
| Kingston            | 17       | 20     | 14.05%  |
| Crucial             | 14       | 18     | 11.57%  |
| SanDisk             | 12       | 15     | 9.92%   |
| A-DATA Technology   | 9        | 9      | 7.44%   |
| WDC                 | 8        | 8      | 6.61%   |
| Toshiba             | 4        | 8      | 3.31%   |
| Intel               | 4        | 4      | 3.31%   |
| China               | 4        | 4      | 3.31%   |
| OCZ                 | 3        | 5      | 2.48%   |
| Intenso             | 3        | 4      | 2.48%   |
| Transcend           | 2        | 3      | 1.65%   |
| TCSUNBOW            | 2        | 2      | 1.65%   |
| Micron Technology   | 2        | 2      | 1.65%   |
| CT500MX5            | 2        | 2      | 1.65%   |
| Unknown             | 1        | 1      | 0.83%   |
| Team                | 1        | 2      | 0.83%   |
| Smartbuy            | 1        | 1      | 0.83%   |
| SK hynix            | 1        | 1      | 0.83%   |
| Plextor             | 1        | 2      | 0.83%   |
| Patriot             | 1        | 1      | 0.83%   |
| OCZ-VERTEX          | 1        | 1      | 0.83%   |
| Netac               | 1        | 1      | 0.83%   |
| KingSpec            | 1        | 1      | 0.83%   |
| Kingmax             | 1        | 1      | 0.83%   |
| Hewlett-Packard     | 1        | 1      | 0.83%   |
| GOODRAM             | 1        | 1      | 0.83%   |
| Gigabyte Technology | 1        | 1      | 0.83%   |
| Dogfish             | 1        | 1      | 0.83%   |
| 2.5''               | 1        | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 155      | 299    | 54.96%  |
| SSD     | 101      | 148    | 35.82%  |
| NVMe    | 25       | 35     | 8.87%   |
| Unknown | 1        | 2      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 196      | 429    | 84.48%  |
| NVMe | 24       | 34     | 10.34%  |
| SAS  | 12       | 21     | 5.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 166      | 297    | 62.41%  |
| 0.51-1.0   | 62       | 91     | 23.31%  |
| 1.01-2.0   | 25       | 34     | 9.4%    |
| 3.01-4.0   | 5        | 9      | 1.88%   |
| 2.01-3.0   | 5        | 13     | 1.88%   |
| 4.01-10.0  | 3        | 3      | 1.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 61       | 28.91%  |
| 251-500        | 46       | 21.8%   |
| 1001-2000      | 31       | 14.69%  |
| More than 3000 | 18       | 8.53%   |
| 501-1000       | 17       | 8.06%   |
| 51-100         | 15       | 7.11%   |
| 2001-3000      | 11       | 5.21%   |
| 21-50          | 9        | 4.27%   |
| 1-20           | 3        | 1.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 73       | 33.18%  |
| 21-50          | 49       | 22.27%  |
| 51-100         | 24       | 10.91%  |
| 251-500        | 19       | 8.64%   |
| 101-250        | 16       | 7.27%   |
| 501-1000       | 15       | 6.82%   |
| 1001-2000      | 14       | 6.36%   |
| More than 3000 | 5        | 2.27%   |
| 2001-3000      | 5        | 2.27%   |

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
| Detected | 169      | 391    | 77.88%  |
| Works    | 41       | 86     | 18.89%  |
| Malfunc  | 7        | 7      | 3.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 144      | 53.73%  |
| AMD                              | 42       | 15.67%  |
| Nvidia                           | 13       | 4.85%   |
| Samsung Electronics              | 12       | 4.48%   |
| ASMedia Technology               | 12       | 4.48%   |
| JMicron Technology               | 11       | 4.1%    |
| VIA Technologies                 | 6        | 2.24%   |
| Phison Electronics               | 6        | 2.24%   |
| Marvell Technology Group         | 6        | 2.24%   |
| SanDisk                          | 3        | 1.12%   |
| Broadcom / LSI                   | 3        | 1.12%   |
| Silicon Motion                   | 2        | 0.75%   |
| Silicon Integrated Systems [SiS] | 2        | 0.75%   |
| Silicon Image                    | 2        | 0.75%   |
| Kingston Technology Company      | 2        | 0.75%   |
| LSI Logic / Symbios Logic        | 1        | 0.37%   |
| Integrated Technology Express    | 1        | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 23       | 6.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21       | 5.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 19       | 5.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17       | 4.64%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 12       | 3.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 3.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 2.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 2.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.46%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 2.19%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.19%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 2.19%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 1.91%   |
| Nvidia MCP61 IDE                                                                        | 6        | 1.64%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.64%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.64%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.64%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 5        | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.37%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.09%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.09%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 1.09%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.09%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 1.09%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 3        | 0.82%   |
| Phison E12 NVMe Controller                                                              | 3        | 0.82%   |
| JMicron JMB368 IDE controller                                                           | 3        | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3        | 0.82%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 0.82%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.82%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 0.82%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 0.82%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 0.82%   |
| Nvidia nForce2 IDE                                                                      | 2        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 141      | 52.03%  |
| IDE  | 87       | 32.1%   |
| NVMe | 24       | 8.86%   |
| RAID | 14       | 5.17%   |
| SAS  | 3        | 1.11%   |
| SCSI | 2        | 0.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 147      | 72.06%  |
| AMD    | 57       | 27.94%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 2.45%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 1.96%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 4        | 1.96%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.96%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 4        | 1.96%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 3        | 1.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.47%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.47%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 3        | 1.47%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 1.47%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.47%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2        | 0.98%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 0.98%   |
| Intel Pentium D CPU 3.00GHz                 | 2        | 0.98%   |
| Intel Pentium D CPU 2.80GHz                 | 2        | 0.98%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 0.98%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 0.98%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.98%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.98%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.98%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.98%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.98%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.98%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.98%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 0.98%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.98%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.98%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz       | 2        | 0.98%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 0.98%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.98%   |
| AMD Sempron Processor 3000+                 | 2        | 0.98%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 0.98%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 0.98%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 0.98%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 0.98%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 0.98%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 0.98%   |
| AMD FX-4300 Quad-Core Processor             | 2        | 0.98%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 26       | 12.75%  |
| Intel Core i7           | 23       | 11.27%  |
| Intel Core 2 Duo        | 19       | 9.31%   |
| Intel Xeon              | 14       | 6.86%   |
| Intel Core i3           | 14       | 6.86%   |
| Intel Core 2 Quad       | 10       | 4.9%    |
| AMD Ryzen 5             | 10       | 4.9%    |
| Intel Pentium           | 9        | 4.41%   |
| Intel Celeron           | 8        | 3.92%   |
| AMD Ryzen 7             | 7        | 3.43%   |
| Intel Pentium D         | 6        | 2.94%   |
| AMD FX                  | 6        | 2.94%   |
| Intel Pentium Dual-Core | 5        | 2.45%   |
| Intel Core 2            | 4        | 1.96%   |
| AMD Sempron             | 4        | 1.96%   |
| AMD Ryzen 3             | 4        | 1.96%   |
| AMD Athlon 64 X2        | 4        | 1.96%   |
| Intel Pentium 4         | 3        | 1.47%   |
| AMD Phenom II X4        | 3        | 1.47%   |
| AMD Athlon XP           | 3        | 1.47%   |
| AMD Athlon II X2        | 3        | 1.47%   |
| Other                   | 2        | 0.98%   |
| Intel Core i9           | 2        | 0.98%   |
| AMD Phenom II X6        | 2        | 0.98%   |
| AMD Athlon II X4        | 2        | 0.98%   |
| AMD Athlon              | 2        | 0.98%   |
| Intel Pentium Gold      | 1        | 0.49%   |
| Intel Pentium Dual      | 1        | 0.49%   |
| AMD Turion II Neo       | 1        | 0.49%   |
| AMD Ryzen 9             | 1        | 0.49%   |
| AMD Ryzen 5 PRO         | 1        | 0.49%   |
| AMD Phenom II X2        | 1        | 0.49%   |
| AMD E1                  | 1        | 0.49%   |
| AMD A4                  | 1        | 0.49%   |
| AMD A10                 | 1        | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 79       | 38.73%  |
| 4      | 76       | 37.25%  |
| 6      | 16       | 7.84%   |
| 8      | 14       | 6.86%   |
| 1      | 12       | 5.88%   |
| 16     | 3        | 1.47%   |
| 3      | 2        | 0.98%   |
| 12     | 1        | 0.49%   |
| 10     | 1        | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 198      | 97.06%  |
| 2      | 6        | 2.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 126      | 61.76%  |
| 2      | 78       | 38.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 198      | 97.06%  |
| 32-bit         | 6        | 2.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 20       | 9.76%   |
| Unknown    | 20       | 9.76%   |
| 0x306a9    | 18       | 8.78%   |
| 0x206a7    | 16       | 7.8%    |
| 0x306c3    | 14       | 6.83%   |
| 0x6fd      | 6        | 2.93%   |
| 0x08108109 | 6        | 2.93%   |
| 0x010000c8 | 6        | 2.93%   |
| 0x906ed    | 5        | 2.44%   |
| 0x6fb      | 5        | 2.44%   |
| 0x506e3    | 5        | 2.44%   |
| 0x10677    | 5        | 2.44%   |
| 0xf65      | 4        | 1.95%   |
| 0x906eb    | 4        | 1.95%   |
| 0xf64      | 3        | 1.46%   |
| 0x906ea    | 3        | 1.46%   |
| 0x6f2      | 3        | 1.46%   |
| 0x206d7    | 3        | 1.46%   |
| 0x106e5    | 3        | 1.46%   |
| 0x106a5    | 3        | 1.46%   |
| 0x08701021 | 3        | 1.46%   |
| 0x08101016 | 3        | 1.46%   |
| 0x06000852 | 3        | 1.46%   |
| 0xf29      | 2        | 0.98%   |
| 0x90675    | 2        | 0.98%   |
| 0x40651    | 2        | 0.98%   |
| 0x10676    | 2        | 0.98%   |
| 0x08701013 | 2        | 0.98%   |
| 0x0800820d | 2        | 0.98%   |
| 0x06001119 | 2        | 0.98%   |
| 0x0600063e | 2        | 0.98%   |
| 0x010000dc | 2        | 0.98%   |
| 0xf43      | 1        | 0.49%   |
| 0xa0671    | 1        | 0.49%   |
| 0xa0655    | 1        | 0.49%   |
| 0xa0653    | 1        | 0.49%   |
| 0x706a8    | 1        | 0.49%   |
| 0x6f6      | 1        | 0.49%   |
| 0x506c9    | 1        | 0.49%   |
| 0x406f1    | 1        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 27       | 13.24%  |
| SandyBridge   | 22       | 10.78%  |
| IvyBridge     | 19       | 9.31%   |
| Haswell       | 17       | 8.33%   |
| Core          | 17       | 8.33%   |
| KabyLake      | 13       | 6.37%   |
| K10           | 12       | 5.88%   |
| NetBurst      | 11       | 5.39%   |
| Zen+          | 9        | 4.41%   |
| Zen           | 8        | 3.92%   |
| K8 Hammer     | 7        | 3.43%   |
| Piledriver    | 6        | 2.94%   |
| Nehalem       | 6        | 2.94%   |
| Zen 2         | 5        | 2.45%   |
| Skylake       | 5        | 2.45%   |
| Zen 3         | 3        | 1.47%   |
| K6            | 3        | 1.47%   |
| Unknown       | 3        | 1.47%   |
| Westmere      | 2        | 0.98%   |
| CometLake     | 2        | 0.98%   |
| Bulldozer     | 2        | 0.98%   |
| Jaguar        | 1        | 0.49%   |
| Goldmont plus | 1        | 0.49%   |
| Goldmont      | 1        | 0.49%   |
| Broadwell     | 1        | 0.49%   |
| Bobcat        | 1        | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 98       | 44.55%  |
| Intel                      | 68       | 30.91%  |
| AMD                        | 47       | 21.36%  |
| VIA Technologies           | 4        | 1.82%   |
| S3 Graphics                | 1        | 0.45%   |
| Matrox Electronics Systems | 1        | 0.45%   |
| ASPEED Technology          | 1        | 0.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 16       | 7.05%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 9        | 3.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 9        | 3.96%   |
| Nvidia GT218 [GeForce 210]                                                    | 8        | 3.52%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 8        | 3.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 7        | 3.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 7        | 3.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 6        | 2.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 6        | 2.64%   |
| Nvidia GK208B [GeForce GT 730]                                                | 5        | 2.2%    |
| Nvidia GK208B [GeForce GT 710]                                                | 5        | 2.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 5        | 2.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4        | 1.76%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 3        | 1.32%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                             | 3        | 1.32%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 3        | 1.32%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 3        | 1.32%   |
| AMD RV710 [Radeon HD 4350/4550]                                               | 3        | 1.32%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 3        | 1.32%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 2        | 0.88%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                         | 2        | 0.88%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2        | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 2        | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 2        | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2        | 0.88%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 2        | 0.88%   |
| Nvidia GK104 [GeForce GTX 760]                                                | 2        | 0.88%   |
| Nvidia GF119 [NVS 310]                                                        | 2        | 0.88%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                             | 2        | 0.88%   |
| Nvidia GF104 [GeForce GTX 460]                                                | 2        | 0.88%   |
| Nvidia G86 [GeForce 8400 GS]                                                  | 2        | 0.88%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                       | 2        | 0.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2        | 0.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 2        | 0.88%   |
| Intel 82Q35 Express Integrated Graphics Controller                            | 2        | 0.88%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                    | 1        | 0.44%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                     | 1        | 0.44%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 1        | 0.44%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.44%   |
| S3 Graphics VT8375 [ProSavage8 KM266/KL266]                                   | 1        | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 91       | 44.17%  |
| 1 x Intel       | 56       | 27.18%  |
| 1 x AMD         | 40       | 19.42%  |
| 2 x AMD         | 4        | 1.94%   |
| 1 x VIA         | 4        | 1.94%   |
| Intel + Nvidia  | 4        | 1.94%   |
| AMD + Nvidia    | 3        | 1.46%   |
| 2 x Nvidia      | 1        | 0.49%   |
| 1 x S3 Graphics | 1        | 0.49%   |
| 1 x Matrox      | 1        | 0.49%   |
| 1 x ASPEED      | 1        | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 136      | 65.7%   |
| Proprietary | 42       | 20.29%  |
| Unknown     | 29       | 14.01%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 85       | 41.06%  |
| 0.01-0.5   | 30       | 14.49%  |
| 1.01-2.0   | 29       | 14.01%  |
| 0.51-1.0   | 29       | 14.01%  |
| 3.01-4.0   | 20       | 9.66%   |
| 7.01-8.0   | 10       | 4.83%   |
| 5.01-6.0   | 2        | 0.97%   |
| 2.01-3.0   | 2        | 0.97%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 38       | 17.84%  |
| Goldstar                | 21       | 9.86%   |
| Dell                    | 20       | 9.39%   |
| Acer                    | 20       | 9.39%   |
| BenQ                    | 13       | 6.1%    |
| Ancor Communications    | 12       | 5.63%   |
| AOC                     | 11       | 5.16%   |
| Philips                 | 9        | 4.23%   |
| Hewlett-Packard         | 9        | 4.23%   |
| Unknown                 | 8        | 3.76%   |
| Lenovo                  | 5        | 2.35%   |
| Sony                    | 4        | 1.88%   |
| Iiyama                  | 4        | 1.88%   |
| Fujitsu Siemens         | 4        | 1.88%   |
| ___                     | 2        | 0.94%   |
| Sceptre Tech            | 2        | 0.94%   |
| NEC Computers           | 2        | 0.94%   |
| Medion                  | 2        | 0.94%   |
| LG Electronics          | 2        | 0.94%   |
| eMachines               | 2        | 0.94%   |
| ASUSTek Computer        | 2        | 0.94%   |
| Vestel                  | 1        | 0.47%   |
| Toshiba                 | 1        | 0.47%   |
| Targa Visionary         | 1        | 0.47%   |
| PLN                     | 1        | 0.47%   |
| OEM                     | 1        | 0.47%   |
| NCS                     | 1        | 0.47%   |
| Mitsubishi              | 1        | 0.47%   |
| Microstep               | 1        | 0.47%   |
| IBM                     | 1        | 0.47%   |
| Hitachi                 | 1        | 0.47%   |
| ELSA International      | 1        | 0.47%   |
| Elo Touch               | 1        | 0.47%   |
| ELO                     | 1        | 0.47%   |
| Eizo                    | 1        | 0.47%   |
| DENON                   | 1        | 0.47%   |
| Compal                  | 1        | 0.47%   |
| Chi Mei Optoelectronics | 1        | 0.47%   |
| Belinea                 | 1        | 0.47%   |
| AUS                     | 1        | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch     | 2        | 0.9%    |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 2        | 0.9%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                     | 2        | 0.9%    |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                       | 2        | 0.9%    |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                           | 2        | 0.9%    |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch        | 2        | 0.9%    |
| ___ LCDTV16 ___0101 1920x1080                                           | 1        | 0.45%   |
| ___ LCD Monitor ___A995 1600x1200 360x270mm 17.7-inch                   | 1        | 0.45%   |
| Vestel LCD Monitor 58UHD_LCD_TV 3840x2160                               | 1        | 0.45%   |
| Unknown Monitor A995 1280x1024 360x270mm 17.7-inch                      | 1        | 0.45%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                      | 1        | 0.45%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.45%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                    | 1        | 0.45%   |
| Unknown LCD Monitor SAMSUNG                                             | 1        | 0.45%   |
| Unknown LCD Monitor Mitsubishi NXM76LCD 1280x1024                       | 1        | 0.45%   |
| Unknown LCD Monitor GBT G34WQC 3440x1440                                | 1        | 0.45%   |
| Unknown HV-734TB ___1770 1280x1024 338x270mm 17.0-inch                  | 1        | 0.45%   |
| Toshiba LCD Monitor TV 1920x1080                                        | 1        | 0.45%   |
| Targa Visionary LCD19-4 TARA194 1280x1024 376x301mm 19.0-inch           | 1        | 0.45%   |
| Sony TV SNY4C03 1920x1080 1063x598mm 48.0-inch                          | 1        | 0.45%   |
| Sony TV SNY1B02 1360x768 1600x900mm 72.3-inch                           | 1        | 0.45%   |
| Sony TV *00 SNYF503 1920x1080 1439x809mm 65.0-inch                      | 1        | 0.45%   |
| Sony LCD Monitor TV 3840x1080                                           | 1        | 0.45%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch          | 1        | 0.45%   |
| Sceptre Tech F24 SPT0961 1920x1080 480x260mm 21.5-inch                  | 1        | 0.45%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 600x340mm 27.2-inch       | 1        | 0.45%   |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch       | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch     | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 459x296mm 21.5-inch    | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch    | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM034F 1440x900 428x255mm 19.6-inch     | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0303 1680x1050 494x320mm 23.2-inch    | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch    | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch    | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 376x301mm 19.0-inch    | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM006E 1280x1024 338x270mm 17.0-inch    | 1        | 0.45%   |
| Samsung Electronics SMS22A200/460 SAM0831 1920x1080 477x268mm 21.5-inch | 1        | 0.45%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 376x301mm 19.0-inch     | 1        | 0.45%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch      | 1        | 0.45%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch      | 1        | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 93       | 46.04%  |
| 1280x1024 (SXGA)   | 34       | 16.83%  |
| 1680x1050 (WSXGA+) | 14       | 6.93%   |
| 1440x900 (WXGA+)   | 10       | 4.95%   |
| 1366x768 (WXGA)    | 9        | 4.46%   |
| 1600x900 (HD+)     | 7        | 3.47%   |
| 1920x1200 (WUXGA)  | 5        | 2.48%   |
| 1360x768           | 5        | 2.48%   |
| 3840x2160 (4K)     | 4        | 1.98%   |
| 2560x1440 (QHD)    | 4        | 1.98%   |
| 1024x768 (XGA)     | 4        | 1.98%   |
| Unknown            | 4        | 1.98%   |
| 3840x1080          | 2        | 0.99%   |
| 3440x1440          | 2        | 0.99%   |
| 2560x1080          | 2        | 0.99%   |
| 7680x2160          | 1        | 0.5%    |
| 4240x1440          | 1        | 0.5%    |
| 1600x1200          | 1        | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 33       | 15.87%  |
| 21      | 26       | 12.5%   |
| 24      | 21       | 10.1%   |
| 23      | 19       | 9.13%   |
| 19      | 19       | 9.13%   |
| 17      | 17       | 8.17%   |
| 27      | 15       | 7.21%   |
| 18      | 14       | 6.73%   |
| 22      | 8        | 3.85%   |
| 20      | 8        | 3.85%   |
| 15      | 8        | 3.85%   |
| 31      | 3        | 1.44%   |
| 72      | 2        | 0.96%   |
| 32      | 2        | 0.96%   |
| 65      | 1        | 0.48%   |
| 54      | 1        | 0.48%   |
| 52      | 1        | 0.48%   |
| 48      | 1        | 0.48%   |
| 34      | 1        | 0.48%   |
| 33      | 1        | 0.48%   |
| 28      | 1        | 0.48%   |
| 26      | 1        | 0.48%   |
| 25      | 1        | 0.48%   |
| 16      | 1        | 0.48%   |
| 14      | 1        | 0.48%   |
| 13      | 1        | 0.48%   |
| 12      | 1        | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 60       | 29.7%   |
| 501-600     | 50       | 24.75%  |
| Unknown     | 33       | 16.34%  |
| 301-350     | 24       | 11.88%  |
| 351-400     | 18       | 8.91%   |
| 601-700     | 5        | 2.48%   |
| 701-800     | 4        | 1.98%   |
| 1001-1500   | 4        | 1.98%   |
| 201-300     | 2        | 0.99%   |
| 1501-2000   | 2        | 0.99%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 97       | 48.99%  |
| Unknown | 32       | 16.16%  |
| 5/4     | 29       | 14.65%  |
| 16/10   | 26       | 13.13%  |
| 4/3     | 10       | 5.05%   |
| 21/9    | 3        | 1.52%   |
| 3/2     | 1        | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 60       | 29.13%  |
| 151-200        | 37       | 17.96%  |
| Unknown        | 33       | 16.02%  |
| 141-150        | 25       | 12.14%  |
| 301-350        | 16       | 7.77%   |
| 251-300        | 9        | 4.37%   |
| 351-500        | 7        | 3.4%    |
| 101-110        | 7        | 3.4%    |
| More than 1000 | 5        | 2.43%   |
| 111-120        | 3        | 1.46%   |
| 81-90          | 1        | 0.49%   |
| 71-80          | 1        | 0.49%   |
| 131-140        | 1        | 0.49%   |
| 501-1000       | 1        | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 123      | 62.76%  |
| Unknown | 33       | 16.84%  |
| 101-120 | 30       | 15.31%  |
| 1-50    | 6        | 3.06%   |
| 121-160 | 3        | 1.53%   |
| 161-240 | 1        | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 166      | 80.19%  |
| 2     | 27       | 13.04%  |
| 0     | 11       | 5.31%   |
| 3     | 3        | 1.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 120      | 41.52%  |
| Intel                            | 65       | 22.49%  |
| Qualcomm Atheros                 | 26       | 9%      |
| Ralink Technology                | 13       | 4.5%    |
| Nvidia                           | 11       | 3.81%   |
| Broadcom                         | 11       | 3.81%   |
| TP-Link                          | 5        | 1.73%   |
| VIA Technologies                 | 4        | 1.38%   |
| Marvell Technology Group         | 4        | 1.38%   |
| Samsung Electronics              | 3        | 1.04%   |
| Broadcom Limited                 | 3        | 1.04%   |
| Sitecom Europe                   | 2        | 0.69%   |
| Microsoft                        | 2        | 0.69%   |
| Huawei Technologies              | 2        | 0.69%   |
| AVM                              | 2        | 0.69%   |
| ZTE WCDMA Technologies MSM       | 1        | 0.35%   |
| Silicon Integrated Systems [SiS] | 1        | 0.35%   |
| Ralink                           | 1        | 0.35%   |
| NetGear                          | 1        | 0.35%   |
| Mercucys                         | 1        | 0.35%   |
| Mellanox Technologies            | 1        | 0.35%   |
| MediaTek                         | 1        | 0.35%   |
| LSI                              | 1        | 0.35%   |
| JMicron Technology               | 1        | 0.35%   |
| Edimax Technology                | 1        | 0.35%   |
| DisplayLink                      | 1        | 0.35%   |
| D-Link System                    | 1        | 0.35%   |
| Belkin Components                | 1        | 0.35%   |
| ASUSTek Computer                 | 1        | 0.35%   |
| ADMtek                           | 1        | 0.35%   |
| 3Com                             | 1        | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 87       | 26.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 10       | 3.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 8        | 2.48%   |
| Nvidia MCP61 Ethernet                                                                         | 8        | 2.48%   |
| Intel I211 Gigabit Network Connection                                                         | 8        | 2.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 6        | 1.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 5        | 1.55%   |
| Intel Wi-Fi 6 AX200                                                                           | 5        | 1.55%   |
| Intel Ethernet Connection (7) I219-V                                                          | 5        | 1.55%   |
| Intel 82579V Gigabit Network Connection                                                       | 5        | 1.55%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 4        | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 4        | 1.24%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 4        | 1.24%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 1.24%   |
| Intel 82574L Gigabit Network Connection                                                       | 4        | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 3        | 0.93%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 3        | 0.93%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                                    | 3        | 0.93%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                                 | 3        | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 3        | 0.93%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                | 3        | 0.93%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 3        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                                          | 3        | 0.93%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 3        | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 0.62%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 2        | 0.62%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 2        | 0.62%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 0.62%   |
| Realtek 802.11ac NIC                                                                          | 2        | 0.62%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 0.62%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2        | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2        | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 0.62%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2        | 0.62%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 2        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 2        | 0.62%   |
| Nvidia nForce2 Ethernet Controller                                                            | 2        | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 28       | 31.11%  |
| Intel                 | 15       | 16.67%  |
| Ralink Technology     | 13       | 14.44%  |
| Qualcomm Atheros      | 10       | 11.11%  |
| TP-Link               | 5        | 5.56%   |
| Broadcom              | 4        | 4.44%   |
| Sitecom Europe        | 2        | 2.22%   |
| Microsoft             | 2        | 2.22%   |
| AVM                   | 2        | 2.22%   |
| Ralink                | 1        | 1.11%   |
| NetGear               | 1        | 1.11%   |
| Mercucys              | 1        | 1.11%   |
| MediaTek              | 1        | 1.11%   |
| Edimax Technology     | 1        | 1.11%   |
| D-Link System         | 1        | 1.11%   |
| Broadcom Limited      | 1        | 1.11%   |
| Belkin Components     | 1        | 1.11%   |
| ASUSTek Computer      | 1        | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 6        | 6.59%   |
| Intel Wi-Fi 6 AX200                                                                           | 5        | 5.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 4.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 4        | 4.4%    |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 4.4%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 3        | 3.3%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 2.2%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 2        | 2.2%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 2.2%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 2.2%    |
| Realtek 802.11ac NIC                                                                          | 2        | 2.2%    |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 2.2%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2        | 2.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 2.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 2.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2        | 2.2%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 2        | 2.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 2.2%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.1%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1        | 1.1%    |
| TP-Link 802.11n NIC                                                                           | 1        | 1.1%    |
| Sitecom Europe WLA-2000 v1.001 WLAN [RTL8191SU]                                               | 1        | 1.1%    |
| Sitecom Europe RTL8188S WLAN Adapter                                                          | 1        | 1.1%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.1%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.1%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 1.1%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 1        | 1.1%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 1.1%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 1.1%    |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 1.1%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 1.1%    |
| Ralink RT2501/RT2573 Wireless Adapter                                                         | 1        | 1.1%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 1.1%    |
| NetGear A6150                                                                                 | 1        | 1.1%    |
| Microsoft XBOX ACC                                                                            | 1        | 1.1%    |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1        | 1.1%    |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 1.1%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 108      | 48.65%  |
| Intel                            | 59       | 26.58%  |
| Qualcomm Atheros                 | 16       | 7.21%   |
| Nvidia                           | 11       | 4.95%   |
| Broadcom                         | 7        | 3.15%   |
| VIA Technologies                 | 4        | 1.8%    |
| Marvell Technology Group         | 4        | 1.8%    |
| Samsung Electronics              | 3        | 1.35%   |
| Huawei Technologies              | 2        | 0.9%    |
| Broadcom Limited                 | 2        | 0.9%    |
| ZTE WCDMA Technologies MSM       | 1        | 0.45%   |
| Silicon Integrated Systems [SiS] | 1        | 0.45%   |
| JMicron Technology               | 1        | 0.45%   |
| DisplayLink                      | 1        | 0.45%   |
| ADMtek                           | 1        | 0.45%   |
| 3Com                             | 1        | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 87       | 37.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8        | 3.48%   |
| Nvidia MCP61 Ethernet                                             | 8        | 3.48%   |
| Intel I211 Gigabit Network Connection                             | 8        | 3.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 2.17%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 2.17%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 2.17%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 1.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 1.74%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 1.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 1.3%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 1.3%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 1.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 1.3%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 1.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 1.3%    |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.3%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 1.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.87%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.87%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.87%   |
| Nvidia nForce2 Ethernet Controller                                | 2        | 0.87%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.87%   |
| Intel 82567V-2 Gigabit Network Connection                         | 2        | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.87%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 2        | 0.87%   |
| Huawei YAL-L21                                                    | 2        | 0.87%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.87%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1        | 0.43%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 0.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.43%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.43%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1        | 0.43%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.43%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 204      | 71.33%  |
| WiFi     | 80       | 27.97%  |
| Modem    | 1        | 0.35%   |
| Unknown  | 1        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 169      | 80.09%  |
| WiFi     | 42       | 19.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 145      | 71.08%  |
| 2     | 54       | 26.47%  |
| 3     | 4        | 1.96%   |
| 4     | 1        | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 175      | 82.55%  |
| Yes  | 37       | 17.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 33.33%  |
| Cambridge Silicon Radio         | 12       | 28.57%  |
| Realtek Semiconductor           | 5        | 11.9%   |
| Broadcom                        | 3        | 7.14%   |
| Qualcomm Atheros Communications | 2        | 4.76%   |
| ASUSTek Computer                | 2        | 4.76%   |
| MediaTek                        | 1        | 2.38%   |
| Lite-On Technology              | 1        | 2.38%   |
| Dell                            | 1        | 2.38%   |
| Apple                           | 1        | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12       | 28.57%  |
| Intel AX200 Bluetooth                               | 5        | 11.9%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3        | 7.14%   |
| Realtek Bluetooth Radio                             | 2        | 4.76%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 4.76%   |
| Intel Bluetooth wireless interface                  | 2        | 4.76%   |
| Intel AX201 Bluetooth                               | 2        | 4.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 2.38%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 2.38%   |
| MediaTek Wireless_Device                            | 1        | 2.38%   |
| Lite-On Bluetooth Device                            | 1        | 2.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.38%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 2.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2.38%   |
| Dell BT Mini-Receiver                               | 1        | 2.38%   |
| Broadcom HP Bluethunder                             | 1        | 2.38%   |
| Broadcom BCM92045B3 ROM                             | 1        | 2.38%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 2.38%   |
| Apple Bluetooth USB Host Controller                 | 1        | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 131      | 40.81%  |
| Nvidia                           | 87       | 27.1%   |
| AMD                              | 57       | 17.76%  |
| C-Media Electronics              | 12       | 3.74%   |
| VIA Technologies                 | 8        | 2.49%   |
| Generalplus Technology           | 4        | 1.25%   |
| Creative Labs                    | 4        | 1.25%   |
| GN Netcom                        | 3        | 0.93%   |
| Silicon Integrated Systems [SiS] | 2        | 0.62%   |
| Logitech                         | 2        | 0.62%   |
| JMTek                            | 2        | 0.62%   |
| Yamaha                           | 1        | 0.31%   |
| Xilinx                           | 1        | 0.31%   |
| Tenx Technology                  | 1        | 0.31%   |
| Plantronics                      | 1        | 0.31%   |
| M-Audio                          | 1        | 0.31%   |
| GYROCOM C&C                      | 1        | 0.31%   |
| Focusrite-Novation               | 1        | 0.31%   |
| Evolution Electronics            | 1        | 0.31%   |
| Creative Technology              | 1        | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 22       | 6.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 20       | 5.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 14       | 3.91%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 13       | 3.63%   |
| AMD Family 17h/19h HD Audio Controller                                      | 12       | 3.35%   |
| Nvidia High Definition Audio Controller                                     | 11       | 3.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 11       | 3.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 11       | 3.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 11       | 3.07%   |
| Intel Cannon Lake PCH cAVS                                                  | 10       | 2.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 10       | 2.79%   |
| Nvidia GM206 High Definition Audio Controller                               | 9        | 2.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 9        | 2.51%   |
| Nvidia MCP61 High Definition Audio                                          | 8        | 2.23%   |
| Nvidia GP107GL High Definition Audio Controller                             | 7        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 7        | 1.96%   |
| AMD Starship/Matisse HD Audio Controller                                    | 6        | 1.68%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 6        | 1.68%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                               | 5        | 1.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 5        | 1.4%    |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                   | 4        | 1.12%   |
| Nvidia GM204 High Definition Audio Controller                               | 4        | 1.12%   |
| Nvidia GF116 High Definition Audio Controller                               | 4        | 1.12%   |
| Intel 9 Series Chipset Family HD Audio Controller                           | 4        | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 4        | 1.12%   |
| Generalplus Technology Usb Audio Device                                     | 4        | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]     | 4        | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                               | 3        | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                               | 3        | 0.84%   |
| Nvidia GP106 High Definition Audio Controller                               | 3        | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 3        | 0.84%   |
| Nvidia GK104 HDMI Audio Controller                                          | 3        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                               | 3        | 0.84%   |
| Intel C600/X79 series chipset High Definition Audio Controller              | 3        | 0.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 3        | 0.84%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                            | 3        | 0.84%   |
| AMD FCH Azalia Controller                                                   | 3        | 0.84%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 3        | 0.84%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 2        | 0.56%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller             | 2        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 16       | 32%     |
| Kingston            | 7        | 14%     |
| Samsung Electronics | 6        | 12%     |
| Crucial             | 6        | 12%     |
| SK hynix            | 3        | 6%      |
| Micron Technology   | 3        | 6%      |
| G.Skill             | 2        | 4%      |
| Smart               | 1        | 2%      |
| PLEXHD              | 1        | 2%      |
| Nanya Technology    | 1        | 2%      |
| Kingmax             | 1        | 2%      |
| Exceleram           | 1        | 2%      |
| Corsair             | 1        | 2%      |
| A-DATA Technology   | 1        | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2        | 3.77%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                   | 1        | 1.89%   |
| Unknown RAM Module 512MB DIMM 667MT/s                     | 1        | 1.89%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1        | 1.89%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 1.89%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 1        | 1.89%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 1.89%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 1.89%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 1.89%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 1        | 1.89%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s               | 1        | 1.89%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                | 1        | 1.89%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                | 1        | 1.89%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                    | 1        | 1.89%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 1        | 1.89%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                    | 1        | 1.89%   |
| Unknown RAM Module 1024MB DIMM                            | 1        | 1.89%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s        | 1        | 1.89%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s     | 1        | 1.89%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s             | 1        | 1.89%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s     | 1        | 1.89%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s      | 1        | 1.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 1.89%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s     | 1        | 1.89%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1600MT/s       | 1        | 1.89%   |
| Samsung RAM M393B1G70BH0-YK0 8GB DIMM DDR3 1600MT/s       | 1        | 1.89%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s      | 1        | 1.89%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s       | 1        | 1.89%   |
| PLEXHD RAM Module 8192MB DIMM DDR3 1333MT/s               | 1        | 1.89%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s         | 1        | 1.89%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 1.89%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s       | 1        | 1.89%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s      | 1        | 1.89%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s            | 1        | 1.89%   |
| Kingston RAM KHX3600C17D4/16GX 16GB DIMM DDR4 3800MT/s    | 1        | 1.89%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s       | 1        | 1.89%   |
| Kingston RAM 99U4342-016.A00G 4096MB SODIMM DDR3 1600MT/s | 1        | 1.89%   |
| Kingston RAM 9965589-033.D00G 8192MB DIMM DDR4 2400MT/s   | 1        | 1.89%   |
| Kingston RAM 9905403-420.A00LF 4GB DIMM DDR3 2133MT/s     | 1        | 1.89%   |
| Kingston RAM 2G-UDIMM 2GB DIMM DDR2 800MT/s               | 1        | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 18       | 38.3%   |
| DDR4    | 13       | 27.66%  |
| DDR2    | 5        | 10.64%  |
| Unknown | 5        | 10.64%  |
| SDRAM   | 3        | 6.38%   |
| DDR     | 3        | 6.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 41       | 89.13%  |
| SODIMM | 5        | 10.87%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 14       | 29.79%  |
| 4096  | 11       | 23.4%   |
| 2048  | 11       | 23.4%   |
| 16384 | 5        | 10.64%  |
| 1024  | 4        | 8.51%   |
| 32768 | 1        | 2.13%   |
| 512   | 1        | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 14       | 28.57%  |
| 800     | 5        | 10.2%   |
| 667     | 5        | 10.2%   |
| 1333    | 4        | 8.16%   |
| 3200    | 2        | 4.08%   |
| 2667    | 2        | 4.08%   |
| 2666    | 2        | 4.08%   |
| 2400    | 2        | 4.08%   |
| Unknown | 2        | 4.08%   |
| 4133    | 1        | 2.04%   |
| 3800    | 1        | 2.04%   |
| 3600    | 1        | 2.04%   |
| 3500    | 1        | 2.04%   |
| 3400    | 1        | 2.04%   |
| 2133    | 1        | 2.04%   |
| 1866    | 1        | 2.04%   |
| 1334    | 1        | 2.04%   |
| 1067    | 1        | 2.04%   |
| 533     | 1        | 2.04%   |
| 400     | 1        | 2.04%   |

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
| Logitech                      | 13       | 39.39%  |
| Microsoft                     | 3        | 9.09%   |
| Z-Star Microelectronics       | 2        | 6.06%   |
| Xiongmai                      | 1        | 3.03%   |
| WCM_USB                       | 1        | 3.03%   |
| Sunplus Innovation Technology | 1        | 3.03%   |
| Service & Quality Technology  | 1        | 3.03%   |
| Pixart Imaging                | 1        | 3.03%   |
| OmniVision Technologies       | 1        | 3.03%   |
| Nintendo                      | 1        | 3.03%   |
| Microdia                      | 1        | 3.03%   |
| MacroSilicon                  | 1        | 3.03%   |
| KYE Systems (Mouse Systems)   | 1        | 3.03%   |
| Generalplus Technology        | 1        | 3.03%   |
| Creative Technology           | 1        | 3.03%   |
| Chicony Electronics           | 1        | 3.03%   |
| ARC International             | 1        | 3.03%   |
| Alcor Micro                   | 1        | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Logitech Webcam C270                               | 5        | 15.15%  |
| Z-Star Venus USB2.0 Camera                         | 2        | 6.06%   |
| Microsoft LifeCam HD-3000                          | 2        | 6.06%   |
| Logitech Webcam C310                               | 2        | 6.06%   |
| Xiongmai web camera                                | 1        | 3.03%   |
| WCM_USB WEB CAM                                    | 1        | 3.03%   |
| Sunplus PAPALOOK_229AF                             | 1        | 3.03%   |
| Service & Quality USB PC Camera                    | 1        | 3.03%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro               | 1        | 3.03%   |
| OmniVision Integrated Webcam for Dell XPS 2010     | 1        | 3.03%   |
| Nintendo USB Camera                                | 1        | 3.03%   |
| Microsoft MicrosoftÂ LifeCam VX-5500              | 1        | 3.03%   |
| Microdia Webcam Vitade AF                          | 1        | 3.03%   |
| MacroSilicon USB Video                             | 1        | 3.03%   |
| Logitech Webcam Pro 9000                           | 1        | 3.03%   |
| Logitech Webcam C930e                              | 1        | 3.03%   |
| Logitech Webcam C925e                              | 1        | 3.03%   |
| Logitech Webcam C210                               | 1        | 3.03%   |
| Logitech Logi Webcam C920e                         | 1        | 3.03%   |
| Logitech HD Pro Webcam C920                        | 1        | 3.03%   |
| KYE Systems (Mouse Systems) Genius iSlim 2000AF V2 | 1        | 3.03%   |
| Generalplus 808 Camera #9 (web-cam mode)           | 1        | 3.03%   |
| Creative Live! Cam Sync HD [VF0770]                | 1        | 3.03%   |
| Chicony HP High Definition 1MP Webcam              | 1        | 3.03%   |
| ARC International Camera                           | 1        | 3.03%   |
| Alcor Micro USB 2.0 PC Camera                      | 1        | 3.03%   |

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
| 0     | 145      | 69.38%  |
| 1     | 56       | 26.79%  |
| 2     | 4        | 1.91%   |
| 4     | 2        | 0.96%   |
| 3     | 2        | 0.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 35       | 47.95%  |
| Net/wireless             | 20       | 27.4%   |
| Communication controller | 5        | 6.85%   |
| Unassigned class         | 3        | 4.11%   |
| Network                  | 2        | 2.74%   |
| Net/ethernet             | 2        | 2.74%   |
| Storage/ide              | 1        | 1.37%   |
| Multimedia controller    | 1        | 1.37%   |
| Modem                    | 1        | 1.37%   |
| Fingerprint reader       | 1        | 1.37%   |
| Chipcard                 | 1        | 1.37%   |
| Camera                   | 1        | 1.37%   |

