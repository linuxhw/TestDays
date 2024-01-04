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

Total: 270

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | G60                         | [a151a8084c](https://linux-hardware.org/?probe=a151a8084c) | Jan 01, 2024 |
| HP       | Laptop 15-da0xxx            | [4e00c088e8](https://linux-hardware.org/?probe=4e00c088e8) | Dec 29, 2023 |
| Lenovo   | ThinkPad T420 4236DA4       | [1188c1619d](https://linux-hardware.org/?probe=1188c1619d) | Dec 20, 2023 |
| Dell     | XPS 15 9560                 | [bb58136a7c](https://linux-hardware.org/?probe=bb58136a7c) | Dec 18, 2023 |
| Dell     | G15 5515                    | [259739c8b5](https://linux-hardware.org/?probe=259739c8b5) | Dec 14, 2023 |
| Lenovo   | IdeaPad S340-14IIL 81VV     | [6b350f2aaf](https://linux-hardware.org/?probe=6b350f2aaf) | Dec 11, 2023 |
| HP       | EliteBook 8470p             | [c723bcc62a](https://linux-hardware.org/?probe=c723bcc62a) | Dec 07, 2023 |
| Apple    | MacBookPro8,1               | [7d8d9279cd](https://linux-hardware.org/?probe=7d8d9279cd) | Nov 21, 2023 |
| Apple    | MacBookPro5,4               | [7045b84f52](https://linux-hardware.org/?probe=7045b84f52) | Nov 21, 2023 |
| ASUSTek  | ASUS TUF Dash F15 FX516P... | [af8edff0b6](https://linux-hardware.org/?probe=af8edff0b6) | Nov 15, 2023 |
| Toshiba  | Satellite L845              | [4dc7e8931e](https://linux-hardware.org/?probe=4dc7e8931e) | Nov 05, 2023 |
| Dell     | Inspiron 3443               | [bbe3093cb4](https://linux-hardware.org/?probe=bbe3093cb4) | Oct 22, 2023 |
| Lenovo   | IdeaPad 1 15AMN7 82VG       | [d8335b95a8](https://linux-hardware.org/?probe=d8335b95a8) | Oct 19, 2023 |
| Apple    | MacBookPro8,1               | [ae4ee327c0](https://linux-hardware.org/?probe=ae4ee327c0) | Oct 06, 2023 |
| HP       | Laptop 15-da0xxx            | [92e214fb3e](https://linux-hardware.org/?probe=92e214fb3e) | Oct 04, 2023 |
| HP       | EliteBook 745 G3            | [a814d9fa4b](https://linux-hardware.org/?probe=a814d9fa4b) | Sep 25, 2023 |
| HP       | Mini 110-1000               | [dda4d7a910](https://linux-hardware.org/?probe=dda4d7a910) | Sep 18, 2023 |
| HP       | Mini 110-1000               | [ee2d142228](https://linux-hardware.org/?probe=ee2d142228) | Sep 18, 2023 |
| Apple    | MacBookPro8,1               | [c7b5f9224a](https://linux-hardware.org/?probe=c7b5f9224a) | Sep 17, 2023 |
| ASUSTek  | X541UV                      | [a66fcc9edb](https://linux-hardware.org/?probe=a66fcc9edb) | Sep 11, 2023 |
| Sony     | SVE14123CLW                 | [2fffba7739](https://linux-hardware.org/?probe=2fffba7739) | Sep 08, 2023 |
| Dell     | Inspiron 5567               | [3b740d65f2](https://linux-hardware.org/?probe=3b740d65f2) | Sep 04, 2023 |
| ASUSTek  | TUF Gaming FX504GD_FX80G... | [40693c0171](https://linux-hardware.org/?probe=40693c0171) | Aug 29, 2023 |
| Lenovo   | B590 20208                  | [65bf0970da](https://linux-hardware.org/?probe=65bf0970da) | Aug 27, 2023 |
| Dell     | Latitude E6420              | [ae48a8c618](https://linux-hardware.org/?probe=ae48a8c618) | Aug 26, 2023 |
| MSI      | Katana 15 B13VGK            | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| HP       | Pavilion Gaming Laptop 1... | [b65293c5a8](https://linux-hardware.org/?probe=b65293c5a8) | Aug 17, 2023 |
| HP       | EliteBook 840 G3            | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Samsung  | 930X2K/931X2K               | [5985901bef](https://linux-hardware.org/?probe=5985901bef) | Aug 03, 2023 |
| Lenovo   | ThinkPad E15 Gen 2 20TES... | [ec5a50d1d8](https://linux-hardware.org/?probe=ec5a50d1d8) | Jul 29, 2023 |
| ASUSTek  | Q551LN                      | [ad2abcddcf](https://linux-hardware.org/?probe=ad2abcddcf) | Jul 27, 2023 |
| Lenovo   | ThinkPad E580 20KS003LLM    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Toshiba  | Satellite L755              | [cb309977d0](https://linux-hardware.org/?probe=cb309977d0) | Jul 08, 2023 |
| Samsung  | 930X2K/931X2K               | [fd0d25039d](https://linux-hardware.org/?probe=fd0d25039d) | Jul 07, 2023 |
| Samsung  | 930X2K/931X2K               | [294e57d915](https://linux-hardware.org/?probe=294e57d915) | Jul 07, 2023 |
| Dell     | Inspiron 5593               | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| ASUSTek  | VivoBook_ASUSLaptop K660... | [3e3987b43f](https://linux-hardware.org/?probe=3e3987b43f) | Jun 20, 2023 |
| HP       | ENVY 15                     | [101fb8810b](https://linux-hardware.org/?probe=101fb8810b) | Jun 19, 2023 |
| HP       | Notebook                    | [42558904aa](https://linux-hardware.org/?probe=42558904aa) | Jun 10, 2023 |
| Apple    | MacBookPro8,1               | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| ASUSTek  | ASUS TUF Dash F15 FX516P... | [1aa286ccff](https://linux-hardware.org/?probe=1aa286ccff) | Jun 03, 2023 |
| HP       | Notebook                    | [c246477ea2](https://linux-hardware.org/?probe=c246477ea2) | May 31, 2023 |
| ASUSTek  | ASUS TUF Dash F15 FX516P... | [360e8fd5e5](https://linux-hardware.org/?probe=360e8fd5e5) | May 30, 2023 |
| HP       | Notebook                    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Lenovo   | ThinkPad E490 20N8A01YGI    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Samsung  | 930X2K/931X2K               | [14eae60f4f](https://linux-hardware.org/?probe=14eae60f4f) | May 13, 2023 |
| Samsung  | 930X2K/931X2K               | [7ac717a41d](https://linux-hardware.org/?probe=7ac717a41d) | May 13, 2023 |
| Apple    | MacBookPro9,2               | [ba104d9250](https://linux-hardware.org/?probe=ba104d9250) | May 10, 2023 |
| ASUSTek  | TUF Gaming FX504GD_FX80G... | [b06388c1f4](https://linux-hardware.org/?probe=b06388c1f4) | May 09, 2023 |
| Samsung  | 930X2K/931X2K               | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| HUAWEI   | NBLK-WAX9X                  | [36ec2bb4c2](https://linux-hardware.org/?probe=36ec2bb4c2) | Apr 22, 2023 |
| HP       | ProBook 6570b               | [2b01f67020](https://linux-hardware.org/?probe=2b01f67020) | Apr 14, 2023 |
| Samsung  | 930X2K/931X2K               | [126c7a430c](https://linux-hardware.org/?probe=126c7a430c) | Apr 13, 2023 |
| Samsung  | 930X2K/931X2K               | [80d44eb98b](https://linux-hardware.org/?probe=80d44eb98b) | Apr 12, 2023 |
| HP       | EliteBook 8560p             | [2ecc0fe5bc](https://linux-hardware.org/?probe=2ecc0fe5bc) | Apr 07, 2023 |
| Apple    | MacBookPro8,1               | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP       | Laptop 15-da0xxx            | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| Google   | Snappy                      | [16dda325bf](https://linux-hardware.org/?probe=16dda325bf) | Apr 02, 2023 |
| Apple    | MacBookPro8,1               | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| Acer     | Aspire E1-431               | [f56a2c21cf](https://linux-hardware.org/?probe=f56a2c21cf) | Mar 26, 2023 |
| Dell     | XPS 15 9510                 | [d8fee2b6b1](https://linux-hardware.org/?probe=d8fee2b6b1) | Mar 08, 2023 |
| Acer     | Aspire V3-571G              | [b02e34a7f9](https://linux-hardware.org/?probe=b02e34a7f9) | Feb 25, 2023 |
| Unknown  | Unknown                     | [6707aef886](https://linux-hardware.org/?probe=6707aef886) | Feb 25, 2023 |
| Apple    | MacBookPro8,1               | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Acer     | Aspire A515-45              | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Dell     | Latitude E5430 non-vPro     | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| HP       | Laptop 14-dk1xxx            | [8761a4096a](https://linux-hardware.org/?probe=8761a4096a) | Jan 22, 2023 |
| HP       | Laptop 14-dk1xxx            | [7099ccff2f](https://linux-hardware.org/?probe=7099ccff2f) | Jan 22, 2023 |
| HP       | Laptop 15-da0xxx            | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| Lenovo   | Legion Y540-15IRH 81SX      | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| Apple    | MacBookPro8,1               | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Apple    | MacBookPro8,1               | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| HP       | Laptop 15-da0xxx            | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| Lenovo   | ThinkPad X1 Extreme Gen ... | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo   | ThinkPad X1 Extreme Gen ... | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Toshiba  | Satellite S55-A             | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| HP       | Unknown                     | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Apple    | MacBookPro8,1               | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Toshiba  | Satellite S55-A             | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| Lenovo   | ThinkPad P16 Gen 1 21D7S... | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| Lenovo   | ThinkPad T60 1952F75        | [a6f536ca3d](https://linux-hardware.org/?probe=a6f536ca3d) | Oct 25, 2022 |
| Lenovo   | ThinkPad T60 1952F75        | [813bd112f8](https://linux-hardware.org/?probe=813bd112f8) | Oct 25, 2022 |
| MSI      | GF65 Thin 10SDR             | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| Dell     | Inspiron 3493               | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Lenovo   | ThinkPad T470 W10DG 20JM... | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell     | G3 3579                     | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| Dell     | Inspiron 3543               | [68d1385b7e](https://linux-hardware.org/?probe=68d1385b7e) | Aug 28, 2022 |
| Toshiba  | Satellite C55-C             | [99faef3f00](https://linux-hardware.org/?probe=99faef3f00) | Aug 20, 2022 |
| Toshiba  | Satellite L655              | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Toshiba  | Satellite C55-C             | [992b4f4910](https://linux-hardware.org/?probe=992b4f4910) | Aug 06, 2022 |
| ASUSTek  | GL552VW                     | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Acer     | Aspire E5-576               | [a31ceb9a36](https://linux-hardware.org/?probe=a31ceb9a36) | Jul 31, 2022 |
| Acer     | Aspire R3-131T              | [f4efe63bf8](https://linux-hardware.org/?probe=f4efe63bf8) | Jul 13, 2022 |
| Acer     | Aspire R3-131T              | [a06c4e1f6b](https://linux-hardware.org/?probe=a06c4e1f6b) | Jul 13, 2022 |
| Deffad   | Unknown                     | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| Dell     | Inspiron 3520               | [b865370f11](https://linux-hardware.org/?probe=b865370f11) | Jun 28, 2022 |
| Lenovo   | ThinkPad P50 20EN001PUS     | [52ef9383a4](https://linux-hardware.org/?probe=52ef9383a4) | Jun 09, 2022 |
| Lenovo   | ThinkPad T440s 20ARS29U0... | [50de8ad2e9](https://linux-hardware.org/?probe=50de8ad2e9) | Jun 01, 2022 |
| Dell     | Latitude 7400               | [caf85903ad](https://linux-hardware.org/?probe=caf85903ad) | May 19, 2022 |
| Dell     | Inspiron 5565               | [d5a8629a31](https://linux-hardware.org/?probe=d5a8629a31) | May 19, 2022 |
| Lenovo   | ThinkPad L420 7829AA4       | [9c1bbe8cf2](https://linux-hardware.org/?probe=9c1bbe8cf2) | May 14, 2022 |
| HP       | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20T80... | [637af2dcc6](https://linux-hardware.org/?probe=637af2dcc6) | Apr 29, 2022 |
| Apple    | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| HP       | Pavilion Notebook           | [a1130d8070](https://linux-hardware.org/?probe=a1130d8070) | Apr 13, 2022 |
| Acer     | Nitro AN515-43              | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
| Dell     | Latitude E5500              | [13be4a0a1b](https://linux-hardware.org/?probe=13be4a0a1b) | Mar 16, 2022 |
| Dell     | Latitude E5500              | [d5f8fd7890](https://linux-hardware.org/?probe=d5f8fd7890) | Mar 16, 2022 |
| HP       | Laptop 15-da0xxx            | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell     | Latitude D630               | [b7b428082a](https://linux-hardware.org/?probe=b7b428082a) | Mar 05, 2022 |
| Dell     | XPS 13 9305                 | [8807d99cb4](https://linux-hardware.org/?probe=8807d99cb4) | Mar 01, 2022 |
| ASUSTek  | VivoBook_ASUS Laptop E41... | [c0adf77f3f](https://linux-hardware.org/?probe=c0adf77f3f) | Feb 26, 2022 |
| Sony     | SVD13215PLB                 | [82c4287f85](https://linux-hardware.org/?probe=82c4287f85) | Feb 23, 2022 |
| Lenovo   | ThinkPad L15 Gen 2 20X4S... | [b355ea1ff3](https://linux-hardware.org/?probe=b355ea1ff3) | Feb 20, 2022 |
| Lenovo   | IdeaPad 3 14ADA05 81W0      | [8468cd0da9](https://linux-hardware.org/?probe=8468cd0da9) | Feb 19, 2022 |
| Lenovo   | IdeaPad 3 14ADA05 81W0      | [80e2f3c47e](https://linux-hardware.org/?probe=80e2f3c47e) | Feb 19, 2022 |
| Apple    | MacBookPro8,1               | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| HP       | Laptop 15-da0xxx            | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| HUAWEI   | NBLK-WAX9X                  | [dbc7cbcfe1](https://linux-hardware.org/?probe=dbc7cbcfe1) | Feb 07, 2022 |
| Toshiba  | Satellite L45-B             | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [3f953ad7f3](https://linux-hardware.org/?probe=3f953ad7f3) | Jan 14, 2022 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [eecedd12b2](https://linux-hardware.org/?probe=eecedd12b2) | Jan 14, 2022 |
| Dell     | Latitude 5490               | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP       | EliteBook 8460p             | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| HP       | EliteBook 8460p             | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| Dell     | Inspiron 3595               | [1df662506b](https://linux-hardware.org/?probe=1df662506b) | Oct 27, 2021 |
| Apple    | MacBookPro8,1               | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Lenovo   | IdeaPad Gaming 3 15ARH05... | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| HP       | EliteBook 8460p             | [5bb3c9bc8b](https://linux-hardware.org/?probe=5bb3c9bc8b) | Oct 19, 2021 |
| Apple    | MacBookPro8,1               | [bfadd59ae5](https://linux-hardware.org/?probe=bfadd59ae5) | Oct 18, 2021 |
| Lenovo   | IdeaPad Gaming 3 15ARH05... | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Acer     | Aspire 5750                 | [ff12aa7481](https://linux-hardware.org/?probe=ff12aa7481) | Oct 15, 2021 |
| Lenovo   | IdeaPad Gaming 3 15ARH05... | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo   | ThinkPad X1 Carbon 2nd 2... | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| HP       | Laptop 15-da0xxx            | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Dell     | Latitude D620               | [1dc8e001f5](https://linux-hardware.org/?probe=1dc8e001f5) | Sep 28, 2021 |
| Apple    | MacBookPro8,1               | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple    | MacBookPro8,1               | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Apple    | MacBookPro8,1               | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Apple    | MacBookPro8,1               | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| HP       | EliteBook 820 G1            | [00b3e62e2e](https://linux-hardware.org/?probe=00b3e62e2e) | Sep 10, 2021 |
| MSI      | GF75 Thin 9SD               | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP       | Pavilion Laptop 15-cc1xx    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP       | Pavilion Laptop 15-cc1xx    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| Olivetti | CL133A                      | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| HP       | Pavilion g4                 | [3f01790d4e](https://linux-hardware.org/?probe=3f01790d4e) | Jul 21, 2021 |
| AZW      | GT-R                        | [115230aa47](https://linux-hardware.org/?probe=115230aa47) | Jul 19, 2021 |
| Olivetti | CL133A                      | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| ASUSTek  | U46E                        | [720dec33c4](https://linux-hardware.org/?probe=720dec33c4) | Jul 14, 2021 |
| HP       | ProBook 6460b               | [b39eb9b256](https://linux-hardware.org/?probe=b39eb9b256) | Jul 13, 2021 |
| Dell     | G3 3590                     | [3781e31377](https://linux-hardware.org/?probe=3781e31377) | Jul 12, 2021 |
| Olivetti | CL133A                      | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti | CL133A                      | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| HP       | EliteBook 8570p             | [ab19b80507](https://linux-hardware.org/?probe=ab19b80507) | Jun 09, 2021 |
| HUAWEI   | NBLK-WAX9X                  | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| HP       | Pavilion dv6000 (RP297UA... | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Dell     | Inspiron 5584               | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| Toshiba  | Satellite C845              | [e3b90e238b](https://linux-hardware.org/?probe=e3b90e238b) | May 24, 2021 |
| HP       | Laptop 14-ck0xxx            | [6f3c2aa3be](https://linux-hardware.org/?probe=6f3c2aa3be) | May 24, 2021 |
| HP       | Laptop 14-ck0xxx            | [8ccda2ce59](https://linux-hardware.org/?probe=8ccda2ce59) | May 24, 2021 |
| Toshiba  | Satellite C845              | [4d346e2691](https://linux-hardware.org/?probe=4d346e2691) | May 24, 2021 |
| Dell     | Inspiron 5584               | [5e2e76f838](https://linux-hardware.org/?probe=5e2e76f838) | May 20, 2021 |
| Acer     | Aspire A515-43              | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| Apple    | MacBookPro8,1               | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Lenovo   | IdeaPad S340-15API 81NC     | [93286a0d38](https://linux-hardware.org/?probe=93286a0d38) | May 15, 2021 |
| Lenovo   | IdeaPad S340-15API 81NC     | [796f490bbb](https://linux-hardware.org/?probe=796f490bbb) | May 15, 2021 |
| Dell     | Inspiron 5584               | [1da876ea0b](https://linux-hardware.org/?probe=1da876ea0b) | May 06, 2021 |
| Dell     | Inspiron 5584               | [0216a041d2](https://linux-hardware.org/?probe=0216a041d2) | May 05, 2021 |
| HP       | Laptop 15-da0xxx            | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| Acer     | Aspire A515-43              | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP       | Pavilion dv6                | [a181ae8691](https://linux-hardware.org/?probe=a181ae8691) | Apr 30, 2021 |
| HP       | Pavilion dv6                | [d363966e4c](https://linux-hardware.org/?probe=d363966e4c) | Apr 30, 2021 |
| HP       | Pavilion dv6                | [204cd9c44f](https://linux-hardware.org/?probe=204cd9c44f) | Apr 30, 2021 |
| HP       | Pavilion dv6                | [e20fc33e2b](https://linux-hardware.org/?probe=e20fc33e2b) | Apr 29, 2021 |
| Lenovo   | ThinkPad L14 Gen 1 20U10... | [3cca89aa74](https://linux-hardware.org/?probe=3cca89aa74) | Apr 28, 2021 |
| HP       | Laptop 15-da0xxx            | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Lenovo   | ThinkPad L14 Gen 1 20U10... | [38c505f6bd](https://linux-hardware.org/?probe=38c505f6bd) | Apr 23, 2021 |
| Apple    | MacBook2,1                  | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| HP       | Laptop 15-da0xxx            | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Lenovo   | IdeaPad S340-15API 81NC     | [e990abe7f1](https://linux-hardware.org/?probe=e990abe7f1) | Apr 11, 2021 |
| Lenovo   | IdeaPad S340-15API 81NC     | [41c14db0ef](https://linux-hardware.org/?probe=41c14db0ef) | Apr 11, 2021 |
| Dell     | G3 3590                     | [3c952dbc96](https://linux-hardware.org/?probe=3c952dbc96) | Mar 26, 2021 |
| Toshiba  | QOSMIO X775                 | [d8f82a3984](https://linux-hardware.org/?probe=d8f82a3984) | Mar 26, 2021 |
| HP       | OMEN by Laptop              | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| HP       | Pavilion g4                 | [1e7372e4f2](https://linux-hardware.org/?probe=1e7372e4f2) | Mar 01, 2021 |
| Toshiba  | Satellite C45-A             | [e00317dc4d](https://linux-hardware.org/?probe=e00317dc4d) | Mar 01, 2021 |
| Unknown  | Unknown                     | [941e941403](https://linux-hardware.org/?probe=941e941403) | Feb 27, 2021 |
| Dell     | Inspiron 5584               | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| Google   | Celes                       | [b30c090b2b](https://linux-hardware.org/?probe=b30c090b2b) | Feb 22, 2021 |
| Dell     | Inspiron 3558               | [41ba11dbb4](https://linux-hardware.org/?probe=41ba11dbb4) | Feb 18, 2021 |
| Dell     | Inspiron 5584               | [660afa073b](https://linux-hardware.org/?probe=660afa073b) | Feb 11, 2021 |
| Dell     | Inspiron 5584               | [840e0e2818](https://linux-hardware.org/?probe=840e0e2818) | Feb 04, 2021 |
| Dell     | Inspiron 5584               | [e10690d1d2](https://linux-hardware.org/?probe=e10690d1d2) | Feb 04, 2021 |
| HP       | Laptop 14-dq1xxx            | [84c932e071](https://linux-hardware.org/?probe=84c932e071) | Feb 02, 2021 |
| Dell     | Inspiron 5584               | [473419d486](https://linux-hardware.org/?probe=473419d486) | Jan 24, 2021 |
| Dell     | Inspiron 5584               | [738e03e488](https://linux-hardware.org/?probe=738e03e488) | Jan 23, 2021 |
| Dell     | Precision M4800             | [f24be700aa](https://linux-hardware.org/?probe=f24be700aa) | Jan 21, 2021 |
| Dell     | Precision M4800             | [316c7dd34b](https://linux-hardware.org/?probe=316c7dd34b) | Jan 21, 2021 |
| HP       | Laptop 14-bp0xx             | [4badbab2db](https://linux-hardware.org/?probe=4badbab2db) | Jan 19, 2021 |
| Dell     | Inspiron 5584               | [1a731e13e0](https://linux-hardware.org/?probe=1a731e13e0) | Jan 18, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [6a0e9eff49](https://linux-hardware.org/?probe=6a0e9eff49) | Jan 16, 2021 |
| Dell     | Inspiron 5584               | [76fe08b67a](https://linux-hardware.org/?probe=76fe08b67a) | Jan 14, 2021 |
| Dell     | Inspiron 5584               | [8d9be2defd](https://linux-hardware.org/?probe=8d9be2defd) | Jan 13, 2021 |
| Lenovo   | ThinkPad X1 Carbon 3rd 2... | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell     | Inspiron 5584               | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| Dell     | Inspiron 5584               | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell     | Inspiron 5584               | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| HP       | Laptop 14-bp0xx             | [a481e8e9c0](https://linux-hardware.org/?probe=a481e8e9c0) | Dec 16, 2020 |
| HP       | Laptop 14-bp0xx             | [266b8d7543](https://linux-hardware.org/?probe=266b8d7543) | Dec 16, 2020 |
| MSI      | GE60 2OC\2OD\2OE            | [a305c14111](https://linux-hardware.org/?probe=a305c14111) | Dec 13, 2020 |
| ASUSTek  | VivoBook_ASUSLaptop X512... | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| Dell     | Latitude 7480               | [2e569dcaed](https://linux-hardware.org/?probe=2e569dcaed) | Oct 22, 2020 |
| Dell     | Latitude 7480               | [1cc0a03f18](https://linux-hardware.org/?probe=1cc0a03f18) | Oct 22, 2020 |
| Dell     | XPS 15 9560                 | [9f10520397](https://linux-hardware.org/?probe=9f10520397) | Oct 11, 2020 |
| Dell     | G3 3590                     | [4c2ddd8b88](https://linux-hardware.org/?probe=4c2ddd8b88) | Oct 01, 2020 |
| Toshiba  | Satellite C55-B             | [6acb0908ff](https://linux-hardware.org/?probe=6acb0908ff) | Sep 18, 2020 |
| HP       | Unknown                     | [a446c81ca9](https://linux-hardware.org/?probe=a446c81ca9) | Sep 10, 2020 |
| HP       | EliteBook 8570p             | [48e494142e](https://linux-hardware.org/?probe=48e494142e) | Aug 27, 2020 |
| Toshiba  | Satellite X205              | [b0d5e7d0dd](https://linux-hardware.org/?probe=b0d5e7d0dd) | Aug 26, 2020 |
| Toshiba  | Satellite X205              | [45e52f3631](https://linux-hardware.org/?probe=45e52f3631) | Aug 26, 2020 |
| Acer     | Aspire 4739Z                | [44ec59d132](https://linux-hardware.org/?probe=44ec59d132) | Aug 11, 2020 |
| HP       | Pavilion dv2500             | [4bdd603282](https://linux-hardware.org/?probe=4bdd603282) | Aug 06, 2020 |
| HP       | Pavilion dv2500             | [4114f58581](https://linux-hardware.org/?probe=4114f58581) | Aug 06, 2020 |
| Dell     | Latitude E5440              | [9d31b1e38d](https://linux-hardware.org/?probe=9d31b1e38d) | Jul 29, 2020 |
| Dell     | G3 3590                     | [e2fa394ba6](https://linux-hardware.org/?probe=e2fa394ba6) | Jun 28, 2020 |
| Dell     | XPS 15 9560                 | [8119688776](https://linux-hardware.org/?probe=8119688776) | Jun 27, 2020 |
| Dell     | XPS 15 9560                 | [d2a2900148](https://linux-hardware.org/?probe=d2a2900148) | Jun 20, 2020 |
| Dell     | Inspiron 5559               | [4619502a6b](https://linux-hardware.org/?probe=4619502a6b) | May 28, 2020 |
| HP       | ProBook 455 G4              | [6b6fe8e0c1](https://linux-hardware.org/?probe=6b6fe8e0c1) | May 18, 2020 |
| HP       | 245 G4 Notebook PC          | [9311532f56](https://linux-hardware.org/?probe=9311532f56) | Apr 23, 2020 |
| HP       | 245 G4 Notebook PC          | [b662f230b2](https://linux-hardware.org/?probe=b662f230b2) | Apr 23, 2020 |
| HP       | Notebook                    | [5815277bb0](https://linux-hardware.org/?probe=5815277bb0) | Apr 22, 2020 |
| HP       | Laptop 15-da0xxx            | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [2f87bcd627](https://linux-hardware.org/?probe=2f87bcd627) | Apr 07, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [16ff51d343](https://linux-hardware.org/?probe=16ff51d343) | Apr 07, 2020 |
| Acer     | Aspire V3-471               | [024d5b0563](https://linux-hardware.org/?probe=024d5b0563) | Apr 06, 2020 |
| Dell     | G3 3590                     | [26a4f7e20b](https://linux-hardware.org/?probe=26a4f7e20b) | Mar 22, 2020 |
| Dell     | G3 3590                     | [96d9b68953](https://linux-hardware.org/?probe=96d9b68953) | Mar 21, 2020 |
| Toshiba  | Satellite C855D             | [9246f32b7e](https://linux-hardware.org/?probe=9246f32b7e) | Mar 01, 2020 |
| HP       | Pavilion Notebook           | [2bbf18e9e5](https://linux-hardware.org/?probe=2bbf18e9e5) | Feb 20, 2020 |
| HP       | Pavilion Notebook           | [68895d1461](https://linux-hardware.org/?probe=68895d1461) | Feb 20, 2020 |
| HP       | ProBook 6460b               | [121b074dd0](https://linux-hardware.org/?probe=121b074dd0) | Feb 19, 2020 |
| Dell     | Latitude 5500               | [3a7f8e19f1](https://linux-hardware.org/?probe=3a7f8e19f1) | Feb 17, 2020 |
| ASUSTek  | K52F                        | [9dde03d12c](https://linux-hardware.org/?probe=9dde03d12c) | Feb 13, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [9eb64d7269](https://linux-hardware.org/?probe=9eb64d7269) | Jan 17, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [8211b13acf](https://linux-hardware.org/?probe=8211b13acf) | Jan 17, 2020 |
| HP       | 240 G6 Notebook PC          | [73da3dccf1](https://linux-hardware.org/?probe=73da3dccf1) | Nov 14, 2019 |
| HP       | 240 G6 Notebook PC          | [efeee7f2fc](https://linux-hardware.org/?probe=efeee7f2fc) | Nov 14, 2019 |
| System76 | Lemur                       | [a9cc263cb4](https://linux-hardware.org/?probe=a9cc263cb4) | Oct 09, 2019 |
| HP       | ProBook 450 G2              | [c7959cccb3](https://linux-hardware.org/?probe=c7959cccb3) | Sep 30, 2019 |
| HP       | Notebook                    | [163fc3e9dd](https://linux-hardware.org/?probe=163fc3e9dd) | Sep 14, 2019 |
| ASUSTek  | Strix 17 GL703GE            | [c34161a66d](https://linux-hardware.org/?probe=c34161a66d) | Sep 02, 2019 |
| System76 | Lemur                       | [01bbf99115](https://linux-hardware.org/?probe=01bbf99115) | Sep 02, 2019 |
| Lenovo   | ThinkPad P53 20QNS00P00     | [47182bd3e3](https://linux-hardware.org/?probe=47182bd3e3) | Sep 01, 2019 |
| Lenovo   | ThinkPad P53 20QNS00P00     | [2105fa4def](https://linux-hardware.org/?probe=2105fa4def) | Sep 01, 2019 |
| HP       | Notebook                    | [b7e9995b67](https://linux-hardware.org/?probe=b7e9995b67) | Aug 18, 2019 |
| HP       | Notebook                    | [273d0bcc2e](https://linux-hardware.org/?probe=273d0bcc2e) | Aug 18, 2019 |
| Dell     | Venue 11 Pro 7130 vPro      | [2e5b92af00](https://linux-hardware.org/?probe=2e5b92af00) | Aug 17, 2019 |
| Dell     | Latitude E5450              | [3336801ccf](https://linux-hardware.org/?probe=3336801ccf) | Aug 10, 2019 |
| Toshiba  | Satellite A305D             | [ebf0a9c89e](https://linux-hardware.org/?probe=ebf0a9c89e) | Aug 08, 2019 |
| Acer     | SW5-017P                    | [fbf9b74a34](https://linux-hardware.org/?probe=fbf9b74a34) | Jul 29, 2019 |
| Dell     | Latitude 5480               | [f488cfd08f](https://linux-hardware.org/?probe=f488cfd08f) | Jun 22, 2019 |
| ASUSTek  | Strix 17 GL703GE            | [328975f3a5](https://linux-hardware.org/?probe=328975f3a5) | May 15, 2019 |
| Dell     | Latitude 5480               | [694ca16d49](https://linux-hardware.org/?probe=694ca16d49) | May 04, 2019 |
| Purism   | Librem 15 v3                | [00259367c8](https://linux-hardware.org/?probe=00259367c8) | Oct 29, 2018 |
| Purism   | Librem 15 v3                | [c5e1ab1520](https://linux-hardware.org/?probe=c5e1ab1520) | Oct 29, 2018 |
| ASUSTek  | X555LAB                     | [243803142a](https://linux-hardware.org/?probe=243803142a) | Aug 01, 2018 |
| Toshiba  | Satellite C645D             | [9d50eb7fdb](https://linux-hardware.org/?probe=9d50eb7fdb) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 14        | 7.45%   |
| Ubuntu 22.04                 | 12        | 6.38%   |
| Ubuntu 18.04                 | 12        | 6.38%   |
| OpenMandriva 4.2             | 7         | 3.72%   |
| Zorin 16                     | 6         | 3.19%   |
| Debian 12                    | 6         | 3.19%   |
| Ubuntu 19.04                 | 4         | 2.13%   |
| OpenMandriva 4.3             | 4         | 2.13%   |
| Debian 11                    | 4         | 2.13%   |
| Ubuntu 23.04                 | 3         | 1.6%    |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.6%    |
| OpenMandriva 23.08           | 3         | 1.6%    |
| Lubuntu 22.10                | 3         | 1.6%    |
| Lubuntu 22.04                | 3         | 1.6%    |
| Lubuntu 21.10                | 3         | 1.6%    |
| Lubuntu 21.04                | 3         | 1.6%    |
| Fedora 38                    | 3         | 1.6%    |
| Xubuntu 20.04                | 2         | 1.06%   |
| Ubuntu Studio 20.04          | 2         | 1.06%   |
| Ubuntu 21.04                 | 2         | 1.06%   |
| Pop!_OS 22.04                | 2         | 1.06%   |
| OpenMandriva 23.03           | 2         | 1.06%   |
| OpenMandriva 23.01           | 2         | 1.06%   |
| Manjaro 20.2.1               | 2         | 1.06%   |
| Lubuntu 23.10                | 2         | 1.06%   |
| Lubuntu 23.04                | 2         | 1.06%   |
| Linux Mint 21.2              | 2         | 1.06%   |
| Linux Mint 20.3              | 2         | 1.06%   |
| Linux Mint 20.1              | 2         | 1.06%   |
| Linux Mint 20                | 2         | 1.06%   |
| Kubuntu 22.04                | 2         | 1.06%   |
| KDE neon 20.04               | 2         | 1.06%   |
| Fedora 36                    | 2         | 1.06%   |
| Debian 10                    | 2         | 1.06%   |
| Zorin 15                     | 1         | 0.53%   |
| Xubuntu 18.04                | 1         | 0.53%   |
| UbuntuDDE 20.04              | 1         | 0.53%   |
| Ubuntu Unity 18.04           | 1         | 0.53%   |
| Ubuntu Unity 16.04           | 1         | 0.53%   |
| Ubuntu MATE 22.04            | 1         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 48        | 28.74%  |
| OpenMandriva  | 17        | 10.18%  |
| Debian        | 13        | 7.78%   |
| Linux Mint    | 11        | 6.59%   |
| Fedora        | 10        | 5.99%   |
| Zorin         | 7         | 4.19%   |
| Manjaro       | 6         | 3.59%   |
| Lubuntu       | 6         | 3.59%   |
| Pop!_OS       | 4         | 2.4%    |
| Kubuntu       | 4         | 2.4%    |
| Xubuntu       | 3         | 1.8%    |
| ROSA          | 3         | 1.8%    |
| openSUSE      | 3         | 1.8%    |
| KDE neon      | 3         | 1.8%    |
| Ubuntu Unity  | 2         | 1.2%    |
| Ubuntu Studio | 2         | 1.2%    |
| Ubuntu MATE   | 2         | 1.2%    |
| Parrot        | 2         | 1.2%    |
| Kali          | 2         | 1.2%    |
| Endless       | 2         | 1.2%    |
| UbuntuDDE     | 1         | 0.6%    |
| Ubuntu Budgie | 1         | 0.6%    |
| Reborn OS     | 1         | 0.6%    |
| PureOS        | 1         | 0.6%    |
| Peppermint    | 1         | 0.6%    |
| Nobara        | 1         | 0.6%    |
| Mageia        | 1         | 0.6%    |
| LMDE          | 1         | 0.6%    |
| LinuxFX       | 1         | 0.6%    |
| Elementary    | 1         | 0.6%    |
| Crystal Linux | 1         | 0.6%    |
| Clear Linux   | 1         | 0.6%    |
| ChimeraOS     | 1         | 0.6%    |
| BigLinux      | 1         | 0.6%    |
| ArcoLinux     | 1         | 0.6%    |
| Arch          | 1         | 0.6%    |
| ALT Linux     | 1         | 0.6%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 7         | 3.38%   |
| 5.16.7-desktop-1omv4003  | 4         | 1.93%   |
| 5.0.0-23-generic         | 4         | 1.93%   |
| 6.4.11-desktop-1omv2390  | 3         | 1.45%   |
| 5.4.0-77-generic         | 3         | 1.45%   |
| 5.4.0-42-generic         | 3         | 1.45%   |
| 5.19.0-32-generic        | 3         | 1.45%   |
| 5.19.0-26-generic        | 3         | 1.45%   |
| 5.13.0-16-generic        | 3         | 1.45%   |
| 5.11.0-27-generic        | 3         | 1.45%   |
| 5.0.0-25-generic         | 3         | 1.45%   |
| 6.5.0-5-generic          | 2         | 0.97%   |
| 6.3.8-200.fc38.x86_64    | 2         | 0.97%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.97%   |
| 6.2.0-20-generic         | 2         | 0.97%   |
| 6.2.0-18-generic         | 2         | 0.97%   |
| 6.1.0-10-amd64           | 2         | 0.97%   |
| 6.0.6-76060006-generic   | 2         | 0.97%   |
| 5.9.16-1-MANJARO         | 2         | 0.97%   |
| 5.8.0-50-generic         | 2         | 0.97%   |
| 5.4.0-21-generic         | 2         | 0.97%   |
| 5.3.0-40-generic         | 2         | 0.97%   |
| 5.3.0-28-generic         | 2         | 0.97%   |
| 5.15.0-91-generic        | 2         | 0.97%   |
| 5.15.0-83-generic        | 2         | 0.97%   |
| 5.15.0-58-generic        | 2         | 0.97%   |
| 5.15.0-52-generic        | 2         | 0.97%   |
| 5.15.0-41-generic        | 2         | 0.97%   |
| 5.13.0-35-generic        | 2         | 0.97%   |
| 5.13.0-20-generic        | 2         | 0.97%   |
| 5.11.0-16-generic        | 2         | 0.97%   |
| 4.15.0-112-generic       | 2         | 0.97%   |
| 6.6.6-1-default          | 1         | 0.48%   |
| 6.6.2-desktop-1omv2390   | 1         | 0.48%   |
| 6.6.2-custom             | 1         | 0.48%   |
| 6.5.9-200.fc38.x86_64    | 1         | 0.48%   |
| 6.5.11-300.fc39.x86_64   | 1         | 0.48%   |
| 6.5.0-7-generic          | 1         | 0.48%   |
| 6.5.0-0.deb12.1-amd64    | 1         | 0.48%   |
| 6.4.6-desktop-2.mga9     | 1         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 23        | 11.92%  |
| 5.15.0  | 21        | 10.88%  |
| 5.11.0  | 11        | 5.7%    |
| 5.19.0  | 10        | 5.18%   |
| 5.13.0  | 8         | 4.15%   |
| 5.0.0   | 8         | 4.15%   |
| 6.2.0   | 7         | 3.63%   |
| 5.3.0   | 7         | 3.63%   |
| 5.10.14 | 7         | 3.63%   |
| 5.10.0  | 7         | 3.63%   |
| 6.1.0   | 6         | 3.11%   |
| 5.8.0   | 5         | 2.59%   |
| 4.15.0  | 5         | 2.59%   |
| 6.5.0   | 4         | 2.07%   |
| 5.16.7  | 4         | 2.07%   |
| 6.4.11  | 3         | 1.55%   |
| 6.6.2   | 2         | 1.04%   |
| 6.3.8   | 2         | 1.04%   |
| 6.3.6   | 2         | 1.04%   |
| 6.2.6   | 2         | 1.04%   |
| 6.1.1   | 2         | 1.04%   |
| 6.0.6   | 2         | 1.04%   |
| 5.9.16  | 2         | 1.04%   |
| 5.18.13 | 2         | 1.04%   |
| 4.19.0  | 2         | 1.04%   |
| 6.6.6   | 1         | 0.52%   |
| 6.5.9   | 1         | 0.52%   |
| 6.5.11  | 1         | 0.52%   |
| 6.4.6   | 1         | 0.52%   |
| 6.3.4   | 1         | 0.52%   |
| 6.2.15  | 1         | 0.52%   |
| 6.1.6   | 1         | 0.52%   |
| 6.1.4   | 1         | 0.52%   |
| 6.1.20  | 1         | 0.52%   |
| 6.0.8   | 1         | 0.52%   |
| 6.0.7   | 1         | 0.52%   |
| 5.9.11  | 1         | 0.52%   |
| 5.8.6   | 1         | 0.52%   |
| 5.7.0   | 1         | 0.52%   |
| 5.2.11  | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 11.98%  |
| 5.15    | 22        | 11.46%  |
| 5.10    | 18        | 9.38%   |
| 5.11    | 14        | 7.29%   |
| 5.19    | 13        | 6.77%   |
| 6.1     | 11        | 5.73%   |
| 6.2     | 10        | 5.21%   |
| 5.0     | 9         | 4.69%   |
| 5.13    | 8         | 4.17%   |
| 5.3     | 7         | 3.65%   |
| 6.5     | 6         | 3.13%   |
| 5.8     | 6         | 3.13%   |
| 6.3     | 5         | 2.6%    |
| 4.15    | 5         | 2.6%    |
| 6.4     | 4         | 2.08%   |
| 6.0     | 4         | 2.08%   |
| 5.16    | 4         | 2.08%   |
| 6.6     | 3         | 1.56%   |
| 5.9     | 3         | 1.56%   |
| 5.18    | 3         | 1.56%   |
| 5.12    | 3         | 1.56%   |
| 4.19    | 3         | 1.56%   |
| 4.18    | 2         | 1.04%   |
| 5.7     | 1         | 0.52%   |
| 5.2     | 1         | 0.52%   |
| 5.17    | 1         | 0.52%   |
| 5.14    | 1         | 0.52%   |
| 4.9     | 1         | 0.52%   |
| 4.1     | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 156       | 98.73%  |
| i686   | 2         | 1.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 76        | 46.34%  |
| KDE5       | 28        | 17.07%  |
| Unknown    | 15        | 9.15%   |
| XFCE       | 12        | 7.32%   |
| MATE       | 7         | 4.27%   |
| LXQt       | 7         | 4.27%   |
| X-Cinnamon | 6         | 3.66%   |
| KDE        | 3         | 1.83%   |
| Unity      | 2         | 1.22%   |
| i3         | 2         | 1.22%   |
| Pantheon   | 1         | 0.61%   |
| onyx:GNOME | 1         | 0.61%   |
| LXDE       | 1         | 0.61%   |
| Deepin     | 1         | 0.61%   |
| Cinnamon   | 1         | 0.61%   |
| Budgie     | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 112       | 70%     |
| Wayland | 38        | 23.75%  |
| Unknown | 8         | 5%      |
| Tty     | 2         | 1.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 64        | 39.75%  |
| SDDM    | 35        | 21.74%  |
| GDM3    | 23        | 14.29%  |
| LightDM | 16        | 9.94%   |
| GDM     | 15        | 9.32%   |
| TDM     | 8         | 4.97%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 74        | 45.96%  |
| es_CR   | 56        | 34.78%  |
| Unknown | 14        | 8.7%    |
| es_ES   | 10        | 6.21%   |
| es_MX   | 2         | 1.24%   |
| C       | 2         | 1.24%   |
| fr_FR   | 1         | 0.62%   |
| es_EC   | 1         | 0.62%   |
| en_AG   | 1         | 0.62%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 86        | 52.76%  |
| BIOS | 77        | 47.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 116       | 72.05%  |
| Btrfs   | 18        | 11.18%  |
| Overlay | 17        | 10.56%  |
| Tmpfs   | 5         | 3.11%   |
| Unknown | 4         | 2.48%   |
| Xfs     | 1         | 0.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 73        | 45.91%  |
| GPT     | 66        | 41.51%  |
| MBR     | 20        | 12.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 89.44%  |
| Yes       | 17        | 10.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 63.13%  |
| Yes       | 59        | 36.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 38        | 24.05%  |
| Dell                | 33        | 20.89%  |
| Lenovo              | 26        | 16.46%  |
| Toshiba             | 14        | 8.86%   |
| ASUSTek Computer    | 13        | 8.23%   |
| Acer                | 11        | 6.96%   |
| Apple               | 7         | 4.43%   |
| MSI                 | 4         | 2.53%   |
| Sony                | 2         | 1.27%   |
| Google              | 2         | 1.27%   |
| System76            | 1         | 0.63%   |
| Samsung Electronics | 1         | 0.63%   |
| Purism              | 1         | 0.63%   |
| Olivetti            | 1         | 0.63%   |
| HUAWEI              | 1         | 0.63%   |
| Deffad              | 1         | 0.63%   |
| AZW                 | 1         | 0.63%   |
| Unknown             | 1         | 0.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Apple MacBookPro8,1                          | 4         | 2.53%   |
| Unknown                                      | 4         | 2.53%   |
| HP Notebook                                  | 3         | 1.9%    |
| HP Laptop 15-da0xxx                          | 3         | 1.9%    |
| Dell Inspiron 5584                           | 3         | 1.9%    |
| HP ProBook 6460b                             | 2         | 1.27%   |
| HP Pavilion Notebook                         | 2         | 1.27%   |
| Toshiba Satellite X205                       | 1         | 0.63%   |
| Toshiba Satellite S55-A                      | 1         | 0.63%   |
| Toshiba Satellite L845                       | 1         | 0.63%   |
| Toshiba Satellite L755                       | 1         | 0.63%   |
| Toshiba Satellite L655                       | 1         | 0.63%   |
| Toshiba Satellite L45-B                      | 1         | 0.63%   |
| Toshiba Satellite C855D                      | 1         | 0.63%   |
| Toshiba Satellite C845                       | 1         | 0.63%   |
| Toshiba Satellite C645D                      | 1         | 0.63%   |
| Toshiba Satellite C55-C                      | 1         | 0.63%   |
| Toshiba Satellite C55-B                      | 1         | 0.63%   |
| Toshiba Satellite C45-A                      | 1         | 0.63%   |
| Toshiba Satellite A305D                      | 1         | 0.63%   |
| Toshiba QOSMIO X775                          | 1         | 0.63%   |
| System76 Lemur                               | 1         | 0.63%   |
| Sony SVE14123CLW                             | 1         | 0.63%   |
| Sony SVD13215PLB                             | 1         | 0.63%   |
| Samsung 930X2K/931X2K                        | 1         | 0.63%   |
| Purism Librem 15 v3                          | 1         | 0.63%   |
| Olivetti CL133A                              | 1         | 0.63%   |
| MSI Katana 15 B13VGK                         | 1         | 0.63%   |
| MSI GF75 Thin 9SD                            | 1         | 0.63%   |
| MSI GF65 Thin 10SDR                          | 1         | 0.63%   |
| MSI GE60 2OC\2OD\2OE                         | 1         | 0.63%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y50010US | 1         | 0.63%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1EY00     | 1         | 0.63%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US     | 1         | 0.63%   |
| Lenovo ThinkPad T60 1952F75                  | 1         | 0.63%   |
| Lenovo ThinkPad T470 W10DG 20JM000CUS        | 1         | 0.63%   |
| Lenovo ThinkPad T440s 20ARS29U00             | 1         | 0.63%   |
| Lenovo ThinkPad T420 4236DA4                 | 1         | 0.63%   |
| Lenovo ThinkPad P53 20QNS00P00               | 1         | 0.63%   |
| Lenovo ThinkPad P50 20EN001PUS               | 1         | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 18        | 11.39%  |
| Toshiba Satellite | 13        | 8.23%   |
| Dell Inspiron     | 13        | 8.23%   |
| Dell Latitude     | 12        | 7.59%   |
| Acer Aspire       | 9         | 5.7%    |
| HP Pavilion       | 8         | 5.06%   |
| HP Laptop         | 7         | 4.43%   |
| HP EliteBook      | 7         | 4.43%   |
| Lenovo IdeaPad    | 6         | 3.8%    |
| HP ProBook        | 5         | 3.16%   |
| ASUS VivoBook     | 4         | 2.53%   |
| Apple MacBookPro8 | 4         | 2.53%   |
| Unknown           | 4         | 2.53%   |
| HP Notebook       | 3         | 1.9%    |
| Dell XPS          | 3         | 1.9%    |
| Dell G3           | 2         | 1.27%   |
| Toshiba QOSMIO    | 1         | 0.63%   |
| System76 Lemur    | 1         | 0.63%   |
| Sony SVE14123CLW  | 1         | 0.63%   |
| Sony SVD13215PLB  | 1         | 0.63%   |
| Samsung 930X2K    | 1         | 0.63%   |
| Purism Librem     | 1         | 0.63%   |
| Olivetti CL133A   | 1         | 0.63%   |
| MSI Katana        | 1         | 0.63%   |
| MSI GF75          | 1         | 0.63%   |
| MSI GF65          | 1         | 0.63%   |
| MSI GE60          | 1         | 0.63%   |
| Lenovo Legion     | 1         | 0.63%   |
| Lenovo B590       | 1         | 0.63%   |
| HUAWEI NBLK-WAX9X | 1         | 0.63%   |
| HP OMEN           | 1         | 0.63%   |
| HP Mini           | 1         | 0.63%   |
| HP G60            | 1         | 0.63%   |
| HP ENVY           | 1         | 0.63%   |
| HP 245            | 1         | 0.63%   |
| HP 240            | 1         | 0.63%   |
| Google Snappy     | 1         | 0.63%   |
| Google Celes      | 1         | 0.63%   |
| Dell Venue        | 1         | 0.63%   |
| Dell Precision    | 1         | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 21        | 13.29%  |
| 2011 | 17        | 10.76%  |
| 2018 | 16        | 10.13%  |
| 2012 | 14        | 8.86%   |
| 2020 | 13        | 8.23%   |
| 2016 | 10        | 6.33%   |
| 2014 | 10        | 6.33%   |
| 2017 | 9         | 5.7%    |
| 2015 | 9         | 5.7%    |
| 2021 | 8         | 5.06%   |
| 2013 | 8         | 5.06%   |
| 2008 | 5         | 3.16%   |
| 2009 | 4         | 2.53%   |
| 2023 | 3         | 1.9%    |
| 2010 | 3         | 1.9%    |
| 2007 | 3         | 1.9%    |
| 2006 | 3         | 1.9%    |
| 2022 | 2         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 158       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 145       | 91.77%  |
| Enabled  | 13        | 8.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 155       | 98.1%   |
| Yes  | 3         | 1.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 47        | 29.01%  |
| 3.01-4.0    | 34        | 20.99%  |
| 8.01-16.0   | 33        | 20.37%  |
| 16.01-24.0  | 23        | 14.2%   |
| 32.01-64.0  | 10        | 6.17%   |
| 24.01-32.0  | 4         | 2.47%   |
| 1.01-2.0    | 4         | 2.47%   |
| 2.01-3.0    | 3         | 1.85%   |
| 64.01-256.0 | 3         | 1.85%   |
| 0.51-1.0    | 1         | 0.62%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 70        | 40.23%  |
| 2.01-3.0   | 45        | 25.86%  |
| 4.01-8.0   | 23        | 13.22%  |
| 3.01-4.0   | 22        | 12.64%  |
| 8.01-16.0  | 6         | 3.45%   |
| 0.51-1.0   | 6         | 3.45%   |
| 16.01-24.0 | 2         | 1.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 120       | 75.95%  |
| 2      | 35        | 22.15%  |
| 3      | 3         | 1.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 89        | 56.33%  |
| Yes       | 69        | 43.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 85.44%  |
| No        | 23        | 14.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 98.1%   |
| No        | 3         | 1.9%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 74.21%  |
| No        | 41        | 25.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Costa Rica | 158       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San José     | 71        | 40.11%  |
| Heredia       | 28        | 15.82%  |
| Alajuela      | 14        | 7.91%   |
| Cartago       | 6         | 3.39%   |
| Quesada       | 5         | 2.82%   |
| Grecia        | 5         | 2.82%   |
| Rio Segundo   | 4         | 2.26%   |
| Puntarenas    | 4         | 2.26%   |
| Escazu        | 4         | 2.26%   |
| San Ramon     | 3         | 1.69%   |
| Siquirres     | 2         | 1.13%   |
| Santa Cruz    | 2         | 1.13%   |
| Naranjo       | 2         | 1.13%   |
| Esparza       | 2         | 1.13%   |
| Colon         | 2         | 1.13%   |
| Bagaces       | 2         | 1.13%   |
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
| Perez Zeledon | 1         | 0.56%   |
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
| WDC                         | 26        | 40     | 13.54%  |
| Toshiba                     | 22        | 27     | 11.46%  |
| Seagate                     | 21        | 29     | 10.94%  |
| Samsung Electronics         | 21        | 31     | 10.94%  |
| Kingston                    | 13        | 17     | 6.77%   |
| Intel                       | 12        | 32     | 6.25%   |
| Unknown                     | 9         | 13     | 4.69%   |
| HGST                        | 9         | 10     | 4.69%   |
| A-DATA Technology           | 8         | 8      | 4.17%   |
| SK hynix                    | 5         | 11     | 2.6%    |
| Sandisk                     | 5         | 5      | 2.6%    |
| Patriot                     | 5         | 5      | 2.6%    |
| Micron Technology           | 5         | 6      | 2.6%    |
| Crucial                     | 5         | 5      | 2.6%    |
| Team                        | 3         | 3      | 1.56%   |
| Netac                       | 3         | 3      | 1.56%   |
| KIOXIA                      | 2         | 2      | 1.04%   |
| Kingston Technology Company | 2         | 2      | 1.04%   |
| JMicron Technology          | 2         | 2      | 1.04%   |
| Hitachi                     | 2         | 3      | 1.04%   |
| Zheino                      | 1         | 1      | 0.52%   |
| UMIS                        | 1         | 1      | 0.52%   |
| Transcend                   | 1         | 1      | 0.52%   |
| Silicon Motion              | 1         | 1      | 0.52%   |
| Mushkin                     | 1         | 1      | 0.52%   |
| LITEONIT                    | 1         | 1      | 0.52%   |
| LITEON                      | 1         | 1      | 0.52%   |
| Gigabyte Technology         | 1         | 1      | 0.52%   |
| Fujitsu                     | 1         | 1      | 0.52%   |
| Dell                        | 1         | 1      | 0.52%   |
| BP4                         | 1         | 1      | 0.52%   |
| Unknown                     | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                            | 6         | 2.96%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 2.46%   |
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 2.46%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 1.97%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 1.48%   |
| Toshiba KBG30ZMS256G NVMe 256GB                     | 3         | 1.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 1.48%   |
| Intel SSDSC2BF180A4H 180GB                          | 3         | 1.48%   |
| Intel SSDSA2CW300G3 304GB                           | 3         | 1.48%   |
| HGST HTS541010A9E680 1TB                            | 3         | 1.48%   |
| WDC WD20SPZX-08UA7 2TB                              | 2         | 0.99%   |
| Unknown MMC Card  128GB                             | 2         | 0.99%   |
| Toshiba NVMe SSD Drive 256GB                        | 2         | 0.99%   |
| SK hynix NVMe SSD Drive 128GB                       | 2         | 0.99%   |
| Seagate ST9500325AS 500GB                           | 2         | 0.99%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 0.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 0.99%   |
| Netac SSD 120GB                                     | 2         | 0.99%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.99%   |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.99%   |
| JMicron Generic 2TB                                 | 2         | 0.99%   |
| Intel SSDSC2MH250A2 250GB                           | 2         | 0.99%   |
| HGST HTS541075A9E680 752GB                          | 2         | 0.99%   |
| Zheino CHN 25SATAA3 240 240GB                       | 1         | 0.49%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.49%   |
| WDC WDS120G1G0B-00RC30 120GB SSD                    | 1         | 0.49%   |
| WDC WD800BEVT-75ZCT2 80GB                           | 1         | 0.49%   |
| WDC WD7500BPVT-22HXZT3 752GB                        | 1         | 0.49%   |
| WDC WD5000LPVX-80V0TT0 500GB                        | 1         | 0.49%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 0.49%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 0.49%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 0.49%   |
| WDC WD5000BPKT-60PK4T0 500GB                        | 1         | 0.49%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 0.49%   |
| WDC WD1600BEVT-75A23T0 160GB                        | 1         | 0.49%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.49%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 0.49%   |
| WDC WD10SPZX-08Z10 1TB                              | 1         | 0.49%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 20        | 28     | 29.41%  |
| Toshiba | 19        | 20     | 27.94%  |
| WDC     | 17        | 20     | 25%     |
| HGST    | 9         | 10     | 13.24%  |
| Hitachi | 2         | 3      | 2.94%   |
| Fujitsu | 1         | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 12        | 12     | 16.67%  |
| Intel               | 8         | 22     | 11.11%  |
| WDC                 | 7         | 15     | 9.72%   |
| Samsung Electronics | 7         | 16     | 9.72%   |
| A-DATA Technology   | 7         | 7      | 9.72%   |
| Patriot             | 5         | 5      | 6.94%   |
| Micron Technology   | 4         | 4      | 5.56%   |
| Crucial             | 4         | 4      | 5.56%   |
| Team                | 3         | 3      | 4.17%   |
| SanDisk             | 3         | 3      | 4.17%   |
| Netac               | 3         | 3      | 4.17%   |
| JMicron Technology  | 2         | 2      | 2.78%   |
| Transcend           | 1         | 1      | 1.39%   |
| Seagate             | 1         | 1      | 1.39%   |
| Mushkin             | 1         | 1      | 1.39%   |
| LITEONIT            | 1         | 1      | 1.39%   |
| LITEON              | 1         | 1      | 1.39%   |
| Gigabyte Technology | 1         | 1      | 1.39%   |
| BP4                 | 1         | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 68        | 103    | 36.56%  |
| HDD     | 68        | 82     | 36.56%  |
| NVMe    | 39        | 66     | 20.97%  |
| MMC     | 9         | 13     | 4.84%   |
| Unknown | 2         | 2      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 128       | 183    | 71.11%  |
| NVMe | 38        | 65     | 21.11%  |
| MMC  | 9         | 13     | 5%      |
| SAS  | 5         | 5      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 83        | 111    | 61.03%  |
| 0.51-1.0   | 42        | 62     | 30.88%  |
| 1.01-2.0   | 11        | 12     | 8.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 49        | 29.34%  |
| 251-500        | 32        | 19.16%  |
| 501-1000       | 28        | 16.77%  |
| 1-20           | 15        | 8.98%   |
| 1001-2000      | 12        | 7.19%   |
| 51-100         | 11        | 6.59%   |
| 21-50          | 9         | 5.39%   |
| More than 3000 | 4         | 2.4%    |
| 2001-3000      | 4         | 2.4%    |
| Unknown        | 3         | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 78        | 44.32%  |
| 21-50     | 30        | 17.05%  |
| 51-100    | 23        | 13.07%  |
| 101-250   | 19        | 10.8%   |
| 251-500   | 14        | 7.95%   |
| 501-1000  | 8         | 4.55%   |
| Unknown   | 3         | 1.7%    |
| 1001-2000 | 1         | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 6.67%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 6.67%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 6.67%   |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 6.67%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 6.67%   |
| Seagate ST9320310AS 320GB                           | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 6.67%   |
| Netac SSD 120GB                                     | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 6.67%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 6.67%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 6.67%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 6.67%   |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 4         | 4      | 26.67%  |
| Seagate           | 3         | 3      | 20%     |
| WDC               | 2         | 2      | 13.33%  |
| HGST              | 2         | 2      | 13.33%  |
| Netac             | 1         | 1      | 6.67%   |
| Micron Technology | 1         | 1      | 6.67%   |
| Intel             | 1         | 1      | 6.67%   |
| Hitachi           | 1         | 2      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 33.33%  |
| Seagate | 3         | 3      | 25%     |
| WDC     | 2         | 2      | 16.67%  |
| HGST    | 2         | 2      | 16.67%  |
| Hitachi | 1         | 2      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 13     | 80%     |
| SSD  | 3         | 3      | 20%     |

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
| Detected | 86        | 140    | 52.12%  |
| Works    | 64        | 110    | 38.79%  |
| Malfunc  | 15        | 16     | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 119       | 65.38%  |
| AMD                          | 20        | 10.99%  |
| Samsung Electronics          | 14        | 7.69%   |
| SanDisk                      | 5         | 2.75%   |
| SK hynix                     | 4         | 2.2%    |
| Toshiba America Info Systems | 3         | 1.65%   |
| Kingston Technology Company  | 3         | 1.65%   |
| Nvidia                       | 2         | 1.1%    |
| Micron Technology            | 2         | 1.1%    |
| KIOXIA                       | 2         | 1.1%    |
| ASMedia Technology           | 2         | 1.1%    |
| Union Memory (Shenzhen)      | 1         | 0.55%   |
| Solidigm                     | 1         | 0.55%   |
| Silicon Motion               | 1         | 0.55%   |
| Realtek Semiconductor        | 1         | 0.55%   |
| Micron/Crucial Technology    | 1         | 0.55%   |
| ADATA Technology             | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 18        | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 16        | 8.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 15        | 7.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 14        | 7.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 12        | 6.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 4.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 7         | 3.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 5         | 2.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 2.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 2.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 2.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 4         | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 2.02%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                    | 3         | 1.52%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 3         | 1.52%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 3         | 1.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.52%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 1.01%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                              | 2         | 1.01%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                  | 2         | 1.01%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 1.01%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                       | 2         | 1.01%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 1.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 1.01%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 2         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 1.01%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                                  | 1         | 0.51%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]                                   | 1         | 0.51%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 1         | 0.51%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 1         | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 1         | 0.51%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                          | 1         | 0.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.51%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                      | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 115       | 61.83%  |
| NVMe | 39        | 20.97%  |
| RAID | 16        | 8.6%    |
| IDE  | 16        | 8.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 133       | 84.18%  |
| AMD    | 25        | 15.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz               | 6         | 3.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz               | 4         | 2.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 4         | 2.53%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 4         | 2.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 3         | 1.9%    |
| Intel Core i7-2640M CPU @ 2.80GHz               | 3         | 1.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz               | 3         | 1.9%    |
| Intel Celeron N4000 CPU @ 1.10GHz               | 3         | 1.9%    |
| Intel Celeron CPU N3060 @ 1.60GHz               | 3         | 1.9%    |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 1.27%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 2         | 1.27%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 1.27%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 1.27%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 1.27%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 2         | 1.27%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 2         | 1.27%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 2         | 1.27%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 2         | 1.27%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 2         | 1.27%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 2         | 1.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.27%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 2         | 1.27%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz            | 1         | 0.63%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 0.63%   |
| Intel Pentium CPU P6100 @ 2.00GHz               | 1         | 0.63%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.63%   |
| Intel Genuine CPU U4100 @ 1.30GHz               | 1         | 0.63%   |
| Intel Genuine CPU T2060 @ 1.60GHz               | 1         | 0.63%   |
| Intel Core M-5Y31 CPU @ 0.90GHz                 | 1         | 0.63%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.63%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 0.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 0.63%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 40        | 25.32%  |
| Intel Core i5                  | 36        | 22.78%  |
| Intel Core i3                  | 17        | 10.76%  |
| Intel Celeron                  | 13        | 8.23%   |
| Other                          | 11        | 6.96%   |
| AMD Ryzen 7                    | 6         | 3.8%    |
| Intel Core 2 Duo               | 4         | 2.53%   |
| AMD Ryzen 5                    | 4         | 2.53%   |
| Intel Core 2                   | 3         | 1.9%    |
| Intel Atom                     | 3         | 1.9%    |
| AMD A10                        | 3         | 1.9%    |
| Intel Pentium                  | 2         | 1.27%   |
| Intel Genuine                  | 2         | 1.27%   |
| AMD Ryzen 3                    | 2         | 1.27%   |
| AMD E1                         | 2         | 1.27%   |
| AMD A8                         | 2         | 1.27%   |
| Intel Xeon                     | 1         | 0.63%   |
| Intel Pentium Dual-Core        | 1         | 0.63%   |
| Intel Core M                   | 1         | 0.63%   |
| AMD V120                       | 1         | 0.63%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.63%   |
| AMD Turion 64 X2               | 1         | 0.63%   |
| AMD PRO A10                    | 1         | 0.63%   |
| AMD Athlon                     | 1         | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 100       | 63.29%  |
| 4      | 36        | 22.78%  |
| 6      | 10        | 6.33%   |
| 8      | 7         | 4.43%   |
| 1      | 2         | 1.27%   |
| 24     | 1         | 0.63%   |
| 16     | 1         | 0.63%   |
| 10     | 1         | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 158       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 118       | 74.68%  |
| 1      | 40        | 25.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 155       | 97.48%  |
| 32-bit         | 2         | 1.26%   |
| Unknown        | 2         | 1.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 29.27%  |
| 0x206a7    | 14        | 8.54%   |
| 0x40651    | 7         | 4.27%   |
| 0x406e3    | 6         | 3.66%   |
| 0x306d4    | 6         | 3.66%   |
| 0x306a9    | 6         | 3.66%   |
| 0x08108109 | 6         | 3.66%   |
| 0x806ec    | 5         | 3.05%   |
| 0x806e9    | 5         | 3.05%   |
| 0x406c4    | 5         | 3.05%   |
| 0x906ea    | 4         | 2.44%   |
| 0x706a1    | 4         | 2.44%   |
| 0x306c3    | 4         | 2.44%   |
| 0x1067a    | 4         | 2.44%   |
| 0x806eb    | 3         | 1.83%   |
| 0x806ea    | 3         | 1.83%   |
| 0x20655    | 3         | 1.83%   |
| 0x806c1    | 2         | 1.22%   |
| 0x6fd      | 2         | 1.22%   |
| 0x506e3    | 2         | 1.22%   |
| 0xb06a2    | 1         | 0.61%   |
| 0xa0652    | 1         | 0.61%   |
| 0x906ed    | 1         | 0.61%   |
| 0x906e9    | 1         | 0.61%   |
| 0x706a8    | 1         | 0.61%   |
| 0x6f6      | 1         | 0.61%   |
| 0x6ec      | 1         | 0.61%   |
| 0x506c9    | 1         | 0.61%   |
| 0x30678    | 1         | 0.61%   |
| 0x106c2    | 1         | 0.61%   |
| 0x0a50000d | 1         | 0.61%   |
| 0x08a00006 | 1         | 0.61%   |
| 0x08608102 | 1         | 0.61%   |
| 0x08600106 | 1         | 0.61%   |
| 0x08600104 | 1         | 0.61%   |
| 0x08600103 | 1         | 0.61%   |
| 0x07030105 | 1         | 0.61%   |
| 0x07000110 | 1         | 0.61%   |
| 0x06006118 | 1         | 0.61%   |
| 0x06006110 | 1         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 29        | 18.35%  |
| SandyBridge      | 22        | 13.92%  |
| Haswell          | 13        | 8.23%   |
| IvyBridge        | 10        | 6.33%   |
| Skylake          | 9         | 5.7%    |
| Broadwell        | 8         | 5.06%   |
| Zen+             | 7         | 4.43%   |
| Silvermont       | 7         | 4.43%   |
| Unknown          | 6         | 3.8%    |
| Goldmont plus    | 5         | 3.16%   |
| Core             | 5         | 3.16%   |
| TigerLake        | 4         | 2.53%   |
| Penryn           | 4         | 2.53%   |
| IceLake          | 4         | 2.53%   |
| Excavator        | 4         | 2.53%   |
| Zen 2            | 3         | 1.9%    |
| Westmere         | 3         | 1.9%    |
| Alderlake Hybrid | 2         | 1.27%   |
| Zen 3            | 1         | 0.63%   |
| Puma             | 1         | 0.63%   |
| Piledriver       | 1         | 0.63%   |
| P6               | 1         | 0.63%   |
| K8 Hammer        | 1         | 0.63%   |
| K8 & K10 hybrid  | 1         | 0.63%   |
| K10 Llano        | 1         | 0.63%   |
| K10              | 1         | 0.63%   |
| Jaguar           | 1         | 0.63%   |
| Goldmont         | 1         | 0.63%   |
| CometLake        | 1         | 0.63%   |
| Bonnell          | 1         | 0.63%   |
| Bobcat           | 1         | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 126       | 65.63%  |
| Nvidia | 36        | 18.75%  |
| AMD    | 30        | 15.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 8.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 3.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 3.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.47%   |
| Intel HD Graphics 620                                                                    | 7         | 3.47%   |
| Intel HD Graphics 5500                                                                   | 7         | 3.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.97%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.48%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 2.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 2.48%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 1.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.98%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.49%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.49%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.49%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.49%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.49%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.49%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.99%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.99%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.99%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.5%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.5%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.5%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.5%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.5%    |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.5%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.5%    |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.5%    |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.5%    |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 94        | 59.49%  |
| Intel + Nvidia | 29        | 18.35%  |
| 1 x AMD        | 21        | 13.29%  |
| 2 x AMD        | 4         | 2.53%   |
| 1 x Nvidia     | 4         | 2.53%   |
| AMD + Nvidia   | 3         | 1.9%    |
| Intel + AMD    | 2         | 1.27%   |
| Other          | 1         | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 139       | 87.42%  |
| Proprietary | 18        | 11.32%  |
| Unknown     | 2         | 1.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 118       | 73.75%  |
| 1.01-2.0   | 14        | 8.75%   |
| 0.01-0.5   | 12        | 7.5%    |
| 3.01-4.0   | 8         | 5%      |
| 0.51-1.0   | 6         | 3.75%   |
| 5.01-6.0   | 2         | 1.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 40        | 20.62%  |
| LG Display              | 31        | 15.98%  |
| Samsung Electronics     | 21        | 10.82%  |
| Chimei Innolux          | 21        | 10.82%  |
| BOE                     | 21        | 10.82%  |
| Goldstar                | 7         | 3.61%   |
| Dell                    | 7         | 3.61%   |
| Apple                   | 7         | 3.61%   |
| AOC                     | 6         | 3.09%   |
| Chi Mei Optoelectronics | 4         | 2.06%   |
| Sony                    | 2         | 1.03%   |
| Sharp                   | 2         | 1.03%   |
| PANDA                   | 2         | 1.03%   |
| Hewlett-Packard         | 2         | 1.03%   |
| CPT                     | 2         | 1.03%   |
| ASUSTek Computer        | 2         | 1.03%   |
| Acer                    | 2         | 1.03%   |
| ViewSonic               | 1         | 0.52%   |
| Sun                     | 1         | 0.52%   |
| RTK                     | 1         | 0.52%   |
| PRISM+                  | 1         | 0.52%   |
| Panasonic               | 1         | 0.52%   |
| LG Philips              | 1         | 0.52%   |
| Lenovo                  | 1         | 0.52%   |
| KDC                     | 1         | 0.52%   |
| InnoLux Display         | 1         | 0.52%   |
| Hitachi                 | 1         | 0.52%   |
| GAOMON                  | 1         | 0.52%   |
| Envision                | 1         | 0.52%   |
| CVT                     | 1         | 0.52%   |
| Ancor Communications    | 1         | 0.52%   |
| AGO                     | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 5         | 2.58%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3         | 1.55%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 1.55%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.55%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 2         | 1.03%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 1.03%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 2         | 1.03%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch           | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 1.03%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 1.03%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.03%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.03%   |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch         | 1         | 0.52%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1         | 0.52%   |
| Sony TV SNY1B02 1360x768                                              | 1         | 0.52%   |
| Sony TV SNY0902 1920x1080                                             | 1         | 0.52%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.52%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM058A 1920x1080 531x298mm 24.0-inch  | 1         | 0.52%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC345A 1366x768 309x174mm 14.0-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3352 1024x576 223x125mm 10.1-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 69        | 38.12%  |
| 1920x1080 (FHD)    | 59        | 32.6%   |
| 3840x2160 (4K)     | 12        | 6.63%   |
| 1280x800 (WXGA)    | 11        | 6.08%   |
| 1600x900 (HD+)     | 9         | 4.97%   |
| 1440x900 (WXGA+)   | 4         | 2.21%   |
| 1280x1024 (SXGA)   | 4         | 2.21%   |
| 2560x1440 (QHD)    | 3         | 1.66%   |
| 1920x1200 (WUXGA)  | 2         | 1.1%    |
| 1360x768           | 2         | 1.1%    |
| 3840x2400          | 1         | 0.55%   |
| 3200x2000          | 1         | 0.55%   |
| 2560x1600          | 1         | 0.55%   |
| 1680x1050 (WSXGA+) | 1         | 0.55%   |
| 1400x1050          | 1         | 0.55%   |
| 1024x576           | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 77        | 40.1%   |
| 14     | 30        | 15.63%  |
| 13     | 28        | 14.58%  |
| 17     | 8         | 4.17%   |
| 21     | 7         | 3.65%   |
| 23     | 6         | 3.13%   |
| 24     | 4         | 2.08%   |
| 19     | 4         | 2.08%   |
| 18     | 4         | 2.08%   |
| 84     | 3         | 1.56%   |
| 31     | 3         | 1.56%   |
| 16     | 3         | 1.56%   |
| 12     | 3         | 1.56%   |
| 11     | 3         | 1.56%   |
| 72     | 2         | 1.04%   |
| 57     | 2         | 1.04%   |
| 27     | 2         | 1.04%   |
| 32     | 1         | 0.52%   |
| 20     | 1         | 0.52%   |
| 10     | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 129       | 67.89%  |
| 201-300     | 16        | 8.42%   |
| 401-500     | 14        | 7.37%   |
| 501-600     | 12        | 6.32%   |
| 351-400     | 8         | 4.21%   |
| 1501-2000   | 5         | 2.63%   |
| 601-700     | 3         | 1.58%   |
| 701-800     | 2         | 1.05%   |
| 1001-1500   | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 137       | 82.53%  |
| 16/10 | 22        | 13.25%  |
| 5/4   | 4         | 2.41%   |
| 4/3   | 2         | 1.2%    |
| 0.56  | 1         | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 77        | 40.31%  |
| 81-90          | 55        | 28.8%   |
| 201-250        | 14        | 7.33%   |
| More than 1000 | 7         | 3.66%   |
| 151-200        | 7         | 3.66%   |
| 141-150        | 5         | 2.62%   |
| 121-130        | 5         | 2.62%   |
| 351-500        | 4         | 2.09%   |
| 71-80          | 3         | 1.57%   |
| 51-60          | 3         | 1.57%   |
| 111-120        | 3         | 1.57%   |
| 61-70          | 2         | 1.05%   |
| 301-350        | 2         | 1.05%   |
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
| 101-120       | 83        | 44.15%  |
| 121-160       | 64        | 34.04%  |
| 51-100        | 28        | 14.89%  |
| More than 240 | 5         | 2.66%   |
| 1-50          | 5         | 2.66%   |
| 161-240       | 3         | 1.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 123       | 74.55%  |
| 2     | 36        | 21.82%  |
| 3     | 4         | 2.42%   |
| 0     | 2         | 1.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 90        | 35.02%  |
| Intel                    | 70        | 27.24%  |
| Qualcomm Atheros         | 44        | 17.12%  |
| Broadcom                 | 25        | 9.73%   |
| Broadcom Limited         | 7         | 2.72%   |
| TP-Link                  | 6         | 2.33%   |
| MediaTek                 | 3         | 1.17%   |
| Nvidia                   | 2         | 0.78%   |
| ASIX Electronics         | 2         | 0.78%   |
| Xiaomi                   | 1         | 0.39%   |
| Marvell Technology Group | 1         | 0.39%   |
| JMicron Technology       | 1         | 0.39%   |
| Huawei Technologies      | 1         | 0.39%   |
| Hewlett-Packard          | 1         | 0.39%   |
| DisplayLink              | 1         | 0.39%   |
| Dell                     | 1         | 0.39%   |
| D-Link                   | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 14.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 8.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 3.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 3.13%   |
| Intel Wireless 7265                                               | 9         | 2.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.5%    |
| Intel Wireless 7260                                               | 7         | 2.19%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 6         | 1.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.56%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 5         | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.25%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 1.25%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 3         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.94%   |
| Intel Wireless 8260                                               | 3         | 0.94%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.94%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                         | 2         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.63%   |
| Realtek 802.11ac NIC                                              | 2         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.63%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.63%   |
| Intel Wireless 3160                                               | 2         | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.63%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 61        | 37.42%  |
| Qualcomm Atheros      | 35        | 21.47%  |
| Realtek Semiconductor | 30        | 18.4%   |
| Broadcom              | 20        | 12.27%  |
| Broadcom Limited      | 7         | 4.29%   |
| TP-Link               | 6         | 3.68%   |
| MediaTek              | 2         | 1.23%   |
| Dell                  | 1         | 0.61%   |
| D-Link                | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 6.63%   |
| Intel Wireless 7265                                            | 9         | 5.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 4.82%   |
| Intel Wireless 7260                                            | 7         | 4.22%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 6         | 3.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 3.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 3.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 3.01%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 3.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 3.01%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 3.01%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 3.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 2.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 2.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.41%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 2.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.81%   |
| Intel Wireless 8260                                            | 3         | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.81%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                      | 2         | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.2%    |
| Realtek 802.11ac NIC                                           | 2         | 1.2%    |
| Intel Wireless 8265 / 8275                                     | 2         | 1.2%    |
| Intel Wireless 3160                                            | 2         | 1.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.2%    |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.2%    |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.2%    |
| Broadcom Limited BCM4311 802.11a/b/g                           | 2         | 1.2%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1         | 0.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.6%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 80        | 55.17%  |
| Intel                    | 31        | 21.38%  |
| Qualcomm Atheros         | 12        | 8.28%   |
| Broadcom                 | 12        | 8.28%   |
| Nvidia                   | 2         | 1.38%   |
| ASIX Electronics         | 2         | 1.38%   |
| Xiaomi                   | 1         | 0.69%   |
| MediaTek                 | 1         | 0.69%   |
| Marvell Technology Group | 1         | 0.69%   |
| JMicron Technology       | 1         | 0.69%   |
| Huawei Technologies      | 1         | 0.69%   |
| DisplayLink              | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 30.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 16.99%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 6.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 3.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 2.61%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.96%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 1.31%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.31%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.31%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 1.31%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.65%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.65%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.65%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.65%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.65%   |
| MediaTek M40Air_EEA                                               | 1         | 0.65%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.65%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.65%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.65%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.65%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.65%   |
| Intel 82599 10 Gigabit Network Connection                         | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 155       | 53.26%  |
| Ethernet | 135       | 46.39%  |
| Modem    | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 121       | 73.33%  |
| Ethernet | 44        | 26.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 126       | 79.25%  |
| 1     | 26        | 16.35%  |
| 3     | 5         | 3.14%   |
| 0     | 2         | 1.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 154       | 96.25%  |
| Yes  | 6         | 3.75%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 39.5%   |
| Realtek Semiconductor           | 19        | 15.97%  |
| Qualcomm Atheros Communications | 17        | 14.29%  |
| Broadcom                        | 9         | 7.56%   |
| Apple                           | 7         | 5.88%   |
| Lite-On Technology              | 4         | 3.36%   |
| IMC Networks                    | 4         | 3.36%   |
| Toshiba                         | 3         | 2.52%   |
| Foxconn / Hon Hai               | 3         | 2.52%   |
| Hewlett-Packard                 | 2         | 1.68%   |
| Cambridge Silicon Radio         | 2         | 1.68%   |
| Realtek                         | 1         | 0.84%   |
| Dell                            | 1         | 0.84%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 18.49%  |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 9.24%   |
| Realtek Bluetooth Radio                             | 10        | 8.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 7.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 6.72%   |
| Intel Bluetooth Device                              | 5         | 4.2%    |
| Intel AX200 Bluetooth                               | 5         | 4.2%    |
| Apple Bluetooth Host Controller                     | 5         | 4.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 2.52%   |
| Broadcom HP Portable SoftSailing                    | 3         | 2.52%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 2.52%   |
| Toshiba Bluetooth Device                            | 2         | 1.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.68%   |
| Intel AX210 Bluetooth                               | 2         | 1.68%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.68%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.68%   |
| Toshiba BCM43142A0                                  | 1         | 0.84%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.84%   |
| Realtek Bluetooth Radio                             | 1         | 0.84%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.84%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.84%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.84%   |
| Lite-On Wireless_Device                             | 1         | 0.84%   |
| Lite-On Bluetooth Device                            | 1         | 0.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.84%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.84%   |
| IMC Networks Wireless_Device                        | 1         | 0.84%   |
| IMC Networks Bluetooth                              | 1         | 0.84%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.84%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.84%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.84%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.84%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.84%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.84%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.84%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.84%   |
| Apple Bluetooth HCI                                 | 1         | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 131       | 65.17%  |
| AMD                    | 29        | 14.43%  |
| Nvidia                 | 21        | 10.45%  |
| Generalplus Technology | 3         | 1.49%   |
| Plantronics            | 2         | 1%      |
| Logitech               | 2         | 1%      |
| JMTek                  | 2         | 1%      |
| GN Netcom              | 2         | 1%      |
| C-Media Electronics    | 2         | 1%      |
| Unknown                | 1         | 0.5%    |
| Sony                   | 1         | 0.5%    |
| Realtek Semiconductor  | 1         | 0.5%    |
| Lenovo                 | 1         | 0.5%    |
| DCMT Technology        | 1         | 0.5%    |
| CMX Systems            | 1         | 0.5%    |
| Afatech                | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 7.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 7.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 5.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 3.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 3.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 3.33%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 3.33%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 3.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.08%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.08%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.67%   |
| Nvidia Audio device                                                                               | 4         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.25%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.25%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 1.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.25%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.83%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.83%   |
| Unknown USB PnP Audio Device                                                                      | 1         | 0.42%   |
| Sony DualSense wireless controller (PS5)                                                          | 1         | 0.42%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.42%   |
| Plantronics Blackwire 5220 Series                                                                 | 1         | 0.42%   |
| Plantronics Blackwire 3225 Series                                                                 | 1         | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 30.09%  |
| SK hynix            | 20        | 17.7%   |
| Micron Technology   | 12        | 10.62%  |
| Kingston            | 9         | 7.96%   |
| Crucial             | 9         | 7.96%   |
| Nanya Technology    | 5         | 4.42%   |
| Unknown             | 4         | 3.54%   |
| Team                | 4         | 3.54%   |
| Corsair             | 4         | 3.54%   |
| A-DATA Technology   | 4         | 3.54%   |
| Ramaxel Technology  | 3         | 2.65%   |
| Transcend           | 1         | 0.88%   |
| Super Talent        | 1         | 0.88%   |
| Patriot             | 1         | 0.88%   |
| G.Skill             | 1         | 0.88%   |
| fef5                | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 5         | 3.85%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s      | 4         | 3.08%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s                | 4         | 3.08%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s                | 4         | 3.08%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s   | 3         | 2.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 3         | 2.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 1.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 2         | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 1.54%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 2         | 1.54%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s   | 2         | 1.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 1.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 1.54%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s   | 2         | 1.54%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s   | 2         | 1.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 2         | 1.54%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s       | 2         | 1.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s      | 2         | 1.54%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                | 1         | 0.77%   |
| Unknown RAM Module 8GB SODIMM DDR3                         | 1         | 0.77%   |
| Unknown RAM Module 4GB SODIMM DDR3                         | 1         | 0.77%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s              | 1         | 0.77%   |
| Unknown RAM Module 1GB SODIMM SDRAM                        | 1         | 0.77%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s        | 1         | 0.77%   |
| Super Talent RAM SUPERTALENT02 8GB SODIMM DDR3 1600MT/s    | 1         | 0.77%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s               | 1         | 0.77%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.77%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 0.77%   |
| SK hynix RAM HMP125S6EFR8C-S6 2GB SODIMM DDR2 800MT/s      | 1         | 0.77%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s     | 1         | 0.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 0.77%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 0.77%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 0.77%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s  | 1         | 0.77%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s | 1         | 0.77%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s    | 1         | 0.77%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.77%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.77%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 0.77%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s     | 1         | 0.77%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 39        | 41.94%  |
| DDR3    | 38        | 40.86%  |
| SDRAM   | 4         | 4.3%    |
| DDR2    | 4         | 4.3%    |
| DDR5    | 3         | 3.23%   |
| LPDDR4  | 2         | 2.15%   |
| LPDDR5  | 1         | 1.08%   |
| LPDDR3  | 1         | 1.08%   |
| Unknown | 1         | 1.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 94.51%  |
| Row Of Chips | 3         | 3.3%    |
| Chip         | 1         | 1.1%    |
| Unknown      | 1         | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 42        | 38.53%  |
| 8192  | 37        | 33.94%  |
| 16384 | 12        | 11.01%  |
| 2048  | 9         | 8.26%   |
| 32768 | 7         | 6.42%   |
| 1024  | 2         | 1.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 28        | 25.93%  |
| 2667    | 25        | 23.15%  |
| 3200    | 10        | 9.26%   |
| 1334    | 7         | 6.48%   |
| 1333    | 7         | 6.48%   |
| 3266    | 5         | 4.63%   |
| 2400    | 5         | 4.63%   |
| 2133    | 3         | 2.78%   |
| 667     | 3         | 2.78%   |
| Unknown | 3         | 2.78%   |
| 4800    | 2         | 1.85%   |
| 4199    | 2         | 1.85%   |
| 1067    | 2         | 1.85%   |
| 8400    | 1         | 0.93%   |
| 6400    | 1         | 0.93%   |
| 5600    | 1         | 0.93%   |
| 2933    | 1         | 0.93%   |
| 2048    | 1         | 0.93%   |
| 800     | 1         | 0.93%   |

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
| Chicony Electronics                    | 31        | 21.99%  |
| Microdia                               | 17        | 12.06%  |
| IMC Networks                           | 15        | 10.64%  |
| Sunplus Innovation Technology          | 13        | 9.22%   |
| Realtek Semiconductor                  | 12        | 8.51%   |
| Apple                                  | 7         | 4.96%   |
| Quanta                                 | 6         | 4.26%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.26%   |
| Lite-On Technology                     | 5         | 3.55%   |
| Primax Electronics                     | 4         | 2.84%   |
| Suyin                                  | 3         | 2.13%   |
| Bison Electronics                      | 3         | 2.13%   |
| Luxvisions Innotech Limited            | 2         | 1.42%   |
| Logitech                               | 2         | 1.42%   |
| Alcor Micro                            | 2         | 1.42%   |
| Acer                                   | 2         | 1.42%   |
| Z-Star Microelectronics                | 1         | 0.71%   |
| Syntek                                 | 1         | 0.71%   |
| Sonix Technology                       | 1         | 0.71%   |
| Silicon Motion                         | 1         | 0.71%   |
| Samsung Electronics                    | 1         | 0.71%   |
| Microsoft                              | 1         | 0.71%   |
| LG Electronics                         | 1         | 0.71%   |
| Importek                               | 1         | 0.71%   |
| GEMBIRD                                | 1         | 0.71%   |
| Creative Technology                    | 1         | 0.71%   |
| Alpha Imaging Technology               | 1         | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 12        | 8.39%   |
| Chicony Integrated Camera                        | 9         | 6.29%   |
| Sunplus HD WebCam                                | 5         | 3.5%    |
| IMC Networks Integrated Camera                   | 5         | 3.5%    |
| Apple FaceTime HD Camera                         | 5         | 3.5%    |
| Sunplus Integrated_Webcam_HD                     | 3         | 2.1%    |
| Realtek Integrated_Webcam_HD                     | 3         | 2.1%    |
| Primax HP HD Webcam [Fixed]                      | 3         | 2.1%    |
| IMC Networks USB2.0 HD UVC WebCam                | 3         | 2.1%    |
| Chicony TOSHIBA Web Camera - HD                  | 3         | 2.1%    |
| Sunplus HP HD Webcam [Fixed]                     | 2         | 1.4%    |
| Realtek Integrated Webcam HD                     | 2         | 1.4%    |
| Realtek Integrated Webcam                        | 2         | 1.4%    |
| Quanta HP TrueVision HD Camera                   | 2         | 1.4%    |
| Quanta HD WebCam                                 | 2         | 1.4%    |
| Microdia Integrated Webcam                       | 2         | 1.4%    |
| Lite-On TOSHIBA Web Camera - HD                  | 2         | 1.4%    |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 1.4%    |
| Chicony USB 2.0 Camera                           | 2         | 1.4%    |
| Chicony Integrated HP HD Webcam                  | 2         | 1.4%    |
| Chicony HP Truevision HD                         | 2         | 1.4%    |
| Chicony HP HD Webcam                             | 2         | 1.4%    |
| Chicony HP HD Camera                             | 2         | 1.4%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.4%    |
| Z-Star Vega USB2.0 Camera                        | 1         | 0.7%    |
| Syntek EasyCamera                                | 1         | 0.7%    |
| Suyin TOSHIBA Web Camera - HD                    | 1         | 0.7%    |
| Suyin HP TrueVision HD                           | 1         | 0.7%    |
| Suyin 1.3M HD WebCam                             | 1         | 0.7%    |
| Sunplus Laptop_Integrated_Webcam_HD              | 1         | 0.7%    |
| Sunplus Integrated Camera                        | 1         | 0.7%    |
| Sunplus Dell Integrated Webcam                   | 1         | 0.7%    |
| Sonix USB2.0 FHD UVC WebCam                      | 1         | 0.7%    |
| Silicon Motion ATIV Real HD Camera               | 1         | 0.7%    |
| Samsung Galaxy series, misc. (MTP mode)          | 1         | 0.7%    |
| Realtek USB2.0 VGA UVC WebCam                    | 1         | 0.7%    |
| Realtek USB Camera                               | 1         | 0.7%    |
| Realtek Rear Camera                              | 1         | 0.7%    |
| Realtek HP Wide Vision FHD Camera                | 1         | 0.7%    |
| Realtek HP Truevision HD                         | 1         | 0.7%    |

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
| 0     | 101       | 61.59%  |
| 1     | 54        | 32.93%  |
| 2     | 6         | 3.66%   |
| 3     | 3         | 1.83%   |

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

