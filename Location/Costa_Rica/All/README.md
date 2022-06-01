Linux in Costa Rica - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Costa_Rica/Desktop/README.md) and [notebooks](/Location/Costa_Rica/Notebook/README.md).

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

Total: 259

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T440s 20ARS29U0... | Notebook    | [50de8ad2e9](https://linux-hardware.org/?probe=50de8ad2e9) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| Dell          | Latitude 7400               | Notebook    | [caf85903ad](https://linux-hardware.org/?probe=caf85903ad) | May 19, 2022 |
| Dell          | Inspiron 5565               | Notebook    | [d5a8629a31](https://linux-hardware.org/?probe=d5a8629a31) | May 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Lenovo        | ThinkPad L420 7829AA4       | Notebook    | [9c1bbe8cf2](https://linux-hardware.org/?probe=9c1bbe8cf2) | May 14, 2022 |
| HP            | 0AECh D                     | Desktop     | [68adfe0740](https://linux-hardware.org/?probe=68adfe0740) | May 12, 2022 |
| HP            | 83EE                        | Desktop     | [55171637ca](https://linux-hardware.org/?probe=55171637ca) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [637af2dcc6](https://linux-hardware.org/?probe=637af2dcc6) | Apr 29, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [1f14473753](https://linux-hardware.org/?probe=1f14473753) | Apr 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a1130d8070](https://linux-hardware.org/?probe=a1130d8070) | Apr 13, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [6a631fae48](https://linux-hardware.org/?probe=6a631fae48) | Mar 22, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
| Dell          | Latitude E5500              | Notebook    | [13be4a0a1b](https://linux-hardware.org/?probe=13be4a0a1b) | Mar 16, 2022 |
| Dell          | Latitude E5500              | Notebook    | [d5f8fd7890](https://linux-hardware.org/?probe=d5f8fd7890) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [b7b428082a](https://linux-hardware.org/?probe=b7b428082a) | Mar 05, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [8807d99cb4](https://linux-hardware.org/?probe=8807d99cb4) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [c0adf77f3f](https://linux-hardware.org/?probe=c0adf77f3f) | Feb 26, 2022 |
| Sony          | SVD13215PLB                 | Notebook    | [82c4287f85](https://linux-hardware.org/?probe=82c4287f85) | Feb 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [b355ea1ff3](https://linux-hardware.org/?probe=b355ea1ff3) | Feb 20, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [8468cd0da9](https://linux-hardware.org/?probe=8468cd0da9) | Feb 19, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [80e2f3c47e](https://linux-hardware.org/?probe=80e2f3c47e) | Feb 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Dell          | 0RW203 A00                  | Desktop     | [21ac06a9f6](https://linux-hardware.org/?probe=21ac06a9f6) | Feb 12, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [8fc6552bc9](https://linux-hardware.org/?probe=8fc6552bc9) | Feb 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [dbc7cbcfe1](https://linux-hardware.org/?probe=dbc7cbcfe1) | Feb 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ac53ba49ef](https://linux-hardware.org/?probe=ac53ba49ef) | Jan 28, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f953ad7f3](https://linux-hardware.org/?probe=3f953ad7f3) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [eecedd12b2](https://linux-hardware.org/?probe=eecedd12b2) | Jan 14, 2022 |
| Samsung       | 930QAA                      | Convertible | [56758d8bfb](https://linux-hardware.org/?probe=56758d8bfb) | Jan 10, 2022 |
| Samsung       | 930QAA                      | Convertible | [206f508be5](https://linux-hardware.org/?probe=206f508be5) | Jan 10, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [6837cca618](https://linux-hardware.org/?probe=6837cca618) | Jan 02, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | Desktop     | [9158036ed3](https://linux-hardware.org/?probe=9158036ed3) | Dec 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b482ef13ea](https://linux-hardware.org/?probe=b482ef13ea) | Dec 26, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| MSI           | H55M-E33                    | Desktop     | [f0786be9c3](https://linux-hardware.org/?probe=f0786be9c3) | Nov 14, 2021 |
| HP            | 18E4                        | Desktop     | [692c64d7c1](https://linux-hardware.org/?probe=692c64d7c1) | Nov 08, 2021 |
| HP            | 18E4                        | Desktop     | [499e85c152](https://linux-hardware.org/?probe=499e85c152) | Nov 07, 2021 |
| MSI           | H55M-E33                    | Desktop     | [3d8c474259](https://linux-hardware.org/?probe=3d8c474259) | Nov 06, 2021 |
| Dell          | Latitude 5490               | Notebook    | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| Dell          | Inspiron 3595               | Notebook    | [1df662506b](https://linux-hardware.org/?probe=1df662506b) | Oct 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [5bb3c9bc8b](https://linux-hardware.org/?probe=5bb3c9bc8b) | Oct 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [bfadd59ae5](https://linux-hardware.org/?probe=bfadd59ae5) | Oct 18, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [ff12aa7481](https://linux-hardware.org/?probe=ff12aa7481) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2a83508f22](https://linux-hardware.org/?probe=2a83508f22) | Oct 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| TPV-INVENT... | 2AF2 A01                    | Desktop     | [23e967d7f5](https://linux-hardware.org/?probe=23e967d7f5) | Oct 06, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Dell          | Latitude D620               | Notebook    | [1dc8e001f5](https://linux-hardware.org/?probe=1dc8e001f5) | Sep 28, 2021 |
| ZOTAC         | NM10                        | Desktop     | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [29a6b45091](https://linux-hardware.org/?probe=29a6b45091) | Sep 26, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [5ed9f083e1](https://linux-hardware.org/?probe=5ed9f083e1) | Sep 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [00b3e62e2e](https://linux-hardware.org/?probe=00b3e62e2e) | Sep 10, 2021 |
| MSI           | GF75 Thin 9SD               | Notebook    | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| ZOTAC         | NM10                        | Desktop     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| Dell          | 0PU052                      | Desktop     | [25ce6d5bbd](https://linux-hardware.org/?probe=25ce6d5bbd) | Aug 05, 2021 |
| Olivetti      | CL133A                      | Notebook    | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| HP            | Pavilion g4                 | Notebook    | [3f01790d4e](https://linux-hardware.org/?probe=3f01790d4e) | Jul 21, 2021 |
| AZW           | GT-R                        | Notebook    | [115230aa47](https://linux-hardware.org/?probe=115230aa47) | Jul 19, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [a5a9cfcd44](https://linux-hardware.org/?probe=a5a9cfcd44) | Jul 18, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [689b83e978](https://linux-hardware.org/?probe=689b83e978) | Jul 18, 2021 |
| Olivetti      | CL133A                      | Notebook    | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| ASUSTek       | U46E                        | Notebook    | [720dec33c4](https://linux-hardware.org/?probe=720dec33c4) | Jul 14, 2021 |
| HP            | ProBook 6460b               | Notebook    | [b39eb9b256](https://linux-hardware.org/?probe=b39eb9b256) | Jul 13, 2021 |
| Dell          | G3 3590                     | Notebook    | [3781e31377](https://linux-hardware.org/?probe=3781e31377) | Jul 12, 2021 |
| Olivetti      | CL133A                      | Notebook    | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | Notebook    | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [9e01fd5e8c](https://linux-hardware.org/?probe=9e01fd5e8c) | Jun 20, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [e937e8ba7e](https://linux-hardware.org/?probe=e937e8ba7e) | Jun 20, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [ab19b80507](https://linux-hardware.org/?probe=ab19b80507) | Jun 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b05fbab283](https://linux-hardware.org/?probe=b05fbab283) | Jun 06, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [2d1d9030e8](https://linux-hardware.org/?probe=2d1d9030e8) | May 31, 2021 |
| HP            | Pavilion dv6000 (RP297UA... | Notebook    | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3e92571a0c](https://linux-hardware.org/?probe=3e92571a0c) | May 26, 2021 |
| Toshiba       | Satellite C845              | Notebook    | [e3b90e238b](https://linux-hardware.org/?probe=e3b90e238b) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6f3c2aa3be](https://linux-hardware.org/?probe=6f3c2aa3be) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [8ccda2ce59](https://linux-hardware.org/?probe=8ccda2ce59) | May 24, 2021 |
| Toshiba       | Satellite C845              | Notebook    | [4d346e2691](https://linux-hardware.org/?probe=4d346e2691) | May 24, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [5e2e76f838](https://linux-hardware.org/?probe=5e2e76f838) | May 20, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [93286a0d38](https://linux-hardware.org/?probe=93286a0d38) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [796f490bbb](https://linux-hardware.org/?probe=796f490bbb) | May 15, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [1da876ea0b](https://linux-hardware.org/?probe=1da876ea0b) | May 06, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [0216a041d2](https://linux-hardware.org/?probe=0216a041d2) | May 05, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [604b735ad8](https://linux-hardware.org/?probe=604b735ad8) | May 02, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a181ae8691](https://linux-hardware.org/?probe=a181ae8691) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [d363966e4c](https://linux-hardware.org/?probe=d363966e4c) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [204cd9c44f](https://linux-hardware.org/?probe=204cd9c44f) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e20fc33e2b](https://linux-hardware.org/?probe=e20fc33e2b) | Apr 29, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [3cca89aa74](https://linux-hardware.org/?probe=3cca89aa74) | Apr 28, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [38c505f6bd](https://linux-hardware.org/?probe=38c505f6bd) | Apr 23, 2021 |
| Intel         | D33217CK G76541-302         | Desktop     | [1db9d29c38](https://linux-hardware.org/?probe=1db9d29c38) | Apr 19, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e990abe7f1](https://linux-hardware.org/?probe=e990abe7f1) | Apr 11, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [41c14db0ef](https://linux-hardware.org/?probe=41c14db0ef) | Apr 11, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [48f003363a](https://linux-hardware.org/?probe=48f003363a) | Apr 09, 2021 |
| Dell          | 096JG8 A01                  | Desktop     | [1cf6d1daea](https://linux-hardware.org/?probe=1cf6d1daea) | Apr 02, 2021 |
| Supermicro    | X9DAi                       | Desktop     | [ff94b1201c](https://linux-hardware.org/?probe=ff94b1201c) | Mar 31, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [2ff9864ce6](https://linux-hardware.org/?probe=2ff9864ce6) | Mar 29, 2021 |
| Dell          | G3 3590                     | Notebook    | [3c952dbc96](https://linux-hardware.org/?probe=3c952dbc96) | Mar 26, 2021 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d8f82a3984](https://linux-hardware.org/?probe=d8f82a3984) | Mar 26, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| HP            | Pavilion g4                 | Notebook    | [1e7372e4f2](https://linux-hardware.org/?probe=1e7372e4f2) | Mar 01, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [e00317dc4d](https://linux-hardware.org/?probe=e00317dc4d) | Mar 01, 2021 |
| Unknown       | Unknown                     | Notebook    | [941e941403](https://linux-hardware.org/?probe=941e941403) | Feb 27, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| Google        | Celes                       | Notebook    | [b30c090b2b](https://linux-hardware.org/?probe=b30c090b2b) | Feb 22, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [41ba11dbb4](https://linux-hardware.org/?probe=41ba11dbb4) | Feb 18, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [8570b15385](https://linux-hardware.org/?probe=8570b15385) | Feb 14, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [34bf1da3fe](https://linux-hardware.org/?probe=34bf1da3fe) | Feb 13, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [48548effcd](https://linux-hardware.org/?probe=48548effcd) | Feb 13, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [660afa073b](https://linux-hardware.org/?probe=660afa073b) | Feb 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [840e0e2818](https://linux-hardware.org/?probe=840e0e2818) | Feb 04, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [e10690d1d2](https://linux-hardware.org/?probe=e10690d1d2) | Feb 04, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [e0de5d87e6](https://linux-hardware.org/?probe=e0de5d87e6) | Feb 04, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [84c932e071](https://linux-hardware.org/?probe=84c932e071) | Feb 02, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [473419d486](https://linux-hardware.org/?probe=473419d486) | Jan 24, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [738e03e488](https://linux-hardware.org/?probe=738e03e488) | Jan 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [f24be700aa](https://linux-hardware.org/?probe=f24be700aa) | Jan 21, 2021 |
| Dell          | Precision M4800             | Notebook    | [316c7dd34b](https://linux-hardware.org/?probe=316c7dd34b) | Jan 21, 2021 |
| HP            | Laptop 14-bp0xx             | Notebook    | [4badbab2db](https://linux-hardware.org/?probe=4badbab2db) | Jan 19, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [1a731e13e0](https://linux-hardware.org/?probe=1a731e13e0) | Jan 18, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6a0e9eff49](https://linux-hardware.org/?probe=6a0e9eff49) | Jan 16, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [76fe08b67a](https://linux-hardware.org/?probe=76fe08b67a) | Jan 14, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [8d9be2defd](https://linux-hardware.org/?probe=8d9be2defd) | Jan 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [6c9d42b55d](https://linux-hardware.org/?probe=6c9d42b55d) | Jan 08, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [9ff8161bec](https://linux-hardware.org/?probe=9ff8161bec) | Jan 08, 2021 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [6706c380ab](https://linux-hardware.org/?probe=6706c380ab) | Dec 21, 2020 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [a481e8e9c0](https://linux-hardware.org/?probe=a481e8e9c0) | Dec 16, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [266b8d7543](https://linux-hardware.org/?probe=266b8d7543) | Dec 16, 2020 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [a305c14111](https://linux-hardware.org/?probe=a305c14111) | Dec 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2d9e84acd0](https://linux-hardware.org/?probe=2d9e84acd0) | Dec 13, 2020 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [3c6c9b7bd3](https://linux-hardware.org/?probe=3c6c9b7bd3) | Dec 11, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Alienware     | 06G6JW A01                  | Desktop     | [812527d15d](https://linux-hardware.org/?probe=812527d15d) | Dec 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| Dell          | Latitude 7480               | Notebook    | [2e569dcaed](https://linux-hardware.org/?probe=2e569dcaed) | Oct 22, 2020 |
| Dell          | Latitude 7480               | Notebook    | [1cc0a03f18](https://linux-hardware.org/?probe=1cc0a03f18) | Oct 22, 2020 |
| HP            | 2B54 100                    | All in one  | [161455efd7](https://linux-hardware.org/?probe=161455efd7) | Oct 17, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [9f10520397](https://linux-hardware.org/?probe=9f10520397) | Oct 11, 2020 |
| Dell          | G3 3590                     | Notebook    | [4c2ddd8b88](https://linux-hardware.org/?probe=4c2ddd8b88) | Oct 01, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [6acb0908ff](https://linux-hardware.org/?probe=6acb0908ff) | Sep 18, 2020 |
| HP            | Unknown                     | Notebook    | [a446c81ca9](https://linux-hardware.org/?probe=a446c81ca9) | Sep 10, 2020 |
| HP            | 2B54 100                    | All in one  | [8e21d2bb01](https://linux-hardware.org/?probe=8e21d2bb01) | Sep 06, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [48e494142e](https://linux-hardware.org/?probe=48e494142e) | Aug 27, 2020 |
| Toshiba       | Satellite X205              | Notebook    | [b0d5e7d0dd](https://linux-hardware.org/?probe=b0d5e7d0dd) | Aug 26, 2020 |
| Toshiba       | Satellite X205              | Notebook    | [45e52f3631](https://linux-hardware.org/?probe=45e52f3631) | Aug 26, 2020 |
| Dell          | 042P49 A01                  | Desktop     | [36ddd61132](https://linux-hardware.org/?probe=36ddd61132) | Aug 12, 2020 |
| Acer          | Aspire 4739Z                | Notebook    | [44ec59d132](https://linux-hardware.org/?probe=44ec59d132) | Aug 11, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [4bdd603282](https://linux-hardware.org/?probe=4bdd603282) | Aug 06, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [4114f58581](https://linux-hardware.org/?probe=4114f58581) | Aug 06, 2020 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d8a8eb467a](https://linux-hardware.org/?probe=d8a8eb467a) | Aug 02, 2020 |
| Dell          | Latitude E5440              | Notebook    | [9d31b1e38d](https://linux-hardware.org/?probe=9d31b1e38d) | Jul 29, 2020 |
| Gateway       | FMCP7AM                     | Desktop     | [58e88b2df5](https://linux-hardware.org/?probe=58e88b2df5) | Jul 28, 2020 |
| ABIT          | AW9D-MAX                    | Desktop     | [fca26e4a11](https://linux-hardware.org/?probe=fca26e4a11) | Jul 21, 2020 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [c00d0feee3](https://linux-hardware.org/?probe=c00d0feee3) | Jul 21, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [73c5756fdd](https://linux-hardware.org/?probe=73c5756fdd) | Jul 01, 2020 |
| Dell          | G3 3590                     | Notebook    | [e2fa394ba6](https://linux-hardware.org/?probe=e2fa394ba6) | Jun 28, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [8119688776](https://linux-hardware.org/?probe=8119688776) | Jun 27, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [d2a2900148](https://linux-hardware.org/?probe=d2a2900148) | Jun 20, 2020 |
| ASRock        | B450 Steel Legend           | Desktop     | [7d9ad3146b](https://linux-hardware.org/?probe=7d9ad3146b) | Jun 12, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [4619502a6b](https://linux-hardware.org/?probe=4619502a6b) | May 28, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b9c266ed55](https://linux-hardware.org/?probe=b9c266ed55) | May 20, 2020 |
| HP            | ProBook 455 G4              | Notebook    | [6b6fe8e0c1](https://linux-hardware.org/?probe=6b6fe8e0c1) | May 18, 2020 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6252910769](https://linux-hardware.org/?probe=6252910769) | May 11, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [8fc4603f6c](https://linux-hardware.org/?probe=8fc4603f6c) | May 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [33cd43676f](https://linux-hardware.org/?probe=33cd43676f) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [1a81d95494](https://linux-hardware.org/?probe=1a81d95494) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [cd09b6b8a5](https://linux-hardware.org/?probe=cd09b6b8a5) | May 09, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [9311532f56](https://linux-hardware.org/?probe=9311532f56) | Apr 23, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [b662f230b2](https://linux-hardware.org/?probe=b662f230b2) | Apr 23, 2020 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [3c2d508fc2](https://linux-hardware.org/?probe=3c2d508fc2) | Apr 23, 2020 |
| HP            | Notebook                    | Notebook    | [5815277bb0](https://linux-hardware.org/?probe=5815277bb0) | Apr 22, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [2f87bcd627](https://linux-hardware.org/?probe=2f87bcd627) | Apr 07, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [16ff51d343](https://linux-hardware.org/?probe=16ff51d343) | Apr 07, 2020 |
| Acer          | Aspire V3-471               | Notebook    | [024d5b0563](https://linux-hardware.org/?probe=024d5b0563) | Apr 06, 2020 |
| Dell          | G3 3590                     | Notebook    | [26a4f7e20b](https://linux-hardware.org/?probe=26a4f7e20b) | Mar 22, 2020 |
| Dell          | G3 3590                     | Notebook    | [96d9b68953](https://linux-hardware.org/?probe=96d9b68953) | Mar 21, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [fcea840696](https://linux-hardware.org/?probe=fcea840696) | Mar 04, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [9246f32b7e](https://linux-hardware.org/?probe=9246f32b7e) | Mar 01, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [9398ebaa03](https://linux-hardware.org/?probe=9398ebaa03) | Feb 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [1419b6c5e7](https://linux-hardware.org/?probe=1419b6c5e7) | Feb 29, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [2bbf18e9e5](https://linux-hardware.org/?probe=2bbf18e9e5) | Feb 20, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [68895d1461](https://linux-hardware.org/?probe=68895d1461) | Feb 20, 2020 |
| HP            | ProBook 6460b               | Notebook    | [121b074dd0](https://linux-hardware.org/?probe=121b074dd0) | Feb 19, 2020 |
| Dell          | Latitude 5500               | Notebook    | [3a7f8e19f1](https://linux-hardware.org/?probe=3a7f8e19f1) | Feb 17, 2020 |
| ASUSTek       | K52F                        | Notebook    | [9dde03d12c](https://linux-hardware.org/?probe=9dde03d12c) | Feb 13, 2020 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [750ccde7c5](https://linux-hardware.org/?probe=750ccde7c5) | Jan 19, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [9eb64d7269](https://linux-hardware.org/?probe=9eb64d7269) | Jan 17, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [8211b13acf](https://linux-hardware.org/?probe=8211b13acf) | Jan 17, 2020 |
| ASRock        | 775i65GV                    | Desktop     | [0367c8a291](https://linux-hardware.org/?probe=0367c8a291) | Jan 07, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [5662d620a5](https://linux-hardware.org/?probe=5662d620a5) | Jan 03, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [bd9a062902](https://linux-hardware.org/?probe=bd9a062902) | Jan 03, 2020 |
| ASRock        | 775i65GV                    | Desktop     | [d0a8b9d7da](https://linux-hardware.org/?probe=d0a8b9d7da) | Dec 25, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [73da3dccf1](https://linux-hardware.org/?probe=73da3dccf1) | Nov 14, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [efeee7f2fc](https://linux-hardware.org/?probe=efeee7f2fc) | Nov 14, 2019 |
| Dell          | 042P49 A01                  | Desktop     | [ce3194fcde](https://linux-hardware.org/?probe=ce3194fcde) | Oct 28, 2019 |
| System76      | Lemur                       | Notebook    | [a9cc263cb4](https://linux-hardware.org/?probe=a9cc263cb4) | Oct 09, 2019 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [4ddf2bb220](https://linux-hardware.org/?probe=4ddf2bb220) | Oct 06, 2019 |
| HP            | ProBook 450 G2              | Notebook    | [c7959cccb3](https://linux-hardware.org/?probe=c7959cccb3) | Sep 30, 2019 |
| HP            | Notebook                    | Notebook    | [163fc3e9dd](https://linux-hardware.org/?probe=163fc3e9dd) | Sep 14, 2019 |
| Biostar       | H61MGV3                     | Desktop     | [911486bcc2](https://linux-hardware.org/?probe=911486bcc2) | Sep 08, 2019 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [c34161a66d](https://linux-hardware.org/?probe=c34161a66d) | Sep 02, 2019 |
| System76      | Lemur                       | Notebook    | [01bbf99115](https://linux-hardware.org/?probe=01bbf99115) | Sep 02, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | Notebook    | [47182bd3e3](https://linux-hardware.org/?probe=47182bd3e3) | Sep 01, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | Notebook    | [2105fa4def](https://linux-hardware.org/?probe=2105fa4def) | Sep 01, 2019 |
| HP            | Notebook                    | Notebook    | [b7e9995b67](https://linux-hardware.org/?probe=b7e9995b67) | Aug 18, 2019 |
| HP            | Notebook                    | Notebook    | [273d0bcc2e](https://linux-hardware.org/?probe=273d0bcc2e) | Aug 18, 2019 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [2e5b92af00](https://linux-hardware.org/?probe=2e5b92af00) | Aug 17, 2019 |
| Dell          | Latitude E5450              | Notebook    | [3336801ccf](https://linux-hardware.org/?probe=3336801ccf) | Aug 10, 2019 |
| Toshiba       | Satellite A305D             | Notebook    | [ebf0a9c89e](https://linux-hardware.org/?probe=ebf0a9c89e) | Aug 08, 2019 |
| Acer          | SW5-017P                    | Notebook    | [fbf9b74a34](https://linux-hardware.org/?probe=fbf9b74a34) | Jul 29, 2019 |
| Dell          | Latitude 5480               | Notebook    | [f488cfd08f](https://linux-hardware.org/?probe=f488cfd08f) | Jun 22, 2019 |
| Biostar       | H61MGV3                     | Desktop     | [0b1e8f1f08](https://linux-hardware.org/?probe=0b1e8f1f08) | Jun 12, 2019 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [7b2dc235f8](https://linux-hardware.org/?probe=7b2dc235f8) | May 18, 2019 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [328975f3a5](https://linux-hardware.org/?probe=328975f3a5) | May 15, 2019 |
| Dell          | Latitude 5480               | Notebook    | [694ca16d49](https://linux-hardware.org/?probe=694ca16d49) | May 04, 2019 |
| Lenovo        | SHARKBAY 31900003 STD       | Desktop     | [e7164fcda2](https://linux-hardware.org/?probe=e7164fcda2) | Dec 01, 2018 |
| Purism        | Librem 15 v3                | Notebook    | [00259367c8](https://linux-hardware.org/?probe=00259367c8) | Oct 29, 2018 |
| Purism        | Librem 15 v3                | Notebook    | [c5e1ab1520](https://linux-hardware.org/?probe=c5e1ab1520) | Oct 29, 2018 |
| ASUSTek       | X555LAB                     | Notebook    | [243803142a](https://linux-hardware.org/?probe=243803142a) | Aug 01, 2018 |
| Toshiba       | Satellite C645D             | Notebook    | [9d50eb7fdb](https://linux-hardware.org/?probe=9d50eb7fdb) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 21        | 11.8%   |
| Ubuntu 18.04                 | 18        | 10.11%  |
| OpenMandriva 4.2             | 16        | 8.99%   |
| OpenMandriva 4.3             | 6         | 3.37%   |
| Ubuntu 19.04                 | 4         | 2.25%   |
| Lubuntu 22.04                | 4         | 2.25%   |
| Lubuntu 21.10                | 4         | 2.25%   |
| Linux Mint 20.2              | 4         | 2.25%   |
| Linux Mint 19.3              | 4         | 2.25%   |
| Ubuntu 22.04                 | 3         | 1.69%   |
| Lubuntu 21.04                | 3         | 1.69%   |
| Debian 11                    | 3         | 1.69%   |
| Debian 10                    | 3         | 1.69%   |
| Zorin 15                     | 2         | 1.12%   |
| Xubuntu 20.04                | 2         | 1.12%   |
| UbuntuDDE 20.04              | 2         | 1.12%   |
| Ubuntu Studio 20.04          | 2         | 1.12%   |
| Ubuntu 21.04                 | 2         | 1.12%   |
| Pop!_OS 21.04                | 2         | 1.12%   |
| Pop!_OS 20.10                | 2         | 1.12%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.12%   |
| Manjaro 20.2.1               | 2         | 1.12%   |
| Lubuntu 20.04                | 2         | 1.12%   |
| Linux Mint 20.3              | 2         | 1.12%   |
| Linux Mint 20.1              | 2         | 1.12%   |
| Linux Mint 20                | 2         | 1.12%   |
| KDE neon 20.04               | 2         | 1.12%   |
| Fedora 34                    | 2         | 1.12%   |
| Fedora 32                    | 2         | 1.12%   |
| Debian Testing               | 2         | 1.12%   |
| Arch                         | 2         | 1.12%   |
| Zorin 16                     | 1         | 0.56%   |
| Zorin 12                     | 1         | 0.56%   |
| Xubuntu 18.04                | 1         | 0.56%   |
| Ubuntu MATE 18.04            | 1         | 0.56%   |
| Ubuntu 21.10                 | 1         | 0.56%   |
| Ubuntu 20.10                 | 1         | 0.56%   |
| Ubuntu 19.10                 | 1         | 0.56%   |
| Ubuntu 16.04                 | 1         | 0.56%   |
| ROSA R8.1                    | 1         | 0.56%   |
| ROSA R8                      | 1         | 0.56%   |
| ROSA R11.1                   | 1         | 0.56%   |
| ROSA R11                     | 1         | 0.56%   |
| ROSA R10                     | 1         | 0.56%   |
| Reborn OS Rolling            | 1         | 0.56%   |
| Raspbian 11                  | 1         | 0.56%   |
| PureOS 10.0                  | 1         | 0.56%   |
| Pop!_OS 21.10                | 1         | 0.56%   |
| Pop!_OS 20.04                | 1         | 0.56%   |
| Peppermint 10                | 1         | 0.56%   |
| Parrot 4.10                  | 1         | 0.56%   |
| OpenMandriva 4.50            | 1         | 0.56%   |
| Manjaro 21.2.5               | 1         | 0.56%   |
| Manjaro 21.2.0               | 1         | 0.56%   |
| Manjaro 21.0.1               | 1         | 0.56%   |
| Manjaro 20.2                 | 1         | 0.56%   |
| Manjaro 20.1                 | 1         | 0.56%   |
| Manjaro                      | 1         | 0.56%   |
| Lubuntu 20.10                | 1         | 0.56%   |
| Lubuntu 18.04                | 1         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 51        | 30.72%  |
| OpenMandriva  | 23        | 13.86%  |
| Linux Mint    | 14        | 8.43%   |
| Manjaro       | 8         | 4.82%   |
| Lubuntu       | 8         | 4.82%   |
| Debian        | 8         | 4.82%   |
| Fedora        | 7         | 4.22%   |
| Pop!_OS       | 6         | 3.61%   |
| Zorin         | 4         | 2.41%   |
| ROSA          | 4         | 2.41%   |
| Xubuntu       | 3         | 1.81%   |
| KDE neon      | 3         | 1.81%   |
| Arch          | 3         | 1.81%   |
| UbuntuDDE     | 2         | 1.2%    |
| Ubuntu Studio | 2         | 1.2%    |
| openSUSE      | 2         | 1.2%    |
| Kubuntu       | 2         | 1.2%    |
| Endless       | 2         | 1.2%    |
| Elementary    | 2         | 1.2%    |
| Ubuntu MATE   | 1         | 0.6%    |
| Reborn OS     | 1         | 0.6%    |
| Raspbian      | 1         | 0.6%    |
| PureOS        | 1         | 0.6%    |
| Peppermint    | 1         | 0.6%    |
| Parrot        | 1         | 0.6%    |
| Kali          | 1         | 0.6%    |
| EndeavourOS   | 1         | 0.6%    |
| Clear Linux   | 1         | 0.6%    |
| BlackPanther  | 1         | 0.6%    |
| ArcoLinux     | 1         | 0.6%    |
| ALT Linux     | 1         | 0.6%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002    | 16        | 8.21%   |
| 5.16.7-desktop-1omv4003     | 6         | 3.08%   |
| 5.4.0-42-generic            | 5         | 2.56%   |
| 5.4.0-70-generic            | 4         | 2.05%   |
| 5.13.0-16-generic           | 4         | 2.05%   |
| 5.11.0-27-generic           | 4         | 2.05%   |
| 5.0.0-23-generic            | 4         | 2.05%   |
| 5.8.0-50-generic            | 3         | 1.54%   |
| 5.4.0-77-generic            | 3         | 1.54%   |
| 5.0.0-25-generic            | 3         | 1.54%   |
| 5.9.16-1-MANJARO            | 2         | 1.03%   |
| 5.8.0-7630-generic          | 2         | 1.03%   |
| 5.4.0-52-generic            | 2         | 1.03%   |
| 5.4.0-29-generic            | 2         | 1.03%   |
| 5.4.0-26-generic            | 2         | 1.03%   |
| 5.4.0-21-generic            | 2         | 1.03%   |
| 5.3.0-40-generic            | 2         | 1.03%   |
| 5.3.0-28-generic            | 2         | 1.03%   |
| 5.15.0-27-generic           | 2         | 1.03%   |
| 5.15.0-25-generic           | 2         | 1.03%   |
| 5.13.0-35-generic           | 2         | 1.03%   |
| 5.13.0-20-generic           | 2         | 1.03%   |
| 5.11.0-16-generic           | 2         | 1.03%   |
| 4.19.0-8-amd64              | 2         | 1.03%   |
| 4.15.0-112-generic          | 2         | 1.03%   |
| 5.9.9-arch1-1               | 1         | 0.51%   |
| 5.9.14-arch1-1              | 1         | 0.51%   |
| 5.9.11-3-MANJARO            | 1         | 0.51%   |
| 5.8.6-1-MANJARO             | 1         | 0.51%   |
| 5.8.0-55-generic            | 1         | 0.51%   |
| 5.8.0-53-generic            | 1         | 0.51%   |
| 5.8.0-41-generic            | 1         | 0.51%   |
| 5.8.0-34-generic            | 1         | 0.51%   |
| 5.7.0-2parrot2-amd64        | 1         | 0.51%   |
| 5.7.0-1-amd64               | 1         | 0.51%   |
| 5.6.19-300.fc32.x86_64      | 1         | 0.51%   |
| 5.6.16-300.fc32.x86_64      | 1         | 0.51%   |
| 5.6.14-desktop-2bP          | 1         | 0.51%   |
| 5.6.13-arch1-1              | 1         | 0.51%   |
| 5.4.40-generic-1rosa-x86_64 | 1         | 0.51%   |
| 5.4.0-91-generic            | 1         | 0.51%   |
| 5.4.0-88-lowlatency         | 1         | 0.51%   |
| 5.4.0-88-generic            | 1         | 0.51%   |
| 5.4.0-74-generic            | 1         | 0.51%   |
| 5.4.0-73-generic            | 1         | 0.51%   |
| 5.4.0-72-generic            | 1         | 0.51%   |
| 5.4.0-65-generic            | 1         | 0.51%   |
| 5.4.0-64-generic            | 1         | 0.51%   |
| 5.4.0-60-generic            | 1         | 0.51%   |
| 5.4.0-58-generic            | 1         | 0.51%   |
| 5.4.0-56-generic            | 1         | 0.51%   |
| 5.4.0-51-generic            | 1         | 0.51%   |
| 5.4.0-48-lowlatency         | 1         | 0.51%   |
| 5.4.0-48-generic            | 1         | 0.51%   |
| 5.4.0-47-generic            | 1         | 0.51%   |
| 5.4.0-45-generic            | 1         | 0.51%   |
| 5.4.0-37-generic            | 1         | 0.51%   |
| 5.4.0-31-generic            | 1         | 0.51%   |
| 5.4.0-25-generic            | 1         | 0.51%   |
| 5.4.0-110-generic           | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 36        | 19.89%  |
| 5.10.14  | 16        | 8.84%   |
| 5.11.0   | 15        | 8.29%   |
| 4.15.0   | 11        | 6.08%   |
| 5.3.0    | 10        | 5.52%   |
| 5.8.0    | 9         | 4.97%   |
| 5.13.0   | 9         | 4.97%   |
| 5.0.0    | 9         | 4.97%   |
| 5.15.0   | 7         | 3.87%   |
| 5.16.7   | 6         | 3.31%   |
| 5.10.0   | 6         | 3.31%   |
| 4.19.0   | 3         | 1.66%   |
| 5.9.16   | 2         | 1.1%    |
| 5.7.0    | 2         | 1.1%    |
| 4.18.0   | 2         | 1.1%    |
| 5.9.9    | 1         | 0.55%   |
| 5.9.14   | 1         | 0.55%   |
| 5.9.11   | 1         | 0.55%   |
| 5.8.6    | 1         | 0.55%   |
| 5.6.19   | 1         | 0.55%   |
| 5.6.16   | 1         | 0.55%   |
| 5.6.14   | 1         | 0.55%   |
| 5.6.13   | 1         | 0.55%   |
| 5.4.40   | 1         | 0.55%   |
| 5.2.11   | 1         | 0.55%   |
| 5.17.9   | 1         | 0.55%   |
| 5.15.23  | 1         | 0.55%   |
| 5.15.13  | 1         | 0.55%   |
| 5.15.11  | 1         | 0.55%   |
| 5.14.14  | 1         | 0.55%   |
| 5.14.0   | 1         | 0.55%   |
| 5.13.9   | 1         | 0.55%   |
| 5.12.6   | 1         | 0.55%   |
| 5.12.15  | 1         | 0.55%   |
| 5.12.0   | 1         | 0.55%   |
| 5.11.5   | 1         | 0.55%   |
| 5.11.12  | 1         | 0.55%   |
| 5.11.11  | 1         | 0.55%   |
| 5.11.1   | 1         | 0.55%   |
| 5.10.94  | 1         | 0.55%   |
| 5.10.9   | 1         | 0.55%   |
| 5.10.7   | 1         | 0.55%   |
| 5.10.63  | 1         | 0.55%   |
| 5.10.35  | 1         | 0.55%   |
| 5.10.26  | 1         | 0.55%   |
| 5.10.2   | 1         | 0.55%   |
| 5.10.105 | 1         | 0.55%   |
| 5.0.15   | 1         | 0.55%   |
| 4.9.111  | 1         | 0.55%   |
| 4.19.96  | 1         | 0.55%   |
| 4.18.11  | 1         | 0.55%   |
| 4.1.38   | 1         | 0.55%   |
| 4.1.34   | 1         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 37        | 20.56%  |
| 5.10    | 29        | 16.11%  |
| 5.11    | 19        | 10.56%  |
| 4.15    | 11        | 6.11%   |
| 5.8     | 10        | 5.56%   |
| 5.3     | 10        | 5.56%   |
| 5.15    | 10        | 5.56%   |
| 5.13    | 10        | 5.56%   |
| 5.0     | 10        | 5.56%   |
| 5.16    | 6         | 3.33%   |
| 5.9     | 5         | 2.78%   |
| 5.6     | 4         | 2.22%   |
| 4.19    | 4         | 2.22%   |
| 5.12    | 3         | 1.67%   |
| 4.18    | 3         | 1.67%   |
| 5.7     | 2         | 1.11%   |
| 5.14    | 2         | 1.11%   |
| 4.1     | 2         | 1.11%   |
| 5.2     | 1         | 0.56%   |
| 5.17    | 1         | 0.56%   |
| 4.9     | 1         | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 151       | 96.18%  |
| i686   | 5         | 3.18%   |
| armv7l | 1         | 0.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 62        | 38.75%  |
| KDE5          | 30        | 18.75%  |
| Unknown       | 19        | 11.88%  |
| XFCE          | 12        | 7.5%    |
| X-Cinnamon    | 7         | 4.38%   |
| LXQt          | 7         | 4.38%   |
| MATE          | 5         | 3.13%   |
| KDE           | 4         | 2.5%    |
| Unity         | 2         | 1.25%   |
| Pantheon      | 2         | 1.25%   |
| LXDE          | 2         | 1.25%   |
| i3            | 2         | 1.25%   |
| Deepin        | 2         | 1.25%   |
| Cinnamon      | 2         | 1.25%   |
| Openbox       | 1         | 0.63%   |
| GNOME Classic | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 129       | 82.17%  |
| Wayland | 17        | 10.83%  |
| Unknown | 8         | 5.1%    |
| Tty     | 3         | 1.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 45.68%  |
| SDDM    | 40        | 24.69%  |
| LightDM | 15        | 9.26%   |
| GDM     | 15        | 9.26%   |
| TDM     | 11        | 6.79%   |
| GDM3    | 7         | 4.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 67        | 41.61%  |
| es_CR   | 60        | 37.27%  |
| Unknown | 19        | 11.8%   |
| es_ES   | 9         | 5.59%   |
| C       | 3         | 1.86%   |
| es_MX   | 1         | 0.62%   |
| en_GB   | 1         | 0.62%   |
| de_DE   | 1         | 0.62%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 83        | 51.88%  |
| BIOS | 77        | 48.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 122       | 75.78%  |
| Overlay | 24        | 14.91%  |
| Btrfs   | 8         | 4.97%   |
| Unknown | 5         | 3.11%   |
| Xfs     | 2         | 1.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 51.9%   |
| GPT     | 55        | 34.81%  |
| MBR     | 21        | 13.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 86.88%  |
| Yes       | 21        | 13.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 96        | 60.38%  |
| Yes       | 63        | 39.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 33        | 21.02%  |
| Hewlett-Packard         | 29        | 18.47%  |
| ASUSTek Computer        | 17        | 10.83%  |
| Lenovo                  | 14        | 8.92%   |
| Toshiba                 | 9         | 5.73%   |
| Gigabyte Technology     | 8         | 5.1%    |
| Acer                    | 7         | 4.46%   |
| MSI                     | 6         | 3.82%   |
| Apple                   | 6         | 3.82%   |
| ASRock                  | 5         | 3.18%   |
| Unknown                 | 3         | 1.91%   |
| Intel                   | 2         | 1.27%   |
| ZOTAC                   | 1         | 0.64%   |
| TPV-INVENTA             | 1         | 0.64%   |
| System76                | 1         | 0.64%   |
| Supermicro              | 1         | 0.64%   |
| Sony                    | 1         | 0.64%   |
| Samsung Electronics     | 1         | 0.64%   |
| Raspberry Pi Foundation | 1         | 0.64%   |
| Purism                  | 1         | 0.64%   |
| Pegatron                | 1         | 0.64%   |
| Olivetti                | 1         | 0.64%   |
| Microsoft               | 1         | 0.64%   |
| HUAWEI                  | 1         | 0.64%   |
| Google                  | 1         | 0.64%   |
| Gateway                 | 1         | 0.64%   |
| Biostar                 | 1         | 0.64%   |
| AZW                     | 1         | 0.64%   |
| Alienware               | 1         | 0.64%   |
| ABIT                    | 1         | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell OptiPlex 3020                       | 5         | 3.18%   |
| Apple MacBookPro8,1                      | 4         | 2.55%   |
| Unknown                                  | 4         | 2.55%   |
| Dell Inspiron 5584                       | 3         | 1.91%   |
| HP ProBook 6460b                         | 2         | 1.27%   |
| HP Pavilion Notebook                     | 2         | 1.27%   |
| HP Notebook                              | 2         | 1.27%   |
| HP Laptop 15-da0xxx                      | 2         | 1.27%   |
| Gigabyte B250M-DS3H                      | 2         | 1.27%   |
| ASUS PRIME A320M-K                       | 2         | 1.27%   |
| ASRock B450 Steel Legend                 | 2         | 1.27%   |
| ZOTAC NM10                               | 1         | 0.64%   |
| TPV-INVENTA 18-2003LA                    | 1         | 0.64%   |
| Toshiba Satellite X205                   | 1         | 0.64%   |
| Toshiba Satellite L45-B                  | 1         | 0.64%   |
| Toshiba Satellite C855D                  | 1         | 0.64%   |
| Toshiba Satellite C845                   | 1         | 0.64%   |
| Toshiba Satellite C645D                  | 1         | 0.64%   |
| Toshiba Satellite C55-B                  | 1         | 0.64%   |
| Toshiba Satellite C45-A                  | 1         | 0.64%   |
| Toshiba Satellite A305D                  | 1         | 0.64%   |
| Toshiba QOSMIO X775                      | 1         | 0.64%   |
| System76 Lemur                           | 1         | 0.64%   |
| Supermicro X9DAi                         | 1         | 0.64%   |
| Sony SVD13215PLB                         | 1         | 0.64%   |
| Samsung 930QAA                           | 1         | 0.64%   |
| RPi Raspberry Pi 3 Model B Plus Rev 1.3  | 1         | 0.64%   |
| Purism Librem 15 v3                      | 1         | 0.64%   |
| Pegatron CQ2728LA                        | 1         | 0.64%   |
| Olivetti CL133A                          | 1         | 0.64%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1         | 0.64%   |
| MSI MS-7B86                              | 1         | 0.64%   |
| MSI MS-7693                              | 1         | 0.64%   |
| MSI MS-7636                              | 1         | 0.64%   |
| MSI GF75 Thin 9SD                        | 1         | 0.64%   |
| MSI GE60 2OC\2OD\2OE                     | 1         | 0.64%   |
| Microsoft Surface with Windows 8 Pro     | 1         | 0.64%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1EY00 | 1         | 0.64%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 0.64%   |
| Lenovo ThinkPad T440s 20ARS29U00         | 1         | 0.64%   |
| Lenovo ThinkPad P53 20QNS00P00           | 1         | 0.64%   |
| Lenovo ThinkPad L420 7829AA4             | 1         | 0.64%   |
| Lenovo ThinkPad L15 Gen 2 20X4S8YL00     | 1         | 0.64%   |
| Lenovo ThinkPad L14 Gen 1 20U1001TUS     | 1         | 0.64%   |
| Lenovo ThinkPad E15 Gen 2 20T8005BUS     | 1         | 0.64%   |
| Lenovo IdeaPadFlex 4-1480 80VD           | 1         | 0.64%   |
| Lenovo IdeaPad S340-15API 81NC           | 1         | 0.64%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 0.64%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 1         | 0.64%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 1         | 0.64%   |
| Lenovo H530S 10132                       | 1         | 0.64%   |
| Intel DG41WV AAE90316-103                | 1         | 0.64%   |
| Intel D33217CK G76541-302                | 1         | 0.64%   |
| HUAWEI NBLK-WAX9X                        | 1         | 0.64%   |
| HP Z800 Workstation                      | 1         | 0.64%   |
| HP ProDesk 600 G4 SFF                    | 1         | 0.64%   |
| HP ProBook 455 G4                        | 1         | 0.64%   |
| HP ProBook 450 G2                        | 1         | 0.64%   |
| HP Pavilion Laptop 15-cc1xx              | 1         | 0.64%   |
| HP Pavilion g4                           | 1         | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 10        | 6.37%   |
| Toshiba Satellite     | 8         | 5.1%    |
| Lenovo ThinkPad       | 8         | 5.1%    |
| Dell OptiPlex         | 8         | 5.1%    |
| HP Pavilion           | 7         | 4.46%   |
| Dell Inspiron         | 7         | 4.46%   |
| HP Laptop             | 5         | 3.18%   |
| Acer Aspire           | 5         | 3.18%   |
| Lenovo IdeaPad        | 4         | 2.55%   |
| HP ProBook            | 4         | 2.55%   |
| Dell Precision        | 4         | 2.55%   |
| Apple MacBookPro8     | 4         | 2.55%   |
| Unknown               | 4         | 2.55%   |
| HP EliteBook          | 3         | 1.91%   |
| ASUS VivoBook         | 3         | 1.91%   |
| ASUS PRIME            | 3         | 1.91%   |
| HP Notebook           | 2         | 1.27%   |
| Gigabyte B250M-DS3H   | 2         | 1.27%   |
| Dell XPS              | 2         | 1.27%   |
| ASUS TUF              | 2         | 1.27%   |
| ASUS STRIX            | 2         | 1.27%   |
| ASRock B450           | 2         | 1.27%   |
| ZOTAC NM10            | 1         | 0.64%   |
| TPV-INVENTA 18-2003LA | 1         | 0.64%   |
| Toshiba QOSMIO        | 1         | 0.64%   |
| System76 Lemur        | 1         | 0.64%   |
| Supermicro X9DAi      | 1         | 0.64%   |
| Sony SVD13215PLB      | 1         | 0.64%   |
| Samsung 930QAA        | 1         | 0.64%   |
| RPi Raspberry         | 1         | 0.64%   |
| Purism Librem         | 1         | 0.64%   |
| Pegatron CQ2728LA     | 1         | 0.64%   |
| Olivetti CL133A       | 1         | 0.64%   |
| MSI Z390              | 1         | 0.64%   |
| MSI MS-7B86           | 1         | 0.64%   |
| MSI MS-7693           | 1         | 0.64%   |
| MSI MS-7636           | 1         | 0.64%   |
| MSI GF75              | 1         | 0.64%   |
| MSI GE60              | 1         | 0.64%   |
| Microsoft Surface     | 1         | 0.64%   |
| Lenovo IdeaPadFlex    | 1         | 0.64%   |
| Lenovo H530S          | 1         | 0.64%   |
| Intel DG41WV          | 1         | 0.64%   |
| Intel D33217CK        | 1         | 0.64%   |
| HUAWEI NBLK-WAX9X     | 1         | 0.64%   |
| HP Z800               | 1         | 0.64%   |
| HP ProDesk            | 1         | 0.64%   |
| HP OMEN               | 1         | 0.64%   |
| HP EliteDesk          | 1         | 0.64%   |
| HP 245                | 1         | 0.64%   |
| HP 240                | 1         | 0.64%   |
| HP 20-e003la          | 1         | 0.64%   |
| Google Celes          | 1         | 0.64%   |
| Gigabyte Z690         | 1         | 0.64%   |
| Gigabyte Z170X-Gaming | 1         | 0.64%   |
| Gigabyte X570         | 1         | 0.64%   |
| Gigabyte H110M-S2     | 1         | 0.64%   |
| Gigabyte H110M-H      | 1         | 0.64%   |
| Gigabyte GA-970A-D3   | 1         | 0.64%   |
| Gateway LX6810-01     | 1         | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 22        | 14.01%  |
| 2018    | 17        | 10.83%  |
| 2014    | 16        | 10.19%  |
| 2011    | 14        | 8.92%   |
| 2016    | 12        | 7.64%   |
| 2013    | 12        | 7.64%   |
| 2020    | 11        | 7.01%   |
| 2017    | 10        | 6.37%   |
| 2012    | 10        | 6.37%   |
| 2008    | 7         | 4.46%   |
| 2015    | 6         | 3.82%   |
| 2010    | 4         | 2.55%   |
| 2007    | 4         | 2.55%   |
| 2021    | 3         | 1.91%   |
| 2009    | 3         | 1.91%   |
| 2006    | 2         | 1.27%   |
| 2005    | 2         | 1.27%   |
| 2022    | 1         | 0.64%   |
| Unknown | 1         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 96        | 61.15%  |
| Desktop        | 53        | 33.76%  |
| All in one     | 3         | 1.91%   |
| Convertible    | 2         | 1.27%   |
| System on chip | 1         | 0.64%   |
| Tablet         | 1         | 0.64%   |
| Server         | 1         | 0.64%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 145       | 92.36%  |
| Enabled  | 12        | 7.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 155       | 98.73%  |
| Yes  | 2         | 1.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 37        | 23.27%  |
| 8.01-16.0       | 36        | 22.64%  |
| 4.01-8.0        | 33        | 20.75%  |
| 16.01-24.0      | 31        | 19.5%   |
| 32.01-64.0      | 9         | 5.66%   |
| 1.01-2.0        | 5         | 3.14%   |
| 2.01-3.0        | 4         | 2.52%   |
| More than 256.0 | 1         | 0.63%   |
| 24.01-32.0      | 1         | 0.63%   |
| 64.01-256.0     | 1         | 0.63%   |
| 0.51-1.0        | 1         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 77        | 44.77%  |
| 2.01-3.0   | 39        | 22.67%  |
| 4.01-8.0   | 19        | 11.05%  |
| 3.01-4.0   | 18        | 10.47%  |
| 0.51-1.0   | 10        | 5.81%   |
| 0.01-0.5   | 4         | 2.33%   |
| 8.01-16.0  | 3         | 1.74%   |
| 24.01-32.0 | 1         | 0.58%   |
| 16.01-24.0 | 1         | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 113       | 70.19%  |
| 2      | 32        | 19.88%  |
| 3      | 8         | 4.97%   |
| 4      | 6         | 3.73%   |
| 8      | 1         | 0.62%   |
| 5      | 1         | 0.62%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 55.06%  |
| Yes       | 71        | 44.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 140       | 89.17%  |
| No        | 17        | 10.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 77.85%  |
| No        | 35        | 22.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 55.63%  |
| No        | 71        | 44.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Costa Rica | 157       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San José     | 62        | 36.26%  |
| Heredia       | 39        | 22.81%  |
| Alajuela      | 14        | 8.19%   |
| Cartago       | 6         | 3.51%   |
| Quesada       | 4         | 2.34%   |
| Escazu        | 4         | 2.34%   |
| Grecia        | 3         | 1.75%   |
| Siquirres     | 2         | 1.17%   |
| Santa Fe      | 2         | 1.17%   |
| Santa Cruz    | 2         | 1.17%   |
| San Ramon     | 2         | 1.17%   |
| San Pedro     | 2         | 1.17%   |
| Palmares      | 2         | 1.17%   |
| Nosara        | 2         | 1.17%   |
| Naranjo       | 2         | 1.17%   |
| Liberia       | 2         | 1.17%   |
| Esparza       | 2         | 1.17%   |
| Curridabat    | 2         | 1.17%   |
| Zarcero       | 1         | 0.58%   |
| Tres Rios     | 1         | 0.58%   |
| Tibas         | 1         | 0.58%   |
| Santo Domingo | 1         | 0.58%   |
| Santiago      | 1         | 0.58%   |
| Santa Ana     | 1         | 0.58%   |
| San Pablo     | 1         | 0.58%   |
| San Juan      | 1         | 0.58%   |
| San Francisco | 1         | 0.58%   |
| Quepos        | 1         | 0.58%   |
| Puntarenas    | 1         | 0.58%   |
| Guacima       | 1         | 0.58%   |
| Colon         | 1         | 0.58%   |
| Bajo Perez    | 1         | 0.58%   |
| Bagaces       | 1         | 0.58%   |
| Alpes         | 1         | 0.58%   |
| Alajuelita    | 1         | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 35        | 45     | 16.75%  |
| Seagate               | 34        | 61     | 16.27%  |
| Toshiba               | 24        | 29     | 11.48%  |
| Samsung Electronics   | 17        | 30     | 8.13%   |
| A-DATA Technology     | 14        | 14     | 6.7%    |
| Kingston              | 12        | 18     | 5.74%   |
| Intel                 | 10        | 15     | 4.78%   |
| HGST                  | 9         | 10     | 4.31%   |
| Unknown               | 8         | 12     | 3.83%   |
| Hitachi               | 6         | 9      | 2.87%   |
| XPG                   | 4         | 4      | 1.91%   |
| SanDisk               | 4         | 5      | 1.91%   |
| Crucial               | 4         | 4      | 1.91%   |
| SK Hynix              | 3         | 8      | 1.44%   |
| Micron Technology     | 3         | 3      | 1.44%   |
| ZOTAC                 | 2         | 3      | 0.96%   |
| Team                  | 2         | 2      | 0.96%   |
| Realtek Semiconductor | 2         | 3      | 0.96%   |
| Patriot               | 2         | 2      | 0.96%   |
| MAXTOR                | 2         | 2      | 0.96%   |
| LITEONIT              | 2         | 2      | 0.96%   |
| JMicron               | 2         | 2      | 0.96%   |
| Zheino                | 1         | 1      | 0.48%   |
| WD MediaMax           | 1         | 1      | 0.48%   |
| UMIS                  | 1         | 1      | 0.48%   |
| Transcend             | 1         | 1      | 0.48%   |
| Silicon Motion        | 1         | 1      | 0.48%   |
| Fujitsu               | 1         | 1      | 0.48%   |
| Dell                  | 1         | 1      | 0.48%   |
| Apple                 | 1         | 2      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 6         | 2.65%   |
| A-DATA SU630 480GB SSD               | 6         | 2.65%   |
| Toshiba MQ01ABD100 1TB               | 5         | 2.21%   |
| Toshiba MQ01ABF050 500GB             | 4         | 1.77%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 3         | 1.33%   |
| WDC WD10EZEX-75WN4A1 1TB             | 3         | 1.33%   |
| Toshiba KBG30ZMS256G NVMe 256GB      | 3         | 1.33%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 1.33%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 1.33%   |
| Intel SSDSA2CW300G3 304GB            | 3         | 1.33%   |
| XPG GAMMIX S11 Pro 256GB             | 2         | 0.88%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 0.88%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 2         | 0.88%   |
| Toshiba DT01ACA100 1TB               | 2         | 0.88%   |
| SK Hynix NVMe SSD Drive 128GB        | 2         | 0.88%   |
| Seagate ST8000DM004-2CX188 8TB       | 2         | 0.88%   |
| Seagate ST380815AS 80GB              | 2         | 0.88%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 0.88%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.88%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 0.88%   |
| Samsung NVMe SSD Drive 256GB         | 2         | 0.88%   |
| JMicron Generic 128GB                | 2         | 0.88%   |
| Intel SSDSC2MH250A2 250GB            | 2         | 0.88%   |
| Intel SSDSC2BF180A4H 180GB           | 2         | 0.88%   |
| HGST HTS541075A9E680 752GB           | 2         | 0.88%   |
| HGST HTS541010A9E680 1TB             | 2         | 0.88%   |
| A-DATA SU650 120GB SSD               | 2         | 0.88%   |
| ZOTAC ZTSSD-S11-240G-P 240GB         | 1         | 0.44%   |
| ZOTAC ZTSSD-S11-120G-MD 120GB        | 1         | 0.44%   |
| Zheino CHN 25SATAA3 240 240GB        | 1         | 0.44%   |
| XPG NVMe SSD Drive 512GB             | 1         | 0.44%   |
| XPG NVMe SSD Drive 1TB               | 1         | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.44%   |
| WDC WDS120G1G0B-00RC30 120GB SSD     | 1         | 0.44%   |
| WDC WD800BEVT-75ZCT2 80GB            | 1         | 0.44%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 0.44%   |
| WDC WD6400AAKS-22A7B0 640GB          | 1         | 0.44%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.44%   |
| WDC WD5000LPCX-21VHAT0 500GB         | 1         | 0.44%   |
| WDC WD5000BPKT-60PK4T0 500GB         | 1         | 0.44%   |
| WDC WD5000AAKS-00V1A0 500GB          | 1         | 0.44%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.44%   |
| WDC WD2500AAJS-00VTA0 250GB          | 1         | 0.44%   |
| WDC WD20SPZX-08UA7 2TB               | 1         | 0.44%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.44%   |
| WDC WD1600BEVT-75A23T0 160GB         | 1         | 0.44%   |
| WDC WD1600BEVS-26VAT0 160GB          | 1         | 0.44%   |
| WDC WD1500HLFS-01G6U0 150GB          | 1         | 0.44%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.44%   |
| WDC WD10SPZX-24Z10T0 1TB             | 1         | 0.44%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.44%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.44%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.44%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.44%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1         | 0.44%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 0.44%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.44%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 1         | 0.44%   |
| WD MediaMax WL3000GSA6472 3TB        | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 32        | 59     | 32.65%  |
| WDC     | 28        | 32     | 28.57%  |
| Toshiba | 19        | 20     | 19.39%  |
| HGST    | 9         | 10     | 9.18%   |
| Hitachi | 6         | 9      | 6.12%   |
| MAXTOR  | 2         | 2      | 2.04%   |
| Fujitsu | 1         | 1      | 1.02%   |
| Apple   | 1         | 1      | 1.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 12        | 12     | 17.65%  |
| Kingston            | 11        | 13     | 16.18%  |
| Samsung Electronics | 10        | 19     | 14.71%  |
| Intel               | 8         | 12     | 11.76%  |
| WDC                 | 5         | 10     | 7.35%   |
| Crucial             | 4         | 4      | 5.88%   |
| SanDisk             | 3         | 4      | 4.41%   |
| Micron Technology   | 3         | 3      | 4.41%   |
| ZOTAC               | 2         | 3      | 2.94%   |
| Team                | 2         | 2      | 2.94%   |
| Patriot             | 2         | 2      | 2.94%   |
| LITEONIT            | 2         | 2      | 2.94%   |
| JMicron             | 2         | 2      | 2.94%   |
| Transcend           | 1         | 1      | 1.47%   |
| Seagate             | 1         | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 89        | 134    | 45.88%  |
| SSD     | 65        | 90     | 33.51%  |
| NVMe    | 30        | 53     | 15.46%  |
| MMC     | 7         | 11     | 3.61%   |
| Unknown | 3         | 4      | 1.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 140       | 217    | 76.09%  |
| NVMe | 30        | 53     | 16.3%   |
| SAS  | 7         | 11     | 3.8%    |
| MMC  | 7         | 11     | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 96        | 123    | 60%     |
| 0.51-1.0   | 51        | 78     | 31.88%  |
| 1.01-2.0   | 7         | 9      | 4.38%   |
| 4.01-10.0  | 5         | 13     | 3.13%   |
| 3.01-4.0   | 1         | 1      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 44        | 26.19%  |
| 251-500        | 30        | 17.86%  |
| 501-1000       | 25        | 14.88%  |
| 1-20           | 20        | 11.9%   |
| 51-100         | 17        | 10.12%  |
| 1001-2000      | 11        | 6.55%   |
| More than 3000 | 9         | 5.36%   |
| 21-50          | 5         | 2.98%   |
| Unknown        | 4         | 2.38%   |
| 2001-3000      | 3         | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 80        | 45.98%  |
| 21-50          | 27        | 15.52%  |
| 101-250        | 19        | 10.92%  |
| 51-100         | 15        | 8.62%   |
| 251-500        | 14        | 8.05%   |
| 501-1000       | 6         | 3.45%   |
| More than 3000 | 4         | 2.3%    |
| Unknown        | 4         | 2.3%    |
| 1001-2000      | 3         | 1.72%   |
| 2001-3000      | 2         | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 6.67%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 6.67%   |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 6.67%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 6.67%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 2      | 6.67%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 6.67%   |
| MAXTOR STM3160215AS 160GB                           | 1         | 1      | 6.67%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 6.67%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 6.67%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 6.67%   |
| Hitachi HDE721010SLA330 1TB                         | 1         | 1      | 6.67%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 6.67%   |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 3         | 3      | 20%     |
| WDC               | 2         | 2      | 13.33%  |
| Hitachi           | 2         | 3      | 13.33%  |
| HGST              | 2         | 2      | 13.33%  |
| Seagate           | 1         | 2      | 6.67%   |
| SanDisk           | 1         | 1      | 6.67%   |
| Micron Technology | 1         | 1      | 6.67%   |
| MAXTOR            | 1         | 1      | 6.67%   |
| Kingston          | 1         | 1      | 6.67%   |
| Intel             | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 27.27%  |
| WDC     | 2         | 2      | 18.18%  |
| Hitachi | 2         | 3      | 18.18%  |
| HGST    | 2         | 2      | 18.18%  |
| Seagate | 1         | 2      | 9.09%   |
| MAXTOR  | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 13     | 73.33%  |
| SSD  | 4         | 4      | 26.67%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 90        | 170    | 53.57%  |
| Works    | 63        | 105    | 37.5%   |
| Malfunc  | 15        | 17     | 8.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 117       | 61.26%  |
| AMD                          | 31        | 16.23%  |
| Samsung Electronics          | 8         | 4.19%   |
| ASMedia Technology           | 5         | 2.62%   |
| ADATA Technology             | 5         | 2.62%   |
| Toshiba America Info Systems | 4         | 2.09%   |
| Realtek Semiconductor        | 4         | 2.09%   |
| SK Hynix                     | 3         | 1.57%   |
| Sandisk                      | 3         | 1.57%   |
| Nvidia                       | 2         | 1.05%   |
| Union Memory (Shenzhen)      | 1         | 0.52%   |
| Silicon Motion               | 1         | 0.52%   |
| Silicon Image                | 1         | 0.52%   |
| OCZ Technology Group         | 1         | 0.52%   |
| Marvell Technology Group     | 1         | 0.52%   |
| LSI Logic / Symbios Logic    | 1         | 0.52%   |
| Kingston Technology Company  | 1         | 0.52%   |
| JMicron Technology           | 1         | 0.52%   |
| Apple                        | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 21        | 9.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 11        | 5.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 5.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 11        | 5.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 4.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 3.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 6         | 2.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 2.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 6         | 2.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 2.33%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 5         | 2.33%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 5         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 1.86%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 1.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 1.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 1.4%    |
| Intel SATA Controller [RAID mode]                                                      | 3         | 1.4%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 1.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 3         | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                                 | 3         | 1.4%    |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 0.93%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 2         | 0.93%   |
| Realtek Realtek Non-Volatile memory controller                                         | 2         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 0.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 2         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 2         | 0.93%   |
| AMD FCH SATA Controller D                                                              | 2         | 0.93%   |
| AMD 500 Series Chipset SATA Controller                                                 | 2         | 0.93%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.47%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                   | 1         | 0.47%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                            | 1         | 0.47%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.47%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                   | 1         | 0.47%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.47%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 0.47%   |
| OCZ Group RD400/400A SSD                                                               | 1         | 0.47%   |
| Nvidia MCP79 RAID Controller                                                           | 1         | 0.47%   |
| Nvidia MCP67 IDE Controller                                                            | 1         | 0.47%   |
| Nvidia MCP67 AHCI Controller                                                           | 1         | 0.47%   |
| Marvell Group 88SE912x IDE Controller                                                  | 1         | 0.47%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                           | 1         | 0.47%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                          | 1         | 0.47%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.47%   |
| JMicron JMB368 IDE controller                                                          | 1         | 0.47%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.47%   |
| Intel Non-Volatile memory controller                                                   | 1         | 0.47%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 0.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 122       | 62.56%  |
| NVMe | 31        | 15.9%   |
| IDE  | 24        | 12.31%  |
| RAID | 16        | 8.21%   |
| SAS  | 1         | 0.51%   |
| SCSI | 1         | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 122       | 77.71%  |
| AMD    | 34        | 21.66%  |
| ARM    | 1         | 0.64%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz                | 5         | 3.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 4         | 2.55%   |
| AMD Ryzen 5 3600 6-Core Processor               | 4         | 2.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 3         | 1.91%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 3         | 1.91%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 3         | 1.91%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 3         | 1.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.27%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 1.27%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 2         | 1.27%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 1.27%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 2         | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.27%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 1.27%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 2         | 1.27%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 2         | 1.27%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 2         | 1.27%   |
| AMD E1-1200 APU with Radeon HD Graphics         | 2         | 1.27%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 2         | 1.27%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz            | 1         | 0.64%   |
| Intel Xeon CPU X5667 @ 3.07GHz                  | 1         | 0.64%   |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1         | 0.64%   |
| Intel Xeon CPU E5405 @ 2.00GHz                  | 1         | 0.64%   |
| Intel Xeon CPU E5-2660 v2 @ 2.20GHz             | 1         | 0.64%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz     | 1         | 0.64%   |
| Intel Pentium CPU G3260 @ 3.30GHz               | 1         | 0.64%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1         | 0.64%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.64%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1         | 0.64%   |
| Intel Genuine CPU U4100 @ 1.30GHz               | 1         | 0.64%   |
| Intel Genuine CPU T2060 @ 1.60GHz               | 1         | 0.64%   |
| Intel Core i9-9900KF CPU @ 3.60GHz              | 1         | 0.64%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.64%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 1         | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.64%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 0.64%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 0.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 0.64%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.64%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 0.64%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 0.64%   |
| Intel Core i7-2630QM CPU @ 2.00GHz              | 1         | 0.64%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 1         | 0.64%   |
| Intel Core i5-8500 CPU @ 3.00GHz                | 1         | 0.64%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 1         | 0.64%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 1         | 0.64%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 1         | 0.64%   |
| Intel Core i5-6500T CPU @ 2.50GHz               | 1         | 0.64%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1         | 0.64%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1         | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 0.64%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 1         | 0.64%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1         | 0.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1         | 0.64%   |
| Intel Core i5-4300Y CPU @ 1.60GHz               | 1         | 0.64%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 36        | 22.93%  |
| Intel Core i7                  | 31        | 19.75%  |
| Intel Core i3                  | 16        | 10.19%  |
| Intel Celeron                  | 13        | 8.28%   |
| AMD Ryzen 5                    | 8         | 5.1%    |
| AMD Ryzen 7                    | 5         | 3.18%   |
| Other                          | 4         | 2.55%   |
| Intel Xeon                     | 4         | 2.55%   |
| Intel Core 2 Duo               | 4         | 2.55%   |
| AMD FX                         | 4         | 2.55%   |
| AMD E1                         | 4         | 2.55%   |
| Intel Pentium                  | 3         | 1.91%   |
| Intel Core 2                   | 3         | 1.91%   |
| AMD Ryzen 3                    | 3         | 1.91%   |
| Intel Genuine                  | 2         | 1.27%   |
| Intel Atom                     | 2         | 1.27%   |
| AMD A8                         | 2         | 1.27%   |
| AMD A10                        | 2         | 1.27%   |
| Intel Xeon Silver              | 1         | 0.64%   |
| Intel Pentium Dual-Core        | 1         | 0.64%   |
| Intel Pentium 4                | 1         | 0.64%   |
| Intel Core i9                  | 1         | 0.64%   |
| Intel Core 2 Quad              | 1         | 0.64%   |
| ARM BCM                        | 1         | 0.64%   |
| AMD V120                       | 1         | 0.64%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.64%   |
| AMD Turion 64 X2               | 1         | 0.64%   |
| AMD Ryzen 7 PRO                | 1         | 0.64%   |
| AMD E2                         | 1         | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 79        | 50.32%  |
| 4      | 52        | 33.12%  |
| 6      | 12        | 7.64%   |
| 8      | 6         | 3.82%   |
| 1      | 4         | 2.55%   |
| 10     | 2         | 1.27%   |
| 20     | 1         | 0.64%   |
| 3      | 1         | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 155       | 98.73%  |
| 2      | 2         | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 92        | 58.6%   |
| 1      | 65        | 41.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 152       | 96.2%   |
| Unknown        | 4         | 2.53%   |
| 32-bit         | 2         | 1.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 15.53%  |
| 0x206a7    | 12        | 7.45%   |
| 0x306c3    | 11        | 6.83%   |
| 0x40651    | 7         | 4.35%   |
| 0x806e9    | 6         | 3.73%   |
| 0x306a9    | 6         | 3.73%   |
| 0x08108109 | 6         | 3.73%   |
| 0x906e9    | 5         | 3.11%   |
| 0x906ea    | 4         | 2.48%   |
| 0x806ec    | 4         | 2.48%   |
| 0x706a1    | 4         | 2.48%   |
| 0x406c4    | 4         | 2.48%   |
| 0x306d4    | 4         | 2.48%   |
| 0x08701021 | 4         | 2.48%   |
| 0x806eb    | 3         | 1.86%   |
| 0x506e3    | 3         | 1.86%   |
| 0x406e3    | 3         | 1.86%   |
| 0x05000119 | 3         | 1.86%   |
| 0x806ea    | 2         | 1.24%   |
| 0x706a8    | 2         | 1.24%   |
| 0x6fd      | 2         | 1.24%   |
| 0x6f6      | 2         | 1.24%   |
| 0x30678    | 2         | 1.24%   |
| 0x20655    | 2         | 1.24%   |
| 0x1067a    | 2         | 1.24%   |
| 0x10676    | 2         | 1.24%   |
| 0x07030105 | 2         | 1.24%   |
| 0x06000852 | 2         | 1.24%   |
| 0xf49      | 1         | 0.62%   |
| 0xf29      | 1         | 0.62%   |
| 0x906ed    | 1         | 0.62%   |
| 0x906ec    | 1         | 0.62%   |
| 0x906eb    | 1         | 0.62%   |
| 0x90672    | 1         | 0.62%   |
| 0x806c1    | 1         | 0.62%   |
| 0x6ec      | 1         | 0.62%   |
| 0x50654    | 1         | 0.62%   |
| 0x306e4    | 1         | 0.62%   |
| 0x106e5    | 1         | 0.62%   |
| 0x106ca    | 1         | 0.62%   |
| 0x106a5    | 1         | 0.62%   |
| 0x10677    | 1         | 0.62%   |
| 0x08701011 | 1         | 0.62%   |
| 0x0870100a | 1         | 0.62%   |
| 0x08600106 | 1         | 0.62%   |
| 0x08600104 | 1         | 0.62%   |
| 0x08600103 | 1         | 0.62%   |
| 0x0800820d | 1         | 0.62%   |
| 0x07000110 | 1         | 0.62%   |
| 0x06006118 | 1         | 0.62%   |
| 0x0500010d | 1         | 0.62%   |
| 0x03000027 | 1         | 0.62%   |
| 0x02000057 | 1         | 0.62%   |
| 0x010000c8 | 1         | 0.62%   |
| 0x00000000 | 1         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 31        | 19.75%  |
| Haswell         | 20        | 12.74%  |
| SandyBridge     | 16        | 10.19%  |
| Zen+            | 8         | 5.1%    |
| Zen 2           | 8         | 5.1%    |
| Skylake         | 8         | 5.1%    |
| IvyBridge       | 7         | 4.46%   |
| Silvermont      | 6         | 3.82%   |
| Penryn          | 6         | 3.82%   |
| Goldmont plus   | 6         | 3.82%   |
| Core            | 5         | 3.18%   |
| Broadwell       | 4         | 2.55%   |
| Westmere        | 3         | 1.91%   |
| Piledriver      | 3         | 1.91%   |
| Excavator       | 3         | 1.91%   |
| Bobcat          | 3         | 1.91%   |
| TigerLake       | 2         | 1.27%   |
| Puma            | 2         | 1.27%   |
| NetBurst        | 2         | 1.27%   |
| Nehalem         | 2         | 1.27%   |
| Unknown         | 2         | 1.27%   |
| Zen 3           | 1         | 0.64%   |
| P6              | 1         | 0.64%   |
| K8 Hammer       | 1         | 0.64%   |
| K8 & K10 hybrid | 1         | 0.64%   |
| K10 Llano       | 1         | 0.64%   |
| K10             | 1         | 0.64%   |
| Jaguar          | 1         | 0.64%   |
| IceLake         | 1         | 0.64%   |
| Bulldozer       | 1         | 0.64%   |
| Bonnell         | 1         | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 102       | 58.29%  |
| Nvidia | 37        | 21.14%  |
| AMD    | 36        | 20.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 7.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 4.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 3.28%   |
| Intel HD Graphics 620                                                                    | 6         | 3.28%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 3.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.73%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.19%   |
| Intel HD Graphics 630                                                                    | 4         | 2.19%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.19%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.64%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.64%   |
| AMD Renoir                                                                               | 3         | 1.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.09%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2         | 1.09%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.09%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 1.09%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2         | 1.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.09%   |
| Intel HD Graphics 530                                                                    | 2         | 1.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.09%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 1.09%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 1.09%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.09%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.09%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.09%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 1.09%   |
| Nvidia TU117M                                                                            | 1         | 0.55%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.55%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.55%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.55%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1         | 0.55%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 0.55%   |
| Nvidia GT218 [ION]                                                                       | 1         | 0.55%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.55%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1         | 0.55%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.55%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.55%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.55%   |
| Nvidia GK106 [GeForce GTX 645 OEM]                                                       | 1         | 0.55%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1         | 0.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.55%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.55%   |
| Nvidia G96C [GeForce GT 120]                                                             | 1         | 0.55%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 0.55%   |
| Nvidia G71GL [Quadro FX 3500]                                                            | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 87        | 55.06%  |
| 1 x AMD        | 27        | 17.09%  |
| 1 x Nvidia     | 22        | 13.92%  |
| Intel + Nvidia | 12        | 7.59%   |
| 2 x AMD        | 4         | 2.53%   |
| AMD + Nvidia   | 3         | 1.9%    |
| Intel + AMD    | 2         | 1.27%   |
| Other          | 1         | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 138       | 86.79%  |
| Proprietary | 18        | 11.32%  |
| Unknown     | 3         | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 97        | 60.25%  |
| 1.01-2.0   | 21        | 13.04%  |
| 0.01-0.5   | 15        | 9.32%   |
| 0.51-1.0   | 11        | 6.83%   |
| 3.01-4.0   | 10        | 6.21%   |
| 5.01-6.0   | 6         | 3.73%   |
| 7.01-8.0   | 1         | 0.62%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 13.59%  |
| AOC                     | 21        | 11.41%  |
| Samsung Electronics     | 18        | 9.78%   |
| LG Display              | 18        | 9.78%   |
| Chimei Innolux          | 15        | 8.15%   |
| Hewlett-Packard         | 11        | 5.98%   |
| Goldstar                | 10        | 5.43%   |
| Dell                    | 10        | 5.43%   |
| BOE                     | 9         | 4.89%   |
| Apple                   | 6         | 3.26%   |
| ViewSonic               | 3         | 1.63%   |
| Sony                    | 3         | 1.63%   |
| Chi Mei Optoelectronics | 3         | 1.63%   |
| BenQ                    | 3         | 1.63%   |
| Acer                    | 3         | 1.63%   |
| Sharp                   | 2         | 1.09%   |
| Panasonic               | 2         | 1.09%   |
| CPT                     | 2         | 1.09%   |
| ASUSTek Computer        | 2         | 1.09%   |
| Ancor Communications    | 2         | 1.09%   |
| Xerox                   | 1         | 0.54%   |
| Unknown (XXX)           | 1         | 0.54%   |
| Royal Information       | 1         | 0.54%   |
| Philips                 | 1         | 0.54%   |
| PAR                     | 1         | 0.54%   |
| MSI                     | 1         | 0.54%   |
| LTM                     | 1         | 0.54%   |
| LG Philips              | 1         | 0.54%   |
| Lenovo                  | 1         | 0.54%   |
| KDC                     | 1         | 0.54%   |
| Hitachi                 | 1         | 0.54%   |
| Haier                   | 1         | 0.54%   |
| GAOMON                  | 1         | 0.54%   |
| Envision                | 1         | 0.54%   |
| CVT                     | 1         | 0.54%   |
| AGO                     | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                          | 5         | 2.66%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                  | 4         | 2.13%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3         | 1.6%    |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                     | 3         | 1.6%    |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch          | 3         | 1.6%    |
| Sony TV SNY0902 1360x768                                                | 2         | 1.06%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch    | 2         | 1.06%   |
| Panasonic TV MEIA296 1360x768                                           | 2         | 1.06%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch            | 2         | 1.06%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch             | 2         | 1.06%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 476x268mm 21.5-inch              | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch         | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch         | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 2         | 1.06%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                          | 2         | 1.06%   |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                      | 1         | 0.53%   |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch               | 1         | 0.53%   |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                              | 1         | 0.53%   |
| ViewSonic LCD Monitor VX2260WM                                          | 1         | 0.53%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1         | 0.53%   |
| Sony TV SNY1B02 1360x768 1600x900mm 72.3-inch                           | 1         | 0.53%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                 | 1         | 0.53%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                 | 1         | 0.53%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM058A 1920x1080 531x298mm 24.0-inch    | 1         | 0.53%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC345A 1366x768 309x174mm 14.0-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1420x800mm 64.2-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch   | 1         | 0.53%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 0.53%   |
| Royal Information Monitor TRL1012 1280x1024 320x240mm 15.7-inch         | 1         | 0.53%   |
| Philips LCD Monitor 170B4 1280x1024                                     | 1         | 0.53%   |
| PAR PAR1366X768 PAR1444 1366x768 344x193mm 15.5-inch                    | 1         | 0.53%   |
| MSI MAG271CQP MSI3FA7 2560x1440 597x336mm 27.0-inch                     | 1         | 0.53%   |
| LTM LCD_VGA LTM0659 1024x768 880x500mm 39.8-inch                        | 1         | 0.53%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch            | 1         | 0.53%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch            | 1         | 0.53%   |
| LG Display LCD Monitor LGD05E6 1920x1080 344x194mm 15.5-inch            | 1         | 0.53%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch            | 1         | 0.53%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD0454 1366x768 310x174mm 14.0-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 63        | 35.8%   |
| 1366x768 (WXGA)   | 49        | 27.84%  |
| 3840x2160 (4K)    | 13        | 7.39%   |
| 1600x900 (HD+)    | 11        | 6.25%   |
| 1280x800 (WXGA)   | 10        | 5.68%   |
| 1280x1024 (SXGA)  | 8         | 4.55%   |
| 1440x900 (WXGA+)  | 7         | 3.98%   |
| 3286x1080         | 2         | 1.14%   |
| 2560x1440 (QHD)   | 2         | 1.14%   |
| 2560x1080         | 2         | 1.14%   |
| 1360x768          | 2         | 1.14%   |
| 1280x720 (HD)     | 2         | 1.14%   |
| Unknown           | 2         | 1.14%   |
| 1920x1200 (WUXGA) | 1         | 0.57%   |
| 1280x960          | 1         | 0.57%   |
| 1024x768 (XGA)    | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 45        | 24.73%  |
| 14      | 21        | 11.54%  |
| 13      | 21        | 11.54%  |
| 23      | 13        | 7.14%   |
| 19      | 13        | 7.14%   |
| 24      | 11        | 6.04%   |
| 17      | 10        | 5.49%   |
| 21      | 8         | 4.4%    |
| 18      | 8         | 4.4%    |
| Unknown | 7         | 3.85%   |
| 84      | 4         | 2.2%    |
| 27      | 4         | 2.2%    |
| 72      | 3         | 1.65%   |
| 43      | 2         | 1.1%    |
| 34      | 2         | 1.1%    |
| 32      | 2         | 1.1%    |
| 31      | 2         | 1.1%    |
| 12      | 2         | 1.1%    |
| 54      | 1         | 0.55%   |
| 40      | 1         | 0.55%   |
| 39      | 1         | 0.55%   |
| 10      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 83        | 45.6%   |
| 501-600     | 28        | 15.38%  |
| 401-500     | 26        | 14.29%  |
| 201-300     | 11        | 6.04%   |
| 351-400     | 9         | 4.95%   |
| 1501-2000   | 7         | 3.85%   |
| Unknown     | 7         | 3.85%   |
| 701-800     | 4         | 2.2%    |
| 801-900     | 2         | 1.1%    |
| 601-700     | 2         | 1.1%    |
| 901-1000    | 2         | 1.1%    |
| 1001-1500   | 1         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 122       | 76.73%  |
| 16/10   | 19        | 11.95%  |
| 5/4     | 7         | 4.4%    |
| Unknown | 7         | 4.4%    |
| 4/3     | 2         | 1.26%   |
| 21/9    | 2         | 1.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 44        | 24.18%  |
| 81-90          | 39        | 21.43%  |
| 201-250        | 25        | 13.74%  |
| 151-200        | 15        | 8.24%   |
| 141-150        | 12        | 6.59%   |
| More than 1000 | 8         | 4.4%    |
| Unknown        | 7         | 3.85%   |
| 351-500        | 6         | 3.3%    |
| 251-300        | 5         | 2.75%   |
| 71-80          | 4         | 2.2%    |
| 301-350        | 4         | 2.2%    |
| 121-130        | 4         | 2.2%    |
| 501-1000       | 4         | 2.2%    |
| 131-140        | 2         | 1.1%    |
| 61-70          | 1         | 0.55%   |
| 41-50          | 1         | 0.55%   |
| 111-120        | 1         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 58        | 32.95%  |
| 51-100        | 57        | 32.39%  |
| 121-160       | 39        | 22.16%  |
| 1-50          | 8         | 4.55%   |
| Unknown       | 7         | 3.98%   |
| 161-240       | 6         | 3.41%   |
| More than 240 | 1         | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 133       | 80.12%  |
| 2     | 29        | 17.47%  |
| 0     | 3         | 1.81%   |
| 3     | 1         | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 92        | 39.15%  |
| Intel                    | 59        | 25.11%  |
| Qualcomm Atheros         | 37        | 15.74%  |
| Broadcom                 | 17        | 7.23%   |
| TP-Link                  | 6         | 2.55%   |
| Broadcom Limited         | 6         | 2.55%   |
| Xiaomi                   | 3         | 1.28%   |
| Ralink                   | 2         | 0.85%   |
| Nvidia                   | 2         | 0.85%   |
| Linksys                  | 2         | 0.85%   |
| Standard Microsystems    | 1         | 0.43%   |
| Ralink Technology        | 1         | 0.43%   |
| Marvell Technology Group | 1         | 0.43%   |
| JMicron Technology       | 1         | 0.43%   |
| Huawei Technologies      | 1         | 0.43%   |
| DisplayLink              | 1         | 0.43%   |
| Dell                     | 1         | 0.43%   |
| D-Link                   | 1         | 0.43%   |
| ASIX Electronics         | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 58        | 20.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 19        | 6.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 7         | 2.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 7         | 2.43%   |
| Intel Wireless 7265                                                                           | 6         | 2.08%   |
| Intel Wireless 7260                                                                           | 6         | 2.08%   |
| Intel Wi-Fi 6 AX200                                                                           | 6         | 2.08%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 5         | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5         | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 5         | 1.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 4         | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 4         | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 1.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4         | 1.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                             | 4         | 1.39%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 4         | 1.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 3         | 1.04%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 3         | 1.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3         | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 3         | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 3         | 1.04%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 1.04%   |
| Intel Ethernet Connection I218-LM                                                             | 3         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                                         | 3         | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 3         | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 1.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 2         | 0.69%   |
| Realtek 802.11ac NIC                                                                          | 2         | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2         | 0.69%   |
| Intel Wireless 3160                                                                           | 2         | 0.69%   |
| Intel Ethernet Controller I225-V                                                              | 2         | 0.69%   |
| Intel Ethernet Connection I217-LM                                                             | 2         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                                                         | 2         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                                         | 2         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 0.69%   |
| Intel Centrino Advanced-N 6235                                                                | 2         | 0.69%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                                             | 2         | 0.69%   |
| Broadcom Limited BCM4311 802.11a/b/g                                                          | 2         | 0.69%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                         | 1         | 0.35%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 0.35%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1         | 0.35%   |
| Standard Microsystems Ethernet controller                                                     | 1         | 0.35%   |
| Realtek USB 10/100/1G/2.5G LAN                                                                | 1         | 0.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 0.35%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.35%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.35%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1         | 0.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                                    | 1         | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1         | 0.35%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.35%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.35%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.35%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 44        | 33.59%  |
| Qualcomm Atheros      | 30        | 22.9%   |
| Realtek Semiconductor | 27        | 20.61%  |
| Broadcom              | 11        | 8.4%    |
| TP-Link               | 6         | 4.58%   |
| Broadcom Limited      | 6         | 4.58%   |
| Ralink                | 2         | 1.53%   |
| Linksys               | 2         | 1.53%   |
| Ralink Technology     | 1         | 0.76%   |
| Dell                  | 1         | 0.76%   |
| D-Link                | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 7         | 5.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 7         | 5.26%   |
| Intel Wireless 7265                                                                           | 6         | 4.51%   |
| Intel Wireless 7260                                                                           | 6         | 4.51%   |
| Intel Wi-Fi 6 AX200                                                                           | 6         | 4.51%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 5         | 3.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5         | 3.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 5         | 3.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 4         | 3.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 3.01%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 4         | 3.01%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                                     | 3         | 2.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3         | 2.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 3         | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 2.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 2.26%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 2.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 3         | 2.26%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.5%    |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2         | 1.5%    |
| Realtek 802.11ac NIC                                                                          | 2         | 1.5%    |
| Intel Wireless 3160                                                                           | 2         | 1.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 1.5%    |
| Intel Centrino Advanced-N 6235                                                                | 2         | 1.5%    |
| Broadcom Limited BCM4311 802.11a/b/g                                                          | 2         | 1.5%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                         | 1         | 0.75%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 0.75%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1         | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1         | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.75%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1         | 0.75%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.75%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.75%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.75%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.75%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express)         | 1         | 0.75%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.75%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 0.75%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]                                | 1         | 0.75%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                                     | 1         | 0.75%   |
| Intel Wireless-AC 9260                                                                        | 1         | 0.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 1         | 0.75%   |
| Intel Centrino Wireless-N 6150                                                                | 1         | 0.75%   |
| Intel Centrino Wireless-N 2230                                                                | 1         | 0.75%   |
| Intel Centrino Wireless-N + WiMAX 6150                                                        | 1         | 0.75%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1         | 0.75%   |
| Dell Wireless 5808e Gobiâ¢ 4G LTE Mobile Broadband Card                                   | 1         | 0.75%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                                | 1         | 0.75%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                                    | 1         | 0.75%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                                       | 1         | 0.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                     | 1         | 0.75%   |
| Broadcom Limited BCM4311 802.11b/g WLAN                                                       | 1         | 0.75%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                                   | 1         | 0.75%   |
| Broadcom BCM43227 802.11b/g/n                                                                 | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 84        | 56.38%  |
| Intel                    | 32        | 21.48%  |
| Broadcom                 | 12        | 8.05%   |
| Qualcomm Atheros         | 10        | 6.71%   |
| Xiaomi                   | 3         | 2.01%   |
| Nvidia                   | 2         | 1.34%   |
| Standard Microsystems    | 1         | 0.67%   |
| Marvell Technology Group | 1         | 0.67%   |
| JMicron Technology       | 1         | 0.67%   |
| Huawei Technologies      | 1         | 0.67%   |
| DisplayLink              | 1         | 0.67%   |
| ASIX Electronics         | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58        | 37.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 12.26%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 2.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.94%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.29%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.29%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.29%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.29%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.29%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.29%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.29%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 1.29%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.65%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.65%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.65%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.65%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.65%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.65%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.65%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.65%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.65%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.65%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.65%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.65%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.65%   |
| Intel 82801DB PRO/100 VE (CNR) Ethernet Controller                | 1         | 0.65%   |
| Intel 82599 10 Gigabit Network Connection                         | 1         | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.65%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.65%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1         | 0.65%   |
| Huawei E353/E3131                                                 | 1         | 0.65%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.65%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.65%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.65%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.65%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.65%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.65%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 0.65%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.65%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 140       | 53.23%  |
| WiFi     | 123       | 46.77%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 96        | 58.18%  |
| Ethernet | 69        | 41.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 101       | 63.92%  |
| 1     | 48        | 30.38%  |
| 3     | 5         | 3.16%   |
| 0     | 3         | 1.9%    |
| 4     | 1         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 157       | 99.37%  |
| Yes  | 1         | 0.63%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 38.46%  |
| Qualcomm Atheros Communications | 13        | 14.29%  |
| Realtek Semiconductor           | 12        | 13.19%  |
| Cambridge Silicon Radio         | 7         | 7.69%   |
| Broadcom                        | 6         | 6.59%   |
| Apple                           | 6         | 6.59%   |
| Toshiba                         | 2         | 2.2%    |
| IMC Networks                    | 2         | 2.2%    |
| ASUSTek Computer                | 2         | 2.2%    |
| Realtek                         | 1         | 1.1%    |
| Marvell Semiconductor           | 1         | 1.1%    |
| Lite-On Technology              | 1         | 1.1%    |
| Hewlett-Packard                 | 1         | 1.1%    |
| Foxconn / Hon Hai               | 1         | 1.1%    |
| Dell                            | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                           | 15        | 16.48%  |
| Qualcomm Atheros  Bluetooth Device                           | 9         | 9.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 7         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 7         | 7.69%   |
| Realtek  Bluetooth 4.2 Adapter                               | 6         | 6.59%   |
| Realtek Bluetooth Radio                                      | 6         | 6.59%   |
| Intel AX200 Bluetooth                                        | 6         | 6.59%   |
| Apple Bluetooth Host Controller                              | 4         | 4.4%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                       | 3         | 3.3%    |
| Intel Centrino Bluetooth Wireless Transceiver                | 3         | 3.3%    |
| Broadcom BCM43142A0 Bluetooth 4.0                            | 3         | 3.3%    |
| Toshiba Bluetooth Device                                     | 2         | 2.2%    |
| Intel Wireless-AC 3168 Bluetooth                             | 2         | 2.2%    |
| Realtek Bluetooth Radio                                      | 1         | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                            | 1         | 1.1%    |
| Marvell Bluetooth and Wireless LAN Composite Device          | 1         | 1.1%    |
| Lite-On Bluetooth Device                                     | 1         | 1.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 1         | 1.1%    |
| Intel AX201 Bluetooth                                        | 1         | 1.1%    |
| IMC Networks Bluetooth Radio                                 | 1         | 1.1%    |
| IMC Networks Bluetooth                                       | 1         | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                             | 1         | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                           | 1         | 1.1%    |
| Dell Broadcom BCM20702A0 Bluetooth                           | 1         | 1.1%    |
| Broadcom HP Portable SoftSailing                             | 1         | 1.1%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                         | 1         | 1.1%    |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1         | 1.1%    |
| ASUS Qualcomm Bluetooth 4.1                                  | 1         | 1.1%    |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 1         | 1.1%    |
| Apple Bluetooth USB Host Controller                          | 1         | 1.1%    |
| Apple Bluetooth HCI                                          | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 118       | 57.28%  |
| AMD                     | 41        | 19.9%   |
| Nvidia                  | 27        | 13.11%  |
| Generalplus Technology  | 3         | 1.46%   |
| C-Media Electronics     | 3         | 1.46%   |
| Logitech                | 2         | 0.97%   |
| JMTek                   | 2         | 0.97%   |
| Realtek Semiconductor   | 1         | 0.49%   |
| Plantronics             | 1         | 0.49%   |
| Lenovo                  | 1         | 0.49%   |
| GN Netcom               | 1         | 0.49%   |
| Corsair                 | 1         | 0.49%   |
| CMX Systems             | 1         | 0.49%   |
| Blue Microphones        | 1         | 0.49%   |
| BEHRINGER International | 1         | 0.49%   |
| Argosy research         | 1         | 0.49%   |
| Afatech                 | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 6.45%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 5.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 4.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 4.03%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 4.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 2.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 2.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 2.42%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 2.42%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.42%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 2.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.02%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.61%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.61%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.21%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.21%   |
| Generalplus Technology Usb Audio Device                                                           | 3         | 1.21%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 1.21%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.81%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.81%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.81%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.81%   |
| Realtek Semiconductor TX-Hifi Type_C Audio                                                        | 1         | 0.4%    |
| Plantronics Blackwire 3225 Series                                                                 | 1         | 0.4%    |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.4%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.4%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.4%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.4%    |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Logitech Headset H390                                                                             | 1         | 0.4%    |
| Logitech AudioHub Speaker                                                                         | 1         | 0.4%    |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 1         | 0.4%    |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.4%    |
| JMTek LCS USB Audio                                                                               | 1         | 0.4%    |
| Intel Lewisburg MROM 0                                                                            | 1         | 0.4%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.4%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.4%    |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.4%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 24.53%  |
| Kingston            | 18        | 16.98%  |
| SK Hynix            | 16        | 15.09%  |
| Micron Technology   | 15        | 14.15%  |
| Corsair             | 7         | 6.6%    |
| A-DATA Technology   | 5         | 4.72%   |
| Unknown             | 4         | 3.77%   |
| Team                | 4         | 3.77%   |
| Crucial             | 4         | 3.77%   |
| Nanya Technology    | 3         | 2.83%   |
| Patriot             | 2         | 1.89%   |
| Kimtigo             | 1         | 0.94%   |
| G.Skill             | 1         | 0.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s      | 5         | 4.07%   |
| Team RAM TEAMGROUP-SD4-2666 16384MB SODIMM DDR4 2667MT/s    | 4         | 3.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 3         | 2.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 3         | 2.44%   |
| Kingston RAM 9905584-015.A00LF 4096MB DIMM DDR3 1600MT/s    | 3         | 2.44%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s                 | 3         | 2.44%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s                 | 3         | 2.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s               | 2         | 1.63%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.63%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 1.63%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s   | 2         | 1.63%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 1.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 1.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 1.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 1.63%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s        | 2         | 1.63%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 2         | 1.63%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s        | 2         | 1.63%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                 | 1         | 0.81%   |
| Unknown RAM Module 8GB SODIMM DDR3                          | 1         | 0.81%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 1         | 0.81%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1867MT/s             | 1         | 0.81%   |
| SK Hynix RAM Module 16GB DIMM DDR4 2667MT/s                 | 1         | 0.81%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4096MB DIMM DDR3 1600MT/s     | 1         | 0.81%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s     | 1         | 0.81%   |
| SK Hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s   | 1         | 0.81%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s     | 1         | 0.81%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s        | 1         | 0.81%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.81%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s   | 1         | 0.81%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 1         | 0.81%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 1         | 0.81%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s   | 1         | 0.81%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s      | 1         | 0.81%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s       | 1         | 0.81%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s      | 1         | 0.81%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s    | 1         | 0.81%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s       | 1         | 0.81%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.81%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s    | 1         | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s | 1         | 0.81%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s       | 1         | 0.81%   |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s    | 1         | 0.81%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 1         | 0.81%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 1         | 0.81%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 1         | 0.81%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s         | 1         | 0.81%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s         | 1         | 0.81%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s        | 1         | 0.81%   |
| Patriot RAM PSD48G266681S 8GB SODIMM DDR4 2667MT/s          | 1         | 0.81%   |
| Patriot RAM PSD48G266681 8192MB DIMM DDR4 2934MT/s          | 1         | 0.81%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s        | 1         | 0.81%   |
| Micron RAM M391A1G43BB1-CRCB1 16GB SODIMM DDR4 2667MT/s     | 1         | 0.81%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.81%   |
| Micron RAM 8JTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s    | 1         | 0.81%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s        | 1         | 0.81%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s        | 1         | 0.81%   |
| Micron RAM 16JTF25664AZ-1G4F1 2GB DIMM 1333MT/s             | 1         | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 42        | 47.19%  |
| DDR3   | 38        | 42.7%   |
| SDRAM  | 4         | 4.49%   |
| DDR2   | 4         | 4.49%   |
| LPDDR4 | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 58        | 67.44%  |
| DIMM         | 25        | 29.07%  |
| Row Of Chips | 2         | 2.33%   |
| Chip         | 1         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 44        | 43.14%  |
| 8192  | 29        | 28.43%  |
| 2048  | 13        | 12.75%  |
| 16384 | 10        | 9.8%    |
| 32768 | 6         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 27        | 26.47%  |
| 2667    | 24        | 23.53%  |
| 1333    | 10        | 9.8%    |
| 3200    | 5         | 4.9%    |
| 2400    | 5         | 4.9%    |
| 667     | 5         | 4.9%    |
| 1334    | 4         | 3.92%   |
| 3266    | 3         | 2.94%   |
| 4199    | 2         | 1.96%   |
| 3600    | 2         | 1.96%   |
| 3466    | 2         | 1.96%   |
| 2933    | 2         | 1.96%   |
| 2133    | 2         | 1.96%   |
| Unknown | 2         | 1.96%   |
| 3100    | 1         | 0.98%   |
| 2934    | 1         | 0.98%   |
| 2800    | 1         | 0.98%   |
| 2666    | 1         | 0.98%   |
| 1867    | 1         | 0.98%   |
| 1800    | 1         | 0.98%   |
| 1067    | 1         | 0.98%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 3         | 37.5%   |
| Hewlett-Packard | 3         | 37.5%   |
| Canon           | 2         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L380 Series            | 1         | 12.5%   |
| Seiko Epson L3110 Series           | 1         | 12.5%   |
| Seiko Epson L222 Series            | 1         | 12.5%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 12.5%   |
| HP DeskJet 2130 series             | 1         | 12.5%   |
| HP Deskjet 2050 J510               | 1         | 12.5%   |
| Canon G2000 series                 | 1         | 12.5%   |
| Canon E400 series                  | 1         | 12.5%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 19.63%  |
| Microdia                               | 12        | 11.21%  |
| Realtek Semiconductor                  | 11        | 10.28%  |
| IMC Networks                           | 11        | 10.28%  |
| Logitech                               | 7         | 6.54%   |
| Apple                                  | 6         | 5.61%   |
| Microsoft                              | 5         | 4.67%   |
| Sunplus Innovation Technology          | 4         | 3.74%   |
| Suyin                                  | 3         | 2.8%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.8%    |
| Z-Star Microelectronics                | 2         | 1.87%   |
| Syntek                                 | 2         | 1.87%   |
| Quanta                                 | 2         | 1.87%   |
| Primax Electronics                     | 2         | 1.87%   |
| Luxvisions Innotech Limited            | 2         | 1.87%   |
| Lite-On Technology                     | 2         | 1.87%   |
| Alcor Micro                            | 2         | 1.87%   |
| Silicon Motion                         | 1         | 0.93%   |
| Philips (or NXP)                       | 1         | 0.93%   |
| LG Electronics                         | 1         | 0.93%   |
| Importek                               | 1         | 0.93%   |
| Huawei Technologies                    | 1         | 0.93%   |
| Creative Technology                    | 1         | 0.93%   |
| Aveo Technology                        | 1         | 0.93%   |
| Arkmicro Technologies                  | 1         | 0.93%   |
| Alpha Imaging Technology               | 1         | 0.93%   |
| Acer                                   | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                         | 8         | 7.27%   |
| IMC Networks Integrated Camera                        | 4         | 3.64%   |
| Chicony Integrated Camera                             | 4         | 3.64%   |
| Apple FaceTime HD Camera                              | 4         | 3.64%   |
| Realtek Integrated_Webcam_HD                          | 3         | 2.73%   |
| Microsoft LifeCam HD-3000                             | 3         | 2.73%   |
| Logitech Webcam C270                                  | 3         | 2.73%   |
| Syntek EasyCamera                                     | 2         | 1.82%   |
| Sunplus HD WebCam                                     | 2         | 1.82%   |
| Realtek Integrated Webcam HD                          | 2         | 1.82%   |
| Realtek Integrated Webcam                             | 2         | 1.82%   |
| Microdia Integrated Webcam                            | 2         | 1.82%   |
| IMC Networks USB2.0 VGA UVC WebCam                    | 2         | 1.82%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 2         | 1.82%   |
| Chicony USB 2.0 Camera                                | 2         | 1.82%   |
| Chicony TOSHIBA Web Camera - HD                       | 2         | 1.82%   |
| Chicony Integrated HP HD Webcam                       | 2         | 1.82%   |
| Chicony HP Truevision HD                              | 2         | 1.82%   |
| Chicony 720p HD Camera                                | 2         | 1.82%   |
| Z-Star Vimicro USB Camera (Altair)                    | 1         | 0.91%   |
| Z-Star Vega USB2.0 Camera                             | 1         | 0.91%   |
| Suyin TOSHIBA Web Camera - HD                         | 1         | 0.91%   |
| Suyin HP TrueVision HD                                | 1         | 0.91%   |
| Suyin 1.3M HD WebCam                                  | 1         | 0.91%   |
| Sunplus Laptop_Integrated_Webcam_HD                   | 1         | 0.91%   |
| Sunplus HP HD Webcam [Fixed]                          | 1         | 0.91%   |
| Silicon Motion Silicon Motion Camera                  | 1         | 0.91%   |
| Realtek USB Camera                                    | 1         | 0.91%   |
| Realtek Rear Camera                                   | 1         | 0.91%   |
| Realtek HP Wide Vision FHD Camera                     | 1         | 0.91%   |
| Realtek HP Truevision HD                              | 1         | 0.91%   |
| Realtek Front Camera                                  | 1         | 0.91%   |
| Quanta HP Webcam                                      | 1         | 0.91%   |
| Quanta HD Webcam                                      | 1         | 0.91%   |
| Primax webcam                                         | 1         | 0.91%   |
| Primax HP HD Webcam [Fixed]                           | 1         | 0.91%   |
| Philips (or NXP) SPC 1300NC PC Camera                 | 1         | 0.91%   |
| Microsoft Rear LifeCam                                | 1         | 0.91%   |
| Microsoft LifeCam Cinema                              | 1         | 0.91%   |
| Microsoft Front LifeCam                               | 1         | 0.91%   |
| Microdia USB 2.0 Camera                               | 1         | 0.91%   |
| Microdia Integrated Webcam HD                         | 1         | 0.91%   |
| Microdia Integrated Camera                            | 1         | 0.91%   |
| Luxvisions Innotech Limited Integrated Camera         | 1         | 0.91%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera   | 1         | 0.91%   |
| Logitech Webcam Pro 9000                              | 1         | 0.91%   |
| Logitech Webcam C925e                                 | 1         | 0.91%   |
| Logitech HD Pro Webcam C920                           | 1         | 0.91%   |
| Logitech BRIO Ultra HD Webcam                         | 1         | 0.91%   |
| Lite-On Integrated Camera                             | 1         | 0.91%   |
| Lite-On HP HD Webcam                                  | 1         | 0.91%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 0.91%   |
| Importek Laptop Integrated Webcam                     | 1         | 0.91%   |
| IMC Networks TOSHIBA Web Camera - HD                  | 1         | 0.91%   |
| IMC Networks ov9734_azurewave_camera                  | 1         | 0.91%   |
| IMC Networks Integrated Webcam                        | 1         | 0.91%   |
| Huawei UVC Camera                                     | 1         | 0.91%   |
| Creative VF0610 Live! Cam Socialize HD                | 1         | 0.91%   |
| Chicony VGA 30fps UVC Webcam                          | 1         | 0.91%   |
| Chicony HP TrueVision HD Camera                       | 1         | 0.91%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 47.37%  |
| Synaptics                  | 3         | 15.79%  |
| Shenzhen Goodix Technology | 2         | 10.53%  |
| STMicroelectronics         | 1         | 5.26%   |
| Samsung Electronics        | 1         | 5.26%   |
| LighTuning Technology      | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 3         | 15.79%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 10.53%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 10.53%  |
| Validity Sensors VFS491                           | 1         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 5.26%   |
| Validity Sensors Synaptics WBDI                   | 1         | 5.26%   |
| Validity Sensors Fingerprint scanner              | 1         | 5.26%   |
| STMicroelectronics Fingerprint Reader             | 1         | 5.26%   |
| Samsung Fingerprint Device                        | 1         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 5.26%   |
| Elan ELAN:ARM-M4                                  | 1         | 5.26%   |
| AuthenTec AES1600                                 | 1         | 5.26%   |
| Unknown                                           | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 4         | 33.33%  |
| O2 Micro                   | 3         | 25%     |
| Athena Smartcard Solutions | 3         | 25%     |
| OmniKey                    | 1         | 8.33%   |
| Alcor Micro                | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Athena Smartcard Solutions ASEDrive CCID                                     | 3         | 25%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 16.67%  |
| Broadcom 5880                                                                | 2         | 16.67%  |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 8.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Broadcom 58200                                                               | 1         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 111       | 68.1%   |
| 1     | 43        | 26.38%  |
| 2     | 5         | 3.07%   |
| 3     | 4         | 2.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 28.57%  |
| Net/wireless             | 14        | 22.22%  |
| Graphics card            | 11        | 17.46%  |
| Chipcard                 | 10        | 15.87%  |
| Communication controller | 3         | 4.76%   |
| Multimedia controller    | 2         | 3.17%   |
| Unassigned class         | 1         | 1.59%   |
| Sound                    | 1         | 1.59%   |
| Network                  | 1         | 1.59%   |
| Net/ethernet             | 1         | 1.59%   |
| Firewire controller      | 1         | 1.59%   |

