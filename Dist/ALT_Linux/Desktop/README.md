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

Total: 423

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Foxconn       | 2ABF                        | [dbc40fef9d](https://linux-hardware.org/?probe=dbc40fef9d) | Dec 18, 2020 |
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

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Kometa P10         | 81       | 26.3%   |
| ALT Linux 10.1     | 65       | 21.1%   |
| ALT Linux 9.1      | 33       | 10.71%  |
| ALT Linux 10.2     | 23       | 7.47%   |
| ALT Linux 10.0     | 23       | 7.47%   |
| ALT Linux 9.0      | 15       | 4.87%   |
| MOS 10             | 14       | 4.55%   |
| ALT Linux 9.2      | 7        | 2.27%   |
| ALT Linux 8.4      | 7        | 2.27%   |
| ALT Linux 10       | 7        | 2.27%   |
| ALT Linux P10      | 5        | 1.62%   |
| ALT Linux P9       | 4        | 1.3%    |
| ALT Linux 10.1.900 | 4        | 1.3%    |
| ALT Linux P8       | 2        | 0.65%   |
| ALT Linux 8.2      | 2        | 0.65%   |
| ALT Linux 7.0.5    | 2        | 0.65%   |
| ALT Linux 20230819 | 2        | 0.65%   |
| ALT Linux 20220110 | 2        | 0.65%   |
| ALT Linux 10.0.900 | 2        | 0.65%   |
| Kometa 1           | 1        | 0.32%   |
| ALT Linux 8.2.0    | 1        | 0.32%   |
| ALT Linux 20201124 | 1        | 0.32%   |
| ALT Linux 20190303 | 1        | 0.32%   |
| ALT Linux 10.1.990 | 1        | 0.32%   |
| ALT Linux 10.0.910 | 1        | 0.32%   |
| ALT Linux 0.8.1    | 1        | 0.32%   |
| ALT Linux 0.7.6    | 1        | 0.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ALT Linux | 289      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.10.109-std-def-alt1      | 51       | 15.99%  |
| 5.10.102-std-def-alt1      | 27       | 8.46%   |
| 5.15.34-un-def-alt1        | 11       | 3.45%   |
| 5.10.164-std-def-alt1      | 11       | 3.45%   |
| 5.15.72-un-def-alt1        | 10       | 3.13%   |
| 5.10.82-std-def-alt1       | 9        | 2.82%   |
| 5.15.80-un-def-alt1        | 8        | 2.51%   |
| 5.4.68-std-def-alt1.1      | 7        | 2.19%   |
| 5.10.123-std-def-alt1      | 7        | 2.19%   |
| 5.10.166-std-def-alt1      | 6        | 1.88%   |
| 5.4.51-std-def-alt1        | 5        | 1.57%   |
| 5.15.32-un-def-alt1        | 5        | 1.57%   |
| 6.1.49-un-def-alt1         | 4        | 1.25%   |
| 6.1.38-un-def-alt1         | 4        | 1.25%   |
| 5.10.88-std-def-alt1       | 4        | 1.25%   |
| 5.10.145-std-def-alt1      | 4        | 1.25%   |
| 5.4.41-std-def-alt1        | 3        | 0.94%   |
| 5.4.28-std-def-alt1        | 3        | 0.94%   |
| 5.10.93-std-def-alt1       | 3        | 0.94%   |
| 5.10.83-std-def-alt0.c9f.2 | 3        | 0.94%   |
| 5.10.35-un-def-alt1        | 3        | 0.94%   |
| 5.10.32-un-def-alt1        | 3        | 0.94%   |
| 5.10.179-std-def-alt1      | 3        | 0.94%   |
| 5.10.156-std-def-alt1      | 3        | 0.94%   |
| 4.19.79-std-def-alt1       | 3        | 0.94%   |
| 6.1.63-un-def-alt1         | 2        | 0.63%   |
| 6.1.62-un-def-alt1         | 2        | 0.63%   |
| 6.1.61-un-def-alt1         | 2        | 0.63%   |
| 6.1.60-un-def-alt1         | 2        | 0.63%   |
| 6.1.29-un-def-alt1         | 2        | 0.63%   |
| 5.7.19-un-def-alt1         | 2        | 0.63%   |
| 5.4.85-std-def-alt1        | 2        | 0.63%   |
| 5.4.62-std-def-alt1        | 2        | 0.63%   |
| 5.4.181-std-def-alt1       | 2        | 0.63%   |
| 5.4.127-std-def-alt1       | 2        | 0.63%   |
| 5.2.10-un-def-alt1         | 2        | 0.63%   |
| 5.15.96-un-def-alt1        | 2        | 0.63%   |
| 5.15.90-un-def-alt1        | 2        | 0.63%   |
| 5.15.70-un-def-alt1        | 2        | 0.63%   |
| 5.15.63-un-def-alt1        | 2        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.109 | 51       | 15.99%  |
| 5.10.102 | 27       | 8.46%   |
| 5.15.34  | 11       | 3.45%   |
| 5.10.164 | 11       | 3.45%   |
| 5.15.72  | 10       | 3.13%   |
| 5.10.82  | 9        | 2.82%   |
| 5.15.80  | 8        | 2.51%   |
| 5.4.68   | 7        | 2.19%   |
| 5.10.123 | 7        | 2.19%   |
| 5.10.166 | 6        | 1.88%   |
| 5.4.51   | 5        | 1.57%   |
| 5.15.32  | 5        | 1.57%   |
| 6.1.49   | 4        | 1.25%   |
| 6.1.38   | 4        | 1.25%   |
| 5.10.88  | 4        | 1.25%   |
| 5.10.156 | 4        | 1.25%   |
| 5.10.145 | 4        | 1.25%   |
| 5.4.41   | 3        | 0.94%   |
| 5.4.28   | 3        | 0.94%   |
| 5.10.93  | 3        | 0.94%   |
| 5.10.83  | 3        | 0.94%   |
| 5.10.35  | 3        | 0.94%   |
| 5.10.32  | 3        | 0.94%   |
| 5.10.179 | 3        | 0.94%   |
| 4.19.79  | 3        | 0.94%   |
| 6.1.63   | 2        | 0.63%   |
| 6.1.62   | 2        | 0.63%   |
| 6.1.61   | 2        | 0.63%   |
| 6.1.60   | 2        | 0.63%   |
| 6.1.29   | 2        | 0.63%   |
| 5.7.19   | 2        | 0.63%   |
| 5.4.85   | 2        | 0.63%   |
| 5.4.62   | 2        | 0.63%   |
| 5.4.181  | 2        | 0.63%   |
| 5.4.127  | 2        | 0.63%   |
| 5.2.10   | 2        | 0.63%   |
| 5.15.96  | 2        | 0.63%   |
| 5.15.90  | 2        | 0.63%   |
| 5.15.70  | 2        | 0.63%   |
| 5.15.63  | 2        | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 166      | 54.97%  |
| 5.15    | 49       | 16.23%  |
| 5.4     | 37       | 12.25%  |
| 6.1     | 20       | 6.62%   |
| 4.19    | 7        | 2.32%   |
| 6.5     | 3        | 0.99%   |
| 5.7     | 3        | 0.99%   |
| 5.2     | 3        | 0.99%   |
| 4.9     | 3        | 0.99%   |
| 6.4     | 2        | 0.66%   |
| 5.14    | 2        | 0.66%   |
| 4.14    | 2        | 0.66%   |
| 5.9     | 1        | 0.33%   |
| 5.18    | 1        | 0.33%   |
| 5.13    | 1        | 0.33%   |
| 5.12    | 1        | 0.33%   |
| 4.20    | 1        | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 281      | 97.23%  |
| i686   | 4        | 1.38%   |
| e2k    | 4        | 1.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 181      | 61.56%  |
| Unknown    | 46       | 15.65%  |
| XFCE       | 44       | 14.97%  |
| MATE       | 14       | 4.76%   |
| GNOME      | 4        | 1.36%   |
| KDE        | 2        | 0.68%   |
| Cinnamon   | 2        | 0.68%   |
| X-Cinnamon | 1        | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 272      | 93.79%  |
| Tty     | 7        | 2.41%   |
| Unknown | 7        | 2.41%   |
| Wayland | 4        | 1.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 135      | 45.61%  |
| LightDM | 66       | 22.3%   |
| Unknown | 66       | 22.3%   |
| TDM     | 28       | 9.46%   |
| WDM     | 1        | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 252      | 85.14%  |
| Unknown | 38       | 12.84%  |
| en_US   | 3        | 1.01%   |
| ru      | 1        | 0.34%   |
| POSIX   | 1        | 0.34%   |
| el_GR   | 1        | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 147      | 50.34%  |
| EFI  | 145      | 49.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 265      | 91.07%  |
| Btrfs   | 15       | 5.15%   |
| Overlay | 11       | 3.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 162      | 55.29%  |
| MBR     | 72       | 24.57%  |
| Unknown | 59       | 20.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 252      | 86.9%   |
| Yes       | 38       | 13.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 227      | 77.21%  |
| Yes       | 67       | 22.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 61       | 21.11%  |
| Intel               | 53       | 18.34%  |
| Gigabyte Technology | 48       | 16.61%  |
| ASRock              | 24       | 8.3%    |
| MSI                 | 23       | 7.96%   |
| Acer                | 14       | 4.84%   |
| Unknown             | 13       | 4.5%    |
| Hewlett-Packard     | 7        | 2.42%   |
| DEPO Computers      | 6        | 2.08%   |
| MAINBRD             | 4        | 1.38%   |
| Graviton            | 4        | 1.38%   |
| Biostar             | 4        | 1.38%   |
| 3Logic Group        | 4        | 1.38%   |
| iRU                 | 3        | 1.04%   |
| Pegatron            | 2        | 0.69%   |
| Lenovo              | 2        | 0.69%   |
| Huanan              | 2        | 0.69%   |
| Foxconn             | 2        | 0.69%   |
| Dell                | 2        | 0.69%   |
| Aquarius            | 2        | 0.69%   |
| Yadro               | 1        | 0.35%   |
| VIA Technologies    | 1        | 0.35%   |
| SYS                 | 1        | 0.35%   |
| Supermicro          | 1        | 0.35%   |
| OEM                 | 1        | 0.35%   |
| Kraftway            | 1        | 0.35%   |
| EPoX Computer       | 1        | 0.35%   |
| ECS                 | 1        | 0.35%   |
| AZW                 | 1        | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel SKYBAY                      | 47       | 16.26%  |
| Unknown                           | 13       | 4.5%    |
| ASUS PRIME B450-PLUS              | 12       | 4.15%   |
| Acer Veriton X2640G               | 10       | 3.46%   |
| MAINBRD OPS62A-SHA                | 4        | 1.38%   |
| HP ProLiant SL230s Gen8           | 4        | 1.38%   |
| Gigabyte H110M-S2H                | 4        | 1.38%   |
| ASUS All Series                   | 4        | 1.38%   |
| 3Logic Group Graviton             | 4        | 1.38%   |
| DEPO Computers DPA520S            | 3        | 1.04%   |
| ASUS H110M-R                      | 3        | 1.04%   |
| MSI MS-7D46                       | 2        | 0.69%   |
| MSI MS-7C94                       | 2        | 0.69%   |
| MSI MS-7C75                       | 2        | 0.69%   |
| MSI MS-7C56                       | 2        | 0.69%   |
| MSI MPG B560 Trident A (MS-B926)  | 2        | 0.69%   |
| iRU 515                           | 2        | 0.69%   |
| Intel B75                         | 2        | 0.69%   |
| Graviton DMB-A520-MCA01           | 2        | 0.69%   |
| Gigabyte Z390 AORUS MASTER        | 2        | 0.69%   |
| Gigabyte H77M-D3H                 | 2        | 0.69%   |
| Gigabyte A320M-S2H                | 2        | 0.69%   |
| DEPO Computers DPH410S            | 2        | 0.69%   |
| ASRock B450M Pro4                 | 2        | 0.69%   |
| Acer Veriton ES2710G              | 2        | 0.69%   |
| Yadro TB560-D4                    | 1        | 0.35%   |
| VIA P4M266A-8235                  | 1        | 0.35%   |
| SYS RAY B101                      | 1        | 0.35%   |
| Supermicro SYS-1019D-14CN-FHN13TP | 1        | 0.35%   |
| Pegatron IPMSB-H61                | 1        | 0.35%   |
| Pegatron Elite 7300 Series MT     | 1        | 0.35%   |
| OEM ZXE CRB                       | 1        | 0.35%   |
| MSI MS-7D95                       | 1        | 0.35%   |
| MSI MS-7D23                       | 1        | 0.35%   |
| MSI MS-7D18                       | 1        | 0.35%   |
| MSI MS-7C37                       | 1        | 0.35%   |
| MSI MS-7B33                       | 1        | 0.35%   |
| MSI MS-7A38                       | 1        | 0.35%   |
| MSI MS-7996                       | 1        | 0.35%   |
| MSI MS-7895                       | 1        | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel SKYBAY                      | 47       | 16.26%  |
| ASUS PRIME                        | 18       | 6.23%   |
| Acer Veriton                      | 13       | 4.5%    |
| Unknown                           | 13       | 4.5%    |
| MAINBRD OPS62A-SHA                | 4        | 1.38%   |
| HP ProLiant                       | 4        | 1.38%   |
| Gigabyte H110M-S2H                | 4        | 1.38%   |
| ASUS All                          | 4        | 1.38%   |
| 3Logic Group Graviton             | 4        | 1.38%   |
| DEPO Computers DPA520S            | 3        | 1.04%   |
| ASUS P7H55-M                      | 3        | 1.04%   |
| ASUS P5G41T-M                     | 3        | 1.04%   |
| ASUS H110M-R                      | 3        | 1.04%   |
| MSI MS-7D46                       | 2        | 0.69%   |
| MSI MS-7C94                       | 2        | 0.69%   |
| MSI MS-7C75                       | 2        | 0.69%   |
| MSI MS-7C56                       | 2        | 0.69%   |
| MSI MPG                           | 2        | 0.69%   |
| iRU 515                           | 2        | 0.69%   |
| Intel B75                         | 2        | 0.69%   |
| HP Compaq                         | 2        | 0.69%   |
| Graviton DMB-A520-MCA01           | 2        | 0.69%   |
| Gigabyte Z390                     | 2        | 0.69%   |
| Gigabyte H77M-D3H                 | 2        | 0.69%   |
| Gigabyte B550                     | 2        | 0.69%   |
| Gigabyte B450                     | 2        | 0.69%   |
| Gigabyte A320M-S2H                | 2        | 0.69%   |
| DEPO Computers DPH410S            | 2        | 0.69%   |
| Dell OptiPlex                     | 2        | 0.69%   |
| ASUS ROG                          | 2        | 0.69%   |
| ASRock Z77                        | 2        | 0.69%   |
| ASRock B450M                      | 2        | 0.69%   |
| Yadro TB560-D4                    | 1        | 0.35%   |
| VIA P4M266A-8235                  | 1        | 0.35%   |
| SYS RAY                           | 1        | 0.35%   |
| Supermicro SYS-1019D-14CN-FHN13TP | 1        | 0.35%   |
| Pegatron IPMSB-H61                | 1        | 0.35%   |
| Pegatron Elite                    | 1        | 0.35%   |
| OEM ZXE                           | 1        | 0.35%   |
| MSI MS-7D95                       | 1        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 51       | 17.65%  |
| 2017    | 39       | 13.49%  |
| 2020    | 25       | 8.65%   |
| 2016    | 22       | 7.61%   |
| 2022    | 21       | 7.27%   |
| 2021    | 17       | 5.88%   |
| 2012    | 14       | 4.84%   |
| 2013    | 12       | 4.15%   |
| 2010    | 12       | 4.15%   |
| 2009    | 11       | 3.81%   |
| 2011    | 10       | 3.46%   |
| 2019    | 8        | 2.77%   |
| 2014    | 8        | 2.77%   |
| 2008    | 8        | 2.77%   |
| 2015    | 7        | 2.42%   |
| 2006    | 7        | 2.42%   |
| 2007    | 6        | 2.08%   |
| Unknown | 4        | 1.38%   |
| 2005    | 3        | 1.04%   |
| 2023    | 2        | 0.69%   |
| 2004    | 1        | 0.35%   |
| 2003    | 1        | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 289      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 278      | 95.53%  |
| Enabled  | 13       | 4.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 289      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 103      | 35.52%  |
| 4.01-8.0    | 64       | 22.07%  |
| 3.01-4.0    | 38       | 13.1%   |
| 16.01-24.0  | 34       | 11.72%  |
| 32.01-64.0  | 19       | 6.55%   |
| 64.01-256.0 | 11       | 3.79%   |
| 1.01-2.0    | 7        | 2.41%   |
| 24.01-32.0  | 6        | 2.07%   |
| 2.01-3.0    | 6        | 2.07%   |
| 0.51-1.0    | 2        | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 143      | 46.89%  |
| 2.01-3.0   | 56       | 18.36%  |
| 0.51-1.0   | 36       | 11.8%   |
| 4.01-8.0   | 32       | 10.49%  |
| 3.01-4.0   | 23       | 7.54%   |
| 8.01-16.0  | 8        | 2.62%   |
| 0.01-0.5   | 3        | 0.98%   |
| 32.01-64.0 | 2        | 0.66%   |
| 16.01-24.0 | 2        | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 182      | 61.69%  |
| 2      | 59       | 20%     |
| 3      | 26       | 8.81%   |
| 4      | 16       | 5.42%   |
| 5      | 8        | 2.71%   |
| 9      | 1        | 0.34%   |
| 8      | 1        | 0.34%   |
| 6      | 1        | 0.34%   |
| 0      | 1        | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 193      | 66.55%  |
| Yes       | 97       | 33.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 288      | 99.65%  |
| No        | 1        | 0.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 232      | 80%     |
| Yes       | 58       | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 244      | 83.85%  |
| Yes       | 47       | 16.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Russia     | 278      | 95.86%  |
| Ukraine    | 4        | 1.38%   |
| Greece     | 2        | 0.69%   |
| UK         | 1        | 0.34%   |
| Latvia     | 1        | 0.34%   |
| Kazakhstan | 1        | 0.34%   |
| Finland    | 1        | 0.34%   |
| China      | 1        | 0.34%   |
| Belarus    | 1        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 159      | 53.54%  |
| St Petersburg     | 23       | 7.74%   |
| Samara            | 7        | 2.36%   |
| Chelyabinsk       | 5        | 1.68%   |
| Krasnoyarsk       | 4        | 1.35%   |
| Irkutsk           | 4        | 1.35%   |
| Barnaul           | 4        | 1.35%   |
| Perm              | 3        | 1.01%   |
| Novosibirsk       | 3        | 1.01%   |
| Kirov             | 3        | 1.01%   |
| Zheleznodorozhnyy | 2        | 0.67%   |
| Zelenodolsk       | 2        | 0.67%   |
| Yekaterinburg     | 2        | 0.67%   |
| Surgut            | 2        | 0.67%   |
| Stavropol         | 2        | 0.67%   |
| Sevastopol        | 2        | 0.67%   |
| Saratov           | 2        | 0.67%   |
| Rostov-on-Don     | 2        | 0.67%   |
| Obninsk           | 2        | 0.67%   |
| Murmansk          | 2        | 0.67%   |
| Krasnodar         | 2        | 0.67%   |
| Kaliningrad       | 2        | 0.67%   |
| Donetsk           | 2        | 0.67%   |
| Zhukovskiy        | 1        | 0.34%   |
| Yessentuki        | 1        | 0.34%   |
| Vologda           | 1        | 0.34%   |
| Volgograd         | 1        | 0.34%   |
| Vladivostok       | 1        | 0.34%   |
| Vladimir          | 1        | 0.34%   |
| Vikhorevka        | 1        | 0.34%   |
| Vidnoye           | 1        | 0.34%   |
| Verkhnyaya Pyshma | 1        | 0.34%   |
| Vergina           | 1        | 0.34%   |
| Valuyki           | 1        | 0.34%   |
| Ulyanovsk         | 1        | 0.34%   |
| Ufa               | 1        | 0.34%   |
| Tula              | 1        | 0.34%   |
| Tolyatti          | 1        | 0.34%   |
| Thessaloniki      | 1        | 0.34%   |
| Taraz             | 1        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 80       | 126    | 18.52%  |
| Seagate                   | 66       | 101    | 15.28%  |
| Samsung Electronics       | 49       | 59     | 11.34%  |
| Toshiba                   | 37       | 55     | 8.56%   |
| Kingston                  | 31       | 36     | 7.18%   |
| AXIOMTEK                  | 29       | 31     | 6.71%   |
| Apacer                    | 15       | 21     | 3.47%   |
| China                     | 12       | 13     | 2.78%   |
| A-DATA Technology         | 9        | 10     | 2.08%   |
| Hitachi                   | 7        | 8      | 1.62%   |
| Hewlett-Packard           | 5        | 9      | 1.16%   |
| AMD                       | 5        | 5      | 1.16%   |
| XPG                       | 4        | 5      | 0.93%   |
| SanDisk                   | 4        | 4      | 0.93%   |
| Plextor                   | 4        | 4      | 0.93%   |
| Patriot                   | 4        | 6      | 0.93%   |
| Micron Technology         | 4        | 5      | 0.93%   |
| Gigabyte Technology       | 4        | 4      | 0.93%   |
| Crucial                   | 4        | 4      | 0.93%   |
| Team                      | 3        | 4      | 0.69%   |
| SPCC                      | 3        | 3      | 0.69%   |
| Smartbuy                  | 3        | 3      | 0.69%   |
| Silicon Motion            | 3        | 4      | 0.69%   |
| Intel                     | 3        | 8      | 0.69%   |
| HGST                      | 3        | 3      | 0.69%   |
| XrayDisk                  | 2        | 2      | 0.46%   |
| TMI                       | 2        | 3      | 0.46%   |
| Phison Electronics        | 2        | 2      | 0.46%   |
| Phison                    | 2        | 2      | 0.46%   |
| OCZ                       | 2        | 2      | 0.46%   |
| Netac                     | 2        | 2      | 0.46%   |
| JMicron Technology        | 2        | 2      | 0.46%   |
| DEPO                      | 2        | 2      | 0.46%   |
| Transcend                 | 1        | 1      | 0.23%   |
| SP-8                      | 1        | 1      | 0.23%   |
| SINTECHI                  | 1        | 1      | 0.23%   |
| SABRENT                   | 1        | 1      | 0.23%   |
| Qumo                      | 1        | 1      | 0.23%   |
| MSI                       | 1        | 1      | 0.23%   |
| Micron/Crucial Technology | 1        | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD                  | 29       | 6.24%   |
| Samsung MZVLW128HEGR-00000 128GB                      | 18       | 3.87%   |
| Toshiba HDWD120 2TB                                   | 13       | 2.8%    |
| WDC WD5000AZLX-21K2TA0 500GB                          | 10       | 2.15%   |
| Toshiba HDWD110 1TB                                   | 9        | 1.94%   |
| Seagate ST1000DM010-2EP102 1TB                        | 6        | 1.29%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 4        | 0.86%   |
| WDC WD10EZEX-00BBHA0 1TB                              | 4        | 0.86%   |
| Toshiba DT01ACA100 1TB                                | 4        | 0.86%   |
| Toshiba DT01ACA050 500GB                              | 4        | 0.86%   |
| Seagate ST500DM002-1BD142 500GB                       | 4        | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 4        | 0.86%   |
| Kingston SV300S37A120G 120GB SSD                      | 4        | 0.86%   |
| Kingston SA400S37240G 240GB SSD                       | 4        | 0.86%   |
| Kingston RBUSC180S37256GJ 256GB SSD                   | 4        | 0.86%   |
| HP EG0450FCSPK 450GB                                  | 4        | 0.86%   |
| Apacer AS350 256GB SSD                                | 4        | 0.86%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                      | 3        | 0.65%   |
| WDC WDS240G1G0A-00SS50 240GB SSD                      | 3        | 0.65%   |
| WDC WD20EZBX-00AYRA0 2TB                              | 3        | 0.65%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 3        | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 3        | 0.65%   |
| Seagate ST380815AS 80GB                               | 3        | 0.65%   |
| Seagate ST1000LM049-2GH172 1TB                        | 3        | 0.65%   |
| Samsung SSD 860 EVO 250GB                             | 3        | 0.65%   |
| Kingston SA400S37120G 120GB SSD                       | 3        | 0.65%   |
| Apacer AS2280P4 512GB                                 | 3        | 0.65%   |
| XPG GAMMIX S5 512GB                                   | 2        | 0.43%   |
| WDC WD5003ABYZ-011FA0 500GB                           | 2        | 0.43%   |
| WDC WD3200AAKS-00G3A0 320GB                           | 2        | 0.43%   |
| WDC WD2000FYYZ-01UL1B1 2TB                            | 2        | 0.43%   |
| WDC WD10PURZ-85U8XY0 1TB                              | 2        | 0.43%   |
| WDC WD10JPVX-00JC3T0 1TB                              | 2        | 0.43%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB                    | 2        | 0.43%   |
| Toshiba DT01ACA200 2TB                                | 2        | 0.43%   |
| Team T253X1240G 240GB SSD                             | 2        | 0.43%   |
| SPCC M.2 PCIe SSD 1TB                                 | 2        | 0.43%   |
| Seagate ST500LM030-2E717D 500GB                       | 2        | 0.43%   |
| Seagate ST500DM002-1BC142 500GB                       | 2        | 0.43%   |
| Seagate ST3500418AS 500GB                             | 2        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 70       | 113    | 37.04%  |
| Seagate             | 64       | 95     | 33.86%  |
| Toshiba             | 37       | 54     | 19.58%  |
| Hitachi             | 7        | 8      | 3.7%    |
| Samsung Electronics | 6        | 7      | 3.17%   |
| HGST                | 3        | 3      | 1.59%   |
| SINTECHI            | 1        | 1      | 0.53%   |
| Maxtor              | 1        | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| AXIOMTEK            | 29       | 31     | 16.67%  |
| Kingston            | 27       | 29     | 15.52%  |
| Samsung Electronics | 14       | 17     | 8.05%   |
| China               | 12       | 13     | 6.9%    |
| Apacer              | 12       | 16     | 6.9%    |
| WDC                 | 11       | 11     | 6.32%   |
| A-DATA Technology   | 7        | 8      | 4.02%   |
| AMD                 | 5        | 5      | 2.87%   |
| Plextor             | 4        | 4      | 2.3%    |
| Patriot             | 4        | 6      | 2.3%    |
| Crucial             | 4        | 4      | 2.3%    |
| Team                | 3        | 4      | 1.72%   |
| Smartbuy            | 3        | 3      | 1.72%   |
| Gigabyte Technology | 3        | 3      | 1.72%   |
| XrayDisk            | 2        | 2      | 1.15%   |
| TMI                 | 2        | 3      | 1.15%   |
| Seagate             | 2        | 6      | 1.15%   |
| SanDisk             | 2        | 2      | 1.15%   |
| Phison              | 2        | 2      | 1.15%   |
| OCZ                 | 2        | 2      | 1.15%   |
| JMicron Technology  | 2        | 2      | 1.15%   |
| Intel               | 2        | 6      | 1.15%   |
| DEPO                | 2        | 2      | 1.15%   |
| Transcend           | 1        | 1      | 0.57%   |
| SP-8                | 1        | 1      | 0.57%   |
| Qumo                | 1        | 1      | 0.57%   |
| Netac               | 1        | 1      | 0.57%   |
| Micron Technology   | 1        | 1      | 0.57%   |
| LITEON              | 1        | 1      | 0.57%   |
| KingSpec            | 1        | 1      | 0.57%   |
| HYDRA               | 1        | 1      | 0.57%   |
| HS-SSD-C100         | 1        | 1      | 0.57%   |
| HEORIADY            | 1        | 1      | 0.57%   |
| GS Nanotech         | 1        | 1      | 0.57%   |
| GOODRAM             | 1        | 1      | 0.57%   |
| FreeBSD             | 1        | 1      | 0.57%   |
| Foxline             | 1        | 1      | 0.57%   |
| Digma               | 1        | 1      | 0.57%   |
| DEXP                | 1        | 2      | 0.57%   |
| Corsair             | 1        | 3      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 160      | 282    | 42.11%  |
| SSD     | 152      | 202    | 40%     |
| NVMe    | 64       | 86     | 16.84%  |
| Unknown | 4        | 7      | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 253      | 479    | 77.85%  |
| NVMe | 64       | 85     | 19.69%  |
| SAS  | 8        | 13     | 2.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 201      | 276    | 61.66%  |
| 0.51-1.0   | 76       | 120    | 23.31%  |
| 1.01-2.0   | 35       | 73     | 10.74%  |
| 3.01-4.0   | 6        | 6      | 1.84%   |
| 2.01-3.0   | 5        | 6      | 1.53%   |
| 4.01-10.0  | 2        | 2      | 0.61%   |
| 0          | 1        | 1      | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 126      | 42.14%  |
| 251-500        | 52       | 17.39%  |
| 1001-2000      | 35       | 11.71%  |
| 501-1000       | 28       | 9.36%   |
| More than 3000 | 15       | 5.02%   |
| 51-100         | 12       | 4.01%   |
| 21-50          | 10       | 3.34%   |
| 2001-3000      | 9        | 3.01%   |
| 1-20           | 7        | 2.34%   |
| Unknown        | 5        | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 138      | 45.7%   |
| 21-50          | 55       | 18.21%  |
| 51-100         | 30       | 9.93%   |
| 101-250        | 26       | 8.61%   |
| 501-1000       | 15       | 4.97%   |
| 251-500        | 14       | 4.64%   |
| 1001-2000      | 10       | 3.31%   |
| More than 3000 | 5        | 1.66%   |
| Unknown        | 5        | 1.66%   |
| 2001-3000      | 4        | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| XrayDisk 512GB SSD                           | 1        | 1      | 2.86%   |
| XrayDisk 240GB SSD                           | 1        | 1      | 2.86%   |
| WDC WD7501AALS-00E3A0 752GB                  | 1        | 1      | 2.86%   |
| WDC WD7500AAKS-00RBA0 752GB                  | 1        | 2      | 2.86%   |
| WDC WD5002AALX-00J37A0 500GB                 | 1        | 2      | 2.86%   |
| WDC WD5000AAKX-001CA0 500GB                  | 1        | 1      | 2.86%   |
| WDC WD3200AAKS-00V1A0 320GB                  | 1        | 1      | 2.86%   |
| WDC WD2500KS-00MJB0 250GB                    | 1        | 1      | 2.86%   |
| WDC WD2500BEVT-60ZCT1 250GB                  | 1        | 3      | 2.86%   |
| WDC WD20EARX-008FB0 2TB                      | 1        | 1      | 2.86%   |
| WDC WD2005FBYZ-01YCBB3 2TB                   | 1        | 1      | 2.86%   |
| WDC WD1003FBYX-01Y7B0 1TB                    | 1        | 1      | 2.86%   |
| Toshiba DT01ACA050 500GB                     | 1        | 1      | 2.86%   |
| Seagate STM3500418AS 500GB                   | 1        | 1      | 2.86%   |
| Seagate ST9500530NS 42D0743 42D0746IBM 500GB | 1        | 1      | 2.86%   |
| Seagate ST9250315AS 250GB                    | 1        | 1      | 2.86%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 1      | 2.86%   |
| Seagate ST380815AS 80GB                      | 1        | 1      | 2.86%   |
| Seagate ST380811AS 80GB                      | 1        | 1      | 2.86%   |
| Seagate ST3320418AS 320GB                    | 1        | 1      | 2.86%   |
| Seagate ST32000641AS 2TB                     | 1        | 2      | 2.86%   |
| Seagate ST3000DM001-1CH166 3TB               | 1        | 1      | 2.86%   |
| Seagate ST250DM000-1BD141 250GB              | 1        | 2      | 2.86%   |
| Seagate ST1000DL004 HD105SI 1TB              | 1        | 1      | 2.86%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1        | 1      | 2.86%   |
| Samsung Electronics HD250HJ 250GB            | 1        | 1      | 2.86%   |
| OCZ VECTOR150 240GB SSD                      | 1        | 1      | 2.86%   |
| Netac SSD 480GB                              | 1        | 1      | 2.86%   |
| Hitachi HUA722010CLA330 1TB                  | 1        | 1      | 2.86%   |
| Hitachi HTS545050KTA300 500GB                | 1        | 2      | 2.86%   |
| Hitachi HDS723020BLA642 2TB                  | 1        | 1      | 2.86%   |
| Hitachi HDS721025CLA382 250GB                | 1        | 1      | 2.86%   |
| DEPO SM3DT-120 120GB SSD                     | 1        | 1      | 2.86%   |
| Corsair Force LS SSD 240GB                   | 1        | 3      | 2.86%   |
| AMD R3SL240G 240GB SSD                       | 1        | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 13     | 31.43%  |
| WDC                 | 10       | 14     | 28.57%  |
| Hitachi             | 4        | 5      | 11.43%  |
| XrayDisk            | 2        | 2      | 5.71%   |
| Samsung Electronics | 2        | 2      | 5.71%   |
| Toshiba             | 1        | 1      | 2.86%   |
| OCZ                 | 1        | 1      | 2.86%   |
| Netac               | 1        | 1      | 2.86%   |
| DEPO                | 1        | 1      | 2.86%   |
| Corsair             | 1        | 3      | 2.86%   |
| AMD                 | 1        | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 13     | 40.74%  |
| WDC                 | 10       | 14     | 37.04%  |
| Hitachi             | 4        | 5      | 14.81%  |
| Toshiba             | 1        | 1      | 3.7%    |
| Samsung Electronics | 1        | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 34     | 75%     |
| SSD  | 8        | 10     | 25%     |

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
| Works    | 203      | 362    | 64.44%  |
| Detected | 79       | 169    | 25.08%  |
| Malfunc  | 31       | 44     | 9.84%   |
| Failed   | 2        | 2      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 209      | 54.57%  |
| AMD                          | 63       | 16.45%  |
| Samsung Electronics          | 30       | 7.83%   |
| Nvidia                       | 11       | 2.87%   |
| Phison Electronics           | 9        | 2.35%   |
| JMicron Technology           | 9        | 2.35%   |
| Kingston Technology Company  | 6        | 1.57%   |
| ASMedia Technology           | 6        | 1.57%   |
| Silicon Motion               | 5        | 1.31%   |
| Realtek Semiconductor        | 5        | 1.31%   |
| Marvell Technology Group     | 5        | 1.31%   |
| Broadcom / LSI               | 5        | 1.31%   |
| SanDisk                      | 4        | 1.04%   |
| Micron Technology            | 3        | 0.78%   |
| MCST                         | 3        | 0.78%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.52%   |
| ADATA Technology             | 2        | 0.52%   |
| Zhaoxin                      | 1        | 0.26%   |
| VIA Technologies             | 1        | 0.26%   |
| Toshiba America Info Systems | 1        | 0.26%   |
| Micron/Crucial Technology    | 1        | 0.26%   |
| LSI Logic / Symbios Logic    | 1        | 0.26%   |
| Hosin Global Electronics     | 1        | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 71       | 15.33%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 41       | 8.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 18       | 3.89%   |
| AMD 400 Series Chipset SATA Controller                                                  | 18       | 3.89%   |
| AMD 500 Series Chipset SATA Controller                                                  | 16       | 3.46%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 14       | 3.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 2.81%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 2.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9        | 1.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 1.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 1.51%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 7        | 1.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 1.51%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 1.3%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 1.3%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 5        | 1.08%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 1.08%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.08%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 5        | 1.08%   |
| AMD FCH SATA Controller D                                                               | 5        | 1.08%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4        | 0.86%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 4        | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 4        | 0.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4        | 0.86%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.65%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 3        | 0.65%   |
| MCST SATA                                                                               | 3        | 0.65%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 3        | 0.65%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 3        | 0.65%   |
| JMicron JMB368 IDE controller                                                           | 3        | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.65%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 0.65%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 0.65%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 0.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 237      | 63.03%  |
| IDE  | 65       | 17.29%  |
| NVMe | 64       | 17.02%  |
| RAID | 5        | 1.33%   |
| SAS  | 5        | 1.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 211      | 73.01%  |
| AMD          | 73       | 25.26%  |
| Elbrus-MCST  | 1        | 0.35%   |
| EL2S4        | 1        | 0.35%   |
| E8C/EATX     | 1        | 0.35%   |
| E8C-SWTX     | 1        | 0.35%   |
| CentaurHauls | 1        | 0.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-6100TE CPU @ 2.70GHz          | 46       | 15.81%  |
| AMD Ryzen 5 1600 Six-Core Processor         | 14       | 4.81%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 10       | 3.44%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 5        | 1.72%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 5        | 1.72%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 1.72%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 5        | 1.72%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GHz          | 4        | 1.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4        | 1.37%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4        | 1.37%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 1.37%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.03%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3        | 1.03%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 1.03%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.03%   |
| Intel Celeron CPU G3900 @ 2.80GHz           | 3        | 1.03%   |
| AMD Ryzen 5 5600 6-Core Processor           | 3        | 1.03%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 2        | 0.69%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 2        | 0.69%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 2        | 0.69%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 2        | 0.69%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2        | 0.69%   |
| Intel Genuine CPU 0000 @ 2.40GHz            | 2        | 0.69%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 2        | 0.69%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.69%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.69%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2        | 0.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.69%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 0.69%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.69%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 2        | 0.69%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 0.69%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2        | 0.69%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 0.69%   |
| Intel 11th Gen Core i5-11500 @ 2.70GHz      | 2        | 0.69%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 0.69%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 0.69%   |
| AMD Athlon 64 X2 Dual Core Processor 4800+  | 2        | 0.69%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 2        | 0.69%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 2        | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 75       | 25.86%  |
| Intel Core i5           | 31       | 10.69%  |
| AMD Ryzen 5             | 27       | 9.31%   |
| Other                   | 19       | 6.55%   |
| Intel Pentium           | 15       | 5.17%   |
| Intel Xeon              | 13       | 4.48%   |
| Intel Celeron           | 13       | 4.48%   |
| Intel Core i7           | 12       | 4.14%   |
| AMD Ryzen 7             | 11       | 3.79%   |
| Intel Core 2 Duo        | 9        | 3.1%    |
| Intel Pentium Dual-Core | 8        | 2.76%   |
| Intel Core 2 Quad       | 6        | 2.07%   |
| AMD A10                 | 5        | 1.72%   |
| Intel Core i9           | 4        | 1.38%   |
| AMD Athlon 64 X2        | 4        | 1.38%   |
| Intel Pentium Gold      | 3        | 1.03%   |
| Intel Genuine           | 3        | 1.03%   |
| AMD Athlon II X2        | 3        | 1.03%   |
| AMD Athlon              | 3        | 1.03%   |
| AMD A8                  | 3        | 1.03%   |
| Intel Core 2            | 2        | 0.69%   |
| AMD Ryzen 9             | 2        | 0.69%   |
| AMD Ryzen 3             | 2        | 0.69%   |
| AMD Phenom II X4        | 2        | 0.69%   |
| AMD FX                  | 2        | 0.69%   |
| AMD Athlon II X4        | 2        | 0.69%   |
| AMD A6                  | 2        | 0.69%   |
| Intel Pentium D         | 1        | 0.34%   |
| Intel Pentium 4         | 1        | 0.34%   |
| Intel Celeron D         | 1        | 0.34%   |
| AMD Sempron             | 1        | 0.34%   |
| AMD Ryzen 7 PRO         | 1        | 0.34%   |
| AMD Ryzen 5 PRO         | 1        | 0.34%   |
| AMD Ryzen 3 PRO         | 1        | 0.34%   |
| AMD Phenom II X6        | 1        | 0.34%   |
| AMD Athlon 64           | 1        | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 130      | 44.83%  |
| 4      | 71       | 24.48%  |
| 6      | 44       | 15.17%  |
| 8      | 22       | 7.59%   |
| 16     | 7        | 2.41%   |
| 1      | 6        | 2.07%   |
| 12     | 3        | 1.03%   |
| 18     | 2        | 0.69%   |
| 3      | 2        | 0.69%   |
| 32     | 1        | 0.34%   |
| 14     | 1        | 0.34%   |
| 10     | 1        | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 281      | 97.23%  |
| 2      | 6        | 2.08%   |
| 4      | 2        | 0.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 192      | 66.44%  |
| 1      | 97       | 33.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 284      | 98.27%  |
| Unknown        | 4        | 1.38%   |
| 32-bit         | 1        | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 82       | 28.18%  |
| 0x506e3    | 53       | 18.21%  |
| 0x1067a    | 16       | 5.5%    |
| 0x08001138 | 14       | 4.81%   |
| 0x906e9    | 13       | 4.47%   |
| 0xa0653    | 9        | 3.09%   |
| 0xa0671    | 7        | 2.41%   |
| 0x306c3    | 7        | 2.41%   |
| 0x0a50000c | 7        | 2.41%   |
| 0x906eb    | 6        | 2.06%   |
| 0x906ea    | 5        | 1.72%   |
| 0x08108109 | 5        | 1.72%   |
| 0x806c1    | 4        | 1.37%   |
| 0x306a9    | 4        | 1.37%   |
| 0x206d7    | 4        | 1.37%   |
| 0x806e9    | 3        | 1.03%   |
| 0x206a7    | 3        | 1.03%   |
| 0x06001119 | 3        | 1.03%   |
| 0x906ed    | 2        | 0.69%   |
| 0x806ec    | 2        | 0.69%   |
| 0x306e4    | 2        | 0.69%   |
| 0x30679    | 2        | 0.69%   |
| 0x20655    | 2        | 0.69%   |
| 0x0a50000d | 2        | 0.69%   |
| 0x0a20120a | 2        | 0.69%   |
| 0x08701021 | 2        | 0.69%   |
| 0x010000db | 2        | 0.69%   |
| 0x010000c8 | 2        | 0.69%   |
| 0x00000000 | 2        | 0.69%   |
| 0xf47      | 1        | 0.34%   |
| 0xf29      | 1        | 0.34%   |
| 0xa0655    | 1        | 0.34%   |
| 0x90675    | 1        | 0.34%   |
| 0x6fd      | 1        | 0.34%   |
| 0x6fb      | 1        | 0.34%   |
| 0x6f6      | 1        | 0.34%   |
| 0x506e8    | 1        | 0.34%   |
| 0x506c9    | 1        | 0.34%   |
| 0x50657    | 1        | 0.34%   |
| 0x50654    | 1        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Skylake     | 61       | 21.03%  |
| KabyLake    | 37       | 12.76%  |
| Penryn      | 21       | 7.24%   |
| Zen 3       | 17       | 5.86%   |
| Zen         | 16       | 5.52%   |
| SandyBridge | 16       | 5.52%   |
| CometLake   | 16       | 5.52%   |
| Unknown     | 16       | 5.52%   |
| IvyBridge   | 12       | 4.14%   |
| Haswell     | 11       | 3.79%   |
| K10         | 9        | 3.1%    |
| Zen+        | 8        | 2.76%   |
| Piledriver  | 6        | 2.07%   |
| K8 Hammer   | 6        | 2.07%   |
| Core        | 6        | 2.07%   |
| Westmere    | 5        | 1.72%   |
| Zen 2       | 4        | 1.38%   |
| TigerLake   | 4        | 1.38%   |
| Steamroller | 4        | 1.38%   |
| Silvermont  | 4        | 1.38%   |
| NetBurst    | 3        | 1.03%   |
| Icelake     | 3        | 1.03%   |
| Nehalem     | 2        | 0.69%   |
| K10 Llano   | 1        | 0.34%   |
| Goldmont    | 1        | 0.34%   |
| Excavator   | 1        | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 141      | 47.16%  |
| Nvidia                     | 84       | 28.09%  |
| AMD                        | 64       | 21.4%   |
| Matrox Electronics Systems | 4        | 1.34%   |
| Silicon Motion             | 3        | 1%      |
| ASPEED Technology          | 2        | 0.67%   |
| Zhaoxin                    | 1        | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                       | 53       | 17.26%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 19       | 6.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 11       | 3.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 3.58%   |
| Intel HD Graphics 610                                                       | 10       | 3.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9        | 2.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7        | 2.28%   |
| Intel HD Graphics 510                                                       | 5        | 1.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 1.63%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 5        | 1.63%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 1.3%    |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.3%    |
| Matrox Electronics Systems MGA G200EH                                       | 4        | 1.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4        | 1.3%    |
| Intel HD Graphics 620                                                       | 4        | 1.3%    |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 1.3%    |
| Silicon Motion SM718 LynxSE+                                                | 3        | 0.98%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.98%   |
| Nvidia GF119 [GeForce GT 610]                                               | 3        | 0.98%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.98%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3        | 0.98%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 3        | 0.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 0.98%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3        | 0.98%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.65%   |
| Nvidia GK107 [GeForce GT 640]                                               | 2        | 0.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 0.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 0.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2        | 0.65%   |
| Intel HD Graphics 630                                                       | 2        | 0.65%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 2        | 0.65%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 0.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 0.65%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 2        | 0.65%   |
| ASPEED Technology ASPEED Graphics Family                                    | 2        | 0.65%   |
| AMD RV530 [Radeon X1600] (Secondary)                                        | 2        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 134      | 46.05%  |
| 1 x Nvidia         | 80       | 27.49%  |
| 1 x AMD            | 55       | 18.9%   |
| 2 x AMD            | 6        | 2.06%   |
| 1 x Matrox         | 4        | 1.37%   |
| 1 x Silicon Motion | 3        | 1.03%   |
| Other              | 2        | 0.69%   |
| Intel + Nvidia     | 2        | 0.69%   |
| 1 x ASPEED         | 2        | 0.69%   |
| Nvidia + Zhaoxin   | 1        | 0.34%   |
| Intel + AMD        | 1        | 0.34%   |
| AMD + Nvidia       | 1        | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 224      | 76.98%  |
| Proprietary | 55       | 18.9%   |
| Unknown     | 12       | 4.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 182      | 62.33%  |
| 3.01-4.0   | 26       | 8.9%    |
| 1.01-2.0   | 24       | 8.22%   |
| 0.01-0.5   | 24       | 8.22%   |
| 0.51-1.0   | 21       | 7.19%   |
| 7.01-8.0   | 6        | 2.05%   |
| 8.01-16.0  | 5        | 1.71%   |
| 5.01-6.0   | 3        | 1.03%   |
| 2.01-3.0   | 1        | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| HHT                  | 47       | 15.88%  |
| Samsung Electronics  | 38       | 12.84%  |
| Acer                 | 34       | 11.49%  |
| AOC                  | 29       | 9.8%    |
| BenQ                 | 27       | 9.12%   |
| Goldstar             | 20       | 6.76%   |
| Philips              | 19       | 6.42%   |
| Dell                 | 13       | 4.39%   |
| ViewSonic            | 9        | 3.04%   |
| Hewlett-Packard      | 7        | 2.36%   |
| Ancor Communications | 7        | 2.36%   |
| PRW                  | 4        | 1.35%   |
| Iiyama               | 4        | 1.35%   |
| WBT                  | 3        | 1.01%   |
| RTK                  | 3        | 1.01%   |
| LG Electronics       | 3        | 1.01%   |
| ASUSTek Computer     | 3        | 1.01%   |
| STD                  | 2        | 0.68%   |
| NEC Computers        | 2        | 0.68%   |
| MSI                  | 2        | 0.68%   |
| Unknown              | 2        | 0.68%   |
| XYK                  | 1        | 0.34%   |
| XHS                  | 1        | 0.34%   |
| VIE                  | 1        | 0.34%   |
| Toshiba              | 1        | 0.34%   |
| SKM                  | 1        | 0.34%   |
| SKG                  | 1        | 0.34%   |
| Plain Tree Systems   | 1        | 0.34%   |
| Lenovo               | 1        | 0.34%   |
| JRY                  | 1        | 0.34%   |
| IPS                  | 1        | 0.34%   |
| HVR                  | 1        | 0.34%   |
| HIB                  | 1        | 0.34%   |
| HannStar             | 1        | 0.34%   |
| Haier                | 1        | 0.34%   |
| DZW                  | 1        | 0.34%   |
| CHD                  | 1        | 0.34%   |
| Apple                | 1        | 0.34%   |
| Aosiman              | 1        | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch               | 47       | 15.31%  |
| AOC LCD Monitor 2778X 2560x1440                                       | 11       | 3.58%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                     | 10       | 3.26%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 7        | 2.28%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 5        | 1.63%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 4        | 1.3%    |
| PRW AP7_Titanium PRW4200 3840x2160                                    | 4        | 1.3%    |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                      | 3        | 0.98%   |
| RTK HDMI RTK2380 1920x1080 530x290mm 23.8-inch                        | 3        | 0.98%   |
| AOC 22B1WG5 AOC2201 1920x1080 479x260mm 21.5-inch                     | 3        | 0.98%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 2        | 0.65%   |
| STD Monitor STD0001 1920x1080                                         | 2        | 0.65%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 2        | 0.65%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 2        | 0.65%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 477x268mm 21.5-inch    | 2        | 0.65%   |
| Samsung Electronics S22E391 SAM0C0E 1920x1080 477x268mm 21.5-inch     | 2        | 0.65%   |
| Goldstar W2261 GSM56CF 1920x1080 477x268mm 21.5-inch                  | 2        | 0.65%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                | 2        | 0.65%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                    | 2        | 0.65%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2        | 0.65%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 2        | 0.65%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 2        | 0.65%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 2        | 0.65%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                      | 2        | 0.65%   |
| AOC 2475W AOC2475 1920x1080 527x296mm 23.8-inch                       | 2        | 0.65%   |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                      | 2        | 0.65%   |
| Ancor Communications ASUS VS229 ACI22C2 1920x1080 477x268mm 21.5-inch | 2        | 0.65%   |
| Acer G227HQL ACR03DE 1920x1080 476x267mm 21.5-inch                    | 2        | 0.65%   |
| Unknown                                                               | 2        | 0.65%   |
| XYK DVI XYK2360 1920x1080 477x268mm 21.5-inch                         | 1        | 0.33%   |
| XHS N221 XHSA215 1920x1080 480x260mm 21.5-inch                        | 1        | 0.33%   |
| ViewSonic VX2451 SERIES VSC2528 1920x1080 521x293mm 23.5-inch         | 1        | 0.33%   |
| ViewSonic VX2409 SERIES VSC6C2E 1920x1080 521x293mm 23.5-inch         | 1        | 0.33%   |
| ViewSonic VA1916wSERIES VSCF91F 1440x900 410x256mm 19.0-inch          | 1        | 0.33%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 0.33%   |
| Toshiba LCD Monitor TV 1920x1080                                      | 1        | 0.33%   |
| SKM T24 Air SKM9322 1920x1080 519x324mm 24.1-inch                     | 1        | 0.33%   |
| SKG 86 Monitor SKG8600 3840x2160 1895x1066mm 85.6-inch                | 1        | 0.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM0611 1920x1080 600x340mm 27.2-inch  | 1        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 126      | 43.75%  |
| 3840x2160 (4K)     | 62       | 21.53%  |
| 2560x1440 (QHD)    | 29       | 10.07%  |
| 1280x1024 (SXGA)   | 24       | 8.33%   |
| 1680x1050 (WSXGA+) | 12       | 4.17%   |
| 1600x900 (HD+)     | 6        | 2.08%   |
| 1440x900 (WXGA+)   | 5        | 1.74%   |
| Unknown            | 5        | 1.74%   |
| 1366x768 (WXGA)    | 3        | 1.04%   |
| 1360x768           | 3        | 1.04%   |
| 3840x1080          | 2        | 0.69%   |
| 1920x1200 (WUXGA)  | 2        | 0.69%   |
| 1600x1200          | 2        | 0.69%   |
| 4480x1440          | 1        | 0.35%   |
| 3840x1600          | 1        | 0.35%   |
| 3840x1440          | 1        | 0.35%   |
| 2560x1080          | 1        | 0.35%   |
| 2160x1200          | 1        | 0.35%   |
| 1280x720 (HD)      | 1        | 0.35%   |
| 1024x768 (XGA)     | 1        | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 40      | 49       | 16.78%  |
| 24      | 46       | 15.75%  |
| 21      | 45       | 15.41%  |
| 23      | 36       | 12.33%  |
| Unknown | 31       | 10.62%  |
| 27      | 21       | 7.19%   |
| 19      | 18       | 6.16%   |
| 17      | 12       | 4.11%   |
| 22      | 6        | 2.05%   |
| 31      | 5        | 1.71%   |
| 20      | 5        | 1.71%   |
| 18      | 5        | 1.71%   |
| 26      | 3        | 1.03%   |
| 85      | 1        | 0.34%   |
| 72      | 1        | 0.34%   |
| 52      | 1        | 0.34%   |
| 46      | 1        | 0.34%   |
| 39      | 1        | 0.34%   |
| 37      | 1        | 0.34%   |
| 33      | 1        | 0.34%   |
| 32      | 1        | 0.34%   |
| 28      | 1        | 0.34%   |
| 15      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 99       | 34.62%  |
| 401-500     | 65       | 22.73%  |
| 901-1000    | 48       | 16.78%  |
| Unknown     | 31       | 10.84%  |
| 301-350     | 13       | 4.55%   |
| 351-400     | 11       | 3.85%   |
| 601-700     | 10       | 3.5%    |
| 801-900     | 3        | 1.05%   |
| 701-800     | 2        | 0.7%    |
| 1501-2000   | 2        | 0.7%    |
| 1001-1500   | 2        | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 154      | 55.6%   |
| 21/9    | 49       | 17.69%  |
| Unknown | 26       | 9.39%   |
| 5/4     | 23       | 8.3%    |
| 16/10   | 20       | 7.22%   |
| 4/3     | 4        | 1.44%   |
| 3/2     | 1        | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 110      | 39.01%  |
| 501-1000       | 52       | 18.44%  |
| 151-200        | 33       | 11.7%   |
| Unknown        | 31       | 10.99%  |
| 301-350        | 24       | 8.51%   |
| 141-150        | 15       | 5.32%   |
| 351-500        | 8        | 2.84%   |
| 251-300        | 5        | 1.77%   |
| More than 1000 | 3        | 1.06%   |
| 101-110        | 1        | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 136      | 47.72%  |
| 101-120 | 98       | 34.39%  |
| Unknown | 31       | 10.88%  |
| 121-160 | 14       | 4.91%   |
| 1-50    | 5        | 1.75%   |
| 161-240 | 1        | 0.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 245      | 83.62%  |
| 2     | 30       | 10.24%  |
| 0     | 17       | 5.8%    |
| 3     | 1        | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 217      | 56.81%  |
| Intel                      | 104      | 27.23%  |
| Qualcomm Atheros           | 18       | 4.71%   |
| Nvidia                     | 10       | 2.62%   |
| TP-Link                    | 4        | 1.05%   |
| Ralink Technology          | 4        | 1.05%   |
| Marvell Technology Group   | 4        | 1.05%   |
| Ralink                     | 3        | 0.79%   |
| Microchip Technology       | 3        | 0.79%   |
| MCST                       | 3        | 0.79%   |
| VIA Technologies           | 2        | 0.52%   |
| U-Blox                     | 2        | 0.52%   |
| ZTE WCDMA Technologies MSM | 1        | 0.26%   |
| Xiaomi                     | 1        | 0.26%   |
| Vimtron Electronics        | 1        | 0.26%   |
| MediaTek                   | 1        | 0.26%   |
| D-Link System              | 1        | 0.26%   |
| D-Link                     | 1        | 0.26%   |
| Broadcom Limited           | 1        | 0.26%   |
| ASUSTek Computer           | 1        | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 144      | 33.96%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 47       | 11.08%  |
| Intel Ethernet Connection I219-LM                                 | 35       | 8.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 4.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 2.12%   |
| Intel Ethernet Connection (14) I219-V                             | 8        | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 1.65%   |
| Intel Wireless 3165                                               | 7        | 1.65%   |
| Intel I350 Gigabit Network Connection                             | 5        | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 0.94%   |
| Intel I211 Gigabit Network Connection                             | 4        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 0.94%   |
| Intel Ethernet Connection (13) I219-V                             | 4        | 0.94%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3        | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3        | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.71%   |
| Realtek 802.11ac NIC                                              | 3        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.71%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.71%   |
| Nvidia MCP77 Ethernet                                             | 3        | 0.71%   |
| Microchip MCP2221(a) UART/I2C Bridge                              | 3        | 0.71%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 0.71%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 0.71%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3        | 0.71%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.71%   |
| U-Blox [u-blox 7]                                                 | 2        | 0.47%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2        | 0.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2        | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.47%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.47%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.47%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.47%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 36.21%  |
| Intel                 | 21       | 36.21%  |
| TP-Link               | 4        | 6.9%    |
| Ralink Technology     | 4        | 6.9%    |
| Ralink                | 3        | 5.17%   |
| Qualcomm Atheros      | 3        | 5.17%   |
| MediaTek              | 1        | 1.72%   |
| ASUSTek Computer      | 1        | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                        | 7        | 12.07%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 4        | 6.9%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 3        | 5.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 3        | 5.17%   |
| Realtek 802.11ac NIC                                       | 3        | 5.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 3        | 5.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 3        | 5.17%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 2        | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2        | 3.45%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 2        | 3.45%   |
| Ralink MT7601U Wireless Adapter                            | 2        | 3.45%   |
| Intel Wireless-AC 9260                                     | 2        | 3.45%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2        | 3.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1        | 1.72%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 1.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1        | 1.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 1        | 1.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1        | 1.72%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 1.72%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter          | 1        | 1.72%   |
| Ralink RT5392 PCIe Wireless Network Adapter                | 1        | 1.72%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                       | 1        | 1.72%   |
| Ralink RT2561/RT61 rev B 802.11g                           | 1        | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 1.72%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 1.72%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 1        | 1.72%   |
| Intel Wireless 7265                                        | 1        | 1.72%   |
| Intel Wi-Fi 6 AX200                                        | 1        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1        | 1.72%   |
| Intel Centrino Wireless-N 2230                             | 1        | 1.72%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]  | 1        | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 214      | 60.8%   |
| Intel                      | 97       | 27.56%  |
| Qualcomm Atheros           | 15       | 4.26%   |
| Nvidia                     | 10       | 2.84%   |
| Marvell Technology Group   | 4        | 1.14%   |
| MCST                       | 3        | 0.85%   |
| VIA Technologies           | 2        | 0.57%   |
| ZTE WCDMA Technologies MSM | 1        | 0.28%   |
| Xiaomi                     | 1        | 0.28%   |
| Vimtron Electronics        | 1        | 0.28%   |
| TP-Link                    | 1        | 0.28%   |
| D-Link System              | 1        | 0.28%   |
| D-Link                     | 1        | 0.28%   |
| Broadcom Limited           | 1        | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 144      | 40%     |
| Realtek RTL8152 Fast Ethernet Adapter                             | 47       | 13.06%  |
| Intel Ethernet Connection I219-LM                                 | 35       | 9.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 5%      |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 2.5%    |
| Intel Ethernet Connection (14) I219-V                             | 8        | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 1.94%   |
| Intel I350 Gigabit Network Connection                             | 5        | 1.39%   |
| Intel I211 Gigabit Network Connection                             | 4        | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.11%   |
| Intel Ethernet Connection (13) I219-V                             | 4        | 1.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.83%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 0.83%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.83%   |
| Nvidia MCP77 Ethernet                                             | 3        | 0.83%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.83%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 0.83%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 0.83%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.83%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.56%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.56%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.56%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.56%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.56%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 2        | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.56%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 1        | 0.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.28%   |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.28%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.28%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.28%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.28%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.28%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 0.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 288      | 81.82%  |
| WiFi     | 58       | 16.48%  |
| Modem    | 5        | 1.42%   |
| Unknown  | 1        | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 260      | 89.35%  |
| WiFi     | 31       | 10.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 231      | 79.93%  |
| 2     | 51       | 17.65%  |
| 3     | 3        | 1.04%   |
| 13    | 1        | 0.35%   |
| 8     | 1        | 0.35%   |
| 4     | 1        | 0.35%   |
| 0     | 1        | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 282      | 97.24%  |
| Yes  | 8        | 2.76%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 20       | 40.82%  |
| Cambridge Silicon Radio  | 13       | 26.53%  |
| Realtek Semiconductor    | 5        | 10.2%   |
| IMC Networks             | 3        | 6.12%   |
| Broadcom                 | 2        | 4.08%   |
| ASUSTek Computer         | 2        | 4.08%   |
| Realtek                  | 1        | 2.04%   |
| MediaTek                 | 1        | 2.04%   |
| Logitech                 | 1        | 2.04%   |
| HTC (High Tech Computer) | 1        | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 13       | 26.53%  |
| Intel Bluetooth wireless interface                                   | 11       | 22.45%  |
| Realtek Bluetooth Radio                                              | 4        | 8.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 4.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 4.08%   |
| Intel AX210 Bluetooth                                                | 2        | 4.08%   |
| IMC Networks Bluetooth Radio                                         | 2        | 4.08%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 2.04%   |
| Realtek Bluetooth Radio                                              | 1        | 2.04%   |
| MediaTek Wireless_Device                                             | 1        | 2.04%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 1        | 2.04%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 2.04%   |
| Intel AX201 Bluetooth                                                | 1        | 2.04%   |
| Intel AX200 Bluetooth                                                | 1        | 2.04%   |
| IMC Networks Bluetooth Device                                        | 1        | 2.04%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 2.04%   |
| Broadcom Bluetooth dongle                                            | 1        | 2.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 2.04%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 2.04%   |
| ASUS 2045 Bluetooth 2.0 Device with trace filter                     | 1        | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 201      | 50%     |
| AMD                    | 84       | 20.9%   |
| Nvidia                 | 80       | 19.9%   |
| C-Media Electronics    | 7        | 1.74%   |
| JMTek                  | 4        | 1%      |
| Creative Technology    | 4        | 1%      |
| MCST                   | 3        | 0.75%   |
| FIFINE Microphones     | 2        | 0.5%    |
| Creative Labs          | 2        | 0.5%    |
| Zhaoxin                | 1        | 0.25%   |
| VIA Technologies       | 1        | 0.25%   |
| Texas Instruments      | 1        | 0.25%   |
| Tenx Technology        | 1        | 0.25%   |
| Logitech               | 1        | 0.25%   |
| KTMicro                | 1        | 0.25%   |
| Goldvish               | 1        | 0.25%   |
| Generalplus Technology | 1        | 0.25%   |
| Focusrite-Novation     | 1        | 0.25%   |
| EasyPass Industrial    | 1        | 0.25%   |
| DSEA A/S               | 1        | 0.25%   |
| Cirrus Logic           | 1        | 0.25%   |
| ASUSTek Computer       | 1        | 0.25%   |
| Apple                  | 1        | 0.25%   |
| A4Tech                 | 1        | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 71       | 15.85%  |
| Nvidia GP107GL High Definition Audio Controller                            | 21       | 4.69%   |
| AMD Family 17h/19h HD Audio Controller                                     | 20       | 4.46%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16       | 3.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13       | 2.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13       | 2.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 12       | 2.68%   |
| Intel 200 Series PCH HD Audio                                              | 11       | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 2.01%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 2.01%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 9        | 2.01%   |
| AMD FCH Azalia Controller                                                  | 9        | 2.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 1.79%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 8        | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 1.56%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 1.34%   |
| Intel Comet Lake PCH-V cAVS                                                | 6        | 1.34%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 1.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5        | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 0.89%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 4        | 0.89%   |
| Nvidia High Definition Audio Controller                                    | 4        | 0.89%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 0.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4        | 0.89%   |
| Intel Sunrise Point-LP HD Audio                                            | 4        | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4        | 0.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.89%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4        | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4        | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 0.67%   |
| Nvidia GF116 High Definition Audio Controller                              | 3        | 0.67%   |
| MCST HD Audio                                                              | 3        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 36       | 18.18%  |
| Crucial             | 35       | 17.68%  |
| Kingston            | 30       | 15.15%  |
| Samsung Electronics | 18       | 9.09%   |
| Micron Technology   | 14       | 7.07%   |
| Apacer              | 8        | 4.04%   |
| SK hynix            | 7        | 3.54%   |
| Patriot             | 5        | 2.53%   |
| Foxline             | 5        | 2.53%   |
| Corsair             | 5        | 2.53%   |
| A-DATA Technology   | 5        | 2.53%   |
| Hewlett-Packard     | 4        | 2.02%   |
| Unknown             | 4        | 2.02%   |
| GOODRAM             | 3        | 1.52%   |
| AMD                 | 3        | 1.52%   |
| Ramaxel Technology  | 2        | 1.01%   |
| Goldkey             | 2        | 1.01%   |
| G.Skill             | 2        | 1.01%   |
| Wilk                | 1        | 0.51%   |
| Unknown (0x7FFF)    | 1        | 0.51%   |
| Unknown (0x0B7A)    | 1        | 0.51%   |
| Unknown (081A)      | 1        | 0.51%   |
| tigo                | 1        | 0.51%   |
| Shenzhen Longsys    | 1        | 0.51%   |
| Qumo                | 1        | 0.51%   |
| Juhor               | 1        | 0.51%   |
| Golden Empire       | 1        | 0.51%   |
| Elpida              | 1        | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s   | 13       | 6.07%   |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s               | 10       | 4.67%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 4        | 1.87%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s | 4        | 1.87%   |
| HP RAM Module 4GB DIMM DDR3 1333MT/s                   | 4        | 1.87%   |
| Unknown                                                | 4        | 1.87%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s   | 3        | 1.4%    |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s | 3        | 1.4%    |
| Apacer RAM D12.2755BS.001 16GB DIMM DDR4 3200MT/s      | 3        | 1.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 0.93%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 2        | 0.93%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 2        | 0.93%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 2        | 0.93%   |
| Unknown RAM Module 1024MB DIMM                         | 2        | 0.93%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s  | 2        | 0.93%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 2        | 0.93%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s   | 2        | 0.93%   |
| Samsung RAM M378A1K43EB2-CVF 8GB DIMM DDR4 3266MT/s    | 2        | 0.93%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s         | 2        | 0.93%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 2        | 0.93%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s    | 2        | 0.93%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s  | 2        | 0.93%   |
| Foxline RAM FL2666D4S19-8G ]. 8GB SODIMM DDR4 2667MT/s | 2        | 0.93%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s | 2        | 0.93%   |
| Crucial RAM BL8G26C16U4R.8FD 8GB DIMM DDR4 3200MT/s    | 2        | 0.93%   |
| Apacer RAM D12.2324CC.001 8GB DIMM DDR4 2667MT/s       | 2        | 0.93%   |
| Wilk RAM IRX3000D464L16S/8G 8GB DIMM DDR4 3200MT/s     | 1        | 0.47%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s           | 1        | 0.47%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s              | 1        | 0.47%   |
| Unknown RAM Module 512MB DIMM 400MT/s                  | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.47%   |
| Unknown RAM Module 4096MB DIMM 333MT/s                 | 1        | 0.47%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s              | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s               | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                   | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM                            | 1        | 0.47%   |
| Unknown RAM Module 2048MB DIMM SDRAM 533MT/s           | 1        | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 112      | 61.2%   |
| DDR3    | 36       | 19.67%  |
| Unknown | 17       | 9.29%   |
| DDR2    | 9        | 4.92%   |
| SDRAM   | 5        | 2.73%   |
| DDR     | 3        | 1.64%   |
| DDR5    | 1        | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 164      | 89.62%  |
| SODIMM | 19       | 10.38%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 74       | 38.54%  |
| 4096  | 65       | 33.85%  |
| 2048  | 21       | 10.94%  |
| 16384 | 15       | 7.81%   |
| 1024  | 12       | 6.25%   |
| 512   | 3        | 1.56%   |
| 32768 | 2        | 1.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2400    | 40       | 20.2%   |
| 3200    | 24       | 12.12%  |
| 2667    | 20       | 10.1%   |
| 1600    | 18       | 9.09%   |
| 1333    | 16       | 8.08%   |
| 2133    | 13       | 6.57%   |
| 800     | 10       | 5.05%   |
| 2933    | 6        | 3.03%   |
| Unknown | 6        | 3.03%   |
| 667     | 5        | 2.53%   |
| 400     | 4        | 2.02%   |
| 3733    | 3        | 1.52%   |
| 3466    | 3        | 1.52%   |
| 3266    | 3        | 1.52%   |
| 1866    | 3        | 1.52%   |
| 533     | 3        | 1.52%   |
| 3066    | 2        | 1.01%   |
| 1066    | 2        | 1.01%   |
| 333     | 2        | 1.01%   |
| 5200    | 1        | 0.51%   |
| 4333    | 1        | 0.51%   |
| 3866    | 1        | 0.51%   |
| 3600    | 1        | 0.51%   |
| 3534    | 1        | 0.51%   |
| 3533    | 1        | 0.51%   |
| 3333    | 1        | 0.51%   |
| 3151    | 1        | 0.51%   |
| 2866    | 1        | 0.51%   |
| 2666    | 1        | 0.51%   |
| 2448    | 1        | 0.51%   |
| 1867    | 1        | 0.51%   |
| 1800    | 1        | 0.51%   |
| 1648    | 1        | 0.51%   |
| 32      | 1        | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 29.63%  |
| Canon               | 6        | 22.22%  |
| Hewlett-Packard     | 5        | 18.52%  |
| Pantum              | 3        | 11.11%  |
| QinHeng Electronics | 2        | 7.41%   |
| Seiko Epson         | 1        | 3.7%    |
| Kyocera             | 1        | 3.7%    |
| Brother Industries  | 1        | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| QinHeng CH340S                       | 2        | 7.41%   |
| HP LaserJet 1010                     | 2        | 7.41%   |
| Seiko Epson L132 Series              | 1        | 3.7%    |
| Samsung SCX-4200 series              | 1        | 3.7%    |
| Samsung SCX-4100 Scanner             | 1        | 3.7%    |
| Samsung SCX-3400 Series              | 1        | 3.7%    |
| Samsung SCX-3200 Series              | 1        | 3.7%    |
| Samsung ML-2010P Mono Laser Printer  | 1        | 3.7%    |
| Samsung ML-1640 Series Laser Printer | 1        | 3.7%    |
| Samsung M332x 382x 402x Series       | 1        | 3.7%    |
| Samsung CLX-3180 Series              | 1        | 3.7%    |
| Pantum P2200 series                  | 1        | 3.7%    |
| Pantum M6500W series                 | 1        | 3.7%    |
| Pantum M6500-series                  | 1        | 3.7%    |
| Kyocera FS-1135MFP                   | 1        | 3.7%    |
| HP LaserJet P1102                    | 1        | 3.7%    |
| HP LaserJet M402dn                   | 1        | 3.7%    |
| HP LaserJet 3055                     | 1        | 3.7%    |
| Canon MF4410                         | 1        | 3.7%    |
| Canon MF420 Series                   | 1        | 3.7%    |
| Canon MF4010 series                  | 1        | 3.7%    |
| Canon MF3110                         | 1        | 3.7%    |
| Canon G3010 series                   | 1        | 3.7%    |
| Canon G1010 series                   | 1        | 3.7%    |
| Brother DCP-7030                     | 1        | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 3        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 2        | 66.67%  |
| Canon CanoScan LIDE 25  | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 22       | 47.83%  |
| Alcor Micro                   | 7        | 15.22%  |
| Sunplus Innovation Technology | 3        | 6.52%   |
| Microdia                      | 3        | 6.52%   |
| Microsoft                     | 2        | 4.35%   |
| Apple                         | 2        | 4.35%   |
| Z-Star Microelectronics       | 1        | 2.17%   |
| Unknown                       | 1        | 2.17%   |
| lihappe8                      | 1        | 2.17%   |
| Hewlett-Packard               | 1        | 2.17%   |
| GEMBIRD                       | 1        | 2.17%   |
| A4Tech                        | 1        | 2.17%   |
| Unknown                       | 1        | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 12       | 26.09%  |
| Alcor Micro USB 2.0 PC Camera                     | 5        | 10.87%  |
| Sunplus USB Microphone                            | 3        | 6.52%   |
| Microdia Camera                                   | 3        | 6.52%   |
| Logitech HD Pro Webcam C920                       | 2        | 4.35%   |
| Logitech C505 HD Webcam                           | 2        | 4.35%   |
| Alcor Micro USB 2.0 Camera                        | 2        | 4.35%   |
| Z-Star Venus USB2.0 Camera                        | 1        | 2.17%   |
| Unknown HD camera                                 | 1        | 2.17%   |
| Microsoft LifeCam VX-700                          | 1        | 2.17%   |
| Microsoft LifeCam HD-3000                         | 1        | 2.17%   |
| Logitech Webcam C930e                             | 1        | 2.17%   |
| Logitech Webcam C170                              | 1        | 2.17%   |
| Logitech HD Webcam C615                           | 1        | 2.17%   |
| Logitech HD Webcam C525                           | 1        | 2.17%   |
| Logitech BRIO Ultra HD Webcam                     | 1        | 2.17%   |
| Logitech B525 HD Webcam                           | 1        | 2.17%   |
| lihappe8 USB 2.0 Camera                           | 1        | 2.17%   |
| HP Webcam HD 2300                                 | 1        | 2.17%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 2.17%   |
| Apple iSight in LED Cinema Display                | 1        | 2.17%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                | 1        | 2.17%   |
| A4Tech FHD 1080P PC Camera                        | 1        | 2.17%   |
| Unknown                                           | 1        | 2.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Aktiv  | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Aktiv Rutoken lite | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 266      | 91.1%   |
| 1     | 23       | 7.88%   |
| 2     | 2        | 0.68%   |
| 5     | 1        | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 10       | 33.33%  |
| Communication controller | 8        | 26.67%  |
| Multimedia controller    | 3        | 10%     |
| Unassigned class         | 2        | 6.67%   |
| Net/ethernet             | 2        | 6.67%   |
| Storage/ide              | 1        | 3.33%   |
| Sound                    | 1        | 3.33%   |
| Net/wireless             | 1        | 3.33%   |
| Chipcard                 | 1        | 3.33%   |
| Bluetooth                | 1        | 3.33%   |

