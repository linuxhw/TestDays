ALT Linux - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for ALT Linux.

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

Total: 690

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| RDW Comput... | B760 D5                     | [3a8ed47b61](https://linux-hardware.org/?probe=3a8ed47b61) | Dec 30, 2025 |
| MSI           | B450M MORTAR MAX            | [5b65e114e2](https://linux-hardware.org/?probe=5b65e114e2) | Dec 28, 2025 |
| MSI           | MPG B550I GAMING EDGE MA... | [1ebd54399c](https://linux-hardware.org/?probe=1ebd54399c) | Dec 27, 2025 |
| MSI           | MPG B550I GAMING EDGE MA... | [d7316cf01d](https://linux-hardware.org/?probe=d7316cf01d) | Dec 25, 2025 |
| Gigabyte      | H410M H V2                  | [289c28f1c0](https://linux-hardware.org/?probe=289c28f1c0) | Dec 24, 2025 |
| Gigabyte      | H410M H V2                  | [be24292e6b](https://linux-hardware.org/?probe=be24292e6b) | Dec 22, 2025 |
| ASUSTek       | PRIME B450M-K               | [9fa9278318](https://linux-hardware.org/?probe=9fa9278318) | Dec 22, 2025 |
| Gigabyte      | MZAPLCP-00                  | [08655dc25a](https://linux-hardware.org/?probe=08655dc25a) | Dec 21, 2025 |
| Biostar       | H110MGC                     | [e8c0a49d16](https://linux-hardware.org/?probe=e8c0a49d16) | Dec 20, 2025 |
| Gigabyte      | F2A68HM-S1                  | [c467bbebde](https://linux-hardware.org/?probe=c467bbebde) | Dec 19, 2025 |
| Gigabyte      | H410M H V3                  | [f6643ae299](https://linux-hardware.org/?probe=f6643ae299) | Dec 19, 2025 |
| Intel         | X99                         | [caaa2bef16](https://linux-hardware.org/?probe=caaa2bef16) | Dec 18, 2025 |
| ASUSTek       | PRIME H510M-R               | [f01f9e46e7](https://linux-hardware.org/?probe=f01f9e46e7) | Dec 18, 2025 |
| ASUSTek       | PRIME H310M-R R2.0          | [4531165482](https://linux-hardware.org/?probe=4531165482) | Dec 16, 2025 |
| ASUSTek       | P8H61-MX                    | [a640d9c8aa](https://linux-hardware.org/?probe=a640d9c8aa) | Dec 11, 2025 |
| BESHTAU       | Q670D5RU002                 | [6e3268d82b](https://linux-hardware.org/?probe=6e3268d82b) | Dec 11, 2025 |
| ASUSTek       | PRIME B850M-K               | [727c1168c2](https://linux-hardware.org/?probe=727c1168c2) | Dec 10, 2025 |
| Unknown       | Intel X79                   | [c21eb1bfec](https://linux-hardware.org/?probe=c21eb1bfec) | Dec 09, 2025 |
| Biostar       | H110MGC                     | [c085c63989](https://linux-hardware.org/?probe=c085c63989) | Dec 09, 2025 |
| Gigabyte      | F2A68HM-DS2                 | [d4eb91338c](https://linux-hardware.org/?probe=d4eb91338c) | Dec 09, 2025 |
| Unknown       | Unknown                     | [a74e5fe873](https://linux-hardware.org/?probe=a74e5fe873) | Dec 04, 2025 |
| ASUSTek       | PRIME H510M-K               | [c026dc8735](https://linux-hardware.org/?probe=c026dc8735) | Nov 30, 2025 |
| Gigabyte      | P85-D3                      | [61d368426e](https://linux-hardware.org/?probe=61d368426e) | Nov 29, 2025 |
| Biostar       | B450NH                      | [0afa4a2a14](https://linux-hardware.org/?probe=0afa4a2a14) | Nov 25, 2025 |
| ASUSTek       | PRIME H310M-R R2.0          | [e4b0c85962](https://linux-hardware.org/?probe=e4b0c85962) | Nov 20, 2025 |
| Gigabyte      | H410M S2H V3                | [d6403a1ef2](https://linux-hardware.org/?probe=d6403a1ef2) | Nov 17, 2025 |
| Huanan        | X99-QD4 V1.0                | [f070f26e5b](https://linux-hardware.org/?probe=f070f26e5b) | Nov 15, 2025 |
| Gigabyte      | B550M DS3H AC               | [edd076134b](https://linux-hardware.org/?probe=edd076134b) | Nov 13, 2025 |
| GEEKOM        | Mini IT 8                   | [bb7720c0a8](https://linux-hardware.org/?probe=bb7720c0a8) | Nov 11, 2025 |
| GEEKOM        | Mini IT 8                   | [441bbf1dc0](https://linux-hardware.org/?probe=441bbf1dc0) | Nov 11, 2025 |
| Gigabyte      | Z87-D3HP-CF                 | [efac60d9cf](https://linux-hardware.org/?probe=efac60d9cf) | Nov 08, 2025 |
| Intel         | X99-H9S V1.1                | [ad4083dc77](https://linux-hardware.org/?probe=ad4083dc77) | Nov 08, 2025 |
| Gigabyte      | E2500N                      | [87d9b594f0](https://linux-hardware.org/?probe=87d9b594f0) | Nov 08, 2025 |
| ASUSTek       | TUF B450-PRO GAMING         | [c247788e95](https://linux-hardware.org/?probe=c247788e95) | Nov 08, 2025 |
| MSI           | PRO H610M-G WIFI DDR4       | [688a752ce9](https://linux-hardware.org/?probe=688a752ce9) | Nov 06, 2025 |
| RAMEC         | RAMG.467145.009 V1.0        | [be3f6cc422](https://linux-hardware.org/?probe=be3f6cc422) | Nov 05, 2025 |
| Gigabyte      | B760M DS3H                  | [f482907595](https://linux-hardware.org/?probe=f482907595) | Nov 03, 2025 |
| BESHTAU       | H610RU001 V1.0              | [12fd7fc8a0](https://linux-hardware.org/?probe=12fd7fc8a0) | Nov 01, 2025 |
| MSI           | H81M-P33                    | [0779b0d3c1](https://linux-hardware.org/?probe=0779b0d3c1) | Oct 29, 2025 |
| Arsenal+      | B760ARS                     | [fda89abd8c](https://linux-hardware.org/?probe=fda89abd8c) | Oct 24, 2025 |
| BESSTAR Te... | Cherry Trail CR             | [5276603cfa](https://linux-hardware.org/?probe=5276603cfa) | Oct 23, 2025 |
| Gigabyte      | AB350M-DS3H V2-CF           | [2346b11567](https://linux-hardware.org/?probe=2346b11567) | Oct 19, 2025 |
| ASRock        | B450 Pro4                   | [5d880da3c9](https://linux-hardware.org/?probe=5d880da3c9) | Oct 13, 2025 |
| Unknown       | GB01                        | [cc281352cd](https://linux-hardware.org/?probe=cc281352cd) | Oct 12, 2025 |
| ASRock        | H610M-HDV/M.2+ D5           | [8050996885](https://linux-hardware.org/?probe=8050996885) | Oct 10, 2025 |
| Gigabyte      | E2500N                      | [56e5db4f90](https://linux-hardware.org/?probe=56e5db4f90) | Oct 08, 2025 |
| ASRock        | H110M-DVS R2.0              | [50d401f8bb](https://linux-hardware.org/?probe=50d401f8bb) | Oct 07, 2025 |
| Gigabyte      | B450 AORUS M                | [46ee4764bf](https://linux-hardware.org/?probe=46ee4764bf) | Oct 06, 2025 |
| Gigabyte      | B450 AORUS M                | [5d157389ce](https://linux-hardware.org/?probe=5d157389ce) | Oct 06, 2025 |
| Gigabyte      | B550M K                     | [9e22a0c37e](https://linux-hardware.org/?probe=9e22a0c37e) | Oct 04, 2025 |
| ASUSTek       | ProArt B650-CREATOR         | [3e125225ee](https://linux-hardware.org/?probe=3e125225ee) | Oct 02, 2025 |
| ASRock        | H610M-HDV/M.2+ D5           | [7a5c82cf20](https://linux-hardware.org/?probe=7a5c82cf20) | Oct 01, 2025 |
| Gigabyte      | GA-78LMT-S2 sex             | [2910994ab4](https://linux-hardware.org/?probe=2910994ab4) | Sep 29, 2025 |
| Gigabyte      | GA-78LMT-S2 sex             | [ce9b33db50](https://linux-hardware.org/?probe=ce9b33db50) | Sep 29, 2025 |
| ASRock        | H97 Pro4                    | [9f16d4e516](https://linux-hardware.org/?probe=9f16d4e516) | Sep 28, 2025 |
| Gigabyte      | B75M-HD3                    | [e3675b3cf6](https://linux-hardware.org/?probe=e3675b3cf6) | Sep 24, 2025 |
| ASUSTek       | H110M-R                     | [a2aa5a7def](https://linux-hardware.org/?probe=a2aa5a7def) | Sep 23, 2025 |
| ASUSTek       | H110M-R                     | [c8522d2b76](https://linux-hardware.org/?probe=c8522d2b76) | Sep 23, 2025 |
| WeiBu         | WNFP7R110 V1.0              | [4c6a6d0892](https://linux-hardware.org/?probe=4c6a6d0892) | Sep 13, 2025 |
| Biostar       | H510MHP                     | [902223928b](https://linux-hardware.org/?probe=902223928b) | Sep 12, 2025 |
| Gigabyte      | H110M-S2H-CF                | [092fd3f15a](https://linux-hardware.org/?probe=092fd3f15a) | Sep 09, 2025 |
| Gigabyte      | H110M-S2H-CF                | [e5a8b0cccf](https://linux-hardware.org/?probe=e5a8b0cccf) | Sep 09, 2025 |
| Loongson      | 3A6000-7A2000-NUC QA612N... | [6e8c1d5a4b](https://linux-hardware.org/?probe=6e8c1d5a4b) | Sep 07, 2025 |
| ASUSTek       | PRIME B760M-K D4            | [3fa3e3ba4a](https://linux-hardware.org/?probe=3fa3e3ba4a) | Sep 06, 2025 |
| ASUSTek       | PRIME H610M-K D4 ARGB       | [c40d0caf0b](https://linux-hardware.org/?probe=c40d0caf0b) | Sep 03, 2025 |
| ASRock        | B550M Pro4                  | [4e7d35aeda](https://linux-hardware.org/?probe=4e7d35aeda) | Sep 01, 2025 |
| Gigabyte      | A320M-H-CF                  | [59ec6c996b](https://linux-hardware.org/?probe=59ec6c996b) | Aug 29, 2025 |
| ASUSTek       | P8H61-M LX3                 | [dcbfeb1d06](https://linux-hardware.org/?probe=dcbfeb1d06) | Aug 25, 2025 |
| Gigabyte      | A320M-H-CF                  | [2face34b92](https://linux-hardware.org/?probe=2face34b92) | Aug 25, 2025 |
| Gigabyte      | A320M-H-CF                  | [3ed3e8b8c8](https://linux-hardware.org/?probe=3ed3e8b8c8) | Aug 23, 2025 |
| ASUSTek       | H110M-R                     | [52767b2382](https://linux-hardware.org/?probe=52767b2382) | Aug 18, 2025 |
| ASRock        | B460 Pro4                   | [ff06fd9aa3](https://linux-hardware.org/?probe=ff06fd9aa3) | Aug 14, 2025 |
| Lenovo        | 3140 NOK                    | [a83169bb48](https://linux-hardware.org/?probe=a83169bb48) | Aug 14, 2025 |
| ASRock        | A620M Pro RS                | [dc128468e5](https://linux-hardware.org/?probe=dc128468e5) | Aug 09, 2025 |
| Lenovo        | 3140 NOK                    | [9d8e08ed7b](https://linux-hardware.org/?probe=9d8e08ed7b) | Aug 08, 2025 |
| ASUSTek       | PRIME B365M-C               | [ddb58c7ef2](https://linux-hardware.org/?probe=ddb58c7ef2) | Aug 08, 2025 |
| ASUSTek       | PRIME B365M-C               | [bdb7482df0](https://linux-hardware.org/?probe=bdb7482df0) | Aug 08, 2025 |
| Dell          | 0U649C                      | [28dd7c57e2](https://linux-hardware.org/?probe=28dd7c57e2) | Jul 20, 2025 |
| MSI           | B550M PRO-VDH               | [3059e9a348](https://linux-hardware.org/?probe=3059e9a348) | Jul 20, 2025 |
| Gigabyte      | B650M S2H                   | [097532534d](https://linux-hardware.org/?probe=097532534d) | Jul 20, 2025 |
| Gigabyte      | B850M D3HP                  | [efcd755494](https://linux-hardware.org/?probe=efcd755494) | Jul 18, 2025 |
| Gigabyte      | AB350M-DS3H V2-CF           | [63b9f39f52](https://linux-hardware.org/?probe=63b9f39f52) | Jul 17, 2025 |
| Gigabyte      | H55M-S2                     | [79894b60d3](https://linux-hardware.org/?probe=79894b60d3) | Jul 04, 2025 |
| Biostar       | B75MU3B                     | [c6b4f7e726](https://linux-hardware.org/?probe=c6b4f7e726) | Jul 03, 2025 |
| Biostar       | B75MU3B                     | [896105a4ae](https://linux-hardware.org/?probe=896105a4ae) | Jul 03, 2025 |
| Intel         | X79M-S                      | [0e44829273](https://linux-hardware.org/?probe=0e44829273) | Jun 15, 2025 |
| ASRock        | A520M Pro4                  | [d6e132e2b5](https://linux-hardware.org/?probe=d6e132e2b5) | Jun 11, 2025 |
| ASUSTek       | PRIME H510M-K               | [0fb1a1da8b](https://linux-hardware.org/?probe=0fb1a1da8b) | Jun 08, 2025 |
| MSI           | MAG B760M MORTAR WIFI II    | [3a26d0ea1e](https://linux-hardware.org/?probe=3a26d0ea1e) | Jun 08, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7      | [1fd3c6e0cf](https://linux-hardware.org/?probe=1fd3c6e0cf) | May 29, 2025 |
| ASRock        | H610M-HDV/M.2+ D5           | [58219f0ead](https://linux-hardware.org/?probe=58219f0ead) | May 28, 2025 |
| ASUSTek       | A68HM-K                     | [717d955cf7](https://linux-hardware.org/?probe=717d955cf7) | May 27, 2025 |
| ASUSTek       | A68HM-K                     | [0f15fe0244](https://linux-hardware.org/?probe=0f15fe0244) | May 20, 2025 |
| Gigabyte      | B450 AORUS ELITE            | [b4aed87628](https://linux-hardware.org/?probe=b4aed87628) | May 16, 2025 |
| HP            | 8917                        | [118d54a235](https://linux-hardware.org/?probe=118d54a235) | May 12, 2025 |
| Gigabyte      | H97-D3H-CF                  | [35089402b7](https://linux-hardware.org/?probe=35089402b7) | May 06, 2025 |
| ASUSTek       | B150M-K                     | [358617370d](https://linux-hardware.org/?probe=358617370d) | May 05, 2025 |
| ASRock        | A520M Pro4                  | [cdfd518526](https://linux-hardware.org/?probe=cdfd518526) | Apr 30, 2025 |
| ASRock        | B550M Pro4                  | [35011b6599](https://linux-hardware.org/?probe=35011b6599) | Apr 25, 2025 |
| ASUSTek       | P5B-Deluxe                  | [117c95b263](https://linux-hardware.org/?probe=117c95b263) | Apr 22, 2025 |
| ASRock        | B450M Pro4                  | [f24f404ff7](https://linux-hardware.org/?probe=f24f404ff7) | Apr 19, 2025 |
| ASUSTek       | P5B-Deluxe                  | [be9d55ac8c](https://linux-hardware.org/?probe=be9d55ac8c) | Apr 16, 2025 |
| INFERIT       | IFMBH610IP                  | [3db2c86380](https://linux-hardware.org/?probe=3db2c86380) | Apr 15, 2025 |
| Gigabyte      | H55M-S2                     | [5509bcb0d9](https://linux-hardware.org/?probe=5509bcb0d9) | Apr 13, 2025 |
| ASRock        | B550M Pro4                  | [c042768fb4](https://linux-hardware.org/?probe=c042768fb4) | Apr 09, 2025 |
| Unknown       | Unknown                     | [43de099aa7](https://linux-hardware.org/?probe=43de099aa7) | Apr 08, 2025 |
| ASUSTek       | P5B-Deluxe                  | [bce2b2ae12](https://linux-hardware.org/?probe=bce2b2ae12) | Apr 03, 2025 |
| Gigabyte      | B560M DS3H V2               | [227af87cc0](https://linux-hardware.org/?probe=227af87cc0) | Apr 03, 2025 |
| Gigabyte      | B550 AORUS ELITE V2         | [e1b3c2009e](https://linux-hardware.org/?probe=e1b3c2009e) | Mar 30, 2025 |
| ASUSTek       | PRIME B250M-C               | [032fdc8bde](https://linux-hardware.org/?probe=032fdc8bde) | Mar 28, 2025 |
| ASUSTek       | PRIME B250M-C               | [f5a5b74b01](https://linux-hardware.org/?probe=f5a5b74b01) | Mar 28, 2025 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [bc98c2c7b6](https://linux-hardware.org/?probe=bc98c2c7b6) | Mar 23, 2025 |
| ASUSTek       | PRIME B365M-C               | [97ecd71f86](https://linux-hardware.org/?probe=97ecd71f86) | Mar 23, 2025 |
| ASRock        | A520M Pro4                  | [a7aa76573b](https://linux-hardware.org/?probe=a7aa76573b) | Mar 23, 2025 |
| Gigabyte      | AB350M-DS3H V2-CF           | [7163fdbaf2](https://linux-hardware.org/?probe=7163fdbaf2) | Mar 22, 2025 |
| Gigabyte      | H97-D3H-CF                  | [fe6d58a4bc](https://linux-hardware.org/?probe=fe6d58a4bc) | Mar 21, 2025 |
| ASUSTek       | P8H61-M LX3                 | [733b20943a](https://linux-hardware.org/?probe=733b20943a) | Mar 20, 2025 |
| Gigabyte      | AB350M-DS3H V2-CF           | [478b8fdf9b](https://linux-hardware.org/?probe=478b8fdf9b) | Mar 19, 2025 |
| Biostar       | A68MHE                      | [311a6e2037](https://linux-hardware.org/?probe=311a6e2037) | Mar 15, 2025 |
| Gigabyte      | GA-970A-DS3                 | [63219f91c3](https://linux-hardware.org/?probe=63219f91c3) | Mar 09, 2025 |
| Pegatron      | IPMSB-H61                   | [66f5fc9a96](https://linux-hardware.org/?probe=66f5fc9a96) | Feb 24, 2025 |
| Intel         | X99-P4 V5.1                 | [76af0e8053](https://linux-hardware.org/?probe=76af0e8053) | Feb 23, 2025 |
| ASUSTek       | H81M-K                      | [5761db173b](https://linux-hardware.org/?probe=5761db173b) | Feb 13, 2025 |
| ASUSTek       | H81M-K                      | [2ee6199435](https://linux-hardware.org/?probe=2ee6199435) | Feb 13, 2025 |
| ASUSTek       | PRIME H510M-R R2.0          | [8c6e89d4ff](https://linux-hardware.org/?probe=8c6e89d4ff) | Feb 13, 2025 |
| LLC PC Aqu... | AQC246DF Series             | [d1a7852073](https://linux-hardware.org/?probe=d1a7852073) | Feb 05, 2025 |
| Dell          | 0YGWFV A02                  | [864e5d51c9](https://linux-hardware.org/?probe=864e5d51c9) | Jan 19, 2025 |
| ASUSTek       | P5B                         | [9c8825ee79](https://linux-hardware.org/?probe=9c8825ee79) | Jan 16, 2025 |
| ASRock        | M3A790GMH/128M              | [d014482d15](https://linux-hardware.org/?probe=d014482d15) | Jan 09, 2025 |
| ICL           | H410SB                      | [a75155cf86](https://linux-hardware.org/?probe=a75155cf86) | Jan 02, 2025 |
| MSI           | PRO H610M-G DDR4            | [da076eeaf3](https://linux-hardware.org/?probe=da076eeaf3) | Jan 02, 2025 |
| ASUSTek       | PRIME H510M-K               | [884ad79ee5](https://linux-hardware.org/?probe=884ad79ee5) | Dec 29, 2024 |
| MSI           | B450M MORTAR MAX            | [f5c01dc687](https://linux-hardware.org/?probe=f5c01dc687) | Dec 28, 2024 |
| MSI           | B450M MORTAR MAX            | [fbaccf3c9e](https://linux-hardware.org/?probe=fbaccf3c9e) | Dec 28, 2024 |
| MSI           | 760G-P43                    | [faf4279015](https://linux-hardware.org/?probe=faf4279015) | Dec 25, 2024 |
| ASRock        | B450 Gaming K4              | [6e86ec71a9](https://linux-hardware.org/?probe=6e86ec71a9) | Dec 23, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [8ccb1a5d52](https://linux-hardware.org/?probe=8ccb1a5d52) | Dec 23, 2024 |
| MSI           | B450-A PRO MAX              | [697b67cc2a](https://linux-hardware.org/?probe=697b67cc2a) | Dec 20, 2024 |
| MSI           | H110M PRO-VD                | [0b9173adf1](https://linux-hardware.org/?probe=0b9173adf1) | Dec 19, 2024 |
| ASUSTek       | PRIME H510M-K               | [7cf5f17079](https://linux-hardware.org/?probe=7cf5f17079) | Dec 18, 2024 |
| ASRock        | Z97 Pro4                    | [1aa9e4d9eb](https://linux-hardware.org/?probe=1aa9e4d9eb) | Dec 15, 2024 |
| HP            | 2B29                        | [9216921849](https://linux-hardware.org/?probe=9216921849) | Dec 14, 2024 |
| DEPO Compu... | DPH110S                     | [bf9bb46070](https://linux-hardware.org/?probe=bf9bb46070) | Dec 13, 2024 |
| Graviton      | DMB-H510-MCA01              | [b4a81ce6eb](https://linux-hardware.org/?probe=b4a81ce6eb) | Dec 11, 2024 |
| DEPO Compu... | DPA520S                     | [5231e4d20b](https://linux-hardware.org/?probe=5231e4d20b) | Dec 06, 2024 |
| ASRock        | A520M Pro4                  | [9b40494a18](https://linux-hardware.org/?probe=9b40494a18) | Nov 30, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | [5050024ce1](https://linux-hardware.org/?probe=5050024ce1) | Nov 26, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [9f23908f61](https://linux-hardware.org/?probe=9f23908f61) | Nov 26, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [140d3172c1](https://linux-hardware.org/?probe=140d3172c1) | Nov 26, 2024 |
| ASRock        | N68-GS4 FX                  | [34007a1ee6](https://linux-hardware.org/?probe=34007a1ee6) | Nov 25, 2024 |
| Gigabyte      | Z97-D3H-CF                  | [da3c0f73b4](https://linux-hardware.org/?probe=da3c0f73b4) | Nov 18, 2024 |
| Gigabyte      | Z97-D3H-CF                  | [508795271f](https://linux-hardware.org/?probe=508795271f) | Nov 15, 2024 |
| ASUSTek       | H87M-PRO                    | [4cfc3ae5e0](https://linux-hardware.org/?probe=4cfc3ae5e0) | Nov 15, 2024 |
| Biostar       | A68MHE                      | [0d3e4beafb](https://linux-hardware.org/?probe=0d3e4beafb) | Nov 13, 2024 |
| MSI           | MAG B760M MORTAR WIFI       | [ab2d6d51bb](https://linux-hardware.org/?probe=ab2d6d51bb) | Nov 12, 2024 |
| MSI           | PRO Z790-P WIFI             | [4a30303850](https://linux-hardware.org/?probe=4a30303850) | Nov 12, 2024 |
| Gigabyte      | B450 GAMING X               | [f898051323](https://linux-hardware.org/?probe=f898051323) | Nov 10, 2024 |
| HP            | 3397                        | [04fa6a24ee](https://linux-hardware.org/?probe=04fa6a24ee) | Nov 08, 2024 |
| HP            | 83EE                        | [491546c0fe](https://linux-hardware.org/?probe=491546c0fe) | Nov 05, 2024 |
| ASRock        | Z68M/USB3                   | [f39d49f78f](https://linux-hardware.org/?probe=f39d49f78f) | Oct 31, 2024 |
| ASUSTek       | M4A89GTD-PRO                | [49f3ef7f7c](https://linux-hardware.org/?probe=49f3ef7f7c) | Oct 28, 2024 |
| Gigabyte      | B550M K                     | [dde963874f](https://linux-hardware.org/?probe=dde963874f) | Oct 27, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | [2a206ed000](https://linux-hardware.org/?probe=2a206ed000) | Oct 26, 2024 |
| MSI           | B550-A PRO                  | [ee26c48295](https://linux-hardware.org/?probe=ee26c48295) | Oct 26, 2024 |
| HP            | 83EE                        | [8cbf62fc9b](https://linux-hardware.org/?probe=8cbf62fc9b) | Oct 21, 2024 |
| MSI           | B450M PRO-VDH MAX           | [6d016ec789](https://linux-hardware.org/?probe=6d016ec789) | Oct 20, 2024 |
| Biostar       | H61MHV3                     | [03f4106810](https://linux-hardware.org/?probe=03f4106810) | Oct 19, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [00e3458bd8](https://linux-hardware.org/?probe=00e3458bd8) | Oct 19, 2024 |
| ASRock        | H61M-VG3                    | [6e0c8954c4](https://linux-hardware.org/?probe=6e0c8954c4) | Oct 18, 2024 |
| ASRock        | H61M-VG3                    | [689b8ad5f4](https://linux-hardware.org/?probe=689b8ad5f4) | Oct 18, 2024 |
| Intel         | B560-AIO T5V E1.0G          | [b1aab7dcb2](https://linux-hardware.org/?probe=b1aab7dcb2) | Oct 17, 2024 |
| Intel         | B560-AIO T5V E1.0G          | [0b038153a1](https://linux-hardware.org/?probe=0b038153a1) | Oct 17, 2024 |
| HP            | 1497                        | [81bc95c34c](https://linux-hardware.org/?probe=81bc95c34c) | Oct 15, 2024 |
| Gigabyte      | A320M-S2H-CF                | [394bacc9ee](https://linux-hardware.org/?probe=394bacc9ee) | Oct 12, 2024 |
| ASUSTek       | PRIME H510M-K               | [6c153457c0](https://linux-hardware.org/?probe=6c153457c0) | Oct 09, 2024 |
| Gigabyte      | H310M S2H x.x               | [bd2ebeb7e0](https://linux-hardware.org/?probe=bd2ebeb7e0) | Sep 30, 2024 |
| HP            | 2B29                        | [f803e78e04](https://linux-hardware.org/?probe=f803e78e04) | Sep 27, 2024 |
| Pegatron      | NM70-P1/ODM                 | [6a2f74fa01](https://linux-hardware.org/?probe=6a2f74fa01) | Sep 27, 2024 |
| Gigabyte      | Z590 VISION G               | [e711388bf1](https://linux-hardware.org/?probe=e711388bf1) | Sep 20, 2024 |
| AZW           | MINI S                      | [26fedf82a8](https://linux-hardware.org/?probe=26fedf82a8) | Sep 18, 2024 |
| ASRock        | B450M-HDV R4.0              | [11fe29956f](https://linux-hardware.org/?probe=11fe29956f) | Sep 18, 2024 |
| ASUSTek       | Z97-K/USB                   | [5b3bbf6f3b](https://linux-hardware.org/?probe=5b3bbf6f3b) | Sep 14, 2024 |
| Kraftway      | KWH310                      | [14063d22e1](https://linux-hardware.org/?probe=14063d22e1) | Sep 07, 2024 |
| ASRock        | A520M Pro4                  | [636eec8156](https://linux-hardware.org/?probe=636eec8156) | Aug 19, 2024 |
| Gigabyte      | 970A-DS3P                   | [d029537860](https://linux-hardware.org/?probe=d029537860) | Aug 19, 2024 |
| MACHINIST     | X99-MR9A PRO MAX V5.1       | [c5b89ad433](https://linux-hardware.org/?probe=c5b89ad433) | Aug 18, 2024 |
| Gigabyte      | 970A-DS3P                   | [7b569e1148](https://linux-hardware.org/?probe=7b569e1148) | Aug 09, 2024 |
| Gigabyte      | B650M DS3H                  | [2d11a234d5](https://linux-hardware.org/?probe=2d11a234d5) | Aug 06, 2024 |
| Unknown       | Unknown                     | [f08e885430](https://linux-hardware.org/?probe=f08e885430) | Aug 01, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | [d7fcb0b28a](https://linux-hardware.org/?probe=d7fcb0b28a) | Jul 28, 2024 |
| MSI           | MS-B0A21                    | [52d37fde14](https://linux-hardware.org/?probe=52d37fde14) | Jul 26, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | [5b236846cf](https://linux-hardware.org/?probe=5b236846cf) | Jul 21, 2024 |
| Unknown       | Unknown                     | [a28e524a63](https://linux-hardware.org/?probe=a28e524a63) | Jul 20, 2024 |
| Acer          | Aspire XC-1660 V:1.1        | [31dbe1ce9e](https://linux-hardware.org/?probe=31dbe1ce9e) | Jul 19, 2024 |
| MSI           | Z97 U3 PLUS                 | [bec2e23ba0](https://linux-hardware.org/?probe=bec2e23ba0) | Jul 13, 2024 |
| MSI           | X470 GAMING PRO             | [704b7ed845](https://linux-hardware.org/?probe=704b7ed845) | Jul 12, 2024 |
| Aquarius      | AQH310CM                    | [65ab62646c](https://linux-hardware.org/?probe=65ab62646c) | Jul 10, 2024 |
| Aquarius      | AQH310CM                    | [8dd8a81958](https://linux-hardware.org/?probe=8dd8a81958) | Jul 10, 2024 |
| Acer          | TDPS05                      | [69ec0ebb0e](https://linux-hardware.org/?probe=69ec0ebb0e) | Jul 05, 2024 |
| Biostar       | A68MHE                      | [8bfd525ace](https://linux-hardware.org/?probe=8bfd525ace) | Jul 05, 2024 |
| Aquarius      | AQH310CM                    | [5be2d7706e](https://linux-hardware.org/?probe=5be2d7706e) | Jul 01, 2024 |
| ASRock        | B550M-HDV                   | [bb05c5cd47](https://linux-hardware.org/?probe=bb05c5cd47) | Jul 01, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [d8b58eedf8](https://linux-hardware.org/?probe=d8b58eedf8) | Jun 28, 2024 |
| ASUSTek       | P5B-Deluxe                  | [5065fe29a2](https://linux-hardware.org/?probe=5065fe29a2) | Jun 26, 2024 |
| ASUSTek       | P5B-Deluxe                  | [b16d910164](https://linux-hardware.org/?probe=b16d910164) | Jun 26, 2024 |
| ASUSTek       | ROG Maximus Z690 HERO       | [c17442ac07](https://linux-hardware.org/?probe=c17442ac07) | Jun 23, 2024 |
| Gigabyte      | B365M D2V                   | [9a4ad817b1](https://linux-hardware.org/?probe=9a4ad817b1) | Jun 23, 2024 |
| Biostar       | A68MHE                      | [14c11d75cb](https://linux-hardware.org/?probe=14c11d75cb) | Jun 22, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | [a6b39899a7](https://linux-hardware.org/?probe=a6b39899a7) | Jun 16, 2024 |
| MSI           | PRO B660M-P DDR4            | [449ead260f](https://linux-hardware.org/?probe=449ead260f) | Jun 09, 2024 |
| Gigabyte      | B250M-DS3H-CF               | [9170618489](https://linux-hardware.org/?probe=9170618489) | Jun 08, 2024 |
| ASUSTek       | PRIME B250M-A               | [ae046e6c96](https://linux-hardware.org/?probe=ae046e6c96) | Jun 04, 2024 |
| ASUSTek       | PRIME X370-PRO              | [7842abdb45](https://linux-hardware.org/?probe=7842abdb45) | Jun 03, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [fcc722c5cb](https://linux-hardware.org/?probe=fcc722c5cb) | May 26, 2024 |
| HP            | 8184 X4                     | [2d56e66964](https://linux-hardware.org/?probe=2d56e66964) | May 22, 2024 |
| BESHTAU       | B560M-D V51                 | [51aab9354b](https://linux-hardware.org/?probe=51aab9354b) | May 20, 2024 |
| Gigabyte      | H610M S2H                   | [342949d0ba](https://linux-hardware.org/?probe=342949d0ba) | May 17, 2024 |
| ASUSTek       | P5PE-VM                     | [c453bf034c](https://linux-hardware.org/?probe=c453bf034c) | May 17, 2024 |
| Aquarius      | AQH310CM                    | [e6b335988e](https://linux-hardware.org/?probe=e6b335988e) | May 14, 2024 |
| ASRock        | H610M-ITX/ac                | [382c5161c1](https://linux-hardware.org/?probe=382c5161c1) | May 13, 2024 |
| ASRock        | B450 Pro4 R2.0              | [2ecceda7ae](https://linux-hardware.org/?probe=2ecceda7ae) | May 09, 2024 |
| Gigabyte      | GA-M56S-S3                  | [93d7cc0722](https://linux-hardware.org/?probe=93d7cc0722) | May 09, 2024 |
| ASRock        | B450 Pro4 R2.0              | [bb1ae830e8](https://linux-hardware.org/?probe=bb1ae830e8) | May 09, 2024 |
| Gigabyte      | B550M DS3H                  | [178f62317e](https://linux-hardware.org/?probe=178f62317e) | May 04, 2024 |
| Gigabyte      | B550M DS3H                  | [f4d652cc40](https://linux-hardware.org/?probe=f4d652cc40) | Apr 25, 2024 |
| ASUSTek       | P8H61-I R2.0                | [db4468debf](https://linux-hardware.org/?probe=db4468debf) | Apr 23, 2024 |
| ASRock        | B450M Pro4-F                | [d721e6ffa6](https://linux-hardware.org/?probe=d721e6ffa6) | Apr 18, 2024 |
| Biostar       | A68MHE                      | [d8db2caef4](https://linux-hardware.org/?probe=d8db2caef4) | Apr 14, 2024 |
| Biostar       | A68MHE                      | [acdf6abfbf](https://linux-hardware.org/?probe=acdf6abfbf) | Apr 14, 2024 |
| MSI           | B450M PRO-VDH MAX           | [dce8bf4cbc](https://linux-hardware.org/?probe=dce8bf4cbc) | Apr 13, 2024 |
| Biostar       | H610MH                      | [06dbe44a85](https://linux-hardware.org/?probe=06dbe44a85) | Apr 13, 2024 |
| AZW           | GTR V02                     | [120d648339](https://linux-hardware.org/?probe=120d648339) | Apr 12, 2024 |
| Dell          | 030VXY A01                  | [03bd29951c](https://linux-hardware.org/?probe=03bd29951c) | Apr 11, 2024 |
| MSI           | B550-A PRO                  | [5ac75aad7e](https://linux-hardware.org/?probe=5ac75aad7e) | Mar 28, 2024 |
| Biostar       | IH61MF-Q5                   | [6f251f08e1](https://linux-hardware.org/?probe=6f251f08e1) | Mar 25, 2024 |
| Aquarius      | AQH310CM                    | [368d914e46](https://linux-hardware.org/?probe=368d914e46) | Mar 24, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | [11f7843550](https://linux-hardware.org/?probe=11f7843550) | Mar 23, 2024 |
| Gigabyte      | B560M AORUS PRO AX          | [693e93ff73](https://linux-hardware.org/?probe=693e93ff73) | Mar 22, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [a8f9e94787](https://linux-hardware.org/?probe=a8f9e94787) | Mar 16, 2024 |
| Gigabyte      | A520M DS3H                  | [d999681595](https://linux-hardware.org/?probe=d999681595) | Mar 16, 2024 |
| Gigabyte      | A520M DS3H                  | [d6731a38c7](https://linux-hardware.org/?probe=d6731a38c7) | Mar 16, 2024 |
| MSI           | B550-A PRO                  | [fd6b99b446](https://linux-hardware.org/?probe=fd6b99b446) | Mar 12, 2024 |
| Unknown       | Intel X79                   | [e88d0410c8](https://linux-hardware.org/?probe=e88d0410c8) | Mar 11, 2024 |
| ASUSTek       | D300TA                      | [a09321cd27](https://linux-hardware.org/?probe=a09321cd27) | Mar 11, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [b6909c9a7a](https://linux-hardware.org/?probe=b6909c9a7a) | Mar 10, 2024 |
| Biostar       | TB250-BTC                   | [c5edeef7fe](https://linux-hardware.org/?probe=c5edeef7fe) | Mar 03, 2024 |
| Aquarius      | AQH310CM                    | [a255e64313](https://linux-hardware.org/?probe=a255e64313) | Feb 22, 2024 |
| ASUSTek       | H81M-K                      | [51188483df](https://linux-hardware.org/?probe=51188483df) | Feb 21, 2024 |
| Unknown       | Unknown                     | [0b2da4684e](https://linux-hardware.org/?probe=0b2da4684e) | Feb 21, 2024 |
| MSI           | H110M PRO-VD                | [61b2aa976f](https://linux-hardware.org/?probe=61b2aa976f) | Feb 13, 2024 |
| ASUSTek       | M4A77TD                     | [75afd83494](https://linux-hardware.org/?probe=75afd83494) | Feb 11, 2024 |
| ASRock        | H61M-HVGS                   | [dc3bd18c15](https://linux-hardware.org/?probe=dc3bd18c15) | Feb 09, 2024 |
| ASUSTek       | P5B-Deluxe                  | [b30373632d](https://linux-hardware.org/?probe=b30373632d) | Feb 01, 2024 |
| ASUSTek       | P6T WS PRO                  | [21d91717a1](https://linux-hardware.org/?probe=21d91717a1) | Jan 31, 2024 |
| ASUSTek       | M5A78L-M LX                 | [8c79f36086](https://linux-hardware.org/?probe=8c79f36086) | Jan 29, 2024 |
| MSI           | MS-B0A21                    | [aebe283d41](https://linux-hardware.org/?probe=aebe283d41) | Jan 26, 2024 |
| MSI           | B550-A PRO                  | [1f374d86d7](https://linux-hardware.org/?probe=1f374d86d7) | Jan 25, 2024 |
| Gigabyte      | H61M-USB3V                  | [6a5faff8dd](https://linux-hardware.org/?probe=6a5faff8dd) | Jan 24, 2024 |
| ASUSTek       | P5B-Deluxe                  | [b628671631](https://linux-hardware.org/?probe=b628671631) | Jan 21, 2024 |
| Aquarius      | AQH310CM                    | [6172ad2c5d](https://linux-hardware.org/?probe=6172ad2c5d) | Jan 20, 2024 |
| ASUSTek       | P6T WS PRO                  | [d8c6804097](https://linux-hardware.org/?probe=d8c6804097) | Jan 18, 2024 |
| ASRock        | J3355M                      | [40caff1c3c](https://linux-hardware.org/?probe=40caff1c3c) | Jan 18, 2024 |
| ASUSTek       | Q87M-E                      | [22cbd96a3b](https://linux-hardware.org/?probe=22cbd96a3b) | Jan 11, 2024 |
| MSI           | B550-A PRO                  | [e658ae012b](https://linux-hardware.org/?probe=e658ae012b) | Jan 11, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [e371e895ec](https://linux-hardware.org/?probe=e371e895ec) | Jan 10, 2024 |
| Aquarius      | AQH310CM                    | [64bd83e185](https://linux-hardware.org/?probe=64bd83e185) | Jan 10, 2024 |
| SZMZ          | H61-ME V1.0                 | [4ca9bf9ced](https://linux-hardware.org/?probe=4ca9bf9ced) | Jan 09, 2024 |
| ASUSTek       | P5G41T-M LX                 | [8bc6ac892f](https://linux-hardware.org/?probe=8bc6ac892f) | Dec 21, 2023 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [cdebd77402](https://linux-hardware.org/?probe=cdebd77402) | Dec 16, 2023 |
| ASUSTek       | M5A78L-M LX                 | [6225f2f85f](https://linux-hardware.org/?probe=6225f2f85f) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [84d4572994](https://linux-hardware.org/?probe=84d4572994) | Dec 12, 2023 |
| Gigabyte      | M55S-S3                     | [bf362d71c7](https://linux-hardware.org/?probe=bf362d71c7) | Dec 09, 2023 |
| ASUSTek       | Q87M-E                      | [df56e68ebc](https://linux-hardware.org/?probe=df56e68ebc) | Dec 04, 2023 |
| MSI           | B550-A PRO                  | [0f258ceffb](https://linux-hardware.org/?probe=0f258ceffb) | Dec 04, 2023 |
| ASUSTek       | P5QL-VM EPU                 | [c70c2ff27f](https://linux-hardware.org/?probe=c70c2ff27f) | Dec 01, 2023 |
| Gigabyte      | H370 HD3-CF                 | [d7367e7072](https://linux-hardware.org/?probe=d7367e7072) | Nov 30, 2023 |
| Gigabyte      | B85-HD3                     | [b64fc99109](https://linux-hardware.org/?probe=b64fc99109) | Nov 29, 2023 |
| Graviton      | DMB-A520-MCA01 1.o          | [f989b31edd](https://linux-hardware.org/?probe=f989b31edd) | Nov 28, 2023 |
| Graviton      | DMB-A520-MCA01 1.o          | [1dce0a4738](https://linux-hardware.org/?probe=1dce0a4738) | Nov 28, 2023 |
| ASUSTek       | P5K                         | [d5cb9ac79b](https://linux-hardware.org/?probe=d5cb9ac79b) | Nov 27, 2023 |
| ASUSTek       | P5B-Deluxe                  | [1af8016aed](https://linux-hardware.org/?probe=1af8016aed) | Nov 27, 2023 |
| ASUSTek       | P5B-Deluxe                  | [668b258270](https://linux-hardware.org/?probe=668b258270) | Nov 27, 2023 |
| HP            | ProLiant SL230s Gen8        | [a0b680d2ac](https://linux-hardware.org/?probe=a0b680d2ac) | Nov 26, 2023 |
| HP            | ProLiant SL230s Gen8        | [b1d3f26e5d](https://linux-hardware.org/?probe=b1d3f26e5d) | Nov 26, 2023 |
| HP            | ProLiant SL230s Gen8        | [800b1eab76](https://linux-hardware.org/?probe=800b1eab76) | Nov 26, 2023 |
| HP            | ProLiant SL230s Gen8        | [35b226a480](https://linux-hardware.org/?probe=35b226a480) | Nov 26, 2023 |
| Unknown       | Unknown                     | [72915fd0dd](https://linux-hardware.org/?probe=72915fd0dd) | Nov 26, 2023 |
| Gigabyte      | B560M D3H                   | [ecf8bf3010](https://linux-hardware.org/?probe=ecf8bf3010) | Nov 26, 2023 |
| MSI           | Z490-A PRO                  | [8fdcfb665c](https://linux-hardware.org/?probe=8fdcfb665c) | Nov 26, 2023 |
| MSI           | B550-A PRO                  | [3914c7ac4f](https://linux-hardware.org/?probe=3914c7ac4f) | Nov 22, 2023 |
| Lenovo        | No DPK                      | [b569bd1d22](https://linux-hardware.org/?probe=b569bd1d22) | Nov 19, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [8b59b311ca](https://linux-hardware.org/?probe=8b59b311ca) | Nov 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [7d34e7f4b0](https://linux-hardware.org/?probe=7d34e7f4b0) | Nov 18, 2023 |
| ASUSTek       | H81M-R                      | [a0617305eb](https://linux-hardware.org/?probe=a0617305eb) | Nov 17, 2023 |
| ASUSTek       | H97-PRO                     | [c5890b8a51](https://linux-hardware.org/?probe=c5890b8a51) | Nov 15, 2023 |
| Pegatron      | 2AB5                        | [8d788a9b4d](https://linux-hardware.org/?probe=8d788a9b4d) | Nov 14, 2023 |
| Pegatron      | 2AB5                        | [c04b52c00e](https://linux-hardware.org/?probe=c04b52c00e) | Nov 14, 2023 |
| ASUSTek       | Q87M-E                      | [2c0511f79f](https://linux-hardware.org/?probe=2c0511f79f) | Nov 12, 2023 |
| MSI           | B550-A PRO                  | [b0bc13f5f8](https://linux-hardware.org/?probe=b0bc13f5f8) | Nov 12, 2023 |
| MSI           | MAG B550M MORTAR            | [b29f519183](https://linux-hardware.org/?probe=b29f519183) | Nov 10, 2023 |
| MSI           | MAG B550M MORTAR            | [cf5ee36e07](https://linux-hardware.org/?probe=cf5ee36e07) | Nov 10, 2023 |
| Gigabyte      | B550M DS3H                  | [fa61fdff34](https://linux-hardware.org/?probe=fa61fdff34) | Nov 09, 2023 |
| Aquarius      | AQX300M                     | [b70a012245](https://linux-hardware.org/?probe=b70a012245) | Nov 01, 2023 |
| ASUSTek       | M5A78L LE                   | [d7dd5dbdf7](https://linux-hardware.org/?probe=d7dd5dbdf7) | Oct 30, 2023 |
| Huanan        | X99-T8 GAMING V2.0          | [27d22c45c8](https://linux-hardware.org/?probe=27d22c45c8) | Oct 26, 2023 |
| AZW           | MINI S                      | [0083fabd4c](https://linux-hardware.org/?probe=0083fabd4c) | Oct 15, 2023 |
| Biostar       | H510MHP                     | [1de1d57c17](https://linux-hardware.org/?probe=1de1d57c17) | Oct 13, 2023 |
| DEPO Compu... | DPA520S                     | [d6cf338b8c](https://linux-hardware.org/?probe=d6cf338b8c) | Oct 12, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [7623527bdb](https://linux-hardware.org/?probe=7623527bdb) | Oct 08, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | [38db8e9cf2](https://linux-hardware.org/?probe=38db8e9cf2) | Oct 04, 2023 |
| Biostar       | H510MHP                     | [1d6b309a9a](https://linux-hardware.org/?probe=1d6b309a9a) | Oct 02, 2023 |
| ASUSTek       | P8H61-M LX2                 | [b2a213cc18](https://linux-hardware.org/?probe=b2a213cc18) | Sep 30, 2023 |
| ASUSTek       | P8H61-M LX2                 | [60e32143f5](https://linux-hardware.org/?probe=60e32143f5) | Sep 29, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | [7cc521d927](https://linux-hardware.org/?probe=7cc521d927) | Sep 29, 2023 |
| Pegatron      | IPMSB-H61                   | [d0e64d2ebf](https://linux-hardware.org/?probe=d0e64d2ebf) | Sep 28, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [1458dfe403](https://linux-hardware.org/?probe=1458dfe403) | Sep 27, 2023 |
| MSI           | H81M-P33                    | [8b0d086b89](https://linux-hardware.org/?probe=8b0d086b89) | Sep 27, 2023 |
| DEPO Compu... | DPA520S                     | [45d07666f9](https://linux-hardware.org/?probe=45d07666f9) | Sep 26, 2023 |
| ASUSTek       | P6T DELUXE V2               | [a0fa16f85c](https://linux-hardware.org/?probe=a0fa16f85c) | Sep 25, 2023 |
| ASRock        | K10N78D                     | [fa2852026b](https://linux-hardware.org/?probe=fa2852026b) | Sep 13, 2023 |
| ASRock        | K10N78D                     | [adf8e09915](https://linux-hardware.org/?probe=adf8e09915) | Sep 13, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [53cdc3e4f0](https://linux-hardware.org/?probe=53cdc3e4f0) | Sep 12, 2023 |
| Intel         | DP43TF AAE34878-404         | [d83ba68fcb](https://linux-hardware.org/?probe=d83ba68fcb) | Sep 05, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [6b33c9cb36](https://linux-hardware.org/?probe=6b33c9cb36) | Sep 02, 2023 |
| Intel         | B75                         | [55695d0962](https://linux-hardware.org/?probe=55695d0962) | Aug 31, 2023 |
| ASUSTek       | P8H61-MX                    | [861e741d6a](https://linux-hardware.org/?probe=861e741d6a) | Aug 29, 2023 |
| ASRock        | B460 Steel Legend           | [09ed405682](https://linux-hardware.org/?probe=09ed405682) | Aug 29, 2023 |
| Intel         | SKYBAY                      | [59cfa4ea58](https://linux-hardware.org/?probe=59cfa4ea58) | Aug 29, 2023 |
| ASRock        | B460 Steel Legend           | [ad478d48ad](https://linux-hardware.org/?probe=ad478d48ad) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [1510eba46f](https://linux-hardware.org/?probe=1510eba46f) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [cc7efa7eba](https://linux-hardware.org/?probe=cc7efa7eba) | Aug 11, 2023 |
| Gigabyte      | X570 AORUS PRO              | [a43111576a](https://linux-hardware.org/?probe=a43111576a) | Aug 09, 2023 |
| DEPO Compu... | DPA520S                     | [71b00682fc](https://linux-hardware.org/?probe=71b00682fc) | Aug 07, 2023 |
| MSI           | PRO B550M-P GEN3            | [163708151e](https://linux-hardware.org/?probe=163708151e) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | [28007801d5](https://linux-hardware.org/?probe=28007801d5) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | [5e3a46dee8](https://linux-hardware.org/?probe=5e3a46dee8) | Aug 03, 2023 |
| ASUSTek       | H110M-K                     | [c12e9ed368](https://linux-hardware.org/?probe=c12e9ed368) | Aug 02, 2023 |
| ASUSTek       | P7F-M                       | [5c04bf12d0](https://linux-hardware.org/?probe=5c04bf12d0) | Aug 02, 2023 |
| HP            | 0AA8h                       | [76dbb0d0a3](https://linux-hardware.org/?probe=76dbb0d0a3) | Jul 31, 2023 |
| ASRock        | G41M-VS2                    | [74564d3418](https://linux-hardware.org/?probe=74564d3418) | Jul 28, 2023 |
| ASUSTek       | P7H55-M LX                  | [543257c1b1](https://linux-hardware.org/?probe=543257c1b1) | Jul 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | [0cf82c02d3](https://linux-hardware.org/?probe=0cf82c02d3) | Jul 18, 2023 |
| ASUSTek       | P5B-Deluxe                  | [da27044389](https://linux-hardware.org/?probe=da27044389) | Jul 17, 2023 |
| Gigabyte      | MRHM3AP                     | [2d91c7c05a](https://linux-hardware.org/?probe=2d91c7c05a) | Jun 28, 2023 |
| Gigabyte      | MRHM3AP                     | [7007bb2db5](https://linux-hardware.org/?probe=7007bb2db5) | Jun 27, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0c4198042a](https://linux-hardware.org/?probe=0c4198042a) | Jun 18, 2023 |
| Biostar       | H610MH                      | [a2c82f65b6](https://linux-hardware.org/?probe=a2c82f65b6) | Jun 08, 2023 |
| ASUSTek       | PRIME Z370-P II             | [5a66eed08e](https://linux-hardware.org/?probe=5a66eed08e) | Jun 05, 2023 |
| MSI           | Z490-A PRO                  | [e34e6ab643](https://linux-hardware.org/?probe=e34e6ab643) | May 26, 2023 |
| Graviton      | DMB-A520-MCA01              | [91ad90fd67](https://linux-hardware.org/?probe=91ad90fd67) | May 22, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [9c184f4251](https://linux-hardware.org/?probe=9c184f4251) | May 22, 2023 |
| Gigabyte      | B560 HD3                    | [1bfbf34771](https://linux-hardware.org/?probe=1bfbf34771) | May 16, 2023 |
| Gigabyte      | G41M-ES2L                   | [d9cac69c4c](https://linux-hardware.org/?probe=d9cac69c4c) | May 16, 2023 |
| Gigabyte      | G41M-ES2L                   | [0959f95f56](https://linux-hardware.org/?probe=0959f95f56) | May 12, 2023 |
| MSI           | H310M PRO-VD                | [b502077711](https://linux-hardware.org/?probe=b502077711) | May 12, 2023 |
| MSI           | H310M PRO-VD                | [ab733d41de](https://linux-hardware.org/?probe=ab733d41de) | May 12, 2023 |
| DEPO Compu... | DPA520S                     | [dea48fc3fa](https://linux-hardware.org/?probe=dea48fc3fa) | May 11, 2023 |
| DEPO Compu... | DPA520S                     | [848dc775e0](https://linux-hardware.org/?probe=848dc775e0) | May 11, 2023 |
| Gigabyte      | H61M-S2PV                   | [3ed55d530a](https://linux-hardware.org/?probe=3ed55d530a) | May 04, 2023 |
| Unknown       | DMB-A520-MCA01              | [d0c1433d54](https://linux-hardware.org/?probe=d0c1433d54) | Apr 18, 2023 |
| Intel         | SKYBAY                      | [ec2b541d85](https://linux-hardware.org/?probe=ec2b541d85) | Apr 13, 2023 |
| ASUSTek       | P8B75-V                     | [3504e8b3bd](https://linux-hardware.org/?probe=3504e8b3bd) | Apr 11, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bec5bda3bd](https://linux-hardware.org/?probe=bec5bda3bd) | Apr 05, 2023 |
| MSI           | H510M PRO-E                 | [9ec66a8f48](https://linux-hardware.org/?probe=9ec66a8f48) | Mar 31, 2023 |
| Graviton      | DMB-A520-MCA01              | [9d7a43d81f](https://linux-hardware.org/?probe=9d7a43d81f) | Mar 29, 2023 |
| Graviton      | DMB-A520-MCA01              | [123e95cee1](https://linux-hardware.org/?probe=123e95cee1) | Mar 22, 2023 |
| Unknown       | Unknown                     | [5d06af8741](https://linux-hardware.org/?probe=5d06af8741) | Mar 22, 2023 |
| Graviton      | DMB-A520-MCA01              | [24b07c4402](https://linux-hardware.org/?probe=24b07c4402) | Mar 21, 2023 |
| Intel         | X99 V1.0                    | [1b993725aa](https://linux-hardware.org/?probe=1b993725aa) | Mar 17, 2023 |
| Biostar       | TB250-BTC                   | [59d148cedc](https://linux-hardware.org/?probe=59d148cedc) | Mar 11, 2023 |
| Gigabyte      | 965GM-S2                    | [8a58676b8d](https://linux-hardware.org/?probe=8a58676b8d) | Mar 10, 2023 |
| Gigabyte      | 965GM-S2                    | [e514c2892e](https://linux-hardware.org/?probe=e514c2892e) | Mar 10, 2023 |
| Intel         | SKYBAY                      | [226b8468d4](https://linux-hardware.org/?probe=226b8468d4) | Mar 09, 2023 |
| ASUSTek       | H110M-R                     | [d62a6bc830](https://linux-hardware.org/?probe=d62a6bc830) | Mar 07, 2023 |
| DEPO Compu... | DPH410S                     | [5fb80da27b](https://linux-hardware.org/?probe=5fb80da27b) | Mar 07, 2023 |
| ASRock        | H110M-DGS R3.0              | [4b3689dc5c](https://linux-hardware.org/?probe=4b3689dc5c) | Mar 05, 2023 |
| Gigabyte      | P31-ES3G                    | [5ab1863f2b](https://linux-hardware.org/?probe=5ab1863f2b) | Feb 28, 2023 |
| MSI           | MS-7357                     | [84cadfbabc](https://linux-hardware.org/?probe=84cadfbabc) | Feb 15, 2023 |
| ASUSTek       | P9X79                       | [d7f1d6a937](https://linux-hardware.org/?probe=d7f1d6a937) | Feb 14, 2023 |
| MAINBRD       | OPS62A-SHA                  | [a9267dffac](https://linux-hardware.org/?probe=a9267dffac) | Feb 14, 2023 |
| ASUSTek       | P5B-E                       | [92bf62be3c](https://linux-hardware.org/?probe=92bf62be3c) | Feb 11, 2023 |
| Acer          | RS880M05                    | [c585589925](https://linux-hardware.org/?probe=c585589925) | Feb 11, 2023 |
| ASRock        | FM2A78 Pro4+                | [788d1d408b](https://linux-hardware.org/?probe=788d1d408b) | Feb 06, 2023 |
| ASRock        | FM2A88X Extreme4+           | [97252e199d](https://linux-hardware.org/?probe=97252e199d) | Feb 06, 2023 |
| Gigabyte      | X570 AORUS PRO              | [ab13127567](https://linux-hardware.org/?probe=ab13127567) | Jan 29, 2023 |
| Intel         | X99 V1.0                    | [560cc09a5a](https://linux-hardware.org/?probe=560cc09a5a) | Jan 26, 2023 |
| Gigabyte      | H61M-DS2                    | [347446f16f](https://linux-hardware.org/?probe=347446f16f) | Jan 25, 2023 |
| Intel         | SKYBAY                      | [0d2187e1bd](https://linux-hardware.org/?probe=0d2187e1bd) | Jan 23, 2023 |
| Intel         | SKYBAY                      | [1781c6451f](https://linux-hardware.org/?probe=1781c6451f) | Jan 23, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [bb4c5c0f73](https://linux-hardware.org/?probe=bb4c5c0f73) | Jan 18, 2023 |
| Intel         | X99 V1.0                    | [c531fbad47](https://linux-hardware.org/?probe=c531fbad47) | Jan 14, 2023 |
| ASRock        | B450M Pro4                  | [fdf24274c5](https://linux-hardware.org/?probe=fdf24274c5) | Jan 13, 2023 |
| Intel         | X79G V2.x                   | [8228b94c50](https://linux-hardware.org/?probe=8228b94c50) | Jan 11, 2023 |
| Yadro         | YadroB560                   | [9d45ee1c8c](https://linux-hardware.org/?probe=9d45ee1c8c) | Jan 11, 2023 |
| Intel         | SKYBAY                      | [b6402cdd5e](https://linux-hardware.org/?probe=b6402cdd5e) | Jan 11, 2023 |
| Intel         | SKYBAY                      | [c896f4d5ee](https://linux-hardware.org/?probe=c896f4d5ee) | Jan 11, 2023 |
| ASUSTek       | P7H55-M                     | [808e7e41c5](https://linux-hardware.org/?probe=808e7e41c5) | Jan 10, 2023 |
| Gigabyte      | Z490 AORUS PRO AX           | [914e3f30cc](https://linux-hardware.org/?probe=914e3f30cc) | Jan 08, 2023 |
| ASUSTek       | P8H77-V LE                  | [bed374999d](https://linux-hardware.org/?probe=bed374999d) | Jan 06, 2023 |
| Gigabyte      | H55M-USB3                   | [2952e11cdb](https://linux-hardware.org/?probe=2952e11cdb) | Jan 01, 2023 |
| Gigabyte      | EP41-UD3L                   | [0456782550](https://linux-hardware.org/?probe=0456782550) | Dec 21, 2022 |
| Unknown       | Unknown                     | [5ad56cab50](https://linux-hardware.org/?probe=5ad56cab50) | Dec 19, 2022 |
| Unknown       | Unknown                     | [e06ebbd650](https://linux-hardware.org/?probe=e06ebbd650) | Dec 19, 2022 |
| Biostar       | TB250-BTC                   | [00dd0bc59e](https://linux-hardware.org/?probe=00dd0bc59e) | Dec 18, 2022 |
| ASUSTek       | M3N78-VM                    | [afd0404144](https://linux-hardware.org/?probe=afd0404144) | Dec 17, 2022 |
| ASUSTek       | M3N78-VM                    | [e7e9b42211](https://linux-hardware.org/?probe=e7e9b42211) | Dec 16, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [2f5b88399a](https://linux-hardware.org/?probe=2f5b88399a) | Dec 13, 2022 |
| Graviton      | DMB-H510-MCA01              | [4dbcbc3b7a](https://linux-hardware.org/?probe=4dbcbc3b7a) | Nov 30, 2022 |
| MSI           | J1800I                      | [156269ae8c](https://linux-hardware.org/?probe=156269ae8c) | Nov 26, 2022 |
| Graviton      | DMB-A520-MCA01              | [1a09a9bb5c](https://linux-hardware.org/?probe=1a09a9bb5c) | Nov 14, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [b5965fce49](https://linux-hardware.org/?probe=b5965fce49) | Nov 11, 2022 |
| ASUSTek       | P7H55-M/USB3                | [d3d30c473e](https://linux-hardware.org/?probe=d3d30c473e) | Nov 10, 2022 |
| Gigabyte      | 8I915GMF                    | [76f5cb17ad](https://linux-hardware.org/?probe=76f5cb17ad) | Nov 10, 2022 |
| ASUSTek       | P7H55-M/USB3                | [8983159779](https://linux-hardware.org/?probe=8983159779) | Oct 30, 2022 |
| ASRock        | Z77 Pro4-M                  | [b388ac6776](https://linux-hardware.org/?probe=b388ac6776) | Oct 27, 2022 |
| Biostar       | TB250-BTC                   | [89e7931244](https://linux-hardware.org/?probe=89e7931244) | Oct 27, 2022 |
| Intel         | D34010WYK H14771-301        | [cea24a780a](https://linux-hardware.org/?probe=cea24a780a) | Oct 26, 2022 |
| Gigabyte      | H61M-S2PV                   | [a876af89ec](https://linux-hardware.org/?probe=a876af89ec) | Oct 24, 2022 |
| MSI           | PRO H610M-B DDR4            | [25db5739b7](https://linux-hardware.org/?probe=25db5739b7) | Oct 24, 2022 |
| Intel         | D34010WYK H14771-301        | [18d8d35afa](https://linux-hardware.org/?probe=18d8d35afa) | Oct 24, 2022 |
| Huanan        | H97-ZD3 V2.0                | [d0d194fbdc](https://linux-hardware.org/?probe=d0d194fbdc) | Oct 15, 2022 |
| Graviton      | DMB-H510-MCA01              | [355974871d](https://linux-hardware.org/?probe=355974871d) | Oct 12, 2022 |
| Graviton      | DMB-H510-MCA01              | [02395d2c6f](https://linux-hardware.org/?probe=02395d2c6f) | Oct 07, 2022 |
| Gigabyte      | H110M-S2-CF                 | [79b160283f](https://linux-hardware.org/?probe=79b160283f) | Oct 05, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [8e3ee86b79](https://linux-hardware.org/?probe=8e3ee86b79) | Oct 05, 2022 |
| ASUSTek       | D300TA                      | [7c175e4db4](https://linux-hardware.org/?probe=7c175e4db4) | Oct 03, 2022 |
| MSI           | B560M PRO-VDH               | [34db101d55](https://linux-hardware.org/?probe=34db101d55) | Sep 22, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [b8609443fe](https://linux-hardware.org/?probe=b8609443fe) | Sep 17, 2022 |
| Gigabyte      | M57SLI-S4                   | [0384b171c7](https://linux-hardware.org/?probe=0384b171c7) | Sep 03, 2022 |
| ASUSTek       | F2A85-V                     | [a6a798ce96](https://linux-hardware.org/?probe=a6a798ce96) | Aug 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [315c1df30c](https://linux-hardware.org/?probe=315c1df30c) | Aug 16, 2022 |
| Dell          | 0W0CHX A00                  | [7d9b8e0f96](https://linux-hardware.org/?probe=7d9b8e0f96) | Aug 01, 2022 |
| OEM           | KX-18 V1.0                  | [a68e653aa9](https://linux-hardware.org/?probe=a68e653aa9) | Jul 14, 2022 |
| Gigabyte      | Z77MX-D3H                   | [c8051cd18e](https://linux-hardware.org/?probe=c8051cd18e) | Jul 13, 2022 |
| MSI           | PRO H610M-G DDR4            | [7a95d588c4](https://linux-hardware.org/?probe=7a95d588c4) | Jul 05, 2022 |
| Gigabyte      | GA-A75M-D2H                 | [7411d7a561](https://linux-hardware.org/?probe=7411d7a561) | Jun 23, 2022 |
| MSI           | Z77A-G43                    | [2724c1558a](https://linux-hardware.org/?probe=2724c1558a) | Jun 20, 2022 |
| MAINBRD       | OPS62A-SHA                  | [8fe4a74fa3](https://linux-hardware.org/?probe=8fe4a74fa3) | Jun 10, 2022 |
| MAINBRD       | OPS62A-SHA                  | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | [31ab5150ea](https://linux-hardware.org/?probe=31ab5150ea) | Jun 06, 2022 |
| ASUSTek       | PRIME Z390-A                | [4fa81ba66a](https://linux-hardware.org/?probe=4fa81ba66a) | Jun 06, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | [fb935ea1d0](https://linux-hardware.org/?probe=fb935ea1d0) | Jun 03, 2022 |
| ASUSTek       | M4A78-EM                    | [7bfddcecee](https://linux-hardware.org/?probe=7bfddcecee) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | [acc0a6ae9c](https://linux-hardware.org/?probe=acc0a6ae9c) | May 31, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | [4ad9ca01bd](https://linux-hardware.org/?probe=4ad9ca01bd) | May 31, 2022 |
| ASUSTek       | PRO H410T                   | [7d7a4c7536](https://linux-hardware.org/?probe=7d7a4c7536) | May 25, 2022 |
| ASUSTek       | M4A78-EM                    | [37a8e41d00](https://linux-hardware.org/?probe=37a8e41d00) | May 25, 2022 |
| Gigabyte      | EP45-UD3LR                  | [ea7f269697](https://linux-hardware.org/?probe=ea7f269697) | May 24, 2022 |
| MAINBRD       | OPS62A-SHA                  | [9450237ae3](https://linux-hardware.org/?probe=9450237ae3) | May 23, 2022 |
| MAINBRD       | OPS62A-SHA                  | [ad85836549](https://linux-hardware.org/?probe=ad85836549) | May 20, 2022 |
| iRU           | LPGR.469559.012             | [9163b267bc](https://linux-hardware.org/?probe=9163b267bc) | May 19, 2022 |
| ASUSTek       | PRO H410T                   | [8ededa12ef](https://linux-hardware.org/?probe=8ededa12ef) | May 16, 2022 |
| ASUSTek       | M4A78-EM                    | [bedc08df5b](https://linux-hardware.org/?probe=bedc08df5b) | May 15, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | [cfb12880a5](https://linux-hardware.org/?probe=cfb12880a5) | May 11, 2022 |
| ASRock        | H61M-GE                     | [fefe67c0d4](https://linux-hardware.org/?probe=fefe67c0d4) | May 05, 2022 |
| Intel         | SKYBAY                      | [4891bdbd5c](https://linux-hardware.org/?probe=4891bdbd5c) | May 04, 2022 |
| ASRock        | A300M-STX                   | [48af028244](https://linux-hardware.org/?probe=48af028244) | Apr 29, 2022 |
| Lenovo        | NOK                         | [4ea735896c](https://linux-hardware.org/?probe=4ea735896c) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | [c75ef7f42d](https://linux-hardware.org/?probe=c75ef7f42d) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | [af1b36d1f6](https://linux-hardware.org/?probe=af1b36d1f6) | Apr 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | [e612a2bab1](https://linux-hardware.org/?probe=e612a2bab1) | Apr 27, 2022 |
| Lenovo        | NOK                         | [6d17068770](https://linux-hardware.org/?probe=6d17068770) | Apr 27, 2022 |
| Acer          | Veriton X2640G V:1.0        | [f1e5d5715f](https://linux-hardware.org/?probe=f1e5d5715f) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [a0e3085b4c](https://linux-hardware.org/?probe=a0e3085b4c) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [9819b3fc78](https://linux-hardware.org/?probe=9819b3fc78) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [d27d03b7e4](https://linux-hardware.org/?probe=d27d03b7e4) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [a8784c861a](https://linux-hardware.org/?probe=a8784c861a) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [b970feef75](https://linux-hardware.org/?probe=b970feef75) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | [6bfffcf96a](https://linux-hardware.org/?probe=6bfffcf96a) | Apr 25, 2022 |
| Unknown       | Unknown                     | [c7c9ed4c0e](https://linux-hardware.org/?probe=c7c9ed4c0e) | Apr 21, 2022 |
| Intel         | SKYBAY                      | [ec99a4a73b](https://linux-hardware.org/?probe=ec99a4a73b) | Apr 19, 2022 |
| Intel         | SKYBAY                      | [807bf178aa](https://linux-hardware.org/?probe=807bf178aa) | Apr 19, 2022 |
| Intel         | SKYBAY                      | [5ce5f89e30](https://linux-hardware.org/?probe=5ce5f89e30) | Apr 18, 2022 |
| Intel         | SKYBAY                      | [016707b662](https://linux-hardware.org/?probe=016707b662) | Apr 18, 2022 |
| Acer          | Veriton X2640G V:1.0        | [472e946f77](https://linux-hardware.org/?probe=472e946f77) | Apr 18, 2022 |
| Intel         | SKYBAY                      | [f227fe1fc7](https://linux-hardware.org/?probe=f227fe1fc7) | Apr 18, 2022 |
| Intel         | SKYBAY                      | [49039d6324](https://linux-hardware.org/?probe=49039d6324) | Apr 18, 2022 |
| Intel         | SKYBAY                      | [39553516dd](https://linux-hardware.org/?probe=39553516dd) | Apr 18, 2022 |
| Intel         | SKYBAY                      | [9f87ee8978](https://linux-hardware.org/?probe=9f87ee8978) | Apr 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [bf274bc0f4](https://linux-hardware.org/?probe=bf274bc0f4) | Apr 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [53137ae702](https://linux-hardware.org/?probe=53137ae702) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | [a98b8b4304](https://linux-hardware.org/?probe=a98b8b4304) | Apr 14, 2022 |
| Intel         | SKYBAY                      | [0d3978670a](https://linux-hardware.org/?probe=0d3978670a) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | [3829d7dfca](https://linux-hardware.org/?probe=3829d7dfca) | Apr 14, 2022 |
| Intel         | SKYBAY                      | [13122b16be](https://linux-hardware.org/?probe=13122b16be) | Apr 14, 2022 |
| Intel         | SKYBAY                      | [82df5d5154](https://linux-hardware.org/?probe=82df5d5154) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [c55e8d0780](https://linux-hardware.org/?probe=c55e8d0780) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [46344da31f](https://linux-hardware.org/?probe=46344da31f) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [906a9f0a46](https://linux-hardware.org/?probe=906a9f0a46) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [482922befd](https://linux-hardware.org/?probe=482922befd) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [2cb7352d17](https://linux-hardware.org/?probe=2cb7352d17) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [54f3bbf0af](https://linux-hardware.org/?probe=54f3bbf0af) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [f7d3604a6b](https://linux-hardware.org/?probe=f7d3604a6b) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [40083e1990](https://linux-hardware.org/?probe=40083e1990) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [ecf34aa4f0](https://linux-hardware.org/?probe=ecf34aa4f0) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [baf8cdeb1a](https://linux-hardware.org/?probe=baf8cdeb1a) | Apr 13, 2022 |
| Gigabyte      | G31M-ES2L                   | [1eacb6915d](https://linux-hardware.org/?probe=1eacb6915d) | Apr 12, 2022 |
| MSI           | A68HM-E33 V2                | [0fecbe6cdc](https://linux-hardware.org/?probe=0fecbe6cdc) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [97d94278ea](https://linux-hardware.org/?probe=97d94278ea) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [5ebaca158a](https://linux-hardware.org/?probe=5ebaca158a) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [7e40f60767](https://linux-hardware.org/?probe=7e40f60767) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [ce83b095fe](https://linux-hardware.org/?probe=ce83b095fe) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | [105088d6de](https://linux-hardware.org/?probe=105088d6de) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | [126b987221](https://linux-hardware.org/?probe=126b987221) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [5d59afae00](https://linux-hardware.org/?probe=5d59afae00) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [442de26b34](https://linux-hardware.org/?probe=442de26b34) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [9d7fc26276](https://linux-hardware.org/?probe=9d7fc26276) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [e07ab03ffb](https://linux-hardware.org/?probe=e07ab03ffb) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [b4b977309d](https://linux-hardware.org/?probe=b4b977309d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [bff39744bc](https://linux-hardware.org/?probe=bff39744bc) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [01cd534e80](https://linux-hardware.org/?probe=01cd534e80) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [669e6289c0](https://linux-hardware.org/?probe=669e6289c0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [d49df4c170](https://linux-hardware.org/?probe=d49df4c170) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [01aa1a4299](https://linux-hardware.org/?probe=01aa1a4299) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [a85817bb6d](https://linux-hardware.org/?probe=a85817bb6d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [25955c9bb1](https://linux-hardware.org/?probe=25955c9bb1) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [0c81aeca67](https://linux-hardware.org/?probe=0c81aeca67) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [e72fe0a0a9](https://linux-hardware.org/?probe=e72fe0a0a9) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [33b61b457e](https://linux-hardware.org/?probe=33b61b457e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [d6c6259cc0](https://linux-hardware.org/?probe=d6c6259cc0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [f2444b315d](https://linux-hardware.org/?probe=f2444b315d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [aa745aba70](https://linux-hardware.org/?probe=aa745aba70) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [3b73c79a3c](https://linux-hardware.org/?probe=3b73c79a3c) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [d1a4cd1698](https://linux-hardware.org/?probe=d1a4cd1698) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [54713393ec](https://linux-hardware.org/?probe=54713393ec) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [56d2022832](https://linux-hardware.org/?probe=56d2022832) | Apr 12, 2022 |
| Intel         | SKYBAY                      | [efbe0a9eca](https://linux-hardware.org/?probe=efbe0a9eca) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [60fbf7929d](https://linux-hardware.org/?probe=60fbf7929d) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [e9a0bae6e6](https://linux-hardware.org/?probe=e9a0bae6e6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [4fb63d6dfe](https://linux-hardware.org/?probe=4fb63d6dfe) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [8ee5753b25](https://linux-hardware.org/?probe=8ee5753b25) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [6fb5a857e1](https://linux-hardware.org/?probe=6fb5a857e1) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [613ea0ab6b](https://linux-hardware.org/?probe=613ea0ab6b) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [2aeec4566f](https://linux-hardware.org/?probe=2aeec4566f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [5751abaf6c](https://linux-hardware.org/?probe=5751abaf6c) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [31b40a1aa0](https://linux-hardware.org/?probe=31b40a1aa0) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [d3bbe595ba](https://linux-hardware.org/?probe=d3bbe595ba) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [24d5b7f6c6](https://linux-hardware.org/?probe=24d5b7f6c6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [f94dbbfc1f](https://linux-hardware.org/?probe=f94dbbfc1f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [960168908f](https://linux-hardware.org/?probe=960168908f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [71610e6e10](https://linux-hardware.org/?probe=71610e6e10) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [d2407bd778](https://linux-hardware.org/?probe=d2407bd778) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [88fc4d57ec](https://linux-hardware.org/?probe=88fc4d57ec) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [a1cbc192aa](https://linux-hardware.org/?probe=a1cbc192aa) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [66d94b1220](https://linux-hardware.org/?probe=66d94b1220) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [e8c2f02ba1](https://linux-hardware.org/?probe=e8c2f02ba1) | Apr 11, 2022 |
| Unknown       | Unknown                     | [7ef15ed6c9](https://linux-hardware.org/?probe=7ef15ed6c9) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [8bcad9c229](https://linux-hardware.org/?probe=8bcad9c229) | Apr 11, 2022 |
| ASRock        | FM2A55M-HD+                 | [a03ff53e01](https://linux-hardware.org/?probe=a03ff53e01) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [5486388fa0](https://linux-hardware.org/?probe=5486388fa0) | Apr 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [237634ce8d](https://linux-hardware.org/?probe=237634ce8d) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [83b01e222e](https://linux-hardware.org/?probe=83b01e222e) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [c6f290816a](https://linux-hardware.org/?probe=c6f290816a) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [60c4fc315b](https://linux-hardware.org/?probe=60c4fc315b) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [faad64ac67](https://linux-hardware.org/?probe=faad64ac67) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f3fe662dcb](https://linux-hardware.org/?probe=f3fe662dcb) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [5293db1b11](https://linux-hardware.org/?probe=5293db1b11) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [7d3b364ff0](https://linux-hardware.org/?probe=7d3b364ff0) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [d8307a4138](https://linux-hardware.org/?probe=d8307a4138) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [bffde28b59](https://linux-hardware.org/?probe=bffde28b59) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [7d31dd74d7](https://linux-hardware.org/?probe=7d31dd74d7) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [7d03a291a2](https://linux-hardware.org/?probe=7d03a291a2) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [91f33b247d](https://linux-hardware.org/?probe=91f33b247d) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [2628069096](https://linux-hardware.org/?probe=2628069096) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [7c2a257e92](https://linux-hardware.org/?probe=7c2a257e92) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [868b030342](https://linux-hardware.org/?probe=868b030342) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [4088112a18](https://linux-hardware.org/?probe=4088112a18) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [68820282cb](https://linux-hardware.org/?probe=68820282cb) | Apr 11, 2022 |
| Unknown       | Unknown                     | [5a5a1a7ae6](https://linux-hardware.org/?probe=5a5a1a7ae6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [936252dfca](https://linux-hardware.org/?probe=936252dfca) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [67ed2ddd29](https://linux-hardware.org/?probe=67ed2ddd29) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [fde95ea3ed](https://linux-hardware.org/?probe=fde95ea3ed) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [de01821ecf](https://linux-hardware.org/?probe=de01821ecf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [67f41bf764](https://linux-hardware.org/?probe=67f41bf764) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [77aadf6511](https://linux-hardware.org/?probe=77aadf6511) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [cb9ae4e880](https://linux-hardware.org/?probe=cb9ae4e880) | Apr 11, 2022 |
| ASUSTek       | A68HM-K                     | [0199b0b388](https://linux-hardware.org/?probe=0199b0b388) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [d2a24f0327](https://linux-hardware.org/?probe=d2a24f0327) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [498dd8c409](https://linux-hardware.org/?probe=498dd8c409) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [fa2978c8db](https://linux-hardware.org/?probe=fa2978c8db) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [150ce1c4dd](https://linux-hardware.org/?probe=150ce1c4dd) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [76e9ddaa30](https://linux-hardware.org/?probe=76e9ddaa30) | Apr 11, 2022 |
| Unknown       | Unknown                     | [43c08af7bf](https://linux-hardware.org/?probe=43c08af7bf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | [093a6488c3](https://linux-hardware.org/?probe=093a6488c3) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | [730280aef1](https://linux-hardware.org/?probe=730280aef1) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [679df55359](https://linux-hardware.org/?probe=679df55359) | Apr 06, 2022 |
| Unknown       | S074VI5R8                   | [3fd567de05](https://linux-hardware.org/?probe=3fd567de05) | Apr 06, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | [7e10ceda79](https://linux-hardware.org/?probe=7e10ceda79) | Apr 06, 2022 |
| ASRock        | M3N78D FX                   | [66bb134c6c](https://linux-hardware.org/?probe=66bb134c6c) | Mar 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [d01df98d83](https://linux-hardware.org/?probe=d01df98d83) | Mar 28, 2022 |
| ASRock        | M3N78D FX                   | [3ebcef4241](https://linux-hardware.org/?probe=3ebcef4241) | Mar 28, 2022 |
| Unknown       | Unknown                     | [95628eab40](https://linux-hardware.org/?probe=95628eab40) | Mar 24, 2022 |
| ASRock        | A300M-STX                   | [1fb2262bcc](https://linux-hardware.org/?probe=1fb2262bcc) | Mar 17, 2022 |
| Gigabyte      | G41MT-D3                    | [92fc99440a](https://linux-hardware.org/?probe=92fc99440a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | [f7f470651e](https://linux-hardware.org/?probe=f7f470651e) | Feb 17, 2022 |
| Gigabyte      | X79-UD3                     | [452ebf6a67](https://linux-hardware.org/?probe=452ebf6a67) | Feb 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [921e224ec5](https://linux-hardware.org/?probe=921e224ec5) | Feb 12, 2022 |
| Aquarius      | AQH410T                     | [351b2e5344](https://linux-hardware.org/?probe=351b2e5344) | Jan 31, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [481e745592](https://linux-hardware.org/?probe=481e745592) | Jan 30, 2022 |
| ASRock        | B450 Gaming K4              | [8c31667834](https://linux-hardware.org/?probe=8c31667834) | Jan 20, 2022 |
| Graviton      | DMB-A520-MCA01              | [edd6464f18](https://linux-hardware.org/?probe=edd6464f18) | Jan 19, 2022 |
| Graviton      | DMB-A520-MCA01              | [93fef2e073](https://linux-hardware.org/?probe=93fef2e073) | Jan 19, 2022 |
| MSI           | A68HM-P33 V2                | [98e05db690](https://linux-hardware.org/?probe=98e05db690) | Jan 17, 2022 |
| ASRock        | B450 Gaming K4              | [0c802de596](https://linux-hardware.org/?probe=0c802de596) | Jan 14, 2022 |
| Gigabyte      | H77M-D3H                    | [c8ff16f0ed](https://linux-hardware.org/?probe=c8ff16f0ed) | Dec 24, 2021 |
| Supermicro    | X11SDW-14CNT-TP13F          | [4d8499f8ba](https://linux-hardware.org/?probe=4d8499f8ba) | Dec 23, 2021 |
| ASRock        | A320M-HDV R4.0              | [9180a824d8](https://linux-hardware.org/?probe=9180a824d8) | Dec 23, 2021 |
| ASRock        | B450 Gaming K4              | [7ef05a32a9](https://linux-hardware.org/?probe=7ef05a32a9) | Dec 17, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | [2aff2121af](https://linux-hardware.org/?probe=2aff2121af) | Dec 16, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | [30eab5f54f](https://linux-hardware.org/?probe=30eab5f54f) | Dec 15, 2021 |
| Gigabyte      | B550 GAMING X               | [c853f62ddd](https://linux-hardware.org/?probe=c853f62ddd) | Dec 06, 2021 |
| Unknown       | Unknown                     | [0f5c69902a](https://linux-hardware.org/?probe=0f5c69902a) | Dec 01, 2021 |
| ASRock        | B450M Pro4                  | [68a1f83b4f](https://linux-hardware.org/?probe=68a1f83b4f) | Nov 28, 2021 |
| Gigabyte      | B550 GAMING X               | [058d8a0404](https://linux-hardware.org/?probe=058d8a0404) | Nov 19, 2021 |
| ASUSTek       | P5Q                         | [70ee05a53e](https://linux-hardware.org/?probe=70ee05a53e) | Oct 28, 2021 |
| Gigabyte      | B450 AORUS M                | [d9dd1b763b](https://linux-hardware.org/?probe=d9dd1b763b) | Oct 08, 2021 |
| Dell          | 0U649C                      | [80e138d949](https://linux-hardware.org/?probe=80e138d949) | Sep 24, 2021 |
| ASRock        | X300M-STX                   | [da7d22c384](https://linux-hardware.org/?probe=da7d22c384) | Sep 16, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [132286ab64](https://linux-hardware.org/?probe=132286ab64) | Aug 17, 2021 |
| Gigabyte      | H77M-D3H                    | [85ce2f74c4](https://linux-hardware.org/?probe=85ce2f74c4) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [624e92e15e](https://linux-hardware.org/?probe=624e92e15e) | Aug 11, 2021 |
| Gigabyte      | H510M S2H                   | [db68dde16d](https://linux-hardware.org/?probe=db68dde16d) | Aug 04, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [b01641d467](https://linux-hardware.org/?probe=b01641d467) | Jul 25, 2021 |
| Gigabyte      | H110M-S2V-CF                | [8687a8809b](https://linux-hardware.org/?probe=8687a8809b) | Jul 14, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | [05be9fcdec](https://linux-hardware.org/?probe=05be9fcdec) | Jul 03, 2021 |
| Gigabyte      | H110M-S2V-CF                | [24bd5ac93f](https://linux-hardware.org/?probe=24bd5ac93f) | Jun 27, 2021 |
| Kraftway      | KWH310                      | [f470a86a1c](https://linux-hardware.org/?probe=f470a86a1c) | Jun 26, 2021 |
| ASRock        | H110M-DGS R3.0              | [87ab7018c4](https://linux-hardware.org/?probe=87ab7018c4) | Jun 24, 2021 |
| MSI           | H110M PRO-VD                | [21a019dcb3](https://linux-hardware.org/?probe=21a019dcb3) | Jun 14, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | [8325754280](https://linux-hardware.org/?probe=8325754280) | Jun 13, 2021 |
| MSI           | H110M PRO-VD                | [96cc5b470f](https://linux-hardware.org/?probe=96cc5b470f) | Jun 12, 2021 |
| MSI           | H110M PRO-VD                | [cfeb0493d3](https://linux-hardware.org/?probe=cfeb0493d3) | Jun 11, 2021 |
| ASRock        | J3455B-ITX                  | [13396a7347](https://linux-hardware.org/?probe=13396a7347) | May 19, 2021 |
| DEPO Compu... | DPH410S                     | [0d1000e904](https://linux-hardware.org/?probe=0d1000e904) | May 14, 2021 |
| DEPO Compu... | DPA320S G10g                | [5ecc011c34](https://linux-hardware.org/?probe=5ecc011c34) | May 14, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | [97b70c1bac](https://linux-hardware.org/?probe=97b70c1bac) | Apr 17, 2021 |
| Acer          | H11H4-AI V:1.0              | [34997240d5](https://linux-hardware.org/?probe=34997240d5) | Mar 30, 2021 |
| ECS           | BAT-I2                      | [037e6e58e6](https://linux-hardware.org/?probe=037e6e58e6) | Mar 30, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [f0c7659cf9](https://linux-hardware.org/?probe=f0c7659cf9) | Mar 29, 2021 |
| Gigabyte      | P35-S3G                     | [8e53d68603](https://linux-hardware.org/?probe=8e53d68603) | Mar 20, 2021 |
| ASUSTek       | N3150M-E                    | [7467b59c82](https://linux-hardware.org/?probe=7467b59c82) | Mar 17, 2021 |
| ASUSTek       | PRIME B250-PRO              | [c62af0239b](https://linux-hardware.org/?probe=c62af0239b) | Mar 17, 2021 |
| iRU           | IRUB365M                    | [b7d5dda036](https://linux-hardware.org/?probe=b7d5dda036) | Mar 11, 2021 |
| Gigabyte      | GA-MA69VM-S2                | [6651c76da3](https://linux-hardware.org/?probe=6651c76da3) | Feb 07, 2021 |
| Gigabyte      | GA-MA69VM-S2                | [d63a1e9eef](https://linux-hardware.org/?probe=d63a1e9eef) | Feb 02, 2021 |
| ASUSTek       | P5B                         | [e0fc318a34](https://linux-hardware.org/?probe=e0fc318a34) | Jan 28, 2021 |
| EPoX Compu... | GeForce6100 + nForce410 ... | [99f734d52e](https://linux-hardware.org/?probe=99f734d52e) | Jan 18, 2021 |
| Gigabyte      | H110M-S2H-CF                | [38ae5dd532](https://linux-hardware.org/?probe=38ae5dd532) | Jan 14, 2021 |
| Intel         | B75                         | [34d29fb066](https://linux-hardware.org/?probe=34d29fb066) | Jan 12, 2021 |
| Gigabyte      | H110M-S2H-CF                | [2c49129777](https://linux-hardware.org/?probe=2c49129777) | Jan 09, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [31d84f6485](https://linux-hardware.org/?probe=31d84f6485) | Dec 31, 2020 |
| SYS           | H310SB                      | [ba93a151f2](https://linux-hardware.org/?probe=ba93a151f2) | Dec 24, 2020 |
| HP            | 877E A                      | [4456ec4081](https://linux-hardware.org/?probe=4456ec4081) | Dec 23, 2020 |
| HP            | 877E A                      | [145b54d631](https://linux-hardware.org/?probe=145b54d631) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | [c560d2aa9b](https://linux-hardware.org/?probe=c560d2aa9b) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | [8286c6ca5c](https://linux-hardware.org/?probe=8286c6ca5c) | Dec 23, 2020 |
| Lenovo        | SDK0E50510 WIN              | [dbc40fef9d](https://linux-hardware.org/?probe=dbc40fef9d) | Dec 18, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [bb4bd8f82f](https://linux-hardware.org/?probe=bb4bd8f82f) | Dec 09, 2020 |
| ASRock        | X299 Steel Legend           | [fdfcfb17c6](https://linux-hardware.org/?probe=fdfcfb17c6) | Dec 03, 2020 |
| ASRock        | X299 Steel Legend           | [98800b881c](https://linux-hardware.org/?probe=98800b881c) | Dec 03, 2020 |
| Gigabyte      | H310N x.x                   | [b0ca19ee36](https://linux-hardware.org/?probe=b0ca19ee36) | Dec 02, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [4ec24e5c24](https://linux-hardware.org/?probe=4ec24e5c24) | Nov 27, 2020 |
| ASUSTek       | Z8NR-D12                    | [2758f1ff94](https://linux-hardware.org/?probe=2758f1ff94) | Nov 21, 2020 |
| iRU           | IRUB365M                    | [ab7e110c9a](https://linux-hardware.org/?probe=ab7e110c9a) | Nov 17, 2020 |
| iRU           | IRUB365M                    | [ed5fee32dd](https://linux-hardware.org/?probe=ed5fee32dd) | Nov 13, 2020 |
| Gigabyte      | H77M-D3H                    | [c878b046bc](https://linux-hardware.org/?probe=c878b046bc) | Nov 13, 2020 |
| Acer          | H11H4-AI V:1.0              | [5ad12e4b3b](https://linux-hardware.org/?probe=5ad12e4b3b) | Nov 12, 2020 |
| Gigabyte      | J1800N-D2H                  | [e25041fb04](https://linux-hardware.org/?probe=e25041fb04) | Nov 09, 2020 |
| ASUSTek       | A8N-E                       | [f716673893](https://linux-hardware.org/?probe=f716673893) | Oct 24, 2020 |
| ASUSTek       | P5B-MX                      | [0779d0f18c](https://linux-hardware.org/?probe=0779d0f18c) | Oct 24, 2020 |
| Acer          | Aspire XC-885 V:1.1         | [f587011ab7](https://linux-hardware.org/?probe=f587011ab7) | Sep 10, 2020 |
| ASRock        | G31M-VS                     | [fb4e557598](https://linux-hardware.org/?probe=fb4e557598) | Aug 16, 2020 |
| ASRock        | 4CoreN73PV-HD720p           | [ac70970005](https://linux-hardware.org/?probe=ac70970005) | Aug 16, 2020 |
| Gigabyte      | EP35C-DS3R                  | [4c98d77a2f](https://linux-hardware.org/?probe=4c98d77a2f) | Aug 07, 2020 |
| ASRock        | G31M-VS                     | [c4c8bad6ca](https://linux-hardware.org/?probe=c4c8bad6ca) | May 31, 2020 |
| Gigabyte      | A320M-S2H-CF                | [74899486ac](https://linux-hardware.org/?probe=74899486ac) | May 26, 2020 |
| ASUSTek       | PRIME B250-PRO              | [8dddac7046](https://linux-hardware.org/?probe=8dddac7046) | Mar 25, 2020 |
| Gigabyte      | H77M-D3H                    | [a644a3a3ad](https://linux-hardware.org/?probe=a644a3a3ad) | Nov 24, 2019 |
| HP            | 09F0h                       | [7f6c26af5d](https://linux-hardware.org/?probe=7f6c26af5d) | Oct 25, 2019 |
| MSI           | B350M PRO-VDH               | [525f09653e](https://linux-hardware.org/?probe=525f09653e) | Oct 08, 2019 |
| Gigabyte      | GA-890XA-UD3                | [1536999c3e](https://linux-hardware.org/?probe=1536999c3e) | Sep 13, 2019 |
| ASRock        | Z77 Pro3                    | [a1db2eb143](https://linux-hardware.org/?probe=a1db2eb143) | Sep 13, 2019 |
| ASRock        | B85M                        | [5a36ce2620](https://linux-hardware.org/?probe=5a36ce2620) | Sep 13, 2019 |
| ASUSTek       | Z97-A                       | [68dbf33470](https://linux-hardware.org/?probe=68dbf33470) | Aug 03, 2019 |
| ASUSTek       | A8N-VM CSM                  | [5814b6a2af](https://linux-hardware.org/?probe=5814b6a2af) | Mar 28, 2019 |
| ASUSTek       | H110M-R                     | [34b40d93fc](https://linux-hardware.org/?probe=34b40d93fc) | Oct 30, 2018 |
| ASRock        | FM2A68M-HD+                 | [d55532d7a9](https://linux-hardware.org/?probe=d55532d7a9) | Oct 29, 2018 |
| Biostar       | NF720D A2G+                 | [ef09cb18cc](https://linux-hardware.org/?probe=ef09cb18cc) | Oct 29, 2018 |
| ASUSTek       | H110M-R                     | [572c918e8a](https://linux-hardware.org/?probe=572c918e8a) | Oct 27, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ALT_Linux/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Kometa P10         | 81       | 15.7%   |
| ALT Linux 10.1     | 65       | 12.6%   |
| ALT Linux 11.0     | 51       | 9.88%   |
| ALT Linux 10.2     | 47       | 9.11%   |
| ALT Linux 10.4     | 39       | 7.56%   |
| ALT Linux 9.1      | 33       | 6.4%    |
| ALT Linux 10.0     | 25       | 4.84%   |
| ALT Linux 20240122 | 22       | 4.26%   |
| ALT Linux 10.3     | 17       | 3.29%   |
| ALT Linux 9.0      | 15       | 2.91%   |
| ALT Linux 11.1     | 15       | 2.91%   |
| MOS 10             | 14       | 2.71%   |
| ALT Linux 10       | 12       | 2.33%   |
| ALT Linux 8.4      | 9        | 1.74%   |
| ALT Linux 9.2      | 7        | 1.36%   |
| ALT Linux 11       | 7        | 1.36%   |
| ALT Linux P10      | 5        | 0.97%   |
| ALT Linux P9       | 4        | 0.78%   |
| ALT Linux 20250612 | 4        | 0.78%   |
| ALT Linux 20230819 | 4        | 0.78%   |
| ALT Linux 10.1.990 | 4        | 0.78%   |
| ALT Linux 10.1.900 | 4        | 0.78%   |
| ALT Linux 0.9.3    | 4        | 0.78%   |
| ALT Linux 8.2      | 3        | 0.58%   |
| ALT Linux 10.900   | 3        | 0.58%   |
| ALT Linux 0.9.2    | 3        | 0.58%   |
| ALT Linux P8       | 2        | 0.39%   |
| ALT Linux 7.0.5    | 2        | 0.39%   |
| ALT Linux 20220110 | 2        | 0.39%   |
| ALT Linux 20201124 | 2        | 0.39%   |
| ALT Linux 10.0.900 | 2        | 0.39%   |
| ALT Linux 0.9.1    | 2        | 0.39%   |
| Kometa 1           | 1        | 0.19%   |
| ALT Linux 8.2.0    | 1        | 0.19%   |
| ALT Linux 20190303 | 1        | 0.19%   |
| ALT Linux 10.2.2   | 1        | 0.19%   |
| ALT Linux 10.0.910 | 1        | 0.19%   |
| ALT Linux 0.8.1    | 1        | 0.19%   |
| ALT Linux 0.7.6    | 1        | 0.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ALT Linux | 477      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.10.109-std-def-alt1      | 51       | 9.48%   |
| 6.12.34-6.12-alt1          | 36       | 6.69%   |
| 5.10.102-std-def-alt1      | 27       | 5.02%   |
| 5.15.34-un-def-alt1        | 15       | 2.79%   |
| 5.10.164-std-def-alt1      | 12       | 2.23%   |
| 5.15.72-un-def-alt1        | 10       | 1.86%   |
| 6.12.41-6.12-alt1          | 9        | 1.67%   |
| 5.10.82-std-def-alt1       | 9        | 1.67%   |
| 5.10.198-std-def-alt1      | 9        | 1.67%   |
| 6.1.115-un-def-alt1        | 8        | 1.49%   |
| 5.15.80-un-def-alt1        | 8        | 1.49%   |
| 5.4.68-std-def-alt1.1      | 7        | 1.3%    |
| 5.10.123-std-def-alt1      | 7        | 1.3%    |
| 6.1.81-un-def-alt1         | 6        | 1.12%   |
| 6.1.49-un-def-alt1         | 6        | 1.12%   |
| 5.10.88-std-def-alt1       | 6        | 1.12%   |
| 5.10.166-std-def-alt1      | 6        | 1.12%   |
| 6.1.79-un-def-alt1         | 5        | 0.93%   |
| 6.1.55-un-def-alt1         | 5        | 0.93%   |
| 5.4.51-std-def-alt1        | 5        | 0.93%   |
| 5.15.32-un-def-alt1        | 5        | 0.93%   |
| 6.1.38-un-def-alt1         | 4        | 0.74%   |
| 6.1.111-un-def-alt1        | 4        | 0.74%   |
| 5.10.156-std-def-alt1      | 4        | 0.74%   |
| 5.10.145-std-def-alt1      | 4        | 0.74%   |
| 6.6.32-un-def-alt1         | 3        | 0.56%   |
| 6.6.21-un-def-alt1         | 3        | 0.56%   |
| 6.12.24-6.12-alt1          | 3        | 0.56%   |
| 6.12.21-6.12-alt1          | 3        | 0.56%   |
| 6.12.19-6.12-alt1          | 3        | 0.56%   |
| 6.1.57-un-def-alt1         | 3        | 0.56%   |
| 6.1.119-un-def-alt1        | 3        | 0.56%   |
| 6.1.107-un-def-alt0.c10f.1 | 3        | 0.56%   |
| 5.4.41-std-def-alt1        | 3        | 0.56%   |
| 5.4.28-std-def-alt1        | 3        | 0.56%   |
| 5.15.96-un-def-alt1        | 3        | 0.56%   |
| 5.10.93-std-def-alt1       | 3        | 0.56%   |
| 5.10.83-std-def-alt0.c9f.2 | 3        | 0.56%   |
| 5.10.35-un-def-alt1        | 3        | 0.56%   |
| 5.10.32-un-def-alt1        | 3        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.109 | 51       | 9.48%   |
| 6.12.34  | 36       | 6.69%   |
| 5.10.102 | 27       | 5.02%   |
| 5.15.34  | 15       | 2.79%   |
| 5.10.164 | 12       | 2.23%   |
| 5.15.72  | 10       | 1.86%   |
| 5.10.198 | 10       | 1.86%   |
| 6.12.41  | 9        | 1.67%   |
| 5.10.82  | 9        | 1.67%   |
| 6.1.115  | 8        | 1.49%   |
| 5.4.68   | 8        | 1.49%   |
| 5.15.80  | 8        | 1.49%   |
| 5.10.123 | 7        | 1.3%    |
| 6.1.81   | 6        | 1.12%   |
| 6.1.49   | 6        | 1.12%   |
| 5.10.88  | 6        | 1.12%   |
| 5.10.166 | 6        | 1.12%   |
| 6.1.79   | 5        | 0.93%   |
| 6.1.55   | 5        | 0.93%   |
| 5.4.51   | 5        | 0.93%   |
| 5.15.32  | 5        | 0.93%   |
| 5.10.156 | 5        | 0.93%   |
| 6.1.38   | 4        | 0.74%   |
| 6.1.112  | 4        | 0.74%   |
| 6.1.111  | 4        | 0.74%   |
| 6.1.100  | 4        | 0.74%   |
| 5.10.145 | 4        | 0.74%   |
| 6.6.56   | 3        | 0.56%   |
| 6.6.32   | 3        | 0.56%   |
| 6.6.21   | 3        | 0.56%   |
| 6.12.24  | 3        | 0.56%   |
| 6.12.21  | 3        | 0.56%   |
| 6.12.19  | 3        | 0.56%   |
| 6.1.57   | 3        | 0.56%   |
| 6.1.119  | 3        | 0.56%   |
| 6.1.107  | 3        | 0.56%   |
| 5.4.41   | 3        | 0.56%   |
| 5.4.28   | 3        | 0.56%   |
| 5.15.96  | 3        | 0.56%   |
| 5.14.21  | 3        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 189      | 37.28%  |
| 6.1     | 86       | 16.96%  |
| 6.12    | 69       | 13.61%  |
| 5.15    | 55       | 10.85%  |
| 5.4     | 39       | 7.69%   |
| 6.6     | 29       | 5.72%   |
| 4.19    | 7        | 1.38%   |
| 6.5     | 4        | 0.79%   |
| 6.9     | 3        | 0.59%   |
| 5.7     | 3        | 0.59%   |
| 5.2     | 3        | 0.59%   |
| 5.14    | 3        | 0.59%   |
| 4.9     | 3        | 0.59%   |
| 6.4     | 2        | 0.39%   |
| 6.11    | 2        | 0.39%   |
| 4.14    | 2        | 0.39%   |
| 6.17    | 1        | 0.2%    |
| 6.16    | 1        | 0.2%    |
| 6.15    | 1        | 0.2%    |
| 5.9     | 1        | 0.2%    |
| 5.18    | 1        | 0.2%    |
| 5.13    | 1        | 0.2%    |
| 5.12    | 1        | 0.2%    |
| 4.20    | 1        | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 466      | 97.69%  |
| e2k         | 5        | 1.05%   |
| i686        | 4        | 0.84%   |
| loongarch64 | 2        | 0.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KDE5             | 225      | 45.55%  |
| Unknown          | 92       | 18.62%  |
| XFCE             | 91       | 18.42%  |
| GNOME            | 38       | 7.69%   |
| MATE             | 25       | 5.06%   |
| KDE:KDE-Wayland  | 5        | 1.01%   |
| KDE:KDE-X11      | 4        | 0.81%   |
| KDE6             | 4        | 0.81%   |
| KDE              | 3        | 0.61%   |
| X-Cinnamon       | 2        | 0.4%    |
| Cinnamon         | 2        | 0.4%    |
| LXQt             | 1        | 0.2%    |
| KDE:KDE-Wayland: | 1        | 0.2%    |
| Hyprland         | 1        | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 406      | 84.41%  |
| Wayland | 39       | 8.11%   |
| Unknown | 25       | 5.2%    |
| Tty     | 11       | 2.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 175      | 35.86%  |
| SDDM    | 143      | 29.3%   |
| Unknown | 123      | 25.2%   |
| TDM     | 28       | 5.74%   |
| GDM     | 17       | 3.48%   |
| WDM     | 1        | 0.2%    |
| GREETD  | 1        | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 428      | 88.07%  |
| Unknown | 40       | 8.23%   |
| en_US   | 12       | 2.47%   |
| POSIX   | 4        | 0.82%   |
| ru      | 1        | 0.21%   |
| el_GR   | 1        | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 253      | 52.38%  |
| BIOS | 230      | 47.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 397      | 81.69%  |
| Btrfs   | 72       | 14.81%  |
| Overlay | 15       | 3.09%   |
| Xfs     | 1        | 0.21%   |
| Tmpfs   | 1        | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 281      | 57.94%  |
| Unknown | 113      | 23.3%   |
| MBR     | 91       | 18.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 423      | 87.76%  |
| Yes       | 59       | 12.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 354      | 72.84%  |
| Yes       | 132      | 27.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 99       | 20.75%  |
| Gigabyte Technology | 97       | 20.34%  |
| Intel               | 58       | 12.16%  |
| ASRock              | 48       | 10.06%  |
| MSI                 | 45       | 9.43%   |
| Unknown             | 20       | 4.19%   |
| Acer                | 16       | 3.35%   |
| Hewlett-Packard     | 13       | 2.73%   |
| Biostar             | 11       | 2.31%   |
| DEPO Computers      | 8        | 1.68%   |
| Graviton            | 5        | 1.05%   |
| MAINBRD             | 4        | 0.84%   |
| Lenovo              | 4        | 0.84%   |
| Huanan              | 4        | 0.84%   |
| Dell                | 4        | 0.84%   |
| 3Logic Group        | 4        | 0.84%   |
| Pegatron            | 3        | 0.63%   |
| iRU                 | 3        | 0.63%   |
| BESHTAU             | 3        | 0.63%   |
| AZW                 | 3        | 0.63%   |
| Aquarius            | 3        | 0.63%   |
| Kraftway            | 2        | 0.42%   |
| Yadro               | 1        | 0.21%   |
| WeiBu               | 1        | 0.21%   |
| VIA Technologies    | 1        | 0.21%   |
| SZMZ                | 1        | 0.21%   |
| SYS                 | 1        | 0.21%   |
| Supermicro          | 1        | 0.21%   |
| RDW Computers       | 1        | 0.21%   |
| RAMEC               | 1        | 0.21%   |
| OEM                 | 1        | 0.21%   |
| MACHINIST           | 1        | 0.21%   |
| Loongson            | 1        | 0.21%   |
| LLC PC Aquarius     | 1        | 0.21%   |
| INFERIT             | 1        | 0.21%   |
| ICL                 | 1        | 0.21%   |
| GEEKOM              | 1        | 0.21%   |
| Foxconn             | 1        | 0.21%   |
| EPoX Computer       | 1        | 0.21%   |
| ECS                 | 1        | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel SKYBAY                     | 47       | 9.85%   |
| Unknown                          | 20       | 4.19%   |
| ASUS PRIME B450-PLUS             | 12       | 2.52%   |
| Acer Veriton X2640G              | 10       | 2.1%    |
| ASUS All Series                  | 8        | 1.68%   |
| Gigabyte H110M-S2H               | 5        | 1.05%   |
| ASUS H110M-R                     | 5        | 1.05%   |
| MSI MS-7D46                      | 4        | 0.84%   |
| MSI MS-7C56                      | 4        | 0.84%   |
| MAINBRD OPS62A-SHA               | 4        | 0.84%   |
| HP ProLiant SL230s Gen8          | 4        | 0.84%   |
| DEPO Computers DPA520S           | 4        | 0.84%   |
| ASUS P5B-Deluxe                  | 4        | 0.84%   |
| 3Logic Group Graviton            | 4        | 0.84%   |
| MSI MS-7A38                      | 3        | 0.63%   |
| Gigabyte A320M-S2H               | 3        | 0.63%   |
| ASUS PRIME H510M-K               | 3        | 0.63%   |
| ASRock H610M-HDV/M.2+ D5         | 3        | 0.63%   |
| ASRock B450M Pro4                | 3        | 0.63%   |
| MSI MS-7C94                      | 2        | 0.42%   |
| MSI MS-7C75                      | 2        | 0.42%   |
| MSI MS-7B89                      | 2        | 0.42%   |
| MSI MS-7817                      | 2        | 0.42%   |
| MSI MPG B560 Trident A (MS-B926) | 2        | 0.42%   |
| iRU 515                          | 2        | 0.42%   |
| Intel B75                        | 2        | 0.42%   |
| Graviton DMB-A520-MCA01          | 2        | 0.42%   |
| Gigabyte Z390 AORUS MASTER       | 2        | 0.42%   |
| Gigabyte H77M-D3H                | 2        | 0.42%   |
| Gigabyte H410M H V2              | 2        | 0.42%   |
| Gigabyte B550M DS3H              | 2        | 0.42%   |
| Gigabyte B450 AORUS M            | 2        | 0.42%   |
| Gigabyte AB350M-DS3H V2          | 2        | 0.42%   |
| Gigabyte A320M-H                 | 2        | 0.42%   |
| DEPO Computers DPH410S           | 2        | 0.42%   |
| AZW MINI S                       | 2        | 0.42%   |
| ASUS PRIME H310M-R R2.0          | 2        | 0.42%   |
| ASUS P8H61-MX                    | 2        | 0.42%   |
| ASUS A68HM-K                     | 2        | 0.42%   |
| ASRock B550M Pro4                | 2        | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Intel SKYBAY           | 47       | 9.85%   |
| ASUS PRIME             | 31       | 6.5%    |
| Unknown                | 20       | 4.19%   |
| Acer Veriton           | 14       | 2.94%   |
| ASUS All               | 8        | 1.68%   |
| Gigabyte H110M-S2H     | 5        | 1.05%   |
| Gigabyte B450          | 5        | 1.05%   |
| ASUS H110M-R           | 5        | 1.05%   |
| MSI MS-7D46            | 4        | 0.84%   |
| MSI MS-7C56            | 4        | 0.84%   |
| MAINBRD OPS62A-SHA     | 4        | 0.84%   |
| HP ProLiant            | 4        | 0.84%   |
| HP Compaq              | 4        | 0.84%   |
| Gigabyte H410M         | 4        | 0.84%   |
| Gigabyte B550M         | 4        | 0.84%   |
| Gigabyte B550          | 4        | 0.84%   |
| Gigabyte A320M-S2H     | 4        | 0.84%   |
| DEPO Computers DPA520S | 4        | 0.84%   |
| Dell OptiPlex          | 4        | 0.84%   |
| ASUS ROG               | 4        | 0.84%   |
| ASUS P5B-Deluxe        | 4        | 0.84%   |
| ASRock B450M           | 4        | 0.84%   |
| 3Logic Group Graviton  | 4        | 0.84%   |
| MSI MS-7A38            | 3        | 0.63%   |
| Gigabyte Z390          | 3        | 0.63%   |
| Gigabyte B560M         | 3        | 0.63%   |
| ASUS P7H55-M           | 3        | 0.63%   |
| ASUS P5G41T-M          | 3        | 0.63%   |
| ASRock H610M-HDV       | 3        | 0.63%   |
| ASRock B450            | 3        | 0.63%   |
| MSI MS-7C94            | 2        | 0.42%   |
| MSI MS-7C75            | 2        | 0.42%   |
| MSI MS-7B89            | 2        | 0.42%   |
| MSI MS-7817            | 2        | 0.42%   |
| MSI MPG                | 2        | 0.42%   |
| Lenovo ThinkCentre     | 2        | 0.42%   |
| iRU 515                | 2        | 0.42%   |
| Intel X99              | 2        | 0.42%   |
| Intel B75              | 2        | 0.42%   |
| Huanan X99-QD4         | 2        | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 71       | 14.88%  |
| 2017    | 46       | 9.64%   |
| 2021    | 39       | 8.18%   |
| 2020    | 39       | 8.18%   |
| 2022    | 35       | 7.34%   |
| 2016    | 31       | 6.5%    |
| 2019    | 24       | 5.03%   |
| 2023    | 23       | 4.82%   |
| 2013    | 22       | 4.61%   |
| 2012    | 22       | 4.61%   |
| 2014    | 19       | 3.98%   |
| 2010    | 15       | 3.14%   |
| 2009    | 14       | 2.94%   |
| 2011    | 13       | 2.73%   |
| 2006    | 11       | 2.31%   |
| 2015    | 10       | 2.1%    |
| 2024    | 9        | 1.89%   |
| 2007    | 9        | 1.89%   |
| 2008    | 8        | 1.68%   |
| Unknown | 7        | 1.47%   |
| 2025    | 5        | 1.05%   |
| 2005    | 3        | 0.63%   |
| 2004    | 1        | 0.21%   |
| 2003    | 1        | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 477      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 455      | 94.79%  |
| Enabled  | 25       | 5.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 477      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 133      | 27.59%  |
| 4.01-8.0    | 98       | 20.33%  |
| 16.01-24.0  | 83       | 17.22%  |
| 32.01-64.0  | 65       | 13.49%  |
| 3.01-4.0    | 54       | 11.2%   |
| 64.01-256.0 | 19       | 3.94%   |
| 24.01-32.0  | 13       | 2.7%    |
| 1.01-2.0    | 9        | 1.87%   |
| 2.01-3.0    | 6        | 1.24%   |
| 0.51-1.0    | 2        | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 202      | 39%     |
| 2.01-3.0   | 107      | 20.66%  |
| 4.01-8.0   | 76       | 14.67%  |
| 3.01-4.0   | 56       | 10.81%  |
| 0.51-1.0   | 48       | 9.27%   |
| 8.01-16.0  | 19       | 3.67%   |
| 16.01-24.0 | 4        | 0.77%   |
| 0.01-0.5   | 3        | 0.58%   |
| 32.01-64.0 | 2        | 0.39%   |
| 24.01-32.0 | 1        | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 269      | 54.45%  |
| 2      | 108      | 21.86%  |
| 3      | 57       | 11.54%  |
| 4      | 34       | 6.88%   |
| 5      | 15       | 3.04%   |
| 6      | 5        | 1.01%   |
| 8      | 2        | 0.4%    |
| 7      | 2        | 0.4%    |
| 9      | 1        | 0.2%    |
| 0      | 1        | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 344      | 71.52%  |
| Yes       | 137      | 28.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 473      | 99.16%  |
| No        | 4        | 0.84%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 357      | 74.22%  |
| Yes       | 124      | 25.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 377      | 78.22%  |
| Yes       | 105      | 21.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Russia     | 450      | 94.14%  |
| Ukraine    | 11       | 2.3%    |
| Greece     | 4        | 0.84%   |
| Belarus    | 3        | 0.63%   |
| Latvia     | 2        | 0.42%   |
| Kazakhstan | 2        | 0.42%   |
| UK         | 1        | 0.21%   |
| Israel     | 1        | 0.21%   |
| Germany    | 1        | 0.21%   |
| Finland    | 1        | 0.21%   |
| China      | 1        | 0.21%   |
| Bangladesh | 1        | 0.21%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Moscow                   | 191      | 38.98%  |
| St Petersburg            | 40       | 8.16%   |
| Novosibirsk              | 12       | 2.45%   |
| Krasnodar                | 12       | 2.45%   |
| Samara                   | 9        | 1.84%   |
| Krasnoyarsk              | 9        | 1.84%   |
| Kazan’                 | 9        | 1.84%   |
| Rostov-on-Don            | 8        | 1.63%   |
| Zheleznodorozhnyy        | 7        | 1.43%   |
| Chelyabinsk              | 7        | 1.43%   |
| Yekaterinburg            | 6        | 1.22%   |
| Barnaul                  | 6        | 1.22%   |
| Stavropol                | 5        | 1.02%   |
| Simferopol               | 5        | 1.02%   |
| Vladimir                 | 4        | 0.82%   |
| Tyumen                   | 4        | 0.82%   |
| Surgut                   | 4        | 0.82%   |
| Saratov                  | 4        | 0.82%   |
| Irkutsk                  | 4        | 0.82%   |
| Balashikha               | 4        | 0.82%   |
| Voronezh                 | 3        | 0.61%   |
| Perm                     | 3        | 0.61%   |
| Omsk                     | 3        | 0.61%   |
| Kirov                    | 3        | 0.61%   |
| Donetsk                  | 3        | 0.61%   |
| Zelenodolsk              | 2        | 0.41%   |
| Volgograd                | 2        | 0.41%   |
| Vladivostok              | 2        | 0.41%   |
| Tolyatti                 | 2        | 0.41%   |
| Sevastopol               | 2        | 0.41%   |
| Sergiyev Posad           | 2        | 0.41%   |
| Riga                     | 2        | 0.41%   |
| Petropavlovsk-Kamchatsky | 2        | 0.41%   |
| Orenburg                 | 2        | 0.41%   |
| Obninsk                  | 2        | 0.41%   |
| Nizhny Tagil             | 2        | 0.41%   |
| Nigrita                  | 2        | 0.41%   |
| Murmansk                 | 2        | 0.41%   |
| Luhansk                  | 2        | 0.41%   |
| Lipetsk                  | 2        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 132      | 209    | 16.56%  |
| Seagate                     | 106      | 163    | 13.3%   |
| Samsung Electronics         | 77       | 103    | 9.66%   |
| Toshiba                     | 58       | 90     | 7.28%   |
| Kingston                    | 52       | 71     | 6.52%   |
| AXIOMTEK                    | 29       | 31     | 3.64%   |
| Apacer                      | 26       | 34     | 3.26%   |
| China                       | 22       | 27     | 2.76%   |
| A-DATA Technology           | 19       | 20     | 2.38%   |
| Netac                       | 15       | 16     | 1.88%   |
| MAXIO Technology (Hangzhou) | 15       | 15     | 1.88%   |
| Hitachi                     | 15       | 18     | 1.88%   |
| Patriot                     | 12       | 15     | 1.51%   |
| Silicon Motion              | 11       | 12     | 1.38%   |
| Crucial                     | 10       | 10     | 1.25%   |
| AMD                         | 10       | 10     | 1.25%   |
| SPCC                        | 9        | 9      | 1.13%   |
| SanDisk                     | 9        | 11     | 1.13%   |
| Gigabyte Technology         | 8        | 8      | 1%      |
| XPG                         | 7        | 8      | 0.88%   |
| Kingston Technology Company | 7        | 10     | 0.88%   |
| Intel                       | 7        | 13     | 0.88%   |
| TMI                         | 6        | 7      | 0.75%   |
| Team                        | 6        | 8      | 0.75%   |
| Plextor                     | 6        | 8      | 0.75%   |
| Phison Electronics          | 6        | 9      | 0.75%   |
| Micron Technology           | 6        | 9      | 0.75%   |
| Hewlett-Packard             | 6        | 10     | 0.75%   |
| XrayDisk                    | 5        | 5      | 0.63%   |
| Smartbuy                    | 5        | 6      | 0.63%   |
| Phison                      | 5        | 6      | 0.63%   |
| KingSpec                    | 5        | 5      | 0.63%   |
| Unknown                     | 4        | 6      | 0.5%    |
| mSTORE                      | 4        | 7      | 0.5%    |
| GS                          | 4        | 9      | 0.5%    |
| Colorful                    | 4        | 5      | 0.5%    |
| Transcend                   | 3        | 4      | 0.38%   |
| OCZ                         | 3        | 5      | 0.38%   |
| MSI                         | 3        | 5      | 0.38%   |
| HGST                        | 3        | 3      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD                  | 29       | 3.36%   |
| Toshiba HDWD110 1TB                                   | 18       | 2.09%   |
| Samsung MZVLW128HEGR-00000 128GB                      | 18       | 2.09%   |
| Toshiba HDWD120 2TB                                   | 13       | 1.51%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB      | 12       | 1.39%   |
| WDC WD5000AZLX-21K2TA0 500GB                          | 10       | 1.16%   |
| Kingston SA400S37240G 240GB SSD                       | 9        | 1.04%   |
| Toshiba DT01ACA050 500GB                              | 8        | 0.93%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 8        | 0.93%   |
| Seagate ST1000DM010-2EP102 1TB                        | 8        | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 7        | 0.81%   |
| Seagate ST500DM002-1BD142 500GB                       | 7        | 0.81%   |
| Kingston SA400S37120G 120GB SSD                       | 6        | 0.7%    |
| Apacer AS350 256GB SSD                                | 6        | 0.7%    |
| Toshiba DT01ACA100 1TB                                | 5        | 0.58%   |
| Seagate ST31000528AS 1TB                              | 5        | 0.58%   |
| Samsung SSD 870 EVO 500GB                             | 5        | 0.58%   |
| Samsung SSD 860 EVO 500GB                             | 5        | 0.58%   |
| Samsung SSD 860 EVO 250GB                             | 5        | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 5        | 0.58%   |
| Apacer AS2280P4 512GB                                 | 5        | 0.58%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                      | 4        | 0.46%   |
| WDC WD20EZBX-00AYRA0 2TB                              | 4        | 0.46%   |
| WDC WD10EZEX-00BBHA0 1TB                              | 4        | 0.46%   |
| Seagate ST3500418AS 500GB                             | 4        | 0.46%   |
| Seagate ST250DM000-1BD141 250GB                       | 4        | 0.46%   |
| Seagate ST2000DM008-2FR102 2TB                        | 4        | 0.46%   |
| Samsung SSD 870 QVO 1TB                               | 4        | 0.46%   |
| Patriot Burst Elite 240GB SSD                         | 4        | 0.46%   |
| mSTORE MSMMN500256-S25 256GB SSD                      | 4        | 0.46%   |
| Kingston SV300S37A120G 120GB SSD                      | 4        | 0.46%   |
| Kingston SA400S37480G 480GB SSD                       | 4        | 0.46%   |
| Kingston RBUSC180S37256GJ 256GB SSD                   | 4        | 0.46%   |
| HP EG0450FCSPK 450GB                                  | 4        | 0.46%   |
| GS SSD 256-8 240GB                                    | 4        | 0.46%   |
| XPG GAMMIX S11 Pro 1TB                                | 3        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 3        | 0.35%   |
| WDC WDS240G1G0A-00SS50 240GB SSD                      | 3        | 0.35%   |
| WDC WD5003ABYZ-011FA0 500GB                           | 3        | 0.35%   |
| WDC WD40EZAZ-00SF3B0 4TB                              | 3        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 115      | 189    | 37.1%   |
| Seagate             | 104      | 157    | 33.55%  |
| Toshiba             | 57       | 87     | 18.39%  |
| Hitachi             | 15       | 18     | 4.84%   |
| Samsung Electronics | 8        | 9      | 2.58%   |
| HGST                | 3        | 3      | 0.97%   |
| Maxtor              | 2        | 2      | 0.65%   |
| JMicron Technology  | 2        | 2      | 0.65%   |
| XrayDisk            | 1        | 1      | 0.32%   |
| Unknown             | 1        | 2      | 0.32%   |
| SINTECHI            | 1        | 1      | 0.32%   |
| ASMT                | 1        | 2      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 41       | 52     | 13.06%  |
| Samsung Electronics | 29       | 41     | 9.24%   |
| AXIOMTEK            | 29       | 31     | 9.24%   |
| China               | 20       | 24     | 6.37%   |
| Apacer              | 20       | 26     | 6.37%   |
| WDC                 | 18       | 18     | 5.73%   |
| A-DATA Technology   | 12       | 13     | 3.82%   |
| Patriot             | 10       | 13     | 3.18%   |
| AMD                 | 9        | 9      | 2.87%   |
| Netac               | 8        | 9      | 2.55%   |
| TMI                 | 6        | 7      | 1.91%   |
| Team                | 6        | 8      | 1.91%   |
| Plextor             | 6        | 8      | 1.91%   |
| Gigabyte Technology | 6        | 6      | 1.91%   |
| Crucial             | 6        | 6      | 1.91%   |
| SPCC                | 5        | 5      | 1.59%   |
| Smartbuy            | 5        | 6      | 1.59%   |
| Intel               | 5        | 10     | 1.59%   |
| XrayDisk            | 4        | 4      | 1.27%   |
| mSTORE              | 4        | 7      | 1.27%   |
| GS                  | 4        | 9      | 1.27%   |
| Transcend           | 3        | 3      | 0.96%   |
| SanDisk             | 3        | 3      | 0.96%   |
| OCZ                 | 3        | 5      | 0.96%   |
| Micron Technology   | 3        | 3      | 0.96%   |
| KingSpec            | 3        | 3      | 0.96%   |
| GOODRAM             | 3        | 3      | 0.96%   |
| Digma               | 3        | 4      | 0.96%   |
| Colorful            | 3        | 4      | 0.96%   |
| Toshiba             | 2        | 2      | 0.64%   |
| Seagate             | 2        | 6      | 0.64%   |
| Phison              | 2        | 2      | 0.64%   |
| Kston               | 2        | 2      | 0.64%   |
| HS-SSD-C100         | 2        | 2      | 0.64%   |
| DEXP                | 2        | 3      | 0.64%   |
| DEPO                | 2        | 2      | 0.64%   |
| BESHTAU             | 2        | 2      | 0.64%   |
| Unknown             | 2        | 3      | 0.64%   |
| SP-8                | 1        | 1      | 0.32%   |
| SHAREVDI            | 1        | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 267      | 388    | 38.98%  |
| HDD     | 253      | 473    | 36.93%  |
| NVMe    | 157      | 214    | 22.92%  |
| Unknown | 7        | 10     | 1.02%   |
| MMC     | 1        | 1      | 0.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 405      | 849    | 70.07%  |
| NVMe | 157      | 213    | 27.16%  |
| SAS  | 15       | 23     | 2.6%    |
| MMC  | 1        | 1      | 0.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 311      | 474    | 57.38%  |
| 0.51-1.0   | 145      | 244    | 26.75%  |
| 1.01-2.0   | 58       | 110    | 10.7%   |
| 3.01-4.0   | 18       | 22     | 3.32%   |
| 2.01-3.0   | 7        | 8      | 1.29%   |
| 4.01-10.0  | 2        | 2      | 0.37%   |
| 0          | 1        | 1      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 175      | 35.14%  |
| 251-500        | 94       | 18.88%  |
| 1001-2000      | 60       | 12.05%  |
| 501-1000       | 60       | 12.05%  |
| More than 3000 | 33       | 6.63%   |
| 2001-3000      | 24       | 4.82%   |
| 51-100         | 21       | 4.22%   |
| 21-50          | 14       | 2.81%   |
| 1-20           | 9        | 1.81%   |
| Unknown        | 8        | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 176      | 34.58%  |
| 21-50          | 114      | 22.4%   |
| 101-250        | 53       | 10.41%  |
| 51-100         | 49       | 9.63%   |
| 501-1000       | 36       | 7.07%   |
| 251-500        | 29       | 5.7%    |
| 1001-2000      | 23       | 4.52%   |
| More than 3000 | 11       | 2.16%   |
| 2001-3000      | 10       | 1.96%   |
| Unknown        | 8        | 1.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| GS SSD 256-8 240GB                           | 4        | 8      | 5.8%    |
| WDC WD5002AALX-00J37A0 500GB                 | 2        | 5      | 2.9%    |
| WDC WD5000AAKX-001CA0 500GB                  | 2        | 2      | 2.9%    |
| Seagate ST9250315AS 250GB                    | 2        | 2      | 2.9%    |
| Seagate ST31000524AS 1TB                     | 2        | 3      | 2.9%    |
| Seagate ST250DM000-1BD141 250GB              | 2        | 3      | 2.9%    |
| XrayDisk 512GB SSD                           | 1        | 1      | 1.45%   |
| XrayDisk 240GB SSD                           | 1        | 1      | 1.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1        | 1      | 1.45%   |
| WDC WD7501AALS-00E3A0 752GB                  | 1        | 1      | 1.45%   |
| WDC WD7500AAKS-00RBA0 752GB                  | 1        | 2      | 1.45%   |
| WDC WD6400AARS-00Y5B1 640GB                  | 1        | 1      | 1.45%   |
| WDC WD5003ABYZ-011FA0 500GB                  | 1        | 1      | 1.45%   |
| WDC WD5000BEVT-22A0RT0 500GB                 | 1        | 1      | 1.45%   |
| WDC WD5000AAKS-00V1A0 500GB                  | 1        | 1      | 1.45%   |
| WDC WD3200AAKS-00V1A0 320GB                  | 1        | 1      | 1.45%   |
| WDC WD2500KS-00MJB0 250GB                    | 1        | 1      | 1.45%   |
| WDC WD2500BEVT-60ZCT1 250GB                  | 1        | 3      | 1.45%   |
| WDC WD20EJRX-89G3VY0 2TB                     | 1        | 1      | 1.45%   |
| WDC WD20EARX-008FB0 2TB                      | 1        | 1      | 1.45%   |
| WDC WD2005FBYZ-01YCBB3 2TB                   | 1        | 1      | 1.45%   |
| WDC WD10EZEX-22RKKA0 1TB                     | 1        | 1      | 1.45%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 1        | 1      | 1.45%   |
| WDC WD10EURX-73C57Y0 1TB                     | 1        | 1      | 1.45%   |
| WDC WD1003FZEX-00K3CA0 1TB                   | 1        | 1      | 1.45%   |
| WDC WD1003FBYX-01Y7B0 1TB                    | 1        | 2      | 1.45%   |
| Toshiba MQ04ABF100 1TB                       | 1        | 1      | 1.45%   |
| Toshiba HDWD110 1TB                          | 1        | 1      | 1.45%   |
| Toshiba DT01ACA050 500GB                     | 1        | 1      | 1.45%   |
| Seagate STM3500418AS 500GB                   | 1        | 1      | 1.45%   |
| Seagate ST9500530NS 42D0743 42D0746IBM 500GB | 1        | 1      | 1.45%   |
| Seagate ST500LM030-1RK17D 500GB              | 1        | 1      | 1.45%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 1      | 1.45%   |
| Seagate ST4000DM000-1F2168 4TB               | 1        | 2      | 1.45%   |
| Seagate ST380815AS 80GB                      | 1        | 1      | 1.45%   |
| Seagate ST380811AS 80GB                      | 1        | 1      | 1.45%   |
| Seagate ST3320418AS 320GB                    | 1        | 1      | 1.45%   |
| Seagate ST3200820AS 200GB                    | 1        | 1      | 1.45%   |
| Seagate ST32000641AS 2TB                     | 1        | 2      | 1.45%   |
| Seagate ST3000DM001-1CH166 3TB               | 1        | 1      | 1.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 29     | 31.88%  |
| Seagate             | 20       | 24     | 28.99%  |
| Hitachi             | 7        | 8      | 10.14%  |
| GS                  | 4        | 8      | 5.8%    |
| Toshiba             | 3        | 3      | 4.35%   |
| XrayDisk            | 2        | 2      | 2.9%    |
| Samsung Electronics | 2        | 2      | 2.9%    |
| Netac               | 2        | 2      | 2.9%    |
| A-DATA Technology   | 2        | 2      | 2.9%    |
| OCZ                 | 1        | 1      | 1.45%   |
| Kingston            | 1        | 4      | 1.45%   |
| DEPO                | 1        | 1      | 1.45%   |
| Corsair             | 1        | 4      | 1.45%   |
| AMD                 | 1        | 1      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 28     | 40.38%  |
| Seagate             | 20       | 24     | 38.46%  |
| Hitachi             | 7        | 8      | 13.46%  |
| Toshiba             | 3        | 3      | 5.77%   |
| Samsung Electronics | 1        | 1      | 1.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 45       | 64     | 73.77%  |
| SSD  | 13       | 24     | 21.31%  |
| NVMe | 3        | 3      | 4.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD5001AALS-00E3A0 500GB     | 1        | 1      | 50%     |
| Seagate ST250DM000-1BD141 250GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 329      | 673    | 61.38%  |
| Detected | 145      | 320    | 27.05%  |
| Malfunc  | 60       | 91     | 11.19%  |
| Failed   | 2        | 2      | 0.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 325      | 47.72%  |
| AMD                          | 127      | 18.65%  |
| Samsung Electronics          | 44       | 6.46%   |
| MAXIO Technology (Hangzhou)  | 24       | 3.52%   |
| Phison Electronics           | 21       | 3.08%   |
| Kingston Technology Company  | 20       | 2.94%   |
| Silicon Motion               | 18       | 2.64%   |
| Nvidia                       | 13       | 1.91%   |
| JMicron Technology           | 13       | 1.91%   |
| ASMedia Technology           | 10       | 1.47%   |
| ADATA Technology             | 9        | 1.32%   |
| SanDisk                      | 8        | 1.17%   |
| Realtek Semiconductor        | 6        | 0.88%   |
| Micron/Crucial Technology    | 6        | 0.88%   |
| Marvell Technology Group     | 6        | 0.88%   |
| Netac Technology             | 5        | 0.73%   |
| Broadcom / LSI               | 5        | 0.73%   |
| MCST                         | 4        | 0.59%   |
| Micron Technology            | 3        | 0.44%   |
| YEESTOR Microelectronics     | 2        | 0.29%   |
| Loongson Technology          | 2        | 0.29%   |
| Hosin Global Electronics     | 2        | 0.29%   |
| Zhaoxin                      | 1        | 0.15%   |
| VIA Technologies             | 1        | 0.15%   |
| Transcend                    | 1        | 0.15%   |
| Toshiba America Info Systems | 1        | 0.15%   |
| SK hynix                     | 1        | 0.15%   |
| OCZ Technology Group         | 1        | 0.15%   |
| LSI Logic / Symbios Logic    | 1        | 0.15%   |
| INNOGRIT                     | 1        | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 78       | 9.74%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 62       | 7.74%   |
| AMD 400 Series Chipset SATA Controller                                                  | 35       | 4.37%   |
| AMD 500 Series Chipset SATA Controller                                                  | 31       | 3.87%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 28       | 3.5%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 21       | 2.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 20       | 2.5%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 19       | 2.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 18       | 2.25%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 16       | 2%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 2%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 1.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 1.62%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 12       | 1.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 12       | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 1.5%    |
| AMD 600 Series Chipset SATA Controller                                                  | 11       | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 1.25%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 10       | 1.25%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 9        | 1.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9        | 1.12%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 8        | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 1%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 1%      |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 8        | 1%      |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 7        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7        | 0.87%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6        | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 0.75%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 0.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 0.75%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 0.75%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 6        | 0.75%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 6        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 0.75%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 0.62%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 409      | 61.69%  |
| NVMe | 157      | 23.68%  |
| IDE  | 82       | 12.37%  |
| RAID | 9        | 1.36%   |
| SAS  | 5        | 0.75%   |
| SCSI | 1        | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 328      | 68.76%  |
| AMD          | 141      | 29.56%  |
| Loongson     | 2        | 0.42%   |
| Elbrus-MCST  | 2        | 0.42%   |
| EL2S4        | 1        | 0.21%   |
| E8C/EATX     | 1        | 0.21%   |
| E8C-SWTX     | 1        | 0.21%   |
| CentaurHauls | 1        | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-6100TE CPU @ 2.70GHz          | 46       | 9.6%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 14       | 2.92%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 11       | 2.3%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 10       | 2.09%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 9        | 1.88%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 8        | 1.67%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 8        | 1.67%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 7        | 1.46%   |
| Intel 12th Gen Core i5-12400                | 7        | 1.46%   |
| AMD Ryzen 5 5600 6-Core Processor           | 7        | 1.46%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 6        | 1.25%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 6        | 1.25%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 1.04%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 5        | 1.04%   |
| Intel Core 2 CPU 6420 @ 2.13GHz             | 5        | 1.04%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 5        | 1.04%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GHz          | 4        | 0.84%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4        | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4        | 0.84%   |
| Intel 12th Gen Core i3-12100                | 4        | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4        | 0.84%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 4        | 0.84%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 0.84%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 0.84%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.63%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 0.63%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.63%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 0.63%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 0.63%   |
| Intel Celeron CPU G3900 @ 2.80GHz           | 3        | 0.63%   |
| Intel 12th Gen Core i3-12100F               | 3        | 0.63%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 3        | 0.63%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 3        | 0.63%   |
| Loongson Loongson 3A                        | 2        | 0.42%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 2        | 0.42%   |
| Intel Pentium Gold G7400                    | 2        | 0.42%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 2        | 0.42%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 2        | 0.42%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 0.42%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 2        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 100      | 20.92%  |
| AMD Ryzen 5             | 56       | 11.72%  |
| Intel Core i5           | 53       | 11.09%  |
| Other                   | 45       | 9.41%   |
| Intel Xeon              | 26       | 5.44%   |
| AMD Ryzen 7             | 24       | 5.02%   |
| Intel Core i7           | 23       | 4.81%   |
| Intel Celeron           | 20       | 4.18%   |
| Intel Pentium           | 18       | 3.77%   |
| Intel Core 2 Duo        | 9        | 1.88%   |
| Intel Pentium Gold      | 8        | 1.67%   |
| Intel Pentium Dual-Core | 8        | 1.67%   |
| AMD Ryzen 9             | 8        | 1.67%   |
| Intel Core 2            | 7        | 1.46%   |
| Intel Core 2 Quad       | 6        | 1.26%   |
| AMD Ryzen 3             | 6        | 1.26%   |
| AMD FX                  | 6        | 1.26%   |
| AMD Phenom II X4        | 5        | 1.05%   |
| AMD A10                 | 5        | 1.05%   |
| Intel Genuine           | 4        | 0.84%   |
| Intel Core i9           | 4        | 0.84%   |
| AMD Athlon 64 X2        | 4        | 0.84%   |
| AMD Athlon              | 4        | 0.84%   |
| AMD Athlon II X4        | 3        | 0.63%   |
| AMD Athlon II X2        | 3        | 0.63%   |
| AMD A8                  | 3        | 0.63%   |
| AMD A6                  | 3        | 0.63%   |
| Intel Atom              | 2        | 0.42%   |
| AMD Ryzen 5 PRO         | 2        | 0.42%   |
| AMD Athlon X4           | 2        | 0.42%   |
| Intel Pentium D         | 1        | 0.21%   |
| Intel Pentium 4         | 1        | 0.21%   |
| Intel Celeron D         | 1        | 0.21%   |
| AMD Sempron             | 1        | 0.21%   |
| AMD Ryzen 7 PRO         | 1        | 0.21%   |
| AMD Ryzen 3 PRO         | 1        | 0.21%   |
| AMD Phenom II X6        | 1        | 0.21%   |
| AMD E1                  | 1        | 0.21%   |
| AMD Athlon X2           | 1        | 0.21%   |
| AMD Athlon 64           | 1        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 165      | 34.45%  |
| 4      | 141      | 29.44%  |
| 6      | 87       | 18.16%  |
| 8      | 41       | 8.56%   |
| 12     | 13       | 2.71%   |
| 16     | 10       | 2.09%   |
| 1      | 7        | 1.46%   |
| 14     | 6        | 1.25%   |
| 10     | 3        | 0.63%   |
| 3      | 3        | 0.63%   |
| 18     | 2        | 0.42%   |
| 32     | 1        | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 469      | 98.32%  |
| 2      | 6        | 1.26%   |
| 4      | 2        | 0.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 321      | 67.15%  |
| 1      | 157      | 32.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 470      | 98.53%  |
| Unknown        | 5        | 1.05%   |
| 64-bit         | 1        | 0.21%   |
| 32-bit         | 1        | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 222      | 45.4%   |
| 0x506e3    | 54       | 11.04%  |
| 0x1067a    | 17       | 3.48%   |
| 0x906e9    | 14       | 2.86%   |
| 0x08001138 | 14       | 2.86%   |
| 0xa0653    | 11       | 2.25%   |
| 0x906eb    | 11       | 2.25%   |
| 0x306c3    | 11       | 2.25%   |
| 0x0a50000c | 9        | 1.84%   |
| 0x306a9    | 8        | 1.64%   |
| 0x08108109 | 8        | 1.64%   |
| 0xa0671    | 7        | 1.43%   |
| 0x906ea    | 7        | 1.43%   |
| 0x806c1    | 4        | 0.82%   |
| 0x206d7    | 4        | 0.82%   |
| 0x0a50000d | 4        | 0.82%   |
| 0x0a20120a | 4        | 0.82%   |
| 0x06001119 | 4        | 0.82%   |
| 0x806e9    | 3        | 0.61%   |
| 0x206a7    | 3        | 0.61%   |
| 0x08701021 | 3        | 0.61%   |
| 0x0800820d | 3        | 0.61%   |
| 0xa0655    | 2        | 0.41%   |
| 0x906ed    | 2        | 0.41%   |
| 0x90675    | 2        | 0.41%   |
| 0x90672    | 2        | 0.41%   |
| 0x806ec    | 2        | 0.41%   |
| 0x6f6      | 2        | 0.41%   |
| 0x306e4    | 2        | 0.41%   |
| 0x30679    | 2        | 0.41%   |
| 0x20655    | 2        | 0.41%   |
| 0x0a601206 | 2        | 0.41%   |
| 0x0a20120e | 2        | 0.41%   |
| 0x08108102 | 2        | 0.41%   |
| 0x08001129 | 2        | 0.41%   |
| 0x06003106 | 2        | 0.41%   |
| 0x06000852 | 2        | 0.41%   |
| 0x010000db | 2        | 0.41%   |
| 0x010000c8 | 2        | 0.41%   |
| 0x00000000 | 2        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Skylake          | 66       | 13.78%  |
| KabyLake         | 56       | 11.69%  |
| Unknown          | 42       | 8.77%   |
| Zen 3            | 34       | 7.1%    |
| CometLake        | 33       | 6.89%   |
| Haswell          | 26       | 5.43%   |
| SandyBridge      | 23       | 4.8%    |
| IvyBridge        | 23       | 4.8%    |
| Zen+             | 21       | 4.38%   |
| Penryn           | 21       | 4.38%   |
| Zen              | 19       | 3.97%   |
| Alderlake Hybrid | 15       | 3.13%   |
| Zen 2            | 13       | 2.71%   |
| K10              | 13       | 2.71%   |
| Piledriver       | 11       | 2.3%    |
| Core             | 11       | 2.3%    |
| K8 Hammer        | 6        | 1.25%   |
| Westmere         | 5        | 1.04%   |
| Steamroller      | 5        | 1.04%   |
| Silvermont       | 5        | 1.04%   |
| Icelake          | 5        | 1.04%   |
| TigerLake        | 4        | 0.84%   |
| Nehalem          | 4        | 0.84%   |
| NetBurst         | 3        | 0.63%   |
| Goldmont         | 3        | 0.63%   |
| Broadwell        | 3        | 0.63%   |
| Goldmont plus    | 2        | 0.42%   |
| Bulldozer        | 2        | 0.42%   |
| Puma             | 1        | 0.21%   |
| K10 Llano        | 1        | 0.21%   |
| Jaguar           | 1        | 0.21%   |
| Excavator        | 1        | 0.21%   |
| Bonnell          | 1        | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 209      | 41.14%  |
| Nvidia                     | 147      | 28.94%  |
| AMD                        | 139      | 27.36%  |
| Matrox Electronics Systems | 4        | 0.79%   |
| Silicon Motion             | 3        | 0.59%   |
| ASPEED Technology          | 3        | 0.59%   |
| Zhaoxin                    | 1        | 0.2%    |
| MCST                       | 1        | 0.2%    |
| Loongson Technology        | 1        | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 55       | 10.58%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 23       | 4.42%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 23       | 4.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 18       | 3.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15       | 2.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 15       | 2.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 11       | 2.12%   |
| Intel Kaby Lake-S GT1 [HD Graphics 610]                                     | 10       | 1.92%   |
| Nvidia GT218 [GeForce 210]                                                  | 9        | 1.73%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 9        | 1.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 1.73%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 8        | 1.54%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 1.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 1.35%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6        | 1.15%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 0.96%   |
| Intel Skylake-S GT1 [HD Graphics 510]                                       | 5        | 0.96%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 5        | 0.96%   |
| AMD Raphael                                                                 | 5        | 0.96%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 5        | 0.96%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 0.77%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 0.77%   |
| Nvidia GF108 [GeForce GT 730]                                               | 4        | 0.77%   |
| Matrox Electronics Systems MGA G200EH                                       | 4        | 0.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4        | 0.77%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                     | 4        | 0.77%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 4        | 0.77%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 4        | 0.77%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 0.77%   |
| Silicon Motion SM718 LynxSE+                                                | 3        | 0.58%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.58%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 0.58%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 0.58%   |
| Nvidia GK107 [GeForce GT 640]                                               | 3        | 0.58%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.58%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 0.58%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 189      | 39.13%  |
| 1 x Nvidia              | 132      | 27.33%  |
| 1 x AMD                 | 123      | 25.47%  |
| Intel + Nvidia          | 8        | 1.66%   |
| 2 x AMD                 | 7        | 1.45%   |
| AMD + Nvidia            | 5        | 1.04%   |
| 1 x Matrox              | 4        | 0.83%   |
| 1 x Silicon Motion      | 3        | 0.62%   |
| Intel + AMD             | 3        | 0.62%   |
| 1 x ASPEED              | 3        | 0.62%   |
| Other                   | 2        | 0.41%   |
| 2 x Nvidia              | 1        | 0.21%   |
| Nvidia + Zhaoxin        | 1        | 0.21%   |
| 1 x MCST                | 1        | 0.21%   |
| 1 x Loongson Technology | 1        | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 356      | 73.55%  |
| Proprietary | 98       | 20.25%  |
| Unknown     | 30       | 6.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 288      | 58.78%  |
| 3.01-4.0   | 41       | 8.37%   |
| 0.01-0.5   | 37       | 7.55%   |
| 0.51-1.0   | 36       | 7.35%   |
| 1.01-2.0   | 34       | 6.94%   |
| 7.01-8.0   | 27       | 5.51%   |
| 8.01-16.0  | 16       | 3.27%   |
| 5.01-6.0   | 8        | 1.63%   |
| 2.01-3.0   | 3        | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 70       | 14%     |
| Acer                 | 50       | 10%     |
| HHT                  | 47       | 9.4%    |
| BenQ                 | 44       | 8.8%    |
| Goldstar             | 33       | 6.6%    |
| Philips              | 32       | 6.4%    |
| AOC                  | 32       | 6.4%    |
| Dell                 | 26       | 5.2%    |
| ViewSonic            | 19       | 3.8%    |
| MSI                  | 12       | 2.4%    |
| Hewlett-Packard      | 11       | 2.2%    |
| Mi                   | 9        | 1.8%    |
| ASUSTek Computer     | 9        | 1.8%    |
| Ancor Communications | 8        | 1.6%    |
| Iiyama               | 6        | 1.2%    |
| RTK                  | 5        | 1%      |
| NEC Computers        | 5        | 1%      |
| Unknown              | 4        | 0.8%    |
| PRW                  | 4        | 0.8%    |
| Lenovo               | 4        | 0.8%    |
| WBT                  | 3        | 0.6%    |
| SKG                  | 3        | 0.6%    |
| LG Electronics       | 3        | 0.6%    |
| VIE                  | 2        | 0.4%    |
| STD                  | 2        | 0.4%    |
| Sony                 | 2        | 0.4%    |
| SKM                  | 2        | 0.4%    |
| SGT                  | 2        | 0.4%    |
| Pixio                | 2        | 0.4%    |
| KVT                  | 2        | 0.4%    |
| ITE                  | 2        | 0.4%    |
| IPS                  | 2        | 0.4%    |
| HVR                  | 2        | 0.4%    |
| HUAWEI               | 2        | 0.4%    |
| Hitachi              | 2        | 0.4%    |
| Denver               | 2        | 0.4%    |
| CTV                  | 2        | 0.4%    |
| Aosiman              | 2        | 0.4%    |
| AGO                  | 2        | 0.4%    |
| Unknown              | 2        | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch               | 47       | 9.16%   |
| AOC LCD Monitor 2778X 2560x1440                                       | 11       | 2.14%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                     | 10       | 1.95%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 7        | 1.36%   |
| Dell E2417H DELA0E2 1920x1080 527x296mm 23.8-inch                     | 5        | 0.97%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 5        | 0.97%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 4        | 0.78%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 4        | 0.78%   |
| RTK HDMI RTK2380 1920x1080 530x290mm 23.8-inch                        | 4        | 0.78%   |
| PRW AP7_Titanium PRW4200 3840x2160                                    | 4        | 0.78%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 4        | 0.78%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 4        | 0.78%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 4        | 0.78%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                      | 3        | 0.58%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 3        | 0.58%   |
| NEC Computers EA244WMi NEC68D4 1920x1200 519x324mm 24.1-inch          | 3        | 0.58%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 3        | 0.58%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 3        | 0.58%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                      | 3        | 0.58%   |
| AOC 22B15HN AOC2201 1920x1080 478x260mm 21.4-inch                     | 3        | 0.58%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 2        | 0.39%   |
| STD LED STD0001 1920x1080 480x260mm 21.5-inch                         | 2        | 0.39%   |
| SKM T24 Air SKM9322 1920x1080 519x324mm 24.1-inch                     | 2        | 0.39%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 2        | 0.39%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 2        | 0.39%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 2        | 0.39%   |
| Samsung Electronics SyncMaster SAM01CF 1600x1200 432x324mm 21.3-inch  | 2        | 0.39%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch    | 2        | 0.39%   |
| Samsung Electronics S22E391 SAM0C0E 1920x1080 477x268mm 21.5-inch     | 2        | 0.39%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch     | 2        | 0.39%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 2        | 0.39%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 0.39%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 2        | 0.39%   |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                    | 2        | 0.39%   |
| Philips 150S PHL0829 1024x768 307x230mm 15.1-inch                     | 2        | 0.39%   |
| MSI MP241X MSI3BA9 1920x1080 527x296mm 23.8-inch                      | 2        | 0.39%   |
| MSI G281UV MSI4CC8 3840x2160 621x341mm 27.9-inch                      | 2        | 0.39%   |
| KVT M24 KVT0002 1920x1080 530x290mm 23.8-inch                         | 2        | 0.39%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 2        | 0.39%   |
| HUAWEI SSN-24 HWV6E4E 1920x1080 527x296mm 23.8-inch                   | 2        | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 237      | 48.97%  |
| 3840x2160 (4K)     | 78       | 16.12%  |
| 2560x1440 (QHD)    | 45       | 9.3%    |
| 1280x1024 (SXGA)   | 33       | 6.82%   |
| 1680x1050 (WSXGA+) | 18       | 3.72%   |
| 1440x900 (WXGA+)   | 10       | 2.07%   |
| 1366x768 (WXGA)    | 9        | 1.86%   |
| 1600x900 (HD+)     | 8        | 1.65%   |
| 1920x1200 (WUXGA)  | 7        | 1.45%   |
| 3440x1440          | 5        | 1.03%   |
| Unknown            | 5        | 1.03%   |
| 2288x1287          | 4        | 0.83%   |
| 1360x768           | 4        | 0.83%   |
| 2560x1080          | 3        | 0.62%   |
| 1600x1200          | 3        | 0.62%   |
| 1280x720 (HD)      | 3        | 0.62%   |
| 1024x768 (XGA)     | 3        | 0.62%   |
| 3840x1080          | 2        | 0.41%   |
| 2160x1200          | 2        | 0.41%   |
| 4480x1440          | 1        | 0.21%   |
| 3840x1600          | 1        | 0.21%   |
| 3840x1440          | 1        | 0.21%   |
| 1920x540           | 1        | 0.21%   |
| 1280x960           | 1        | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 87       | 17.54%  |
| 23      | 71       | 14.31%  |
| 27      | 60       | 12.1%   |
| 21      | 55       | 11.09%  |
| 40      | 50       | 10.08%  |
| Unknown | 35       | 7.06%   |
| 19      | 25       | 5.04%   |
| 17      | 21       | 4.23%   |
| 31      | 14       | 2.82%   |
| 22      | 12       | 2.42%   |
| 18      | 11       | 2.22%   |
| 32      | 7        | 1.41%   |
| 34      | 6        | 1.21%   |
| 20      | 6        | 1.21%   |
| 15      | 5        | 1.01%   |
| 142     | 4        | 0.81%   |
| 72      | 3        | 0.6%    |
| 54      | 3        | 0.6%    |
| 28      | 3        | 0.6%    |
| 26      | 3        | 0.6%    |
| 49      | 2        | 0.4%    |
| 14      | 2        | 0.4%    |
| 85      | 1        | 0.2%    |
| 84      | 1        | 0.2%    |
| 57      | 1        | 0.2%    |
| 52      | 1        | 0.2%    |
| 46      | 1        | 0.2%    |
| 39      | 1        | 0.2%    |
| 37      | 1        | 0.2%    |
| 33      | 1        | 0.2%    |
| 29      | 1        | 0.2%    |
| 25      | 1        | 0.2%    |
| 12      | 1        | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 208      | 42.98%  |
| 401-500        | 94       | 19.42%  |
| 901-1000       | 48       | 9.92%   |
| Unknown        | 35       | 7.23%   |
| 301-350        | 26       | 5.37%   |
| 601-700        | 23       | 4.75%   |
| 701-800        | 14       | 2.89%   |
| 351-400        | 12       | 2.48%   |
| 1001-1500      | 7        | 1.45%   |
| 801-900        | 5        | 1.03%   |
| 1501-2000      | 5        | 1.03%   |
| More than 2000 | 4        | 0.83%   |
| 201-300        | 3        | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 287      | 62.39%  |
| 21/9    | 56       | 12.17%  |
| 16/10   | 39       | 8.48%   |
| 5/4     | 33       | 7.17%   |
| Unknown | 27       | 5.87%   |
| 4/3     | 10       | 2.17%   |
| 1.00    | 4        | 0.87%   |
| 32/9    | 2        | 0.43%   |
| 3/2     | 1        | 0.22%   |
| 0.56    | 1        | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 187      | 38.8%   |
| 301-350        | 63       | 13.07%  |
| 501-1000       | 55       | 11.41%  |
| 151-200        | 43       | 8.92%   |
| Unknown        | 35       | 7.26%   |
| 351-500        | 31       | 6.43%   |
| 141-150        | 27       | 5.6%    |
| 251-300        | 19       | 3.94%   |
| More than 1000 | 14       | 2.9%    |
| 101-110        | 6        | 1.24%   |
| 71-80          | 1        | 0.21%   |
| 91-100         | 1        | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 269      | 57.48%  |
| 101-120 | 124      | 26.5%   |
| Unknown | 35       | 7.48%   |
| 121-160 | 19       | 4.06%   |
| 1-50    | 17       | 3.63%   |
| 161-240 | 4        | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 402      | 82.89%  |
| 2     | 56       | 11.55%  |
| 0     | 22       | 4.54%   |
| 3     | 4        | 0.82%   |
| 4     | 1        | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 363      | 57.99%  |
| Intel                                  | 158      | 25.24%  |
| Qualcomm Atheros                       | 21       | 3.35%   |
| Nvidia                                 | 10       | 1.6%    |
| Ralink Technology                      | 9        | 1.44%   |
| TP-Link                                | 8        | 1.28%   |
| Ralink                                 | 7        | 1.12%   |
| Marvell Technology Group               | 7        | 1.12%   |
| MediaTek                               | 6        | 0.96%   |
| MCST                                   | 4        | 0.64%   |
| VIA Technologies                       | 3        | 0.48%   |
| Microchip Technology                   | 3        | 0.48%   |
| Huawei Technologies                    | 3        | 0.48%   |
| Broadcom Limited                       | 3        | 0.48%   |
| U-Blox                                 | 2        | 0.32%   |
| Mercucys                               | 2        | 0.32%   |
| Loongson Technology                    | 2        | 0.32%   |
| D-Link System                          | 2        | 0.32%   |
| ASUSTek Computer                       | 2        | 0.32%   |
| ZTopInc                                | 1        | 0.16%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.16%   |
| Xiaomi                                 | 1        | 0.16%   |
| Vimtron Electronics                    | 1        | 0.16%   |
| T & A Mobile Phones                    | 1        | 0.16%   |
| Suzhou Motorcomm Electronic Technology | 1        | 0.16%   |
| STMicroelectronics                     | 1        | 0.16%   |
| Microsoft                              | 1        | 0.16%   |
| LG Electronics                         | 1        | 0.16%   |
| D-Link                                 | 1        | 0.16%   |
| Broadcom                               | 1        | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 263      | 37.57%  |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 48       | 6.86%   |
| Intel Ethernet Connection I219-LM                                      | 35       | 5%      |
| Realtek RTL8125 2.5GbE Controller                                      | 30       | 4.29%   |
| Intel Ethernet Connection (2) I219-LM                                  | 18       | 2.57%   |
| Intel Ethernet Connection (14) I219-V                                  | 15       | 2.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 7        | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7        | 1%      |
| Intel Wireless 3165                                                    | 7        | 1%      |
| Intel I211 Gigabit Network Connection                                  | 7        | 1%      |
| Realtek 802.11ac NIC                                                   | 6        | 0.86%   |
| Intel Ethernet Controller I225-V                                       | 6        | 0.86%   |
| Intel Ethernet Connection (7) I219-V                                   | 6        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                                   | 6        | 0.86%   |
| Intel Ethernet Connection (17) I219-V                                  | 6        | 0.86%   |
| Ralink MT7601U Wireless Adapter                                        | 5        | 0.71%   |
| Intel I350 Gigabit Network Connection                                  | 5        | 0.71%   |
| Intel 82574L Gigabit Network Connection                                | 5        | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4        | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 4        | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4        | 0.57%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                   | 4        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4        | 0.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 4        | 0.57%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 4        | 0.57%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4        | 0.57%   |
| Intel Wi-Fi 6 AX200                                                    | 4        | 0.57%   |
| Intel Ethernet Connection (13) I219-V                                  | 4        | 0.57%   |
| Intel 700 Series Chipset CNVi WiFi                                     | 4        | 0.57%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 3        | 0.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3        | 0.43%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 3        | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3        | 0.43%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3        | 0.43%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 3        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3        | 0.43%   |
| Nvidia MCP77 Ethernet                                                  | 3        | 0.43%   |
| Microchip MCP2221 USB-I2C/UART Combo                                   | 3        | 0.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 3        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 42       | 33.6%   |
| Realtek Semiconductor | 38       | 30.4%   |
| Ralink Technology     | 9        | 7.2%    |
| TP-Link               | 8        | 6.4%    |
| Ralink                | 7        | 5.6%    |
| MediaTek              | 6        | 4.8%    |
| Qualcomm Atheros      | 5        | 4%      |
| Mercucys              | 2        | 1.6%    |
| Broadcom Limited      | 2        | 1.6%    |
| ASUSTek Computer      | 2        | 1.6%    |
| ZTopInc               | 1        | 0.8%    |
| Microsoft             | 1        | 0.8%    |
| LG Electronics        | 1        | 0.8%    |
| D-Link System         | 1        | 0.8%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 7        | 5.56%   |
| Intel Wireless 3165                                                  | 7        | 5.56%   |
| Realtek 802.11ac NIC                                                 | 6        | 4.76%   |
| Ralink MT7601U Wireless Adapter                                      | 5        | 3.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4        | 3.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 4        | 3.17%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 4        | 3.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 4        | 3.17%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 4        | 3.17%   |
| Intel Wi-Fi 6 AX200                                                  | 4        | 3.17%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 4        | 3.17%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 3        | 2.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 3        | 2.38%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 3        | 2.38%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 3        | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3        | 2.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3        | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3        | 2.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 1.59%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 2        | 1.59%   |
| Ralink RT5370 Wireless Adapter                                       | 2        | 1.59%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 2        | 1.59%   |
| Mercucys 802.11n NIC                                                 | 2        | 1.59%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2        | 1.59%   |
| Intel Wireless 7265                                                  | 2        | 1.59%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2        | 1.59%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2        | 1.59%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2        | 1.59%   |
| ZTopInc 802.11n NIC                                                  | 1        | 0.79%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                | 1        | 0.79%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 1        | 0.79%   |
| TP-Link 802.11n NIC                                                  | 1        | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1        | 0.79%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1        | 0.79%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 0.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1        | 0.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 0.79%   |
| Realtek 802.11ax WLAN Adapter                                        | 1        | 0.79%   |
| Ralink RT5572 Wireless Adapter                                       | 1        | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 357      | 65.5%   |
| Intel                                  | 136      | 24.95%  |
| Qualcomm Atheros                       | 16       | 2.94%   |
| Nvidia                                 | 10       | 1.83%   |
| Marvell Technology Group               | 7        | 1.28%   |
| MCST                                   | 4        | 0.73%   |
| VIA Technologies                       | 3        | 0.55%   |
| Loongson Technology                    | 2        | 0.37%   |
| Huawei Technologies                    | 2        | 0.37%   |
| Xiaomi                                 | 1        | 0.18%   |
| Vimtron Electronics                    | 1        | 0.18%   |
| TP-Link                                | 1        | 0.18%   |
| Suzhou Motorcomm Electronic Technology | 1        | 0.18%   |
| D-Link System                          | 1        | 0.18%   |
| D-Link                                 | 1        | 0.18%   |
| Broadcom Limited                       | 1        | 0.18%   |
| Broadcom                               | 1        | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 263      | 46.63%  |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 48       | 8.51%   |
| Intel Ethernet Connection I219-LM                                      | 35       | 6.21%   |
| Realtek RTL8125 2.5GbE Controller                                      | 30       | 5.32%   |
| Intel Ethernet Connection (2) I219-LM                                  | 18       | 3.19%   |
| Intel Ethernet Connection (14) I219-V                                  | 15       | 2.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7        | 1.24%   |
| Intel I211 Gigabit Network Connection                                  | 7        | 1.24%   |
| Intel Ethernet Controller I225-V                                       | 6        | 1.06%   |
| Intel Ethernet Connection (7) I219-V                                   | 6        | 1.06%   |
| Intel Ethernet Connection (2) I219-V                                   | 6        | 1.06%   |
| Intel Ethernet Connection (17) I219-V                                  | 6        | 1.06%   |
| Intel I350 Gigabit Network Connection                                  | 5        | 0.89%   |
| Intel 82574L Gigabit Network Connection                                | 5        | 0.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4        | 0.71%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 4        | 0.71%   |
| Intel Ethernet Connection (13) I219-V                                  | 4        | 0.71%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3        | 0.53%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 3        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3        | 0.53%   |
| Nvidia MCP77 Ethernet                                                  | 3        | 0.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 3        | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 3        | 0.53%   |
| Intel Ethernet Connection I217-V                                       | 3        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 0.53%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 2        | 0.35%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2        | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 0.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 0.35%   |
| Nvidia MCP55 Ethernet                                                  | 2        | 0.35%   |
| Nvidia MCP51 Ethernet Controller                                       | 2        | 0.35%   |
| MCST Gigabit Ethernet MAC controller                                   | 2        | 0.35%   |
| MCST Gigabit Ethernet Controller                                       | 2        | 0.35%   |
| Loongson 2K2000 / 7A2000 Chipset Gigabit Ethernet Controller           | 2        | 0.35%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 0.35%   |
| Intel Ethernet Controller I226-V                                       | 2        | 0.35%   |
| Intel Ethernet Connection (17) I219-LM                                 | 2        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 473      | 78.18%  |
| WiFi     | 122      | 20.17%  |
| Modem    | 9        | 1.49%   |
| Unknown  | 1        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 415      | 86.28%  |
| WiFi     | 66       | 13.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 366      | 76.57%  |
| 2     | 95       | 19.87%  |
| 3     | 10       | 2.09%   |
| 4     | 3        | 0.63%   |
| 0     | 2        | 0.42%   |
| 13    | 1        | 0.21%   |
| 8     | 1        | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 460      | 95.83%  |
| Yes  | 20       | 4.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 40       | 37.38%  |
| Cambridge Silicon Radio  | 23       | 21.5%   |
| Realtek Semiconductor    | 16       | 14.95%  |
| MediaTek                 | 5        | 4.67%   |
| IMC Networks             | 5        | 4.67%   |
| ASUSTek Computer         | 5        | 4.67%   |
| TP-Link                  | 2        | 1.87%   |
| HTC (High Tech Computer) | 2        | 1.87%   |
| Broadcom                 | 2        | 1.87%   |
| Apple                    | 2        | 1.87%   |
| Actions                  | 2        | 1.87%   |
| Realtek                  | 1        | 0.93%   |
| Logitech                 | 1        | 0.93%   |
| Unknown                  | 1        | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 23       | 21.5%   |
| Realtek Bluetooth Radio                                              | 14       | 13.08%  |
| Intel Bluetooth wireless interface                                   | 13       | 12.15%  |
| MediaTek Wireless_Device                                             | 5        | 4.67%   |
| Intel Bluetooth Device                                               | 5        | 4.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 5        | 4.67%   |
| Intel AX201 Bluetooth                                                | 4        | 3.74%   |
| Intel AX200 Bluetooth                                                | 4        | 3.74%   |
| ASUS 2045 Bluetooth 2.0 Device with trace filter                     | 4        | 3.74%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 2.8%    |
| Intel AX210 Bluetooth                                                | 3        | 2.8%    |
| IMC Networks Bluetooth Radio                                         | 3        | 2.8%    |
| TP-Link TP-T@- UB500 Adapter                                         | 2        | 1.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 1.87%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 1.87%   |
| Apple Bluetooth Host Controller                                      | 2        | 1.87%   |
| Actions general adapter                                              | 2        | 1.87%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.93%   |
| Realtek Bluetooth 5.4 Radio                                          | 1        | 0.93%   |
| Realtek Bluetooth Radio                                              | 1        | 0.93%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 1        | 0.93%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.93%   |
| IMC Networks Wireless_Device                                         | 1        | 0.93%   |
| IMC Networks Bluetooth Device                                        | 1        | 0.93%   |
| Broadcom Bluetooth dongle                                            | 1        | 0.93%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 0.93%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.93%   |
| Unknown                                                              | 1        | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 316      | 44.51%  |
| AMD                      | 176      | 24.79%  |
| Nvidia                   | 139      | 19.58%  |
| JMTek                    | 10       | 1.41%   |
| C-Media Electronics      | 10       | 1.41%   |
| Creative Technology      | 7        | 0.99%   |
| Creative Labs            | 5        | 0.7%    |
| MCST                     | 4        | 0.56%   |
| Logitech                 | 3        | 0.42%   |
| fifine Microphones       | 3        | 0.42%   |
| Unknown                  | 3        | 0.42%   |
| Loongson Technology      | 2        | 0.28%   |
| ASUSTek Computer         | 2        | 0.28%   |
| A4Tech                   | 2        | 0.28%   |
| Zhaoxin                  | 1        | 0.14%   |
| Yamaha                   | 1        | 0.14%   |
| VIA Technologies         | 1        | 0.14%   |
| Texas Instruments        | 1        | 0.14%   |
| Tenx Technology          | 1        | 0.14%   |
| Sony                     | 1        | 0.14%   |
| Razer USA                | 1        | 0.14%   |
| Plantronics              | 1        | 0.14%   |
| Onkyo                    | 1        | 0.14%   |
| MV-SILICON               | 1        | 0.14%   |
| Micro Star International | 1        | 0.14%   |
| KTMicro                  | 1        | 0.14%   |
| Jieli Technology         | 1        | 0.14%   |
| Huawei Technologies      | 1        | 0.14%   |
| Hewlett-Packard          | 1        | 0.14%   |
| Goldvish                 | 1        | 0.14%   |
| GN Netcom                | 1        | 0.14%   |
| Giga-Byte Technology     | 1        | 0.14%   |
| Generalplus Technology   | 1        | 0.14%   |
| Focusrite-Novation       | 1        | 0.14%   |
| Evolution Electronics    | 1        | 0.14%   |
| ESI Audiotechnik         | 1        | 0.14%   |
| EasyPass Industrial      | 1        | 0.14%   |
| DSEA A/S                 | 1        | 0.14%   |
| Comtrue                  | 1        | 0.14%   |
| Cirrus Logic             | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 78       | 9.54%   |
| AMD Ryzen HD Audio Controller                                              | 46       | 5.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 27       | 3.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 27       | 3.3%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 25       | 3.06%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 22       | 2.69%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 20       | 2.44%   |
| Intel 200 Series PCH HD Audio                                              | 20       | 2.44%   |
| Intel Alder Lake-S HD Audio Controller                                     | 19       | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19       | 2.32%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 19       | 2.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 19       | 2.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18       | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17       | 2.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 15       | 1.83%   |
| AMD FCH Azalia Controller                                                  | 15       | 1.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14       | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 13       | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13       | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12       | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 10       | 1.22%   |
| Nvidia High Definition Audio Controller                                    | 10       | 1.22%   |
| Nvidia GF108 High Definition Audio Controller                              | 10       | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 1.1%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 8        | 0.98%   |
| Intel Raptor Lake High Definition Audio Controller                         | 8        | 0.98%   |
| Intel Comet Lake PCH-V cAVS                                                | 8        | 0.98%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 8        | 0.98%   |
| AMD Radeon High Definition Audio Controller                                | 8        | 0.98%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 0.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 0.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 7        | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6        | 0.73%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6        | 0.73%   |
| Intel Sunrise Point-LP HD Audio                                            | 6        | 0.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 0.61%   |
| Nvidia GA106 High Definition Audio Controller                              | 5        | 0.61%   |
| Intel Comet Lake PCH cAVS                                                  | 5        | 0.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 62       | 18.02%  |
| Crucial                      | 45       | 13.08%  |
| Unknown                      | 43       | 12.5%   |
| Samsung Electronics          | 30       | 8.72%   |
| Micron Technology            | 17       | 4.94%   |
| SK hynix                     | 16       | 4.65%   |
| Apacer                       | 14       | 4.07%   |
| AMD                          | 12       | 3.49%   |
| Unknown                      | 12       | 3.49%   |
| Patriot                      | 11       | 3.2%    |
| A-DATA Technology            | 9        | 2.62%   |
| G.Skill                      | 8        | 2.33%   |
| Corsair                      | 8        | 2.33%   |
| Foxline                      | 7        | 2.03%   |
| KingSpec                     | 5        | 1.45%   |
| Goodram                      | 5        | 1.45%   |
| Unknown (0B7A)               | 4        | 1.16%   |
| Hewlett-Packard              | 4        | 1.16%   |
| Ramaxel Technology           | 2        | 0.58%   |
| Qumo                         | 2        | 0.58%   |
| Netac                        | 2        | 0.58%   |
| Goldkey                      | 2        | 0.58%   |
| Elpida                       | 2        | 0.58%   |
| Wilk                         | 1        | 0.29%   |
| Unknown (ABCD)               | 1        | 0.29%   |
| Unknown (89F7)               | 1        | 0.29%   |
| Unknown (0x7FFF)             | 1        | 0.29%   |
| Unknown (0x0B7A)             | 1        | 0.29%   |
| Unknown (09D5)               | 1        | 0.29%   |
| Unknown (081A)               | 1        | 0.29%   |
| Transcend                    | 1        | 0.29%   |
| tigo                         | 1        | 0.29%   |
| Team                         | 1        | 0.29%   |
| Shenzhen Longsys             | 1        | 0.29%   |
| Shenzhen Jinge Information   | 1        | 0.29%   |
| Patriot Memory (PDP Systems) | 1        | 0.29%   |
| Patriot Memory               | 1        | 0.29%   |
| OCZ                          | 1        | 0.29%   |
| Nanya Technology             | 1        | 0.29%   |
| Kingmax                      | 1        | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2666MT/s           | 13       | 3.53%   |
| Unknown                                                        | 12       | 3.26%   |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s                       | 10       | 2.72%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 4        | 1.09%   |
| Unknown (0B7A) RAM UDIMM PC4-3200 16GB 16GB DIMM DDR4 3200MT/s | 4        | 1.09%   |
| Samsung RAM M378A1K43EB2-CVF 8GB DIMM DDR4 3266MT/s            | 4        | 1.09%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 4        | 1.09%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s         | 4        | 1.09%   |
| HP RAM Module 4GB DIMM DDR3 1333MT/s                           | 4        | 1.09%   |
| Apacer RAM D12.2755BS.001 16GB DIMM DDR4 3200MT/s              | 4        | 1.09%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 3        | 0.82%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s           | 3        | 0.82%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s            | 3        | 0.82%   |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s         | 3        | 0.82%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 2        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 2        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                       | 2        | 0.54%   |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 2        | 0.54%   |
| Unknown RAM Module 1024MB DIMM                                 | 2        | 0.54%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2        | 0.54%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s           | 2        | 0.54%   |
| Qumo RAM QUM4U-8G2666P19 8GB DIMM DDR4 2667MT/s                | 2        | 0.54%   |
| Patriot RAM PSD38G16002 8192MB DIMM DDR3 1600MT/s              | 2        | 0.54%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s             | 2        | 0.54%   |
| Kingston RAM KHX2666C16/8G 8GiB DIMM DDR4 3466MT/s             | 2        | 0.54%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s            | 2        | 0.54%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s          | 2        | 0.54%   |
| Kingston RAM KF3200C16D4/8GX 8GiB DIMM DDR4 3600MT/s           | 2        | 0.54%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s          | 2        | 0.54%   |
| Kingston RAM 9905713-017.A00G 4GB DIMM DDR4 2866MT/s           | 2        | 0.54%   |
| KingSpec RAM KS4800D5P11016G 16GB DIMM DDR5 4800MT/s           | 2        | 0.54%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s            | 2        | 0.54%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3600MT/s             | 2        | 0.54%   |
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s              | 2        | 0.54%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s            | 2        | 0.54%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s         | 2        | 0.54%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 2        | 0.54%   |
| Crucial RAM BL8G26C16U4R.8FD 8GB DIMM DDR4 3200MT/s            | 2        | 0.54%   |
| Apacer RAM D12.2756CS.001 8GB DIMM DDR4 3200MT/s               | 2        | 0.54%   |
| Apacer RAM D12.2324CC.001 8GB DIMM DDR4 2667MT/s               | 2        | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 183      | 58.65%  |
| DDR3    | 65       | 20.83%  |
| DDR5    | 24       | 7.69%   |
| Unknown | 18       | 5.77%   |
| DDR2    | 10       | 3.21%   |
| SDRAM   | 7        | 2.24%   |
| DDR     | 3        | 0.96%   |
| LPDDR4  | 1        | 0.32%   |
| DRAM    | 1        | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 282      | 90.68%  |
| SODIMM | 29       | 9.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 129      | 39.33%  |
| 4096  | 85       | 25.91%  |
| 16384 | 59       | 17.99%  |
| 2048  | 28       | 8.54%   |
| 1024  | 13       | 3.96%   |
| 32768 | 11       | 3.35%   |
| 512   | 3        | 0.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 47       | 13.86%  |
| 2400    | 40       | 11.8%   |
| 1600    | 35       | 10.32%  |
| 2667    | 25       | 7.37%   |
| 1333    | 23       | 6.78%   |
| 2666    | 18       | 5.31%   |
| 2133    | 17       | 5.01%   |
| 800     | 12       | 3.54%   |
| 4800    | 11       | 3.24%   |
| 3600    | 11       | 3.24%   |
| 1866    | 7        | 2.06%   |
| 3733    | 6        | 1.77%   |
| 667     | 6        | 1.77%   |
| Unknown | 6        | 1.77%   |
| 3266    | 5        | 1.47%   |
| 6000    | 4        | 1.18%   |
| 5600    | 4        | 1.18%   |
| 3800    | 4        | 1.18%   |
| 3466    | 4        | 1.18%   |
| 3000    | 4        | 1.18%   |
| 400     | 4        | 1.18%   |
| 4000    | 3        | 0.88%   |
| 3333    | 3        | 0.88%   |
| 3066    | 3        | 0.88%   |
| 2933    | 3        | 0.88%   |
| 2800    | 3        | 0.88%   |
| 533     | 3        | 0.88%   |
| 5200    | 2        | 0.59%   |
| 3400    | 2        | 0.59%   |
| 2866    | 2        | 0.59%   |
| 1334    | 2        | 0.59%   |
| 1066    | 2        | 0.59%   |
| 333     | 2        | 0.59%   |
| 12800   | 1        | 0.29%   |
| 6800    | 1        | 0.29%   |
| 5400    | 1        | 0.29%   |
| 4333    | 1        | 0.29%   |
| 3534    | 1        | 0.29%   |
| 3533    | 1        | 0.29%   |
| 3467    | 1        | 0.29%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 9        | 23.08%  |
| Samsung Electronics | 8        | 20.51%  |
| Hewlett-Packard     | 8        | 20.51%  |
| Pantum              | 6        | 15.38%  |
| Brother Industries  | 3        | 7.69%   |
| Seiko Epson         | 2        | 5.13%   |
| QinHeng Electronics | 2        | 5.13%   |
| Kyocera             | 1        | 2.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Pantum P2200 series                  | 3        | 7.69%   |
| QinHeng CH340S                       | 2        | 5.13%   |
| HP LaserJet 1010                     | 2        | 5.13%   |
| Canon MF4010 series                  | 2        | 5.13%   |
| Seiko Epson L3050 Series             | 1        | 2.56%   |
| Seiko Epson EPSON L132 Series        | 1        | 2.56%   |
| Samsung SCX-4200 series              | 1        | 2.56%   |
| Samsung SCX-4100 Scanner             | 1        | 2.56%   |
| Samsung SCX-3400 Series              | 1        | 2.56%   |
| Samsung SCX-3200 Series              | 1        | 2.56%   |
| Samsung ML-2010P Mono Laser Printer  | 1        | 2.56%   |
| Samsung ML-1640 Series Laser Printer | 1        | 2.56%   |
| Samsung M332x 382x 402x Series       | 1        | 2.56%   |
| Samsung CLX-3180 Series              | 1        | 2.56%   |
| Pantum M7100DN series                | 1        | 2.56%   |
| Pantum M6500W series                 | 1        | 2.56%   |
| Pantum M6500-series                  | 1        | 2.56%   |
| Kyocera FS-1135MFP                   | 1        | 2.56%   |
| HP LaserJet P3010 Series             | 1        | 2.56%   |
| HP LaserJet P1102                    | 1        | 2.56%   |
| HP LaserJet P1005                    | 1        | 2.56%   |
| HP LaserJet M402dn                   | 1        | 2.56%   |
| HP LaserJet 3055                     | 1        | 2.56%   |
| HP HP LaserJet Pro M428-M429         | 1        | 2.56%   |
| Canon PIXMA MP280                    | 1        | 2.56%   |
| Canon MF4410                         | 1        | 2.56%   |
| Canon MF420 Series                   | 1        | 2.56%   |
| Canon MF3110                         | 1        | 2.56%   |
| Canon LiDE 300                       | 1        | 2.56%   |
| Canon G3010 series                   | 1        | 2.56%   |
| Canon G1010 series                   | 1        | 2.56%   |
| Brother HL-L2300D series             | 1        | 2.56%   |
| Brother DCP-7030                     | 1        | 2.56%   |
| Brother DCP-1510                     | 1        | 2.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 4        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LIDE 25  | 2        | 50%     |
| Canon CanoScan LiDE 110 | 2        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Logitech                       | 30       | 38.46%  |
| Alcor Micro                    | 7        | 8.97%   |
| Sunplus Innovation Technology  | 5        | 6.41%   |
| Microsoft                      | 4        | 5.13%   |
| Z-Star Microelectronics        | 3        | 3.85%   |
| Realtek Semiconductor          | 3        | 3.85%   |
| Microdia                       | 3        | 3.85%   |
| WaveRider Communications       | 2        | 2.56%   |
| SunplusIT                      | 2        | 2.56%   |
| Samsung Electronics            | 2        | 2.56%   |
| Creative Technology            | 2        | 2.56%   |
| Apple                          | 2        | 2.56%   |
| Unknown                        | 1        | 1.28%   |
| Sunplus IT                     | 1        | 1.28%   |
| MediaTek                       | 1        | 1.28%   |
| lihappe8                       | 1        | 1.28%   |
| KYT-240222-A                   | 1        | 1.28%   |
| Hewlett-Packard                | 1        | 1.28%   |
| GEMBIRD                        | 1        | 1.28%   |
| Beijing Senseshield Technology | 1        | 1.28%   |
| Aveo Technology                | 1        | 1.28%   |
| ANYKA                          | 1        | 1.28%   |
| AlcorMicroCorp                 | 1        | 1.28%   |
| A4Tech                         | 1        | 1.28%   |
| Unknown                        | 1        | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 17       | 21.52%  |
| Alcor Micro USB 2.0 PC Camera                     | 5        | 6.33%   |
| Z-Star Venus USB2.0 Camera                        | 3        | 3.8%    |
| Sunplus USB Microphone                            | 3        | 3.8%    |
| Microdia Camera                                   | 3        | 3.8%    |
| WaveRider USB Camera                              | 2        | 2.53%   |
| SunplusIT USB Camera                              | 2        | 2.53%   |
| Realtek USB Camera                                | 2        | 2.53%   |
| Microsoft LifeCam VX-700                          | 2        | 2.53%   |
| Logitech HD Pro Webcam C920                       | 2        | 2.53%   |
| Logitech C505 HD Webcam                           | 2        | 2.53%   |
| Logitech BRIO Ultra HD Webcam                     | 2        | 2.53%   |
| Creative Live! Cam Sync 1080p V2                  | 2        | 2.53%   |
| Alcor Micro USB 2.0 Camera                        | 2        | 2.53%   |
| Unknown HD camera                                 | 1        | 1.27%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 1        | 1.27%   |
| Sunplus SPCA2650 PC Camera                        | 1        | 1.27%   |
| Sunplus Full HD webcam                            | 1        | 1.27%   |
| Samsung USB2.0 UVC HQ WebCam                      | 1        | 1.27%   |
| Samsung Galaxy series, misc. (MTP mode)           | 1        | 1.27%   |
| Realtek 1080p Camera                              | 1        | 1.27%   |
| Microsoft LifeCam Studio                          | 1        | 1.27%   |
| Microsoft LifeCam HD-3000                         | 1        | 1.27%   |
| MediaTek R570E                                    | 1        | 1.27%   |
| Logitech Webcam C930e                             | 1        | 1.27%   |
| Logitech Webcam C200                              | 1        | 1.27%   |
| Logitech Webcam C170                              | 1        | 1.27%   |
| Logitech HD Webcam C615                           | 1        | 1.27%   |
| Logitech HD Webcam C525                           | 1        | 1.27%   |
| Logitech HD Webcam B910                           | 1        | 1.27%   |
| Logitech C920 PRO HD Webcam                       | 1        | 1.27%   |
| Logitech B525 HD Webcam                           | 1        | 1.27%   |
| lihappe8 USB 2.0 Camera                           | 1        | 1.27%   |
| KYT-240222-A USB Camera                           | 1        | 1.27%   |
| HP Webcam HD 2300                                 | 1        | 1.27%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 1.27%   |
| Beijing Senseshield ZET USB WEBCAM                | 1        | 1.27%   |
| Aveo UVC camera (Bresser microscope)              | 1        | 1.27%   |
| Apple iSight in LED Cinema Display                | 1        | 1.27%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 1        | 1.27%   |

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


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Aktiv                     | 2        | 40%     |
| Aladdin R.D.              | 1        | 20%     |
| Aladdin Knowledge Systems | 1        | 20%     |
| Advanced Card Systems     | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Aktiv Rutoken lite                           | 2        | 40%     |
| Aladdin R.D. JaCarta LT                      | 1        | 20%     |
| Aladdin Knowledge Systems Token JC           | 1        | 20%     |
| Advanced Card Systems ACR38 SmartCard Reader | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 429      | 89%     |
| 1     | 48       | 9.96%   |
| 2     | 4        | 0.83%   |
| 5     | 1        | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 24       | 42.86%  |
| Communication controller | 8        | 14.29%  |
| Net/wireless             | 6        | 10.71%  |
| Unassigned class         | 4        | 7.14%   |
| Multimedia controller    | 3        | 5.36%   |
| Sound                    | 2        | 3.57%   |
| Net/ethernet             | 2        | 3.57%   |
| Chipcard                 | 2        | 3.57%   |
| Storage/ide              | 1        | 1.79%   |
| Network                  | 1        | 1.79%   |
| Fingerprint reader       | 1        | 1.79%   |
| Camera                   | 1        | 1.79%   |
| Bluetooth                | 1        | 1.79%   |

