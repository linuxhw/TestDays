RHEL - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for RHEL.

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

Total: 301

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 7490               | [5781936456](https://linux-hardware.org/?probe=5781936456) | Dec 31, 2024 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [ea8d4bb295](https://linux-hardware.org/?probe=ea8d4bb295) | Nov 24, 2024 |
| Acer          | Aspire A515-45              | [a10f9b0aa6](https://linux-hardware.org/?probe=a10f9b0aa6) | Nov 17, 2024 |
| HP            | EliteBook 840 G5            | [3d9365dd8e](https://linux-hardware.org/?probe=3d9365dd8e) | Nov 08, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [9f24fcf5f6](https://linux-hardware.org/?probe=9f24fcf5f6) | Nov 07, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1a592a4c8c](https://linux-hardware.org/?probe=1a592a4c8c) | Oct 30, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [88c68a9636](https://linux-hardware.org/?probe=88c68a9636) | Oct 19, 2024 |
| Dell          | Latitude E6520              | [1fccf13e1b](https://linux-hardware.org/?probe=1fccf13e1b) | Oct 14, 2024 |
| UNOWHY        | Y13G010S4EI                 | [8b9768888f](https://linux-hardware.org/?probe=8b9768888f) | Sep 29, 2024 |
| UNOWHY        | Y13G010S4EI                 | [8bc1a2e515](https://linux-hardware.org/?probe=8bc1a2e515) | Sep 25, 2024 |
| Dell          | Precision 7730              | [7f0ef4c558](https://linux-hardware.org/?probe=7f0ef4c558) | Sep 19, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [325da6b558](https://linux-hardware.org/?probe=325da6b558) | Sep 16, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [7a11752435](https://linux-hardware.org/?probe=7a11752435) | Sep 11, 2024 |
| Dell          | Precision 7530              | [f24cdeec73](https://linux-hardware.org/?probe=f24cdeec73) | Aug 18, 2024 |
| Lenovo        | IdeaPad S145-15API 81UT     | [4d550f9d4c](https://linux-hardware.org/?probe=4d550f9d4c) | Jul 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [37e0d80500](https://linux-hardware.org/?probe=37e0d80500) | Jul 12, 2024 |
| Unknown       | G13                         | [ac710043ec](https://linux-hardware.org/?probe=ac710043ec) | Jul 09, 2024 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | [07807f87ab](https://linux-hardware.org/?probe=07807f87ab) | Jul 04, 2024 |
| HP            | EliteBook 855 G7 Noteboo... | [70d021b045](https://linux-hardware.org/?probe=70d021b045) | Jul 02, 2024 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [cd307f9782](https://linux-hardware.org/?probe=cd307f9782) | Jun 27, 2024 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [5f79f30b85](https://linux-hardware.org/?probe=5f79f30b85) | Jun 19, 2024 |
| Dell          | Latitude 5340               | [f8bada88dd](https://linux-hardware.org/?probe=f8bada88dd) | Jun 15, 2024 |
| Dell          | Latitude 5520               | [c1a7e532c9](https://linux-hardware.org/?probe=c1a7e532c9) | Jun 10, 2024 |
| Dell          | Latitude 3340               | [0179e77195](https://linux-hardware.org/?probe=0179e77195) | Jun 10, 2024 |
| Dell          | Latitude 3340               | [3719b02ec1](https://linux-hardware.org/?probe=3719b02ec1) | Jun 10, 2024 |
| HP            | EliteBook 860 16 inch G1... | [a2f0057f55](https://linux-hardware.org/?probe=a2f0057f55) | Jun 05, 2024 |
| HP            | EliteBook 860 16 inch G1... | [75728b162c](https://linux-hardware.org/?probe=75728b162c) | Jun 04, 2024 |
| HP            | Stream Laptop 11-ak0xxx     | [564a4d2df9](https://linux-hardware.org/?probe=564a4d2df9) | May 27, 2024 |
| Dell          | Precision 7540              | [4703617413](https://linux-hardware.org/?probe=4703617413) | May 07, 2024 |
| Dell          | Precision 7540              | [37638500df](https://linux-hardware.org/?probe=37638500df) | May 07, 2024 |
| HP            | ZBook Fury 16 G9 Mobile ... | [10ff3b22cf](https://linux-hardware.org/?probe=10ff3b22cf) | Apr 03, 2024 |
| HP            | ZBook Fury 16 G9 Mobile ... | [896bd3d75a](https://linux-hardware.org/?probe=896bd3d75a) | Apr 03, 2024 |
| HP            | ZBook Fury 15 G7 Mobile ... | [59749a8b22](https://linux-hardware.org/?probe=59749a8b22) | Mar 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [24f8aa7cd0](https://linux-hardware.org/?probe=24f8aa7cd0) | Mar 07, 2024 |
| MSI           | Modern 15 A5M               | [e591b9e544](https://linux-hardware.org/?probe=e591b9e544) | Feb 04, 2024 |
| Dell          | Inspiron N5040              | [7cd09c7dde](https://linux-hardware.org/?probe=7cd09c7dde) | Jan 25, 2024 |
| LG Electro... | 15Z95P-GRLGL                | [ce6c983048](https://linux-hardware.org/?probe=ce6c983048) | Jan 24, 2024 |
| LG Electro... | 15Z95P-GRLGL                | [9dcc8bbc45](https://linux-hardware.org/?probe=9dcc8bbc45) | Jan 24, 2024 |
| Dell          | Precision M4800             | [dccdba8512](https://linux-hardware.org/?probe=dccdba8512) | Jan 21, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d4e6e0ae3e](https://linux-hardware.org/?probe=d4e6e0ae3e) | Jan 19, 2024 |
| MSI           | Katana GF76 12UC            | [73c3208c03](https://linux-hardware.org/?probe=73c3208c03) | Jan 10, 2024 |
| MSI           | Katana GF76 12UC            | [15db2ea112](https://linux-hardware.org/?probe=15db2ea112) | Jan 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [2bb251ffbb](https://linux-hardware.org/?probe=2bb251ffbb) | Jan 09, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1abf742848](https://linux-hardware.org/?probe=1abf742848) | Jan 09, 2024 |
| Dell          | Precision 3480              | [e81f3e856b](https://linux-hardware.org/?probe=e81f3e856b) | Jan 03, 2024 |
| Dell          | Latitude 5340               | [c9d3b3d7a7](https://linux-hardware.org/?probe=c9d3b3d7a7) | Dec 19, 2023 |
| Dell          | Precision 7530              | [e75b16ca5e](https://linux-hardware.org/?probe=e75b16ca5e) | Dec 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [5c4714ecce](https://linux-hardware.org/?probe=5c4714ecce) | Dec 01, 2023 |
| Lenovo        | ThinkPad L480 20LS0015UK    | [5f786955fc](https://linux-hardware.org/?probe=5f786955fc) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-14IKB U 81F... | [0b06f82d9d](https://linux-hardware.org/?probe=0b06f82d9d) | Nov 19, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [1c3bf8f6ef](https://linux-hardware.org/?probe=1c3bf8f6ef) | Oct 19, 2023 |
| System76      | Galago Pro                  | [fbdb665814](https://linux-hardware.org/?probe=fbdb665814) | Oct 03, 2023 |
| Dell          | Inspiron N5010              | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| Dell          | G16 7620                    | [cd30e51d53](https://linux-hardware.org/?probe=cd30e51d53) | Sep 27, 2023 |
| Dell          | Precision 7720              | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Dell          | Latitude 5420               | [f2bb4ee9f0](https://linux-hardware.org/?probe=f2bb4ee9f0) | Sep 23, 2023 |
| HP            | ProBook 640 G2              | [c0af84c629](https://linux-hardware.org/?probe=c0af84c629) | Sep 02, 2023 |
| Lenovo        | ThinkPad T490 20N3S77601    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| MSI           | Katana GF66 12UC            | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| HP            | Laptop 15-bs0xx             | [5f2a27253a](https://linux-hardware.org/?probe=5f2a27253a) | Aug 21, 2023 |
| HP            | Laptop 15-bs0xx             | [5e76f9bfc3](https://linux-hardware.org/?probe=5e76f9bfc3) | Aug 21, 2023 |
| HP            | EliteBook 2570p             | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [49ecdacd71](https://linux-hardware.org/?probe=49ecdacd71) | May 14, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [5938e62d47](https://linux-hardware.org/?probe=5938e62d47) | Apr 17, 2023 |
| Dell          | Precision 7510              | [f68123c20a](https://linux-hardware.org/?probe=f68123c20a) | Apr 13, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [de656b2182](https://linux-hardware.org/?probe=de656b2182) | Apr 06, 2023 |
| ASUSTek       | X550ZA                      | [cc243873e2](https://linux-hardware.org/?probe=cc243873e2) | Mar 26, 2023 |
| ASUSTek       | X550ZA                      | [2e55d2163a](https://linux-hardware.org/?probe=2e55d2163a) | Mar 26, 2023 |
| HP            | ProBook 640 G2              | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [52e2d79bad](https://linux-hardware.org/?probe=52e2d79bad) | Mar 01, 2023 |
| Getac         | B360                        | [c4bd09adf1](https://linux-hardware.org/?probe=c4bd09adf1) | Mar 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [affa3bb9f1](https://linux-hardware.org/?probe=affa3bb9f1) | Feb 19, 2023 |
| Dell          | Precision 7560              | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI           | GP75 Leopard 9SD            | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [2a4e6ab2d4](https://linux-hardware.org/?probe=2a4e6ab2d4) | Feb 07, 2023 |
| Getac         | S410G4                      | [81b80297ab](https://linux-hardware.org/?probe=81b80297ab) | Feb 06, 2023 |
| Getac         | S410G4                      | [1d8e6ad383](https://linux-hardware.org/?probe=1d8e6ad383) | Feb 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [701a355d37](https://linux-hardware.org/?probe=701a355d37) | Feb 04, 2023 |
| Dell          | Latitude 9420               | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell          | Latitude 3410               | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [34169c74c5](https://linux-hardware.org/?probe=34169c74c5) | Dec 31, 2022 |
| HP            | EliteBook 2570p             | [199df541f2](https://linux-hardware.org/?probe=199df541f2) | Dec 21, 2022 |
| MSI           | GE72VR 7RF                  | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [64fb254a64](https://linux-hardware.org/?probe=64fb254a64) | Nov 17, 2022 |
| Dell          | Latitude E7450              | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [de9e18e6ca](https://linux-hardware.org/?probe=de9e18e6ca) | Nov 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek       | Z450LA                      | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP            | 340S G7                     | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [8656acec04](https://linux-hardware.org/?probe=8656acec04) | Sep 14, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [23649c49e3](https://linux-hardware.org/?probe=23649c49e3) | Sep 14, 2022 |
| Dell          | Precision 7510              | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [3df0bebc37](https://linux-hardware.org/?probe=3df0bebc37) | Aug 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [71c31086e6](https://linux-hardware.org/?probe=71c31086e6) | Jul 11, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [714c212f51](https://linux-hardware.org/?probe=714c212f51) | Jul 08, 2022 |
| Dell          | Inspiron 5559               | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | ThinkPad T480 20L60034MX    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [d77ce7a3f7](https://linux-hardware.org/?probe=d77ce7a3f7) | Jun 13, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| Dell          | XPS 17 9710                 | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell          | XPS 17 9710                 | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S29D02    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell          | Precision 5550              | [949f4a7658](https://linux-hardware.org/?probe=949f4a7658) | Apr 19, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [7763003308](https://linux-hardware.org/?probe=7763003308) | Mar 31, 2022 |
| Dell          | Precision 7560              | [2abd72978c](https://linux-hardware.org/?probe=2abd72978c) | Mar 29, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [14ea45c4d7](https://linux-hardware.org/?probe=14ea45c4d7) | Mar 03, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [eed6e0f012](https://linux-hardware.org/?probe=eed6e0f012) | Mar 01, 2022 |
| Lenovo        | Z40-70 20366                | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | [7b31f4ca0b](https://linux-hardware.org/?probe=7b31f4ca0b) | Feb 05, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [b3ef38d0ef](https://linux-hardware.org/?probe=b3ef38d0ef) | Jan 31, 2022 |
| Dell          | Latitude E5570              | [87ec93dcdc](https://linux-hardware.org/?probe=87ec93dcdc) | Jan 31, 2022 |
| Lenovo        | ThinkPad T490 20N3S5DV0S    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [a60504e123](https://linux-hardware.org/?probe=a60504e123) | Jan 29, 2022 |
| HP            | EliteBook 8460p             | [335a0c0490](https://linux-hardware.org/?probe=335a0c0490) | Jan 28, 2022 |
| Samsung       | 730QCJ/730QCR               | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| ASUSTek       | X550VX                      | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| Toshiba       | Satellite Pro R50-C         | [012f2de3d5](https://linux-hardware.org/?probe=012f2de3d5) | Dec 28, 2021 |
| Toshiba       | Satellite Pro R50-C         | [2e716df6c6](https://linux-hardware.org/?probe=2e716df6c6) | Dec 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Dell          | Precision 3551              | [cbddfb522a](https://linux-hardware.org/?probe=cbddfb522a) | Dec 21, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Acer          | Nitro AN515-54              | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Gigabyte      | AERO 15 KD                  | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [f766090339](https://linux-hardware.org/?probe=f766090339) | Nov 16, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [ece232f046](https://linux-hardware.org/?probe=ece232f046) | Nov 11, 2021 |
| Lenovo        | ThinkPad P50 20ENS1L000     | [318b5aea2b](https://linux-hardware.org/?probe=318b5aea2b) | Nov 08, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [59dfcd3b23](https://linux-hardware.org/?probe=59dfcd3b23) | Oct 22, 2021 |
| HP            | ZBook Firefly 15 inch G8... | [49d20bd238](https://linux-hardware.org/?probe=49d20bd238) | Oct 12, 2021 |
| Lenovo        | ThinkPad P50 20ENS1L000     | [f8443770b9](https://linux-hardware.org/?probe=f8443770b9) | Oct 08, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | [042f9bec29](https://linux-hardware.org/?probe=042f9bec29) | Oct 06, 2021 |
| Lenovo        | ThinkPad T470 20HES57W00    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [a667466f62](https://linux-hardware.org/?probe=a667466f62) | Sep 17, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [502a6b96a3](https://linux-hardware.org/?probe=502a6b96a3) | Sep 13, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [daadb8ccc0](https://linux-hardware.org/?probe=daadb8ccc0) | Sep 06, 2021 |
| Dell          | XPS 15 9560                 | [952dd9f6f5](https://linux-hardware.org/?probe=952dd9f6f5) | Sep 01, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [7bf4b860a8](https://linux-hardware.org/?probe=7bf4b860a8) | Aug 26, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Dell          | XPS 15 9560                 | [1bb9bd9d46](https://linux-hardware.org/?probe=1bb9bd9d46) | Jul 27, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| HP            | ZBook 15 G5                 | [9f9cc51cda](https://linux-hardware.org/?probe=9f9cc51cda) | Jul 20, 2021 |
| Dell          | Latitude E5510              | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [7e7fbaff11](https://linux-hardware.org/?probe=7e7fbaff11) | Jul 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [c4091b8c8c](https://linux-hardware.org/?probe=c4091b8c8c) | Jul 09, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [a03b6b86cc](https://linux-hardware.org/?probe=a03b6b86cc) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [500c95d16b](https://linux-hardware.org/?probe=500c95d16b) | Jul 03, 2021 |
| Dell          | Latitude E6430              | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell          | Latitude E6430              | [ed72da5de8](https://linux-hardware.org/?probe=ed72da5de8) | Jun 25, 2021 |
| Dell          | Latitude E6430              | [899e8720e1](https://linux-hardware.org/?probe=899e8720e1) | Jun 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [eccdf8e8c1](https://linux-hardware.org/?probe=eccdf8e8c1) | Jun 20, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [a703424a8c](https://linux-hardware.org/?probe=a703424a8c) | Jun 13, 2021 |
| Dell          | Precision 3541              | [984db774ed](https://linux-hardware.org/?probe=984db774ed) | Jun 08, 2021 |
| HP            | ZBook Studio G5             | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| Dell          | Latitude E6530              | [2e9b8200a9](https://linux-hardware.org/?probe=2e9b8200a9) | May 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [c51ae8a5ff](https://linux-hardware.org/?probe=c51ae8a5ff) | May 28, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [65666a7bec](https://linux-hardware.org/?probe=65666a7bec) | May 17, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | [bf95cd0ce7](https://linux-hardware.org/?probe=bf95cd0ce7) | Apr 20, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [349f951788](https://linux-hardware.org/?probe=349f951788) | Apr 18, 2021 |
| Dell          | Inspiron 3559               | [854655e305](https://linux-hardware.org/?probe=854655e305) | Apr 14, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [f98af88440](https://linux-hardware.org/?probe=f98af88440) | Apr 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [ee5d8875e3](https://linux-hardware.org/?probe=ee5d8875e3) | Mar 11, 2021 |
| Lenovo        | ThinkPad T460 20FMS1VA09    | [5bc6b53ecf](https://linux-hardware.org/?probe=5bc6b53ecf) | Mar 03, 2021 |
| Lenovo        | ThinkPad T460 20FMS1VA09    | [55314e09ff](https://linux-hardware.org/?probe=55314e09ff) | Mar 03, 2021 |
| Lenovo        | ThinkPad W530 2441B32       | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [c6fd48fe3f](https://linux-hardware.org/?probe=c6fd48fe3f) | Feb 28, 2021 |
| Dell          | Precision 5510              | [2d4aed7f6c](https://linux-hardware.org/?probe=2d4aed7f6c) | Feb 22, 2021 |
| Sony          | VPCEB4L1R                   | [1744d5db17](https://linux-hardware.org/?probe=1744d5db17) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [071f1be343](https://linux-hardware.org/?probe=071f1be343) | Feb 09, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [832d7f19ae](https://linux-hardware.org/?probe=832d7f19ae) | Feb 02, 2021 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | [bdff7fe555](https://linux-hardware.org/?probe=bdff7fe555) | Jan 28, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [3e0d4ac7c7](https://linux-hardware.org/?probe=3e0d4ac7c7) | Jan 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1a1bbc078f](https://linux-hardware.org/?probe=1a1bbc078f) | Jan 18, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [d606944d2b](https://linux-hardware.org/?probe=d606944d2b) | Jan 10, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [e24d02bc67](https://linux-hardware.org/?probe=e24d02bc67) | Jan 05, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [e1e788633e](https://linux-hardware.org/?probe=e1e788633e) | Dec 22, 2020 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [f95e7c46f7](https://linux-hardware.org/?probe=f95e7c46f7) | Dec 14, 2020 |
| Dell          | Latitude 5290               | [f69f594914](https://linux-hardware.org/?probe=f69f594914) | Dec 09, 2020 |
| Dell          | Latitude 5290               | [538342789e](https://linux-hardware.org/?probe=538342789e) | Dec 09, 2020 |
| HP            | Pavilion 14                 | [bed5ca82b9](https://linux-hardware.org/?probe=bed5ca82b9) | Dec 03, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | [a70d23cd77](https://linux-hardware.org/?probe=a70d23cd77) | Dec 02, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | [b446c7d5a5](https://linux-hardware.org/?probe=b446c7d5a5) | Dec 02, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | [81c97fb756](https://linux-hardware.org/?probe=81c97fb756) | Dec 02, 2020 |
| Lenovo        | ThinkPad T460 20BUS0QT0A    | [c0487ec734](https://linux-hardware.org/?probe=c0487ec734) | Dec 02, 2020 |
| HP            | ZBook 14u G6                | [84782d875f](https://linux-hardware.org/?probe=84782d875f) | Nov 27, 2020 |
| Dell          | Precision 7510              | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| TUXEDO        | N13xWU                      | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell          | Inspiron 5567               | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| Dell          | Latitude E6420              | [363320d61e](https://linux-hardware.org/?probe=363320d61e) | Nov 11, 2020 |
| Dell          | Latitude E6420              | [8a37aaac86](https://linux-hardware.org/?probe=8a37aaac86) | Nov 11, 2020 |
| TUXEDO        | N13xWU                      | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Dell          | Precision 7510              | [432ebce0a4](https://linux-hardware.org/?probe=432ebce0a4) | Nov 03, 2020 |
| HP            | Pavilion 14                 | [d8220245e5](https://linux-hardware.org/?probe=d8220245e5) | Nov 01, 2020 |
| Dell          | Precision 7510              | [a564df5de7](https://linux-hardware.org/?probe=a564df5de7) | Nov 01, 2020 |
| Lenovo        | ThinkPad T520 42404CG       | [1ca04091de](https://linux-hardware.org/?probe=1ca04091de) | Oct 24, 2020 |
| Lenovo        | ThinkPad T520 42404CG       | [2e3d64e7c5](https://linux-hardware.org/?probe=2e3d64e7c5) | Oct 24, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [f2907d324d](https://linux-hardware.org/?probe=f2907d324d) | Oct 21, 2020 |
| Dell          | Latitude 5300               | [4169f50442](https://linux-hardware.org/?probe=4169f50442) | Oct 18, 2020 |
| Dell          | Latitude 5300               | [4bd822b6e3](https://linux-hardware.org/?probe=4bd822b6e3) | Oct 15, 2020 |
| HP            | Pavilion 14                 | [b29b04ed35](https://linux-hardware.org/?probe=b29b04ed35) | Oct 08, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | [2bc1a5b44a](https://linux-hardware.org/?probe=2bc1a5b44a) | Oct 01, 2020 |
| Lenovo        | ThinkPad P50 20EN0005UK     | [94c1b32081](https://linux-hardware.org/?probe=94c1b32081) | Sep 21, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | [e3dab03999](https://linux-hardware.org/?probe=e3dab03999) | Sep 01, 2020 |
| HP            | ProBook 430 G5              | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Dell          | Inspiron N5110              | [8b995a24c1](https://linux-hardware.org/?probe=8b995a24c1) | Aug 04, 2020 |
| Dell          | Inspiron N5110              | [97293b7aa0](https://linux-hardware.org/?probe=97293b7aa0) | Aug 04, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | [93b236ab24](https://linux-hardware.org/?probe=93b236ab24) | Aug 01, 2020 |
| ASUSTek       | GL502VMK                    | [7556ef6b87](https://linux-hardware.org/?probe=7556ef6b87) | Jul 22, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU27    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Dell          | Latitude 5300               | [65284e0295](https://linux-hardware.org/?probe=65284e0295) | Jul 04, 2020 |
| Timi          | TM1707                      | [84538e3769](https://linux-hardware.org/?probe=84538e3769) | Jun 30, 2020 |
| Timi          | TM1707                      | [1267830169](https://linux-hardware.org/?probe=1267830169) | Jun 30, 2020 |
| ASUSTek       | GL502VMK                    | [45e4ef6c32](https://linux-hardware.org/?probe=45e4ef6c32) | Jun 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [ce5bce7893](https://linux-hardware.org/?probe=ce5bce7893) | Jun 19, 2020 |
| Dell          | Latitude 5300               | [8ebae81f7c](https://linux-hardware.org/?probe=8ebae81f7c) | Jun 18, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | [b74e2f66bd](https://linux-hardware.org/?probe=b74e2f66bd) | May 29, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | [de063b9994](https://linux-hardware.org/?probe=de063b9994) | May 28, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [9b51817b92](https://linux-hardware.org/?probe=9b51817b92) | May 26, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| HP            | ProBook 430 G5              | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP            | ProBook 430 G5              | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | [0108b32128](https://linux-hardware.org/?probe=0108b32128) | May 07, 2020 |
| Dell          | G3 3779                     | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Dell          | Precision 5540              | [3c0f6bcf28](https://linux-hardware.org/?probe=3c0f6bcf28) | Apr 29, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0B50... | [ea2a99e61e](https://linux-hardware.org/?probe=ea2a99e61e) | Apr 12, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | [d955389819](https://linux-hardware.org/?probe=d955389819) | Mar 27, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC00    | [c86bb46fad](https://linux-hardware.org/?probe=c86bb46fad) | Mar 26, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC00    | [79d1c623b5](https://linux-hardware.org/?probe=79d1c623b5) | Mar 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [07d54a6a50](https://linux-hardware.org/?probe=07d54a6a50) | Mar 24, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0B50... | [e2eabf79b0](https://linux-hardware.org/?probe=e2eabf79b0) | Mar 03, 2020 |
| Sony          | VPCEB23FM                   | [908bc46e69](https://linux-hardware.org/?probe=908bc46e69) | Feb 27, 2020 |
| Sony          | VPCEB23FM                   | [654cbddfc9](https://linux-hardware.org/?probe=654cbddfc9) | Feb 26, 2020 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [48c65f99c6](https://linux-hardware.org/?probe=48c65f99c6) | Feb 17, 2020 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [4e770d86e3](https://linux-hardware.org/?probe=4e770d86e3) | Feb 15, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [2b0d41a249](https://linux-hardware.org/?probe=2b0d41a249) | Jan 29, 2020 |
| Lenovo        | ThinkPad T490s 20NX002HU... | [622df7e336](https://linux-hardware.org/?probe=622df7e336) | Jan 24, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [ff60ab76a9](https://linux-hardware.org/?probe=ff60ab76a9) | Jan 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [21aeb33209](https://linux-hardware.org/?probe=21aeb33209) | Dec 18, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7b90aa9c1b](https://linux-hardware.org/?probe=7b90aa9c1b) | Nov 21, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [1858b15d73](https://linux-hardware.org/?probe=1858b15d73) | Nov 20, 2019 |
| Lenovo        | ThinkPad X270 20HN001EMC    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Dell          | Inspiron 5567               | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| HP            | 250 G4 Notebook PC          | [8dbaf2e95e](https://linux-hardware.org/?probe=8dbaf2e95e) | Nov 07, 2019 |
| HP            | 250 G4 Notebook PC          | [0347166558](https://linux-hardware.org/?probe=0347166558) | Nov 07, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f5adffebe4](https://linux-hardware.org/?probe=f5adffebe4) | Oct 30, 2019 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | [2204d80ff6](https://linux-hardware.org/?probe=2204d80ff6) | Oct 22, 2019 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [d1d0246ce6](https://linux-hardware.org/?probe=d1d0246ce6) | Aug 09, 2019 |
| Dell          | Latitude 7390               | [9b0861a491](https://linux-hardware.org/?probe=9b0861a491) | Jul 04, 2019 |
| Dell          | Latitude 7390               | [5090404699](https://linux-hardware.org/?probe=5090404699) | Jul 04, 2019 |
| Lenovo        | ThinkPad L480 20LSS0M100    | [b1b6812c4f](https://linux-hardware.org/?probe=b1b6812c4f) | May 19, 2019 |
| Lenovo        | ThinkPad X131e 3368CTO      | [c3f67b75e2](https://linux-hardware.org/?probe=c3f67b75e2) | Oct 31, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| RHEL 8  | 123       | 62.76%  |
| RHEL 9  | 62        | 31.63%  |
| RHEL 7  | 10        | 5.1%    |
| RHEL 10 | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| RHEL | 193       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64 | 10        | 4.37%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 10        | 4.37%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 8         | 3.49%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 8         | 3.49%   |
| 4.18.0-425.10.1.el8_7.x86_64 | 7         | 3.06%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 7         | 3.06%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 7         | 3.06%   |
| 5.14.0-284.30.1.el9_2.x86_64 | 6         | 2.62%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 4         | 1.75%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 4         | 1.75%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 4         | 1.75%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 4         | 1.75%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 4         | 1.75%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 1.75%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4         | 1.75%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 4         | 1.75%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 4         | 1.75%   |
| 4.18.0-193.el8.x86_64        | 4         | 1.75%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 4         | 1.75%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 3         | 1.31%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 3         | 1.31%   |
| 5.14.0-427.42.1.el9_4.x86_64 | 3         | 1.31%   |
| 5.14.0-427.22.1.el9_4.x86_64 | 3         | 1.31%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 3         | 1.31%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 3         | 1.31%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 3         | 1.31%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 3         | 1.31%   |
| 4.18.0-425.3.1.el8.x86_64    | 3         | 1.31%   |
| 4.18.0-372.9.1.el8.x86_64    | 3         | 1.31%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 1.31%   |
| 4.18.0-305.el8.x86_64        | 3         | 1.31%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 1.31%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 3         | 1.31%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 3         | 1.31%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3         | 1.31%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 2         | 0.87%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 0.87%   |
| 5.14.0-427.33.1.el9_4.x86_64 | 2         | 0.87%   |
| 5.14.0-427.20.1.el9_4.x86_64 | 2         | 0.87%   |
| 5.14.0-427.18.1.el9_4.x86_64 | 2         | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 122       | 62.24%  |
| 5.14.0  | 60        | 30.61%  |
| 3.10.0  | 10        | 5.1%    |
| 6.7.1   | 1         | 0.51%   |
| 6.5.2   | 1         | 0.51%   |
| 6.11.0  | 1         | 0.51%   |
| 5.9.1   | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 122       | 62.24%  |
| 5.14    | 60        | 30.61%  |
| 3.10    | 10        | 5.1%    |
| 6.7     | 1         | 0.51%   |
| 6.5     | 1         | 0.51%   |
| 6.11    | 1         | 0.51%   |
| 5.9     | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 193       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 170       | 84.58%  |
| Unknown         | 13        | 6.47%   |
| GNOME Classic   | 10        | 4.98%   |
| KDE5            | 4         | 1.99%   |
| XFCE            | 1         | 0.5%    |
| KDE4            | 1         | 0.5%    |
| GNOME Flashback | 1         | 0.5%    |
| Cinnamon        | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 97        | 49.24%  |
| Wayland | 95        | 48.22%  |
| Unknown | 5         | 2.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 147       | 73.5%   |
| GDM     | 52        | 26%     |
| SDDM    | 1         | 0.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 137       | 69.54%  |
| en_GB   | 11        | 5.58%   |
| Unknown | 10        | 5.08%   |
| pt_BR   | 5         | 2.54%   |
| fr_FR   | 5         | 2.54%   |
| en_IN   | 4         | 2.03%   |
| en_IE   | 3         | 1.52%   |
| de_DE   | 3         | 1.52%   |
| pl_PL   | 2         | 1.02%   |
| nl_NL   | 2         | 1.02%   |
| cs_CZ   | 2         | 1.02%   |
| ru_RU   | 1         | 0.51%   |
| ro_RO   | 1         | 0.51%   |
| nl_BE   | 1         | 0.51%   |
| ko_KR   | 1         | 0.51%   |
| ja_JP   | 1         | 0.51%   |
| it_IT   | 1         | 0.51%   |
| es_ES   | 1         | 0.51%   |
| es_EC   | 1         | 0.51%   |
| es_CO   | 1         | 0.51%   |
| en_DK   | 1         | 0.51%   |
| en_CA   | 1         | 0.51%   |
| de_CH   | 1         | 0.51%   |
| C       | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 164       | 83.25%  |
| BIOS | 33        | 16.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 169       | 86.67%  |
| Ext4    | 18        | 9.23%   |
| Unknown | 8         | 4.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 145       | 72.5%   |
| GPT     | 52        | 26%     |
| MBR     | 3         | 1.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 185       | 94.39%  |
| Yes       | 11        | 5.61%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 179       | 91.33%  |
| Yes       | 17        | 8.67%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 95        | 49.22%  |
| Dell                | 43        | 22.28%  |
| Hewlett-Packard     | 23        | 11.92%  |
| ASUSTek Computer    | 11        | 5.7%    |
| MSI                 | 5         | 2.59%   |
| Sony                | 2         | 1.04%   |
| Getac               | 2         | 1.04%   |
| Acer                | 2         | 1.04%   |
| UNOWHY              | 1         | 0.52%   |
| TUXEDO              | 1         | 0.52%   |
| Toshiba             | 1         | 0.52%   |
| Timi                | 1         | 0.52%   |
| System76            | 1         | 0.52%   |
| Samsung Electronics | 1         | 0.52%   |
| Razer               | 1         | 0.52%   |
| LG Electronics      | 1         | 0.52%   |
| Gigabyte Technology | 1         | 0.52%   |
| Unknown             | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X          | 4         | 2.07%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401     | 2         | 1.04%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00     | 2         | 1.04%   |
| Lenovo ThinkPad T590 20N5S2NC0N              | 2         | 1.04%   |
| Lenovo ThinkPad T490s 20NYS7K91R             | 2         | 1.04%   |
| Lenovo ThinkPad T480s 20L8S2N800             | 2         | 1.04%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08        | 2         | 1.04%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q          | 2         | 1.04%   |
| HP EliteBook 8460p                           | 2         | 1.04%   |
| HP EliteBook 2570p                           | 2         | 1.04%   |
| Dell Precision 7560                          | 2         | 1.04%   |
| Dell Precision 7510                          | 2         | 1.04%   |
| Dell Latitude E6430                          | 2         | 1.04%   |
| Dell Latitude 5300                           | 2         | 1.04%   |
| UNOWHY Y13G010S4EI                           | 1         | 0.52%   |
| TUXEDO N13xWU                                | 1         | 0.52%   |
| Toshiba Satellite Pro R50-C                  | 1         | 0.52%   |
| Timi TM1707                                  | 1         | 0.52%   |
| System76 Galago Pro                          | 1         | 0.52%   |
| Sony VPCEB4L1R                               | 1         | 0.52%   |
| Sony VPCEB23FM                               | 1         | 0.52%   |
| Samsung 730QCJ/730QCR                        | 1         | 0.52%   |
| Razer Blade 15 Mid 2019-Base                 | 1         | 0.52%   |
| MSI Modern 15 A5M                            | 1         | 0.52%   |
| MSI Katana GF76 12UC                         | 1         | 0.52%   |
| MSI Katana GF66 12UC                         | 1         | 0.52%   |
| MSI GP75 Leopard 9SD                         | 1         | 0.52%   |
| MSI GE72VR 7RF                               | 1         | 0.52%   |
| LG 15Z95P-GRLGL                              | 1         | 0.52%   |
| Lenovo Z40-70 20366                          | 1         | 0.52%   |
| Lenovo ThinkPad X270 20HN001EMC              | 1         | 0.52%   |
| Lenovo ThinkPad X250 20CLS0H807              | 1         | 0.52%   |
| Lenovo ThinkPad X230 Tablet 34373KU          | 1         | 0.52%   |
| Lenovo ThinkPad X201 3680PKS                 | 1         | 0.52%   |
| Lenovo ThinkPad X131e 3368CTO                | 1         | 0.52%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100       | 1         | 0.52%   |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US     | 1         | 0.52%   |
| Lenovo ThinkPad X1 Extreme Gen 5 21DFS08200  | 1         | 0.52%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5S08300 | 1         | 0.52%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS  | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 86        | 44.56%  |
| Dell Latitude      | 18        | 9.33%   |
| Dell Precision     | 15        | 7.77%   |
| HP EliteBook       | 9         | 4.66%   |
| Dell Inspiron      | 6         | 3.11%   |
| HP ZBook           | 5         | 2.59%   |
| Lenovo ThinkBook   | 3         | 1.55%   |
| Lenovo IdeaPad     | 3         | 1.55%   |
| ASUS VivoBook      | 3         | 1.55%   |
| MSI Katana         | 2         | 1.04%   |
| Lenovo Legion      | 2         | 1.04%   |
| HP ProBook         | 2         | 1.04%   |
| HP Laptop          | 2         | 1.04%   |
| Dell XPS           | 2         | 1.04%   |
| ASUS TUF           | 2         | 1.04%   |
| UNOWHY Y13G010S4EI | 1         | 0.52%   |
| TUXEDO N13xWU      | 1         | 0.52%   |
| Toshiba Satellite  | 1         | 0.52%   |
| Timi TM1707        | 1         | 0.52%   |
| System76 Galago    | 1         | 0.52%   |
| Sony VPCEB4L1R     | 1         | 0.52%   |
| Sony VPCEB23FM     | 1         | 0.52%   |
| Samsung 730QCJ     | 1         | 0.52%   |
| Razer Blade        | 1         | 0.52%   |
| MSI Modern         | 1         | 0.52%   |
| MSI GP75           | 1         | 0.52%   |
| MSI GE72VR         | 1         | 0.52%   |
| LG 15Z95P-GRLGL    | 1         | 0.52%   |
| Lenovo Z40-70      | 1         | 0.52%   |
| HP Stream          | 1         | 0.52%   |
| HP Pavilion        | 1         | 0.52%   |
| HP OMEN            | 1         | 0.52%   |
| HP 340S            | 1         | 0.52%   |
| HP 250             | 1         | 0.52%   |
| Gigabyte AERO      | 1         | 0.52%   |
| Getac S410G4       | 1         | 0.52%   |
| Getac B360         | 1         | 0.52%   |
| Dell G3            | 1         | 0.52%   |
| Dell G16           | 1         | 0.52%   |
| ASUS Zephyrus      | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 40        | 20.73%  |
| 2019 | 37        | 19.17%  |
| 2018 | 22        | 11.4%   |
| 2021 | 19        | 9.84%   |
| 2017 | 11        | 5.7%    |
| 2011 | 10        | 5.18%   |
| 2022 | 9         | 4.66%   |
| 2016 | 9         | 4.66%   |
| 2015 | 9         | 4.66%   |
| 2012 | 8         | 4.15%   |
| 2023 | 6         | 3.11%   |
| 2014 | 6         | 3.11%   |
| 2010 | 4         | 2.07%   |
| 2013 | 3         | 1.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 193       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 158       | 81.03%  |
| Enabled  | 37        | 18.97%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 192       | 99.48%  |
| Yes  | 1         | 0.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 58        | 29.44%  |
| 8.01-16.0   | 47        | 23.86%  |
| 4.01-8.0    | 36        | 18.27%  |
| 16.01-24.0  | 27        | 13.71%  |
| 64.01-256.0 | 14        | 7.11%   |
| 3.01-4.0    | 11        | 5.58%   |
| 24.01-32.0  | 4         | 2.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 89        | 41.78%  |
| 2.01-3.0   | 38        | 17.84%  |
| 3.01-4.0   | 33        | 15.49%  |
| 8.01-16.0  | 30        | 14.08%  |
| 1.01-2.0   | 16        | 7.51%   |
| 16.01-24.0 | 3         | 1.41%   |
| 24.01-32.0 | 2         | 0.94%   |
| 32.01-64.0 | 1         | 0.47%   |
| 0.51-1.0   | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 143       | 71.86%  |
| 2      | 40        | 20.1%   |
| 3      | 14        | 7.04%   |
| 4      | 2         | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 170       | 87.63%  |
| Yes       | 24        | 12.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 84.02%  |
| No        | 31        | 15.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 98.96%  |
| No        | 2         | 1.04%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 79.5%   |
| No        | 41        | 20.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 44        | 22.8%   |
| India        | 22        | 11.4%   |
| Germany      | 10        | 5.18%   |
| UK           | 9         | 4.66%   |
| Czechia      | 7         | 3.63%   |
| Brazil       | 7         | 3.63%   |
| Spain        | 6         | 3.11%   |
| France       | 6         | 3.11%   |
| Canada       | 6         | 3.11%   |
| Switzerland  | 4         | 2.07%   |
| Romania      | 4         | 2.07%   |
| Netherlands  | 4         | 2.07%   |
| Mexico       | 4         | 2.07%   |
| Italy        | 4         | 2.07%   |
| South Africa | 3         | 1.55%   |
| Chile        | 3         | 1.55%   |
| Turkey       | 2         | 1.04%   |
| South Korea  | 2         | 1.04%   |
| Singapore    | 2         | 1.04%   |
| Russia       | 2         | 1.04%   |
| Poland       | 2         | 1.04%   |
| Kenya        | 2         | 1.04%   |
| Japan        | 2         | 1.04%   |
| Ireland      | 2         | 1.04%   |
| Guatemala    | 2         | 1.04%   |
| Finland      | 2         | 1.04%   |
| Egypt        | 2         | 1.04%   |
| Colombia     | 2         | 1.04%   |
| Australia    | 2         | 1.04%   |
| Vietnam      | 1         | 0.52%   |
| Sri Lanka    | 1         | 0.52%   |
| Slovakia     | 1         | 0.52%   |
| Saudi Arabia | 1         | 0.52%   |
| Portugal     | 1         | 0.52%   |
| Pakistan     | 1         | 0.52%   |
| Norway       | 1         | 0.52%   |
| Nepal        | 1         | 0.52%   |
| Myanmar      | 1         | 0.52%   |
| Morocco      | 1         | 0.52%   |
| Luxembourg   | 1         | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Prague            | 4         | 1.95%   |
| Munich            | 3         | 1.46%   |
| Mexico City       | 3         | 1.46%   |
| Madrid            | 3         | 1.46%   |
| Chennai           | 3         | 1.46%   |
| Singapore         | 2         | 0.98%   |
| Santiago          | 2         | 0.98%   |
| Ottawa            | 2         | 0.98%   |
| Nairobi           | 2         | 0.98%   |
| Milan             | 2         | 0.98%   |
| Jaipur            | 2         | 0.98%   |
| Houston           | 2         | 0.98%   |
| Guatemala City    | 2         | 0.98%   |
| Berlin            | 2         | 0.98%   |
| Bengaluru         | 2         | 0.98%   |
| Barcelona         | 2         | 0.98%   |
| Zlín             | 1         | 0.49%   |
| Zaragoza          | 1         | 0.49%   |
| Whiteley          | 1         | 0.49%   |
| Webster           | 1         | 0.49%   |
| Wayne             | 1         | 0.49%   |
| Wagholi           | 1         | 0.49%   |
| Vardenis          | 1         | 0.49%   |
| Vancouver         | 1         | 0.49%   |
| Valbrembo         | 1         | 0.49%   |
| Urbandale         | 1         | 0.49%   |
| Udaipur           | 1         | 0.49%   |
| Turku             | 1         | 0.49%   |
| Temuco            | 1         | 0.49%   |
| Temara            | 1         | 0.49%   |
| Taringa           | 1         | 0.49%   |
| Talkha            | 1         | 0.49%   |
| Syracuse          | 1         | 0.49%   |
| Stuttgart         | 1         | 0.49%   |
| Streatham         | 1         | 0.49%   |
| Stratham          | 1         | 0.49%   |
| Stellenbosch      | 1         | 0.49%   |
| Steamboat Springs | 1         | 0.49%   |
| Spring Hill       | 1         | 0.49%   |
| Sofia             | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 60        | 88     | 23.35%  |
| Toshiba                     | 25        | 30     | 9.73%   |
| SanDisk                     | 22        | 28     | 8.56%   |
| WDC                         | 19        | 23     | 7.39%   |
| SK hynix                    | 17        | 18     | 6.61%   |
| Seagate                     | 17        | 24     | 6.61%   |
| Unknown                     | 15        | 17     | 5.84%   |
| Micron Technology           | 11        | 13     | 4.28%   |
| Kingston                    | 10        | 10     | 3.89%   |
| Intel                       | 9         | 13     | 3.5%    |
| KIOXIA                      | 7         | 9      | 2.72%   |
| HGST                        | 4         | 4      | 1.56%   |
| A-DATA Technology           | 4         | 4      | 1.56%   |
| Lenovo                      | 3         | 3      | 1.17%   |
| Crucial                     | 3         | 3      | 1.17%   |
| SSSTC                       | 2         | 2      | 0.78%   |
| Silicon Motion              | 2         | 3      | 0.78%   |
| PNY                         | 2         | 3      | 0.78%   |
| Micron/Crucial Technology   | 2         | 3      | 0.78%   |
| Kingston Technology Company | 2         | 2      | 0.78%   |
| Unknown                     | 2         | 2      | 0.78%   |
| WDC WDS                     | 1         | 1      | 0.39%   |
| Union Memory                | 1         | 1      | 0.39%   |
| UMIS                        | 1         | 1      | 0.39%   |
| Transcend                   | 1         | 1      | 0.39%   |
| Team                        | 1         | 2      | 0.39%   |
| SMI                         | 1         | 2      | 0.39%   |
| SABRENT                     | 1         | 1      | 0.39%   |
| Realtek                     | 1         | 1      | 0.39%   |
| Plextor                     | 1         | 1      | 0.39%   |
| Phison                      | 1         | 1      | 0.39%   |
| Lite-On                     | 1         | 1      | 0.39%   |
| KingSpec                    | 1         | 1      | 0.39%   |
| Kingmax                     | 1         | 1      | 0.39%   |
| Intenso                     | 1         | 1      | 0.39%   |
| Golden                      | 1         | 1      | 0.39%   |
| Gigabyte Technology         | 1         | 1      | 0.39%   |
| DERLAR                      | 1         | 1      | 0.39%   |
| Corsair                     | 1         | 1      | 0.39%   |
| China                       | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB                        | 10        | 3.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 7         | 2.55%   |
| SanDisk NVMe SSD Drive 256GB                         | 6         | 2.19%   |
| Samsung NVMe SSD Drive 512GB                         | 6         | 2.19%   |
| Samsung NVMe SSD Drive 256GB                         | 6         | 2.19%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 5         | 1.82%   |
| Samsung NVMe SSD Drive 1024GB                        | 5         | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 5         | 1.82%   |
| Toshiba NVMe SSD Drive 256GB                         | 4         | 1.46%   |
| Intel NVMe SSD Drive 512GB                           | 4         | 1.46%   |
| Unknown MMC Card  64GB                               | 3         | 1.09%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 3         | 1.09%   |
| Toshiba NVMe SSD Drive 512GB                         | 3         | 1.09%   |
| Toshiba MQ01ABF050 500GB                             | 3         | 1.09%   |
| Seagate ST1000LM049-2GH172 1TB                       | 3         | 1.09%   |
| Samsung SSD 860 EVO 1TB                              | 3         | 1.09%   |
| Samsung NVMe SSD Drive 2TB                           | 3         | 1.09%   |
| Samsung NVMe SSD Drive 1TB                           | 3         | 1.09%   |
| Micron NVMe SSD Drive 256GB                          | 3         | 1.09%   |
| HGST HTS721010A9E630 1TB                             | 3         | 1.09%   |
| Unknown NVMe SSD Drive 256GB                         | 2         | 0.73%   |
| Unknown MMC Card  256GB                              | 2         | 0.73%   |
| Unknown MMC Card  16GB                               | 2         | 0.73%   |
| Toshiba NVMe SSD Drive 1024GB                        | 2         | 0.73%   |
| Toshiba KXG6AZNV256G 256GB                           | 2         | 0.73%   |
| SK hynix NVMe SSD Drive 1024GB                       | 2         | 0.73%   |
| Seagate ST1000LM035-1RK172 1TB                       | 2         | 0.73%   |
| Seagate Expansion 1TB                                | 2         | 0.73%   |
| Seagate BUP Slim BK 2TB                              | 2         | 0.73%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB      | 2         | 0.73%   |
| SanDisk NVMe SSD Drive 512GB                         | 2         | 0.73%   |
| Samsung SSD PM830 2.5 7mm 128GB                      | 2         | 0.73%   |
| Samsung SSD 980 1TB                                  | 2         | 0.73%   |
| Samsung SSD 860 QVO 1TB                              | 2         | 0.73%   |
| Samsung Portable SSD T5 500GB                        | 2         | 0.73%   |
| Samsung NVMe SSD Drive 500GB                         | 2         | 0.73%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                       | 2         | 0.73%   |
| Micron 2400_MTFDKBA512QFM 512GB                      | 2         | 0.73%   |
| KIOXIA KBG5AZNT1T02 LA 1024GB                        | 2         | 0.73%   |
| Kingston SA400S37480G 480GB SSD                      | 2         | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 17        | 23     | 40.48%  |
| WDC     | 10        | 12     | 23.81%  |
| Toshiba | 10        | 12     | 23.81%  |
| HGST    | 4         | 4      | 9.52%   |
| SABRENT | 1         | 1      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 23     | 38.18%  |
| WDC                 | 5         | 6      | 9.09%   |
| Kingston            | 5         | 5      | 9.09%   |
| SanDisk             | 3         | 4      | 5.45%   |
| Crucial             | 3         | 3      | 5.45%   |
| PNY                 | 2         | 3      | 3.64%   |
| A-DATA Technology   | 2         | 2      | 3.64%   |
| WDC WDS             | 1         | 1      | 1.82%   |
| Transcend           | 1         | 1      | 1.82%   |
| Toshiba             | 1         | 1      | 1.82%   |
| Team                | 1         | 2      | 1.82%   |
| Seagate             | 1         | 1      | 1.82%   |
| Plextor             | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| KingSpec            | 1         | 1      | 1.82%   |
| Kingmax             | 1         | 1      | 1.82%   |
| Intenso             | 1         | 1      | 1.82%   |
| Intel               | 1         | 2      | 1.82%   |
| DERLAR              | 1         | 1      | 1.82%   |
| Corsair             | 1         | 1      | 1.82%   |
| China               | 1         | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 138       | 191    | 56.33%  |
| SSD     | 51        | 62     | 20.82%  |
| HDD     | 42        | 52     | 17.14%  |
| MMC     | 12        | 15     | 4.9%    |
| Unknown | 2         | 3      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 137       | 190    | 58.3%   |
| SATA | 72        | 99     | 30.64%  |
| SAS  | 14        | 19     | 5.96%   |
| MMC  | 12        | 15     | 5.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 53     | 48.39%  |
| 0.51-1.0   | 36        | 45     | 38.71%  |
| 1.01-2.0   | 8         | 8      | 8.6%    |
| 3.01-4.0   | 3         | 7      | 3.23%   |
| 4.01-10.0  | 1         | 1      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 77        | 38.31%  |
| 251-500        | 39        | 19.4%   |
| 501-1000       | 36        | 17.91%  |
| 1001-2000      | 17        | 8.46%   |
| 51-100         | 9         | 4.48%   |
| More than 3000 | 6         | 2.99%   |
| 21-50          | 6         | 2.99%   |
| 2001-3000      | 5         | 2.49%   |
| 1-20           | 3         | 1.49%   |
| Unknown        | 3         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 51        | 24.17%  |
| 21-50          | 50        | 23.7%   |
| 101-250        | 37        | 17.54%  |
| 51-100         | 33        | 15.64%  |
| 251-500        | 23        | 10.9%   |
| 501-1000       | 7         | 3.32%   |
| 1001-2000      | 5         | 2.37%   |
| Unknown        | 3         | 1.42%   |
| More than 3000 | 1         | 0.47%   |
| 2001-3000      | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Transcend TS512GMTS800 512GB SSD               | 1         | 1      | 16.67%  |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 16.67%  |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 16.67%  |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 1         | 1      | 16.67%  |
| Intel SSDSC2BA800G4R 800GB                     | 1         | 2      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 3         | 3      | 50%     |
| Transcend                 | 1         | 1      | 16.67%  |
| Micron/Crucial Technology | 1         | 1      | 16.67%  |
| Intel                     | 1         | 2      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 50%     |
| SSD  | 2         | 3      | 33.33%  |
| NVMe | 1         | 1      | 16.67%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 154       | 253    | 74.4%   |
| Works    | 47        | 63     | 22.71%  |
| Malfunc  | 6         | 7      | 2.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 96        | 40.34%  |
| Samsung Electronics            | 41        | 17.23%  |
| SanDisk                        | 23        | 9.66%   |
| SK hynix                       | 17        | 7.14%   |
| Toshiba America Info Systems   | 14        | 5.88%   |
| Micron Technology              | 10        | 4.2%    |
| KIOXIA                         | 9         | 3.78%   |
| Kingston Technology Company    | 6         | 2.52%   |
| AMD                            | 6         | 2.52%   |
| Lenovo                         | 3         | 1.26%   |
| ADATA Technology               | 3         | 1.26%   |
| Union Memory (Shenzhen)        | 2         | 0.84%   |
| Silicon Motion                 | 2         | 0.84%   |
| Phison Electronics             | 2         | 0.84%   |
| Micron/Crucial Technology      | 2         | 0.84%   |
| Solid State Storage Technology | 1         | 0.42%   |
| Lite-On Technology             | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 26        | 10.66%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 16        | 6.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 13        | 5.33%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 13        | 5.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 10        | 4.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 8         | 3.28%   |
| SK hynix PC611 NVMe Solid State Drive                                         | 7         | 2.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 7         | 2.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 2.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 6         | 2.46%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                    | 6         | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 6         | 2.46%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 5         | 2.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 5         | 2.05%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 5         | 2.05%   |
| SK hynix PC601 NVMe Solid State Drive                                         | 4         | 1.64%   |
| Micron 2300 NVMe SSD [Santana]                                                | 4         | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 4         | 1.64%   |
| Intel Volume Management Device NVMe RAID Controller                           | 4         | 1.64%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                              | 4         | 1.64%   |
| Intel SSD 660P Series                                                         | 4         | 1.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 4         | 1.64%   |
| Intel Comet Lake SATA AHCI Controller                                         | 4         | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 4         | 1.64%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                         | 3         | 1.23%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 3         | 1.23%   |
| Intel SATA Controller [RAID mode]                                             | 3         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 3         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 1.23%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 2         | 0.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 2         | 0.82%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)     | 2         | 0.82%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                   | 2         | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 0.82%   |
| Micron 3400 NVMe SSD [Hendrix]                                                | 2         | 0.82%   |
| Micron 2400 NVMe SSD (DRAM-less)                                              | 2         | 0.82%   |
| Lenovo LENSE20256GMSP34MEAT2TA                                                | 2         | 0.82%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                          | 2         | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 136       | 58.12%  |
| SATA | 83        | 35.47%  |
| RAID | 15        | 6.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 179       | 92.75%  |
| AMD    | 14        | 7.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 12        | 6.22%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 10        | 5.18%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 10        | 5.18%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 3.63%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 3.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 3.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 2.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.07%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 2.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.55%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 3         | 1.55%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 1.55%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 1.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.55%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 3         | 1.55%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.55%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.04%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.04%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.04%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.04%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.04%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 2         | 1.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.04%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.04%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.04%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.04%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.04%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz       | 2         | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.04%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.04%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.04%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.04%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.04%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 83        | 43.01%  |
| Intel Core i5   | 46        | 23.83%  |
| Other           | 27        | 13.99%  |
| Intel Core i3   | 8         | 4.15%   |
| AMD Ryzen 7     | 7         | 3.63%   |
| Intel Xeon      | 6         | 3.11%   |
| Intel Core i9   | 4         | 2.07%   |
| Intel Celeron   | 4         | 2.07%   |
| AMD Ryzen 7 PRO | 3         | 1.55%   |
| AMD Ryzen 5     | 2         | 1.04%   |
| Intel Pentium   | 1         | 0.52%   |
| AMD Ryzen 3     | 1         | 0.52%   |
| AMD A10         | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 88        | 45.6%   |
| 2      | 46        | 23.83%  |
| 6      | 29        | 15.03%  |
| 8      | 19        | 9.84%   |
| 10     | 5         | 2.59%   |
| 14     | 3         | 1.55%   |
| 12     | 2         | 1.04%   |
| 16     | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 193       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 183       | 94.33%  |
| 1      | 11        | 5.67%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 188       | 96.41%  |
| Unknown        | 7         | 3.59%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 36        | 18.37%  |
| Unknown    | 34        | 17.35%  |
| 0x806ea    | 15        | 7.65%   |
| 0xa0652    | 12        | 6.12%   |
| 0x906ea    | 8         | 4.08%   |
| 0x506e3    | 8         | 4.08%   |
| 0x406e3    | 8         | 4.08%   |
| 0x306a9    | 8         | 4.08%   |
| 0x206a7    | 7         | 3.57%   |
| 0x806d1    | 6         | 3.06%   |
| 0x806c1    | 6         | 3.06%   |
| 0x906ed    | 5         | 2.55%   |
| 0x906e9    | 4         | 2.04%   |
| 0x806e9    | 4         | 2.04%   |
| 0x306d4    | 4         | 2.04%   |
| 0x20655    | 4         | 2.04%   |
| 0x906a3    | 3         | 1.53%   |
| 0x40651    | 3         | 1.53%   |
| 0x08108102 | 3         | 1.53%   |
| 0x706e5    | 2         | 1.02%   |
| 0x0a50000c | 2         | 1.02%   |
| 0x08600103 | 2         | 1.02%   |
| 0x906a4    | 1         | 0.51%   |
| 0x90672    | 1         | 0.51%   |
| 0x706a8    | 1         | 0.51%   |
| 0x706a1    | 1         | 0.51%   |
| 0x306c3    | 1         | 0.51%   |
| 0x20652    | 1         | 0.51%   |
| 0x0a404102 | 1         | 0.51%   |
| 0x08608103 | 1         | 0.51%   |
| 0x08600106 | 1         | 0.51%   |
| 0x08600104 | 1         | 0.51%   |
| 0x08108109 | 1         | 0.51%   |
| 0x06003106 | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 82        | 42.27%  |
| Skylake          | 16        | 8.25%   |
| CometLake        | 14        | 7.22%   |
| Alderlake Hybrid | 12        | 6.19%   |
| TigerLake        | 9         | 4.64%   |
| Icelake          | 9         | 4.64%   |
| SandyBridge      | 8         | 4.12%   |
| IvyBridge        | 8         | 4.12%   |
| Westmere         | 6         | 3.09%   |
| Haswell          | 5         | 2.58%   |
| Broadwell        | 5         | 2.58%   |
| Unknown          | 5         | 2.58%   |
| Zen+             | 4         | 2.06%   |
| Zen 2            | 4         | 2.06%   |
| Goldmont plus    | 3         | 1.55%   |
| Zen 3            | 2         | 1.03%   |
| Tremont          | 1         | 0.52%   |
| Steamroller      | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 162       | 66.94%  |
| Nvidia | 55        | 22.73%  |
| AMD    | 25        | 10.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                                          | 19        | 7.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 18        | 7.44%   |
| Intel UHD Graphics 620                                                        | 18        | 7.44%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 13        | 5.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 11        | 4.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 9         | 3.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 8         | 3.31%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 8         | 3.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6         | 2.48%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 5         | 2.07%   |
| Intel HD Graphics 620                                                         | 5         | 2.07%   |
| Intel HD Graphics 5500                                                        | 5         | 2.07%   |
| Intel Core Processor Integrated Graphics Controller                           | 5         | 2.07%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 4         | 1.65%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 4         | 1.65%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 4         | 1.65%   |
| Intel HD Graphics 530                                                         | 4         | 1.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 1.65%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 4         | 1.65%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 4         | 1.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 1.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 1.24%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 3         | 1.24%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 3         | 1.24%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 3         | 1.24%   |
| Intel HD Graphics 630                                                         | 3         | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.24%   |
| Nvidia GP107GLM [Quadro P620]                                                 | 2         | 0.83%   |
| Nvidia GM107GLM [Quadro M2000M]                                               | 2         | 0.83%   |
| Nvidia GM107GLM [Quadro M1000M]                                               | 2         | 0.83%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 2         | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 0.83%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 2         | 0.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 0.83%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 0.83%   |
| AMD Lucienne                                                                  | 2         | 0.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 0.83%   |
| Nvidia TU117M [GeForce MX450]                                                 | 1         | 0.41%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.41%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                            | 1         | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 117       | 60.31%  |
| Intel + Nvidia | 37        | 19.07%  |
| 1 x Nvidia     | 15        | 7.73%   |
| 1 x AMD        | 13        | 6.7%    |
| Intel + AMD    | 8         | 4.12%   |
| AMD + Nvidia   | 4         | 2.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 170       | 86.73%  |
| Proprietary | 19        | 9.69%   |
| Unknown     | 7         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 137       | 70.26%  |
| 1.01-2.0   | 16        | 8.21%   |
| 3.01-4.0   | 15        | 7.69%   |
| 5.01-6.0   | 10        | 5.13%   |
| 0.51-1.0   | 7         | 3.59%   |
| 0.01-0.5   | 6         | 3.08%   |
| 7.01-8.0   | 1         | 0.51%   |
| 2.01-3.0   | 1         | 0.51%   |
| 16.01-24.0 | 1         | 0.51%   |
| 8.01-16.0  | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 16.79%  |
| BOE                     | 37        | 14.12%  |
| LG Display              | 31        | 11.83%  |
| Chimei Innolux          | 28        | 10.69%  |
| Samsung Electronics     | 21        | 8.02%   |
| Dell                    | 21        | 8.02%   |
| Lenovo                  | 15        | 5.73%   |
| Sharp                   | 8         | 3.05%   |
| Hewlett-Packard         | 8         | 3.05%   |
| Goldstar                | 7         | 2.67%   |
| InfoVision              | 6         | 2.29%   |
| CSO                     | 6         | 2.29%   |
| PANDA                   | 4         | 1.53%   |
| Acer                    | 4         | 1.53%   |
| Philips                 | 3         | 1.15%   |
| AOC                     | 3         | 1.15%   |
| Vizio                   | 2         | 0.76%   |
| LGD                     | 2         | 0.76%   |
| BOE Technology Group    | 2         | 0.76%   |
| Unknown (XXX)           | 1         | 0.38%   |
| Sun                     | 1         | 0.38%   |
| Sceptre Tech            | 1         | 0.38%   |
| Planar                  | 1         | 0.38%   |
| ITE                     | 1         | 0.38%   |
| Gigabyte Technology     | 1         | 0.38%   |
| Eizo                    | 1         | 0.38%   |
| Chi Mei Optoelectronics | 1         | 0.38%   |
| CEX                     | 1         | 0.38%   |
| ASUSTek Computer        | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 7         | 2.55%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 5         | 1.82%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 5         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 5         | 1.82%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 5         | 1.82%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                    | 4         | 1.45%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 4         | 1.45%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch         | 3         | 1.09%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 3         | 1.09%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch       | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 3         | 1.09%   |
| Vizio D48-D0 VIZ1004 1920x1080 1070x610mm 48.5-inch                  | 2         | 0.73%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 2         | 0.73%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch              | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 2         | 0.73%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2         | 0.73%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch              | 2         | 0.73%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.73%   |
| LGD LCD Monitor 1920x1080                                            | 2         | 0.73%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch          | 2         | 0.73%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch           | 2         | 0.73%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 2         | 0.73%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch           | 2         | 0.73%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch             | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch     | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO6A9F 2560x1600 344x215mm 16.0-inch       | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch       | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch        | 2         | 0.73%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch       | 1         | 0.36%   |
| Sun LCD Monitor SUN059A 1920x1080 518x324mm 24.1-inch                | 1         | 0.36%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch              | 1         | 0.36%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 1         | 0.36%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.36%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch              | 1         | 0.36%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch       | 1         | 0.36%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1         | 0.36%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 1         | 0.36%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch    | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 129       | 57.59%  |
| 1366x768 (WXGA)    | 31        | 13.84%  |
| 3840x2160 (4K)     | 14        | 6.25%   |
| 2560x1440 (QHD)    | 11        | 4.91%   |
| 1920x1200 (WUXGA)  | 10        | 4.46%   |
| 1600x900 (HD+)     | 7         | 3.13%   |
| 2560x1600          | 4         | 1.79%   |
| 2560x1080          | 3         | 1.34%   |
| 3440x1440          | 2         | 0.89%   |
| 1680x1050 (WSXGA+) | 2         | 0.89%   |
| Unknown            | 2         | 0.89%   |
| 6400x2160          | 1         | 0.45%   |
| 5120x1440          | 1         | 0.45%   |
| 3840x2400          | 1         | 0.45%   |
| 3840x1080          | 1         | 0.45%   |
| 2880x1800          | 1         | 0.45%   |
| 2160x1350          | 1         | 0.45%   |
| 2048x1152          | 1         | 0.45%   |
| 1440x900 (WXGA+)   | 1         | 0.45%   |
| 1280x800 (WXGA)    | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 70        | 26.72%  |
| 14      | 44        | 16.79%  |
| 13      | 41        | 15.65%  |
| 24      | 24        | 9.16%   |
| 27      | 18        | 6.87%   |
| 23      | 12        | 4.58%   |
| 17      | 7         | 2.67%   |
| 16      | 7         | 2.67%   |
| 21      | 6         | 2.29%   |
| 12      | 6         | 2.29%   |
| 34      | 5         | 1.91%   |
| Unknown | 5         | 1.91%   |
| 31      | 4         | 1.53%   |
| 54      | 3         | 1.15%   |
| 22      | 2         | 0.76%   |
| 18      | 2         | 0.76%   |
| 11      | 2         | 0.76%   |
| 72      | 1         | 0.38%   |
| 49      | 1         | 0.38%   |
| 32      | 1         | 0.38%   |
| 19      | 1         | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 149       | 57.98%  |
| 501-600     | 46        | 17.9%   |
| 201-300     | 21        | 8.17%   |
| 401-500     | 11        | 4.28%   |
| 601-700     | 7         | 2.72%   |
| 351-400     | 7         | 2.72%   |
| 701-800     | 6         | 2.33%   |
| Unknown     | 5         | 1.95%   |
| 1001-1500   | 4         | 1.56%   |
| 1501-2000   | 1         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 169       | 82.44%  |
| 16/10   | 24        | 11.71%  |
| 21/9    | 5         | 2.44%   |
| Unknown | 5         | 2.44%   |
| 32/9    | 1         | 0.49%   |
| 3/2     | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 72        | 27.69%  |
| 101-110        | 69        | 26.54%  |
| 201-250        | 34        | 13.08%  |
| 301-350        | 18        | 6.92%   |
| 71-80          | 13        | 5%      |
| 351-500        | 9         | 3.46%   |
| 251-300        | 8         | 3.08%   |
| 111-120        | 8         | 3.08%   |
| 121-130        | 7         | 2.69%   |
| 61-70          | 6         | 2.31%   |
| Unknown        | 5         | 1.92%   |
| More than 1000 | 4         | 1.54%   |
| 51-60          | 2         | 0.77%   |
| 151-200        | 2         | 0.77%   |
| 141-150        | 2         | 0.77%   |
| 501-1000       | 1         | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 124       | 49.4%   |
| 51-100        | 49        | 19.52%  |
| 101-120       | 41        | 16.33%  |
| 161-240       | 18        | 7.17%   |
| More than 240 | 11        | 4.38%   |
| Unknown       | 5         | 1.99%   |
| 1-50          | 3         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 124       | 61.39%  |
| 2     | 55        | 27.23%  |
| 3     | 13        | 6.44%   |
| 0     | 8         | 3.96%   |
| 5     | 1         | 0.5%    |
| 4     | 1         | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 162       | 54.55%  |
| Realtek Semiconductor             | 66        | 22.22%  |
| Lenovo                            | 18        | 6.06%   |
| Qualcomm Atheros                  | 14        | 4.71%   |
| MediaTek                          | 4         | 1.35%   |
| DisplayLink                       | 3         | 1.01%   |
| Broadcom Limited                  | 3         | 1.01%   |
| Broadcom                          | 3         | 1.01%   |
| Sierra Wireless                   | 2         | 0.67%   |
| OPPO Electronics                  | 2         | 0.67%   |
| Marvell Technology Group          | 2         | 0.67%   |
| Ericsson Business Mobile Networks | 2         | 0.67%   |
| Dell                              | 2         | 0.67%   |
| ASIX Electronics                  | 2         | 0.67%   |
| Xiaomi                            | 1         | 0.34%   |
| TP-Link                           | 1         | 0.34%   |
| Samsung Electronics               | 1         | 0.34%   |
| Ralink Technology                 | 1         | 0.34%   |
| Ralink                            | 1         | 0.34%   |
| Qualcomm Atheros Communications   | 1         | 0.34%   |
| Qualcomm                          | 1         | 0.34%   |
| Luminary Micro                    | 1         | 0.34%   |
| ICS Advent                        | 1         | 0.34%   |
| Huawei Technologies               | 1         | 0.34%   |
| Google                            | 1         | 0.34%   |
| Aquantia                          | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 31        | 7.73%   |
| Intel Wireless 8265 / 8275                                             | 22        | 5.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 18        | 4.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 18        | 4.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 16        | 3.99%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 14        | 3.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 3.24%   |
| Intel Ethernet Connection (6) I219-LM                                  | 12        | 2.99%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 2.99%   |
| Intel Wireless 8260                                                    | 10        | 2.49%   |
| Intel Ethernet Connection (10) I219-LM                                 | 10        | 2.49%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 9         | 2.24%   |
| Intel Wi-Fi 6 AX201                                                    | 9         | 2.24%   |
| Intel Wi-Fi 6 AX200                                                    | 9         | 2.24%   |
| Intel Ethernet Connection (7) I219-LM                                  | 9         | 2.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 9         | 2.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 2%      |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 7         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.5%    |
| Intel Wireless 7265                                                    | 5         | 1.25%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 1.25%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 1%      |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 1%      |
| Intel Raptor Lake PCH CNVi WiFi                                        | 4         | 1%      |
| Intel Ethernet Connection (6) I219-V                                   | 4         | 1%      |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 1%      |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 1%      |
| Intel Ethernet Connection (13) I219-LM                                 | 4         | 1%      |
| Intel Ethernet Connection (10) I219-V                                  | 4         | 1%      |
| Intel Centrino Ultimate-N 6300                                         | 4         | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 0.75%   |
| Lenovo Lenovo USB-C to LAN                                             | 3         | 0.75%   |
| Intel Wireless 3165                                                    | 3         | 0.75%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.5%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 0.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 155       | 77.89%  |
| Realtek Semiconductor           | 14        | 7.04%   |
| Qualcomm Atheros                | 12        | 6.03%   |
| MediaTek                        | 4         | 2.01%   |
| Broadcom                        | 3         | 1.51%   |
| Sierra Wireless                 | 2         | 1.01%   |
| Dell                            | 2         | 1.01%   |
| Broadcom Limited                | 2         | 1.01%   |
| TP-Link                         | 1         | 0.5%    |
| Ralink Technology               | 1         | 0.5%    |
| Ralink                          | 1         | 0.5%    |
| Qualcomm Atheros Communications | 1         | 0.5%    |
| Qualcomm                        | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                    | 22        | 11.06%  |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 18        | 9.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 16        | 8.04%   |
| Intel Comet Lake PCH CNVi WiFi                                | 14        | 7.04%   |
| Intel Wireless 8260                                           | 10        | 5.03%   |
| Intel Wi-Fi 6 AX201                                           | 9         | 4.52%   |
| Intel Wi-Fi 6 AX200                                           | 9         | 4.52%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 9         | 4.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 6         | 3.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 6         | 3.02%   |
| Intel Wireless 7265                                           | 5         | 2.51%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 5         | 2.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 2.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 4         | 2.01%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 4         | 2.01%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 4         | 2.01%   |
| Intel Centrino Ultimate-N 6300                                | 4         | 2.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 3         | 1.51%   |
| Intel Wireless 3165                                           | 3         | 1.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 2         | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 2         | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 1.01%   |
| Intel Wireless 7260                                           | 2         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 2         | 1.01%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 2         | 1.01%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                          | 2         | 1.01%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1         | 0.5%    |
| Sierra Wireless EM7565 QualcommÂ Snapdragonâ¢ X16 LTE-A  | 1         | 0.5%    |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem               | 1         | 0.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 0.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1         | 0.5%    |
| Ralink MT7601U Wireless Adapter                               | 1         | 0.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 1         | 0.5%    |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 1         | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                               | 1         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 101       | 51.79%  |
| Realtek Semiconductor    | 59        | 30.26%  |
| Lenovo                   | 18        | 9.23%   |
| DisplayLink              | 3         | 1.54%   |
| Qualcomm Atheros         | 2         | 1.03%   |
| OPPO Electronics         | 2         | 1.03%   |
| Marvell Technology Group | 2         | 1.03%   |
| ASIX Electronics         | 2         | 1.03%   |
| Xiaomi                   | 1         | 0.51%   |
| ICS Advent               | 1         | 0.51%   |
| Huawei Technologies      | 1         | 0.51%   |
| Google                   | 1         | 0.51%   |
| Broadcom Limited         | 1         | 0.51%   |
| Aquantia                 | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 31        | 15.66%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 18        | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 13        | 6.57%   |
| Intel Ethernet Connection (6) I219-LM                                          | 12        | 6.06%   |
| Intel Ethernet Connection (4) I219-LM                                          | 12        | 6.06%   |
| Intel Ethernet Connection (10) I219-LM                                         | 10        | 5.05%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 9         | 4.55%   |
| Intel Ethernet Connection (7) I219-LM                                          | 9         | 4.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 4.04%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 2.53%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 2.02%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 2.02%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 2.02%   |
| Intel Ethernet Connection (13) I219-LM                                         | 4         | 2.02%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 2.02%   |
| Lenovo Lenovo USB-C to LAN                                                     | 3         | 1.52%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.01%   |
| OPPO OnePlus Nord 4                                                            | 2         | 1.01%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.01%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1.01%   |
| Lenovo ThinkPad Lan                                                            | 2         | 1.01%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.01%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 1.01%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 1.01%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.51%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.51%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.51%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.51%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.51%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.51%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.51%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.51%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.51%   |
| Intel Ethernet Connection (23) I219-LM                                         | 1         | 0.51%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 191       | 53.2%   |
| Ethernet | 164       | 45.68%  |
| Modem    | 4         | 1.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 144       | 68.57%  |
| Ethernet | 65        | 30.95%  |
| Modem    | 1         | 0.48%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 146       | 75.65%  |
| 1     | 47        | 24.35%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 163       | 84.02%  |
| Yes  | 31        | 15.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 122       | 76.25%  |
| Broadcom                        | 9         | 5.63%   |
| Realtek Semiconductor           | 7         | 4.38%   |
| Qualcomm Atheros Communications | 7         | 4.38%   |
| IMC Networks                    | 4         | 2.5%    |
| Foxconn / Hon Hai               | 3         | 1.88%   |
| Cambridge Silicon Radio         | 2         | 1.25%   |
| USI                             | 1         | 0.63%   |
| Ralink                          | 1         | 0.63%   |
| MediaTek                        | 1         | 0.63%   |
| Lite-On Technology              | 1         | 0.63%   |
| Dell                            | 1         | 0.63%   |
| ASUSTek Computer                | 1         | 0.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 44        | 27.5%   |
| Intel Bluetooth wireless interface                                                  | 31        | 19.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 22        | 13.75%  |
| Intel AX200 Bluetooth                                                               | 9         | 5.63%   |
| Intel AX211 Bluetooth                                                               | 8         | 5%      |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 3.75%   |
| Realtek Bluetooth Radio                                                             | 4         | 2.5%    |
| Intel AX210 Bluetooth                                                               | 4         | 2.5%    |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.5%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.25%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.25%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.25%   |
| USI Bluetooth Device                                                                | 1         | 0.63%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.63%   |
| MediaTek Wireless_Device                                                            | 1         | 0.63%   |
| Lite-On Wireless_Device                                                             | 1         | 0.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.63%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.63%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.63%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.63%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.63%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.63%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.63%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.63%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.63%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 179       | 61.51%  |
| Nvidia                   | 35        | 12.03%  |
| AMD                      | 19        | 6.53%   |
| Lenovo                   | 15        | 5.15%   |
| Realtek Semiconductor    | 8         | 2.75%   |
| GN Netcom                | 6         | 2.06%   |
| Texas Instruments        | 4         | 1.37%   |
| Plantronics              | 4         | 1.37%   |
| JMTek                    | 2         | 0.69%   |
| Hewlett-Packard          | 2         | 0.69%   |
| Generalplus Technology   | 2         | 0.69%   |
| Corsair                  | 2         | 0.69%   |
| C-Media Electronics      | 2         | 0.69%   |
| SteelSeries ApS          | 1         | 0.34%   |
| Sony                     | 1         | 0.34%   |
| Nordic Semiconductor ASA | 1         | 0.34%   |
| Logitech                 | 1         | 0.34%   |
| LG Electronics           | 1         | 0.34%   |
| Google                   | 1         | 0.34%   |
| Focusrite-Novation       | 1         | 0.34%   |
| DSEA A/S                 | 1         | 0.34%   |
| Dell                     | 1         | 0.34%   |
| Blue Microphones         | 1         | 0.34%   |
| BEHRINGER International  | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 31        | 9.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 19        | 6.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 6.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 17        | 5.45%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 4.49%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 13        | 4.17%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 9         | 2.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 2.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 2.88%   |
| Realtek Semiconductor USB Audio                                            | 8         | 2.56%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 2.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 2.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 2.24%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 2.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.6%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.6%    |
| Intel CM238 HD Audio Controller                                            | 5         | 1.6%    |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.6%    |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.28%   |
| Nvidia GA107 High Definition Audio Controller                              | 4         | 1.28%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.28%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 4         | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.28%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.28%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 0.96%   |
| Plantronics BT600                                                          | 3         | 0.96%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.64%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.64%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.64%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 2         | 0.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.64%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 0.64%   |
| Hewlett-Packard USB Audio                                                  | 2         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 36%     |
| SK hynix            | 21        | 28%     |
| Kingston            | 7         | 9.33%   |
| Crucial             | 5         | 6.67%   |
| Micron Technology   | 4         | 5.33%   |
| Unknown             | 2         | 2.67%   |
| Smart               | 2         | 2.67%   |
| Elpida              | 2         | 2.67%   |
| Unknown (0x0B5E)    | 1         | 1.33%   |
| Transcend           | 1         | 1.33%   |
| Team                | 1         | 1.33%   |
| Innodisk            | 1         | 1.33%   |
| GOODRAM             | 1         | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 3         | 3.85%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 3         | 3.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 2.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 2.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 2         | 2.56%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 2         | 2.56%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 2.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 2.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 2.56%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s           | 2         | 2.56%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 1.28%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.28%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 1.28%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 1.28%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.28%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.28%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.28%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.28%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.28%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s         | 1         | 1.28%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.28%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 1.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.28%   |
| SK hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.28%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.28%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.28%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 1.28%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.28%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s          | 1         | 1.28%   |
| SK hynix RAM H5AN8G6NDJR-XNC 4GB Row Of Chips DDR4 2400MT/s     | 1         | 1.28%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.28%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 1.28%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                    | 1         | 1.28%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.28%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.28%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 40        | 66.67%  |
| DDR3   | 15        | 25%     |
| LPDDR5 | 2         | 3.33%   |
| LPDDR4 | 1         | 1.67%   |
| LPDDR3 | 1         | 1.67%   |
| DDR5   | 1         | 1.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 93.22%  |
| Row Of Chips | 4         | 6.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 22        | 33.85%  |
| 8192  | 20        | 30.77%  |
| 4096  | 15        | 23.08%  |
| 32768 | 7         | 10.77%  |
| 2048  | 1         | 1.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 19        | 29.23%  |
| 2667  | 15        | 23.08%  |
| 1600  | 12        | 18.46%  |
| 2400  | 6         | 9.23%   |
| 2133  | 5         | 7.69%   |
| 1333  | 3         | 4.62%   |
| 6400  | 2         | 3.08%   |
| 4800  | 1         | 1.54%   |
| 2933  | 1         | 1.54%   |
| 1334  | 1         | 1.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3210 Series | 1         | 50%     |
| HP ENVY 4500 series      | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 56        | 28%     |
| IMC Networks                           | 28        | 14%     |
| Bison Electronics                      | 19        | 9.5%    |
| Microdia                               | 16        | 8%      |
| Sunplus Innovation Technology          | 15        | 7.5%    |
| Realtek Semiconductor                  | 15        | 7.5%    |
| Logitech                               | 7         | 3.5%    |
| Lite-On Technology                     | 6         | 3%      |
| Luxvisions Innotech Limited            | 5         | 2.5%    |
| Suyin                                  | 4         | 2%      |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2%      |
| Acer                                   | 4         | 2%      |
| Samsung Electronics                    | 3         | 1.5%    |
| Quanta                                 | 3         | 1.5%    |
| Syntek                                 | 2         | 1%      |
| Microsoft                              | 2         | 1%      |
| Sonix Technology                       | 1         | 0.5%    |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.5%    |
| Ruision                                | 1         | 0.5%    |
| Remo Tech                              | 1         | 0.5%    |
| LG Electronics                         | 1         | 0.5%    |
| Lenovo                                 | 1         | 0.5%    |
| KYE Systems (Mouse Systems)            | 1         | 0.5%    |
| icSpring                               | 1         | 0.5%    |
| Hopewin Electronic Material            | 1         | 0.5%    |
| Creative Technology                    | 1         | 0.5%    |
| Alcor Micro                            | 1         | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 26        | 12.94%  |
| IMC Networks Integrated Camera                    | 22        | 10.95%  |
| Realtek Integrated_Webcam_HD                      | 10        | 4.98%   |
| Sunplus Integrated_Webcam_HD                      | 8         | 3.98%   |
| Bison Integrated Camera                           | 8         | 3.98%   |
| Microdia Integrated_Webcam_HD                     | 6         | 2.99%   |
| Chicony HP HD Camera                              | 6         | 2.99%   |
| Lite-On Integrated Camera                         | 5         | 2.49%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 5         | 2.49%   |
| Chicony Integrated Camera (1280x720@30)           | 5         | 2.49%   |
| Bison SunplusIT Integrated Camera                 | 5         | 2.49%   |
| Logitech HD Pro Webcam C920                       | 4         | 1.99%   |
| Chicony ThinkPad T490 Webcam                      | 4         | 1.99%   |
| Samsung Galaxy series, misc. (MTP mode)           | 3         | 1.49%   |
| Microdia Integrated Webcam                        | 3         | 1.49%   |
| Suyin Integrated_Webcam_HD                        | 2         | 1%      |
| Sunplus Laptop_Integrated_Webcam_FHD              | 2         | 1%      |
| Sunplus DICOTA 4K                                 | 2         | 1%      |
| Microdia Webcam                                   | 2         | 1%      |
| Luxvisions Innotech Limited Integrated RGB Camera | 2         | 1%      |
| Chicony Integrated Camera [ThinkPad]              | 2         | 1%      |
| Chicony HP HD Webcam [Fixed]                      | 2         | 1%      |
| Bison HD Webcam                                   | 2         | 1%      |
| Acer Integrated IR Camera                         | 2         | 1%      |
| Syntek Lenovo EasyCamera                          | 1         | 0.5%    |
| Syntek Integrated Camera                          | 1         | 0.5%    |
| Suyin RGBIR Camera                                | 1         | 0.5%    |
| Suyin HP Truevision HD                            | 1         | 0.5%    |
| Sunplus Integrated Webcam                         | 1         | 0.5%    |
| Sunplus Integrated Camera                         | 1         | 0.5%    |
| Sunplus HP HD Webcam [Fixed]                      | 1         | 0.5%    |
| Sonix USB2.0 HD UVC WebCam                        | 1         | 0.5%    |
| Shenzhen Kingcome Optoelectronic 720p HD Camera   | 1         | 0.5%    |
| Ruision UVC Camera                                | 1         | 0.5%    |
| Remo Tech OBSBOT Tiny 4K                          | 1         | 0.5%    |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 0.5%    |
| Realtek USB Camera                                | 1         | 0.5%    |
| Realtek NexiGo N660P FHD Webcam                   | 1         | 0.5%    |
| Realtek Integrated Webcam_HD                      | 1         | 0.5%    |
| Realtek HP Webcam                                 | 1         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 46        | 64.79%  |
| Validity Sensors           | 17        | 23.94%  |
| Shenzhen Goodix Technology | 4         | 5.63%   |
| Upek                       | 2         | 2.82%   |
| Samsung Electronics        | 1         | 1.41%   |
| Elan Microelectronics      | 1         | 1.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 38.03%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 9.86%   |
| Synaptics UWP WBDI Device                                                  | 4         | 5.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 4.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 4.23%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 4.23%   |
| Validity Sensors VFS491                                                    | 2         | 2.82%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.82%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.82%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.82%   |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 2.82%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.41%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.41%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.41%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.41%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.41%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.41%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 21        | 70%     |
| Alcor Micro | 6         | 20%     |
| Lenovo      | 2         | 6.67%   |
| Upek        | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 8         | 26.67%  |
| Broadcom 58200                                                               | 8         | 26.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 13.33%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 89        | 45.41%  |
| 0     | 81        | 41.33%  |
| 2     | 18        | 9.18%   |
| 3     | 5         | 2.55%   |
| 5     | 2         | 1.02%   |
| 4     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 71        | 47.02%  |
| Graphics card            | 21        | 13.91%  |
| Chipcard                 | 19        | 12.58%  |
| Net/wireless             | 11        | 7.28%   |
| Multimedia controller    | 8         | 5.3%    |
| Card reader              | 6         | 3.97%   |
| Net/ethernet             | 4         | 2.65%   |
| Bluetooth                | 3         | 1.99%   |
| Storage                  | 2         | 1.32%   |
| Communication controller | 2         | 1.32%   |
| Camera                   | 2         | 1.32%   |
| Sound                    | 1         | 0.66%   |
| Firewire controller      | 1         | 0.66%   |

