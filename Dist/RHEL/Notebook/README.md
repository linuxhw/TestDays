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

Total: 273

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| RHEL 8 | 121       | 68.75%  |
| RHEL 9 | 45        | 25.57%  |
| RHEL 7 | 10        | 5.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| RHEL | 173       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64 | 10        | 4.85%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 10        | 4.85%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 8         | 3.88%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 8         | 3.88%   |
| 4.18.0-425.10.1.el8_7.x86_64 | 7         | 3.4%    |
| 4.18.0-348.20.1.el8_5.x86_64 | 7         | 3.4%    |
| 4.18.0-305.3.1.el8_4.x86_64  | 7         | 3.4%    |
| 5.14.0-284.30.1.el9_2.x86_64 | 6         | 2.91%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 4         | 1.94%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 4         | 1.94%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 4         | 1.94%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 4         | 1.94%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 4         | 1.94%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 1.94%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4         | 1.94%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 4         | 1.94%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 4         | 1.94%   |
| 4.18.0-193.el8.x86_64        | 4         | 1.94%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 4         | 1.94%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 3         | 1.46%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 3         | 1.46%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 3         | 1.46%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 3         | 1.46%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 3         | 1.46%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 3         | 1.46%   |
| 4.18.0-425.3.1.el8.x86_64    | 3         | 1.46%   |
| 4.18.0-372.9.1.el8.x86_64    | 3         | 1.46%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 1.46%   |
| 4.18.0-305.el8.x86_64        | 3         | 1.46%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 1.46%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 3         | 1.46%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 3         | 1.46%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3         | 1.46%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 2         | 0.97%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 0.97%   |
| 5.14.0-362.18.1.el9_3.x86_64 | 2         | 0.97%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 0.97%   |
| 4.18.0-477.27.1.el8_8.x86_64 | 2         | 0.97%   |
| 4.18.0-477.21.1.el8_8.x86_64 | 2         | 0.97%   |
| 4.18.0-348.el8.x86_64        | 2         | 0.97%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 120       | 68.18%  |
| 5.14.0  | 43        | 24.43%  |
| 3.10.0  | 10        | 5.68%   |
| 6.7.1   | 1         | 0.57%   |
| 6.5.2   | 1         | 0.57%   |
| 5.9.1   | 1         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 120       | 68.18%  |
| 5.14    | 43        | 24.43%  |
| 3.10    | 10        | 5.68%   |
| 6.7     | 1         | 0.57%   |
| 6.5     | 1         | 0.57%   |
| 5.9     | 1         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 173       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 151       | 83.89%  |
| Unknown         | 13        | 7.22%   |
| GNOME Classic   | 9         | 5%      |
| KDE5            | 3         | 1.67%   |
| XFCE            | 1         | 0.56%   |
| KDE4            | 1         | 0.56%   |
| GNOME Flashback | 1         | 0.56%   |
| Cinnamon        | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 91        | 51.41%  |
| Wayland | 81        | 45.76%  |
| Unknown | 5         | 2.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 133       | 73.89%  |
| GDM     | 46        | 25.56%  |
| SDDM    | 1         | 0.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 121       | 68.36%  |
| en_GB   | 11        | 6.21%   |
| Unknown | 10        | 5.65%   |
| pt_BR   | 4         | 2.26%   |
| fr_FR   | 4         | 2.26%   |
| en_IN   | 4         | 2.26%   |
| de_DE   | 3         | 1.69%   |
| pl_PL   | 2         | 1.13%   |
| nl_NL   | 2         | 1.13%   |
| en_IE   | 2         | 1.13%   |
| cs_CZ   | 2         | 1.13%   |
| ru_RU   | 1         | 0.56%   |
| ro_RO   | 1         | 0.56%   |
| nl_BE   | 1         | 0.56%   |
| ko_KR   | 1         | 0.56%   |
| ja_JP   | 1         | 0.56%   |
| it_IT   | 1         | 0.56%   |
| es_ES   | 1         | 0.56%   |
| es_EC   | 1         | 0.56%   |
| es_CO   | 1         | 0.56%   |
| en_DK   | 1         | 0.56%   |
| de_CH   | 1         | 0.56%   |
| C       | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 147       | 83.05%  |
| BIOS | 30        | 16.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 150       | 85.71%  |
| Ext4    | 17        | 9.71%   |
| Unknown | 8         | 4.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 131       | 72.78%  |
| GPT     | 46        | 25.56%  |
| MBR     | 3         | 1.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 165       | 93.75%  |
| Yes       | 11        | 6.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 161       | 91.48%  |
| Yes       | 15        | 8.52%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 87        | 50.29%  |
| Dell                | 38        | 21.97%  |
| Hewlett-Packard     | 20        | 11.56%  |
| ASUSTek Computer    | 10        | 5.78%   |
| MSI                 | 5         | 2.89%   |
| Sony                | 2         | 1.16%   |
| Getac               | 2         | 1.16%   |
| TUXEDO              | 1         | 0.58%   |
| Toshiba             | 1         | 0.58%   |
| Timi                | 1         | 0.58%   |
| System76            | 1         | 0.58%   |
| Samsung Electronics | 1         | 0.58%   |
| Razer               | 1         | 0.58%   |
| LG Electronics      | 1         | 0.58%   |
| Gigabyte Technology | 1         | 0.58%   |
| Acer                | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X         | 4         | 2.31%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401    | 2         | 1.16%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00    | 2         | 1.16%   |
| Lenovo ThinkPad T590 20N5S2NC0N             | 2         | 1.16%   |
| Lenovo ThinkPad T490s 20NYS7K91R            | 2         | 1.16%   |
| Lenovo ThinkPad T480s 20L8S2N800            | 2         | 1.16%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08       | 2         | 1.16%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q         | 2         | 1.16%   |
| HP EliteBook 8460p                          | 2         | 1.16%   |
| HP EliteBook 2570p                          | 2         | 1.16%   |
| Dell Precision 7560                         | 2         | 1.16%   |
| Dell Precision 7510                         | 2         | 1.16%   |
| Dell Latitude E6430                         | 2         | 1.16%   |
| Dell Latitude 5300                          | 2         | 1.16%   |
| TUXEDO N13xWU                               | 1         | 0.58%   |
| Toshiba Satellite Pro R50-C                 | 1         | 0.58%   |
| Timi TM1707                                 | 1         | 0.58%   |
| System76 Galago Pro                         | 1         | 0.58%   |
| Sony VPCEB4L1R                              | 1         | 0.58%   |
| Sony VPCEB23FM                              | 1         | 0.58%   |
| Samsung 730QCJ/730QCR                       | 1         | 0.58%   |
| Razer Blade 15 Mid 2019-Base                | 1         | 0.58%   |
| MSI Modern 15 A5M                           | 1         | 0.58%   |
| MSI Katana GF76 12UC                        | 1         | 0.58%   |
| MSI Katana GF66 12UC                        | 1         | 0.58%   |
| MSI GP75 Leopard 9SD                        | 1         | 0.58%   |
| MSI GE72VR 7RF                              | 1         | 0.58%   |
| LG 15Z95P-GRLGL                             | 1         | 0.58%   |
| Lenovo Z40-70 20366                         | 1         | 0.58%   |
| Lenovo ThinkPad X270 20HN001EMC             | 1         | 0.58%   |
| Lenovo ThinkPad X250 20CLS0H807             | 1         | 0.58%   |
| Lenovo ThinkPad X230 Tablet 34373KU         | 1         | 0.58%   |
| Lenovo ThinkPad X201 3680PKS                | 1         | 0.58%   |
| Lenovo ThinkPad X131e 3368CTO               | 1         | 0.58%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100      | 1         | 0.58%   |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US    | 1         | 0.58%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XXS3HC1G  | 1         | 0.58%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMS1V900 | 1         | 0.58%   |
| Lenovo ThinkPad W530 2441B32                | 1         | 0.58%   |
| Lenovo ThinkPad W520 4284GN2                | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 81        | 46.82%  |
| Dell Precision    | 14        | 8.09%   |
| Dell Latitude     | 14        | 8.09%   |
| HP EliteBook      | 7         | 4.05%   |
| Dell Inspiron     | 6         | 3.47%   |
| HP ZBook          | 5         | 2.89%   |
| ASUS VivoBook     | 3         | 1.73%   |
| MSI Katana        | 2         | 1.16%   |
| Lenovo ThinkBook  | 2         | 1.16%   |
| Lenovo IdeaPad    | 2         | 1.16%   |
| HP ProBook        | 2         | 1.16%   |
| HP Laptop         | 2         | 1.16%   |
| Dell XPS          | 2         | 1.16%   |
| ASUS TUF          | 2         | 1.16%   |
| TUXEDO N13xWU     | 1         | 0.58%   |
| Toshiba Satellite | 1         | 0.58%   |
| Timi TM1707       | 1         | 0.58%   |
| System76 Galago   | 1         | 0.58%   |
| Sony VPCEB4L1R    | 1         | 0.58%   |
| Sony VPCEB23FM    | 1         | 0.58%   |
| Samsung 730QCJ    | 1         | 0.58%   |
| Razer Blade       | 1         | 0.58%   |
| MSI Modern        | 1         | 0.58%   |
| MSI GP75          | 1         | 0.58%   |
| MSI GE72VR        | 1         | 0.58%   |
| LG 15Z95P-GRLGL   | 1         | 0.58%   |
| Lenovo Z40-70     | 1         | 0.58%   |
| Lenovo Legion     | 1         | 0.58%   |
| HP Pavilion       | 1         | 0.58%   |
| HP OMEN           | 1         | 0.58%   |
| HP 340S           | 1         | 0.58%   |
| HP 250            | 1         | 0.58%   |
| Gigabyte AERO     | 1         | 0.58%   |
| Getac S410G4      | 1         | 0.58%   |
| Getac B360        | 1         | 0.58%   |
| Dell G3           | 1         | 0.58%   |
| Dell G16          | 1         | 0.58%   |
| ASUS Zephyrus     | 1         | 0.58%   |
| ASUS Z450LA       | 1         | 0.58%   |
| ASUS X550ZA       | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 36        | 20.81%  |
| 2019 | 34        | 19.65%  |
| 2018 | 20        | 11.56%  |
| 2021 | 16        | 9.25%   |
| 2017 | 11        | 6.36%   |
| 2016 | 9         | 5.2%    |
| 2015 | 9         | 5.2%    |
| 2012 | 8         | 4.62%   |
| 2011 | 8         | 4.62%   |
| 2022 | 6         | 3.47%   |
| 2014 | 5         | 2.89%   |
| 2023 | 4         | 2.31%   |
| 2010 | 4         | 2.31%   |
| 2013 | 3         | 1.73%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 173       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 142       | 81.14%  |
| Enabled  | 33        | 18.86%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 172       | 99.42%  |
| Yes  | 1         | 0.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 54        | 30.51%  |
| 8.01-16.0   | 43        | 24.29%  |
| 4.01-8.0    | 34        | 19.21%  |
| 16.01-24.0  | 25        | 14.12%  |
| 64.01-256.0 | 11        | 6.21%   |
| 3.01-4.0    | 8         | 4.52%   |
| 24.01-32.0  | 2         | 1.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 78        | 40.84%  |
| 3.01-4.0   | 32        | 16.75%  |
| 2.01-3.0   | 32        | 16.75%  |
| 8.01-16.0  | 27        | 14.14%  |
| 1.01-2.0   | 15        | 7.85%   |
| 16.01-24.0 | 3         | 1.57%   |
| 24.01-32.0 | 2         | 1.05%   |
| 32.01-64.0 | 1         | 0.52%   |
| 0.51-1.0   | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 132       | 73.74%  |
| 2      | 32        | 17.88%  |
| 3      | 13        | 7.26%   |
| 4      | 2         | 1.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 151       | 86.78%  |
| Yes       | 23        | 13.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 85.06%  |
| No        | 26        | 14.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 172       | 99.42%  |
| No        | 1         | 0.58%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 78.33%  |
| No        | 39        | 21.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 39        | 22.54%  |
| India        | 21        | 12.14%  |
| UK           | 9         | 5.2%    |
| Germany      | 9         | 5.2%    |
| Czechia      | 7         | 4.05%   |
| France       | 5         | 2.89%   |
| Brazil       | 5         | 2.89%   |
| Switzerland  | 4         | 2.31%   |
| Spain        | 4         | 2.31%   |
| Netherlands  | 4         | 2.31%   |
| Italy        | 4         | 2.31%   |
| South Africa | 3         | 1.73%   |
| Romania      | 3         | 1.73%   |
| Mexico       | 3         | 1.73%   |
| Chile        | 3         | 1.73%   |
| Canada       | 3         | 1.73%   |
| Turkey       | 2         | 1.16%   |
| Singapore    | 2         | 1.16%   |
| Russia       | 2         | 1.16%   |
| Poland       | 2         | 1.16%   |
| Kenya        | 2         | 1.16%   |
| Japan        | 2         | 1.16%   |
| Guatemala    | 2         | 1.16%   |
| Finland      | 2         | 1.16%   |
| Egypt        | 2         | 1.16%   |
| Colombia     | 2         | 1.16%   |
| Australia    | 2         | 1.16%   |
| Vietnam      | 1         | 0.58%   |
| Sri Lanka    | 1         | 0.58%   |
| South Korea  | 1         | 0.58%   |
| Slovakia     | 1         | 0.58%   |
| Saudi Arabia | 1         | 0.58%   |
| Portugal     | 1         | 0.58%   |
| Pakistan     | 1         | 0.58%   |
| Norway       | 1         | 0.58%   |
| Nepal        | 1         | 0.58%   |
| Myanmar      | 1         | 0.58%   |
| Morocco      | 1         | 0.58%   |
| Luxembourg   | 1         | 0.58%   |
| Lithuania    | 1         | 0.58%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Prague            | 4         | 2.17%   |
| Munich            | 3         | 1.63%   |
| Mexico City       | 3         | 1.63%   |
| Chennai           | 3         | 1.63%   |
| Singapore         | 2         | 1.09%   |
| Santiago          | 2         | 1.09%   |
| Nairobi           | 2         | 1.09%   |
| Milan             | 2         | 1.09%   |
| Madrid            | 2         | 1.09%   |
| Houston           | 2         | 1.09%   |
| Guatemala City    | 2         | 1.09%   |
| Berlin            | 2         | 1.09%   |
| Bengaluru         | 2         | 1.09%   |
| Zlín             | 1         | 0.54%   |
| Zaragoza          | 1         | 0.54%   |
| Whiteley          | 1         | 0.54%   |
| Webster           | 1         | 0.54%   |
| Wayne             | 1         | 0.54%   |
| Wagholi           | 1         | 0.54%   |
| Vardenis          | 1         | 0.54%   |
| Valbrembo         | 1         | 0.54%   |
| Udaipur           | 1         | 0.54%   |
| Turku             | 1         | 0.54%   |
| Temuco            | 1         | 0.54%   |
| Temara            | 1         | 0.54%   |
| Taringa           | 1         | 0.54%   |
| Talkha            | 1         | 0.54%   |
| Syracuse          | 1         | 0.54%   |
| Stuttgart         | 1         | 0.54%   |
| Streatham         | 1         | 0.54%   |
| Stratham          | 1         | 0.54%   |
| Stellenbosch      | 1         | 0.54%   |
| Steamboat Springs | 1         | 0.54%   |
| Sofia             | 1         | 0.54%   |
| Skien             | 1         | 0.54%   |
| Šilalė          | 1         | 0.54%   |
| Sheffield         | 1         | 0.54%   |
| Seoul             | 1         | 0.54%   |
| Sao Paulo         | 1         | 0.54%   |
| San Jose          | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 54        | 81     | 23.89%  |
| Toshiba                     | 22        | 26     | 9.73%   |
| WDC                         | 19        | 23     | 8.41%   |
| SanDisk                     | 18        | 23     | 7.96%   |
| SK hynix                    | 16        | 17     | 7.08%   |
| Seagate                     | 16        | 23     | 7.08%   |
| Unknown                     | 11        | 13     | 4.87%   |
| Micron Technology           | 11        | 13     | 4.87%   |
| Intel                       | 9         | 13     | 3.98%   |
| Kingston                    | 8         | 8      | 3.54%   |
| KIOXIA                      | 5         | 6      | 2.21%   |
| HGST                        | 4         | 4      | 1.77%   |
| Lenovo                      | 3         | 3      | 1.33%   |
| Crucial                     | 3         | 3      | 1.33%   |
| A-DATA Technology           | 3         | 3      | 1.33%   |
| SSSTC                       | 2         | 2      | 0.88%   |
| Silicon Motion              | 2         | 3      | 0.88%   |
| Micron/Crucial Technology   | 2         | 3      | 0.88%   |
| Kingston Technology Company | 2         | 2      | 0.88%   |
| UMIS                        | 1         | 1      | 0.44%   |
| Transcend                   | 1         | 1      | 0.44%   |
| Team                        | 1         | 2      | 0.44%   |
| SMI                         | 1         | 2      | 0.44%   |
| SABRENT                     | 1         | 1      | 0.44%   |
| PNY                         | 1         | 2      | 0.44%   |
| Plextor                     | 1         | 1      | 0.44%   |
| Phison                      | 1         | 1      | 0.44%   |
| Lite-On                     | 1         | 1      | 0.44%   |
| KingSpec                    | 1         | 1      | 0.44%   |
| Kingmax                     | 1         | 1      | 0.44%   |
| Intenso                     | 1         | 1      | 0.44%   |
| Golden                      | 1         | 1      | 0.44%   |
| Gigabyte Technology         | 1         | 1      | 0.44%   |
| Corsair                     | 1         | 1      | 0.44%   |
| China                       | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB                      | 10        | 4.13%   |
| SanDisk NVMe SSD Drive 256GB                       | 6         | 2.48%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 6         | 2.48%   |
| Samsung NVMe SSD Drive 512GB                       | 6         | 2.48%   |
| Samsung NVMe SSD Drive 1024GB                      | 5         | 2.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 5         | 2.07%   |
| Toshiba NVMe SSD Drive 256GB                       | 4         | 1.65%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 4         | 1.65%   |
| Intel NVMe SSD Drive 512GB                         | 4         | 1.65%   |
| Toshiba NVMe SSD Drive 512GB                       | 3         | 1.24%   |
| Samsung SSD 860 EVO 1TB                            | 3         | 1.24%   |
| Samsung NVMe SSD Drive 2TB                         | 3         | 1.24%   |
| Samsung NVMe SSD Drive 1TB                         | 3         | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 1.24%   |
| Micron NVMe SSD Drive 256GB                        | 3         | 1.24%   |
| HGST HTS721010A9E630 1TB                           | 3         | 1.24%   |
| Unknown NVMe SSD Drive 256GB                       | 2         | 0.83%   |
| Unknown MMC Card  256GB                            | 2         | 0.83%   |
| Unknown MMC Card  16GB                             | 2         | 0.83%   |
| Toshiba XG6 NVMe SSD Controller 1024GB             | 2         | 0.83%   |
| Toshiba NVMe SSD Drive 1024GB                      | 2         | 0.83%   |
| Toshiba MQ01ABF050 500GB                           | 2         | 0.83%   |
| Toshiba KXG6AZNV256G 256GB                         | 2         | 0.83%   |
| SK hynix NVMe SSD Drive 1024GB                     | 2         | 0.83%   |
| Seagate ST1000LM049-2GH172 1TB                     | 2         | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 0.83%   |
| Seagate Expansion 2TB                              | 2         | 0.83%   |
| Seagate BUP Slim BK 2TB                            | 2         | 0.83%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB    | 2         | 0.83%   |
| SanDisk NVMe SSD Drive 512GB                       | 2         | 0.83%   |
| Samsung SSD PM830 2.5 7mm 128GB                    | 2         | 0.83%   |
| Samsung SSD 980 1TB                                | 2         | 0.83%   |
| Samsung SSD 860 QVO 1TB                            | 2         | 0.83%   |
| Samsung Portable SSD T5 500GB                      | 2         | 0.83%   |
| Samsung NVMe SSD Drive 500GB                       | 2         | 0.83%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                     | 2         | 0.83%   |
| Micron 2400_MTFDKBA512QFM 512GB                    | 2         | 0.83%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                         | 2         | 0.83%   |
| Kingston SA400S37480G 480GB SSD                    | 2         | 0.83%   |
| Intel NVMe SSD Drive 2TB                           | 2         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 22     | 41.03%  |
| WDC     | 10        | 12     | 25.64%  |
| Toshiba | 8         | 10     | 20.51%  |
| HGST    | 4         | 4      | 10.26%  |
| SABRENT | 1         | 1      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 22     | 40%     |
| WDC                 | 5         | 6      | 10%     |
| Kingston            | 4         | 4      | 8%      |
| SanDisk             | 3         | 4      | 6%      |
| Crucial             | 3         | 3      | 6%      |
| A-DATA Technology   | 2         | 2      | 4%      |
| Transcend           | 1         | 1      | 2%      |
| Toshiba             | 1         | 1      | 2%      |
| Team                | 1         | 2      | 2%      |
| Seagate             | 1         | 1      | 2%      |
| PNY                 | 1         | 2      | 2%      |
| Plextor             | 1         | 1      | 2%      |
| Micron Technology   | 1         | 1      | 2%      |
| KingSpec            | 1         | 1      | 2%      |
| Kingmax             | 1         | 1      | 2%      |
| Intenso             | 1         | 1      | 2%      |
| Intel               | 1         | 2      | 2%      |
| Corsair             | 1         | 1      | 2%      |
| China               | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 122       | 170    | 55.96%  |
| SSD     | 47        | 57     | 21.56%  |
| HDD     | 39        | 49     | 17.89%  |
| MMC     | 8         | 9      | 3.67%   |
| Unknown | 2         | 3      | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 122       | 170    | 58.65%  |
| SATA | 67        | 93     | 32.21%  |
| SAS  | 11        | 16     | 5.29%   |
| MMC  | 8         | 9      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 48     | 47.56%  |
| 0.51-1.0   | 33        | 42     | 40.24%  |
| 1.01-2.0   | 7         | 9      | 8.54%   |
| 3.01-4.0   | 2         | 2      | 2.44%   |
| 4.01-10.0  | 1         | 5      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 72        | 39.78%  |
| 251-500        | 35        | 19.34%  |
| 501-1000       | 30        | 16.57%  |
| 1001-2000      | 15        | 8.29%   |
| 51-100         | 8         | 4.42%   |
| More than 3000 | 6         | 3.31%   |
| 21-50          | 5         | 2.76%   |
| 2001-3000      | 4         | 2.21%   |
| 1-20           | 3         | 1.66%   |
| Unknown        | 3         | 1.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 45        | 23.81%  |
| 21-50          | 44        | 23.28%  |
| 101-250        | 33        | 17.46%  |
| 51-100         | 31        | 16.4%   |
| 251-500        | 20        | 10.58%  |
| 501-1000       | 7         | 3.7%    |
| 1001-2000      | 4         | 2.12%   |
| Unknown        | 3         | 1.59%   |
| More than 3000 | 1         | 0.53%   |
| 2001-3000      | 1         | 0.53%   |

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
| Detected | 139       | 225    | 74.33%  |
| Works    | 42        | 56     | 22.46%  |
| Malfunc  | 6         | 7      | 3.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 90        | 41.86%  |
| Samsung Electronics            | 36        | 16.74%  |
| SanDisk                        | 19        | 8.84%   |
| SK hynix                       | 16        | 7.44%   |
| Toshiba America Info Systems   | 13        | 6.05%   |
| Micron Technology              | 10        | 4.65%   |
| KIOXIA                         | 7         | 3.26%   |
| Kingston Technology Company    | 5         | 2.33%   |
| AMD                            | 5         | 2.33%   |
| Lenovo                         | 3         | 1.4%    |
| Silicon Motion                 | 2         | 0.93%   |
| Phison Electronics             | 2         | 0.93%   |
| Micron/Crucial Technology      | 2         | 0.93%   |
| ADATA Technology               | 2         | 0.93%   |
| Union Memory (Shenzhen)        | 1         | 0.47%   |
| Solid State Storage Technology | 1         | 0.47%   |
| Lite-On Technology             | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 24        | 10.96%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 16        | 7.31%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 12        | 5.48%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 12        | 5.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 9         | 4.11%   |
| SK hynix PC611 NVMe Solid State Drive                                         | 7         | 3.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 7         | 3.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 3.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 6         | 2.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 5         | 2.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 5         | 2.28%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 5         | 2.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 5         | 2.28%   |
| SK hynix PC601 NVMe Solid State Drive                                         | 4         | 1.83%   |
| Micron 2300 NVMe SSD [Santana]                                                | 4         | 1.83%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                    | 4         | 1.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 4         | 1.83%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                              | 4         | 1.83%   |
| Intel SSD 660P Series                                                         | 4         | 1.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 4         | 1.83%   |
| Intel Comet Lake SATA AHCI Controller                                         | 4         | 1.83%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 4         | 1.83%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                         | 3         | 1.37%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 3         | 1.37%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 1.37%   |
| Intel SATA Controller [RAID mode]                                             | 3         | 1.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 3         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 3         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 1.37%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 2         | 0.91%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                   | 2         | 0.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 0.91%   |
| Micron 3400 NVMe SSD [Hendrix]                                                | 2         | 0.91%   |
| Micron 2400 NVMe SSD (DRAM-less)                                              | 2         | 0.91%   |
| Lenovo LENSE20256GMSP34MEAT2TA                                                | 2         | 0.91%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.91%   |
| Intel Alder Lake-P SATA AHCI Controller                                       | 2         | 0.91%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                 | 1         | 0.46%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.46%   |
| Solid State Storage CA5-8D256 NVMe SSD M.2                                    | 1         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 121       | 57.35%  |
| SATA | 77        | 36.49%  |
| RAID | 13        | 6.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 162       | 93.64%  |
| AMD    | 11        | 6.36%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 11        | 6.36%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 10        | 5.78%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 10        | 5.78%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 3.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 3.47%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.31%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 2.31%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.73%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 3         | 1.73%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 1.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.73%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 3         | 1.73%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.16%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.16%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.16%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.16%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.16%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.16%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.16%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 2         | 1.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.16%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.16%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.16%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.16%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz       | 2         | 1.16%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.16%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.16%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.16%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.16%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.58%   |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 0.58%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.58%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 81        | 46.82%  |
| Intel Core i5   | 40        | 23.12%  |
| Other           | 21        | 12.14%  |
| Intel Core i3   | 8         | 4.62%   |
| Intel Xeon      | 6         | 3.47%   |
| AMD Ryzen 7     | 6         | 3.47%   |
| Intel Core i9   | 4         | 2.31%   |
| AMD Ryzen 7 PRO | 2         | 1.16%   |
| AMD Ryzen 5     | 2         | 1.16%   |
| Intel Pentium   | 1         | 0.58%   |
| Intel Celeron   | 1         | 0.58%   |
| AMD A10         | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 79        | 45.66%  |
| 2      | 43        | 24.86%  |
| 6      | 27        | 15.61%  |
| 8      | 16        | 9.25%   |
| 10     | 4         | 2.31%   |
| 14     | 2         | 1.16%   |
| 16     | 1         | 0.58%   |
| 12     | 1         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 173       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 166       | 95.4%   |
| 1      | 8         | 4.6%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 168       | 96%     |
| Unknown        | 7         | 4%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 36        | 20.57%  |
| Unknown    | 16        | 9.14%   |
| 0x806ea    | 15        | 8.57%   |
| 0xa0652    | 12        | 6.86%   |
| 0x906ea    | 8         | 4.57%   |
| 0x506e3    | 8         | 4.57%   |
| 0x406e3    | 8         | 4.57%   |
| 0x306a9    | 8         | 4.57%   |
| 0x206a7    | 7         | 4%      |
| 0x806d1    | 6         | 3.43%   |
| 0x806c1    | 6         | 3.43%   |
| 0x906ed    | 5         | 2.86%   |
| 0x906e9    | 4         | 2.29%   |
| 0x806e9    | 4         | 2.29%   |
| 0x306d4    | 4         | 2.29%   |
| 0x20655    | 4         | 2.29%   |
| 0x906a3    | 3         | 1.71%   |
| 0x40651    | 3         | 1.71%   |
| 0x706e5    | 2         | 1.14%   |
| 0x0a50000c | 2         | 1.14%   |
| 0x08600103 | 2         | 1.14%   |
| 0x08108102 | 2         | 1.14%   |
| 0x906a4    | 1         | 0.57%   |
| 0x90672    | 1         | 0.57%   |
| 0x706a8    | 1         | 0.57%   |
| 0x306c3    | 1         | 0.57%   |
| 0x20652    | 1         | 0.57%   |
| 0x08608103 | 1         | 0.57%   |
| 0x08600106 | 1         | 0.57%   |
| 0x08600104 | 1         | 0.57%   |
| 0x08108109 | 1         | 0.57%   |
| 0x06003106 | 1         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 77        | 44.25%  |
| Skylake          | 16        | 9.2%    |
| CometLake        | 13        | 7.47%   |
| Alderlake Hybrid | 9         | 5.17%   |
| IvyBridge        | 8         | 4.6%    |
| Icelake          | 8         | 4.6%    |
| TigerLake        | 7         | 4.02%   |
| SandyBridge      | 7         | 4.02%   |
| Westmere         | 6         | 3.45%   |
| Broadwell        | 5         | 2.87%   |
| Zen 2            | 4         | 2.3%    |
| Haswell          | 4         | 2.3%    |
| Zen+             | 3         | 1.72%   |
| Unknown          | 3         | 1.72%   |
| Zen 3            | 2         | 1.15%   |
| Steamroller      | 1         | 0.57%   |
| Goldmont plus    | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 147       | 67.12%  |
| Nvidia | 50        | 22.83%  |
| AMD    | 22        | 10.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 18        | 8.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 18        | 8.22%   |
| Intel UHD Graphics 620                                                        | 16        | 7.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 12        | 5.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 11        | 5.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 8         | 3.65%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 8         | 3.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 7         | 3.2%    |
| Intel HD Graphics 620                                                         | 5         | 2.28%   |
| Intel HD Graphics 5500                                                        | 5         | 2.28%   |
| Intel Core Processor Integrated Graphics Controller                           | 5         | 2.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 2.28%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 4         | 1.83%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 4         | 1.83%   |
| Intel HD Graphics 530                                                         | 4         | 1.83%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 4         | 1.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 3         | 1.37%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 3         | 1.37%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 3         | 1.37%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 3         | 1.37%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 3         | 1.37%   |
| Intel HD Graphics 630                                                         | 3         | 1.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 1.37%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 3         | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.91%   |
| Nvidia GP107GLM [Quadro P620]                                                 | 2         | 0.91%   |
| Nvidia GM107GLM [Quadro M2000M]                                               | 2         | 0.91%   |
| Nvidia GM107GLM [Quadro M1000M]                                               | 2         | 0.91%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 2         | 0.91%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 0.91%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 0.91%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 0.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 0.91%   |
| Nvidia TU117M [GeForce MX450]                                                 | 1         | 0.46%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                            | 1         | 0.46%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.46%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 1         | 0.46%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                              | 1         | 0.46%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                              | 1         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 105       | 60.34%  |
| Intel + Nvidia | 34        | 19.54%  |
| 1 x Nvidia     | 13        | 7.47%   |
| 1 x AMD        | 10        | 5.75%   |
| Intel + AMD    | 8         | 4.6%    |
| AMD + Nvidia   | 4         | 2.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 153       | 86.93%  |
| Proprietary | 16        | 9.09%   |
| Unknown     | 7         | 3.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 121       | 69.14%  |
| 1.01-2.0   | 15        | 8.57%   |
| 3.01-4.0   | 14        | 8%      |
| 5.01-6.0   | 9         | 5.14%   |
| 0.51-1.0   | 6         | 3.43%   |
| 0.01-0.5   | 6         | 3.43%   |
| 7.01-8.0   | 1         | 0.57%   |
| 2.01-3.0   | 1         | 0.57%   |
| 16.01-24.0 | 1         | 0.57%   |
| 8.01-16.0  | 1         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 39        | 16.53%  |
| BOE                     | 31        | 13.14%  |
| LG Display              | 29        | 12.29%  |
| Chimei Innolux          | 27        | 11.44%  |
| Samsung Electronics     | 20        | 8.47%   |
| Dell                    | 20        | 8.47%   |
| Lenovo                  | 14        | 5.93%   |
| Sharp                   | 8         | 3.39%   |
| Hewlett-Packard         | 8         | 3.39%   |
| Goldstar                | 7         | 2.97%   |
| InfoVision              | 6         | 2.54%   |
| PANDA                   | 3         | 1.27%   |
| AOC                     | 3         | 1.27%   |
| Acer                    | 3         | 1.27%   |
| Philips                 | 2         | 0.85%   |
| LGD                     | 2         | 0.85%   |
| CSO                     | 2         | 0.85%   |
| BOE Technology Group    | 2         | 0.85%   |
| Vizio                   | 1         | 0.42%   |
| Sun                     | 1         | 0.42%   |
| Sceptre Tech            | 1         | 0.42%   |
| Planar                  | 1         | 0.42%   |
| ITE                     | 1         | 0.42%   |
| Gigabyte Technology     | 1         | 0.42%   |
| Eizo                    | 1         | 0.42%   |
| Chi Mei Optoelectronics | 1         | 0.42%   |
| CEX                     | 1         | 0.42%   |
| ASUSTek Computer        | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 7         | 2.83%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 5         | 2.02%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 5         | 2.02%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 5         | 2.02%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 5         | 2.02%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 4         | 1.62%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch         | 3         | 1.21%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 3         | 1.21%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                    | 3         | 1.21%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                | 3         | 1.21%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch       | 3         | 1.21%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 2         | 0.81%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch              | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 2         | 0.81%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2         | 0.81%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch              | 2         | 0.81%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.81%   |
| LGD LCD Monitor 1920x1080                                            | 2         | 0.81%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch          | 2         | 0.81%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch           | 2         | 0.81%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 2         | 0.81%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch           | 2         | 0.81%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch     | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch       | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch        | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.81%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                | 1         | 0.4%    |
| Sun LCD Monitor SUN059A 1920x1080 518x324mm 24.1-inch                | 1         | 0.4%    |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch              | 1         | 0.4%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 1         | 0.4%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.4%    |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch              | 1         | 0.4%    |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch       | 1         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 1         | 0.4%    |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch    | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch | 1         | 0.4%    |
| Samsung Electronics SMBX2431 SAM0771 1920x1080 531x299mm 24.0-inch   | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 117       | 57.92%  |
| 1366x768 (WXGA)    | 28        | 13.86%  |
| 3840x2160 (4K)     | 13        | 6.44%   |
| 2560x1440 (QHD)    | 10        | 4.95%   |
| 1920x1200 (WUXGA)  | 8         | 3.96%   |
| 1600x900 (HD+)     | 7         | 3.47%   |
| 2560x1080          | 3         | 1.49%   |
| 3440x1440          | 2         | 0.99%   |
| 2560x1600          | 2         | 0.99%   |
| 1680x1050 (WSXGA+) | 2         | 0.99%   |
| Unknown            | 2         | 0.99%   |
| 6400x2160          | 1         | 0.5%    |
| 5120x1440          | 1         | 0.5%    |
| 3840x1080          | 1         | 0.5%    |
| 2880x1800          | 1         | 0.5%    |
| 2160x1350          | 1         | 0.5%    |
| 2048x1152          | 1         | 0.5%    |
| 1440x900 (WXGA+)   | 1         | 0.5%    |
| 1280x800 (WXGA)    | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 62        | 26.38%  |
| 14      | 44        | 18.72%  |
| 13      | 35        | 14.89%  |
| 24      | 20        | 8.51%   |
| 27      | 17        | 7.23%   |
| 23      | 11        | 4.68%   |
| 17      | 7         | 2.98%   |
| 21      | 6         | 2.55%   |
| 12      | 6         | 2.55%   |
| 34      | 5         | 2.13%   |
| Unknown | 5         | 2.13%   |
| 31      | 4         | 1.7%    |
| 16      | 3         | 1.28%   |
| 22      | 2         | 0.85%   |
| 18      | 2         | 0.85%   |
| 72      | 1         | 0.43%   |
| 54      | 1         | 0.43%   |
| 49      | 1         | 0.43%   |
| 32      | 1         | 0.43%   |
| 19      | 1         | 0.43%   |
| 11      | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 134       | 58.01%  |
| 501-600     | 41        | 17.75%  |
| 201-300     | 17        | 7.36%   |
| 401-500     | 11        | 4.76%   |
| 601-700     | 7         | 3.03%   |
| 351-400     | 7         | 3.03%   |
| 701-800     | 6         | 2.6%    |
| Unknown     | 5         | 2.16%   |
| 1001-1500   | 2         | 0.87%   |
| 1501-2000   | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 153       | 83.15%  |
| 16/10   | 19        | 10.33%  |
| 21/9    | 5         | 2.72%   |
| Unknown | 5         | 2.72%   |
| 32/9    | 1         | 0.54%   |
| 3/2     | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 69        | 29.49%  |
| 101-110        | 61        | 26.07%  |
| 201-250        | 30        | 12.82%  |
| 301-350        | 17        | 7.26%   |
| 71-80          | 10        | 4.27%   |
| 351-500        | 9         | 3.85%   |
| 251-300        | 8         | 3.42%   |
| 121-130        | 7         | 2.99%   |
| 61-70          | 6         | 2.56%   |
| Unknown        | 5         | 2.14%   |
| 111-120        | 4         | 1.71%   |
| More than 1000 | 2         | 0.85%   |
| 151-200        | 2         | 0.85%   |
| 141-150        | 2         | 0.85%   |
| 51-60          | 1         | 0.43%   |
| 501-1000       | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 112       | 49.78%  |
| 51-100        | 45        | 20%     |
| 101-120       | 38        | 16.89%  |
| 161-240       | 15        | 6.67%   |
| More than 240 | 9         | 4%      |
| Unknown       | 5         | 2.22%   |
| 1-50          | 1         | 0.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 111       | 60.99%  |
| 2     | 52        | 28.57%  |
| 3     | 10        | 5.49%   |
| 0     | 7         | 3.85%   |
| 5     | 1         | 0.55%   |
| 4     | 1         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 148       | 55.43%  |
| Realtek Semiconductor             | 57        | 21.35%  |
| Lenovo                            | 18        | 6.74%   |
| Qualcomm Atheros                  | 12        | 4.49%   |
| MediaTek                          | 3         | 1.12%   |
| Broadcom Limited                  | 3         | 1.12%   |
| Sierra Wireless                   | 2         | 0.75%   |
| Marvell Technology Group          | 2         | 0.75%   |
| Ericsson Business Mobile Networks | 2         | 0.75%   |
| DisplayLink                       | 2         | 0.75%   |
| Dell                              | 2         | 0.75%   |
| Broadcom                          | 2         | 0.75%   |
| ASIX Electronics                  | 2         | 0.75%   |
| Xiaomi                            | 1         | 0.37%   |
| TP-Link                           | 1         | 0.37%   |
| Samsung Electronics               | 1         | 0.37%   |
| Ralink Technology                 | 1         | 0.37%   |
| Ralink                            | 1         | 0.37%   |
| Qualcomm Atheros Communications   | 1         | 0.37%   |
| OPPO Electronics                  | 1         | 0.37%   |
| Luminary Micro                    | 1         | 0.37%   |
| ICS Advent                        | 1         | 0.37%   |
| Huawei Technologies               | 1         | 0.37%   |
| Google                            | 1         | 0.37%   |
| Aquantia                          | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 7.73%   |
| Intel Wireless 8265 / 8275                                             | 20        | 5.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 17        | 4.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 16        | 4.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 14        | 3.87%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 13        | 3.59%   |
| Intel Ethernet Connection (6) I219-LM                                  | 12        | 3.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 3.31%   |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 3.04%   |
| Intel Wireless 8260                                                    | 10        | 2.76%   |
| Intel Ethernet Connection (10) I219-LM                                 | 10        | 2.76%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 9         | 2.49%   |
| Intel Wi-Fi 6 AX200                                                    | 9         | 2.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 9         | 2.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 2.21%   |
| Intel Ethernet Connection (7) I219-LM                                  | 8         | 2.21%   |
| Intel Wi-Fi 6 AX201                                                    | 7         | 1.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.66%   |
| Intel Wireless 7265                                                    | 5         | 1.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 1.38%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                                   | 4         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 1.1%    |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 1.1%    |
| Intel Centrino Ultimate-N 6300                                         | 4         | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 0.83%   |
| Lenovo USB-C to LAN                                                    | 3         | 0.83%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3         | 0.83%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 3         | 0.83%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.83%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 0.83%   |
| Intel Ethernet Connection (10) I219-V                                  | 3         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 0.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 143       | 79.44%  |
| Realtek Semiconductor           | 12        | 6.67%   |
| Qualcomm Atheros                | 10        | 5.56%   |
| MediaTek                        | 3         | 1.67%   |
| Sierra Wireless                 | 2         | 1.11%   |
| Dell                            | 2         | 1.11%   |
| Broadcom Limited                | 2         | 1.11%   |
| Broadcom                        | 2         | 1.11%   |
| TP-Link                         | 1         | 0.56%   |
| Ralink Technology               | 1         | 0.56%   |
| Ralink                          | 1         | 0.56%   |
| Qualcomm Atheros Communications | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                   | 20        | 11.11%  |
| Intel Comet Lake PCH-LP CNVi WiFi                                            | 17        | 9.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                     | 16        | 8.89%   |
| Intel Comet Lake PCH CNVi WiFi                                               | 13        | 7.22%   |
| Intel Wireless 8260                                                          | 10        | 5.56%   |
| Intel Wi-Fi 6 AX200                                                          | 9         | 5%      |
| Intel Cannon Lake PCH CNVi WiFi                                              | 9         | 5%      |
| Intel Wi-Fi 6 AX201                                                          | 7         | 3.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                 | 6         | 3.33%   |
| Intel Wireless 7265                                                          | 5         | 2.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                             | 5         | 2.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                    | 4         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                               | 4         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                     | 3         | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                   | 3         | 1.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                      | 3         | 1.67%   |
| Intel Raptor Lake PCH CNVi WiFi                                              | 3         | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                              | 2         | 1.11%   |
| Realtek RTL8723DE Wireless Network Adapter                                   | 2         | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                   | 2         | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                   | 2         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                   | 2         | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                             | 2         | 1.11%   |
| Intel Wireless 3165                                                          | 2         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                              | 2         | 1.11%   |
| Intel Alder Lake-S PCH CNVi WiFi                                             | 2         | 1.11%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                         | 2         | 1.11%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                       | 1         | 0.56%   |
| Sierra Wireless Sierra Wireless EM7431 QualcommÂ Snapdragonâ¢ X16 LTE-A | 1         | 0.56%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                              | 1         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                     | 1         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                              | 1         | 0.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                      | 1         | 0.56%   |
| Ralink MT7601U Wireless Adapter                                              | 1         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                    | 1         | 0.56%   |
| Qualcomm Atheros AR9271 802.11n                                              | 1         | 0.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)               | 1         | 0.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                      | 1         | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                | 1         | 0.56%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                          | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 93        | 52.54%  |
| Realtek Semiconductor    | 50        | 28.25%  |
| Lenovo                   | 18        | 10.17%  |
| Qualcomm Atheros         | 2         | 1.13%   |
| Marvell Technology Group | 2         | 1.13%   |
| DisplayLink              | 2         | 1.13%   |
| ASIX Electronics         | 2         | 1.13%   |
| Xiaomi                   | 1         | 0.56%   |
| Samsung Electronics      | 1         | 0.56%   |
| OPPO Electronics         | 1         | 0.56%   |
| ICS Advent               | 1         | 0.56%   |
| Huawei Technologies      | 1         | 0.56%   |
| Google                   | 1         | 0.56%   |
| Broadcom Limited         | 1         | 0.56%   |
| Aquantia                 | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 28        | 15.64%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 14        | 7.82%   |
| Intel Ethernet Connection (6) I219-LM                                          | 12        | 6.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 6.7%    |
| Intel Ethernet Connection (4) I219-LM                                          | 11        | 6.15%   |
| Intel Ethernet Connection (10) I219-LM                                         | 10        | 5.59%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 9         | 5.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 4.47%   |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 4.47%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 2.23%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 2.23%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 2.23%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 2.23%   |
| Lenovo USB-C to LAN                                                            | 3         | 1.68%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.68%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 1.68%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.68%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.12%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1.12%   |
| Lenovo ThinkPad Lan                                                            | 2         | 1.12%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.12%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 1.12%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 1.12%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.56%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.56%   |
| OPPO SM8350-MTP _SN:9338D66C                                                   | 1         | 0.56%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.56%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.56%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.56%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.56%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.56%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.56%   |
| Intel Ethernet Connection (23) I219-LM                                         | 1         | 0.56%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.56%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 172       | 53.25%  |
| Ethernet | 148       | 45.82%  |
| Modem    | 3         | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 132       | 69.47%  |
| Ethernet | 58        | 30.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 135       | 78.03%  |
| 1     | 38        | 21.97%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 151       | 86.78%  |
| Yes  | 23        | 13.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 110       | 77.46%  |
| Broadcom                        | 9         | 6.34%   |
| Realtek Semiconductor           | 5         | 3.52%   |
| Qualcomm Atheros Communications | 5         | 3.52%   |
| IMC Networks                    | 4         | 2.82%   |
| Foxconn / Hon Hai               | 3         | 2.11%   |
| Cambridge Silicon Radio         | 2         | 1.41%   |
| Ralink                          | 1         | 0.7%    |
| MediaTek                        | 1         | 0.7%    |
| Dell                            | 1         | 0.7%    |
| ASUSTek Computer                | 1         | 0.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 40        | 28.17%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 22        | 15.49%  |
| Intel Bluetooth Device                                                              | 21        | 14.79%  |
| Intel AX200 Bluetooth                                                               | 9         | 6.34%   |
| Intel Bluetooth wireless interface                                                  | 6         | 4.23%   |
| Intel AX211 Bluetooth                                                               | 5         | 3.52%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.82%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.82%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.11%   |
| Intel AX210 Bluetooth                                                               | 3         | 2.11%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.41%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.41%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.41%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.7%    |
| MediaTek Wireless_Device                                                            | 1         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.7%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.7%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.7%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.7%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.7%    |
| Foxconn / Hon Hai BT                                                                | 1         | 0.7%    |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.7%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.7%    |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.7%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.7%    |
| ASUS ASUS USB-BT500                                                                 | 1         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 162       | 62.31%  |
| Nvidia                  | 30        | 11.54%  |
| AMD                     | 16        | 6.15%   |
| Lenovo                  | 14        | 5.38%   |
| Realtek Semiconductor   | 6         | 2.31%   |
| GN Netcom               | 5         | 1.92%   |
| Texas Instruments       | 4         | 1.54%   |
| Plantronics             | 3         | 1.15%   |
| JMTek                   | 2         | 0.77%   |
| Hewlett-Packard         | 2         | 0.77%   |
| Generalplus Technology  | 2         | 0.77%   |
| Corsair                 | 2         | 0.77%   |
| C-Media Electronics     | 2         | 0.77%   |
| SteelSeries ApS         | 1         | 0.38%   |
| Sony                    | 1         | 0.38%   |
| Logitech                | 1         | 0.38%   |
| LG Electronics          | 1         | 0.38%   |
| Google                  | 1         | 0.38%   |
| Focusrite-Novation      | 1         | 0.38%   |
| DSEA A/S                | 1         | 0.38%   |
| Dell                    | 1         | 0.38%   |
| Blue Microphones        | 1         | 0.38%   |
| BEHRINGER International | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 29        | 10.47%  |
| Intel Cannon Point-LP High Definition Audio Controller                            | 19        | 6.86%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 18        | 6.5%    |
| Intel Cannon Lake PCH cAVS                                                        | 15        | 5.42%   |
| Intel Comet Lake PCH cAVS                                                         | 13        | 4.69%   |
| AMD Family 17h/19h HD Audio Controller                                            | 10        | 3.61%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 9         | 3.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9         | 3.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 7         | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7         | 2.53%   |
| Realtek Semiconductor USB Audio                                                   | 6         | 2.17%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 6         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6         | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 6         | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 6         | 2.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 5         | 1.81%   |
| Intel CM238 HD Audio Controller                                                   | 5         | 1.81%   |
| Intel Broadwell-U Audio Controller                                                | 5         | 1.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 5         | 1.81%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 1.44%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 1.08%   |
| Plantronics BT600                                                                 | 3         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 1.08%   |
| Nvidia GA106 High Definition Audio Controller                                     | 3         | 1.08%   |
| Nvidia Audio device                                                               | 3         | 1.08%   |
| Intel Raptor Lake-P/U/H cAVS                                                      | 3         | 1.08%   |
| Intel Haswell-ULT HD Audio Controller                                             | 3         | 1.08%   |
| Intel 8 Series HD Audio Controller                                                | 3         | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2         | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 0.72%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 0.72%   |
| Intel Alder Lake-S HD Audio Controller                                            | 2         | 0.72%   |
| Hewlett-Packard USB Audio                                                         | 2         | 0.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 0.72%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.72%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                 | 1         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 37.31%  |
| SK hynix            | 18        | 26.87%  |
| Kingston            | 5         | 7.46%   |
| Crucial             | 5         | 7.46%   |
| Micron Technology   | 4         | 5.97%   |
| Unknown             | 2         | 2.99%   |
| Smart               | 2         | 2.99%   |
| Elpida              | 2         | 2.99%   |
| Unknown (0x0B5E)    | 1         | 1.49%   |
| Transcend           | 1         | 1.49%   |
| Innodisk            | 1         | 1.49%   |
| GOODRAM             | 1         | 1.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 5         | 7.14%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 3         | 4.29%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 2.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 2         | 2.86%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 2         | 2.86%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 2.86%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 2.86%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s        | 2         | 2.86%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s           | 2         | 2.86%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 1.43%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.43%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 1.43%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s           | 1         | 1.43%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 1.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.43%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.43%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.43%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 1.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.43%   |
| SK hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.43%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.43%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.43%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 1.43%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.43%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s          | 1         | 1.43%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 1.43%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                    | 1         | 1.43%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.43%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.43%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s          | 1         | 1.43%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.43%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.43%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.43%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 35        | 66.04%  |
| DDR3   | 14        | 26.42%  |
| LPDDR5 | 1         | 1.89%   |
| LPDDR4 | 1         | 1.89%   |
| LPDDR3 | 1         | 1.89%   |
| DDR5   | 1         | 1.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 96.15%  |
| Row Of Chips | 2         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 21        | 36.21%  |
| 8192  | 18        | 31.03%  |
| 4096  | 13        | 22.41%  |
| 32768 | 5         | 8.62%   |
| 2048  | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 17        | 29.31%  |
| 2667  | 14        | 24.14%  |
| 1600  | 11        | 18.97%  |
| 2133  | 5         | 8.62%   |
| 2400  | 4         | 6.9%    |
| 1333  | 3         | 5.17%   |
| 6400  | 1         | 1.72%   |
| 4800  | 1         | 1.72%   |
| 2933  | 1         | 1.72%   |
| 1334  | 1         | 1.72%   |

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
| Chicony Electronics                    | 50        | 28.25%  |
| IMC Networks                           | 25        | 14.12%  |
| Bison Electronics                      | 17        | 9.6%    |
| Realtek Semiconductor                  | 15        | 8.47%   |
| Microdia                               | 15        | 8.47%   |
| Sunplus Innovation Technology          | 10        | 5.65%   |
| Logitech                               | 7         | 3.95%   |
| Luxvisions Innotech Limited            | 5         | 2.82%   |
| Lite-On Technology                     | 5         | 2.82%   |
| Suyin                                  | 4         | 2.26%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.26%   |
| Samsung Electronics                    | 3         | 1.69%   |
| Syntek                                 | 2         | 1.13%   |
| Quanta                                 | 2         | 1.13%   |
| Microsoft                              | 2         | 1.13%   |
| Acer                                   | 2         | 1.13%   |
| Sonix Technology                       | 1         | 0.56%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.56%   |
| Ruision                                | 1         | 0.56%   |
| Remo Tech                              | 1         | 0.56%   |
| LG Electronics                         | 1         | 0.56%   |
| Lenovo                                 | 1         | 0.56%   |
| KYE Systems (Mouse Systems)            | 1         | 0.56%   |
| Hopewin Electronic Material            | 1         | 0.56%   |
| Creative Technology                    | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 24        | 13.33%  |
| IMC Networks Integrated Camera                    | 20        | 11.11%  |
| Realtek Integrated_Webcam_HD                      | 10        | 5.56%   |
| Bison Integrated Camera                           | 7         | 3.89%   |
| Sunplus Integrated_Webcam_HD                      | 5         | 2.78%   |
| Microdia Integrated_Webcam_HD                     | 5         | 2.78%   |
| Chicony Integrated Camera (1280x720@30)           | 5         | 2.78%   |
| Chicony HP HD Camera                              | 5         | 2.78%   |
| Bison SunplusIT Integrated Camera                 | 5         | 2.78%   |
| Logitech HD Pro Webcam C920                       | 4         | 2.22%   |
| Lite-On Integrated Camera                         | 4         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 4         | 2.22%   |
| Chicony ThinkPad T490 Webcam                      | 4         | 2.22%   |
| Samsung Galaxy series, misc. (MTP mode)           | 3         | 1.67%   |
| Microdia Integrated Webcam                        | 3         | 1.67%   |
| Suyin Integrated_Webcam_HD                        | 2         | 1.11%   |
| Microdia Webcam                                   | 2         | 1.11%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 2         | 1.11%   |
| Chicony Integrated Camera [ThinkPad]              | 2         | 1.11%   |
| Chicony HP HD Webcam [Fixed]                      | 2         | 1.11%   |
| Bison Integrated IR Camera                        | 2         | 1.11%   |
| Bison HD Webcam                                   | 2         | 1.11%   |
| Syntek Lenovo EasyCamera                          | 1         | 0.56%   |
| Syntek Integrated Camera                          | 1         | 0.56%   |
| Suyin RGBIR Camera                                | 1         | 0.56%   |
| Suyin HP Truevision HD                            | 1         | 0.56%   |
| Sunplus USB2.0 Camera                             | 1         | 0.56%   |
| Sunplus PC Camera                                 | 1         | 0.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 1         | 0.56%   |
| Sunplus Integrated Camera                         | 1         | 0.56%   |
| Sunplus HP HD Webcam [Fixed]                      | 1         | 0.56%   |
| Sonix USB2.0 HD UVC WebCam                        | 1         | 0.56%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera   | 1         | 0.56%   |
| Ruision UVC Camera                                | 1         | 0.56%   |
| Remo Tech OBSBOT Tiny 4K                          | 1         | 0.56%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 0.56%   |
| Realtek USB Camera                                | 1         | 0.56%   |
| Realtek Thronmax Stream Go Pro Webcam             | 1         | 0.56%   |
| Realtek Integrated Webcam_HD                      | 1         | 0.56%   |
| Realtek HP Webcam                                 | 1         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 40        | 61.54%  |
| Validity Sensors           | 17        | 26.15%  |
| Shenzhen Goodix Technology | 4         | 6.15%   |
| Upek                       | 2         | 3.08%   |
| Samsung Electronics        | 1         | 1.54%   |
| Elan Microelectronics      | 1         | 1.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 40%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 10.77%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 4.62%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.62%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 4.62%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 4.62%   |
| Validity Sensors VFS491                                                    | 2         | 3.08%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.08%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.08%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.08%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.54%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.54%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.54%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.54%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.54%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.54%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.54%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.54%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 17        | 65.38%  |
| Alcor Micro | 6         | 23.08%  |
| Lenovo      | 2         | 7.69%   |
| Upek        | 1         | 3.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                             | 7         | 26.92%  |
| Broadcom 5880                                              | 6         | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader                        | 6         | 23.08%  |
| Broadcom BCM5880 Secure Applications Processor             | 4         | 15.38%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 7.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 3.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 82        | 46.59%  |
| 0     | 71        | 40.34%  |
| 2     | 17        | 9.66%   |
| 3     | 4         | 2.27%   |
| 5     | 1         | 0.57%   |
| 4     | 1         | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 65        | 48.15%  |
| Graphics card            | 20        | 14.81%  |
| Chipcard                 | 17        | 12.59%  |
| Net/wireless             | 9         | 6.67%   |
| Multimedia controller    | 7         | 5.19%   |
| Card reader              | 6         | 4.44%   |
| Net/ethernet             | 4         | 2.96%   |
| Bluetooth                | 3         | 2.22%   |
| Communication controller | 2         | 1.48%   |
| Storage                  | 1         | 0.74%   |
| Camera                   | 1         | 0.74%   |

