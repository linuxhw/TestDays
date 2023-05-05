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

Total: 331

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Graviton      | DMB-A520-MCA01              | [d0c1433d54](https://linux-hardware.org/?probe=d0c1433d54) | Apr 18, 2023 |
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
| Kometa P10         | 81       | 34.03%  |
| ALT Linux 10.1     | 43       | 18.07%  |
| ALT Linux 9.1      | 33       | 13.87%  |
| ALT Linux 10.0     | 21       | 8.82%   |
| ALT Linux 9.0      | 15       | 6.3%    |
| MOS 10             | 12       | 5.04%   |
| ALT Linux 9.2      | 7        | 2.94%   |
| ALT Linux P10      | 5        | 2.1%    |
| ALT Linux 8.4      | 4        | 1.68%   |
| ALT Linux P9       | 2        | 0.84%   |
| ALT Linux P8       | 2        | 0.84%   |
| ALT Linux 8.2      | 2        | 0.84%   |
| ALT Linux 7.0.5    | 2        | 0.84%   |
| ALT Linux 20220110 | 2        | 0.84%   |
| ALT Linux 10.0.900 | 2        | 0.84%   |
| Kometa 1           | 1        | 0.42%   |
| ALT Linux 8.2.0    | 1        | 0.42%   |
| ALT Linux 20201124 | 1        | 0.42%   |
| ALT Linux 20190303 | 1        | 0.42%   |
| ALT Linux 10.0.910 | 1        | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ALT Linux | 225      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.10.109-std-def-alt1      | 51       | 20.65%  |
| 5.10.102-std-def-alt1      | 27       | 10.93%  |
| 5.15.34-un-def-alt1        | 10       | 4.05%   |
| 5.15.80-un-def-alt1        | 8        | 3.24%   |
| 5.10.82-std-def-alt1       | 8        | 3.24%   |
| 5.4.68-std-def-alt1.1      | 7        | 2.83%   |
| 5.4.51-std-def-alt1        | 5        | 2.02%   |
| 5.15.72-un-def-alt1        | 5        | 2.02%   |
| 5.15.32-un-def-alt1        | 5        | 2.02%   |
| 5.10.164-std-def-alt1      | 4        | 1.62%   |
| 5.10.145-std-def-alt1      | 4        | 1.62%   |
| 5.4.41-std-def-alt1        | 3        | 1.21%   |
| 5.10.93-std-def-alt1       | 3        | 1.21%   |
| 5.10.88-std-def-alt1       | 3        | 1.21%   |
| 5.10.35-un-def-alt1        | 3        | 1.21%   |
| 5.10.32-un-def-alt1        | 3        | 1.21%   |
| 5.10.123-std-def-alt1      | 3        | 1.21%   |
| 4.19.79-std-def-alt1       | 3        | 1.21%   |
| 5.7.19-un-def-alt1         | 2        | 0.81%   |
| 5.4.85-std-def-alt1        | 2        | 0.81%   |
| 5.4.62-std-def-alt1        | 2        | 0.81%   |
| 5.4.28-std-def-alt1        | 2        | 0.81%   |
| 5.4.181-std-def-alt1       | 2        | 0.81%   |
| 5.4.127-std-def-alt1       | 2        | 0.81%   |
| 5.2.10-un-def-alt1         | 2        | 0.81%   |
| 5.15.96-un-def-alt1        | 2        | 0.81%   |
| 5.15.70-un-def-alt1        | 2        | 0.81%   |
| 5.15.15-un-def-alt1        | 2        | 0.81%   |
| 5.15.14-un-def-alt1        | 2        | 0.81%   |
| 5.10.83-std-def-alt0.c9f.2 | 2        | 0.81%   |
| 5.10.72-std-def-alt1       | 2        | 0.81%   |
| 5.10.170-std-def-alt1      | 2        | 0.81%   |
| 5.10.17-un-def-alt1        | 2        | 0.81%   |
| 5.10.165-std-def-alt1      | 2        | 0.81%   |
| 5.10.156-std-def-alt1      | 2        | 0.81%   |
| 5.10.118-std-def-alt1      | 2        | 0.81%   |
| 5.9.8-un-def-alt1          | 1        | 0.4%    |
| 5.7.14-un-def-alt1         | 1        | 0.4%    |
| 5.4.94-std-def-alt1        | 1        | 0.4%    |
| 5.4.92-std-def-alt1        | 1        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.109 | 51       | 20.65%  |
| 5.10.102 | 27       | 10.93%  |
| 5.15.34  | 10       | 4.05%   |
| 5.15.80  | 8        | 3.24%   |
| 5.10.82  | 8        | 3.24%   |
| 5.4.68   | 7        | 2.83%   |
| 5.4.51   | 5        | 2.02%   |
| 5.15.72  | 5        | 2.02%   |
| 5.15.32  | 5        | 2.02%   |
| 5.10.164 | 4        | 1.62%   |
| 5.10.145 | 4        | 1.62%   |
| 5.4.41   | 3        | 1.21%   |
| 5.10.93  | 3        | 1.21%   |
| 5.10.88  | 3        | 1.21%   |
| 5.10.35  | 3        | 1.21%   |
| 5.10.32  | 3        | 1.21%   |
| 5.10.156 | 3        | 1.21%   |
| 5.10.123 | 3        | 1.21%   |
| 4.19.79  | 3        | 1.21%   |
| 5.7.19   | 2        | 0.81%   |
| 5.4.85   | 2        | 0.81%   |
| 5.4.62   | 2        | 0.81%   |
| 5.4.28   | 2        | 0.81%   |
| 5.4.181  | 2        | 0.81%   |
| 5.4.127  | 2        | 0.81%   |
| 5.2.10   | 2        | 0.81%   |
| 5.15.96  | 2        | 0.81%   |
| 5.15.70  | 2        | 0.81%   |
| 5.15.15  | 2        | 0.81%   |
| 5.15.14  | 2        | 0.81%   |
| 5.14.21  | 2        | 0.81%   |
| 5.10.83  | 2        | 0.81%   |
| 5.10.72  | 2        | 0.81%   |
| 5.10.54  | 2        | 0.81%   |
| 5.10.170 | 2        | 0.81%   |
| 5.10.17  | 2        | 0.81%   |
| 5.10.165 | 2        | 0.81%   |
| 5.10.118 | 2        | 0.81%   |
| 5.9.8    | 1        | 0.4%    |
| 5.7.14   | 1        | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 133      | 56.84%  |
| 5.15    | 41       | 17.52%  |
| 5.4     | 35       | 14.96%  |
| 4.19    | 7        | 2.99%   |
| 5.7     | 3        | 1.28%   |
| 5.2     | 3        | 1.28%   |
| 4.9     | 3        | 1.28%   |
| 5.14    | 2        | 0.85%   |
| 4.14    | 2        | 0.85%   |
| 5.9     | 1        | 0.43%   |
| 5.18    | 1        | 0.43%   |
| 5.13    | 1        | 0.43%   |
| 5.12    | 1        | 0.43%   |
| 4.20    | 1        | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 218      | 96.89%  |
| i686   | 4        | 1.78%   |
| e2k    | 3        | 1.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 152      | 66.67%  |
| Unknown  | 36       | 15.79%  |
| XFCE     | 32       | 14.04%  |
| MATE     | 5        | 2.19%   |
| KDE      | 2        | 0.88%   |
| Cinnamon | 1        | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 218      | 96.89%  |
| Unknown | 6        | 2.67%   |
| Tty     | 1        | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 126      | 55.02%  |
| LightDM | 38       | 16.59%  |
| Unknown | 36       | 15.72%  |
| TDM     | 28       | 12.23%  |
| WDM     | 1        | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 191      | 83.04%  |
| Unknown | 35       | 15.22%  |
| en_US   | 2        | 0.87%   |
| POSIX   | 1        | 0.43%   |
| el_GR   | 1        | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 129      | 56.58%  |
| BIOS | 99       | 43.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 213      | 94.25%  |
| Overlay | 9        | 3.98%   |
| Btrfs   | 4        | 1.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 143      | 62.72%  |
| MBR     | 50       | 21.93%  |
| Unknown | 35       | 15.35%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 198      | 88%     |
| Yes       | 27       | 12%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 174      | 75.98%  |
| Yes       | 55       | 24.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 50       | 22.22%  |
| ASUSTek Computer    | 42       | 18.67%  |
| Gigabyte Technology | 38       | 16.89%  |
| ASRock              | 21       | 9.33%   |
| MSI                 | 14       | 6.22%   |
| Acer                | 14       | 6.22%   |
| Unknown             | 11       | 4.89%   |
| MAINBRD             | 4        | 1.78%   |
| Graviton            | 4        | 1.78%   |
| iRU                 | 3        | 1.33%   |
| DEPO Computers      | 3        | 1.33%   |
| 3Logic Group        | 3        | 1.33%   |
| Hewlett-Packard     | 2        | 0.89%   |
| Dell                | 2        | 0.89%   |
| Biostar             | 2        | 0.89%   |
| Yadro               | 1        | 0.44%   |
| VIA Technologies    | 1        | 0.44%   |
| SYS                 | 1        | 0.44%   |
| Supermicro          | 1        | 0.44%   |
| OEM                 | 1        | 0.44%   |
| Lenovo              | 1        | 0.44%   |
| Kraftway            | 1        | 0.44%   |
| Huanan              | 1        | 0.44%   |
| Foxconn             | 1        | 0.44%   |
| EPoX Computer       | 1        | 0.44%   |
| ECS                 | 1        | 0.44%   |
| Aquarius            | 1        | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel SKYBAY                      | 46       | 20.44%  |
| ASUS PRIME B450-PLUS              | 12       | 5.33%   |
| Unknown                           | 11       | 4.89%   |
| Acer Veriton X2640G               | 10       | 4.44%   |
| MAINBRD OPS62A-SHA                | 4        | 1.78%   |
| Gigabyte H110M-S2H                | 4        | 1.78%   |
| Graviton DMB-A520-MCA01           | 3        | 1.33%   |
| ASUS H110M-R                      | 3        | 1.33%   |
| 3Logic Group Graviton             | 3        | 1.33%   |
| MSI MS-7D46                       | 2        | 0.89%   |
| MSI MPG B560 Trident A (MS-B926)  | 2        | 0.89%   |
| iRU 515                           | 2        | 0.89%   |
| Gigabyte H77M-D3H                 | 2        | 0.89%   |
| Gigabyte A320M-S2H                | 2        | 0.89%   |
| DEPO Computers DPH410S            | 2        | 0.89%   |
| ASRock B450M Pro4                 | 2        | 0.89%   |
| Acer Veriton ES2710G              | 2        | 0.89%   |
| Yadro TB560-D4                    | 1        | 0.44%   |
| VIA P4M266A-8235                  | 1        | 0.44%   |
| SYS RAY B101                      | 1        | 0.44%   |
| Supermicro SYS-1019D-14CN-FHN13TP | 1        | 0.44%   |
| OEM ZXE CRB                       | 1        | 0.44%   |
| MSI MS-7D23                       | 1        | 0.44%   |
| MSI MS-7D18                       | 1        | 0.44%   |
| MSI MS-7C94                       | 1        | 0.44%   |
| MSI MS-7A38                       | 1        | 0.44%   |
| MSI MS-7996                       | 1        | 0.44%   |
| MSI MS-7895                       | 1        | 0.44%   |
| MSI MS-7877                       | 1        | 0.44%   |
| MSI MS-7758                       | 1        | 0.44%   |
| MSI MS-7721                       | 1        | 0.44%   |
| MSI MS-7357                       | 1        | 0.44%   |
| Lenovo ThinkCentre M73 10B1S15000 | 1        | 0.44%   |
| Kraftway KWH310                   | 1        | 0.44%   |
| iRU IRUB365M                      | 1        | 0.44%   |
| Intel X99 V1.0                    | 1        | 0.44%   |
| Intel X79                         | 1        | 0.44%   |
| Intel D34010WYK                   | 1        | 0.44%   |
| Intel B75                         | 1        | 0.44%   |
| Huanan H97-ZD3 V2.0               | 1        | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel SKYBAY                      | 46       | 20.44%  |
| ASUS PRIME                        | 17       | 7.56%   |
| Acer Veriton                      | 13       | 5.78%   |
| Unknown                           | 11       | 4.89%   |
| MAINBRD OPS62A-SHA                | 4        | 1.78%   |
| Gigabyte H110M-S2H                | 4        | 1.78%   |
| Graviton DMB-A520-MCA01           | 3        | 1.33%   |
| ASUS H110M-R                      | 3        | 1.33%   |
| 3Logic Group Graviton             | 3        | 1.33%   |
| MSI MS-7D46                       | 2        | 0.89%   |
| MSI MPG                           | 2        | 0.89%   |
| iRU 515                           | 2        | 0.89%   |
| Gigabyte H77M-D3H                 | 2        | 0.89%   |
| Gigabyte B550                     | 2        | 0.89%   |
| Gigabyte B450                     | 2        | 0.89%   |
| Gigabyte A320M-S2H                | 2        | 0.89%   |
| DEPO Computers DPH410S            | 2        | 0.89%   |
| Dell OptiPlex                     | 2        | 0.89%   |
| ASUS P7H55-M                      | 2        | 0.89%   |
| ASRock Z77                        | 2        | 0.89%   |
| ASRock B450M                      | 2        | 0.89%   |
| Yadro TB560-D4                    | 1        | 0.44%   |
| VIA P4M266A-8235                  | 1        | 0.44%   |
| SYS RAY                           | 1        | 0.44%   |
| Supermicro SYS-1019D-14CN-FHN13TP | 1        | 0.44%   |
| OEM ZXE                           | 1        | 0.44%   |
| MSI MS-7D23                       | 1        | 0.44%   |
| MSI MS-7D18                       | 1        | 0.44%   |
| MSI MS-7C94                       | 1        | 0.44%   |
| MSI MS-7A38                       | 1        | 0.44%   |
| MSI MS-7996                       | 1        | 0.44%   |
| MSI MS-7895                       | 1        | 0.44%   |
| MSI MS-7877                       | 1        | 0.44%   |
| MSI MS-7758                       | 1        | 0.44%   |
| MSI MS-7721                       | 1        | 0.44%   |
| MSI MS-7357                       | 1        | 0.44%   |
| Lenovo ThinkCentre                | 1        | 0.44%   |
| Kraftway KWH310                   | 1        | 0.44%   |
| iRU IRUB365M                      | 1        | 0.44%   |
| Intel X99                         | 1        | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 45       | 20%     |
| 2017    | 37       | 16.44%  |
| 2016    | 22       | 9.78%   |
| 2020    | 18       | 8%      |
| 2021    | 15       | 6.67%   |
| 2012    | 15       | 6.67%   |
| 2022    | 11       | 4.89%   |
| 2019    | 7        | 3.11%   |
| 2010    | 7        | 3.11%   |
| 2008    | 7        | 3.11%   |
| 2015    | 6        | 2.67%   |
| 2014    | 6        | 2.67%   |
| 2009    | 5        | 2.22%   |
| 2006    | 5        | 2.22%   |
| 2011    | 4        | 1.78%   |
| 2007    | 4        | 1.78%   |
| 2013    | 3        | 1.33%   |
| 2005    | 3        | 1.33%   |
| Unknown | 3        | 1.33%   |
| 2004    | 1        | 0.44%   |
| 2003    | 1        | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 225      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 215      | 95.56%  |
| Enabled  | 10       | 4.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 225      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 89       | 39.56%  |
| 4.01-8.0    | 54       | 24%     |
| 3.01-4.0    | 33       | 14.67%  |
| 16.01-24.0  | 25       | 11.11%  |
| 32.01-64.0  | 7        | 3.11%   |
| 64.01-256.0 | 5        | 2.22%   |
| 1.01-2.0    | 5        | 2.22%   |
| 2.01-3.0    | 4        | 1.78%   |
| 0.51-1.0    | 2        | 0.89%   |
| 24.01-32.0  | 1        | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 119      | 50.21%  |
| 2.01-3.0   | 37       | 15.61%  |
| 0.51-1.0   | 32       | 13.5%   |
| 4.01-8.0   | 21       | 8.86%   |
| 3.01-4.0   | 19       | 8.02%   |
| 8.01-16.0  | 5        | 2.11%   |
| 0.01-0.5   | 3        | 1.27%   |
| 16.01-24.0 | 1        | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 149      | 64.78%  |
| 2      | 46       | 20%     |
| 3      | 20       | 8.7%    |
| 4      | 7        | 3.04%   |
| 5      | 5        | 2.17%   |
| 8      | 1        | 0.43%   |
| 6      | 1        | 0.43%   |
| 0      | 1        | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 149      | 65.93%  |
| Yes       | 77       | 34.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 224      | 99.56%  |
| No        | 1        | 0.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 182      | 80.89%  |
| Yes       | 43       | 19.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 191      | 84.51%  |
| Yes       | 35       | 15.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Russia     | 217      | 96.44%  |
| Ukraine    | 3        | 1.33%   |
| Greece     | 2        | 0.89%   |
| Kazakhstan | 1        | 0.44%   |
| China      | 1        | 0.44%   |
| Belarus    | 1        | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Moscow                   | 135      | 58.7%   |
| St Petersburg            | 11       | 4.78%   |
| Samara                   | 7        | 3.04%   |
| Chelyabinsk              | 5        | 2.17%   |
| Irkutsk                  | 4        | 1.74%   |
| Barnaul                  | 3        | 1.3%    |
| Yekaterinburg            | 2        | 0.87%   |
| Sevastopol               | 2        | 0.87%   |
| Saratov                  | 2        | 0.87%   |
| Rostov-on-Don            | 2        | 0.87%   |
| Perm                     | 2        | 0.87%   |
| Obninsk                  | 2        | 0.87%   |
| Novosibirsk              | 2        | 0.87%   |
| Krasnoyarsk              | 2        | 0.87%   |
| Kaliningrad              | 2        | 0.87%   |
| Donetsk                  | 2        | 0.87%   |
| Zelenodolsk              | 1        | 0.43%   |
| Yessentuki               | 1        | 0.43%   |
| Vologda                  | 1        | 0.43%   |
| Vladivostok              | 1        | 0.43%   |
| Vladimir                 | 1        | 0.43%   |
| Vikhorevka               | 1        | 0.43%   |
| Verkhnyaya Pyshma        | 1        | 0.43%   |
| Vergina                  | 1        | 0.43%   |
| Valuyki                  | 1        | 0.43%   |
| Ulyanovsk                | 1        | 0.43%   |
| Tula                     | 1        | 0.43%   |
| Tolyatti                 | 1        | 0.43%   |
| Thessaloniki             | 1        | 0.43%   |
| Taraz                    | 1        | 0.43%   |
| Tambov                   | 1        | 0.43%   |
| Surgut                   | 1        | 0.43%   |
| Stavropol                | 1        | 0.43%   |
| Shenzhen                 | 1        | 0.43%   |
| Serov                    | 1        | 0.43%   |
| Pushchino                | 1        | 0.43%   |
| Protvino                 | 1        | 0.43%   |
| Polyarnyy                | 1        | 0.43%   |
| Petropavlovsk-Kamchatsky | 1        | 0.43%   |
| Nizhny Tagil             | 1        | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 62       | 93     | 19.44%  |
| Seagate                     | 50       | 76     | 15.67%  |
| Samsung Electronics         | 36       | 43     | 11.29%  |
| Toshiba                     | 30       | 46     | 9.4%    |
| AXIOMTEK                    | 28       | 30     | 8.78%   |
| Kingston                    | 24       | 26     | 7.52%   |
| China                       | 10       | 11     | 3.13%   |
| Apacer                      | 9        | 12     | 2.82%   |
| Hitachi                     | 7        | 8      | 2.19%   |
| A-DATA Technology           | 7        | 7      | 2.19%   |
| XPG                         | 3        | 3      | 0.94%   |
| SanDisk                     | 3        | 3      | 0.94%   |
| Plextor                     | 3        | 3      | 0.94%   |
| Patriot                     | 3        | 5      | 0.94%   |
| Intel                       | 3        | 8      | 0.94%   |
| TMI                         | 2        | 2      | 0.63%   |
| Team                        | 2        | 2      | 0.63%   |
| SPCC                        | 2        | 2      | 0.63%   |
| Smartbuy                    | 2        | 2      | 0.63%   |
| Phison                      | 2        | 2      | 0.63%   |
| Micron Technology           | 2        | 2      | 0.63%   |
| JMicron Technology          | 2        | 2      | 0.63%   |
| Gigabyte Technology         | 2        | 2      | 0.63%   |
| DEPO                        | 2        | 2      | 0.63%   |
| Crucial                     | 2        | 2      | 0.63%   |
| XrayDisk                    | 1        | 1      | 0.31%   |
| Transcend                   | 1        | 1      | 0.31%   |
| SP-8                        | 1        | 1      | 0.31%   |
| SINTECHI                    | 1        | 1      | 0.31%   |
| Silicon Motion              | 1        | 2      | 0.31%   |
| OCZ                         | 1        | 1      | 0.31%   |
| Netac                       | 1        | 1      | 0.31%   |
| Micron/Crucial Technology   | 1        | 1      | 0.31%   |
| Maxtor                      | 1        | 1      | 0.31%   |
| LITEON                      | 1        | 1      | 0.31%   |
| Kingston Technology Company | 1        | 1      | 0.31%   |
| KingSpec                    | 1        | 1      | 0.31%   |
| HS-SSD-C100                 | 1        | 1      | 0.31%   |
| HGST                        | 1        | 1      | 0.31%   |
| HEORIADY                    | 1        | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD   | 28       | 8.21%   |
| Samsung MZVLW128HEGR-00000 128GB       | 18       | 5.28%   |
| Toshiba HDWD120 2TB                    | 13       | 3.81%   |
| WDC WD5000AZLX-21K2TA0 500GB           | 10       | 2.93%   |
| Toshiba HDWD110 1TB                    | 6        | 1.76%   |
| Seagate ST1000DM010-2EP102 1TB         | 6        | 1.76%   |
| WDC WD10EZEX-08WN4A0 1TB               | 4        | 1.17%   |
| Toshiba DT01ACA100 1TB                 | 4        | 1.17%   |
| Kingston SV300S37A120G 120GB SSD       | 4        | 1.17%   |
| Kingston RBUSC180S37256GJ 256GB SSD    | 4        | 1.17%   |
| Apacer AS350 256GB SSD                 | 4        | 1.17%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 3        | 0.88%   |
| Seagate ST380815AS 80GB                | 3        | 0.88%   |
| Samsung SSD 860 EVO 250GB              | 3        | 0.88%   |
| Kingston SA400S37240G 240GB SSD        | 3        | 0.88%   |
| Kingston SA400S37120G 120GB SSD        | 3        | 0.88%   |
| XPG GAMMIX S5 512GB                    | 2        | 0.59%   |
| WDC WD3200AAKS-00G3A0 320GB            | 2        | 0.59%   |
| WDC WD2000FYYZ-01UL1B1 2TB             | 2        | 0.59%   |
| WDC WD10PURZ-85U8XY0 1TB               | 2        | 0.59%   |
| WDC WD10JPVX-00JC3T0 1TB               | 2        | 0.59%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB     | 2        | 0.59%   |
| Toshiba DT01ACA050 500GB               | 2        | 0.59%   |
| Seagate ST500LM030-2E717D 500GB        | 2        | 0.59%   |
| Seagate ST500DM002-1BD142 500GB        | 2        | 0.59%   |
| Seagate ST500DM002-1BC142 500GB        | 2        | 0.59%   |
| Seagate ST3320620AS 320GB              | 2        | 0.59%   |
| Seagate ST250DM000-1BD141 250GB        | 2        | 0.59%   |
| Seagate ST2000DM008-2FR102 2TB         | 2        | 0.59%   |
| Seagate ST1000LM049-2GH172 1TB         | 2        | 0.59%   |
| Samsung SSD 970 EVO Plus 250GB         | 2        | 0.59%   |
| Samsung SSD 860 EVO 500GB              | 2        | 0.59%   |
| Samsung MZVL2256HCHQ-00B00 256GB       | 2        | 0.59%   |
| Phison M.2 128GB SSO128GTLCG-SBC-2 SSD | 2        | 0.59%   |
| JMicron Generic 1TB                    | 2        | 0.59%   |
| Hitachi HUA722010CLA330 1TB            | 2        | 0.59%   |
| Hitachi HDS723020BLA642 2TB            | 2        | 0.59%   |
| Hitachi HDS721025CLA382 250GB          | 2        | 0.59%   |
| DEPO SM3DT-120 120GB SSD               | 2        | 0.59%   |
| China SSD 128GB                        | 2        | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 53       | 82     | 35.81%  |
| Seagate             | 48       | 70     | 32.43%  |
| Toshiba             | 30       | 45     | 20.27%  |
| Hitachi             | 7        | 8      | 4.73%   |
| Samsung Electronics | 4        | 5      | 2.7%    |
| JMicron Technology  | 2        | 2      | 1.35%   |
| SINTECHI            | 1        | 1      | 0.68%   |
| Maxtor              | 1        | 1      | 0.68%   |
| HGST                | 1        | 1      | 0.68%   |
| FreeBSD             | 1        | 1      | 0.68%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| AXIOMTEK            | 28       | 30     | 21.54%  |
| Kingston            | 22       | 23     | 16.92%  |
| China               | 10       | 11     | 7.69%   |
| WDC                 | 9        | 9      | 6.92%   |
| Apacer              | 9        | 12     | 6.92%   |
| Samsung Electronics | 7        | 9      | 5.38%   |
| A-DATA Technology   | 6        | 6      | 4.62%   |
| Plextor             | 3        | 3      | 2.31%   |
| Patriot             | 3        | 5      | 2.31%   |
| TMI                 | 2        | 2      | 1.54%   |
| Team                | 2        | 2      | 1.54%   |
| Smartbuy            | 2        | 2      | 1.54%   |
| Seagate             | 2        | 6      | 1.54%   |
| SanDisk             | 2        | 2      | 1.54%   |
| Phison              | 2        | 2      | 1.54%   |
| Intel               | 2        | 6      | 1.54%   |
| DEPO                | 2        | 2      | 1.54%   |
| Crucial             | 2        | 2      | 1.54%   |
| XrayDisk            | 1        | 1      | 0.77%   |
| Transcend           | 1        | 1      | 0.77%   |
| SP-8                | 1        | 1      | 0.77%   |
| OCZ                 | 1        | 1      | 0.77%   |
| Micron Technology   | 1        | 1      | 0.77%   |
| LITEON              | 1        | 1      | 0.77%   |
| KingSpec            | 1        | 1      | 0.77%   |
| HS-SSD-C100         | 1        | 1      | 0.77%   |
| HEORIADY            | 1        | 1      | 0.77%   |
| GS Nanotech         | 1        | 1      | 0.77%   |
| Gigabyte Technology | 1        | 1      | 0.77%   |
| Foxline             | 1        | 1      | 0.77%   |
| Corsair             | 1        | 3      | 0.77%   |
| AMD                 | 1        | 1      | 0.77%   |
| Unknown             | 1        | 1      | 0.77%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 123      | 216    | 43.31%  |
| SSD  | 118      | 151    | 41.55%  |
| NVMe | 43       | 51     | 15.14%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 198      | 362    | 81.15%  |
| NVMe | 43       | 51     | 17.62%  |
| SAS  | 3        | 5      | 1.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 157      | 213    | 62.55%  |
| 0.51-1.0   | 58       | 86     | 23.11%  |
| 1.01-2.0   | 28       | 59     | 11.16%  |
| 2.01-3.0   | 3        | 4      | 1.2%    |
| 3.01-4.0   | 2        | 2      | 0.8%    |
| 4.01-10.0  | 2        | 2      | 0.8%    |
| 0          | 1        | 1      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 108      | 46.75%  |
| 251-500        | 35       | 15.15%  |
| 1001-2000      | 32       | 13.85%  |
| 501-1000       | 19       | 8.23%   |
| 51-100         | 9        | 3.9%    |
| More than 3000 | 8        | 3.46%   |
| 21-50          | 8        | 3.46%   |
| 2001-3000      | 6        | 2.6%    |
| 1-20           | 5        | 2.16%   |
| Unknown        | 1        | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 125      | 53.65%  |
| 21-50          | 40       | 17.17%  |
| 51-100         | 18       | 7.73%   |
| 101-250        | 16       | 6.87%   |
| 501-1000       | 13       | 5.58%   |
| 251-500        | 10       | 4.29%   |
| 1001-2000      | 5        | 2.15%   |
| More than 3000 | 3        | 1.29%   |
| 2001-3000      | 2        | 0.86%   |
| Unknown        | 1        | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| XrayDisk 512GB SSD                           | 1        | 1      | 3.85%   |
| WDC WD7501AALS-00E3A0 752GB                  | 1        | 1      | 3.85%   |
| WDC WD7500AAKS-00RBA0 752GB                  | 1        | 2      | 3.85%   |
| WDC WD3200AAKS-00V1A0 320GB                  | 1        | 1      | 3.85%   |
| WDC WD2500KS-00MJB0 250GB                    | 1        | 1      | 3.85%   |
| WDC WD2500BEVT-60ZCT1 250GB                  | 1        | 3      | 3.85%   |
| WDC WD20EARX-008FB0 2TB                      | 1        | 1      | 3.85%   |
| WDC WD2005FBYZ-01YCBB3 2TB                   | 1        | 1      | 3.85%   |
| WDC WD1003FBYX-01Y7B0 1TB                    | 1        | 1      | 3.85%   |
| Toshiba DT01ACA050 500GB                     | 1        | 1      | 3.85%   |
| Seagate ST9500530NS 42D0743 42D0746IBM 500GB | 1        | 1      | 3.85%   |
| Seagate ST9250315AS 250GB                    | 1        | 1      | 3.85%   |
| Seagate ST380815AS 80GB                      | 1        | 1      | 3.85%   |
| Seagate ST380811AS 80GB                      | 1        | 1      | 3.85%   |
| Seagate ST3320418AS 320GB                    | 1        | 1      | 3.85%   |
| Seagate ST32000641AS 2TB                     | 1        | 2      | 3.85%   |
| Seagate ST3000DM001-1CH166 3TB               | 1        | 1      | 3.85%   |
| Seagate ST250DM000-1BD141 250GB              | 1        | 2      | 3.85%   |
| Seagate ST1000DL004 HD105SI 1TB              | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1        | 1      | 3.85%   |
| Hitachi HUA722010CLA330 1TB                  | 1        | 1      | 3.85%   |
| Hitachi HTS545050KTA300 500GB                | 1        | 2      | 3.85%   |
| Hitachi HDS723020BLA642 2TB                  | 1        | 1      | 3.85%   |
| Hitachi HDS721025CLA382 250GB                | 1        | 1      | 3.85%   |
| DEPO SM3DT-120 120GB SSD                     | 1        | 1      | 3.85%   |
| Corsair Force LS SSD 240GB                   | 1        | 3      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 11     | 34.62%  |
| WDC                 | 8        | 11     | 30.77%  |
| Hitachi             | 4        | 5      | 15.38%  |
| XrayDisk            | 1        | 1      | 3.85%   |
| Toshiba             | 1        | 1      | 3.85%   |
| Samsung Electronics | 1        | 1      | 3.85%   |
| DEPO                | 1        | 1      | 3.85%   |
| Corsair             | 1        | 3      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 9        | 11     | 40.91%  |
| WDC     | 8        | 11     | 36.36%  |
| Hitachi | 4        | 5      | 18.18%  |
| Toshiba | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 28     | 82.61%  |
| SSD  | 4        | 6      | 17.39%  |

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
| Works    | 173      | 289    | 70.33%  |
| Detected | 49       | 93     | 19.92%  |
| Malfunc  | 22       | 34     | 8.94%   |
| Failed   | 2        | 2      | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 162      | 56.84%  |
| AMD                          | 48       | 16.84%  |
| Samsung Electronics          | 25       | 8.77%   |
| Nvidia                       | 9        | 3.16%   |
| JMicron Technology           | 7        | 2.46%   |
| ASMedia Technology           | 5        | 1.75%   |
| Realtek Semiconductor        | 4        | 1.4%    |
| Marvell Technology Group     | 4        | 1.4%    |
| Kingston Technology Company  | 4        | 1.4%    |
| Silicon Motion               | 3        | 1.05%   |
| SanDisk                      | 3        | 1.05%   |
| MCST                         | 3        | 1.05%   |
| Phison Electronics           | 2        | 0.7%    |
| Zhaoxin                      | 1        | 0.35%   |
| VIA Technologies             | 1        | 0.35%   |
| Toshiba America Info Systems | 1        | 0.35%   |
| Micron/Crucial Technology    | 1        | 0.35%   |
| Micron Technology            | 1        | 0.35%   |
| LSI Logic / Symbios Logic    | 1        | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 69       | 19.83%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 37       | 10.63%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 18       | 5.17%   |
| AMD 400 Series Chipset SATA Controller                                                  | 18       | 5.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 10       | 2.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 2.87%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 2.3%    |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 2.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 1.72%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.44%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.44%   |
| AMD FCH SATA Controller D                                                               | 5        | 1.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 1.15%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 4        | 1.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4        | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.86%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 3        | 0.86%   |
| MCST SATA                                                                               | 3        | 0.86%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.86%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.86%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.86%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 3        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 0.86%   |
| AMD FCH IDE Controller                                                                  | 3        | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.57%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2        | 0.57%   |
| Realtek NVMe Controller                                                                 | 2        | 0.57%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 0.57%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 2        | 0.57%   |
| Nvidia MCP51 Serial ATA Controller                                                      | 2        | 0.57%   |
| Nvidia MCP51 IDE                                                                        | 2        | 0.57%   |
| MCST IDE controller                                                                     | 2        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 189      | 67.26%  |
| IDE  | 47       | 16.73%  |
| NVMe | 43       | 15.3%   |
| RAID | 2        | 0.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 165      | 73.33%  |
| AMD          | 56       | 24.89%  |
| Elbrus-MCST  | 1        | 0.44%   |
| E8C/EATX     | 1        | 0.44%   |
| E8C-SWTX     | 1        | 0.44%   |
| CentaurHauls | 1        | 0.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i3-6100TE CPU @ 2.70GHz              | 45       | 19.82%  |
| AMD Ryzen 5 1600 Six-Core Processor             | 13       | 5.73%   |
| Intel Pentium CPU G4560 @ 3.50GHz               | 10       | 4.41%   |
| Intel Core i3-10100 CPU @ 3.60GHz               | 5        | 2.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz               | 4        | 1.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 4        | 1.76%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 4        | 1.76%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 3        | 1.32%   |
| Intel Core i3-9100 CPU @ 3.60GHz                | 3        | 1.32%   |
| Intel Celeron CPU G3900 @ 2.80GHz               | 3        | 1.32%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz          | 2        | 0.88%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz     | 2        | 0.88%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 2        | 0.88%   |
| Intel Pentium CPU G4400 @ 3.30GHz               | 2        | 0.88%   |
| Intel Genuine CPU 0000 @ 2.40GHz                | 2        | 0.88%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 2        | 0.88%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 2        | 0.88%   |
| Intel Core i5-3450 CPU @ 3.10GHz                | 2        | 0.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 2        | 0.88%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 2        | 0.88%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 2        | 0.88%   |
| Intel Core i3-6100 CPU @ 3.70GHz                | 2        | 0.88%   |
| Intel Core i3-10105 CPU @ 3.70GHz               | 2        | 0.88%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 0.88%   |
| Intel Celeron CPU J1800 @ 2.41GHz               | 2        | 0.88%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 2        | 0.88%   |
| Intel 11th Gen Core i5-11500 @ 2.70GHz          | 2        | 0.88%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 2        | 0.88%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 2        | 0.88%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 2        | 0.88%   |
| AMD Athlon 64 X2 Dual Core Processor 4800+      | 2        | 0.88%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+      | 2        | 0.88%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 2        | 0.88%   |
| AMD A10-7890K Radeon R7, 12 Compute Cores 4C+8G | 2        | 0.88%   |
| Intel Xeon D-2177NT CPU @ 1.90GHz               | 1        | 0.44%   |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 1        | 0.44%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz             | 1        | 0.44%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz             | 1        | 0.44%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz              | 1        | 0.44%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz             | 1        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 68       | 30.09%  |
| Intel Core i5           | 23       | 10.18%  |
| AMD Ryzen 5             | 19       | 8.41%   |
| Other                   | 14       | 6.19%   |
| Intel Pentium           | 14       | 6.19%   |
| Intel Celeron           | 11       | 4.87%   |
| AMD Ryzen 7             | 7        | 3.1%    |
| Intel Xeon              | 6        | 2.65%   |
| Intel Pentium Dual-Core | 6        | 2.65%   |
| Intel Core i7           | 6        | 2.65%   |
| Intel Core 2 Duo        | 6        | 2.65%   |
| AMD A10                 | 5        | 2.21%   |
| Intel Core 2 Quad       | 4        | 1.77%   |
| AMD Athlon 64 X2        | 4        | 1.77%   |
| Intel Pentium Gold      | 3        | 1.33%   |
| Intel Genuine           | 3        | 1.33%   |
| AMD A8                  | 3        | 1.33%   |
| Intel Core i9           | 2        | 0.88%   |
| AMD Ryzen 3             | 2        | 0.88%   |
| AMD Phenom II X4        | 2        | 0.88%   |
| AMD FX                  | 2        | 0.88%   |
| AMD Athlon              | 2        | 0.88%   |
| AMD A6                  | 2        | 0.88%   |
| Intel Pentium D         | 1        | 0.44%   |
| Intel Pentium 4         | 1        | 0.44%   |
| Intel Celeron D         | 1        | 0.44%   |
| AMD Sempron             | 1        | 0.44%   |
| AMD Ryzen 9             | 1        | 0.44%   |
| AMD Ryzen 7 PRO         | 1        | 0.44%   |
| AMD Ryzen 5 PRO         | 1        | 0.44%   |
| AMD Ryzen 3 PRO         | 1        | 0.44%   |
| AMD Phenom II X6        | 1        | 0.44%   |
| AMD Athlon II X4        | 1        | 0.44%   |
| AMD Athlon II X2        | 1        | 0.44%   |
| AMD Athlon 64           | 1        | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 111      | 49.12%  |
| 4      | 56       | 24.78%  |
| 6      | 29       | 12.83%  |
| 8      | 15       | 6.64%   |
| 1      | 6        | 2.65%   |
| 16     | 2        | 0.88%   |
| 12     | 2        | 0.88%   |
| 3      | 2        | 0.88%   |
| 32     | 1        | 0.44%   |
| 18     | 1        | 0.44%   |
| 14     | 1        | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 222      | 98.67%  |
| 2      | 2        | 0.89%   |
| 4      | 1        | 0.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 152      | 67.56%  |
| 1      | 73       | 32.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 221      | 98.22%  |
| Unknown        | 3        | 1.33%   |
| 32-bit         | 1        | 0.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 53       | 23.35%  |
| 0x506e3    | 52       | 22.91%  |
| 0x906e9    | 13       | 5.73%   |
| 0x08001138 | 13       | 5.73%   |
| 0x1067a    | 10       | 4.41%   |
| 0xa0653    | 8        | 3.52%   |
| 0xa0671    | 5        | 2.2%    |
| 0x906eb    | 5        | 2.2%    |
| 0x906ea    | 5        | 2.2%    |
| 0x08108109 | 5        | 2.2%    |
| 0x806c1    | 4        | 1.76%   |
| 0x306a9    | 4        | 1.76%   |
| 0x806e9    | 3        | 1.32%   |
| 0x206a7    | 3        | 1.32%   |
| 0x0a50000c | 3        | 1.32%   |
| 0x06001119 | 3        | 1.32%   |
| 0x906ed    | 2        | 0.88%   |
| 0x806ec    | 2        | 0.88%   |
| 0x306e4    | 2        | 0.88%   |
| 0x306c3    | 2        | 0.88%   |
| 0x30679    | 2        | 0.88%   |
| 0x08701021 | 2        | 0.88%   |
| 0x010000db | 2        | 0.88%   |
| 0x00000000 | 2        | 0.88%   |
| 0xf47      | 1        | 0.44%   |
| 0xf29      | 1        | 0.44%   |
| 0x6fd      | 1        | 0.44%   |
| 0x6fb      | 1        | 0.44%   |
| 0x506e8    | 1        | 0.44%   |
| 0x506c9    | 1        | 0.44%   |
| 0x50657    | 1        | 0.44%   |
| 0x50654    | 1        | 0.44%   |
| 0x206c2    | 1        | 0.44%   |
| 0x20655    | 1        | 0.44%   |
| 0x106e5    | 1        | 0.44%   |
| 0x10661    | 1        | 0.44%   |
| 0x0a50000d | 1        | 0.44%   |
| 0x0a20120a | 1        | 0.44%   |
| 0x08600106 | 1        | 0.44%   |
| 0x08108102 | 1        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Skylake     | 59       | 26.11%  |
| KabyLake    | 32       | 14.16%  |
| Zen         | 15       | 6.64%   |
| Penryn      | 13       | 5.75%   |
| CometLake   | 12       | 5.31%   |
| IvyBridge   | 10       | 4.42%   |
| Unknown     | 10       | 4.42%   |
| Zen+        | 8        | 3.54%   |
| SandyBridge | 7        | 3.1%    |
| Zen 3       | 6        | 2.65%   |
| Piledriver  | 6        | 2.65%   |
| K8 Hammer   | 6        | 2.65%   |
| K10         | 5        | 2.21%   |
| Haswell     | 5        | 2.21%   |
| Zen 2       | 4        | 1.77%   |
| TigerLake   | 4        | 1.77%   |
| Steamroller | 4        | 1.77%   |
| Silvermont  | 4        | 1.77%   |
| Core        | 4        | 1.77%   |
| Westmere    | 3        | 1.33%   |
| NetBurst    | 3        | 1.33%   |
| Icelake     | 2        | 0.88%   |
| Nehalem     | 1        | 0.44%   |
| K10 Llano   | 1        | 0.44%   |
| Goldmont    | 1        | 0.44%   |
| Excavator   | 1        | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 124      | 52.99%  |
| Nvidia            | 59       | 25.21%  |
| AMD               | 46       | 19.66%  |
| Silicon Motion    | 2        | 0.85%   |
| ASPEED Technology | 2        | 0.85%   |
| Zhaoxin           | 1        | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                     | 51       | 21.25%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 18       | 7.5%    |
| Intel HD Graphics 610                                                     | 10       | 4.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 9        | 3.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 9        | 3.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 7        | 2.92%   |
| Intel HD Graphics 510                                                     | 5        | 2.08%   |
| Nvidia GK208B [GeForce GT 710]                                            | 4        | 1.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4        | 1.67%   |
| Intel HD Graphics 620                                                     | 4        | 1.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4        | 1.67%   |
| AMD Kaveri [Radeon R7 Graphics]                                           | 4        | 1.67%   |
| Nvidia GF108 [GeForce GT 630]                                             | 3        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3        | 1.25%   |
| AMD RV710 [Radeon HD 4350/4550]                                           | 3        | 1.25%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 3        | 1.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3        | 1.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3        | 1.25%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                         | 3        | 1.25%   |
| Silicon Motion SM718 LynxSE+                                              | 2        | 0.83%   |
| Nvidia GK208B [GeForce GT 730]                                            | 2        | 0.83%   |
| Nvidia GF119 [GeForce GT 610]                                             | 2        | 0.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 2        | 0.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2        | 0.83%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                 | 2        | 0.83%   |
| Intel HD Graphics 630                                                     | 2        | 0.83%   |
| Intel Core Processor Integrated Graphics Controller                       | 2        | 0.83%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                 | 2        | 0.83%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 2        | 0.83%   |
| ASPEED Technology ASPEED Graphics Family                                  | 2        | 0.83%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series] (Secondary)                     | 2        | 0.83%   |
| AMD RV515 PRO [Radeon X1300/X1550 Series]                                 | 2        | 0.83%   |
| AMD Renoir                                                                | 2        | 0.83%   |
| Zhaoxin ZX-E C-960 GPU                                                    | 1        | 0.42%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1        | 0.42%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                     | 1        | 0.42%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                      | 1        | 0.42%   |
| Nvidia GT218 [GeForce 210]                                                | 1        | 0.42%   |
| Nvidia GP107GL [Quadro P400]                                              | 1        | 0.42%   |
| Nvidia GP107 [GeForce GTX 1050]                                           | 1        | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 118      | 51.98%  |
| 1 x Nvidia         | 57       | 25.11%  |
| 1 x AMD            | 39       | 17.18%  |
| 2 x AMD            | 5        | 2.2%    |
| 1 x Silicon Motion | 2        | 0.88%   |
| 1 x ASPEED         | 2        | 0.88%   |
| Other              | 1        | 0.44%   |
| Nvidia + Zhaoxin   | 1        | 0.44%   |
| Intel + Nvidia     | 1        | 0.44%   |
| Intel + AMD        | 1        | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 179      | 78.85%  |
| Proprietary | 42       | 18.5%   |
| Unknown     | 6        | 2.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 146      | 64.04%  |
| 3.01-4.0   | 24       | 10.53%  |
| 1.01-2.0   | 19       | 8.33%   |
| 0.01-0.5   | 16       | 7.02%   |
| 0.51-1.0   | 15       | 6.58%   |
| 8.01-16.0  | 4        | 1.75%   |
| 7.01-8.0   | 2        | 0.88%   |
| 5.01-6.0   | 1        | 0.44%   |
| 2.01-3.0   | 1        | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| HHT                  | 46       | 20.18%  |
| Acer                 | 26       | 11.4%   |
| Samsung Electronics  | 25       | 10.96%  |
| AOC                  | 23       | 10.09%  |
| BenQ                 | 22       | 9.65%   |
| Goldstar             | 14       | 6.14%   |
| Philips              | 13       | 5.7%    |
| ViewSonic            | 9        | 3.95%   |
| Dell                 | 8        | 3.51%   |
| Ancor Communications | 5        | 2.19%   |
| PRW                  | 4        | 1.75%   |
| WBT                  | 3        | 1.32%   |
| LG Electronics       | 3        | 1.32%   |
| Iiyama               | 3        | 1.32%   |
| STD                  | 2        | 0.88%   |
| MSI                  | 2        | 0.88%   |
| Hewlett-Packard      | 2        | 0.88%   |
| ASUSTek Computer     | 2        | 0.88%   |
| Unknown              | 2        | 0.88%   |
| XYK                  | 1        | 0.44%   |
| VIE                  | 1        | 0.44%   |
| Toshiba              | 1        | 0.44%   |
| SKM                  | 1        | 0.44%   |
| SKG                  | 1        | 0.44%   |
| Plain Tree Systems   | 1        | 0.44%   |
| Lenovo               | 1        | 0.44%   |
| JRY                  | 1        | 0.44%   |
| IPS                  | 1        | 0.44%   |
| HIB                  | 1        | 0.44%   |
| HannStar             | 1        | 0.44%   |
| Haier                | 1        | 0.44%   |
| DZW                  | 1        | 0.44%   |
| Apple                | 1        | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch               | 46       | 19.49%  |
| AOC LCD Monitor 2778X 2560x1440                                       | 11       | 4.66%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                     | 10       | 4.24%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 7        | 2.97%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 5        | 2.12%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 4        | 1.69%   |
| PRW AP7_Titanium PRW4200 3840x2160                                    | 4        | 1.69%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                      | 3        | 1.27%   |
| AOC 22B1WG5 AOC2201 1920x1080 479x260mm 21.5-inch                     | 3        | 1.27%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 2        | 0.85%   |
| STD LED STD0001 1920x1080 480x260mm 21.5-inch                         | 2        | 0.85%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 2        | 0.85%   |
| Samsung Electronics S22E391 SAM0C0E 1920x1080 477x268mm 21.5-inch     | 2        | 0.85%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                | 2        | 0.85%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2        | 0.85%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 2        | 0.85%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 2        | 0.85%   |
| AOC G2490W1G4 AOC2490 1920x1080 527x296mm 23.8-inch                   | 2        | 0.85%   |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                      | 2        | 0.85%   |
| Unknown                                                               | 2        | 0.85%   |
| XYK DVI XYK2360 1920x1080 477x268mm 21.5-inch                         | 1        | 0.42%   |
| ViewSonic VX2451 SERIES VSC2528 1920x1080 521x293mm 23.5-inch         | 1        | 0.42%   |
| ViewSonic VA1916wSERIES VSCF91F 1440x900 410x256mm 19.0-inch          | 1        | 0.42%   |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch           | 1        | 0.42%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 0.42%   |
| Toshiba LCD Monitor TV 1920x1080                                      | 1        | 0.42%   |
| SKM LCD Monitor SKM9322 1920x1080 527x296mm 23.8-inch                 | 1        | 0.42%   |
| SKG 86 Monitor SKG8600 3840x2160 1650x928mm 74.5-inch                 | 1        | 0.42%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0611 1920x1080 600x340mm 27.2-inch  | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM01CF 1600x1200 432x324mm 21.3-inch  | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 1        | 0.42%   |
| Samsung Electronics SMS22A450 SAM0836 1680x1050 459x296mm 21.5-inch   | 1        | 0.42%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1        | 0.42%   |
| Samsung Electronics S27E370D SAM0CF3 1920x1080 598x336mm 27.0-inch    | 1        | 0.42%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 1        | 0.42%   |
| Samsung Electronics S24B370 SAM08DE 1920x1080 531x299mm 24.0-inch     | 1        | 0.42%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 1        | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 91       | 40.99%  |
| 3840x2160 (4K)     | 60       | 27.03%  |
| 2560x1440 (QHD)    | 26       | 11.71%  |
| 1280x1024 (SXGA)   | 17       | 7.66%   |
| 1680x1050 (WSXGA+) | 5        | 2.25%   |
| 1600x900 (HD+)     | 5        | 2.25%   |
| 1440x900 (WXGA+)   | 4        | 1.8%    |
| Unknown            | 4        | 1.8%    |
| 3840x1080          | 2        | 0.9%    |
| 1366x768 (WXGA)    | 2        | 0.9%    |
| 4480x1440          | 1        | 0.45%   |
| 3840x1600          | 1        | 0.45%   |
| 1920x1200 (WUXGA)  | 1        | 0.45%   |
| 1600x1200          | 1        | 0.45%   |
| 1360x768           | 1        | 0.45%   |
| 1280x720 (HD)      | 1        | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 40      | 48       | 21.62%  |
| 24      | 34       | 15.32%  |
| 21      | 29       | 13.06%  |
| Unknown | 27       | 12.16%  |
| 23      | 22       | 9.91%   |
| 27      | 17       | 7.66%   |
| 19      | 12       | 5.41%   |
| 17      | 10       | 4.5%    |
| 31      | 5        | 2.25%   |
| 26      | 3        | 1.35%   |
| 22      | 3        | 1.35%   |
| 20      | 2        | 0.9%    |
| 18      | 2        | 0.9%    |
| 74      | 1        | 0.45%   |
| 72      | 1        | 0.45%   |
| 52      | 1        | 0.45%   |
| 46      | 1        | 0.45%   |
| 37      | 1        | 0.45%   |
| 33      | 1        | 0.45%   |
| 32      | 1        | 0.45%   |
| 28      | 1        | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 70       | 32.11%  |
| 901-1000    | 46       | 21.1%   |
| 401-500     | 40       | 18.35%  |
| Unknown     | 27       | 12.39%  |
| 601-700     | 10       | 4.59%   |
| 301-350     | 10       | 4.59%   |
| 351-400     | 6        | 2.75%   |
| 801-900     | 3        | 1.38%   |
| 701-800     | 2        | 0.92%   |
| 1501-2000   | 2        | 0.92%   |
| 1001-1500   | 2        | 0.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 114      | 53.52%  |
| 21/9    | 47       | 22.07%  |
| Unknown | 23       | 10.8%   |
| 5/4     | 16       | 7.51%   |
| 16/10   | 11       | 5.16%   |
| 4/3     | 1        | 0.47%   |
| 3/2     | 1        | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 73       | 33.33%  |
| 501-1000       | 50       | 22.83%  |
| Unknown        | 27       | 12.33%  |
| 151-200        | 24       | 10.96%  |
| 301-350        | 20       | 9.13%   |
| 141-150        | 11       | 5.02%   |
| 351-500        | 8        | 3.65%   |
| More than 1000 | 3        | 1.37%   |
| 251-300        | 3        | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 90       | 41.1%   |
| 101-120 | 82       | 37.44%  |
| Unknown | 27       | 12.33%  |
| 121-160 | 14       | 6.39%   |
| 1-50    | 5        | 2.28%   |
| 161-240 | 1        | 0.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 197      | 86.78%  |
| 2     | 18       | 7.93%   |
| 0     | 11       | 4.85%   |
| 3     | 1        | 0.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 177      | 57.65%  |
| Intel                      | 82       | 26.71%  |
| Qualcomm Atheros           | 15       | 4.89%   |
| Nvidia                     | 8        | 2.61%   |
| TP-Link                    | 4        | 1.3%    |
| Ralink Technology          | 3        | 0.98%   |
| Microchip Technology       | 3        | 0.98%   |
| MCST                       | 3        | 0.98%   |
| VIA Technologies           | 2        | 0.65%   |
| Ralink                     | 2        | 0.65%   |
| Marvell Technology Group   | 2        | 0.65%   |
| ZTE WCDMA Technologies MSM | 1        | 0.33%   |
| Xiaomi                     | 1        | 0.33%   |
| Vimtron Electronics        | 1        | 0.33%   |
| U-Blox                     | 1        | 0.33%   |
| D-Link                     | 1        | 0.33%   |
| Broadcom Limited           | 1        | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 111      | 32.94%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 46       | 13.65%  |
| Intel Ethernet Connection I219-LM                                 | 34       | 10.09%  |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 5.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 1.78%   |
| Intel Wireless 3165                                               | 6        | 1.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.48%   |
| Intel Ethernet Connection (14) I219-V                             | 5        | 1.48%   |
| Intel Ethernet Connection (13) I219-V                             | 4        | 1.19%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.89%   |
| Microchip MCP2221 USB-I2C/UART Combo                              | 3        | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 0.89%   |
| Intel I211 Gigabit Network Connection                             | 3        | 0.89%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3        | 0.89%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2        | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.59%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.59%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.59%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.59%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.59%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.59%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.59%   |
| Intel Wireless-AC 9260                                            | 2        | 0.59%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.59%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.59%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 1        | 0.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.3%    |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.3%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.3%    |
| U-Blox [u-blox 7]                                                 | 1        | 0.3%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 17       | 39.53%  |
| Realtek Semiconductor | 14       | 32.56%  |
| TP-Link               | 4        | 9.3%    |
| Ralink Technology     | 3        | 6.98%   |
| Qualcomm Atheros      | 3        | 6.98%   |
| Ralink                | 2        | 4.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                        | 6        | 13.95%  |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 3        | 6.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 3        | 6.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 3        | 6.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 3        | 6.98%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 2        | 4.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2        | 4.65%   |
| Ralink MT7601U Wireless Adapter                            | 2        | 4.65%   |
| Intel Wireless-AC 9260                                     | 2        | 4.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1        | 2.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 2.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1        | 2.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 1        | 2.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1        | 2.33%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 2.33%   |
| Realtek 802.11ac NIC                                       | 1        | 2.33%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 2.33%   |
| Ralink RT5392 PCIe Wireless Network Adapter                | 1        | 2.33%   |
| Ralink RT2561/RT61 rev B 802.11g                           | 1        | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 2.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 2.33%   |
| Intel Wi-Fi 6 AX200                                        | 1        | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1        | 2.33%   |
| Intel Centrino Wireless-N 2230                             | 1        | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 174      | 61.27%  |
| Intel                      | 77       | 27.11%  |
| Qualcomm Atheros           | 12       | 4.23%   |
| Nvidia                     | 8        | 2.82%   |
| MCST                       | 3        | 1.06%   |
| VIA Technologies           | 2        | 0.7%    |
| Marvell Technology Group   | 2        | 0.7%    |
| ZTE WCDMA Technologies MSM | 1        | 0.35%   |
| Xiaomi                     | 1        | 0.35%   |
| Vimtron Electronics        | 1        | 0.35%   |
| TP-Link                    | 1        | 0.35%   |
| D-Link                     | 1        | 0.35%   |
| Broadcom Limited           | 1        | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 111      | 38.41%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 46       | 15.92%  |
| Intel Ethernet Connection I219-LM                                 | 34       | 11.76%  |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 6.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.73%   |
| Intel Ethernet Connection (14) I219-V                             | 5        | 1.73%   |
| Intel Ethernet Connection (13) I219-V                             | 4        | 1.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 1.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.04%   |
| Intel I211 Gigabit Network Connection                             | 3        | 1.04%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.04%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.69%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.69%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.69%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.69%   |
| MCST Gigabit Ethernet Controller                                  | 2        | 0.69%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.69%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.69%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 1        | 0.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.35%   |
| Vimtron Mobile Composite Device Bus                               | 1        | 0.35%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.35%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.35%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.35%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.35%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.35%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.35%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.35%   |
| MCST Gigabit Ethernet                                             | 1        | 0.35%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.35%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.35%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 224      | 82.35%  |
| WiFi     | 43       | 15.81%  |
| Modem    | 4        | 1.47%   |
| Unknown  | 1        | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 204      | 90.27%  |
| WiFi     | 22       | 9.73%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 186      | 82.67%  |
| 2     | 34       | 15.11%  |
| 3     | 2        | 0.89%   |
| 13    | 1        | 0.44%   |
| 8     | 1        | 0.44%   |
| 0     | 1        | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 219      | 96.9%   |
| Yes  | 7        | 3.1%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 16       | 44.44%  |
| Cambridge Silicon Radio | 11       | 30.56%  |
| Realtek Semiconductor   | 3        | 8.33%   |
| IMC Networks            | 3        | 8.33%   |
| Broadcom                | 2        | 5.56%   |
| Logitech                | 1        | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11       | 30.56%  |
| Intel Bluetooth wireless interface                  | 9        | 25%     |
| Realtek Bluetooth Radio                             | 2        | 5.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 5.56%   |
| Intel AX210 Bluetooth                               | 2        | 5.56%   |
| IMC Networks Bluetooth Radio                        | 2        | 5.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 2.78%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 2.78%   |
| Intel AX201 Bluetooth                               | 1        | 2.78%   |
| Intel AX200 Bluetooth                               | 1        | 2.78%   |
| IMC Networks Bluetooth Device                       | 1        | 2.78%   |
| Broadcom Bluetooth dongle                           | 1        | 2.78%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 161      | 53.31%  |
| AMD                 | 63       | 20.86%  |
| Nvidia              | 57       | 18.87%  |
| C-Media Electronics | 6        | 1.99%   |
| MCST                | 3        | 0.99%   |
| JMTek               | 2        | 0.66%   |
| Creative Technology | 2        | 0.66%   |
| Zhaoxin             | 1        | 0.33%   |
| VIA Technologies    | 1        | 0.33%   |
| Texas Instruments   | 1        | 0.33%   |
| Goldvish            | 1        | 0.33%   |
| EasyPass Industrial | 1        | 0.33%   |
| Creative Labs       | 1        | 0.33%   |
| Apple               | 1        | 0.33%   |
| A4Tech              | 1        | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 69       | 20.66%  |
| Nvidia GP107GL High Definition Audio Controller                            | 20       | 5.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 4.49%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14       | 4.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 2.99%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 2.99%   |
| AMD FCH Azalia Controller                                                  | 9        | 2.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 2.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 2.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 2.1%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 1.8%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 1.5%    |
| Intel Smart Sound Technology (SST) Audio Controller                        | 5        | 1.5%    |
| Intel Comet Lake PCH-V cAVS                                                | 5        | 1.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.5%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 1.5%    |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4        | 1.2%    |
| Intel Sunrise Point-LP HD Audio                                            | 4        | 1.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 1.2%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4        | 1.2%    |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 1.2%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4        | 1.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.2%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 3        | 0.9%    |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 0.9%    |
| MCST HD Audio                                                              | 3        | 0.9%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3        | 0.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 0.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.9%    |
| AMD Trinity HDMI Audio Controller                                          | 3        | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 0.9%    |
| AMD Kaveri HDMI/DP Audio Controller                                        | 3        | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.6%    |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 31       | 20%     |
| Unknown             | 25       | 16.13%  |
| Kingston            | 23       | 14.84%  |
| Samsung Electronics | 17       | 10.97%  |
| Micron Technology   | 14       | 9.03%   |
| SK hynix            | 7        | 4.52%   |
| Foxline             | 5        | 3.23%   |
| Apacer              | 5        | 3.23%   |
| Patriot             | 3        | 1.94%   |
| A-DATA Technology   | 3        | 1.94%   |
| Unknown             | 3        | 1.94%   |
| GOODRAM             | 2        | 1.29%   |
| Goldkey             | 2        | 1.29%   |
| Corsair             | 2        | 1.29%   |
| AMD                 | 2        | 1.29%   |
| Wilk                | 1        | 0.65%   |
| Unknown (0x0B7A)    | 1        | 0.65%   |
| Unknown (081A)      | 1        | 0.65%   |
| tigo                | 1        | 0.65%   |
| Shenzhen Longsys    | 1        | 0.65%   |
| Ramaxel Technology  | 1        | 0.65%   |
| Qumo                | 1        | 0.65%   |
| Juhor               | 1        | 0.65%   |
| Golden Empire       | 1        | 0.65%   |
| G.Skill             | 1        | 0.65%   |
| Elpida              | 1        | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s   | 13       | 7.69%   |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s               | 10       | 5.92%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s | 4        | 2.37%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 3        | 1.78%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s   | 3        | 1.78%   |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s | 3        | 1.78%   |
| Unknown                                                | 3        | 1.78%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 1.18%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 2        | 1.18%   |
| Unknown RAM Module 1024MB DIMM                         | 2        | 1.18%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s  | 2        | 1.18%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 2        | 1.18%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s   | 2        | 1.18%   |
| Samsung RAM M378A1K43EB2-CVF 8GB DIMM DDR4 3266MT/s    | 2        | 1.18%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 2        | 1.18%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s    | 2        | 1.18%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s  | 2        | 1.18%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s    | 2        | 1.18%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s | 2        | 1.18%   |
| Apacer RAM D12.2324CC.001 8GB DIMM DDR4 2667MT/s       | 2        | 1.18%   |
| Wilk RAM IRX3000D464L16S/8G 8GB DIMM DDR4 3200MT/s     | 1        | 0.59%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s           | 1        | 0.59%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s              | 1        | 0.59%   |
| Unknown RAM Module 512MB DIMM 400MT/s                  | 1        | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 0.59%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.59%   |
| Unknown RAM Module 4096MB DIMM 333MT/s                 | 1        | 0.59%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 1        | 0.59%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s              | 1        | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM SDRAM 533MT/s           | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s            | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                 | 1        | 0.59%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 1        | 0.59%   |
| Unknown RAM Module 1024MB DIMM SDRAM 533MT/s           | 1        | 0.59%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 1        | 0.59%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s            | 1        | 0.59%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s             | 1        | 0.59%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 1        | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 94       | 65.73%  |
| DDR3    | 26       | 18.18%  |
| Unknown | 13       | 9.09%   |
| SDRAM   | 4        | 2.8%    |
| DDR2    | 4        | 2.8%    |
| DDR     | 2        | 1.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 125      | 87.41%  |
| SODIMM | 18       | 12.59%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 59       | 39.6%   |
| 8192  | 56       | 37.58%  |
| 2048  | 12       | 8.05%   |
| 1024  | 10       | 6.71%   |
| 16384 | 8        | 5.37%   |
| 512   | 3        | 2.01%   |
| 32768 | 1        | 0.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2400    | 40       | 25.97%  |
| 3200    | 17       | 11.04%  |
| 2667    | 15       | 9.74%   |
| 1600    | 14       | 9.09%   |
| 2133    | 9        | 5.84%   |
| 1333    | 9        | 5.84%   |
| 800     | 5        | 3.25%   |
| 2933    | 4        | 2.6%    |
| 667     | 4        | 2.6%    |
| Unknown | 4        | 2.6%    |
| 3600    | 3        | 1.95%   |
| 3266    | 3        | 1.95%   |
| 1866    | 3        | 1.95%   |
| 533     | 3        | 1.95%   |
| 400     | 3        | 1.95%   |
| 3466    | 2        | 1.3%    |
| 3066    | 2        | 1.3%    |
| 333     | 2        | 1.3%    |
| 4333    | 1        | 0.65%   |
| 3534    | 1        | 0.65%   |
| 3333    | 1        | 0.65%   |
| 3151    | 1        | 0.65%   |
| 2866    | 1        | 0.65%   |
| 2800    | 1        | 0.65%   |
| 2666    | 1        | 0.65%   |
| 2448    | 1        | 0.65%   |
| 1867    | 1        | 0.65%   |
| 1648    | 1        | 0.65%   |
| 1066    | 1        | 0.65%   |
| 32      | 1        | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 33.33%  |
| Hewlett-Packard     | 4        | 26.67%  |
| Canon               | 4        | 26.67%  |
| QinHeng Electronics | 2        | 13.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| QinHeng CH340S                 | 2        | 13.33%  |
| HP LaserJet 1010               | 2        | 13.33%  |
| Samsung SCX-4200 series        | 1        | 6.67%   |
| Samsung SCX-3400 Series        | 1        | 6.67%   |
| Samsung SCX-3200 Series        | 1        | 6.67%   |
| Samsung M332x 382x 402x Series | 1        | 6.67%   |
| Samsung CLX-3180 Series        | 1        | 6.67%   |
| HP LaserJet P1102              | 1        | 6.67%   |
| HP LaserJet M402dn             | 1        | 6.67%   |
| Canon MF4410                   | 1        | 6.67%   |
| Canon MF4010 series            | 1        | 6.67%   |
| Canon MF3110                   | 1        | 6.67%   |
| Canon G1010 series             | 1        | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LIDE 25  | 1        | 50%     |
| Canon CanoScan LiDE 110 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 19       | 52.78%  |
| Alcor Micro             | 7        | 19.44%  |
| Microdia                | 2        | 5.56%   |
| Z-Star Microelectronics | 1        | 2.78%   |
| Unknown                 | 1        | 2.78%   |
| Microsoft               | 1        | 2.78%   |
| lihappe8                | 1        | 2.78%   |
| Hewlett-Packard         | 1        | 2.78%   |
| GEMBIRD                 | 1        | 2.78%   |
| Apple                   | 1        | 2.78%   |
| Unknown                 | 1        | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Logitech Webcam C270               | 11       | 30.56%  |
| Alcor Micro USB 2.0 PC Camera      | 5        | 13.89%  |
| Microdia Camera                    | 2        | 5.56%   |
| Logitech HD Pro Webcam C920        | 2        | 5.56%   |
| Logitech C505 HD Webcam            | 2        | 5.56%   |
| Alcor Micro SHUNCCM2MP             | 2        | 5.56%   |
| Z-Star Venus USB2.0 Camera         | 1        | 2.78%   |
| Unknown HD camera                  | 1        | 2.78%   |
| Microsoft LifeCam VX-700           | 1        | 2.78%   |
| Logitech Webcam C930e              | 1        | 2.78%   |
| Logitech HD Webcam C615            | 1        | 2.78%   |
| Logitech HD Webcam C525            | 1        | 2.78%   |
| Logitech B525 HD Webcam            | 1        | 2.78%   |
| lihappe8 USB 2.0 Camera            | 1        | 2.78%   |
| HP Webcam HD 2300                  | 1        | 2.78%   |
| GEMBIRD USB2.0 PC CAMERA           | 1        | 2.78%   |
| Apple iSight in LED Cinema Display | 1        | 2.78%   |
| Unknown                            | 1        | 2.78%   |

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
| 0     | 210      | 92.11%  |
| 1     | 15       | 6.58%   |
| 2     | 2        | 0.88%   |
| 5     | 1        | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 8        | 36.36%  |
| Graphics card            | 5        | 22.73%  |
| Net/ethernet             | 2        | 9.09%   |
| Multimedia controller    | 2        | 9.09%   |
| Unassigned class         | 1        | 4.55%   |
| Sound                    | 1        | 4.55%   |
| Net/wireless             | 1        | 4.55%   |
| Chipcard                 | 1        | 4.55%   |
| Bluetooth                | 1        | 4.55%   |

