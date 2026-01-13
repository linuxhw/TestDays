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

Total: 339

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Medion        | E15301                      | [7154d8f268](https://linux-hardware.org/?probe=7154d8f268) | Dec 24, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [9dd9dfc62f](https://linux-hardware.org/?probe=9dd9dfc62f) | Dec 23, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f1d96afe71](https://linux-hardware.org/?probe=f1d96afe71) | Dec 23, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f645e7853f](https://linux-hardware.org/?probe=f645e7853f) | Dec 14, 2025 |
| HP            | ZBook 15 G5                 | [b00db81fe5](https://linux-hardware.org/?probe=b00db81fe5) | Dec 07, 2025 |
| HP            | EliteBook 855 G7 Noteboo... | [372612d4cb](https://linux-hardware.org/?probe=372612d4cb) | Nov 21, 2025 |
| HP            | ZBook Fury 16 G10 Mobile... | [0d1e21ed35](https://linux-hardware.org/?probe=0d1e21ed35) | Oct 18, 2025 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [dff2f956e4](https://linux-hardware.org/?probe=dff2f956e4) | Oct 05, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [51b1869ab3](https://linux-hardware.org/?probe=51b1869ab3) | Sep 01, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a7ca8790e2](https://linux-hardware.org/?probe=a7ca8790e2) | Sep 01, 2025 |
| Dell          | Pro Max 14 MC14250          | [e284bbe318](https://linux-hardware.org/?probe=e284bbe318) | Aug 08, 2025 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [ebfb439ae8](https://linux-hardware.org/?probe=ebfb439ae8) | Jul 28, 2025 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [50ad7f0414](https://linux-hardware.org/?probe=50ad7f0414) | Jul 23, 2025 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [4f1a9b731c](https://linux-hardware.org/?probe=4f1a9b731c) | Jul 22, 2025 |
| HP            | EliteBook 8470p             | [699e60ab98](https://linux-hardware.org/?probe=699e60ab98) | Jul 20, 2025 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [d694fa0335](https://linux-hardware.org/?probe=d694fa0335) | Jul 13, 2025 |
| Unknown       | Unknown                     | [b1f831d148](https://linux-hardware.org/?probe=b1f831d148) | Jul 09, 2025 |
| HP            | EliteBook 8470p             | [03e67e85c7](https://linux-hardware.org/?probe=03e67e85c7) | Jul 07, 2025 |
| Dell          | Precision 5490              | [862d9564ec](https://linux-hardware.org/?probe=862d9564ec) | Jun 30, 2025 |
| Alienware     | m18 R1 AMD                  | [17d23a6c79](https://linux-hardware.org/?probe=17d23a6c79) | Jun 15, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | [6bddfcec0d](https://linux-hardware.org/?probe=6bddfcec0d) | Jun 13, 2025 |
| ASUSTek       | ProArt Studiobook H7604J... | [e1c82d7e68](https://linux-hardware.org/?probe=e1c82d7e68) | Jun 04, 2025 |
| Dell          | Precision 5490              | [aa3fe64169](https://linux-hardware.org/?probe=aa3fe64169) | Jun 02, 2025 |
| Dell          | Precision M4800             | [f3a2c881d4](https://linux-hardware.org/?probe=f3a2c881d4) | May 29, 2025 |
| HP            | ZBook Fury 15 G7 Mobile ... | [6fcbd16acf](https://linux-hardware.org/?probe=6fcbd16acf) | May 21, 2025 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [f65f1d1f72](https://linux-hardware.org/?probe=f65f1d1f72) | May 20, 2025 |
| Dell          | Precision M4800             | [b31e551454](https://linux-hardware.org/?probe=b31e551454) | May 14, 2025 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | [54677dffeb](https://linux-hardware.org/?probe=54677dffeb) | Apr 04, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | [12adf7443f](https://linux-hardware.org/?probe=12adf7443f) | Apr 01, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [14d91dd406](https://linux-hardware.org/?probe=14d91dd406) | Mar 29, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8f0328cec8](https://linux-hardware.org/?probe=8f0328cec8) | Mar 29, 2025 |
| Acer          | Aspire AL14-31P             | [c1b9edd8c5](https://linux-hardware.org/?probe=c1b9edd8c5) | Mar 27, 2025 |
| Lenovo        | Legion S7 15ACH6 82K8       | [58a52af839](https://linux-hardware.org/?probe=58a52af839) | Mar 13, 2025 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | [72c5b1b57e](https://linux-hardware.org/?probe=72c5b1b57e) | Feb 22, 2025 |
| Lenovo        | ThinkPad P1 Gen 6 21FWS1... | [42d17fcd67](https://linux-hardware.org/?probe=42d17fcd67) | Feb 14, 2025 |
| Lenovo        | ThinkPad P16v Gen 2 21KY... | [4c043a2d86](https://linux-hardware.org/?probe=4c043a2d86) | Feb 12, 2025 |
| HP            | Laptop 15-fd0xxx            | [bd083d24c2](https://linux-hardware.org/?probe=bd083d24c2) | Jan 23, 2025 |
| HP            | ProBook 4530s               | [e4dbd31493](https://linux-hardware.org/?probe=e4dbd31493) | Jan 21, 2025 |
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
| RHEL 8  | 126       | 56.5%   |
| RHEL 9  | 77        | 34.53%  |
| RHEL 7  | 10        | 4.48%   |
| RHEL 10 | 10        | 4.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| RHEL | 220       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64  | 10        | 3.88%   |
| 4.18.0-240.1.1.el8_3.x86_64   | 10        | 3.88%   |
| 4.18.0-80.11.2.el8_0.x86_64   | 8         | 3.1%    |
| 4.18.0-240.15.1.el8_3.x86_64  | 8         | 3.1%    |
| 4.18.0-425.10.1.el8_7.x86_64  | 7         | 2.71%   |
| 4.18.0-348.20.1.el8_5.x86_64  | 7         | 2.71%   |
| 4.18.0-305.3.1.el8_4.x86_64   | 7         | 2.71%   |
| 5.14.0-284.30.1.el9_2.x86_64  | 6         | 2.33%   |
| 5.14.0-162.6.1.el9_1.x86_64   | 4         | 1.55%   |
| 5.14.0-162.12.1.el9_1.x86_64  | 4         | 1.55%   |
| 4.18.0-348.2.1.el8_5.x86_64   | 4         | 1.55%   |
| 4.18.0-348.12.2.el8_5.x86_64  | 4         | 1.55%   |
| 4.18.0-305.7.1.el8_4.x86_64   | 4         | 1.55%   |
| 4.18.0-305.25.1.el8_4.x86_64  | 4         | 1.55%   |
| 4.18.0-305.19.1.el8_4.x86_64  | 4         | 1.55%   |
| 4.18.0-305.10.2.el8_4.x86_64  | 4         | 1.55%   |
| 4.18.0-240.22.1.el8_3.x86_64  | 4         | 1.55%   |
| 4.18.0-193.el8.x86_64         | 4         | 1.55%   |
| 4.18.0-193.19.1.el8_2.x86_64  | 4         | 1.55%   |
| 5.14.0-70.5.1.el9_0.x86_64    | 3         | 1.16%   |
| 5.14.0-70.26.1.el9_0.x86_64   | 3         | 1.16%   |
| 5.14.0-503.34.1.el9_5.x86_64  | 3         | 1.16%   |
| 5.14.0-427.42.1.el9_4.x86_64  | 3         | 1.16%   |
| 5.14.0-427.22.1.el9_4.x86_64  | 3         | 1.16%   |
| 5.14.0-427.13.1.el9_4.x86_64  | 3         | 1.16%   |
| 5.14.0-362.8.1.el9_3.x86_64   | 3         | 1.16%   |
| 5.14.0-362.13.1.el9_3.x86_64  | 3         | 1.16%   |
| 5.14.0-284.25.1.el9_2.x86_64  | 3         | 1.16%   |
| 5.14.0-162.23.1.el9_1.x86_64  | 3         | 1.16%   |
| 4.18.0-425.3.1.el8.x86_64     | 3         | 1.16%   |
| 4.18.0-372.9.1.el8.x86_64     | 3         | 1.16%   |
| 4.18.0-348.7.1.el8_5.x86_64   | 3         | 1.16%   |
| 4.18.0-305.el8.x86_64         | 3         | 1.16%   |
| 4.18.0-305.12.1.el8_4.x86_64  | 3         | 1.16%   |
| 4.18.0-193.6.3.el8_2.x86_64   | 3         | 1.16%   |
| 4.18.0-193.28.1.el8_2.x86_64  | 3         | 1.16%   |
| 4.18.0-147.el8.x86_64         | 3         | 1.16%   |
| 4.18.0-147.5.1.el8_1.x86_64   | 3         | 1.16%   |
| 6.12.0-55.16.1.el10_0.x86_64  | 2         | 0.78%   |
| 6.12.0-124.21.1.el10_1.x86_64 | 2         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 124       | 55.61%  |
| 5.14.0  | 74        | 33.18%  |
| 3.10.0  | 10        | 4.48%   |
| 6.12.0  | 9         | 4.04%   |
| 6.7.1   | 1         | 0.45%   |
| 6.5.2   | 1         | 0.45%   |
| 6.17.3  | 1         | 0.45%   |
| 6.14.9  | 1         | 0.45%   |
| 6.11.0  | 1         | 0.45%   |
| 5.9.1   | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 124       | 55.61%  |
| 5.14    | 74        | 33.18%  |
| 3.10    | 10        | 4.48%   |
| 6.12    | 9         | 4.04%   |
| 6.7     | 1         | 0.45%   |
| 6.5     | 1         | 0.45%   |
| 6.17    | 1         | 0.45%   |
| 6.14    | 1         | 0.45%   |
| 6.11    | 1         | 0.45%   |
| 5.9     | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 220       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 194       | 85.09%  |
| Unknown         | 13        | 5.7%    |
| GNOME Classic   | 11        | 4.82%   |
| KDE5            | 6         | 2.63%   |
| XFCE            | 1         | 0.44%   |
| KDE4            | 1         | 0.44%   |
| GNOME Flashback | 1         | 0.44%   |
| Cinnamon        | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 119       | 53.13%  |
| X11     | 100       | 44.64%  |
| Unknown | 5         | 2.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 162       | 71.37%  |
| GDM     | 64        | 28.19%  |
| SDDM    | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 153       | 68.3%   |
| en_GB   | 12        | 5.36%   |
| Unknown | 10        | 4.46%   |
| pt_BR   | 6         | 2.68%   |
| en_IN   | 6         | 2.68%   |
| fr_FR   | 5         | 2.23%   |
| de_DE   | 4         | 1.79%   |
| pl_PL   | 3         | 1.34%   |
| en_IE   | 3         | 1.34%   |
| de_CH   | 3         | 1.34%   |
| cs_CZ   | 3         | 1.34%   |
| nl_NL   | 2         | 0.89%   |
| zh_CN   | 1         | 0.45%   |
| ru_RU   | 1         | 0.45%   |
| ro_RO   | 1         | 0.45%   |
| nl_BE   | 1         | 0.45%   |
| ko_KR   | 1         | 0.45%   |
| ja_JP   | 1         | 0.45%   |
| it_IT   | 1         | 0.45%   |
| es_MX   | 1         | 0.45%   |
| es_ES   | 1         | 0.45%   |
| es_EC   | 1         | 0.45%   |
| es_CO   | 1         | 0.45%   |
| en_DK   | 1         | 0.45%   |
| en_CA   | 1         | 0.45%   |
| C       | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 181       | 80.8%   |
| BIOS | 43        | 19.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 194       | 87.39%  |
| Ext4    | 18        | 8.11%   |
| Unknown | 8         | 3.6%    |
| Tmpfs   | 2         | 0.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 159       | 70.04%  |
| GPT     | 64        | 28.19%  |
| MBR     | 4         | 1.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 211       | 94.62%  |
| Yes       | 12        | 5.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 203       | 91.03%  |
| Yes       | 20        | 8.97%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 108       | 49.09%  |
| Dell                | 46        | 20.91%  |
| Hewlett-Packard     | 28        | 12.73%  |
| ASUSTek Computer    | 13        | 5.91%   |
| MSI                 | 5         | 2.27%   |
| Acer                | 3         | 1.36%   |
| Sony                | 2         | 0.91%   |
| Getac               | 2         | 0.91%   |
| Unknown             | 2         | 0.91%   |
| UNOWHY              | 1         | 0.45%   |
| TUXEDO              | 1         | 0.45%   |
| Toshiba             | 1         | 0.45%   |
| Timi                | 1         | 0.45%   |
| System76            | 1         | 0.45%   |
| Samsung Electronics | 1         | 0.45%   |
| Razer               | 1         | 0.45%   |
| Medion              | 1         | 0.45%   |
| LG Electronics      | 1         | 0.45%   |
| Gigabyte Technology | 1         | 0.45%   |
| Alienware           | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 4         | 1.82%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 0.91%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 0.91%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 0.91%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 0.91%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 2         | 0.91%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 0.91%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 2         | 0.91%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 0.91%   |
| HP ZBook 15 G5                           | 2         | 0.91%   |
| HP EliteBook 8460p                       | 2         | 0.91%   |
| HP EliteBook 2570p                       | 2         | 0.91%   |
| Dell Precision M4800                     | 2         | 0.91%   |
| Dell Precision 7560                      | 2         | 0.91%   |
| Dell Precision 7510                      | 2         | 0.91%   |
| Dell Latitude E6430                      | 2         | 0.91%   |
| Dell Latitude 5300                       | 2         | 0.91%   |
| Unknown                                  | 2         | 0.91%   |
| UNOWHY Y13G010S4EI                       | 1         | 0.45%   |
| TUXEDO N13xWU                            | 1         | 0.45%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.45%   |
| Timi TM1707                              | 1         | 0.45%   |
| System76 Galago Pro                      | 1         | 0.45%   |
| Sony VPCEB4L1R                           | 1         | 0.45%   |
| Sony VPCEB23FM                           | 1         | 0.45%   |
| Samsung 730QCJ/730QCR                    | 1         | 0.45%   |
| Razer Blade 15 Mid 2019-Base             | 1         | 0.45%   |
| MSI Modern 15 A5M                        | 1         | 0.45%   |
| MSI Katana GF76 12UC                     | 1         | 0.45%   |
| MSI Katana GF66 12UC                     | 1         | 0.45%   |
| MSI GP75 Leopard 9SD                     | 1         | 0.45%   |
| MSI GE72VR 7RF                           | 1         | 0.45%   |
| Medion E15301                            | 1         | 0.45%   |
| LG 15Z95P-GRLGL                          | 1         | 0.45%   |
| Lenovo Z40-70 20366                      | 1         | 0.45%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 0.45%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 0.45%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 0.45%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 0.45%   |
| Lenovo ThinkPad X131e 3368CTO            | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 97        | 44.09%  |
| Dell Latitude      | 18        | 8.18%   |
| Dell Precision     | 17        | 7.73%   |
| HP EliteBook       | 10        | 4.55%   |
| HP ZBook           | 7         | 3.18%   |
| Dell Inspiron      | 6         | 2.73%   |
| Lenovo IdeaPad     | 4         | 1.82%   |
| Lenovo ThinkBook   | 3         | 1.36%   |
| Lenovo Legion      | 3         | 1.36%   |
| HP ProBook         | 3         | 1.36%   |
| HP Laptop          | 3         | 1.36%   |
| ASUS VivoBook      | 3         | 1.36%   |
| MSI Katana         | 2         | 0.91%   |
| Dell XPS           | 2         | 0.91%   |
| ASUS TUF           | 2         | 0.91%   |
| Acer Aspire        | 2         | 0.91%   |
| Unknown            | 2         | 0.91%   |
| UNOWHY Y13G010S4EI | 1         | 0.45%   |
| TUXEDO N13xWU      | 1         | 0.45%   |
| Toshiba Satellite  | 1         | 0.45%   |
| Timi TM1707        | 1         | 0.45%   |
| System76 Galago    | 1         | 0.45%   |
| Sony VPCEB4L1R     | 1         | 0.45%   |
| Sony VPCEB23FM     | 1         | 0.45%   |
| Samsung 730QCJ     | 1         | 0.45%   |
| Razer Blade        | 1         | 0.45%   |
| MSI Modern         | 1         | 0.45%   |
| MSI GP75           | 1         | 0.45%   |
| MSI GE72VR         | 1         | 0.45%   |
| Medion E15301      | 1         | 0.45%   |
| LG 15Z95P-GRLGL    | 1         | 0.45%   |
| Lenovo Z40-70      | 1         | 0.45%   |
| HP Stream          | 1         | 0.45%   |
| HP Pavilion        | 1         | 0.45%   |
| HP OMEN            | 1         | 0.45%   |
| HP 340S            | 1         | 0.45%   |
| HP 250             | 1         | 0.45%   |
| Gigabyte AERO      | 1         | 0.45%   |
| Getac S410G4       | 1         | 0.45%   |
| Getac B360         | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 42        | 19.09%  |
| 2019 | 39        | 17.73%  |
| 2018 | 23        | 10.45%  |
| 2021 | 22        | 10%     |
| 2023 | 13        | 5.91%   |
| 2011 | 12        | 5.45%   |
| 2016 | 11        | 5%      |
| 2017 | 10        | 4.55%   |
| 2015 | 10        | 4.55%   |
| 2022 | 9         | 4.09%   |
| 2014 | 8         | 3.64%   |
| 2012 | 8         | 3.64%   |
| 2024 | 4         | 1.82%   |
| 2013 | 4         | 1.82%   |
| 2010 | 4         | 1.82%   |
| 2025 | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 220       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 180       | 81.08%  |
| Enabled  | 42        | 18.92%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 219       | 99.55%  |
| Yes  | 1         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 65        | 29.02%  |
| 8.01-16.0   | 53        | 23.66%  |
| 4.01-8.0    | 40        | 17.86%  |
| 16.01-24.0  | 28        | 12.5%   |
| 64.01-256.0 | 21        | 9.38%   |
| 3.01-4.0    | 11        | 4.91%   |
| 24.01-32.0  | 6         | 2.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 101       | 41.91%  |
| 3.01-4.0   | 43        | 17.84%  |
| 2.01-3.0   | 39        | 16.18%  |
| 8.01-16.0  | 31        | 12.86%  |
| 1.01-2.0   | 18        | 7.47%   |
| 16.01-24.0 | 4         | 1.66%   |
| 24.01-32.0 | 3         | 1.24%   |
| 32.01-64.0 | 1         | 0.41%   |
| 0.51-1.0   | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 162       | 71.68%  |
| 2      | 46        | 20.35%  |
| 3      | 16        | 7.08%   |
| 4      | 2         | 0.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 195       | 88.24%  |
| Yes       | 26        | 11.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 85.07%  |
| No        | 33        | 14.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 211       | 95.91%  |
| No        | 9         | 4.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 79.82%  |
| No        | 46        | 20.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 52        | 23.64%  |
| India        | 26        | 11.82%  |
| Germany      | 11        | 5%      |
| UK           | 10        | 4.55%   |
| Czechia      | 8         | 3.64%   |
| Brazil       | 8         | 3.64%   |
| France       | 7         | 3.18%   |
| Switzerland  | 6         | 2.73%   |
| Spain        | 6         | 2.73%   |
| Canada       | 6         | 2.73%   |
| Mexico       | 5         | 2.27%   |
| Italy        | 5         | 2.27%   |
| Romania      | 4         | 1.82%   |
| Poland       | 4         | 1.82%   |
| Netherlands  | 4         | 1.82%   |
| South Africa | 3         | 1.36%   |
| Chile        | 3         | 1.36%   |
| Turkey       | 2         | 0.91%   |
| South Korea  | 2         | 0.91%   |
| Singapore    | 2         | 0.91%   |
| Russia       | 2         | 0.91%   |
| Pakistan     | 2         | 0.91%   |
| Kenya        | 2         | 0.91%   |
| Japan        | 2         | 0.91%   |
| Ireland      | 2         | 0.91%   |
| Guatemala    | 2         | 0.91%   |
| Finland      | 2         | 0.91%   |
| Egypt        | 2         | 0.91%   |
| Colombia     | 2         | 0.91%   |
| Australia    | 2         | 0.91%   |
| Vietnam      | 1         | 0.45%   |
| Thailand     | 1         | 0.45%   |
| Sri Lanka    | 1         | 0.45%   |
| Slovakia     | 1         | 0.45%   |
| Saudi Arabia | 1         | 0.45%   |
| Portugal     | 1         | 0.45%   |
| Norway       | 1         | 0.45%   |
| Nepal        | 1         | 0.45%   |
| Myanmar      | 1         | 0.45%   |
| Morocco      | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Prague         | 4         | 1.71%   |
| Munich         | 3         | 1.28%   |
| Mexico City    | 3         | 1.28%   |
| Madrid         | 3         | 1.28%   |
| Chennai        | 3         | 1.28%   |
| Bengaluru      | 3         | 1.28%   |
| Singapore      | 2         | 0.85%   |
| Sao Paulo      | 2         | 0.85%   |
| Santiago       | 2         | 0.85%   |
| Ottawa         | 2         | 0.85%   |
| Nairobi        | 2         | 0.85%   |
| Milan          | 2         | 0.85%   |
| Jaipur         | 2         | 0.85%   |
| Houston        | 2         | 0.85%   |
| Guatemala City | 2         | 0.85%   |
| Coimbatore     | 2         | 0.85%   |
| Berlin         | 2         | 0.85%   |
| Barcelona      | 2         | 0.85%   |
| Austin         | 2         | 0.85%   |
| Zlín          | 1         | 0.43%   |
| Zaragoza       | 1         | 0.43%   |
| Whiteley       | 1         | 0.43%   |
| Webster        | 1         | 0.43%   |
| Wayne          | 1         | 0.43%   |
| Wagholi        | 1         | 0.43%   |
| Vardenis       | 1         | 0.43%   |
| Vancouver      | 1         | 0.43%   |
| Valbrembo      | 1         | 0.43%   |
| Urbandale      | 1         | 0.43%   |
| Udaipur        | 1         | 0.43%   |
| Turku          | 1         | 0.43%   |
| Thun           | 1         | 0.43%   |
| Temuco         | 1         | 0.43%   |
| Temara         | 1         | 0.43%   |
| Taunton        | 1         | 0.43%   |
| Taringa        | 1         | 0.43%   |
| Talkha         | 1         | 0.43%   |
| Syracuse       | 1         | 0.43%   |
| Stuttgart      | 1         | 0.43%   |
| Streatham      | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 71        | 99     | 24.07%  |
| Toshiba                     | 26        | 31     | 8.81%   |
| SanDisk                     | 24        | 32     | 8.14%   |
| SK hynix                    | 20        | 21     | 6.78%   |
| WDC                         | 19        | 23     | 6.44%   |
| Seagate                     | 17        | 24     | 5.76%   |
| Unknown                     | 16        | 18     | 5.42%   |
| Micron Technology           | 13        | 15     | 4.41%   |
| KIOXIA                      | 11        | 14     | 3.73%   |
| Kingston                    | 11        | 11     | 3.73%   |
| Intel                       | 10        | 14     | 3.39%   |
| Micron/Crucial Technology   | 4         | 5      | 1.36%   |
| HGST                        | 4         | 4      | 1.36%   |
| A-DATA Technology           | 4         | 4      | 1.36%   |
| Silicon Motion              | 3         | 4      | 1.02%   |
| Lenovo                      | 3         | 3      | 1.02%   |
| Kingston Technology Company | 3         | 3      | 1.02%   |
| Crucial                     | 3         | 3      | 1.02%   |
| Transcend                   | 2         | 2      | 0.68%   |
| SSSTC                       | 2         | 2      | 0.68%   |
| PNY                         | 2         | 3      | 0.68%   |
| Phison                      | 2         | 2      | 0.68%   |
| Unknown                     | 2         | 2      | 0.68%   |
| WDC WDS                     | 1         | 1      | 0.34%   |
| Union Memory                | 1         | 1      | 0.34%   |
| UMIS                        | 1         | 1      | 0.34%   |
| Team                        | 1         | 2      | 0.34%   |
| SMI                         | 1         | 2      | 0.34%   |
| SCY                         | 1         | 1      | 0.34%   |
| SABRENT                     | 1         | 1      | 0.34%   |
| Realtek Semiconductor       | 1         | 1      | 0.34%   |
| Realtek                     | 1         | 1      | 0.34%   |
| Plextor                     | 1         | 1      | 0.34%   |
| Phison Electronics          | 1         | 1      | 0.34%   |
| MiniPro                     | 1         | 1      | 0.34%   |
| LITEON                      | 1         | 1      | 0.34%   |
| Lite-On                     | 1         | 1      | 0.34%   |
| KingSpec                    | 1         | 1      | 0.34%   |
| Kingmax                     | 1         | 1      | 0.34%   |
| Intenso                     | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB                      | 10        | 3.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 9         | 2.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 9         | 2.88%   |
| SanDisk NVMe SSD Drive 256GB                       | 6         | 1.92%   |
| Samsung NVMe SSD Drive 512GB                       | 6         | 1.92%   |
| Samsung NVMe SSD Drive 256GB                       | 6         | 1.92%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 5         | 1.6%    |
| Samsung NVMe SSD Drive 1024GB                      | 5         | 1.6%    |
| Toshiba NVMe SSD Drive 256GB                       | 4         | 1.28%   |
| Intel NVMe SSD Drive 512GB                         | 4         | 1.28%   |
| Unknown MMC Card  64GB                             | 3         | 0.96%   |
| Toshiba XG6 NVMe SSD Controller 1024GB             | 3         | 0.96%   |
| Toshiba NVMe SSD Drive 512GB                       | 3         | 0.96%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 0.96%   |
| Seagate ST1000LM049-2GH172 1TB                     | 3         | 0.96%   |
| Samsung SSD 860 EVO 1TB                            | 3         | 0.96%   |
| Samsung NVMe SSD Drive 2TB                         | 3         | 0.96%   |
| Samsung NVMe SSD Drive 1TB                         | 3         | 0.96%   |
| Micron NVMe SSD Drive 256GB                        | 3         | 0.96%   |
| HGST HTS721010A9E630 1TB                           | 3         | 0.96%   |
| Unknown NVMe SSD Drive 256GB                       | 2         | 0.64%   |
| Unknown MMC Card  256GB                            | 2         | 0.64%   |
| Unknown MMC Card  16GB                             | 2         | 0.64%   |
| Toshiba NVMe SSD Drive 1024GB                      | 2         | 0.64%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 0.64%   |
| Toshiba KXG6AZNV256G 256GB                         | 2         | 0.64%   |
| SK hynix NVMe SSD Drive 1024GB                     | 2         | 0.64%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 0.64%   |
| Seagate Expansion 2TB                              | 2         | 0.64%   |
| Seagate BUP Slim BK 2TB                            | 2         | 0.64%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB    | 2         | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                       | 2         | 0.64%   |
| Samsung SSD PM830 2.5 7mm 128GB                    | 2         | 0.64%   |
| Samsung SSD 980 1TB                                | 2         | 0.64%   |
| Samsung SSD 860 QVO 1TB                            | 2         | 0.64%   |
| Samsung Portable SSD T5 500GB                      | 2         | 0.64%   |
| Samsung NVMe SSD Drive 500GB                       | 2         | 0.64%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                     | 2         | 0.64%   |
| Micron 2400_MTFDKBA512QFM 512GB                    | 2         | 0.64%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                         | 2         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 17        | 23     | 40.48%  |
| Toshiba | 11        | 13     | 26.19%  |
| WDC     | 10        | 12     | 23.81%  |
| HGST    | 4         | 4      | 9.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 24     | 33.85%  |
| Kingston            | 6         | 6      | 9.23%   |
| WDC                 | 5         | 6      | 7.69%   |
| SanDisk             | 4         | 5      | 6.15%   |
| Crucial             | 3         | 3      | 4.62%   |
| Transcend           | 2         | 2      | 3.08%   |
| PNY                 | 2         | 3      | 3.08%   |
| Micron Technology   | 2         | 2      | 3.08%   |
| Intel               | 2         | 3      | 3.08%   |
| A-DATA Technology   | 2         | 2      | 3.08%   |
| WDC WDS             | 1         | 1      | 1.54%   |
| Toshiba             | 1         | 1      | 1.54%   |
| Team                | 1         | 2      | 1.54%   |
| Seagate             | 1         | 1      | 1.54%   |
| SABRENT             | 1         | 1      | 1.54%   |
| Plextor             | 1         | 1      | 1.54%   |
| Phison              | 1         | 1      | 1.54%   |
| LITEON              | 1         | 1      | 1.54%   |
| KingSpec            | 1         | 1      | 1.54%   |
| Kingmax             | 1         | 1      | 1.54%   |
| Intenso             | 1         | 1      | 1.54%   |
| GOODRAM             | 1         | 1      | 1.54%   |
| DERLAR              | 1         | 1      | 1.54%   |
| Corsair             | 1         | 1      | 1.54%   |
| China               | 1         | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 159       | 220    | 57.61%  |
| SSD     | 59        | 72     | 21.38%  |
| HDD     | 42        | 52     | 15.22%  |
| MMC     | 13        | 16     | 4.71%   |
| Unknown | 3         | 4      | 1.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 158       | 219    | 59.62%  |
| SATA | 79        | 108    | 29.81%  |
| SAS  | 15        | 21     | 5.66%   |
| MMC  | 13        | 16     | 4.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 59     | 50%     |
| 0.51-1.0   | 38        | 46     | 38%     |
| 1.01-2.0   | 7         | 10     | 7%      |
| 3.01-4.0   | 3         | 3      | 3%      |
| 4.01-10.0  | 2         | 6      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 83        | 36.24%  |
| 251-500        | 45        | 19.65%  |
| 501-1000       | 42        | 18.34%  |
| 1001-2000      | 20        | 8.73%   |
| 51-100         | 10        | 4.37%   |
| More than 3000 | 9         | 3.93%   |
| 21-50          | 6         | 2.62%   |
| 2001-3000      | 6         | 2.62%   |
| 1-20           | 4         | 1.75%   |
| Unknown        | 4         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 59        | 24.58%  |
| 21-50          | 55        | 22.92%  |
| 101-250        | 42        | 17.5%   |
| 51-100         | 38        | 15.83%  |
| 251-500        | 25        | 10.42%  |
| 501-1000       | 10        | 4.17%   |
| 1001-2000      | 5         | 2.08%   |
| Unknown        | 4         | 1.67%   |
| More than 3000 | 1         | 0.42%   |
| 2001-3000      | 1         | 0.42%   |

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
| Detected | 171       | 278    | 72.46%  |
| Works    | 59        | 79     | 25%     |
| Malfunc  | 6         | 7      | 2.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 107       | 38.63%  |
| Samsung Electronics              | 51        | 18.41%  |
| SanDisk                          | 24        | 8.66%   |
| SK hynix                         | 20        | 7.22%   |
| Toshiba America Info Systems     | 14        | 5.05%   |
| KIOXIA                           | 13        | 4.69%   |
| Micron Technology                | 11        | 3.97%   |
| AMD                              | 8         | 2.89%   |
| Kingston Technology Company      | 7         | 2.53%   |
| Micron/Crucial Technology        | 4         | 1.44%   |
| Silicon Motion                   | 3         | 1.08%   |
| Phison Electronics               | 3         | 1.08%   |
| Lenovo                           | 3         | 1.08%   |
| ADATA Technology                 | 3         | 1.08%   |
| Union Memory (Shenzhen)          | 2         | 0.72%   |
| Solid State Storage Technology   | 1         | 0.36%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.36%   |
| Realtek Semiconductor            | 1         | 0.36%   |
| Lite-On Technology               | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 28        | 9.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 17        | 6.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 13        | 4.59%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 13        | 4.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 11        | 3.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 11        | 3.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 8         | 2.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 8         | 2.83%   |
| SK hynix PC611 NVMe Solid State Drive                                         | 7         | 2.47%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 7         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 7         | 2.47%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 7         | 2.47%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 6         | 2.12%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                    | 6         | 2.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 5         | 1.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 5         | 1.77%   |
| Intel Comet Lake SATA AHCI Controller                                         | 5         | 1.77%   |
| SK hynix PC601 NVMe Solid State Drive                                         | 4         | 1.41%   |
| Micron 2300 NVMe SSD [Santana]                                                | 4         | 1.41%   |
| KIOXIA NVMe SSD Controller XG8                                                | 4         | 1.41%   |
| Intel Volume Management Device NVMe RAID Controller                           | 4         | 1.41%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                              | 4         | 1.41%   |
| Intel SSD 660P Series                                                         | 4         | 1.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 4         | 1.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 4         | 1.41%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                         | 3         | 1.06%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                   | 3         | 1.06%   |
| Micron 2400 NVMe SSD (DRAM-less)                                              | 3         | 1.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 3         | 1.06%   |
| Intel SATA Controller [RAID mode]                                             | 3         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 3         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 1.06%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 2         | 0.71%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 2         | 0.71%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)     | 2         | 0.71%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                   | 2         | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 0.71%   |
| Micron 3400 NVMe SSD [Hendrix]                                                | 2         | 0.71%   |
| Lenovo LENSE20256GMSP34MEAT2TA                                                | 2         | 0.71%   |
| Kingston Company NV2 NVMe SSD [E21T] (DRAM-less)                              | 2         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 157       | 58.58%  |
| SATA | 93        | 34.7%   |
| RAID | 18        | 6.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 201       | 91.36%  |
| AMD    | 19        | 8.64%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz         | 13        | 5.91%   |
| Intel Core i7-8665U CPU @ 1.90GHz          | 10        | 4.55%   |
| Intel Core i7-10610U CPU @ 1.80GHz         | 10        | 4.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 7         | 3.18%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 6         | 2.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 6         | 2.73%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 5         | 2.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 5         | 2.27%   |
| Intel Core i5-5300U CPU @ 2.30GHz          | 5         | 2.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 1.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 3         | 1.36%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 3         | 1.36%   |
| Intel Core i7-7600U CPU @ 2.80GHz          | 3         | 1.36%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 3         | 1.36%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 3         | 1.36%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 3         | 1.36%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 3         | 1.36%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 3         | 1.36%   |
| Intel Core i3 CPU M 380 @ 2.53GHz          | 3         | 1.36%   |
| Intel 12th Gen Core i7-12700H              | 3         | 1.36%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz    | 3         | 1.36%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 3         | 1.36%   |
| Intel Core i7-9850H CPU @ 2.60GHz          | 2         | 0.91%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 0.91%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 2         | 0.91%   |
| Intel Core i7-3520M CPU @ 2.90GHz          | 2         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 0.91%   |
| Intel Core i5-8365U CPU @ 1.60GHz          | 2         | 0.91%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 2         | 0.91%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 2         | 0.91%   |
| Intel Core i5-3360M CPU @ 2.80GHz          | 2         | 0.91%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz         | 2         | 0.91%   |
| Intel Core i3-6006U CPU @ 2.00GHz          | 2         | 0.91%   |
| Intel 12th Gen Core i7-1260P               | 2         | 0.91%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz    | 2         | 0.91%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 2         | 0.91%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 2         | 0.91%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 2         | 0.91%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 2         | 0.91%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 87        | 39.55%  |
| Intel Core i5   | 49        | 22.27%  |
| Other           | 37        | 16.82%  |
| Intel Core i3   | 9         | 4.09%   |
| AMD Ryzen 7     | 8         | 3.64%   |
| Intel Xeon      | 7         | 3.18%   |
| Intel Core i9   | 4         | 1.82%   |
| Intel Celeron   | 4         | 1.82%   |
| AMD Ryzen 7 PRO | 4         | 1.82%   |
| Intel Core      | 3         | 1.36%   |
| AMD Ryzen 5     | 3         | 1.36%   |
| AMD Ryzen 9     | 2         | 0.91%   |
| Intel Pentium   | 1         | 0.45%   |
| AMD Ryzen 3     | 1         | 0.45%   |
| AMD A10         | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 93        | 42.27%  |
| 2      | 49        | 22.27%  |
| 6      | 32        | 14.55%  |
| 8      | 24        | 10.91%  |
| 10     | 7         | 3.18%   |
| 16     | 5         | 2.27%   |
| 14     | 4         | 1.82%   |
| 12     | 4         | 1.82%   |
| 24     | 1         | 0.45%   |
| 20     | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 220       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 206       | 93.21%  |
| 1      | 15        | 6.79%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 215       | 96.85%  |
| Unknown        | 7         | 3.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 27.23%  |
| 0x806ec    | 36        | 16.07%  |
| 0x806ea    | 15        | 6.7%    |
| 0xa0652    | 12        | 5.36%   |
| 0x906ea    | 8         | 3.57%   |
| 0x506e3    | 8         | 3.57%   |
| 0x406e3    | 8         | 3.57%   |
| 0x306a9    | 8         | 3.57%   |
| 0x206a7    | 7         | 3.13%   |
| 0x806d1    | 6         | 2.68%   |
| 0x806c1    | 6         | 2.68%   |
| 0x906ed    | 5         | 2.23%   |
| 0x906e9    | 4         | 1.79%   |
| 0x806e9    | 4         | 1.79%   |
| 0x306d4    | 4         | 1.79%   |
| 0x20655    | 4         | 1.79%   |
| 0x906a3    | 3         | 1.34%   |
| 0x40651    | 3         | 1.34%   |
| 0x08108102 | 3         | 1.34%   |
| 0x706e5    | 2         | 0.89%   |
| 0x0a50000c | 2         | 0.89%   |
| 0x08600103 | 2         | 0.89%   |
| 0xa0655    | 1         | 0.45%   |
| 0x906a4    | 1         | 0.45%   |
| 0x90672    | 1         | 0.45%   |
| 0x706a8    | 1         | 0.45%   |
| 0x706a1    | 1         | 0.45%   |
| 0x306c3    | 1         | 0.45%   |
| 0x20652    | 1         | 0.45%   |
| 0x0a404102 | 1         | 0.45%   |
| 0x08608103 | 1         | 0.45%   |
| 0x08600106 | 1         | 0.45%   |
| 0x08600104 | 1         | 0.45%   |
| 0x08108109 | 1         | 0.45%   |
| 0x06003106 | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 83        | 37.56%  |
| Skylake           | 17        | 7.69%   |
| Alderlake Hybrid  | 17        | 7.69%   |
| CometLake         | 16        | 7.24%   |
| TigerLake         | 11        | 4.98%   |
| Unknown           | 11        | 4.98%   |
| Icelake           | 10        | 4.52%   |
| SandyBridge       | 9         | 4.07%   |
| IvyBridge         | 9         | 4.07%   |
| Westmere          | 6         | 2.71%   |
| Haswell           | 6         | 2.71%   |
| Broadwell         | 6         | 2.71%   |
| Zen+              | 5         | 2.26%   |
| Zen 2             | 4         | 1.81%   |
| Zen 3             | 3         | 1.36%   |
| Goldmont plus     | 3         | 1.36%   |
| Meteorlake Hybrid | 2         | 0.9%    |
| Tremont           | 1         | 0.45%   |
| Steamroller       | 1         | 0.45%   |
| Gracemont         | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 182       | 65%     |
| Nvidia | 67        | 23.93%  |
| AMD    | 31        | 11.07%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                                      | 19        | 6.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 18        | 6.41%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 18        | 6.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 14        | 4.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 12        | 4.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 11        | 3.91%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 9         | 3.2%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 8         | 2.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 7         | 2.49%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 6         | 2.14%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 6         | 2.14%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 6         | 2.14%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 5         | 1.78%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 5         | 1.78%   |
| Intel Core Processor Integrated Graphics Controller                       | 5         | 1.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 1.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 4         | 1.42%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 4         | 1.42%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                     | 4         | 1.42%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 4         | 1.42%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                     | 4         | 1.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 1.42%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 4         | 1.42%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.07%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 3         | 1.07%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                   | 3         | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.07%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 3         | 1.07%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 2         | 0.71%   |
| Nvidia GP107GLM [Quadro P620]                                             | 2         | 0.71%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 2         | 0.71%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 2         | 0.71%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 2         | 0.71%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 0.71%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                        | 2         | 0.71%   |
| Nvidia AD107GLM [RTX 2000 Ada Generation Laptop GPU]                      | 2         | 0.71%   |
| Intel Raptor Lake-S UHD Graphics                                          | 2         | 0.71%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                  | 2         | 0.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 0.71%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 2         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 127       | 57.47%  |
| Intel + Nvidia | 45        | 20.36%  |
| 1 x Nvidia     | 18        | 8.14%   |
| 1 x AMD        | 16        | 7.24%   |
| Intel + AMD    | 9         | 4.07%   |
| AMD + Nvidia   | 5         | 2.26%   |
| 2 x AMD        | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 193       | 86.55%  |
| Proprietary | 21        | 9.42%   |
| Unknown     | 9         | 4.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 160       | 72.07%  |
| 1.01-2.0   | 16        | 7.21%   |
| 3.01-4.0   | 15        | 6.76%   |
| 5.01-6.0   | 10        | 4.5%    |
| 0.51-1.0   | 9         | 4.05%   |
| 0.01-0.5   | 6         | 2.7%    |
| 7.01-8.0   | 3         | 1.35%   |
| 2.01-3.0   | 1         | 0.45%   |
| 16.01-24.0 | 1         | 0.45%   |
| 8.01-16.0  | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 17.29%  |
| BOE                     | 44        | 14.92%  |
| LG Display              | 32        | 10.85%  |
| Chimei Innolux          | 32        | 10.85%  |
| Samsung Electronics     | 23        | 7.8%    |
| Dell                    | 22        | 7.46%   |
| Lenovo                  | 16        | 5.42%   |
| Sharp                   | 9         | 3.05%   |
| Hewlett-Packard         | 8         | 2.71%   |
| Goldstar                | 7         | 2.37%   |
| InfoVision              | 6         | 2.03%   |
| CSO                     | 6         | 2.03%   |
| PANDA                   | 4         | 1.36%   |
| Acer                    | 4         | 1.36%   |
| Philips                 | 3         | 1.02%   |
| AOC                     | 3         | 1.02%   |
| ___                     | 2         | 0.68%   |
| Vizio                   | 2         | 0.68%   |
| Unknown                 | 2         | 0.68%   |
| Sceptre Tech            | 2         | 0.68%   |
| LGD                     | 2         | 0.68%   |
| BOE Technology Group    | 2         | 0.68%   |
| Unknown (XXX)           | 1         | 0.34%   |
| Sun                     | 1         | 0.34%   |
| Planar                  | 1         | 0.34%   |
| KDB                     | 1         | 0.34%   |
| ITE                     | 1         | 0.34%   |
| Gigabyte Technology     | 1         | 0.34%   |
| Eizo                    | 1         | 0.34%   |
| CTO                     | 1         | 0.34%   |
| CSW                     | 1         | 0.34%   |
| CSOT                    | 1         | 0.34%   |
| Chi Mei Optoelectronics | 1         | 0.34%   |
| CEX                     | 1         | 0.34%   |
| ASUSTek Computer        | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 7         | 2.27%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 5         | 1.62%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 5         | 1.62%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 5         | 1.62%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 5         | 1.62%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                    | 4         | 1.3%    |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 4         | 1.3%    |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch         | 3         | 0.97%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 3         | 0.97%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch       | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.97%   |
| ___ LCD TV ___9000 1360x768                                          | 2         | 0.65%   |
| Vizio E500i-B1 VIZ1004 1920x1080 1095x616mm 49.5-inch                | 2         | 0.65%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                    | 2         | 0.65%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 2         | 0.65%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch              | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 2         | 0.65%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2         | 0.65%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch              | 2         | 0.65%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.65%   |
| LGD LCD Monitor 1920x1080                                            | 2         | 0.65%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch          | 2         | 0.65%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch           | 2         | 0.65%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 2         | 0.65%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch           | 2         | 0.65%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch     | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch     | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch     | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.65%   |
| BOE LCD Monitor BOE08DE 3840x2160 382x215mm 17.3-inch                | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO6A9F 2560x1600 344x215mm 16.0-inch       | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch       | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO4999 1920x1080 344x193mm 15.5-inch       | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch        | 2         | 0.65%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch       | 1         | 0.32%   |
| Sun LCD Monitor SUN059A 1920x1080 518x324mm 24.1-inch                | 1         | 0.32%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch              | 1         | 0.32%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 139       | 54.51%  |
| 1366x768 (WXGA)    | 32        | 12.55%  |
| 1920x1200 (WUXGA)  | 17        | 6.67%   |
| 3840x2160 (4K)     | 15        | 5.88%   |
| 2560x1440 (QHD)    | 11        | 4.31%   |
| 1600x900 (HD+)     | 8         | 3.14%   |
| 2560x1600          | 6         | 2.35%   |
| 3440x1440          | 4         | 1.57%   |
| 3840x2400          | 3         | 1.18%   |
| 2560x1080          | 3         | 1.18%   |
| 2880x1800          | 2         | 0.78%   |
| 1680x1050 (WSXGA+) | 2         | 0.78%   |
| 1360x768           | 2         | 0.78%   |
| Unknown            | 2         | 0.78%   |
| 6400x2160          | 1         | 0.39%   |
| 5120x1440          | 1         | 0.39%   |
| 3840x1080          | 1         | 0.39%   |
| 3200x1800 (QHD+)   | 1         | 0.39%   |
| 2240x1400          | 1         | 0.39%   |
| 2160x1350          | 1         | 0.39%   |
| 2048x1152          | 1         | 0.39%   |
| 1440x900 (WXGA+)   | 1         | 0.39%   |
| 1280x800 (WXGA)    | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 77        | 26.19%  |
| 14      | 53        | 18.03%  |
| 13      | 44        | 14.97%  |
| 24      | 24        | 8.16%   |
| 27      | 18        | 6.12%   |
| 23      | 13        | 4.42%   |
| 16      | 11        | 3.74%   |
| 17      | 8         | 2.72%   |
| Unknown | 7         | 2.38%   |
| 34      | 6         | 2.04%   |
| 21      | 6         | 2.04%   |
| 12      | 6         | 2.04%   |
| 31      | 4         | 1.36%   |
| 72      | 3         | 1.02%   |
| 54      | 3         | 1.02%   |
| 18      | 3         | 1.02%   |
| 22      | 2         | 0.68%   |
| 11      | 2         | 0.68%   |
| 49      | 1         | 0.34%   |
| 35      | 1         | 0.34%   |
| 32      | 1         | 0.34%   |
| 19      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 171       | 59.17%  |
| 501-600     | 47        | 16.26%  |
| 201-300     | 22        | 7.61%   |
| 401-500     | 11        | 3.81%   |
| 351-400     | 9         | 3.11%   |
| 701-800     | 7         | 2.42%   |
| 601-700     | 7         | 2.42%   |
| Unknown     | 7         | 2.42%   |
| 1001-1500   | 4         | 1.38%   |
| 1501-2000   | 3         | 1.04%   |
| 801-900     | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 183       | 78.21%  |
| 16/10   | 37        | 15.81%  |
| 21/9    | 7         | 2.99%   |
| Unknown | 5         | 2.14%   |
| 32/9    | 1         | 0.43%   |
| 3/2     | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 84        | 28.77%  |
| 101-110        | 75        | 25.68%  |
| 201-250        | 35        | 11.99%  |
| 301-350        | 18        | 6.16%   |
| 71-80          | 13        | 4.45%   |
| 111-120        | 12        | 4.11%   |
| 351-500        | 11        | 3.77%   |
| 251-300        | 8         | 2.74%   |
| 121-130        | 8         | 2.74%   |
| Unknown        | 7         | 2.4%    |
| More than 1000 | 6         | 2.05%   |
| 61-70          | 6         | 2.05%   |
| 141-150        | 3         | 1.03%   |
| 51-60          | 2         | 0.68%   |
| 151-200        | 2         | 0.68%   |
| 501-1000       | 1         | 0.34%   |
| 91-100         | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 135       | 47.7%   |
| 51-100        | 50        | 17.67%  |
| 101-120       | 44        | 15.55%  |
| 161-240       | 27        | 9.54%   |
| More than 240 | 15        | 5.3%    |
| Unknown       | 7         | 2.47%   |
| 1-50          | 5         | 1.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 146       | 63.2%   |
| 2     | 58        | 25.11%  |
| 3     | 15        | 6.49%   |
| 0     | 10        | 4.33%   |
| 5     | 1         | 0.43%   |
| 4     | 1         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 183       | 53.98%  |
| Realtek Semiconductor             | 75        | 22.12%  |
| Lenovo                            | 18        | 5.31%   |
| Qualcomm Atheros                  | 16        | 4.72%   |
| MediaTek                          | 6         | 1.77%   |
| Sierra Wireless                   | 3         | 0.88%   |
| DisplayLink                       | 3         | 0.88%   |
| Broadcom Limited                  | 3         | 0.88%   |
| Broadcom                          | 3         | 0.88%   |
| Shenzhen Goodix Technology        | 2         | 0.59%   |
| Qualcomm                          | 2         | 0.59%   |
| OPPO Electronics                  | 2         | 0.59%   |
| Marvell Technology Group          | 2         | 0.59%   |
| HMD Global                        | 2         | 0.59%   |
| Ericsson Business Mobile Networks | 2         | 0.59%   |
| Dell                              | 2         | 0.59%   |
| ASIX Electronics                  | 2         | 0.59%   |
| Xiaomi                            | 1         | 0.29%   |
| TP-Link                           | 1         | 0.29%   |
| Samsung Electronics               | 1         | 0.29%   |
| Ralink Technology                 | 1         | 0.29%   |
| Ralink                            | 1         | 0.29%   |
| Quectel Wireless Solutions        | 1         | 0.29%   |
| Qualcomm Technologies             | 1         | 0.29%   |
| Qualcomm Atheros Communications   | 1         | 0.29%   |
| Luminary Micro                    | 1         | 0.29%   |
| ICS Advent                        | 1         | 0.29%   |
| Huawei Technologies               | 1         | 0.29%   |
| Google                            | 1         | 0.29%   |
| Aquantia                          | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 35        | 7.66%   |
| Intel Wireless 8265 / 8275                                             | 22        | 4.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 20        | 4.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 18        | 3.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 16        | 3.5%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 15        | 3.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14        | 3.06%   |
| Intel Ethernet Connection (6) I219-LM                                  | 12        | 2.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 2.63%   |
| Intel Wireless 8260                                                    | 11        | 2.41%   |
| Intel Wi-Fi 6 AX201                                                    | 10        | 2.19%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 2.19%   |
| Intel Ethernet Connection (7) I219-LM                                  | 10        | 2.19%   |
| Intel Ethernet Connection (10) I219-LM                                 | 10        | 2.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 10        | 2.19%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 9         | 1.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 1.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 7         | 1.53%   |
| Intel Wireless 7265                                                    | 6         | 1.31%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6         | 1.31%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 6         | 1.31%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                  | 5         | 1.09%   |
| Intel Ethernet Connection (13) I219-LM                                 | 5         | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 0.88%   |
| Intel Wireless 3165                                                    | 4         | 0.88%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 0.88%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                                   | 4         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.88%   |
| Intel Ethernet Connection (11) I219-LM                                 | 4         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                                  | 4         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                         | 4         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 0.66%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 3         | 0.66%   |
| Lenovo Lenovo USB-C to LAN                                             | 3         | 0.66%   |
| Shenzhen Goodix Fingerprint Reader                                     | 2         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 167       | 75.91%  |
| Realtek Semiconductor           | 15        | 6.82%   |
| Qualcomm Atheros                | 14        | 6.36%   |
| MediaTek                        | 6         | 2.73%   |
| Sierra Wireless                 | 3         | 1.36%   |
| Broadcom                        | 3         | 1.36%   |
| Qualcomm                        | 2         | 0.91%   |
| Dell                            | 2         | 0.91%   |
| Broadcom Limited                | 2         | 0.91%   |
| TP-Link                         | 1         | 0.45%   |
| Ralink Technology               | 1         | 0.45%   |
| Ralink                          | 1         | 0.45%   |
| Quectel Wireless Solutions      | 1         | 0.45%   |
| Qualcomm Technologies           | 1         | 0.45%   |
| Qualcomm Atheros Communications | 1         | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 22        | 10%     |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 18        | 8.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 16        | 7.27%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 15        | 6.82%   |
| Intel Wireless 8260                                                  | 11        | 5%      |
| Intel Wi-Fi 6 AX201                                                  | 10        | 4.55%   |
| Intel Wi-Fi 6 AX200                                                  | 10        | 4.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 10        | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 3.18%   |
| Intel Wireless 7265                                                  | 6         | 2.73%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 6         | 2.73%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 6         | 2.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 4         | 1.82%   |
| Intel Wireless 3165                                                  | 4         | 1.82%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 4         | 1.82%   |
| Intel Centrino Ultimate-N 6300                                       | 4         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 1.36%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 3         | 1.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 1.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 0.91%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 2         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2         | 0.91%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 2         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 0.91%   |
| Intel Wireless 7260                                                  | 2         | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 2         | 0.91%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2         | 0.91%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 2         | 0.91%   |
| Dell DW5811e Snapdragon X7 LTE                                       | 2         | 0.91%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 1         | 0.45%   |
| Sierra Wireless Sierra Wireless EM7511 Qualcomm Snapdragon X16 LTE-A | 1         | 0.45%   |
| Sierra Wireless EM7455                                               | 1         | 0.45%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                      | 1         | 0.45%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 1         | 0.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1         | 0.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 0.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 121       | 53.54%  |
| Realtek Semiconductor    | 67        | 29.65%  |
| Lenovo                   | 18        | 7.96%   |
| DisplayLink              | 3         | 1.33%   |
| Qualcomm Atheros         | 2         | 0.88%   |
| OPPO Electronics         | 2         | 0.88%   |
| Marvell Technology Group | 2         | 0.88%   |
| HMD Global               | 2         | 0.88%   |
| ASIX Electronics         | 2         | 0.88%   |
| Xiaomi                   | 1         | 0.44%   |
| Samsung Electronics      | 1         | 0.44%   |
| ICS Advent               | 1         | 0.44%   |
| Huawei Technologies      | 1         | 0.44%   |
| Google                   | 1         | 0.44%   |
| Broadcom Limited         | 1         | 0.44%   |
| Aquantia                 | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 35        | 15.09%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 20        | 8.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 14        | 6.03%   |
| Intel Ethernet Connection (6) I219-LM                                          | 12        | 5.17%   |
| Intel Ethernet Connection (4) I219-LM                                          | 12        | 5.17%   |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 4.31%   |
| Intel Ethernet Connection (10) I219-LM                                         | 10        | 4.31%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 9         | 3.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 3.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 6         | 2.59%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 2.16%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 2.16%   |
| Intel Ethernet Connection (13) I219-LM                                         | 5         | 2.16%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.72%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 1.72%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 1.72%   |
| Intel Ethernet Connection (11) I219-LM                                         | 4         | 1.72%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.29%   |
| Lenovo Lenovo USB-C to LAN                                                     | 3         | 1.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.86%   |
| OPPO Ace 3V                                                                    | 2         | 0.86%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.86%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.86%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.86%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.86%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.86%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.86%   |
| Intel Ethernet Connection (23) I219-LM                                         | 2         | 0.86%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 0.86%   |
| HMD Global Nokia7.2                                                            | 2         | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.43%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.43%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.43%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.43%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 211       | 52.1%   |
| Ethernet | 189       | 46.67%  |
| Modem    | 5         | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 159       | 66.81%  |
| Ethernet | 79        | 33.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 162       | 73.64%  |
| 1     | 55        | 25%     |
| 3     | 2         | 0.91%   |
| 4     | 1         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 182       | 81.61%  |
| Yes  | 41        | 18.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 137       | 74.86%  |
| Broadcom                        | 10        | 5.46%   |
| Qualcomm Atheros Communications | 9         | 4.92%   |
| Realtek Semiconductor           | 8         | 4.37%   |
| Foxconn / Hon Hai               | 6         | 3.28%   |
| IMC Networks                    | 4         | 2.19%   |
| USI                             | 2         | 1.09%   |
| Cambridge Silicon Radio         | 2         | 1.09%   |
| Ralink                          | 1         | 0.55%   |
| MediaTek                        | 1         | 0.55%   |
| Lite-On Technology              | 1         | 0.55%   |
| Dell                            | 1         | 0.55%   |
| ASUSTek Computer                | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 46        | 25.14%  |
| Intel Bluetooth wireless interface                                                  | 32        | 17.49%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 24        | 13.11%  |
| Intel Bluetooth Device                                                              | 16        | 8.74%   |
| Intel AX200 Bluetooth                                                               | 10        | 5.46%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 3.83%   |
| Realtek Bluetooth Radio                                                             | 5         | 2.73%   |
| Intel AX210 Bluetooth                                                               | 5         | 2.73%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.19%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.64%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 1.64%   |
| USI Bluetooth Device                                                                | 2         | 1.09%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 1.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.09%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.09%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.55%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.55%   |
| MediaTek Wireless_Device                                                            | 1         | 0.55%   |
| Lite-On Wireless_Device                                                             | 1         | 0.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.55%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.55%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.55%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.55%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.55%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.55%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.55%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.55%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.55%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 201       | 60.91%  |
| Nvidia                   | 44        | 13.33%  |
| AMD                      | 25        | 7.58%   |
| Lenovo                   | 16        | 4.85%   |
| Realtek Semiconductor    | 8         | 2.42%   |
| GN Netcom                | 6         | 1.82%   |
| Texas Instruments        | 4         | 1.21%   |
| Plantronics              | 4         | 1.21%   |
| JMTek                    | 2         | 0.61%   |
| Hewlett-Packard          | 2         | 0.61%   |
| Generalplus Technology   | 2         | 0.61%   |
| Corsair                  | 2         | 0.61%   |
| C-Media Electronics      | 2         | 0.61%   |
| SteelSeries ApS          | 1         | 0.3%    |
| Sony                     | 1         | 0.3%    |
| Nordic Semiconductor ASA | 1         | 0.3%    |
| Logitech                 | 1         | 0.3%    |
| LG Electronics           | 1         | 0.3%    |
| Harman                   | 1         | 0.3%    |
| Google                   | 1         | 0.3%    |
| Focusrite-Novation       | 1         | 0.3%    |
| DSEA A/S                 | 1         | 0.3%    |
| Dell                     | 1         | 0.3%    |
| Blue Microphones         | 1         | 0.3%    |
| BEHRINGER International  | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 32        | 8.99%   |
| Intel Comet Lake PCH-LP cAVS                                               | 19        | 5.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 5.34%   |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 5.06%   |
| AMD Ryzen HD Audio Controller                                              | 18        | 5.06%   |
| Intel Comet Lake PCH cAVS                                                  | 16        | 4.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 3.09%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 2.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 2.81%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 9         | 2.53%   |
| Realtek Semiconductor USB Audio                                            | 8         | 2.25%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.97%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 7         | 1.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 1.69%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 1.69%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.4%    |
| Nvidia GA107 High Definition Audio Controller                              | 5         | 1.4%    |
| Intel CM238 HD Audio Controller                                            | 5         | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.12%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.12%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.12%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3         | 0.84%   |
| Plantronics BT600                                                          | 3         | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.84%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.84%   |
| AMD Radeon High Definition Audio Controller                                | 3         | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.56%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.56%   |
| Nvidia AD107 High Definition Audio Controller                              | 2         | 0.56%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 2         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 32.95%  |
| SK hynix            | 23        | 26.14%  |
| Kingston            | 8         | 9.09%   |
| Micron Technology   | 6         | 6.82%   |
| Crucial             | 6         | 6.82%   |
| Unknown             | 3         | 3.41%   |
| Transcend           | 2         | 2.27%   |
| Smart               | 2         | 2.27%   |
| Elpida              | 2         | 2.27%   |
| Unknown             | 2         | 2.27%   |
| Unknown (0x0B5E)    | 1         | 1.14%   |
| Team                | 1         | 1.14%   |
| Nanya Technology    | 1         | 1.14%   |
| Innodisk            | 1         | 1.14%   |
| GOODRAM             | 1         | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 5         | 5.43%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 3         | 3.26%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 3         | 3.26%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 2.17%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 2         | 2.17%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 2.17%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 2.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s          | 2         | 2.17%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s           | 2         | 2.17%   |
| Crucial RAM CT16G4SFRA32A.M8FF 16GB SODIMM DDR4 3200MT/s        | 2         | 2.17%   |
| Unknown                                                         | 2         | 2.17%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 1.09%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.09%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                       | 1         | 1.09%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 1.09%   |
| Transcend RAM TS4GLH64V2E-I 32GB SODIMM DDR4 3200MT/s           | 1         | 1.09%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s           | 1         | 1.09%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s           | 1         | 1.09%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s           | 1         | 1.09%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 1.09%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.09%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.09%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.09%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.09%   |
| SK hynix RAM HMCG88AGBSA095N 32GB SODIMM DDR5 5600MT/s          | 1         | 1.09%   |
| SK hynix RAM HMCG78AGBSA095N 16GB SODIMM DDR5 5600MT/s          | 1         | 1.09%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s          | 1         | 1.09%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.09%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s         | 1         | 1.09%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.09%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 1.09%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.09%   |
| SK hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.09%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.09%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.09%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 1.09%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.09%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s          | 1         | 1.09%   |
| SK hynix RAM H5AN8G6NDJR-XNC 4GB Row Of Chips DDR4 2400MT/s     | 1         | 1.09%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 64.79%  |
| DDR3   | 15        | 21.13%  |
| LPDDR5 | 4         | 5.63%   |
| DDR5   | 4         | 5.63%   |
| LPDDR4 | 1         | 1.41%   |
| LPDDR3 | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 64        | 90.14%  |
| Row Of Chips    | 5         | 7.04%   |
| Proprietary Car | 1         | 1.41%   |
| Chip            | 1         | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 25        | 32.89%  |
| 8192  | 23        | 30.26%  |
| 4096  | 15        | 19.74%  |
| 32768 | 12        | 15.79%  |
| 2048  | 1         | 1.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 24        | 31.17%  |
| 2667  | 15        | 19.48%  |
| 1600  | 13        | 16.88%  |
| 2400  | 6         | 7.79%   |
| 2133  | 6         | 7.79%   |
| 5600  | 3         | 3.9%    |
| 1333  | 3         | 3.9%    |
| 6400  | 2         | 2.6%    |
| 8400  | 1         | 1.3%    |
| 7500  | 1         | 1.3%    |
| 7467  | 1         | 1.3%    |
| 4800  | 1         | 1.3%    |
| 2933  | 1         | 1.3%    |

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
| Chicony Electronics                    | 59        | 26.82%  |
| IMC Networks                           | 30        | 13.64%  |
| Bison Electronics                      | 21        | 9.55%   |
| Realtek Semiconductor                  | 17        | 7.73%   |
| Sunplus Innovation Technology          | 16        | 7.27%   |
| Microdia                               | 16        | 7.27%   |
| Luxvisions Innotech Limited            | 9         | 4.09%   |
| Logitech                               | 8         | 3.64%   |
| Lite-On Technology                     | 8         | 3.64%   |
| Syntek                                 | 4         | 1.82%   |
| Suyin                                  | 4         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 1.82%   |
| Samsung Electronics                    | 3         | 1.36%   |
| Quanta                                 | 3         | 1.36%   |
| Shinetech                              | 2         | 0.91%   |
| Microsoft                              | 2         | 0.91%   |
| Acer                                   | 2         | 0.91%   |
| Sonix Technology                       | 1         | 0.45%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.45%   |
| Ruision                                | 1         | 0.45%   |
| Remo Tech                              | 1         | 0.45%   |
| LG Electronics                         | 1         | 0.45%   |
| Lenovo                                 | 1         | 0.45%   |
| KYE Systems (Mouse Systems)            | 1         | 0.45%   |
| icSpring                               | 1         | 0.45%   |
| Hopewin Electronic Material            | 1         | 0.45%   |
| Creative Technology                    | 1         | 0.45%   |
| Apple                                  | 1         | 0.45%   |
| Alcor Micro                            | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 27        | 12.11%  |
| IMC Networks Integrated Camera                    | 24        | 10.76%  |
| Realtek Integrated_Webcam_HD                      | 10        | 4.48%   |
| Bison Integrated Camera                           | 9         | 4.04%   |
| Sunplus Integrated_Webcam_HD                      | 8         | 3.59%   |
| Microdia Integrated_Webcam_HD                     | 6         | 2.69%   |
| Lite-On Integrated Camera                         | 6         | 2.69%   |
| Chicony HP HD Camera                              | 6         | 2.69%   |
| Logitech HD Pro Webcam C920                       | 5         | 2.24%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 5         | 2.24%   |
| Chicony Integrated Camera (1280x720@30)           | 5         | 2.24%   |
| Bison SunplusIT Integrated Camera                 | 5         | 2.24%   |
| Chicony ThinkPad T490 Webcam                      | 4         | 1.79%   |
| Syntek Integrated Camera                          | 3         | 1.35%   |
| Sunplus Integrated Camera                         | 3         | 1.35%   |
| Samsung Galaxy series, misc. (MTP mode)           | 3         | 1.35%   |
| Microdia Integrated Webcam                        | 3         | 1.35%   |
| Luxvisions Innotech Limited Integrated Camera     | 3         | 1.35%   |
| Suyin Integrated_Webcam_HD                        | 2         | 0.9%    |
| Sunplus Laptop_Integrated_Webcam_FHD              | 2         | 0.9%    |
| Shinetech USB2.0 FHD UVC WebCam                   | 2         | 0.9%    |
| Realtek Integrated_Webcam_FHD                     | 2         | 0.9%    |
| Microdia Webcam                                   | 2         | 0.9%    |
| Luxvisions Innotech Limited Integrated RGB Camera | 2         | 0.9%    |
| Luxvisions Innotech Limited HP 5MP Camera         | 2         | 0.9%    |
| Lite-On HP HD Camera                              | 2         | 0.9%    |
| Chicony Integrated HP HD Webcam                   | 2         | 0.9%    |
| Chicony Integrated Camera [ThinkPad]              | 2         | 0.9%    |
| Chicony HP HD Webcam [Fixed]                      | 2         | 0.9%    |
| Bison Integrated IR Camera                        | 2         | 0.9%    |
| Bison HD Webcam                                   | 2         | 0.9%    |
| Acer Integrated Camera                            | 2         | 0.9%    |
| Syntek Lenovo EasyCamera                          | 1         | 0.45%   |
| Suyin RGBIR Camera                                | 1         | 0.45%   |
| Suyin HP Truevision HD                            | 1         | 0.45%   |
| Sunplus Integrated Webcam                         | 1         | 0.45%   |
| Sunplus Hy FHD B200 Came                          | 1         | 0.45%   |
| Sunplus HP HD Webcam [Fixed]                      | 1         | 0.45%   |
| Sonix USB2.0 HD UVC WebCam                        | 1         | 0.45%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera   | 1         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 51        | 63.75%  |
| Validity Sensors           | 20        | 25%     |
| Shenzhen Goodix Technology | 4         | 5%      |
| Upek                       | 2         | 2.5%    |
| Samsung Electronics        | 1         | 1.25%   |
| Elan Microelectronics      | 1         | 1.25%   |
| AuthenTec                  | 1         | 1.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 29        | 36.25%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 8.75%   |
| Synaptics UWP WBDI Device                                                  | 5         | 6.25%   |
| Synaptics Prometheus Fingerprint Reader                                    | 4         | 5%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 3.75%   |
| Validity Sensors VFS491                                                    | 3         | 3.75%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 3.75%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.75%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3.75%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 3.75%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 3.75%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.5%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.5%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.25%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.25%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.25%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.25%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.25%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 23        | 67.65%  |
| Alcor Micro | 8         | 23.53%  |
| Lenovo      | 2         | 5.88%   |
| Upek        | 1         | 2.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 8         | 23.53%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 23.53%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 14.71%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 5         | 14.71%  |
| Broadcom 58200                                                               | 4         | 11.76%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 2.94%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 100       | 44.84%  |
| 0     | 92        | 41.26%  |
| 2     | 22        | 9.87%   |
| 3     | 6         | 2.69%   |
| 5     | 2         | 0.9%    |
| 4     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 80        | 46.24%  |
| Graphics card            | 26        | 15.03%  |
| Chipcard                 | 22        | 12.72%  |
| Net/wireless             | 11        | 6.36%   |
| Multimedia controller    | 10        | 5.78%   |
| Card reader              | 7         | 4.05%   |
| Net/ethernet             | 5         | 2.89%   |
| Communication controller | 3         | 1.73%   |
| Bluetooth                | 3         | 1.73%   |
| Storage                  | 2         | 1.16%   |
| Camera                   | 2         | 1.16%   |
| Sound                    | 1         | 0.58%   |
| Firewire controller      | 1         | 0.58%   |

