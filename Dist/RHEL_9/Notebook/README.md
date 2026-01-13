RHEL 9 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for RHEL 9.

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

Total: 104

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f645e7853f](https://linux-hardware.org/?probe=f645e7853f) | Dec 14, 2025 |
| HP            | EliteBook 855 G7 Noteboo... | [372612d4cb](https://linux-hardware.org/?probe=372612d4cb) | Nov 21, 2025 |
| Dell          | Pro Max 14 MC14250          | [e284bbe318](https://linux-hardware.org/?probe=e284bbe318) | Aug 08, 2025 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [ebfb439ae8](https://linux-hardware.org/?probe=ebfb439ae8) | Jul 28, 2025 |
| HP            | EliteBook 8470p             | [699e60ab98](https://linux-hardware.org/?probe=699e60ab98) | Jul 20, 2025 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [d694fa0335](https://linux-hardware.org/?probe=d694fa0335) | Jul 13, 2025 |
| HP            | EliteBook 8470p             | [03e67e85c7](https://linux-hardware.org/?probe=03e67e85c7) | Jul 07, 2025 |
| Dell          | Precision 5490              | [862d9564ec](https://linux-hardware.org/?probe=862d9564ec) | Jun 30, 2025 |
| Dell          | Precision 5490              | [aa3fe64169](https://linux-hardware.org/?probe=aa3fe64169) | Jun 02, 2025 |
| Dell          | Precision M4800             | [f3a2c881d4](https://linux-hardware.org/?probe=f3a2c881d4) | May 29, 2025 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [f65f1d1f72](https://linux-hardware.org/?probe=f65f1d1f72) | May 20, 2025 |
| Dell          | Precision M4800             | [b31e551454](https://linux-hardware.org/?probe=b31e551454) | May 14, 2025 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | [54677dffeb](https://linux-hardware.org/?probe=54677dffeb) | Apr 04, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | [12adf7443f](https://linux-hardware.org/?probe=12adf7443f) | Apr 01, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [14d91dd406](https://linux-hardware.org/?probe=14d91dd406) | Mar 29, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8f0328cec8](https://linux-hardware.org/?probe=8f0328cec8) | Mar 29, 2025 |
| Acer          | Aspire AL14-31P             | [c1b9edd8c5](https://linux-hardware.org/?probe=c1b9edd8c5) | Mar 27, 2025 |
| Lenovo        | Legion S7 15ACH6 82K8       | [58a52af839](https://linux-hardware.org/?probe=58a52af839) | Mar 13, 2025 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | [72c5b1b57e](https://linux-hardware.org/?probe=72c5b1b57e) | Feb 22, 2025 |
| Lenovo        | ThinkPad P16v Gen 2 21KY... | [4c043a2d86](https://linux-hardware.org/?probe=4c043a2d86) | Feb 12, 2025 |
| HP            | Laptop 15-fd0xxx            | [bd083d24c2](https://linux-hardware.org/?probe=bd083d24c2) | Jan 23, 2025 |
| HP            | ProBook 4530s               | [e4dbd31493](https://linux-hardware.org/?probe=e4dbd31493) | Jan 21, 2025 |
| Dell          | Latitude 7490               | [5781936456](https://linux-hardware.org/?probe=5781936456) | Dec 31, 2024 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [ea8d4bb295](https://linux-hardware.org/?probe=ea8d4bb295) | Nov 24, 2024 |
| HP            | EliteBook 840 G5            | [3d9365dd8e](https://linux-hardware.org/?probe=3d9365dd8e) | Nov 08, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [9f24fcf5f6](https://linux-hardware.org/?probe=9f24fcf5f6) | Nov 07, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1a592a4c8c](https://linux-hardware.org/?probe=1a592a4c8c) | Oct 30, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [88c68a9636](https://linux-hardware.org/?probe=88c68a9636) | Oct 19, 2024 |
| Dell          | Latitude E6520              | [1fccf13e1b](https://linux-hardware.org/?probe=1fccf13e1b) | Oct 14, 2024 |
| UNOWHY        | Y13G010S4EI                 | [8b9768888f](https://linux-hardware.org/?probe=8b9768888f) | Sep 29, 2024 |
| UNOWHY        | Y13G010S4EI                 | [8bc1a2e515](https://linux-hardware.org/?probe=8bc1a2e515) | Sep 25, 2024 |
| Dell          | Precision 7730              | [7f0ef4c558](https://linux-hardware.org/?probe=7f0ef4c558) | Sep 19, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [325da6b558](https://linux-hardware.org/?probe=325da6b558) | Sep 16, 2024 |
| Dell          | Precision 7530              | [f24cdeec73](https://linux-hardware.org/?probe=f24cdeec73) | Aug 18, 2024 |
| Lenovo        | IdeaPad S145-15API 81UT     | [4d550f9d4c](https://linux-hardware.org/?probe=4d550f9d4c) | Jul 22, 2024 |
| Unknown       | G13                         | [ac710043ec](https://linux-hardware.org/?probe=ac710043ec) | Jul 09, 2024 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | [07807f87ab](https://linux-hardware.org/?probe=07807f87ab) | Jul 04, 2024 |
| HP            | EliteBook 855 G7 Noteboo... | [70d021b045](https://linux-hardware.org/?probe=70d021b045) | Jul 02, 2024 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [cd307f9782](https://linux-hardware.org/?probe=cd307f9782) | Jun 27, 2024 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [5f79f30b85](https://linux-hardware.org/?probe=5f79f30b85) | Jun 19, 2024 |
| Dell          | Latitude 5520               | [c1a7e532c9](https://linux-hardware.org/?probe=c1a7e532c9) | Jun 10, 2024 |
| Dell          | Latitude 3340               | [0179e77195](https://linux-hardware.org/?probe=0179e77195) | Jun 10, 2024 |
| Dell          | Latitude 3340               | [3719b02ec1](https://linux-hardware.org/?probe=3719b02ec1) | Jun 10, 2024 |
| HP            | EliteBook 860 16 inch G1... | [a2f0057f55](https://linux-hardware.org/?probe=a2f0057f55) | Jun 05, 2024 |
| HP            | EliteBook 860 16 inch G1... | [75728b162c](https://linux-hardware.org/?probe=75728b162c) | Jun 04, 2024 |
| HP            | Stream Laptop 11-ak0xxx     | [564a4d2df9](https://linux-hardware.org/?probe=564a4d2df9) | May 27, 2024 |
| Dell          | Precision 7540              | [4703617413](https://linux-hardware.org/?probe=4703617413) | May 07, 2024 |
| Dell          | Precision 7540              | [37638500df](https://linux-hardware.org/?probe=37638500df) | May 07, 2024 |
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
| Dell          | Precision 7530              | [e75b16ca5e](https://linux-hardware.org/?probe=e75b16ca5e) | Dec 03, 2023 |
| Lenovo        | ThinkPad L480 20LS0015UK    | [5f786955fc](https://linux-hardware.org/?probe=5f786955fc) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-14IKB U 81F... | [0b06f82d9d](https://linux-hardware.org/?probe=0b06f82d9d) | Nov 19, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [1c3bf8f6ef](https://linux-hardware.org/?probe=1c3bf8f6ef) | Oct 19, 2023 |
| System76      | Galago Pro                  | [fbdb665814](https://linux-hardware.org/?probe=fbdb665814) | Oct 03, 2023 |
| Dell          | Inspiron N5010              | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| Dell          | G16 7620                    | [cd30e51d53](https://linux-hardware.org/?probe=cd30e51d53) | Sep 27, 2023 |
| Dell          | Precision 7720              | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Lenovo        | ThinkPad T490 20N3S77601    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| MSI           | Katana GF66 12UC            | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| HP            | EliteBook 2570p             | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [49ecdacd71](https://linux-hardware.org/?probe=49ecdacd71) | May 14, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [5938e62d47](https://linux-hardware.org/?probe=5938e62d47) | Apr 17, 2023 |
| Dell          | Precision 7510              | [f68123c20a](https://linux-hardware.org/?probe=f68123c20a) | Apr 13, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [de656b2182](https://linux-hardware.org/?probe=de656b2182) | Apr 06, 2023 |
| HP            | ProBook 640 G2              | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Dell          | Precision 7560              | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI           | GP75 Leopard 9SD            | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Dell          | Latitude 9420               | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell          | Latitude 3410               | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| MSI           | GE72VR 7RF                  | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Dell          | Latitude E7450              | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek       | Z450LA                      | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP            | 340S G7                     | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Dell          | Precision 7510              | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Dell          | Inspiron 5559               | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Dell          | XPS 17 9710                 | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell          | XPS 17 9710                 | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Samsung       | 730QCJ/730QCR               | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Gigabyte      | AERO 15 KD                  | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.0-284.30.1.el9_2.x86_64 | 6         | 7.32%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 4         | 4.88%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 4         | 4.88%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 3         | 3.66%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 3         | 3.66%   |
| 5.14.0-503.34.1.el9_5.x86_64 | 3         | 3.66%   |
| 5.14.0-427.42.1.el9_4.x86_64 | 3         | 3.66%   |
| 5.14.0-427.22.1.el9_4.x86_64 | 3         | 3.66%   |
| 5.14.0-427.13.1.el9_4.x86_64 | 3         | 3.66%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 3         | 3.66%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 3         | 3.66%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 3         | 3.66%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 3         | 3.66%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 2         | 2.44%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 2.44%   |
| 5.14.0-427.33.1.el9_4.x86_64 | 2         | 2.44%   |
| 5.14.0-427.20.1.el9_4.x86_64 | 2         | 2.44%   |
| 5.14.0-427.18.1.el9_4.x86_64 | 2         | 2.44%   |
| 5.14.0-362.18.1.el9_3.x86_64 | 2         | 2.44%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 2         | 2.44%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 2.44%   |
| 6.7.1-1.el9.elrepo.x86_64    | 1         | 1.22%   |
| 6.5.2-1.el9.elrepo.x86_64    | 1         | 1.22%   |
| 6.14.9-1.el9.elrepo.x86_64   | 1         | 1.22%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 1.22%   |
| 5.14.0-611.13.1.el9_7.x86_64 | 1         | 1.22%   |
| 5.14.0-570.32.1.el9_6.x86_64 | 1         | 1.22%   |
| 5.14.0-570.26.1.el9_6.x86_64 | 1         | 1.22%   |
| 5.14.0-570.23.1.el9_6.x86_64 | 1         | 1.22%   |
| 5.14.0-570.17.1.el9_6.x86_64 | 1         | 1.22%   |
| 5.14.0-570.16.1.el9_6.x86_64 | 1         | 1.22%   |
| 5.14.0-503.31.1.el9_5.x86_64 | 1         | 1.22%   |
| 5.14.0-503.26.1.el9_5.x86_64 | 1         | 1.22%   |
| 5.14.0-503.23.2.el9_5.x86_64 | 1         | 1.22%   |
| 5.14.0-503.22.1.el9_5.x86_64 | 1         | 1.22%   |
| 5.14.0-503.21.1.el9_5.x86_64 | 1         | 1.22%   |
| 5.14.0-503.19.1.el9_5.x86_64 | 1         | 1.22%   |
| 5.14.0-427.40.1.el9_4.x86_64 | 1         | 1.22%   |
| 5.14.0-427.37.1.el9_4.x86_64 | 1         | 1.22%   |
| 5.14.0-427.26.1.el9_4.x86_64 | 1         | 1.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 74        | 96.1%   |
| 6.7.1   | 1         | 1.3%    |
| 6.5.2   | 1         | 1.3%    |
| 6.14.9  | 1         | 1.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 74        | 96.1%   |
| 6.7     | 1         | 1.3%    |
| 6.5     | 1         | 1.3%    |
| 6.14    | 1         | 1.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 77        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 70        | 88.61%  |
| KDE5            | 4         | 5.06%   |
| GNOME Classic   | 3         | 3.8%    |
| XFCE            | 1         | 1.27%   |
| GNOME Flashback | 1         | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 62        | 80.52%  |
| X11     | 15        | 19.48%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 50        | 64.94%  |
| GDM     | 27        | 35.06%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 55        | 71.43%  |
| en_GB | 5         | 6.49%   |
| pt_BR | 3         | 3.9%    |
| en_IN | 2         | 2.6%    |
| de_CH | 2         | 2.6%    |
| cs_CZ | 2         | 2.6%    |
| ro_RO | 1         | 1.3%    |
| pl_PL | 1         | 1.3%    |
| ko_KR | 1         | 1.3%    |
| fr_FR | 1         | 1.3%    |
| es_MX | 1         | 1.3%    |
| en_IE | 1         | 1.3%    |
| en_CA | 1         | 1.3%    |
| C     | 1         | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 71        | 92.21%  |
| BIOS | 6         | 7.79%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Xfs   | 73        | 94.81%  |
| Ext4  | 3         | 3.9%    |
| Tmpfs | 1         | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 49        | 63.64%  |
| GPT     | 27        | 35.06%  |
| MBR     | 1         | 1.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 94.81%  |
| Yes       | 4         | 5.19%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 89.61%  |
| Yes       | 8         | 10.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 35.06%  |
| Dell                | 22        | 28.57%  |
| Hewlett-Packard     | 11        | 14.29%  |
| MSI                 | 5         | 6.49%   |
| ASUSTek Computer    | 4         | 5.19%   |
| UNOWHY              | 1         | 1.3%    |
| System76            | 1         | 1.3%    |
| Samsung Electronics | 1         | 1.3%    |
| Razer               | 1         | 1.3%    |
| LG Electronics      | 1         | 1.3%    |
| Gigabyte Technology | 1         | 1.3%    |
| Acer                | 1         | 1.3%    |
| Unknown             | 1         | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS        | 2         | 2.6%    |
| Dell Precision M4800                         | 2         | 2.6%    |
| UNOWHY Y13G010S4EI                           | 1         | 1.3%    |
| System76 Galago Pro                          | 1         | 1.3%    |
| Samsung 730QCJ/730QCR                        | 1         | 1.3%    |
| Razer Blade 15 Mid 2019-Base                 | 1         | 1.3%    |
| MSI Modern 15 A5M                            | 1         | 1.3%    |
| MSI Katana GF76 12UC                         | 1         | 1.3%    |
| MSI Katana GF66 12UC                         | 1         | 1.3%    |
| MSI GP75 Leopard 9SD                         | 1         | 1.3%    |
| MSI GE72VR 7RF                               | 1         | 1.3%    |
| LG 15Z95P-GRLGL                              | 1         | 1.3%    |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US     | 1         | 1.3%    |
| Lenovo ThinkPad X1 Extreme Gen 5 21DFS08200  | 1         | 1.3%    |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5S08300 | 1         | 1.3%    |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMS1V900  | 1         | 1.3%    |
| Lenovo ThinkPad X1 Carbon Gen 10 21CCS4LT00  | 1         | 1.3%    |
| Lenovo ThinkPad T490 20N3S77601              | 1         | 1.3%    |
| Lenovo ThinkPad T460s 20FAS1NF00             | 1         | 1.3%    |
| Lenovo ThinkPad T16 Gen 1 21CH000JUS         | 1         | 1.3%    |
| Lenovo ThinkPad T14 Gen 4 21HES0VD0H         | 1         | 1.3%    |
| Lenovo ThinkPad S1 Yoga 12 20DK001YMC        | 1         | 1.3%    |
| Lenovo ThinkPad P16v Gen 2 21KYS0LG00        | 1         | 1.3%    |
| Lenovo ThinkPad P15 Gen 1 20SUS31203         | 1         | 1.3%    |
| Lenovo ThinkPad L480 20LS0015UK              | 1         | 1.3%    |
| Lenovo ThinkPad L14 Gen 3 21C2S1EE00         | 1         | 1.3%    |
| Lenovo ThinkPad L14 Gen 2 20X2SC6400         | 1         | 1.3%    |
| Lenovo ThinkPad Edge E431 62771L7            | 1         | 1.3%    |
| Lenovo ThinkPad E14 20RA001MMZ               | 1         | 1.3%    |
| Lenovo ThinkBook 14-IIL 20SL                 | 1         | 1.3%    |
| Lenovo ThinkBook 13x G2 IAP 21AT             | 1         | 1.3%    |
| Lenovo ThinkBook 13s-IWL 20R9                | 1         | 1.3%    |
| Lenovo Legion Y540-15IRH-PG0 81SY            | 1         | 1.3%    |
| Lenovo IdeaPad S145-15API 81UT               | 1         | 1.3%    |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1          | 1         | 1.3%    |
| Lenovo IdeaPad 330S-14IKB U 81F4             | 1         | 1.3%    |
| Lenovo IdeaPad 320-15IKB 80XL                | 1         | 1.3%    |
| HP Stream Laptop 11-ak0xxx                   | 1         | 1.3%    |
| HP ProBook 640 G2                            | 1         | 1.3%    |
| HP ProBook 4530s                             | 1         | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 19        | 24.68%  |
| Dell Precision     | 10        | 12.99%  |
| Dell Latitude      | 6         | 7.79%   |
| HP EliteBook       | 5         | 6.49%   |
| Lenovo IdeaPad     | 4         | 5.19%   |
| Lenovo ThinkBook   | 3         | 3.9%    |
| Dell Inspiron      | 3         | 3.9%    |
| MSI Katana         | 2         | 2.6%    |
| HP ProBook         | 2         | 2.6%    |
| HP Laptop          | 2         | 2.6%    |
| UNOWHY Y13G010S4EI | 1         | 1.3%    |
| System76 Galago    | 1         | 1.3%    |
| Samsung 730QCJ     | 1         | 1.3%    |
| Razer Blade        | 1         | 1.3%    |
| MSI Modern         | 1         | 1.3%    |
| MSI GP75           | 1         | 1.3%    |
| MSI GE72VR         | 1         | 1.3%    |
| LG 15Z95P-GRLGL    | 1         | 1.3%    |
| Lenovo Legion      | 1         | 1.3%    |
| HP Stream          | 1         | 1.3%    |
| HP 340S            | 1         | 1.3%    |
| Gigabyte AERO      | 1         | 1.3%    |
| Dell XPS           | 1         | 1.3%    |
| Dell Pro           | 1         | 1.3%    |
| Dell G16           | 1         | 1.3%    |
| ASUS Z450LA        | 1         | 1.3%    |
| ASUS VivoBook      | 1         | 1.3%    |
| ASUS TUF           | 1         | 1.3%    |
| ASUS ASUS          | 1         | 1.3%    |
| Acer Aspire        | 1         | 1.3%    |
| Unknown            | 1         | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 14        | 18.18%  |
| 2021 | 12        | 15.58%  |
| 2020 | 9         | 11.69%  |
| 2023 | 7         | 9.09%   |
| 2022 | 6         | 7.79%   |
| 2011 | 5         | 6.49%   |
| 2018 | 4         | 5.19%   |
| 2014 | 4         | 5.19%   |
| 2016 | 3         | 3.9%    |
| 2015 | 3         | 3.9%    |
| 2013 | 3         | 3.9%    |
| 2024 | 2         | 2.6%    |
| 2017 | 2         | 2.6%    |
| 2025 | 1         | 1.3%    |
| 2012 | 1         | 1.3%    |
| 2010 | 1         | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 77        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 59        | 75.64%  |
| Enabled  | 19        | 24.36%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 98.7%   |
| Yes  | 1         | 1.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 27        | 35.06%  |
| 4.01-8.0    | 17        | 22.08%  |
| 32.01-64.0  | 12        | 15.58%  |
| 64.01-256.0 | 9         | 11.69%  |
| 3.01-4.0    | 6         | 7.79%   |
| 24.01-32.0  | 3         | 3.9%    |
| 16.01-24.0  | 3         | 3.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 31        | 38.27%  |
| 2.01-3.0   | 21        | 25.93%  |
| 3.01-4.0   | 16        | 19.75%  |
| 8.01-16.0  | 7         | 8.64%   |
| 1.01-2.0   | 3         | 3.7%    |
| 32.01-64.0 | 1         | 1.23%   |
| 24.01-32.0 | 1         | 1.23%   |
| 16.01-24.0 | 1         | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 63.29%  |
| 2      | 21        | 26.58%  |
| 3      | 7         | 8.86%   |
| 4      | 1         | 1.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 85.71%  |
| Yes       | 11        | 14.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 80.52%  |
| No        | 15        | 19.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 90.91%  |
| No        | 7         | 9.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 82.5%   |
| No        | 14        | 17.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 22        | 28.57%  |
| India       | 7         | 9.09%   |
| Brazil      | 4         | 5.19%   |
| UK          | 3         | 3.9%    |
| Switzerland | 3         | 3.9%    |
| Italy       | 3         | 3.9%    |
| Canada      | 3         | 3.9%    |
| Turkey      | 2         | 2.6%    |
| Spain       | 2         | 2.6%    |
| South Korea | 2         | 2.6%    |
| Romania     | 2         | 2.6%    |
| Mexico      | 2         | 2.6%    |
| Guatemala   | 2         | 2.6%    |
| Czechia     | 2         | 2.6%    |
| Chile       | 2         | 2.6%    |
| Vietnam     | 1         | 1.3%    |
| Sri Lanka   | 1         | 1.3%    |
| Slovakia    | 1         | 1.3%    |
| Russia      | 1         | 1.3%    |
| Poland      | 1         | 1.3%    |
| Pakistan    | 1         | 1.3%    |
| Norway      | 1         | 1.3%    |
| Netherlands | 1         | 1.3%    |
| Kenya       | 1         | 1.3%    |
| Jordan      | 1         | 1.3%    |
| Ireland     | 1         | 1.3%    |
| Indonesia   | 1         | 1.3%    |
| France      | 1         | 1.3%    |
| Finland     | 1         | 1.3%    |
| Egypt       | 1         | 1.3%    |
| Austria     | 1         | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Sao Paulo           | 2         | 2.5%    |
| Santiago            | 2         | 2.5%    |
| Jaipur              | 2         | 2.5%    |
| Guatemala City      | 2         | 2.5%    |
| Zlín               | 1         | 1.25%   |
| Whiteley            | 1         | 1.25%   |
| Vancouver           | 1         | 1.25%   |
| Valbrembo           | 1         | 1.25%   |
| Urbandale           | 1         | 1.25%   |
| Thun                | 1         | 1.25%   |
| Taunton             | 1         | 1.25%   |
| Stratham            | 1         | 1.25%   |
| Spring Hill         | 1         | 1.25%   |
| Skien               | 1         | 1.25%   |
| Seoul               | 1         | 1.25%   |
| Saint Paul          | 1         | 1.25%   |
| Râmnicu Vâlcea    | 1         | 1.25%   |
| Providence          | 1         | 1.25%   |
| Prairieville        | 1         | 1.25%   |
| Piracicaba          | 1         | 1.25%   |
| Parker              | 1         | 1.25%   |
| Omegna              | 1         | 1.25%   |
| Nuenen              | 1         | 1.25%   |
| North Shields       | 1         | 1.25%   |
| Newcastle upon Tyne | 1         | 1.25%   |
| New Delhi           | 1         | 1.25%   |
| Nairobi             | 1         | 1.25%   |
| Mountlake Terrace   | 1         | 1.25%   |
| Morlaix             | 1         | 1.25%   |
| Montgomery          | 1         | 1.25%   |
| Milano              | 1         | 1.25%   |
| Maltepe             | 1         | 1.25%   |
| Madrid              | 1         | 1.25%   |
| Lucerne             | 1         | 1.25%   |
| Liberec             | 1         | 1.25%   |
| Kolkata             | 1         | 1.25%   |
| Klosterneuburg      | 1         | 1.25%   |
| Kemerovo            | 1         | 1.25%   |
| Karachi             | 1         | 1.25%   |
| Jeonju              | 1         | 1.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 28        | 32     | 25%     |
| Sandisk                     | 10        | 13     | 8.93%   |
| Unknown                     | 8         | 8      | 7.14%   |
| Toshiba                     | 8         | 9      | 7.14%   |
| KIOXIA                      | 8         | 10     | 7.14%   |
| Seagate                     | 6         | 7      | 5.36%   |
| Micron Technology           | 6         | 6      | 5.36%   |
| SK hynix                    | 4         | 4      | 3.57%   |
| Kingston                    | 4         | 4      | 3.57%   |
| WDC                         | 3         | 3      | 2.68%   |
| Micron/Crucial Technology   | 3         | 4      | 2.68%   |
| Intel                       | 2         | 3      | 1.79%   |
| Unknown                     | 2         | 2      | 1.79%   |
| WDC WDS                     | 1         | 1      | 0.89%   |
| Union Memory                | 1         | 1      | 0.89%   |
| SSSTC                       | 1         | 1      | 0.89%   |
| Silicon Motion              | 1         | 1      | 0.89%   |
| SCY                         | 1         | 1      | 0.89%   |
| SABRENT                     | 1         | 1      | 0.89%   |
| Realtek                     | 1         | 1      | 0.89%   |
| PNY                         | 1         | 1      | 0.89%   |
| Plextor                     | 1         | 1      | 0.89%   |
| Phison                      | 1         | 1      | 0.89%   |
| LITEON                      | 1         | 1      | 0.89%   |
| Kingston Technology Company | 1         | 1      | 0.89%   |
| KingSpec                    | 1         | 1      | 0.89%   |
| Kingmax                     | 1         | 1      | 0.89%   |
| HGST                        | 1         | 1      | 0.89%   |
| GOODRAM                     | 1         | 1      | 0.89%   |
| Golden                      | 1         | 1      | 0.89%   |
| DERLAR                      | 1         | 1      | 0.89%   |
| China                       | 1         | 1      | 0.89%   |
| A-DATA Technology           | 1         | 1      | 0.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 7         | 6.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 7         | 6.09%   |
| Unknown MMC Card  64GB                             | 3         | 2.61%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 3         | 2.61%   |
| Unknown MMC Card  256GB                            | 2         | 1.74%   |
| Toshiba MQ01ABF050 500GB                           | 2         | 1.74%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 1.74%   |
| Seagate ST1000LM049-2GH172 1TB                     | 2         | 1.74%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB    | 2         | 1.74%   |
| Micron 2400_MTFDKBA512QFM 512GB                    | 2         | 1.74%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                         | 2         | 1.74%   |
| Unknown                                            | 2         | 1.74%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.87%   |
| WDC WDS 250G2B0A-00SM50 250GB SSD                  | 1         | 0.87%   |
| WDC WDBNCE5000PNC 500GB SSD                        | 1         | 0.87%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 0.87%   |
| Unknown MMC Card  512GB                            | 1         | 0.87%   |
| Unknown MMC Card  483MB                            | 1         | 0.87%   |
| Unknown MMC Card  1TB                              | 1         | 0.87%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB            | 1         | 0.87%   |
| Toshiba XG6 NVMe SSD Controller 1024GB             | 1         | 0.87%   |
| Toshiba MQ01ACF050 500GB                           | 1         | 0.87%   |
| Toshiba MQ01ACF032 320GB                           | 1         | 0.87%   |
| Toshiba MQ01ABF032 320GB                           | 1         | 0.87%   |
| Toshiba KXG50ZNV512G NVMe 512GB                    | 1         | 0.87%   |
| SSSTC CL1-3D512-Q11 NVMe 512GB                     | 1         | 0.87%   |
| SK hynix SHGP31-1000GM 1TB                         | 1         | 0.87%   |
| SK hynix PC811 SED 1024GB                          | 1         | 0.87%   |
| SK hynix NVMe SSD Drive 1024GB                     | 1         | 0.87%   |
| SK hynix HFM256GD3JX013N 256GB                     | 1         | 0.87%   |
| Silicon Motion INTENSO SSD 2TB                     | 1         | 0.87%   |
| Seagate ST500LT012-9WS142 500GB                    | 1         | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 0.87%   |
| Seagate BUP Slim BK 2TB                            | 1         | 0.87%   |
| Seagate Backup+ Hub BK 6TB                         | 1         | 0.87%   |
| SCY NVMe SSD Drive 512GB                           | 1         | 0.87%   |
| Sandisk WD_BLACK SN770 2TB                         | 1         | 0.87%   |
| Sandisk WD Blue SN570 500GB                        | 1         | 0.87%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 1         | 0.87%   |
| Sandisk WD Black SN850 1TB                         | 1         | 0.87%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 7         | 7      | 46.67%  |
| Seagate | 6         | 7      | 40%     |
| WDC     | 1         | 1      | 6.67%   |
| HGST    | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 30.43%  |
| WDC                 | 2         | 2      | 8.7%    |
| Kingston            | 2         | 2      | 8.7%    |
| WDC WDS             | 1         | 1      | 4.35%   |
| SABRENT             | 1         | 1      | 4.35%   |
| PNY                 | 1         | 1      | 4.35%   |
| Plextor             | 1         | 1      | 4.35%   |
| Micron Technology   | 1         | 1      | 4.35%   |
| LITEON              | 1         | 1      | 4.35%   |
| KingSpec            | 1         | 1      | 4.35%   |
| Kingmax             | 1         | 1      | 4.35%   |
| Intel               | 1         | 2      | 4.35%   |
| GOODRAM             | 1         | 1      | 4.35%   |
| DERLAR              | 1         | 1      | 4.35%   |
| China               | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 58        | 74     | 57.43%  |
| SSD     | 19        | 24     | 18.81%  |
| HDD     | 15        | 16     | 14.85%  |
| MMC     | 8         | 10     | 7.92%   |
| Unknown | 1         | 1      | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 57        | 73     | 57.58%  |
| SATA | 28        | 35     | 28.28%  |
| MMC  | 8         | 10     | 8.08%   |
| SAS  | 6         | 7      | 6.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 20     | 48.57%  |
| 0.51-1.0   | 15        | 16     | 42.86%  |
| 3.01-4.0   | 1         | 1      | 2.86%   |
| 1.01-2.0   | 1         | 1      | 2.86%   |
| 4.01-10.0  | 1         | 2      | 2.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 29.11%  |
| 501-1000       | 19        | 24.05%  |
| 251-500        | 14        | 17.72%  |
| 1001-2000      | 11        | 13.92%  |
| 51-100         | 4         | 5.06%   |
| 21-50          | 3         | 3.8%    |
| 2001-3000      | 2         | 2.53%   |
| More than 3000 | 1         | 1.27%   |
| 1-20           | 1         | 1.27%   |
| Unknown        | 1         | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 26        | 32.1%   |
| 21-50     | 21        | 25.93%  |
| 51-100    | 11        | 13.58%  |
| 251-500   | 8         | 9.88%   |
| 101-250   | 8         | 9.88%   |
| 1001-2000 | 3         | 3.7%    |
| 501-1000  | 3         | 3.7%    |
| Unknown   | 1         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 25%     |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 25%     |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 1         | 1      | 25%     |
| Intel SSDSC2BA800G4R 800GB                     | 1         | 2      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 2         | 2      | 50%     |
| Micron/Crucial Technology | 1         | 1      | 25%     |
| Intel                     | 1         | 2      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 50%     |
| NVMe | 1         | 1      | 25%     |
| SSD  | 1         | 2      | 25%     |

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
| Detected | 55        | 87     | 66.27%  |
| Works    | 24        | 33     | 28.92%  |
| Malfunc  | 4         | 5      | 4.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 44        | 41.9%   |
| Samsung Electronics              | 21        | 20%     |
| SanDisk                          | 10        | 9.52%   |
| KIOXIA                           | 8         | 7.62%   |
| Micron Technology                | 5         | 4.76%   |
| SK hynix                         | 4         | 3.81%   |
| Micron/Crucial Technology        | 3         | 2.86%   |
| Kingston Technology Company      | 3         | 2.86%   |
| Union Memory (Shenzhen)          | 1         | 0.95%   |
| Toshiba America Info Systems     | 1         | 0.95%   |
| Silicon Motion                   | 1         | 0.95%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.95%   |
| Phison Electronics               | 1         | 0.95%   |
| AMD                              | 1         | 0.95%   |
| ADATA Technology                 | 1         | 0.95%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 7.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 6.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 5.5%    |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 5         | 4.59%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 3.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 3.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.67%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 2.75%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 2.75%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 3         | 2.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.75%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 2.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 2.75%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.83%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 1.83%   |
| KIOXIA NVMe SSD Controller XG8                                                 | 2         | 1.83%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 2         | 1.83%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.83%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 1.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.83%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 0.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.92%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.92%   |
| SK hynix PC811 NVMe Solid State Drive                                          | 1         | 0.92%   |
| Silicon Motion SM2268XT (DRAM-less) NVMe SSD Controller                        | 1         | 0.92%   |
| Shenzhen Shichuangyi MAP1202-Based NVMe SSD (DRAM-less)                        | 1         | 0.92%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 1         | 0.92%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 1         | 0.92%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 0.92%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 1         | 0.92%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1         | 0.92%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 1         | 0.92%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.92%   |
| Micron/Crucial P510 NVMe PCIe SSD (DRAM-less)                                  | 1         | 0.92%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.92%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1         | 0.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 56        | 54.9%   |
| SATA | 36        | 35.29%  |
| RAID | 10        | 9.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 72        | 93.51%  |
| AMD    | 5         | 6.49%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 3.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 3.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 3.9%    |
| Intel 12th Gen Core i7-12700H           | 3         | 3.9%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 2.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 2.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 2.6%    |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 2         | 2.6%    |
| Intel 11th Gen Core i9-11950H @ 2.60GHz | 2         | 2.6%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 2         | 2.6%    |
| Intel Xeon W-11855M CPU @ 3.20GHz       | 1         | 1.3%    |
| Intel Core Ultra 9 185H                 | 1         | 1.3%    |
| Intel Core Ultra 7 265H                 | 1         | 1.3%    |
| Intel Core Ultra 7 165H                 | 1         | 1.3%    |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 1.3%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.3%    |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 1.3%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.3%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.3%    |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.3%    |
| Intel Core i7-4900MQ CPU @ 2.80GHz      | 1         | 1.3%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 1.3%    |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.3%    |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 1.3%    |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.3%    |
| Intel Core i5-9300H CPU @ 2.40GHz       | 1         | 1.3%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.3%    |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.3%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.3%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.3%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.3%    |
| Intel Core i5-5300U CPU @ 2.30GHz       | 1         | 1.3%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.3%    |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 1.3%    |
| Intel Core i3-N300                      | 1         | 1.3%    |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 1.3%    |
| Intel Celeron N5095A @ 2.00GHz          | 1         | 1.3%    |
| Intel Celeron N4120 CPU @ 1.10GHz       | 1         | 1.3%    |
| Intel Celeron N4100 CPU @ 1.10GHz       | 1         | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Other           | 24        | 31.17%  |
| Intel Core i5   | 20        | 25.97%  |
| Intel Core i7   | 15        | 19.48%  |
| Intel Core i3   | 4         | 5.19%   |
| Intel Celeron   | 4         | 5.19%   |
| Intel Core      | 3         | 3.9%    |
| AMD Ryzen 7 PRO | 2         | 2.6%    |
| AMD Ryzen 5     | 2         | 2.6%    |
| Intel Xeon      | 1         | 1.3%    |
| Intel Core i9   | 1         | 1.3%    |
| AMD Ryzen 3     | 1         | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 28        | 36.36%  |
| 2      | 16        | 20.78%  |
| 8      | 10        | 12.99%  |
| 6      | 9         | 11.69%  |
| 10     | 5         | 6.49%   |
| 16     | 3         | 3.9%    |
| 14     | 3         | 3.9%    |
| 12     | 3         | 3.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 77        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 69        | 89.61%  |
| 1      | 8         | 10.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 77        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 51.9%   |
| 0x806ec    | 6         | 7.59%   |
| 0x806d1    | 4         | 5.06%   |
| 0x906a3    | 3         | 3.8%    |
| 0x706e5    | 2         | 2.53%   |
| 0x506e3    | 2         | 2.53%   |
| 0x406e3    | 2         | 2.53%   |
| 0x306a9    | 2         | 2.53%   |
| 0x906ed    | 1         | 1.27%   |
| 0x906ea    | 1         | 1.27%   |
| 0x906e9    | 1         | 1.27%   |
| 0x906a4    | 1         | 1.27%   |
| 0x90672    | 1         | 1.27%   |
| 0x806ea    | 1         | 1.27%   |
| 0x706a8    | 1         | 1.27%   |
| 0x706a1    | 1         | 1.27%   |
| 0x40651    | 1         | 1.27%   |
| 0x306d4    | 1         | 1.27%   |
| 0x306c3    | 1         | 1.27%   |
| 0x20655    | 1         | 1.27%   |
| 0x0a404102 | 1         | 1.27%   |
| 0x08608103 | 1         | 1.27%   |
| 0x08600106 | 1         | 1.27%   |
| 0x08108109 | 1         | 1.27%   |
| 0x08108102 | 1         | 1.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 18        | 23.38%  |
| Alderlake Hybrid  | 14        | 18.18%  |
| Icelake           | 8         | 10.39%  |
| TigerLake         | 5         | 6.49%   |
| Skylake           | 5         | 6.49%   |
| Haswell           | 4         | 5.19%   |
| IvyBridge         | 3         | 3.9%    |
| Goldmont plus     | 3         | 3.9%    |
| Unknown           | 3         | 3.9%    |
| Zen+              | 2         | 2.6%    |
| Westmere          | 2         | 2.6%    |
| SandyBridge       | 2         | 2.6%    |
| Meteorlake Hybrid | 2         | 2.6%    |
| Broadwell         | 2         | 2.6%    |
| Zen 2             | 1         | 1.3%    |
| Tremont           | 1         | 1.3%    |
| Gracemont         | 1         | 1.3%    |
| CometLake         | 1         | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 63        | 65.63%  |
| Nvidia | 23        | 23.96%  |
| AMD    | 10        | 10.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 5.21%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 5         | 5.21%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 4         | 4.17%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 4         | 4.17%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 4         | 4.17%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 4         | 4.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 4.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 4.17%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 3         | 3.13%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 3.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 2.08%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 2.08%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 2         | 2.08%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 2.08%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                        | 2         | 2.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 2.08%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                  | 2         | 2.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 2.08%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 2         | 2.08%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 2         | 2.08%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 2.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 2.08%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                        | 1         | 1.04%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 1.04%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 1.04%   |
| Nvidia GP104GLM [Quadro P3200 Mobile]                                     | 1         | 1.04%   |
| Nvidia GP104GLM [Quadro P3000 Mobile]                                     | 1         | 1.04%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 1.04%   |
| Nvidia GA102 [GeForce RTX 3090]                                           | 1         | 1.04%   |
| Nvidia AD107GLM [RTX 2000 Ada Generation Laptop GPU]                      | 1         | 1.04%   |
| Nvidia AD106GLM [RTX 3000 Ada Generation Laptop GPU]                      | 1         | 1.04%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                     | 1         | 1.04%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 1         | 1.04%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                   | 1         | 1.04%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 1.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 1.04%   |
| Intel Arrow Lake-P [Arc Pro 130T/140T]                                    | 1         | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 57.14%  |
| Intel + Nvidia | 15        | 19.48%  |
| 1 x Nvidia     | 8         | 10.39%  |
| 1 x AMD        | 6         | 7.79%   |
| Intel + AMD    | 4         | 5.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 66        | 85.71%  |
| Proprietary | 9         | 11.69%  |
| Unknown     | 2         | 2.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 70.13%  |
| 5.01-6.0   | 6         | 7.79%   |
| 1.01-2.0   | 6         | 7.79%   |
| 0.51-1.0   | 3         | 3.9%    |
| 3.01-4.0   | 2         | 2.6%    |
| 0.01-0.5   | 2         | 2.6%    |
| 7.01-8.0   | 1         | 1.3%    |
| 2.01-3.0   | 1         | 1.3%    |
| 16.01-24.0 | 1         | 1.3%    |
| 8.01-16.0  | 1         | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 21        | 20.19%  |
| AU Optronics         | 15        | 14.42%  |
| LG Display           | 12        | 11.54%  |
| Chimei Innolux       | 10        | 9.62%   |
| Dell                 | 5         | 4.81%   |
| CSO                  | 5         | 4.81%   |
| Samsung Electronics  | 4         | 3.85%   |
| Sharp                | 3         | 2.88%   |
| Lenovo               | 3         | 2.88%   |
| Hewlett-Packard      | 3         | 2.88%   |
| Goldstar             | 3         | 2.88%   |
| ___                  | 2         | 1.92%   |
| Vizio                | 2         | 1.92%   |
| Unknown              | 2         | 1.92%   |
| Unknown (XXX)        | 1         | 0.96%   |
| Sceptre Tech         | 1         | 0.96%   |
| Philips              | 1         | 0.96%   |
| PANDA                | 1         | 0.96%   |
| KDB                  | 1         | 0.96%   |
| InfoVision           | 1         | 0.96%   |
| Gigabyte Technology  | 1         | 0.96%   |
| CTO                  | 1         | 0.96%   |
| CSW                  | 1         | 0.96%   |
| CEX                  | 1         | 0.96%   |
| BOE Technology Group | 1         | 0.96%   |
| ASUSTek Computer     | 1         | 0.96%   |
| AOC                  | 1         | 0.96%   |
| Acer                 | 1         | 0.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| ___ LCD TV ___9000 1360x768                                           | 2         | 1.87%   |
| Vizio E500i-B1 VIZ1004 1920x1080 1095x616mm 49.5-inch                 | 2         | 1.87%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 2         | 1.87%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch        | 1         | 0.93%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch               | 1         | 0.93%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.93%   |
| Sharp LCD Monitor SHP13F9 3200x1800 350x190mm 15.7-inch               | 1         | 0.93%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 819x346mm 35.0-inch        | 1         | 0.93%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch     | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.93%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch              | 1         | 0.93%   |
| Philips PHL 272B7QPJ PHL0900 2560x1440 597x336mm 27.0-inch            | 1         | 0.93%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD0753 1920x1080 309x174mm 14.0-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD06CF 1920x1080 344x194mm 15.5-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD0645 1920x1080 344x194mm 15.5-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD0613 1920x1080 309x174mm 14.0-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 0.93%   |
| Lenovo P34w-20 LEN62CC 3440x1440 800x335mm 34.1-inch                  | 1         | 0.93%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch              | 1         | 0.93%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 1         | 0.93%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 1         | 0.93%   |
| KDB LCD Monitor KDB0106 1920x1200 302x189mm 14.0-inch                 | 1         | 0.93%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 0.93%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 519x324mm 24.1-inch          | 1         | 0.93%   |
| Hewlett-Packard LCD Monitor Pavilion32                                | 1         | 0.93%   |
| Hewlett-Packard E271i HWP3106 1920x1080 600x340mm 27.2-inch           | 1         | 0.93%   |
| Goldstar UltraFine GSM5B11 4096x2304 600x340mm 27.2-inch              | 1         | 0.93%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 1         | 0.93%   |
| Goldstar 27GL850 GSM5B80 2560x1440 697x392mm 31.5-inch                | 1         | 0.93%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 597x336mm 27.0-inch        | 1         | 0.93%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 44        | 47.31%  |
| 1366x768 (WXGA)   | 13        | 13.98%  |
| 1920x1200 (WUXGA) | 9         | 9.68%   |
| 3840x2160 (4K)    | 6         | 6.45%   |
| 2560x1600         | 4         | 4.3%    |
| 2560x1440 (QHD)   | 4         | 4.3%    |
| 3840x2400         | 2         | 2.15%   |
| 3440x1440         | 2         | 2.15%   |
| 1360x768          | 2         | 2.15%   |
| Unknown           | 2         | 2.15%   |
| 6400x2160         | 1         | 1.08%   |
| 5120x1440         | 1         | 1.08%   |
| 3200x1800 (QHD+)  | 1         | 1.08%   |
| 2160x1350         | 1         | 1.08%   |
| 1600x900 (HD+)    | 1         | 1.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 25        | 24.51%  |
| 13      | 19        | 18.63%  |
| 14      | 15        | 14.71%  |
| 16      | 6         | 5.88%   |
| 27      | 5         | 4.9%    |
| 24      | 5         | 4.9%    |
| 17      | 5         | 4.9%    |
| 23      | 4         | 3.92%   |
| Unknown | 4         | 3.92%   |
| 72      | 3         | 2.94%   |
| 54      | 3         | 2.94%   |
| 31      | 2         | 1.96%   |
| 35      | 1         | 0.98%   |
| 34      | 1         | 0.98%   |
| 21      | 1         | 0.98%   |
| 18      | 1         | 0.98%   |
| 12      | 1         | 0.98%   |
| 11      | 1         | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 57.43%  |
| 501-600     | 13        | 12.87%  |
| 201-300     | 9         | 8.91%   |
| 351-400     | 5         | 4.95%   |
| Unknown     | 4         | 3.96%   |
| 1501-2000   | 3         | 2.97%   |
| 1001-1500   | 3         | 2.97%   |
| 601-700     | 2         | 1.98%   |
| 401-500     | 2         | 1.98%   |
| 801-900     | 1         | 0.99%   |
| 701-800     | 1         | 0.99%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 62        | 74.7%   |
| 16/10   | 17        | 20.48%  |
| 21/9    | 2         | 2.41%   |
| Unknown | 2         | 2.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 27        | 26.21%  |
| 101-110        | 24        | 23.3%   |
| 201-250        | 9         | 8.74%   |
| 71-80          | 7         | 6.8%    |
| More than 1000 | 6         | 5.83%   |
| 111-120        | 6         | 5.83%   |
| 301-350        | 5         | 4.85%   |
| 121-130        | 5         | 4.85%   |
| 351-500        | 4         | 3.88%   |
| Unknown        | 4         | 3.88%   |
| 251-300        | 2         | 1.94%   |
| 61-70          | 1         | 0.97%   |
| 51-60          | 1         | 0.97%   |
| 141-150        | 1         | 0.97%   |
| 91-100         | 1         | 0.97%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 39        | 39.39%  |
| 101-120       | 18        | 18.18%  |
| 161-240       | 16        | 16.16%  |
| 51-100        | 11        | 11.11%  |
| More than 240 | 6         | 6.06%   |
| 1-50          | 5         | 5.05%   |
| Unknown       | 4         | 4.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 55        | 69.62%  |
| 2     | 15        | 18.99%  |
| 3     | 6         | 7.59%   |
| 5     | 1         | 1.27%   |
| 4     | 1         | 1.27%   |
| 0     | 1         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 62        | 52.99%  |
| Realtek Semiconductor | 33        | 28.21%  |
| Qualcomm Atheros      | 10        | 8.55%   |
| HMD Global            | 2         | 1.71%   |
| DisplayLink           | 2         | 1.71%   |
| Broadcom              | 2         | 1.71%   |
| Sierra Wireless       | 1         | 0.85%   |
| Ralink Technology     | 1         | 0.85%   |
| Qualcomm              | 1         | 0.85%   |
| OPPO Electronics      | 1         | 0.85%   |
| MediaTek              | 1         | 0.85%   |
| Broadcom Limited      | 1         | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14        | 9.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 7.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 8         | 5.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 2.65%   |
| Intel Wireless 8265 / 8275                                             | 4         | 2.65%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 2.65%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 2.65%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 4         | 2.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 2.65%   |
| Intel Wireless 8260                                                    | 3         | 1.99%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 1.99%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.32%   |
| Intel Wireless 7265                                                    | 2         | 1.32%   |
| Intel Wireless 7260                                                    | 2         | 1.32%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 1.32%   |
| Intel Ethernet Controller I225-LM                                      | 2         | 1.32%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.32%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.32%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.32%   |
| Intel Ethernet Connection (23) I219-LM                                 | 2         | 1.32%   |
| Intel Ethernet Connection (13) I219-LM                                 | 2         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.32%   |
| HMD Global Nokia7.2                                                    | 2         | 1.32%   |
| Sierra Wireless EM7455                                                 | 1         | 0.66%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.66%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.66%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.66%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.66%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 70.83%  |
| Qualcomm Atheros      | 8         | 11.11%  |
| Realtek Semiconductor | 6         | 8.33%   |
| Broadcom              | 2         | 2.78%   |
| Sierra Wireless       | 1         | 1.39%   |
| Ralink Technology     | 1         | 1.39%   |
| Qualcomm              | 1         | 1.39%   |
| MediaTek              | 1         | 1.39%   |
| Broadcom Limited      | 1         | 1.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 4         | 5.56%   |
| Intel Wireless 8265 / 8275                                      | 4         | 5.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 4         | 5.56%   |
| Intel Wi-Fi 6 AX201                                             | 4         | 5.56%   |
| Intel Raptor Lake PCH CNVi WiFi                                 | 4         | 5.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 4         | 5.56%   |
| Intel Wireless 8260                                             | 3         | 4.17%   |
| Intel Wi-Fi 6 AX200                                             | 3         | 4.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                | 3         | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2         | 2.78%   |
| Intel Wireless 7265                                             | 2         | 2.78%   |
| Intel Wireless 7260                                             | 2         | 2.78%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 2         | 2.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 2         | 2.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 2         | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 2         | 2.78%   |
| Sierra Wireless EM7455                                          | 1         | 1.39%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 1         | 1.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.39%   |
| Realtek RTL8723DE Wireless Network Adapter                      | 1         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 1         | 1.39%   |
| Ralink MT7601U Wireless Adapter                                 | 1         | 1.39%   |
| Qualcomm QCNFA765 Wireless Network Adapter                      | 1         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1         | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 1         | 1.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 1         | 1.39%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 1         | 1.39%   |
| Intel Wireless 3165                                             | 1         | 1.39%   |
| Intel Wireless 3160                                             | 1         | 1.39%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2 | 1         | 1.39%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 1         | 1.39%   |
| Intel Meteor Lake PCH CNVi WiFi                                 | 1         | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                  | 1         | 1.39%   |
| Intel Centrino Wireless-N 2230                                  | 1         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 1         | 1.39%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 1         | 1.39%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter     | 1         | 1.39%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 1         | 1.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 49.33%  |
| Realtek Semiconductor | 31        | 41.33%  |
| Qualcomm Atheros      | 2         | 2.67%   |
| HMD Global            | 2         | 2.67%   |
| DisplayLink           | 2         | 2.67%   |
| OPPO Electronics      | 1         | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14        | 17.72%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 13.92%  |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 6.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 5.06%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 3.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 3.8%    |
| Intel Ethernet Controller I225-LM                                      | 2         | 2.53%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 2.53%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 2.53%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 2.53%   |
| Intel Ethernet Connection (23) I219-LM                                 | 2         | 2.53%   |
| Intel Ethernet Connection (13) I219-LM                                 | 2         | 2.53%   |
| HMD Global Nokia7.2                                                    | 2         | 2.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.27%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 1.27%   |
| OPPO Ace 3V                                                            | 1         | 1.27%   |
| Intel Ethernet Controller I226-LMvP                                    | 1         | 1.27%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.27%   |
| Intel Ethernet Controller (2) I225-LMvP                                | 1         | 1.27%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.27%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.27%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.27%   |
| Intel Ethernet Connection (24) I219-LM                                 | 1         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.27%   |
| Intel Ethernet Connection (18) I219-LM                                 | 1         | 1.27%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.27%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 1.27%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.27%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 1.27%   |
| Intel Arrow Lake CNVi WiFi                                             | 1         | 1.27%   |
| Intel Alder Lake-N PCH CNVi WiFi                                       | 1         | 1.27%   |
| DisplayLink USB-C Triple-4K Dock                                       | 1         | 1.27%   |
| DisplayLink Dell D3100 Docking Station                                 | 1         | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 70        | 52.63%  |
| Ethernet | 63        | 47.37%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 54        | 66.67%  |
| Ethernet | 27        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 51        | 66.23%  |
| 1     | 24        | 31.17%  |
| 3     | 2         | 2.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 53        | 67.95%  |
| Yes  | 25        | 32.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 70.15%  |
| Qualcomm Atheros Communications | 7         | 10.45%  |
| Realtek Semiconductor           | 5         | 7.46%   |
| Broadcom                        | 4         | 5.97%   |
| USI                             | 1         | 1.49%   |
| MediaTek                        | 1         | 1.49%   |
| IMC Networks                    | 1         | 1.49%   |
| ASUSTek Computer                | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 13        | 19.4%   |
| Intel Bluetooth Device                         | 11        | 16.42%  |
| Intel Bluetooth wireless interface             | 8         | 11.94%  |
| Qualcomm Atheros  Bluetooth Device             | 6         | 8.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 6         | 8.96%   |
| Realtek Bluetooth Radio                        | 4         | 5.97%   |
| Intel AX210 Bluetooth                          | 4         | 5.97%   |
| Intel AX200 Bluetooth                          | 3         | 4.48%   |
| Broadcom HP Portable SoftSailing               | 2         | 2.99%   |
| USI Bluetooth Device                           | 1         | 1.49%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 1.49%   |
| Qualcomm Atheros AR3011 Bluetooth              | 1         | 1.49%   |
| MediaTek Wireless_Device                       | 1         | 1.49%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 1.49%   |
| IMC Networks Bluetooth Radio                   | 1         | 1.49%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 1         | 1.49%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 1.49%   |
| ASUS ASUS USB-BT500                            | 1         | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 72        | 61.54%  |
| Nvidia                   | 18        | 15.38%  |
| AMD                      | 8         | 6.84%   |
| Realtek Semiconductor    | 5         | 4.27%   |
| Texas Instruments        | 3         | 2.56%   |
| Lenovo                   | 2         | 1.71%   |
| SteelSeries ApS          | 1         | 0.85%   |
| Sony                     | 1         | 0.85%   |
| Plantronics              | 1         | 0.85%   |
| Nordic Semiconductor ASA | 1         | 0.85%   |
| LG Electronics           | 1         | 0.85%   |
| Hewlett-Packard          | 1         | 0.85%   |
| Harman                   | 1         | 0.85%   |
| Corsair                  | 1         | 0.85%   |
| BEHRINGER International  | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                      | 9         | 7.14%   |
| Intel Sunrise Point-LP HD Audio                                              | 8         | 6.35%   |
| Intel Tiger Lake-H HD Audio Controller                                       | 6         | 4.76%   |
| Intel Cannon Lake PCH cAVS                                                   | 6         | 4.76%   |
| Realtek Semiconductor USB Audio                                              | 5         | 3.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                  | 5         | 3.97%   |
| AMD Ryzen HD Audio Controller                                                | 5         | 3.97%   |
| Nvidia GA106 High Definition Audio Controller                                | 4         | 3.17%   |
| Intel Raptor Lake-P/U/H cAVS                                                 | 4         | 3.17%   |
| Intel Comet Lake PCH-LP cAVS                                                 | 4         | 3.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller               | 3         | 2.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                 | 3         | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller          | 3         | 2.38%   |
| Texas Instruments PCM2902 Audio Codec                                        | 2         | 1.59%   |
| Nvidia TU116 High Definition Audio Controller                                | 2         | 1.59%   |
| Nvidia GP104 High Definition Audio Controller                                | 2         | 1.59%   |
| Nvidia GK107 HDMI Audio Controller                                           | 2         | 1.59%   |
| Nvidia GA104 High Definition Audio Controller                                | 2         | 1.59%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                                 | 2         | 1.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                      | 2         | 1.59%   |
| Intel Meteor Lake-P HD Audio Controller                                      | 2         | 1.59%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                    | 2         | 1.59%   |
| Intel Haswell-ULT HD Audio Controller                                        | 2         | 1.59%   |
| Intel CM238 HD Audio Controller                                              | 2         | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                       | 2         | 1.59%   |
| Intel Broadwell-U Audio Controller                                           | 2         | 1.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller          | 2         | 1.59%   |
| Intel 8 Series HD Audio Controller                                           | 2         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller   | 2         | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                     | 2         | 1.59%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                  | 2         | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                          | 2         | 1.59%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                            | 1         | 0.79%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                                | 1         | 0.79%   |
| Sony DualSense wireless controller (PS5)                                     | 1         | 0.79%   |
| Plantronics Blackwire C5220 headset (remote control and 3.5mm audio adapter) | 1         | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                                | 1         | 0.79%   |
| Nvidia GA107 High Definition Audio Controller                                | 1         | 0.79%   |
| Nvidia GA102 High Definition Audio Controller                                | 1         | 0.79%   |
| Nordic Semiconductor ASA SG Control Mic                                      | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 23.33%  |
| SK hynix            | 6         | 20%     |
| Kingston            | 5         | 16.67%  |
| Micron Technology   | 3         | 10%     |
| Crucial             | 2         | 6.67%   |
| Unknown             | 2         | 6.67%   |
| Unknown             | 1         | 3.33%   |
| Team                | 1         | 3.33%   |
| Smart               | 1         | 3.33%   |
| Nanya Technology    | 1         | 3.33%   |
| Elpida              | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 2         | 6.25%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                    | 1         | 3.13%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 1         | 3.13%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s        | 1         | 3.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 3.13%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 3.13%   |
| SK hynix RAM HMCG78AGBSA095N 16GB SODIMM DDR5 5600MT/s       | 1         | 3.13%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s       | 1         | 3.13%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 3.13%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 3.13%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 3.13%   |
| SK hynix RAM H5AN8G6NDJR-XNC 4GB Row Of Chips DDR4 2400MT/s  | 1         | 3.13%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 3.13%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 3.13%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 3.13%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 1         | 3.13%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 3.13%   |
| Samsung RAM K3LKBKB0BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 3.13%   |
| Samsung RAM K3LK7K7@BM-BGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 3.13%   |
| Nanya RAM NT8GA64D88CX3S-JR 8GB SODIMM DDR4 3200MT/s         | 1         | 3.13%   |
| Micron RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s     | 1         | 3.13%   |
| Micron RAM CB8GS3200.C8TT 8GB SODIMM DDR4 3200MT/s           | 1         | 3.13%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s        | 1         | 3.13%   |
| Kingston RAM X74R9W-MIE 8GB SODIMM DDR4 2933MT/s             | 1         | 3.13%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2667MT/s        | 1         | 3.13%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 1         | 3.13%   |
| Kingston RAM 9905744-108.A00G 16GB SODIMM DDR4 3200MT/s      | 1         | 3.13%   |
| Kingston RAM 9905624-009.A00G 8GB SODIMM DDR4 2133MT/s       | 1         | 3.13%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 1         | 3.13%   |
| Crucial RAM CT4G4SFS824A.M8FE 4GB SODIMM DDR4 2400MT/s       | 1         | 3.13%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s   | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 17        | 68%     |
| LPDDR5 | 4         | 16%     |
| DDR3   | 3         | 12%     |
| DDR5   | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 20        | 76.92%  |
| Row Of Chips    | 4         | 15.38%  |
| Proprietary Car | 1         | 3.85%   |
| Chip            | 1         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 10        | 37.04%  |
| 16384 | 6         | 22.22%  |
| 32768 | 5         | 18.52%  |
| 4096  | 5         | 18.52%  |
| 2048  | 1         | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 7         | 25%     |
| 2667  | 5         | 17.86%  |
| 2400  | 4         | 14.29%  |
| 2133  | 3         | 10.71%  |
| 1600  | 3         | 10.71%  |
| 6400  | 2         | 7.14%   |
| 7500  | 1         | 3.57%   |
| 7467  | 1         | 3.57%   |
| 5600  | 1         | 3.57%   |
| 2933  | 1         | 3.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3210 Series | 1         | 100%    |

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
| Chicony Electronics                    | 17        | 22.97%  |
| Sunplus Innovation Technology          | 9         | 12.16%  |
| Microdia                               | 7         | 9.46%   |
| IMC Networks                           | 7         | 9.46%   |
| Bison Electronics                      | 7         | 9.46%   |
| Realtek Semiconductor                  | 4         | 5.41%   |
| Luxvisions Innotech Limited            | 4         | 5.41%   |
| Syntek                                 | 3         | 4.05%   |
| Lite-On Technology                     | 3         | 4.05%   |
| Suyin                                  | 1         | 1.35%   |
| Sonix Technology                       | 1         | 1.35%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.35%   |
| Samsung Electronics                    | 1         | 1.35%   |
| Remo Tech                              | 1         | 1.35%   |
| Quanta                                 | 1         | 1.35%   |
| Microsoft                              | 1         | 1.35%   |
| Logitech                               | 1         | 1.35%   |
| LG Electronics                         | 1         | 1.35%   |
| icSpring                               | 1         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.35%   |
| Alcor Micro                            | 1         | 1.35%   |
| Acer                                   | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                          | 5         | 6.76%   |
| Chicony Integrated Camera                             | 5         | 6.76%   |
| IMC Networks Integrated Camera                        | 4         | 5.41%   |
| Syntek Integrated Camera                              | 3         | 4.05%   |
| Microdia Integrated_Webcam_HD                         | 3         | 4.05%   |
| Sunplus Integrated Camera                             | 2         | 2.7%    |
| Realtek Integrated_Webcam_HD                          | 2         | 2.7%    |
| Luxvisions Innotech Limited Integrated Camera         | 2         | 2.7%    |
| Lite-On Integrated Camera                             | 2         | 2.7%    |
| IMC Networks USB2.0 HD UVC WebCam                     | 2         | 2.7%    |
| Chicony Integrated HP HD Webcam                       | 2         | 2.7%    |
| Chicony HP HD Camera                                  | 2         | 2.7%    |
| Bison Integrated Camera                               | 2         | 2.7%    |
| Bison HD Webcam                                       | 2         | 2.7%    |
| Suyin Integrated_Webcam_HD                            | 1         | 1.35%   |
| Sunplus Laptop_Integrated_Webcam_FHD                  | 1         | 1.35%   |
| Sunplus Hy FHD B200 Came                              | 1         | 1.35%   |
| Sonix USB2.0 HD UVC WebCam                            | 1         | 1.35%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera       | 1         | 1.35%   |
| Samsung Galaxy series, misc. (MTP mode)               | 1         | 1.35%   |
| Remo Tech OBSBOT Tiny 4K                              | 1         | 1.35%   |
| Realtek Integrated_Webcam_FHD                         | 1         | 1.35%   |
| Realtek Integrated Webcam_HD                          | 1         | 1.35%   |
| Quanta HP TrueVision HD Camera                        | 1         | 1.35%   |
| Microsoft LifeCam VX-2000                             | 1         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_0.3M                | 1         | 1.35%   |
| Microdia Integrated_Webcam_FHD                        | 1         | 1.35%   |
| Microdia Integrated Webcam                            | 1         | 1.35%   |
| Microdia 1.3 MPixel Integrated Webcam                 | 1         | 1.35%   |
| Luxvisions Innotech Limited Integrated RGB Camera     | 1         | 1.35%   |
| Luxvisions Innotech Limited HP True Vision FHD Camera | 1         | 1.35%   |
| Logitech HD Pro Webcam C920                           | 1         | 1.35%   |
| Lite-On HP HD Camera                                  | 1         | 1.35%   |
| LG LG UltraFine Display Camera                        | 1         | 1.35%   |
| IMC Networks USB Camera                               | 1         | 1.35%   |
| icSpring camera                                       | 1         | 1.35%   |
| Chicony USB2.0 VGA UVC WebCam                         | 1         | 1.35%   |
| Chicony ThinkPad T490 Webcam                          | 1         | 1.35%   |
| Chicony LG Camera                                     | 1         | 1.35%   |
| Chicony Integrated RGB Camera                         | 1         | 1.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 12        | 63.16%  |
| Validity Sensors           | 4         | 21.05%  |
| Shenzhen Goodix Technology | 2         | 10.53%  |
| Samsung Electronics        | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 5         | 26.32%  |
| Synaptics UWP WBDI Device                                 | 4         | 21.05%  |
| Validity Sensors VFS491                                   | 2         | 10.53%  |
| Synaptics Prometheus Fingerprint Reader                   | 2         | 10.53%  |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 10.53%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 5.26%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 5.26%   |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 13        | 81.25%  |
| Alcor Micro | 3         | 18.75%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 5         | 31.25%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 18.75%  |
| Broadcom 58200                                                               | 3         | 18.75%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 18.75%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 43        | 55.84%  |
| 1     | 27        | 35.06%  |
| 2     | 5         | 6.49%   |
| 5     | 1         | 1.3%    |
| 3     | 1         | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 19        | 41.3%   |
| Chipcard              | 9         | 19.57%  |
| Graphics card         | 6         | 13.04%  |
| Multimedia controller | 4         | 8.7%    |
| Net/wireless          | 3         | 6.52%   |
| Storage               | 1         | 2.17%   |
| Sound                 | 1         | 2.17%   |
| Firewire controller   | 1         | 2.17%   |
| Card reader           | 1         | 2.17%   |
| Camera                | 1         | 2.17%   |

