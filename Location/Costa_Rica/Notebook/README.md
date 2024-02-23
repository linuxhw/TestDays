Linux in Costa Rica - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

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

Total: 274

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire E5-473               | [0a294c97ee](https://linux-hardware.org/?probe=0a294c97ee) | Jan 31, 2024 |
| HP            | Pavilion g4                 | [1edc58a524](https://linux-hardware.org/?probe=1edc58a524) | Jan 22, 2024 |
| GPU Compan... | GWTN141-10                  | [cd417ed644](https://linux-hardware.org/?probe=cd417ed644) | Jan 10, 2024 |
| GPU Compan... | GWTN141-10                  | [443e0e2a67](https://linux-hardware.org/?probe=443e0e2a67) | Jan 04, 2024 |
| HP            | G60                         | [a151a8084c](https://linux-hardware.org/?probe=a151a8084c) | Jan 01, 2024 |
| HP            | Laptop 15-da0xxx            | [4e00c088e8](https://linux-hardware.org/?probe=4e00c088e8) | Dec 29, 2023 |
| Lenovo        | ThinkPad T420 4236DA4       | [1188c1619d](https://linux-hardware.org/?probe=1188c1619d) | Dec 20, 2023 |
| Dell          | XPS 15 9560                 | [bb58136a7c](https://linux-hardware.org/?probe=bb58136a7c) | Dec 18, 2023 |
| Dell          | G15 5515                    | [259739c8b5](https://linux-hardware.org/?probe=259739c8b5) | Dec 14, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [6b350f2aaf](https://linux-hardware.org/?probe=6b350f2aaf) | Dec 11, 2023 |
| HP            | EliteBook 8470p             | [c723bcc62a](https://linux-hardware.org/?probe=c723bcc62a) | Dec 07, 2023 |
| Apple         | MacBookPro8,1               | [7d8d9279cd](https://linux-hardware.org/?probe=7d8d9279cd) | Nov 21, 2023 |
| Apple         | MacBookPro5,4               | [7045b84f52](https://linux-hardware.org/?probe=7045b84f52) | Nov 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [af8edff0b6](https://linux-hardware.org/?probe=af8edff0b6) | Nov 15, 2023 |
| Toshiba       | Satellite L845              | [4dc7e8931e](https://linux-hardware.org/?probe=4dc7e8931e) | Nov 05, 2023 |
| Dell          | Inspiron 3443               | [bbe3093cb4](https://linux-hardware.org/?probe=bbe3093cb4) | Oct 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [d8335b95a8](https://linux-hardware.org/?probe=d8335b95a8) | Oct 19, 2023 |
| Apple         | MacBookPro8,1               | [ae4ee327c0](https://linux-hardware.org/?probe=ae4ee327c0) | Oct 06, 2023 |
| HP            | Laptop 15-da0xxx            | [92e214fb3e](https://linux-hardware.org/?probe=92e214fb3e) | Oct 04, 2023 |
| HP            | EliteBook 745 G3            | [a814d9fa4b](https://linux-hardware.org/?probe=a814d9fa4b) | Sep 25, 2023 |
| HP            | Mini 110-1000               | [dda4d7a910](https://linux-hardware.org/?probe=dda4d7a910) | Sep 18, 2023 |
| HP            | Mini 110-1000               | [ee2d142228](https://linux-hardware.org/?probe=ee2d142228) | Sep 18, 2023 |
| Apple         | MacBookPro8,1               | [c7b5f9224a](https://linux-hardware.org/?probe=c7b5f9224a) | Sep 17, 2023 |
| ASUSTek       | X541UV                      | [a66fcc9edb](https://linux-hardware.org/?probe=a66fcc9edb) | Sep 11, 2023 |
| Sony          | SVE14123CLW                 | [2fffba7739](https://linux-hardware.org/?probe=2fffba7739) | Sep 08, 2023 |
| Dell          | Inspiron 5567               | [3b740d65f2](https://linux-hardware.org/?probe=3b740d65f2) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [40693c0171](https://linux-hardware.org/?probe=40693c0171) | Aug 29, 2023 |
| Lenovo        | B590 20208                  | [65bf0970da](https://linux-hardware.org/?probe=65bf0970da) | Aug 27, 2023 |
| Dell          | Latitude E6420              | [ae48a8c618](https://linux-hardware.org/?probe=ae48a8c618) | Aug 26, 2023 |
| MSI           | Katana 15 B13VGK            | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b65293c5a8](https://linux-hardware.org/?probe=b65293c5a8) | Aug 17, 2023 |
| HP            | EliteBook 840 G3            | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Samsung       | 930X2K/931X2K               | [5985901bef](https://linux-hardware.org/?probe=5985901bef) | Aug 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [ec5a50d1d8](https://linux-hardware.org/?probe=ec5a50d1d8) | Jul 29, 2023 |
| ASUSTek       | Q551LN                      | [ad2abcddcf](https://linux-hardware.org/?probe=ad2abcddcf) | Jul 27, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Toshiba       | Satellite L755              | [cb309977d0](https://linux-hardware.org/?probe=cb309977d0) | Jul 08, 2023 |
| Samsung       | 930X2K/931X2K               | [fd0d25039d](https://linux-hardware.org/?probe=fd0d25039d) | Jul 07, 2023 |
| Samsung       | 930X2K/931X2K               | [294e57d915](https://linux-hardware.org/?probe=294e57d915) | Jul 07, 2023 |
| Dell          | Inspiron 5593               | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [3e3987b43f](https://linux-hardware.org/?probe=3e3987b43f) | Jun 20, 2023 |
| HP            | ENVY 15                     | [101fb8810b](https://linux-hardware.org/?probe=101fb8810b) | Jun 19, 2023 |
| HP            | Notebook                    | [42558904aa](https://linux-hardware.org/?probe=42558904aa) | Jun 10, 2023 |
| Apple         | MacBookPro8,1               | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1aa286ccff](https://linux-hardware.org/?probe=1aa286ccff) | Jun 03, 2023 |
| HP            | Notebook                    | [c246477ea2](https://linux-hardware.org/?probe=c246477ea2) | May 31, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [360e8fd5e5](https://linux-hardware.org/?probe=360e8fd5e5) | May 30, 2023 |
| HP            | Notebook                    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Samsung       | 930X2K/931X2K               | [14eae60f4f](https://linux-hardware.org/?probe=14eae60f4f) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | [7ac717a41d](https://linux-hardware.org/?probe=7ac717a41d) | May 13, 2023 |
| Apple         | MacBookPro9,2               | [ba104d9250](https://linux-hardware.org/?probe=ba104d9250) | May 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b06388c1f4](https://linux-hardware.org/?probe=b06388c1f4) | May 09, 2023 |
| Samsung       | 930X2K/931X2K               | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [36ec2bb4c2](https://linux-hardware.org/?probe=36ec2bb4c2) | Apr 22, 2023 |
| HP            | ProBook 6570b               | [2b01f67020](https://linux-hardware.org/?probe=2b01f67020) | Apr 14, 2023 |
| Samsung       | 930X2K/931X2K               | [126c7a430c](https://linux-hardware.org/?probe=126c7a430c) | Apr 13, 2023 |
| Samsung       | 930X2K/931X2K               | [80d44eb98b](https://linux-hardware.org/?probe=80d44eb98b) | Apr 12, 2023 |
| HP            | EliteBook 8560p             | [2ecc0fe5bc](https://linux-hardware.org/?probe=2ecc0fe5bc) | Apr 07, 2023 |
| Apple         | MacBookPro8,1               | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Laptop 15-da0xxx            | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| Google        | Snappy                      | [16dda325bf](https://linux-hardware.org/?probe=16dda325bf) | Apr 02, 2023 |
| Apple         | MacBookPro8,1               | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| Acer          | Aspire E1-431               | [f56a2c21cf](https://linux-hardware.org/?probe=f56a2c21cf) | Mar 26, 2023 |
| Dell          | XPS 15 9510                 | [d8fee2b6b1](https://linux-hardware.org/?probe=d8fee2b6b1) | Mar 08, 2023 |
| Acer          | Aspire V3-571G              | [b02e34a7f9](https://linux-hardware.org/?probe=b02e34a7f9) | Feb 25, 2023 |
| Unknown       | Unknown                     | [6707aef886](https://linux-hardware.org/?probe=6707aef886) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Acer          | Aspire A515-45              | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [8761a4096a](https://linux-hardware.org/?probe=8761a4096a) | Jan 22, 2023 |
| HP            | Laptop 14-dk1xxx            | [7099ccff2f](https://linux-hardware.org/?probe=7099ccff2f) | Jan 22, 2023 |
| HP            | Laptop 15-da0xxx            | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| Apple         | MacBookPro8,1               | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| HP            | Laptop 15-da0xxx            | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Toshiba       | Satellite S55-A             | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| HP            | Unknown                     | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Apple         | MacBookPro8,1               | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Toshiba       | Satellite S55-A             | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | [a6f536ca3d](https://linux-hardware.org/?probe=a6f536ca3d) | Oct 25, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | [813bd112f8](https://linux-hardware.org/?probe=813bd112f8) | Oct 25, 2022 |
| MSI           | GF65 Thin 10SDR             | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| Dell          | Inspiron 3493               | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell          | G3 3579                     | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| Dell          | Inspiron 3543               | [68d1385b7e](https://linux-hardware.org/?probe=68d1385b7e) | Aug 28, 2022 |
| Toshiba       | Satellite C55-C             | [99faef3f00](https://linux-hardware.org/?probe=99faef3f00) | Aug 20, 2022 |
| Toshiba       | Satellite L655              | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Toshiba       | Satellite C55-C             | [992b4f4910](https://linux-hardware.org/?probe=992b4f4910) | Aug 06, 2022 |
| ASUSTek       | GL552VW                     | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Acer          | Aspire E5-576               | [a31ceb9a36](https://linux-hardware.org/?probe=a31ceb9a36) | Jul 31, 2022 |
| Acer          | Aspire R3-131T              | [f4efe63bf8](https://linux-hardware.org/?probe=f4efe63bf8) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | [a06c4e1f6b](https://linux-hardware.org/?probe=a06c4e1f6b) | Jul 13, 2022 |
| Deffad        | Unknown                     | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| Dell          | Inspiron 3520               | [b865370f11](https://linux-hardware.org/?probe=b865370f11) | Jun 28, 2022 |
| Lenovo        | ThinkPad P50 20EN001PUS     | [52ef9383a4](https://linux-hardware.org/?probe=52ef9383a4) | Jun 09, 2022 |
| Lenovo        | ThinkPad T440s 20ARS29U0... | [50de8ad2e9](https://linux-hardware.org/?probe=50de8ad2e9) | Jun 01, 2022 |
| Dell          | Latitude 7400               | [caf85903ad](https://linux-hardware.org/?probe=caf85903ad) | May 19, 2022 |
| Dell          | Inspiron 5565               | [d5a8629a31](https://linux-hardware.org/?probe=d5a8629a31) | May 19, 2022 |
| Lenovo        | ThinkPad L420 7829AA4       | [9c1bbe8cf2](https://linux-hardware.org/?probe=9c1bbe8cf2) | May 14, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [637af2dcc6](https://linux-hardware.org/?probe=637af2dcc6) | Apr 29, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| HP            | Pavilion Notebook           | [a1130d8070](https://linux-hardware.org/?probe=a1130d8070) | Apr 13, 2022 |
| Acer          | Nitro AN515-43              | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
| Dell          | Latitude E5500              | [13be4a0a1b](https://linux-hardware.org/?probe=13be4a0a1b) | Mar 16, 2022 |
| Dell          | Latitude E5500              | [d5f8fd7890](https://linux-hardware.org/?probe=d5f8fd7890) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | [b7b428082a](https://linux-hardware.org/?probe=b7b428082a) | Mar 05, 2022 |
| Dell          | XPS 13 9305                 | [8807d99cb4](https://linux-hardware.org/?probe=8807d99cb4) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [c0adf77f3f](https://linux-hardware.org/?probe=c0adf77f3f) | Feb 26, 2022 |
| Sony          | SVD13215PLB                 | [82c4287f85](https://linux-hardware.org/?probe=82c4287f85) | Feb 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [b355ea1ff3](https://linux-hardware.org/?probe=b355ea1ff3) | Feb 20, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [8468cd0da9](https://linux-hardware.org/?probe=8468cd0da9) | Feb 19, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [80e2f3c47e](https://linux-hardware.org/?probe=80e2f3c47e) | Feb 19, 2022 |
| Apple         | MacBookPro8,1               | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| HP            | Laptop 15-da0xxx            | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [dbc7cbcfe1](https://linux-hardware.org/?probe=dbc7cbcfe1) | Feb 07, 2022 |
| Toshiba       | Satellite L45-B             | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3f953ad7f3](https://linux-hardware.org/?probe=3f953ad7f3) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [eecedd12b2](https://linux-hardware.org/?probe=eecedd12b2) | Jan 14, 2022 |
| Dell          | Latitude 5490               | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | EliteBook 8460p             | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| Dell          | Inspiron 3595               | [1df662506b](https://linux-hardware.org/?probe=1df662506b) | Oct 27, 2021 |
| Apple         | MacBookPro8,1               | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| HP            | EliteBook 8460p             | [5bb3c9bc8b](https://linux-hardware.org/?probe=5bb3c9bc8b) | Oct 19, 2021 |
| Apple         | MacBookPro8,1               | [bfadd59ae5](https://linux-hardware.org/?probe=bfadd59ae5) | Oct 18, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Acer          | Aspire 5750                 | [ff12aa7481](https://linux-hardware.org/?probe=ff12aa7481) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| HP            | Laptop 15-da0xxx            | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Dell          | Latitude D620               | [1dc8e001f5](https://linux-hardware.org/?probe=1dc8e001f5) | Sep 28, 2021 |
| Apple         | MacBookPro8,1               | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| HP            | EliteBook 820 G1            | [00b3e62e2e](https://linux-hardware.org/?probe=00b3e62e2e) | Sep 10, 2021 |
| MSI           | GF75 Thin 9SD               | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| Olivetti      | CL133A                      | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| HP            | Pavilion g4                 | [3f01790d4e](https://linux-hardware.org/?probe=3f01790d4e) | Jul 21, 2021 |
| AZW           | GT-R                        | [115230aa47](https://linux-hardware.org/?probe=115230aa47) | Jul 19, 2021 |
| Olivetti      | CL133A                      | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| ASUSTek       | U46E                        | [720dec33c4](https://linux-hardware.org/?probe=720dec33c4) | Jul 14, 2021 |
| HP            | ProBook 6460b               | [b39eb9b256](https://linux-hardware.org/?probe=b39eb9b256) | Jul 13, 2021 |
| Dell          | G3 3590                     | [3781e31377](https://linux-hardware.org/?probe=3781e31377) | Jul 12, 2021 |
| Olivetti      | CL133A                      | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| HP            | EliteBook 8570p             | [ab19b80507](https://linux-hardware.org/?probe=ab19b80507) | Jun 09, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| HP            | Pavilion dv6000 (RP297UA... | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Dell          | Inspiron 5584               | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| Toshiba       | Satellite C845              | [e3b90e238b](https://linux-hardware.org/?probe=e3b90e238b) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | [6f3c2aa3be](https://linux-hardware.org/?probe=6f3c2aa3be) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | [8ccda2ce59](https://linux-hardware.org/?probe=8ccda2ce59) | May 24, 2021 |
| Toshiba       | Satellite C845              | [4d346e2691](https://linux-hardware.org/?probe=4d346e2691) | May 24, 2021 |
| Dell          | Inspiron 5584               | [5e2e76f838](https://linux-hardware.org/?probe=5e2e76f838) | May 20, 2021 |
| Acer          | Aspire A515-43              | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| Apple         | MacBookPro8,1               | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [93286a0d38](https://linux-hardware.org/?probe=93286a0d38) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [796f490bbb](https://linux-hardware.org/?probe=796f490bbb) | May 15, 2021 |
| Dell          | Inspiron 5584               | [1da876ea0b](https://linux-hardware.org/?probe=1da876ea0b) | May 06, 2021 |
| Dell          | Inspiron 5584               | [0216a041d2](https://linux-hardware.org/?probe=0216a041d2) | May 05, 2021 |
| HP            | Laptop 15-da0xxx            | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| Acer          | Aspire A515-43              | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP            | Pavilion dv6                | [a181ae8691](https://linux-hardware.org/?probe=a181ae8691) | Apr 30, 2021 |
| HP            | Pavilion dv6                | [d363966e4c](https://linux-hardware.org/?probe=d363966e4c) | Apr 30, 2021 |
| HP            | Pavilion dv6                | [204cd9c44f](https://linux-hardware.org/?probe=204cd9c44f) | Apr 30, 2021 |
| HP            | Pavilion dv6                | [e20fc33e2b](https://linux-hardware.org/?probe=e20fc33e2b) | Apr 29, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [3cca89aa74](https://linux-hardware.org/?probe=3cca89aa74) | Apr 28, 2021 |
| HP            | Laptop 15-da0xxx            | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [38c505f6bd](https://linux-hardware.org/?probe=38c505f6bd) | Apr 23, 2021 |
| Apple         | MacBook2,1                  | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| HP            | Laptop 15-da0xxx            | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e990abe7f1](https://linux-hardware.org/?probe=e990abe7f1) | Apr 11, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [41c14db0ef](https://linux-hardware.org/?probe=41c14db0ef) | Apr 11, 2021 |
| Dell          | G3 3590                     | [3c952dbc96](https://linux-hardware.org/?probe=3c952dbc96) | Mar 26, 2021 |
| Toshiba       | QOSMIO X775                 | [d8f82a3984](https://linux-hardware.org/?probe=d8f82a3984) | Mar 26, 2021 |
| HP            | OMEN by Laptop              | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| HP            | Pavilion g4                 | [1e7372e4f2](https://linux-hardware.org/?probe=1e7372e4f2) | Mar 01, 2021 |
| Toshiba       | Satellite C45-A             | [e00317dc4d](https://linux-hardware.org/?probe=e00317dc4d) | Mar 01, 2021 |
| Unknown       | Unknown                     | [941e941403](https://linux-hardware.org/?probe=941e941403) | Feb 27, 2021 |
| Dell          | Inspiron 5584               | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| Google        | Celes                       | [b30c090b2b](https://linux-hardware.org/?probe=b30c090b2b) | Feb 22, 2021 |
| Dell          | Inspiron 3558               | [41ba11dbb4](https://linux-hardware.org/?probe=41ba11dbb4) | Feb 18, 2021 |
| Dell          | Inspiron 5584               | [660afa073b](https://linux-hardware.org/?probe=660afa073b) | Feb 11, 2021 |
| Dell          | Inspiron 5584               | [840e0e2818](https://linux-hardware.org/?probe=840e0e2818) | Feb 04, 2021 |
| Dell          | Inspiron 5584               | [e10690d1d2](https://linux-hardware.org/?probe=e10690d1d2) | Feb 04, 2021 |
| HP            | Laptop 14-dq1xxx            | [84c932e071](https://linux-hardware.org/?probe=84c932e071) | Feb 02, 2021 |
| Dell          | Inspiron 5584               | [473419d486](https://linux-hardware.org/?probe=473419d486) | Jan 24, 2021 |
| Dell          | Inspiron 5584               | [738e03e488](https://linux-hardware.org/?probe=738e03e488) | Jan 23, 2021 |
| Dell          | Precision M4800             | [f24be700aa](https://linux-hardware.org/?probe=f24be700aa) | Jan 21, 2021 |
| Dell          | Precision M4800             | [316c7dd34b](https://linux-hardware.org/?probe=316c7dd34b) | Jan 21, 2021 |
| HP            | Laptop 14-bp0xx             | [4badbab2db](https://linux-hardware.org/?probe=4badbab2db) | Jan 19, 2021 |
| Dell          | Inspiron 5584               | [1a731e13e0](https://linux-hardware.org/?probe=1a731e13e0) | Jan 18, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6a0e9eff49](https://linux-hardware.org/?probe=6a0e9eff49) | Jan 16, 2021 |
| Dell          | Inspiron 5584               | [76fe08b67a](https://linux-hardware.org/?probe=76fe08b67a) | Jan 14, 2021 |
| Dell          | Inspiron 5584               | [8d9be2defd](https://linux-hardware.org/?probe=8d9be2defd) | Jan 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell          | Inspiron 5584               | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| HP            | Laptop 14-bp0xx             | [a481e8e9c0](https://linux-hardware.org/?probe=a481e8e9c0) | Dec 16, 2020 |
| HP            | Laptop 14-bp0xx             | [266b8d7543](https://linux-hardware.org/?probe=266b8d7543) | Dec 16, 2020 |
| MSI           | GE60 2OC\2OD\2OE            | [a305c14111](https://linux-hardware.org/?probe=a305c14111) | Dec 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| Dell          | Latitude 7480               | [2e569dcaed](https://linux-hardware.org/?probe=2e569dcaed) | Oct 22, 2020 |
| Dell          | Latitude 7480               | [1cc0a03f18](https://linux-hardware.org/?probe=1cc0a03f18) | Oct 22, 2020 |
| Dell          | XPS 15 9560                 | [9f10520397](https://linux-hardware.org/?probe=9f10520397) | Oct 11, 2020 |
| Dell          | G3 3590                     | [4c2ddd8b88](https://linux-hardware.org/?probe=4c2ddd8b88) | Oct 01, 2020 |
| Toshiba       | Satellite C55-B             | [6acb0908ff](https://linux-hardware.org/?probe=6acb0908ff) | Sep 18, 2020 |
| HP            | Unknown                     | [a446c81ca9](https://linux-hardware.org/?probe=a446c81ca9) | Sep 10, 2020 |
| HP            | EliteBook 8570p             | [48e494142e](https://linux-hardware.org/?probe=48e494142e) | Aug 27, 2020 |
| Toshiba       | Satellite X205              | [b0d5e7d0dd](https://linux-hardware.org/?probe=b0d5e7d0dd) | Aug 26, 2020 |
| Toshiba       | Satellite X205              | [45e52f3631](https://linux-hardware.org/?probe=45e52f3631) | Aug 26, 2020 |
| Acer          | Aspire 4739Z                | [44ec59d132](https://linux-hardware.org/?probe=44ec59d132) | Aug 11, 2020 |
| HP            | Pavilion dv2500             | [4bdd603282](https://linux-hardware.org/?probe=4bdd603282) | Aug 06, 2020 |
| HP            | Pavilion dv2500             | [4114f58581](https://linux-hardware.org/?probe=4114f58581) | Aug 06, 2020 |
| Dell          | Latitude E5440              | [9d31b1e38d](https://linux-hardware.org/?probe=9d31b1e38d) | Jul 29, 2020 |
| Dell          | G3 3590                     | [e2fa394ba6](https://linux-hardware.org/?probe=e2fa394ba6) | Jun 28, 2020 |
| Dell          | XPS 15 9560                 | [8119688776](https://linux-hardware.org/?probe=8119688776) | Jun 27, 2020 |
| Dell          | XPS 15 9560                 | [d2a2900148](https://linux-hardware.org/?probe=d2a2900148) | Jun 20, 2020 |
| Dell          | Inspiron 5559               | [4619502a6b](https://linux-hardware.org/?probe=4619502a6b) | May 28, 2020 |
| HP            | ProBook 455 G4              | [6b6fe8e0c1](https://linux-hardware.org/?probe=6b6fe8e0c1) | May 18, 2020 |
| HP            | 245 G4 Notebook PC          | [9311532f56](https://linux-hardware.org/?probe=9311532f56) | Apr 23, 2020 |
| HP            | 245 G4 Notebook PC          | [b662f230b2](https://linux-hardware.org/?probe=b662f230b2) | Apr 23, 2020 |
| HP            | Notebook                    | [5815277bb0](https://linux-hardware.org/?probe=5815277bb0) | Apr 22, 2020 |
| HP            | Laptop 15-da0xxx            | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [2f87bcd627](https://linux-hardware.org/?probe=2f87bcd627) | Apr 07, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [16ff51d343](https://linux-hardware.org/?probe=16ff51d343) | Apr 07, 2020 |
| Acer          | Aspire V3-471               | [024d5b0563](https://linux-hardware.org/?probe=024d5b0563) | Apr 06, 2020 |
| Dell          | G3 3590                     | [26a4f7e20b](https://linux-hardware.org/?probe=26a4f7e20b) | Mar 22, 2020 |
| Dell          | G3 3590                     | [96d9b68953](https://linux-hardware.org/?probe=96d9b68953) | Mar 21, 2020 |
| Toshiba       | Satellite C855D             | [9246f32b7e](https://linux-hardware.org/?probe=9246f32b7e) | Mar 01, 2020 |
| HP            | Pavilion Notebook           | [2bbf18e9e5](https://linux-hardware.org/?probe=2bbf18e9e5) | Feb 20, 2020 |
| HP            | Pavilion Notebook           | [68895d1461](https://linux-hardware.org/?probe=68895d1461) | Feb 20, 2020 |
| HP            | ProBook 6460b               | [121b074dd0](https://linux-hardware.org/?probe=121b074dd0) | Feb 19, 2020 |
| Dell          | Latitude 5500               | [3a7f8e19f1](https://linux-hardware.org/?probe=3a7f8e19f1) | Feb 17, 2020 |
| ASUSTek       | K52F                        | [9dde03d12c](https://linux-hardware.org/?probe=9dde03d12c) | Feb 13, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [9eb64d7269](https://linux-hardware.org/?probe=9eb64d7269) | Jan 17, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [8211b13acf](https://linux-hardware.org/?probe=8211b13acf) | Jan 17, 2020 |
| HP            | 240 G6 Notebook PC          | [73da3dccf1](https://linux-hardware.org/?probe=73da3dccf1) | Nov 14, 2019 |
| HP            | 240 G6 Notebook PC          | [efeee7f2fc](https://linux-hardware.org/?probe=efeee7f2fc) | Nov 14, 2019 |
| System76      | Lemur                       | [a9cc263cb4](https://linux-hardware.org/?probe=a9cc263cb4) | Oct 09, 2019 |
| HP            | ProBook 450 G2              | [c7959cccb3](https://linux-hardware.org/?probe=c7959cccb3) | Sep 30, 2019 |
| HP            | Notebook                    | [163fc3e9dd](https://linux-hardware.org/?probe=163fc3e9dd) | Sep 14, 2019 |
| ASUSTek       | Strix 17 GL703GE            | [c34161a66d](https://linux-hardware.org/?probe=c34161a66d) | Sep 02, 2019 |
| System76      | Lemur                       | [01bbf99115](https://linux-hardware.org/?probe=01bbf99115) | Sep 02, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | [47182bd3e3](https://linux-hardware.org/?probe=47182bd3e3) | Sep 01, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | [2105fa4def](https://linux-hardware.org/?probe=2105fa4def) | Sep 01, 2019 |
| HP            | Notebook                    | [b7e9995b67](https://linux-hardware.org/?probe=b7e9995b67) | Aug 18, 2019 |
| HP            | Notebook                    | [273d0bcc2e](https://linux-hardware.org/?probe=273d0bcc2e) | Aug 18, 2019 |
| Dell          | Venue 11 Pro 7130 vPro      | [2e5b92af00](https://linux-hardware.org/?probe=2e5b92af00) | Aug 17, 2019 |
| Dell          | Latitude E5450              | [3336801ccf](https://linux-hardware.org/?probe=3336801ccf) | Aug 10, 2019 |
| Toshiba       | Satellite A305D             | [ebf0a9c89e](https://linux-hardware.org/?probe=ebf0a9c89e) | Aug 08, 2019 |
| Acer          | SW5-017P                    | [fbf9b74a34](https://linux-hardware.org/?probe=fbf9b74a34) | Jul 29, 2019 |
| Dell          | Latitude 5480               | [f488cfd08f](https://linux-hardware.org/?probe=f488cfd08f) | Jun 22, 2019 |
| ASUSTek       | Strix 17 GL703GE            | [328975f3a5](https://linux-hardware.org/?probe=328975f3a5) | May 15, 2019 |
| Dell          | Latitude 5480               | [694ca16d49](https://linux-hardware.org/?probe=694ca16d49) | May 04, 2019 |
| Purism        | Librem 15 v3                | [00259367c8](https://linux-hardware.org/?probe=00259367c8) | Oct 29, 2018 |
| Purism        | Librem 15 v3                | [c5e1ab1520](https://linux-hardware.org/?probe=c5e1ab1520) | Oct 29, 2018 |
| ASUSTek       | X555LAB                     | [243803142a](https://linux-hardware.org/?probe=243803142a) | Aug 01, 2018 |
| Toshiba       | Satellite C645D             | [9d50eb7fdb](https://linux-hardware.org/?probe=9d50eb7fdb) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 14        | 7.33%   |
| Ubuntu 22.04                 | 12        | 6.28%   |
| Ubuntu 18.04                 | 12        | 6.28%   |
| OpenMandriva 4.2             | 7         | 3.66%   |
| Debian 12                    | 7         | 3.66%   |
| Zorin 16                     | 6         | 3.14%   |
| Ubuntu 19.04                 | 4         | 2.09%   |
| OpenMandriva 4.3             | 4         | 2.09%   |
| Debian 11                    | 4         | 2.09%   |
| Ubuntu 23.04                 | 3         | 1.57%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.57%   |
| OpenMandriva 23.08           | 3         | 1.57%   |
| Lubuntu 22.10                | 3         | 1.57%   |
| Lubuntu 22.04                | 3         | 1.57%   |
| Lubuntu 21.10                | 3         | 1.57%   |
| Lubuntu 21.04                | 3         | 1.57%   |
| Fedora 38                    | 3         | 1.57%   |
| Xubuntu 20.04                | 2         | 1.05%   |
| Ubuntu Studio 20.04          | 2         | 1.05%   |
| Ubuntu 21.04                 | 2         | 1.05%   |
| Pop!_OS 22.04                | 2         | 1.05%   |
| OpenMandriva 23.03           | 2         | 1.05%   |
| OpenMandriva 23.01           | 2         | 1.05%   |
| Manjaro 20.2.1               | 2         | 1.05%   |
| Lubuntu 23.10                | 2         | 1.05%   |
| Lubuntu 23.04                | 2         | 1.05%   |
| Linux Mint 21.2              | 2         | 1.05%   |
| Linux Mint 20.3              | 2         | 1.05%   |
| Linux Mint 20.1              | 2         | 1.05%   |
| Linux Mint 20                | 2         | 1.05%   |
| Kubuntu 22.04                | 2         | 1.05%   |
| KDE neon 20.04               | 2         | 1.05%   |
| Fedora 36                    | 2         | 1.05%   |
| Debian 10                    | 2         | 1.05%   |
| Zorin 15                     | 1         | 0.52%   |
| Xubuntu 18.04                | 1         | 0.52%   |
| UbuntuDDE 20.04              | 1         | 0.52%   |
| Ubuntu Unity 18.04           | 1         | 0.52%   |
| Ubuntu Unity 16.04           | 1         | 0.52%   |
| Ubuntu MATE 22.04            | 1         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 49        | 28.82%  |
| OpenMandriva  | 17        | 10%     |
| Debian        | 14        | 8.24%   |
| Linux Mint    | 12        | 7.06%   |
| Fedora        | 10        | 5.88%   |
| Zorin         | 7         | 4.12%   |
| Manjaro       | 6         | 3.53%   |
| Lubuntu       | 6         | 3.53%   |
| Pop!_OS       | 4         | 2.35%   |
| Kubuntu       | 4         | 2.35%   |
| Xubuntu       | 3         | 1.76%   |
| ROSA          | 3         | 1.76%   |
| openSUSE      | 3         | 1.76%   |
| KDE neon      | 3         | 1.76%   |
| Ubuntu Unity  | 2         | 1.18%   |
| Ubuntu Studio | 2         | 1.18%   |
| Ubuntu MATE   | 2         | 1.18%   |
| Parrot        | 2         | 1.18%   |
| Kali          | 2         | 1.18%   |
| Endless       | 2         | 1.18%   |
| UbuntuDDE     | 1         | 0.59%   |
| Ubuntu Budgie | 1         | 0.59%   |
| Reborn OS     | 1         | 0.59%   |
| PureOS        | 1         | 0.59%   |
| Peppermint    | 1         | 0.59%   |
| Nobara        | 1         | 0.59%   |
| Mageia        | 1         | 0.59%   |
| LMDE          | 1         | 0.59%   |
| LinuxFX       | 1         | 0.59%   |
| Elementary    | 1         | 0.59%   |
| Crystal Linux | 1         | 0.59%   |
| Clear Linux   | 1         | 0.59%   |
| ChimeraOS     | 1         | 0.59%   |
| BigLinux      | 1         | 0.59%   |
| ArcoLinux     | 1         | 0.59%   |
| Arch          | 1         | 0.59%   |
| ALT Linux     | 1         | 0.59%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 7         | 3.33%   |
| 5.16.7-desktop-1omv4003  | 4         | 1.9%    |
| 5.0.0-23-generic         | 4         | 1.9%    |
| 6.4.11-desktop-1omv2390  | 3         | 1.43%   |
| 5.4.0-77-generic         | 3         | 1.43%   |
| 5.4.0-42-generic         | 3         | 1.43%   |
| 5.19.0-32-generic        | 3         | 1.43%   |
| 5.19.0-26-generic        | 3         | 1.43%   |
| 5.13.0-16-generic        | 3         | 1.43%   |
| 5.11.0-27-generic        | 3         | 1.43%   |
| 5.0.0-25-generic         | 3         | 1.43%   |
| 6.5.0-5-generic          | 2         | 0.95%   |
| 6.3.8-200.fc38.x86_64    | 2         | 0.95%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.95%   |
| 6.2.0-20-generic         | 2         | 0.95%   |
| 6.2.0-18-generic         | 2         | 0.95%   |
| 6.1.0-10-amd64           | 2         | 0.95%   |
| 6.0.6-76060006-generic   | 2         | 0.95%   |
| 5.9.16-1-MANJARO         | 2         | 0.95%   |
| 5.8.0-50-generic         | 2         | 0.95%   |
| 5.4.0-21-generic         | 2         | 0.95%   |
| 5.3.0-40-generic         | 2         | 0.95%   |
| 5.3.0-28-generic         | 2         | 0.95%   |
| 5.15.0-91-generic        | 2         | 0.95%   |
| 5.15.0-83-generic        | 2         | 0.95%   |
| 5.15.0-58-generic        | 2         | 0.95%   |
| 5.15.0-52-generic        | 2         | 0.95%   |
| 5.15.0-41-generic        | 2         | 0.95%   |
| 5.13.0-35-generic        | 2         | 0.95%   |
| 5.13.0-20-generic        | 2         | 0.95%   |
| 5.11.0-16-generic        | 2         | 0.95%   |
| 4.15.0-112-generic       | 2         | 0.95%   |
| 6.6.6-1-default          | 1         | 0.48%   |
| 6.6.2-desktop-1omv2390   | 1         | 0.48%   |
| 6.6.2-custom             | 1         | 0.48%   |
| 6.5.9-200.fc38.x86_64    | 1         | 0.48%   |
| 6.5.11-300.fc39.x86_64   | 1         | 0.48%   |
| 6.5.0-7-generic          | 1         | 0.48%   |
| 6.5.0-14-generic         | 1         | 0.48%   |
| 6.5.0-0.deb12.1-amd64    | 1         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 23        | 11.73%  |
| 5.15.0  | 22        | 11.22%  |
| 5.11.0  | 11        | 5.61%   |
| 5.19.0  | 10        | 5.1%    |
| 5.13.0  | 8         | 4.08%   |
| 5.0.0   | 8         | 4.08%   |
| 6.2.0   | 7         | 3.57%   |
| 6.1.0   | 7         | 3.57%   |
| 5.3.0   | 7         | 3.57%   |
| 5.10.14 | 7         | 3.57%   |
| 5.10.0  | 7         | 3.57%   |
| 6.5.0   | 5         | 2.55%   |
| 5.8.0   | 5         | 2.55%   |
| 4.15.0  | 5         | 2.55%   |
| 5.16.7  | 4         | 2.04%   |
| 6.4.11  | 3         | 1.53%   |
| 6.6.2   | 2         | 1.02%   |
| 6.3.8   | 2         | 1.02%   |
| 6.3.6   | 2         | 1.02%   |
| 6.2.6   | 2         | 1.02%   |
| 6.1.1   | 2         | 1.02%   |
| 6.0.6   | 2         | 1.02%   |
| 5.9.16  | 2         | 1.02%   |
| 5.18.13 | 2         | 1.02%   |
| 4.19.0  | 2         | 1.02%   |
| 6.6.6   | 1         | 0.51%   |
| 6.5.9   | 1         | 0.51%   |
| 6.5.11  | 1         | 0.51%   |
| 6.4.6   | 1         | 0.51%   |
| 6.3.4   | 1         | 0.51%   |
| 6.2.15  | 1         | 0.51%   |
| 6.1.6   | 1         | 0.51%   |
| 6.1.4   | 1         | 0.51%   |
| 6.1.20  | 1         | 0.51%   |
| 6.0.8   | 1         | 0.51%   |
| 6.0.7   | 1         | 0.51%   |
| 5.9.11  | 1         | 0.51%   |
| 5.8.6   | 1         | 0.51%   |
| 5.7.0   | 1         | 0.51%   |
| 5.2.11  | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 11.79%  |
| 5.15    | 23        | 11.79%  |
| 5.10    | 18        | 9.23%   |
| 5.11    | 14        | 7.18%   |
| 5.19    | 13        | 6.67%   |
| 6.1     | 12        | 6.15%   |
| 6.2     | 10        | 5.13%   |
| 5.0     | 9         | 4.62%   |
| 5.13    | 8         | 4.1%    |
| 6.5     | 7         | 3.59%   |
| 5.3     | 7         | 3.59%   |
| 5.8     | 6         | 3.08%   |
| 6.3     | 5         | 2.56%   |
| 4.15    | 5         | 2.56%   |
| 6.4     | 4         | 2.05%   |
| 6.0     | 4         | 2.05%   |
| 5.16    | 4         | 2.05%   |
| 6.6     | 3         | 1.54%   |
| 5.9     | 3         | 1.54%   |
| 5.18    | 3         | 1.54%   |
| 5.12    | 3         | 1.54%   |
| 4.19    | 3         | 1.54%   |
| 4.18    | 2         | 1.03%   |
| 5.7     | 1         | 0.51%   |
| 5.2     | 1         | 0.51%   |
| 5.17    | 1         | 0.51%   |
| 5.14    | 1         | 0.51%   |
| 4.9     | 1         | 0.51%   |
| 4.1     | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 159       | 98.76%  |
| i686   | 2         | 1.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 77        | 46.11%  |
| KDE5       | 29        | 17.37%  |
| Unknown    | 15        | 8.98%   |
| XFCE       | 13        | 7.78%   |
| MATE       | 7         | 4.19%   |
| LXQt       | 7         | 4.19%   |
| X-Cinnamon | 6         | 3.59%   |
| KDE        | 3         | 1.8%    |
| Unity      | 2         | 1.2%    |
| i3         | 2         | 1.2%    |
| Pantheon   | 1         | 0.6%    |
| onyx:GNOME | 1         | 0.6%    |
| LXDE       | 1         | 0.6%    |
| Deepin     | 1         | 0.6%    |
| Cinnamon   | 1         | 0.6%    |
| Budgie     | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 114       | 69.94%  |
| Wayland | 39        | 23.93%  |
| Unknown | 8         | 4.91%   |
| Tty     | 2         | 1.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 65        | 39.63%  |
| SDDM    | 35        | 21.34%  |
| GDM3    | 24        | 14.63%  |
| LightDM | 17        | 10.37%  |
| GDM     | 15        | 9.15%   |
| TDM     | 8         | 4.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 76        | 46.34%  |
| es_CR   | 56        | 34.15%  |
| Unknown | 14        | 8.54%   |
| es_ES   | 10        | 6.1%    |
| es_MX   | 3         | 1.83%   |
| C       | 2         | 1.22%   |
| fr_FR   | 1         | 0.61%   |
| es_EC   | 1         | 0.61%   |
| en_AG   | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 87        | 52.41%  |
| BIOS | 79        | 47.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 118       | 71.95%  |
| Btrfs   | 18        | 10.98%  |
| Overlay | 17        | 10.37%  |
| Tmpfs   | 6         | 3.66%   |
| Unknown | 4         | 2.44%   |
| Xfs     | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 74        | 45.68%  |
| GPT     | 68        | 41.98%  |
| MBR     | 20        | 12.35%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 147       | 89.63%  |
| Yes       | 17        | 10.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 103       | 63.19%  |
| Yes       | 60        | 36.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 39        | 24.22%  |
| Dell                | 33        | 20.5%   |
| Lenovo              | 26        | 16.15%  |
| Toshiba             | 14        | 8.7%    |
| ASUSTek Computer    | 13        | 8.07%   |
| Acer                | 12        | 7.45%   |
| Apple               | 7         | 4.35%   |
| MSI                 | 4         | 2.48%   |
| Sony                | 2         | 1.24%   |
| Google              | 2         | 1.24%   |
| System76            | 1         | 0.62%   |
| Samsung Electronics | 1         | 0.62%   |
| Purism              | 1         | 0.62%   |
| Olivetti            | 1         | 0.62%   |
| HUAWEI              | 1         | 0.62%   |
| GPU Company         | 1         | 0.62%   |
| Deffad              | 1         | 0.62%   |
| AZW                 | 1         | 0.62%   |
| Unknown             | 1         | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Apple MacBookPro8,1                          | 4         | 2.48%   |
| Unknown                                      | 4         | 2.48%   |
| HP Notebook                                  | 3         | 1.86%   |
| HP Laptop 15-da0xxx                          | 3         | 1.86%   |
| Dell Inspiron 5584                           | 3         | 1.86%   |
| HP ProBook 6460b                             | 2         | 1.24%   |
| HP Pavilion Notebook                         | 2         | 1.24%   |
| HP Pavilion g4                               | 2         | 1.24%   |
| Toshiba Satellite X205                       | 1         | 0.62%   |
| Toshiba Satellite S55-A                      | 1         | 0.62%   |
| Toshiba Satellite L845                       | 1         | 0.62%   |
| Toshiba Satellite L755                       | 1         | 0.62%   |
| Toshiba Satellite L655                       | 1         | 0.62%   |
| Toshiba Satellite L45-B                      | 1         | 0.62%   |
| Toshiba Satellite C855D                      | 1         | 0.62%   |
| Toshiba Satellite C845                       | 1         | 0.62%   |
| Toshiba Satellite C645D                      | 1         | 0.62%   |
| Toshiba Satellite C55-C                      | 1         | 0.62%   |
| Toshiba Satellite C55-B                      | 1         | 0.62%   |
| Toshiba Satellite C45-A                      | 1         | 0.62%   |
| Toshiba Satellite A305D                      | 1         | 0.62%   |
| Toshiba QOSMIO X775                          | 1         | 0.62%   |
| System76 Lemur                               | 1         | 0.62%   |
| Sony SVE14123CLW                             | 1         | 0.62%   |
| Sony SVD13215PLB                             | 1         | 0.62%   |
| Samsung 930X2K/931X2K                        | 1         | 0.62%   |
| Purism Librem 15 v3                          | 1         | 0.62%   |
| Olivetti CL133A                              | 1         | 0.62%   |
| MSI Katana 15 B13VGK                         | 1         | 0.62%   |
| MSI GF75 Thin 9SD                            | 1         | 0.62%   |
| MSI GF65 Thin 10SDR                          | 1         | 0.62%   |
| MSI GE60 2OC\2OD\2OE                         | 1         | 0.62%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y50010US | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1EY00     | 1         | 0.62%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US     | 1         | 0.62%   |
| Lenovo ThinkPad T60 1952F75                  | 1         | 0.62%   |
| Lenovo ThinkPad T470 W10DG 20JM000CUS        | 1         | 0.62%   |
| Lenovo ThinkPad T440s 20ARS29U00             | 1         | 0.62%   |
| Lenovo ThinkPad T420 4236DA4                 | 1         | 0.62%   |
| Lenovo ThinkPad P53 20QNS00P00               | 1         | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 18        | 11.18%  |
| Toshiba Satellite      | 13        | 8.07%   |
| Dell Inspiron          | 13        | 8.07%   |
| Dell Latitude          | 12        | 7.45%   |
| Acer Aspire            | 10        | 6.21%   |
| HP Pavilion            | 9         | 5.59%   |
| HP Laptop              | 7         | 4.35%   |
| HP EliteBook           | 7         | 4.35%   |
| Lenovo IdeaPad         | 6         | 3.73%   |
| HP ProBook             | 5         | 3.11%   |
| ASUS VivoBook          | 4         | 2.48%   |
| Apple MacBookPro8      | 4         | 2.48%   |
| Unknown                | 4         | 2.48%   |
| HP Notebook            | 3         | 1.86%   |
| Dell XPS               | 3         | 1.86%   |
| Dell G3                | 2         | 1.24%   |
| Toshiba QOSMIO         | 1         | 0.62%   |
| System76 Lemur         | 1         | 0.62%   |
| Sony SVE14123CLW       | 1         | 0.62%   |
| Sony SVD13215PLB       | 1         | 0.62%   |
| Samsung 930X2K         | 1         | 0.62%   |
| Purism Librem          | 1         | 0.62%   |
| Olivetti CL133A        | 1         | 0.62%   |
| MSI Katana             | 1         | 0.62%   |
| MSI GF75               | 1         | 0.62%   |
| MSI GF65               | 1         | 0.62%   |
| MSI GE60               | 1         | 0.62%   |
| Lenovo Legion          | 1         | 0.62%   |
| Lenovo B590            | 1         | 0.62%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.62%   |
| HP OMEN                | 1         | 0.62%   |
| HP Mini                | 1         | 0.62%   |
| HP G60                 | 1         | 0.62%   |
| HP ENVY                | 1         | 0.62%   |
| HP 245                 | 1         | 0.62%   |
| HP 240                 | 1         | 0.62%   |
| GPU Company GWTN141-10 | 1         | 0.62%   |
| Google Snappy          | 1         | 0.62%   |
| Google Celes           | 1         | 0.62%   |
| Dell Venue             | 1         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 21        | 13.04%  |
| 2011 | 18        | 11.18%  |
| 2018 | 15        | 9.32%   |
| 2012 | 14        | 8.7%    |
| 2020 | 13        | 8.07%   |
| 2017 | 10        | 6.21%   |
| 2016 | 10        | 6.21%   |
| 2015 | 10        | 6.21%   |
| 2014 | 10        | 6.21%   |
| 2021 | 9         | 5.59%   |
| 2013 | 8         | 4.97%   |
| 2008 | 5         | 3.11%   |
| 2009 | 4         | 2.48%   |
| 2023 | 3         | 1.86%   |
| 2010 | 3         | 1.86%   |
| 2007 | 3         | 1.86%   |
| 2006 | 3         | 1.86%   |
| 2022 | 2         | 1.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 161       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 147       | 91.3%   |
| Enabled  | 14        | 8.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 158       | 98.14%  |
| Yes  | 3         | 1.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 48        | 29.09%  |
| 3.01-4.0    | 35        | 21.21%  |
| 8.01-16.0   | 33        | 20%     |
| 16.01-24.0  | 24        | 14.55%  |
| 32.01-64.0  | 10        | 6.06%   |
| 24.01-32.0  | 4         | 2.42%   |
| 1.01-2.0    | 4         | 2.42%   |
| 2.01-3.0    | 3         | 1.82%   |
| 64.01-256.0 | 3         | 1.82%   |
| 0.51-1.0    | 1         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 72        | 40.68%  |
| 2.01-3.0   | 46        | 25.99%  |
| 4.01-8.0   | 23        | 12.99%  |
| 3.01-4.0   | 22        | 12.43%  |
| 8.01-16.0  | 6         | 3.39%   |
| 0.51-1.0   | 6         | 3.39%   |
| 16.01-24.0 | 2         | 1.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 123       | 76.4%   |
| 2      | 35        | 21.74%  |
| 3      | 3         | 1.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 55.9%   |
| Yes       | 71        | 44.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 85.09%  |
| No        | 24        | 14.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 98.14%  |
| No        | 3         | 1.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 74.69%  |
| No        | 41        | 25.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Costa Rica | 161       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San José     | 72        | 40%     |
| Heredia       | 28        | 15.56%  |
| Alajuela      | 15        | 8.33%   |
| Cartago       | 6         | 3.33%   |
| Quesada       | 5         | 2.78%   |
| Grecia        | 5         | 2.78%   |
| Rio Segundo   | 4         | 2.22%   |
| Puntarenas    | 4         | 2.22%   |
| Escazu        | 4         | 2.22%   |
| San Ramon     | 3         | 1.67%   |
| Siquirres     | 2         | 1.11%   |
| Santa Cruz    | 2         | 1.11%   |
| Perez Zeledon | 2         | 1.11%   |
| Naranjo       | 2         | 1.11%   |
| Esparza       | 2         | 1.11%   |
| Colon         | 2         | 1.11%   |
| Bagaces       | 2         | 1.11%   |
| Zarcero       | 1         | 0.56%   |
| Tres Rios     | 1         | 0.56%   |
| Santo Domingo | 1         | 0.56%   |
| Santiago      | 1         | 0.56%   |
| Santa Fe      | 1         | 0.56%   |
| San Rafael    | 1         | 0.56%   |
| San Pedro     | 1         | 0.56%   |
| San Pablo     | 1         | 0.56%   |
| San Juan      | 1         | 0.56%   |
| San Francisco | 1         | 0.56%   |
| San Felipe    | 1         | 0.56%   |
| Quepos        | 1         | 0.56%   |
| Pavas         | 1         | 0.56%   |
| Palmares      | 1         | 0.56%   |
| Nosara        | 1         | 0.56%   |
| Liberia       | 1         | 0.56%   |
| Guapiles      | 1         | 0.56%   |
| Guacima       | 1         | 0.56%   |
| Curridabat    | 1         | 0.56%   |
| Alpes         | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 26        | 40     | 13.33%  |
| Toshiba                     | 24        | 29     | 12.31%  |
| Seagate                     | 21        | 29     | 10.77%  |
| Samsung Electronics         | 21        | 31     | 10.77%  |
| Kingston                    | 13        | 17     | 6.67%   |
| Intel                       | 12        | 32     | 6.15%   |
| Unknown                     | 9         | 13     | 4.62%   |
| HGST                        | 9         | 10     | 4.62%   |
| A-DATA Technology           | 8         | 8      | 4.1%    |
| SK hynix                    | 5         | 11     | 2.56%   |
| SanDisk                     | 5         | 5      | 2.56%   |
| Patriot                     | 5         | 5      | 2.56%   |
| Micron Technology           | 5         | 6      | 2.56%   |
| Crucial                     | 5         | 5      | 2.56%   |
| Team                        | 3         | 3      | 1.54%   |
| Netac                       | 3         | 3      | 1.54%   |
| KIOXIA                      | 2         | 2      | 1.03%   |
| Kingston Technology Company | 2         | 2      | 1.03%   |
| JMicron Technology          | 2         | 2      | 1.03%   |
| Hitachi                     | 2         | 3      | 1.03%   |
| Zheino                      | 1         | 1      | 0.51%   |
| Wibtek                      | 1         | 1      | 0.51%   |
| UMIS                        | 1         | 1      | 0.51%   |
| Transcend                   | 1         | 1      | 0.51%   |
| Silicon Motion              | 1         | 1      | 0.51%   |
| Mushkin                     | 1         | 1      | 0.51%   |
| LITEONIT                    | 1         | 1      | 0.51%   |
| LITEON                      | 1         | 1      | 0.51%   |
| Gigabyte Technology         | 1         | 1      | 0.51%   |
| Fujitsu                     | 1         | 1      | 0.51%   |
| Dell                        | 1         | 1      | 0.51%   |
| BP4                         | 1         | 1      | 0.51%   |
| Unknown                     | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                          | 6         | 2.91%   |
| Toshiba MQ01ABD100 1TB                            | 6         | 2.91%   |
| Seagate ST1000LM035-1RK172 1TB                    | 5         | 2.43%   |
| Kingston SA400S37240G 240GB SSD                   | 4         | 1.94%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 3         | 1.46%   |
| Toshiba KBG30ZMS256G NVMe 256GB                   | 3         | 1.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 3         | 1.46%   |
| Intel SSDSC2BF180A4H 180GB                        | 3         | 1.46%   |
| Intel SSDSA2CW300G3 304GB                         | 3         | 1.46%   |
| HGST HTS541010A9E680 1TB                          | 3         | 1.46%   |
| WDC WD20SPZX-08UA7 2TB                            | 2         | 0.97%   |
| Unknown MMC Card  128GB                           | 2         | 0.97%   |
| Toshiba NVMe SSD Drive 256GB                      | 2         | 0.97%   |
| SK hynix NVMe SSD Drive 128GB                     | 2         | 0.97%   |
| Seagate ST9500325AS 500GB                         | 2         | 0.97%   |
| Seagate ST500LM021-1KJ152 500GB                   | 2         | 0.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 0.97%   |
| Netac SSD 120GB                                   | 2         | 0.97%   |
| Kingston SV300S37A120G 120GB SSD                  | 2         | 0.97%   |
| Kingston SA400S37960G 960GB SSD                   | 2         | 0.97%   |
| JMicron Generic 8GB                               | 2         | 0.97%   |
| Intel SSDSC2MH250A2 250GB                         | 2         | 0.97%   |
| HGST HTS541075A9E680 752GB                        | 2         | 0.97%   |
| Zheino CHN 25SATAA3 240 240GB                     | 1         | 0.49%   |
| Wibtek W800S 512GB                                | 1         | 0.49%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                  | 1         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 1         | 0.49%   |
| WDC WDS120G1G0B-00RC30 120GB SSD                  | 1         | 0.49%   |
| WDC WD800BEVT-75ZCT2 80GB                         | 1         | 0.49%   |
| WDC WD7500BPVT-22HXZT3 752GB                      | 1         | 0.49%   |
| WDC WD5000LPVX-80V0TT0 500GB                      | 1         | 0.49%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 1         | 0.49%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 1         | 0.49%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 1         | 0.49%   |
| WDC WD5000BPKT-60PK4T0 500GB                      | 1         | 0.49%   |
| WDC WD3200BPVT-22JJ5T0 320GB                      | 1         | 0.49%   |
| WDC WD1600BEVT-75A23T0 160GB                      | 1         | 0.49%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 0.49%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 1         | 0.49%   |
| WDC WD10SPZX-08Z10 1TB                            | 1         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Toshiba            | 21        | 22     | 29.17%  |
| Seagate            | 20        | 28     | 27.78%  |
| WDC                | 17        | 20     | 23.61%  |
| HGST               | 9         | 10     | 12.5%   |
| JMicron Technology | 2         | 2      | 2.78%   |
| Hitachi            | 2         | 3      | 2.78%   |
| Fujitsu            | 1         | 1      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 12        | 12     | 16.9%   |
| Intel               | 8         | 22     | 11.27%  |
| WDC                 | 7         | 15     | 9.86%   |
| Samsung Electronics | 7         | 16     | 9.86%   |
| A-DATA Technology   | 7         | 7      | 9.86%   |
| Patriot             | 5         | 5      | 7.04%   |
| Micron Technology   | 4         | 4      | 5.63%   |
| Crucial             | 4         | 4      | 5.63%   |
| Team                | 3         | 3      | 4.23%   |
| SanDisk             | 3         | 3      | 4.23%   |
| Netac               | 3         | 3      | 4.23%   |
| Wibtek              | 1         | 1      | 1.41%   |
| Transcend           | 1         | 1      | 1.41%   |
| Seagate             | 1         | 1      | 1.41%   |
| Mushkin             | 1         | 1      | 1.41%   |
| LITEONIT            | 1         | 1      | 1.41%   |
| LITEON              | 1         | 1      | 1.41%   |
| Gigabyte Technology | 1         | 1      | 1.41%   |
| BP4                 | 1         | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 71        | 86     | 37.57%  |
| SSD     | 68        | 102    | 35.98%  |
| NVMe    | 39        | 66     | 20.63%  |
| MMC     | 9         | 13     | 4.76%   |
| Unknown | 2         | 2      | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 131       | 186    | 71.58%  |
| NVMe | 38        | 65     | 20.77%  |
| MMC  | 9         | 13     | 4.92%   |
| SAS  | 5         | 5      | 2.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 114    | 61.31%  |
| 0.51-1.0   | 44        | 64     | 32.12%  |
| 1.01-2.0   | 9         | 10     | 6.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 50        | 29.41%  |
| 251-500        | 34        | 20%     |
| 501-1000       | 28        | 16.47%  |
| 1-20           | 15        | 8.82%   |
| 1001-2000      | 12        | 7.06%   |
| 51-100         | 11        | 6.47%   |
| 21-50          | 9         | 5.29%   |
| More than 3000 | 4         | 2.35%   |
| 2001-3000      | 4         | 2.35%   |
| Unknown        | 3         | 1.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 78        | 43.58%  |
| 21-50     | 32        | 17.88%  |
| 51-100    | 23        | 12.85%  |
| 101-250   | 20        | 11.17%  |
| 251-500   | 14        | 7.82%   |
| 501-1000  | 8         | 4.47%   |
| Unknown   | 3         | 1.68%   |
| 1001-2000 | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 6.25%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 6.25%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 6.25%   |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 6.25%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 6.25%   |
| Seagate ST9320310AS 320GB                           | 1         | 1      | 6.25%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 6.25%   |
| Netac SSD 120GB                                     | 1         | 1      | 6.25%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 6.25%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 6.25%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 6.25%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 6.25%   |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 5         | 5      | 31.25%  |
| Seagate           | 3         | 3      | 18.75%  |
| WDC               | 2         | 2      | 12.5%   |
| HGST              | 2         | 2      | 12.5%   |
| Netac             | 1         | 1      | 6.25%   |
| Micron Technology | 1         | 1      | 6.25%   |
| Intel             | 1         | 1      | 6.25%   |
| Hitachi           | 1         | 2      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 38.46%  |
| Seagate | 3         | 3      | 23.08%  |
| WDC     | 2         | 2      | 15.38%  |
| HGST    | 2         | 2      | 15.38%  |
| Hitachi | 1         | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 14     | 81.25%  |
| SSD  | 3         | 3      | 18.75%  |

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
| Detected | 88        | 142    | 52.38%  |
| Works    | 64        | 110    | 38.1%   |
| Malfunc  | 16        | 17     | 9.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 121       | 65.41%  |
| AMD                          | 21        | 11.35%  |
| Samsung Electronics          | 14        | 7.57%   |
| SanDisk                      | 5         | 2.7%    |
| SK hynix                     | 4         | 2.16%   |
| Toshiba America Info Systems | 3         | 1.62%   |
| Kingston Technology Company  | 3         | 1.62%   |
| Nvidia                       | 2         | 1.08%   |
| Micron Technology            | 2         | 1.08%   |
| KIOXIA                       | 2         | 1.08%   |
| ASMedia Technology           | 2         | 1.08%   |
| Union Memory (Shenzhen)      | 1         | 0.54%   |
| Solidigm                     | 1         | 0.54%   |
| Silicon Motion               | 1         | 0.54%   |
| Realtek Semiconductor        | 1         | 0.54%   |
| Micron/Crucial Technology    | 1         | 0.54%   |
| ADATA Technology             | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 18        | 8.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 16        | 7.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 15        | 7.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 14        | 6.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 12        | 5.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 4.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 8         | 3.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 2.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 5         | 2.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 2.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 1.99%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.99%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 4         | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 1.99%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                    | 3         | 1.49%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 3         | 1.49%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 3         | 1.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.49%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 1%      |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                              | 2         | 1%      |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                  | 2         | 1%      |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 1%      |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                       | 2         | 1%      |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 1%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1%      |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 1%      |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                          | 2         | 1%      |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                                  | 1         | 0.5%    |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]                                   | 1         | 0.5%    |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 1         | 0.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 1         | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 1         | 0.5%    |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                          | 1         | 0.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.5%    |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                      | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 118       | 62.43%  |
| NVMe | 39        | 20.63%  |
| RAID | 16        | 8.47%   |
| IDE  | 16        | 8.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 135       | 83.85%  |
| AMD    | 26        | 16.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz               | 6         | 3.73%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 4         | 2.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 4         | 2.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 4         | 2.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 3         | 1.86%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 3         | 1.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 3         | 1.86%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 3         | 1.86%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 3         | 1.86%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 3         | 1.86%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 1.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 1.24%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 1.24%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 2         | 1.24%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.24%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 1.24%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 1.24%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 1.24%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 2         | 1.24%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 2         | 1.24%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 2         | 1.24%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 2         | 1.24%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 2         | 1.24%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 1.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.24%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 1.24%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 2         | 1.24%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz            | 1         | 0.62%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 0.62%   |
| Intel Pentium CPU P6100 @ 2.00GHz               | 1         | 0.62%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.62%   |
| Intel Genuine CPU U4100 @ 1.30GHz               | 1         | 0.62%   |
| Intel Genuine CPU T2060 @ 1.60GHz               | 1         | 0.62%   |
| Intel Core M-5Y31 CPU @ 0.90GHz                 | 1         | 0.62%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.62%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 0.62%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 0.62%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 40        | 24.84%  |
| Intel Core i5                  | 36        | 22.36%  |
| Intel Core i3                  | 18        | 11.18%  |
| Intel Celeron                  | 13        | 8.07%   |
| Other                          | 12        | 7.45%   |
| AMD Ryzen 7                    | 6         | 3.73%   |
| Intel Core 2 Duo               | 4         | 2.48%   |
| AMD Ryzen 5                    | 4         | 2.48%   |
| Intel Core 2                   | 3         | 1.86%   |
| Intel Atom                     | 3         | 1.86%   |
| AMD A10                        | 3         | 1.86%   |
| Intel Pentium                  | 2         | 1.24%   |
| Intel Genuine                  | 2         | 1.24%   |
| AMD Ryzen 3                    | 2         | 1.24%   |
| AMD E1                         | 2         | 1.24%   |
| AMD A8                         | 2         | 1.24%   |
| Intel Xeon                     | 1         | 0.62%   |
| Intel Pentium Dual-Core        | 1         | 0.62%   |
| Intel Core M                   | 1         | 0.62%   |
| AMD V120                       | 1         | 0.62%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.62%   |
| AMD Turion 64 X2               | 1         | 0.62%   |
| AMD PRO A10                    | 1         | 0.62%   |
| AMD E                          | 1         | 0.62%   |
| AMD Athlon                     | 1         | 0.62%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 102       | 63.35%  |
| 4      | 37        | 22.98%  |
| 6      | 10        | 6.21%   |
| 8      | 7         | 4.35%   |
| 1      | 2         | 1.24%   |
| 24     | 1         | 0.62%   |
| 16     | 1         | 0.62%   |
| 10     | 1         | 0.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 161       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 120       | 74.53%  |
| 1      | 41        | 25.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 158       | 97.53%  |
| 32-bit         | 2         | 1.23%   |
| Unknown        | 2         | 1.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 29.34%  |
| 0x206a7    | 14        | 8.38%   |
| 0x40651    | 7         | 4.19%   |
| 0x306d4    | 7         | 4.19%   |
| 0x406e3    | 6         | 3.59%   |
| 0x306a9    | 6         | 3.59%   |
| 0x08108109 | 6         | 3.59%   |
| 0x806ec    | 5         | 2.99%   |
| 0x806e9    | 5         | 2.99%   |
| 0x406c4    | 5         | 2.99%   |
| 0x906ea    | 4         | 2.4%    |
| 0x706a1    | 4         | 2.4%    |
| 0x306c3    | 4         | 2.4%    |
| 0x1067a    | 4         | 2.4%    |
| 0x806eb    | 3         | 1.8%    |
| 0x806ea    | 3         | 1.8%    |
| 0x20655    | 3         | 1.8%    |
| 0x806c1    | 2         | 1.2%    |
| 0x6fd      | 2         | 1.2%    |
| 0x506e3    | 2         | 1.2%    |
| 0x05000119 | 2         | 1.2%    |
| 0xb06a2    | 1         | 0.6%    |
| 0xa0652    | 1         | 0.6%    |
| 0x906ed    | 1         | 0.6%    |
| 0x906e9    | 1         | 0.6%    |
| 0x706a8    | 1         | 0.6%    |
| 0x6f6      | 1         | 0.6%    |
| 0x6ec      | 1         | 0.6%    |
| 0x506c9    | 1         | 0.6%    |
| 0x30678    | 1         | 0.6%    |
| 0x106c2    | 1         | 0.6%    |
| 0x0a50000d | 1         | 0.6%    |
| 0x08a00006 | 1         | 0.6%    |
| 0x08608102 | 1         | 0.6%    |
| 0x08600106 | 1         | 0.6%    |
| 0x08600104 | 1         | 0.6%    |
| 0x08600103 | 1         | 0.6%    |
| 0x07030105 | 1         | 0.6%    |
| 0x07000110 | 1         | 0.6%    |
| 0x06006118 | 1         | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 29        | 18.01%  |
| SandyBridge      | 22        | 13.66%  |
| Haswell          | 13        | 8.07%   |
| IvyBridge        | 10        | 6.21%   |
| Skylake          | 9         | 5.59%   |
| Broadwell        | 9         | 5.59%   |
| Zen+             | 7         | 4.35%   |
| Silvermont       | 7         | 4.35%   |
| Unknown          | 6         | 3.73%   |
| TigerLake        | 5         | 3.11%   |
| Goldmont plus    | 5         | 3.11%   |
| Core             | 5         | 3.11%   |
| Penryn           | 4         | 2.48%   |
| IceLake          | 4         | 2.48%   |
| Excavator        | 4         | 2.48%   |
| Zen 2            | 3         | 1.86%   |
| Westmere         | 3         | 1.86%   |
| Bobcat           | 2         | 1.24%   |
| Alderlake Hybrid | 2         | 1.24%   |
| Zen 3            | 1         | 0.62%   |
| Puma             | 1         | 0.62%   |
| Piledriver       | 1         | 0.62%   |
| P6               | 1         | 0.62%   |
| K8 Hammer        | 1         | 0.62%   |
| K8 & K10 hybrid  | 1         | 0.62%   |
| K10 Llano        | 1         | 0.62%   |
| K10              | 1         | 0.62%   |
| Jaguar           | 1         | 0.62%   |
| Goldmont         | 1         | 0.62%   |
| CometLake        | 1         | 0.62%   |
| Bonnell          | 1         | 0.62%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 128       | 65.64%  |
| Nvidia | 36        | 18.46%  |
| AMD    | 31        | 15.9%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 8.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.39%   |
| Intel HD Graphics 5500                                                                   | 8         | 3.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 3.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 3.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.41%   |
| Intel HD Graphics 620                                                                    | 7         | 3.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.93%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.44%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 2.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 2.44%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 1.95%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.46%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.46%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.46%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.46%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.46%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.46%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.46%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.98%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.98%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.98%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.49%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.49%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.49%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.49%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.49%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.49%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.49%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.49%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.49%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 96        | 59.63%  |
| Intel + Nvidia | 29        | 18.01%  |
| 1 x AMD        | 22        | 13.66%  |
| 2 x AMD        | 4         | 2.48%   |
| 1 x Nvidia     | 4         | 2.48%   |
| AMD + Nvidia   | 3         | 1.86%   |
| Intel + AMD    | 2         | 1.24%   |
| Other          | 1         | 0.62%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 142       | 87.65%  |
| Proprietary | 18        | 11.11%  |
| Unknown     | 2         | 1.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 120       | 73.62%  |
| 1.01-2.0   | 14        | 8.59%   |
| 0.01-0.5   | 13        | 7.98%   |
| 3.01-4.0   | 8         | 4.91%   |
| 0.51-1.0   | 6         | 3.68%   |
| 5.01-6.0   | 2         | 1.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 40        | 20.3%   |
| LG Display              | 32        | 16.24%  |
| BOE                     | 23        | 11.68%  |
| Samsung Electronics     | 21        | 10.66%  |
| Chimei Innolux          | 21        | 10.66%  |
| Goldstar                | 7         | 3.55%   |
| Dell                    | 7         | 3.55%   |
| Apple                   | 7         | 3.55%   |
| AOC                     | 6         | 3.05%   |
| Chi Mei Optoelectronics | 4         | 2.03%   |
| Sony                    | 2         | 1.02%   |
| Sharp                   | 2         | 1.02%   |
| PANDA                   | 2         | 1.02%   |
| Hewlett-Packard         | 2         | 1.02%   |
| CPT                     | 2         | 1.02%   |
| ASUSTek Computer        | 2         | 1.02%   |
| Acer                    | 2         | 1.02%   |
| ViewSonic               | 1         | 0.51%   |
| Sun                     | 1         | 0.51%   |
| RTK                     | 1         | 0.51%   |
| PRISM+                  | 1         | 0.51%   |
| Panasonic               | 1         | 0.51%   |
| LG Philips              | 1         | 0.51%   |
| Lenovo                  | 1         | 0.51%   |
| KDC                     | 1         | 0.51%   |
| InnoLux Display         | 1         | 0.51%   |
| Hitachi                 | 1         | 0.51%   |
| GAOMON                  | 1         | 0.51%   |
| Envision                | 1         | 0.51%   |
| CVT                     | 1         | 0.51%   |
| Ancor Communications    | 1         | 0.51%   |
| AGO                     | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 5         | 2.54%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3         | 1.52%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 1.52%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.52%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 2         | 1.02%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 1.02%   |
| LG Display LCD Monitor LGD02F8 1366x768 310x170mm 13.9-inch           | 2         | 1.02%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 2         | 1.02%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 2         | 1.02%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.02%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.02%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 1.02%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 1.02%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 1.02%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.02%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch         | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.02%   |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch         | 1         | 0.51%   |
| Sun 48FHD_LCD_TV SCE0301 1920x1080 1280x720mm 57.8-inch               | 1         | 0.51%   |
| Sony TV SNY1B02 1360x768                                              | 1         | 0.51%   |
| Sony TV SNY0902 1920x1080                                             | 1         | 0.51%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 1         | 0.51%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.51%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.51%   |
| Samsung Electronics SyncMaster SAM058A 1920x1080 531x298mm 24.0-inch  | 1         | 0.51%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC345A 1366x768 309x174mm 14.0-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3352 1024x576 223x125mm 10.1-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 71        | 38.59%  |
| 1920x1080 (FHD)    | 60        | 32.61%  |
| 3840x2160 (4K)     | 12        | 6.52%   |
| 1280x800 (WXGA)    | 11        | 5.98%   |
| 1600x900 (HD+)     | 9         | 4.89%   |
| 1440x900 (WXGA+)   | 4         | 2.17%   |
| 1280x1024 (SXGA)   | 4         | 2.17%   |
| 2560x1440 (QHD)    | 3         | 1.63%   |
| 1920x1200 (WUXGA)  | 2         | 1.09%   |
| 1360x768           | 2         | 1.09%   |
| 3840x2400          | 1         | 0.54%   |
| 3200x2000          | 1         | 0.54%   |
| 2560x1600          | 1         | 0.54%   |
| 1680x1050 (WSXGA+) | 1         | 0.54%   |
| 1400x1050          | 1         | 0.54%   |
| 1024x576           | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 77        | 39.49%  |
| 14     | 32        | 16.41%  |
| 13     | 29        | 14.87%  |
| 17     | 8         | 4.1%    |
| 21     | 7         | 3.59%   |
| 23     | 6         | 3.08%   |
| 24     | 4         | 2.05%   |
| 19     | 4         | 2.05%   |
| 18     | 4         | 2.05%   |
| 84     | 3         | 1.54%   |
| 31     | 3         | 1.54%   |
| 16     | 3         | 1.54%   |
| 12     | 3         | 1.54%   |
| 11     | 3         | 1.54%   |
| 72     | 2         | 1.03%   |
| 57     | 2         | 1.03%   |
| 27     | 2         | 1.03%   |
| 32     | 1         | 0.51%   |
| 20     | 1         | 0.51%   |
| 10     | 1         | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 132       | 68.39%  |
| 201-300     | 16        | 8.29%   |
| 401-500     | 14        | 7.25%   |
| 501-600     | 12        | 6.22%   |
| 351-400     | 8         | 4.15%   |
| 1501-2000   | 5         | 2.59%   |
| 601-700     | 3         | 1.55%   |
| 701-800     | 2         | 1.04%   |
| 1001-1500   | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 140       | 82.84%  |
| 16/10 | 22        | 13.02%  |
| 5/4   | 4         | 2.37%   |
| 4/3   | 2         | 1.18%   |
| 0.56  | 1         | 0.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 77        | 39.69%  |
| 81-90          | 58        | 29.9%   |
| 201-250        | 14        | 7.22%   |
| More than 1000 | 7         | 3.61%   |
| 151-200        | 7         | 3.61%   |
| 141-150        | 5         | 2.58%   |
| 121-130        | 5         | 2.58%   |
| 351-500        | 4         | 2.06%   |
| 71-80          | 3         | 1.55%   |
| 51-60          | 3         | 1.55%   |
| 111-120        | 3         | 1.55%   |
| 61-70          | 2         | 1.03%   |
| 301-350        | 2         | 1.03%   |
| 41-50          | 1         | 0.52%   |
| 251-300        | 1         | 0.52%   |
| 131-140        | 1         | 0.52%   |
| 91-100         | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 85        | 44.5%   |
| 121-160       | 65        | 34.03%  |
| 51-100        | 28        | 14.66%  |
| More than 240 | 5         | 2.62%   |
| 1-50          | 5         | 2.62%   |
| 161-240       | 3         | 1.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 126       | 75%     |
| 2     | 36        | 21.43%  |
| 3     | 4         | 2.38%   |
| 0     | 2         | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 92        | 35.11%  |
| Intel                    | 71        | 27.1%   |
| Qualcomm Atheros         | 45        | 17.18%  |
| Broadcom                 | 26        | 9.92%   |
| Broadcom Limited         | 7         | 2.67%   |
| TP-Link                  | 6         | 2.29%   |
| MediaTek                 | 3         | 1.15%   |
| Nvidia                   | 2         | 0.76%   |
| ASIX Electronics         | 2         | 0.76%   |
| Xiaomi                   | 1         | 0.38%   |
| Marvell Technology Group | 1         | 0.38%   |
| JMicron Technology       | 1         | 0.38%   |
| Huawei Technologies      | 1         | 0.38%   |
| Hewlett-Packard          | 1         | 0.38%   |
| DisplayLink              | 1         | 0.38%   |
| Dell                     | 1         | 0.38%   |
| D-Link                   | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 48        | 14.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 27        | 8.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 12        | 3.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 3.08%   |
| Intel Wireless 7265                                                    | 9         | 2.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 2.46%   |
| Intel Wireless 7260                                                    | 7         | 2.15%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 6         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.54%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 1.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 1.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 5         | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 1.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 4         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 1.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 1.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 4         | 1.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 1.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 3         | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.92%   |
| Intel Wireless 8260                                                    | 3         | 0.92%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 0.92%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 0.92%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                              | 2         | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.62%   |
| Realtek 802.11ac NIC                                                   | 2         | 0.62%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.62%   |
| Intel Wireless 8265 / 8275                                             | 2         | 0.62%   |
| Intel Wireless 3160                                                    | 2         | 0.62%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 62        | 37.35%  |
| Qualcomm Atheros      | 36        | 21.69%  |
| Realtek Semiconductor | 30        | 18.07%  |
| Broadcom              | 21        | 12.65%  |
| Broadcom Limited      | 7         | 4.22%   |
| TP-Link               | 6         | 3.61%   |
| MediaTek              | 2         | 1.2%    |
| Dell                  | 1         | 0.6%    |
| D-Link                | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 7.1%    |
| Intel Wireless 7265                                            | 9         | 5.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 4.73%   |
| Intel Wireless 7260                                            | 7         | 4.14%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 6         | 3.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 3.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 3.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.96%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 2.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 2.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 2.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 2.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 2.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.37%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 2.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 2.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.78%   |
| Intel Wireless 8260                                            | 3         | 1.78%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.78%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                      | 2         | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.18%   |
| Realtek 802.11ac NIC                                           | 2         | 1.18%   |
| Intel Wireless 8265 / 8275                                     | 2         | 1.18%   |
| Intel Wireless 3160                                            | 2         | 1.18%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.18%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.18%   |
| Broadcom Limited BCM4311 802.11a/b/g                           | 2         | 1.18%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1         | 0.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.59%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.59%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 82        | 55.78%  |
| Intel                    | 31        | 21.09%  |
| Qualcomm Atheros         | 12        | 8.16%   |
| Broadcom                 | 12        | 8.16%   |
| Nvidia                   | 2         | 1.36%   |
| ASIX Electronics         | 2         | 1.36%   |
| Xiaomi                   | 1         | 0.68%   |
| MediaTek                 | 1         | 0.68%   |
| Marvell Technology Group | 1         | 0.68%   |
| JMicron Technology       | 1         | 0.68%   |
| Huawei Technologies      | 1         | 0.68%   |
| DisplayLink              | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 48        | 30.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 27        | 17.42%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 6.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 5.16%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 3.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 2.58%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.94%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.94%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 1.29%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.29%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 1.29%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 2         | 1.29%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.29%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.65%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.65%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.65%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.65%   |
| Nvidia MCP67 Ethernet                                                  | 1         | 0.65%   |
| MediaTek File-CD Gadget                                                | 1         | 0.65%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.65%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 0.65%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.65%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.65%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.65%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.65%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.65%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.65%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 0.65%   |
| Intel 82599 10 Gigabit Network Connection                              | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 158       | 53.38%  |
| Ethernet | 137       | 46.28%  |
| Modem    | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 124       | 73.81%  |
| Ethernet | 44        | 26.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 128       | 79.01%  |
| 1     | 27        | 16.67%  |
| 3     | 5         | 3.09%   |
| 0     | 2         | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 157       | 96.32%  |
| Yes  | 6         | 3.68%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 39.34%  |
| Realtek Semiconductor           | 19        | 15.57%  |
| Qualcomm Atheros Communications | 17        | 13.93%  |
| Broadcom                        | 10        | 8.2%    |
| Apple                           | 7         | 5.74%   |
| Lite-On Technology              | 5         | 4.1%    |
| IMC Networks                    | 4         | 3.28%   |
| Toshiba                         | 3         | 2.46%   |
| Foxconn / Hon Hai               | 3         | 2.46%   |
| Hewlett-Packard                 | 2         | 1.64%   |
| Cambridge Silicon Radio         | 2         | 1.64%   |
| Realtek                         | 1         | 0.82%   |
| Dell                            | 1         | 0.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 18.03%  |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 9.02%   |
| Realtek Bluetooth Radio                             | 10        | 8.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 8.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 6.56%   |
| Intel AX200 Bluetooth                               | 5         | 4.1%    |
| Apple Bluetooth Host Controller                     | 5         | 4.1%    |
| Intel AX201 Bluetooth                               | 4         | 3.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 2.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.46%   |
| Broadcom HP Portable SoftSailing                    | 3         | 2.46%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 2.46%   |
| Toshiba Bluetooth Device                            | 2         | 1.64%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.64%   |
| Intel AX210 Bluetooth                               | 2         | 1.64%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.64%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.64%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.64%   |
| Toshiba BCM43142A0                                  | 1         | 0.82%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.82%   |
| Realtek Bluetooth Radio                             | 1         | 0.82%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.82%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.82%   |
| Lite-On Wireless_Device                             | 1         | 0.82%   |
| Lite-On Bluetooth Device                            | 1         | 0.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.82%   |
| Intel Bluetooth Device                              | 1         | 0.82%   |
| IMC Networks Wireless_Device                        | 1         | 0.82%   |
| IMC Networks Bluetooth                              | 1         | 0.82%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.82%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.82%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.82%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.82%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.82%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.82%   |
| Apple Bluetooth HCI                                 | 1         | 0.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 133       | 65.2%   |
| AMD                    | 30        | 14.71%  |
| Nvidia                 | 21        | 10.29%  |
| Generalplus Technology | 3         | 1.47%   |
| Plantronics            | 2         | 0.98%   |
| Logitech               | 2         | 0.98%   |
| JMTek                  | 2         | 0.98%   |
| GN Netcom              | 2         | 0.98%   |
| C-Media Electronics    | 2         | 0.98%   |
| Unknown                | 1         | 0.49%   |
| Sony                   | 1         | 0.49%   |
| Realtek Semiconductor  | 1         | 0.49%   |
| Lenovo                 | 1         | 0.49%   |
| KTMicro                | 1         | 0.49%   |
| CMX Systems            | 1         | 0.49%   |
| Afatech                | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 7.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 6.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 6.12%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 5.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 3.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 3.67%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 3.27%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 3.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.04%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.04%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.04%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.63%   |
| Nvidia Audio device                                                                               | 4         | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.22%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.22%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 1.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.22%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.82%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.82%   |
| Unknown USB PnP Audio Device                                                                      | 1         | 0.41%   |
| Sony DualSense wireless controller (PS5)                                                          | 1         | 0.41%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.41%   |
| Plantronics Blackwire C5220 headset (remote control and 3.5mm audio adapter)                      | 1         | 0.41%   |
| Plantronics Blackwire 3225 Series                                                                 | 1         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 29.82%  |
| SK hynix            | 20        | 17.54%  |
| Micron Technology   | 12        | 10.53%  |
| Kingston            | 10        | 8.77%   |
| Crucial             | 9         | 7.89%   |
| Nanya Technology    | 5         | 4.39%   |
| Unknown             | 4         | 3.51%   |
| Team                | 4         | 3.51%   |
| Corsair             | 4         | 3.51%   |
| A-DATA Technology   | 4         | 3.51%   |
| Ramaxel Technology  | 3         | 2.63%   |
| Transcend           | 1         | 0.88%   |
| Super Talent        | 1         | 0.88%   |
| Patriot             | 1         | 0.88%   |
| G.Skill             | 1         | 0.88%   |
| fef5                | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s | 5         | 3.82%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s    | 4         | 3.05%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s              | 4         | 3.05%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s              | 4         | 3.05%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 3         | 2.29%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 2.29%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 1.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 2         | 1.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 1.53%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 2         | 1.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 2         | 1.53%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s | 2         | 1.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 2         | 1.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s    | 2         | 1.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s    | 2         | 1.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s    | 2         | 1.53%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s     | 2         | 1.53%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s    | 2         | 1.53%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s              | 1         | 0.76%   |
| Unknown RAM Module 8GB SODIMM DDR3                       | 1         | 0.76%   |
| Unknown RAM Module 4GB SODIMM DDR3                       | 1         | 0.76%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 1         | 0.76%   |
| Unknown RAM Module 1GB SODIMM SDRAM                      | 1         | 0.76%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s      | 1         | 0.76%   |
| Super Talent RAM SUPERTALENT02 8GB SODIMM DDR3 1600MT/s  | 1         | 0.76%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s             | 1         | 0.76%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s             | 1         | 0.76%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s   | 1         | 0.76%   |
| SK hynix RAM HMP125S6EFR8C-S6 2GB SODIMM DDR2 800MT/s    | 1         | 0.76%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s   | 1         | 0.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s   | 1         | 0.76%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s   | 1         | 0.76%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s   | 1         | 0.76%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 1         | 0.76%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1         | 0.76%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s  | 1         | 0.76%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1         | 0.76%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1         | 0.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 1         | 0.76%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s   | 1         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 39        | 41.49%  |
| DDR3    | 39        | 41.49%  |
| SDRAM   | 4         | 4.26%   |
| DDR2    | 4         | 4.26%   |
| DDR5    | 3         | 3.19%   |
| LPDDR4  | 2         | 2.13%   |
| LPDDR5  | 1         | 1.06%   |
| LPDDR3  | 1         | 1.06%   |
| Unknown | 1         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 94.57%  |
| Row Of Chips | 3         | 3.26%   |
| Chip         | 1         | 1.09%   |
| Unknown      | 1         | 1.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 43        | 39.09%  |
| 8192  | 37        | 33.64%  |
| 16384 | 12        | 10.91%  |
| 2048  | 9         | 8.18%   |
| 32768 | 7         | 6.36%   |
| 1024  | 2         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 29        | 26.61%  |
| 2667    | 25        | 22.94%  |
| 3200    | 10        | 9.17%   |
| 1334    | 7         | 6.42%   |
| 1333    | 7         | 6.42%   |
| 3266    | 5         | 4.59%   |
| 2400    | 5         | 4.59%   |
| 2133    | 3         | 2.75%   |
| 667     | 3         | 2.75%   |
| Unknown | 3         | 2.75%   |
| 4800    | 2         | 1.83%   |
| 4199    | 2         | 1.83%   |
| 1067    | 2         | 1.83%   |
| 8400    | 1         | 0.92%   |
| 6400    | 1         | 0.92%   |
| 5600    | 1         | 0.92%   |
| 2933    | 1         | 0.92%   |
| 2048    | 1         | 0.92%   |
| 800     | 1         | 0.92%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L382 Series | 1         | 50%     |
| Seiko Epson L360 Series | 1         | 50%     |

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
| Chicony Electronics                    | 32        | 22.38%  |
| Microdia                               | 17        | 11.89%  |
| IMC Networks                           | 15        | 10.49%  |
| Sunplus Innovation Technology          | 13        | 9.09%   |
| Realtek Semiconductor                  | 13        | 9.09%   |
| Apple                                  | 7         | 4.9%    |
| Quanta                                 | 6         | 4.2%    |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.2%    |
| Lite-On Technology                     | 5         | 3.5%    |
| Primax Electronics                     | 4         | 2.8%    |
| Bison Electronics                      | 4         | 2.8%    |
| Suyin                                  | 3         | 2.1%    |
| Luxvisions Innotech Limited            | 2         | 1.4%    |
| Logitech                               | 2         | 1.4%    |
| Alcor Micro                            | 2         | 1.4%    |
| Z-Star Microelectronics                | 1         | 0.7%    |
| Syntek                                 | 1         | 0.7%    |
| Sonix Technology                       | 1         | 0.7%    |
| Silicon Motion                         | 1         | 0.7%    |
| Samsung Electronics                    | 1         | 0.7%    |
| Microsoft                              | 1         | 0.7%    |
| LG Electronics                         | 1         | 0.7%    |
| Importek                               | 1         | 0.7%    |
| GEMBIRD                                | 1         | 0.7%    |
| Creative Technology                    | 1         | 0.7%    |
| Alpha Imaging Technology               | 1         | 0.7%    |
| Acer                                   | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 12        | 8.28%   |
| Chicony Integrated Camera                        | 9         | 6.21%   |
| Sunplus HD WebCam                                | 5         | 3.45%   |
| Realtek Integrated_Webcam_HD                     | 5         | 3.45%   |
| IMC Networks Integrated Camera                   | 5         | 3.45%   |
| Apple FaceTime HD Camera                         | 5         | 3.45%   |
| Sunplus Integrated_Webcam_HD                     | 3         | 2.07%   |
| Primax HP HD Webcam [Fixed]                      | 3         | 2.07%   |
| IMC Networks USB2.0 HD UVC WebCam                | 3         | 2.07%   |
| Chicony TOSHIBA Web Camera - HD                  | 3         | 2.07%   |
| Sunplus HP HD Webcam [Fixed]                     | 2         | 1.38%   |
| Realtek USB Camera                               | 2         | 1.38%   |
| Realtek Integrated Webcam                        | 2         | 1.38%   |
| Quanta HP TrueVision HD Camera                   | 2         | 1.38%   |
| Quanta HD WebCam                                 | 2         | 1.38%   |
| Microdia Integrated Webcam                       | 2         | 1.38%   |
| Lite-On TOSHIBA Web Camera - HD                  | 2         | 1.38%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 1.38%   |
| Chicony USB 2.0 Camera                           | 2         | 1.38%   |
| Chicony Integrated HP HD Webcam                  | 2         | 1.38%   |
| Chicony HP Truevision HD                         | 2         | 1.38%   |
| Chicony HP HD Webcam                             | 2         | 1.38%   |
| Chicony HP HD Camera                             | 2         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.38%   |
| Z-Star Vega USB2.0 Camera                        | 1         | 0.69%   |
| Syntek EasyCamera                                | 1         | 0.69%   |
| Suyin TOSHIBA Web Camera - HD                    | 1         | 0.69%   |
| Suyin HP TrueVision HD                           | 1         | 0.69%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.69%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 1         | 0.69%   |
| Sunplus Integrated Camera                        | 1         | 0.69%   |
| Sunplus Dell Integrated Webcam                   | 1         | 0.69%   |
| Sonix USB2.0 FHD UVC WebCam                      | 1         | 0.69%   |
| Silicon Motion ATIV Real HD Camera               | 1         | 0.69%   |
| Samsung Galaxy series, misc. (MTP mode)          | 1         | 0.69%   |
| Realtek USB2.0 VGA UVC WebCam                    | 1         | 0.69%   |
| Realtek Rear Camera                              | 1         | 0.69%   |
| Realtek HP Wide Vision FHD Camera                | 1         | 0.69%   |
| Realtek HP Truevision HD                         | 1         | 0.69%   |
| Realtek Front Camera                             | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 51.72%  |
| Synaptics                  | 6         | 20.69%  |
| Shenzhen Goodix Technology | 3         | 10.34%  |
| Upek                       | 1         | 3.45%   |
| STMicroelectronics         | 1         | 3.45%   |
| LighTuning Technology      | 1         | 3.45%   |
| Elan Microelectronics      | 1         | 3.45%   |
| AuthenTec                  | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 13.79%  |
| Validity Sensors VFS491                                | 3         | 10.34%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 3         | 10.34%  |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 10.34%  |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 6.9%    |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 6.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 6.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 3.45%   |
| Validity Sensors Synaptics WBDI                        | 1         | 3.45%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 3.45%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 3.45%   |
| Synaptics WBDI                                         | 1         | 3.45%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 3.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.45%   |
| Elan ELAN:ARM-M4                                       | 1         | 3.45%   |
| AuthenTec AES1600                                      | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 4         | 40%     |
| O2 Micro                   | 3         | 30%     |
| Athena Smartcard Solutions | 2         | 20%     |
| Alcor Micro                | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 20%     |
| Broadcom 5880                                                                | 2         | 20%     |
| Athena Smartcard Solutions ASEDrive CCID                                     | 2         | 20%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom 58200                                                               | 1         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 103       | 61.68%  |
| 1     | 56        | 33.53%  |
| 2     | 5         | 2.99%   |
| 3     | 3         | 1.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 28        | 36.84%  |
| Net/wireless             | 15        | 19.74%  |
| Graphics card            | 15        | 19.74%  |
| Chipcard                 | 8         | 10.53%  |
| Multimedia controller    | 2         | 2.63%   |
| Storage                  | 1         | 1.32%   |
| Sound                    | 1         | 1.32%   |
| Net/ethernet             | 1         | 1.32%   |
| Firewire controller      | 1         | 1.32%   |
| Communication controller | 1         | 1.32%   |
| Card reader              | 1         | 1.32%   |
| Camera                   | 1         | 1.32%   |
| Bluetooth                | 1         | 1.32%   |

