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

Total: 249

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 13        | 7.69%   |
| Ubuntu 18.04                 | 12        | 7.1%    |
| Ubuntu 22.04                 | 10        | 5.92%   |
| OpenMandriva 4.2             | 7         | 4.14%   |
| Zorin 16                     | 6         | 3.55%   |
| Ubuntu 19.04                 | 4         | 2.37%   |
| OpenMandriva 4.3             | 4         | 2.37%   |
| Debian 12                    | 4         | 2.37%   |
| Debian 11                    | 4         | 2.37%   |
| Lubuntu 22.10                | 3         | 1.78%   |
| Lubuntu 22.04                | 3         | 1.78%   |
| Lubuntu 21.10                | 3         | 1.78%   |
| Lubuntu 21.04                | 3         | 1.78%   |
| Xubuntu 20.04                | 2         | 1.18%   |
| Ubuntu Studio 20.04          | 2         | 1.18%   |
| Ubuntu 23.04                 | 2         | 1.18%   |
| Ubuntu 21.04                 | 2         | 1.18%   |
| Pop!_OS 22.04                | 2         | 1.18%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.18%   |
| OpenMandriva 23.03           | 2         | 1.18%   |
| OpenMandriva 23.01           | 2         | 1.18%   |
| Manjaro 20.2.1               | 2         | 1.18%   |
| Lubuntu 23.04                | 2         | 1.18%   |
| Linux Mint 20.3              | 2         | 1.18%   |
| Linux Mint 20.1              | 2         | 1.18%   |
| Linux Mint 20                | 2         | 1.18%   |
| Kubuntu 22.04                | 2         | 1.18%   |
| KDE neon 20.04               | 2         | 1.18%   |
| Fedora 38                    | 2         | 1.18%   |
| Fedora 36                    | 2         | 1.18%   |
| Debian 10                    | 2         | 1.18%   |
| Zorin 15                     | 1         | 0.59%   |
| Xubuntu 18.04                | 1         | 0.59%   |
| UbuntuDDE 20.04              | 1         | 0.59%   |
| Ubuntu Unity 18.04           | 1         | 0.59%   |
| Ubuntu Unity 16.04           | 1         | 0.59%   |
| Ubuntu MATE 18.04            | 1         | 0.59%   |
| Ubuntu Budgie 23.04          | 1         | 0.59%   |
| Ubuntu 22.10                 | 1         | 0.59%   |
| Ubuntu 21.10                 | 1         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 44        | 28.95%  |
| OpenMandriva  | 14        | 9.21%   |
| Debian        | 11        | 7.24%   |
| Fedora        | 9         | 5.92%   |
| Linux Mint    | 8         | 5.26%   |
| Zorin         | 7         | 4.61%   |
| Manjaro       | 6         | 3.95%   |
| Lubuntu       | 6         | 3.95%   |
| Pop!_OS       | 4         | 2.63%   |
| Kubuntu       | 4         | 2.63%   |
| Xubuntu       | 3         | 1.97%   |
| ROSA          | 3         | 1.97%   |
| KDE neon      | 3         | 1.97%   |
| Ubuntu Unity  | 2         | 1.32%   |
| Ubuntu Studio | 2         | 1.32%   |
| Parrot        | 2         | 1.32%   |
| openSUSE      | 2         | 1.32%   |
| Kali          | 2         | 1.32%   |
| Endless       | 2         | 1.32%   |
| UbuntuDDE     | 1         | 0.66%   |
| Ubuntu MATE   | 1         | 0.66%   |
| Ubuntu Budgie | 1         | 0.66%   |
| Reborn OS     | 1         | 0.66%   |
| PureOS        | 1         | 0.66%   |
| Peppermint    | 1         | 0.66%   |
| Nobara        | 1         | 0.66%   |
| Mageia        | 1         | 0.66%   |
| LMDE          | 1         | 0.66%   |
| LinuxFX       | 1         | 0.66%   |
| Elementary    | 1         | 0.66%   |
| Crystal Linux | 1         | 0.66%   |
| Clear Linux   | 1         | 0.66%   |
| ChimeraOS     | 1         | 0.66%   |
| BigLinux      | 1         | 0.66%   |
| ArcoLinux     | 1         | 0.66%   |
| Arch          | 1         | 0.66%   |
| ALT Linux     | 1         | 0.66%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 7         | 3.74%   |
| 5.16.7-desktop-1omv4003  | 4         | 2.14%   |
| 5.0.0-23-generic         | 4         | 2.14%   |
| 5.4.0-77-generic         | 3         | 1.6%    |
| 5.4.0-42-generic         | 3         | 1.6%    |
| 5.19.0-26-generic        | 3         | 1.6%    |
| 5.13.0-16-generic        | 3         | 1.6%    |
| 5.11.0-27-generic        | 3         | 1.6%    |
| 5.0.0-25-generic         | 3         | 1.6%    |
| 6.3.8-200.fc38.x86_64    | 2         | 1.07%   |
| 6.2.6-desktop-1omv2390   | 2         | 1.07%   |
| 6.2.0-20-generic         | 2         | 1.07%   |
| 6.2.0-18-generic         | 2         | 1.07%   |
| 6.1.0-10-amd64           | 2         | 1.07%   |
| 6.0.6-76060006-generic   | 2         | 1.07%   |
| 5.9.16-1-MANJARO         | 2         | 1.07%   |
| 5.8.0-50-generic         | 2         | 1.07%   |
| 5.4.0-21-generic         | 2         | 1.07%   |
| 5.3.0-40-generic         | 2         | 1.07%   |
| 5.3.0-28-generic         | 2         | 1.07%   |
| 5.19.0-32-generic        | 2         | 1.07%   |
| 5.15.0-58-generic        | 2         | 1.07%   |
| 5.15.0-52-generic        | 2         | 1.07%   |
| 5.15.0-41-generic        | 2         | 1.07%   |
| 5.13.0-35-generic        | 2         | 1.07%   |
| 5.13.0-20-generic        | 2         | 1.07%   |
| 5.11.0-16-generic        | 2         | 1.07%   |
| 4.15.0-112-generic       | 2         | 1.07%   |
| 6.4.6-desktop-2.mga9     | 1         | 0.53%   |
| 6.4.11-desktop-1omv2390  | 1         | 0.53%   |
| 6.3.6-custom             | 1         | 0.53%   |
| 6.3.6-arch1-1            | 1         | 0.53%   |
| 6.3.4-101.fc37.x86_64    | 1         | 0.53%   |
| 6.2.15-200.fc37.x86_64   | 1         | 0.53%   |
| 6.2.0-custom             | 1         | 0.53%   |
| 6.2.0-27-generic         | 1         | 0.53%   |
| 6.2.0-26-generic         | 1         | 0.53%   |
| 6.2.0-24-generic         | 1         | 0.53%   |
| 6.2.0-19-generic         | 1         | 0.53%   |
| 6.1.6-custom             | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 22        | 12.72%  |
| 5.15.0  | 16        | 9.25%   |
| 5.11.0  | 11        | 6.36%   |
| 5.19.0  | 9         | 5.2%    |
| 5.13.0  | 8         | 4.62%   |
| 5.0.0   | 8         | 4.62%   |
| 5.3.0   | 7         | 4.05%   |
| 5.10.14 | 7         | 4.05%   |
| 5.10.0  | 7         | 4.05%   |
| 6.2.0   | 6         | 3.47%   |
| 6.1.0   | 5         | 2.89%   |
| 5.8.0   | 5         | 2.89%   |
| 4.15.0  | 5         | 2.89%   |
| 5.16.7  | 4         | 2.31%   |
| 6.3.8   | 2         | 1.16%   |
| 6.3.6   | 2         | 1.16%   |
| 6.2.6   | 2         | 1.16%   |
| 6.1.1   | 2         | 1.16%   |
| 6.0.6   | 2         | 1.16%   |
| 5.9.16  | 2         | 1.16%   |
| 5.18.13 | 2         | 1.16%   |
| 4.19.0  | 2         | 1.16%   |
| 6.4.6   | 1         | 0.58%   |
| 6.4.11  | 1         | 0.58%   |
| 6.3.4   | 1         | 0.58%   |
| 6.2.15  | 1         | 0.58%   |
| 6.1.6   | 1         | 0.58%   |
| 6.1.4   | 1         | 0.58%   |
| 6.1.20  | 1         | 0.58%   |
| 6.0.8   | 1         | 0.58%   |
| 6.0.7   | 1         | 0.58%   |
| 5.9.11  | 1         | 0.58%   |
| 5.8.6   | 1         | 0.58%   |
| 5.7.0   | 1         | 0.58%   |
| 5.2.11  | 1         | 0.58%   |
| 5.19.4  | 1         | 0.58%   |
| 5.19.16 | 1         | 0.58%   |
| 5.19.11 | 1         | 0.58%   |
| 5.18.0  | 1         | 0.58%   |
| 5.17.9  | 1         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 22        | 12.79%  |
| 5.10    | 18        | 10.47%  |
| 5.15    | 17        | 9.88%   |
| 5.11    | 14        | 8.14%   |
| 5.19    | 12        | 6.98%   |
| 6.1     | 10        | 5.81%   |
| 6.2     | 9         | 5.23%   |
| 5.0     | 9         | 5.23%   |
| 5.13    | 8         | 4.65%   |
| 5.3     | 7         | 4.07%   |
| 5.8     | 6         | 3.49%   |
| 6.3     | 5         | 2.91%   |
| 4.15    | 5         | 2.91%   |
| 6.0     | 4         | 2.33%   |
| 5.16    | 4         | 2.33%   |
| 5.9     | 3         | 1.74%   |
| 5.18    | 3         | 1.74%   |
| 5.12    | 3         | 1.74%   |
| 4.19    | 3         | 1.74%   |
| 6.4     | 2         | 1.16%   |
| 4.18    | 2         | 1.16%   |
| 5.7     | 1         | 0.58%   |
| 5.2     | 1         | 0.58%   |
| 5.17    | 1         | 0.58%   |
| 5.14    | 1         | 0.58%   |
| 4.9     | 1         | 0.58%   |
| 4.1     | 1         | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 143       | 99.31%  |
| i686   | 1         | 0.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 67        | 44.97%  |
| KDE5       | 27        | 18.12%  |
| Unknown    | 14        | 9.4%    |
| XFCE       | 12        | 8.05%   |
| LXQt       | 7         | 4.7%    |
| MATE       | 5         | 3.36%   |
| X-Cinnamon | 4         | 2.68%   |
| KDE        | 3         | 2.01%   |
| Unity      | 2         | 1.34%   |
| i3         | 2         | 1.34%   |
| Pantheon   | 1         | 0.67%   |
| onyx:GNOME | 1         | 0.67%   |
| LXDE       | 1         | 0.67%   |
| Deepin     | 1         | 0.67%   |
| Cinnamon   | 1         | 0.67%   |
| Budgie     | 1         | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 107       | 73.79%  |
| Wayland | 29        | 20%     |
| Unknown | 8         | 5.52%   |
| Tty     | 1         | 0.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 60        | 40.82%  |
| SDDM    | 34        | 23.13%  |
| GDM3    | 19        | 12.93%  |
| LightDM | 13        | 8.84%   |
| GDM     | 13        | 8.84%   |
| TDM     | 8         | 5.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 64        | 43.54%  |
| es_CR   | 53        | 36.05%  |
| Unknown | 14        | 9.52%   |
| es_ES   | 9         | 6.12%   |
| es_MX   | 2         | 1.36%   |
| C       | 2         | 1.36%   |
| fr_FR   | 1         | 0.68%   |
| es_EC   | 1         | 0.68%   |
| en_AG   | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 77        | 52.03%  |
| BIOS | 71        | 47.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 110       | 74.83%  |
| Btrfs   | 16        | 10.88%  |
| Overlay | 14        | 9.52%   |
| Unknown | 4         | 2.72%   |
| Tmpfs   | 2         | 1.36%   |
| Xfs     | 1         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 69        | 47.59%  |
| GPT     | 58        | 40%     |
| MBR     | 18        | 12.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 132       | 89.8%   |
| Yes       | 15        | 10.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 64.14%  |
| Yes       | 52        | 35.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 33        | 22.92%  |
| Dell                | 31        | 21.53%  |
| Lenovo              | 23        | 15.97%  |
| Toshiba             | 13        | 9.03%   |
| ASUSTek Computer    | 12        | 8.33%   |
| Acer                | 11        | 7.64%   |
| Apple               | 6         | 4.17%   |
| MSI                 | 4         | 2.78%   |
| Google              | 2         | 1.39%   |
| System76            | 1         | 0.69%   |
| Sony                | 1         | 0.69%   |
| Samsung Electronics | 1         | 0.69%   |
| Purism              | 1         | 0.69%   |
| Olivetti            | 1         | 0.69%   |
| HUAWEI              | 1         | 0.69%   |
| Deffad              | 1         | 0.69%   |
| AZW                 | 1         | 0.69%   |
| Unknown             | 1         | 0.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Apple MacBookPro8,1                          | 4         | 2.78%   |
| Unknown                                      | 4         | 2.78%   |
| HP Notebook                                  | 3         | 2.08%   |
| Dell Inspiron 5584                           | 3         | 2.08%   |
| HP ProBook 6460b                             | 2         | 1.39%   |
| HP Pavilion Notebook                         | 2         | 1.39%   |
| HP Laptop 15-da0xxx                          | 2         | 1.39%   |
| Toshiba Satellite X205                       | 1         | 0.69%   |
| Toshiba Satellite S55-A                      | 1         | 0.69%   |
| Toshiba Satellite L755                       | 1         | 0.69%   |
| Toshiba Satellite L655                       | 1         | 0.69%   |
| Toshiba Satellite L45-B                      | 1         | 0.69%   |
| Toshiba Satellite C855D                      | 1         | 0.69%   |
| Toshiba Satellite C845                       | 1         | 0.69%   |
| Toshiba Satellite C645D                      | 1         | 0.69%   |
| Toshiba Satellite C55-C                      | 1         | 0.69%   |
| Toshiba Satellite C55-B                      | 1         | 0.69%   |
| Toshiba Satellite C45-A                      | 1         | 0.69%   |
| Toshiba Satellite A305D                      | 1         | 0.69%   |
| Toshiba QOSMIO X775                          | 1         | 0.69%   |
| System76 Lemur                               | 1         | 0.69%   |
| Sony SVD13215PLB                             | 1         | 0.69%   |
| Samsung 930X2K/931X2K                        | 1         | 0.69%   |
| Purism Librem 15 v3                          | 1         | 0.69%   |
| Olivetti CL133A                              | 1         | 0.69%   |
| MSI Katana 15 B13VGK                         | 1         | 0.69%   |
| MSI GF75 Thin 9SD                            | 1         | 0.69%   |
| MSI GF65 Thin 10SDR                          | 1         | 0.69%   |
| MSI GE60 2OC\2OD\2OE                         | 1         | 0.69%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y50010US | 1         | 0.69%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1EY00     | 1         | 0.69%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US     | 1         | 0.69%   |
| Lenovo ThinkPad T60 1952F75                  | 1         | 0.69%   |
| Lenovo ThinkPad T470 W10DG 20JM000CUS        | 1         | 0.69%   |
| Lenovo ThinkPad T440s 20ARS29U00             | 1         | 0.69%   |
| Lenovo ThinkPad P53 20QNS00P00               | 1         | 0.69%   |
| Lenovo ThinkPad P50 20EN001PUS               | 1         | 0.69%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002RUS        | 1         | 0.69%   |
| Lenovo ThinkPad P16 Gen 1 21D7S0L500         | 1         | 0.69%   |
| Lenovo ThinkPad L420 7829AA4                 | 1         | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 17        | 11.81%  |
| Toshiba Satellite | 12        | 8.33%   |
| Dell Latitude     | 12        | 8.33%   |
| Dell Inspiron     | 12        | 8.33%   |
| Acer Aspire       | 9         | 6.25%   |
| HP Pavilion       | 8         | 5.56%   |
| HP Laptop         | 6         | 4.17%   |
| HP ProBook        | 5         | 3.47%   |
| HP EliteBook      | 5         | 3.47%   |
| Lenovo IdeaPad    | 4         | 2.78%   |
| ASUS VivoBook     | 4         | 2.78%   |
| Apple MacBookPro8 | 4         | 2.78%   |
| Unknown           | 4         | 2.78%   |
| HP Notebook       | 3         | 2.08%   |
| Dell XPS          | 3         | 2.08%   |
| Dell G3           | 2         | 1.39%   |
| Toshiba QOSMIO    | 1         | 0.69%   |
| System76 Lemur    | 1         | 0.69%   |
| Sony SVD13215PLB  | 1         | 0.69%   |
| Samsung 930X2K    | 1         | 0.69%   |
| Purism Librem     | 1         | 0.69%   |
| Olivetti CL133A   | 1         | 0.69%   |
| MSI Katana        | 1         | 0.69%   |
| MSI GF75          | 1         | 0.69%   |
| MSI GF65          | 1         | 0.69%   |
| MSI GE60          | 1         | 0.69%   |
| Lenovo Legion     | 1         | 0.69%   |
| Lenovo B590       | 1         | 0.69%   |
| HUAWEI NBLK-WAX9X | 1         | 0.69%   |
| HP OMEN           | 1         | 0.69%   |
| HP ENVY           | 1         | 0.69%   |
| HP 245            | 1         | 0.69%   |
| HP 240            | 1         | 0.69%   |
| Google Snappy     | 1         | 0.69%   |
| Google Celes      | 1         | 0.69%   |
| Dell Venue        | 1         | 0.69%   |
| Dell Precision    | 1         | 0.69%   |
| AZW GT-R          | 1         | 0.69%   |
| ASUS X555LAB      | 1         | 0.69%   |
| ASUS U46E         | 1         | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 20        | 13.89%  |
| 2018 | 15        | 10.42%  |
| 2011 | 15        | 10.42%  |
| 2020 | 13        | 9.03%   |
| 2012 | 12        | 8.33%   |
| 2017 | 9         | 6.25%   |
| 2015 | 9         | 6.25%   |
| 2014 | 9         | 6.25%   |
| 2016 | 8         | 5.56%   |
| 2013 | 8         | 5.56%   |
| 2021 | 7         | 4.86%   |
| 2008 | 4         | 2.78%   |
| 2023 | 3         | 2.08%   |
| 2010 | 3         | 2.08%   |
| 2007 | 3         | 2.08%   |
| 2006 | 3         | 2.08%   |
| 2009 | 2         | 1.39%   |
| 2022 | 1         | 0.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 144       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 132       | 91.67%  |
| Enabled  | 12        | 8.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 141       | 97.92%  |
| Yes  | 3         | 2.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 41        | 27.89%  |
| 3.01-4.0    | 30        | 20.41%  |
| 8.01-16.0   | 30        | 20.41%  |
| 16.01-24.0  | 22        | 14.97%  |
| 32.01-64.0  | 10        | 6.8%    |
| 24.01-32.0  | 4         | 2.72%   |
| 1.01-2.0    | 4         | 2.72%   |
| 2.01-3.0    | 3         | 2.04%   |
| 64.01-256.0 | 3         | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 64        | 40.76%  |
| 2.01-3.0   | 40        | 25.48%  |
| 4.01-8.0   | 21        | 13.38%  |
| 3.01-4.0   | 19        | 12.1%   |
| 8.01-16.0  | 6         | 3.82%   |
| 0.51-1.0   | 5         | 3.18%   |
| 16.01-24.0 | 2         | 1.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 108       | 75%     |
| 2      | 33        | 22.92%  |
| 3      | 3         | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 57.64%  |
| Yes       | 61        | 42.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 85.42%  |
| No        | 21        | 14.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 97.92%  |
| No        | 3         | 2.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 74.48%  |
| No        | 37        | 25.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Costa Rica | 144       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San José     | 64        | 39.26%  |
| Heredia       | 27        | 16.56%  |
| Alajuela      | 13        | 7.98%   |
| Quesada       | 5         | 3.07%   |
| Grecia        | 5         | 3.07%   |
| Cartago       | 5         | 3.07%   |
| Rio Segundo   | 4         | 2.45%   |
| Puntarenas    | 4         | 2.45%   |
| Escazu        | 4         | 2.45%   |
| San Ramon     | 3         | 1.84%   |
| Siquirres     | 2         | 1.23%   |
| Santa Cruz    | 2         | 1.23%   |
| Naranjo       | 2         | 1.23%   |
| Esparza       | 2         | 1.23%   |
| Zarcero       | 1         | 0.61%   |
| Tres Rios     | 1         | 0.61%   |
| Santo Domingo | 1         | 0.61%   |
| Santiago      | 1         | 0.61%   |
| Santa Fe      | 1         | 0.61%   |
| San Pedro     | 1         | 0.61%   |
| San Pablo     | 1         | 0.61%   |
| San Juan      | 1         | 0.61%   |
| San Francisco | 1         | 0.61%   |
| San Felipe    | 1         | 0.61%   |
| Quepos        | 1         | 0.61%   |
| Pavas         | 1         | 0.61%   |
| Palmares      | 1         | 0.61%   |
| Nosara        | 1         | 0.61%   |
| Liberia       | 1         | 0.61%   |
| Guapiles      | 1         | 0.61%   |
| Guacima       | 1         | 0.61%   |
| Curridabat    | 1         | 0.61%   |
| Colon         | 1         | 0.61%   |
| Bagaces       | 1         | 0.61%   |
| Alpes         | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 39     | 14.2%   |
| Toshiba             | 20        | 25     | 11.36%  |
| Samsung Electronics | 20        | 29     | 11.36%  |
| Seagate             | 19        | 27     | 10.8%   |
| Intel               | 12        | 27     | 6.82%   |
| Kingston            | 11        | 15     | 6.25%   |
| Unknown             | 9         | 13     | 5.11%   |
| HGST                | 9         | 10     | 5.11%   |
| A-DATA Technology   | 7         | 7      | 3.98%   |
| SK hynix            | 5         | 10     | 2.84%   |
| SanDisk             | 5         | 5      | 2.84%   |
| Patriot             | 5         | 5      | 2.84%   |
| Micron Technology   | 5         | 6      | 2.84%   |
| Crucial             | 5         | 5      | 2.84%   |
| Team                | 2         | 2      | 1.14%   |
| Netac               | 2         | 2      | 1.14%   |
| KIOXIA              | 2         | 2      | 1.14%   |
| Zheino              | 1         | 1      | 0.57%   |
| UMIS                | 1         | 1      | 0.57%   |
| Transcend           | 1         | 1      | 0.57%   |
| Silicon Motion      | 1         | 1      | 0.57%   |
| Mushkin             | 1         | 1      | 0.57%   |
| LITEONIT            | 1         | 1      | 0.57%   |
| JMicron Technology  | 1         | 1      | 0.57%   |
| Hitachi             | 1         | 2      | 0.57%   |
| Gigabyte Technology | 1         | 1      | 0.57%   |
| Fujitsu             | 1         | 1      | 0.57%   |
| Dell                | 1         | 1      | 0.57%   |
| BP4                 | 1         | 1      | 0.57%   |
| Unknown             | 1         | 1      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                            | 5         | 2.69%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 2.69%   |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 2.15%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 2.15%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 1.61%   |
| Toshiba KBG30ZMS256G NVMe 256GB                     | 3         | 1.61%   |
| Intel SSDSC2BF180A4H 180GB                          | 3         | 1.61%   |
| Intel SSDSA2CW300G3 304GB                           | 3         | 1.61%   |
| HGST HTS541010A9E680 1TB                            | 3         | 1.61%   |
| WDC WD20SPZX-08UA7 2TB                              | 2         | 1.08%   |
| Unknown MMC Card  128GB                             | 2         | 1.08%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD                 | 2         | 1.08%   |
| SK hynix NVMe SSD Drive 128GB                       | 2         | 1.08%   |
| Seagate ST9500325AS 500GB                           | 2         | 1.08%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2         | 1.08%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 1.08%   |
| Intel SSDSC2MH250A2 250GB                           | 2         | 1.08%   |
| HGST HTS541075A9E680 752GB                          | 2         | 1.08%   |
| Zheino CHN 25SATAA3 240 240GB                       | 1         | 0.54%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.54%   |
| WDC WDS120G1G0B-00RC30 120GB SSD                    | 1         | 0.54%   |
| WDC WD800BEVT-75ZCT2 80GB                           | 1         | 0.54%   |
| WDC WD7500BPVT-22HXZT3 752GB                        | 1         | 0.54%   |
| WDC WD5000LPVX-80V0TT0 500GB                        | 1         | 0.54%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 0.54%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 0.54%   |
| WDC WD5000BPKT-60PK4T0 500GB                        | 1         | 0.54%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 0.54%   |
| WDC WD1600BEVT-75A23T0 160GB                        | 1         | 0.54%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 0.54%   |
| WDC WD10SPZX-08Z10 1TB                              | 1         | 0.54%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 0.54%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.54%   |
| WDC WD Blue SA510 M.2 2280 500GB SSD                | 1         | 0.54%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 18        | 26     | 29.03%  |
| Toshiba | 17        | 18     | 27.42%  |
| WDC     | 16        | 19     | 25.81%  |
| HGST    | 9         | 10     | 14.52%  |
| Hitachi | 1         | 2      | 1.61%   |
| Fujitsu | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 10     | 15.38%  |
| Intel               | 8         | 19     | 12.31%  |
| WDC                 | 7         | 15     | 10.77%  |
| Samsung Electronics | 7         | 15     | 10.77%  |
| A-DATA Technology   | 6         | 6      | 9.23%   |
| Patriot             | 5         | 5      | 7.69%   |
| Micron Technology   | 4         | 4      | 6.15%   |
| Crucial             | 4         | 4      | 6.15%   |
| SanDisk             | 3         | 3      | 4.62%   |
| Team                | 2         | 2      | 3.08%   |
| Netac               | 2         | 2      | 3.08%   |
| Transcend           | 1         | 1      | 1.54%   |
| Seagate             | 1         | 1      | 1.54%   |
| Mushkin             | 1         | 1      | 1.54%   |
| LITEONIT            | 1         | 1      | 1.54%   |
| JMicron Technology  | 1         | 1      | 1.54%   |
| Gigabyte Technology | 1         | 1      | 1.54%   |
| BP4                 | 1         | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 62        | 92     | 36.26%  |
| HDD     | 62        | 76     | 36.26%  |
| NVMe    | 36        | 60     | 21.05%  |
| MMC     | 9         | 13     | 5.26%   |
| Unknown | 2         | 2      | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 117       | 167    | 70.91%  |
| NVMe | 35        | 59     | 21.21%  |
| MMC  | 9         | 13     | 5.45%   |
| SAS  | 4         | 4      | 2.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 99     | 60.48%  |
| 0.51-1.0   | 40        | 59     | 32.26%  |
| 1.01-2.0   | 9         | 10     | 7.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 44        | 28.95%  |
| 251-500        | 28        | 18.42%  |
| 501-1000       | 27        | 17.76%  |
| 1-20           | 12        | 7.89%   |
| 1001-2000      | 11        | 7.24%   |
| 51-100         | 11        | 7.24%   |
| 21-50          | 9         | 5.92%   |
| 2001-3000      | 4         | 2.63%   |
| More than 3000 | 3         | 1.97%   |
| Unknown        | 3         | 1.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 71        | 44.38%  |
| 21-50     | 29        | 18.13%  |
| 101-250   | 18        | 11.25%  |
| 51-100    | 18        | 11.25%  |
| 251-500   | 13        | 8.13%   |
| 501-1000  | 7         | 4.38%   |
| Unknown   | 3         | 1.88%   |
| 1001-2000 | 1         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 7.69%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 7.69%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 7.69%   |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 7.69%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 7.69%   |
| Seagate ST9320310AS 320GB                           | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 7.69%   |
| Netac SSD 120GB                                     | 1         | 1      | 7.69%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 7.69%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 7.69%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 7.69%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 7.69%   |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 3         | 3      | 23.08%  |
| WDC               | 2         | 2      | 15.38%  |
| Seagate           | 2         | 2      | 15.38%  |
| HGST              | 2         | 2      | 15.38%  |
| Netac             | 1         | 1      | 7.69%   |
| Micron Technology | 1         | 1      | 7.69%   |
| Intel             | 1         | 1      | 7.69%   |
| Hitachi           | 1         | 2      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| Seagate | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| Hitachi | 1         | 2      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 11     | 76.92%  |
| SSD  | 3         | 3      | 23.08%  |

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
| Detected | 80        | 130    | 52.98%  |
| Works    | 58        | 99     | 38.41%  |
| Malfunc  | 13        | 14     | 8.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 109       | 65.66%  |
| AMD                          | 18        | 10.84%  |
| Samsung Electronics          | 13        | 7.83%   |
| SanDisk                      | 5         | 3.01%   |
| SK hynix                     | 4         | 2.41%   |
| Toshiba America Info Systems | 3         | 1.81%   |
| Micron Technology            | 2         | 1.2%    |
| KIOXIA                       | 2         | 1.2%    |
| ASMedia Technology           | 2         | 1.2%    |
| Union Memory (Shenzhen)      | 1         | 0.6%    |
| Solidigm                     | 1         | 0.6%    |
| Silicon Motion               | 1         | 0.6%    |
| Realtek Semiconductor        | 1         | 0.6%    |
| Nvidia                       | 1         | 0.6%    |
| Micron/Crucial Technology    | 1         | 0.6%    |
| Kingston Technology Company  | 1         | 0.6%    |
| ADATA Technology             | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 16        | 8.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 15        | 8.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 14        | 7.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 11        | 6.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 11        | 6.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 4.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 6         | 3.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 3.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 2.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 4         | 2.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 2.2%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 2.2%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 1.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.65%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 1.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 1.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.65%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 1.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 2         | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                  | 2         | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 1.1%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                       | 2         | 1.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                  | 2         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 1.1%    |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                                  | 1         | 0.55%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less)                                                 | 1         | 0.55%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 1         | 0.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 1         | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 1         | 0.55%   |
| Samsung NVMe SSD Controller PM9B1                                                      | 1         | 0.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.55%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                      | 1         | 0.55%   |
| Nvidia MCP67 IDE Controller                                                            | 1         | 0.55%   |
| Nvidia MCP67 AHCI Controller                                                           | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 104       | 61.18%  |
| NVMe | 36        | 21.18%  |
| RAID | 15        | 8.82%   |
| IDE  | 15        | 8.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 122       | 84.72%  |
| AMD    | 22        | 15.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz               | 5         | 3.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 4         | 2.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 4         | 2.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 3         | 2.08%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 3         | 2.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 3         | 2.08%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 3         | 2.08%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 3         | 2.08%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 3         | 2.08%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 1.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 1.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 1.39%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 2         | 1.39%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 1.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 1.39%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 2         | 1.39%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 2         | 1.39%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 2         | 1.39%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 2         | 1.39%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 2         | 1.39%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 1.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.39%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 2         | 1.39%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz            | 1         | 0.69%   |
| Intel Pentium CPU P6100 @ 2.00GHz               | 1         | 0.69%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.69%   |
| Intel Genuine CPU U4100 @ 1.30GHz               | 1         | 0.69%   |
| Intel Genuine CPU T2060 @ 1.60GHz               | 1         | 0.69%   |
| Intel Core M-5Y31 CPU @ 0.90GHz                 | 1         | 0.69%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.69%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 0.69%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 0.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 0.69%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.69%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz              | 1         | 0.69%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 39        | 27.08%  |
| Intel Core i5                  | 31        | 21.53%  |
| Intel Core i3                  | 15        | 10.42%  |
| Intel Celeron                  | 13        | 9.03%   |
| Other                          | 11        | 7.64%   |
| AMD Ryzen 7                    | 5         | 3.47%   |
| Intel Core 2 Duo               | 3         | 2.08%   |
| Intel Core 2                   | 3         | 2.08%   |
| AMD Ryzen 5                    | 3         | 2.08%   |
| AMD A10                        | 3         | 2.08%   |
| Intel Pentium                  | 2         | 1.39%   |
| Intel Genuine                  | 2         | 1.39%   |
| Intel Atom                     | 2         | 1.39%   |
| AMD Ryzen 3                    | 2         | 1.39%   |
| AMD E1                         | 2         | 1.39%   |
| AMD A8                         | 2         | 1.39%   |
| Intel Xeon                     | 1         | 0.69%   |
| Intel Core M                   | 1         | 0.69%   |
| AMD V120                       | 1         | 0.69%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.69%   |
| AMD Turion 64 X2               | 1         | 0.69%   |
| AMD Athlon                     | 1         | 0.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 91        | 63.19%  |
| 4      | 33        | 22.92%  |
| 6      | 10        | 6.94%   |
| 8      | 6         | 4.17%   |
| 24     | 1         | 0.69%   |
| 16     | 1         | 0.69%   |
| 10     | 1         | 0.69%   |
| 1      | 1         | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 144       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 106       | 73.61%  |
| 1      | 38        | 26.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 142       | 97.93%  |
| Unknown        | 2         | 1.38%   |
| 32-bit         | 1         | 0.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 27.52%  |
| 0x206a7    | 14        | 9.4%    |
| 0x40651    | 7         | 4.7%    |
| 0x306d4    | 6         | 4.03%   |
| 0x08108109 | 6         | 4.03%   |
| 0x806ec    | 5         | 3.36%   |
| 0x806e9    | 5         | 3.36%   |
| 0x406e3    | 5         | 3.36%   |
| 0x406c4    | 5         | 3.36%   |
| 0x306a9    | 5         | 3.36%   |
| 0x906ea    | 4         | 2.68%   |
| 0x706a1    | 4         | 2.68%   |
| 0x306c3    | 4         | 2.68%   |
| 0x806eb    | 3         | 2.01%   |
| 0x806ea    | 3         | 2.01%   |
| 0x20655    | 3         | 2.01%   |
| 0x806c1    | 2         | 1.34%   |
| 0x6fd      | 2         | 1.34%   |
| 0x506e3    | 2         | 1.34%   |
| 0x1067a    | 2         | 1.34%   |
| 0xb06a2    | 1         | 0.67%   |
| 0xa0652    | 1         | 0.67%   |
| 0x906ed    | 1         | 0.67%   |
| 0x906e9    | 1         | 0.67%   |
| 0x706a8    | 1         | 0.67%   |
| 0x6f6      | 1         | 0.67%   |
| 0x6ec      | 1         | 0.67%   |
| 0x506c9    | 1         | 0.67%   |
| 0x30678    | 1         | 0.67%   |
| 0x08608102 | 1         | 0.67%   |
| 0x08600106 | 1         | 0.67%   |
| 0x08600104 | 1         | 0.67%   |
| 0x08600103 | 1         | 0.67%   |
| 0x07030105 | 1         | 0.67%   |
| 0x07000110 | 1         | 0.67%   |
| 0x06006118 | 1         | 0.67%   |
| 0x06001119 | 1         | 0.67%   |
| 0x05000119 | 1         | 0.67%   |
| 0x03000027 | 1         | 0.67%   |
| 0x02000057 | 1         | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 28        | 19.44%  |
| SandyBridge      | 21        | 14.58%  |
| Haswell          | 13        | 9.03%   |
| Skylake          | 8         | 5.56%   |
| Zen+             | 7         | 4.86%   |
| Silvermont       | 7         | 4.86%   |
| IvyBridge        | 7         | 4.86%   |
| Broadwell        | 7         | 4.86%   |
| Goldmont plus    | 5         | 3.47%   |
| Core             | 5         | 3.47%   |
| Unknown          | 5         | 3.47%   |
| TigerLake        | 4         | 2.78%   |
| Zen 2            | 3         | 2.08%   |
| Westmere         | 3         | 2.08%   |
| IceLake          | 3         | 2.08%   |
| Excavator        | 3         | 2.08%   |
| Penryn           | 2         | 1.39%   |
| Alderlake Hybrid | 2         | 1.39%   |
| Puma             | 1         | 0.69%   |
| Piledriver       | 1         | 0.69%   |
| P6               | 1         | 0.69%   |
| K8 Hammer        | 1         | 0.69%   |
| K8 & K10 hybrid  | 1         | 0.69%   |
| K10 Llano        | 1         | 0.69%   |
| K10              | 1         | 0.69%   |
| Jaguar           | 1         | 0.69%   |
| Goldmont         | 1         | 0.69%   |
| CometLake        | 1         | 0.69%   |
| Bobcat           | 1         | 0.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 116       | 65.91%  |
| Nvidia | 33        | 18.75%  |
| AMD    | 27        | 15.34%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 9.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 4.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 4.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.24%   |
| Intel HD Graphics 620                                                                    | 6         | 3.24%   |
| Intel HD Graphics 5500                                                                   | 6         | 3.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 3.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.24%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 2.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 2.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 2.16%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 2.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.16%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.62%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.62%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.62%   |
| AMD Renoir                                                                               | 3         | 1.62%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.08%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.08%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.54%   |
| Nvidia TU117M                                                                            | 1         | 0.54%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.54%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.54%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.54%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.54%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.54%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.54%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.54%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.54%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 85        | 59.03%  |
| Intel + Nvidia | 28        | 19.44%  |
| 1 x AMD        | 19        | 13.19%  |
| 2 x AMD        | 4         | 2.78%   |
| 1 x Nvidia     | 3         | 2.08%   |
| Intel + AMD    | 2         | 1.39%   |
| AMD + Nvidia   | 2         | 1.39%   |
| Other          | 1         | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 125       | 86.21%  |
| Proprietary | 18        | 12.41%  |
| Unknown     | 2         | 1.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 74.48%  |
| 1.01-2.0   | 12        | 8.28%   |
| 0.01-0.5   | 10        | 6.9%    |
| 3.01-4.0   | 7         | 4.83%   |
| 0.51-1.0   | 6         | 4.14%   |
| 5.01-6.0   | 2         | 1.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 35        | 19.89%  |
| LG Display              | 28        | 15.91%  |
| BOE                     | 20        | 11.36%  |
| Samsung Electronics     | 19        | 10.8%   |
| Chimei Innolux          | 19        | 10.8%   |
| Goldstar                | 6         | 3.41%   |
| Apple                   | 6         | 3.41%   |
| AOC                     | 6         | 3.41%   |
| Dell                    | 5         | 2.84%   |
| Chi Mei Optoelectronics | 4         | 2.27%   |
| Sony                    | 2         | 1.14%   |
| Sharp                   | 2         | 1.14%   |
| PANDA                   | 2         | 1.14%   |
| Hewlett-Packard         | 2         | 1.14%   |
| CPT                     | 2         | 1.14%   |
| ASUSTek Computer        | 2         | 1.14%   |
| ViewSonic               | 1         | 0.57%   |
| Sun                     | 1         | 0.57%   |
| RTK                     | 1         | 0.57%   |
| PRISM+                  | 1         | 0.57%   |
| Panasonic               | 1         | 0.57%   |
| LG Philips              | 1         | 0.57%   |
| Lenovo                  | 1         | 0.57%   |
| KDC                     | 1         | 0.57%   |
| InnoLux Display         | 1         | 0.57%   |
| Hitachi                 | 1         | 0.57%   |
| GAOMON                  | 1         | 0.57%   |
| Envision                | 1         | 0.57%   |
| CVT                     | 1         | 0.57%   |
| Ancor Communications    | 1         | 0.57%   |
| AGO                     | 1         | 0.57%   |
| Acer                    | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 5         | 2.84%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3         | 1.7%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 1.7%    |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.7%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 1.14%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 2         | 1.14%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 480x270mm 21.7-inch           | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 1.14%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.14%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.14%   |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch         | 1         | 0.57%   |
| Sun 48FHD_LCD_TV SCE0301 1920x1080 1280x720mm 57.8-inch               | 1         | 0.57%   |
| Sony TV SNY1B02 1360x768                                              | 1         | 0.57%   |
| Sony TV SNY0902 1920x1080                                             | 1         | 0.57%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 1         | 0.57%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.57%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM058A 1920x1080 531x298mm 24.0-inch  | 1         | 0.57%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC345A 1366x768 309x174mm 14.0-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4178 3200x2000 344x215mm 16.0-inch | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC3030 2560x1600 262x164mm 12.2-inch | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 61        | 36.97%  |
| 1920x1080 (FHD)   | 55        | 33.33%  |
| 3840x2160 (4K)    | 12        | 7.27%   |
| 1280x800 (WXGA)   | 11        | 6.67%   |
| 1600x900 (HD+)    | 8         | 4.85%   |
| 1280x1024 (SXGA)  | 4         | 2.42%   |
| 2560x1440 (QHD)   | 3         | 1.82%   |
| 1440x900 (WXGA+)  | 3         | 1.82%   |
| 1920x1200 (WUXGA) | 2         | 1.21%   |
| 1360x768          | 2         | 1.21%   |
| 3840x2400         | 1         | 0.61%   |
| 3200x2000         | 1         | 0.61%   |
| 2560x1600         | 1         | 0.61%   |
| 1400x1050         | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 71        | 40.8%   |
| 13     | 27        | 15.52%  |
| 14     | 24        | 13.79%  |
| 17     | 8         | 4.6%    |
| 23     | 6         | 3.45%   |
| 21     | 6         | 3.45%   |
| 19     | 4         | 2.3%    |
| 84     | 3         | 1.72%   |
| 31     | 3         | 1.72%   |
| 24     | 3         | 1.72%   |
| 18     | 3         | 1.72%   |
| 16     | 3         | 1.72%   |
| 12     | 3         | 1.72%   |
| 11     | 3         | 1.72%   |
| 72     | 2         | 1.15%   |
| 57     | 2         | 1.15%   |
| 27     | 2         | 1.15%   |
| 32     | 1         | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 116       | 67.44%  |
| 201-300     | 15        | 8.72%   |
| 501-600     | 11        | 6.4%    |
| 401-500     | 11        | 6.4%    |
| 351-400     | 8         | 4.65%   |
| 1501-2000   | 5         | 2.91%   |
| 601-700     | 3         | 1.74%   |
| 701-800     | 2         | 1.16%   |
| 1001-1500   | 1         | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 123       | 82%     |
| 16/10 | 20        | 13.33%  |
| 5/4   | 4         | 2.67%   |
| 4/3   | 2         | 1.33%   |
| 0.56  | 1         | 0.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 71        | 41.04%  |
| 81-90          | 48        | 27.75%  |
| 201-250        | 13        | 7.51%   |
| More than 1000 | 7         | 4.05%   |
| 151-200        | 6         | 3.47%   |
| 121-130        | 5         | 2.89%   |
| 351-500        | 4         | 2.31%   |
| 141-150        | 4         | 2.31%   |
| 71-80          | 3         | 1.73%   |
| 51-60          | 3         | 1.73%   |
| 111-120        | 3         | 1.73%   |
| 61-70          | 2         | 1.16%   |
| 301-350        | 2         | 1.16%   |
| 131-140        | 1         | 0.58%   |
| 91-100         | 1         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 72        | 42.35%  |
| 121-160       | 60        | 35.29%  |
| 51-100        | 25        | 14.71%  |
| More than 240 | 5         | 2.94%   |
| 1-50          | 5         | 2.94%   |
| 161-240       | 3         | 1.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 112       | 74.67%  |
| 2     | 32        | 21.33%  |
| 3     | 4         | 2.67%   |
| 0     | 2         | 1.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 82        | 35.34%  |
| Intel                    | 66        | 28.45%  |
| Qualcomm Atheros         | 38        | 16.38%  |
| Broadcom                 | 22        | 9.48%   |
| Broadcom Limited         | 7         | 3.02%   |
| TP-Link                  | 4         | 1.72%   |
| MediaTek                 | 3         | 1.29%   |
| ASIX Electronics         | 2         | 0.86%   |
| Xiaomi                   | 1         | 0.43%   |
| Nvidia                   | 1         | 0.43%   |
| Marvell Technology Group | 1         | 0.43%   |
| JMicron Technology       | 1         | 0.43%   |
| Huawei Technologies      | 1         | 0.43%   |
| Hewlett-Packard          | 1         | 0.43%   |
| DisplayLink              | 1         | 0.43%   |
| Dell                     | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 15.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 7.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 3.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 3.09%   |
| Intel Wireless 7265                                               | 8         | 2.75%   |
| Intel Wireless 7260                                               | 7         | 2.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 2.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.06%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 5         | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 5         | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.37%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.03%   |
| Intel Wireless 8260                                               | 3         | 1.03%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.03%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.03%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                         | 2         | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.69%   |
| Realtek 802.11ac NIC                                              | 2         | 0.69%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.69%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.69%   |
| Intel Wireless 3160                                               | 2         | 0.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.69%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.69%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 57        | 38.78%  |
| Qualcomm Atheros      | 31        | 21.09%  |
| Realtek Semiconductor | 27        | 18.37%  |
| Broadcom              | 18        | 12.24%  |
| Broadcom Limited      | 7         | 4.76%   |
| TP-Link               | 4         | 2.72%   |
| MediaTek              | 2         | 1.36%   |
| Dell                  | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 10        | 6.67%   |
| Intel Wireless 7265                                                                   | 8         | 5.33%   |
| Intel Wireless 7260                                                                   | 7         | 4.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 6         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 6         | 4%      |
| Realtek RTL8723DE Wireless Network Adapter                                            | 5         | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 5         | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 5         | 3.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 5         | 3.33%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 5         | 3.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 4         | 2.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 2.67%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 2.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 3         | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 2%      |
| Intel Wireless 8260                                                                   | 3         | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 2%      |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 3         | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 2%      |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                             | 2         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 1.33%   |
| Realtek 802.11ac NIC                                                                  | 2         | 1.33%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 1.33%   |
| Intel Wireless 3160                                                                   | 2         | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 2         | 1.33%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.33%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.33%   |
| Broadcom Limited BCM4311 802.11a/b/g                                                  | 2         | 1.33%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                 | 1         | 0.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 0.67%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                | 1         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.67%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 73        | 55.3%   |
| Intel                    | 29        | 21.97%  |
| Broadcom                 | 11        | 8.33%   |
| Qualcomm Atheros         | 10        | 7.58%   |
| ASIX Electronics         | 2         | 1.52%   |
| Xiaomi                   | 1         | 0.76%   |
| Nvidia                   | 1         | 0.76%   |
| MediaTek                 | 1         | 0.76%   |
| Marvell Technology Group | 1         | 0.76%   |
| JMicron Technology       | 1         | 0.76%   |
| Huawei Technologies      | 1         | 0.76%   |
| DisplayLink              | 1         | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 32.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 16.43%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 6.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.29%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 3.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 2.14%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.14%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 1.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.43%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.43%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 1.43%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.71%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.71%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.71%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.71%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.71%   |
| MediaTek moto g22                                                 | 1         | 0.71%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.71%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.71%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.71%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.71%   |
| Intel 82599 10 Gigabit Network Connection                         | 1         | 0.71%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.71%   |
| Huawei E353/E3131                                                 | 1         | 0.71%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 141       | 53.21%  |
| Ethernet | 123       | 46.42%  |
| Modem    | 1         | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 111       | 73.51%  |
| Ethernet | 40        | 26.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 115       | 79.31%  |
| 1     | 23        | 15.86%  |
| 3     | 5         | 3.45%   |
| 0     | 2         | 1.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 142       | 97.26%  |
| Yes  | 4         | 2.74%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 41.28%  |
| Realtek Semiconductor           | 16        | 14.68%  |
| Qualcomm Atheros Communications | 15        | 13.76%  |
| Broadcom                        | 8         | 7.34%   |
| Apple                           | 6         | 5.5%    |
| Lite-On Technology              | 4         | 3.67%   |
| IMC Networks                    | 4         | 3.67%   |
| Toshiba                         | 3         | 2.75%   |
| Hewlett-Packard                 | 2         | 1.83%   |
| Foxconn / Hon Hai               | 2         | 1.83%   |
| Cambridge Silicon Radio         | 2         | 1.83%   |
| Realtek                         | 1         | 0.92%   |
| Dell                            | 1         | 0.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 19.27%  |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 9.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 8.26%   |
| Realtek Bluetooth Radio                             | 8         | 7.34%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 6.42%   |
| Intel AX201 Bluetooth                               | 4         | 3.67%   |
| Intel AX200 Bluetooth                               | 4         | 3.67%   |
| Apple Bluetooth Host Controller                     | 4         | 3.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 2.75%   |
| Intel Bluetooth Device                              | 3         | 2.75%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 2.75%   |
| Toshiba Bluetooth Device                            | 2         | 1.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.83%   |
| Intel AX210 Bluetooth                               | 2         | 1.83%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.83%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.83%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.83%   |
| Toshiba BCM43142A0                                  | 1         | 0.92%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.92%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.92%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.92%   |
| Lite-On Wireless_Device                             | 1         | 0.92%   |
| Lite-On Bluetooth Device                            | 1         | 0.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.92%   |
| IMC Networks Wireless_Device                        | 1         | 0.92%   |
| IMC Networks Bluetooth                              | 1         | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.92%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.92%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.92%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.92%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.92%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.92%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.92%   |
| Apple Bluetooth HCI                                 | 1         | 0.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 121       | 65.41%  |
| AMD                    | 26        | 14.05%  |
| Nvidia                 | 19        | 10.27%  |
| Generalplus Technology | 3         | 1.62%   |
| Plantronics            | 2         | 1.08%   |
| Logitech               | 2         | 1.08%   |
| JMTek                  | 2         | 1.08%   |
| GN Netcom              | 2         | 1.08%   |
| C-Media Electronics    | 2         | 1.08%   |
| Sony                   | 1         | 0.54%   |
| Realtek Semiconductor  | 1         | 0.54%   |
| Lenovo                 | 1         | 0.54%   |
| DCMT Technology        | 1         | 0.54%   |
| CMX Systems            | 1         | 0.54%   |
| Afatech                | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 7.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 7.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 5%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 4.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 3.64%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 3.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 3.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 3.18%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 3.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.18%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.27%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.27%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.82%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.36%   |
| Nvidia Audio device                                                                               | 3         | 1.36%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.36%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.36%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 1.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.36%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.91%   |
| Sony DualSense Wireless Controller                                                                | 1         | 0.45%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.45%   |
| Plantronics Blackwire 5220 Series                                                                 | 1         | 0.45%   |
| Plantronics Blackwire 3225 Series                                                                 | 1         | 0.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 31.68%  |
| SK hynix            | 19        | 18.81%  |
| Micron Technology   | 8         | 7.92%   |
| Kingston            | 8         | 7.92%   |
| Crucial             | 8         | 7.92%   |
| Nanya Technology    | 5         | 4.95%   |
| Team                | 4         | 3.96%   |
| Corsair             | 4         | 3.96%   |
| A-DATA Technology   | 4         | 3.96%   |
| Unknown             | 3         | 2.97%   |
| Transcend           | 1         | 0.99%   |
| Super Talent        | 1         | 0.99%   |
| Ramaxel Technology  | 1         | 0.99%   |
| Patriot             | 1         | 0.99%   |
| G.Skill             | 1         | 0.99%   |
| fef5                | 1         | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s     | 4         | 3.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 4         | 3.42%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s               | 4         | 3.42%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s               | 4         | 3.42%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 3         | 2.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.71%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 1.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.71%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 1.71%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 1.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.71%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s      | 2         | 1.71%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 2         | 1.71%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s               | 1         | 0.85%   |
| Unknown RAM Module 8GB SODIMM DDR3                        | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3                        | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1         | 0.85%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s       | 1         | 0.85%   |
| Super Talent RAM SUPERTALENT02 8GB SODIMM DDR3 1600MT/s   | 1         | 0.85%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s              | 1         | 0.85%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1         | 0.85%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s    | 1         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 0.85%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 0.85%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 0.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1         | 0.85%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 0.85%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 1         | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 0.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 1         | 0.85%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s    | 1         | 0.85%   |
| Samsung RAM Module 2GB SODIMM LPDDR3 1600MT/s             | 1         | 0.85%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s  | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 36        | 43.37%  |
| DDR3    | 35        | 42.17%  |
| DDR5    | 3         | 3.61%   |
| DDR2    | 3         | 3.61%   |
| SDRAM   | 2         | 2.41%   |
| LPDDR4  | 2         | 2.41%   |
| LPDDR3  | 1         | 1.2%    |
| Unknown | 1         | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 95.06%  |
| Row Of Chips | 2         | 2.47%   |
| Chip         | 1         | 1.23%   |
| Unknown      | 1         | 1.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 37        | 37.76%  |
| 8192  | 33        | 33.67%  |
| 16384 | 12        | 12.24%  |
| 2048  | 8         | 8.16%   |
| 32768 | 7         | 7.14%   |
| 1024  | 1         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 27.37%  |
| 2667    | 23        | 24.21%  |
| 3200    | 9         | 9.47%   |
| 1333    | 7         | 7.37%   |
| 1334    | 6         | 6.32%   |
| 3266    | 4         | 4.21%   |
| 2400    | 4         | 4.21%   |
| 2133    | 3         | 3.16%   |
| 667     | 3         | 3.16%   |
| 4800    | 2         | 2.11%   |
| 4199    | 2         | 2.11%   |
| Unknown | 2         | 2.11%   |
| 8400    | 1         | 1.05%   |
| 5600    | 1         | 1.05%   |
| 2933    | 1         | 1.05%   |
| 1067    | 1         | 1.05%   |

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
| Seiko Epson L380 Series | 1         | 50%     |
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
| Chicony Electronics                    | 30        | 23.08%  |
| Microdia                               | 15        | 11.54%  |
| IMC Networks                           | 15        | 11.54%  |
| Sunplus Innovation Technology          | 12        | 9.23%   |
| Realtek Semiconductor                  | 11        | 8.46%   |
| Quanta                                 | 6         | 4.62%   |
| Apple                                  | 6         | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.85%   |
| Primax Electronics                     | 4         | 3.08%   |
| Suyin                                  | 3         | 2.31%   |
| Lite-On Technology                     | 3         | 2.31%   |
| Luxvisions Innotech Limited            | 2         | 1.54%   |
| Logitech                               | 2         | 1.54%   |
| Alcor Micro                            | 2         | 1.54%   |
| Acer                                   | 2         | 1.54%   |
| Z-Star Microelectronics                | 1         | 0.77%   |
| Syntek                                 | 1         | 0.77%   |
| Sonix Technology                       | 1         | 0.77%   |
| Silicon Motion                         | 1         | 0.77%   |
| Samsung Electronics                    | 1         | 0.77%   |
| Microsoft                              | 1         | 0.77%   |
| LG Electronics                         | 1         | 0.77%   |
| Importek                               | 1         | 0.77%   |
| GEMBIRD                                | 1         | 0.77%   |
| Creative Technology                    | 1         | 0.77%   |
| Bison Electronics                      | 1         | 0.77%   |
| Alpha Imaging Technology               | 1         | 0.77%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 10        | 7.58%   |
| Chicony Integrated Camera                        | 9         | 6.82%   |
| Sunplus HD WebCam                                | 5         | 3.79%   |
| IMC Networks Integrated Camera                   | 5         | 3.79%   |
| Apple FaceTime HD Camera                         | 5         | 3.79%   |
| Sunplus Integrated_Webcam_HD                     | 3         | 2.27%   |
| Realtek Integrated_Webcam_HD                     | 3         | 2.27%   |
| Primax HP HD Webcam [Fixed]                      | 3         | 2.27%   |
| IMC Networks USB2.0 HD UVC WebCam                | 3         | 2.27%   |
| Chicony TOSHIBA Web Camera - HD                  | 3         | 2.27%   |
| Realtek Integrated Webcam HD                     | 2         | 1.52%   |
| Realtek Integrated Webcam                        | 2         | 1.52%   |
| Quanta HP TrueVision HD Camera                   | 2         | 1.52%   |
| Quanta HD WebCam                                 | 2         | 1.52%   |
| Microdia Integrated Webcam                       | 2         | 1.52%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 1.52%   |
| Chicony USB 2.0 Camera                           | 2         | 1.52%   |
| Chicony Integrated HP HD Webcam                  | 2         | 1.52%   |
| Chicony HP Truevision HD                         | 2         | 1.52%   |
| Chicony HP HD Webcam                             | 2         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.52%   |
| Z-Star Vega USB2.0 Camera                        | 1         | 0.76%   |
| Syntek EasyCamera                                | 1         | 0.76%   |
| Suyin TOSHIBA Web Camera - HD                    | 1         | 0.76%   |
| Suyin HP TrueVision HD                           | 1         | 0.76%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.76%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 1         | 0.76%   |
| Sunplus Integrated Camera                        | 1         | 0.76%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.76%   |
| Sunplus Dell Integrated Webcam                   | 1         | 0.76%   |
| Sonix USB2.0 FHD UVC WebCam                      | 1         | 0.76%   |
| Silicon Motion ATIV Real HD Camera               | 1         | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode)          | 1         | 0.76%   |
| Realtek USB Camera                               | 1         | 0.76%   |
| Realtek Rear Camera                              | 1         | 0.76%   |
| Realtek HP Wide Vision FHD Camera                | 1         | 0.76%   |
| Realtek HP Truevision HD                         | 1         | 0.76%   |
| Realtek Front Camera                             | 1         | 0.76%   |
| Quanta HP Webcam                                 | 1         | 0.76%   |
| Quanta HD User Facing                            | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 51.85%  |
| Synaptics                  | 6         | 22.22%  |
| Shenzhen Goodix Technology | 3         | 11.11%  |
| STMicroelectronics         | 1         | 3.7%    |
| LighTuning Technology      | 1         | 3.7%    |
| Elan Microelectronics      | 1         | 3.7%    |
| AuthenTec                  | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 4         | 14.81%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device               | 3         | 11.11%  |
| Validity Sensors VFS491                           | 2         | 7.41%   |
| Validity Sensors VFS471 Fingerprint Reader        | 2         | 7.41%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 7.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader  | 2         | 7.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 3.7%    |
| Validity Sensors Synaptics WBDI                   | 1         | 3.7%    |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 3.7%    |
| Validity Sensors Fingerprint scanner              | 1         | 3.7%    |
| Synaptics WBDI                                    | 1         | 3.7%    |
| STMicroelectronics Fingerprint Reader             | 1         | 3.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 3.7%    |
| Elan ELAN:ARM-M4                                  | 1         | 3.7%    |
| AuthenTec AES1600                                 | 1         | 3.7%    |

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
| 0     | 92        | 61.33%  |
| 1     | 49        | 32.67%  |
| 2     | 6         | 4%      |
| 3     | 3         | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 26        | 36.62%  |
| Graphics card            | 14        | 19.72%  |
| Net/wireless             | 13        | 18.31%  |
| Chipcard                 | 8         | 11.27%  |
| Multimedia controller    | 2         | 2.82%   |
| Storage                  | 1         | 1.41%   |
| Sound                    | 1         | 1.41%   |
| Net/ethernet             | 1         | 1.41%   |
| Firewire controller      | 1         | 1.41%   |
| Communication controller | 1         | 1.41%   |
| Card reader              | 1         | 1.41%   |
| Camera                   | 1         | 1.41%   |
| Bluetooth                | 1         | 1.41%   |

